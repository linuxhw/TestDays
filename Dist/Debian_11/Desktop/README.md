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
| ASRock     | H310CM-DVS                  | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek    | M4A785TD-M EVO              | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek    | P5QL-E                      | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| ASUSTek    | A88X-PRO                    | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP         | 2187 A01                    | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Gigabyte   | 970A-DS3P                   | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| ASRock     | J1900D2Y                    | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| ASRock     | N68C-S UCC                  | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell       | 0WVYMC A00                  | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| ASUSTek    | Pro WS WRX80E-SAGE SE WI... | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| ASRock     | Z370M-ITX/ac                | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| ASUSTek    | Pro WS WRX80E-SAGE SE WI... | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| MSI        | Z490-A PRO                  | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| MSI        | Q45MDO                      | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| MSI        | Q45MDO                      | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| Dell       | 0TY915                      | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte   | B550M AORUS PRO-P           | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek    | LEONITE                     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn    | 2AA9                        | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| ASRock     | B85M Pro4                   | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| ASRock     | FM2A88X Extreme6+           | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| ECS        | H61H2-M12                   | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| MSI        | B450M PRO-VDH PLUS          | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| Gigabyte   | GA-990FX-GAMING             | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte   | GA-990FX-GAMING             | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| Shuttle    | FX79R                       | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| ASUSTek    | PRIME X570-PRO              | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| ASRockRack | X570D4U-2L2T                | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| ASUSTek    | A88X-PLUS/USB               | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock     | N68C-GS FX                  | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek    | PRIME Z490-P                | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell       | 0X8DXD A00                  | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek    | M4A785D-M PRO               | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn    | 915MH Series                | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| ASUSTek    | PRIME H310M-R R2.0          | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell       | 0WMJ54 A01                  | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| ASUSTek    | PRIME H310M-K R2.0          | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
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
| 5.10.0-8-amd64                 | 76       | 51.7%   |
| 5.10.0-7-amd64                 | 42       | 28.57%  |
| 5.10.0-6-amd64                 | 9        | 6.12%   |
| 5.11.22-1-pve                  | 3        | 2.04%   |
| 5.10.0-8-rt-amd64              | 2        | 1.36%   |
| 5.8.0-3-amd64                  | 1        | 0.68%   |
| 5.13.4                         | 1        | 0.68%   |
| 5.13.1a                        | 1        | 0.68%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1        | 0.68%   |
| 5.11.22-2-pve                  | 1        | 0.68%   |
| 5.11.0-21.1-liquorix-amd64     | 1        | 0.68%   |
| 5.11.0-16.1-liquorix-amd64     | 1        | 0.68%   |
| 5.10.46custom                  | 1        | 0.68%   |
| 5.10.42+truenas                | 1        | 0.68%   |
| 5.10.38-falcot                 | 1        | 0.68%   |
| 5.10.0-8-686-pae               | 1        | 0.68%   |
| 5.10.0-8-686                   | 1        | 0.68%   |
| 5.10.0-7-686-pae               | 1        | 0.68%   |
| 5.10.0-3-amd64                 | 1        | 0.68%   |
| 5.10.0-2-amd64                 | 1        | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 133      | 91.1%   |
| 5.11.22 | 4        | 2.74%   |
| 5.11.0  | 2        | 1.37%   |
| 5.8.0   | 1        | 0.68%   |
| 5.13.4  | 1        | 0.68%   |
| 5.13.1  | 1        | 0.68%   |
| 5.13.0  | 1        | 0.68%   |
| 5.10.46 | 1        | 0.68%   |
| 5.10.42 | 1        | 0.68%   |
| 5.10.38 | 1        | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 136      | 93.15%  |
| 5.11    | 6        | 4.11%   |
| 5.13    | 3        | 2.05%   |
| 5.8     | 1        | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 143      | 97.95%  |
| i686   | 3        | 2.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 29       | 19.73%  |
| KDE5             | 26       | 17.69%  |
| Unknown          | 18       | 12.24%  |
| XFCE             | 16       | 10.88%  |
| MATE             | 14       | 9.52%   |
| Cinnamon         | 11       | 7.48%   |
| LXQt             | 6        | 4.08%   |
| Trinity          | 5        | 3.4%    |
| LXDE             | 5        | 3.4%    |
| i3               | 5        | 3.4%    |
| KDE              | 4        | 2.72%   |
| X-Cinnamon       | 2        | 1.36%   |
| GNOME Flashback  | 2        | 1.36%   |
| sway             | 1        | 0.68%   |
| lightdm-xsession | 1        | 0.68%   |
| GNUstep          | 1        | 0.68%   |
| Budgie           | 1        | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 102      | 69.86%  |
| Wayland | 19       | 13.01%  |
| Tty     | 18       | 12.33%  |
| Unknown | 7        | 4.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 54       | 36.73%  |
| Unknown | 31       | 21.09%  |
| GDM     | 29       | 19.73%  |
| SDDM    | 25       | 17.01%  |
| LightDM | 5        | 3.4%    |
| SLiM    | 2        | 1.36%   |
| XDM     | 1        | 0.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 68       | 46.58%  |
| ru_RU   | 13       | 8.9%    |
| fr_FR   | 10       | 6.85%   |
| en_GB   | 8        | 5.48%   |
| de_DE   | 8        | 5.48%   |
| Unknown | 5        | 3.42%   |
| C       | 4        | 2.74%   |
| pt_BR   | 3        | 2.05%   |
| pl_PL   | 3        | 2.05%   |
| es_ES   | 3        | 2.05%   |
| en_CA   | 3        | 2.05%   |
| nl_BE   | 2        | 1.37%   |
| en_AU   | 2        | 1.37%   |
| uk_UA   | 1        | 0.68%   |
| sv_SE   | 1        | 0.68%   |
| sr_RS   | 1        | 0.68%   |
| ru_UA   | 1        | 0.68%   |
| ro_RO   | 1        | 0.68%   |
| hu_HU   | 1        | 0.68%   |
| es_VE   | 1        | 0.68%   |
| es_US   | 1        | 0.68%   |
| es_AR   | 1        | 0.68%   |
| en_PH   | 1        | 0.68%   |
| en_IN   | 1        | 0.68%   |
| en_IE   | 1        | 0.68%   |
| en_HK   | 1        | 0.68%   |
| cs_CZ   | 1        | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 75       | 51.02%  |
| BIOS | 72       | 48.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 112      | 76.71%  |
| Btrfs   | 12       | 8.22%   |
| Overlay | 10       | 6.85%   |
| Ext3    | 5        | 3.42%   |
| Zfs     | 4        | 2.74%   |
| Xfs     | 2        | 1.37%   |
| Unknown | 1        | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 91       | 61.9%   |
| MBR     | 41       | 27.89%  |
| Unknown | 15       | 10.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 70.55%  |
| Yes       | 43       | 29.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 106      | 72.11%  |
| Yes       | 41       | 27.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 37       | 25.34%  |
| Gigabyte Technology | 31       | 21.23%  |
| ASRock              | 23       | 15.75%  |
| MSI                 | 17       | 11.64%  |
| Dell                | 14       | 9.59%   |
| Hewlett-Packard     | 9        | 6.16%   |
| Lenovo              | 2        | 1.37%   |
| Intel               | 2        | 1.37%   |
| Huanan              | 2        | 1.37%   |
| Foxconn             | 2        | 1.37%   |
| Supermicro          | 1        | 0.68%   |
| Shuttle             | 1        | 0.68%   |
| Protectli           | 1        | 0.68%   |
| HARDKERNEL          | 1        | 0.68%   |
| ECS                 | 1        | 0.68%   |
| Biostar             | 1        | 0.68%   |
| ASRockRack          | 1        | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 4        | 2.74%   |
| Gigabyte B550I AORUS PRO AX       | 3        | 2.05%   |
| ASRock B450M Pro4                 | 3        | 2.05%   |
| HP Z620 Workstation               | 2        | 1.37%   |
| Gigabyte Z77-D3H                  | 2        | 1.37%   |
| Gigabyte Z370 AORUS Gaming 5      | 2        | 1.37%   |
| Dell OptiPlex 760                 | 2        | 1.37%   |
| ASUS PRIME B550-PLUS              | 2        | 1.37%   |
| ASUS PRIME B450M-A                | 2        | 1.37%   |
| Supermicro SYS-5038MA-H24TRF      | 1        | 0.68%   |
| Shuttle SX79R                     | 1        | 0.68%   |
| Protectli FW6                     | 1        | 0.68%   |
| MSI MS-7C94                       | 1        | 0.68%   |
| MSI MS-7C84                       | 1        | 0.68%   |
| MSI MS-7C75                       | 1        | 0.68%   |
| MSI MS-7C56                       | 1        | 0.68%   |
| MSI MS-7C35                       | 1        | 0.68%   |
| MSI MS-7B89                       | 1        | 0.68%   |
| MSI MS-7B46                       | 1        | 0.68%   |
| MSI MS-7B09                       | 1        | 0.68%   |
| MSI MS-7A70                       | 1        | 0.68%   |
| MSI MS-7A40                       | 1        | 0.68%   |
| MSI MS-7A38                       | 1        | 0.68%   |
| MSI MS-7995                       | 1        | 0.68%   |
| MSI MS-7823                       | 1        | 0.68%   |
| MSI MS-7759                       | 1        | 0.68%   |
| MSI MS-7721                       | 1        | 0.68%   |
| MSI MS-7562                       | 1        | 0.68%   |
| MSI MS-6712                       | 1        | 0.68%   |
| Lenovo ThinkCentre M92p 3209EK4   | 1        | 0.68%   |
| Lenovo ThinkCentre M73 10B00005US | 1        | 0.68%   |
| Intel DP55WG AAE57269-407         | 1        | 0.68%   |
| Intel DP55WB AAE64798-206         | 1        | 0.68%   |
| Huanan X99-F8                     | 1        | 0.68%   |
| Huanan X99-8M-F V1.1              | 1        | 0.68%   |
| HP Z840 Workstation               | 1        | 0.68%   |
| HP t620 Dual Core TC              | 1        | 0.68%   |
| HP ProLiant MicroServer Gen8      | 1        | 0.68%   |
| HP ProLiant MicroServer           | 1        | 0.68%   |
| HP EliteDesk 705 G1 SFF           | 1        | 0.68%   |
| HP Compaq 8200 Elite SFF PC       | 1        | 0.68%   |
| HP 200-010hk                      | 1        | 0.68%   |
| HARDKERNEL ODROID-H2              | 1        | 0.68%   |
| Gigabyte Z97X-UD3H                | 1        | 0.68%   |
| Gigabyte Z170X-GamingG1           | 1        | 0.68%   |
| Gigabyte Z170M-D3H                | 1        | 0.68%   |
| Gigabyte X570 I AORUS PRO WIFI    | 1        | 0.68%   |
| Gigabyte P35C-DS3R                | 1        | 0.68%   |
| Gigabyte H87-HD3                  | 1        | 0.68%   |
| Gigabyte H81M-S2H GSM             | 1        | 0.68%   |
| Gigabyte H61MS                    | 1        | 0.68%   |
| Gigabyte H110N                    | 1        | 0.68%   |
| Gigabyte H110M-S2H                | 1        | 0.68%   |
| Gigabyte GA-990FX-GAMING          | 1        | 0.68%   |
| Gigabyte EG41MF-US2H              | 1        | 0.68%   |
| Gigabyte BRi7(H)-10710            | 1        | 0.68%   |
| Gigabyte B560M D3H                | 1        | 0.68%   |
| Gigabyte B550M AORUS PRO-P        | 1        | 0.68%   |
| Gigabyte B450M DS3H               | 1        | 0.68%   |
| Gigabyte B450 AORUS PRO WIFI      | 1        | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS PRIME                   | 14       | 9.59%   |
| Dell OptiPlex                | 9        | 6.16%   |
| ASUS ROG                     | 5        | 3.42%   |
| Dell Precision               | 4        | 2.74%   |
| ASUS All                     | 4        | 2.74%   |
| Gigabyte B550I               | 3        | 2.05%   |
| ASRock B450M                 | 3        | 2.05%   |
| Lenovo ThinkCentre           | 2        | 1.37%   |
| HP Z620                      | 2        | 1.37%   |
| HP ProLiant                  | 2        | 1.37%   |
| Gigabyte Z77-D3H             | 2        | 1.37%   |
| Gigabyte Z370                | 2        | 1.37%   |
| ASRock Z97                   | 2        | 1.37%   |
| Supermicro SYS-5038MA-H24TRF | 1        | 0.68%   |
| Shuttle SX79R                | 1        | 0.68%   |
| Protectli FW6                | 1        | 0.68%   |
| MSI MS-7C94                  | 1        | 0.68%   |
| MSI MS-7C84                  | 1        | 0.68%   |
| MSI MS-7C75                  | 1        | 0.68%   |
| MSI MS-7C56                  | 1        | 0.68%   |
| MSI MS-7C35                  | 1        | 0.68%   |
| MSI MS-7B89                  | 1        | 0.68%   |
| MSI MS-7B46                  | 1        | 0.68%   |
| MSI MS-7B09                  | 1        | 0.68%   |
| MSI MS-7A70                  | 1        | 0.68%   |
| MSI MS-7A40                  | 1        | 0.68%   |
| MSI MS-7A38                  | 1        | 0.68%   |
| MSI MS-7995                  | 1        | 0.68%   |
| MSI MS-7823                  | 1        | 0.68%   |
| MSI MS-7759                  | 1        | 0.68%   |
| MSI MS-7721                  | 1        | 0.68%   |
| MSI MS-7562                  | 1        | 0.68%   |
| MSI MS-6712                  | 1        | 0.68%   |
| Intel DP55WG                 | 1        | 0.68%   |
| Intel DP55WB                 | 1        | 0.68%   |
| Huanan X99-F8                | 1        | 0.68%   |
| Huanan X99-8M-F              | 1        | 0.68%   |
| HP Z840                      | 1        | 0.68%   |
| HP t620                      | 1        | 0.68%   |
| HP EliteDesk                 | 1        | 0.68%   |
| HP Compaq                    | 1        | 0.68%   |
| HP 200-010hk                 | 1        | 0.68%   |
| HARDKERNEL ODROID-H2         | 1        | 0.68%   |
| Gigabyte Z97X-UD3H           | 1        | 0.68%   |
| Gigabyte Z170X-GamingG1      | 1        | 0.68%   |
| Gigabyte Z170M-D3H           | 1        | 0.68%   |
| Gigabyte X570                | 1        | 0.68%   |
| Gigabyte P35C-DS3R           | 1        | 0.68%   |
| Gigabyte H87-HD3             | 1        | 0.68%   |
| Gigabyte H81M-S2H            | 1        | 0.68%   |
| Gigabyte H61MS               | 1        | 0.68%   |
| Gigabyte H110N               | 1        | 0.68%   |
| Gigabyte H110M-S2H           | 1        | 0.68%   |
| Gigabyte GA-990FX-GAMING     | 1        | 0.68%   |
| Gigabyte EG41MF-US2H         | 1        | 0.68%   |
| Gigabyte BRi7(H)-10710       | 1        | 0.68%   |
| Gigabyte B560M               | 1        | 0.68%   |
| Gigabyte B550M               | 1        | 0.68%   |
| Gigabyte B450M               | 1        | 0.68%   |
| Gigabyte B450                | 1        | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 30       | 20.55%  |
| 2019 | 18       | 12.33%  |
| 2018 | 18       | 12.33%  |
| 2021 | 14       | 9.59%   |
| 2016 | 12       | 8.22%   |
| 2014 | 11       | 7.53%   |
| 2012 | 9        | 6.16%   |
| 2010 | 8        | 5.48%   |
| 2015 | 7        | 4.79%   |
| 2009 | 5        | 3.42%   |
| 2013 | 4        | 2.74%   |
| 2011 | 3        | 2.05%   |
| 2017 | 2        | 1.37%   |
| 2007 | 2        | 1.37%   |
| 2006 | 2        | 1.37%   |
| 2001 | 1        | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 146      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 143      | 97.95%  |
| Enabled  | 3        | 2.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 145      | 99.32%  |
| Yes  | 1        | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 47       | 32.19%  |
| 32.01-64.0      | 26       | 17.81%  |
| 8.01-16.0       | 26       | 17.81%  |
| 64.01-256.0     | 16       | 10.96%  |
| 4.01-8.0        | 15       | 10.27%  |
| 3.01-4.0        | 8        | 5.48%   |
| 1.01-2.0        | 4        | 2.74%   |
| 2.01-3.0        | 2        | 1.37%   |
| More than 256.0 | 1        | 0.68%   |
| 24.01-32.0      | 1        | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 26       | 17.81%  |
| 3.01-4.0   | 26       | 17.81%  |
| 1.01-2.0   | 24       | 16.44%  |
| 2.01-3.0   | 22       | 15.07%  |
| 0.51-1.0   | 15       | 10.27%  |
| 8.01-16.0  | 14       | 9.59%   |
| 0.01-0.5   | 9        | 6.16%   |
| 24.01-32.0 | 4        | 2.74%   |
| 16.01-24.0 | 4        | 2.74%   |
| 32.01-64.0 | 2        | 1.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 31.51%  |
| 2      | 40       | 27.4%   |
| 3      | 26       | 17.81%  |
| 4      | 14       | 9.59%   |
| 5      | 10       | 6.85%   |
| 9      | 3        | 2.05%   |
| 8      | 3        | 2.05%   |
| 6      | 3        | 2.05%   |
| 10     | 1        | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 54.11%  |
| Yes       | 67       | 45.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 145      | 99.32%  |
| No        | 1        | 0.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 69.18%  |
| Yes       | 45       | 30.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 112      | 76.71%  |
| Yes       | 34       | 23.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 36       | 24.66%  |
| Russia                 | 16       | 10.96%  |
| France                 | 13       | 8.9%    |
| Germany                | 12       | 8.22%   |
| Ukraine                | 7        | 4.79%   |
| UK                     | 7        | 4.79%   |
| Spain                  | 5        | 3.42%   |
| Poland                 | 5        | 3.42%   |
| Mexico                 | 3        | 2.05%   |
| Canada                 | 3        | 2.05%   |
| Bulgaria               | 3        | 2.05%   |
| Brazil                 | 3        | 2.05%   |
| Australia              | 3        | 2.05%   |
| Venezuela              | 2        | 1.37%   |
| Sweden                 | 2        | 1.37%   |
| Norway                 | 2        | 1.37%   |
| Netherlands            | 2        | 1.37%   |
| Hungary                | 2        | 1.37%   |
| Finland                | 2        | 1.37%   |
| Czechia                | 2        | 1.37%   |
| Belgium                | 2        | 1.37%   |
| Argentina              | 2        | 1.37%   |
| Syria                  | 1        | 0.68%   |
| Singapore              | 1        | 0.68%   |
| Serbia                 | 1        | 0.68%   |
| New Caledonia          | 1        | 0.68%   |
| Madagascar             | 1        | 0.68%   |
| Italy                  | 1        | 0.68%   |
| India                  | 1        | 0.68%   |
| Hong Kong              | 1        | 0.68%   |
| Greece                 | 1        | 0.68%   |
| Ecuador                | 1        | 0.68%   |
| Bosnia and Herzegovina | 1        | 0.68%   |
| Austria                | 1        | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Ocala                       | 5        | 3.42%   |
| Lyon                        | 5        | 3.42%   |
| Sofia                       | 3        | 2.05%   |
| Kalamazoo                   | 3        | 2.05%   |
| Ensenada                    | 3        | 2.05%   |
| Warsaw                      | 2        | 1.37%   |
| Saint-Denis                 | 2        | 1.37%   |
| Perm                        | 2        | 1.37%   |
| New York                    | 2        | 1.37%   |
| Moscow                      | 2        | 1.37%   |
| Las Vegas                   | 2        | 1.37%   |
| Kyiv                        | 2        | 1.37%   |
| Kharkiv                     | 2        | 1.37%   |
| Athens                      | 2        | 1.37%   |
| Érd                        | 1        | 0.68%   |
| Yekaterinburg               | 1        | 0.68%   |
| Woolloongabba               | 1        | 0.68%   |
| Woodstock                   | 1        | 0.68%   |
| Wenatchee                   | 1        | 0.68%   |
| Waregem                     | 1        | 0.68%   |
| Voerde                      | 1        | 0.68%   |
| Vladimir                    | 1        | 0.68%   |
| Vienna                      | 1        | 0.68%   |
| Vancouver                   | 1        | 0.68%   |
| Valera                      | 1        | 0.68%   |
| Vaasa                       | 1        | 0.68%   |
| Ulyanovsk                   | 1        | 0.68%   |
| Ufa                         | 1        | 0.68%   |
| Turku                       | 1        | 0.68%   |
| Toulouse                    | 1        | 0.68%   |
| Thionville                  | 1        | 0.68%   |
| Tai Kok Tsui                | 1        | 0.68%   |
| Stroud                      | 1        | 0.68%   |
| Strasbourg                  | 1        | 0.68%   |
| Stockholm                   | 1        | 0.68%   |
| Stockelsdorf                | 1        | 0.68%   |
| Stavanger                   | 1        | 0.68%   |
| Springfield                 | 1        | 0.68%   |
| Sosnowiec                   | 1        | 0.68%   |
| Singapore                   | 1        | 0.68%   |
| Saratov                     | 1        | 0.68%   |
| Sarajevo                    | 1        | 0.68%   |
| San Francisco               | 1        | 0.68%   |
| San Cristóbal de La Laguna | 1        | 0.68%   |
| Rochester                   | 1        | 0.68%   |
| Ribeirao Pires              | 1        | 0.68%   |
| Prague                      | 1        | 0.68%   |
| Phoenix                     | 1        | 0.68%   |
| Pforzheim                   | 1        | 0.68%   |
| Perth                       | 1        | 0.68%   |
| Paris                       | 1        | 0.68%   |
| Ostrava                     | 1        | 0.68%   |
| Orlando                     | 1        | 0.68%   |
| Omsk                        | 1        | 0.68%   |
| Oleksandrivka               | 1        | 0.68%   |
| Oldham                      | 1        | 0.68%   |
| Noumea                      | 1        | 0.68%   |
| Noblesville                 | 1        | 0.68%   |
| New Orleans                 | 1        | 0.68%   |
| Nampa                       | 1        | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 58       | 93     | 21.72%  |
| Seagate             | 55       | 89     | 20.6%   |
| Samsung Electronics | 38       | 57     | 14.23%  |
| Toshiba             | 18       | 32     | 6.74%   |
| Crucial             | 16       | 18     | 5.99%   |
| Kingston            | 15       | 16     | 5.62%   |
| Sandisk             | 9        | 12     | 3.37%   |
| Intel               | 9        | 16     | 3.37%   |
| Hitachi             | 9        | 10     | 3.37%   |
| HGST                | 5        | 7      | 1.87%   |
| SPCC                | 4        | 4      | 1.5%    |
| PNY                 | 4        | 4      | 1.5%    |
| A-DATA Technology   | 4        | 6      | 1.5%    |
| Gigabyte Technology | 3        | 3      | 1.12%   |
| Unknown             | 2        | 2      | 0.75%   |
| Phison Electronics  | 2        | 2      | 0.75%   |
| Phison              | 2        | 2      | 0.75%   |
| Corsair             | 2        | 2      | 0.75%   |
| Transcend           | 1        | 2      | 0.37%   |
| Team                | 1        | 1      | 0.37%   |
| T-FORCE             | 1        | 1      | 0.37%   |
| SK Hynix            | 1        | 2      | 0.37%   |
| Patriot             | 1        | 1      | 0.37%   |
| OCZ                 | 1        | 1      | 0.37%   |
| MaxDigital          | 1        | 2      | 0.37%   |
| Lexar               | 1        | 1      | 0.37%   |
| KingDian            | 1        | 1      | 0.37%   |
| Intenso             | 1        | 1      | 0.37%   |
| DOGFISH             | 1        | 1      | 0.37%   |
| China               | 1        | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB          | 8        | 2.43%   |
| Toshiba HDWD110 1TB              | 4        | 1.22%   |
| Toshiba DT01ACA200 2TB           | 4        | 1.22%   |
| Seagate ST500DM002-1BD142 500GB  | 4        | 1.22%   |
| Seagate ST4000DM004-2CV104 4TB   | 4        | 1.22%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 1.22%   |
| Samsung SSD 970 EVO Plus 500GB   | 4        | 1.22%   |
| Samsung SSD 970 EVO Plus 1TB     | 4        | 1.22%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 3        | 0.91%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 3        | 0.91%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 3        | 0.91%   |
| Toshiba DT01ACA300 3TB           | 3        | 0.91%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 0.91%   |
| Samsung SSD 850 EVO 500GB        | 3        | 0.91%   |
| Samsung SSD 850 EVO 250GB        | 3        | 0.91%   |
| Kingston SV300S37A240G 240GB SSD | 3        | 0.91%   |
| Kingston SA400S37120G 120GB SSD  | 3        | 0.91%   |
| Hitachi HUS724040ALE641 4TB      | 3        | 0.91%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 2        | 0.61%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 2        | 0.61%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2        | 0.61%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.61%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 0.61%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.61%   |
| WDC WD10EFRX-68FYTN0 1TB         | 2        | 0.61%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 2        | 0.61%   |
| Seagate ST3160815AS 160GB        | 2        | 0.61%   |
| Seagate ST3000DM001-1CH166 3TB   | 2        | 0.61%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 0.61%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 0.61%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 0.61%   |
| Seagate BUP Slim BL 2TB          | 2        | 0.61%   |
| Seagate Backup+ Hub BK 4TB       | 2        | 0.61%   |
| Sandisk NVMe SSD Drive 1TB       | 2        | 0.61%   |
| Samsung SSD 970 EVO 500GB        | 2        | 0.61%   |
| Samsung SSD 860 EVO 500GB        | 2        | 0.61%   |
| Samsung SSD 860 EVO 2TB          | 2        | 0.61%   |
| Samsung SSD 860 EVO 250GB        | 2        | 0.61%   |
| Samsung SSD 840 PRO Series 256GB | 2        | 0.61%   |
| Samsung HD103SJ 1TB              | 2        | 0.61%   |
| Phison PCIe SSD 512GB            | 2        | 0.61%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 0.61%   |
| Kingston SUV500240G 240GB SSD    | 2        | 0.61%   |
| Intel SSDPEKNW010T9 1TB          | 2        | 0.61%   |
| Intel NVMe SSD Drive 1024GB      | 2        | 0.61%   |
| Intel MEMPEK1J016GAL 16GB        | 2        | 0.61%   |
| Crucial CT500P2SSD8 500GB        | 2        | 0.61%   |
| Crucial CT500P1SSD8 500GB        | 2        | 0.61%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 0.61%   |
| WDC WUH721414ALE6L4 14TB         | 1        | 0.3%    |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 0.3%    |
| WDC WDS500G1B0C-00S6U0 500GB     | 1        | 0.3%    |
| WDC WDS250G1B0A-00H9H0 250GB SSD | 1        | 0.3%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 0.3%    |
| WDC WDS200T2B0B-00YS70 2TB SSD   | 1        | 0.3%    |
| WDC WDS100T1X0E-00AFY0 1TB       | 1        | 0.3%    |
| WDC WDBRPG5000ANC-WRSN 500GB     | 1        | 0.3%    |
| WDC WD6001FZWX-00A2VA0 6TB       | 1        | 0.3%    |
| WDC WD5003ABYX-18WERA0 500GB     | 1        | 0.3%    |
| WDC WD5000AZRX-00A8LB0 500GB     | 1        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 53       | 77     | 38.97%  |
| WDC                 | 46       | 73     | 33.82%  |
| Toshiba             | 16       | 29     | 11.76%  |
| Hitachi             | 9        | 10     | 6.62%   |
| Samsung Electronics | 6        | 7      | 4.41%   |
| HGST                | 5        | 7      | 3.68%   |
| MaxDigital          | 1        | 2      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 31     | 26.14%  |
| Kingston            | 14       | 15     | 15.91%  |
| Crucial             | 12       | 13     | 13.64%  |
| WDC                 | 9        | 10     | 10.23%  |
| SanDisk             | 6        | 8      | 6.82%   |
| A-DATA Technology   | 4        | 5      | 4.55%   |
| SPCC                | 3        | 3      | 3.41%   |
| PNY                 | 3        | 3      | 3.41%   |
| Toshiba             | 2        | 3      | 2.27%   |
| Unknown             | 1        | 1      | 1.14%   |
| Transcend           | 1        | 2      | 1.14%   |
| Team                | 1        | 1      | 1.14%   |
| T-FORCE             | 1        | 1      | 1.14%   |
| Seagate             | 1        | 1      | 1.14%   |
| Patriot             | 1        | 1      | 1.14%   |
| OCZ                 | 1        | 1      | 1.14%   |
| Lexar               | 1        | 1      | 1.14%   |
| KingDian            | 1        | 1      | 1.14%   |
| Gigabyte Technology | 1        | 1      | 1.14%   |
| DOGFISH             | 1        | 1      | 1.14%   |
| China               | 1        | 1      | 1.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 107      | 205    | 43.32%  |
| SSD     | 83       | 104    | 33.6%   |
| NVMe    | 51       | 68     | 20.65%  |
| Unknown | 5        | 12     | 2.02%   |
| MMC     | 1        | 1      | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 132      | 303    | 68.04%  |
| NVMe | 51       | 68     | 26.29%  |
| SAS  | 10       | 18     | 5.15%   |
| MMC  | 1        | 1      | 0.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 90       | 126    | 43.06%  |
| 0.51-1.0   | 56       | 76     | 26.79%  |
| 1.01-2.0   | 34       | 42     | 16.27%  |
| 3.01-4.0   | 12       | 31     | 5.74%   |
| 2.01-3.0   | 9        | 14     | 4.31%   |
| 4.01-10.0  | 6        | 17     | 2.87%   |
| 10.01-20.0 | 2        | 3      | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 28       | 19.18%  |
| 251-500        | 25       | 17.12%  |
| 1001-2000      | 20       | 13.7%   |
| 501-1000       | 19       | 13.01%  |
| 101-250        | 16       | 10.96%  |
| 1-20           | 14       | 9.59%   |
| 2001-3000      | 9        | 6.16%   |
| 51-100         | 6        | 4.11%   |
| Unknown        | 6        | 4.11%   |
| 21-50          | 3        | 2.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 35       | 23.81%  |
| 101-250        | 18       | 12.24%  |
| 251-500        | 16       | 10.88%  |
| 501-1000       | 15       | 10.2%   |
| 21-50          | 13       | 8.84%   |
| More than 3000 | 12       | 8.16%   |
| 1001-2000      | 12       | 8.16%   |
| 51-100         | 12       | 8.16%   |
| 2001-3000      | 7        | 4.76%   |
| Unknown        | 6        | 4.08%   |
| 0              | 1        | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 4.44%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1        | 2      | 2.22%   |
| WDC WD5000AAKX-00U6AA0 500GB          | 1        | 1      | 2.22%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 2.22%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1        | 1      | 2.22%   |
| WDC WD5000AAJS-22A8B0 500GB           | 1        | 1      | 2.22%   |
| WDC WD40EFZX-68AWUN0 4TB              | 1        | 6      | 2.22%   |
| WDC WD400BB-00DEA0 40GB               | 1        | 1      | 2.22%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 2.22%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 2.22%   |
| WDC WD20EARS-00MVWB0 2TB              | 1        | 1      | 2.22%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1        | 1      | 2.22%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1        | 1      | 2.22%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 2.22%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 2.22%   |
| WDC WD1001FALS-75J7B0 1TB             | 1        | 1      | 2.22%   |
| Toshiba MK2565GSX 250GB               | 1        | 1      | 2.22%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 2.22%   |
| SK Hynix PC401 NVMe 512GB             | 1        | 2      | 2.22%   |
| Seagate ST3320620A 320GB              | 1        | 1      | 2.22%   |
| Seagate ST3200827AS 200GB             | 1        | 1      | 2.22%   |
| Seagate ST32000542AS 2TB              | 1        | 1      | 2.22%   |
| Seagate ST3160813AS 160GB             | 1        | 1      | 2.22%   |
| Seagate ST31500341AS 1TB              | 1        | 1      | 2.22%   |
| Seagate ST3120827AS 120GB             | 1        | 1      | 2.22%   |
| Seagate ST31000333AS 1TB              | 1        | 1      | 2.22%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 2.22%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 2.22%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 2.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 2.22%   |
| Seagate ST1000DM003-9YN162 1TB        | 1        | 1      | 2.22%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 2.22%   |
| SanDisk SSD PLUS 120 GB               | 1        | 1      | 2.22%   |
| Samsung Electronics SSD 970 EVO 250GB | 1        | 1      | 2.22%   |
| Samsung Electronics HD161GJ 160GB     | 1        | 1      | 2.22%   |
| PNY SSD2SC240G3LC709B121-460P 240GB   | 1        | 1      | 2.22%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 2.22%   |
| Kingston SE100S3100G 100GB SSD        | 1        | 1      | 2.22%   |
| KingDian S280 240GB                   | 1        | 1      | 2.22%   |
| Intel SSDPEKKW010T7 1TB               | 1        | 2      | 2.22%   |
| Hitachi HUA722020ALA331 2TB           | 1        | 1      | 2.22%   |
| Hitachi HDS722525VLAT80 250GB         | 1        | 1      | 2.22%   |
| A-DATA Technology SU800 256GB SSD     | 1        | 2      | 2.22%   |
| A-DATA Technology SSD DP900 128GB-DL3 | 1        | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 22     | 34.88%  |
| Seagate             | 13       | 15     | 30.23%  |
| Toshiba             | 2        | 2      | 4.65%   |
| Samsung Electronics | 2        | 2      | 4.65%   |
| Kingston            | 2        | 2      | 4.65%   |
| Hitachi             | 2        | 2      | 4.65%   |
| A-DATA Technology   | 2        | 3      | 4.65%   |
| SK Hynix            | 1        | 2      | 2.33%   |
| SanDisk             | 1        | 1      | 2.33%   |
| PNY                 | 1        | 1      | 2.33%   |
| KingDian            | 1        | 1      | 2.33%   |
| Intel               | 1        | 2      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 22     | 45.45%  |
| Seagate             | 13       | 15     | 39.39%  |
| Toshiba             | 2        | 2      | 6.06%   |
| Hitachi             | 2        | 2      | 6.06%   |
| Samsung Electronics | 1        | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 32       | 42     | 76.19%  |
| SSD  | 7        | 8      | 16.67%  |
| NVMe | 3        | 5      | 7.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1      | 50%     |
| Seagate ST3500830AS 500GB        | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 126      | 285    | 67.74%  |
| Malfunc  | 39       | 55     | 20.97%  |
| Detected | 19       | 48     | 10.22%  |
| Failed   | 2        | 2      | 1.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 86       | 40.38%  |
| AMD                         | 60       | 28.17%  |
| Samsung Electronics         | 18       | 8.45%   |
| Sandisk                     | 10       | 4.69%   |
| Phison Electronics          | 9        | 4.23%   |
| ASMedia Technology          | 7        | 3.29%   |
| Micron/Crucial Technology   | 5        | 2.35%   |
| Marvell Technology Group    | 4        | 1.88%   |
| JMicron Technology          | 3        | 1.41%   |
| Nvidia                      | 2        | 0.94%   |
| Broadcom / LSI              | 2        | 0.94%   |
| VIA Technologies            | 1        | 0.47%   |
| SK Hynix                    | 1        | 0.47%   |
| Silicon Image               | 1        | 0.47%   |
| Seagate Technology          | 1        | 0.47%   |
| Kingston Technology Company | 1        | 0.47%   |
| ADATA Technology            | 1        | 0.47%   |
| Adaptec                     | 1        | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 39       | 14.13%  |
| AMD 400 Series Chipset SATA Controller                                                  | 15       | 5.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14       | 5.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12       | 4.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 3.99%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 9        | 3.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 2.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8        | 2.9%    |
| Phison E12 NVMe Controller                                                              | 6        | 2.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 2.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.81%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.81%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4        | 1.45%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.45%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 1.45%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.45%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 1.09%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 3        | 1.09%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.09%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.09%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.72%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.72%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.72%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.72%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.72%   |
| Intel SSD 660P Series                                                                   | 2        | 0.72%   |
| Intel SSD 600P Series                                                                   | 2        | 0.72%   |
| Intel NVMe Optane Memory Series                                                         | 2        | 0.72%   |
| Intel Non-Volatile memory controller                                                    | 2        | 0.72%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.72%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.72%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 0.72%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.72%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2        | 0.72%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.72%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.72%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.36%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                             | 1        | 0.36%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.36%   |
| Seagate FireCuda 510 SSD                                                                | 1        | 0.36%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 0.36%   |
| Sandisk WD Black SN850                                                                  | 1        | 0.36%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.36%   |
| Samsung NVMe Controller                                                                 | 1        | 0.36%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.36%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.36%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.36%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.36%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                                   | 1        | 0.36%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.36%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.36%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 126      | 57.27%  |
| NVMe | 51       | 23.18%  |
| IDE  | 28       | 12.73%  |
| RAID | 10       | 4.55%   |
| SAS  | 5        | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 84       | 57.53%  |
| AMD    | 62       | 42.47%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 9        | 6.16%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 4        | 2.74%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 3        | 2.05%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 2.05%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 3        | 2.05%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 3        | 2.05%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 3        | 2.05%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 3        | 2.05%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz | 2        | 1.37%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2        | 1.37%   |
| Intel Core i5-6600 CPU @ 3.30GHz       | 2        | 1.37%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 2        | 1.37%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 2        | 1.37%   |
| Intel Core i5-2500K CPU @ 3.30GHz      | 2        | 1.37%   |
| Intel Core i5 CPU 650 @ 3.20GHz        | 2        | 1.37%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz  | 2        | 1.37%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 2        | 1.37%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 2        | 1.37%   |
| AMD Phenom II X4 965 Processor         | 2        | 1.37%   |
| Intel Xeon W-2145 CPU @ 3.70GHz        | 1        | 0.68%   |
| Intel Xeon CPU W3503 @ 2.40GHz         | 1        | 0.68%   |
| Intel Xeon CPU E5-2699 v4 @ 2.20GHz    | 1        | 0.68%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz    | 1        | 0.68%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz    | 1        | 0.68%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz     | 1        | 0.68%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz    | 1        | 0.68%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz     | 1        | 0.68%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz     | 1        | 0.68%   |
| Intel Pentium CPU N3700 @ 1.60GHz      | 1        | 0.68%   |
| Intel Pentium CPU G3250 @ 3.20GHz      | 1        | 0.68%   |
| Intel Pentium CPU G2030 @ 3.00GHz      | 1        | 0.68%   |
| Intel Pentium 4 CPU 2.80GHz            | 1        | 0.68%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 1        | 0.68%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 0.68%   |
| Intel Core i7-8086K CPU @ 4.00GHz      | 1        | 0.68%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 1        | 0.68%   |
| Intel Core i7-4820K CPU @ 3.70GHz      | 1        | 0.68%   |
| Intel Core i7-4790S CPU @ 3.20GHz      | 1        | 0.68%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1        | 0.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 1        | 0.68%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 0.68%   |
| Intel Core i7-10710U CPU @ 1.10GHz     | 1        | 0.68%   |
| Intel Core i7-10700K CPU @ 3.80GHz     | 1        | 0.68%   |
| Intel Core i7-10700 CPU @ 2.90GHz      | 1        | 0.68%   |
| Intel Core i7 CPU 860 @ 2.80GHz        | 1        | 0.68%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 1        | 0.68%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 1        | 0.68%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 1        | 0.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1        | 0.68%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 1        | 0.68%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 1        | 0.68%   |
| Intel Core i5-4590S CPU @ 3.00GHz      | 1        | 0.68%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 0.68%   |
| Intel Core i5-4430 CPU @ 3.00GHz       | 1        | 0.68%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 1        | 0.68%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 1        | 0.68%   |
| Intel Core i5-3550 CPU @ 3.30GHz       | 1        | 0.68%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1        | 0.68%   |
| Intel Core i5-3450 CPU @ 3.10GHz       | 1        | 0.68%   |
| Intel Core i5-3330 CPU @ 3.00GHz       | 1        | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 30       | 20.55%  |
| AMD Ryzen 5            | 19       | 13.01%  |
| Intel Core i7          | 17       | 11.64%  |
| AMD Ryzen 7            | 13       | 8.9%    |
| Intel Xeon             | 9        | 6.16%   |
| Intel Core i3          | 5        | 3.42%   |
| Intel Core 2 Duo       | 5        | 3.42%   |
| Intel Celeron          | 5        | 3.42%   |
| AMD Ryzen 9            | 4        | 2.74%   |
| AMD Phenom II X4       | 4        | 2.74%   |
| AMD FX                 | 4        | 2.74%   |
| Intel Pentium          | 3        | 2.05%   |
| Intel Core 2 Quad      | 3        | 2.05%   |
| AMD Ryzen Threadripper | 3        | 2.05%   |
| Intel Pentium Gold     | 2        | 1.37%   |
| AMD Ryzen 3            | 2        | 1.37%   |
| AMD Athlon X4          | 2        | 1.37%   |
| AMD A10                | 2        | 1.37%   |
| Other                  | 1        | 0.68%   |
| Intel Pentium 4        | 1        | 0.68%   |
| Intel Core i9          | 1        | 0.68%   |
| Intel Core 2           | 1        | 0.68%   |
| Intel Atom             | 1        | 0.68%   |
| AMD Sempron            | 1        | 0.68%   |
| AMD PRO A8             | 1        | 0.68%   |
| AMD GX                 | 1        | 0.68%   |
| AMD Athlon XP          | 1        | 0.68%   |
| AMD Athlon II X2       | 1        | 0.68%   |
| AMD Athlon II Neo      | 1        | 0.68%   |
| AMD Athlon Dual Core   | 1        | 0.68%   |
| AMD A8                 | 1        | 0.68%   |
| AMD A6                 | 1        | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 53       | 36.3%   |
| 2      | 30       | 20.55%  |
| 6      | 28       | 19.18%  |
| 8      | 19       | 13.01%  |
| 12     | 5        | 3.42%   |
| 1      | 5        | 3.42%   |
| 16     | 3        | 2.05%   |
| 44     | 1        | 0.68%   |
| 32     | 1        | 0.68%   |
| 28     | 1        | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 143      | 97.95%  |
| 2      | 3        | 2.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 84       | 57.53%  |
| 1      | 62       | 42.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 144      | 98.63%  |
| 32-bit         | 2        | 1.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 18.37%  |
| 0x08701021 | 14       | 9.52%   |
| 0x306c3    | 13       | 8.84%   |
| 0x306a9    | 7        | 4.76%   |
| 0x06003106 | 6        | 4.08%   |
| 0x506e3    | 5        | 3.4%    |
| 0x206a7    | 5        | 3.4%    |
| 0x906ea    | 4        | 2.72%   |
| 0x906e9    | 4        | 2.72%   |
| 0x0a201009 | 4        | 2.72%   |
| 0x306f2    | 3        | 2.04%   |
| 0x206d7    | 3        | 2.04%   |
| 0x1067a    | 3        | 2.04%   |
| 0x0800820d | 3        | 2.04%   |
| 0x08001138 | 3        | 2.04%   |
| 0x010000c8 | 3        | 2.04%   |
| 0xa0655    | 2        | 1.36%   |
| 0x6fb      | 2        | 1.36%   |
| 0x0a201016 | 2        | 1.36%   |
| 0x08701013 | 2        | 1.36%   |
| 0x010000b6 | 2        | 1.36%   |
| 0xf41      | 1        | 0.68%   |
| 0xf29      | 1        | 0.68%   |
| 0xa0671    | 1        | 0.68%   |
| 0xa0660    | 1        | 0.68%   |
| 0xa0653    | 1        | 0.68%   |
| 0x906ed    | 1        | 0.68%   |
| 0x906ec    | 1        | 0.68%   |
| 0x906eb    | 1        | 0.68%   |
| 0x806e9    | 1        | 0.68%   |
| 0x706a1    | 1        | 0.68%   |
| 0x6fd      | 1        | 0.68%   |
| 0x6f6      | 1        | 0.68%   |
| 0x50654    | 1        | 0.68%   |
| 0x406f1    | 1        | 0.68%   |
| 0x406d8    | 1        | 0.68%   |
| 0x406c3    | 1        | 0.68%   |
| 0x40651    | 1        | 0.68%   |
| 0x306e4    | 1        | 0.68%   |
| 0x30678    | 1        | 0.68%   |
| 0x20655    | 1        | 0.68%   |
| 0x106e5    | 1        | 0.68%   |
| 0x106a5    | 1        | 0.68%   |
| 0x0830104d | 1        | 0.68%   |
| 0x0800820b | 1        | 0.68%   |
| 0x08001137 | 1        | 0.68%   |
| 0x0700010f | 1        | 0.68%   |
| 0x06000852 | 1        | 0.68%   |
| 0x0600063e | 1        | 0.68%   |
| 0x0600063d | 1        | 0.68%   |
| 0x010000db | 1        | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 22       | 15.07%  |
| Haswell       | 18       | 12.33%  |
| KabyLake      | 15       | 10.27%  |
| IvyBridge     | 10       | 6.85%   |
| Skylake       | 8        | 5.48%   |
| SandyBridge   | 8        | 5.48%   |
| Zen+          | 7        | 4.79%   |
| Zen 3         | 7        | 4.79%   |
| Steamroller   | 7        | 4.79%   |
| K10           | 7        | 4.79%   |
| Zen           | 5        | 3.42%   |
| Core          | 5        | 3.42%   |
| Penryn        | 4        | 2.74%   |
| CometLake     | 4        | 2.74%   |
| Silvermont    | 3        | 2.05%   |
| Westmere      | 2        | 1.37%   |
| Piledriver    | 2        | 1.37%   |
| NetBurst      | 2        | 1.37%   |
| Nehalem       | 2        | 1.37%   |
| Bulldozer     | 2        | 1.37%   |
| K8 Hammer     | 1        | 0.68%   |
| K6            | 1        | 0.68%   |
| Jaguar        | 1        | 0.68%   |
| Goldmont plus | 1        | 0.68%   |
| Broadwell     | 1        | 0.68%   |
| Unknown       | 1        | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 61       | 40.4%   |
| AMD                        | 48       | 31.79%  |
| Intel                      | 37       | 24.5%   |
| ASPEED Technology          | 4        | 2.65%   |
| Matrox Electronics Systems | 1        | 0.66%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 14       | 9.21%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 3.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 3.95%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 3.29%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 3.29%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 2.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 2.63%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 2.63%   |
| ASPEED Technology ASPEED Graphics Family                                    | 4        | 2.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 2.63%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 2.63%   |
| Intel HD Graphics 530                                                       | 3        | 1.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.97%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.32%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.32%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.32%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.32%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 2        | 1.32%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 2        | 1.32%   |
| Nvidia G98 [Quadro NVS 295]                                                 | 2        | 1.32%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 2        | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.32%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 1.32%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.32%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.32%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.66%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.66%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.66%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.66%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.66%   |
| Nvidia GV100GL [Quadro GV100]                                               | 1        | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.66%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.66%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 0.66%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 0.66%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.66%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.66%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 0.66%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 0.66%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.66%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 0.66%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 0.66%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                       | 1        | 0.66%   |
| Nvidia GF110 [GeForce GTX 560 Ti 448 Cores]                                 | 1        | 0.66%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.66%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 0.66%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.66%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.66%   |
| Nvidia G92 [GeForce GTS 250]                                                | 1        | 0.66%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 0.66%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 1        | 0.66%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 0.66%   |
| Matrox Electronics Systems MGA G200EH                                       | 1        | 0.66%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 0.66%   |
| Intel HD Graphics 630                                                       | 1        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 58       | 39.73%  |
| 1 x AMD        | 45       | 30.82%  |
| 1 x Intel      | 34       | 23.29%  |
| 1 x ASPEED     | 3        | 2.05%   |
| Intel + Nvidia | 2        | 1.37%   |
| 2 x AMD        | 1        | 0.68%   |
| 1 x Matrox     | 1        | 0.68%   |
| AMD + Nvidia   | 1        | 0.68%   |
| AMD + ASPEED   | 1        | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 104      | 71.23%  |
| Proprietary | 38       | 26.03%  |
| Unknown     | 4        | 2.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 60       | 40.82%  |
| 7.01-8.0   | 20       | 13.61%  |
| 1.01-2.0   | 17       | 11.56%  |
| 3.01-4.0   | 15       | 10.2%   |
| 0.51-1.0   | 12       | 8.16%   |
| 0.01-0.5   | 11       | 7.48%   |
| 5.01-6.0   | 6        | 4.08%   |
| 2.01-3.0   | 2        | 1.36%   |
| 8.01-16.0  | 2        | 1.36%   |
| 24.01-32.0 | 1        | 0.68%   |
| 16.01-24.0 | 1        | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 23       | 14.38%  |
| Goldstar             | 22       | 13.75%  |
| Samsung Electronics  | 21       | 13.13%  |
| Acer                 | 16       | 10%     |
| Ancor Communications | 13       | 8.13%   |
| BenQ                 | 10       | 6.25%   |
| Hewlett-Packard      | 9        | 5.63%   |
| Philips              | 7        | 4.38%   |
| AOC                  | 7        | 4.38%   |
| ASUSTek Computer     | 4        | 2.5%    |
| Unknown              | 2        | 1.25%   |
| Sony                 | 2        | 1.25%   |
| NEC Computers        | 2        | 1.25%   |
| LG Electronics       | 2        | 1.25%   |
| Lenovo               | 2        | 1.25%   |
| Iiyama               | 2        | 1.25%   |
| Eizo                 | 2        | 1.25%   |
| Vizio                | 1        | 0.63%   |
| ViewSonic            | 1        | 0.63%   |
| Vestel Elektronik    | 1        | 0.63%   |
| Prestigio            | 1        | 0.63%   |
| ODH                  | 1        | 0.63%   |
| MIT                  | 1        | 0.63%   |
| Mi                   | 1        | 0.63%   |
| Medion               | 1        | 0.63%   |
| JVC                  | 1        | 0.63%   |
| INFOTRONIC           | 1        | 0.63%   |
| Idek Iiyama          | 1        | 0.63%   |
| Hitachi              | 1        | 0.63%   |
| COBY                 | 1        | 0.63%   |
| Belinea              | 1        | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 3        | 1.76%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3        | 1.76%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2        | 1.18%   |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch               | 2        | 1.18%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2        | 1.18%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 1.18%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 2        | 1.18%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2        | 1.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2        | 1.18%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2        | 1.18%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 2        | 1.18%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2        | 1.18%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                     | 1        | 0.59%   |
| ViewSonic VA926 Series VSC7D20 1280x1024 376x301mm 19.0-inch           | 1        | 0.59%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.59%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.59%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1        | 0.59%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.59%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch      | 1        | 0.59%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1        | 0.59%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch    | 1        | 0.59%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1        | 0.59%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch   | 1        | 0.59%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch    | 1        | 0.59%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch     | 1        | 0.59%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch   | 1        | 0.59%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1        | 0.59%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch      | 1        | 0.59%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 0.59%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch       | 1        | 0.59%   |
| Samsung Electronics Monitor SAM1057 1280x1024 306x230mm 15.1-inch      | 1        | 0.59%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.59%   |
| Samsung Electronics LF27T850 SAM704F 2560x1440 597x336mm 27.0-inch     | 1        | 0.59%   |
| Samsung Electronics LCD Monitor SyncMaster 5760x1080                   | 1        | 0.59%   |
| Samsung Electronics LCD Monitor SMB2430L                               | 1        | 0.59%   |
| Samsung Electronics LCD Monitor SAM0BC9 1920x1080 600x340mm 27.2-inch  | 1        | 0.59%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 0.59%   |
| Samsung Electronics LCD Monitor C24F390 3360x1080                      | 1        | 0.59%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1        | 0.59%   |
| Samsung Electronics C24FG70 SAM0D58 1920x1080 532x304mm 24.1-inch      | 1        | 0.59%   |
| Prestigio P151 ASB0503 1024x768 304x228mm 15.0-inch                    | 1        | 0.59%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1        | 0.59%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.59%   |
| Philips PHL 242E1GZ PHLC24C 1920x1080 527x296mm 23.8-inch              | 1        | 0.59%   |
| Philips PHL 241E1 PHLC207 1920x1080 530x300mm 24.0-inch                | 1        | 0.59%   |
| Philips LCD Monitor PHLC0B8 1920x1080 600x340mm 27.2-inch              | 1        | 0.59%   |
| Philips LCD Monitor PHL0850 1680x1050 470x300mm 22.0-inch              | 1        | 0.59%   |
| Philips 240S PHL087D 1920x1200 519x324mm 24.1-inch                     | 1        | 0.59%   |
| ODH LM24 ODH2492 1920x1080 345x259mm 17.0-inch                         | 1        | 0.59%   |
| NEC Computers EA243WM NEC6865 1920x1200 519x324mm 24.1-inch            | 1        | 0.59%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch            | 1        | 0.59%   |
| MIT LCD Monitor MIT2015 3840x2160 520x330mm 24.2-inch                  | 1        | 0.59%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1        | 0.59%   |
| Medion MD41077EA MED078B 1280x1024 330x270mm 16.8-inch                 | 1        | 0.59%   |
| LG Electronics LCD Monitor LG IPS FULLHD                               | 1        | 0.59%   |
| LG Electronics LCD Monitor LG HDR QHD 4480x1440                        | 1        | 0.59%   |
| LG Electronics LCD Monitor 27GL850 2560x1440                           | 1        | 0.59%   |
| JVC EM32FL AMR1007 1920x1080 700x390mm 31.5-inch                       | 1        | 0.59%   |
| INFOTRONIC L2130 ITR8852 1600x1200 432x324mm 21.3-inch                 | 1        | 0.59%   |
| Iiyama PL2790 IVM6616 1920x1080 598x336mm 27.0-inch                    | 1        | 0.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 62       | 39.49%  |
| 2560x1440 (QHD)    | 17       | 10.83%  |
| 3840x2160 (4K)     | 15       | 9.55%   |
| 1280x1024 (SXGA)   | 11       | 7.01%   |
| 1680x1050 (WSXGA+) | 9        | 5.73%   |
| 1920x1200 (WUXGA)  | 7        | 4.46%   |
| 1366x768 (WXGA)    | 6        | 3.82%   |
| 1600x900 (HD+)     | 5        | 3.18%   |
| 2560x1080          | 4        | 2.55%   |
| Unknown            | 4        | 2.55%   |
| 1440x900 (WXGA+)   | 3        | 1.91%   |
| 2560x1600          | 2        | 1.27%   |
| 2288x1287          | 2        | 1.27%   |
| 1600x1200          | 2        | 1.27%   |
| 1024x768 (XGA)     | 2        | 1.27%   |
| 7680x4320          | 1        | 0.64%   |
| 5760x1080          | 1        | 0.64%   |
| 4480x1440          | 1        | 0.64%   |
| 3440x1440          | 1        | 0.64%   |
| 3360x1080          | 1        | 0.64%   |
| 1920x540           | 1        | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 31       | 19.5%   |
| 27      | 28       | 17.61%  |
| 23      | 22       | 13.84%  |
| 21      | 11       | 6.92%   |
| Unknown | 11       | 6.92%   |
| 31      | 7        | 4.4%    |
| 18      | 7        | 4.4%    |
| 17      | 7        | 4.4%    |
| 22      | 5        | 3.14%   |
| 20      | 5        | 3.14%   |
| 19      | 5        | 3.14%   |
| 34      | 4        | 2.52%   |
| 15      | 3        | 1.89%   |
| 142     | 2        | 1.26%   |
| 29      | 2        | 1.26%   |
| 28      | 2        | 1.26%   |
| 84      | 1        | 0.63%   |
| 72      | 1        | 0.63%   |
| 55      | 1        | 0.63%   |
| 48      | 1        | 0.63%   |
| 38      | 1        | 0.63%   |
| 25      | 1        | 0.63%   |
| 16      | 1        | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 71       | 46.71%  |
| 401-500        | 31       | 20.39%  |
| 601-700        | 14       | 9.21%   |
| 301-350        | 11       | 7.24%   |
| Unknown        | 11       | 7.24%   |
| 701-800        | 4        | 2.63%   |
| 351-400        | 3        | 1.97%   |
| More than 2000 | 2        | 1.32%   |
| 1501-2000      | 2        | 1.32%   |
| 1001-1500      | 2        | 1.32%   |
| 801-900        | 1        | 0.66%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 95       | 63.33%  |
| 16/10   | 19       | 12.67%  |
| Unknown | 10       | 6.67%   |
| 5/4     | 9        | 6%      |
| 4/3     | 6        | 4%      |
| 21/9    | 5        | 3.33%   |
| 3/2     | 2        | 1.33%   |
| 1.00    | 2        | 1.33%   |
| 6/5     | 1        | 0.67%   |
| 1.96    | 1        | 0.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 52       | 33.99%  |
| 301-350        | 28       | 18.3%   |
| 351-500        | 14       | 9.15%   |
| 151-200        | 13       | 8.5%    |
| 251-300        | 12       | 7.84%   |
| 141-150        | 11       | 7.19%   |
| Unknown        | 11       | 7.19%   |
| More than 1000 | 5        | 3.27%   |
| 101-110        | 3        | 1.96%   |
| 131-140        | 2        | 1.31%   |
| 501-1000       | 2        | 1.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 91       | 62.33%  |
| 101-120 | 23       | 15.75%  |
| Unknown | 11       | 7.53%   |
| 121-160 | 9        | 6.16%   |
| 161-240 | 7        | 4.79%   |
| 1-50    | 5        | 3.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 101      | 69.18%  |
| 2     | 29       | 19.86%  |
| 0     | 11       | 7.53%   |
| 3     | 4        | 2.74%   |
| 4     | 1        | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 83       | 44.15%  |
| Intel                      | 68       | 36.17%  |
| Qualcomm Atheros           | 13       | 6.91%   |
| Broadcom                   | 7        | 3.72%   |
| Ralink Technology          | 3        | 1.6%    |
| Nvidia                     | 2        | 1.06%   |
| Microsoft                  | 2        | 1.06%   |
| ZTE WCDMA Technologies MSM | 1        | 0.53%   |
| Xiaomi                     | 1        | 0.53%   |
| TP-Link                    | 1        | 0.53%   |
| Ralink                     | 1        | 0.53%   |
| Mellanox Technologies      | 1        | 0.53%   |
| Marvell Technology Group   | 1        | 0.53%   |
| Edimax Technology          | 1        | 0.53%   |
| D-Link                     | 1        | 0.53%   |
| Broadcom Limited           | 1        | 0.53%   |
| American Megatrends        | 1        | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 63       | 29.58%  |
| Intel I211 Gigabit Network Connection                               | 12       | 5.63%   |
| Realtek RTL8125 2.5GbE Controller                                   | 10       | 4.69%   |
| Intel Ethernet Connection (2) I219-V                                | 10       | 4.69%   |
| Intel Wi-Fi 6 AX200                                                 | 7        | 3.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 7        | 3.29%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6        | 2.82%   |
| Intel I210 Gigabit Network Connection                               | 4        | 1.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 3        | 1.41%   |
| Intel Ethernet Connection I217-V                                    | 3        | 1.41%   |
| Intel Ethernet Connection (2) I218-V                                | 3        | 1.41%   |
| Intel 82574L Gigabit Network Connection                             | 3        | 1.41%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 3        | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.94%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 0.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2        | 0.94%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.94%   |
| Nvidia MCP61 Ethernet                                               | 2        | 0.94%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 2        | 0.94%   |
| Intel Wireless 8260                                                 | 2        | 0.94%   |
| Intel Wireless 3165                                                 | 2        | 0.94%   |
| Intel Ethernet Controller 10G X550T                                 | 2        | 0.94%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                       | 1        | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.47%   |
| TP-Link Archer T4U ver.3                                            | 1        | 0.47%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.47%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 0.47%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1        | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1        | 0.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.47%   |
| Realtek 802.11ac NIC                                                | 1        | 0.47%   |
| Ralink RT5372 Wireless Adapter                                      | 1        | 0.47%   |
| Ralink RT5370 Wireless Adapter                                      | 1        | 0.47%   |
| Ralink MT7601U Wireless Adapter                                     | 1        | 0.47%   |
| Ralink RT5392 PCIe Wireless Network Adapter                         | 1        | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1        | 0.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 1        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1        | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.47%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 0.47%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 0.47%   |
| Mellanox MT27500 Family [ConnectX-3]                                | 1        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.47%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                   | 1        | 0.47%   |
| Intel Wireless-AC 9260                                              | 1        | 0.47%   |
| Intel Wireless 7260                                                 | 1        | 0.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 1        | 0.47%   |
| Intel NM10/ICH7 Family LAN Controller                               | 1        | 0.47%   |
| Intel I350 Gigabit Network Connection                               | 1        | 0.47%   |
| Intel Ethernet Virtual Function 700 Series                          | 1        | 0.47%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                    | 1        | 0.47%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                       | 1        | 0.47%   |
| Intel Ethernet Connection I354                                      | 1        | 0.47%   |
| Intel Ethernet Connection (7) I219-V                                | 1        | 0.47%   |
| Intel Ethernet Connection (6) I219-V                                | 1        | 0.47%   |
| Intel Ethernet Connection (5) I219-LM                               | 1        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 20       | 44.44%  |
| Realtek Semiconductor | 8        | 17.78%  |
| Qualcomm Atheros      | 5        | 11.11%  |
| Ralink Technology     | 3        | 6.67%   |
| Broadcom              | 3        | 6.67%   |
| Microsoft             | 2        | 4.44%   |
| TP-Link               | 1        | 2.22%   |
| Ralink                | 1        | 2.22%   |
| Edimax Technology     | 1        | 2.22%   |
| D-Link                | 1        | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 7        | 15.56%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6        | 13.33%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2        | 4.44%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2        | 4.44%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 2        | 4.44%   |
| Intel Wireless 8260                                                     | 2        | 4.44%   |
| Intel Wireless 3165                                                     | 2        | 4.44%   |
| TP-Link Archer T4U ver.3                                                | 1        | 2.22%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2.22%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 2.22%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 2.22%   |
| Realtek 802.11ac NIC                                                    | 1        | 2.22%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 2.22%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 2.22%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 2.22%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1        | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 2.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 2.22%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1        | 2.22%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1        | 2.22%   |
| Intel Wireless-AC 9260                                                  | 1        | 2.22%   |
| Intel Wireless 7260                                                     | 1        | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 2.22%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1        | 2.22%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 2.22%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1        | 2.22%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1        | 2.22%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1        | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 79       | 50.32%  |
| Intel                    | 58       | 36.94%  |
| Qualcomm Atheros         | 9        | 5.73%   |
| Broadcom                 | 4        | 2.55%   |
| Nvidia                   | 2        | 1.27%   |
| Xiaomi                   | 1        | 0.64%   |
| Mellanox Technologies    | 1        | 0.64%   |
| Marvell Technology Group | 1        | 0.64%   |
| Broadcom Limited         | 1        | 0.64%   |
| American Megatrends      | 1        | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63       | 37.72%  |
| Intel I211 Gigabit Network Connection                             | 12       | 7.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 5.99%   |
| Intel Ethernet Connection (2) I219-V                              | 10       | 5.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 4.19%   |
| Intel I210 Gigabit Network Connection                             | 4        | 2.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.8%    |
| Intel Ethernet Connection I217-V                                  | 3        | 1.8%    |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.8%    |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.8%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 1.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 1.2%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 1.2%    |
| Nvidia MCP61 Ethernet                                             | 2        | 1.2%    |
| Intel Ethernet Controller 10G X550T                               | 2        | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.6%    |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 0.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.6%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.6%    |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.6%    |
| Intel I350 Gigabit Network Connection                             | 1        | 0.6%    |
| Intel Ethernet Virtual Function 700 Series                        | 1        | 0.6%    |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 0.6%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.6%    |
| Intel Ethernet Connection I354                                    | 1        | 0.6%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.6%    |
| Intel Ethernet Connection (6) I219-V                              | 1        | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.6%    |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.6%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.6%    |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.6%    |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.6%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.6%    |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.6%    |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.6%    |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.6%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 0.6%    |
| Intel 82540EM Gigabit Ethernet Controller                         | 1        | 0.6%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.6%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.6%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.6%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 0.6%    |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 0.6%    |
| American Megatrends Virtual Ethernet                              | 1        | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 145      | 75.92%  |
| WiFi     | 45       | 23.56%  |
| Modem    | 1        | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 133      | 82.61%  |
| WiFi     | 28       | 17.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 88       | 60.27%  |
| 2     | 46       | 31.51%  |
| 3     | 7        | 4.79%   |
| 13    | 1        | 0.68%   |
| 6     | 1        | 0.68%   |
| 5     | 1        | 0.68%   |
| 4     | 1        | 0.68%   |
| 0     | 1        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 115      | 78.77%  |
| Yes  | 31       | 21.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 17       | 48.57%  |
| Cambridge Silicon Radio         | 9        | 25.71%  |
| ASUSTek Computer                | 4        | 11.43%  |
| Broadcom                        | 3        | 8.57%   |
| Realtek Semiconductor           | 1        | 2.86%   |
| Qualcomm Atheros Communications | 1        | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 25.71%  |
| Intel AX200 Bluetooth                               | 7        | 20%     |
| Intel Wireless-AC 3168 Bluetooth                    | 5        | 14.29%  |
| Intel Bluetooth wireless interface                  | 3        | 8.57%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 5.71%   |
| Realtek Bluetooth Radio                             | 1        | 2.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.86%   |
| Intel Bluetooth Device                              | 1        | 2.86%   |
| Broadcom Bluetooth 3.0 Device                       | 1        | 2.86%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 2.86%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1        | 2.86%   |
| ASUS Bluetooth Radio                                | 1        | 2.86%   |
| ASUS Bluetooth Adapter                              | 1        | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 77       | 31.05%  |
| AMD                        | 69       | 27.82%  |
| Nvidia                     | 56       | 22.58%  |
| C-Media Electronics        | 10       | 4.03%   |
| GYROCOM C&C                | 4        | 1.61%   |
| Creative Labs              | 4        | 1.61%   |
| Logitech                   | 3        | 1.21%   |
| Generalplus Technology     | 3        | 1.21%   |
| Samson Technologies        | 2        | 0.81%   |
| GN Netcom                  | 2        | 0.81%   |
| BEHRINGER International    | 2        | 0.81%   |
| XMOS                       | 1        | 0.4%    |
| VIA Technologies           | 1        | 0.4%    |
| Texas Instruments          | 1        | 0.4%    |
| TEAC                       | 1        | 0.4%    |
| SteelSeries ApS            | 1        | 0.4%    |
| RODE Microphones           | 1        | 0.4%    |
| ROCCAT                     | 1        | 0.4%    |
| PreSonus Audio Electronics | 1        | 0.4%    |
| Hangzhou Worlde            | 1        | 0.4%    |
| Dell                       | 1        | 0.4%    |
| Blue Microphones           | 1        | 0.4%    |
| AXELVOX                    | 1        | 0.4%    |
| AVID Technology            | 1        | 0.4%    |
| Audioengine                | 1        | 0.4%    |
| ASUSTek Computer           | 1        | 0.4%    |
| Alesis                     | 1        | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 27       | 9.51%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14       | 4.93%   |
| Intel 200 Series PCH HD Audio                                              | 13       | 4.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 3.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9        | 3.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9        | 3.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 2.82%   |
| AMD FCH Azalia Controller                                                  | 8        | 2.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 2.46%   |
| AMD Navi 10 HDMI Audio                                                     | 7        | 2.46%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 2.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 2.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.76%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 5        | 1.76%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 1.41%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 1.41%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.41%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1.06%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1.06%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 1.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.06%   |
| GYROCOM C&C Fiio E10                                                       | 3        | 1.06%   |
| Generalplus Technology USB Audio Device                                    | 3        | 1.06%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.7%    |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.7%    |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.7%    |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.7%    |
| Nvidia High Definition Audio Controller                                    | 2        | 0.7%    |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.7%    |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.7%    |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.7%    |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.7%    |
| Nvidia GF104 High Definition Audio Controller                              | 2        | 0.7%    |
| Logitech G430 Surround Sound Gaming Headset                                | 2        | 0.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.7%    |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                         | 2        | 0.7%    |
| C-Media Electronics USB Audio Device                                       | 2        | 0.7%    |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 0.7%    |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 2        | 0.7%    |
| XMOS HIFI DSD                                                              | 1        | 0.35%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 0.35%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.35%   |
| TEAC US-2x2                                                                | 1        | 0.35%   |
| SteelSeries ApS SteelSeries Arctis 9                                       | 1        | 0.35%   |
| Samson Technologies Q1U dynamic microphone                                 | 1        | 0.35%   |
| Samson Technologies Meteorite condenser microphone                         | 1        | 0.35%   |
| RODE Microphones RODE NT-USB Mini                                          | 1        | 0.35%   |
| ROCCAT Juke                                                                | 1        | 0.35%   |
| PreSonus Audio Electronics PreSonus AudioBox iTwo                          | 1        | 0.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.35%   |
| Nvidia GV100 TITAN V High Definition Audio Controller                      | 1        | 0.35%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.35%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 33       | 21.71%  |
| Unknown             | 23       | 15.13%  |
| Corsair             | 22       | 14.47%  |
| G.Skill             | 14       | 9.21%   |
| SK Hynix            | 13       | 8.55%   |
| Samsung Electronics | 13       | 8.55%   |
| Crucial             | 13       | 8.55%   |
| Micron Technology   | 4        | 2.63%   |
| Patriot             | 3        | 1.97%   |
| A-DATA Technology   | 3        | 1.97%   |
| Team                | 2        | 1.32%   |
| Kllisre             | 2        | 1.32%   |
| Elpida              | 2        | 1.32%   |
| V-Color             | 1        | 0.66%   |
| Unknown (ABCD)      | 1        | 0.66%   |
| Kingmax             | 1        | 0.66%   |
| GOODRAM             | 1        | 0.66%   |
| GeIL                | 1        | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 4        | 2.3%    |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 4        | 2.3%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 3        | 1.72%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 3        | 1.72%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s          | 3        | 1.72%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 2        | 1.15%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 2        | 1.15%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 2        | 1.15%   |
| Unknown RAM 99[2/7/4]164(F/R) 4GB DIMM DDR3 1600MT/s           | 2        | 1.15%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s             | 2        | 1.15%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s              | 2        | 1.15%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 2        | 1.15%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s            | 2        | 1.15%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s            | 2        | 1.15%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s            | 2        | 1.15%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s         | 2        | 1.15%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s         | 2        | 1.15%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s          | 2        | 1.15%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s          | 2        | 1.15%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s               | 1        | 0.57%   |
| Unknown RAM V02D4LF8GB5285282400 8192MB DIMM DDR4 2400MT/s     | 1        | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.57%   |
| Unknown RAM Module 512MB DIMM SDRAM 400MT/s                    | 1        | 0.57%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                     | 1        | 0.57%   |
| Unknown RAM Module 4GB DIMM 800MT/s                            | 1        | 0.57%   |
| Unknown RAM Module 4GB DIMM 400MT/s                            | 1        | 0.57%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s                     | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM 400MT/s                            | 1        | 0.57%   |
| Unknown RAM Module 256MB DIMM SDRAM 400MT/s                    | 1        | 0.57%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.57%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 1        | 0.57%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                     | 1        | 0.57%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                     | 1        | 0.57%   |
| Unknown RAM 7EH64AA# 8GB DIMM DDR4 2667MT/s                    | 1        | 0.57%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s          | 1        | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 1        | 0.57%   |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s             | 1        | 0.57%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                     | 1        | 0.57%   |
| SK Hynix RAM S949A4UUH-ITR 16GB DIMM DDR4 2400MT/s             | 1        | 0.57%   |
| SK Hynix RAM HYMP512U64CP8-S5 1GB DIMM DDR2 400MT/s            | 1        | 0.57%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 400MT/s            | 1        | 0.57%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.57%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.57%   |
| SK Hynix RAM HMT41GE7BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.57%   |
| SK Hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 1333MT/s              | 1        | 0.57%   |
| SK Hynix RAM HMT325U7CFR8A-H9 2GB DIMM DDR3 1333MT/s           | 1        | 0.57%   |
| SK Hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s           | 1        | 0.57%   |
| SK Hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 0.57%   |
| SK Hynix RAM HMT125U6TFR8C-G7 2GB DIMM DDR3 1067MT/s           | 1        | 0.57%   |
| SK Hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s           | 1        | 0.57%   |
| SK Hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s           | 1        | 0.57%   |
| SK Hynix RAM HMA41GR7AFR4N-TF 8GB DIMM DDR4 2133MT/s           | 1        | 0.57%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 0.57%   |
| Samsung RAM M471B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s            | 1        | 0.57%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.57%   |
| Samsung RAM M393B5270DH0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 66       | 49.62%  |
| DDR3    | 49       | 36.84%  |
| Unknown | 7        | 5.26%   |
| SDRAM   | 5        | 3.76%   |
| DDR2    | 5        | 3.76%   |
| LPDDR4  | 1        | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 128      | 96.97%  |
| SODIMM | 3        | 2.27%   |
| RIMM   | 1        | 0.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 57       | 39.04%  |
| 4096  | 31       | 21.23%  |
| 16384 | 23       | 15.75%  |
| 2048  | 15       | 10.27%  |
| 32768 | 9        | 6.16%   |
| 1024  | 7        | 4.79%   |
| 512   | 2        | 1.37%   |
| 65536 | 1        | 0.68%   |
| 256   | 1        | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 33       | 21.57%  |
| 1333    | 21       | 13.73%  |
| 3200    | 19       | 12.42%  |
| 2667    | 12       | 7.84%   |
| 3600    | 10       | 6.54%   |
| 2400    | 10       | 6.54%   |
| 800     | 6        | 3.92%   |
| 2133    | 5        | 3.27%   |
| 2933    | 4        | 2.61%   |
| 1867    | 4        | 2.61%   |
| 3466    | 3        | 1.96%   |
| 2666    | 3        | 1.96%   |
| 1866    | 3        | 1.96%   |
| 400     | 3        | 1.96%   |
| 3400    | 2        | 1.31%   |
| 3000    | 2        | 1.31%   |
| 1067    | 2        | 1.31%   |
| 667     | 2        | 1.31%   |
| Unknown | 2        | 1.31%   |
| 3533    | 1        | 0.65%   |
| 3500    | 1        | 0.65%   |
| 3100    | 1        | 0.65%   |
| 3066    | 1        | 0.65%   |
| 2465    | 1        | 0.65%   |
| 2000    | 1        | 0.65%   |
| 1800    | 1        | 0.65%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 11       | 33.33%  |
| Microdia                      | 5        | 15.15%  |
| Samsung Electronics           | 3        | 9.09%   |
| Genesys Logic                 | 2        | 6.06%   |
| Generalplus Technology        | 2        | 6.06%   |
| Z-Star Microelectronics       | 1        | 3.03%   |
| Xiongmai                      | 1        | 3.03%   |
| Sunplus Innovation Technology | 1        | 3.03%   |
| SiGma Micro                   | 1        | 3.03%   |
| Razer USA                     | 1        | 3.03%   |
| Huawei Technologies           | 1        | 3.03%   |
| Hewlett-Packard               | 1        | 3.03%   |
| eMPIA Technology              | 1        | 3.03%   |
| AVerMedia Technologies        | 1        | 3.03%   |
| ARC International             | 1        | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)                  | 3        | 9.09%   |
| Microdia Webcam Vitade AF                | 3        | 9.09%   |
| Logitech Webcam C270                     | 2        | 6.06%   |
| Logitech HD Webcam C910                  | 2        | 6.06%   |
| Logitech HD Webcam C615                  | 2        | 6.06%   |
| Logitech HD Pro Webcam C920              | 2        | 6.06%   |
| Z-Star Venus USB2.0 Camera               | 1        | 3.03%   |
| Xiongmai web camera                      | 1        | 3.03%   |
| Sunplus HD USB Camaer 4K                 | 1        | 3.03%   |
| SiGma Micro WebCam SiGma Micro           | 1        | 3.03%   |
| Razer USA Razer Kiyo                     | 1        | 3.03%   |
| Microdia USB Live camera                 | 1        | 3.03%   |
| Microdia Integrated Camera               | 1        | 3.03%   |
| Logitech Webcam C260                     | 1        | 3.03%   |
| Logitech Quickcam 3000 For Business      | 1        | 3.03%   |
| Logitech BRIO                            | 1        | 3.03%   |
| Huawei UVC Camera                        | 1        | 3.03%   |
| HP Webcam 3110                           | 1        | 3.03%   |
| Genesys Logic USB2.0 Digital Camera      | 1        | 3.03%   |
| Genesys Logic Camera                     | 1        | 3.03%   |
| Generalplus GENERAL WEBCAM               | 1        | 3.03%   |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 3.03%   |
| eMPIA M035 Compact Web Cam               | 1        | 3.03%   |
| AVerMedia Live Gamer Ultra-Video         | 1        | 3.03%   |
| ARC International Camera                 | 1        | 3.03%   |

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
| Yubico.com            | 1        | 50%     |
| Gemalto (was Gemplus) | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4 CCID                         | 1        | 50%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 131      | 89.73%  |
| 1     | 13       | 8.9%    |
| 5     | 1        | 0.68%   |
| 2     | 1        | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 46.67%  |
| Unassigned class         | 3        | 20%     |
| Sound                    | 1        | 6.67%   |
| Network                  | 1        | 6.67%   |
| Net/wireless             | 1        | 6.67%   |
| Multimedia controller    | 1        | 6.67%   |
| Communication controller | 1        | 6.67%   |

