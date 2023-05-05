Manjaro - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

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

Total: 3832

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | A320M-S2H V2-CF             | [cf6a478eb1](https://linux-hardware.org/?probe=cf6a478eb1) | May 01, 2023 |
| ASRock        | B650 LiveMixer              | [aecb4b61b4](https://linux-hardware.org/?probe=aecb4b61b4) | May 01, 2023 |
| Shuttle       | DL20N                       | [3f97bcaa08](https://linux-hardware.org/?probe=3f97bcaa08) | Apr 30, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [2e2b57b3ae](https://linux-hardware.org/?probe=2e2b57b3ae) | Apr 30, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [e47ae2080c](https://linux-hardware.org/?probe=e47ae2080c) | Apr 29, 2023 |
| MSI           | B450M MORTAR MAX            | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| HP            | 845A                        | [d0aa2a4a7a](https://linux-hardware.org/?probe=d0aa2a4a7a) | Apr 29, 2023 |
| HP            | 845A                        | [f8bc4601ef](https://linux-hardware.org/?probe=f8bc4601ef) | Apr 29, 2023 |
| Pegatron      | Benicia                     | [930452646c](https://linux-hardware.org/?probe=930452646c) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [e8886a7521](https://linux-hardware.org/?probe=e8886a7521) | Apr 28, 2023 |
| Apple         | Mac-F221BEC8                | [3342a295e8](https://linux-hardware.org/?probe=3342a295e8) | Apr 28, 2023 |
| Dell          | 0200DY A02                  | [2499c633a5](https://linux-hardware.org/?probe=2499c633a5) | Apr 27, 2023 |
| Gigabyte      | H61MA-D3V                   | [3a1d89d5a0](https://linux-hardware.org/?probe=3a1d89d5a0) | Apr 27, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [6dec479f55](https://linux-hardware.org/?probe=6dec479f55) | Apr 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [a2875a31b2](https://linux-hardware.org/?probe=a2875a31b2) | Apr 25, 2023 |
| Biostar       | B450MX-S                    | [5ac7debff3](https://linux-hardware.org/?probe=5ac7debff3) | Apr 25, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [25ac3a297e](https://linux-hardware.org/?probe=25ac3a297e) | Apr 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [0e85243397](https://linux-hardware.org/?probe=0e85243397) | Apr 23, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [e5c6fc2738](https://linux-hardware.org/?probe=e5c6fc2738) | Apr 23, 2023 |
| HUAWEI        | PUM-WDX9-PCB-B1 M1060       | [2c8835f2e2](https://linux-hardware.org/?probe=2c8835f2e2) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [519c11a569](https://linux-hardware.org/?probe=519c11a569) | Apr 21, 2023 |
| MSI           | B450-A PRO MAX              | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Dell          | 0WN7Y6 A01                  | [cc1233b9b9](https://linux-hardware.org/?probe=cc1233b9b9) | Apr 21, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [15cc4335c7](https://linux-hardware.org/?probe=15cc4335c7) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | [b0b94f2462](https://linux-hardware.org/?probe=b0b94f2462) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | [d429a2c865](https://linux-hardware.org/?probe=d429a2c865) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5a9a6c553f](https://linux-hardware.org/?probe=5a9a6c553f) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | [f8519c5a20](https://linux-hardware.org/?probe=f8519c5a20) | Apr 20, 2023 |
| Gigabyte      | B550 GAMING X               | [a815ec2fa2](https://linux-hardware.org/?probe=a815ec2fa2) | Apr 19, 2023 |
| ASRock        | FM2A68M-DG3+                | [701110cf4e](https://linux-hardware.org/?probe=701110cf4e) | Apr 19, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [023e96a6fd](https://linux-hardware.org/?probe=023e96a6fd) | Apr 18, 2023 |
| Dell          | 0200DY A02                  | [6041b126fa](https://linux-hardware.org/?probe=6041b126fa) | Apr 18, 2023 |
| ASRock        | 970 Pro3 R2.0               | [e816e4de38](https://linux-hardware.org/?probe=e816e4de38) | Apr 18, 2023 |
| ASRock        | Z790 Taichi                 | [0d25cf28bc](https://linux-hardware.org/?probe=0d25cf28bc) | Apr 17, 2023 |
| MSI           | MS-B0A41                    | [5950f6e73c](https://linux-hardware.org/?probe=5950f6e73c) | Apr 17, 2023 |
| ASUSTek       | X99-PRO/USB                 | [058029e9f7](https://linux-hardware.org/?probe=058029e9f7) | Apr 17, 2023 |
| Dell          | 0P01GV A03                  | [ed2675881e](https://linux-hardware.org/?probe=ed2675881e) | Apr 17, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [286c8ef93c](https://linux-hardware.org/?probe=286c8ef93c) | Apr 16, 2023 |
| HP            | 158A                        | [56694ce9a3](https://linux-hardware.org/?probe=56694ce9a3) | Apr 16, 2023 |
| ASUSTek       | PRIME Z490-A                | [3924bb4eb5](https://linux-hardware.org/?probe=3924bb4eb5) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [2eb96e4d6e](https://linux-hardware.org/?probe=2eb96e4d6e) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [7d34909c86](https://linux-hardware.org/?probe=7d34909c86) | Apr 16, 2023 |
| HP            | 802E                        | [d6a1c8ad74](https://linux-hardware.org/?probe=d6a1c8ad74) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3a6ad12afa](https://linux-hardware.org/?probe=3a6ad12afa) | Apr 15, 2023 |
| ASUSTek       | GR6                         | [9cccf46449](https://linux-hardware.org/?probe=9cccf46449) | Apr 15, 2023 |
| MSI           | Z97 GAMING 5                | [988cd72346](https://linux-hardware.org/?probe=988cd72346) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [8aa8fd23c6](https://linux-hardware.org/?probe=8aa8fd23c6) | Apr 15, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | [c99626b458](https://linux-hardware.org/?probe=c99626b458) | Apr 14, 2023 |
| MSI           | B85-G43                     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Gigabyte      | F2A68HM-S1                  | [b5ce8ee6ec](https://linux-hardware.org/?probe=b5ce8ee6ec) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [bbc081e43e](https://linux-hardware.org/?probe=bbc081e43e) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [a59a28162e](https://linux-hardware.org/?probe=a59a28162e) | Apr 13, 2023 |
| Intel         | H61 V1.1                    | [1b97e4ffc5](https://linux-hardware.org/?probe=1b97e4ffc5) | Apr 12, 2023 |
| Intel         | H61 V1.1                    | [402a94b1c0](https://linux-hardware.org/?probe=402a94b1c0) | Apr 12, 2023 |
| Gigabyte      | X570S UD                    | [2d599510b8](https://linux-hardware.org/?probe=2d599510b8) | Apr 12, 2023 |
| Daten Tecn... | DH110MXV                    | [6a1c34f539](https://linux-hardware.org/?probe=6a1c34f539) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1429799ca6](https://linux-hardware.org/?probe=1429799ca6) | Apr 11, 2023 |
| HP            | 1495                        | [762886dcb0](https://linux-hardware.org/?probe=762886dcb0) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8b8b7e1e4e](https://linux-hardware.org/?probe=8b8b7e1e4e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [192ca29359](https://linux-hardware.org/?probe=192ca29359) | Apr 11, 2023 |
| Dell          | 0K240Y A01                  | [1daf1b0ff6](https://linux-hardware.org/?probe=1daf1b0ff6) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [1dad85ccf1](https://linux-hardware.org/?probe=1dad85ccf1) | Apr 10, 2023 |
| Intel         | H61 V1.1                    | [1c3cfd94a3](https://linux-hardware.org/?probe=1c3cfd94a3) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [6aae769b7a](https://linux-hardware.org/?probe=6aae769b7a) | Apr 09, 2023 |
| Intel         | H61 V1.1                    | [e553db41a3](https://linux-hardware.org/?probe=e553db41a3) | Apr 08, 2023 |
| Huanan        | X99-F8                      | [4b020d6c5a](https://linux-hardware.org/?probe=4b020d6c5a) | Apr 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | [15c7f69a52](https://linux-hardware.org/?probe=15c7f69a52) | Apr 07, 2023 |
| ASUSTek       | Z170M-PLUS                  | [be741560b8](https://linux-hardware.org/?probe=be741560b8) | Apr 06, 2023 |
| HP            | 21D0                        | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | [1190aa9be8](https://linux-hardware.org/?probe=1190aa9be8) | Apr 06, 2023 |
| HP            | 84FD                        | [7e80c3baf0](https://linux-hardware.org/?probe=7e80c3baf0) | Apr 05, 2023 |
| Gigabyte      | H61MA-D3V                   | [ba4ee67415](https://linux-hardware.org/?probe=ba4ee67415) | Apr 05, 2023 |
| ASUSTek       | X99-A II                    | [882dc981fb](https://linux-hardware.org/?probe=882dc981fb) | Apr 04, 2023 |
| Foxconn       | 2ADA                        | [0d1d784767](https://linux-hardware.org/?probe=0d1d784767) | Apr 04, 2023 |
| Dell          | 042P49 A02                  | [74a232499a](https://linux-hardware.org/?probe=74a232499a) | Apr 04, 2023 |
| MSI           | H81M-E34                    | [5e24c6a44a](https://linux-hardware.org/?probe=5e24c6a44a) | Apr 03, 2023 |
| MSI           | B450-A PRO                  | [c487bcedab](https://linux-hardware.org/?probe=c487bcedab) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| MSI           | GF615M-P33                  | [022324033e](https://linux-hardware.org/?probe=022324033e) | Apr 02, 2023 |
| ASRock        | B550M Pro4                  | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | [fe4d7e3bd0](https://linux-hardware.org/?probe=fe4d7e3bd0) | Apr 02, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [bb490db4a9](https://linux-hardware.org/?probe=bb490db4a9) | Apr 02, 2023 |
| ASRock        | B550 Taichi                 | [cff286981b](https://linux-hardware.org/?probe=cff286981b) | Apr 01, 2023 |
| ASRock        | B550 Taichi                 | [01517a396d](https://linux-hardware.org/?probe=01517a396d) | Apr 01, 2023 |
| HP            | 1495                        | [96ea87fbce](https://linux-hardware.org/?probe=96ea87fbce) | Apr 01, 2023 |
| MSI           | X570-A PRO                  | [3093c50d3d](https://linux-hardware.org/?probe=3093c50d3d) | Mar 31, 2023 |
| Intel         | H61 V1.1                    | [e670f092d7](https://linux-hardware.org/?probe=e670f092d7) | Mar 31, 2023 |
| ASRock        | H61M-HVS                    | [0672578da7](https://linux-hardware.org/?probe=0672578da7) | Mar 30, 2023 |
| Intel         | X99 V1.0                    | [13c66b0e69](https://linux-hardware.org/?probe=13c66b0e69) | Mar 30, 2023 |
| MSI           | H81M-E34                    | [ac06c6037f](https://linux-hardware.org/?probe=ac06c6037f) | Mar 30, 2023 |
| MSI           | X570-A PRO                  | [0921fd9096](https://linux-hardware.org/?probe=0921fd9096) | Mar 28, 2023 |
| ASRock        | B550 Taichi                 | [94d97c5e0c](https://linux-hardware.org/?probe=94d97c5e0c) | Mar 28, 2023 |
| Intel         | H61 V1.1                    | [497266ad29](https://linux-hardware.org/?probe=497266ad29) | Mar 28, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | [a45bc637c9](https://linux-hardware.org/?probe=a45bc637c9) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [aaae412a63](https://linux-hardware.org/?probe=aaae412a63) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Lenovo        | 30D2 NOK                    | [dc62baadff](https://linux-hardware.org/?probe=dc62baadff) | Mar 25, 2023 |
| MSI           | GF615M-P33                  | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Intel         | H61 V1.1                    | [e678dd580c](https://linux-hardware.org/?probe=e678dd580c) | Mar 25, 2023 |
| Dell          | 08NPPY A00                  | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4731c6e59f](https://linux-hardware.org/?probe=4731c6e59f) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [127173d60b](https://linux-hardware.org/?probe=127173d60b) | Mar 23, 2023 |
| Intel         | H61 V1.1                    | [f1292785cd](https://linux-hardware.org/?probe=f1292785cd) | Mar 23, 2023 |
| Dell          | 0X9M3X A01                  | [38f83864e4](https://linux-hardware.org/?probe=38f83864e4) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | [4b80817d4b](https://linux-hardware.org/?probe=4b80817d4b) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | [9c01b0ee80](https://linux-hardware.org/?probe=9c01b0ee80) | Mar 22, 2023 |
| Lenovo        | Dory CRB                    | [821914dc88](https://linux-hardware.org/?probe=821914dc88) | Mar 22, 2023 |
| ASUSTek       | Z170M-PLUS                  | [a1e76aa5c1](https://linux-hardware.org/?probe=a1e76aa5c1) | Mar 21, 2023 |
| MSI           | PRO B660M-A WIFI            | [2184cf01f3](https://linux-hardware.org/?probe=2184cf01f3) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [cd12accab0](https://linux-hardware.org/?probe=cd12accab0) | Mar 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [5eee23b1db](https://linux-hardware.org/?probe=5eee23b1db) | Mar 20, 2023 |
| ASUSTek       | PRIME Z370-P II             | [3b81f87409](https://linux-hardware.org/?probe=3b81f87409) | Mar 20, 2023 |
| ASRock        | X570 Taichi                 | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| ASRock        | B360M Pro4                  | [e5be65dd5e](https://linux-hardware.org/?probe=e5be65dd5e) | Mar 19, 2023 |
| HP            | 8056                        | [fa7f589aea](https://linux-hardware.org/?probe=fa7f589aea) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [add9634ad5](https://linux-hardware.org/?probe=add9634ad5) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [e2cfab15ef](https://linux-hardware.org/?probe=e2cfab15ef) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [75dd9244fb](https://linux-hardware.org/?probe=75dd9244fb) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | [8a94a38026](https://linux-hardware.org/?probe=8a94a38026) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | [31851c4e15](https://linux-hardware.org/?probe=31851c4e15) | Mar 18, 2023 |
| HP            | 1495                        | [d83e879ba0](https://linux-hardware.org/?probe=d83e879ba0) | Mar 18, 2023 |
| HP            | 1495                        | [b7b5d46ce0](https://linux-hardware.org/?probe=b7b5d46ce0) | Mar 18, 2023 |
| Dell          | 0GY6Y8 A01                  | [3b10072541](https://linux-hardware.org/?probe=3b10072541) | Mar 18, 2023 |
| HP            | 2B36                        | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| ASUSTek       | PRIME B450M-A               | [fbf7dd9d94](https://linux-hardware.org/?probe=fbf7dd9d94) | Mar 17, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [e41f82bcfd](https://linux-hardware.org/?probe=e41f82bcfd) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [d6def0b0aa](https://linux-hardware.org/?probe=d6def0b0aa) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [1a4e62a4a5](https://linux-hardware.org/?probe=1a4e62a4a5) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | [b34a55307e](https://linux-hardware.org/?probe=b34a55307e) | Mar 16, 2023 |
| Intel         | H61 V1.1                    | [175eb36378](https://linux-hardware.org/?probe=175eb36378) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | [73a4a38e57](https://linux-hardware.org/?probe=73a4a38e57) | Mar 15, 2023 |
| Intel         | H61 V1.1                    | [eaa24cb538](https://linux-hardware.org/?probe=eaa24cb538) | Mar 15, 2023 |
| MSI           | X570-A PRO                  | [c4be4f7d67](https://linux-hardware.org/?probe=c4be4f7d67) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [39ded01df5](https://linux-hardware.org/?probe=39ded01df5) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [529e83761c](https://linux-hardware.org/?probe=529e83761c) | Mar 14, 2023 |
| ASRock        | Z270 Gaming K6              | [3afad06d79](https://linux-hardware.org/?probe=3afad06d79) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [e1fc53bd25](https://linux-hardware.org/?probe=e1fc53bd25) | Mar 13, 2023 |
| ASUSTek       | B85M-G                      | [22ae0716b2](https://linux-hardware.org/?probe=22ae0716b2) | Mar 13, 2023 |
| Biostar       | A960D+V3                    | [e18f6a3a84](https://linux-hardware.org/?probe=e18f6a3a84) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [abb73d2e5f](https://linux-hardware.org/?probe=abb73d2e5f) | Mar 13, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [44fc80c7d5](https://linux-hardware.org/?probe=44fc80c7d5) | Mar 13, 2023 |
| Huanan        | X99-F8                      | [2bd21ce3b3](https://linux-hardware.org/?probe=2bd21ce3b3) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| ASUSTek       | PRIME B450M-K               | [d5a4dbf55c](https://linux-hardware.org/?probe=d5a4dbf55c) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | [ebb7252eb5](https://linux-hardware.org/?probe=ebb7252eb5) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | [74001bfcc3](https://linux-hardware.org/?probe=74001bfcc3) | Mar 12, 2023 |
| ASUSTek       | X99-PRO/USB                 | [f4d8b766a9](https://linux-hardware.org/?probe=f4d8b766a9) | Mar 12, 2023 |
| HP            | 212B                        | [0d3860ffc6](https://linux-hardware.org/?probe=0d3860ffc6) | Mar 11, 2023 |
| MSI           | X99A SLI PLUS               | [77566542fd](https://linux-hardware.org/?probe=77566542fd) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [e7682656f1](https://linux-hardware.org/?probe=e7682656f1) | Mar 11, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [b53c65e6c9](https://linux-hardware.org/?probe=b53c65e6c9) | Mar 10, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [29a2c22865](https://linux-hardware.org/?probe=29a2c22865) | Mar 09, 2023 |
| Gigabyte      | B550M DS3H                  | [dba3d6498b](https://linux-hardware.org/?probe=dba3d6498b) | Mar 09, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [add9ea7c34](https://linux-hardware.org/?probe=add9ea7c34) | Mar 09, 2023 |
| MSI           | B75MA-P45                   | [f066452d7d](https://linux-hardware.org/?probe=f066452d7d) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [4cc3cc4c17](https://linux-hardware.org/?probe=4cc3cc4c17) | Mar 08, 2023 |
| Dell          | 0TTDMJ A00                  | [3d321d8069](https://linux-hardware.org/?probe=3d321d8069) | Mar 07, 2023 |
| ASRock        | H97 Pro4                    | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| ASUSTek       | PRIME A520M-E               | [be51d02a20](https://linux-hardware.org/?probe=be51d02a20) | Mar 06, 2023 |
| ASRock        | AB350 Gaming K4             | [896ea5798f](https://linux-hardware.org/?probe=896ea5798f) | Mar 06, 2023 |
| HP            | 8597                        | [17c1e6efd7](https://linux-hardware.org/?probe=17c1e6efd7) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-A                | [859a660d90](https://linux-hardware.org/?probe=859a660d90) | Mar 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | [cb13decef3](https://linux-hardware.org/?probe=cb13decef3) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [ce8df757cc](https://linux-hardware.org/?probe=ce8df757cc) | Mar 04, 2023 |
| Biostar       | B450MX-S                    | [7dfed91b1f](https://linux-hardware.org/?probe=7dfed91b1f) | Mar 03, 2023 |
| HP            | 212B                        | [45dec8a39c](https://linux-hardware.org/?probe=45dec8a39c) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H                  | [150a75757b](https://linux-hardware.org/?probe=150a75757b) | Mar 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [8bc604606b](https://linux-hardware.org/?probe=8bc604606b) | Mar 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [d209549d77](https://linux-hardware.org/?probe=d209549d77) | Mar 02, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| Dell          | 08NPPY A00                  | [66b1256bd3](https://linux-hardware.org/?probe=66b1256bd3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| Gigabyte      | B450M S2H                   | [4f55a08266](https://linux-hardware.org/?probe=4f55a08266) | Feb 27, 2023 |
| Kllisre       | X79 V2.72S                  | [eb7e4b521c](https://linux-hardware.org/?probe=eb7e4b521c) | Feb 26, 2023 |
| ASRock        | B450M Steel Legend          | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | [e63cbac447](https://linux-hardware.org/?probe=e63cbac447) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | [4af0524a44](https://linux-hardware.org/?probe=4af0524a44) | Feb 25, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [fea6031cfe](https://linux-hardware.org/?probe=fea6031cfe) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4cf00365ff](https://linux-hardware.org/?probe=4cf00365ff) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| ASRock        | H370M-ITX/ac                | [300d88af87](https://linux-hardware.org/?probe=300d88af87) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| Dell          | 0200DY A02                  | [a39eba7e6a](https://linux-hardware.org/?probe=a39eba7e6a) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [64b7226700](https://linux-hardware.org/?probe=64b7226700) | Feb 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c61a513a81](https://linux-hardware.org/?probe=c61a513a81) | Feb 20, 2023 |
| ASUSTek       | H81M-K                      | [cb6168e276](https://linux-hardware.org/?probe=cb6168e276) | Feb 20, 2023 |
| ASUSTek       | X99-M WS                    | [69eb540783](https://linux-hardware.org/?probe=69eb540783) | Feb 20, 2023 |
| ASRock        | X570 Taichi Razer Editio... | [3f44c52c3e](https://linux-hardware.org/?probe=3f44c52c3e) | Feb 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [35d0544ea5](https://linux-hardware.org/?probe=35d0544ea5) | Feb 19, 2023 |
| ASUSTek       | BT6130                      | [470ceee356](https://linux-hardware.org/?probe=470ceee356) | Feb 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | [703cc27199](https://linux-hardware.org/?probe=703cc27199) | Feb 19, 2023 |
| MSI           | B85M-P33 V2                 | [b78aee1c5a](https://linux-hardware.org/?probe=b78aee1c5a) | Feb 19, 2023 |
| ASUSTek       | X99-PRO/USB                 | [45631ae666](https://linux-hardware.org/?probe=45631ae666) | Feb 18, 2023 |
| Dell          | 0X9M3X A04                  | [9b13a670c5](https://linux-hardware.org/?probe=9b13a670c5) | Feb 18, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [ab3e07326a](https://linux-hardware.org/?probe=ab3e07326a) | Feb 18, 2023 |
| ASRock        | B450 Pro4                   | [d6b212b427](https://linux-hardware.org/?probe=d6b212b427) | Feb 18, 2023 |
| ASUSTek       | PRIME Z270-K                | [5ecce23878](https://linux-hardware.org/?probe=5ecce23878) | Feb 18, 2023 |
| MSI           | B450-A PRO MAX              | [13485dcee3](https://linux-hardware.org/?probe=13485dcee3) | Feb 18, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [06d9c4427a](https://linux-hardware.org/?probe=06d9c4427a) | Feb 18, 2023 |
| Intel         | H61                         | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| MSI           | 970A-G43                    | [e02e6e5509](https://linux-hardware.org/?probe=e02e6e5509) | Feb 17, 2023 |
| HP            | 8053                        | [adbabb5537](https://linux-hardware.org/?probe=adbabb5537) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [dc2acd10eb](https://linux-hardware.org/?probe=dc2acd10eb) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d98e6087da](https://linux-hardware.org/?probe=d98e6087da) | Feb 16, 2023 |
| ASRock        | Z77 Extreme3                | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| Dell          | 0W2F8G A00                  | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| ASUSTek       | P5QPL-AM                    | [a3b4daa09d](https://linux-hardware.org/?probe=a3b4daa09d) | Feb 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [e8dc5253a3](https://linux-hardware.org/?probe=e8dc5253a3) | Feb 15, 2023 |
| MSI           | Z390-A PRO                  | [713f522b92](https://linux-hardware.org/?probe=713f522b92) | Feb 14, 2023 |
| Acer          | H410H6-M17 P21-A1           | [beaef7f0ab](https://linux-hardware.org/?probe=beaef7f0ab) | Feb 14, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Shuttle       | FX79R                       | [b1631ebb53](https://linux-hardware.org/?probe=b1631ebb53) | Feb 13, 2023 |
| ASUSTek       | PRIME H510M-A               | [8583704242](https://linux-hardware.org/?probe=8583704242) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [88b290f249](https://linux-hardware.org/?probe=88b290f249) | Feb 13, 2023 |
| ASRock        | B460 Phantom Gaming 4       | [785e6e2876](https://linux-hardware.org/?probe=785e6e2876) | Feb 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [35781b31c5](https://linux-hardware.org/?probe=35781b31c5) | Feb 12, 2023 |
| HP            | 3397                        | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASRock        | B460M-HDV                   | [cb5573dd52](https://linux-hardware.org/?probe=cb5573dd52) | Feb 11, 2023 |
| Dell          | 0T568R A00                  | [fedf0db748](https://linux-hardware.org/?probe=fedf0db748) | Feb 10, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [e6bcd546ae](https://linux-hardware.org/?probe=e6bcd546ae) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [7a116a53c6](https://linux-hardware.org/?probe=7a116a53c6) | Feb 09, 2023 |
| Gigabyte      | Z87N-WIFI                   | [530627f086](https://linux-hardware.org/?probe=530627f086) | Feb 09, 2023 |
| ASUSTek       | B85M-G                      | [7f27fb0a83](https://linux-hardware.org/?probe=7f27fb0a83) | Feb 09, 2023 |
| MSI           | X570-A PRO                  | [9decf03532](https://linux-hardware.org/?probe=9decf03532) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [157c2ef73f](https://linux-hardware.org/?probe=157c2ef73f) | Feb 09, 2023 |
| ASUSTek       | X99-PRO/USB                 | [29e3ebe102](https://linux-hardware.org/?probe=29e3ebe102) | Feb 09, 2023 |
| ASRock        | B460M-HDV                   | [dd0daa720e](https://linux-hardware.org/?probe=dd0daa720e) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | [4684c0511e](https://linux-hardware.org/?probe=4684c0511e) | Feb 08, 2023 |
| ASUSTek       | X99-PRO/USB                 | [d1f6f6da3a](https://linux-hardware.org/?probe=d1f6f6da3a) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| Dell          | 0W2F8G A00                  | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| HP            | 3397                        | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [add74ba4b4](https://linux-hardware.org/?probe=add74ba4b4) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [66a494b2ec](https://linux-hardware.org/?probe=66a494b2ec) | Feb 04, 2023 |
| MSI           | MEG Z390 ACE                | [0528b7476a](https://linux-hardware.org/?probe=0528b7476a) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| Intel         | H61                         | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | [62882a0c3e](https://linux-hardware.org/?probe=62882a0c3e) | Feb 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [19b6a074e8](https://linux-hardware.org/?probe=19b6a074e8) | Feb 03, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [9b2f47d039](https://linux-hardware.org/?probe=9b2f47d039) | Feb 02, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | [115de2faed](https://linux-hardware.org/?probe=115de2faed) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | [02c8ae01d1](https://linux-hardware.org/?probe=02c8ae01d1) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [02580dd501](https://linux-hardware.org/?probe=02580dd501) | Jan 30, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [8b5c80cad4](https://linux-hardware.org/?probe=8b5c80cad4) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | [2658d00cd2](https://linux-hardware.org/?probe=2658d00cd2) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [31bda5eb31](https://linux-hardware.org/?probe=31bda5eb31) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | [d4c609c373](https://linux-hardware.org/?probe=d4c609c373) | Jan 27, 2023 |
| ASUSTek       | PRIME B450M-A               | [4a33dd0b76](https://linux-hardware.org/?probe=4a33dd0b76) | Jan 27, 2023 |
| ASRock        | X570 Taichi                 | [bdfb4aecf9](https://linux-hardware.org/?probe=bdfb4aecf9) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| Lenovo        | NO DPK                      | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| Intel         | DG965SS AAD41678-306        | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| ASUSTek       | PRIME B560M-A               | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [026efbc485](https://linux-hardware.org/?probe=026efbc485) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [184de230c5](https://linux-hardware.org/?probe=184de230c5) | Jan 25, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | [b67d126993](https://linux-hardware.org/?probe=b67d126993) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| ASUSTek       | A68HM-PLUS                  | [3afbe94c21](https://linux-hardware.org/?probe=3afbe94c21) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| ASUSTek       | PRIME B450M-K               | [8a68388e16](https://linux-hardware.org/?probe=8a68388e16) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| ASUSTek       | Z97-K                       | [1261e08a8a](https://linux-hardware.org/?probe=1261e08a8a) | Jan 22, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [d1e0b2e009](https://linux-hardware.org/?probe=d1e0b2e009) | Jan 22, 2023 |
| Gigabyte      | Z97X-Gaming 7               | [a51b58dfbb](https://linux-hardware.org/?probe=a51b58dfbb) | Jan 22, 2023 |
| Shenzhen M... | F6BFC                       | [21f62b0eac](https://linux-hardware.org/?probe=21f62b0eac) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [be39389c7f](https://linux-hardware.org/?probe=be39389c7f) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [0d8275b0de](https://linux-hardware.org/?probe=0d8275b0de) | Jan 21, 2023 |
| Gigabyte      | Z87N-WIFI                   | [d77592ccf0](https://linux-hardware.org/?probe=d77592ccf0) | Jan 20, 2023 |
| ASUSTek       | M5A97 R2.0                  | [19eabab270](https://linux-hardware.org/?probe=19eabab270) | Jan 19, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| Gigabyte      | H77-D3H                     | [15da5de3ae](https://linux-hardware.org/?probe=15da5de3ae) | Jan 18, 2023 |
| MSI           | H81I                        | [f51db4589d](https://linux-hardware.org/?probe=f51db4589d) | Jan 18, 2023 |
| Gigabyte      | 990FXA-UD3                  | [39591416ac](https://linux-hardware.org/?probe=39591416ac) | Jan 18, 2023 |
| Gigabyte      | Z87N-WIFI                   | [b796ac9a1d](https://linux-hardware.org/?probe=b796ac9a1d) | Jan 17, 2023 |
| Gigabyte      | F2A68HM-H                   | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| HP            | 805A                        | [0f9521809b](https://linux-hardware.org/?probe=0f9521809b) | Jan 17, 2023 |
| HP            | 805A                        | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [8cd20f181b](https://linux-hardware.org/?probe=8cd20f181b) | Jan 16, 2023 |
| Biostar       | A320MH                      | [1736406da7](https://linux-hardware.org/?probe=1736406da7) | Jan 16, 2023 |
| Intel         | X99                         | [9c0ea1f762](https://linux-hardware.org/?probe=9c0ea1f762) | Jan 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [02178066f5](https://linux-hardware.org/?probe=02178066f5) | Jan 16, 2023 |
| ASUSTek       | GD30CI                      | [7d1227f25f](https://linux-hardware.org/?probe=7d1227f25f) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | [2ed7e76dbe](https://linux-hardware.org/?probe=2ed7e76dbe) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ebe7fa8c2a](https://linux-hardware.org/?probe=ebe7fa8c2a) | Jan 14, 2023 |
| Dell          | 00V62H A01                  | [47aa34eddd](https://linux-hardware.org/?probe=47aa34eddd) | Jan 14, 2023 |
| Gigabyte      | B450M S2H                   | [e92f01ff78](https://linux-hardware.org/?probe=e92f01ff78) | Jan 14, 2023 |
| ASRock        | B450 Gaming K4              | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| Shuttle       | FS61                        | [9034ce313b](https://linux-hardware.org/?probe=9034ce313b) | Jan 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [4cb06b24fd](https://linux-hardware.org/?probe=4cb06b24fd) | Jan 11, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| ASRock        | Z87M Extreme4               | [4aa4793173](https://linux-hardware.org/?probe=4aa4793173) | Jan 10, 2023 |
| ASUSTek       | PRIME Z270-A                | [b4c192526f](https://linux-hardware.org/?probe=b4c192526f) | Jan 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [874ab2d9a6](https://linux-hardware.org/?probe=874ab2d9a6) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09e26eaa3](https://linux-hardware.org/?probe=f09e26eaa3) | Jan 07, 2023 |
| Intel         | DG35EC AAE29266-205         | [29654c0c64](https://linux-hardware.org/?probe=29654c0c64) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | [bf90b7d77d](https://linux-hardware.org/?probe=bf90b7d77d) | Jan 06, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [f188e7e419](https://linux-hardware.org/?probe=f188e7e419) | Jan 04, 2023 |
| Lenovo        | 31900058 STD or WIN         | [21cdab1361](https://linux-hardware.org/?probe=21cdab1361) | Jan 03, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [32e666defa](https://linux-hardware.org/?probe=32e666defa) | Jan 03, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [c2c723d7b2](https://linux-hardware.org/?probe=c2c723d7b2) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [395606c638](https://linux-hardware.org/?probe=395606c638) | Jan 03, 2023 |
| ASUSTek       | B85M-E/BR                   | [88f7654113](https://linux-hardware.org/?probe=88f7654113) | Jan 02, 2023 |
| Lenovo        | Dory CRB                    | [c87645ef7b](https://linux-hardware.org/?probe=c87645ef7b) | Jan 02, 2023 |
| MSI           | A520M-A PRO                 | [28a0c6dda9](https://linux-hardware.org/?probe=28a0c6dda9) | Jan 02, 2023 |
| ASRock        | B450M Pro4                  | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Dell          | 0PU052                      | [82740aac1d](https://linux-hardware.org/?probe=82740aac1d) | Jan 02, 2023 |
| Dell          | 0PU052                      | [e40981850d](https://linux-hardware.org/?probe=e40981850d) | Jan 02, 2023 |
| Dell          | 04YP6J A02                  | [ee7f6ddcc1](https://linux-hardware.org/?probe=ee7f6ddcc1) | Jan 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e877a9f9e3](https://linux-hardware.org/?probe=e877a9f9e3) | Jan 01, 2023 |
| AZW           | GTR V02                     | [5c08e4403a](https://linux-hardware.org/?probe=5c08e4403a) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7e22db9b23](https://linux-hardware.org/?probe=7e22db9b23) | Dec 31, 2022 |
| ASRock        | B550 Steel Legend           | [8705e10ac6](https://linux-hardware.org/?probe=8705e10ac6) | Dec 31, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [cecef0575d](https://linux-hardware.org/?probe=cecef0575d) | Dec 30, 2022 |
| Gigabyte      | Z87-HD3                     | [97f08bd689](https://linux-hardware.org/?probe=97f08bd689) | Dec 30, 2022 |
| Gigabyte      | H510M H                     | [24574296e5](https://linux-hardware.org/?probe=24574296e5) | Dec 29, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [7a7f335c4a](https://linux-hardware.org/?probe=7a7f335c4a) | Dec 29, 2022 |
| MSI           | X370 GAMING M7 ACK          | [60fe0d0b31](https://linux-hardware.org/?probe=60fe0d0b31) | Dec 29, 2022 |
| MSI           | PRO B660M-A DDR4            | [dbc37ff826](https://linux-hardware.org/?probe=dbc37ff826) | Dec 29, 2022 |
| Dell          | 0TTDMJ A00                  | [198e723dc2](https://linux-hardware.org/?probe=198e723dc2) | Dec 28, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [6d56c4c392](https://linux-hardware.org/?probe=6d56c4c392) | Dec 27, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [d6a12148ec](https://linux-hardware.org/?probe=d6a12148ec) | Dec 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [bd232cd937](https://linux-hardware.org/?probe=bd232cd937) | Dec 27, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ac6571db76](https://linux-hardware.org/?probe=ac6571db76) | Dec 27, 2022 |
| ASRock        | Z690 Taichi                 | [4a4e2975d2](https://linux-hardware.org/?probe=4a4e2975d2) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [a6c0667059](https://linux-hardware.org/?probe=a6c0667059) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [ad94a727ab](https://linux-hardware.org/?probe=ad94a727ab) | Dec 27, 2022 |
| ASRock        | AB350M-HDV                  | [666ea6d820](https://linux-hardware.org/?probe=666ea6d820) | Dec 26, 2022 |
| ASUSTek       | M5A97 R2.0                  | [be1ace7f20](https://linux-hardware.org/?probe=be1ace7f20) | Dec 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [82de75771e](https://linux-hardware.org/?probe=82de75771e) | Dec 25, 2022 |
| ASRock        | X670E Pro RS                | [b7a0a3d703](https://linux-hardware.org/?probe=b7a0a3d703) | Dec 24, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e3e2773bde](https://linux-hardware.org/?probe=e3e2773bde) | Dec 24, 2022 |
| Gigabyte      | H510M H                     | [d592546f0a](https://linux-hardware.org/?probe=d592546f0a) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | [52f1e32fc8](https://linux-hardware.org/?probe=52f1e32fc8) | Dec 23, 2022 |
| Dell          | 0GY6Y8 A02                  | [1044231936](https://linux-hardware.org/?probe=1044231936) | Dec 22, 2022 |
| HP            | 8053                        | [38b3012a7c](https://linux-hardware.org/?probe=38b3012a7c) | Dec 22, 2022 |
| ASRock        | X670E Taichi                | [e1b13226a4](https://linux-hardware.org/?probe=e1b13226a4) | Dec 21, 2022 |
| ASRock        | AB350 Pro4                  | [c7005e1e89](https://linux-hardware.org/?probe=c7005e1e89) | Dec 21, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [dbefd12c1c](https://linux-hardware.org/?probe=dbefd12c1c) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [9fb0357e3e](https://linux-hardware.org/?probe=9fb0357e3e) | Dec 19, 2022 |
| ASRock        | Z390 Pro4                   | [478165e478](https://linux-hardware.org/?probe=478165e478) | Dec 18, 2022 |
| Gigabyte      | B550M DS3H                  | [d868b73cfb](https://linux-hardware.org/?probe=d868b73cfb) | Dec 18, 2022 |
| Gigabyte      | B460M AORUS PRO             | [6deb38fb48](https://linux-hardware.org/?probe=6deb38fb48) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | [71dabd9e44](https://linux-hardware.org/?probe=71dabd9e44) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | [3b245437e5](https://linux-hardware.org/?probe=3b245437e5) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [d2dce9cbfd](https://linux-hardware.org/?probe=d2dce9cbfd) | Dec 16, 2022 |
| Gigabyte      | H510M H                     | [ccb746cd73](https://linux-hardware.org/?probe=ccb746cd73) | Dec 15, 2022 |
| ZOTAC         | ION                         | [f02f6b8382](https://linux-hardware.org/?probe=f02f6b8382) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| Gigabyte      | B450M H                     | [c888c743e3](https://linux-hardware.org/?probe=c888c743e3) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7d15ecff86](https://linux-hardware.org/?probe=7d15ecff86) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [72175490ae](https://linux-hardware.org/?probe=72175490ae) | Dec 15, 2022 |
| MSI           | B250 GAMING M3              | [cf050915a5](https://linux-hardware.org/?probe=cf050915a5) | Dec 14, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [39d58ec9aa](https://linux-hardware.org/?probe=39d58ec9aa) | Dec 13, 2022 |
| ASUSTek       | X99-A II                    | [a6e0258bbe](https://linux-hardware.org/?probe=a6e0258bbe) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [8fd3c60681](https://linux-hardware.org/?probe=8fd3c60681) | Dec 13, 2022 |
| Intel         | Eaglelake Fab D             | [ed5c44a200](https://linux-hardware.org/?probe=ed5c44a200) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [0973466d88](https://linux-hardware.org/?probe=0973466d88) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [9d2ef8adf1](https://linux-hardware.org/?probe=9d2ef8adf1) | Dec 13, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c5501c208c](https://linux-hardware.org/?probe=c5501c208c) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [6964e348d6](https://linux-hardware.org/?probe=6964e348d6) | Dec 11, 2022 |
| ASUSTek       | X99-A II                    | [09f8da551c](https://linux-hardware.org/?probe=09f8da551c) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [23be4288bb](https://linux-hardware.org/?probe=23be4288bb) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [121359234c](https://linux-hardware.org/?probe=121359234c) | Dec 11, 2022 |
| ASUSTek       | PRIME X570-P                | [6b00f35a38](https://linux-hardware.org/?probe=6b00f35a38) | Dec 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [deab1a46db](https://linux-hardware.org/?probe=deab1a46db) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-A               | [e843a9c61d](https://linux-hardware.org/?probe=e843a9c61d) | Dec 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [27fdfb657e](https://linux-hardware.org/?probe=27fdfb657e) | Dec 09, 2022 |
| Gigabyte      | B550M S2H                   | [5e56097f25](https://linux-hardware.org/?probe=5e56097f25) | Dec 08, 2022 |
| MSI           | PRO B650-P WIFI             | [b74866314e](https://linux-hardware.org/?probe=b74866314e) | Dec 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [d6666dccec](https://linux-hardware.org/?probe=d6666dccec) | Dec 08, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [c6895362e6](https://linux-hardware.org/?probe=c6895362e6) | Dec 07, 2022 |
| Lenovo        | ThinkStation S20 4157DT6    | [7c45cf5115](https://linux-hardware.org/?probe=7c45cf5115) | Dec 07, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [037c8e9cbc](https://linux-hardware.org/?probe=037c8e9cbc) | Dec 06, 2022 |
| Gigabyte      | F2A58M-HD2                  | [61c23e2501](https://linux-hardware.org/?probe=61c23e2501) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [689479ce87](https://linux-hardware.org/?probe=689479ce87) | Dec 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [f11d4ebe40](https://linux-hardware.org/?probe=f11d4ebe40) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [ddd1487d81](https://linux-hardware.org/?probe=ddd1487d81) | Dec 05, 2022 |
| HP            | 8053                        | [5fad592ef3](https://linux-hardware.org/?probe=5fad592ef3) | Dec 05, 2022 |
| Gigabyte      | B550M S2H                   | [dd012c9f92](https://linux-hardware.org/?probe=dd012c9f92) | Dec 04, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9eb248d38e](https://linux-hardware.org/?probe=9eb248d38e) | Dec 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b3b5eb90e5](https://linux-hardware.org/?probe=b3b5eb90e5) | Dec 03, 2022 |
| ASRock        | Z87 Extreme4                | [422dde5ae5](https://linux-hardware.org/?probe=422dde5ae5) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ec36ceb3fd](https://linux-hardware.org/?probe=ec36ceb3fd) | Dec 02, 2022 |
| MSI           | A68HM-E33                   | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [8cf4925f08](https://linux-hardware.org/?probe=8cf4925f08) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [97ceee65f3](https://linux-hardware.org/?probe=97ceee65f3) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [5b7f983a24](https://linux-hardware.org/?probe=5b7f983a24) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [42ddb2463e](https://linux-hardware.org/?probe=42ddb2463e) | Dec 01, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ece7618688](https://linux-hardware.org/?probe=ece7618688) | Nov 30, 2022 |
| ASRock        | B550M Pro4                  | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| Dell          | 09WH54 A00                  | [2700be5b4a](https://linux-hardware.org/?probe=2700be5b4a) | Nov 28, 2022 |
| Gigabyte      | M61PME-S2P                  | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| HP            | 3397                        | [e264b68f30](https://linux-hardware.org/?probe=e264b68f30) | Nov 27, 2022 |
| Gigabyte      | 970A-DS3P FX                | [4ded1fb943](https://linux-hardware.org/?probe=4ded1fb943) | Nov 26, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [bb0d4b34af](https://linux-hardware.org/?probe=bb0d4b34af) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | [5f1188d448](https://linux-hardware.org/?probe=5f1188d448) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | [771019bcc6](https://linux-hardware.org/?probe=771019bcc6) | Nov 26, 2022 |
| Gigabyte      | B550M S2H                   | [8ea3c120c6](https://linux-hardware.org/?probe=8ea3c120c6) | Nov 23, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [6cd720c62c](https://linux-hardware.org/?probe=6cd720c62c) | Nov 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [fc53a66047](https://linux-hardware.org/?probe=fc53a66047) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [62b0cb4c94](https://linux-hardware.org/?probe=62b0cb4c94) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [26e7d04331](https://linux-hardware.org/?probe=26e7d04331) | Nov 22, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [a22e271ac2](https://linux-hardware.org/?probe=a22e271ac2) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| ASRock        | B550M Pro4                  | [7d1d0390ba](https://linux-hardware.org/?probe=7d1d0390ba) | Nov 20, 2022 |
| MSI           | 970A-G43                    | [6c04d813ff](https://linux-hardware.org/?probe=6c04d813ff) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [d40491a06a](https://linux-hardware.org/?probe=d40491a06a) | Nov 19, 2022 |
| Intel         | DH55PJ AAE93812-303         | [bebe890c96](https://linux-hardware.org/?probe=bebe890c96) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [c8fc039301](https://linux-hardware.org/?probe=c8fc039301) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [1ffee02fee](https://linux-hardware.org/?probe=1ffee02fee) | Nov 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [312da35b57](https://linux-hardware.org/?probe=312da35b57) | Nov 17, 2022 |
| ASUSTek       | Maximus VIII GENE           | [8b542ffc42](https://linux-hardware.org/?probe=8b542ffc42) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [7f7b7354b8](https://linux-hardware.org/?probe=7f7b7354b8) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [42d08e1136](https://linux-hardware.org/?probe=42d08e1136) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f5fd3e9e4b](https://linux-hardware.org/?probe=f5fd3e9e4b) | Nov 16, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [07d80f1783](https://linux-hardware.org/?probe=07d80f1783) | Nov 16, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [4da8ff348a](https://linux-hardware.org/?probe=4da8ff348a) | Nov 15, 2022 |
| ASRock        | A320M-HDV R4.0              | [7764c0fea2](https://linux-hardware.org/?probe=7764c0fea2) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c8c74ea1ec](https://linux-hardware.org/?probe=c8c74ea1ec) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [567b81705d](https://linux-hardware.org/?probe=567b81705d) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [389d8cf0e0](https://linux-hardware.org/?probe=389d8cf0e0) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| MSI           | Z97A GAMING 7               | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| MSI           | B85M-P33 V2                 | [d633461307](https://linux-hardware.org/?probe=d633461307) | Nov 13, 2022 |
| ASRock        | X300M-STX                   | [6b2e935e07](https://linux-hardware.org/?probe=6b2e935e07) | Nov 12, 2022 |
| ASRock        | X300M-STX                   | [b071af765d](https://linux-hardware.org/?probe=b071af765d) | Nov 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [87b7416681](https://linux-hardware.org/?probe=87b7416681) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [f4ed581802](https://linux-hardware.org/?probe=f4ed581802) | Nov 11, 2022 |
| ASUSTek       | PRIME A320M-K               | [e06ab9c0b9](https://linux-hardware.org/?probe=e06ab9c0b9) | Nov 11, 2022 |
| Gigabyte      | H410M S2H V3                | [2172ca7325](https://linux-hardware.org/?probe=2172ca7325) | Nov 11, 2022 |
| MSI           | X79A-GD45                   | [cb82895374](https://linux-hardware.org/?probe=cb82895374) | Nov 11, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [8dcd548e89](https://linux-hardware.org/?probe=8dcd548e89) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [e95608162f](https://linux-hardware.org/?probe=e95608162f) | Nov 10, 2022 |
| ASUSTek       | H110M-A                     | [4868cf87f5](https://linux-hardware.org/?probe=4868cf87f5) | Nov 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9571026291](https://linux-hardware.org/?probe=9571026291) | Nov 08, 2022 |
| ASRock        | X300M-STX                   | [1fee3f08a9](https://linux-hardware.org/?probe=1fee3f08a9) | Nov 07, 2022 |
| MSI           | B550-A PRO                  | [6c4ff211d1](https://linux-hardware.org/?probe=6c4ff211d1) | Nov 07, 2022 |
| HP            | 844C                        | [5b8b05d13d](https://linux-hardware.org/?probe=5b8b05d13d) | Nov 07, 2022 |
| ASRock        | AB350M                      | [fae0de4ece](https://linux-hardware.org/?probe=fae0de4ece) | Nov 07, 2022 |
| Pegatron      | 2AB6                        | [c55efc41db](https://linux-hardware.org/?probe=c55efc41db) | Nov 06, 2022 |
| HP            | 828A                        | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| ASRock        | H310CM-HDV                  | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | [fb29e83d2d](https://linux-hardware.org/?probe=fb29e83d2d) | Nov 05, 2022 |
| ASUSTek       | P8H67                       | [0d98e4b3b3](https://linux-hardware.org/?probe=0d98e4b3b3) | Nov 05, 2022 |
| Lenovo        | 3728 SDK0J40700 WIN 3258... | [6700909ef7](https://linux-hardware.org/?probe=6700909ef7) | Nov 03, 2022 |
| ASUSTek       | M5A97 R2.0                  | [fecd8f06dd](https://linux-hardware.org/?probe=fecd8f06dd) | Nov 02, 2022 |
| HP            | 8054                        | [0f866b3605](https://linux-hardware.org/?probe=0f866b3605) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| MSI           | Z370 GAMING PLUS            | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [8ce0b9271b](https://linux-hardware.org/?probe=8ce0b9271b) | Nov 01, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Acer          | H410H6-M17 P21-A1           | [9333be5120](https://linux-hardware.org/?probe=9333be5120) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6e577f6de5](https://linux-hardware.org/?probe=6e577f6de5) | Nov 01, 2022 |
| HP            | 3397                        | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Gigabyte      | Z77M-D3H                    | [83cd207e4e](https://linux-hardware.org/?probe=83cd207e4e) | Oct 30, 2022 |
| ASRock        | X570 Pro4                   | [d2407c253b](https://linux-hardware.org/?probe=d2407c253b) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [06cb3f01ba](https://linux-hardware.org/?probe=06cb3f01ba) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| ASUSTek       | PRIME B365M-C               | [ccf9650f9a](https://linux-hardware.org/?probe=ccf9650f9a) | Oct 29, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| ASRock        | B550M Pro4                  | [b21b6b2908](https://linux-hardware.org/?probe=b21b6b2908) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| Unknown       | 1.0                         | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Acer          | Aspire MC605 v1.0           | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [4b88876126](https://linux-hardware.org/?probe=4b88876126) | Oct 24, 2022 |
| HP            | 828A                        | [2123f2610c](https://linux-hardware.org/?probe=2123f2610c) | Oct 24, 2022 |
| MSI           | Z68MA-G45                   | [3f398756eb](https://linux-hardware.org/?probe=3f398756eb) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | [d96627943d](https://linux-hardware.org/?probe=d96627943d) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [7cb3500943](https://linux-hardware.org/?probe=7cb3500943) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [e1dedae10a](https://linux-hardware.org/?probe=e1dedae10a) | Oct 22, 2022 |
| ASRock        | H310CM-HDV                  | [afe54b52c9](https://linux-hardware.org/?probe=afe54b52c9) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [7f069e1021](https://linux-hardware.org/?probe=7f069e1021) | Oct 20, 2022 |
| ASUSTek       | H110M-K                     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| ASUSTek       | H170 PRO GAMING             | [cb86d1ba99](https://linux-hardware.org/?probe=cb86d1ba99) | Oct 18, 2022 |
| ASRock        | X670E PG Lightning          | [c3ce6dce01](https://linux-hardware.org/?probe=c3ce6dce01) | Oct 18, 2022 |
| Foxconn       | 2ABF                        | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASRock        | H310CM-HDV                  | [2426012acb](https://linux-hardware.org/?probe=2426012acb) | Oct 18, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [98024d1066](https://linux-hardware.org/?probe=98024d1066) | Oct 17, 2022 |
| MACHINIST     | X79 V2.82H                  | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [7de3eff9df](https://linux-hardware.org/?probe=7de3eff9df) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [93e82a30ac](https://linux-hardware.org/?probe=93e82a30ac) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [eb9b7e329b](https://linux-hardware.org/?probe=eb9b7e329b) | Oct 16, 2022 |
| ASUSTek       | P8H77-V                     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| Gigabyte      | H510M H                     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| HP            | 802E                        | [6231a344aa](https://linux-hardware.org/?probe=6231a344aa) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [a71fb08b36](https://linux-hardware.org/?probe=a71fb08b36) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [abf7c780d2](https://linux-hardware.org/?probe=abf7c780d2) | Oct 13, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f55bb836c3](https://linux-hardware.org/?probe=f55bb836c3) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d006fa9a19](https://linux-hardware.org/?probe=d006fa9a19) | Oct 11, 2022 |
| Gigabyte      | B450M H                     | [36fc5f2c90](https://linux-hardware.org/?probe=36fc5f2c90) | Oct 10, 2022 |
| Gigabyte      | B450M H                     | [c3dc2e33df](https://linux-hardware.org/?probe=c3dc2e33df) | Oct 10, 2022 |
| HP            | 8460                        | [08601807cc](https://linux-hardware.org/?probe=08601807cc) | Oct 10, 2022 |
| HP            | 8460                        | [5be586f271](https://linux-hardware.org/?probe=5be586f271) | Oct 10, 2022 |
| ASUSTek       | P6X58-E-WS                  | [786a8ba316](https://linux-hardware.org/?probe=786a8ba316) | Oct 09, 2022 |
| Dell          | 0TTDMJ A00                  | [656b9369be](https://linux-hardware.org/?probe=656b9369be) | Oct 09, 2022 |
| ASRock        | B550M Steel Legend          | [740a5f78d8](https://linux-hardware.org/?probe=740a5f78d8) | Oct 09, 2022 |
| Gigabyte      | B450 GAMING X               | [a297c351ed](https://linux-hardware.org/?probe=a297c351ed) | Oct 09, 2022 |
| Dell          | 0NW73C A00                  | [2b0a3f91ea](https://linux-hardware.org/?probe=2b0a3f91ea) | Oct 08, 2022 |
| Dell          | 0M9KCM A01                  | [6fa93f6da5](https://linux-hardware.org/?probe=6fa93f6da5) | Oct 07, 2022 |
| Gigabyte      | P55M-UD2                    | [e9627c4c34](https://linux-hardware.org/?probe=e9627c4c34) | Oct 07, 2022 |
| Dell          | 0D24M8 A00                  | [8130af2fab](https://linux-hardware.org/?probe=8130af2fab) | Oct 06, 2022 |
| HP            | 87D6 SMVB                   | [03cf885086](https://linux-hardware.org/?probe=03cf885086) | Oct 05, 2022 |
| Gigabyte      | H510M H                     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| HP            | 21D0                        | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| Dell          | 0HN7XN A00                  | [77776da6f7](https://linux-hardware.org/?probe=77776da6f7) | Oct 03, 2022 |
| Dell          | 0HN7XN A00                  | [84d4748b3e](https://linux-hardware.org/?probe=84d4748b3e) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [668ad3e30a](https://linux-hardware.org/?probe=668ad3e30a) | Oct 02, 2022 |
| ASRock        | B450 Pro4                   | [402a7995c4](https://linux-hardware.org/?probe=402a7995c4) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [15a068e26b](https://linux-hardware.org/?probe=15a068e26b) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3a9d882d91](https://linux-hardware.org/?probe=3a9d882d91) | Oct 01, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dda857d7e6](https://linux-hardware.org/?probe=dda857d7e6) | Oct 01, 2022 |
| Gigabyte      | Z170X-Gaming GT             | [991ea6c93f](https://linux-hardware.org/?probe=991ea6c93f) | Oct 01, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [32a742b50d](https://linux-hardware.org/?probe=32a742b50d) | Oct 01, 2022 |
| Dell          | 07PR60 A01                  | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| Dell          | 0HN7XN A00                  | [c9126cd382](https://linux-hardware.org/?probe=c9126cd382) | Sep 30, 2022 |
| ASRock        | X399M Taichi                | [b7943d1645](https://linux-hardware.org/?probe=b7943d1645) | Sep 29, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| ASRock        | J3160DC-ITX                 | [7e1818288f](https://linux-hardware.org/?probe=7e1818288f) | Sep 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [c83049a0f6](https://linux-hardware.org/?probe=c83049a0f6) | Sep 29, 2022 |
| ASRock        | Z97 Pro3                    | [7b34a50df8](https://linux-hardware.org/?probe=7b34a50df8) | Sep 28, 2022 |
| ASRock        | B450 Pro4                   | [6a9066019c](https://linux-hardware.org/?probe=6a9066019c) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [27ce89f701](https://linux-hardware.org/?probe=27ce89f701) | Sep 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [30507c8461](https://linux-hardware.org/?probe=30507c8461) | Sep 27, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [e5b4fe8914](https://linux-hardware.org/?probe=e5b4fe8914) | Sep 25, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [c65cbf84dc](https://linux-hardware.org/?probe=c65cbf84dc) | Sep 25, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e47b2b85dc](https://linux-hardware.org/?probe=e47b2b85dc) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [719b20fd4e](https://linux-hardware.org/?probe=719b20fd4e) | Sep 24, 2022 |
| Huanan        | X99-TF                      | [1361d73bcd](https://linux-hardware.org/?probe=1361d73bcd) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1faf714086](https://linux-hardware.org/?probe=1faf714086) | Sep 21, 2022 |
| Minix         | NEO G41V-4 Max              | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6c7d6ef178](https://linux-hardware.org/?probe=6c7d6ef178) | Sep 20, 2022 |
| Dell          | 040DDP A01                  | [635c6895e1](https://linux-hardware.org/?probe=635c6895e1) | Sep 20, 2022 |
| Intel         | X99 V1.0                    | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [25d7dc8f0d](https://linux-hardware.org/?probe=25d7dc8f0d) | Sep 19, 2022 |
| Gigabyte      | A320M-H-CF                  | [a3e30957c7](https://linux-hardware.org/?probe=a3e30957c7) | Sep 19, 2022 |
| HP            | 212B                        | [c823e0060e](https://linux-hardware.org/?probe=c823e0060e) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [b0836f0c26](https://linux-hardware.org/?probe=b0836f0c26) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [a28b408f4a](https://linux-hardware.org/?probe=a28b408f4a) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [3b6b90fee6](https://linux-hardware.org/?probe=3b6b90fee6) | Sep 18, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [d11c4e27df](https://linux-hardware.org/?probe=d11c4e27df) | Sep 18, 2022 |
| Intel         | X99 V1.0                    | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Foxconn       | 2ADA                        | [b136916fb3](https://linux-hardware.org/?probe=b136916fb3) | Sep 16, 2022 |
| BESSTAR Te... | UM700                       | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| ASRock        | B450M Pro4                  | [19a46a2f8e](https://linux-hardware.org/?probe=19a46a2f8e) | Sep 16, 2022 |
| ASUSTek       | PRIME H410M-E               | [91f1fdc978](https://linux-hardware.org/?probe=91f1fdc978) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASUSTek       | X99-DELUXE II               | [8c9013ec12](https://linux-hardware.org/?probe=8c9013ec12) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Gigabyte      | H77M-D3H                    | [3767b84078](https://linux-hardware.org/?probe=3767b84078) | Sep 12, 2022 |
| Foxconn       | 2ADA                        | [1b43b0d291](https://linux-hardware.org/?probe=1b43b0d291) | Sep 11, 2022 |
| MSI           | B350M BAZOOKA               | [ff7d2e74a5](https://linux-hardware.org/?probe=ff7d2e74a5) | Sep 11, 2022 |
| ASRock        | J3160DC-ITX                 | [e854b82ab9](https://linux-hardware.org/?probe=e854b82ab9) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [70f5e3d77c](https://linux-hardware.org/?probe=70f5e3d77c) | Sep 08, 2022 |
| HP            | 3397                        | [0ebeef29bf](https://linux-hardware.org/?probe=0ebeef29bf) | Sep 07, 2022 |
| Intel         | Unknown                     | [2758407d23](https://linux-hardware.org/?probe=2758407d23) | Sep 07, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [d35810173c](https://linux-hardware.org/?probe=d35810173c) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| MSI           | Z87-G41 PC Mate             | [775e007fc8](https://linux-hardware.org/?probe=775e007fc8) | Sep 05, 2022 |
| Intel         | B75                         | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [43267285d4](https://linux-hardware.org/?probe=43267285d4) | Sep 04, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [518aa50eb0](https://linux-hardware.org/?probe=518aa50eb0) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [4a27f8b033](https://linux-hardware.org/?probe=4a27f8b033) | Sep 04, 2022 |
| HP            | 8054                        | [878115f808](https://linux-hardware.org/?probe=878115f808) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [65562b09e0](https://linux-hardware.org/?probe=65562b09e0) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ASUSTek       | P6X58D-E                    | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| HP            | 8054                        | [1586ce33d1](https://linux-hardware.org/?probe=1586ce33d1) | Sep 02, 2022 |
| ASRock        | N68-S                       | [df5d34428a](https://linux-hardware.org/?probe=df5d34428a) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [5ba264dfb2](https://linux-hardware.org/?probe=5ba264dfb2) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [169c9af937](https://linux-hardware.org/?probe=169c9af937) | Sep 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [f872d36cd5](https://linux-hardware.org/?probe=f872d36cd5) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [37695eb7e5](https://linux-hardware.org/?probe=37695eb7e5) | Aug 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d816d2ade0](https://linux-hardware.org/?probe=d816d2ade0) | Aug 30, 2022 |
| ASRock        | N68-S                       | [6aabf89438](https://linux-hardware.org/?probe=6aabf89438) | Aug 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [e05dcd4a08](https://linux-hardware.org/?probe=e05dcd4a08) | Aug 29, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | [422af9d6b5](https://linux-hardware.org/?probe=422af9d6b5) | Aug 29, 2022 |
| ASRock        | N68-S                       | [4fff0a6104](https://linux-hardware.org/?probe=4fff0a6104) | Aug 29, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [ec9f8ea30e](https://linux-hardware.org/?probe=ec9f8ea30e) | Aug 28, 2022 |
| ASRock        | B550M Pro4                  | [8c6b85a46c](https://linux-hardware.org/?probe=8c6b85a46c) | Aug 27, 2022 |
| ASRock        | B450M Pro4                  | [f4fe5fd168](https://linux-hardware.org/?probe=f4fe5fd168) | Aug 27, 2022 |
| Gigabyte      | B550 GAMING X V2            | [94e2f7cedc](https://linux-hardware.org/?probe=94e2f7cedc) | Aug 27, 2022 |
| Dell          | 0KWVT8 A02                  | [3f9c00b0da](https://linux-hardware.org/?probe=3f9c00b0da) | Aug 27, 2022 |
| ASRock        | X99 WS                      | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| ASUSTek       | Z170-P                      | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | B550M S2H                   | [8b5fe2494e](https://linux-hardware.org/?probe=8b5fe2494e) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0dbe2c5dfd](https://linux-hardware.org/?probe=0dbe2c5dfd) | Aug 22, 2022 |
| MACHINIST     | H81M-PRO S1 V2.0            | [12be75fa90](https://linux-hardware.org/?probe=12be75fa90) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [3b799e56c6](https://linux-hardware.org/?probe=3b799e56c6) | Aug 21, 2022 |
| MSI           | P55-GD55                    | [89f2c92fa1](https://linux-hardware.org/?probe=89f2c92fa1) | Aug 21, 2022 |
| ASUSTek       | PRIME B365M-C               | [8ae386a7a0](https://linux-hardware.org/?probe=8ae386a7a0) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1d1f39fd1b](https://linux-hardware.org/?probe=1d1f39fd1b) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d59342b7a4](https://linux-hardware.org/?probe=d59342b7a4) | Aug 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [e61c3cee8a](https://linux-hardware.org/?probe=e61c3cee8a) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [41b271c4e7](https://linux-hardware.org/?probe=41b271c4e7) | Aug 17, 2022 |
| Gigabyte      | H61M-S2P                    | [49aedf1cf8](https://linux-hardware.org/?probe=49aedf1cf8) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | [e04617befa](https://linux-hardware.org/?probe=e04617befa) | Aug 17, 2022 |
| MSI           | Z87-G41 PC Mate             | [08e79a0a1c](https://linux-hardware.org/?probe=08e79a0a1c) | Aug 16, 2022 |
| MSI           | X470 GAMING PRO             | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| ASRock        | Z77 Extreme4                | [07e825ed5b](https://linux-hardware.org/?probe=07e825ed5b) | Aug 16, 2022 |
| VS Company    | H61H2                       | [a0b88242a4](https://linux-hardware.org/?probe=a0b88242a4) | Aug 16, 2022 |
| Gigabyte      | B450 AORUS M                | [bdf5ba285f](https://linux-hardware.org/?probe=bdf5ba285f) | Aug 15, 2022 |
| Gigabyte      | B550M S2H                   | [db7b7b3126](https://linux-hardware.org/?probe=db7b7b3126) | Aug 15, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [2fb0eea98c](https://linux-hardware.org/?probe=2fb0eea98c) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [76e185a2e5](https://linux-hardware.org/?probe=76e185a2e5) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| ASRock        | 990FX Extreme3              | [646169ae62](https://linux-hardware.org/?probe=646169ae62) | Aug 14, 2022 |
| HP            | 82A2                        | [bc3d667d42](https://linux-hardware.org/?probe=bc3d667d42) | Aug 13, 2022 |
| MSI           | B350M PRO-VD PLUS           | [ba65d9b67e](https://linux-hardware.org/?probe=ba65d9b67e) | Aug 13, 2022 |
| MSI           | 970A SLI Krait Edition      | [a94fe940b1](https://linux-hardware.org/?probe=a94fe940b1) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [41560e8e13](https://linux-hardware.org/?probe=41560e8e13) | Aug 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f82761570b](https://linux-hardware.org/?probe=f82761570b) | Aug 12, 2022 |
| AZW           | U59                         | [344d4587f6](https://linux-hardware.org/?probe=344d4587f6) | Aug 12, 2022 |
| ASRock        | 990FX Extreme3              | [e3006f6ca1](https://linux-hardware.org/?probe=e3006f6ca1) | Aug 11, 2022 |
| ASUSTek       | Z87-PRO                     | [f8a688c41e](https://linux-hardware.org/?probe=f8a688c41e) | Aug 11, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [3219cc3946](https://linux-hardware.org/?probe=3219cc3946) | Aug 10, 2022 |
| HP            | 8053                        | [db80dc0ee1](https://linux-hardware.org/?probe=db80dc0ee1) | Aug 10, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| Unknown       | Unknown                     | [e4c7906333](https://linux-hardware.org/?probe=e4c7906333) | Aug 09, 2022 |
| Lenovo        | Bantry CRB NOK              | [fbeb21c99a](https://linux-hardware.org/?probe=fbeb21c99a) | Aug 09, 2022 |
| ASUSTek       | G10DK                       | [2401d4af44](https://linux-hardware.org/?probe=2401d4af44) | Aug 08, 2022 |
| MSI           | MAG B550M MORTAR            | [7cf010b820](https://linux-hardware.org/?probe=7cf010b820) | Aug 08, 2022 |
| ASRock        | B450 Pro4                   | [b87492e7c7](https://linux-hardware.org/?probe=b87492e7c7) | Aug 08, 2022 |
| Gigabyte      | B150M-D3H-CF                | [5235533a87](https://linux-hardware.org/?probe=5235533a87) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [a3aa8d0879](https://linux-hardware.org/?probe=a3aa8d0879) | Aug 05, 2022 |
| Dell          | 0XR1GT A00                  | [2e069ba5c2](https://linux-hardware.org/?probe=2e069ba5c2) | Aug 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [e963ce265b](https://linux-hardware.org/?probe=e963ce265b) | Aug 04, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [22b43d3149](https://linux-hardware.org/?probe=22b43d3149) | Aug 04, 2022 |
| ECS           | H61H2-MV                    | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [5951f66289](https://linux-hardware.org/?probe=5951f66289) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [30e0a23365](https://linux-hardware.org/?probe=30e0a23365) | Aug 01, 2022 |
| ASUSTek       | F2A55-M LK2                 | [97a5e9c390](https://linux-hardware.org/?probe=97a5e9c390) | Aug 01, 2022 |
| Dell          | 0D24M8 A00                  | [6367e245e6](https://linux-hardware.org/?probe=6367e245e6) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9ea9e6f737](https://linux-hardware.org/?probe=9ea9e6f737) | Jul 30, 2022 |
| MSI           | X470 GAMING PRO MAX         | [5651db0a63](https://linux-hardware.org/?probe=5651db0a63) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [1fd9e0ca3a](https://linux-hardware.org/?probe=1fd9e0ca3a) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [309df31c47](https://linux-hardware.org/?probe=309df31c47) | Jul 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [fa38197b4d](https://linux-hardware.org/?probe=fa38197b4d) | Jul 29, 2022 |
| Lenovo        | 3133 SDK0J40675 WIN 3305... | [4434d4d78a](https://linux-hardware.org/?probe=4434d4d78a) | Jul 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f666b16fde](https://linux-hardware.org/?probe=f666b16fde) | Jul 28, 2022 |
| Gigabyte      | H97-Gaming 3                | [90656d8ef4](https://linux-hardware.org/?probe=90656d8ef4) | Jul 27, 2022 |
| Lenovo        | 3717 SDK0J40697 WIN 3305... | [701f519b4c](https://linux-hardware.org/?probe=701f519b4c) | Jul 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [b41540a078](https://linux-hardware.org/?probe=b41540a078) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [331a99ef9a](https://linux-hardware.org/?probe=331a99ef9a) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [1f3433b9e1](https://linux-hardware.org/?probe=1f3433b9e1) | Jul 26, 2022 |
| Gigabyte      | 990XA-UD3                   | [803bd277e7](https://linux-hardware.org/?probe=803bd277e7) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| Gigabyte      | Z68P-DS3                    | [b03f1fee53](https://linux-hardware.org/?probe=b03f1fee53) | Jul 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e512b2f9f2](https://linux-hardware.org/?probe=e512b2f9f2) | Jul 23, 2022 |
| Dell          | 0GM819                      | [8c617c1c3f](https://linux-hardware.org/?probe=8c617c1c3f) | Jul 23, 2022 |
| BESSTAR Te... | HM90                        | [cb4da5b649](https://linux-hardware.org/?probe=cb4da5b649) | Jul 23, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9002ca2e54](https://linux-hardware.org/?probe=9002ca2e54) | Jul 23, 2022 |
| ASUSTek       | Maximus Formula             | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| BESSTAR Te... | HM90                        | [380230bbf6](https://linux-hardware.org/?probe=380230bbf6) | Jul 22, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [51c2b5bc3b](https://linux-hardware.org/?probe=51c2b5bc3b) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| ASUSTek       | P9X79                       | [5ff04691ce](https://linux-hardware.org/?probe=5ff04691ce) | Jul 21, 2022 |
| ASUSTek       | P9X79                       | [1bcee43b6e](https://linux-hardware.org/?probe=1bcee43b6e) | Jul 21, 2022 |
| ASRock        | Z77 Extreme4                | [492529f973](https://linux-hardware.org/?probe=492529f973) | Jul 21, 2022 |
| PCWare        | IPMH81G1                    | [cb66716a63](https://linux-hardware.org/?probe=cb66716a63) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [63489ff6e5](https://linux-hardware.org/?probe=63489ff6e5) | Jul 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [fd46c32d92](https://linux-hardware.org/?probe=fd46c32d92) | Jul 19, 2022 |
| ASUSTek       | Maximus Formula             | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [b28f8248b4](https://linux-hardware.org/?probe=b28f8248b4) | Jul 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [84d62872f5](https://linux-hardware.org/?probe=84d62872f5) | Jul 17, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [3b1f082065](https://linux-hardware.org/?probe=3b1f082065) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [3605f29c73](https://linux-hardware.org/?probe=3605f29c73) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [533392d790](https://linux-hardware.org/?probe=533392d790) | Jul 16, 2022 |
| Gigabyte      | A520M S2H                   | [dfc64d417f](https://linux-hardware.org/?probe=dfc64d417f) | Jul 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [06992e615b](https://linux-hardware.org/?probe=06992e615b) | Jul 15, 2022 |
| BESSTAR Te... | TL50                        | [c77ff65710](https://linux-hardware.org/?probe=c77ff65710) | Jul 15, 2022 |
| ASRock        | B550M Pro4                  | [dcdc04db9f](https://linux-hardware.org/?probe=dcdc04db9f) | Jul 14, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| MSI           | X470 GAMING PRO             | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| ASUSTek       | Maximus Formula             | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| MSI           | A320M-A PRO MAX             | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | [8bdaa5b844](https://linux-hardware.org/?probe=8bdaa5b844) | Jul 13, 2022 |
| BESSTAR Te... | UM350                       | [7437e30da5](https://linux-hardware.org/?probe=7437e30da5) | Jul 11, 2022 |
| MSI           | Z77A-G45                    | [ff2bae4518](https://linux-hardware.org/?probe=ff2bae4518) | Jul 11, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [5c8deeb62c](https://linux-hardware.org/?probe=5c8deeb62c) | Jul 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | [02cbc3a4ae](https://linux-hardware.org/?probe=02cbc3a4ae) | Jul 10, 2022 |
| MSI           | Z77A-G45                    | [2d4a011972](https://linux-hardware.org/?probe=2d4a011972) | Jul 10, 2022 |
| Gigabyte      | B365M DS3H                  | [8c2d8a89d0](https://linux-hardware.org/?probe=8c2d8a89d0) | Jul 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [5dc09a66d8](https://linux-hardware.org/?probe=5dc09a66d8) | Jul 08, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b46404cc89](https://linux-hardware.org/?probe=b46404cc89) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [6e17948aa5](https://linux-hardware.org/?probe=6e17948aa5) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [56b772ade4](https://linux-hardware.org/?probe=56b772ade4) | Jul 07, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d9dc513be7](https://linux-hardware.org/?probe=d9dc513be7) | Jul 06, 2022 |
| Fujitsu       | D2981-A1 S26361-D2981-A1    | [5e40d26a2b](https://linux-hardware.org/?probe=5e40d26a2b) | Jul 06, 2022 |
| Inventec      | D CLASS A02                 | [ac1652fd54](https://linux-hardware.org/?probe=ac1652fd54) | Jul 06, 2022 |
| ASUSTek       | PRIME B550M-A               | [a5e8e3a046](https://linux-hardware.org/?probe=a5e8e3a046) | Jul 05, 2022 |
| ASRock        | B550M Pro4                  | [39803eaf94](https://linux-hardware.org/?probe=39803eaf94) | Jul 04, 2022 |
| ASRock        | B550M Pro4                  | [747051c1fc](https://linux-hardware.org/?probe=747051c1fc) | Jul 04, 2022 |
| MSI           | B250M PRO-VDH               | [fb76db49bd](https://linux-hardware.org/?probe=fb76db49bd) | Jul 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| ASRock        | IMB-1213                    | [6e1ba0ba69](https://linux-hardware.org/?probe=6e1ba0ba69) | Jul 04, 2022 |
| HP            | 0A9Ch                       | [3dafdd1a3f](https://linux-hardware.org/?probe=3dafdd1a3f) | Jul 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [a381b573f6](https://linux-hardware.org/?probe=a381b573f6) | Jul 03, 2022 |
| ASUSTek       | PRIME X570-P                | [1a729c627d](https://linux-hardware.org/?probe=1a729c627d) | Jul 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [c633887935](https://linux-hardware.org/?probe=c633887935) | Jul 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [5763cb4576](https://linux-hardware.org/?probe=5763cb4576) | Jul 01, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [21dd020507](https://linux-hardware.org/?probe=21dd020507) | Jul 01, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [7f17faf180](https://linux-hardware.org/?probe=7f17faf180) | Jun 30, 2022 |
| HP            | 0B54h D                     | [bef89f554e](https://linux-hardware.org/?probe=bef89f554e) | Jun 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6a2f1d22f1](https://linux-hardware.org/?probe=6a2f1d22f1) | Jun 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0a976062da](https://linux-hardware.org/?probe=0a976062da) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | [e8d5e4ff14](https://linux-hardware.org/?probe=e8d5e4ff14) | Jun 29, 2022 |
| ASUSTek       | PRIME Z390-P                | [97613877b7](https://linux-hardware.org/?probe=97613877b7) | Jun 29, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [be4dd3360f](https://linux-hardware.org/?probe=be4dd3360f) | Jun 28, 2022 |
| Gigabyte      | A520M DS3H                  | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [0441b2cf28](https://linux-hardware.org/?probe=0441b2cf28) | Jun 27, 2022 |
| HP            | 212B                        | [687ca162d2](https://linux-hardware.org/?probe=687ca162d2) | Jun 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [ca055793c5](https://linux-hardware.org/?probe=ca055793c5) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-K               | [441cba3212](https://linux-hardware.org/?probe=441cba3212) | Jun 27, 2022 |
| Gigabyte      | H370M DS3H-CF               | [862d58f1a4](https://linux-hardware.org/?probe=862d58f1a4) | Jun 27, 2022 |
| MSI           | A320M PRO-M2 V2             | [a801c7c2ba](https://linux-hardware.org/?probe=a801c7c2ba) | Jun 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [da1c9472bd](https://linux-hardware.org/?probe=da1c9472bd) | Jun 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [0e8993f232](https://linux-hardware.org/?probe=0e8993f232) | Jun 27, 2022 |
| ASRock        | B550M Pro4                  | [92d424a6b5](https://linux-hardware.org/?probe=92d424a6b5) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | [4fd5881226](https://linux-hardware.org/?probe=4fd5881226) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | [01e2541b47](https://linux-hardware.org/?probe=01e2541b47) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | [6b2aa6c257](https://linux-hardware.org/?probe=6b2aa6c257) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | [dae78cdc9e](https://linux-hardware.org/?probe=dae78cdc9e) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | [b397f63621](https://linux-hardware.org/?probe=b397f63621) | Jun 26, 2022 |
| ASRock        | H61M-ITX                    | [6c9ee0dadd](https://linux-hardware.org/?probe=6c9ee0dadd) | Jun 26, 2022 |
| ASRock        | B450M Pro4 R2.0             | [f1e0998426](https://linux-hardware.org/?probe=f1e0998426) | Jun 25, 2022 |
| ASRock        | B450M Pro4 R2.0             | [abdb925c2a](https://linux-hardware.org/?probe=abdb925c2a) | Jun 24, 2022 |
| Gigabyte      | MQLP5AP-00                  | [fad6b4b320](https://linux-hardware.org/?probe=fad6b4b320) | Jun 24, 2022 |
| Gigabyte      | B450M S2H V2                | [e0e21604de](https://linux-hardware.org/?probe=e0e21604de) | Jun 24, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [4a8c282d59](https://linux-hardware.org/?probe=4a8c282d59) | Jun 24, 2022 |
| ASRock        | H510M-ITX/ac                | [f1e5f3d686](https://linux-hardware.org/?probe=f1e5f3d686) | Jun 23, 2022 |
| ECS           | H61H2-MV                    | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| Gigabyte      | 970A-DS3P                   | [43c1598008](https://linux-hardware.org/?probe=43c1598008) | Jun 22, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [0e6a585307](https://linux-hardware.org/?probe=0e6a585307) | Jun 21, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7063b6a7ef](https://linux-hardware.org/?probe=7063b6a7ef) | Jun 21, 2022 |
| ASRock        | B550M Pro4                  | [ab46a92e42](https://linux-hardware.org/?probe=ab46a92e42) | Jun 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1bd776020e](https://linux-hardware.org/?probe=1bd776020e) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [75d908e7db](https://linux-hardware.org/?probe=75d908e7db) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [df832fa379](https://linux-hardware.org/?probe=df832fa379) | Jun 18, 2022 |
| Gigabyte      | B450 AORUS M                | [8b1fb7056f](https://linux-hardware.org/?probe=8b1fb7056f) | Jun 17, 2022 |
| Gigabyte      | B450 AORUS M                | [277df992e4](https://linux-hardware.org/?probe=277df992e4) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [530c081484](https://linux-hardware.org/?probe=530c081484) | Jun 17, 2022 |
| ASRock        | AB350M-HDV                  | [65478d1857](https://linux-hardware.org/?probe=65478d1857) | Jun 17, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [b9de371265](https://linux-hardware.org/?probe=b9de371265) | Jun 17, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [d987e4522e](https://linux-hardware.org/?probe=d987e4522e) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4a8163d07f](https://linux-hardware.org/?probe=4a8163d07f) | Jun 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [cee122d15f](https://linux-hardware.org/?probe=cee122d15f) | Jun 16, 2022 |
| AZW           | U59                         | [5a661910dc](https://linux-hardware.org/?probe=5a661910dc) | Jun 16, 2022 |
| Unknown       | Unknown                     | [87eb57392c](https://linux-hardware.org/?probe=87eb57392c) | Jun 16, 2022 |
| MSI           | B360M PRO-VD                | [fa86b2da10](https://linux-hardware.org/?probe=fa86b2da10) | Jun 15, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [a46a8033f8](https://linux-hardware.org/?probe=a46a8033f8) | Jun 15, 2022 |
| ASRock        | B550M Pro4                  | [4dc0746a65](https://linux-hardware.org/?probe=4dc0746a65) | Jun 15, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [7587cca95a](https://linux-hardware.org/?probe=7587cca95a) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [d0050d4fcd](https://linux-hardware.org/?probe=d0050d4fcd) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| Dell          | 0D28YY A00                  | [18487dbcb1](https://linux-hardware.org/?probe=18487dbcb1) | Jun 14, 2022 |
| ASRock        | B550M Pro4                  | [5c9ca9542b](https://linux-hardware.org/?probe=5c9ca9542b) | Jun 13, 2022 |
| HP            | 212B                        | [2680c53ca7](https://linux-hardware.org/?probe=2680c53ca7) | Jun 13, 2022 |
| ASRock        | B550M Pro4                  | [275c522503](https://linux-hardware.org/?probe=275c522503) | Jun 13, 2022 |
| Unknown       | 1.0                         | [8c8f612260](https://linux-hardware.org/?probe=8c8f612260) | Jun 13, 2022 |
| Huanan        | X99-TF V2.0                 | [cf8091c979](https://linux-hardware.org/?probe=cf8091c979) | Jun 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [feca5f6bb5](https://linux-hardware.org/?probe=feca5f6bb5) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| HP            | 0A9Ch                       | [bd8345d324](https://linux-hardware.org/?probe=bd8345d324) | Jun 12, 2022 |
| Gigabyte      | H510M H                     | [7b1a78a681](https://linux-hardware.org/?probe=7b1a78a681) | Jun 11, 2022 |
| Gigabyte      | Z68P-DS3                    | [03554389d5](https://linux-hardware.org/?probe=03554389d5) | Jun 11, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| Gigabyte      | B550M DS3H                  | [32415f8bd1](https://linux-hardware.org/?probe=32415f8bd1) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0dd5653fc1](https://linux-hardware.org/?probe=0dd5653fc1) | Jun 10, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [294890a076](https://linux-hardware.org/?probe=294890a076) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [1b4307a298](https://linux-hardware.org/?probe=1b4307a298) | Jun 09, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [c18fee9219](https://linux-hardware.org/?probe=c18fee9219) | Jun 08, 2022 |
| MSI           | H81M-E33                    | [49191a1c98](https://linux-hardware.org/?probe=49191a1c98) | Jun 08, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [2f1acce421](https://linux-hardware.org/?probe=2f1acce421) | Jun 08, 2022 |
| HP            | 1998                        | [fd5184fe12](https://linux-hardware.org/?probe=fd5184fe12) | Jun 08, 2022 |
| ASRock        | B550M Pro4                  | [10fbde5027](https://linux-hardware.org/?probe=10fbde5027) | Jun 07, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [25213ed098](https://linux-hardware.org/?probe=25213ed098) | Jun 07, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | [1196dd3b41](https://linux-hardware.org/?probe=1196dd3b41) | Jun 06, 2022 |
| MSI           | B350M PRO-VDH               | [ae45bf67a3](https://linux-hardware.org/?probe=ae45bf67a3) | Jun 06, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | [15efe8a0a2](https://linux-hardware.org/?probe=15efe8a0a2) | Jun 06, 2022 |
| MSI           | H81M-E33                    | [6a2d6cbe74](https://linux-hardware.org/?probe=6a2d6cbe74) | Jun 04, 2022 |
| BESSTAR Te... | UM700                       | [ea24f8341e](https://linux-hardware.org/?probe=ea24f8341e) | Jun 02, 2022 |
| BESSTAR Te... | UM700                       | [d3799b37d7](https://linux-hardware.org/?probe=d3799b37d7) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [829ee446bd](https://linux-hardware.org/?probe=829ee446bd) | Jun 02, 2022 |
| MSI           | B350 TOMAHAWK               | [b9cdc775ea](https://linux-hardware.org/?probe=b9cdc775ea) | Jun 02, 2022 |
| ASRock        | B550M Pro4                  | [9ac2f5ba04](https://linux-hardware.org/?probe=9ac2f5ba04) | Jun 01, 2022 |
| MSI           | H81I                        | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| MSI           | B250M PRO-VDH               | [eede963720](https://linux-hardware.org/?probe=eede963720) | May 31, 2022 |
| MSI           | B250M PRO-VDH               | [e2dd690b16](https://linux-hardware.org/?probe=e2dd690b16) | May 31, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [a6506e0582](https://linux-hardware.org/?probe=a6506e0582) | May 30, 2022 |
| ASRock        | B550M Pro4                  | [a5eee874a5](https://linux-hardware.org/?probe=a5eee874a5) | May 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0050247c85](https://linux-hardware.org/?probe=0050247c85) | May 29, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1416d5a87d](https://linux-hardware.org/?probe=1416d5a87d) | May 29, 2022 |
| Google        | Guado                       | [d026c0565d](https://linux-hardware.org/?probe=d026c0565d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | [4e2d37a90d](https://linux-hardware.org/?probe=4e2d37a90d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | [b861a73ade](https://linux-hardware.org/?probe=b861a73ade) | May 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c3d1916e14](https://linux-hardware.org/?probe=c3d1916e14) | May 28, 2022 |
| Gigabyte      | MCMLUCB-00                  | [90c886e471](https://linux-hardware.org/?probe=90c886e471) | May 27, 2022 |
| Dell          | 0KP561                      | [2435960bba](https://linux-hardware.org/?probe=2435960bba) | May 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [63690e08a1](https://linux-hardware.org/?probe=63690e08a1) | May 27, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [d1891c2d3b](https://linux-hardware.org/?probe=d1891c2d3b) | May 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bf3f9d0ed3](https://linux-hardware.org/?probe=bf3f9d0ed3) | May 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c9c34c5c6f](https://linux-hardware.org/?probe=c9c34c5c6f) | May 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [c8f47b62d2](https://linux-hardware.org/?probe=c8f47b62d2) | May 26, 2022 |
| ASRock        | B550M Pro4                  | [d5df82a4ce](https://linux-hardware.org/?probe=d5df82a4ce) | May 25, 2022 |
| ASRock        | H670M-ITX/ax                | [c11c9ac073](https://linux-hardware.org/?probe=c11c9ac073) | May 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [0390e0a7c2](https://linux-hardware.org/?probe=0390e0a7c2) | May 25, 2022 |
| MSI           | X470 GAMING PRO             | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| ASRock        | B550M Pro4                  | [35ba2b5a7a](https://linux-hardware.org/?probe=35ba2b5a7a) | May 24, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [7375e6d7ec](https://linux-hardware.org/?probe=7375e6d7ec) | May 24, 2022 |
| Unknown       | Unknown                     | [62b61f57ef](https://linux-hardware.org/?probe=62b61f57ef) | May 24, 2022 |
| Gigabyte      | Z77M-D3H                    | [b7369242f9](https://linux-hardware.org/?probe=b7369242f9) | May 23, 2022 |
| Google        | Guado                       | [3245615e95](https://linux-hardware.org/?probe=3245615e95) | May 23, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [de3cd5c495](https://linux-hardware.org/?probe=de3cd5c495) | May 23, 2022 |
| ASRock        | Z77 Extreme4                | [198a8b039a](https://linux-hardware.org/?probe=198a8b039a) | May 22, 2022 |
| ASRock        | Z77 Extreme4                | [3c45f702eb](https://linux-hardware.org/?probe=3c45f702eb) | May 22, 2022 |
| MSI           | H97M-G43                    | [3869b1146e](https://linux-hardware.org/?probe=3869b1146e) | May 22, 2022 |
| ASRock        | B550M Pro4                  | [85974104c5](https://linux-hardware.org/?probe=85974104c5) | May 21, 2022 |
| MSI           | Z390-A PRO                  | [8baf319c52](https://linux-hardware.org/?probe=8baf319c52) | May 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [4dce3bdb3a](https://linux-hardware.org/?probe=4dce3bdb3a) | May 21, 2022 |
| Chatreey      | AC1-DP                      | [aefe90ce82](https://linux-hardware.org/?probe=aefe90ce82) | May 20, 2022 |
| HP            | 212B                        | [a52da35d02](https://linux-hardware.org/?probe=a52da35d02) | May 20, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [1efa62dcdb](https://linux-hardware.org/?probe=1efa62dcdb) | May 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [bcb2dd930d](https://linux-hardware.org/?probe=bcb2dd930d) | May 19, 2022 |
| HP            | 8053                        | [67ea3799ad](https://linux-hardware.org/?probe=67ea3799ad) | May 18, 2022 |
| MSI           | X99S GAMING 7               | [ff6fe109c0](https://linux-hardware.org/?probe=ff6fe109c0) | May 17, 2022 |
| ASUSTek       | PRIME X570-P                | [0e0b2d38d8](https://linux-hardware.org/?probe=0e0b2d38d8) | May 17, 2022 |
| ASUSTek       | PRIME X570-P                | [a80d230e6e](https://linux-hardware.org/?probe=a80d230e6e) | May 17, 2022 |
| ASRock        | B550M Pro4                  | [acd5c94fc8](https://linux-hardware.org/?probe=acd5c94fc8) | May 16, 2022 |
| HP            | 3031h                       | [9a6723ea52](https://linux-hardware.org/?probe=9a6723ea52) | May 16, 2022 |
| HP            | 3031h                       | [414614ec5d](https://linux-hardware.org/?probe=414614ec5d) | May 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [798d2cee16](https://linux-hardware.org/?probe=798d2cee16) | May 16, 2022 |
| Gigabyte      | MCMLUCB-00                  | [1ad57be6ad](https://linux-hardware.org/?probe=1ad57be6ad) | May 16, 2022 |
| ASUSTek       | PRIME Z390-P                | [a0c15e2a2f](https://linux-hardware.org/?probe=a0c15e2a2f) | May 16, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [6d1b1bca17](https://linux-hardware.org/?probe=6d1b1bca17) | May 16, 2022 |
| HP            | 8053                        | [35d3caac96](https://linux-hardware.org/?probe=35d3caac96) | May 16, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [178d910ec8](https://linux-hardware.org/?probe=178d910ec8) | May 15, 2022 |
| Gigabyte      | Z97M-DS3H                   | [82b98a2f7e](https://linux-hardware.org/?probe=82b98a2f7e) | May 15, 2022 |
| ASRock        | B550M Pro4                  | [289c04b1dd](https://linux-hardware.org/?probe=289c04b1dd) | May 14, 2022 |
| Dell          | 0C27VV A01                  | [bf0f5c5d07](https://linux-hardware.org/?probe=bf0f5c5d07) | May 14, 2022 |
| ASRock        | X570 Taichi                 | [4d3e26ea12](https://linux-hardware.org/?probe=4d3e26ea12) | May 14, 2022 |
| MSI           | B450M MORTAR MAX            | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| ASUSTek       | Acacia                      | [4b633150fa](https://linux-hardware.org/?probe=4b633150fa) | May 14, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [7a7065c273](https://linux-hardware.org/?probe=7a7065c273) | May 13, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [25654025a8](https://linux-hardware.org/?probe=25654025a8) | May 13, 2022 |
| ASRock        | B550M Pro4                  | [9f9e071e39](https://linux-hardware.org/?probe=9f9e071e39) | May 12, 2022 |
| ASRock        | B550M Pro4                  | [fad48ff5dd](https://linux-hardware.org/?probe=fad48ff5dd) | May 12, 2022 |
| ASUSTek       | P8P67 DELUXE                | [4293bc4b1c](https://linux-hardware.org/?probe=4293bc4b1c) | May 12, 2022 |
| ASUSTek       | P8Z77-V LX                  | [1c124eec80](https://linux-hardware.org/?probe=1c124eec80) | May 12, 2022 |
| Gigabyte      | B550 GAMING X V2            | [326b50009b](https://linux-hardware.org/?probe=326b50009b) | May 12, 2022 |
| ASUSTek       | PRIME X570-PRO              | [23b8b07484](https://linux-hardware.org/?probe=23b8b07484) | May 11, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3fa341f81f](https://linux-hardware.org/?probe=3fa341f81f) | May 11, 2022 |
| Gigabyte      | H97M-HD3                    | [5b0d379b54](https://linux-hardware.org/?probe=5b0d379b54) | May 11, 2022 |
| HP            | 1905                        | [91a5807da1](https://linux-hardware.org/?probe=91a5807da1) | May 10, 2022 |
| HP            | 1905                        | [40dbe34df3](https://linux-hardware.org/?probe=40dbe34df3) | May 10, 2022 |
| MSI           | Z170A GAMING M5             | [766ec913a6](https://linux-hardware.org/?probe=766ec913a6) | May 09, 2022 |
| BESSTAR Te... | UM350                       | [c5234552de](https://linux-hardware.org/?probe=c5234552de) | May 09, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1906da1cb4](https://linux-hardware.org/?probe=1906da1cb4) | May 08, 2022 |
| Intel         | X79M-S                      | [770b00ef16](https://linux-hardware.org/?probe=770b00ef16) | May 08, 2022 |
| ASRock        | B550M Steel Legend          | [a384972a7a](https://linux-hardware.org/?probe=a384972a7a) | May 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [21486c437b](https://linux-hardware.org/?probe=21486c437b) | May 08, 2022 |
| Pegatron      | NARRA5                      | [bfe1e3f80d](https://linux-hardware.org/?probe=bfe1e3f80d) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [027968f6e4](https://linux-hardware.org/?probe=027968f6e4) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [72ae77348e](https://linux-hardware.org/?probe=72ae77348e) | May 07, 2022 |
| ASRock        | X370 Taichi                 | [256b60b267](https://linux-hardware.org/?probe=256b60b267) | May 07, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [093d7ea1c9](https://linux-hardware.org/?probe=093d7ea1c9) | May 06, 2022 |
| ASRock        | H470M-HDV                   | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| MSI           | MEG Z590 GODLIKE            | [0b88e8e449](https://linux-hardware.org/?probe=0b88e8e449) | May 06, 2022 |
| ASRock        | AB350 Pro4                  | [2ce796a070](https://linux-hardware.org/?probe=2ce796a070) | May 05, 2022 |
| MSI           | MEG Z590 GODLIKE            | [ce253bc962](https://linux-hardware.org/?probe=ce253bc962) | May 05, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [3a3a4e634d](https://linux-hardware.org/?probe=3a3a4e634d) | May 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9a2b895663](https://linux-hardware.org/?probe=9a2b895663) | May 04, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [0a2ba1d529](https://linux-hardware.org/?probe=0a2ba1d529) | May 04, 2022 |
| ASUSTek       | P8Z77-V LX                  | [97185f1809](https://linux-hardware.org/?probe=97185f1809) | May 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [473e906b63](https://linux-hardware.org/?probe=473e906b63) | May 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9176b48887](https://linux-hardware.org/?probe=9176b48887) | May 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2089066a7d](https://linux-hardware.org/?probe=2089066a7d) | May 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [edc5f16866](https://linux-hardware.org/?probe=edc5f16866) | May 03, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [26aa108efd](https://linux-hardware.org/?probe=26aa108efd) | May 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | [142c1f1a2f](https://linux-hardware.org/?probe=142c1f1a2f) | May 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [1fea9af929](https://linux-hardware.org/?probe=1fea9af929) | May 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [d49d0283d4](https://linux-hardware.org/?probe=d49d0283d4) | May 03, 2022 |
| Gigabyte      | H81M-S1                     | [8a7d82f85b](https://linux-hardware.org/?probe=8a7d82f85b) | May 03, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [935eb1722b](https://linux-hardware.org/?probe=935eb1722b) | May 02, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [9967806049](https://linux-hardware.org/?probe=9967806049) | May 02, 2022 |
| Gigabyte      | A520M H                     | [80f3ccadb9](https://linux-hardware.org/?probe=80f3ccadb9) | May 02, 2022 |
| MSI           | B450 GAMING PLUS            | [a792e309de](https://linux-hardware.org/?probe=a792e309de) | May 02, 2022 |
| ASRock        | B550AM Gaming               | [e31ad2a03f](https://linux-hardware.org/?probe=e31ad2a03f) | May 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [45a9821bc8](https://linux-hardware.org/?probe=45a9821bc8) | May 02, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a19c88dc27](https://linux-hardware.org/?probe=a19c88dc27) | May 02, 2022 |
| MSI           | Z77A-G43                    | [2c6195f0b8](https://linux-hardware.org/?probe=2c6195f0b8) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | [a913401ce9](https://linux-hardware.org/?probe=a913401ce9) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | [726be8a4f1](https://linux-hardware.org/?probe=726be8a4f1) | May 02, 2022 |
| ASUSTek       | PRIME B350M-A               | [87542ba2c2](https://linux-hardware.org/?probe=87542ba2c2) | Apr 30, 2022 |
| Gigabyte      | H310N x.x                   | [d0daa33c07](https://linux-hardware.org/?probe=d0daa33c07) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [da04f72dfc](https://linux-hardware.org/?probe=da04f72dfc) | Apr 30, 2022 |
| ASRock        | Z370 Gaming K6              | [63d2d272b6](https://linux-hardware.org/?probe=63d2d272b6) | Apr 30, 2022 |
| MSI           | MEG Z590 GODLIKE            | [d0ca0e52ad](https://linux-hardware.org/?probe=d0ca0e52ad) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [29e1e28903](https://linux-hardware.org/?probe=29e1e28903) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [a2f86e2fea](https://linux-hardware.org/?probe=a2f86e2fea) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6f7b2f6a78](https://linux-hardware.org/?probe=6f7b2f6a78) | Apr 28, 2022 |
| ASRock        | B550M Pro4                  | [31f358fdd0](https://linux-hardware.org/?probe=31f358fdd0) | Apr 28, 2022 |
| Gigabyte      | X570 UD                     | [67f24b974b](https://linux-hardware.org/?probe=67f24b974b) | Apr 27, 2022 |
| ASRock        | AB350M-HDV                  | [6ee4ea44a8](https://linux-hardware.org/?probe=6ee4ea44a8) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | [7c7b023841](https://linux-hardware.org/?probe=7c7b023841) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | [eddac3b03f](https://linux-hardware.org/?probe=eddac3b03f) | Apr 27, 2022 |
| ASRock        | B550M Pro4                  | [003eab04ae](https://linux-hardware.org/?probe=003eab04ae) | Apr 26, 2022 |
| MSI           | MEG X570 UNIFY              | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| AZW           | U59                         | [ecee060925](https://linux-hardware.org/?probe=ecee060925) | Apr 26, 2022 |
| Gigabyte      | Z590 D                      | [afad17a56d](https://linux-hardware.org/?probe=afad17a56d) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | [6bee5ac8c6](https://linux-hardware.org/?probe=6bee5ac8c6) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | [a304ccdfb1](https://linux-hardware.org/?probe=a304ccdfb1) | Apr 26, 2022 |
| Alienware     | 02XRCM A01                  | [90cc83b1aa](https://linux-hardware.org/?probe=90cc83b1aa) | Apr 26, 2022 |
| ASRock        | H97 Pro4                    | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Dell          | 042P49 A02                  | [cc2266d5aa](https://linux-hardware.org/?probe=cc2266d5aa) | Apr 25, 2022 |
| MSI           | MEG B550 UNIFY              | [3cf3319591](https://linux-hardware.org/?probe=3cf3319591) | Apr 25, 2022 |
| Dell          | 0KP561                      | [0467bf679e](https://linux-hardware.org/?probe=0467bf679e) | Apr 25, 2022 |
| ASRock        | H110 Pro BTC+               | [1251ef669d](https://linux-hardware.org/?probe=1251ef669d) | Apr 24, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [81f1c06851](https://linux-hardware.org/?probe=81f1c06851) | Apr 23, 2022 |
| Alienware     | 07HV66 A00                  | [7b889c5010](https://linux-hardware.org/?probe=7b889c5010) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6af9cfacd0](https://linux-hardware.org/?probe=6af9cfacd0) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [afcef911ce](https://linux-hardware.org/?probe=afcef911ce) | Apr 23, 2022 |
| ASRock        | AB350M Pro4                 | [544c5dbbf7](https://linux-hardware.org/?probe=544c5dbbf7) | Apr 22, 2022 |
| ASUSTek       | H81M-K                      | [95a2757020](https://linux-hardware.org/?probe=95a2757020) | Apr 22, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [6c6203c7ff](https://linux-hardware.org/?probe=6c6203c7ff) | Apr 22, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [acc082b594](https://linux-hardware.org/?probe=acc082b594) | Apr 22, 2022 |
| Acer          | Predator G3610              | [a53edf84d4](https://linux-hardware.org/?probe=a53edf84d4) | Apr 22, 2022 |
| ASUSTek       | PRIME A320M-K               | [822db71f7a](https://linux-hardware.org/?probe=822db71f7a) | Apr 21, 2022 |
| Gigabyte      | B450 AORUS M                | [ff11434d18](https://linux-hardware.org/?probe=ff11434d18) | Apr 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [34c876e7e6](https://linux-hardware.org/?probe=34c876e7e6) | Apr 19, 2022 |
| Dell          | 0C522T A00                  | [8684c390a7](https://linux-hardware.org/?probe=8684c390a7) | Apr 19, 2022 |
| Dell          | 09M8Y8 A01                  | [8b989c82a2](https://linux-hardware.org/?probe=8b989c82a2) | Apr 18, 2022 |
| Dell          | 09M8Y8 A01                  | [fff624b795](https://linux-hardware.org/?probe=fff624b795) | Apr 18, 2022 |
| ECS           | H61H2-M13                   | [f3d574e81e](https://linux-hardware.org/?probe=f3d574e81e) | Apr 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ff70aec1ae](https://linux-hardware.org/?probe=ff70aec1ae) | Apr 18, 2022 |
| Foxconn       | 2ABF                        | [ce158f41e2](https://linux-hardware.org/?probe=ce158f41e2) | Apr 17, 2022 |
| MSI           | B350M PRO-VDH               | [884f15c1df](https://linux-hardware.org/?probe=884f15c1df) | Apr 17, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [271eb8380b](https://linux-hardware.org/?probe=271eb8380b) | Apr 17, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Manjaro           | 1111     | 41.19%  |
| Manjaro 20.1      | 135      | 5.01%   |
| Manjaro 20.2.1    | 108      | 4%      |
| Manjaro 22.0.0    | 102      | 3.78%   |
| Manjaro 20.2      | 89       | 3.3%    |
| Manjaro 20.0.3    | 81       | 3%      |
| Manjaro 18.1.5    | 56       | 2.08%   |
| Manjaro 21.2.6    | 53       | 1.97%   |
| Manjaro 21.2.5    | 53       | 1.97%   |
| Manjaro 21.1.0    | 53       | 1.97%   |
| Manjaro 18.0.4    | 46       | 1.71%   |
| Manjaro 21.2.0    | 45       | 1.67%   |
| Manjaro 20.0      | 45       | 1.67%   |
| Manjaro 21.1.6    | 38       | 1.41%   |
| Manjaro 21.0.7    | 36       | 1.33%   |
| Manjaro 21.0.5    | 35       | 1.3%    |
| Manjaro 21.0      | 35       | 1.3%    |
| Manjaro 19.0.2    | 31       | 1.15%   |
| Manjaro 20.1.2    | 29       | 1.08%   |
| Manjaro 20.0.1    | 29       | 1.08%   |
| Manjaro 21.2.3    | 27       | 1%      |
| Manjaro 20.1.1    | 24       | 0.89%   |
| Manjaro 22.1.0    | 23       | 0.85%   |
| Manjaro 21.2.1    | 23       | 0.85%   |
| Manjaro 21.3.7    | 20       | 0.74%   |
| Manjaro 21.3.6    | 17       | 0.63%   |
| Manjaro 22.0.4    | 16       | 0.59%   |
| Manjaro 21.0.4    | 16       | 0.59%   |
| Manjaro 21.0.1    | 14       | 0.52%   |
| Manjaro 21.0.2    | 13       | 0.48%   |
| Manjaro 21.2rc    | 12       | 0.44%   |
| Manjaro 21.2.4    | 12       | 0.44%   |
| Manjaro 21.1.2    | 12       | 0.44%   |
| Manjaro 21.0.3    | 12       | 0.44%   |
| Manjaro 18.0.0-rc | 12       | 0.44%   |
| Manjaro 22.0      | 11       | 0.41%   |
| Manjaro 21.3.1    | 11       | 0.41%   |
| Manjaro 21.1.5    | 11       | 0.41%   |
| Manjaro 21.3.0    | 10       | 0.37%   |
| Manjaro 21.2.2    | 10       | 0.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Manjaro | 2477     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.9.16-1-MANJARO  | 115      | 3.83%   |
| 5.8.6-1-MANJARO   | 68       | 2.26%   |
| 5.13.19-2-MANJARO | 66       | 2.2%    |
| 5.15.28-1-MANJARO | 49       | 1.63%   |
| 5.9.11-3-MANJARO  | 48       | 1.6%    |
| 5.8.11-1-MANJARO  | 46       | 1.53%   |
| 5.10.42-1-MANJARO | 40       | 1.33%   |
| 6.1.1-1-MANJARO   | 38       | 1.26%   |
| 5.8.18-1-MANJARO  | 38       | 1.26%   |
| 6.1.12-1-MANJARO  | 32       | 1.07%   |
| 5.15.32-1-MANJARO | 32       | 1.07%   |
| 5.6.16-1-MANJARO  | 31       | 1.03%   |
| 5.15.60-1-MANJARO | 30       | 1%      |
| 5.10.36-2-MANJARO | 30       | 1%      |
| 5.7.9-1-MANJARO   | 29       | 0.97%   |
| 5.15.12-1-MANJARO | 29       | 0.97%   |
| 5.8.3-2-MANJARO   | 25       | 0.83%   |
| 5.8.16-2-MANJARO  | 25       | 0.83%   |
| 5.6.19-2-MANJARO  | 24       | 0.8%    |
| 5.6.15-1-MANJARO  | 24       | 0.8%    |
| 5.17.1-3-MANJARO  | 24       | 0.8%    |
| 5.7.0-3-MANJARO   | 23       | 0.77%   |
| 5.10.2-2-MANJARO  | 23       | 0.77%   |
| 5.6.7-1-MANJARO   | 22       | 0.73%   |
| 5.6.12-1-MANJARO  | 22       | 0.73%   |
| 5.16.14-1-MANJARO | 22       | 0.73%   |
| 5.15.2-2-MANJARO  | 22       | 0.73%   |
| 5.10.23-1-MANJARO | 22       | 0.73%   |
| 5.9.1-1-MANJARO   | 21       | 0.7%    |
| 5.11.6-1-MANJARO  | 21       | 0.7%    |
| 5.4.15-2-MANJARO  | 20       | 0.67%   |
| 5.7.17-2-MANJARO  | 19       | 0.63%   |
| 5.4.6-2-MANJARO   | 19       | 0.63%   |
| 5.10.7-3-MANJARO  | 19       | 0.63%   |
| 5.10.15-1-MANJARO | 19       | 0.63%   |
| 5.14.10-1-MANJARO | 17       | 0.57%   |
| 5.11.2-1-MANJARO  | 17       | 0.57%   |
| 5.10.53-1-MANJARO | 17       | 0.57%   |
| 5.9.3-1-MANJARO   | 16       | 0.53%   |
| 5.6.11-1-MANJARO  | 16       | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 115      | 3.83%   |
| 5.8.6   | 68       | 2.26%   |
| 5.13.19 | 66       | 2.2%    |
| 5.9.11  | 51       | 1.7%    |
| 5.15.28 | 49       | 1.63%   |
| 5.8.11  | 47       | 1.57%   |
| 5.10.42 | 40       | 1.33%   |
| 6.1.1   | 38       | 1.27%   |
| 5.8.18  | 38       | 1.27%   |
| 6.1.12  | 32       | 1.07%   |
| 5.15.32 | 32       | 1.07%   |
| 5.6.16  | 31       | 1.03%   |
| 5.15.60 | 30       | 1%      |
| 5.10.36 | 30       | 1%      |
| 5.7.9   | 29       | 0.97%   |
| 5.7.0   | 29       | 0.97%   |
| 5.17.1  | 29       | 0.97%   |
| 5.15.12 | 29       | 0.97%   |
| 5.9.1   | 28       | 0.93%   |
| 5.6.19  | 27       | 0.9%    |
| 5.8.3   | 26       | 0.87%   |
| 5.8.16  | 25       | 0.83%   |
| 5.6.15  | 24       | 0.8%    |
| 5.6.12  | 23       | 0.77%   |
| 5.15.2  | 23       | 0.77%   |
| 5.10.2  | 23       | 0.77%   |
| 5.6.7   | 22       | 0.73%   |
| 5.16.14 | 22       | 0.73%   |
| 5.10.23 | 22       | 0.73%   |
| 5.11.6  | 21       | 0.7%    |
| 5.7.17  | 20       | 0.67%   |
| 5.4.15  | 20       | 0.67%   |
| 5.10.7  | 20       | 0.67%   |
| 5.4.6   | 19       | 0.63%   |
| 5.10.15 | 19       | 0.63%   |
| 5.15.7  | 17       | 0.57%   |
| 5.14.10 | 17       | 0.57%   |
| 5.14.0  | 17       | 0.57%   |
| 5.11.2  | 17       | 0.57%   |
| 5.10.53 | 17       | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 436      | 15.54%  |
| 5.10    | 359      | 12.79%  |
| 5.4     | 253      | 9.02%   |
| 5.9     | 230      | 8.2%    |
| 5.8     | 228      | 8.13%   |
| 5.6     | 172      | 6.13%   |
| 6.1     | 147      | 5.24%   |
| 5.13    | 126      | 4.49%   |
| 5.7     | 109      | 3.88%   |
| 5.11    | 91       | 3.24%   |
| 4.19    | 66       | 2.35%   |
| 5.17    | 64       | 2.28%   |
| 5.16    | 64       | 2.28%   |
| 5.14    | 61       | 2.17%   |
| 6.0     | 60       | 2.14%   |
| 5.18    | 55       | 1.96%   |
| 5.19    | 53       | 1.89%   |
| 5.12    | 49       | 1.75%   |
| 5.5     | 39       | 1.39%   |
| 4.14    | 33       | 1.18%   |
| 6.2     | 23       | 0.82%   |
| 5.3     | 23       | 0.82%   |
| 5.2     | 17       | 0.61%   |
| 5.1     | 13       | 0.46%   |
| 5.0     | 11       | 0.39%   |
| 4.20    | 5        | 0.18%   |
| 4.18    | 5        | 0.18%   |
| 4.17    | 3        | 0.11%   |
| 4.16    | 3        | 0.11%   |
| 6.3     | 2        | 0.07%   |
| 4.9     | 2        | 0.07%   |
| 4.7     | 2        | 0.07%   |
| 4.4     | 2        | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2477     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| KDE5                     | 954      | 36.78%  |
| XFCE                     | 559      | 21.55%  |
| GNOME                    | 496      | 19.12%  |
| KDE                      | 247      | 9.52%   |
| Unknown                  | 104      | 4.01%   |
| X-Cinnamon               | 81       | 3.12%   |
| i3                       | 45       | 1.73%   |
| MATE                     | 22       | 0.85%   |
| Cinnamon                 | 22       | 0.85%   |
| Deepin                   | 21       | 0.81%   |
| Budgie                   | 14       | 0.54%   |
| LXQt                     | 7        | 0.27%   |
| awesome                  | 5        | 0.19%   |
| sway                     | 4        | 0.15%   |
| Bspwm                    | 3        | 0.12%   |
| ICEWM                    | 2        | 0.08%   |
| GNOME Classic            | 2        | 0.08%   |
| Yaru:ubuntu:GNOME        | 1        | 0.04%   |
| openbox                  | 1        | 0.04%   |
| LXDE                     | 1        | 0.04%   |
| Enlightenment            | 1        | 0.04%   |
| DWM                      | 1        | 0.04%   |
| /usr/bin/openbox-session | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2261     | 89.62%  |
| Wayland | 196      | 7.77%   |
| Unknown | 41       | 1.63%   |
| Tty     | 25       | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1106     | 43.25%  |
| SDDM    | 635      | 24.83%  |
| LightDM | 432      | 16.89%  |
| GDM     | 283      | 11.07%  |
| TDM     | 89       | 3.48%   |
| LXDM    | 5        | 0.2%    |
| GREETD  | 3        | 0.12%   |
| SLiM    | 2        | 0.08%   |
| XDM     | 1        | 0.04%   |
| LYNDE   | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 988      | 39.24%  |
| de_DE   | 222      | 8.82%   |
| ru_RU   | 194      | 7.7%    |
| en_GB   | 157      | 6.24%   |
| Unknown | 155      | 6.16%   |
| pt_BR   | 108      | 4.29%   |
| fr_FR   | 68       | 2.7%    |
| en_CA   | 68       | 2.7%    |
| es_ES   | 63       | 2.5%    |
| it_IT   | 55       | 2.18%   |
| pl_PL   | 48       | 1.91%   |
| en_AU   | 36       | 1.43%   |
| nl_NL   | 20       | 0.79%   |
| en_IN   | 20       | 0.79%   |
| de_AT   | 20       | 0.79%   |
| ru_UA   | 18       | 0.71%   |
| sv_SE   | 15       | 0.6%    |
| es_MX   | 15       | 0.6%    |
| es_AR   | 15       | 0.6%    |
| zh_CN   | 14       | 0.56%   |
| fi_FI   | 13       | 0.52%   |
| en_IE   | 11       | 0.44%   |
| fr_CA   | 10       | 0.4%    |
| hu_HU   | 9        | 0.36%   |
| en_ZA   | 9        | 0.36%   |
| en_PH   | 9        | 0.36%   |
| da_DK   | 9        | 0.36%   |
| en_NZ   | 8        | 0.32%   |
| cs_CZ   | 8        | 0.32%   |
| pt_PT   | 7        | 0.28%   |
| es_CL   | 7        | 0.28%   |
| uk_UA   | 6        | 0.24%   |
| en_IL   | 6        | 0.24%   |
| en_DK   | 6        | 0.24%   |
| ja_JP   | 5        | 0.2%    |
| fr_BE   | 5        | 0.2%    |
| tr_TR   | 4        | 0.16%   |
| nb_NO   | 4        | 0.16%   |
| es_UY   | 4        | 0.16%   |
| es_PE   | 4        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1577     | 62.28%  |
| EFI  | 955      | 37.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 2106     | 83.57%  |
| Btrfs   | 262      | 10.4%   |
| Unknown | 40       | 1.59%   |
| Xfs     | 39       | 1.55%   |
| Overlay | 37       | 1.47%   |
| Tmpfs   | 13       | 0.52%   |
| F2fs    | 12       | 0.48%   |
| Zfs     | 4        | 0.16%   |
| Ext2    | 3        | 0.12%   |
| Ext3    | 2        | 0.08%   |
| XXXX    | 1        | 0.04%   |
| XXXfs   | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1205     | 47.4%   |
| GPT     | 1070     | 42.09%  |
| MBR     | 267      | 10.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2096     | 82.78%  |
| Yes       | 436      | 17.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1586     | 62.66%  |
| Yes       | 945      | 37.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 734      | 29.63%  |
| Gigabyte Technology                  | 508      | 20.51%  |
| MSI                                  | 396      | 15.99%  |
| ASRock                               | 274      | 11.06%  |
| Dell                                 | 130      | 5.25%   |
| Hewlett-Packard                      | 117      | 4.72%   |
| Intel                                | 58       | 2.34%   |
| Lenovo                               | 50       | 2.02%   |
| Acer                                 | 27       | 1.09%   |
| Biostar                              | 20       | 0.81%   |
| Unknown                              | 19       | 0.77%   |
| Pegatron                             | 16       | 0.65%   |
| Huanan                               | 13       | 0.52%   |
| Foxconn                              | 11       | 0.44%   |
| Apple                                | 9        | 0.36%   |
| Medion                               | 8        | 0.32%   |
| Fujitsu                              | 7        | 0.28%   |
| ECS                                  | 7        | 0.28%   |
| Shuttle                              | 5        | 0.2%    |
| Positivo                             | 5        | 0.2%    |
| BESSTAR Tech                         | 5        | 0.2%    |
| AZW                                  | 4        | 0.16%   |
| Alienware                            | 4        | 0.16%   |
| PCWare                               | 3        | 0.12%   |
| ZOTAC                                | 2        | 0.08%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.08%   |
| OEM                                  | 2        | 0.08%   |
| Minix                                | 2        | 0.08%   |
| MACHINIST                            | 2        | 0.08%   |
| Inventec                             | 2        | 0.08%   |
| Google                               | 2        | 0.08%   |
| Fujitsu Siemens                      | 2        | 0.08%   |
| XFX                                  | 1        | 0.04%   |
| VS Company                           | 1        | 0.04%   |
| TPV-INVENTA                          | 1        | 0.04%   |
| SYWZ                                 | 1        | 0.04%   |
| System76                             | 1        | 0.04%   |
| Supermicro                           | 1        | 0.04%   |
| SiYW                                 | 1        | 0.04%   |
| Samsung Electronics                  | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 71       | 2.87%   |
| MSI MS-7C37                      | 27       | 1.09%   |
| Gigabyte B450M DS3H              | 26       | 1.05%   |
| MSI MS-7C02                      | 24       | 0.97%   |
| ASUS TUF Gaming X570-PLUS        | 21       | 0.85%   |
| Unknown                          | 21       | 0.85%   |
| ASUS PRIME A320M-K               | 19       | 0.77%   |
| MSI MS-7C91                      | 17       | 0.69%   |
| MSI MS-7B86                      | 17       | 0.69%   |
| ASRock B450M Pro4                | 16       | 0.65%   |
| MSI MS-7B79                      | 15       | 0.61%   |
| ASUS ROG STRIX B450-F GAMING     | 14       | 0.57%   |
| MSI MS-7A38                      | 12       | 0.48%   |
| Gigabyte X570 AORUS ELITE        | 12       | 0.48%   |
| ASUS TUF Gaming B550M-PLUS       | 12       | 0.48%   |
| ASUS ROG STRIX B550-F GAMING     | 12       | 0.48%   |
| ASUS PRIME B450M-A               | 12       | 0.48%   |
| Dell OptiPlex 9020               | 11       | 0.44%   |
| Dell OptiPlex 7010               | 11       | 0.44%   |
| ASUS PRIME B350-PLUS             | 11       | 0.44%   |
| MSI MS-7B89                      | 10       | 0.4%    |
| Gigabyte X570 AORUS MASTER       | 10       | 0.4%    |
| Gigabyte X470 AORUS ULTRA GAMING | 10       | 0.4%    |
| Gigabyte B450 AORUS M            | 10       | 0.4%    |
| Gigabyte 970A-DS3P               | 10       | 0.4%    |
| ASUS ROG STRIX X570-E GAMING     | 10       | 0.4%    |
| MSI MS-7817                      | 9        | 0.36%   |
| MSI MS-7693                      | 9        | 0.36%   |
| Gigabyte B450 AORUS ELITE        | 9        | 0.36%   |
| ASUS ROG CROSSHAIR VIII HERO     | 9        | 0.36%   |
| ASUS PRIME X470-PRO              | 9        | 0.36%   |
| ASUS PRIME B450-PLUS             | 9        | 0.36%   |
| MSI MS-7C94                      | 8        | 0.32%   |
| MSI MS-7A34                      | 8        | 0.32%   |
| ASUS PRIME X370-PRO              | 8        | 0.32%   |
| ASUS PRIME B350M-A               | 8        | 0.32%   |
| ASRock B450M Steel Legend        | 8        | 0.32%   |
| ASRock B450 Pro4                 | 8        | 0.32%   |
| ASUS ROG STRIX X570-F GAMING     | 7        | 0.28%   |
| ASUS M5A78L-M PLUS/USB3          | 7        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 159      | 6.42%   |
| ASUS ROG            | 140      | 5.65%   |
| Dell OptiPlex       | 80       | 3.23%   |
| ASUS TUF            | 77       | 3.11%   |
| ASUS All            | 71       | 2.87%   |
| Gigabyte X570       | 46       | 1.86%   |
| Gigabyte B450M      | 43       | 1.74%   |
| HP Compaq           | 35       | 1.41%   |
| Gigabyte B450       | 33       | 1.33%   |
| MSI MS-7C37         | 27       | 1.09%   |
| ASRock B450M        | 26       | 1.05%   |
| MSI MS-7C02         | 24       | 0.97%   |
| Lenovo ThinkCentre  | 23       | 0.93%   |
| Dell Precision      | 21       | 0.85%   |
| Unknown             | 21       | 0.85%   |
| ASRock X570         | 20       | 0.81%   |
| HP EliteDesk        | 19       | 0.77%   |
| Gigabyte B550       | 18       | 0.73%   |
| ASRock B450         | 18       | 0.73%   |
| MSI MS-7C91         | 17       | 0.69%   |
| MSI MS-7B86         | 17       | 0.69%   |
| Acer Aspire         | 17       | 0.69%   |
| MSI MS-7B79         | 15       | 0.61%   |
| ASUS P8Z77-V        | 15       | 0.61%   |
| Gigabyte Z390       | 14       | 0.57%   |
| ASUS M5A97          | 14       | 0.57%   |
| ASUS M5A78L-M       | 14       | 0.57%   |
| MSI MS-7A38         | 12       | 0.48%   |
| Gigabyte X470       | 12       | 0.48%   |
| ASUS Maximus        | 12       | 0.48%   |
| Gigabyte B550M      | 11       | 0.44%   |
| Gigabyte 970A-DS3P  | 11       | 0.44%   |
| ASUS P8H61-M        | 11       | 0.44%   |
| MSI MS-7B89         | 10       | 0.4%    |
| MSI MS-7817         | 9        | 0.36%   |
| MSI MS-7693         | 9        | 0.36%   |
| Lenovo ThinkStation | 9        | 0.36%   |
| HP Pavilion         | 9        | 0.36%   |
| ASRock X470         | 9        | 0.36%   |
| ASRock B550M        | 9        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 408      | 16.47%  |
| 2019    | 313      | 12.64%  |
| 2020    | 271      | 10.94%  |
| 2017    | 209      | 8.44%   |
| 2012    | 203      | 8.2%    |
| 2013    | 176      | 7.11%   |
| 2014    | 147      | 5.93%   |
| 2011    | 136      | 5.49%   |
| 2015    | 112      | 4.52%   |
| 2016    | 108      | 4.36%   |
| 2021    | 88       | 3.55%   |
| 2010    | 85       | 3.43%   |
| 2009    | 75       | 3.03%   |
| 2008    | 46       | 1.86%   |
| 2007    | 44       | 1.78%   |
| 2022    | 35       | 1.41%   |
| 2006    | 12       | 0.48%   |
| 2023    | 4        | 0.16%   |
| 2005    | 4        | 0.16%   |
| Unknown | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2477     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2475     | 99.88%  |
| Enabled  | 3        | 0.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2475     | 99.92%  |
| Yes  | 2        | 0.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 906      | 35.9%   |
| 32.01-64.0  | 521      | 20.64%  |
| 8.01-16.0   | 452      | 17.91%  |
| 4.01-8.0    | 241      | 9.55%   |
| 3.01-4.0    | 166      | 6.58%   |
| 64.01-256.0 | 124      | 4.91%   |
| 24.01-32.0  | 78       | 3.09%   |
| 1.01-2.0    | 30       | 1.19%   |
| 2.01-3.0    | 6        | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 701      | 24.99%  |
| 2.01-3.0    | 634      | 22.6%   |
| 1.01-2.0    | 625      | 22.28%  |
| 3.01-4.0    | 463      | 16.51%  |
| 8.01-16.0   | 236      | 8.41%   |
| 0.51-1.0    | 71       | 2.53%   |
| 16.01-24.0  | 43       | 1.53%   |
| 24.01-32.0  | 11       | 0.39%   |
| 0.01-0.5    | 11       | 0.39%   |
| 32.01-64.0  | 9        | 0.32%   |
| 64.01-256.0 | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 783      | 30.07%  |
| 1      | 616      | 23.66%  |
| 3      | 525      | 20.16%  |
| 4      | 339      | 13.02%  |
| 5      | 190      | 7.3%    |
| 6      | 71       | 2.73%   |
| 7      | 36       | 1.38%   |
| 8      | 14       | 0.54%   |
| 0      | 11       | 0.42%   |
| 9      | 9        | 0.35%   |
| 11     | 4        | 0.15%   |
| 10     | 3        | 0.12%   |
| 12     | 2        | 0.08%   |
| 20     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1662     | 66.08%  |
| Yes       | 853      | 33.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2451     | 98.95%  |
| No        | 26       | 1.05%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1336     | 53.21%  |
| Yes       | 1175     | 46.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1493     | 59.27%  |
| Yes       | 1026     | 40.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 473      | 18.97%  |
| Germany      | 307      | 12.31%  |
| Russia       | 227      | 9.11%   |
| Brazil       | 150      | 6.02%   |
| Canada       | 100      | 4.01%   |
| France       | 91       | 3.65%   |
| Spain        | 83       | 3.33%   |
| UK           | 82       | 3.29%   |
| Italy        | 76       | 3.05%   |
| Poland       | 75       | 3.01%   |
| Ukraine      | 54       | 2.17%   |
| Netherlands  | 48       | 1.93%   |
| Sweden       | 42       | 1.68%   |
| Australia    | 38       | 1.52%   |
| Austria      | 37       | 1.48%   |
| Finland      | 30       | 1.2%    |
| Belgium      | 26       | 1.04%   |
| Mexico       | 25       | 1%      |
| India        | 24       | 0.96%   |
| Romania      | 23       | 0.92%   |
| Argentina    | 23       | 0.92%   |
| Greece       | 20       | 0.8%    |
| Bulgaria     | 19       | 0.76%   |
| Norway       | 18       | 0.72%   |
| Portugal     | 17       | 0.68%   |
| Hungary      | 17       | 0.68%   |
| Denmark      | 17       | 0.68%   |
| Switzerland  | 16       | 0.64%   |
| South Africa | 14       | 0.56%   |
| China        | 14       | 0.56%   |
| Israel       | 13       | 0.52%   |
| Belarus      | 13       | 0.52%   |
| Czechia      | 12       | 0.48%   |
| Turkey       | 11       | 0.44%   |
| Saudi Arabia | 10       | 0.4%    |
| New Zealand  | 10       | 0.4%    |
| Lithuania    | 10       | 0.4%    |
| Ireland      | 10       | 0.4%    |
| Philippines  | 9        | 0.36%   |
| Chile        | 9        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 53       | 2.01%   |
| St Petersburg     | 24       | 0.91%   |
| Berlin            | 20       | 0.76%   |
| Warsaw            | 19       | 0.72%   |
| Vienna            | 18       | 0.68%   |
| Kyiv              | 17       | 0.65%   |
| Madrid            | 15       | 0.57%   |
| Toronto           | 14       | 0.53%   |
| Sao Paulo         | 14       | 0.53%   |
| Athens            | 14       | 0.53%   |
| Rome              | 13       | 0.49%   |
| Stockholm         | 12       | 0.46%   |
| Rio de Janeiro    | 12       | 0.46%   |
| Frankfurt am Main | 12       | 0.46%   |
| Amsterdam         | 12       | 0.46%   |
| Helsinki          | 11       | 0.42%   |
| Hamburg           | 11       | 0.42%   |
| Sydney            | 10       | 0.38%   |
| Portland          | 10       | 0.38%   |
| Paris             | 10       | 0.38%   |
| Krakow            | 10       | 0.38%   |
| Bucharest         | 10       | 0.38%   |
| Sofia             | 9        | 0.34%   |
| Milan             | 9        | 0.34%   |
| Melbourne         | 9        | 0.34%   |
| Dallas            | 9        | 0.34%   |
| Copenhagen        | 9        | 0.34%   |
| Barcelona         | 9        | 0.34%   |
| Stuttgart         | 8        | 0.3%    |
| New York          | 8        | 0.3%    |
| Montreal          | 8        | 0.3%    |
| Minsk             | 8        | 0.3%    |
| Miami             | 8        | 0.3%    |
| Indianapolis      | 8        | 0.3%    |
| Austin            | 8        | 0.3%    |
| Yekaterinburg     | 7        | 0.27%   |
| Omsk              | 7        | 0.27%   |
| Munich            | 7        | 0.27%   |
| London            | 7        | 0.27%   |
| Istanbul          | 7        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 966      | 1634   | 17.82%  |
| Seagate                     | 947      | 1535   | 17.47%  |
| Samsung Electronics         | 903      | 1590   | 16.66%  |
| Kingston                    | 340      | 484    | 6.27%   |
| Toshiba                     | 295      | 385    | 5.44%   |
| Crucial                     | 281      | 429    | 5.18%   |
| SanDisk                     | 277      | 375    | 5.11%   |
| Hitachi                     | 134      | 194    | 2.47%   |
| Intel                       | 110      | 149    | 2.03%   |
| Phison                      | 84       | 112    | 1.55%   |
| A-DATA Technology           | 84       | 118    | 1.55%   |
| HGST                        | 62       | 97     | 1.14%   |
| China                       | 53       | 74     | 0.98%   |
| Silicon Motion              | 46       | 66     | 0.85%   |
| PNY                         | 41       | 62     | 0.76%   |
| OCZ                         | 39       | 53     | 0.72%   |
| Unknown                     | 36       | 61     | 0.66%   |
| Micron/Crucial Technology   | 36       | 45     | 0.66%   |
| SPCC                        | 35       | 42     | 0.65%   |
| Patriot                     | 35       | 44     | 0.65%   |
| Intenso                     | 34       | 50     | 0.63%   |
| XPG                         | 32       | 36     | 0.59%   |
| SK hynix                    | 30       | 34     | 0.55%   |
| Corsair                     | 27       | 38     | 0.5%    |
| Phison Electronics          | 26       | 29     | 0.48%   |
| Transcend                   | 23       | 23     | 0.42%   |
| Micron Technology           | 23       | 29     | 0.42%   |
| Plextor                     | 21       | 25     | 0.39%   |
| JMicron Technology          | 20       | 26     | 0.37%   |
| Realtek Semiconductor       | 19       | 24     | 0.35%   |
| GOODRAM                     | 19       | 23     | 0.35%   |
| Team                        | 18       | 23     | 0.33%   |
| Lexar                       | 18       | 20     | 0.33%   |
| Apacer                      | 15       | 17     | 0.28%   |
| Kingston Technology Company | 14       | 15     | 0.26%   |
| Maxtor                      | 13       | 15     | 0.24%   |
| Gigabyte Technology         | 13       | 22     | 0.24%   |
| ASMT                        | 11       | 18     | 0.2%    |
| KingDian                    | 10       | 10     | 0.18%   |
| Hewlett-Packard             | 10       | 14     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 88       | 1.36%   |
| Samsung SSD 860 EVO 500GB                          | 83       | 1.28%   |
| Seagate ST1000DM010-2EP102 1TB                     | 78       | 1.21%   |
| Seagate ST2000DM008-2FR102 2TB                     | 71       | 1.1%    |
| Samsung SSD 850 EVO 500GB                          | 63       | 0.97%   |
| Samsung NVMe SSD Drive 500GB                       | 63       | 0.97%   |
| Samsung SSD 850 EVO 250GB                          | 61       | 0.94%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 55       | 0.85%   |
| Toshiba DT01ACA100 1TB                             | 54       | 0.84%   |
| Kingston SA400S37120G 120GB SSD                    | 53       | 0.82%   |
| Samsung SSD 860 EVO 1TB                            | 49       | 0.76%   |
| Samsung NVMe SSD Drive 1TB                         | 49       | 0.76%   |
| Crucial CT500MX500SSD1 500GB                       | 48       | 0.74%   |
| Seagate ST500DM002-1BD142 500GB                    | 41       | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB                     | 41       | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB                     | 41       | 0.63%   |
| Samsung SSD 860 EVO 250GB                          | 40       | 0.62%   |
| Kingston SA400S37480G 480GB SSD                    | 40       | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                        | 39       | 0.6%    |
| WDC WD10EZEX-00BN5A0 1TB                           | 38       | 0.59%   |
| Toshiba HDWD110 1TB                                | 37       | 0.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 36       | 0.56%   |
| Crucial CT240BX500SSD1 240GB                       | 35       | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB                     | 33       | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB                     | 32       | 0.49%   |
| SanDisk NVMe SSD Drive 500GB                       | 31       | 0.48%   |
| Kingston SV300S37A120G 120GB SSD                   | 31       | 0.48%   |
| Seagate ST3500418AS 500GB                          | 30       | 0.46%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 28       | 0.43%   |
| Toshiba DT01ACA200 2TB                             | 28       | 0.43%   |
| Seagate Expansion 4TB                              | 28       | 0.43%   |
| Seagate ST4000DM004-2CV104 4TB                     | 27       | 0.42%   |
| Toshiba DT01ACA050 500GB                           | 25       | 0.39%   |
| Seagate ST2000DM001-1CH164 2TB                     | 25       | 0.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 25       | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 24       | 0.37%   |
| Seagate ST31000524AS 1TB                           | 24       | 0.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 24       | 0.37%   |
| Samsung SSD 970 EVO Plus 500GB                     | 24       | 0.37%   |
| Samsung SSD 840 EVO 250GB                          | 24       | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 927      | 1493   | 37.64%  |
| WDC                 | 859      | 1402   | 34.88%  |
| Toshiba             | 263      | 337    | 10.68%  |
| Samsung Electronics | 137      | 212    | 5.56%   |
| Hitachi             | 134      | 194    | 5.44%   |
| HGST                | 61       | 96     | 2.48%   |
| Unknown             | 16       | 25     | 0.65%   |
| Maxtor              | 13       | 15     | 0.53%   |
| JMicron Technology  | 10       | 14     | 0.41%   |
| Fujitsu             | 8        | 8      | 0.32%   |
| Intenso             | 6        | 10     | 0.24%   |
| Apple               | 5        | 8      | 0.2%    |
| USB3.0              | 4        | 4      | 0.16%   |
| ASMT                | 4        | 7      | 0.16%   |
| HGST HTS            | 3        | 3      | 0.12%   |
| ASMedia             | 3        | 3      | 0.12%   |
| USB                 | 2        | 2      | 0.08%   |
| Maxone              | 2        | 2      | 0.08%   |
| Hewlett-Packard     | 2        | 2      | 0.08%   |
| SABRENT             | 1        | 1      | 0.04%   |
| MaxDigital          | 1        | 1      | 0.04%   |
| Lenovo              | 1        | 1      | 0.04%   |
| IBM/Hitachi         | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 536      | 821    | 26.27%  |
| Kingston            | 298      | 417    | 14.61%  |
| Crucial             | 254      | 393    | 12.45%  |
| SanDisk             | 167      | 218    | 8.19%   |
| WDC                 | 131      | 186    | 6.42%   |
| A-DATA Technology   | 70       | 99     | 3.43%   |
| Intel               | 53       | 71     | 2.6%    |
| China               | 52       | 73     | 2.55%   |
| OCZ                 | 39       | 53     | 1.91%   |
| PNY                 | 36       | 57     | 1.76%   |
| Patriot             | 33       | 42     | 1.62%   |
| SPCC                | 29       | 36     | 1.42%   |
| Toshiba             | 23       | 34     | 1.13%   |
| Intenso             | 20       | 30     | 0.98%   |
| Plextor             | 19       | 23     | 0.93%   |
| Corsair             | 19       | 28     | 0.93%   |
| Transcend           | 18       | 18     | 0.88%   |
| Lexar               | 18       | 20     | 0.88%   |
| GOODRAM             | 18       | 22     | 0.88%   |
| Micron Technology   | 15       | 17     | 0.74%   |
| Apacer              | 15       | 17     | 0.74%   |
| Team                | 14       | 19     | 0.69%   |
| SK hynix            | 11       | 12     | 0.54%   |
| Gigabyte Technology | 11       | 15     | 0.54%   |
| KingDian            | 10       | 10     | 0.49%   |
| Seagate             | 9        | 12     | 0.44%   |
| Leven               | 9        | 9      | 0.44%   |
| KingSpec            | 7        | 9      | 0.34%   |
| ASMT                | 7        | 11     | 0.34%   |
| LITEONIT            | 5        | 8      | 0.25%   |
| Apple               | 5        | 5      | 0.25%   |
| Verbatim            | 4        | 5      | 0.2%    |
| Mushkin             | 4        | 4      | 0.2%    |
| LITEON              | 4        | 4      | 0.2%    |
| Hoodisk             | 4        | 4      | 0.2%    |
| External            | 4        | 5      | 0.2%    |
| TO Exter            | 3        | 3      | 0.15%   |
| NGFF                | 3        | 3      | 0.15%   |
| Kingmax             | 3        | 4      | 0.15%   |
| Hewlett-Packard     | 3        | 4      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1786     | 3841   | 40.87%  |
| SSD     | 1588     | 2900   | 36.34%  |
| NVMe    | 905      | 1446   | 20.71%  |
| Unknown | 86       | 121    | 1.97%   |
| MMC     | 5        | 5      | 0.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2278     | 6511   | 66.8%   |
| NVMe | 902      | 1439   | 26.45%  |
| SAS  | 225      | 358    | 6.6%    |
| MMC  | 5        | 5      | 0.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1698     | 3312   | 44.07%  |
| 0.51-1.0   | 1184     | 1930   | 30.73%  |
| 1.01-2.0   | 520      | 769    | 13.5%   |
| 3.01-4.0   | 185      | 285    | 4.8%    |
| 4.01-10.0  | 123      | 217    | 3.19%   |
| 2.01-3.0   | 121      | 187    | 3.14%   |
| 10.01-20.0 | 22       | 41     | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 454      | 17.16%  |
| 101-250        | 454      | 17.16%  |
| 1001-2000      | 439      | 16.59%  |
| 501-1000       | 437      | 16.52%  |
| More than 3000 | 374      | 14.13%  |
| 2001-3000      | 229      | 8.65%   |
| Unknown        | 93       | 3.51%   |
| 51-100         | 92       | 3.48%   |
| 1-20           | 41       | 1.55%   |
| 21-50          | 33       | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 427      | 15.51%  |
| 1-20           | 395      | 14.35%  |
| 501-1000       | 356      | 12.93%  |
| 21-50          | 329      | 11.95%  |
| 251-500        | 328      | 11.91%  |
| 51-100         | 301      | 10.93%  |
| 1001-2000      | 269      | 9.77%   |
| More than 3000 | 151      | 5.48%   |
| 2001-3000      | 103      | 3.74%   |
| Unknown        | 93       | 3.38%   |
| 0              | 1        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7        | 9      | 2.19%   |
| WDC WD5000AAKX-001CA0 500GB           | 5        | 7      | 1.56%   |
| WDC WD10EARS-00Y5B1 1TB               | 5        | 5      | 1.56%   |
| Samsung Electronics HD103SJ 1TB       | 5        | 5      | 1.56%   |
| Hitachi HDS721010CLA332 1TB           | 5        | 5      | 1.56%   |
| Seagate ST3500413AS 500GB             | 4        | 5      | 1.25%   |
| Seagate ST1000DX001-1CM162 1TB        | 4        | 6      | 1.25%   |
| Samsung Electronics SSD 960 EVO 250GB | 4        | 5      | 1.25%   |
| Samsung Electronics HD103UJ 1TB       | 4        | 6      | 1.25%   |
| WDC WD15EARS-00MVWB0 1TB              | 3        | 3      | 0.94%   |
| WDC WD10EZEX-00RKKA0 1TB              | 3        | 3      | 0.94%   |
| WDC WD10EZEX-00BN5A0 1TB              | 3        | 3      | 0.94%   |
| WDC WD10EARX-00N0YB0 1TB              | 3        | 4      | 0.94%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 3        | 3      | 0.94%   |
| Toshiba MQ01ABD050 500GB              | 3        | 3      | 0.94%   |
| Seagate ST4000DM000-1F2168 4TB        | 3        | 10     | 0.94%   |
| Seagate ST31000524AS 1TB              | 3        | 5      | 0.94%   |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 0.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3        | 3      | 0.94%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.94%   |
| Kingston SA400S37240G 240GB SSD       | 3        | 3      | 0.94%   |
| Crucial CT525MX300SSD1 528GB          | 3        | 3      | 0.94%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2        | 2      | 0.63%   |
| WDC WD5000AAKX-003CA0 500GB           | 2        | 2      | 0.63%   |
| WDC WD5000AACS-00G8B1 500GB           | 2        | 2      | 0.63%   |
| WDC WD40EFRX-68WT0N0 4TB              | 2        | 3      | 0.63%   |
| WDC WD30EZRZ-00Z5HB0 3TB              | 2        | 2      | 0.63%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 2      | 0.63%   |
| WDC WD20EARX-00PASB0 2TB              | 2        | 2      | 0.63%   |
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 0.63%   |
| Seagate ST3250318AS 250GB             | 2        | 2      | 0.63%   |
| Seagate ST3250310AS 250GB             | 2        | 2      | 0.63%   |
| Seagate ST31000340NS 1TB              | 2        | 3      | 0.63%   |
| Seagate ST2000DX001-1CM164 2TB        | 2        | 2      | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB        | 2        | 2      | 0.63%   |
| Seagate ST2000DM001-1ER164 2TB        | 2        | 7      | 0.63%   |
| Seagate ST1000DX001-1NS162 1TB        | 2        | 3      | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB        | 2        | 2      | 0.63%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 3      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 97       | 113    | 31.49%  |
| Seagate             | 87       | 126    | 28.25%  |
| Samsung Electronics | 28       | 34     | 9.09%   |
| Hitachi             | 19       | 21     | 6.17%   |
| Kingston            | 12       | 12     | 3.9%    |
| Toshiba             | 11       | 14     | 3.57%   |
| SanDisk             | 9        | 12     | 2.92%   |
| Intel               | 9        | 10     | 2.92%   |
| HGST                | 7        | 7      | 2.27%   |
| Crucial             | 7        | 7      | 2.27%   |
| A-DATA Technology   | 4        | 4      | 1.3%    |
| OCZ                 | 2        | 2      | 0.65%   |
| Apacer              | 2        | 2      | 0.65%   |
| Transcend           | 1        | 1      | 0.32%   |
| SPCC                | 1        | 1      | 0.32%   |
| SK hynix            | 1        | 2      | 0.32%   |
| Phison              | 1        | 2      | 0.32%   |
| Patriot             | 1        | 1      | 0.32%   |
| Maxtor              | 1        | 1      | 0.32%   |
| MaxDigital          | 1        | 1      | 0.32%   |
| KingSpec            | 1        | 2      | 0.32%   |
| Intenso             | 1        | 4      | 0.32%   |
| Hewlett-Packard     | 1        | 1      | 0.32%   |
| Fujitsu             | 1        | 1      | 0.32%   |
| Drevo               | 1        | 1      | 0.32%   |
| Corsair             | 1        | 5      | 0.32%   |
| ASMT                | 1        | 5      | 0.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 96       | 112    | 39.83%  |
| Seagate             | 86       | 123    | 35.68%  |
| Samsung Electronics | 19       | 24     | 7.88%   |
| Hitachi             | 19       | 21     | 7.88%   |
| Toshiba             | 11       | 14     | 4.56%   |
| HGST                | 7        | 7      | 2.9%    |
| Maxtor              | 1        | 1      | 0.41%   |
| MaxDigital          | 1        | 1      | 0.41%   |
| Fujitsu             | 1        | 1      | 0.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 222      | 304    | 77.35%  |
| SSD  | 55       | 76     | 19.16%  |
| NVMe | 10       | 12     | 3.48%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB      | 1        | 1      | 8.33%   |
| WDC WD3200BPVT-24ZEST0 320GB      | 1        | 1      | 8.33%   |
| WDC WD1600AAJS-65WAA0 160GB       | 1        | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB          | 1        | 1      | 8.33%   |
| Toshiba MK1059GSM 1TB             | 1        | 1      | 8.33%   |
| Seagate ST9640320AS 640GB         | 1        | 1      | 8.33%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 8.33%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 8.33%   |
| Seagate ST31000524AS 1TB          | 1        | 2      | 8.33%   |
| Samsung Electronics HD321HJ 320GB | 1        | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 8.33%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 33.33%  |
| WDC                 | 3        | 3      | 25%     |
| Toshiba             | 2        | 2      | 16.67%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1634     | 5198   | 56.93%  |
| Works    | 952      | 2710   | 33.17%  |
| Malfunc  | 272      | 392    | 9.48%   |
| Failed   | 12       | 13     | 0.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1313     | 34.46%  |
| AMD                              | 1152     | 30.24%  |
| Samsung Electronics              | 384      | 10.08%  |
| ASMedia Technology               | 158      | 4.15%   |
| SanDisk                          | 147      | 3.86%   |
| Phison Electronics               | 123      | 3.23%   |
| Marvell Technology Group         | 70       | 1.84%   |
| Micron/Crucial Technology        | 65       | 1.71%   |
| Silicon Motion                   | 61       | 1.6%    |
| Kingston Technology Company      | 60       | 1.57%   |
| JMicron Technology               | 58       | 1.52%   |
| ADATA Technology                 | 42       | 1.1%    |
| Nvidia                           | 35       | 0.92%   |
| Realtek Semiconductor            | 30       | 0.79%   |
| SK hynix                         | 19       | 0.5%    |
| Toshiba America Info Systems     | 9        | 0.24%   |
| Seagate Technology               | 9        | 0.24%   |
| LSI Logic / Symbios Logic        | 9        | 0.24%   |
| KIOXIA                           | 9        | 0.24%   |
| Micron Technology                | 8        | 0.21%   |
| VIA Technologies                 | 7        | 0.18%   |
| Lite-On Technology               | 6        | 0.16%   |
| Broadcom / LSI                   | 6        | 0.16%   |
| Silicon Image                    | 5        | 0.13%   |
| Adaptec                          | 4        | 0.1%    |
| Shenzhen Longsys Electronics     | 3        | 0.08%   |
| Integrated Technology Express    | 3        | 0.08%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.05%   |
| Yangtze Memory Technologies      | 1        | 0.03%   |
| Union Memory (Shenzhen)          | 1        | 0.03%   |
| Transcend                        | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| Promise Technology               | 1        | 0.03%   |
| PMC-Sierra                       | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| Lenovo                           | 1        | 0.03%   |
| INNOGRIT                         | 1        | 0.03%   |
| HighPoint Technologies           | 1        | 0.03%   |
| Dell                             | 1        | 0.03%   |
| Biwin Storage Technology         | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 777      | 16.28%  |
| AMD 400 Series Chipset SATA Controller                                                  | 337      | 7.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 232      | 4.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 156      | 3.27%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 155      | 3.25%   |
| AMD 500 Series Chipset SATA Controller                                                  | 147      | 3.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 128      | 2.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 108      | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 108      | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 107      | 2.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 101      | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 96       | 2.01%   |
| AMD 300 Series Chipset SATA Controller                                                  | 86       | 1.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 84       | 1.76%   |
| Intel SATA Controller [RAID mode]                                                       | 79       | 1.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 69       | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 62       | 1.3%    |
| Phison E12 NVMe Controller                                                              | 61       | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 56       | 1.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 54       | 1.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 53       | 1.11%   |
| AMD FCH SATA Controller D                                                               | 53       | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 42       | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 42       | 0.88%   |
| AMD X370 Series Chipset SATA Controller                                                 | 42       | 0.88%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 42       | 0.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 41       | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 40       | 0.84%   |
| Samsung NVMe SSD Controller 980                                                         | 39       | 0.82%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 39       | 0.82%   |
| Kingston Company A2000 NVMe SSD                                                         | 37       | 0.78%   |
| Intel SSD 660P Series                                                                   | 35       | 0.73%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 35       | 0.73%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 34       | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 33       | 0.69%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 32       | 0.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 29       | 0.61%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 29       | 0.61%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 27       | 0.57%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 26       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2195     | 60.39%  |
| NVMe | 907      | 24.95%  |
| IDE  | 373      | 10.26%  |
| RAID | 137      | 3.77%   |
| SAS  | 20       | 0.55%   |
| SCSI | 3        | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1290     | 52.06%  |
| AMD    | 1188     | 47.94%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 130      | 5.22%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 75       | 3.01%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 62       | 2.49%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 62       | 2.49%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 45       | 1.81%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 33       | 1.33%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 33       | 1.33%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 29       | 1.16%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 26       | 1.04%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 26       | 1.04%   |
| AMD FX-8350 Eight-Core Processor            | 26       | 1.04%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 25       | 1%      |
| AMD Ryzen 7 5800X 8-Core Processor          | 24       | 0.96%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 23       | 0.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 23       | 0.92%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 23       | 0.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 23       | 0.92%   |
| AMD FX-6300 Six-Core Processor              | 23       | 0.92%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 22       | 0.88%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 22       | 0.88%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 22       | 0.88%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 22       | 0.88%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 20       | 0.8%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 20       | 0.8%    |
| AMD Ryzen 5 2600X Six-Core Processor        | 20       | 0.8%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 19       | 0.76%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 19       | 0.76%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 19       | 0.76%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 19       | 0.76%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 18       | 0.72%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 18       | 0.72%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 18       | 0.72%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 18       | 0.72%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 17       | 0.68%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 17       | 0.68%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 16       | 0.64%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 16       | 0.64%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 16       | 0.64%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 15       | 0.6%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 15       | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 424      | 17.06%  |
| AMD Ryzen 5             | 414      | 16.66%  |
| Intel Core i7           | 345      | 13.88%  |
| AMD Ryzen 7             | 279      | 11.23%  |
| Intel Core i3           | 131      | 5.27%   |
| Intel Xeon              | 121      | 4.87%   |
| AMD Ryzen 9             | 116      | 4.67%   |
| AMD FX                  | 107      | 4.31%   |
| Other                   | 51       | 2.05%   |
| AMD Ryzen 3             | 46       | 1.85%   |
| Intel Core 2 Duo        | 43       | 1.73%   |
| Intel Celeron           | 34       | 1.37%   |
| Intel Pentium           | 31       | 1.25%   |
| AMD Ryzen Threadripper  | 28       | 1.13%   |
| Intel Core 2 Quad       | 26       | 1.05%   |
| AMD Phenom II X4        | 26       | 1.05%   |
| Intel Pentium Dual-Core | 22       | 0.89%   |
| Intel Core i9           | 22       | 0.89%   |
| AMD Athlon II X2        | 19       | 0.76%   |
| AMD A10                 | 19       | 0.76%   |
| AMD A8                  | 18       | 0.72%   |
| AMD A4                  | 16       | 0.64%   |
| AMD Athlon              | 14       | 0.56%   |
| Intel Core 2            | 11       | 0.44%   |
| AMD Phenom II X6        | 11       | 0.44%   |
| AMD Athlon 64 X2        | 11       | 0.44%   |
| AMD Athlon X4           | 9        | 0.36%   |
| AMD Athlon II X4        | 9        | 0.36%   |
| Intel Atom              | 8        | 0.32%   |
| AMD Ryzen 5 PRO         | 8        | 0.32%   |
| AMD Phenom              | 7        | 0.28%   |
| Intel Pentium Gold      | 6        | 0.24%   |
| Intel Pentium Dual      | 6        | 0.24%   |
| AMD Ryzen 7 PRO         | 6        | 0.24%   |
| Intel Genuine           | 5        | 0.2%    |
| AMD Athlon II X3        | 5        | 0.2%    |
| Intel Pentium D         | 4        | 0.16%   |
| AMD Sempron             | 4        | 0.16%   |
| AMD Phenom II X2        | 3        | 0.12%   |
| AMD E1                  | 3        | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 869      | 34.96%  |
| 6       | 589      | 23.69%  |
| 2       | 382      | 15.37%  |
| 8       | 368      | 14.8%   |
| 12      | 108      | 4.34%   |
| 16      | 65       | 2.61%   |
| 3       | 44       | 1.77%   |
| 1       | 28       | 1.13%   |
| 10      | 18       | 0.72%   |
| 24      | 7        | 0.28%   |
| 32      | 3        | 0.12%   |
| 20      | 2        | 0.08%   |
| Unknown | 2        | 0.08%   |
| 14      | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2456     | 99.15%  |
| 2      | 21       | 0.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1675     | 67.43%  |
| 1       | 807      | 32.49%  |
| Unknown | 2        | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2449     | 98.67%  |
| Unknown        | 33       | 1.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1275     | 49.67%  |
| 0x08701021 | 133      | 5.18%   |
| 0x306c3    | 102      | 3.97%   |
| 0x0800820d | 101      | 3.93%   |
| 0x08701013 | 76       | 2.96%   |
| 0x306a9    | 67       | 2.61%   |
| 0x206a7    | 62       | 2.42%   |
| 0x906ea    | 57       | 2.22%   |
| 0x506e3    | 50       | 1.95%   |
| 0x06000852 | 47       | 1.83%   |
| 0x1067a    | 35       | 1.36%   |
| 0x08001138 | 32       | 1.25%   |
| 0x906e9    | 28       | 1.09%   |
| 0x306f2    | 23       | 0.9%    |
| 0x0a201016 | 23       | 0.9%    |
| 0x010000c8 | 23       | 0.9%    |
| 0x0a201009 | 22       | 0.86%   |
| 0x08108109 | 20       | 0.78%   |
| 0x206d7    | 19       | 0.74%   |
| 0x08001137 | 19       | 0.74%   |
| 0x08101016 | 16       | 0.62%   |
| 0x06003106 | 14       | 0.55%   |
| 0xa0655    | 13       | 0.51%   |
| 0x906ed    | 13       | 0.51%   |
| 0x06001119 | 13       | 0.51%   |
| 0x106e5    | 12       | 0.47%   |
| 0x90672    | 11       | 0.43%   |
| 0x08600106 | 11       | 0.43%   |
| 0x0a20120a | 10       | 0.39%   |
| 0x0a50000c | 9        | 0.35%   |
| 0x08001129 | 9        | 0.35%   |
| 0xa0671    | 8        | 0.31%   |
| 0xa0653    | 8        | 0.31%   |
| 0x906ec    | 8        | 0.31%   |
| 0x906eb    | 8        | 0.31%   |
| 0x6fd      | 8        | 0.31%   |
| 0x406f1    | 7        | 0.27%   |
| 0x10676    | 7        | 0.27%   |
| 0x0a601203 | 7        | 0.27%   |
| 0x0a50000d | 7        | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 353      | 14.19%  |
| Haswell          | 262      | 10.53%  |
| KabyLake         | 251      | 10.09%  |
| Zen+             | 236      | 9.49%   |
| Zen              | 163      | 6.55%   |
| SandyBridge      | 158      | 6.35%   |
| IvyBridge        | 156      | 6.27%   |
| Zen 3            | 148      | 5.95%   |
| Piledriver       | 119      | 4.78%   |
| Skylake          | 112      | 4.5%    |
| Penryn           | 89       | 3.58%   |
| K10              | 81       | 3.26%   |
| CometLake        | 55       | 2.21%   |
| Unknown          | 49       | 1.97%   |
| Core             | 39       | 1.57%   |
| Nehalem          | 33       | 1.33%   |
| Westmere         | 30       | 1.21%   |
| Steamroller      | 26       | 1.05%   |
| Broadwell        | 19       | 0.76%   |
| Bulldozer        | 18       | 0.72%   |
| K8 Hammer        | 14       | 0.56%   |
| Alderlake Hybrid | 12       | 0.48%   |
| Excavator        | 8        | 0.32%   |
| Icelake          | 7        | 0.28%   |
| Goldmont plus    | 7        | 0.28%   |
| Bonnell          | 7        | 0.28%   |
| Silvermont       | 6        | 0.24%   |
| NetBurst         | 6        | 0.24%   |
| Goldmont         | 6        | 0.24%   |
| K10 Llano        | 5        | 0.2%    |
| Jaguar           | 4        | 0.16%   |
| Bobcat           | 4        | 0.16%   |
| Puma             | 2        | 0.08%   |
| Tremont          | 1        | 0.04%   |
| TigerLake        | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1253     | 46.91%  |
| AMD                        | 947      | 35.45%  |
| Intel                      | 469      | 17.56%  |
| Matrox Electronics Systems | 1        | 0.04%   |
| ATI Technologies           | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 235      | 8.55%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 92       | 3.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 87       | 3.16%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 85       | 3.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 85       | 3.09%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 62       | 2.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 56       | 2.04%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 53       | 1.93%   |
| Nvidia GK208B [GeForce GT 710]                                              | 52       | 1.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 50       | 1.82%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 42       | 1.53%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 41       | 1.49%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 39       | 1.42%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 39       | 1.42%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 38       | 1.38%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 34       | 1.24%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 34       | 1.24%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 33       | 1.2%    |
| Intel HD Graphics 530                                                       | 31       | 1.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 30       | 1.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 30       | 1.09%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 28       | 1.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 28       | 1.02%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 27       | 0.98%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 26       | 0.95%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 24       | 0.87%   |
| Intel HD Graphics 630                                                       | 23       | 0.84%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 23       | 0.84%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 23       | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 22       | 0.8%    |
| Nvidia GK208B [GeForce GT 730]                                              | 21       | 0.76%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 21       | 0.76%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 20       | 0.73%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 20       | 0.73%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 20       | 0.73%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 20       | 0.73%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 19       | 0.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 19       | 0.69%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 19       | 0.69%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 17       | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 1142     | 45.41%  |
| 1 x AMD            | 863      | 34.31%  |
| 1 x Intel          | 344      | 13.68%  |
| Intel + Nvidia     | 48       | 1.91%   |
| AMD + Nvidia       | 38       | 1.51%   |
| 2 x AMD            | 37       | 1.47%   |
| 2 x Nvidia         | 26       | 1.03%   |
| Intel + AMD        | 14       | 0.56%   |
| 1 x Matrox         | 1        | 0.04%   |
| Intel + 2 x Nvidia | 1        | 0.04%   |
| Intel + 2 x AMD    | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1474     | 58.77%  |
| Proprietary | 1022     | 40.75%  |
| Unknown     | 12       | 0.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1015     | 39.74%  |
| 7.01-8.0   | 392      | 15.35%  |
| 1.01-2.0   | 310      | 12.14%  |
| 3.01-4.0   | 266      | 10.42%  |
| 5.01-6.0   | 174      | 6.81%   |
| 0.51-1.0   | 153      | 5.99%   |
| 8.01-16.0  | 100      | 3.92%   |
| 0.01-0.5   | 83       | 3.25%   |
| 2.01-3.0   | 46       | 1.8%    |
| 16.01-24.0 | 13       | 0.51%   |
| 4.01-5.0   | 2        | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 465      | 15.74%  |
| Goldstar             | 315      | 10.66%  |
| Dell                 | 272      | 9.21%   |
| Acer                 | 240      | 8.12%   |
| AOC                  | 182      | 6.16%   |
| Ancor Communications | 177      | 5.99%   |
| BenQ                 | 171      | 5.79%   |
| Hewlett-Packard      | 141      | 4.77%   |
| Philips              | 119      | 4.03%   |
| LG Electronics       | 98       | 3.32%   |
| ViewSonic            | 66       | 2.23%   |
| ASUSTek Computer     | 62       | 2.1%    |
| Lenovo               | 46       | 1.56%   |
| Iiyama               | 43       | 1.46%   |
| Unknown              | 42       | 1.42%   |
| Unknown              | 28       | 0.95%   |
| Sony                 | 27       | 0.91%   |
| Vizio                | 21       | 0.71%   |
| MSI                  | 19       | 0.64%   |
| Eizo                 | 18       | 0.61%   |
| AUS                  | 17       | 0.58%   |
| Fujitsu Siemens      | 15       | 0.51%   |
| NEC Computers        | 14       | 0.47%   |
| Idek Iiyama          | 14       | 0.47%   |
| Gigabyte Technology  | 14       | 0.47%   |
| Sceptre Tech         | 12       | 0.41%   |
| Medion               | 12       | 0.41%   |
| Sharp                | 10       | 0.34%   |
| Vestel Elektronik    | 8        | 0.27%   |
| Microstep            | 8        | 0.27%   |
| Lenovo Group Limited | 8        | 0.27%   |
| HannStar             | 8        | 0.27%   |
| Toshiba              | 7        | 0.24%   |
| Panasonic            | 7        | 0.24%   |
| Pixio                | 6        | 0.2%    |
| KTC                  | 6        | 0.2%    |
| HPN                  | 6        | 0.2%    |
| Apple                | 6        | 0.2%    |
| Vestel               | 5        | 0.17%   |
| Plain Tree Systems   | 5        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown                                                                | 28       | 0.87%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 18       | 0.56%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 18       | 0.56%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 18       | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 13       | 0.4%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 11       | 0.34%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 10       | 0.31%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 9        | 0.28%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 9        | 0.28%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 9        | 0.28%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 8        | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 8        | 0.25%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch                | 8        | 0.25%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 8        | 0.25%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                       | 8        | 0.25%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 7        | 0.22%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 7        | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 7        | 0.22%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 7        | 0.22%   |
| AOC 27G1G4 AOC2701 1920x1080 598x336mm 27.0-inch                       | 7        | 0.22%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 7        | 0.22%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 6        | 0.19%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 6        | 0.19%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 6        | 0.19%   |
| Goldstar E2350 GSM5791 1920x1080 510x290mm 23.1-inch                   | 6        | 0.19%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                 | 6        | 0.19%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 6        | 0.19%   |
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch           | 6        | 0.19%   |
| AOC 24P2W1DG5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 6        | 0.19%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                       | 6        | 0.19%   |
| AOC 1970W-1 AOC1970 1366x768 410x230mm 18.5-inch                       | 6        | 0.19%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 6        | 0.19%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch       | 6        | 0.19%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 6        | 0.19%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 6        | 0.19%   |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch  | 6        | 0.19%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 5        | 0.16%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 5        | 0.16%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 5        | 0.16%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch      | 5        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1264     | 43.98%  |
| 2560x1440 (QHD)    | 272      | 9.46%   |
| 3840x2160 (4K)     | 265      | 9.22%   |
| Unknown            | 163      | 5.67%   |
| 1680x1050 (WSXGA+) | 118      | 4.11%   |
| 1280x1024 (SXGA)   | 114      | 3.97%   |
| 1366x768 (WXGA)    | 76       | 2.64%   |
| 3440x1440          | 74       | 2.57%   |
| 1920x1200 (WUXGA)  | 74       | 2.57%   |
| 1440x900 (WXGA+)   | 71       | 2.47%   |
| 3840x1080          | 65       | 2.26%   |
| 2560x1080          | 64       | 2.23%   |
| 1600x900 (HD+)     | 56       | 1.95%   |
| 1360x768           | 25       | 0.87%   |
| 4480x1440          | 12       | 0.42%   |
| 5760x1080          | 10       | 0.35%   |
| 5120x1440          | 10       | 0.35%   |
| 1920x540           | 10       | 0.35%   |
| 1280x720 (HD)      | 9        | 0.31%   |
| 1024x768 (XGA)     | 9        | 0.31%   |
| 5760x2160          | 7        | 0.24%   |
| 3600x1080          | 7        | 0.24%   |
| 2560x1600          | 7        | 0.24%   |
| 3840x1600          | 5        | 0.17%   |
| 3360x1080          | 5        | 0.17%   |
| 3200x1080          | 5        | 0.17%   |
| 1600x1200          | 5        | 0.17%   |
| 7680x2160          | 4        | 0.14%   |
| 6400x2160          | 4        | 0.14%   |
| 3840x1200          | 4        | 0.14%   |
| 3520x1080          | 4        | 0.14%   |
| 3286x1080          | 3        | 0.1%    |
| 5504x1440          | 2        | 0.07%   |
| 5120x1080          | 2        | 0.07%   |
| 4480x1080          | 2        | 0.07%   |
| 4240x1440          | 2        | 0.07%   |
| 3360x1050          | 2        | 0.07%   |
| 2944x1080          | 2        | 0.07%   |
| 2880x900           | 2        | 0.07%   |
| 2720x1024          | 2        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 503      | 17.71%  |
| 24      | 402      | 14.15%  |
| 27      | 397      | 13.97%  |
| 23      | 331      | 11.65%  |
| 21      | 293      | 10.31%  |
| 19      | 123      | 4.33%   |
| 31      | 112      | 3.94%   |
| 34      | 106      | 3.73%   |
| 22      | 81       | 2.85%   |
| 18      | 70       | 2.46%   |
| 20      | 63       | 2.22%   |
| 17      | 50       | 1.76%   |
| 84      | 34       | 1.2%    |
| 32      | 22       | 0.77%   |
| 72      | 21       | 0.74%   |
| 40      | 20       | 0.7%    |
| 25      | 20       | 0.7%    |
| 54      | 19       | 0.67%   |
| 15      | 15       | 0.53%   |
| 28      | 12       | 0.42%   |
| 65      | 11       | 0.39%   |
| 49      | 10       | 0.35%   |
| 48      | 10       | 0.35%   |
| 33      | 9        | 0.32%   |
| 43      | 8        | 0.28%   |
| 46      | 7        | 0.25%   |
| 37      | 7        | 0.25%   |
| 29      | 7        | 0.25%   |
| 26      | 7        | 0.25%   |
| 12      | 7        | 0.25%   |
| 36      | 6        | 0.21%   |
| 14      | 6        | 0.21%   |
| 42      | 5        | 0.18%   |
| 39      | 5        | 0.18%   |
| 35      | 5        | 0.18%   |
| 60      | 4        | 0.14%   |
| 52      | 4        | 0.14%   |
| 47      | 4        | 0.14%   |
| 16      | 4        | 0.14%   |
| 64      | 3        | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 1009     | 37.14%  |
| 401-500     | 549      | 20.21%  |
| Unknown     | 503      | 18.51%  |
| 601-700     | 168      | 6.18%   |
| 701-800     | 143      | 5.26%   |
| 351-400     | 80       | 2.94%   |
| 1001-1500   | 73       | 2.69%   |
| 301-350     | 61       | 2.25%   |
| 1501-2000   | 60       | 2.21%   |
| 801-900     | 42       | 1.55%   |
| 201-300     | 16       | 0.59%   |
| 901-1000    | 13       | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1557     | 60.47%  |
| Unknown | 471      | 18.29%  |
| 16/10   | 254      | 9.86%   |
| 21/9    | 116      | 4.5%    |
| 5/4     | 108      | 4.19%   |
| 4/3     | 29       | 1.13%   |
| 3/2     | 18       | 0.7%    |
| 32/9    | 12       | 0.47%   |
| 6/5     | 5        | 0.19%   |
| 3.20    | 1        | 0.04%   |
| 1.96    | 1        | 0.04%   |
| 1.03    | 1        | 0.04%   |
| 0.80    | 1        | 0.04%   |
| 0.56    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 889      | 31.98%  |
| Unknown        | 503      | 18.09%  |
| 301-350        | 399      | 14.35%  |
| 351-500        | 268      | 9.64%   |
| 151-200        | 254      | 9.14%   |
| 251-300        | 140      | 5.04%   |
| More than 1000 | 113      | 4.06%   |
| 141-150        | 96       | 3.45%   |
| 501-1000       | 76       | 2.73%   |
| 101-110        | 18       | 0.65%   |
| 131-140        | 8        | 0.29%   |
| 71-80          | 7        | 0.25%   |
| 81-90          | 2        | 0.07%   |
| 51-60          | 2        | 0.07%   |
| 111-120        | 2        | 0.07%   |
| 91-100         | 2        | 0.07%   |
| 121-130        | 1        | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1398     | 52.99%  |
| Unknown | 503      | 19.07%  |
| 101-120 | 502      | 19.03%  |
| 121-160 | 95       | 3.6%    |
| 1-50    | 88       | 3.34%   |
| 161-240 | 52       | 1.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1833     | 72.28%  |
| 2     | 583      | 22.99%  |
| 3     | 80       | 3.15%   |
| 0     | 35       | 1.38%   |
| 4     | 5        | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1515     | 42.65%  |
| Intel                                  | 1123     | 31.62%  |
| Qualcomm Atheros                       | 188      | 5.29%   |
| Broadcom                               | 100      | 2.82%   |
| Ralink Technology                      | 90       | 2.53%   |
| TP-Link                                | 88       | 2.48%   |
| Microsoft                              | 45       | 1.27%   |
| Aquantia                               | 31       | 0.87%   |
| Nvidia                                 | 30       | 0.84%   |
| MediaTek                               | 29       | 0.82%   |
| Ralink                                 | 26       | 0.73%   |
| Qualcomm Atheros Communications        | 24       | 0.68%   |
| Samsung Electronics                    | 21       | 0.59%   |
| Xiaomi                                 | 18       | 0.51%   |
| ASUSTek Computer                       | 17       | 0.48%   |
| NetGear                                | 15       | 0.42%   |
| Marvell Technology Group               | 15       | 0.42%   |
| D-Link                                 | 15       | 0.42%   |
| Huawei Technologies                    | 13       | 0.37%   |
| Broadcom Limited                       | 12       | 0.34%   |
| Linksys                                | 11       | 0.31%   |
| D-Link System                          | 9        | 0.25%   |
| Microchip Technology                   | 8        | 0.23%   |
| Edimax Technology                      | 7        | 0.2%    |
| Mellanox Technologies                  | 6        | 0.17%   |
| Motorola PCS                           | 5        | 0.14%   |
| ASIX Electronics                       | 5        | 0.14%   |
| ZyXEL Communications                   | 4        | 0.11%   |
| InterBiometrics                        | 4        | 0.11%   |
| T & A Mobile Phones                    | 3        | 0.08%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.08%   |
| SEGGER                                 | 3        | 0.08%   |
| Qualcomm                               | 3        | 0.08%   |
| OPPO Electronics                       | 3        | 0.08%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.08%   |
| JMicron Technology                     | 3        | 0.08%   |
| IMC Networks                           | 3        | 0.08%   |
| Google                                 | 3        | 0.08%   |
| Belkin Components                      | 3        | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 3        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1236     | 30.23%  |
| Intel I211 Gigabit Network Connection                             | 279      | 6.82%   |
| Intel Wi-Fi 6 AX200                                               | 189      | 4.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 140      | 3.42%   |
| Intel Ethernet Connection (2) I219-V                              | 121      | 2.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 80       | 1.96%   |
| Intel Ethernet Controller I225-V                                  | 77       | 1.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 64       | 1.57%   |
| Intel Ethernet Connection (7) I219-V                              | 56       | 1.37%   |
| Intel Wireless-AC 9260                                            | 48       | 1.17%   |
| Intel 82579V Gigabit Network Connection                           | 47       | 1.15%   |
| Intel Ethernet Connection (2) I218-V                              | 43       | 1.05%   |
| Intel Ethernet Connection I217-V                                  | 37       | 0.9%    |
| Intel Ethernet Connection I217-LM                                 | 37       | 0.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33       | 0.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 32       | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 32       | 0.78%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 31       | 0.76%   |
| Ralink MT7601U Wireless Adapter                                   | 30       | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 29       | 0.71%   |
| Realtek 802.11ac NIC                                              | 26       | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26       | 0.64%   |
| Microsoft Xbox 360 Wireless Adapter                               | 25       | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                   | 24       | 0.59%   |
| Intel 82574L Gigabit Network Connection                           | 23       | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 22       | 0.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 22       | 0.54%   |
| Intel Wireless 7265                                               | 22       | 0.54%   |
| Intel Wireless 8265 / 8275                                        | 20       | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19       | 0.46%   |
| Nvidia MCP61 Ethernet                                             | 19       | 0.46%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17       | 0.42%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 17       | 0.42%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 17       | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16       | 0.39%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 16       | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 16       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 463      | 36.31%  |
| Realtek Semiconductor                 | 253      | 19.84%  |
| Qualcomm Atheros                      | 95       | 7.45%   |
| Ralink Technology                     | 90       | 7.06%   |
| TP-Link                               | 87       | 6.82%   |
| Broadcom                              | 64       | 5.02%   |
| Microsoft                             | 45       | 3.53%   |
| Ralink                                | 26       | 2.04%   |
| Qualcomm Atheros Communications       | 24       | 1.88%   |
| MediaTek                              | 23       | 1.8%    |
| ASUSTek Computer                      | 17       | 1.33%   |
| NetGear                               | 15       | 1.18%   |
| D-Link                                | 15       | 1.18%   |
| Linksys                               | 11       | 0.86%   |
| Edimax Technology                     | 7        | 0.55%   |
| D-Link System                         | 6        | 0.47%   |
| Broadcom Limited                      | 5        | 0.39%   |
| ZyXEL Communications                  | 4        | 0.31%   |
| IMC Networks                          | 3        | 0.24%   |
| Belkin Components                     | 3        | 0.24%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.24%   |
| ZyDAS                                 | 2        | 0.16%   |
| Tenda                                 | 2        | 0.16%   |
| Mercucys                              | 2        | 0.16%   |
| AVM                                   | 2        | 0.16%   |
| Xiaomi                                | 1        | 0.08%   |
| Wacom                                 | 1        | 0.08%   |
| Senao                                 | 1        | 0.08%   |
| Samsung Electronics                   | 1        | 0.08%   |
| Philips (or NXP)                      | 1        | 0.08%   |
| Marvell Technology Group              | 1        | 0.08%   |
| Fujitsu Siemens Computers             | 1        | 0.08%   |
| Encore Electronics                    | 1        | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 189      | 14.69%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 64       | 4.97%   |
| Intel Wireless-AC 9260                                         | 48       | 3.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 32       | 2.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 32       | 2.49%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 31       | 2.41%   |
| Ralink MT7601U Wireless Adapter                                | 30       | 2.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 29       | 2.25%   |
| Realtek 802.11ac NIC                                           | 26       | 2.02%   |
| Microsoft Xbox 360 Wireless Adapter                            | 25       | 1.94%   |
| Qualcomm Atheros AR9271 802.11n                                | 24       | 1.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 22       | 1.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 22       | 1.71%   |
| Intel Wireless 7265                                            | 22       | 1.71%   |
| Intel Wireless 8265 / 8275                                     | 20       | 1.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 17       | 1.32%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 17       | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16       | 1.24%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 16       | 1.24%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 15       | 1.17%   |
| Ralink RT5370 Wireless Adapter                                 | 15       | 1.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 15       | 1.17%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 15       | 1.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 13       | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13       | 1.01%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 13       | 1.01%   |
| Intel Wireless 3165                                            | 12       | 0.93%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 11       | 0.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 11       | 0.85%   |
| Intel Wireless 7260                                            | 11       | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 10       | 0.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 10       | 0.78%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 9        | 0.7%    |
| TP-Link 802.11ac NIC                                           | 9        | 0.7%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 9        | 0.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 9        | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 9        | 0.7%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 9        | 0.7%    |
| Intel Wireless 8260                                            | 9        | 0.7%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 8        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1427     | 53.69%  |
| Intel                                  | 908      | 34.16%  |
| Qualcomm Atheros                       | 108      | 4.06%   |
| Broadcom                               | 39       | 1.47%   |
| Aquantia                               | 31       | 1.17%   |
| Nvidia                                 | 30       | 1.13%   |
| Xiaomi                                 | 17       | 0.64%   |
| Marvell Technology Group               | 14       | 0.53%   |
| Samsung Electronics                    | 11       | 0.41%   |
| Huawei Technologies                    | 11       | 0.41%   |
| Broadcom Limited                       | 7        | 0.26%   |
| Mellanox Technologies                  | 6        | 0.23%   |
| ASIX Electronics                       | 5        | 0.19%   |
| MediaTek                               | 4        | 0.15%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.11%   |
| OPPO Electronics                       | 3        | 0.11%   |
| JMicron Technology                     | 3        | 0.11%   |
| Google                                 | 3        | 0.11%   |
| D-Link System                          | 3        | 0.11%   |
| T & A Mobile Phones                    | 2        | 0.08%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.08%   |
| Qualcomm                               | 2        | 0.08%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.08%   |
| National Semiconductor                 | 2        | 0.08%   |
| Motorola PCS                           | 2        | 0.08%   |
| HMD Global                             | 2        | 0.08%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.04%   |
| VIA Technologies                       | 1        | 0.04%   |
| TP-Link                                | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.04%   |
| NetXen Incorporated                    | 1        | 0.04%   |
| LG Electronics                         | 1        | 0.04%   |
| ICS Advent                             | 1        | 0.04%   |
| Foxconn / Hon Hai                      | 1        | 0.04%   |
| DisplayLink                            | 1        | 0.04%   |
| Apple                                  | 1        | 0.04%   |
| Accton Technology                      | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1236     | 44.93%  |
| Intel I211 Gigabit Network Connection                             | 279      | 10.14%  |
| Realtek RTL8125 2.5GbE Controller                                 | 140      | 5.09%   |
| Intel Ethernet Connection (2) I219-V                              | 121      | 4.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 80       | 2.91%   |
| Intel Ethernet Controller I225-V                                  | 77       | 2.8%    |
| Intel Ethernet Connection (7) I219-V                              | 56       | 2.04%   |
| Intel 82579V Gigabit Network Connection                           | 47       | 1.71%   |
| Intel Ethernet Connection (2) I218-V                              | 43       | 1.56%   |
| Intel Ethernet Connection I217-V                                  | 37       | 1.34%   |
| Intel Ethernet Connection I217-LM                                 | 37       | 1.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33       | 1.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26       | 0.95%   |
| Intel 82574L Gigabit Network Connection                           | 23       | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19       | 0.69%   |
| Nvidia MCP61 Ethernet                                             | 19       | 0.69%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17       | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 16       | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14       | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13       | 0.47%   |
| Intel I210 Gigabit Network Connection                             | 12       | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11       | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 10       | 0.36%   |
| Intel Ethernet Connection (11) I219-V                             | 10       | 0.36%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 10       | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9        | 0.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9        | 0.33%   |
| Intel Ethernet Connection (14) I219-V                             | 9        | 0.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 0.29%   |
| Intel Ethernet Connection (2) I218-LM                             | 8        | 0.29%   |
| Intel Ethernet Connection (12) I219-V                             | 7        | 0.25%   |
| Huawei ATU-L21                                                    | 7        | 0.25%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7        | 0.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 6        | 0.22%   |
| Intel 82578DC Gigabit Network Connection                          | 6        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2452     | 66.7%   |
| WiFi     | 1175     | 31.96%  |
| Modem    | 41       | 1.12%   |
| Unknown  | 8        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1967     | 76.33%  |
| WiFi     | 610      | 23.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1573     | 62.92%  |
| 2     | 777      | 31.08%  |
| 3     | 114      | 4.56%   |
| 0     | 19       | 0.76%   |
| 5     | 8        | 0.32%   |
| 4     | 7        | 0.28%   |
| 8     | 1        | 0.04%   |
| 7     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2083     | 82.56%  |
| Yes  | 440      | 17.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 435      | 40.81%  |
| Cambridge Silicon Radio         | 299      | 28.05%  |
| ASUSTek Computer                | 98       | 9.19%   |
| Realtek Semiconductor           | 68       | 6.38%   |
| Broadcom                        | 53       | 4.97%   |
| Qualcomm Atheros Communications | 16       | 1.5%    |
| Apple                           | 14       | 1.31%   |
| IMC Networks                    | 13       | 1.22%   |
| TP-Link                         | 11       | 1.03%   |
| Edimax Technology               | 8        | 0.75%   |
| MediaTek                        | 7        | 0.66%   |
| Foxconn / Hon Hai               | 7        | 0.66%   |
| Dynex                           | 6        | 0.56%   |
| HTC (High Tech Computer)        | 5        | 0.47%   |
| Realtek                         | 4        | 0.38%   |
| Lite-On Technology              | 4        | 0.38%   |
| Conwise Technology              | 4        | 0.38%   |
| SINO WEALTH                     | 3        | 0.28%   |
| Integrated System Solution      | 3        | 0.28%   |
| Belkin Components               | 3        | 0.28%   |
| Ralink                          | 2        | 0.19%   |
| Sitecom Europe                  | 1        | 0.09%   |
| Micro Star International        | 1        | 0.09%   |
| D-Link                          | 1        | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 299      | 27.94%  |
| Intel AX200 Bluetooth                                                | 174      | 16.26%  |
| Intel Bluetooth wireless interface                                   | 72       | 6.73%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 63       | 5.89%   |
| Realtek Bluetooth Radio                                              | 54       | 5.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 48       | 4.49%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 39       | 3.64%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 35       | 3.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 33       | 3.08%   |
| Intel AX201 Bluetooth                                                | 24       | 2.24%   |
| Intel AX210 Bluetooth                                                | 15       | 1.4%    |
| ASUS Bluetooth Radio                                                 | 15       | 1.4%    |
| ASUS ASUS USB-BT500                                                  | 14       | 1.31%   |
| ASUS Bluetooth Adapter                                               | 13       | 1.21%   |
| TP-Link UB500 Adapter                                                | 11       | 1.03%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 10       | 0.93%   |
| ASUS BCM20702A0                                                      | 10       | 0.93%   |
| Qualcomm Atheros  Bluetooth Device                                   | 8        | 0.75%   |
| IMC Networks Bluetooth Radio                                         | 8        | 0.75%   |
| MediaTek Wireless_Device                                             | 7        | 0.65%   |
| Apple Bluetooth Host Controller                                      | 7        | 0.65%   |
| Edimax Bluetooth Adapter                                             | 6        | 0.56%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 6        | 0.56%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.56%   |
| Intel Bluetooth Device                                               | 5        | 0.47%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 5        | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 4        | 0.37%   |
| Foxconn / Hon Hai Wireless_Device                                    | 4        | 0.37%   |
| Conwise CW6622                                                       | 4        | 0.37%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 4        | 0.37%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 3        | 0.28%   |
| Realtek Bluetooth 5.1 Radio                                          | 3        | 0.28%   |
| Realtek Bluetooth Radio                                              | 3        | 0.28%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 0.28%   |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 3        | 0.28%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 3        | 0.28%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                            | 3        | 0.28%   |
| Ralink RT3290 Bluetooth                                              | 2        | 0.19%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 0.19%   |
| Lite-On Bluetooth Device                                             | 2        | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 1409     | 29.22%  |
| Intel                                | 1246     | 25.84%  |
| Nvidia                               | 1199     | 24.87%  |
| C-Media Electronics                  | 179      | 3.71%   |
| Creative Labs                        | 70       | 1.45%   |
| Logitech                             | 68       | 1.41%   |
| Kingston Technology                  | 45       | 0.93%   |
| JMTek                                | 38       | 0.79%   |
| Texas Instruments                    | 34       | 0.71%   |
| Corsair                              | 33       | 0.68%   |
| SteelSeries ApS                      | 28       | 0.58%   |
| Creative Technology                  | 28       | 0.58%   |
| Focusrite-Novation                   | 27       | 0.56%   |
| Blue Microphones                     | 26       | 0.54%   |
| Razer USA                            | 25       | 0.52%   |
| ASUSTek Computer                     | 25       | 0.52%   |
| Generalplus Technology               | 23       | 0.48%   |
| BEHRINGER International              | 20       | 0.41%   |
| Sony                                 | 14       | 0.29%   |
| Plantronics                          | 14       | 0.29%   |
| Realtek Semiconductor                | 11       | 0.23%   |
| GYROCOM C&C                          | 11       | 0.23%   |
| VIA Technologies                     | 9        | 0.19%   |
| M-Audio                              | 9        | 0.19%   |
| Sennheiser Communications            | 8        | 0.17%   |
| Samson Technologies                  | 8        | 0.17%   |
| Turtle Beach                         | 7        | 0.15%   |
| SAVITECH                             | 7        | 0.15%   |
| RODE Microphones                     | 7        | 0.15%   |
| GN Netcom                            | 7        | 0.15%   |
| Giga-Byte Technology                 | 7        | 0.15%   |
| Dell                                 | 7        | 0.15%   |
| Yamaha                               | 6        | 0.12%   |
| XMOS                                 | 6        | 0.12%   |
| Micro Star International             | 6        | 0.12%   |
| Astro Gaming                         | 6        | 0.12%   |
| Valve Software                       | 5        | 0.1%    |
| Elgato Systems                       | 5        | 0.1%    |
| DCMT Technology                      | 5        | 0.1%    |
| Thesycon Systemsoftware & Consulting | 4        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 425      | 7.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 299      | 5.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 237      | 4.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 163      | 2.89%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 162      | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 154      | 2.73%   |
| AMD Family 17h/19h HD Audio Controller                                     | 154      | 2.73%   |
| Intel 200 Series PCH HD Audio                                              | 133      | 2.36%   |
| Nvidia GP104 High Definition Audio Controller                              | 125      | 2.21%   |
| Nvidia GP106 High Definition Audio Controller                              | 121      | 2.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 112      | 1.98%   |
| Nvidia GP107GL High Definition Audio Controller                            | 109      | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 109      | 1.93%   |
| AMD Navi 10 HDMI Audio                                                     | 108      | 1.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 100      | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 93       | 1.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 76       | 1.35%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 72       | 1.28%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 70       | 1.24%   |
| Nvidia TU116 High Definition Audio Controller                              | 69       | 1.22%   |
| AMD FCH Azalia Controller                                                  | 69       | 1.22%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 69       | 1.22%   |
| Nvidia GM204 High Definition Audio Controller                              | 62       | 1.1%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 62       | 1.1%    |
| Nvidia TU104 HD Audio Controller                                           | 60       | 1.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 60       | 1.06%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 58       | 1.03%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 56       | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 54       | 0.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 52       | 0.92%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 45       | 0.8%    |
| Nvidia GM206 High Definition Audio Controller                              | 43       | 0.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 43       | 0.76%   |
| Nvidia GP108 High Definition Audio Controller                              | 42       | 0.74%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 42       | 0.74%   |
| Nvidia GK104 HDMI Audio Controller                                         | 41       | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                              | 40       | 0.71%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 37       | 0.66%   |
| Nvidia GP102 HDMI Audio Controller                                         | 35       | 0.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 34       | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 301      | 18.68%  |
| Kingston                     | 288      | 17.88%  |
| G.Skill                      | 226      | 14.03%  |
| Unknown                      | 196      | 12.17%  |
| Crucial                      | 147      | 9.12%   |
| Samsung Electronics          | 93       | 5.77%   |
| SK hynix                     | 61       | 3.79%   |
| Micron Technology            | 51       | 3.17%   |
| Team                         | 41       | 2.55%   |
| A-DATA Technology            | 40       | 2.48%   |
| Patriot                      | 31       | 1.92%   |
| Nanya Technology             | 11       | 0.68%   |
| GOODRAM                      | 11       | 0.68%   |
| Elpida                       | 9        | 0.56%   |
| Unknown                      | 9        | 0.56%   |
| Unknown (ABCD)               | 7        | 0.43%   |
| Ramaxel Technology           | 7        | 0.43%   |
| Kllisre                      | 5        | 0.31%   |
| GeIL                         | 5        | 0.31%   |
| Transcend                    | 4        | 0.25%   |
| Smart                        | 4        | 0.25%   |
| Silicon Power                | 4        | 0.25%   |
| PNY                          | 4        | 0.25%   |
| AMD                          | 4        | 0.25%   |
| Kingmax                      | 3        | 0.19%   |
| CSX                          | 3        | 0.19%   |
| Apacer                       | 3        | 0.19%   |
| Unknown (08C8)               | 2        | 0.12%   |
| Qumo                         | 2        | 0.12%   |
| Patriot Memory (PDP Systems) | 2        | 0.12%   |
| Patriot Memory               | 2        | 0.12%   |
| Neo Forza                    | 2        | 0.12%   |
| Wilk Elektronik              | 1        | 0.06%   |
| Unknown (AB)                 | 1        | 0.06%   |
| Unknown (0xAD44594E45540000) | 1        | 0.06%   |
| Unknown (0x8551)             | 1        | 0.06%   |
| Unknown (0x0416)             | 1        | 0.06%   |
| TwinMOS                      | 1        | 0.06%   |
| Thermaltake                  | 1        | 0.06%   |
| TEXTORM                      | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 42       | 2.36%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s       | 32       | 1.8%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 20       | 1.12%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 20       | 1.12%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 17       | 0.95%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 17       | 0.95%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 16       | 0.9%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 14       | 0.79%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 14       | 0.79%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 13       | 0.73%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 13       | 0.73%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s             | 11       | 0.62%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 10       | 0.56%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s             | 10       | 0.56%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 10       | 0.56%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s          | 10       | 0.56%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                    | 10       | 0.56%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 9        | 0.51%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s            | 9        | 0.51%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 9        | 0.51%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s          | 9        | 0.51%   |
| Unknown                                                        | 9        | 0.51%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 8        | 0.45%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s             | 8        | 0.45%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s          | 8        | 0.45%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM 1600MT/s                 | 8        | 0.45%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 7        | 0.39%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 7        | 0.39%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s            | 7        | 0.39%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s          | 7        | 0.39%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s            | 7        | 0.39%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s            | 7        | 0.39%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 6        | 0.34%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s          | 6        | 0.34%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 6        | 0.34%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 6        | 0.34%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s            | 6        | 0.34%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s             | 6        | 0.34%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s             | 6        | 0.34%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s         | 6        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 847      | 58.53%  |
| DDR3    | 406      | 28.06%  |
| Unknown | 79       | 5.46%   |
| DDR2    | 42       | 2.9%    |
| SDRAM   | 38       | 2.63%   |
| DDR5    | 14       | 0.97%   |
| DDR     | 12       | 0.83%   |
| LPDDR4  | 7        | 0.48%   |
| LPDDR3  | 1        | 0.07%   |
| DRAM    | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1389     | 97.06%  |
| SODIMM  | 36       | 2.52%   |
| RIMM    | 3        | 0.21%   |
| FB-DIMM | 3        | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 697      | 44.45%  |
| 4096  | 318      | 20.28%  |
| 16384 | 292      | 18.62%  |
| 2048  | 143      | 9.12%   |
| 32768 | 73       | 4.66%   |
| 1024  | 40       | 2.55%   |
| 512   | 4        | 0.26%   |
| 3072  | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 230      | 14.28%  |
| 3200    | 203      | 12.6%   |
| 3600    | 175      | 10.86%  |
| 1333    | 141      | 8.75%   |
| 2400    | 92       | 5.71%   |
| 2133    | 73       | 4.53%   |
| 2667    | 71       | 4.41%   |
| 3466    | 57       | 3.54%   |
| 3400    | 52       | 3.23%   |
| 1867    | 52       | 3.23%   |
| 3000    | 49       | 3.04%   |
| 800     | 45       | 2.79%   |
| 3800    | 32       | 1.99%   |
| 1866    | 30       | 1.86%   |
| 667     | 28       | 1.74%   |
| 3866    | 27       | 1.68%   |
| 3733    | 25       | 1.55%   |
| 2933    | 19       | 1.18%   |
| Unknown | 17       | 1.06%   |
| 3266    | 15       | 0.93%   |
| 2666    | 15       | 0.93%   |
| 2800    | 14       | 0.87%   |
| 1066    | 14       | 0.87%   |
| 1800    | 11       | 0.68%   |
| 3666    | 10       | 0.62%   |
| 4800    | 7        | 0.43%   |
| 3334    | 6        | 0.37%   |
| 2448    | 6        | 0.37%   |
| 1334    | 6        | 0.37%   |
| 3534    | 5        | 0.31%   |
| 1067    | 5        | 0.31%   |
| 333     | 5        | 0.31%   |
| 5200    | 4        | 0.25%   |
| 3500    | 4        | 0.25%   |
| 3100    | 4        | 0.25%   |
| 2048    | 4        | 0.25%   |
| 1648    | 4        | 0.25%   |
| 533     | 4        | 0.25%   |
| 400     | 4        | 0.25%   |
| 49926   | 3        | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 45       | 41.28%  |
| Brother Industries    | 20       | 18.35%  |
| Canon                 | 13       | 11.93%  |
| Seiko Epson           | 7        | 6.42%   |
| Samsung Electronics   | 6        | 5.5%    |
| Pantum                | 3        | 2.75%   |
| Apple                 | 3        | 2.75%   |
| Xerox                 | 2        | 1.83%   |
| Ricoh                 | 2        | 1.83%   |
| Prolific Technology   | 2        | 1.83%   |
| STMicroelectronics    | 1        | 0.92%   |
| QinHeng Electronics   | 1        | 0.92%   |
| Oki Data              | 1        | 0.92%   |
| Lexmark International | 1        | 0.92%   |
| Graphtec America      | 1        | 0.92%   |
| Dymo-CoStar           | 1        | 0.92%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP OfficeJet 5200 series                                  | 4        | 3.64%   |
| HP LaserJet 1300                                          | 3        | 2.73%   |
| Apple Gamesir-T1s 2.0b                                    | 3        | 2.73%   |
| Xerox Phaser 3020                                         | 2        | 1.82%   |
| Seiko Epson L120 Series                                   | 2        | 1.82%   |
| Samsung ML-1640 Series Laser Printer                      | 2        | 1.82%   |
| Prolific PL2305 Parallel Port                             | 2        | 1.82%   |
| HP Officejet 2620 series                                  | 2        | 1.82%   |
| HP DeskJet 4530 series                                    | 2        | 1.82%   |
| HP DeskJet 3630 series                                    | 2        | 1.82%   |
| HP DeskJet 2620 All-in-One Printer                        | 2        | 1.82%   |
| HP DeskJet 2130 series                                    | 2        | 1.82%   |
| HP Color LaserJet Pro M453-4                              | 2        | 1.82%   |
| Canon PIXMA MX340                                         | 2        | 1.82%   |
| Canon PIXMA MG2500 Series                                 | 2        | 1.82%   |
| Canon MG5700 series                                       | 2        | 1.82%   |
| Brother HL-5370DW series                                  | 2        | 1.82%   |
| Brother DCP-7040                                          | 2        | 1.82%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.91%   |
| Seiko Epson XP-4100 Series                                | 1        | 0.91%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1        | 0.91%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1        | 0.91%   |
| Seiko Epson L805 Series                                   | 1        | 0.91%   |
| Seiko Epson ET-4760 Series                                | 1        | 0.91%   |
| Seiko Epson ET-3850 Series                                | 1        | 0.91%   |
| Samsung ML-1660 Series                                    | 1        | 0.91%   |
| Samsung M2020 Series                                      | 1        | 0.91%   |
| Samsung CLX-3300 Series                                   | 1        | 0.91%   |
| Samsung CLP-310 Color Laser Printer                       | 1        | 0.91%   |
| Ricoh SP 112SU                                            | 1        | 0.91%   |
| Ricoh Printing Support                                    | 1        | 0.91%   |
| QinHeng CH340S                                            | 1        | 0.91%   |
| Pantum P2500W series                                      | 1        | 0.91%   |
| Pantum P2200 series                                       | 1        | 0.91%   |
| Pantum M6500 series                                       | 1        | 0.91%   |
| Oki Data USB Device                                       | 1        | 0.91%   |
| Lexmark International Lexmark MS312dn                     | 1        | 0.91%   |
| HP Smart Install                                          | 1        | 0.91%   |
| HP OfficeJet Pro 8020 series                              | 1        | 0.91%   |
| HP LaserJet P2015 series                                  | 1        | 0.91%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 12       | 52.17%  |
| Seiko Epson        | 5        | 21.74%  |
| Hewlett-Packard    | 2        | 8.7%    |
| Visioneer          | 1        | 4.35%   |
| Ultima Electronics | 1        | 4.35%   |
| Mustek Systems     | 1        | 4.35%   |
| AGFA-Gevaert NV    | 1        | 4.35%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 4        | 17.39%  |
| Canon CanoScan LiDE 220                                                               | 3        | 13.04%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 8.7%    |
| Canon CanoScan LIDE 25                                                                | 2        | 8.7%    |
| Visioneer OneTouch 5300 USB                                                           | 1        | 4.35%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 4.35%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 4.35%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 4.35%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1        | 4.35%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 4.35%   |
| HP ScanJet 3500c                                                                      | 1        | 4.35%   |
| HP ScanJet 3400cse                                                                    | 1        | 4.35%   |
| Canon CanoScan LiDE 90                                                                | 1        | 4.35%   |
| Canon CanoScan LiDE 210                                                               | 1        | 4.35%   |
| Canon CanoScan LiDE 120                                                               | 1        | 4.35%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1        | 4.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 239      | 41.14%  |
| Microsoft                     | 47       | 8.09%   |
| Microdia                      | 46       | 7.92%   |
| Samsung Electronics           | 23       | 3.96%   |
| Z-Star Microelectronics       | 19       | 3.27%   |
| Sunplus Innovation Technology | 15       | 2.58%   |
| Creative Technology           | 12       | 2.07%   |
| Apple                         | 10       | 1.72%   |
| GEMBIRD                       | 9        | 1.55%   |
| Generalplus Technology        | 8        | 1.38%   |
| Realtek Semiconductor         | 7        | 1.2%    |
| MacroSilicon                  | 7        | 1.2%    |
| Cubeternet                    | 7        | 1.2%    |
| LG Electronics                | 6        | 1.03%   |
| Google                        | 6        | 1.03%   |
| Chicony Electronics           | 6        | 1.03%   |
| ARC International             | 6        | 1.03%   |
| Valve Software                | 5        | 0.86%   |
| KYE Systems (Mouse Systems)   | 5        | 0.86%   |
| Aveo Technology               | 5        | 0.86%   |
| Pixart Imaging                | 4        | 0.69%   |
| Jieli Technology              | 4        | 0.69%   |
| Huawei Technologies           | 4        | 0.69%   |
| Genesys Logic                 | 4        | 0.69%   |
| Alcor Micro                   | 4        | 0.69%   |
| Xiongmai                      | 3        | 0.52%   |
| WCM_USB                       | 3        | 0.52%   |
| Sunplus IT                    | 3        | 0.52%   |
| Sonix Technology              | 3        | 0.52%   |
| SHENZHEN EMEET TECHNOLOGY     | 3        | 0.52%   |
| Razer USA                     | 3        | 0.52%   |
| Philips (or NXP)              | 3        | 0.52%   |
| Elgato Systems                | 3        | 0.52%   |
| AVerMedia Technologies        | 3        | 0.52%   |
| Arkmicro Technologies         | 3        | 0.52%   |
| 2M UVC CAMERA                 | 3        | 0.52%   |
| Xiaomi                        | 2        | 0.34%   |
| WaveRider Communications      | 2        | 0.34%   |
| Silicon Motion                | 2        | 0.34%   |
| OPPO Electronics              | 2        | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 59       | 10.1%   |
| Logitech HD Pro Webcam C920                           | 42       | 7.19%   |
| Samsung Galaxy series, misc. (MTP mode)               | 23       | 3.94%   |
| Microsoft LifeCam HD-3000                             | 21       | 3.6%    |
| Logitech C922 Pro Stream Webcam                       | 18       | 3.08%   |
| Microdia Webcam Vitade AF                             | 16       | 2.74%   |
| Z-Star Venus USB2.0 Camera                            | 11       | 1.88%   |
| Microdia USB 2.0 Camera                               | 11       | 1.88%   |
| Logitech Webcam C310                                  | 11       | 1.88%   |
| Logitech HD Webcam C615                               | 9        | 1.54%   |
| Logitech Webcam C170                                  | 8        | 1.37%   |
| Logitech HD Webcam C525                               | 8        | 1.37%   |
| GEMBIRD USB2.0 PC CAMERA                              | 8        | 1.37%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                       | 8        | 1.37%   |
| MacroSilicon USB Video                                | 7        | 1.2%    |
| Logitech Webcam C930e                                 | 7        | 1.2%    |
| Logitech C920 PRO HD Webcam                           | 7        | 1.2%    |
| Logitech BRIO Ultra HD Webcam                         | 7        | 1.2%    |
| Sunplus FHD Camera Microphone                         | 6        | 1.03%   |
| Sunplus Canyon CNS-CWC5 Webcam                        | 6        | 1.03%   |
| Microsoft LifeCam VX-2000                             | 6        | 1.03%   |
| Logitech StreamCam                                    | 6        | 1.03%   |
| Logitech B525 HD Webcam                               | 6        | 1.03%   |
| Valve Software 3D Camera                              | 5        | 0.86%   |
| Logitech Webcam Pro 9000                              | 5        | 0.86%   |
| Logitech HD Webcam C910                               | 5        | 0.86%   |
| Logitech HD Webcam C510                               | 5        | 0.86%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 5        | 0.86%   |
| ARC International Camera                              | 5        | 0.86%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 4        | 0.68%   |
| Microsoft LifeCam Cinema                              | 4        | 0.68%   |
| Logitech BRIO 4K Stream Edition                       | 4        | 0.68%   |
| Jieli USB PHY 2.0                                     | 4        | 0.68%   |
| Huawei HiCamera                                       | 4        | 0.68%   |
| Google Nexus/Pixel Device (MTP + debug)               | 4        | 0.68%   |
| Generalplus 808 Camera                                | 4        | 0.68%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]            | 4        | 0.68%   |
| Z-Star Vimicro USB Camera (Altair)                    | 3        | 0.51%   |
| Xiongmai web camera                                   | 3        | 0.51%   |
| WCM_USB WEB CAM                                       | 3        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 3        | 42.86%  |
| STMicroelectronics    | 1        | 14.29%  |
| LighTuning Technology | 1        | 14.29%  |
| Futronic Technology   | 1        | 14.29%  |
| AuthenTec             | 1        | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 3        | 42.86%  |
| STMicroelectronics Fingerprint Reader       | 1        | 14.29%  |
| LighTuning Fingerprint Sensor               | 1        | 14.29%  |
| Futronic FS81 Fingerprint Scanner Module    | 1        | 14.29%  |
| AuthenTec AES1600                           | 1        | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 5        | 21.74%  |
| Alcor Micro                       | 5        | 21.74%  |
| VASCO Data Security International | 4        | 17.39%  |
| Realtek Semiconductor             | 4        | 17.39%  |
| OmniKey                           | 2        | 8.7%    |
| SCM Microsystems                  | 1        | 4.35%   |
| Cherry                            | 1        | 4.35%   |
| Bit4id                            | 1        | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 5        | 21.74%  |
| Realtek Semiconductor Smart Card Reader Interface               | 4        | 17.39%  |
| Alcor Micro AU9540 Smartcard Reader                             | 4        | 17.39%  |
| VASCO Data Security International Digipass 905 SmartCard Reader | 2        | 8.7%    |
| OmniKey 3x21 Smart Card Reader                                  | 2        | 8.7%    |
| VASCO Data Security International DIGIPASS 920                  | 1        | 4.35%   |
| VASCO Data Security International DIGIPASS 870                  | 1        | 4.35%   |
| SCM Microsystems SCR331 SmartCard Reader                        | 1        | 4.35%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                     | 1        | 4.35%   |
| Bit4id miniLector EVO                                           | 1        | 4.35%   |
| Alcor Micro Watchdata W 1981                                    | 1        | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2165     | 85.64%  |
| 1     | 327      | 12.94%  |
| 2     | 33       | 1.31%   |
| 3     | 3        | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 152      | 39.69%  |
| Graphics card            | 53       | 13.84%  |
| Unassigned class         | 52       | 13.58%  |
| Camera                   | 20       | 5.22%   |
| Chipcard                 | 15       | 3.92%   |
| Multimedia controller    | 14       | 3.66%   |
| Net/ethernet             | 13       | 3.39%   |
| Sound                    | 12       | 3.13%   |
| Communication controller | 11       | 2.87%   |
| Bluetooth                | 10       | 2.61%   |
| Dvb card                 | 9        | 2.35%   |
| Storage/raid             | 6        | 1.57%   |
| Fingerprint reader       | 6        | 1.57%   |
| Network                  | 5        | 1.31%   |
| Storage/ide              | 2        | 0.52%   |
| Video                    | 1        | 0.26%   |
| Storage/ata              | 1        | 0.26%   |
| Storage                  | 1        | 0.26%   |

