Linux in Finland - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Finland.

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

Total: 900

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MEG X570 UNIFY              | [179381f376](https://linux-hardware.org/?probe=179381f376) | Aug 12, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [873825c261](https://linux-hardware.org/?probe=873825c261) | Aug 07, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [28ee020bed](https://linux-hardware.org/?probe=28ee020bed) | Aug 06, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | [13f47a5399](https://linux-hardware.org/?probe=13f47a5399) | Aug 06, 2023 |
| Medion        | B550A4-EM                   | [f1bf2b93c1](https://linux-hardware.org/?probe=f1bf2b93c1) | Aug 05, 2023 |
| HP            | 8653 A                      | [09f876ab04](https://linux-hardware.org/?probe=09f876ab04) | Aug 02, 2023 |
| HP            | 0AA8h                       | [76dbb0d0a3](https://linux-hardware.org/?probe=76dbb0d0a3) | Jul 31, 2023 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [36c7268653](https://linux-hardware.org/?probe=36c7268653) | Jul 31, 2023 |
| ASUSTek       | H97M-PLUS                   | [940e14c90d](https://linux-hardware.org/?probe=940e14c90d) | Jul 31, 2023 |
| ASUSTek       | M2N68-AM Plus               | [c980146db6](https://linux-hardware.org/?probe=c980146db6) | Jul 29, 2023 |
| ASUSTek       | M2N68-AM Plus               | [a9a2ac74bc](https://linux-hardware.org/?probe=a9a2ac74bc) | Jul 29, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [f591b4a83a](https://linux-hardware.org/?probe=f591b4a83a) | Jul 28, 2023 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [4f809512a6](https://linux-hardware.org/?probe=4f809512a6) | Jul 26, 2023 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [99352602c2](https://linux-hardware.org/?probe=99352602c2) | Jul 24, 2023 |
| ASUSTek       | PRIME X399-A                | [3dac76b45f](https://linux-hardware.org/?probe=3dac76b45f) | Jul 23, 2023 |
| ASUSTek       | PRIME Z270-K                | [97aa2f7158](https://linux-hardware.org/?probe=97aa2f7158) | Jul 22, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [cc9f1fdcd8](https://linux-hardware.org/?probe=cc9f1fdcd8) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [fc0fcad674](https://linux-hardware.org/?probe=fc0fcad674) | Jul 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | [4884c4b183](https://linux-hardware.org/?probe=4884c4b183) | Jul 18, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [81d6c4c3bd](https://linux-hardware.org/?probe=81d6c4c3bd) | Jul 15, 2023 |
| MSI           | Z87-G45 GAMING              | [110a53c220](https://linux-hardware.org/?probe=110a53c220) | Jul 13, 2023 |
| ASUSTek       | PRIME Z390-A                | [2551062f30](https://linux-hardware.org/?probe=2551062f30) | Jul 13, 2023 |
| ASUSTek       | P10S-I Series               | [109d52a9be](https://linux-hardware.org/?probe=109d52a9be) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | [8e53be597f](https://linux-hardware.org/?probe=8e53be597f) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | [dcb1a242c5](https://linux-hardware.org/?probe=dcb1a242c5) | Jul 13, 2023 |
| ASRock        | X570 Taichi                 | [ea2102a05b](https://linux-hardware.org/?probe=ea2102a05b) | Jul 09, 2023 |
| ASRock        | X570 Taichi                 | [655b6ba155](https://linux-hardware.org/?probe=655b6ba155) | Jul 09, 2023 |
| HP            | 158B                        | [aad7455bc5](https://linux-hardware.org/?probe=aad7455bc5) | Jul 08, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [d122a1cedc](https://linux-hardware.org/?probe=d122a1cedc) | Jul 07, 2023 |
| MSI           | B350 GAMING PLUS            | [8115e08748](https://linux-hardware.org/?probe=8115e08748) | Jul 05, 2023 |
| MSI           | Z170A GAMING M3             | [ebd5d13804](https://linux-hardware.org/?probe=ebd5d13804) | Jul 04, 2023 |
| ASRock        | Z87 Extreme6                | [d69ea1a2cb](https://linux-hardware.org/?probe=d69ea1a2cb) | Jul 02, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [42624c8bb1](https://linux-hardware.org/?probe=42624c8bb1) | Jun 29, 2023 |
| Cisco         | WAVE-694-K9 A0              | [26b9c3adb7](https://linux-hardware.org/?probe=26b9c3adb7) | Jun 27, 2023 |
| ASUSTek       | P5Q-E                       | [55179e2249](https://linux-hardware.org/?probe=55179e2249) | Jun 25, 2023 |
| ASUSTek       | P8P67 PRO                   | [7b33fc2cb8](https://linux-hardware.org/?probe=7b33fc2cb8) | Jun 23, 2023 |
| HP            | 1495                        | [9bdf95d92b](https://linux-hardware.org/?probe=9bdf95d92b) | Jun 21, 2023 |
| ASUSTek       | PRIME B360M-C               | [4dca77df51](https://linux-hardware.org/?probe=4dca77df51) | Jun 21, 2023 |
| ASUSTek       | P8P67 PRO                   | [ba4e83abed](https://linux-hardware.org/?probe=ba4e83abed) | Jun 20, 2023 |
| ASUSTek       | P7P55D LE                   | [285303d1a0](https://linux-hardware.org/?probe=285303d1a0) | Jun 13, 2023 |
| HP            | 3398                        | [7523eb041f](https://linux-hardware.org/?probe=7523eb041f) | Jun 11, 2023 |
| Gigabyte      | B650M GAMING X AX           | [5affc12294](https://linux-hardware.org/?probe=5affc12294) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0f42ca8c95](https://linux-hardware.org/?probe=0f42ca8c95) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [276844abe2](https://linux-hardware.org/?probe=276844abe2) | Jun 07, 2023 |
| Acer          | Predator G3-605             | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| Foxconn       | 2ABF                        | [8472aba19b](https://linux-hardware.org/?probe=8472aba19b) | May 25, 2023 |
| ASRock        | 890GX Extreme3              | [016f2a8ada](https://linux-hardware.org/?probe=016f2a8ada) | May 24, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [a2a31dbbee](https://linux-hardware.org/?probe=a2a31dbbee) | May 24, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a4528c4521](https://linux-hardware.org/?probe=a4528c4521) | May 20, 2023 |
| MSI           | 2AE0                        | [5f47fbb9cb](https://linux-hardware.org/?probe=5f47fbb9cb) | May 19, 2023 |
| MSI           | 2AE0                        | [c14f84a498](https://linux-hardware.org/?probe=c14f84a498) | May 19, 2023 |
| ASRock        | X299 Taichi XE              | [deae8ee190](https://linux-hardware.org/?probe=deae8ee190) | May 19, 2023 |
| ASRock        | 890FX Deluxe4               | [c00eb20149](https://linux-hardware.org/?probe=c00eb20149) | May 18, 2023 |
| HP            | 1495                        | [6332ac9d68](https://linux-hardware.org/?probe=6332ac9d68) | May 14, 2023 |
| ASRock        | X299 Taichi                 | [59e43db209](https://linux-hardware.org/?probe=59e43db209) | May 14, 2023 |
| Acer          | Predator G3-605             | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Acer          | Predator G3-605             | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [713564ccd4](https://linux-hardware.org/?probe=713564ccd4) | May 12, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [33f3e64e8f](https://linux-hardware.org/?probe=33f3e64e8f) | May 11, 2023 |
| ASRock        | X670E Pro RS                | [a17449f761](https://linux-hardware.org/?probe=a17449f761) | May 02, 2023 |
| ASRock        | 890FX Deluxe4               | [327a1a2b37](https://linux-hardware.org/?probe=327a1a2b37) | Apr 29, 2023 |
| ASRock        | B550M-ITX/ac                | [0295ab04a7](https://linux-hardware.org/?probe=0295ab04a7) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [e8886a7521](https://linux-hardware.org/?probe=e8886a7521) | Apr 28, 2023 |
| HP            | 3029h                       | [35be4d25c4](https://linux-hardware.org/?probe=35be4d25c4) | Apr 25, 2023 |
| ASUSTek       | PRIME X470-PRO              | [962bffed9f](https://linux-hardware.org/?probe=962bffed9f) | Apr 25, 2023 |
| MSI           | B450M MORTAR MAX            | [7560923404](https://linux-hardware.org/?probe=7560923404) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| ASRock        | B550M-ITX/ac                | [4fad4d4a09](https://linux-hardware.org/?probe=4fad4d4a09) | Apr 21, 2023 |
| Dell          | 0T656F A02                  | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [e8b30a69f9](https://linux-hardware.org/?probe=e8b30a69f9) | Apr 16, 2023 |
| ASRock        | H87 Pro4                    | [e85b3e34b0](https://linux-hardware.org/?probe=e85b3e34b0) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [87acc1eb9d](https://linux-hardware.org/?probe=87acc1eb9d) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c3eb775c80](https://linux-hardware.org/?probe=c3eb775c80) | Apr 13, 2023 |
| HP            | 1791                        | [c87bf6d0e1](https://linux-hardware.org/?probe=c87bf6d0e1) | Apr 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [654728e9fe](https://linux-hardware.org/?probe=654728e9fe) | Apr 13, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | [33a7fad816](https://linux-hardware.org/?probe=33a7fad816) | Apr 13, 2023 |
| Foxconn       | 2ABF                        | [408e2e47c1](https://linux-hardware.org/?probe=408e2e47c1) | Apr 12, 2023 |
| MSI           | B350 GAMING PLUS            | [df2f924a6e](https://linux-hardware.org/?probe=df2f924a6e) | Apr 11, 2023 |
| ASRock        | 970 Pro3 R2.0               | [375bb1794b](https://linux-hardware.org/?probe=375bb1794b) | Apr 08, 2023 |
| ASUSTek       | P5B                         | [a2a4936e2c](https://linux-hardware.org/?probe=a2a4936e2c) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3569575b7c](https://linux-hardware.org/?probe=3569575b7c) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5881a47fd0](https://linux-hardware.org/?probe=5881a47fd0) | Apr 05, 2023 |
| HP            | 18E5                        | [71c68a2c6a](https://linux-hardware.org/?probe=71c68a2c6a) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0662f665d7](https://linux-hardware.org/?probe=0662f665d7) | Apr 03, 2023 |
| HP            | 2AF3                        | [fe33aa7257](https://linux-hardware.org/?probe=fe33aa7257) | Apr 02, 2023 |
| HP            | 0A64h                       | [f4fd3904f0](https://linux-hardware.org/?probe=f4fd3904f0) | Mar 31, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [a025953f4c](https://linux-hardware.org/?probe=a025953f4c) | Mar 31, 2023 |
| HP            | 0A64h                       | [9f50595e87](https://linux-hardware.org/?probe=9f50595e87) | Mar 30, 2023 |
| HP            | 18E7                        | [6b64a1639b](https://linux-hardware.org/?probe=6b64a1639b) | Mar 30, 2023 |
| ASRock        | B85M Pro4                   | [d237bcc0a2](https://linux-hardware.org/?probe=d237bcc0a2) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a1d2ac5e6e](https://linux-hardware.org/?probe=a1d2ac5e6e) | Mar 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | [7483952d78](https://linux-hardware.org/?probe=7483952d78) | Mar 29, 2023 |
| ASUSTek       | P8H67                       | [3b9e638ecb](https://linux-hardware.org/?probe=3b9e638ecb) | Mar 26, 2023 |
| ASUSTek       | PRIME B450M-K               | [95b0768bfc](https://linux-hardware.org/?probe=95b0768bfc) | Mar 25, 2023 |
| HP            | 8433 11                     | [1f76e1dc62](https://linux-hardware.org/?probe=1f76e1dc62) | Mar 25, 2023 |
| HP            | 0A64h                       | [c53db667a1](https://linux-hardware.org/?probe=c53db667a1) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0c824a1f88](https://linux-hardware.org/?probe=0c824a1f88) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6a57dfd8fc](https://linux-hardware.org/?probe=6a57dfd8fc) | Mar 23, 2023 |
| ASUSTek       | PRIME B360M-C               | [8cf7b9cc76](https://linux-hardware.org/?probe=8cf7b9cc76) | Mar 23, 2023 |
| MSI           | MAG B550M BAZOOKA           | [3fe3c818f7](https://linux-hardware.org/?probe=3fe3c818f7) | Mar 20, 2023 |
| Intel         | DP55WB AAE64798-205         | [a76d46bf92](https://linux-hardware.org/?probe=a76d46bf92) | Mar 18, 2023 |
| HP            | 805A                        | [fd97efb317](https://linux-hardware.org/?probe=fd97efb317) | Mar 16, 2023 |
| HP            | 8299                        | [59417ae66d](https://linux-hardware.org/?probe=59417ae66d) | Mar 16, 2023 |
| Lenovo        | Annapurna CRB 0B98401 WI... | [c4603a155e](https://linux-hardware.org/?probe=c4603a155e) | Mar 14, 2023 |
| ASUSTek       | P5KR                        | [613bbd6934](https://linux-hardware.org/?probe=613bbd6934) | Mar 14, 2023 |
| MSI           | MPG Z490 GAMING CARBON W... | [a6c5296f86](https://linux-hardware.org/?probe=a6c5296f86) | Mar 12, 2023 |
| HP            | 8433 11                     | [51a4dbf83e](https://linux-hardware.org/?probe=51a4dbf83e) | Mar 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [c5950249eb](https://linux-hardware.org/?probe=c5950249eb) | Mar 11, 2023 |
| ASUSTek       | P6T WS PRO                  | [7d5df3a3d7](https://linux-hardware.org/?probe=7d5df3a3d7) | Mar 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [ca937e17a7](https://linux-hardware.org/?probe=ca937e17a7) | Mar 10, 2023 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [fcb5d30135](https://linux-hardware.org/?probe=fcb5d30135) | Mar 09, 2023 |
| Inventec      | Z CLASS A02                 | [c45e770987](https://linux-hardware.org/?probe=c45e770987) | Mar 06, 2023 |
| Gigabyte      | B450M GAMING                | [168b8db115](https://linux-hardware.org/?probe=168b8db115) | Mar 06, 2023 |
| MSI           | MS-6702E                    | [e17662e6c0](https://linux-hardware.org/?probe=e17662e6c0) | Mar 05, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [65aa79b0a3](https://linux-hardware.org/?probe=65aa79b0a3) | Mar 05, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [ab7448d0bf](https://linux-hardware.org/?probe=ab7448d0bf) | Mar 05, 2023 |
| Gigabyte      | A320M-S2H-CF                | [b531e1a7a8](https://linux-hardware.org/?probe=b531e1a7a8) | Mar 04, 2023 |
| ASUSTek       | P7P55D                      | [1c2701a81c](https://linux-hardware.org/?probe=1c2701a81c) | Mar 04, 2023 |
| MSI           | B350 GAMING PLUS            | [c3d6a142c0](https://linux-hardware.org/?probe=c3d6a142c0) | Mar 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [a04a4550d5](https://linux-hardware.org/?probe=a04a4550d5) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [62c37af17b](https://linux-hardware.org/?probe=62c37af17b) | Mar 03, 2023 |
| HP            | 8053                        | [c48153fe6d](https://linux-hardware.org/?probe=c48153fe6d) | Mar 02, 2023 |
| ASUSTek       | PRIME B250-PRO              | [cd58d8a863](https://linux-hardware.org/?probe=cd58d8a863) | Feb 28, 2023 |
| HP            | 18E7                        | [a4fb4affcf](https://linux-hardware.org/?probe=a4fb4affcf) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [4018e453c4](https://linux-hardware.org/?probe=4018e453c4) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [48725cdc4d](https://linux-hardware.org/?probe=48725cdc4d) | Feb 28, 2023 |
| ASUSTek       | B150M-C                     | [e675a40455](https://linux-hardware.org/?probe=e675a40455) | Feb 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | [a758475e11](https://linux-hardware.org/?probe=a758475e11) | Feb 26, 2023 |
| HP            | 8433 11                     | [881b062090](https://linux-hardware.org/?probe=881b062090) | Feb 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | [c34909b191](https://linux-hardware.org/?probe=c34909b191) | Feb 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [ec6ab709e5](https://linux-hardware.org/?probe=ec6ab709e5) | Feb 22, 2023 |
| ASUSTek       | P5Q-E                       | [1fd091bff9](https://linux-hardware.org/?probe=1fd091bff9) | Feb 21, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [50261acb6b](https://linux-hardware.org/?probe=50261acb6b) | Feb 21, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | [32ed66a6f9](https://linux-hardware.org/?probe=32ed66a6f9) | Feb 20, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [06c110e6f1](https://linux-hardware.org/?probe=06c110e6f1) | Feb 19, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [d94b8cf0e0](https://linux-hardware.org/?probe=d94b8cf0e0) | Feb 18, 2023 |
| ASUSTek       | M5A97 R2.0                  | [8fb0aec13d](https://linux-hardware.org/?probe=8fb0aec13d) | Feb 18, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [c67a2ae3c5](https://linux-hardware.org/?probe=c67a2ae3c5) | Feb 18, 2023 |
| AOpen         | iBDWMt-WBOP R1.00H 55WB3... | [c524d923e6](https://linux-hardware.org/?probe=c524d923e6) | Feb 17, 2023 |
| Pegatron      | 2AD5                        | [5065063fa1](https://linux-hardware.org/?probe=5065063fa1) | Feb 16, 2023 |
| HP            | 8433 11                     | [3f4ea738b6](https://linux-hardware.org/?probe=3f4ea738b6) | Feb 15, 2023 |
| MSI           | Z370 PC PRO                 | [b5744eb259](https://linux-hardware.org/?probe=b5744eb259) | Feb 13, 2023 |
| ASRock        | B550M-ITX/ac                | [79204339d0](https://linux-hardware.org/?probe=79204339d0) | Feb 11, 2023 |
| HP            | 212B                        | [d3ac338cb9](https://linux-hardware.org/?probe=d3ac338cb9) | Feb 11, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [04929299d7](https://linux-hardware.org/?probe=04929299d7) | Feb 10, 2023 |
| HP            | 212B                        | [cc32aa2d27](https://linux-hardware.org/?probe=cc32aa2d27) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3af865ffdf](https://linux-hardware.org/?probe=3af865ffdf) | Feb 07, 2023 |
| Acer          | F690GVM                     | [8110fd6f99](https://linux-hardware.org/?probe=8110fd6f99) | Feb 07, 2023 |
| Gigabyte      | Z77X-UD3H                   | [6023defc83](https://linux-hardware.org/?probe=6023defc83) | Feb 05, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [c66fb39891](https://linux-hardware.org/?probe=c66fb39891) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [cbac9c37ba](https://linux-hardware.org/?probe=cbac9c37ba) | Feb 04, 2023 |
| Gigabyte      | EP45-UD3P                   | [da7b0aca1f](https://linux-hardware.org/?probe=da7b0aca1f) | Feb 03, 2023 |
| MSI           | D2415 S26361-D2415-A21      | [3acfaaf14c](https://linux-hardware.org/?probe=3acfaaf14c) | Feb 01, 2023 |
| Intel         | D34010WYK H14771-303        | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| HP            | 805A                        | [b33510966e](https://linux-hardware.org/?probe=b33510966e) | Jan 27, 2023 |
| BESSTAR Te... | TH50                        | [da185120e5](https://linux-hardware.org/?probe=da185120e5) | Jan 25, 2023 |
| Dell          | 0KRC95 A01                  | [9580da1eb5](https://linux-hardware.org/?probe=9580da1eb5) | Jan 25, 2023 |
| ASUSTek       | PRIME H510M-A               | [287c632c93](https://linux-hardware.org/?probe=287c632c93) | Jan 21, 2023 |
| ASUSTek       | PRIME H510M-A               | [83529ed276](https://linux-hardware.org/?probe=83529ed276) | Jan 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [a551d228f4](https://linux-hardware.org/?probe=a551d228f4) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| ASUSTek       | Z97-P                       | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| HP            | 87D6 SMVB                   | [cf2b65f039](https://linux-hardware.org/?probe=cf2b65f039) | Jan 12, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | [cc5b67471e](https://linux-hardware.org/?probe=cc5b67471e) | Jan 12, 2023 |
| HP            | 3397                        | [0057e1b40e](https://linux-hardware.org/?probe=0057e1b40e) | Jan 11, 2023 |
| ASRock        | Z87 Extreme6                | [49e3d87de4](https://linux-hardware.org/?probe=49e3d87de4) | Jan 11, 2023 |
| ASUSTek       | M5A97 R2.0                  | [333595c9de](https://linux-hardware.org/?probe=333595c9de) | Jan 10, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [19658b1d4e](https://linux-hardware.org/?probe=19658b1d4e) | Jan 10, 2023 |
| HP            | 3646h                       | [9baf70c121](https://linux-hardware.org/?probe=9baf70c121) | Jan 08, 2023 |
| Foxconn       | ETON                        | [f30a00babb](https://linux-hardware.org/?probe=f30a00babb) | Jan 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [79551dad5b](https://linux-hardware.org/?probe=79551dad5b) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7142941d7c](https://linux-hardware.org/?probe=7142941d7c) | Jan 07, 2023 |
| Gigabyte      | EP45-UD3P                   | [fa5bdcfc4c](https://linux-hardware.org/?probe=fa5bdcfc4c) | Jan 06, 2023 |
| ASUSTek       | M5A97                       | [06ff3bed63](https://linux-hardware.org/?probe=06ff3bed63) | Jan 06, 2023 |
| Dell          | 0D881F A06                  | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | EP45-UD3P                   | [d89c5688d2](https://linux-hardware.org/?probe=d89c5688d2) | Jan 03, 2023 |
| Intel         | X79-SERVER V1.1             | [322b016537](https://linux-hardware.org/?probe=322b016537) | Jan 01, 2023 |
| HP            | 339A                        | [8e0b785427](https://linux-hardware.org/?probe=8e0b785427) | Dec 29, 2022 |
| ASUSTek       | PRIME X570-P                | [33fd3ed258](https://linux-hardware.org/?probe=33fd3ed258) | Dec 29, 2022 |
| ASRock        | Z790M-ITX WiFi              | [c1c0ab5824](https://linux-hardware.org/?probe=c1c0ab5824) | Dec 28, 2022 |
| Dell          | 0HN7XN A01                  | [43a0d87199](https://linux-hardware.org/?probe=43a0d87199) | Dec 28, 2022 |
| Foxconn       | 2ADA                        | [7a7d8227ee](https://linux-hardware.org/?probe=7a7d8227ee) | Dec 25, 2022 |
| ASUSTek       | PRIME Z270-P                | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| MSI           | B550-A PRO                  | [3d63d2fe51](https://linux-hardware.org/?probe=3d63d2fe51) | Dec 22, 2022 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [ef5cd85ef3](https://linux-hardware.org/?probe=ef5cd85ef3) | Dec 20, 2022 |
| Gigabyte      | X570S AERO G                | [262a879a99](https://linux-hardware.org/?probe=262a879a99) | Dec 19, 2022 |
| Gigabyte      | Z590I VISION D              | [9787630f1c](https://linux-hardware.org/?probe=9787630f1c) | Dec 12, 2022 |
| ASUSTek       | H170-PRO                    | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| ASUSTek       | PRIME B550M-K               | [fa85be7b33](https://linux-hardware.org/?probe=fa85be7b33) | Dec 12, 2022 |
| ASUSTek       | PRIME B550M-K               | [c8890a2f74](https://linux-hardware.org/?probe=c8890a2f74) | Dec 09, 2022 |
| ASRock        | Z77 Pro3                    | [a2e7958d4a](https://linux-hardware.org/?probe=a2e7958d4a) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | [3184df2bf6](https://linux-hardware.org/?probe=3184df2bf6) | Dec 07, 2022 |
| ASUSTek       | P5Q-E                       | [fb93b5bdfa](https://linux-hardware.org/?probe=fb93b5bdfa) | Dec 06, 2022 |
| MSI           | B450-A PRO MAX              | [8de79673ea](https://linux-hardware.org/?probe=8de79673ea) | Dec 01, 2022 |
| MSI           | B350 GAMING PLUS            | [b840a0d02e](https://linux-hardware.org/?probe=b840a0d02e) | Dec 01, 2022 |
| MSI           | B450-A PRO MAX              | [e2f97abdea](https://linux-hardware.org/?probe=e2f97abdea) | Nov 30, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [a42a4d6080](https://linux-hardware.org/?probe=a42a4d6080) | Nov 29, 2022 |
| MSI           | B350 GAMING PLUS            | [1e016dcb9b](https://linux-hardware.org/?probe=1e016dcb9b) | Nov 26, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [2813bdf250](https://linux-hardware.org/?probe=2813bdf250) | Nov 26, 2022 |
| ASUSTek       | PRIME X370-PRO              | [5b0f04d592](https://linux-hardware.org/?probe=5b0f04d592) | Nov 25, 2022 |
| ASRock        | AB350M-HDV                  | [9484c00cb6](https://linux-hardware.org/?probe=9484c00cb6) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f5fd3e9e4b](https://linux-hardware.org/?probe=f5fd3e9e4b) | Nov 16, 2022 |
| Intel         | D53427RKE G87971-406        | [e3bc504c6e](https://linux-hardware.org/?probe=e3bc504c6e) | Nov 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1472f0a14e](https://linux-hardware.org/?probe=1472f0a14e) | Nov 15, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [00db55919b](https://linux-hardware.org/?probe=00db55919b) | Nov 14, 2022 |
| HP            | 1998                        | [ddcba37929](https://linux-hardware.org/?probe=ddcba37929) | Nov 14, 2022 |
| HP            | 1998                        | [5249f1cdd7](https://linux-hardware.org/?probe=5249f1cdd7) | Nov 14, 2022 |
| Gigabyte      | A320M-H-CF                  | [2a6473f450](https://linux-hardware.org/?probe=2a6473f450) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [c1044ebf60](https://linux-hardware.org/?probe=c1044ebf60) | Nov 13, 2022 |
| Dell          | 0HY9JP A00                  | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| HP            | 8054                        | [08a9a98d04](https://linux-hardware.org/?probe=08a9a98d04) | Nov 10, 2022 |
| HP            | 8054                        | [4ce3ccc26d](https://linux-hardware.org/?probe=4ce3ccc26d) | Nov 09, 2022 |
| ASUSTek       | H97M-PLUS                   | [dc9837cefc](https://linux-hardware.org/?probe=dc9837cefc) | Nov 09, 2022 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [9746d693c3](https://linux-hardware.org/?probe=9746d693c3) | Nov 08, 2022 |
| HP            | 0B4Ch D                     | [6921f657bf](https://linux-hardware.org/?probe=6921f657bf) | Nov 07, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [4b9071c932](https://linux-hardware.org/?probe=4b9071c932) | Nov 01, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [479fdd085d](https://linux-hardware.org/?probe=479fdd085d) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [dfde89926c](https://linux-hardware.org/?probe=dfde89926c) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [135f93d663](https://linux-hardware.org/?probe=135f93d663) | Oct 31, 2022 |
| Acer          | Predator PO3-620            | [e737f3b4bd](https://linux-hardware.org/?probe=e737f3b4bd) | Oct 29, 2022 |
| HP            | 805A                        | [dbe3ff75e8](https://linux-hardware.org/?probe=dbe3ff75e8) | Oct 24, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [59f7d0820f](https://linux-hardware.org/?probe=59f7d0820f) | Oct 20, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [48d48d4c8e](https://linux-hardware.org/?probe=48d48d4c8e) | Oct 19, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | [dfdde1675c](https://linux-hardware.org/?probe=dfdde1675c) | Oct 17, 2022 |
| ASUSTek       | PRIME X370-PRO              | [2495f40df9](https://linux-hardware.org/?probe=2495f40df9) | Oct 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ba8acdb280](https://linux-hardware.org/?probe=ba8acdb280) | Oct 15, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [14891d8a26](https://linux-hardware.org/?probe=14891d8a26) | Oct 13, 2022 |
| Lenovo        | T530-28ICB                  | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| Lenovo        | T530-28ICB                  | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| ASUSTek       | P8P67 LE                    | [08a298f14e](https://linux-hardware.org/?probe=08a298f14e) | Oct 03, 2022 |
| ASUSTek       | P8P67 LE                    | [33cb2c0dce](https://linux-hardware.org/?probe=33cb2c0dce) | Oct 03, 2022 |
| ASUSTek       | P8P67 LE                    | [12486e4114](https://linux-hardware.org/?probe=12486e4114) | Oct 03, 2022 |
| ASUSTek       | Z170-P                      | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0f4b7501b3](https://linux-hardware.org/?probe=0f4b7501b3) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [d603e07087](https://linux-hardware.org/?probe=d603e07087) | Sep 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [a2ebf20cd0](https://linux-hardware.org/?probe=a2ebf20cd0) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| HP            | 0AA0h                       | [5757039d29](https://linux-hardware.org/?probe=5757039d29) | Sep 23, 2022 |
| ASUSTek       | PRIME Z270-P                | [d44ac0cc2a](https://linux-hardware.org/?probe=d44ac0cc2a) | Sep 19, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [e620df9580](https://linux-hardware.org/?probe=e620df9580) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASRock        | H97M Anniversary            | [1b5e2c2e0a](https://linux-hardware.org/?probe=1b5e2c2e0a) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | [649c5fb453](https://linux-hardware.org/?probe=649c5fb453) | Sep 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6168b7089f](https://linux-hardware.org/?probe=6168b7089f) | Sep 11, 2022 |
| ASUSTek       | PRIME Z270-P                | [4a00a1ca0b](https://linux-hardware.org/?probe=4a00a1ca0b) | Sep 10, 2022 |
| Dell          | 0TTDMJ A00                  | [66aa958693](https://linux-hardware.org/?probe=66aa958693) | Sep 08, 2022 |
| ASUSTek       | M4A78T-E                    | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| MSI           | B350M PRO-VDH               | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [3a599be2f2](https://linux-hardware.org/?probe=3a599be2f2) | Sep 03, 2022 |
| Gigabyte      | Z590I VISION D              | [22131a6ec5](https://linux-hardware.org/?probe=22131a6ec5) | Sep 03, 2022 |
| HP            | 805A                        | [477936d851](https://linux-hardware.org/?probe=477936d851) | Aug 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2fd4ef02b3](https://linux-hardware.org/?probe=2fd4ef02b3) | Aug 30, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [4b37519faf](https://linux-hardware.org/?probe=4b37519faf) | Aug 29, 2022 |
| HP            | 339A                        | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| ASRock        | B450M-HDV R4.0              | [a180ab604a](https://linux-hardware.org/?probe=a180ab604a) | Aug 26, 2022 |
| ASUSTek       | H97M-PLUS                   | [6bcc6b550f](https://linux-hardware.org/?probe=6bcc6b550f) | Aug 24, 2022 |
| Acer          | Predator G3620              | [b79ed7b47b](https://linux-hardware.org/?probe=b79ed7b47b) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [1d0c242f30](https://linux-hardware.org/?probe=1d0c242f30) | Aug 23, 2022 |
| ASRock        | Z75 Pro3                    | [4fbe3d2710](https://linux-hardware.org/?probe=4fbe3d2710) | Aug 22, 2022 |
| Acer          | Predator PO5-600s V:1.0     | [6e8b922033](https://linux-hardware.org/?probe=6e8b922033) | Aug 18, 2022 |
| Foxconn       | 2ABF                        | [eaea01215e](https://linux-hardware.org/?probe=eaea01215e) | Aug 17, 2022 |
| Dell          | 0C27VV A01                  | [04f75d45cb](https://linux-hardware.org/?probe=04f75d45cb) | Aug 15, 2022 |
| ASUSTek       | PRIME B550M-A               | [bd608fb7bc](https://linux-hardware.org/?probe=bd608fb7bc) | Aug 13, 2022 |
| HP            | 805A                        | [c7671a704a](https://linux-hardware.org/?probe=c7671a704a) | Aug 11, 2022 |
| ASUSTek       | M5A97 R2.0                  | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [ea9b6a4757](https://linux-hardware.org/?probe=ea9b6a4757) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [4e9256cf7f](https://linux-hardware.org/?probe=4e9256cf7f) | Aug 10, 2022 |
| ASUSTek       | Z87-PRO                     | [89a77b442f](https://linux-hardware.org/?probe=89a77b442f) | Aug 09, 2022 |
| Gigabyte      | H55M-UD2H                   | [4d6a861120](https://linux-hardware.org/?probe=4d6a861120) | Aug 07, 2022 |
| Gigabyte      | Z77X-UD3H                   | [db843c1cae](https://linux-hardware.org/?probe=db843c1cae) | Aug 07, 2022 |
| HP            | 1497                        | [2fe6cb5b2c](https://linux-hardware.org/?probe=2fe6cb5b2c) | Aug 07, 2022 |
| HP            | 1497                        | [24959f2c80](https://linux-hardware.org/?probe=24959f2c80) | Aug 07, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [d5e820b393](https://linux-hardware.org/?probe=d5e820b393) | Aug 03, 2022 |
| ASUSTek       | PRIME B450M-A               | [97dba8f5e3](https://linux-hardware.org/?probe=97dba8f5e3) | Aug 02, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Gigabyte      | B85-HD3                     | [ca37936b6f](https://linux-hardware.org/?probe=ca37936b6f) | Jul 28, 2022 |
| ASRock        | X399 Taichi                 | [d2eb8a032b](https://linux-hardware.org/?probe=d2eb8a032b) | Jul 26, 2022 |
| ASUSTek       | PRIME Z270-A                | [70ddacf43f](https://linux-hardware.org/?probe=70ddacf43f) | Jul 25, 2022 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | [cda18f8739](https://linux-hardware.org/?probe=cda18f8739) | Jul 22, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [b35dabeb45](https://linux-hardware.org/?probe=b35dabeb45) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | [2625b243eb](https://linux-hardware.org/?probe=2625b243eb) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | [25728e964b](https://linux-hardware.org/?probe=25728e964b) | Jul 20, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [9558ff01e9](https://linux-hardware.org/?probe=9558ff01e9) | Jul 20, 2022 |
| Dell          | 0GM819                      | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| HP            | 3647h                       | [f59774eab5](https://linux-hardware.org/?probe=f59774eab5) | Jun 30, 2022 |
| Gigabyte      | B150-HD3P-CF                | [c62062eac9](https://linux-hardware.org/?probe=c62062eac9) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [36bf4dc378](https://linux-hardware.org/?probe=36bf4dc378) | Jun 13, 2022 |
| Dell          | 0RW203                      | [d53558bc85](https://linux-hardware.org/?probe=d53558bc85) | Jun 12, 2022 |
| Supermicro    | X10SBA-LA                   | [4b46c69e08](https://linux-hardware.org/?probe=4b46c69e08) | Jun 03, 2022 |
| ASUSTek       | P8H67                       | [dff99aa7e6](https://linux-hardware.org/?probe=dff99aa7e6) | May 30, 2022 |
| HP            | 1998                        | [48be2e4a99](https://linux-hardware.org/?probe=48be2e4a99) | May 30, 2022 |
| HP            | 1998                        | [d68e99102e](https://linux-hardware.org/?probe=d68e99102e) | May 29, 2022 |
| ASRock        | X99 Taichi                  | [18ec1a6a1a](https://linux-hardware.org/?probe=18ec1a6a1a) | May 25, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | [ee04d8165a](https://linux-hardware.org/?probe=ee04d8165a) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| Gigabyte      | B550 GAMING X V2            | [a84132c514](https://linux-hardware.org/?probe=a84132c514) | May 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [0e42effbfb](https://linux-hardware.org/?probe=0e42effbfb) | May 17, 2022 |
| ASUSTek       | H97M-PLUS                   | [d2e3603431](https://linux-hardware.org/?probe=d2e3603431) | May 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [244be4f232](https://linux-hardware.org/?probe=244be4f232) | May 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [587c1deb4c](https://linux-hardware.org/?probe=587c1deb4c) | May 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [3fe223176c](https://linux-hardware.org/?probe=3fe223176c) | May 13, 2022 |
| ASUSTek       | P8H67                       | [d94b81d9d3](https://linux-hardware.org/?probe=d94b81d9d3) | May 12, 2022 |
| HP            | 805F                        | [466bb8cc36](https://linux-hardware.org/?probe=466bb8cc36) | May 10, 2022 |
| ASUSTek       | P8B75-V                     | [b4ecefaba5](https://linux-hardware.org/?probe=b4ecefaba5) | May 09, 2022 |
| Acer          | RS780HVF                    | [431353b969](https://linux-hardware.org/?probe=431353b969) | May 09, 2022 |
| MSI           | Z87M GAMING                 | [7e95657ad7](https://linux-hardware.org/?probe=7e95657ad7) | May 08, 2022 |
| ASUSTek       | Z170-A                      | [abccbed349](https://linux-hardware.org/?probe=abccbed349) | May 08, 2022 |
| ASUSTek       | AM1M-A                      | [537def711a](https://linux-hardware.org/?probe=537def711a) | May 08, 2022 |
| Acer          | RS780HVF                    | [1f30630929](https://linux-hardware.org/?probe=1f30630929) | May 08, 2022 |
| ASUSTek       | PRIME X570-PRO              | [f12944a9bd](https://linux-hardware.org/?probe=f12944a9bd) | May 07, 2022 |
| Supermicro    | X8ST3                       | [3cab505f0a](https://linux-hardware.org/?probe=3cab505f0a) | May 05, 2022 |
| Acer          | H57M01                      | [180132b3e1](https://linux-hardware.org/?probe=180132b3e1) | May 03, 2022 |
| Acer          | FX58M                       | [0a6673afb9](https://linux-hardware.org/?probe=0a6673afb9) | May 03, 2022 |
| HP            | 1589                        | [79df2c00dc](https://linux-hardware.org/?probe=79df2c00dc) | May 03, 2022 |
| ASUSTek       | P5B                         | [39c9900546](https://linux-hardware.org/?probe=39c9900546) | May 01, 2022 |
| MSI           | B550-A PRO                  | [0b23621ed1](https://linux-hardware.org/?probe=0b23621ed1) | Apr 30, 2022 |
| Gigabyte      | B450M S2H                   | [2e84d98937](https://linux-hardware.org/?probe=2e84d98937) | Apr 29, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [1612f46137](https://linux-hardware.org/?probe=1612f46137) | Apr 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [822db71f7a](https://linux-hardware.org/?probe=822db71f7a) | Apr 21, 2022 |
| ASRock        | Z87 Extreme6                | [d7e24821ee](https://linux-hardware.org/?probe=d7e24821ee) | Apr 18, 2022 |
| Dell          | 0HY9JP A00                  | [a767ef8b4e](https://linux-hardware.org/?probe=a767ef8b4e) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | [5ce6ef2934](https://linux-hardware.org/?probe=5ce6ef2934) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | [fed643b7ec](https://linux-hardware.org/?probe=fed643b7ec) | Apr 16, 2022 |
| MSI           | Indio                       | [ca3a24d84d](https://linux-hardware.org/?probe=ca3a24d84d) | Apr 13, 2022 |
| MSI           | Z370 PC PRO                 | [2d4574e9fe](https://linux-hardware.org/?probe=2d4574e9fe) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | [b0ffa911b5](https://linux-hardware.org/?probe=b0ffa911b5) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | [5264d55ce2](https://linux-hardware.org/?probe=5264d55ce2) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | [1a910e93c5](https://linux-hardware.org/?probe=1a910e93c5) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | [2d350f40d2](https://linux-hardware.org/?probe=2d350f40d2) | Apr 09, 2022 |
| Acer          | Batman A01                  | [a102f85d9d](https://linux-hardware.org/?probe=a102f85d9d) | Apr 08, 2022 |
| Gigabyte      | H410M H V3                  | [1a1c86083e](https://linux-hardware.org/?probe=1a1c86083e) | Apr 07, 2022 |
| HP            | 18E7                        | [35dbcc5737](https://linux-hardware.org/?probe=35dbcc5737) | Apr 07, 2022 |
| ASUSTek       | B150M-K                     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Acer          | Aspire TC-120               | [a92d7ab62a](https://linux-hardware.org/?probe=a92d7ab62a) | Apr 02, 2022 |
| ASRock        | B85M-ITX                    | [1a2849588f](https://linux-hardware.org/?probe=1a2849588f) | Apr 01, 2022 |
| HP            | 3047h                       | [356fac6a3a](https://linux-hardware.org/?probe=356fac6a3a) | Apr 01, 2022 |
| HP            | 3047h                       | [d4c9852b3c](https://linux-hardware.org/?probe=d4c9852b3c) | Apr 01, 2022 |
| MSI           | 990FXA-GD65                 | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [79c9d66395](https://linux-hardware.org/?probe=79c9d66395) | Mar 26, 2022 |
| Gigabyte      | 990XA-UD3                   | [913cf55cc3](https://linux-hardware.org/?probe=913cf55cc3) | Mar 25, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [7b835e9a57](https://linux-hardware.org/?probe=7b835e9a57) | Mar 23, 2022 |
| ASRock        | AB350M-HDV                  | [069ce018ad](https://linux-hardware.org/?probe=069ce018ad) | Mar 22, 2022 |
| Gigabyte      | H61M-S2PV                   | [6b32e0c788](https://linux-hardware.org/?probe=6b32e0c788) | Mar 10, 2022 |
| Acer          | FX58M                       | [7404e9534e](https://linux-hardware.org/?probe=7404e9534e) | Mar 09, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [2142681934](https://linux-hardware.org/?probe=2142681934) | Mar 06, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [456b0dd391](https://linux-hardware.org/?probe=456b0dd391) | Mar 06, 2022 |
| ASUSTek       | Maximus VIII IMPACT         | [2e19b36624](https://linux-hardware.org/?probe=2e19b36624) | Mar 03, 2022 |
| Acer          | Aspire XC-105               | [0dd55e5b26](https://linux-hardware.org/?probe=0dd55e5b26) | Feb 26, 2022 |
| ABIT          | IP35                        | [278dd592cc](https://linux-hardware.org/?probe=278dd592cc) | Feb 26, 2022 |
| ASUSTek       | Z170-K                      | [cfdffcf6ab](https://linux-hardware.org/?probe=cfdffcf6ab) | Feb 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [f12d1e47df](https://linux-hardware.org/?probe=f12d1e47df) | Feb 24, 2022 |
| ASRock        | AB350M-HDV                  | [5fe85bba2e](https://linux-hardware.org/?probe=5fe85bba2e) | Feb 22, 2022 |
| ASUSTek       | P8Z68 DELUXE                | [8b588bf90b](https://linux-hardware.org/?probe=8b588bf90b) | Feb 15, 2022 |
| ASRock        | 890FX Deluxe4               | [33a47b3c4b](https://linux-hardware.org/?probe=33a47b3c4b) | Feb 11, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [040550cdaa](https://linux-hardware.org/?probe=040550cdaa) | Feb 11, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [ba2262bba5](https://linux-hardware.org/?probe=ba2262bba5) | Feb 10, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [3d76f83751](https://linux-hardware.org/?probe=3d76f83751) | Feb 10, 2022 |
| ASUSTek       | H97M-PLUS                   | [75b31509a3](https://linux-hardware.org/?probe=75b31509a3) | Feb 09, 2022 |
| ASUSTek       | H97M-PLUS                   | [88fdd17fc6](https://linux-hardware.org/?probe=88fdd17fc6) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [22be2d64a2](https://linux-hardware.org/?probe=22be2d64a2) | Feb 06, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [035ccaeec8](https://linux-hardware.org/?probe=035ccaeec8) | Feb 04, 2022 |
| Dell          | 051FJ8 A00                  | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| MSI           | Z170A PC MATE               | [e83deb15fd](https://linux-hardware.org/?probe=e83deb15fd) | Jan 31, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [5f6a8cf57f](https://linux-hardware.org/?probe=5f6a8cf57f) | Jan 29, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [9ff78b6d13](https://linux-hardware.org/?probe=9ff78b6d13) | Jan 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| ASRock        | H510M-HVS                   | [ef779f5d49](https://linux-hardware.org/?probe=ef779f5d49) | Jan 26, 2022 |
| ASRock        | AB350M-HDV                  | [cf5823e07b](https://linux-hardware.org/?probe=cf5823e07b) | Jan 26, 2022 |
| Packard Be... | IMEDIA S3840                | [eff4bf09ec](https://linux-hardware.org/?probe=eff4bf09ec) | Jan 26, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [88049a6cee](https://linux-hardware.org/?probe=88049a6cee) | Jan 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | [8f7c57b03f](https://linux-hardware.org/?probe=8f7c57b03f) | Jan 18, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [5f904131f5](https://linux-hardware.org/?probe=5f904131f5) | Jan 18, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [06c4be96aa](https://linux-hardware.org/?probe=06c4be96aa) | Jan 17, 2022 |
| HP            | 18E5                        | [a06f3d3373](https://linux-hardware.org/?probe=a06f3d3373) | Jan 16, 2022 |
| HP            | 1495                        | [ea7df45832](https://linux-hardware.org/?probe=ea7df45832) | Jan 14, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [e82feb71d2](https://linux-hardware.org/?probe=e82feb71d2) | Jan 12, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [0529614510](https://linux-hardware.org/?probe=0529614510) | Jan 12, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | [1da9aea182](https://linux-hardware.org/?probe=1da9aea182) | Jan 10, 2022 |
| HP            | 3646h                       | [85edd0c1bf](https://linux-hardware.org/?probe=85edd0c1bf) | Jan 08, 2022 |
| HP            | 3646h                       | [616a0acd31](https://linux-hardware.org/?probe=616a0acd31) | Jan 08, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [72fa18d5dd](https://linux-hardware.org/?probe=72fa18d5dd) | Jan 08, 2022 |
| MSI           | H110M ECO                   | [c056a2eafa](https://linux-hardware.org/?probe=c056a2eafa) | Jan 07, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | [6f8a6d74e4](https://linux-hardware.org/?probe=6f8a6d74e4) | Jan 07, 2022 |
| Acer          | WMCP78M                     | [250fa57c5d](https://linux-hardware.org/?probe=250fa57c5d) | Jan 05, 2022 |
| Gigabyte      | 970A-UD3P                   | [c28c0f7f40](https://linux-hardware.org/?probe=c28c0f7f40) | Jan 04, 2022 |
| HP            | 3397                        | [188bb8c669](https://linux-hardware.org/?probe=188bb8c669) | Dec 28, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [a3f574b521](https://linux-hardware.org/?probe=a3f574b521) | Dec 26, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7b2a363709](https://linux-hardware.org/?probe=7b2a363709) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [82a9ed12b5](https://linux-hardware.org/?probe=82a9ed12b5) | Dec 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| ASUSTek       | A_F_K20CE                   | [4365a457d8](https://linux-hardware.org/?probe=4365a457d8) | Dec 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | [a1c07a7e6a](https://linux-hardware.org/?probe=a1c07a7e6a) | Dec 15, 2021 |
| ASRock        | AB350 Pro4                  | [002a05b1c7](https://linux-hardware.org/?probe=002a05b1c7) | Dec 14, 2021 |
| ASUSTek       | Z97-C                       | [3284718afd](https://linux-hardware.org/?probe=3284718afd) | Dec 01, 2021 |
| HP            | 3646h                       | [e7069f8a3b](https://linux-hardware.org/?probe=e7069f8a3b) | Nov 29, 2021 |
| HP            | 3646h                       | [a46d638004](https://linux-hardware.org/?probe=a46d638004) | Nov 29, 2021 |
| ASUSTek       | SABERTOOTH Z87              | [71d6a80bd1](https://linux-hardware.org/?probe=71d6a80bd1) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6591fce926](https://linux-hardware.org/?probe=6591fce926) | Nov 27, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [3355d6fd50](https://linux-hardware.org/?probe=3355d6fd50) | Nov 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [f62619c698](https://linux-hardware.org/?probe=f62619c698) | Nov 24, 2021 |
| Acer          | WMCP78M                     | [5930f530bb](https://linux-hardware.org/?probe=5930f530bb) | Nov 24, 2021 |
| HP            | 3647h                       | [e3d0601f0b](https://linux-hardware.org/?probe=e3d0601f0b) | Nov 23, 2021 |
| Gigabyte      | Z270X-Gaming K5             | [613686da3f](https://linux-hardware.org/?probe=613686da3f) | Nov 22, 2021 |
| HP            | 8433 11                     | [e88c3d4a94](https://linux-hardware.org/?probe=e88c3d4a94) | Nov 22, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [89c87a0f8c](https://linux-hardware.org/?probe=89c87a0f8c) | Nov 21, 2021 |
| Dell          | 0WMJ54 A01                  | [b1f845a48f](https://linux-hardware.org/?probe=b1f845a48f) | Nov 20, 2021 |
| Lenovo        | ThinkStation S20 4157FY2    | [b05be2384d](https://linux-hardware.org/?probe=b05be2384d) | Nov 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d0581432da](https://linux-hardware.org/?probe=d0581432da) | Nov 20, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [646919d578](https://linux-hardware.org/?probe=646919d578) | Nov 20, 2021 |
| Dell          | 00F82W A01                  | [972f96ba1d](https://linux-hardware.org/?probe=972f96ba1d) | Nov 17, 2021 |
| ASRock        | B450M-HDV                   | [d004277425](https://linux-hardware.org/?probe=d004277425) | Nov 14, 2021 |
| MSI           | X570-A PRO                  | [1d72b572ac](https://linux-hardware.org/?probe=1d72b572ac) | Nov 14, 2021 |
| HP            | 1495                        | [d66a2a8cf5](https://linux-hardware.org/?probe=d66a2a8cf5) | Nov 10, 2021 |
| Lenovo        | Kabini CRB 31900003 STD     | [4d94fd8ba6](https://linux-hardware.org/?probe=4d94fd8ba6) | Nov 10, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [b98565dc8e](https://linux-hardware.org/?probe=b98565dc8e) | Nov 09, 2021 |
| HP            | 1495                        | [22bbd228cb](https://linux-hardware.org/?probe=22bbd228cb) | Nov 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8cf09365a4](https://linux-hardware.org/?probe=8cf09365a4) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [10faa36c81](https://linux-hardware.org/?probe=10faa36c81) | Nov 06, 2021 |
| ASUSTek       | A_F_K20CE                   | [a40335233e](https://linux-hardware.org/?probe=a40335233e) | Nov 04, 2021 |
| ASRock        | Z87 Extreme6                | [32b0b7b787](https://linux-hardware.org/?probe=32b0b7b787) | Nov 04, 2021 |
| ABIT          | AI7                         | [75f77dabe1](https://linux-hardware.org/?probe=75f77dabe1) | Nov 03, 2021 |
| ASUSTek       | M2N-E                       | [dfa80f4b9f](https://linux-hardware.org/?probe=dfa80f4b9f) | Oct 31, 2021 |
| ASRock        | 970 Extreme4                | [e10152abc8](https://linux-hardware.org/?probe=e10152abc8) | Oct 25, 2021 |
| ASRock        | 970 Extreme4                | [0f6daccd63](https://linux-hardware.org/?probe=0f6daccd63) | Oct 25, 2021 |
| ASUSTek       | PRIME Z270-P                | [5b429fd560](https://linux-hardware.org/?probe=5b429fd560) | Oct 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [477512ba5c](https://linux-hardware.org/?probe=477512ba5c) | Oct 23, 2021 |
| Gigabyte      | Z170-HD3P-CF                | [c487ba6138](https://linux-hardware.org/?probe=c487ba6138) | Oct 22, 2021 |
| HP            | 158B                        | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [8961245abb](https://linux-hardware.org/?probe=8961245abb) | Oct 15, 2021 |
| ASUSTek       | P8Z68-V                     | [e8ad89cb87](https://linux-hardware.org/?probe=e8ad89cb87) | Oct 12, 2021 |
| HP            | 21D0                        | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [818fe93a6d](https://linux-hardware.org/?probe=818fe93a6d) | Oct 10, 2021 |
| Gigabyte      | Z170-HD3P-CF                | [319f2002de](https://linux-hardware.org/?probe=319f2002de) | Oct 09, 2021 |
| Dell          | 0YC523                      | [cf8d063deb](https://linux-hardware.org/?probe=cf8d063deb) | Oct 09, 2021 |
| MSI           | Z370-A PRO                  | [e7742aa472](https://linux-hardware.org/?probe=e7742aa472) | Oct 03, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | [0c5e4a2345](https://linux-hardware.org/?probe=0c5e4a2345) | Oct 02, 2021 |
| HP            | 0AACh                       | [37766217ae](https://linux-hardware.org/?probe=37766217ae) | Sep 30, 2021 |
| Medion        | B460H6-EM                   | [b461764429](https://linux-hardware.org/?probe=b461764429) | Sep 27, 2021 |
| MSI           | MS-7211                     | [bb7e83b8cb](https://linux-hardware.org/?probe=bb7e83b8cb) | Sep 25, 2021 |
| Lenovo        | ThinkCentre M91p 7033J54    | [7ded59f42f](https://linux-hardware.org/?probe=7ded59f42f) | Sep 21, 2021 |
| ASRock        | B450M-HDV R4.0              | [78fc85808c](https://linux-hardware.org/?probe=78fc85808c) | Sep 05, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [22390a295d](https://linux-hardware.org/?probe=22390a295d) | Sep 04, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [7467c9452c](https://linux-hardware.org/?probe=7467c9452c) | Sep 01, 2021 |
| Gigabyte      | H97N-WIFI                   | [bee6b88bab](https://linux-hardware.org/?probe=bee6b88bab) | Aug 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [fa40b359a1](https://linux-hardware.org/?probe=fa40b359a1) | Aug 27, 2021 |
| Acer          | RS780HVF                    | [f051228785](https://linux-hardware.org/?probe=f051228785) | Aug 21, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [33bfc09a3a](https://linux-hardware.org/?probe=33bfc09a3a) | Aug 17, 2021 |
| Acer          | RS780HVF                    | [32c3b00b51](https://linux-hardware.org/?probe=32c3b00b51) | Aug 14, 2021 |
| Acer          | RS780HVF                    | [858844ae39](https://linux-hardware.org/?probe=858844ae39) | Aug 14, 2021 |
| Acer          | Predator G3-710             | [bc8ec0cacc](https://linux-hardware.org/?probe=bc8ec0cacc) | Aug 14, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| ASUSTek       | PRIME X470-PRO              | [21b619d91b](https://linux-hardware.org/?probe=21b619d91b) | Aug 11, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [c69570237c](https://linux-hardware.org/?probe=c69570237c) | Aug 10, 2021 |
| Gigabyte      | B360HD3PLM-CF               | [ab5514ae70](https://linux-hardware.org/?probe=ab5514ae70) | Aug 06, 2021 |
| ASRock        | Z87 Extreme6                | [ec6b248ebe](https://linux-hardware.org/?probe=ec6b248ebe) | Aug 03, 2021 |
| ASRock        | 939A785GMH/128M             | [fe09c8fdc1](https://linux-hardware.org/?probe=fe09c8fdc1) | Aug 03, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [d6735c5f18](https://linux-hardware.org/?probe=d6735c5f18) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [734237b1dc](https://linux-hardware.org/?probe=734237b1dc) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [9ce0842819](https://linux-hardware.org/?probe=9ce0842819) | Aug 02, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [0451bc276f](https://linux-hardware.org/?probe=0451bc276f) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [754750effc](https://linux-hardware.org/?probe=754750effc) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0f19cc3c0e](https://linux-hardware.org/?probe=0f19cc3c0e) | Jul 31, 2021 |
| ASUSTek       | P5K-VM                      | [1b2a02afbe](https://linux-hardware.org/?probe=1b2a02afbe) | Jul 31, 2021 |
| HP            | 8437                        | [06f61b9a3f](https://linux-hardware.org/?probe=06f61b9a3f) | Jul 27, 2021 |
| HP            | 8437                        | [3e06775292](https://linux-hardware.org/?probe=3e06775292) | Jul 27, 2021 |
| MSI           | Z370 SLI PLUS               | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| Intel         | DP55WG AAE57269-407         | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| HP            | 8437                        | [0764df2f0a](https://linux-hardware.org/?probe=0764df2f0a) | Jul 24, 2021 |
| ASUSTek       | M2N68-AM Plus               | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| ASRock        | 939A785GMH/128M             | [f363c1063a](https://linux-hardware.org/?probe=f363c1063a) | Jul 22, 2021 |
| Gigabyte      | Z270X-Gaming K5             | [384c090a20](https://linux-hardware.org/?probe=384c090a20) | Jul 22, 2021 |
| Dell          | 0C27VV A01                  | [99b906c497](https://linux-hardware.org/?probe=99b906c497) | Jul 21, 2021 |
| Dell          | 0GH911                      | [2aa93c89cd](https://linux-hardware.org/?probe=2aa93c89cd) | Jul 21, 2021 |
| Dell          | 0VHWTR A01                  | [5116710fe0](https://linux-hardware.org/?probe=5116710fe0) | Jul 20, 2021 |
| HP            | 802F                        | [469561ff27](https://linux-hardware.org/?probe=469561ff27) | Jul 20, 2021 |
| ASUSTek       | A88XM-PLUS                  | [4f9f3cbb83](https://linux-hardware.org/?probe=4f9f3cbb83) | Jul 18, 2021 |
| ASUSTek       | NARRA2                      | [e7e7f905c7](https://linux-hardware.org/?probe=e7e7f905c7) | Jul 17, 2021 |
| ASUSTek       | NARRA2                      | [40f65831a3](https://linux-hardware.org/?probe=40f65831a3) | Jul 17, 2021 |
| MSI           | MEG X570 GODLIKE            | [517a612c58](https://linux-hardware.org/?probe=517a612c58) | Jul 10, 2021 |
| Pegatron      | 2AB6                        | [d5eb8c32fb](https://linux-hardware.org/?probe=d5eb8c32fb) | Jul 06, 2021 |
| MSI           | Z370-A PRO                  | [557af42b3d](https://linux-hardware.org/?probe=557af42b3d) | Jul 03, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [2043830384](https://linux-hardware.org/?probe=2043830384) | Jun 26, 2021 |
| ASRock        | Z370 Professional Gaming... | [fa3749c0c0](https://linux-hardware.org/?probe=fa3749c0c0) | Jun 22, 2021 |
| ASUSTek       | PRIME Z370-P                | [8ec235f1f1](https://linux-hardware.org/?probe=8ec235f1f1) | Jun 13, 2021 |
| Dell          | 0GH911                      | [3d8aec55af](https://linux-hardware.org/?probe=3d8aec55af) | Jun 10, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [e0db4d0875](https://linux-hardware.org/?probe=e0db4d0875) | Jun 08, 2021 |
| ASRockRack    | B450D4U-V1L                 | [49a0eec9f5](https://linux-hardware.org/?probe=49a0eec9f5) | Jun 05, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [a750453ba5](https://linux-hardware.org/?probe=a750453ba5) | Jun 04, 2021 |
| Gigabyte      | B360HD3PLM-CF               | [a434845c16](https://linux-hardware.org/?probe=a434845c16) | Jun 03, 2021 |
| ASUSTek       | M4A78LT-M                   | [ef97789a6a](https://linux-hardware.org/?probe=ef97789a6a) | May 27, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | [a266b8dd81](https://linux-hardware.org/?probe=a266b8dd81) | May 27, 2021 |
| MSI           | Z370 PC PRO                 | [ddfe32e6ab](https://linux-hardware.org/?probe=ddfe32e6ab) | May 25, 2021 |
| ASUSTek       | P7P55D EVO                  | [66c62dc8f8](https://linux-hardware.org/?probe=66c62dc8f8) | May 22, 2021 |
| HP            | 8433 11                     | [8670420e76](https://linux-hardware.org/?probe=8670420e76) | May 21, 2021 |
| ASRock        | X99M Extreme4               | [fba004a752](https://linux-hardware.org/?probe=fba004a752) | May 20, 2021 |
| ASUSTek       | P8H67                       | [fa879ee1d2](https://linux-hardware.org/?probe=fa879ee1d2) | May 19, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [249ab0aa24](https://linux-hardware.org/?probe=249ab0aa24) | May 19, 2021 |
| ASRock        | Z77 Pro3                    | [a981f9a0c5](https://linux-hardware.org/?probe=a981f9a0c5) | May 12, 2021 |
| ASUSTek       | UN45H                       | [714a70d40a](https://linux-hardware.org/?probe=714a70d40a) | May 07, 2021 |
| ASUSTek       | A88XM-PLUS                  | [4482a1fb69](https://linux-hardware.org/?probe=4482a1fb69) | May 06, 2021 |
| ASUSTek       | UN45H                       | [efc8ac4c79](https://linux-hardware.org/?probe=efc8ac4c79) | May 06, 2021 |
| ASRock        | Z77 Pro3                    | [3ea8d93c76](https://linux-hardware.org/?probe=3ea8d93c76) | May 05, 2021 |
| HP            | 3647h                       | [bd39210291](https://linux-hardware.org/?probe=bd39210291) | May 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | [9482db99b9](https://linux-hardware.org/?probe=9482db99b9) | May 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | [4af6233f97](https://linux-hardware.org/?probe=4af6233f97) | May 03, 2021 |
| ASRock        | X570M Pro4                  | [ef52974aaf](https://linux-hardware.org/?probe=ef52974aaf) | May 03, 2021 |
| ASRock        | X570M Pro4                  | [1c94c5b005](https://linux-hardware.org/?probe=1c94c5b005) | May 03, 2021 |
| MSI           | 2A9C                        | [fbb37a1ceb](https://linux-hardware.org/?probe=fbb37a1ceb) | May 02, 2021 |
| MSI           | 2A9C                        | [1b4573b9c5](https://linux-hardware.org/?probe=1b4573b9c5) | May 02, 2021 |
| Dell          | 0T10XW A01                  | [4ab0e6b099](https://linux-hardware.org/?probe=4ab0e6b099) | May 01, 2021 |
| MSI           | Z370-A PRO                  | [470be454f6](https://linux-hardware.org/?probe=470be454f6) | Apr 23, 2021 |
| HP            | 1998                        | [9bb6ae0565](https://linux-hardware.org/?probe=9bb6ae0565) | Apr 18, 2021 |
| ASRock        | Z87 Extreme6                | [6ac1485bc6](https://linux-hardware.org/?probe=6ac1485bc6) | Apr 17, 2021 |
| Pegatron      | APX85-GS                    | [3a6accac1f](https://linux-hardware.org/?probe=3a6accac1f) | Apr 12, 2021 |
| ASUSTek       | P5E                         | [8689ac73b3](https://linux-hardware.org/?probe=8689ac73b3) | Apr 11, 2021 |
| Pegatron      | 2A99                        | [07a84a3b4d](https://linux-hardware.org/?probe=07a84a3b4d) | Apr 11, 2021 |
| HP            | 0A00h                       | [144a5f7819](https://linux-hardware.org/?probe=144a5f7819) | Apr 09, 2021 |
| ASUSTek       | PRIME Z390-P                | [055066b50a](https://linux-hardware.org/?probe=055066b50a) | Apr 08, 2021 |
| Pegatron      | 2A72h                       | [e1fff3ade4](https://linux-hardware.org/?probe=e1fff3ade4) | Apr 07, 2021 |
| MSI           | B450I GAMING PLUS AC        | [88b1b582b5](https://linux-hardware.org/?probe=88b1b582b5) | Apr 01, 2021 |
| Gigabyte      | B550 AORUS PRO              | [e88c887878](https://linux-hardware.org/?probe=e88c887878) | Apr 01, 2021 |
| ASUSTek       | STRIX Z270I GAMING          | [2838e1ca6c](https://linux-hardware.org/?probe=2838e1ca6c) | Mar 30, 2021 |
| ASRock        | ALiveNF6G-GLAN              | [1f409f9bf1](https://linux-hardware.org/?probe=1f409f9bf1) | Mar 28, 2021 |
| HP            | 1589                        | [8b3a28644e](https://linux-hardware.org/?probe=8b3a28644e) | Mar 28, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | [25fd34ad8f](https://linux-hardware.org/?probe=25fd34ad8f) | Mar 27, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | [354da6602b](https://linux-hardware.org/?probe=354da6602b) | Mar 27, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | [04469024ca](https://linux-hardware.org/?probe=04469024ca) | Mar 27, 2021 |
| HP            | 8054                        | [b3bc9388b0](https://linux-hardware.org/?probe=b3bc9388b0) | Mar 27, 2021 |
| HP            | 1589                        | [7b3c9bf186](https://linux-hardware.org/?probe=7b3c9bf186) | Mar 27, 2021 |
| ASUSTek       | Z87-K                       | [c412261d89](https://linux-hardware.org/?probe=c412261d89) | Mar 26, 2021 |
| HP            | 802F                        | [ae40d5cbc9](https://linux-hardware.org/?probe=ae40d5cbc9) | Mar 24, 2021 |
| ASUSTek       | P7H55D-M EVO                | [ccb057337e](https://linux-hardware.org/?probe=ccb057337e) | Mar 23, 2021 |
| Shuttle       | FZ77                        | [ca3dfc266d](https://linux-hardware.org/?probe=ca3dfc266d) | Mar 20, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [63c58340d1](https://linux-hardware.org/?probe=63c58340d1) | Mar 20, 2021 |
| Gigabyte      | M61PME-S2P                  | [72fc5ffa15](https://linux-hardware.org/?probe=72fc5ffa15) | Mar 18, 2021 |
| HP            | 1495                        | [23947d4a1e](https://linux-hardware.org/?probe=23947d4a1e) | Mar 17, 2021 |
| ASUSTek       | Acacia                      | [51a2e8c7b7](https://linux-hardware.org/?probe=51a2e8c7b7) | Mar 17, 2021 |
| Dell          | 0C27VV A01                  | [48f8273cdb](https://linux-hardware.org/?probe=48f8273cdb) | Mar 16, 2021 |
| Unknown       | Unknown                     | [e9c99960d1](https://linux-hardware.org/?probe=e9c99960d1) | Mar 16, 2021 |
| ASUSTek       | P5N32-E SLI                 | [11caeb50ac](https://linux-hardware.org/?probe=11caeb50ac) | Mar 16, 2021 |
| MSI           | B450I GAMING PLUS AC        | [3d16f2ffb4](https://linux-hardware.org/?probe=3d16f2ffb4) | Mar 16, 2021 |
| ASUSTek       | Z87-K                       | [2cbefa6c90](https://linux-hardware.org/?probe=2cbefa6c90) | Mar 15, 2021 |
| MSI           | H81M-P33                    | [9487818af0](https://linux-hardware.org/?probe=9487818af0) | Mar 13, 2021 |
| HP            | 859C                        | [6434de9da7](https://linux-hardware.org/?probe=6434de9da7) | Mar 13, 2021 |
| ASRock        | X570 Phantom Gaming X       | [feedeb2b69](https://linux-hardware.org/?probe=feedeb2b69) | Mar 12, 2021 |
| ASUSTek       | STRIX Z270I GAMING          | [e83e8ffa64](https://linux-hardware.org/?probe=e83e8ffa64) | Mar 08, 2021 |
| ASRock        | 990FX Extreme3              | [ee5505ce8e](https://linux-hardware.org/?probe=ee5505ce8e) | Mar 05, 2021 |
| ASUSTek       | P5E                         | [adac4a8f70](https://linux-hardware.org/?probe=adac4a8f70) | Mar 04, 2021 |
| Intel         | DH77KC AAG39641-401         | [1af2ede26c](https://linux-hardware.org/?probe=1af2ede26c) | Mar 03, 2021 |
| ASRock        | 990FX Extreme6              | [8b50e7792e](https://linux-hardware.org/?probe=8b50e7792e) | Mar 02, 2021 |
| Gigabyte      | Z490 VISION D               | [0ac71fbeba](https://linux-hardware.org/?probe=0ac71fbeba) | Feb 28, 2021 |
| ASRock        | P67 Extreme4                | [1f91d9a631](https://linux-hardware.org/?probe=1f91d9a631) | Feb 27, 2021 |
| ASRock        | P67 Extreme4                | [ad443f47c2](https://linux-hardware.org/?probe=ad443f47c2) | Feb 27, 2021 |
| HP            | 805A                        | [26d9d2a996](https://linux-hardware.org/?probe=26d9d2a996) | Feb 25, 2021 |
| ASRock        | A320M-HDV                   | [cd111b2c04](https://linux-hardware.org/?probe=cd111b2c04) | Feb 25, 2021 |
| Lenovo        | ThinkCentre M91p 7033J54    | [762e158923](https://linux-hardware.org/?probe=762e158923) | Feb 25, 2021 |
| ASUSTek       | H97M-PLUS                   | [bcbcbdf158](https://linux-hardware.org/?probe=bcbcbdf158) | Feb 25, 2021 |
| Lenovo        | ThinkCentre M90 5485W45     | [90fa6e7434](https://linux-hardware.org/?probe=90fa6e7434) | Feb 24, 2021 |
| Lenovo        | ThinkCentre M90 5485W45     | [601807d0e7](https://linux-hardware.org/?probe=601807d0e7) | Feb 24, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [84ddb6cbec](https://linux-hardware.org/?probe=84ddb6cbec) | Feb 24, 2021 |
| Dell          | 0C27VV A01                  | [d47c258b89](https://linux-hardware.org/?probe=d47c258b89) | Feb 22, 2021 |
| Gigabyte      | G31M-ES2L                   | [ccd37902d0](https://linux-hardware.org/?probe=ccd37902d0) | Feb 22, 2021 |
| Dell          | 0YC523                      | [d805d39715](https://linux-hardware.org/?probe=d805d39715) | Feb 22, 2021 |
| ASUSTek       | P5KPL-CM                    | [c116602ad6](https://linux-hardware.org/?probe=c116602ad6) | Feb 18, 2021 |
| ASUSTek       | H97M-PLUS                   | [b1e9a3d14d](https://linux-hardware.org/?probe=b1e9a3d14d) | Feb 18, 2021 |
| ASUSTek       | Z87M-PLUS                   | [d90fd08234](https://linux-hardware.org/?probe=d90fd08234) | Feb 17, 2021 |
| ECS           | Nettle3                     | [fb2a315c43](https://linux-hardware.org/?probe=fb2a315c43) | Feb 16, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [ce117380dd](https://linux-hardware.org/?probe=ce117380dd) | Feb 14, 2021 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [9862174836](https://linux-hardware.org/?probe=9862174836) | Feb 13, 2021 |
| ASUSTek       | P8H77-V LE                  | [99f3171b76](https://linux-hardware.org/?probe=99f3171b76) | Feb 10, 2021 |
| ASUSTek       | P8H77-V LE                  | [e052a51f58](https://linux-hardware.org/?probe=e052a51f58) | Feb 10, 2021 |
| ASRock        | 970 Extreme4                | [dee973015c](https://linux-hardware.org/?probe=dee973015c) | Feb 09, 2021 |
| ASRock        | X570 Phantom Gaming X       | [c0ada2d30c](https://linux-hardware.org/?probe=c0ada2d30c) | Feb 08, 2021 |
| Gigabyte      | GA-970A-UD3                 | [71a56734c1](https://linux-hardware.org/?probe=71a56734c1) | Feb 07, 2021 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [826729feac](https://linux-hardware.org/?probe=826729feac) | Feb 07, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [389456d6b7](https://linux-hardware.org/?probe=389456d6b7) | Feb 06, 2021 |
| ASUSTek       | P7P55D PRO                  | [3e78bc9f2c](https://linux-hardware.org/?probe=3e78bc9f2c) | Feb 06, 2021 |
| ASUSTek       | M3A78-EM                    | [95af098c68](https://linux-hardware.org/?probe=95af098c68) | Feb 05, 2021 |
| HP            | 0A64h                       | [6b5e34333d](https://linux-hardware.org/?probe=6b5e34333d) | Feb 04, 2021 |
| ASRock        | 990FX Extreme3              | [e5ac3cd7e2](https://linux-hardware.org/?probe=e5ac3cd7e2) | Feb 04, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [47d61a08a0](https://linux-hardware.org/?probe=47d61a08a0) | Jan 31, 2021 |
| Lenovo        | IC 310S-08IGM               | [e546964d97](https://linux-hardware.org/?probe=e546964d97) | Jan 31, 2021 |
| Lenovo        | IC 310S-08IGM               | [80124b02cf](https://linux-hardware.org/?probe=80124b02cf) | Jan 31, 2021 |
| ASUSTek       | P5G41T-M LX PLUS            | [ef58793cd1](https://linux-hardware.org/?probe=ef58793cd1) | Jan 29, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [897d7d00d7](https://linux-hardware.org/?probe=897d7d00d7) | Jan 27, 2021 |
| AOpen         | D1007 0BB4                  | [8e09b52f79](https://linux-hardware.org/?probe=8e09b52f79) | Jan 24, 2021 |
| AOpen         | D1007 0BB4                  | [73d0723981](https://linux-hardware.org/?probe=73d0723981) | Jan 21, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [d4d4c84bc5](https://linux-hardware.org/?probe=d4d4c84bc5) | Jan 19, 2021 |
| HP            | 844C                        | [f9e65434d6](https://linux-hardware.org/?probe=f9e65434d6) | Jan 16, 2021 |
| ASUSTek       | M5A97 R2.0                  | [0e5edf7f67](https://linux-hardware.org/?probe=0e5edf7f67) | Jan 14, 2021 |
| ASUSTek       | M5A97 R2.0                  | [4d2826d61b](https://linux-hardware.org/?probe=4d2826d61b) | Jan 13, 2021 |
| Dell          | 0Y958C A00                  | [6a52898067](https://linux-hardware.org/?probe=6a52898067) | Jan 12, 2021 |
| MSI           | AMETHYST-M                  | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| Dell          | 0YC523                      | [ef04db7b3d](https://linux-hardware.org/?probe=ef04db7b3d) | Jan 04, 2021 |
| MSI           | Z170A GAMING M5             | [fde14ce5dd](https://linux-hardware.org/?probe=fde14ce5dd) | Jan 04, 2021 |
| MSI           | Z170A GAMING M5             | [f120a3b7a1](https://linux-hardware.org/?probe=f120a3b7a1) | Jan 04, 2021 |
| ASUSTek       | Z87-K                       | [aa039f37b7](https://linux-hardware.org/?probe=aa039f37b7) | Dec 30, 2020 |
| Packard Be... | RS740                       | [5ce58f1cfb](https://linux-hardware.org/?probe=5ce58f1cfb) | Dec 30, 2020 |
| MSI           | B360M MORTAR                | [96a4f4f86f](https://linux-hardware.org/?probe=96a4f4f86f) | Dec 29, 2020 |
| MSI           | B360M MORTAR                | [770704b41d](https://linux-hardware.org/?probe=770704b41d) | Dec 29, 2020 |
| ASUSTek       | Z170I PRO GAMING            | [a4ad398189](https://linux-hardware.org/?probe=a4ad398189) | Dec 28, 2020 |
| ASUSTek       | Z87-PRO                     | [38bf55661f](https://linux-hardware.org/?probe=38bf55661f) | Dec 28, 2020 |
| ASUSTek       | Z87-PRO                     | [9c1f8e8a57](https://linux-hardware.org/?probe=9c1f8e8a57) | Dec 28, 2020 |
| Foxconn       | 2AA9                        | [ad51692f6a](https://linux-hardware.org/?probe=ad51692f6a) | Dec 26, 2020 |
| Intel         | D34010WYK H14771-303        | [3a3ce906e2](https://linux-hardware.org/?probe=3a3ce906e2) | Dec 25, 2020 |
| ASUSTek       | M4A785TD-M EVO              | [4b40fc00f6](https://linux-hardware.org/?probe=4b40fc00f6) | Dec 20, 2020 |
| HP            | 1850                        | [a92e22af3c](https://linux-hardware.org/?probe=a92e22af3c) | Dec 19, 2020 |
| ASRock        | G41C-GS                     | [822e9847fc](https://linux-hardware.org/?probe=822e9847fc) | Dec 19, 2020 |
| ASRockRack    | B450D4U-V1L                 | [53bda46668](https://linux-hardware.org/?probe=53bda46668) | Dec 17, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [4e7ff831eb](https://linux-hardware.org/?probe=4e7ff831eb) | Dec 14, 2020 |
| MSI           | MS-7211                     | [d5848092f3](https://linux-hardware.org/?probe=d5848092f3) | Dec 14, 2020 |
| Foxconn       | 2ADA                        | [0b3c20a9d9](https://linux-hardware.org/?probe=0b3c20a9d9) | Dec 12, 2020 |
| ASUSTek       | H110M-C                     | [cde1c20a36](https://linux-hardware.org/?probe=cde1c20a36) | Dec 12, 2020 |
| Foxconn       | 2ADA                        | [1aedfd747c](https://linux-hardware.org/?probe=1aedfd747c) | Dec 12, 2020 |
| Gigabyte      | H370 HD3-CF                 | [16778aa65b](https://linux-hardware.org/?probe=16778aa65b) | Dec 11, 2020 |
| Lenovo        | SDK0E50510 WIN              | [79400c58bc](https://linux-hardware.org/?probe=79400c58bc) | Dec 11, 2020 |
| Gigabyte      | H370 HD3-CF                 | [3167aca45c](https://linux-hardware.org/?probe=3167aca45c) | Dec 10, 2020 |
| HP            | 2AF3                        | [66cb088231](https://linux-hardware.org/?probe=66cb088231) | Dec 10, 2020 |
| HP            | 2AF3                        | [839c9749a0](https://linux-hardware.org/?probe=839c9749a0) | Dec 10, 2020 |
| ASUSTek       | M4A785T-M                   | [44e7dff3d3](https://linux-hardware.org/?probe=44e7dff3d3) | Dec 10, 2020 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [b9e091029f](https://linux-hardware.org/?probe=b9e091029f) | Dec 10, 2020 |
| ASRock        | G41C-GS                     | [84feb3d2f6](https://linux-hardware.org/?probe=84feb3d2f6) | Dec 10, 2020 |
| ASRock        | G41C-GS                     | [92ad61acb2](https://linux-hardware.org/?probe=92ad61acb2) | Dec 10, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e4dc25a528](https://linux-hardware.org/?probe=e4dc25a528) | Dec 09, 2020 |
| Gigabyte      | B360M D3H-CF                | [27f9412b8a](https://linux-hardware.org/?probe=27f9412b8a) | Dec 08, 2020 |
| Acer          | Aspire XC600 v1.0           | [5a3c92338e](https://linux-hardware.org/?probe=5a3c92338e) | Dec 08, 2020 |
| ASUSTek       | PRIME B550-PLUS             | [0d011c1658](https://linux-hardware.org/?probe=0d011c1658) | Nov 30, 2020 |
| ASUSTek       | PRIME X370-PRO              | [45e6832bd6](https://linux-hardware.org/?probe=45e6832bd6) | Nov 26, 2020 |
| Acer          | Aspire TC-603               | [79605fa1a1](https://linux-hardware.org/?probe=79605fa1a1) | Nov 24, 2020 |
| ASRockRack    | B450D4U-V1L                 | [19c11c3ffd](https://linux-hardware.org/?probe=19c11c3ffd) | Nov 24, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cd25862710](https://linux-hardware.org/?probe=cd25862710) | Nov 20, 2020 |
| HP            | 198E                        | [1c885683dc](https://linux-hardware.org/?probe=1c885683dc) | Nov 19, 2020 |
| ASUSTek       | P5G41T-M LE                 | [e7fe53d106](https://linux-hardware.org/?probe=e7fe53d106) | Nov 18, 2020 |
| HP            | 1998                        | [1346951067](https://linux-hardware.org/?probe=1346951067) | Nov 12, 2020 |
| HP            | 1998                        | [dece9d28a6](https://linux-hardware.org/?probe=dece9d28a6) | Nov 12, 2020 |
| HP            | 1998                        | [00c2c438c0](https://linux-hardware.org/?probe=00c2c438c0) | Nov 11, 2020 |
| HP            | 1998                        | [3772df1169](https://linux-hardware.org/?probe=3772df1169) | Nov 11, 2020 |
| HP            | 1998                        | [7c1b7a3a8f](https://linux-hardware.org/?probe=7c1b7a3a8f) | Nov 11, 2020 |
| MSI           | G41M-P28                    | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Dell          | 0T656F A02                  | [cae149b8a1](https://linux-hardware.org/?probe=cae149b8a1) | Nov 11, 2020 |
| HP            | 1998                        | [e3874c5181](https://linux-hardware.org/?probe=e3874c5181) | Nov 11, 2020 |
| MSI           | G41M-P28                    | [afee9b144d](https://linux-hardware.org/?probe=afee9b144d) | Nov 11, 2020 |
| ASUSTek       | P8H67                       | [58e6f9543d](https://linux-hardware.org/?probe=58e6f9543d) | Nov 10, 2020 |
| ASUSTek       | P8H67                       | [4ac5a781a1](https://linux-hardware.org/?probe=4ac5a781a1) | Nov 10, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [5234189221](https://linux-hardware.org/?probe=5234189221) | Nov 08, 2020 |
| HP            | 1495                        | [931bc038c8](https://linux-hardware.org/?probe=931bc038c8) | Nov 07, 2020 |
| HP            | 1495                        | [a2c50ab08e](https://linux-hardware.org/?probe=a2c50ab08e) | Nov 07, 2020 |
| MSI           | Z97M-G43                    | [58cf86104b](https://linux-hardware.org/?probe=58cf86104b) | Nov 03, 2020 |
| MSI           | B450-A PRO MAX              | [b348fef370](https://linux-hardware.org/?probe=b348fef370) | Nov 02, 2020 |
| ASUSTek       | P5KPL-CM                    | [0352b345cb](https://linux-hardware.org/?probe=0352b345cb) | Nov 02, 2020 |
| Pegatron      | NARRA3                      | [0ed9f03fcd](https://linux-hardware.org/?probe=0ed9f03fcd) | Nov 01, 2020 |
| Pegatron      | NARRA3                      | [2fbfcbd44d](https://linux-hardware.org/?probe=2fbfcbd44d) | Oct 31, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [0745eca4eb](https://linux-hardware.org/?probe=0745eca4eb) | Oct 31, 2020 |
| Foxconn       | 2ABF                        | [a4caa7de36](https://linux-hardware.org/?probe=a4caa7de36) | Oct 30, 2020 |
| ASUSTek       | M5A97 R2.0                  | [80424d0c76](https://linux-hardware.org/?probe=80424d0c76) | Oct 30, 2020 |
| ASRock        | B150M-DVS R2.0              | [fe0d972e21](https://linux-hardware.org/?probe=fe0d972e21) | Oct 29, 2020 |
| ASUSTek       | M4A785TD-M EVO              | [1bad9ab1dd](https://linux-hardware.org/?probe=1bad9ab1dd) | Oct 29, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | [3f18f3f21e](https://linux-hardware.org/?probe=3f18f3f21e) | Oct 28, 2020 |
| ASUSTek       | P6T                         | [3ac523398e](https://linux-hardware.org/?probe=3ac523398e) | Oct 28, 2020 |
| ASUSTek       | H97M-PLUS                   | [0441a81235](https://linux-hardware.org/?probe=0441a81235) | Oct 27, 2020 |
| Supermicro    | X9SCI/X9SCA                 | [311e5dfe10](https://linux-hardware.org/?probe=311e5dfe10) | Oct 25, 2020 |
| Dell          | 0T656F A02                  | [92ccdd2770](https://linux-hardware.org/?probe=92ccdd2770) | Oct 24, 2020 |
| Gigabyte      | Z170-Gaming K3-CF           | [002d0884a9](https://linux-hardware.org/?probe=002d0884a9) | Oct 22, 2020 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [9d3c97dea2](https://linux-hardware.org/?probe=9d3c97dea2) | Oct 21, 2020 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [4609337b52](https://linux-hardware.org/?probe=4609337b52) | Oct 20, 2020 |
| ASUSTek       | PRIME Z370-P                | [aaeb2157bb](https://linux-hardware.org/?probe=aaeb2157bb) | Oct 19, 2020 |
| Gigabyte      | B550 AORUS PRO              | [2779444bba](https://linux-hardware.org/?probe=2779444bba) | Oct 19, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8892c91b74](https://linux-hardware.org/?probe=8892c91b74) | Oct 19, 2020 |
| ASRock        | J3710-ITX                   | [3f1b610426](https://linux-hardware.org/?probe=3f1b610426) | Oct 18, 2020 |
| Acer          | Aspire XC-605               | [77bfaa4cf4](https://linux-hardware.org/?probe=77bfaa4cf4) | Oct 17, 2020 |
| ASRockRack    | B450D4U-V1L                 | [423121e43d](https://linux-hardware.org/?probe=423121e43d) | Oct 12, 2020 |
| Acer          | WMCP78M                     | [85191c5734](https://linux-hardware.org/?probe=85191c5734) | Oct 07, 2020 |
| ASUSTek       | PRIME Z370-P                | [db2d04c102](https://linux-hardware.org/?probe=db2d04c102) | Oct 07, 2020 |
| ASUSTek       | Maximus VI EXTREME          | [a6995dcd50](https://linux-hardware.org/?probe=a6995dcd50) | Oct 07, 2020 |
| ASUSTek       | Z170M-PLUS                  | [0de2f730e6](https://linux-hardware.org/?probe=0de2f730e6) | Oct 07, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | [fba1eca372](https://linux-hardware.org/?probe=fba1eca372) | Oct 05, 2020 |
| ASUSTek       | P5E                         | [6cb501be5f](https://linux-hardware.org/?probe=6cb501be5f) | Oct 05, 2020 |
| MSI           | 990FXA-GD65                 | [fe2c088ea6](https://linux-hardware.org/?probe=fe2c088ea6) | Oct 03, 2020 |
| Lenovo        | 3098 0B98401 PRO            | [2221632b84](https://linux-hardware.org/?probe=2221632b84) | Oct 03, 2020 |
| MSI           | 990FXA-GD65                 | [e4175eb759](https://linux-hardware.org/?probe=e4175eb759) | Oct 03, 2020 |
| HP            | 3397                        | [3d20bbed7a](https://linux-hardware.org/?probe=3d20bbed7a) | Oct 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [3c907dd84e](https://linux-hardware.org/?probe=3c907dd84e) | Oct 03, 2020 |
| ASUSTek       | H81I-PLUS                   | [3770254bcd](https://linux-hardware.org/?probe=3770254bcd) | Oct 02, 2020 |
| ASRock        | FM2A75 Pro4                 | [a57ba9c332](https://linux-hardware.org/?probe=a57ba9c332) | Sep 29, 2020 |
| ASUSTek       | P8Z68-V GEN3                | [ac4a6958b0](https://linux-hardware.org/?probe=ac4a6958b0) | Sep 29, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [0bd951036d](https://linux-hardware.org/?probe=0bd951036d) | Sep 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | [bfb9828008](https://linux-hardware.org/?probe=bfb9828008) | Sep 28, 2020 |
| WeiBu         | WTGLKC1R120 SD-BS-CJ41G-... | [37b2dd7af9](https://linux-hardware.org/?probe=37b2dd7af9) | Sep 28, 2020 |
| ASUSTek       | PRIME Z390M-PLUS            | [495415d7ad](https://linux-hardware.org/?probe=495415d7ad) | Sep 28, 2020 |
| ASUSTek       | PRIME Z390-A                | [63e778d2be](https://linux-hardware.org/?probe=63e778d2be) | Sep 28, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [9edecf1b35](https://linux-hardware.org/?probe=9edecf1b35) | Sep 28, 2020 |
| Intel         | D946GZIS AAD66165-301       | [f8df50faeb](https://linux-hardware.org/?probe=f8df50faeb) | Sep 27, 2020 |
| MSI           | Z77A-G45                    | [28a219f7b8](https://linux-hardware.org/?probe=28a219f7b8) | Sep 23, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | [333f34e356](https://linux-hardware.org/?probe=333f34e356) | Sep 20, 2020 |
| ASUSTek       | M4A78T-E                    | [6fe22c6007](https://linux-hardware.org/?probe=6fe22c6007) | Sep 20, 2020 |
| ASUSTek       | KRPA-U16 Series             | [588c3eb0ba](https://linux-hardware.org/?probe=588c3eb0ba) | Sep 18, 2020 |
| ASUSTek       | Z10PA-U8 Series             | [f60b4c96e0](https://linux-hardware.org/?probe=f60b4c96e0) | Sep 18, 2020 |
| ASUSTek       | Z10PA-U8 Series             | [bfc568f6d8](https://linux-hardware.org/?probe=bfc568f6d8) | Sep 18, 2020 |
| MSI           | B350M PRO-VDH               | [16827d150f](https://linux-hardware.org/?probe=16827d150f) | Sep 18, 2020 |
| MSI           | B350M PRO-VDH               | [10a678dfa9](https://linux-hardware.org/?probe=10a678dfa9) | Sep 18, 2020 |
| MSI           | B350M PRO-VDH               | [b1cc6e2b49](https://linux-hardware.org/?probe=b1cc6e2b49) | Sep 18, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [1896a5c345](https://linux-hardware.org/?probe=1896a5c345) | Sep 17, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0cf8ee1ae8](https://linux-hardware.org/?probe=0cf8ee1ae8) | Sep 16, 2020 |
| ASRock        | B450M Pro4                  | [9df4d6c8b1](https://linux-hardware.org/?probe=9df4d6c8b1) | Sep 15, 2020 |
| ASUSTek       | Z170-A                      | [81cb15062d](https://linux-hardware.org/?probe=81cb15062d) | Sep 14, 2020 |
| ASRock        | Z87 Extreme6                | [8e26b54de5](https://linux-hardware.org/?probe=8e26b54de5) | Sep 12, 2020 |
| Gigabyte      | X570 AORUS PRO              | [086d35ff5c](https://linux-hardware.org/?probe=086d35ff5c) | Sep 12, 2020 |
| Intel         | D946GZIS AAD66165-301       | [517c09218d](https://linux-hardware.org/?probe=517c09218d) | Sep 10, 2020 |
| Foxconn       | 2ADA                        | [5a32535dcd](https://linux-hardware.org/?probe=5a32535dcd) | Sep 10, 2020 |
| ASUSTek       | X99-PRO/USB                 | [231f0afb76](https://linux-hardware.org/?probe=231f0afb76) | Sep 09, 2020 |
| MSI           | B450I GAMING PLUS AC        | [0b87386e6a](https://linux-hardware.org/?probe=0b87386e6a) | Sep 09, 2020 |
| ASRock        | B450M-HDV R4.0              | [cf465b6ceb](https://linux-hardware.org/?probe=cf465b6ceb) | Sep 05, 2020 |
| Gigabyte      | F2A88XN-WIFI                | [342b54e7a0](https://linux-hardware.org/?probe=342b54e7a0) | Sep 04, 2020 |
| MSI           | B450I GAMING PLUS AC        | [d3510ce4e2](https://linux-hardware.org/?probe=d3510ce4e2) | Sep 04, 2020 |
| ASRock        | B450M-HDV R4.0              | [34b84c17b7](https://linux-hardware.org/?probe=34b84c17b7) | Sep 04, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [900f200c57](https://linux-hardware.org/?probe=900f200c57) | Sep 03, 2020 |
| ASUSTek       | M5A97 R2.0                  | [b511e8b52a](https://linux-hardware.org/?probe=b511e8b52a) | Aug 31, 2020 |
| Intel         | D946GZIS AAD66165-301       | [10e5c82714](https://linux-hardware.org/?probe=10e5c82714) | Aug 31, 2020 |
| MSI           | B450M MORTAR MAX            | [d24e39c945](https://linux-hardware.org/?probe=d24e39c945) | Aug 29, 2020 |
| MSI           | B450M MORTAR MAX            | [2a246d5ea8](https://linux-hardware.org/?probe=2a246d5ea8) | Aug 29, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [7640a283c8](https://linux-hardware.org/?probe=7640a283c8) | Aug 28, 2020 |
| HP            | 2AF3                        | [61d714ef58](https://linux-hardware.org/?probe=61d714ef58) | Aug 27, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [7152566435](https://linux-hardware.org/?probe=7152566435) | Aug 23, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [422ee2d231](https://linux-hardware.org/?probe=422ee2d231) | Aug 21, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0230526040](https://linux-hardware.org/?probe=0230526040) | Aug 20, 2020 |
| HP            | 0A64h                       | [223ff53d77](https://linux-hardware.org/?probe=223ff53d77) | Aug 18, 2020 |
| ASUSTek       | PRIME X570-PRO              | [36e63c4f0b](https://linux-hardware.org/?probe=36e63c4f0b) | Aug 18, 2020 |
| ASUSTek       | M4A78T-E                    | [8345dd66f0](https://linux-hardware.org/?probe=8345dd66f0) | Aug 17, 2020 |
| ASUSTek       | Z170M-PLUS                  | [7831468225](https://linux-hardware.org/?probe=7831468225) | Aug 14, 2020 |
| ASUSTek       | Z170M-PLUS                  | [302127e58b](https://linux-hardware.org/?probe=302127e58b) | Aug 14, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [01515127a6](https://linux-hardware.org/?probe=01515127a6) | Aug 11, 2020 |
| MSI           | B450I GAMING PLUS AC        | [d6a59a4350](https://linux-hardware.org/?probe=d6a59a4350) | Aug 10, 2020 |
| ASRock        | Z87 Extreme6                | [9ab8243174](https://linux-hardware.org/?probe=9ab8243174) | Aug 07, 2020 |
| ASUSTek       | H81I-PLUS                   | [7259e07174](https://linux-hardware.org/?probe=7259e07174) | Aug 07, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [ddda943f96](https://linux-hardware.org/?probe=ddda943f96) | Aug 07, 2020 |
| HP            | 198E                        | [321cdddb29](https://linux-hardware.org/?probe=321cdddb29) | Aug 05, 2020 |
| Intel         | D946GZIS AAD66165-301       | [0f40a312c4](https://linux-hardware.org/?probe=0f40a312c4) | Aug 03, 2020 |
| ASRock        | Z87 Extreme6                | [0ab11e1615](https://linux-hardware.org/?probe=0ab11e1615) | Jul 30, 2020 |
| ASUSTek       | Z170M-PLUS                  | [74d141c870](https://linux-hardware.org/?probe=74d141c870) | Jul 30, 2020 |
| ASRock        | B450M Pro4                  | [a05ebd9a3d](https://linux-hardware.org/?probe=a05ebd9a3d) | Jul 29, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [9f29db1cee](https://linux-hardware.org/?probe=9f29db1cee) | Jul 28, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [a68b2400b4](https://linux-hardware.org/?probe=a68b2400b4) | Jul 27, 2020 |
| ASUSTek       | M4A785D-M PRO               | [dcf2273c01](https://linux-hardware.org/?probe=dcf2273c01) | Jul 26, 2020 |
| ASRock        | B450M Pro4                  | [022e082270](https://linux-hardware.org/?probe=022e082270) | Jul 25, 2020 |
| ASRock        | B450M Pro4                  | [6595773d87](https://linux-hardware.org/?probe=6595773d87) | Jul 23, 2020 |
| MSI           | MS-7388                     | [95f9f16df0](https://linux-hardware.org/?probe=95f9f16df0) | Jul 23, 2020 |
| ASUSTek       | P5E                         | [bcea9f0625](https://linux-hardware.org/?probe=bcea9f0625) | Jul 14, 2020 |
| MSI           | B450M MORTAR MAX            | [8b21c297c5](https://linux-hardware.org/?probe=8b21c297c5) | Jul 03, 2020 |
| Pegatron      | 2A99                        | [a2db447eb2](https://linux-hardware.org/?probe=a2db447eb2) | Jul 01, 2020 |
| ASUSTek       | Maximus VII GENE            | [6209226e93](https://linux-hardware.org/?probe=6209226e93) | Jun 23, 2020 |
| Pegatron      | NARRA3                      | [5ba05ac282](https://linux-hardware.org/?probe=5ba05ac282) | Jun 23, 2020 |
| Pegatron      | NARRA3                      | [458687c748](https://linux-hardware.org/?probe=458687c748) | Jun 23, 2020 |
| MSI           | X570-A PRO                  | [8ea0db2339](https://linux-hardware.org/?probe=8ea0db2339) | Jun 15, 2020 |
| MSI           | MS-7211                     | [76c18a99c5](https://linux-hardware.org/?probe=76c18a99c5) | Jun 14, 2020 |
| MSI           | MS-7211                     | [3bad7f0625](https://linux-hardware.org/?probe=3bad7f0625) | Jun 14, 2020 |
| Acer          | RS780HVF                    | [83b78f2956](https://linux-hardware.org/?probe=83b78f2956) | Jun 12, 2020 |
| HP            | 1850                        | [2cc6a94d41](https://linux-hardware.org/?probe=2cc6a94d41) | Jun 11, 2020 |
| HP            | 844C                        | [9ca2de8699](https://linux-hardware.org/?probe=9ca2de8699) | Jun 04, 2020 |
| HP            | 8596                        | [8a317cad1f](https://linux-hardware.org/?probe=8a317cad1f) | Jun 04, 2020 |
| ASRock        | X399 Taichi                 | [9c9844febe](https://linux-hardware.org/?probe=9c9844febe) | Jun 03, 2020 |
| ASUSTek       | VM42                        | [0c45d392cd](https://linux-hardware.org/?probe=0c45d392cd) | Jun 01, 2020 |
| ASUSTek       | P8P67 DELUXE                | [e66cc02c0f](https://linux-hardware.org/?probe=e66cc02c0f) | May 26, 2020 |
| ASRock        | X570 Taichi                 | [0a9aa77797](https://linux-hardware.org/?probe=0a9aa77797) | May 25, 2020 |
| ASRock        | 970 Pro3 R2.0               | [6ac29193c7](https://linux-hardware.org/?probe=6ac29193c7) | May 22, 2020 |
| ASUSTek       | PRIME X570-PRO              | [dac4e0e6ee](https://linux-hardware.org/?probe=dac4e0e6ee) | May 09, 2020 |
| ASUSTek       | Z97-E                       | [64ac218015](https://linux-hardware.org/?probe=64ac218015) | May 04, 2020 |
| ASUSTek       | Z97-E                       | [110eb7afe6](https://linux-hardware.org/?probe=110eb7afe6) | May 04, 2020 |
| HP            | 2AFB                        | [ad8b92b3c2](https://linux-hardware.org/?probe=ad8b92b3c2) | Apr 29, 2020 |
| Pegatron      | 2A72h                       | [e91fa26092](https://linux-hardware.org/?probe=e91fa26092) | Apr 29, 2020 |
| Pegatron      | 2A72h                       | [ba42a81415](https://linux-hardware.org/?probe=ba42a81415) | Apr 28, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [3cef1ebb25](https://linux-hardware.org/?probe=3cef1ebb25) | Apr 23, 2020 |
| ASRock        | X570M Pro4                  | [84162d8ef3](https://linux-hardware.org/?probe=84162d8ef3) | Apr 21, 2020 |
| Gigabyte      | X570 GAMING X               | [b6ddb425af](https://linux-hardware.org/?probe=b6ddb425af) | Apr 12, 2020 |
| ASUSTek       | Z97-P                       | [1e40acf175](https://linux-hardware.org/?probe=1e40acf175) | Apr 09, 2020 |
| ASUSTek       | P8Z77-V LX                  | [893f6857b2](https://linux-hardware.org/?probe=893f6857b2) | Apr 04, 2020 |
| ASUSTek       | H87I-PLUS                   | [0f8a987ceb](https://linux-hardware.org/?probe=0f8a987ceb) | Apr 03, 2020 |
| ASUSTek       | P8Z77-V LX                  | [ec1375a9f8](https://linux-hardware.org/?probe=ec1375a9f8) | Apr 02, 2020 |
| ASUSTek       | CM1855                      | [3b029acc71](https://linux-hardware.org/?probe=3b029acc71) | Apr 02, 2020 |
| Gigabyte      | MFHM17P-00                  | [456a21854c](https://linux-hardware.org/?probe=456a21854c) | Mar 29, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [d925844b9e](https://linux-hardware.org/?probe=d925844b9e) | Mar 25, 2020 |
| ASUSTek       | Rampage IV FORMULA          | [4303c3c3a0](https://linux-hardware.org/?probe=4303c3c3a0) | Mar 24, 2020 |
| ASUSTek       | Rampage IV FORMULA          | [572afffcf7](https://linux-hardware.org/?probe=572afffcf7) | Mar 24, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [165309707f](https://linux-hardware.org/?probe=165309707f) | Mar 24, 2020 |
| ASUSTek       | PRIME B450M-A               | [e973706460](https://linux-hardware.org/?probe=e973706460) | Mar 24, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cdc5018f7b](https://linux-hardware.org/?probe=cdc5018f7b) | Mar 20, 2020 |
| HP            | 0A64h                       | [e525355c31](https://linux-hardware.org/?probe=e525355c31) | Mar 15, 2020 |
| ASUSTek       | PRIME Z370-P                | [5b782ed08d](https://linux-hardware.org/?probe=5b782ed08d) | Mar 15, 2020 |
| ASUSTek       | Maximus VII GENE            | [222a13e152](https://linux-hardware.org/?probe=222a13e152) | Mar 12, 2020 |
| ASUSTek       | Maximus VII GENE            | [f4da492647](https://linux-hardware.org/?probe=f4da492647) | Mar 11, 2020 |
| Gigabyte      | B360M D3H-CF                | [ec4c81e7d9](https://linux-hardware.org/?probe=ec4c81e7d9) | Mar 06, 2020 |
| ASUSTek       | M4A88TD-M EVO               | [1276eb9896](https://linux-hardware.org/?probe=1276eb9896) | Feb 29, 2020 |
| ASUSTek       | Z170-P D3                   | [0dc81f0e45](https://linux-hardware.org/?probe=0dc81f0e45) | Feb 26, 2020 |
| ASUSTek       | G21CN                       | [45598f0644](https://linux-hardware.org/?probe=45598f0644) | Feb 24, 2020 |
| ASUSTek       | PRIME Z370-P                | [5a72aef554](https://linux-hardware.org/?probe=5a72aef554) | Feb 22, 2020 |
| ASRock        | Z97 Extreme4                | [60038b2000](https://linux-hardware.org/?probe=60038b2000) | Feb 21, 2020 |
| ASUSTek       | M5A78L LE                   | [ba36629619](https://linux-hardware.org/?probe=ba36629619) | Feb 15, 2020 |
| ASRock        | Z77 Pro3                    | [698b8aaaed](https://linux-hardware.org/?probe=698b8aaaed) | Feb 09, 2020 |
| ASUSTek       | P9X79 DELUXE                | [c37f970528](https://linux-hardware.org/?probe=c37f970528) | Feb 01, 2020 |
| Gigabyte      | Z97P-D3                     | [f151961dd1](https://linux-hardware.org/?probe=f151961dd1) | Feb 01, 2020 |
| ASUSTek       | M4A78T-E                    | [6059173c99](https://linux-hardware.org/?probe=6059173c99) | Jan 28, 2020 |
| MSI           | B450M PRO-M2                | [04b3edf01b](https://linux-hardware.org/?probe=04b3edf01b) | Jan 25, 2020 |
| ASUSTek       | PRIME X370-PRO              | [4e9e3904fb](https://linux-hardware.org/?probe=4e9e3904fb) | Jan 25, 2020 |
| ASUSTek       | PRIME B350M-A               | [efe2412a0a](https://linux-hardware.org/?probe=efe2412a0a) | Jan 25, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [6eaa1a038c](https://linux-hardware.org/?probe=6eaa1a038c) | Jan 24, 2020 |
| Gigabyte      | X170-WS ECC-CF              | [c284714094](https://linux-hardware.org/?probe=c284714094) | Jan 24, 2020 |
| ASUSTek       | PRIME Z270-A                | [cda0e88379](https://linux-hardware.org/?probe=cda0e88379) | Jan 15, 2020 |
| Intel         | DP55WG AAE57269-408         | [b1606ddfdf](https://linux-hardware.org/?probe=b1606ddfdf) | Jan 14, 2020 |
| ASRock        | X399 Taichi                 | [5ab003017d](https://linux-hardware.org/?probe=5ab003017d) | Jan 09, 2020 |
| ASUSTek       | PRIME Z270-A                | [80297eeeb4](https://linux-hardware.org/?probe=80297eeeb4) | Jan 04, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [ad44824354](https://linux-hardware.org/?probe=ad44824354) | Jan 02, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [a853544a4d](https://linux-hardware.org/?probe=a853544a4d) | Jan 02, 2020 |
| ASUSTek       | M5A78L LE                   | [6c0bf83741](https://linux-hardware.org/?probe=6c0bf83741) | Jan 01, 2020 |
| ASRock        | G31M-GS                     | [857343b33e](https://linux-hardware.org/?probe=857343b33e) | Dec 30, 2019 |
| ASUSTek       | Z170-A                      | [562af84691](https://linux-hardware.org/?probe=562af84691) | Dec 16, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [3973a7cef2](https://linux-hardware.org/?probe=3973a7cef2) | Dec 12, 2019 |
| Lenovo        | ThinkCentre M90p 3652A3G    | [3877a5d3bb](https://linux-hardware.org/?probe=3877a5d3bb) | Dec 09, 2019 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [8e2b5b679e](https://linux-hardware.org/?probe=8e2b5b679e) | Dec 05, 2019 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [b9ff361521](https://linux-hardware.org/?probe=b9ff361521) | Dec 03, 2019 |
| ASUSTek       | P8Z68-V                     | [1f44759168](https://linux-hardware.org/?probe=1f44759168) | Dec 02, 2019 |
| HP            | 1998                        | [ee17d70239](https://linux-hardware.org/?probe=ee17d70239) | Nov 28, 2019 |
| ASUSTek       | P8Z77-V LX                  | [8f2d04de46](https://linux-hardware.org/?probe=8f2d04de46) | Nov 28, 2019 |
| HP            | 1998                        | [78481ffcd4](https://linux-hardware.org/?probe=78481ffcd4) | Nov 17, 2019 |
| Foxconn       | A76ML-K 30                  | [cd69cd71e1](https://linux-hardware.org/?probe=cd69cd71e1) | Nov 12, 2019 |
| Gigabyte      | 970A-DS3P                   | [870d0fe48e](https://linux-hardware.org/?probe=870d0fe48e) | Oct 28, 2019 |
| ASUSTek       | H97M-E                      | [9d2304c49f](https://linux-hardware.org/?probe=9d2304c49f) | Oct 27, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [4dc787cc15](https://linux-hardware.org/?probe=4dc787cc15) | Oct 27, 2019 |
| Gigabyte      | B450 AORUS M                | [b05e61e4d9](https://linux-hardware.org/?probe=b05e61e4d9) | Oct 25, 2019 |
| ASRock        | B450 Pro4                   | [dcfc0b3327](https://linux-hardware.org/?probe=dcfc0b3327) | Oct 23, 2019 |
| ASRock        | B450 Pro4                   | [a29a11899f](https://linux-hardware.org/?probe=a29a11899f) | Oct 23, 2019 |
| ASRock        | B450 Pro4                   | [1740915405](https://linux-hardware.org/?probe=1740915405) | Oct 23, 2019 |
| ASRock        | B450 Pro4                   | [ba98645988](https://linux-hardware.org/?probe=ba98645988) | Oct 23, 2019 |
| ASUSTek       | Z87-K                       | [a2c50a6a82](https://linux-hardware.org/?probe=a2c50a6a82) | Oct 22, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | [afd255688a](https://linux-hardware.org/?probe=afd255688a) | Oct 20, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | [b194fb82fe](https://linux-hardware.org/?probe=b194fb82fe) | Oct 20, 2019 |
| ASUSTek       | PRIME H270-PLUS             | [0656361c4f](https://linux-hardware.org/?probe=0656361c4f) | Oct 19, 2019 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [3f141d1c9d](https://linux-hardware.org/?probe=3f141d1c9d) | Oct 05, 2019 |
| HP            | 0A64h                       | [b3aec62eb9](https://linux-hardware.org/?probe=b3aec62eb9) | Oct 01, 2019 |
| MSI           | Z370 SLI PLUS               | [d6f9a54a5e](https://linux-hardware.org/?probe=d6f9a54a5e) | Sep 04, 2019 |
| Packard Be... | MCP73T-AD                   | [897bde5f15](https://linux-hardware.org/?probe=897bde5f15) | Aug 22, 2019 |
| ASUSTek       | P8H77-I                     | [9a5e6f850c](https://linux-hardware.org/?probe=9a5e6f850c) | Aug 16, 2019 |
| MSI           | Z370 SLI PLUS               | [9d169b5017](https://linux-hardware.org/?probe=9d169b5017) | Aug 14, 2019 |
| ASUSTek       | P8H77-I                     | [3ecc7afdb6](https://linux-hardware.org/?probe=3ecc7afdb6) | Aug 03, 2019 |
| ASUSTek       | TUF B450-PLUS GAMING        | [537d11b224](https://linux-hardware.org/?probe=537d11b224) | Jul 26, 2019 |
| Gigabyte      | P35-DS3                     | [b79ee752b4](https://linux-hardware.org/?probe=b79ee752b4) | Jul 15, 2019 |
| MSI           | IONA                        | [a585eaef35](https://linux-hardware.org/?probe=a585eaef35) | Jul 13, 2019 |
| ASUSTek       | M5A97 R2.0                  | [e2e30d9fb0](https://linux-hardware.org/?probe=e2e30d9fb0) | Jul 09, 2019 |
| ASUSTek       | M5A97 R2.0                  | [a6b185ca6f](https://linux-hardware.org/?probe=a6b185ca6f) | Jul 09, 2019 |
| ASUSTek       | M5A97 R2.0                  | [4ee3c4c06c](https://linux-hardware.org/?probe=4ee3c4c06c) | Jul 09, 2019 |
| HP            | 1497                        | [5ce732df30](https://linux-hardware.org/?probe=5ce732df30) | Jun 21, 2019 |
| ASUSTek       | M4A78                       | [f95aec52e4](https://linux-hardware.org/?probe=f95aec52e4) | Jun 15, 2019 |
| ASUSTek       | PRIME H270-PLUS             | [347d0dbf57](https://linux-hardware.org/?probe=347d0dbf57) | May 29, 2019 |
| ASUSTek       | M4A87TD/USB3                | [a55280bb16](https://linux-hardware.org/?probe=a55280bb16) | May 25, 2019 |
| ASUSTek       | M5A78L LE                   | [8d3a77af71](https://linux-hardware.org/?probe=8d3a77af71) | May 24, 2019 |
| MSI           | 760GM-E51                   | [b23ed61a74](https://linux-hardware.org/?probe=b23ed61a74) | May 13, 2019 |
| Foxconn       | 2ABF                        | [80e41dc351](https://linux-hardware.org/?probe=80e41dc351) | May 10, 2019 |
| MSI           | 760GM-E51                   | [c77558abf8](https://linux-hardware.org/?probe=c77558abf8) | May 01, 2019 |
| Gigabyte      | G1.Sniper Z87               | [8ce5db772c](https://linux-hardware.org/?probe=8ce5db772c) | Apr 17, 2019 |
| Intel         | DG33TL AAD89517-700         | [90ba96cb73](https://linux-hardware.org/?probe=90ba96cb73) | Apr 16, 2019 |
| Intel         | DG33TL AAD89517-700         | [b151450467](https://linux-hardware.org/?probe=b151450467) | Apr 15, 2019 |
| ASRock        | X470 Gaming-ITX/ac          | [1c1b87dea4](https://linux-hardware.org/?probe=1c1b87dea4) | Apr 13, 2019 |
| ASUSTek       | P6T                         | [4db2f20573](https://linux-hardware.org/?probe=4db2f20573) | Apr 07, 2019 |
| ASRock        | AB350M Pro4                 | [855fdd6eac](https://linux-hardware.org/?probe=855fdd6eac) | Mar 19, 2019 |
| ASRock        | Z87 Extreme6                | [96aaa39135](https://linux-hardware.org/?probe=96aaa39135) | Mar 18, 2019 |
| HP            | 1497                        | [357589623a](https://linux-hardware.org/?probe=357589623a) | Feb 23, 2019 |
| ASUSTek       | P6T                         | [5040f012a9](https://linux-hardware.org/?probe=5040f012a9) | Feb 10, 2019 |
| ASUSTek       | P6T                         | [79dfc022fd](https://linux-hardware.org/?probe=79dfc022fd) | Feb 09, 2019 |
| ASRock        | ALiveNF6G-GLAN              | [a89f20ae20](https://linux-hardware.org/?probe=a89f20ae20) | Feb 08, 2019 |
| AOpen         | nMCP7ALPx-DE R1.04 Oct.0... | [b778a6096a](https://linux-hardware.org/?probe=b778a6096a) | Jan 30, 2019 |
| ASRock        | ALiveNF6G-GLAN              | [5ab2a6ed4a](https://linux-hardware.org/?probe=5ab2a6ed4a) | Jan 25, 2019 |
| ASUSTek       | P5LD2EB-DHS                 | [ece39839eb](https://linux-hardware.org/?probe=ece39839eb) | Jan 05, 2019 |
| Intel         | DH61DL AAG14066-202         | [8e77a793e3](https://linux-hardware.org/?probe=8e77a793e3) | Dec 19, 2018 |
| ASUSTek       | M5A78L-M/USB3               | [82325163f4](https://linux-hardware.org/?probe=82325163f4) | Dec 12, 2018 |
| ASUSTek       | M5A78L-M/USB3               | [b699ce4e30](https://linux-hardware.org/?probe=b699ce4e30) | Dec 12, 2018 |
| ASUSTek       | P7H55-M PRO                 | [79918271ca](https://linux-hardware.org/?probe=79918271ca) | Dec 12, 2018 |
| ASUSTek       | H87M-PLUS                   | [0e6e8c5fc5](https://linux-hardware.org/?probe=0e6e8c5fc5) | Dec 10, 2018 |
| ASUSTek       | H81I-PLUS                   | [81d31aab82](https://linux-hardware.org/?probe=81d31aab82) | Nov 30, 2018 |
| ASUSTek       | H81I-PLUS                   | [f1e742b9b3](https://linux-hardware.org/?probe=f1e742b9b3) | Nov 30, 2018 |
| HP            | 2B47                        | [e887d07240](https://linux-hardware.org/?probe=e887d07240) | Nov 19, 2018 |
| HP            | 2B47                        | [447f6778a8](https://linux-hardware.org/?probe=447f6778a8) | Nov 19, 2018 |
| HP            | 3048h                       | [4b5985d50d](https://linux-hardware.org/?probe=4b5985d50d) | Nov 18, 2018 |
| ASUSTek       | P7H55-M PRO                 | [4863c625bf](https://linux-hardware.org/?probe=4863c625bf) | Nov 13, 2018 |
| HP            | 1494                        | [055a009ae7](https://linux-hardware.org/?probe=055a009ae7) | Nov 04, 2018 |
| ASUSTek       | P5GD1-VM                    | [22f77f9153](https://linux-hardware.org/?probe=22f77f9153) | Oct 28, 2018 |
| ASRock        | AB350M Pro4                 | [aa933db296](https://linux-hardware.org/?probe=aa933db296) | Sep 06, 2018 |
| ASUSTek       | X99-E WS                    | [b396839f41](https://linux-hardware.org/?probe=b396839f41) | Jul 31, 2018 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [31bf9ac5b7](https://linux-hardware.org/?probe=31bf9ac5b7) | Jun 21, 2018 |
| Gigabyte      | EP45-DS3R                   | [304f67f539](https://linux-hardware.org/?probe=304f67f539) | Jan 10, 2018 |
| HP            | ProLiant MicroServer        | [eed6dea797](https://linux-hardware.org/?probe=eed6dea797) | Dec 18, 2017 |
| HP            | 3398                        | [eefaeab3db](https://linux-hardware.org/?probe=eefaeab3db) | Dec 09, 2017 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | [5d5433f7bb](https://linux-hardware.org/?probe=5d5433f7bb) | Dec 07, 2017 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | [45a3db7122](https://linux-hardware.org/?probe=45a3db7122) | Dec 07, 2017 |
| Intel         | DH61DL AAG14066-202         | [6fc8f44aa5](https://linux-hardware.org/?probe=6fc8f44aa5) | Oct 18, 2017 |
| HP            | 3398                        | [2685073294](https://linux-hardware.org/?probe=2685073294) | Aug 28, 2017 |
| Lenovo        | ThinkCentre M57 6072WUS     | [d300880847](https://linux-hardware.org/?probe=d300880847) | Feb 09, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Finland/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 74       | 10.83%  |
| Ubuntu 18.04       | 39       | 5.71%   |
| Ubuntu 22.04       | 38       | 5.56%   |
| OpenMandriva 23.01 | 29       | 4.25%   |
| Arch Rolling       | 29       | 4.25%   |
| OpenMandriva 4.2   | 18       | 2.64%   |
| Pop!_OS 22.04      | 17       | 2.49%   |
| Arch               | 15       | 2.2%    |
| Linux Mint 20.1    | 14       | 2.05%   |
| Debian 11          | 13       | 1.9%    |
| OpenMandriva 23.03 | 12       | 1.76%   |
| Gentoo 2.7         | 12       | 1.76%   |
| Manjaro            | 11       | 1.61%   |
| OpenMandriva 4.3   | 10       | 1.46%   |
| Linux Mint 20      | 10       | 1.46%   |
| Fedora 36          | 10       | 1.46%   |
| Ubuntu 20.10       | 9        | 1.32%   |
| Linux Mint 20.3    | 9        | 1.32%   |
| Xubuntu 18.04      | 8        | 1.17%   |
| Pop!_OS 21.04      | 8        | 1.17%   |
| ArcoLinux Rolling  | 8        | 1.17%   |
| Xubuntu 20.04      | 7        | 1.02%   |
| Pop!_OS 20.04      | 7        | 1.02%   |
| Linux Mint 19.3    | 7        | 1.02%   |
| Debian Testing     | 7        | 1.02%   |
| Debian 10          | 7        | 1.02%   |
| Zorin 16           | 6        | 0.88%   |
| Ubuntu 21.10       | 6        | 0.88%   |
| Ubuntu 21.04       | 6        | 0.88%   |
| Ubuntu 19.10       | 6        | 0.88%   |
| KDE neon 20.04     | 6        | 0.88%   |
| Fedora 32          | 6        | 0.88%   |
| Debian 12          | 6        | 0.88%   |
| Ubuntu 23.04       | 5        | 0.73%   |
| Ubuntu 19.04       | 5        | 0.73%   |
| ROSA R10           | 5        | 0.73%   |
| Pop!_OS 20.10      | 5        | 0.73%   |
| OpenMandriva 4.50  | 5        | 0.73%   |
| Linux Mint 21.1    | 5        | 0.73%   |
| Kubuntu 22.04      | 5        | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 184      | 28.75%  |
| OpenMandriva  | 74       | 11.56%  |
| Linux Mint    | 44       | 6.88%   |
| Arch          | 44       | 6.88%   |
| Pop!_OS       | 38       | 5.94%   |
| Fedora        | 37       | 5.78%   |
| Debian        | 35       | 5.47%   |
| Manjaro       | 31       | 4.84%   |
| Gentoo        | 18       | 2.81%   |
| Xubuntu       | 17       | 2.66%   |
| Kubuntu       | 12       | 1.88%   |
| ROSA          | 10       | 1.56%   |
| openSUSE      | 9        | 1.41%   |
| KDE neon      | 9        | 1.41%   |
| ArcoLinux     | 9        | 1.41%   |
| Zorin         | 7        | 1.09%   |
| Lubuntu       | 7        | 1.09%   |
| Ubuntu MATE   | 6        | 0.94%   |
| CentOS        | 6        | 0.94%   |
| MX            | 5        | 0.78%   |
| Elementary    | 4        | 0.63%   |
| Ubuntu Unity  | 3        | 0.47%   |
| Peppermint    | 3        | 0.47%   |
| Nobara        | 3        | 0.47%   |
| EndeavourOS   | 3        | 0.47%   |
| BlackPanther  | 3        | 0.47%   |
| Void Linux    | 2        | 0.31%   |
| LMDE          | 2        | 0.31%   |
| Clear Linux   | 2        | 0.31%   |
| Artix         | 2        | 0.31%   |
| UbuntuDDE     | 1        | 0.16%   |
| Solus         | 1        | 0.16%   |
| Rocky Linux   | 1        | 0.16%   |
| RHEL          | 1        | 0.16%   |
| Parabola      | 1        | 0.16%   |
| Oracle Linux  | 1        | 0.16%   |
| Garuda Linux  | 1        | 0.16%   |
| Crystal Linux | 1        | 0.16%   |
| antergos      | 1        | 0.16%   |
| ALT Linux     | 1        | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 6.1.1-desktop-1omv2290          | 28       | 3.77%   |
| 5.10.14-desktop-1omv4002        | 18       | 2.43%   |
| 5.4.0-42-generic                | 13       | 1.75%   |
| 6.2.6-desktop-1omv2390          | 10       | 1.35%   |
| 5.4.0-47-generic                | 9        | 1.21%   |
| 5.16.7-desktop-1omv4003         | 9        | 1.21%   |
| 5.8.0-44-generic                | 6        | 0.81%   |
| 5.4.0-65-generic                | 6        | 0.81%   |
| 5.4.0-52-generic                | 6        | 0.81%   |
| 5.4.0-48-generic                | 6        | 0.81%   |
| 5.8.0-41-generic                | 5        | 0.67%   |
| 5.4.0-56-generic                | 5        | 0.67%   |
| 5.4.0-53-generic                | 5        | 0.67%   |
| 5.15.0-58-generic               | 5        | 0.67%   |
| 5.15.0-46-generic               | 5        | 0.67%   |
| 5.15.0-27-generic               | 5        | 0.67%   |
| 5.13.0-7620-generic             | 5        | 0.67%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 5        | 0.67%   |
| 6.0.12-76060006-generic         | 4        | 0.54%   |
| 5.8.0-7630-generic              | 4        | 0.54%   |
| 5.4.0-66-generic                | 4        | 0.54%   |
| 5.4.0-58-generic                | 4        | 0.54%   |
| 5.4.0-54-generic                | 4        | 0.54%   |
| 5.4.0-45-generic                | 4        | 0.54%   |
| 5.19.0-76051900-generic         | 4        | 0.54%   |
| 5.15.28-1-MANJARO               | 4        | 0.54%   |
| 5.15.0-60-generic               | 4        | 0.54%   |
| 5.15.0-52-generic               | 4        | 0.54%   |
| 5.15.0-48-generic               | 4        | 0.54%   |
| 5.13.0-30-generic               | 4        | 0.54%   |
| 4.15.0-29-generic               | 4        | 0.54%   |
| 6.3.5-desktop-3omv2390          | 3        | 0.4%    |
| 6.2.6-76060206-generic          | 3        | 0.4%    |
| 6.1.0-9-amd64                   | 3        | 0.4%    |
| 5.8.0-49-generic                | 3        | 0.4%    |
| 5.8.0-43-generic                | 3        | 0.4%    |
| 5.4.0-92-generic                | 3        | 0.4%    |
| 5.4.0-51-generic                | 3        | 0.4%    |
| 5.3.0-46-generic                | 3        | 0.4%    |
| 5.3.0-40-generic                | 3        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 111      | 15.61%  |
| 5.15.0  | 52       | 7.31%   |
| 5.8.0   | 38       | 5.34%   |
| 4.15.0  | 35       | 4.92%   |
| 6.1.1   | 28       | 3.94%   |
| 5.13.0  | 22       | 3.09%   |
| 5.11.0  | 22       | 3.09%   |
| 5.19.0  | 19       | 2.67%   |
| 5.10.14 | 19       | 2.67%   |
| 6.2.6   | 13       | 1.83%   |
| 5.3.0   | 13       | 1.83%   |
| 5.0.0   | 12       | 1.69%   |
| 5.10.0  | 10       | 1.41%   |
| 4.19.0  | 10       | 1.41%   |
| 5.16.7  | 9        | 1.27%   |
| 4.18.0  | 9        | 1.27%   |
| 6.2.0   | 7        | 0.98%   |
| 6.0.12  | 7        | 0.98%   |
| 6.1.0   | 5        | 0.7%    |
| 4.9.60  | 5        | 0.7%    |
| 5.17.5  | 4        | 0.56%   |
| 5.15.28 | 4        | 0.56%   |
| 5.14.14 | 4        | 0.56%   |
| 5.14.0  | 4        | 0.56%   |
| 5.11.2  | 4        | 0.56%   |
| 6.3.5   | 3        | 0.42%   |
| 6.1.4   | 3        | 0.42%   |
| 6.0.7   | 3        | 0.42%   |
| 6.0.5   | 3        | 0.42%   |
| 6.0.11  | 3        | 0.42%   |
| 5.3.18  | 3        | 0.42%   |
| 5.17.3  | 3        | 0.42%   |
| 5.12.4  | 3        | 0.42%   |
| 5.10.74 | 3        | 0.42%   |
| 4.18.16 | 3        | 0.42%   |
| 3.10.0  | 3        | 0.42%   |
| 6.3.1   | 2        | 0.28%   |
| 6.2.8   | 2        | 0.28%   |
| 6.2.2   | 2        | 0.28%   |
| 6.2.12  | 2        | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 122      | 17.45%  |
| 5.15    | 78       | 11.16%  |
| 5.8     | 50       | 7.15%   |
| 5.10    | 46       | 6.58%   |
| 6.1     | 45       | 6.44%   |
| 4.15    | 36       | 5.15%   |
| 5.11    | 32       | 4.58%   |
| 6.2     | 31       | 4.43%   |
| 5.13    | 29       | 4.15%   |
| 5.19    | 26       | 3.72%   |
| 6.0     | 24       | 3.43%   |
| 5.3     | 19       | 2.72%   |
| 5.16    | 18       | 2.58%   |
| 5.17    | 16       | 2.29%   |
| 5.0     | 13       | 1.86%   |
| 4.19    | 13       | 1.86%   |
| 4.18    | 13       | 1.86%   |
| 6.3     | 10       | 1.43%   |
| 5.14    | 10       | 1.43%   |
| 5.9     | 9        | 1.29%   |
| 5.7     | 9        | 1.29%   |
| 5.18    | 9        | 1.29%   |
| 5.12    | 8        | 1.14%   |
| 5.6     | 6        | 0.86%   |
| 4.9     | 6        | 0.86%   |
| 6.4     | 5        | 0.72%   |
| 5.5     | 5        | 0.72%   |
| 3.10    | 3        | 0.43%   |
| 4.1     | 2        | 0.29%   |
| 5.2     | 1        | 0.14%   |
| 5.1     | 1        | 0.14%   |
| 4.4     | 1        | 0.14%   |
| 4.20    | 1        | 0.14%   |
| 4.13    | 1        | 0.14%   |
| 4.12    | 1        | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 609      | 98.54%  |
| i686   | 9        | 1.46%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 240      | 37.27%  |
| KDE5             | 150      | 23.29%  |
| Unknown          | 93       | 14.44%  |
| XFCE             | 42       | 6.52%   |
| X-Cinnamon       | 33       | 5.12%   |
| MATE             | 24       | 3.73%   |
| KDE              | 17       | 2.64%   |
| LXQt             | 8        | 1.24%   |
| KDE4             | 4        | 0.62%   |
| Cinnamon         | 4        | 0.62%   |
| Unity            | 3        | 0.47%   |
| Pantheon         | 3        | 0.47%   |
| LXDE             | 3        | 0.47%   |
| lightdm-xsession | 3        | 0.47%   |
| GNOME Flashback  | 3        | 0.47%   |
| sway             | 2        | 0.31%   |
| i3               | 2        | 0.31%   |
| DWM              | 2        | 0.31%   |
| Budgie           | 2        | 0.31%   |
| bspwm            | 2        | 0.31%   |
| sway:Unity       | 1        | 0.16%   |
| onyx:GNOME       | 1        | 0.16%   |
| GNOME Classic    | 1        | 0.16%   |
| Deepin           | 1        | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 480      | 75.83%  |
| Wayland | 83       | 13.11%  |
| Tty     | 37       | 5.85%   |
| Unknown | 32       | 5.06%   |
| Web     | 1        | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 298      | 45.85%  |
| SDDM    | 134      | 20.62%  |
| GDM     | 69       | 10.62%  |
| GDM3    | 66       | 10.15%  |
| LightDM | 50       | 7.69%   |
| TDM     | 27       | 4.15%   |
| KDM     | 5        | 0.77%   |
| SLiM    | 1        | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 282      | 44.27%  |
| fi_FI       | 203      | 31.87%  |
| Unknown     | 67       | 10.52%  |
| en_GB       | 35       | 5.49%   |
| C           | 12       | 1.88%   |
| ru_RU       | 8        | 1.26%   |
| en_FI       | 5        | 0.78%   |
| sv_SE       | 3        | 0.47%   |
| sv_FI       | 3        | 0.47%   |
| fr_FR       | 3        | 0.47%   |
| en_DK       | 3        | 0.47%   |
| en_SE       | 2        | 0.31%   |
| C.UTF8      | 2        | 0.31%   |
| POSIX       | 1        | 0.16%   |
| pl_PL       | 1        | 0.16%   |
| it_IT       | 1        | 0.16%   |
| ia_FR       | 1        | 0.16%   |
| fr_CA       | 1        | 0.16%   |
| en_us.utf-8 | 1        | 0.16%   |
| en_IE       | 1        | 0.16%   |
| en_CA       | 1        | 0.16%   |
| af_ZA       | 1        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 361      | 57.03%  |
| EFI  | 272      | 42.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 451      | 70.69%  |
| Btrfs   | 69       | 10.82%  |
| Overlay | 62       | 9.72%   |
| Unknown | 21       | 3.29%   |
| Xfs     | 16       | 2.51%   |
| Tmpfs   | 8        | 1.25%   |
| Zfs     | 7        | 1.1%    |
| F2fs    | 2        | 0.31%   |
| Ext3    | 1        | 0.16%   |
| Ext2    | 1        | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 281      | 44.11%  |
| GPT     | 274      | 43.01%  |
| MBR     | 82       | 12.87%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 481      | 76.11%  |
| Yes       | 151      | 23.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 411      | 65.03%  |
| Yes       | 221      | 34.97%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 229      | 37.12%  |
| Hewlett-Packard     | 76       | 12.32%  |
| MSI                 | 63       | 10.21%  |
| Gigabyte Technology | 59       | 9.56%   |
| ASRock              | 56       | 9.08%   |
| Lenovo              | 20       | 3.24%   |
| Dell                | 20       | 3.24%   |
| Acer                | 20       | 3.24%   |
| Fujitsu             | 19       | 3.08%   |
| Intel               | 11       | 1.78%   |
| Foxconn             | 10       | 1.62%   |
| Pegatron            | 9        | 1.46%   |
| Supermicro          | 3        | 0.49%   |
| Packard Bell        | 3        | 0.49%   |
| AOpen               | 3        | 0.49%   |
| Medion              | 2        | 0.32%   |
| ASRockRack          | 2        | 0.32%   |
| ABIT                | 2        | 0.32%   |
| WeiBu               | 1        | 0.16%   |
| Shuttle             | 1        | 0.16%   |
| Inventec            | 1        | 0.16%   |
| IceWhale Technology | 1        | 0.16%   |
| Fujitsu Siemens     | 1        | 0.16%   |
| ECS                 | 1        | 0.16%   |
| Cisco               | 1        | 0.16%   |
| BESSTAR Tech        | 1        | 0.16%   |
| Apple               | 1        | 0.16%   |
| Unknown             | 1        | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 24       | 3.89%   |
| HP EliteDesk 800 G1 SFF             | 9        | 1.46%   |
| MSI MS-7C37                         | 6        | 0.97%   |
| ASUS TUF Gaming X570-PLUS           | 6        | 0.97%   |
| ASUS ROG STRIX B550-F GAMING        | 6        | 0.97%   |
| ASUS PRIME X370-PRO                 | 5        | 0.81%   |
| ASUS M5A97 R2.0                     | 5        | 0.81%   |
| MSI MS-7A38                         | 4        | 0.65%   |
| HP Compaq 8200 Elite SFF PC         | 4        | 0.65%   |
| Gigabyte X570 AORUS ELITE           | 4        | 0.65%   |
| ASUS TUF B450-PLUS GAMING           | 4        | 0.65%   |
| ASUS Pro WS 565-ACE                 | 4        | 0.65%   |
| ASUS PRIME B350-PLUS                | 4        | 0.65%   |
| MSI MS-7B89                         | 3        | 0.49%   |
| MSI MS-7B49                         | 3        | 0.49%   |
| MSI MS-7B48                         | 3        | 0.49%   |
| Fujitsu ESPRIMO E910                | 3        | 0.49%   |
| Fujitsu D3401-H2 S26361-D3401-H2    | 3        | 0.49%   |
| Dell OptiPlex 780                   | 3        | 0.49%   |
| ASUS TUF Gaming B550-PLUS           | 3        | 0.49%   |
| ASUS ROG STRIX Z370-F GAMING        | 3        | 0.49%   |
| ASUS ROG STRIX B550-I GAMING        | 3        | 0.49%   |
| ASUS PRIME X470-PRO                 | 3        | 0.49%   |
| ASUS PRIME B450-PLUS                | 3        | 0.49%   |
| ASUS M5A97 EVO R2.0                 | 3        | 0.49%   |
| ASRock B450M-HDV R4.0               | 3        | 0.49%   |
| Acer Aspire X3300                   | 3        | 0.49%   |
| MSI MS-7C95                         | 2        | 0.32%   |
| MSI MS-7C84                         | 2        | 0.32%   |
| MSI MS-7C56                         | 2        | 0.32%   |
| MSI MS-7B86                         | 2        | 0.32%   |
| MSI MS-7B46                         | 2        | 0.32%   |
| MSI MS-7A40                         | 2        | 0.32%   |
| Lenovo ThinkCentre M90 5485W45      | 2        | 0.32%   |
| Intel D34010WYK H14771-303          | 2        | 0.32%   |
| HP Z820 Workstation                 | 2        | 0.32%   |
| HP Z420 Workstation                 | 2        | 0.32%   |
| HP Z240 Tower Workstation           | 2        | 0.32%   |
| HP ProDesk 600 G1 TWR               | 2        | 0.32%   |
| HP Pavilion Gaming Desktop 690-00xx | 2        | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 45       | 7.29%   |
| ASUS ROG            | 31       | 5.02%   |
| HP Compaq           | 26       | 4.21%   |
| ASUS All            | 24       | 3.89%   |
| ASUS TUF            | 18       | 2.92%   |
| HP EliteDesk        | 16       | 2.59%   |
| Dell OptiPlex       | 16       | 2.59%   |
| Lenovo ThinkCentre  | 13       | 2.11%   |
| Acer Aspire         | 13       | 2.11%   |
| Fujitsu ESPRIMO     | 11       | 1.78%   |
| ASUS M5A97          | 11       | 1.78%   |
| HP ProDesk          | 8        | 1.3%    |
| Gigabyte X570       | 7        | 1.13%   |
| MSI MS-7C37         | 6        | 0.97%   |
| HP Pavilion         | 6        | 0.97%   |
| ASUS Pro            | 5        | 0.81%   |
| Acer Predator       | 5        | 0.81%   |
| MSI MS-7A38         | 4        | 0.65%   |
| Gigabyte B550       | 4        | 0.65%   |
| ASUS P7P55D         | 4        | 0.65%   |
| ASRock B450M-HDV    | 4        | 0.65%   |
| ASRock 970          | 4        | 0.65%   |
| MSI MS-7B89         | 3        | 0.49%   |
| MSI MS-7B49         | 3        | 0.49%   |
| MSI MS-7B48         | 3        | 0.49%   |
| Fujitsu D3401-H2    | 3        | 0.49%   |
| Dell Precision      | 3        | 0.49%   |
| ASUS P8Z77-V        | 3        | 0.49%   |
| ASUS P8Z68-V        | 3        | 0.49%   |
| ASUS P8P67          | 3        | 0.49%   |
| ASUS P6T            | 3        | 0.49%   |
| ASRock X570         | 3        | 0.49%   |
| ASRock B450         | 3        | 0.49%   |
| Packard Bell IMEDIA | 2        | 0.32%   |
| MSI MS-7C95         | 2        | 0.32%   |
| MSI MS-7C84         | 2        | 0.32%   |
| MSI MS-7C56         | 2        | 0.32%   |
| MSI MS-7B86         | 2        | 0.32%   |
| MSI MS-7B46         | 2        | 0.32%   |
| MSI MS-7A40         | 2        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 70       | 11.35%  |
| 2018 | 64       | 10.37%  |
| 2013 | 58       | 9.4%    |
| 2017 | 56       | 9.08%   |
| 2020 | 47       | 7.62%   |
| 2019 | 46       | 7.46%   |
| 2009 | 42       | 6.81%   |
| 2011 | 38       | 6.16%   |
| 2015 | 31       | 5.02%   |
| 2010 | 30       | 4.86%   |
| 2008 | 28       | 4.54%   |
| 2014 | 27       | 4.38%   |
| 2016 | 22       | 3.57%   |
| 2021 | 16       | 2.59%   |
| 2007 | 15       | 2.43%   |
| 2022 | 12       | 1.94%   |
| 2006 | 8        | 1.3%    |
| 2005 | 3        | 0.49%   |
| 2023 | 2        | 0.32%   |
| 2004 | 2        | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 617      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 603      | 97.42%  |
| Enabled  | 16       | 2.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 617      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 173      | 27.5%   |
| 8.01-16.0       | 111      | 17.65%  |
| 32.01-64.0      | 103      | 16.38%  |
| 3.01-4.0        | 85       | 13.51%  |
| 4.01-8.0        | 79       | 12.56%  |
| 64.01-256.0     | 36       | 5.72%   |
| 24.01-32.0      | 20       | 3.18%   |
| 1.01-2.0        | 13       | 2.07%   |
| 2.01-3.0        | 6        | 0.95%   |
| More than 256.0 | 1        | 0.16%   |
| 0.51-1.0        | 1        | 0.16%   |
| 0.01-0.5        | 1        | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 236      | 34.55%  |
| 2.01-3.0    | 139      | 20.35%  |
| 4.01-8.0    | 109      | 15.96%  |
| 3.01-4.0    | 83       | 12.15%  |
| 0.51-1.0    | 47       | 6.88%   |
| 8.01-16.0   | 45       | 6.59%   |
| 0.01-0.5    | 7        | 1.02%   |
| 16.01-24.0  | 6        | 0.88%   |
| 32.01-64.0  | 5        | 0.73%   |
| 24.01-32.0  | 3        | 0.44%   |
| 0           | 2        | 0.29%   |
| 64.01-256.0 | 1        | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 213      | 32.97%  |
| 2      | 173      | 26.78%  |
| 3      | 116      | 17.96%  |
| 4      | 55       | 8.51%   |
| 5      | 39       | 6.04%   |
| 6      | 15       | 2.32%   |
| 0      | 10       | 1.55%   |
| 7      | 9        | 1.39%   |
| 9      | 6        | 0.93%   |
| 10     | 4        | 0.62%   |
| 8      | 4        | 0.62%   |
| 23     | 1        | 0.15%   |
| 11     | 1        | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 326      | 51.83%  |
| Yes       | 303      | 48.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 613      | 99.35%  |
| No        | 4        | 0.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 378      | 60.67%  |
| Yes       | 245      | 39.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 438      | 70.19%  |
| Yes       | 186      | 29.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Finland | 617      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Helsinki     | 256      | 38.27%  |
| Tampere      | 64       | 9.57%   |
| Turku        | 46       | 6.88%   |
| Oulu         | 42       | 6.28%   |
| Espoo        | 37       | 5.53%   |
| Vantaa       | 20       | 2.99%   |
| Kuopio       | 19       | 2.84%   |
| Jyväskylä  | 15       | 2.24%   |
| Lahti        | 13       | 1.94%   |
| Tuusula      | 9        | 1.35%   |
| Vaasa        | 8        | 1.2%    |
| Raisio       | 8        | 1.2%    |
| Hyvinkaeae   | 8        | 1.2%    |
| Joensuu      | 7        | 1.05%   |
| Raahe        | 6        | 0.9%    |
| Salo         | 5        | 0.75%   |
| Pori         | 5        | 0.75%   |
| Kotka        | 4        | 0.6%    |
| Uusikaupunki | 3        | 0.45%   |
| Seinäjoki   | 3        | 0.45%   |
| Lempäälä  | 3        | 0.45%   |
| Lappeenranta | 3        | 0.45%   |
| Kouvola      | 3        | 0.45%   |
| Hanko        | 3        | 0.45%   |
| Hämeenlinna | 3        | 0.45%   |
| Tupos        | 2        | 0.3%    |
| Tenala       | 2        | 0.3%    |
| Tarvasjoki   | 2        | 0.3%    |
| Solv         | 2        | 0.3%    |
| Rovaniemi    | 2        | 0.3%    |
| Rauma        | 2        | 0.3%    |
| Porlammi     | 2        | 0.3%    |
| Nokia        | 2        | 0.3%    |
| Maenttae     | 2        | 0.3%    |
| Lohja        | 2        | 0.3%    |
| Lieto        | 2        | 0.3%    |
| Klaukkala    | 2        | 0.3%    |
| Kerava       | 2        | 0.3%    |
| Kangasala    | 2        | 0.3%    |
| Heinola      | 2        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 244      | 428    | 20.98%  |
| WDC                         | 225      | 413    | 19.35%  |
| Seagate                     | 181      | 311    | 15.56%  |
| Kingston                    | 167      | 254    | 14.36%  |
| Toshiba                     | 44       | 94     | 3.78%   |
| Crucial                     | 40       | 50     | 3.44%   |
| Intel                       | 36       | 52     | 3.1%    |
| Hitachi                     | 34       | 45     | 2.92%   |
| SanDisk                     | 23       | 27     | 1.98%   |
| A-DATA Technology           | 19       | 26     | 1.63%   |
| Maxtor                      | 13       | 20     | 1.12%   |
| Verbatim                    | 10       | 17     | 0.86%   |
| Phison                      | 10       | 10     | 0.86%   |
| Micron Technology           | 10       | 17     | 0.86%   |
| Corsair                     | 10       | 12     | 0.86%   |
| Unknown                     | 8        | 16     | 0.69%   |
| Transcend                   | 8        | 9      | 0.69%   |
| PNY                         | 8        | 10     | 0.69%   |
| OCZ                         | 8        | 10     | 0.69%   |
| HGST                        | 8        | 19     | 0.69%   |
| SK hynix                    | 7        | 7      | 0.6%    |
| Kingston Technology Company | 4        | 5      | 0.34%   |
| Intenso                     | 4        | 7      | 0.34%   |
| XPG                         | 3        | 5      | 0.26%   |
| LITEONIT                    | 3        | 3      | 0.26%   |
| ADATA Technology            | 3        | 4      | 0.26%   |
| Plextor                     | 2        | 2      | 0.17%   |
| Phison Electronics          | 2        | 3      | 0.17%   |
| Patriot                     | 2        | 5      | 0.17%   |
| OCZ-VERTEX3                 | 2        | 2      | 0.17%   |
| Micron/Crucial Technology   | 2        | 3      | 0.17%   |
| LITEON                      | 2        | 2      | 0.17%   |
| HUAWEI                      | 2        | 2      | 0.17%   |
| Hewlett-Packard             | 2        | 3      | 0.17%   |
| Fujitsu                     | 2        | 2      | 0.17%   |
| USB3.1                      | 1        | 1      | 0.09%   |
| USB3.0                      | 1        | 1      | 0.09%   |
| TSA                         | 1        | 1      | 0.09%   |
| StoreJet                    | 1        | 1      | 0.09%   |
| SPCC                        | 1        | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                           | 29       | 2.08%   |
| Kingston SA400S37240G 240GB SSD                     | 29       | 2.08%   |
| Kingston SA400S37480G 480GB SSD                     | 22       | 1.58%   |
| Samsung SSD 850 EVO 500GB                           | 18       | 1.29%   |
| Kingston SA400S37120G 120GB SSD                     | 18       | 1.29%   |
| Samsung NVMe SSD Drive 500GB                        | 14       | 1.01%   |
| Seagate ST500DM002-1BD142 500GB                     | 13       | 0.93%   |
| Kingston SV300S37A120G 120GB SSD                    | 13       | 0.93%   |
| Samsung SSD 860 EVO 500GB                           | 12       | 0.86%   |
| Kingston SHFS37A120G 120GB SSD                      | 12       | 0.86%   |
| Samsung HD103SJ 1TB                                 | 11       | 0.79%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 10       | 0.72%   |
| Toshiba DT01ACA300 3TB                              | 10       | 0.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 10       | 0.72%   |
| Samsung SSD 860 EVO 1TB                             | 9        | 0.65%   |
| Kingston SV300S37A240G 240GB SSD                    | 9        | 0.65%   |
| WDC WD40EFRX-68WT0N0 4TB                            | 8        | 0.57%   |
| Seagate ST4000DM004-2CV104 4TB                      | 8        | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB                      | 8        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB                      | 8        | 0.57%   |
| Samsung SSD 960 EVO 500GB                           | 8        | 0.57%   |
| Samsung HD501LJ 500GB                               | 8        | 0.57%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 7        | 0.5%    |
| Toshiba DT01ACA100 1TB                              | 7        | 0.5%    |
| Seagate ST31000528AS 1TB                            | 7        | 0.5%    |
| Seagate ST1000DM003-1CH162 1TB                      | 7        | 0.5%    |
| Samsung SSD 840 EVO 120GB                           | 7        | 0.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 7        | 0.5%    |
| Kingston SA400S37960G 960GB SSD                     | 7        | 0.5%    |
| Crucial CT1000MX500SSD1 1TB                         | 7        | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 6        | 0.43%   |
| Verbatim Vi550 S3 SSD 1TB                           | 6        | 0.43%   |
| Seagate ST31000524AS 1TB                            | 6        | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB                      | 6        | 0.43%   |
| Samsung SSD 860 EVO 250GB                           | 6        | 0.43%   |
| Samsung SSD 850 PRO 256GB                           | 6        | 0.43%   |
| Samsung NVMe SSD Drive 1TB                          | 6        | 0.43%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 5        | 0.36%   |
| Seagate ST3250318AS 250GB                           | 5        | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 201      | 358    | 38.88%  |
| Seagate             | 175      | 300    | 33.85%  |
| Samsung Electronics | 42       | 67     | 8.12%   |
| Toshiba             | 36       | 70     | 6.96%   |
| Hitachi             | 34       | 45     | 6.58%   |
| Maxtor              | 13       | 20     | 2.51%   |
| HGST                | 8        | 19     | 1.55%   |
| Unknown             | 2        | 2      | 0.39%   |
| Fujitsu             | 2        | 2      | 0.39%   |
| USB3.0              | 1        | 1      | 0.19%   |
| StoreJet            | 1        | 1      | 0.19%   |
| Hewlett-Packard     | 1        | 1      | 0.19%   |
| External            | 1        | 1      | 0.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 148      | 216    | 31.69%  |
| Kingston            | 148      | 226    | 31.69%  |
| Crucial             | 38       | 47     | 8.14%   |
| WDC                 | 27       | 42     | 5.78%   |
| Intel               | 12       | 26     | 2.57%   |
| Verbatim            | 10       | 17     | 2.14%   |
| SanDisk             | 10       | 10     | 2.14%   |
| Micron Technology   | 10       | 17     | 2.14%   |
| A-DATA Technology   | 10       | 14     | 2.14%   |
| Transcend           | 8        | 9      | 1.71%   |
| OCZ                 | 8        | 10     | 1.71%   |
| PNY                 | 6        | 8      | 1.28%   |
| Corsair             | 6        | 7      | 1.28%   |
| Intenso             | 4        | 7      | 0.86%   |
| Toshiba             | 3        | 10     | 0.64%   |
| LITEONIT            | 3        | 3      | 0.64%   |
| Plextor             | 2        | 2      | 0.43%   |
| Patriot             | 2        | 5      | 0.43%   |
| OCZ-VERTEX3         | 2        | 2      | 0.43%   |
| LITEON              | 2        | 2      | 0.43%   |
| Unknown             | 1        | 1      | 0.21%   |
| TSA                 | 1        | 1      | 0.21%   |
| SPCC                | 1        | 1      | 0.21%   |
| Seagate             | 1        | 1      | 0.21%   |
| OCZ-VERTEX          | 1        | 1      | 0.21%   |
| Hewlett-Packard     | 1        | 2      | 0.21%   |
| China               | 1        | 1      | 0.21%   |
| Unknown             | 1        | 1      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 389      | 887    | 40.19%  |
| SSD     | 363      | 689    | 37.5%   |
| NVMe    | 198      | 307    | 20.45%  |
| Unknown | 16       | 26     | 1.65%   |
| MMC     | 2        | 2      | 0.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 550      | 1532   | 69.62%  |
| NVMe | 198      | 307    | 25.06%  |
| SAS  | 40       | 70     | 5.06%   |
| MMC  | 2        | 2      | 0.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 430      | 851    | 50.83%  |
| 0.51-1.0   | 235      | 354    | 27.78%  |
| 1.01-2.0   | 77       | 124    | 9.1%    |
| 3.01-4.0   | 39       | 104    | 4.61%   |
| 2.01-3.0   | 34       | 73     | 4.02%   |
| 4.01-10.0  | 29       | 68     | 3.43%   |
| 10.01-20.0 | 2        | 2      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 151      | 23.05%  |
| 251-500        | 95       | 14.5%   |
| 501-1000       | 94       | 14.35%  |
| More than 3000 | 78       | 11.91%  |
| 1001-2000      | 65       | 9.92%   |
| 1-20           | 51       | 7.79%   |
| 2001-3000      | 41       | 6.26%   |
| Unknown        | 38       | 5.8%    |
| 51-100         | 30       | 4.58%   |
| 21-50          | 12       | 1.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 229      | 34.44%  |
| 21-50          | 76       | 11.43%  |
| 101-250        | 61       | 9.17%   |
| 501-1000       | 58       | 8.72%   |
| 51-100         | 57       | 8.57%   |
| 251-500        | 51       | 7.67%   |
| 1001-2000      | 40       | 6.02%   |
| Unknown        | 38       | 5.71%   |
| More than 3000 | 32       | 4.81%   |
| 2001-3000      | 23       | 3.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Desktops | Drives | Percent |
|------------------------------------------------|----------|--------|---------|
| WDC WD40EFRX-68WT0N0 4TB                       | 4        | 6      | 4.12%   |
| Samsung Electronics HD103SJ 1TB                | 3        | 4      | 3.09%   |
| Kingston SHFS37A120G 120GB SSD                 | 3        | 4      | 3.09%   |
| Toshiba DT01ACA100 1TB                         | 2        | 2      | 2.06%   |
| Seagate ST3250318AS 250GB                      | 2        | 2      | 2.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2        | 3      | 2.06%   |
| Samsung Electronics SSD 980 1TB                | 2        | 2      | 2.06%   |
| Samsung Electronics SSD 850 EVO 1TB            | 2        | 2      | 2.06%   |
| Micron Technology MTFDDAK512MAM-1K1 512GB SSD  | 2        | 4      | 2.06%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB SSD | 2        | 4      | 2.06%   |
| Maxtor 7Y250M0 250GB                           | 2        | 2      | 2.06%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1        | 1      | 1.03%   |
| WDC WDS120G2G0A-00JH30 120GB SSD               | 1        | 1      | 1.03%   |
| WDC WD6400AAKS-07A7B0 640GB                    | 1        | 1      | 1.03%   |
| WDC WD50EZRZ-32RWYB1 5TB                       | 1        | 1      | 1.03%   |
| WDC WD5000ABPS-01ZZB0 500GB                    | 1        | 1      | 1.03%   |
| WDC WD5000AAKX-00ERMA0 500GB                   | 1        | 1      | 1.03%   |
| WDC WD5000AAKS-22A7B0 500GB                    | 1        | 1      | 1.03%   |
| WDC WD3200YS-01PGB0 320GB                      | 1        | 1      | 1.03%   |
| WDC WD3200BEVT-22ZCT0 320GB                    | 1        | 1      | 1.03%   |
| WDC WD3200AAKS-00L9A0 320GB                    | 1        | 1      | 1.03%   |
| WDC WD3200AAJS-60Z0A0 320GB                    | 1        | 1      | 1.03%   |
| WDC WD3200AAJS-00RYA0 320GB                    | 1        | 1      | 1.03%   |
| WDC WD30EFRX-68EUZN0 3TB                       | 1        | 1      | 1.03%   |
| WDC WD2500AAJS-00V4A0 250GB                    | 1        | 1      | 1.03%   |
| WDC WD20EARS-00MVWB0 2TB                       | 1        | 1      | 1.03%   |
| WDC WD2002FAEX-007BA0 2TB                      | 1        | 1      | 1.03%   |
| WDC WD10EZEX-60ZF5A0 1TB                       | 1        | 1      | 1.03%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 1        | 1      | 1.03%   |
| WDC WD10EARS-22Y5B1 1TB                        | 1        | 1      | 1.03%   |
| WDC WD10EADX-22TDHB0 1TB                       | 1        | 1      | 1.03%   |
| WDC WD10EADS-22M2B0 1TB                        | 1        | 1      | 1.03%   |
| USB3.0 Super Speed 500GB                       | 1        | 1      | 1.03%   |
| Toshiba MQ04ABF100 1TB                         | 1        | 1      | 1.03%   |
| Toshiba HDWA120 2TB                            | 1        | 1      | 1.03%   |
| Seagate ST8000DM004-2CX188 8TB                 | 1        | 1      | 1.03%   |
| Seagate ST500LT012-9WS142 500GB                | 1        | 1      | 1.03%   |
| Seagate ST500LM000-1EJ162-SSHD-8GB             | 1        | 1      | 1.03%   |
| Seagate ST500DM002-1BD142 500GB                | 1        | 1      | 1.03%   |
| Seagate ST500DM002-1BC142 500GB                | 1        | 1      | 1.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 27     | 25.53%  |
| Seagate             | 20       | 22     | 21.28%  |
| Samsung Electronics | 13       | 15     | 13.83%  |
| Kingston            | 11       | 12     | 11.7%   |
| Hitachi             | 5        | 6      | 5.32%   |
| Toshiba             | 4        | 4      | 4.26%   |
| Micron Technology   | 4        | 8      | 4.26%   |
| Maxtor              | 4        | 4      | 4.26%   |
| Intel               | 2        | 2      | 2.13%   |
| Corsair             | 2        | 2      | 2.13%   |
| USB3.0              | 1        | 1      | 1.06%   |
| PNY                 | 1        | 1      | 1.06%   |
| LITEONIT            | 1        | 1      | 1.06%   |
| HGST                | 1        | 1      | 1.06%   |
| A-DATA Technology   | 1        | 1      | 1.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 25     | 35.48%  |
| Seagate             | 20       | 22     | 32.26%  |
| Samsung Electronics | 5        | 6      | 8.06%   |
| Hitachi             | 5        | 6      | 8.06%   |
| Toshiba             | 4        | 4      | 6.45%   |
| Maxtor              | 4        | 4      | 6.45%   |
| USB3.0              | 1        | 1      | 1.61%   |
| HGST                | 1        | 1      | 1.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 60       | 69     | 64.52%  |
| SSD  | 27       | 32     | 29.03%  |
| NVMe | 6        | 6      | 6.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3250318AS 250GB         | 1        | 1      | 50%     |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 322      | 975    | 46%     |
| Works    | 286      | 827    | 40.86%  |
| Malfunc  | 90       | 107    | 12.86%  |
| Failed   | 2        | 2      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 371      | 40.15%  |
| AMD                          | 229      | 24.78%  |
| Samsung Electronics          | 97       | 10.5%   |
| ASMedia Technology           | 37       | 4%      |
| JMicron Technology           | 29       | 3.14%   |
| Kingston Technology Company  | 25       | 2.71%   |
| SanDisk                      | 24       | 2.6%    |
| Nvidia                       | 21       | 2.27%   |
| Phison Electronics           | 19       | 2.06%   |
| Marvell Technology Group     | 16       | 1.73%   |
| ADATA Technology             | 15       | 1.62%   |
| VIA Technologies             | 7        | 0.76%   |
| Toshiba America Info Systems | 7        | 0.76%   |
| SK hynix                     | 6        | 0.65%   |
| Micron/Crucial Technology    | 5        | 0.54%   |
| LSI Logic / Symbios Logic    | 5        | 0.54%   |
| Realtek Semiconductor        | 3        | 0.32%   |
| Broadcom / LSI               | 3        | 0.32%   |
| Seagate Technology           | 2        | 0.22%   |
| Promise Technology           | 1        | 0.11%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.11%   |
| Adaptec                      | 1        | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 127      | 11.01%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 50       | 4.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 47       | 4.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 46       | 3.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 41       | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 38       | 3.29%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 36       | 3.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 35       | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 33       | 2.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 32       | 2.77%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 31       | 2.69%   |
| AMD 500 Series Chipset SATA Controller                                                  | 28       | 2.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 25       | 2.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 22       | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 22       | 1.91%   |
| AMD 300 Series Chipset SATA Controller                                                  | 20       | 1.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 17       | 1.47%   |
| Kingston Company A2000 NVMe SSD                                                         | 16       | 1.39%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 14       | 1.21%   |
| Intel SATA Controller [RAID mode]                                                       | 14       | 1.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 14       | 1.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14       | 1.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 14       | 1.21%   |
| Nvidia MCP61 SATA Controller                                                            | 13       | 1.13%   |
| Intel SSD 660P Series                                                                   | 13       | 1.13%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 13       | 1.13%   |
| Phison E12 NVMe Controller                                                              | 12       | 1.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 12       | 1.04%   |
| Nvidia MCP61 IDE                                                                        | 9        | 0.78%   |
| JMicron JMB368 IDE controller                                                           | 8        | 0.69%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 8        | 0.69%   |
| AMD X370 Series Chipset SATA Controller                                                 | 8        | 0.69%   |
| Samsung NVMe SSD Controller 980                                                         | 7        | 0.61%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 6        | 0.52%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 6        | 0.52%   |
| JMicron JMB362 SATA Controller                                                          | 6        | 0.52%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6        | 0.52%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 6        | 0.52%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 6        | 0.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 529      | 58.26%  |
| NVMe | 202      | 22.25%  |
| IDE  | 141      | 15.53%  |
| RAID | 27       | 2.97%   |
| SAS  | 7        | 0.77%   |
| SCSI | 2        | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 366      | 59.32%  |
| AMD    | 251      | 40.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 17       | 2.74%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 15       | 2.42%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 11       | 1.77%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 11       | 1.77%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 10       | 1.61%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 9        | 1.45%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 9        | 1.45%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 9        | 1.45%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 8        | 1.29%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 8        | 1.29%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 8        | 1.29%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 8        | 1.29%   |
| AMD FX-8350 Eight-Core Processor            | 8        | 1.29%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 7        | 1.13%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 7        | 1.13%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 7        | 1.13%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 7        | 1.13%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 7        | 1.13%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 0.97%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 6        | 0.97%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 6        | 0.97%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 5        | 0.81%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 0.81%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 5        | 0.81%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 5        | 0.81%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5        | 0.81%   |
| AMD Phenom II X4 965 Processor              | 5        | 0.81%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 4        | 0.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 0.65%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 4        | 0.65%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 4        | 0.65%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 4        | 0.65%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.65%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 0.65%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 0.65%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 4        | 0.65%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 0.65%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 4        | 0.65%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 4        | 0.65%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 121      | 19.58%  |
| Intel Core i7           | 92       | 14.89%  |
| AMD Ryzen 5             | 62       | 10.03%  |
| AMD Ryzen 7             | 53       | 8.58%   |
| Intel Core i3           | 36       | 5.83%   |
| AMD Ryzen 9             | 29       | 4.69%   |
| Intel Xeon              | 27       | 4.37%   |
| AMD FX                  | 25       | 4.05%   |
| Intel Core 2 Duo        | 18       | 2.91%   |
| Intel Pentium           | 16       | 2.59%   |
| Intel Celeron           | 16       | 2.59%   |
| AMD Athlon II X2        | 13       | 2.1%    |
| Intel Core 2 Quad       | 11       | 1.78%   |
| AMD Phenom II X4        | 11       | 1.78%   |
| AMD Athlon 64 X2        | 10       | 1.62%   |
| Other                   | 8        | 1.29%   |
| Intel Pentium Dual-Core | 7        | 1.13%   |
| AMD Ryzen 3             | 7        | 1.13%   |
| AMD Phenom              | 5        | 0.81%   |
| Intel Core i9           | 4        | 0.65%   |
| Intel Core 2            | 4        | 0.65%   |
| AMD Phenom II X6        | 4        | 0.65%   |
| Intel Pentium 4         | 3        | 0.49%   |
| AMD Ryzen Threadripper  | 3        | 0.49%   |
| AMD Ryzen 7 PRO         | 3        | 0.49%   |
| AMD Athlon II X4        | 3        | 0.49%   |
| AMD Athlon              | 3        | 0.49%   |
| Intel Atom              | 2        | 0.32%   |
| AMD Sempron             | 2        | 0.32%   |
| AMD G                   | 2        | 0.32%   |
| AMD E1                  | 2        | 0.32%   |
| AMD Athlon Dual Core    | 2        | 0.32%   |
| AMD A6                  | 2        | 0.32%   |
| AMD A4                  | 2        | 0.32%   |
| AMD A10                 | 2        | 0.32%   |
| Intel Pentium Dual      | 1        | 0.16%   |
| Intel Genuine           | 1        | 0.16%   |
| AMD Turion II Neo       | 1        | 0.16%   |
| AMD PRO A10             | 1        | 0.16%   |
| AMD EPYC                | 1        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 254      | 41.1%   |
| 2      | 129      | 20.87%  |
| 6      | 91       | 14.72%  |
| 8      | 72       | 11.65%  |
| 12     | 21       | 3.4%    |
| 1      | 16       | 2.59%   |
| 16     | 14       | 2.27%   |
| 3      | 12       | 1.94%   |
| 14     | 3        | 0.49%   |
| 10     | 3        | 0.49%   |
| 32     | 1        | 0.16%   |
| 20     | 1        | 0.16%   |
| 18     | 1        | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 611      | 99.03%  |
| 2      | 5        | 0.81%   |
| 0      | 1        | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 348      | 56.31%  |
| 1      | 270      | 43.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 608      | 98.22%  |
| Unknown        | 9        | 1.45%   |
| 32-bit         | 2        | 0.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 180      | 28.08%  |
| 0x306c3    | 42       | 6.55%   |
| 0x306a9    | 36       | 5.62%   |
| 0x506e3    | 31       | 4.84%   |
| 0x206a7    | 26       | 4.06%   |
| 0x1067a    | 26       | 4.06%   |
| 0x08701021 | 23       | 3.59%   |
| 0x0800820d | 18       | 2.81%   |
| 0x0a201016 | 15       | 2.34%   |
| 0x906ea    | 14       | 2.18%   |
| 0x08701013 | 14       | 2.18%   |
| 0x06000852 | 14       | 2.18%   |
| 0x010000c8 | 14       | 2.18%   |
| 0x906e9    | 12       | 1.87%   |
| 0x906eb    | 8        | 1.25%   |
| 0x08001137 | 7        | 1.09%   |
| 0x20655    | 6        | 0.94%   |
| 0x20652    | 6        | 0.94%   |
| 0x106e5    | 6        | 0.94%   |
| 0x0a201009 | 6        | 0.94%   |
| 0x08001138 | 6        | 0.94%   |
| 0x906ec    | 5        | 0.78%   |
| 0x106a5    | 5        | 0.78%   |
| 0x6fd      | 4        | 0.62%   |
| 0x6fb      | 4        | 0.62%   |
| 0x40651    | 4        | 0.62%   |
| 0x0a601203 | 4        | 0.62%   |
| 0x010000db | 4        | 0.62%   |
| 0xf41      | 3        | 0.47%   |
| 0xa0653    | 3        | 0.47%   |
| 0x906ed    | 3        | 0.47%   |
| 0x6f6      | 3        | 0.47%   |
| 0x206d7    | 3        | 0.47%   |
| 0x10676    | 3        | 0.47%   |
| 0x0a50000d | 3        | 0.47%   |
| 0x0a20120a | 3        | 0.47%   |
| 0x08108109 | 3        | 0.47%   |
| 0x08101016 | 3        | 0.47%   |
| 0x0800820b | 3        | 0.47%   |
| 0x06001119 | 3        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 74       | 11.94%  |
| KabyLake         | 59       | 9.52%   |
| Zen 2            | 57       | 9.19%   |
| IvyBridge        | 47       | 7.58%   |
| Skylake          | 41       | 6.61%   |
| Zen 3            | 40       | 6.45%   |
| SandyBridge      | 38       | 6.13%   |
| K10              | 38       | 6.13%   |
| Zen              | 33       | 5.32%   |
| Penryn           | 31       | 5%      |
| Zen+             | 27       | 4.35%   |
| Piledriver       | 26       | 4.19%   |
| Core             | 16       | 2.58%   |
| Nehalem          | 15       | 2.42%   |
| K8 Hammer        | 15       | 2.42%   |
| Westmere         | 14       | 2.26%   |
| Unknown          | 9        | 1.45%   |
| CometLake        | 8        | 1.29%   |
| Silvermont       | 5        | 0.81%   |
| NetBurst         | 5        | 0.81%   |
| Bulldozer        | 4        | 0.65%   |
| Steamroller      | 3        | 0.48%   |
| Jaguar           | 3        | 0.48%   |
| Goldmont plus    | 2        | 0.32%   |
| Bonnell          | 2        | 0.32%   |
| Bobcat           | 2        | 0.32%   |
| Alderlake Hybrid | 2        | 0.32%   |
| TigerLake        | 1        | 0.16%   |
| Icelake          | 1        | 0.16%   |
| Goldmont         | 1        | 0.16%   |
| Broadwell        | 1        | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 299      | 44.69%  |
| AMD                                          | 194      | 29%     |
| Intel                                        | 160      | 23.92%  |
| ASPEED Technology                            | 10       | 1.49%   |
| Silicon Motion                               | 3        | 0.45%   |
| Matrox Electronics Systems                   | 2        | 0.3%    |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 35       | 5.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 32       | 4.62%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 21       | 3.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 18       | 2.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 17       | 2.46%   |
| Intel HD Graphics 530                                                       | 17       | 2.46%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 14       | 2.02%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 14       | 2.02%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 13       | 1.88%   |
| Nvidia GT218 [GeForce 210]                                                  | 11       | 1.59%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 11       | 1.59%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 11       | 1.59%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 10       | 1.45%   |
| Nvidia GK208B [GeForce GT 710]                                              | 10       | 1.45%   |
| ASPEED Technology ASPEED Graphics Family                                    | 10       | 1.45%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 10       | 1.45%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 9        | 1.3%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 9        | 1.3%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 9        | 1.3%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 8        | 1.16%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 8        | 1.16%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 1.01%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 7        | 1.01%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 1.01%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 6        | 0.87%   |
| AMD RS880 [Radeon HD 4200]                                                  | 6        | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.72%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 5        | 0.72%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 5        | 0.72%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 0.72%   |
| Intel Core Processor Integrated Graphics Controller                         | 5        | 0.72%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 5        | 0.72%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 5        | 0.72%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 5        | 0.72%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 0.58%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 0.58%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 4        | 0.58%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 4        | 0.58%   |
| Nvidia GF108 [GeForce GT 420]                                               | 4        | 0.58%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 4        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 276      | 43.81%  |
| 1 x AMD            | 171      | 27.14%  |
| 1 x Intel          | 133      | 21.11%  |
| 1 x ASPEED         | 10       | 1.59%   |
| 2 x AMD            | 9        | 1.43%   |
| AMD + Nvidia       | 9        | 1.43%   |
| Intel + Nvidia     | 7        | 1.11%   |
| 2 x Nvidia         | 5        | 0.79%   |
| 1 x Silicon Motion | 3        | 0.48%   |
| Intel + AMD        | 2        | 0.32%   |
| Other              | 1        | 0.16%   |
| 2 x Intel          | 1        | 0.16%   |
| 1 x XGI            | 1        | 0.16%   |
| Nvidia + Matrox    | 1        | 0.16%   |
| 1 x Matrox         | 1        | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 423      | 66.82%  |
| Proprietary | 177      | 27.96%  |
| Unknown     | 33       | 5.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 235      | 36.38%  |
| 1.01-2.0   | 91       | 14.09%  |
| 7.01-8.0   | 76       | 11.76%  |
| 0.01-0.5   | 66       | 10.22%  |
| 3.01-4.0   | 60       | 9.29%   |
| 0.51-1.0   | 58       | 8.98%   |
| 5.01-6.0   | 30       | 4.64%   |
| 8.01-16.0  | 16       | 2.48%   |
| 2.01-3.0   | 9        | 1.39%   |
| 16.01-24.0 | 5        | 0.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 133      | 19%     |
| BenQ                 | 65       | 9.29%   |
| Ancor Communications | 60       | 8.57%   |
| Acer                 | 59       | 8.43%   |
| Hewlett-Packard      | 58       | 8.29%   |
| Dell                 | 51       | 7.29%   |
| Goldstar             | 46       | 6.57%   |
| Lenovo               | 25       | 3.57%   |
| Fujitsu Siemens      | 22       | 3.14%   |
| ASUSTek Computer     | 22       | 3.14%   |
| AOC                  | 22       | 3.14%   |
| Philips              | 21       | 3%      |
| Sony                 | 17       | 2.43%   |
| Eizo                 | 13       | 1.86%   |
| ViewSonic            | 12       | 1.71%   |
| Unknown              | 6        | 0.86%   |
| LG Electronics       | 6        | 0.86%   |
| Panasonic            | 5        | 0.71%   |
| Vestel Elektronik    | 4        | 0.57%   |
| FUS                  | 4        | 0.57%   |
| Toshiba              | 3        | 0.43%   |
| Packard Bell         | 3        | 0.43%   |
| Onkyo                | 3        | 0.43%   |
| NEC Computers        | 3        | 0.43%   |
| Iiyama               | 3        | 0.43%   |
| Wacom                | 2        | 0.29%   |
| Tech Concepts        | 2        | 0.29%   |
| MSI                  | 2        | 0.29%   |
| Lenovo Group Limited | 2        | 0.29%   |
| Hitachi              | 2        | 0.29%   |
| DENON                | 2        | 0.29%   |
| AUS                  | 2        | 0.29%   |
| Unknown              | 2        | 0.29%   |
| Valve                | 1        | 0.14%   |
| UGD                  | 1        | 0.14%   |
| TVT                  | 1        | 0.14%   |
| SFX                  | 1        | 0.14%   |
| PKB                  | 1        | 0.14%   |
| Optoma               | 1        | 0.14%   |
| NXG                  | 1        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 6        | 0.81%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 6        | 0.81%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 5        | 0.67%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 5        | 0.67%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 4        | 0.54%   |
| Hewlett-Packard Z23i HWP3090 1920x1080 509x286mm 23.0-inch            | 4        | 0.54%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 4        | 0.54%   |
| BenQ XL2411Z BNQ7F31 1920x1080 530x300mm 24.0-inch                    | 4        | 0.54%   |
| BenQ G2400W BNQ780A 1920x1200 519x324mm 24.1-inch                     | 4        | 0.54%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 4        | 0.54%   |
| Samsung Electronics T24D390 SAM0B6C 1920x1080 521x293mm 23.5-inch     | 3        | 0.4%    |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 3        | 0.4%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 3        | 0.4%    |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch    | 3        | 0.4%    |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                     | 3        | 0.4%    |
| Samsung Electronics CF791 SAM0DC4 3440x1440 797x333mm 34.0-inch       | 3        | 0.4%    |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 3        | 0.4%    |
| LG Electronics LCD Monitor LG TV                                      | 3        | 0.4%    |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 3        | 0.4%    |
| Lenovo LCD Monitor LEN1144 1920x1080 520x320mm 24.0-inch              | 3        | 0.4%    |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 3        | 0.4%    |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 3        | 0.4%    |
| Goldstar L192WS GSM4B32 1440x900 410x260mm 19.1-inch                  | 3        | 0.4%    |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 3        | 0.4%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3        | 0.4%    |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 3        | 0.4%    |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch               | 3        | 0.4%    |
| BenQ XL2411Z BNQ7F32 1920x1080 531x298mm 24.0-inch                    | 3        | 0.4%    |
| BenQ GW2450H BNQ78C1 1920x1080 531x298mm 24.0-inch                    | 3        | 0.4%    |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 3        | 0.4%    |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 3        | 0.4%    |
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 3        | 0.4%    |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 3        | 0.4%    |
| Ancor Communications ASUS MG28U ACI28A7 3840x2160 621x341mm 27.9-inch | 3        | 0.4%    |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch | 3        | 0.4%    |
| Acer X34A ACR0450 3440x1440 800x340mm 34.2-inch                       | 3        | 0.4%    |
| Acer S191HQL ACR021C 1366x768 410x230mm 18.5-inch                     | 3        | 0.4%    |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 3        | 0.4%    |
| Acer G237HL ACR03DF 1920x1080 510x290mm 23.1-inch                     | 3        | 0.4%    |
| ViewSonic VA912-4SERIES VSC721C 1280x1024 376x301mm 19.0-inch         | 2        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 269      | 39.04%  |
| 3840x2160 (4K)     | 68       | 9.87%   |
| 2560x1440 (QHD)    | 68       | 9.87%   |
| 1680x1050 (WSXGA+) | 53       | 7.69%   |
| 1920x1200 (WUXGA)  | 45       | 6.53%   |
| 1280x1024 (SXGA)   | 41       | 5.95%   |
| Unknown            | 31       | 4.5%    |
| 3440x1440          | 18       | 2.61%   |
| 1440x900 (WXGA+)   | 15       | 2.18%   |
| 1360x768           | 14       | 2.03%   |
| 3840x1080          | 12       | 1.74%   |
| 1366x768 (WXGA)    | 7        | 1.02%   |
| 1600x900 (HD+)     | 5        | 0.73%   |
| 1280x720 (HD)      | 5        | 0.73%   |
| 4480x1440          | 4        | 0.58%   |
| 1920x540           | 4        | 0.58%   |
| 2560x1080          | 3        | 0.44%   |
| 1600x1200          | 3        | 0.44%   |
| 5760x2160          | 2        | 0.29%   |
| 5120x1440          | 2        | 0.29%   |
| 3840x1200          | 2        | 0.29%   |
| 3360x1050          | 2        | 0.29%   |
| 7680x2160          | 1        | 0.15%   |
| 5760x1440          | 1        | 0.15%   |
| 5280x1080          | 1        | 0.15%   |
| 4480x1600          | 1        | 0.15%   |
| 3840x1600          | 1        | 0.15%   |
| 3520x1200          | 1        | 0.15%   |
| 3360x1080          | 1        | 0.15%   |
| 2560x2880          | 1        | 0.15%   |
| 2560x1600          | 1        | 0.15%   |
| 2288x1287          | 1        | 0.15%   |
| 2160x1200          | 1        | 0.15%   |
| 1834x1031          | 1        | 0.15%   |
| 1826x1027          | 1        | 0.15%   |
| 1400x1050          | 1        | 0.15%   |
| 1360x765           | 1        | 0.15%   |
| 1024x768 (XGA)     | 1        | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 126      | 18.56%  |
| 27      | 98       | 14.43%  |
| 23      | 92       | 13.55%  |
| Unknown | 89       | 13.11%  |
| 22      | 44       | 6.48%   |
| 19      | 38       | 5.6%    |
| 31      | 26       | 3.83%   |
| 21      | 26       | 3.83%   |
| 84      | 16       | 2.36%   |
| 34      | 16       | 2.36%   |
| 18      | 14       | 2.06%   |
| 20      | 12       | 1.77%   |
| 32      | 11       | 1.62%   |
| 25      | 11       | 1.62%   |
| 17      | 10       | 1.47%   |
| 72      | 8        | 1.18%   |
| 40      | 4        | 0.59%   |
| 28      | 4        | 0.59%   |
| 65      | 3        | 0.44%   |
| 55      | 3        | 0.44%   |
| 26      | 3        | 0.44%   |
| 75      | 2        | 0.29%   |
| 54      | 2        | 0.29%   |
| 48      | 2        | 0.29%   |
| 46      | 2        | 0.29%   |
| 39      | 2        | 0.29%   |
| 36      | 2        | 0.29%   |
| 33      | 2        | 0.29%   |
| 15      | 2        | 0.29%   |
| 13      | 2        | 0.29%   |
| 142     | 1        | 0.15%   |
| 49      | 1        | 0.15%   |
| 47      | 1        | 0.15%   |
| 37      | 1        | 0.15%   |
| 35      | 1        | 0.15%   |
| 29      | 1        | 0.15%   |
| 14      | 1        | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 281      | 43.97%  |
| 401-500        | 101      | 15.81%  |
| Unknown        | 89       | 13.93%  |
| 601-700        | 42       | 6.57%   |
| 351-400        | 32       | 5.01%   |
| 701-800        | 31       | 4.85%   |
| 1501-2000      | 26       | 4.07%   |
| 1001-1500      | 13       | 2.03%   |
| 301-350        | 12       | 1.88%   |
| 801-900        | 8        | 1.25%   |
| 201-300        | 3        | 0.47%   |
| More than 2000 | 1        | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 351      | 56.43%  |
| 16/10   | 120      | 19.29%  |
| Unknown | 75       | 12.06%  |
| 5/4     | 40       | 6.43%   |
| 21/9    | 20       | 3.22%   |
| 32/9    | 5        | 0.8%    |
| 4/3     | 4        | 0.64%   |
| 3/2     | 3        | 0.48%   |
| 6/5     | 2        | 0.32%   |
| 1.00    | 1        | 0.16%   |
| 0.89    | 1        | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 216      | 32.73%  |
| 301-350        | 99       | 15%     |
| Unknown        | 89       | 13.48%  |
| 251-300        | 63       | 9.55%   |
| 151-200        | 63       | 9.55%   |
| 351-500        | 60       | 9.09%   |
| More than 1000 | 34       | 5.15%   |
| 141-150        | 16       | 2.42%   |
| 501-1000       | 15       | 2.27%   |
| 101-110        | 3        | 0.45%   |
| 71-80          | 2        | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 384      | 61.34%  |
| Unknown | 89       | 14.22%  |
| 101-120 | 86       | 13.74%  |
| 121-160 | 32       | 5.11%   |
| 1-50    | 24       | 3.83%   |
| 161-240 | 11       | 1.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 461      | 72.94%  |
| 2     | 114      | 18.04%  |
| 0     | 38       | 6.01%   |
| 3     | 16       | 2.53%   |
| 4     | 3        | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 329      | 37.18%  |
| Intel                                  | 294      | 33.22%  |
| Qualcomm Atheros                       | 34       | 3.84%   |
| Broadcom                               | 26       | 2.94%   |
| Ralink                                 | 18       | 2.03%   |
| Nvidia                                 | 17       | 1.92%   |
| TP-Link                                | 14       | 1.58%   |
| Huawei Technologies                    | 14       | 1.58%   |
| Ralink Technology                      | 13       | 1.47%   |
| ASUSTek Computer                       | 13       | 1.47%   |
| Samsung Electronics                    | 10       | 1.13%   |
| Marvell Technology Group               | 9        | 1.02%   |
| Xiaomi                                 | 8        | 0.9%    |
| Broadcom Limited                       | 7        | 0.79%   |
| Microsoft                              | 6        | 0.68%   |
| MediaTek                               | 6        | 0.68%   |
| ZyXEL Communications                   | 5        | 0.56%   |
| D-Link System                          | 5        | 0.56%   |
| Motorola PCS                           | 4        | 0.45%   |
| NetGear                                | 3        | 0.34%   |
| Microchip Technology                   | 3        | 0.34%   |
| HMD Global                             | 3        | 0.34%   |
| Gemtek                                 | 3        | 0.34%   |
| D-Link                                 | 3        | 0.34%   |
| BUFFALO                                | 3        | 0.34%   |
| ASIX Electronics                       | 3        | 0.34%   |
| Aquantia                               | 3        | 0.34%   |
| 3Com                                   | 3        | 0.34%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.23%   |
| Qualcomm                               | 2        | 0.23%   |
| Linksys                                | 2        | 0.23%   |
| Edimax Technology                      | 2        | 0.23%   |
| ZyDAS                                  | 1        | 0.11%   |
| VIA Technologies                       | 1        | 0.11%   |
| U-Blox                                 | 1        | 0.11%   |
| Seeed Technology                       | 1        | 0.11%   |
| OPPO Electronics                       | 1        | 0.11%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.11%   |
| Loupedeck                              | 1        | 0.11%   |
| LG Electronics                         | 1        | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 264      | 26.48%  |
| Intel I211 Gigabit Network Connection                             | 49       | 4.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32       | 3.21%   |
| Intel Ethernet Connection (2) I219-V                              | 30       | 3.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 27       | 2.71%   |
| Intel Wi-Fi 6 AX200                                               | 24       | 2.41%   |
| Intel Ethernet Controller I225-V                                  | 16       | 1.6%    |
| Intel Ethernet Connection I217-LM                                 | 15       | 1.5%    |
| Intel Ethernet Connection (7) I219-V                              | 14       | 1.4%    |
| Intel 82579V Gigabit Network Connection                           | 14       | 1.4%    |
| Intel I210 Gigabit Network Connection                             | 13       | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 13       | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 13       | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 12       | 1.2%    |
| Nvidia MCP61 Ethernet                                             | 12       | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12       | 1.2%    |
| Intel Ethernet Connection (2) I218-V                              | 10       | 1%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 10       | 1%      |
| Intel 82574L Gigabit Network Connection                           | 8        | 0.8%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7        | 0.7%    |
| Huawei WLZ-AN00                                                   | 7        | 0.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 7        | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6        | 0.6%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 6        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 0.6%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 6        | 0.6%    |
| Intel Wireless 7260                                               | 6        | 0.6%    |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]         | 6        | 0.6%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 5        | 0.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 0.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 5        | 0.5%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 5        | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5        | 0.5%    |
| Intel Wireless-AC 9260                                            | 5        | 0.5%    |
| Intel I350 Gigabit Network Connection                             | 5        | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5        | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4        | 0.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 4        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 75       | 29.07%  |
| Realtek Semiconductor | 62       | 24.03%  |
| Ralink                | 18       | 6.98%   |
| Broadcom              | 14       | 5.43%   |
| TP-Link               | 13       | 5.04%   |
| Ralink Technology     | 13       | 5.04%   |
| ASUSTek Computer      | 13       | 5.04%   |
| Qualcomm Atheros      | 12       | 4.65%   |
| Microsoft             | 6        | 2.33%   |
| MediaTek              | 6        | 2.33%   |
| ZyXEL Communications  | 5        | 1.94%   |
| D-Link System         | 4        | 1.55%   |
| NetGear               | 3        | 1.16%   |
| Gemtek                | 3        | 1.16%   |
| BUFFALO               | 3        | 1.16%   |
| Edimax Technology     | 2        | 0.78%   |
| D-Link                | 2        | 0.78%   |
| ZyDAS                 | 1        | 0.39%   |
| Linksys               | 1        | 0.39%   |
| LG Electronics        | 1        | 0.39%   |
| Broadcom Limited      | 1        | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 24       | 9.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 12       | 4.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12       | 4.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7        | 2.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 7        | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6        | 2.31%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 6        | 2.31%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 6        | 2.31%   |
| Intel Wireless 7260                                            | 6        | 2.31%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]      | 6        | 2.31%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 5        | 1.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 5        | 1.92%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 5        | 1.92%   |
| Intel Wireless-AC 9260                                         | 5        | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5        | 1.92%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 4        | 1.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4        | 1.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4        | 1.54%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 4        | 1.54%   |
| Microsoft Xbox 360 Wireless Adapter                            | 4        | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4        | 1.54%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 4        | 1.54%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 3        | 1.15%   |
| Realtek 802.11ac NIC                                           | 3        | 1.15%   |
| Ralink RT5370 Wireless Adapter                                 | 3        | 1.15%   |
| Ralink MT7601U Wireless Adapter                                | 3        | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3        | 1.15%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3        | 1.15%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 3        | 1.15%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3        | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3        | 1.15%   |
| Gemtek WUBR-177G [Ralink RT2571W]                              | 3        | 1.15%   |
| ZyXEL ZyXEL Dual-Band Wireless AC USB Adapter                  | 2        | 0.77%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2        | 0.77%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 2        | 0.77%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2        | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2        | 0.77%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 2        | 0.77%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2        | 0.77%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 2        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 306      | 44.35%  |
| Intel                                  | 260      | 37.68%  |
| Qualcomm Atheros                       | 22       | 3.19%   |
| Nvidia                                 | 17       | 2.46%   |
| Broadcom                               | 12       | 1.74%   |
| Huawei Technologies                    | 11       | 1.59%   |
| Marvell Technology Group               | 9        | 1.3%    |
| Xiaomi                                 | 8        | 1.16%   |
| Samsung Electronics                    | 7        | 1.01%   |
| Broadcom Limited                       | 6        | 0.87%   |
| Motorola PCS                           | 3        | 0.43%   |
| HMD Global                             | 3        | 0.43%   |
| ASIX Electronics                       | 3        | 0.43%   |
| Aquantia                               | 3        | 0.43%   |
| 3Com                                   | 3        | 0.43%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.29%   |
| Qualcomm                               | 2        | 0.29%   |
| VIA Technologies                       | 1        | 0.14%   |
| TP-Link                                | 1        | 0.14%   |
| OPPO Electronics                       | 1        | 0.14%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.14%   |
| Linksys                                | 1        | 0.14%   |
| Lenovo                                 | 1        | 0.14%   |
| Google                                 | 1        | 0.14%   |
| DisplayLink                            | 1        | 0.14%   |
| D-Link System                          | 1        | 0.14%   |
| D-Link                                 | 1        | 0.14%   |
| American Megatrends                    | 1        | 0.14%   |
| AMD                                    | 1        | 0.14%   |
| ADMtek                                 | 1        | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 264      | 36.67%  |
| Intel I211 Gigabit Network Connection                             | 49       | 6.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32       | 4.44%   |
| Intel Ethernet Connection (2) I219-V                              | 30       | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 27       | 3.75%   |
| Intel Ethernet Controller I225-V                                  | 16       | 2.22%   |
| Intel Ethernet Connection I217-LM                                 | 15       | 2.08%   |
| Intel Ethernet Connection (7) I219-V                              | 14       | 1.94%   |
| Intel 82579V Gigabit Network Connection                           | 14       | 1.94%   |
| Intel I210 Gigabit Network Connection                             | 13       | 1.81%   |
| Intel Ethernet Connection I217-V                                  | 13       | 1.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 13       | 1.81%   |
| Nvidia MCP61 Ethernet                                             | 12       | 1.67%   |
| Intel Ethernet Connection (2) I218-V                              | 10       | 1.39%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 10       | 1.39%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 1.11%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 0.97%   |
| Huawei WLZ-AN00                                                   | 7        | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 0.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 0.69%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5        | 0.69%   |
| Intel I350 Gigabit Network Connection                             | 5        | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4        | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4        | 0.56%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 4        | 0.56%   |
| Intel 82578DM Gigabit Network Connection                          | 4        | 0.56%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 4        | 0.56%   |
| Huawei E353/E3131                                                 | 4        | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.42%   |
| Motorola PCS XT1032                                               | 3        | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.42%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 3        | 0.42%   |
| Intel 82578DC Gigabit Network Connection                          | 3        | 0.42%   |
| HMD Global Nokia7.2                                               | 3        | 0.42%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 3        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 613      | 70.22%  |
| WiFi     | 244      | 27.95%  |
| Modem    | 14       | 1.6%    |
| Unknown  | 2        | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 498      | 80.84%  |
| WiFi     | 115      | 18.67%  |
| Modem    | 2        | 0.32%   |
| Unknown  | 1        | 0.16%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 400      | 64.31%  |
| 2     | 181      | 29.1%   |
| 3     | 26       | 4.18%   |
| 0     | 7        | 1.13%   |
| 5     | 5        | 0.8%    |
| 4     | 3        | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 513      | 81.43%  |
| Yes  | 117      | 18.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 75       | 39.47%  |
| Cambridge Silicon Radio         | 46       | 24.21%  |
| ASUSTek Computer                | 33       | 17.37%  |
| Realtek Semiconductor           | 11       | 5.79%   |
| MediaTek                        | 4        | 2.11%   |
| IMC Networks                    | 4        | 2.11%   |
| HTC (High Tech Computer)        | 4        | 2.11%   |
| Apple                           | 4        | 2.11%   |
| Qualcomm Atheros Communications | 3        | 1.58%   |
| Edimax Technology               | 2        | 1.05%   |
| Broadcom                        | 2        | 1.05%   |
| Lite-On Technology              | 1        | 0.53%   |
| Belkin Components               | 1        | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 46       | 23.96%  |
| Intel AX200 Bluetooth                                                | 28       | 14.58%  |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 19       | 9.9%    |
| Intel Bluetooth wireless interface                                   | 15       | 7.81%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 10       | 5.21%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 9        | 4.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 6        | 3.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 5        | 2.6%    |
| ASUS ASUS USB-BT500                                                  | 5        | 2.6%    |
| MediaTek Wireless_Device                                             | 4        | 2.08%   |
| IMC Networks Bluetooth Radio                                         | 4        | 2.08%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 1.56%   |
| Intel AX210 Bluetooth                                                | 3        | 1.56%   |
| Intel AX201 Bluetooth                                                | 3        | 1.56%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 3        | 1.56%   |
| ASUS Bluetooth Radio                                                 | 3        | 1.56%   |
| Apple Bluetooth USB Host Controller                                  | 3        | 1.56%   |
| Realtek Bluetooth Radio                                              | 2        | 1.04%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 2        | 1.04%   |
| Intel Bluetooth Device                                               | 2        | 1.04%   |
| Edimax Bluetooth Adapter                                             | 2        | 1.04%   |
| ASUS Bluetooth Adapter                                               | 2        | 1.04%   |
| ASUS BCM20702A0                                                      | 2        | 1.04%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)                      | 1        | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 1        | 0.52%   |
| Broadcom Bluetooth 3.0+HS USB Adapter                                | 1        | 0.52%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 1        | 0.52%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 0.52%   |
| ASUS Bluetooth Device                                                | 1        | 0.52%   |
| Apple Bluetooth HCI                                                  | 1        | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 331      | 30.48%  |
| Nvidia                               | 294      | 27.07%  |
| AMD                                  | 275      | 25.32%  |
| C-Media Electronics                  | 24       | 2.21%   |
| Logitech                             | 17       | 1.57%   |
| Creative Labs                        | 16       | 1.47%   |
| Kingston Technology                  | 10       | 0.92%   |
| ASUSTek Computer                     | 9        | 0.83%   |
| Texas Instruments                    | 8        | 0.74%   |
| SteelSeries ApS                      | 8        | 0.74%   |
| Creative Technology                  | 8        | 0.74%   |
| Razer USA                            | 7        | 0.64%   |
| VIA Technologies                     | 5        | 0.46%   |
| RODE Microphones                     | 4        | 0.37%   |
| M-Audio                              | 4        | 0.37%   |
| DSEA A/S                             | 4        | 0.37%   |
| Blue Microphones                     | 4        | 0.37%   |
| Thesycon Systemsoftware & Consulting | 3        | 0.28%   |
| GN Netcom                            | 3        | 0.28%   |
| Generalplus Technology               | 3        | 0.28%   |
| Focusrite-Novation                   | 3        | 0.28%   |
| Corsair                              | 3        | 0.28%   |
| SAVITECH                             | 2        | 0.18%   |
| Plantronics                          | 2        | 0.18%   |
| Lenovo                               | 2        | 0.18%   |
| JBL                                  | 2        | 0.18%   |
| GYROCOM C&C                          | 2        | 0.18%   |
| FiiO Electronics Technology          | 2        | 0.18%   |
| Cambridge Audio                      | 2        | 0.18%   |
| BEHRINGER International              | 2        | 0.18%   |
| AudioQuest                           | 2        | 0.18%   |
| XMOS                                 | 1        | 0.09%   |
| Valve Software                       | 1        | 0.09%   |
| USB MICROPHONE                       | 1        | 0.09%   |
| Trust                                | 1        | 0.09%   |
| Thomann                              | 1        | 0.09%   |
| Tenx Technology                      | 1        | 0.09%   |
| Syntek                               | 1        | 0.09%   |
| Superlux digit                       | 1        | 0.09%   |
| SM900 Microphone                     | 1        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 79       | 6.27%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 58       | 4.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 48       | 3.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 42       | 3.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 41       | 3.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 35       | 2.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 35       | 2.78%   |
| Nvidia GP104 High Definition Audio Controller                              | 33       | 2.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 31       | 2.46%   |
| Intel 200 Series PCH HD Audio                                              | 31       | 2.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 31       | 2.46%   |
| AMD Family 17h/19h HD Audio Controller                                     | 24       | 1.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 23       | 1.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 21       | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 20       | 1.59%   |
| Nvidia High Definition Audio Controller                                    | 17       | 1.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 17       | 1.35%   |
| Nvidia TU116 High Definition Audio Controller                              | 16       | 1.27%   |
| Nvidia GP106 High Definition Audio Controller                              | 16       | 1.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 16       | 1.27%   |
| AMD Navi 10 HDMI Audio                                                     | 16       | 1.27%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14       | 1.11%   |
| Nvidia MCP61 High Definition Audio                                         | 13       | 1.03%   |
| Nvidia GM206 High Definition Audio Controller                              | 13       | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 13       | 1.03%   |
| Nvidia GK107 HDMI Audio Controller                                         | 13       | 1.03%   |
| Nvidia GK104 HDMI Audio Controller                                         | 13       | 1.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 13       | 1.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 12       | 0.95%   |
| Nvidia TU104 HD Audio Controller                                           | 11       | 0.87%   |
| Nvidia GM204 High Definition Audio Controller                              | 11       | 0.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 11       | 0.87%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 11       | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 10       | 0.79%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 10       | 0.79%   |
| AMD FCH Azalia Controller                                                  | 10       | 0.79%   |
| Nvidia GP102 HDMI Audio Controller                                         | 9        | 0.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9        | 0.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 0.71%   |
| Nvidia GK106 HDMI Audio Controller                                         | 8        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 134      | 32.52%  |
| Samsung Electronics | 49       | 11.89%  |
| Unknown             | 40       | 9.71%   |
| G.Skill             | 39       | 9.47%   |
| Corsair             | 38       | 9.22%   |
| SK hynix            | 33       | 8.01%   |
| Crucial             | 26       | 6.31%   |
| Micron Technology   | 22       | 5.34%   |
| Ramaxel Technology  | 6        | 1.46%   |
| Elpida              | 4        | 0.97%   |
| Nanya Technology    | 3        | 0.73%   |
| Unknown (ABCD)      | 2        | 0.49%   |
| Team                | 2        | 0.49%   |
| ASint Technology    | 2        | 0.49%   |
| Apacer              | 2        | 0.49%   |
| A-DATA Technology   | 2        | 0.49%   |
| Unknown (AB)        | 1        | 0.24%   |
| Unigen              | 1        | 0.24%   |
| Qimonda             | 1        | 0.24%   |
| Patriot             | 1        | 0.24%   |
| Hitachi             | 1        | 0.24%   |
| GOODRAM             | 1        | 0.24%   |
| GIGA-BYTE           | 1        | 0.24%   |
| Unknown             | 1        | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 14       | 3.13%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                 | 10       | 2.24%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s               | 8        | 1.79%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s               | 7        | 1.57%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s               | 5        | 1.12%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s             | 5        | 1.12%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 4        | 0.89%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s               | 4        | 0.89%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s               | 4        | 0.89%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 4        | 0.89%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s            | 4        | 0.89%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s               | 4        | 0.89%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s              | 4        | 0.89%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3                        | 4        | 0.89%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s             | 4        | 0.89%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s               | 4        | 0.89%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s             | 4        | 0.89%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                              | 3        | 0.67%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                       | 3        | 0.67%   |
| Samsung RAM M391A4G43AB1-CWE 32GB DIMM DDR4 3200MT/s              | 3        | 0.67%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s               | 3        | 0.67%   |
| Ramaxel RAM RMR1870EC58E9F1333 4GB DIMM DDR3 1333MT/s             | 3        | 0.67%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 3200MT/s               | 3        | 0.67%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s               | 3        | 0.67%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s             | 3        | 0.67%   |
| Kingston RAM 99U5471-002.A01LF 2GB DIMM DDR3 1334MT/s             | 3        | 0.67%   |
| G.Skill RAM F4-3200C16-16GTZ 16GB DIMM DDR4 3200MT/s              | 3        | 0.67%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s                | 3        | 0.67%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s              | 3        | 0.67%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                              | 2        | 0.45%   |
| Unknown RAM Module 2GB DIMM 800MT/s                               | 2        | 0.45%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                              | 2        | 0.45%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                          | 2        | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2        | 0.45%   |
| SK hynix RAM Module 8GB DIMM DDR3 1333MT/s                        | 2        | 0.45%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s               | 2        | 0.45%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s              | 2        | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 2        | 0.45%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s               | 2        | 0.45%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s                | 2        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 180      | 48.13%  |
| DDR3    | 128      | 34.22%  |
| DDR2    | 26       | 6.95%   |
| Unknown | 16       | 4.28%   |
| SDRAM   | 12       | 3.21%   |
| DDR     | 5        | 1.34%   |
| DDR5    | 4        | 1.07%   |
| LPDDR4  | 3        | 0.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 347      | 94.55%  |
| SODIMM       | 16       | 4.36%   |
| RIMM         | 2        | 0.54%   |
| Row Of Chips | 1        | 0.27%   |
| FB-DIMM      | 1        | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 151      | 37.94%  |
| 4096  | 88       | 22.11%  |
| 16384 | 58       | 14.57%  |
| 2048  | 55       | 13.82%  |
| 32768 | 21       | 5.28%   |
| 1024  | 20       | 5.03%   |
| 512   | 5        | 1.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 54       | 13.17%  |
| 1333    | 45       | 10.98%  |
| 3600    | 41       | 10%     |
| 3200    | 29       | 7.07%   |
| 2133    | 25       | 6.1%    |
| 2400    | 23       | 5.61%   |
| 800     | 20       | 4.88%   |
| 2667    | 15       | 3.66%   |
| 1867    | 15       | 3.66%   |
| 667     | 14       | 3.41%   |
| 3466    | 13       | 3.17%   |
| 3000    | 8        | 1.95%   |
| 1066    | 8        | 1.95%   |
| 3800    | 7        | 1.71%   |
| 3733    | 6        | 1.46%   |
| 3533    | 6        | 1.46%   |
| 2933    | 6        | 1.46%   |
| 1866    | 6        | 1.46%   |
| 3266    | 5        | 1.22%   |
| 1800    | 5        | 1.22%   |
| 3866    | 4        | 0.98%   |
| 3400    | 4        | 0.98%   |
| 2800    | 4        | 0.98%   |
| 2200    | 4        | 0.98%   |
| 1334    | 4        | 0.98%   |
| 2666    | 3        | 0.73%   |
| 1067    | 3        | 0.73%   |
| 533     | 3        | 0.73%   |
| 49926   | 2        | 0.49%   |
| 4800    | 2        | 0.49%   |
| 3333    | 2        | 0.49%   |
| 3151    | 2        | 0.49%   |
| 3100    | 2        | 0.49%   |
| Unknown | 2        | 0.49%   |
| 8192    | 1        | 0.24%   |
| 5600    | 1        | 0.24%   |
| 5200    | 1        | 0.24%   |
| 4133    | 1        | 0.24%   |
| 4000    | 1        | 0.24%   |
| 3933    | 1        | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 10       | 45.45%  |
| Seiko Epson         | 3        | 13.64%  |
| Samsung Electronics | 3        | 13.64%  |
| Canon               | 2        | 9.09%   |
| Brother Industries  | 2        | 9.09%   |
| Xerox               | 1        | 4.55%   |
| Prolific Technology | 1        | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung ML-1660 Series              | 2        | 9.09%   |
| Xerox Phaser 6500DN                 | 1        | 4.55%   |
| Seiko Epson WF-3520 Series          | 1        | 4.55%   |
| Seiko Epson Printer                 | 1        | 4.55%   |
| Seiko Epson L555 Series             | 1        | 4.55%   |
| Samsung CLP-325 Color Laser Printer | 1        | 4.55%   |
| Prolific PL2305 Parallel Port       | 1        | 4.55%   |
| HP PSC 1100 series                  | 1        | 4.55%   |
| HP OfficeJet 5200 series            | 1        | 4.55%   |
| HP LaserJet Professional P 1102w    | 1        | 4.55%   |
| HP LaserJet Pro M148-M149           | 1        | 4.55%   |
| HP LaserJet P2055 series            | 1        | 4.55%   |
| HP LaserJet P2015 series            | 1        | 4.55%   |
| HP LaserJet 1200                    | 1        | 4.55%   |
| HP DeskJet F300 series              | 1        | 4.55%   |
| HP DeskJet 960c                     | 1        | 4.55%   |
| HP DeskJet 6940 series              | 1        | 4.55%   |
| Canon TS3300 series                 | 1        | 4.55%   |
| Canon TS3100 series                 | 1        | 4.55%   |
| Brother MFC-7460DN                  | 1        | 4.55%   |
| Brother DCP-L2530DW series          | 1        | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 4        | 80%     |
| Seiko Epson | 1        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Canon CanoScan N650U/N656U            | 2        | 40%     |
| Seiko Epson GT-X770 [Perfection V500] | 1        | 20%     |
| Canon CanoScan LiDE 200               | 1        | 20%     |
| Canon CanoScan LiDE 110               | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 38       | 47.5%   |
| Microsoft                     | 9        | 11.25%  |
| Microdia                      | 9        | 11.25%  |
| Samsung Electronics           | 3        | 3.75%   |
| Trust                         | 2        | 2.5%    |
| Sunplus Innovation Technology | 2        | 2.5%    |
| Realtek Semiconductor         | 2        | 2.5%    |
| Creative Technology           | 2        | 2.5%    |
| Chicony Electronics           | 2        | 2.5%    |
| Apple                         | 2        | 2.5%    |
| Valve Software                | 1        | 1.25%   |
| Tobii Technology AB           | 1        | 1.25%   |
| Silicon Motion                | 1        | 1.25%   |
| Razer USA                     | 1        | 1.25%   |
| OnePlus                       | 1        | 1.25%   |
| MacroSilicon                  | 1        | 1.25%   |
| Lenovo                        | 1        | 1.25%   |
| Google                        | 1        | 1.25%   |
| Generalplus Technology        | 1        | 1.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech Webcam C270                        | 8        | 10%     |
| Logitech HD Pro Webcam C920                 | 8        | 10%     |
| Microsoft LifeCam HD-3000                   | 7        | 8.75%   |
| Logitech StreamCam                          | 5        | 6.25%   |
| Microdia Camera                             | 4        | 5%      |
| Samsung Galaxy series, misc. (MTP mode)     | 3        | 3.75%   |
| Logitech HD Webcam C510                     | 3        | 3.75%   |
| Sunplus papalook AF 925                     | 2        | 2.5%    |
| Realtek FULL HD 1080P Webcam                | 2        | 2.5%    |
| Logitech Webcam C930e                       | 2        | 2.5%    |
| Logitech Webcam B500                        | 2        | 2.5%    |
| Logitech HD Webcam C525                     | 2        | 2.5%    |
| Logitech C922 Pro Stream Webcam             | 2        | 2.5%    |
| Valve Software 3D Camera                    | 1        | 1.25%   |
| Trust USB Camera                            | 1        | 1.25%   |
| Trust Full HD Webcam                        | 1        | 1.25%   |
| Tobii AB EyeChip                            | 1        | 1.25%   |
| Silicon Motion Endoscope camera             | 1        | 1.25%   |
| Razer USA Razer Kiyo Pro                    | 1        | 1.25%   |
| OnePlus GM1913                              | 1        | 1.25%   |
| Microsoft LifeCam Studio                    | 1        | 1.25%   |
| Microsoft LifeCam HD-5000                   | 1        | 1.25%   |
| Microdia USB 2.0 Camera                     | 1        | 1.25%   |
| Microdia Sonix USB 2.0 Camera               | 1        | 1.25%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 1.25%   |
| Microdia AUKEY-W1                           | 1        | 1.25%   |
| Microdia ACR010 USB Webcam                  | 1        | 1.25%   |
| MacroSilicon USB Video                      | 1        | 1.25%   |
| Logitech Webcam C925e                       | 1        | 1.25%   |
| Logitech Webcam C210                        | 1        | 1.25%   |
| Logitech Webcam C110                        | 1        | 1.25%   |
| Logitech QuickCam Communicate MP/S5500      | 1        | 1.25%   |
| Logitech HD Webcam C615                     | 1        | 1.25%   |
| Logitech BRIO Ultra HD Webcam               | 1        | 1.25%   |
| Lenovo FHD Webcam                           | 1        | 1.25%   |
| Google Nexus/Pixel Device (MTP + debug)     | 1        | 1.25%   |
| Generalplus GENERAL WEBCAM                  | 1        | 1.25%   |
| Creative VF0610 Live! Cam Socialize HD      | 1        | 1.25%   |
| Creative VF0530 Live! Cam Chat IM           | 1        | 1.25%   |
| Chicony ViewSonic 1.3M, USB2.0 Webcam       | 1        | 1.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Microsoft Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| SCM Microsystems          | 4        | 33.33%  |
| Fujitsu Siemens Computers | 3        | 25%     |
| OmniKey                   | 2        | 16.67%  |
| Advanced Card Systems     | 2        | 16.67%  |
| Alcor Micro               | 1        | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Fujitsu Siemens Computers SmartCard Reader 2A              | 3        | 25%     |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader | 2        | 16.67%  |
| OmniKey CardMan 1021                                       | 2        | 16.67%  |
| Advanced Card Systems ACR38 SmartCard Reader               | 2        | 16.67%  |
| SCM Microsystems SCR333 SmartCard Reader                   | 1        | 8.33%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1        | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                        | 1        | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 516      | 82.56%  |
| 1     | 90       | 14.4%   |
| 2     | 15       | 2.4%    |
| 4     | 2        | 0.32%   |
| 3     | 2        | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 43       | 34.68%  |
| Net/wireless             | 26       | 20.97%  |
| Communication controller | 13       | 10.48%  |
| Unassigned class         | 9        | 7.26%   |
| Chipcard                 | 6        | 4.84%   |
| Sound                    | 5        | 4.03%   |
| Multimedia controller    | 5        | 4.03%   |
| Storage/raid             | 3        | 2.42%   |
| Card reader              | 3        | 2.42%   |
| Camera                   | 3        | 2.42%   |
| Storage/nvme             | 2        | 1.61%   |
| Net/ethernet             | 2        | 1.61%   |
| Bluetooth                | 2        | 1.61%   |
| Network                  | 1        | 0.81%   |
| Firewire controller      | 1        | 0.81%   |

