Fedora 37 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 37.

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

Total: 333

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX X570-E GAMING     | [f16b55ea54](https://linux-hardware.org/?probe=f16b55ea54) | Dec 31, 2022 |
| Shuttle       | SH570                       | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| ASRock        | A320M-DVS R4.0              | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c45e0f54fd](https://linux-hardware.org/?probe=c45e0f54fd) | Dec 31, 2022 |
| Shuttle       | SH570                       | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| ASRock        | X79 Extreme6                | [5ea31811b4](https://linux-hardware.org/?probe=5ea31811b4) | Dec 30, 2022 |
| MSI           | H510M-A PRO                 | [4dba3b7c55](https://linux-hardware.org/?probe=4dba3b7c55) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [498c8c83e2](https://linux-hardware.org/?probe=498c8c83e2) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8289d108fb](https://linux-hardware.org/?probe=8289d108fb) | Dec 30, 2022 |
| ASUSTek       | Z87-PRO                     | [eafab9edba](https://linux-hardware.org/?probe=eafab9edba) | Dec 30, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bdc5158ffb](https://linux-hardware.org/?probe=bdc5158ffb) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [4cf9d40c0d](https://linux-hardware.org/?probe=4cf9d40c0d) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [7e53808767](https://linux-hardware.org/?probe=7e53808767) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [12c052156c](https://linux-hardware.org/?probe=12c052156c) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [24b822291e](https://linux-hardware.org/?probe=24b822291e) | Dec 28, 2022 |
| Gigabyte      | B365M DS3H                  | [0dc3c192fd](https://linux-hardware.org/?probe=0dc3c192fd) | Dec 28, 2022 |
| Dell          | 0N4YC8 A00                  | [fc766b2a1b](https://linux-hardware.org/?probe=fc766b2a1b) | Dec 28, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [7bb247e453](https://linux-hardware.org/?probe=7bb247e453) | Dec 28, 2022 |
| Gigabyte      | B365M D2V                   | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5ac2a0028](https://linux-hardware.org/?probe=f5ac2a0028) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | [7aab4546f6](https://linux-hardware.org/?probe=7aab4546f6) | Dec 28, 2022 |
| ASRock        | Z370M-ITX/ac                | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| Gigabyte      | B650I AORUS ULTRA           | [3c25f43c23](https://linux-hardware.org/?probe=3c25f43c23) | Dec 28, 2022 |
| Itautec       | ST 4265                     | [38e4a07f9a](https://linux-hardware.org/?probe=38e4a07f9a) | Dec 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f2751df7ec](https://linux-hardware.org/?probe=f2751df7ec) | Dec 27, 2022 |
| MSI           | Z390-A PRO                  | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| ASRock        | AD2700-ITX                  | [d4fff49f31](https://linux-hardware.org/?probe=d4fff49f31) | Dec 27, 2022 |
| Itautec       | ST 4265                     | [8323542129](https://linux-hardware.org/?probe=8323542129) | Dec 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8d1181c71b](https://linux-hardware.org/?probe=8d1181c71b) | Dec 26, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [4c97c87b61](https://linux-hardware.org/?probe=4c97c87b61) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [628cefc78a](https://linux-hardware.org/?probe=628cefc78a) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b6def743ea](https://linux-hardware.org/?probe=b6def743ea) | Dec 25, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [46705eb79f](https://linux-hardware.org/?probe=46705eb79f) | Dec 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c7d8ce8f80](https://linux-hardware.org/?probe=c7d8ce8f80) | Dec 24, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [e853f645cf](https://linux-hardware.org/?probe=e853f645cf) | Dec 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| MSI           | Z270M MORTAR                | [70564a2846](https://linux-hardware.org/?probe=70564a2846) | Dec 24, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bf8f02ac85](https://linux-hardware.org/?probe=bf8f02ac85) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5fa069144](https://linux-hardware.org/?probe=f5fa069144) | Dec 24, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [926850a516](https://linux-hardware.org/?probe=926850a516) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88df914367](https://linux-hardware.org/?probe=88df914367) | Dec 23, 2022 |
| ASUSTek       | B85-PLUS                    | [16b14098bf](https://linux-hardware.org/?probe=16b14098bf) | Dec 22, 2022 |
| ASRock        | H470M Pro4                  | [b69ccc3353](https://linux-hardware.org/?probe=b69ccc3353) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb006d2d4](https://linux-hardware.org/?probe=6eb006d2d4) | Dec 22, 2022 |
| ASUSTek       | B85-PLUS                    | [cbad10e284](https://linux-hardware.org/?probe=cbad10e284) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [f39488c597](https://linux-hardware.org/?probe=f39488c597) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [0243df6ce4](https://linux-hardware.org/?probe=0243df6ce4) | Dec 21, 2022 |
| HP            | 8266                        | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [8428e68855](https://linux-hardware.org/?probe=8428e68855) | Dec 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd7ed31b20](https://linux-hardware.org/?probe=bd7ed31b20) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cb70181c3a](https://linux-hardware.org/?probe=cb70181c3a) | Dec 21, 2022 |
| Dell          | 02YRK5 A02                  | [f5f6093483](https://linux-hardware.org/?probe=f5f6093483) | Dec 21, 2022 |
| Intel         | H81                         | [747dd5e27a](https://linux-hardware.org/?probe=747dd5e27a) | Dec 20, 2022 |
| ASRock        | Z790 Pro RS WiFi            | [d54c198ec8](https://linux-hardware.org/?probe=d54c198ec8) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [ef5cd85ef3](https://linux-hardware.org/?probe=ef5cd85ef3) | Dec 20, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [f7e97a6c6c](https://linux-hardware.org/?probe=f7e97a6c6c) | Dec 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9451dc3035](https://linux-hardware.org/?probe=9451dc3035) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [60dbf09ee4](https://linux-hardware.org/?probe=60dbf09ee4) | Dec 20, 2022 |
| Gigabyte      | H61M-USB3V                  | [3161a64c4b](https://linux-hardware.org/?probe=3161a64c4b) | Dec 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [6a964b9d6b](https://linux-hardware.org/?probe=6a964b9d6b) | Dec 19, 2022 |
| Gigabyte      | A520M DS3H                  | [4251c08b5d](https://linux-hardware.org/?probe=4251c08b5d) | Dec 18, 2022 |
| Dell          | 0KRC95 A02                  | [e7bb083869](https://linux-hardware.org/?probe=e7bb083869) | Dec 18, 2022 |
| MSI           | Z87M GAMING                 | [bf27014217](https://linux-hardware.org/?probe=bf27014217) | Dec 18, 2022 |
| ASUSTek       | P8H77-V LE                  | [3f76e320c0](https://linux-hardware.org/?probe=3f76e320c0) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | [fed4383ac0](https://linux-hardware.org/?probe=fed4383ac0) | Dec 18, 2022 |
| MSI           | B550-A PRO                  | [53c582a7f6](https://linux-hardware.org/?probe=53c582a7f6) | Dec 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [561aa4411a](https://linux-hardware.org/?probe=561aa4411a) | Dec 18, 2022 |
| ASUSTek       | PRIME B550M-K               | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [3db1266e41](https://linux-hardware.org/?probe=3db1266e41) | Dec 17, 2022 |
| ASUSTek       | P8H77-M LE                  | [d9eba2d52f](https://linux-hardware.org/?probe=d9eba2d52f) | Dec 17, 2022 |
| Gigabyte      | J1900M-D2P                  | [26ecfabc95](https://linux-hardware.org/?probe=26ecfabc95) | Dec 17, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [1bb7d1bffe](https://linux-hardware.org/?probe=1bb7d1bffe) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88d55eced8](https://linux-hardware.org/?probe=88d55eced8) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [54132f7285](https://linux-hardware.org/?probe=54132f7285) | Dec 17, 2022 |
| HP            | 82F2 A01                    | [859d719a2a](https://linux-hardware.org/?probe=859d719a2a) | Dec 16, 2022 |
| Gigabyte      | Z77MX-D3H                   | [50ba321b50](https://linux-hardware.org/?probe=50ba321b50) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [f048f7fcdb](https://linux-hardware.org/?probe=f048f7fcdb) | Dec 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [04bbc083d7](https://linux-hardware.org/?probe=04bbc083d7) | Dec 16, 2022 |
| ASUSTek       | PRIME B550M-K               | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-K               | [a6dfbac9f9](https://linux-hardware.org/?probe=a6dfbac9f9) | Dec 15, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| Lenovo        | 31900003 STD                | [81dea8d96e](https://linux-hardware.org/?probe=81dea8d96e) | Dec 15, 2022 |
| ASRock        | X670E Steel Legend          | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| MSI           | B550-A PRO B02              | [3a1ebe10f8](https://linux-hardware.org/?probe=3a1ebe10f8) | Dec 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2e9fac9df4](https://linux-hardware.org/?probe=2e9fac9df4) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [572f0231a5](https://linux-hardware.org/?probe=572f0231a5) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a0d17e1d50](https://linux-hardware.org/?probe=a0d17e1d50) | Dec 15, 2022 |
| ASUSTek       | PRIME H410M-E               | [cb7bfc231e](https://linux-hardware.org/?probe=cb7bfc231e) | Dec 15, 2022 |
| Intel         | DQ67SW AAG12527-309         | [3b826b42e0](https://linux-hardware.org/?probe=3b826b42e0) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [c7ce3d7180](https://linux-hardware.org/?probe=c7ce3d7180) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [fa4afa166d](https://linux-hardware.org/?probe=fa4afa166d) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [b136ecfff3](https://linux-hardware.org/?probe=b136ecfff3) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [5cde0cdcc4](https://linux-hardware.org/?probe=5cde0cdcc4) | Dec 14, 2022 |
| HP            | 18E4                        | [fece9d45b4](https://linux-hardware.org/?probe=fece9d45b4) | Dec 14, 2022 |
| Dell          | 0M5DCD A00                  | [61c4e63c2d](https://linux-hardware.org/?probe=61c4e63c2d) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [1ccd39b328](https://linux-hardware.org/?probe=1ccd39b328) | Dec 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b20a4554c5](https://linux-hardware.org/?probe=b20a4554c5) | Dec 14, 2022 |
| Dell          | 0YJMC0 A01                  | [59de758672](https://linux-hardware.org/?probe=59de758672) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [1800fc9efb](https://linux-hardware.org/?probe=1800fc9efb) | Dec 14, 2022 |
| Gigabyte      | B550M DS3H                  | [bf6f0c23a2](https://linux-hardware.org/?probe=bf6f0c23a2) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [466ea5976d](https://linux-hardware.org/?probe=466ea5976d) | Dec 13, 2022 |
| MSI           | PRO B650M-A WIFI            | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [469dfe26a6](https://linux-hardware.org/?probe=469dfe26a6) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [9b02acceb3](https://linux-hardware.org/?probe=9b02acceb3) | Dec 12, 2022 |
| ASRock        | X79 Extreme6                | [8ef84e95c1](https://linux-hardware.org/?probe=8ef84e95c1) | Dec 11, 2022 |
| Gigabyte      | H370M DS3H-CF               | [8c1901e5d6](https://linux-hardware.org/?probe=8c1901e5d6) | Dec 11, 2022 |
| ASRock        | 760GM-HD                    | [03fdf6453b](https://linux-hardware.org/?probe=03fdf6453b) | Dec 11, 2022 |
| MSI           | B450M PRO-VDH MAX           | [6bf96cf0fc](https://linux-hardware.org/?probe=6bf96cf0fc) | Dec 11, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5749b67534](https://linux-hardware.org/?probe=5749b67534) | Dec 10, 2022 |
| Lenovo        | ThinkStation S30 056851U    | [8c7b6cfca0](https://linux-hardware.org/?probe=8c7b6cfca0) | Dec 10, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [4f1f6fde97](https://linux-hardware.org/?probe=4f1f6fde97) | Dec 10, 2022 |
| MSI           | H97M-G43                    | [c62f2a0b49](https://linux-hardware.org/?probe=c62f2a0b49) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| ASRock        | X670E Steel Legend          | [11df680f78](https://linux-hardware.org/?probe=11df680f78) | Dec 09, 2022 |
| Gigabyte      | G31_ICH7                    | [d433eed3f1](https://linux-hardware.org/?probe=d433eed3f1) | Dec 09, 2022 |
| Dell          | 0GU083 A00                  | [1f3f73a41c](https://linux-hardware.org/?probe=1f3f73a41c) | Dec 09, 2022 |
| Gigabyte      | Z77MX-D3H                   | [b77b64cc48](https://linux-hardware.org/?probe=b77b64cc48) | Dec 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bcb55a7e4c](https://linux-hardware.org/?probe=bcb55a7e4c) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bddf744d58](https://linux-hardware.org/?probe=bddf744d58) | Dec 09, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [a875eabf3d](https://linux-hardware.org/?probe=a875eabf3d) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [6ab58fe686](https://linux-hardware.org/?probe=6ab58fe686) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [07e4a8072a](https://linux-hardware.org/?probe=07e4a8072a) | Dec 09, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [42f14a38dd](https://linux-hardware.org/?probe=42f14a38dd) | Dec 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [d52b5053b2](https://linux-hardware.org/?probe=d52b5053b2) | Dec 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5544994d11](https://linux-hardware.org/?probe=5544994d11) | Dec 08, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| Shenzhen M... | HX90G                       | [83a892b661](https://linux-hardware.org/?probe=83a892b661) | Dec 08, 2022 |
| Gigabyte      | A520I AC                    | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| MSI           | H97M-G43                    | [53754acfcb](https://linux-hardware.org/?probe=53754acfcb) | Dec 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e40a7efd61](https://linux-hardware.org/?probe=e40a7efd61) | Dec 08, 2022 |
| Gigabyte      | G41MT-S2                    | [f69d93aece](https://linux-hardware.org/?probe=f69d93aece) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [551e0142a8](https://linux-hardware.org/?probe=551e0142a8) | Dec 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [6f715ffe60](https://linux-hardware.org/?probe=6f715ffe60) | Dec 08, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [7f45781139](https://linux-hardware.org/?probe=7f45781139) | Dec 08, 2022 |
| MSI           | B550-A PRO                  | [804710787d](https://linux-hardware.org/?probe=804710787d) | Dec 08, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [61a9d5f84c](https://linux-hardware.org/?probe=61a9d5f84c) | Dec 07, 2022 |
| Gigabyte      | X570 GAMING X               | [811b0e1a71](https://linux-hardware.org/?probe=811b0e1a71) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5be32d156a](https://linux-hardware.org/?probe=5be32d156a) | Dec 06, 2022 |
| HP            | 8767 A                      | [1d4dc77fa3](https://linux-hardware.org/?probe=1d4dc77fa3) | Dec 06, 2022 |
| Acer          | FMP55                       | [78aabc71bf](https://linux-hardware.org/?probe=78aabc71bf) | Dec 05, 2022 |
| Unknown       | HX90                        | [9f3f9dec0b](https://linux-hardware.org/?probe=9f3f9dec0b) | Dec 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [57b6a24933](https://linux-hardware.org/?probe=57b6a24933) | Dec 05, 2022 |
| HP            | 8860 A                      | [23fde1381a](https://linux-hardware.org/?probe=23fde1381a) | Dec 05, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [73d037e031](https://linux-hardware.org/?probe=73d037e031) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Dell          | 0M017G A00                  | [d6b5487094](https://linux-hardware.org/?probe=d6b5487094) | Dec 05, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [cff58a3529](https://linux-hardware.org/?probe=cff58a3529) | Dec 04, 2022 |
| ASRock        | X300-ITX                    | [77d8c41481](https://linux-hardware.org/?probe=77d8c41481) | Dec 04, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d6829bfb6d](https://linux-hardware.org/?probe=d6829bfb6d) | Dec 04, 2022 |
| HP            | 158B                        | [5652b24e0d](https://linux-hardware.org/?probe=5652b24e0d) | Dec 04, 2022 |
| HP            | 158B                        | [015085e084](https://linux-hardware.org/?probe=015085e084) | Dec 04, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [0a626fffe5](https://linux-hardware.org/?probe=0a626fffe5) | Dec 04, 2022 |
| Gigabyte      | GA-970A-DS3                 | [8c06e98cf8](https://linux-hardware.org/?probe=8c06e98cf8) | Dec 03, 2022 |
| Dell          | 0N826N A02                  | [e9f0634dd6](https://linux-hardware.org/?probe=e9f0634dd6) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [05131558b5](https://linux-hardware.org/?probe=05131558b5) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [9fcc18738b](https://linux-hardware.org/?probe=9fcc18738b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [80bba2043d](https://linux-hardware.org/?probe=80bba2043d) | Dec 03, 2022 |
| Unknown       | HX90                        | [40847bd89b](https://linux-hardware.org/?probe=40847bd89b) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [9b1ef89e7e](https://linux-hardware.org/?probe=9b1ef89e7e) | Dec 02, 2022 |
| HP            | 0A98h                       | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [07a15db1a6](https://linux-hardware.org/?probe=07a15db1a6) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [6c18ee8479](https://linux-hardware.org/?probe=6c18ee8479) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [d31a6b4c0f](https://linux-hardware.org/?probe=d31a6b4c0f) | Dec 01, 2022 |
| Positivo      | POS-PIQ57BQA                | [8403658c27](https://linux-hardware.org/?probe=8403658c27) | Dec 01, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [9cd70143b5](https://linux-hardware.org/?probe=9cd70143b5) | Dec 01, 2022 |
| HP            | 0A98h                       | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [42932dd5fd](https://linux-hardware.org/?probe=42932dd5fd) | Dec 01, 2022 |
| ASUSTek       | PRIME X370-PRO              | [aa87dfdc13](https://linux-hardware.org/?probe=aa87dfdc13) | Dec 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [8a4813eec4](https://linux-hardware.org/?probe=8a4813eec4) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Gigabyte      | X570 GAMING X               | [7ea2de1a3b](https://linux-hardware.org/?probe=7ea2de1a3b) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9eabacd766](https://linux-hardware.org/?probe=9eabacd766) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [da83c13da3](https://linux-hardware.org/?probe=da83c13da3) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9f7438d5a3](https://linux-hardware.org/?probe=9f7438d5a3) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [459c2ba743](https://linux-hardware.org/?probe=459c2ba743) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK S       | [2c5c1d6071](https://linux-hardware.org/?probe=2c5c1d6071) | Nov 30, 2022 |
| HP            | 3048h                       | [6f5a8d1a09](https://linux-hardware.org/?probe=6f5a8d1a09) | Nov 29, 2022 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6d835027fa](https://linux-hardware.org/?probe=6d835027fa) | Nov 29, 2022 |
| MSI           | X570-A PRO                  | [92ddd925db](https://linux-hardware.org/?probe=92ddd925db) | Nov 28, 2022 |
| ASUSTek       | GA15DH                      | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | [207d763813](https://linux-hardware.org/?probe=207d763813) | Nov 28, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [81a61c4765](https://linux-hardware.org/?probe=81a61c4765) | Nov 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [521f5c20a9](https://linux-hardware.org/?probe=521f5c20a9) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Gigabyte      | B550 GAMING X               | [b9264b2557](https://linux-hardware.org/?probe=b9264b2557) | Nov 26, 2022 |
| ASUSTek       | PRIME X370-PRO              | [5b0f04d592](https://linux-hardware.org/?probe=5b0f04d592) | Nov 25, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [33f5823764](https://linux-hardware.org/?probe=33f5823764) | Nov 25, 2022 |
| ASUSTek       | PRIME B360M-D               | [67a7943b8d](https://linux-hardware.org/?probe=67a7943b8d) | Nov 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [6f867d822a](https://linux-hardware.org/?probe=6f867d822a) | Nov 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bf1722d4d6](https://linux-hardware.org/?probe=bf1722d4d6) | Nov 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [d6fe192013](https://linux-hardware.org/?probe=d6fe192013) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [7f0ba24aad](https://linux-hardware.org/?probe=7f0ba24aad) | Nov 24, 2022 |
| ASUSTek       | GA15DH                      | [ec6d666a16](https://linux-hardware.org/?probe=ec6d666a16) | Nov 24, 2022 |
| ASRock        | B75 Pro3                    | [e359d0bd70](https://linux-hardware.org/?probe=e359d0bd70) | Nov 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ee5b760222](https://linux-hardware.org/?probe=ee5b760222) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [8de6a24029](https://linux-hardware.org/?probe=8de6a24029) | Nov 24, 2022 |
| Dell          | 0J3C2F A02                  | [0cfd78c6bb](https://linux-hardware.org/?probe=0cfd78c6bb) | Nov 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [b0e5869f2d](https://linux-hardware.org/?probe=b0e5869f2d) | Nov 23, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [99fc338b3e](https://linux-hardware.org/?probe=99fc338b3e) | Nov 23, 2022 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [1deb081598](https://linux-hardware.org/?probe=1deb081598) | Nov 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | [e89ecf8da4](https://linux-hardware.org/?probe=e89ecf8da4) | Nov 23, 2022 |
| MSI           | 2A9C                        | [ee8683a595](https://linux-hardware.org/?probe=ee8683a595) | Nov 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7dd9d3bec3](https://linux-hardware.org/?probe=7dd9d3bec3) | Nov 23, 2022 |
| MSI           | 2A9C                        | [77dd7e3fbc](https://linux-hardware.org/?probe=77dd7e3fbc) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [bd9c6238bc](https://linux-hardware.org/?probe=bd9c6238bc) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [393b7f7d3a](https://linux-hardware.org/?probe=393b7f7d3a) | Nov 23, 2022 |
| Gigabyte      | Z87-HD3                     | [00faab62d7](https://linux-hardware.org/?probe=00faab62d7) | Nov 22, 2022 |
| ASUSTek       | Maximus IX HERO             | [587aa317bd](https://linux-hardware.org/?probe=587aa317bd) | Nov 22, 2022 |
| MSI           | 990FXA-GD65                 | [8e134485ce](https://linux-hardware.org/?probe=8e134485ce) | Nov 22, 2022 |
| ASUSTek       | P6T DELUXE V2               | [d126214b62](https://linux-hardware.org/?probe=d126214b62) | Nov 22, 2022 |
| HP            | 3647h                       | [8f77a73e9b](https://linux-hardware.org/?probe=8f77a73e9b) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f13d80cf0b](https://linux-hardware.org/?probe=f13d80cf0b) | Nov 21, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [34e6521bc8](https://linux-hardware.org/?probe=34e6521bc8) | Nov 21, 2022 |
| ASUSTek       | PRIME Z270-A                | [540d321764](https://linux-hardware.org/?probe=540d321764) | Nov 21, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [34f72bd414](https://linux-hardware.org/?probe=34f72bd414) | Nov 20, 2022 |
| Gigabyte      | H310M S2H x.x               | [97ea29ed26](https://linux-hardware.org/?probe=97ea29ed26) | Nov 20, 2022 |
| Dell          | 0HY9JP A02                  | [fa0e9792f0](https://linux-hardware.org/?probe=fa0e9792f0) | Nov 20, 2022 |
| MSI           | 990FXA-GD65                 | [d41acd5075](https://linux-hardware.org/?probe=d41acd5075) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [a28ef28876](https://linux-hardware.org/?probe=a28ef28876) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | [0735dabc9b](https://linux-hardware.org/?probe=0735dabc9b) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK               | [8c271e833d](https://linux-hardware.org/?probe=8c271e833d) | Nov 20, 2022 |
| ASRock        | B450 Pro4                   | [cd0f63540b](https://linux-hardware.org/?probe=cd0f63540b) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [ecceccb3b7](https://linux-hardware.org/?probe=ecceccb3b7) | Nov 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d304f26226](https://linux-hardware.org/?probe=d304f26226) | Nov 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [050e6cfd68](https://linux-hardware.org/?probe=050e6cfd68) | Nov 19, 2022 |
| ASUSTek       | Z97-P                       | [75748e49d9](https://linux-hardware.org/?probe=75748e49d9) | Nov 19, 2022 |
| Gigabyte      | M720-US3                    | [299b2cd745](https://linux-hardware.org/?probe=299b2cd745) | Nov 18, 2022 |
| Acer          | FMP55                       | [f35d63ca8b](https://linux-hardware.org/?probe=f35d63ca8b) | Nov 18, 2022 |
| ASRock        | X300-ITX                    | [54f7198f58](https://linux-hardware.org/?probe=54f7198f58) | Nov 18, 2022 |
| ASRock        | X670E Pro RS                | [bfccdbd536](https://linux-hardware.org/?probe=bfccdbd536) | Nov 17, 2022 |
| ASUSTek       | H81M-R                      | [cd129bebe1](https://linux-hardware.org/?probe=cd129bebe1) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9f45de6ee3](https://linux-hardware.org/?probe=9f45de6ee3) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [cdf4d49427](https://linux-hardware.org/?probe=cdf4d49427) | Nov 16, 2022 |
| Intel         | DX79SR AAG57199-200         | [b12b9ec8d5](https://linux-hardware.org/?probe=b12b9ec8d5) | Nov 16, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [7bf6427590](https://linux-hardware.org/?probe=7bf6427590) | Nov 14, 2022 |
| Huanan        | X99-F8                      | [503cf4b0ea](https://linux-hardware.org/?probe=503cf4b0ea) | Nov 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [c1044ebf60](https://linux-hardware.org/?probe=c1044ebf60) | Nov 13, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [a84e5c2107](https://linux-hardware.org/?probe=a84e5c2107) | Nov 13, 2022 |
| ASUSTek       | PRIME A320M-E               | [2eacb090ee](https://linux-hardware.org/?probe=2eacb090ee) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [a35ca3673b](https://linux-hardware.org/?probe=a35ca3673b) | Nov 12, 2022 |
| MSI           | Z390-A PRO                  | [e851ddd11a](https://linux-hardware.org/?probe=e851ddd11a) | Nov 10, 2022 |
| ASRock        | H310M-STX                   | [cb421b22a5](https://linux-hardware.org/?probe=cb421b22a5) | Nov 09, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [f2afc66464](https://linux-hardware.org/?probe=f2afc66464) | Nov 09, 2022 |
| Gigabyte      | B85M-D3V-A                  | [f236aa0a8b](https://linux-hardware.org/?probe=f236aa0a8b) | Nov 08, 2022 |
| Dell          | 09WH54 A00                  | [c7723a2b2f](https://linux-hardware.org/?probe=c7723a2b2f) | Nov 07, 2022 |
| Gigabyte      | X670 GAMING X AX            | [1a96ebec7a](https://linux-hardware.org/?probe=1a96ebec7a) | Nov 07, 2022 |
| Gigabyte      | A320M-H-CF                  | [fa33ccff27](https://linux-hardware.org/?probe=fa33ccff27) | Nov 05, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [16b0128664](https://linux-hardware.org/?probe=16b0128664) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [02104ae91b](https://linux-hardware.org/?probe=02104ae91b) | Nov 05, 2022 |
| ASRock        | X570 Taichi                 | [d9902c03cb](https://linux-hardware.org/?probe=d9902c03cb) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [aa9fe4c05c](https://linux-hardware.org/?probe=aa9fe4c05c) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [108df7bc6d](https://linux-hardware.org/?probe=108df7bc6d) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a2c8fe2afa](https://linux-hardware.org/?probe=a2c8fe2afa) | Nov 05, 2022 |
| MSI           | Z390-A PRO                  | [5cfd4967b0](https://linux-hardware.org/?probe=5cfd4967b0) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2c3ddc79ce](https://linux-hardware.org/?probe=2c3ddc79ce) | Nov 04, 2022 |
| HP            | 8459                        | [378537c13c](https://linux-hardware.org/?probe=378537c13c) | Nov 04, 2022 |
| ASUSTek       | PRIME Z370-P II             | [1866954ec7](https://linux-hardware.org/?probe=1866954ec7) | Nov 04, 2022 |
| ASUSTek       | B150 PRO GAMING             | [b2229c56c4](https://linux-hardware.org/?probe=b2229c56c4) | Nov 01, 2022 |
| Gigabyte      | B85M-D3V-A                  | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [4820bca604](https://linux-hardware.org/?probe=4820bca604) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [cdca8a4d95](https://linux-hardware.org/?probe=cdca8a4d95) | Oct 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [8e2ab3d61b](https://linux-hardware.org/?probe=8e2ab3d61b) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H V2               | [ba5da6b270](https://linux-hardware.org/?probe=ba5da6b270) | Oct 29, 2022 |
| MSI           | B450M MORTAR                | [44e8a164d1](https://linux-hardware.org/?probe=44e8a164d1) | Oct 27, 2022 |
| MSI           | X299 SLI PLUS               | [4b79f3c1e6](https://linux-hardware.org/?probe=4b79f3c1e6) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [fbd1924bea](https://linux-hardware.org/?probe=fbd1924bea) | Oct 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | [055062356e](https://linux-hardware.org/?probe=055062356e) | Oct 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [db4db1b508](https://linux-hardware.org/?probe=db4db1b508) | Oct 25, 2022 |
| ASUSTek       | PRIME Z390-P                | [261e670072](https://linux-hardware.org/?probe=261e670072) | Oct 24, 2022 |
| HP            | 2B05                        | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7f855c9b05](https://linux-hardware.org/?probe=7f855c9b05) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [77b57dbe12](https://linux-hardware.org/?probe=77b57dbe12) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [13f4800fa8](https://linux-hardware.org/?probe=13f4800fa8) | Oct 20, 2022 |
| Gigabyte      | 970A-DS3P FX                | [e0c8c2fe15](https://linux-hardware.org/?probe=e0c8c2fe15) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [6941ece1e9](https://linux-hardware.org/?probe=6941ece1e9) | Oct 18, 2022 |
| Dell          | 0WR7PY A02                  | [8c1b258565](https://linux-hardware.org/?probe=8c1b258565) | Oct 16, 2022 |
| MSI           | A320M PRO-VH PLUS           | [c3c46266d1](https://linux-hardware.org/?probe=c3c46266d1) | Oct 16, 2022 |
| Gigabyte      | H610M H DDR4                | [985b192440](https://linux-hardware.org/?probe=985b192440) | Oct 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [4e66c25e04](https://linux-hardware.org/?probe=4e66c25e04) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | [05fa96288f](https://linux-hardware.org/?probe=05fa96288f) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [f1fcb66794](https://linux-hardware.org/?probe=f1fcb66794) | Oct 12, 2022 |
| MSI           | B450M-A PRO MAX             | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| MSI           | B550M PRO-VDH               | [c4e09cdf87](https://linux-hardware.org/?probe=c4e09cdf87) | Oct 09, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| Dell          | 0RY007                      | [745f69ec3d](https://linux-hardware.org/?probe=745f69ec3d) | Oct 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| Gigabyte      | B550M DS3H                  | [2f8557640c](https://linux-hardware.org/?probe=2f8557640c) | Oct 02, 2022 |
| ASUSTek       | PRIME Z270-A                | [4118e245a3](https://linux-hardware.org/?probe=4118e245a3) | Sep 29, 2022 |
| Intel         | DP35DP AAD81073-208         | [031ff09179](https://linux-hardware.org/?probe=031ff09179) | Sep 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| Acer          | Aspire X1900                | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [54d3096bb6](https://linux-hardware.org/?probe=54d3096bb6) | Sep 21, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1869422fde](https://linux-hardware.org/?probe=1869422fde) | Sep 20, 2022 |
| ASUSTek       | Z170-A                      | [aad09d3281](https://linux-hardware.org/?probe=aad09d3281) | Sep 20, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a6857e4b03](https://linux-hardware.org/?probe=a6857e4b03) | Sep 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [424e3ded44](https://linux-hardware.org/?probe=424e3ded44) | Sep 19, 2022 |
| HP            | 2B05                        | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| HP            | 3397                        | [637a5570cf](https://linux-hardware.org/?probe=637a5570cf) | Sep 16, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [dcaf7e8bd0](https://linux-hardware.org/?probe=dcaf7e8bd0) | Sep 15, 2022 |
| Gigabyte      | B85M-D3V-A                  | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| ASUSTek       | PRIME Z270-A                | [2642647feb](https://linux-hardware.org/?probe=2642647feb) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| HP            | 1998                        | [bf93a500f4](https://linux-hardware.org/?probe=bf93a500f4) | Sep 14, 2022 |
| MSI           | Z370 TOMAHAWK               | [251d227686](https://linux-hardware.org/?probe=251d227686) | Aug 22, 2022 |
| Dell          | 08NPPY A00                  | [93eb00c3c5](https://linux-hardware.org/?probe=93eb00c3c5) | Jun 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | [2cd65296c2](https://linux-hardware.org/?probe=2cd65296c2) | May 08, 2022 |
| HP            | 0B54h D                     | [7153ec172b](https://linux-hardware.org/?probe=7153ec172b) | Mar 21, 2022 |
| HP            | 0B54h D                     | [399cc50503](https://linux-hardware.org/?probe=399cc50503) | Mar 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| 6.0.12-300.fc37.x86_64                                 | 43       | 16.8%   |
| 6.0.11-300.fc37.x86_64                                 | 30       | 11.72%  |
| 6.0.8-300.fc37.x86_64                                  | 27       | 10.55%  |
| 6.0.9-300.fc37.x86_64                                  | 26       | 10.16%  |
| 6.0.10-300.fc37.x86_64                                 | 21       | 8.2%    |
| 6.0.15-300.fc37.x86_64                                 | 18       | 7.03%   |
| 6.0.7-301.fc37.x86_64                                  | 15       | 5.86%   |
| 5.19.16-301.fc37.x86_64                                | 12       | 4.69%   |
| 6.0.14-300.fc37.x86_64                                 | 8        | 3.13%   |
| 5.19.9-300.fc37.x86_64                                 | 8        | 3.13%   |
| 5.19.13-300.fc37.x86_64                                | 8        | 3.13%   |
| 6.0.13-300.fc37.x86_64                                 | 5        | 1.95%   |
| 5.19.7-300.fc37.x86_64                                 | 4        | 1.56%   |
| 6.0.5-300.fc37.x86_64                                  | 3        | 1.17%   |
| 5.19.8-300.fc37.x86_64                                 | 3        | 1.17%   |
| 6.0.6-300.fc37.x86_64                                  | 2        | 0.78%   |
| 5.19.16-300.fc37.x86_64                                | 2        | 0.78%   |
| 5.19.12-300.fc37.x86_64                                | 2        | 0.78%   |
| 6.1.0-0.rc0.20221014git9c9155a3509a.11.fc38.x86_64     | 1        | 0.39%   |
| 6.0.3-300.fc37.x86_64                                  | 1        | 0.39%   |
| 6.0.2-301.fc37.x86_64                                  | 1        | 0.39%   |
| 6.0.13-602.inttf.fc37.x86_64                           | 1        | 0.39%   |
| 6.0.10-602.inttf.fc37.x86_64                           | 1        | 0.39%   |
| 6.0.10-301.fsync.fc37.x86_64                           | 1        | 0.39%   |
| 6.0.0-0.rc6.20220922gitdc164f4fb00a.43.fc38.x86_64     | 1        | 0.39%   |
| 5.8.15-301.fc33.x86_64                                 | 1        | 0.39%   |
| 5.19.8-501.chinfo.fc37.x86_64                          | 1        | 0.39%   |
| 5.19.16-602.inttf.fc37.x86_64                          | 1        | 0.39%   |
| 5.19.15-301.fc37.x86_64                                | 1        | 0.39%   |
| 5.19.14-602.inttf.fc37.x86_64                          | 1        | 0.39%   |
| 5.19.14-300.fc37.x86_64                                | 1        | 0.39%   |
| 5.19.10-602.inttf.fc37.x86_64                          | 1        | 0.39%   |
| 5.19.10-300.fc37.x86_64                                | 1        | 0.39%   |
| 5.19.0-65.fc37.x86_64                                  | 1        | 0.39%   |
| 5.19.0-0.rc1.20220610git874c8ca1e60b.18.fc37.x86_64    | 1        | 0.39%   |
| 5.18.0-0.rc5.20220505gita7391ad3572431a.43.fc37.x86_64 | 1        | 0.39%   |
| 5.17.0-0.rc6.109.fc37.x86_64                           | 1        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0.12  | 43       | 16.8%   |
| 6.0.11  | 30       | 11.72%  |
| 6.0.8   | 27       | 10.55%  |
| 6.0.9   | 26       | 10.16%  |
| 6.0.10  | 23       | 8.98%   |
| 6.0.15  | 18       | 7.03%   |
| 6.0.7   | 15       | 5.86%   |
| 5.19.16 | 15       | 5.86%   |
| 6.0.14  | 8        | 3.13%   |
| 5.19.9  | 8        | 3.13%   |
| 5.19.13 | 8        | 3.13%   |
| 6.0.13  | 6        | 2.34%   |
| 5.19.8  | 4        | 1.56%   |
| 5.19.7  | 4        | 1.56%   |
| 6.0.5   | 3        | 1.17%   |
| 6.0.6   | 2        | 0.78%   |
| 5.19.14 | 2        | 0.78%   |
| 5.19.12 | 2        | 0.78%   |
| 5.19.10 | 2        | 0.78%   |
| 5.19.0  | 2        | 0.78%   |
| 6.1.0   | 1        | 0.39%   |
| 6.0.3   | 1        | 0.39%   |
| 6.0.2   | 1        | 0.39%   |
| 6.0.0   | 1        | 0.39%   |
| 5.8.15  | 1        | 0.39%   |
| 5.19.15 | 1        | 0.39%   |
| 5.18.0  | 1        | 0.39%   |
| 5.17.0  | 1        | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0     | 199      | 80.24%  |
| 5.19    | 45       | 18.15%  |
| 6.1     | 1        | 0.4%    |
| 5.8     | 1        | 0.4%    |
| 5.18    | 1        | 0.4%    |
| 5.17    | 1        | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 245      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| GNOME                        | 183      | 74.69%  |
| KDE5                         | 43       | 17.55%  |
| XFCE                         | 6        | 2.45%   |
| Unknown                      | 4        | 1.63%   |
| Cinnamon                     | 3        | 1.22%   |
| X-Cinnamon                   | 2        | 0.82%   |
| MATE                         | 2        | 0.82%   |
| LXDE                         | 1        | 0.41%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1        | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 155      | 63.27%  |
| X11     | 81       | 33.06%  |
| Tty     | 5        | 2.04%   |
| Unknown | 4        | 1.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 136      | 55.28%  |
| GDM     | 73       | 29.67%  |
| SDDM    | 22       | 8.94%   |
| LightDM | 14       | 5.69%   |
| LXDM    | 1        | 0.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| en_US          | 128      | 52.24%  |
| en_GB          | 22       | 8.98%   |
| pt_BR          | 16       | 6.53%   |
| ru_RU          | 15       | 6.12%   |
| pl_PL          | 9        | 3.67%   |
| fr_FR          | 7        | 2.86%   |
| es_ES          | 7        | 2.86%   |
| en_AU          | 7        | 2.86%   |
| de_DE          | 7        | 2.86%   |
| it_IT          | 6        | 2.45%   |
| en_CA          | 4        | 1.63%   |
| hu_HU          | 3        | 1.22%   |
| cs_CZ          | 3        | 1.22%   |
| fi_FI          | 2        | 0.82%   |
| C              | 2        | 0.82%   |
| tr_TR          | 1        | 0.41%   |
| sv_SE          | 1        | 0.41%   |
| pt_PT          | 1        | 0.41%   |
| nl_NL          | 1        | 0.41%   |
| es_PE          | 1        | 0.41%   |
| ca_ES@valencia | 1        | 0.41%   |
| ca_ES          | 1        | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 182      | 73.98%  |
| BIOS | 64       | 26.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 190      | 77.55%  |
| Ext4  | 46       | 18.78%  |
| Xfs   | 8        | 3.27%   |
| F2fs  | 1        | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 132      | 53.66%  |
| GPT     | 99       | 40.24%  |
| MBR     | 15       | 6.1%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 213      | 86.94%  |
| Yes       | 32       | 13.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 196      | 80%     |
| Yes       | 49       | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 78       | 31.84%  |
| MSI                                  | 48       | 19.59%  |
| Gigabyte Technology                  | 45       | 18.37%  |
| ASRock                               | 21       | 8.57%   |
| Dell                                 | 17       | 6.94%   |
| Hewlett-Packard                      | 13       | 5.31%   |
| Lenovo                               | 6        | 2.45%   |
| Intel                                | 4        | 1.63%   |
| Acer                                 | 3        | 1.22%   |
| Shuttle                              | 1        | 0.41%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.41%   |
| Positivo                             | 1        | 0.41%   |
| MACHINIST                            | 1        | 0.41%   |
| Itautec                              | 1        | 0.41%   |
| Huanan                               | 1        | 0.41%   |
| GALAX                                | 1        | 0.41%   |
| Fujitsu                              | 1        | 0.41%   |
| Apple                                | 1        | 0.41%   |
| Unknown                              | 1        | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 6        | 2.45%   |
| MSI MS-7C02                                | 4        | 1.63%   |
| Dell OptiPlex 7010                         | 4        | 1.63%   |
| MSI MS-7C56                                | 3        | 1.22%   |
| MSI MS-7A38                                | 3        | 1.22%   |
| ASUS TUF Gaming B550M-PLUS                 | 3        | 1.22%   |
| ASUS ROG STRIX X670E-F GAMING WIFI         | 3        | 1.22%   |
| ASUS ROG STRIX X570-E GAMING               | 3        | 1.22%   |
| ASUS ROG STRIX B450-F GAMING               | 3        | 1.22%   |
| ASUS PRIME B550-PLUS                       | 3        | 1.22%   |
| MSI MS-7C91                                | 2        | 0.82%   |
| MSI MS-7C84                                | 2        | 0.82%   |
| MSI MS-7B98                                | 2        | 0.82%   |
| MSI MS-7B78                                | 2        | 0.82%   |
| Gigabyte GA-78LMT-USB3 6.0                 | 2        | 0.82%   |
| Gigabyte B550M DS3H                        | 2        | 0.82%   |
| Dell OptiPlex 790                          | 2        | 0.82%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 0.82%   |
| ASUS TUF Gaming B550-PLUS                  | 2        | 0.82%   |
| ASUS ROG STRIX B550-F GAMING               | 2        | 0.82%   |
| ASUS ROG CROSSHAIR VIII IMPACT             | 2        | 0.82%   |
| ASUS ProArt Z690-CREATOR WIFI              | 2        | 0.82%   |
| ASUS PRIME Z270-A                          | 2        | 0.82%   |
| ASUS PRIME X670E-PRO WIFI                  | 2        | 0.82%   |
| ASUS PRIME X370-PRO                        | 2        | 0.82%   |
| ASUS PRIME B450M-GAMING/BR                 | 2        | 0.82%   |
| ASRock X79 Extreme6                        | 2        | 0.82%   |
| ASRock X670E Steel Legend                  | 2        | 0.82%   |
| ASRock X300-ITX                            | 2        | 0.82%   |
| Shuttle SH570                              | 1        | 0.41%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.41%   |
| Positivo POS-PIQ57BQ                       | 1        | 0.41%   |
| MSI VENGEANCE a7200                        | 1        | 0.41%   |
| MSI s5650br                                | 1        | 0.41%   |
| MSI MS-7D77                                | 1        | 0.41%   |
| MSI MS-7D75                                | 1        | 0.41%   |
| MSI MS-7D43                                | 1        | 0.41%   |
| MSI MS-7D31                                | 1        | 0.41%   |
| MSI MS-7D25                                | 1        | 0.41%   |
| MSI MS-7D22                                | 1        | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 25       | 10.2%   |
| ASUS ROG                                   | 19       | 7.76%   |
| ASUS TUF                                   | 15       | 6.12%   |
| Dell OptiPlex                              | 11       | 4.49%   |
| ASUS All                                   | 6        | 2.45%   |
| MSI MS-7C02                                | 4        | 1.63%   |
| Lenovo ThinkCentre                         | 4        | 1.63%   |
| MSI MS-7C56                                | 3        | 1.22%   |
| MSI MS-7A38                                | 3        | 1.22%   |
| HP Pavilion                                | 3        | 1.22%   |
| HP Compaq                                  | 3        | 1.22%   |
| Gigabyte X570                              | 3        | 1.22%   |
| Gigabyte B550                              | 3        | 1.22%   |
| Dell Inspiron                              | 3        | 1.22%   |
| ASUS ProArt                                | 3        | 1.22%   |
| ASRock X670E                               | 3        | 1.22%   |
| Acer Aspire                                | 3        | 1.22%   |
| MSI MS-7C91                                | 2        | 0.82%   |
| MSI MS-7C84                                | 2        | 0.82%   |
| MSI MS-7B98                                | 2        | 0.82%   |
| MSI MS-7B78                                | 2        | 0.82%   |
| HP EliteDesk                               | 2        | 0.82%   |
| Gigabyte GA-78LMT-USB3                     | 2        | 0.82%   |
| Gigabyte B550M                             | 2        | 0.82%   |
| Gigabyte B450M                             | 2        | 0.82%   |
| Gigabyte B365M                             | 2        | 0.82%   |
| Dell Precision                             | 2        | 0.82%   |
| ASRock X79                                 | 2        | 0.82%   |
| ASRock X300-ITX                            | 2        | 0.82%   |
| ASRock FM2A88X                             | 2        | 0.82%   |
| Shuttle SH570                              | 1        | 0.41%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.41%   |
| Positivo POS-PIQ57BQ                       | 1        | 0.41%   |
| MSI VENGEANCE                              | 1        | 0.41%   |
| MSI s5650br                                | 1        | 0.41%   |
| MSI MS-7D77                                | 1        | 0.41%   |
| MSI MS-7D75                                | 1        | 0.41%   |
| MSI MS-7D43                                | 1        | 0.41%   |
| MSI MS-7D31                                | 1        | 0.41%   |
| MSI MS-7D25                                | 1        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 40       | 16.33%  |
| 2018 | 33       | 13.47%  |
| 2019 | 27       | 11.02%  |
| 2022 | 26       | 10.61%  |
| 2021 | 23       | 9.39%   |
| 2017 | 16       | 6.53%   |
| 2013 | 16       | 6.53%   |
| 2012 | 15       | 6.12%   |
| 2014 | 14       | 5.71%   |
| 2011 | 7        | 2.86%   |
| 2009 | 7        | 2.86%   |
| 2015 | 6        | 2.45%   |
| 2010 | 6        | 2.45%   |
| 2016 | 4        | 1.63%   |
| 2008 | 3        | 1.22%   |
| 2007 | 1        | 0.41%   |
| 2006 | 1        | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 245      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 222      | 90.61%  |
| Enabled  | 23       | 9.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 245      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 71       | 28.86%  |
| 32.01-64.0      | 67       | 27.24%  |
| 8.01-16.0       | 36       | 14.63%  |
| 64.01-256.0     | 28       | 11.38%  |
| 24.01-32.0      | 16       | 6.5%    |
| 4.01-8.0        | 15       | 6.1%    |
| 3.01-4.0        | 11       | 4.47%   |
| More than 256.0 | 1        | 0.41%   |
| 1.01-2.0        | 1        | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 75       | 29.88%  |
| 3.01-4.0   | 68       | 27.09%  |
| 2.01-3.0   | 53       | 21.12%  |
| 8.01-16.0  | 29       | 11.55%  |
| 1.01-2.0   | 19       | 7.57%   |
| 0.51-1.0   | 4        | 1.59%   |
| 16.01-24.0 | 2        | 0.8%    |
| 24.01-32.0 | 1        | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 72       | 29.27%  |
| 1      | 70       | 28.46%  |
| 3      | 55       | 22.36%  |
| 4      | 27       | 10.98%  |
| 5      | 10       | 4.07%   |
| 6      | 6        | 2.44%   |
| 7      | 3        | 1.22%   |
| 15     | 1        | 0.41%   |
| 12     | 1        | 0.41%   |
| 0      | 1        | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 177      | 71.95%  |
| Yes       | 69       | 28.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 243      | 99.18%  |
| No        | 2        | 0.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 50.61%  |
| Yes       | 121      | 49.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 125      | 51.02%  |
| Yes       | 120      | 48.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 66       | 26.61%  |
| Brazil       | 18       | 7.26%   |
| Germany      | 16       | 6.45%   |
| Russia       | 14       | 5.65%   |
| Poland       | 13       | 5.24%   |
| Italy        | 11       | 4.44%   |
| Spain        | 10       | 4.03%   |
| France       | 10       | 4.03%   |
| UK           | 9        | 3.63%   |
| Australia    | 8        | 3.23%   |
| Sweden       | 5        | 2.02%   |
| Netherlands  | 5        | 2.02%   |
| Hungary      | 5        | 2.02%   |
| Romania      | 4        | 1.61%   |
| Czechia      | 4        | 1.61%   |
| Canada       | 4        | 1.61%   |
| Austria      | 4        | 1.61%   |
| Greece       | 3        | 1.21%   |
| Vietnam      | 2        | 0.81%   |
| Switzerland  | 2        | 0.81%   |
| Singapore    | 2        | 0.81%   |
| Saudi Arabia | 2        | 0.81%   |
| Portugal     | 2        | 0.81%   |
| Norway       | 2        | 0.81%   |
| Malaysia     | 2        | 0.81%   |
| Indonesia    | 2        | 0.81%   |
| Finland      | 2        | 0.81%   |
| Belgium      | 2        | 0.81%   |
| Belarus      | 2        | 0.81%   |
| UAE          | 1        | 0.4%    |
| Turkey       | 1        | 0.4%    |
| Thailand     | 1        | 0.4%    |
| South Korea  | 1        | 0.4%    |
| South Africa | 1        | 0.4%    |
| Slovenia     | 1        | 0.4%    |
| Serbia       | 1        | 0.4%    |
| Peru         | 1        | 0.4%    |
| Oman         | 1        | 0.4%    |
| Mexico       | 1        | 0.4%    |
| Maldives     | 1        | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Warsaw                   | 5        | 1.99%   |
| Sydney                   | 4        | 1.59%   |
| Moscow                   | 4        | 1.59%   |
| Budapest                 | 4        | 1.59%   |
| Berlin                   | 4        | 1.59%   |
| Vienna                   | 3        | 1.2%    |
| Singapore                | 2        | 0.8%    |
| Sao Paulo                | 2        | 0.8%    |
| Santa Clara              | 2        | 0.8%    |
| Rochester                | 2        | 0.8%    |
| Porto Alegre             | 2        | 0.8%    |
| Palmas                   | 2        | 0.8%    |
| Minsk                    | 2        | 0.8%    |
| Melbourne                | 2        | 0.8%    |
| London                   | 2        | 0.8%    |
| Krasnodar                | 2        | 0.8%    |
| Ho Chi Minh City         | 2        | 0.8%    |
| Hamburg                  | 2        | 0.8%    |
| Goiânia                 | 2        | 0.8%    |
| Zurich                   | 1        | 0.4%    |
| Zierikzee                | 1        | 0.4%    |
| York                     | 1        | 0.4%    |
| Yogyakarta               | 1        | 0.4%    |
| Yekaterinburg            | 1        | 0.4%    |
| Westford                 | 1        | 0.4%    |
| Waterville               | 1        | 0.4%    |
| Waterbury                | 1        | 0.4%    |
| Waren                    | 1        | 0.4%    |
| Wallisellen              | 1        | 0.4%    |
| Wageningen               | 1        | 0.4%    |
| Voronezh                 | 1        | 0.4%    |
| Volgograd                | 1        | 0.4%    |
| Vitry-sur-Seine          | 1        | 0.4%    |
| Vinhedo                  | 1        | 0.4%    |
| Villeneuve-Saint-Germain | 1        | 0.4%    |
| Villa                    | 1        | 0.4%    |
| Vigo                     | 1        | 0.4%    |
| Veresegyhaz              | 1        | 0.4%    |
| Vaxjo                    | 1        | 0.4%    |
| Vassar                   | 1        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| Samsung Electronics            | 110      | 165    | 22.09%  |
| WDC                            | 84       | 130    | 16.87%  |
| Seagate                        | 84       | 111    | 16.87%  |
| Kingston                       | 40       | 46     | 8.03%   |
| Sandisk                        | 35       | 39     | 7.03%   |
| Toshiba                        | 24       | 27     | 4.82%   |
| Crucial                        | 21       | 23     | 4.22%   |
| Phison Electronics             | 11       | 13     | 2.21%   |
| Intel                          | 7        | 7      | 1.41%   |
| Hitachi                        | 6        | 8      | 1.2%    |
| A-DATA Technology              | 6        | 6      | 1.2%    |
| Unknown                        | 5        | 5      | 1%      |
| SPCC                           | 5        | 7      | 1%      |
| Micron/Crucial Technology      | 5        | 5      | 1%      |
| Apacer                         | 5        | 5      | 1%      |
| HGST                           | 4        | 6      | 0.8%    |
| Corsair                        | 4        | 6      | 0.8%    |
| China                          | 3        | 3      | 0.6%    |
| ADATA Technology               | 3        | 3      | 0.6%    |
| SK hynix                       | 2        | 2      | 0.4%    |
| Realtek Semiconductor          | 2        | 2      | 0.4%    |
| PNY                            | 2        | 2      | 0.4%    |
| Plextor                        | 2        | 2      | 0.4%    |
| Lite-On Technology             | 2        | 2      | 0.4%    |
| USB3.0                         | 1        | 1      | 0.2%    |
| Transcend                      | 1        | 1      | 0.2%    |
| Team                           | 1        | 1      | 0.2%    |
| Super Talent                   | 1        | 1      | 0.2%    |
| Solid State Storage Technology | 1        | 1      | 0.2%    |
| Seagate Technology             | 1        | 1      | 0.2%    |
| SABRENT                        | 1        | 1      | 0.2%    |
| Phison                         | 1        | 1      | 0.2%    |
| Patriot                        | 1        | 1      | 0.2%    |
| OWC                            | 1        | 1      | 0.2%    |
| Netac                          | 1        | 1      | 0.2%    |
| Mercury                        | 1        | 1      | 0.2%    |
| Maxtor                         | 1        | 1      | 0.2%    |
| LITEON                         | 1        | 1      | 0.2%    |
| Lexar                          | 1        | 2      | 0.2%    |
| KingSpec                       | 1        | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 26       | 4.48%   |
| Seagate ST2000DM008-2FR102 2TB                        | 14       | 2.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 13       | 2.24%   |
| Kingston SA400S37240G 240GB SSD                       | 12       | 2.07%   |
| Seagate ST1000DM010-2EP102 1TB                        | 8        | 1.38%   |
| Seagate ST500DM002-1BD142 500GB                       | 6        | 1.03%   |
| Samsung SSD 870 EVO 500GB                             | 6        | 1.03%   |
| Samsung SSD 860 EVO 500GB                             | 6        | 1.03%   |
| Phison E12 NVMe Controller 1TB                        | 6        | 1.03%   |
| Kingston SA400S37120G 120GB SSD                       | 6        | 1.03%   |
| Crucial CT1000MX500SSD1 1TB                           | 6        | 1.03%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 5        | 0.86%   |
| Toshiba DT01ACA200 2TB                                | 5        | 0.86%   |
| Seagate ST1000DM003-1ER162 1TB                        | 5        | 0.86%   |
| Samsung SSD 970 EVO Plus 500GB                        | 5        | 0.86%   |
| Samsung SSD 970 EVO Plus 2TB                          | 5        | 0.86%   |
| Samsung SSD 860 EVO 1TB                               | 5        | 0.86%   |
| Samsung SSD 850 EVO 250GB                             | 5        | 0.86%   |
| Kingston SA400S37480G 480GB SSD                       | 5        | 0.86%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 4        | 0.69%   |
| WDC WD30EFRX-68EUZN0 3TB                              | 4        | 0.69%   |
| Seagate ST31000528AS 1TB                              | 4        | 0.69%   |
| Seagate ST2000DM008-2UB102 2TB                        | 4        | 0.69%   |
| Seagate ST2000DM006-2DM164 2TB                        | 4        | 0.69%   |
| Samsung SSD 980 PRO 1TB                               | 4        | 0.69%   |
| Samsung SSD 980 1TB                                   | 4        | 0.69%   |
| Samsung SSD 870 QVO 2TB                               | 4        | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 4        | 0.69%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 4        | 0.69%   |
| Intel SSD 660P Series 1024GB                          | 4        | 0.69%   |
| WDC WD40EZRZ-00GXCB0 4TB                              | 3        | 0.52%   |
| WDC WD20EARX-00PASB0 2TB                              | 3        | 0.52%   |
| WDC WD10EZEX-60WN4A0 1TB                              | 3        | 0.52%   |
| Toshiba HDWD110 1TB                                   | 3        | 0.52%   |
| Seagate ST31000524AS 1TB                              | 3        | 0.52%   |
| Sandisk WD Blue SN550 NVMe SSD 500GB                  | 3        | 0.52%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 256GB | 3        | 0.52%   |
| Samsung SSD 970 EVO Plus 250GB                        | 3        | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB                          | 3        | 0.52%   |
| Samsung SSD 960 EVO 250GB                             | 3        | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 82       | 109    | 44.09%  |
| WDC                 | 68       | 101    | 36.56%  |
| Toshiba             | 17       | 19     | 9.14%   |
| Hitachi             | 6        | 8      | 3.23%   |
| Samsung Electronics | 4        | 4      | 2.15%   |
| HGST                | 4        | 6      | 2.15%   |
| Unknown             | 2        | 2      | 1.08%   |
| USB3.0              | 1        | 1      | 0.54%   |
| Maxtor              | 1        | 1      | 0.54%   |
| ASMT                | 1        | 2      | 0.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 47       | 68     | 28.83%  |
| Kingston            | 29       | 34     | 17.79%  |
| Crucial             | 20       | 21     | 12.27%  |
| SanDisk             | 16       | 16     | 9.82%   |
| WDC                 | 12       | 15     | 7.36%   |
| Toshiba             | 4        | 4      | 2.45%   |
| SPCC                | 3        | 4      | 1.84%   |
| China               | 3        | 3      | 1.84%   |
| Apacer              | 3        | 3      | 1.84%   |
| Unknown             | 2        | 2      | 1.23%   |
| PNY                 | 2        | 2      | 1.23%   |
| Plextor             | 2        | 2      | 1.23%   |
| Intel               | 2        | 2      | 1.23%   |
| Corsair             | 2        | 3      | 1.23%   |
| A-DATA Technology   | 2        | 2      | 1.23%   |
| Transcend           | 1        | 1      | 0.61%   |
| Super Talent        | 1        | 1      | 0.61%   |
| SK hynix            | 1        | 1      | 0.61%   |
| Patriot             | 1        | 1      | 0.61%   |
| OWC                 | 1        | 1      | 0.61%   |
| Netac               | 1        | 1      | 0.61%   |
| Mercury             | 1        | 1      | 0.61%   |
| LITEON              | 1        | 1      | 0.61%   |
| Lexar               | 1        | 2      | 0.61%   |
| KingSpec            | 1        | 1      | 0.61%   |
| KingFast            | 1        | 1      | 0.61%   |
| KingDian            | 1        | 1      | 0.61%   |
| AMD                 | 1        | 1      | 0.61%   |
| Acer                | 1        | 1      | 0.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 147      | 199    | 34.03%  |
| SSD     | 140      | 196    | 32.41%  |
| HDD     | 140      | 253    | 32.41%  |
| Unknown | 5        | 5      | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 197      | 434    | 54.57%  |
| NVMe | 146      | 198    | 40.44%  |
| SAS  | 18       | 21     | 4.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 129      | 184    | 41.21%  |
| 0.51-1.0   | 95       | 136    | 30.35%  |
| 1.01-2.0   | 47       | 63     | 15.02%  |
| 4.01-10.0  | 15       | 21     | 4.79%   |
| 3.01-4.0   | 13       | 17     | 4.15%   |
| 2.01-3.0   | 13       | 24     | 4.15%   |
| 10.01-20.0 | 1        | 4      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 48       | 19.43%  |
| 501-1000       | 43       | 17.41%  |
| More than 3000 | 41       | 16.6%   |
| 2001-3000      | 31       | 12.55%  |
| 251-500        | 27       | 10.93%  |
| 101-250        | 23       | 9.31%   |
| 1-20           | 15       | 6.07%   |
| Unknown        | 11       | 4.45%   |
| 51-100         | 6        | 2.43%   |
| 21-50          | 2        | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 50       | 20.16%  |
| 501-1000       | 41       | 16.53%  |
| 21-50          | 28       | 11.29%  |
| 101-250        | 28       | 11.29%  |
| 1001-2000      | 27       | 10.89%  |
| 251-500        | 26       | 10.48%  |
| 51-100         | 18       | 7.26%   |
| Unknown        | 11       | 4.44%   |
| More than 3000 | 10       | 4.03%   |
| 2001-3000      | 9        | 3.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63H0B1 500GB           | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-603CA0 500GB           | 1        | 1      | 2.56%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1        | 1      | 2.56%   |
| WDC WD3200AAKS-00UU3A0 320GB          | 1        | 1      | 2.56%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 1      | 2.56%   |
| WDC WD15EARS-00MVWB0 1TB              | 1        | 1      | 2.56%   |
| WDC WD140EDFZ-11A0VA0 14TB            | 1        | 2      | 2.56%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1        | 2      | 2.56%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1        | 1      | 2.56%   |
| Toshiba MK3263GSX 320GB               | 1        | 1      | 2.56%   |
| SPCC SPCCSolidStateDisk 128GB SSD     | 1        | 1      | 2.56%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1        | 1      | 2.56%   |
| Seagate ST8000NE001-2M7101 8TB        | 1        | 1      | 2.56%   |
| Seagate ST6000DM003-2CY186 6TB        | 1        | 1      | 2.56%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 2.56%   |
| Seagate ST3320620AS 320GB             | 1        | 1      | 2.56%   |
| Seagate ST32000641AS 2TB              | 1        | 1      | 2.56%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 2.56%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 2.56%   |
| Seagate ST31000340NS 1TB              | 1        | 1      | 2.56%   |
| Seagate ST3000DM001-1ER166 3TB        | 1        | 1      | 2.56%   |
| Seagate ST3000DM001-1CH166 3TB        | 1        | 1      | 2.56%   |
| Seagate ST2000DM008-2FR102 2TB        | 1        | 1      | 2.56%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 2.56%   |
| Seagate ST1000VM002-1CT162 1TB        | 1        | 1      | 2.56%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 2.56%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1        | 1      | 2.56%   |
| Samsung Electronics HD642JJ 640GB     | 1        | 1      | 2.56%   |
| Samsung Electronics HD103SI 1TB       | 1        | 1      | 2.56%   |
| Maxtor 6B200M0 208GB                  | 1        | 1      | 2.56%   |
| Kingston SA400S37480G 480GB SSD       | 1        | 1      | 2.56%   |
| Intel SSDSC2CT120A3 120GB             | 1        | 1      | 2.56%   |
| Intel SSDSA2M080G2GC 80GB             | 1        | 1      | 2.56%   |
| Hitachi HDT721032SLA360 320GB         | 1        | 1      | 2.56%   |
| Crucial CT240M500SSD1 240GB           | 1        | 1      | 2.56%   |
| Crucial CT1050MX300SSD4 1050GB        | 1        | 1      | 2.56%   |
| Corsair Force LE200 SSD 240GB         | 1        | 1      | 2.56%   |
| AMD R5SL960G 960GB SSD                | 1        | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 14     | 33.33%  |
| WDC                 | 9        | 12     | 25%     |
| Samsung Electronics | 3        | 3      | 8.33%   |
| Intel               | 2        | 2      | 5.56%   |
| Crucial             | 2        | 2      | 5.56%   |
| Toshiba             | 1        | 1      | 2.78%   |
| SPCC                | 1        | 1      | 2.78%   |
| SK hynix            | 1        | 1      | 2.78%   |
| Maxtor              | 1        | 1      | 2.78%   |
| Kingston            | 1        | 1      | 2.78%   |
| Hitachi             | 1        | 1      | 2.78%   |
| Corsair             | 1        | 1      | 2.78%   |
| AMD                 | 1        | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 14     | 46.15%  |
| WDC                 | 9        | 12     | 34.62%  |
| Samsung Electronics | 2        | 2      | 7.69%   |
| Toshiba             | 1        | 1      | 3.85%   |
| Maxtor              | 1        | 1      | 3.85%   |
| Hitachi             | 1        | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 31     | 69.7%   |
| SSD  | 10       | 10     | 30.3%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| SPCC M.2 PCIe SSD 2TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| SPCC   | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 151      | 355    | 53.74%  |
| Works    | 99       | 256    | 35.23%  |
| Malfunc  | 30       | 41     | 10.68%  |
| Failed   | 1        | 1      | 0.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 127      | 29.53%  |
| AMD                            | 115      | 26.74%  |
| Samsung Electronics            | 73       | 16.98%  |
| SanDisk                        | 29       | 6.74%   |
| Phison Electronics             | 17       | 3.95%   |
| ASMedia Technology             | 13       | 3.02%   |
| Kingston Technology Company    | 11       | 2.56%   |
| Micron/Crucial Technology      | 6        | 1.4%    |
| Marvell Technology Group       | 6        | 1.4%    |
| ADATA Technology               | 6        | 1.4%    |
| Toshiba America Info Systems   | 3        | 0.7%    |
| Silicon Motion                 | 3        | 0.7%    |
| Realtek Semiconductor          | 3        | 0.7%    |
| VIA Technologies               | 2        | 0.47%   |
| MAXIO Technology (Hangzhou)    | 2        | 0.47%   |
| LSI Logic / Symbios Logic      | 2        | 0.47%   |
| Lite-On Technology             | 2        | 0.47%   |
| JMicron Technology             | 2        | 0.47%   |
| Broadcom / LSI                 | 2        | 0.47%   |
| Solidigm                       | 1        | 0.23%   |
| Solid State Storage Technology | 1        | 0.23%   |
| SK hynix                       | 1        | 0.23%   |
| Seagate Technology             | 1        | 0.23%   |
| Nvidia                         | 1        | 0.23%   |
| Biwin Storage Technology       | 1        | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 50       | 10.06%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 45       | 9.05%   |
| AMD 400 Series Chipset SATA Controller                                         | 30       | 6.04%   |
| AMD 500 Series Chipset SATA Controller                                         | 23       | 4.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 20       | 4.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 16       | 3.22%   |
| AMD SATA controller                                                            | 15       | 3.02%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 13       | 2.62%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 13       | 2.62%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 11       | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11       | 2.21%   |
| Intel SATA Controller [RAID mode]                                              | 10       | 2.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10       | 2.01%   |
| SanDisk Non-Volatile memory controller                                         | 9        | 1.81%   |
| Phison E12 NVMe Controller                                                     | 9        | 1.81%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9        | 1.81%   |
| Samsung NVMe SSD Controller 980                                                | 7        | 1.41%   |
| Kingston Company Company Non-Volatile memory controller                        | 7        | 1.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6        | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6        | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6        | 1.21%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5        | 1.01%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 5        | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 5        | 1.01%   |
| AMD FCH SATA Controller D                                                      | 5        | 1.01%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 5        | 1.01%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 4        | 0.8%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4        | 0.8%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 4        | 0.8%    |
| Intel SSD 660P Series                                                          | 4        | 0.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 4        | 0.8%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 0.8%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3        | 0.6%    |
| Phison PS5013 E13 NVMe Controller                                              | 3        | 0.6%    |
| Phison E16 PCIe4 NVMe Controller                                               | 3        | 0.6%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 3        | 0.6%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3        | 0.6%    |
| AMD X370 Series Chipset SATA Controller                                        | 3        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 214      | 51.07%  |
| NVMe | 145      | 34.61%  |
| IDE  | 29       | 6.92%   |
| RAID | 26       | 6.21%   |
| SAS  | 4        | 0.95%   |
| SCSI | 1        | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 125      | 51.02%  |
| AMD    | 120      | 48.98%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 13       | 5.31%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 8        | 3.27%   |
| AMD Ryzen 9 7950X 16-Core Processor     | 7        | 2.86%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 7        | 2.86%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 7        | 2.86%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 6        | 2.45%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 5        | 2.04%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 5        | 2.04%   |
| AMD Ryzen 5 7600X 6-Core Processor      | 5        | 2.04%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 5        | 2.04%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 4        | 1.63%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 4        | 1.63%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 4        | 1.63%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 4        | 1.63%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 4        | 1.63%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 3        | 1.22%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 3        | 1.22%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 3        | 1.22%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 3        | 1.22%   |
| Intel 12th Gen Core i9-12900K           | 3        | 1.22%   |
| Intel 12th Gen Core i7-12700            | 3        | 1.22%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 3        | 1.22%   |
| AMD Ryzen 7 3800X 8-Core Processor      | 3        | 1.22%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 3        | 1.22%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 2        | 0.82%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 2        | 0.82%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 2        | 0.82%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2        | 0.82%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 2        | 0.82%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 2        | 0.82%   |
| Intel Core i7-3770S CPU @ 3.10GHz       | 2        | 0.82%   |
| Intel Core i7-10700K CPU @ 3.80GHz      | 2        | 0.82%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2        | 0.82%   |
| Intel 12th Gen Core i5-12600K           | 2        | 0.82%   |
| Intel 12th Gen Core i3-12100F           | 2        | 0.82%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 2        | 0.82%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 2        | 0.82%   |
| AMD Ryzen 7 7700X 8-Core Processor      | 2        | 0.82%   |
| AMD Ryzen 7 5800X3D 8-Core Processor    | 2        | 0.82%   |
| AMD Ryzen 7 1700 Eight-Core Processor   | 2        | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 48       | 19.59%  |
| Intel Core i7           | 45       | 18.37%  |
| Intel Core i5           | 28       | 11.43%  |
| AMD Ryzen 7             | 27       | 11.02%  |
| AMD Ryzen 9             | 22       | 8.98%   |
| Other                   | 18       | 7.35%   |
| Intel Xeon              | 9        | 3.67%   |
| Intel Core i3           | 9        | 3.67%   |
| AMD FX                  | 8        | 3.27%   |
| Intel Core 2 Quad       | 4        | 1.63%   |
| Intel Pentium Dual-Core | 3        | 1.22%   |
| Intel Core i9           | 3        | 1.22%   |
| AMD Ryzen 3             | 3        | 1.22%   |
| AMD Ryzen Threadripper  | 2        | 0.82%   |
| AMD A4                  | 2        | 0.82%   |
| AMD A10                 | 2        | 0.82%   |
| Intel Pentium Gold      | 1        | 0.41%   |
| Intel Pentium Dual      | 1        | 0.41%   |
| Intel Pentium           | 1        | 0.41%   |
| Intel Core 2 Duo        | 1        | 0.41%   |
| Intel Celeron           | 1        | 0.41%   |
| Intel Atom              | 1        | 0.41%   |
| AMD Ryzen 3 PRO         | 1        | 0.41%   |
| AMD PRO A10             | 1        | 0.41%   |
| AMD Athlon II X4        | 1        | 0.41%   |
| AMD Athlon II X2        | 1        | 0.41%   |
| AMD A8                  | 1        | 0.41%   |
| AMD A6                  | 1        | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 74       | 30.2%   |
| 6      | 61       | 24.9%   |
| 8      | 45       | 18.37%  |
| 2      | 22       | 8.98%   |
| 12     | 16       | 6.53%   |
| 16     | 15       | 6.12%   |
| 10     | 5        | 2.04%   |
| 24     | 2        | 0.82%   |
| 3      | 2        | 0.82%   |
| 32     | 1        | 0.41%   |
| 14     | 1        | 0.41%   |
| 1      | 1        | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 242      | 98.78%  |
| 2      | 3        | 1.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 183      | 74.69%  |
| 1      | 62       | 25.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 245      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 24       | 9.8%    |
| 0x306c3    | 16       | 6.53%   |
| 0x306a9    | 13       | 5.31%   |
| 0x0a601203 | 11       | 4.49%   |
| 0x0a201016 | 11       | 4.49%   |
| 0x906ed    | 9        | 3.67%   |
| 0x906ea    | 9        | 3.67%   |
| 0x90672    | 9        | 3.67%   |
| 0x0a50000d | 9        | 3.67%   |
| 0x506e3    | 8        | 3.27%   |
| 0x0a20120a | 8        | 3.27%   |
| Unknown    | 8        | 3.27%   |
| 0x206a7    | 7        | 2.86%   |
| 0x906e9    | 6        | 2.45%   |
| 0x1067a    | 6        | 2.45%   |
| 0xa0655    | 5        | 2.04%   |
| 0x206d7    | 5        | 2.04%   |
| 0x0a50000c | 5        | 2.04%   |
| 0x08701013 | 5        | 2.04%   |
| 0x0800820d | 5        | 2.04%   |
| 0x06000822 | 5        | 2.04%   |
| 0x0a601201 | 4        | 1.63%   |
| 0x0a201009 | 4        | 1.63%   |
| 0xa0671    | 3        | 1.22%   |
| 0x90675    | 3        | 1.22%   |
| 0x08108109 | 3        | 1.22%   |
| 0x06001119 | 3        | 1.22%   |
| 0xb0671    | 2        | 0.82%   |
| 0xa0653    | 2        | 0.82%   |
| 0x906ec    | 2        | 0.82%   |
| 0x6fb      | 2        | 0.82%   |
| 0x306f2    | 2        | 0.82%   |
| 0x206c2    | 2        | 0.82%   |
| 0x0a201204 | 2        | 0.82%   |
| 0x08101016 | 2        | 0.82%   |
| 0x08001138 | 2        | 0.82%   |
| 0x906eb    | 1        | 0.41%   |
| 0x6fd      | 1        | 0.41%   |
| 0x50657    | 1        | 0.41%   |
| 0x30678    | 1        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 41       | 16.73%  |
| Zen 2            | 33       | 13.47%  |
| KabyLake         | 28       | 11.43%  |
| Haswell          | 18       | 7.35%   |
| Unknown          | 16       | 6.53%   |
| Alderlake Hybrid | 14       | 5.71%   |
| IvyBridge        | 13       | 5.31%   |
| SandyBridge      | 12       | 4.9%    |
| Skylake          | 10       | 4.08%   |
| Piledriver       | 10       | 4.08%   |
| Zen+             | 9        | 3.67%   |
| Penryn           | 8        | 3.27%   |
| CometLake        | 7        | 2.86%   |
| Zen              | 5        | 2.04%   |
| Westmere         | 4        | 1.63%   |
| Icelake          | 3        | 1.22%   |
| Core             | 3        | 1.22%   |
| Nehalem          | 2        | 0.82%   |
| Excavator        | 2        | 0.82%   |
| Steamroller      | 1        | 0.41%   |
| Silvermont       | 1        | 0.41%   |
| K10 Llano        | 1        | 0.41%   |
| K10              | 1        | 0.41%   |
| Jaguar           | 1        | 0.41%   |
| Bulldozer        | 1        | 0.41%   |
| Bonnell          | 1        | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 115      | 43.56%  |
| AMD               | 106      | 40.15%  |
| Intel             | 42       | 15.91%  |
| ASPEED Technology | 1        | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 19       | 6.86%   |
| AMD Raphael                                                                 | 14       | 5.05%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 13       | 4.69%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 11       | 3.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 11       | 3.97%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 7        | 2.53%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 6        | 2.17%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 6        | 2.17%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 6        | 2.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 2.17%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 2.17%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 1.81%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 1.81%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 1.44%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 1.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.44%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 4        | 1.44%   |
| Intel AlderLake-S GT1                                                       | 4        | 1.44%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.08%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 1.08%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 3        | 1.08%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.08%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 1.08%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 1.08%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 3        | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 1.08%   |
| Intel HD Graphics 630                                                       | 3        | 1.08%   |
| Intel HD Graphics 530                                                       | 3        | 1.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 1.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.08%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 1.08%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 1.08%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.72%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.72%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.72%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.72%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 0.72%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Nvidia              | 101      | 41.22%  |
| 1 x AMD                 | 90       | 36.73%  |
| 1 x Intel               | 30       | 12.24%  |
| 2 x AMD                 | 10       | 4.08%   |
| Intel + Nvidia          | 6        | 2.45%   |
| AMD + Nvidia            | 5        | 2.04%   |
| 2 x Nvidia + 1 x ASPEED | 1        | 0.41%   |
| 2 x Nvidia              | 1        | 0.41%   |
| 2 x Intel               | 1        | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 174      | 71.02%  |
| Proprietary | 64       | 26.12%  |
| Unknown     | 7        | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 66       | 26.72%  |
| 7.01-8.0   | 57       | 23.08%  |
| 1.01-2.0   | 30       | 12.15%  |
| 3.01-4.0   | 24       | 9.72%   |
| 8.01-16.0  | 21       | 8.5%    |
| 0.01-0.5   | 19       | 7.69%   |
| 0.51-1.0   | 18       | 7.29%   |
| 5.01-6.0   | 9        | 3.64%   |
| 2.01-3.0   | 2        | 0.81%   |
| 16.01-24.0 | 1        | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 42       | 15.16%  |
| Goldstar             | 39       | 14.08%  |
| Dell                 | 36       | 13%     |
| Hewlett-Packard      | 25       | 9.03%   |
| AOC                  | 15       | 5.42%   |
| Acer                 | 15       | 5.42%   |
| BenQ                 | 13       | 4.69%   |
| ASUSTek Computer     | 10       | 3.61%   |
| Philips              | 9        | 3.25%   |
| Ancor Communications | 9        | 3.25%   |
| Sceptre Tech         | 7        | 2.53%   |
| MSI                  | 5        | 1.81%   |
| Lenovo               | 5        | 1.81%   |
| Iiyama               | 4        | 1.44%   |
| Gigabyte Technology  | 4        | 1.44%   |
| Eizo                 | 4        | 1.44%   |
| Pixio                | 3        | 1.08%   |
| Mi                   | 3        | 1.08%   |
| ViewSonic            | 2        | 0.72%   |
| Sony                 | 2        | 0.72%   |
| NEC Computers        | 2        | 0.72%   |
| Belinea              | 2        | 0.72%   |
| Vizio                | 1        | 0.36%   |
| USR                  | 1        | 0.36%   |
| Unknown              | 1        | 0.36%   |
| Panasonic            | 1        | 0.36%   |
| ONN                  | 1        | 0.36%   |
| KTC                  | 1        | 0.36%   |
| JRY                  | 1        | 0.36%   |
| InnoView             | 1        | 0.36%   |
| HVR                  | 1        | 0.36%   |
| HUAWEI               | 1        | 0.36%   |
| Hitachi              | 1        | 0.36%   |
| HannStar             | 1        | 0.36%   |
| Haier                | 1        | 0.36%   |
| GMX                  | 1        | 0.36%   |
| GDH                  | 1        | 0.36%   |
| FUR                  | 1        | 0.36%   |
| DTV                  | 1        | 0.36%   |
| CHE                  | 1        | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 4        | 1.35%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 3        | 1.01%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 560x300mm 25.0-inch         | 2        | 0.67%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 2        | 0.67%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 597x336mm 27.0-inch | 2        | 0.67%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2        | 0.67%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                       | 2        | 0.67%   |
| Hewlett-Packard 2511 HWP293E 1920x1080 550x310mm 24.9-inch             | 2        | 0.67%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 2        | 0.67%   |
| Hewlett-Packard 2311 HWP293B 1920x1080 509x286mm 23.0-inch             | 2        | 0.67%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 2        | 0.67%   |
| Goldstar UltraFine GSM5B74 3840x2160 600x340mm 27.2-inch               | 2        | 0.67%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                   | 2        | 0.67%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 2        | 0.67%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                  | 2        | 0.67%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 0.67%   |
| Dell U2713HM DEL407F 1920x1080 597x336mm 27.0-inch                     | 2        | 0.67%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                      | 2        | 0.67%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                      | 2        | 0.67%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                      | 2        | 0.67%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2        | 0.67%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                       | 2        | 0.67%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 2        | 0.67%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 2        | 0.67%   |
| Acer VG240Y S ACR0750 1920x1080 527x296mm 23.8-inch                    | 2        | 0.67%   |
| Vizio E321VL VIZ0083 1366x768 700x390mm 31.5-inch                      | 1        | 0.34%   |
| ViewSonic XG270QC VSCC438 2560x1440 597x336mm 27.0-inch                | 1        | 0.34%   |
| ViewSonic VX3418-2KPC VSC613B 3440x1440 797x334mm 34.0-inch            | 1        | 0.34%   |
| USR GSV26 PASS USR0100 1920x1080 708x398mm 32.0-inch                   | 1        | 0.34%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 0.34%   |
| Sony TV SNY02A2 1360x768                                               | 1        | 0.34%   |
| Sony BM320 SNY050A 1920x1080 708x399mm 32.0-inch                       | 1        | 0.34%   |
| Sceptre Tech U65 SPT19A1 3840x2160 575x323mm 26.0-inch                 | 1        | 0.34%   |
| Sceptre Tech Sceptre M27 SPT0ACD 1920x1080 598x336mm 27.0-inch         | 1        | 0.34%   |
| Sceptre Tech Sceptre K27 SPT0AA4 1920x1080 597x336mm 27.0-inch         | 1        | 0.34%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch         | 1        | 0.34%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch         | 1        | 0.34%   |
| Sceptre Tech E20 SPT080D 1600x900 434x236mm 19.4-inch                  | 1        | 0.34%   |
| Sceptre Tech E16 SPT0673 1366x768 413x234mm 18.7-inch                  | 1        | 0.34%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 1        | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 121      | 45.32%  |
| 3840x2160 (4K)     | 47       | 17.6%   |
| 2560x1440 (QHD)    | 37       | 13.86%  |
| 3440x1440          | 15       | 5.62%   |
| 2560x1080          | 7        | 2.62%   |
| 1680x1050 (WSXGA+) | 7        | 2.62%   |
| 1280x1024 (SXGA)   | 6        | 2.25%   |
| 1920x1200 (WUXGA)  | 4        | 1.5%    |
| 1366x768 (WXGA)    | 4        | 1.5%    |
| 1600x900 (HD+)     | 3        | 1.12%   |
| 1440x900 (WXGA+)   | 3        | 1.12%   |
| 1360x768           | 3        | 1.12%   |
| 2560x1600          | 2        | 0.75%   |
| 1600x1200          | 2        | 0.75%   |
| 3840x1600          | 1        | 0.37%   |
| 3120x1600          | 1        | 0.37%   |
| 2560x2880          | 1        | 0.37%   |
| 2288x1287          | 1        | 0.37%   |
| 2160x1200          | 1        | 0.37%   |
| Unknown            | 1        | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 69       | 24.47%  |
| 24      | 43       | 15.25%  |
| 23      | 37       | 13.12%  |
| 21      | 24       | 8.51%   |
| 31      | 22       | 7.8%    |
| 34      | 20       | 7.09%   |
| Unknown | 7        | 2.48%   |
| 32      | 6        | 2.13%   |
| 25      | 6        | 2.13%   |
| 20      | 6        | 2.13%   |
| 19      | 6        | 2.13%   |
| 26      | 5        | 1.77%   |
| 84      | 4        | 1.42%   |
| 22      | 4        | 1.42%   |
| 29      | 3        | 1.06%   |
| 28      | 3        | 1.06%   |
| 54      | 2        | 0.71%   |
| 36      | 2        | 0.71%   |
| 18      | 2        | 0.71%   |
| 15      | 2        | 0.71%   |
| 142     | 1        | 0.35%   |
| 72      | 1        | 0.35%   |
| 52      | 1        | 0.35%   |
| 48      | 1        | 0.35%   |
| 44      | 1        | 0.35%   |
| 42      | 1        | 0.35%   |
| 39      | 1        | 0.35%   |
| 37      | 1        | 0.35%   |
| 33      | 1        | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 138      | 51.69%  |
| 601-700        | 36       | 13.48%  |
| 401-500        | 36       | 13.48%  |
| 701-800        | 29       | 10.86%  |
| Unknown        | 7        | 2.62%   |
| 351-400        | 5        | 1.87%   |
| 1501-2000      | 5        | 1.87%   |
| 1001-1500      | 4        | 1.5%    |
| 901-1000       | 3        | 1.12%   |
| 301-350        | 2        | 0.75%   |
| More than 2000 | 1        | 0.37%   |
| 801-900        | 1        | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 193      | 78.46%  |
| 21/9    | 23       | 9.35%   |
| 16/10   | 17       | 6.91%   |
| 5/4     | 5        | 2.03%   |
| 4/3     | 3        | 1.22%   |
| Unknown | 3        | 1.22%   |
| 1.00    | 1        | 0.41%   |
| 0.89    | 1        | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 85       | 30.47%  |
| 301-350        | 71       | 25.45%  |
| 351-500        | 53       | 19%     |
| 251-300        | 22       | 7.89%   |
| 151-200        | 22       | 7.89%   |
| More than 1000 | 10       | 3.58%   |
| Unknown        | 7        | 2.51%   |
| 501-1000       | 6        | 2.15%   |
| 101-110        | 2        | 0.72%   |
| 141-150        | 1        | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 141      | 54.65%  |
| 101-120 | 62       | 24.03%  |
| 121-160 | 24       | 9.3%    |
| 161-240 | 14       | 5.43%   |
| 1-50    | 10       | 3.88%   |
| Unknown | 7        | 2.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 172      | 70.2%   |
| 2     | 55       | 22.45%  |
| 3     | 9        | 3.67%   |
| 0     | 8        | 3.27%   |
| 4     | 1        | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 143      | 40.28%  |
| Intel                         | 129      | 36.34%  |
| MediaTek                      | 17       | 4.79%   |
| Qualcomm Atheros              | 13       | 3.66%   |
| TP-Link                       | 11       | 3.1%    |
| Broadcom                      | 9        | 2.54%   |
| Ralink Technology             | 6        | 1.69%   |
| Google                        | 4        | 1.13%   |
| Aquantia                      | 4        | 1.13%   |
| Ralink                        | 3        | 0.85%   |
| Microsoft                     | 2        | 0.56%   |
| D-Link                        | 2        | 0.56%   |
| Xiaomi                        | 1        | 0.28%   |
| Samsung Electronics           | 1        | 0.28%   |
| OnePlus Technology (Shenzhen) | 1        | 0.28%   |
| NetGear                       | 1        | 0.28%   |
| Microchip Technology          | 1        | 0.28%   |
| Mellanox Technologies         | 1        | 0.28%   |
| Marvell Technology Group      | 1        | 0.28%   |
| InterBiometrics               | 1        | 0.28%   |
| Conexant Systems              | 1        | 0.28%   |
| Broadcom Limited              | 1        | 0.28%   |
| Bose                          | 1        | 0.28%   |
| Arduino SA                    | 1        | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 104      | 25.49%  |
| Realtek RTL8125 2.5GbE Controller                                   | 32       | 7.84%   |
| Intel Wi-Fi 6 AX200                                                 | 27       | 6.62%   |
| Intel I211 Gigabit Network Connection                               | 24       | 5.88%   |
| Intel Ethernet Controller I225-V                                    | 20       | 4.9%    |
| Intel Ethernet Connection (2) I219-V                                | 14       | 3.43%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 12       | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 11       | 2.7%    |
| Intel Wireless-AC 9260                                              | 7        | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 7        | 1.72%   |
| Intel Ethernet Connection (7) I219-V                                | 6        | 1.47%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 6        | 1.47%   |
| Intel 82574L Gigabit Network Connection                             | 6        | 1.47%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 5        | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 4        | 0.98%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 3        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                               | 3        | 0.74%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 2        | 0.49%   |
| TP-Link Archer T4U ver.3                                            | 2        | 0.49%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 2        | 0.49%   |
| TP-Link 802.11ac NIC                                                | 2        | 0.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2        | 0.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 0.49%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 2        | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2        | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 2        | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 2        | 0.49%   |
| Intel Ethernet Connection I217-LM                                   | 2        | 0.49%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.49%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.49%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 0.49%   |
| Google Pixel 6 Pro                                                  | 2        | 0.49%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                     | 2        | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.25%   |
| TP-Link USB 10/100 LAN                                              | 1        | 0.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 56       | 45.16%  |
| Realtek Semiconductor | 18       | 14.52%  |
| MediaTek              | 17       | 13.71%  |
| TP-Link               | 10       | 8.06%   |
| Ralink Technology     | 6        | 4.84%   |
| Qualcomm Atheros      | 6        | 4.84%   |
| Ralink                | 3        | 2.42%   |
| Microsoft             | 2        | 1.61%   |
| D-Link                | 2        | 1.61%   |
| Broadcom              | 2        | 1.61%   |
| NetGear               | 1        | 0.81%   |
| Broadcom Limited      | 1        | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 27       | 21.6%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 12       | 9.6%    |
| Intel Wireless-AC 9260                                        | 7        | 5.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 7        | 5.6%    |
| Intel Alder Lake-S PCH CNVi WiFi                              | 6        | 4.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 5        | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 4        | 3.2%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 3        | 2.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 2        | 1.6%    |
| TP-Link Archer T4U ver.3                                      | 2        | 1.6%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 2        | 1.6%    |
| TP-Link 802.11ac NIC                                          | 2        | 1.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2        | 1.6%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter             | 2        | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2        | 1.6%    |
| Intel Tiger Lake PCH CNVi WiFi                                | 2        | 1.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1        | 0.8%    |
| TP-Link 802.11ac WLAN Adapter                                 | 1        | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1        | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1        | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1        | 0.8%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter           | 1        | 0.8%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1        | 0.8%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 1        | 0.8%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1        | 0.8%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 1        | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                    | 1        | 0.8%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1        | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1        | 0.8%    |
| Realtek 8821CE Wireless LAN 802.11ac PCIe NIC                 | 1        | 0.8%    |
| Realtek 802.11n WLAN Adapter                                  | 1        | 0.8%    |
| Ralink RT5572 Wireless Adapter                                | 1        | 0.8%    |
| Ralink RT5370 Wireless Adapter                                | 1        | 0.8%    |
| Ralink RT3072 Wireless Adapter                                | 1        | 0.8%    |
| Ralink MT7601U Wireless Adapter                               | 1        | 0.8%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1        | 0.8%    |
| Ralink RT2800 802.11n PCI                                     | 1        | 0.8%    |
| Ralink RT2561/RT61 rev B 802.11g                              | 1        | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1        | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 137      | 51.5%   |
| Intel                         | 101      | 37.97%  |
| Qualcomm Atheros              | 7        | 2.63%   |
| Broadcom                      | 7        | 2.63%   |
| Google                        | 4        | 1.5%    |
| Aquantia                      | 4        | 1.5%    |
| Xiaomi                        | 1        | 0.38%   |
| TP-Link                       | 1        | 0.38%   |
| Samsung Electronics           | 1        | 0.38%   |
| OnePlus Technology (Shenzhen) | 1        | 0.38%   |
| Mellanox Technologies         | 1        | 0.38%   |
| Marvell Technology Group      | 1        | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 104      | 37.41%  |
| Realtek RTL8125 2.5GbE Controller                                   | 32       | 11.51%  |
| Intel I211 Gigabit Network Connection                               | 24       | 8.63%   |
| Intel Ethernet Controller I225-V                                    | 20       | 7.19%   |
| Intel Ethernet Connection (2) I219-V                                | 14       | 5.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 11       | 3.96%   |
| Intel Ethernet Connection (7) I219-V                                | 6        | 2.16%   |
| Intel 82574L Gigabit Network Connection                             | 6        | 2.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3        | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                               | 3        | 1.08%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 1.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2        | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 2        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.72%   |
| Intel Ethernet Connection I217-LM                                   | 2        | 0.72%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.72%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 0.72%   |
| Google Pixel 6 Pro                                                  | 2        | 0.72%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                     | 2        | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.36%   |
| TP-Link USB 10/100 LAN                                              | 1        | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.36%   |
| Realtek USB 10/100/1G/2.5G LAN                                      | 1        | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 1        | 0.36%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.36%   |
| OnePlus (Shenzhen) OnePlus                                          | 1        | 0.36%   |
| Mellanox MT27500 Family [ConnectX-3]                                | 1        | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.36%   |
| Intel I210 Gigabit Network Connection                               | 1        | 0.36%   |
| Intel Ethernet Controller X550                                      | 1        | 0.36%   |
| Intel Ethernet Connection I217-V                                    | 1        | 0.36%   |
| Intel Ethernet Connection (7) I219-LM                               | 1        | 0.36%   |
| Intel Ethernet Connection (17) I219-V                               | 1        | 0.36%   |
| Intel Ethernet Connection (14) I219-LM                              | 1        | 0.36%   |
| Intel Ethernet Connection (10) I219-V                               | 1        | 0.36%   |
| Intel 82579V Gigabit Network Connection                             | 1        | 0.36%   |
| Intel 82578DM Gigabit Network Connection                            | 1        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 243      | 65.85%  |
| WiFi     | 121      | 32.79%  |
| Modem    | 4        | 1.08%   |
| Unknown  | 1        | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 198      | 74.72%  |
| WiFi     | 67       | 25.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 136      | 55.51%  |
| 2     | 88       | 35.92%  |
| 3     | 18       | 7.35%   |
| 9     | 1        | 0.41%   |
| 5     | 1        | 0.41%   |
| 0     | 1        | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 175      | 71.14%  |
| Yes  | 71       | 28.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 53       | 43.44%  |
| Cambridge Silicon Radio         | 24       | 19.67%  |
| Realtek Semiconductor           | 10       | 8.2%    |
| MediaTek                        | 10       | 8.2%    |
| TP-Link                         | 8        | 6.56%   |
| Broadcom                        | 7        | 5.74%   |
| Foxconn / Hon Hai               | 4        | 3.28%   |
| Belkin Components               | 2        | 1.64%   |
| Qualcomm Atheros Communications | 1        | 0.82%   |
| IMC Networks                    | 1        | 0.82%   |
| HTC (High Tech Computer)        | 1        | 0.82%   |
| ASUSTek Computer                | 1        | 0.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 25       | 20.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 24       | 19.51%  |
| MediaTek Wireless_Device                                             | 10       | 8.13%   |
| Intel AX201 Bluetooth                                                | 9        | 7.32%   |
| TP-Link UB500 Adapter                                                | 8        | 6.5%    |
| Realtek Bluetooth Radio                                              | 8        | 6.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 7        | 5.69%   |
| Intel AX210 Bluetooth                                                | 7        | 5.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5        | 4.07%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 4        | 3.25%   |
| Foxconn / Hon Hai Wireless_Device                                    | 4        | 3.25%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 1.63%   |
| Intel Bluetooth wireless interface                                   | 2        | 1.63%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1        | 0.81%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.81%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.81%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.81%   |
| Broadcom BCM20702A0 Bluetooth                                        | 1        | 0.81%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.81%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 0.81%   |
| ASUS Bluetooth Device                                                | 1        | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 144      | 29.33%  |
| Intel                                | 120      | 24.44%  |
| Nvidia                               | 111      | 22.61%  |
| C-Media Electronics                  | 17       | 3.46%   |
| Logitech                             | 9        | 1.83%   |
| Creative Labs                        | 6        | 1.22%   |
| Razer USA                            | 5        | 1.02%   |
| SteelSeries ApS                      | 4        | 0.81%   |
| Sony                                 | 4        | 0.81%   |
| Kingston Technology                  | 4        | 0.81%   |
| Generalplus Technology               | 4        | 0.81%   |
| Focusrite-Novation                   | 4        | 0.81%   |
| ASUSTek Computer                     | 4        | 0.81%   |
| RODE Microphones                     | 3        | 0.61%   |
| JMTek                                | 3        | 0.61%   |
| GN Netcom                            | 3        | 0.61%   |
| Giga-Byte Technology                 | 3        | 0.61%   |
| Corsair                              | 3        | 0.61%   |
| XMOS                                 | 2        | 0.41%   |
| VIA Technologies                     | 2        | 0.41%   |
| Trust                                | 2        | 0.41%   |
| Texas Instruments                    | 2        | 0.41%   |
| Samson Technologies                  | 2        | 0.41%   |
| Plantronics                          | 2        | 0.41%   |
| Micro Star International             | 2        | 0.41%   |
| LG Electronics                       | 2        | 0.41%   |
| Antlion Audio                        | 2        | 0.41%   |
| ZOOM                                 | 1        | 0.2%    |
| Thesycon Systemsoftware & Consulting | 1        | 0.2%    |
| Studiologic                          | 1        | 0.2%    |
| Shure                                | 1        | 0.2%    |
| Samsung Electronics                  | 1        | 0.2%    |
| PreSonus Audio Electronics           | 1        | 0.2%    |
| miniDSP                              | 1        | 0.2%    |
| M-Audio                              | 1        | 0.2%    |
| iConnectivity                        | 1        | 0.2%    |
| GYROCOM C&C                          | 1        | 0.2%    |
| Goldvish                             | 1        | 0.2%    |
| Formosa Industrial Computing         | 1        | 0.2%    |
| FiiO Electronics Technology          | 1        | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 59       | 10.03%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 33       | 5.61%   |
| AMD Family 17h/19h HD Audio Controller                                     | 32       | 5.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 19       | 3.23%   |
| Intel 200 Series PCH HD Audio                                              | 16       | 2.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15       | 2.55%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 14       | 2.38%   |
| Intel Alder Lake-S HD Audio Controller                                     | 13       | 2.21%   |
| Intel Cannon Lake PCH cAVS                                                 | 12       | 2.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12       | 2.04%   |
| Nvidia GA104 High Definition Audio Controller                              | 11       | 1.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 1.87%   |
| Nvidia GM206 High Definition Audio Controller                              | 9        | 1.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9        | 1.53%   |
| Nvidia TU104 HD Audio Controller                                           | 8        | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 1.36%   |
| Nvidia GA106 High Definition Audio Controller                              | 8        | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 1.36%   |
| AMD Navi 10 HDMI Audio                                                     | 8        | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                              | 7        | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 1.19%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 1.19%   |
| Nvidia TU106 High Definition Audio Controller                              | 6        | 1.02%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 1.02%   |
| AMD FCH Azalia Controller                                                  | 6        | 1.02%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 1.02%   |
| Nvidia GK104 HDMI Audio Controller                                         | 5        | 0.85%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 0.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4        | 0.68%   |
| Nvidia High Definition Audio Controller                                    | 4        | 0.68%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 0.68%   |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 0.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 0.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 0.68%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.68%   |
| Intel Audio device                                                         | 4        | 0.68%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 27       | 22.13%  |
| G.Skill             | 23       | 18.85%  |
| Corsair             | 19       | 15.57%  |
| Crucial             | 10       | 8.2%    |
| Samsung Electronics | 9        | 7.38%   |
| Unknown             | 6        | 4.92%   |
| SK hynix            | 5        | 4.1%    |
| A-DATA Technology   | 5        | 4.1%    |
| Micron Technology   | 3        | 2.46%   |
| Unknown             | 3        | 2.46%   |
| Team                | 2        | 1.64%   |
| Patriot             | 2        | 1.64%   |
| Smart               | 1        | 0.82%   |
| Silicon Power       | 1        | 0.82%   |
| Qimonda             | 1        | 0.82%   |
| Nanya Technology    | 1        | 0.82%   |
| GOODRAM             | 1        | 0.82%   |
| Elpida              | 1        | 0.82%   |
| Apacer              | 1        | 0.82%   |
| AMD                 | 1        | 0.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 3        | 2.27%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 3        | 2.27%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 3        | 2.27%   |
| Unknown                                                  | 3        | 2.27%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s      | 2        | 1.52%   |
| Kingston RAM KF552C40-32 32GB DIMM DDR5 5200MT/s         | 2        | 1.52%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s         | 2        | 1.52%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s   | 2        | 1.52%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 1.52%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 1        | 0.76%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s       | 1        | 0.76%   |
| Team RAM TEAMGROUP-UD3-1333 4GB DIMM DDR3 1333MT/s       | 1        | 0.76%   |
| Smart RAM SH564128FH8N0TNSDR 4GB DIMM DDR3 1600MT/s      | 1        | 0.76%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s               | 1        | 0.76%   |
| SK hynix RAM HYMP151F72CP4N3-Y5 4GB FB-DIMM DDR2 667MT/s | 1        | 0.76%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s     | 1        | 0.76%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s     | 1        | 0.76%   |
| SK hynix RAM HMA81GU6MFR8N-UH 8GB DIMM DDR4 2400MT/s     | 1        | 0.76%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s     | 1        | 0.76%   |
| Silicon Power RAM Module 8GB DIMM DDR4 3200MT/s          | 1        | 0.76%   |
| Samsung RAM M395T5750GZ4-CE66 2GB FB-DIMM DDR2 667MT/s   | 1        | 0.76%   |
| Samsung RAM M395T5160QZ4-CE65 4GB FB-DIMM DDR2 667MT/s   | 1        | 0.76%   |
| Samsung RAM M395T5160DZ4-CE66 4GB FB-DIMM DDR2 667MT/s   | 1        | 0.76%   |
| Samsung RAM M395T5160CZ4-CE66 4GB FB-DIMM DDR2 667MT/s   | 1        | 0.76%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s   | 1        | 0.76%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 0.76%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 0.76%   |
| Samsung RAM M378B2873EH1-CH9 1GB DIMM DDR3 1334MT/s      | 1        | 0.76%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s     | 1        | 0.76%   |
| Qimonda RAM 72T128420HFN3SB 1GB FB-DIMM DDR2 667MT/s     | 1        | 0.76%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s      | 1        | 0.76%   |
| Patriot RAM 2800 C16 Series 8GB DIMM DDR4 3466MT/s       | 1        | 0.76%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2GB DIMM DDR3 1333MT/s       | 1        | 0.76%   |
| Micron RAM 18HF12872FD667D6D4 1GB FB-DIMM DDR2 667MT/s   | 1        | 0.76%   |
| Micron RAM 16ATF2G64AZ-2G1B1 16GB DIMM DDR4 2133MT/s     | 1        | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 60       | 54.55%  |
| DDR3    | 26       | 23.64%  |
| DDR5    | 16       | 14.55%  |
| DDR2    | 4        | 3.64%   |
| SDRAM   | 2        | 1.82%   |
| Unknown | 2        | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 105      | 97.22%  |
| FB-DIMM | 2        | 1.85%   |
| SODIMM  | 1        | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 42       | 38.53%  |
| 16384 | 29       | 26.61%  |
| 4096  | 17       | 15.6%   |
| 32768 | 11       | 10.09%  |
| 2048  | 7        | 6.42%   |
| 1024  | 3        | 2.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 15       | 12.82%  |
| 3600  | 13       | 11.11%  |
| 3200  | 12       | 10.26%  |
| 4800  | 9        | 7.69%   |
| 3466  | 8        | 6.84%   |
| 2400  | 7        | 5.98%   |
| 1333  | 7        | 5.98%   |
| 5200  | 4        | 3.42%   |
| 2133  | 4        | 3.42%   |
| 5600  | 3        | 2.56%   |
| 3866  | 3        | 2.56%   |
| 3000  | 3        | 2.56%   |
| 2667  | 3        | 2.56%   |
| 2666  | 3        | 2.56%   |
| 667   | 3        | 2.56%   |
| 3333  | 2        | 1.71%   |
| 1800  | 2        | 1.71%   |
| 800   | 2        | 1.71%   |
| 4133  | 1        | 0.85%   |
| 3800  | 1        | 0.85%   |
| 3733  | 1        | 0.85%   |
| 3666  | 1        | 0.85%   |
| 3400  | 1        | 0.85%   |
| 3100  | 1        | 0.85%   |
| 2800  | 1        | 0.85%   |
| 2132  | 1        | 0.85%   |
| 1867  | 1        | 0.85%   |
| 1866  | 1        | 0.85%   |
| 1334  | 1        | 0.85%   |
| 1066  | 1        | 0.85%   |
| 533   | 1        | 0.85%   |
| 400   | 1        | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 4        | 33.33%  |
| Brother Industries    | 3        | 25%     |
| Seiko Epson           | 1        | 8.33%   |
| Samsung Electronics   | 1        | 8.33%   |
| Prolific Technology   | 1        | 8.33%   |
| Lexmark International | 1        | 8.33%   |
| Canon                 | 1        | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Seiko Epson Printer           | 1        | 8.33%   |
| Samsung ML-2855 Series        | 1        | 8.33%   |
| Prolific PL2305 Parallel Port | 1        | 8.33%   |
| Lexmark International B2236dw | 1        | 8.33%   |
| HP LaserJet 1010              | 1        | 8.33%   |
| HP ENVY Photo 7800 series     | 1        | 8.33%   |
| HP DeskJet F300 series        | 1        | 8.33%   |
| HP DeskJet 3630 series        | 1        | 8.33%   |
| Canon LiDE 400                | 1        | 8.33%   |
| Brother MFC-7460DN            | 1        | 8.33%   |
| Brother HL-L2300D series      | 1        | 8.33%   |
| Brother DCP-L2510D series     | 1        | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 210 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 25       | 39.68%  |
| Microdia                    | 5        | 7.94%   |
| Microsoft                   | 4        | 6.35%   |
| Apple                       | 4        | 6.35%   |
| Samsung Electronics         | 3        | 4.76%   |
| LG Electronics              | 3        | 4.76%   |
| KYE Systems (Mouse Systems) | 3        | 4.76%   |
| Trust                       | 2        | 3.17%   |
| WCM_USB                     | 1        | 1.59%   |
| Sonix Technology            | 1        | 1.59%   |
| SN0002                      | 1        | 1.59%   |
| Smartronix                  | 1        | 1.59%   |
| SJ-180517-N                 | 1        | 1.59%   |
| Realtek Semiconductor       | 1        | 1.59%   |
| Hewlett-Packard             | 1        | 1.59%   |
| HD 2MP WEBCAM               | 1        | 1.59%   |
| Cubeternet                  | 1        | 1.59%   |
| Chicony Electronics         | 1        | 1.59%   |
| ASUSTek Computer            | 1        | 1.59%   |
| ARC International           | 1        | 1.59%   |
| Anker PowerConf C200        | 1        | 1.59%   |
| A4Tech                      | 1        | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech HD Webcam C525                         | 5        | 7.94%   |
| Microdia Webcam Vitade AF                       | 4        | 6.35%   |
| Apple iPhone5/5C/5S/6                           | 4        | 6.35%   |
| Samsung Galaxy A5 (MTP)                         | 3        | 4.76%   |
| Logitech Webcam C270                            | 3        | 4.76%   |
| Logitech HD Pro Webcam C920                     | 3        | 4.76%   |
| Logitech Webcam C930e                           | 2        | 3.17%   |
| Logitech Logi Webcam C920e                      | 2        | 3.17%   |
| Logitech C922 Pro Stream Webcam                 | 2        | 3.17%   |
| Logitech C920 PRO HD Webcam                     | 2        | 3.17%   |
| LG LG UltraFine Display Camera                  | 2        | 3.17%   |
| WCM_USB WEB CAM                                 | 1        | 1.59%   |
| Trust WB-6250X Webcam                           | 1        | 1.59%   |
| Trust Full HD Webcam                            | 1        | 1.59%   |
| Sonix USB Camera                                | 1        | 1.59%   |
| SN0002 1080P Web Camera                         | 1        | 1.59%   |
| Smartronix webcam                               | 1        | 1.59%   |
| SJ-180517-N 1080P Webcam                        | 1        | 1.59%   |
| Realtek NexiGo N660P FHD Webcam                 | 1        | 1.59%   |
| Microsoft MicrosoftÂ LifeCam Cinema            | 1        | 1.59%   |
| Microsoft LifeCam VX-5000                       | 1        | 1.59%   |
| Microsoft LifeCam VX-2000                       | 1        | 1.59%   |
| Microsoft LifeCam Studio                        | 1        | 1.59%   |
| Microdia USB 2.0 Camera                         | 1        | 1.59%   |
| Logitech Webcam C925e                           | 1        | 1.59%   |
| Logitech Webcam C250                            | 1        | 1.59%   |
| Logitech HD Webcam C615                         | 1        | 1.59%   |
| Logitech HD Webcam C510                         | 1        | 1.59%   |
| Logitech C930c                                  | 1        | 1.59%   |
| Logitech BRIO Ultra HD Webcam                   | 1        | 1.59%   |
| LG Optimus (Various Models) MTP Mode            | 1        | 1.59%   |
| KYE Systems (Mouse Systems) iSlim 320           | 1        | 1.59%   |
| KYE Systems (Mouse Systems) Genius WideCam F100 | 1        | 1.59%   |
| KYE Systems (Mouse Systems) FaceCam 2020        | 1        | 1.59%   |
| HP HD-4110 Webcam                               | 1        | 1.59%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                     | 1        | 1.59%   |
| Cubeternet Live Streaming USB Device            | 1        | 1.59%   |
| Chicony USB 2.0 Camera                          | 1        | 1.59%   |
| ASUS CU4K30 UVC UHD Video                       | 1        | 1.59%   |
| ARC International Camera                        | 1        | 1.59%   |

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
| 0     | 206      | 83.74%  |
| 1     | 30       | 12.2%   |
| 4     | 4        | 1.63%   |
| 3     | 3        | 1.22%   |
| 8     | 1        | 0.41%   |
| 5     | 1        | 0.41%   |
| 2     | 1        | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 12       | 21.43%  |
| Net/wireless             | 11       | 19.64%  |
| Sound                    | 10       | 17.86%  |
| Camera                   | 6        | 10.71%  |
| Multimedia controller    | 5        | 8.93%   |
| Storage/raid             | 3        | 5.36%   |
| Communication controller | 3        | 5.36%   |
| Network                  | 2        | 3.57%   |
| Unassigned class         | 1        | 1.79%   |
| Net/ethernet             | 1        | 1.79%   |
| Modem                    | 1        | 1.79%   |
| Bluetooth                | 1        | 1.79%   |

