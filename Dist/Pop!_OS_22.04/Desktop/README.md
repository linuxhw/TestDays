Pop!_OS 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

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

Total: 342

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | A520I AC                    | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| EVGA          | 134-KS-E377                 | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| MSI           | MEG Z690 UNIFY              | [571f500e5e](https://linux-hardware.org/?probe=571f500e5e) | Jul 30, 2022 |
| Dell          | 0TP412                      | [c6138574f4](https://linux-hardware.org/?probe=c6138574f4) | Jul 30, 2022 |
| Gigabyte      | A520I AC                    | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| MSI           | B450M MORTAR MAX            | [1316e90024](https://linux-hardware.org/?probe=1316e90024) | Jul 30, 2022 |
| HP            | 2215                        | [6e351e6da3](https://linux-hardware.org/?probe=6e351e6da3) | Jul 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [31b2d82a52](https://linux-hardware.org/?probe=31b2d82a52) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | [622aa6421e](https://linux-hardware.org/?probe=622aa6421e) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | [d8c0404bad](https://linux-hardware.org/?probe=d8c0404bad) | Jul 29, 2022 |
| MACHINIST     | X79 V2.82H                  | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [b25ca31168](https://linux-hardware.org/?probe=b25ca31168) | Jul 27, 2022 |
| MSI           | PRO Z690-A DDR4             | [2d81f40aad](https://linux-hardware.org/?probe=2d81f40aad) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| Dell          | 0F896N A02                  | [ede9425ed8](https://linux-hardware.org/?probe=ede9425ed8) | Jul 27, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASUSTek       | PRIME Z390-A                | [b8e8d2b6c4](https://linux-hardware.org/?probe=b8e8d2b6c4) | Jul 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [567addf380](https://linux-hardware.org/?probe=567addf380) | Jul 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [221bb14fbd](https://linux-hardware.org/?probe=221bb14fbd) | Jul 24, 2022 |
| MSI           | MEG X570 ACE                | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8f131b55b9](https://linux-hardware.org/?probe=8f131b55b9) | Jul 22, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [20d32236ad](https://linux-hardware.org/?probe=20d32236ad) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a52692425](https://linux-hardware.org/?probe=5a52692425) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f524dac3fa](https://linux-hardware.org/?probe=f524dac3fa) | Jul 20, 2022 |
| MSI           | Z590-A PRO                  | [9500cfd7e1](https://linux-hardware.org/?probe=9500cfd7e1) | Jul 19, 2022 |
| Dell          | 02YYK5 A01                  | [94b2dc99fa](https://linux-hardware.org/?probe=94b2dc99fa) | Jul 19, 2022 |
| Lenovo        | MAHOBAY                     | [c1c146a0f9](https://linux-hardware.org/?probe=c1c146a0f9) | Jul 18, 2022 |
| Gigabyte      | B75M-D3H                    | [1c0d0a79d1](https://linux-hardware.org/?probe=1c0d0a79d1) | Jul 17, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | [3c55557131](https://linux-hardware.org/?probe=3c55557131) | Jul 17, 2022 |
| Gigabyte      | H97M-Gaming 3               | [a72ad8ba14](https://linux-hardware.org/?probe=a72ad8ba14) | Jul 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [36ad4a7384](https://linux-hardware.org/?probe=36ad4a7384) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [a23b73c3ff](https://linux-hardware.org/?probe=a23b73c3ff) | Jul 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [2e73a9947c](https://linux-hardware.org/?probe=2e73a9947c) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c9ff108124](https://linux-hardware.org/?probe=c9ff108124) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M90p 5864A1U    | [406232d6c2](https://linux-hardware.org/?probe=406232d6c2) | Jul 15, 2022 |
| MSI           | Z170A GAMING M5             | [16d2d7469b](https://linux-hardware.org/?probe=16d2d7469b) | Jul 15, 2022 |
| Gigabyte      | H310M S2 x.x                | [a55538b651](https://linux-hardware.org/?probe=a55538b651) | Jul 14, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [608d209fe5](https://linux-hardware.org/?probe=608d209fe5) | Jul 14, 2022 |
| ASRock        | Z77 Pro4-M                  | [69b486ea31](https://linux-hardware.org/?probe=69b486ea31) | Jul 14, 2022 |
| Dell          | 02YYK5 A01                  | [ca4bfe598b](https://linux-hardware.org/?probe=ca4bfe598b) | Jul 14, 2022 |
| ASUSTek       | M4A79XTD EVO                | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| ASRock        | B450M Steel Legend          | [3732c0ad0c](https://linux-hardware.org/?probe=3732c0ad0c) | Jul 13, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [a6d5a615d0](https://linux-hardware.org/?probe=a6d5a615d0) | Jul 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [d7e4d34816](https://linux-hardware.org/?probe=d7e4d34816) | Jul 12, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [a3c14e06c9](https://linux-hardware.org/?probe=a3c14e06c9) | Jul 11, 2022 |
| MSI           | P67A-C43                    | [c76725f62c](https://linux-hardware.org/?probe=c76725f62c) | Jul 11, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [84e5c2ab51](https://linux-hardware.org/?probe=84e5c2ab51) | Jul 11, 2022 |
| ASUSTek       | P5Q-PRO                     | [ad6eedb5e5](https://linux-hardware.org/?probe=ad6eedb5e5) | Jul 10, 2022 |
| ASUSTek       | Z170-A                      | [1ac13f76b1](https://linux-hardware.org/?probe=1ac13f76b1) | Jul 10, 2022 |
| Dell          | 042P49 A02                  | [1b8b98b54d](https://linux-hardware.org/?probe=1b8b98b54d) | Jul 10, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [0e0d93b899](https://linux-hardware.org/?probe=0e0d93b899) | Jul 10, 2022 |
| ASUSTek       | P5Q-PRO                     | [9860ca66f6](https://linux-hardware.org/?probe=9860ca66f6) | Jul 09, 2022 |
| Gigabyte      | B450 AORUS M                | [5d50b40871](https://linux-hardware.org/?probe=5d50b40871) | Jul 09, 2022 |
| HP            | 1495                        | [3e67bd3405](https://linux-hardware.org/?probe=3e67bd3405) | Jul 09, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [a374367376](https://linux-hardware.org/?probe=a374367376) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [fe383d7488](https://linux-hardware.org/?probe=fe383d7488) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [786c9e341c](https://linux-hardware.org/?probe=786c9e341c) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [833f3df27a](https://linux-hardware.org/?probe=833f3df27a) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [199e7db55a](https://linux-hardware.org/?probe=199e7db55a) | Jul 09, 2022 |
| Gigabyte      | B550 AORUS PRO AX           | [9ad45447d4](https://linux-hardware.org/?probe=9ad45447d4) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6ebe4f89b7](https://linux-hardware.org/?probe=6ebe4f89b7) | Jul 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [3458084b51](https://linux-hardware.org/?probe=3458084b51) | Jul 08, 2022 |
| HP            | 3398                        | [fb1290d5b3](https://linux-hardware.org/?probe=fb1290d5b3) | Jul 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8b1a622249](https://linux-hardware.org/?probe=8b1a622249) | Jul 07, 2022 |
| ASUSTek       | PRIME Z390-A                | [0e7b73b341](https://linux-hardware.org/?probe=0e7b73b341) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [9c2efc454e](https://linux-hardware.org/?probe=9c2efc454e) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [eb5d4499aa](https://linux-hardware.org/?probe=eb5d4499aa) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [e068e197b4](https://linux-hardware.org/?probe=e068e197b4) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Soyo          | SY-A68M FS V2.0             | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [7a6f484b16](https://linux-hardware.org/?probe=7a6f484b16) | Jul 06, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [bfa2b2f092](https://linux-hardware.org/?probe=bfa2b2f092) | Jul 05, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [161f8c2665](https://linux-hardware.org/?probe=161f8c2665) | Jul 03, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [15118ef9fd](https://linux-hardware.org/?probe=15118ef9fd) | Jul 03, 2022 |
| HP            | 18E7                        | [8f2b2cb5e5](https://linux-hardware.org/?probe=8f2b2cb5e5) | Jul 02, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7da3547526](https://linux-hardware.org/?probe=7da3547526) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d979555615](https://linux-hardware.org/?probe=d979555615) | Jul 01, 2022 |
| ASRock        | B450 Gaming K4              | [2bdfc5f472](https://linux-hardware.org/?probe=2bdfc5f472) | Jul 01, 2022 |
| MSI           | B250M PRO-VD                | [b48e88849b](https://linux-hardware.org/?probe=b48e88849b) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [8c29343495](https://linux-hardware.org/?probe=8c29343495) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [2631bf2ae1](https://linux-hardware.org/?probe=2631bf2ae1) | Jul 01, 2022 |
| HP            | 18E7                        | [1808b6dee4](https://linux-hardware.org/?probe=1808b6dee4) | Jul 01, 2022 |
| Dell          | 0HHV7N A00                  | [41255f7150](https://linux-hardware.org/?probe=41255f7150) | Jun 30, 2022 |
| ASRock        | X399 Taichi                 | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | [b85b1f9277](https://linux-hardware.org/?probe=b85b1f9277) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | [67dc174a62](https://linux-hardware.org/?probe=67dc174a62) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | [f01192b57e](https://linux-hardware.org/?probe=f01192b57e) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [0a66ce61c6](https://linux-hardware.org/?probe=0a66ce61c6) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [f2b790de57](https://linux-hardware.org/?probe=f2b790de57) | Jun 29, 2022 |
| HP            | 3647h                       | [3227f38f98](https://linux-hardware.org/?probe=3227f38f98) | Jun 28, 2022 |
| Gigabyte      | Z170-Gaming K3              | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | [8efb1d3556](https://linux-hardware.org/?probe=8efb1d3556) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | [5b239d8bba](https://linux-hardware.org/?probe=5b239d8bba) | Jun 28, 2022 |
| ASRock        | B450 Gaming K4              | [6ecc609381](https://linux-hardware.org/?probe=6ecc609381) | Jun 27, 2022 |
| ASRock        | B450 Steel Legend           | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| ASUSTek       | VM40B                       | [35f67bace1](https://linux-hardware.org/?probe=35f67bace1) | Jun 26, 2022 |
| Dell          | 0D6H9T A00                  | [fd65f44d25](https://linux-hardware.org/?probe=fd65f44d25) | Jun 26, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [6580b51e30](https://linux-hardware.org/?probe=6580b51e30) | Jun 25, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [01fcd4495e](https://linux-hardware.org/?probe=01fcd4495e) | Jun 25, 2022 |
| Dell          | 040DDP A00                  | [02721926a7](https://linux-hardware.org/?probe=02721926a7) | Jun 25, 2022 |
| MSI           | MAG Z690 TORPEDO            | [44700880cf](https://linux-hardware.org/?probe=44700880cf) | Jun 24, 2022 |
| ASUSTek       | LEUCITE                     | [c4d2ed5723](https://linux-hardware.org/?probe=c4d2ed5723) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | [517a155f9b](https://linux-hardware.org/?probe=517a155f9b) | Jun 24, 2022 |
| Dell          | 0WMJ54 A01                  | [ee865231c1](https://linux-hardware.org/?probe=ee865231c1) | Jun 24, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [055977bdee](https://linux-hardware.org/?probe=055977bdee) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [1e7e58ae1d](https://linux-hardware.org/?probe=1e7e58ae1d) | Jun 23, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [0bd1e7d592](https://linux-hardware.org/?probe=0bd1e7d592) | Jun 23, 2022 |
| ASUSTek       | PRIME B550M-A               | [d4492d1e5d](https://linux-hardware.org/?probe=d4492d1e5d) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ae30cadddf](https://linux-hardware.org/?probe=ae30cadddf) | Jun 22, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [21d1dc43e6](https://linux-hardware.org/?probe=21d1dc43e6) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [27bc9defca](https://linux-hardware.org/?probe=27bc9defca) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [941b96e6ab](https://linux-hardware.org/?probe=941b96e6ab) | Jun 22, 2022 |
| BESSTAR Te... | UM700                       | [5dc08ee2d7](https://linux-hardware.org/?probe=5dc08ee2d7) | Jun 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d5fd58e3b0](https://linux-hardware.org/?probe=d5fd58e3b0) | Jun 21, 2022 |
| ASUSTek       | PRIME Z370-A                | [8dca736a46](https://linux-hardware.org/?probe=8dca736a46) | Jun 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [f747d1bfd3](https://linux-hardware.org/?probe=f747d1bfd3) | Jun 21, 2022 |
| System76      | Thelio thelio-r2            | [b9b9d5ffda](https://linux-hardware.org/?probe=b9b9d5ffda) | Jun 21, 2022 |
| MSI           | B550M-A PRO                 | [1765b91360](https://linux-hardware.org/?probe=1765b91360) | Jun 21, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [eb61c79793](https://linux-hardware.org/?probe=eb61c79793) | Jun 21, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [6ddca91c97](https://linux-hardware.org/?probe=6ddca91c97) | Jun 21, 2022 |
| Biostar       | N68S3+                      | [efe83d16ac](https://linux-hardware.org/?probe=efe83d16ac) | Jun 21, 2022 |
| Intel         | MAHOBAY                     | [f615165669](https://linux-hardware.org/?probe=f615165669) | Jun 21, 2022 |
| ASRock        | B450 Gaming K4              | [230bdf84a1](https://linux-hardware.org/?probe=230bdf84a1) | Jun 20, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [ec3bc83e7a](https://linux-hardware.org/?probe=ec3bc83e7a) | Jun 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [d5af99ece6](https://linux-hardware.org/?probe=d5af99ece6) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V LX                  | [ad271e0eec](https://linux-hardware.org/?probe=ad271e0eec) | Jun 19, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | [3d4d492e9d](https://linux-hardware.org/?probe=3d4d492e9d) | Jun 19, 2022 |
| Dell          | 0YXT71 A03                  | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| HP            | 158B                        | [b66a2770e7](https://linux-hardware.org/?probe=b66a2770e7) | Jun 18, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [6ba04b0f37](https://linux-hardware.org/?probe=6ba04b0f37) | Jun 18, 2022 |
| BESSTAR Te... | UM700                       | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| Intel         | MAHOBAY                     | [755ead951d](https://linux-hardware.org/?probe=755ead951d) | Jun 17, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [5241a60357](https://linux-hardware.org/?probe=5241a60357) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f4178c276d](https://linux-hardware.org/?probe=f4178c276d) | Jun 16, 2022 |
| Intel         | MAHOBAY                     | [91039940ea](https://linux-hardware.org/?probe=91039940ea) | Jun 16, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [24140a62de](https://linux-hardware.org/?probe=24140a62de) | Jun 16, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| MSI           | B450 TOMAHAWK               | [e11d001f52](https://linux-hardware.org/?probe=e11d001f52) | Jun 15, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [29cfeda814](https://linux-hardware.org/?probe=29cfeda814) | Jun 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [b12643d9ac](https://linux-hardware.org/?probe=b12643d9ac) | Jun 15, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d4e4001c4c](https://linux-hardware.org/?probe=d4e4001c4c) | Jun 15, 2022 |
| Medion        | MS-7728                     | [ae02539c17](https://linux-hardware.org/?probe=ae02539c17) | Jun 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [5be4039515](https://linux-hardware.org/?probe=5be4039515) | Jun 15, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [507c214577](https://linux-hardware.org/?probe=507c214577) | Jun 15, 2022 |
| MSI           | B550-A PRO                  | [f7201ee1de](https://linux-hardware.org/?probe=f7201ee1de) | Jun 14, 2022 |
| HP            | 1905                        | [b3d0170095](https://linux-hardware.org/?probe=b3d0170095) | Jun 14, 2022 |
| HP            | 18E7                        | [9f82638329](https://linux-hardware.org/?probe=9f82638329) | Jun 14, 2022 |
| Lenovo        | 0B98401 PRO                 | [23de86aa97](https://linux-hardware.org/?probe=23de86aa97) | Jun 14, 2022 |
| Alienware     | 0R3FWM A00                  | [6690a39447](https://linux-hardware.org/?probe=6690a39447) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f9e74fdcd3](https://linux-hardware.org/?probe=f9e74fdcd3) | Jun 13, 2022 |
| Dell          | 073MMW A03                  | [3e206d2462](https://linux-hardware.org/?probe=3e206d2462) | Jun 13, 2022 |
| ASUSTek       | Z87-K                       | [cafc34944d](https://linux-hardware.org/?probe=cafc34944d) | Jun 13, 2022 |
| MSI           | B350 PC MATE                | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [a332c946a2](https://linux-hardware.org/?probe=a332c946a2) | Jun 11, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [d02f89642d](https://linux-hardware.org/?probe=d02f89642d) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | [a4277bcba9](https://linux-hardware.org/?probe=a4277bcba9) | Jun 11, 2022 |
| MSI           | MEG X570 ACE                | [d88374c06d](https://linux-hardware.org/?probe=d88374c06d) | Jun 11, 2022 |
| Unknown       | Unknown                     | [19d1362c66](https://linux-hardware.org/?probe=19d1362c66) | Jun 10, 2022 |
| Gigabyte      | H87M-HD3                    | [eadd724efa](https://linux-hardware.org/?probe=eadd724efa) | Jun 10, 2022 |
| MSI           | H97 GAMING 3                | [839bbee3fa](https://linux-hardware.org/?probe=839bbee3fa) | Jun 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [1fef4f1cf3](https://linux-hardware.org/?probe=1fef4f1cf3) | Jun 10, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [9c7b34c996](https://linux-hardware.org/?probe=9c7b34c996) | Jun 09, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [44a6f3e33d](https://linux-hardware.org/?probe=44a6f3e33d) | Jun 07, 2022 |
| Gigabyte      | Z390 UD                     | [cd4b8b609f](https://linux-hardware.org/?probe=cd4b8b609f) | Jun 07, 2022 |
| Dell          | 0JW6C6 A01                  | [34d9fc3968](https://linux-hardware.org/?probe=34d9fc3968) | Jun 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [56c4428636](https://linux-hardware.org/?probe=56c4428636) | Jun 06, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a0c155ffb9](https://linux-hardware.org/?probe=a0c155ffb9) | Jun 05, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [816b4e757d](https://linux-hardware.org/?probe=816b4e757d) | Jun 05, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [e92e195362](https://linux-hardware.org/?probe=e92e195362) | Jun 05, 2022 |
| ASUSTek       | P8Z68-V LX                  | [e7e3608105](https://linux-hardware.org/?probe=e7e3608105) | Jun 04, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [a65dd5834e](https://linux-hardware.org/?probe=a65dd5834e) | Jun 04, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [81bfe17cb5](https://linux-hardware.org/?probe=81bfe17cb5) | Jun 04, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [95db56a864](https://linux-hardware.org/?probe=95db56a864) | Jun 03, 2022 |
| ASUSTek       | Z87-K                       | [915e2819c0](https://linux-hardware.org/?probe=915e2819c0) | Jun 02, 2022 |
| ASRock        | Z390 Phantom Gaming SLI/... | [5f40da7ae9](https://linux-hardware.org/?probe=5f40da7ae9) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5348dd6576](https://linux-hardware.org/?probe=5348dd6576) | Jun 01, 2022 |
| ASUSTek       | PRIME Z590-A                | [fa29e357fa](https://linux-hardware.org/?probe=fa29e357fa) | Jun 01, 2022 |
| ASUSTek       | F2A85-M                     | [82b4935292](https://linux-hardware.org/?probe=82b4935292) | Jun 01, 2022 |
| MSI           | Z170A MPOWER GAMING TITA... | [538feade4f](https://linux-hardware.org/?probe=538feade4f) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [bee74ec003](https://linux-hardware.org/?probe=bee74ec003) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| System76      | Thelio Major thelio-majo... | [291730a3bb](https://linux-hardware.org/?probe=291730a3bb) | May 31, 2022 |
| Dell          | 0Y2MRG A00                  | [013e0da975](https://linux-hardware.org/?probe=013e0da975) | May 30, 2022 |
| Dell          | 0D02VH A01                  | [fc97b0a5bf](https://linux-hardware.org/?probe=fc97b0a5bf) | May 30, 2022 |
| ASUSTek       | PRIME Z590-A                | [1058cdf867](https://linux-hardware.org/?probe=1058cdf867) | May 30, 2022 |
| HP            | 8266                        | [d0e35451ab](https://linux-hardware.org/?probe=d0e35451ab) | May 29, 2022 |
| Gigabyte      | H270-Gaming 3               | [c28c21c4d8](https://linux-hardware.org/?probe=c28c21c4d8) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [5d899f8fc5](https://linux-hardware.org/?probe=5d899f8fc5) | May 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d1923db949](https://linux-hardware.org/?probe=d1923db949) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b78390767c](https://linux-hardware.org/?probe=b78390767c) | May 28, 2022 |
| MSI           | MS-7717                     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| MSI           | MS-7717                     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ASRock        | B450 Steel Legend           | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Dell          | 040DDP A01                  | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| HP            | 158B                        | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [bdf54228e5](https://linux-hardware.org/?probe=bdf54228e5) | May 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f5195788f8](https://linux-hardware.org/?probe=f5195788f8) | May 27, 2022 |
| ASUSTek       | PRIME Z270-A                | [5d1ee4048a](https://linux-hardware.org/?probe=5d1ee4048a) | May 27, 2022 |
| ASUSTek       | P5KPL-SE                    | [c4b27d79ef](https://linux-hardware.org/?probe=c4b27d79ef) | May 26, 2022 |
| ASUSTek       | P5QPL-AM                    | [938ab3ec5c](https://linux-hardware.org/?probe=938ab3ec5c) | May 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ae0ada290a](https://linux-hardware.org/?probe=ae0ada290a) | May 26, 2022 |
| ASRock        | H670M-ITX/ax                | [b3f7ff3d98](https://linux-hardware.org/?probe=b3f7ff3d98) | May 25, 2022 |
| ASUSTek       | M5A78L/USB3                 | [852a292ba3](https://linux-hardware.org/?probe=852a292ba3) | May 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [4738560555](https://linux-hardware.org/?probe=4738560555) | May 25, 2022 |
| HP            | 8703                        | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| ASRock        | H470M-ITX/ac                | [181f7decc6](https://linux-hardware.org/?probe=181f7decc6) | May 24, 2022 |
| Dell          | 0Y2MRG A00                  | [08527b166e](https://linux-hardware.org/?probe=08527b166e) | May 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1122022ae1](https://linux-hardware.org/?probe=1122022ae1) | May 24, 2022 |
| SIEMENS       | A5E02122237 ES010           | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| Lenovo        | MAHOBAY                     | [dbfb736222](https://linux-hardware.org/?probe=dbfb736222) | May 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [78bb2ba75c](https://linux-hardware.org/?probe=78bb2ba75c) | May 23, 2022 |
| Foxconn       | 2ABF                        | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [21818b99b4](https://linux-hardware.org/?probe=21818b99b4) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [f1db82519f](https://linux-hardware.org/?probe=f1db82519f) | May 22, 2022 |
| MSI           | MEG Z390 ACE                | [0065576586](https://linux-hardware.org/?probe=0065576586) | May 22, 2022 |
| Gigabyte      | H67N-USB3-B3                | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| ASRock        | B450 Steel Legend           | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| ASUSTek       | P7P55D-E LX                 | [358e85c524](https://linux-hardware.org/?probe=358e85c524) | May 21, 2022 |
| MSI           | B250M PRO-VD                | [540e0831b1](https://linux-hardware.org/?probe=540e0831b1) | May 20, 2022 |
| ASRock        | TRX40 Creator               | [a810336f3f](https://linux-hardware.org/?probe=a810336f3f) | May 20, 2022 |
| ASRock        | TRX40 Creator               | [6993400976](https://linux-hardware.org/?probe=6993400976) | May 20, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [2211d5c2a2](https://linux-hardware.org/?probe=2211d5c2a2) | May 20, 2022 |
| ASUSTek       | H110M-R                     | [7cae58580a](https://linux-hardware.org/?probe=7cae58580a) | May 20, 2022 |
| ASRock        | Z390 Phantom Gaming 4-IB    | [543ab770e8](https://linux-hardware.org/?probe=543ab770e8) | May 20, 2022 |
| Positivo      | POS-MI945AA                 | [0f9875e8fc](https://linux-hardware.org/?probe=0f9875e8fc) | May 19, 2022 |
| Lenovo        | MAHOBAY                     | [fa1f318919](https://linux-hardware.org/?probe=fa1f318919) | May 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [d94f4b0a43](https://linux-hardware.org/?probe=d94f4b0a43) | May 19, 2022 |
| Gigabyte      | B450 AORUS M                | [5ddfbf547b](https://linux-hardware.org/?probe=5ddfbf547b) | May 19, 2022 |
| Supermicro    | X8SIL                       | [66e8a4001f](https://linux-hardware.org/?probe=66e8a4001f) | May 18, 2022 |
| MSI           | B350M MORTAR                | [fd66fd9a5a](https://linux-hardware.org/?probe=fd66fd9a5a) | May 18, 2022 |
| Supermicro    | X8SIL                       | [5cb6f1067b](https://linux-hardware.org/?probe=5cb6f1067b) | May 18, 2022 |
| HP            | 8054                        | [725f204fd0](https://linux-hardware.org/?probe=725f204fd0) | May 18, 2022 |
| ASUSTek       | GA15DH                      | [ca68812bf2](https://linux-hardware.org/?probe=ca68812bf2) | May 17, 2022 |
| MSI           | Z270-A PRO                  | [f005623f03](https://linux-hardware.org/?probe=f005623f03) | May 17, 2022 |
| ASUSTek       | AM1M-A/BR                   | [e23e8291e0](https://linux-hardware.org/?probe=e23e8291e0) | May 17, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | [2f7a99c28b](https://linux-hardware.org/?probe=2f7a99c28b) | May 17, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [ee4e4a7bc7](https://linux-hardware.org/?probe=ee4e4a7bc7) | May 17, 2022 |
| Dell          | 040DDP A00                  | [4806ca2a7e](https://linux-hardware.org/?probe=4806ca2a7e) | May 17, 2022 |
| Gigabyte      | H310M S2H x.x               | [4d76b03e66](https://linux-hardware.org/?probe=4d76b03e66) | May 17, 2022 |
| ASUSTek       | Z87-K                       | [2daea316b2](https://linux-hardware.org/?probe=2daea316b2) | May 16, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [91d8b47a30](https://linux-hardware.org/?probe=91d8b47a30) | May 15, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [608664ce7a](https://linux-hardware.org/?probe=608664ce7a) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a049c51989](https://linux-hardware.org/?probe=a049c51989) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [0cc824e2a5](https://linux-hardware.org/?probe=0cc824e2a5) | May 13, 2022 |
| NZXT          | N7 B550                     | [73441bbfc4](https://linux-hardware.org/?probe=73441bbfc4) | May 12, 2022 |
| Unknown       | BTC79X5                     | [42b222eb65](https://linux-hardware.org/?probe=42b222eb65) | May 12, 2022 |
| Gigabyte      | Z170-Gaming K3              | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| AZW           | BT3 X                       | [a17cb64acb](https://linux-hardware.org/?probe=a17cb64acb) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [ee225906fc](https://linux-hardware.org/?probe=ee225906fc) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [16911d5e64](https://linux-hardware.org/?probe=16911d5e64) | May 11, 2022 |
| Gigabyte      | B660 AORUS MASTER DDR4      | [e5981a9f20](https://linux-hardware.org/?probe=e5981a9f20) | May 11, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| NZXT          | N7 B550                     | [147247dfb6](https://linux-hardware.org/?probe=147247dfb6) | May 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [396a39e5a6](https://linux-hardware.org/?probe=396a39e5a6) | May 10, 2022 |
| ASRock        | X370 Professional Gaming    | [1e22ba0468](https://linux-hardware.org/?probe=1e22ba0468) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [0b3cda16db](https://linux-hardware.org/?probe=0b3cda16db) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [90190717eb](https://linux-hardware.org/?probe=90190717eb) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| ASUSTek       | Z97-AR                      | [29c93ea162](https://linux-hardware.org/?probe=29c93ea162) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| ASRock        | X299 Taichi CLX             | [47a45fca48](https://linux-hardware.org/?probe=47a45fca48) | May 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [8964a4c5ec](https://linux-hardware.org/?probe=8964a4c5ec) | May 08, 2022 |
| ECS           | Nettle3                     | [36f8cde007](https://linux-hardware.org/?probe=36f8cde007) | May 08, 2022 |
| ASUSTek       | PRIME X570-P                | [65d94c8458](https://linux-hardware.org/?probe=65d94c8458) | May 08, 2022 |
| ECS           | Nettle3                     | [646fb53a2c](https://linux-hardware.org/?probe=646fb53a2c) | May 07, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [61a4daec98](https://linux-hardware.org/?probe=61a4daec98) | May 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [180dd73bd6](https://linux-hardware.org/?probe=180dd73bd6) | May 07, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| MSI           | B450-A PRO                  | [5b5ceb0f53](https://linux-hardware.org/?probe=5b5ceb0f53) | May 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [4fe934e84d](https://linux-hardware.org/?probe=4fe934e84d) | May 06, 2022 |
| ASRock        | 970M Pro3                   | [2853128cd0](https://linux-hardware.org/?probe=2853128cd0) | May 05, 2022 |
| ASRock        | 970M Pro3                   | [5f51fd4cf8](https://linux-hardware.org/?probe=5f51fd4cf8) | May 05, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [7b7f29e504](https://linux-hardware.org/?probe=7b7f29e504) | May 05, 2022 |
| ASRock        | X470 Taichi                 | [e133868179](https://linux-hardware.org/?probe=e133868179) | May 05, 2022 |
| ASRock        | X470 Taichi                 | [93d6fb1610](https://linux-hardware.org/?probe=93d6fb1610) | May 05, 2022 |
| ASRock        | A320M-HDV R4.0              | [36cabd86ba](https://linux-hardware.org/?probe=36cabd86ba) | May 04, 2022 |
| ASUSTek       | B85M-E                      | [2b6338d755](https://linux-hardware.org/?probe=2b6338d755) | May 04, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [7196bf2ec6](https://linux-hardware.org/?probe=7196bf2ec6) | May 03, 2022 |
| ASRock        | 970M Pro3                   | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [65a2309744](https://linux-hardware.org/?probe=65a2309744) | May 03, 2022 |
| Alienware     | 0CPDXD A00                  | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| ASUSTek       | B85M-E                      | [9645231d87](https://linux-hardware.org/?probe=9645231d87) | May 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [c0ef0738b5](https://linux-hardware.org/?probe=c0ef0738b5) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [4a09f5d3f3](https://linux-hardware.org/?probe=4a09f5d3f3) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [ab716981c3](https://linux-hardware.org/?probe=ab716981c3) | May 02, 2022 |
| Alienware     | 0P0JWX A00                  | [e6e1548aa1](https://linux-hardware.org/?probe=e6e1548aa1) | May 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [a456619489](https://linux-hardware.org/?probe=a456619489) | May 02, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [925447d7e9](https://linux-hardware.org/?probe=925447d7e9) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b1e331055f](https://linux-hardware.org/?probe=b1e331055f) | May 01, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [dec71580c4](https://linux-hardware.org/?probe=dec71580c4) | May 01, 2022 |
| Gigabyte      | X570S AERO G                | [ab6b8eaa71](https://linux-hardware.org/?probe=ab6b8eaa71) | May 01, 2022 |
| MSI           | 970 GAMING                  | [32052450db](https://linux-hardware.org/?probe=32052450db) | May 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8db041a1e4](https://linux-hardware.org/?probe=8db041a1e4) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| MSI           | B450M GAMING PLUS           | [0929d58de7](https://linux-hardware.org/?probe=0929d58de7) | Apr 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [3edd5f05f7](https://linux-hardware.org/?probe=3edd5f05f7) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | [d45e1e88db](https://linux-hardware.org/?probe=d45e1e88db) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | [41cec63ac6](https://linux-hardware.org/?probe=41cec63ac6) | Apr 30, 2022 |
| EVGA          | X58 SLI Classified Tyler... | [07254f2dbb](https://linux-hardware.org/?probe=07254f2dbb) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [bce425f138](https://linux-hardware.org/?probe=bce425f138) | Apr 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [e37bc471b1](https://linux-hardware.org/?probe=e37bc471b1) | Apr 29, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [2b7167b16e](https://linux-hardware.org/?probe=2b7167b16e) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [aed5ee3ded](https://linux-hardware.org/?probe=aed5ee3ded) | Apr 28, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ab83eedd1f](https://linux-hardware.org/?probe=ab83eedd1f) | Apr 28, 2022 |
| MSI           | H55M-E23                    | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [46430e1117](https://linux-hardware.org/?probe=46430e1117) | Apr 28, 2022 |
| Dell          | 09KPNV A00                  | [5046e0575b](https://linux-hardware.org/?probe=5046e0575b) | Apr 28, 2022 |
| Dell          | 0NW73C A00                  | [344e2b816e](https://linux-hardware.org/?probe=344e2b816e) | Apr 28, 2022 |
| Dell          | 088DT1 A01                  | [b664b8720e](https://linux-hardware.org/?probe=b664b8720e) | Apr 28, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [19e0445e6f](https://linux-hardware.org/?probe=19e0445e6f) | Apr 27, 2022 |
| Dell          | 0R1PCR A00                  | [feec38a0f5](https://linux-hardware.org/?probe=feec38a0f5) | Apr 27, 2022 |
| Unknown       | Unknown                     | [82ad7e86b5](https://linux-hardware.org/?probe=82ad7e86b5) | Apr 27, 2022 |
| ASUSTek       | GA15DH                      | [30a22d7be3](https://linux-hardware.org/?probe=30a22d7be3) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| System76      | Thelio thelio-r2            | [aae937be8b](https://linux-hardware.org/?probe=aae937be8b) | Apr 25, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| MSI           | B250M BAZOOKA               | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.17.5-76051705-generic   | 155      | 55.76%  |
| 5.17.15-76051715-generic  | 59       | 21.22%  |
| 5.16.19-76051619-generic  | 40       | 14.39%  |
| 5.18.10-76051810-generic  | 21       | 7.55%   |
| 5.18.0-9.1-liquorix-amd64 | 1        | 0.36%   |
| 5.17.4-051704-generic     | 1        | 0.36%   |
| 5.16.15-76051615-generic  | 1        | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.5  | 155      | 55.76%  |
| 5.17.15 | 59       | 21.22%  |
| 5.16.19 | 40       | 14.39%  |
| 5.18.10 | 21       | 7.55%   |
| 5.18.0  | 1        | 0.36%   |
| 5.17.4  | 1        | 0.36%   |
| 5.16.15 | 1        | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17    | 210      | 76.92%  |
| 5.16    | 41       | 15.02%  |
| 5.18    | 22       | 8.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 268      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 260      | 97.01%  |
| KDE5       | 4        | 1.49%   |
| X-Cinnamon | 1        | 0.37%   |
| LXQt       | 1        | 0.37%   |
| Cinnamon   | 1        | 0.37%   |
| Unknown    | 1        | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 262      | 97.76%  |
| Wayland | 4        | 1.49%   |
| Tty     | 1        | 0.37%   |
| Unknown | 1        | 0.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 227      | 84.7%   |
| GDM3    | 39       | 14.55%  |
| SDDM    | 2        | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 159      | 59.11%  |
| pt_BR   | 14       | 5.2%    |
| en_GB   | 14       | 5.2%    |
| C       | 13       | 4.83%   |
| en_CA   | 12       | 4.46%   |
| de_DE   | 11       | 4.09%   |
| en_AU   | 8        | 2.97%   |
| fr_FR   | 6        | 2.23%   |
| pl_PL   | 5        | 1.86%   |
| sv_SE   | 4        | 1.49%   |
| es_ES   | 3        | 1.12%   |
| es_CL   | 3        | 1.12%   |
| nl_NL   | 2        | 0.74%   |
| ru_RU   | 1        | 0.37%   |
| ro_RO   | 1        | 0.37%   |
| nl_BE   | 1        | 0.37%   |
| ja_JP   | 1        | 0.37%   |
| it_IT   | 1        | 0.37%   |
| fi_FI   | 1        | 0.37%   |
| es_UY   | 1        | 0.37%   |
| es_DO   | 1        | 0.37%   |
| en_IN   | 1        | 0.37%   |
| en_IL   | 1        | 0.37%   |
| en_IE   | 1        | 0.37%   |
| en_DK   | 1        | 0.37%   |
| de_AT   | 1        | 0.37%   |
| cs_CZ   | 1        | 0.37%   |
| Unknown | 1        | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 231      | 86.19%  |
| EFI  | 37       | 13.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 252      | 94.03%  |
| Btrfs   | 9        | 3.36%   |
| Overlay | 6        | 2.24%   |
| Xfs     | 1        | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 226      | 84.33%  |
| GPT     | 41       | 15.3%   |
| MBR     | 1        | 0.37%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 261      | 97.39%  |
| Yes       | 7        | 2.61%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 238      | 88.81%  |
| Yes       | 30       | 11.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 80       | 29.85%  |
| Gigabyte Technology | 57       | 21.27%  |
| MSI                 | 39       | 14.55%  |
| Dell                | 21       | 7.84%   |
| ASRock              | 20       | 7.46%   |
| Hewlett-Packard     | 11       | 4.1%    |
| Lenovo              | 9        | 3.36%   |
| Alienware           | 4        | 1.49%   |
| System76            | 3        | 1.12%   |
| Unknown             | 3        | 1.12%   |
| MACHINIST           | 2        | 0.75%   |
| Intel               | 2        | 0.75%   |
| Fujitsu             | 2        | 0.75%   |
| Foxconn             | 2        | 0.75%   |
| EVGA                | 2        | 0.75%   |
| Supermicro          | 1        | 0.37%   |
| Soyo                | 1        | 0.37%   |
| SIEMENS             | 1        | 0.37%   |
| Positivo            | 1        | 0.37%   |
| NZXT                | 1        | 0.37%   |
| Medion              | 1        | 0.37%   |
| ECS                 | 1        | 0.37%   |
| Biostar             | 1        | 0.37%   |
| BESSTAR Tech        | 1        | 0.37%   |
| AZW                 | 1        | 0.37%   |
| Apple               | 1        | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Gigabyte X570 AORUS ELITE                          | 5        | 1.87%   |
| ASUS All Series                                    | 5        | 1.87%   |
| Gigabyte B450 AORUS M                              | 4        | 1.49%   |
| Dell OptiPlex 3020                                 | 3        | 1.12%   |
| ASUS ROG STRIX B450-F GAMING                       | 3        | 1.12%   |
| ASUS ROG CROSSHAIR VIII DARK HERO                  | 3        | 1.12%   |
| ASUS PRIME B450M-A                                 | 3        | 1.12%   |
| Unknown                                            | 3        | 1.12%   |
| System76 Thelio                                    | 2        | 0.75%   |
| MSI MS-7D32                                        | 2        | 0.75%   |
| MSI MS-7C37                                        | 2        | 0.75%   |
| MSI MS-7C35                                        | 2        | 0.75%   |
| MSI MS-7C02                                        | 2        | 0.75%   |
| HP ProDesk 600 G1 SFF                              | 2        | 0.75%   |
| Gigabyte Z170-HD3P                                 | 2        | 0.75%   |
| Gigabyte Z170-Gaming K3                            | 2        | 0.75%   |
| Gigabyte X570 I AORUS PRO WIFI                     | 2        | 0.75%   |
| Gigabyte X570 AORUS MASTER                         | 2        | 0.75%   |
| Gigabyte B450M DS3H                                | 2        | 0.75%   |
| Gigabyte AB350-Gaming 3                            | 2        | 0.75%   |
| ASUS TUF Gaming B550-PLUS                          | 2        | 0.75%   |
| ASUS ROG STRIX B550-I GAMING                       | 2        | 0.75%   |
| ASUS ROG STRIX B450-I GAMING                       | 2        | 0.75%   |
| ASUS ROG Maximus XI HERO                           | 2        | 0.75%   |
| ASUS ROG CROSSHAIR VIII HERO                       | 2        | 0.75%   |
| ASUS PRIME Z390-A                                  | 2        | 0.75%   |
| ASUS P6X58D PREMIUM                                | 2        | 0.75%   |
| ASRock B450 Gaming K4                              | 2        | 0.75%   |
| Alienware Aurora R8                                | 2        | 0.75%   |
| System76 Thelio Major                              | 1        | 0.37%   |
| Supermicro X8SIL                                   | 1        | 0.37%   |
| Soyo SY-A68M FS V2.0                               | 1        | 0.37%   |
| SIEMENS SIMATIC BOX PC 627B/PANEL PC 677B Profibus | 1        | 0.37%   |
| Positivo POS-MI945AA                               | 1        | 0.37%   |
| NZXT N7 B550                                       | 1        | 0.37%   |
| MSI MS-7D54                                        | 1        | 0.37%   |
| MSI MS-7D28                                        | 1        | 0.37%   |
| MSI MS-7D25                                        | 1        | 0.37%   |
| MSI MS-7D09                                        | 1        | 0.37%   |
| MSI MS-7C96                                        | 1        | 0.37%   |
| MSI MS-7C91                                        | 1        | 0.37%   |
| MSI MS-7C75                                        | 1        | 0.37%   |
| MSI MS-7C56                                        | 1        | 0.37%   |
| MSI MS-7B89                                        | 1        | 0.37%   |
| MSI MS-7B87                                        | 1        | 0.37%   |
| MSI MS-7B86                                        | 1        | 0.37%   |
| MSI MS-7B85                                        | 1        | 0.37%   |
| MSI MS-7B17                                        | 1        | 0.37%   |
| MSI MS-7B12                                        | 1        | 0.37%   |
| MSI MS-7A74                                        | 1        | 0.37%   |
| MSI MS-7A71                                        | 1        | 0.37%   |
| MSI MS-7A70                                        | 1        | 0.37%   |
| MSI MS-7A40                                        | 1        | 0.37%   |
| MSI MS-7A38                                        | 1        | 0.37%   |
| MSI MS-7A37                                        | 1        | 0.37%   |
| MSI MS-7A34                                        | 1        | 0.37%   |
| MSI MS-7A32                                        | 1        | 0.37%   |
| MSI MS-7A16                                        | 1        | 0.37%   |
| MSI MS-7A11                                        | 1        | 0.37%   |
| MSI MS-7977                                        | 1        | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 25       | 9.33%   |
| ASUS PRIME            | 16       | 5.97%   |
| Gigabyte X570         | 10       | 3.73%   |
| Dell OptiPlex         | 9        | 3.36%   |
| ASUS TUF              | 8        | 2.99%   |
| Lenovo ThinkCentre    | 6        | 2.24%   |
| Dell Precision        | 6        | 2.24%   |
| Gigabyte B450         | 5        | 1.87%   |
| ASUS All              | 5        | 1.87%   |
| Dell Inspiron         | 4        | 1.49%   |
| ASRock B450           | 4        | 1.49%   |
| Alienware Aurora      | 4        | 1.49%   |
| System76 Thelio       | 3        | 1.12%   |
| HP EliteDesk          | 3        | 1.12%   |
| HP Compaq             | 3        | 1.12%   |
| Gigabyte B550         | 3        | 1.12%   |
| Gigabyte B450M        | 3        | 1.12%   |
| Gigabyte AB350-Gaming | 3        | 1.12%   |
| Unknown               | 3        | 1.12%   |
| MSI MS-7D32           | 2        | 0.75%   |
| MSI MS-7C37           | 2        | 0.75%   |
| MSI MS-7C35           | 2        | 0.75%   |
| MSI MS-7C02           | 2        | 0.75%   |
| HP ProDesk            | 2        | 0.75%   |
| Gigabyte Z390         | 2        | 0.75%   |
| Gigabyte Z170-HD3P    | 2        | 0.75%   |
| Gigabyte Z170-Gaming  | 2        | 0.75%   |
| Gigabyte X470         | 2        | 0.75%   |
| Gigabyte H310M        | 2        | 0.75%   |
| Fujitsu ESPRIMO       | 2        | 0.75%   |
| Dell XPS              | 2        | 0.75%   |
| ASUS P6X58D           | 2        | 0.75%   |
| ASRock Z390           | 2        | 0.75%   |
| ASRock B550           | 2        | 0.75%   |
| Supermicro X8SIL      | 1        | 0.37%   |
| Soyo SY-A68M          | 1        | 0.37%   |
| SIEMENS SIMATIC       | 1        | 0.37%   |
| Positivo POS-MI945AA  | 1        | 0.37%   |
| NZXT N7               | 1        | 0.37%   |
| MSI MS-7D54           | 1        | 0.37%   |
| MSI MS-7D28           | 1        | 0.37%   |
| MSI MS-7D25           | 1        | 0.37%   |
| MSI MS-7D09           | 1        | 0.37%   |
| MSI MS-7C96           | 1        | 0.37%   |
| MSI MS-7C91           | 1        | 0.37%   |
| MSI MS-7C75           | 1        | 0.37%   |
| MSI MS-7C56           | 1        | 0.37%   |
| MSI MS-7B89           | 1        | 0.37%   |
| MSI MS-7B87           | 1        | 0.37%   |
| MSI MS-7B86           | 1        | 0.37%   |
| MSI MS-7B85           | 1        | 0.37%   |
| MSI MS-7B17           | 1        | 0.37%   |
| MSI MS-7B12           | 1        | 0.37%   |
| MSI MS-7A74           | 1        | 0.37%   |
| MSI MS-7A71           | 1        | 0.37%   |
| MSI MS-7A70           | 1        | 0.37%   |
| MSI MS-7A40           | 1        | 0.37%   |
| MSI MS-7A38           | 1        | 0.37%   |
| MSI MS-7A37           | 1        | 0.37%   |
| MSI MS-7A34           | 1        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 46       | 17.16%  |
| 2019 | 36       | 13.43%  |
| 2021 | 29       | 10.82%  |
| 2020 | 28       | 10.45%  |
| 2017 | 16       | 5.97%   |
| 2011 | 15       | 5.6%    |
| 2016 | 14       | 5.22%   |
| 2014 | 14       | 5.22%   |
| 2013 | 14       | 5.22%   |
| 2015 | 12       | 4.48%   |
| 2012 | 12       | 4.48%   |
| 2010 | 9        | 3.36%   |
| 2009 | 8        | 2.99%   |
| 2022 | 7        | 2.61%   |
| 2008 | 5        | 1.87%   |
| 2007 | 2        | 0.75%   |
| 2006 | 1        | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 268      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 267      | 99.63%  |
| Enabled  | 1        | 0.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 268      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 88       | 32.59%  |
| 32.01-64.0      | 72       | 26.67%  |
| 8.01-16.0       | 38       | 14.07%  |
| 64.01-256.0     | 26       | 9.63%   |
| 4.01-8.0        | 23       | 8.52%   |
| 3.01-4.0        | 16       | 5.93%   |
| 24.01-32.0      | 4        | 1.48%   |
| More than 256.0 | 2        | 0.74%   |
| 1.01-2.0        | 1        | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 85       | 30.14%  |
| 4.01-8.0   | 78       | 27.66%  |
| 3.01-4.0   | 65       | 23.05%  |
| 1.01-2.0   | 34       | 12.06%  |
| 8.01-16.0  | 13       | 4.61%   |
| 16.01-24.0 | 4        | 1.42%   |
| 32.01-64.0 | 3        | 1.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 100      | 37.04%  |
| 1      | 68       | 25.19%  |
| 3      | 56       | 20.74%  |
| 4      | 19       | 7.04%   |
| 5      | 11       | 4.07%   |
| 6      | 10       | 3.7%    |
| 7      | 3        | 1.11%   |
| 11     | 1        | 0.37%   |
| 10     | 1        | 0.37%   |
| 9      | 1        | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 184      | 68.66%  |
| Yes       | 84       | 31.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 264      | 98.51%  |
| No        | 4        | 1.49%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 151      | 56.34%  |
| No        | 117      | 43.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 156      | 57.99%  |
| Yes       | 113      | 42.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| USA                | 108      | 40.15%  |
| Canada             | 16       | 5.95%   |
| Brazil             | 15       | 5.58%   |
| Germany            | 14       | 5.2%    |
| UK                 | 10       | 3.72%   |
| Australia          | 10       | 3.72%   |
| Netherlands        | 9        | 3.35%   |
| France             | 8        | 2.97%   |
| Sweden             | 5        | 1.86%   |
| Austria            | 5        | 1.86%   |
| Switzerland        | 4        | 1.49%   |
| Poland             | 4        | 1.49%   |
| Norway             | 4        | 1.49%   |
| Italy              | 4        | 1.49%   |
| Ireland            | 4        | 1.49%   |
| Spain              | 3        | 1.12%   |
| Mexico             | 3        | 1.12%   |
| Japan              | 3        | 1.12%   |
| Chile              | 3        | 1.12%   |
| Thailand           | 2        | 0.74%   |
| South Africa       | 2        | 0.74%   |
| Russia             | 2        | 0.74%   |
| India              | 2        | 0.74%   |
| Hong Kong          | 2        | 0.74%   |
| Greece             | 2        | 0.74%   |
| Finland            | 2        | 0.74%   |
| Czechia            | 2        | 0.74%   |
| Belgium            | 2        | 0.74%   |
| Uruguay            | 1        | 0.37%   |
| Turkey             | 1        | 0.37%   |
| Tunisia            | 1        | 0.37%   |
| South Korea        | 1        | 0.37%   |
| Slovakia           | 1        | 0.37%   |
| Saudi Arabia       | 1        | 0.37%   |
| Romania            | 1        | 0.37%   |
| Portugal           | 1        | 0.37%   |
| Philippines        | 1        | 0.37%   |
| Nicaragua          | 1        | 0.37%   |
| Lithuania          | 1        | 0.37%   |
| Jordan             | 1        | 0.37%   |
| Israel             | 1        | 0.37%   |
| Hungary            | 1        | 0.37%   |
| Dominican Republic | 1        | 0.37%   |
| Denmark            | 1        | 0.37%   |
| Colombia           | 1        | 0.37%   |
| Azerbaijan         | 1        | 0.37%   |
| Argentina          | 1        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Vienna            | 3        | 1.11%   |
| Zurich            | 2        | 0.74%   |
| Sydney            | 2        | 0.74%   |
| Springfield       | 2        | 0.74%   |
| Seattle           | 2        | 0.74%   |
| Sapporo           | 2        | 0.74%   |
| Sao Paulo         | 2        | 0.74%   |
| San Francisco     | 2        | 0.74%   |
| Richmond          | 2        | 0.74%   |
| Ogden             | 2        | 0.74%   |
| Mannheim          | 2        | 0.74%   |
| Goiânia          | 2        | 0.74%   |
| Dublin            | 2        | 0.74%   |
| Cleveland         | 2        | 0.74%   |
| Chicago           | 2        | 0.74%   |
| Broomfield        | 2        | 0.74%   |
| Brisbane          | 2        | 0.74%   |
| Berlin            | 2        | 0.74%   |
| Bedford           | 2        | 0.74%   |
| Atlanta           | 2        | 0.74%   |
| Żyrardów        | 1        | 0.37%   |
| Zaragoza          | 1        | 0.37%   |
| Zapopan           | 1        | 0.37%   |
| Yekaterinburg     | 1        | 0.37%   |
| Woodstock         | 1        | 0.37%   |
| Winter Garden     | 1        | 0.37%   |
| Wilmslow          | 1        | 0.37%   |
| Wichita           | 1        | 0.37%   |
| Weston-super-Mare | 1        | 0.37%   |
| Westland          | 1        | 0.37%   |
| Weimar            | 1        | 0.37%   |
| Wausau            | 1        | 0.37%   |
| Wasilla           | 1        | 0.37%   |
| Walker            | 1        | 0.37%   |
| Virginia Beach    | 1        | 0.37%   |
| Vilnius           | 1        | 0.37%   |
| Vicksburg         | 1        | 0.37%   |
| Ventura           | 1        | 0.37%   |
| Vedevag           | 1        | 0.37%   |
| Västerås        | 1        | 0.37%   |
| Varel             | 1        | 0.37%   |
| Valparaiso        | 1        | 0.37%   |
| Vallenar          | 1        | 0.37%   |
| Utrecht           | 1        | 0.37%   |
| Union             | 1        | 0.37%   |
| Turku             | 1        | 0.37%   |
| Tunis             | 1        | 0.37%   |
| Tuen Mun          | 1        | 0.37%   |
| Tucson            | 1        | 0.37%   |
| Tuam              | 1        | 0.37%   |
| Trondheim         | 1        | 0.37%   |
| Toronto           | 1        | 0.37%   |
| Thessaloniki      | 1        | 0.37%   |
| Theilingen        | 1        | 0.37%   |
| Telford           | 1        | 0.37%   |
| Taunton           | 1        | 0.37%   |
| Tarlac City       | 1        | 0.37%   |
| Tahlequah         | 1        | 0.37%   |
| Swannanoa         | 1        | 0.37%   |
| Surrey            | 1        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 105      | 148    | 19.16%  |
| Samsung Electronics       | 102      | 144    | 18.61%  |
| WDC                       | 78       | 112    | 14.23%  |
| SanDisk                   | 34       | 42     | 6.2%    |
| Crucial                   | 33       | 48     | 6.02%   |
| Toshiba                   | 27       | 30     | 4.93%   |
| Kingston                  | 24       | 31     | 4.38%   |
| Phison                    | 15       | 20     | 2.74%   |
| Hitachi                   | 15       | 21     | 2.74%   |
| Intel                     | 11       | 12     | 2.01%   |
| A-DATA Technology         | 11       | 12     | 2.01%   |
| Silicon Motion            | 7        | 10     | 1.28%   |
| SPCC                      | 6        | 8      | 1.09%   |
| Micron/Crucial Technology | 6        | 8      | 1.09%   |
| Micron Technology         | 6        | 7      | 1.09%   |
| China                     | 6        | 7      | 1.09%   |
| SK hynix                  | 5        | 5      | 0.91%   |
| Hewlett-Packard           | 4        | 4      | 0.73%   |
| PNY                       | 3        | 3      | 0.55%   |
| OCZ                       | 3        | 3      | 0.55%   |
| Lexar                     | 3        | 3      | 0.55%   |
| Intenso                   | 3        | 3      | 0.55%   |
| XPG                       | 2        | 2      | 0.36%   |
| Unknown                   | 2        | 2      | 0.36%   |
| Patriot                   | 2        | 2      | 0.36%   |
| Mushkin                   | 2        | 3      | 0.36%   |
| Maxtor                    | 2        | 2      | 0.36%   |
| JMicron Technology        | 2        | 2      | 0.36%   |
| HGST                      | 2        | 2      | 0.36%   |
| Fujitsu                   | 2        | 3      | 0.36%   |
| Corsair                   | 2        | 3      | 0.36%   |
| Apple                     | 2        | 2      | 0.36%   |
| WALRAM                    | 1        | 1      | 0.18%   |
| TurXun                    | 1        | 1      | 0.18%   |
| Transcend                 | 1        | 2      | 0.18%   |
| TO Exter                  | 1        | 1      | 0.18%   |
| T-FORCE                   | 1        | 2      | 0.18%   |
| Realtek Semiconductor     | 1        | 1      | 0.18%   |
| Qunion                    | 1        | 2      | 0.18%   |
| PNY USB                   | 1        | 1      | 0.18%   |
| MaxDigital                | 1        | 1      | 0.18%   |
| Mass                      | 1        | 1      | 0.18%   |
| LITEON                    | 1        | 1      | 0.18%   |
| KingFast                  | 1        | 1      | 0.18%   |
| Indilinx                  | 1        | 1      | 0.18%   |
| HS-SSD-E100N              | 1        | 1      | 0.18%   |
| HS-SSD-C100               | 1        | 2      | 0.18%   |
| Gigabyte Technology       | 1        | 1      | 0.18%   |
| GALAX                     | 1        | 1      | 0.18%   |
| FORESEE                   | 1        | 2      | 0.18%   |
| ASMT                      | 1        | 1      | 0.18%   |
| Apacer                    | 1        | 1      | 0.18%   |
| Unknown                   | 1        | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB          | 18       | 2.78%   |
| Seagate ST2000DM008-2FR102 2TB      | 16       | 2.47%   |
| Samsung NVMe SSD Drive 500GB        | 14       | 2.16%   |
| SanDisk NVMe SSD Drive 1TB          | 12       | 1.85%   |
| WDC WD10EZEX-08WN4A0 1TB            | 7        | 1.08%   |
| Seagate ST4000DM004-2CV104 4TB      | 7        | 1.08%   |
| Samsung SSD 860 EVO 1TB             | 7        | 1.08%   |
| Samsung SSD 850 EVO 250GB           | 7        | 1.08%   |
| Samsung NVMe SSD Drive 2TB          | 7        | 1.08%   |
| Phison NVMe SSD Drive 1TB           | 7        | 1.08%   |
| Crucial CT1000MX500SSD1 1TB         | 7        | 1.08%   |
| Seagate ST500DM002-1BD142 500GB     | 6        | 0.93%   |
| Seagate ST1000DM010-2EP102 1TB      | 6        | 0.93%   |
| Seagate ST1000DM003-1CH162 1TB      | 6        | 0.93%   |
| Samsung SSD 850 EVO 500GB           | 6        | 0.93%   |
| Kingston SA400S37240G 240GB SSD     | 6        | 0.93%   |
| Crucial CT2000MX500SSD1 2TB         | 6        | 0.93%   |
| Samsung SSD 970 EVO Plus 1TB        | 5        | 0.77%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 4        | 0.62%   |
| WDC WD30EFRX-68EUZN0 3TB            | 4        | 0.62%   |
| Toshiba HDWD120 2TB                 | 4        | 0.62%   |
| Toshiba DT01ACA200 2TB              | 4        | 0.62%   |
| Toshiba DT01ACA100 1TB              | 4        | 0.62%   |
| Seagate ST31000528AS 1TB            | 4        | 0.62%   |
| Seagate ST2000DM001-1ER164 2TB      | 4        | 0.62%   |
| Seagate Expansion 1TB               | 4        | 0.62%   |
| SanDisk NVMe SSD Drive 500GB        | 4        | 0.62%   |
| Samsung SSD 860 EVO 500GB           | 4        | 0.62%   |
| Phison NVMe SSD Drive 2TB           | 4        | 0.62%   |
| Micron/Crucial NVMe SSD Drive 1TB   | 4        | 0.62%   |
| Kingston SV300S37A120G 120GB SSD    | 4        | 0.62%   |
| Kingston SA400S37120G 120GB SSD     | 4        | 0.62%   |
| WDC WDS100T3X0C-00SJG0 1TB          | 3        | 0.46%   |
| WDC WD20EZAZ-00GGJB0 2TB            | 3        | 0.46%   |
| WDC WD20EARS-00MVWB0 2TB            | 3        | 0.46%   |
| Seagate ST8000DM004-2CX188 8TB      | 3        | 0.46%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 0.46%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 0.46%   |
| Seagate ST3500418AS 500GB           | 3        | 0.46%   |
| Seagate ST31000524AS 1TB            | 3        | 0.46%   |
| Seagate ST2000DX002-2DV164 2TB      | 3        | 0.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3        | 0.46%   |
| Seagate ST1000DM003-1SB10C 1TB      | 3        | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB      | 3        | 0.46%   |
| SanDisk NVMe SSD Drive 512GB        | 3        | 0.46%   |
| Samsung SSD 970 EVO 500GB           | 3        | 0.46%   |
| Intel NVMe SSD Drive 512GB          | 3        | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2        | 0.31%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 2        | 0.31%   |
| WDC WD30EZRZ-00GXCB0 3TB            | 2        | 0.31%   |
| WDC WD20EZRX-00D8PB0 2TB            | 2        | 0.31%   |
| WDC WD20EFRX-68AX9N0 2TB            | 2        | 0.31%   |
| WDC WD10EZEX-08M2NA0 1TB            | 2        | 0.31%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2        | 0.31%   |
| WDC WD10EZEX-00BN5A0 1TB            | 2        | 0.31%   |
| WDC WD10EALX-009BA0 1TB             | 2        | 0.31%   |
| Toshiba HDWD110 1TB                 | 2        | 0.31%   |
| SPCC Solid State Disk 512GB         | 2        | 0.31%   |
| Silicon Motion NVMe SSD Drive 480GB | 2        | 0.31%   |
| Silicon Motion NVMe SSD Drive 1TB   | 2        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 100      | 140    | 45.25%  |
| WDC                 | 64       | 88     | 28.96%  |
| Toshiba             | 25       | 28     | 11.31%  |
| Hitachi             | 15       | 21     | 6.79%   |
| Samsung Electronics | 10       | 13     | 4.52%   |
| HGST                | 2        | 2      | 0.9%    |
| Apple               | 2        | 2      | 0.9%    |
| Unknown             | 1        | 1      | 0.45%   |
| Maxtor              | 1        | 1      | 0.45%   |
| Fujitsu             | 1        | 2      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 43       | 60     | 24.16%  |
| Crucial             | 29       | 44     | 16.29%  |
| Kingston            | 22       | 27     | 12.36%  |
| WDC                 | 13       | 17     | 7.3%    |
| SanDisk             | 12       | 15     | 6.74%   |
| A-DATA Technology   | 9        | 10     | 5.06%   |
| China               | 6        | 7      | 3.37%   |
| Intel               | 5        | 5      | 2.81%   |
| SPCC                | 4        | 5      | 2.25%   |
| SK hynix            | 3        | 3      | 1.69%   |
| PNY                 | 3        | 3      | 1.69%   |
| OCZ                 | 3        | 3      | 1.69%   |
| Lexar               | 3        | 3      | 1.69%   |
| Hewlett-Packard     | 3        | 3      | 1.69%   |
| Patriot             | 2        | 2      | 1.12%   |
| Mushkin             | 2        | 3      | 1.12%   |
| Micron Technology   | 2        | 2      | 1.12%   |
| Transcend           | 1        | 2      | 0.56%   |
| Toshiba             | 1        | 1      | 0.56%   |
| TO Exter            | 1        | 1      | 0.56%   |
| Seagate             | 1        | 1      | 0.56%   |
| PNY USB             | 1        | 1      | 0.56%   |
| Maxtor              | 1        | 1      | 0.56%   |
| Intenso             | 1        | 1      | 0.56%   |
| HS-SSD-E100N        | 1        | 1      | 0.56%   |
| Gigabyte Technology | 1        | 1      | 0.56%   |
| Fujitsu             | 1        | 1      | 0.56%   |
| FORESEE             | 1        | 2      | 0.56%   |
| Corsair             | 1        | 2      | 0.56%   |
| ASMT                | 1        | 1      | 0.56%   |
| Apacer              | 1        | 1      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 173      | 298    | 38.02%  |
| SSD     | 147      | 229    | 32.31%  |
| NVMe    | 117      | 183    | 25.71%  |
| Unknown | 17       | 19     | 3.74%   |
| MMC     | 1        | 1      | 0.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 235      | 516    | 62.17%  |
| NVMe | 117      | 182    | 30.95%  |
| SAS  | 25       | 31     | 6.61%   |
| MMC  | 1        | 1      | 0.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 148      | 217    | 38.95%  |
| 0.51-1.0   | 109      | 161    | 28.68%  |
| 1.01-2.0   | 76       | 88     | 20%     |
| 3.01-4.0   | 21       | 26     | 5.53%   |
| 2.01-3.0   | 14       | 17     | 3.68%   |
| 4.01-10.0  | 11       | 15     | 2.89%   |
| 10.01-20.0 | 1        | 3      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 54       | 19.71%  |
| 251-500        | 51       | 18.61%  |
| 1001-2000      | 48       | 17.52%  |
| 101-250        | 43       | 15.69%  |
| More than 3000 | 39       | 14.23%  |
| 2001-3000      | 16       | 5.84%   |
| 1-20           | 10       | 3.65%   |
| 51-100         | 6        | 2.19%   |
| 21-50          | 4        | 1.46%   |
| Unknown        | 3        | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 66       | 23.83%  |
| 21-50          | 45       | 16.25%  |
| 101-250        | 37       | 13.36%  |
| 51-100         | 34       | 12.27%  |
| 251-500        | 33       | 11.91%  |
| 1001-2000      | 19       | 6.86%   |
| 501-1000       | 18       | 6.5%    |
| More than 3000 | 16       | 5.78%   |
| 2001-3000      | 6        | 2.17%   |
| Unknown        | 3        | 1.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5001AALS-00J7B1 500GB           | 1        | 1      | 8.33%   |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 1      | 8.33%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1        | 1      | 8.33%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1        | 1      | 8.33%   |
| WDC WD1001FALS-00E8B0 1TB             | 1        | 1      | 8.33%   |
| Seagate ST5000LM000-2AN170 5TB        | 1        | 1      | 8.33%   |
| Seagate ST2000DM008-2FR102 2TB        | 1        | 1      | 8.33%   |
| Samsung Electronics SSD 850 PRO 256GB | 1        | 1      | 8.33%   |
| Kingston SV300S37A240G 240GB SSD      | 1        | 1      | 8.33%   |
| Hitachi HDP725050GLA360 500GB         | 1        | 1      | 8.33%   |
| Crucial CT525MX300SSD1 528GB          | 1        | 1      | 8.33%   |
| A-DATA Technology SU800 512GB SSD     | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 41.67%  |
| Seagate             | 2        | 2      | 16.67%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |
| Crucial             | 1        | 1      | 8.33%   |
| A-DATA Technology   | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 5      | 62.5%   |
| Seagate | 2        | 2      | 25%     |
| Hitachi | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 8      | 66.67%  |
| SSD  | 4        | 4      | 33.33%  |

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
| Detected | 230      | 614    | 79.86%  |
| Works    | 47       | 104    | 16.32%  |
| Malfunc  | 11       | 12     | 3.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 149      | 33.94%  |
| AMD                          | 121      | 27.56%  |
| Samsung Electronics          | 61       | 13.9%   |
| SanDisk                      | 24       | 5.47%   |
| Phison Electronics           | 19       | 4.33%   |
| ASMedia Technology           | 13       | 2.96%   |
| Silicon Motion               | 9        | 2.05%   |
| Micron/Crucial Technology    | 9        | 2.05%   |
| Marvell Technology Group     | 6        | 1.37%   |
| Micron Technology            | 4        | 0.91%   |
| Seagate Technology           | 3        | 0.68%   |
| Kingston Technology Company  | 3        | 0.68%   |
| JMicron Technology           | 3        | 0.68%   |
| ADATA Technology             | 3        | 0.68%   |
| SK hynix                     | 2        | 0.46%   |
| Realtek Semiconductor        | 2        | 0.46%   |
| Nvidia                       | 2        | 0.46%   |
| VIA Technologies             | 1        | 0.23%   |
| Toshiba America Info Systems | 1        | 0.23%   |
| Silicon Image                | 1        | 0.23%   |
| LSI Logic / Symbios Logic    | 1        | 0.23%   |
| Lite-On Technology           | 1        | 0.23%   |
| Broadcom / LSI               | 1        | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 80       | 15.07%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 37       | 6.97%   |
| AMD 400 Series Chipset SATA Controller                                                  | 36       | 6.78%   |
| AMD 500 Series Chipset SATA Controller                                                  | 20       | 3.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 16       | 3.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16       | 3.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 15       | 2.82%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 12       | 2.26%   |
| Intel SATA Controller [RAID mode]                                                       | 11       | 2.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 2.07%   |
| Phison E12 NVMe Controller                                                              | 10       | 1.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 1.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 1.51%   |
| Samsung NVMe SSD Controller 980                                                         | 7        | 1.32%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 7        | 1.32%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 6        | 1.13%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 6        | 1.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.13%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 6        | 1.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 1.13%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 1.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5        | 0.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 5        | 0.94%   |
| SanDisk Non-Volatile memory controller                                                  | 5        | 0.94%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 0.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 0.94%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 4        | 0.75%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 4        | 0.75%   |
| Micron Non-Volatile memory controller                                                   | 4        | 0.75%   |
| Intel SSD 660P Series                                                                   | 4        | 0.75%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.75%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.56%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 0.56%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3        | 0.56%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.56%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 0.56%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.56%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 0.56%   |
| Seagate FireCuda 530 SSD                                                                | 2        | 0.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.38%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 2        | 0.38%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 0.38%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 2        | 0.38%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.38%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.38%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.38%   |
| Micron/Crucial NVMe Controller                                                          | 2        | 0.38%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 2        | 0.38%   |
| JMicron JMB361 AHCI/IDE                                                                 | 2        | 0.38%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.38%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.38%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.38%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 0.38%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 230      | 56.23%  |
| NVMe | 118      | 28.85%  |
| IDE  | 39       | 9.54%   |
| RAID | 20       | 4.89%   |
| SAS  | 2        | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 145      | 54.1%   |
| AMD    | 123      | 45.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 16       | 5.97%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 10       | 3.73%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 8        | 2.99%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 7        | 2.61%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 7        | 2.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 6        | 2.24%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 6        | 2.24%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 5        | 1.87%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4        | 1.49%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 4        | 1.49%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 1.49%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 4        | 1.49%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 1.49%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 1.49%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 1.49%   |
| AMD FX-8350 Eight-Core Processor            | 4        | 1.49%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 1.12%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 1.12%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.12%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.12%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 1.12%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 3        | 1.12%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 1.12%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 1.12%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 3        | 1.12%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 1.12%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 3        | 1.12%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3        | 1.12%   |
| Intel Core i9-10900X CPU @ 3.70GHz          | 2        | 0.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.75%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.75%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.75%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 2        | 0.75%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.75%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.75%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.75%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.75%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 2        | 0.75%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 0.75%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 0.75%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 2        | 0.75%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.75%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 2        | 0.75%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 2        | 0.75%   |
| Intel 12th Gen Core i9-12900K               | 2        | 0.75%   |
| Intel 12th Gen Core i5-12600K               | 2        | 0.75%   |
| AMD Ryzen 7 1800X Eight-Core Processor      | 2        | 0.75%   |
| AMD Ryzen 5 3500 6-Core Processor           | 2        | 0.75%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 0.75%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 0.75%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 0.75%   |
| AMD FX-6300 Six-Core Processor              | 2        | 0.75%   |
| Intel Xeon E-2146G CPU @ 3.50GHz            | 1        | 0.37%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 0.37%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1        | 0.37%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 0.37%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.37%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 1        | 0.37%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 45       | 16.79%  |
| Intel Core i7           | 44       | 16.42%  |
| Intel Core i5           | 40       | 14.93%  |
| AMD Ryzen 7             | 30       | 11.19%  |
| AMD Ryzen 9             | 23       | 8.58%   |
| Intel Core i3           | 12       | 4.48%   |
| Other                   | 11       | 4.1%    |
| Intel Xeon              | 11       | 4.1%    |
| Intel Core i9           | 8        | 2.99%   |
| AMD FX                  | 7        | 2.61%   |
| Intel Core 2 Quad       | 5        | 1.87%   |
| Intel Pentium           | 3        | 1.12%   |
| Intel Celeron           | 3        | 1.12%   |
| AMD Ryzen Threadripper  | 3        | 1.12%   |
| Intel Pentium Gold      | 2        | 0.75%   |
| Intel Core 2            | 2        | 0.75%   |
| AMD Ryzen 3             | 2        | 0.75%   |
| AMD Phenom              | 2        | 0.75%   |
| AMD A8                  | 2        | 0.75%   |
| Intel Pentium Dual-Core | 1        | 0.37%   |
| Intel Pentium Dual      | 1        | 0.37%   |
| Intel Pentium D         | 1        | 0.37%   |
| Intel Core 2 Duo        | 1        | 0.37%   |
| AMD Sempron             | 1        | 0.37%   |
| AMD PRO A10             | 1        | 0.37%   |
| AMD Phenom II X6        | 1        | 0.37%   |
| AMD Phenom II X4        | 1        | 0.37%   |
| AMD Phenom II X3        | 1        | 0.37%   |
| AMD Athlon II X4        | 1        | 0.37%   |
| AMD Athlon II X2        | 1        | 0.37%   |
| AMD A6                  | 1        | 0.37%   |
| AMD A10                 | 1        | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 89       | 33.21%  |
| 6      | 63       | 23.51%  |
| 8      | 43       | 16.04%  |
| 2      | 29       | 10.82%  |
| 12     | 16       | 5.97%   |
| 16     | 13       | 4.85%   |
| 10     | 6        | 2.24%   |
| 3      | 4        | 1.49%   |
| 32     | 2        | 0.75%   |
| 24     | 1        | 0.37%   |
| 14     | 1        | 0.37%   |
| 1      | 1        | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 265      | 98.88%  |
| 2      | 3        | 1.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 191      | 71.27%  |
| 1      | 77       | 28.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 268      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 223      | 83.21%  |
| 0x08701021 | 7        | 2.61%   |
| 0x0800820d | 6        | 2.24%   |
| 0x906ec    | 3        | 1.12%   |
| 0x206a7    | 3        | 1.12%   |
| 0x906ea    | 2        | 0.75%   |
| 0x906e9    | 2        | 0.75%   |
| 0x90672    | 2        | 0.75%   |
| 0x506e3    | 2        | 0.75%   |
| 0x0a201016 | 2        | 0.75%   |
| 0x08001138 | 2        | 0.75%   |
| 0x08001137 | 2        | 0.75%   |
| 0xa0655    | 1        | 0.37%   |
| 0xa0653    | 1        | 0.37%   |
| 0x50657    | 1        | 0.37%   |
| 0x306c3    | 1        | 0.37%   |
| 0x0a201006 | 1        | 0.37%   |
| 0x08701013 | 1        | 0.37%   |
| 0x08301039 | 1        | 0.37%   |
| 0x08108109 | 1        | 0.37%   |
| 0x08101016 | 1        | 0.37%   |
| 0x0600611a | 1        | 0.37%   |
| 0x06003106 | 1        | 0.37%   |
| 0x06000852 | 1        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 39       | 14.55%  |
| Zen 2            | 38       | 14.18%  |
| KabyLake         | 30       | 11.19%  |
| Haswell          | 21       | 7.84%   |
| Skylake          | 18       | 6.72%   |
| Zen+             | 16       | 5.97%   |
| SandyBridge      | 15       | 5.6%    |
| IvyBridge        | 15       | 5.6%    |
| Zen              | 10       | 3.73%   |
| CometLake        | 9        | 3.36%   |
| Unknown          | 9        | 3.36%   |
| Piledriver       | 8        | 2.99%   |
| Penryn           | 7        | 2.61%   |
| Nehalem          | 7        | 2.61%   |
| K10              | 7        | 2.61%   |
| Core             | 4        | 1.49%   |
| Westmere         | 3        | 1.12%   |
| Steamroller      | 2        | 0.75%   |
| Excavator        | 2        | 0.75%   |
| Broadwell        | 2        | 0.75%   |
| Alderlake Hybrid | 2        | 0.75%   |
| Silvermont       | 1        | 0.37%   |
| NetBurst         | 1        | 0.37%   |
| Jaguar           | 1        | 0.37%   |
| Goldmont         | 1        | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 144      | 50%     |
| AMD                        | 99       | 34.38%  |
| Intel                      | 44       | 15.28%  |
| Matrox Electronics Systems | 1        | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 13       | 4.36%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 9        | 3.02%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 8        | 2.68%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 8        | 2.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 7        | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 2.35%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 7        | 2.35%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 2.01%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 6        | 2.01%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 5        | 1.68%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 1.68%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 5        | 1.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.68%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 1.68%   |
| AMD Cezanne                                                                 | 5        | 1.68%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 1.34%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 4        | 1.34%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.34%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 1.34%   |
| Intel AlderLake-S GT1                                                       | 4        | 1.34%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 1.34%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 1.01%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 3        | 1.01%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 3        | 1.01%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 1.01%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.01%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.01%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3        | 1.01%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 3        | 1.01%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 3        | 1.01%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 1.01%   |
| Intel HD Graphics 530                                                       | 3        | 1.01%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 1.01%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.01%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1.01%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.67%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 0.67%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.67%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.67%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 0.67%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 2        | 0.67%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 2        | 0.67%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 0.67%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 0.67%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 2        | 0.67%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 2        | 0.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 0.67%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 0.67%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 2        | 0.67%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 0.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 0.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 0.67%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 0.67%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 0.67%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2        | 0.67%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 0.67%   |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                      | 2        | 0.67%   |
| AMD Cypress XT [Radeon HD 5870]                                             | 2        | 0.67%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 134      | 49.08%  |
| 1 x AMD              | 91       | 33.33%  |
| 1 x Intel            | 28       | 10.26%  |
| 2 x Nvidia           | 5        | 1.83%   |
| Intel + Nvidia       | 4        | 1.47%   |
| 2 x AMD              | 3        | 1.1%    |
| Intel + AMD          | 3        | 1.1%    |
| Other                | 1        | 0.37%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.37%   |
| 1 x Matrox           | 1        | 0.37%   |
| AMD + 2 x Nvidia     | 1        | 0.37%   |
| AMD + Nvidia         | 1        | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 135      | 49.63%  |
| Proprietary | 127      | 46.69%  |
| Unknown     | 10       | 3.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 141      | 51.84%  |
| 7.01-8.0   | 34       | 12.5%   |
| 8.01-16.0  | 23       | 8.46%   |
| 3.01-4.0   | 21       | 7.72%   |
| 5.01-6.0   | 20       | 7.35%   |
| 1.01-2.0   | 18       | 6.62%   |
| 2.01-3.0   | 7        | 2.57%   |
| 0.51-1.0   | 3        | 1.1%    |
| 16.01-24.0 | 2        | 0.74%   |
| 0.01-0.5   | 2        | 0.74%   |
| 32.01-64.0 | 1        | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 56       | 18.36%  |
| Dell                 | 41       | 13.44%  |
| Goldstar             | 31       | 10.16%  |
| Hewlett-Packard      | 21       | 6.89%   |
| Ancor Communications | 19       | 6.23%   |
| AOC                  | 17       | 5.57%   |
| Acer                 | 17       | 5.57%   |
| BenQ                 | 16       | 5.25%   |
| ASUSTek Computer     | 13       | 4.26%   |
| Iiyama               | 6        | 1.97%   |
| NEC Computers        | 5        | 1.64%   |
| Gigabyte Technology  | 5        | 1.64%   |
| ViewSonic            | 4        | 1.31%   |
| Unknown              | 4        | 1.31%   |
| Sceptre Tech         | 4        | 1.31%   |
| MSI                  | 4        | 1.31%   |
| Lenovo               | 3        | 0.98%   |
| Viotek               | 2        | 0.66%   |
| Vestel Elektronik    | 2        | 0.66%   |
| ITE                  | 2        | 0.66%   |
| ___                  | 1        | 0.33%   |
| VOXICON              | 1        | 0.33%   |
| Vizio                | 1        | 0.33%   |
| Valve                | 1        | 0.33%   |
| Unknown (XXX)        | 1        | 0.33%   |
| Toshiba              | 1        | 0.33%   |
| STD                  | 1        | 0.33%   |
| SKY                  | 1        | 0.33%   |
| Sharp                | 1        | 0.33%   |
| RTK                  | 1        | 0.33%   |
| Positivo             | 1        | 0.33%   |
| Plain Tree Systems   | 1        | 0.33%   |
| Pixio                | 1        | 0.33%   |
| Pioneer              | 1        | 0.33%   |
| Philips              | 1        | 0.33%   |
| Orion                | 1        | 0.33%   |
| ONN                  | 1        | 0.33%   |
| Onkyo                | 1        | 0.33%   |
| OEM                  | 1        | 0.33%   |
| MiTAC                | 1        | 0.33%   |
| Mi                   | 1        | 0.33%   |
| Medion Akoya         | 1        | 0.33%   |
| LG Electronics       | 1        | 0.33%   |
| Impression           | 1        | 0.33%   |
| Huion                | 1        | 0.33%   |
| Hitachi              | 1        | 0.33%   |
| GVE                  | 1        | 0.33%   |
| GDH                  | 1        | 0.33%   |
| G-Story              | 1        | 0.33%   |
| Fujitsu Siemens      | 1        | 0.33%   |
| Eizo                 | 1        | 0.33%   |
| CVT                  | 1        | 0.33%   |
| AU Optronics         | 1        | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4        | 1.26%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch          | 3        | 0.94%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 3        | 0.94%   |
| Vestel Elektronik 39FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 2        | 0.63%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2        | 0.63%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 520x290mm 23.4-inch     | 2        | 0.63%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 2        | 0.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2        | 0.63%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2        | 0.63%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 800x330mm 34.1-inch      | 2        | 0.63%   |
| Dell U2212HM DELD048 1920x1080 475x267mm 21.5-inch                    | 2        | 0.63%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 2        | 0.63%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2        | 0.63%   |
| Dell AW3821DW DELA17F 3840x1600 880x367mm 37.5-inch                   | 2        | 0.63%   |
| Dell 1704FPV DEL3016 1280x1024 338x270mm 17.0-inch                    | 2        | 0.63%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                    | 2        | 0.63%   |
| ASUSTek Computer VG279 AUS2782 1920x1080 598x336mm 27.0-inch          | 2        | 0.63%   |
| AOC LE24H067 AOC2410 1920x1080 521x293mm 23.5-inch                    | 2        | 0.63%   |
| Ancor Communications VG248 ACI24A5 1920x1080 531x299mm 24.0-inch      | 2        | 0.63%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 2        | 0.63%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch      | 2        | 0.63%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 2        | 0.63%   |
| ___ LCD TV ___9000 1360x768                                           | 1        | 0.31%   |
| VOXICON D27Q0 DUS2700 2560x1440 597x336mm 27.0-inch                   | 1        | 0.31%   |
| Vizio V705-H3 VIZ1039 3840x2160 1538x865mm 69.5-inch                  | 1        | 0.31%   |
| Viotek VIOTEKGN27C2 VTK0027 1920x1080 598x336mm 27.0-inch             | 1        | 0.31%   |
| Viotek SUW49DA VTK0490 2560x1440 1194x336mm 48.8-inch                 | 1        | 0.31%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch         | 1        | 0.31%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch            | 1        | 0.31%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch         | 1        | 0.31%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 1        | 0.31%   |
| Valve Index HMD VLV91A8                                               | 1        | 0.31%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1        | 0.31%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1        | 0.31%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.31%   |
| Unknown LCD Monitor MEC MD20491 1920x1080                             | 1        | 0.31%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 1        | 0.31%   |
| Toshiba TV TSB0108 1920x1080 1594x900mm 72.1-inch                     | 1        | 0.31%   |
| STD LED STD0110 1366x768 410x230mm 18.5-inch                          | 1        | 0.31%   |
| SKY M16U1 SKY0156 3840x2160 345x194mm 15.6-inch                       | 1        | 0.31%   |
| Sharp HDMI SHP0FEC 1920x1080 820x460mm 37.0-inch                      | 1        | 0.31%   |
| Sceptre Tech Sceptre M25 SPT09FB 1920x1080 544x303mm 24.5-inch        | 1        | 0.31%   |
| Sceptre Tech Sceptre E20 SPT080D 1600x900 410x280mm 19.5-inch         | 1        | 0.31%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                | 1        | 0.31%   |
| Sceptre Tech E32 SPT0CB8 1366x768 575x323mm 26.0-inch                 | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM0613 1920x1080                      | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM0604 1920x1080                      | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM044C 1680x1050 474x296mm 22.0-inch  | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM03F1 1680x1050                      | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM031F 1680x1050 474x296mm 22.0-inch  | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM030E 1680x1050 474x296mm 22.0-inch  | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 1        | 0.31%   |
| Samsung Electronics SMT27A550 SAM07B7 1920x1080 598x336mm 27.0-inch   | 1        | 0.31%   |
| Samsung Electronics SMBX2440 SAM068A 1920x1080 531x299mm 24.0-inch    | 1        | 0.31%   |
| Samsung Electronics SMBX2431 SAM0771 1920x1080 531x299mm 24.0-inch    | 1        | 0.31%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 480x270mm 21.7-inch    | 1        | 0.31%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch | 1        | 0.31%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 138      | 48.08%  |
| 3840x2160 (4K)     | 42       | 14.63%  |
| 2560x1440 (QHD)    | 29       | 10.1%   |
| 1680x1050 (WSXGA+) | 14       | 4.88%   |
| 3440x1440          | 11       | 3.83%   |
| 1280x1024 (SXGA)   | 9        | 3.14%   |
| 2560x1080          | 8        | 2.79%   |
| 1920x1200 (WUXGA)  | 5        | 1.74%   |
| 1366x768 (WXGA)    | 5        | 1.74%   |
| 3840x1080          | 4        | 1.39%   |
| 1600x900 (HD+)     | 4        | 1.39%   |
| 3840x1600          | 3        | 1.05%   |
| 1920x540           | 3        | 1.05%   |
| 1360x768           | 3        | 1.05%   |
| 1440x900 (WXGA+)   | 2        | 0.7%    |
| 1024x768 (XGA)     | 2        | 0.7%    |
| Unknown            | 2        | 0.7%    |
| 3040x900           | 1        | 0.35%   |
| 2560x1600          | 1        | 0.35%   |
| 1280x800 (WXGA)    | 1        | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 51       | 17.11%  |
| 24      | 44       | 14.77%  |
| 23      | 37       | 12.42%  |
| 21      | 28       | 9.4%    |
| 31      | 22       | 7.38%   |
| 34      | 18       | 6.04%   |
| Unknown | 13       | 4.36%   |
| 22      | 9        | 3.02%   |
| 19      | 8        | 2.68%   |
| 84      | 7        | 2.35%   |
| 32      | 7        | 2.35%   |
| 72      | 5        | 1.68%   |
| 25      | 5        | 1.68%   |
| 20      | 5        | 1.68%   |
| 17      | 5        | 1.68%   |
| 48      | 4        | 1.34%   |
| 37      | 4        | 1.34%   |
| 18      | 4        | 1.34%   |
| 15      | 4        | 1.34%   |
| 26      | 3        | 1.01%   |
| 54      | 2        | 0.67%   |
| 46      | 2        | 0.67%   |
| 69      | 1        | 0.34%   |
| 65      | 1        | 0.34%   |
| 52      | 1        | 0.34%   |
| 49      | 1        | 0.34%   |
| 47      | 1        | 0.34%   |
| 42      | 1        | 0.34%   |
| 35      | 1        | 0.34%   |
| 33      | 1        | 0.34%   |
| 30      | 1        | 0.34%   |
| 29      | 1        | 0.34%   |
| 28      | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 125      | 43.55%  |
| 401-500     | 48       | 16.72%  |
| 601-700     | 30       | 10.45%  |
| 701-800     | 26       | 9.06%   |
| 1501-2000   | 13       | 4.53%   |
| Unknown     | 13       | 4.53%   |
| 1001-1500   | 12       | 4.18%   |
| 301-350     | 9        | 3.14%   |
| 801-900     | 5        | 1.74%   |
| 351-400     | 5        | 1.74%   |
| 901-1000    | 1        | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 199      | 73.16%  |
| 16/10   | 25       | 9.19%   |
| 21/9    | 23       | 8.46%   |
| 5/4     | 9        | 3.31%   |
| Unknown | 7        | 2.57%   |
| 32/9    | 5        | 1.84%   |
| 4/3     | 4        | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 88       | 30.77%  |
| 301-350        | 54       | 18.88%  |
| 351-500        | 50       | 17.48%  |
| 151-200        | 21       | 7.34%   |
| 251-300        | 18       | 6.29%   |
| More than 1000 | 17       | 5.94%   |
| Unknown        | 13       | 4.55%   |
| 501-1000       | 12       | 4.2%    |
| 141-150        | 9        | 3.15%   |
| 101-110        | 4        | 1.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 161      | 59.63%  |
| 101-120       | 63       | 23.33%  |
| 1-50          | 13       | 4.81%   |
| 121-160       | 13       | 4.81%   |
| Unknown       | 13       | 4.81%   |
| 161-240       | 6        | 2.22%   |
| More than 240 | 1        | 0.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 193      | 71.48%  |
| 2     | 57       | 21.11%  |
| 0     | 11       | 4.07%   |
| 3     | 8        | 2.96%   |
| 6     | 1        | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 152      | 37.62%  |
| Intel                           | 149      | 36.88%  |
| Qualcomm Atheros                | 27       | 6.68%   |
| Broadcom                        | 13       | 3.22%   |
| Ralink Technology               | 6        | 1.49%   |
| TP-Link                         | 5        | 1.24%   |
| Xiaomi                          | 4        | 0.99%   |
| Microsoft                       | 4        | 0.99%   |
| MediaTek                        | 4        | 0.99%   |
| Aquantia                        | 4        | 0.99%   |
| Qualcomm Atheros Communications | 3        | 0.74%   |
| NetGear                         | 3        | 0.74%   |
| ASUSTek Computer                | 3        | 0.74%   |
| Samsung Electronics             | 2        | 0.5%    |
| Ralink                          | 2        | 0.5%    |
| Nvidia                          | 2        | 0.5%    |
| InterBiometrics                 | 2        | 0.5%    |
| D-Link                          | 2        | 0.5%    |
| STMicroelectronics              | 1        | 0.25%   |
| Sitecom Europe                  | 1        | 0.25%   |
| SIEMENS                         | 1        | 0.25%   |
| Qualcomm                        | 1        | 0.25%   |
| OPPO Electronics                | 1        | 0.25%   |
| Micro Star International        | 1        | 0.25%   |
| Mellanox Technologies           | 1        | 0.25%   |
| IMC Networks                    | 1        | 0.25%   |
| Hyperkin                        | 1        | 0.25%   |
| Huawei Technologies             | 1        | 0.25%   |
| Google                          | 1        | 0.25%   |
| Gemtek                          | 1        | 0.25%   |
| DisplayLink                     | 1        | 0.25%   |
| D-Link System                   | 1        | 0.25%   |
| Broadcom Limited                | 1        | 0.25%   |
| Belkin Components               | 1        | 0.25%   |
| AVM                             | 1        | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 99       | 21.06%  |
| Intel I211 Gigabit Network Connection                               | 43       | 9.15%   |
| Intel Wi-Fi 6 AX200                                                 | 36       | 7.66%   |
| Realtek RTL8125 2.5GbE Controller                                   | 32       | 6.81%   |
| Intel Ethernet Controller I225-V                                    | 15       | 3.19%   |
| Intel Ethernet Connection (2) I219-V                                | 14       | 2.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 13       | 2.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 10       | 2.13%   |
| Intel Ethernet Connection (7) I219-V                                | 9        | 1.91%   |
| Realtek 802.11ac NIC                                                | 8        | 1.7%    |
| Intel Ethernet Connection I217-LM                                   | 8        | 1.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 7        | 1.49%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 7        | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 6        | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 6        | 1.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 5        | 1.06%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 5        | 1.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 4        | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 4        | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 3        | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 3        | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                     | 3        | 0.64%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 3        | 0.64%   |
| Intel Wireless-AC 9260                                              | 3        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                                | 3        | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 3        | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 2        | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                | 2        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.43%   |
| Ralink MT7601U Wireless Adapter                                     | 2        | 0.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 2        | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2        | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 2        | 0.43%   |
| Nvidia MCP61 Ethernet                                               | 2        | 0.43%   |
| NetGear A6210                                                       | 2        | 0.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 2        | 0.43%   |
| InterBiometrics Io                                                  | 2        | 0.43%   |
| Intel Wireless Gigabit 17265                                        | 2        | 0.43%   |
| Intel Wireless 7265                                                 | 2        | 0.43%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 2        | 0.43%   |
| Intel Ethernet Connection I217-V                                    | 2        | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                               | 2        | 0.43%   |
| Intel Ethernet Connection (14) I219-V                               | 2        | 0.43%   |
| Intel 82579V Gigabit Network Connection                             | 2        | 0.43%   |
| Intel 82574L Gigabit Network Connection                             | 2        | 0.43%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 0.43%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                    | 2        | 0.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 2        | 0.43%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 0.43%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1        | 0.21%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.21%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.21%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 1        | 0.21%   |
| TP-Link 802.11ac NIC                                                | 1        | 0.21%   |
| STMicroelectronics Virtual COM Port                                 | 1        | 0.21%   |
| Sitecom Europe WL-344 Wireless Adapter 300N X2 [Ralink RT3071]      | 1        | 0.21%   |
| SIEMENS SIMATIC NET CP 5611 / 5621                                  | 1        | 0.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.21%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 79       | 49.07%  |
| Realtek Semiconductor           | 22       | 13.66%  |
| Qualcomm Atheros                | 14       | 8.7%    |
| Broadcom                        | 8        | 4.97%   |
| Ralink Technology               | 6        | 3.73%   |
| TP-Link                         | 4        | 2.48%   |
| Microsoft                       | 4        | 2.48%   |
| MediaTek                        | 4        | 2.48%   |
| Qualcomm Atheros Communications | 3        | 1.86%   |
| NetGear                         | 3        | 1.86%   |
| ASUSTek Computer                | 3        | 1.86%   |
| Ralink                          | 2        | 1.24%   |
| D-Link                          | 2        | 1.24%   |
| Sitecom Europe                  | 1        | 0.62%   |
| Micro Star International        | 1        | 0.62%   |
| IMC Networks                    | 1        | 0.62%   |
| Gemtek                          | 1        | 0.62%   |
| D-Link System                   | 1        | 0.62%   |
| Belkin Components               | 1        | 0.62%   |
| AVM                             | 1        | 0.62%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 36       | 22.09%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 13       | 7.98%   |
| Realtek 802.11ac NIC                                                                          | 8        | 4.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 7        | 4.29%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 7        | 4.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 6        | 3.68%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 5        | 3.07%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 4        | 2.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 1.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3        | 1.84%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 3        | 1.84%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 3        | 1.84%   |
| Intel Wireless-AC 9260                                                                        | 3        | 1.84%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 3        | 1.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2        | 1.23%   |
| Ralink MT7601U Wireless Adapter                                                               | 2        | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2        | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 1.23%   |
| NetGear A6210                                                                                 | 2        | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 2        | 1.23%   |
| Intel Wireless Gigabit 17265                                                                  | 2        | 1.23%   |
| Intel Wireless 7265                                                                           | 2        | 1.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2        | 1.23%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.61%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 0.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.61%   |
| TP-Link 802.11ac NIC                                                                          | 1        | 0.61%   |
| Sitecom Europe WL-344 Wireless Adapter 300N X2 [Ralink RT3071]                                | 1        | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 0.61%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 0.61%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.61%   |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 0.61%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.61%   |
| Ralink RT3572 Wireless Adapter                                                                | 1        | 0.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1        | 0.61%   |
| Ralink RT5592 PCIe Wireless Network Adapter                                                   | 1        | 0.61%   |
| Ralink RT2500 Wireless 802.11bg                                                               | 1        | 0.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 0.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 1        | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1        | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1        | 0.61%   |
| Qualcomm Atheros AR922x Wireless Network Adapter                                              | 1        | 0.61%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1        | 0.61%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express)         | 1        | 0.61%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                                   | 1        | 0.61%   |
| Microsoft XBOX ACC                                                                            | 1        | 0.61%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]                    | 1        | 0.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 0.61%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                            | 1        | 0.61%   |
| Intel Wireless 8260                                                                           | 1        | 0.61%   |
| Intel Wireless 3165                                                                           | 1        | 0.61%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                          | 1        | 0.61%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                                             | 1        | 0.61%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B2) [Ralink RT3072]                          | 1        | 0.61%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                          | 1        | 0.61%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS]                       | 1        | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 1        | 0.61%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]                            | 1        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 139      | 46.64%  |
| Intel                 | 119      | 39.93%  |
| Qualcomm Atheros      | 14       | 4.7%    |
| Broadcom              | 6        | 2.01%   |
| Xiaomi                | 4        | 1.34%   |
| Aquantia              | 4        | 1.34%   |
| Samsung Electronics   | 2        | 0.67%   |
| Nvidia                | 2        | 0.67%   |
| TP-Link               | 1        | 0.34%   |
| Qualcomm              | 1        | 0.34%   |
| OPPO Electronics      | 1        | 0.34%   |
| Mellanox Technologies | 1        | 0.34%   |
| Huawei Technologies   | 1        | 0.34%   |
| Google                | 1        | 0.34%   |
| DisplayLink           | 1        | 0.34%   |
| Broadcom Limited      | 1        | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 99       | 32.78%  |
| Intel I211 Gigabit Network Connection                             | 43       | 14.24%  |
| Realtek RTL8125 2.5GbE Controller                                 | 32       | 10.6%   |
| Intel Ethernet Controller I225-V                                  | 15       | 4.97%   |
| Intel Ethernet Connection (2) I219-V                              | 14       | 4.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 3.31%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 2.98%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 2.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 1.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 1.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4        | 1.32%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2        | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.66%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.66%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.66%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.66%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.66%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2        | 0.66%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.66%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.66%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.33%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.33%   |
| Qualcomm BENGAL-QRD _SN:C5464635                                  | 1        | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.33%   |
| OPPO SDM720G-IDP _SN:B922E265                                     | 1        | 0.33%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 0.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.33%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.33%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.33%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.33%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.33%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1        | 0.33%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.33%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.33%   |
| Huawei LYA-L09                                                    | 1        | 0.33%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1        | 0.33%   |
| DisplayLink USB3.0 Dual Video Dock                                | 1        | 0.33%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.33%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.33%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 0.33%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.33%   |
| Aquantia AQC108 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 265      | 62.8%   |
| WiFi     | 152      | 36.02%  |
| Modem    | 3        | 0.71%   |
| Unknown  | 2        | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 200      | 72.73%  |
| WiFi     | 75       | 27.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 147      | 54.65%  |
| 2     | 95       | 35.32%  |
| 3     | 21       | 7.81%   |
| 0     | 4        | 1.49%   |
| 4     | 2        | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 188      | 69.89%  |
| Yes  | 81       | 30.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 72       | 62.07%  |
| Cambridge Silicon Radio         | 18       | 15.52%  |
| ASUSTek Computer                | 8        | 6.9%    |
| Qualcomm Atheros Communications | 5        | 4.31%   |
| Foxconn / Hon Hai               | 3        | 2.59%   |
| Broadcom                        | 3        | 2.59%   |
| Apple                           | 2        | 1.72%   |
| TP-Link                         | 1        | 0.86%   |
| Realtek Semiconductor           | 1        | 0.86%   |
| Micro Star International        | 1        | 0.86%   |
| MediaTek                        | 1        | 0.86%   |
| IMC Networks                    | 1        | 0.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 33       | 28.45%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 18       | 15.52%  |
| Intel Wireless-AC 3168 Bluetooth                      | 12       | 10.34%  |
| Intel AX201 Bluetooth                                 | 8        | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 6        | 5.17%   |
| Intel Bluetooth Device                                | 5        | 4.31%   |
| Intel AX210 Bluetooth                                 | 5        | 4.31%   |
| Qualcomm Atheros  Bluetooth Device                    | 3        | 2.59%   |
| Intel Bluetooth wireless interface                    | 3        | 2.59%   |
| ASUS Bluetooth Radio                                  | 3        | 2.59%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 1.72%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 1.72%   |
| ASUS ASUS USB-BT500                                   | 2        | 1.72%   |
| TP-Link TP-hink UB500 Adapter                         | 1        | 0.86%   |
| Realtek Bluetooth Radio                               | 1        | 0.86%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.86%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 0.86%   |
| Micro Star International Bluetooth Device             | 1        | 0.86%   |
| MediaTek Wireless_Device                              | 1        | 0.86%   |
| IMC Networks Bluetooth Radio                          | 1        | 0.86%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 0.86%   |
| Broadcom BCM2035 Bluetooth dongle                     | 1        | 0.86%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 0.86%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 0.86%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.86%   |
| Apple Bluetooth USB Host Controller                   | 1        | 0.86%   |
| Apple Bluetooth HCI                                   | 1        | 0.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 151      | 27.96%  |
| Nvidia                               | 141      | 26.11%  |
| Intel                                | 137      | 25.37%  |
| C-Media Electronics                  | 13       | 2.41%   |
| Logitech                             | 10       | 1.85%   |
| Kingston Technology                  | 9        | 1.67%   |
| Creative Labs                        | 6        | 1.11%   |
| JMTek                                | 5        | 0.93%   |
| Focusrite-Novation                   | 5        | 0.93%   |
| SteelSeries ApS                      | 4        | 0.74%   |
| Micro Star International             | 4        | 0.74%   |
| Corsair                              | 4        | 0.74%   |
| Razer USA                            | 3        | 0.56%   |
| Texas Instruments                    | 2        | 0.37%   |
| Sennheiser Communications            | 2        | 0.37%   |
| GN Netcom                            | 2        | 0.37%   |
| Creative Technology                  | 2        | 0.37%   |
| ASUSTek Computer                     | 2        | 0.37%   |
| Antlion Audio                        | 2        | 0.37%   |
| Yamaha                               | 1        | 0.19%   |
| Valve Software                       | 1        | 0.19%   |
| USB MIDI                             | 1        | 0.19%   |
| Unknown                              | 1        | 0.19%   |
| Turtle Beach                         | 1        | 0.19%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.19%   |
| Tenx Technology                      | 1        | 0.19%   |
| Sony                                 | 1        | 0.19%   |
| Solid State System                   | 1        | 0.19%   |
| Shure                                | 1        | 0.19%   |
| Shenzhen Rapoo Technology            | 1        | 0.19%   |
| SAVITECH                             | 1        | 0.19%   |
| Samson Technologies                  | 1        | 0.19%   |
| Realtek Semiconductor                | 1        | 0.19%   |
| Native Instruments                   | 1        | 0.19%   |
| Microsoft                            | 1        | 0.19%   |
| Micronas                             | 1        | 0.19%   |
| Medeli Electronics                   | 1        | 0.19%   |
| Mackie Designs                       | 1        | 0.19%   |
| JOUNIVO JV601                        | 1        | 0.19%   |
| GYROCOM C&C                          | 1        | 0.19%   |
| Google                               | 1        | 0.19%   |
| Giga-Byte Technology                 | 1        | 0.19%   |
| Generalplus Technology               | 1        | 0.19%   |
| GEMBIRD                              | 1        | 0.19%   |
| FiiO Electronics Technology          | 1        | 0.19%   |
| fifinemicrophone.com                 | 1        | 0.19%   |
| FIFINE Microphones                   | 1        | 0.19%   |
| DEXP BK-20                           | 1        | 0.19%   |
| DCMT Technology                      | 1        | 0.19%   |
| C&T                                  | 1        | 0.19%   |
| Blue Microphones                     | 1        | 0.19%   |
| BEHRINGER International              | 1        | 0.19%   |
| Barco Display Systems                | 1        | 0.19%   |
| AudioQuest                           | 1        | 0.19%   |
| Audient                              | 1        | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 66       | 10.56%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 23       | 3.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 21       | 3.36%   |
| Intel 200 Series PCH HD Audio                                              | 18       | 2.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 16       | 2.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15       | 2.4%    |
| Nvidia GP107GL High Definition Audio Controller                            | 14       | 2.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14       | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14       | 2.24%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14       | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 13       | 2.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13       | 2.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13       | 2.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 11       | 1.76%   |
| Nvidia GP104 High Definition Audio Controller                              | 11       | 1.76%   |
| Nvidia GA104 High Definition Audio Controller                              | 11       | 1.76%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11       | 1.76%   |
| Nvidia TU104 HD Audio Controller                                           | 10       | 1.6%    |
| Nvidia GA106 High Definition Audio Controller                              | 9        | 1.44%   |
| Nvidia GA102 High Definition Audio Controller                              | 9        | 1.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 1.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9        | 1.44%   |
| AMD Navi 10 HDMI Audio                                                     | 9        | 1.44%   |
| Intel Alder Lake-S HD Audio Controller                                     | 7        | 1.12%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 7        | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 6        | 0.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 0.96%   |
| Kingston Technology HyperX 7.1 Audio                                       | 6        | 0.96%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 0.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 0.96%   |
| Nvidia TU102 High Definition Audio Controller                              | 5        | 0.8%    |
| Intel Audio device                                                         | 5        | 0.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5        | 0.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 0.8%    |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 0.64%   |
| Micro Star International USB Audio                                         | 4        | 0.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 0.64%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 0.64%   |
| AMD FCH Azalia Controller                                                  | 4        | 0.64%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 0.48%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.48%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.48%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 0.48%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.48%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 0.48%   |
| JMTek USB PnP Audio Device                                                 | 3        | 0.48%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.48%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 0.48%   |
| Focusrite-Novation Scarlett 2i2 Camera                                     | 3        | 0.48%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 3        | 0.48%   |
| C-Media Electronics USB Audio Device                                       | 3        | 0.48%   |
| C-Media Electronics Blue Snowball                                          | 3        | 0.48%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3        | 0.48%   |
| AMD Kabini HDMI/DP Audio                                                   | 3        | 0.48%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 3        | 0.48%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 0.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.32%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.32%   |
| Nvidia GF116 High Definition Audio Controller                              | 2        | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 16       | 32%     |
| G.Skill             | 10       | 20%     |
| Kingston            | 5        | 10%     |
| Team                | 4        | 8%      |
| Unknown             | 3        | 6%      |
| Samsung Electronics | 3        | 6%      |
| Micron Technology   | 2        | 4%      |
| Crucial             | 2        | 4%      |
| Unknown             | 2        | 4%      |
| SK hynix            | 1        | 2%      |
| Patriot Memory      | 1        | 2%      |
| Avant               | 1        | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 3        | 5.88%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s     | 3        | 5.88%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s       | 2        | 3.92%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 2        | 3.92%   |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s      | 2        | 3.92%   |
| Unknown                                                   | 2        | 3.92%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                      | 1        | 1.96%   |
| Unknown RAM Module 16GB DIMM DDR4 3600MT/s                | 1        | 1.96%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s        | 1        | 1.96%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s        | 1        | 1.96%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s        | 1        | 1.96%   |
| SK hynix RAM HMT351U6CFR8C-PBA 4GB DIMM DDR3 1600MT/s     | 1        | 1.96%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s       | 1        | 1.96%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s       | 1        | 1.96%   |
| Patriot Memory RAM 4400 C19 Series 8GB DIMM DDR4 3000MT/s | 1        | 1.96%   |
| Micron RAM M378A1K43BB2G3A141 8GB DIMM DDR4 2400MT/s      | 1        | 1.96%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s    | 1        | 1.96%   |
| Kingston RAM KVT8FP-HYC 4GB DIMM DDR3 1600MT/s            | 1        | 1.96%   |
| Kingston RAM KHX3600C18D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 1.96%   |
| Kingston RAM CL16-18-18 D4-3000 8GB DIMM DDR4 3000MT/s    | 1        | 1.96%   |
| Kingston RAM 99U5471-033.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 1.96%   |
| Kingston RAM 99P5471-033.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 1.96%   |
| G.Skill RAM F4-3600C18-8GVK 8GB DIMM DDR4 3600MT/s        | 1        | 1.96%   |
| G.Skill RAM F4-3600C18-32GTZN 32GB DIMM DDR4 3600MT/s     | 1        | 1.96%   |
| G.Skill RAM F4-3600C16-8GVKC 8GB DIMM DDR4 3600MT/s       | 1        | 1.96%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s       | 1        | 1.96%   |
| G.Skill RAM F4-3200C16-4GVKB 4GB DIMM DDR4 3200MT/s       | 1        | 1.96%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 1        | 1.96%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 1        | 1.96%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s        | 1        | 1.96%   |
| Crucial RAM CT51264BA1339.M16F 4GB DIMM DDR3 1333MT/s     | 1        | 1.96%   |
| Crucial RAM BLS8G4D30AESEK.M8FE 8GB DIMM DDR4 3600MT/s    | 1        | 1.96%   |
| Corsair RAM Module 16GB SODIMM DDR4 2400MT/s              | 1        | 1.96%   |
| Corsair RAM CMY8GX3M2A2400C11 4GB DIMM DDR3 2133MT/s      | 1        | 1.96%   |
| Corsair RAM CMX16GX3M4A1333C9 4GB DIMM DDR3 1333MT/s      | 1        | 1.96%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s     | 1        | 1.96%   |
| Corsair RAM CMT32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s    | 1        | 1.96%   |
| Corsair RAM CMK8GX4M1A2400C14 8GB DIMM DDR4 2800MT/s      | 1        | 1.96%   |
| Corsair RAM CMK32GX4M4A2400C14 8GB DIMM DDR4 2666MT/s     | 1        | 1.96%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s    | 1        | 1.96%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s    | 1        | 1.96%   |
| Corsair RAM CMG32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s    | 1        | 1.96%   |
| Avant RAM W641GU42J5213NB 8GB DIMM DDR4 2133MT/s          | 1        | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 39       | 84.78%  |
| DDR3    | 6        | 13.04%  |
| Unknown | 1        | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 45       | 97.83%  |
| SODIMM | 1        | 2.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 25       | 54.35%  |
| 16384 | 11       | 23.91%  |
| 4096  | 6        | 13.04%  |
| 32768 | 4        | 8.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 15       | 31.25%  |
| 3200  | 8        | 16.67%  |
| 1600  | 5        | 10.42%  |
| 3466  | 4        | 8.33%   |
| 3000  | 3        | 6.25%   |
| 2400  | 2        | 4.17%   |
| 2133  | 2        | 4.17%   |
| 1333  | 2        | 4.17%   |
| 3266  | 1        | 2.08%   |
| 3100  | 1        | 2.08%   |
| 3067  | 1        | 2.08%   |
| 2800  | 1        | 2.08%   |
| 2667  | 1        | 2.08%   |
| 2666  | 1        | 2.08%   |
| 1866  | 1        | 2.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 23.08%  |
| Hewlett-Packard     | 3        | 23.08%  |
| Brother Industries  | 3        | 23.08%  |
| Seiko Epson         | 1        | 7.69%   |
| QinHeng Electronics | 1        | 7.69%   |
| Dymo-CoStar         | 1        | 7.69%   |
| Canon               | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seiko Epson WF-4830 Series             | 1        | 7.14%   |
| Samsung SCX-3400 Series                | 1        | 7.14%   |
| Samsung ML-191x/ML-252x Laser Printer  | 1        | 7.14%   |
| Samsung M2070 Series                   | 1        | 7.14%   |
| QinHeng CH340S                         | 1        | 7.14%   |
| HP PSC-1315/PSC-1317                   | 1        | 7.14%   |
| HP LaserJet P2035                      | 1        | 7.14%   |
| HP ENVY Pro 6400 series                | 1        | 7.14%   |
| Dymo-CoStar DYMO LabelWriter 4XL       | 1        | 7.14%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 7.14%   |
| Canon Pro9000II series                 | 1        | 7.14%   |
| Brother MFC-L2700DW                    | 1        | 7.14%   |
| Brother MFC-5440CN                     | 1        | 7.14%   |
| Brother HL-2130 series                 | 1        | 7.14%   |

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


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LiDE 60 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 27       | 42.19%  |
| Microdia                      | 5        | 7.81%   |
| Sunplus Innovation Technology | 4        | 6.25%   |
| Samsung Electronics           | 4        | 6.25%   |
| Sunplus IT                    | 2        | 3.13%   |
| Realtek Semiconductor         | 2        | 3.13%   |
| Razer USA                     | 2        | 3.13%   |
| Jieli Technology              | 2        | 3.13%   |
| ARC International             | 2        | 3.13%   |
| Apple                         | 2        | 3.13%   |
| YGTek                         | 1        | 1.56%   |
| XHT-210518                    | 1        | 1.56%   |
| WaveRider Communications      | 1        | 1.56%   |
| Valve Software                | 1        | 1.56%   |
| Microsoft                     | 1        | 1.56%   |
| MacroSilicon                  | 1        | 1.56%   |
| icSpring                      | 1        | 1.56%   |
| Hewlett-Packard               | 1        | 1.56%   |
| GenesysLogic Technology       | 1        | 1.56%   |
| Generalplus Technology        | 1        | 1.56%   |
| eMeet                         | 1        | 1.56%   |
| Creative Technology           | 1        | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Logitech Webcam C270                | 7        | 10.94%  |
| Logitech HD Pro Webcam C920         | 6        | 9.38%   |
| Samsung Galaxy A5 (MTP)             | 4        | 6.25%   |
| Logitech C922 Pro Stream Webcam     | 3        | 4.69%   |
| Sunplus IT AUKEY PC-LM1 USB Camera  | 2        | 3.13%   |
| Sunplus SPCA2281 Web Camera         | 2        | 3.13%   |
| Sunplus Full HD webcam              | 2        | 3.13%   |
| Razer USA Gaming Webcam [Kiyo]      | 2        | 3.13%   |
| Logitech Webcam C930e               | 2        | 3.13%   |
| Logitech HD Webcam C615             | 2        | 3.13%   |
| Jieli USB PHY 2.0                   | 2        | 3.13%   |
| ARC International Camera            | 2        | 3.13%   |
| Apple iPhone 5/5C/5S/6/SE           | 2        | 3.13%   |
| YGTek Webcam                        | 1        | 1.56%   |
| XHT-210518 EC500X                   | 1        | 1.56%   |
| WaveRider USB Live camera           | 1        | 1.56%   |
| Valve Software 3D Camera            | 1        | 1.56%   |
| Realtek Thronmax StreamGo Webcam    | 1        | 1.56%   |
| Realtek FULL HD 1080P Webcam        | 1        | 1.56%   |
| Microsoft LifeCam Cinema            | 1        | 1.56%   |
| Microdia Rapoo camera               | 1        | 1.56%   |
| Microdia Integrated Camera          | 1        | 1.56%   |
| Microdia HDP Webcam USB             | 1        | 1.56%   |
| Microdia AUKEY PC-W1                | 1        | 1.56%   |
| Microdia Amcrest AWC2198 USB Webcam | 1        | 1.56%   |
| MacroSilicon USB3.0 HD VIDEO        | 1        | 1.56%   |
| Logitech Webcam Pro 9000            | 1        | 1.56%   |
| Logitech Webcam C925e               | 1        | 1.56%   |
| Logitech HD Webcam C525             | 1        | 1.56%   |
| Logitech HD Webcam C510             | 1        | 1.56%   |
| Logitech CrystalCam                 | 1        | 1.56%   |
| Logitech C920 PRO HD Webcam         | 1        | 1.56%   |
| Logitech BRIO Ultra HD Webcam       | 1        | 1.56%   |
| icSpring camera                     | 1        | 1.56%   |
| HP USB Webcam                       | 1        | 1.56%   |
| GenesysLogic USB2.0 UVC PC Camera   | 1        | 1.56%   |
| Generalplus WEB CAM                 | 1        | 1.56%   |
| eMeet HD Webcam C960                | 1        | 1.56%   |
| Creative Live! Cam Optia            | 1        | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 226      | 84.01%  |
| 1     | 39       | 14.5%   |
| 2     | 3        | 1.12%   |
| 3     | 1        | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 17       | 35.42%  |
| Graphics card            | 12       | 25%     |
| Bluetooth                | 5        | 10.42%  |
| Unassigned class         | 3        | 6.25%   |
| Network                  | 2        | 4.17%   |
| Multimedia controller    | 2        | 4.17%   |
| Communication controller | 2        | 4.17%   |
| Storage/ide              | 1        | 2.08%   |
| Sound                    | 1        | 2.08%   |
| Net/ethernet             | 1        | 2.08%   |
| Fingerprint reader       | 1        | 2.08%   |
| Chipcard                 | 1        | 2.08%   |

