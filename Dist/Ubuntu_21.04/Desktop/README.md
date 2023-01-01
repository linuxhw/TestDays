Ubuntu 21.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.04.

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

Total: 928

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | GA-MA785GT-UD3H             | [5ab13c42b3](https://linux-hardware.org/?probe=5ab13c42b3) | Dec 03, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | [b3ab0684c5](https://linux-hardware.org/?probe=b3ab0684c5) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ac0380e724](https://linux-hardware.org/?probe=ac0380e724) | Oct 20, 2022 |
| HP            | 18E9                        | [2dff78f303](https://linux-hardware.org/?probe=2dff78f303) | Aug 31, 2022 |
| Dell          | 0F642F A00                  | [832cf31a6f](https://linux-hardware.org/?probe=832cf31a6f) | Aug 25, 2022 |
| ASRock        | Z77 Pro3                    | [289b6912d0](https://linux-hardware.org/?probe=289b6912d0) | Jul 10, 2022 |
| Medion        | MS-7501                     | [e5bf3cfdc2](https://linux-hardware.org/?probe=e5bf3cfdc2) | Jun 07, 2022 |
| MW            | GMLK-2_5G4L                 | [69e61d13d7](https://linux-hardware.org/?probe=69e61d13d7) | May 30, 2022 |
| ASUSTek       | PRIME B550M-A               | [97fc69a492](https://linux-hardware.org/?probe=97fc69a492) | May 22, 2022 |
| ASUSTek       | PRIME B550M-A               | [a5cd1ea7e4](https://linux-hardware.org/?probe=a5cd1ea7e4) | May 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [88c6676e7b](https://linux-hardware.org/?probe=88c6676e7b) | Apr 29, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f2bdbd2a4a](https://linux-hardware.org/?probe=f2bdbd2a4a) | Apr 29, 2022 |
| MSI           | Z97 PC Mate                 | [930c18b320](https://linux-hardware.org/?probe=930c18b320) | Apr 14, 2022 |
| Gigabyte      | H97M-HD3                    | [fc7b16c289](https://linux-hardware.org/?probe=fc7b16c289) | Apr 05, 2022 |
| Dell          | 0FPP7F A00                  | [8e8bee474f](https://linux-hardware.org/?probe=8e8bee474f) | Apr 03, 2022 |
| ASRock        | X99 Extreme4                | [112e437f5d](https://linux-hardware.org/?probe=112e437f5d) | Mar 31, 2022 |
| ASRock        | X99 Extreme4                | [293958c009](https://linux-hardware.org/?probe=293958c009) | Mar 31, 2022 |
| Dell          | 0F642F A00                  | [b3ae697cd6](https://linux-hardware.org/?probe=b3ae697cd6) | Mar 30, 2022 |
| Acer          | Aspire XC-885 V:1.1         | [8696148b4a](https://linux-hardware.org/?probe=8696148b4a) | Mar 29, 2022 |
| HP            | 0A98h                       | [4b9c0556af](https://linux-hardware.org/?probe=4b9c0556af) | Mar 26, 2022 |
| ASUSTek       | P7H55D-M EVO                | [2e70de8c8d](https://linux-hardware.org/?probe=2e70de8c8d) | Mar 19, 2022 |
| ASUSTek       | PRIME B460M-A               | [eaa5b0f454](https://linux-hardware.org/?probe=eaa5b0f454) | Mar 08, 2022 |
| ASUSTek       | PRIME B460M-A               | [e207d2bf0a](https://linux-hardware.org/?probe=e207d2bf0a) | Mar 08, 2022 |
| Gigabyte      | H310M S2 x.x                | [feb1d977ea](https://linux-hardware.org/?probe=feb1d977ea) | Feb 26, 2022 |
| MSI           | B550M PRO-VDH               | [747899db53](https://linux-hardware.org/?probe=747899db53) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [bd1fb80901](https://linux-hardware.org/?probe=bd1fb80901) | Feb 15, 2022 |
| ASRock        | 880GMH/USB3                 | [2789041a4d](https://linux-hardware.org/?probe=2789041a4d) | Feb 15, 2022 |
| ASUSTek       | PRIME Z590-P                | [fbea64f951](https://linux-hardware.org/?probe=fbea64f951) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [e21a51339e](https://linux-hardware.org/?probe=e21a51339e) | Feb 06, 2022 |
| ASUSTek       | PRIME Z590-P                | [cb34c3126d](https://linux-hardware.org/?probe=cb34c3126d) | Feb 05, 2022 |
| ASRock        | Z77 Pro3                    | [0bd2b97304](https://linux-hardware.org/?probe=0bd2b97304) | Feb 03, 2022 |
| Gigabyte      | B75M-D3H                    | [23987146db](https://linux-hardware.org/?probe=23987146db) | Feb 02, 2022 |
| MSI           | X570-A PRO                  | [df3c56c53c](https://linux-hardware.org/?probe=df3c56c53c) | Feb 02, 2022 |
| Lenovo        | 3176 NOK                    | [d3a3d5276b](https://linux-hardware.org/?probe=d3a3d5276b) | Feb 02, 2022 |
| MSI           | Z97 GAMING 5                | [26005d669e](https://linux-hardware.org/?probe=26005d669e) | Jan 29, 2022 |
| ASRock        | FM2A88X+ Killer             | [efc653778b](https://linux-hardware.org/?probe=efc653778b) | Jan 29, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [9e892d9ea3](https://linux-hardware.org/?probe=9e892d9ea3) | Jan 26, 2022 |
| HP            | 1998                        | [7bbd98aafa](https://linux-hardware.org/?probe=7bbd98aafa) | Jan 24, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [f1c61e2a1b](https://linux-hardware.org/?probe=f1c61e2a1b) | Jan 19, 2022 |
| HC            | HCAR357-MI V1.0             | [a610cc37dc](https://linux-hardware.org/?probe=a610cc37dc) | Jan 16, 2022 |
| MSI           | X58 Pro-E                   | [32b53a700a](https://linux-hardware.org/?probe=32b53a700a) | Jan 15, 2022 |
| ASUSTek       | M4A88T-V EVO/USB3           | [6eff31c620](https://linux-hardware.org/?probe=6eff31c620) | Jan 14, 2022 |
| HP            | 82F2                        | [708ffd7bb5](https://linux-hardware.org/?probe=708ffd7bb5) | Jan 13, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [e82feb71d2](https://linux-hardware.org/?probe=e82feb71d2) | Jan 12, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [0529614510](https://linux-hardware.org/?probe=0529614510) | Jan 12, 2022 |
| HP            | 8906 SMVB                   | [118b411a8c](https://linux-hardware.org/?probe=118b411a8c) | Jan 12, 2022 |
| Gigabyte      | Z87M-D3H                    | [7e4fe3d952](https://linux-hardware.org/?probe=7e4fe3d952) | Jan 10, 2022 |
| ASUSTek       | P5Q                         | [b2e4fe050c](https://linux-hardware.org/?probe=b2e4fe050c) | Jan 09, 2022 |
| ASRock        | FM2A55M-HD+                 | [91c54ce00a](https://linux-hardware.org/?probe=91c54ce00a) | Jan 08, 2022 |
| MSI           | Z390-A PRO                  | [9be23e2b2d](https://linux-hardware.org/?probe=9be23e2b2d) | Dec 30, 2021 |
| Biostar       | H55A+                       | [0a4141bcc2](https://linux-hardware.org/?probe=0a4141bcc2) | Dec 28, 2021 |
| Shuttle       | FZ87                        | [e26f5a10e8](https://linux-hardware.org/?probe=e26f5a10e8) | Dec 24, 2021 |
| Shuttle       | FZ87                        | [62a0a858a6](https://linux-hardware.org/?probe=62a0a858a6) | Dec 24, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [04bcdd10e9](https://linux-hardware.org/?probe=04bcdd10e9) | Dec 24, 2021 |
| ASRock        | FM2A55M-HD+                 | [d76ed454c1](https://linux-hardware.org/?probe=d76ed454c1) | Dec 24, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [4466b5357f](https://linux-hardware.org/?probe=4466b5357f) | Dec 21, 2021 |
| ASUSTek       | B85M-F                      | [04b3b165f6](https://linux-hardware.org/?probe=04b3b165f6) | Dec 14, 2021 |
| Dell          | 0GM819                      | [2b84176135](https://linux-hardware.org/?probe=2b84176135) | Dec 11, 2021 |
| ASUSTek       | H81M-K                      | [412accf186](https://linux-hardware.org/?probe=412accf186) | Dec 09, 2021 |
| HP            | 8184 X4                     | [3a2d5e3c77](https://linux-hardware.org/?probe=3a2d5e3c77) | Dec 08, 2021 |
| HP            | 8184 X4                     | [e225665abc](https://linux-hardware.org/?probe=e225665abc) | Dec 08, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [ad04822d41](https://linux-hardware.org/?probe=ad04822d41) | Dec 07, 2021 |
| ASRock        | B450M-HDV R4.0              | [594becb8c9](https://linux-hardware.org/?probe=594becb8c9) | Dec 06, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [7f6abaf57b](https://linux-hardware.org/?probe=7f6abaf57b) | Dec 05, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [3c693abd6e](https://linux-hardware.org/?probe=3c693abd6e) | Dec 04, 2021 |
| Dell          | 0WG261                      | [21617413f1](https://linux-hardware.org/?probe=21617413f1) | Dec 04, 2021 |
| Dell          | 0WG261                      | [95facf9dd4](https://linux-hardware.org/?probe=95facf9dd4) | Dec 04, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [8b68d87b85](https://linux-hardware.org/?probe=8b68d87b85) | Nov 28, 2021 |
| Dell          | 0F642F A00                  | [86a0053059](https://linux-hardware.org/?probe=86a0053059) | Nov 28, 2021 |
| Gigabyte      | Z87M-D3H                    | [185831a6a6](https://linux-hardware.org/?probe=185831a6a6) | Nov 28, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [064efec6fb](https://linux-hardware.org/?probe=064efec6fb) | Nov 27, 2021 |
| FIRICH        | J1900                       | [65b936ff81](https://linux-hardware.org/?probe=65b936ff81) | Nov 27, 2021 |
| Dell          | 0RF703                      | [fafb09d7a7](https://linux-hardware.org/?probe=fafb09d7a7) | Nov 27, 2021 |
| Dell          | 0RF703                      | [a1c5f0a19e](https://linux-hardware.org/?probe=a1c5f0a19e) | Nov 27, 2021 |
| ASUSTek       | P5B-VM SE                   | [0162ece16f](https://linux-hardware.org/?probe=0162ece16f) | Nov 25, 2021 |
| ASUSTek       | P8Z68-V GEN3                | [e8a1a915a4](https://linux-hardware.org/?probe=e8a1a915a4) | Nov 25, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [3355d6fd50](https://linux-hardware.org/?probe=3355d6fd50) | Nov 24, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [56f55d6a20](https://linux-hardware.org/?probe=56f55d6a20) | Nov 24, 2021 |
| HP            | 3647h                       | [e3d0601f0b](https://linux-hardware.org/?probe=e3d0601f0b) | Nov 23, 2021 |
| ASRock        | FM2A88X+ Killer             | [2b2b399b41](https://linux-hardware.org/?probe=2b2b399b41) | Nov 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | [7640e31dd0](https://linux-hardware.org/?probe=7640e31dd0) | Nov 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | [21a35c6975](https://linux-hardware.org/?probe=21a35c6975) | Nov 22, 2021 |
| Gigabyte      | Z370P D3-CF                 | [b2a2916a12](https://linux-hardware.org/?probe=b2a2916a12) | Nov 22, 2021 |
| Gigabyte      | B450M S2H                   | [d46b86b5c0](https://linux-hardware.org/?probe=d46b86b5c0) | Nov 22, 2021 |
| Dell          | 0R790T A00                  | [af9a5a76c3](https://linux-hardware.org/?probe=af9a5a76c3) | Nov 22, 2021 |
| Dell          | 0M9KCM A00                  | [e0f0471cee](https://linux-hardware.org/?probe=e0f0471cee) | Nov 20, 2021 |
| Gigabyte      | B450M S2H                   | [4fe276b0c3](https://linux-hardware.org/?probe=4fe276b0c3) | Nov 20, 2021 |
| Dell          | 07PR60 A00                  | [806800bb1f](https://linux-hardware.org/?probe=806800bb1f) | Nov 19, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [246e62e738](https://linux-hardware.org/?probe=246e62e738) | Nov 16, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [fc12beb786](https://linux-hardware.org/?probe=fc12beb786) | Nov 16, 2021 |
| Gigabyte      | H61M-S1                     | [c5764c10dc](https://linux-hardware.org/?probe=c5764c10dc) | Nov 16, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [877d892aae](https://linux-hardware.org/?probe=877d892aae) | Nov 15, 2021 |
| Gigabyte      | H61M-S1                     | [3028a32b5d](https://linux-hardware.org/?probe=3028a32b5d) | Nov 15, 2021 |
| Gigabyte      | X570 AORUS PRO              | [c202664327](https://linux-hardware.org/?probe=c202664327) | Nov 15, 2021 |
| MSI           | Z370M MORTAR                | [003fc9518e](https://linux-hardware.org/?probe=003fc9518e) | Nov 14, 2021 |
| MSI           | Z370M MORTAR                | [66683db42d](https://linux-hardware.org/?probe=66683db42d) | Nov 14, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [5d283e7da8](https://linux-hardware.org/?probe=5d283e7da8) | Nov 13, 2021 |
| ASUSTek       | M4N78-AM                    | [33e5f6918d](https://linux-hardware.org/?probe=33e5f6918d) | Nov 11, 2021 |
| HP            | 0AECh D                     | [7d8a81315d](https://linux-hardware.org/?probe=7d8a81315d) | Nov 11, 2021 |
| ASUSTek       | M5A97 R2.0                  | [3d5a6a79f2](https://linux-hardware.org/?probe=3d5a6a79f2) | Nov 10, 2021 |
| Gigabyte      | F2A78M-HD2                  | [4b0d19ecf1](https://linux-hardware.org/?probe=4b0d19ecf1) | Nov 08, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [c32869e5a8](https://linux-hardware.org/?probe=c32869e5a8) | Nov 08, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [0ef80f43bb](https://linux-hardware.org/?probe=0ef80f43bb) | Nov 08, 2021 |
| Gigabyte      | 970A-D3P                    | [0c5902f5a8](https://linux-hardware.org/?probe=0c5902f5a8) | Nov 07, 2021 |
| ASUSTek       | Z170-A                      | [5d9f112e39](https://linux-hardware.org/?probe=5d9f112e39) | Nov 07, 2021 |
| HP            | 0A9Ch                       | [59703eca34](https://linux-hardware.org/?probe=59703eca34) | Nov 05, 2021 |
| MSI           | IONA                        | [80a676d45e](https://linux-hardware.org/?probe=80a676d45e) | Nov 03, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [b643635a41](https://linux-hardware.org/?probe=b643635a41) | Nov 02, 2021 |
| MSI           | 2A9C                        | [7c98a4adff](https://linux-hardware.org/?probe=7c98a4adff) | Nov 02, 2021 |
| Gigabyte      | H110M-D2P-WG-CF             | [82a1f8e51e](https://linux-hardware.org/?probe=82a1f8e51e) | Nov 01, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [80627a5a8a](https://linux-hardware.org/?probe=80627a5a8a) | Nov 01, 2021 |
| Gigabyte      | H110M-D2P-WG-CF             | [36bf6dab37](https://linux-hardware.org/?probe=36bf6dab37) | Oct 31, 2021 |
| Dell          | 0X9M3X A03                  | [bbf963580d](https://linux-hardware.org/?probe=bbf963580d) | Oct 30, 2021 |
| HP            | 0A98h                       | [4299904c4d](https://linux-hardware.org/?probe=4299904c4d) | Oct 30, 2021 |
| MSI           | Z97 PC Mate                 | [5ca8bbd80d](https://linux-hardware.org/?probe=5ca8bbd80d) | Oct 30, 2021 |
| HP            | 0AECh D                     | [cd2f6268cf](https://linux-hardware.org/?probe=cd2f6268cf) | Oct 28, 2021 |
| MSI           | MEG B550 UNIFY              | [6326601487](https://linux-hardware.org/?probe=6326601487) | Oct 27, 2021 |
| Gigabyte      | Z77X-UD5H                   | [8d74dd99c7](https://linux-hardware.org/?probe=8d74dd99c7) | Oct 26, 2021 |
| MSI           | B85-G41 PC Mate             | [90659e6a34](https://linux-hardware.org/?probe=90659e6a34) | Oct 26, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [9d4edc7252](https://linux-hardware.org/?probe=9d4edc7252) | Oct 25, 2021 |
| MSI           | Trinergy                    | [f2f1ad0e41](https://linux-hardware.org/?probe=f2f1ad0e41) | Oct 25, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [6ecbec2c49](https://linux-hardware.org/?probe=6ecbec2c49) | Oct 25, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [d66b719066](https://linux-hardware.org/?probe=d66b719066) | Oct 23, 2021 |
| ASUSTek       | B150M-C/BR                  | [040d7f611e](https://linux-hardware.org/?probe=040d7f611e) | Oct 22, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | [545b983e7c](https://linux-hardware.org/?probe=545b983e7c) | Oct 22, 2021 |
| ASUSTek       | Q87M-E                      | [2253d95e90](https://linux-hardware.org/?probe=2253d95e90) | Oct 22, 2021 |
| HP            | 8053                        | [4f5c7dde74](https://linux-hardware.org/?probe=4f5c7dde74) | Oct 22, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | [0278eaa13a](https://linux-hardware.org/?probe=0278eaa13a) | Oct 22, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | [0be91c158b](https://linux-hardware.org/?probe=0be91c158b) | Oct 22, 2021 |
| ASRock        | 960GM/U3S3 FX               | [516c451ac1](https://linux-hardware.org/?probe=516c451ac1) | Oct 21, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [fe32d5538f](https://linux-hardware.org/?probe=fe32d5538f) | Oct 21, 2021 |
| Dell          | 0NK5PH A00                  | [36e6c22cc6](https://linux-hardware.org/?probe=36e6c22cc6) | Oct 20, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.309     | [7775a20781](https://linux-hardware.org/?probe=7775a20781) | Oct 20, 2021 |
| Gigabyte      | H87N-WIFI                   | [fb7beb9612](https://linux-hardware.org/?probe=fb7beb9612) | Oct 20, 2021 |
| MSI           | 2A9C                        | [29628ccee7](https://linux-hardware.org/?probe=29628ccee7) | Oct 19, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [9f21330313](https://linux-hardware.org/?probe=9f21330313) | Oct 18, 2021 |
| HP            | 8053                        | [8f76510560](https://linux-hardware.org/?probe=8f76510560) | Oct 17, 2021 |
| Dell          | 0M9KCM A00                  | [d837406f2a](https://linux-hardware.org/?probe=d837406f2a) | Oct 16, 2021 |
| ASUSTek       | TUF Z390-PRO GAMING         | [aa8e220390](https://linux-hardware.org/?probe=aa8e220390) | Oct 16, 2021 |
| IBM           | 81Y7071 SVT-R               | [033203aade](https://linux-hardware.org/?probe=033203aade) | Oct 16, 2021 |
| ASRock        | P67 Extreme4                | [fb4d76caab](https://linux-hardware.org/?probe=fb4d76caab) | Oct 16, 2021 |
| ASRock        | B460M Pro4                  | [1a90b22456](https://linux-hardware.org/?probe=1a90b22456) | Oct 16, 2021 |
| ASUSTek       | PRIME A320M-K               | [5c405f8cf2](https://linux-hardware.org/?probe=5c405f8cf2) | Oct 15, 2021 |
| ASUSTek       | PRIME A320M-K               | [722ca22e90](https://linux-hardware.org/?probe=722ca22e90) | Oct 15, 2021 |
| MSI           | Z270 PC MATE                | [72cbd4e7cf](https://linux-hardware.org/?probe=72cbd4e7cf) | Oct 15, 2021 |
| Dell          | 06FW8P A00                  | [7db180dfdd](https://linux-hardware.org/?probe=7db180dfdd) | Oct 15, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [e2538800e5](https://linux-hardware.org/?probe=e2538800e5) | Oct 15, 2021 |
| HP            | 0A98h                       | [5cebaf2fa6](https://linux-hardware.org/?probe=5cebaf2fa6) | Oct 14, 2021 |
| Dell          | 0N826N A03                  | [54b9ff49e4](https://linux-hardware.org/?probe=54b9ff49e4) | Oct 14, 2021 |
| ASUSTek       | M5A97 R2.0                  | [3074d8f202](https://linux-hardware.org/?probe=3074d8f202) | Oct 14, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a99608bc0c](https://linux-hardware.org/?probe=a99608bc0c) | Oct 13, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [294d1f6a89](https://linux-hardware.org/?probe=294d1f6a89) | Oct 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [0ca14eb2ea](https://linux-hardware.org/?probe=0ca14eb2ea) | Oct 12, 2021 |
| ASUSTek       | M5A97 R2.0                  | [138ad65457](https://linux-hardware.org/?probe=138ad65457) | Oct 12, 2021 |
| ASRock        | H97M Pro4                   | [3a14292469](https://linux-hardware.org/?probe=3a14292469) | Oct 12, 2021 |
| Gigabyte      | H61MA-D2V                   | [3968e39b0b](https://linux-hardware.org/?probe=3968e39b0b) | Oct 12, 2021 |
| MSI           | NF520T-C35                  | [277af949b6](https://linux-hardware.org/?probe=277af949b6) | Oct 12, 2021 |
| Dell          | 0N826N A03                  | [d74fd1a5d9](https://linux-hardware.org/?probe=d74fd1a5d9) | Oct 12, 2021 |
| MSI           | NF520T-C35                  | [ed9520268a](https://linux-hardware.org/?probe=ed9520268a) | Oct 12, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [5e8e9aea62](https://linux-hardware.org/?probe=5e8e9aea62) | Oct 12, 2021 |
| Gigabyte      | X99-UD3-CF                  | [347d6df600](https://linux-hardware.org/?probe=347d6df600) | Oct 12, 2021 |
| ASUSTek       | P8Z77-V LK                  | [64861e0fdd](https://linux-hardware.org/?probe=64861e0fdd) | Oct 11, 2021 |
| ASUSTek       | P8Z77-V LK                  | [0813ceeeca](https://linux-hardware.org/?probe=0813ceeeca) | Oct 11, 2021 |
| ASRock        | J4005M                      | [dbef05ba27](https://linux-hardware.org/?probe=dbef05ba27) | Oct 11, 2021 |
| HP            | 0A98h                       | [ea96f19e99](https://linux-hardware.org/?probe=ea96f19e99) | Oct 11, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [a671b6ab07](https://linux-hardware.org/?probe=a671b6ab07) | Oct 11, 2021 |
| Gigabyte      | B85M-DS3H-A                 | [9855c138d4](https://linux-hardware.org/?probe=9855c138d4) | Oct 11, 2021 |
| Dell          | 0HHV7N A00                  | [8fddbf28a1](https://linux-hardware.org/?probe=8fddbf28a1) | Oct 11, 2021 |
| MSI           | 2AE0                        | [e5ede0905a](https://linux-hardware.org/?probe=e5ede0905a) | Oct 10, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [1fa4e26ee6](https://linux-hardware.org/?probe=1fa4e26ee6) | Oct 10, 2021 |
| Dell          | 00FKMJ A00                  | [713d852597](https://linux-hardware.org/?probe=713d852597) | Oct 10, 2021 |
| Dell          | 0YXT71 A02                  | [ff477e5a71](https://linux-hardware.org/?probe=ff477e5a71) | Oct 10, 2021 |
| Acer          | Aspire XC600 v1.0           | [e770d8dd7c](https://linux-hardware.org/?probe=e770d8dd7c) | Oct 10, 2021 |
| Dell          | 0YXT71 A02                  | [f467bc83ef](https://linux-hardware.org/?probe=f467bc83ef) | Oct 10, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [032398c308](https://linux-hardware.org/?probe=032398c308) | Oct 10, 2021 |
| Dell          | 09KPNV A00                  | [d576cb2dd3](https://linux-hardware.org/?probe=d576cb2dd3) | Oct 10, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ad1aaa06bc](https://linux-hardware.org/?probe=ad1aaa06bc) | Oct 09, 2021 |
| ASUSTek       | P8Z77-M                     | [e2837da9c2](https://linux-hardware.org/?probe=e2837da9c2) | Oct 09, 2021 |
| ASUSTek       | M2N                         | [f319cddaf6](https://linux-hardware.org/?probe=f319cddaf6) | Oct 09, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [56e9375e76](https://linux-hardware.org/?probe=56e9375e76) | Oct 09, 2021 |
| ASUSTek       | PRIME B450M-A               | [f62701cf54](https://linux-hardware.org/?probe=f62701cf54) | Oct 09, 2021 |
| ASRock        | 970 Extreme4                | [64a98a63e8](https://linux-hardware.org/?probe=64a98a63e8) | Oct 09, 2021 |
| MSI           | B550M PRO-VDH               | [b806a146d2](https://linux-hardware.org/?probe=b806a146d2) | Oct 08, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [ed0af6256d](https://linux-hardware.org/?probe=ed0af6256d) | Oct 07, 2021 |
| MSI           | Z170M MORTAR                | [f0c8db4bdb](https://linux-hardware.org/?probe=f0c8db4bdb) | Oct 07, 2021 |
| MSI           | Z97-G45 GAMING              | [0d11725312](https://linux-hardware.org/?probe=0d11725312) | Oct 07, 2021 |
| HP            | 0AECh D                     | [415146d6ec](https://linux-hardware.org/?probe=415146d6ec) | Oct 07, 2021 |
| Foxconn       | 2AB1                        | [396ca17477](https://linux-hardware.org/?probe=396ca17477) | Oct 07, 2021 |
| ASUSTek       | P8Z68-V PRO GEN3            | [834aacd006](https://linux-hardware.org/?probe=834aacd006) | Oct 07, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [372dc0e0aa](https://linux-hardware.org/?probe=372dc0e0aa) | Oct 06, 2021 |
| Unknown       | Intel X79                   | [e3d2bdbc3d](https://linux-hardware.org/?probe=e3d2bdbc3d) | Oct 06, 2021 |
| ASUSTek       | P7P55D LE                   | [21e7391f6a](https://linux-hardware.org/?probe=21e7391f6a) | Oct 05, 2021 |
| Gigabyte      | GA-MA770T-UD3               | [4b6c9614d7](https://linux-hardware.org/?probe=4b6c9614d7) | Oct 05, 2021 |
| Acer          | Aspire M1930                | [0f21c5864a](https://linux-hardware.org/?probe=0f21c5864a) | Oct 05, 2021 |
| Dell          | 09KPNV A00                  | [d99107fc98](https://linux-hardware.org/?probe=d99107fc98) | Oct 04, 2021 |
| Intel         | DQ57TM AAE70931-403         | [bf6d27f32d](https://linux-hardware.org/?probe=bf6d27f32d) | Oct 04, 2021 |
| Dell          | 0KV62T A01                  | [fbf1a41e0e](https://linux-hardware.org/?probe=fbf1a41e0e) | Oct 04, 2021 |
| Dell          | 0T656F A02                  | [a5080391e9](https://linux-hardware.org/?probe=a5080391e9) | Oct 04, 2021 |
| ASUSTek       | P5Q SE2                     | [36c4b84f94](https://linux-hardware.org/?probe=36c4b84f94) | Oct 04, 2021 |
| Dell          | 0X8582                      | [ec2be1d168](https://linux-hardware.org/?probe=ec2be1d168) | Oct 03, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [9923b250ea](https://linux-hardware.org/?probe=9923b250ea) | Oct 02, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [a7876d8329](https://linux-hardware.org/?probe=a7876d8329) | Oct 02, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | [4a4f239e4d](https://linux-hardware.org/?probe=4a4f239e4d) | Oct 01, 2021 |
| Dell          | 0HHV7N A00                  | [601a9a3bec](https://linux-hardware.org/?probe=601a9a3bec) | Oct 01, 2021 |
| ASUSTek       | P7P55D-E                    | [9c801b9bcf](https://linux-hardware.org/?probe=9c801b9bcf) | Sep 30, 2021 |
| ASUSTek       | PRIME B360M-A               | [af2c7a813d](https://linux-hardware.org/?probe=af2c7a813d) | Sep 30, 2021 |
| ASUSTek       | PRIME B360M-A               | [e17f08bb61](https://linux-hardware.org/?probe=e17f08bb61) | Sep 30, 2021 |
| Gigabyte      | GA-78LMT-S2                 | [3977fe7bd2](https://linux-hardware.org/?probe=3977fe7bd2) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [410a604bab](https://linux-hardware.org/?probe=410a604bab) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1f251e5ba2](https://linux-hardware.org/?probe=1f251e5ba2) | Sep 29, 2021 |
| ASUSTek       | M4A785TD-V EVO              | [c21eff0d32](https://linux-hardware.org/?probe=c21eff0d32) | Sep 28, 2021 |
| ASRock        | Z97 Anniversary             | [c2e1c947ca](https://linux-hardware.org/?probe=c2e1c947ca) | Sep 28, 2021 |
| Dell          | 0D24M8 A01                  | [f1f58938d1](https://linux-hardware.org/?probe=f1f58938d1) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | [38a7a4c1d4](https://linux-hardware.org/?probe=38a7a4c1d4) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | [1f148a0dc9](https://linux-hardware.org/?probe=1f148a0dc9) | Sep 27, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | [37d30a84ca](https://linux-hardware.org/?probe=37d30a84ca) | Sep 27, 2021 |
| Dell          | 0KV62T A01                  | [5792f11670](https://linux-hardware.org/?probe=5792f11670) | Sep 27, 2021 |
| ASUSTek       | PRIME X370-PRO              | [6886cfc383](https://linux-hardware.org/?probe=6886cfc383) | Sep 26, 2021 |
| MSI           | X399 SLI PLUS               | [4d6c77accb](https://linux-hardware.org/?probe=4d6c77accb) | Sep 26, 2021 |
| ASUSTek       | M5A78L-M LE/USB3            | [28a3e24d5a](https://linux-hardware.org/?probe=28a3e24d5a) | Sep 26, 2021 |
| ASRock        | A320M-HDV R4.0              | [c5da6d90b3](https://linux-hardware.org/?probe=c5da6d90b3) | Sep 26, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [4a373f1855](https://linux-hardware.org/?probe=4a373f1855) | Sep 26, 2021 |
| ASUSTek       | PRIME Z590-P                | [d2aaa88c7a](https://linux-hardware.org/?probe=d2aaa88c7a) | Sep 25, 2021 |
| ASRock        | Z390M Pro4                  | [7be02e74b3](https://linux-hardware.org/?probe=7be02e74b3) | Sep 25, 2021 |
| ASUSTek       | PRIME H410M-A               | [dd082afe88](https://linux-hardware.org/?probe=dd082afe88) | Sep 24, 2021 |
| Gigabyte      | H310M S2 x.x                | [3aad736b24](https://linux-hardware.org/?probe=3aad736b24) | Sep 24, 2021 |
| ASRock        | Z390M Pro4                  | [449f4436f5](https://linux-hardware.org/?probe=449f4436f5) | Sep 24, 2021 |
| HP            | 843F                        | [2160393dde](https://linux-hardware.org/?probe=2160393dde) | Sep 24, 2021 |
| HP            | 843F                        | [be648e45cb](https://linux-hardware.org/?probe=be648e45cb) | Sep 24, 2021 |
| ASUSTek       | A55BM-K                     | [e06893df36](https://linux-hardware.org/?probe=e06893df36) | Sep 24, 2021 |
| HP            | 18E4                        | [fbd08bc910](https://linux-hardware.org/?probe=fbd08bc910) | Sep 23, 2021 |
| Acer          | EG43M                       | [e355190768](https://linux-hardware.org/?probe=e355190768) | Sep 23, 2021 |
| Acer          | EG43M                       | [e9e005a181](https://linux-hardware.org/?probe=e9e005a181) | Sep 23, 2021 |
| HP            | 0AA8h                       | [b702f1c3a2](https://linux-hardware.org/?probe=b702f1c3a2) | Sep 23, 2021 |
| MSI           | Z87 MPOWER MAX              | [9405707012](https://linux-hardware.org/?probe=9405707012) | Sep 23, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [b4bd76d198](https://linux-hardware.org/?probe=b4bd76d198) | Sep 23, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [bc776de3a8](https://linux-hardware.org/?probe=bc776de3a8) | Sep 23, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [46af053a8e](https://linux-hardware.org/?probe=46af053a8e) | Sep 23, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | [67338cd31a](https://linux-hardware.org/?probe=67338cd31a) | Sep 23, 2021 |
| HP            | 18E7                        | [4c52ebef48](https://linux-hardware.org/?probe=4c52ebef48) | Sep 22, 2021 |
| Gigabyte      | Z77-D3H                     | [fd1153a7da](https://linux-hardware.org/?probe=fd1153a7da) | Sep 22, 2021 |
| Acer          | EG43M                       | [48c256116d](https://linux-hardware.org/?probe=48c256116d) | Sep 21, 2021 |
| Dell          | 0KV62T A01                  | [70b115b474](https://linux-hardware.org/?probe=70b115b474) | Sep 21, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [fce5a6bf2a](https://linux-hardware.org/?probe=fce5a6bf2a) | Sep 21, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b44b19f051](https://linux-hardware.org/?probe=b44b19f051) | Sep 21, 2021 |
| ASUSTek       | Z170-A                      | [323169caf9](https://linux-hardware.org/?probe=323169caf9) | Sep 21, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [ef22f8090a](https://linux-hardware.org/?probe=ef22f8090a) | Sep 20, 2021 |
| Huanan        | X79 249PC V2.3              | [feb9cf5a3f](https://linux-hardware.org/?probe=feb9cf5a3f) | Sep 20, 2021 |
| Huanan        | X79 249PC V2.3              | [0025ab8888](https://linux-hardware.org/?probe=0025ab8888) | Sep 20, 2021 |
| ASRock        | X570 Taichi                 | [ab2b72b7d5](https://linux-hardware.org/?probe=ab2b72b7d5) | Sep 20, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [d922af010d](https://linux-hardware.org/?probe=d922af010d) | Sep 19, 2021 |
| MSI           | MS-7058 100                 | [e8b0580c54](https://linux-hardware.org/?probe=e8b0580c54) | Sep 19, 2021 |
| ASUSTek       | B85M-G                      | [9f31d3090b](https://linux-hardware.org/?probe=9f31d3090b) | Sep 19, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [1d86899e9a](https://linux-hardware.org/?probe=1d86899e9a) | Sep 19, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [b9c711e311](https://linux-hardware.org/?probe=b9c711e311) | Sep 19, 2021 |
| Dell          | 0X8582                      | [e4ea4d8c3e](https://linux-hardware.org/?probe=e4ea4d8c3e) | Sep 18, 2021 |
| Dell          | 0VRWRC A01                  | [c2a88904db](https://linux-hardware.org/?probe=c2a88904db) | Sep 18, 2021 |
| MSI           | A75MA-G55                   | [2e92160434](https://linux-hardware.org/?probe=2e92160434) | Sep 18, 2021 |
| Biostar       | A68MHE                      | [8a2cdafa86](https://linux-hardware.org/?probe=8a2cdafa86) | Sep 18, 2021 |
| Acer          | FIH57                       | [af740ea4c9](https://linux-hardware.org/?probe=af740ea4c9) | Sep 18, 2021 |
| Acer          | FIH57                       | [1f486783b8](https://linux-hardware.org/?probe=1f486783b8) | Sep 18, 2021 |
| MSI           | MS-7058 100                 | [87a56cdea2](https://linux-hardware.org/?probe=87a56cdea2) | Sep 18, 2021 |
| ASUSTek       | P8Z77-V LX                  | [4340e989f9](https://linux-hardware.org/?probe=4340e989f9) | Sep 17, 2021 |
| Gigabyte      | B450M DS3H-CF               | [76f8472281](https://linux-hardware.org/?probe=76f8472281) | Sep 16, 2021 |
| HP            | 339A                        | [973b7c1b1f](https://linux-hardware.org/?probe=973b7c1b1f) | Sep 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | [b2b889b773](https://linux-hardware.org/?probe=b2b889b773) | Sep 16, 2021 |
| HP            | 3048h                       | [b7b670e814](https://linux-hardware.org/?probe=b7b670e814) | Sep 16, 2021 |
| ASUSTek       | P6X58D-E                    | [1c61b20dd4](https://linux-hardware.org/?probe=1c61b20dd4) | Sep 16, 2021 |
| ASUSTek       | P8H77-M                     | [1efbf10e10](https://linux-hardware.org/?probe=1efbf10e10) | Sep 15, 2021 |
| Gigabyte      | 970A-UD3P                   | [6209c3e2c2](https://linux-hardware.org/?probe=6209c3e2c2) | Sep 15, 2021 |
| Gigabyte      | 970A-UD3P                   | [c5f600efd8](https://linux-hardware.org/?probe=c5f600efd8) | Sep 15, 2021 |
| HP            | 212B                        | [9a7f2627a3](https://linux-hardware.org/?probe=9a7f2627a3) | Sep 15, 2021 |
| HP            | 212B                        | [289f117cde](https://linux-hardware.org/?probe=289f117cde) | Sep 14, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [67361acb38](https://linux-hardware.org/?probe=67361acb38) | Sep 14, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [f7cc010076](https://linux-hardware.org/?probe=f7cc010076) | Sep 14, 2021 |
| ASRock        | 970 Pro3 R2.0               | [d172a59c18](https://linux-hardware.org/?probe=d172a59c18) | Sep 14, 2021 |
| ASUSTek       | P5K-VM                      | [59fc10448f](https://linux-hardware.org/?probe=59fc10448f) | Sep 14, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | [7e07383aa8](https://linux-hardware.org/?probe=7e07383aa8) | Sep 14, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [51a17a84a4](https://linux-hardware.org/?probe=51a17a84a4) | Sep 13, 2021 |
| Dell          | 0VRWRC A01                  | [a14cd2accb](https://linux-hardware.org/?probe=a14cd2accb) | Sep 13, 2021 |
| Gigabyte      | G1.Sniper 3                 | [4f79120f74](https://linux-hardware.org/?probe=4f79120f74) | Sep 13, 2021 |
| Dell          | 0VRWRC A01                  | [442dd66231](https://linux-hardware.org/?probe=442dd66231) | Sep 13, 2021 |
| ASRock        | FM2A58M-DG3+                | [7433bea790](https://linux-hardware.org/?probe=7433bea790) | Sep 13, 2021 |
| Gigabyte      | G1.Sniper 3                 | [3d3b3161f5](https://linux-hardware.org/?probe=3d3b3161f5) | Sep 12, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [edb5bc2cac](https://linux-hardware.org/?probe=edb5bc2cac) | Sep 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | [4404093ccf](https://linux-hardware.org/?probe=4404093ccf) | Sep 12, 2021 |
| ASUSTek       | Leonite2                    | [be99559571](https://linux-hardware.org/?probe=be99559571) | Sep 12, 2021 |
| Acer          | Revo RN96                   | [1559422fd4](https://linux-hardware.org/?probe=1559422fd4) | Sep 12, 2021 |
| Dell          | 0X8582                      | [75d86d9235](https://linux-hardware.org/?probe=75d86d9235) | Sep 12, 2021 |
| Unknown       | G41                         | [0ac983ecc1](https://linux-hardware.org/?probe=0ac983ecc1) | Sep 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a11f12a84a](https://linux-hardware.org/?probe=a11f12a84a) | Sep 12, 2021 |
| Acer          | Revo RN96                   | [9bfcad9af4](https://linux-hardware.org/?probe=9bfcad9af4) | Sep 11, 2021 |
| ASRock        | FM2A58M-HD+                 | [3be61fa185](https://linux-hardware.org/?probe=3be61fa185) | Sep 11, 2021 |
| ASUSTek       | P6X58D PREMIUM              | [5f2cc29efc](https://linux-hardware.org/?probe=5f2cc29efc) | Sep 11, 2021 |
| ASUSTek       | H110M-C                     | [e73e96c866](https://linux-hardware.org/?probe=e73e96c866) | Sep 11, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [67285c1d5d](https://linux-hardware.org/?probe=67285c1d5d) | Sep 11, 2021 |
| ASUSTek       | P8H77-M                     | [088a432984](https://linux-hardware.org/?probe=088a432984) | Sep 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | [ab69e5a8f1](https://linux-hardware.org/?probe=ab69e5a8f1) | Sep 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | [20664604ad](https://linux-hardware.org/?probe=20664604ad) | Sep 10, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [0e6deb049c](https://linux-hardware.org/?probe=0e6deb049c) | Sep 09, 2021 |
| ASUSTek       | A68HM-PLUS                  | [443986835d](https://linux-hardware.org/?probe=443986835d) | Sep 09, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [f04053a978](https://linux-hardware.org/?probe=f04053a978) | Sep 08, 2021 |
| ASRock        | 970 Extreme3                | [2d9e427f68](https://linux-hardware.org/?probe=2d9e427f68) | Sep 08, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [46f2f68684](https://linux-hardware.org/?probe=46f2f68684) | Sep 07, 2021 |
| ASUSTek       | AM1M-A                      | [4963032754](https://linux-hardware.org/?probe=4963032754) | Sep 07, 2021 |
| Intel         | DQ57TM AAE70931-403         | [6add940021](https://linux-hardware.org/?probe=6add940021) | Sep 07, 2021 |
| Dell          | 0M5DCD A00                  | [ddee404146](https://linux-hardware.org/?probe=ddee404146) | Sep 07, 2021 |
| ASRock        | B75M-GL R2.0                | [9e43cd58cd](https://linux-hardware.org/?probe=9e43cd58cd) | Sep 07, 2021 |
| Acer          | Aspire XC-830               | [859878d1b2](https://linux-hardware.org/?probe=859878d1b2) | Sep 06, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [463f501179](https://linux-hardware.org/?probe=463f501179) | Sep 06, 2021 |
| ASUSTek       | P6X58D-E                    | [ee58e16f17](https://linux-hardware.org/?probe=ee58e16f17) | Sep 06, 2021 |
| ASUSTek       | P6X58D-E                    | [c18c52cd70](https://linux-hardware.org/?probe=c18c52cd70) | Sep 06, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [d45a82c3c9](https://linux-hardware.org/?probe=d45a82c3c9) | Sep 06, 2021 |
| HP            | 870C                        | [f46fa4ba94](https://linux-hardware.org/?probe=f46fa4ba94) | Sep 06, 2021 |
| HP            | 870C                        | [fcd88590bc](https://linux-hardware.org/?probe=fcd88590bc) | Sep 06, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [129a34a37f](https://linux-hardware.org/?probe=129a34a37f) | Sep 06, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [e72963a1b5](https://linux-hardware.org/?probe=e72963a1b5) | Sep 06, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [28a20b5f72](https://linux-hardware.org/?probe=28a20b5f72) | Sep 06, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c6e769829b](https://linux-hardware.org/?probe=c6e769829b) | Sep 06, 2021 |
| ASUSTek       | P6X58D-E                    | [f1300c2d55](https://linux-hardware.org/?probe=f1300c2d55) | Sep 05, 2021 |
| ASRock        | B365M Pro4                  | [a244333b78](https://linux-hardware.org/?probe=a244333b78) | Sep 05, 2021 |
| HP            | 339A                        | [ceb91782c2](https://linux-hardware.org/?probe=ceb91782c2) | Sep 05, 2021 |
| HP            | ProLiant MicroServer        | [69ca9e90ae](https://linux-hardware.org/?probe=69ca9e90ae) | Sep 05, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [22390a295d](https://linux-hardware.org/?probe=22390a295d) | Sep 04, 2021 |
| HP            | 1494                        | [064f4ff59f](https://linux-hardware.org/?probe=064f4ff59f) | Sep 04, 2021 |
| ASUSTek       | AM1M-A                      | [4d7a9bb2cf](https://linux-hardware.org/?probe=4d7a9bb2cf) | Sep 04, 2021 |
| Pegatron      | Maureen                     | [c5ab105ead](https://linux-hardware.org/?probe=c5ab105ead) | Sep 04, 2021 |
| ASRock        | A300M-STX                   | [811f366c65](https://linux-hardware.org/?probe=811f366c65) | Sep 03, 2021 |
| ASRock        | Z370 Pro4                   | [a507f9835b](https://linux-hardware.org/?probe=a507f9835b) | Sep 03, 2021 |
| Gigabyte      | B85M-D3H                    | [5377e486bc](https://linux-hardware.org/?probe=5377e486bc) | Sep 03, 2021 |
| Pegatron      | Maureen                     | [8591d54048](https://linux-hardware.org/?probe=8591d54048) | Sep 03, 2021 |
| ASUSTek       | P7P55D LE                   | [8bbe7e58ae](https://linux-hardware.org/?probe=8bbe7e58ae) | Sep 02, 2021 |
| ASUSTek       | P7P55D LE                   | [21fd5c096a](https://linux-hardware.org/?probe=21fd5c096a) | Sep 02, 2021 |
| MSI           | TRX40 PRO WIFI              | [d337b01cb3](https://linux-hardware.org/?probe=d337b01cb3) | Sep 02, 2021 |
| Biostar       | H77MU3                      | [82f367ec4b](https://linux-hardware.org/?probe=82f367ec4b) | Sep 02, 2021 |
| ASUSTek       | Z87-EXPERT                  | [f8846969fd](https://linux-hardware.org/?probe=f8846969fd) | Sep 02, 2021 |
| HP            | 18E9                        | [22f86af485](https://linux-hardware.org/?probe=22f86af485) | Sep 01, 2021 |
| ASUSTek       | PRIME Z270-A                | [0a0d13044d](https://linux-hardware.org/?probe=0a0d13044d) | Sep 01, 2021 |
| HP            | 1998                        | [585ff46bb3](https://linux-hardware.org/?probe=585ff46bb3) | Sep 01, 2021 |
| ASUSTek       | PRIME Z270-A                | [cde0de2a3d](https://linux-hardware.org/?probe=cde0de2a3d) | Sep 01, 2021 |
| FIRICH        | J1900                       | [a682347a14](https://linux-hardware.org/?probe=a682347a14) | Sep 01, 2021 |
| Gigabyte      | Z370 HD3P-CF                | [0f8fe06e8f](https://linux-hardware.org/?probe=0f8fe06e8f) | Aug 31, 2021 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [e689b2de7a](https://linux-hardware.org/?probe=e689b2de7a) | Aug 31, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [078613f010](https://linux-hardware.org/?probe=078613f010) | Aug 31, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [02cd32fbb4](https://linux-hardware.org/?probe=02cd32fbb4) | Aug 30, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [b5459f613b](https://linux-hardware.org/?probe=b5459f613b) | Aug 30, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e829df72a5](https://linux-hardware.org/?probe=e829df72a5) | Aug 30, 2021 |
| ASRock        | FM2A58M-HD+                 | [9eb666fd13](https://linux-hardware.org/?probe=9eb666fd13) | Aug 30, 2021 |
| Fujitsu       | D3313-F1 S26361-D3313-F1    | [47c72f21ae](https://linux-hardware.org/?probe=47c72f21ae) | Aug 30, 2021 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [f4e788dce6](https://linux-hardware.org/?probe=f4e788dce6) | Aug 30, 2021 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [8f5b776bcb](https://linux-hardware.org/?probe=8f5b776bcb) | Aug 30, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [4771af382d](https://linux-hardware.org/?probe=4771af382d) | Aug 30, 2021 |
| MSI           | P67A-C45                    | [5f5d217d7b](https://linux-hardware.org/?probe=5f5d217d7b) | Aug 30, 2021 |
| MSI           | P67A-C45                    | [8f1d2c8ca0](https://linux-hardware.org/?probe=8f1d2c8ca0) | Aug 30, 2021 |
| ASUSTek       | PRIME A320M-K/BR            | [2ca1595715](https://linux-hardware.org/?probe=2ca1595715) | Aug 30, 2021 |
| ASUSTek       | P6X58D-E                    | [a2c8bb417d](https://linux-hardware.org/?probe=a2c8bb417d) | Aug 29, 2021 |
| Gigabyte      | H55-USB3                    | [ae6cbc8dd8](https://linux-hardware.org/?probe=ae6cbc8dd8) | Aug 29, 2021 |
| ASRock        | FM2A58M-HD+                 | [8a976ca31c](https://linux-hardware.org/?probe=8a976ca31c) | Aug 29, 2021 |
| HP            | 18E9                        | [539f181954](https://linux-hardware.org/?probe=539f181954) | Aug 29, 2021 |
| Foxconn       | 2ABF                        | [171462cc36](https://linux-hardware.org/?probe=171462cc36) | Aug 29, 2021 |
| Gigabyte      | A320M-H-CF                  | [a089d56f43](https://linux-hardware.org/?probe=a089d56f43) | Aug 29, 2021 |
| Gigabyte      | Z77-DS3H                    | [e06775bbd6](https://linux-hardware.org/?probe=e06775bbd6) | Aug 29, 2021 |
| HP            | 3397                        | [abf1615138](https://linux-hardware.org/?probe=abf1615138) | Aug 29, 2021 |
| Gigabyte      | B450M DS3H-CF               | [99b7f572be](https://linux-hardware.org/?probe=99b7f572be) | Aug 28, 2021 |
| ASUSTek       | P6X58D-E                    | [593479bed8](https://linux-hardware.org/?probe=593479bed8) | Aug 28, 2021 |
| ASUSTek       | PRIME Z270-A                | [9e81caf509](https://linux-hardware.org/?probe=9e81caf509) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [04c8ccfac4](https://linux-hardware.org/?probe=04c8ccfac4) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2ad8401f8f](https://linux-hardware.org/?probe=2ad8401f8f) | Aug 28, 2021 |
| Pegatron      | IPMSB-GS                    | [b17f032a44](https://linux-hardware.org/?probe=b17f032a44) | Aug 27, 2021 |
| HP            | 2B34                        | [9477a88acd](https://linux-hardware.org/?probe=9477a88acd) | Aug 27, 2021 |
| Gigabyte      | M68MT-S2P                   | [e234ec66f2](https://linux-hardware.org/?probe=e234ec66f2) | Aug 27, 2021 |
| Pegatron      | IPMSB-GS                    | [9d2bbbabf1](https://linux-hardware.org/?probe=9d2bbbabf1) | Aug 27, 2021 |
| Dell          | 0R790T A00                  | [03b37f86b2](https://linux-hardware.org/?probe=03b37f86b2) | Aug 27, 2021 |
| Shuttle       | FH61V                       | [11b6744d1c](https://linux-hardware.org/?probe=11b6744d1c) | Aug 27, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [c8198b5d21](https://linux-hardware.org/?probe=c8198b5d21) | Aug 26, 2021 |
| ASUSTek       | Z97-P                       | [1fc077ad52](https://linux-hardware.org/?probe=1fc077ad52) | Aug 26, 2021 |
| HP            | 1494                        | [29bc1c62ad](https://linux-hardware.org/?probe=29bc1c62ad) | Aug 26, 2021 |
| Gigabyte      | 990FXA-UD3                  | [2f9e0312b5](https://linux-hardware.org/?probe=2f9e0312b5) | Aug 26, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [badc363516](https://linux-hardware.org/?probe=badc363516) | Aug 26, 2021 |
| HP            | 8768 A                      | [40e82f4d4f](https://linux-hardware.org/?probe=40e82f4d4f) | Aug 25, 2021 |
| ASUSTek       | P5G41T-M LX                 | [870deaf9fd](https://linux-hardware.org/?probe=870deaf9fd) | Aug 25, 2021 |
| ASUSTek       | P5G41T-M LX                 | [4b952eb1ae](https://linux-hardware.org/?probe=4b952eb1ae) | Aug 25, 2021 |
| Shuttle       | FH61V                       | [1b74c0ad1d](https://linux-hardware.org/?probe=1b74c0ad1d) | Aug 25, 2021 |
| Dell          | 03NVJ6 A02                  | [75869e33b7](https://linux-hardware.org/?probe=75869e33b7) | Aug 25, 2021 |
| Medion        | MS-7501                     | [c84fb9217e](https://linux-hardware.org/?probe=c84fb9217e) | Aug 25, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [2a6bfff91f](https://linux-hardware.org/?probe=2a6bfff91f) | Aug 24, 2021 |
| HP            | 8054                        | [d54cd14c63](https://linux-hardware.org/?probe=d54cd14c63) | Aug 24, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [e9e6b8b426](https://linux-hardware.org/?probe=e9e6b8b426) | Aug 24, 2021 |
| ASRock        | Q77M vPro                   | [f53a9f288f](https://linux-hardware.org/?probe=f53a9f288f) | Aug 24, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [8a59fff598](https://linux-hardware.org/?probe=8a59fff598) | Aug 24, 2021 |
| Gigabyte      | H510M S2H                   | [c10c8ceffe](https://linux-hardware.org/?probe=c10c8ceffe) | Aug 23, 2021 |
| Gigabyte      | F2A78M-HD2                  | [410b6b854f](https://linux-hardware.org/?probe=410b6b854f) | Aug 23, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [c5414322d8](https://linux-hardware.org/?probe=c5414322d8) | Aug 23, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [a0805b7ffd](https://linux-hardware.org/?probe=a0805b7ffd) | Aug 23, 2021 |
| HP            | ProLiant ML350 G6           | [d89bfcf1f9](https://linux-hardware.org/?probe=d89bfcf1f9) | Aug 22, 2021 |
| HP            | 1494                        | [414b1c48e7](https://linux-hardware.org/?probe=414b1c48e7) | Aug 22, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [1c910aa761](https://linux-hardware.org/?probe=1c910aa761) | Aug 22, 2021 |
| Gigabyte      | A320M-H-CF                  | [1c1434ce76](https://linux-hardware.org/?probe=1c1434ce76) | Aug 21, 2021 |
| Acer          | EG43M                       | [3c17aecee4](https://linux-hardware.org/?probe=3c17aecee4) | Aug 21, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [e9b8721812](https://linux-hardware.org/?probe=e9b8721812) | Aug 21, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [0c8cadf01b](https://linux-hardware.org/?probe=0c8cadf01b) | Aug 20, 2021 |
| ASUSTek       | M2N-E SLI                   | [149d762d08](https://linux-hardware.org/?probe=149d762d08) | Aug 20, 2021 |
| Gigabyte      | H87M-HD3                    | [bdc2409477](https://linux-hardware.org/?probe=bdc2409477) | Aug 20, 2021 |
| ASRock        | H61M-VG3                    | [7e1f4b1620](https://linux-hardware.org/?probe=7e1f4b1620) | Aug 20, 2021 |
| MSI           | MEG X570 UNIFY              | [c4800a930a](https://linux-hardware.org/?probe=c4800a930a) | Aug 20, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [bffc40c965](https://linux-hardware.org/?probe=bffc40c965) | Aug 19, 2021 |
| Gigabyte      | H61M-S1                     | [0223d6864b](https://linux-hardware.org/?probe=0223d6864b) | Aug 19, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [0c1d976c3c](https://linux-hardware.org/?probe=0c1d976c3c) | Aug 19, 2021 |
| Dell          | 0M5DCD A00                  | [5c98a0115b](https://linux-hardware.org/?probe=5c98a0115b) | Aug 19, 2021 |
| Gigabyte      | M68MT-S2P                   | [e983759ddc](https://linux-hardware.org/?probe=e983759ddc) | Aug 19, 2021 |
| Gigabyte      | H310M S2 x.x                | [e26140d6a5](https://linux-hardware.org/?probe=e26140d6a5) | Aug 19, 2021 |
| ASRock        | 970 Extreme3                | [40aa5bc719](https://linux-hardware.org/?probe=40aa5bc719) | Aug 19, 2021 |
| MSI           | B450-A PRO MAX              | [7cf3758630](https://linux-hardware.org/?probe=7cf3758630) | Aug 19, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [5b2b23ac97](https://linux-hardware.org/?probe=5b2b23ac97) | Aug 19, 2021 |
| ASUSTek       | M2N-E SLI                   | [4c1a100ab1](https://linux-hardware.org/?probe=4c1a100ab1) | Aug 19, 2021 |
| ASUSTek       | M2N-E SLI                   | [810f986c77](https://linux-hardware.org/?probe=810f986c77) | Aug 19, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [a20cebc67a](https://linux-hardware.org/?probe=a20cebc67a) | Aug 18, 2021 |
| ASUSTek       | M5A78L LE                   | [8e26bae3fc](https://linux-hardware.org/?probe=8e26bae3fc) | Aug 18, 2021 |
| ASUSTek       | P8P67                       | [9bed63f2f6](https://linux-hardware.org/?probe=9bed63f2f6) | Aug 18, 2021 |
| ASUSTek       | P8P67                       | [8885a008e0](https://linux-hardware.org/?probe=8885a008e0) | Aug 18, 2021 |
| Gigabyte      | G41M-ES2L                   | [996054b23c](https://linux-hardware.org/?probe=996054b23c) | Aug 18, 2021 |
| MSI           | B450-A PRO MAX              | [38ce4c1114](https://linux-hardware.org/?probe=38ce4c1114) | Aug 18, 2021 |
| Gigabyte      | X570 AORUS XTREME           | [8596bc4b0e](https://linux-hardware.org/?probe=8596bc4b0e) | Aug 18, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [eb1e9924f7](https://linux-hardware.org/?probe=eb1e9924f7) | Aug 18, 2021 |
| Gigabyte      | H310M S2 x.x                | [3e3018cc57](https://linux-hardware.org/?probe=3e3018cc57) | Aug 17, 2021 |
| HP            | 1494                        | [df10192c5b](https://linux-hardware.org/?probe=df10192c5b) | Aug 16, 2021 |
| ASUSTek       | B150M-C                     | [794387ddd6](https://linux-hardware.org/?probe=794387ddd6) | Aug 16, 2021 |
| Medion        | MS-7707                     | [66ace31297](https://linux-hardware.org/?probe=66ace31297) | Aug 16, 2021 |
| Unknown       | Unknown                     | [65ebd0006e](https://linux-hardware.org/?probe=65ebd0006e) | Aug 16, 2021 |
| Dell          | 082WXT A01                  | [e6b9ac8959](https://linux-hardware.org/?probe=e6b9ac8959) | Aug 16, 2021 |
| Lenovo        | 0B98401 PRO                 | [537aee667d](https://linux-hardware.org/?probe=537aee667d) | Aug 16, 2021 |
| ASUSTek       | Basswood                    | [f42051fa02](https://linux-hardware.org/?probe=f42051fa02) | Aug 15, 2021 |
| Gigabyte      | X99-SLI-CF                  | [27f528f809](https://linux-hardware.org/?probe=27f528f809) | Aug 15, 2021 |
| ASUSTek       | P8H67                       | [7c1b975d25](https://linux-hardware.org/?probe=7c1b975d25) | Aug 15, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [696380b374](https://linux-hardware.org/?probe=696380b374) | Aug 15, 2021 |
| ASUSTek       | P8Z68-V LX                  | [5076334ae6](https://linux-hardware.org/?probe=5076334ae6) | Aug 15, 2021 |
| Dell          | 0NK5PH A00                  | [676c2b2a79](https://linux-hardware.org/?probe=676c2b2a79) | Aug 14, 2021 |
| ASRock        | H97M Pro4                   | [5edf7e02c8](https://linux-hardware.org/?probe=5edf7e02c8) | Aug 14, 2021 |
| Gigabyte      | B460M DS3H AC V2-Y1         | [e2d8270403](https://linux-hardware.org/?probe=e2d8270403) | Aug 13, 2021 |
| Gigabyte      | B460M DS3H AC V2-Y1         | [e9e0bafaee](https://linux-hardware.org/?probe=e9e0bafaee) | Aug 13, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [fec985ca69](https://linux-hardware.org/?probe=fec985ca69) | Aug 13, 2021 |
| Gigabyte      | Z170XP-SLI-CF               | [1174eec6c2](https://linux-hardware.org/?probe=1174eec6c2) | Aug 13, 2021 |
| Acer          | Veriton X2631G V:1.0        | [d0db0c37b0](https://linux-hardware.org/?probe=d0db0c37b0) | Aug 12, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [adde6ef882](https://linux-hardware.org/?probe=adde6ef882) | Aug 12, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [02f3303081](https://linux-hardware.org/?probe=02f3303081) | Aug 12, 2021 |
| ASRock        | B550M-ITX/ac                | [9b490356cb](https://linux-hardware.org/?probe=9b490356cb) | Aug 11, 2021 |
| ECS           | Asterope3                   | [9255f2e941](https://linux-hardware.org/?probe=9255f2e941) | Aug 10, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [2af094f75d](https://linux-hardware.org/?probe=2af094f75d) | Aug 10, 2021 |
| Gigabyte      | GA-A55M-DS2                 | [8beee2f359](https://linux-hardware.org/?probe=8beee2f359) | Aug 10, 2021 |
| ASUSTek       | D642MF                      | [e50f269bc9](https://linux-hardware.org/?probe=e50f269bc9) | Aug 10, 2021 |
| Gigabyte      | GA-A55M-DS2                 | [d2e35c6ccb](https://linux-hardware.org/?probe=d2e35c6ccb) | Aug 10, 2021 |
| ASUSTek       | P7H55D-M EVO                | [88dcb8813a](https://linux-hardware.org/?probe=88dcb8813a) | Aug 10, 2021 |
| ASUSTek       | P7H55D-M EVO                | [07fad2e81c](https://linux-hardware.org/?probe=07fad2e81c) | Aug 10, 2021 |
| HP            | 87D6 SMVB                   | [7e4cda26e2](https://linux-hardware.org/?probe=7e4cda26e2) | Aug 09, 2021 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [a2c47444e8](https://linux-hardware.org/?probe=a2c47444e8) | Aug 09, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [aaf4f26a30](https://linux-hardware.org/?probe=aaf4f26a30) | Aug 09, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c42793eeff](https://linux-hardware.org/?probe=c42793eeff) | Aug 08, 2021 |
| HP            | 212B                        | [ee483c7463](https://linux-hardware.org/?probe=ee483c7463) | Aug 08, 2021 |
| AOpen         | D1009 A1A4                  | [a1ad011d2c](https://linux-hardware.org/?probe=a1ad011d2c) | Aug 08, 2021 |
| Foxconn       | 2A8C                        | [7123b6c779](https://linux-hardware.org/?probe=7123b6c779) | Aug 08, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [b4fe0907aa](https://linux-hardware.org/?probe=b4fe0907aa) | Aug 08, 2021 |
| HP            | 1998                        | [b0e8ef9aa2](https://linux-hardware.org/?probe=b0e8ef9aa2) | Aug 08, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [8c36ac6a56](https://linux-hardware.org/?probe=8c36ac6a56) | Aug 07, 2021 |
| MSI           | Z97 GAMING 9 AC             | [17ce8c5436](https://linux-hardware.org/?probe=17ce8c5436) | Aug 07, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [fd15e7b399](https://linux-hardware.org/?probe=fd15e7b399) | Aug 07, 2021 |
| ASUSTek       | M5A78L LE                   | [32192f4588](https://linux-hardware.org/?probe=32192f4588) | Aug 07, 2021 |
| ASUSTek       | PRIME B450M-A               | [21e4e5c57d](https://linux-hardware.org/?probe=21e4e5c57d) | Aug 07, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [a053325efe](https://linux-hardware.org/?probe=a053325efe) | Aug 06, 2021 |
| Gigabyte      | A320M-S2H-CF                | [09fa4c99dc](https://linux-hardware.org/?probe=09fa4c99dc) | Aug 06, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [2415e3e33f](https://linux-hardware.org/?probe=2415e3e33f) | Aug 06, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [c149c02018](https://linux-hardware.org/?probe=c149c02018) | Aug 06, 2021 |
| Acer          | Veriton X2631G V:1.0        | [7306d11e16](https://linux-hardware.org/?probe=7306d11e16) | Aug 06, 2021 |
| MSI           | Z370 TOMAHAWK               | [3118d29bf0](https://linux-hardware.org/?probe=3118d29bf0) | Aug 05, 2021 |
| Gigabyte      | B85M-D3H                    | [3e56e95f2f](https://linux-hardware.org/?probe=3e56e95f2f) | Aug 05, 2021 |
| ASUSTek       | M4A78 PRO                   | [ef7f570d01](https://linux-hardware.org/?probe=ef7f570d01) | Aug 04, 2021 |
| Dell          | 03NVJ6 A02                  | [a2a1574d81](https://linux-hardware.org/?probe=a2a1574d81) | Aug 04, 2021 |
| MSI           | 2A9C                        | [3616ca63df](https://linux-hardware.org/?probe=3616ca63df) | Aug 04, 2021 |
| Biostar       | A68MHE                      | [160e00a244](https://linux-hardware.org/?probe=160e00a244) | Aug 04, 2021 |
| ASRock        | X570 Taichi                 | [a7feba2af0](https://linux-hardware.org/?probe=a7feba2af0) | Aug 04, 2021 |
| Gigabyte      | Z87M-D3H                    | [e679a451ab](https://linux-hardware.org/?probe=e679a451ab) | Aug 03, 2021 |
| ASUSTek       | PRIME A320M-C R2.0          | [32e0ae8af0](https://linux-hardware.org/?probe=32e0ae8af0) | Aug 03, 2021 |
| MSI           | Z97-G43 GAMING              | [282ecb40ca](https://linux-hardware.org/?probe=282ecb40ca) | Aug 03, 2021 |
| MSI           | Z97-G43 GAMING              | [ce156e88b0](https://linux-hardware.org/?probe=ce156e88b0) | Aug 03, 2021 |
| ASUSTek       | M3N78 PRO                   | [dda6e493b7](https://linux-hardware.org/?probe=dda6e493b7) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS Gaming 7         | [d976766cee](https://linux-hardware.org/?probe=d976766cee) | Aug 03, 2021 |
| Foxconn       | 2A8C                        | [67e965bb06](https://linux-hardware.org/?probe=67e965bb06) | Aug 02, 2021 |
| MSI           | G31M3-F V2                  | [8f821ac3a7](https://linux-hardware.org/?probe=8f821ac3a7) | Aug 02, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [cb617ee0fa](https://linux-hardware.org/?probe=cb617ee0fa) | Aug 02, 2021 |
| ASUSTek       | P7Q57-M DO                  | [e14cd31bf6](https://linux-hardware.org/?probe=e14cd31bf6) | Aug 01, 2021 |
| Gigabyte      | Z87X-UD4H-CF                | [39b2e07348](https://linux-hardware.org/?probe=39b2e07348) | Aug 01, 2021 |
| Gigabyte      | Z87X-UD4H-CF                | [aaece9a4d4](https://linux-hardware.org/?probe=aaece9a4d4) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | [2c67644e4c](https://linux-hardware.org/?probe=2c67644e4c) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | [3b4a485e30](https://linux-hardware.org/?probe=3b4a485e30) | Jul 31, 2021 |
| Gigabyte      | G41M-ES2H                   | [ba0824b1c9](https://linux-hardware.org/?probe=ba0824b1c9) | Jul 30, 2021 |
| Gigabyte      | B450M DS3H-CF               | [fda988dc8a](https://linux-hardware.org/?probe=fda988dc8a) | Jul 30, 2021 |
| ASRock        | H470M-HVS                   | [97dbb1b8b9](https://linux-hardware.org/?probe=97dbb1b8b9) | Jul 30, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [4a27442871](https://linux-hardware.org/?probe=4a27442871) | Jul 30, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [d3e4773f47](https://linux-hardware.org/?probe=d3e4773f47) | Jul 30, 2021 |
| MSI           | H510M PRO                   | [6b204e25a9](https://linux-hardware.org/?probe=6b204e25a9) | Jul 29, 2021 |
| Dell          | 0JGM7F A00                  | [8eba192a2d](https://linux-hardware.org/?probe=8eba192a2d) | Jul 29, 2021 |
| Dell          | 0JGM7F A00                  | [d2cd2288c7](https://linux-hardware.org/?probe=d2cd2288c7) | Jul 29, 2021 |
| MSI           | H510I PRO WIFI              | [e896a37f1d](https://linux-hardware.org/?probe=e896a37f1d) | Jul 29, 2021 |
| MSI           | G31TM-P21                   | [024df6a0c1](https://linux-hardware.org/?probe=024df6a0c1) | Jul 29, 2021 |
| Dell          | 0NKW6Y A00                  | [85f066488a](https://linux-hardware.org/?probe=85f066488a) | Jul 29, 2021 |
| Gigabyte      | G41M-ES2H                   | [04b060a090](https://linux-hardware.org/?probe=04b060a090) | Jul 29, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [55f86a29a2](https://linux-hardware.org/?probe=55f86a29a2) | Jul 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [41c1c2551d](https://linux-hardware.org/?probe=41c1c2551d) | Jul 29, 2021 |
| Dell          | 0NKW6Y A00                  | [fd1285b7f2](https://linux-hardware.org/?probe=fd1285b7f2) | Jul 29, 2021 |
| ASRock        | 970 Extreme3                | [4769f95bad](https://linux-hardware.org/?probe=4769f95bad) | Jul 29, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [8fe5a59e53](https://linux-hardware.org/?probe=8fe5a59e53) | Jul 28, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [844de3ccbf](https://linux-hardware.org/?probe=844de3ccbf) | Jul 28, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [6fcd0a6b24](https://linux-hardware.org/?probe=6fcd0a6b24) | Jul 27, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [67a1d9bcc9](https://linux-hardware.org/?probe=67a1d9bcc9) | Jul 27, 2021 |
| MSI           | B450M PRO-VDH MAX           | [8a24dd720f](https://linux-hardware.org/?probe=8a24dd720f) | Jul 27, 2021 |
| Intel         | BTC-T37                     | [758e5d4332](https://linux-hardware.org/?probe=758e5d4332) | Jul 27, 2021 |
| Intel         | BTC-T37                     | [000e132ac1](https://linux-hardware.org/?probe=000e132ac1) | Jul 26, 2021 |
| ASUSTek       | Z97-K                       | [588c5ca9f6](https://linux-hardware.org/?probe=588c5ca9f6) | Jul 26, 2021 |
| ASUSTek       | Z97-P                       | [ef88333344](https://linux-hardware.org/?probe=ef88333344) | Jul 26, 2021 |
| ASUSTek       | H110M-R                     | [87ca1f0bda](https://linux-hardware.org/?probe=87ca1f0bda) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3185d49877](https://linux-hardware.org/?probe=3185d49877) | Jul 26, 2021 |
| Dell          | 0R790T A00                  | [474dfcb3e3](https://linux-hardware.org/?probe=474dfcb3e3) | Jul 26, 2021 |
| Dell          | 0RY007                      | [f2cd48444a](https://linux-hardware.org/?probe=f2cd48444a) | Jul 26, 2021 |
| ASUSTek       | Rampage III Extreme         | [f637e33171](https://linux-hardware.org/?probe=f637e33171) | Jul 25, 2021 |
| ASUSTek       | B150M-K                     | [34e2582dc2](https://linux-hardware.org/?probe=34e2582dc2) | Jul 25, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [acc53aae10](https://linux-hardware.org/?probe=acc53aae10) | Jul 25, 2021 |
| MSI           | Z490-A PRO                  | [740f322568](https://linux-hardware.org/?probe=740f322568) | Jul 25, 2021 |
| HP            | 212B                        | [2ae8fe394a](https://linux-hardware.org/?probe=2ae8fe394a) | Jul 24, 2021 |
| Dell          | 0D24M8 A01                  | [2080a71bc0](https://linux-hardware.org/?probe=2080a71bc0) | Jul 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [3d2cd06389](https://linux-hardware.org/?probe=3d2cd06389) | Jul 24, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [aa0949f27f](https://linux-hardware.org/?probe=aa0949f27f) | Jul 24, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [61aa66455b](https://linux-hardware.org/?probe=61aa66455b) | Jul 23, 2021 |
| MSI           | H110M PRO-VH                | [42bd7fe7d2](https://linux-hardware.org/?probe=42bd7fe7d2) | Jul 23, 2021 |
| MSI           | 3664h                       | [8141885507](https://linux-hardware.org/?probe=8141885507) | Jul 23, 2021 |
| MSI           | B360M BAZOOKA               | [c0e89d7f2c](https://linux-hardware.org/?probe=c0e89d7f2c) | Jul 23, 2021 |
| MSI           | B360M BAZOOKA               | [53b9087fbb](https://linux-hardware.org/?probe=53b9087fbb) | Jul 23, 2021 |
| Gigabyte      | 945GCMX-S2                  | [c9d0df911e](https://linux-hardware.org/?probe=c9d0df911e) | Jul 23, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [bc81196561](https://linux-hardware.org/?probe=bc81196561) | Jul 22, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [81c950f0e4](https://linux-hardware.org/?probe=81c950f0e4) | Jul 22, 2021 |
| Acer          | WMCP78M                     | [591c077e28](https://linux-hardware.org/?probe=591c077e28) | Jul 22, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [f00892d38b](https://linux-hardware.org/?probe=f00892d38b) | Jul 22, 2021 |
| Intel         | X79 V2.4F                   | [62eca59ba3](https://linux-hardware.org/?probe=62eca59ba3) | Jul 22, 2021 |
| Intel         | X79 V2.4F                   | [c469ee9d35](https://linux-hardware.org/?probe=c469ee9d35) | Jul 22, 2021 |
| Acer          | WMCP78M                     | [4d35606ff5](https://linux-hardware.org/?probe=4d35606ff5) | Jul 22, 2021 |
| Acer          | Aspire TC-780               | [cc39834e1d](https://linux-hardware.org/?probe=cc39834e1d) | Jul 21, 2021 |
| ASUSTek       | Z97-AR                      | [900229235e](https://linux-hardware.org/?probe=900229235e) | Jul 21, 2021 |
| ASUSTek       | Z97-AR                      | [c1dcbf95e4](https://linux-hardware.org/?probe=c1dcbf95e4) | Jul 21, 2021 |
| Dell          | 00FKMJ A00                  | [0b4299bc41](https://linux-hardware.org/?probe=0b4299bc41) | Jul 21, 2021 |
| Gigabyte      | Z87M-D3H                    | [85533714a5](https://linux-hardware.org/?probe=85533714a5) | Jul 21, 2021 |
| HP            | 3397                        | [7626063783](https://linux-hardware.org/?probe=7626063783) | Jul 20, 2021 |
| HP            | 3397                        | [38dfe540f7](https://linux-hardware.org/?probe=38dfe540f7) | Jul 20, 2021 |
| Gigabyte      | B250-FinTech-CF             | [58b1c1aecf](https://linux-hardware.org/?probe=58b1c1aecf) | Jul 20, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [8e68827883](https://linux-hardware.org/?probe=8e68827883) | Jul 20, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | [b7a612e4ec](https://linux-hardware.org/?probe=b7a612e4ec) | Jul 20, 2021 |
| PCWare        | IPMH61R1                    | [1212ad03e9](https://linux-hardware.org/?probe=1212ad03e9) | Jul 20, 2021 |
| MSI           | 890GXM-G65                  | [ae86741130](https://linux-hardware.org/?probe=ae86741130) | Jul 19, 2021 |
| ASUSTek       | PRIME A320M-K               | [fb9c551dd7](https://linux-hardware.org/?probe=fb9c551dd7) | Jul 19, 2021 |
| Unknown       | Unknown                     | [5faacb9f0b](https://linux-hardware.org/?probe=5faacb9f0b) | Jul 19, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD           | [0f6b60cc29](https://linux-hardware.org/?probe=0f6b60cc29) | Jul 19, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD           | [704aa27146](https://linux-hardware.org/?probe=704aa27146) | Jul 19, 2021 |
| Dell          | OptiPlex 7020               | [653462ebfc](https://linux-hardware.org/?probe=653462ebfc) | Jul 19, 2021 |
| Dell          | OptiPlex 7020               | [221fc0def9](https://linux-hardware.org/?probe=221fc0def9) | Jul 18, 2021 |
| ASUSTek       | B85M-G                      | [59a5d00285](https://linux-hardware.org/?probe=59a5d00285) | Jul 18, 2021 |
| Biostar       | NF520D3                     | [3c302b5285](https://linux-hardware.org/?probe=3c302b5285) | Jul 18, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [3cc44e771e](https://linux-hardware.org/?probe=3cc44e771e) | Jul 17, 2021 |
| ASRock        | Z77 Extreme3                | [79dd398eff](https://linux-hardware.org/?probe=79dd398eff) | Jul 17, 2021 |
| ASUSTek       | X99-DELUXE II               | [f7c2e4c1ff](https://linux-hardware.org/?probe=f7c2e4c1ff) | Jul 17, 2021 |
| ASUSTek       | X99-DELUXE II               | [279539af23](https://linux-hardware.org/?probe=279539af23) | Jul 17, 2021 |
| MSI           | H81M-P33                    | [4a187b22eb](https://linux-hardware.org/?probe=4a187b22eb) | Jul 16, 2021 |
| MSI           | H110M PRO-VH                | [c91d217ad5](https://linux-hardware.org/?probe=c91d217ad5) | Jul 16, 2021 |
| ASUSTek       | M4A88T-M                    | [8a768d9d2e](https://linux-hardware.org/?probe=8a768d9d2e) | Jul 16, 2021 |
| MSI           | X399 SLI PLUS               | [00b0b9f630](https://linux-hardware.org/?probe=00b0b9f630) | Jul 15, 2021 |
| ASRock        | 970 Extreme3                | [15b36f53b7](https://linux-hardware.org/?probe=15b36f53b7) | Jul 15, 2021 |
| ASUSTek       | M4A785TD-V EVO              | [b833818421](https://linux-hardware.org/?probe=b833818421) | Jul 15, 2021 |
| ASRock        | 970 Extreme3                | [7802550585](https://linux-hardware.org/?probe=7802550585) | Jul 15, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | [d84332d50b](https://linux-hardware.org/?probe=d84332d50b) | Jul 14, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | [f68b508049](https://linux-hardware.org/?probe=f68b508049) | Jul 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2b7c858e62](https://linux-hardware.org/?probe=2b7c858e62) | Jul 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9a7cff028c](https://linux-hardware.org/?probe=9a7cff028c) | Jul 14, 2021 |
| Dell          | 0YXT71 A03                  | [eea8e3b740](https://linux-hardware.org/?probe=eea8e3b740) | Jul 14, 2021 |
| Biostar       | TZ68K+                      | [52ef8197ad](https://linux-hardware.org/?probe=52ef8197ad) | Jul 13, 2021 |
| Dell          | 0YXT71 A03                  | [e363457394](https://linux-hardware.org/?probe=e363457394) | Jul 13, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5b9e8c2d22](https://linux-hardware.org/?probe=5b9e8c2d22) | Jul 13, 2021 |
| Dell          | 0D6H9T A00                  | [a989b9d184](https://linux-hardware.org/?probe=a989b9d184) | Jul 13, 2021 |
| Dell          | 0D6H9T A00                  | [19a34b1a62](https://linux-hardware.org/?probe=19a34b1a62) | Jul 13, 2021 |
| ASUSTek       | P8H61-MX USB3               | [4bf665fc54](https://linux-hardware.org/?probe=4bf665fc54) | Jul 13, 2021 |
| ASRock        | 980DE3/U3S3                 | [f44cd2127b](https://linux-hardware.org/?probe=f44cd2127b) | Jul 12, 2021 |
| MSI           | H61M-E22/W8                 | [6fff913666](https://linux-hardware.org/?probe=6fff913666) | Jul 12, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [fe6c28a62e](https://linux-hardware.org/?probe=fe6c28a62e) | Jul 11, 2021 |
| Gigabyte      | Z77-DS3H                    | [4bb7996ee5](https://linux-hardware.org/?probe=4bb7996ee5) | Jul 11, 2021 |
| Gigabyte      | H61M-USB3H                  | [667aa68843](https://linux-hardware.org/?probe=667aa68843) | Jul 11, 2021 |
| Gigabyte      | B85M-D3H                    | [b551baea7d](https://linux-hardware.org/?probe=b551baea7d) | Jul 11, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [395229874c](https://linux-hardware.org/?probe=395229874c) | Jul 10, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [21129fefc1](https://linux-hardware.org/?probe=21129fefc1) | Jul 10, 2021 |
| Dell          | 0NK5PH A00                  | [f79af9ba9b](https://linux-hardware.org/?probe=f79af9ba9b) | Jul 10, 2021 |
| Pegatron      | Benicia                     | [ad6d42566b](https://linux-hardware.org/?probe=ad6d42566b) | Jul 10, 2021 |
| MSI           | H110M PRO-VH                | [39bbc7b6a9](https://linux-hardware.org/?probe=39bbc7b6a9) | Jul 09, 2021 |
| Gigabyte      | A320M-DS2-CF                | [ec4f4e1d9b](https://linux-hardware.org/?probe=ec4f4e1d9b) | Jul 09, 2021 |
| Dell          | 0200DY A01                  | [28c56ed28e](https://linux-hardware.org/?probe=28c56ed28e) | Jul 09, 2021 |
| Shuttle       | FH61V                       | [57e978bf7e](https://linux-hardware.org/?probe=57e978bf7e) | Jul 09, 2021 |
| ASRock        | B550M-ITX/ac                | [cda1d2d081](https://linux-hardware.org/?probe=cda1d2d081) | Jul 09, 2021 |
| ASRock        | H67M                        | [660e47da08](https://linux-hardware.org/?probe=660e47da08) | Jul 08, 2021 |
| MSI           | H81M-P33                    | [a03d8e33d2](https://linux-hardware.org/?probe=a03d8e33d2) | Jul 08, 2021 |
| Gigabyte      | A320M-S2H-CF                | [65dab5ea20](https://linux-hardware.org/?probe=65dab5ea20) | Jul 08, 2021 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [77513a0fe5](https://linux-hardware.org/?probe=77513a0fe5) | Jul 08, 2021 |
| MSI           | CSM-H81M-P32                | [dcac2bf6e1](https://linux-hardware.org/?probe=dcac2bf6e1) | Jul 08, 2021 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [8beba5ddf7](https://linux-hardware.org/?probe=8beba5ddf7) | Jul 08, 2021 |
| Lenovo        | MAHOBAY NOK                 | [76a98ccf8a](https://linux-hardware.org/?probe=76a98ccf8a) | Jul 08, 2021 |
| ASUSTek       | PRIME A320M-K               | [7ff048cc41](https://linux-hardware.org/?probe=7ff048cc41) | Jul 08, 2021 |
| Lenovo        | MAHOBAY NOK                 | [e1e7fa29fb](https://linux-hardware.org/?probe=e1e7fa29fb) | Jul 08, 2021 |
| Dell          | 0WR7PY A00                  | [174989025c](https://linux-hardware.org/?probe=174989025c) | Jul 07, 2021 |
| ASRock        | 970 Extreme4                | [4c4f65a000](https://linux-hardware.org/?probe=4c4f65a000) | Jul 07, 2021 |
| ASRock        | 970 Extreme4                | [8f33247147](https://linux-hardware.org/?probe=8f33247147) | Jul 07, 2021 |
| MACHINIST     | X99-K9 V2.0                 | [11cb60efc3](https://linux-hardware.org/?probe=11cb60efc3) | Jul 07, 2021 |
| Gigabyte      | Z77-DS3H                    | [d87f176b36](https://linux-hardware.org/?probe=d87f176b36) | Jul 07, 2021 |
| MSI           | B350 TOMAHAWK               | [7b4d2e8580](https://linux-hardware.org/?probe=7b4d2e8580) | Jul 06, 2021 |
| Lenovo        | ThinkStation D10 6493RT8    | [8adc2b3a82](https://linux-hardware.org/?probe=8adc2b3a82) | Jul 06, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [0345fe1b56](https://linux-hardware.org/?probe=0345fe1b56) | Jul 05, 2021 |
| HP            | 83E8                        | [dd469e94e9](https://linux-hardware.org/?probe=dd469e94e9) | Jul 05, 2021 |
| Gigabyte      | H110M-S2V DDR3-CF           | [9eac8917f1](https://linux-hardware.org/?probe=9eac8917f1) | Jul 04, 2021 |
| MSI           | H81M-P33                    | [5a289e338f](https://linux-hardware.org/?probe=5a289e338f) | Jul 04, 2021 |
| MSI           | G41M-P33                    | [8bc3bbf743](https://linux-hardware.org/?probe=8bc3bbf743) | Jul 04, 2021 |
| ASUSTek       | PRIME A320M-K               | [29dc877a37](https://linux-hardware.org/?probe=29dc877a37) | Jul 03, 2021 |
| Gigabyte      | B85M-DS3H-A                 | [6496f18326](https://linux-hardware.org/?probe=6496f18326) | Jul 02, 2021 |
| Biostar       | H61MLV2                     | [45f8d339a6](https://linux-hardware.org/?probe=45f8d339a6) | Jul 02, 2021 |
| ASUSTek       | H81M-C                      | [cdcbc5460d](https://linux-hardware.org/?probe=cdcbc5460d) | Jul 02, 2021 |
| ASUSTek       | H81M-C                      | [c8a5a8c476](https://linux-hardware.org/?probe=c8a5a8c476) | Jul 02, 2021 |
| ASUSTek       | PRIME A320M-K               | [f281017450](https://linux-hardware.org/?probe=f281017450) | Jun 30, 2021 |
| ASUSTek       | PRIME Z590-P                | [5530b28aa3](https://linux-hardware.org/?probe=5530b28aa3) | Jun 30, 2021 |
| ASUSTek       | PRIME Z590-P                | [582e4795cf](https://linux-hardware.org/?probe=582e4795cf) | Jun 30, 2021 |
| MSI           | 890GXM-G65                  | [f4e1c45ed2](https://linux-hardware.org/?probe=f4e1c45ed2) | Jun 30, 2021 |
| Pegatron      | 2AC2                        | [46df29e3a0](https://linux-hardware.org/?probe=46df29e3a0) | Jun 30, 2021 |
| ASUSTek       | PRIME A320M-K               | [39ce85da03](https://linux-hardware.org/?probe=39ce85da03) | Jun 30, 2021 |
| ASUSTek       | N3050I-C                    | [e9cd0640f7](https://linux-hardware.org/?probe=e9cd0640f7) | Jun 30, 2021 |
| MSI           | Z77A-G43                    | [072048636a](https://linux-hardware.org/?probe=072048636a) | Jun 29, 2021 |
| ASUSTek       | PRIME Z390-P                | [e99b341cf4](https://linux-hardware.org/?probe=e99b341cf4) | Jun 29, 2021 |
| ASRock        | B85 Pro4                    | [f9a2e6f60c](https://linux-hardware.org/?probe=f9a2e6f60c) | Jun 29, 2021 |
| Lenovo        | ThinkCentre M57 6062A25     | [e5a404d35c](https://linux-hardware.org/?probe=e5a404d35c) | Jun 29, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [0a190b5aa4](https://linux-hardware.org/?probe=0a190b5aa4) | Jun 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d6fb94e774](https://linux-hardware.org/?probe=d6fb94e774) | Jun 28, 2021 |
| ASRock        | B450 Pro4                   | [42238e9adc](https://linux-hardware.org/?probe=42238e9adc) | Jun 28, 2021 |
| ASRock        | B450 Pro4                   | [e86f5af473](https://linux-hardware.org/?probe=e86f5af473) | Jun 28, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [15884a55b2](https://linux-hardware.org/?probe=15884a55b2) | Jun 27, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [921fcdf0c3](https://linux-hardware.org/?probe=921fcdf0c3) | Jun 27, 2021 |
| Dell          | 05DN3X A00                  | [d0fb4fb2ad](https://linux-hardware.org/?probe=d0fb4fb2ad) | Jun 27, 2021 |
| ASUSTek       | Basswood                    | [daf1b9da91](https://linux-hardware.org/?probe=daf1b9da91) | Jun 27, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [e56a7ee3c9](https://linux-hardware.org/?probe=e56a7ee3c9) | Jun 27, 2021 |
| Pegatron      | 2AB5                        | [8fae33ceb8](https://linux-hardware.org/?probe=8fae33ceb8) | Jun 26, 2021 |
| ASUSTek       | N3050I-C                    | [c42e493962](https://linux-hardware.org/?probe=c42e493962) | Jun 26, 2021 |
| ASRock        | TRX40 Taichi                | [6a2d22eae8](https://linux-hardware.org/?probe=6a2d22eae8) | Jun 26, 2021 |
| ASRock        | TRX40 Taichi                | [5b1b696b98](https://linux-hardware.org/?probe=5b1b696b98) | Jun 26, 2021 |
| ASUSTek       | N3050I-C                    | [9834731c15](https://linux-hardware.org/?probe=9834731c15) | Jun 26, 2021 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [d1e5fbd176](https://linux-hardware.org/?probe=d1e5fbd176) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [048336bb59](https://linux-hardware.org/?probe=048336bb59) | Jun 26, 2021 |
| Dell          | 0FPP7F A00                  | [2e2e4ab599](https://linux-hardware.org/?probe=2e2e4ab599) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [b93fa99bf8](https://linux-hardware.org/?probe=b93fa99bf8) | Jun 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f9070b6d21](https://linux-hardware.org/?probe=f9070b6d21) | Jun 26, 2021 |
| Gigabyte      | Z590I AORUS ULTRA           | [3791b62c7e](https://linux-hardware.org/?probe=3791b62c7e) | Jun 25, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [598db879ae](https://linux-hardware.org/?probe=598db879ae) | Jun 25, 2021 |
| ASUSTek       | F1A55-M LX R2.0             | [dab6b0d848](https://linux-hardware.org/?probe=dab6b0d848) | Jun 25, 2021 |
| Intel         | X79 V2.72B                  | [c78b66e96e](https://linux-hardware.org/?probe=c78b66e96e) | Jun 25, 2021 |
| Gigabyte      | H61M-S2PV                   | [3da8487d5f](https://linux-hardware.org/?probe=3da8487d5f) | Jun 24, 2021 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [180890e9c8](https://linux-hardware.org/?probe=180890e9c8) | Jun 24, 2021 |
| ASUSTek       | P5KPL-AM IN/GB              | [24c93ed20a](https://linux-hardware.org/?probe=24c93ed20a) | Jun 24, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [1905557ab4](https://linux-hardware.org/?probe=1905557ab4) | Jun 24, 2021 |
| Dell          | 08HPGT A01                  | [7be7bba24f](https://linux-hardware.org/?probe=7be7bba24f) | Jun 24, 2021 |
| MSI           | B450M PRO-VDH PLUS          | [39f96730d9](https://linux-hardware.org/?probe=39f96730d9) | Jun 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [e24031d13d](https://linux-hardware.org/?probe=e24031d13d) | Jun 23, 2021 |
| MSI           | Z270I CORSAIR ONE           | [0609479af2](https://linux-hardware.org/?probe=0609479af2) | Jun 23, 2021 |
| MSI           | Z270I CORSAIR ONE           | [bbbed29691](https://linux-hardware.org/?probe=bbbed29691) | Jun 23, 2021 |
| MSI           | H510I PRO WIFI              | [06e8d9bce7](https://linux-hardware.org/?probe=06e8d9bce7) | Jun 23, 2021 |
| ASRock        | B550M Steel Legend          | [c13a83286a](https://linux-hardware.org/?probe=c13a83286a) | Jun 23, 2021 |
| OEM           | B250B                       | [76ea6ec5b6](https://linux-hardware.org/?probe=76ea6ec5b6) | Jun 22, 2021 |
| Packard Be... | MCP73                       | [949909da41](https://linux-hardware.org/?probe=949909da41) | Jun 22, 2021 |
| ASRock        | 970 Pro3 R2.0               | [8ed5dab80e](https://linux-hardware.org/?probe=8ed5dab80e) | Jun 22, 2021 |
| TYAN Compu... | Toledo i3210W/i3200R S52... | [cfacd9e7ce](https://linux-hardware.org/?probe=cfacd9e7ce) | Jun 21, 2021 |
| OEM           | B250B                       | [cadd03edf3](https://linux-hardware.org/?probe=cadd03edf3) | Jun 21, 2021 |
| Gigabyte      | H510M S2H                   | [c40ed6f57e](https://linux-hardware.org/?probe=c40ed6f57e) | Jun 21, 2021 |
| Gigabyte      | H510M S2H                   | [6c5f517ffe](https://linux-hardware.org/?probe=6c5f517ffe) | Jun 21, 2021 |
| Packard Be... | MCP73                       | [e1eb07cc34](https://linux-hardware.org/?probe=e1eb07cc34) | Jun 21, 2021 |
| ASUSTek       | P5KPL-AM IN/GB              | [b23297702d](https://linux-hardware.org/?probe=b23297702d) | Jun 21, 2021 |
| ASUSTek       | PRIME Z270-A                | [5fa67b7e7e](https://linux-hardware.org/?probe=5fa67b7e7e) | Jun 21, 2021 |
| Dell          | 0GDG8Y A00                  | [5573a86f4c](https://linux-hardware.org/?probe=5573a86f4c) | Jun 21, 2021 |
| ASUSTek       | Z97-P                       | [3e013acd03](https://linux-hardware.org/?probe=3e013acd03) | Jun 21, 2021 |
| Pegatron      | Benicia                     | [40526a2b4c](https://linux-hardware.org/?probe=40526a2b4c) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [14083d2e96](https://linux-hardware.org/?probe=14083d2e96) | Jun 20, 2021 |
| Biostar       | TB250-BTC                   | [135a42fc66](https://linux-hardware.org/?probe=135a42fc66) | Jun 19, 2021 |
| Biostar       | TB250-BTC                   | [acdf9bed0d](https://linux-hardware.org/?probe=acdf9bed0d) | Jun 19, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [c13134fc57](https://linux-hardware.org/?probe=c13134fc57) | Jun 19, 2021 |
| ASUSTek       | H81M-C                      | [8337e476da](https://linux-hardware.org/?probe=8337e476da) | Jun 19, 2021 |
| ASRock        | B85M Pro4                   | [3400ad3eb1](https://linux-hardware.org/?probe=3400ad3eb1) | Jun 19, 2021 |
| MSI           | Z77A-G43 GAMING             | [e5da744b7b](https://linux-hardware.org/?probe=e5da744b7b) | Jun 19, 2021 |
| ASRock        | B85M Pro4                   | [f1e7b8a65b](https://linux-hardware.org/?probe=f1e7b8a65b) | Jun 18, 2021 |
| MSI           | H510I PRO WIFI              | [b2c184af4f](https://linux-hardware.org/?probe=b2c184af4f) | Jun 18, 2021 |
| ASUSTek       | H81M-C                      | [c843908a01](https://linux-hardware.org/?probe=c843908a01) | Jun 18, 2021 |
| MSI           | MEG Z490 UNIFY              | [542e64b8b1](https://linux-hardware.org/?probe=542e64b8b1) | Jun 17, 2021 |
| ASUSTek       | H81M-C                      | [39e707392d](https://linux-hardware.org/?probe=39e707392d) | Jun 17, 2021 |
| ASUSTek       | P8H61-MX USB3               | [1b6fedfa86](https://linux-hardware.org/?probe=1b6fedfa86) | Jun 16, 2021 |
| Gigabyte      | B450 AORUS M                | [061955c2a0](https://linux-hardware.org/?probe=061955c2a0) | Jun 16, 2021 |
| ASUSTek       | M2N68-AM                    | [21b5888299](https://linux-hardware.org/?probe=21b5888299) | Jun 16, 2021 |
| MSI           | B250I PRO                   | [02087ebc8a](https://linux-hardware.org/?probe=02087ebc8a) | Jun 15, 2021 |
| MSI           | B250I PRO                   | [05b0b94ace](https://linux-hardware.org/?probe=05b0b94ace) | Jun 15, 2021 |
| ASRock        | N68C-S UCC                  | [e62dd54d79](https://linux-hardware.org/?probe=e62dd54d79) | Jun 15, 2021 |
| MSI           | B75MA-P45                   | [0ccd0cdf44](https://linux-hardware.org/?probe=0ccd0cdf44) | Jun 15, 2021 |
| Gigabyte      | 990FXA-UD3                  | [3d0e9bc4aa](https://linux-hardware.org/?probe=3d0e9bc4aa) | Jun 14, 2021 |
| HC            | HCAR357-MI V1.0             | [6757c0e254](https://linux-hardware.org/?probe=6757c0e254) | Jun 14, 2021 |
| ASRock        | B560M-ITX/ac                | [2284cea3c5](https://linux-hardware.org/?probe=2284cea3c5) | Jun 14, 2021 |
| ASUSTek       | PRIME Z590-A                | [ad883d60a1](https://linux-hardware.org/?probe=ad883d60a1) | Jun 14, 2021 |
| Gigabyte      | B360M HD3                   | [666afe018d](https://linux-hardware.org/?probe=666afe018d) | Jun 14, 2021 |
| ASRock        | 970M Pro3                   | [c75be35c68](https://linux-hardware.org/?probe=c75be35c68) | Jun 14, 2021 |
| ASUSTek       | PRIME Z370-P                | [8ec235f1f1](https://linux-hardware.org/?probe=8ec235f1f1) | Jun 13, 2021 |
| ASUSTek       | P5WD2-Premium               | [35c95bde23](https://linux-hardware.org/?probe=35c95bde23) | Jun 13, 2021 |
| ASUSTek       | H97M-E                      | [0bc409e14c](https://linux-hardware.org/?probe=0bc409e14c) | Jun 13, 2021 |
| MSI           | 970A-G46                    | [f7b1001ef1](https://linux-hardware.org/?probe=f7b1001ef1) | Jun 13, 2021 |
| Gigabyte      | Z77-DS3H                    | [981954c88b](https://linux-hardware.org/?probe=981954c88b) | Jun 13, 2021 |
| ASUSTek       | M2A-VM                      | [e4fdaff878](https://linux-hardware.org/?probe=e4fdaff878) | Jun 12, 2021 |
| Gigabyte      | X99M-Gaming 5               | [10d40dc417](https://linux-hardware.org/?probe=10d40dc417) | Jun 12, 2021 |
| Gigabyte      | Z590 VISION G               | [c3b20ee137](https://linux-hardware.org/?probe=c3b20ee137) | Jun 12, 2021 |
| ASUSTek       | PRIME X399-A                | [bfb3ab2f44](https://linux-hardware.org/?probe=bfb3ab2f44) | Jun 11, 2021 |
| Gigabyte      | G41MT-USB3                  | [df62a2a7e0](https://linux-hardware.org/?probe=df62a2a7e0) | Jun 11, 2021 |
| ASRock        | 970M Pro3                   | [76a7098ea9](https://linux-hardware.org/?probe=76a7098ea9) | Jun 11, 2021 |
| ASRock        | 970M Pro3                   | [f5ba57634a](https://linux-hardware.org/?probe=f5ba57634a) | Jun 11, 2021 |
| HP            | 0B4Ch D                     | [5ac932248a](https://linux-hardware.org/?probe=5ac932248a) | Jun 10, 2021 |
| HP            | 158A                        | [1da50908cf](https://linux-hardware.org/?probe=1da50908cf) | Jun 10, 2021 |
| MSI           | MPG Z590 GAMING EDGE WIF... | [bab34a6951](https://linux-hardware.org/?probe=bab34a6951) | Jun 10, 2021 |
| HP            | 843B                        | [95015678e1](https://linux-hardware.org/?probe=95015678e1) | Jun 09, 2021 |
| ASUSTek       | G11DF                       | [86408c43ff](https://linux-hardware.org/?probe=86408c43ff) | Jun 09, 2021 |
| Gigabyte      | F2A88XM-DS2                 | [e8ea861c92](https://linux-hardware.org/?probe=e8ea861c92) | Jun 09, 2021 |
| Gigabyte      | GA-870A-UD3                 | [89462c851a](https://linux-hardware.org/?probe=89462c851a) | Jun 08, 2021 |
| Gigabyte      | P43T-ES3G                   | [ab6924723a](https://linux-hardware.org/?probe=ab6924723a) | Jun 08, 2021 |
| Acer          | EG43M                       | [4300da7d4b](https://linux-hardware.org/?probe=4300da7d4b) | Jun 08, 2021 |
| Acer          | EG43M                       | [c160d8848f](https://linux-hardware.org/?probe=c160d8848f) | Jun 08, 2021 |
| ASUSTek       | P8H61-MX USB3               | [cf5748e282](https://linux-hardware.org/?probe=cf5748e282) | Jun 07, 2021 |
| HP            | 0AA0h                       | [1231618175](https://linux-hardware.org/?probe=1231618175) | Jun 07, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [6f5aed374a](https://linux-hardware.org/?probe=6f5aed374a) | Jun 06, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [1fe01a8a37](https://linux-hardware.org/?probe=1fe01a8a37) | Jun 05, 2021 |
| Gigabyte      | Z77X-D3H                    | [0f9baa3f5f](https://linux-hardware.org/?probe=0f9baa3f5f) | Jun 05, 2021 |
| ASUSTek       | P5WD2-Premium               | [3bf03e7263](https://linux-hardware.org/?probe=3bf03e7263) | Jun 05, 2021 |
| HP            | 1998                        | [68978259f3](https://linux-hardware.org/?probe=68978259f3) | Jun 05, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [f55a54325f](https://linux-hardware.org/?probe=f55a54325f) | Jun 05, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [24a4df74e1](https://linux-hardware.org/?probe=24a4df74e1) | Jun 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [e7e821c4a7](https://linux-hardware.org/?probe=e7e821c4a7) | Jun 04, 2021 |
| HP            | 0AA0h                       | [ff231665d3](https://linux-hardware.org/?probe=ff231665d3) | Jun 04, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [62a56ec749](https://linux-hardware.org/?probe=62a56ec749) | Jun 04, 2021 |
| Medion        | MS-7621                     | [29ecaf9382](https://linux-hardware.org/?probe=29ecaf9382) | Jun 04, 2021 |
| MSI           | MS-7125                     | [66e6adf1ec](https://linux-hardware.org/?probe=66e6adf1ec) | Jun 04, 2021 |
| HP            | 1998                        | [617a033a6e](https://linux-hardware.org/?probe=617a033a6e) | Jun 04, 2021 |
| ASUSTek       | PRIME Z390-P                | [c0e0de26cb](https://linux-hardware.org/?probe=c0e0de26cb) | Jun 04, 2021 |
| ASUSTek       | TUF H370-PRO GAMING         | [8f75ede232](https://linux-hardware.org/?probe=8f75ede232) | Jun 04, 2021 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [0126e8d357](https://linux-hardware.org/?probe=0126e8d357) | Jun 04, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [9237a7a68b](https://linux-hardware.org/?probe=9237a7a68b) | Jun 03, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [6a9e537939](https://linux-hardware.org/?probe=6a9e537939) | Jun 03, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [adeee24676](https://linux-hardware.org/?probe=adeee24676) | Jun 03, 2021 |
| Gigabyte      | B360HD3PLM-CF               | [a434845c16](https://linux-hardware.org/?probe=a434845c16) | Jun 03, 2021 |
| HP            | 3397                        | [73e07145f4](https://linux-hardware.org/?probe=73e07145f4) | Jun 03, 2021 |
| ASUSTek       | M2N                         | [f5537f32f6](https://linux-hardware.org/?probe=f5537f32f6) | Jun 02, 2021 |
| HP            | 3397                        | [1eba8aa1c1](https://linux-hardware.org/?probe=1eba8aa1c1) | Jun 02, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [40545ef53f](https://linux-hardware.org/?probe=40545ef53f) | Jun 02, 2021 |
| ASUSTek       | PRIME Z370-A II             | [5cbd925314](https://linux-hardware.org/?probe=5cbd925314) | Jun 02, 2021 |
| Gigabyte      | F2A55M-HD2                  | [8daf7e0679](https://linux-hardware.org/?probe=8daf7e0679) | Jun 02, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [c31c1c69c6](https://linux-hardware.org/?probe=c31c1c69c6) | Jun 02, 2021 |
| ASUSTek       | PRIME Z390-P                | [75cd860063](https://linux-hardware.org/?probe=75cd860063) | Jun 01, 2021 |
| Fujitsu Si... | MS-7379VP                   | [e417b5e11e](https://linux-hardware.org/?probe=e417b5e11e) | Jun 01, 2021 |
| Fujitsu Si... | MS-7379VP                   | [ea4e7fc19e](https://linux-hardware.org/?probe=ea4e7fc19e) | Jun 01, 2021 |
| Acer          | Aspire XC-230               | [4594f040e1](https://linux-hardware.org/?probe=4594f040e1) | May 31, 2021 |
| Gigabyte      | Z590 VISION G               | [ea4492aeee](https://linux-hardware.org/?probe=ea4492aeee) | May 30, 2021 |
| Gigabyte      | F2A55M-HD2                  | [6dde896b4f](https://linux-hardware.org/?probe=6dde896b4f) | May 30, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [36ebf65d44](https://linux-hardware.org/?probe=36ebf65d44) | May 30, 2021 |
| Gigabyte      | 990FXA-UD3                  | [44a0f0e4e2](https://linux-hardware.org/?probe=44a0f0e4e2) | May 30, 2021 |
| MSI           | B350 PC MATE                | [d640900b8a](https://linux-hardware.org/?probe=d640900b8a) | May 29, 2021 |
| MSI           | B350 PC MATE                | [f7942b9c3e](https://linux-hardware.org/?probe=f7942b9c3e) | May 29, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [8fd027f078](https://linux-hardware.org/?probe=8fd027f078) | May 29, 2021 |
| Foxconn       | 2ADA                        | [6e2fc02f05](https://linux-hardware.org/?probe=6e2fc02f05) | May 29, 2021 |
| ASUSTek       | M5A97 R2.0                  | [dfa6b5b067](https://linux-hardware.org/?probe=dfa6b5b067) | May 28, 2021 |
| MSI           | Z490-A PRO                  | [654c105561](https://linux-hardware.org/?probe=654c105561) | May 28, 2021 |
| MSI           | 970A-G43                    | [07a86d218e](https://linux-hardware.org/?probe=07a86d218e) | May 27, 2021 |
| ASRock        | H77 Pro4-M                  | [f0450b570d](https://linux-hardware.org/?probe=f0450b570d) | May 27, 2021 |
| HP            | 81B4                        | [41311d3164](https://linux-hardware.org/?probe=41311d3164) | May 27, 2021 |
| Biostar       | A320MD PRO                  | [02e5d996c8](https://linux-hardware.org/?probe=02e5d996c8) | May 27, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [abd5d85c0e](https://linux-hardware.org/?probe=abd5d85c0e) | May 27, 2021 |
| ASUSTek       | PRIME Z390-P                | [9f58a0f0bf](https://linux-hardware.org/?probe=9f58a0f0bf) | May 26, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [3b8ddca28e](https://linux-hardware.org/?probe=3b8ddca28e) | May 26, 2021 |
| MSI           | FM2-A85XMA-P33              | [0a01344d75](https://linux-hardware.org/?probe=0a01344d75) | May 26, 2021 |
| MSI           | ZH77A-G41                   | [8755040ea2](https://linux-hardware.org/?probe=8755040ea2) | May 25, 2021 |
| MSI           | FM2-A85XMA-P33              | [0fabdb3aad](https://linux-hardware.org/?probe=0fabdb3aad) | May 25, 2021 |
| MSI           | FM2-A85XMA-P33              | [40de3f5310](https://linux-hardware.org/?probe=40de3f5310) | May 25, 2021 |
| ASUSTek       | PRIME B250M-A               | [2961088957](https://linux-hardware.org/?probe=2961088957) | May 24, 2021 |
| Soyo          | SY-I5GC2-L                  | [02a90f300e](https://linux-hardware.org/?probe=02a90f300e) | May 24, 2021 |
| Soyo          | SY-I5GC2-L                  | [91bdc4a9a0](https://linux-hardware.org/?probe=91bdc4a9a0) | May 24, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [86060380c8](https://linux-hardware.org/?probe=86060380c8) | May 23, 2021 |
| ASRock        | G41M-S3                     | [33ba80d2ae](https://linux-hardware.org/?probe=33ba80d2ae) | May 23, 2021 |
| ASRock        | B450 Pro4                   | [5be7a59bcd](https://linux-hardware.org/?probe=5be7a59bcd) | May 23, 2021 |
| Gigabyte      | F2A78M-DS2                  | [da126fa410](https://linux-hardware.org/?probe=da126fa410) | May 23, 2021 |
| ASUSTek       | ET2700I                     | [a3edd93ada](https://linux-hardware.org/?probe=a3edd93ada) | May 23, 2021 |
| Dell          | 0RK936                      | [27b342b50b](https://linux-hardware.org/?probe=27b342b50b) | May 22, 2021 |
| Dell          | 0RK936                      | [6c12a5edf2](https://linux-hardware.org/?probe=6c12a5edf2) | May 22, 2021 |
| ASRock        | X370 Gaming K4              | [4945bb80f6](https://linux-hardware.org/?probe=4945bb80f6) | May 22, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [c458b6d1ca](https://linux-hardware.org/?probe=c458b6d1ca) | May 21, 2021 |
| ASUSTek       | H81M-PLUS                   | [0e3415879f](https://linux-hardware.org/?probe=0e3415879f) | May 21, 2021 |
| MSI           | 970 GAMING                  | [eb4531374e](https://linux-hardware.org/?probe=eb4531374e) | May 21, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [60450a65b2](https://linux-hardware.org/?probe=60450a65b2) | May 20, 2021 |
| Acer          | Aspire XC-230               | [31e0dabfb9](https://linux-hardware.org/?probe=31e0dabfb9) | May 20, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [a42bee6110](https://linux-hardware.org/?probe=a42bee6110) | May 19, 2021 |
| HP            | 802F                        | [f01cdeed88](https://linux-hardware.org/?probe=f01cdeed88) | May 19, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [a1b3c9d405](https://linux-hardware.org/?probe=a1b3c9d405) | May 19, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [3814598db5](https://linux-hardware.org/?probe=3814598db5) | May 19, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | [0548f9650b](https://linux-hardware.org/?probe=0548f9650b) | May 18, 2021 |
| ASUSTek       | H81M-K                      | [d44e900d30](https://linux-hardware.org/?probe=d44e900d30) | May 18, 2021 |
| Dell          | 0RK936                      | [c3c620590f](https://linux-hardware.org/?probe=c3c620590f) | May 18, 2021 |
| ASRock        | B550 Extreme4               | [38fe00e843](https://linux-hardware.org/?probe=38fe00e843) | May 18, 2021 |
| ASUSTek       | PRIME B250M-A               | [b646c2612a](https://linux-hardware.org/?probe=b646c2612a) | May 18, 2021 |
| ASRock        | Z97E-ITX/ac                 | [b6812b6242](https://linux-hardware.org/?probe=b6812b6242) | May 17, 2021 |
| Dell          | 0VHRW1 A03                  | [1ac850d5b7](https://linux-hardware.org/?probe=1ac850d5b7) | May 17, 2021 |
| MSI           | G41M-P25                    | [57d1c4dafa](https://linux-hardware.org/?probe=57d1c4dafa) | May 16, 2021 |
| Dell          | 0Y5DDC A00                  | [7694ca4dfd](https://linux-hardware.org/?probe=7694ca4dfd) | May 16, 2021 |
| Dell          | 051FJ8 A02                  | [dd8dc2d85a](https://linux-hardware.org/?probe=dd8dc2d85a) | May 16, 2021 |
| ASUSTek       | PRIME Z390-P                | [00a90e02e9](https://linux-hardware.org/?probe=00a90e02e9) | May 15, 2021 |
| Pegatron      | 2AB5                        | [ef62ad9c4b](https://linux-hardware.org/?probe=ef62ad9c4b) | May 15, 2021 |
| Apple         | Mac-F221BEC8                | [637ea140ae](https://linux-hardware.org/?probe=637ea140ae) | May 15, 2021 |
| Apple         | Mac-F221BEC8                | [0d737eab8c](https://linux-hardware.org/?probe=0d737eab8c) | May 15, 2021 |
| Medion        | MS-7621                     | [9d7d398cc1](https://linux-hardware.org/?probe=9d7d398cc1) | May 15, 2021 |
| MSI           | 970 GAMING                  | [bc393b7046](https://linux-hardware.org/?probe=bc393b7046) | May 15, 2021 |
| Gigabyte      | B460M AORUS PRO             | [ef3422dd2d](https://linux-hardware.org/?probe=ef3422dd2d) | May 14, 2021 |
| Unknown       | Unknown                     | [2c887c5d3f](https://linux-hardware.org/?probe=2c887c5d3f) | May 14, 2021 |
| Unknown       | Unknown                     | [aca4c8c6cf](https://linux-hardware.org/?probe=aca4c8c6cf) | May 14, 2021 |
| HC            | HCAR357-MI V1.0             | [b3d306266e](https://linux-hardware.org/?probe=b3d306266e) | May 14, 2021 |
| HC            | HCAR357-MI V1.0             | [5310f8c130](https://linux-hardware.org/?probe=5310f8c130) | May 14, 2021 |
| Gigabyte      | F2A55M-HD2                  | [b39ddf3718](https://linux-hardware.org/?probe=b39ddf3718) | May 14, 2021 |
| ASUSTek       | PRIME B560-PLUS             | [a44fcb1c39](https://linux-hardware.org/?probe=a44fcb1c39) | May 13, 2021 |
| ASUSTek       | PRIME X299-A                | [d5cdc97c3b](https://linux-hardware.org/?probe=d5cdc97c3b) | May 13, 2021 |
| Medion        | E631X Ver                   | [872b2a2dc9](https://linux-hardware.org/?probe=872b2a2dc9) | May 13, 2021 |
| ASUSTek       | PRIME B560-PLUS             | [2efd6e26e3](https://linux-hardware.org/?probe=2efd6e26e3) | May 12, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [cf41b106cb](https://linux-hardware.org/?probe=cf41b106cb) | May 11, 2021 |
| Acer          | Aspire XC-230               | [73c9019a57](https://linux-hardware.org/?probe=73c9019a57) | May 10, 2021 |
| ASUSTek       | M2A-VM                      | [425df4a110](https://linux-hardware.org/?probe=425df4a110) | May 09, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [511e08ef09](https://linux-hardware.org/?probe=511e08ef09) | May 09, 2021 |
| Dell          | 0YXT71 A00                  | [0b1b291060](https://linux-hardware.org/?probe=0b1b291060) | May 09, 2021 |
| MSI           | H61M-P20/W8                 | [ca302c374f](https://linux-hardware.org/?probe=ca302c374f) | May 08, 2021 |
| MSI           | H61M-P20/W8                 | [e68f90acd5](https://linux-hardware.org/?probe=e68f90acd5) | May 08, 2021 |
| HP            | 09F8h                       | [88de1576e5](https://linux-hardware.org/?probe=88de1576e5) | May 08, 2021 |
| ASUSTek       | PRIME A320M-K               | [85058201a1](https://linux-hardware.org/?probe=85058201a1) | May 08, 2021 |
| Acer          | Veriton X490G               | [a729505133](https://linux-hardware.org/?probe=a729505133) | May 08, 2021 |
| ASRock        | X99 Extreme4                | [22b924723a](https://linux-hardware.org/?probe=22b924723a) | May 08, 2021 |
| Gigabyte      | B560M DS3H AC               | [7d79c9afb9](https://linux-hardware.org/?probe=7d79c9afb9) | May 08, 2021 |
| ASUSTek       | PRIME B460M-A               | [a65a4354b9](https://linux-hardware.org/?probe=a65a4354b9) | May 07, 2021 |
| HP            | 09F8h                       | [9d6ad317f4](https://linux-hardware.org/?probe=9d6ad317f4) | May 07, 2021 |
| MSI           | H410M PRO                   | [68104520c5](https://linux-hardware.org/?probe=68104520c5) | May 06, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [8219a4a9ac](https://linux-hardware.org/?probe=8219a4a9ac) | May 06, 2021 |
| MSI           | H270M BAZOOKA               | [c2fdd4a7da](https://linux-hardware.org/?probe=c2fdd4a7da) | May 06, 2021 |
| Gigabyte      | B75M-HD3                    | [cff51c85da](https://linux-hardware.org/?probe=cff51c85da) | May 06, 2021 |
| Gigabyte      | 970A-DS3P                   | [25ad87e22b](https://linux-hardware.org/?probe=25ad87e22b) | May 05, 2021 |
| Gigabyte      | Z390 UD                     | [bbc8131c67](https://linux-hardware.org/?probe=bbc8131c67) | May 05, 2021 |
| Gigabyte      | A320M-S2H-CF                | [dc28c67e94](https://linux-hardware.org/?probe=dc28c67e94) | May 05, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | [48d1110975](https://linux-hardware.org/?probe=48d1110975) | May 05, 2021 |
| MSI           | MAG B460M MORTAR            | [9b72abe5d8](https://linux-hardware.org/?probe=9b72abe5d8) | May 05, 2021 |
| MSI           | B450 GAMING PLUS            | [45f40c1d2b](https://linux-hardware.org/?probe=45f40c1d2b) | May 04, 2021 |
| HP            | 3647h                       | [bd39210291](https://linux-hardware.org/?probe=bd39210291) | May 04, 2021 |
| ASUSTek       | Rampage III Extreme         | [f42aef173c](https://linux-hardware.org/?probe=f42aef173c) | May 04, 2021 |
| ASUSTek       | Rampage III Extreme         | [8b524de561](https://linux-hardware.org/?probe=8b524de561) | May 04, 2021 |
| ASUSTek       | PRIME A320M-K               | [6fbe833fac](https://linux-hardware.org/?probe=6fbe833fac) | May 02, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [aebf5d33a4](https://linux-hardware.org/?probe=aebf5d33a4) | May 02, 2021 |
| SYWZ          | S210H Series                | [746808e2c5](https://linux-hardware.org/?probe=746808e2c5) | May 01, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [315bc839ec](https://linux-hardware.org/?probe=315bc839ec) | May 01, 2021 |
| ASUSTek       | PRIME Z490-A                | [af5179a1f9](https://linux-hardware.org/?probe=af5179a1f9) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | [1a9b2e458a](https://linux-hardware.org/?probe=1a9b2e458a) | Apr 30, 2021 |
| Dell          | 0Y5DDC A00                  | [29206c06a9](https://linux-hardware.org/?probe=29206c06a9) | Apr 30, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [c3243b55ef](https://linux-hardware.org/?probe=c3243b55ef) | Apr 29, 2021 |
| Alienware     | 0TYR0X A00                  | [9f3fe00e5c](https://linux-hardware.org/?probe=9f3fe00e5c) | Apr 29, 2021 |
| Alienware     | 0TYR0X A00                  | [41fd34d001](https://linux-hardware.org/?probe=41fd34d001) | Apr 29, 2021 |
| ASUSTek       | P5Q DELUXE                  | [34b91a88a8](https://linux-hardware.org/?probe=34b91a88a8) | Apr 28, 2021 |
| Gigabyte      | H61M-S2PV                   | [325c441d47](https://linux-hardware.org/?probe=325c441d47) | Apr 27, 2021 |
| ASRock        | G41M-S3                     | [1fe4e3b8f2](https://linux-hardware.org/?probe=1fe4e3b8f2) | Apr 27, 2021 |
| Lenovo        | MAHOBAY NOK                 | [5a9b9278df](https://linux-hardware.org/?probe=5a9b9278df) | Apr 26, 2021 |
| MSI           | B350 PC MATE                | [5ae67a0ac5](https://linux-hardware.org/?probe=5ae67a0ac5) | Apr 26, 2021 |
| ASUSTek       | M4N78 SE                    | [b4d731ce7b](https://linux-hardware.org/?probe=b4d731ce7b) | Apr 26, 2021 |
| ASUSTek       | M4N78 SE                    | [7a99053f1f](https://linux-hardware.org/?probe=7a99053f1f) | Apr 26, 2021 |
| Biostar       | A880GU3                     | [7c3cadb886](https://linux-hardware.org/?probe=7c3cadb886) | Apr 26, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [c1b51f4738](https://linux-hardware.org/?probe=c1b51f4738) | Apr 25, 2021 |
| MSI           | Z77A-GD55                   | [4ae20b53ca](https://linux-hardware.org/?probe=4ae20b53ca) | Apr 25, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [6dc9bcb3f7](https://linux-hardware.org/?probe=6dc9bcb3f7) | Apr 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [80224285b6](https://linux-hardware.org/?probe=80224285b6) | Apr 24, 2021 |
| Gigabyte      | B550 AORUS PRO              | [15f9ee179c](https://linux-hardware.org/?probe=15f9ee179c) | Apr 24, 2021 |
| ASUSTek       | VC66                        | [6158b04856](https://linux-hardware.org/?probe=6158b04856) | Apr 24, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [a63e8e0aeb](https://linux-hardware.org/?probe=a63e8e0aeb) | Apr 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | [3423651b5d](https://linux-hardware.org/?probe=3423651b5d) | Apr 23, 2021 |
| ASUSTek       | PRIME H270-PRO              | [163211473a](https://linux-hardware.org/?probe=163211473a) | Apr 23, 2021 |
| ASUSTek       | A68HM-K                     | [06b060c49c](https://linux-hardware.org/?probe=06b060c49c) | Apr 23, 2021 |
| Gigabyte      | H81M-S2V                    | [6dba735784](https://linux-hardware.org/?probe=6dba735784) | Apr 20, 2021 |
| Gigabyte      | B560M DS3H AC               | [9622491640](https://linux-hardware.org/?probe=9622491640) | Apr 19, 2021 |
| ASUSTek       | PRIME H410M-A               | [1a10915a97](https://linux-hardware.org/?probe=1a10915a97) | Apr 17, 2021 |
| Gigabyte      | H81M-S2V                    | [8e9d22ed4d](https://linux-hardware.org/?probe=8e9d22ed4d) | Apr 15, 2021 |
| ASRock        | X570 PG Velocita            | [20e91a55f2](https://linux-hardware.org/?probe=20e91a55f2) | Apr 15, 2021 |
| ASRock        | H570 Phantom Gaming 4       | [e89bff9fa4](https://linux-hardware.org/?probe=e89bff9fa4) | Apr 14, 2021 |
| Dell          | 0VD5HY A07                  | [28dda9b894](https://linux-hardware.org/?probe=28dda9b894) | Apr 12, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | [3a69abb947](https://linux-hardware.org/?probe=3a69abb947) | Apr 05, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | [63996f0452](https://linux-hardware.org/?probe=63996f0452) | Apr 04, 2021 |
| MSI           | MS-B9181                    | [7c467c7f2b](https://linux-hardware.org/?probe=7c467c7f2b) | Apr 02, 2021 |
| MSI           | MS-B9181                    | [5ed3225348](https://linux-hardware.org/?probe=5ed3225348) | Apr 02, 2021 |
| ASUSTek       | P5Q DELUXE                  | [2d30481374](https://linux-hardware.org/?probe=2d30481374) | Apr 01, 2021 |
| MSI           | MS-1672 Ver                 | [c630018fea](https://linux-hardware.org/?probe=c630018fea) | Mar 31, 2021 |
| MSI           | MS-1672 Ver                 | [d72651aaf4](https://linux-hardware.org/?probe=d72651aaf4) | Mar 31, 2021 |
| AAEON         | UP-APL01 V0.4               | [9a724f738f](https://linux-hardware.org/?probe=9a724f738f) | Mar 26, 2021 |
| HP            | 3646h                       | [f870632953](https://linux-hardware.org/?probe=f870632953) | Mar 26, 2021 |
| Pegatron      | VIOLET                      | [97b60b69c9](https://linux-hardware.org/?probe=97b60b69c9) | Mar 19, 2021 |
| Biostar       | A320MD PRO                  | [cc647d652a](https://linux-hardware.org/?probe=cc647d652a) | Mar 16, 2021 |
| ASUSTek       | PRIME X470-PRO              | [ee9f48a9d0](https://linux-hardware.org/?probe=ee9f48a9d0) | Mar 06, 2021 |
| ASRockRack    | X570D4U                     | [046e21b599](https://linux-hardware.org/?probe=046e21b599) | Mar 04, 2021 |
| ASRockRack    | X570D4U                     | [250918faa7](https://linux-hardware.org/?probe=250918faa7) | Mar 03, 2021 |
| ASRock        | FM2A75M-DGS                 | [72c1ab0b9b](https://linux-hardware.org/?probe=72c1ab0b9b) | Mar 01, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [237d8d39fb](https://linux-hardware.org/?probe=237d8d39fb) | Feb 27, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ec5eb37f90](https://linux-hardware.org/?probe=ec5eb37f90) | Feb 25, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [3555575966](https://linux-hardware.org/?probe=3555575966) | Feb 21, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [190805f976](https://linux-hardware.org/?probe=190805f976) | Feb 21, 2021 |
| Gigabyte      | AB350M-D3V-CF               | [38a9e8bdd4](https://linux-hardware.org/?probe=38a9e8bdd4) | Feb 05, 2021 |
| HUAWEI        | SP1PGUM M1020               | [bd05c84564](https://linux-hardware.org/?probe=bd05c84564) | Feb 04, 2021 |
| Gigabyte      | H61M-S2-B3                  | [449cccd96f](https://linux-hardware.org/?probe=449cccd96f) | Feb 04, 2021 |
| HP            | 3032h                       | [89ff3e8a36](https://linux-hardware.org/?probe=89ff3e8a36) | Jan 25, 2021 |
| ASRock        | B75M-GL R2.0                | [79848dc213](https://linux-hardware.org/?probe=79848dc213) | Jan 17, 2021 |
| MSI           | MEG Z390 GODLIKE            | [319ddce23d](https://linux-hardware.org/?probe=319ddce23d) | Jan 11, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [e081c11999](https://linux-hardware.org/?probe=e081c11999) | Jan 11, 2021 |
| MSI           | AMETHYST-M                  | [b242ecc226](https://linux-hardware.org/?probe=b242ecc226) | Jan 11, 2021 |
| MSI           | MEG Z390 GODLIKE            | [f5c9028c6a](https://linux-hardware.org/?probe=f5c9028c6a) | Dec 21, 2020 |
| ASRock        | B75M-GL R2.0                | [91c33b15fe](https://linux-hardware.org/?probe=91c33b15fe) | Dec 18, 2020 |
| HP            | 3032h                       | [aca3ed50ac](https://linux-hardware.org/?probe=aca3ed50ac) | Dec 07, 2020 |
| HP            | 3032h                       | [b061d52e66](https://linux-hardware.org/?probe=b061d52e66) | Dec 07, 2020 |
| MSI           | MEG Z390 GODLIKE            | [bb2f68b014](https://linux-hardware.org/?probe=bb2f68b014) | Nov 27, 2020 |
| MSI           | MEG Z390 GODLIKE            | [5c18dade22](https://linux-hardware.org/?probe=5c18dade22) | Nov 27, 2020 |
| Gigabyte      | Z97X-Gaming 5               | [bcc73e0b8d](https://linux-hardware.org/?probe=bcc73e0b8d) | Nov 25, 2020 |
| Colorful T... | C.H110M-K PRO V21           | [c8211ace73](https://linux-hardware.org/?probe=c8211ace73) | Nov 20, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_21.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.11.0-25-generic     | 78       | 11.45%  |
| 5.11.0-22-generic     | 75       | 11.01%  |
| 5.11.0-16-generic     | 74       | 10.87%  |
| 5.11.0-18-generic     | 69       | 10.13%  |
| 5.11.0-31-generic     | 65       | 9.54%   |
| 5.11.0-37-generic     | 54       | 7.93%   |
| 5.11.0-34-generic     | 40       | 5.87%   |
| 5.11.0-17-generic     | 36       | 5.29%   |
| 5.11.0-38-generic     | 24       | 3.52%   |
| 5.11.0-49-generic     | 22       | 3.23%   |
| 5.11.0-40-generic     | 19       | 2.79%   |
| 5.11.0-41-generic     | 14       | 2.06%   |
| 5.11.0-36-generic     | 14       | 2.06%   |
| 5.11.0-33-generic     | 8        | 1.17%   |
| 5.11.0-26-generic     | 8        | 1.17%   |
| 5.11.0-24-generic     | 7        | 1.03%   |
| 5.11.0-13-generic     | 5        | 0.73%   |
| 5.10.0-14-generic     | 5        | 0.73%   |
| 5.11.0-23-generic     | 4        | 0.59%   |
| 5.11.0-14-generic     | 4        | 0.59%   |
| 5.8.0-36-generic      | 3        | 0.44%   |
| 5.11.0-46-generic     | 3        | 0.44%   |
| 5.8.0-50-generic      | 2        | 0.29%   |
| 5.11.0-42-generic     | 2        | 0.29%   |
| 5.11.0-35-generic     | 2        | 0.29%   |
| 5.11.0-19-generic     | 2        | 0.29%   |
| 5.11.0-11-generic     | 2        | 0.29%   |
| 5.11.0-051100-generic | 2        | 0.29%   |
| 5.10.0-12-generic     | 2        | 0.29%   |
| 5.10.0-051000-generic | 2        | 0.29%   |
| 5.9.8-xanmod1-cachy   | 1        | 0.15%   |
| 5.9.10-050910-generic | 1        | 0.15%   |
| 5.8.0-63-generic      | 1        | 0.15%   |
| 5.8.0-55-generic      | 1        | 0.15%   |
| 5.8.0-38-generic      | 1        | 0.15%   |
| 5.8.0-34-generic      | 1        | 0.15%   |
| 5.8.0-32-generic      | 1        | 0.15%   |
| 5.8.0-31-generic      | 1        | 0.15%   |
| 5.8.0-28-generic      | 1        | 0.15%   |
| 5.8.0-26-generic      | 1        | 0.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 576      | 93.66%  |
| 5.8.0   | 13       | 2.11%   |
| 5.10.0  | 9        | 1.46%   |
| 5.13.0  | 3        | 0.49%   |
| 5.12.0  | 2        | 0.33%   |
| 5.9.8   | 1        | 0.16%   |
| 5.9.10  | 1        | 0.16%   |
| 5.4.0   | 1        | 0.16%   |
| 5.16.10 | 1        | 0.16%   |
| 5.15.0  | 1        | 0.16%   |
| 5.14.9  | 1        | 0.16%   |
| 5.14.0  | 1        | 0.16%   |
| 5.13.9  | 1        | 0.16%   |
| 5.12.9  | 1        | 0.16%   |
| 5.12.10 | 1        | 0.16%   |
| 5.11.12 | 1        | 0.16%   |
| 5.11.1  | 1        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 578      | 93.98%  |
| 5.8     | 13       | 2.11%   |
| 5.10    | 9        | 1.46%   |
| 5.13    | 4        | 0.65%   |
| 5.12    | 4        | 0.65%   |
| 5.9     | 2        | 0.33%   |
| 5.14    | 2        | 0.33%   |
| 5.4     | 1        | 0.16%   |
| 5.16    | 1        | 0.16%   |
| 5.15    | 1        | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 608      | 99.84%  |
| aarch64 | 1        | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GNOME             | 546      | 88.78%  |
| Unknown           | 54       | 8.78%   |
| X-Cinnamon        | 6        | 0.98%   |
| Cinnamon          | 3        | 0.49%   |
| Yaru:ubuntu:GNOME | 2        | 0.33%   |
| Trinity           | 1        | 0.16%   |
| openbox           | 1        | 0.16%   |
| fvwm              | 1        | 0.16%   |
| awesome           | 1        | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 341      | 54.65%  |
| X11     | 249      | 39.9%   |
| Unknown | 26       | 4.17%   |
| Tty     | 8        | 1.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 385      | 60.73%  |
| GDM3    | 134      | 21.14%  |
| GDM     | 111      | 17.51%  |
| TDM     | 2        | 0.32%   |
| LightDM | 2        | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 207      | 33.93%  |
| de_DE   | 91       | 14.92%  |
| fr_FR   | 39       | 6.39%   |
| it_IT   | 27       | 4.43%   |
| en_GB   | 26       | 4.26%   |
| pt_BR   | 22       | 3.61%   |
| en_CA   | 18       | 2.95%   |
| en_AU   | 17       | 2.79%   |
| ru_RU   | 15       | 2.46%   |
| pl_PL   | 14       | 2.3%    |
| es_ES   | 11       | 1.8%    |
| zh_CN   | 9        | 1.48%   |
| en_IN   | 8        | 1.31%   |
| hu_HU   | 7        | 1.15%   |
| es_AR   | 7        | 1.15%   |
| de_AT   | 7        | 1.15%   |
| sv_SE   | 6        | 0.98%   |
| en_ZA   | 6        | 0.98%   |
| ru_UA   | 5        | 0.82%   |
| ja_JP   | 5        | 0.82%   |
| en_NZ   | 5        | 0.82%   |
| de_CH   | 5        | 0.82%   |
| cs_CZ   | 5        | 0.82%   |
| el_GR   | 4        | 0.66%   |
| C       | 4        | 0.66%   |
| pt_PT   | 3        | 0.49%   |
| nl_NL   | 3        | 0.49%   |
| bg_BG   | 3        | 0.49%   |
| ro_RO   | 2        | 0.33%   |
| nb_NO   | 2        | 0.33%   |
| fr_BE   | 2        | 0.33%   |
| fi_FI   | 2        | 0.33%   |
| es_CL   | 2        | 0.33%   |
| en_IL   | 2        | 0.33%   |
| ca_ES   | 2        | 0.33%   |
| Unknown | 2        | 0.33%   |
| zh_TW   | 1        | 0.16%   |
| zh_HK   | 1        | 0.16%   |
| vi_VN   | 1        | 0.16%   |
| uk_UA   | 1        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 476      | 77.52%  |
| EFI  | 138      | 22.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 547      | 89.53%  |
| Zfs      | 25       | 4.09%   |
| Overlay  | 15       | 2.45%   |
| Btrfs    | 13       | 2.13%   |
| Xfs      | 6        | 0.98%   |
| Ext3     | 2        | 0.33%   |
| Ext2     | 2        | 0.33%   |
| SquXshfs | 1        | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 490      | 80.07%  |
| GPT     | 107      | 17.48%  |
| MBR     | 15       | 2.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 482      | 77.49%  |
| Yes       | 140      | 22.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 328      | 53.16%  |
| Yes       | 289      | 46.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 173      | 28.41%  |
| Gigabyte Technology | 120      | 19.7%   |
| MSI                 | 85       | 13.96%  |
| ASRock              | 53       | 8.7%    |
| Dell                | 42       | 6.9%    |
| Hewlett-Packard     | 40       | 6.57%   |
| Lenovo              | 17       | 2.79%   |
| Acer                | 15       | 2.46%   |
| Biostar             | 9        | 1.48%   |
| Pegatron            | 6        | 0.99%   |
| Fujitsu             | 6        | 0.99%   |
| Medion              | 5        | 0.82%   |
| Unknown             | 5        | 0.82%   |
| Intel               | 4        | 0.66%   |
| Foxconn             | 4        | 0.66%   |
| Shuttle             | 3        | 0.49%   |
| HC                  | 2        | 0.33%   |
| TYAN Computer       | 1        | 0.16%   |
| SYWZ                | 1        | 0.16%   |
| Soyo                | 1        | 0.16%   |
| PCWare              | 1        | 0.16%   |
| Packard Bell        | 1        | 0.16%   |
| OEM                 | 1        | 0.16%   |
| MW                  | 1        | 0.16%   |
| MACHINIST           | 1        | 0.16%   |
| IBM                 | 1        | 0.16%   |
| HUAWEI              | 1        | 0.16%   |
| Huanan              | 1        | 0.16%   |
| Fujitsu Siemens     | 1        | 0.16%   |
| FIRICH              | 1        | 0.16%   |
| ECS                 | 1        | 0.16%   |
| Colorful Technology | 1        | 0.16%   |
| ASRockRack          | 1        | 0.16%   |
| Apple               | 1        | 0.16%   |
| AOpen               | 1        | 0.16%   |
| Alienware           | 1        | 0.16%   |
| AAEON               | 1        | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 17       | 2.79%   |
| Unknown                      | 5        | 0.82%   |
| MSI MS-7C37                  | 4        | 0.66%   |
| MSI MS-7B86                  | 4        | 0.66%   |
| Gigabyte B450M DS3H          | 4        | 0.66%   |
| Dell OptiPlex 7010           | 4        | 0.66%   |
| ASUS ROG STRIX B450-F GAMING | 4        | 0.66%   |
| MSI MS-7A34                  | 3        | 0.49%   |
| MSI MS-7850                  | 3        | 0.49%   |
| MSI MS-7758                  | 3        | 0.49%   |
| MSI MS-7693                  | 3        | 0.49%   |
| HP Z440 Workstation          | 3        | 0.49%   |
| Gigabyte Z77-DS3H            | 3        | 0.49%   |
| Gigabyte X570 AORUS MASTER   | 3        | 0.49%   |
| Dell OptiPlex 9010           | 3        | 0.49%   |
| ASUS ROG STRIX X570-E GAMING | 3        | 0.49%   |
| ASUS ROG STRIX B550-F GAMING | 3        | 0.49%   |
| ASUS PRIME Z590-P            | 3        | 0.49%   |
| ASUS PRIME A320M-K           | 3        | 0.49%   |
| ASUS M5A97 R2.0              | 3        | 0.49%   |
| Shuttle XH61V                | 2        | 0.33%   |
| MSI MS-7C91                  | 2        | 0.33%   |
| MSI MS-7C75                  | 2        | 0.33%   |
| MSI MS-7C02                  | 2        | 0.33%   |
| MSI MS-7B79                  | 2        | 0.33%   |
| MSI MS-7A38                  | 2        | 0.33%   |
| MSI MS-7817                  | 2        | 0.33%   |
| MSI MS-7592                  | 2        | 0.33%   |
| MSI MS-7529                  | 2        | 0.33%   |
| HP ProDesk 400 G1 SFF        | 2        | 0.33%   |
| HP EliteDesk 800 G1 SFF      | 2        | 0.33%   |
| HC HCAR357-MI                | 2        | 0.33%   |
| Gigabyte Z270X-Gaming 5      | 2        | 0.33%   |
| Gigabyte Z170X-Gaming 7      | 2        | 0.33%   |
| Gigabyte X570 AORUS PRO WIFI | 2        | 0.33%   |
| Gigabyte H61M-S2PV           | 2        | 0.33%   |
| Gigabyte H61M-S1             | 2        | 0.33%   |
| Gigabyte GA-78LMT-USB3 R2    | 2        | 0.33%   |
| Gigabyte GA-78LMT-USB3 6.0   | 2        | 0.33%   |
| Gigabyte GA-78LMT-USB3       | 2        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 37       | 6.08%   |
| ASUS ROG               | 28       | 4.6%    |
| Dell OptiPlex          | 22       | 3.61%   |
| ASUS All               | 17       | 2.79%   |
| Acer Aspire            | 12       | 1.97%   |
| Lenovo ThinkCentre     | 11       | 1.81%   |
| ASUS TUF               | 11       | 1.81%   |
| HP Compaq              | 9        | 1.48%   |
| Gigabyte X570          | 9        | 1.48%   |
| Dell Precision         | 8        | 1.31%   |
| HP EliteDesk           | 7        | 1.15%   |
| Gigabyte GA-78LMT-USB3 | 6        | 0.99%   |
| Gigabyte B450M         | 6        | 0.99%   |
| ASUS M5A97             | 6        | 0.99%   |
| ASUS P8Z77-V           | 5        | 0.82%   |
| Unknown                | 5        | 0.82%   |
| MSI MS-7C37            | 4        | 0.66%   |
| MSI MS-7B86            | 4        | 0.66%   |
| Dell Inspiron          | 4        | 0.66%   |
| ASUS P5Q               | 4        | 0.66%   |
| ASRock 970             | 4        | 0.66%   |
| MSI MS-7A34            | 3        | 0.49%   |
| MSI MS-7850            | 3        | 0.49%   |
| MSI MS-7758            | 3        | 0.49%   |
| MSI MS-7693            | 3        | 0.49%   |
| HP Z440                | 3        | 0.49%   |
| HP ProDesk             | 3        | 0.49%   |
| HP Pavilion            | 3        | 0.49%   |
| Gigabyte Z77-DS3H      | 3        | 0.49%   |
| Gigabyte Z390          | 3        | 0.49%   |
| Gigabyte B550          | 3        | 0.49%   |
| Fujitsu CELSIUS        | 3        | 0.49%   |
| Dell Vostro            | 3        | 0.49%   |
| ASUS P8Z68-V           | 3        | 0.49%   |
| ASRock X570            | 3        | 0.49%   |
| Shuttle XH61V          | 2        | 0.33%   |
| MSI MS-7C91            | 2        | 0.33%   |
| MSI MS-7C75            | 2        | 0.33%   |
| MSI MS-7C02            | 2        | 0.33%   |
| MSI MS-7B79            | 2        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 72       | 11.82%  |
| 2012 | 68       | 11.17%  |
| 2020 | 59       | 9.69%   |
| 2013 | 48       | 7.88%   |
| 2019 | 46       | 7.55%   |
| 2017 | 43       | 7.06%   |
| 2011 | 41       | 6.73%   |
| 2021 | 36       | 5.91%   |
| 2014 | 35       | 5.75%   |
| 2010 | 34       | 5.58%   |
| 2009 | 32       | 5.25%   |
| 2015 | 28       | 4.6%    |
| 2008 | 23       | 3.78%   |
| 2016 | 19       | 3.12%   |
| 2007 | 13       | 2.13%   |
| 2005 | 6        | 0.99%   |
| 2006 | 5        | 0.82%   |
| 2022 | 1        | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 609      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 596      | 97.87%  |
| Enabled  | 13       | 2.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 609      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 159      | 26.02%  |
| 8.01-16.0       | 129      | 21.11%  |
| 32.01-64.0      | 93       | 15.22%  |
| 3.01-4.0        | 82       | 13.42%  |
| 4.01-8.0        | 77       | 12.6%   |
| 64.01-256.0     | 39       | 6.38%   |
| 24.01-32.0      | 16       | 2.62%   |
| 1.01-2.0        | 13       | 2.13%   |
| 2.01-3.0        | 2        | 0.33%   |
| More than 256.0 | 1        | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 241      | 37.31%  |
| 2.01-3.0    | 172      | 26.63%  |
| 4.01-8.0    | 101      | 15.63%  |
| 3.01-4.0    | 72       | 11.15%  |
| 8.01-16.0   | 30       | 4.64%   |
| 16.01-24.0  | 10       | 1.55%   |
| 0.51-1.0    | 9        | 1.39%   |
| 32.01-64.0  | 6        | 0.93%   |
| 24.01-32.0  | 3        | 0.46%   |
| 64.01-256.0 | 1        | 0.15%   |
| 0.01-0.5    | 1        | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 227      | 36.15%  |
| 2      | 171      | 27.23%  |
| 3      | 99       | 15.76%  |
| 4      | 62       | 9.87%   |
| 5      | 32       | 5.1%    |
| 6      | 14       | 2.23%   |
| 8      | 7        | 1.11%   |
| 7      | 6        | 0.96%   |
| 0      | 4        | 0.64%   |
| 9      | 3        | 0.48%   |
| 10     | 2        | 0.32%   |
| 11     | 1        | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 309      | 50.41%  |
| Yes       | 304      | 49.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 596      | 97.87%  |
| No        | 13       | 2.13%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 327      | 53.17%  |
| Yes       | 288      | 46.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 385      | 62.91%  |
| Yes       | 227      | 37.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 113      | 18.49%  |
| Germany      | 102      | 16.69%  |
| France       | 40       | 6.55%   |
| Italy        | 30       | 4.91%   |
| Brazil       | 25       | 4.09%   |
| UK           | 24       | 3.93%   |
| Canada       | 21       | 3.44%   |
| Russia       | 19       | 3.11%   |
| Spain        | 17       | 2.78%   |
| Poland       | 16       | 2.62%   |
| Australia    | 16       | 2.62%   |
| Netherlands  | 13       | 2.13%   |
| Switzerland  | 10       | 1.64%   |
| Sweden       | 10       | 1.64%   |
| Austria      | 10       | 1.64%   |
| Argentina    | 10       | 1.64%   |
| Ukraine      | 9        | 1.47%   |
| India        | 9        | 1.47%   |
| Portugal     | 8        | 1.31%   |
| China        | 8        | 1.31%   |
| South Africa | 6        | 0.98%   |
| New Zealand  | 6        | 0.98%   |
| Japan        | 6        | 0.98%   |
| Hungary      | 6        | 0.98%   |
| Finland      | 6        | 0.98%   |
| Czechia      | 6        | 0.98%   |
| Romania      | 5        | 0.82%   |
| Greece       | 5        | 0.82%   |
| Serbia       | 4        | 0.65%   |
| Chile        | 4        | 0.65%   |
| Pakistan     | 3        | 0.49%   |
| Norway       | 3        | 0.49%   |
| Bulgaria     | 3        | 0.49%   |
| Belgium      | 3        | 0.49%   |
| Algeria      | 3        | 0.49%   |
| Singapore    | 2        | 0.33%   |
| Mexico       | 2        | 0.33%   |
| Israel       | 2        | 0.33%   |
| Indonesia    | 2        | 0.33%   |
| Croatia      | 2        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Berlin         | 11       | 1.74%   |
| Vienna         | 8        | 1.27%   |
| Paris          | 7        | 1.11%   |
| Milan          | 6        | 0.95%   |
| Sydney         | 5        | 0.79%   |
| Moscow         | 5        | 0.79%   |
| Sao Paulo      | 4        | 0.63%   |
| Melbourne      | 4        | 0.63%   |
| Hyderabad      | 4        | 0.63%   |
| Cologne        | 4        | 0.63%   |
| Beijing        | 4        | 0.63%   |
| Toronto        | 3        | 0.47%   |
| Santo André   | 3        | 0.47%   |
| New York       | 3        | 0.47%   |
| Munich         | 3        | 0.47%   |
| Lisbon         | 3        | 0.47%   |
| Karachi        | 3        | 0.47%   |
| Hamburg        | 3        | 0.47%   |
| Gelsenkirchen  | 3        | 0.47%   |
| Düsseldorf    | 3        | 0.47%   |
| Dallas         | 3        | 0.47%   |
| Bologna        | 3        | 0.47%   |
| Belo Horizonte | 3        | 0.47%   |
| Athens         | 3        | 0.47%   |
| Amsterdam      | 3        | 0.47%   |
| Wil            | 2        | 0.32%   |
| Warsaw         | 2        | 0.32%   |
| Tucson         | 2        | 0.32%   |
| Strasbourg     | 2        | 0.32%   |
| Singapore      | 2        | 0.32%   |
| Seattle        | 2        | 0.32%   |
| San Francisco  | 2        | 0.32%   |
| Saarbrücken   | 2        | 0.32%   |
| Saalfeld       | 2        | 0.32%   |
| Rosario        | 2        | 0.32%   |
| Portland       | 2        | 0.32%   |
| Pomarede       | 2        | 0.32%   |
| Phoenix        | 2        | 0.32%   |
| Perth          | 2        | 0.32%   |
| Oslo           | 2        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 218      | 352    | 18.99%  |
| Seagate                   | 212      | 348    | 18.47%  |
| Samsung Electronics       | 185      | 277    | 16.11%  |
| Kingston                  | 62       | 75     | 5.4%    |
| Toshiba                   | 61       | 82     | 5.31%   |
| SanDisk                   | 60       | 75     | 5.23%   |
| Crucial                   | 47       | 57     | 4.09%   |
| Hitachi                   | 43       | 55     | 3.75%   |
| A-DATA Technology         | 24       | 31     | 2.09%   |
| Silicon Motion            | 17       | 19     | 1.48%   |
| Phison                    | 17       | 20     | 1.48%   |
| Intel                     | 16       | 21     | 1.39%   |
| Unknown                   | 13       | 16     | 1.13%   |
| Maxtor                    | 10       | 14     | 0.87%   |
| Corsair                   | 8        | 11     | 0.7%    |
| China                     | 8        | 10     | 0.7%    |
| SPCC                      | 7        | 8      | 0.61%   |
| HGST                      | 7        | 12     | 0.61%   |
| PNY                       | 6        | 6      | 0.52%   |
| Micron Technology         | 6        | 6      | 0.52%   |
| JMicron Technology        | 6        | 9      | 0.52%   |
| Intenso                   | 6        | 7      | 0.52%   |
| GOODRAM                   | 6        | 6      | 0.52%   |
| OCZ                       | 5        | 6      | 0.44%   |
| Mushkin                   | 5        | 7      | 0.44%   |
| Micron/Crucial Technology | 5        | 6      | 0.44%   |
| LITEON                    | 5        | 6      | 0.44%   |
| Gigabyte Technology       | 5        | 6      | 0.44%   |
| XPG                       | 4        | 4      | 0.35%   |
| Transcend                 | 4        | 4      | 0.35%   |
| Vaseky                    | 3        | 3      | 0.26%   |
| SK hynix                  | 3        | 3      | 0.26%   |
| Plextor                   | 3        | 3      | 0.26%   |
| Patriot                   | 3        | 4      | 0.26%   |
| LITEONIT                  | 3        | 3      | 0.26%   |
| SABRENT                   | 2        | 3      | 0.17%   |
| Realtek Semiconductor     | 2        | 3      | 0.17%   |
| LaCie                     | 2        | 2      | 0.17%   |
| KingDian                  | 2        | 2      | 0.17%   |
| Hewlett-Packard           | 2        | 3      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB     | 19       | 1.41%   |
| Seagate ST1000DM010-2EP102 1TB   | 18       | 1.33%   |
| Samsung SSD 860 EVO 500GB        | 15       | 1.11%   |
| Kingston SA400S37240G 240GB SSD  | 15       | 1.11%   |
| Toshiba DT01ACA100 1TB           | 14       | 1.04%   |
| Samsung SSD 850 EVO 500GB        | 12       | 0.89%   |
| Samsung NVMe SSD Drive 1TB       | 12       | 0.89%   |
| Seagate ST2000DM001-1ER164 2TB   | 11       | 0.82%   |
| Seagate ST500DM002-1BD142 500GB  | 10       | 0.74%   |
| Samsung SSD 850 EVO 250GB        | 10       | 0.74%   |
| Toshiba DT01ACA200 2TB           | 9        | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB   | 9        | 0.67%   |
| Kingston SA400S37480G 480GB SSD  | 9        | 0.67%   |
| Seagate ST4000DM004-2CV104 4TB   | 8        | 0.59%   |
| Seagate ST31000524AS 1TB         | 8        | 0.59%   |
| Seagate ST2000DM006-2DM164 2TB   | 8        | 0.59%   |
| Seagate Expansion 4TB            | 8        | 0.59%   |
| Samsung SSD 860 EVO 250GB        | 8        | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB         | 7        | 0.52%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 7        | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB   | 7        | 0.52%   |
| SanDisk NVMe SSD Drive 500GB     | 7        | 0.52%   |
| SanDisk NVMe SSD Drive 1TB       | 7        | 0.52%   |
| Samsung NVMe SSD Drive 250GB     | 7        | 0.52%   |
| Kingston SA400S37120G 120GB SSD  | 7        | 0.52%   |
| Unknown SD/MMC/MS PRO 64GB       | 6        | 0.44%   |
| Seagate ST3500418AS 500GB        | 6        | 0.44%   |
| SanDisk SSD PLUS 240GB           | 6        | 0.44%   |
| Samsung SSD 840 EVO 250GB        | 6        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD | 6        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB      | 6        | 0.44%   |
| WDC WD5000AAKX-001CA0 500GB      | 5        | 0.37%   |
| WDC WD20EZRX-00D8PB0 2TB         | 5        | 0.37%   |
| WDC WD10EARS-00Y5B1 1TB          | 5        | 0.37%   |
| Seagate ST3500312CS 500GB        | 5        | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB   | 5        | 0.37%   |
| SanDisk NVMe SSD Drive 2TB       | 5        | 0.37%   |
| Samsung SSD 860 EVO 1TB          | 5        | 0.37%   |
| Samsung NVMe SSD Drive 512GB     | 5        | 0.37%   |
| Kingston SUV400S37240G 240GB SSD | 5        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 207      | 340    | 36.38%  |
| WDC                 | 199      | 321    | 34.97%  |
| Toshiba             | 55       | 73     | 9.67%   |
| Hitachi             | 43       | 55     | 7.56%   |
| Samsung Electronics | 33       | 44     | 5.8%    |
| Maxtor              | 10       | 14     | 1.76%   |
| HGST                | 7        | 12     | 1.23%   |
| Unknown             | 6        | 6      | 1.05%   |
| ASMT                | 2        | 3      | 0.35%   |
| Synology            | 1        | 8      | 0.18%   |
| RSH-339             | 1        | 1      | 0.18%   |
| JMicron Technology  | 1        | 2      | 0.18%   |
| Hewlett-Packard     | 1        | 1      | 0.18%   |
| Fujitsu             | 1        | 1      | 0.18%   |
| ASMT109x            | 1        | 1      | 0.18%   |
| Apple               | 1        | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 101      | 134    | 25.44%  |
| Kingston            | 53       | 63     | 13.35%  |
| Crucial             | 44       | 54     | 11.08%  |
| SanDisk             | 41       | 48     | 10.33%  |
| WDC                 | 21       | 22     | 5.29%   |
| A-DATA Technology   | 21       | 26     | 5.29%   |
| China               | 8        | 10     | 2.02%   |
| Toshiba             | 7        | 8      | 1.76%   |
| SPCC                | 7        | 8      | 1.76%   |
| GOODRAM             | 6        | 6      | 1.51%   |
| PNY                 | 5        | 5      | 1.26%   |
| OCZ                 | 5        | 6      | 1.26%   |
| Mushkin             | 5        | 7      | 1.26%   |
| Micron Technology   | 5        | 5      | 1.26%   |
| LITEON              | 5        | 6      | 1.26%   |
| Intenso             | 5        | 6      | 1.26%   |
| Intel               | 5        | 8      | 1.26%   |
| Transcend           | 4        | 4      | 1.01%   |
| JMicron Technology  | 4        | 4      | 1.01%   |
| Vaseky              | 3        | 3      | 0.76%   |
| Plextor             | 3        | 3      | 0.76%   |
| Patriot             | 3        | 4      | 0.76%   |
| LITEONIT            | 3        | 3      | 0.76%   |
| Gigabyte Technology | 3        | 3      | 0.76%   |
| Corsair             | 3        | 3      | 0.76%   |
| KingDian            | 2        | 2      | 0.5%    |
| Unknown             | 2        | 2      | 0.5%    |
| Zozt                | 1        | 3      | 0.25%   |
| Zheino              | 1        | 2      | 0.25%   |
| Verbatim            | 1        | 1      | 0.25%   |
| Unknown             | 1        | 1      | 0.25%   |
| Teclast             | 1        | 1      | 0.25%   |
| Team                | 1        | 2      | 0.25%   |
| Smartbuy            | 1        | 1      | 0.25%   |
| Palit               | 1        | 1      | 0.25%   |
| OCZ-VERTEX3         | 1        | 1      | 0.25%   |
| Lexar               | 1        | 1      | 0.25%   |
| Leven               | 1        | 1      | 0.25%   |
| LDLC                | 1        | 1      | 0.25%   |
| KLEVV               | 1        | 1      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 425      | 883    | 45.41%  |
| SSD     | 326      | 481    | 34.83%  |
| NVMe    | 162      | 248    | 17.31%  |
| Unknown | 21       | 32     | 2.24%   |
| MMC     | 2        | 2      | 0.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 558      | 1319   | 72.37%  |
| NVMe | 160      | 244    | 20.75%  |
| SAS  | 51       | 81     | 6.61%   |
| MMC  | 2        | 2      | 0.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 403      | 709    | 48.21%  |
| 0.51-1.0   | 234      | 333    | 27.99%  |
| 1.01-2.0   | 107      | 172    | 12.8%   |
| 3.01-4.0   | 36       | 50     | 4.31%   |
| 4.01-10.0  | 27       | 45     | 3.23%   |
| 2.01-3.0   | 21       | 30     | 2.51%   |
| 10.01-20.0 | 8        | 25     | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 137      | 21.71%  |
| 251-500        | 123      | 19.49%  |
| 501-1000       | 111      | 17.59%  |
| 1001-2000      | 85       | 13.47%  |
| More than 3000 | 61       | 9.67%   |
| 2001-3000      | 34       | 5.39%   |
| 51-100         | 29       | 4.6%    |
| 1-20           | 24       | 3.8%    |
| 21-50          | 23       | 3.65%   |
| Unknown        | 4        | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 226      | 34.88%  |
| 21-50          | 103      | 15.9%   |
| 101-250        | 82       | 12.65%  |
| 51-100         | 64       | 9.88%   |
| 501-1000       | 50       | 7.72%   |
| 251-500        | 45       | 6.94%   |
| 1001-2000      | 36       | 5.56%   |
| More than 3000 | 26       | 4.01%   |
| 2001-3000      | 12       | 1.85%   |
| Unknown        | 4        | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB                  | 2        | 2      | 3.64%   |
| Seagate ST4000DM004-2CV104 4TB               | 2        | 3      | 3.64%   |
| Crucial CT240M500SSD1 240GB                  | 2        | 2      | 3.64%   |
| WDC WD7500BPKX-00HPJT0 752GB                 | 1        | 1      | 1.82%   |
| WDC WD7500AADS-00M2B0 752GB                  | 1        | 1      | 1.82%   |
| WDC WD6400AAKS-65A7B0 640GB                  | 1        | 1      | 1.82%   |
| WDC WD5000AZRX-00A8LB0 500GB                 | 1        | 1      | 1.82%   |
| WDC WD5000AAKS-22A7B0 500GB                  | 1        | 1      | 1.82%   |
| WDC WD5000AAKS-00UU3A0 500GB                 | 1        | 1      | 1.82%   |
| WDC WD5000AADS-00S9B0 500GB                  | 1        | 1      | 1.82%   |
| WDC WD5000AADS-00L4B1 500GB                  | 1        | 1      | 1.82%   |
| WDC WD3200AAVS-00ZTB0 320GB                  | 1        | 1      | 1.82%   |
| WDC WD3200AAJS-60M0A0 320GB                  | 1        | 1      | 1.82%   |
| WDC WD20EZRZ-00Z5HB0 2TB                     | 1        | 1      | 1.82%   |
| WDC WD20EZRX-00DC0B0 2TB                     | 1        | 1      | 1.82%   |
| WDC WD15EARS-00S8B1 1TB                      | 1        | 1      | 1.82%   |
| WDC WD10EZEX-60ZF5A0 1TB                     | 1        | 2      | 1.82%   |
| WDC WD10EZEX-08M2NA0 1TB                     | 1        | 1      | 1.82%   |
| WDC WD10EADS-65M2B1 1TB                      | 1        | 1      | 1.82%   |
| WDC WD1003FZEX-00MK2A0 1TB                   | 1        | 1      | 1.82%   |
| Toshiba MQ01ABF050 500GB                     | 1        | 1      | 1.82%   |
| Toshiba DT01ACA100 1TB                       | 1        | 1      | 1.82%   |
| Seagate ST9250311CS 250GB                    | 1        | 1      | 1.82%   |
| Seagate ST500NM0011 39M4517 42C0468IBM 500GB | 1        | 1      | 1.82%   |
| Seagate ST500LM021-1KJ152 500GB              | 1        | 1      | 1.82%   |
| Seagate ST500DM002-1BD142 500GB              | 1        | 1      | 1.82%   |
| Seagate ST3750640NS 752GB                    | 1        | 1      | 1.82%   |
| Seagate ST3500830AS 500GB                    | 1        | 1      | 1.82%   |
| Seagate ST3500630AS 500GB                    | 1        | 1      | 1.82%   |
| Seagate ST3500414CS 500GB                    | 1        | 1      | 1.82%   |
| Seagate ST3320820AS 320GB                    | 1        | 1      | 1.82%   |
| Seagate ST2000DX002-2DV164 2TB               | 1        | 1      | 1.82%   |
| Seagate ST2000DM001-1CH164 2TB               | 1        | 1      | 1.82%   |
| Seagate ST2000DL003-9VT166 2TB               | 1        | 1      | 1.82%   |
| Samsung Electronics SSD 970 EVO 1TB          | 1        | 1      | 1.82%   |
| Samsung Electronics SSD 870 EVO 4TB          | 1        | 1      | 1.82%   |
| Samsung Electronics SSD 840 EVO 500GB        | 1        | 1      | 1.82%   |
| Samsung Electronics HD103SJ 1TB              | 1        | 1      | 1.82%   |
| Plextor PX-128M5S 128GB SSD                  | 1        | 1      | 1.82%   |
| OCZ VERTEX3 120GB SSD                        | 1        | 1      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 20     | 33.33%  |
| Seagate             | 12       | 15     | 23.53%  |
| Samsung Electronics | 4        | 4      | 7.84%   |
| Kingston            | 4        | 4      | 7.84%   |
| Crucial             | 3        | 3      | 5.88%   |
| Toshiba             | 2        | 2      | 3.92%   |
| OCZ                 | 2        | 2      | 3.92%   |
| Intel               | 2        | 2      | 3.92%   |
| Hitachi             | 2        | 2      | 3.92%   |
| Plextor             | 1        | 1      | 1.96%   |
| Micron Technology   | 1        | 1      | 1.96%   |
| Anobit              | 1        | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 20     | 50%     |
| Seagate             | 12       | 15     | 35.29%  |
| Toshiba             | 2        | 2      | 5.88%   |
| Hitachi             | 2        | 2      | 5.88%   |
| Samsung Electronics | 1        | 1      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 33       | 40     | 67.35%  |
| SSD  | 15       | 16     | 30.61%  |
| NVMe | 1        | 1      | 2.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB | 1        | 1      | 100%    |

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
| Detected | 490      | 1252   | 73.68%  |
| Works    | 128      | 336    | 19.25%  |
| Malfunc  | 46       | 57     | 6.92%   |
| Failed   | 1        | 1      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 394      | 45.44%  |
| AMD                          | 199      | 22.95%  |
| Samsung Electronics          | 68       | 7.84%   |
| SanDisk                      | 27       | 3.11%   |
| Phison Electronics           | 25       | 2.88%   |
| ASMedia Technology           | 24       | 2.77%   |
| Marvell Technology Group     | 20       | 2.31%   |
| Nvidia                       | 19       | 2.19%   |
| Silicon Motion               | 18       | 2.08%   |
| JMicron Technology           | 17       | 1.96%   |
| Kingston Technology Company  | 10       | 1.15%   |
| ADATA Technology             | 9        | 1.04%   |
| Micron/Crucial Technology    | 8        | 0.92%   |
| Silicon Image                | 4        | 0.46%   |
| LSI Logic / Symbios Logic    | 4        | 0.46%   |
| Broadcom / LSI               | 3        | 0.35%   |
| VIA Technologies             | 2        | 0.23%   |
| SK hynix                     | 2        | 0.23%   |
| Realtek Semiconductor        | 2        | 0.23%   |
| INNOGRIT                     | 2        | 0.23%   |
| Adaptec                      | 2        | 0.23%   |
| Toshiba America Info Systems | 1        | 0.12%   |
| Shenzhen Longsys Electronics | 1        | 0.12%   |
| Promise Technology           | 1        | 0.12%   |
| Micron Technology            | 1        | 0.12%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.12%   |
| KIOXIA                       | 1        | 0.12%   |
| Huawei Technologies          | 1        | 0.12%   |
| Hewlett-Packard              | 1        | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 104      | 9.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 44       | 3.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 39       | 3.52%   |
| AMD 400 Series Chipset SATA Controller                                                  | 38       | 3.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 37       | 3.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 33       | 2.98%   |
| Intel SATA Controller [RAID mode]                                                       | 29       | 2.62%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 29       | 2.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 29       | 2.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 26       | 2.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 23       | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 23       | 2.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 22       | 1.99%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 22       | 1.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 22       | 1.99%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 21       | 1.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 20       | 1.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 20       | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 18       | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 18       | 1.62%   |
| Phison E12 NVMe Controller                                                              | 16       | 1.44%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 15       | 1.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 12       | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12       | 1.08%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 12       | 1.08%   |
| AMD FCH SATA Controller D                                                               | 12       | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11       | 0.99%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 11       | 0.99%   |
| AMD FCH IDE Controller                                                                  | 11       | 0.99%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 10       | 0.9%    |
| Samsung NVMe SSD Controller 980                                                         | 10       | 0.9%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 10       | 0.9%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 10       | 0.9%    |
| AMD 300 Series Chipset SATA Controller                                                  | 10       | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 9        | 0.81%   |
| Intel SSD 660P Series                                                                   | 8        | 0.72%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 8        | 0.72%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 8        | 0.72%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 7        | 0.63%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 485      | 56%     |
| IDE  | 161      | 18.59%  |
| NVMe | 158      | 18.24%  |
| RAID | 49       | 5.66%   |
| SAS  | 8        | 0.92%   |
| SCSI | 5        | 0.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 395      | 64.86%  |
| AMD     | 213      | 34.98%  |
| Unknown | 1        | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 16       | 2.62%   |
| AMD Ryzen 5 3600 6-Core Processor           | 14       | 2.3%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 9        | 1.48%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 9        | 1.48%   |
| AMD FX-8350 Eight-Core Processor            | 9        | 1.48%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 8        | 1.31%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 7        | 1.15%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 7        | 1.15%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 7        | 1.15%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 7        | 1.15%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 7        | 1.15%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 6        | 0.98%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 6        | 0.98%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 6        | 0.98%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 6        | 0.98%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 6        | 0.98%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 6        | 0.98%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 0.98%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 6        | 0.98%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 6        | 0.98%   |
| AMD FX-6300 Six-Core Processor              | 6        | 0.98%   |
| Intel Core i9-10900 CPU @ 2.80GHz           | 5        | 0.82%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 0.82%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 5        | 0.82%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 0.82%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 5        | 0.82%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 0.82%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5        | 0.82%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 5        | 0.82%   |
| AMD A4-4000 APU with Radeon HD Graphics     | 5        | 0.82%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 4        | 0.66%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 0.66%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 0.66%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 4        | 0.66%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 0.66%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 4        | 0.66%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4        | 0.66%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 4        | 0.66%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 120      | 19.67%  |
| Intel Core i7           | 85       | 13.93%  |
| AMD Ryzen 5             | 50       | 8.2%    |
| Intel Core i3           | 46       | 7.54%   |
| AMD Ryzen 7             | 36       | 5.9%    |
| Intel Xeon              | 30       | 4.92%   |
| AMD FX                  | 28       | 4.59%   |
| Intel Core i9           | 18       | 2.95%   |
| Intel Celeron           | 17       | 2.79%   |
| Intel Core 2 Duo        | 16       | 2.62%   |
| Intel Pentium Dual-Core | 14       | 2.3%    |
| AMD Ryzen 9             | 13       | 2.13%   |
| AMD Ryzen 3             | 13       | 2.13%   |
| Intel Core 2 Quad       | 12       | 1.97%   |
| Intel Pentium           | 11       | 1.8%    |
| Other                   | 9        | 1.48%   |
| AMD Phenom II X4        | 9        | 1.48%   |
| AMD A4                  | 9        | 1.48%   |
| AMD Athlon 64 X2        | 8        | 1.31%   |
| AMD Athlon II X2        | 7        | 1.15%   |
| AMD Ryzen Threadripper  | 6        | 0.98%   |
| Intel Pentium 4         | 4        | 0.66%   |
| AMD Phenom II X6        | 4        | 0.66%   |
| AMD Phenom              | 4        | 0.66%   |
| AMD A10                 | 4        | 0.66%   |
| Intel Pentium D         | 3        | 0.49%   |
| AMD Athlon II X4        | 3        | 0.49%   |
| AMD A6                  | 3        | 0.49%   |
| Intel Pentium Dual      | 2        | 0.33%   |
| Intel Core 2 Extreme    | 2        | 0.33%   |
| Intel Core 2            | 2        | 0.33%   |
| AMD Sempron             | 2        | 0.33%   |
| AMD Athlon X4           | 2        | 0.33%   |
| AMD A8                  | 2        | 0.33%   |
| Intel Pentium Silver    | 1        | 0.16%   |
| Intel Pentium Gold      | 1        | 0.16%   |
| Intel Genuine           | 1        | 0.16%   |
| Intel Celeron D         | 1        | 0.16%   |
| Intel Atom              | 1        | 0.16%   |
| AMD Turion II Neo       | 1        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 248      | 40.66%  |
| 2      | 137      | 22.46%  |
| 6      | 92       | 15.08%  |
| 8      | 68       | 11.15%  |
| 1      | 16       | 2.62%   |
| 3      | 13       | 2.13%   |
| 12     | 12       | 1.97%   |
| 10     | 12       | 1.97%   |
| 16     | 5        | 0.82%   |
| 24     | 4        | 0.66%   |
| 64     | 1        | 0.16%   |
| 36     | 1        | 0.16%   |
| 14     | 1        | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 600      | 98.52%  |
| 2      | 8        | 1.31%   |
| 6      | 1        | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 342      | 56.16%  |
| 1      | 267      | 43.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 608      | 99.84%  |
| Unknown        | 1        | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 423      | 68.12%  |
| 0x306c3    | 28       | 4.51%   |
| 0x306a9    | 13       | 2.09%   |
| 0x08701021 | 12       | 1.93%   |
| 0xa0655    | 9        | 1.45%   |
| 0xa0653    | 9        | 1.45%   |
| 0x206a7    | 9        | 1.45%   |
| 0x906ed    | 8        | 1.29%   |
| 0x906ea    | 7        | 1.13%   |
| 0xa0671    | 6        | 0.97%   |
| 0x506e3    | 6        | 0.97%   |
| 0x1067a    | 6        | 0.97%   |
| 0x0a201016 | 6        | 0.97%   |
| 0x08108109 | 6        | 0.97%   |
| 0x906e9    | 5        | 0.81%   |
| 0x0800820d | 5        | 0.81%   |
| 0x06000852 | 5        | 0.81%   |
| 0x0a201009 | 4        | 0.64%   |
| 0x906eb    | 3        | 0.48%   |
| 0x106a5    | 3        | 0.48%   |
| 0x08701013 | 3        | 0.48%   |
| 0x010000c8 | 3        | 0.48%   |
| 0x20655    | 2        | 0.32%   |
| 0x106e5    | 2        | 0.32%   |
| 0x0a50000c | 2        | 0.32%   |
| 0x0a201006 | 2        | 0.32%   |
| 0x08001137 | 2        | 0.32%   |
| 0x010000dc | 2        | 0.32%   |
| 0x010000db | 2        | 0.32%   |
| 0xf64      | 1        | 0.16%   |
| 0xf43      | 1        | 0.16%   |
| 0x906ec    | 1        | 0.16%   |
| 0x706a8    | 1        | 0.16%   |
| 0x706a1    | 1        | 0.16%   |
| 0x6fd      | 1        | 0.16%   |
| 0x6fb      | 1        | 0.16%   |
| 0x6f7      | 1        | 0.16%   |
| 0x50654    | 1        | 0.16%   |
| 0x406f1    | 1        | 0.16%   |
| 0x406e3    | 1        | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Haswell         | 69       | 11.31%  |
| KabyLake        | 63       | 10.33%  |
| IvyBridge       | 53       | 8.69%   |
| Zen 2           | 45       | 7.38%   |
| SandyBridge     | 45       | 7.38%   |
| Penryn          | 39       | 6.39%   |
| Piledriver      | 36       | 5.9%    |
| CometLake       | 34       | 5.57%   |
| K10             | 32       | 5.25%   |
| Zen+            | 29       | 4.75%   |
| Skylake         | 26       | 4.26%   |
| Zen             | 25       | 4.1%    |
| Zen 3           | 22       | 3.61%   |
| Nehalem         | 14       | 2.3%    |
| Core            | 14       | 2.3%    |
| Westmere        | 10       | 1.64%   |
| K8 Hammer       | 9        | 1.48%   |
| NetBurst        | 8        | 1.31%   |
| Icelake         | 5        | 0.82%   |
| Steamroller     | 4        | 0.66%   |
| Goldmont plus   | 4        | 0.66%   |
| Bulldozer       | 4        | 0.66%   |
| Broadwell       | 4        | 0.66%   |
| K10 Llano       | 3        | 0.49%   |
| Unknown         | 3        | 0.49%   |
| Silvermont      | 2        | 0.33%   |
| Puma            | 2        | 0.33%   |
| Goldmont        | 2        | 0.33%   |
| TigerLake       | 1        | 0.16%   |
| K8 & K10 hybrid | 1        | 0.16%   |
| Jaguar          | 1        | 0.16%   |
| Bobcat          | 1        | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 265      | 41.34%  |
| AMD                                          | 191      | 29.8%   |
| Intel                                        | 182      | 28.39%  |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.16%   |
| Matrox Electronics Systems                   | 1        | 0.16%   |
| ASPEED Technology                            | 1        | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 28       | 4.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 27       | 4.09%   |
| Nvidia GK208B [GeForce GT 710]                                              | 21       | 3.18%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 20       | 3.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 19       | 2.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 18       | 2.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 15       | 2.27%   |
| Nvidia GT218 [GeForce 210]                                                  | 13       | 1.97%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 12       | 1.82%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 11       | 1.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 11       | 1.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 11       | 1.67%   |
| Nvidia GK208B [GeForce GT 730]                                              | 10       | 1.52%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 10       | 1.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 10       | 1.52%   |
| Intel HD Graphics 530                                                       | 9        | 1.36%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 9        | 1.36%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 9        | 1.36%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 9        | 1.36%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 8        | 1.21%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 8        | 1.21%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 8        | 1.21%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 7        | 1.06%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 7        | 1.06%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 7        | 1.06%   |
| Intel HD Graphics 630                                                       | 7        | 1.06%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 6        | 0.91%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 6        | 0.91%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 6        | 0.91%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 5        | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 0.76%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 5        | 0.76%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 0.76%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 5        | 0.76%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 5        | 0.76%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 5        | 0.76%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 5        | 0.76%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4        | 0.61%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x Nvidia          | 246      | 40.2%   |
| 1 x AMD             | 178      | 29.08%  |
| 1 x Intel           | 157      | 25.65%  |
| 2 x Nvidia          | 9        | 1.47%   |
| Intel + Nvidia      | 7        | 1.14%   |
| 2 x AMD             | 5        | 0.82%   |
| Intel + AMD         | 4        | 0.65%   |
| AMD + Nvidia        | 2        | 0.33%   |
| 1 x XGI             | 1        | 0.16%   |
| 1 x Matrox          | 1        | 0.16%   |
| 1 x Intel + 4 x AMD | 1        | 0.16%   |
| 1 x ASPEED          | 1        | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 442      | 71.41%  |
| Proprietary | 152      | 24.56%  |
| Unknown     | 25       | 4.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 416      | 67.21%  |
| 1.01-2.0   | 64       | 10.34%  |
| 7.01-8.0   | 36       | 5.82%   |
| 0.51-1.0   | 30       | 4.85%   |
| 3.01-4.0   | 29       | 4.68%   |
| 5.01-6.0   | 13       | 2.1%    |
| 8.01-16.0  | 12       | 1.94%   |
| 0.01-0.5   | 12       | 1.94%   |
| 2.01-3.0   | 7        | 1.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 123      | 19.16%  |
| Dell                 | 69       | 10.75%  |
| Acer                 | 58       | 9.03%   |
| Goldstar             | 57       | 8.88%   |
| Hewlett-Packard      | 38       | 5.92%   |
| Ancor Communications | 37       | 5.76%   |
| Philips              | 30       | 4.67%   |
| BenQ                 | 29       | 4.52%   |
| AOC                  | 21       | 3.27%   |
| LG Electronics       | 18       | 2.8%    |
| Unknown              | 17       | 2.65%   |
| ViewSonic            | 14       | 2.18%   |
| Iiyama               | 12       | 1.87%   |
| Sony                 | 11       | 1.71%   |
| NEC Computers        | 7        | 1.09%   |
| HannStar             | 7        | 1.09%   |
| Fujitsu Siemens      | 7        | 1.09%   |
| Lenovo               | 6        | 0.93%   |
| ASUSTek Computer     | 6        | 0.93%   |
| Medion               | 5        | 0.78%   |
| Hitachi              | 4        | 0.62%   |
| Idek Iiyama          | 3        | 0.47%   |
| Eizo                 | 3        | 0.47%   |
| Viotek               | 2        | 0.31%   |
| Vestel Elektronik    | 2        | 0.31%   |
| SKY                  | 2        | 0.31%   |
| Sceptre Tech         | 2        | 0.31%   |
| Sceptre              | 2        | 0.31%   |
| Panasonic            | 2        | 0.31%   |
| HPN                  | 2        | 0.31%   |
| AUS                  | 2        | 0.31%   |
| Xiaomi               | 1        | 0.16%   |
| Westinghouse         | 1        | 0.16%   |
| Vizio                | 1        | 0.16%   |
| Vestel               | 1        | 0.16%   |
| Unknown (XXX)        | 1        | 0.16%   |
| Unknown (ACA)        | 1        | 0.16%   |
| TXD                  | 1        | 0.16%   |
| Toshiba              | 1        | 0.16%   |
| Tech Concepts        | 1        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 4        | 0.58%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 4        | 0.58%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 3        | 0.44%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                      | 3        | 0.44%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 3        | 0.44%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 3        | 0.44%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                | 3        | 0.44%   |
| Hitachi HISENSE HEC0030 1920x1080 580x330mm 26.3-inch                  | 3        | 0.44%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch               | 3        | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3        | 0.44%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                      | 3        | 0.44%   |
| BenQ LCD Monitor GL2450H 1920x1080                                     | 3        | 0.44%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 3        | 0.44%   |
| Viotek VIOTEKNB32C VTK3200 1920x1080 698x393mm 31.5-inch               | 2        | 0.29%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch          | 2        | 0.29%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch   | 2        | 0.29%   |
| SKY SKYWORTH SKY0001 1920x1080 885x498mm 40.0-inch                     | 2        | 0.29%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 2        | 0.29%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch   | 2        | 0.29%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch   | 2        | 0.29%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 520x290mm 23.4-inch      | 2        | 0.29%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 2        | 0.29%   |
| Samsung Electronics LCD Monitor U32J59x 3840x2160                      | 2        | 0.29%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 2        | 0.29%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2        | 0.29%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                    | 2        | 0.29%   |
| LG Electronics LCD Monitor LG TV 1920x1080                             | 2        | 0.29%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch             | 2        | 0.29%   |
| Hewlett-Packard VH240a HPN349A 1920x1080 527x296mm 23.8-inch           | 2        | 0.29%   |
| Hewlett-Packard V27i HPN36B1 1920x1080 598x336mm 27.0-inch             | 2        | 0.29%   |
| Hewlett-Packard Compaq WF1907 HWP26A4 1440x900 408x255mm 18.9-inch     | 2        | 0.29%   |
| Hewlett-Packard 27fh HPN354A 1920x1080 598x336mm 27.0-inch             | 2        | 0.29%   |
| Hewlett-Packard 27es HWP3325 1920x1080 598x336mm 27.0-inch             | 2        | 0.29%   |
| Goldstar L207W GSM4E7B 1680x1050 434x270mm 20.1-inch                   | 2        | 0.29%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 2        | 0.29%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch               | 2        | 0.29%   |
| Dell U2717D DEL40EA 2560x1440 597x336mm 27.0-inch                      | 2        | 0.29%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2        | 0.29%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                     | 2        | 0.29%   |
| Dell S2421HN DEL41F1 1920x1080 527x296mm 23.8-inch                     | 2        | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 293      | 45.85%  |
| 3840x2160 (4K)     | 52       | 8.14%   |
| 1280x1024 (SXGA)   | 45       | 7.04%   |
| 2560x1440 (QHD)    | 42       | 6.57%   |
| 1680x1050 (WSXGA+) | 34       | 5.32%   |
| Unknown            | 31       | 4.85%   |
| 1366x768 (WXGA)    | 19       | 2.97%   |
| 1440x900 (WXGA+)   | 16       | 2.5%    |
| 1920x1200 (WUXGA)  | 15       | 2.35%   |
| 1600x900 (HD+)     | 14       | 2.19%   |
| 2560x1080          | 11       | 1.72%   |
| 3440x1440          | 8        | 1.25%   |
| 1360x768           | 8        | 1.25%   |
| 3840x1080          | 6        | 0.94%   |
| 1920x540           | 5        | 0.78%   |
| 1280x720 (HD)      | 5        | 0.78%   |
| 4480x1440          | 4        | 0.63%   |
| 1600x1200          | 4        | 0.63%   |
| 5760x2160          | 3        | 0.47%   |
| 5120x1440          | 3        | 0.47%   |
| 5760x1080          | 2        | 0.31%   |
| 3520x1080          | 2        | 0.31%   |
| 2048x1152          | 2        | 0.31%   |
| 1024x768 (XGA)     | 2        | 0.31%   |
| 6400x2160          | 1        | 0.16%   |
| 5760x1200          | 1        | 0.16%   |
| 4608x1440          | 1        | 0.16%   |
| 4480x1200          | 1        | 0.16%   |
| 4480x1080          | 1        | 0.16%   |
| 4240x1440          | 1        | 0.16%   |
| 3640x1920          | 1        | 0.16%   |
| 3600x1080          | 1        | 0.16%   |
| 2880x1200          | 1        | 0.16%   |
| 2560x2520          | 1        | 0.16%   |
| 2048x1536          | 1        | 0.16%   |
| 1826x1027          | 1        | 0.16%   |
| 1360x765           | 1        | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 109      | 17.27%  |
| 24      | 84       | 13.31%  |
| 27      | 75       | 11.89%  |
| 23      | 70       | 11.09%  |
| 21      | 66       | 10.46%  |
| 19      | 46       | 7.29%   |
| 31      | 33       | 5.23%   |
| 22      | 21       | 3.33%   |
| 20      | 18       | 2.85%   |
| 18      | 17       | 2.69%   |
| 84      | 14       | 2.22%   |
| 34      | 13       | 2.06%   |
| 17      | 12       | 1.9%    |
| 32      | 8        | 1.27%   |
| 15      | 8        | 1.27%   |
| 54      | 6        | 0.95%   |
| 40      | 4        | 0.63%   |
| 25      | 4        | 0.63%   |
| 65      | 3        | 0.48%   |
| 48      | 3        | 0.48%   |
| 72      | 2        | 0.32%   |
| 47      | 2        | 0.32%   |
| 28      | 2        | 0.32%   |
| 26      | 2        | 0.32%   |
| 86      | 1        | 0.16%   |
| 69      | 1        | 0.16%   |
| 52      | 1        | 0.16%   |
| 50      | 1        | 0.16%   |
| 43      | 1        | 0.16%   |
| 38      | 1        | 0.16%   |
| 36      | 1        | 0.16%   |
| 14      | 1        | 0.16%   |
| 10      | 1        | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 216      | 35.01%  |
| 401-500     | 137      | 22.2%   |
| Unknown     | 109      | 17.67%  |
| 601-700     | 40       | 6.48%   |
| 351-400     | 34       | 5.51%   |
| 701-800     | 20       | 3.24%   |
| 301-350     | 19       | 3.08%   |
| 1501-2000   | 18       | 2.92%   |
| 1001-1500   | 16       | 2.59%   |
| 801-900     | 6        | 0.97%   |
| 201-300     | 1        | 0.16%   |
| 901-1000    | 1        | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 361      | 60.57%  |
| Unknown | 99       | 16.61%  |
| 16/10   | 68       | 11.41%  |
| 5/4     | 39       | 6.54%   |
| 21/9    | 15       | 2.52%   |
| 4/3     | 7        | 1.17%   |
| 6/5     | 4        | 0.67%   |
| 3/2     | 2        | 0.34%   |
| 32/9    | 1        | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 195      | 31.3%   |
| Unknown        | 109      | 17.5%   |
| 151-200        | 85       | 13.64%  |
| 301-350        | 76       | 12.2%   |
| 351-500        | 51       | 8.19%   |
| More than 1000 | 32       | 5.14%   |
| 251-300        | 31       | 4.98%   |
| 141-150        | 24       | 3.85%   |
| 501-1000       | 10       | 1.61%   |
| 101-110        | 7        | 1.12%   |
| 81-90          | 1        | 0.16%   |
| 41-50          | 1        | 0.16%   |
| 111-120        | 1        | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 339      | 57.17%  |
| Unknown | 109      | 18.38%  |
| 101-120 | 96       | 16.19%  |
| 1-50    | 26       | 4.38%   |
| 121-160 | 14       | 2.36%   |
| 161-240 | 9        | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 471      | 75.97%  |
| 2     | 101      | 16.29%  |
| 0     | 41       | 6.61%   |
| 3     | 6        | 0.97%   |
| 4     | 1        | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 376      | 43.17%  |
| Intel                           | 257      | 29.51%  |
| Qualcomm Atheros                | 69       | 7.92%   |
| Broadcom                        | 21       | 2.41%   |
| Ralink Technology               | 20       | 2.3%    |
| TP-Link                         | 18       | 2.07%   |
| Nvidia                          | 14       | 1.61%   |
| Ralink                          | 12       | 1.38%   |
| Marvell Technology Group        | 6        | 0.69%   |
| Samsung Electronics             | 5        | 0.57%   |
| D-Link System                   | 5        | 0.57%   |
| D-Link                          | 5        | 0.57%   |
| ASUSTek Computer                | 5        | 0.57%   |
| Qualcomm Atheros Communications | 4        | 0.46%   |
| MediaTek                        | 4        | 0.46%   |
| Broadcom Limited                | 4        | 0.46%   |
| Microsoft                       | 3        | 0.34%   |
| Edimax Technology               | 3        | 0.34%   |
| Aquantia                        | 3        | 0.34%   |
| Xiaomi                          | 2        | 0.23%   |
| Sitecom Europe                  | 2        | 0.23%   |
| NetGear                         | 2        | 0.23%   |
| Motorola PCS                    | 2        | 0.23%   |
| IMC Networks                    | 2        | 0.23%   |
| Huawei Technologies             | 2        | 0.23%   |
| BUFFALO                         | 2        | 0.23%   |
| AVM                             | 2        | 0.23%   |
| ASIX Electronics                | 2        | 0.23%   |
| Arduino SA                      | 2        | 0.23%   |
| Uniden                          | 1        | 0.11%   |
| Texas Instruments               | 1        | 0.11%   |
| Solarflare Communications       | 1        | 0.11%   |
| Sigma Designs                   | 1        | 0.11%   |
| Seeed Technology                | 1        | 0.11%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.11%   |
| Mellanox Technologies           | 1        | 0.11%   |
| Linksys                         | 1        | 0.11%   |
| LG Electronics                  | 1        | 0.11%   |
| IBM                             | 1        | 0.11%   |
| Guillemot                       | 1        | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 296      | 29.93%  |
| Intel Wi-Fi 6 AX200                                               | 38       | 3.84%   |
| Intel I211 Gigabit Network Connection                             | 35       | 3.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28       | 2.83%   |
| Intel Ethernet Connection (2) I219-V                              | 28       | 2.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25       | 2.53%   |
| Intel Ethernet Controller I225-V                                  | 16       | 1.62%   |
| Intel Ethernet Connection (7) I219-V                              | 13       | 1.31%   |
| Intel Ethernet Connection I217-LM                                 | 12       | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12       | 1.21%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11       | 1.11%   |
| Intel Ethernet Connection I217-V                                  | 10       | 1.01%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 9        | 0.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9        | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 9        | 0.91%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 9        | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9        | 0.91%   |
| Ralink MT7601U Wireless Adapter                                   | 9        | 0.91%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8        | 0.81%   |
| Intel Ethernet Connection (2) I218-V                              | 8        | 0.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 0.71%   |
| Realtek 802.11ac NIC                                              | 7        | 0.71%   |
| Intel Wireless 7260                                               | 7        | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7        | 0.71%   |
| Intel 82574L Gigabit Network Connection                           | 7        | 0.71%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 7        | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6        | 0.61%   |
| Nvidia MCP77 Ethernet                                             | 6        | 0.61%   |
| Intel Wireless-AC 9260                                            | 6        | 0.61%   |
| Intel Wireless 8265 / 8275                                        | 6        | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 0.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 5        | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5        | 0.51%   |
| Intel Wireless 7265                                               | 5        | 0.51%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5        | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 4        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 0.4%    |
| Ralink RT5370 Wireless Adapter                                    | 4        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 106      | 35.1%   |
| Realtek Semiconductor           | 63       | 20.86%  |
| Qualcomm Atheros                | 36       | 11.92%  |
| Ralink Technology               | 20       | 6.62%   |
| TP-Link                         | 18       | 5.96%   |
| Ralink                          | 11       | 3.64%   |
| Broadcom                        | 9        | 2.98%   |
| D-Link                          | 5        | 1.66%   |
| ASUSTek Computer                | 5        | 1.66%   |
| Qualcomm Atheros Communications | 4        | 1.32%   |
| Microsoft                       | 3        | 0.99%   |
| Edimax Technology               | 3        | 0.99%   |
| D-Link System                   | 3        | 0.99%   |
| Sitecom Europe                  | 2        | 0.66%   |
| NetGear                         | 2        | 0.66%   |
| IMC Networks                    | 2        | 0.66%   |
| BUFFALO                         | 2        | 0.66%   |
| AVM                             | 2        | 0.66%   |
| MediaTek                        | 1        | 0.33%   |
| Linksys                         | 1        | 0.33%   |
| Guillemot                       | 1        | 0.33%   |
| Broadcom Limited                | 1        | 0.33%   |
| Belkin Components               | 1        | 0.33%   |
| Belkin                          | 1        | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 38       | 12.46%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 12       | 3.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 9        | 2.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9        | 2.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 9        | 2.95%   |
| Ralink MT7601U Wireless Adapter                                        | 9        | 2.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 8        | 2.62%   |
| Realtek 802.11ac NIC                                                   | 7        | 2.3%    |
| Intel Wireless 7260                                                    | 7        | 2.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7        | 2.3%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 7        | 2.3%    |
| Intel Wireless-AC 9260                                                 | 6        | 1.97%   |
| Intel Wireless 8265 / 8275                                             | 6        | 1.97%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 5        | 1.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 5        | 1.64%   |
| Intel Wireless 7265                                                    | 5        | 1.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 5        | 1.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 4        | 1.31%   |
| Ralink RT5370 Wireless Adapter                                         | 4        | 1.31%   |
| Intel Wireless 8260                                                    | 4        | 1.31%   |
| TP-Link Archer T4U ver.3                                               | 3        | 0.98%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 3        | 0.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 3        | 0.98%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 3        | 0.98%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 3        | 0.98%   |
| Ralink RT2800 802.11n PCI                                              | 3        | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3        | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3        | 0.98%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 3        | 0.98%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 3        | 0.98%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 3        | 0.98%   |
| TP-Link 802.11ac NIC                                                   | 2        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2        | 0.66%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 2        | 0.66%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 2        | 0.66%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2        | 0.66%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 2        | 0.66%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                 | 2        | 0.66%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 2        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 349      | 53.2%   |
| Intel                     | 208      | 31.71%  |
| Qualcomm Atheros          | 35       | 5.34%   |
| Nvidia                    | 14       | 2.13%   |
| Broadcom                  | 12       | 1.83%   |
| Marvell Technology Group  | 6        | 0.91%   |
| Samsung Electronics       | 5        | 0.76%   |
| MediaTek                  | 3        | 0.46%   |
| Broadcom Limited          | 3        | 0.46%   |
| Aquantia                  | 3        | 0.46%   |
| Xiaomi                    | 2        | 0.3%    |
| Motorola PCS              | 2        | 0.3%    |
| Huawei Technologies       | 2        | 0.3%    |
| D-Link System             | 2        | 0.3%    |
| ASIX Electronics          | 2        | 0.3%    |
| Solarflare Communications | 1        | 0.15%   |
| Mellanox Technologies     | 1        | 0.15%   |
| LG Electronics            | 1        | 0.15%   |
| IBM                       | 1        | 0.15%   |
| Google                    | 1        | 0.15%   |
| Apple                     | 1        | 0.15%   |
| American Megatrends       | 1        | 0.15%   |
| ADMtek                    | 1        | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 296      | 43.79%  |
| Intel I211 Gigabit Network Connection                             | 35       | 5.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28       | 4.14%   |
| Intel Ethernet Connection (2) I219-V                              | 28       | 4.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25       | 3.7%    |
| Intel Ethernet Controller I225-V                                  | 16       | 2.37%   |
| Intel Ethernet Connection (7) I219-V                              | 13       | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 12       | 1.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11       | 1.63%   |
| Intel Ethernet Connection I217-V                                  | 10       | 1.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 9        | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9        | 1.33%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 1.33%   |
| Intel Ethernet Connection (2) I218-V                              | 8        | 1.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 1.04%   |
| Intel 82574L Gigabit Network Connection                           | 7        | 1.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6        | 0.89%   |
| Nvidia MCP77 Ethernet                                             | 6        | 0.89%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 0.89%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4        | 0.59%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 0.59%   |
| Intel Ethernet Connection (12) I219-V                             | 4        | 0.59%   |
| Intel 82567V-2 Gigabit Network Connection                         | 4        | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.44%   |
| Nvidia MCP61 Ethernet                                             | 3        | 0.44%   |
| MediaTek Infinix NOTE 11                                          | 3        | 0.44%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.44%   |
| Intel NM10/ICH7 Family LAN Controller                             | 3        | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.44%   |
| Intel Ethernet Connection (2) I218-LM                             | 3        | 0.44%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 0.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 0.3%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.3%    |
| Motorola PCS moto g(9) play                                       | 2        | 0.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 596      | 66.82%  |
| WiFi     | 288      | 32.29%  |
| Modem    | 6        | 0.67%   |
| Unknown  | 2        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 462      | 72.99%  |
| WiFi     | 171      | 27.01%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 365      | 59.64%  |
| 2     | 206      | 33.66%  |
| 3     | 26       | 4.25%   |
| 0     | 10       | 1.63%   |
| 5     | 3        | 0.49%   |
| 4     | 2        | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 424      | 69.06%  |
| Yes  | 190      | 30.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 92       | 39.66%  |
| Cambridge Silicon Radio         | 62       | 26.72%  |
| Realtek Semiconductor           | 20       | 8.62%   |
| ASUSTek Computer                | 13       | 5.6%    |
| Broadcom                        | 12       | 5.17%   |
| Qualcomm Atheros Communications | 8        | 3.45%   |
| IMC Networks                    | 5        | 2.16%   |
| Belkin Components               | 4        | 1.72%   |
| Dynex                           | 3        | 1.29%   |
| Apple                           | 3        | 1.29%   |
| Hewlett-Packard                 | 2        | 0.86%   |
| Unknown                         | 1        | 0.43%   |
| Ralink                          | 1        | 0.43%   |
| Qcom                            | 1        | 0.43%   |
| Primax Electronics              | 1        | 0.43%   |
| Logitech                        | 1        | 0.43%   |
| Integrated System Solution      | 1        | 0.43%   |
| Dell                            | 1        | 0.43%   |
| Conwise Technology              | 1        | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 62       | 26.72%  |
| Intel AX200 Bluetooth                                    | 32       | 13.79%  |
| Intel Bluetooth wireless interface                       | 23       | 9.91%   |
| Realtek Bluetooth Radio                                  | 17       | 7.33%   |
| Intel Wireless-AC 3168 Bluetooth                         | 11       | 4.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 9        | 3.88%   |
| Intel AX201 Bluetooth                                    | 8        | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 7        | 3.02%   |
| Qualcomm Atheros  Bluetooth Device                       | 5        | 2.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 5        | 2.16%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 5        | 2.16%   |
| ASUS Bluetooth Device                                    | 4        | 1.72%   |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 1.29%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 3        | 1.29%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 3        | 1.29%   |
| Intel AX210 Bluetooth                                    | 3        | 1.29%   |
| IMC Networks Bluetooth Radio                             | 3        | 1.29%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 3        | 1.29%   |
| Broadcom BCM2045 Bluetooth                               | 2        | 0.86%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 2        | 0.86%   |
| ASUS Bluetooth Radio                                     | 2        | 0.86%   |
| Apple Bluetooth USB Host Controller                      | 2        | 0.86%   |
| Unknown Bluetooth Device                                 | 1        | 0.43%   |
| Ralink RT3290 Bluetooth                                  | 1        | 0.43%   |
| Qcom Bluetooth USB                                       | 1        | 0.43%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter            | 1        | 0.43%   |
| Logitech BT Mini-Receiver (HCI mode)                     | 1        | 0.43%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 1        | 0.43%   |
| IMC Networks Bluetooth Device                            | 1        | 0.43%   |
| IMC Networks BCM20702A0                                  | 1        | 0.43%   |
| HP Bluetooth Dongle                                      | 1        | 0.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 1        | 0.43%   |
| Dell BT Mini-Receiver                                    | 1        | 0.43%   |
| Conwise CW6622                                           | 1        | 0.43%   |
| Broadcom BCM2210 Bluetooth                               | 1        | 0.43%   |
| Belkin Components F8T012 Bluetooth Adapter               | 1        | 0.43%   |
| Belkin Components Bluetooth Device with trace filter     | 1        | 0.43%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 1        | 0.43%   |
| ASUS Bluetooth Adapter                                   | 1        | 0.43%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 1        | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 372      | 37.35%  |
| AMD                                             | 256      | 25.7%   |
| Nvidia                                          | 253      | 25.4%   |
| C-Media Electronics                             | 20       | 2.01%   |
| Logitech                                        | 11       | 1.1%    |
| Creative Labs                                   | 10       | 1%      |
| Texas Instruments                               | 6        | 0.6%    |
| Focusrite-Novation                              | 5        | 0.5%    |
| ASUSTek Computer                                | 5        | 0.5%    |
| Kingston Technology                             | 4        | 0.4%    |
| JMTek                                           | 4        | 0.4%    |
| Plantronics                                     | 3        | 0.3%    |
| GN Netcom                                       | 3        | 0.3%    |
| SteelSeries ApS                                 | 2        | 0.2%    |
| Samson Technologies                             | 2        | 0.2%    |
| RODE Microphones                                | 2        | 0.2%    |
| Realtek Semiconductor                           | 2        | 0.2%    |
| Razer USA                                       | 2        | 0.2%    |
| Microsoft                                       | 2        | 0.2%    |
| Micro Star International                        | 2        | 0.2%    |
| GYROCOM C&C                                     | 2        | 0.2%    |
| Creative Technology                             | 2        | 0.2%    |
| Yealink Network Technology                      | 1        | 0.1%    |
| Yamaha                                          | 1        | 0.1%    |
| VIA Technologies                                | 1        | 0.1%    |
| Unknown                                         | 1        | 0.1%    |
| Sony                                            | 1        | 0.1%    |
| Sennheiser Communications                       | 1        | 0.1%    |
| Pixart Imaging                                  | 1        | 0.1%    |
| Mad Catz                                        | 1        | 0.1%    |
| Licensed by Sony Computer Entertainment America | 1        | 0.1%    |
| KYE Systems (Mouse Systems)                     | 1        | 0.1%    |
| IK Multimedia                                   | 1        | 0.1%    |
| iConnectivity                                   | 1        | 0.1%    |
| Holtek Semiconductor                            | 1        | 0.1%    |
| Generalplus Technology                          | 1        | 0.1%    |
| Fry's Electronics                               | 1        | 0.1%    |
| Elite Silicon                                   | 1        | 0.1%    |
| Earth Computer Technologies                     | 1        | 0.1%    |
| DSEA A/S                                        | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 62       | 5.36%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 51       | 4.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 46       | 3.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 42       | 3.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 41       | 3.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 33       | 2.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 31       | 2.68%   |
| Intel 200 Series PCH HD Audio                                              | 31       | 2.68%   |
| AMD Family 17h/19h HD Audio Controller                                     | 31       | 2.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 27       | 2.34%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 27       | 2.34%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 25       | 2.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 24       | 2.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 24       | 2.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 23       | 1.99%   |
| Nvidia High Definition Audio Controller                                    | 22       | 1.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 21       | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 21       | 1.82%   |
| AMD FCH Azalia Controller                                                  | 20       | 1.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 19       | 1.64%   |
| Nvidia GF108 High Definition Audio Controller                              | 16       | 1.38%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 15       | 1.3%    |
| Intel Audio device                                                         | 14       | 1.21%   |
| AMD Navi 10 HDMI Audio                                                     | 14       | 1.21%   |
| Nvidia GP106 High Definition Audio Controller                              | 13       | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 12       | 1.04%   |
| Nvidia TU104 HD Audio Controller                                           | 12       | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 12       | 1.04%   |
| Intel Comet Lake PCH-V cAVS                                                | 12       | 1.04%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 12       | 1.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12       | 1.04%   |
| Nvidia GP108 High Definition Audio Controller                              | 11       | 0.95%   |
| Nvidia GP104 High Definition Audio Controller                              | 11       | 0.95%   |
| Nvidia GM206 High Definition Audio Controller                              | 10       | 0.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9        | 0.78%   |
| Nvidia GP102 HDMI Audio Controller                                         | 8        | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                         | 8        | 0.69%   |
| Nvidia GK104 HDMI Audio Controller                                         | 8        | 0.69%   |
| Nvidia GF119 HDMI Audio Controller                                         | 8        | 0.69%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 8        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 54       | 22.31%  |
| Corsair                      | 44       | 18.18%  |
| Unknown                      | 28       | 11.57%  |
| G.Skill                      | 28       | 11.57%  |
| Crucial                      | 22       | 9.09%   |
| Samsung Electronics          | 18       | 7.44%   |
| SK hynix                     | 12       | 4.96%   |
| Micron Technology            | 8        | 3.31%   |
| Team                         | 4        | 1.65%   |
| A-DATA Technology            | 4        | 1.65%   |
| Patriot                      | 3        | 1.24%   |
| Neo Forza                    | 2        | 0.83%   |
| Wilk Elektronik              | 1        | 0.41%   |
| Vaseky                       | 1        | 0.41%   |
| Unknown (F785)               | 1        | 0.41%   |
| Unknown (ABCD)               | 1        | 0.41%   |
| Unknown (0x0702)             | 1        | 0.41%   |
| Unifosa                      | 1        | 0.41%   |
| Ramaxel Technology           | 1        | 0.41%   |
| Patriot Memory (PDP Systems) | 1        | 0.41%   |
| Nanya Technology             | 1        | 0.41%   |
| Mushkin                      | 1        | 0.41%   |
| J&A Information              | 1        | 0.41%   |
| Exceleram                    | 1        | 0.41%   |
| Elpida                       | 1        | 0.41%   |
| Avant                        | 1        | 0.41%   |
| Apacer                       | 1        | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s           | 6        | 2.21%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 4        | 1.47%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s           | 4        | 1.47%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                       | 3        | 1.1%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s               | 3        | 1.1%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s             | 3        | 1.1%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s             | 3        | 1.1%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                            | 2        | 0.74%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                            | 2        | 0.74%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 2        | 0.74%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                       | 2        | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                       | 2        | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                        | 2        | 0.74%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                            | 2        | 0.74%   |
| SK hynix RAM Module 16GB DIMM DDR4 3200MT/s                     | 2        | 0.74%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s            | 2        | 0.74%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s          | 2        | 0.74%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s            | 2        | 0.74%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s             | 2        | 0.74%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s          | 2        | 0.74%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s           | 2        | 0.74%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s           | 2        | 0.74%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s           | 2        | 0.74%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s           | 2        | 0.74%   |
| Kingston RAM 9905471-064.A00LF 8GB DIMM DDR3 1600MT/s           | 2        | 0.74%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s          | 2        | 0.74%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s             | 2        | 0.74%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s           | 2        | 0.74%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s          | 2        | 0.74%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s          | 2        | 0.74%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s           | 2        | 0.74%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s           | 2        | 0.74%   |
| Wilk Elektronik RAM IRP3600D4V64L17/16G 16GB DIMM DDR4 3600MT/s | 1        | 0.37%   |
| Vaseky RAM CT4G4DFS824A.C8FBD2 4GB DIMM DDR4 2400MT/s           | 1        | 0.37%   |
| Unknown RAM V02D4L84GB5285282400 4096MB DIMM DDR4 2400MT/s      | 1        | 0.37%   |
| Unknown RAM Module 512MB DIMM DDR 266MT/s                       | 1        | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                       | 1        | 0.37%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                            | 1        | 0.37%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                            | 1        | 0.37%   |
| Unknown RAM Module 2GB DIMM SDRAM                               | 1        | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 119      | 54.84%  |
| DDR3    | 69       | 31.8%   |
| Unknown | 9        | 4.15%   |
| DDR2    | 8        | 3.69%   |
| SDRAM   | 5        | 2.3%    |
| DDR     | 5        | 2.3%    |
| LPDDR4  | 2        | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 209      | 97.21%  |
| SODIMM | 6        | 2.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 94       | 39.83%  |
| 4096  | 51       | 21.61%  |
| 16384 | 41       | 17.37%  |
| 2048  | 27       | 11.44%  |
| 32768 | 17       | 7.2%    |
| 1024  | 4        | 1.69%   |
| 512   | 2        | 0.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 35       | 14.52%  |
| 1333    | 33       | 13.69%  |
| 3200    | 32       | 13.28%  |
| 3600    | 23       | 9.54%   |
| 2400    | 13       | 5.39%   |
| 2133    | 12       | 4.98%   |
| 2667    | 10       | 4.15%   |
| 3466    | 9        | 3.73%   |
| 3000    | 9        | 3.73%   |
| 3400    | 6        | 2.49%   |
| 800     | 6        | 2.49%   |
| 2800    | 5        | 2.07%   |
| 2666    | 5        | 2.07%   |
| 3733    | 4        | 1.66%   |
| 1867    | 4        | 1.66%   |
| 667     | 4        | 1.66%   |
| 3866    | 3        | 1.24%   |
| 3800    | 3        | 1.24%   |
| 1066    | 3        | 1.24%   |
| Unknown | 3        | 1.24%   |
| 3334    | 2        | 0.83%   |
| 2933    | 2        | 0.83%   |
| 2048    | 2        | 0.83%   |
| 333     | 2        | 0.83%   |
| 3500    | 1        | 0.41%   |
| 3100    | 1        | 0.41%   |
| 3066    | 1        | 0.41%   |
| 2934    | 1        | 0.41%   |
| 1866    | 1        | 0.41%   |
| 1800    | 1        | 0.41%   |
| 1648    | 1        | 0.41%   |
| 1400    | 1        | 0.41%   |
| 1334    | 1        | 0.41%   |
| 400     | 1        | 0.41%   |
| 266     | 1        | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Hewlett-Packard                    | 16       | 36.36%  |
| Canon                              | 8        | 18.18%  |
| Brother Industries                 | 6        | 13.64%  |
| Seiko Epson                        | 3        | 6.82%   |
| Samsung Electronics                | 3        | 6.82%   |
| Kyocera                            | 2        | 4.55%   |
| Dymo-CoStar                        | 2        | 4.55%   |
| Zebra                              | 1        | 2.27%   |
| Xerox                              | 1        | 2.27%   |
| Lexmark International              | 1        | 2.27%   |
| BeiJing LanXum Computer Technology | 1        | 2.27%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| HP DeskJet 3700 series                                 | 2        | 4.55%   |
| Canon PIXMA MG3600 Series                              | 2        | 4.55%   |
| Brother HL-5250DN Printer                              | 2        | 4.55%   |
| Zebra LP2844 Printer                                   | 1        | 2.27%   |
| Xerox WorkCentre 3119 Series                           | 1        | 2.27%   |
| Seiko Epson WF-2510 Series                             | 1        | 2.27%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1        | 2.27%   |
| Seiko Epson ET-2600 Series                             | 1        | 2.27%   |
| Samsung SCX-3400 Series                                | 1        | 2.27%   |
| Samsung ML-1450                                        | 1        | 2.27%   |
| Samsung Composite Device                               | 1        | 2.27%   |
| Lexmark International Lexmark MC2425adw                | 1        | 2.27%   |
| Kyocera FS-3920DN                                      | 1        | 2.27%   |
| Kyocera FS-1370DN                                      | 1        | 2.27%   |
| HP OfficeJet 6950                                      | 1        | 2.27%   |
| HP Officejet 4500 G510g-m                              | 1        | 2.27%   |
| HP LaserJet Professional P1102w                        | 1        | 2.27%   |
| HP LaserJet P1005                                      | 1        | 2.27%   |
| HP LaserJet M14-M17                                    | 1        | 2.27%   |
| HP LaserJet 3050                                       | 1        | 2.27%   |
| HP LaserJet 1020                                       | 1        | 2.27%   |
| HP LaserJet 1010                                       | 1        | 2.27%   |
| HP ENVY Photo 6200 series                              | 1        | 2.27%   |
| HP ENVY 5000 series                                    | 1        | 2.27%   |
| HP DeskJet Plus 4100 series                            | 1        | 2.27%   |
| HP Deskjet F4500 series                                | 1        | 2.27%   |
| HP DeskJet 970c/970cse                                 | 1        | 2.27%   |
| HP Deskjet 3050 J610 series                            | 1        | 2.27%   |
| Dymo-CoStar LabelWriter 400                            | 1        | 2.27%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                 | 1        | 2.27%   |
| Canon TS8000 series                                    | 1        | 2.27%   |
| Canon TR4500 series                                    | 1        | 2.27%   |
| Canon PRO-100 series                                   | 1        | 2.27%   |
| Canon PIXMA iP5300 Printer                             | 1        | 2.27%   |
| Canon LBP6030w/6018w                                   | 1        | 2.27%   |
| Canon iP8700 series                                    | 1        | 2.27%   |
| Brother QL-550 printer                                 | 1        | 2.27%   |
| Brother Printer                                        | 1        | 2.27%   |
| Brother MFC-J480DW                                     | 1        | 2.27%   |
| Brother DCP-L2540DW                                    | 1        | 2.27%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 8        | 88.89%  |
| Mustek Systems | 1        | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30      | 3        | 33.33%  |
| Canon CanoScan LiDE 120            | 2        | 22.22%  |
| Mustek Systems BearPaw 2448 CU Pro | 1        | 11.11%  |
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 11.11%  |
| Canon CanoScan LiDE 700F           | 1        | 11.11%  |
| Canon CanoScan LiDE 210            | 1        | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 47       | 33.57%  |
| Microdia                      | 17       | 12.14%  |
| Sunplus Innovation Technology | 9        | 6.43%   |
| Microsoft                     | 7        | 5%      |
| Realtek Semiconductor         | 5        | 3.57%   |
| Generalplus Technology        | 5        | 3.57%   |
| Samsung Electronics           | 4        | 2.86%   |
| HD 2MP WEBCAM                 | 4        | 2.86%   |
| Z-Star Microelectronics       | 3        | 2.14%   |
| GEMBIRD                       | 3        | 2.14%   |
| Cubeternet                    | 3        | 2.14%   |
| Apple                         | 3        | 2.14%   |
| IMC Networks                  | 2        | 1.43%   |
| Guillemot                     | 2        | 1.43%   |
| Creative Technology           | 2        | 1.43%   |
| Chicony Electronics           | 2        | 1.43%   |
| AVerMedia Technologies        | 2        | 1.43%   |
| ARC International             | 2        | 1.43%   |
| Xiongmai                      | 1        | 0.71%   |
| Trust                         | 1        | 0.71%   |
| Syntek                        | 1        | 0.71%   |
| Razer USA                     | 1        | 0.71%   |
| PrehKeyTec                    | 1        | 0.71%   |
| Polycom                       | 1        | 0.71%   |
| Philips (or NXP)              | 1        | 0.71%   |
| Motorola PCS                  | 1        | 0.71%   |
| Magic Control Technology      | 1        | 0.71%   |
| MacroSilicon                  | 1        | 0.71%   |
| Jieli Technology              | 1        | 0.71%   |
| IPEVO                         | 1        | 0.71%   |
| Huawei Technologies           | 1        | 0.71%   |
| Genesys Logic                 | 1        | 0.71%   |
| Etron Technology              | 1        | 0.71%   |
| Aveo Technology               | 1        | 0.71%   |
| Arkmicro Technologies         | 1        | 0.71%   |
| ANYKA                         | 1        | 0.71%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 13       | 9.22%   |
| Logitech HD Webcam C525                           | 7        | 4.96%   |
| Sunplus SPCA2650 AV Camera                        | 5        | 3.55%   |
| Microdia Webcam Vitade AF                         | 5        | 3.55%   |
| Microdia USB 2.0 Camera                           | 5        | 3.55%   |
| Microdia Camera                                   | 5        | 3.55%   |
| Samsung Galaxy A5 (MTP)                           | 4        | 2.84%   |
| Logitech Webcam C310                              | 4        | 2.84%   |
| Logitech HD Pro Webcam C920                       | 4        | 2.84%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                       | 4        | 2.84%   |
| Logitech C922 Pro Stream Webcam                   | 3        | 2.13%   |
| Generalplus GENERAL WEBCAM                        | 3        | 2.13%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 3        | 2.13%   |
| Realtek NexiGo N660P FHD Webcam                   | 2        | 1.42%   |
| Realtek Full HD webcam                            | 2        | 1.42%   |
| Logitech Webcam Pro 9000                          | 2        | 1.42%   |
| Logitech Webcam C210                              | 2        | 1.42%   |
| Logitech HD Webcam C910                           | 2        | 1.42%   |
| Logitech BRIO Ultra HD Webcam                     | 2        | 1.42%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 2        | 1.42%   |
| Cubeternet USB2.0 Camera                          | 2        | 1.42%   |
| AVerMedia Live Streamer CAM 313                   | 2        | 1.42%   |
| ARC International Camera                          | 2        | 1.42%   |
| Apple iPhone5/5C/5S/6                             | 2        | 1.42%   |
| Z-Star Vimicro USB2.0 UVC PC Camera               | 1        | 0.71%   |
| Z-Star Vimicro USB Camera (Altair)                | 1        | 0.71%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 1        | 0.71%   |
| Xiongmai web camera                               | 1        | 0.71%   |
| Trust 17676 Webcam                                | 1        | 0.71%   |
| Syntek USB Video Device                           | 1        | 0.71%   |
| Sunplus Full HD webcam                            | 1        | 0.71%   |
| Sunplus Aukey-PC-LM1E Camera                      | 1        | 0.71%   |
| Sunplus AUKEY PC-LM1E Camera                      | 1        | 0.71%   |
| Sunplus AAPDQT-0622-W                             | 1        | 0.71%   |
| Realtek USB Camera                                | 1        | 0.71%   |
| Razer USA Gaming Webcam [Kiyo]                    | 1        | 0.71%   |
| PrehKeyTec TA-0120-AS                             | 1        | 0.71%   |
| Polycom Poly Studio P15                           | 1        | 0.71%   |
| Philips (or NXP) SPC 520/525NC PC Camera          | 1        | 0.71%   |
| Motorola PCS XT1033 [Moto G], PTP mode            | 1        | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Elan Microelectronics      | 3        | 60%     |
| Shenzhen Goodix Technology | 1        | 20%     |
| Dell                       | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]    | 3        | 60%     |
| Shenzhen Goodix Fingerprint Reader             | 1        | 20%     |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 1        | 50%     |
| Advanced Card Systems | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |
| Advanced Card Systems ACR38 SmartCard Reader      | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 528      | 85.71%  |
| 1     | 77       | 12.5%   |
| 2     | 10       | 1.62%   |
| 3     | 1        | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 29       | 29.29%  |
| Graphics card            | 29       | 29.29%  |
| Unassigned class         | 12       | 12.12%  |
| Sound                    | 4        | 4.04%   |
| Multimedia controller    | 4        | 4.04%   |
| Fingerprint reader       | 4        | 4.04%   |
| Communication controller | 4        | 4.04%   |
| Camera                   | 4        | 4.04%   |
| Storage/raid             | 2        | 2.02%   |
| Card reader              | 2        | 2.02%   |
| Bluetooth                | 2        | 2.02%   |
| Network                  | 1        | 1.01%   |
| Dvb card                 | 1        | 1.01%   |
| Chipcard                 | 1        | 1.01%   |

