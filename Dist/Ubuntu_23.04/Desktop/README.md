Ubuntu 23.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 23.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 719

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | B450M Pro4                  | [aded29632d](https://linux-hardware.org/?probe=aded29632d) | Apr 28, 2024 |
| ASRock        | Z77 Extreme3                | [83083ad34f](https://linux-hardware.org/?probe=83083ad34f) | Apr 26, 2024 |
| Gigabyte      | B760M AORUS ELITE           | [abd7f2bfbc](https://linux-hardware.org/?probe=abd7f2bfbc) | Apr 03, 2024 |
| HP            | 843B                        | [8d6b0674a6](https://linux-hardware.org/?probe=8d6b0674a6) | Feb 29, 2024 |
| Supermicro    | X10DRH-CT                   | [085564adc0](https://linux-hardware.org/?probe=085564adc0) | Feb 24, 2024 |
| Medion        | B360H4-EM V1.0              | [45981f1ad4](https://linux-hardware.org/?probe=45981f1ad4) | Feb 23, 2024 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | [0a9db7ec56](https://linux-hardware.org/?probe=0a9db7ec56) | Feb 16, 2024 |
| Gigabyte      | H81ND2H                     | [eca344c342](https://linux-hardware.org/?probe=eca344c342) | Feb 09, 2024 |
| ASRock        | Z270 Gaming-ITX/ac          | [b417d2ae80](https://linux-hardware.org/?probe=b417d2ae80) | Feb 07, 2024 |
| Shuttle       | FH87                        | [3f1a7051b6](https://linux-hardware.org/?probe=3f1a7051b6) | Feb 04, 2024 |
| Shuttle       | FH87                        | [781377b2cd](https://linux-hardware.org/?probe=781377b2cd) | Feb 04, 2024 |
| ASUSTek       | P5K                         | [2596e1adb2](https://linux-hardware.org/?probe=2596e1adb2) | Jan 29, 2024 |
| Lenovo        | 3740 NOK                    | [2bfb559750](https://linux-hardware.org/?probe=2bfb559750) | Jan 25, 2024 |
| ASUSTek       | ROG Rampage VI EXTREME E... | [299dd0311b](https://linux-hardware.org/?probe=299dd0311b) | Jan 24, 2024 |
| ASUSTek       | X99-A/USB                   | [c07863641d](https://linux-hardware.org/?probe=c07863641d) | Jan 22, 2024 |
| Gigabyte      | M68MT-S2                    | [ec13e42e3a](https://linux-hardware.org/?probe=ec13e42e3a) | Jan 20, 2024 |
| Gigabyte      | A520M S2H                   | [cf1f6f18f3](https://linux-hardware.org/?probe=cf1f6f18f3) | Jan 17, 2024 |
| ONDA          | H61V Ver:4.01               | [83030b6f99](https://linux-hardware.org/?probe=83030b6f99) | Jan 16, 2024 |
| Dell          | 0K1D6X A00                  | [a47ccd2cfe](https://linux-hardware.org/?probe=a47ccd2cfe) | Jan 11, 2024 |
| Dell          | 0K1D6X A00                  | [5fc28b03c2](https://linux-hardware.org/?probe=5fc28b03c2) | Jan 11, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [92202ac225](https://linux-hardware.org/?probe=92202ac225) | Jan 11, 2024 |
| Gigabyte      | G41M-Combo                  | [e34d332260](https://linux-hardware.org/?probe=e34d332260) | Jan 10, 2024 |
| Intel         | JSL MRD                     | [546cbf14b5](https://linux-hardware.org/?probe=546cbf14b5) | Jan 06, 2024 |
| Lenovo        | MAHOBAY NO DPK              | [9a18a450f2](https://linux-hardware.org/?probe=9a18a450f2) | Jan 04, 2024 |
| Dell          | 0M858N A01                  | [9f73363db2](https://linux-hardware.org/?probe=9f73363db2) | Jan 04, 2024 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | [2b1a79920a](https://linux-hardware.org/?probe=2b1a79920a) | Jan 03, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ab3cc8a89c](https://linux-hardware.org/?probe=ab3cc8a89c) | Dec 23, 2023 |
| Supermicro    | X9DRD-7LN4F                 | [56a303c264](https://linux-hardware.org/?probe=56a303c264) | Dec 20, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [ad8a2053bc](https://linux-hardware.org/?probe=ad8a2053bc) | Dec 17, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [20a11e4c01](https://linux-hardware.org/?probe=20a11e4c01) | Dec 15, 2023 |
| ASUSTek       | P5E WS Pro                  | [9c68d265b1](https://linux-hardware.org/?probe=9c68d265b1) | Dec 12, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [bd9d40cd17](https://linux-hardware.org/?probe=bd9d40cd17) | Dec 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [6aaaa355d3](https://linux-hardware.org/?probe=6aaaa355d3) | Dec 06, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [12c6da7b14](https://linux-hardware.org/?probe=12c6da7b14) | Dec 05, 2023 |
| HP            | 1497                        | [d6ef1fa27d](https://linux-hardware.org/?probe=d6ef1fa27d) | Dec 04, 2023 |
| Huanan        | X99-F8D PLUS V1.3           | [848f3c01c3](https://linux-hardware.org/?probe=848f3c01c3) | Dec 03, 2023 |
| ONDA          | H81M                        | [76c44af7fc](https://linux-hardware.org/?probe=76c44af7fc) | Dec 02, 2023 |
| HP            | 82B4                        | [fae1e016be](https://linux-hardware.org/?probe=fae1e016be) | Dec 02, 2023 |
| Dell          | 0VRWRC A00                  | [55c38cfaa9](https://linux-hardware.org/?probe=55c38cfaa9) | Dec 01, 2023 |
| MSI           | B450 GAMING PLUS            | [8b41445765](https://linux-hardware.org/?probe=8b41445765) | Nov 30, 2023 |
| Dell          | 02YYK5 A01                  | [44dd5b984b](https://linux-hardware.org/?probe=44dd5b984b) | Nov 28, 2023 |
| MSI           | Z97 PC Mate                 | [3bc66597b8](https://linux-hardware.org/?probe=3bc66597b8) | Nov 27, 2023 |
| Biostar       | A78MD                       | [c7e8dd6939](https://linux-hardware.org/?probe=c7e8dd6939) | Nov 27, 2023 |
| HP            | 1825                        | [78c3833b1a](https://linux-hardware.org/?probe=78c3833b1a) | Nov 21, 2023 |
| eMachines     | EL1360G                     | [5b2ab65e0a](https://linux-hardware.org/?probe=5b2ab65e0a) | Nov 20, 2023 |
| Dell          | 0J3C2F A00                  | [28440e547a](https://linux-hardware.org/?probe=28440e547a) | Nov 18, 2023 |
| ONDA          | H61V Ver:4.01               | [9686807789](https://linux-hardware.org/?probe=9686807789) | Nov 18, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [09ef1df759](https://linux-hardware.org/?probe=09ef1df759) | Nov 14, 2023 |
| Gigabyte      | H610M H V2 DDR4             | [bafab6bf21](https://linux-hardware.org/?probe=bafab6bf21) | Nov 10, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [2788382d20](https://linux-hardware.org/?probe=2788382d20) | Nov 10, 2023 |
| Gigabyte      | H67MA-USB3-B3               | [a6a53a60f0](https://linux-hardware.org/?probe=a6a53a60f0) | Nov 10, 2023 |
| Lenovo        | ThinkCentre M58e 7514A2U    | [59554fada7](https://linux-hardware.org/?probe=59554fada7) | Nov 09, 2023 |
| Gigabyte      | H61M-DS2                    | [5a6cfb8bce](https://linux-hardware.org/?probe=5a6cfb8bce) | Nov 07, 2023 |
| HP            | 2AF3                        | [19333e743d](https://linux-hardware.org/?probe=19333e743d) | Nov 07, 2023 |
| HP            | 8594                        | [d51c507511](https://linux-hardware.org/?probe=d51c507511) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [9655bf2db1](https://linux-hardware.org/?probe=9655bf2db1) | Nov 06, 2023 |
| ASRockRack    | EPC602D8A                   | [c1b6c06dc5](https://linux-hardware.org/?probe=c1b6c06dc5) | Nov 05, 2023 |
| MSI           | A68HM-E33 V2                | [f029848e7d](https://linux-hardware.org/?probe=f029848e7d) | Nov 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [baf30122ca](https://linux-hardware.org/?probe=baf30122ca) | Nov 03, 2023 |
| ASUSTek       | PRIME X299-A                | [387194bdf6](https://linux-hardware.org/?probe=387194bdf6) | Nov 03, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | [328a40f6fe](https://linux-hardware.org/?probe=328a40f6fe) | Nov 03, 2023 |
| HP            | 0AECh D                     | [2ddad2bbf2](https://linux-hardware.org/?probe=2ddad2bbf2) | Nov 03, 2023 |
| Dell          | 0X8DXD A00                  | [e972336105](https://linux-hardware.org/?probe=e972336105) | Nov 03, 2023 |
| ASRock        | Z790 Taichi                 | [01ba7dff2f](https://linux-hardware.org/?probe=01ba7dff2f) | Oct 31, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f1d5844389](https://linux-hardware.org/?probe=f1d5844389) | Oct 31, 2023 |
| Unknown       | Unknown                     | [4aa5e757eb](https://linux-hardware.org/?probe=4aa5e757eb) | Oct 31, 2023 |
| ASRock        | Z370 Pro4                   | [55f20f6750](https://linux-hardware.org/?probe=55f20f6750) | Oct 31, 2023 |
| ASRock        | Z170 Extreme4               | [90fc87e07a](https://linux-hardware.org/?probe=90fc87e07a) | Oct 31, 2023 |
| ASRock        | Z170 Extreme4               | [5d99367248](https://linux-hardware.org/?probe=5d99367248) | Oct 31, 2023 |
| ASRock        | FM2A88X+ Killer             | [2310075f2d](https://linux-hardware.org/?probe=2310075f2d) | Oct 30, 2023 |
| Intel         | H61                         | [0f282da58e](https://linux-hardware.org/?probe=0f282da58e) | Oct 30, 2023 |
| Dell          | 02YYK5 A00                  | [bda6b9ff10](https://linux-hardware.org/?probe=bda6b9ff10) | Oct 29, 2023 |
| Gigabyte      | X58A-UD3R                   | [7c4b363241](https://linux-hardware.org/?probe=7c4b363241) | Oct 28, 2023 |
| ASRock        | Z790 PG SONIC               | [3d8af896cc](https://linux-hardware.org/?probe=3d8af896cc) | Oct 27, 2023 |
| Intel         | DB85FL AAG89861-201         | [44b772393d](https://linux-hardware.org/?probe=44b772393d) | Oct 27, 2023 |
| GEEKOM        | A5                          | [2a6fe744c1](https://linux-hardware.org/?probe=2a6fe744c1) | Oct 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [fc849b0e23](https://linux-hardware.org/?probe=fc849b0e23) | Oct 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [3a0c166a2f](https://linux-hardware.org/?probe=3a0c166a2f) | Oct 25, 2023 |
| Dell          | 0D24M8 A01                  | [74e623d263](https://linux-hardware.org/?probe=74e623d263) | Oct 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [e622e81e16](https://linux-hardware.org/?probe=e622e81e16) | Oct 24, 2023 |
| ASUSTek       | Crosshair IV Formula        | [9664d44f1e](https://linux-hardware.org/?probe=9664d44f1e) | Oct 24, 2023 |
| HP            | 339A                        | [2e0eb78de2](https://linux-hardware.org/?probe=2e0eb78de2) | Oct 24, 2023 |
| Dell          | 0VD5HY A07                  | [5e68194dd0](https://linux-hardware.org/?probe=5e68194dd0) | Oct 23, 2023 |
| HP            | 18E7                        | [eec2c6a2fd](https://linux-hardware.org/?probe=eec2c6a2fd) | Oct 23, 2023 |
| MSI           | X58 Pro SLI                 | [e127c69a3f](https://linux-hardware.org/?probe=e127c69a3f) | Oct 23, 2023 |
| Shenzhen M... | F6BFC                       | [04dd8d9baf](https://linux-hardware.org/?probe=04dd8d9baf) | Oct 23, 2023 |
| HP            | 18E7                        | [18f7dbf492](https://linux-hardware.org/?probe=18f7dbf492) | Oct 22, 2023 |
| Gigabyte      | B85M-D2V                    | [f7b3792e3e](https://linux-hardware.org/?probe=f7b3792e3e) | Oct 21, 2023 |
| ASRock        | B450 Steel Legend           | [d3036ca319](https://linux-hardware.org/?probe=d3036ca319) | Oct 20, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ed9af05f78](https://linux-hardware.org/?probe=ed9af05f78) | Oct 20, 2023 |
| ASUSTek       | Z170-P                      | [4f6fad364d](https://linux-hardware.org/?probe=4f6fad364d) | Oct 20, 2023 |
| Dell          | 0J3C2F A00                  | [eb391611f3](https://linux-hardware.org/?probe=eb391611f3) | Oct 19, 2023 |
| ASRock        | Z370 Taichi                 | [ca57155c40](https://linux-hardware.org/?probe=ca57155c40) | Oct 19, 2023 |
| Dell          | 0J3C2F A00                  | [df408e2203](https://linux-hardware.org/?probe=df408e2203) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b28a7b8c25](https://linux-hardware.org/?probe=b28a7b8c25) | Oct 17, 2023 |
| Foxconn       | 2ADA                        | [da4ea80916](https://linux-hardware.org/?probe=da4ea80916) | Oct 17, 2023 |
| Gigabyte      | H110M-D2P-WG-CF             | [113b3d362d](https://linux-hardware.org/?probe=113b3d362d) | Oct 17, 2023 |
| ASUSTek       | Maximus IX HERO             | [58e17c747d](https://linux-hardware.org/?probe=58e17c747d) | Oct 17, 2023 |
| ASRock        | FM2A68M-HD+                 | [3597183b2f](https://linux-hardware.org/?probe=3597183b2f) | Oct 17, 2023 |
| ASUSTek       | Maximus IX HERO             | [fcd9389f36](https://linux-hardware.org/?probe=fcd9389f36) | Oct 17, 2023 |
| Intel         | DH77KC AAG39641-401         | [abfbdc1640](https://linux-hardware.org/?probe=abfbdc1640) | Oct 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [52a3f75a39](https://linux-hardware.org/?probe=52a3f75a39) | Oct 16, 2023 |
| ASUSTek       | PRIME H510M-A               | [8f5d44a983](https://linux-hardware.org/?probe=8f5d44a983) | Oct 16, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [3a8e72ab3b](https://linux-hardware.org/?probe=3a8e72ab3b) | Oct 15, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | [1f718e54bf](https://linux-hardware.org/?probe=1f718e54bf) | Oct 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [70c2a81f9f](https://linux-hardware.org/?probe=70c2a81f9f) | Oct 14, 2023 |
| ASRock        | X399 Taichi                 | [10b572c94a](https://linux-hardware.org/?probe=10b572c94a) | Oct 14, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [1d1e26c1fe](https://linux-hardware.org/?probe=1d1e26c1fe) | Oct 14, 2023 |
| Dell          | 0K3CM7 A00                  | [35d569ea79](https://linux-hardware.org/?probe=35d569ea79) | Oct 14, 2023 |
| Dell          | 042P49 A02                  | [dd056a62d3](https://linux-hardware.org/?probe=dd056a62d3) | Oct 14, 2023 |
| ASUSTek       | P9X79 PRO                   | [d9361064fd](https://linux-hardware.org/?probe=d9361064fd) | Oct 13, 2023 |
| ASRockRack    | EPC602D8A                   | [a47c7098c0](https://linux-hardware.org/?probe=a47c7098c0) | Oct 13, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [2869814e7d](https://linux-hardware.org/?probe=2869814e7d) | Oct 12, 2023 |
| HP            | 2B5E                        | [9dff375d05](https://linux-hardware.org/?probe=9dff375d05) | Oct 12, 2023 |
| Gigabyte      | A320M-H-CF                  | [a549a213f1](https://linux-hardware.org/?probe=a549a213f1) | Oct 12, 2023 |
| HP            | 805D                        | [8fb0d8213e](https://linux-hardware.org/?probe=8fb0d8213e) | Oct 12, 2023 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [9ca6bc0b08](https://linux-hardware.org/?probe=9ca6bc0b08) | Oct 11, 2023 |
| ASUSTek       | H61M-K                      | [77ff5b185a](https://linux-hardware.org/?probe=77ff5b185a) | Oct 11, 2023 |
| Lenovo        | MAHOBAY NOK                 | [83ed978b53](https://linux-hardware.org/?probe=83ed978b53) | Oct 11, 2023 |
| HP            | 18E7                        | [fd71ca186e](https://linux-hardware.org/?probe=fd71ca186e) | Oct 11, 2023 |
| Dell          | 0XJ8C4 A00                  | [c95c8a8a2e](https://linux-hardware.org/?probe=c95c8a8a2e) | Oct 11, 2023 |
| Intel         | H61 V1.5                    | [ed796dbba7](https://linux-hardware.org/?probe=ed796dbba7) | Oct 11, 2023 |
| Quanta        | 2ABB 101                    | [1ae3a7098e](https://linux-hardware.org/?probe=1ae3a7098e) | Oct 11, 2023 |
| Gigabyte      | H81M-S                      | [9799f9f959](https://linux-hardware.org/?probe=9799f9f959) | Oct 10, 2023 |
| MSI           | MS-7125                     | [2e6837be6d](https://linux-hardware.org/?probe=2e6837be6d) | Oct 10, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9e03b4745f](https://linux-hardware.org/?probe=9e03b4745f) | Oct 10, 2023 |
| MSI           | MS-7380                     | [b2c3a106ca](https://linux-hardware.org/?probe=b2c3a106ca) | Oct 10, 2023 |
| ASUSTek       | PRIME B365M-K               | [e5e897e96a](https://linux-hardware.org/?probe=e5e897e96a) | Oct 09, 2023 |
| ASUSTek       | H81M-A                      | [38a83d68e5](https://linux-hardware.org/?probe=38a83d68e5) | Oct 09, 2023 |
| ASUSTek       | H81M-A                      | [fd663ca7fa](https://linux-hardware.org/?probe=fd663ca7fa) | Oct 09, 2023 |
| HP            | 845A                        | [b3bd3f3036](https://linux-hardware.org/?probe=b3bd3f3036) | Oct 09, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | [d8cf994cfe](https://linux-hardware.org/?probe=d8cf994cfe) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [a07ec0ee55](https://linux-hardware.org/?probe=a07ec0ee55) | Oct 08, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [687287904f](https://linux-hardware.org/?probe=687287904f) | Oct 08, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | [8ea6db3dbb](https://linux-hardware.org/?probe=8ea6db3dbb) | Oct 08, 2023 |
| GIADA         | Braswell JHS60S             | [ed113a0bc0](https://linux-hardware.org/?probe=ed113a0bc0) | Oct 08, 2023 |
| Dell          | 042P49 A02                  | [5e51e3dabc](https://linux-hardware.org/?probe=5e51e3dabc) | Oct 08, 2023 |
| Unknown       | Phitronics G31VS-M          | [7b7ac9e326](https://linux-hardware.org/?probe=7b7ac9e326) | Oct 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [5324f47bcf](https://linux-hardware.org/?probe=5324f47bcf) | Oct 07, 2023 |
| Dell          | 0X9M3X A01                  | [59c96d1008](https://linux-hardware.org/?probe=59c96d1008) | Oct 07, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [00fa623097](https://linux-hardware.org/?probe=00fa623097) | Oct 07, 2023 |
| HP            | 18E7                        | [4d548e9668](https://linux-hardware.org/?probe=4d548e9668) | Oct 06, 2023 |
| MSI           | X570-A PRO                  | [fbd07d95c2](https://linux-hardware.org/?probe=fbd07d95c2) | Oct 06, 2023 |
| ASUSTek       | Z170-P                      | [634ca46a18](https://linux-hardware.org/?probe=634ca46a18) | Oct 06, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [6a56e8a819](https://linux-hardware.org/?probe=6a56e8a819) | Oct 05, 2023 |
| Pegatron      | H81-M1                      | [a2af980b4f](https://linux-hardware.org/?probe=a2af980b4f) | Oct 04, 2023 |
| Dell          | 0GXM1W A00                  | [529f4a7005](https://linux-hardware.org/?probe=529f4a7005) | Oct 04, 2023 |
| Intel         | X79M-S                      | [a62dc4f931](https://linux-hardware.org/?probe=a62dc4f931) | Oct 04, 2023 |
| SHANGZHAOY... | H97M-PRO V1.0               | [0056cb50c2](https://linux-hardware.org/?probe=0056cb50c2) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [e590e7eb2c](https://linux-hardware.org/?probe=e590e7eb2c) | Oct 04, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [f93ae6a15c](https://linux-hardware.org/?probe=f93ae6a15c) | Oct 03, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [30ff6af03d](https://linux-hardware.org/?probe=30ff6af03d) | Oct 03, 2023 |
| Unknown       | Phitronics G31VS-M          | [a30a4e0d2e](https://linux-hardware.org/?probe=a30a4e0d2e) | Oct 03, 2023 |
| ASUSTek       | Pro Q670M-C                 | [8bbc915322](https://linux-hardware.org/?probe=8bbc915322) | Oct 03, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | [d7108a55e5](https://linux-hardware.org/?probe=d7108a55e5) | Oct 02, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [06f658c722](https://linux-hardware.org/?probe=06f658c722) | Oct 02, 2023 |
| Dell          | 084J0R A00                  | [93abdf2d50](https://linux-hardware.org/?probe=93abdf2d50) | Oct 02, 2023 |
| Intel         | DP45SG AAE27733-404         | [2b0868267b](https://linux-hardware.org/?probe=2b0868267b) | Oct 02, 2023 |
| Intel         | DP45SG AAE27733-404         | [d8e6101d6d](https://linux-hardware.org/?probe=d8e6101d6d) | Oct 02, 2023 |
| Foxconn       | 2ADA                        | [be587ff5b8](https://linux-hardware.org/?probe=be587ff5b8) | Oct 02, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [0236b6af15](https://linux-hardware.org/?probe=0236b6af15) | Oct 01, 2023 |
| NZXT          | N7 B550                     | [53a99b69e6](https://linux-hardware.org/?probe=53a99b69e6) | Sep 30, 2023 |
| Foxconn       | 2ADA                        | [da117a4e6a](https://linux-hardware.org/?probe=da117a4e6a) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [0b4432877e](https://linux-hardware.org/?probe=0b4432877e) | Sep 30, 2023 |
| ASUSTek       | CG8480                      | [dc174e8f73](https://linux-hardware.org/?probe=dc174e8f73) | Sep 30, 2023 |
| Lenovo        | ThinkCentre M58e 7514A2U    | [68f162bf42](https://linux-hardware.org/?probe=68f162bf42) | Sep 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [770e7037d3](https://linux-hardware.org/?probe=770e7037d3) | Sep 30, 2023 |
| Apple         | Mac-F221BEC8                | [7b4a0099a9](https://linux-hardware.org/?probe=7b4a0099a9) | Sep 29, 2023 |
| GEEKOM        | Mini IT 8                   | [fc5d6092da](https://linux-hardware.org/?probe=fc5d6092da) | Sep 29, 2023 |
| ASUSTek       | H81M-K                      | [16dabb2f6e](https://linux-hardware.org/?probe=16dabb2f6e) | Sep 29, 2023 |
| Foxconn       | 2ADA                        | [0c29af254c](https://linux-hardware.org/?probe=0c29af254c) | Sep 29, 2023 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | [26580dc672](https://linux-hardware.org/?probe=26580dc672) | Sep 29, 2023 |
| MSI           | A520M-A PRO                 | [27d7959e57](https://linux-hardware.org/?probe=27d7959e57) | Sep 28, 2023 |
| ASRock        | Z370 Pro4                   | [a70543ae67](https://linux-hardware.org/?probe=a70543ae67) | Sep 28, 2023 |
| HP            | 8594                        | [374067df48](https://linux-hardware.org/?probe=374067df48) | Sep 27, 2023 |
| MSI           | Z77A-S01                    | [277586f152](https://linux-hardware.org/?probe=277586f152) | Sep 27, 2023 |
| Intel         | X79F1 V2.0                  | [919b208284](https://linux-hardware.org/?probe=919b208284) | Sep 27, 2023 |
| MSI           | B550-A PRO                  | [c60600b4f0](https://linux-hardware.org/?probe=c60600b4f0) | Sep 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | [812b06784e](https://linux-hardware.org/?probe=812b06784e) | Sep 27, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [fc79d63b87](https://linux-hardware.org/?probe=fc79d63b87) | Sep 26, 2023 |
| ASUSTek       | M51AC                       | [b4bd7fad24](https://linux-hardware.org/?probe=b4bd7fad24) | Sep 25, 2023 |
| HP            | 3047h                       | [03fd91188a](https://linux-hardware.org/?probe=03fd91188a) | Sep 24, 2023 |
| ASUSTek       | B85M-E                      | [25c109d366](https://linux-hardware.org/?probe=25c109d366) | Sep 24, 2023 |
| Dell          | 0T10XW A02                  | [5df1a942d9](https://linux-hardware.org/?probe=5df1a942d9) | Sep 24, 2023 |
| Foxconn       | 2ADA                        | [8a1af94640](https://linux-hardware.org/?probe=8a1af94640) | Sep 24, 2023 |
| MSI           | B450M MORTAR MAX            | [da277c4d5a](https://linux-hardware.org/?probe=da277c4d5a) | Sep 23, 2023 |
| Gigabyte      | X570 AORUS PRO              | [45c1c156af](https://linux-hardware.org/?probe=45c1c156af) | Sep 23, 2023 |
| Pegatron      | 2AB6                        | [9b814d0254](https://linux-hardware.org/?probe=9b814d0254) | Sep 23, 2023 |
| MACHINIST     | E5-D8-MAX V1.0              | [41ac03cc3a](https://linux-hardware.org/?probe=41ac03cc3a) | Sep 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | [898219c64a](https://linux-hardware.org/?probe=898219c64a) | Sep 23, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [2a0c1d15f9](https://linux-hardware.org/?probe=2a0c1d15f9) | Sep 23, 2023 |
| ASUSTek       | F1A75-V PRO                 | [ce054bb837](https://linux-hardware.org/?probe=ce054bb837) | Sep 22, 2023 |
| Dell          | 02YYK5 A01                  | [a204305d1e](https://linux-hardware.org/?probe=a204305d1e) | Sep 22, 2023 |
| AZW           | GTR V21                     | [c3da1f2fd5](https://linux-hardware.org/?probe=c3da1f2fd5) | Sep 22, 2023 |
| Dell          | 02YYK5 A01                  | [d43d654621](https://linux-hardware.org/?probe=d43d654621) | Sep 22, 2023 |
| Gigabyte      | P55-UD4                     | [16f768ab94](https://linux-hardware.org/?probe=16f768ab94) | Sep 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [c933105cd8](https://linux-hardware.org/?probe=c933105cd8) | Sep 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | [f65b051dc9](https://linux-hardware.org/?probe=f65b051dc9) | Sep 20, 2023 |
| Gigabyte      | B365M DS3H                  | [b66d6be0cf](https://linux-hardware.org/?probe=b66d6be0cf) | Sep 19, 2023 |
| Huanan        | X99-F8 V2.0                 | [f832424d90](https://linux-hardware.org/?probe=f832424d90) | Sep 19, 2023 |
| Lenovo        | IdeaCentre K320 10031       | [35cbc95f9e](https://linux-hardware.org/?probe=35cbc95f9e) | Sep 18, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [bb285c7da5](https://linux-hardware.org/?probe=bb285c7da5) | Sep 18, 2023 |
| Lenovo        | IdeaCentre K320 10031       | [bc9d2f6691](https://linux-hardware.org/?probe=bc9d2f6691) | Sep 18, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [c323f31788](https://linux-hardware.org/?probe=c323f31788) | Sep 17, 2023 |
| ASRock        | Z77 Pro4                    | [13f3de6336](https://linux-hardware.org/?probe=13f3de6336) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [88a398f990](https://linux-hardware.org/?probe=88a398f990) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [0c7cb04f38](https://linux-hardware.org/?probe=0c7cb04f38) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [c47a157971](https://linux-hardware.org/?probe=c47a157971) | Sep 16, 2023 |
| ASUSTek       | A88XM-E                     | [2dae5fb442](https://linux-hardware.org/?probe=2dae5fb442) | Sep 16, 2023 |
| ASUSTek       | A88XM-E                     | [a3d82edc9c](https://linux-hardware.org/?probe=a3d82edc9c) | Sep 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [27d7589428](https://linux-hardware.org/?probe=27d7589428) | Sep 15, 2023 |
| Dell          | 0XJ8C4 A00                  | [35d0557ca0](https://linux-hardware.org/?probe=35d0557ca0) | Sep 14, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [14874e9d32](https://linux-hardware.org/?probe=14874e9d32) | Sep 14, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [3c09b49188](https://linux-hardware.org/?probe=3c09b49188) | Sep 14, 2023 |
| Dell          | 0XJ8C4 A00                  | [4f9a4f7031](https://linux-hardware.org/?probe=4f9a4f7031) | Sep 14, 2023 |
| ASRock        | H97 Anniversary             | [37014ea895](https://linux-hardware.org/?probe=37014ea895) | Sep 13, 2023 |
| Intel         | X99H                        | [e38e67a30c](https://linux-hardware.org/?probe=e38e67a30c) | Sep 13, 2023 |
| Biostar       | TB360-BTC Expert            | [4ab8e8a944](https://linux-hardware.org/?probe=4ab8e8a944) | Sep 12, 2023 |
| ASUSTek       | Z170-P                      | [4070a28418](https://linux-hardware.org/?probe=4070a28418) | Sep 11, 2023 |
| ASUSTek       | Z170-P                      | [3abcd33b9c](https://linux-hardware.org/?probe=3abcd33b9c) | Sep 11, 2023 |
| ASRock        | B360M-HDV                   | [d4b0ae4d0c](https://linux-hardware.org/?probe=d4b0ae4d0c) | Sep 11, 2023 |
| Login Info... | LOG-H61H2-M2                | [fa6e51b9bf](https://linux-hardware.org/?probe=fa6e51b9bf) | Sep 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [772c3204b4](https://linux-hardware.org/?probe=772c3204b4) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [0562141e37](https://linux-hardware.org/?probe=0562141e37) | Sep 10, 2023 |
| Dell          | 0HY9JP A00                  | [3b642be7da](https://linux-hardware.org/?probe=3b642be7da) | Sep 10, 2023 |
| MSI           | B350M MORTAR                | [71f9c8579d](https://linux-hardware.org/?probe=71f9c8579d) | Sep 10, 2023 |
| ASRock        | H81 Pro BTC                 | [33891eebf8](https://linux-hardware.org/?probe=33891eebf8) | Sep 10, 2023 |
| ONDA          | H61V Ver:4.01               | [7423e0ce99](https://linux-hardware.org/?probe=7423e0ce99) | Sep 09, 2023 |
| ASRock        | B550M-ITX/ac                | [cdf1a3f17b](https://linux-hardware.org/?probe=cdf1a3f17b) | Sep 09, 2023 |
| Intel         | DN2820FYK H24582-204        | [625b62078a](https://linux-hardware.org/?probe=625b62078a) | Sep 09, 2023 |
| Intel         | DN2820FYK H24582-204        | [440c9854ff](https://linux-hardware.org/?probe=440c9854ff) | Sep 09, 2023 |
| Biostar       | TB360-BTC Expert            | [e392e78b0d](https://linux-hardware.org/?probe=e392e78b0d) | Sep 08, 2023 |
| HP            | 82B4                        | [e702194024](https://linux-hardware.org/?probe=e702194024) | Sep 08, 2023 |
| HP            | 82B4                        | [5c85d3bf3c](https://linux-hardware.org/?probe=5c85d3bf3c) | Sep 08, 2023 |
| Intel         | H61                         | [929cfae9af](https://linux-hardware.org/?probe=929cfae9af) | Sep 08, 2023 |
| ASUSTek       | M51AC                       | [2cd8d3959a](https://linux-hardware.org/?probe=2cd8d3959a) | Sep 07, 2023 |
| Shenzhen M... | AHBAA OEM                   | [d4e6f24af3](https://linux-hardware.org/?probe=d4e6f24af3) | Sep 07, 2023 |
| ASUSTek       | P7H55-M PRO                 | [26a5d8b449](https://linux-hardware.org/?probe=26a5d8b449) | Sep 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d095848fec](https://linux-hardware.org/?probe=d095848fec) | Sep 06, 2023 |
| HP            | 844C                        | [6f4911cda7](https://linux-hardware.org/?probe=6f4911cda7) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | [7bfb24d8e3](https://linux-hardware.org/?probe=7bfb24d8e3) | Sep 06, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [7fa390fcc4](https://linux-hardware.org/?probe=7fa390fcc4) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | [650e71b107](https://linux-hardware.org/?probe=650e71b107) | Sep 05, 2023 |
| ASRock        | FM2A68M-HD+                 | [5971b283b6](https://linux-hardware.org/?probe=5971b283b6) | Sep 05, 2023 |
| ASUSTek       | A88XM-E                     | [464ff29a95](https://linux-hardware.org/?probe=464ff29a95) | Sep 04, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | [06571c70a0](https://linux-hardware.org/?probe=06571c70a0) | Sep 04, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [75c1744e6f](https://linux-hardware.org/?probe=75c1744e6f) | Sep 03, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | [499d13e212](https://linux-hardware.org/?probe=499d13e212) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [93b9808859](https://linux-hardware.org/?probe=93b9808859) | Sep 03, 2023 |
| ASRock        | Z790 PG SONIC               | [72f1cf1ac0](https://linux-hardware.org/?probe=72f1cf1ac0) | Sep 02, 2023 |
| Gigabyte      | GA-970A-D3                  | [193a173166](https://linux-hardware.org/?probe=193a173166) | Sep 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [238b7ca83d](https://linux-hardware.org/?probe=238b7ca83d) | Sep 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [7940f23184](https://linux-hardware.org/?probe=7940f23184) | Sep 01, 2023 |
| ASUSTek       | M2N68-AM SE2                | [78cb25f581](https://linux-hardware.org/?probe=78cb25f581) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [d0a3fefd23](https://linux-hardware.org/?probe=d0a3fefd23) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [710315c4f1](https://linux-hardware.org/?probe=710315c4f1) | Aug 31, 2023 |
| ASUSTek       | PRIME A320M-K               | [8c1eeceddd](https://linux-hardware.org/?probe=8c1eeceddd) | Aug 31, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [d4f09e50b2](https://linux-hardware.org/?probe=d4f09e50b2) | Aug 30, 2023 |
| Fujitsu       | D3061-B1 S26361-D3061-B1    | [5de56db01e](https://linux-hardware.org/?probe=5de56db01e) | Aug 30, 2023 |
| ASUSTek       | M5A78L-M LE                 | [58446213e2](https://linux-hardware.org/?probe=58446213e2) | Aug 30, 2023 |
| Pegatron      | 2AB6                        | [272508eb60](https://linux-hardware.org/?probe=272508eb60) | Aug 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [b70096c6f9](https://linux-hardware.org/?probe=b70096c6f9) | Aug 28, 2023 |
| Dell          | 0D24M8 A00                  | [08229cf960](https://linux-hardware.org/?probe=08229cf960) | Aug 28, 2023 |
| HP            | 843C                        | [6ad21e7d94](https://linux-hardware.org/?probe=6ad21e7d94) | Aug 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [d76b06bfd3](https://linux-hardware.org/?probe=d76b06bfd3) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [f108558763](https://linux-hardware.org/?probe=f108558763) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [7a67556942](https://linux-hardware.org/?probe=7a67556942) | Aug 27, 2023 |
| Gigabyte      | A320M-S2H-CF                | [4ea7c3580b](https://linux-hardware.org/?probe=4ea7c3580b) | Aug 26, 2023 |
| ASUSTek       | Z10PE-D8 WS                 | [206043f3a7](https://linux-hardware.org/?probe=206043f3a7) | Aug 26, 2023 |
| Dell          | 07PR60 A00                  | [6f26d24018](https://linux-hardware.org/?probe=6f26d24018) | Aug 26, 2023 |
| HP            | ProLiant ML10 v2            | [86cb962a7d](https://linux-hardware.org/?probe=86cb962a7d) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [04426b4b83](https://linux-hardware.org/?probe=04426b4b83) | Aug 25, 2023 |
| Dell          | 0T7D40 A00                  | [85e74676ed](https://linux-hardware.org/?probe=85e74676ed) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [9a98c147d4](https://linux-hardware.org/?probe=9a98c147d4) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3723979edb](https://linux-hardware.org/?probe=3723979edb) | Aug 24, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [536f3c29b6](https://linux-hardware.org/?probe=536f3c29b6) | Aug 23, 2023 |
| Biostar       | B450MH                      | [21f8924d2c](https://linux-hardware.org/?probe=21f8924d2c) | Aug 23, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [a7cd220563](https://linux-hardware.org/?probe=a7cd220563) | Aug 21, 2023 |
| ASUSTek       | X99-DELUXE II               | [d59b79adfe](https://linux-hardware.org/?probe=d59b79adfe) | Aug 21, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [bca7b6990c](https://linux-hardware.org/?probe=bca7b6990c) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [b9701cd43c](https://linux-hardware.org/?probe=b9701cd43c) | Aug 20, 2023 |
| ASUSTek       | B85M-E                      | [158cc5fe6f](https://linux-hardware.org/?probe=158cc5fe6f) | Aug 20, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [fee22676ae](https://linux-hardware.org/?probe=fee22676ae) | Aug 20, 2023 |
| ASRock        | Q1900M                      | [1e1e781c93](https://linux-hardware.org/?probe=1e1e781c93) | Aug 19, 2023 |
| Foxconn       | A74MX-S/A74MX-K             | [1cd8a1d54a](https://linux-hardware.org/?probe=1cd8a1d54a) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [b52dbe962f](https://linux-hardware.org/?probe=b52dbe962f) | Aug 19, 2023 |
| ECS           | 7AT-3LB                     | [fe545a2a23](https://linux-hardware.org/?probe=fe545a2a23) | Aug 19, 2023 |
| Acer          | Veriton M2611G v1.0         | [1527c20b46](https://linux-hardware.org/?probe=1527c20b46) | Aug 19, 2023 |
| Intel         | DH67CL AAG10212-205         | [329cfbcae1](https://linux-hardware.org/?probe=329cfbcae1) | Aug 18, 2023 |
| Dell          | 0X8582                      | [c9661782e6](https://linux-hardware.org/?probe=c9661782e6) | Aug 18, 2023 |
| ASUSTek       | PRIME Z270-A                | [c6918bacbd](https://linux-hardware.org/?probe=c6918bacbd) | Aug 18, 2023 |
| Gigabyte      | H81M-D2V                    | [68639ddf06](https://linux-hardware.org/?probe=68639ddf06) | Aug 16, 2023 |
| ASRock        | FM2A68M-DG3+                | [fd5dd48ab1](https://linux-hardware.org/?probe=fd5dd48ab1) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | [bf2f7b52d1](https://linux-hardware.org/?probe=bf2f7b52d1) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | [7b94897e1a](https://linux-hardware.org/?probe=7b94897e1a) | Aug 15, 2023 |
| AK3V          | 1.0                         | [02b6f071a6](https://linux-hardware.org/?probe=02b6f071a6) | Aug 14, 2023 |
| HP            | 21F5 0A                     | [7a8b1ea89a](https://linux-hardware.org/?probe=7a8b1ea89a) | Aug 14, 2023 |
| Gigabyte      | H81M-S2PV                   | [0e51f02009](https://linux-hardware.org/?probe=0e51f02009) | Aug 14, 2023 |
| Lenovo        | ThinkCentre Edge71 1577K... | [8127e491dc](https://linux-hardware.org/?probe=8127e491dc) | Aug 14, 2023 |
| Gigabyte      | G41MT-S2                    | [da23ffa8ca](https://linux-hardware.org/?probe=da23ffa8ca) | Aug 13, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3decac5b92](https://linux-hardware.org/?probe=3decac5b92) | Aug 13, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [74e54546c6](https://linux-hardware.org/?probe=74e54546c6) | Aug 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [396327d1fa](https://linux-hardware.org/?probe=396327d1fa) | Aug 13, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b232e62577](https://linux-hardware.org/?probe=b232e62577) | Aug 13, 2023 |
| Unknown       | Unknown                     | [e52e8ee5df](https://linux-hardware.org/?probe=e52e8ee5df) | Aug 13, 2023 |
| Gigabyte      | H81M-D2V                    | [2996bc5d6c](https://linux-hardware.org/?probe=2996bc5d6c) | Aug 13, 2023 |
| ASUSTek       | M5A78L-M LE                 | [a68db843ea](https://linux-hardware.org/?probe=a68db843ea) | Aug 12, 2023 |
| Intel         | B85 V5.56                   | [7fb2d45505](https://linux-hardware.org/?probe=7fb2d45505) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | [5226916c20](https://linux-hardware.org/?probe=5226916c20) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | [f59a93f116](https://linux-hardware.org/?probe=f59a93f116) | Aug 12, 2023 |
| Dell          | 0HD5W2 A01                  | [be4514c366](https://linux-hardware.org/?probe=be4514c366) | Aug 12, 2023 |
| Intel         | B85 V5.56                   | [f278787ab5](https://linux-hardware.org/?probe=f278787ab5) | Aug 11, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [76078461ae](https://linux-hardware.org/?probe=76078461ae) | Aug 11, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ab2473ff49](https://linux-hardware.org/?probe=ab2473ff49) | Aug 11, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [7f2903e1a4](https://linux-hardware.org/?probe=7f2903e1a4) | Aug 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [44fe085499](https://linux-hardware.org/?probe=44fe085499) | Aug 10, 2023 |
| ASUSTek       | PRIME X570-PRO              | [f7fe8fc7f3](https://linux-hardware.org/?probe=f7fe8fc7f3) | Aug 10, 2023 |
| ASRock        | B450M-HDV R4.0              | [ab3503021a](https://linux-hardware.org/?probe=ab3503021a) | Aug 10, 2023 |
| MSI           | Z590-A PRO                  | [4448c9f2e1](https://linux-hardware.org/?probe=4448c9f2e1) | Aug 09, 2023 |
| MSI           | Z590-A PRO                  | [6e1d11025a](https://linux-hardware.org/?probe=6e1d11025a) | Aug 09, 2023 |
| MSI           | Z97-G45 GAMING              | [65d491c109](https://linux-hardware.org/?probe=65d491c109) | Aug 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | [783906b878](https://linux-hardware.org/?probe=783906b878) | Aug 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [1d8737323b](https://linux-hardware.org/?probe=1d8737323b) | Aug 06, 2023 |
| ASUSTek       | P8H61-M LX3                 | [6875c17337](https://linux-hardware.org/?probe=6875c17337) | Aug 06, 2023 |
| MSI           | 2AE0                        | [9d3b59de32](https://linux-hardware.org/?probe=9d3b59de32) | Aug 06, 2023 |
| MSI           | H81M-P33                    | [ebed30097f](https://linux-hardware.org/?probe=ebed30097f) | Aug 06, 2023 |
| Intel         | B85 V5.56                   | [9c9e999e7f](https://linux-hardware.org/?probe=9c9e999e7f) | Aug 06, 2023 |
| Intel         | B85 V5.56                   | [54f0bde318](https://linux-hardware.org/?probe=54f0bde318) | Aug 06, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [ffa55735b6](https://linux-hardware.org/?probe=ffa55735b6) | Aug 06, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [ac7079fac9](https://linux-hardware.org/?probe=ac7079fac9) | Aug 05, 2023 |
| ASRock        | B450M Pro4                  | [1e157ae535](https://linux-hardware.org/?probe=1e157ae535) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | [5ca4ca286b](https://linux-hardware.org/?probe=5ca4ca286b) | Aug 05, 2023 |
| GMKtec        | NucBox K4                   | [64b27a1390](https://linux-hardware.org/?probe=64b27a1390) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-K II            | [fed2da6500](https://linux-hardware.org/?probe=fed2da6500) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2531b9d0db](https://linux-hardware.org/?probe=2531b9d0db) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [67cea35f6d](https://linux-hardware.org/?probe=67cea35f6d) | Aug 04, 2023 |
| ASUSTek       | M3A78-T                     | [e97447ea9d](https://linux-hardware.org/?probe=e97447ea9d) | Aug 03, 2023 |
| MSI           | Z97 GAMING 3                | [caac03a431](https://linux-hardware.org/?probe=caac03a431) | Aug 03, 2023 |
| MSI           | A320M-A PRO MAX             | [881ac0a0e0](https://linux-hardware.org/?probe=881ac0a0e0) | Aug 02, 2023 |
| MSI           | A320M-A PRO MAX             | [c3beec95b8](https://linux-hardware.org/?probe=c3beec95b8) | Aug 02, 2023 |
| HP            | 8653 A                      | [09f876ab04](https://linux-hardware.org/?probe=09f876ab04) | Aug 02, 2023 |
| ASRock        | B365M-HDV                   | [994853ef26](https://linux-hardware.org/?probe=994853ef26) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [66000207b0](https://linux-hardware.org/?probe=66000207b0) | Aug 01, 2023 |
| Lenovo        | 1066 SDK0T76528 WIN 3556... | [df0702afb0](https://linux-hardware.org/?probe=df0702afb0) | Aug 01, 2023 |
| Lenovo        | 1066 SDK0T76528 WIN 3556... | [0ac623dd70](https://linux-hardware.org/?probe=0ac623dd70) | Aug 01, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [2e4793aa6c](https://linux-hardware.org/?probe=2e4793aa6c) | Aug 01, 2023 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [36c7268653](https://linux-hardware.org/?probe=36c7268653) | Jul 31, 2023 |
| ASRock        | FM2A75 Pro4                 | [831157a9ac](https://linux-hardware.org/?probe=831157a9ac) | Jul 31, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [45405639f5](https://linux-hardware.org/?probe=45405639f5) | Jul 31, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [42a2df4c91](https://linux-hardware.org/?probe=42a2df4c91) | Jul 30, 2023 |
| Gigabyte      | MZAPLBP-00                  | [b70677782d](https://linux-hardware.org/?probe=b70677782d) | Jul 29, 2023 |
| Gigabyte      | MZAPLBP-00                  | [ae8a9f3aaf](https://linux-hardware.org/?probe=ae8a9f3aaf) | Jul 29, 2023 |
| ASUSTek       | H110M-R                     | [471516b82e](https://linux-hardware.org/?probe=471516b82e) | Jul 29, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [f36740f05f](https://linux-hardware.org/?probe=f36740f05f) | Jul 29, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [7b5aebd006](https://linux-hardware.org/?probe=7b5aebd006) | Jul 28, 2023 |
| Gigabyte      | Z490 UD                     | [370243099a](https://linux-hardware.org/?probe=370243099a) | Jul 27, 2023 |
| ASUSTek       | PRIME B450M-K II            | [87bb7b0b79](https://linux-hardware.org/?probe=87bb7b0b79) | Jul 26, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [c7ec8db97e](https://linux-hardware.org/?probe=c7ec8db97e) | Jul 26, 2023 |
| HP            | 3646h                       | [fbc7ac7c08](https://linux-hardware.org/?probe=fbc7ac7c08) | Jul 26, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2fe1d4509a](https://linux-hardware.org/?probe=2fe1d4509a) | Jul 26, 2023 |
| ASRock        | B560M Pro4                  | [d96478ff29](https://linux-hardware.org/?probe=d96478ff29) | Jul 25, 2023 |
| ASUSTek       | PRIME B450M-K II            | [32707549f9](https://linux-hardware.org/?probe=32707549f9) | Jul 25, 2023 |
| Unknown       | 1.2                         | [b18dd168dd](https://linux-hardware.org/?probe=b18dd168dd) | Jul 24, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [ffee60fde7](https://linux-hardware.org/?probe=ffee60fde7) | Jul 24, 2023 |
| Gigabyte      | B450 AORUS M                | [858d935d25](https://linux-hardware.org/?probe=858d935d25) | Jul 24, 2023 |
| Intel         | Unknown                     | [74d458db75](https://linux-hardware.org/?probe=74d458db75) | Jul 23, 2023 |
| ASUSTek       | PRIME X570-P                | [c052f51a67](https://linux-hardware.org/?probe=c052f51a67) | Jul 23, 2023 |
| Intel         | B75                         | [f6b0d91a50](https://linux-hardware.org/?probe=f6b0d91a50) | Jul 23, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3511a9786a](https://linux-hardware.org/?probe=3511a9786a) | Jul 23, 2023 |
| ASUSTek       | CG8480                      | [2b839ca54f](https://linux-hardware.org/?probe=2b839ca54f) | Jul 23, 2023 |
| Dell          | 08NPPY A00                  | [63fb3abc69](https://linux-hardware.org/?probe=63fb3abc69) | Jul 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0e830a2330](https://linux-hardware.org/?probe=0e830a2330) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [719e8b9ad3](https://linux-hardware.org/?probe=719e8b9ad3) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [5e02d0f4e4](https://linux-hardware.org/?probe=5e02d0f4e4) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [a12700ebb8](https://linux-hardware.org/?probe=a12700ebb8) | Jul 22, 2023 |
| Gigabyte      | B450 AORUS M                | [574d6f4393](https://linux-hardware.org/?probe=574d6f4393) | Jul 21, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [e35d64a41b](https://linux-hardware.org/?probe=e35d64a41b) | Jul 21, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [a07f95cdcc](https://linux-hardware.org/?probe=a07f95cdcc) | Jul 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b0efbdb752](https://linux-hardware.org/?probe=b0efbdb752) | Jul 20, 2023 |
| Gigabyte      | A520M DS3H                  | [3bd7501f03](https://linux-hardware.org/?probe=3bd7501f03) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [413194ce8c](https://linux-hardware.org/?probe=413194ce8c) | Jul 20, 2023 |
| Gigabyte      | Z77-DS3H                    | [f99a99e95e](https://linux-hardware.org/?probe=f99a99e95e) | Jul 19, 2023 |
| Unknown       | G41 Series                  | [5890a777c5](https://linux-hardware.org/?probe=5890a777c5) | Jul 19, 2023 |
| Lenovo        | ThinkCentre M58e 7268C5F    | [e62367803c](https://linux-hardware.org/?probe=e62367803c) | Jul 18, 2023 |
| Lenovo        | ThinkCentre M58e 7268C5F    | [41e06d3720](https://linux-hardware.org/?probe=41e06d3720) | Jul 18, 2023 |
| ASRock        | A300M-STX                   | [2fd0158946](https://linux-hardware.org/?probe=2fd0158946) | Jul 17, 2023 |
| Packard Be... | IMEDIA S2885                | [fa20588062](https://linux-hardware.org/?probe=fa20588062) | Jul 17, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60280e0708](https://linux-hardware.org/?probe=60280e0708) | Jul 17, 2023 |
| MSI           | FM2-A85XA-G65               | [8e6741f497](https://linux-hardware.org/?probe=8e6741f497) | Jul 17, 2023 |
| ASRock        | FM2A68M-HD+                 | [5abf5fb1c3](https://linux-hardware.org/?probe=5abf5fb1c3) | Jul 16, 2023 |
| Gigabyte      | H61M-DS2                    | [5b68d7d6e2](https://linux-hardware.org/?probe=5b68d7d6e2) | Jul 16, 2023 |
| Intel         | DH61BF AAG81311-102         | [bc2e347565](https://linux-hardware.org/?probe=bc2e347565) | Jul 16, 2023 |
| Unknown       | EMB-BT1                     | [90dbc847d2](https://linux-hardware.org/?probe=90dbc847d2) | Jul 16, 2023 |
| MSI           | G41M4                       | [b7bda60261](https://linux-hardware.org/?probe=b7bda60261) | Jul 16, 2023 |
| MSI           | G41M4                       | [a3e5e23a49](https://linux-hardware.org/?probe=a3e5e23a49) | Jul 16, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [79af0f54f4](https://linux-hardware.org/?probe=79af0f54f4) | Jul 15, 2023 |
| ASUSTek       | PRIME B650M-A II            | [bf4a6e7eea](https://linux-hardware.org/?probe=bf4a6e7eea) | Jul 15, 2023 |
| Unknown       | Unknown                     | [3820e840f0](https://linux-hardware.org/?probe=3820e840f0) | Jul 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [8df4f1a098](https://linux-hardware.org/?probe=8df4f1a098) | Jul 14, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [eedcf805f7](https://linux-hardware.org/?probe=eedcf805f7) | Jul 14, 2023 |
| MSI           | FM2-A85XA-G65               | [00b4b2f7b0](https://linux-hardware.org/?probe=00b4b2f7b0) | Jul 13, 2023 |
| MSI           | Z87-G43                     | [86d9a28ae8](https://linux-hardware.org/?probe=86d9a28ae8) | Jul 13, 2023 |
| HP            | 83EE                        | [af63e7b8fd](https://linux-hardware.org/?probe=af63e7b8fd) | Jul 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [67ef58f2b3](https://linux-hardware.org/?probe=67ef58f2b3) | Jul 12, 2023 |
| ASRock        | X79 Extreme9                | [bfd488feb9](https://linux-hardware.org/?probe=bfd488feb9) | Jul 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [f4f002c37a](https://linux-hardware.org/?probe=f4f002c37a) | Jul 10, 2023 |
| Gigabyte      | H61M-DS2 DVI                | [44f9b46596](https://linux-hardware.org/?probe=44f9b46596) | Jul 10, 2023 |
| ASRock        | Z77 Extreme3                | [1312271ad3](https://linux-hardware.org/?probe=1312271ad3) | Jul 10, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [fe6456ff43](https://linux-hardware.org/?probe=fe6456ff43) | Jul 09, 2023 |
| Gigabyte      | MZAPLBP-00                  | [8f57c74864](https://linux-hardware.org/?probe=8f57c74864) | Jul 09, 2023 |
| Dell          | 0GXM1W A00                  | [b320d70c27](https://linux-hardware.org/?probe=b320d70c27) | Jul 09, 2023 |
| ASUSTek       | BM2AD_D510MT_D310MT         | [d7f7dc2ef3](https://linux-hardware.org/?probe=d7f7dc2ef3) | Jul 08, 2023 |
| Lenovo        | IdeaCentre K330A            | [8d98ff8f86](https://linux-hardware.org/?probe=8d98ff8f86) | Jul 08, 2023 |
| Dell          | 0GXM1W A00                  | [91cab30323](https://linux-hardware.org/?probe=91cab30323) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | [89a1894d2a](https://linux-hardware.org/?probe=89a1894d2a) | Jul 08, 2023 |
| MSI           | Z97S SLI Krait Edition      | [c353b62b15](https://linux-hardware.org/?probe=c353b62b15) | Jul 07, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7e3f6aabfb](https://linux-hardware.org/?probe=7e3f6aabfb) | Jul 06, 2023 |
| Apple         | Mac-F221BEC8                | [5e66adbc36](https://linux-hardware.org/?probe=5e66adbc36) | Jul 06, 2023 |
| MSI           | H110 PC MATE                | [cc74c165b7](https://linux-hardware.org/?probe=cc74c165b7) | Jul 06, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [56c3cb8200](https://linux-hardware.org/?probe=56c3cb8200) | Jul 06, 2023 |
| MSI           | 760GM-E51                   | [757eefb29d](https://linux-hardware.org/?probe=757eefb29d) | Jul 05, 2023 |
| MSI           | PRO X670-P WIFI             | [12e2330b5a](https://linux-hardware.org/?probe=12e2330b5a) | Jul 05, 2023 |
| ASRock        | A320M-HDV R3.0              | [df1fff149d](https://linux-hardware.org/?probe=df1fff149d) | Jul 04, 2023 |
| ASUSTek       | PRIME A520M-K               | [9b1631574e](https://linux-hardware.org/?probe=9b1631574e) | Jul 03, 2023 |
| ASUSTek       | PRIME X570-P                | [0302d7f3a8](https://linux-hardware.org/?probe=0302d7f3a8) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d17e5d7807](https://linux-hardware.org/?probe=d17e5d7807) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [29897719d5](https://linux-hardware.org/?probe=29897719d5) | Jul 03, 2023 |
| ASRock        | P67 Performance             | [5abbfdce39](https://linux-hardware.org/?probe=5abbfdce39) | Jul 02, 2023 |
| Gigabyte      | B150M-DS3H-CF               | [1a3056376b](https://linux-hardware.org/?probe=1a3056376b) | Jul 02, 2023 |
| Gigabyte      | B150M-DS3H-CF               | [648742f6d3](https://linux-hardware.org/?probe=648742f6d3) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | [40ab1ca8ab](https://linux-hardware.org/?probe=40ab1ca8ab) | Jul 02, 2023 |
| Intel         | H55                         | [446ffab057](https://linux-hardware.org/?probe=446ffab057) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | [5c7d4754d6](https://linux-hardware.org/?probe=5c7d4754d6) | Jul 02, 2023 |
| Biostar       | A10N-8800E                  | [261bb38239](https://linux-hardware.org/?probe=261bb38239) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [669754af36](https://linux-hardware.org/?probe=669754af36) | Jul 02, 2023 |
| Dell          | 05XGC8 A00                  | [83da477284](https://linux-hardware.org/?probe=83da477284) | Jul 02, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [e0e64ac6a1](https://linux-hardware.org/?probe=e0e64ac6a1) | Jul 01, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [fa055ceb7c](https://linux-hardware.org/?probe=fa055ceb7c) | Jun 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [d42cdc8551](https://linux-hardware.org/?probe=d42cdc8551) | Jun 30, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [ffcfef2edb](https://linux-hardware.org/?probe=ffcfef2edb) | Jun 30, 2023 |
| Lenovo        | 0B98401 WIN                 | [35871c9acc](https://linux-hardware.org/?probe=35871c9acc) | Jun 30, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [42624c8bb1](https://linux-hardware.org/?probe=42624c8bb1) | Jun 29, 2023 |
| Acer          | Aspire XC-840               | [76c750aae4](https://linux-hardware.org/?probe=76c750aae4) | Jun 29, 2023 |
| ASUSTek       | PRIME Z590-P                | [6147d58cdf](https://linux-hardware.org/?probe=6147d58cdf) | Jun 29, 2023 |
| ASUSTek       | H170-PRO                    | [506c909e37](https://linux-hardware.org/?probe=506c909e37) | Jun 28, 2023 |
| ASUSTek       | P8Z77-V                     | [177c923e5a](https://linux-hardware.org/?probe=177c923e5a) | Jun 27, 2023 |
| ASRock        | A320M-DVS R4.0              | [742d015edb](https://linux-hardware.org/?probe=742d015edb) | Jun 26, 2023 |
| ASRock        | A320M-DVS R4.0              | [6c659f8e1f](https://linux-hardware.org/?probe=6c659f8e1f) | Jun 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [544c014552](https://linux-hardware.org/?probe=544c014552) | Jun 26, 2023 |
| Gigabyte      | 970A-DS3P                   | [77e0f0541a](https://linux-hardware.org/?probe=77e0f0541a) | Jun 26, 2023 |
| Dell          | 0KJCC5 A00                  | [3ec1b71f5c](https://linux-hardware.org/?probe=3ec1b71f5c) | Jun 25, 2023 |
| Intel         | H61                         | [8af1bf1ada](https://linux-hardware.org/?probe=8af1bf1ada) | Jun 25, 2023 |
| ASUSTek       | PRIME A320M-K               | [3505659de8](https://linux-hardware.org/?probe=3505659de8) | Jun 25, 2023 |
| Dell          | 07N90W A01                  | [67a12e071e](https://linux-hardware.org/?probe=67a12e071e) | Jun 25, 2023 |
| ASRock        | X570 Extreme4               | [0ab63facb3](https://linux-hardware.org/?probe=0ab63facb3) | Jun 25, 2023 |
| HP            | 805D                        | [d55246de23](https://linux-hardware.org/?probe=d55246de23) | Jun 24, 2023 |
| Gigabyte      | A520M S2H                   | [cc2b3ff1ad](https://linux-hardware.org/?probe=cc2b3ff1ad) | Jun 24, 2023 |
| Gigabyte      | H61M-DS2                    | [1a8f2401f1](https://linux-hardware.org/?probe=1a8f2401f1) | Jun 24, 2023 |
| System76      | Desktop leox5               | [210eb3f1e8](https://linux-hardware.org/?probe=210eb3f1e8) | Jun 24, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [45575cf0cc](https://linux-hardware.org/?probe=45575cf0cc) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e3d196b0b5](https://linux-hardware.org/?probe=e3d196b0b5) | Jun 24, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [77d2d05995](https://linux-hardware.org/?probe=77d2d05995) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e5b4e8d2d4](https://linux-hardware.org/?probe=e5b4e8d2d4) | Jun 24, 2023 |
| MSI           | H270-A PRO                  | [169bbe5f04](https://linux-hardware.org/?probe=169bbe5f04) | Jun 23, 2023 |
| Gigabyte      | H61M-DS2                    | [a9079161b0](https://linux-hardware.org/?probe=a9079161b0) | Jun 23, 2023 |
| ASUSTek       | P8P67 PRO                   | [7b33fc2cb8](https://linux-hardware.org/?probe=7b33fc2cb8) | Jun 23, 2023 |
| MSI           | 760GM -E51                  | [3f0c7f7d21](https://linux-hardware.org/?probe=3f0c7f7d21) | Jun 22, 2023 |
| ASUSTek       | PRIME Z790M-PLUS            | [ea7090722f](https://linux-hardware.org/?probe=ea7090722f) | Jun 22, 2023 |
| Gigabyte      | H77-D3H                     | [67f3cd78e2](https://linux-hardware.org/?probe=67f3cd78e2) | Jun 22, 2023 |
| Dell          | 0YXG0N A00                  | [546af4a5d6](https://linux-hardware.org/?probe=546af4a5d6) | Jun 22, 2023 |
| HP            | 339A                        | [420903b9cc](https://linux-hardware.org/?probe=420903b9cc) | Jun 21, 2023 |
| Shenzhen M... | F7BFC                       | [6840ce5f21](https://linux-hardware.org/?probe=6840ce5f21) | Jun 20, 2023 |
| Apple         | Mac-F221BEC8                | [05b8720dce](https://linux-hardware.org/?probe=05b8720dce) | Jun 19, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [c867520de1](https://linux-hardware.org/?probe=c867520de1) | Jun 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [bc9f4e0f09](https://linux-hardware.org/?probe=bc9f4e0f09) | Jun 18, 2023 |
| HP            | 84FD                        | [968b4e287f](https://linux-hardware.org/?probe=968b4e287f) | Jun 17, 2023 |
| HP            | 84FD                        | [1711c65b62](https://linux-hardware.org/?probe=1711c65b62) | Jun 17, 2023 |
| Dell          | 0P301D A00                  | [91bec0952f](https://linux-hardware.org/?probe=91bec0952f) | Jun 17, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [2734ce8c5d](https://linux-hardware.org/?probe=2734ce8c5d) | Jun 16, 2023 |
| HP            | 1496                        | [ccc9943e2d](https://linux-hardware.org/?probe=ccc9943e2d) | Jun 16, 2023 |
| Unknown       | G41 Series                  | [07122155fa](https://linux-hardware.org/?probe=07122155fa) | Jun 15, 2023 |
| ASUSTek       | Rev                         | [6c5d91db68](https://linux-hardware.org/?probe=6c5d91db68) | Jun 15, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [7df89b77f2](https://linux-hardware.org/?probe=7df89b77f2) | Jun 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [dcfab5627c](https://linux-hardware.org/?probe=dcfab5627c) | Jun 14, 2023 |
| Unknown       | G41T-M7                     | [18a63d3a27](https://linux-hardware.org/?probe=18a63d3a27) | Jun 14, 2023 |
| Gigabyte      | Z77X-UD3H                   | [5cbee4094a](https://linux-hardware.org/?probe=5cbee4094a) | Jun 14, 2023 |
| ASUSTek       | M5A97 PRO                   | [a5cbd2e848](https://linux-hardware.org/?probe=a5cbd2e848) | Jun 14, 2023 |
| ASRock        | Z77 Extreme3                | [143672bf6c](https://linux-hardware.org/?probe=143672bf6c) | Jun 14, 2023 |
| Medion        | Z370H4-EM                   | [e2df546273](https://linux-hardware.org/?probe=e2df546273) | Jun 13, 2023 |
| Medion        | Z370H4-EM                   | [bcfcd0b59d](https://linux-hardware.org/?probe=bcfcd0b59d) | Jun 13, 2023 |
| ASRock        | A520M-HVS                   | [0834ca7236](https://linux-hardware.org/?probe=0834ca7236) | Jun 13, 2023 |
| Gigabyte      | G41M-Combo                  | [a22e7ac3ea](https://linux-hardware.org/?probe=a22e7ac3ea) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M58 7360PL9     | [da837e8612](https://linux-hardware.org/?probe=da837e8612) | Jun 13, 2023 |
| ASRock        | Z77 Extreme3                | [0579a4f6f3](https://linux-hardware.org/?probe=0579a4f6f3) | Jun 13, 2023 |
| MSI           | B250M MORTAR ARCTIC         | [5e0e6586b7](https://linux-hardware.org/?probe=5e0e6586b7) | Jun 11, 2023 |
| Entroware     | Poseidon                    | [506bfb1a08](https://linux-hardware.org/?probe=506bfb1a08) | Jun 11, 2023 |
| Intel         | DP45SG AAE27733-404         | [7abba8629e](https://linux-hardware.org/?probe=7abba8629e) | Jun 10, 2023 |
| Intel         | DP45SG AAE27733-404         | [afaced265f](https://linux-hardware.org/?probe=afaced265f) | Jun 10, 2023 |
| HP            | 81B4                        | [2d7748536f](https://linux-hardware.org/?probe=2d7748536f) | Jun 10, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [63c110632a](https://linux-hardware.org/?probe=63c110632a) | Jun 10, 2023 |
| HP            | 0B4Ch D                     | [672a491915](https://linux-hardware.org/?probe=672a491915) | Jun 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | [4f69ba649a](https://linux-hardware.org/?probe=4f69ba649a) | Jun 09, 2023 |
| ASRock        | X670E Pro RS                | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| AZW           | Green G4 10                 | [326b499893](https://linux-hardware.org/?probe=326b499893) | Jun 08, 2023 |
| BESSTAR Te... | UM700                       | [92645b42ac](https://linux-hardware.org/?probe=92645b42ac) | Jun 08, 2023 |
| Dell          | 0HN7XN A01                  | [c44abee9e7](https://linux-hardware.org/?probe=c44abee9e7) | Jun 08, 2023 |
| ASUSTek       | WS Z390 PRO                 | [7346eaf346](https://linux-hardware.org/?probe=7346eaf346) | Jun 07, 2023 |
| MSI           | A88XM-E35                   | [efe1285363](https://linux-hardware.org/?probe=efe1285363) | Jun 07, 2023 |
| ASUSTek       | B85M-E                      | [9ea0a82205](https://linux-hardware.org/?probe=9ea0a82205) | Jun 07, 2023 |
| Dell          | 0R6PCT A01                  | [e1623fbc8e](https://linux-hardware.org/?probe=e1623fbc8e) | Jun 07, 2023 |
| Dell          | 0RY007                      | [49c7cbbfde](https://linux-hardware.org/?probe=49c7cbbfde) | Jun 06, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [fe852e8a1d](https://linux-hardware.org/?probe=fe852e8a1d) | Jun 06, 2023 |
| Pegatron      | H81-M1                      | [2641e6773e](https://linux-hardware.org/?probe=2641e6773e) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | [1c99e1316c](https://linux-hardware.org/?probe=1c99e1316c) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | [60fb09bf5e](https://linux-hardware.org/?probe=60fb09bf5e) | Jun 05, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [32da3735d9](https://linux-hardware.org/?probe=32da3735d9) | Jun 05, 2023 |
| ASUSTek       | Z170-K                      | [a2c31cdc69](https://linux-hardware.org/?probe=a2c31cdc69) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-V                | [d0fd3fd90a](https://linux-hardware.org/?probe=d0fd3fd90a) | Jun 04, 2023 |
| ASUSTek       | PRIME Z590-V                | [bc93ac1588](https://linux-hardware.org/?probe=bc93ac1588) | Jun 04, 2023 |
| ASRock        | A320M-HDV R4.0              | [f472cba5a6](https://linux-hardware.org/?probe=f472cba5a6) | Jun 04, 2023 |
| ASUSTek       | H170-PRO                    | [b9fd75507c](https://linux-hardware.org/?probe=b9fd75507c) | Jun 04, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [82542c4daa](https://linux-hardware.org/?probe=82542c4daa) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [0c8afa948b](https://linux-hardware.org/?probe=0c8afa948b) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK               | [aaed1b39af](https://linux-hardware.org/?probe=aaed1b39af) | Jun 03, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [8b790b76a6](https://linux-hardware.org/?probe=8b790b76a6) | Jun 03, 2023 |
| Intel         | X99 V102                    | [ed5a67e8a5](https://linux-hardware.org/?probe=ed5a67e8a5) | Jun 03, 2023 |
| MSI           | H97M-G43                    | [6bd1b61977](https://linux-hardware.org/?probe=6bd1b61977) | Jun 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [8d783c6b00](https://linux-hardware.org/?probe=8d783c6b00) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [51868dd3c8](https://linux-hardware.org/?probe=51868dd3c8) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [44571410f0](https://linux-hardware.org/?probe=44571410f0) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [d54d77b051](https://linux-hardware.org/?probe=d54d77b051) | Jun 03, 2023 |
| HP            | 3047h                       | [1825675e99](https://linux-hardware.org/?probe=1825675e99) | Jun 03, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [ef7acf6baa](https://linux-hardware.org/?probe=ef7acf6baa) | Jun 03, 2023 |
| Dell          | 0M6C7G A00                  | [93bdbbdafb](https://linux-hardware.org/?probe=93bdbbdafb) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [4e17d7c6e8](https://linux-hardware.org/?probe=4e17d7c6e8) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [965de576c7](https://linux-hardware.org/?probe=965de576c7) | Jun 03, 2023 |
| Dell          | 0RY007                      | [f3028ff55d](https://linux-hardware.org/?probe=f3028ff55d) | Jun 02, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8aab7c6536](https://linux-hardware.org/?probe=8aab7c6536) | Jun 01, 2023 |
| HP            | 83E2                        | [eaf5f90360](https://linux-hardware.org/?probe=eaf5f90360) | Jun 01, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [3b9639141c](https://linux-hardware.org/?probe=3b9639141c) | May 31, 2023 |
| Dell          | 0RY007                      | [b726df555b](https://linux-hardware.org/?probe=b726df555b) | May 31, 2023 |
| Dell          | 0RY007                      | [32e931c79b](https://linux-hardware.org/?probe=32e931c79b) | May 31, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [953ee1ef05](https://linux-hardware.org/?probe=953ee1ef05) | May 31, 2023 |
| Gigabyte      | X99-UD7 WIFI-CF             | [955e65b76f](https://linux-hardware.org/?probe=955e65b76f) | May 31, 2023 |
| ASRock        | Z77 Extreme3                | [e45b1707bd](https://linux-hardware.org/?probe=e45b1707bd) | May 31, 2023 |
| ZOTAC         | Unknown                     | [0626de1b2a](https://linux-hardware.org/?probe=0626de1b2a) | May 31, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2703e7856e](https://linux-hardware.org/?probe=2703e7856e) | May 30, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [45e5adbb22](https://linux-hardware.org/?probe=45e5adbb22) | May 30, 2023 |
| Intel         | DH61BF AAG81311-102         | [22123492ab](https://linux-hardware.org/?probe=22123492ab) | May 30, 2023 |
| ASRock        | Z77 Extreme3                | [67c96085bf](https://linux-hardware.org/?probe=67c96085bf) | May 30, 2023 |
| ASUSTek       | ROG STRIX Z790-H GAMING ... | [11432ddeb6](https://linux-hardware.org/?probe=11432ddeb6) | May 29, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [312b05f0a4](https://linux-hardware.org/?probe=312b05f0a4) | May 29, 2023 |
| Gigabyte      | B360M D2V                   | [7fce8e04b2](https://linux-hardware.org/?probe=7fce8e04b2) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [7e895c167b](https://linux-hardware.org/?probe=7e895c167b) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [526503fef7](https://linux-hardware.org/?probe=526503fef7) | May 27, 2023 |
| AAEON         | UP-CHCR1 V0.4               | [b77201e825](https://linux-hardware.org/?probe=b77201e825) | May 26, 2023 |
| Dell          | 0MGK50 A02                  | [4572d76da5](https://linux-hardware.org/?probe=4572d76da5) | May 26, 2023 |
| Gigabyte      | P43-ES3G                    | [9683a94030](https://linux-hardware.org/?probe=9683a94030) | May 26, 2023 |
| Dell          | 0RY007                      | [6fb4081584](https://linux-hardware.org/?probe=6fb4081584) | May 25, 2023 |
| ASUSTek       | PRIME B460M-K               | [e55e554596](https://linux-hardware.org/?probe=e55e554596) | May 25, 2023 |
| ASUSTek       | A88XM-PLUS                  | [55790e804a](https://linux-hardware.org/?probe=55790e804a) | May 25, 2023 |
| Dell          | 03KWTV A02                  | [60ade2d50f](https://linux-hardware.org/?probe=60ade2d50f) | May 25, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [b291f783a2](https://linux-hardware.org/?probe=b291f783a2) | May 25, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [a2a31dbbee](https://linux-hardware.org/?probe=a2a31dbbee) | May 24, 2023 |
| ASUSTek       | Z87-DELUXE/DUAL             | [0f0c4f64ce](https://linux-hardware.org/?probe=0f0c4f64ce) | May 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ed936908c9](https://linux-hardware.org/?probe=ed936908c9) | May 23, 2023 |
| Intel         | DG31PR AAD97573-302         | [a36e076c17](https://linux-hardware.org/?probe=a36e076c17) | May 23, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [8b3acda484](https://linux-hardware.org/?probe=8b3acda484) | May 22, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [76bd19169a](https://linux-hardware.org/?probe=76bd19169a) | May 22, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [11c329d15a](https://linux-hardware.org/?probe=11c329d15a) | May 22, 2023 |
| Unknown       | DT138IB                     | [130e17f9e3](https://linux-hardware.org/?probe=130e17f9e3) | May 21, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [f511a54601](https://linux-hardware.org/?probe=f511a54601) | May 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [4a68db15c2](https://linux-hardware.org/?probe=4a68db15c2) | May 21, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8952bab351](https://linux-hardware.org/?probe=8952bab351) | May 21, 2023 |
| Gigabyte      | H77M-D3H                    | [88cf891056](https://linux-hardware.org/?probe=88cf891056) | May 21, 2023 |
| MSI           | H110M PRO-VD PLUS           | [d549fb62db](https://linux-hardware.org/?probe=d549fb62db) | May 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c242460e72](https://linux-hardware.org/?probe=c242460e72) | May 20, 2023 |
| HP            | 8055                        | [ddfca600c1](https://linux-hardware.org/?probe=ddfca600c1) | May 20, 2023 |
| ASUSTek       | PRIME B460M-K               | [c6ce2f365a](https://linux-hardware.org/?probe=c6ce2f365a) | May 20, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [5da7add39a](https://linux-hardware.org/?probe=5da7add39a) | May 20, 2023 |
| HP            | 8055                        | [d7b466e881](https://linux-hardware.org/?probe=d7b466e881) | May 20, 2023 |
| ASRock        | Z77 Extreme3                | [b60db9bc14](https://linux-hardware.org/?probe=b60db9bc14) | May 20, 2023 |
| ASUSTek       | Z170-A                      | [e168b46b94](https://linux-hardware.org/?probe=e168b46b94) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9f1830f264](https://linux-hardware.org/?probe=9f1830f264) | May 19, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [061e1e2aec](https://linux-hardware.org/?probe=061e1e2aec) | May 19, 2023 |
| ASUSTek       | PRIME B650M-A II            | [183b85c77c](https://linux-hardware.org/?probe=183b85c77c) | May 19, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [9dbbfc6c8e](https://linux-hardware.org/?probe=9dbbfc6c8e) | May 19, 2023 |
| Gigabyte      | H67A-D3H-B3                 | [606bb335e6](https://linux-hardware.org/?probe=606bb335e6) | May 19, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [f79cecb83e](https://linux-hardware.org/?probe=f79cecb83e) | May 19, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [e4b87f1e56](https://linux-hardware.org/?probe=e4b87f1e56) | May 19, 2023 |
| MSI           | MS-B9311                    | [3cfc1fbb83](https://linux-hardware.org/?probe=3cfc1fbb83) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d8d391a609](https://linux-hardware.org/?probe=d8d391a609) | May 18, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [87418d1634](https://linux-hardware.org/?probe=87418d1634) | May 18, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [c3626b71ae](https://linux-hardware.org/?probe=c3626b71ae) | May 18, 2023 |
| Gateway       | DS10G                       | [556a92e56a](https://linux-hardware.org/?probe=556a92e56a) | May 18, 2023 |
| ASUSTek       | M2N68-AM SE2                | [41971afc9c](https://linux-hardware.org/?probe=41971afc9c) | May 17, 2023 |
| Gigabyte      | H61M-DS2                    | [3c3f22e8c7](https://linux-hardware.org/?probe=3c3f22e8c7) | May 17, 2023 |
| Dell          | 0M3F6C A01                  | [d0fc9b65d0](https://linux-hardware.org/?probe=d0fc9b65d0) | May 17, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [74b2c2122c](https://linux-hardware.org/?probe=74b2c2122c) | May 17, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | [f7c208d0f0](https://linux-hardware.org/?probe=f7c208d0f0) | May 16, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [212936564d](https://linux-hardware.org/?probe=212936564d) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [5553ae2ec9](https://linux-hardware.org/?probe=5553ae2ec9) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [f297fbda85](https://linux-hardware.org/?probe=f297fbda85) | May 16, 2023 |
| Intel         | H61                         | [c54c89a4b1](https://linux-hardware.org/?probe=c54c89a4b1) | May 16, 2023 |
| MSI           | 3664h                       | [b45eee9c3a](https://linux-hardware.org/?probe=b45eee9c3a) | May 16, 2023 |
| HP            | 8055                        | [639cc3308f](https://linux-hardware.org/?probe=639cc3308f) | May 16, 2023 |
| HP            | 8055                        | [15c8401c45](https://linux-hardware.org/?probe=15c8401c45) | May 16, 2023 |
| HP            | 3397                        | [3cfe6e2812](https://linux-hardware.org/?probe=3cfe6e2812) | May 15, 2023 |
| Dell          | 0KV3RP A00                  | [d324b5e64d](https://linux-hardware.org/?probe=d324b5e64d) | May 15, 2023 |
| Intel         | DX79SI AAG28808-600         | [d222ee2f89](https://linux-hardware.org/?probe=d222ee2f89) | May 14, 2023 |
| Lenovo        | NOK                         | [9c6f0bae8f](https://linux-hardware.org/?probe=9c6f0bae8f) | May 14, 2023 |
| Gigabyte      | H61M-DS2                    | [423359d677](https://linux-hardware.org/?probe=423359d677) | May 14, 2023 |
| Gigabyte      | 970A-DS3                    | [97ef085eca](https://linux-hardware.org/?probe=97ef085eca) | May 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | [07bf228811](https://linux-hardware.org/?probe=07bf228811) | May 14, 2023 |
| Dell          | 0GWHMW A00                  | [d2dbc10885](https://linux-hardware.org/?probe=d2dbc10885) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | [bfff1b604f](https://linux-hardware.org/?probe=bfff1b604f) | May 13, 2023 |
| Dell          | 0D883F A05                  | [99e782e805](https://linux-hardware.org/?probe=99e782e805) | May 13, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [6d362f8c74](https://linux-hardware.org/?probe=6d362f8c74) | May 13, 2023 |
| Intel         | DG43GT AAE62768-303         | [4cc21b00e7](https://linux-hardware.org/?probe=4cc21b00e7) | May 12, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [33f3e64e8f](https://linux-hardware.org/?probe=33f3e64e8f) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | [dbf711a2f5](https://linux-hardware.org/?probe=dbf711a2f5) | May 11, 2023 |
| Dell          | 0GU083 A00                  | [eec8f60d12](https://linux-hardware.org/?probe=eec8f60d12) | May 11, 2023 |
| Dell          | 0J3C2F A02                  | [622dd024aa](https://linux-hardware.org/?probe=622dd024aa) | May 11, 2023 |
| ASRock        | H110M-HG4                   | [7995d3740a](https://linux-hardware.org/?probe=7995d3740a) | May 10, 2023 |
| ASRock        | H110M-HG4                   | [2864ff8227](https://linux-hardware.org/?probe=2864ff8227) | May 10, 2023 |
| Gigabyte      | B360N WIFI-CF               | [e4b3bba2b5](https://linux-hardware.org/?probe=e4b3bba2b5) | May 10, 2023 |
| ASRock        | B450M-HDV R4.0              | [297c4b54d4](https://linux-hardware.org/?probe=297c4b54d4) | May 10, 2023 |
| MSI           | B450 GAMING PLUS            | [df94e4a72a](https://linux-hardware.org/?probe=df94e4a72a) | May 10, 2023 |
| Dell          | 03NVJ6 A02                  | [9f509a2647](https://linux-hardware.org/?probe=9f509a2647) | May 10, 2023 |
| ASUSTek       | M2N68-AM SE2                | [39b8aee709](https://linux-hardware.org/?probe=39b8aee709) | May 10, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [1e41703eca](https://linux-hardware.org/?probe=1e41703eca) | May 09, 2023 |
| ASRock        | Z97 Extreme4                | [5803f15c1d](https://linux-hardware.org/?probe=5803f15c1d) | May 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | [669dc67190](https://linux-hardware.org/?probe=669dc67190) | May 09, 2023 |
| Acer          | Aspire TC-1760              | [24664f3383](https://linux-hardware.org/?probe=24664f3383) | May 09, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [de7b924fdb](https://linux-hardware.org/?probe=de7b924fdb) | May 08, 2023 |
| ASUSTek       | PRIME B450M-A               | [83c0648d66](https://linux-hardware.org/?probe=83c0648d66) | May 08, 2023 |
| Dell          | 0VNP2H A00                  | [ec04c034d3](https://linux-hardware.org/?probe=ec04c034d3) | May 08, 2023 |
| Gigabyte      | Z690 AERO G                 | [7673380766](https://linux-hardware.org/?probe=7673380766) | May 07, 2023 |
| ASUSTek       | M11BB                       | [35d2ca0280](https://linux-hardware.org/?probe=35d2ca0280) | May 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6a4a95e86f](https://linux-hardware.org/?probe=6a4a95e86f) | May 06, 2023 |
| Google        | Zako                        | [5d6aa6c0df](https://linux-hardware.org/?probe=5d6aa6c0df) | May 06, 2023 |
| ASRock        | Z97 Extreme4                | [7b83def3e1](https://linux-hardware.org/?probe=7b83def3e1) | May 06, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [7cf447e261](https://linux-hardware.org/?probe=7cf447e261) | May 05, 2023 |
| ASUSTek       | P8H61-M LX                  | [6c96dbe3f3](https://linux-hardware.org/?probe=6c96dbe3f3) | May 05, 2023 |
| MSI           | H110M PRO-VD PLUS           | [af27e2497a](https://linux-hardware.org/?probe=af27e2497a) | May 05, 2023 |
| HP            | 212B                        | [d71b834a1c](https://linux-hardware.org/?probe=d71b834a1c) | May 05, 2023 |
| ASRock        | Z77 Extreme3                | [0da080327f](https://linux-hardware.org/?probe=0da080327f) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | [14a87bc11a](https://linux-hardware.org/?probe=14a87bc11a) | May 04, 2023 |
| MSI           | A68HM-E33 V2                | [2f3264f25f](https://linux-hardware.org/?probe=2f3264f25f) | May 04, 2023 |
| Dell          | 0RY007                      | [3ec4846de7](https://linux-hardware.org/?probe=3ec4846de7) | May 03, 2023 |
| ASUSTek       | B150M-A/M.2                 | [cd68a79e95](https://linux-hardware.org/?probe=cd68a79e95) | May 03, 2023 |
| Lenovo        | IdeaCentre K320 10031       | [86fc44372c](https://linux-hardware.org/?probe=86fc44372c) | May 03, 2023 |
| Dell          | 0RY007                      | [54e2c92bb9](https://linux-hardware.org/?probe=54e2c92bb9) | May 02, 2023 |
| HP            | 198E                        | [9c02a85763](https://linux-hardware.org/?probe=9c02a85763) | May 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [0dd7d869b2](https://linux-hardware.org/?probe=0dd7d869b2) | May 02, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1362f2e3df](https://linux-hardware.org/?probe=1362f2e3df) | May 02, 2023 |
| Gigabyte      | H110M-DS2-CF                | [211eb49a00](https://linux-hardware.org/?probe=211eb49a00) | May 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [22cf2ddf02](https://linux-hardware.org/?probe=22cf2ddf02) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | [e89da96576](https://linux-hardware.org/?probe=e89da96576) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | [0aa06876c7](https://linux-hardware.org/?probe=0aa06876c7) | May 01, 2023 |
| Shuttle       | FS35V4                      | [137fda9bc6](https://linux-hardware.org/?probe=137fda9bc6) | May 01, 2023 |
| MSI           | A520M-A PRO                 | [aa8e8397f6](https://linux-hardware.org/?probe=aa8e8397f6) | May 01, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [705ff684a9](https://linux-hardware.org/?probe=705ff684a9) | Apr 30, 2023 |
| ASRock        | FM2A68M-HD+                 | [467bb5ded2](https://linux-hardware.org/?probe=467bb5ded2) | Apr 30, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [9a1d443928](https://linux-hardware.org/?probe=9a1d443928) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [233ea7cdd8](https://linux-hardware.org/?probe=233ea7cdd8) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [177fe2fc00](https://linux-hardware.org/?probe=177fe2fc00) | Apr 30, 2023 |
| ASUSTek       | B85M-G R2.0                 | [243a170e5a](https://linux-hardware.org/?probe=243a170e5a) | Apr 30, 2023 |
| HP            | ProLiant ML10 v2            | [3582be2f06](https://linux-hardware.org/?probe=3582be2f06) | Apr 30, 2023 |
| Dell          | 0T10XW A02                  | [2cd32d1efe](https://linux-hardware.org/?probe=2cd32d1efe) | Apr 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [4801547d54](https://linux-hardware.org/?probe=4801547d54) | Apr 29, 2023 |
| Apple         | Mac-F221BEC8                | [033718212c](https://linux-hardware.org/?probe=033718212c) | Apr 28, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [77150d1166](https://linux-hardware.org/?probe=77150d1166) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [d97d6d6dff](https://linux-hardware.org/?probe=d97d6d6dff) | Apr 28, 2023 |
| Lenovo        | NOK                         | [cf3db26781](https://linux-hardware.org/?probe=cf3db26781) | Apr 28, 2023 |
| Unknown       | G41                         | [2a6a185bec](https://linux-hardware.org/?probe=2a6a185bec) | Apr 28, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [de581801e8](https://linux-hardware.org/?probe=de581801e8) | Apr 27, 2023 |
| HP            | 1905                        | [7b15ec2d7d](https://linux-hardware.org/?probe=7b15ec2d7d) | Apr 26, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [eaac4c0ba0](https://linux-hardware.org/?probe=eaac4c0ba0) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [8f417742d1](https://linux-hardware.org/?probe=8f417742d1) | Apr 26, 2023 |
| ASUSTek       | H110-PLUS                   | [f8317bce7b](https://linux-hardware.org/?probe=f8317bce7b) | Apr 26, 2023 |
| Dell          | 0JP3NX A01                  | [2fa64e56ff](https://linux-hardware.org/?probe=2fa64e56ff) | Apr 25, 2023 |
| ASRock        | X670E Pro RS                | [e36216c3c7](https://linux-hardware.org/?probe=e36216c3c7) | Apr 25, 2023 |
| Dell          | 0K071D A01                  | [0c7edbd8ea](https://linux-hardware.org/?probe=0c7edbd8ea) | Apr 25, 2023 |
| ASUSTek       | P8B75-V                     | [f60927a4d8](https://linux-hardware.org/?probe=f60927a4d8) | Apr 24, 2023 |
| Dell          | 0JP3NX A01                  | [609eeb8038](https://linux-hardware.org/?probe=609eeb8038) | Apr 24, 2023 |
| MSI           | H81M PRO-VD                 | [00ade274cb](https://linux-hardware.org/?probe=00ade274cb) | Apr 24, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [88c455761b](https://linux-hardware.org/?probe=88c455761b) | Apr 24, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2d0269750e](https://linux-hardware.org/?probe=2d0269750e) | Apr 24, 2023 |
| MSI           | B460M PRO-VDH               | [f7709c23a1](https://linux-hardware.org/?probe=f7709c23a1) | Apr 24, 2023 |
| MSI           | Z97S SLI Krait Edition      | [6ed93f8338](https://linux-hardware.org/?probe=6ed93f8338) | Apr 24, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [0dfc7cce7a](https://linux-hardware.org/?probe=0dfc7cce7a) | Apr 23, 2023 |
| ASUSTek       | M5A78L LE                   | [df70910ec6](https://linux-hardware.org/?probe=df70910ec6) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [4e664e5e26](https://linux-hardware.org/?probe=4e664e5e26) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [658450824e](https://linux-hardware.org/?probe=658450824e) | Apr 23, 2023 |
| ASRock        | A75M-HVS                    | [a4964506f7](https://linux-hardware.org/?probe=a4964506f7) | Apr 23, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [67f15c6f4a](https://linux-hardware.org/?probe=67f15c6f4a) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [180784b3a2](https://linux-hardware.org/?probe=180784b3a2) | Apr 22, 2023 |
| ASRock        | Z170 Gaming K4              | [8209f53171](https://linux-hardware.org/?probe=8209f53171) | Apr 22, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [2afc5398b8](https://linux-hardware.org/?probe=2afc5398b8) | Apr 22, 2023 |
| ASRock        | Z97E-ITX/ac                 | [f916f697ed](https://linux-hardware.org/?probe=f916f697ed) | Apr 22, 2023 |
| Biostar       | H410MH S2                   | [0f2593dc78](https://linux-hardware.org/?probe=0f2593dc78) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [a60c54ec31](https://linux-hardware.org/?probe=a60c54ec31) | Apr 22, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [f89cce4966](https://linux-hardware.org/?probe=f89cce4966) | Apr 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [170b38e40f](https://linux-hardware.org/?probe=170b38e40f) | Apr 20, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [9f81660d12](https://linux-hardware.org/?probe=9f81660d12) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M LX                 | [c34c1abf02](https://linux-hardware.org/?probe=c34c1abf02) | Apr 18, 2023 |
| BESSTAR Te... | UM700                       | [2e820040bc](https://linux-hardware.org/?probe=2e820040bc) | Apr 02, 2023 |
| ASUSTek       | M5A78L LE                   | [7a23362aac](https://linux-hardware.org/?probe=7a23362aac) | Mar 31, 2023 |
| HP            | 18E5                        | [82e5831486](https://linux-hardware.org/?probe=82e5831486) | Mar 10, 2023 |
| MSI           | A320M PRO-VD PLUS           | [6677ab11b2](https://linux-hardware.org/?probe=6677ab11b2) | Feb 28, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [580db05e08](https://linux-hardware.org/?probe=580db05e08) | Feb 27, 2023 |
| Gigabyte      | GA-880GM-USB3               | [bb5da28703](https://linux-hardware.org/?probe=bb5da28703) | Feb 23, 2023 |
| Fujitsu Si... | D2420 S26361-D2420          | [9e8c937daa](https://linux-hardware.org/?probe=9e8c937daa) | Dec 31, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | [019236854d](https://linux-hardware.org/?probe=019236854d) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | [d6f064e643](https://linux-hardware.org/?probe=d6f064e643) | Dec 30, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [ba498df129](https://linux-hardware.org/?probe=ba498df129) | Dec 23, 2022 |
| Gigabyte      | B85M-D3H                    | [1550136432](https://linux-hardware.org/?probe=1550136432) | Dec 06, 2022 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [1817579f89](https://linux-hardware.org/?probe=1817579f89) | Nov 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_23.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.2.0-20-generic        | 184      | 32.11%  |
| 6.2.0-34-generic        | 44       | 7.68%   |
| 6.2.0-27-generic        | 39       | 6.81%   |
| 6.2.0-33-generic        | 33       | 5.76%   |
| 6.2.0-26-generic        | 32       | 5.58%   |
| 6.2.0-24-generic        | 31       | 5.41%   |
| 6.2.0-25-generic        | 30       | 5.24%   |
| 6.2.0-32-generic        | 27       | 4.71%   |
| 6.2.0-23-generic        | 27       | 4.71%   |
| 6.2.0-36-generic        | 21       | 3.66%   |
| 6.2.0-39-generic        | 20       | 3.49%   |
| 6.2.0-35-generic        | 18       | 3.14%   |
| 6.2.0-31-generic        | 16       | 2.79%   |
| 6.2.0-37-generic        | 7        | 1.22%   |
| 5.19.0-21-generic       | 5        | 0.87%   |
| 6.5.0-14-generic        | 2        | 0.35%   |
| 6.3.6-060306-generic    | 2        | 0.35%   |
| 6.3.4-060304-generic    | 2        | 0.35%   |
| 6.3.2-060302-generic    | 2        | 0.35%   |
| 6.2.16-060216-generic   | 2        | 0.35%   |
| 6.2.0-18-generic        | 2        | 0.35%   |
| 6.2.0-1007-lowlatency   | 2        | 0.35%   |
| 6.5.5-zen1-1-zen        | 1        | 0.17%   |
| 6.5.4-060504-generic    | 1        | 0.17%   |
| 6.5.2-tkg-bore-llvm     | 1        | 0.17%   |
| 6.5.0-17-generic        | 1        | 0.17%   |
| 6.5.0-060500rc5-generic | 1        | 0.17%   |
| 6.5.0-060500-generic    | 1        | 0.17%   |
| 6.4.6-060406-generic    | 1        | 0.17%   |
| 6.4.0-060400-generic    | 1        | 0.17%   |
| 6.2.16-3-pve            | 1        | 0.17%   |
| 6.2.11-060211-generic   | 1        | 0.17%   |
| 6.2.1-060201-generic    | 1        | 0.17%   |
| 6.2.0-19-generic        | 1        | 0.17%   |
| 6.2.0-1017-lowlatency   | 1        | 0.17%   |
| 6.2.0-1014-gcp          | 1        | 0.17%   |
| 6.2.0-1010-lowlatency   | 1        | 0.17%   |
| 6.2.0-1009-lowlatency   | 1        | 0.17%   |
| 6.2.0-1007-gcp          | 1        | 0.17%   |
| 6.2.0-1003-oracle       | 1        | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 502      | 94.36%  |
| 5.19.0  | 9        | 1.69%   |
| 6.5.0   | 4        | 0.75%   |
| 6.2.16  | 3        | 0.56%   |
| 6.3.6   | 2        | 0.38%   |
| 6.3.4   | 2        | 0.38%   |
| 6.3.2   | 2        | 0.38%   |
| 6.5.5   | 1        | 0.19%   |
| 6.5.4   | 1        | 0.19%   |
| 6.5.2   | 1        | 0.19%   |
| 6.4.6   | 1        | 0.19%   |
| 6.4.0   | 1        | 0.19%   |
| 6.2.11  | 1        | 0.19%   |
| 6.2.1   | 1        | 0.19%   |
| 6.1.0   | 1        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 506      | 95.29%  |
| 5.19    | 9        | 1.69%   |
| 6.5     | 7        | 1.32%   |
| 6.3     | 6        | 1.13%   |
| 6.4     | 2        | 0.38%   |
| 6.1     | 1        | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 531      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 506      | 95.29%  |
| Unknown         | 12       | 2.26%   |
| X-Cinnamon      | 9        | 1.69%   |
| GNOME Flashback | 2        | 0.38%   |
| i3              | 1        | 0.19%   |
| DDE             | 1        | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 308      | 57.14%  |
| X11     | 209      | 38.78%  |
| Tty     | 11       | 2.04%   |
| Unknown | 11       | 2.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 466      | 87.43%  |
| Unknown | 52       | 9.76%   |
| LightDM | 12       | 2.25%   |
| GDM     | 3        | 0.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 239      | 44.59%  |
| de_DE   | 68       | 12.69%  |
| fr_FR   | 30       | 5.6%    |
| C       | 24       | 4.48%   |
| pt_BR   | 22       | 4.1%    |
| en_GB   | 16       | 2.99%   |
| es_ES   | 15       | 2.8%    |
| it_IT   | 14       | 2.61%   |
| en_CA   | 11       | 2.05%   |
| ru_RU   | 10       | 1.87%   |
| pl_PL   | 8        | 1.49%   |
| en_AU   | 7        | 1.31%   |
| nl_NL   | 5        | 0.93%   |
| Unknown | 5        | 0.93%   |
| zh_CN   | 4        | 0.75%   |
| hu_HU   | 4        | 0.75%   |
| fi_FI   | 4        | 0.75%   |
| de_AT   | 4        | 0.75%   |
| cs_CZ   | 4        | 0.75%   |
| sv_SE   | 3        | 0.56%   |
| pt_PT   | 3        | 0.56%   |
| en_IN   | 3        | 0.56%   |
| el_GR   | 3        | 0.56%   |
| zh_TW   | 2        | 0.37%   |
| sk_SK   | 2        | 0.37%   |
| en_ZA   | 2        | 0.37%   |
| en_NZ   | 2        | 0.37%   |
| en_IL   | 2        | 0.37%   |
| bg_BG   | 2        | 0.37%   |
| tr_TR   | 1        | 0.19%   |
| nl_BE   | 1        | 0.19%   |
| nb_NO   | 1        | 0.19%   |
| lt_LT   | 1        | 0.19%   |
| ko_KR   | 1        | 0.19%   |
| ja_JP   | 1        | 0.19%   |
| fr_CH   | 1        | 0.19%   |
| fr_CA   | 1        | 0.19%   |
| es_MX   | 1        | 0.19%   |
| es_CL   | 1        | 0.19%   |
| es_AR   | 1        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 386      | 72.01%  |
| EFI  | 150      | 27.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Tmpfs   | 328      | 61.08%  |
| Ext4    | 192      | 35.75%  |
| Overlay | 6        | 1.12%   |
| Zfs     | 5        | 0.93%   |
| Btrfs   | 5        | 0.93%   |
| Xfs     | 1        | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 454      | 85.02%  |
| Unknown | 41       | 7.68%   |
| MBR     | 39       | 7.3%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 429      | 79.59%  |
| Yes       | 110      | 20.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 327      | 60.78%  |
| Yes       | 211      | 39.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 150      | 28.25%  |
| Gigabyte Technology                  | 71       | 13.37%  |
| MSI                                  | 64       | 12.05%  |
| Dell                                 | 44       | 8.29%   |
| ASRock                               | 42       | 7.91%   |
| Hewlett-Packard                      | 38       | 7.16%   |
| Lenovo                               | 25       | 4.71%   |
| Intel                                | 22       | 4.14%   |
| Unknown                              | 10       | 1.88%   |
| Fujitsu                              | 9        | 1.69%   |
| Biostar                              | 5        | 0.94%   |
| Apple                                | 4        | 0.75%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.56%   |
| Huanan                               | 3        | 0.56%   |
| Acer                                 | 3        | 0.56%   |
| Supermicro                           | 2        | 0.38%   |
| Shuttle                              | 2        | 0.38%   |
| Pegatron                             | 2        | 0.38%   |
| ONDA                                 | 2        | 0.38%   |
| MACHINIST                            | 2        | 0.38%   |
| GEEKOM                               | 2        | 0.38%   |
| Foxconn                              | 2        | 0.38%   |
| AZW                                  | 2        | 0.38%   |
| ZOTAC                                | 1        | 0.19%   |
| System76                             | 1        | 0.19%   |
| SHANGZHAOYUAN                        | 1        | 0.19%   |
| Quanta                               | 1        | 0.19%   |
| Packard Bell                         | 1        | 0.19%   |
| NZXT                                 | 1        | 0.19%   |
| Medion                               | 1        | 0.19%   |
| Login Informatica                    | 1        | 0.19%   |
| Itautec                              | 1        | 0.19%   |
| Google                               | 1        | 0.19%   |
| GMKtec                               | 1        | 0.19%   |
| GIADA                                | 1        | 0.19%   |
| Gateway                              | 1        | 0.19%   |
| Fujitsu Siemens                      | 1        | 0.19%   |
| Entroware                            | 1        | 0.19%   |
| eMachines                            | 1        | 0.19%   |
| ECS                                  | 1        | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 12       | 2.26%   |
| ASUS All Series                    | 10       | 1.88%   |
| MSI MS-7B86                        | 4        | 0.75%   |
| MSI MS-7C95                        | 3        | 0.56%   |
| MSI MS-7721                        | 3        | 0.56%   |
| Intel H61                          | 3        | 0.56%   |
| Gigabyte B450M DS3H                | 3        | 0.56%   |
| Dell OptiPlex 790                  | 3        | 0.56%   |
| Dell OptiPlex 3010                 | 3        | 0.56%   |
| ASUS ROG STRIX B650E-I GAMING WIFI | 3        | 0.56%   |
| ASUS PRIME B660M-A D4              | 3        | 0.56%   |
| ASRock A320M-HDV R4.0              | 3        | 0.56%   |
| Apple MacPro5,1                    | 3        | 0.56%   |
| MSI MS-7D73                        | 2        | 0.38%   |
| MSI MS-7C96                        | 2        | 0.38%   |
| MSI MS-7C56                        | 2        | 0.38%   |
| MSI MS-7C37                        | 2        | 0.38%   |
| MSI MS-7C02                        | 2        | 0.38%   |
| MSI MS-7596                        | 2        | 0.38%   |
| HP ProLiant ML10 v2                | 2        | 0.38%   |
| HP ProDesk 600 G3 SFF              | 2        | 0.38%   |
| HP ProDesk 600 G2 SFF              | 2        | 0.38%   |
| HP ProDesk 600 G1 SFF              | 2        | 0.38%   |
| HP EliteDesk 800 G5 Desktop Mini   | 2        | 0.38%   |
| HP EliteDesk 800 G2 DM 35W         | 2        | 0.38%   |
| Gigabyte X670 AORUS ELITE AX       | 2        | 0.38%   |
| Gigabyte H61M-DS2                  | 2        | 0.38%   |
| Gigabyte G41M-Combo                | 2        | 0.38%   |
| Gigabyte A520M S2H                 | 2        | 0.38%   |
| Fujitsu ESPRIMO Q920               | 2        | 0.38%   |
| Dell XPS 8940                      | 2        | 0.38%   |
| Dell Precision Tower 7810          | 2        | 0.38%   |
| Dell OptiPlex 7020                 | 2        | 0.38%   |
| Dell OptiPlex 7010                 | 2        | 0.38%   |
| Dell OptiPlex 3050                 | 2        | 0.38%   |
| Dell OptiPlex 3040                 | 2        | 0.38%   |
| ASUS Z170-P                        | 2        | 0.38%   |
| ASUS TUF Gaming Z590-PLUS WIFI     | 2        | 0.38%   |
| ASUS TUF Gaming X670E-PLUS WIFI    | 2        | 0.38%   |
| ASUS TUF Gaming X570-PLUS          | 2        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 41       | 7.72%   |
| Dell OptiPlex       | 24       | 4.52%   |
| ASUS ROG            | 24       | 4.52%   |
| ASUS TUF            | 21       | 3.95%   |
| Lenovo ThinkCentre  | 16       | 3.01%   |
| Unknown             | 12       | 2.26%   |
| ASUS All            | 10       | 1.88%   |
| HP ProDesk          | 9        | 1.69%   |
| HP EliteDesk        | 8        | 1.51%   |
| HP Compaq           | 7        | 1.32%   |
| Dell Precision      | 6        | 1.13%   |
| Fujitsu ESPRIMO     | 5        | 0.94%   |
| Dell Inspiron       | 5        | 0.94%   |
| MSI MS-7B86         | 4        | 0.75%   |
| Lenovo IdeaCentre   | 4        | 0.75%   |
| Intel H61           | 4        | 0.75%   |
| Gigabyte X570       | 4        | 0.75%   |
| Gigabyte H61M-DS2   | 4        | 0.75%   |
| Dell XPS            | 4        | 0.75%   |
| ASUS P8Z77-V        | 4        | 0.75%   |
| ASUS M5A78L-M       | 4        | 0.75%   |
| ASRock A320M-HDV    | 4        | 0.75%   |
| MSI MS-7C95         | 3        | 0.56%   |
| MSI MS-7721         | 3        | 0.56%   |
| Lenovo ThinkStation | 3        | 0.56%   |
| Gigabyte B450M      | 3        | 0.56%   |
| Gigabyte A520M      | 3        | 0.56%   |
| Dell Vostro         | 3        | 0.56%   |
| ASUS P8H61-M        | 3        | 0.56%   |
| ASUS M5A97          | 3        | 0.56%   |
| ASRock Z370         | 3        | 0.56%   |
| Apple MacPro5       | 3        | 0.56%   |
| MSI MS-7D73         | 2        | 0.38%   |
| MSI MS-7C96         | 2        | 0.38%   |
| MSI MS-7C56         | 2        | 0.38%   |
| MSI MS-7C37         | 2        | 0.38%   |
| MSI MS-7C02         | 2        | 0.38%   |
| MSI MS-7596         | 2        | 0.38%   |
| Intel X99           | 2        | 0.38%   |
| Huanan X99-F8       | 2        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2022 | 61       | 11.49%  |
| 2018 | 46       | 8.66%   |
| 2014 | 46       | 8.66%   |
| 2012 | 42       | 7.91%   |
| 2021 | 41       | 7.72%   |
| 2013 | 41       | 7.72%   |
| 2019 | 40       | 7.53%   |
| 2020 | 37       | 6.97%   |
| 2017 | 28       | 5.27%   |
| 2015 | 28       | 5.27%   |
| 2011 | 25       | 4.71%   |
| 2023 | 23       | 4.33%   |
| 2010 | 23       | 4.33%   |
| 2016 | 22       | 4.14%   |
| 2009 | 17       | 3.2%    |
| 2008 | 5        | 0.94%   |
| 2006 | 3        | 0.56%   |
| 2007 | 2        | 0.38%   |
| 2005 | 1        | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 531      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 512      | 96.24%  |
| Enabled  | 20       | 3.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 530      | 99.81%  |
| Yes  | 1        | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 135      | 25.23%  |
| 32.01-64.0      | 103      | 19.25%  |
| 4.01-8.0        | 89       | 16.64%  |
| 8.01-16.0       | 67       | 12.52%  |
| 64.01-256.0     | 56       | 10.47%  |
| 3.01-4.0        | 48       | 8.97%   |
| 24.01-32.0      | 26       | 4.86%   |
| 1.01-2.0        | 5        | 0.93%   |
| More than 256.0 | 3        | 0.56%   |
| 2.01-3.0        | 3        | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 168      | 30.16%  |
| 1.01-2.0   | 148      | 26.57%  |
| 4.01-8.0   | 112      | 20.11%  |
| 3.01-4.0   | 84       | 15.08%  |
| 8.01-16.0  | 32       | 5.75%   |
| 24.01-32.0 | 5        | 0.9%    |
| 32.01-64.0 | 3        | 0.54%   |
| 0.51-1.0   | 3        | 0.54%   |
| 16.01-24.0 | 2        | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 225      | 41.44%  |
| 2      | 132      | 24.31%  |
| 3      | 92       | 16.94%  |
| 4      | 45       | 8.29%   |
| 5      | 21       | 3.87%   |
| 6      | 15       | 2.76%   |
| 8      | 5        | 0.92%   |
| 7      | 4        | 0.74%   |
| 101    | 1        | 0.18%   |
| 12     | 1        | 0.18%   |
| 9      | 1        | 0.18%   |
| 0      | 1        | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 337      | 62.87%  |
| Yes       | 199      | 37.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 525      | 98.68%  |
| No        | 7        | 1.32%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 283      | 53.1%   |
| No        | 250      | 46.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 309      | 57.54%  |
| Yes       | 228      | 42.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 108      | 20.34%  |
| Germany      | 79       | 14.88%  |
| France       | 32       | 6.03%   |
| Canada       | 31       | 5.84%   |
| Brazil       | 28       | 5.27%   |
| UK           | 24       | 4.52%   |
| Italy        | 23       | 4.33%   |
| Australia    | 16       | 3.01%   |
| Russia       | 15       | 2.82%   |
| Netherlands  | 12       | 2.26%   |
| Sweden       | 11       | 2.07%   |
| Spain        | 10       | 1.88%   |
| India        | 10       | 1.88%   |
| Czechia      | 8        | 1.51%   |
| Switzerland  | 7        | 1.32%   |
| Poland       | 7        | 1.32%   |
| Finland      | 7        | 1.32%   |
| Portugal     | 6        | 1.13%   |
| Austria      | 6        | 1.13%   |
| Turkey       | 5        | 0.94%   |
| Norway       | 5        | 0.94%   |
| Hungary      | 5        | 0.94%   |
| Greece       | 5        | 0.94%   |
| Belgium      | 5        | 0.94%   |
| Philippines  | 4        | 0.75%   |
| New Zealand  | 4        | 0.75%   |
| China        | 4        | 0.75%   |
| South Africa | 3        | 0.56%   |
| Romania      | 3        | 0.56%   |
| Peru         | 3        | 0.56%   |
| Mexico       | 3        | 0.56%   |
| Israel       | 3        | 0.56%   |
| Iran         | 3        | 0.56%   |
| Hong Kong    | 3        | 0.56%   |
| Argentina    | 3        | 0.56%   |
| Taiwan       | 2        | 0.38%   |
| South Korea  | 2        | 0.38%   |
| Serbia       | 2        | 0.38%   |
| Malaysia     | 2        | 0.38%   |
| Lithuania    | 2        | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Sao Paulo     | 7        | 1.29%   |
| Moscow        | 5        | 0.92%   |
| Montreal      | 5        | 0.92%   |
| Helsinki      | 5        | 0.92%   |
| Hamburg       | 5        | 0.92%   |
| Brisbane      | 5        | 0.92%   |
| St Petersburg | 4        | 0.74%   |
| Rome          | 4        | 0.74%   |
| Prague        | 4        | 0.74%   |
| Melbourne     | 4        | 0.74%   |
| Hanover       | 4        | 0.74%   |
| Berlin        | 4        | 0.74%   |
| Winnipeg      | 3        | 0.55%   |
| Warsaw        | 3        | 0.55%   |
| Valencia      | 3        | 0.55%   |
| Tourcoing     | 3        | 0.55%   |
| Toronto       | 3        | 0.55%   |
| Tehran        | 3        | 0.55%   |
| Sydney        | 3        | 0.55%   |
| Gothenburg    | 3        | 0.55%   |
| Edmonton      | 3        | 0.55%   |
| Brussels      | 3        | 0.55%   |
| Auckland      | 3        | 0.55%   |
| Amsterdam     | 3        | 0.55%   |
| Waynesboro    | 2        | 0.37%   |
| Vienna        | 2        | 0.37%   |
| Surat         | 2        | 0.37%   |
| Sorocaba      | 2        | 0.37%   |
| Seattle       | 2        | 0.37%   |
| Sacramento    | 2        | 0.37%   |
| Porto Alegre  | 2        | 0.37%   |
| Plaisir       | 2        | 0.37%   |
| Petah Tikva   | 2        | 0.37%   |
| Oshawa        | 2        | 0.37%   |
| Munich        | 2        | 0.37%   |
| Minneapolis   | 2        | 0.37%   |
| Marcon        | 2        | 0.37%   |
| Makati City   | 2        | 0.37%   |
| Lima          | 2        | 0.37%   |
| Las Vegas     | 2        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 168      | 248    | 17%     |
| Seagate                     | 157      | 236    | 15.89%  |
| WDC                         | 155      | 262    | 15.69%  |
| SanDisk                     | 57       | 79     | 5.77%   |
| Kingston                    | 54       | 63     | 5.47%   |
| Crucial                     | 42       | 49     | 4.25%   |
| Toshiba                     | 36       | 52     | 3.64%   |
| Hitachi                     | 26       | 35     | 2.63%   |
| Intel                       | 19       | 21     | 1.92%   |
| Phison Electronics          | 16       | 19     | 1.62%   |
| Micron/Crucial Technology   | 15       | 18     | 1.52%   |
| SK hynix                    | 13       | 13     | 1.32%   |
| Kingston Technology Company | 11       | 17     | 1.11%   |
| China                       | 10       | 14     | 1.01%   |
| Unknown                     | 9        | 16     | 0.91%   |
| PNY                         | 9        | 13     | 0.91%   |
| HGST                        | 9        | 36     | 0.91%   |
| Micron Technology           | 8        | 10     | 0.81%   |
| Intenso                     | 8        | 10     | 0.81%   |
| A-DATA Technology           | 8        | 13     | 0.81%   |
| Silicon Motion              | 7        | 7      | 0.71%   |
| OCZ                         | 7        | 7      | 0.71%   |
| SABRENT                     | 6        | 9      | 0.61%   |
| Patriot                     | 6        | 6      | 0.61%   |
| MAXIO Technology (Hangzhou) | 5        | 5      | 0.51%   |
| Hewlett-Packard             | 5        | 5      | 0.51%   |
| Corsair                     | 5        | 6      | 0.51%   |
| Apacer                      | 5        | 6      | 0.51%   |
| Unknown                     | 5        | 7      | 0.51%   |
| SPCC                        | 4        | 5      | 0.4%    |
| Phison                      | 4        | 5      | 0.4%    |
| Netac                       | 4        | 4      | 0.4%    |
| Lexar                       | 4        | 4      | 0.4%    |
| KIOXIA                      | 4        | 4      | 0.4%    |
| Gigabyte Technology         | 4        | 4      | 0.4%    |
| KingSpec                    | 3        | 4      | 0.3%    |
| ASMT                        | 3        | 5      | 0.3%    |
| Vaseky                      | 2        | 2      | 0.2%    |
| Transcend                   | 2        | 2      | 0.2%    |
| Team                        | 2        | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 29       | 2.51%   |
| Seagate ST1000DM010-2EP102 1TB                        | 14       | 1.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 14       | 1.21%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 13       | 1.13%   |
| Samsung SSD 980 1TB                                   | 11       | 0.95%   |
| Samsung SSD 860 EVO 500GB                             | 11       | 0.95%   |
| Kingston SA400S37240G 240GB SSD                       | 11       | 0.95%   |
| Seagate ST2000DM008-2FR102 2TB                        | 10       | 0.87%   |
| Samsung SSD 850 EVO 250GB                             | 10       | 0.87%   |
| Kingston SA400S37480G 480GB SSD                       | 7        | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 6        | 0.52%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 6        | 0.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 6        | 0.52%   |
| Seagate ST500DM002-1BD142 500GB                       | 6        | 0.52%   |
| Seagate ST4000DM004-2CV104 4TB                        | 6        | 0.52%   |
| Seagate ST3500418AS 500GB                             | 6        | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB                        | 6        | 0.52%   |
| Samsung SSD 870 EVO 1TB                               | 6        | 0.52%   |
| Samsung SSD 860 QVO 1TB                               | 6        | 0.52%   |
| Samsung SSD 850 EVO 500GB                             | 6        | 0.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB     | 6        | 0.52%   |
| Phison E12 NVMe Controller 2TB                        | 6        | 0.52%   |
| Kingston SV300S37A120G 120GB SSD                      | 6        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                           | 6        | 0.52%   |
| WDC WD20EZRX-00D8PB0 2TB                              | 5        | 0.43%   |
| Seagate ST2000DM006-2DM164 2TB                        | 5        | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB                        | 5        | 0.43%   |
| Seagate ST2000DM001-1CH164 2TB                        | 5        | 0.43%   |
| Seagate ST1000DM003-1SB102 1TB                        | 5        | 0.43%   |
| Seagate ST1000DM003-1ER162 1TB                        | 5        | 0.43%   |
| SanDisk SSD PLUS 1000GB                               | 5        | 0.43%   |
| Samsung SSD 990 PRO 1TB                               | 5        | 0.43%   |
| Samsung SSD 870 EVO 500GB                             | 5        | 0.43%   |
| Samsung SSD 860 EVO 1TB                               | 5        | 0.43%   |
| Samsung PSSD T7 1TB                                   | 5        | 0.43%   |
| SABRENT Disk 1TB                                      | 5        | 0.43%   |
| Crucial CT240BX500SSD1 240GB                          | 5        | 0.43%   |
| Unknown                                               | 5        | 0.43%   |
| WDC WD5000AAKX-001CA0 500GB                           | 4        | 0.35%   |
| Toshiba DT01ACA100 1TB                                | 4        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 150      | 227    | 38.17%  |
| WDC                 | 140      | 233    | 35.62%  |
| Toshiba             | 30       | 44     | 7.63%   |
| Hitachi             | 26       | 35     | 6.62%   |
| Samsung Electronics | 20       | 24     | 5.09%   |
| HGST                | 9        | 14     | 2.29%   |
| SABRENT             | 5        | 8      | 1.27%   |
| Unknown             | 3        | 3      | 0.76%   |
| Maxtor              | 2        | 3      | 0.51%   |
| TO Exter            | 1        | 1      | 0.25%   |
| OOS16000            | 1        | 1      | 0.25%   |
| NETAPP              | 1        | 12     | 0.25%   |
| Intenso             | 1        | 1      | 0.25%   |
| Hewlett-Packard     | 1        | 1      | 0.25%   |
| ASMT                | 1        | 3      | 0.25%   |
| Apple               | 1        | 1      | 0.25%   |
| Unknown             | 1        | 1      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 77       | 106    | 23.05%  |
| Kingston            | 40       | 47     | 11.98%  |
| Crucial             | 34       | 38     | 10.18%  |
| SanDisk             | 31       | 41     | 9.28%   |
| WDC                 | 20       | 21     | 5.99%   |
| Intel               | 10       | 12     | 2.99%   |
| China               | 10       | 14     | 2.99%   |
| PNY                 | 8        | 11     | 2.4%    |
| OCZ                 | 7        | 7      | 2.1%    |
| Patriot             | 6        | 6      | 1.8%    |
| Intenso             | 6        | 8      | 1.8%    |
| A-DATA Technology   | 6        | 11     | 1.8%    |
| Apacer              | 5        | 6      | 1.5%    |
| Toshiba             | 3        | 4      | 0.9%    |
| Micron Technology   | 3        | 4      | 0.9%    |
| KingSpec            | 3        | 4      | 0.9%    |
| Hewlett-Packard     | 3        | 3      | 0.9%    |
| Unknown             | 3        | 3      | 0.9%    |
| Vaseky              | 2        | 2      | 0.6%    |
| Team                | 2        | 2      | 0.6%    |
| SPCC                | 2        | 2      | 0.6%    |
| SK hynix            | 2        | 2      | 0.6%    |
| OWC                 | 2        | 6      | 0.6%    |
| INNOVATION IT       | 2        | 2      | 0.6%    |
| GOODRAM             | 2        | 3      | 0.6%    |
| Gigastone           | 2        | 2      | 0.6%    |
| Gigabyte Technology | 2        | 2      | 0.6%    |
| Emtec               | 2        | 2      | 0.6%    |
| ASMT                | 2        | 2      | 0.6%    |
| WALRAM              | 1        | 1      | 0.3%    |
| Verbatim            | 1        | 6      | 0.3%    |
| V7                  | 1        | 1      | 0.3%    |
| USB3.0              | 1        | 1      | 0.3%    |
| Transcend           | 1        | 1      | 0.3%    |
| TEXTORM             | 1        | 1      | 0.3%    |
| TCSUNBOW            | 1        | 1      | 0.3%    |
| T-FORCE             | 1        | 1      | 0.3%    |
| SUNEAST             | 1        | 1      | 0.3%    |
| Smartbuy            | 1        | 2      | 0.3%    |
| SILICONMOTION       | 1        | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 313      | 612    | 37.49%  |
| SSD     | 278      | 421    | 33.29%  |
| NVMe    | 223      | 335    | 26.71%  |
| Unknown | 19       | 55     | 2.28%   |
| MMC     | 2        | 2      | 0.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 439      | 964    | 61.48%  |
| NVMe | 223      | 327    | 31.23%  |
| SAS  | 50       | 132    | 7%      |
| MMC  | 2        | 2      | 0.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 290      | 459    | 44.82%  |
| 0.51-1.0   | 191      | 278    | 29.52%  |
| 1.01-2.0   | 84       | 111    | 12.98%  |
| 3.01-4.0   | 35       | 60     | 5.41%   |
| 4.01-10.0  | 21       | 52     | 3.25%   |
| 2.01-3.0   | 17       | 20     | 2.63%   |
| 10.01-20.0 | 9        | 53     | 1.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 122      | 22.34%  |
| 101-250        | 117      | 21.43%  |
| 251-500        | 104      | 19.05%  |
| More than 3000 | 62       | 11.36%  |
| 1001-2000      | 62       | 11.36%  |
| 2001-3000      | 35       | 6.41%   |
| 1-20           | 17       | 3.11%   |
| 51-100         | 15       | 2.75%   |
| 21-50          | 8        | 1.47%   |
| Unknown        | 4        | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 140      | 25.36%  |
| 21-50          | 118      | 21.38%  |
| 101-250        | 73       | 13.22%  |
| 51-100         | 65       | 11.78%  |
| 251-500        | 47       | 8.51%   |
| 501-1000       | 41       | 7.43%   |
| More than 3000 | 26       | 4.71%   |
| 1001-2000      | 21       | 3.8%    |
| 2001-3000      | 17       | 3.08%   |
| Unknown        | 4        | 0.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Desktops | Drives | Percent |
|-----------------------------------------|----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD        | 2        | 2      | 4.88%   |
| WDC WD6400AACS-00G8B1 640GB             | 1        | 1      | 2.44%   |
| WDC WD60EFRX-68L0BN1 6TB                | 1        | 1      | 2.44%   |
| WDC WD5000HHTZ-04N21V0 500GB            | 1        | 1      | 2.44%   |
| WDC WD5000AZLX-22JKKA0 500GB            | 1        | 1      | 2.44%   |
| WDC WD5000AAKX-001CA0 500GB             | 1        | 1      | 2.44%   |
| WDC WD5000AAKS-00UU3A0 500GB            | 1        | 1      | 2.44%   |
| WDC WD2500AAKX-753CA1 250GB             | 1        | 1      | 2.44%   |
| WDC WD2500AAJS-75M0A0 250GB             | 1        | 1      | 2.44%   |
| WDC WD10EZRZ-00HTKB0 1TB                | 1        | 1      | 2.44%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1        | 1      | 2.44%   |
| WDC WD10EZEX-22MFCA0 1TB                | 1        | 2      | 2.44%   |
| WDC WD10EARS-22Y5B1 1TB                 | 1        | 1      | 2.44%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 1        | 1      | 2.44%   |
| WDC WD1003FBYX-01Y7B0 1TB               | 1        | 1      | 2.44%   |
| Toshiba MK3261GSYN 320GB                | 1        | 1      | 2.44%   |
| Toshiba MK2555GSXF 250GB                | 1        | 1      | 2.44%   |
| Seagate ST8000DM0004-1ZC11G 8TB         | 1        | 1      | 2.44%   |
| Seagate ST500DM002-1BD142 500GB         | 1        | 1      | 2.44%   |
| Seagate ST3500418AS 500GB               | 1        | 1      | 2.44%   |
| Seagate ST2000LX001-1RG174 2TB          | 1        | 1      | 2.44%   |
| Seagate ST2000LM007-1R8174 2TB          | 1        | 1      | 2.44%   |
| Seagate ST2000DM008-2FR102 2TB          | 1        | 1      | 2.44%   |
| SanDisk SSD PLUS 240GB                  | 1        | 1      | 2.44%   |
| SanDisk SD7SB2Q-512G-1006 512GB SSD     | 1        | 1      | 2.44%   |
| Samsung Electronics SSD 960 EVO 250GB   | 1        | 1      | 2.44%   |
| Samsung Electronics HD502HJ 500GB       | 1        | 1      | 2.44%   |
| Samsung Electronics HD161GJ 160GB       | 1        | 1      | 2.44%   |
| Patriot P210 1TB SSD                    | 1        | 1      | 2.44%   |
| Neo Forza NFS121SA312-6007000 120GB SSD | 1        | 2      | 2.44%   |
| Maxtor 6L160M0 160GB                    | 1        | 2      | 2.44%   |
| Kingston SUV400S37240G 240GB SSD        | 1        | 1      | 2.44%   |
| Intel SSDSC2KW240H6 240GB               | 1        | 1      | 2.44%   |
| Intel SSDSC2BF180A5L 180GB              | 1        | 1      | 2.44%   |
| Hitachi HDT721010SLA360 1TB             | 1        | 1      | 2.44%   |
| Hitachi HDS721010CLA332 1TB             | 1        | 1      | 2.44%   |
| Gigabyte Technology GP-GM30512G-G 512GB | 1        | 1      | 2.44%   |
| Crucial CT512MX100SSD1 512GB            | 1        | 1      | 2.44%   |
| Crucial CT240M500SSD1 240GB             | 1        | 1      | 2.44%   |
| Crucial CT1050MX300SSD1 1050GB          | 1        | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 15     | 34.15%  |
| Seagate             | 6        | 6      | 14.63%  |
| Samsung Electronics | 3        | 3      | 7.32%   |
| Kingston            | 3        | 3      | 7.32%   |
| Crucial             | 3        | 3      | 7.32%   |
| Toshiba             | 2        | 2      | 4.88%   |
| SanDisk             | 2        | 2      | 4.88%   |
| Intel               | 2        | 2      | 4.88%   |
| Hitachi             | 2        | 2      | 4.88%   |
| Patriot             | 1        | 1      | 2.44%   |
| Neo                 | 1        | 2      | 2.44%   |
| Maxtor              | 1        | 2      | 2.44%   |
| Gigabyte Technology | 1        | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 15     | 51.85%  |
| Seagate             | 6        | 6      | 22.22%  |
| Toshiba             | 2        | 2      | 7.41%   |
| Samsung Electronics | 2        | 2      | 7.41%   |
| Hitachi             | 2        | 2      | 7.41%   |
| Maxtor              | 1        | 2      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 26       | 29     | 65%     |
| SSD  | 12       | 13     | 30%     |
| NVMe | 2        | 2      | 5%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Toshiba NVMe SSD Drive 256GB | 1        | 1      | 50%     |
| Hitachi HUS724040ALE640 4TB  | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 50%     |
| Hitachi | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 393      | 1002   | 67.41%  |
| Works    | 152      | 377    | 26.07%  |
| Malfunc  | 36       | 44     | 6.17%   |
| Failed   | 2        | 2      | 0.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 353      | 42.38%  |
| AMD                          | 168      | 20.17%  |
| Samsung Electronics          | 86       | 10.32%  |
| SanDisk                      | 29       | 3.48%   |
| Phison Electronics           | 25       | 3%      |
| Micron/Crucial Technology    | 25       | 3%      |
| Kingston Technology Company  | 25       | 3%      |
| ASMedia Technology           | 24       | 2.88%   |
| Marvell Technology Group     | 12       | 1.44%   |
| JMicron Technology           | 11       | 1.32%   |
| SK hynix                     | 10       | 1.2%    |
| Silicon Motion               | 8        | 0.96%   |
| MAXIO Technology (Hangzhou)  | 8        | 0.96%   |
| Seagate Technology           | 7        | 0.84%   |
| Toshiba America Info Systems | 5        | 0.6%    |
| Realtek Semiconductor        | 5        | 0.6%    |
| Micron Technology            | 5        | 0.6%    |
| Nvidia                       | 4        | 0.48%   |
| KIOXIA                       | 4        | 0.48%   |
| Netac Technology             | 3        | 0.36%   |
| LSI Logic / Symbios Logic    | 3        | 0.36%   |
| Broadcom / LSI               | 3        | 0.36%   |
| Shenzhen Longsys Electronics | 2        | 0.24%   |
| ADATA Technology             | 2        | 0.24%   |
| Yangtze Memory Technologies  | 1        | 0.12%   |
| VIA Technologies             | 1        | 0.12%   |
| OCZ Technology Group         | 1        | 0.12%   |
| INNOGRIT                     | 1        | 0.12%   |
| Biwin Storage Technology     | 1        | 0.12%   |
| Apple                        | 1        | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 70       | 7.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 44       | 4.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 37       | 3.74%   |
| AMD 500 Series Chipset SATA Controller                                                  | 31       | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 30       | 3.03%   |
| AMD 600 Series Chipset SATA Controller                                                  | 30       | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 28       | 2.83%   |
| AMD 400 Series Chipset SATA Controller                                                  | 28       | 2.83%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 25       | 2.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 24       | 2.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 23       | 2.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 22       | 2.22%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 22       | 2.22%   |
| Intel SATA Controller [RAID Mode]                                                       | 21       | 2.12%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 19       | 1.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 19       | 1.92%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 17       | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16       | 1.62%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 15       | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 14       | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 14       | 1.42%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 12       | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12       | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12       | 1.21%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 11       | 1.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 11       | 1.11%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 11       | 1.11%   |
| AMD FCH SATA Controller D                                                               | 11       | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10       | 1.01%   |
| Phison E12 NVMe Controller                                                              | 10       | 1.01%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 10       | 1.01%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 10       | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 1.01%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                                      | 9        | 0.91%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 7        | 0.71%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 6        | 0.61%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 6        | 0.61%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                   | 6        | 0.61%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 0.61%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 456      | 56.58%  |
| NVMe | 223      | 27.67%  |
| IDE  | 75       | 9.31%   |
| RAID | 47       | 5.83%   |
| SAS  | 4        | 0.5%    |
| SCSI | 1        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 356      | 67.04%  |
| AMD    | 175      | 32.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 11       | 2.06%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 10       | 1.88%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 9        | 1.69%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 7        | 1.31%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7        | 1.31%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 7        | 1.31%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 7        | 1.31%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 7        | 1.31%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 1.13%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 6        | 1.13%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 6        | 1.13%   |
| Intel 12th Gen Core i7-12700                | 6        | 1.13%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 6        | 1.13%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 6        | 1.13%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 6        | 1.13%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 5        | 0.94%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 5        | 0.94%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 5        | 0.94%   |
| Intel 13th Gen Core i9-13900K               | 5        | 0.94%   |
| AMD Ryzen 9 7900 12-Core Processor          | 5        | 0.94%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 0.94%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 0.94%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 0.94%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 4        | 0.75%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 4        | 0.75%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 4        | 0.75%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 4        | 0.75%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 4        | 0.75%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 0.75%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 0.75%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz     | 4        | 0.75%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 0.75%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 0.75%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 0.75%   |
| AMD Ryzen 5 5500                            | 4        | 0.75%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 3        | 0.56%   |
| Intel N100                                  | 3        | 0.56%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.56%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 0.56%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 3        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 115      | 21.62%  |
| Intel Core i7           | 69       | 12.97%  |
| Other                   | 54       | 10.15%  |
| AMD Ryzen 5             | 47       | 8.83%   |
| AMD Ryzen 7             | 36       | 6.77%   |
| Intel Xeon              | 33       | 6.2%    |
| Intel Core i3           | 33       | 6.2%    |
| AMD Ryzen 9             | 33       | 6.2%    |
| Intel Celeron           | 13       | 2.44%   |
| Intel Core 2 Duo        | 12       | 2.26%   |
| Intel Pentium           | 8        | 1.5%    |
| AMD FX                  | 7        | 1.32%   |
| Intel Pentium Dual-Core | 6        | 1.13%   |
| AMD Ryzen 3             | 6        | 1.13%   |
| AMD A8                  | 6        | 1.13%   |
| Intel Core 2 Quad       | 5        | 0.94%   |
| AMD Athlon II X2        | 5        | 0.94%   |
| AMD Phenom II X4        | 4        | 0.75%   |
| AMD Athlon X4           | 4        | 0.75%   |
| AMD A10                 | 4        | 0.75%   |
| Intel Core i9           | 3        | 0.56%   |
| Intel Atom              | 3        | 0.56%   |
| AMD Ryzen Threadripper  | 3        | 0.56%   |
| AMD Ryzen 5 PRO         | 3        | 0.56%   |
| AMD Phenom II X6        | 2        | 0.38%   |
| AMD Phenom II X2        | 2        | 0.38%   |
| AMD Athlon 64 X2        | 2        | 0.38%   |
| Intel Pentium Silver    | 1        | 0.19%   |
| Intel Pentium 4         | 1        | 0.19%   |
| Intel Core 2            | 1        | 0.19%   |
| Intel Celeron D         | 1        | 0.19%   |
| AMD Ryzen 7 PRO         | 1        | 0.19%   |
| AMD Ryzen 3 PRO         | 1        | 0.19%   |
| AMD Phenom              | 1        | 0.19%   |
| AMD E                   | 1        | 0.19%   |
| AMD Athlon II X4        | 1        | 0.19%   |
| AMD Athlon II X3        | 1        | 0.19%   |
| AMD Athlon Dual Core    | 1        | 0.19%   |
| AMD Athlon              | 1        | 0.19%   |
| AMD A6                  | 1        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 196      | 36.91%  |
| 6      | 100      | 18.83%  |
| 2      | 92       | 17.33%  |
| 8      | 53       | 9.98%   |
| 12     | 39       | 7.34%   |
| 16     | 13       | 2.45%   |
| 24     | 8        | 1.51%   |
| 14     | 6        | 1.13%   |
| 10     | 6        | 1.13%   |
| 3      | 5        | 0.94%   |
| 1      | 5        | 0.94%   |
| 32     | 3        | 0.56%   |
| 20     | 2        | 0.38%   |
| 36     | 1        | 0.19%   |
| 18     | 1        | 0.19%   |
| 7      | 1        | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 520      | 97.93%  |
| 2      | 11       | 2.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 320      | 60.15%  |
| 1      | 212      | 39.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 531      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 459      | 86.12%  |
| 0x0a601203 | 21       | 3.94%   |
| 0x0a50000d | 9        | 1.69%   |
| 0x0a20120a | 5        | 0.94%   |
| 0x08701021 | 5        | 0.94%   |
| 0x0800820d | 4        | 0.75%   |
| 0x010000c8 | 4        | 0.75%   |
| 0x0a50000b | 2        | 0.38%   |
| 0x0a201025 | 2        | 0.38%   |
| 0x08701030 | 2        | 0.38%   |
| 0x08108109 | 2        | 0.38%   |
| 0xf64      | 1        | 0.19%   |
| 0x306c3    | 1        | 0.19%   |
| 0x0a704103 | 1        | 0.19%   |
| 0x0a50000c | 1        | 0.19%   |
| 0x0a404102 | 1        | 0.19%   |
| 0x0a201205 | 1        | 0.19%   |
| 0x0a201009 | 1        | 0.19%   |
| 0x08600109 | 1        | 0.19%   |
| 0x08101016 | 1        | 0.19%   |
| 0x0810100b | 1        | 0.19%   |
| 0x06006705 | 1        | 0.19%   |
| 0x06003104 | 1        | 0.19%   |
| 0x06001119 | 1        | 0.19%   |
| 0x06000852 | 1        | 0.19%   |
| 0x0600063e | 1        | 0.19%   |
| 0x03000027 | 1        | 0.19%   |
| 0x010000dc | 1        | 0.19%   |
| 0x00000000 | 1        | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 74       | 13.86%  |
| Unknown          | 72       | 13.48%  |
| KabyLake         | 47       | 8.8%    |
| IvyBridge        | 42       | 7.87%   |
| Zen 3            | 41       | 7.68%   |
| Skylake          | 36       | 6.74%   |
| SandyBridge      | 33       | 6.18%   |
| Zen 2            | 30       | 5.62%   |
| Penryn           | 22       | 4.12%   |
| Zen+             | 18       | 3.37%   |
| Piledriver       | 16       | 3%      |
| K10              | 16       | 3%      |
| Alderlake Hybrid | 14       | 2.62%   |
| Zen              | 9        | 1.69%   |
| CometLake        | 9        | 1.69%   |
| Nehalem          | 8        | 1.5%    |
| Silvermont       | 7        | 1.31%   |
| Westmere         | 6        | 1.12%   |
| Broadwell        | 6        | 1.12%   |
| Core             | 5        | 0.94%   |
| K8 Hammer        | 3        | 0.56%   |
| Icelake          | 3        | 0.56%   |
| Excavator        | 3        | 0.56%   |
| Steamroller      | 2        | 0.37%   |
| NetBurst         | 2        | 0.37%   |
| Gracemont        | 2        | 0.37%   |
| Goldmont         | 2        | 0.37%   |
| Bulldozer        | 2        | 0.37%   |
| TigerLake        | 1        | 0.19%   |
| K10 Llano        | 1        | 0.19%   |
| Bonnell          | 1        | 0.19%   |
| Bobcat           | 1        | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 207      | 35.51%  |
| Intel                      | 194      | 33.28%  |
| AMD                        | 178      | 30.53%  |
| Matrox Electronics Systems | 3        | 0.51%   |
| ASPEED Technology          | 1        | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 40       | 6.7%    |
| AMD Raphael                                                                 | 27       | 4.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 23       | 3.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 22       | 3.69%   |
| Intel HD Graphics 530                                                       | 21       | 3.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 19       | 3.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 16       | 2.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 13       | 2.18%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 12       | 2.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 12       | 2.01%   |
| Nvidia GK208B [GeForce GT 710]                                              | 9        | 1.51%   |
| Intel HD Graphics 630                                                       | 9        | 1.51%   |
| Nvidia GK208B [GeForce GT 730]                                              | 7        | 1.17%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 7        | 1.17%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 7        | 1.17%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 7        | 1.17%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 1.01%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 6        | 1.01%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 1.01%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 6        | 1.01%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 6        | 1.01%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 6        | 1.01%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 1.01%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 1.01%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6        | 1.01%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 5        | 0.84%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 0.84%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 5        | 0.84%   |
| Intel AlderLake-S GT1                                                       | 5        | 0.84%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 4        | 0.67%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 0.67%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 0.67%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 4        | 0.67%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 4        | 0.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 0.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 0.67%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 4        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x Nvidia          | 165      | 30.9%   |
| 1 x Intel           | 162      | 30.34%  |
| 1 x AMD             | 149      | 27.9%   |
| AMD + Nvidia        | 19       | 3.56%   |
| Intel + Nvidia      | 17       | 3.18%   |
| 2 x AMD             | 8        | 1.5%    |
| 1 x Matrox          | 3        | 0.56%   |
| Intel + 2 x Nvidia  | 3        | 0.56%   |
| Intel + AMD         | 3        | 0.56%   |
| 2 x Nvidia          | 2        | 0.37%   |
| 2 x Intel + 1 x AMD | 1        | 0.19%   |
| 2 x Intel           | 1        | 0.19%   |
| 1 x ASPEED          | 1        | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 377      | 70.07%  |
| Proprietary | 142      | 26.39%  |
| Unknown     | 19       | 3.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 395      | 73.56%  |
| 1.01-2.0   | 28       | 5.21%   |
| 0.01-0.5   | 28       | 5.21%   |
| 7.01-8.0   | 26       | 4.84%   |
| 3.01-4.0   | 25       | 4.66%   |
| 0.51-1.0   | 16       | 2.98%   |
| 16.01-24.0 | 7        | 1.3%    |
| 8.01-16.0  | 7        | 1.3%    |
| 5.01-6.0   | 5        | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 84       | 15.11%  |
| Goldstar             | 69       | 12.41%  |
| Dell                 | 61       | 10.97%  |
| Acer                 | 40       | 7.19%   |
| Hewlett-Packard      | 35       | 6.29%   |
| AOC                  | 30       | 5.4%    |
| Ancor Communications | 26       | 4.68%   |
| Philips              | 25       | 4.5%    |
| Iiyama               | 20       | 3.6%    |
| BenQ                 | 20       | 3.6%    |
| ViewSonic            | 12       | 2.16%   |
| ASUSTek Computer     | 12       | 2.16%   |
| Lenovo               | 9        | 1.62%   |
| MSI                  | 8        | 1.44%   |
| Sony                 | 6        | 1.08%   |
| HKC                  | 5        | 0.9%    |
| Medion               | 4        | 0.72%   |
| Fujitsu Siemens      | 4        | 0.72%   |
| Eizo                 | 4        | 0.72%   |
| Unknown              | 4        | 0.72%   |
| Vestel Elektronik    | 3        | 0.54%   |
| Unknown              | 3        | 0.54%   |
| NEC Computers        | 3        | 0.54%   |
| MiTAC                | 3        | 0.54%   |
| Gigabyte Technology  | 3        | 0.54%   |
| Wacom                | 2        | 0.36%   |
| Vizio                | 2        | 0.36%   |
| Unknown (XXX)        | 2        | 0.36%   |
| TCL                  | 2        | 0.36%   |
| SGT                  | 2        | 0.36%   |
| Sceptre Tech         | 2        | 0.36%   |
| Hitachi              | 2        | 0.36%   |
| Gericom              | 2        | 0.36%   |
| CVT                  | 2        | 0.36%   |
| ___                  | 1        | 0.18%   |
| Yashi                | 1        | 0.18%   |
| Xiaomi               | 1        | 0.18%   |
| Westinghouse         | 1        | 0.18%   |
| VIE                  | 1        | 0.18%   |
| Unknown (AAA)        | 1        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 7        | 1.21%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6        | 1.04%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 0.69%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 4        | 0.69%   |
| Unknown                                                               | 4        | 0.69%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 3        | 0.52%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 0.52%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 3        | 0.52%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 3        | 0.52%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                    | 3        | 0.52%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 3        | 0.52%   |
| Ancor Communications ASUS PB278 ACI27A3 1920x1080 597x336mm 27.0-inch | 3        | 0.52%   |
| Acer XB273U ACR074A 2560x1440 597x336mm 27.0-inch                     | 3        | 0.52%   |
| Wacom Cintiq 13HD WAC1040 1920x1080 293x165mm 13.2-inch               | 2        | 0.35%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 2        | 0.35%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 2        | 0.35%   |
| Sony TV SNY3002 1920x1080 531x299mm 24.0-inch                         | 2        | 0.35%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2        | 0.35%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 2        | 0.35%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 950x540mm 43.0-inch | 2        | 0.35%   |
| Samsung Electronics LCD Monitor SAM0D47 1920x1080 885x498mm 40.0-inch | 2        | 0.35%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 2        | 0.35%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2        | 0.35%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 2        | 0.35%   |
| Philips 247E4 PHLC0C0 1920x1080 521x293mm 23.5-inch                   | 2        | 0.35%   |
| MSI MAG241C MSI3EA2 1920x1080 521x293mm 23.5-inch                     | 2        | 0.35%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 2        | 0.35%   |
| HKC '' HKC2160 1920x1080 360x270mm 17.7-inch                          | 2        | 0.35%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 2        | 0.35%   |
| Goldstar W2361 GSM56FB 1920x1080 510x290mm 23.1-inch                  | 2        | 0.35%   |
| Goldstar ULTRAGEAR GSM5BB2 1920x1080 527x296mm 23.8-inch              | 2        | 0.35%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 2        | 0.35%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2        | 0.35%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2        | 0.35%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                      | 2        | 0.35%   |
| Dell SE2422H DEL424A 1920x1080 527x296mm 23.8-inch                    | 2        | 0.35%   |
| Dell SE178WFP DELD017 1440x900 370x230mm 17.2-inch                    | 2        | 0.35%   |
| CVT CVTE TV CVT0003 1360x768 575x323mm 26.0-inch                      | 2        | 0.35%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 2        | 0.35%   |
| BenQ GW2255 BNQ78CD 1920x1080 477x268mm 21.5-inch                     | 2        | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 263      | 49.72%  |
| 3840x2160 (4K)     | 76       | 14.37%  |
| 2560x1440 (QHD)    | 56       | 10.59%  |
| 1366x768 (WXGA)    | 20       | 3.78%   |
| 1440x900 (WXGA+)   | 18       | 3.4%    |
| 1680x1050 (WSXGA+) | 13       | 2.46%   |
| 1280x1024 (SXGA)   | 12       | 2.27%   |
| 3440x1440          | 11       | 2.08%   |
| 1920x1200 (WUXGA)  | 10       | 1.89%   |
| 2560x1080          | 8        | 1.51%   |
| 1600x900 (HD+)     | 8        | 1.51%   |
| 3840x1080          | 6        | 1.13%   |
| Unknown            | 5        | 0.95%   |
| 1280x720 (HD)      | 4        | 0.76%   |
| 3840x1600          | 3        | 0.57%   |
| 2560x1600          | 3        | 0.57%   |
| 1920x540           | 3        | 0.57%   |
| 1360x768           | 3        | 0.57%   |
| 1024x768 (XGA)     | 2        | 0.38%   |
| 5760x2160          | 1        | 0.19%   |
| 3600x1080          | 1        | 0.19%   |
| 1600x1200          | 1        | 0.19%   |
| 1280x960           | 1        | 0.19%   |
| 1024x600           | 1        | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 94       | 17.22%  |
| 24      | 82       | 15.02%  |
| 23      | 72       | 13.19%  |
| 21      | 60       | 10.99%  |
| 31      | 37       | 6.78%   |
| 19      | 22       | 4.03%   |
| Unknown | 22       | 4.03%   |
| 18      | 19       | 3.48%   |
| 34      | 13       | 2.38%   |
| 84      | 12       | 2.2%    |
| 22      | 12       | 2.2%    |
| 20      | 10       | 1.83%   |
| 17      | 9        | 1.65%   |
| 40      | 7        | 1.28%   |
| 32      | 6        | 1.1%    |
| 65      | 5        | 0.92%   |
| 48      | 5        | 0.92%   |
| 28      | 5        | 0.92%   |
| 26      | 5        | 0.92%   |
| 13      | 5        | 0.92%   |
| 72      | 4        | 0.73%   |
| 35      | 4        | 0.73%   |
| 54      | 3        | 0.55%   |
| 52      | 3        | 0.55%   |
| 46      | 3        | 0.55%   |
| 42      | 3        | 0.55%   |
| 16      | 3        | 0.55%   |
| 49      | 2        | 0.37%   |
| 37      | 2        | 0.37%   |
| 29      | 2        | 0.37%   |
| 25      | 2        | 0.37%   |
| 15      | 2        | 0.37%   |
| 63      | 1        | 0.18%   |
| 61      | 1        | 0.18%   |
| 60      | 1        | 0.18%   |
| 47      | 1        | 0.18%   |
| 43      | 1        | 0.18%   |
| 38      | 1        | 0.18%   |
| 36      | 1        | 0.18%   |
| 33      | 1        | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 230      | 43.31%  |
| 401-500     | 114      | 21.47%  |
| 601-700     | 54       | 10.17%  |
| 1001-1500   | 25       | 4.71%   |
| Unknown     | 22       | 4.14%   |
| 701-800     | 21       | 3.95%   |
| 1501-2000   | 16       | 3.01%   |
| 351-400     | 14       | 2.64%   |
| 801-900     | 13       | 2.45%   |
| 301-350     | 9        | 1.69%   |
| 201-300     | 7        | 1.32%   |
| 901-1000    | 5        | 0.94%   |
| 101-200     | 1        | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 380      | 75.25%  |
| 16/10   | 55       | 10.89%  |
| 21/9    | 21       | 4.16%   |
| Unknown | 19       | 3.76%   |
| 5/4     | 15       | 2.97%   |
| 32/9    | 8        | 1.58%   |
| 4/3     | 6        | 1.19%   |
| 3/2     | 1        | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 171      | 31.9%   |
| 301-350        | 97       | 18.1%   |
| 351-500        | 66       | 12.31%  |
| 151-200        | 49       | 9.14%   |
| 251-300        | 39       | 7.28%   |
| More than 1000 | 31       | 5.78%   |
| 501-1000       | 23       | 4.29%   |
| 141-150        | 22       | 4.1%    |
| Unknown        | 22       | 4.1%    |
| 71-80          | 4        | 0.75%   |
| 101-110        | 4        | 0.75%   |
| 131-140        | 3        | 0.56%   |
| 81-90          | 1        | 0.19%   |
| 51-60          | 1        | 0.19%   |
| 41-50          | 1        | 0.19%   |
| 121-130        | 1        | 0.19%   |
| 111-120        | 1        | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 316      | 60.19%  |
| 101-120       | 115      | 21.9%   |
| 121-160       | 29       | 5.52%   |
| 1-50          | 22       | 4.19%   |
| Unknown       | 22       | 4.19%   |
| 161-240       | 20       | 3.81%   |
| More than 240 | 1        | 0.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 413      | 76.91%  |
| 2     | 80       | 14.9%   |
| 0     | 31       | 5.77%   |
| 3     | 12       | 2.23%   |
| 4     | 1        | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 343      | 43.58%  |
| Intel                           | 231      | 29.35%  |
| MediaTek                        | 33       | 4.19%   |
| Qualcomm Atheros                | 32       | 4.07%   |
| Broadcom                        | 27       | 3.43%   |
| TP-Link                         | 21       | 2.67%   |
| Ralink Technology               | 14       | 1.78%   |
| Microsoft                       | 8        | 1.02%   |
| NetGear                         | 7        | 0.89%   |
| Marvell Technology Group        | 6        | 0.76%   |
| D-Link                          | 6        | 0.76%   |
| Aquantia                        | 6        | 0.76%   |
| Ralink                          | 4        | 0.51%   |
| Qualcomm Atheros Communications | 4        | 0.51%   |
| Xiaomi                          | 3        | 0.38%   |
| Nvidia                          | 3        | 0.38%   |
| Mellanox Technologies           | 3        | 0.38%   |
| Edimax Technology               | 3        | 0.38%   |
| D-Link System                   | 3        | 0.38%   |
| Samsung Electronics             | 2        | 0.25%   |
| Huawei Technologies             | 2        | 0.25%   |
| Google                          | 2        | 0.25%   |
| Dresden Elektronik              | 2        | 0.25%   |
| Broadcom Limited                | 2        | 0.25%   |
| AVM                             | 2        | 0.25%   |
| ASUSTek Computer                | 2        | 0.25%   |
| Apple                           | 2        | 0.25%   |
| ZyXEL Communications            | 1        | 0.13%   |
| ZyDAS                           | 1        | 0.13%   |
| Z-Com                           | 1        | 0.13%   |
| Qualcomm                        | 1        | 0.13%   |
| QinHeng Electronics             | 1        | 0.13%   |
| Philips (or NXP)                | 1        | 0.13%   |
| Motorola PCS                    | 1        | 0.13%   |
| Linksys                         | 1        | 0.13%   |
| Lenovo                          | 1        | 0.13%   |
| IMC Networks                    | 1        | 0.13%   |
| Guillemot                       | 1        | 0.13%   |
| DisplayLink                     | 1        | 0.13%   |
| ASIX Electronics                | 1        | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 252      | 28.31%  |
| Realtek RTL8125 2.5GbE Controller                                              | 48       | 5.39%   |
| Intel Ethernet Controller I225-V                                               | 27       | 3.03%   |
| Intel Wi-Fi 6 AX200                                                            | 23       | 2.58%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 20       | 2.25%   |
| Intel I211 Gigabit Network Connection                                          | 18       | 2.02%   |
| Intel Ethernet Connection I217-LM                                              | 18       | 2.02%   |
| Intel Ethernet Connection (2) I219-V                                           | 17       | 1.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 16       | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15       | 1.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 11       | 1.24%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 11       | 1.24%   |
| Intel 82579V Gigabit Network Connection                                        | 9        | 1.01%   |
| Realtek 802.11ac NIC                                                           | 8        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8        | 0.9%    |
| Intel I210 Gigabit Network Connection                                          | 8        | 0.9%    |
| Intel Ethernet Connection (17) I219-V                                          | 8        | 0.9%    |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 8        | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 7        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                           | 7        | 0.79%   |
| Intel Ethernet Connection (2) I218-V                                           | 7        | 0.79%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                    | 6        | 0.67%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 6        | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 6        | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 6        | 0.67%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                              | 6        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6        | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                                          | 6        | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 6        | 0.67%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 5        | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 5        | 0.56%   |
| Microsoft Xbox 360 Wireless Adapter                                            | 5        | 0.56%   |
| Intel Wireless 7260                                                            | 5        | 0.56%   |
| Intel Ethernet Connection I217-V                                               | 5        | 0.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 5        | 0.56%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 5        | 0.56%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 5        | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4        | 0.45%   |
| Ralink MT7601U Wireless Adapter                                                | 4        | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 4        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 91       | 30.43%  |
| Realtek Semiconductor           | 65       | 21.74%  |
| MediaTek                        | 32       | 10.7%   |
| TP-Link                         | 21       | 7.02%   |
| Broadcom                        | 16       | 5.35%   |
| Ralink Technology               | 14       | 4.68%   |
| Qualcomm Atheros                | 14       | 4.68%   |
| Microsoft                       | 8        | 2.68%   |
| NetGear                         | 7        | 2.34%   |
| D-Link                          | 6        | 2.01%   |
| Ralink                          | 4        | 1.34%   |
| Qualcomm Atheros Communications | 4        | 1.34%   |
| Edimax Technology               | 3        | 1%      |
| Broadcom Limited                | 2        | 0.67%   |
| AVM                             | 2        | 0.67%   |
| ASUSTek Computer                | 2        | 0.67%   |
| ZyXEL Communications            | 1        | 0.33%   |
| ZyDAS                           | 1        | 0.33%   |
| Z-Com                           | 1        | 0.33%   |
| Philips (or NXP)                | 1        | 0.33%   |
| Linksys                         | 1        | 0.33%   |
| IMC Networks                    | 1        | 0.33%   |
| Guillemot                       | 1        | 0.33%   |
| D-Link System                   | 1        | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 23       | 7.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 20       | 6.6%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 16       | 5.28%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 11       | 3.63%   |
| Realtek 802.11ac NIC                                          | 8        | 2.64%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 8        | 2.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 7        | 2.31%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 6        | 1.98%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 6        | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 6        | 1.98%   |
| Intel Raptor Lake-S PCH CNVi WiFi                             | 6        | 1.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 6        | 1.98%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 5        | 1.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 5        | 1.65%   |
| Microsoft Xbox 360 Wireless Adapter                           | 5        | 1.65%   |
| Intel Wireless 7260                                           | 5        | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 5        | 1.65%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 5        | 1.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 4        | 1.32%   |
| Ralink MT7601U Wireless Adapter                               | 4        | 1.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 4        | 1.32%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 4        | 1.32%   |
| D-Link 802.11ac NIC                                           | 4        | 1.32%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter  | 4        | 1.32%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 3        | 0.99%   |
| TP-Link 802.11ac NIC                                          | 3        | 0.99%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 3        | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3        | 0.99%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 3        | 0.99%   |
| Ralink RT5370 Wireless Adapter                                | 3        | 0.99%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter             | 3        | 0.99%   |
| Qualcomm Atheros AR9271 802.11n                               | 3        | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3        | 0.99%   |
| Intel Wireless 7265                                           | 3        | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                | 3        | 0.99%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 2        | 0.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 2        | 0.66%   |
| TP-Link Archer T4U ver.3                                      | 2        | 0.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 2        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 2        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 320      | 56.44%  |
| Intel                    | 181      | 31.92%  |
| Qualcomm Atheros         | 19       | 3.35%   |
| Broadcom                 | 11       | 1.94%   |
| Marvell Technology Group | 6        | 1.06%   |
| Aquantia                 | 6        | 1.06%   |
| Xiaomi                   | 3        | 0.53%   |
| Nvidia                   | 3        | 0.53%   |
| Mellanox Technologies    | 3        | 0.53%   |
| Samsung Electronics      | 2        | 0.35%   |
| Google                   | 2        | 0.35%   |
| D-Link System            | 2        | 0.35%   |
| Qualcomm                 | 1        | 0.18%   |
| Motorola PCS             | 1        | 0.18%   |
| MediaTek                 | 1        | 0.18%   |
| Lenovo                   | 1        | 0.18%   |
| Huawei Technologies      | 1        | 0.18%   |
| DisplayLink              | 1        | 0.18%   |
| ASIX Electronics         | 1        | 0.18%   |
| Apple                    | 1        | 0.18%   |
| 3Com                     | 1        | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 252      | 43.3%   |
| Realtek RTL8125 2.5GbE Controller                                              | 48       | 8.25%   |
| Intel Ethernet Controller I225-V                                               | 27       | 4.64%   |
| Intel I211 Gigabit Network Connection                                          | 18       | 3.09%   |
| Intel Ethernet Connection I217-LM                                              | 18       | 3.09%   |
| Intel Ethernet Connection (2) I219-V                                           | 17       | 2.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15       | 2.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 11       | 1.89%   |
| Intel 82579V Gigabit Network Connection                                        | 9        | 1.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8        | 1.37%   |
| Intel I210 Gigabit Network Connection                                          | 8        | 1.37%   |
| Intel Ethernet Connection (17) I219-V                                          | 8        | 1.37%   |
| Intel Ethernet Connection (7) I219-V                                           | 7        | 1.2%    |
| Intel Ethernet Connection (2) I218-V                                           | 7        | 1.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 6        | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6        | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                                          | 6        | 1.03%   |
| Intel Ethernet Connection I217-V                                               | 5        | 0.86%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 5        | 0.86%   |
| Intel Ethernet Connection (5) I219-LM                                          | 4        | 0.69%   |
| Intel 82574L Gigabit Network Connection                                        | 4        | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 4        | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 0.52%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 3        | 0.52%   |
| Intel Ethernet Controller I226-V                                               | 3        | 0.52%   |
| Intel Ethernet Connection (14) I219-V                                          | 3        | 0.52%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 3        | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2        | 0.34%   |
| Realtek Killer E2600 GbE Controller                                            | 2        | 0.34%   |
| Nvidia MCP61 Ethernet                                                          | 2        | 0.34%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                          | 2        | 0.34%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2        | 0.34%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 2        | 0.34%   |
| Intel Ethernet Controller X550                                                 | 2        | 0.34%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2        | 0.34%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 2        | 0.34%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 2        | 0.34%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2        | 0.34%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 2        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 524      | 64.61%  |
| WiFi     | 282      | 34.77%  |
| Modem    | 5        | 0.62%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 403      | 72.48%  |
| WiFi     | 153      | 27.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 309      | 58.08%  |
| 2     | 180      | 33.83%  |
| 3     | 34       | 6.39%   |
| 0     | 5        | 0.94%   |
| 5     | 2        | 0.38%   |
| 6     | 1        | 0.19%   |
| 4     | 1        | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 343      | 64.11%  |
| Yes  | 192      | 35.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 87       | 36.71%  |
| Cambridge Silicon Radio         | 38       | 16.03%  |
| Realtek Semiconductor           | 29       | 12.24%  |
| MediaTek                        | 19       | 8.02%   |
| IMC Networks                    | 12       | 5.06%   |
| ASUSTek Computer                | 12       | 5.06%   |
| Broadcom                        | 8        | 3.38%   |
| TP-Link                         | 7        | 2.95%   |
| Foxconn / Hon Hai               | 5        | 2.11%   |
| Apple                           | 5        | 2.11%   |
| Qualcomm Atheros Communications | 4        | 1.69%   |
| Realtek                         | 2        | 0.84%   |
| Lite-On Technology              | 2        | 0.84%   |
| Logitech                        | 1        | 0.42%   |
| Integrated System Solution      | 1        | 0.42%   |
| HTC (High Tech Computer)        | 1        | 0.42%   |
| Fujitsu                         | 1        | 0.42%   |
| Edimax Technology               | 1        | 0.42%   |
| Dynex                           | 1        | 0.42%   |
| Belkin Components               | 1        | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 38       | 15.97%  |
| Realtek Bluetooth Radio                                              | 26       | 10.92%  |
| Intel AX200 Bluetooth                                                | 21       | 8.82%   |
| MediaTek Wireless_Device                                             | 19       | 7.98%   |
| Intel AX210 Bluetooth                                                | 16       | 6.72%   |
| Intel Bluetooth wireless interface                                   | 12       | 5.04%   |
| Intel AX201 Bluetooth                                                | 12       | 5.04%   |
| Intel AX211 Bluetooth                                                | 8        | 3.36%   |
| IMC Networks Bluetooth Radio                                         | 8        | 3.36%   |
| TP-Link UB500 Adapter                                                | 7        | 2.94%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 7        | 2.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 6        | 2.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 5        | 2.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 4        | 1.68%   |
| Foxconn / Hon Hai Wireless_Device                                    | 4        | 1.68%   |
| IMC Networks Wireless_Device                                         | 3        | 1.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3        | 1.26%   |
| ASUS ASUS USB-BT500                                                  | 3        | 1.26%   |
| Apple Bluetooth Host Controller                                      | 3        | 1.26%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 0.84%   |
| Realtek Bluetooth Radio                                              | 2        | 0.84%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2        | 0.84%   |
| Intel Bluetooth Device                                               | 2        | 0.84%   |
| ASUS BCM20702A0                                                      | 2        | 0.84%   |
| Realtek RTL8723B Bluetooth                                           | 1        | 0.42%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 1        | 0.42%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 0.42%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 1        | 0.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1        | 0.42%   |
| Lite-On Bluetooth Device                                             | 1        | 0.42%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.42%   |
| IMC Networks BCM20702A0                                              | 1        | 0.42%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.42%   |
| Fujitsu Bluetooth Device                                             | 1        | 0.42%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 1        | 0.42%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 1        | 0.42%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.42%   |
| Broadcom HP Bluethunder                                              | 1        | 0.42%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.42%   |
| Broadcom BCM92046DG-CL1ROM                                           | 1        | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 342      | 37.54%  |
| AMD                                             | 220      | 24.15%  |
| Nvidia                                          | 200      | 21.95%  |
| C-Media Electronics                             | 27       | 2.96%   |
| Logitech                                        | 17       | 1.87%   |
| ASUSTek Computer                                | 15       | 1.65%   |
| Texas Instruments                               | 6        | 0.66%   |
| Micro Star International                        | 6        | 0.66%   |
| Kingston Technology                             | 5        | 0.55%   |
| Razer USA                                       | 4        | 0.44%   |
| GN Netcom                                       | 4        | 0.44%   |
| Creative Labs                                   | 4        | 0.44%   |
| VIA Technologies                                | 3        | 0.33%   |
| Sony                                            | 3        | 0.33%   |
| KORG                                            | 3        | 0.33%   |
| JMTek                                           | 3        | 0.33%   |
| Zoran Co. Personal Media Division (Nogatech)    | 2        | 0.22%   |
| SteelSeries ApS                                 | 2        | 0.22%   |
| Samson Technologies                             | 2        | 0.22%   |
| PreSonus Audio Electronics                      | 2        | 0.22%   |
| Native Instruments                              | 2        | 0.22%   |
| Licensed by Sony Computer Entertainment America | 2        | 0.22%   |
| Lenovo                                          | 2        | 0.22%   |
| Jieli Technology                                | 2        | 0.22%   |
| Giga-Byte Technology                            | 2        | 0.22%   |
| Generalplus Technology                          | 2        | 0.22%   |
| Focusrite-Novation                              | 2        | 0.22%   |
| Creative Technology                             | 2        | 0.22%   |
| BEHRINGER International                         | 2        | 0.22%   |
| Yamaha                                          | 1        | 0.11%   |
| USB-MIC                                         | 1        | 0.11%   |
| USB Audio                                       | 1        | 0.11%   |
| Turtle Beach                                    | 1        | 0.11%   |
| Thesycon Systemsoftware & Consulting            | 1        | 0.11%   |
| Tenx Technology                                 | 1        | 0.11%   |
| ROCCAT                                          | 1        | 0.11%   |
| Realtek Semiconductor                           | 1        | 0.11%   |
| Plantronics                                     | 1        | 0.11%   |
| Nektar                                          | 1        | 0.11%   |
| Microdia                                        | 1        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 60       | 5.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 47       | 4.28%   |
| AMD Starship/Matisse HD Audio Controller                                   | 45       | 4.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 42       | 3.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 41       | 3.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 30       | 2.73%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 30       | 2.73%   |
| Intel 200 Series PCH HD Audio                                              | 28       | 2.55%   |
| Intel Alder Lake-S HD Audio Controller                                     | 25       | 2.28%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 25       | 2.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 25       | 2.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 24       | 2.19%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 23       | 2.1%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 22       | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 21       | 1.91%   |
| Nvidia GP107GL High Definition Audio Controller                            | 18       | 1.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 17       | 1.55%   |
| AMD FCH Azalia Controller                                                  | 16       | 1.46%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16       | 1.46%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 15       | 1.37%   |
| Nvidia GA104 High Definition Audio Controller                              | 14       | 1.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14       | 1.28%   |
| ASUSTek Computer USB Audio                                                 | 14       | 1.28%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 13       | 1.19%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 13       | 1.19%   |
| Nvidia GA106 High Definition Audio Controller                              | 12       | 1.09%   |
| Nvidia TU116 High Definition Audio Controller                              | 11       | 1%      |
| Nvidia GP104 High Definition Audio Controller                              | 11       | 1%      |
| Intel Raptor Lake High Definition Audio Controller                         | 11       | 1%      |
| Nvidia GK107 HDMI Audio Controller                                         | 10       | 0.91%   |
| Nvidia GA102 High Definition Audio Controller                              | 10       | 0.91%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10       | 0.91%   |
| Nvidia GM204 High Definition Audio Controller                              | 9        | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 9        | 0.82%   |
| AMD Trinity HDMI Audio Controller                                          | 9        | 0.82%   |
| Nvidia High Definition Audio Controller                                    | 8        | 0.73%   |
| Nvidia Audio device                                                        | 8        | 0.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 0.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8        | 0.73%   |
| AMD Navi 10 HDMI Audio                                                     | 8        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Kingston                             | 44       | 18.8%   |
| Corsair                              | 31       | 13.25%  |
| Samsung Electronics                  | 24       | 10.26%  |
| G.Skill                              | 22       | 9.4%    |
| Unknown                              | 21       | 8.97%   |
| Crucial                              | 20       | 8.55%   |
| SK hynix                             | 14       | 5.98%   |
| Micron Technology                    | 13       | 5.56%   |
| A-DATA Technology                    | 7        | 2.99%   |
| Team                                 | 5        | 2.14%   |
| Patriot                              | 3        | 1.28%   |
| Unknown                              | 3        | 1.28%   |
| Wodposit                             | 2        | 0.85%   |
| Transcend                            | 2        | 0.85%   |
| Ramaxel Technology                   | 2        | 0.85%   |
| Patriot Memory                       | 2        | 0.85%   |
| Nanya Technology                     | 2        | 0.85%   |
| GOODRAM                              | 2        | 0.85%   |
| Elpida                               | 2        | 0.85%   |
| Unknown (ABCD)                       | 1        | 0.43%   |
| Unknown (AB)                         | 1        | 0.43%   |
| Unknown (0x9801)                     | 1        | 0.43%   |
| Unknown (0x0C26)                     | 1        | 0.43%   |
| Unknown (0B85)                       | 1        | 0.43%   |
| Unifosa                              | 1        | 0.43%   |
| Sesame                               | 1        | 0.43%   |
| Lexar                                | 1        | 0.43%   |
| Juhor                                | 1        | 0.43%   |
| Hewlett-Packard                      | 1        | 0.43%   |
| Chun Well Technology Holding Limited | 1        | 0.43%   |
| Atermiter                            | 1        | 0.43%   |
| ASint Technology                     | 1        | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s     | 4        | 1.62%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s       | 4        | 1.62%   |
| Kingston RAM KF556C40-32 32GB DIMM DDR5 5808MT/s          | 3        | 1.21%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 3        | 1.21%   |
| Unknown                                                   | 3        | 1.21%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 2        | 0.81%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 2        | 0.81%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                 | 2        | 0.81%   |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s                 | 2        | 0.81%   |
| Patriot Memory RAM 3200 C16 Series 8GB DIMM DDR4 3400MT/s | 2        | 0.81%   |
| Kingston RAM KHX2400C11D3/4GX 4GB DIMM DDR3 2400MT/s      | 2        | 0.81%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s       | 2        | 0.81%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 6000MT/s          | 2        | 0.81%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s      | 2        | 0.81%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s      | 2        | 0.81%   |
| G.Skill RAM F4-3600C19-16GVRB 16GB DIMM DDR4 3600MT/s     | 2        | 0.81%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s        | 2        | 0.81%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s       | 2        | 0.81%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s    | 2        | 0.81%   |
| A-DATA RAM Module 16GB DIMM DDR4 3200MT/s                 | 2        | 0.81%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s               | 2        | 0.81%   |
| Wodposit RAM WPBH32D408SWM-16G 16GB SODIMM DDR4 3200MT/s  | 1        | 0.4%    |
| Wodposit RAM WPBH26D416SXA-8G 8GB SODIMM DDR4 2667MT/s    | 1        | 0.4%    |
| Unknown RAM Module 8GB DIMM SDRAM                         | 1        | 0.4%    |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                 | 1        | 0.4%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                      | 1        | 0.4%    |
| Unknown RAM Module 8GB DIMM                               | 1        | 0.4%    |
| Unknown RAM Module 4GB DIMM SDRAM                         | 1        | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 0.4%    |
| Unknown RAM Module 4GB DIMM 400MT/s                       | 1        | 0.4%    |
| Unknown RAM Module 32GB DIMM DDR4 2400MT/s                | 1        | 0.4%    |
| Unknown RAM Module 2GB DIMM SDRAM 667MT/s                 | 1        | 0.4%    |
| Unknown RAM Module 2GB DIMM DDR2                          | 1        | 0.4%    |
| Unknown RAM Module 2GB DIMM DDR 533MT/s                   | 1        | 0.4%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 0.4%    |
| Unknown RAM Module 1GB DIMM SDRAM 800MT/s                 | 1        | 0.4%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                  | 1        | 0.4%    |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                  | 1        | 0.4%    |
| Unknown RAM Module 1GB DIMM                               | 1        | 0.4%    |
| Unknown RAM DDR4 16GB 2666MHz 16GB SODIMM DDR4 2667MT/s   | 1        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 101      | 47.42%  |
| DDR3    | 52       | 24.41%  |
| DDR5    | 32       | 15.02%  |
| SDRAM   | 12       | 5.63%   |
| Unknown | 6        | 2.82%   |
| DDR2    | 3        | 1.41%   |
| DRAM    | 2        | 0.94%   |
| DDR     | 2        | 0.94%   |
| LPDDR5  | 1        | 0.47%   |
| LPDDR4  | 1        | 0.47%   |
| LPDDR3  | 1        | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 189      | 90.87%  |
| SODIMM       | 18       | 8.65%   |
| Row Of Chips | 1        | 0.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 81       | 36.16%  |
| 16384 | 52       | 23.21%  |
| 32768 | 34       | 15.18%  |
| 4096  | 34       | 15.18%  |
| 2048  | 15       | 6.7%    |
| 1024  | 6        | 2.68%   |
| 49152 | 1        | 0.45%   |
| 512   | 1        | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 34       | 15.11%  |
| 3200    | 27       | 12%     |
| 2400    | 20       | 8.89%   |
| 3600    | 18       | 8%      |
| 1333    | 12       | 5.33%   |
| 2667    | 9        | 4%      |
| 2133    | 9        | 4%      |
| 6000    | 8        | 3.56%   |
| 4800    | 8        | 3.56%   |
| Unknown | 6        | 2.67%   |
| 1867    | 5        | 2.22%   |
| 6400    | 4        | 1.78%   |
| 5600    | 4        | 1.78%   |
| 5200    | 4        | 1.78%   |
| 3866    | 4        | 1.78%   |
| 3800    | 4        | 1.78%   |
| 3733    | 4        | 1.78%   |
| 800     | 4        | 1.78%   |
| 5808    | 3        | 1.33%   |
| 3400    | 3        | 1.33%   |
| 2666    | 3        | 1.33%   |
| 3666    | 2        | 0.89%   |
| 3466    | 2        | 0.89%   |
| 2933    | 2        | 0.89%   |
| 2048    | 2        | 0.89%   |
| 1866    | 2        | 0.89%   |
| 1800    | 2        | 0.89%   |
| 667     | 2        | 0.89%   |
| 400     | 2        | 0.89%   |
| 6800    | 1        | 0.44%   |
| 5800    | 1        | 0.44%   |
| 4199    | 1        | 0.44%   |
| 4000    | 1        | 0.44%   |
| 3933    | 1        | 0.44%   |
| 3534    | 1        | 0.44%   |
| 3334    | 1        | 0.44%   |
| 3266    | 1        | 0.44%   |
| 3066    | 1        | 0.44%   |
| 2800    | 1        | 0.44%   |
| 2176    | 1        | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Brother Industries    | 8        | 26.67%  |
| Seiko Epson           | 6        | 20%     |
| Hewlett-Packard       | 5        | 16.67%  |
| Samsung Electronics   | 4        | 13.33%  |
| Canon                 | 3        | 10%     |
| QinHeng Electronics   | 1        | 3.33%   |
| Pantum                | 1        | 3.33%   |
| Lexmark International | 1        | 3.33%   |
| Dymo-CoStar           | 1        | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson XP-2200 Series                   | 1        | 3.33%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 3.33%   |
| Seiko Epson L6160 Series                     | 1        | 3.33%   |
| Seiko Epson L3250 Series                     | 1        | 3.33%   |
| Seiko Epson ET-8550 Series                   | 1        | 3.33%   |
| Seiko Epson ET-2820 Series                   | 1        | 3.33%   |
| Samsung SCX-4623 Series                      | 1        | 3.33%   |
| Samsung SCX-3400 Series                      | 1        | 3.33%   |
| Samsung M2020 Series                         | 1        | 3.33%   |
| Samsung CLX-3170 Series                      | 1        | 3.33%   |
| QinHeng CH340S                               | 1        | 3.33%   |
| Pantum P2200 series                          | 1        | 3.33%   |
| Lexmark International MC3326adwe             | 1        | 3.33%   |
| HP OfficeJet 5200 series                     | 1        | 3.33%   |
| HP LaserJet P2055 series                     | 1        | 3.33%   |
| HP DeskJet 960c                              | 1        | 3.33%   |
| HP ColorLaserJet M253-M254                   | 1        | 3.33%   |
| HP Color LaserJet Pro M453-4                 | 1        | 3.33%   |
| Dymo-CoStar DYMO LabelWriter 4XL             | 1        | 3.33%   |
| Canon TR4500 series                          | 1        | 3.33%   |
| Canon iP90                                   | 1        | 3.33%   |
| Canon iP7200 series                          | 1        | 3.33%   |
| Brother MFC-J6530DW                          | 1        | 3.33%   |
| Brother MFC-J1010DW                          | 1        | 3.33%   |
| Brother MFC-9330CDW                          | 1        | 3.33%   |
| Brother HL-L5000D series                     | 1        | 3.33%   |
| Brother HL-52x0 series                       | 1        | 3.33%   |
| Brother HL-2030 Laser Printer                | 1        | 3.33%   |
| Brother DCP-7055W                            | 1        | 3.33%   |
| Brother DCP-1610W                            | 1        | 3.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Canon   | 3        | 75%     |
| Plustek | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan LiDE 100            | 2        | 50%     |
| Plustek 600dpi USB Scanner         | 1        | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                              | Desktops | Percent |
|-------------------------------------|----------|---------|
| Logitech                            | 36       | 37.89%  |
| Sunplus Innovation Technology       | 6        | 6.32%   |
| Microsoft                           | 6        | 6.32%   |
| Apple                               | 5        | 5.26%   |
| Samsung Electronics                 | 4        | 4.21%   |
| Microdia                            | 4        | 4.21%   |
| Z-Star Microelectronics             | 3        | 3.16%   |
| Razer USA                           | 3        | 3.16%   |
| Generalplus Technology              | 3        | 3.16%   |
| ARC International                   | 3        | 3.16%   |
| Trust                               | 2        | 2.11%   |
| YT-221117-J                         | 1        | 1.05%   |
| WCM_USB                             | 1        | 1.05%   |
| WaveRider Communications            | 1        | 1.05%   |
| Sunplus IT                          | 1        | 1.05%   |
| Sonix Technology                    | 1        | 1.05%   |
| Pixart Imaging                      | 1        | 1.05%   |
| MacroSilicon                        | 1        | 1.05%   |
| Lite-On Technology                  | 1        | 1.05%   |
| KYE Systems (Mouse Systems)         | 1        | 1.05%   |
| Hewlett-Packard                     | 1        | 1.05%   |
| Hauppauge                           | 1        | 1.05%   |
| Genesys Logic                       | 1        | 1.05%   |
| Fuzhou Rockchip Electronics Company | 1        | 1.05%   |
| eMeet                               | 1        | 1.05%   |
| Chicony Electronics                 | 1        | 1.05%   |
| AVerMedia Technologies              | 1        | 1.05%   |
| Arkmicro Technologies               | 1        | 1.05%   |
| Anchor Chips                        | 1        | 1.05%   |
| 2M UVC CAMERA                       | 1        | 1.05%   |
| Unknown                             | 1        | 1.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 11       | 11.46%  |
| Samsung Galaxy series, misc. (MTP mode) | 4        | 4.17%   |
| Logitech HD Pro Webcam C920             | 4        | 4.17%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 4        | 4.17%   |
| Microsoft LifeCam HD-3000               | 3        | 3.13%   |
| Logitech BRIO Ultra HD Webcam           | 3        | 3.13%   |
| Sunplus PC Camera                       | 2        | 2.08%   |
| Sunplus Full HD webcam                  | 2        | 2.08%   |
| Razer USA Gaming Webcam [Kiyo]          | 2        | 2.08%   |
| Logitech HD Webcam C510                 | 2        | 2.08%   |
| Generalplus CAMERA - UVC                | 2        | 2.08%   |
| ARC International Camera                | 2        | 2.08%   |
| Z-Star Vimicro USB Camera (Altair)      | 1        | 1.04%   |
| Z-Star USB 2.0 Web Camera               | 1        | 1.04%   |
| Z-Star Lenovo USB 2.0 UVC Camera        | 1        | 1.04%   |
| YT-221117-J USB2.0 Camera               | 1        | 1.04%   |
| WCM_USB WEB CAM                         | 1        | 1.04%   |
| WaveRider USB 2.0 Camera                | 1        | 1.04%   |
| Trust Widescreen 3MP Webcam             | 1        | 1.04%   |
| Trust USB Camera                        | 1        | 1.04%   |
| Sunplus IT 1080P Webcam                 | 1        | 1.04%   |
| Sunplus ZET USB WEBCAM                  | 1        | 1.04%   |
| Sunplus iContact Camera                 | 1        | 1.04%   |
| Sonix FHD Webcam                        | 1        | 1.04%   |
| Razer USA Razer Kiyo Pro                | 1        | 1.04%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro    | 1        | 1.04%   |
| Microsoft MicrosoftÂ LifeCam Studio    | 1        | 1.04%   |
| Microsoft LifeCam NX-6000               | 1        | 1.04%   |
| Microsoft LifeCam HD-5000               | 1        | 1.04%   |
| Microdia Sonix USB 2.0 Camera           | 1        | 1.04%   |
| Microdia Laptop_Integrated_Webcam_HD    | 1        | 1.04%   |
| Microdia HP Integrated Webcam           | 1        | 1.04%   |
| Microdia Camera                         | 1        | 1.04%   |
| MacroSilicon MiraBox Capture            | 1        | 1.04%   |
| Logitech Webcam Pro 9000                | 1        | 1.04%   |
| Logitech Webcam C930e                   | 1        | 1.04%   |
| Logitech Webcam C300                    | 1        | 1.04%   |
| Logitech Webcam C250                    | 1        | 1.04%   |
| Logitech Webcam C210                    | 1        | 1.04%   |
| Logitech Webcam C200                    | 1        | 1.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 50%     |
| Alcor Micro           | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1        | 50%     |
| Alcor Micro Watchdata W 1981                      | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 459      | 85.63%  |
| 1     | 63       | 11.75%  |
| 2     | 11       | 2.05%   |
| 6     | 1        | 0.19%   |
| 5     | 1        | 0.19%   |
| 3     | 1        | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 30       | 34.48%  |
| Unassigned class         | 16       | 18.39%  |
| Communication controller | 14       | 16.09%  |
| Net/wireless             | 12       | 13.79%  |
| Sound                    | 5        | 5.75%   |
| Camera                   | 3        | 3.45%   |
| Bluetooth                | 3        | 3.45%   |
| Multimedia controller    | 2        | 2.3%    |
| Fingerprint reader       | 1        | 1.15%   |
| Chipcard                 | 1        | 1.15%   |

