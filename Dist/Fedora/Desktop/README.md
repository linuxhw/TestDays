Fedora - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 5044

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 0A98h                       | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [42932dd5fd](https://linux-hardware.org/?probe=42932dd5fd) | Dec 01, 2022 |
| ASUSTek       | PRIME X370-PRO              | [aa87dfdc13](https://linux-hardware.org/?probe=aa87dfdc13) | Dec 01, 2022 |
| MSI           | X99A RAIDER                 | [0e87a76042](https://linux-hardware.org/?probe=0e87a76042) | Dec 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [8a4813eec4](https://linux-hardware.org/?probe=8a4813eec4) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Gigabyte      | X570 GAMING X               | [7ea2de1a3b](https://linux-hardware.org/?probe=7ea2de1a3b) | Nov 30, 2022 |
| Unknown       | X99H                        | [b9e2236de7](https://linux-hardware.org/?probe=b9e2236de7) | Nov 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [a6a71120f2](https://linux-hardware.org/?probe=a6a71120f2) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9eabacd766](https://linux-hardware.org/?probe=9eabacd766) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [da83c13da3](https://linux-hardware.org/?probe=da83c13da3) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9f7438d5a3](https://linux-hardware.org/?probe=9f7438d5a3) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [459c2ba743](https://linux-hardware.org/?probe=459c2ba743) | Nov 30, 2022 |
| Gigabyte      | H77N-WIFI                   | [f4fa3a4e7f](https://linux-hardware.org/?probe=f4fa3a4e7f) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK S       | [2c5c1d6071](https://linux-hardware.org/?probe=2c5c1d6071) | Nov 30, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [bc3188dd75](https://linux-hardware.org/?probe=bc3188dd75) | Nov 29, 2022 |
| HP            | 3048h                       | [6f5a8d1a09](https://linux-hardware.org/?probe=6f5a8d1a09) | Nov 29, 2022 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6d835027fa](https://linux-hardware.org/?probe=6d835027fa) | Nov 29, 2022 |
| MSI           | X570-A PRO                  | [92ddd925db](https://linux-hardware.org/?probe=92ddd925db) | Nov 28, 2022 |
| ASUSTek       | GA15DH                      | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | [207d763813](https://linux-hardware.org/?probe=207d763813) | Nov 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [8fa53292bf](https://linux-hardware.org/?probe=8fa53292bf) | Nov 27, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [81a61c4765](https://linux-hardware.org/?probe=81a61c4765) | Nov 27, 2022 |
| Foxconn       | 2ABF                        | [d95233ff31](https://linux-hardware.org/?probe=d95233ff31) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [521f5c20a9](https://linux-hardware.org/?probe=521f5c20a9) | Nov 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [07363955de](https://linux-hardware.org/?probe=07363955de) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Gigabyte      | B550 GAMING X               | [b9264b2557](https://linux-hardware.org/?probe=b9264b2557) | Nov 26, 2022 |
| ASUSTek       | PRIME X370-PRO              | [5b0f04d592](https://linux-hardware.org/?probe=5b0f04d592) | Nov 25, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [33f5823764](https://linux-hardware.org/?probe=33f5823764) | Nov 25, 2022 |
| ASUSTek       | PRIME B360M-D               | [67a7943b8d](https://linux-hardware.org/?probe=67a7943b8d) | Nov 25, 2022 |
| Biostar       | H310MHC2                    | [49e09047c4](https://linux-hardware.org/?probe=49e09047c4) | Nov 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [6f867d822a](https://linux-hardware.org/?probe=6f867d822a) | Nov 25, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [45dc299d52](https://linux-hardware.org/?probe=45dc299d52) | Nov 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bf1722d4d6](https://linux-hardware.org/?probe=bf1722d4d6) | Nov 25, 2022 |
| MSI           | X99A RAIDER                 | [1c648060f6](https://linux-hardware.org/?probe=1c648060f6) | Nov 25, 2022 |
| MSI           | H81M-E33                    | [80ec8663ac](https://linux-hardware.org/?probe=80ec8663ac) | Nov 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [d6fe192013](https://linux-hardware.org/?probe=d6fe192013) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [ccf106edce](https://linux-hardware.org/?probe=ccf106edce) | Nov 24, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [b154300490](https://linux-hardware.org/?probe=b154300490) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [7f0ba24aad](https://linux-hardware.org/?probe=7f0ba24aad) | Nov 24, 2022 |
| ASUSTek       | GA15DH                      | [ec6d666a16](https://linux-hardware.org/?probe=ec6d666a16) | Nov 24, 2022 |
| Gigabyte      | GA-990XA-UD3                | [a5005bf517](https://linux-hardware.org/?probe=a5005bf517) | Nov 24, 2022 |
| MSI           | X99A RAIDER                 | [c1e62a557c](https://linux-hardware.org/?probe=c1e62a557c) | Nov 24, 2022 |
| ASRock        | B75 Pro3                    | [e359d0bd70](https://linux-hardware.org/?probe=e359d0bd70) | Nov 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ee5b760222](https://linux-hardware.org/?probe=ee5b760222) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [8de6a24029](https://linux-hardware.org/?probe=8de6a24029) | Nov 24, 2022 |
| Dell          | 0J3C2F A02                  | [0cfd78c6bb](https://linux-hardware.org/?probe=0cfd78c6bb) | Nov 23, 2022 |
| ASRock        | Z370 Pro4                   | [ced8851dc3](https://linux-hardware.org/?probe=ced8851dc3) | Nov 23, 2022 |
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
| ASUSTek       | M5A99FX PRO R2.0            | [990ff088e8](https://linux-hardware.org/?probe=990ff088e8) | Nov 22, 2022 |
| ASUSTek       | P6T DELUXE V2               | [d126214b62](https://linux-hardware.org/?probe=d126214b62) | Nov 22, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [4743344f41](https://linux-hardware.org/?probe=4743344f41) | Nov 22, 2022 |
| Dell          | 0GY6Y8 A02                  | [8789b14e39](https://linux-hardware.org/?probe=8789b14e39) | Nov 21, 2022 |
| HP            | 3647h                       | [8f77a73e9b](https://linux-hardware.org/?probe=8f77a73e9b) | Nov 21, 2022 |
| Gigabyte      | B75M-D3H                    | [ac4a817e75](https://linux-hardware.org/?probe=ac4a817e75) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f13d80cf0b](https://linux-hardware.org/?probe=f13d80cf0b) | Nov 21, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [8478dece38](https://linux-hardware.org/?probe=8478dece38) | Nov 21, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [34e6521bc8](https://linux-hardware.org/?probe=34e6521bc8) | Nov 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b41f6ec236](https://linux-hardware.org/?probe=b41f6ec236) | Nov 21, 2022 |
| ASUSTek       | PRIME Z270-A                | [540d321764](https://linux-hardware.org/?probe=540d321764) | Nov 21, 2022 |
| HP            | 18E7                        | [0b963b44fb](https://linux-hardware.org/?probe=0b963b44fb) | Nov 21, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [34f72bd414](https://linux-hardware.org/?probe=34f72bd414) | Nov 20, 2022 |
| Gigabyte      | H310M S2H x.x               | [97ea29ed26](https://linux-hardware.org/?probe=97ea29ed26) | Nov 20, 2022 |
| Dell          | 0HY9JP A02                  | [fa0e9792f0](https://linux-hardware.org/?probe=fa0e9792f0) | Nov 20, 2022 |
| MSI           | 990FXA-GD65                 | [d41acd5075](https://linux-hardware.org/?probe=d41acd5075) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [a28ef28876](https://linux-hardware.org/?probe=a28ef28876) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | [0735dabc9b](https://linux-hardware.org/?probe=0735dabc9b) | Nov 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d3412020ec](https://linux-hardware.org/?probe=d3412020ec) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK               | [8c271e833d](https://linux-hardware.org/?probe=8c271e833d) | Nov 20, 2022 |
| ASUSTek       | PRIME Z370-A                | [a890ae6d6c](https://linux-hardware.org/?probe=a890ae6d6c) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [f10fc36516](https://linux-hardware.org/?probe=f10fc36516) | Nov 19, 2022 |
| ASRock        | B450 Pro4                   | [cd0f63540b](https://linux-hardware.org/?probe=cd0f63540b) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [ecceccb3b7](https://linux-hardware.org/?probe=ecceccb3b7) | Nov 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d304f26226](https://linux-hardware.org/?probe=d304f26226) | Nov 19, 2022 |
| MSI           | H510M-A PRO                 | [1755321c80](https://linux-hardware.org/?probe=1755321c80) | Nov 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [050e6cfd68](https://linux-hardware.org/?probe=050e6cfd68) | Nov 19, 2022 |
| ASRock        | AD2700-ITX                  | [806ac66c75](https://linux-hardware.org/?probe=806ac66c75) | Nov 19, 2022 |
| ASUSTek       | Z170-K                      | [1af696c23c](https://linux-hardware.org/?probe=1af696c23c) | Nov 19, 2022 |
| ASUSTek       | Z97-P                       | [75748e49d9](https://linux-hardware.org/?probe=75748e49d9) | Nov 19, 2022 |
| Gigabyte      | X570 GAMING X               | [587db1b08f](https://linux-hardware.org/?probe=587db1b08f) | Nov 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [7de2db4d3a](https://linux-hardware.org/?probe=7de2db4d3a) | Nov 18, 2022 |
| Gigabyte      | M720-US3                    | [299b2cd745](https://linux-hardware.org/?probe=299b2cd745) | Nov 18, 2022 |
| Acer          | FMP55                       | [f35d63ca8b](https://linux-hardware.org/?probe=f35d63ca8b) | Nov 18, 2022 |
| ASRock        | X300-ITX                    | [54f7198f58](https://linux-hardware.org/?probe=54f7198f58) | Nov 18, 2022 |
| Gigabyte      | H61M-USB3V                  | [e034e5bbb2](https://linux-hardware.org/?probe=e034e5bbb2) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | [a8847bb3ad](https://linux-hardware.org/?probe=a8847bb3ad) | Nov 18, 2022 |
| Dell          | 0X30MX A00                  | [c3657c7f97](https://linux-hardware.org/?probe=c3657c7f97) | Nov 18, 2022 |
| ASRock        | X670E Pro RS                | [bfccdbd536](https://linux-hardware.org/?probe=bfccdbd536) | Nov 17, 2022 |
| ASUSTek       | H81M-R                      | [cd129bebe1](https://linux-hardware.org/?probe=cd129bebe1) | Nov 17, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [e9eb63ca62](https://linux-hardware.org/?probe=e9eb63ca62) | Nov 17, 2022 |
| MSI           | X99A RAIDER                 | [5d1e2af2ea](https://linux-hardware.org/?probe=5d1e2af2ea) | Nov 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4c86f7c670](https://linux-hardware.org/?probe=4c86f7c670) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9f45de6ee3](https://linux-hardware.org/?probe=9f45de6ee3) | Nov 17, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [cd01bd7dad](https://linux-hardware.org/?probe=cd01bd7dad) | Nov 16, 2022 |
| MSI           | B450M PRO-VDH MAX           | [cdf4d49427](https://linux-hardware.org/?probe=cdf4d49427) | Nov 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2eb90688b5](https://linux-hardware.org/?probe=2eb90688b5) | Nov 16, 2022 |
| MSI           | X99A RAIDER                 | [620dbe0a8f](https://linux-hardware.org/?probe=620dbe0a8f) | Nov 16, 2022 |
| ASUSTek       | B85M-E                      | [2455b541f5](https://linux-hardware.org/?probe=2455b541f5) | Nov 16, 2022 |
| Intel         | DX79SR AAG57199-200         | [b12b9ec8d5](https://linux-hardware.org/?probe=b12b9ec8d5) | Nov 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [9cd3d86efc](https://linux-hardware.org/?probe=9cd3d86efc) | Nov 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1472f0a14e](https://linux-hardware.org/?probe=1472f0a14e) | Nov 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [ea39f5300c](https://linux-hardware.org/?probe=ea39f5300c) | Nov 15, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [459c5879e6](https://linux-hardware.org/?probe=459c5879e6) | Nov 15, 2022 |
| Intel         | DB75EN AAG39650-400         | [07d6aa9adc](https://linux-hardware.org/?probe=07d6aa9adc) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [7bf6427590](https://linux-hardware.org/?probe=7bf6427590) | Nov 14, 2022 |
| Huanan        | X99-F8                      | [503cf4b0ea](https://linux-hardware.org/?probe=503cf4b0ea) | Nov 14, 2022 |
| Dell          | 06X1TJ A00                  | [4a19565db2](https://linux-hardware.org/?probe=4a19565db2) | Nov 14, 2022 |
| ASUSTek       | CM6870                      | [c050452a72](https://linux-hardware.org/?probe=c050452a72) | Nov 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5b9f10af19](https://linux-hardware.org/?probe=5b9f10af19) | Nov 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [c1044ebf60](https://linux-hardware.org/?probe=c1044ebf60) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [9d942ddc9c](https://linux-hardware.org/?probe=9d942ddc9c) | Nov 13, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [2c896d28a8](https://linux-hardware.org/?probe=2c896d28a8) | Nov 13, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [97bfce0a04](https://linux-hardware.org/?probe=97bfce0a04) | Nov 13, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [a84e5c2107](https://linux-hardware.org/?probe=a84e5c2107) | Nov 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [256503ef7e](https://linux-hardware.org/?probe=256503ef7e) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [2eacb090ee](https://linux-hardware.org/?probe=2eacb090ee) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [a35ca3673b](https://linux-hardware.org/?probe=a35ca3673b) | Nov 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | [c73b422075](https://linux-hardware.org/?probe=c73b422075) | Nov 12, 2022 |
| MSI           | X99A RAIDER                 | [dffde21ad4](https://linux-hardware.org/?probe=dffde21ad4) | Nov 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5006a2d188](https://linux-hardware.org/?probe=5006a2d188) | Nov 12, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [cedb086e46](https://linux-hardware.org/?probe=cedb086e46) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [6eedcdeb01](https://linux-hardware.org/?probe=6eedcdeb01) | Nov 11, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [022a97b52e](https://linux-hardware.org/?probe=022a97b52e) | Nov 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [3f11ca7016](https://linux-hardware.org/?probe=3f11ca7016) | Nov 11, 2022 |
| ASRock        | H81M-DGS R2.0               | [07bae444fc](https://linux-hardware.org/?probe=07bae444fc) | Nov 11, 2022 |
| MSI           | 2A9C                        | [a531fd4d8e](https://linux-hardware.org/?probe=a531fd4d8e) | Nov 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [578b9c0e61](https://linux-hardware.org/?probe=578b9c0e61) | Nov 11, 2022 |
| MSI           | 2A9C                        | [599470c2f4](https://linux-hardware.org/?probe=599470c2f4) | Nov 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a311d2c018](https://linux-hardware.org/?probe=a311d2c018) | Nov 11, 2022 |
| MSI           | X99A RAIDER                 | [b7d21d229b](https://linux-hardware.org/?probe=b7d21d229b) | Nov 11, 2022 |
| Dell          | 0DR845                      | [c4d2b18dd8](https://linux-hardware.org/?probe=c4d2b18dd8) | Nov 10, 2022 |
| MSI           | Z390-A PRO                  | [e851ddd11a](https://linux-hardware.org/?probe=e851ddd11a) | Nov 10, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [009f3d82e9](https://linux-hardware.org/?probe=009f3d82e9) | Nov 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [faf531627e](https://linux-hardware.org/?probe=faf531627e) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f49624457d](https://linux-hardware.org/?probe=f49624457d) | Nov 09, 2022 |
| Dell          | 0RW203 A00                  | [67fa42f70a](https://linux-hardware.org/?probe=67fa42f70a) | Nov 09, 2022 |
| ASRock        | H310M-STX                   | [cb421b22a5](https://linux-hardware.org/?probe=cb421b22a5) | Nov 09, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [f2afc66464](https://linux-hardware.org/?probe=f2afc66464) | Nov 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [226409c98f](https://linux-hardware.org/?probe=226409c98f) | Nov 09, 2022 |
| Foxconn       | H61M-S/H61M                 | [81b2006fd3](https://linux-hardware.org/?probe=81b2006fd3) | Nov 09, 2022 |
| ASRock        | Z77 Pro4-M                  | [3a4a75d603](https://linux-hardware.org/?probe=3a4a75d603) | Nov 08, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0b65e26932](https://linux-hardware.org/?probe=0b65e26932) | Nov 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | [f236aa0a8b](https://linux-hardware.org/?probe=f236aa0a8b) | Nov 08, 2022 |
| Dell          | 09WH54 A00                  | [c7723a2b2f](https://linux-hardware.org/?probe=c7723a2b2f) | Nov 07, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | [6987230f73](https://linux-hardware.org/?probe=6987230f73) | Nov 07, 2022 |
| Gigabyte      | X670 GAMING X AX            | [1a96ebec7a](https://linux-hardware.org/?probe=1a96ebec7a) | Nov 07, 2022 |
| ASUSTek       | PRIME Z370-A                | [d87a3e023a](https://linux-hardware.org/?probe=d87a3e023a) | Nov 07, 2022 |
| Gigabyte      | B450M GAMING                | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| Gigabyte      | A320M-H-CF                  | [fa33ccff27](https://linux-hardware.org/?probe=fa33ccff27) | Nov 05, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [55b349ab41](https://linux-hardware.org/?probe=55b349ab41) | Nov 05, 2022 |
| Dell          | 096JG8 A01                  | [e8a62297a5](https://linux-hardware.org/?probe=e8a62297a5) | Nov 05, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [16b0128664](https://linux-hardware.org/?probe=16b0128664) | Nov 05, 2022 |
| ASUSTek       | PRO H410T                   | [66a809ab24](https://linux-hardware.org/?probe=66a809ab24) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [02104ae91b](https://linux-hardware.org/?probe=02104ae91b) | Nov 05, 2022 |
| ASRock        | X570 Taichi                 | [d9902c03cb](https://linux-hardware.org/?probe=d9902c03cb) | Nov 05, 2022 |
| MSI           | X99A RAIDER                 | [95fb6a845e](https://linux-hardware.org/?probe=95fb6a845e) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [36e78b1c17](https://linux-hardware.org/?probe=36e78b1c17) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [56db615f30](https://linux-hardware.org/?probe=56db615f30) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [aa9fe4c05c](https://linux-hardware.org/?probe=aa9fe4c05c) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [108df7bc6d](https://linux-hardware.org/?probe=108df7bc6d) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a2c8fe2afa](https://linux-hardware.org/?probe=a2c8fe2afa) | Nov 05, 2022 |
| MSI           | Z390-A PRO                  | [5cfd4967b0](https://linux-hardware.org/?probe=5cfd4967b0) | Nov 05, 2022 |
| ASRock        | X370 Taichi                 | [02a767e075](https://linux-hardware.org/?probe=02a767e075) | Nov 04, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2c3ddc79ce](https://linux-hardware.org/?probe=2c3ddc79ce) | Nov 04, 2022 |
| HP            | 339A                        | [77ddeeda51](https://linux-hardware.org/?probe=77ddeeda51) | Nov 04, 2022 |
| HP            | 339A                        | [8ebb8b6522](https://linux-hardware.org/?probe=8ebb8b6522) | Nov 04, 2022 |
| Gigabyte      | H97-HD3                     | [bb8dbe6d52](https://linux-hardware.org/?probe=bb8dbe6d52) | Nov 04, 2022 |
| HP            | 8459                        | [378537c13c](https://linux-hardware.org/?probe=378537c13c) | Nov 04, 2022 |
| ASUSTek       | PRIME Z370-P II             | [1866954ec7](https://linux-hardware.org/?probe=1866954ec7) | Nov 04, 2022 |
| HP            | 2B05                        | [5c0a96cd5b](https://linux-hardware.org/?probe=5c0a96cd5b) | Nov 04, 2022 |
| HP            | 2B05                        | [95b5255056](https://linux-hardware.org/?probe=95b5255056) | Nov 04, 2022 |
| MSI           | X99A RAIDER                 | [b3eefc89d6](https://linux-hardware.org/?probe=b3eefc89d6) | Nov 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | [653a03dee6](https://linux-hardware.org/?probe=653a03dee6) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [f027f3a4e2](https://linux-hardware.org/?probe=f027f3a4e2) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [cb9374e939](https://linux-hardware.org/?probe=cb9374e939) | Nov 04, 2022 |
| ASUSTek       | PRIME Z270-P                | [ec0599883c](https://linux-hardware.org/?probe=ec0599883c) | Nov 03, 2022 |
| Gigabyte      | G41MT-D3                    | [921a646464](https://linux-hardware.org/?probe=921a646464) | Nov 03, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9bdccc90c4](https://linux-hardware.org/?probe=9bdccc90c4) | Nov 03, 2022 |
| MSI           | X99A RAIDER                 | [0036848bf2](https://linux-hardware.org/?probe=0036848bf2) | Nov 03, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [c9041d22be](https://linux-hardware.org/?probe=c9041d22be) | Nov 02, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [86bf890d23](https://linux-hardware.org/?probe=86bf890d23) | Nov 02, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| MSI           | X99A RAIDER                 | [36eda457da](https://linux-hardware.org/?probe=36eda457da) | Nov 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4e260473ba](https://linux-hardware.org/?probe=4e260473ba) | Nov 02, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9b093574b9](https://linux-hardware.org/?probe=9b093574b9) | Nov 02, 2022 |
| Gigabyte      | B550 UD AC                  | [c5a5219cf3](https://linux-hardware.org/?probe=c5a5219cf3) | Nov 01, 2022 |
| ASUSTek       | B150 PRO GAMING             | [b2229c56c4](https://linux-hardware.org/?probe=b2229c56c4) | Nov 01, 2022 |
| MSI           | H81M-E33                    | [ee4c33d7b1](https://linux-hardware.org/?probe=ee4c33d7b1) | Nov 01, 2022 |
| HP            | 339A                        | [68392c18c9](https://linux-hardware.org/?probe=68392c18c9) | Nov 01, 2022 |
| MSI           | X99A RAIDER                 | [2f3428a435](https://linux-hardware.org/?probe=2f3428a435) | Nov 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [cf7b016772](https://linux-hardware.org/?probe=cf7b016772) | Nov 01, 2022 |
| MSI           | PRO B660M-A DDR4            | [f6b6afc8a3](https://linux-hardware.org/?probe=f6b6afc8a3) | Nov 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [a2a8473e4b](https://linux-hardware.org/?probe=a2a8473e4b) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| Gigabyte      | B85M-D3V-A                  | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [479fdd085d](https://linux-hardware.org/?probe=479fdd085d) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [dfde89926c](https://linux-hardware.org/?probe=dfde89926c) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [135f93d663](https://linux-hardware.org/?probe=135f93d663) | Oct 31, 2022 |
| MSI           | X99A RAIDER                 | [2f41c9eaa5](https://linux-hardware.org/?probe=2f41c9eaa5) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5bd92395da](https://linux-hardware.org/?probe=5bd92395da) | Oct 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [4ac9bf1711](https://linux-hardware.org/?probe=4ac9bf1711) | Oct 31, 2022 |
| MSI           | B250M GAMING PRO            | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [4820bca604](https://linux-hardware.org/?probe=4820bca604) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [cdca8a4d95](https://linux-hardware.org/?probe=cdca8a4d95) | Oct 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [8e2ab3d61b](https://linux-hardware.org/?probe=8e2ab3d61b) | Oct 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c8392f24d9](https://linux-hardware.org/?probe=c8392f24d9) | Oct 30, 2022 |
| MSI           | X99A RAIDER                 | [7ddd09eeec](https://linux-hardware.org/?probe=7ddd09eeec) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H V2               | [ba5da6b270](https://linux-hardware.org/?probe=ba5da6b270) | Oct 29, 2022 |
| MSI           | X99A RAIDER                 | [782207dfcf](https://linux-hardware.org/?probe=782207dfcf) | Oct 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [75b050a9f0](https://linux-hardware.org/?probe=75b050a9f0) | Oct 29, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [ce9a718851](https://linux-hardware.org/?probe=ce9a718851) | Oct 28, 2022 |
| Gigabyte      | G41MT-D3                    | [2e4153161f](https://linux-hardware.org/?probe=2e4153161f) | Oct 28, 2022 |
| ASRock        | X99 Extreme4                | [72102d6890](https://linux-hardware.org/?probe=72102d6890) | Oct 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [38135da604](https://linux-hardware.org/?probe=38135da604) | Oct 28, 2022 |
| MSI           | H81M-E33                    | [f0613bfce8](https://linux-hardware.org/?probe=f0613bfce8) | Oct 27, 2022 |
| MSI           | B450M MORTAR                | [44e8a164d1](https://linux-hardware.org/?probe=44e8a164d1) | Oct 27, 2022 |
| Gigabyte      | H97N-WIFI                   | [aa2345213b](https://linux-hardware.org/?probe=aa2345213b) | Oct 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd9367f2b7](https://linux-hardware.org/?probe=bd9367f2b7) | Oct 27, 2022 |
| MSI           | X299 SLI PLUS               | [4b79f3c1e6](https://linux-hardware.org/?probe=4b79f3c1e6) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d2debd1dab](https://linux-hardware.org/?probe=d2debd1dab) | Oct 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [6c7c7fa216](https://linux-hardware.org/?probe=6c7c7fa216) | Oct 26, 2022 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | [2bed8fe9b1](https://linux-hardware.org/?probe=2bed8fe9b1) | Oct 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [317d318d85](https://linux-hardware.org/?probe=317d318d85) | Oct 26, 2022 |
| HP            | ProLiant ML350 G6           | [d080f0956b](https://linux-hardware.org/?probe=d080f0956b) | Oct 26, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [958c0a2ae7](https://linux-hardware.org/?probe=958c0a2ae7) | Oct 25, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [6896f337ab](https://linux-hardware.org/?probe=6896f337ab) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-P                | [0eb9c3ebff](https://linux-hardware.org/?probe=0eb9c3ebff) | Oct 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [0c63b974e1](https://linux-hardware.org/?probe=0c63b974e1) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [fbd1924bea](https://linux-hardware.org/?probe=fbd1924bea) | Oct 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | [055062356e](https://linux-hardware.org/?probe=055062356e) | Oct 25, 2022 |
| ASRock        | FM2A88M-HD+ R2.0            | [10e0a497e9](https://linux-hardware.org/?probe=10e0a497e9) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [82fb357322](https://linux-hardware.org/?probe=82fb357322) | Oct 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [db4db1b508](https://linux-hardware.org/?probe=db4db1b508) | Oct 25, 2022 |
| Gigabyte      | A520M DS3H                  | [88e45a4e65](https://linux-hardware.org/?probe=88e45a4e65) | Oct 25, 2022 |
| Acer          | Veriton M2631 V:1.0         | [1d5e3aa9f0](https://linux-hardware.org/?probe=1d5e3aa9f0) | Oct 25, 2022 |
| MSI           | MAG A520M VECTOR WIFI       | [91a8a52c4a](https://linux-hardware.org/?probe=91a8a52c4a) | Oct 25, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Core ... | [601e080563](https://linux-hardware.org/?probe=601e080563) | Oct 25, 2022 |
| ASUSTek       | PRIME Z390-P                | [261e670072](https://linux-hardware.org/?probe=261e670072) | Oct 24, 2022 |
| ASRock        | Z170 Gaming K4              | [184139e7bc](https://linux-hardware.org/?probe=184139e7bc) | Oct 24, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [3f6368ca5a](https://linux-hardware.org/?probe=3f6368ca5a) | Oct 24, 2022 |
| HP            | 3048h                       | [3c3f7eda5e](https://linux-hardware.org/?probe=3c3f7eda5e) | Oct 24, 2022 |
| ASRock        | X370 Gaming K4              | [5658dbff1b](https://linux-hardware.org/?probe=5658dbff1b) | Oct 24, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [2a57a65990](https://linux-hardware.org/?probe=2a57a65990) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5010a8ef47](https://linux-hardware.org/?probe=5010a8ef47) | Oct 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [fe9ec739e2](https://linux-hardware.org/?probe=fe9ec739e2) | Oct 24, 2022 |
| HP            | 2B05                        | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| ASRock        | P45TS                       | [484f63b830](https://linux-hardware.org/?probe=484f63b830) | Oct 24, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [b9e4b934ee](https://linux-hardware.org/?probe=b9e4b934ee) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [22ea226b97](https://linux-hardware.org/?probe=22ea226b97) | Oct 23, 2022 |
| ASUSTek       | Z170-A                      | [22a96186fa](https://linux-hardware.org/?probe=22a96186fa) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b42893c91e](https://linux-hardware.org/?probe=b42893c91e) | Oct 22, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [b633b478aa](https://linux-hardware.org/?probe=b633b478aa) | Oct 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b7ad660d88](https://linux-hardware.org/?probe=b7ad660d88) | Oct 22, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7f855c9b05](https://linux-hardware.org/?probe=7f855c9b05) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [312828c6a3](https://linux-hardware.org/?probe=312828c6a3) | Oct 22, 2022 |
| Gigabyte      | H77N-WIFI                   | [3e2bd05f56](https://linux-hardware.org/?probe=3e2bd05f56) | Oct 22, 2022 |
| MSI           | MAG B460M BAZOOKA           | [9cfe9f3c51](https://linux-hardware.org/?probe=9cfe9f3c51) | Oct 22, 2022 |
| Dell          | 0PP150 A00                  | [0e07990bda](https://linux-hardware.org/?probe=0e07990bda) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [77b57dbe12](https://linux-hardware.org/?probe=77b57dbe12) | Oct 21, 2022 |
| Unknown       | X79                         | [fd8f23bc70](https://linux-hardware.org/?probe=fd8f23bc70) | Oct 21, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [1ab730c85c](https://linux-hardware.org/?probe=1ab730c85c) | Oct 21, 2022 |
| HP            | 8459                        | [c2ebcf9e20](https://linux-hardware.org/?probe=c2ebcf9e20) | Oct 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [60d4787bb7](https://linux-hardware.org/?probe=60d4787bb7) | Oct 21, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [f03f1bb041](https://linux-hardware.org/?probe=f03f1bb041) | Oct 20, 2022 |
| HP            | 8433 11                     | [7e28f54181](https://linux-hardware.org/?probe=7e28f54181) | Oct 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [502ae94f8f](https://linux-hardware.org/?probe=502ae94f8f) | Oct 20, 2022 |
| NZXT          | N7 B550                     | [f699b7e1d2](https://linux-hardware.org/?probe=f699b7e1d2) | Oct 20, 2022 |
| HP            | 8459                        | [d8ec2e7ee9](https://linux-hardware.org/?probe=d8ec2e7ee9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [13f4800fa8](https://linux-hardware.org/?probe=13f4800fa8) | Oct 20, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [76c0902958](https://linux-hardware.org/?probe=76c0902958) | Oct 19, 2022 |
| Gigabyte      | P67A-UD3                    | [96b72bfa8a](https://linux-hardware.org/?probe=96b72bfa8a) | Oct 19, 2022 |
| Shuttle       | FH67H                       | [6679449225](https://linux-hardware.org/?probe=6679449225) | Oct 19, 2022 |
| MSI           | Z97 GAMING 5                | [980d0d7bb2](https://linux-hardware.org/?probe=980d0d7bb2) | Oct 19, 2022 |
| Gigabyte      | B550M DS3H                  | [d267c64062](https://linux-hardware.org/?probe=d267c64062) | Oct 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | [da8a11aac5](https://linux-hardware.org/?probe=da8a11aac5) | Oct 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [41d2e6298d](https://linux-hardware.org/?probe=41d2e6298d) | Oct 19, 2022 |
| ASUSTek       | P5B-Deluxe                  | [95a75ab35b](https://linux-hardware.org/?probe=95a75ab35b) | Oct 19, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [495c7fdc3d](https://linux-hardware.org/?probe=495c7fdc3d) | Oct 18, 2022 |
| Gigabyte      | 970A-DS3P FX                | [e0c8c2fe15](https://linux-hardware.org/?probe=e0c8c2fe15) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [6941ece1e9](https://linux-hardware.org/?probe=6941ece1e9) | Oct 18, 2022 |
| BESSTAR Te... | F6BFC                       | [70d12e710f](https://linux-hardware.org/?probe=70d12e710f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | [5c2590f03f](https://linux-hardware.org/?probe=5c2590f03f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | [df0afd4326](https://linux-hardware.org/?probe=df0afd4326) | Oct 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d53b4edda1](https://linux-hardware.org/?probe=d53b4edda1) | Oct 18, 2022 |
| ASRock        | Z97E-ITX/ac                 | [2ae712a746](https://linux-hardware.org/?probe=2ae712a746) | Oct 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e618e79bd5](https://linux-hardware.org/?probe=e618e79bd5) | Oct 17, 2022 |
| Dell          | 0WR7PY A02                  | [8c1b258565](https://linux-hardware.org/?probe=8c1b258565) | Oct 16, 2022 |
| ASUSTek       | PRIME Z690-A                | [50fe9fcad5](https://linux-hardware.org/?probe=50fe9fcad5) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | [77f04d4628](https://linux-hardware.org/?probe=77f04d4628) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | [ee436e327b](https://linux-hardware.org/?probe=ee436e327b) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | [86e01f1479](https://linux-hardware.org/?probe=86e01f1479) | Oct 16, 2022 |
| MSI           | A320M PRO-VH PLUS           | [c3c46266d1](https://linux-hardware.org/?probe=c3c46266d1) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [1993500f68](https://linux-hardware.org/?probe=1993500f68) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | [985b192440](https://linux-hardware.org/?probe=985b192440) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8557c8b501](https://linux-hardware.org/?probe=8557c8b501) | Oct 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [4e66c25e04](https://linux-hardware.org/?probe=4e66c25e04) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | [05fa96288f](https://linux-hardware.org/?probe=05fa96288f) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6de814388c](https://linux-hardware.org/?probe=6de814388c) | Oct 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [1200f4104f](https://linux-hardware.org/?probe=1200f4104f) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [79eba98b95](https://linux-hardware.org/?probe=79eba98b95) | Oct 14, 2022 |
| MSI           | FM2-A55M-E33                | [1fe306ae1e](https://linux-hardware.org/?probe=1fe306ae1e) | Oct 13, 2022 |
| ASUSTek       | PRIME Z270-A                | [a6083f4dfe](https://linux-hardware.org/?probe=a6083f4dfe) | Oct 13, 2022 |
| ASUSTek       | Z97-K                       | [47394cb2b5](https://linux-hardware.org/?probe=47394cb2b5) | Oct 13, 2022 |
| ASUSTek       | P8P67 LE                    | [0c7961c445](https://linux-hardware.org/?probe=0c7961c445) | Oct 13, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [f1fcb66794](https://linux-hardware.org/?probe=f1fcb66794) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d0d2949fd3](https://linux-hardware.org/?probe=d0d2949fd3) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2412a53d05](https://linux-hardware.org/?probe=2412a53d05) | Oct 12, 2022 |
| BESSTAR Te... | UM350                       | [f58608a000](https://linux-hardware.org/?probe=f58608a000) | Oct 11, 2022 |
| MSI           | B450M-A PRO MAX             | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| Gigabyte      | J1900M-D2P                  | [dde4a94108](https://linux-hardware.org/?probe=dde4a94108) | Oct 11, 2022 |
| Gigabyte      | H410M DS2V                  | [bd9d9e10c7](https://linux-hardware.org/?probe=bd9d9e10c7) | Oct 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [60037612c1](https://linux-hardware.org/?probe=60037612c1) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e2d9db1022](https://linux-hardware.org/?probe=e2d9db1022) | Oct 10, 2022 |
| ASRock        | X570 PG Velocita            | [ec3a819326](https://linux-hardware.org/?probe=ec3a819326) | Oct 10, 2022 |
| Intel         | DG41TY AAE47335-302         | [c0d07ec775](https://linux-hardware.org/?probe=c0d07ec775) | Oct 10, 2022 |
| MSI           | B450 GAMING PLUS            | [6f95e1591a](https://linux-hardware.org/?probe=6f95e1591a) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8694ed82a6](https://linux-hardware.org/?probe=8694ed82a6) | Oct 09, 2022 |
| MSI           | A320M-A PRO MAX             | [edb6e4180f](https://linux-hardware.org/?probe=edb6e4180f) | Oct 09, 2022 |
| MSI           | B550M PRO-VDH               | [c4e09cdf87](https://linux-hardware.org/?probe=c4e09cdf87) | Oct 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [4aa8b37ac5](https://linux-hardware.org/?probe=4aa8b37ac5) | Oct 09, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [30ff2d0e8f](https://linux-hardware.org/?probe=30ff2d0e8f) | Oct 09, 2022 |
| Pegatron      | 2AD5                        | [19ad61d9c7](https://linux-hardware.org/?probe=19ad61d9c7) | Oct 09, 2022 |
| ASUSTek       | PRIME Z270-A                | [0f4a711f6a](https://linux-hardware.org/?probe=0f4a711f6a) | Oct 08, 2022 |
| Dell          | 0RY007                      | [745f69ec3d](https://linux-hardware.org/?probe=745f69ec3d) | Oct 08, 2022 |
| HP            | 3647h                       | [ddffa21a6e](https://linux-hardware.org/?probe=ddffa21a6e) | Oct 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8895a815c6](https://linux-hardware.org/?probe=8895a815c6) | Oct 07, 2022 |
| Unknown       | Intel X79                   | [9c0ffde822](https://linux-hardware.org/?probe=9c0ffde822) | Oct 06, 2022 |
| HP            | 0AECh D                     | [8fd13e9017](https://linux-hardware.org/?probe=8fd13e9017) | Oct 06, 2022 |
| MSI           | X370 SLI PLUS               | [ea7dc6a41a](https://linux-hardware.org/?probe=ea7dc6a41a) | Oct 06, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [3ea8d4d25e](https://linux-hardware.org/?probe=3ea8d4d25e) | Oct 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6a5822719f](https://linux-hardware.org/?probe=6a5822719f) | Oct 06, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [20b6b5f918](https://linux-hardware.org/?probe=20b6b5f918) | Oct 06, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [7f2b63950d](https://linux-hardware.org/?probe=7f2b63950d) | Oct 05, 2022 |
| MSI           | MEG Z390 GODLIKE            | [368530a660](https://linux-hardware.org/?probe=368530a660) | Oct 05, 2022 |
| MSI           | MEG Z490I UNIFY             | [a60e3c519e](https://linux-hardware.org/?probe=a60e3c519e) | Oct 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [51c401fd4e](https://linux-hardware.org/?probe=51c401fd4e) | Oct 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [ca81117136](https://linux-hardware.org/?probe=ca81117136) | Oct 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [07d4cf95ec](https://linux-hardware.org/?probe=07d4cf95ec) | Oct 04, 2022 |
| Gigabyte      | B85M-D2V                    | [4e6047ec5b](https://linux-hardware.org/?probe=4e6047ec5b) | Oct 03, 2022 |
| Gigabyte      | B85M-D3V-A                  | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [48e867fba8](https://linux-hardware.org/?probe=48e867fba8) | Oct 02, 2022 |
| Acer          | Veriton X6620G v1.0         | [80e98d9053](https://linux-hardware.org/?probe=80e98d9053) | Oct 02, 2022 |
| MSI           | B350 TOMAHAWK               | [253e143d94](https://linux-hardware.org/?probe=253e143d94) | Oct 02, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6121fee541](https://linux-hardware.org/?probe=6121fee541) | Oct 02, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6d8ed9f182](https://linux-hardware.org/?probe=6d8ed9f182) | Oct 02, 2022 |
| Gigabyte      | B550M DS3H                  | [2f8557640c](https://linux-hardware.org/?probe=2f8557640c) | Oct 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a0d36f3810](https://linux-hardware.org/?probe=a0d36f3810) | Oct 02, 2022 |
| ASRock        | X570 Phantom Gaming 4S      | [2215129a47](https://linux-hardware.org/?probe=2215129a47) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [ee22a244e2](https://linux-hardware.org/?probe=ee22a244e2) | Oct 01, 2022 |
| ASRock        | AD2700-ITX                  | [4275ef3653](https://linux-hardware.org/?probe=4275ef3653) | Oct 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [186495d063](https://linux-hardware.org/?probe=186495d063) | Oct 01, 2022 |
| Gigabyte      | B75M-D3H                    | [162334ac1e](https://linux-hardware.org/?probe=162334ac1e) | Sep 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [c06e7e3586](https://linux-hardware.org/?probe=c06e7e3586) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6553398b7d](https://linux-hardware.org/?probe=6553398b7d) | Sep 30, 2022 |
| ASRock        | H270M-ITX/ac                | [c6ae2f8a45](https://linux-hardware.org/?probe=c6ae2f8a45) | Sep 29, 2022 |
| ASUSTek       | PRIME Z270-A                | [4118e245a3](https://linux-hardware.org/?probe=4118e245a3) | Sep 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [362c6b7436](https://linux-hardware.org/?probe=362c6b7436) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| Biostar       | H410MH S2                   | [fbba79fc43](https://linux-hardware.org/?probe=fbba79fc43) | Sep 28, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| Dell          | 0YGYJY A01                  | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | [7af967061b](https://linux-hardware.org/?probe=7af967061b) | Sep 27, 2022 |
| Intel         | DP35DP AAD81073-208         | [031ff09179](https://linux-hardware.org/?probe=031ff09179) | Sep 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6373bf42ef](https://linux-hardware.org/?probe=6373bf42ef) | Sep 26, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [778f7340fa](https://linux-hardware.org/?probe=778f7340fa) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | [982d41c1eb](https://linux-hardware.org/?probe=982d41c1eb) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [82b73270ca](https://linux-hardware.org/?probe=82b73270ca) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | [a5d5950e29](https://linux-hardware.org/?probe=a5d5950e29) | Sep 25, 2022 |
| MSI           | MAG Z590 TORPEDO            | [cedbd8909f](https://linux-hardware.org/?probe=cedbd8909f) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [a1f261d09d](https://linux-hardware.org/?probe=a1f261d09d) | Sep 25, 2022 |
| Acer          | Aspire X1900                | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [66b5b65077](https://linux-hardware.org/?probe=66b5b65077) | Sep 25, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [a35dda8c10](https://linux-hardware.org/?probe=a35dda8c10) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a4b47e7325](https://linux-hardware.org/?probe=a4b47e7325) | Sep 25, 2022 |
| ASRock        | Z170M Extreme4              | [bd1e98639b](https://linux-hardware.org/?probe=bd1e98639b) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [542249f675](https://linux-hardware.org/?probe=542249f675) | Sep 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ab2e3b1767](https://linux-hardware.org/?probe=ab2e3b1767) | Sep 24, 2022 |
| ASUSTek       | PRIME B365M-A               | [c4c88d72ae](https://linux-hardware.org/?probe=c4c88d72ae) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [31f1acf273](https://linux-hardware.org/?probe=31f1acf273) | Sep 23, 2022 |
| ASUSTek       | PRIME B250M-C               | [2e45736b42](https://linux-hardware.org/?probe=2e45736b42) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a4ce7c179e](https://linux-hardware.org/?probe=a4ce7c179e) | Sep 23, 2022 |
| Gigabyte      | B660I AORUS PRO DDR4        | [810c7883d4](https://linux-hardware.org/?probe=810c7883d4) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [7d69f0c6c6](https://linux-hardware.org/?probe=7d69f0c6c6) | Sep 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [0f750af134](https://linux-hardware.org/?probe=0f750af134) | Sep 23, 2022 |
| Gigabyte      | Z270P-D3-CF                 | [79509e063b](https://linux-hardware.org/?probe=79509e063b) | Sep 23, 2022 |
| MSI           | FM2-A55M-E33                | [4867faffbf](https://linux-hardware.org/?probe=4867faffbf) | Sep 23, 2022 |
| Foxconn       | H61M-S/H61M                 | [039b5cff54](https://linux-hardware.org/?probe=039b5cff54) | Sep 22, 2022 |
| MSI           | H310M PRO-VH                | [c11e067cb5](https://linux-hardware.org/?probe=c11e067cb5) | Sep 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bfb470649a](https://linux-hardware.org/?probe=bfb470649a) | Sep 22, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [11ea16f0d6](https://linux-hardware.org/?probe=11ea16f0d6) | Sep 22, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [54d3096bb6](https://linux-hardware.org/?probe=54d3096bb6) | Sep 21, 2022 |
| BESSTAR Te... | UM350                       | [62a9723eb7](https://linux-hardware.org/?probe=62a9723eb7) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | [20d37d51bd](https://linux-hardware.org/?probe=20d37d51bd) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | [cabebaa0e6](https://linux-hardware.org/?probe=cabebaa0e6) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [754dfba736](https://linux-hardware.org/?probe=754dfba736) | Sep 21, 2022 |
| HP            | ProLiant ML110 G7           | [d5b4924a7b](https://linux-hardware.org/?probe=d5b4924a7b) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | [015c8dd353](https://linux-hardware.org/?probe=015c8dd353) | Sep 20, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1869422fde](https://linux-hardware.org/?probe=1869422fde) | Sep 20, 2022 |
| ASUSTek       | Z170-A                      | [aad09d3281](https://linux-hardware.org/?probe=aad09d3281) | Sep 20, 2022 |
| ASUSTek       | Z97-AR                      | [5cf4494f07](https://linux-hardware.org/?probe=5cf4494f07) | Sep 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [fa5f7f7245](https://linux-hardware.org/?probe=fa5f7f7245) | Sep 20, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [75854836f7](https://linux-hardware.org/?probe=75854836f7) | Sep 20, 2022 |
| Dell          | 0K3CM7 A00                  | [3f82789198](https://linux-hardware.org/?probe=3f82789198) | Sep 20, 2022 |
| Dell          | 0K3CM7 A00                  | [b6ce2720e2](https://linux-hardware.org/?probe=b6ce2720e2) | Sep 20, 2022 |
| ASRock        | H610M-HDV/M.2               | [02a5a10d7a](https://linux-hardware.org/?probe=02a5a10d7a) | Sep 20, 2022 |
| ASUSTek       | A88X-PRO                    | [b88a699d58](https://linux-hardware.org/?probe=b88a699d58) | Sep 19, 2022 |
| ASUSTek       | PRIME Z270-P                | [d44ac0cc2a](https://linux-hardware.org/?probe=d44ac0cc2a) | Sep 19, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a6857e4b03](https://linux-hardware.org/?probe=a6857e4b03) | Sep 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [424e3ded44](https://linux-hardware.org/?probe=424e3ded44) | Sep 19, 2022 |
| Dell          | 0J3C2F A02                  | [8027be6f7e](https://linux-hardware.org/?probe=8027be6f7e) | Sep 19, 2022 |
| HP            | 2B05                        | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [f8bf8fd596](https://linux-hardware.org/?probe=f8bf8fd596) | Sep 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7a1dbe2204](https://linux-hardware.org/?probe=7a1dbe2204) | Sep 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [8072b6c0e0](https://linux-hardware.org/?probe=8072b6c0e0) | Sep 19, 2022 |
| ASUSTek       | P8Q77-M2                    | [1e067b7c4f](https://linux-hardware.org/?probe=1e067b7c4f) | Sep 19, 2022 |
| Dell          | 0KWVT8 A03                  | [7c52790345](https://linux-hardware.org/?probe=7c52790345) | Sep 19, 2022 |
| ASRock        | X570 Steel Legend           | [6fd34fa73b](https://linux-hardware.org/?probe=6fd34fa73b) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H                  | [bf7318e65e](https://linux-hardware.org/?probe=bf7318e65e) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| ASUSTek       | Z97-P                       | [37f0f7b888](https://linux-hardware.org/?probe=37f0f7b888) | Sep 19, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [75be2db65c](https://linux-hardware.org/?probe=75be2db65c) | Sep 19, 2022 |
| Dell          | 02M8NY A01                  | [498286eb91](https://linux-hardware.org/?probe=498286eb91) | Sep 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [3da12828c0](https://linux-hardware.org/?probe=3da12828c0) | Sep 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [6c63c03b9f](https://linux-hardware.org/?probe=6c63c03b9f) | Sep 19, 2022 |
| ASRock        | 960GM-VGS3 FX               | [7c89dc4342](https://linux-hardware.org/?probe=7c89dc4342) | Sep 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5233832be3](https://linux-hardware.org/?probe=5233832be3) | Sep 19, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [8d2c35d5f2](https://linux-hardware.org/?probe=8d2c35d5f2) | Sep 19, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [27d1f0c593](https://linux-hardware.org/?probe=27d1f0c593) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| ASUSTek       | P8Q77-M2                    | [171e24a5c1](https://linux-hardware.org/?probe=171e24a5c1) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | [798bb8eda6](https://linux-hardware.org/?probe=798bb8eda6) | Sep 18, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [b48eda0e37](https://linux-hardware.org/?probe=b48eda0e37) | Sep 18, 2022 |
| ASUSTek       | PRIME H410M-K R2.0          | [7d18b85f33](https://linux-hardware.org/?probe=7d18b85f33) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [21da8441d5](https://linux-hardware.org/?probe=21da8441d5) | Sep 18, 2022 |
| Casper        | NIRVANA DESKTOP             | [7cdffad4a2](https://linux-hardware.org/?probe=7cdffad4a2) | Sep 18, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [1f27376b8e](https://linux-hardware.org/?probe=1f27376b8e) | Sep 18, 2022 |
| Acer          | Aspire TC-780               | [936ece435c](https://linux-hardware.org/?probe=936ece435c) | Sep 18, 2022 |
| Acer          | A75F2-M2 P21-A1             | [2d00ba463b](https://linux-hardware.org/?probe=2d00ba463b) | Sep 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [7161071790](https://linux-hardware.org/?probe=7161071790) | Sep 18, 2022 |
| ASRock        | B550M-ITX/ac                | [379aaf7b61](https://linux-hardware.org/?probe=379aaf7b61) | Sep 16, 2022 |
| ASUSTek       | PRIME B365M-A               | [e191511194](https://linux-hardware.org/?probe=e191511194) | Sep 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | [07dd87b76b](https://linux-hardware.org/?probe=07dd87b76b) | Sep 16, 2022 |
| HP            | 3397                        | [637a5570cf](https://linux-hardware.org/?probe=637a5570cf) | Sep 16, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4d460404c8](https://linux-hardware.org/?probe=4d460404c8) | Sep 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9bfc1472d1](https://linux-hardware.org/?probe=9bfc1472d1) | Sep 16, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [dcaf7e8bd0](https://linux-hardware.org/?probe=dcaf7e8bd0) | Sep 15, 2022 |
| ASRock        | X370 Gaming K4              | [0858e80da7](https://linux-hardware.org/?probe=0858e80da7) | Sep 15, 2022 |
| Gigabyte      | B85M-D3V-A                  | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| Gigabyte      | Z97P-D3                     | [ca9e537823](https://linux-hardware.org/?probe=ca9e537823) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [e633838a51](https://linux-hardware.org/?probe=e633838a51) | Sep 15, 2022 |
| ASUSTek       | P5PL2-E                     | [84bfb7d319](https://linux-hardware.org/?probe=84bfb7d319) | Sep 15, 2022 |
| ASUSTek       | PRIME Z270-A                | [2642647feb](https://linux-hardware.org/?probe=2642647feb) | Sep 14, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [55216d250b](https://linux-hardware.org/?probe=55216d250b) | Sep 14, 2022 |
| HP            | 805D                        | [8acaebbd42](https://linux-hardware.org/?probe=8acaebbd42) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| HP            | 1998                        | [bf93a500f4](https://linux-hardware.org/?probe=bf93a500f4) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [37d6996290](https://linux-hardware.org/?probe=37d6996290) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e7cb70c141](https://linux-hardware.org/?probe=e7cb70c141) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [754d0f3a2b](https://linux-hardware.org/?probe=754d0f3a2b) | Sep 14, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [175c84f6ea](https://linux-hardware.org/?probe=175c84f6ea) | Sep 13, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [d3f957e34a](https://linux-hardware.org/?probe=d3f957e34a) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [9b2a84cd02](https://linux-hardware.org/?probe=9b2a84cd02) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [1285ab4d66](https://linux-hardware.org/?probe=1285ab4d66) | Sep 13, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a6e7414518](https://linux-hardware.org/?probe=a6e7414518) | Sep 13, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | [1faad914c6](https://linux-hardware.org/?probe=1faad914c6) | Sep 13, 2022 |
| Unknown       | X99H                        | [9fb8886110](https://linux-hardware.org/?probe=9fb8886110) | Sep 13, 2022 |
| Dell          | 0M017G A00                  | [e040958337](https://linux-hardware.org/?probe=e040958337) | Sep 13, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [7ce5d8e865](https://linux-hardware.org/?probe=7ce5d8e865) | Sep 12, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [ec5f57ab65](https://linux-hardware.org/?probe=ec5f57ab65) | Sep 12, 2022 |
| ASUSTek       | Z97-A                       | [b23a59ba48](https://linux-hardware.org/?probe=b23a59ba48) | Sep 12, 2022 |
| HP            | 1494                        | [0faa06cff4](https://linux-hardware.org/?probe=0faa06cff4) | Sep 12, 2022 |
| BESSTAR Te... | UM700                       | [6847632df3](https://linux-hardware.org/?probe=6847632df3) | Sep 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d85067b0f0](https://linux-hardware.org/?probe=d85067b0f0) | Sep 11, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [a3b824ba41](https://linux-hardware.org/?probe=a3b824ba41) | Sep 10, 2022 |
| ASUSTek       | Z170-A                      | [66c2198f48](https://linux-hardware.org/?probe=66c2198f48) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | [841be89be6](https://linux-hardware.org/?probe=841be89be6) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | [626cf13c17](https://linux-hardware.org/?probe=626cf13c17) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | [6ce0fb28ee](https://linux-hardware.org/?probe=6ce0fb28ee) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | [5cce5f5ade](https://linux-hardware.org/?probe=5cce5f5ade) | Sep 10, 2022 |
| ASUSTek       | B150 PRO GAMING             | [5e145ec2d1](https://linux-hardware.org/?probe=5e145ec2d1) | Sep 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [2cb423c8e7](https://linux-hardware.org/?probe=2cb423c8e7) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [03979fc286](https://linux-hardware.org/?probe=03979fc286) | Sep 10, 2022 |
| ASRock        | FM2A88X Extreme6+           | [20ee71a4d6](https://linux-hardware.org/?probe=20ee71a4d6) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [c6dac06569](https://linux-hardware.org/?probe=c6dac06569) | Sep 09, 2022 |
| Gigabyte      | H77N-WIFI                   | [3c454664b0](https://linux-hardware.org/?probe=3c454664b0) | Sep 09, 2022 |
| Biostar       | A780L3G                     | [e53730ab48](https://linux-hardware.org/?probe=e53730ab48) | Sep 09, 2022 |
| ASRock        | B550M Pro4                  | [e43ef549eb](https://linux-hardware.org/?probe=e43ef549eb) | Sep 08, 2022 |
| ASRock        | B550M Pro4                  | [ac6cb859ad](https://linux-hardware.org/?probe=ac6cb859ad) | Sep 08, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [174c263499](https://linux-hardware.org/?probe=174c263499) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | [aeb2bae778](https://linux-hardware.org/?probe=aeb2bae778) | Sep 08, 2022 |
| Intel         | DH77DF AAG40293-300         | [217971d572](https://linux-hardware.org/?probe=217971d572) | Sep 08, 2022 |
| Dell          | 02YRK5 A02                  | [daf3e0182b](https://linux-hardware.org/?probe=daf3e0182b) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | [d5040ffbda](https://linux-hardware.org/?probe=d5040ffbda) | Sep 08, 2022 |
| HP            | 18E4                        | [1e8addf905](https://linux-hardware.org/?probe=1e8addf905) | Sep 08, 2022 |
| ASUSTek       | H110M-A                     | [dad38946f6](https://linux-hardware.org/?probe=dad38946f6) | Sep 08, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [0f0a18c852](https://linux-hardware.org/?probe=0f0a18c852) | Sep 08, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [e06271e233](https://linux-hardware.org/?probe=e06271e233) | Sep 08, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [051ea3b002](https://linux-hardware.org/?probe=051ea3b002) | Sep 08, 2022 |
| ASUSTek       | Z97-A                       | [46be1ea134](https://linux-hardware.org/?probe=46be1ea134) | Sep 08, 2022 |
| MSI           | Z97 PC Mate                 | [bcf93bb718](https://linux-hardware.org/?probe=bcf93bb718) | Sep 08, 2022 |
| Biostar       | H310MHP                     | [6063bede72](https://linux-hardware.org/?probe=6063bede72) | Sep 07, 2022 |
| Dell          | 02YRK5 A02                  | [2395ab5aed](https://linux-hardware.org/?probe=2395ab5aed) | Sep 07, 2022 |
| ASUSTek       | H97-PRO                     | [fb4bfcf055](https://linux-hardware.org/?probe=fb4bfcf055) | Sep 07, 2022 |
| ASRock        | EP2C602                     | [56a6980ddc](https://linux-hardware.org/?probe=56a6980ddc) | Sep 07, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [a816f4f60b](https://linux-hardware.org/?probe=a816f4f60b) | Sep 07, 2022 |
| ASUSTek       | Z97-AR                      | [01dbdc3b29](https://linux-hardware.org/?probe=01dbdc3b29) | Sep 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [dad765ca9e](https://linux-hardware.org/?probe=dad765ca9e) | Sep 06, 2022 |
| MSI           | MEG X570 ACE                | [5f7f592f25](https://linux-hardware.org/?probe=5f7f592f25) | Sep 05, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e83fa739c9](https://linux-hardware.org/?probe=e83fa739c9) | Sep 05, 2022 |
| MSI           | B550-A PRO                  | [950b2a8eb5](https://linux-hardware.org/?probe=950b2a8eb5) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [127c2f5f75](https://linux-hardware.org/?probe=127c2f5f75) | Sep 05, 2022 |
| Gigabyte      | EP45-DS3L                   | [cb17ac9b4e](https://linux-hardware.org/?probe=cb17ac9b4e) | Sep 05, 2022 |
| Gigabyte      | Z370M DS3H-CF               | [e590a83122](https://linux-hardware.org/?probe=e590a83122) | Sep 05, 2022 |
| Lenovo        | 367D 31900003 STD           | [c145bac65a](https://linux-hardware.org/?probe=c145bac65a) | Sep 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [7c87d1ad42](https://linux-hardware.org/?probe=7c87d1ad42) | Sep 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [0df0bba932](https://linux-hardware.org/?probe=0df0bba932) | Sep 05, 2022 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [b4a71c0eff](https://linux-hardware.org/?probe=b4a71c0eff) | Sep 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2cf13f4045](https://linux-hardware.org/?probe=2cf13f4045) | Sep 04, 2022 |
| ASUSTek       | KCMA-D8                     | [df5fdfccf0](https://linux-hardware.org/?probe=df5fdfccf0) | Sep 04, 2022 |
| MSI           | H510M-A PRO                 | [7bb2d68f03](https://linux-hardware.org/?probe=7bb2d68f03) | Sep 04, 2022 |
| Foxconn       | 2AB1                        | [3b7dae5f40](https://linux-hardware.org/?probe=3b7dae5f40) | Sep 04, 2022 |
| Gigabyte      | F2A78M-D3H                  | [5b0da32c82](https://linux-hardware.org/?probe=5b0da32c82) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [ea22a308c9](https://linux-hardware.org/?probe=ea22a308c9) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [bd2f18b5a5](https://linux-hardware.org/?probe=bd2f18b5a5) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [159c1dcd33](https://linux-hardware.org/?probe=159c1dcd33) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | [e20b509508](https://linux-hardware.org/?probe=e20b509508) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [b9f43af7d0](https://linux-hardware.org/?probe=b9f43af7d0) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [5dcc9cd8c8](https://linux-hardware.org/?probe=5dcc9cd8c8) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [9cab157472](https://linux-hardware.org/?probe=9cab157472) | Sep 03, 2022 |
| ASUSTek       | Z170-K                      | [d47c5fe35c](https://linux-hardware.org/?probe=d47c5fe35c) | Sep 03, 2022 |
| Gigabyte      | B450M DS3H-CF               | [5f37e7a618](https://linux-hardware.org/?probe=5f37e7a618) | Sep 03, 2022 |
| ASRock        | X470 Taichi                 | [0a6ff089f1](https://linux-hardware.org/?probe=0a6ff089f1) | Sep 03, 2022 |
| MSI           | X470 GAMING PRO MAX         | [7f10b8002b](https://linux-hardware.org/?probe=7f10b8002b) | Sep 03, 2022 |
| BESSTAR Te... | UM350                       | [02423b61e0](https://linux-hardware.org/?probe=02423b61e0) | Sep 03, 2022 |
| Foxconn       | 2ADA                        | [f1ca159a19](https://linux-hardware.org/?probe=f1ca159a19) | Sep 03, 2022 |
| Acer          | Aspire M3910                | [17c1079582](https://linux-hardware.org/?probe=17c1079582) | Sep 02, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [0a1de8a406](https://linux-hardware.org/?probe=0a1de8a406) | Sep 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [446e2d292a](https://linux-hardware.org/?probe=446e2d292a) | Sep 02, 2022 |
| Dell          | 0MWYPT A02                  | [e2f98387b0](https://linux-hardware.org/?probe=e2f98387b0) | Sep 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [2cf98644bc](https://linux-hardware.org/?probe=2cf98644bc) | Sep 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [689c3aa34d](https://linux-hardware.org/?probe=689c3aa34d) | Sep 01, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [c5547cac7c](https://linux-hardware.org/?probe=c5547cac7c) | Aug 31, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | [36eb80672f](https://linux-hardware.org/?probe=36eb80672f) | Aug 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [df96c4acaf](https://linux-hardware.org/?probe=df96c4acaf) | Aug 31, 2022 |
| Dell          | 0KV3RP A00                  | [731a14ee10](https://linux-hardware.org/?probe=731a14ee10) | Aug 31, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [2c72dfccbb](https://linux-hardware.org/?probe=2c72dfccbb) | Aug 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [eba231b7db](https://linux-hardware.org/?probe=eba231b7db) | Aug 30, 2022 |
| HP            | 8464                        | [16bb2588e0](https://linux-hardware.org/?probe=16bb2588e0) | Aug 30, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d9d75bc1f0](https://linux-hardware.org/?probe=d9d75bc1f0) | Aug 29, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9fbdc83458](https://linux-hardware.org/?probe=9fbdc83458) | Aug 29, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7b0113a203](https://linux-hardware.org/?probe=7b0113a203) | Aug 29, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | [cf0cdab1da](https://linux-hardware.org/?probe=cf0cdab1da) | Aug 29, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [60bc287a81](https://linux-hardware.org/?probe=60bc287a81) | Aug 29, 2022 |
| HP            | 8751                        | [62c8c2f25e](https://linux-hardware.org/?probe=62c8c2f25e) | Aug 29, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [7d1dae1de6](https://linux-hardware.org/?probe=7d1dae1de6) | Aug 29, 2022 |
| MSI           | Z77A-G43                    | [1d1864dabc](https://linux-hardware.org/?probe=1d1864dabc) | Aug 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [505d987d1e](https://linux-hardware.org/?probe=505d987d1e) | Aug 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [3de4d575a9](https://linux-hardware.org/?probe=3de4d575a9) | Aug 27, 2022 |
| HP            | 805D                        | [419598ebba](https://linux-hardware.org/?probe=419598ebba) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7642980e6e](https://linux-hardware.org/?probe=7642980e6e) | Aug 27, 2022 |
| Dell          | 0KV3RP A00                  | [f73bf383ce](https://linux-hardware.org/?probe=f73bf383ce) | Aug 26, 2022 |
| ASUSTek       | P5QL-E                      | [f1c16cf6e7](https://linux-hardware.org/?probe=f1c16cf6e7) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [dd68273352](https://linux-hardware.org/?probe=dd68273352) | Aug 26, 2022 |
| ASUSTek       | P5QL-E                      | [e69218ea58](https://linux-hardware.org/?probe=e69218ea58) | Aug 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | [f37ee1975e](https://linux-hardware.org/?probe=f37ee1975e) | Aug 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ff55a7dbf1](https://linux-hardware.org/?probe=ff55a7dbf1) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2388b95ce9](https://linux-hardware.org/?probe=2388b95ce9) | Aug 25, 2022 |
| ASUSTek       | UN62                        | [49fcd1324f](https://linux-hardware.org/?probe=49fcd1324f) | Aug 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f80abd07f3](https://linux-hardware.org/?probe=f80abd07f3) | Aug 25, 2022 |
| ASRock        | B450M Pro4                  | [69fd53a234](https://linux-hardware.org/?probe=69fd53a234) | Aug 25, 2022 |
| ASRock        | B450M Pro4                  | [47dc749c6c](https://linux-hardware.org/?probe=47dc749c6c) | Aug 25, 2022 |
| Dell          | 01TKCC A01                  | [9a362ed844](https://linux-hardware.org/?probe=9a362ed844) | Aug 25, 2022 |
| Dell          | 0PU052                      | [2bffd37724](https://linux-hardware.org/?probe=2bffd37724) | Aug 24, 2022 |
| ASUSTek       | Z97-AR                      | [a766ce2d5a](https://linux-hardware.org/?probe=a766ce2d5a) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ae4a81a473](https://linux-hardware.org/?probe=ae4a81a473) | Aug 24, 2022 |
| ASUSTek       | Z97-A                       | [016c661430](https://linux-hardware.org/?probe=016c661430) | Aug 24, 2022 |
| ASRock        | X570M Pro4                  | [f2bc1e0fae](https://linux-hardware.org/?probe=f2bc1e0fae) | Aug 23, 2022 |
| Gigabyte      | H81M-S                      | [0b1e1d125d](https://linux-hardware.org/?probe=0b1e1d125d) | Aug 23, 2022 |
| Dell          | 0T1D10 A01                  | [39e79a7077](https://linux-hardware.org/?probe=39e79a7077) | Aug 23, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [0796a8df9d](https://linux-hardware.org/?probe=0796a8df9d) | Aug 23, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [b0af95356c](https://linux-hardware.org/?probe=b0af95356c) | Aug 22, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bc32a93168](https://linux-hardware.org/?probe=bc32a93168) | Aug 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [a25c6f8d64](https://linux-hardware.org/?probe=a25c6f8d64) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | [2af48f00ac](https://linux-hardware.org/?probe=2af48f00ac) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | [0910ca3887](https://linux-hardware.org/?probe=0910ca3887) | Aug 22, 2022 |
| MSI           | Z370 TOMAHAWK               | [251d227686](https://linux-hardware.org/?probe=251d227686) | Aug 22, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [eb81df27ce](https://linux-hardware.org/?probe=eb81df27ce) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | [51f5d50d85](https://linux-hardware.org/?probe=51f5d50d85) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | [002a0c3f5a](https://linux-hardware.org/?probe=002a0c3f5a) | Aug 22, 2022 |
| ASRock        | X370 Taichi                 | [8f952ff258](https://linux-hardware.org/?probe=8f952ff258) | Aug 21, 2022 |
| ASRock        | AD2700-ITX                  | [4be47e3738](https://linux-hardware.org/?probe=4be47e3738) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [5f90bb65a6](https://linux-hardware.org/?probe=5f90bb65a6) | Aug 21, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [b2ac87cffc](https://linux-hardware.org/?probe=b2ac87cffc) | Aug 20, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [7dbac78a87](https://linux-hardware.org/?probe=7dbac78a87) | Aug 20, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [abbb1d7360](https://linux-hardware.org/?probe=abbb1d7360) | Aug 20, 2022 |
| Gigabyte      | B550M DS3H                  | [fd0604d0fb](https://linux-hardware.org/?probe=fd0604d0fb) | Aug 20, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [c9738d69e9](https://linux-hardware.org/?probe=c9738d69e9) | Aug 20, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [2f5ef1300f](https://linux-hardware.org/?probe=2f5ef1300f) | Aug 19, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [ffb095f0c3](https://linux-hardware.org/?probe=ffb095f0c3) | Aug 19, 2022 |
| ASUSTek       | P8H67-M LE                  | [ce8c93b28f](https://linux-hardware.org/?probe=ce8c93b28f) | Aug 19, 2022 |
| ASRock        | B450 Pro4                   | [ed013e82aa](https://linux-hardware.org/?probe=ed013e82aa) | Aug 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8fc237babf](https://linux-hardware.org/?probe=8fc237babf) | Aug 17, 2022 |
| Lenovo        | SHARKBAY NOK                | [e73d7ae317](https://linux-hardware.org/?probe=e73d7ae317) | Aug 17, 2022 |
| Dell          | 09M8Y8 A01                  | [9defe532c0](https://linux-hardware.org/?probe=9defe532c0) | Aug 17, 2022 |
| ASUSTek       | P8H77-V LE                  | [7f6138d8ce](https://linux-hardware.org/?probe=7f6138d8ce) | Aug 17, 2022 |
| ASUSTek       | Z97-C                       | [58f88a4494](https://linux-hardware.org/?probe=58f88a4494) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | [e68748c0f1](https://linux-hardware.org/?probe=e68748c0f1) | Aug 16, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [8b591b08b0](https://linux-hardware.org/?probe=8b591b08b0) | Aug 16, 2022 |
| ASUSTek       | Z97-C                       | [e68b5affa4](https://linux-hardware.org/?probe=e68b5affa4) | Aug 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [3f83c9e402](https://linux-hardware.org/?probe=3f83c9e402) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [97ff4c0078](https://linux-hardware.org/?probe=97ff4c0078) | Aug 16, 2022 |
| Gigabyte      | B550M DS3H                  | [6ef5e022c7](https://linux-hardware.org/?probe=6ef5e022c7) | Aug 15, 2022 |
| ECS           | H61H2-MV                    | [0b95f78b15](https://linux-hardware.org/?probe=0b95f78b15) | Aug 15, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [8072e15459](https://linux-hardware.org/?probe=8072e15459) | Aug 15, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [bbbda98d21](https://linux-hardware.org/?probe=bbbda98d21) | Aug 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [20d9ba44b5](https://linux-hardware.org/?probe=20d9ba44b5) | Aug 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | [1298facab1](https://linux-hardware.org/?probe=1298facab1) | Aug 15, 2022 |
| ASUSTek       | B85M-G                      | [b44e802677](https://linux-hardware.org/?probe=b44e802677) | Aug 14, 2022 |
| ASUSTek       | P8H77-V                     | [83abda5bc9](https://linux-hardware.org/?probe=83abda5bc9) | Aug 14, 2022 |
| Foxconn       | 2ABF                        | [cc835ea750](https://linux-hardware.org/?probe=cc835ea750) | Aug 13, 2022 |
| Huanan        | X99-BD4 V1.33               | [a250b39eec](https://linux-hardware.org/?probe=a250b39eec) | Aug 13, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [6a0c6ab778](https://linux-hardware.org/?probe=6a0c6ab778) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [4983efddbb](https://linux-hardware.org/?probe=4983efddbb) | Aug 13, 2022 |
| ASRock        | FM2A88M-HD+ R2.0            | [e1f4ef0670](https://linux-hardware.org/?probe=e1f4ef0670) | Aug 12, 2022 |
| MSI           | Z97 GAMING 5                | [e7c81a6ce7](https://linux-hardware.org/?probe=e7c81a6ce7) | Aug 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [6a8f06be23](https://linux-hardware.org/?probe=6a8f06be23) | Aug 12, 2022 |
| HP            | 8183                        | [19f5199de8](https://linux-hardware.org/?probe=19f5199de8) | Aug 12, 2022 |
| Gigabyte      | H370 HD3-CF                 | [3d93d807ca](https://linux-hardware.org/?probe=3d93d807ca) | Aug 12, 2022 |
| MSI           | X370 SLI PLUS               | [8b4bc6f127](https://linux-hardware.org/?probe=8b4bc6f127) | Aug 11, 2022 |
| MSI           | Z87-G45 GAMING              | [5f25d77994](https://linux-hardware.org/?probe=5f25d77994) | Aug 11, 2022 |
| HP            | 8183                        | [c441ead9f8](https://linux-hardware.org/?probe=c441ead9f8) | Aug 11, 2022 |
| MSI           | Z87-G45 GAMING              | [0790b09ae3](https://linux-hardware.org/?probe=0790b09ae3) | Aug 11, 2022 |
| Gigabyte      | B150M-D3H-CF                | [43b4579869](https://linux-hardware.org/?probe=43b4579869) | Aug 11, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [edf947ace6](https://linux-hardware.org/?probe=edf947ace6) | Aug 10, 2022 |
| Lenovo        | SHARKBAY NOK                | [c788f4d7a8](https://linux-hardware.org/?probe=c788f4d7a8) | Aug 10, 2022 |
| ASRock        | H61M-HVGS                   | [f646dceb7c](https://linux-hardware.org/?probe=f646dceb7c) | Aug 10, 2022 |
| ASRock        | B450M Steel Legend          | [a24161deaa](https://linux-hardware.org/?probe=a24161deaa) | Aug 10, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [d586bdd82d](https://linux-hardware.org/?probe=d586bdd82d) | Aug 10, 2022 |
| Gigabyte      | X570 AORUS PRO              | [8558001fa2](https://linux-hardware.org/?probe=8558001fa2) | Aug 09, 2022 |
| Gigabyte      | Z87-HD3                     | [ee1bdd9333](https://linux-hardware.org/?probe=ee1bdd9333) | Aug 09, 2022 |
| Gigabyte      | Z87-HD3                     | [a0243ce6f0](https://linux-hardware.org/?probe=a0243ce6f0) | Aug 09, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [e74a95c4d9](https://linux-hardware.org/?probe=e74a95c4d9) | Aug 09, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [42d32cdfda](https://linux-hardware.org/?probe=42d32cdfda) | Aug 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | [91a2943c51](https://linux-hardware.org/?probe=91a2943c51) | Aug 09, 2022 |
| MSI           | Z87-G45 GAMING              | [093a936372](https://linux-hardware.org/?probe=093a936372) | Aug 08, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [b421a8c6c4](https://linux-hardware.org/?probe=b421a8c6c4) | Aug 08, 2022 |
| ASUSTek       | P8H67-M LE                  | [07c89bcbc6](https://linux-hardware.org/?probe=07c89bcbc6) | Aug 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [08b891334e](https://linux-hardware.org/?probe=08b891334e) | Aug 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [244025d59e](https://linux-hardware.org/?probe=244025d59e) | Aug 08, 2022 |
| Lenovo        | SHARKBAY NOK                | [f08a60d37c](https://linux-hardware.org/?probe=f08a60d37c) | Aug 07, 2022 |
| ASUSTek       | PRIME B550M-A               | [64e8ddf1c9](https://linux-hardware.org/?probe=64e8ddf1c9) | Aug 07, 2022 |
| ECS           | H61H2-MV                    | [7dbc1a26ca](https://linux-hardware.org/?probe=7dbc1a26ca) | Aug 07, 2022 |
| MSI           | MAG B460M MORTAR            | [a823925843](https://linux-hardware.org/?probe=a823925843) | Aug 07, 2022 |
| HP            | 1587h                       | [d9d1b6832f](https://linux-hardware.org/?probe=d9d1b6832f) | Aug 07, 2022 |
| HP            | 1587h                       | [737b509512](https://linux-hardware.org/?probe=737b509512) | Aug 07, 2022 |
| Gigabyte      | A320M-S2H-CF                | [31c87abaf3](https://linux-hardware.org/?probe=31c87abaf3) | Aug 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [154440549c](https://linux-hardware.org/?probe=154440549c) | Aug 06, 2022 |
| ECS           | H61H2-MV                    | [6dbb0a4eb9](https://linux-hardware.org/?probe=6dbb0a4eb9) | Aug 06, 2022 |
| Gigabyte      | B450M DS3H-CF               | [258c7a2f71](https://linux-hardware.org/?probe=258c7a2f71) | Aug 06, 2022 |
| ASUSTek       | SABERTOOTH X79              | [4f10e80880](https://linux-hardware.org/?probe=4f10e80880) | Aug 06, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [4f12a5e11e](https://linux-hardware.org/?probe=4f12a5e11e) | Aug 06, 2022 |
| BESSTAR Te... | HM90                        | [36e148426c](https://linux-hardware.org/?probe=36e148426c) | Aug 06, 2022 |
| BESSTAR Te... | HM90                        | [28ec23aa22](https://linux-hardware.org/?probe=28ec23aa22) | Aug 06, 2022 |
| Gigabyte      | 945GCM-S2L                  | [fd6cf872ae](https://linux-hardware.org/?probe=fd6cf872ae) | Aug 06, 2022 |
| ASRock        | B460M Pro4S/ac              | [79f01ebf66](https://linux-hardware.org/?probe=79f01ebf66) | Aug 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [1798c25088](https://linux-hardware.org/?probe=1798c25088) | Aug 05, 2022 |
| Gigabyte      | H77N-WIFI                   | [caa404d4c6](https://linux-hardware.org/?probe=caa404d4c6) | Aug 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9320816ca5](https://linux-hardware.org/?probe=9320816ca5) | Aug 05, 2022 |
| Gigabyte      | AX370-Gaming 5              | [46f109ed37](https://linux-hardware.org/?probe=46f109ed37) | Aug 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [c6e5356615](https://linux-hardware.org/?probe=c6e5356615) | Aug 04, 2022 |
| Gigabyte      | M68MT-S2P                   | [7c41cd3006](https://linux-hardware.org/?probe=7c41cd3006) | Aug 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b224ef1b8d](https://linux-hardware.org/?probe=b224ef1b8d) | Aug 04, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [b932802b52](https://linux-hardware.org/?probe=b932802b52) | Aug 04, 2022 |
| ASUSTek       | H110M-K                     | [df01e617f2](https://linux-hardware.org/?probe=df01e617f2) | Aug 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [6e77095fb6](https://linux-hardware.org/?probe=6e77095fb6) | Aug 03, 2022 |
| Dell          | 05GD68 A00                  | [32bda73b5e](https://linux-hardware.org/?probe=32bda73b5e) | Aug 03, 2022 |
| ASRock        | AB350M-HDV                  | [4678a0f755](https://linux-hardware.org/?probe=4678a0f755) | Aug 03, 2022 |
| HP            | 8767 A                      | [3679ccede7](https://linux-hardware.org/?probe=3679ccede7) | Aug 02, 2022 |
| MSI           | H510M-A PRO                 | [b570321ffa](https://linux-hardware.org/?probe=b570321ffa) | Aug 02, 2022 |
| Dell          | 0Y56T3 A00                  | [c52a590c5b](https://linux-hardware.org/?probe=c52a590c5b) | Aug 02, 2022 |
| ASRock        | Z390 Extreme4               | [9983a0cc64](https://linux-hardware.org/?probe=9983a0cc64) | Aug 02, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | [4bd0f9e461](https://linux-hardware.org/?probe=4bd0f9e461) | Aug 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [015ec264f5](https://linux-hardware.org/?probe=015ec264f5) | Aug 02, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [37b8171416](https://linux-hardware.org/?probe=37b8171416) | Aug 01, 2022 |
| MSI           | 970A-G46                    | [44a7f8800c](https://linux-hardware.org/?probe=44a7f8800c) | Aug 01, 2022 |
| MSI           | H81M-E34                    | [c0be356e96](https://linux-hardware.org/?probe=c0be356e96) | Aug 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [dcccfd1beb](https://linux-hardware.org/?probe=dcccfd1beb) | Aug 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8ea1e0f22c](https://linux-hardware.org/?probe=8ea1e0f22c) | Aug 01, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [4956d72048](https://linux-hardware.org/?probe=4956d72048) | Aug 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [163affcbb8](https://linux-hardware.org/?probe=163affcbb8) | Aug 01, 2022 |
| ASUSTek       | M2N-MX SE Plus              | [7a0035ad18](https://linux-hardware.org/?probe=7a0035ad18) | Jul 31, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [f6a106d6df](https://linux-hardware.org/?probe=f6a106d6df) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | [d8bfe4a00b](https://linux-hardware.org/?probe=d8bfe4a00b) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0f72d43717](https://linux-hardware.org/?probe=0f72d43717) | Jul 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9dd9d17e79](https://linux-hardware.org/?probe=9dd9d17e79) | Jul 31, 2022 |
| ASRock        | X570 Steel Legend           | [f43e0c2c81](https://linux-hardware.org/?probe=f43e0c2c81) | Jul 31, 2022 |
| ASUSTek       | M4A77TD                     | [f10ef09086](https://linux-hardware.org/?probe=f10ef09086) | Jul 30, 2022 |
| Gateway       | DX4860                      | [279b6793e4](https://linux-hardware.org/?probe=279b6793e4) | Jul 30, 2022 |
| Gateway       | DX4860                      | [fec12bcbe9](https://linux-hardware.org/?probe=fec12bcbe9) | Jul 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9a7de8cc64](https://linux-hardware.org/?probe=9a7de8cc64) | Jul 30, 2022 |
| Gigabyte      | H61M-DS2V                   | [e5744803f2](https://linux-hardware.org/?probe=e5744803f2) | Jul 29, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [9258c864d5](https://linux-hardware.org/?probe=9258c864d5) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3b661517b1](https://linux-hardware.org/?probe=3b661517b1) | Jul 29, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [efa02942f2](https://linux-hardware.org/?probe=efa02942f2) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [25d688e258](https://linux-hardware.org/?probe=25d688e258) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [93caf82d7a](https://linux-hardware.org/?probe=93caf82d7a) | Jul 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c0ce536184](https://linux-hardware.org/?probe=c0ce536184) | Jul 29, 2022 |
| Pegatron      | IPM41-D3                    | [ce24b0bab7](https://linux-hardware.org/?probe=ce24b0bab7) | Jul 28, 2022 |
| ASUSTek       | WS Z390 PRO                 | [256172b01e](https://linux-hardware.org/?probe=256172b01e) | Jul 28, 2022 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | [757ba0f252](https://linux-hardware.org/?probe=757ba0f252) | Jul 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a9c3256946](https://linux-hardware.org/?probe=a9c3256946) | Jul 28, 2022 |
| ASRock        | B450M Pro4-F                | [af4d396115](https://linux-hardware.org/?probe=af4d396115) | Jul 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [32e82dc9ae](https://linux-hardware.org/?probe=32e82dc9ae) | Jul 27, 2022 |
| HP            | 1494                        | [6805afe809](https://linux-hardware.org/?probe=6805afe809) | Jul 27, 2022 |
| MSI           | B450M PRO-VDH MAX           | [d63a6f2607](https://linux-hardware.org/?probe=d63a6f2607) | Jul 26, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [a0e19ce405](https://linux-hardware.org/?probe=a0e19ce405) | Jul 26, 2022 |
| ASRock        | Z690 PG Riptide             | [87c499b088](https://linux-hardware.org/?probe=87c499b088) | Jul 26, 2022 |
| MSI           | B150M PRO-VD                | [8194e1dc19](https://linux-hardware.org/?probe=8194e1dc19) | Jul 26, 2022 |
| ASRock        | B450M Steel Legend          | [30fd52a2a5](https://linux-hardware.org/?probe=30fd52a2a5) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [3a34e9c018](https://linux-hardware.org/?probe=3a34e9c018) | Jul 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2632256ed7](https://linux-hardware.org/?probe=2632256ed7) | Jul 25, 2022 |
| ASUSTek       | H81M-K                      | [a3eeaecb07](https://linux-hardware.org/?probe=a3eeaecb07) | Jul 25, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [24fec424ff](https://linux-hardware.org/?probe=24fec424ff) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f00c831f5b](https://linux-hardware.org/?probe=f00c831f5b) | Jul 25, 2022 |
| MSI           | B365M PRO-VH                | [f254ee30b7](https://linux-hardware.org/?probe=f254ee30b7) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | [58f727d948](https://linux-hardware.org/?probe=58f727d948) | Jul 25, 2022 |
| Dell          | 0DF42J A00                  | [6a75ac249a](https://linux-hardware.org/?probe=6a75ac249a) | Jul 24, 2022 |
| ASUSTek       | Z170-P                      | [85e3fee140](https://linux-hardware.org/?probe=85e3fee140) | Jul 24, 2022 |
| MSI           | 2A9C                        | [b0441c833d](https://linux-hardware.org/?probe=b0441c833d) | Jul 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8bb191bc8f](https://linux-hardware.org/?probe=8bb191bc8f) | Jul 24, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [793c3d4e22](https://linux-hardware.org/?probe=793c3d4e22) | Jul 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [2ae14bcbc1](https://linux-hardware.org/?probe=2ae14bcbc1) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [9c0899916c](https://linux-hardware.org/?probe=9c0899916c) | Jul 23, 2022 |
| ASUSTek       | SABERTOOTH X79              | [88c35211e1](https://linux-hardware.org/?probe=88c35211e1) | Jul 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9c1f5f7a4e](https://linux-hardware.org/?probe=9c1f5f7a4e) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [6889befce9](https://linux-hardware.org/?probe=6889befce9) | Jul 23, 2022 |
| MSI           | PRO Z690-A                  | [9264d3b652](https://linux-hardware.org/?probe=9264d3b652) | Jul 22, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [edcecb5e13](https://linux-hardware.org/?probe=edcecb5e13) | Jul 22, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [f90d74f5b5](https://linux-hardware.org/?probe=f90d74f5b5) | Jul 22, 2022 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | [cda18f8739](https://linux-hardware.org/?probe=cda18f8739) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6e4f170da9](https://linux-hardware.org/?probe=6e4f170da9) | Jul 22, 2022 |
| ASUSTek       | P7H55-M                     | [d7ba204d31](https://linux-hardware.org/?probe=d7ba204d31) | Jul 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d758abd21c](https://linux-hardware.org/?probe=d758abd21c) | Jul 22, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [d57e35934f](https://linux-hardware.org/?probe=d57e35934f) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [41dbccf7d9](https://linux-hardware.org/?probe=41dbccf7d9) | Jul 21, 2022 |
| Dell          | 0WMJ54 A01                  | [dace7a0b12](https://linux-hardware.org/?probe=dace7a0b12) | Jul 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b54cb1f930](https://linux-hardware.org/?probe=b54cb1f930) | Jul 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | [9c98b2fcd6](https://linux-hardware.org/?probe=9c98b2fcd6) | Jul 21, 2022 |
| ASRock        | H81M-HG4 R4.0               | [4628e310fd](https://linux-hardware.org/?probe=4628e310fd) | Jul 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f42ed5053a](https://linux-hardware.org/?probe=f42ed5053a) | Jul 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6e4fbc6688](https://linux-hardware.org/?probe=6e4fbc6688) | Jul 20, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c763e49e7e](https://linux-hardware.org/?probe=c763e49e7e) | Jul 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a04d18d87a](https://linux-hardware.org/?probe=a04d18d87a) | Jul 20, 2022 |
| Foxconn       | 2AB1                        | [c269d962ea](https://linux-hardware.org/?probe=c269d962ea) | Jul 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8cae76caea](https://linux-hardware.org/?probe=8cae76caea) | Jul 20, 2022 |
| NCR           | Pocono BIOS.6.0             | [3026f24fe3](https://linux-hardware.org/?probe=3026f24fe3) | Jul 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [190936df71](https://linux-hardware.org/?probe=190936df71) | Jul 19, 2022 |
| ASUSTek       | M11BB                       | [582292657c](https://linux-hardware.org/?probe=582292657c) | Jul 18, 2022 |
| MSI           | MEG B550 UNIFY              | [d6ecbbbfda](https://linux-hardware.org/?probe=d6ecbbbfda) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [39fd39c3b0](https://linux-hardware.org/?probe=39fd39c3b0) | Jul 17, 2022 |
| ASRock        | AD2700-ITX                  | [870cda5796](https://linux-hardware.org/?probe=870cda5796) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [aae1bec902](https://linux-hardware.org/?probe=aae1bec902) | Jul 17, 2022 |
| MSI           | X370 KRAIT GAMING           | [e74a442ccc](https://linux-hardware.org/?probe=e74a442ccc) | Jul 17, 2022 |
| Huanan        | B75                         | [0580a5a948](https://linux-hardware.org/?probe=0580a5a948) | Jul 17, 2022 |
| Huanan        | B75                         | [e1788853ec](https://linux-hardware.org/?probe=e1788853ec) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [326c97ba50](https://linux-hardware.org/?probe=326c97ba50) | Jul 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [d60e6afc41](https://linux-hardware.org/?probe=d60e6afc41) | Jul 16, 2022 |
| Gigabyte      | GA-A55M-S2V                 | [713765e224](https://linux-hardware.org/?probe=713765e224) | Jul 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [41517adf39](https://linux-hardware.org/?probe=41517adf39) | Jul 16, 2022 |
| HP            | 802E                        | [c86ddd647b](https://linux-hardware.org/?probe=c86ddd647b) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [34a905d705](https://linux-hardware.org/?probe=34a905d705) | Jul 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [fc316a6331](https://linux-hardware.org/?probe=fc316a6331) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [86ac444b35](https://linux-hardware.org/?probe=86ac444b35) | Jul 15, 2022 |
| HP            | 88BF                        | [92b12df551](https://linux-hardware.org/?probe=92b12df551) | Jul 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [1338941bd0](https://linux-hardware.org/?probe=1338941bd0) | Jul 15, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [7efe67fd9a](https://linux-hardware.org/?probe=7efe67fd9a) | Jul 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [f655a34cc1](https://linux-hardware.org/?probe=f655a34cc1) | Jul 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e9c788dfd2](https://linux-hardware.org/?probe=e9c788dfd2) | Jul 14, 2022 |
| ASUSTek       | M5A97 PRO                   | [e963ba85db](https://linux-hardware.org/?probe=e963ba85db) | Jul 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [165cdc7df2](https://linux-hardware.org/?probe=165cdc7df2) | Jul 14, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ea3f033d93](https://linux-hardware.org/?probe=ea3f033d93) | Jul 14, 2022 |
| ASUSTek       | PRIME Z390-A                | [7486493ea1](https://linux-hardware.org/?probe=7486493ea1) | Jul 14, 2022 |
| Dell          | 0J3C2F A00                  | [e9be99b44d](https://linux-hardware.org/?probe=e9be99b44d) | Jul 14, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [4355281f8e](https://linux-hardware.org/?probe=4355281f8e) | Jul 13, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [36f96a4ef6](https://linux-hardware.org/?probe=36f96a4ef6) | Jul 13, 2022 |
| ASRock        | X570 Taichi                 | [98ffa2e8b0](https://linux-hardware.org/?probe=98ffa2e8b0) | Jul 13, 2022 |
| HP            | 1632                        | [d2582aff1d](https://linux-hardware.org/?probe=d2582aff1d) | Jul 12, 2022 |
| HP            | 8768 A                      | [f4afb80e18](https://linux-hardware.org/?probe=f4afb80e18) | Jul 12, 2022 |
| Lenovo        | Annapurna CRB NOK           | [46d0d5dccc](https://linux-hardware.org/?probe=46d0d5dccc) | Jul 12, 2022 |
| MSI           | Z370-OC PRO                 | [2c9d1d78df](https://linux-hardware.org/?probe=2c9d1d78df) | Jul 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ce2e8f2a2a](https://linux-hardware.org/?probe=ce2e8f2a2a) | Jul 12, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [c69dd8da85](https://linux-hardware.org/?probe=c69dd8da85) | Jul 12, 2022 |
| MSI           | H97M-G43                    | [c8b2844540](https://linux-hardware.org/?probe=c8b2844540) | Jul 11, 2022 |
| HP            | 3646h                       | [88b38da161](https://linux-hardware.org/?probe=88b38da161) | Jul 11, 2022 |
| Dell          | 02YYK5 A00                  | [6592ae8873](https://linux-hardware.org/?probe=6592ae8873) | Jul 11, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [05b0102f01](https://linux-hardware.org/?probe=05b0102f01) | Jul 11, 2022 |
| Dell          | 0XCR8D A03                  | [b6771bbe08](https://linux-hardware.org/?probe=b6771bbe08) | Jul 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [84f993f04d](https://linux-hardware.org/?probe=84f993f04d) | Jul 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [8739a403bc](https://linux-hardware.org/?probe=8739a403bc) | Jul 11, 2022 |
| Dell          | 09WH54 A00                  | [8570e35470](https://linux-hardware.org/?probe=8570e35470) | Jul 11, 2022 |
| ASUSTek       | PRIME X470-PRO              | [314c3aaf0e](https://linux-hardware.org/?probe=314c3aaf0e) | Jul 10, 2022 |
| ASUSTek       | PRIME X470-PRO              | [d6f1e47bf5](https://linux-hardware.org/?probe=d6f1e47bf5) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | [cf71ced9a0](https://linux-hardware.org/?probe=cf71ced9a0) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | [cf470317b1](https://linux-hardware.org/?probe=cf470317b1) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [45e46ac933](https://linux-hardware.org/?probe=45e46ac933) | Jul 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [cdf7b9a4d1](https://linux-hardware.org/?probe=cdf7b9a4d1) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | [4245ef07db](https://linux-hardware.org/?probe=4245ef07db) | Jul 10, 2022 |
| Intel         | DH61WW AAG23116-301         | [3b4120b3af](https://linux-hardware.org/?probe=3b4120b3af) | Jul 09, 2022 |
| MSI           | PRO B660M-A DDR4            | [65c661af95](https://linux-hardware.org/?probe=65c661af95) | Jul 09, 2022 |
| ZOTAC         | Unknown                     | [70105d0f43](https://linux-hardware.org/?probe=70105d0f43) | Jul 09, 2022 |
| ASRock        | Z170 Extreme4               | [34f14d654f](https://linux-hardware.org/?probe=34f14d654f) | Jul 09, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [6513be6d44](https://linux-hardware.org/?probe=6513be6d44) | Jul 09, 2022 |
| Gigabyte      | X99-UD4-CF                  | [1dafd7beed](https://linux-hardware.org/?probe=1dafd7beed) | Jul 09, 2022 |
| HP            | 8455                        | [62b146bca0](https://linux-hardware.org/?probe=62b146bca0) | Jul 08, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [44db6036ce](https://linux-hardware.org/?probe=44db6036ce) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [546a26c882](https://linux-hardware.org/?probe=546a26c882) | Jul 07, 2022 |
| HP            | 8455                        | [9954a77308](https://linux-hardware.org/?probe=9954a77308) | Jul 07, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [4da61d3e61](https://linux-hardware.org/?probe=4da61d3e61) | Jul 07, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [234b2b0ee8](https://linux-hardware.org/?probe=234b2b0ee8) | Jul 07, 2022 |
| ECS           | H61H2-MV                    | [80e2fc79da](https://linux-hardware.org/?probe=80e2fc79da) | Jul 07, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [342362a5f8](https://linux-hardware.org/?probe=342362a5f8) | Jul 06, 2022 |
| MSI           | G31TM-P21                   | [8c15268c47](https://linux-hardware.org/?probe=8c15268c47) | Jul 06, 2022 |
| Unknown       | Unknown                     | [c22b57692e](https://linux-hardware.org/?probe=c22b57692e) | Jul 06, 2022 |
| MSI           | G31TM-P21                   | [a0a2cd9568](https://linux-hardware.org/?probe=a0a2cd9568) | Jul 06, 2022 |
| Lenovo        | 3098 NOK                    | [0fb5f3cc66](https://linux-hardware.org/?probe=0fb5f3cc66) | Jul 06, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [699e033557](https://linux-hardware.org/?probe=699e033557) | Jul 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [54f8e71da0](https://linux-hardware.org/?probe=54f8e71da0) | Jul 06, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [0954f0b44c](https://linux-hardware.org/?probe=0954f0b44c) | Jul 06, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [779bc20f77](https://linux-hardware.org/?probe=779bc20f77) | Jul 05, 2022 |
| ASRock        | 990FX Killer                | [28b0984086](https://linux-hardware.org/?probe=28b0984086) | Jul 05, 2022 |
| Gigabyte      | H77N-WIFI                   | [e795477a20](https://linux-hardware.org/?probe=e795477a20) | Jul 05, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [a74834b383](https://linux-hardware.org/?probe=a74834b383) | Jul 04, 2022 |
| MSI           | MEG X570 UNIFY              | [f1de99a0da](https://linux-hardware.org/?probe=f1de99a0da) | Jul 04, 2022 |
| MSI           | MS-B0A1                     | [9b53e39bad](https://linux-hardware.org/?probe=9b53e39bad) | Jul 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [729fab1a51](https://linux-hardware.org/?probe=729fab1a51) | Jul 04, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [58b8e08cf9](https://linux-hardware.org/?probe=58b8e08cf9) | Jul 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | [7f4faab065](https://linux-hardware.org/?probe=7f4faab065) | Jul 04, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [a6fb0fd95c](https://linux-hardware.org/?probe=a6fb0fd95c) | Jul 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | [24d32e73bd](https://linux-hardware.org/?probe=24d32e73bd) | Jul 03, 2022 |
| Intel         | DP55KG AAE47218-404         | [aaa7656f44](https://linux-hardware.org/?probe=aaa7656f44) | Jul 03, 2022 |
| MSI           | Z97 GAMING 5                | [6a1978f197](https://linux-hardware.org/?probe=6a1978f197) | Jul 02, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [963029db26](https://linux-hardware.org/?probe=963029db26) | Jul 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [1bec4af414](https://linux-hardware.org/?probe=1bec4af414) | Jul 02, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [2d22d14874](https://linux-hardware.org/?probe=2d22d14874) | Jul 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8e6d23cf01](https://linux-hardware.org/?probe=8e6d23cf01) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | [a32cb9b3f1](https://linux-hardware.org/?probe=a32cb9b3f1) | Jul 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a658ebf5e9](https://linux-hardware.org/?probe=a658ebf5e9) | Jul 01, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | [febb798e92](https://linux-hardware.org/?probe=febb798e92) | Jul 01, 2022 |
| Dell          | 0M9KCM A00                  | [e72232ee43](https://linux-hardware.org/?probe=e72232ee43) | Jul 01, 2022 |
| Gigabyte      | Z87-HD3                     | [c38c4e9cb9](https://linux-hardware.org/?probe=c38c4e9cb9) | Jun 30, 2022 |
| Dell          | 0M9KCM A00                  | [5e80242b43](https://linux-hardware.org/?probe=5e80242b43) | Jun 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7e14880c80](https://linux-hardware.org/?probe=7e14880c80) | Jun 30, 2022 |
| ASUSTek       | PRIME Z370-A                | [28479b3edf](https://linux-hardware.org/?probe=28479b3edf) | Jun 30, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [cea6c9ea52](https://linux-hardware.org/?probe=cea6c9ea52) | Jun 30, 2022 |
| Gigabyte      | GB-BSi5-1135G7              | [4701b81ce2](https://linux-hardware.org/?probe=4701b81ce2) | Jun 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [163a5c29e6](https://linux-hardware.org/?probe=163a5c29e6) | Jun 30, 2022 |
| Gigabyte      | B560M DS3H V2               | [85b8793585](https://linux-hardware.org/?probe=85b8793585) | Jun 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [01d9100427](https://linux-hardware.org/?probe=01d9100427) | Jun 29, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [392d5c7c12](https://linux-hardware.org/?probe=392d5c7c12) | Jun 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [66b8ec6b28](https://linux-hardware.org/?probe=66b8ec6b28) | Jun 29, 2022 |
| Gigabyte      | D525TUD                     | [b6cfc5d2df](https://linux-hardware.org/?probe=b6cfc5d2df) | Jun 28, 2022 |
| Gigabyte      | B85M-D3V-A                  | [3417dd6a9a](https://linux-hardware.org/?probe=3417dd6a9a) | Jun 28, 2022 |
| Gigabyte      | G41MT-D3                    | [20de16a046](https://linux-hardware.org/?probe=20de16a046) | Jun 28, 2022 |
| ASRock        | N68-VS3 UCC                 | [2c7959c607](https://linux-hardware.org/?probe=2c7959c607) | Jun 26, 2022 |
| ASUSTek       | PRIME H410M-E               | [3eb97735b3](https://linux-hardware.org/?probe=3eb97735b3) | Jun 26, 2022 |
| HP            | 3398                        | [4241fd0ba0](https://linux-hardware.org/?probe=4241fd0ba0) | Jun 26, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [9a853085ea](https://linux-hardware.org/?probe=9a853085ea) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bb3f7f9534](https://linux-hardware.org/?probe=bb3f7f9534) | Jun 26, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [519e378380](https://linux-hardware.org/?probe=519e378380) | Jun 25, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [6c6d94e4b7](https://linux-hardware.org/?probe=6c6d94e4b7) | Jun 25, 2022 |
| BESSTAR Te... | HM90                        | [e8a4e37cc6](https://linux-hardware.org/?probe=e8a4e37cc6) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | [47cf388077](https://linux-hardware.org/?probe=47cf388077) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [c3c48bb18e](https://linux-hardware.org/?probe=c3c48bb18e) | Jun 25, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [c6c59e12b6](https://linux-hardware.org/?probe=c6c59e12b6) | Jun 25, 2022 |
| MSI           | B360M MORTAR                | [607f489961](https://linux-hardware.org/?probe=607f489961) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | [73eb3e0db6](https://linux-hardware.org/?probe=73eb3e0db6) | Jun 25, 2022 |
| HP            | 89D8 SMVB                   | [f92ff0c37f](https://linux-hardware.org/?probe=f92ff0c37f) | Jun 24, 2022 |
| MSI           | IONA                        | [9f4e8871a7](https://linux-hardware.org/?probe=9f4e8871a7) | Jun 24, 2022 |
| Dell          | 0VRWRC A00                  | [373df03a96](https://linux-hardware.org/?probe=373df03a96) | Jun 24, 2022 |
| ASRock        | H77 Pro4/MVP                | [f022b1b430](https://linux-hardware.org/?probe=f022b1b430) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [5129e4893a](https://linux-hardware.org/?probe=5129e4893a) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [dbfad9b8fe](https://linux-hardware.org/?probe=dbfad9b8fe) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [6f13e0f8a0](https://linux-hardware.org/?probe=6f13e0f8a0) | Jun 23, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| Unknown       | HX90                        | [837e70229a](https://linux-hardware.org/?probe=837e70229a) | Jun 23, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [167acd417b](https://linux-hardware.org/?probe=167acd417b) | Jun 23, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [d11995947a](https://linux-hardware.org/?probe=d11995947a) | Jun 23, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [92944b1e97](https://linux-hardware.org/?probe=92944b1e97) | Jun 22, 2022 |
| HP            | 2B05                        | [677bb9d569](https://linux-hardware.org/?probe=677bb9d569) | Jun 22, 2022 |
| ASRock        | B550M Pro4                  | [45871f6d61](https://linux-hardware.org/?probe=45871f6d61) | Jun 22, 2022 |
| ASRock        | B450 Gaming K4              | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Dell          | 02YYK5 A00                  | [7a571de1b9](https://linux-hardware.org/?probe=7a571de1b9) | Jun 22, 2022 |
| System76      | Thelio Mira thelio-mira-... | [58c9da7f20](https://linux-hardware.org/?probe=58c9da7f20) | Jun 22, 2022 |
| MSI           | B85M-E45                    | [f5e1312d31](https://linux-hardware.org/?probe=f5e1312d31) | Jun 22, 2022 |
| Gigabyte      | H61M-S2P                    | [ac99674975](https://linux-hardware.org/?probe=ac99674975) | Jun 22, 2022 |
| Dell          | 04YP6J A02                  | [11151bb62c](https://linux-hardware.org/?probe=11151bb62c) | Jun 22, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [04927da7b6](https://linux-hardware.org/?probe=04927da7b6) | Jun 22, 2022 |
| ASRock        | Z690M-ITX/ax                | [cc8224a123](https://linux-hardware.org/?probe=cc8224a123) | Jun 21, 2022 |
| ASRock        | Z690M-ITX/ax                | [1d3eb4348d](https://linux-hardware.org/?probe=1d3eb4348d) | Jun 21, 2022 |
| ASRock        | Z690M-ITX/ax                | [35bec2520a](https://linux-hardware.org/?probe=35bec2520a) | Jun 21, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [f3176204c8](https://linux-hardware.org/?probe=f3176204c8) | Jun 21, 2022 |
| MSI           | B450-A PRO MAX              | [490076a383](https://linux-hardware.org/?probe=490076a383) | Jun 20, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [b7a6099e25](https://linux-hardware.org/?probe=b7a6099e25) | Jun 20, 2022 |
| MSI           | MS-B0A1                     | [3193cbe3fd](https://linux-hardware.org/?probe=3193cbe3fd) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [a384703b5e](https://linux-hardware.org/?probe=a384703b5e) | Jun 20, 2022 |
| MSI           | 2A9C                        | [73dd2172d3](https://linux-hardware.org/?probe=73dd2172d3) | Jun 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [560fa88cad](https://linux-hardware.org/?probe=560fa88cad) | Jun 19, 2022 |
| HP            | 2B05                        | [a49ebb4aed](https://linux-hardware.org/?probe=a49ebb4aed) | Jun 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [4fc1134f6d](https://linux-hardware.org/?probe=4fc1134f6d) | Jun 19, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [a59676f7be](https://linux-hardware.org/?probe=a59676f7be) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [707f314c74](https://linux-hardware.org/?probe=707f314c74) | Jun 19, 2022 |
| MSI           | H510I PRO WIFI              | [b9d3cb4755](https://linux-hardware.org/?probe=b9d3cb4755) | Jun 18, 2022 |
| ASUSTek       | Q170M2                      | [76f5dd0027](https://linux-hardware.org/?probe=76f5dd0027) | Jun 18, 2022 |
| ASUSTek       | Q170M2                      | [32713d6759](https://linux-hardware.org/?probe=32713d6759) | Jun 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4801136187](https://linux-hardware.org/?probe=4801136187) | Jun 18, 2022 |
| MSI           | X99A RAIDER                 | [550772184f](https://linux-hardware.org/?probe=550772184f) | Jun 18, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | [292cc4bcab](https://linux-hardware.org/?probe=292cc4bcab) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [f54dda344d](https://linux-hardware.org/?probe=f54dda344d) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [6647ddd346](https://linux-hardware.org/?probe=6647ddd346) | Jun 17, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [dfed0867e1](https://linux-hardware.org/?probe=dfed0867e1) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | [7205fff536](https://linux-hardware.org/?probe=7205fff536) | Jun 17, 2022 |
| MSI           | MAG B460M MORTAR            | [9074247e52](https://linux-hardware.org/?probe=9074247e52) | Jun 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [680bf4c033](https://linux-hardware.org/?probe=680bf4c033) | Jun 17, 2022 |
| Dell          | 08NPPY A00                  | [93eb00c3c5](https://linux-hardware.org/?probe=93eb00c3c5) | Jun 16, 2022 |
| Dell          | 0XC7MM A01                  | [8c8a1ef522](https://linux-hardware.org/?probe=8c8a1ef522) | Jun 16, 2022 |
| ASUSTek       | PRIME A320M-K               | [17e9f5a71f](https://linux-hardware.org/?probe=17e9f5a71f) | Jun 16, 2022 |
| Gigabyte      | H87N-WIFI                   | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| ASUSTek       | PRIME B550M-A               | [527aea0d6e](https://linux-hardware.org/?probe=527aea0d6e) | Jun 16, 2022 |
| ASRock        | B550M-ITX/ac                | [42fd0dcad9](https://linux-hardware.org/?probe=42fd0dcad9) | Jun 16, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [08527d664b](https://linux-hardware.org/?probe=08527d664b) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [8d106f8677](https://linux-hardware.org/?probe=8d106f8677) | Jun 16, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [701de0d7ad](https://linux-hardware.org/?probe=701de0d7ad) | Jun 15, 2022 |
| ASRock        | B450M Pro4                  | [041f94473b](https://linux-hardware.org/?probe=041f94473b) | Jun 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [9418d283c9](https://linux-hardware.org/?probe=9418d283c9) | Jun 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [131a938c5e](https://linux-hardware.org/?probe=131a938c5e) | Jun 14, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [e61344b416](https://linux-hardware.org/?probe=e61344b416) | Jun 14, 2022 |
| Gigabyte      | H61M-S2PV                   | [cc88cec642](https://linux-hardware.org/?probe=cc88cec642) | Jun 14, 2022 |
| ASUSTek       | PRIME Z370-A                | [1bb2aa2c68](https://linux-hardware.org/?probe=1bb2aa2c68) | Jun 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [7990c32699](https://linux-hardware.org/?probe=7990c32699) | Jun 14, 2022 |
| Dell          | 00V62H A00                  | [dc89caf09f](https://linux-hardware.org/?probe=dc89caf09f) | Jun 13, 2022 |
| Gigabyte      | B560M DS3H V2               | [61d456c166](https://linux-hardware.org/?probe=61d456c166) | Jun 13, 2022 |
| ASUSTek       | H87-PLUS                    | [1c5488bdf7](https://linux-hardware.org/?probe=1c5488bdf7) | Jun 13, 2022 |
| ASUSTek       | H87-PLUS                    | [fd8af28ed5](https://linux-hardware.org/?probe=fd8af28ed5) | Jun 13, 2022 |
| ASRock        | B450M/ac R2.0               | [bc509480d2](https://linux-hardware.org/?probe=bc509480d2) | Jun 13, 2022 |
| ASRock        | FM2A88X Extreme6+           | [dcd3256961](https://linux-hardware.org/?probe=dcd3256961) | Jun 13, 2022 |
| HP            | 18E5                        | [275b8ca77c](https://linux-hardware.org/?probe=275b8ca77c) | Jun 12, 2022 |
| ASUSTek       | P5K Premium                 | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [0c0715a9b2](https://linux-hardware.org/?probe=0c0715a9b2) | Jun 12, 2022 |
| Gigabyte      | B75-D3V                     | [f0fe22dfe7](https://linux-hardware.org/?probe=f0fe22dfe7) | Jun 12, 2022 |
| ASUSTek       | P5G41T-M                    | [0fd96bfcf3](https://linux-hardware.org/?probe=0fd96bfcf3) | Jun 12, 2022 |
| Gigabyte      | H77N-WIFI                   | [23fa842567](https://linux-hardware.org/?probe=23fa842567) | Jun 11, 2022 |
| MSI           | B450M MORTAR                | [18240b9552](https://linux-hardware.org/?probe=18240b9552) | Jun 11, 2022 |
| Gigabyte      | GA-MA69GM-S2H               | [a382b54934](https://linux-hardware.org/?probe=a382b54934) | Jun 11, 2022 |
| Gigabyte      | H77N-WIFI                   | [fd1478145b](https://linux-hardware.org/?probe=fd1478145b) | Jun 11, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [661f4f701b](https://linux-hardware.org/?probe=661f4f701b) | Jun 10, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [b771c75e31](https://linux-hardware.org/?probe=b771c75e31) | Jun 10, 2022 |
| ASUSTek       | PRIME B360M-A               | [272c6283d4](https://linux-hardware.org/?probe=272c6283d4) | Jun 10, 2022 |
| Gigabyte      | H55M-S2                     | [86b61f1ef6](https://linux-hardware.org/?probe=86b61f1ef6) | Jun 10, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [267db233fa](https://linux-hardware.org/?probe=267db233fa) | Jun 10, 2022 |
| Unknown       | Unknown                     | [4a2f4f8cb1](https://linux-hardware.org/?probe=4a2f4f8cb1) | Jun 09, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | [4458c8a8ca](https://linux-hardware.org/?probe=4458c8a8ca) | Jun 09, 2022 |
| Intel         | X79 V2.4E                   | [12a530acde](https://linux-hardware.org/?probe=12a530acde) | Jun 09, 2022 |
| ASUSTek       | Z170-A                      | [87fa4e032d](https://linux-hardware.org/?probe=87fa4e032d) | Jun 09, 2022 |
| ASUSTek       | Z170-A                      | [3531488e43](https://linux-hardware.org/?probe=3531488e43) | Jun 09, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [35b29ccf1d](https://linux-hardware.org/?probe=35b29ccf1d) | Jun 08, 2022 |
| Gigabyte      | A520M DS3H                  | [e12c11bc94](https://linux-hardware.org/?probe=e12c11bc94) | Jun 08, 2022 |
| Gigabyte      | G41MT-D3                    | [2ac69cc327](https://linux-hardware.org/?probe=2ac69cc327) | Jun 08, 2022 |
| Gigabyte      | B450 GAMING X               | [34e884bb50](https://linux-hardware.org/?probe=34e884bb50) | Jun 08, 2022 |
| HP            | 872D                        | [c27f333c46](https://linux-hardware.org/?probe=c27f333c46) | Jun 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Fedora 36 | 636      | 18.37%  |
| Fedora 33 | 562      | 16.23%  |
| Fedora 35 | 527      | 15.22%  |
| Fedora 34 | 518      | 14.96%  |
| Fedora 32 | 518      | 14.96%  |
| Fedora 31 | 343      | 9.9%    |
| Fedora 30 | 132      | 3.81%   |
| Fedora 37 | 120      | 3.47%   |
| Fedora 29 | 75       | 2.17%   |
| Fedora 28 | 13       | 0.38%   |
| Fedora 27 | 9        | 0.26%   |
| Fedora 38 | 2        | 0.06%   |
| Fedora 25 | 2        | 0.06%   |
| Fedora 24 | 2        | 0.06%   |
| Fedora 4  | 1        | 0.03%   |
| Fedora 21 | 1        | 0.03%   |
| Fedora 17 | 1        | 0.03%   |
| Fedora 14 | 1        | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Fedora | 3014     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.9.16-200.fc33.x86_64  | 58       | 1.46%   |
| 5.16.18-200.fc35.x86_64 | 57       | 1.43%   |
| 5.17.5-300.fc36.x86_64  | 47       | 1.18%   |
| 5.18.13-200.fc36.x86_64 | 42       | 1.06%   |
| 5.13.12-200.fc34.x86_64 | 39       | 0.98%   |
| 5.19.16-200.fc36.x86_64 | 38       | 0.95%   |
| 5.14.10-300.fc35.x86_64 | 36       | 0.9%    |
| 5.11.12-300.fc34.x86_64 | 35       | 0.88%   |
| 5.8.4-200.fc32.x86_64   | 33       | 0.83%   |
| 5.8.15-301.fc33.x86_64  | 33       | 0.83%   |
| 6.0.5-200.fc36.x86_64   | 32       | 0.8%    |
| 5.19.9-200.fc36.x86_64  | 31       | 0.78%   |
| 5.18.16-200.fc36.x86_64 | 31       | 0.78%   |
| 5.18.11-200.fc36.x86_64 | 31       | 0.78%   |
| 5.6.19-300.fc32.x86_64  | 30       | 0.75%   |
| 5.18.5-200.fc36.x86_64  | 30       | 0.75%   |
| 5.12.13-300.fc34.x86_64 | 30       | 0.75%   |
| 5.8.18-300.fc33.x86_64  | 29       | 0.73%   |
| 5.15.6-200.fc35.x86_64  | 29       | 0.73%   |
| 5.8.16-300.fc33.x86_64  | 28       | 0.7%    |
| 6.0.9-300.fc37.x86_64   | 26       | 0.65%   |
| 6.0.8-300.fc37.x86_64   | 26       | 0.65%   |
| 5.9.11-200.fc33.x86_64  | 26       | 0.65%   |
| 5.3.16-300.fc31.x86_64  | 26       | 0.65%   |
| 5.7.10-201.fc32.x86_64  | 25       | 0.63%   |
| 5.16.16-200.fc35.x86_64 | 25       | 0.63%   |
| 5.11.11-200.fc33.x86_64 | 25       | 0.63%   |
| 5.9.8-200.fc33.x86_64   | 24       | 0.6%    |
| 5.11.16-300.fc34.x86_64 | 24       | 0.6%    |
| 5.19.6-200.fc36.x86_64  | 23       | 0.58%   |
| 5.17.6-300.fc36.x86_64  | 23       | 0.58%   |
| 5.14.9-200.fc34.x86_64  | 23       | 0.58%   |
| 5.12.8-300.fc34.x86_64  | 23       | 0.58%   |
| 5.8.11-200.fc32.x86_64  | 22       | 0.55%   |
| 5.7.15-200.fc32.x86_64  | 22       | 0.55%   |
| 5.17.4-200.fc35.x86_64  | 22       | 0.55%   |
| 5.16.9-200.fc35.x86_64  | 22       | 0.55%   |
| 5.6.6-300.fc32.x86_64   | 21       | 0.53%   |
| 5.19.8-200.fc36.x86_64  | 21       | 0.53%   |
| 5.15.12-200.fc35.x86_64 | 21       | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 67       | 1.68%   |
| 5.16.18 | 65       | 1.63%   |
| 5.17.5  | 63       | 1.58%   |
| 5.19.16 | 57       | 1.43%   |
| 5.8.15  | 53       | 1.33%   |
| 5.8.18  | 47       | 1.18%   |
| 5.18.13 | 43       | 1.08%   |
| 5.8.16  | 40       | 1.01%   |
| 5.13.12 | 40       | 1.01%   |
| 5.19.9  | 39       | 0.98%   |
| 5.14.10 | 38       | 0.96%   |
| 6.0.8   | 37       | 0.93%   |
| 5.11.12 | 37       | 0.93%   |
| 5.11.11 | 37       | 0.93%   |
| 6.0.5   | 35       | 0.88%   |
| 6.0.9   | 34       | 0.85%   |
| 5.18.5  | 34       | 0.85%   |
| 5.8.4   | 33       | 0.83%   |
| 5.18.16 | 32       | 0.8%    |
| 5.18.11 | 32       | 0.8%    |
| 5.12.13 | 32       | 0.8%    |
| 5.6.19  | 31       | 0.78%   |
| 5.14.18 | 31       | 0.78%   |
| 5.12.8  | 30       | 0.75%   |
| 5.15.6  | 29       | 0.73%   |
| 5.9.11  | 28       | 0.7%    |
| 5.19.6  | 28       | 0.7%    |
| 5.17.6  | 28       | 0.7%    |
| 5.14.9  | 28       | 0.7%    |
| 5.6.6   | 27       | 0.68%   |
| 5.17.11 | 27       | 0.68%   |
| 5.11.16 | 27       | 0.68%   |
| 5.9.8   | 26       | 0.65%   |
| 5.7.15  | 26       | 0.65%   |
| 5.3.16  | 26       | 0.65%   |
| 5.19.8  | 26       | 0.65%   |
| 5.17.4  | 26       | 0.65%   |
| 5.15.12 | 26       | 0.65%   |
| 5.7.10  | 25       | 0.63%   |
| 5.17.12 | 25       | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8     | 307      | 8.13%   |
| 5.11    | 256      | 6.78%   |
| 5.19    | 253      | 6.7%    |
| 5.18    | 248      | 6.57%   |
| 5.17    | 244      | 6.46%   |
| 5.16    | 223      | 5.9%    |
| 5.9     | 209      | 5.53%   |
| 5.10    | 206      | 5.45%   |
| 5.14    | 201      | 5.32%   |
| 5.6     | 195      | 5.16%   |
| 5.13    | 191      | 5.06%   |
| 5.15    | 177      | 4.69%   |
| 5.12    | 176      | 4.66%   |
| 5.7     | 171      | 4.53%   |
| 6.0     | 140      | 3.71%   |
| 5.4     | 135      | 3.57%   |
| 5.5     | 121      | 3.2%    |
| 5.3     | 115      | 3.04%   |
| 5.2     | 55       | 1.46%   |
| 5.0     | 47       | 1.24%   |
| 5.1     | 25       | 0.66%   |
| 4.19    | 22       | 0.58%   |
| 4.18    | 19       | 0.5%    |
| 4.20    | 18       | 0.48%   |
| 4.16    | 5        | 0.13%   |
| 6.1     | 3        | 0.08%   |
| 4.15    | 3        | 0.08%   |
| 4.17    | 2        | 0.05%   |
| 4.13    | 2        | 0.05%   |
| 4.11    | 2        | 0.05%   |
| 4.14    | 1        | 0.03%   |
| 4.1     | 1        | 0.03%   |
| 3.9     | 1        | 0.03%   |
| 3.17    | 1        | 0.03%   |
| 2.6.35  | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 3011     | 99.87%  |
| i686    | 3        | 0.1%    |
| Unknown | 1        | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| GNOME                        | 2050     | 65.92%  |
| KDE5                         | 367      | 11.8%   |
| Unknown                      | 247      | 7.94%   |
| KDE                          | 115      | 3.7%    |
| XFCE                         | 80       | 2.57%   |
| X-Cinnamon                   | 63       | 2.03%   |
| Cinnamon                     | 57       | 1.83%   |
| MATE                         | 54       | 1.74%   |
| GNOME Classic                | 22       | 0.71%   |
| LXQt                         | 10       | 0.32%   |
| Deepin                       | 10       | 0.32%   |
| LXDE                         | 9        | 0.29%   |
| i3                           | 7        | 0.23%   |
| KDE4                         | 6        | 0.19%   |
| awesome                      | 3        | 0.1%    |
| openbox                      | 2        | 0.06%   |
| DWM                          | 2        | 0.06%   |
| qtile                        | 1        | 0.03%   |
| Pantheon                     | 1        | 0.03%   |
| NsCDE                        | 1        | 0.03%   |
| GNUstep                      | 1        | 0.03%   |
| GNOME Flashback              | 1        | 0.03%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 1518     | 47.96%  |
| X11     | 1405     | 44.39%  |
| Unknown | 127      | 4.01%   |
| Tty     | 110      | 3.48%   |
| Web     | 5        | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1718     | 55.37%  |
| GDM     | 920      | 29.65%  |
| SDDM    | 241      | 7.77%   |
| LightDM | 135      | 4.35%   |
| TDM     | 73       | 2.35%   |
| XDM     | 7        | 0.23%   |
| KDM     | 7        | 0.23%   |
| SLiM    | 1        | 0.03%   |
| LXDM    | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1409     | 45.81%  |
| Unknown | 243      | 7.9%    |
| en_GB   | 221      | 7.18%   |
| pt_BR   | 150      | 4.88%   |
| ru_RU   | 140      | 4.55%   |
| de_DE   | 136      | 4.42%   |
| fr_FR   | 104      | 3.38%   |
| en_AU   | 87       | 2.83%   |
| en_CA   | 84       | 2.73%   |
| it_IT   | 65       | 2.11%   |
| pl_PL   | 47       | 1.53%   |
| es_ES   | 40       | 1.3%    |
| cs_CZ   | 22       | 0.72%   |
| en_IN   | 21       | 0.68%   |
| en_NZ   | 19       | 0.62%   |
| es_MX   | 17       | 0.55%   |
| nl_BE   | 13       | 0.42%   |
| ja_JP   | 13       | 0.42%   |
| es_AR   | 13       | 0.42%   |
| fi_FI   | 11       | 0.36%   |
| es_CO   | 11       | 0.36%   |
| uk_UA   | 10       | 0.33%   |
| nl_NL   | 10       | 0.33%   |
| en_IE   | 10       | 0.33%   |
| tr_TR   | 9        | 0.29%   |
| zh_CN   | 8        | 0.26%   |
| hu_HU   | 8        | 0.26%   |
| fr_CH   | 8        | 0.26%   |
| de_AT   | 8        | 0.26%   |
| C       | 8        | 0.26%   |
| sv_SE   | 7        | 0.23%   |
| ru_UA   | 7        | 0.23%   |
| sk_SK   | 6        | 0.2%    |
| pt_PT   | 6        | 0.2%    |
| es_CL   | 6        | 0.2%    |
| en_DK   | 6        | 0.2%    |
| el_GR   | 5        | 0.16%   |
| nb_NO   | 4        | 0.13%   |
| ko_KR   | 4        | 0.13%   |
| fr_CA   | 4        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 1893     | 61.76%  |
| BIOS | 1172     | 38.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Btrfs               | 1497     | 48.29%  |
| Ext4                | 1299     | 41.9%   |
| Xfs                 | 159      | 5.13%   |
| Unknown             | 132      | 4.26%   |
| Overlay             | 5        | 0.16%   |
| Ext3                | 4        | 0.13%   |
| Zfs                 | 3        | 0.1%    |
| Fuse.fuse-overlayfs | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1683     | 54.22%  |
| GPT     | 1083     | 34.89%  |
| MBR     | 338      | 10.89%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2615     | 84.55%  |
| Yes       | 478      | 15.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2417     | 78.81%  |
| Yes       | 650      | 21.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 881      | 29.23%  |
| Gigabyte Technology | 613      | 20.34%  |
| MSI                 | 445      | 14.76%  |
| ASRock              | 313      | 10.38%  |
| Dell                | 205      | 6.8%    |
| Hewlett-Packard     | 163      | 5.41%   |
| Lenovo              | 85       | 2.82%   |
| Intel               | 48       | 1.59%   |
| Unknown             | 37       | 1.23%   |
| Acer                | 31       | 1.03%   |
| Biostar             | 17       | 0.56%   |
| ECS                 | 15       | 0.5%    |
| Pegatron            | 14       | 0.46%   |
| BESSTAR Tech        | 12       | 0.4%    |
| Fujitsu             | 11       | 0.36%   |
| Foxconn             | 11       | 0.36%   |
| Supermicro          | 10       | 0.33%   |
| Huanan              | 10       | 0.33%   |
| Shuttle             | 7        | 0.23%   |
| Apple               | 7        | 0.23%   |
| Alienware           | 7        | 0.23%   |
| Positivo            | 4        | 0.13%   |
| PCWare              | 4        | 0.13%   |
| Medion              | 4        | 0.13%   |
| EVGA                | 4        | 0.13%   |
| System76            | 3        | 0.1%    |
| Packard Bell        | 3        | 0.1%    |
| eMachines           | 3        | 0.1%    |
| ABIT                | 3        | 0.1%    |
| ZOTAC               | 2        | 0.07%   |
| XFX                 | 2        | 0.07%   |
| OEM                 | 2        | 0.07%   |
| MACHINIST           | 2        | 0.07%   |
| JINGSHA             | 2        | 0.07%   |
| Google              | 2        | 0.07%   |
| Gateway             | 2        | 0.07%   |
| ASRockRack          | 2        | 0.07%   |
| AMI                 | 2        | 0.07%   |
| AMD                 | 2        | 0.07%   |
| X79                 | 1        | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 92       | 3.05%   |
| Unknown                        | 40       | 1.33%   |
| MSI MS-7C37                    | 33       | 1.09%   |
| Gigabyte B450M DS3H            | 23       | 0.76%   |
| MSI MS-7C02                    | 21       | 0.7%    |
| ASUS TUF Gaming X570-PLUS      | 21       | 0.7%    |
| MSI MS-7A38                    | 19       | 0.63%   |
| MSI MS-7B86                    | 16       | 0.53%   |
| ASUS PRIME X370-PRO            | 15       | 0.5%    |
| MSI MS-7C91                    | 14       | 0.46%   |
| ASUS ROG STRIX B550-F GAMING   | 14       | 0.46%   |
| MSI MS-7C84                    | 13       | 0.43%   |
| MSI MS-7B79                    | 13       | 0.43%   |
| Dell OptiPlex 7010             | 13       | 0.43%   |
| MSI MS-7C56                    | 12       | 0.4%    |
| Gigabyte B450 AORUS ELITE      | 12       | 0.4%    |
| Gigabyte A320M-S2H             | 12       | 0.4%    |
| Dell OptiPlex 9020             | 12       | 0.4%    |
| ASUS ROG STRIX X570-F GAMING   | 12       | 0.4%    |
| ASUS ROG STRIX B550-I GAMING   | 12       | 0.4%    |
| ASUS PRIME X470-PRO            | 12       | 0.4%    |
| Gigabyte X570 I AORUS PRO WIFI | 11       | 0.36%   |
| Gigabyte B450 AORUS M          | 11       | 0.36%   |
| Gigabyte 970A-DS3P             | 11       | 0.36%   |
| ASUS TUF Gaming B550M-PLUS     | 11       | 0.36%   |
| ASUS ROG STRIX B450-F GAMING   | 11       | 0.36%   |
| MSI MS-7B89                    | 10       | 0.33%   |
| MSI MS-7A34                    | 10       | 0.33%   |
| Gigabyte X570 AORUS ELITE      | 10       | 0.33%   |
| ASUS Z170-A                    | 10       | 0.33%   |
| ASUS ROG STRIX X570-E GAMING   | 10       | 0.33%   |
| ASUS ROG CROSSHAIR VII HERO    | 10       | 0.33%   |
| ASUS PRIME B350-PLUS           | 10       | 0.33%   |
| ASRock B450M Pro4              | 10       | 0.33%   |
| Gigabyte X570 AORUS MASTER     | 9        | 0.3%    |
| Dell OptiPlex 3020             | 9        | 0.3%    |
| ASUS TUF Gaming B550-PLUS      | 9        | 0.3%    |
| MSI MS-7C52                    | 8        | 0.27%   |
| MSI MS-7817                    | 8        | 0.27%   |
| MSI MS-7758                    | 8        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 174      | 5.77%   |
| ASUS PRIME             | 171      | 5.67%   |
| Dell OptiPlex          | 104      | 3.45%   |
| ASUS All               | 92       | 3.05%   |
| ASUS TUF               | 90       | 2.99%   |
| Gigabyte X570          | 58       | 1.92%   |
| Lenovo ThinkCentre     | 50       | 1.66%   |
| Gigabyte B450          | 42       | 1.39%   |
| HP Compaq              | 40       | 1.33%   |
| Dell Precision         | 40       | 1.33%   |
| Unknown                | 40       | 1.33%   |
| Gigabyte B450M         | 35       | 1.16%   |
| MSI MS-7C37            | 33       | 1.09%   |
| HP EliteDesk           | 31       | 1.03%   |
| Dell XPS               | 22       | 0.73%   |
| ASRock X570            | 22       | 0.73%   |
| Acer Aspire            | 22       | 0.73%   |
| MSI MS-7C02            | 21       | 0.7%    |
| Dell Inspiron          | 21       | 0.7%    |
| ASRock B450M           | 21       | 0.7%    |
| MSI MS-7A38            | 19       | 0.63%   |
| Gigabyte B550          | 19       | 0.63%   |
| HP ProDesk             | 18       | 0.6%    |
| ASRock B450            | 18       | 0.6%    |
| MSI MS-7B86            | 16       | 0.53%   |
| ASUS P8Z77-V           | 15       | 0.5%    |
| MSI MS-7C91            | 14       | 0.46%   |
| Gigabyte A320M-S2H     | 14       | 0.46%   |
| ASUS M5A97             | 14       | 0.46%   |
| ASUS M5A78L-M          | 14       | 0.46%   |
| MSI MS-7C84            | 13       | 0.43%   |
| MSI MS-7B79            | 13       | 0.43%   |
| Gigabyte Z390          | 13       | 0.43%   |
| ASUS SABERTOOTH        | 13       | 0.43%   |
| ASUS Maximus           | 13       | 0.43%   |
| MSI MS-7C56            | 12       | 0.4%    |
| Gigabyte X470          | 12       | 0.4%    |
| Gigabyte 970A-DS3P     | 12       | 0.4%    |
| ASUS P8Z68-V           | 12       | 0.4%    |
| Gigabyte GA-78LMT-USB3 | 11       | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 428      | 14.2%   |
| 2019    | 366      | 12.14%  |
| 2020    | 304      | 10.09%  |
| 2017    | 272      | 9.02%   |
| 2012    | 242      | 8.03%   |
| 2013    | 212      | 7.03%   |
| 2014    | 203      | 6.74%   |
| 2011    | 158      | 5.24%   |
| 2021    | 155      | 5.14%   |
| 2015    | 149      | 4.94%   |
| 2016    | 146      | 4.84%   |
| 2010    | 105      | 3.48%   |
| 2009    | 103      | 3.42%   |
| 2008    | 80       | 2.65%   |
| 2007    | 36       | 1.19%   |
| 2022    | 32       | 1.06%   |
| 2006    | 17       | 0.56%   |
| 2005    | 4        | 0.13%   |
| Unknown | 2        | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3014     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2856     | 94.07%  |
| Enabled  | 180      | 5.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3012     | 99.93%  |
| Yes  | 2        | 0.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 937      | 30.38%  |
| 32.01-64.0      | 695      | 22.54%  |
| 8.01-16.0       | 543      | 17.61%  |
| 4.01-8.0        | 349      | 11.32%  |
| 64.01-256.0     | 225      | 7.3%    |
| 3.01-4.0        | 203      | 6.58%   |
| 24.01-32.0      | 92       | 2.98%   |
| 1.01-2.0        | 18       | 0.58%   |
| 2.01-3.0        | 16       | 0.52%   |
| Unknown         | 4        | 0.13%   |
| More than 256.0 | 1        | 0.03%   |
| 0.51-1.0        | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 951      | 27.12%  |
| 2.01-3.0    | 890      | 25.39%  |
| 3.01-4.0    | 680      | 19.4%   |
| 1.01-2.0    | 499      | 14.23%  |
| 8.01-16.0   | 318      | 9.07%   |
| 16.01-24.0  | 62       | 1.77%   |
| 0.51-1.0    | 49       | 1.4%    |
| 24.01-32.0  | 25       | 0.71%   |
| 32.01-64.0  | 12       | 0.34%   |
| 0.01-0.5    | 11       | 0.31%   |
| Unknown     | 6        | 0.17%   |
| 64.01-256.0 | 3        | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 972      | 30.44%  |
| 1      | 865      | 27.09%  |
| 3      | 648      | 20.29%  |
| 4      | 345      | 10.8%   |
| 5      | 169      | 5.29%   |
| 6      | 87       | 2.72%   |
| 7      | 47       | 1.47%   |
| 8      | 22       | 0.69%   |
| 9      | 11       | 0.34%   |
| 0      | 10       | 0.31%   |
| 10     | 5        | 0.16%   |
| 11     | 4        | 0.13%   |
| 15     | 2        | 0.06%   |
| 14     | 2        | 0.06%   |
| 12     | 2        | 0.06%   |
| 27     | 1        | 0.03%   |
| 24     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1926     | 62.96%  |
| Yes       | 1133     | 37.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2994     | 99.3%   |
| No        | 21       | 0.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1638     | 53.46%  |
| Yes       | 1426     | 46.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1832     | 59.75%  |
| Yes       | 1234     | 40.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 719      | 23.75%  |
| Germany     | 237      | 7.83%   |
| Brazil      | 218      | 7.2%    |
| Russia      | 193      | 6.37%   |
| Canada      | 125      | 4.13%   |
| UK          | 123      | 4.06%   |
| France      | 122      | 4.03%   |
| Italy       | 111      | 3.67%   |
| Australia   | 97       | 3.2%    |
| Poland      | 86       | 2.84%   |
| Spain       | 72       | 2.38%   |
| Sweden      | 51       | 1.68%   |
| India       | 47       | 1.55%   |
| Netherlands | 44       | 1.45%   |
| Czechia     | 43       | 1.42%   |
| Switzerland | 41       | 1.35%   |
| Ukraine     | 37       | 1.22%   |
| Belgium     | 35       | 1.16%   |
| Finland     | 32       | 1.06%   |
| Mexico      | 30       | 0.99%   |
| Romania     | 29       | 0.96%   |
| Norway      | 29       | 0.96%   |
| Austria     | 28       | 0.92%   |
| Argentina   | 28       | 0.92%   |
| Turkey      | 24       | 0.79%   |
| Greece      | 21       | 0.69%   |
| New Zealand | 20       | 0.66%   |
| Portugal    | 19       | 0.63%   |
| Japan       | 19       | 0.63%   |
| Hungary     | 17       | 0.56%   |
| Indonesia   | 15       | 0.5%    |
| Colombia    | 14       | 0.46%   |
| Chile       | 13       | 0.43%   |
| Philippines | 12       | 0.4%    |
| Denmark     | 12       | 0.4%    |
| Belarus     | 12       | 0.4%    |
| Slovakia    | 11       | 0.36%   |
| China       | 11       | 0.36%   |
| Israel      | 10       | 0.33%   |
| Serbia      | 9        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 51       | 1.57%   |
| Sydney         | 36       | 1.11%   |
| Berlin         | 30       | 0.93%   |
| St Petersburg  | 25       | 0.77%   |
| Warsaw         | 23       | 0.71%   |
| Sao Paulo      | 21       | 0.65%   |
| Vienna         | 19       | 0.59%   |
| Paris          | 17       | 0.52%   |
| Brisbane       | 17       | 0.52%   |
| Toronto        | 16       | 0.49%   |
| Melbourne      | 15       | 0.46%   |
| Auckland       | 15       | 0.46%   |
| Zurich         | 14       | 0.43%   |
| Rome           | 14       | 0.43%   |
| Prague         | 14       | 0.43%   |
| Hamburg        | 14       | 0.43%   |
| Athens         | 14       | 0.43%   |
| Madrid         | 13       | 0.4%    |
| Buenos Aires   | 13       | 0.4%    |
| Rio de Janeiro | 12       | 0.37%   |
| Porto Alegre   | 12       | 0.37%   |
| Munich         | 12       | 0.37%   |
| Helsinki       | 12       | 0.37%   |
| Krakow         | 11       | 0.34%   |
| Amsterdam      | 11       | 0.34%   |
| Vancouver      | 10       | 0.31%   |
| Montreal       | 10       | 0.31%   |
| Milan          | 10       | 0.31%   |
| London         | 10       | 0.31%   |
| Istanbul       | 10       | 0.31%   |
| Cologne        | 10       | 0.31%   |
| Bucharest      | 10       | 0.31%   |
| Belo Horizonte | 10       | 0.31%   |
| Ufa            | 9        | 0.28%   |
| Los Angeles    | 9        | 0.28%   |
| Dallas         | 9        | 0.28%   |
| Charlotte      | 9        | 0.28%   |
| Budapest       | 9        | 0.28%   |
| Yekaterinburg  | 8        | 0.25%   |
| Wroclaw        | 8        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 1145     | 2196   | 18.64%  |
| Samsung Electronics       | 1128     | 2223   | 18.36%  |
| Seagate                   | 1027     | 1896   | 16.72%  |
| Kingston                  | 421      | 636    | 6.85%   |
| Toshiba                   | 318      | 492    | 5.18%   |
| Crucial                   | 316      | 482    | 5.14%   |
| SanDisk                   | 285      | 394    | 4.64%   |
| Hitachi                   | 170      | 277    | 2.77%   |
| Intel                     | 144      | 248    | 2.34%   |
| A-DATA Technology         | 112      | 157    | 1.82%   |
| Phison                    | 106      | 149    | 1.73%   |
| HGST                      | 57       | 111    | 0.93%   |
| Unknown                   | 48       | 75     | 0.78%   |
| Corsair                   | 48       | 71     | 0.78%   |
| SPCC                      | 47       | 74     | 0.76%   |
| Micron/Crucial Technology | 39       | 52     | 0.63%   |
| SK hynix                  | 38       | 44     | 0.62%   |
| China                     | 36       | 46     | 0.59%   |
| OCZ                       | 35       | 46     | 0.57%   |
| Silicon Motion            | 33       | 43     | 0.54%   |
| PNY                       | 32       | 45     | 0.52%   |
| Patriot                   | 32       | 49     | 0.52%   |
| Micron Technology         | 29       | 43     | 0.47%   |
| XPG                       | 23       | 33     | 0.37%   |
| Maxtor                    | 23       | 27     | 0.37%   |
| Transcend                 | 20       | 27     | 0.33%   |
| Plextor                   | 18       | 26     | 0.29%   |
| Intenso                   | 18       | 26     | 0.29%   |
| Team                      | 17       | 27     | 0.28%   |
| Phison Electronics        | 17       | 31     | 0.28%   |
| Hewlett-Packard           | 17       | 21     | 0.28%   |
| Gigabyte Technology       | 17       | 31     | 0.28%   |
| GOODRAM                   | 16       | 22     | 0.26%   |
| ASMT                      | 16       | 18     | 0.26%   |
| SABRENT                   | 12       | 15     | 0.2%    |
| KingSpec                  | 12       | 19     | 0.2%    |
| Apacer                    | 11       | 18     | 0.18%   |
| LITEON                    | 10       | 13     | 0.16%   |
| Realtek Semiconductor     | 9        | 10     | 0.15%   |
| Lexar                     | 9        | 13     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                         | 109      | 1.46%   |
| Samsung SSD 860 EVO 500GB                         | 94       | 1.26%   |
| Samsung NVMe SSD Drive 500GB                      | 91       | 1.22%   |
| Kingston SA400S37240G 240GB SSD                   | 88       | 1.18%   |
| Seagate ST1000DM010-2EP102 1TB                    | 81       | 1.09%   |
| Samsung SSD 850 EVO 500GB                         | 79       | 1.06%   |
| Samsung SSD 860 EVO 1TB                           | 78       | 1.05%   |
| Seagate ST2000DM008-2FR102 2TB                    | 75       | 1.01%   |
| Samsung NVMe SSD Drive 1TB                        | 69       | 0.93%   |
| Seagate ST500DM002-1BD142 500GB                   | 66       | 0.89%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 59       | 0.79%   |
| Toshiba DT01ACA100 1TB                            | 57       | 0.77%   |
| Kingston SA400S37120G 120GB SSD                   | 57       | 0.77%   |
| Kingston SA400S37480G 480GB SSD                   | 52       | 0.7%    |
| Crucial CT500MX500SSD1 500GB                      | 48       | 0.64%   |
| Crucial CT1000MX500SSD1 1TB                       | 41       | 0.55%   |
| Samsung SSD 970 EVO Plus 500GB                    | 40       | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB                    | 38       | 0.51%   |
| SanDisk NVMe SSD Drive 500GB                      | 38       | 0.51%   |
| SanDisk NVMe SSD Drive 1TB                        | 37       | 0.5%    |
| Kingston SV300S37A120G 120GB SSD                  | 37       | 0.5%    |
| Seagate ST4000DM004-2CV104 4TB                    | 35       | 0.47%   |
| Seagate ST2000DM001-1ER164 2TB                    | 35       | 0.47%   |
| Samsung SSD 860 EVO 250GB                         | 35       | 0.47%   |
| Toshiba HDWD110 1TB                               | 34       | 0.46%   |
| Samsung SSD 860 QVO 1TB                           | 33       | 0.44%   |
| Samsung NVMe SSD Drive 250GB                      | 33       | 0.44%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 32       | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB                    | 32       | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB                      | 32       | 0.43%   |
| Samsung SSD 840 EVO 250GB                         | 32       | 0.43%   |
| Seagate ST3500418AS 500GB                         | 31       | 0.42%   |
| Toshiba DT01ACA200 2TB                            | 30       | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 29       | 0.39%   |
| Crucial CT240BX500SSD1 240GB                      | 29       | 0.39%   |
| WDC WD40EZRZ-00GXCB0 4TB                          | 28       | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 27       | 0.36%   |
| WDC WD30EFRX-68EUZN0 3TB                          | 27       | 0.36%   |
| Seagate ST31000528AS 1TB                          | 27       | 0.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 25       | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 996      | 1832   | 36.75%  |
| WDC                 | 987      | 1867   | 36.42%  |
| Toshiba             | 274      | 413    | 10.11%  |
| Hitachi             | 170      | 277    | 6.27%   |
| Samsung Electronics | 125      | 202    | 4.61%   |
| HGST                | 57       | 111    | 2.1%    |
| Maxtor              | 22       | 25     | 0.81%   |
| Unknown             | 15       | 20     | 0.55%   |
| ASMT                | 13       | 14     | 0.48%   |
| Fujitsu             | 9        | 11     | 0.33%   |
| Hewlett-Packard     | 5        | 6      | 0.18%   |
| Apple               | 4        | 4      | 0.15%   |
| MaxDigital          | 3        | 3      | 0.11%   |
| JMicron Technology  | 3        | 7      | 0.11%   |
| Intenso             | 3        | 6      | 0.11%   |
| Inateck             | 3        | 8      | 0.11%   |
| USB                 | 2        | 2      | 0.07%   |
| LaCie               | 2        | 4      | 0.07%   |
| ASMT109x            | 2        | 2      | 0.07%   |
| USB3.0              | 1        | 1      | 0.04%   |
| USB 3.0             | 1        | 3      | 0.04%   |
| Unknown (583)       | 1        | 1      | 0.04%   |
| Synology            | 1        | 1      | 0.04%   |
| SAGE                | 1        | 1      | 0.04%   |
| RSH-339             | 1        | 1      | 0.04%   |
| PHD 3.0             | 1        | 1      | 0.04%   |
| MARVELL             | 1        | 1      | 0.04%   |
| Magnetic Data       | 1        | 1      | 0.04%   |
| KESU                | 1        | 1      | 0.04%   |
| H/W                 | 1        | 1      | 0.04%   |
| External            | 1        | 1      | 0.04%   |
| ExcelStor           | 1        | 1      | 0.04%   |
| ASMT106x            | 1        | 2      | 0.04%   |
| Unknown             | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 692      | 1235   | 29.16%  |
| Kingston            | 353      | 537    | 14.88%  |
| Crucial             | 284      | 438    | 11.97%  |
| SanDisk             | 176      | 228    | 7.42%   |
| WDC                 | 161      | 233    | 6.78%   |
| A-DATA Technology   | 92       | 129    | 3.88%   |
| Intel               | 67       | 126    | 2.82%   |
| SPCC                | 38       | 57     | 1.6%    |
| China               | 36       | 46     | 1.52%   |
| OCZ                 | 35       | 46     | 1.47%   |
| PNY                 | 32       | 44     | 1.35%   |
| Patriot             | 29       | 45     | 1.22%   |
| Toshiba             | 28       | 37     | 1.18%   |
| Corsair             | 26       | 39     | 1.1%    |
| Micron Technology   | 24       | 35     | 1.01%   |
| Transcend           | 20       | 27     | 0.84%   |
| SK hynix            | 17       | 18     | 0.72%   |
| Team                | 16       | 26     | 0.67%   |
| Plextor             | 16       | 23     | 0.67%   |
| GOODRAM             | 16       | 22     | 0.67%   |
| Seagate             | 13       | 16     | 0.55%   |
| KingSpec            | 12       | 19     | 0.51%   |
| Intenso             | 12       | 17     | 0.51%   |
| Gigabyte Technology | 11       | 19     | 0.46%   |
| LITEON              | 10       | 13     | 0.42%   |
| Apacer              | 10       | 17     | 0.42%   |
| KingDian            | 9        | 10     | 0.38%   |
| Unknown             | 8        | 8      | 0.34%   |
| Hewlett-Packard     | 8        | 9      | 0.34%   |
| Verbatim            | 7        | 9      | 0.29%   |
| Mushkin             | 7        | 10     | 0.29%   |
| LITEONIT            | 7        | 8      | 0.29%   |
| Lexar               | 7        | 10     | 0.29%   |
| Leven               | 7        | 8      | 0.29%   |
| JMicron Technology  | 4        | 4      | 0.17%   |
| Drevo               | 4        | 4      | 0.17%   |
| Radeon              | 3        | 4      | 0.13%   |
| OWC                 | 3        | 5      | 0.13%   |
| KingFast            | 3        | 3      | 0.13%   |
| Smartbuy            | 2        | 2      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2048     | 4832   | 39.89%  |
| SSD     | 1904     | 3673   | 37.09%  |
| NVMe    | 1094     | 1888   | 21.31%  |
| Unknown | 80       | 122    | 1.56%   |
| MMC     | 8        | 9      | 0.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2718     | 8253   | 67.04%  |
| NVMe | 1088     | 1871   | 26.84%  |
| SAS  | 240      | 391    | 5.92%   |
| MMC  | 8        | 9      | 0.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2017     | 4142   | 45.27%  |
| 0.51-1.0   | 1344     | 2348   | 30.17%  |
| 1.01-2.0   | 535      | 889    | 12.01%  |
| 3.01-4.0   | 225      | 425    | 5.05%   |
| 2.01-3.0   | 156      | 302    | 3.5%    |
| 4.01-10.0  | 148      | 352    | 3.32%   |
| 10.01-20.0 | 30       | 47     | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 592      | 18.25%  |
| 1001-2000      | 575      | 17.73%  |
| 251-500        | 502      | 15.48%  |
| More than 3000 | 488      | 15.05%  |
| 101-250        | 436      | 13.44%  |
| 2001-3000      | 272      | 8.39%   |
| 1-20           | 149      | 4.59%   |
| Unknown        | 115      | 3.55%   |
| 51-100         | 82       | 2.53%   |
| 21-50          | 32       | 0.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 591      | 17.36%  |
| 101-250        | 466      | 13.69%  |
| 21-50          | 437      | 12.83%  |
| 251-500        | 427      | 12.54%  |
| 501-1000       | 413      | 12.13%  |
| 51-100         | 372      | 10.93%  |
| 1001-2000      | 305      | 8.96%   |
| More than 3000 | 160      | 4.7%    |
| 2001-3000      | 118      | 3.47%   |
| Unknown        | 115      | 3.38%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 14       | 39     | 3.17%   |
| Seagate ST3500418AS 500GB           | 7        | 12     | 1.59%   |
| Seagate ST31000528AS 1TB            | 6        | 8      | 1.36%   |
| Seagate ST1000DM010-2EP102 1TB      | 5        | 5      | 1.13%   |
| Samsung Electronics SSD 870 EVO 1TB | 5        | 5      | 1.13%   |
| Intel SSDSC2CT120A3 120GB           | 5        | 21     | 1.13%   |
| WDC WD10EZEX-00BN5A0 1TB            | 4        | 4      | 0.91%   |
| Toshiba MQ01ABD050 500GB            | 4        | 5      | 0.91%   |
| Seagate ST31500341AS 1TB            | 4        | 4      | 0.91%   |
| Seagate ST31000524AS 1TB            | 4        | 4      | 0.91%   |
| Samsung Electronics HD501LJ 500GB   | 4        | 27     | 0.91%   |
| Samsung Electronics HD322HJ 320GB   | 4        | 4      | 0.91%   |
| Crucial CT128MX100SSD1 128GB        | 4        | 6      | 0.91%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3        | 3      | 0.68%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 3        | 3      | 0.68%   |
| Toshiba DT01ACA100 1TB              | 3        | 3      | 0.68%   |
| Seagate ST500LT012-1DG142 500GB     | 3        | 3      | 0.68%   |
| Seagate ST2000DM001-1CH164 2TB      | 3        | 3      | 0.68%   |
| Kingston SV300S37A120G 120GB SSD    | 3        | 3      | 0.68%   |
| Hitachi HDS721010DLE630 1TB         | 3        | 5      | 0.68%   |
| Hitachi HDS721010CLA332 1TB         | 3        | 3      | 0.68%   |
| Hitachi HDP725050GLA360 500GB       | 3        | 3      | 0.68%   |
| Crucial CT275MX300SSD1 275GB        | 3        | 3      | 0.68%   |
| Crucial CT240M500SSD1 240GB         | 3        | 3      | 0.68%   |
| WDC WD5000AAKX-753CA1 500GB         | 2        | 2      | 0.45%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2        | 2      | 0.45%   |
| WDC WD5000AAKX-003CA0 500GB         | 2        | 2      | 0.45%   |
| WDC WD40EFRX-68WT0N0 4TB            | 2        | 2      | 0.45%   |
| WDC WD30EZRX-00D8PB0 3TB            | 2        | 2      | 0.45%   |
| WDC WD20EZRX-00D8PB0 2TB            | 2        | 3      | 0.45%   |
| WDC WD20EFRX-68AX9N0 2TB            | 2        | 6      | 0.45%   |
| WDC WD1600AVVS-63L2B0 160GB         | 2        | 5      | 0.45%   |
| WDC WD1600AABS-00H4A0 160GB         | 2        | 2      | 0.45%   |
| WDC WD10EZRX-00A8LB0 1TB            | 2        | 2      | 0.45%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 2        | 2      | 0.45%   |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 2      | 0.45%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2        | 2      | 0.45%   |
| WDC WD10EZEX-00MFCA0 1TB            | 2        | 2      | 0.45%   |
| WDC WD10EARS-22Y5B1 1TB             | 2        | 2      | 0.45%   |
| WDC WD1003FBYX-01Y7B1 1TB           | 2        | 5      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 112      | 176    | 26.86%  |
| WDC                 | 104      | 154    | 24.94%  |
| Samsung Electronics | 38       | 65     | 9.11%   |
| Hitachi             | 34       | 47     | 8.15%   |
| Toshiba             | 27       | 32     | 6.47%   |
| Intel               | 18       | 36     | 4.32%   |
| Crucial             | 15       | 17     | 3.6%    |
| SanDisk             | 12       | 12     | 2.88%   |
| Kingston            | 9        | 10     | 2.16%   |
| A-DATA Technology   | 7        | 7      | 1.68%   |
| Maxtor              | 6        | 6      | 1.44%   |
| Corsair             | 5        | 8      | 1.2%    |
| OCZ                 | 4        | 5      | 0.96%   |
| LITEON              | 3        | 3      | 0.72%   |
| HGST                | 3        | 5      | 0.72%   |
| SPCC                | 2        | 3      | 0.48%   |
| SK hynix            | 2        | 2      | 0.48%   |
| OCZ-VERTEX3         | 2        | 2      | 0.48%   |
| Fujitsu             | 2        | 2      | 0.48%   |
| Verbatim            | 1        | 1      | 0.24%   |
| Unknown             | 1        | 1      | 0.24%   |
| Team                | 1        | 4      | 0.24%   |
| PNY                 | 1        | 1      | 0.24%   |
| ORICO               | 1        | 1      | 0.24%   |
| Micron Technology   | 1        | 1      | 0.24%   |
| KingDian            | 1        | 1      | 0.24%   |
| Hewlett-Packard     | 1        | 1      | 0.24%   |
| BIWIN               | 1        | 1      | 0.24%   |
| ASMT                | 1        | 1      | 0.24%   |
| ASMedia             | 1        | 1      | 0.24%   |
| Apacer              | 1        | 1      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 112      | 176    | 36.01%  |
| WDC                 | 103      | 153    | 33.12%  |
| Hitachi             | 34       | 47     | 10.93%  |
| Toshiba             | 27       | 32     | 8.68%   |
| Samsung Electronics | 22       | 49     | 7.07%   |
| Maxtor              | 6        | 6      | 1.93%   |
| HGST                | 3        | 5      | 0.96%   |
| Fujitsu             | 2        | 2      | 0.64%   |
| Hewlett-Packard     | 1        | 1      | 0.32%   |
| ASMT                | 1        | 1      | 0.32%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 283      | 472    | 72.94%  |
| SSD  | 95       | 125    | 24.48%  |
| NVMe | 10       | 10     | 2.58%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000BEVT-00ZAT0 500GB       | 1        | 2      | 16.67%  |
| Toshiba HDWD130 3TB               | 1        | 1      | 16.67%  |
| Seagate ST3320613AS 320GB         | 1        | 1      | 16.67%  |
| Samsung Electronics SSD 980 500GB | 1        | 2      | 16.67%  |
| Samsung Electronics HD321HJ 320GB | 1        | 2      | 16.67%  |
| Hitachi HDS721010DLE630 1TB       | 1        | 6      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 4      | 33.33%  |
| WDC                 | 1        | 2      | 16.67%  |
| Toshiba             | 1        | 1      | 16.67%  |
| Seagate             | 1        | 1      | 16.67%  |
| Hitachi             | 1        | 6      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1758     | 5869   | 50.14%  |
| Works    | 1365     | 4034   | 38.93%  |
| Malfunc  | 378      | 607    | 10.78%  |
| Failed   | 5        | 14     | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 1700     | 36.54%  |
| AMD                            | 1285     | 27.62%  |
| Samsung Electronics            | 499      | 10.73%  |
| ASMedia Technology             | 206      | 4.43%   |
| SanDisk                        | 175      | 3.76%   |
| Phison Electronics             | 151      | 3.25%   |
| Marvell Technology Group       | 97       | 2.09%   |
| Kingston Technology Company    | 79       | 1.7%    |
| JMicron Technology             | 76       | 1.63%   |
| Micron/Crucial Technology      | 70       | 1.5%    |
| Nvidia                         | 49       | 1.05%   |
| Silicon Motion                 | 40       | 0.86%   |
| ADATA Technology               | 40       | 0.86%   |
| Toshiba America Info Systems   | 24       | 0.52%   |
| SK hynix                       | 21       | 0.45%   |
| LSI Logic / Symbios Logic      | 19       | 0.41%   |
| Realtek Semiconductor          | 17       | 0.37%   |
| Broadcom / LSI                 | 16       | 0.34%   |
| Seagate Technology             | 14       | 0.3%    |
| Silicon Image                  | 11       | 0.24%   |
| VIA Technologies               | 8        | 0.17%   |
| MAXIO Technology (Hangzhou)    | 8        | 0.17%   |
| Lite-On Technology             | 8        | 0.17%   |
| Micron Technology              | 7        | 0.15%   |
| KIOXIA                         | 6        | 0.13%   |
| Adaptec                        | 5        | 0.11%   |
| Integrated Technology Express  | 4        | 0.09%   |
| ULi Electronics                | 2        | 0.04%   |
| Solid State Storage Technology | 2        | 0.04%   |
| Lite-On IT Corp. / Plextor     | 2        | 0.04%   |
| INNOGRIT                       | 2        | 0.04%   |
| HighPoint Technologies         | 2        | 0.04%   |
| Hewlett-Packard                | 2        | 0.04%   |
| 3ware                          | 2        | 0.04%   |
| Union Memory (Shenzhen)        | 1        | 0.02%   |
| Solidigm                       | 1        | 0.02%   |
| Netac Technology               | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 847      | 14.74%  |
| AMD 400 Series Chipset SATA Controller                                                  | 330      | 5.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 316      | 5.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 205      | 3.57%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 198      | 3.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 180      | 3.13%   |
| AMD 500 Series Chipset SATA Controller                                                  | 170      | 2.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 169      | 2.94%   |
| Intel SATA Controller [RAID mode]                                                       | 130      | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 127      | 2.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 122      | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 118      | 2.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 117      | 2.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 115      | 2%      |
| Phison E12 NVMe Controller                                                              | 90       | 1.57%   |
| AMD 300 Series Chipset SATA Controller                                                  | 90       | 1.57%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 85       | 1.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 82       | 1.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 74       | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 74       | 1.29%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 57       | 0.99%   |
| AMD FCH SATA Controller D                                                               | 53       | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 51       | 0.89%   |
| AMD X370 Series Chipset SATA Controller                                                 | 50       | 0.87%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 46       | 0.8%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 44       | 0.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 43       | 0.75%   |
| Intel SSD 660P Series                                                                   | 41       | 0.71%   |
| Samsung NVMe SSD Controller 980                                                         | 40       | 0.7%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 36       | 0.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 36       | 0.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 36       | 0.63%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 36       | 0.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 34       | 0.59%   |
| Kingston Company A2000 NVMe SSD                                                         | 34       | 0.59%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 34       | 0.59%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 34       | 0.59%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 32       | 0.56%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 32       | 0.56%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 29       | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2623     | 58.75%  |
| NVMe | 1092     | 24.46%  |
| IDE  | 484      | 10.84%  |
| RAID | 224      | 5.02%   |
| SAS  | 32       | 0.72%   |
| SCSI | 10       | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1684     | 55.87%  |
| AMD    | 1330     | 44.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 105      | 3.46%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 85       | 2.8%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 64       | 2.11%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 56       | 1.85%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 50       | 1.65%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 45       | 1.48%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 44       | 1.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 43       | 1.42%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 39       | 1.29%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 38       | 1.25%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 37       | 1.22%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 36       | 1.19%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 33       | 1.09%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 32       | 1.06%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 32       | 1.06%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 31       | 1.02%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 31       | 1.02%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 30       | 0.99%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 29       | 0.96%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 29       | 0.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 29       | 0.96%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 29       | 0.96%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 29       | 0.96%   |
| AMD FX-6300 Six-Core Processor              | 28       | 0.92%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 27       | 0.89%   |
| AMD FX-8350 Eight-Core Processor            | 27       | 0.89%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 26       | 0.86%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 25       | 0.82%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 23       | 0.76%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 23       | 0.76%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 23       | 0.76%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 23       | 0.76%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 22       | 0.73%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 22       | 0.73%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 21       | 0.69%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 21       | 0.69%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 21       | 0.69%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 20       | 0.66%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 20       | 0.66%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 20       | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 527      | 17.44%  |
| Intel Core i7           | 490      | 16.21%  |
| AMD Ryzen 5             | 414      | 13.7%   |
| AMD Ryzen 7             | 302      | 9.99%   |
| AMD Ryzen 9             | 169      | 5.59%   |
| Intel Core i3           | 160      | 5.29%   |
| Intel Xeon              | 159      | 5.26%   |
| AMD FX                  | 120      | 3.97%   |
| Other                   | 71       | 2.35%   |
| Intel Core 2 Duo        | 67       | 2.22%   |
| AMD Ryzen 3             | 51       | 1.69%   |
| Intel Core 2 Quad       | 43       | 1.42%   |
| Intel Core i9           | 41       | 1.36%   |
| AMD Ryzen Threadripper  | 39       | 1.29%   |
| Intel Pentium           | 38       | 1.26%   |
| Intel Celeron           | 35       | 1.16%   |
| AMD Phenom II X4        | 28       | 0.93%   |
| AMD A10                 | 24       | 0.79%   |
| AMD A8                  | 23       | 0.76%   |
| Intel Pentium Dual-Core | 20       | 0.66%   |
| AMD Athlon II X2        | 18       | 0.6%    |
| AMD A6                  | 18       | 0.6%    |
| AMD Phenom II X6        | 15       | 0.5%    |
| AMD Athlon              | 15       | 0.5%    |
| Intel Core 2            | 13       | 0.43%   |
| AMD Phenom              | 12       | 0.4%    |
| AMD Athlon 64 X2        | 12       | 0.4%    |
| Intel Atom              | 10       | 0.33%   |
| AMD Ryzen 7 PRO         | 9        | 0.3%    |
| AMD Athlon X4           | 8        | 0.26%   |
| AMD A4                  | 8        | 0.26%   |
| AMD Ryzen 5 PRO         | 6        | 0.2%    |
| AMD Phenom II X2        | 6        | 0.2%    |
| AMD Athlon II X4        | 6        | 0.2%    |
| Intel Pentium Dual      | 4        | 0.13%   |
| AMD Athlon Dual Core    | 4        | 0.13%   |
| Intel Pentium Gold      | 3        | 0.1%    |
| Intel Pentium D         | 3        | 0.1%    |
| Intel Genuine           | 3        | 0.1%    |
| AMD Athlon 64           | 3        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1164     | 38.49%  |
| 6      | 604      | 19.97%  |
| 2      | 465      | 15.38%  |
| 8      | 422      | 13.96%  |
| 12     | 156      | 5.16%   |
| 16     | 84       | 2.78%   |
| 3      | 46       | 1.52%   |
| 10     | 29       | 0.96%   |
| 1      | 28       | 0.93%   |
| 32     | 10       | 0.33%   |
| 24     | 10       | 0.33%   |
| 14     | 4        | 0.13%   |
| 20     | 1        | 0.03%   |
| 18     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2978     | 98.81%  |
| 2      | 36       | 1.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2037     | 67.43%  |
| 1      | 984      | 32.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2925     | 96.53%  |
| Unknown        | 105      | 3.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 294      | 9.51%   |
| 0x08701021 | 231      | 7.47%   |
| Unknown    | 179      | 5.79%   |
| 0x306a9    | 159      | 5.14%   |
| 0x506e3    | 156      | 5.05%   |
| 0x0800820d | 136      | 4.4%    |
| 0x206a7    | 126      | 4.08%   |
| 0x906ea    | 117      | 3.79%   |
| 0x906e9    | 113      | 3.66%   |
| 0x08701013 | 107      | 3.46%   |
| 0x1067a    | 81       | 2.62%   |
| 0x06000852 | 73       | 2.36%   |
| 0x0a201016 | 64       | 2.07%   |
| 0x0a201009 | 60       | 1.94%   |
| 0x08001138 | 53       | 1.71%   |
| 0x906ed    | 49       | 1.59%   |
| 0x08108109 | 46       | 1.49%   |
| 0x08001137 | 46       | 1.49%   |
| 0x010000c8 | 39       | 1.26%   |
| 0x306f2    | 38       | 1.23%   |
| 0xa0655    | 35       | 1.13%   |
| 0x0a50000c | 35       | 1.13%   |
| 0x08101016 | 35       | 1.13%   |
| 0x90672    | 34       | 1.1%    |
| 0xa0653    | 32       | 1.04%   |
| 0x06001119 | 30       | 0.97%   |
| 0x20655    | 27       | 0.87%   |
| 0x106a5    | 26       | 0.84%   |
| 0x6fb      | 25       | 0.81%   |
| 0x206d7    | 25       | 0.81%   |
| 0x10676    | 25       | 0.81%   |
| 0x106e5    | 23       | 0.74%   |
| 0x906eb    | 22       | 0.71%   |
| 0xa0671    | 21       | 0.68%   |
| 0x906ec    | 21       | 0.68%   |
| 0x0800820b | 20       | 0.65%   |
| 0x06003106 | 19       | 0.61%   |
| 0x0810100b | 18       | 0.58%   |
| 0x206c2    | 17       | 0.55%   |
| 0x06000822 | 15       | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 378      | 12.5%   |
| Haswell          | 350      | 11.57%  |
| KabyLake         | 345      | 11.41%  |
| Zen+             | 228      | 7.54%   |
| Zen 3            | 215      | 7.11%   |
| IvyBridge        | 185      | 6.12%   |
| Zen              | 184      | 6.08%   |
| Skylake          | 181      | 5.99%   |
| SandyBridge      | 163      | 5.39%   |
| Piledriver       | 132      | 4.37%   |
| Penryn           | 120      | 3.97%   |
| K10              | 91       | 3.01%   |
| CometLake        | 69       | 2.28%   |
| Nehalem          | 55       | 1.82%   |
| Westmere         | 52       | 1.72%   |
| Core             | 51       | 1.69%   |
| Alderlake Hybrid | 41       | 1.36%   |
| Steamroller      | 26       | 0.86%   |
| Icelake          | 21       | 0.69%   |
| Excavator        | 20       | 0.66%   |
| K8 Hammer        | 19       | 0.63%   |
| Bulldozer        | 19       | 0.63%   |
| Silvermont       | 14       | 0.46%   |
| Broadwell        | 12       | 0.4%    |
| Unknown          | 11       | 0.36%   |
| NetBurst         | 7        | 0.23%   |
| Bonnell          | 7        | 0.23%   |
| K10 Llano        | 6        | 0.2%    |
| Jaguar           | 6        | 0.2%    |
| Bobcat           | 5        | 0.17%   |
| Puma             | 3        | 0.1%    |
| Goldmont plus    | 3        | 0.1%    |
| Goldmont         | 3        | 0.1%    |
| Tremont          | 1        | 0.03%   |
| TigerLake        | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1319     | 40.14%  |
| AMD                        | 1213     | 36.91%  |
| Intel                      | 739      | 22.49%  |
| Matrox Electronics Systems | 7        | 0.21%   |
| ASPEED Technology          | 7        | 0.21%   |
| S3 Graphics                | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 258      | 7.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 135      | 3.99%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 112      | 3.31%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 88       | 2.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 84       | 2.48%   |
| Intel HD Graphics 530                                                       | 82       | 2.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 81       | 2.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 71       | 2.1%    |
| Intel HD Graphics 630                                                       | 61       | 1.8%    |
| Nvidia GK208B [GeForce GT 710]                                              | 55       | 1.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 55       | 1.63%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 48       | 1.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 47       | 1.39%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 46       | 1.36%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 45       | 1.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 45       | 1.33%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 44       | 1.3%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 42       | 1.24%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 41       | 1.21%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 39       | 1.15%   |
| Nvidia GT218 [GeForce 210]                                                  | 37       | 1.09%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 37       | 1.09%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 36       | 1.06%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 36       | 1.06%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 35       | 1.03%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 33       | 0.98%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 32       | 0.95%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 32       | 0.95%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 32       | 0.95%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 32       | 0.95%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 32       | 0.95%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 30       | 0.89%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 28       | 0.83%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 28       | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 26       | 0.77%   |
| Nvidia GK208B [GeForce GT 730]                                              | 25       | 0.74%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 24       | 0.71%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 24       | 0.71%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 24       | 0.71%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 22       | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1199     | 39.13%  |
| 1 x AMD                  | 1123     | 36.65%  |
| 1 x Intel                | 551      | 17.98%  |
| Intel + Nvidia           | 64       | 2.09%   |
| 2 x AMD                  | 36       | 1.17%   |
| AMD + Nvidia             | 31       | 1.01%   |
| Intel + AMD              | 21       | 0.69%   |
| 2 x Nvidia               | 19       | 0.62%   |
| 1 x ASPEED               | 5        | 0.16%   |
| 1 x Matrox               | 4        | 0.13%   |
| Nvidia + Matrox          | 2        | 0.07%   |
| Other                    | 1        | 0.03%   |
| 2 x Nvidia + 1 x ASPEED  | 1        | 0.03%   |
| 1 x S3 Graphics          | 1        | 0.03%   |
| Nvidia + ASPEED          | 1        | 0.03%   |
| Intel + 2 x Nvidia       | 1        | 0.03%   |
| Intel + 2 x AMD          | 1        | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.03%   |
| AMD + 2 x Nvidia         | 1        | 0.03%   |
| AMD + Matrox             | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2246     | 73.02%  |
| Proprietary | 747      | 24.28%  |
| Unknown     | 83       | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1059     | 33.72%  |
| 7.01-8.0   | 465      | 14.8%   |
| 1.01-2.0   | 429      | 13.66%  |
| 3.01-4.0   | 344      | 10.95%  |
| 0.51-1.0   | 309      | 9.84%   |
| 0.01-0.5   | 217      | 6.91%   |
| 5.01-6.0   | 147      | 4.68%   |
| 8.01-16.0  | 125      | 3.98%   |
| 2.01-3.0   | 43       | 1.37%   |
| 16.01-24.0 | 3        | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 529      | 14.84%  |
| Goldstar             | 473      | 13.27%  |
| Dell                 | 473      | 13.27%  |
| Acer                 | 259      | 7.27%   |
| AOC                  | 211      | 5.92%   |
| BenQ                 | 207      | 5.81%   |
| Hewlett-Packard      | 201      | 5.64%   |
| Ancor Communications | 186      | 5.22%   |
| Philips              | 146      | 4.1%    |
| ViewSonic            | 99       | 2.78%   |
| Iiyama               | 81       | 2.27%   |
| Lenovo               | 68       | 1.91%   |
| ASUSTek Computer     | 67       | 1.88%   |
| Sony                 | 34       | 0.95%   |
| Eizo                 | 34       | 0.95%   |
| MSI                  | 31       | 0.87%   |
| Sceptre Tech         | 30       | 0.84%   |
| Unknown              | 27       | 0.76%   |
| HannStar             | 27       | 0.76%   |
| NEC Computers        | 22       | 0.62%   |
| Gigabyte Technology  | 19       | 0.53%   |
| Vizio                | 16       | 0.45%   |
| Insignia             | 15       | 0.42%   |
| LG Electronics       | 13       | 0.36%   |
| ___                  | 11       | 0.31%   |
| Panasonic            | 11       | 0.31%   |
| Mi                   | 10       | 0.28%   |
| Fujitsu Siemens      | 10       | 0.28%   |
| Gateway              | 9        | 0.25%   |
| Pixio                | 8        | 0.22%   |
| Vestel Elektronik    | 6        | 0.17%   |
| RTK                  | 6        | 0.17%   |
| ONN                  | 6        | 0.17%   |
| Apple                | 6        | 0.17%   |
| Unknown (XXX)        | 5        | 0.14%   |
| Toshiba              | 5        | 0.14%   |
| Sharp                | 5        | 0.14%   |
| Planar               | 5        | 0.14%   |
| Packard Bell         | 5        | 0.14%   |
| Mitsubishi           | 5        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 29       | 0.74%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 24       | 0.62%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 23       | 0.59%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 21       | 0.54%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 19       | 0.49%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 16       | 0.41%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 16       | 0.41%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 16       | 0.41%   |
| AOC Q27G2G4 AOC2702 2560x1440 597x336mm 27.0-inch                     | 16       | 0.41%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 14       | 0.36%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 14       | 0.36%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                       | 13       | 0.33%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch      | 13       | 0.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 12       | 0.31%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch           | 12       | 0.31%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 12       | 0.31%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 11       | 0.28%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch   | 11       | 0.28%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 11       | 0.28%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 11       | 0.28%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 11       | 0.28%   |
| Samsung Electronics C49RG9x SAM0F9C 2560x1440 1193x336mm 48.8-inch    | 9        | 0.23%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                      | 9        | 0.23%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 9        | 0.23%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 9        | 0.23%   |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                     | 9        | 0.23%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 8        | 0.21%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 8        | 0.21%   |
| MSI PRO 22X 10M MSI1462 1920x1080 595x336mm 26.9-inch                 | 8        | 0.21%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 8        | 0.21%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 8        | 0.21%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 8        | 0.21%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 8        | 0.21%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                       | 8        | 0.21%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 8        | 0.21%   |
| ___ LCDTV16 ___0101 1360x768                                          | 7        | 0.18%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch             | 7        | 0.18%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 480x270mm 21.7-inch | 7        | 0.18%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 7        | 0.18%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch              | 7        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1564     | 45.69%  |
| 2560x1440 (QHD)    | 406      | 11.86%  |
| 3840x2160 (4K)     | 382      | 11.16%  |
| 1280x1024 (SXGA)   | 146      | 4.27%   |
| 1680x1050 (WSXGA+) | 141      | 4.12%   |
| 1920x1200 (WUXGA)  | 129      | 3.77%   |
| 3440x1440          | 96       | 2.8%    |
| 1366x768 (WXGA)    | 96       | 2.8%    |
| 1440x900 (WXGA+)   | 94       | 2.75%   |
| 2560x1080          | 80       | 2.34%   |
| 1600x900 (HD+)     | 64       | 1.87%   |
| 1360x768           | 43       | 1.26%   |
| 3840x1080          | 32       | 0.93%   |
| Unknown            | 32       | 0.93%   |
| 1600x1200          | 18       | 0.53%   |
| 1024x768 (XGA)     | 14       | 0.41%   |
| 2560x1600          | 12       | 0.35%   |
| 1920x540           | 12       | 0.35%   |
| 2288x1287          | 10       | 0.29%   |
| 2048x1152          | 6        | 0.18%   |
| 1280x720 (HD)      | 6        | 0.18%   |
| 1280x960           | 5        | 0.15%   |
| 3840x1600          | 4        | 0.12%   |
| 5760x2160          | 2        | 0.06%   |
| 3840x1200          | 2        | 0.06%   |
| 2160x1200          | 2        | 0.06%   |
| 1280x768           | 2        | 0.06%   |
| 7680x2160          | 1        | 0.03%   |
| 7680x1440          | 1        | 0.03%   |
| 7120x1080          | 1        | 0.03%   |
| 6784x2160          | 1        | 0.03%   |
| 6400x2160          | 1        | 0.03%   |
| 6400x1080          | 1        | 0.03%   |
| 5760x1200          | 1        | 0.03%   |
| 5760x1080          | 1        | 0.03%   |
| 5120x1440          | 1        | 0.03%   |
| 4864x2160          | 1        | 0.03%   |
| 4480x1200          | 1        | 0.03%   |
| 4480x1080          | 1        | 0.03%   |
| 4093x4093          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 677      | 18.8%   |
| 24      | 632      | 17.55%  |
| 23      | 451      | 12.52%  |
| 21      | 428      | 11.89%  |
| 31      | 169      | 4.69%   |
| 19      | 167      | 4.64%   |
| 34      | 156      | 4.33%   |
| 22      | 122      | 3.39%   |
| 18      | 120      | 3.33%   |
| Unknown | 103      | 2.86%   |
| 20      | 84       | 2.33%   |
| 17      | 56       | 1.56%   |
| 72      | 49       | 1.36%   |
| 32      | 46       | 1.28%   |
| 84      | 38       | 1.06%   |
| 25      | 38       | 1.06%   |
| 15      | 30       | 0.83%   |
| 54      | 23       | 0.64%   |
| 48      | 21       | 0.58%   |
| 40      | 18       | 0.5%    |
| 26      | 17       | 0.47%   |
| 42      | 16       | 0.44%   |
| 49      | 11       | 0.31%   |
| 29      | 11       | 0.31%   |
| 28      | 11       | 0.31%   |
| 46      | 10       | 0.28%   |
| 16      | 10       | 0.28%   |
| 142     | 8        | 0.22%   |
| 13      | 8        | 0.22%   |
| 65      | 7        | 0.19%   |
| 52      | 7        | 0.19%   |
| 37      | 7        | 0.19%   |
| 30      | 5        | 0.14%   |
| 50      | 4        | 0.11%   |
| 39      | 4        | 0.11%   |
| 35      | 4        | 0.11%   |
| 33      | 4        | 0.11%   |
| 69      | 3        | 0.08%   |
| 47      | 3        | 0.08%   |
| 43      | 3        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1569     | 46.15%  |
| 401-500        | 785      | 23.09%  |
| 601-700        | 267      | 7.85%   |
| 701-800        | 209      | 6.15%   |
| 351-400        | 126      | 3.71%   |
| Unknown        | 103      | 3.03%   |
| 1501-2000      | 92       | 2.71%   |
| 1001-1500      | 88       | 2.59%   |
| 301-350        | 86       | 2.53%   |
| 801-900        | 32       | 0.94%   |
| 901-1000       | 23       | 0.68%   |
| More than 2000 | 10       | 0.29%   |
| 201-300        | 10       | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2269     | 71.42%  |
| 16/10   | 410      | 12.91%  |
| 21/9    | 169      | 5.32%   |
| 5/4     | 146      | 4.6%    |
| Unknown | 72       | 2.27%   |
| 4/3     | 50       | 1.57%   |
| 32/9    | 25       | 0.79%   |
| 6/5     | 12       | 0.38%   |
| 3/2     | 9        | 0.28%   |
| 1.00    | 8        | 0.25%   |
| 1.96    | 4        | 0.13%   |
| 3.20    | 1        | 0.03%   |
| 0.89    | 1        | 0.03%   |
| 0.80    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1220     | 35.12%  |
| 301-350        | 691      | 19.89%  |
| 151-200        | 390      | 11.23%  |
| 351-500        | 385      | 11.08%  |
| 251-300        | 242      | 6.97%   |
| More than 1000 | 148      | 4.26%   |
| 141-150        | 136      | 3.91%   |
| Unknown        | 103      | 2.96%   |
| 501-1000       | 97       | 2.79%   |
| 101-110        | 26       | 0.75%   |
| 131-140        | 11       | 0.32%   |
| 91-100         | 6        | 0.17%   |
| 71-80          | 5        | 0.14%   |
| 121-130        | 5        | 0.14%   |
| 111-120        | 5        | 0.14%   |
| 81-90          | 4        | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1946     | 59.17%  |
| 101-120 | 822      | 24.99%  |
| 121-160 | 176      | 5.35%   |
| 1-50    | 137      | 4.17%   |
| 161-240 | 105      | 3.19%   |
| Unknown | 103      | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2167     | 69.52%  |
| 2     | 731      | 23.45%  |
| 0     | 106      | 3.4%    |
| 3     | 95       | 3.05%   |
| 4     | 14       | 0.45%   |
| 5     | 4        | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1755     | 40.66%  |
| Intel                           | 1501     | 34.78%  |
| Qualcomm Atheros                | 256      | 5.93%   |
| Broadcom                        | 110      | 2.55%   |
| Ralink Technology               | 91       | 2.11%   |
| TP-Link                         | 85       | 1.97%   |
| Microsoft                       | 41       | 0.95%   |
| Nvidia                          | 40       | 0.93%   |
| Aquantia                        | 38       | 0.88%   |
| Ralink                          | 36       | 0.83%   |
| ASUSTek Computer                | 28       | 0.65%   |
| Qualcomm Atheros Communications | 27       | 0.63%   |
| Marvell Technology Group        | 22       | 0.51%   |
| MediaTek                        | 20       | 0.46%   |
| D-Link                          | 19       | 0.44%   |
| Xiaomi                          | 17       | 0.39%   |
| NetGear                         | 17       | 0.39%   |
| Edimax Technology               | 15       | 0.35%   |
| Samsung Electronics             | 14       | 0.32%   |
| ASIX Electronics                | 11       | 0.25%   |
| D-Link System                   | 9        | 0.21%   |
| Broadcom Limited                | 9        | 0.21%   |
| Mellanox Technologies           | 8        | 0.19%   |
| Linksys                         | 8        | 0.19%   |
| Huawei Technologies             | 8        | 0.19%   |
| Google                          | 8        | 0.19%   |
| Arduino SA                      | 8        | 0.19%   |
| Motorola PCS                    | 7        | 0.16%   |
| Belkin Components               | 7        | 0.16%   |
| Apple                           | 7        | 0.16%   |
| DisplayLink                     | 6        | 0.14%   |
| ICS Advent                      | 5        | 0.12%   |
| AVM                             | 5        | 0.12%   |
| Wilocity                        | 4        | 0.09%   |
| Qualcomm                        | 4        | 0.09%   |
| HMD Global                      | 4        | 0.09%   |
| OpenMoko                        | 3        | 0.07%   |
| Microchip Technology            | 3        | 0.07%   |
| InterBiometrics                 | 3        | 0.07%   |
| ADMtek                          | 3        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1398     | 27.79%  |
| Intel I211 Gigabit Network Connection                             | 341      | 6.78%   |
| Intel Wi-Fi 6 AX200                                               | 297      | 5.9%    |
| Intel Ethernet Connection (2) I219-V                              | 184      | 3.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 172      | 3.42%   |
| Intel Ethernet Controller I225-V                                  | 107      | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 94       | 1.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 89       | 1.77%   |
| Intel Ethernet Connection (7) I219-V                              | 74       | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 63       | 1.25%   |
| Intel Ethernet Connection (2) I218-V                              | 58       | 1.15%   |
| Intel Wireless-AC 9260                                            | 57       | 1.13%   |
| Intel 82574L Gigabit Network Connection                           | 43       | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 42       | 0.83%   |
| Intel 82579V Gigabit Network Connection                           | 41       | 0.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 40       | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 39       | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39       | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 39       | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 35       | 0.7%    |
| Ralink MT7601U Wireless Adapter                                   | 35       | 0.7%    |
| Intel Ethernet Connection I217-V                                  | 33       | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 31       | 0.62%   |
| Intel Wireless 7260                                               | 30       | 0.6%    |
| Intel Wireless 8260                                               | 28       | 0.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 28       | 0.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23       | 0.46%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 22       | 0.44%   |
| Qualcomm Atheros AR9271 802.11n                                   | 21       | 0.42%   |
| Intel I210 Gigabit Network Connection                             | 21       | 0.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 21       | 0.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 20       | 0.4%    |
| Ralink RT5370 Wireless Adapter                                    | 20       | 0.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 20       | 0.4%    |
| Intel Wireless 7265                                               | 20       | 0.4%    |
| Intel Wireless 8265 / 8275                                        | 19       | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 18       | 0.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 18       | 0.36%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 18       | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 18       | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 680      | 44.33%  |
| Realtek Semiconductor                 | 247      | 16.1%   |
| Qualcomm Atheros                      | 134      | 8.74%   |
| Ralink Technology                     | 91       | 5.93%   |
| TP-Link                               | 83       | 5.41%   |
| Broadcom                              | 55       | 3.59%   |
| Microsoft                             | 40       | 2.61%   |
| Ralink                                | 36       | 2.35%   |
| Qualcomm Atheros Communications       | 27       | 1.76%   |
| ASUSTek Computer                      | 26       | 1.69%   |
| MediaTek                              | 19       | 1.24%   |
| NetGear                               | 17       | 1.11%   |
| Edimax Technology                     | 15       | 0.98%   |
| D-Link                                | 15       | 0.98%   |
| Linksys                               | 8        | 0.52%   |
| Belkin Components                     | 7        | 0.46%   |
| D-Link System                         | 6        | 0.39%   |
| AVM                                   | 5        | 0.33%   |
| Wilocity                              | 4        | 0.26%   |
| Xiaomi                                | 2        | 0.13%   |
| IMC Networks                          | 2        | 0.13%   |
| BUFFALO                               | 2        | 0.13%   |
| Broadcom Limited                      | 2        | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.13%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.07%   |
| Toshiba                               | 1        | 0.07%   |
| Sitecom Europe                        | 1        | 0.07%   |
| Sierra Wireless                       | 1        | 0.07%   |
| Samsung Electronics                   | 1        | 0.07%   |
| PLANEX                                | 1        | 0.07%   |
| Mercucys                              | 1        | 0.07%   |
| Gemtek                                | 1        | 0.07%   |
| AboCom Systems                        | 1        | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 297      | 19.16%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 89       | 5.74%   |
| Intel Wireless-AC 9260                                         | 57       | 3.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 40       | 2.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 35       | 2.26%   |
| Ralink MT7601U Wireless Adapter                                | 35       | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 31       | 2%      |
| Intel Wireless 7260                                            | 30       | 1.94%   |
| Intel Wireless 8260                                            | 28       | 1.81%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 28       | 1.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23       | 1.48%   |
| Qualcomm Atheros AR9271 802.11n                                | 21       | 1.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 20       | 1.29%   |
| Ralink RT5370 Wireless Adapter                                 | 20       | 1.29%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 20       | 1.29%   |
| Intel Wireless 7265                                            | 20       | 1.29%   |
| Intel Wireless 8265 / 8275                                     | 19       | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 18       | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 18       | 1.16%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 18       | 1.16%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 18       | 1.16%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 17       | 1.1%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 17       | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 17       | 1.1%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 16       | 1.03%   |
| Realtek 802.11ac NIC                                           | 16       | 1.03%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 15       | 0.97%   |
| Microsoft Xbox 360 Wireless Adapter                            | 15       | 0.97%   |
| Intel Wireless 3165                                            | 15       | 0.97%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 14       | 0.9%    |
| Microsoft XBOX ACC                                             | 14       | 0.9%    |
| Intel Wireless 3160                                            | 13       | 0.84%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 13       | 0.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 12       | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11       | 0.71%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 11       | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11       | 0.71%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 11       | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 11       | 0.71%   |
| TP-Link 802.11ac WLAN Adapter                                  | 10       | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1648     | 50.09%  |
| Intel                                  | 1212     | 36.84%  |
| Qualcomm Atheros                       | 138      | 4.19%   |
| Broadcom                               | 55       | 1.67%   |
| Nvidia                                 | 40       | 1.22%   |
| Aquantia                               | 38       | 1.16%   |
| Marvell Technology Group               | 22       | 0.67%   |
| Xiaomi                                 | 15       | 0.46%   |
| Samsung Electronics                    | 13       | 0.4%    |
| ASIX Electronics                       | 11       | 0.33%   |
| Google                                 | 8        | 0.24%   |
| Motorola PCS                           | 7        | 0.21%   |
| Mellanox Technologies                  | 7        | 0.21%   |
| Broadcom Limited                       | 7        | 0.21%   |
| Apple                                  | 7        | 0.21%   |
| DisplayLink                            | 6        | 0.18%   |
| ICS Advent                             | 5        | 0.15%   |
| Qualcomm                               | 4        | 0.12%   |
| Huawei Technologies                    | 4        | 0.12%   |
| HMD Global                             | 4        | 0.12%   |
| D-Link                                 | 4        | 0.12%   |
| D-Link System                          | 3        | 0.09%   |
| ADMtek                                 | 3        | 0.09%   |
| VIA Technologies                       | 2        | 0.06%   |
| TP-Link                                | 2        | 0.06%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.06%   |
| OPPO Electronics                       | 2        | 0.06%   |
| Lenovo                                 | 2        | 0.06%   |
| Davicom Semiconductor                  | 2        | 0.06%   |
| ASUSTek Computer                       | 2        | 0.06%   |
| Accton Technology                      | 2        | 0.06%   |
| 3Com                                   | 2        | 0.06%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.03%   |
| Xilinx                                 | 1        | 0.03%   |
| vivo                                   | 1        | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.03%   |
| QNAP System                            | 1        | 0.03%   |
| OpenMoko                               | 1        | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.03%   |
| NetXen Incorporated                    | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1398     | 40.65%  |
| Intel I211 Gigabit Network Connection                                         | 341      | 9.92%   |
| Intel Ethernet Connection (2) I219-V                                          | 184      | 5.35%   |
| Realtek RTL8125 2.5GbE Controller                                             | 172      | 5%      |
| Intel Ethernet Controller I225-V                                              | 107      | 3.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 94       | 2.73%   |
| Intel Ethernet Connection (7) I219-V                                          | 74       | 2.15%   |
| Intel Ethernet Connection I217-LM                                             | 63       | 1.83%   |
| Intel Ethernet Connection (2) I218-V                                          | 58       | 1.69%   |
| Intel 82574L Gigabit Network Connection                                       | 43       | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                                         | 42       | 1.22%   |
| Intel 82579V Gigabit Network Connection                                       | 41       | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 39       | 1.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 39       | 1.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 39       | 1.13%   |
| Intel Ethernet Connection I217-V                                              | 33       | 0.96%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 22       | 0.64%   |
| Intel I210 Gigabit Network Connection                                         | 21       | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 21       | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 18       | 0.52%   |
| Nvidia MCP61 Ethernet                                                         | 18       | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 17       | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 16       | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 15       | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 14       | 0.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 14       | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                                         | 14       | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 12       | 0.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 11       | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 11       | 0.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 11       | 0.32%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 11       | 0.32%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 11       | 0.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 10       | 0.29%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 10       | 0.29%   |
| Intel Ethernet Connection (2) I218-LM                                         | 9        | 0.26%   |
| Intel 82578DM Gigabit Network Connection                                      | 9        | 0.26%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 9        | 0.26%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 9        | 0.26%   |
| Nvidia MCP55 Ethernet                                                         | 8        | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2992     | 67.12%  |
| WiFi     | 1426     | 31.99%  |
| Modem    | 35       | 0.79%   |
| Unknown  | 5        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2423     | 75.93%  |
| WiFi     | 768      | 24.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1778     | 58.2%   |
| 2     | 1025     | 33.55%  |
| 3     | 190      | 6.22%   |
| 4     | 22       | 0.72%   |
| 0     | 18       | 0.59%   |
| 5     | 13       | 0.43%   |
| 6     | 6        | 0.2%    |
| 9     | 2        | 0.07%   |
| 8     | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 2588     | 83.92%  |
| Yes     | 493      | 15.99%  |
| Unknown | 3        | 0.1%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 635      | 50%     |
| Cambridge Silicon Radio         | 281      | 22.13%  |
| ASUSTek Computer                | 100      | 7.87%   |
| Broadcom                        | 67       | 5.28%   |
| Realtek Semiconductor           | 65       | 5.12%   |
| Qualcomm Atheros Communications | 29       | 2.28%   |
| IMC Networks                    | 14       | 1.1%    |
| TP-Link                         | 13       | 1.02%   |
| Apple                           | 13       | 1.02%   |
| MediaTek                        | 12       | 0.94%   |
| Belkin Components               | 7        | 0.55%   |
| HTC (High Tech Computer)        | 5        | 0.39%   |
| Lite-On Technology              | 4        | 0.31%   |
| Edimax Technology               | 4        | 0.31%   |
| Integrated System Solution      | 3        | 0.24%   |
| Foxconn / Hon Hai               | 3        | 0.24%   |
| Dynex                           | 3        | 0.24%   |
| Dell                            | 3        | 0.24%   |
| Toshiba                         | 2        | 0.16%   |
| Hewlett-Packard                 | 2        | 0.16%   |
| SINO WEALTH                     | 1        | 0.08%   |
| Kensington                      | 1        | 0.08%   |
| D-Link System                   | 1        | 0.08%   |
| Creative Technology             | 1        | 0.08%   |
| BUFFALO                         | 1        | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 281      | 22.07%  |
| Intel AX200 Bluetooth                                                | 279      | 21.92%  |
| Intel Bluetooth wireless interface                                   | 115      | 9.03%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 88       | 6.91%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 54       | 4.24%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 48       | 3.77%   |
| Realtek Bluetooth Radio                                              | 45       | 3.53%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 41       | 3.22%   |
| Intel AX210 Bluetooth                                                | 38       | 2.99%   |
| Intel AX201 Bluetooth                                                | 34       | 2.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 23       | 1.81%   |
| ASUS Bluetooth Radio                                                 | 18       | 1.41%   |
| TP-Link UB500 Adapter                                                | 13       | 1.02%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 12       | 0.94%   |
| MediaTek Wireless_Device                                             | 12       | 0.94%   |
| ASUS Bluetooth Adapter                                               | 12       | 0.94%   |
| ASUS ASUS USB-BT500                                                  | 9        | 0.71%   |
| Qualcomm Atheros  Bluetooth Device                                   | 8        | 0.63%   |
| ASUS BCM20702A0                                                      | 8        | 0.63%   |
| Apple Bluetooth USB Host Controller                                  | 8        | 0.63%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 6        | 0.47%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.47%   |
| Realtek RTL8821A Bluetooth                                           | 5        | 0.39%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 5        | 0.39%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 5        | 0.39%   |
| IMC Networks Bluetooth Radio                                         | 5        | 0.39%   |
| IMC Networks Bluetooth Device                                        | 5        | 0.39%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 5        | 0.39%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 5        | 0.39%   |
| ASUS Bluetooth Device                                                | 5        | 0.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 4        | 0.31%   |
| Lite-On Bluetooth Device                                             | 4        | 0.31%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4        | 0.31%   |
| Broadcom BCM2045 Bluetooth                                           | 4        | 0.31%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 4        | 0.31%   |
| Integrated System Solution Bluetooth Device                          | 3        | 0.24%   |
| Edimax Bluetooth Adapter                                             | 3        | 0.24%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 3        | 0.24%   |
| Broadcom HP Portable Bumble Bee                                      | 3        | 0.24%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 3        | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 1645     | 29.3%   |
| Intel                                | 1613     | 28.73%  |
| Nvidia                               | 1265     | 22.53%  |
| C-Media Electronics                  | 192      | 3.42%   |
| Logitech                             | 96       | 1.71%   |
| Creative Labs                        | 64       | 1.14%   |
| Kingston Technology                  | 38       | 0.68%   |
| SteelSeries ApS                      | 37       | 0.66%   |
| JMTek                                | 36       | 0.64%   |
| Corsair                              | 36       | 0.64%   |
| Texas Instruments                    | 35       | 0.62%   |
| Focusrite-Novation                   | 34       | 0.61%   |
| Creative Technology                  | 32       | 0.57%   |
| Razer USA                            | 30       | 0.53%   |
| Generalplus Technology               | 23       | 0.41%   |
| Blue Microphones                     | 22       | 0.39%   |
| Plantronics                          | 21       | 0.37%   |
| GYROCOM C&C                          | 19       | 0.34%   |
| GN Netcom                            | 19       | 0.34%   |
| ASUSTek Computer                     | 18       | 0.32%   |
| Sony                                 | 15       | 0.27%   |
| XMOS                                 | 13       | 0.23%   |
| Samson Technologies                  | 12       | 0.21%   |
| Realtek Semiconductor                | 12       | 0.21%   |
| Sennheiser Communications            | 11       | 0.2%    |
| Tenx Technology                      | 10       | 0.18%   |
| RODE Microphones                     | 10       | 0.18%   |
| Giga-Byte Technology                 | 10       | 0.18%   |
| Cambridge Silicon Radio              | 10       | 0.18%   |
| VIA Technologies                     | 8        | 0.14%   |
| SAVITECH                             | 8        | 0.14%   |
| Micro Star International             | 8        | 0.14%   |
| Lenovo                               | 7        | 0.12%   |
| Dell                                 | 7        | 0.12%   |
| Yamaha                               | 6        | 0.11%   |
| Thesycon Systemsoftware & Consulting | 6        | 0.11%   |
| Schiit Audio                         | 6        | 0.11%   |
| PreSonus Audio Electronics           | 6        | 0.11%   |
| FiiO Electronics Technology          | 6        | 0.11%   |
| Unknown                              | 5        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 497      | 7.46%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 296      | 4.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 259      | 3.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 213      | 3.2%    |
| Intel 200 Series PCH HD Audio                                              | 189      | 2.84%   |
| AMD Family 17h/19h HD Audio Controller                                     | 187      | 2.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 185      | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 179      | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 169      | 2.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 148      | 2.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 139      | 2.09%   |
| AMD Navi 10 HDMI Audio                                                     | 133      | 2%      |
| Nvidia GP107GL High Definition Audio Controller                            | 132      | 1.98%   |
| Intel Cannon Lake PCH cAVS                                                 | 128      | 1.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 122      | 1.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 117      | 1.76%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 114      | 1.71%   |
| Nvidia GP104 High Definition Audio Controller                              | 92       | 1.38%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 89       | 1.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 88       | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 88       | 1.32%   |
| Nvidia TU116 High Definition Audio Controller                              | 87       | 1.31%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 81       | 1.22%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 78       | 1.17%   |
| AMD FCH Azalia Controller                                                  | 74       | 1.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 71       | 1.07%   |
| Nvidia TU106 High Definition Audio Controller                              | 66       | 0.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 57       | 0.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 56       | 0.84%   |
| Nvidia TU104 HD Audio Controller                                           | 52       | 0.78%   |
| Nvidia High Definition Audio Controller                                    | 52       | 0.78%   |
| Nvidia GM204 High Definition Audio Controller                              | 52       | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 51       | 0.77%   |
| Nvidia GM206 High Definition Audio Controller                              | 48       | 0.72%   |
| Nvidia GP108 High Definition Audio Controller                              | 45       | 0.68%   |
| Intel Alder Lake-S HD Audio Controller                                     | 45       | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                              | 43       | 0.65%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 43       | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 42       | 0.63%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 41       | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 315      | 19.27%  |
| Corsair                      | 283      | 17.31%  |
| G.Skill                      | 206      | 12.6%   |
| Unknown                      | 178      | 10.89%  |
| Crucial                      | 137      | 8.38%   |
| Samsung Electronics          | 120      | 7.34%   |
| SK hynix                     | 118      | 7.22%   |
| Micron Technology            | 71       | 4.34%   |
| A-DATA Technology            | 31       | 1.9%    |
| Patriot                      | 30       | 1.83%   |
| Team                         | 26       | 1.59%   |
| Ramaxel Technology           | 10       | 0.61%   |
| Nanya Technology             | 10       | 0.61%   |
| Elpida                       | 9        | 0.55%   |
| GOODRAM                      | 7        | 0.43%   |
| Unknown                      | 7        | 0.43%   |
| GeIL                         | 6        | 0.37%   |
| Transcend                    | 5        | 0.31%   |
| Silicon Power                | 5        | 0.31%   |
| Qimonda                      | 4        | 0.24%   |
| PNY                          | 4        | 0.24%   |
| Smart                        | 3        | 0.18%   |
| Qumo                         | 3        | 0.18%   |
| Avant                        | 3        | 0.18%   |
| AMD                          | 3        | 0.18%   |
| OCZ                          | 2        | 0.12%   |
| MINPO                        | 2        | 0.12%   |
| Goldkey                      | 2        | 0.12%   |
| CSX                          | 2        | 0.12%   |
| zApacer                      | 1        | 0.06%   |
| V-GeN                        | 1        | 0.06%   |
| V-Color                      | 1        | 0.06%   |
| Unknown (ABCD)               | 1        | 0.06%   |
| Unknown (AB)                 | 1        | 0.06%   |
| Unknown (9B)                 | 1        | 0.06%   |
| Unknown (0xF7F7F7F7F7F7E300) | 1        | 0.06%   |
| Toshiba                      | 1        | 0.06%   |
| Timetec                      | 1        | 0.06%   |
| Teikon                       | 1        | 0.06%   |
| TakeMS                       | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 33       | 1.85%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s   | 24       | 1.35%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 19       | 1.07%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 15       | 0.84%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s | 14       | 0.79%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 14       | 0.79%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 13       | 0.73%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s  | 13       | 0.73%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s     | 12       | 0.67%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 12       | 0.67%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 10       | 0.56%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 10       | 0.56%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s     | 10       | 0.56%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 9        | 0.51%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s     | 9        | 0.51%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s     | 9        | 0.51%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 8        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 8        | 0.45%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s  | 8        | 0.45%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s     | 8        | 0.45%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s   | 8        | 0.45%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s      | 8        | 0.45%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s      | 8        | 0.45%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s  | 8        | 0.45%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 7        | 0.39%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s | 7        | 0.39%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s       | 7        | 0.39%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 7        | 0.39%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s  | 7        | 0.39%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s  | 7        | 0.39%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s  | 7        | 0.39%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s   | 7        | 0.39%   |
| Unknown                                                 | 7        | 0.39%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 6        | 0.34%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 6        | 0.34%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s     | 6        | 0.34%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s  | 6        | 0.34%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 5        | 0.28%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 5        | 0.28%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s      | 5        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 848      | 57.88%  |
| DDR3    | 426      | 29.08%  |
| Unknown | 85       | 5.8%    |
| DDR2    | 53       | 3.62%   |
| SDRAM   | 33       | 2.25%   |
| DDR     | 10       | 0.68%   |
| DDR5    | 6        | 0.41%   |
| LPDDR3  | 3        | 0.2%    |
| LPDDR4  | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1374     | 94.89%  |
| SODIMM       | 62       | 4.28%   |
| RIMM         | 8        | 0.55%   |
| Row Of Chips | 2        | 0.14%   |
| FB-DIMM      | 2        | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 651      | 41.36%  |
| 4096  | 329      | 20.9%   |
| 16384 | 328      | 20.84%  |
| 2048  | 146      | 9.28%   |
| 32768 | 78       | 4.96%   |
| 1024  | 36       | 2.29%   |
| 512   | 5        | 0.32%   |
| 256   | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 244      | 15.28%  |
| 3200    | 213      | 13.34%  |
| 3600    | 160      | 10.02%  |
| 1333    | 136      | 8.52%   |
| 2400    | 109      | 6.83%   |
| 2133    | 90       | 5.64%   |
| 2667    | 74       | 4.63%   |
| 800     | 52       | 3.26%   |
| 3000    | 46       | 2.88%   |
| 3466    | 42       | 2.63%   |
| 3400    | 41       | 2.57%   |
| 667     | 37       | 2.32%   |
| 1867    | 36       | 2.25%   |
| 2666    | 26       | 1.63%   |
| 3733    | 24       | 1.5%    |
| Unknown | 22       | 1.38%   |
| 3866    | 19       | 1.19%   |
| 3800    | 18       | 1.13%   |
| 2933    | 18       | 1.13%   |
| 1866    | 18       | 1.13%   |
| 1066    | 18       | 1.13%   |
| 2800    | 16       | 1%      |
| 1800    | 12       | 0.75%   |
| 1067    | 10       | 0.63%   |
| 3333    | 8        | 0.5%    |
| 3100    | 8        | 0.5%    |
| 1334    | 8        | 0.5%    |
| 3666    | 5        | 0.31%   |
| 2733    | 5        | 0.31%   |
| 2000    | 5        | 0.31%   |
| 533     | 5        | 0.31%   |
| 5200    | 4        | 0.25%   |
| 4800    | 4        | 0.25%   |
| 3334    | 4        | 0.25%   |
| 400     | 4        | 0.25%   |
| 4400    | 3        | 0.19%   |
| 4133    | 3        | 0.19%   |
| 4000    | 3        | 0.19%   |
| 3500    | 3        | 0.19%   |
| 3151    | 3        | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 60       | 41.1%   |
| Brother Industries    | 35       | 23.97%  |
| Canon                 | 15       | 10.27%  |
| Seiko Epson           | 9        | 6.16%   |
| Samsung Electronics   | 9        | 6.16%   |
| Prolific Technology   | 5        | 3.42%   |
| Lexmark International | 3        | 2.05%   |
| Xerox                 | 2        | 1.37%   |
| Kyocera               | 2        | 1.37%   |
| Star Micronics        | 1        | 0.68%   |
| QinHeng Electronics   | 1        | 0.68%   |
| Graphtec America      | 1        | 0.68%   |
| Dymo-CoStar           | 1        | 0.68%   |
| Dell                  | 1        | 0.68%   |
| Boca Systems          | 1        | 0.68%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port                | 5        | 3.4%    |
| Samsung M2070 Series                         | 4        | 2.72%   |
| HP LaserJet Professional P 1102w             | 4        | 2.72%   |
| Brother HL-L2340D series                     | 4        | 2.72%   |
| HP ENVY 5000 series                          | 3        | 2.04%   |
| HP ENVY 4520 series                          | 3        | 2.04%   |
| HP DeskJet F300 series                       | 3        | 2.04%   |
| Brother Printer                              | 3        | 2.04%   |
| Brother HL-1110 series                       | 3        | 2.04%   |
| Seiko Epson Printer                          | 2        | 1.36%   |
| Samsung ML-216x Series Laser Printer         | 2        | 1.36%   |
| HP OfficeJet 6950                            | 2        | 1.36%   |
| HP DeskJet 3700 series                       | 2        | 1.36%   |
| HP DeskJet 3630 series                       | 2        | 1.36%   |
| HP DeskJet 2620 All-in-One Printer           | 2        | 1.36%   |
| HP DeskJet 2130 series                       | 2        | 1.36%   |
| Canon TS3300 series                          | 2        | 1.36%   |
| Canon TR4500 series                          | 2        | 1.36%   |
| Canon CanoScan LiDE 300                      | 2        | 1.36%   |
| Brother MFC-9330CDW                          | 2        | 1.36%   |
| Brother HL-2230 series                       | 2        | 1.36%   |
| Xerox Phaser 6500DN                          | 1        | 0.68%   |
| Xerox Phaser 3010                            | 1        | 0.68%   |
| Star Micronics TUP592 (STR_T-001)            | 1        | 0.68%   |
| Seiko Epson WF-2510 Series                   | 1        | 0.68%   |
| Seiko Epson PX-045A Series                   | 1        | 0.68%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.68%   |
| Seiko Epson L3110 Series                     | 1        | 0.68%   |
| Seiko Epson L300 Series                      | 1        | 0.68%   |
| Seiko Epson L222 Series                      | 1        | 0.68%   |
| Seiko Epson L100 Series                      | 1        | 0.68%   |
| Samsung Xerox Phaser 3117 Laser Printer      | 1        | 0.68%   |
| Samsung ML-2010P Mono Laser Printer          | 1        | 0.68%   |
| Samsung ML-1640 Series Laser Printer         | 1        | 0.68%   |
| QinHeng CH340S                               | 1        | 0.68%   |
| Lexmark International Lexmark MS521dn        | 1        | 0.68%   |
| Lexmark International Laser Printer E232     | 1        | 0.68%   |
| Lexmark International 2200 series            | 1        | 0.68%   |
| Kyocera TASKalfa 250ci                       | 1        | 0.68%   |
| Kyocera ECOSYS M5521cdw                      | 1        | 0.68%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 21       | 58.33%  |
| Seiko Epson     | 9        | 25%     |
| Hewlett-Packard | 4        | 11.11%  |
| UMAX            | 1        | 2.78%   |
| Mustek Systems  | 1        | 2.78%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500]                   | 4        | 11.11%  |
| Canon CanoScan LIDE 25                                  | 3        | 8.33%   |
| Canon CanoScan LiDE 220                                 | 3        | 8.33%   |
| Canon CanoScan LiDE 210                                 | 3        | 8.33%   |
| Canon CanoScan LiDE 100                                 | 3        | 8.33%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 2        | 5.56%   |
| Canon CanoScan LiDE 110                                 | 2        | 5.56%   |
| UMAX Astra 2200/2200SU                                  | 1        | 2.78%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1        | 2.78%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1        | 2.78%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 2.78%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]             | 1        | 2.78%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1        | 2.78%   |
| Mustek Systems BearPaw 2448 TA Plus                     | 1        | 2.78%   |
| HP ScanJet G4050                                        | 1        | 2.78%   |
| HP ScanJet 5590                                         | 1        | 2.78%   |
| HP ScanJet 3400cse                                      | 1        | 2.78%   |
| HP ScanJet 2400c                                        | 1        | 2.78%   |
| Canon CanoScan N1240U/LiDE 30                           | 1        | 2.78%   |
| Canon CanoScan LiDE 70                                  | 1        | 2.78%   |
| Canon CanoScan LiDE 200                                 | 1        | 2.78%   |
| Canon CanoScan LiDE 120                                 | 1        | 2.78%   |
| Canon CanoScan 4400F                                    | 1        | 2.78%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 352      | 45.42%  |
| Microsoft                              | 66       | 8.52%   |
| Microdia                               | 39       | 5.03%   |
| Apple                                  | 27       | 3.48%   |
| Sunplus Innovation Technology          | 26       | 3.35%   |
| Samsung Electronics                    | 25       | 3.23%   |
| KYE Systems (Mouse Systems)            | 19       | 2.45%   |
| Realtek Semiconductor                  | 18       | 2.32%   |
| Creative Technology                    | 15       | 1.94%   |
| Chicony Electronics                    | 13       | 1.68%   |
| Generalplus Technology                 | 12       | 1.55%   |
| Cubeternet                             | 11       | 1.42%   |
| Z-Star Microelectronics                | 9        | 1.16%   |
| ARC International                      | 9        | 1.16%   |
| 2M UVC CAMERA                          | 9        | 1.16%   |
| Jieli Technology                       | 8        | 1.03%   |
| Razer USA                              | 7        | 0.9%    |
| Lenovo                                 | 7        | 0.9%    |
| Hewlett-Packard                        | 7        | 0.9%    |
| GEMBIRD                                | 7        | 0.9%    |
| Trust                                  | 6        | 0.77%   |
| MacroSilicon                           | 5        | 0.65%   |
| LG Electronics                         | 5        | 0.65%   |
| AVerMedia Technologies                 | 5        | 0.65%   |
| Aveo Technology                        | 4        | 0.52%   |
| Arkmicro Technologies                  | 4        | 0.52%   |
| YGTek                                  | 3        | 0.39%   |
| Unknown                                | 3        | 0.39%   |
| OmniVision Technologies                | 3        | 0.39%   |
| Huawei Technologies                    | 3        | 0.39%   |
| Genesys Logic                          | 3        | 0.39%   |
| Alcor Micro                            | 3        | 0.39%   |
| Valve Software                         | 2        | 0.26%   |
| Sunplus IT                             | 2        | 0.26%   |
| Sonix Technology                       | 2        | 0.26%   |
| Linux Foundation                       | 2        | 0.26%   |
| Intel                                  | 2        | 0.26%   |
| Cheng Uei Precision Industry (Foxlink) | 2        | 0.26%   |
| Asuscom Network                        | 2        | 0.26%   |
| A4Tech                                 | 2        | 0.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                | 83       | 10.55%  |
| Logitech Webcam C270                       | 78       | 9.91%   |
| Microsoft LifeCam HD-3000                  | 25       | 3.18%   |
| Logitech HD Webcam C525                    | 25       | 3.18%   |
| Samsung Galaxy series, misc. (MTP mode)    | 24       | 3.05%   |
| Apple iPhone 5/5C/5S/6/SE                  | 22       | 2.8%    |
| Microdia Webcam Vitade AF                  | 17       | 2.16%   |
| Microsoft LifeCam Cinema                   | 16       | 2.03%   |
| Logitech Webcam C310                       | 16       | 2.03%   |
| Logitech HD Webcam C615                    | 16       | 2.03%   |
| Logitech C922 Pro Stream Webcam            | 15       | 1.91%   |
| Logitech Webcam Pro 9000                   | 14       | 1.78%   |
| Logitech Webcam C170                       | 11       | 1.4%    |
| Logitech BRIO                              | 11       | 1.4%    |
| Logitech Webcam C925e                      | 9        | 1.14%   |
| Logitech StreamCam                         | 9        | 1.14%   |
| ARC International Camera                   | 9        | 1.14%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam        | 9        | 1.14%   |
| Logitech Webcam C930e                      | 8        | 1.02%   |
| Logitech QuickCam Pro 9000                 | 8        | 1.02%   |
| Logitech C920 PRO HD Webcam                | 8        | 1.02%   |
| Jieli USB PHY 2.0                          | 8        | 1.02%   |
| Sunplus HD 720P webcam                     | 7        | 0.89%   |
| Realtek HD webcam                          | 7        | 0.89%   |
| Microdia Hy-HD-Camera                      | 7        | 0.89%   |
| Microsoft LifeCam VX-5000                  | 6        | 0.76%   |
| Logitech Logi 4K Stream Edition            | 6        | 0.76%   |
| Realtek USB Camera                         | 5        | 0.64%   |
| Razer USA Gaming Webcam [Kiyo]             | 5        | 0.64%   |
| Microdia USB 2.0 Camera                    | 5        | 0.64%   |
| Microdia Camera                            | 5        | 0.64%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 5        | 0.64%   |
| Generalplus GENERAL WEBCAM                 | 5        | 0.64%   |
| Creative Live! Cam Sync HD [VF0770]        | 5        | 0.64%   |
| Creative Live! Cam Sync 1080p              | 5        | 0.64%   |
| Sunplus Canyon CNS-CWC5 Webcam             | 4        | 0.51%   |
| Realtek WEB CAMERA M9 Pro                  | 4        | 0.51%   |
| Microsoft LifeCam VX-500 [1357]            | 4        | 0.51%   |
| Microsoft LifeCam Studio                   | 4        | 0.51%   |
| MacroSilicon USB Video                     | 4        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| DigitalPersona        | 2        | 33.33%  |
| Synaptics             | 1        | 16.67%  |
| LighTuning Technology | 1        | 16.67%  |
| Elan Microelectronics | 1        | 16.67%  |
| Dell                  | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader              | 2        | 33.33%  |
| Synaptics  WBDI Fingerprint Reader - USB 052   | 1        | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor    | 1        | 16.67%  |
| Elan fingerprint sensor [FeinTech FPS00200]    | 1        | 16.67%  |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Yubico.com                        | 5        | 15.15%  |
| Alcor Micro                       | 5        | 15.15%  |
| SCM Microsystems                  | 4        | 12.12%  |
| Realtek Semiconductor             | 4        | 12.12%  |
| VASCO Data Security International | 3        | 9.09%   |
| OmniKey                           | 3        | 9.09%   |
| Gemalto (was Gemplus)             | 2        | 6.06%   |
| Fujitsu Siemens Computers         | 1        | 3.03%   |
| Feitian Technologies              | 1        | 3.03%   |
| Clay Logic                        | 1        | 3.03%   |
| Chicony Electronics               | 1        | 3.03%   |
| Cherry                            | 1        | 3.03%   |
| Aktiv                             | 1        | 3.03%   |
| Advanced Card Systems             | 1        | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface               | 4        | 12.12%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                 | 3        | 9.09%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader          | 3        | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                             | 3        | 9.09%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 2        | 6.06%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 2        | 6.06%   |
| Alcor Micro Watchdata W 1981                                    | 2        | 6.06%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                             | 1        | 3.03%   |
| Yubico.com Yubikey 4/5 CCID                                     | 1        | 3.03%   |
| VASCO Data Security International DIGIPASS 870                  | 1        | 3.03%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader      | 1        | 3.03%   |
| OmniKey CardMan 3121 (HID Technologies)                         | 1        | 3.03%   |
| OmniKey CardMan 3021 / 3121                                     | 1        | 3.03%   |
| OmniKey CardMan 1021                                            | 1        | 3.03%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                   | 1        | 3.03%   |
| Feitian Technologies FT SCR310                                  | 1        | 3.03%   |
| Clay Logic Nitrokey Pro                                         | 1        | 3.03%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard            | 1        | 3.03%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                     | 1        | 3.03%   |
| Aktiv Rutoken lite                                              | 1        | 3.03%   |
| Advanced Card Systems ACR122U                                   | 1        | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2654     | 86.11%  |
| 1     | 372      | 12.07%  |
| 2     | 40       | 1.3%    |
| 3     | 6        | 0.19%   |
| 4     | 5        | 0.16%   |
| 5     | 4        | 0.13%   |
| 8     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 146      | 30.67%  |
| Graphics card            | 125      | 26.26%  |
| Unassigned class         | 48       | 10.08%  |
| Sound                    | 27       | 5.67%   |
| Communication controller | 27       | 5.67%   |
| Camera                   | 25       | 5.25%   |
| Multimedia controller    | 21       | 4.41%   |
| Network                  | 10       | 2.1%    |
| Storage/raid             | 9        | 1.89%   |
| Bluetooth                | 9        | 1.89%   |
| Fingerprint reader       | 5        | 1.05%   |
| Chipcard                 | 5        | 1.05%   |
| Card reader              | 5        | 1.05%   |
| Modem                    | 4        | 0.84%   |
| Net/ethernet             | 3        | 0.63%   |
| Firewire controller      | 2        | 0.42%   |
| Dvb card                 | 2        | 0.42%   |
| Wireless                 | 1        | 0.21%   |
| Storage/ata              | 1        | 0.21%   |
| Storage                  | 1        | 0.21%   |

