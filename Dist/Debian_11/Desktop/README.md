Debian 11 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linux-bsd)
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

* [ Printers & scanners ](#printers-scanners)
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

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell       | 0M863N A00                  | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Gigabyte   | P35C-DS3R                   | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI        | X399 GAMING PRO CARBON A... | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| MSI        | MEG X570 UNIFY              | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| ASRock     | Z97 Pro3                    | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| MSI        | Z370 SLI PLUS               | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| ASUSTek    | PRIME X370-PRO              | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock     | B450 Pro4                   | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP         | 2B38                        | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP         | 2B38                        | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock     | 970 Pro3 R2.0               | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek    | PRIME B550-PLUS             | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek    | PRIME B550-PLUS             | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASRock     | X570 Steel Legend           | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek    | PRIME B350-PLUS             | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Gigabyte   | AB350-Gaming 3-CF           | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Gigabyte   | AB350-Gaming 3-CF           | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek    | M5A78L-M LX3                | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Gigabyte   | B450M DS3H-CF               | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek    | B85-PRO GAMER               | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek    | M5A78L-M LX3                | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell       | 0D28YY A02                  | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock     | H470M-ITX/ac                | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| ASUSTek    | M5A78L-M LX3                | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek    | PRIME B450M-A               | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| MSI        | B450 TOMAHAWK MAX II        | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Gigabyte   | H110M-S2H-CF                | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell       | 0PTTT9 A00                  | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell       | 0X8DXD A00                  | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| ASUSTek    | PRIME H270M-PLUS            | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte   | Z170M-D3H-CF                | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| ASRock     | P67 Pro3                    | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro | A1SA2-2750FA                | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte   | H87-HD3                     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| ASUSTek    | ROG STRIX B450-I GAMING     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte   | AB350M-DS3H V2-CF           | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| Dell       | 0Y1057                      | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP         | ProLiant MicroServer Gen... | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock     | B450M Pro4                  | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| ASRock     | Z97 Extreme6                | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo     | 3098 0B98401 PRO            | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP         | 1495                        | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| HP         | 158A                        | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| HP         | 158A                        | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| ASUSTek    | H110M-A/M.2                 | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| Gigabyte   | H110N-CF                    | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| MSI        | MAG B550M MORTAR            | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell       | 0X8DXD A00                  | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP         | 2129                        | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Intel      | DP55WG AAE57269-407         | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock     | B85 Anniversary             | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte   | B550I AORUS PRO AX          | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte   | B550I AORUS PRO AX          | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Gigabyte   | Z97X-UD3H-CF                | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| ASUSTek    | PRIME B250M-A               | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| ASRock     | B450M Pro4                  | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| ASRock     | B450M Pro4                  | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Gigabyte   | H61MS                       | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Gigabyte   | H81M-S2H GSM                | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell       | 09KPNV A01                  | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| ASUSTek    | PRIME A320I-K               | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| ASUSTek    | H61M-K                      | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell       | 0NK5PH A00                  | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte   | Z77-D3H                     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| Intel      | DP55WB AAE64798-206         | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Protectli  | FW6                         | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek    | ROG STRIX Z390-F GAMING     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte   | X570 I AORUS PRO WIFI       | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek    | Z170-DELUXE                 | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte   | 970A-D3P                    | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Dell       | 0D441T A03                  | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| MSI        | H110I PRO AC                | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek    | PRIME Z370-A                | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek    | H87-PRO                     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI        | Z77MA-G45                   | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| ASRock     | FM2A68M-DG3+                | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Gigabyte   | B560M D3H                   | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| ASUSTek    | ROG STRIX Z370-H GAMING     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek    | P8Z68-V                     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| HP         | ProLiant MicroServer        | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| MSI        | A68HM-E33 V2                | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Huanan     | X99-F8 V2.0                 | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell       | 0M863N A00                  | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| MSI        | MPG B550 GAMING PLUS        | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek    | H81M-E                      | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP         | 2215                        | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| HP         | 2215                        | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| MSI        | MS-6712                     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| ASRock     | H77 Pro4-M                  | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte   | B550I AORUS PRO AX          | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Gigabyte   | AX370-Gaming K7             | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| MSI        | B85M-G43                    | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| Huanan     | X99-8M-F V1.1               | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| ASRock     | FM2A68M-HD+                 | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Gigabyte   | Z370 AORUS Gaming 5-CF      | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte   | Z370 AORUS Gaming 5-CF      | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock     | B550 Pro4                   | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock     | X399 Taichi                 | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL | ODROID-H2                   | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING ... | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Gigabyte   | AB350M-Gaming 3-CF          | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| MSI        | B450M MORTAR MAX            | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING ... | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| ASUSTek    | PRIME B450M-A               | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Gigabyte   | MCMLUAB-00                  | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| ASUSTek    | PRIME A320M-K               | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| Dell       | 0Y7WYT A00                  | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| ASUSTek    | Z97-AR                      | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| ASRock     | B450M Pro4                  | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| ASUSTek    | PRIME A320M-K               | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| ASRock     | B450M Pro4                  | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| ASUSTek    | M4A88T-M/USB3               | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Dell       | 0YXT71 A02                  | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| ASUSTek    | PRIME B550-PLUS             | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| ASUSTek    | P5B-Deluxe                  | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Gigabyte   | B450 AORUS PRO WIFI-CF      | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI        | B250M BAZOOKA               | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| MSI        | B450I GAMING PLUS AC        | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Gigabyte   | AB350M-D3H-CF               | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Gigabyte   | Z170X-GamingG1              | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Gigabyte   | Z77-D3H                     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo     | MAHOBAY                     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| Biostar    | B450MH                      | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| Gigabyte   | EG41MF-US2H                 | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.0-8-amd64                 | 51       | 44.74%  |
| 5.10.0-7-amd64                 | 38       | 33.33%  |
| 5.10.0-6-amd64                 | 9        | 7.89%   |
| 5.11.22-1-pve                  | 2        | 1.75%   |
| 5.8.0-3-amd64                  | 1        | 0.88%   |
| 5.13.4                         | 1        | 0.88%   |
| 5.13.1a                        | 1        | 0.88%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1        | 0.88%   |
| 5.11.22-2-pve                  | 1        | 0.88%   |
| 5.11.0-21.1-liquorix-amd64     | 1        | 0.88%   |
| 5.11.0-16.1-liquorix-amd64     | 1        | 0.88%   |
| 5.10.46custom                  | 1        | 0.88%   |
| 5.10.38-falcot                 | 1        | 0.88%   |
| 5.10.0-8-rt-amd64              | 1        | 0.88%   |
| 5.10.0-8-686                   | 1        | 0.88%   |
| 5.10.0-7-686-pae               | 1        | 0.88%   |
| 5.10.0-3-amd64                 | 1        | 0.88%   |
| 5.10.0-2-amd64                 | 1        | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 102      | 90.27%  |
| 5.11.22 | 3        | 2.65%   |
| 5.11.0  | 2        | 1.77%   |
| 5.8.0   | 1        | 0.88%   |
| 5.13.4  | 1        | 0.88%   |
| 5.13.1  | 1        | 0.88%   |
| 5.13.0  | 1        | 0.88%   |
| 5.10.46 | 1        | 0.88%   |
| 5.10.38 | 1        | 0.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 104      | 92.04%  |
| 5.11    | 5        | 4.42%   |
| 5.13    | 3        | 2.65%   |
| 5.8     | 1        | 0.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 111      | 98.23%  |
| i686   | 2        | 1.77%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KDE5             | 23       | 20.18%  |
| GNOME            | 23       | 20.18%  |
| XFCE             | 14       | 12.28%  |
| MATE             | 14       | 12.28%  |
| Unknown          | 11       | 9.65%   |
| i3               | 5        | 4.39%   |
| LXQt             | 4        | 3.51%   |
| KDE              | 4        | 3.51%   |
| Cinnamon         | 4        | 3.51%   |
| LXDE             | 3        | 2.63%   |
| X-Cinnamon       | 2        | 1.75%   |
| GNOME Flashback  | 2        | 1.75%   |
| Trinity          | 1        | 0.88%   |
| sway             | 1        | 0.88%   |
| lightdm-xsession | 1        | 0.88%   |
| GNUstep          | 1        | 0.88%   |
| Budgie           | 1        | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 82       | 72.57%  |
| Wayland | 14       | 12.39%  |
| Tty     | 13       | 11.5%   |
| Unknown | 4        | 3.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 39       | 34.21%  |
| GDM     | 23       | 20.18%  |
| Unknown | 23       | 20.18%  |
| SDDM    | 21       | 18.42%  |
| LightDM | 5        | 4.39%   |
| SLiM    | 2        | 1.75%   |
| XDM     | 1        | 0.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 54       | 47.79%  |
| ru_RU   | 8        | 7.08%   |
| fr_FR   | 8        | 7.08%   |
| en_GB   | 8        | 7.08%   |
| de_DE   | 5        | 4.42%   |
| C       | 4        | 3.54%   |
| pt_BR   | 3        | 2.65%   |
| pl_PL   | 3        | 2.65%   |
| en_CA   | 3        | 2.65%   |
| nl_BE   | 2        | 1.77%   |
| es_ES   | 2        | 1.77%   |
| en_AU   | 2        | 1.77%   |
| Unknown | 2        | 1.77%   |
| sv_SE   | 1        | 0.88%   |
| sr_RS   | 1        | 0.88%   |
| ru_UA   | 1        | 0.88%   |
| ro_RO   | 1        | 0.88%   |
| hu_HU   | 1        | 0.88%   |
| es_AR   | 1        | 0.88%   |
| en_PH   | 1        | 0.88%   |
| en_IN   | 1        | 0.88%   |
| en_HK   | 1        | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 58       | 50.88%  |
| BIOS | 56       | 49.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 88       | 77.88%  |
| Btrfs   | 11       | 9.73%   |
| Overlay | 5        | 4.42%   |
| Ext3    | 4        | 3.54%   |
| Zfs     | 3        | 2.65%   |
| Xfs     | 1        | 0.88%   |
| Unknown | 1        | 0.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 72       | 63.16%  |
| MBR     | 28       | 24.56%  |
| Unknown | 14       | 12.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 72.57%  |
| Yes       | 31       | 27.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 71.05%  |
| Yes       | 33       | 28.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 28       | 24.78%  |
| ASUSTek Computer    | 27       | 23.89%  |
| ASRock              | 16       | 14.16%  |
| MSI                 | 13       | 11.5%   |
| Dell                | 11       | 9.73%   |
| Hewlett-Packard     | 8        | 7.08%   |
| Lenovo              | 2        | 1.77%   |
| Intel               | 2        | 1.77%   |
| Huanan              | 2        | 1.77%   |
| Supermicro          | 1        | 0.88%   |
| Protectli           | 1        | 0.88%   |
| HARDKERNEL          | 1        | 0.88%   |
| Biostar             | 1        | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 4        | 3.54%   |
| Gigabyte B550I AORUS PRO AX       | 3        | 2.65%   |
| ASRock B450M Pro4                 | 3        | 2.65%   |
| HP Z620 Workstation               | 2        | 1.77%   |
| Gigabyte Z77-D3H                  | 2        | 1.77%   |
| Gigabyte Z370 AORUS Gaming 5      | 2        | 1.77%   |
| Dell OptiPlex 760                 | 2        | 1.77%   |
| ASUS PRIME B550-PLUS              | 2        | 1.77%   |
| ASUS PRIME B450M-A                | 2        | 1.77%   |
| Supermicro SYS-5038MA-H24TRF      | 1        | 0.88%   |
| Protectli FW6                     | 1        | 0.88%   |
| MSI MS-7C94                       | 1        | 0.88%   |
| MSI MS-7C56                       | 1        | 0.88%   |
| MSI MS-7C35                       | 1        | 0.88%   |
| MSI MS-7B89                       | 1        | 0.88%   |
| MSI MS-7B46                       | 1        | 0.88%   |
| MSI MS-7B09                       | 1        | 0.88%   |
| MSI MS-7A70                       | 1        | 0.88%   |
| MSI MS-7A40                       | 1        | 0.88%   |
| MSI MS-7995                       | 1        | 0.88%   |
| MSI MS-7823                       | 1        | 0.88%   |
| MSI MS-7759                       | 1        | 0.88%   |
| MSI MS-7721                       | 1        | 0.88%   |
| MSI MS-6712                       | 1        | 0.88%   |
| Lenovo ThinkCentre M92p 3209EK4   | 1        | 0.88%   |
| Lenovo ThinkCentre M73 10B00005US | 1        | 0.88%   |
| Intel DP55WG AAE57269-407         | 1        | 0.88%   |
| Intel DP55WB AAE64798-206         | 1        | 0.88%   |
| Huanan X99-F8                     | 1        | 0.88%   |
| Huanan X99-8M-F V1.1              | 1        | 0.88%   |
| HP Z840 Workstation               | 1        | 0.88%   |
| HP ProLiant MicroServer Gen8      | 1        | 0.88%   |
| HP ProLiant MicroServer           | 1        | 0.88%   |
| HP EliteDesk 705 G1 SFF           | 1        | 0.88%   |
| HP Compaq 8200 Elite SFF PC       | 1        | 0.88%   |
| HP 200-010hk                      | 1        | 0.88%   |
| HARDKERNEL ODROID-H2              | 1        | 0.88%   |
| Gigabyte Z97X-UD3H                | 1        | 0.88%   |
| Gigabyte Z170X-GamingG1           | 1        | 0.88%   |
| Gigabyte Z170M-D3H                | 1        | 0.88%   |
| Gigabyte X570 I AORUS PRO WIFI    | 1        | 0.88%   |
| Gigabyte P35C-DS3R                | 1        | 0.88%   |
| Gigabyte H87-HD3                  | 1        | 0.88%   |
| Gigabyte H81M-S2H GSM             | 1        | 0.88%   |
| Gigabyte H61MS                    | 1        | 0.88%   |
| Gigabyte H110N                    | 1        | 0.88%   |
| Gigabyte H110M-S2H                | 1        | 0.88%   |
| Gigabyte EG41MF-US2H              | 1        | 0.88%   |
| Gigabyte BRi7(H)-10710            | 1        | 0.88%   |
| Gigabyte B560M D3H                | 1        | 0.88%   |
| Gigabyte B450M DS3H               | 1        | 0.88%   |
| Gigabyte B450 AORUS PRO WIFI      | 1        | 0.88%   |
| Gigabyte AX370-Gaming K7          | 1        | 0.88%   |
| Gigabyte AB350M-Gaming 3          | 1        | 0.88%   |
| Gigabyte AB350M-DS3H V2           | 1        | 0.88%   |
| Gigabyte AB350M-D3H               | 1        | 0.88%   |
| Gigabyte AB350-Gaming 3           | 1        | 0.88%   |
| Gigabyte 970A-D3P                 | 1        | 0.88%   |
| Dell Precision WorkStation T3500  | 1        | 0.88%   |
| Dell Precision Tower 7910         | 1        | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS PRIME                   | 11       | 9.73%   |
| Dell OptiPlex                | 7        | 6.19%   |
| ASUS ROG                     | 5        | 4.42%   |
| Dell Precision               | 4        | 3.54%   |
| ASUS All                     | 4        | 3.54%   |
| Gigabyte B550I               | 3        | 2.65%   |
| ASRock B450M                 | 3        | 2.65%   |
| Lenovo ThinkCentre           | 2        | 1.77%   |
| HP Z620                      | 2        | 1.77%   |
| HP ProLiant                  | 2        | 1.77%   |
| Gigabyte Z77-D3H             | 2        | 1.77%   |
| Gigabyte Z370                | 2        | 1.77%   |
| ASRock Z97                   | 2        | 1.77%   |
| Supermicro SYS-5038MA-H24TRF | 1        | 0.88%   |
| Protectli FW6                | 1        | 0.88%   |
| MSI MS-7C94                  | 1        | 0.88%   |
| MSI MS-7C56                  | 1        | 0.88%   |
| MSI MS-7C35                  | 1        | 0.88%   |
| MSI MS-7B89                  | 1        | 0.88%   |
| MSI MS-7B46                  | 1        | 0.88%   |
| MSI MS-7B09                  | 1        | 0.88%   |
| MSI MS-7A70                  | 1        | 0.88%   |
| MSI MS-7A40                  | 1        | 0.88%   |
| MSI MS-7995                  | 1        | 0.88%   |
| MSI MS-7823                  | 1        | 0.88%   |
| MSI MS-7759                  | 1        | 0.88%   |
| MSI MS-7721                  | 1        | 0.88%   |
| MSI MS-6712                  | 1        | 0.88%   |
| Intel DP55WG                 | 1        | 0.88%   |
| Intel DP55WB                 | 1        | 0.88%   |
| Huanan X99-F8                | 1        | 0.88%   |
| Huanan X99-8M-F              | 1        | 0.88%   |
| HP Z840                      | 1        | 0.88%   |
| HP EliteDesk                 | 1        | 0.88%   |
| HP Compaq                    | 1        | 0.88%   |
| HP 200-010hk                 | 1        | 0.88%   |
| HARDKERNEL ODROID-H2         | 1        | 0.88%   |
| Gigabyte Z97X-UD3H           | 1        | 0.88%   |
| Gigabyte Z170X-GamingG1      | 1        | 0.88%   |
| Gigabyte Z170M-D3H           | 1        | 0.88%   |
| Gigabyte X570                | 1        | 0.88%   |
| Gigabyte P35C-DS3R           | 1        | 0.88%   |
| Gigabyte H87-HD3             | 1        | 0.88%   |
| Gigabyte H81M-S2H            | 1        | 0.88%   |
| Gigabyte H61MS               | 1        | 0.88%   |
| Gigabyte H110N               | 1        | 0.88%   |
| Gigabyte H110M-S2H           | 1        | 0.88%   |
| Gigabyte EG41MF-US2H         | 1        | 0.88%   |
| Gigabyte BRi7(H)-10710       | 1        | 0.88%   |
| Gigabyte B560M               | 1        | 0.88%   |
| Gigabyte B450M               | 1        | 0.88%   |
| Gigabyte B450                | 1        | 0.88%   |
| Gigabyte AX370-Gaming        | 1        | 0.88%   |
| Gigabyte AB350M-Gaming       | 1        | 0.88%   |
| Gigabyte AB350M-DS3H         | 1        | 0.88%   |
| Gigabyte AB350M-D3H          | 1        | 0.88%   |
| Gigabyte AB350-Gaming        | 1        | 0.88%   |
| Gigabyte 970A-D3P            | 1        | 0.88%   |
| Biostar B450MH               | 1        | 0.88%   |
| ASUS Z170-DELUXE             | 1        | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 25       | 22.12%  |
| 2018 | 16       | 14.16%  |
| 2019 | 15       | 13.27%  |
| 2021 | 12       | 10.62%  |
| 2014 | 9        | 7.96%   |
| 2016 | 8        | 7.08%   |
| 2012 | 7        | 6.19%   |
| 2015 | 4        | 3.54%   |
| 2010 | 4        | 3.54%   |
| 2013 | 3        | 2.65%   |
| 2009 | 3        | 2.65%   |
| 2017 | 2        | 1.77%   |
| 2011 | 2        | 1.77%   |
| 2007 | 1        | 0.88%   |
| 2006 | 1        | 0.88%   |
| 2001 | 1        | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 113      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 110      | 97.35%  |
| Enabled  | 3        | 2.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 112      | 99.12%  |
| Yes  | 1        | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 41       | 36.28%  |
| 32.01-64.0      | 21       | 18.58%  |
| 8.01-16.0       | 18       | 15.93%  |
| 64.01-256.0     | 15       | 13.27%  |
| 4.01-8.0        | 8        | 7.08%   |
| 3.01-4.0        | 5        | 4.42%   |
| 1.01-2.0        | 2        | 1.77%   |
| More than 256.0 | 1        | 0.88%   |
| 24.01-32.0      | 1        | 0.88%   |
| 2.01-3.0        | 1        | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 25       | 22.12%  |
| 3.01-4.0   | 21       | 18.58%  |
| 2.01-3.0   | 17       | 15.04%  |
| 8.01-16.0  | 14       | 12.39%  |
| 1.01-2.0   | 13       | 11.5%   |
| 0.51-1.0   | 10       | 8.85%   |
| 16.01-24.0 | 4        | 3.54%   |
| 0.01-0.5   | 4        | 3.54%   |
| 24.01-32.0 | 3        | 2.65%   |
| 32.01-64.0 | 2        | 1.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 31       | 27.43%  |
| 1      | 27       | 23.89%  |
| 3      | 24       | 21.24%  |
| 4      | 13       | 11.5%   |
| 5      | 10       | 8.85%   |
| 9      | 3        | 2.65%   |
| 8      | 3        | 2.65%   |
| 6      | 2        | 1.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 52.21%  |
| Yes       | 54       | 47.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 112      | 99.12%  |
| No        | 1        | 0.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 65.49%  |
| Yes       | 39       | 34.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 73.45%  |
| Yes       | 30       | 26.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country       | Desktops | Percent |
|---------------|----------|---------|
| USA           | 26       | 23.01%  |
| France        | 10       | 8.85%   |
| Russia        | 9        | 7.96%   |
| Germany       | 8        | 7.08%   |
| UK            | 7        | 6.19%   |
| Ukraine       | 5        | 4.42%   |
| Poland        | 5        | 4.42%   |
| Spain         | 4        | 3.54%   |
| Mexico        | 3        | 2.65%   |
| Canada        | 3        | 2.65%   |
| Bulgaria      | 3        | 2.65%   |
| Brazil        | 3        | 2.65%   |
| Australia     | 3        | 2.65%   |
| Sweden        | 2        | 1.77%   |
| Hungary       | 2        | 1.77%   |
| Finland       | 2        | 1.77%   |
| Belgium       | 2        | 1.77%   |
| Argentina     | 2        | 1.77%   |
| Syria         | 1        | 0.88%   |
| Singapore     | 1        | 0.88%   |
| Serbia        | 1        | 0.88%   |
| Norway        | 1        | 0.88%   |
| New Caledonia | 1        | 0.88%   |
| Netherlands   | 1        | 0.88%   |
| Madagascar    | 1        | 0.88%   |
| Italy         | 1        | 0.88%   |
| India         | 1        | 0.88%   |
| Hong Kong     | 1        | 0.88%   |
| Greece        | 1        | 0.88%   |
| Ecuador       | 1        | 0.88%   |
| Czechia       | 1        | 0.88%   |
| Austria       | 1        | 0.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Sofia                       | 3        | 2.65%   |
| Lyon                        | 3        | 2.65%   |
| Ensenada                    | 3        | 2.65%   |
| Warsaw                      | 2        | 1.77%   |
| New York                    | 2        | 1.77%   |
| Las Vegas                   | 2        | 1.77%   |
| Kyiv                        | 2        | 1.77%   |
| Kalamazoo                   | 2        | 1.77%   |
| Athens                      | 2        | 1.77%   |
| Érd                        | 1        | 0.88%   |
| Woolloongabba               | 1        | 0.88%   |
| Woodstock                   | 1        | 0.88%   |
| Wenatchee                   | 1        | 0.88%   |
| Waregem                     | 1        | 0.88%   |
| Vienna                      | 1        | 0.88%   |
| Vancouver                   | 1        | 0.88%   |
| Vaasa                       | 1        | 0.88%   |
| Ulyanovsk                   | 1        | 0.88%   |
| Ufa                         | 1        | 0.88%   |
| Turku                       | 1        | 0.88%   |
| Toulouse                    | 1        | 0.88%   |
| Thionville                  | 1        | 0.88%   |
| Tai Kok Tsui                | 1        | 0.88%   |
| Stroud                      | 1        | 0.88%   |
| Strasbourg                  | 1        | 0.88%   |
| Stockholm                   | 1        | 0.88%   |
| Stavanger                   | 1        | 0.88%   |
| Sosnowiec                   | 1        | 0.88%   |
| Singapore                   | 1        | 0.88%   |
| Saratov                     | 1        | 0.88%   |
| San Francisco               | 1        | 0.88%   |
| San Cristóbal de La Laguna | 1        | 0.88%   |
| Saint-Denis                 | 1        | 0.88%   |
| Rochester                   | 1        | 0.88%   |
| Ribeirao Pires              | 1        | 0.88%   |
| Prague                      | 1        | 0.88%   |
| Phoenix                     | 1        | 0.88%   |
| Pforzheim                   | 1        | 0.88%   |
| Perth                       | 1        | 0.88%   |
| Perm                        | 1        | 0.88%   |
| Paris                       | 1        | 0.88%   |
| Orlando                     | 1        | 0.88%   |
| Oleksandrivka               | 1        | 0.88%   |
| Oldham                      | 1        | 0.88%   |
| Ocala                       | 1        | 0.88%   |
| Noumea                      | 1        | 0.88%   |
| Noblesville                 | 1        | 0.88%   |
| New Orleans                 | 1        | 0.88%   |
| Mytishchi                   | 1        | 0.88%   |
| Mesa                        | 1        | 0.88%   |
| Mannheim                    | 1        | 0.88%   |
| Mairena del Aljarafe        | 1        | 0.88%   |
| Madrid                      | 1        | 0.88%   |
| Lublin                      | 1        | 0.88%   |
| London                      | 1        | 0.88%   |
| Langenhagen                 | 1        | 0.88%   |
| Kozhikode                   | 1        | 0.88%   |
| Kiel                        | 1        | 0.88%   |
| Kharkiv                     | 1        | 0.88%   |
| Khabarovsk                  | 1        | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 49       | 76     | 22.48%  |
| Seagate             | 41       | 72     | 18.81%  |
| Samsung Electronics | 31       | 48     | 14.22%  |
| Crucial             | 15       | 17     | 6.88%   |
| Toshiba             | 14       | 28     | 6.42%   |
| Kingston            | 10       | 11     | 4.59%   |
| Sandisk             | 8        | 10     | 3.67%   |
| Intel               | 8        | 15     | 3.67%   |
| Hitachi             | 8        | 9      | 3.67%   |
| HGST                | 5        | 7      | 2.29%   |
| A-DATA Technology   | 4        | 6      | 1.83%   |
| Gigabyte Technology | 3        | 3      | 1.38%   |
| Unknown             | 2        | 2      | 0.92%   |
| SPCC                | 2        | 2      | 0.92%   |
| PNY                 | 2        | 2      | 0.92%   |
| Phison Electronics  | 2        | 2      | 0.92%   |
| Phison              | 2        | 2      | 0.92%   |
| Corsair             | 2        | 2      | 0.92%   |
| Transcend           | 1        | 2      | 0.46%   |
| Team                | 1        | 1      | 0.46%   |
| SK Hynix            | 1        | 2      | 0.46%   |
| Patriot             | 1        | 1      | 0.46%   |
| MaxDigital          | 1        | 2      | 0.46%   |
| Lexar               | 1        | 1      | 0.46%   |
| KingDian            | 1        | 1      | 0.46%   |
| Intenso             | 1        | 1      | 0.46%   |
| DOGFISH             | 1        | 1      | 0.46%   |
| China               | 1        | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB          | 7        | 2.56%   |
| Samsung SSD 970 EVO Plus 500GB   | 4        | 1.47%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 3        | 1.1%    |
| WDC WDS500G2B0A-00SM50 500GB SSD | 3        | 1.1%    |
| WDC WDS120G2G0A-00JH30 120GB SSD | 3        | 1.1%    |
| Toshiba HDWD110 1TB              | 3        | 1.1%    |
| Toshiba DT01ACA200 2TB           | 3        | 1.1%    |
| Seagate ST4000DM004-2CV104 4TB   | 3        | 1.1%    |
| Samsung SSD 970 EVO Plus 1TB     | 3        | 1.1%    |
| Samsung SSD 850 EVO 500GB        | 3        | 1.1%    |
| Samsung SSD 850 EVO 250GB        | 3        | 1.1%    |
| Kingston SV300S37A240G 240GB SSD | 3        | 1.1%    |
| Hitachi HUS724040ALE641 4TB      | 3        | 1.1%    |
| WDC WDS500G2B0C-00PXH0 500GB     | 2        | 0.73%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2        | 0.73%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.73%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 0.73%   |
| WDC WD10EFRX-68FYTN0 1TB         | 2        | 0.73%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 2        | 0.73%   |
| Toshiba DT01ACA300 3TB           | 2        | 0.73%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 0.73%   |
| Seagate ST3000DM001-1CH166 3TB   | 2        | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 0.73%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 0.73%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 0.73%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 0.73%   |
| Seagate BUP Slim BL 2TB          | 2        | 0.73%   |
| Sandisk NVMe SSD Drive 1TB       | 2        | 0.73%   |
| Samsung SSD 970 EVO 500GB        | 2        | 0.73%   |
| Samsung SSD 860 EVO 2TB          | 2        | 0.73%   |
| Samsung SSD 860 EVO 250GB        | 2        | 0.73%   |
| Samsung SSD 840 PRO Series 256GB | 2        | 0.73%   |
| Samsung HD103SJ 1TB              | 2        | 0.73%   |
| Phison PCIe SSD 512GB            | 2        | 0.73%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 0.73%   |
| Kingston SUV500240G 240GB SSD    | 2        | 0.73%   |
| Intel SSDPEKNW010T9 1TB          | 2        | 0.73%   |
| Intel NVMe SSD Drive 1024GB      | 2        | 0.73%   |
| Intel MEMPEK1J016GAL 16GB        | 2        | 0.73%   |
| Crucial CT500P2SSD8 500GB        | 2        | 0.73%   |
| Crucial CT500P1SSD8 500GB        | 2        | 0.73%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 0.73%   |
| WDC WUH721414ALE6L4 14TB         | 1        | 0.37%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 0.37%   |
| WDC WDS500G1B0C-00S6U0 500GB     | 1        | 0.37%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD | 1        | 0.37%   |
| WDC WDS200T2B0B-00YS70 2TB SSD   | 1        | 0.37%   |
| WDC WDBRPG5000ANC-WRSN 500GB     | 1        | 0.37%   |
| WDC WD6001FZWX-00A2VA0 6TB       | 1        | 0.37%   |
| WDC WD5003ABYX-18WERA0 500GB     | 1        | 0.37%   |
| WDC WD5000AZRX-00A8LB0 500GB     | 1        | 0.37%   |
| WDC WD5000AVCS-632DY1 500GB      | 1        | 0.37%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.37%   |
| WDC WD5000AAKS-22V1A0 500GB      | 1        | 0.37%   |
| WDC WD5000AAJS-22A8B0 500GB      | 1        | 0.37%   |
| WDC WD5000AADS-00S9B0 500GB      | 1        | 0.37%   |
| WDC WD5000A 500GB                | 1        | 0.37%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1        | 0.37%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 39       | 61     | 36.11%  |
| WDC                 | 38       | 60     | 35.19%  |
| Toshiba             | 12       | 25     | 11.11%  |
| Hitachi             | 8        | 9      | 7.41%   |
| Samsung Electronics | 5        | 6      | 4.63%   |
| HGST                | 5        | 7      | 4.63%   |
| MaxDigital          | 1        | 2      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 20       | 27     | 27.78%  |
| Crucial             | 11       | 12     | 15.28%  |
| Kingston            | 10       | 11     | 13.89%  |
| WDC                 | 8        | 9      | 11.11%  |
| SanDisk             | 5        | 6      | 6.94%   |
| A-DATA Technology   | 4        | 5      | 5.56%   |
| Toshiba             | 2        | 3      | 2.78%   |
| Unknown             | 1        | 1      | 1.39%   |
| Transcend           | 1        | 2      | 1.39%   |
| Team                | 1        | 1      | 1.39%   |
| SPCC                | 1        | 1      | 1.39%   |
| Seagate             | 1        | 1      | 1.39%   |
| PNY                 | 1        | 1      | 1.39%   |
| Patriot             | 1        | 1      | 1.39%   |
| Lexar               | 1        | 1      | 1.39%   |
| KingDian            | 1        | 1      | 1.39%   |
| Gigabyte Technology | 1        | 1      | 1.39%   |
| DOGFISH             | 1        | 1      | 1.39%   |
| China               | 1        | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 84       | 170    | 42%     |
| SSD     | 67       | 86     | 33.5%   |
| NVMe    | 44       | 59     | 22%     |
| Unknown | 4        | 11     | 2%      |
| MMC     | 1        | 1      | 0.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 100      | 250    | 64.94%  |
| NVMe | 44       | 59     | 28.57%  |
| SAS  | 9        | 17     | 5.84%   |
| MMC  | 1        | 1      | 0.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 65       | 99     | 39.39%  |
| 0.51-1.0   | 48       | 67     | 29.09%  |
| 1.01-2.0   | 26       | 34     | 15.76%  |
| 3.01-4.0   | 11       | 24     | 6.67%   |
| 2.01-3.0   | 7        | 12     | 4.24%   |
| 4.01-10.0  | 6        | 17     | 3.64%   |
| 10.01-20.0 | 2        | 3      | 1.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 25       | 22.12%  |
| 251-500        | 22       | 19.47%  |
| 501-1000       | 17       | 15.04%  |
| 1001-2000      | 16       | 14.16%  |
| 101-250        | 10       | 8.85%   |
| 1-20           | 8        | 7.08%   |
| 2001-3000      | 7        | 6.19%   |
| 21-50          | 3        | 2.65%   |
| Unknown        | 3        | 2.65%   |
| 51-100         | 2        | 1.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 24       | 21.05%  |
| 101-250        | 17       | 14.91%  |
| 251-500        | 14       | 12.28%  |
| More than 3000 | 12       | 10.53%  |
| 501-1000       | 12       | 10.53%  |
| 1001-2000      | 10       | 8.77%   |
| 51-100         | 8        | 7.02%   |
| 21-50          | 7        | 6.14%   |
| 2001-3000      | 6        | 5.26%   |
| Unknown        | 3        | 2.63%   |
| 0              | 1        | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5003ABYX-18WERA0 500GB          | 1        | 2      | 2.86%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 2.86%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1        | 1      | 2.86%   |
| WDC WD5000AAJS-22A8B0 500GB           | 1        | 1      | 2.86%   |
| WDC WD400BB-00DEA0 40GB               | 1        | 1      | 2.86%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 2.86%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 2.86%   |
| WDC WD20EARS-00MVWB0 2TB              | 1        | 1      | 2.86%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1        | 1      | 2.86%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1        | 1      | 2.86%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 2.86%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 2.86%   |
| WDC WD1001FALS-75J7B0 1TB             | 1        | 1      | 2.86%   |
| Toshiba MK2565GSX 250GB               | 1        | 1      | 2.86%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 2.86%   |
| SK Hynix PC401 NVMe 512GB             | 1        | 2      | 2.86%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 2.86%   |
| Seagate ST3200827AS 200GB             | 1        | 1      | 2.86%   |
| Seagate ST32000542AS 2TB              | 1        | 1      | 2.86%   |
| Seagate ST31500341AS 1TB              | 1        | 1      | 2.86%   |
| Seagate ST3120827AS 120GB             | 1        | 1      | 2.86%   |
| Seagate ST31000333AS 1TB              | 1        | 1      | 2.86%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 2.86%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 2.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 2.86%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 2.86%   |
| SanDisk SSD PLUS 120 GB               | 1        | 1      | 2.86%   |
| Samsung Electronics SSD 970 EVO 250GB | 1        | 1      | 2.86%   |
| Samsung Electronics HD161GJ 160GB     | 1        | 1      | 2.86%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 2.86%   |
| KingDian S280 240GB                   | 1        | 1      | 2.86%   |
| Intel SSDPEKKW010T7 1TB               | 1        | 2      | 2.86%   |
| Hitachi HDS722525VLAT80 250GB         | 1        | 1      | 2.86%   |
| A-DATA Technology SU800 256GB SSD     | 1        | 2      | 2.86%   |
| A-DATA Technology SSD DP900 128GB-DL3 | 1        | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 15     | 38.24%  |
| Seagate             | 9        | 10     | 26.47%  |
| Toshiba             | 2        | 2      | 5.88%   |
| Samsung Electronics | 2        | 2      | 5.88%   |
| A-DATA Technology   | 2        | 3      | 5.88%   |
| SK Hynix            | 1        | 2      | 2.94%   |
| SanDisk             | 1        | 1      | 2.94%   |
| Kingston            | 1        | 1      | 2.94%   |
| KingDian            | 1        | 1      | 2.94%   |
| Intel               | 1        | 2      | 2.94%   |
| Hitachi             | 1        | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 15     | 50%     |
| Seagate             | 9        | 10     | 34.62%  |
| Toshiba             | 2        | 2      | 7.69%   |
| Samsung Electronics | 1        | 1      | 3.85%   |
| Hitachi             | 1        | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 29     | 75.76%  |
| SSD  | 5        | 6      | 15.15%  |
| NVMe | 3        | 5      | 9.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500830AS 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 97       | 244    | 65.99%  |
| Malfunc  | 31       | 40     | 21.09%  |
| Detected | 18       | 42     | 12.24%  |
| Failed   | 1        | 1      | 0.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 70       | 40.94%  |
| AMD                       | 45       | 26.32%  |
| Samsung Electronics       | 14       | 8.19%   |
| Sandisk                   | 9        | 5.26%   |
| Phison Electronics        | 9        | 5.26%   |
| ASMedia Technology        | 6        | 3.51%   |
| Micron/Crucial Technology | 5        | 2.92%   |
| Marvell Technology Group  | 4        | 2.34%   |
| JMicron Technology        | 2        | 1.17%   |
| Broadcom / LSI            | 2        | 1.17%   |
| VIA Technologies          | 1        | 0.58%   |
| SK Hynix                  | 1        | 0.58%   |
| Seagate Technology        | 1        | 0.58%   |
| ADATA Technology          | 1        | 0.58%   |
| Adaptec                   | 1        | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 31       | 13.9%   |
| AMD 400 Series Chipset SATA Controller                                                  | 14       | 6.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 5.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 4.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 3.59%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 3.59%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 8        | 3.59%   |
| Phison E12 NVMe Controller                                                              | 6        | 2.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.24%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 2.24%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 2.24%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4        | 1.79%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.79%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.79%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 1.35%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 3        | 1.35%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.9%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.9%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.9%    |
| Intel SSD 600P Series                                                                   | 2        | 0.9%    |
| Intel NVMe Optane Memory Series                                                         | 2        | 0.9%    |
| Intel Non-Volatile memory controller                                                    | 2        | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.9%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.9%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.9%    |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 0.9%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.9%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.9%    |
| AMD X399 Series Chipset SATA Controller                                                 | 2        | 0.9%    |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 0.9%    |
| AMD FCH SATA Controller D                                                               | 2        | 0.9%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.45%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                             | 1        | 0.45%   |
| Seagate FireCuda 510 SSD                                                                | 1        | 0.45%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 0.45%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.45%   |
| Samsung NVMe Controller                                                                 | 1        | 0.45%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.45%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.45%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.45%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.45%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                                   | 1        | 0.45%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.45%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.45%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 0.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.45%   |
| Intel SSD 660P Series                                                                   | 1        | 0.45%   |
| Intel PCIe Data Center SSD                                                              | 1        | 0.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.45%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 0.45%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.45%   |
| Intel C608 chipset Dual 4-Port SATA/SAS Storage Control Unit                            | 1        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 98       | 56%     |
| NVMe | 44       | 25.14%  |
| IDE  | 19       | 10.86%  |
| RAID | 9        | 5.14%   |
| SAS  | 5        | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 67       | 59.29%  |
| AMD    | 46       | 40.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 9        | 7.96%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 4        | 3.54%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 3        | 2.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 2.65%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 3        | 2.65%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2        | 1.77%   |
| Intel Core i5-6600 CPU @ 3.30GHz       | 2        | 1.77%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 2        | 1.77%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 2        | 1.77%   |
| Intel Core i5-2500K CPU @ 3.30GHz      | 2        | 1.77%   |
| Intel Core i5 CPU 650 @ 3.20GHz        | 2        | 1.77%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz  | 2        | 1.77%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 2        | 1.77%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 2        | 1.77%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 2        | 1.77%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 2        | 1.77%   |
| Intel Xeon W-2145 CPU @ 3.70GHz        | 1        | 0.88%   |
| Intel Xeon CPU W3503 @ 2.40GHz         | 1        | 0.88%   |
| Intel Xeon CPU E5-2699 v4 @ 2.20GHz    | 1        | 0.88%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz    | 1        | 0.88%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz    | 1        | 0.88%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz     | 1        | 0.88%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz    | 1        | 0.88%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz     | 1        | 0.88%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz     | 1        | 0.88%   |
| Intel Pentium CPU G2030 @ 3.00GHz      | 1        | 0.88%   |
| Intel Pentium 4 CPU 2.80GHz            | 1        | 0.88%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 1        | 0.88%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 0.88%   |
| Intel Core i7-8086K CPU @ 4.00GHz      | 1        | 0.88%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 1        | 0.88%   |
| Intel Core i7-4790S CPU @ 3.20GHz      | 1        | 0.88%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1        | 0.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 1        | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 0.88%   |
| Intel Core i7-10710U CPU @ 1.10GHz     | 1        | 0.88%   |
| Intel Core i7 CPU 860 @ 2.80GHz        | 1        | 0.88%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 1        | 0.88%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 1        | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1        | 0.88%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 1        | 0.88%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 1        | 0.88%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 0.88%   |
| Intel Core i5-4430 CPU @ 3.00GHz       | 1        | 0.88%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 1        | 0.88%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 1        | 0.88%   |
| Intel Core i5-3550 CPU @ 3.30GHz       | 1        | 0.88%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1        | 0.88%   |
| Intel Core i5-3450 CPU @ 3.10GHz       | 1        | 0.88%   |
| Intel Core i5-2500 CPU @ 3.30GHz       | 1        | 0.88%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 1        | 0.88%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 1        | 0.88%   |
| Intel Core i3-4170 CPU @ 3.70GHz       | 1        | 0.88%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 1        | 0.88%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 1        | 0.88%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz   | 1        | 0.88%   |
| Intel Celeron J4115 CPU @ 1.80GHz      | 1        | 0.88%   |
| Intel Celeron CPU G1610T @ 2.30GHz     | 1        | 0.88%   |
| Intel Celeron 2957U @ 1.40GHz          | 1        | 0.88%   |
| Intel Atom CPU C2750 @ 2.40GHz         | 1        | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 27       | 23.89%  |
| AMD Ryzen 5            | 17       | 15.04%  |
| Intel Core i7          | 14       | 12.39%  |
| AMD Ryzen 7            | 11       | 9.73%   |
| Intel Xeon             | 9        | 7.96%   |
| Intel Core i3          | 4        | 3.54%   |
| AMD Ryzen 9            | 4        | 3.54%   |
| Intel Core 2 Duo       | 3        | 2.65%   |
| Intel Celeron          | 3        | 2.65%   |
| Intel Core 2 Quad      | 2        | 1.77%   |
| AMD Ryzen Threadripper | 2        | 1.77%   |
| AMD Ryzen 3            | 2        | 1.77%   |
| AMD Phenom II X4       | 2        | 1.77%   |
| AMD FX                 | 2        | 1.77%   |
| Other                  | 1        | 0.88%   |
| Intel Pentium 4        | 1        | 0.88%   |
| Intel Pentium          | 1        | 0.88%   |
| Intel Core i9          | 1        | 0.88%   |
| Intel Atom             | 1        | 0.88%   |
| AMD Athlon XP          | 1        | 0.88%   |
| AMD Athlon X4          | 1        | 0.88%   |
| AMD Athlon II Neo      | 1        | 0.88%   |
| AMD A8                 | 1        | 0.88%   |
| AMD A6                 | 1        | 0.88%   |
| AMD A10                | 1        | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 42       | 37.17%  |
| 6      | 26       | 23.01%  |
| 2      | 17       | 15.04%  |
| 8      | 15       | 13.27%  |
| 12     | 5        | 4.42%   |
| 1      | 3        | 2.65%   |
| 16     | 2        | 1.77%   |
| 44     | 1        | 0.88%   |
| 32     | 1        | 0.88%   |
| 28     | 1        | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 110      | 97.35%  |
| 2      | 3        | 2.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 69       | 61.06%  |
| 1      | 44       | 38.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 111      | 98.23%  |
| 32-bit         | 2        | 1.77%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 25       | 21.93%  |
| 0x08701021 | 14       | 12.28%  |
| 0x306c3    | 11       | 9.65%   |
| 0x306a9    | 6        | 5.26%   |
| 0x506e3    | 5        | 4.39%   |
| 0x206a7    | 5        | 4.39%   |
| 0x906e9    | 4        | 3.51%   |
| 0x306f2    | 3        | 2.63%   |
| 0x206d7    | 3        | 2.63%   |
| 0x0800820d | 3        | 2.63%   |
| 0x08001138 | 3        | 2.63%   |
| 0x06003106 | 3        | 2.63%   |
| 0x6fb      | 2        | 1.75%   |
| 0x0a201009 | 2        | 1.75%   |
| 0x08701013 | 2        | 1.75%   |
| 0x010000c8 | 2        | 1.75%   |
| 0xf29      | 1        | 0.88%   |
| 0xa0671    | 1        | 0.88%   |
| 0xa0660    | 1        | 0.88%   |
| 0xa0653    | 1        | 0.88%   |
| 0x906ed    | 1        | 0.88%   |
| 0x906ec    | 1        | 0.88%   |
| 0x906ea    | 1        | 0.88%   |
| 0x806e9    | 1        | 0.88%   |
| 0x706a1    | 1        | 0.88%   |
| 0x50654    | 1        | 0.88%   |
| 0x406f1    | 1        | 0.88%   |
| 0x406d8    | 1        | 0.88%   |
| 0x40651    | 1        | 0.88%   |
| 0x20655    | 1        | 0.88%   |
| 0x106e5    | 1        | 0.88%   |
| 0x106a5    | 1        | 0.88%   |
| 0x1067a    | 1        | 0.88%   |
| 0x0a201016 | 1        | 0.88%   |
| 0x0800820b | 1        | 0.88%   |
| 0x08001137 | 1        | 0.88%   |
| 0x0600063e | 1        | 0.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 21       | 18.58%  |
| Haswell       | 16       | 14.16%  |
| KabyLake      | 11       | 9.73%   |
| Skylake       | 8        | 7.08%   |
| SandyBridge   | 8        | 7.08%   |
| IvyBridge     | 8        | 7.08%   |
| Zen+          | 7        | 6.19%   |
| Zen 3         | 4        | 3.54%   |
| Zen           | 4        | 3.54%   |
| Steamroller   | 4        | 3.54%   |
| K10           | 3        | 2.65%   |
| Core          | 3        | 2.65%   |
| Westmere      | 2        | 1.77%   |
| Penryn        | 2        | 1.77%   |
| Nehalem       | 2        | 1.77%   |
| CometLake     | 2        | 1.77%   |
| Silvermont    | 1        | 0.88%   |
| Piledriver    | 1        | 0.88%   |
| NetBurst      | 1        | 0.88%   |
| K6            | 1        | 0.88%   |
| Goldmont plus | 1        | 0.88%   |
| Bulldozer     | 1        | 0.88%   |
| Broadwell     | 1        | 0.88%   |
| Unknown       | 1        | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 50       | 43.1%   |
| AMD                        | 35       | 30.17%  |
| Intel                      | 29       | 25%     |
| Matrox Electronics Systems | 1        | 0.86%   |
| ASPEED Technology          | 1        | 0.86%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 10.26%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 4.27%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 3.42%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 3.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 3.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 3.42%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 3.42%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 3.42%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 3.42%   |
| Intel HD Graphics 530                                                       | 3        | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.56%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.71%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.71%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.71%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 2        | 1.71%   |
| Nvidia G98 [Quadro NVS 295]                                                 | 2        | 1.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.71%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 1.71%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.71%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.71%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.85%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.85%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.85%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.85%   |
| Nvidia GV100GL [Quadro GV100]                                               | 1        | 0.85%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.85%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.85%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.85%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.85%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 0.85%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 0.85%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.85%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.85%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 0.85%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 0.85%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 0.85%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                       | 1        | 0.85%   |
| Nvidia GF110 [GeForce GTX 560 Ti 448 Cores]                                 | 1        | 0.85%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 0.85%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.85%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 0.85%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.85%   |
| Nvidia G92 [GeForce GTS 250]                                                | 1        | 0.85%   |
| Matrox Electronics Systems MGA G200EH                                       | 1        | 0.85%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 0.85%   |
| Intel HD Graphics 630                                                       | 1        | 0.85%   |
| Intel HD Graphics 620                                                       | 1        | 0.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 0.85%   |
| Intel Comet Lake UHD Graphics                                               | 1        | 0.85%   |
| Intel 82865G Integrated Graphics Controller                                 | 1        | 0.85%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 0.85%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 0.85%   |
| AMD Turks [Radeon HD 7600 Series]                                           | 1        | 0.85%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 1        | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 47       | 41.59%  |
| 1 x AMD        | 33       | 29.2%   |
| 1 x Intel      | 27       | 23.89%  |
| Intel + Nvidia | 2        | 1.77%   |
| 2 x AMD        | 1        | 0.88%   |
| 1 x Matrox     | 1        | 0.88%   |
| 1 x ASPEED     | 1        | 0.88%   |
| AMD + Nvidia   | 1        | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 78       | 69.03%  |
| Proprietary | 33       | 29.2%   |
| Unknown     | 2        | 1.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 47       | 41.23%  |
| 7.01-8.0   | 16       | 14.04%  |
| 1.01-2.0   | 15       | 13.16%  |
| 3.01-4.0   | 12       | 10.53%  |
| 0.51-1.0   | 7        | 6.14%   |
| 5.01-6.0   | 6        | 5.26%   |
| 0.01-0.5   | 6        | 5.26%   |
| 2.01-3.0   | 2        | 1.75%   |
| 24.01-32.0 | 1        | 0.88%   |
| 16.01-24.0 | 1        | 0.88%   |
| 8.01-16.0  | 1        | 0.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 20       | 15.38%  |
| Dell                 | 19       | 14.62%  |
| Samsung Electronics  | 18       | 13.85%  |
| Acer                 | 12       | 9.23%   |
| Ancor Communications | 11       | 8.46%   |
| BenQ                 | 8        | 6.15%   |
| Philips              | 7        | 5.38%   |
| Hewlett-Packard      | 7        | 5.38%   |
| AOC                  | 5        | 3.85%   |
| ASUSTek Computer     | 4        | 3.08%   |
| Unknown              | 2        | 1.54%   |
| LG Electronics       | 2        | 1.54%   |
| Iiyama               | 2        | 1.54%   |
| Vestel Elektronik    | 1        | 0.77%   |
| Sony                 | 1        | 0.77%   |
| ODH                  | 1        | 0.77%   |
| MIT                  | 1        | 0.77%   |
| Mi                   | 1        | 0.77%   |
| Medion               | 1        | 0.77%   |
| Lenovo               | 1        | 0.77%   |
| JVC                  | 1        | 0.77%   |
| INFOTRONIC           | 1        | 0.77%   |
| Idek Iiyama          | 1        | 0.77%   |
| Hitachi              | 1        | 0.77%   |
| Eizo                 | 1        | 0.77%   |
| Belinea              | 1        | 0.77%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3        | 2.16%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2        | 1.44%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2        | 1.44%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 1.44%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 2        | 1.44%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2        | 1.44%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2        | 1.44%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2        | 1.44%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 2        | 1.44%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 2        | 1.44%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2        | 1.44%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.72%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1        | 0.72%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.72%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch      | 1        | 0.72%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1        | 0.72%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch    | 1        | 0.72%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1        | 0.72%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch   | 1        | 0.72%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch     | 1        | 0.72%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1        | 0.72%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch      | 1        | 0.72%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 0.72%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch       | 1        | 0.72%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.72%   |
| Samsung Electronics LF27T850 SAM704F 2560x1440 597x336mm 27.0-inch     | 1        | 0.72%   |
| Samsung Electronics LCD Monitor SyncMaster 5760x1080                   | 1        | 0.72%   |
| Samsung Electronics LCD Monitor SMB2430L                               | 1        | 0.72%   |
| Samsung Electronics LCD Monitor SAM0BC9 1920x1080 600x340mm 27.2-inch  | 1        | 0.72%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 0.72%   |
| Samsung Electronics LCD Monitor C24F390 3360x1080                      | 1        | 0.72%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1        | 0.72%   |
| Samsung Electronics C24FG70 SAM0D58 1920x1080 532x304mm 24.1-inch      | 1        | 0.72%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1        | 0.72%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.72%   |
| Philips PHL 242E1GZ PHLC24C 1920x1080 527x296mm 23.8-inch              | 1        | 0.72%   |
| Philips PHL 241E1 PHLC207 1920x1080 530x300mm 24.0-inch                | 1        | 0.72%   |
| Philips LCD Monitor PHLC0B8 1920x1080 600x340mm 27.2-inch              | 1        | 0.72%   |
| Philips LCD Monitor PHL0850 1680x1050 470x300mm 22.0-inch              | 1        | 0.72%   |
| Philips 240S PHL087D 1920x1200 519x324mm 24.1-inch                     | 1        | 0.72%   |
| ODH LM24 ODH2492 1920x1080 345x259mm 17.0-inch                         | 1        | 0.72%   |
| MIT LCD Monitor MIT2015 3840x2160 520x330mm 24.2-inch                  | 1        | 0.72%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1        | 0.72%   |
| Medion MD41077EA MED078B 1280x1024 330x270mm 16.8-inch                 | 1        | 0.72%   |
| LG Electronics LCD Monitor LG IPS FULLHD                               | 1        | 0.72%   |
| LG Electronics LCD Monitor LG HDR QHD 4480x1440                        | 1        | 0.72%   |
| LG Electronics LCD Monitor 27GL850 2560x1440                           | 1        | 0.72%   |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch               | 1        | 0.72%   |
| JVC EM32FL AMR1007 1920x1080 700x390mm 31.5-inch                       | 1        | 0.72%   |
| INFOTRONIC L2130 ITR8852 1600x1200 432x324mm 21.3-inch                 | 1        | 0.72%   |
| Iiyama PL2790 IVM6616 1920x1080 598x336mm 27.0-inch                    | 1        | 0.72%   |
| Iiyama PL2480H IVM610B 1920x1080 520x290mm 23.4-inch                   | 1        | 0.72%   |
| Idek Iiyama LCD Monitor PL2492H                                        | 1        | 0.72%   |
| Hitachi HDMI    HEC0088 1920x1080 1100x560mm 48.6-inch                 | 1        | 0.72%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch             | 1        | 0.72%   |
| Hewlett-Packard Z23i HWP308F 1920x1080 509x286mm 23.0-inch             | 1        | 0.72%   |
| Hewlett-Packard V20 HPN36B3 1600x900 440x240mm 19.7-inch               | 1        | 0.72%   |
| Hewlett-Packard LCD Monitor w2007 1680x1050                            | 1        | 0.72%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 1        | 0.72%   |
| Goldstar WX942 GSM4B80 1440x900 408x255mm 18.9-inch                    | 1        | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 49       | 38.58%  |
| 2560x1440 (QHD)    | 15       | 11.81%  |
| 3840x2160 (4K)     | 13       | 10.24%  |
| 1280x1024 (SXGA)   | 8        | 6.3%    |
| 1680x1050 (WSXGA+) | 7        | 5.51%   |
| 1920x1200 (WUXGA)  | 5        | 3.94%   |
| 1600x900 (HD+)     | 4        | 3.15%   |
| 1366x768 (WXGA)    | 4        | 3.15%   |
| Unknown            | 4        | 3.15%   |
| 2560x1080          | 3        | 2.36%   |
| 1440x900 (WXGA+)   | 3        | 2.36%   |
| 2560x1600          | 2        | 1.57%   |
| 2288x1287          | 2        | 1.57%   |
| 1600x1200          | 2        | 1.57%   |
| 7680x4320          | 1        | 0.79%   |
| 5760x1080          | 1        | 0.79%   |
| 4480x1440          | 1        | 0.79%   |
| 3440x1440          | 1        | 0.79%   |
| 3360x1080          | 1        | 0.79%   |
| 1920x540           | 1        | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 25       | 19.38%  |
| 27      | 23       | 17.83%  |
| 23      | 18       | 13.95%  |
| Unknown | 11       | 8.53%   |
| 21      | 8        | 6.2%    |
| 31      | 7        | 5.43%   |
| 18      | 6        | 4.65%   |
| 17      | 6        | 4.65%   |
| 34      | 4        | 3.1%    |
| 20      | 4        | 3.1%    |
| 19      | 4        | 3.1%    |
| 22      | 3        | 2.33%   |
| 142     | 2        | 1.55%   |
| 29      | 2        | 1.55%   |
| 84      | 1        | 0.78%   |
| 55      | 1        | 0.78%   |
| 48      | 1        | 0.78%   |
| 28      | 1        | 0.78%   |
| 25      | 1        | 0.78%   |
| 16      | 1        | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 57       | 46.72%  |
| 401-500        | 24       | 19.67%  |
| 601-700        | 12       | 9.84%   |
| Unknown        | 11       | 9.02%   |
| 301-350        | 7        | 5.74%   |
| 701-800        | 4        | 3.28%   |
| More than 2000 | 2        | 1.64%   |
| 351-400        | 2        | 1.64%   |
| 1001-1500      | 2        | 1.64%   |
| 1501-2000      | 1        | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 76       | 63.33%  |
| 16/10   | 14       | 11.67%  |
| Unknown | 10       | 8.33%   |
| 5/4     | 7        | 5.83%   |
| 21/9    | 4        | 3.33%   |
| 4/3     | 3        | 2.5%    |
| 3/2     | 2        | 1.67%   |
| 1.00    | 2        | 1.67%   |
| 6/5     | 1        | 0.83%   |
| 1.96    | 1        | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 40       | 32.52%  |
| 301-350        | 23       | 18.7%   |
| 351-500        | 14       | 11.38%  |
| 151-200        | 11       | 8.94%   |
| Unknown        | 11       | 8.94%   |
| 141-150        | 9        | 7.32%   |
| 251-300        | 8        | 6.5%    |
| More than 1000 | 4        | 3.25%   |
| 131-140        | 2        | 1.63%   |
| 501-1000       | 1        | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 71       | 61.21%  |
| 101-120 | 17       | 14.66%  |
| Unknown | 11       | 9.48%   |
| 121-160 | 8        | 6.9%    |
| 161-240 | 6        | 5.17%   |
| 1-50    | 3        | 2.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 75       | 66.37%  |
| 2     | 26       | 23.01%  |
| 0     | 7        | 6.19%   |
| 3     | 4        | 3.54%   |
| 4     | 1        | 0.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 63       | 42.57%  |
| Intel                      | 59       | 39.86%  |
| Qualcomm Atheros           | 8        | 5.41%   |
| Broadcom                   | 6        | 4.05%   |
| Ralink Technology          | 3        | 2.03%   |
| ZTE WCDMA Technologies MSM | 1        | 0.68%   |
| TP-Link                    | 1        | 0.68%   |
| Ralink                     | 1        | 0.68%   |
| Microsoft                  | 1        | 0.68%   |
| Mellanox Technologies      | 1        | 0.68%   |
| Marvell Technology Group   | 1        | 0.68%   |
| Edimax Technology          | 1        | 0.68%   |
| D-Link                     | 1        | 0.68%   |
| Broadcom Limited           | 1        | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 50       | 29.59%  |
| Intel I211 Gigabit Network Connection                               | 11       | 6.51%   |
| Intel Ethernet Connection (2) I219-V                                | 9        | 5.33%   |
| Realtek RTL8125 2.5GbE Controller                                   | 7        | 4.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 7        | 4.14%   |
| Intel Wi-Fi 6 AX200                                                 | 5        | 2.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 5        | 2.96%   |
| Intel Ethernet Connection (2) I218-V                                | 3        | 1.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 1.18%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 1.18%   |
| Intel Wireless 8260                                                 | 2        | 1.18%   |
| Intel Wireless 3165                                                 | 2        | 1.18%   |
| Intel I210 Gigabit Network Connection                               | 2        | 1.18%   |
| Intel Ethernet Connection I217-V                                    | 2        | 1.18%   |
| Intel 82574L Gigabit Network Connection                             | 2        | 1.18%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 1.18%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                       | 1        | 0.59%   |
| TP-Link Archer T4U ver.3                                            | 1        | 0.59%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.59%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 0.59%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1        | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1        | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.59%   |
| Realtek 802.11ac NIC                                                | 1        | 0.59%   |
| Ralink RT5372 Wireless Adapter                                      | 1        | 0.59%   |
| Ralink RT5370 Wireless Adapter                                      | 1        | 0.59%   |
| Ralink MT7601U Wireless Adapter                                     | 1        | 0.59%   |
| Ralink RT5392 PCIe Wireless Network Adapter                         | 1        | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 1        | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 0.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.59%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 0.59%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 0.59%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 1        | 0.59%   |
| Mellanox MT27500 Family [ConnectX-3]                                | 1        | 0.59%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.59%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                   | 1        | 0.59%   |
| Intel Wireless-AC 9260                                              | 1        | 0.59%   |
| Intel Wireless 7260                                                 | 1        | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 1        | 0.59%   |
| Intel I350 Gigabit Network Connection                               | 1        | 0.59%   |
| Intel Ethernet Virtual Function 700 Series                          | 1        | 0.59%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                    | 1        | 0.59%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                       | 1        | 0.59%   |
| Intel Ethernet Connection I354                                      | 1        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                | 1        | 0.59%   |
| Intel Ethernet Connection (6) I219-V                                | 1        | 0.59%   |
| Intel Ethernet Connection (5) I219-LM                               | 1        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                               | 1        | 0.59%   |
| Intel Ethernet Connection (2) I218-LM                               | 1        | 0.59%   |
| Intel Ethernet Connection (14) I219-V                               | 1        | 0.59%   |
| Intel Ethernet Connection (11) I219-V                               | 1        | 0.59%   |
| Intel 82583V Gigabit Network Connection                             | 1        | 0.59%   |
| Intel 82579V Gigabit Network Connection                             | 1        | 0.59%   |
| Intel 82578DM Gigabit Network Connection                            | 1        | 0.59%   |
| Intel 82578DC Gigabit Network Connection                            | 1        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 17       | 43.59%  |
| Realtek Semiconductor | 8        | 20.51%  |
| Qualcomm Atheros      | 4        | 10.26%  |
| Ralink Technology     | 3        | 7.69%   |
| Broadcom              | 2        | 5.13%   |
| TP-Link               | 1        | 2.56%   |
| Ralink                | 1        | 2.56%   |
| Microsoft             | 1        | 2.56%   |
| Edimax Technology     | 1        | 2.56%   |
| D-Link                | 1        | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 5        | 12.82%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5        | 12.82%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2        | 5.13%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2        | 5.13%   |
| Intel Wireless 8260                                                     | 2        | 5.13%   |
| Intel Wireless 3165                                                     | 2        | 5.13%   |
| TP-Link Archer T4U ver.3                                                | 1        | 2.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 2.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 2.56%   |
| Realtek 802.11ac NIC                                                    | 1        | 2.56%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 2.56%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 2.56%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 2.56%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1        | 2.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 2.56%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1        | 2.56%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1        | 2.56%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 2.56%   |
| Intel Wireless-AC 9260                                                  | 1        | 2.56%   |
| Intel Wireless 7260                                                     | 1        | 2.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 2.56%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1        | 2.56%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 2.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1        | 2.56%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1        | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 59       | 48.76%  |
| Intel                    | 50       | 41.32%  |
| Qualcomm Atheros         | 5        | 4.13%   |
| Broadcom                 | 4        | 3.31%   |
| Mellanox Technologies    | 1        | 0.83%   |
| Marvell Technology Group | 1        | 0.83%   |
| Broadcom Limited         | 1        | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 50       | 38.76%  |
| Intel I211 Gigabit Network Connection                             | 11       | 8.53%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 6.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 5.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 5.43%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 2.33%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.55%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.55%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.78%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 0.78%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.78%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.78%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.78%   |
| Intel Ethernet Virtual Function 700 Series                        | 1        | 0.78%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 0.78%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.78%   |
| Intel Ethernet Connection I354                                    | 1        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.78%   |
| Intel Ethernet Connection (6) I219-V                              | 1        | 0.78%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.78%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.78%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.78%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.78%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.78%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.78%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.78%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.78%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 0.78%   |
| Intel 82540EM Gigabit Ethernet Controller                         | 1        | 0.78%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.78%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.78%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.78%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 0.78%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 112      | 73.68%  |
| WiFi     | 39       | 25.66%  |
| Modem    | 1        | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 100      | 80%     |
| WiFi     | 25       | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 64       | 56.64%  |
| 2     | 40       | 35.4%   |
| 3     | 5        | 4.42%   |
| 13    | 1        | 0.88%   |
| 6     | 1        | 0.88%   |
| 5     | 1        | 0.88%   |
| 0     | 1        | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 88       | 77.88%  |
| Yes  | 25       | 22.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 48.39%  |
| Cambridge Silicon Radio         | 8        | 25.81%  |
| ASUSTek Computer                | 4        | 12.9%   |
| Broadcom                        | 2        | 6.45%   |
| Realtek Semiconductor           | 1        | 3.23%   |
| Qualcomm Atheros Communications | 1        | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 25.81%  |
| Intel Wireless-AC 3168 Bluetooth                    | 5        | 16.13%  |
| Intel AX200 Bluetooth                               | 5        | 16.13%  |
| Intel Bluetooth wireless interface                  | 3        | 9.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 6.45%   |
| Realtek Bluetooth Radio                             | 1        | 3.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 3.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.23%   |
| Intel Bluetooth Device                              | 1        | 3.23%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 3.23%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1        | 3.23%   |
| ASUS Bluetooth Radio                                | 1        | 3.23%   |
| ASUS Bluetooth Adapter                              | 1        | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 62       | 31.16%  |
| AMD                        | 51       | 25.63%  |
| Nvidia                     | 47       | 23.62%  |
| C-Media Electronics        | 9        | 4.52%   |
| GYROCOM C&C                | 4        | 2.01%   |
| Creative Labs              | 4        | 2.01%   |
| Logitech                   | 3        | 1.51%   |
| Generalplus Technology     | 3        | 1.51%   |
| Samson Technologies        | 2        | 1.01%   |
| GN Netcom                  | 2        | 1.01%   |
| BEHRINGER International    | 2        | 1.01%   |
| XMOS                       | 1        | 0.5%    |
| VIA Technologies           | 1        | 0.5%    |
| Texas Instruments          | 1        | 0.5%    |
| RODE Microphones           | 1        | 0.5%    |
| ROCCAT                     | 1        | 0.5%    |
| PreSonus Audio Electronics | 1        | 0.5%    |
| Hangzhou Worlde            | 1        | 0.5%    |
| Blue Microphones           | 1        | 0.5%    |
| AXELVOX                    | 1        | 0.5%    |
| Alesis                     | 1        | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 23       | 10.18%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 5.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 4.42%   |
| Intel 200 Series PCH HD Audio                                              | 9        | 3.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 3.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 3.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 2.65%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 2.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 2.65%   |
| AMD Navi 10 HDMI Audio                                                     | 6        | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 2.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.77%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 1.77%   |
| AMD FCH Azalia Controller                                                  | 4        | 1.77%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.77%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1.33%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.33%   |
| GYROCOM C&C Fiio E10                                                       | 3        | 1.33%   |
| Generalplus Technology USB Audio Device                                    | 3        | 1.33%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 1.33%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 3        | 1.33%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.88%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.88%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.88%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.88%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.88%   |
| Logitech G430 Surround Sound Gaming Headset                                | 2        | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 0.88%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                         | 2        | 0.88%   |
| C-Media Electronics USB Audio Device                                       | 2        | 0.88%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 0.88%   |
| XMOS HIFI DSD                                                              | 1        | 0.44%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 0.44%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.44%   |
| Samson Technologies Q1U dynamic microphone                                 | 1        | 0.44%   |
| Samson Technologies Meteorite condenser microphone                         | 1        | 0.44%   |
| RODE Microphones RODE NT-USB Mini                                          | 1        | 0.44%   |
| ROCCAT Juke                                                                | 1        | 0.44%   |
| PreSonus Audio Electronics PreSonus AudioBox iTwo                          | 1        | 0.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.44%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.44%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.44%   |
| Nvidia GV100 TITAN V High Definition Audio Controller                      | 1        | 0.44%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.44%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.44%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 0.44%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 0.44%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.44%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.44%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 0.44%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.44%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 0.44%   |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 0.44%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 27       | 23.28%  |
| Corsair             | 17       | 14.66%  |
| Unknown             | 13       | 11.21%  |
| G.Skill             | 12       | 10.34%  |
| Crucial             | 12       | 10.34%  |
| Samsung Electronics | 9        | 7.76%   |
| SK Hynix            | 8        | 6.9%    |
| Micron Technology   | 4        | 3.45%   |
| A-DATA Technology   | 3        | 2.59%   |
| Team                | 2        | 1.72%   |
| Kllisre             | 2        | 1.72%   |
| Elpida              | 2        | 1.72%   |
| V-Color             | 1        | 0.86%   |
| Unknown (ABCD)      | 1        | 0.86%   |
| Patriot             | 1        | 0.86%   |
| GOODRAM             | 1        | 0.86%   |
| GeIL                | 1        | 0.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3        | 2.33%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 3        | 2.33%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s          | 3        | 2.33%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s             | 2        | 1.55%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 2        | 1.55%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s              | 2        | 1.55%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 2        | 1.55%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s            | 2        | 1.55%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s            | 2        | 1.55%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s            | 2        | 1.55%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s         | 2        | 1.55%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s         | 2        | 1.55%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s          | 2        | 1.55%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s          | 2        | 1.55%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s               | 1        | 0.78%   |
| Unknown RAM V02D4LF8GB5285282400 8192MB DIMM DDR4 2400MT/s     | 1        | 0.78%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.78%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.78%   |
| Unknown RAM Module 512MB DIMM SDRAM 400MT/s                    | 1        | 0.78%   |
| Unknown RAM Module 4GB DIMM 800MT/s                            | 1        | 0.78%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s                     | 1        | 0.78%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.78%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.78%   |
| Unknown RAM Module 256MB DIMM SDRAM 400MT/s                    | 1        | 0.78%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                     | 1        | 0.78%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                     | 1        | 0.78%   |
| Unknown RAM 7EH64AA# 8GB DIMM DDR4 2667MT/s                    | 1        | 0.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 1        | 0.78%   |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s             | 1        | 0.78%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                     | 1        | 0.78%   |
| SK Hynix RAM S949A4UUH-ITR 16GB DIMM DDR4 2400MT/s             | 1        | 0.78%   |
| SK Hynix RAM HMT41GE7BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.78%   |
| SK Hynix RAM HMT325U7CFR8A-H9 2GB DIMM DDR3 1333MT/s           | 1        | 0.78%   |
| SK Hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s           | 1        | 0.78%   |
| SK Hynix RAM HMT125U6TFR8C-G7 2GB DIMM DDR3 1067MT/s           | 1        | 0.78%   |
| SK Hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s           | 1        | 0.78%   |
| SK Hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s           | 1        | 0.78%   |
| SK Hynix RAM HMA41GR7AFR4N-TF 8GB DIMM DDR4 2133MT/s           | 1        | 0.78%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.78%   |
| Samsung RAM M393B5270DH0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.78%   |
| Samsung RAM M386A8K40BM1-CRC 64GB RIMM DDR4 2400MT/s           | 1        | 0.78%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 1        | 0.78%   |
| Samsung RAM M378B5673FH0-CF8 2GB DIMM DDR3 1067MT/s            | 1        | 0.78%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s            | 1        | 0.78%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 1        | 0.78%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s            | 1        | 0.78%   |
| Samsung RAM M3 78T2863EHS-CF7 1GB DIMM DDR2 800MT/s            | 1        | 0.78%   |
| Patriot RAM 2666 C15 Series 8GB DIMM DDR4 2666MT/s             | 1        | 0.78%   |
| Micron RAM 9ASF1G72PZ-2G6D1 8GB DIMM DDR4 2667MT/s             | 1        | 0.78%   |
| Micron RAM 16KTF1G64AZ-1G6P1 8GB DIMM DDR3 1600MT/s            | 1        | 0.78%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 1        | 0.78%   |
| Micron RAM 16JTF25664AY-1G1D1 2GB DIMM DDR3 1067MT/s           | 1        | 0.78%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                     | 1        | 0.78%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s                     | 1        | 0.78%   |
| Kingston RAM KHX3333C16D4/16GX 16GB DIMM DDR4 2933MT/s         | 1        | 0.78%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s           | 1        | 0.78%   |
| Kingston RAM KHX3000C15/16GX 16GB DIMM DDR4 3200MT/s           | 1        | 0.78%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s            | 1        | 0.78%   |
| Kingston RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.78%   |
| Kingston RAM CL16-18-18 D4-3000 8192MB DIMM DDR4 3000MT/s      | 1        | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 56       | 55.45%  |
| DDR3    | 36       | 35.64%  |
| Unknown | 5        | 4.95%   |
| SDRAM   | 2        | 1.98%   |
| LPDDR4  | 1        | 0.99%   |
| DDR2    | 1        | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 97       | 97%     |
| SODIMM | 2        | 2%      |
| RIMM   | 1        | 1%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 49       | 45.37%  |
| 4096  | 21       | 19.44%  |
| 16384 | 19       | 17.59%  |
| 2048  | 9        | 8.33%   |
| 32768 | 6        | 5.56%   |
| 65536 | 1        | 0.93%   |
| 1024  | 1        | 0.93%   |
| 512   | 1        | 0.93%   |
| 256   | 1        | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 23       | 19.33%  |
| 3200  | 16       | 13.45%  |
| 1333  | 16       | 13.45%  |
| 2667  | 10       | 8.4%    |
| 3600  | 9        | 7.56%   |
| 2400  | 8        | 6.72%   |
| 2133  | 5        | 4.2%    |
| 2933  | 4        | 3.36%   |
| 1867  | 4        | 3.36%   |
| 800   | 4        | 3.36%   |
| 3466  | 3        | 2.52%   |
| 2666  | 3        | 2.52%   |
| 3000  | 2        | 1.68%   |
| 1866  | 2        | 1.68%   |
| 1067  | 2        | 1.68%   |
| 3533  | 1        | 0.84%   |
| 3500  | 1        | 0.84%   |
| 3400  | 1        | 0.84%   |
| 3066  | 1        | 0.84%   |
| 2465  | 1        | 0.84%   |
| 2000  | 1        | 0.84%   |
| 1800  | 1        | 0.84%   |
| 400   | 1        | 0.84%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 66.67%  |
| Samsung Electronics | 1        | 16.67%  |
| Canon               | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Samsung ML-1660 Series | 1        | 16.67%  |
| HP LaserJet P1006      | 1        | 16.67%  |
| HP LaserJet M101-M106  | 1        | 16.67%  |
| HP LaserJet 1200       | 1        | 16.67%  |
| HP ENVY 4520 series    | 1        | 16.67%  |
| Canon iP2700 series    | 1        | 16.67%  |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 9        | 33.33%  |
| Microdia                | 5        | 18.52%  |
| Samsung Electronics     | 2        | 7.41%   |
| Generalplus Technology  | 2        | 7.41%   |
| Z-Star Microelectronics | 1        | 3.7%    |
| Xiongmai                | 1        | 3.7%    |
| Razer USA               | 1        | 3.7%    |
| Huawei Technologies     | 1        | 3.7%    |
| Hewlett-Packard         | 1        | 3.7%    |
| Genesys Logic           | 1        | 3.7%    |
| eMPIA Technology        | 1        | 3.7%    |
| AVerMedia Technologies  | 1        | 3.7%    |
| ARC International       | 1        | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Microdia Webcam Vitade AF                | 3        | 11.11%  |
| Samsung Galaxy (MTP)                     | 2        | 7.41%   |
| Logitech HD Webcam C615                  | 2        | 7.41%   |
| Logitech HD Pro Webcam C920              | 2        | 7.41%   |
| Z-Star Venus USB2.0 Camera               | 1        | 3.7%    |
| Xiongmai web camera                      | 1        | 3.7%    |
| Razer USA Razer Kiyo                     | 1        | 3.7%    |
| Microdia USB Live camera                 | 1        | 3.7%    |
| Microdia Integrated Camera               | 1        | 3.7%    |
| Logitech Webcam C270                     | 1        | 3.7%    |
| Logitech Webcam C260                     | 1        | 3.7%    |
| Logitech Quickcam 3000 For Business      | 1        | 3.7%    |
| Logitech HD Webcam C910                  | 1        | 3.7%    |
| Logitech BRIO                            | 1        | 3.7%    |
| Huawei UVC Camera                        | 1        | 3.7%    |
| HP Webcam 3110                           | 1        | 3.7%    |
| Genesys Logic Camera                     | 1        | 3.7%    |
| Generalplus GENERAL WEBCAM               | 1        | 3.7%    |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 3.7%    |
| eMPIA M035 Compact Web Cam               | 1        | 3.7%    |
| AVerMedia Live Gamer Ultra-Video         | 1        | 3.7%    |
| ARC International Camera                 | 1        | 3.7%    |

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
| Gemalto (was Gemplus) | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 102      | 90.27%  |
| 1     | 9        | 7.96%   |
| 5     | 1        | 0.88%   |
| 2     | 1        | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 5        | 45.45%  |
| Unassigned class      | 3        | 27.27%  |
| Sound                 | 1        | 9.09%   |
| Net/wireless          | 1        | 9.09%   |
| Multimedia controller | 1        | 9.09%   |

