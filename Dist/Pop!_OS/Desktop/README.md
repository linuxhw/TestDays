Pop!_OS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 6742

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | B650 GAMING PLUS WIFI       | [1ff9c9f7cb](https://linux-hardware.org/?probe=1ff9c9f7cb) | Jan 06, 2025 |
| Gigabyte      | H370M D3H GSM-CF            | [639eb0e4fc](https://linux-hardware.org/?probe=639eb0e4fc) | Jan 05, 2025 |
| Gigabyte      | B650M D3HP                  | [0d0a62d437](https://linux-hardware.org/?probe=0d0a62d437) | Jan 05, 2025 |
| Gigabyte      | B550 UD AC-Y1               | [b5d5a649e6](https://linux-hardware.org/?probe=b5d5a649e6) | Jan 05, 2025 |
| Apple         | Mac-F221BEC8                | [05de585a46](https://linux-hardware.org/?probe=05de585a46) | Jan 04, 2025 |
| Gigabyte      | H370M D3H GSM-CF            | [305c971d23](https://linux-hardware.org/?probe=305c971d23) | Jan 03, 2025 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [e8f18de27b](https://linux-hardware.org/?probe=e8f18de27b) | Jan 03, 2025 |
| ASRock        | B450M/ac                    | [58bf1994a2](https://linux-hardware.org/?probe=58bf1994a2) | Jan 03, 2025 |
| Gigabyte      | B650 AORUS ELITE AX         | [91839e20df](https://linux-hardware.org/?probe=91839e20df) | Jan 03, 2025 |
| ASUSTek       | M5A97 R2.0                  | [7526506dc2](https://linux-hardware.org/?probe=7526506dc2) | Jan 03, 2025 |
| Gigabyte      | B450M DS3H WIFI-CF          | [e91eadd16c](https://linux-hardware.org/?probe=e91eadd16c) | Jan 02, 2025 |
| Gigabyte      | B450 AORUS ELITE            | [849e3021f2](https://linux-hardware.org/?probe=849e3021f2) | Jan 02, 2025 |
| MSI           | B450 TOMAHAWK               | [77e32dabcd](https://linux-hardware.org/?probe=77e32dabcd) | Jan 02, 2025 |
| ASUSTek       | M5A97 R2.0                  | [a15d70317f](https://linux-hardware.org/?probe=a15d70317f) | Jan 01, 2025 |
| ASUSTek       | PRIME B760M-A AX6 II        | [1012b4d63f](https://linux-hardware.org/?probe=1012b4d63f) | Jan 01, 2025 |
| ASUSTek       | PRIME B760M-A AX6 II        | [e3f9df9d9e](https://linux-hardware.org/?probe=e3f9df9d9e) | Jan 01, 2025 |
| MSI           | A68HM GAMING                | [d12ab6c4d3](https://linux-hardware.org/?probe=d12ab6c4d3) | Jan 01, 2025 |
| ASRock        | N68-S UCC                   | [b83c60bccf](https://linux-hardware.org/?probe=b83c60bccf) | Jan 01, 2025 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [079f7f1707](https://linux-hardware.org/?probe=079f7f1707) | Dec 31, 2024 |
| ASRock        | H570M Pro4                  | [ae9219a819](https://linux-hardware.org/?probe=ae9219a819) | Dec 31, 2024 |
| ASRock        | N68-S UCC                   | [e48cfb70c6](https://linux-hardware.org/?probe=e48cfb70c6) | Dec 31, 2024 |
| ASRock        | N68-S UCC                   | [a53617b9d5](https://linux-hardware.org/?probe=a53617b9d5) | Dec 31, 2024 |
| ASRock        | X370 Gaming-ITX/ac          | [f89abca0f9](https://linux-hardware.org/?probe=f89abca0f9) | Dec 29, 2024 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [0e48acaa7e](https://linux-hardware.org/?probe=0e48acaa7e) | Dec 29, 2024 |
| ASUSTek       | Z97-K                       | [53f0c1c555](https://linux-hardware.org/?probe=53f0c1c555) | Dec 29, 2024 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [9fa8931c0b](https://linux-hardware.org/?probe=9fa8931c0b) | Dec 29, 2024 |
| ASUSTek       | F1A75-M-PRO R2.0            | [8485c1ce27](https://linux-hardware.org/?probe=8485c1ce27) | Dec 28, 2024 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [39e50a00e4](https://linux-hardware.org/?probe=39e50a00e4) | Dec 28, 2024 |
| ASUSTek       | M4A87TD EVO                 | [4182d5a5ec](https://linux-hardware.org/?probe=4182d5a5ec) | Dec 28, 2024 |
| HP            | 8265                        | [3b63487fcf](https://linux-hardware.org/?probe=3b63487fcf) | Dec 28, 2024 |
| ASRock        | H110M-HDV                   | [4501aaefe1](https://linux-hardware.org/?probe=4501aaefe1) | Dec 27, 2024 |
| ASRock        | B450 Steel Legend           | [5320a7c488](https://linux-hardware.org/?probe=5320a7c488) | Dec 27, 2024 |
| ASRock        | H110M-HDV                   | [eb488f568b](https://linux-hardware.org/?probe=eb488f568b) | Dec 26, 2024 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [283a58ac15](https://linux-hardware.org/?probe=283a58ac15) | Dec 26, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | [9fcbcdf645](https://linux-hardware.org/?probe=9fcbcdf645) | Dec 26, 2024 |
| Dell          | 0WPMFG A00                  | [32af132170](https://linux-hardware.org/?probe=32af132170) | Dec 25, 2024 |
| Dell          | 0XHGV1 A00                  | [017302e467](https://linux-hardware.org/?probe=017302e467) | Dec 25, 2024 |
| Dell          | 0YF8P5 A00                  | [fab3c1d036](https://linux-hardware.org/?probe=fab3c1d036) | Dec 25, 2024 |
| HP            | 8906 SMVB                   | [7c1ad30996](https://linux-hardware.org/?probe=7c1ad30996) | Dec 25, 2024 |
| MSI           | Z370 GAMING PRO CARBON A... | [46c1540093](https://linux-hardware.org/?probe=46c1540093) | Dec 24, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | [bbae43def0](https://linux-hardware.org/?probe=bbae43def0) | Dec 24, 2024 |
| MSI           | B550-A PRO                  | [dd6260a709](https://linux-hardware.org/?probe=dd6260a709) | Dec 24, 2024 |
| Gigabyte      | Z370P D3-CF                 | [9ea1b90178](https://linux-hardware.org/?probe=9ea1b90178) | Dec 23, 2024 |
| Gigabyte      | A620M DS3H                  | [2993fdb631](https://linux-hardware.org/?probe=2993fdb631) | Dec 23, 2024 |
| HP            | 3396                        | [6e2c93c063](https://linux-hardware.org/?probe=6e2c93c063) | Dec 23, 2024 |
| HP            | 3396                        | [a237d63fa3](https://linux-hardware.org/?probe=a237d63fa3) | Dec 23, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [ca3ac47c6d](https://linux-hardware.org/?probe=ca3ac47c6d) | Dec 23, 2024 |
| Gigabyte      | X570S AERO G                | [f4832ab80c](https://linux-hardware.org/?probe=f4832ab80c) | Dec 23, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [b9260cccc7](https://linux-hardware.org/?probe=b9260cccc7) | Dec 22, 2024 |
| ASUSTek       | B150M-A/M.2                 | [bdb9de439f](https://linux-hardware.org/?probe=bdb9de439f) | Dec 22, 2024 |
| HP            | 3397                        | [d72e973be9](https://linux-hardware.org/?probe=d72e973be9) | Dec 22, 2024 |
| MSI           | B560M-A PRO                 | [814f11f38f](https://linux-hardware.org/?probe=814f11f38f) | Dec 22, 2024 |
| ASRock        | X670E PG Lightning          | [a87b7ceb23](https://linux-hardware.org/?probe=a87b7ceb23) | Dec 22, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [c0bbc9c576](https://linux-hardware.org/?probe=c0bbc9c576) | Dec 22, 2024 |
| Unknown       | X99-D8                      | [0bd81498ad](https://linux-hardware.org/?probe=0bd81498ad) | Dec 21, 2024 |
| ECS           | H61H2-M6                    | [ee83334d6e](https://linux-hardware.org/?probe=ee83334d6e) | Dec 21, 2024 |
| ASUSTek       | B150M-A/M.2                 | [58579615c1](https://linux-hardware.org/?probe=58579615c1) | Dec 20, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c83a325000](https://linux-hardware.org/?probe=c83a325000) | Dec 20, 2024 |
| ASRock        | 970 Extreme3 R2.0           | [cc8e8b062c](https://linux-hardware.org/?probe=cc8e8b062c) | Dec 19, 2024 |
| Gigabyte      | B550 GAMING X               | [5e7733d216](https://linux-hardware.org/?probe=5e7733d216) | Dec 19, 2024 |
| MSI           | B150 GAMING M3              | [eb7d688010](https://linux-hardware.org/?probe=eb7d688010) | Dec 18, 2024 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [475c698644](https://linux-hardware.org/?probe=475c698644) | Dec 18, 2024 |
| MSI           | Z370 GAMING PRO CARBON      | [3b9ab5404e](https://linux-hardware.org/?probe=3b9ab5404e) | Dec 17, 2024 |
| ASUSTek       | Z77-A                       | [905b20309d](https://linux-hardware.org/?probe=905b20309d) | Dec 17, 2024 |
| MSI           | MPG Z690 FORCE WIFI         | [67fda65f1a](https://linux-hardware.org/?probe=67fda65f1a) | Dec 16, 2024 |
| JGINYUE       | B650I Night Devil Ver:      | [d98b74d533](https://linux-hardware.org/?probe=d98b74d533) | Dec 15, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [ea5d5a1d8f](https://linux-hardware.org/?probe=ea5d5a1d8f) | Dec 14, 2024 |
| ASUSTek       | PRIME Z270-A                | [5af9a6f758](https://linux-hardware.org/?probe=5af9a6f758) | Dec 14, 2024 |
| Biostar       | A520MH                      | [46f468d23e](https://linux-hardware.org/?probe=46f468d23e) | Dec 14, 2024 |
| Gigabyte      | Z590 VISION D               | [e51c407f40](https://linux-hardware.org/?probe=e51c407f40) | Dec 14, 2024 |
| ASUSTek       | Maximus IX HERO             | [277adb5291](https://linux-hardware.org/?probe=277adb5291) | Dec 14, 2024 |
| Gigabyte      | X870 GAMING X WIFI7         | [bf3a0594a1](https://linux-hardware.org/?probe=bf3a0594a1) | Dec 14, 2024 |
| Lenovo        | 0B98401 PRO                 | [fbf5a87269](https://linux-hardware.org/?probe=fbf5a87269) | Dec 14, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS        | [d46d8a8dc1](https://linux-hardware.org/?probe=d46d8a8dc1) | Dec 13, 2024 |
| Alienware     | 0K9TKY A00                  | [02f928f245](https://linux-hardware.org/?probe=02f928f245) | Dec 13, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [bc4af2a098](https://linux-hardware.org/?probe=bc4af2a098) | Dec 12, 2024 |
| Gigabyte      | B650 EAGLE                  | [b7d5b664b5](https://linux-hardware.org/?probe=b7d5b664b5) | Dec 12, 2024 |
| System76      | Thelio thelio-r2            | [7a66bf9502](https://linux-hardware.org/?probe=7a66bf9502) | Dec 12, 2024 |
| ASUSTek       | Z97-K                       | [8096f8f1b6](https://linux-hardware.org/?probe=8096f8f1b6) | Dec 12, 2024 |
| ASUSTek       | M5A97 R2.0                  | [e0157671c5](https://linux-hardware.org/?probe=e0157671c5) | Dec 12, 2024 |
| ASRock        | 970 Extreme3 R2.0           | [9fa51abc19](https://linux-hardware.org/?probe=9fa51abc19) | Dec 11, 2024 |
| Acer          | Aspire X3960                | [7bc5a0a910](https://linux-hardware.org/?probe=7bc5a0a910) | Dec 11, 2024 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [4caf21526d](https://linux-hardware.org/?probe=4caf21526d) | Dec 11, 2024 |
| Gigabyte      | G41M-ES2L                   | [ff47572b6b](https://linux-hardware.org/?probe=ff47572b6b) | Dec 11, 2024 |
| Gigabyte      | X870 EAGLE WIFI7            | [9d8f1f5a1c](https://linux-hardware.org/?probe=9d8f1f5a1c) | Dec 11, 2024 |
| Dell          | 09KPNV A01                  | [157ad19f93](https://linux-hardware.org/?probe=157ad19f93) | Dec 11, 2024 |
| MSI           | Z270 SLI PLUS               | [4bd957e3ec](https://linux-hardware.org/?probe=4bd957e3ec) | Dec 10, 2024 |
| Dell          | 0478VN A00                  | [86908e3156](https://linux-hardware.org/?probe=86908e3156) | Dec 09, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [7305cf039c](https://linux-hardware.org/?probe=7305cf039c) | Dec 09, 2024 |
| ASRock        | H610M-ITX/eDP               | [75e26c7c07](https://linux-hardware.org/?probe=75e26c7c07) | Dec 09, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [d873aaad11](https://linux-hardware.org/?probe=d873aaad11) | Dec 09, 2024 |
| AZW           | MINI S                      | [a82e287e6c](https://linux-hardware.org/?probe=a82e287e6c) | Dec 09, 2024 |
| ASRock        | H610M-ITX/eDP               | [e9eed28958](https://linux-hardware.org/?probe=e9eed28958) | Dec 09, 2024 |
| Supermicro    | X9DRD-iF                    | [f90d8dfc09](https://linux-hardware.org/?probe=f90d8dfc09) | Dec 08, 2024 |
| ASUSTek       | PRIME H270-PLUS             | [79abd0b864](https://linux-hardware.org/?probe=79abd0b864) | Dec 08, 2024 |
| ASUSTek       | ROG Maximus X HERO          | [13abb368c7](https://linux-hardware.org/?probe=13abb368c7) | Dec 08, 2024 |
| ASUSTek       | B150M-C                     | [0e25bdfd87](https://linux-hardware.org/?probe=0e25bdfd87) | Dec 07, 2024 |
| MSI           | MPG B650I EDGE WIFI         | [15ceab731a](https://linux-hardware.org/?probe=15ceab731a) | Dec 07, 2024 |
| Supermicro    | X9DRD-iF                    | [24c2ea7bbd](https://linux-hardware.org/?probe=24c2ea7bbd) | Dec 07, 2024 |
| ASUSTek       | P8P67 PRO                   | [89c4ef1413](https://linux-hardware.org/?probe=89c4ef1413) | Dec 07, 2024 |
| ASUSTek       | P8P67 PRO                   | [40751025a5](https://linux-hardware.org/?probe=40751025a5) | Dec 07, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | [741eb16cb4](https://linux-hardware.org/?probe=741eb16cb4) | Dec 07, 2024 |
| ASRock        | B450M Pro4                  | [780d8477b4](https://linux-hardware.org/?probe=780d8477b4) | Dec 07, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [4b14a65ae5](https://linux-hardware.org/?probe=4b14a65ae5) | Dec 07, 2024 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [e25da0298a](https://linux-hardware.org/?probe=e25da0298a) | Dec 06, 2024 |
| MSI           | PRO Z790-A WIFI             | [386b5bb2fa](https://linux-hardware.org/?probe=386b5bb2fa) | Dec 06, 2024 |
| Gigabyte      | Z390 AORUS PRO-CF           | [c28dd5c7ab](https://linux-hardware.org/?probe=c28dd5c7ab) | Dec 05, 2024 |
| Intel         | B75                         | [69a652cb51](https://linux-hardware.org/?probe=69a652cb51) | Dec 05, 2024 |
| Gigabyte      | Z170-Gaming K3              | [eb3f1d8587](https://linux-hardware.org/?probe=eb3f1d8587) | Dec 05, 2024 |
| Dell          | 0GY6Y8 A02                  | [315414ee85](https://linux-hardware.org/?probe=315414ee85) | Dec 05, 2024 |
| Dell          | 0GY6Y8 A02                  | [91d86a1a29](https://linux-hardware.org/?probe=91d86a1a29) | Dec 05, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [38917bc287](https://linux-hardware.org/?probe=38917bc287) | Dec 04, 2024 |
| Dell          | 09KPNV A00                  | [954003dcdc](https://linux-hardware.org/?probe=954003dcdc) | Dec 04, 2024 |
| ASRock        | X570 Taichi                 | [095dc95b9d](https://linux-hardware.org/?probe=095dc95b9d) | Dec 04, 2024 |
| MSI           | MPG B650I EDGE WIFI         | [b1cf6cfea9](https://linux-hardware.org/?probe=b1cf6cfea9) | Dec 04, 2024 |
| Gigabyte      | X870 EAGLE WIFI7            | [4178f34632](https://linux-hardware.org/?probe=4178f34632) | Dec 04, 2024 |
| MSI           | MPG Z690 FORCE WIFI         | [eea3d584af](https://linux-hardware.org/?probe=eea3d584af) | Dec 04, 2024 |
| Positivo      | POS-EIH61CQ                 | [d4fad86c11](https://linux-hardware.org/?probe=d4fad86c11) | Dec 04, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [23325c9670](https://linux-hardware.org/?probe=23325c9670) | Dec 03, 2024 |
| ASUSTek       | PRIME B350M-K               | [8e7c6af74e](https://linux-hardware.org/?probe=8e7c6af74e) | Dec 03, 2024 |
| HP            | 1905                        | [925e9c6a14](https://linux-hardware.org/?probe=925e9c6a14) | Dec 03, 2024 |
| ASUSTek       | PRIME B350M-A               | [3b2b2cdb80](https://linux-hardware.org/?probe=3b2b2cdb80) | Dec 03, 2024 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [898f745e60](https://linux-hardware.org/?probe=898f745e60) | Dec 03, 2024 |
| ASRock        | B450M Steel Legend          | [b4a0a64ac0](https://linux-hardware.org/?probe=b4a0a64ac0) | Dec 03, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | [303b3a510d](https://linux-hardware.org/?probe=303b3a510d) | Dec 02, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | [98f50b0d90](https://linux-hardware.org/?probe=98f50b0d90) | Dec 02, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [ad5a11492c](https://linux-hardware.org/?probe=ad5a11492c) | Dec 02, 2024 |
| ASUSTek       | PRIME B760M-A AX6 II        | [66cdfbda88](https://linux-hardware.org/?probe=66cdfbda88) | Dec 02, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | [d71db12c0a](https://linux-hardware.org/?probe=d71db12c0a) | Dec 02, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | [6c84ee4665](https://linux-hardware.org/?probe=6c84ee4665) | Dec 01, 2024 |
| ASUSTek       | P6T DELUXE V2               | [fa59a3d752](https://linux-hardware.org/?probe=fa59a3d752) | Dec 01, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [6ba50b8196](https://linux-hardware.org/?probe=6ba50b8196) | Dec 01, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [882e0e49e0](https://linux-hardware.org/?probe=882e0e49e0) | Dec 01, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS       | [b2a46b17d9](https://linux-hardware.org/?probe=b2a46b17d9) | Dec 01, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [cfe2d2980e](https://linux-hardware.org/?probe=cfe2d2980e) | Dec 01, 2024 |
| HP            | 1905                        | [a3ed3e5797](https://linux-hardware.org/?probe=a3ed3e5797) | Dec 01, 2024 |
| MSI           | B550 GAMING GEN3            | [7f2c1251c1](https://linux-hardware.org/?probe=7f2c1251c1) | Dec 01, 2024 |
| Shenzhen M... | RPBNB                       | [471e0eae44](https://linux-hardware.org/?probe=471e0eae44) | Nov 30, 2024 |
| Dell          | 0VHWTR A02                  | [0295b5d88e](https://linux-hardware.org/?probe=0295b5d88e) | Nov 30, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [be0716093f](https://linux-hardware.org/?probe=be0716093f) | Nov 30, 2024 |
| AZW           | MINI S                      | [b21eaf0955](https://linux-hardware.org/?probe=b21eaf0955) | Nov 29, 2024 |
| ASRock        | B550 Phantom Gaming 4       | [8351202a05](https://linux-hardware.org/?probe=8351202a05) | Nov 28, 2024 |
| HP            | 18E6                        | [8ff866b586](https://linux-hardware.org/?probe=8ff866b586) | Nov 28, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [0cfba5ec43](https://linux-hardware.org/?probe=0cfba5ec43) | Nov 27, 2024 |
| ASUSTek       | P5Q-WS                      | [9c1be46138](https://linux-hardware.org/?probe=9c1be46138) | Nov 27, 2024 |
| Gigabyte      | Z97X-Gaming 7               | [66ed7c3731](https://linux-hardware.org/?probe=66ed7c3731) | Nov 26, 2024 |
| ASUSTek       | PRIME Z790-V AX             | [e3dda3c505](https://linux-hardware.org/?probe=e3dda3c505) | Nov 26, 2024 |
| MSI           | H270-A PRO                  | [e2974172be](https://linux-hardware.org/?probe=e2974172be) | Nov 25, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [4f62376d84](https://linux-hardware.org/?probe=4f62376d84) | Nov 25, 2024 |
| Dell          | 0VHWTR A02                  | [c23095586a](https://linux-hardware.org/?probe=c23095586a) | Nov 24, 2024 |
| MSI           | H270-A PRO                  | [554c3ad6a6](https://linux-hardware.org/?probe=554c3ad6a6) | Nov 23, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ffd1398e1b](https://linux-hardware.org/?probe=ffd1398e1b) | Nov 23, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5233943083](https://linux-hardware.org/?probe=5233943083) | Nov 22, 2024 |
| ASUSTek       | PRIME B450M-A               | [79597758d9](https://linux-hardware.org/?probe=79597758d9) | Nov 22, 2024 |
| ASRock        | 970 Extreme3 R2.0           | [3c75cf4004](https://linux-hardware.org/?probe=3c75cf4004) | Nov 21, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | [0b7cd81ab1](https://linux-hardware.org/?probe=0b7cd81ab1) | Nov 21, 2024 |
| Gigabyte      | B75M-D3H                    | [f4e6dc4230](https://linux-hardware.org/?probe=f4e6dc4230) | Nov 21, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [d9fa077e13](https://linux-hardware.org/?probe=d9fa077e13) | Nov 19, 2024 |
| ASRock        | X670E PG Lightning          | [07a38ec669](https://linux-hardware.org/?probe=07a38ec669) | Nov 19, 2024 |
| MSI           | H61M-P31                    | [0209ef23d5](https://linux-hardware.org/?probe=0209ef23d5) | Nov 19, 2024 |
| MSI           | H61M-P31                    | [6ff594d173](https://linux-hardware.org/?probe=6ff594d173) | Nov 18, 2024 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [896963442d](https://linux-hardware.org/?probe=896963442d) | Nov 18, 2024 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [5590d9581e](https://linux-hardware.org/?probe=5590d9581e) | Nov 18, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [56a3f6ca37](https://linux-hardware.org/?probe=56a3f6ca37) | Nov 18, 2024 |
| Dell          | 0VHWTR A02                  | [c4fd80459e](https://linux-hardware.org/?probe=c4fd80459e) | Nov 17, 2024 |
| ASRock        | X670E PG Lightning          | [0db2e7e64c](https://linux-hardware.org/?probe=0db2e7e64c) | Nov 17, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [2c5311e308](https://linux-hardware.org/?probe=2c5311e308) | Nov 17, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [ff04745822](https://linux-hardware.org/?probe=ff04745822) | Nov 16, 2024 |
| MSI           | PRO Z790-A WIFI             | [0c8044a2d4](https://linux-hardware.org/?probe=0c8044a2d4) | Nov 16, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [d13f4015bb](https://linux-hardware.org/?probe=d13f4015bb) | Nov 15, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [fc1124cd18](https://linux-hardware.org/?probe=fc1124cd18) | Nov 15, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [054b123f91](https://linux-hardware.org/?probe=054b123f91) | Nov 15, 2024 |
| ASUSTek       | M3A                         | [d3f42b3ab8](https://linux-hardware.org/?probe=d3f42b3ab8) | Nov 15, 2024 |
| Dell          | 0YF8P5 A00                  | [e42cce2813](https://linux-hardware.org/?probe=e42cce2813) | Nov 15, 2024 |
| ASUSTek       | PRIME B450M-A               | [792208442b](https://linux-hardware.org/?probe=792208442b) | Nov 14, 2024 |
| MSI           | MPG Z690 CARBON WIFI        | [7c566f5d03](https://linux-hardware.org/?probe=7c566f5d03) | Nov 14, 2024 |
| Dell          | 0YF8P5 A00                  | [e872037135](https://linux-hardware.org/?probe=e872037135) | Nov 14, 2024 |
| ASUSTek       | P8Z77-V LX2                 | [482dd6b939](https://linux-hardware.org/?probe=482dd6b939) | Nov 14, 2024 |
| AZW           | MINI S                      | [16e41e32ed](https://linux-hardware.org/?probe=16e41e32ed) | Nov 14, 2024 |
| AZW           | MINI S                      | [b766d78b0f](https://linux-hardware.org/?probe=b766d78b0f) | Nov 14, 2024 |
| Dell          | 0D4MD1 A00                  | [8a55c02e08](https://linux-hardware.org/?probe=8a55c02e08) | Nov 12, 2024 |
| HC Technol... | HCAR5000-MI                 | [3d0f0dc3a3](https://linux-hardware.org/?probe=3d0f0dc3a3) | Nov 11, 2024 |
| MSI           | Z270 SLI PLUS               | [ed80f0f9d6](https://linux-hardware.org/?probe=ed80f0f9d6) | Nov 11, 2024 |
| ASUSTek       | B85M-G                      | [83854ceaa7](https://linux-hardware.org/?probe=83854ceaa7) | Nov 10, 2024 |
| Gigabyte      | B650 GAMING X AX V2         | [06e904448b](https://linux-hardware.org/?probe=06e904448b) | Nov 09, 2024 |
| Intel         | X99H                        | [5e31d210ca](https://linux-hardware.org/?probe=5e31d210ca) | Nov 09, 2024 |
| Gigabyte      | B550 UD AC                  | [844ce5e614](https://linux-hardware.org/?probe=844ce5e614) | Nov 09, 2024 |
| Gigabyte      | B650 GAMING X AX V2         | [747035fcc0](https://linux-hardware.org/?probe=747035fcc0) | Nov 09, 2024 |
| ASUSTek       | PRIME A520M-K               | [3c0fea8e9f](https://linux-hardware.org/?probe=3c0fea8e9f) | Nov 09, 2024 |
| Intel         | DH61BF AAG81311-102         | [fa09fae0e6](https://linux-hardware.org/?probe=fa09fae0e6) | Nov 08, 2024 |
| MSI           | PRO B660-A DDR4             | [723518a192](https://linux-hardware.org/?probe=723518a192) | Nov 08, 2024 |
| Dell          | 0HY9JP A00                  | [ba793c9a96](https://linux-hardware.org/?probe=ba793c9a96) | Nov 07, 2024 |
| Gigabyte      | X870 GAMING WIFI6           | [92957f360a](https://linux-hardware.org/?probe=92957f360a) | Nov 06, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [c53cffc662](https://linux-hardware.org/?probe=c53cffc662) | Nov 06, 2024 |
| ASRock        | B650 LiveMixer              | [312b0972f7](https://linux-hardware.org/?probe=312b0972f7) | Nov 06, 2024 |
| ASUSTek       | PRIME Z790-V AX             | [24710cb98a](https://linux-hardware.org/?probe=24710cb98a) | Nov 06, 2024 |
| ASUSTek       | PRIME Z790-V AX             | [3d09c0f78f](https://linux-hardware.org/?probe=3d09c0f78f) | Nov 06, 2024 |
| ASUSTek       | PRIME B360M-A               | [45d0b46228](https://linux-hardware.org/?probe=45d0b46228) | Nov 06, 2024 |
| ASUSTek       | P7P55D-E                    | [e6cddc3d72](https://linux-hardware.org/?probe=e6cddc3d72) | Nov 05, 2024 |
| Dell          | 0RCPW3 A03                  | [dff53af38f](https://linux-hardware.org/?probe=dff53af38f) | Nov 05, 2024 |
| ASRock        | H87 Performance             | [5680ba8d20](https://linux-hardware.org/?probe=5680ba8d20) | Nov 04, 2024 |
| HP            | 2129                        | [0a6a53a99f](https://linux-hardware.org/?probe=0a6a53a99f) | Nov 04, 2024 |
| ASUSTek       | CM6870                      | [bb5ceef12d](https://linux-hardware.org/?probe=bb5ceef12d) | Nov 04, 2024 |
| Dell          | 0VHWTR A02                  | [0510510273](https://linux-hardware.org/?probe=0510510273) | Nov 03, 2024 |
| Dell          | 0JP3NX A01                  | [44c5885090](https://linux-hardware.org/?probe=44c5885090) | Nov 02, 2024 |
| Biostar       | A780L                       | [9fbbe8bb22](https://linux-hardware.org/?probe=9fbbe8bb22) | Nov 02, 2024 |
| Intel         | X99 V1.0                    | [41c10ad1c4](https://linux-hardware.org/?probe=41c10ad1c4) | Nov 01, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [07c831fabd](https://linux-hardware.org/?probe=07c831fabd) | Nov 01, 2024 |
| Intel         | X99                         | [1090396c96](https://linux-hardware.org/?probe=1090396c96) | Oct 31, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [fe5d53b473](https://linux-hardware.org/?probe=fe5d53b473) | Oct 31, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [99224e2693](https://linux-hardware.org/?probe=99224e2693) | Oct 31, 2024 |
| Dell          | 0D4MD1 A00                  | [ba7413667b](https://linux-hardware.org/?probe=ba7413667b) | Oct 31, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [df33da1aff](https://linux-hardware.org/?probe=df33da1aff) | Oct 30, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | [fc46ea6344](https://linux-hardware.org/?probe=fc46ea6344) | Oct 29, 2024 |
| Dell          | 07T4MC A09                  | [e6f3a1ec08](https://linux-hardware.org/?probe=e6f3a1ec08) | Oct 29, 2024 |
| ASUSTek       | PRIME A320M-K               | [1f16dfb5a7](https://linux-hardware.org/?probe=1f16dfb5a7) | Oct 29, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [6ba1445c64](https://linux-hardware.org/?probe=6ba1445c64) | Oct 29, 2024 |
| ASUSTek       | P8Z77-V LE PLUS             | [34c1bd3c07](https://linux-hardware.org/?probe=34c1bd3c07) | Oct 29, 2024 |
| Gigabyte      | B450 AORUS M                | [028685c0a9](https://linux-hardware.org/?probe=028685c0a9) | Oct 26, 2024 |
| Gigabyte      | G41M-Combo                  | [4ddd0f69f1](https://linux-hardware.org/?probe=4ddd0f69f1) | Oct 26, 2024 |
| Gigabyte      | G41M-Combo                  | [0fb81a0008](https://linux-hardware.org/?probe=0fb81a0008) | Oct 26, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | [bfa95cffa8](https://linux-hardware.org/?probe=bfa95cffa8) | Oct 26, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [9be6f0ffd0](https://linux-hardware.org/?probe=9be6f0ffd0) | Oct 25, 2024 |
| Intel         | DH77EB AAG39073-304         | [260a0dccc2](https://linux-hardware.org/?probe=260a0dccc2) | Oct 25, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | [424bbe5529](https://linux-hardware.org/?probe=424bbe5529) | Oct 25, 2024 |
| TB            | WTR R1                      | [deb31354cb](https://linux-hardware.org/?probe=deb31354cb) | Oct 25, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [d013c75bc0](https://linux-hardware.org/?probe=d013c75bc0) | Oct 25, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | [ec5c700007](https://linux-hardware.org/?probe=ec5c700007) | Oct 24, 2024 |
| Dell          | 0K240Y A01                  | [0c8041b514](https://linux-hardware.org/?probe=0c8041b514) | Oct 24, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [51e502d243](https://linux-hardware.org/?probe=51e502d243) | Oct 24, 2024 |
| Gigabyte      | B75M-D3H                    | [833b93b860](https://linux-hardware.org/?probe=833b93b860) | Oct 23, 2024 |
| ASUSTek       | PRIME H310M-K R2.0          | [3c7f38442a](https://linux-hardware.org/?probe=3c7f38442a) | Oct 23, 2024 |
| Gigabyte      | H370M D3H GSM-CF            | [069580c3b2](https://linux-hardware.org/?probe=069580c3b2) | Oct 22, 2024 |
| ASRock        | B450M Steel Legend          | [4710ecffdc](https://linux-hardware.org/?probe=4710ecffdc) | Oct 22, 2024 |
| ASRock        | B450M Steel Legend          | [841c88c37f](https://linux-hardware.org/?probe=841c88c37f) | Oct 22, 2024 |
| TB            | WTR R1                      | [77199b6dc7](https://linux-hardware.org/?probe=77199b6dc7) | Oct 21, 2024 |
| ASRock        | 970 Extreme3 R2.0           | [1fcb0f751e](https://linux-hardware.org/?probe=1fcb0f751e) | Oct 21, 2024 |
| MSI           | X99S XPOWER AC              | [b089ed1300](https://linux-hardware.org/?probe=b089ed1300) | Oct 20, 2024 |
| ASRock        | B760M PG Riptide            | [dffb37693f](https://linux-hardware.org/?probe=dffb37693f) | Oct 20, 2024 |
| Unknown       | Unknown                     | [1380476f1e](https://linux-hardware.org/?probe=1380476f1e) | Oct 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bd85cf1a79](https://linux-hardware.org/?probe=bd85cf1a79) | Oct 19, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b4ee7a4976](https://linux-hardware.org/?probe=b4ee7a4976) | Oct 19, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [519c6c9fce](https://linux-hardware.org/?probe=519c6c9fce) | Oct 19, 2024 |
| Biostar       | A780L                       | [ce27f19033](https://linux-hardware.org/?probe=ce27f19033) | Oct 19, 2024 |
| Gigabyte      | GA-990FXA-UD3               | [ad76756fd0](https://linux-hardware.org/?probe=ad76756fd0) | Oct 19, 2024 |
| MSI           | PRO B650-P WIFI             | [19d2539e75](https://linux-hardware.org/?probe=19d2539e75) | Oct 19, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [0b40a221ac](https://linux-hardware.org/?probe=0b40a221ac) | Oct 18, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [5dca39ff49](https://linux-hardware.org/?probe=5dca39ff49) | Oct 17, 2024 |
| Intel         | X99                         | [057dc6ac9f](https://linux-hardware.org/?probe=057dc6ac9f) | Oct 17, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [bc04563516](https://linux-hardware.org/?probe=bc04563516) | Oct 17, 2024 |
| MSI           | H110M PRO-VH PLUS           | [a10a4ae8fa](https://linux-hardware.org/?probe=a10a4ae8fa) | Oct 17, 2024 |
| HP            | 802F                        | [5553cbd4ca](https://linux-hardware.org/?probe=5553cbd4ca) | Oct 17, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5d46c792d0](https://linux-hardware.org/?probe=5d46c792d0) | Oct 17, 2024 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [0a10d42a20](https://linux-hardware.org/?probe=0a10d42a20) | Oct 16, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [637bebb3f3](https://linux-hardware.org/?probe=637bebb3f3) | Oct 16, 2024 |
| Gigabyte      | Z490 GAMING X AX            | [e726c70ed6](https://linux-hardware.org/?probe=e726c70ed6) | Oct 16, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [76a70beb84](https://linux-hardware.org/?probe=76a70beb84) | Oct 16, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [1d18778ca6](https://linux-hardware.org/?probe=1d18778ca6) | Oct 15, 2024 |
| Gigabyte      | X570S AORUS MASTER          | [30fd511ed4](https://linux-hardware.org/?probe=30fd511ed4) | Oct 15, 2024 |
| MSI           | H110M PRO-VH PLUS           | [fdd792f39b](https://linux-hardware.org/?probe=fdd792f39b) | Oct 15, 2024 |
| ASRock        | B550 Taichi Razer Editio... | [6a3e9babae](https://linux-hardware.org/?probe=6a3e9babae) | Oct 15, 2024 |
| ASRock        | B550 Taichi Razer Editio... | [abd8353fc1](https://linux-hardware.org/?probe=abd8353fc1) | Oct 15, 2024 |
| MSI           | H310-F PRO                  | [96e06666bd](https://linux-hardware.org/?probe=96e06666bd) | Oct 15, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [4ab8dafc86](https://linux-hardware.org/?probe=4ab8dafc86) | Oct 14, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | [8fabff367d](https://linux-hardware.org/?probe=8fabff367d) | Oct 14, 2024 |
| ASRock        | B760M PG Riptide            | [f4e8c2acd6](https://linux-hardware.org/?probe=f4e8c2acd6) | Oct 14, 2024 |
| Koloe         | X58                         | [53ff53a4cc](https://linux-hardware.org/?probe=53ff53a4cc) | Oct 14, 2024 |
| ASUSTek       | Maximus VIII HERO           | [cc3ba34210](https://linux-hardware.org/?probe=cc3ba34210) | Oct 13, 2024 |
| ASUSTek       | PRIME X570-P                | [beeb197b20](https://linux-hardware.org/?probe=beeb197b20) | Oct 13, 2024 |
| ASRock        | AB350M-HDV R3.0             | [0caee97f69](https://linux-hardware.org/?probe=0caee97f69) | Oct 13, 2024 |
| Dell          | 0CU409                      | [674f7bd1a1](https://linux-hardware.org/?probe=674f7bd1a1) | Oct 13, 2024 |
| Alienware     | 0N4R4N A00                  | [0cfa6f6b4b](https://linux-hardware.org/?probe=0cfa6f6b4b) | Oct 13, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [ec7fc07772](https://linux-hardware.org/?probe=ec7fc07772) | Oct 13, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | [24c4bcf3e5](https://linux-hardware.org/?probe=24c4bcf3e5) | Oct 13, 2024 |
| MSI           | MS-B9351                    | [9ab378024d](https://linux-hardware.org/?probe=9ab378024d) | Oct 13, 2024 |
| MSI           | MPG X570 GAMING PRO CARB... | [ce0e497ca9](https://linux-hardware.org/?probe=ce0e497ca9) | Oct 12, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [700a309817](https://linux-hardware.org/?probe=700a309817) | Oct 12, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [57aa3bcdd4](https://linux-hardware.org/?probe=57aa3bcdd4) | Oct 12, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [685ba31b0b](https://linux-hardware.org/?probe=685ba31b0b) | Oct 10, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | [7b955e70d1](https://linux-hardware.org/?probe=7b955e70d1) | Oct 10, 2024 |
| ASUSTek       | B150M-C                     | [09809c7c01](https://linux-hardware.org/?probe=09809c7c01) | Oct 10, 2024 |
| ASUSTek       | B150M-C                     | [3c5997535c](https://linux-hardware.org/?probe=3c5997535c) | Oct 10, 2024 |
| Gigabyte      | H170-HD3-CF                 | [767fd4f4a9](https://linux-hardware.org/?probe=767fd4f4a9) | Oct 10, 2024 |
| Foxconn       | 2ADA                        | [1660f30544](https://linux-hardware.org/?probe=1660f30544) | Oct 10, 2024 |
| Foxconn       | 2ADA                        | [48ef106fef](https://linux-hardware.org/?probe=48ef106fef) | Oct 10, 2024 |
| Dell          | 096JG8 A00                  | [eeaa3bb7a6](https://linux-hardware.org/?probe=eeaa3bb7a6) | Oct 10, 2024 |
| Gigabyte      | H170-HD3-CF                 | [9cf0171a3a](https://linux-hardware.org/?probe=9cf0171a3a) | Oct 09, 2024 |
| Dell          | 096JG8 A00                  | [19449a27f3](https://linux-hardware.org/?probe=19449a27f3) | Oct 09, 2024 |
| HP            | 2B4B                        | [0591688b19](https://linux-hardware.org/?probe=0591688b19) | Oct 09, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [be147f67ae](https://linux-hardware.org/?probe=be147f67ae) | Oct 09, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1fc0dd6939](https://linux-hardware.org/?probe=1fc0dd6939) | Oct 09, 2024 |
| Alienware     | 0K9TKY A00                  | [eed362c8ce](https://linux-hardware.org/?probe=eed362c8ce) | Oct 09, 2024 |
| ASRock        | B760M PG Riptide            | [0112e0d2f6](https://linux-hardware.org/?probe=0112e0d2f6) | Oct 09, 2024 |
| Fujitsu       | D3118-A1 S26361-D3118-A1    | [0b42d66aec](https://linux-hardware.org/?probe=0b42d66aec) | Oct 08, 2024 |
| Fujitsu       | D3118-A1 S26361-D3118-A1    | [f57726906e](https://linux-hardware.org/?probe=f57726906e) | Oct 08, 2024 |
| System76      | Thelio Mira thelio-mira-... | [863019f9d8](https://linux-hardware.org/?probe=863019f9d8) | Oct 08, 2024 |
| ASUSTek       | PRIME B650M-A AX6           | [6597170653](https://linux-hardware.org/?probe=6597170653) | Oct 07, 2024 |
| ASUSTek       | PRIME B650M-A AX6           | [f4948e7ce8](https://linux-hardware.org/?probe=f4948e7ce8) | Oct 07, 2024 |
| ASUSTek       | P6X58D-E                    | [254590d90b](https://linux-hardware.org/?probe=254590d90b) | Oct 07, 2024 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | [8e7794b5e5](https://linux-hardware.org/?probe=8e7794b5e5) | Oct 07, 2024 |
| MSI           | MPG Z590 GAMING FORCE       | [224dee322a](https://linux-hardware.org/?probe=224dee322a) | Oct 06, 2024 |
| ASRock        | B550M-HDV                   | [f0ff453f6e](https://linux-hardware.org/?probe=f0ff453f6e) | Oct 06, 2024 |
| MSI           | MPG Z590 GAMING FORCE       | [e395202fd1](https://linux-hardware.org/?probe=e395202fd1) | Oct 05, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | [2965460cd4](https://linux-hardware.org/?probe=2965460cd4) | Oct 05, 2024 |
| Dell          | 0K240Y A01                  | [67e40a612b](https://linux-hardware.org/?probe=67e40a612b) | Oct 05, 2024 |
| Gigabyte      | Z170-HD3-CF                 | [8ef4229227](https://linux-hardware.org/?probe=8ef4229227) | Oct 05, 2024 |
| Gigabyte      | Z170-HD3-CF                 | [b3d161f10c](https://linux-hardware.org/?probe=b3d161f10c) | Oct 05, 2024 |
| ASRock        | 970 Extreme3                | [3350145c6a](https://linux-hardware.org/?probe=3350145c6a) | Oct 05, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [057d1d7a74](https://linux-hardware.org/?probe=057d1d7a74) | Oct 04, 2024 |
| Gigabyte      | B450M GAMING                | [5a7e21c336](https://linux-hardware.org/?probe=5a7e21c336) | Oct 04, 2024 |
| Gigabyte      | B450M GAMING                | [09718bd83a](https://linux-hardware.org/?probe=09718bd83a) | Oct 04, 2024 |
| ASRock        | 970 Extreme3                | [8eaad2bb51](https://linux-hardware.org/?probe=8eaad2bb51) | Oct 04, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [64e32d6a96](https://linux-hardware.org/?probe=64e32d6a96) | Oct 04, 2024 |
| MSI           | PRO B650-P WIFI             | [2d97f44bd4](https://linux-hardware.org/?probe=2d97f44bd4) | Oct 03, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [11620bee22](https://linux-hardware.org/?probe=11620bee22) | Oct 03, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [4462ad232a](https://linux-hardware.org/?probe=4462ad232a) | Oct 03, 2024 |
| ASUSTek       | PRIME Z790-P                | [5a20f0fbcf](https://linux-hardware.org/?probe=5a20f0fbcf) | Oct 03, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [43ebb1e4ec](https://linux-hardware.org/?probe=43ebb1e4ec) | Oct 03, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [66c7197cab](https://linux-hardware.org/?probe=66c7197cab) | Oct 03, 2024 |
| ASRock        | 970 Extreme3 R2.0           | [234ffa3729](https://linux-hardware.org/?probe=234ffa3729) | Oct 02, 2024 |
| Gigabyte      | Z590 VISION D               | [992bb7d24d](https://linux-hardware.org/?probe=992bb7d24d) | Oct 02, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [73dd513b22](https://linux-hardware.org/?probe=73dd513b22) | Oct 01, 2024 |
| HP            | 8597                        | [39f106b002](https://linux-hardware.org/?probe=39f106b002) | Sep 29, 2024 |
| HP            | 18E5                        | [e1758fc5c4](https://linux-hardware.org/?probe=e1758fc5c4) | Sep 29, 2024 |
| HP            | 1493                        | [6e42b160f1](https://linux-hardware.org/?probe=6e42b160f1) | Sep 29, 2024 |
| ASRock        | 970 Extreme3 R2.0           | [506731ea8d](https://linux-hardware.org/?probe=506731ea8d) | Sep 29, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | [3db990dffa](https://linux-hardware.org/?probe=3db990dffa) | Sep 29, 2024 |
| MSI           | X370 KRAIT GAMING           | [eda2ccd052](https://linux-hardware.org/?probe=eda2ccd052) | Sep 29, 2024 |
| Dell          | 0KRC95 A00                  | [886b6b82bf](https://linux-hardware.org/?probe=886b6b82bf) | Sep 29, 2024 |
| ASUSTek       | PRIME H310M-K R2.0          | [ccbfad6c6d](https://linux-hardware.org/?probe=ccbfad6c6d) | Sep 29, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [c356997396](https://linux-hardware.org/?probe=c356997396) | Sep 28, 2024 |
| ASRock        | H470M-HDV/M.2               | [8158f71264](https://linux-hardware.org/?probe=8158f71264) | Sep 28, 2024 |
| TianBei       | GOD88                       | [14aaf1d0f2](https://linux-hardware.org/?probe=14aaf1d0f2) | Sep 27, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [dc0da7194e](https://linux-hardware.org/?probe=dc0da7194e) | Sep 27, 2024 |
| Dell          | 0VHWTR A02                  | [5edaae1ca1](https://linux-hardware.org/?probe=5edaae1ca1) | Sep 27, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | [7956faa4b1](https://linux-hardware.org/?probe=7956faa4b1) | Sep 27, 2024 |
| MSI           | H410M-A PRO                 | [13cba33fe8](https://linux-hardware.org/?probe=13cba33fe8) | Sep 25, 2024 |
| ASUSTek       | PRIME A320M-K               | [4bd09ca30d](https://linux-hardware.org/?probe=4bd09ca30d) | Sep 24, 2024 |
| MACHINIST     | E5-MR9S V1.0                | [334e949999](https://linux-hardware.org/?probe=334e949999) | Sep 24, 2024 |
| ASUSTek       | PRIME A320M-K               | [c4e195980b](https://linux-hardware.org/?probe=c4e195980b) | Sep 23, 2024 |
| Dell          | 0VHWTR A02                  | [d5a9f39421](https://linux-hardware.org/?probe=d5a9f39421) | Sep 22, 2024 |
| Gigabyte      | 970A-DS3P                   | [8ee1bad547](https://linux-hardware.org/?probe=8ee1bad547) | Sep 22, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [dc1a763d32](https://linux-hardware.org/?probe=dc1a763d32) | Sep 22, 2024 |
| ASUSTek       | PRIME X570-PRO              | [f1a006d1e1](https://linux-hardware.org/?probe=f1a006d1e1) | Sep 21, 2024 |
| ASRock        | B450 Steel Legend           | [2f3706f0c5](https://linux-hardware.org/?probe=2f3706f0c5) | Sep 21, 2024 |
| Gigabyte      | B550 UD AC-Y1               | [aa5cd0be8f](https://linux-hardware.org/?probe=aa5cd0be8f) | Sep 21, 2024 |
| Lenovo        | 31900058 STD                | [87e28eedb3](https://linux-hardware.org/?probe=87e28eedb3) | Sep 20, 2024 |
| ASUSTek       | TUF Gaming B650-E WIFI      | [cbdf576f50](https://linux-hardware.org/?probe=cbdf576f50) | Sep 19, 2024 |
| ASUSTek       | H81-GAMER                   | [be55c0ed79](https://linux-hardware.org/?probe=be55c0ed79) | Sep 19, 2024 |
| ASRock        | B450 Steel Legend           | [068811de2e](https://linux-hardware.org/?probe=068811de2e) | Sep 19, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [2aaab87e79](https://linux-hardware.org/?probe=2aaab87e79) | Sep 18, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | [0fd910b3ad](https://linux-hardware.org/?probe=0fd910b3ad) | Sep 18, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [09db67859d](https://linux-hardware.org/?probe=09db67859d) | Sep 18, 2024 |
| ASUSTek       | Z97-A                       | [15116f089f](https://linux-hardware.org/?probe=15116f089f) | Sep 18, 2024 |
| ASUSTek       | M4A78T-E                    | [b079e72277](https://linux-hardware.org/?probe=b079e72277) | Sep 18, 2024 |
| Dell          | 0YJMC0 A01                  | [f4d1431f71](https://linux-hardware.org/?probe=f4d1431f71) | Sep 17, 2024 |
| Lenovo        | 333B SDK0T76465 WIN 3422... | [3ebea78539](https://linux-hardware.org/?probe=3ebea78539) | Sep 17, 2024 |
| ASRock        | B365M-HDV                   | [4f11e504a4](https://linux-hardware.org/?probe=4f11e504a4) | Sep 17, 2024 |
| ASRock        | B650I Lightning WiFi        | [f8098b07c0](https://linux-hardware.org/?probe=f8098b07c0) | Sep 17, 2024 |
| ASUSTek       | M5A97 R2.0                  | [ebd8e172d8](https://linux-hardware.org/?probe=ebd8e172d8) | Sep 17, 2024 |
| Dell          | 0MGK50 A02                  | [c77fca48aa](https://linux-hardware.org/?probe=c77fca48aa) | Sep 16, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [246cf80922](https://linux-hardware.org/?probe=246cf80922) | Sep 15, 2024 |
| OEM           | X79G                        | [6469747833](https://linux-hardware.org/?probe=6469747833) | Sep 15, 2024 |
| MSI           | B550 GAMING GEN3            | [55b783934d](https://linux-hardware.org/?probe=55b783934d) | Sep 14, 2024 |
| HP            | 89D8 SMVB                   | [83680c3917](https://linux-hardware.org/?probe=83680c3917) | Sep 14, 2024 |
| Dell          | 0MGK50 A02                  | [f135e80c90](https://linux-hardware.org/?probe=f135e80c90) | Sep 14, 2024 |
| ASUSTek       | PRIME B550M-A               | [d2eade6008](https://linux-hardware.org/?probe=d2eade6008) | Sep 14, 2024 |
| MSI           | B75MA-P45                   | [5f511858b7](https://linux-hardware.org/?probe=5f511858b7) | Sep 13, 2024 |
| MSI           | B75MA-P45                   | [2268718971](https://linux-hardware.org/?probe=2268718971) | Sep 13, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [14c0a6e948](https://linux-hardware.org/?probe=14c0a6e948) | Sep 13, 2024 |
| Intel         | DH77KC AAG39641-400         | [2478ecb6d7](https://linux-hardware.org/?probe=2478ecb6d7) | Sep 12, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [db5724bfce](https://linux-hardware.org/?probe=db5724bfce) | Sep 11, 2024 |
| MSI           | 880GMS-E41                  | [2bf925c67c](https://linux-hardware.org/?probe=2bf925c67c) | Sep 11, 2024 |
| ASRock        | Z390 Pro4                   | [ae24d0086f](https://linux-hardware.org/?probe=ae24d0086f) | Sep 11, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [cfcf6ea362](https://linux-hardware.org/?probe=cfcf6ea362) | Sep 11, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [47253bcf4b](https://linux-hardware.org/?probe=47253bcf4b) | Sep 09, 2024 |
| MSI           | B550 GAMING GEN3            | [7b19658095](https://linux-hardware.org/?probe=7b19658095) | Sep 09, 2024 |
| ASRock        | A520M/ac                    | [a612bc35e1](https://linux-hardware.org/?probe=a612bc35e1) | Sep 09, 2024 |
| ASUSTek       | SABERTOOTH P67              | [e6c0c03a84](https://linux-hardware.org/?probe=e6c0c03a84) | Sep 08, 2024 |
| ASUSTek       | SABERTOOTH P67              | [c035e6b964](https://linux-hardware.org/?probe=c035e6b964) | Sep 08, 2024 |
| ASUSTek       | M4A785-M                    | [9182978bbb](https://linux-hardware.org/?probe=9182978bbb) | Sep 08, 2024 |
| ASUSTek       | PRIME B650-PLUS             | [19a2d37f08](https://linux-hardware.org/?probe=19a2d37f08) | Sep 08, 2024 |
| Gigabyte      | Z170X-Gaming 7              | [84cf77aa77](https://linux-hardware.org/?probe=84cf77aa77) | Sep 08, 2024 |
| Dell          | 0WMJ54 A01                  | [a610abe7e7](https://linux-hardware.org/?probe=a610abe7e7) | Sep 08, 2024 |
| Dell          | 0WMJ54 A01                  | [6e97ea00ea](https://linux-hardware.org/?probe=6e97ea00ea) | Sep 08, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [c2cef73d11](https://linux-hardware.org/?probe=c2cef73d11) | Sep 07, 2024 |
| Intel         | BOX-J4105A V3.0             | [b1d4dd0bd4](https://linux-hardware.org/?probe=b1d4dd0bd4) | Sep 07, 2024 |
| Intel         | BOX-J4105A V3.0             | [01d917fce6](https://linux-hardware.org/?probe=01d917fce6) | Sep 07, 2024 |
| ASUSTek       | PRIME A320M-K               | [a2923c2916](https://linux-hardware.org/?probe=a2923c2916) | Sep 04, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [a62e0834a8](https://linux-hardware.org/?probe=a62e0834a8) | Sep 04, 2024 |
| HP            | 3397                        | [010527f0d2](https://linux-hardware.org/?probe=010527f0d2) | Sep 04, 2024 |
| ASRock        | B550 Phantom Gaming-ITX/... | [2e9c4a3189](https://linux-hardware.org/?probe=2e9c4a3189) | Sep 04, 2024 |
| ASRock        | B650E PG-ITX WiFi           | [64739c4c52](https://linux-hardware.org/?probe=64739c4c52) | Sep 03, 2024 |
| ASRock        | B650E PG-ITX WiFi           | [2f6b2386f3](https://linux-hardware.org/?probe=2f6b2386f3) | Sep 03, 2024 |
| Gigabyte      | Z370 AORUS Gaming 7         | [3f9d434cda](https://linux-hardware.org/?probe=3f9d434cda) | Sep 03, 2024 |
| ASUSTek       | M4A78T-E                    | [ba9e4ef02e](https://linux-hardware.org/?probe=ba9e4ef02e) | Sep 03, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | [59c732d659](https://linux-hardware.org/?probe=59c732d659) | Sep 03, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | [f1cb450aad](https://linux-hardware.org/?probe=f1cb450aad) | Sep 03, 2024 |
| Alienware     | 0K9TKY A00                  | [5cd57cb73f](https://linux-hardware.org/?probe=5cd57cb73f) | Sep 02, 2024 |
| ASRock        | B450 Gaming K4              | [bbaaf71d62](https://linux-hardware.org/?probe=bbaaf71d62) | Sep 02, 2024 |
| ASRock        | ALiveNF6G-VSTA              | [d5b3f47a4f](https://linux-hardware.org/?probe=d5b3f47a4f) | Sep 02, 2024 |
| ASRock        | ALiveNF6G-VSTA              | [e90b700498](https://linux-hardware.org/?probe=e90b700498) | Sep 02, 2024 |
| ASRock        | B550M Steel Legend          | [417c981b8f](https://linux-hardware.org/?probe=417c981b8f) | Sep 02, 2024 |
| ASUSTek       | M5A97 R2.0                  | [7ce9667960](https://linux-hardware.org/?probe=7ce9667960) | Sep 02, 2024 |
| ASUSTek       | H110M-K                     | [a1c10987b2](https://linux-hardware.org/?probe=a1c10987b2) | Sep 01, 2024 |
| Dell          | 0MGK50 A02                  | [4609e527b3](https://linux-hardware.org/?probe=4609e527b3) | Sep 01, 2024 |
| ASUSTek       | P6X58D PREMIUM              | [ec48a70ebf](https://linux-hardware.org/?probe=ec48a70ebf) | Sep 01, 2024 |
| ASUSTek       | M5A97 R2.0                  | [949ce28218](https://linux-hardware.org/?probe=949ce28218) | Sep 01, 2024 |
| Gigabyte      | H370M D3H GSM-CF            | [3341372848](https://linux-hardware.org/?probe=3341372848) | Aug 31, 2024 |
| ASRock        | B450 Gaming K4              | [1f76825972](https://linux-hardware.org/?probe=1f76825972) | Aug 31, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [0515980bed](https://linux-hardware.org/?probe=0515980bed) | Aug 31, 2024 |
| Dell          | 0RK936                      | [eaa47d3a8d](https://linux-hardware.org/?probe=eaa47d3a8d) | Aug 30, 2024 |
| Pegatron      | 2AD3                        | [89dfc9f55e](https://linux-hardware.org/?probe=89dfc9f55e) | Aug 30, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [4c473e9fe3](https://linux-hardware.org/?probe=4c473e9fe3) | Aug 30, 2024 |
| ASUSTek       | H81M-E                      | [9dec794b7f](https://linux-hardware.org/?probe=9dec794b7f) | Aug 30, 2024 |
| ASUSTek       | PRIME B450M-A II            | [e5c85f2d04](https://linux-hardware.org/?probe=e5c85f2d04) | Aug 29, 2024 |
| ASRock        | B550 Taichi                 | [c0740cc1dd](https://linux-hardware.org/?probe=c0740cc1dd) | Aug 28, 2024 |
| HP            | 8949 11                     | [1ef02868d1](https://linux-hardware.org/?probe=1ef02868d1) | Aug 27, 2024 |
| Dell          | 05MG37 A01                  | [66f6608841](https://linux-hardware.org/?probe=66f6608841) | Aug 26, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [7619941ef4](https://linux-hardware.org/?probe=7619941ef4) | Aug 25, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | [43248f6c75](https://linux-hardware.org/?probe=43248f6c75) | Aug 24, 2024 |
| JGINYUE       | B550i-GAMING                | [21385ab790](https://linux-hardware.org/?probe=21385ab790) | Aug 24, 2024 |
| Gigabyte      | Z590 AORUS ELITE            | [f133a301ef](https://linux-hardware.org/?probe=f133a301ef) | Aug 24, 2024 |
| MSI           | Z490-A PRO                  | [34676385aa](https://linux-hardware.org/?probe=34676385aa) | Aug 24, 2024 |
| Gigabyte      | H97M-D3H                    | [6219f88938](https://linux-hardware.org/?probe=6219f88938) | Aug 24, 2024 |
| Intel         | H61                         | [235d185a09](https://linux-hardware.org/?probe=235d185a09) | Aug 23, 2024 |
| Gigabyte      | X79-UD3                     | [eaef87529d](https://linux-hardware.org/?probe=eaef87529d) | Aug 23, 2024 |
| Dell          | 05MG37 A01                  | [afe6bb3f3a](https://linux-hardware.org/?probe=afe6bb3f3a) | Aug 23, 2024 |
| ASUSTek       | PRIME A320M-K               | [312bbf1a56](https://linux-hardware.org/?probe=312bbf1a56) | Aug 23, 2024 |
| ASRock        | B760M PG Riptide            | [b645bcc70f](https://linux-hardware.org/?probe=b645bcc70f) | Aug 23, 2024 |
| ASRock        | B760M PG Riptide            | [634b1003f7](https://linux-hardware.org/?probe=634b1003f7) | Aug 22, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [b8be1cfaa0](https://linux-hardware.org/?probe=b8be1cfaa0) | Aug 22, 2024 |
| ASUSTek       | Maximus VIII HERO           | [b66200f3af](https://linux-hardware.org/?probe=b66200f3af) | Aug 21, 2024 |
| ASUSTek       | M4A78T-E                    | [850670b457](https://linux-hardware.org/?probe=850670b457) | Aug 20, 2024 |
| MSI           | P55-GD65                    | [b84957335d](https://linux-hardware.org/?probe=b84957335d) | Aug 20, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [bd0e0e631d](https://linux-hardware.org/?probe=bd0e0e631d) | Aug 19, 2024 |
| Gigabyte      | H370M D3H GSM-CF            | [e9e34bd161](https://linux-hardware.org/?probe=e9e34bd161) | Aug 19, 2024 |
| HP            | 158A                        | [dba33b3615](https://linux-hardware.org/?probe=dba33b3615) | Aug 19, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [538bd3b7c8](https://linux-hardware.org/?probe=538bd3b7c8) | Aug 18, 2024 |
| HP            | 8298                        | [7c08836a71](https://linux-hardware.org/?probe=7c08836a71) | Aug 18, 2024 |
| Dell          | 0KRC95 A00                  | [3e257fb08c](https://linux-hardware.org/?probe=3e257fb08c) | Aug 18, 2024 |
| HP            | 8298                        | [9cdee21525](https://linux-hardware.org/?probe=9cdee21525) | Aug 18, 2024 |
| Alienware     | 0K9TKY A00                  | [bf601c79a0](https://linux-hardware.org/?probe=bf601c79a0) | Aug 18, 2024 |
| MSI           | B550 GAMING GEN3            | [3282cc5b8d](https://linux-hardware.org/?probe=3282cc5b8d) | Aug 17, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [fbf683c390](https://linux-hardware.org/?probe=fbf683c390) | Aug 17, 2024 |
| Lenovo        | SDK0E50510 WIN 262508278... | [705442b78e](https://linux-hardware.org/?probe=705442b78e) | Aug 17, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | [f016b8e504](https://linux-hardware.org/?probe=f016b8e504) | Aug 17, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | [5dfed557cd](https://linux-hardware.org/?probe=5dfed557cd) | Aug 17, 2024 |
| MSI           | X470 GAMING PRO             | [3c3b5c074d](https://linux-hardware.org/?probe=3c3b5c074d) | Aug 16, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | [0508702536](https://linux-hardware.org/?probe=0508702536) | Aug 16, 2024 |
| Dell          | 0M6C7G A00                  | [1cc2213cb3](https://linux-hardware.org/?probe=1cc2213cb3) | Aug 16, 2024 |
| Dell          | 0M6C7G A00                  | [15d2eb7ffa](https://linux-hardware.org/?probe=15d2eb7ffa) | Aug 16, 2024 |
| MSI           | Z390-A PRO                  | [061af3f20b](https://linux-hardware.org/?probe=061af3f20b) | Aug 15, 2024 |
| Gigabyte      | GA-890FXA-UD5               | [811a08f014](https://linux-hardware.org/?probe=811a08f014) | Aug 15, 2024 |
| Gigabyte      | G1.SNIPER B7-CF             | [9c74fd2453](https://linux-hardware.org/?probe=9c74fd2453) | Aug 15, 2024 |
| Dell          | 0MWYPT A02                  | [bf6bb2e1f9](https://linux-hardware.org/?probe=bf6bb2e1f9) | Aug 15, 2024 |
| ASUSTek       | Maximus VIII HERO           | [de7ad64690](https://linux-hardware.org/?probe=de7ad64690) | Aug 14, 2024 |
| Gigabyte      | Z170XP-SLI-CF               | [28698ba5b1](https://linux-hardware.org/?probe=28698ba5b1) | Aug 14, 2024 |
| Gigabyte      | Z170XP-SLI-CF               | [1c6e3b0798](https://linux-hardware.org/?probe=1c6e3b0798) | Aug 14, 2024 |
| ASUSTek       | PRIME B650-PLUS             | [bd67fc9306](https://linux-hardware.org/?probe=bd67fc9306) | Aug 13, 2024 |
| Unknown       | X99                         | [2424de4c27](https://linux-hardware.org/?probe=2424de4c27) | Aug 13, 2024 |
| Gigabyte      | H270M-DS3H-CF               | [b05ae1d293](https://linux-hardware.org/?probe=b05ae1d293) | Aug 12, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [fc8c3576ff](https://linux-hardware.org/?probe=fc8c3576ff) | Aug 12, 2024 |
| Gigabyte      | B760M DS3H AX               | [2511e2e27c](https://linux-hardware.org/?probe=2511e2e27c) | Aug 12, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [e9bf3f35c2](https://linux-hardware.org/?probe=e9bf3f35c2) | Aug 12, 2024 |
| ASUSTek       | PRIME TRX40-PRO S           | [8d430814f9](https://linux-hardware.org/?probe=8d430814f9) | Aug 12, 2024 |
| ASUSTek       | PRIME TRX40-PRO S           | [b8e277723a](https://linux-hardware.org/?probe=b8e277723a) | Aug 12, 2024 |
| MSI           | PRO Z790-VC WIFI            | [12fd87d753](https://linux-hardware.org/?probe=12fd87d753) | Aug 12, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [a8a2ca27f5](https://linux-hardware.org/?probe=a8a2ca27f5) | Aug 11, 2024 |
| Huanan        | X99-QD4 V1.0                | [03d9cd7d8f](https://linux-hardware.org/?probe=03d9cd7d8f) | Aug 11, 2024 |
| Dell          | 0KWVT8 A03                  | [bd84edf70b](https://linux-hardware.org/?probe=bd84edf70b) | Aug 11, 2024 |
| ASRock        | B550 Taichi                 | [4c7c930992](https://linux-hardware.org/?probe=4c7c930992) | Aug 11, 2024 |
| ASRock        | B360M Pro4                  | [617db99564](https://linux-hardware.org/?probe=617db99564) | Aug 10, 2024 |
| MSI           | Z97 GAMING 5                | [f5df62e0e3](https://linux-hardware.org/?probe=f5df62e0e3) | Aug 09, 2024 |
| MSI           | B450M MORTAR MAX            | [2ae38468fe](https://linux-hardware.org/?probe=2ae38468fe) | Aug 09, 2024 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [57e8458491](https://linux-hardware.org/?probe=57e8458491) | Aug 09, 2024 |
| ASRock        | B550M Pro4                  | [4ee5c05e5d](https://linux-hardware.org/?probe=4ee5c05e5d) | Aug 08, 2024 |
| ASRock        | B650 PG Lightning           | [24b9cbc4c3](https://linux-hardware.org/?probe=24b9cbc4c3) | Aug 08, 2024 |
| MSI           | X470 GAMING PLUS            | [25ae750555](https://linux-hardware.org/?probe=25ae750555) | Aug 08, 2024 |
| JGINYUE       | B450I-GAMING Ver:1.1        | [30352439df](https://linux-hardware.org/?probe=30352439df) | Aug 07, 2024 |
| ASUSTek       | Maximus VIII HERO           | [6016928948](https://linux-hardware.org/?probe=6016928948) | Aug 07, 2024 |
| ASUSTek       | PRIME A520M-E               | [cb8a72934c](https://linux-hardware.org/?probe=cb8a72934c) | Aug 07, 2024 |
| Gigabyte      | B560M AORUS PRO AX          | [ad142aa4d2](https://linux-hardware.org/?probe=ad142aa4d2) | Aug 06, 2024 |
| ASRock        | B550M Pro4                  | [9292fcc7a3](https://linux-hardware.org/?probe=9292fcc7a3) | Aug 06, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [69f6392035](https://linux-hardware.org/?probe=69f6392035) | Aug 05, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [37373cb53a](https://linux-hardware.org/?probe=37373cb53a) | Aug 05, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [3571fff949](https://linux-hardware.org/?probe=3571fff949) | Aug 05, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [61a0d663e1](https://linux-hardware.org/?probe=61a0d663e1) | Aug 04, 2024 |
| ASUSTek       | M5A78L-M LX PLUS            | [56a5fc5294](https://linux-hardware.org/?probe=56a5fc5294) | Aug 04, 2024 |
| ASUSTek       | M5A78L-M LX PLUS            | [3925335793](https://linux-hardware.org/?probe=3925335793) | Aug 04, 2024 |
| Gigabyte      | G41MT-S2P                   | [68972e8426](https://linux-hardware.org/?probe=68972e8426) | Aug 02, 2024 |
| Gigabyte      | X670 GAMING X AX            | [8fc63684ca](https://linux-hardware.org/?probe=8fc63684ca) | Aug 01, 2024 |
| ASRockRack    | ROMED6U-2L2T                | [bc2cfbbe18](https://linux-hardware.org/?probe=bc2cfbbe18) | Aug 01, 2024 |
| ASUSTek       | PRIME B660M-A D4            | [711db524cd](https://linux-hardware.org/?probe=711db524cd) | Aug 01, 2024 |
| HP            | 802F                        | [9e091395a1](https://linux-hardware.org/?probe=9e091395a1) | Aug 01, 2024 |
| Gigabyte      | X670 GAMING X AX            | [76160087f0](https://linux-hardware.org/?probe=76160087f0) | Aug 01, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [9c32109aca](https://linux-hardware.org/?probe=9c32109aca) | Jul 31, 2024 |
| Gigabyte      | B760 DS3H                   | [e8ca621821](https://linux-hardware.org/?probe=e8ca621821) | Jul 31, 2024 |
| ASRock        | B760M PG Riptide            | [d48ccd8631](https://linux-hardware.org/?probe=d48ccd8631) | Jul 30, 2024 |
| Gigabyte      | H97N-WIFI                   | [02b2bee06f](https://linux-hardware.org/?probe=02b2bee06f) | Jul 30, 2024 |
| Gigabyte      | H97N-WIFI                   | [3b982914c0](https://linux-hardware.org/?probe=3b982914c0) | Jul 30, 2024 |
| AMI           | Intel                       | [e8c1dc7dbf](https://linux-hardware.org/?probe=e8c1dc7dbf) | Jul 30, 2024 |
| ASRock        | H470M-HDV/M.2               | [7a15f390cd](https://linux-hardware.org/?probe=7a15f390cd) | Jul 30, 2024 |
| MSI           | A320M PRO-VH PLUS           | [fe0642521d](https://linux-hardware.org/?probe=fe0642521d) | Jul 29, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [0fd188eec7](https://linux-hardware.org/?probe=0fd188eec7) | Jul 29, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [db921cc454](https://linux-hardware.org/?probe=db921cc454) | Jul 29, 2024 |
| Gigabyte      | Z690 UD DDR4                | [42e4e46256](https://linux-hardware.org/?probe=42e4e46256) | Jul 29, 2024 |
| Alienware     | 0K9TKY A00                  | [2b6c81fc5d](https://linux-hardware.org/?probe=2b6c81fc5d) | Jul 28, 2024 |
| MSI           | B450M PRO-VDH V2            | [d6f37140d4](https://linux-hardware.org/?probe=d6f37140d4) | Jul 28, 2024 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [5eeb285b4b](https://linux-hardware.org/?probe=5eeb285b4b) | Jul 28, 2024 |
| Gigabyte      | H270M-D3H-CF                | [527bafa1a2](https://linux-hardware.org/?probe=527bafa1a2) | Jul 27, 2024 |
| Gigabyte      | H270M-D3H-CF                | [8e61c77d83](https://linux-hardware.org/?probe=8e61c77d83) | Jul 27, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [5b73fc65a2](https://linux-hardware.org/?probe=5b73fc65a2) | Jul 27, 2024 |
| Acer          | H57M01                      | [a5d0b5cb23](https://linux-hardware.org/?probe=a5d0b5cb23) | Jul 27, 2024 |
| MSI           | PRO Z790-VC WIFI            | [ce2bd01306](https://linux-hardware.org/?probe=ce2bd01306) | Jul 27, 2024 |
| ASUSTek       | PRIME B350M-A               | [7eca7458ea](https://linux-hardware.org/?probe=7eca7458ea) | Jul 26, 2024 |
| Biostar       | A320MH                      | [8185a71a75](https://linux-hardware.org/?probe=8185a71a75) | Jul 26, 2024 |
| ASUSTek       | M5A99X EVO R2.0             | [cc020bee59](https://linux-hardware.org/?probe=cc020bee59) | Jul 26, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | [ea83bd1705](https://linux-hardware.org/?probe=ea83bd1705) | Jul 26, 2024 |
| Intel         | H61                         | [75e5c32ae4](https://linux-hardware.org/?probe=75e5c32ae4) | Jul 25, 2024 |
| Alienware     | 0RF96M A01                  | [846675b6a3](https://linux-hardware.org/?probe=846675b6a3) | Jul 24, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [b59bcf1a4d](https://linux-hardware.org/?probe=b59bcf1a4d) | Jul 24, 2024 |
| Gigabyte      | X570 GAMING X               | [9c0f3d7564](https://linux-hardware.org/?probe=9c0f3d7564) | Jul 23, 2024 |
| ASRock        | Z370 Gaming-ITX/ac          | [1feb2d1ed8](https://linux-hardware.org/?probe=1feb2d1ed8) | Jul 22, 2024 |
| HP            | 83E1                        | [8730997b3c](https://linux-hardware.org/?probe=8730997b3c) | Jul 22, 2024 |
| Dell          | 0782GW A01                  | [3977ca7e9a](https://linux-hardware.org/?probe=3977ca7e9a) | Jul 22, 2024 |
| HP            | 3646h                       | [372bfceee8](https://linux-hardware.org/?probe=372bfceee8) | Jul 22, 2024 |
| ASRock        | Z370 Gaming-ITX/ac          | [8bb305deae](https://linux-hardware.org/?probe=8bb305deae) | Jul 22, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [ce47e04e8c](https://linux-hardware.org/?probe=ce47e04e8c) | Jul 21, 2024 |
| Gigabyte      | B650 EAGLE AX               | [6dd7e462ee](https://linux-hardware.org/?probe=6dd7e462ee) | Jul 21, 2024 |
| MSI           | PRO B760M-P DDR4            | [de6efe8006](https://linux-hardware.org/?probe=de6efe8006) | Jul 21, 2024 |
| NZXT          | N7 B650E                    | [a377d12a39](https://linux-hardware.org/?probe=a377d12a39) | Jul 21, 2024 |
| MSI           | PRO B760M-P DDR4            | [c2902561c9](https://linux-hardware.org/?probe=c2902561c9) | Jul 20, 2024 |
| Dell          | 0GY6Y8 A01                  | [790ecb5d30](https://linux-hardware.org/?probe=790ecb5d30) | Jul 20, 2024 |
| MSI           | B550-A PRO[CEC]             | [8df15d15a4](https://linux-hardware.org/?probe=8df15d15a4) | Jul 20, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [51a79b8877](https://linux-hardware.org/?probe=51a79b8877) | Jul 19, 2024 |
| Apple         | Mac-F221BEC8                | [9e98e8a38c](https://linux-hardware.org/?probe=9e98e8a38c) | Jul 19, 2024 |
| Gigabyte      | B550M DS3H                  | [a3f16864aa](https://linux-hardware.org/?probe=a3f16864aa) | Jul 19, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [a433142bff](https://linux-hardware.org/?probe=a433142bff) | Jul 19, 2024 |
| ASUSTek       | PRIME Z490-P                | [535e9dce6d](https://linux-hardware.org/?probe=535e9dce6d) | Jul 17, 2024 |
| MSI           | Z97 GAMING 5                | [fe874570ea](https://linux-hardware.org/?probe=fe874570ea) | Jul 17, 2024 |
| Unknown       | Unknown                     | [929917505d](https://linux-hardware.org/?probe=929917505d) | Jul 17, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [8116b5ab58](https://linux-hardware.org/?probe=8116b5ab58) | Jul 17, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [1e38b6ee2b](https://linux-hardware.org/?probe=1e38b6ee2b) | Jul 16, 2024 |
| ASRock        | B550M Pro SE                | [ff98e2b24e](https://linux-hardware.org/?probe=ff98e2b24e) | Jul 15, 2024 |
| System76      | Thelio Major thelio-majo... | [75684532af](https://linux-hardware.org/?probe=75684532af) | Jul 15, 2024 |
| Gigabyte      | X58A-UD7                    | [6ba0085048](https://linux-hardware.org/?probe=6ba0085048) | Jul 15, 2024 |
| JGINYUE       | B550i-GAMING                | [facf752650](https://linux-hardware.org/?probe=facf752650) | Jul 15, 2024 |
| ASRock        | B550 PG Riptide             | [40de96ebe6](https://linux-hardware.org/?probe=40de96ebe6) | Jul 13, 2024 |
| MSI           | MAG Z390M MORTAR            | [a313a791dd](https://linux-hardware.org/?probe=a313a791dd) | Jul 13, 2024 |
| Gigabyte      | B450 AORUS M                | [49965ee28e](https://linux-hardware.org/?probe=49965ee28e) | Jul 12, 2024 |
| ASUSTek       | PRIME X570-P                | [6c0c752f84](https://linux-hardware.org/?probe=6c0c752f84) | Jul 12, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [775d104dd5](https://linux-hardware.org/?probe=775d104dd5) | Jul 10, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1630508daf](https://linux-hardware.org/?probe=1630508daf) | Jul 10, 2024 |
| HP            | 8594                        | [422cea7949](https://linux-hardware.org/?probe=422cea7949) | Jul 09, 2024 |
| Gigabyte      | H270M-DS3H-CF               | [880956dce2](https://linux-hardware.org/?probe=880956dce2) | Jul 09, 2024 |
| Gigabyte      | X670E AORUS PRO X           | [128fea1e97](https://linux-hardware.org/?probe=128fea1e97) | Jul 09, 2024 |
| Gigabyte      | X58A-UD7                    | [c5471b61ce](https://linux-hardware.org/?probe=c5471b61ce) | Jul 08, 2024 |
| Gigabyte      | Z170X-Gaming 3              | [509596fdcd](https://linux-hardware.org/?probe=509596fdcd) | Jul 08, 2024 |
| MSI           | PRO Z790-P WIFI DDR4        | [d49beb2797](https://linux-hardware.org/?probe=d49beb2797) | Jul 08, 2024 |
| Gigabyte      | Z690 UD DDR4                | [bd15491297](https://linux-hardware.org/?probe=bd15491297) | Jul 07, 2024 |
| MSI           | MEG X570 UNIFY              | [ec1a7d5e3f](https://linux-hardware.org/?probe=ec1a7d5e3f) | Jul 06, 2024 |
| Dell          | 0DF42J A00                  | [2c0fa89939](https://linux-hardware.org/?probe=2c0fa89939) | Jul 06, 2024 |
| ASUSTek       | PRIME H670-PLUS D4          | [fcde8cb1f0](https://linux-hardware.org/?probe=fcde8cb1f0) | Jul 06, 2024 |
| ASUSTek       | PRIME X470-PRO              | [5149c43ac4](https://linux-hardware.org/?probe=5149c43ac4) | Jul 05, 2024 |
| Gigabyte      | A520M K V2                  | [3315587330](https://linux-hardware.org/?probe=3315587330) | Jul 05, 2024 |
| Gigabyte      | H270M-DS3H-CF               | [85ee8988bc](https://linux-hardware.org/?probe=85ee8988bc) | Jul 05, 2024 |
| Gigabyte      | H270M-DS3H-CF               | [4135003321](https://linux-hardware.org/?probe=4135003321) | Jul 05, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [a74e9f1285](https://linux-hardware.org/?probe=a74e9f1285) | Jul 04, 2024 |
| ASUSTek       | PRIME X570-P                | [853c595909](https://linux-hardware.org/?probe=853c595909) | Jul 04, 2024 |
| GEEKOM        | AE7                         | [44457a7465](https://linux-hardware.org/?probe=44457a7465) | Jul 04, 2024 |
| HP            | 3646h                       | [e86953fc1d](https://linux-hardware.org/?probe=e86953fc1d) | Jul 04, 2024 |
| ASUSTek       | Z87-PRO                     | [e96b292b22](https://linux-hardware.org/?probe=e96b292b22) | Jul 04, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | [4e01739375](https://linux-hardware.org/?probe=4e01739375) | Jul 02, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | [85e6955fa3](https://linux-hardware.org/?probe=85e6955fa3) | Jul 02, 2024 |
| ASUSTek       | Z87-K                       | [b1bc62b3b8](https://linux-hardware.org/?probe=b1bc62b3b8) | Jul 02, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ff1e4af5fd](https://linux-hardware.org/?probe=ff1e4af5fd) | Jul 02, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [de10fc7f16](https://linux-hardware.org/?probe=de10fc7f16) | Jul 02, 2024 |
| HP            | 18E7                        | [d7e6718daf](https://linux-hardware.org/?probe=d7e6718daf) | Jul 01, 2024 |
| MSI           | B365M PRO-VH                | [58ca108468](https://linux-hardware.org/?probe=58ca108468) | Jun 30, 2024 |
| Dell          | 0XD433 A01                  | [b137bc0e39](https://linux-hardware.org/?probe=b137bc0e39) | Jun 30, 2024 |
| GEEKOM        | AE7                         | [4cd8965470](https://linux-hardware.org/?probe=4cd8965470) | Jun 30, 2024 |
| ASUSTek       | M4A79T Deluxe               | [1ffc2643fe](https://linux-hardware.org/?probe=1ffc2643fe) | Jun 29, 2024 |
| ASUSTek       | M4A79T Deluxe               | [4b5020cb2d](https://linux-hardware.org/?probe=4b5020cb2d) | Jun 29, 2024 |
| MSI           | MPG B650I EDGE WIFI         | [c1cca08c85](https://linux-hardware.org/?probe=c1cca08c85) | Jun 29, 2024 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [012abe9f82](https://linux-hardware.org/?probe=012abe9f82) | Jun 28, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [fc1c8bb5cd](https://linux-hardware.org/?probe=fc1c8bb5cd) | Jun 28, 2024 |
| HP            | 18E7                        | [afd21565ec](https://linux-hardware.org/?probe=afd21565ec) | Jun 28, 2024 |
| Shenzhen M... | F7BFC                       | [f9159f1d37](https://linux-hardware.org/?probe=f9159f1d37) | Jun 27, 2024 |
| ASUSTek       | Pro WS TRX50-SAGE WIFI      | [480f889606](https://linux-hardware.org/?probe=480f889606) | Jun 27, 2024 |
| ASUSTek       | M5A78L-M LX PLUS            | [46e856fc41](https://linux-hardware.org/?probe=46e856fc41) | Jun 27, 2024 |
| ASUSTek       | M5A78L-M LX PLUS            | [81b37e4b57](https://linux-hardware.org/?probe=81b37e4b57) | Jun 27, 2024 |
| ASUSTek       | Maximus VI GENE             | [309582e7e2](https://linux-hardware.org/?probe=309582e7e2) | Jun 25, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [9f5a8cdb08](https://linux-hardware.org/?probe=9f5a8cdb08) | Jun 25, 2024 |
| ASUSTek       | M5A97 R2.0                  | [04eff2c63f](https://linux-hardware.org/?probe=04eff2c63f) | Jun 24, 2024 |
| Acer          | FX58M                       | [d17ad6dfdf](https://linux-hardware.org/?probe=d17ad6dfdf) | Jun 24, 2024 |
| Acer          | FX58M                       | [12d25a0b03](https://linux-hardware.org/?probe=12d25a0b03) | Jun 24, 2024 |
| ASUSTek       | M4N72-E                     | [bf131f9def](https://linux-hardware.org/?probe=bf131f9def) | Jun 24, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9545489533](https://linux-hardware.org/?probe=9545489533) | Jun 24, 2024 |
| ASUSTek       | Maximus VI GENE             | [ecadf3dd2d](https://linux-hardware.org/?probe=ecadf3dd2d) | Jun 24, 2024 |
| MSI           | B365M PRO-VDH               | [850f3ea904](https://linux-hardware.org/?probe=850f3ea904) | Jun 24, 2024 |
| ASUSTek       | M5A97 R2.0                  | [c6be85ff7c](https://linux-hardware.org/?probe=c6be85ff7c) | Jun 23, 2024 |
| Dell          | 05YDCW A01                  | [39ed01c33a](https://linux-hardware.org/?probe=39ed01c33a) | Jun 23, 2024 |
| ASUSTek       | Z97-PRO GAMER               | [73032707be](https://linux-hardware.org/?probe=73032707be) | Jun 22, 2024 |
| ASUSTek       | Z97-PRO GAMER               | [15a3dbd5db](https://linux-hardware.org/?probe=15a3dbd5db) | Jun 22, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [e52122428e](https://linux-hardware.org/?probe=e52122428e) | Jun 20, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [de04fdf07e](https://linux-hardware.org/?probe=de04fdf07e) | Jun 20, 2024 |
| System76      | Thelio thelio-r3            | [ce68e3a906](https://linux-hardware.org/?probe=ce68e3a906) | Jun 19, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [31ded147a8](https://linux-hardware.org/?probe=31ded147a8) | Jun 18, 2024 |
| ASRock        | H510 Pro BTC+               | [49d94371c8](https://linux-hardware.org/?probe=49d94371c8) | Jun 18, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [2f6972e738](https://linux-hardware.org/?probe=2f6972e738) | Jun 18, 2024 |
| MSI           | Z390-A PRO                  | [01dbafbb6e](https://linux-hardware.org/?probe=01dbafbb6e) | Jun 18, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [8a2e597dec](https://linux-hardware.org/?probe=8a2e597dec) | Jun 18, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [adc88cbb14](https://linux-hardware.org/?probe=adc88cbb14) | Jun 18, 2024 |
| ASRock        | H510 Pro BTC+               | [09fe9680f7](https://linux-hardware.org/?probe=09fe9680f7) | Jun 18, 2024 |
| ASUSTek       | H97-PLUS                    | [0f87602b5a](https://linux-hardware.org/?probe=0f87602b5a) | Jun 18, 2024 |
| ASUSTek       | H97-PLUS                    | [d85b52226d](https://linux-hardware.org/?probe=d85b52226d) | Jun 18, 2024 |
| ASUSTek       | P8Z77-V LX                  | [f2691bf535](https://linux-hardware.org/?probe=f2691bf535) | Jun 17, 2024 |
| ASUSTek       | Z170-A                      | [432f4114f1](https://linux-hardware.org/?probe=432f4114f1) | Jun 17, 2024 |
| Dell          | 0KWVT8 A03                  | [72eddb2385](https://linux-hardware.org/?probe=72eddb2385) | Jun 17, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [98fa90965a](https://linux-hardware.org/?probe=98fa90965a) | Jun 17, 2024 |
| Unknown       | Intel X79                   | [b2d0c166c4](https://linux-hardware.org/?probe=b2d0c166c4) | Jun 16, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [3c22c8cd3f](https://linux-hardware.org/?probe=3c22c8cd3f) | Jun 16, 2024 |
| ASUSTek       | PRIME B660M-A D4            | [fade2029a5](https://linux-hardware.org/?probe=fade2029a5) | Jun 16, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [53e13d322f](https://linux-hardware.org/?probe=53e13d322f) | Jun 16, 2024 |
| HP            | 8054                        | [9beee67f9c](https://linux-hardware.org/?probe=9beee67f9c) | Jun 15, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [47bb7c0f58](https://linux-hardware.org/?probe=47bb7c0f58) | Jun 15, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [aee377ab97](https://linux-hardware.org/?probe=aee377ab97) | Jun 15, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | [a3adbfd79c](https://linux-hardware.org/?probe=a3adbfd79c) | Jun 15, 2024 |
| Gigabyte      | B75M-D2V                    | [1bdb0774ec](https://linux-hardware.org/?probe=1bdb0774ec) | Jun 14, 2024 |
| ASUSTek       | M5A78L-M LE/USB3            | [de724a5157](https://linux-hardware.org/?probe=de724a5157) | Jun 13, 2024 |
| Packard Be... | MCP73PV                     | [cee96d28a1](https://linux-hardware.org/?probe=cee96d28a1) | Jun 13, 2024 |
| HP            | 8054                        | [75ae1fa0b1](https://linux-hardware.org/?probe=75ae1fa0b1) | Jun 13, 2024 |
| Pegatron      | NARRA5                      | [3a6b723286](https://linux-hardware.org/?probe=3a6b723286) | Jun 13, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [991030218a](https://linux-hardware.org/?probe=991030218a) | Jun 13, 2024 |
| Gigabyte      | X570 UD                     | [5be50e6828](https://linux-hardware.org/?probe=5be50e6828) | Jun 11, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [2bcce1eb1d](https://linux-hardware.org/?probe=2bcce1eb1d) | Jun 11, 2024 |
| MSI           | B450M MORTAR MAX            | [1d847efc24](https://linux-hardware.org/?probe=1d847efc24) | Jun 10, 2024 |
| MSI           | PRO Z790-P WIFI DDR4        | [c433941141](https://linux-hardware.org/?probe=c433941141) | Jun 10, 2024 |
| MSI           | Z590-A PRO                  | [eabc9dc662](https://linux-hardware.org/?probe=eabc9dc662) | Jun 09, 2024 |
| MSI           | Z590-A PRO                  | [bf614aeed9](https://linux-hardware.org/?probe=bf614aeed9) | Jun 09, 2024 |
| System76      | Thelio Mira thelio-mira-... | [95d2abb431](https://linux-hardware.org/?probe=95d2abb431) | Jun 08, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [1bd06c13ce](https://linux-hardware.org/?probe=1bd06c13ce) | Jun 08, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [df3ab4e94b](https://linux-hardware.org/?probe=df3ab4e94b) | Jun 08, 2024 |
| HP            | 8062                        | [4e05352650](https://linux-hardware.org/?probe=4e05352650) | Jun 08, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | [e6c7d4912f](https://linux-hardware.org/?probe=e6c7d4912f) | Jun 08, 2024 |
| Gigabyte      | Z77X-UP7                    | [4abbeda82d](https://linux-hardware.org/?probe=4abbeda82d) | Jun 07, 2024 |
| Gigabyte      | Z790 AORUS MASTER           | [7817d930fa](https://linux-hardware.org/?probe=7817d930fa) | Jun 07, 2024 |
| MSI           | B450M MORTAR MAX            | [5bec71f136](https://linux-hardware.org/?probe=5bec71f136) | Jun 07, 2024 |
| MSI           | MAG B550M MORTAR            | [6dc4d4c1dd](https://linux-hardware.org/?probe=6dc4d4c1dd) | Jun 06, 2024 |
| MSI           | B550-A PRO[CEC]             | [849db29a1d](https://linux-hardware.org/?probe=849db29a1d) | Jun 04, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [f5bc6c6c54](https://linux-hardware.org/?probe=f5bc6c6c54) | Jun 04, 2024 |
| Biostar       | A780L3G                     | [4cb71b4e62](https://linux-hardware.org/?probe=4cb71b4e62) | Jun 04, 2024 |
| Biostar       | A780L3G                     | [ae6c98362a](https://linux-hardware.org/?probe=ae6c98362a) | Jun 04, 2024 |
| ASRock        | H87 Performance             | [5968bb803e](https://linux-hardware.org/?probe=5968bb803e) | Jun 04, 2024 |
| ASRock        | X399M Taichi                | [929dd2727f](https://linux-hardware.org/?probe=929dd2727f) | Jun 03, 2024 |
| System76      | Thelio thelio-r3            | [1c218fa3ad](https://linux-hardware.org/?probe=1c218fa3ad) | Jun 03, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c957fc0c93](https://linux-hardware.org/?probe=c957fc0c93) | Jun 03, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [2b10ae5b48](https://linux-hardware.org/?probe=2b10ae5b48) | Jun 03, 2024 |
| Gigabyte      | B550M AORUS ELITE AX        | [c1700109fd](https://linux-hardware.org/?probe=c1700109fd) | Jun 03, 2024 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [69b6277fcf](https://linux-hardware.org/?probe=69b6277fcf) | Jun 03, 2024 |
| MSI           | B365M PRO-VDH               | [14edaf1e7f](https://linux-hardware.org/?probe=14edaf1e7f) | Jun 02, 2024 |
| MSI           | B365M PRO-VDH               | [ffc93e1209](https://linux-hardware.org/?probe=ffc93e1209) | Jun 02, 2024 |
| ASRock        | FM2A68M-HD+                 | [cabf968b6e](https://linux-hardware.org/?probe=cabf968b6e) | Jun 02, 2024 |
| Gigabyte      | B360M DS3H                  | [833dd15bc4](https://linux-hardware.org/?probe=833dd15bc4) | Jun 02, 2024 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | [ae32a8e661](https://linux-hardware.org/?probe=ae32a8e661) | Jun 02, 2024 |
| Gigabyte      | B75M-D2V                    | [0c8e64428d](https://linux-hardware.org/?probe=0c8e64428d) | Jun 02, 2024 |
| ASUSTek       | PRIME H310M-K R2.0          | [72a9b30345](https://linux-hardware.org/?probe=72a9b30345) | Jun 01, 2024 |
| ASRock        | A620M Pro RS WiFi           | [ec74bbb795](https://linux-hardware.org/?probe=ec74bbb795) | Jun 01, 2024 |
| MSI           | MPG X670E CARBON WIFI       | [2a6ac8beef](https://linux-hardware.org/?probe=2a6ac8beef) | Jun 01, 2024 |
| HP            | 8299                        | [4a034c01ed](https://linux-hardware.org/?probe=4a034c01ed) | May 31, 2024 |
| Gigabyte      | H97-HD3                     | [236cebe749](https://linux-hardware.org/?probe=236cebe749) | May 31, 2024 |
| MSI           | B550-A PRO[CEC]             | [e545c7bbc2](https://linux-hardware.org/?probe=e545c7bbc2) | May 31, 2024 |
| Gigabyte      | B150M-Gaming 3 DDR3-CF      | [bace54b773](https://linux-hardware.org/?probe=bace54b773) | May 31, 2024 |
| Pegatron      | IPMH61P1                    | [cb15d21b08](https://linux-hardware.org/?probe=cb15d21b08) | May 31, 2024 |
| Pegatron      | IPMH61P1                    | [e48bc5d02a](https://linux-hardware.org/?probe=e48bc5d02a) | May 31, 2024 |
| HP            | 8918                        | [1004c84bae](https://linux-hardware.org/?probe=1004c84bae) | May 30, 2024 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [7dc90447a3](https://linux-hardware.org/?probe=7dc90447a3) | May 28, 2024 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [868d1bdf81](https://linux-hardware.org/?probe=868d1bdf81) | May 28, 2024 |
| MSI           | B450 GAMING PRO CARBON M... | [f79e2971d2](https://linux-hardware.org/?probe=f79e2971d2) | May 28, 2024 |
| MSI           | B450 GAMING PRO CARBON M... | [0e655f1bfa](https://linux-hardware.org/?probe=0e655f1bfa) | May 28, 2024 |
| Dell          | 0NW6H5 A00                  | [1e9b9b0333](https://linux-hardware.org/?probe=1e9b9b0333) | May 28, 2024 |
| ASRock        | H310CM-HG4                  | [c6d4a074c8](https://linux-hardware.org/?probe=c6d4a074c8) | May 28, 2024 |
| ASRock        | H310CM-HG4                  | [5e2e1c09b6](https://linux-hardware.org/?probe=5e2e1c09b6) | May 28, 2024 |
| OEM           | X79G                        | [121e628b73](https://linux-hardware.org/?probe=121e628b73) | May 27, 2024 |
| wpc           | zrd616                      | [750cee7cf1](https://linux-hardware.org/?probe=750cee7cf1) | May 27, 2024 |
| Gigabyte      | Z370P D3-CF                 | [46d4ec8068](https://linux-hardware.org/?probe=46d4ec8068) | May 27, 2024 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [8b648fe3dd](https://linux-hardware.org/?probe=8b648fe3dd) | May 27, 2024 |
| Dell          | 088DT1 A01                  | [37c260cdf4](https://linux-hardware.org/?probe=37c260cdf4) | May 27, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [20cafc4d87](https://linux-hardware.org/?probe=20cafc4d87) | May 27, 2024 |
| OEM           | X79G                        | [e87ff18bc6](https://linux-hardware.org/?probe=e87ff18bc6) | May 27, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [2ca38eda81](https://linux-hardware.org/?probe=2ca38eda81) | May 26, 2024 |
| Dell          | 0NW6H5 A00                  | [2c36f9b7bf](https://linux-hardware.org/?probe=2c36f9b7bf) | May 26, 2024 |
| Dell          | 088DT1 A01                  | [8a594af62b](https://linux-hardware.org/?probe=8a594af62b) | May 26, 2024 |
| MSI           | MPG B650I EDGE WIFI         | [a8ec581725](https://linux-hardware.org/?probe=a8ec581725) | May 25, 2024 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [4cfa5b370b](https://linux-hardware.org/?probe=4cfa5b370b) | May 25, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e3e492ea9d](https://linux-hardware.org/?probe=e3e492ea9d) | May 25, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [294f10e7ec](https://linux-hardware.org/?probe=294f10e7ec) | May 25, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [6c7c56ff88](https://linux-hardware.org/?probe=6c7c56ff88) | May 25, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [957c0eb5a9](https://linux-hardware.org/?probe=957c0eb5a9) | May 24, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [e272ca0091](https://linux-hardware.org/?probe=e272ca0091) | May 24, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [a44eb792e2](https://linux-hardware.org/?probe=a44eb792e2) | May 24, 2024 |
| ASUSTek       | H61M-K                      | [ed0fb6e87d](https://linux-hardware.org/?probe=ed0fb6e87d) | May 24, 2024 |
| System76      | Thelio Major thelio-majo... | [dadeec5b07](https://linux-hardware.org/?probe=dadeec5b07) | May 23, 2024 |
| System76      | Thelio Major thelio-majo... | [5342f98e5d](https://linux-hardware.org/?probe=5342f98e5d) | May 23, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [57ba2db209](https://linux-hardware.org/?probe=57ba2db209) | May 23, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [69dad0d312](https://linux-hardware.org/?probe=69dad0d312) | May 23, 2024 |
| Gigabyte      | B650I AORUS ULTRA se2       | [d7174a91c0](https://linux-hardware.org/?probe=d7174a91c0) | May 23, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [42ad45fdb0](https://linux-hardware.org/?probe=42ad45fdb0) | May 23, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [3e96be14e5](https://linux-hardware.org/?probe=3e96be14e5) | May 23, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [7106807bee](https://linux-hardware.org/?probe=7106807bee) | May 22, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | [fb438ab94d](https://linux-hardware.org/?probe=fb438ab94d) | May 22, 2024 |
| Supermicro    | X9DRD-iF                    | [c3e37574b8](https://linux-hardware.org/?probe=c3e37574b8) | May 19, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [ca50be5e65](https://linux-hardware.org/?probe=ca50be5e65) | May 19, 2024 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [2dd203a224](https://linux-hardware.org/?probe=2dd203a224) | May 18, 2024 |
| Dell          | 0D28YY A01                  | [2c136b41f3](https://linux-hardware.org/?probe=2c136b41f3) | May 18, 2024 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [29ba819911](https://linux-hardware.org/?probe=29ba819911) | May 18, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [04c04edfa1](https://linux-hardware.org/?probe=04c04edfa1) | May 17, 2024 |
| Gigabyte      | GB-BRR5H-4500               | [d99dadbc4b](https://linux-hardware.org/?probe=d99dadbc4b) | May 17, 2024 |
| ASRock        | Z77 Extreme4                | [adf0c13a95](https://linux-hardware.org/?probe=adf0c13a95) | May 17, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3c34af9c72](https://linux-hardware.org/?probe=3c34af9c72) | May 16, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [5952316fb5](https://linux-hardware.org/?probe=5952316fb5) | May 15, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [be312ef1e8](https://linux-hardware.org/?probe=be312ef1e8) | May 12, 2024 |
| Shenzhen M... | AHWSA                       | [19f474bae1](https://linux-hardware.org/?probe=19f474bae1) | May 12, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [1748ce8131](https://linux-hardware.org/?probe=1748ce8131) | May 12, 2024 |
| ASUSTek       | PRIME Z390-P                | [5c270250f4](https://linux-hardware.org/?probe=5c270250f4) | May 11, 2024 |
| ASRock        | B450M Pro4 R2.0             | [ef2b611075](https://linux-hardware.org/?probe=ef2b611075) | May 10, 2024 |
| wpc           | zrd616                      | [9b15a24303](https://linux-hardware.org/?probe=9b15a24303) | May 09, 2024 |
| Gigabyte      | Z790 UD AX                  | [38ae310bd0](https://linux-hardware.org/?probe=38ae310bd0) | May 08, 2024 |
| HP            | 8AC1                        | [34fb750829](https://linux-hardware.org/?probe=34fb750829) | May 08, 2024 |
| ASUSTek       | P8Z77-V LX2                 | [1181eb41ee](https://linux-hardware.org/?probe=1181eb41ee) | May 06, 2024 |
| Dell          | 088DT1 A01                  | [9cdeec0464](https://linux-hardware.org/?probe=9cdeec0464) | May 05, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [28d0d4304f](https://linux-hardware.org/?probe=28d0d4304f) | May 04, 2024 |
| SZMZ          | X99-S3                      | [9dc9366e04](https://linux-hardware.org/?probe=9dc9366e04) | May 03, 2024 |
| MSI           | PRO Z790-A WIFI             | [b7cb9e7573](https://linux-hardware.org/?probe=b7cb9e7573) | May 03, 2024 |
| Intel         | B75                         | [4925a7fcb7](https://linux-hardware.org/?probe=4925a7fcb7) | May 02, 2024 |
| HP            | 3646h                       | [3c2faf0d32](https://linux-hardware.org/?probe=3c2faf0d32) | May 02, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | [0299f8321b](https://linux-hardware.org/?probe=0299f8321b) | May 01, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | [569772c380](https://linux-hardware.org/?probe=569772c380) | May 01, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [2ffc5da09f](https://linux-hardware.org/?probe=2ffc5da09f) | May 01, 2024 |
| ASUSTek       | P7P55D PRO                  | [9ae885f7fd](https://linux-hardware.org/?probe=9ae885f7fd) | Apr 30, 2024 |
| ASUSTek       | M4N72-E                     | [c8920341bc](https://linux-hardware.org/?probe=c8920341bc) | Apr 29, 2024 |
| HP            | 2129                        | [40fa42996a](https://linux-hardware.org/?probe=40fa42996a) | Apr 29, 2024 |
| ASRock        | B650 PG Lightning           | [2afe25d1f8](https://linux-hardware.org/?probe=2afe25d1f8) | Apr 28, 2024 |
| MSI           | 970A-G46                    | [156b1bab44](https://linux-hardware.org/?probe=156b1bab44) | Apr 28, 2024 |
| Gigabyte      | B75M-D3H                    | [48a48b4523](https://linux-hardware.org/?probe=48a48b4523) | Apr 28, 2024 |
| HP            | 2129                        | [03800251ed](https://linux-hardware.org/?probe=03800251ed) | Apr 28, 2024 |
| System76      | Thelio Mira thelio-mira-... | [14dbfab450](https://linux-hardware.org/?probe=14dbfab450) | Apr 27, 2024 |
| Gigabyte      | H410M S2 V2                 | [a1fbe8858b](https://linux-hardware.org/?probe=a1fbe8858b) | Apr 26, 2024 |
| Dell          | 0K240Y A01                  | [6b932e4eb7](https://linux-hardware.org/?probe=6b932e4eb7) | Apr 26, 2024 |
| Acer          | FX58M                       | [d8aec92fe1](https://linux-hardware.org/?probe=d8aec92fe1) | Apr 25, 2024 |
| HP            | 8704                        | [deeb399937](https://linux-hardware.org/?probe=deeb399937) | Apr 25, 2024 |
| Dell          | 0K240Y A01                  | [554822996a](https://linux-hardware.org/?probe=554822996a) | Apr 24, 2024 |
| ASUSTek       | PRIME B450M-K II            | [31838248fa](https://linux-hardware.org/?probe=31838248fa) | Apr 24, 2024 |
| ASUSTek       | Maximus IX CODE             | [db21083720](https://linux-hardware.org/?probe=db21083720) | Apr 24, 2024 |
| ASRock        | B450M Pro4 R2.0             | [188e5e5bde](https://linux-hardware.org/?probe=188e5e5bde) | Apr 24, 2024 |
| Gigabyte      | B560M H                     | [db05a445f8](https://linux-hardware.org/?probe=db05a445f8) | Apr 24, 2024 |
| Dell          | 0C1R19 A02                  | [de862a6d95](https://linux-hardware.org/?probe=de862a6d95) | Apr 24, 2024 |
| Gigabyte      | 970A-DS3P                   | [0253ffc79c](https://linux-hardware.org/?probe=0253ffc79c) | Apr 24, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [b6aa6b2262](https://linux-hardware.org/?probe=b6aa6b2262) | Apr 22, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [d24a794778](https://linux-hardware.org/?probe=d24a794778) | Apr 22, 2024 |
| ASRock        | B450M Steel Legend          | [7fb64c7bef](https://linux-hardware.org/?probe=7fb64c7bef) | Apr 22, 2024 |
| Supermicro    | C7Q67 V1.01                 | [e63cba3bfa](https://linux-hardware.org/?probe=e63cba3bfa) | Apr 22, 2024 |
| Gigabyte      | B450M S2H                   | [d3e9e01950](https://linux-hardware.org/?probe=d3e9e01950) | Apr 21, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [ff86440a74](https://linux-hardware.org/?probe=ff86440a74) | Apr 21, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [42a4ba108a](https://linux-hardware.org/?probe=42a4ba108a) | Apr 21, 2024 |
| Intel         | B75                         | [27d3a826f4](https://linux-hardware.org/?probe=27d3a826f4) | Apr 20, 2024 |
| ASRock        | Z77 Extreme4                | [52009ffcd0](https://linux-hardware.org/?probe=52009ffcd0) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [8fd0a624a7](https://linux-hardware.org/?probe=8fd0a624a7) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [5e91dc2b03](https://linux-hardware.org/?probe=5e91dc2b03) | Apr 20, 2024 |
| ASRock        | X570 Taichi                 | [2de05483c5](https://linux-hardware.org/?probe=2de05483c5) | Apr 19, 2024 |
| ASUSTek       | P7P55D PRO                  | [712655c5bd](https://linux-hardware.org/?probe=712655c5bd) | Apr 19, 2024 |
| Gigabyte      | H170-HD3-CF                 | [4f5d1a37c3](https://linux-hardware.org/?probe=4f5d1a37c3) | Apr 19, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [6190a14941](https://linux-hardware.org/?probe=6190a14941) | Apr 19, 2024 |
| HP            | 8299                        | [aecdc0598b](https://linux-hardware.org/?probe=aecdc0598b) | Apr 19, 2024 |
| HP            | 8949 11                     | [ab13748833](https://linux-hardware.org/?probe=ab13748833) | Apr 18, 2024 |
| HP            | 8949 11                     | [3f180801bd](https://linux-hardware.org/?probe=3f180801bd) | Apr 18, 2024 |
| ASUSTek       | PRIME B450M-K II            | [e25b6a6321](https://linux-hardware.org/?probe=e25b6a6321) | Apr 18, 2024 |
| MSI           | B250M PRO-VD                | [ec68301ab8](https://linux-hardware.org/?probe=ec68301ab8) | Apr 17, 2024 |
| MSI           | Z87-G45 GAMING              | [f646b54913](https://linux-hardware.org/?probe=f646b54913) | Apr 17, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e9fcf03a9f](https://linux-hardware.org/?probe=e9fcf03a9f) | Apr 17, 2024 |
| Gigabyte      | 970A-DS3P                   | [53055c8335](https://linux-hardware.org/?probe=53055c8335) | Apr 17, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [e45ac0e9cc](https://linux-hardware.org/?probe=e45ac0e9cc) | Apr 16, 2024 |
| ASRock        | Z790 Nova WiFi              | [e7087ec7e4](https://linux-hardware.org/?probe=e7087ec7e4) | Apr 16, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [d504f8b8a6](https://linux-hardware.org/?probe=d504f8b8a6) | Apr 16, 2024 |
| Unknown       | Unknown                     | [bcaf7cac1a](https://linux-hardware.org/?probe=bcaf7cac1a) | Apr 15, 2024 |
| ASUSTek       | STRIX Z270H GAMING          | [47f139152e](https://linux-hardware.org/?probe=47f139152e) | Apr 15, 2024 |
| ASRock        | B450 Steel Legend           | [eae63cf682](https://linux-hardware.org/?probe=eae63cf682) | Apr 15, 2024 |
| ASUSTek       | P5Q-EM                      | [dc780bc9a5](https://linux-hardware.org/?probe=dc780bc9a5) | Apr 15, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [ad14cabff5](https://linux-hardware.org/?probe=ad14cabff5) | Apr 13, 2024 |
| Unknown       | Unknown                     | [31b430e45e](https://linux-hardware.org/?probe=31b430e45e) | Apr 13, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [b977bc3a0a](https://linux-hardware.org/?probe=b977bc3a0a) | Apr 12, 2024 |
| Intel         | X99 V1.0                    | [57c2d76c65](https://linux-hardware.org/?probe=57c2d76c65) | Apr 12, 2024 |
| ASUSTek       | PRIME H310T R2.0            | [66cbd66636](https://linux-hardware.org/?probe=66cbd66636) | Apr 11, 2024 |
| Itautec       | ST 4271                     | [8fc18963b3](https://linux-hardware.org/?probe=8fc18963b3) | Apr 09, 2024 |
| Dell          | 0VTJVC A00                  | [edb54fbe32](https://linux-hardware.org/?probe=edb54fbe32) | Apr 09, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [43618657fd](https://linux-hardware.org/?probe=43618657fd) | Apr 09, 2024 |
| Dell          | 088DT1 A01                  | [a22e72117f](https://linux-hardware.org/?probe=a22e72117f) | Apr 09, 2024 |
| Huanan        | X99-QD4 V1.0                | [732523a553](https://linux-hardware.org/?probe=732523a553) | Apr 09, 2024 |
| Huanan        | X99-QD4 V1.0                | [d53567aeb3](https://linux-hardware.org/?probe=d53567aeb3) | Apr 09, 2024 |
| Acer          | Aspire TC-105               | [7ecc002fc3](https://linux-hardware.org/?probe=7ecc002fc3) | Apr 07, 2024 |
| Acer          | Aspire TC-105               | [9c7c1f6869](https://linux-hardware.org/?probe=9c7c1f6869) | Apr 07, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [e7b99f79ab](https://linux-hardware.org/?probe=e7b99f79ab) | Apr 06, 2024 |
| Dell          | 0DF42J A00                  | [575fd0d93d](https://linux-hardware.org/?probe=575fd0d93d) | Apr 06, 2024 |
| Intel         | DH67CF AAG10215-203         | [c26c93bb88](https://linux-hardware.org/?probe=c26c93bb88) | Apr 06, 2024 |
| Gigabyte      | Z590I AORUS ULTRA           | [2a11ab4791](https://linux-hardware.org/?probe=2a11ab4791) | Apr 06, 2024 |
| Gigabyte      | Z590I AORUS ULTRA           | [e786bc1b13](https://linux-hardware.org/?probe=e786bc1b13) | Apr 06, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [f519652f57](https://linux-hardware.org/?probe=f519652f57) | Apr 06, 2024 |
| Biostar       | TA970                       | [b95526c668](https://linux-hardware.org/?probe=b95526c668) | Apr 05, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [b1f7625755](https://linux-hardware.org/?probe=b1f7625755) | Apr 05, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [836a40664c](https://linux-hardware.org/?probe=836a40664c) | Apr 05, 2024 |
| ASUSTek       | J1800I-C/BR                 | [bdde2d1fe9](https://linux-hardware.org/?probe=bdde2d1fe9) | Apr 05, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [a92eac3002](https://linux-hardware.org/?probe=a92eac3002) | Apr 05, 2024 |
| BESSTAR Te... | HM90                        | [6dda4c2573](https://linux-hardware.org/?probe=6dda4c2573) | Apr 05, 2024 |
| BESSTAR Te... | HM90                        | [e9b2e7f701](https://linux-hardware.org/?probe=e9b2e7f701) | Apr 05, 2024 |
| Gigabyte      | Z790 GAMING X AX            | [5aa6e72318](https://linux-hardware.org/?probe=5aa6e72318) | Apr 04, 2024 |
| ASUSTek       | P7P55D PRO                  | [0b96c3a901](https://linux-hardware.org/?probe=0b96c3a901) | Apr 02, 2024 |
| ASUSTek       | P5G41T-M                    | [731881f720](https://linux-hardware.org/?probe=731881f720) | Apr 02, 2024 |
| MSI           | MPG B550I GAMING EDGE WI... | [98c3893edd](https://linux-hardware.org/?probe=98c3893edd) | Apr 01, 2024 |
| MSI           | MAG B460M MORTAR            | [0a8f92ffe1](https://linux-hardware.org/?probe=0a8f92ffe1) | Mar 30, 2024 |
| ASUSTek       | AT3N7A-I                    | [0af90b54ec](https://linux-hardware.org/?probe=0af90b54ec) | Mar 30, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [943c4e0f41](https://linux-hardware.org/?probe=943c4e0f41) | Mar 29, 2024 |
| ASUSTek       | PRIME H310M-K R2.0          | [6f6c4699f5](https://linux-hardware.org/?probe=6f6c4699f5) | Mar 29, 2024 |
| Biostar       | A960D+V2                    | [1295e48af0](https://linux-hardware.org/?probe=1295e48af0) | Mar 28, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [ba5d17c1d9](https://linux-hardware.org/?probe=ba5d17c1d9) | Mar 28, 2024 |
| ASUSTek       | P8P67                       | [6ab2d189e5](https://linux-hardware.org/?probe=6ab2d189e5) | Mar 28, 2024 |
| ASUSTek       | P8P67                       | [eae7373113](https://linux-hardware.org/?probe=eae7373113) | Mar 28, 2024 |
| Gigabyte      | A620M DS3H                  | [2b5f386cb4](https://linux-hardware.org/?probe=2b5f386cb4) | Mar 28, 2024 |
| Dell          | 0MN1TX A00                  | [8cef7b13b5](https://linux-hardware.org/?probe=8cef7b13b5) | Mar 27, 2024 |
| Dell          | 0MN1TX A00                  | [6a8ffef6f2](https://linux-hardware.org/?probe=6a8ffef6f2) | Mar 27, 2024 |
| Apple         | Mac-F221BEC8                | [35cbc2ccda](https://linux-hardware.org/?probe=35cbc2ccda) | Mar 27, 2024 |
| Dell          | 02GDWG A00                  | [a138fcbf39](https://linux-hardware.org/?probe=a138fcbf39) | Mar 26, 2024 |
| Dell          | 0GU083 A00                  | [c7a2de496a](https://linux-hardware.org/?probe=c7a2de496a) | Mar 26, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | [e98dcc5095](https://linux-hardware.org/?probe=e98dcc5095) | Mar 26, 2024 |
| MSI           | PRO Z790-S WIFI             | [ecaa8a51cb](https://linux-hardware.org/?probe=ecaa8a51cb) | Mar 26, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [efbd82bed8](https://linux-hardware.org/?probe=efbd82bed8) | Mar 25, 2024 |
| HP            | 83EF                        | [a2e4b98916](https://linux-hardware.org/?probe=a2e4b98916) | Mar 22, 2024 |
| HP            | 83EF                        | [79c2564db3](https://linux-hardware.org/?probe=79c2564db3) | Mar 22, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [0565d53d0c](https://linux-hardware.org/?probe=0565d53d0c) | Mar 21, 2024 |
| ASUSTek       | PRIME B550M-A WIFI II       | [caecf9a750](https://linux-hardware.org/?probe=caecf9a750) | Mar 21, 2024 |
| MSI           | Z170A GAMING M3             | [8e89b3ef32](https://linux-hardware.org/?probe=8e89b3ef32) | Mar 20, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [302a31192b](https://linux-hardware.org/?probe=302a31192b) | Mar 20, 2024 |
| ASUSTek       | PRIME X570-PRO              | [56b4e033b8](https://linux-hardware.org/?probe=56b4e033b8) | Mar 20, 2024 |
| MSI           | MAG B660M MORTAR WIFI DD... | [d1ba139b4e](https://linux-hardware.org/?probe=d1ba139b4e) | Mar 19, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [37a57d5b70](https://linux-hardware.org/?probe=37a57d5b70) | Mar 19, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [0eaf5f5be0](https://linux-hardware.org/?probe=0eaf5f5be0) | Mar 18, 2024 |
| ASUSTek       | M4A785TD-V EVO              | [9a29b7badd](https://linux-hardware.org/?probe=9a29b7badd) | Mar 17, 2024 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | [16b029f8b8](https://linux-hardware.org/?probe=16b029f8b8) | Mar 17, 2024 |
| ASRock        | H110M-DVS R3.0              | [311809b062](https://linux-hardware.org/?probe=311809b062) | Mar 16, 2024 |
| Gigabyte      | A520M DS3H                  | [e9eaacfaa2](https://linux-hardware.org/?probe=e9eaacfaa2) | Mar 15, 2024 |
| Dell          | 0KV62T A00                  | [7f865ffb79](https://linux-hardware.org/?probe=7f865ffb79) | Mar 15, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [ed06ccc20a](https://linux-hardware.org/?probe=ed06ccc20a) | Mar 15, 2024 |
| System76      | Thelio thelio-r2            | [609e72eef1](https://linux-hardware.org/?probe=609e72eef1) | Mar 14, 2024 |
| Gigabyte      | H310M S2P                   | [3d5cf9dd65](https://linux-hardware.org/?probe=3d5cf9dd65) | Mar 13, 2024 |
| Gigabyte      | AX370-Gaming 3-CF           | [c0420b6b81](https://linux-hardware.org/?probe=c0420b6b81) | Mar 11, 2024 |
| Intel         | B75                         | [d0ba74ec7d](https://linux-hardware.org/?probe=d0ba74ec7d) | Mar 10, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [b07882e6fb](https://linux-hardware.org/?probe=b07882e6fb) | Mar 07, 2024 |
| MSI           | MAG Z790 TOMAHAWK MAX WI... | [f9fa747b4f](https://linux-hardware.org/?probe=f9fa747b4f) | Mar 07, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | [d5ee5ee229](https://linux-hardware.org/?probe=d5ee5ee229) | Mar 06, 2024 |
| HP            | 81C5 MVB                    | [957fd824c5](https://linux-hardware.org/?probe=957fd824c5) | Mar 05, 2024 |
| MSI           | X470 GAMING PLUS MAX        | [d746e0ee2c](https://linux-hardware.org/?probe=d746e0ee2c) | Mar 05, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | [3772b43c62](https://linux-hardware.org/?probe=3772b43c62) | Mar 05, 2024 |
| Dell          | 0HD5W2 A01                  | [f015ff4f75](https://linux-hardware.org/?probe=f015ff4f75) | Mar 05, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [e415b0c776](https://linux-hardware.org/?probe=e415b0c776) | Mar 04, 2024 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [01c04e14c0](https://linux-hardware.org/?probe=01c04e14c0) | Mar 04, 2024 |
| Intel         | B75                         | [2b0d558a5e](https://linux-hardware.org/?probe=2b0d558a5e) | Mar 04, 2024 |
| Gigabyte      | B450M DS3H-CF               | [95bfa43508](https://linux-hardware.org/?probe=95bfa43508) | Mar 04, 2024 |
| Gigabyte      | B450M DS3H-CF               | [1eb604d726](https://linux-hardware.org/?probe=1eb604d726) | Mar 04, 2024 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [abbcee09db](https://linux-hardware.org/?probe=abbcee09db) | Mar 03, 2024 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [040699f391](https://linux-hardware.org/?probe=040699f391) | Mar 03, 2024 |
| AZW           | MINI S                      | [dc07e234d0](https://linux-hardware.org/?probe=dc07e234d0) | Mar 03, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c2b4500a60](https://linux-hardware.org/?probe=c2b4500a60) | Mar 03, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [a0a450644b](https://linux-hardware.org/?probe=a0a450644b) | Mar 02, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [e8dae907db](https://linux-hardware.org/?probe=e8dae907db) | Mar 02, 2024 |
| Dell          | 02GDWG A00                  | [dd54511393](https://linux-hardware.org/?probe=dd54511393) | Mar 01, 2024 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [13c3d127e8](https://linux-hardware.org/?probe=13c3d127e8) | Mar 01, 2024 |
| HP            | 843B                        | [4293861b42](https://linux-hardware.org/?probe=4293861b42) | Mar 01, 2024 |
| HP            | 18E9                        | [9bdda08a35](https://linux-hardware.org/?probe=9bdda08a35) | Mar 01, 2024 |
| ASRock        | B550 Phantom Gaming 4       | [223fbfa988](https://linux-hardware.org/?probe=223fbfa988) | Feb 29, 2024 |
| ASRock        | H97 Anniversary             | [f4f4c960d4](https://linux-hardware.org/?probe=f4f4c960d4) | Feb 28, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [365e852379](https://linux-hardware.org/?probe=365e852379) | Feb 28, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | [5c749148f2](https://linux-hardware.org/?probe=5c749148f2) | Feb 28, 2024 |
| Intel         | H410M                       | [b22fd32a7d](https://linux-hardware.org/?probe=b22fd32a7d) | Feb 27, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [15510ee9c4](https://linux-hardware.org/?probe=15510ee9c4) | Feb 27, 2024 |
| JGINYUE       | B550i-GAMING                | [8d44c9ccdd](https://linux-hardware.org/?probe=8d44c9ccdd) | Feb 27, 2024 |
| ASUSTek       | F2A85-M                     | [a78b141db1](https://linux-hardware.org/?probe=a78b141db1) | Feb 26, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [2b4ed9044c](https://linux-hardware.org/?probe=2b4ed9044c) | Feb 25, 2024 |
| ASUSTek       | PRIME Z790-P                | [e302c30d09](https://linux-hardware.org/?probe=e302c30d09) | Feb 25, 2024 |
| ASUSTek       | P7P55D PRO                  | [f6c4f78658](https://linux-hardware.org/?probe=f6c4f78658) | Feb 24, 2024 |
| ASRock        | B450M Steel Legend          | [650af37e87](https://linux-hardware.org/?probe=650af37e87) | Feb 23, 2024 |
| ASRock        | Z68 Extreme4 Gen3           | [bc9dad6852](https://linux-hardware.org/?probe=bc9dad6852) | Feb 23, 2024 |
| MSI           | MS-B9171                    | [8d8e1e76c8](https://linux-hardware.org/?probe=8d8e1e76c8) | Feb 23, 2024 |
| ASUSTek       | Z87-K                       | [82f0780a43](https://linux-hardware.org/?probe=82f0780a43) | Feb 23, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [bade017d6b](https://linux-hardware.org/?probe=bade017d6b) | Feb 22, 2024 |
| ASUSTek       | PRIME Z490-P                | [9c9f621388](https://linux-hardware.org/?probe=9c9f621388) | Feb 21, 2024 |
| ASUSTek       | Z87-K                       | [d091e6a911](https://linux-hardware.org/?probe=d091e6a911) | Feb 21, 2024 |
| Gigabyte      | Z590 VISION D               | [8070df1f8e](https://linux-hardware.org/?probe=8070df1f8e) | Feb 21, 2024 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [dd7412b565](https://linux-hardware.org/?probe=dd7412b565) | Feb 21, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | [e65b561651](https://linux-hardware.org/?probe=e65b561651) | Feb 20, 2024 |
| Intel         | H55                         | [77825586e5](https://linux-hardware.org/?probe=77825586e5) | Feb 20, 2024 |
| HP            | 885F A                      | [0e14337b75](https://linux-hardware.org/?probe=0e14337b75) | Feb 20, 2024 |
| BESSTAR Te... | B550                        | [864d3987bc](https://linux-hardware.org/?probe=864d3987bc) | Feb 19, 2024 |
| Dell          | 0J3C2F A02                  | [17a18809d8](https://linux-hardware.org/?probe=17a18809d8) | Feb 18, 2024 |
| Gigabyte      | A320M-H-CF                  | [e115b602d3](https://linux-hardware.org/?probe=e115b602d3) | Feb 18, 2024 |
| Gigabyte      | Q87M-MK                     | [31f52cfaa6](https://linux-hardware.org/?probe=31f52cfaa6) | Feb 18, 2024 |
| HP            | 82F2                        | [10051f1b07](https://linux-hardware.org/?probe=10051f1b07) | Feb 18, 2024 |
| ASRock        | B450M Steel Legend          | [2d7aaba177](https://linux-hardware.org/?probe=2d7aaba177) | Feb 18, 2024 |
| MSI           | Z87-GD65 GAMING             | [c6883405b2](https://linux-hardware.org/?probe=c6883405b2) | Feb 17, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ac497abd97](https://linux-hardware.org/?probe=ac497abd97) | Feb 17, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [5e4e265aeb](https://linux-hardware.org/?probe=5e4e265aeb) | Feb 16, 2024 |
| Gigabyte      | B660 DS3H AX DDR4           | [993110fab0](https://linux-hardware.org/?probe=993110fab0) | Feb 16, 2024 |
| MSI           | B450M PRO-VDH MAX           | [16a3b93921](https://linux-hardware.org/?probe=16a3b93921) | Feb 16, 2024 |
| MSI           | B450M-A PRO MAX             | [dbe01c0fc4](https://linux-hardware.org/?probe=dbe01c0fc4) | Feb 16, 2024 |
| MSI           | B450M-A PRO MAX             | [06ec01ce9a](https://linux-hardware.org/?probe=06ec01ce9a) | Feb 15, 2024 |
| ASUSTek       | TUF X470-PLUS GAMING        | [76f7aa1d25](https://linux-hardware.org/?probe=76f7aa1d25) | Feb 14, 2024 |
| Fujitsu       | D3118-A2 S26361-D3118-A2    | [169a2bedd3](https://linux-hardware.org/?probe=169a2bedd3) | Feb 14, 2024 |
| MSI           | A520M-A PRO                 | [66417e286c](https://linux-hardware.org/?probe=66417e286c) | Feb 14, 2024 |
| Acer          | Predator PO3-640            | [4e920c60c3](https://linux-hardware.org/?probe=4e920c60c3) | Feb 14, 2024 |
| Acer          | Predator PO3-640            | [b081b6359d](https://linux-hardware.org/?probe=b081b6359d) | Feb 13, 2024 |
| Gigabyte      | A520M K V2                  | [dca7100475](https://linux-hardware.org/?probe=dca7100475) | Feb 13, 2024 |
| ASRock        | A320M/ac                    | [adc9f93ca8](https://linux-hardware.org/?probe=adc9f93ca8) | Feb 13, 2024 |
| HP            | 2B2C                        | [a39c469e43](https://linux-hardware.org/?probe=a39c469e43) | Feb 13, 2024 |
| Gigabyte      | H310M S2H                   | [0ccb8813c9](https://linux-hardware.org/?probe=0ccb8813c9) | Feb 12, 2024 |
| Apple         | Mac-F221BEC8                | [6e8ebecbf2](https://linux-hardware.org/?probe=6e8ebecbf2) | Feb 11, 2024 |
| ASUSTek       | P8H61                       | [6b53ddd469](https://linux-hardware.org/?probe=6b53ddd469) | Feb 11, 2024 |
| HP            | 18E5                        | [3e90471e97](https://linux-hardware.org/?probe=3e90471e97) | Feb 09, 2024 |
| HP            | 18E5                        | [9ae685a4cb](https://linux-hardware.org/?probe=9ae685a4cb) | Feb 09, 2024 |
| Gigabyte      | H310M S2H                   | [329de876ea](https://linux-hardware.org/?probe=329de876ea) | Feb 09, 2024 |
| MSI           | A320M-A PRO                 | [33988a8ce4](https://linux-hardware.org/?probe=33988a8ce4) | Feb 08, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [e3a70ea869](https://linux-hardware.org/?probe=e3a70ea869) | Feb 07, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [18bb015935](https://linux-hardware.org/?probe=18bb015935) | Feb 07, 2024 |
| Acer          | Aspire XC-603G              | [f4bc1814e8](https://linux-hardware.org/?probe=f4bc1814e8) | Feb 06, 2024 |
| ASUSTek       | P8Z68-V PRO                 | [c2ee1a3fc6](https://linux-hardware.org/?probe=c2ee1a3fc6) | Feb 04, 2024 |
| Dell          | 0C522T A03                  | [8a0946f2b4](https://linux-hardware.org/?probe=8a0946f2b4) | Feb 04, 2024 |
| MSI           | H310M PRO-VDH PLUS          | [d28656e6f3](https://linux-hardware.org/?probe=d28656e6f3) | Feb 03, 2024 |
| MSI           | H310M PRO-VDH PLUS          | [eb7d7aa84f](https://linux-hardware.org/?probe=eb7d7aa84f) | Feb 03, 2024 |
| ASUSTek       | A_F_K20CE                   | [7f1b60be2a](https://linux-hardware.org/?probe=7f1b60be2a) | Feb 03, 2024 |
| Gigabyte      | H55M-S2H                    | [e5a8865f78](https://linux-hardware.org/?probe=e5a8865f78) | Feb 03, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [2b98b922fe](https://linux-hardware.org/?probe=2b98b922fe) | Feb 03, 2024 |
| ASUSTek       | M4N72-E                     | [815b251540](https://linux-hardware.org/?probe=815b251540) | Feb 02, 2024 |
| Dell          | 0V8WGR A00                  | [9762a633ab](https://linux-hardware.org/?probe=9762a633ab) | Feb 01, 2024 |
| MSI           | B760 GAMING PLUS WIFI       | [a5425cfc63](https://linux-hardware.org/?probe=a5425cfc63) | Feb 01, 2024 |
| MSI           | B760 GAMING PLUS WIFI       | [67539ba367](https://linux-hardware.org/?probe=67539ba367) | Feb 01, 2024 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | [54beeb17dc](https://linux-hardware.org/?probe=54beeb17dc) | Jan 31, 2024 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | [65272ffc77](https://linux-hardware.org/?probe=65272ffc77) | Jan 31, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [5222452ba4](https://linux-hardware.org/?probe=5222452ba4) | Jan 30, 2024 |
| Gigabyte      | Z690 UD DDR4                | [454433be44](https://linux-hardware.org/?probe=454433be44) | Jan 30, 2024 |
| Alienware     | 07HV66 A01                  | [732d349380](https://linux-hardware.org/?probe=732d349380) | Jan 29, 2024 |
| SZMZ          | X99-S3                      | [acf24ed760](https://linux-hardware.org/?probe=acf24ed760) | Jan 29, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [4e6d22c388](https://linux-hardware.org/?probe=4e6d22c388) | Jan 28, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [a7826ae1af](https://linux-hardware.org/?probe=a7826ae1af) | Jan 28, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f80e16d62d](https://linux-hardware.org/?probe=f80e16d62d) | Jan 28, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [d5f5ab4b3f](https://linux-hardware.org/?probe=d5f5ab4b3f) | Jan 27, 2024 |
| ASUSTek       | Z170-A                      | [0f1f062eda](https://linux-hardware.org/?probe=0f1f062eda) | Jan 27, 2024 |
| Dell          | 0DF42J A00                  | [f0ac1844ad](https://linux-hardware.org/?probe=f0ac1844ad) | Jan 27, 2024 |
| ASUSTek       | PRIME A320M-K               | [b1d979bcb3](https://linux-hardware.org/?probe=b1d979bcb3) | Jan 27, 2024 |
| Foxconn       | 2ABF                        | [91412d213a](https://linux-hardware.org/?probe=91412d213a) | Jan 26, 2024 |
| Gigabyte      | Z97X-SLI-CF                 | [1eb12a361c](https://linux-hardware.org/?probe=1eb12a361c) | Jan 26, 2024 |
| ASUSTek       | P5QPL-AM                    | [1f2bb560a8](https://linux-hardware.org/?probe=1f2bb560a8) | Jan 26, 2024 |
| ASRock        | B550M-HDV                   | [afbea953be](https://linux-hardware.org/?probe=afbea953be) | Jan 26, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [068df25275](https://linux-hardware.org/?probe=068df25275) | Jan 26, 2024 |
| Huanan        | X99-8M-F V1.4               | [65388b76e1](https://linux-hardware.org/?probe=65388b76e1) | Jan 25, 2024 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [4cedf6ee3a](https://linux-hardware.org/?probe=4cedf6ee3a) | Jan 25, 2024 |
| Gigabyte      | X99-Gaming 5P               | [e306ef8710](https://linux-hardware.org/?probe=e306ef8710) | Jan 24, 2024 |
| MSI           | B460M PRO-VDH WIFI          | [8b3e1a6d31](https://linux-hardware.org/?probe=8b3e1a6d31) | Jan 24, 2024 |
| ASUSTek       | ROG Maximus Z690 HERO EV... | [340fdb1832](https://linux-hardware.org/?probe=340fdb1832) | Jan 24, 2024 |
| MSI           | H55M-E33                    | [2935476b48](https://linux-hardware.org/?probe=2935476b48) | Jan 23, 2024 |
| MSI           | B350M MORTAR                | [f728e7ad76](https://linux-hardware.org/?probe=f728e7ad76) | Jan 22, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | [ed9635f427](https://linux-hardware.org/?probe=ed9635f427) | Jan 22, 2024 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [d248b6e5a9](https://linux-hardware.org/?probe=d248b6e5a9) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [66cf4b0b5a](https://linux-hardware.org/?probe=66cf4b0b5a) | Jan 21, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [41a62ec1d4](https://linux-hardware.org/?probe=41a62ec1d4) | Jan 21, 2024 |
| Gigabyte      | B660 AORUS MASTER DDR4      | [d36c2b07fd](https://linux-hardware.org/?probe=d36c2b07fd) | Jan 20, 2024 |
| MSI           | PRO X670-P WIFI             | [a0637d4400](https://linux-hardware.org/?probe=a0637d4400) | Jan 20, 2024 |
| Dell          | 0GDG8Y A00                  | [8f41b6b7f9](https://linux-hardware.org/?probe=8f41b6b7f9) | Jan 20, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [af503dbdd1](https://linux-hardware.org/?probe=af503dbdd1) | Jan 20, 2024 |
| ASUSTek       | H97M-E                      | [d6fe598f33](https://linux-hardware.org/?probe=d6fe598f33) | Jan 20, 2024 |
| Dell          | 0TTDMJ A00                  | [e5d9f41477](https://linux-hardware.org/?probe=e5d9f41477) | Jan 19, 2024 |
| Gigabyte      | B450 AORUS M                | [06cced7a39](https://linux-hardware.org/?probe=06cced7a39) | Jan 18, 2024 |
| ASRock        | H670 PG Riptide             | [d1a75ad00a](https://linux-hardware.org/?probe=d1a75ad00a) | Jan 18, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [42e7298c19](https://linux-hardware.org/?probe=42e7298c19) | Jan 17, 2024 |
| MSI           | PRO X670-P WIFI             | [3b62b0b588](https://linux-hardware.org/?probe=3b62b0b588) | Jan 17, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [a5bd71f259](https://linux-hardware.org/?probe=a5bd71f259) | Jan 17, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [48399b3fc4](https://linux-hardware.org/?probe=48399b3fc4) | Jan 16, 2024 |
| ASUSTek       | PRIME Z490M-PLUS            | [be6d425c5a](https://linux-hardware.org/?probe=be6d425c5a) | Jan 16, 2024 |
| MSI           | MAG B660M MORTAR WIFI DD... | [58d64e6a70](https://linux-hardware.org/?probe=58d64e6a70) | Jan 16, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [adb9343764](https://linux-hardware.org/?probe=adb9343764) | Jan 16, 2024 |
| MSI           | PRO B650M-A WIFI            | [cb4fc4f2da](https://linux-hardware.org/?probe=cb4fc4f2da) | Jan 16, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [8e26115f48](https://linux-hardware.org/?probe=8e26115f48) | Jan 16, 2024 |
| MSI           | Z68A-G43                    | [9ab9ae7952](https://linux-hardware.org/?probe=9ab9ae7952) | Jan 15, 2024 |
| MSI           | PRO B650M-A WIFI            | [75e74c82af](https://linux-hardware.org/?probe=75e74c82af) | Jan 15, 2024 |
| Dell          | 0J8H4R A00                  | [ce34102531](https://linux-hardware.org/?probe=ce34102531) | Jan 15, 2024 |
| ASUSTek       | P8P67 LE                    | [8e77609cb6](https://linux-hardware.org/?probe=8e77609cb6) | Jan 14, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | [fe987e391e](https://linux-hardware.org/?probe=fe987e391e) | Jan 14, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [08074470dd](https://linux-hardware.org/?probe=08074470dd) | Jan 13, 2024 |
| Gigabyte      | 970A-DS3P                   | [1b6a4a4985](https://linux-hardware.org/?probe=1b6a4a4985) | Jan 13, 2024 |
| Gigabyte      | H610M H DDR4                | [7ad8786f92](https://linux-hardware.org/?probe=7ad8786f92) | Jan 13, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [dbcc44707c](https://linux-hardware.org/?probe=dbcc44707c) | Jan 13, 2024 |
| Dell          | 04Y8V0 A02                  | [e5e36f25f0](https://linux-hardware.org/?probe=e5e36f25f0) | Jan 12, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | [50ff1c2eb6](https://linux-hardware.org/?probe=50ff1c2eb6) | Jan 12, 2024 |
| Gigabyte      | B450M S2H                   | [5ff6a8a29a](https://linux-hardware.org/?probe=5ff6a8a29a) | Jan 12, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Pop!_OS 22.04 | 1963     | 41.83%  |
| Pop!_OS 20.04 | 866      | 18.45%  |
| Pop!_OS 21.04 | 719      | 15.32%  |
| Pop!_OS 20.10 | 673      | 14.34%  |
| Pop!_OS 21.10 | 422      | 8.99%   |
| Pop!_OS 24.04 | 24       | 0.51%   |
| Pop!_OS 19.10 | 15       | 0.32%   |
| Pop!_OS 19.04 | 6        | 0.13%   |
| Pop!_OS 18.04 | 4        | 0.09%   |
| Pop!_OS 18.10 | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Pop!_OS | 4457     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 6.9.3-76060903-generic              | 403      | 7.8%    |
| 5.11.0-7620-generic                 | 340      | 6.58%   |
| 5.8.0-7630-generic                  | 314      | 6.08%   |
| 6.2.6-76060206-generic              | 305      | 5.9%    |
| 5.4.0-7634-generic                  | 282      | 5.46%   |
| 5.8.0-7642-generic                  | 204      | 3.95%   |
| 5.13.0-7614-generic                 | 203      | 3.93%   |
| 5.4.0-7642-generic                  | 187      | 3.62%   |
| 5.11.0-7614-generic                 | 183      | 3.54%   |
| 5.17.5-76051705-generic             | 180      | 3.48%   |
| 6.0.12-76060006-generic             | 176      | 3.41%   |
| 6.8.0-76060800daily20240311-generic | 174      | 3.37%   |
| 5.13.0-7620-generic                 | 171      | 3.31%   |
| 5.19.0-76051900-generic             | 144      | 2.79%   |
| 6.5.6-76060506-generic              | 116      | 2.25%   |
| 5.16.11-76051611-generic            | 112      | 2.17%   |
| 5.15.15-76051515-generic            | 109      | 2.11%   |
| 6.0.6-76060006-generic              | 102      | 1.97%   |
| 6.6.10-76060610-generic             | 100      | 1.94%   |
| 6.4.6-76060406-generic              | 92       | 1.78%   |
| 5.15.5-76051505-generic             | 92       | 1.78%   |
| 6.6.6-76060606-generic              | 90       | 1.74%   |
| 5.11.0-7612-generic                 | 85       | 1.65%   |
| 5.8.0-7625-generic                  | 79       | 1.53%   |
| 5.18.10-76051810-generic            | 76       | 1.47%   |
| 5.11.0-7633-generic                 | 70       | 1.35%   |
| 5.17.15-76051715-generic            | 69       | 1.34%   |
| 5.16.19-76051619-generic            | 65       | 1.26%   |
| 5.15.8-76051508-generic             | 62       | 1.2%    |
| 5.16.15-76051615-generic            | 56       | 1.08%   |
| 6.5.4-76060504-generic              | 53       | 1.03%   |
| 5.15.11-76051511-generic            | 49       | 0.95%   |
| 5.4.0-7626-generic                  | 43       | 0.83%   |
| 6.2.0-76060200-generic              | 36       | 0.7%    |
| 6.1.11-76060111-generic             | 29       | 0.56%   |
| 6.0.2-76060002-generic              | 29       | 0.56%   |
| 5.15.23-76051523-generic            | 29       | 0.56%   |
| 5.4.0-7625-generic                  | 24       | 0.46%   |
| 5.4.0-7629-generic                  | 21       | 0.41%   |
| 5.19.16-76051916-generic            | 18       | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 650      | 12.8%   |
| 5.8.0   | 569      | 11.21%  |
| 5.4.0   | 538      | 10.6%   |
| 6.9.3   | 403      | 7.94%   |
| 5.13.0  | 371      | 7.31%   |
| 6.2.6   | 305      | 6.01%   |
| 6.0.12  | 183      | 3.6%    |
| 5.17.5  | 180      | 3.55%   |
| 6.8.0   | 174      | 3.43%   |
| 5.19.0  | 144      | 2.84%   |
| 6.5.6   | 116      | 2.28%   |
| 5.16.11 | 112      | 2.21%   |
| 5.15.15 | 110      | 2.17%   |
| 6.0.6   | 103      | 2.03%   |
| 6.6.10  | 100      | 1.97%   |
| 6.4.6   | 92       | 1.81%   |
| 5.15.5  | 92       | 1.81%   |
| 6.6.6   | 90       | 1.77%   |
| 5.18.10 | 76       | 1.5%    |
| 5.17.15 | 69       | 1.36%   |
| 5.16.19 | 65       | 1.28%   |
| 5.15.8  | 62       | 1.22%   |
| 5.16.15 | 56       | 1.1%    |
| 6.5.4   | 53       | 1.04%   |
| 5.15.11 | 49       | 0.97%   |
| 6.2.0   | 37       | 0.73%   |
| 6.0.2   | 30       | 0.59%   |
| 6.1.11  | 29       | 0.57%   |
| 5.15.23 | 29       | 0.57%   |
| 5.19.16 | 18       | 0.35%   |
| 5.3.0   | 17       | 0.33%   |
| 6.0.3   | 14       | 0.28%   |
| 5.8.5   | 8        | 0.16%   |
| 5.0.0   | 6        | 0.12%   |
| 5.8.12  | 5        | 0.1%    |
| 6.3.7   | 3        | 0.06%   |
| 6.1.0   | 3        | 0.06%   |
| 5.7.8   | 3        | 0.06%   |
| 5.7.0   | 3        | 0.06%   |
| 5.6.16  | 3        | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 652      | 12.98%  |
| 5.8     | 591      | 11.77%  |
| 5.4     | 540      | 10.75%  |
| 6.9     | 405      | 8.06%   |
| 5.13    | 376      | 7.49%   |
| 5.15    | 344      | 6.85%   |
| 6.2     | 339      | 6.75%   |
| 6.0     | 325      | 6.47%   |
| 5.17    | 247      | 4.92%   |
| 5.16    | 224      | 4.46%   |
| 6.6     | 184      | 3.66%   |
| 6.8     | 175      | 3.48%   |
| 6.5     | 171      | 3.41%   |
| 5.19    | 162      | 3.23%   |
| 6.4     | 94       | 1.87%   |
| 5.18    | 78       | 1.55%   |
| 6.1     | 35       | 0.7%    |
| 5.3     | 17       | 0.34%   |
| 5.7     | 14       | 0.28%   |
| 5.6     | 8        | 0.16%   |
| 5.10    | 8        | 0.16%   |
| 6.3     | 6        | 0.12%   |
| 5.0     | 6        | 0.12%   |
| 5.9     | 5        | 0.1%    |
| 5.14    | 5        | 0.1%    |
| 5.12    | 4        | 0.08%   |
| 6.7     | 2        | 0.04%   |
| 6.11    | 2        | 0.04%   |
| 6.10    | 1        | 0.02%   |
| 4.18    | 1        | 0.02%   |
| 4.15    | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 4457     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 4279     | 95.26%  |
| KDE5            | 58       | 1.29%   |
| KDE             | 34       | 0.76%   |
| COSMIC          | 29       | 0.65%   |
| Unknown         | 24       | 0.53%   |
| X-Cinnamon      | 21       | 0.47%   |
| XFCE            | 10       | 0.22%   |
| MATE            | 9        | 0.2%    |
| GNOME Flashback | 6        | 0.13%   |
| LXQt            | 5        | 0.11%   |
| Cinnamon        | 5        | 0.11%   |
| i3              | 4        | 0.09%   |
| Unity           | 2        | 0.04%   |
| Budgie          | 2        | 0.04%   |
| UKUI            | 1        | 0.02%   |
| Pantheon        | 1        | 0.02%   |
| GNOME Classic   | 1        | 0.02%   |
| Deepin          | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 4332     | 96.59%  |
| Wayland | 132      | 2.94%   |
| Unknown | 13       | 0.29%   |
| Tty     | 8        | 0.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 3724     | 82.7%   |
| GDM3           | 394      | 8.75%   |
| GDM            | 361      | 8.02%   |
| SDDM           | 14       | 0.31%   |
| COSMIC-GREETER | 4        | 0.09%   |
| TDM            | 3        | 0.07%   |
| LightDM        | 3        | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 2528     | 56.1%   |
| en_GB   | 338      | 7.5%    |
| pt_BR   | 292      | 6.48%   |
| de_DE   | 265      | 5.88%   |
| C       | 173      | 3.84%   |
| en_AU   | 133      | 2.95%   |
| en_CA   | 124      | 2.75%   |
| fr_FR   | 91       | 2.02%   |
| it_IT   | 67       | 1.49%   |
| ru_RU   | 55       | 1.22%   |
| es_ES   | 51       | 1.13%   |
| pl_PL   | 39       | 0.87%   |
| sv_SE   | 30       | 0.67%   |
| nl_NL   | 30       | 0.67%   |
| Unknown | 26       | 0.58%   |
| pt_PT   | 16       | 0.36%   |
| fi_FI   | 15       | 0.33%   |
| da_DK   | 13       | 0.29%   |
| fr_CA   | 12       | 0.27%   |
| es_CL   | 12       | 0.27%   |
| es_AR   | 11       | 0.24%   |
| ja_JP   | 10       | 0.22%   |
| en_ZA   | 10       | 0.22%   |
| en_IN   | 10       | 0.22%   |
| en_DK   | 10       | 0.22%   |
| en_NZ   | 9        | 0.2%    |
| cs_CZ   | 9        | 0.2%    |
| zh_TW   | 8        | 0.18%   |
| sk_SK   | 8        | 0.18%   |
| nl_BE   | 8        | 0.18%   |
| tr_TR   | 7        | 0.16%   |
| nb_NO   | 7        | 0.16%   |
| hu_HU   | 7        | 0.16%   |
| de_CH   | 7        | 0.16%   |
| es_MX   | 6        | 0.13%   |
| de_AT   | 6        | 0.13%   |
| zh_CN   | 4        | 0.09%   |
| ro_RO   | 4        | 0.09%   |
| hr_HR   | 4        | 0.09%   |
| fr_CH   | 4        | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3623     | 80.31%  |
| EFI  | 888      | 19.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 4289     | 95.8%   |
| Btrfs   | 83       | 1.85%   |
| Overlay | 82       | 1.83%   |
| Xfs     | 10       | 0.22%   |
| Zfs     | 6        | 0.13%   |
| Unknown | 6        | 0.13%   |
| Tmpfs   | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3709     | 82.48%  |
| GPT     | 699      | 15.54%  |
| MBR     | 89       | 1.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4310     | 96.21%  |
| Yes       | 170      | 3.79%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4032     | 89.86%  |
| Yes       | 455      | 10.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1284     | 28.81%  |
| Gigabyte Technology                  | 853      | 19.14%  |
| MSI                                  | 693      | 15.55%  |
| ASRock                               | 422      | 9.47%   |
| Dell                                 | 325      | 7.29%   |
| Hewlett-Packard                      | 232      | 5.21%   |
| Lenovo                               | 104      | 2.33%   |
| Intel                                | 86       | 1.93%   |
| System76                             | 41       | 0.92%   |
| Acer                                 | 36       | 0.81%   |
| Unknown                              | 33       | 0.74%   |
| Pegatron                             | 28       | 0.63%   |
| Biostar                              | 27       | 0.61%   |
| Fujitsu                              | 23       | 0.52%   |
| Alienware                            | 23       | 0.52%   |
| Foxconn                              | 20       | 0.45%   |
| Apple                                | 20       | 0.45%   |
| ECS                                  | 16       | 0.36%   |
| Huanan                               | 14       | 0.31%   |
| Supermicro                           | 13       | 0.29%   |
| Positivo                             | 13       | 0.29%   |
| Medion                               | 10       | 0.22%   |
| BESSTAR Tech                         | 10       | 0.22%   |
| PCWare                               | 8        | 0.18%   |
| MACHINIST                            | 7        | 0.16%   |
| Gateway                              | 7        | 0.16%   |
| AZW                                  | 7        | 0.16%   |
| EVGA                                 | 6        | 0.13%   |
| Shenzhen Meigao Electronic Equipment | 5        | 0.11%   |
| NZXT                                 | 5        | 0.11%   |
| Minix                                | 5        | 0.11%   |
| JGINYUE                              | 5        | 0.11%   |
| OEM                                  | 4        | 0.09%   |
| AMI                                  | 4        | 0.09%   |
| Samsung Electronics                  | 3        | 0.07%   |
| Packard Bell                         | 3        | 0.07%   |
| MAXSUN                               | 3        | 0.07%   |
| eMachines                            | 3        | 0.07%   |
| ASRockRack                           | 3        | 0.07%   |
| TYAN Computer                        | 2        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 108      | 2.42%   |
| ASUS TUF Gaming X570-PLUS      | 50       | 1.12%   |
| MSI MS-7C02                    | 37       | 0.83%   |
| ASUS ROG STRIX B550-F GAMING   | 35       | 0.79%   |
| Gigabyte B450M DS3H            | 34       | 0.76%   |
| Unknown                        | 34       | 0.76%   |
| MSI MS-7C37                    | 33       | 0.74%   |
| MSI MS-7B86                    | 32       | 0.72%   |
| ASUS ROG STRIX B450-F GAMING   | 31       | 0.7%    |
| Dell OptiPlex 9020             | 25       | 0.56%   |
| ASUS PRIME B450M-A             | 25       | 0.56%   |
| Gigabyte X570 AORUS ELITE      | 23       | 0.52%   |
| Dell OptiPlex 7010             | 23       | 0.52%   |
| System76 Thelio                | 22       | 0.49%   |
| MSI MS-7C91                    | 19       | 0.43%   |
| Gigabyte X570 AORUS MASTER     | 19       | 0.43%   |
| Gigabyte A320M-S2H             | 19       | 0.43%   |
| ASRock B450M Steel Legend      | 18       | 0.4%    |
| ASRock B450M Pro4              | 18       | 0.4%    |
| MSI MS-7C56                    | 17       | 0.38%   |
| MSI MS-7B79                    | 16       | 0.36%   |
| Gigabyte B450 AORUS M          | 16       | 0.36%   |
| MSI MS-7B89                    | 15       | 0.34%   |
| Gigabyte B450 AORUS PRO WIFI   | 15       | 0.34%   |
| ASUS ROG STRIX B550-I GAMING   | 15       | 0.34%   |
| MSI MS-7C95                    | 14       | 0.31%   |
| MSI MS-7C84                    | 14       | 0.31%   |
| Gigabyte B550I AORUS PRO AX    | 14       | 0.31%   |
| Gigabyte B450 I AORUS PRO WIFI | 14       | 0.31%   |
| Dell OptiPlex 790              | 14       | 0.31%   |
| ASUS PRIME A320M-K             | 14       | 0.31%   |
| MSI MS-7A38                    | 13       | 0.29%   |
| Gigabyte B75M-D3H              | 13       | 0.29%   |
| ASUS TUF Gaming B550-PLUS      | 13       | 0.29%   |
| ASUS ROG STRIX X570-E GAMING   | 13       | 0.29%   |
| ASUS PRIME B450M-GAMING/BR     | 13       | 0.29%   |
| MSI MS-7693                    | 12       | 0.27%   |
| Dell OptiPlex 3020             | 12       | 0.27%   |
| ASUS TUF Gaming X570-PRO       | 12       | 0.27%   |
| ASUS TUF Gaming B550M-PLUS     | 12       | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 300      | 6.73%   |
| ASUS PRIME             | 252      | 5.65%   |
| Dell OptiPlex          | 181      | 4.06%   |
| ASUS TUF               | 169      | 3.79%   |
| ASUS All               | 108      | 2.42%   |
| Gigabyte X570          | 89       | 2%      |
| HP Compaq              | 66       | 1.48%   |
| Gigabyte B450          | 59       | 1.32%   |
| Lenovo ThinkCentre     | 58       | 1.3%    |
| Dell Precision         | 57       | 1.28%   |
| Gigabyte B450M         | 52       | 1.17%   |
| Gigabyte B550          | 45       | 1.01%   |
| ASRock B450M           | 44       | 0.99%   |
| System76 Thelio        | 41       | 0.92%   |
| ASRock X570            | 39       | 0.88%   |
| MSI MS-7C02            | 37       | 0.83%   |
| Unknown                | 34       | 0.76%   |
| MSI MS-7C37            | 33       | 0.74%   |
| Dell Inspiron          | 33       | 0.74%   |
| MSI MS-7B86            | 32       | 0.72%   |
| HP EliteDesk           | 30       | 0.67%   |
| ASRock B450            | 26       | 0.58%   |
| ASUS SABERTOOTH        | 25       | 0.56%   |
| Acer Aspire            | 25       | 0.56%   |
| Gigabyte B550M         | 24       | 0.54%   |
| Dell XPS               | 24       | 0.54%   |
| Gigabyte Z390          | 23       | 0.52%   |
| Gigabyte A320M-S2H     | 23       | 0.52%   |
| ASUS P8Z77-V           | 20       | 0.45%   |
| ASUS M5A78L-M          | 20       | 0.45%   |
| MSI MS-7C91            | 19       | 0.43%   |
| Gigabyte GA-78LMT-USB3 | 19       | 0.43%   |
| ASUS M5A97             | 19       | 0.43%   |
| HP ProDesk             | 18       | 0.4%    |
| MSI MS-7C56            | 17       | 0.38%   |
| Lenovo IdeaCentre      | 17       | 0.38%   |
| ASUS Maximus           | 17       | 0.38%   |
| ASRock B550            | 17       | 0.38%   |
| MSI MS-7B79            | 16       | 0.36%   |
| MSI MS-7B89            | 15       | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 634      | 14.22%  |
| 2020 | 517      | 11.6%   |
| 2019 | 488      | 10.95%  |
| 2012 | 336      | 7.54%   |
| 2017 | 314      | 7.05%   |
| 2013 | 289      | 6.48%   |
| 2021 | 274      | 6.15%   |
| 2014 | 261      | 5.86%   |
| 2011 | 233      | 5.23%   |
| 2022 | 194      | 4.35%   |
| 2016 | 179      | 4.02%   |
| 2015 | 171      | 3.84%   |
| 2010 | 155      | 3.48%   |
| 2009 | 150      | 3.37%   |
| 2023 | 89       | 2%      |
| 2008 | 78       | 1.75%   |
| 2007 | 60       | 1.35%   |
| 2024 | 22       | 0.49%   |
| 2006 | 12       | 0.27%   |
| 2005 | 1        | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4457     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 4452     | 99.87%  |
| Enabled  | 6        | 0.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4455     | 99.96%  |
| Yes  | 2        | 0.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1414     | 31.08%  |
| 32.01-64.0      | 1080     | 23.74%  |
| 8.01-16.0       | 750      | 16.48%  |
| 4.01-8.0        | 404      | 8.88%   |
| 64.01-256.0     | 364      | 8%      |
| 3.01-4.0        | 294      | 6.46%   |
| 24.01-32.0      | 189      | 4.15%   |
| 1.01-2.0        | 32       | 0.7%    |
| 2.01-3.0        | 12       | 0.26%   |
| More than 256.0 | 10       | 0.22%   |
| 0.51-1.0        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 1379     | 27.97%  |
| 2.01-3.0    | 1129     | 22.9%   |
| 1.01-2.0    | 951      | 19.29%  |
| 3.01-4.0    | 852      | 17.28%  |
| 8.01-16.0   | 486      | 9.86%   |
| 16.01-24.0  | 73       | 1.48%   |
| 24.01-32.0  | 24       | 0.49%   |
| 32.01-64.0  | 22       | 0.45%   |
| 0.51-1.0    | 10       | 0.2%    |
| 64.01-256.0 | 4        | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1482     | 32.03%  |
| 2      | 1403     | 30.32%  |
| 3      | 846      | 18.28%  |
| 4      | 477      | 10.31%  |
| 5      | 216      | 4.67%   |
| 6      | 100      | 2.16%   |
| 7      | 39       | 0.84%   |
| 0      | 18       | 0.39%   |
| 8      | 12       | 0.26%   |
| 9      | 10       | 0.22%   |
| 11     | 9        | 0.19%   |
| 12     | 3        | 0.06%   |
| 10     | 3        | 0.06%   |
| 14     | 2        | 0.04%   |
| 13     | 2        | 0.04%   |
| 26     | 1        | 0.02%   |
| 23     | 1        | 0.02%   |
| 22     | 1        | 0.02%   |
| 20     | 1        | 0.02%   |
| 19     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3129     | 69.47%  |
| Yes       | 1375     | 30.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4406     | 98.83%  |
| No        | 52       | 1.17%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2422     | 53.77%  |
| No        | 2082     | 46.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2583     | 57.31%  |
| Yes       | 1924     | 42.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1520     | 33.94%  |
| Brazil       | 387      | 8.64%   |
| Germany      | 365      | 8.15%   |
| UK           | 249      | 5.56%   |
| Canada       | 241      | 5.38%   |
| Australia    | 160      | 3.57%   |
| Italy        | 112      | 2.5%    |
| Netherlands  | 104      | 2.32%   |
| France       | 102      | 2.28%   |
| Sweden       | 86       | 1.92%   |
| Poland       | 76       | 1.7%    |
| Russia       | 71       | 1.59%   |
| Spain        | 54       | 1.21%   |
| Finland      | 48       | 1.07%   |
| South Africa | 45       | 1%      |
| India        | 43       | 0.96%   |
| Switzerland  | 40       | 0.89%   |
| Austria      | 38       | 0.85%   |
| Mexico       | 35       | 0.78%   |
| Norway       | 34       | 0.76%   |
| Denmark      | 33       | 0.74%   |
| New Zealand  | 32       | 0.71%   |
| Romania      | 31       | 0.69%   |
| Portugal     | 31       | 0.69%   |
| Belgium      | 31       | 0.69%   |
| Greece       | 30       | 0.67%   |
| Argentina    | 28       | 0.63%   |
| Hungary      | 27       | 0.6%    |
| Czechia      | 26       | 0.58%   |
| Philippines  | 23       | 0.51%   |
| Bulgaria     | 22       | 0.49%   |
| Japan        | 20       | 0.45%   |
| Chile        | 19       | 0.42%   |
| Malaysia     | 16       | 0.36%   |
| Slovakia     | 15       | 0.33%   |
| Serbia       | 15       | 0.33%   |
| Ukraine      | 13       | 0.29%   |
| Turkey       | 13       | 0.29%   |
| Israel       | 13       | 0.29%   |
| Ireland      | 13       | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 52       | 1.11%   |
| Sydney         | 47       | 1.01%   |
| Berlin         | 34       | 0.73%   |
| Melbourne      | 29       | 0.62%   |
| Rio de Janeiro | 28       | 0.6%    |
| Helsinki       | 25       | 0.53%   |
| Brisbane       | 24       | 0.51%   |
| Seattle        | 22       | 0.47%   |
| Miami          | 22       | 0.47%   |
| Chicago        | 21       | 0.45%   |
| Vienna         | 20       | 0.43%   |
| Denver         | 20       | 0.43%   |
| Toronto        | 19       | 0.41%   |
| Milan          | 19       | 0.41%   |
| Dallas         | 18       | 0.39%   |
| Warsaw         | 17       | 0.36%   |
| New York       | 17       | 0.36%   |
| Montreal       | 17       | 0.36%   |
| Perth          | 16       | 0.34%   |
| Moscow         | 16       | 0.34%   |
| Hamburg        | 16       | 0.34%   |
| Edmonton       | 16       | 0.34%   |
| Browning       | 16       | 0.34%   |
| Auckland       | 16       | 0.34%   |
| Rome           | 15       | 0.32%   |
| London         | 15       | 0.32%   |
| Budapest       | 15       | 0.32%   |
| Amsterdam      | 15       | 0.32%   |
| Phoenix        | 14       | 0.3%    |
| Cologne        | 14       | 0.3%    |
| Adelaide       | 14       | 0.3%    |
| St Louis       | 13       | 0.28%   |
| Cape Town      | 13       | 0.28%   |
| Calgary        | 13       | 0.28%   |
| Athens         | 13       | 0.28%   |
| Sofia          | 12       | 0.26%   |
| Los Angeles    | 12       | 0.26%   |
| Atlanta        | 12       | 0.26%   |
| Washington     | 11       | 0.24%   |
| Richmond       | 11       | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 1573     | 2761   | 17.77%  |
| Seagate                     | 1458     | 2342   | 16.47%  |
| WDC                         | 1388     | 2145   | 15.68%  |
| SanDisk                     | 556      | 756    | 6.28%   |
| Kingston                    | 530      | 699    | 5.99%   |
| Crucial                     | 425      | 624    | 4.8%    |
| Toshiba                     | 364      | 476    | 4.11%   |
| Hitachi                     | 208      | 288    | 2.35%   |
| Intel                       | 172      | 248    | 1.94%   |
| Phison                      | 158      | 236    | 1.79%   |
| A-DATA Technology           | 135      | 169    | 1.53%   |
| Micron/Crucial Technology   | 127      | 177    | 1.43%   |
| Phison Electronics          | 103      | 167    | 1.16%   |
| Silicon Motion              | 101      | 137    | 1.14%   |
| PNY                         | 100      | 129    | 1.13%   |
| China                       | 98       | 148    | 1.11%   |
| Unknown                     | 76       | 145    | 0.86%   |
| SK hynix                    | 69       | 94     | 0.78%   |
| HGST                        | 68       | 89     | 0.77%   |
| SPCC                        | 56       | 86     | 0.63%   |
| Kingston Technology Company | 55       | 71     | 0.62%   |
| OCZ                         | 54       | 74     | 0.61%   |
| Micron Technology           | 49       | 65     | 0.55%   |
| Realtek Semiconductor       | 47       | 56     | 0.53%   |
| Team                        | 44       | 52     | 0.5%    |
| Corsair                     | 42       | 56     | 0.47%   |
| XPG                         | 41       | 58     | 0.46%   |
| Patriot                     | 37       | 56     | 0.42%   |
| Intenso                     | 33       | 40     | 0.37%   |
| Maxtor                      | 31       | 32     | 0.35%   |
| Hewlett-Packard             | 26       | 35     | 0.29%   |
| Lexar                       | 21       | 30     | 0.24%   |
| ADATA Technology            | 20       | 23     | 0.23%   |
| Netac                       | 19       | 23     | 0.21%   |
| JMicron Technology          | 19       | 35     | 0.21%   |
| Gigabyte Technology         | 19       | 20     | 0.21%   |
| Apple                       | 18       | 21     | 0.2%    |
| Unknown                     | 18       | 20     | 0.2%    |
| T-FORCE                     | 17       | 21     | 0.19%   |
| KingSpec                    | 17       | 21     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB                           | 132      | 1.28%   |
| Kingston SA400S37240G 240GB SSD                      | 129      | 1.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 126      | 1.22%   |
| Seagate ST2000DM008-2FR102 2TB                       | 123      | 1.19%   |
| Seagate ST1000DM010-2EP102 1TB                       | 119      | 1.15%   |
| Samsung SSD 850 EVO 250GB                            | 119      | 1.15%   |
| Samsung NVMe SSD Drive 500GB                         | 117      | 1.13%   |
| Samsung SSD 850 EVO 500GB                            | 97       | 0.94%   |
| Samsung SSD 860 EVO 500GB                            | 95       | 0.92%   |
| Samsung SSD 860 EVO 1TB                              | 93       | 0.9%    |
| Seagate ST500DM002-1BD142 500GB                      | 87       | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 84       | 0.81%   |
| Kingston SA400S37120G 120GB SSD                      | 78       | 0.75%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 76       | 0.73%   |
| SanDisk NVMe SSD Drive 1TB                           | 73       | 0.71%   |
| Crucial CT1000MX500SSD1 1TB                          | 73       | 0.71%   |
| Kingston SA400S37480G 480GB SSD                      | 72       | 0.7%    |
| SanDisk NVMe SSD Drive 500GB                         | 67       | 0.65%   |
| Seagate ST4000DM004-2CV104 4TB                       | 61       | 0.59%   |
| Toshiba DT01ACA100 1TB                               | 59       | 0.57%   |
| Crucial CT500MX500SSD1 500GB                         | 57       | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB                       | 55       | 0.53%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB               | 47       | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                     | 44       | 0.43%   |
| Seagate ST1000DM003-1ER162 1TB                       | 43       | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                         | 43       | 0.42%   |
| Samsung SSD 870 QVO 1TB                              | 43       | 0.42%   |
| Phison NVMe SSD Drive 1TB                            | 43       | 0.42%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 43       | 0.42%   |
| Samsung SSD 860 EVO 250GB                            | 41       | 0.4%    |
| Crucial CT240BX500SSD1 240GB                         | 41       | 0.4%    |
| Samsung SSD 980 1TB                                  | 40       | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB                       | 37       | 0.36%   |
| Seagate ST2000DM001-1CH164 2TB                       | 37       | 0.36%   |
| Samsung SSD 840 EVO 250GB                            | 37       | 0.36%   |
| Micron/Crucial NVMe SSD Drive 1TB                    | 37       | 0.36%   |
| Toshiba HDWD110 1TB                                  | 36       | 0.35%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 35       | 0.34%   |
| Seagate ST2000DM001-1ER164 2TB                       | 35       | 0.34%   |
| Samsung SSD 860 QVO 1TB                              | 35       | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1415     | 2223   | 40.57%  |
| WDC                 | 1189     | 1817   | 34.09%  |
| Toshiba             | 316      | 416    | 9.06%   |
| Hitachi             | 208      | 288    | 5.96%   |
| Samsung Electronics | 137      | 169    | 3.93%   |
| HGST                | 68       | 89     | 1.95%   |
| Maxtor              | 27       | 28     | 0.77%   |
| Unknown             | 26       | 36     | 0.75%   |
| SABRENT             | 15       | 17     | 0.43%   |
| JMicron Technology  | 12       | 24     | 0.34%   |
| Apple               | 12       | 14     | 0.34%   |
| ASMT                | 11       | 15     | 0.32%   |
| TO Exter            | 8        | 11     | 0.23%   |
| Hewlett-Packard     | 7        | 10     | 0.2%    |
| Fujitsu             | 5        | 9      | 0.14%   |
| External            | 4        | 4      | 0.11%   |
| USB                 | 3        | 4      | 0.09%   |
| LaCie               | 3        | 5      | 0.09%   |
| ExcelStor           | 3        | 3      | 0.09%   |
| WD MediaMax         | 2        | 8      | 0.06%   |
| MaxDigital          | 2        | 2      | 0.06%   |
| Magnetic Data       | 2        | 2      | 0.06%   |
| Unknown             | 2        | 3      | 0.06%   |
| XrayDisk            | 1        | 1      | 0.03%   |
| RSH-339             | 1        | 1      | 0.03%   |
| Quantum             | 1        | 1      | 0.03%   |
| OEM                 | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 2      | 0.03%   |
| Inateck             | 1        | 1      | 0.03%   |
| HPE                 | 1        | 1      | 0.03%   |
| HGST HTS            | 1        | 1      | 0.03%   |
| H/W                 | 1        | 1      | 0.03%   |
| Glyph               | 1        | 2      | 0.03%   |
| ASMT109x            | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 858      | 1361   | 26.86%  |
| Kingston            | 440      | 576    | 13.78%  |
| Crucial             | 380      | 541    | 11.9%   |
| SanDisk             | 265      | 346    | 8.3%    |
| WDC                 | 215      | 272    | 6.73%   |
| A-DATA Technology   | 116      | 148    | 3.63%   |
| PNY                 | 98       | 127    | 3.07%   |
| China               | 96       | 146    | 3.01%   |
| Intel               | 69       | 96     | 2.16%   |
| OCZ                 | 53       | 70     | 1.66%   |
| SPCC                | 45       | 58     | 1.41%   |
| Team                | 39       | 46     | 1.22%   |
| Patriot             | 37       | 56     | 1.16%   |
| SK hynix            | 33       | 47     | 1.03%   |
| Corsair             | 31       | 39     | 0.97%   |
| Micron Technology   | 26       | 31     | 0.81%   |
| Intenso             | 25       | 32     | 0.78%   |
| Toshiba             | 23       | 25     | 0.72%   |
| Seagate             | 23       | 38     | 0.72%   |
| Lexar               | 17       | 25     | 0.53%   |
| KingSpec            | 17       | 21     | 0.53%   |
| Apacer              | 17       | 21     | 0.53%   |
| Transcend           | 16       | 20     | 0.5%    |
| Hewlett-Packard     | 16       | 22     | 0.5%    |
| Netac               | 14       | 17     | 0.44%   |
| Gigabyte Technology | 13       | 14     | 0.41%   |
| GOODRAM             | 12       | 13     | 0.38%   |
| LITEON              | 11       | 16     | 0.34%   |
| Mushkin             | 10       | 13     | 0.31%   |
| LITEONIT            | 10       | 11     | 0.31%   |
| Plextor             | 9        | 12     | 0.28%   |
| KingDian            | 8        | 14     | 0.25%   |
| Verbatim            | 7        | 11     | 0.22%   |
| Dogfish             | 6        | 10     | 0.19%   |
| T-FORCE             | 5        | 6      | 0.16%   |
| OWC                 | 5        | 15     | 0.16%   |
| Maxtor              | 4        | 4      | 0.13%   |
| Integral            | 4        | 4      | 0.13%   |
| Fanxiang            | 4        | 4      | 0.13%   |
| Apple               | 4        | 5      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2732     | 5210   | 36.86%  |
| SSD     | 2569     | 4490   | 34.66%  |
| NVMe    | 1929     | 3347   | 26.03%  |
| Unknown | 164      | 283    | 2.21%   |
| MMC     | 18       | 22     | 0.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3801     | 9351   | 62.17%  |
| NVMe | 1924     | 3320   | 31.47%  |
| SAS  | 371      | 659    | 6.07%   |
| MMC  | 18       | 22     | 0.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2714     | 4702   | 46.28%  |
| 0.51-1.0   | 1692     | 2658   | 28.85%  |
| 1.01-2.0   | 800      | 1223   | 13.64%  |
| 3.01-4.0   | 283      | 491    | 4.83%   |
| 4.01-10.0  | 173      | 303    | 2.95%   |
| 2.01-3.0   | 165      | 243    | 2.81%   |
| 10.01-20.0 | 37       | 80     | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1004     | 21.39%  |
| 501-1000       | 950      | 20.24%  |
| 251-500        | 918      | 19.56%  |
| 1001-2000      | 678      | 14.44%  |
| More than 3000 | 518      | 11.04%  |
| 2001-3000      | 280      | 5.97%   |
| 51-100         | 143      | 3.05%   |
| 1-20           | 103      | 2.19%   |
| 21-50          | 65       | 1.38%   |
| Unknown        | 35       | 0.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1412     | 28.73%  |
| 21-50          | 830      | 16.89%  |
| 101-250        | 637      | 12.96%  |
| 51-100         | 510      | 10.38%  |
| 251-500        | 485      | 9.87%   |
| 501-1000       | 410      | 8.34%   |
| 1001-2000      | 289      | 5.88%   |
| More than 3000 | 191      | 3.89%   |
| 2001-3000      | 116      | 2.36%   |
| Unknown        | 35       | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4        | 4      | 1.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4        | 4      | 1.93%   |
| WDC WD10EZEX-60WN4A0 1TB              | 3        | 3      | 1.45%   |
| Seagate ST1500DL003-9VT16L 1TB        | 3        | 5      | 1.45%   |
| Seagate ST1000DM003-9YN162 1TB        | 3        | 3      | 1.45%   |
| Samsung Electronics HD502HI 500GB     | 3        | 5      | 1.45%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 5      | 1.45%   |
| Kingston SA400S37120G 120GB SSD       | 3        | 5      | 1.45%   |
| WDC WD3200AAKS-75B3A0 320GB           | 2        | 2      | 0.97%   |
| WDC WD10EZEX-00BN5A0 1TB              | 2        | 3      | 0.97%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2        | 2      | 0.97%   |
| Toshiba MQ01ABD100 1TB                | 2        | 2      | 0.97%   |
| Toshiba HDWD110 1TB                   | 2        | 2      | 0.97%   |
| Seagate ST8000DM004-2CX188 8TB        | 2        | 2      | 0.97%   |
| Seagate ST3750528AS 752GB             | 2        | 2      | 0.97%   |
| Seagate ST3250310AS 250GB             | 2        | 4      | 0.97%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 0.97%   |
| SanDisk SSD PLUS 240GB                | 2        | 2      | 0.97%   |
| Samsung Electronics SSD 870 EVO 1TB   | 2        | 2      | 0.97%   |
| Samsung Electronics SSD 850 EVO 250GB | 2        | 2      | 0.97%   |
| Samsung Electronics HD154UI 1TB       | 2        | 2      | 0.97%   |
| Samsung Electronics HD103SJ 1TB       | 2        | 2      | 0.97%   |
| Samsung Electronics HD103SI 1TB       | 2        | 2      | 0.97%   |
| Kingston SA400S37480G 480GB SSD       | 2        | 2      | 0.97%   |
| Hitachi HDS721010CLA332 1TB           | 2        | 2      | 0.97%   |
| Hitachi HDP725050GLA360 500GB         | 2        | 2      | 0.97%   |
| HGST HTS721010A9E630 1TB              | 2        | 2      | 0.97%   |
| Crucial CT525MX300SSD1 528GB          | 2        | 2      | 0.97%   |
| China SSD 240GB                       | 2        | 2      | 0.97%   |
| WDC WD80EZZX-11CSGA0 8TB              | 1        | 2      | 0.48%   |
| WDC WD7500BPVT-60HXZT1 752GB          | 1        | 1      | 0.48%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1        | 1      | 0.48%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1        | 1      | 0.48%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1        | 1      | 0.48%   |
| WDC WD5001AALS-00J7B1 500GB           | 1        | 1      | 0.48%   |
| WDC WD5000LPVX-28V0TT0 500GB          | 1        | 1      | 0.48%   |
| WDC WD5000LPLX-00ZNTT0 500GB          | 1        | 2      | 0.48%   |
| WDC WD5000BEVT-75A0RT0 500GB          | 1        | 2      | 0.48%   |
| WDC WD5000AVVS-63H0B1 500GB           | 1        | 1      | 0.48%   |
| WDC WD5000AAKX-753CA1 500GB           | 1        | 1      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 50       | 63     | 25.25%  |
| WDC                         | 49       | 70     | 24.75%  |
| Samsung Electronics         | 30       | 39     | 15.15%  |
| Toshiba                     | 11       | 11     | 5.56%   |
| Kingston                    | 9        | 13     | 4.55%   |
| Crucial                     | 8        | 8      | 4.04%   |
| Hitachi                     | 7        | 8      | 3.54%   |
| HGST                        | 7        | 7      | 3.54%   |
| SanDisk                     | 5        | 5      | 2.53%   |
| A-DATA Technology           | 4        | 4      | 2.02%   |
| Intel                       | 2        | 2      | 1.01%   |
| China                       | 2        | 2      | 1.01%   |
| Apple                       | 2        | 2      | 1.01%   |
| Team                        | 1        | 1      | 0.51%   |
| SPCC                        | 1        | 1      | 0.51%   |
| SABRENT                     | 1        | 1      | 0.51%   |
| S3+                         | 1        | 1      | 0.51%   |
| Plextor                     | 1        | 1      | 0.51%   |
| Micron Technology           | 1        | 1      | 0.51%   |
| Maxtor                      | 1        | 1      | 0.51%   |
| Kingston Technology Company | 1        | 1      | 0.51%   |
| Intenso                     | 1        | 1      | 0.51%   |
| Flashwar                    | 1        | 1      | 0.51%   |
| BAITITON                    | 1        | 1      | 0.51%   |
| ASMT                        | 1        | 1      | 0.51%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 50       | 63     | 35.21%  |
| WDC                 | 49       | 70     | 34.51%  |
| Samsung Electronics | 13       | 16     | 9.15%   |
| Toshiba             | 11       | 11     | 7.75%   |
| Hitachi             | 7        | 8      | 4.93%   |
| HGST                | 7        | 7      | 4.93%   |
| Apple               | 2        | 2      | 1.41%   |
| SABRENT             | 1        | 1      | 0.7%    |
| Maxtor              | 1        | 1      | 0.7%    |
| ASMT                | 1        | 1      | 0.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 127      | 180    | 69.02%  |
| SSD  | 45       | 54     | 24.46%  |
| NVMe | 12       | 12     | 6.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 25%     |
| Samsung Electronics SSD 980 500GB | 1        | 1      | 25%     |
| Samsung Electronics SSD 980 1TB   | 1        | 1      | 25%     |
| Patriot Pyro SSD 120GB            | 1        | 2      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 50%     |
| Seagate             | 1        | 1      | 25%     |
| Patriot             | 1        | 2      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 3799     | 11160  | 79.89%  |
| Works    | 779      | 1940   | 16.38%  |
| Malfunc  | 172      | 246    | 3.62%   |
| Failed   | 4        | 5      | 0.08%   |
| Limited  | 1        | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2406     | 33.25%  |
| AMD                              | 2012     | 27.8%   |
| Samsung Electronics              | 828      | 11.44%  |
| SanDisk                          | 338      | 4.67%   |
| Phison Electronics               | 272      | 3.76%   |
| ASMedia Technology               | 259      | 3.58%   |
| Micron/Crucial Technology        | 175      | 2.42%   |
| Kingston Technology Company      | 149      | 2.06%   |
| Marvell Technology Group         | 114      | 1.58%   |
| Silicon Motion                   | 111      | 1.53%   |
| JMicron Technology               | 102      | 1.41%   |
| Nvidia                           | 70       | 0.97%   |
| ADATA Technology                 | 69       | 0.95%   |
| Realtek Semiconductor            | 60       | 0.83%   |
| SK hynix                         | 36       | 0.5%    |
| Toshiba America Info Systems     | 30       | 0.41%   |
| Micron Technology                | 27       | 0.37%   |
| Broadcom / LSI                   | 26       | 0.36%   |
| Seagate Technology               | 22       | 0.3%    |
| MAXIO Technology (Hangzhou)      | 19       | 0.26%   |
| LSI Logic / Symbios Logic        | 18       | 0.25%   |
| Shenzhen Longsys Electronics     | 13       | 0.18%   |
| VIA Technologies                 | 12       | 0.17%   |
| Lite-On Technology               | 9        | 0.12%   |
| INNOGRIT                         | 9        | 0.12%   |
| Solidigm                         | 8        | 0.11%   |
| Silicon Image                    | 7        | 0.1%    |
| KIOXIA                           | 7        | 0.1%    |
| Adaptec                          | 5        | 0.07%   |
| Solid State Storage Technology   | 3        | 0.04%   |
| Netac Technology                 | 3        | 0.04%   |
| HighPoint Technologies           | 3        | 0.04%   |
| Apple                            | 3        | 0.04%   |
| Union Memory (Shenzhen)          | 2        | 0.03%   |
| Silicon Integrated Systems [SiS] | 2        | 0.03%   |
| Hewlett-Packard                  | 2        | 0.03%   |
| Biwin Storage Technology         | 2        | 0.03%   |
| OCZ Technology Group             | 1        | 0.01%   |
| Integrated Technology Express    | 1        | 0.01%   |
| Hosin Global Electronics         | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1177     | 13.43%  |
| AMD 400 Series Chipset SATA Controller                                                  | 522      | 5.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 478      | 5.45%   |
| AMD 500 Series Chipset SATA Controller                                                  | 345      | 3.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 258      | 2.94%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 245      | 2.8%    |
| Intel SATA Controller [RAID mode]                                                       | 211      | 2.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 207      | 2.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 199      | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 183      | 2.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 171      | 1.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 164      | 1.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 133      | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 132      | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 127      | 1.45%   |
| Phison E12 NVMe Controller                                                              | 117      | 1.34%   |
| AMD 600 Series Chipset SATA Controller                                                  | 117      | 1.34%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 99       | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 98       | 1.12%   |
| AMD 300 Series Chipset SATA Controller                                                  | 95       | 1.08%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 89       | 1.02%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 89       | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 88       | 1%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 87       | 0.99%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 87       | 0.99%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 86       | 0.98%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 84       | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 84       | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 83       | 0.95%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 81       | 0.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 75       | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 72       | 0.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 62       | 0.71%   |
| Intel SSD 660P Series                                                                   | 58       | 0.66%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 56       | 0.64%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 56       | 0.64%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 55       | 0.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 55       | 0.63%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 53       | 0.6%    |
| Intel Raptor Lake SATA AHCI Controller                                                  | 52       | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3841     | 56.36%  |
| NVMe | 1923     | 28.22%  |
| IDE  | 653      | 9.58%   |
| RAID | 340      | 4.99%   |
| SAS  | 44       | 0.65%   |
| SCSI | 14       | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2378     | 53.35%  |
| AMD    | 2079     | 46.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 172      | 3.84%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 127      | 2.83%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 91       | 2.03%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 79       | 1.76%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 74       | 1.65%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 71       | 1.58%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 68       | 1.52%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 66       | 1.47%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 63       | 1.41%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 57       | 1.27%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 53       | 1.18%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 51       | 1.14%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 50       | 1.12%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 48       | 1.07%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 47       | 1.05%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 46       | 1.03%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 44       | 0.98%   |
| AMD FX-8350 Eight-Core Processor            | 42       | 0.94%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 41       | 0.91%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 40       | 0.89%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 40       | 0.89%   |
| AMD FX-6300 Six-Core Processor              | 39       | 0.87%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 38       | 0.85%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 37       | 0.83%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 37       | 0.83%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 36       | 0.8%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 34       | 0.76%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 33       | 0.74%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 31       | 0.69%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 29       | 0.65%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 29       | 0.65%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 28       | 0.62%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 28       | 0.62%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 27       | 0.6%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 27       | 0.6%    |
| AMD Ryzen 7 3800X 8-Core Processor          | 27       | 0.6%    |
| AMD Ryzen 9 3950X 16-Core Processor         | 26       | 0.58%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 25       | 0.56%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 25       | 0.56%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 24       | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 727      | 16.24%  |
| AMD Ryzen 5             | 704      | 15.72%  |
| Intel Core i7           | 662      | 14.79%  |
| AMD Ryzen 7             | 525      | 11.73%  |
| AMD Ryzen 9             | 286      | 6.39%   |
| Intel Xeon              | 225      | 5.03%   |
| Intel Core i3           | 208      | 4.65%   |
| Other                   | 173      | 3.86%   |
| AMD FX                  | 144      | 3.22%   |
| Intel Core i9           | 78       | 1.74%   |
| AMD Ryzen 3             | 76       | 1.7%    |
| Intel Core 2 Duo        | 61       | 1.36%   |
| AMD Ryzen Threadripper  | 57       | 1.27%   |
| Intel Pentium           | 56       | 1.25%   |
| Intel Core 2 Quad       | 52       | 1.16%   |
| Intel Celeron           | 49       | 1.09%   |
| AMD Phenom II X4        | 40       | 0.89%   |
| Intel Pentium Dual-Core | 34       | 0.76%   |
| AMD A10                 | 32       | 0.71%   |
| AMD A8                  | 29       | 0.65%   |
| AMD Athlon II X2        | 27       | 0.6%    |
| AMD Athlon II X4        | 20       | 0.45%   |
| AMD Athlon              | 20       | 0.45%   |
| Intel Core 2            | 17       | 0.38%   |
| AMD Phenom II X6        | 15       | 0.34%   |
| AMD A6                  | 15       | 0.34%   |
| AMD Ryzen 5 PRO         | 13       | 0.29%   |
| AMD A4                  | 13       | 0.29%   |
| AMD Athlon 64 X2        | 12       | 0.27%   |
| Intel Atom              | 11       | 0.25%   |
| Intel Pentium Gold      | 10       | 0.22%   |
| AMD Phenom              | 10       | 0.22%   |
| Intel Pentium Dual      | 8        | 0.18%   |
| AMD Athlon X4           | 7        | 0.16%   |
| Intel Pentium D         | 6        | 0.13%   |
| AMD Sempron             | 5        | 0.11%   |
| AMD Ryzen 7 PRO         | 5        | 0.11%   |
| Intel Genuine           | 4        | 0.09%   |
| AMD Ryzen 3 PRO         | 4        | 0.09%   |
| AMD Phenom II X3        | 4        | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1596     | 35.64%  |
| 6      | 957      | 21.37%  |
| 8      | 719      | 16.06%  |
| 2      | 557      | 12.44%  |
| 12     | 232      | 5.18%   |
| 16     | 163      | 3.64%   |
| 10     | 63       | 1.41%   |
| 3      | 60       | 1.34%   |
| 24     | 38       | 0.85%   |
| 1      | 38       | 0.85%   |
| 32     | 18       | 0.4%    |
| 14     | 17       | 0.38%   |
| 20     | 9        | 0.2%    |
| 64     | 5        | 0.11%   |
| 28     | 2        | 0.04%   |
| 18     | 2        | 0.04%   |
| 36     | 1        | 0.02%   |
| 9      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 4407     | 98.88%  |
| 2      | 50       | 1.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 3121     | 69.88%  |
| 1      | 1339     | 29.98%  |
| 8      | 3        | 0.07%   |
| 16     | 2        | 0.04%   |
| 12     | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4453     | 99.91%  |
| Unknown        | 4        | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3482     | 76.49%  |
| 0x08701021 | 112      | 2.46%   |
| 0x0800820d | 79       | 1.74%   |
| 0x306c3    | 78       | 1.71%   |
| 0x08701013 | 74       | 1.63%   |
| 0x306a9    | 63       | 1.38%   |
| 0x206a7    | 50       | 1.1%    |
| 0x506e3    | 42       | 0.92%   |
| 0x906ea    | 38       | 0.83%   |
| 0x906e9    | 30       | 0.66%   |
| 0x0a201016 | 28       | 0.62%   |
| 0x08001138 | 28       | 0.62%   |
| 0x1067a    | 27       | 0.59%   |
| 0x08108109 | 26       | 0.57%   |
| 0x06000852 | 25       | 0.55%   |
| 0x0a601203 | 18       | 0.4%    |
| 0x0a201009 | 17       | 0.37%   |
| 0x906ec    | 15       | 0.33%   |
| 0x906ed    | 14       | 0.31%   |
| 0x08301039 | 14       | 0.31%   |
| 0x0a20120a | 13       | 0.29%   |
| 0x08001137 | 13       | 0.29%   |
| 0xa0655    | 11       | 0.24%   |
| 0x06001119 | 11       | 0.24%   |
| 0x010000c8 | 11       | 0.24%   |
| 0x306f2    | 9        | 0.2%    |
| 0x106a5    | 9        | 0.2%    |
| 0x0a50000d | 9        | 0.2%    |
| 0x06003106 | 9        | 0.2%    |
| 0xa0653    | 8        | 0.18%   |
| 0x206c2    | 8        | 0.18%   |
| 0x0a50000c | 8        | 0.18%   |
| 0xa0671    | 7        | 0.15%   |
| 0x906eb    | 7        | 0.15%   |
| 0x90672    | 7        | 0.15%   |
| 0x08101016 | 7        | 0.15%   |
| 0x6fd      | 6        | 0.13%   |
| 0x206d7    | 6        | 0.13%   |
| 0x20655    | 6        | 0.13%   |
| 0x6fb      | 5        | 0.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 585      | 13.08%  |
| Zen 3            | 449      | 10.04%  |
| Haswell          | 448      | 10.01%  |
| KabyLake         | 397      | 8.87%   |
| Zen+             | 320      | 7.15%   |
| IvyBridge        | 301      | 6.73%   |
| Unknown          | 281      | 6.28%   |
| SandyBridge      | 262      | 5.86%   |
| Skylake          | 232      | 5.19%   |
| Zen              | 201      | 4.49%   |
| Piledriver       | 170      | 3.8%    |
| CometLake        | 134      | 3%      |
| Penryn           | 128      | 2.86%   |
| K10              | 127      | 2.84%   |
| Nehalem          | 94       | 2.1%    |
| Westmere         | 66       | 1.48%   |
| Core             | 60       | 1.34%   |
| Alderlake Hybrid | 34       | 0.76%   |
| Steamroller      | 28       | 0.63%   |
| Silvermont       | 23       | 0.51%   |
| K8 Hammer        | 20       | 0.45%   |
| Excavator        | 17       | 0.38%   |
| Broadwell        | 16       | 0.36%   |
| Bulldozer        | 15       | 0.34%   |
| K10 Llano        | 14       | 0.31%   |
| Goldmont plus    | 12       | 0.27%   |
| NetBurst         | 9        | 0.2%    |
| Icelake          | 8        | 0.18%   |
| Jaguar           | 7        | 0.16%   |
| Bobcat           | 5        | 0.11%   |
| Goldmont         | 4        | 0.09%   |
| Bonnell          | 3        | 0.07%   |
| Gracemont        | 2        | 0.04%   |
| Tremont          | 1        | 0.02%   |
| Puma             | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 2378     | 48.64%  |
| AMD                              | 1637     | 33.48%  |
| Intel                            | 863      | 17.65%  |
| Matrox Electronics Systems       | 7        | 0.14%   |
| Silicon Integrated Systems [SiS] | 2        | 0.04%   |
| ASPEED Technology                | 1        | 0.02%   |
| 3Dfx Interactive                 | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 308      | 6.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 163      | 3.2%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 133      | 2.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 128      | 2.51%   |
| AMD Raphael                                                                 | 101      | 1.98%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 93       | 1.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 91       | 1.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 88       | 1.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 83       | 1.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 82       | 1.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 77       | 1.51%   |
| Nvidia GK208B [GeForce GT 710]                                              | 77       | 1.51%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 76       | 1.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 74       | 1.45%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 71       | 1.39%   |
| Intel HD Graphics 530                                                       | 68       | 1.34%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 68       | 1.34%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 65       | 1.28%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 62       | 1.22%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 61       | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 59       | 1.16%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 55       | 1.08%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 52       | 1.02%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 50       | 0.98%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 48       | 0.94%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 46       | 0.9%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 45       | 0.88%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 45       | 0.88%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 44       | 0.86%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 43       | 0.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 42       | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 40       | 0.79%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 39       | 0.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 39       | 0.77%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 38       | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 37       | 0.73%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 37       | 0.73%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 36       | 0.71%   |
| Nvidia GT218 [GeForce 210]                                                  | 36       | 0.71%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 36       | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| 1 x Nvidia                | 2142     | 47.16%  |
| 1 x AMD                   | 1397     | 30.76%  |
| 1 x Intel                 | 614      | 13.52%  |
| 2 x AMD                   | 105      | 2.31%   |
| AMD + Nvidia              | 97       | 2.14%   |
| Intel + Nvidia            | 83       | 1.83%   |
| 2 x Nvidia                | 46       | 1.01%   |
| Intel + AMD               | 35       | 0.77%   |
| 1 x Matrox                | 4        | 0.09%   |
| Other                     | 2        | 0.04%   |
| 4 x Nvidia                | 2        | 0.04%   |
| 1 x SiS                   | 2        | 0.04%   |
| Nvidia + Matrox           | 2        | 0.04%   |
| Intel + 2 x Nvidia        | 2        | 0.04%   |
| 5 x Nvidia                | 1        | 0.02%   |
| 3 x Nvidia                | 1        | 0.02%   |
| 2 x AMD + 2 x Nvidia      | 1        | 0.02%   |
| 2 x AMD + 1 x Nvidia      | 1        | 0.02%   |
| Nvidia + ASPEED           | 1        | 0.02%   |
| Nvidia + 3Dfx Interactive | 1        | 0.02%   |
| Intel + AMD + 2 x Nvidia  | 1        | 0.02%   |
| AMD + 2 x Nvidia          | 1        | 0.02%   |
| AMD + Matrox              | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2338     | 51.57%  |
| Proprietary | 1950     | 43.01%  |
| Unknown     | 246      | 5.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2655     | 57.94%  |
| 7.01-8.0   | 541      | 11.81%  |
| 1.01-2.0   | 330      | 7.2%    |
| 3.01-4.0   | 324      | 7.07%   |
| 5.01-6.0   | 267      | 5.83%   |
| 8.01-16.0  | 220      | 4.8%    |
| 0.51-1.0   | 94       | 2.05%   |
| 0.01-0.5   | 58       | 1.27%   |
| 2.01-3.0   | 53       | 1.16%   |
| 16.01-24.0 | 35       | 0.76%   |
| 4.01-5.0   | 3        | 0.07%   |
| 32.01-64.0 | 1        | 0.02%   |
| 24.01-32.0 | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 817      | 16.18%  |
| Goldstar             | 578      | 11.45%  |
| Dell                 | 540      | 10.69%  |
| Acer                 | 439      | 8.69%   |
| Hewlett-Packard      | 311      | 6.16%   |
| AOC                  | 287      | 5.68%   |
| Ancor Communications | 237      | 4.69%   |
| BenQ                 | 232      | 4.59%   |
| ASUSTek Computer     | 191      | 3.78%   |
| Philips              | 153      | 3.03%   |
| ViewSonic            | 84       | 1.66%   |
| MSI                  | 80       | 1.58%   |
| Iiyama               | 79       | 1.56%   |
| Lenovo               | 78       | 1.54%   |
| Sony                 | 60       | 1.19%   |
| Sceptre Tech         | 53       | 1.05%   |
| Gigabyte Technology  | 42       | 0.83%   |
| Vizio                | 40       | 0.79%   |
| Unknown              | 29       | 0.57%   |
| Toshiba              | 25       | 0.5%    |
| Eizo                 | 24       | 0.48%   |
| Panasonic            | 23       | 0.46%   |
| NEC Computers        | 20       | 0.4%    |
| Insignia             | 20       | 0.4%    |
| Fujitsu Siemens      | 20       | 0.4%    |
| Hitachi              | 18       | 0.36%   |
| Vestel Elektronik    | 17       | 0.34%   |
| Valve                | 15       | 0.3%    |
| Mi                   | 15       | 0.3%    |
| MStar                | 14       | 0.28%   |
| LG Electronics       | 14       | 0.28%   |
| HKC                  | 13       | 0.26%   |
| ONN                  | 12       | 0.24%   |
| HannStar             | 12       | 0.24%   |
| Viotek               | 11       | 0.22%   |
| Sharp                | 11       | 0.22%   |
| Pixio                | 11       | 0.22%   |
| Unknown (XXX)        | 10       | 0.2%    |
| HUAWEI               | 10       | 0.2%    |
| Medion               | 9        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 45       | 0.84%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 39       | 0.73%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 29       | 0.54%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 26       | 0.48%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 23       | 0.43%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 23       | 0.43%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 19       | 0.35%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 18       | 0.33%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 18       | 0.33%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 17       | 0.32%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 17       | 0.32%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 17       | 0.32%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 16       | 0.3%    |
| Valve Index HMD VLV91A8                                               | 15       | 0.28%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 15       | 0.28%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 15       | 0.28%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 14       | 0.26%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 14       | 0.26%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 14       | 0.26%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 14       | 0.26%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 13       | 0.24%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 13       | 0.24%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 12       | 0.22%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 12       | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 12       | 0.22%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 11       | 0.2%    |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 11       | 0.2%    |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch               | 11       | 0.2%    |
| AOC 2460G4 AOC246A 1920x1080 531x299mm 24.0-inch                      | 11       | 0.2%    |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 11       | 0.2%    |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch      | 11       | 0.2%    |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 526x296mm 23.8-inch        | 10       | 0.19%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch         | 10       | 0.19%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 10       | 0.19%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 10       | 0.19%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 10       | 0.19%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch               | 10       | 0.19%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 10       | 0.19%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch          | 10       | 0.19%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 10       | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2178     | 45.36%  |
| 3840x2160 (4K)     | 670      | 13.95%  |
| 2560x1440 (QHD)    | 542      | 11.29%  |
| 3440x1440          | 205      | 4.27%   |
| 1680x1050 (WSXGA+) | 178      | 3.71%   |
| 1280x1024 (SXGA)   | 155      | 3.23%   |
| 1366x768 (WXGA)    | 146      | 3.04%   |
| 2560x1080          | 137      | 2.85%   |
| 1920x1200 (WUXGA)  | 99       | 2.06%   |
| 1440x900 (WXGA+)   | 99       | 2.06%   |
| 1600x900 (HD+)     | 97       | 2.02%   |
| 1360x768           | 60       | 1.25%   |
| 3840x1080          | 46       | 0.96%   |
| Unknown            | 36       | 0.75%   |
| 1920x540           | 35       | 0.73%   |
| 3840x1600          | 17       | 0.35%   |
| 1024x768 (XGA)     | 13       | 0.27%   |
| 2560x1600          | 11       | 0.23%   |
| 1600x1200          | 11       | 0.23%   |
| 1280x720 (HD)      | 11       | 0.23%   |
| 2288x1287          | 7        | 0.15%   |
| 3840x1200          | 6        | 0.12%   |
| 2048x1152          | 5        | 0.1%    |
| 4480x1440          | 4        | 0.08%   |
| 5120x1440          | 2        | 0.04%   |
| 2520x1680          | 2        | 0.04%   |
| 9840x3840          | 1        | 0.02%   |
| 8320x2160          | 1        | 0.02%   |
| 8160x4627          | 1        | 0.02%   |
| 800x480            | 1        | 0.02%   |
| 7680x2160          | 1        | 0.02%   |
| 6400x1440          | 1        | 0.02%   |
| 5280x1080          | 1        | 0.02%   |
| 5200x2160          | 1        | 0.02%   |
| 4096x2160          | 1        | 0.02%   |
| 4080x2030          | 1        | 0.02%   |
| 4080x2026          | 1        | 0.02%   |
| 3840x2560          | 1        | 0.02%   |
| 3360x1080          | 1        | 0.02%   |
| 3280x2048          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 902      | 17.92%  |
| 24      | 800      | 15.9%   |
| 23      | 570      | 11.33%  |
| 21      | 410      | 8.15%   |
| 31      | 389      | 7.73%   |
| 34      | 290      | 5.76%   |
| 19      | 183      | 3.64%   |
| Unknown | 161      | 3.2%    |
| 22      | 128      | 2.54%   |
| 18      | 126      | 2.5%    |
| 84      | 113      | 2.25%   |
| 20      | 107      | 2.13%   |
| 17      | 82       | 1.63%   |
| 32      | 78       | 1.55%   |
| 72      | 70       | 1.39%   |
| 54      | 57       | 1.13%   |
| 15      | 57       | 1.13%   |
| 40      | 53       | 1.05%   |
| 48      | 41       | 0.81%   |
| 26      | 33       | 0.66%   |
| 25      | 33       | 0.66%   |
| 28      | 32       | 0.64%   |
| 52      | 25       | 0.5%    |
| 35      | 24       | 0.48%   |
| 49      | 21       | 0.42%   |
| 65      | 20       | 0.4%    |
| 37      | 20       | 0.4%    |
| 29      | 19       | 0.38%   |
| 46      | 17       | 0.34%   |
| 36      | 16       | 0.32%   |
| 33      | 14       | 0.28%   |
| 43      | 13       | 0.26%   |
| 42      | 11       | 0.22%   |
| 38      | 10       | 0.2%    |
| 16      | 10       | 0.2%    |
| 74      | 8        | 0.16%   |
| 44      | 8        | 0.16%   |
| 12      | 8        | 0.16%   |
| 142     | 6        | 0.12%   |
| 55      | 6        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 2025     | 42.08%  |
| 401-500        | 848      | 17.62%  |
| 601-700        | 554      | 11.51%  |
| 701-800        | 386      | 8.02%   |
| 1001-1500      | 223      | 4.63%   |
| 1501-2000      | 201      | 4.18%   |
| Unknown        | 161      | 3.35%   |
| 301-350        | 129      | 2.68%   |
| 801-900        | 121      | 2.51%   |
| 351-400        | 112      | 2.33%   |
| 901-1000       | 24       | 0.5%    |
| 201-300        | 22       | 0.46%   |
| More than 2000 | 6        | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 3237     | 73.15%  |
| 16/10   | 456      | 10.31%  |
| 21/9    | 351      | 7.93%   |
| 5/4     | 151      | 3.41%   |
| Unknown | 92       | 2.08%   |
| 32/9    | 55       | 1.24%   |
| 4/3     | 42       | 0.95%   |
| 3/2     | 14       | 0.32%   |
| 6/5     | 7        | 0.16%   |
| 1.00    | 7        | 0.16%   |
| 3.20    | 6        | 0.14%   |
| 1.96    | 5        | 0.11%   |
| 6.00    | 1        | 0.02%   |
| 2.12    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1480     | 30.25%  |
| 301-350        | 925      | 18.9%   |
| 351-500        | 800      | 16.35%  |
| 151-200        | 410      | 8.38%   |
| More than 1000 | 344      | 7.03%   |
| 251-300        | 294      | 6.01%   |
| 501-1000       | 210      | 4.29%   |
| 141-150        | 169      | 3.45%   |
| Unknown        | 161      | 3.29%   |
| 101-110        | 55       | 1.12%   |
| 71-80          | 13       | 0.27%   |
| 111-120        | 10       | 0.2%    |
| 131-140        | 9        | 0.18%   |
| 121-130        | 5        | 0.1%    |
| 51-60          | 4        | 0.08%   |
| 91-100         | 3        | 0.06%   |
| 81-90          | 1        | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2818     | 61.65%  |
| 101-120       | 954      | 20.87%  |
| 121-160       | 277      | 6.06%   |
| 1-50          | 249      | 5.45%   |
| Unknown       | 161      | 3.52%   |
| 161-240       | 111      | 2.43%   |
| More than 240 | 1        | 0.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3154     | 69.05%  |
| 2     | 983      | 21.52%  |
| 0     | 275      | 6.02%   |
| 3     | 137      | 3%      |
| 4     | 16       | 0.35%   |
| 5     | 2        | 0.04%   |
| 6     | 1        | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 2671     | 40.23%  |
| Intel                                 | 2197     | 33.09%  |
| Qualcomm Atheros                      | 365      | 5.5%    |
| Broadcom                              | 208      | 3.13%   |
| MediaTek                              | 129      | 1.94%   |
| TP-Link                               | 127      | 1.91%   |
| Ralink Technology                     | 112      | 1.69%   |
| Microsoft                             | 82       | 1.23%   |
| Samsung Electronics                   | 59       | 0.89%   |
| Nvidia                                | 57       | 0.86%   |
| Aquantia                              | 54       | 0.81%   |
| Ralink                                | 53       | 0.8%    |
| NetGear                               | 47       | 0.71%   |
| Qualcomm Atheros Communications       | 41       | 0.62%   |
| InterBiometrics                       | 41       | 0.62%   |
| Marvell Technology Group              | 27       | 0.41%   |
| ASIX Electronics                      | 26       | 0.39%   |
| Xiaomi                                | 24       | 0.36%   |
| Google                                | 24       | 0.36%   |
| D-Link                                | 24       | 0.36%   |
| Linksys                               | 23       | 0.35%   |
| Broadcom Limited                      | 20       | 0.3%    |
| ASUSTek Computer                      | 20       | 0.3%    |
| Huawei Technologies                   | 19       | 0.29%   |
| D-Link System                         | 12       | 0.18%   |
| Edimax Technology                     | 11       | 0.17%   |
| DisplayLink                           | 10       | 0.15%   |
| Belkin Components                     | 10       | 0.15%   |
| OPPO Electronics                      | 9        | 0.14%   |
| Motorola PCS                          | 9        | 0.14%   |
| OnePlus Technology (Shenzhen)         | 8        | 0.12%   |
| Mellanox Technologies                 | 6        | 0.09%   |
| AVM                                   | 6        | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 6        | 0.09%   |
| VIA Technologies                      | 5        | 0.08%   |
| Sitecom Europe                        | 5        | 0.08%   |
| Qualcomm                              | 5        | 0.08%   |
| Gemtek                                | 5        | 0.08%   |
| Qualcomm Technologies                 | 4        | 0.06%   |
| Mercucys                              | 4        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1982     | 25.56%  |
| Intel I211 Gigabit Network Connection                                  | 474      | 6.11%   |
| Intel Wi-Fi 6 AX200                                                    | 427      | 5.51%   |
| Realtek RTL8125 2.5GbE Controller                                      | 401      | 5.17%   |
| Intel Ethernet Controller I225-V                                       | 231      | 2.98%   |
| Intel Ethernet Connection (2) I219-V                                   | 186      | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 151      | 1.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 119      | 1.53%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 114      | 1.47%   |
| Intel Ethernet Connection (7) I219-V                                   | 110      | 1.42%   |
| Intel Ethernet Connection I217-LM                                      | 96       | 1.24%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 87       | 1.12%   |
| Realtek 802.11ac NIC                                                   | 74       | 0.95%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 71       | 0.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 67       | 0.86%   |
| Intel 82579V Gigabit Network Connection                                | 67       | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 60       | 0.77%   |
| Intel Ethernet Connection (2) I218-V                                   | 57       | 0.74%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 54       | 0.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 53       | 0.68%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 53       | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 52       | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 51       | 0.66%   |
| Ralink MT7601U Wireless Adapter                                        | 50       | 0.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 49       | 0.63%   |
| Intel Ethernet Connection I217-V                                       | 47       | 0.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 44       | 0.57%   |
| Nvidia MCP61 Ethernet                                                  | 43       | 0.55%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 43       | 0.55%   |
| InterBiometrics Io                                                     | 40       | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 38       | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 38       | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                                  | 38       | 0.49%   |
| Intel 82574L Gigabit Network Connection                                | 38       | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                        | 34       | 0.44%   |
| Intel Wireless 7265                                                    | 34       | 0.44%   |
| Intel Wireless 7260                                                    | 33       | 0.43%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 33       | 0.43%   |
| Intel Wireless 8265 / 8275                                             | 32       | 0.41%   |
| Intel I210 Gigabit Network Connection                                  | 31       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 1073     | 41.3%   |
| Realtek Semiconductor                 | 499      | 19.21%  |
| Qualcomm Atheros                      | 188      | 7.24%   |
| Broadcom                              | 128      | 4.93%   |
| TP-Link                               | 121      | 4.66%   |
| Ralink Technology                     | 112      | 4.31%   |
| MediaTek                              | 108      | 4.16%   |
| Microsoft                             | 82       | 3.16%   |
| Ralink                                | 53       | 2.04%   |
| NetGear                               | 47       | 1.81%   |
| Qualcomm Atheros Communications       | 41       | 1.58%   |
| Linksys                               | 22       | 0.85%   |
| D-Link                                | 22       | 0.85%   |
| ASUSTek Computer                      | 20       | 0.77%   |
| Edimax Technology                     | 11       | 0.42%   |
| Broadcom Limited                      | 10       | 0.38%   |
| Belkin Components                     | 10       | 0.38%   |
| D-Link System                         | 7        | 0.27%   |
| AVM                                   | 6        | 0.23%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 6        | 0.23%   |
| Sitecom Europe                        | 5        | 0.19%   |
| Gemtek                                | 5        | 0.19%   |
| Qualcomm Technologies                 | 4        | 0.15%   |
| Mercucys                              | 4        | 0.15%   |
| IMC Networks                          | 3        | 0.12%   |
| Accton Technology                     | 2        | 0.08%   |
| ZyDAS                                 | 1        | 0.04%   |
| Wilocity                              | 1        | 0.04%   |
| Wacom                                 | 1        | 0.04%   |
| TRENDnet                              | 1        | 0.04%   |
| Texas Instruments                     | 1        | 0.04%   |
| Samsung Electronics                   | 1        | 0.04%   |
| Ovislink                              | 1        | 0.04%   |
| Micro Star International              | 1        | 0.04%   |
| BUFFALO                               | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 427      | 16.25%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 119      | 4.53%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 114      | 4.34%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 87       | 3.31%   |
| Realtek 802.11ac NIC                                           | 74       | 2.82%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 71       | 2.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 67       | 2.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 60       | 2.28%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 53       | 2.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 51       | 1.94%   |
| Ralink MT7601U Wireless Adapter                                | 50       | 1.9%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 44       | 1.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 43       | 1.64%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 40       | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 38       | 1.45%   |
| Qualcomm Atheros AR9271 802.11n                                | 34       | 1.29%   |
| Intel Wireless 7265                                            | 34       | 1.29%   |
| Intel Wireless 7260                                            | 33       | 1.26%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 33       | 1.26%   |
| Intel Wireless 8265 / 8275                                     | 32       | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 30       | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 30       | 1.14%   |
| Microsoft Xbox 360 Wireless Adapter                            | 30       | 1.14%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 27       | 1.03%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 26       | 0.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 26       | 0.99%   |
| Intel Wireless 8260                                            | 26       | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 26       | 0.99%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 23       | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 22       | 0.84%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 21       | 0.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 20       | 0.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 19       | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 19       | 0.72%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter   | 19       | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 18       | 0.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 17       | 0.65%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 17       | 0.65%   |
| NetGear A6210                                                  | 16       | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 16       | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 2476     | 50.95%  |
| Intel                            | 1720     | 35.39%  |
| Qualcomm Atheros                 | 192      | 3.95%   |
| Broadcom                         | 90       | 1.85%   |
| Nvidia                           | 57       | 1.17%   |
| Aquantia                         | 54       | 1.11%   |
| Samsung Electronics              | 38       | 0.78%   |
| Marvell Technology Group         | 27       | 0.56%   |
| ASIX Electronics                 | 26       | 0.53%   |
| Xiaomi                           | 24       | 0.49%   |
| Google                           | 22       | 0.45%   |
| MediaTek                         | 21       | 0.43%   |
| Huawei Technologies              | 18       | 0.37%   |
| DisplayLink                      | 10       | 0.21%   |
| Broadcom Limited                 | 10       | 0.21%   |
| OPPO Electronics                 | 9        | 0.19%   |
| Motorola PCS                     | 9        | 0.19%   |
| TP-Link                          | 6        | 0.12%   |
| VIA Technologies                 | 5        | 0.1%    |
| Qualcomm                         | 5        | 0.1%    |
| OnePlus Technology (Shenzhen)    | 5        | 0.1%    |
| D-Link System                    | 5        | 0.1%    |
| Mellanox Technologies            | 4        | 0.08%   |
| ZTE WCDMA Technologies MSM       | 2        | 0.04%   |
| Lenovo                           | 2        | 0.04%   |
| ICS Advent                       | 2        | 0.04%   |
| D-Link                           | 2        | 0.04%   |
| American Megatrends              | 2        | 0.04%   |
| 3Com                             | 2        | 0.04%   |
| Tehuti Networks                  | 1        | 0.02%   |
| T & A Mobile Phones              | 1        | 0.02%   |
| Solarflare Communications        | 1        | 0.02%   |
| Silicon Integrated Systems [SiS] | 1        | 0.02%   |
| QLogic                           | 1        | 0.02%   |
| Netchip Technology               | 1        | 0.02%   |
| Motorola BCS                     | 1        | 0.02%   |
| Linksys                          | 1        | 0.02%   |
| LG Electronics                   | 1        | 0.02%   |
| JMicron Technology               | 1        | 0.02%   |
| HMD Global                       | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1982     | 39.51%  |
| Intel I211 Gigabit Network Connection                                          | 474      | 9.45%   |
| Realtek RTL8125 2.5GbE Controller                                              | 401      | 7.99%   |
| Intel Ethernet Controller I225-V                                               | 231      | 4.6%    |
| Intel Ethernet Connection (2) I219-V                                           | 186      | 3.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 151      | 3.01%   |
| Intel Ethernet Connection (7) I219-V                                           | 110      | 2.19%   |
| Intel Ethernet Connection I217-LM                                              | 96       | 1.91%   |
| Intel 82579V Gigabit Network Connection                                        | 67       | 1.34%   |
| Intel Ethernet Connection (2) I218-V                                           | 57       | 1.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 53       | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 52       | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 49       | 0.98%   |
| Intel Ethernet Connection I217-V                                               | 47       | 0.94%   |
| Nvidia MCP61 Ethernet                                                          | 43       | 0.86%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 38       | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                                          | 38       | 0.76%   |
| Intel 82574L Gigabit Network Connection                                        | 38       | 0.76%   |
| Intel I210 Gigabit Network Connection                                          | 31       | 0.62%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 31       | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 30       | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 26       | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 26       | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 24       | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 21       | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 20       | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 19       | 0.38%   |
| Intel Ethernet Controller I226-V                                               | 19       | 0.38%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 19       | 0.38%   |
| Intel Ethernet Connection (11) I219-V                                          | 17       | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 16       | 0.32%   |
| Intel Ethernet Connection (2) I218-LM                                          | 16       | 0.32%   |
| Huawei FOA-LX9                                                                 | 16       | 0.32%   |
| Intel Ethernet Connection (14) I219-V                                          | 15       | 0.3%    |
| Intel 82578DM Gigabit Network Connection                                       | 15       | 0.3%    |
| Google Nexus/Pixel Device (tether)                                             | 15       | 0.3%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 14       | 0.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 13       | 0.26%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 13       | 0.26%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 12       | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4408     | 63.53%  |
| WiFi     | 2424     | 34.93%  |
| Modem    | 94       | 1.35%   |
| Unknown  | 13       | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3348     | 70.77%  |
| WiFi     | 1378     | 29.13%  |
| Modem    | 3        | 0.06%   |
| Unknown  | 2        | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2496     | 55.63%  |
| 2     | 1680     | 37.44%  |
| 3     | 226      | 5.04%   |
| 0     | 37       | 0.82%   |
| 4     | 36       | 0.8%    |
| 5     | 8        | 0.18%   |
| 10    | 2        | 0.04%   |
| 6     | 2        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3403     | 74.86%  |
| Yes  | 1143     | 25.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 992      | 50.3%   |
| Cambridge Silicon Radio         | 346      | 17.55%  |
| Realtek Semiconductor           | 129      | 6.54%   |
| ASUSTek Computer                | 109      | 5.53%   |
| MediaTek                        | 74       | 3.75%   |
| Broadcom                        | 74       | 3.75%   |
| Qualcomm Atheros Communications | 56       | 2.84%   |
| Apple                           | 36       | 1.83%   |
| IMC Networks                    | 34       | 1.72%   |
| Foxconn / Hon Hai               | 31       | 1.57%   |
| TP-Link                         | 29       | 1.47%   |
| Dynex                           | 10       | 0.51%   |
| Realtek                         | 7        | 0.35%   |
| Actions                         | 7        | 0.35%   |
| Lite-On Technology              | 4        | 0.2%    |
| Integrated System Solution      | 4        | 0.2%    |
| HTC (High Tech Computer)        | 4        | 0.2%    |
| Edimax Technology               | 4        | 0.2%    |
| Ralink                          | 3        | 0.15%   |
| Logitech                        | 3        | 0.15%   |
| Dell                            | 3        | 0.15%   |
| SINO WEALTH                     | 2        | 0.1%    |
| Hewlett-Packard                 | 2        | 0.1%    |
| Creative Technology             | 2        | 0.1%    |
| Conwise Technology              | 2        | 0.1%    |
| Belkin Components               | 2        | 0.1%    |
| Primax Electronics              | 1        | 0.05%   |
| Micro Star International        | 1        | 0.05%   |
| Unknown                         | 1        | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 394      | 19.94%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 346      | 17.51%  |
| Intel Bluetooth wireless interface                                   | 126      | 6.38%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 115      | 5.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 106      | 5.36%   |
| Realtek Bluetooth Radio                                              | 92       | 4.66%   |
| Intel AX210 Bluetooth                                                | 81       | 4.1%    |
| MediaTek Wireless_Device                                             | 74       | 3.74%   |
| Intel AX201 Bluetooth                                                | 71       | 3.59%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 56       | 2.83%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 54       | 2.73%   |
| Intel AX211 Bluetooth                                                | 41       | 2.07%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 34       | 1.72%   |
| TP-Link TP-Link Bluetooth USB Adapter                                | 29       | 1.47%   |
| Qualcomm Atheros  Bluetooth Device                                   | 28       | 1.42%   |
| ASUS Bluetooth Radio                                                 | 27       | 1.37%   |
| IMC Networks Bluetooth Radio                                         | 21       | 1.06%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 20       | 1.01%   |
| ASUS ASUS USB-BT500                                                  | 20       | 1.01%   |
| Apple Bluetooth Host Controller                                      | 17       | 0.86%   |
| Foxconn / Hon Hai Wireless_Device                                    | 14       | 0.71%   |
| IMC Networks Wireless_Device                                         | 11       | 0.56%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 10       | 0.51%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 10       | 0.51%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 10       | 0.51%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 9        | 0.46%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 8        | 0.4%    |
| Realtek Bluetooth Radio                                              | 7        | 0.35%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 7        | 0.35%   |
| ASUS BCM20702A0                                                      | 7        | 0.35%   |
| Actions general adapter                                              | 7        | 0.35%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 6        | 0.3%    |
| Realtek RTL8821A Bluetooth                                           | 5        | 0.25%   |
| Realtek Bluetooth 5.3 Radio                                          | 5        | 0.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 5        | 0.25%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 5        | 0.25%   |
| Apple Bluetooth USB Host Controller                                  | 5        | 0.25%   |
| Apple Bluetooth HCI                                                  | 5        | 0.25%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4        | 0.2%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 2473     | 28.17%  |
| Nvidia                               | 2307     | 26.28%  |
| Intel                                | 2283     | 26%     |
| C-Media Electronics                  | 242      | 2.76%   |
| Logitech                             | 127      | 1.45%   |
| Creative Labs                        | 91       | 1.04%   |
| Razer USA                            | 78       | 0.89%   |
| Kingston Technology                  | 78       | 0.89%   |
| ASUSTek Computer                     | 67       | 0.76%   |
| SteelSeries ApS                      | 65       | 0.74%   |
| JMTek                                | 63       | 0.72%   |
| Corsair                              | 61       | 0.69%   |
| Focusrite-Novation                   | 54       | 0.62%   |
| Texas Instruments                    | 53       | 0.6%    |
| Micro Star International             | 46       | 0.52%   |
| Creative Technology                  | 42       | 0.48%   |
| Blue Microphones                     | 36       | 0.41%   |
| Generalplus Technology               | 30       | 0.34%   |
| Giga-Byte Technology                 | 21       | 0.24%   |
| Sony                                 | 20       | 0.23%   |
| GN Netcom                            | 20       | 0.23%   |
| Astro Gaming                         | 20       | 0.23%   |
| Plantronics                          | 19       | 0.22%   |
| Valve Software                       | 18       | 0.21%   |
| Realtek Semiconductor                | 16       | 0.18%   |
| DSEA A/S                             | 15       | 0.17%   |
| Thesycon Systemsoftware & Consulting | 14       | 0.16%   |
| Tenx Technology                      | 14       | 0.16%   |
| Hewlett-Packard                      | 13       | 0.15%   |
| Turtle Beach                         | 12       | 0.14%   |
| SAVITECH                             | 12       | 0.14%   |
| Samson Technologies                  | 12       | 0.14%   |
| M-Audio                              | 12       | 0.14%   |
| BEHRINGER International              | 12       | 0.14%   |
| Yamaha                               | 11       | 0.13%   |
| FiiO Electronics Technology          | 11       | 0.13%   |
| KTMicro                              | 10       | 0.11%   |
| Audio-Technica                       | 10       | 0.11%   |
| RODE Microphones                     | 9        | 0.1%    |
| Medeli Electronics                   | 8        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 880      | 8.55%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 378      | 3.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 354      | 3.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 322      | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 288      | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 268      | 2.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 226      | 2.2%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 224      | 2.18%   |
| Intel 200 Series PCH HD Audio                                              | 223      | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 215      | 2.09%   |
| Nvidia GP104 High Definition Audio Controller                              | 214      | 2.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 212      | 2.06%   |
| Nvidia TU116 High Definition Audio Controller                              | 180      | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 172      | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 170      | 1.65%   |
| AMD Navi 10 HDMI Audio                                                     | 162      | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 161      | 1.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 151      | 1.47%   |
| Nvidia GP106 High Definition Audio Controller                              | 142      | 1.38%   |
| Nvidia TU104 HD Audio Controller                                           | 135      | 1.31%   |
| Nvidia TU106 High Definition Audio Controller                              | 134      | 1.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 127      | 1.23%   |
| Nvidia GA102 High Definition Audio Controller                              | 115      | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 113      | 1.1%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 110      | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 106      | 1.03%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 106      | 1.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 106      | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 100      | 0.97%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 96       | 0.93%   |
| Nvidia GM204 High Definition Audio Controller                              | 92       | 0.89%   |
| AMD FCH Azalia Controller                                                  | 92       | 0.89%   |
| Intel Alder Lake-S HD Audio Controller                                     | 83       | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 77       | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                              | 73       | 0.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 72       | 0.7%    |
| AMD Navi 31 HDMI/DP Audio                                                  | 67       | 0.65%   |
| Nvidia GM206 High Definition Audio Controller                              | 65       | 0.63%   |
| Nvidia GP102 HDMI Audio Controller                                         | 63       | 0.61%   |
| Nvidia GK104 HDMI Audio Controller                                         | 62       | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 225      | 24.06%  |
| Kingston                     | 155      | 16.58%  |
| G.Skill                      | 144      | 15.4%   |
| Crucial                      | 89       | 9.52%   |
| Unknown                      | 62       | 6.63%   |
| Samsung Electronics          | 51       | 5.45%   |
| SK hynix                     | 46       | 4.92%   |
| Team                         | 41       | 4.39%   |
| Micron Technology            | 28       | 2.99%   |
| A-DATA Technology            | 23       | 2.46%   |
| Patriot                      | 12       | 1.28%   |
| Unknown                      | 12       | 1.28%   |
| Ramaxel Technology           | 3        | 0.32%   |
| Avant                        | 3        | 0.32%   |
| Apacer                       | 3        | 0.32%   |
| Unknown (ABCD)               | 2        | 0.21%   |
| Unifosa                      | 2        | 0.21%   |
| Patriot Memory (PDP Systems) | 2        | 0.21%   |
| Patriot Memory               | 2        | 0.21%   |
| OLOY                         | 2        | 0.21%   |
| Neo Forza                    | 2        | 0.21%   |
| GOODRAM                      | 2        | 0.21%   |
| Goldkey                      | 2        | 0.21%   |
| ASint Technology             | 2        | 0.21%   |
| Unknown (0B92)               | 1        | 0.11%   |
| Transcend                    | 1        | 0.11%   |
| Toshiba                      | 1        | 0.11%   |
| Teikon                       | 1        | 0.11%   |
| Smart                        | 1        | 0.11%   |
| Silicon Power                | 1        | 0.11%   |
| PNY                          | 1        | 0.11%   |
| Pioneer                      | 1        | 0.11%   |
| Nanya Technology             | 1        | 0.11%   |
| Juhor                        | 1        | 0.11%   |
| J&A Information              | 1        | 0.11%   |
| HMD                          | 1        | 0.11%   |
| GLOWAY                       | 1        | 0.11%   |
| GeIL                         | 1        | 0.11%   |
| EVGA                         | 1        | 0.11%   |
| Elpida                       | 1        | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 23       | 2.3%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s  | 19       | 1.9%    |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s | 16       | 1.6%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s    | 12       | 1.2%    |
| Unknown                                                | 12       | 1.2%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s     | 11       | 1.1%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 11       | 1.1%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 9        | 0.9%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 8        | 0.8%    |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s | 8        | 0.8%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s     | 7        | 0.7%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 7        | 0.7%    |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s  | 7        | 0.7%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s | 7        | 0.7%    |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s            | 7        | 0.7%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 6        | 0.6%    |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s  | 6        | 0.6%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 6        | 0.6%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 5        | 0.5%    |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s    | 5        | 0.5%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 5        | 0.5%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 5        | 0.5%    |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 5        | 0.5%    |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s | 5        | 0.5%    |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s    | 5        | 0.5%    |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s  | 5        | 0.5%    |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s | 5        | 0.5%    |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s   | 5        | 0.5%    |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s            | 5        | 0.5%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s     | 4        | 0.4%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 4        | 0.4%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s    | 4        | 0.4%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s    | 4        | 0.4%    |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s   | 4        | 0.4%    |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s   | 4        | 0.4%    |
| G.Skill RAM F4-3600C18-32GVK 32GB DIMM DDR4 3600MT/s   | 4        | 0.4%    |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s   | 4        | 0.4%    |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s | 4        | 0.4%    |
| Corsair RAM CMW64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s | 4        | 0.4%    |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s | 4        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 599      | 69.41%  |
| DDR3    | 159      | 18.42%  |
| DDR5    | 60       | 6.95%   |
| Unknown | 17       | 1.97%   |
| DDR2    | 14       | 1.62%   |
| SDRAM   | 8        | 0.93%   |
| LPDDR4  | 3        | 0.35%   |
| DDR     | 2        | 0.23%   |
| DRAM    | 1        | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 828      | 96.39%  |
| SODIMM       | 29       | 3.38%   |
| Row Of Chips | 1        | 0.12%   |
| RIMM         | 1        | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 367      | 40.33%  |
| 16384 | 285      | 31.32%  |
| 4096  | 128      | 14.07%  |
| 32768 | 87       | 9.56%   |
| 2048  | 30       | 3.3%    |
| 1024  | 10       | 1.1%    |
| 512   | 2        | 0.22%   |
| 65536 | 1        | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 172      | 18.18%  |
| 3200    | 94       | 9.94%   |
| 1600    | 91       | 9.62%   |
| 2400    | 57       | 6.03%   |
| 1333    | 47       | 4.97%   |
| 3800    | 42       | 4.44%   |
| 3733    | 38       | 4.02%   |
| 2667    | 38       | 4.02%   |
| 2133    | 35       | 3.7%    |
| 3000    | 32       | 3.38%   |
| 6000    | 20       | 2.11%   |
| 4000    | 20       | 2.11%   |
| 3400    | 20       | 2.11%   |
| 2666    | 17       | 1.8%    |
| 1867    | 17       | 1.8%    |
| 3534    | 16       | 1.69%   |
| 2933    | 14       | 1.48%   |
| 3466    | 12       | 1.27%   |
| 800     | 12       | 1.27%   |
| 4800    | 11       | 1.16%   |
| 3866    | 11       | 1.16%   |
| 1866    | 11       | 1.16%   |
| 1800    | 11       | 1.16%   |
| 5200    | 10       | 1.06%   |
| 6400    | 7        | 0.74%   |
| 3066    | 7        | 0.74%   |
| 2800    | 7        | 0.74%   |
| 667     | 7        | 0.74%   |
| Unknown | 7        | 0.74%   |
| 5600    | 6        | 0.63%   |
| 3666    | 6        | 0.63%   |
| 4400    | 5        | 0.53%   |
| 12800   | 3        | 0.32%   |
| 3467    | 3        | 0.32%   |
| 3333    | 3        | 0.32%   |
| 3266    | 3        | 0.32%   |
| 3100    | 3        | 0.32%   |
| 1066    | 3        | 0.32%   |
| 4266    | 2        | 0.21%   |
| 3151    | 2        | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 55       | 30.22%  |
| Brother Industries    | 36       | 19.78%  |
| Canon                 | 28       | 15.38%  |
| Samsung Electronics   | 21       | 11.54%  |
| Seiko Epson           | 18       | 9.89%   |
| Dymo-CoStar           | 6        | 3.3%    |
| Fuji Xerox            | 3        | 1.65%   |
| STMicroelectronics    | 2        | 1.1%    |
| QinHeng Electronics   | 2        | 1.1%    |
| Kyocera               | 2        | 1.1%    |
| Dell                  | 2        | 1.1%    |
| Xerox                 | 1        | 0.55%   |
| Ricoh                 | 1        | 0.55%   |
| Prolific Technology   | 1        | 0.55%   |
| Pantum                | 1        | 0.55%   |
| Oki Data              | 1        | 0.55%   |
| Lexmark International | 1        | 0.55%   |
| Apple                 | 1        | 0.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Brother Printer                                           | 5        | 2.73%   |
| HP Deskjet 3050 J610 series                               | 4        | 2.19%   |
| Brother HL-2130 series                                    | 4        | 2.19%   |
| Samsung SCX-3400 Series                                   | 3        | 1.64%   |
| HP LaserJet Professional P 1102w                          | 3        | 1.64%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 3        | 1.64%   |
| Canon PIXMA MG2500 Series                                 | 3        | 1.64%   |
| Seiko Epson WF-4830 Series                                | 2        | 1.09%   |
| Seiko Epson L355 Series                                   | 2        | 1.09%   |
| Seiko Epson ET-3760 Series                                | 2        | 1.09%   |
| Seiko Epson ET-2700 Series                                | 2        | 1.09%   |
| Seiko Epson ET-2600 Series                                | 2        | 1.09%   |
| Samsung ML-1640 Series Laser Printer                      | 2        | 1.09%   |
| Samsung M2070 Series                                      | 2        | 1.09%   |
| Samsung M2020 Series                                      | 2        | 1.09%   |
| QinHeng CH340S                                            | 2        | 1.09%   |
| HP HP LaserJet M14-M17                                    | 2        | 1.09%   |
| HP ENVY Pro 6400 series                                   | 2        | 1.09%   |
| HP ENVY Photo 6200 series                                 | 2        | 1.09%   |
| HP ENVY 4500 series                                       | 2        | 1.09%   |
| HP DeskJet F4100 Printer series                           | 2        | 1.09%   |
| HP Deskjet F2280 series                                   | 2        | 1.09%   |
| HP DeskJet 2620 All-in-One Printer                        | 2        | 1.09%   |
| HP Deskjet 1050 J410                                      | 2        | 1.09%   |
| HP Deskjet 1000 J110 series                               | 2        | 1.09%   |
| Fuji Xerox DocuPrint CM315/318 z                          | 2        | 1.09%   |
| Dymo-CoStar LabelWriter 450                               | 2        | 1.09%   |
| Canon PIXMA MX920 Series                                  | 2        | 1.09%   |
| Canon LiDE 400                                            | 2        | 1.09%   |
| Brother HL-L3230CDW series                                | 2        | 1.09%   |
| Brother HL-2270DW Laser Printer                           | 2        | 1.09%   |
| Brother HL-1110 series                                    | 2        | 1.09%   |
| Xerox Phaser 6000B                                        | 1        | 0.55%   |
| STMicroelectronics YICHIP3121 Virtual ComPort in FS Mode  | 1        | 0.55%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.55%   |
| Seiko Epson XP-3100 Series                                | 1        | 0.55%   |
| Seiko Epson XP-243 245 247 Series                         | 1        | 0.55%   |
| Seiko Epson WF-3520 Series                                | 1        | 0.55%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1        | 0.55%   |
| Seiko Epson L365 Series                                   | 1        | 0.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 11       | 45.83%  |
| Seiko Epson     | 8        | 33.33%  |
| Hewlett-Packard | 4        | 16.67%  |
| Mustek Systems  | 1        | 4.17%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson Perfection V37/V370                         | 2        | 8.33%   |
| Canon CanoScan N1240U/LiDE 30                           | 2        | 8.33%   |
| Canon CanoScan LiDE 210                                 | 2        | 8.33%   |
| Seiko Epson Scanner                                     | 1        | 4.17%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1        | 4.17%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1        | 4.17%   |
| Seiko Epson GT-X700 [Perfection 4870]                   | 1        | 4.17%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 4.17%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1        | 4.17%   |
| Mustek Systems ScanExpress 1200 UB                      | 1        | 4.17%   |
| HP Scanjet G2710                                        | 1        | 4.17%   |
| HP ScanJet 82x0C                                        | 1        | 4.17%   |
| HP Scanjet 300                                          | 1        | 4.17%   |
| HP ScanJet 2400c                                        | 1        | 4.17%   |
| Canon CanoScan N650U/N656U                              | 1        | 4.17%   |
| Canon CanoScan LiDE 60                                  | 1        | 4.17%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1        | 4.17%   |
| Canon CanoScan LiDE 220                                 | 1        | 4.17%   |
| Canon CanoScan LiDE 200                                 | 1        | 4.17%   |
| Canon CanoScan LiDE 110                                 | 1        | 4.17%   |
| Canon CanoScan 9000F Mark II                            | 1        | 4.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 388      | 43.26%  |
| Microdia                      | 78       | 8.7%    |
| Microsoft                     | 45       | 5.02%   |
| Sunplus Innovation Technology | 37       | 4.12%   |
| Generalplus Technology        | 25       | 2.79%   |
| Apple                         | 25       | 2.79%   |
| Samsung Electronics           | 19       | 2.12%   |
| Razer USA                     | 18       | 2.01%   |
| Valve Software                | 16       | 1.78%   |
| Realtek Semiconductor         | 16       | 1.78%   |
| ARC International             | 16       | 1.78%   |
| Jieli Technology              | 13       | 1.45%   |
| Creative Technology           | 13       | 1.45%   |
| Chicony Electronics           | 13       | 1.45%   |
| Z-Star Microelectronics       | 12       | 1.34%   |
| MacroSilicon                  | 10       | 1.11%   |
| KYE Systems (Mouse Systems)   | 9        | 1%      |
| Hewlett-Packard               | 8        | 0.89%   |
| Cubeternet                    | 7        | 0.78%   |
| Trust                         | 6        | 0.67%   |
| eMeet                         | 6        | 0.67%   |
| YGTek                         | 5        | 0.56%   |
| LG Electronics                | 5        | 0.56%   |
| Huawei Technologies           | 5        | 0.56%   |
| AVerMedia Technologies        | 5        | 0.56%   |
| Aveo Technology               | 5        | 0.56%   |
| ValueHD                       | 4        | 0.45%   |
| Anker PowerConf C200          | 4        | 0.45%   |
| 2M UVC CAMERA                 | 4        | 0.45%   |
| Unknown                       | 3        | 0.33%   |
| Alcor Micro                   | 3        | 0.33%   |
| A4Tech                        | 3        | 0.33%   |
| WCM_USB                       | 2        | 0.22%   |
| WaveRider Communications      | 2        | 0.22%   |
| SunplusIT                     | 2        | 0.22%   |
| Sunplus IT                    | 2        | 0.22%   |
| SN0002                        | 2        | 0.22%   |
| Ruision                       | 2        | 0.22%   |
| OmniVision Technologies       | 2        | 0.22%   |
| Novatek Microelectronics      | 2        | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 96       | 10.63%  |
| Logitech Webcam C270                    | 71       | 7.86%   |
| Logitech C922 Pro Stream Webcam         | 39       | 4.32%   |
| Microdia Webcam Vitade AF               | 29       | 3.21%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 24       | 2.66%   |
| Logitech BRIO Ultra HD Webcam           | 23       | 2.55%   |
| Generalplus GENERAL WEBCAM              | 23       | 2.55%   |
| Samsung Galaxy series, misc. (MTP mode) | 19       | 2.1%    |
| Microdia USB 2.0 Camera                 | 18       | 1.99%   |
| Microsoft LifeCam HD-3000               | 17       | 1.88%   |
| Valve Software 3D Camera                | 16       | 1.77%   |
| Logitech HD Webcam C615                 | 16       | 1.77%   |
| Logitech HD Webcam C525                 | 16       | 1.77%   |
| ARC International Camera                | 16       | 1.77%   |
| Logitech Logitech Webcam C925e          | 13       | 1.44%   |
| Razer USA Gaming Webcam [Kiyo]          | 12       | 1.33%   |
| Jieli USB PHY 2.0                       | 12       | 1.33%   |
| Logitech Webcam C310                    | 11       | 1.22%   |
| Logitech StreamCam                      | 11       | 1.22%   |
| Sunplus Full HD webcam                  | 10       | 1.11%   |
| Microsoft LifeCam Cinema                | 10       | 1.11%   |
| Logitech Webcam C930e                   | 10       | 1.11%   |
| Logitech Webcam C170                    | 10       | 1.11%   |
| Logitech Webcam Pro 9000                | 9        | 1%      |
| Microdia Integrated Camera              | 8        | 0.89%   |
| MacroSilicon USB Video                  | 8        | 0.89%   |
| Microdia Camera                         | 7        | 0.78%   |
| Logitech HD Webcam C910                 | 7        | 0.78%   |
| Logitech BRIO 4K Stream Edition         | 6        | 0.66%   |
| Chicony HP High Definition 1MP Webcam   | 6        | 0.66%   |
| YGTek Webcam                            | 5        | 0.55%   |
| Sunplus DICOTA 4K                       | 5        | 0.55%   |
| Logitech HD Webcam C510                 | 5        | 0.55%   |
| Huawei HiCamera                         | 5        | 0.55%   |
| eMeet HD Webcam C960                    | 5        | 0.55%   |
| AVerMedia Live Streamer CAM 313         | 5        | 0.55%   |
| Sunplus USB 2.0 Camera                  | 4        | 0.44%   |
| Realtek FULL HD 1080P Webcam            | 4        | 0.44%   |
| Razer USA Razer Kiyo Pro                | 4        | 0.44%   |
| Microsoft MicrosoftÂ LifeCam Studio    | 4        | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 2        | 25%     |
| Elan Microelectronics | 2        | 25%     |
| Validity Sensors      | 1        | 12.5%   |
| LighTuning Technology | 1        | 12.5%   |
| DigitalPersona        | 1        | 12.5%   |
| AuthenTec             | 1        | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052                | 2        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200]                 | 2        | 25%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1        | 12.5%   |
| LighTuning Fingerprint Sensor                               | 1        | 12.5%   |
| DigitalPersona Fingerprint Reader                           | 1        | 12.5%   |
| AuthenTec Fingerprint Sensor                                | 1        | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 7        | 35%     |
| Alcor Micro           | 4        | 20%     |
| Realtek Semiconductor | 3        | 15%     |
| OmniKey               | 3        | 15%     |
| Chicony Electronics   | 2        | 10%     |
| Advanced Card Systems | 1        | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 5        | 25%     |
| Realtek Semiconductor Smart Card Reader Interface      | 3        | 15%     |
| OmniKey CardMan 3021 / 3121                            | 2        | 10%     |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 2        | 10%     |
| Alcor Micro Watchdata W 1981                           | 2        | 10%     |
| Alcor Micro AU9540 Smartcard Reader                    | 2        | 10%     |
| SCM Microsystems SCR3500 A Contact Reader              | 1        | 5%      |
| SCM Microsystems SCR331 SmartCard Reader               | 1        | 5%      |
| OmniKey CardMan 1021                                   | 1        | 5%      |
| Advanced Card Systems ACR1252 Dual Reader              | 1        | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3697     | 81%     |
| 1     | 777      | 17.02%  |
| 2     | 75       | 1.64%   |
| 3     | 11       | 0.24%   |
| 5     | 2        | 0.04%   |
| 7     | 1        | 0.02%   |
| 4     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 339      | 35.87%  |
| Net/wireless             | 328      | 34.71%  |
| Unassigned class         | 66       | 6.98%   |
| Sound                    | 31       | 3.28%   |
| Multimedia controller    | 28       | 2.96%   |
| Bluetooth                | 28       | 2.96%   |
| Communication controller | 25       | 2.65%   |
| Storage/raid             | 24       | 2.54%   |
| Net/ethernet             | 15       | 1.59%   |
| Chipcard                 | 15       | 1.59%   |
| Network                  | 13       | 1.38%   |
| Camera                   | 10       | 1.06%   |
| Fingerprint reader       | 8        | 0.85%   |
| Storage/ide              | 4        | 0.42%   |
| Card reader              | 4        | 0.42%   |
| Storage/nvme             | 3        | 0.32%   |
| Firewire controller      | 2        | 0.21%   |
| Tv card                  | 1        | 0.11%   |
| Dvb card                 | 1        | 0.11%   |

