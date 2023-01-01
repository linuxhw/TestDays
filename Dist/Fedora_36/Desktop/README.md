Fedora 36 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 36.

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

Total: 912

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | X99A RAIDER                 | [8582096251](https://linux-hardware.org/?probe=8582096251) | Dec 31, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [8f06578f10](https://linux-hardware.org/?probe=8f06578f10) | Dec 31, 2022 |
| ASRock        | B450M Pro4                  | [4393041949](https://linux-hardware.org/?probe=4393041949) | Dec 30, 2022 |
| Intel         | LADPNVMO AAE76523-300       | [4e6065532f](https://linux-hardware.org/?probe=4e6065532f) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | [3b0d4e8973](https://linux-hardware.org/?probe=3b0d4e8973) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | [daf7777113](https://linux-hardware.org/?probe=daf7777113) | Dec 29, 2022 |
| BESSTAR Te... | F6BFC                       | [7c6adb6279](https://linux-hardware.org/?probe=7c6adb6279) | Dec 28, 2022 |
| BESSTAR Te... | F6BFC                       | [59b38f9b63](https://linux-hardware.org/?probe=59b38f9b63) | Dec 28, 2022 |
| MSI           | X99A RAIDER                 | [2d572d06d7](https://linux-hardware.org/?probe=2d572d06d7) | Dec 28, 2022 |
| MSI           | X99A RAIDER                 | [cbe4c82d15](https://linux-hardware.org/?probe=cbe4c82d15) | Dec 26, 2022 |
| HP            | 3397                        | [c546bb007b](https://linux-hardware.org/?probe=c546bb007b) | Dec 26, 2022 |
| HP            | 3397                        | [4286520907](https://linux-hardware.org/?probe=4286520907) | Dec 26, 2022 |
| MSI           | X99A RAIDER                 | [8636b69474](https://linux-hardware.org/?probe=8636b69474) | Dec 25, 2022 |
| MSI           | X99A RAIDER                 | [a375cc62c7](https://linux-hardware.org/?probe=a375cc62c7) | Dec 24, 2022 |
| MSI           | X99A RAIDER                 | [c36553b2b8](https://linux-hardware.org/?probe=c36553b2b8) | Dec 23, 2022 |
| MSI           | X99A RAIDER                 | [bfe7b1ec1d](https://linux-hardware.org/?probe=bfe7b1ec1d) | Dec 22, 2022 |
| MSI           | X99A RAIDER                 | [3832e7e0af](https://linux-hardware.org/?probe=3832e7e0af) | Dec 21, 2022 |
| MSI           | X99A RAIDER                 | [8a7ee1147b](https://linux-hardware.org/?probe=8a7ee1147b) | Dec 20, 2022 |
| MSI           | Boston                      | [8587c9cf45](https://linux-hardware.org/?probe=8587c9cf45) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | [900fd62aaf](https://linux-hardware.org/?probe=900fd62aaf) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | [b34721e6cb](https://linux-hardware.org/?probe=b34721e6cb) | Dec 19, 2022 |
| MSI           | X99A RAIDER                 | [b4d6964157](https://linux-hardware.org/?probe=b4d6964157) | Dec 18, 2022 |
| MSI           | X99A RAIDER                 | [be93cca77c](https://linux-hardware.org/?probe=be93cca77c) | Dec 17, 2022 |
| MSI           | X99A RAIDER                 | [9caae58821](https://linux-hardware.org/?probe=9caae58821) | Dec 16, 2022 |
| MSI           | X99A RAIDER                 | [5a071587fb](https://linux-hardware.org/?probe=5a071587fb) | Dec 15, 2022 |
| ASUSTek       | PRIME A320M-K               | [e647deca28](https://linux-hardware.org/?probe=e647deca28) | Dec 14, 2022 |
| MSI           | X370 SLI PLUS               | [7c32d0f453](https://linux-hardware.org/?probe=7c32d0f453) | Dec 14, 2022 |
| MSI           | X99A RAIDER                 | [c8ffea5473](https://linux-hardware.org/?probe=c8ffea5473) | Dec 14, 2022 |
| Intel         | DB75EN AAG39650-400         | [72b3306c33](https://linux-hardware.org/?probe=72b3306c33) | Dec 13, 2022 |
| MSI           | MEG B550 UNIFY              | [e9a996b54a](https://linux-hardware.org/?probe=e9a996b54a) | Dec 12, 2022 |
| Gigabyte      | J1900M-D2P                  | [8111a18c7c](https://linux-hardware.org/?probe=8111a18c7c) | Dec 12, 2022 |
| Intel         | DB75EN AAG39650-400         | [01decbbb6d](https://linux-hardware.org/?probe=01decbbb6d) | Dec 10, 2022 |
| ASUSTek       | P5K Deluxe                  | [6f97813144](https://linux-hardware.org/?probe=6f97813144) | Dec 10, 2022 |
| MSI           | X99A RAIDER                 | [ea91fc57ae](https://linux-hardware.org/?probe=ea91fc57ae) | Dec 09, 2022 |
| MSI           | X99A RAIDER                 | [2d35fb5bbb](https://linux-hardware.org/?probe=2d35fb5bbb) | Dec 08, 2022 |
| Gigabyte      | EP45-DS3P                   | [6844d4578b](https://linux-hardware.org/?probe=6844d4578b) | Dec 07, 2022 |
| MSI           | X370 SLI PLUS               | [e6941ba491](https://linux-hardware.org/?probe=e6941ba491) | Dec 05, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [db7cd6f0dc](https://linux-hardware.org/?probe=db7cd6f0dc) | Dec 04, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [cbb4692837](https://linux-hardware.org/?probe=cbb4692837) | Dec 04, 2022 |
| MSI           | X99A RAIDER                 | [8b85688e36](https://linux-hardware.org/?probe=8b85688e36) | Dec 02, 2022 |
| MSI           | X99A RAIDER                 | [0e87a76042](https://linux-hardware.org/?probe=0e87a76042) | Dec 01, 2022 |
| Unknown       | X99H                        | [b9e2236de7](https://linux-hardware.org/?probe=b9e2236de7) | Nov 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [a6a71120f2](https://linux-hardware.org/?probe=a6a71120f2) | Nov 30, 2022 |
| Gigabyte      | H77N-WIFI                   | [f4fa3a4e7f](https://linux-hardware.org/?probe=f4fa3a4e7f) | Nov 30, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [bc3188dd75](https://linux-hardware.org/?probe=bc3188dd75) | Nov 29, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [8fa53292bf](https://linux-hardware.org/?probe=8fa53292bf) | Nov 27, 2022 |
| Foxconn       | 2ABF                        | [d95233ff31](https://linux-hardware.org/?probe=d95233ff31) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [07363955de](https://linux-hardware.org/?probe=07363955de) | Nov 26, 2022 |
| Biostar       | H310MHC2                    | [49e09047c4](https://linux-hardware.org/?probe=49e09047c4) | Nov 25, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [45dc299d52](https://linux-hardware.org/?probe=45dc299d52) | Nov 25, 2022 |
| MSI           | X99A RAIDER                 | [1c648060f6](https://linux-hardware.org/?probe=1c648060f6) | Nov 25, 2022 |
| MSI           | H81M-E33                    | [80ec8663ac](https://linux-hardware.org/?probe=80ec8663ac) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [ccf106edce](https://linux-hardware.org/?probe=ccf106edce) | Nov 24, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [b154300490](https://linux-hardware.org/?probe=b154300490) | Nov 24, 2022 |
| Gigabyte      | GA-990XA-UD3                | [a5005bf517](https://linux-hardware.org/?probe=a5005bf517) | Nov 24, 2022 |
| MSI           | X99A RAIDER                 | [c1e62a557c](https://linux-hardware.org/?probe=c1e62a557c) | Nov 24, 2022 |
| ASRock        | Z370 Pro4                   | [ced8851dc3](https://linux-hardware.org/?probe=ced8851dc3) | Nov 23, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [990ff088e8](https://linux-hardware.org/?probe=990ff088e8) | Nov 22, 2022 |
| Gigabyte      | B75M-D3H                    | [ac4a817e75](https://linux-hardware.org/?probe=ac4a817e75) | Nov 21, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [8478dece38](https://linux-hardware.org/?probe=8478dece38) | Nov 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b41f6ec236](https://linux-hardware.org/?probe=b41f6ec236) | Nov 21, 2022 |
| HP            | 18E7                        | [0b963b44fb](https://linux-hardware.org/?probe=0b963b44fb) | Nov 21, 2022 |
| ASUSTek       | PRIME Z370-A                | [a890ae6d6c](https://linux-hardware.org/?probe=a890ae6d6c) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [f10fc36516](https://linux-hardware.org/?probe=f10fc36516) | Nov 19, 2022 |
| MSI           | H510M-A PRO                 | [1755321c80](https://linux-hardware.org/?probe=1755321c80) | Nov 19, 2022 |
| ASRock        | AD2700-ITX                  | [806ac66c75](https://linux-hardware.org/?probe=806ac66c75) | Nov 19, 2022 |
| ASUSTek       | Z170-K                      | [1af696c23c](https://linux-hardware.org/?probe=1af696c23c) | Nov 19, 2022 |
| Gigabyte      | X570 GAMING X               | [587db1b08f](https://linux-hardware.org/?probe=587db1b08f) | Nov 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [7de2db4d3a](https://linux-hardware.org/?probe=7de2db4d3a) | Nov 18, 2022 |
| Gigabyte      | H61M-USB3V                  | [e034e5bbb2](https://linux-hardware.org/?probe=e034e5bbb2) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | [a8847bb3ad](https://linux-hardware.org/?probe=a8847bb3ad) | Nov 18, 2022 |
| Dell          | 0X30MX A00                  | [c3657c7f97](https://linux-hardware.org/?probe=c3657c7f97) | Nov 18, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [e9eb63ca62](https://linux-hardware.org/?probe=e9eb63ca62) | Nov 17, 2022 |
| MSI           | X99A RAIDER                 | [5d1e2af2ea](https://linux-hardware.org/?probe=5d1e2af2ea) | Nov 17, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [cd01bd7dad](https://linux-hardware.org/?probe=cd01bd7dad) | Nov 16, 2022 |
| MSI           | X99A RAIDER                 | [620dbe0a8f](https://linux-hardware.org/?probe=620dbe0a8f) | Nov 16, 2022 |
| ASUSTek       | B85M-E                      | [2455b541f5](https://linux-hardware.org/?probe=2455b541f5) | Nov 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [9cd3d86efc](https://linux-hardware.org/?probe=9cd3d86efc) | Nov 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1472f0a14e](https://linux-hardware.org/?probe=1472f0a14e) | Nov 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [ea39f5300c](https://linux-hardware.org/?probe=ea39f5300c) | Nov 15, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [459c5879e6](https://linux-hardware.org/?probe=459c5879e6) | Nov 15, 2022 |
| Intel         | DB75EN AAG39650-400         | [07d6aa9adc](https://linux-hardware.org/?probe=07d6aa9adc) | Nov 14, 2022 |
| Dell          | 06X1TJ A00                  | [4a19565db2](https://linux-hardware.org/?probe=4a19565db2) | Nov 14, 2022 |
| ASUSTek       | CM6870                      | [c050452a72](https://linux-hardware.org/?probe=c050452a72) | Nov 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5b9f10af19](https://linux-hardware.org/?probe=5b9f10af19) | Nov 14, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [9d942ddc9c](https://linux-hardware.org/?probe=9d942ddc9c) | Nov 13, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [2c896d28a8](https://linux-hardware.org/?probe=2c896d28a8) | Nov 13, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [97bfce0a04](https://linux-hardware.org/?probe=97bfce0a04) | Nov 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [256503ef7e](https://linux-hardware.org/?probe=256503ef7e) | Nov 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | [c73b422075](https://linux-hardware.org/?probe=c73b422075) | Nov 12, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [cedb086e46](https://linux-hardware.org/?probe=cedb086e46) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [6eedcdeb01](https://linux-hardware.org/?probe=6eedcdeb01) | Nov 11, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [022a97b52e](https://linux-hardware.org/?probe=022a97b52e) | Nov 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [3f11ca7016](https://linux-hardware.org/?probe=3f11ca7016) | Nov 11, 2022 |
| ASRock        | H81M-DGS R2.0               | [07bae444fc](https://linux-hardware.org/?probe=07bae444fc) | Nov 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [578b9c0e61](https://linux-hardware.org/?probe=578b9c0e61) | Nov 11, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [009f3d82e9](https://linux-hardware.org/?probe=009f3d82e9) | Nov 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [faf531627e](https://linux-hardware.org/?probe=faf531627e) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f49624457d](https://linux-hardware.org/?probe=f49624457d) | Nov 09, 2022 |
| Dell          | 0RW203 A00                  | [67fa42f70a](https://linux-hardware.org/?probe=67fa42f70a) | Nov 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [226409c98f](https://linux-hardware.org/?probe=226409c98f) | Nov 09, 2022 |
| Foxconn       | H61M-S/H61M                 | [81b2006fd3](https://linux-hardware.org/?probe=81b2006fd3) | Nov 09, 2022 |
| ASRock        | Z77 Pro4-M                  | [3a4a75d603](https://linux-hardware.org/?probe=3a4a75d603) | Nov 08, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0b65e26932](https://linux-hardware.org/?probe=0b65e26932) | Nov 08, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | [6987230f73](https://linux-hardware.org/?probe=6987230f73) | Nov 07, 2022 |
| ASUSTek       | PRIME Z370-A                | [d87a3e023a](https://linux-hardware.org/?probe=d87a3e023a) | Nov 07, 2022 |
| Gigabyte      | B450M GAMING                | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [55b349ab41](https://linux-hardware.org/?probe=55b349ab41) | Nov 05, 2022 |
| Dell          | 096JG8 A01                  | [e8a62297a5](https://linux-hardware.org/?probe=e8a62297a5) | Nov 05, 2022 |
| ASUSTek       | PRO H410T                   | [66a809ab24](https://linux-hardware.org/?probe=66a809ab24) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [56db615f30](https://linux-hardware.org/?probe=56db615f30) | Nov 05, 2022 |
| ASRock        | X370 Taichi                 | [02a767e075](https://linux-hardware.org/?probe=02a767e075) | Nov 04, 2022 |
| HP            | 339A                        | [77ddeeda51](https://linux-hardware.org/?probe=77ddeeda51) | Nov 04, 2022 |
| HP            | 339A                        | [8ebb8b6522](https://linux-hardware.org/?probe=8ebb8b6522) | Nov 04, 2022 |
| HP            | 2B05                        | [5c0a96cd5b](https://linux-hardware.org/?probe=5c0a96cd5b) | Nov 04, 2022 |
| HP            | 2B05                        | [95b5255056](https://linux-hardware.org/?probe=95b5255056) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [f027f3a4e2](https://linux-hardware.org/?probe=f027f3a4e2) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [cb9374e939](https://linux-hardware.org/?probe=cb9374e939) | Nov 04, 2022 |
| ASUSTek       | PRIME Z270-P                | [ec0599883c](https://linux-hardware.org/?probe=ec0599883c) | Nov 03, 2022 |
| Gigabyte      | G41MT-D3                    | [921a646464](https://linux-hardware.org/?probe=921a646464) | Nov 03, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [c9041d22be](https://linux-hardware.org/?probe=c9041d22be) | Nov 02, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9b093574b9](https://linux-hardware.org/?probe=9b093574b9) | Nov 02, 2022 |
| Gigabyte      | B550 UD AC                  | [c5a5219cf3](https://linux-hardware.org/?probe=c5a5219cf3) | Nov 01, 2022 |
| MSI           | H81M-E33                    | [ee4c33d7b1](https://linux-hardware.org/?probe=ee4c33d7b1) | Nov 01, 2022 |
| HP            | 339A                        | [68392c18c9](https://linux-hardware.org/?probe=68392c18c9) | Nov 01, 2022 |
| MSI           | PRO B660M-A DDR4            | [f6b6afc8a3](https://linux-hardware.org/?probe=f6b6afc8a3) | Nov 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [a2a8473e4b](https://linux-hardware.org/?probe=a2a8473e4b) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [479fdd085d](https://linux-hardware.org/?probe=479fdd085d) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [dfde89926c](https://linux-hardware.org/?probe=dfde89926c) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [135f93d663](https://linux-hardware.org/?probe=135f93d663) | Oct 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [4ac9bf1711](https://linux-hardware.org/?probe=4ac9bf1711) | Oct 31, 2022 |
| MSI           | B250M GAMING PRO            | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [ce9a718851](https://linux-hardware.org/?probe=ce9a718851) | Oct 28, 2022 |
| Gigabyte      | G41MT-D3                    | [2e4153161f](https://linux-hardware.org/?probe=2e4153161f) | Oct 28, 2022 |
| ASRock        | X99 Extreme4                | [72102d6890](https://linux-hardware.org/?probe=72102d6890) | Oct 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [38135da604](https://linux-hardware.org/?probe=38135da604) | Oct 28, 2022 |
| MSI           | H81M-E33                    | [f0613bfce8](https://linux-hardware.org/?probe=f0613bfce8) | Oct 27, 2022 |
| Gigabyte      | H97N-WIFI                   | [aa2345213b](https://linux-hardware.org/?probe=aa2345213b) | Oct 27, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d2debd1dab](https://linux-hardware.org/?probe=d2debd1dab) | Oct 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [6c7c7fa216](https://linux-hardware.org/?probe=6c7c7fa216) | Oct 26, 2022 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | [2bed8fe9b1](https://linux-hardware.org/?probe=2bed8fe9b1) | Oct 26, 2022 |
| HP            | ProLiant ML350 G6           | [d080f0956b](https://linux-hardware.org/?probe=d080f0956b) | Oct 26, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [958c0a2ae7](https://linux-hardware.org/?probe=958c0a2ae7) | Oct 25, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [6896f337ab](https://linux-hardware.org/?probe=6896f337ab) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-P                | [0eb9c3ebff](https://linux-hardware.org/?probe=0eb9c3ebff) | Oct 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [0c63b974e1](https://linux-hardware.org/?probe=0c63b974e1) | Oct 25, 2022 |
| ASRock        | FM2A88M-HD+ R2.0            | [10e0a497e9](https://linux-hardware.org/?probe=10e0a497e9) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [82fb357322](https://linux-hardware.org/?probe=82fb357322) | Oct 25, 2022 |
| Gigabyte      | A520M DS3H                  | [88e45a4e65](https://linux-hardware.org/?probe=88e45a4e65) | Oct 25, 2022 |
| MSI           | MAG A520M VECTOR WIFI       | [91a8a52c4a](https://linux-hardware.org/?probe=91a8a52c4a) | Oct 25, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Core ... | [601e080563](https://linux-hardware.org/?probe=601e080563) | Oct 25, 2022 |
| ASRock        | Z170 Gaming K4              | [184139e7bc](https://linux-hardware.org/?probe=184139e7bc) | Oct 24, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [3f6368ca5a](https://linux-hardware.org/?probe=3f6368ca5a) | Oct 24, 2022 |
| HP            | 3048h                       | [3c3f7eda5e](https://linux-hardware.org/?probe=3c3f7eda5e) | Oct 24, 2022 |
| ASRock        | X370 Gaming K4              | [5658dbff1b](https://linux-hardware.org/?probe=5658dbff1b) | Oct 24, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [2a57a65990](https://linux-hardware.org/?probe=2a57a65990) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5010a8ef47](https://linux-hardware.org/?probe=5010a8ef47) | Oct 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [fe9ec739e2](https://linux-hardware.org/?probe=fe9ec739e2) | Oct 24, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [b9e4b934ee](https://linux-hardware.org/?probe=b9e4b934ee) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [22ea226b97](https://linux-hardware.org/?probe=22ea226b97) | Oct 23, 2022 |
| ASUSTek       | Z170-A                      | [22a96186fa](https://linux-hardware.org/?probe=22a96186fa) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b42893c91e](https://linux-hardware.org/?probe=b42893c91e) | Oct 22, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [b633b478aa](https://linux-hardware.org/?probe=b633b478aa) | Oct 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b7ad660d88](https://linux-hardware.org/?probe=b7ad660d88) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [312828c6a3](https://linux-hardware.org/?probe=312828c6a3) | Oct 22, 2022 |
| Gigabyte      | H77N-WIFI                   | [3e2bd05f56](https://linux-hardware.org/?probe=3e2bd05f56) | Oct 22, 2022 |
| MSI           | MAG B460M BAZOOKA           | [9cfe9f3c51](https://linux-hardware.org/?probe=9cfe9f3c51) | Oct 22, 2022 |
| Dell          | 0PP150 A00                  | [0e07990bda](https://linux-hardware.org/?probe=0e07990bda) | Oct 22, 2022 |
| Unknown       | X79                         | [fd8f23bc70](https://linux-hardware.org/?probe=fd8f23bc70) | Oct 21, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [1ab730c85c](https://linux-hardware.org/?probe=1ab730c85c) | Oct 21, 2022 |
| HP            | 8459                        | [c2ebcf9e20](https://linux-hardware.org/?probe=c2ebcf9e20) | Oct 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [60d4787bb7](https://linux-hardware.org/?probe=60d4787bb7) | Oct 21, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [f03f1bb041](https://linux-hardware.org/?probe=f03f1bb041) | Oct 20, 2022 |
| HP            | 8433 11                     | [7e28f54181](https://linux-hardware.org/?probe=7e28f54181) | Oct 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [502ae94f8f](https://linux-hardware.org/?probe=502ae94f8f) | Oct 20, 2022 |
| NZXT          | N7 B550                     | [f699b7e1d2](https://linux-hardware.org/?probe=f699b7e1d2) | Oct 20, 2022 |
| HP            | 8459                        | [d8ec2e7ee9](https://linux-hardware.org/?probe=d8ec2e7ee9) | Oct 20, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [76c0902958](https://linux-hardware.org/?probe=76c0902958) | Oct 19, 2022 |
| Gigabyte      | P67A-UD3                    | [96b72bfa8a](https://linux-hardware.org/?probe=96b72bfa8a) | Oct 19, 2022 |
| Shuttle       | FH67H                       | [6679449225](https://linux-hardware.org/?probe=6679449225) | Oct 19, 2022 |
| MSI           | Z97 GAMING 5                | [980d0d7bb2](https://linux-hardware.org/?probe=980d0d7bb2) | Oct 19, 2022 |
| Gigabyte      | B550M DS3H                  | [d267c64062](https://linux-hardware.org/?probe=d267c64062) | Oct 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [41d2e6298d](https://linux-hardware.org/?probe=41d2e6298d) | Oct 19, 2022 |
| ASUSTek       | P5B-Deluxe                  | [95a75ab35b](https://linux-hardware.org/?probe=95a75ab35b) | Oct 19, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [495c7fdc3d](https://linux-hardware.org/?probe=495c7fdc3d) | Oct 18, 2022 |
| BESSTAR Te... | F6BFC                       | [70d12e710f](https://linux-hardware.org/?probe=70d12e710f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | [5c2590f03f](https://linux-hardware.org/?probe=5c2590f03f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | [df0afd4326](https://linux-hardware.org/?probe=df0afd4326) | Oct 18, 2022 |
| ASRock        | Z97E-ITX/ac                 | [2ae712a746](https://linux-hardware.org/?probe=2ae712a746) | Oct 18, 2022 |
| ASUSTek       | PRIME Z690-A                | [50fe9fcad5](https://linux-hardware.org/?probe=50fe9fcad5) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | [77f04d4628](https://linux-hardware.org/?probe=77f04d4628) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | [ee436e327b](https://linux-hardware.org/?probe=ee436e327b) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | [86e01f1479](https://linux-hardware.org/?probe=86e01f1479) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [1993500f68](https://linux-hardware.org/?probe=1993500f68) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8557c8b501](https://linux-hardware.org/?probe=8557c8b501) | Oct 15, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6de814388c](https://linux-hardware.org/?probe=6de814388c) | Oct 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [1200f4104f](https://linux-hardware.org/?probe=1200f4104f) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [79eba98b95](https://linux-hardware.org/?probe=79eba98b95) | Oct 14, 2022 |
| ASUSTek       | PRIME Z270-A                | [a6083f4dfe](https://linux-hardware.org/?probe=a6083f4dfe) | Oct 13, 2022 |
| ASUSTek       | Z97-K                       | [47394cb2b5](https://linux-hardware.org/?probe=47394cb2b5) | Oct 13, 2022 |
| ASUSTek       | P8P67 LE                    | [0c7961c445](https://linux-hardware.org/?probe=0c7961c445) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d0d2949fd3](https://linux-hardware.org/?probe=d0d2949fd3) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| BESSTAR Te... | UM350                       | [f58608a000](https://linux-hardware.org/?probe=f58608a000) | Oct 11, 2022 |
| Gigabyte      | J1900M-D2P                  | [dde4a94108](https://linux-hardware.org/?probe=dde4a94108) | Oct 11, 2022 |
| Gigabyte      | H410M DS2V                  | [bd9d9e10c7](https://linux-hardware.org/?probe=bd9d9e10c7) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e2d9db1022](https://linux-hardware.org/?probe=e2d9db1022) | Oct 10, 2022 |
| ASRock        | X570 PG Velocita            | [ec3a819326](https://linux-hardware.org/?probe=ec3a819326) | Oct 10, 2022 |
| Intel         | DG41TY AAE47335-302         | [c0d07ec775](https://linux-hardware.org/?probe=c0d07ec775) | Oct 10, 2022 |
| MSI           | B450 GAMING PLUS            | [6f95e1591a](https://linux-hardware.org/?probe=6f95e1591a) | Oct 10, 2022 |
| MSI           | A320M-A PRO MAX             | [edb6e4180f](https://linux-hardware.org/?probe=edb6e4180f) | Oct 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [4aa8b37ac5](https://linux-hardware.org/?probe=4aa8b37ac5) | Oct 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [30ff2d0e8f](https://linux-hardware.org/?probe=30ff2d0e8f) | Oct 09, 2022 |
| Pegatron      | 2AD5                        | [19ad61d9c7](https://linux-hardware.org/?probe=19ad61d9c7) | Oct 09, 2022 |
| ASUSTek       | PRIME Z270-A                | [0f4a711f6a](https://linux-hardware.org/?probe=0f4a711f6a) | Oct 08, 2022 |
| HP            | 3647h                       | [ddffa21a6e](https://linux-hardware.org/?probe=ddffa21a6e) | Oct 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8895a815c6](https://linux-hardware.org/?probe=8895a815c6) | Oct 07, 2022 |
| Unknown       | Intel X79                   | [9c0ffde822](https://linux-hardware.org/?probe=9c0ffde822) | Oct 06, 2022 |
| HP            | 0AECh D                     | [8fd13e9017](https://linux-hardware.org/?probe=8fd13e9017) | Oct 06, 2022 |
| MSI           | X370 SLI PLUS               | [ea7dc6a41a](https://linux-hardware.org/?probe=ea7dc6a41a) | Oct 06, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [3ea8d4d25e](https://linux-hardware.org/?probe=3ea8d4d25e) | Oct 06, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [20b6b5f918](https://linux-hardware.org/?probe=20b6b5f918) | Oct 06, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [7f2b63950d](https://linux-hardware.org/?probe=7f2b63950d) | Oct 05, 2022 |
| MSI           | MEG Z390 GODLIKE            | [368530a660](https://linux-hardware.org/?probe=368530a660) | Oct 05, 2022 |
| MSI           | MEG Z490I UNIFY             | [a60e3c519e](https://linux-hardware.org/?probe=a60e3c519e) | Oct 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [ca81117136](https://linux-hardware.org/?probe=ca81117136) | Oct 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [07d4cf95ec](https://linux-hardware.org/?probe=07d4cf95ec) | Oct 04, 2022 |
| Gigabyte      | B85M-D2V                    | [4e6047ec5b](https://linux-hardware.org/?probe=4e6047ec5b) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [48e867fba8](https://linux-hardware.org/?probe=48e867fba8) | Oct 02, 2022 |
| Acer          | Veriton X6620G v1.0         | [80e98d9053](https://linux-hardware.org/?probe=80e98d9053) | Oct 02, 2022 |
| MSI           | B350 TOMAHAWK               | [253e143d94](https://linux-hardware.org/?probe=253e143d94) | Oct 02, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6121fee541](https://linux-hardware.org/?probe=6121fee541) | Oct 02, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6d8ed9f182](https://linux-hardware.org/?probe=6d8ed9f182) | Oct 02, 2022 |
| ASRock        | X570 Phantom Gaming 4S      | [2215129a47](https://linux-hardware.org/?probe=2215129a47) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [ee22a244e2](https://linux-hardware.org/?probe=ee22a244e2) | Oct 01, 2022 |
| ASRock        | AD2700-ITX                  | [4275ef3653](https://linux-hardware.org/?probe=4275ef3653) | Oct 01, 2022 |
| Gigabyte      | B75M-D3H                    | [162334ac1e](https://linux-hardware.org/?probe=162334ac1e) | Sep 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [c06e7e3586](https://linux-hardware.org/?probe=c06e7e3586) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| ASRock        | H270M-ITX/ac                | [c6ae2f8a45](https://linux-hardware.org/?probe=c6ae2f8a45) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| Biostar       | H410MH S2                   | [fbba79fc43](https://linux-hardware.org/?probe=fbba79fc43) | Sep 28, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| Dell          | 0YGYJY A01                  | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | [7af967061b](https://linux-hardware.org/?probe=7af967061b) | Sep 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6373bf42ef](https://linux-hardware.org/?probe=6373bf42ef) | Sep 26, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [778f7340fa](https://linux-hardware.org/?probe=778f7340fa) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | [982d41c1eb](https://linux-hardware.org/?probe=982d41c1eb) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [82b73270ca](https://linux-hardware.org/?probe=82b73270ca) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | [a5d5950e29](https://linux-hardware.org/?probe=a5d5950e29) | Sep 25, 2022 |
| MSI           | MAG Z590 TORPEDO            | [cedbd8909f](https://linux-hardware.org/?probe=cedbd8909f) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [a1f261d09d](https://linux-hardware.org/?probe=a1f261d09d) | Sep 25, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [66b5b65077](https://linux-hardware.org/?probe=66b5b65077) | Sep 25, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [a35dda8c10](https://linux-hardware.org/?probe=a35dda8c10) | Sep 25, 2022 |
| ASRock        | Z170M Extreme4              | [bd1e98639b](https://linux-hardware.org/?probe=bd1e98639b) | Sep 24, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [542249f675](https://linux-hardware.org/?probe=542249f675) | Sep 24, 2022 |
| ASUSTek       | PRIME B365M-A               | [c4c88d72ae](https://linux-hardware.org/?probe=c4c88d72ae) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [31f1acf273](https://linux-hardware.org/?probe=31f1acf273) | Sep 23, 2022 |
| ASUSTek       | PRIME B250M-C               | [2e45736b42](https://linux-hardware.org/?probe=2e45736b42) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a4ce7c179e](https://linux-hardware.org/?probe=a4ce7c179e) | Sep 23, 2022 |
| Gigabyte      | B660I AORUS PRO DDR4        | [810c7883d4](https://linux-hardware.org/?probe=810c7883d4) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [7d69f0c6c6](https://linux-hardware.org/?probe=7d69f0c6c6) | Sep 23, 2022 |
| Gigabyte      | Z270P-D3-CF                 | [79509e063b](https://linux-hardware.org/?probe=79509e063b) | Sep 23, 2022 |
| Foxconn       | H61M-S/H61M                 | [039b5cff54](https://linux-hardware.org/?probe=039b5cff54) | Sep 22, 2022 |
| MSI           | H310M PRO-VH                | [c11e067cb5](https://linux-hardware.org/?probe=c11e067cb5) | Sep 22, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [11ea16f0d6](https://linux-hardware.org/?probe=11ea16f0d6) | Sep 22, 2022 |
| BESSTAR Te... | UM350                       | [62a9723eb7](https://linux-hardware.org/?probe=62a9723eb7) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | [20d37d51bd](https://linux-hardware.org/?probe=20d37d51bd) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | [cabebaa0e6](https://linux-hardware.org/?probe=cabebaa0e6) | Sep 21, 2022 |
| HP            | ProLiant ML110 G7           | [d5b4924a7b](https://linux-hardware.org/?probe=d5b4924a7b) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | [015c8dd353](https://linux-hardware.org/?probe=015c8dd353) | Sep 20, 2022 |
| ASUSTek       | Z97-AR                      | [5cf4494f07](https://linux-hardware.org/?probe=5cf4494f07) | Sep 20, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [75854836f7](https://linux-hardware.org/?probe=75854836f7) | Sep 20, 2022 |
| Dell          | 0K3CM7 A00                  | [3f82789198](https://linux-hardware.org/?probe=3f82789198) | Sep 20, 2022 |
| Dell          | 0K3CM7 A00                  | [b6ce2720e2](https://linux-hardware.org/?probe=b6ce2720e2) | Sep 20, 2022 |
| ASRock        | H610M-HDV/M.2               | [02a5a10d7a](https://linux-hardware.org/?probe=02a5a10d7a) | Sep 20, 2022 |
| ASUSTek       | PRIME Z270-P                | [d44ac0cc2a](https://linux-hardware.org/?probe=d44ac0cc2a) | Sep 19, 2022 |
| Dell          | 0J3C2F A02                  | [8027be6f7e](https://linux-hardware.org/?probe=8027be6f7e) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [f8bf8fd596](https://linux-hardware.org/?probe=f8bf8fd596) | Sep 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7a1dbe2204](https://linux-hardware.org/?probe=7a1dbe2204) | Sep 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [8072b6c0e0](https://linux-hardware.org/?probe=8072b6c0e0) | Sep 19, 2022 |
| ASUSTek       | P8Q77-M2                    | [1e067b7c4f](https://linux-hardware.org/?probe=1e067b7c4f) | Sep 19, 2022 |
| Dell          | 0KWVT8 A03                  | [7c52790345](https://linux-hardware.org/?probe=7c52790345) | Sep 19, 2022 |
| ASRock        | X570 Steel Legend           | [6fd34fa73b](https://linux-hardware.org/?probe=6fd34fa73b) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H                  | [bf7318e65e](https://linux-hardware.org/?probe=bf7318e65e) | Sep 19, 2022 |
| ASUSTek       | Z97-P                       | [37f0f7b888](https://linux-hardware.org/?probe=37f0f7b888) | Sep 19, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [75be2db65c](https://linux-hardware.org/?probe=75be2db65c) | Sep 19, 2022 |
| Dell          | 02M8NY A01                  | [498286eb91](https://linux-hardware.org/?probe=498286eb91) | Sep 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [3da12828c0](https://linux-hardware.org/?probe=3da12828c0) | Sep 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [6c63c03b9f](https://linux-hardware.org/?probe=6c63c03b9f) | Sep 19, 2022 |
| ASRock        | 960GM-VGS3 FX               | [7c89dc4342](https://linux-hardware.org/?probe=7c89dc4342) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [8d2c35d5f2](https://linux-hardware.org/?probe=8d2c35d5f2) | Sep 19, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [27d1f0c593](https://linux-hardware.org/?probe=27d1f0c593) | Sep 19, 2022 |
| ASUSTek       | P8Q77-M2                    | [171e24a5c1](https://linux-hardware.org/?probe=171e24a5c1) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | [798bb8eda6](https://linux-hardware.org/?probe=798bb8eda6) | Sep 18, 2022 |
| ASUSTek       | PRIME H410M-K R2.0          | [7d18b85f33](https://linux-hardware.org/?probe=7d18b85f33) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [21da8441d5](https://linux-hardware.org/?probe=21da8441d5) | Sep 18, 2022 |
| Casper        | NIRVANA DESKTOP             | [7cdffad4a2](https://linux-hardware.org/?probe=7cdffad4a2) | Sep 18, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [1f27376b8e](https://linux-hardware.org/?probe=1f27376b8e) | Sep 18, 2022 |
| Acer          | Aspire TC-780               | [936ece435c](https://linux-hardware.org/?probe=936ece435c) | Sep 18, 2022 |
| Acer          | A75F2-M2 P21-A1             | [2d00ba463b](https://linux-hardware.org/?probe=2d00ba463b) | Sep 18, 2022 |
| ASRock        | B550M-ITX/ac                | [379aaf7b61](https://linux-hardware.org/?probe=379aaf7b61) | Sep 16, 2022 |
| ASUSTek       | PRIME B365M-A               | [e191511194](https://linux-hardware.org/?probe=e191511194) | Sep 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | [07dd87b76b](https://linux-hardware.org/?probe=07dd87b76b) | Sep 16, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4d460404c8](https://linux-hardware.org/?probe=4d460404c8) | Sep 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9bfc1472d1](https://linux-hardware.org/?probe=9bfc1472d1) | Sep 16, 2022 |
| ASRock        | X370 Gaming K4              | [0858e80da7](https://linux-hardware.org/?probe=0858e80da7) | Sep 15, 2022 |
| Gigabyte      | Z97P-D3                     | [ca9e537823](https://linux-hardware.org/?probe=ca9e537823) | Sep 15, 2022 |
| ASUSTek       | P5PL2-E                     | [84bfb7d319](https://linux-hardware.org/?probe=84bfb7d319) | Sep 15, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [55216d250b](https://linux-hardware.org/?probe=55216d250b) | Sep 14, 2022 |
| HP            | 805D                        | [8acaebbd42](https://linux-hardware.org/?probe=8acaebbd42) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e7cb70c141](https://linux-hardware.org/?probe=e7cb70c141) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [754d0f3a2b](https://linux-hardware.org/?probe=754d0f3a2b) | Sep 14, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [175c84f6ea](https://linux-hardware.org/?probe=175c84f6ea) | Sep 13, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [d3f957e34a](https://linux-hardware.org/?probe=d3f957e34a) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [9b2a84cd02](https://linux-hardware.org/?probe=9b2a84cd02) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [1285ab4d66](https://linux-hardware.org/?probe=1285ab4d66) | Sep 13, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | [1faad914c6](https://linux-hardware.org/?probe=1faad914c6) | Sep 13, 2022 |
| Unknown       | X99H                        | [9fb8886110](https://linux-hardware.org/?probe=9fb8886110) | Sep 13, 2022 |
| Dell          | 0M017G A00                  | [e040958337](https://linux-hardware.org/?probe=e040958337) | Sep 13, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [7ce5d8e865](https://linux-hardware.org/?probe=7ce5d8e865) | Sep 12, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [ec5f57ab65](https://linux-hardware.org/?probe=ec5f57ab65) | Sep 12, 2022 |
| HP            | 1494                        | [0faa06cff4](https://linux-hardware.org/?probe=0faa06cff4) | Sep 12, 2022 |
| BESSTAR Te... | UM700                       | [6847632df3](https://linux-hardware.org/?probe=6847632df3) | Sep 12, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [a3b824ba41](https://linux-hardware.org/?probe=a3b824ba41) | Sep 10, 2022 |
| ASUSTek       | Z170-A                      | [66c2198f48](https://linux-hardware.org/?probe=66c2198f48) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | [841be89be6](https://linux-hardware.org/?probe=841be89be6) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | [626cf13c17](https://linux-hardware.org/?probe=626cf13c17) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | [6ce0fb28ee](https://linux-hardware.org/?probe=6ce0fb28ee) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | [5cce5f5ade](https://linux-hardware.org/?probe=5cce5f5ade) | Sep 10, 2022 |
| ASUSTek       | B150 PRO GAMING             | [5e145ec2d1](https://linux-hardware.org/?probe=5e145ec2d1) | Sep 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [2cb423c8e7](https://linux-hardware.org/?probe=2cb423c8e7) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [03979fc286](https://linux-hardware.org/?probe=03979fc286) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [c6dac06569](https://linux-hardware.org/?probe=c6dac06569) | Sep 09, 2022 |
| Gigabyte      | H77N-WIFI                   | [3c454664b0](https://linux-hardware.org/?probe=3c454664b0) | Sep 09, 2022 |
| ASRock        | B550M Pro4                  | [e43ef549eb](https://linux-hardware.org/?probe=e43ef549eb) | Sep 08, 2022 |
| ASRock        | B550M Pro4                  | [ac6cb859ad](https://linux-hardware.org/?probe=ac6cb859ad) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | [aeb2bae778](https://linux-hardware.org/?probe=aeb2bae778) | Sep 08, 2022 |
| Intel         | DH77DF AAG40293-300         | [217971d572](https://linux-hardware.org/?probe=217971d572) | Sep 08, 2022 |
| Dell          | 02YRK5 A02                  | [daf3e0182b](https://linux-hardware.org/?probe=daf3e0182b) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | [d5040ffbda](https://linux-hardware.org/?probe=d5040ffbda) | Sep 08, 2022 |
| HP            | 18E4                        | [1e8addf905](https://linux-hardware.org/?probe=1e8addf905) | Sep 08, 2022 |
| ASUSTek       | H110M-A                     | [dad38946f6](https://linux-hardware.org/?probe=dad38946f6) | Sep 08, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [0f0a18c852](https://linux-hardware.org/?probe=0f0a18c852) | Sep 08, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [e06271e233](https://linux-hardware.org/?probe=e06271e233) | Sep 08, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [051ea3b002](https://linux-hardware.org/?probe=051ea3b002) | Sep 08, 2022 |
| MSI           | Z97 PC Mate                 | [bcf93bb718](https://linux-hardware.org/?probe=bcf93bb718) | Sep 08, 2022 |
| Dell          | 02YRK5 A02                  | [2395ab5aed](https://linux-hardware.org/?probe=2395ab5aed) | Sep 07, 2022 |
| ASUSTek       | H97-PRO                     | [fb4bfcf055](https://linux-hardware.org/?probe=fb4bfcf055) | Sep 07, 2022 |
| ASRock        | EP2C602                     | [56a6980ddc](https://linux-hardware.org/?probe=56a6980ddc) | Sep 07, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [a816f4f60b](https://linux-hardware.org/?probe=a816f4f60b) | Sep 07, 2022 |
| ASUSTek       | Z97-AR                      | [01dbdc3b29](https://linux-hardware.org/?probe=01dbdc3b29) | Sep 06, 2022 |
| MSI           | MEG X570 ACE                | [5f7f592f25](https://linux-hardware.org/?probe=5f7f592f25) | Sep 05, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e83fa739c9](https://linux-hardware.org/?probe=e83fa739c9) | Sep 05, 2022 |
| MSI           | B550-A PRO                  | [950b2a8eb5](https://linux-hardware.org/?probe=950b2a8eb5) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [127c2f5f75](https://linux-hardware.org/?probe=127c2f5f75) | Sep 05, 2022 |
| Gigabyte      | EP45-DS3L                   | [cb17ac9b4e](https://linux-hardware.org/?probe=cb17ac9b4e) | Sep 05, 2022 |
| Gigabyte      | Z370M DS3H-CF               | [e590a83122](https://linux-hardware.org/?probe=e590a83122) | Sep 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [7c87d1ad42](https://linux-hardware.org/?probe=7c87d1ad42) | Sep 05, 2022 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [b4a71c0eff](https://linux-hardware.org/?probe=b4a71c0eff) | Sep 04, 2022 |
| ASUSTek       | KCMA-D8                     | [df5fdfccf0](https://linux-hardware.org/?probe=df5fdfccf0) | Sep 04, 2022 |
| MSI           | H510M-A PRO                 | [7bb2d68f03](https://linux-hardware.org/?probe=7bb2d68f03) | Sep 04, 2022 |
| Gigabyte      | F2A78M-D3H                  | [5b0da32c82](https://linux-hardware.org/?probe=5b0da32c82) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [ea22a308c9](https://linux-hardware.org/?probe=ea22a308c9) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [bd2f18b5a5](https://linux-hardware.org/?probe=bd2f18b5a5) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [159c1dcd33](https://linux-hardware.org/?probe=159c1dcd33) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | [e20b509508](https://linux-hardware.org/?probe=e20b509508) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [b9f43af7d0](https://linux-hardware.org/?probe=b9f43af7d0) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [9cab157472](https://linux-hardware.org/?probe=9cab157472) | Sep 03, 2022 |
| ASUSTek       | Z170-K                      | [d47c5fe35c](https://linux-hardware.org/?probe=d47c5fe35c) | Sep 03, 2022 |
| Gigabyte      | B450M DS3H-CF               | [5f37e7a618](https://linux-hardware.org/?probe=5f37e7a618) | Sep 03, 2022 |
| ASRock        | X470 Taichi                 | [0a6ff089f1](https://linux-hardware.org/?probe=0a6ff089f1) | Sep 03, 2022 |
| MSI           | X470 GAMING PRO MAX         | [7f10b8002b](https://linux-hardware.org/?probe=7f10b8002b) | Sep 03, 2022 |
| BESSTAR Te... | UM350                       | [02423b61e0](https://linux-hardware.org/?probe=02423b61e0) | Sep 03, 2022 |
| Foxconn       | 2ADA                        | [f1ca159a19](https://linux-hardware.org/?probe=f1ca159a19) | Sep 03, 2022 |
| Acer          | Aspire M3910                | [17c1079582](https://linux-hardware.org/?probe=17c1079582) | Sep 02, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [0a1de8a406](https://linux-hardware.org/?probe=0a1de8a406) | Sep 02, 2022 |
| Dell          | 0MWYPT A02                  | [e2f98387b0](https://linux-hardware.org/?probe=e2f98387b0) | Sep 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [2cf98644bc](https://linux-hardware.org/?probe=2cf98644bc) | Sep 01, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [c5547cac7c](https://linux-hardware.org/?probe=c5547cac7c) | Aug 31, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | [36eb80672f](https://linux-hardware.org/?probe=36eb80672f) | Aug 31, 2022 |
| Dell          | 0KV3RP A00                  | [731a14ee10](https://linux-hardware.org/?probe=731a14ee10) | Aug 31, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [2c72dfccbb](https://linux-hardware.org/?probe=2c72dfccbb) | Aug 30, 2022 |
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
| ASUSTek       | ROG STRIX B550-F GAMING     | [2388b95ce9](https://linux-hardware.org/?probe=2388b95ce9) | Aug 25, 2022 |
| ASUSTek       | UN62                        | [49fcd1324f](https://linux-hardware.org/?probe=49fcd1324f) | Aug 25, 2022 |
| ASRock        | B450M Pro4                  | [69fd53a234](https://linux-hardware.org/?probe=69fd53a234) | Aug 25, 2022 |
| ASRock        | B450M Pro4                  | [47dc749c6c](https://linux-hardware.org/?probe=47dc749c6c) | Aug 25, 2022 |
| Dell          | 01TKCC A01                  | [9a362ed844](https://linux-hardware.org/?probe=9a362ed844) | Aug 25, 2022 |
| Dell          | 0PU052                      | [2bffd37724](https://linux-hardware.org/?probe=2bffd37724) | Aug 24, 2022 |
| ASUSTek       | Z97-AR                      | [a766ce2d5a](https://linux-hardware.org/?probe=a766ce2d5a) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ae4a81a473](https://linux-hardware.org/?probe=ae4a81a473) | Aug 24, 2022 |
| ASRock        | X570M Pro4                  | [f2bc1e0fae](https://linux-hardware.org/?probe=f2bc1e0fae) | Aug 23, 2022 |
| Gigabyte      | H81M-S                      | [0b1e1d125d](https://linux-hardware.org/?probe=0b1e1d125d) | Aug 23, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [0796a8df9d](https://linux-hardware.org/?probe=0796a8df9d) | Aug 23, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [b0af95356c](https://linux-hardware.org/?probe=b0af95356c) | Aug 22, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bc32a93168](https://linux-hardware.org/?probe=bc32a93168) | Aug 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [a25c6f8d64](https://linux-hardware.org/?probe=a25c6f8d64) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | [2af48f00ac](https://linux-hardware.org/?probe=2af48f00ac) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | [0910ca3887](https://linux-hardware.org/?probe=0910ca3887) | Aug 22, 2022 |
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
| ASUSTek       | Z97-C                       | [58f88a4494](https://linux-hardware.org/?probe=58f88a4494) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | [e68748c0f1](https://linux-hardware.org/?probe=e68748c0f1) | Aug 16, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [8b591b08b0](https://linux-hardware.org/?probe=8b591b08b0) | Aug 16, 2022 |
| ASUSTek       | Z97-C                       | [e68b5affa4](https://linux-hardware.org/?probe=e68b5affa4) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [97ff4c0078](https://linux-hardware.org/?probe=97ff4c0078) | Aug 16, 2022 |
| Gigabyte      | B550M DS3H                  | [6ef5e022c7](https://linux-hardware.org/?probe=6ef5e022c7) | Aug 15, 2022 |
| ECS           | H61H2-MV                    | [0b95f78b15](https://linux-hardware.org/?probe=0b95f78b15) | Aug 15, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [8072e15459](https://linux-hardware.org/?probe=8072e15459) | Aug 15, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [bbbda98d21](https://linux-hardware.org/?probe=bbbda98d21) | Aug 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [20d9ba44b5](https://linux-hardware.org/?probe=20d9ba44b5) | Aug 15, 2022 |
| ASUSTek       | B85M-G                      | [b44e802677](https://linux-hardware.org/?probe=b44e802677) | Aug 14, 2022 |
| ASUSTek       | P8H77-V                     | [83abda5bc9](https://linux-hardware.org/?probe=83abda5bc9) | Aug 14, 2022 |
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
| ASRock        | B450M Steel Legend          | [a24161deaa](https://linux-hardware.org/?probe=a24161deaa) | Aug 10, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [d586bdd82d](https://linux-hardware.org/?probe=d586bdd82d) | Aug 10, 2022 |
| Gigabyte      | X570 AORUS PRO              | [8558001fa2](https://linux-hardware.org/?probe=8558001fa2) | Aug 09, 2022 |
| Gigabyte      | Z87-HD3                     | [ee1bdd9333](https://linux-hardware.org/?probe=ee1bdd9333) | Aug 09, 2022 |
| Gigabyte      | Z87-HD3                     | [a0243ce6f0](https://linux-hardware.org/?probe=a0243ce6f0) | Aug 09, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [e74a95c4d9](https://linux-hardware.org/?probe=e74a95c4d9) | Aug 09, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [42d32cdfda](https://linux-hardware.org/?probe=42d32cdfda) | Aug 09, 2022 |
| MSI           | Z87-G45 GAMING              | [093a936372](https://linux-hardware.org/?probe=093a936372) | Aug 08, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [b421a8c6c4](https://linux-hardware.org/?probe=b421a8c6c4) | Aug 08, 2022 |
| ASUSTek       | P8H67-M LE                  | [07c89bcbc6](https://linux-hardware.org/?probe=07c89bcbc6) | Aug 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [08b891334e](https://linux-hardware.org/?probe=08b891334e) | Aug 08, 2022 |
| Lenovo        | SHARKBAY NOK                | [f08a60d37c](https://linux-hardware.org/?probe=f08a60d37c) | Aug 07, 2022 |
| ASUSTek       | PRIME B550M-A               | [64e8ddf1c9](https://linux-hardware.org/?probe=64e8ddf1c9) | Aug 07, 2022 |
| ECS           | H61H2-MV                    | [7dbc1a26ca](https://linux-hardware.org/?probe=7dbc1a26ca) | Aug 07, 2022 |
| MSI           | MAG B460M MORTAR            | [a823925843](https://linux-hardware.org/?probe=a823925843) | Aug 07, 2022 |
| HP            | 1587h                       | [d9d1b6832f](https://linux-hardware.org/?probe=d9d1b6832f) | Aug 07, 2022 |
| HP            | 1587h                       | [737b509512](https://linux-hardware.org/?probe=737b509512) | Aug 07, 2022 |
| Gigabyte      | A320M-S2H-CF                | [31c87abaf3](https://linux-hardware.org/?probe=31c87abaf3) | Aug 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [154440549c](https://linux-hardware.org/?probe=154440549c) | Aug 06, 2022 |
| ECS           | H61H2-MV                    | [6dbb0a4eb9](https://linux-hardware.org/?probe=6dbb0a4eb9) | Aug 06, 2022 |
| ASUSTek       | SABERTOOTH X79              | [4f10e80880](https://linux-hardware.org/?probe=4f10e80880) | Aug 06, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [4f12a5e11e](https://linux-hardware.org/?probe=4f12a5e11e) | Aug 06, 2022 |
| BESSTAR Te... | HM90                        | [36e148426c](https://linux-hardware.org/?probe=36e148426c) | Aug 06, 2022 |
| BESSTAR Te... | HM90                        | [28ec23aa22](https://linux-hardware.org/?probe=28ec23aa22) | Aug 06, 2022 |
| Gigabyte      | 945GCM-S2L                  | [fd6cf872ae](https://linux-hardware.org/?probe=fd6cf872ae) | Aug 06, 2022 |
| ASRock        | B460M Pro4S/ac              | [79f01ebf66](https://linux-hardware.org/?probe=79f01ebf66) | Aug 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [1798c25088](https://linux-hardware.org/?probe=1798c25088) | Aug 05, 2022 |
| Gigabyte      | H77N-WIFI                   | [caa404d4c6](https://linux-hardware.org/?probe=caa404d4c6) | Aug 05, 2022 |
| Gigabyte      | AX370-Gaming 5              | [46f109ed37](https://linux-hardware.org/?probe=46f109ed37) | Aug 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [c6e5356615](https://linux-hardware.org/?probe=c6e5356615) | Aug 04, 2022 |
| Gigabyte      | M68MT-S2P                   | [7c41cd3006](https://linux-hardware.org/?probe=7c41cd3006) | Aug 04, 2022 |
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
| Gigabyte      | B550I AORUS PRO AX          | [37b8171416](https://linux-hardware.org/?probe=37b8171416) | Aug 01, 2022 |
| MSI           | H81M-E34                    | [c0be356e96](https://linux-hardware.org/?probe=c0be356e96) | Aug 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [dcccfd1beb](https://linux-hardware.org/?probe=dcccfd1beb) | Aug 01, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [4956d72048](https://linux-hardware.org/?probe=4956d72048) | Aug 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [163affcbb8](https://linux-hardware.org/?probe=163affcbb8) | Aug 01, 2022 |
| ASUSTek       | M2N-MX SE Plus              | [7a0035ad18](https://linux-hardware.org/?probe=7a0035ad18) | Jul 31, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [f6a106d6df](https://linux-hardware.org/?probe=f6a106d6df) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | [d8bfe4a00b](https://linux-hardware.org/?probe=d8bfe4a00b) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0f72d43717](https://linux-hardware.org/?probe=0f72d43717) | Jul 31, 2022 |
| ASRock        | X570 Steel Legend           | [f43e0c2c81](https://linux-hardware.org/?probe=f43e0c2c81) | Jul 31, 2022 |
| ASUSTek       | M4A77TD                     | [f10ef09086](https://linux-hardware.org/?probe=f10ef09086) | Jul 30, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [9258c864d5](https://linux-hardware.org/?probe=9258c864d5) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3b661517b1](https://linux-hardware.org/?probe=3b661517b1) | Jul 29, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [efa02942f2](https://linux-hardware.org/?probe=efa02942f2) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [25d688e258](https://linux-hardware.org/?probe=25d688e258) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [93caf82d7a](https://linux-hardware.org/?probe=93caf82d7a) | Jul 29, 2022 |
| Pegatron      | IPM41-D3                    | [ce24b0bab7](https://linux-hardware.org/?probe=ce24b0bab7) | Jul 28, 2022 |
| ASUSTek       | WS Z390 PRO                 | [256172b01e](https://linux-hardware.org/?probe=256172b01e) | Jul 28, 2022 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | [757ba0f252](https://linux-hardware.org/?probe=757ba0f252) | Jul 28, 2022 |
| ASRock        | B450M Pro4-F                | [af4d396115](https://linux-hardware.org/?probe=af4d396115) | Jul 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [32e82dc9ae](https://linux-hardware.org/?probe=32e82dc9ae) | Jul 27, 2022 |
| HP            | 1494                        | [6805afe809](https://linux-hardware.org/?probe=6805afe809) | Jul 27, 2022 |
| MSI           | B450M PRO-VDH MAX           | [d63a6f2607](https://linux-hardware.org/?probe=d63a6f2607) | Jul 26, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [a0e19ce405](https://linux-hardware.org/?probe=a0e19ce405) | Jul 26, 2022 |
| ASRock        | Z690 PG Riptide             | [87c499b088](https://linux-hardware.org/?probe=87c499b088) | Jul 26, 2022 |
| MSI           | B150M PRO-VD                | [8194e1dc19](https://linux-hardware.org/?probe=8194e1dc19) | Jul 26, 2022 |
| ASRock        | B450M Steel Legend          | [30fd52a2a5](https://linux-hardware.org/?probe=30fd52a2a5) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [3a34e9c018](https://linux-hardware.org/?probe=3a34e9c018) | Jul 25, 2022 |
| ASUSTek       | H81M-K                      | [a3eeaecb07](https://linux-hardware.org/?probe=a3eeaecb07) | Jul 25, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [24fec424ff](https://linux-hardware.org/?probe=24fec424ff) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f00c831f5b](https://linux-hardware.org/?probe=f00c831f5b) | Jul 25, 2022 |
| MSI           | B365M PRO-VH                | [f254ee30b7](https://linux-hardware.org/?probe=f254ee30b7) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | [58f727d948](https://linux-hardware.org/?probe=58f727d948) | Jul 25, 2022 |
| Dell          | 0DF42J A00                  | [6a75ac249a](https://linux-hardware.org/?probe=6a75ac249a) | Jul 24, 2022 |
| ASUSTek       | Z170-P                      | [85e3fee140](https://linux-hardware.org/?probe=85e3fee140) | Jul 24, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [793c3d4e22](https://linux-hardware.org/?probe=793c3d4e22) | Jul 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [2ae14bcbc1](https://linux-hardware.org/?probe=2ae14bcbc1) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [9c0899916c](https://linux-hardware.org/?probe=9c0899916c) | Jul 23, 2022 |
| ASUSTek       | SABERTOOTH X79              | [88c35211e1](https://linux-hardware.org/?probe=88c35211e1) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [6889befce9](https://linux-hardware.org/?probe=6889befce9) | Jul 23, 2022 |
| MSI           | PRO Z690-A                  | [9264d3b652](https://linux-hardware.org/?probe=9264d3b652) | Jul 22, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [edcecb5e13](https://linux-hardware.org/?probe=edcecb5e13) | Jul 22, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [f90d74f5b5](https://linux-hardware.org/?probe=f90d74f5b5) | Jul 22, 2022 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | [cda18f8739](https://linux-hardware.org/?probe=cda18f8739) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6e4f170da9](https://linux-hardware.org/?probe=6e4f170da9) | Jul 22, 2022 |
| ASUSTek       | P7H55-M                     | [d7ba204d31](https://linux-hardware.org/?probe=d7ba204d31) | Jul 22, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [d57e35934f](https://linux-hardware.org/?probe=d57e35934f) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [41dbccf7d9](https://linux-hardware.org/?probe=41dbccf7d9) | Jul 21, 2022 |
| Dell          | 0WMJ54 A01                  | [dace7a0b12](https://linux-hardware.org/?probe=dace7a0b12) | Jul 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | [9c98b2fcd6](https://linux-hardware.org/?probe=9c98b2fcd6) | Jul 21, 2022 |
| ASRock        | H81M-HG4 R4.0               | [4628e310fd](https://linux-hardware.org/?probe=4628e310fd) | Jul 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f42ed5053a](https://linux-hardware.org/?probe=f42ed5053a) | Jul 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6e4fbc6688](https://linux-hardware.org/?probe=6e4fbc6688) | Jul 20, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c763e49e7e](https://linux-hardware.org/?probe=c763e49e7e) | Jul 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a04d18d87a](https://linux-hardware.org/?probe=a04d18d87a) | Jul 20, 2022 |
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
| ASUSTek       | ROG STRIX Z490-I GAMING     | [34a905d705](https://linux-hardware.org/?probe=34a905d705) | Jul 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [fc316a6331](https://linux-hardware.org/?probe=fc316a6331) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [86ac444b35](https://linux-hardware.org/?probe=86ac444b35) | Jul 15, 2022 |
| HP            | 88BF                        | [92b12df551](https://linux-hardware.org/?probe=92b12df551) | Jul 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [1338941bd0](https://linux-hardware.org/?probe=1338941bd0) | Jul 15, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [7efe67fd9a](https://linux-hardware.org/?probe=7efe67fd9a) | Jul 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [f655a34cc1](https://linux-hardware.org/?probe=f655a34cc1) | Jul 15, 2022 |
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
| MSI           | Z370-OC PRO                 | [2c9d1d78df](https://linux-hardware.org/?probe=2c9d1d78df) | Jul 12, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [c69dd8da85](https://linux-hardware.org/?probe=c69dd8da85) | Jul 12, 2022 |
| MSI           | H97M-G43                    | [c8b2844540](https://linux-hardware.org/?probe=c8b2844540) | Jul 11, 2022 |
| HP            | 3646h                       | [88b38da161](https://linux-hardware.org/?probe=88b38da161) | Jul 11, 2022 |
| Dell          | 02YYK5 A00                  | [6592ae8873](https://linux-hardware.org/?probe=6592ae8873) | Jul 11, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [05b0102f01](https://linux-hardware.org/?probe=05b0102f01) | Jul 11, 2022 |
| Dell          | 0XCR8D A03                  | [b6771bbe08](https://linux-hardware.org/?probe=b6771bbe08) | Jul 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [8739a403bc](https://linux-hardware.org/?probe=8739a403bc) | Jul 11, 2022 |
| Dell          | 09WH54 A00                  | [8570e35470](https://linux-hardware.org/?probe=8570e35470) | Jul 11, 2022 |
| ASUSTek       | PRIME X470-PRO              | [314c3aaf0e](https://linux-hardware.org/?probe=314c3aaf0e) | Jul 10, 2022 |
| ASUSTek       | PRIME X470-PRO              | [d6f1e47bf5](https://linux-hardware.org/?probe=d6f1e47bf5) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | [cf71ced9a0](https://linux-hardware.org/?probe=cf71ced9a0) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | [cf470317b1](https://linux-hardware.org/?probe=cf470317b1) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [45e46ac933](https://linux-hardware.org/?probe=45e46ac933) | Jul 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [cdf7b9a4d1](https://linux-hardware.org/?probe=cdf7b9a4d1) | Jul 10, 2022 |
| Intel         | DH61WW AAG23116-301         | [3b4120b3af](https://linux-hardware.org/?probe=3b4120b3af) | Jul 09, 2022 |
| MSI           | PRO B660M-A DDR4            | [65c661af95](https://linux-hardware.org/?probe=65c661af95) | Jul 09, 2022 |
| ZOTAC         | Unknown                     | [70105d0f43](https://linux-hardware.org/?probe=70105d0f43) | Jul 09, 2022 |
| ASRock        | Z170 Extreme4               | [34f14d654f](https://linux-hardware.org/?probe=34f14d654f) | Jul 09, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [6513be6d44](https://linux-hardware.org/?probe=6513be6d44) | Jul 09, 2022 |
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
| MSI           | MEG X570 UNIFY              | [f1de99a0da](https://linux-hardware.org/?probe=f1de99a0da) | Jul 04, 2022 |
| MSI           | MS-B0A1                     | [9b53e39bad](https://linux-hardware.org/?probe=9b53e39bad) | Jul 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [729fab1a51](https://linux-hardware.org/?probe=729fab1a51) | Jul 04, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [58b8e08cf9](https://linux-hardware.org/?probe=58b8e08cf9) | Jul 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | [7f4faab065](https://linux-hardware.org/?probe=7f4faab065) | Jul 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | [24d32e73bd](https://linux-hardware.org/?probe=24d32e73bd) | Jul 03, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [963029db26](https://linux-hardware.org/?probe=963029db26) | Jul 02, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [2d22d14874](https://linux-hardware.org/?probe=2d22d14874) | Jul 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8e6d23cf01](https://linux-hardware.org/?probe=8e6d23cf01) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | [a32cb9b3f1](https://linux-hardware.org/?probe=a32cb9b3f1) | Jul 01, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | [febb798e92](https://linux-hardware.org/?probe=febb798e92) | Jul 01, 2022 |
| Dell          | 0M9KCM A00                  | [e72232ee43](https://linux-hardware.org/?probe=e72232ee43) | Jul 01, 2022 |
| Gigabyte      | Z87-HD3                     | [c38c4e9cb9](https://linux-hardware.org/?probe=c38c4e9cb9) | Jun 30, 2022 |
| Dell          | 0M9KCM A00                  | [5e80242b43](https://linux-hardware.org/?probe=5e80242b43) | Jun 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7e14880c80](https://linux-hardware.org/?probe=7e14880c80) | Jun 30, 2022 |
| ASUSTek       | PRIME Z370-A                | [28479b3edf](https://linux-hardware.org/?probe=28479b3edf) | Jun 30, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [cea6c9ea52](https://linux-hardware.org/?probe=cea6c9ea52) | Jun 30, 2022 |
| Gigabyte      | B560M DS3H V2               | [85b8793585](https://linux-hardware.org/?probe=85b8793585) | Jun 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [01d9100427](https://linux-hardware.org/?probe=01d9100427) | Jun 29, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [392d5c7c12](https://linux-hardware.org/?probe=392d5c7c12) | Jun 29, 2022 |
| Gigabyte      | D525TUD                     | [b6cfc5d2df](https://linux-hardware.org/?probe=b6cfc5d2df) | Jun 28, 2022 |
| Gigabyte      | B85M-D3V-A                  | [3417dd6a9a](https://linux-hardware.org/?probe=3417dd6a9a) | Jun 28, 2022 |
| Gigabyte      | G41MT-D3                    | [20de16a046](https://linux-hardware.org/?probe=20de16a046) | Jun 28, 2022 |
| ASRock        | N68-VS3 UCC                 | [2c7959c607](https://linux-hardware.org/?probe=2c7959c607) | Jun 26, 2022 |
| ASUSTek       | PRIME H410M-E               | [3eb97735b3](https://linux-hardware.org/?probe=3eb97735b3) | Jun 26, 2022 |
| HP            | 3398                        | [4241fd0ba0](https://linux-hardware.org/?probe=4241fd0ba0) | Jun 26, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [9a853085ea](https://linux-hardware.org/?probe=9a853085ea) | Jun 26, 2022 |
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
| MSI           | MPG B550 GAMING EDGE WIF... | [f3176204c8](https://linux-hardware.org/?probe=f3176204c8) | Jun 21, 2022 |
| MSI           | B450-A PRO MAX              | [490076a383](https://linux-hardware.org/?probe=490076a383) | Jun 20, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [b7a6099e25](https://linux-hardware.org/?probe=b7a6099e25) | Jun 20, 2022 |
| MSI           | MS-B0A1                     | [3193cbe3fd](https://linux-hardware.org/?probe=3193cbe3fd) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [a384703b5e](https://linux-hardware.org/?probe=a384703b5e) | Jun 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [560fa88cad](https://linux-hardware.org/?probe=560fa88cad) | Jun 19, 2022 |
| HP            | 2B05                        | [a49ebb4aed](https://linux-hardware.org/?probe=a49ebb4aed) | Jun 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [4fc1134f6d](https://linux-hardware.org/?probe=4fc1134f6d) | Jun 19, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [a59676f7be](https://linux-hardware.org/?probe=a59676f7be) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [707f314c74](https://linux-hardware.org/?probe=707f314c74) | Jun 19, 2022 |
| MSI           | H510I PRO WIFI              | [b9d3cb4755](https://linux-hardware.org/?probe=b9d3cb4755) | Jun 18, 2022 |
| ASUSTek       | Q170M2                      | [76f5dd0027](https://linux-hardware.org/?probe=76f5dd0027) | Jun 18, 2022 |
| ASUSTek       | Q170M2                      | [32713d6759](https://linux-hardware.org/?probe=32713d6759) | Jun 18, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | [292cc4bcab](https://linux-hardware.org/?probe=292cc4bcab) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [f54dda344d](https://linux-hardware.org/?probe=f54dda344d) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [6647ddd346](https://linux-hardware.org/?probe=6647ddd346) | Jun 17, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [dfed0867e1](https://linux-hardware.org/?probe=dfed0867e1) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | [7205fff536](https://linux-hardware.org/?probe=7205fff536) | Jun 17, 2022 |
| MSI           | MAG B460M MORTAR            | [9074247e52](https://linux-hardware.org/?probe=9074247e52) | Jun 17, 2022 |
| Dell          | 0XC7MM A01                  | [8c8a1ef522](https://linux-hardware.org/?probe=8c8a1ef522) | Jun 16, 2022 |
| Gigabyte      | H87N-WIFI                   | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| ASUSTek       | PRIME B550M-A               | [527aea0d6e](https://linux-hardware.org/?probe=527aea0d6e) | Jun 16, 2022 |
| ASRock        | B550M-ITX/ac                | [42fd0dcad9](https://linux-hardware.org/?probe=42fd0dcad9) | Jun 16, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [08527d664b](https://linux-hardware.org/?probe=08527d664b) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [8d106f8677](https://linux-hardware.org/?probe=8d106f8677) | Jun 16, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [701de0d7ad](https://linux-hardware.org/?probe=701de0d7ad) | Jun 15, 2022 |
| ASRock        | B450M Pro4                  | [041f94473b](https://linux-hardware.org/?probe=041f94473b) | Jun 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [131a938c5e](https://linux-hardware.org/?probe=131a938c5e) | Jun 14, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [e61344b416](https://linux-hardware.org/?probe=e61344b416) | Jun 14, 2022 |
| Gigabyte      | H61M-S2PV                   | [cc88cec642](https://linux-hardware.org/?probe=cc88cec642) | Jun 14, 2022 |
| ASUSTek       | PRIME Z370-A                | [1bb2aa2c68](https://linux-hardware.org/?probe=1bb2aa2c68) | Jun 14, 2022 |
| Dell          | 00V62H A00                  | [dc89caf09f](https://linux-hardware.org/?probe=dc89caf09f) | Jun 13, 2022 |
| Gigabyte      | B560M DS3H V2               | [61d456c166](https://linux-hardware.org/?probe=61d456c166) | Jun 13, 2022 |
| ASUSTek       | H87-PLUS                    | [1c5488bdf7](https://linux-hardware.org/?probe=1c5488bdf7) | Jun 13, 2022 |
| ASUSTek       | H87-PLUS                    | [fd8af28ed5](https://linux-hardware.org/?probe=fd8af28ed5) | Jun 13, 2022 |
| HP            | 18E5                        | [275b8ca77c](https://linux-hardware.org/?probe=275b8ca77c) | Jun 12, 2022 |
| ASUSTek       | P5K Premium                 | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [0c0715a9b2](https://linux-hardware.org/?probe=0c0715a9b2) | Jun 12, 2022 |
| Gigabyte      | B75-D3V                     | [f0fe22dfe7](https://linux-hardware.org/?probe=f0fe22dfe7) | Jun 12, 2022 |
| ASUSTek       | P5G41T-M                    | [0fd96bfcf3](https://linux-hardware.org/?probe=0fd96bfcf3) | Jun 12, 2022 |
| MSI           | B450M MORTAR                | [18240b9552](https://linux-hardware.org/?probe=18240b9552) | Jun 11, 2022 |
| Gigabyte      | GA-MA69GM-S2H               | [a382b54934](https://linux-hardware.org/?probe=a382b54934) | Jun 11, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [661f4f701b](https://linux-hardware.org/?probe=661f4f701b) | Jun 10, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [b771c75e31](https://linux-hardware.org/?probe=b771c75e31) | Jun 10, 2022 |
| ASUSTek       | PRIME B360M-A               | [272c6283d4](https://linux-hardware.org/?probe=272c6283d4) | Jun 10, 2022 |
| Gigabyte      | H55M-S2                     | [86b61f1ef6](https://linux-hardware.org/?probe=86b61f1ef6) | Jun 10, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | [4458c8a8ca](https://linux-hardware.org/?probe=4458c8a8ca) | Jun 09, 2022 |
| Intel         | X79 V2.4E                   | [12a530acde](https://linux-hardware.org/?probe=12a530acde) | Jun 09, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [35b29ccf1d](https://linux-hardware.org/?probe=35b29ccf1d) | Jun 08, 2022 |
| Gigabyte      | A520M DS3H                  | [e12c11bc94](https://linux-hardware.org/?probe=e12c11bc94) | Jun 08, 2022 |
| Gigabyte      | H410M S2H V3                | [feaff6859d](https://linux-hardware.org/?probe=feaff6859d) | Jun 07, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c446ea33eb](https://linux-hardware.org/?probe=c446ea33eb) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [f23f59523b](https://linux-hardware.org/?probe=f23f59523b) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [2e5071518f](https://linux-hardware.org/?probe=2e5071518f) | Jun 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [9fe17edc24](https://linux-hardware.org/?probe=9fe17edc24) | Jun 06, 2022 |
| ASUSTek       | P8H67-M LE                  | [d1409ca910](https://linux-hardware.org/?probe=d1409ca910) | Jun 06, 2022 |
| Dell          | 0XC7MM A01                  | [ed376c819b](https://linux-hardware.org/?probe=ed376c819b) | Jun 06, 2022 |
| Dell          | 08K0X7 A00                  | [28a29e32c6](https://linux-hardware.org/?probe=28a29e32c6) | Jun 06, 2022 |
| Dell          | 06JWJY A00                  | [577bbe62e1](https://linux-hardware.org/?probe=577bbe62e1) | Jun 06, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [8b87017c24](https://linux-hardware.org/?probe=8b87017c24) | Jun 05, 2022 |
| Gigabyte      | B460M DS3H V2               | [afb7427d61](https://linux-hardware.org/?probe=afb7427d61) | Jun 05, 2022 |
| Foxconn       | H81MXV FAB A                | [1f880ea008](https://linux-hardware.org/?probe=1f880ea008) | Jun 05, 2022 |
| Gigabyte      | B75M-HD3                    | [63a565a5e1](https://linux-hardware.org/?probe=63a565a5e1) | Jun 05, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [feec15b490](https://linux-hardware.org/?probe=feec15b490) | Jun 04, 2022 |
| Positivo      | POS-PIH55BO                 | [cffe8043b8](https://linux-hardware.org/?probe=cffe8043b8) | Jun 04, 2022 |
| ASUSTek       | PRIME B450M-A               | [1813b3a9a5](https://linux-hardware.org/?probe=1813b3a9a5) | Jun 04, 2022 |
| ASUSTek       | CROSSHAIR                   | [11834759e2](https://linux-hardware.org/?probe=11834759e2) | Jun 04, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2e9cc784ac](https://linux-hardware.org/?probe=2e9cc784ac) | Jun 03, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [68a1616b4a](https://linux-hardware.org/?probe=68a1616b4a) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [909d9cb8d5](https://linux-hardware.org/?probe=909d9cb8d5) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9829bd8f60](https://linux-hardware.org/?probe=9829bd8f60) | Jun 03, 2022 |
| MSI           | B560M PRO-VDH               | [2e9996424a](https://linux-hardware.org/?probe=2e9996424a) | Jun 02, 2022 |
| ASRock        | H81M-HG4 R4.0               | [2a09c108e5](https://linux-hardware.org/?probe=2a09c108e5) | Jun 02, 2022 |
| Gigabyte      | B85M-D3V-A                  | [88d5e21b42](https://linux-hardware.org/?probe=88d5e21b42) | Jun 01, 2022 |
| ASUSTek       | Maximus VII IMPACT          | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [0d91ffc3e9](https://linux-hardware.org/?probe=0d91ffc3e9) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [6190087942](https://linux-hardware.org/?probe=6190087942) | Jun 01, 2022 |
| ASUSTek       | PRIME B560M-A               | [b68bcf6b84](https://linux-hardware.org/?probe=b68bcf6b84) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [53dbc2fe14](https://linux-hardware.org/?probe=53dbc2fe14) | May 31, 2022 |
| MSI           | B450M PRO-VDH MAX           | [ece9950c65](https://linux-hardware.org/?probe=ece9950c65) | May 31, 2022 |
| MSI           | B450M PRO-VDH MAX           | [07a1bcfa9e](https://linux-hardware.org/?probe=07a1bcfa9e) | May 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7b27373492](https://linux-hardware.org/?probe=7b27373492) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | [386a88c2b6](https://linux-hardware.org/?probe=386a88c2b6) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | [5a51cc8767](https://linux-hardware.org/?probe=5a51cc8767) | May 30, 2022 |
| Dell          | 0R6PCT A01                  | [23c83c37e6](https://linux-hardware.org/?probe=23c83c37e6) | May 29, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [33a2de91a2](https://linux-hardware.org/?probe=33a2de91a2) | May 29, 2022 |
| ASUSTek       | H81M-A                      | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [8409764263](https://linux-hardware.org/?probe=8409764263) | May 27, 2022 |
| BESSTAR Te... | UM700                       | [f754f78f66](https://linux-hardware.org/?probe=f754f78f66) | May 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [c01e0f9ac4](https://linux-hardware.org/?probe=c01e0f9ac4) | May 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [06e3526c59](https://linux-hardware.org/?probe=06e3526c59) | May 25, 2022 |
| ASRock        | X99 Taichi                  | [18ec1a6a1a](https://linux-hardware.org/?probe=18ec1a6a1a) | May 25, 2022 |
| ASUSTek       | KCMA-D8                     | [2d8bea4f55](https://linux-hardware.org/?probe=2d8bea4f55) | May 24, 2022 |
| Dell          | 0PU052                      | [4e3e3cc0fd](https://linux-hardware.org/?probe=4e3e3cc0fd) | May 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [282c849b82](https://linux-hardware.org/?probe=282c849b82) | May 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [da5f6c9ba0](https://linux-hardware.org/?probe=da5f6c9ba0) | May 23, 2022 |
| MSI           | Z77A-G43                    | [7d35f08c28](https://linux-hardware.org/?probe=7d35f08c28) | May 23, 2022 |
| ASUSTek       | PRIME Z270-P                | [afb47f4860](https://linux-hardware.org/?probe=afb47f4860) | May 23, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [2034bf506d](https://linux-hardware.org/?probe=2034bf506d) | May 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2bd8d64c3b](https://linux-hardware.org/?probe=2bd8d64c3b) | May 22, 2022 |
| ASUSTek       | P8P67-M                     | [83917315b7](https://linux-hardware.org/?probe=83917315b7) | May 22, 2022 |
| Gigabyte      | B550 GAMING X V2            | [a84132c514](https://linux-hardware.org/?probe=a84132c514) | May 22, 2022 |
| ASRock        | AB350 Pro4                  | [49223fe44b](https://linux-hardware.org/?probe=49223fe44b) | May 21, 2022 |
| ASRock        | AB350 Pro4                  | [40cb336486](https://linux-hardware.org/?probe=40cb336486) | May 21, 2022 |
| MSI           | B450M-A PRO MAX             | [fce678a9e8](https://linux-hardware.org/?probe=fce678a9e8) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [01e2d063e8](https://linux-hardware.org/?probe=01e2d063e8) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [f3986d7e7d](https://linux-hardware.org/?probe=f3986d7e7d) | May 21, 2022 |
| MSI           | B450M PRO-M2 MAX            | [1984313b19](https://linux-hardware.org/?probe=1984313b19) | May 20, 2022 |
| ASRock        | Z390 Taichi Ultimate        | [68d0cdd597](https://linux-hardware.org/?probe=68d0cdd597) | May 19, 2022 |
| HP            | 82A2                        | [56d6c8d749](https://linux-hardware.org/?probe=56d6c8d749) | May 19, 2022 |
| HP            | 82A2                        | [6e0efeba1d](https://linux-hardware.org/?probe=6e0efeba1d) | May 19, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [4a971be254](https://linux-hardware.org/?probe=4a971be254) | May 19, 2022 |
| Intel         | DH77EB AAG39073-304         | [dc2f9f56a5](https://linux-hardware.org/?probe=dc2f9f56a5) | May 18, 2022 |
| HP            | 8767 A                      | [0f564fe004](https://linux-hardware.org/?probe=0f564fe004) | May 18, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9c3b90c60d](https://linux-hardware.org/?probe=9c3b90c60d) | May 18, 2022 |
| ASRock        | 970M Pro3                   | [d39e962536](https://linux-hardware.org/?probe=d39e962536) | May 18, 2022 |
| ASUSTek       | P8Z68-V PRO GEN3            | [8a6fc346c5](https://linux-hardware.org/?probe=8a6fc346c5) | May 18, 2022 |
| Dell          | 0DF42J A00                  | [ac9f539524](https://linux-hardware.org/?probe=ac9f539524) | May 18, 2022 |
| HP            | 8767 A                      | [caad4001f1](https://linux-hardware.org/?probe=caad4001f1) | May 18, 2022 |
| ASRock        | 970M Pro3                   | [6f48a71a87](https://linux-hardware.org/?probe=6f48a71a87) | May 17, 2022 |
| ASUSTek       | P8H67-M LE                  | [ef70fd2699](https://linux-hardware.org/?probe=ef70fd2699) | May 17, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d831b6cb22](https://linux-hardware.org/?probe=d831b6cb22) | May 17, 2022 |
| Dell          | 0NKW6Y A02                  | [ffee0745b6](https://linux-hardware.org/?probe=ffee0745b6) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | [21b3b45491](https://linux-hardware.org/?probe=21b3b45491) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | [81e0a19eaa](https://linux-hardware.org/?probe=81e0a19eaa) | May 16, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d1dbcd7651](https://linux-hardware.org/?probe=d1dbcd7651) | May 16, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [efe02f8593](https://linux-hardware.org/?probe=efe02f8593) | May 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2f12c77058](https://linux-hardware.org/?probe=2f12c77058) | May 16, 2022 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [fa17134027](https://linux-hardware.org/?probe=fa17134027) | May 16, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [26f332bc9c](https://linux-hardware.org/?probe=26f332bc9c) | May 16, 2022 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [16bd9d3c6d](https://linux-hardware.org/?probe=16bd9d3c6d) | May 16, 2022 |
| Intel         | DH77EB AAG39073-304         | [22f5a0269f](https://linux-hardware.org/?probe=22f5a0269f) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | [8b8bd9dead](https://linux-hardware.org/?probe=8b8bd9dead) | May 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [12d277d32c](https://linux-hardware.org/?probe=12d277d32c) | May 15, 2022 |
| ASRock        | 880GMH/U3S3                 | [57c85dd37a](https://linux-hardware.org/?probe=57c85dd37a) | May 15, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [ec0ec5ea27](https://linux-hardware.org/?probe=ec0ec5ea27) | May 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [a2ae5d95dd](https://linux-hardware.org/?probe=a2ae5d95dd) | May 15, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [6fc56522d6](https://linux-hardware.org/?probe=6fc56522d6) | May 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [1bde2ca3e7](https://linux-hardware.org/?probe=1bde2ca3e7) | May 14, 2022 |
| ASUSTek       | P8Z77-V LK                  | [70809098f6](https://linux-hardware.org/?probe=70809098f6) | May 14, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [3112931a28](https://linux-hardware.org/?probe=3112931a28) | May 14, 2022 |
| ASRock        | B560M-C                     | [b4946d836b](https://linux-hardware.org/?probe=b4946d836b) | May 13, 2022 |
| ASRock        | B560M-C                     | [16360de6cd](https://linux-hardware.org/?probe=16360de6cd) | May 13, 2022 |
| Gigabyte      | GA-K8NF-9                   | [f9d59e3770](https://linux-hardware.org/?probe=f9d59e3770) | May 13, 2022 |
| ASRock        | X570M Pro4                  | [fca86a854a](https://linux-hardware.org/?probe=fca86a854a) | May 13, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [ec4bd74f0b](https://linux-hardware.org/?probe=ec4bd74f0b) | May 13, 2022 |
| Gigabyte      | B85M-D3V-A                  | [46481247b1](https://linux-hardware.org/?probe=46481247b1) | May 12, 2022 |
| Acer          | Aspire M3985                | [e650ae1a26](https://linux-hardware.org/?probe=e650ae1a26) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [927afa0c20](https://linux-hardware.org/?probe=927afa0c20) | May 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c703872774](https://linux-hardware.org/?probe=c703872774) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [b9766a94d7](https://linux-hardware.org/?probe=b9766a94d7) | May 11, 2022 |
| ASRock        | X470 Taichi                 | [9ead3d53b0](https://linux-hardware.org/?probe=9ead3d53b0) | May 11, 2022 |
| MSI           | X470 GAMING PLUS            | [565dfeea66](https://linux-hardware.org/?probe=565dfeea66) | May 11, 2022 |
| Gigabyte      | Q35M-S2                     | [784ac96428](https://linux-hardware.org/?probe=784ac96428) | May 11, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [173fac4f5b](https://linux-hardware.org/?probe=173fac4f5b) | May 11, 2022 |
| ASRock        | 880GMH/U3S3                 | [73e6cb3b6b](https://linux-hardware.org/?probe=73e6cb3b6b) | May 10, 2022 |
| ASRock        | X470 Taichi                 | [fb1d5703eb](https://linux-hardware.org/?probe=fb1d5703eb) | May 10, 2022 |
| MSI           | H110M PRO-VD                | [f43f2e2bee](https://linux-hardware.org/?probe=f43f2e2bee) | May 10, 2022 |
| MSI           | H110M PRO-VD                | [3d0c46dc84](https://linux-hardware.org/?probe=3d0c46dc84) | May 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [d7e92b0ac7](https://linux-hardware.org/?probe=d7e92b0ac7) | May 09, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [fbe61c70ff](https://linux-hardware.org/?probe=fbe61c70ff) | May 09, 2022 |
| Gigabyte      | EP45-DS3L                   | [76e67361ea](https://linux-hardware.org/?probe=76e67361ea) | May 08, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [d24bbea844](https://linux-hardware.org/?probe=d24bbea844) | May 08, 2022 |
| ASUSTek       | PRIME X570-PRO              | [f12944a9bd](https://linux-hardware.org/?probe=f12944a9bd) | May 07, 2022 |
| ASUSTek       | PRIME X470-PRO              | [be200c9e57](https://linux-hardware.org/?probe=be200c9e57) | May 06, 2022 |
| Huanan        | X99-BD4 V1.1, NALEX         | [e69b3ef962](https://linux-hardware.org/?probe=e69b3ef962) | May 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [52d956751f](https://linux-hardware.org/?probe=52d956751f) | May 06, 2022 |
| MSI           | B550M PRO-DASH              | [585987ecf7](https://linux-hardware.org/?probe=585987ecf7) | May 06, 2022 |
| Gigabyte      | H410M H V3                  | [ddc4d88d20](https://linux-hardware.org/?probe=ddc4d88d20) | May 05, 2022 |
| ASUSTek       | P8H67-M LE                  | [302e27b974](https://linux-hardware.org/?probe=302e27b974) | May 04, 2022 |
| ASUSTek       | P8H67-M LE                  | [a9cf3bc268](https://linux-hardware.org/?probe=a9cf3bc268) | May 04, 2022 |
| HP            | 1589                        | [79df2c00dc](https://linux-hardware.org/?probe=79df2c00dc) | May 03, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [cb6d49fe71](https://linux-hardware.org/?probe=cb6d49fe71) | Apr 30, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [83e47f9c91](https://linux-hardware.org/?probe=83e47f9c91) | Apr 30, 2022 |
| ASUSTek       | PRIME Z390-A                | [c4d7dc5e80](https://linux-hardware.org/?probe=c4d7dc5e80) | Apr 30, 2022 |
| MSI           | MAG B460M MORTAR            | [07cb268e5e](https://linux-hardware.org/?probe=07cb268e5e) | Apr 30, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [2999ff1487](https://linux-hardware.org/?probe=2999ff1487) | Apr 28, 2022 |
| ASRock        | B450 Steel Legend           | [bf0a56358c](https://linux-hardware.org/?probe=bf0a56358c) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [5456280ec0](https://linux-hardware.org/?probe=5456280ec0) | Apr 26, 2022 |
| Gigabyte      | X570 AORUS PRO              | [187db4f8e4](https://linux-hardware.org/?probe=187db4f8e4) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b9ea98672f](https://linux-hardware.org/?probe=b9ea98672f) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [c3f809fc02](https://linux-hardware.org/?probe=c3f809fc02) | Apr 23, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [68a04098ec](https://linux-hardware.org/?probe=68a04098ec) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [466f67adb3](https://linux-hardware.org/?probe=466f67adb3) | Apr 20, 2022 |
| Gigabyte      | H81M-S2H                    | [85082e6de6](https://linux-hardware.org/?probe=85082e6de6) | Apr 19, 2022 |
| Gigabyte      | H110M-H-CF                  | [66ef9c9e5f](https://linux-hardware.org/?probe=66ef9c9e5f) | Apr 16, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [22a1a17a81](https://linux-hardware.org/?probe=22a1a17a81) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| ASUSTek       | P8P67 LE                    | [84abfd3112](https://linux-hardware.org/?probe=84abfd3112) | Apr 14, 2022 |
| MSI           | FM2-A75IA-E53               | [25ffe3d211](https://linux-hardware.org/?probe=25ffe3d211) | Apr 14, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | [d1b267f496](https://linux-hardware.org/?probe=d1b267f496) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | [c1beed0e9b](https://linux-hardware.org/?probe=c1beed0e9b) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | [e5a9e99dbc](https://linux-hardware.org/?probe=e5a9e99dbc) | Apr 13, 2022 |
| Dell          | 0GWHMW A03                  | [ff312c5929](https://linux-hardware.org/?probe=ff312c5929) | Apr 13, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [5b861faffd](https://linux-hardware.org/?probe=5b861faffd) | Apr 09, 2022 |
| Gigabyte      | Z490 UD                     | [31ecc9c776](https://linux-hardware.org/?probe=31ecc9c776) | Apr 09, 2022 |
| Biostar       | B550MH                      | [abd373497b](https://linux-hardware.org/?probe=abd373497b) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS M                | [1a4b90c894](https://linux-hardware.org/?probe=1a4b90c894) | Apr 08, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | [ffcbeed952](https://linux-hardware.org/?probe=ffcbeed952) | Apr 08, 2022 |
| Gigabyte      | Z170N-Gaming 5              | [f0472bcf0d](https://linux-hardware.org/?probe=f0472bcf0d) | Apr 05, 2022 |
| Gigabyte      | Z170N-Gaming 5              | [9ee2f76c12](https://linux-hardware.org/?probe=9ee2f76c12) | Apr 05, 2022 |
| ASUSTek       | B150M-K                     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [5bbc4cbbf5](https://linux-hardware.org/?probe=5bbc4cbbf5) | Apr 03, 2022 |
| Dell          | 088DT1 A01                  | [718a7d42cc](https://linux-hardware.org/?probe=718a7d42cc) | Apr 02, 2022 |
| Gigabyte      | H81M-S2H                    | [8a810aa9f6](https://linux-hardware.org/?probe=8a810aa9f6) | Apr 02, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | [f7946783ea](https://linux-hardware.org/?probe=f7946783ea) | Mar 31, 2022 |
| Gigabyte      | H370M DS3H-CF               | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| Gigabyte      | EP45-DS3L                   | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Gigabyte      | B85M-D3V-A                  | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [97eedd34f4](https://linux-hardware.org/?probe=97eedd34f4) | Mar 05, 2022 |
| Gigabyte      | EP45-DS3L                   | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| Biostar       | H55 HD                      | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| Biostar       | H55 HD                      | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [f1a1a21c56](https://linux-hardware.org/?probe=f1a1a21c56) | Oct 26, 2021 |
| Dell          | 0KC9NP A01                  | [ff356cba89](https://linux-hardware.org/?probe=ff356cba89) | Oct 22, 2021 |
| MSI           | FM2-A55M-E33                | [bcf7dcdd2c](https://linux-hardware.org/?probe=bcf7dcdd2c) | Oct 09, 2021 |
| MSI           | FM2-A55M-E33                | [0b3691d096](https://linux-hardware.org/?probe=0b3691d096) | Oct 09, 2021 |
| HP            | 304Ah                       | [047d1b0887](https://linux-hardware.org/?probe=047d1b0887) | Aug 18, 2021 |
| Dell          | 0KC9NP A01                  | [2ca8cc81b1](https://linux-hardware.org/?probe=2ca8cc81b1) | Aug 18, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_36/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.17.5-300.fc36.x86_64  | 47       | 6.33%   |
| 5.18.13-200.fc36.x86_64 | 42       | 5.65%   |
| 5.19.16-200.fc36.x86_64 | 38       | 5.11%   |
| 6.0.5-200.fc36.x86_64   | 35       | 4.71%   |
| 5.19.9-200.fc36.x86_64  | 31       | 4.17%   |
| 5.18.16-200.fc36.x86_64 | 31       | 4.17%   |
| 5.18.11-200.fc36.x86_64 | 31       | 4.17%   |
| 5.18.5-200.fc36.x86_64  | 30       | 4.04%   |
| 5.19.6-200.fc36.x86_64  | 23       | 3.1%    |
| 5.17.6-300.fc36.x86_64  | 23       | 3.1%    |
| 5.19.8-200.fc36.x86_64  | 21       | 2.83%   |
| 5.17.11-300.fc36.x86_64 | 20       | 2.69%   |
| 5.18.18-200.fc36.x86_64 | 19       | 2.56%   |
| 5.18.10-200.fc36.x86_64 | 18       | 2.42%   |
| 5.17.12-300.fc36.x86_64 | 16       | 2.15%   |
| 5.19.12-200.fc36.x86_64 | 15       | 2.02%   |
| 5.18.9-200.fc36.x86_64  | 15       | 2.02%   |
| 5.17.13-300.fc36.x86_64 | 15       | 2.02%   |
| 5.19.4-200.fc36.x86_64  | 14       | 1.88%   |
| 5.19.14-200.fc36.x86_64 | 14       | 1.88%   |
| 6.0.7-200.fc36.x86_64   | 13       | 1.75%   |
| 5.19.15-201.fc36.x86_64 | 13       | 1.75%   |
| 5.17.8-300.fc36.x86_64  | 13       | 1.75%   |
| 5.18.7-200.fc36.x86_64  | 12       | 1.62%   |
| 5.19.11-200.fc36.x86_64 | 11       | 1.48%   |
| 5.18.6-200.fc36.x86_64  | 11       | 1.48%   |
| 5.18.19-200.fc36.x86_64 | 11       | 1.48%   |
| 5.17.2-300.fc36.x86_64  | 11       | 1.48%   |
| 5.18.17-200.fc36.x86_64 | 10       | 1.35%   |
| 5.17.1-300.fc36.x86_64  | 10       | 1.35%   |
| 5.19.13-200.fc36.x86_64 | 9        | 1.21%   |
| 5.17.7-300.fc36.x86_64  | 9        | 1.21%   |
| 6.0.9-200.fc36.x86_64   | 8        | 1.08%   |
| 6.0.8-200.fc36.x86_64   | 8        | 1.08%   |
| 5.18.15-200.fc36.x86_64 | 8        | 1.08%   |
| 5.19.7-200.fc36.x86_64  | 6        | 0.81%   |
| 5.17.3-302.fc36.x86_64  | 6        | 0.81%   |
| 6.0.10-200.fc36.x86_64  | 5        | 0.67%   |
| 5.19.10-200.fc36.x86_64 | 5        | 0.67%   |
| 5.17.9-300.fc36.x86_64  | 5        | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.5  | 48       | 6.46%   |
| 5.18.13 | 42       | 5.65%   |
| 5.19.16 | 39       | 5.25%   |
| 6.0.5   | 35       | 4.71%   |
| 5.18.5  | 32       | 4.31%   |
| 5.19.9  | 31       | 4.17%   |
| 5.18.16 | 31       | 4.17%   |
| 5.18.11 | 31       | 4.17%   |
| 5.19.6  | 24       | 3.23%   |
| 5.17.6  | 24       | 3.23%   |
| 5.19.8  | 22       | 2.96%   |
| 5.17.11 | 22       | 2.96%   |
| 5.18.18 | 19       | 2.56%   |
| 5.18.10 | 19       | 2.56%   |
| 5.18.9  | 18       | 2.42%   |
| 5.17.12 | 17       | 2.29%   |
| 5.19.12 | 16       | 2.15%   |
| 5.17.13 | 15       | 2.02%   |
| 5.19.4  | 14       | 1.88%   |
| 5.19.14 | 14       | 1.88%   |
| 6.0.7   | 13       | 1.75%   |
| 5.19.15 | 13       | 1.75%   |
| 5.17.8  | 13       | 1.75%   |
| 5.18.7  | 12       | 1.62%   |
| 5.18.6  | 12       | 1.62%   |
| 5.19.11 | 11       | 1.48%   |
| 5.18.19 | 11       | 1.48%   |
| 5.17.2  | 11       | 1.48%   |
| 5.19.13 | 10       | 1.35%   |
| 5.18.17 | 10       | 1.35%   |
| 5.17.7  | 10       | 1.35%   |
| 5.17.1  | 10       | 1.35%   |
| 6.0.8   | 9        | 1.21%   |
| 6.0.9   | 8        | 1.08%   |
| 5.18.15 | 8        | 1.08%   |
| 5.19.7  | 7        | 0.94%   |
| 5.17.9  | 7        | 0.94%   |
| 5.17.3  | 6        | 0.81%   |
| 5.17.0  | 6        | 0.81%   |
| 6.0.10  | 5        | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.18    | 238      | 33.47%  |
| 5.19    | 201      | 28.27%  |
| 5.17    | 186      | 26.16%  |
| 6.0     | 77       | 10.83%  |
| 5.15    | 3        | 0.42%   |
| 5.14    | 2        | 0.28%   |
| 6.1     | 1        | 0.14%   |
| 5.4     | 1        | 0.14%   |
| 5.16    | 1        | 0.14%   |
| 5.11    | 1        | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 647      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 445      | 68.67%  |
| KDE5          | 128      | 19.75%  |
| XFCE          | 15       | 2.31%   |
| Cinnamon      | 14       | 2.16%   |
| X-Cinnamon    | 13       | 2.01%   |
| Unknown       | 13       | 2.01%   |
| MATE          | 7        | 1.08%   |
| GNOME Classic | 5        | 0.77%   |
| LXQt          | 4        | 0.62%   |
| Pantheon      | 1        | 0.15%   |
| KDE           | 1        | 0.15%   |
| i3            | 1        | 0.15%   |
| awesome       | 1        | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 391      | 59.97%  |
| X11     | 228      | 34.97%  |
| Tty     | 28       | 4.29%   |
| Unknown | 3        | 0.46%   |
| Web     | 2        | 0.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 378      | 58.06%  |
| GDM     | 161      | 24.73%  |
| SDDM    | 65       | 9.98%   |
| LightDM | 47       | 7.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 310      | 47.91%  |
| en_GB      | 45       | 6.96%   |
| ru_RU      | 44       | 6.8%    |
| pt_BR      | 34       | 5.26%   |
| en_AU      | 31       | 4.79%   |
| de_DE      | 25       | 3.86%   |
| it_IT      | 23       | 3.55%   |
| en_CA      | 16       | 2.47%   |
| fr_FR      | 15       | 2.32%   |
| pl_PL      | 12       | 1.85%   |
| es_ES      | 11       | 1.7%    |
| en_IN      | 7        | 1.08%   |
| en_NZ      | 6        | 0.93%   |
| cs_CZ      | 6        | 0.93%   |
| es_AR      | 5        | 0.77%   |
| zh_CN      | 4        | 0.62%   |
| nl_NL      | 4        | 0.62%   |
| nl_BE      | 4        | 0.62%   |
| ja_JP      | 3        | 0.46%   |
| es_MX      | 3        | 0.46%   |
| en_IE      | 3        | 0.46%   |
| tr_TR      | 2        | 0.31%   |
| sv_SE      | 2        | 0.31%   |
| pt_PT      | 2        | 0.31%   |
| hu_HU      | 2        | 0.31%   |
| fi_FI      | 2        | 0.31%   |
| en_SG      | 2        | 0.31%   |
| C          | 2        | 0.31%   |
| sr_RS      | 1        | 0.15%   |
| sk_SK      | 1        | 0.15%   |
| nn_NO      | 1        | 0.15%   |
| nb_NO      | 1        | 0.15%   |
| hu_HU.UTF8 | 1        | 0.15%   |
| fr_BE      | 1        | 0.15%   |
| es_VE      | 1        | 0.15%   |
| es_PE      | 1        | 0.15%   |
| es_EC      | 1        | 0.15%   |
| es_CR      | 1        | 0.15%   |
| es_CO      | 1        | 0.15%   |
| es_CL      | 1        | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 462      | 71.08%  |
| BIOS | 188      | 28.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 509      | 78.43%  |
| Ext4    | 117      | 18.03%  |
| Xfs     | 22       | 3.39%   |
| Overlay | 1        | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 370      | 56.84%  |
| GPT     | 227      | 34.87%  |
| MBR     | 54       | 8.29%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 561      | 85.91%  |
| Yes       | 92       | 14.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 503      | 77.27%  |
| Yes       | 148      | 22.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 209      | 32.3%   |
| Gigabyte Technology | 128      | 19.78%  |
| MSI                 | 104      | 16.07%  |
| ASRock              | 60       | 9.27%   |
| Dell                | 39       | 6.03%   |
| Hewlett-Packard     | 34       | 5.26%   |
| Lenovo              | 17       | 2.63%   |
| BESSTAR Tech        | 9        | 1.39%   |
| Intel               | 8        | 1.24%   |
| Foxconn             | 6        | 0.93%   |
| Acer                | 6        | 0.93%   |
| Unknown             | 6        | 0.93%   |
| Huanan              | 4        | 0.62%   |
| Biostar             | 3        | 0.46%   |
| Pegatron            | 2        | 0.31%   |
| ECS                 | 2        | 0.31%   |
| ZOTAC               | 1        | 0.15%   |
| System76            | 1        | 0.15%   |
| Shuttle             | 1        | 0.15%   |
| Positivo            | 1        | 0.15%   |
| NZXT                | 1        | 0.15%   |
| NCR                 | 1        | 0.15%   |
| MAXSUN              | 1        | 0.15%   |
| MACHINIST           | 1        | 0.15%   |
| Fujitsu             | 1        | 0.15%   |
| Casper              | 1        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 14       | 2.16%   |
| MSI MS-7C37                       | 8        | 1.24%   |
| MSI MS-7A38                       | 7        | 1.08%   |
| ASUS ROG STRIX B550-F GAMING      | 7        | 1.08%   |
| Unknown                           | 7        | 1.08%   |
| MSI MS-7C91                       | 6        | 0.93%   |
| MSI MS-7B86                       | 6        | 0.93%   |
| ASUS TUF Gaming B550M-PLUS        | 5        | 0.77%   |
| ASUS ROG STRIX X570-F GAMING      | 5        | 0.77%   |
| MSI MS-7B79                       | 4        | 0.62%   |
| Gigabyte B450M DS3H               | 4        | 0.62%   |
| Gigabyte B450 AORUS ELITE         | 4        | 0.62%   |
| Dell OptiPlex 9020                | 4        | 0.62%   |
| ASUS TUF Gaming X570-PLUS         | 4        | 0.62%   |
| ASUS TUF Gaming B550-PLUS         | 4        | 0.62%   |
| ASUS PRIME Z370-A                 | 4        | 0.62%   |
| ASUS PRIME B450-PLUS              | 4        | 0.62%   |
| ASRock B450M Pro4                 | 4        | 0.62%   |
| MSI MS-7D54                       | 3        | 0.46%   |
| MSI MS-7D43                       | 3        | 0.46%   |
| MSI MS-7C95                       | 3        | 0.46%   |
| MSI MS-7C84                       | 3        | 0.46%   |
| MSI MS-7C56                       | 3        | 0.46%   |
| MSI MS-7817                       | 3        | 0.46%   |
| Gigabyte X470 AORUS GAMING 7 WIFI | 3        | 0.46%   |
| Gigabyte GA-78LMT-USB3 6.0        | 3        | 0.46%   |
| Gigabyte B550M DS3H               | 3        | 0.46%   |
| Gigabyte B550I AORUS PRO AX       | 3        | 0.46%   |
| Gigabyte A320M-S2H                | 3        | 0.46%   |
| Dell XPS 8940                     | 3        | 0.46%   |
| Dell OptiPlex 790                 | 3        | 0.46%   |
| BESSTAR Tech UM700                | 3        | 0.46%   |
| ASUS TUF B350M-PLUS GAMING        | 3        | 0.46%   |
| ASUS ROG STRIX X570-E GAMING      | 3        | 0.46%   |
| ASUS ROG STRIX B550-I GAMING      | 3        | 0.46%   |
| ASUS ROG STRIX B450-F GAMING II   | 3        | 0.46%   |
| ASUS ROG CROSSHAIR VIII HERO      | 3        | 0.46%   |
| ASUS ProArt Z690-CREATOR WIFI     | 3        | 0.46%   |
| ASUS PRIME Z270-P                 | 3        | 0.46%   |
| ASUS PRIME X470-PRO               | 3        | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS ROG            | 54       | 8.35%   |
| ASUS PRIME          | 46       | 7.11%   |
| ASUS TUF            | 32       | 4.95%   |
| Dell OptiPlex       | 17       | 2.63%   |
| ASUS All            | 14       | 2.16%   |
| Dell Precision      | 11       | 1.7%    |
| HP Compaq           | 9        | 1.39%   |
| MSI MS-7C37         | 8        | 1.24%   |
| Lenovo ThinkCentre  | 8        | 1.24%   |
| Gigabyte B450       | 8        | 1.24%   |
| MSI MS-7A38         | 7        | 1.08%   |
| Gigabyte B550       | 7        | 1.08%   |
| Dell XPS            | 7        | 1.08%   |
| ASRock B450M        | 7        | 1.08%   |
| Unknown             | 7        | 1.08%   |
| MSI MS-7C91         | 6        | 0.93%   |
| MSI MS-7B86         | 6        | 0.93%   |
| Gigabyte X570       | 6        | 0.93%   |
| Gigabyte B450M      | 6        | 0.93%   |
| Gigabyte X470       | 5        | 0.77%   |
| ASUS ProArt         | 5        | 0.77%   |
| ASRock X570         | 5        | 0.77%   |
| MSI MS-7B79         | 4        | 0.62%   |
| HP Z2               | 4        | 0.62%   |
| HP ProDesk          | 4        | 0.62%   |
| Gigabyte B550M      | 4        | 0.62%   |
| Gigabyte A320M-S2H  | 4        | 0.62%   |
| ASUS CROSSHAIR      | 4        | 0.62%   |
| ASRock X370         | 4        | 0.62%   |
| Acer Aspire         | 4        | 0.62%   |
| MSI MS-7D54         | 3        | 0.46%   |
| MSI MS-7D43         | 3        | 0.46%   |
| MSI MS-7C95         | 3        | 0.46%   |
| MSI MS-7C84         | 3        | 0.46%   |
| MSI MS-7C56         | 3        | 0.46%   |
| MSI MS-7817         | 3        | 0.46%   |
| Lenovo ThinkStation | 3        | 0.46%   |
| Lenovo Legion       | 3        | 0.46%   |
| HP Pavilion         | 3        | 0.46%   |
| HP EliteDesk        | 3        | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 99       | 15.3%   |
| 2019 | 79       | 12.21%  |
| 2021 | 76       | 11.75%  |
| 2018 | 76       | 11.75%  |
| 2012 | 45       | 6.96%   |
| 2017 | 44       | 6.8%    |
| 2014 | 43       | 6.65%   |
| 2013 | 32       | 4.95%   |
| 2015 | 27       | 4.17%   |
| 2022 | 26       | 4.02%   |
| 2016 | 26       | 4.02%   |
| 2011 | 21       | 3.25%   |
| 2010 | 18       | 2.78%   |
| 2009 | 13       | 2.01%   |
| 2008 | 10       | 1.55%   |
| 2007 | 7        | 1.08%   |
| 2006 | 4        | 0.62%   |
| 2005 | 1        | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 647      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 592      | 91.22%  |
| Enabled  | 57       | 8.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 647      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 213      | 32.67%  |
| 32.01-64.0  | 178      | 27.3%   |
| 8.01-16.0   | 84       | 12.88%  |
| 4.01-8.0    | 67       | 10.28%  |
| 64.01-256.0 | 55       | 8.44%   |
| 3.01-4.0    | 31       | 4.75%   |
| 24.01-32.0  | 16       | 2.45%   |
| 1.01-2.0    | 5        | 0.77%   |
| 2.01-3.0    | 3        | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 202      | 29.36%  |
| 2.01-3.0   | 166      | 24.13%  |
| 3.01-4.0   | 148      | 21.51%  |
| 8.01-16.0  | 74       | 10.76%  |
| 1.01-2.0   | 67       | 9.74%   |
| 16.01-24.0 | 13       | 1.89%   |
| 0.51-1.0   | 10       | 1.45%   |
| 32.01-64.0 | 3        | 0.44%   |
| 0.01-0.5   | 3        | 0.44%   |
| 24.01-32.0 | 2        | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 218      | 33.08%  |
| 1      | 174      | 26.4%   |
| 3      | 135      | 20.49%  |
| 4      | 73       | 11.08%  |
| 5      | 26       | 3.95%   |
| 6      | 18       | 2.73%   |
| 7      | 9        | 1.37%   |
| 11     | 2        | 0.3%    |
| 10     | 2        | 0.3%    |
| 9      | 1        | 0.15%   |
| 0      | 1        | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 471      | 72.46%  |
| Yes       | 179      | 27.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 642      | 99.07%  |
| No        | 6        | 0.93%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 359      | 55.32%  |
| No        | 290      | 44.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 349      | 53.69%  |
| Yes       | 301      | 46.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 142      | 21.91%  |
| Brazil      | 49       | 7.56%   |
| Russia      | 47       | 7.25%   |
| Germany     | 44       | 6.79%   |
| Italy       | 42       | 6.48%   |
| Australia   | 30       | 4.63%   |
| UK          | 24       | 3.7%    |
| Poland      | 21       | 3.24%   |
| France      | 21       | 3.24%   |
| Canada      | 19       | 2.93%   |
| Spain       | 17       | 2.62%   |
| Netherlands | 13       | 2.01%   |
| Sweden      | 12       | 1.85%   |
| India       | 11       | 1.7%    |
| Finland     | 10       | 1.54%   |
| Belgium     | 10       | 1.54%   |
| Norway      | 7        | 1.08%   |
| Argentina   | 7        | 1.08%   |
| Switzerland | 6        | 0.93%   |
| Mexico      | 6        | 0.93%   |
| Greece      | 6        | 0.93%   |
| Czechia     | 6        | 0.93%   |
| Turkey      | 5        | 0.77%   |
| Portugal    | 5        | 0.77%   |
| Philippines | 5        | 0.77%   |
| New Zealand | 5        | 0.77%   |
| Japan       | 5        | 0.77%   |
| Hungary     | 5        | 0.77%   |
| Romania     | 4        | 0.62%   |
| Israel      | 4        | 0.62%   |
| China       | 4        | 0.62%   |
| Belarus     | 4        | 0.62%   |
| Serbia      | 3        | 0.46%   |
| Indonesia   | 3        | 0.46%   |
| Colombia    | 3        | 0.46%   |
| Thailand    | 2        | 0.31%   |
| Slovakia    | 2        | 0.31%   |
| Puerto Rico | 2        | 0.31%   |
| Ireland     | 2        | 0.31%   |
| Estonia     | 2        | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 10       | 1.51%   |
| Launceston     | 8        | 1.2%    |
| Brisbane       | 8        | 1.2%    |
| Warsaw         | 7        | 1.05%   |
| St Petersburg  | 6        | 0.9%    |
| Melbourne      | 6        | 0.9%    |
| Lane Cove      | 6        | 0.9%    |
| Berlin         | 6        | 0.9%    |
| Sydney         | 5        | 0.75%   |
| Sao Paulo      | 5        | 0.75%   |
| Porto Alegre   | 5        | 0.75%   |
| Novosibirsk    | 5        | 0.75%   |
| Vitória       | 4        | 0.6%    |
| Milan          | 4        | 0.6%    |
| Helsinki       | 4        | 0.6%    |
| Auckland       | 4        | 0.6%    |
| Wroclaw        | 3        | 0.45%   |
| Stockholm      | 3        | 0.45%   |
| San Juan       | 3        | 0.45%   |
| Rome           | 3        | 0.45%   |
| Portland       | 3        | 0.45%   |
| Perth          | 3        | 0.45%   |
| Pasco          | 3        | 0.45%   |
| Oulu           | 3        | 0.45%   |
| New York       | 3        | 0.45%   |
| Minsk          | 3        | 0.45%   |
| Mexico City    | 3        | 0.45%   |
| Marietta       | 3        | 0.45%   |
| Manchester     | 3        | 0.45%   |
| Los Angeles    | 3        | 0.45%   |
| Hamburg        | 3        | 0.45%   |
| Fayetteville   | 3        | 0.45%   |
| Chicago        | 3        | 0.45%   |
| Brussels       | 3        | 0.45%   |
| Belo Horizonte | 3        | 0.45%   |
| Belgrade       | 3        | 0.45%   |
| Amsterdam      | 3        | 0.45%   |
| Yekaterinburg  | 2        | 0.3%    |
| Winnipeg       | 2        | 0.3%    |
| Verona         | 2        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 234      | 377    | 17.75%  |
| WDC                         | 220      | 352    | 16.69%  |
| Seagate                     | 214      | 317    | 16.24%  |
| Kingston                    | 104      | 124    | 7.89%   |
| SanDisk                     | 77       | 95     | 5.84%   |
| Crucial                     | 68       | 95     | 5.16%   |
| Toshiba                     | 65       | 78     | 4.93%   |
| Phison                      | 27       | 30     | 2.05%   |
| Hitachi                     | 26       | 41     | 1.97%   |
| Intel                       | 20       | 30     | 1.52%   |
| A-DATA Technology           | 19       | 21     | 1.44%   |
| Micron/Crucial Technology   | 17       | 22     | 1.29%   |
| China                       | 13       | 16     | 0.99%   |
| SPCC                        | 12       | 17     | 0.91%   |
| SK hynix                    | 11       | 11     | 0.83%   |
| Silicon Motion              | 11       | 11     | 0.83%   |
| HGST                        | 11       | 15     | 0.83%   |
| Patriot                     | 10       | 11     | 0.76%   |
| XPG                         | 8        | 9      | 0.61%   |
| PNY                         | 8        | 10     | 0.61%   |
| Phison Electronics          | 8        | 10     | 0.61%   |
| Unknown                     | 7        | 10     | 0.53%   |
| Micron Technology           | 7        | 8      | 0.53%   |
| Corsair                     | 6        | 7      | 0.46%   |
| MAXIO Technology (Hangzhou) | 5        | 6      | 0.38%   |
| Gigabyte Technology         | 5        | 8      | 0.38%   |
| SABRENT                     | 4        | 6      | 0.3%    |
| LITEON                      | 4        | 4      | 0.3%    |
| Intenso                     | 4        | 6      | 0.3%    |
| Hewlett-Packard             | 4        | 5      | 0.3%    |
| GOODRAM                     | 4        | 6      | 0.3%    |
| Unknown                     | 4        | 4      | 0.3%    |
| Transcend                   | 3        | 3      | 0.23%   |
| Team                        | 3        | 6      | 0.23%   |
| Realtek Semiconductor       | 3        | 3      | 0.23%   |
| Plextor                     | 3        | 5      | 0.23%   |
| OCZ                         | 3        | 6      | 0.23%   |
| Netac                       | 3        | 3      | 0.23%   |
| Lexar                       | 3        | 4      | 0.23%   |
| KIOXIA-EXCERIA              | 3        | 3      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 26       | 1.69%   |
| Samsung SSD 850 EVO 250GB                           | 22       | 1.43%   |
| Samsung NVMe SSD Drive 1TB                          | 21       | 1.36%   |
| Seagate ST1000DM010-2EP102 1TB                      | 19       | 1.23%   |
| Seagate ST500DM002-1BD142 500GB                     | 18       | 1.17%   |
| Samsung SSD 860 EVO 500GB                           | 17       | 1.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 16       | 1.04%   |
| Kingston SA400S37120G 120GB SSD                     | 15       | 0.97%   |
| Seagate ST2000DM008-2FR102 2TB                      | 14       | 0.91%   |
| SanDisk NVMe SSD Drive 1TB                          | 14       | 0.91%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 13       | 0.84%   |
| Seagate ST1000DM003-1ER162 1TB                      | 13       | 0.84%   |
| Samsung SSD 850 EVO 500GB                           | 13       | 0.84%   |
| Samsung NVMe SSD Drive 500GB                        | 13       | 0.84%   |
| Samsung NVMe SSD Drive 2TB                          | 11       | 0.71%   |
| Crucial CT1000MX500SSD1 1TB                         | 11       | 0.71%   |
| SanDisk NVMe SSD Drive 500GB                        | 10       | 0.65%   |
| Toshiba DT01ACA100 1TB                              | 9        | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 9        | 0.58%   |
| Kingston SA400S37480G 480GB SSD                     | 9        | 0.58%   |
| Crucial CT500MX500SSD1 500GB                        | 9        | 0.58%   |
| Seagate ST2000DM001-1ER164 2TB                      | 8        | 0.52%   |
| Samsung SSD 980 PRO 1TB                             | 8        | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB                      | 8        | 0.52%   |
| Samsung NVMe SSD Drive 250GB                        | 8        | 0.52%   |
| Crucial CT240BX500SSD1 240GB                        | 8        | 0.52%   |
| Seagate ST2000DM006-2DM164 2TB                      | 7        | 0.45%   |
| Seagate ST1000DM003-1CH162 1TB                      | 7        | 0.45%   |
| Samsung SSD 870 QVO 2TB                             | 7        | 0.45%   |
| Samsung SSD 870 QVO 1TB                             | 7        | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 7        | 0.45%   |
| Crucial CT2000MX500SSD1 2TB                         | 7        | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 6        | 0.39%   |
| WDC WD40EFRX-68N32N0 4TB                            | 6        | 0.39%   |
| WDC WD10EZEX-00WN4A0 1TB                            | 6        | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 6        | 0.39%   |
| Toshiba HDWD110 1TB                                 | 6        | 0.39%   |
| Seagate Expansion 4TB                               | 6        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6        | 0.39%   |
| Samsung SSD 870 EVO 500GB                           | 6        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 208      | 304    | 40.7%   |
| WDC                 | 183      | 282    | 35.81%  |
| Toshiba             | 53       | 59     | 10.37%  |
| Hitachi             | 26       | 41     | 5.09%   |
| Samsung Electronics | 11       | 20     | 2.15%   |
| HGST                | 11       | 15     | 2.15%   |
| Unknown             | 3        | 3      | 0.59%   |
| Hewlett-Packard     | 2        | 3      | 0.39%   |
| Fujitsu             | 2        | 3      | 0.39%   |
| ASMT                | 2        | 2      | 0.39%   |
| USB                 | 1        | 1      | 0.2%    |
| SAGE                | 1        | 1      | 0.2%    |
| RSH-339             | 1        | 1      | 0.2%    |
| Maxtor              | 1        | 3      | 0.2%    |
| JMicron Technology  | 1        | 1      | 0.2%    |
| Intenso             | 1        | 1      | 0.2%    |
| ExcelStor           | 1        | 1      | 0.2%    |
| ASMT106x            | 1        | 1      | 0.2%    |
| Apple               | 1        | 1      | 0.2%    |
| Unknown             | 1        | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 131      | 180    | 27.12%  |
| Kingston            | 79       | 93     | 16.36%  |
| Crucial             | 61       | 87     | 12.63%  |
| WDC                 | 36       | 50     | 7.45%   |
| SanDisk             | 36       | 39     | 7.45%   |
| China               | 13       | 16     | 2.69%   |
| A-DATA Technology   | 13       | 13     | 2.69%   |
| SPCC                | 11       | 16     | 2.28%   |
| Intel               | 11       | 17     | 2.28%   |
| Patriot             | 9        | 10     | 1.86%   |
| PNY                 | 8        | 10     | 1.66%   |
| Toshiba             | 5        | 6      | 1.04%   |
| Micron Technology   | 5        | 5      | 1.04%   |
| Gigabyte Technology | 5        | 8      | 1.04%   |
| LITEON              | 4        | 4      | 0.83%   |
| GOODRAM             | 4        | 6      | 0.83%   |
| Corsair             | 4        | 4      | 0.83%   |
| Transcend           | 3        | 3      | 0.62%   |
| Team                | 3        | 6      | 0.62%   |
| SK hynix            | 3        | 3      | 0.62%   |
| Seagate             | 3        | 3      | 0.62%   |
| Plextor             | 3        | 5      | 0.62%   |
| OCZ                 | 3        | 6      | 0.62%   |
| Lexar               | 3        | 4      | 0.62%   |
| Verbatim            | 2        | 4      | 0.41%   |
| LITEONIT            | 2        | 2      | 0.41%   |
| KIOXIA-EXCERIA      | 2        | 2      | 0.41%   |
| KingSpec            | 2        | 2      | 0.41%   |
| KingDian            | 2        | 2      | 0.41%   |
| Intenso             | 2        | 4      | 0.41%   |
| Apacer              | 2        | 2      | 0.41%   |
| XSTAR               | 1        | 1      | 0.21%   |
| Timetec             | 1        | 1      | 0.21%   |
| TCSUNBOW            | 1        | 1      | 0.21%   |
| Smartbuy            | 1        | 1      | 0.21%   |
| SKIHOTAR            | 1        | 1      | 0.21%   |
| Netac               | 1        | 1      | 0.21%   |
| MyDigitalSSD        | 1        | 2      | 0.21%   |
| Mushkin             | 1        | 1      | 0.21%   |
| Leven               | 1        | 1      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 403      | 744    | 35.73%  |
| SSD     | 382      | 628    | 33.87%  |
| NVMe    | 319      | 462    | 28.28%  |
| Unknown | 24       | 31     | 2.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 557      | 1327   | 60.02%  |
| NVMe | 317      | 456    | 34.16%  |
| SAS  | 54       | 82     | 5.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 377      | 661    | 43.58%  |
| 0.51-1.0   | 267      | 386    | 30.87%  |
| 1.01-2.0   | 109      | 163    | 12.6%   |
| 3.01-4.0   | 58       | 77     | 6.71%   |
| 2.01-3.0   | 25       | 33     | 2.89%   |
| 4.01-10.0  | 25       | 46     | 2.89%   |
| 10.01-20.0 | 4        | 6      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 134      | 20.18%  |
| 501-1000       | 125      | 18.83%  |
| More than 3000 | 118      | 17.77%  |
| 251-500        | 79       | 11.9%   |
| 101-250        | 68       | 10.24%  |
| 2001-3000      | 58       | 8.73%   |
| 1-20           | 36       | 5.42%   |
| Unknown        | 22       | 3.31%   |
| 51-100         | 17       | 2.56%   |
| 21-50          | 7        | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 127      | 18.51%  |
| 21-50          | 88       | 12.83%  |
| 501-1000       | 84       | 12.24%  |
| 101-250        | 83       | 12.1%   |
| 251-500        | 79       | 11.52%  |
| 51-100         | 74       | 10.79%  |
| 1001-2000      | 67       | 9.77%   |
| More than 3000 | 39       | 5.69%   |
| 2001-3000      | 23       | 3.35%   |
| Unknown        | 22       | 3.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 5        | 11     | 7.04%   |
| Samsung Electronics SSD 870 EVO 1TB | 4        | 4      | 5.63%   |
| Seagate ST500LT012-1DG142 500GB     | 3        | 3      | 4.23%   |
| Seagate ST3500418AS 500GB           | 3        | 3      | 4.23%   |
| Samsung Electronics HD322HJ 320GB   | 2        | 2      | 2.82%   |
| Intel SSDSC2CT120A3 120GB           | 2        | 7      | 2.82%   |
| Intel SSDSC2BF180A4H 180GB          | 2        | 2      | 2.82%   |
| WDC WD800JD-75MSA3 80GB             | 1        | 1      | 1.41%   |
| WDC WD5000AAKX-08ERMA0 500GB        | 1        | 1      | 1.41%   |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 1      | 1.41%   |
| WDC WD5000AADS-00S9B0 500GB         | 1        | 1      | 1.41%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 1      | 1.41%   |
| WDC WD4001FAEX-00MJRA0 4TB          | 1        | 1      | 1.41%   |
| WDC WD3200AAKS-75B3A0 320GB         | 1        | 1      | 1.41%   |
| WDC WD3200AAJS-65M0A0 320GB         | 1        | 1      | 1.41%   |
| WDC WD30EZRX-00SPEB0 3TB            | 1        | 1      | 1.41%   |
| WDC WD2500AAKX-753CA1 250GB         | 1        | 1      | 1.41%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 1      | 1.41%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 1      | 1.41%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 1        | 1      | 1.41%   |
| WDC WD10EZEX-22MFCA0 1TB            | 1        | 1      | 1.41%   |
| WDC WD10EZEX-00MFCA0 1TB            | 1        | 1      | 1.41%   |
| WDC WD10EARS-22Y5B1 1TB             | 1        | 1      | 1.41%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 1      | 1.41%   |
| WDC WD10EADS-65M2B1 1TB             | 1        | 1      | 1.41%   |
| WDC WD1003FBYX-01Y7B1 1TB           | 1        | 2      | 1.41%   |
| Toshiba MQ01ABF050 500GB            | 1        | 1      | 1.41%   |
| Toshiba MQ01ABD050 500GB            | 1        | 2      | 1.41%   |
| Toshiba MK3275GSX 320GB             | 1        | 1      | 1.41%   |
| Toshiba DT01ACA100 1TB              | 1        | 1      | 1.41%   |
| SPCC Solid State Disk 1TB           | 1        | 2      | 1.41%   |
| SK hynix SH920 2.5 7MM 256GB SSD    | 1        | 1      | 1.41%   |
| Seagate ST500LM030-2E717D 500GB     | 1        | 1      | 1.41%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 1      | 1.41%   |
| Seagate ST4000VN008-2DR166 4TB      | 1        | 1      | 1.41%   |
| Seagate ST3500620AS 500GB           | 1        | 1      | 1.41%   |
| Seagate ST32000641AS 2TB            | 1        | 1      | 1.41%   |
| Seagate ST32000542AS 2TB            | 1        | 2      | 1.41%   |
| Seagate ST31000528AS 1TB            | 1        | 1      | 1.41%   |
| Seagate ST2000DX001-1CM164 2TB      | 1        | 1      | 1.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 20     | 27.69%  |
| Seagate             | 18       | 30     | 27.69%  |
| Samsung Electronics | 10       | 19     | 15.38%  |
| Intel               | 5        | 10     | 7.69%   |
| Toshiba             | 4        | 5      | 6.15%   |
| Hitachi             | 3        | 3      | 4.62%   |
| LITEON              | 2        | 2      | 3.08%   |
| SPCC                | 1        | 2      | 1.54%   |
| SK hynix            | 1        | 1      | 1.54%   |
| Kingston            | 1        | 1      | 1.54%   |
| HGST                | 1        | 1      | 1.54%   |
| Crucial             | 1        | 1      | 1.54%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 20     | 37.5%   |
| Seagate             | 18       | 30     | 37.5%   |
| Toshiba             | 4        | 5      | 8.33%   |
| Samsung Electronics | 4        | 13     | 8.33%   |
| Hitachi             | 3        | 3      | 6.25%   |
| HGST                | 1        | 1      | 2.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 45       | 72     | 73.77%  |
| SSD  | 16       | 23     | 26.23%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 394      | 1118   | 54.27%  |
| Works    | 270      | 650    | 37.19%  |
| Malfunc  | 61       | 95     | 8.4%    |
| Failed   | 1        | 2      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 349      | 32.59%  |
| AMD                           | 294      | 27.45%  |
| Samsung Electronics           | 133      | 12.42%  |
| SanDisk                       | 56       | 5.23%   |
| ASMedia Technology            | 40       | 3.73%   |
| Phison Electronics            | 39       | 3.64%   |
| Kingston Technology Company   | 28       | 2.61%   |
| Micron/Crucial Technology     | 24       | 2.24%   |
| Silicon Motion                | 14       | 1.31%   |
| ADATA Technology              | 13       | 1.21%   |
| Marvell Technology Group      | 11       | 1.03%   |
| JMicron Technology            | 11       | 1.03%   |
| Toshiba America Info Systems  | 8        | 0.75%   |
| SK hynix                      | 8        | 0.75%   |
| Nvidia                        | 6        | 0.56%   |
| Realtek Semiconductor         | 5        | 0.47%   |
| MAXIO Technology (Hangzhou)   | 5        | 0.47%   |
| Seagate Technology            | 4        | 0.37%   |
| LSI Logic / Symbios Logic     | 4        | 0.37%   |
| Silicon Image                 | 3        | 0.28%   |
| Micron Technology             | 2        | 0.19%   |
| KIOXIA                        | 2        | 0.19%   |
| INNOGRIT                      | 2        | 0.19%   |
| Broadcom / LSI                | 2        | 0.19%   |
| Adaptec                       | 2        | 0.19%   |
| VIA Technologies              | 1        | 0.09%   |
| ULi Electronics               | 1        | 0.09%   |
| Netac Technology              | 1        | 0.09%   |
| Lite-On Technology            | 1        | 0.09%   |
| Integrated Technology Express | 1        | 0.09%   |
| Hewlett-Packard               | 1        | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 171      | 13.45%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 75       | 5.9%    |
| AMD 400 Series Chipset SATA Controller                                         | 75       | 5.9%    |
| AMD 500 Series Chipset SATA Controller                                         | 70       | 5.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 45       | 3.54%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 39       | 3.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 32       | 2.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 32       | 2.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 29       | 2.28%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 28       | 2.2%    |
| Intel SATA Controller [RAID mode]                                              | 27       | 2.12%   |
| Phison E12 NVMe Controller                                                     | 25       | 1.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 23       | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 21       | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 21       | 1.65%   |
| Intel Volume Management Device NVMe RAID Controller                            | 20       | 1.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 20       | 1.57%   |
| Samsung NVMe SSD Controller 980                                                | 19       | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 18       | 1.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 15       | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 15       | 1.18%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 15       | 1.18%   |
| SanDisk Non-Volatile memory controller                                         | 14       | 1.1%    |
| AMD 300 Series Chipset SATA Controller                                         | 14       | 1.1%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 13       | 1.02%   |
| Kingston Company Company Non-Volatile memory controller                        | 12       | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                          | 12       | 0.94%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 10       | 0.79%   |
| AMD FCH SATA Controller D                                                      | 10       | 0.79%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 10       | 0.79%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 9        | 0.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 9        | 0.71%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 9        | 0.71%   |
| AMD X370 Series Chipset SATA Controller                                        | 9        | 0.71%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 8        | 0.63%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 8        | 0.63%   |
| Phison E16 PCIe4 NVMe Controller                                               | 7        | 0.55%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 7        | 0.55%   |
| Kingston Company A2000 NVMe SSD                                                | 7        | 0.55%   |
| Intel SSD 660P Series                                                          | 7        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 572      | 55.16%  |
| NVMe | 317      | 30.57%  |
| IDE  | 77       | 7.43%   |
| RAID | 64       | 6.17%   |
| SAS  | 4        | 0.39%   |
| SCSI | 3        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 346      | 53.48%  |
| AMD    | 301      | 46.52%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 30       | 4.62%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 23       | 3.54%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 21       | 3.24%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 18       | 2.77%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 16       | 2.47%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 14       | 2.16%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 13       | 2%      |
| AMD Ryzen 7 2700X Eight-Core Processor      | 12       | 1.85%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 11       | 1.69%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 10       | 1.54%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 10       | 1.54%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 9        | 1.39%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 9        | 1.39%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 9        | 1.39%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 8        | 1.23%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 8        | 1.23%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 8        | 1.23%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 6        | 0.92%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 6        | 0.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6        | 0.92%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 6        | 0.92%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 6        | 0.92%   |
| Intel 12th Gen Core i7-12700K               | 6        | 0.92%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 0.77%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 5        | 0.77%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 5        | 0.77%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 5        | 0.77%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 5        | 0.77%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 5        | 0.77%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 5        | 0.77%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 0.62%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 4        | 0.62%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 4        | 0.62%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 4        | 0.62%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 4        | 0.62%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 0.62%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 0.62%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 4        | 0.62%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 4        | 0.62%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 119      | 18.36%  |
| Intel Core i5           | 113      | 17.44%  |
| Intel Core i7           | 84       | 12.96%  |
| AMD Ryzen 7             | 68       | 10.49%  |
| AMD Ryzen 9             | 55       | 8.49%   |
| Other                   | 39       | 6.02%   |
| Intel Xeon              | 30       | 4.63%   |
| Intel Core i3           | 30       | 4.63%   |
| AMD FX                  | 16       | 2.47%   |
| Intel Core 2 Duo        | 12       | 1.85%   |
| Intel Core i9           | 10       | 1.54%   |
| Intel Core 2 Quad       | 8        | 1.23%   |
| Intel Pentium           | 6        | 0.93%   |
| AMD Ryzen 3             | 5        | 0.77%   |
| AMD Phenom II X4        | 5        | 0.77%   |
| AMD A8                  | 4        | 0.62%   |
| AMD A6                  | 4        | 0.62%   |
| AMD A10                 | 4        | 0.62%   |
| Intel Genuine           | 3        | 0.46%   |
| Intel Celeron           | 3        | 0.46%   |
| Intel Atom              | 3        | 0.46%   |
| AMD Phenom II X2        | 3        | 0.46%   |
| Intel Pentium Gold      | 2        | 0.31%   |
| Intel Pentium Dual-Core | 2        | 0.31%   |
| AMD Ryzen 7 PRO         | 2        | 0.31%   |
| AMD Phenom II X6        | 2        | 0.31%   |
| AMD Opteron             | 2        | 0.31%   |
| AMD Athlon Dual Core    | 2        | 0.31%   |
| AMD Athlon 64 X2        | 2        | 0.31%   |
| Intel Pentium Silver    | 1        | 0.15%   |
| Intel Core 2            | 1        | 0.15%   |
| AMD Ryzen Threadripper  | 1        | 0.15%   |
| AMD PRO A10             | 1        | 0.15%   |
| AMD Athlon X4           | 1        | 0.15%   |
| AMD Athlon II X4        | 1        | 0.15%   |
| AMD Athlon II X2        | 1        | 0.15%   |
| AMD Athlon 64           | 1        | 0.15%   |
| AMD Athlon              | 1        | 0.15%   |
| AMD A4                  | 1        | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 204      | 31.48%  |
| 6      | 172      | 26.54%  |
| 8      | 94       | 14.51%  |
| 2      | 77       | 11.88%  |
| 12     | 55       | 8.49%   |
| 16     | 22       | 3.4%    |
| 10     | 12       | 1.85%   |
| 3      | 7        | 1.08%   |
| 1      | 3        | 0.46%   |
| 18     | 1        | 0.15%   |
| 14     | 1        | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 641      | 99.07%  |
| 2      | 6        | 0.93%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 484      | 74.81%  |
| 1      | 163      | 25.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 647      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 58       | 8.92%   |
| 0x08701021 | 57       | 8.77%   |
| 0x0a201016 | 38       | 5.85%   |
| 0x506e3    | 30       | 4.62%   |
| 0x306a9    | 28       | 4.31%   |
| 0x0800820d | 28       | 4.31%   |
| 0x906ea    | 27       | 4.15%   |
| Unknown    | 27       | 4.15%   |
| 0x206a7    | 24       | 3.69%   |
| 0x90672    | 20       | 3.08%   |
| 0x0a50000c | 20       | 3.08%   |
| 0xa0653    | 18       | 2.77%   |
| 0x906e9    | 18       | 2.77%   |
| 0xa0655    | 14       | 2.15%   |
| 0x1067a    | 12       | 1.85%   |
| 0x0a201009 | 12       | 1.85%   |
| 0xa0671    | 11       | 1.69%   |
| 0x08701013 | 10       | 1.54%   |
| 0x08108109 | 10       | 1.54%   |
| 0x306f2    | 9        | 1.38%   |
| 0x0a50000d | 9        | 1.38%   |
| 0x0a201204 | 9        | 1.38%   |
| 0x06000822 | 9        | 1.38%   |
| 0x206d7    | 8        | 1.23%   |
| 0x08001138 | 8        | 1.23%   |
| 0x906ed    | 7        | 1.08%   |
| 0x0a20120a | 7        | 1.08%   |
| 0x0a201205 | 7        | 1.08%   |
| 0x08101016 | 6        | 0.92%   |
| 0x10676    | 5        | 0.77%   |
| 0x08001137 | 5        | 0.77%   |
| 0x90675    | 4        | 0.62%   |
| 0x6fb      | 4        | 0.62%   |
| 0x0a50000b | 4        | 0.62%   |
| 0x906ec    | 3        | 0.46%   |
| 0x906eb    | 3        | 0.46%   |
| 0x20652    | 3        | 0.46%   |
| 0x106e5    | 3        | 0.46%   |
| 0x08600106 | 3        | 0.46%   |
| 0x08008206 | 3        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 114      | 17.59%  |
| Haswell          | 72       | 11.11%  |
| Zen 2            | 70       | 10.8%   |
| KabyLake         | 59       | 9.1%    |
| Zen+             | 44       | 6.79%   |
| Skylake          | 36       | 5.56%   |
| SandyBridge      | 33       | 5.09%   |
| CometLake        | 33       | 5.09%   |
| IvyBridge        | 31       | 4.78%   |
| Zen              | 24       | 3.7%    |
| Alderlake Hybrid | 24       | 3.7%    |
| Penryn           | 19       | 2.93%   |
| Piledriver       | 16       | 2.47%   |
| K10              | 13       | 2.01%   |
| Icelake          | 11       | 1.7%    |
| Westmere         | 7        | 1.08%   |
| Core             | 7        | 1.08%   |
| K8 Hammer        | 5        | 0.77%   |
| Excavator        | 5        | 0.77%   |
| Bulldozer        | 5        | 0.77%   |
| Steamroller      | 4        | 0.62%   |
| Bonnell          | 4        | 0.62%   |
| Unknown          | 4        | 0.62%   |
| Nehalem          | 3        | 0.46%   |
| Tremont          | 1        | 0.15%   |
| Silvermont       | 1        | 0.15%   |
| K10 Llano        | 1        | 0.15%   |
| Jaguar           | 1        | 0.15%   |
| Broadwell        | 1        | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 284      | 40.23%  |
| Nvidia                     | 280      | 39.66%  |
| Intel                      | 140      | 19.83%  |
| Matrox Electronics Systems | 1        | 0.14%   |
| ASPEED Technology          | 1        | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 51       | 7.02%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 31       | 4.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 28       | 3.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 25       | 3.44%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 23       | 3.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 20       | 2.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 16       | 2.2%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 16       | 2.2%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 16       | 2.2%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 13       | 1.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 13       | 1.79%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 12       | 1.65%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 12       | 1.65%   |
| Intel HD Graphics 530                                                       | 12       | 1.65%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 11       | 1.52%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 10       | 1.38%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 10       | 1.38%   |
| Nvidia GK208B [GeForce GT 710]                                              | 10       | 1.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 10       | 1.38%   |
| Intel AlderLake-S GT1                                                       | 10       | 1.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 1.24%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 9        | 1.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 9        | 1.24%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 8        | 1.1%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 8        | 1.1%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 8        | 1.1%    |
| Intel HD Graphics 630                                                       | 7        | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 0.96%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 7        | 0.96%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 6        | 0.83%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 6        | 0.83%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 5        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 5        | 0.69%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 5        | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.69%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 5        | 0.69%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 5        | 0.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 0.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 0.69%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 5        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 255      | 39.23%  |
| 1 x Nvidia      | 251      | 38.62%  |
| 1 x Intel       | 95       | 14.62%  |
| Intel + Nvidia  | 16       | 2.46%   |
| 2 x AMD         | 11       | 1.69%   |
| AMD + Nvidia    | 9        | 1.38%   |
| Intel + AMD     | 7        | 1.08%   |
| 2 x Nvidia      | 3        | 0.46%   |
| Intel + 2 x AMD | 1        | 0.15%   |
| 1 x ASPEED      | 1        | 0.15%   |
| AMD + Matrox    | 1        | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 461      | 70.6%   |
| Proprietary | 167      | 25.57%  |
| Unknown     | 25       | 3.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 205      | 31.16%  |
| 7.01-8.0   | 118      | 17.93%  |
| 3.01-4.0   | 88       | 13.37%  |
| 1.01-2.0   | 80       | 12.16%  |
| 8.01-16.0  | 47       | 7.14%   |
| 0.51-1.0   | 44       | 6.69%   |
| 0.01-0.5   | 40       | 6.08%   |
| 5.01-6.0   | 33       | 5.02%   |
| 2.01-3.0   | 3        | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 105      | 14.34%  |
| Goldstar             | 100      | 13.66%  |
| Dell                 | 81       | 11.07%  |
| AOC                  | 49       | 6.69%   |
| Acer                 | 48       | 6.56%   |
| BenQ                 | 46       | 6.28%   |
| Hewlett-Packard      | 42       | 5.74%   |
| Philips              | 34       | 4.64%   |
| Ancor Communications | 30       | 4.1%    |
| ViewSonic            | 19       | 2.6%    |
| Lenovo               | 18       | 2.46%   |
| ASUSTek Computer     | 18       | 2.46%   |
| Iiyama               | 14       | 1.91%   |
| MSI                  | 12       | 1.64%   |
| Sceptre Tech         | 9        | 1.23%   |
| Gigabyte Technology  | 9        | 1.23%   |
| Vizio                | 6        | 0.82%   |
| Unknown              | 6        | 0.82%   |
| Eizo                 | 6        | 0.82%   |
| Sony                 | 5        | 0.68%   |
| NEC Computers        | 4        | 0.55%   |
| Mi                   | 4        | 0.55%   |
| HUAWEI               | 4        | 0.55%   |
| Medion               | 3        | 0.41%   |
| HannStar             | 3        | 0.41%   |
| Belinea              | 3        | 0.41%   |
| Sharp                | 2        | 0.27%   |
| SGT                  | 2        | 0.27%   |
| RTK                  | 2        | 0.27%   |
| Mitsubishi           | 2        | 0.27%   |
| Marantz              | 2        | 0.27%   |
| Insignia             | 2        | 0.27%   |
| Gateway              | 2        | 0.27%   |
| Fujitsu Siemens      | 2        | 0.27%   |
| Westinghouse         | 1        | 0.14%   |
| VOXICON              | 1        | 0.14%   |
| VIE                  | 1        | 0.14%   |
| Unknown (XXX)        | 1        | 0.14%   |
| SKK                  | 1        | 0.14%   |
| Planar               | 1        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 8        | 1.01%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 7        | 0.89%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 7        | 0.89%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 6        | 0.76%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 5        | 0.63%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 5        | 0.63%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 4        | 0.51%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 4        | 0.51%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4        | 0.51%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                      | 4        | 0.51%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 4        | 0.51%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 4        | 0.51%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4        | 0.51%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 560x300mm 25.0-inch        | 3        | 0.38%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 3        | 0.38%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 3        | 0.38%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 360x300mm 18.4-inch              | 3        | 0.38%   |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch              | 3        | 0.38%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 3        | 0.38%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 3        | 0.38%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 3        | 0.38%   |
| Goldstar 34GN850 GSM774B 3440x1440 800x335mm 34.1-inch                | 3        | 0.38%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch       | 3        | 0.38%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                    | 3        | 0.38%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 3        | 0.38%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 3        | 0.38%   |
| Acer XG270HU ACR0414 2560x1440 597x336mm 27.0-inch                    | 3        | 0.38%   |
| Vizio M65Q6-J09 VIZ1039 3840x2160 1428x803mm 64.5-inch                | 2        | 0.25%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch            | 2        | 0.25%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 2        | 0.25%   |
| Sony TV *00 SNYF303 1920x1080 1218x685mm 55.0-inch                    | 2        | 0.25%   |
| Sceptre Tech E20 SPT080D 1600x900 434x236mm 19.4-inch                 | 2        | 0.25%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 2        | 0.25%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch     | 2        | 0.25%   |
| Samsung Electronics LCD Monitor SAM0C44 3840x2160 950x540mm 43.0-inch | 2        | 0.25%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 2        | 0.25%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch              | 2        | 0.25%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 2        | 0.25%   |
| MSI G27C4 MSI3CA9 1920x1080 598x336mm 27.0-inch                       | 2        | 0.25%   |
| Marantz AVR MJI0031 1920x1080 2210x1250mm 100.0-inch                  | 2        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 340      | 47.82%  |
| 2560x1440 (QHD)    | 96       | 13.5%   |
| 3840x2160 (4K)     | 95       | 13.36%  |
| 3440x1440          | 34       | 4.78%   |
| 1366x768 (WXGA)    | 25       | 3.52%   |
| 1280x1024 (SXGA)   | 22       | 3.09%   |
| 1680x1050 (WSXGA+) | 15       | 2.11%   |
| 1600x900 (HD+)     | 13       | 1.83%   |
| 2560x1080          | 12       | 1.69%   |
| 1920x1200 (WUXGA)  | 12       | 1.69%   |
| 1440x900 (WXGA+)   | 11       | 1.55%   |
| 1360x768           | 8        | 1.13%   |
| 2288x1287          | 6        | 0.84%   |
| 1600x1200          | 5        | 0.7%    |
| 3840x1080          | 4        | 0.56%   |
| 1920x540           | 4        | 0.56%   |
| 2560x1600          | 2        | 0.28%   |
| 1024x768 (XGA)     | 2        | 0.28%   |
| 3840x1600          | 1        | 0.14%   |
| 2200x1650          | 1        | 0.14%   |
| 2160x1200          | 1        | 0.14%   |
| 1640x2048          | 1        | 0.14%   |
| 1400x1050          | 1        | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 158      | 21.29%  |
| 24      | 115      | 15.5%   |
| 23      | 94       | 12.67%  |
| 21      | 94       | 12.67%  |
| 31      | 54       | 7.28%   |
| 34      | 39       | 5.26%   |
| 18      | 29       | 3.91%   |
| 19      | 18       | 2.43%   |
| 22      | 15       | 2.02%   |
| 20      | 15       | 2.02%   |
| Unknown | 13       | 1.75%   |
| 32      | 11       | 1.48%   |
| 17      | 9        | 1.21%   |
| 142     | 6        | 0.81%   |
| 72      | 6        | 0.81%   |
| 84      | 5        | 0.67%   |
| 54      | 5        | 0.67%   |
| 48      | 5        | 0.67%   |
| 42      | 5        | 0.67%   |
| 40      | 5        | 0.67%   |
| 25      | 5        | 0.67%   |
| 52      | 4        | 0.54%   |
| 29      | 3        | 0.4%    |
| 26      | 3        | 0.4%    |
| 15      | 3        | 0.4%    |
| 100     | 2        | 0.27%   |
| 75      | 2        | 0.27%   |
| 69      | 2        | 0.27%   |
| 46      | 2        | 0.27%   |
| 37      | 2        | 0.27%   |
| 35      | 2        | 0.27%   |
| 12      | 2        | 0.27%   |
| 58      | 1        | 0.13%   |
| 49      | 1        | 0.13%   |
| 43      | 1        | 0.13%   |
| 39      | 1        | 0.13%   |
| 38      | 1        | 0.13%   |
| 36      | 1        | 0.13%   |
| 33      | 1        | 0.13%   |
| 28      | 1        | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 327      | 45.93%  |
| 401-500        | 153      | 21.49%  |
| 601-700        | 81       | 11.38%  |
| 701-800        | 52       | 7.3%    |
| 1001-1500      | 17       | 2.39%   |
| 1501-2000      | 15       | 2.11%   |
| 301-350        | 14       | 1.97%   |
| 351-400        | 13       | 1.83%   |
| Unknown        | 13       | 1.83%   |
| 801-900        | 10       | 1.4%    |
| More than 2000 | 8        | 1.12%   |
| 901-1000       | 7        | 0.98%   |
| 201-300        | 2        | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 510      | 77.86%  |
| 16/10   | 52       | 7.94%   |
| 21/9    | 44       | 6.72%   |
| 5/4     | 19       | 2.9%    |
| 4/3     | 9        | 1.37%   |
| 1.00    | 6        | 0.92%   |
| Unknown | 5        | 0.76%   |
| 32/9    | 4        | 0.61%   |
| 6/5     | 3        | 0.46%   |
| 3/2     | 1        | 0.15%   |
| 1.96    | 1        | 0.15%   |
| 0.80    | 1        | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 243      | 33.66%  |
| 301-350        | 160      | 22.16%  |
| 351-500        | 109      | 15.1%   |
| 151-200        | 66       | 9.14%   |
| 251-300        | 37       | 5.12%   |
| More than 1000 | 34       | 4.71%   |
| 141-150        | 32       | 4.43%   |
| 501-1000       | 22       | 3.05%   |
| Unknown        | 13       | 1.8%    |
| 101-110        | 3        | 0.42%   |
| 71-80          | 2        | 0.28%   |
| 81-90          | 1        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 400      | 57.39%  |
| 101-120 | 184      | 26.4%   |
| 121-160 | 43       | 6.17%   |
| 1-50    | 31       | 4.45%   |
| 161-240 | 26       | 3.73%   |
| Unknown | 13       | 1.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 463      | 70.8%   |
| 2     | 144      | 22.02%  |
| 0     | 23       | 3.52%   |
| 3     | 22       | 3.36%   |
| 4     | 2        | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 399      | 41.26%  |
| Intel                             | 367      | 37.95%  |
| Qualcomm Atheros                  | 34       | 3.52%   |
| TP-Link                           | 26       | 2.69%   |
| Broadcom                          | 15       | 1.55%   |
| MediaTek                          | 13       | 1.34%   |
| Ralink                            | 11       | 1.14%   |
| Qualcomm Atheros Communications   | 11       | 1.14%   |
| Microsoft                         | 11       | 1.14%   |
| Ralink Technology                 | 9        | 0.93%   |
| Xiaomi                            | 8        | 0.83%   |
| Nvidia                            | 6        | 0.62%   |
| Aquantia                          | 5        | 0.52%   |
| Mellanox Technologies             | 4        | 0.41%   |
| ASUSTek Computer                  | 4        | 0.41%   |
| ASIX Electronics                  | 4        | 0.41%   |
| Samsung Electronics               | 3        | 0.31%   |
| Marvell Technology Group          | 3        | 0.31%   |
| Edimax Technology                 | 3        | 0.31%   |
| D-Link                            | 3        | 0.31%   |
| Motorola PCS                      | 2        | 0.21%   |
| Apple                             | 2        | 0.21%   |
| Sundance Technology Inc / IC Plus | 1        | 0.1%    |
| STMicroelectronics                | 1        | 0.1%    |
| Sitecom Europe                    | 1        | 0.1%    |
| Sierra Wireless                   | 1        | 0.1%    |
| Qualcomm                          | 1        | 0.1%    |
| QNAP System                       | 1        | 0.1%    |
| PLANEX                            | 1        | 0.1%    |
| NetGear                           | 1        | 0.1%    |
| MicroPython                       | 1        | 0.1%    |
| Microchip Technology              | 1        | 0.1%    |
| LSI                               | 1        | 0.1%    |
| Linksys                           | 1        | 0.1%    |
| Lenovo                            | 1        | 0.1%    |
| InterBiometrics                   | 1        | 0.1%    |
| Huawei Technologies               | 1        | 0.1%    |
| HMD Global                        | 1        | 0.1%    |
| Google                            | 1        | 0.1%    |
| DisplayLink                       | 1        | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 281      | 24.91%  |
| Intel Wi-Fi 6 AX200                                               | 81       | 7.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 69       | 6.12%   |
| Intel I211 Gigabit Network Connection                             | 68       | 6.03%   |
| Intel Ethernet Controller I225-V                                  | 54       | 4.79%   |
| Intel Ethernet Connection (2) I219-V                              | 31       | 2.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 27       | 2.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18       | 1.6%    |
| Intel Ethernet Connection (7) I219-V                              | 16       | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 16       | 1.42%   |
| Intel Ethernet Connection I217-LM                                 | 13       | 1.15%   |
| Intel Ethernet Connection (2) I218-V                              | 12       | 1.06%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 11       | 0.98%   |
| Intel Wireless 7265                                               | 11       | 0.98%   |
| Intel Wireless-AC 9260                                            | 10       | 0.89%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 10       | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                             | 9        | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 8        | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 8        | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                   | 8        | 0.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 0.62%   |
| Intel 82579V Gigabit Network Connection                           | 7        | 0.62%   |
| Intel 82574L Gigabit Network Connection                           | 7        | 0.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6        | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 0.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6        | 0.53%   |
| Microsoft XBOX ACC                                                | 6        | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6        | 0.53%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 6        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5        | 0.44%   |
| TP-Link 802.11ac NIC                                              | 5        | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5        | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 0.44%   |
| Ralink MT7601U Wireless Adapter                                   | 5        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5        | 0.44%   |
| Intel Wireless 7260                                               | 5        | 0.44%   |
| Intel Wireless 3160                                               | 5        | 0.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5        | 0.44%   |
| Intel Ethernet Connection I217-V                                  | 5        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 192      | 50.93%  |
| Realtek Semiconductor           | 61       | 16.18%  |
| TP-Link                         | 26       | 6.9%    |
| Qualcomm Atheros                | 18       | 4.77%   |
| MediaTek                        | 13       | 3.45%   |
| Ralink                          | 11       | 2.92%   |
| Qualcomm Atheros Communications | 11       | 2.92%   |
| Microsoft                       | 11       | 2.92%   |
| Broadcom                        | 10       | 2.65%   |
| Ralink Technology               | 9        | 2.39%   |
| Edimax Technology               | 3        | 0.8%    |
| ASUSTek Computer                | 3        | 0.8%    |
| Sitecom Europe                  | 1        | 0.27%   |
| Sierra Wireless                 | 1        | 0.27%   |
| PLANEX                          | 1        | 0.27%   |
| NetGear                         | 1        | 0.27%   |
| Linksys                         | 1        | 0.27%   |
| D-Link                          | 1        | 0.27%   |
| BUFFALO                         | 1        | 0.27%   |
| Broadcom Limited                | 1        | 0.27%   |
| Belkin Components               | 1        | 0.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 81       | 21.49%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 27       | 7.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 16       | 4.24%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 11       | 2.92%   |
| Intel Wireless 7265                                        | 11       | 2.92%   |
| Intel Wireless-AC 9260                                     | 10       | 2.65%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 10       | 2.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 8        | 2.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 8        | 2.12%   |
| Qualcomm Atheros AR9271 802.11n                            | 8        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 6        | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 6        | 1.59%   |
| Microsoft XBOX ACC                                         | 6        | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                             | 6        | 1.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 6        | 1.59%   |
| TP-Link 802.11ac NIC                                       | 5        | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 5        | 1.33%   |
| Ralink MT7601U Wireless Adapter                            | 5        | 1.33%   |
| Intel Wireless 7260                                        | 5        | 1.33%   |
| Intel Wireless 3160                                        | 5        | 1.33%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 5        | 1.33%   |
| Realtek 802.11ac NIC                                       | 4        | 1.06%   |
| Microsoft Xbox 360 Wireless Adapter                        | 4        | 1.06%   |
| Intel Wireless 8265 / 8275                                 | 4        | 1.06%   |
| Intel Wireless 8260                                        | 4        | 1.06%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 3        | 0.8%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 3        | 0.8%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 3        | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 3        | 0.8%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 3        | 0.8%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 3        | 0.8%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 3        | 0.8%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 3        | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3        | 0.8%    |
| Intel Wireless 3165                                        | 3        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                            | 3        | 0.8%    |
| TP-Link Archer T4U ver.3                                   | 2        | 0.53%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 2        | 0.53%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                        | 2        | 0.53%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 2        | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 374      | 51.73%  |
| Intel                             | 277      | 38.31%  |
| Qualcomm Atheros                  | 19       | 2.63%   |
| Xiaomi                            | 8        | 1.11%   |
| Nvidia                            | 6        | 0.83%   |
| Broadcom                          | 5        | 0.69%   |
| Aquantia                          | 5        | 0.69%   |
| ASIX Electronics                  | 4        | 0.55%   |
| Samsung Electronics               | 3        | 0.41%   |
| Mellanox Technologies             | 3        | 0.41%   |
| Marvell Technology Group          | 3        | 0.41%   |
| Motorola PCS                      | 2        | 0.28%   |
| D-Link                            | 2        | 0.28%   |
| Apple                             | 2        | 0.28%   |
| Sundance Technology Inc / IC Plus | 1        | 0.14%   |
| Qualcomm                          | 1        | 0.14%   |
| QNAP System                       | 1        | 0.14%   |
| Lenovo                            | 1        | 0.14%   |
| HMD Global                        | 1        | 0.14%   |
| Google                            | 1        | 0.14%   |
| DisplayLink                       | 1        | 0.14%   |
| Davicom Semiconductor             | 1        | 0.14%   |
| ASUSTek Computer                  | 1        | 0.14%   |
| ADMtek                            | 1        | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 281      | 37.82%  |
| Realtek RTL8125 2.5GbE Controller                                   | 69       | 9.29%   |
| Intel I211 Gigabit Network Connection                               | 68       | 9.15%   |
| Intel Ethernet Controller I225-V                                    | 54       | 7.27%   |
| Intel Ethernet Connection (2) I219-V                                | 31       | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 18       | 2.42%   |
| Intel Ethernet Connection (7) I219-V                                | 16       | 2.15%   |
| Intel Ethernet Connection I217-LM                                   | 13       | 1.75%   |
| Intel Ethernet Connection (2) I218-V                                | 12       | 1.62%   |
| Intel Ethernet Connection (2) I219-LM                               | 9        | 1.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 7        | 0.94%   |
| Intel 82579V Gigabit Network Connection                             | 7        | 0.94%   |
| Intel 82574L Gigabit Network Connection                             | 7        | 0.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 6        | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 5        | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 5        | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 5        | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 5        | 0.67%   |
| Intel Ethernet Connection I217-V                                    | 5        | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 4        | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                               | 4        | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 4        | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                       | 4        | 0.54%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                | 3        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                       | 3        | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 3        | 0.4%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 3        | 0.4%    |
| Realtek Killer E3000 2.5GbE Controller                              | 3        | 0.4%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 3        | 0.4%    |
| Nvidia MCP61 Ethernet                                               | 3        | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                               | 3        | 0.4%    |
| Intel Ethernet Connection (11) I219-V                               | 3        | 0.4%    |
| Intel Ethernet Connection (11) I219-LM                              | 3        | 0.4%    |
| Intel Ethernet Connection (10) I219-V                               | 3        | 0.4%    |
| Intel 82583V Gigabit Network Connection                             | 3        | 0.4%    |
| Intel 82566DM-2 Gigabit Network Connection                          | 3        | 0.4%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                | 3        | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.27%   |
| Motorola PCS moto g(9) play                                         | 2        | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 641      | 63.47%  |
| WiFi     | 361      | 35.74%  |
| Modem    | 7        | 0.69%   |
| Unknown  | 1        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 491      | 71.78%  |
| WiFi     | 193      | 28.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 338      | 52.16%  |
| 2     | 265      | 40.9%   |
| 3     | 40       | 6.17%   |
| 4     | 3        | 0.46%   |
| 0     | 2        | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 477      | 73.05%  |
| Yes  | 176      | 26.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 180      | 58.25%  |
| Cambridge Silicon Radio         | 48       | 15.53%  |
| Realtek Semiconductor           | 24       | 7.77%   |
| ASUSTek Computer                | 17       | 5.5%    |
| MediaTek                        | 11       | 3.56%   |
| TP-Link                         | 7        | 2.27%   |
| Broadcom                        | 5        | 1.62%   |
| Qualcomm Atheros Communications | 4        | 1.29%   |
| IMC Networks                    | 4        | 1.29%   |
| Apple                           | 3        | 0.97%   |
| Edimax Technology               | 2        | 0.65%   |
| Toshiba                         | 1        | 0.32%   |
| SINO WEALTH                     | 1        | 0.32%   |
| HTC (High Tech Computer)        | 1        | 0.32%   |
| BUFFALO                         | 1        | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 75       | 24.27%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 48       | 15.53%  |
| Intel Bluetooth wireless interface                                   | 28       | 9.06%   |
| Intel AX210 Bluetooth                                                | 25       | 8.09%   |
| Intel AX201 Bluetooth                                                | 21       | 6.8%    |
| Realtek Bluetooth Radio                                              | 17       | 5.5%    |
| Intel Wireless-AC 3168 Bluetooth                                     | 16       | 5.18%   |
| MediaTek Wireless_Device                                             | 11       | 3.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 10       | 3.24%   |
| TP-Link UB500 Adapter                                                | 7        | 2.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 5        | 1.62%   |
| ASUS Bluetooth Radio                                                 | 5        | 1.62%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4        | 1.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4        | 1.29%   |
| ASUS Bluetooth Device                                                | 4        | 1.29%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 3        | 0.97%   |
| Apple Bluetooth USB Host Controller                                  | 3        | 0.97%   |
| Realtek Bluetooth 5.1 Radio                                          | 2        | 0.65%   |
| Edimax Bluetooth Adapter                                             | 2        | 0.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 0.65%   |
| Toshiba Bluetooth USB Host Controller                                | 1        | 0.32%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 1        | 0.32%   |
| Realtek RTL8821A Bluetooth                                           | 1        | 0.32%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 0.32%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.32%   |
| IMC Networks Wireless_Device                                         | 1        | 0.32%   |
| IMC Networks Bluetooth USB Host Controller                           | 1        | 0.32%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.32%   |
| IMC Networks BCM20702A0                                              | 1        | 0.32%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.32%   |
| BUFFALO Bluetooth Radio                                              | 1        | 0.32%   |
| Broadcom HP Portable Bumble Bee                                      | 1        | 0.32%   |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 1        | 0.32%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.32%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.32%   |
| ASUS Bluetooth Adapter                                               | 1        | 0.32%   |
| ASUS BCM20702A0                                                      | 1        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 377      | 29.5%   |
| Intel                                | 336      | 26.29%  |
| Nvidia                               | 275      | 21.52%  |
| C-Media Electronics                  | 47       | 3.68%   |
| Logitech                             | 22       | 1.72%   |
| Creative Labs                        | 13       | 1.02%   |
| Texas Instruments                    | 11       | 0.86%   |
| Corsair                              | 11       | 0.86%   |
| SteelSeries ApS                      | 10       | 0.78%   |
| Kingston Technology                  | 10       | 0.78%   |
| Razer USA                            | 9        | 0.7%    |
| Creative Technology                  | 9        | 0.7%    |
| JMTek                                | 8        | 0.63%   |
| Focusrite-Novation                   | 8        | 0.63%   |
| XMOS                                 | 7        | 0.55%   |
| Generalplus Technology               | 7        | 0.55%   |
| Samson Technologies                  | 6        | 0.47%   |
| ASUSTek Computer                     | 6        | 0.47%   |
| Sony                                 | 5        | 0.39%   |
| Plantronics                          | 5        | 0.39%   |
| Micro Star International             | 5        | 0.39%   |
| Realtek Semiconductor                | 4        | 0.31%   |
| Blue Microphones                     | 4        | 0.31%   |
| Lenovo                               | 3        | 0.23%   |
| GN Netcom                            | 3        | 0.23%   |
| FiiO Electronics Technology          | 3        | 0.23%   |
| Elgato Systems                       | 3        | 0.23%   |
| Dell                                 | 3        | 0.23%   |
| ZOOM                                 | 2        | 0.16%   |
| USB MICROPHONE                       | 2        | 0.16%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.16%   |
| Tenx Technology                      | 2        | 0.16%   |
| Sennheiser Communications            | 2        | 0.16%   |
| Schiit Audio                         | 2        | 0.16%   |
| Samsung Electronics                  | 2        | 0.16%   |
| Native Instruments                   | 2        | 0.16%   |
| KTMicro                              | 2        | 0.16%   |
| GYROCOM C&C                          | 2        | 0.16%   |
| Giga-Byte Technology                 | 2        | 0.16%   |
| FIFINE 683 Microphone                | 2        | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 142      | 9.32%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 70       | 4.6%    |
| AMD Family 17h/19h HD Audio Controller                                     | 53       | 3.48%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 51       | 3.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 49       | 3.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 48       | 3.15%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 38       | 2.5%    |
| Intel 200 Series PCH HD Audio                                              | 36       | 2.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 32       | 2.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 30       | 1.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 29       | 1.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 28       | 1.84%   |
| Intel Alder Lake-S HD Audio Controller                                     | 28       | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 27       | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 26       | 1.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 25       | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 23       | 1.51%   |
| AMD Navi 10 HDMI Audio                                                     | 21       | 1.38%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 21       | 1.38%   |
| Nvidia GP106 High Definition Audio Controller                              | 20       | 1.31%   |
| Nvidia GP104 High Definition Audio Controller                              | 20       | 1.31%   |
| Nvidia GA104 High Definition Audio Controller                              | 20       | 1.31%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 17       | 1.12%   |
| Nvidia GM206 High Definition Audio Controller                              | 16       | 1.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 16       | 1.05%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 16       | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                              | 15       | 0.98%   |
| Intel Comet Lake PCH cAVS                                                  | 15       | 0.98%   |
| Nvidia GM204 High Definition Audio Controller                              | 14       | 0.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 14       | 0.92%   |
| Nvidia GA102 High Definition Audio Controller                              | 11       | 0.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11       | 0.72%   |
| Intel Comet Lake PCH-V cAVS                                                | 11       | 0.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 10       | 0.66%   |
| Nvidia GP108 High Definition Audio Controller                              | 10       | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 10       | 0.66%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 10       | 0.66%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 10       | 0.66%   |
| AMD FCH Azalia Controller                                                  | 10       | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                         | 9        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 61       | 18.71%  |
| Corsair             | 51       | 15.64%  |
| G.Skill             | 43       | 13.19%  |
| Crucial             | 33       | 10.12%  |
| Unknown             | 28       | 8.59%   |
| SK hynix            | 25       | 7.67%   |
| Samsung Electronics | 18       | 5.52%   |
| Micron Technology   | 17       | 5.21%   |
| Patriot             | 10       | 3.07%   |
| A-DATA Technology   | 8        | 2.45%   |
| Team                | 7        | 2.15%   |
| Unknown             | 4        | 1.23%   |
| Nanya Technology    | 3        | 0.92%   |
| PNY                 | 2        | 0.61%   |
| Elpida              | 2        | 0.61%   |
| AMD                 | 2        | 0.61%   |
| V-GeN               | 1        | 0.31%   |
| Smart               | 1        | 0.31%   |
| Silicon Power       | 1        | 0.31%   |
| Samsung 1           | 1        | 0.31%   |
| Ramaxel Technology  | 1        | 0.31%   |
| PUSKILL             | 1        | 0.31%   |
| Mushkin             | 1        | 0.31%   |
| GOODRAM             | 1        | 0.31%   |
| Goldkey             | 1        | 0.31%   |
| Exceleram           | 1        | 0.31%   |
| Atermiter           | 1        | 0.31%   |
| A-TECH              | 1        | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 6        | 1.75%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 6        | 1.75%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 6        | 1.75%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 4        | 1.17%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s      | 4        | 1.17%   |
| Unknown                                                  | 4        | 1.17%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s     | 3        | 0.87%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 3        | 0.87%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 3        | 0.87%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s   | 3        | 0.87%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 3        | 0.87%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 3        | 0.87%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s    | 3        | 0.87%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s    | 3        | 0.87%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 3        | 0.87%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s    | 3        | 0.87%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 3        | 0.87%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                     | 2        | 0.58%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 2        | 0.58%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2        | 0.58%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 2        | 0.58%   |
| Unknown RAM Module 2GB DIMM 400MT/s                      | 2        | 0.58%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s      | 2        | 0.58%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s      | 2        | 0.58%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s     | 2        | 0.58%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s      | 2        | 0.58%   |
| Patriot RAM 2666 C16 Series 8GB DIMM DDR4 2667MT/s       | 2        | 0.58%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 2        | 0.58%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s      | 2        | 0.58%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s      | 2        | 0.58%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 2        | 0.58%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s   | 2        | 0.58%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s     | 2        | 0.58%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 2        | 0.58%   |
| Kingston RAM KF3600C18D4/16GX 16384MB DIMM DDR4 3600MT/s | 2        | 0.58%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 2        | 0.58%   |
| G.Skill RAM F4-3200C14-8GTZR 8GB DIMM DDR4 3200MT/s      | 2        | 0.58%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1867MT/s     | 2        | 0.58%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s    | 2        | 0.58%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s   | 2        | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 191      | 65.86%  |
| DDR3    | 70       | 24.14%  |
| Unknown | 15       | 5.17%   |
| DDR2    | 6        | 2.07%   |
| SDRAM   | 5        | 1.72%   |
| DDR5    | 2        | 0.69%   |
| DDR     | 1        | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 271      | 95.09%  |
| SODIMM | 12       | 4.21%   |
| RIMM   | 2        | 0.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 122      | 40%     |
| 16384 | 79       | 25.9%   |
| 4096  | 51       | 16.72%  |
| 32768 | 24       | 7.87%   |
| 2048  | 22       | 7.21%   |
| 1024  | 7        | 2.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 58       | 18.77%  |
| 1600    | 53       | 17.15%  |
| 3600    | 42       | 13.59%  |
| 2133    | 21       | 6.8%    |
| 2667    | 13       | 4.21%   |
| 1333    | 13       | 4.21%   |
| 2400    | 11       | 3.56%   |
| 3466    | 10       | 3.24%   |
| 3000    | 7        | 2.27%   |
| 1867    | 7        | 2.27%   |
| 3733    | 6        | 1.94%   |
| 3400    | 6        | 1.94%   |
| 2933    | 6        | 1.94%   |
| 2666    | 6        | 1.94%   |
| 3800    | 5        | 1.62%   |
| 800     | 5        | 1.62%   |
| 667     | 5        | 1.62%   |
| 3866    | 4        | 1.29%   |
| 3333    | 3        | 0.97%   |
| 400     | 3        | 0.97%   |
| Unknown | 3        | 0.97%   |
| 4800    | 2        | 0.65%   |
| 3100    | 2        | 0.65%   |
| 2800    | 2        | 0.65%   |
| 1800    | 2        | 0.65%   |
| 49926   | 1        | 0.32%   |
| 5200    | 1        | 0.32%   |
| 3666    | 1        | 0.32%   |
| 3467    | 1        | 0.32%   |
| 2733    | 1        | 0.32%   |
| 2600    | 1        | 0.32%   |
| 2048    | 1        | 0.32%   |
| 1866    | 1        | 0.32%   |
| 1639    | 1        | 0.32%   |
| 1334    | 1        | 0.32%   |
| 1067    | 1        | 0.32%   |
| 1066    | 1        | 0.32%   |
| 333     | 1        | 0.32%   |
| 200     | 1        | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 8        | 30.77%  |
| Brother Industries    | 7        | 26.92%  |
| Canon                 | 3        | 11.54%  |
| Seiko Epson           | 2        | 7.69%   |
| Samsung Electronics   | 2        | 7.69%   |
| Prolific Technology   | 1        | 3.85%   |
| Lexmark International | 1        | 3.85%   |
| Kyocera               | 1        | 3.85%   |
| Graphtec America      | 1        | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson L3110 Series             | 1        | 3.85%   |
| Seiko Epson L300 Series              | 1        | 3.85%   |
| Samsung ML-1640 Series Laser Printer | 1        | 3.85%   |
| Samsung M2070 Series                 | 1        | 3.85%   |
| Prolific PL2305 Parallel Port        | 1        | 3.85%   |
| Lexmark International 2200 series    | 1        | 3.85%   |
| Kyocera ECOSYS M5521cdw              | 1        | 3.85%   |
| HP Officejet 4630 series             | 1        | 3.85%   |
| HP Neverstop Laser 100x              | 1        | 3.85%   |
| HP LaserJet Pro M148-M149            | 1        | 3.85%   |
| HP LaserJet 1150                     | 1        | 3.85%   |
| HP Ink Tank 310 series               | 1        | 3.85%   |
| HP DeskJet 3700 series               | 1        | 3.85%   |
| HP DeskJet 3630 series               | 1        | 3.85%   |
| HP DeskJet 2700 series               | 1        | 3.85%   |
| Graphtec America Graphtec Printer    | 1        | 3.85%   |
| Canon TS3100 series                  | 1        | 3.85%   |
| Canon TR4500 series                  | 1        | 3.85%   |
| Canon CanoScan LiDE 300              | 1        | 3.85%   |
| Brother Printer                      | 1        | 3.85%   |
| Brother MFC-9330CDW                  | 1        | 3.85%   |
| Brother HL-2230 series               | 1        | 3.85%   |
| Brother HL-1110 series               | 1        | 3.85%   |
| Brother DCP-T510W                    | 1        | 3.85%   |
| Brother DCP-L2530DW series           | 1        | 3.85%   |
| Brother DCP-7055W                    | 1        | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 5        | 71.43%  |
| Seiko Epson | 2        | 28.57%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 100                                 | 2        | 28.57%  |
| Seiko Epson GT-X770 [Perfection V500]                   | 1        | 14.29%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 14.29%  |
| Canon CanoScan LiDE 70                                  | 1        | 14.29%  |
| Canon CanoScan LiDE 220                                 | 1        | 14.29%  |
| Canon CanoScan LiDE 200                                 | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 69       | 41.32%  |
| Sunplus Innovation Technology | 14       | 8.38%   |
| Microsoft                     | 13       | 7.78%   |
| Microdia                      | 10       | 5.99%   |
| KYE Systems (Mouse Systems)   | 9        | 5.39%   |
| Apple                         | 7        | 4.19%   |
| Realtek Semiconductor         | 4        | 2.4%    |
| Lenovo                        | 4        | 2.4%    |
| Hewlett-Packard               | 4        | 2.4%    |
| Razer USA                     | 3        | 1.8%    |
| Generalplus Technology        | 3        | 1.8%    |
| Cubeternet                    | 3        | 1.8%    |
| Creative Technology           | 3        | 1.8%    |
| Samsung Electronics           | 2        | 1.2%    |
| Jieli Technology              | 2        | 1.2%    |
| HD 2MP WEBCAM                 | 2        | 1.2%    |
| Chicony Electronics           | 2        | 1.2%    |
| Asuscom Network               | 2        | 1.2%    |
| ARC International             | 2        | 1.2%    |
| YSD-2053--200409              | 1        | 0.6%    |
| Polycom                       | 1        | 0.6%    |
| MacroSilicon                  | 1        | 0.6%    |
| Linux Foundation              | 1        | 0.6%    |
| LG Electronics                | 1        | 0.6%    |
| Intel                         | 1        | 0.6%    |
| Huawei Technologies           | 1        | 0.6%    |
| AVerMedia Technologies        | 1        | 0.6%    |
| Aveo Technology               | 1        | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                | 22       | 13.02%  |
| Logitech Webcam C270                       | 11       | 6.51%   |
| Sunplus HD 720P webcam                     | 6        | 3.55%   |
| Microdia USB 2.0 Camera                    | 5        | 2.96%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 5        | 2.96%   |
| Apple iPhone5/5C/5S/6                      | 5        | 2.96%   |
| Microsoft LifeCam HD-3000                  | 4        | 2.37%   |
| Logitech Webcam C310                       | 4        | 2.37%   |
| Logitech C922 Pro Stream Webcam            | 4        | 2.37%   |
| Microsoft LifeCam Cinema                   | 3        | 1.78%   |
| Microdia Webcam Vitade AF                  | 3        | 1.78%   |
| Logitech Logi 4K Stream Edition            | 3        | 1.78%   |
| Logitech HD Webcam C615                    | 3        | 1.78%   |
| Logitech HD Webcam C525                    | 3        | 1.78%   |
| Logitech C920 PRO HD Webcam                | 3        | 1.78%   |
| Logitech BRIO Ultra HD Webcam              | 3        | 1.78%   |
| Sunplus SPCA2650 AV Camera                 | 2        | 1.18%   |
| Sunplus NexiGo N930AF FHD Webcam           | 2        | 1.18%   |
| Sunplus Aukey-PC-LM1E Camera               | 2        | 1.18%   |
| Samsung Galaxy A5 (MTP)                    | 2        | 1.18%   |
| Realtek USB Camera                         | 2        | 1.18%   |
| Realtek NexiGo N660P FHD Webcam            | 2        | 1.18%   |
| Razer USA Gaming Webcam [Kiyo]             | 2        | 1.18%   |
| Microsoft MicrosoftÂ LifeCam Cinema       | 2        | 1.18%   |
| Logitech Webcam C925e                      | 2        | 1.18%   |
| Logitech QuickCam Pro 9000                 | 2        | 1.18%   |
| Lenovo FHD Webcam Audio                    | 2        | 1.18%   |
| KYE Systems (Mouse Systems) FaceCam 1000X  | 2        | 1.18%   |
| Jieli USB PHY 2.0                          | 2        | 1.18%   |
| HP Webcam HD 2300                          | 2        | 1.18%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                | 2        | 1.18%   |
| Generalplus 2K HD Camera                   | 2        | 1.18%   |
| Creative Live! Cam Sync 1080p V2           | 2        | 1.18%   |
| Asuscom Network Depstech webcam            | 2        | 1.18%   |
| ARC International Camera                   | 2        | 1.18%   |
| YSD-2053--200409 YSD-586                   | 1        | 0.59%   |
| Sunplus Feeltek Full HD Webcam 1080P       | 1        | 0.59%   |
| Sunplus ezcap U3 capture-04                | 1        | 0.59%   |
| Realtek Realtek USB MIC                    | 1        | 0.59%   |
| Razer USA Razer Kiyo Pro                   | 1        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 2        | 28.57%  |
| Yubico.com            | 1        | 14.29%  |
| Realtek Semiconductor | 1        | 14.29%  |
| OmniKey               | 1        | 14.29%  |
| Alcor Micro           | 1        | 14.29%  |
| Aktiv                 | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 2        | 28.57%  |
| Yubico.com Yubikey 4/5 CCID                            | 1        | 14.29%  |
| Realtek Semiconductor Smart Card Reader Interface      | 1        | 14.29%  |
| OmniKey CardMan 1021                                   | 1        | 14.29%  |
| Alcor Micro Watchdata W 1981                           | 1        | 14.29%  |
| Aktiv Rutoken lite                                     | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 545      | 83.21%  |
| 1     | 93       | 14.2%   |
| 2     | 11       | 1.68%   |
| 3     | 4        | 0.61%   |
| 5     | 1        | 0.15%   |
| 4     | 1        | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 46       | 37.7%   |
| Graphics card            | 31       | 25.41%  |
| Multimedia controller    | 10       | 8.2%    |
| Unassigned class         | 7        | 5.74%   |
| Sound                    | 7        | 5.74%   |
| Storage/raid             | 4        | 3.28%   |
| Communication controller | 4        | 3.28%   |
| Camera                   | 4        | 3.28%   |
| Bluetooth                | 3        | 2.46%   |
| Modem                    | 2        | 1.64%   |
| Fingerprint reader       | 2        | 1.64%   |
| Wireless                 | 1        | 0.82%   |
| Firewire controller      | 1        | 0.82%   |

