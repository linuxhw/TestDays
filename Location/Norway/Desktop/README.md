Linux in Norway - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Norway.

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

Total: 445

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | X99A RAIDER                 | [5fe6f7eb57](https://linux-hardware.org/?probe=5fe6f7eb57) | Aug 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8ea1e0f22c](https://linux-hardware.org/?probe=8ea1e0f22c) | Aug 01, 2022 |
| MSI           | X99A RAIDER                 | [76a30e3042](https://linux-hardware.org/?probe=76a30e3042) | Jul 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9dd9d17e79](https://linux-hardware.org/?probe=9dd9d17e79) | Jul 31, 2022 |
| MSI           | X99A RAIDER                 | [ebfa3daff5](https://linux-hardware.org/?probe=ebfa3daff5) | Jul 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9a7de8cc64](https://linux-hardware.org/?probe=9a7de8cc64) | Jul 30, 2022 |
| Intel         | TR440BXA A16643-311         | [e6245255f4](https://linux-hardware.org/?probe=e6245255f4) | Jul 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c0ce536184](https://linux-hardware.org/?probe=c0ce536184) | Jul 29, 2022 |
| MSI           | X99A RAIDER                 | [d5034f5f52](https://linux-hardware.org/?probe=d5034f5f52) | Jul 29, 2022 |
| ASRock        | H77M-ITX                    | [ca0d4b7108](https://linux-hardware.org/?probe=ca0d4b7108) | Jul 28, 2022 |
| ASUSTek       | VC65                        | [b43ad009f1](https://linux-hardware.org/?probe=b43ad009f1) | Jul 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a9c3256946](https://linux-hardware.org/?probe=a9c3256946) | Jul 28, 2022 |
| MSI           | X99A RAIDER                 | [db30ba1d0e](https://linux-hardware.org/?probe=db30ba1d0e) | Jul 28, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [e214df8838](https://linux-hardware.org/?probe=e214df8838) | Jul 27, 2022 |
| ASRock        | H77M-ITX                    | [78a53c9be0](https://linux-hardware.org/?probe=78a53c9be0) | Jul 26, 2022 |
| ASRock        | H77M-ITX                    | [8c749dd7e6](https://linux-hardware.org/?probe=8c749dd7e6) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2632256ed7](https://linux-hardware.org/?probe=2632256ed7) | Jul 25, 2022 |
| MSI           | X99A RAIDER                 | [57beac41bc](https://linux-hardware.org/?probe=57beac41bc) | Jul 25, 2022 |
| MSI           | X99A RAIDER                 | [79d402e1ff](https://linux-hardware.org/?probe=79d402e1ff) | Jul 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8bb191bc8f](https://linux-hardware.org/?probe=8bb191bc8f) | Jul 24, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [aa2242c51f](https://linux-hardware.org/?probe=aa2242c51f) | Jul 23, 2022 |
| MSI           | X99A RAIDER                 | [7a33ccf211](https://linux-hardware.org/?probe=7a33ccf211) | Jul 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9c1f5f7a4e](https://linux-hardware.org/?probe=9c1f5f7a4e) | Jul 23, 2022 |
| MSI           | X99A RAIDER                 | [347ff14d90](https://linux-hardware.org/?probe=347ff14d90) | Jul 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d758abd21c](https://linux-hardware.org/?probe=d758abd21c) | Jul 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b54cb1f930](https://linux-hardware.org/?probe=b54cb1f930) | Jul 21, 2022 |
| MSI           | X99A RAIDER                 | [a671047cb4](https://linux-hardware.org/?probe=a671047cb4) | Jul 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8cae76caea](https://linux-hardware.org/?probe=8cae76caea) | Jul 20, 2022 |
| MSI           | X99A RAIDER                 | [05a5bc0fa8](https://linux-hardware.org/?probe=05a5bc0fa8) | Jul 20, 2022 |
| MSI           | X99A RAIDER                 | [108d31db10](https://linux-hardware.org/?probe=108d31db10) | Jul 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ce2e8f2a2a](https://linux-hardware.org/?probe=ce2e8f2a2a) | Jul 12, 2022 |
| MSI           | X99A RAIDER                 | [7ce0875267](https://linux-hardware.org/?probe=7ce0875267) | Jul 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [84f993f04d](https://linux-hardware.org/?probe=84f993f04d) | Jul 11, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [1bec4af414](https://linux-hardware.org/?probe=1bec4af414) | Jul 02, 2022 |
| MSI           | X99A RAIDER                 | [e6eeb4dfe6](https://linux-hardware.org/?probe=e6eeb4dfe6) | Jul 02, 2022 |
| MSI           | X99A RAIDER                 | [e1c3d1dfad](https://linux-hardware.org/?probe=e1c3d1dfad) | Jul 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a658ebf5e9](https://linux-hardware.org/?probe=a658ebf5e9) | Jul 01, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [a082da0857](https://linux-hardware.org/?probe=a082da0857) | Jun 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [163a5c29e6](https://linux-hardware.org/?probe=163a5c29e6) | Jun 30, 2022 |
| MSI           | X99A RAIDER                 | [2da2ad735c](https://linux-hardware.org/?probe=2da2ad735c) | Jun 30, 2022 |
| MSI           | X99A RAIDER                 | [b197a0fd35](https://linux-hardware.org/?probe=b197a0fd35) | Jun 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [66b8ec6b28](https://linux-hardware.org/?probe=66b8ec6b28) | Jun 29, 2022 |
| MSI           | P67A-C45                    | [79a2dd2b27](https://linux-hardware.org/?probe=79a2dd2b27) | Jun 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4801136187](https://linux-hardware.org/?probe=4801136187) | Jun 18, 2022 |
| MSI           | X99A RAIDER                 | [550772184f](https://linux-hardware.org/?probe=550772184f) | Jun 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [f54dda344d](https://linux-hardware.org/?probe=f54dda344d) | Jun 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [680bf4c033](https://linux-hardware.org/?probe=680bf4c033) | Jun 17, 2022 |
| MSI           | X99A RAIDER                 | [184ad2670a](https://linux-hardware.org/?probe=184ad2670a) | Jun 17, 2022 |
| MSI           | X99A RAIDER                 | [6b279160dc](https://linux-hardware.org/?probe=6b279160dc) | Jun 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [7990c32699](https://linux-hardware.org/?probe=7990c32699) | Jun 14, 2022 |
| MSI           | X99A RAIDER                 | [2f784679b0](https://linux-hardware.org/?probe=2f784679b0) | Jun 13, 2022 |
| ASRock        | FM2A88X Extreme6+           | [dcd3256961](https://linux-hardware.org/?probe=dcd3256961) | Jun 13, 2022 |
| MSI           | P67A-C45                    | [86fc259ec4](https://linux-hardware.org/?probe=86fc259ec4) | Jun 07, 2022 |
| MSI           | X99A RAIDER                 | [34e068e6ad](https://linux-hardware.org/?probe=34e068e6ad) | Jun 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5a835b2aa6](https://linux-hardware.org/?probe=5a835b2aa6) | Jun 07, 2022 |
| MSI           | X99A RAIDER                 | [9dc558e0e2](https://linux-hardware.org/?probe=9dc558e0e2) | Jun 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [838e0b8e42](https://linux-hardware.org/?probe=838e0b8e42) | Jun 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [cb07ae6e24](https://linux-hardware.org/?probe=cb07ae6e24) | Jun 02, 2022 |
| MSI           | X99A RAIDER                 | [97428f0f4d](https://linux-hardware.org/?probe=97428f0f4d) | Jun 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [dd51d706e3](https://linux-hardware.org/?probe=dd51d706e3) | Jun 01, 2022 |
| MSI           | X99A RAIDER                 | [0b16a52ca1](https://linux-hardware.org/?probe=0b16a52ca1) | Jun 01, 2022 |
| Unknown       | Unknown                     | [c2d6d647d8](https://linux-hardware.org/?probe=c2d6d647d8) | May 31, 2022 |
| MSI           | X99A RAIDER                 | [8794ca2ca9](https://linux-hardware.org/?probe=8794ca2ca9) | May 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [85a456dd94](https://linux-hardware.org/?probe=85a456dd94) | May 31, 2022 |
| Unknown       | Unknown                     | [59d0634230](https://linux-hardware.org/?probe=59d0634230) | May 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ff73ff1ea6](https://linux-hardware.org/?probe=ff73ff1ea6) | May 30, 2022 |
| MSI           | X99A RAIDER                 | [e6fc3ad487](https://linux-hardware.org/?probe=e6fc3ad487) | May 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [3487c76d47](https://linux-hardware.org/?probe=3487c76d47) | May 29, 2022 |
| MSI           | X99A RAIDER                 | [1783c56618](https://linux-hardware.org/?probe=1783c56618) | May 29, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [db4eade79e](https://linux-hardware.org/?probe=db4eade79e) | May 28, 2022 |
| MSI           | X99A RAIDER                 | [d83c99fb0e](https://linux-hardware.org/?probe=d83c99fb0e) | May 28, 2022 |
| MSI           | X99A RAIDER                 | [8226c07ba6](https://linux-hardware.org/?probe=8226c07ba6) | May 27, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [1fa6bb2d62](https://linux-hardware.org/?probe=1fa6bb2d62) | May 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [19d23eb25f](https://linux-hardware.org/?probe=19d23eb25f) | May 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5ea71aeb2](https://linux-hardware.org/?probe=f5ea71aeb2) | May 21, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [79682a20fa](https://linux-hardware.org/?probe=79682a20fa) | May 16, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d1dbcd7651](https://linux-hardware.org/?probe=d1dbcd7651) | May 16, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [d4e303b92c](https://linux-hardware.org/?probe=d4e303b92c) | May 15, 2022 |
| Gigabyte      | Z170-Gaming K3              | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [927afa0c20](https://linux-hardware.org/?probe=927afa0c20) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [b9766a94d7](https://linux-hardware.org/?probe=b9766a94d7) | May 11, 2022 |
| ASUSTek       | Z170-A                      | [97e2613936](https://linux-hardware.org/?probe=97e2613936) | May 08, 2022 |
| Gigabyte      | X570 GAMING X               | [ffc6dac164](https://linux-hardware.org/?probe=ffc6dac164) | May 07, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [afac7f7fb3](https://linux-hardware.org/?probe=afac7f7fb3) | May 07, 2022 |
| Gigabyte      | X570 GAMING X               | [816a78b4cd](https://linux-hardware.org/?probe=816a78b4cd) | May 06, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [6f9cfe324a](https://linux-hardware.org/?probe=6f9cfe324a) | May 05, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7d9a2b425f](https://linux-hardware.org/?probe=7d9a2b425f) | May 03, 2022 |
| MSI           | 970 GAMING                  | [32052450db](https://linux-hardware.org/?probe=32052450db) | May 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8db041a1e4](https://linux-hardware.org/?probe=8db041a1e4) | May 01, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [5456280ec0](https://linux-hardware.org/?probe=5456280ec0) | Apr 26, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b9ea98672f](https://linux-hardware.org/?probe=b9ea98672f) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [c3f809fc02](https://linux-hardware.org/?probe=c3f809fc02) | Apr 23, 2022 |
| Acer          | Predator G3610              | [a53edf84d4](https://linux-hardware.org/?probe=a53edf84d4) | Apr 22, 2022 |
| ASUSTek       | PRIME X399-A                | [e595903b64](https://linux-hardware.org/?probe=e595903b64) | Apr 18, 2022 |
| ASUSTek       | PRIME X399-A                | [b2fe9a09fd](https://linux-hardware.org/?probe=b2fe9a09fd) | Apr 17, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| MSI           | Z390-A PRO                  | [bfec30bf8d](https://linux-hardware.org/?probe=bfec30bf8d) | Apr 13, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [486b6a5d64](https://linux-hardware.org/?probe=486b6a5d64) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ec3689ffdc](https://linux-hardware.org/?probe=ec3689ffdc) | Apr 10, 2022 |
| Dell          | 0MN1TX A02                  | [cf2e65caf4](https://linux-hardware.org/?probe=cf2e65caf4) | Apr 10, 2022 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [c344a9c7b9](https://linux-hardware.org/?probe=c344a9c7b9) | Apr 10, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb6b5ebaf](https://linux-hardware.org/?probe=6eb6b5ebaf) | Apr 08, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [cf7f6c5ed4](https://linux-hardware.org/?probe=cf7f6c5ed4) | Apr 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [448e59a9a6](https://linux-hardware.org/?probe=448e59a9a6) | Apr 02, 2022 |
| Acer          | Aspire X3400                | [47097032fd](https://linux-hardware.org/?probe=47097032fd) | Mar 31, 2022 |
| Dell          | 0MN1TX A02                  | [f9be94fa9b](https://linux-hardware.org/?probe=f9be94fa9b) | Mar 31, 2022 |
| ASUSTek       | M2R-FVM                     | [94beabac6e](https://linux-hardware.org/?probe=94beabac6e) | Mar 30, 2022 |
| ASUSTek       | M2R-FVM                     | [76ec39764b](https://linux-hardware.org/?probe=76ec39764b) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [6190e57794](https://linux-hardware.org/?probe=6190e57794) | Mar 25, 2022 |
| ASUSTek       | M2R-FVM                     | [eaaef17c19](https://linux-hardware.org/?probe=eaaef17c19) | Mar 25, 2022 |
| ASUSTek       | X99-A                       | [b071309501](https://linux-hardware.org/?probe=b071309501) | Mar 23, 2022 |
| ASUSTek       | M2R-FVM                     | [eb934cc46a](https://linux-hardware.org/?probe=eb934cc46a) | Mar 23, 2022 |
| Dell          | 0YNVJG A01                  | [7a52c137cf](https://linux-hardware.org/?probe=7a52c137cf) | Mar 18, 2022 |
| MSI           | Z170A PC MATE               | [56c1c58549](https://linux-hardware.org/?probe=56c1c58549) | Mar 15, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Gigabyte      | 970A-DS3P                   | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f1b0d6e847](https://linux-hardware.org/?probe=f1b0d6e847) | Mar 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [54ae8c7668](https://linux-hardware.org/?probe=54ae8c7668) | Mar 01, 2022 |
| Gigabyte      | 970A-DS3P                   | [ad43671e4c](https://linux-hardware.org/?probe=ad43671e4c) | Mar 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9d178352ca](https://linux-hardware.org/?probe=9d178352ca) | Mar 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [9670ab829e](https://linux-hardware.org/?probe=9670ab829e) | Feb 26, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [d61754bba9](https://linux-hardware.org/?probe=d61754bba9) | Feb 26, 2022 |
| MSI           | 990FXA-GD65                 | [290919912c](https://linux-hardware.org/?probe=290919912c) | Feb 26, 2022 |
| Lenovo        | 0B98401 PRO                 | [c332efa9f8](https://linux-hardware.org/?probe=c332efa9f8) | Feb 24, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1c6d204561](https://linux-hardware.org/?probe=1c6d204561) | Feb 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [67deab7343](https://linux-hardware.org/?probe=67deab7343) | Feb 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [160ecaffd8](https://linux-hardware.org/?probe=160ecaffd8) | Feb 21, 2022 |
| ASUSTek       | SABERTOOTH P67              | [2ad209abc4](https://linux-hardware.org/?probe=2ad209abc4) | Feb 12, 2022 |
| ASUSTek       | Maximus VIII HERO           | [ef92dfd4f1](https://linux-hardware.org/?probe=ef92dfd4f1) | Feb 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ccd7847b28](https://linux-hardware.org/?probe=ccd7847b28) | Jan 30, 2022 |
| ASRock        | ION3D-HT                    | [5a4158f549](https://linux-hardware.org/?probe=5a4158f549) | Jan 29, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Intel         | D54250WYK H13922-303        | [8b6b3d70bf](https://linux-hardware.org/?probe=8b6b3d70bf) | Jan 26, 2022 |
| Gigabyte      | 970A-DS3P                   | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| ASRock        | Z87 Killer                  | [6931f1ca2f](https://linux-hardware.org/?probe=6931f1ca2f) | Jan 17, 2022 |
| MSI           | P67A-C45                    | [953176b34f](https://linux-hardware.org/?probe=953176b34f) | Jan 17, 2022 |
| ASUSTek       | P5L8L-SE                    | [459b062c3e](https://linux-hardware.org/?probe=459b062c3e) | Jan 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [7921e32637](https://linux-hardware.org/?probe=7921e32637) | Jan 14, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [7b12fb3749](https://linux-hardware.org/?probe=7b12fb3749) | Jan 14, 2022 |
| Acer          | Aspire X3400                | [6833137bc8](https://linux-hardware.org/?probe=6833137bc8) | Jan 02, 2022 |
| MSI           | H110M PRO-VH                | [a32495b8e4](https://linux-hardware.org/?probe=a32495b8e4) | Jan 02, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [b86150c4bd](https://linux-hardware.org/?probe=b86150c4bd) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [923f77a787](https://linux-hardware.org/?probe=923f77a787) | Dec 16, 2021 |
| ASUSTek       | SABERTOOTH P67              | [af2732b8a5](https://linux-hardware.org/?probe=af2732b8a5) | Dec 15, 2021 |
| ASUSTek       | TUF Gaming B550-PRO         | [62f4289baa](https://linux-hardware.org/?probe=62f4289baa) | Dec 14, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [12da1dc78f](https://linux-hardware.org/?probe=12da1dc78f) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [882e308c93](https://linux-hardware.org/?probe=882e308c93) | Dec 11, 2021 |
| ASRockRack    | ROMED8-2T                   | [87b9d0f1e5](https://linux-hardware.org/?probe=87b9d0f1e5) | Dec 04, 2021 |
| ASRockRack    | ROMED8-2T                   | [071e272398](https://linux-hardware.org/?probe=071e272398) | Dec 04, 2021 |
| ASRock        | B450M Steel Legend          | [5c0f6b8395](https://linux-hardware.org/?probe=5c0f6b8395) | Nov 28, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [fb92bb54af](https://linux-hardware.org/?probe=fb92bb54af) | Nov 28, 2021 |
| MSI           | B350M MORTAR ARCTIC         | [7c0e3a92a5](https://linux-hardware.org/?probe=7c0e3a92a5) | Nov 26, 2021 |
| ASUSTek       | ROG Maximus Z690 HERO       | [f3e1cfcdab](https://linux-hardware.org/?probe=f3e1cfcdab) | Nov 26, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [846877b55f](https://linux-hardware.org/?probe=846877b55f) | Nov 25, 2021 |
| MSI           | H170 GAMING M3              | [e9a754ed5c](https://linux-hardware.org/?probe=e9a754ed5c) | Nov 24, 2021 |
| Gigabyte      | Z170-Gaming K3              | [496b525711](https://linux-hardware.org/?probe=496b525711) | Nov 24, 2021 |
| ASRock        | X99M Extreme4               | [3f738eedfc](https://linux-hardware.org/?probe=3f738eedfc) | Nov 22, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [756684e469](https://linux-hardware.org/?probe=756684e469) | Nov 20, 2021 |
| Acer          | EG43M                       | [03dc3c8d61](https://linux-hardware.org/?probe=03dc3c8d61) | Nov 20, 2021 |
| ASUSTek       | P8Z77-V LX                  | [6807e3fa8c](https://linux-hardware.org/?probe=6807e3fa8c) | Nov 18, 2021 |
| HP            | 8056                        | [f62a924908](https://linux-hardware.org/?probe=f62a924908) | Nov 16, 2021 |
| Gigabyte      | H87N-WIFI                   | [b19a68b774](https://linux-hardware.org/?probe=b19a68b774) | Nov 13, 2021 |
| MSI           | B75MA-P45                   | [8196870f95](https://linux-hardware.org/?probe=8196870f95) | Nov 11, 2021 |
| Gigabyte      | F2A78M-D3H                  | [43e09b8e80](https://linux-hardware.org/?probe=43e09b8e80) | Nov 05, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [4615791bf1](https://linux-hardware.org/?probe=4615791bf1) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | [0cc8ca1a78](https://linux-hardware.org/?probe=0cc8ca1a78) | Oct 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [688a36c9df](https://linux-hardware.org/?probe=688a36c9df) | Oct 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [ccce1ad4e4](https://linux-hardware.org/?probe=ccce1ad4e4) | Oct 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [a96916c86f](https://linux-hardware.org/?probe=a96916c86f) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| MSI           | Z77A-GD65                   | [5273767a7e](https://linux-hardware.org/?probe=5273767a7e) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | [f4442e94e7](https://linux-hardware.org/?probe=f4442e94e7) | Oct 21, 2021 |
| HP            | 1998                        | [db3a3fbce2](https://linux-hardware.org/?probe=db3a3fbce2) | Oct 21, 2021 |
| Pegatron      | 2AC3                        | [ae8b02d9cb](https://linux-hardware.org/?probe=ae8b02d9cb) | Oct 21, 2021 |
| ASUSTek       | PRIME B460M-A               | [6db5e9be6b](https://linux-hardware.org/?probe=6db5e9be6b) | Oct 19, 2021 |
| Dell          | 0D28YY A02                  | [237a82041b](https://linux-hardware.org/?probe=237a82041b) | Oct 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [bc7f078524](https://linux-hardware.org/?probe=bc7f078524) | Oct 07, 2021 |
| Packard Be... | IXTREME M5120               | [315bbefc53](https://linux-hardware.org/?probe=315bbefc53) | Oct 06, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c9022127a9](https://linux-hardware.org/?probe=c9022127a9) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [99b237ae08](https://linux-hardware.org/?probe=99b237ae08) | Oct 02, 2021 |
| HP            | 8056                        | [2199f7a715](https://linux-hardware.org/?probe=2199f7a715) | Sep 26, 2021 |
| ASUSTek       | PRIME B350M-A               | [3808823182](https://linux-hardware.org/?probe=3808823182) | Sep 23, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [f28906612f](https://linux-hardware.org/?probe=f28906612f) | Sep 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [17ad477c6f](https://linux-hardware.org/?probe=17ad477c6f) | Sep 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [a122cb5006](https://linux-hardware.org/?probe=a122cb5006) | Sep 19, 2021 |
| Acer          | EG43M                       | [03cff58061](https://linux-hardware.org/?probe=03cff58061) | Sep 17, 2021 |
| HP            | 8056                        | [61c50556d0](https://linux-hardware.org/?probe=61c50556d0) | Sep 13, 2021 |
| ASUSTek       | Z170-A                      | [630fec5a83](https://linux-hardware.org/?probe=630fec5a83) | Sep 11, 2021 |
| Gigabyte      | J3455N-D3H                  | [24bc89b42a](https://linux-hardware.org/?probe=24bc89b42a) | Aug 31, 2021 |
| HP            | 0B40h                       | [da95bc989c](https://linux-hardware.org/?probe=da95bc989c) | Aug 30, 2021 |
| Supermicro    | X10DAI                      | [078ab4c114](https://linux-hardware.org/?probe=078ab4c114) | Aug 24, 2021 |
| ASRock        | X370 Gaming-ITX/ac          | [5909ea8d8d](https://linux-hardware.org/?probe=5909ea8d8d) | Aug 20, 2021 |
| HP            | 802E                        | [35a2f000fd](https://linux-hardware.org/?probe=35a2f000fd) | Aug 19, 2021 |
| ASUSTek       | B150M-C                     | [794387ddd6](https://linux-hardware.org/?probe=794387ddd6) | Aug 16, 2021 |
| ASUSTek       | PRIME Z270-A                | [eaac722778](https://linux-hardware.org/?probe=eaac722778) | Aug 16, 2021 |
| ASUSTek       | PRIME Z270-A                | [a24db8e84d](https://linux-hardware.org/?probe=a24db8e84d) | Aug 16, 2021 |
| ASUSTek       | PRIME Z270-A                | [51b28dbd02](https://linux-hardware.org/?probe=51b28dbd02) | Aug 16, 2021 |
| Acer          | Aspire X3400                | [0a158e8bce](https://linux-hardware.org/?probe=0a158e8bce) | Aug 13, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [034630b7f9](https://linux-hardware.org/?probe=034630b7f9) | Aug 11, 2021 |
| Acer          | Aspire X3400                | [6836f60d13](https://linux-hardware.org/?probe=6836f60d13) | Aug 11, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | [a1768aa578](https://linux-hardware.org/?probe=a1768aa578) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | [52aa712b0c](https://linux-hardware.org/?probe=52aa712b0c) | Aug 05, 2021 |
| HP            | 3397                        | [d5add95307](https://linux-hardware.org/?probe=d5add95307) | Aug 05, 2021 |
| ASRock        | Z370M-ITX/ac                | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| Wibtek        | TH61G-S                     | [346ae2c85d](https://linux-hardware.org/?probe=346ae2c85d) | Jul 29, 2021 |
| HP            | 87D6 SMVB                   | [77f9eee003](https://linux-hardware.org/?probe=77f9eee003) | Jul 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [88d668c3ab](https://linux-hardware.org/?probe=88d668c3ab) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| ASRock        | B450 Gaming K4              | [563a58b492](https://linux-hardware.org/?probe=563a58b492) | Jul 24, 2021 |
| ASRock        | X570 Steel Legend           | [6f026a93d1](https://linux-hardware.org/?probe=6f026a93d1) | Jul 17, 2021 |
| ASRock        | X570 Steel Legend           | [af12b529b0](https://linux-hardware.org/?probe=af12b529b0) | Jul 17, 2021 |
| Gigabyte      | B550 AORUS MASTER           | [35bf19b527](https://linux-hardware.org/?probe=35bf19b527) | Jul 13, 2021 |
| HP            | 872B                        | [319ce0e306](https://linux-hardware.org/?probe=319ce0e306) | Jul 13, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [ef051fc485](https://linux-hardware.org/?probe=ef051fc485) | Jul 04, 2021 |
| HP            | 1998                        | [8f095c8449](https://linux-hardware.org/?probe=8f095c8449) | Jul 01, 2021 |
| ASUSTek       | P5G41T-M                    | [8553d8a919](https://linux-hardware.org/?probe=8553d8a919) | Jun 30, 2021 |
| ASUSTek       | M5A97 R2.0                  | [04c4ddf9b0](https://linux-hardware.org/?probe=04c4ddf9b0) | Jun 29, 2021 |
| Acer          | EG43LMK                     | [5df39d6ba0](https://linux-hardware.org/?probe=5df39d6ba0) | Jun 26, 2021 |
| MSI           | B85M-E45                    | [5508d6a84e](https://linux-hardware.org/?probe=5508d6a84e) | Jun 23, 2021 |
| MSI           | B75MA-P45                   | [0ccd0cdf44](https://linux-hardware.org/?probe=0ccd0cdf44) | Jun 15, 2021 |
| Dell          | 02YYK5 A01                  | [74a4b076a9](https://linux-hardware.org/?probe=74a4b076a9) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [8081e6a752](https://linux-hardware.org/?probe=8081e6a752) | Jun 12, 2021 |
| ASUSTek       | X99-DELUXE                  | [382c24055c](https://linux-hardware.org/?probe=382c24055c) | Jun 09, 2021 |
| Lenovo        | SDK0E50510 WIN              | [9cfdd32388](https://linux-hardware.org/?probe=9cfdd32388) | Jun 04, 2021 |
| ASUSTek       | PRIME B460M-A               | [5125306d59](https://linux-hardware.org/?probe=5125306d59) | May 31, 2021 |
| ASUSTek       | M5A97 R2.0                  | [f0145b568f](https://linux-hardware.org/?probe=f0145b568f) | May 27, 2021 |
| ASUSTek       | Maximus VIII HERO           | [4550202db3](https://linux-hardware.org/?probe=4550202db3) | May 15, 2021 |
| Gigabyte      | GA-970A-UD3                 | [1cf830acd9](https://linux-hardware.org/?probe=1cf830acd9) | May 13, 2021 |
| Gigabyte      | X99-UD7 WIFI-CF             | [87d92ce1b4](https://linux-hardware.org/?probe=87d92ce1b4) | May 08, 2021 |
| Gigabyte      | X99-UD7 WIFI-CF             | [766557aeb8](https://linux-hardware.org/?probe=766557aeb8) | May 07, 2021 |
| Dell          | 0M9KCM A02                  | [c016fc8897](https://linux-hardware.org/?probe=c016fc8897) | May 03, 2021 |
| ASUSTek       | PRIME Z490-A                | [af5179a1f9](https://linux-hardware.org/?probe=af5179a1f9) | Apr 30, 2021 |
| Dell          | 02YYK5 A01                  | [bd1254fe8d](https://linux-hardware.org/?probe=bd1254fe8d) | Apr 28, 2021 |
| MSI           | Z97S SLI Krait Edition      | [afb9057dda](https://linux-hardware.org/?probe=afb9057dda) | Apr 16, 2021 |
| ASRock        | X470 Taichi Ultimate        | [7ab07ae1e9](https://linux-hardware.org/?probe=7ab07ae1e9) | Apr 11, 2021 |
| ASRock        | X470 Taichi Ultimate        | [174dc97643](https://linux-hardware.org/?probe=174dc97643) | Apr 11, 2021 |
| Gigabyte      | B450M DS3H-CF               | [2116d4313c](https://linux-hardware.org/?probe=2116d4313c) | Apr 11, 2021 |
| Dell          | 0WMJ54 A01                  | [59c7b4d6ff](https://linux-hardware.org/?probe=59c7b4d6ff) | Apr 10, 2021 |
| ASUSTek       | F2A85-M                     | [9548d9f0c6](https://linux-hardware.org/?probe=9548d9f0c6) | Apr 06, 2021 |
| ASUSTek       | PRIME Z490-A                | [9db70676f4](https://linux-hardware.org/?probe=9db70676f4) | Apr 05, 2021 |
| HP            | 1790                        | [d03e7a12c6](https://linux-hardware.org/?probe=d03e7a12c6) | Apr 04, 2021 |
| Gigabyte      | X570 AORUS XTREME           | [39f6ad5463](https://linux-hardware.org/?probe=39f6ad5463) | Apr 04, 2021 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | [393b9a2647](https://linux-hardware.org/?probe=393b9a2647) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [6a1ee4ca94](https://linux-hardware.org/?probe=6a1ee4ca94) | Mar 31, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [394a2510d4](https://linux-hardware.org/?probe=394a2510d4) | Mar 31, 2021 |
| Cisco Syst... | UCSB-B200-M4 73-15862-03    | [4c55de0b30](https://linux-hardware.org/?probe=4c55de0b30) | Mar 31, 2021 |
| ASRock        | B450M Pro4-F                | [c7223020fe](https://linux-hardware.org/?probe=c7223020fe) | Mar 25, 2021 |
| ASUSTek       | PRIME X470-PRO              | [c3f70afbd8](https://linux-hardware.org/?probe=c3f70afbd8) | Mar 18, 2021 |
| ASUSTek       | M4A79T Deluxe               | [2ccff038d2](https://linux-hardware.org/?probe=2ccff038d2) | Mar 16, 2021 |
| HP            | 802F                        | [9ea8632891](https://linux-hardware.org/?probe=9ea8632891) | Mar 14, 2021 |
| MSI           | X99A RAIDER                 | [6f27ffd7aa](https://linux-hardware.org/?probe=6f27ffd7aa) | Mar 13, 2021 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [9625a9c184](https://linux-hardware.org/?probe=9625a9c184) | Feb 26, 2021 |
| Dell          | 0NK70N A03                  | [5354c0cb90](https://linux-hardware.org/?probe=5354c0cb90) | Feb 22, 2021 |
| HP            | 2B35                        | [ab5c723699](https://linux-hardware.org/?probe=ab5c723699) | Feb 20, 2021 |
| MSI           | MEG X570 UNIFY              | [455cf08e86](https://linux-hardware.org/?probe=455cf08e86) | Feb 20, 2021 |
| Dell          | 0MN1TX A01                  | [ebc826cccc](https://linux-hardware.org/?probe=ebc826cccc) | Feb 18, 2021 |
| Acer          | Predator G3-605             | [f1a8ae2c26](https://linux-hardware.org/?probe=f1a8ae2c26) | Feb 17, 2021 |
| ASUSTek       | ROG STRIX B460-F GAMING     | [c445cf637b](https://linux-hardware.org/?probe=c445cf637b) | Feb 15, 2021 |
| MSI           | X299 SLI PLUS               | [1499657b8c](https://linux-hardware.org/?probe=1499657b8c) | Feb 13, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [743d5820cc](https://linux-hardware.org/?probe=743d5820cc) | Feb 13, 2021 |
| ASRock        | X570 Taichi                 | [96d6904297](https://linux-hardware.org/?probe=96d6904297) | Feb 01, 2021 |
| ASUSTek       | P8Z77-M                     | [d60b967710](https://linux-hardware.org/?probe=d60b967710) | Jan 22, 2021 |
| Dell          | 00V62H A00                  | [3d8b11fbf3](https://linux-hardware.org/?probe=3d8b11fbf3) | Jan 20, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [7a840d41b2](https://linux-hardware.org/?probe=7a840d41b2) | Jan 19, 2021 |
| MSI           | MAG B550M MORTAR            | [0900f71645](https://linux-hardware.org/?probe=0900f71645) | Jan 17, 2021 |
| ASUSTek       | PRIME Z270-P                | [d3150c1175](https://linux-hardware.org/?probe=d3150c1175) | Jan 14, 2021 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [772bf2459f](https://linux-hardware.org/?probe=772bf2459f) | Jan 11, 2021 |
| MSI           | B350M MORTAR ARCTIC         | [0d39b0f1de](https://linux-hardware.org/?probe=0d39b0f1de) | Jan 10, 2021 |
| Dell          | 0VD5HY A00                  | [470703f4af](https://linux-hardware.org/?probe=470703f4af) | Dec 27, 2020 |
| ASUSTek       | ROG Maximus XII FORMULA     | [656256db83](https://linux-hardware.org/?probe=656256db83) | Dec 22, 2020 |
| Gigabyte      | B550 AORUS PRO              | [1520dcde71](https://linux-hardware.org/?probe=1520dcde71) | Dec 20, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [03fbf815fb](https://linux-hardware.org/?probe=03fbf815fb) | Dec 19, 2020 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [6cff41d0d5](https://linux-hardware.org/?probe=6cff41d0d5) | Dec 18, 2020 |
| ASUSTek       | ROG STRIX B460-F GAMING     | [3673aeec97](https://linux-hardware.org/?probe=3673aeec97) | Dec 07, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [e9fb942639](https://linux-hardware.org/?probe=e9fb942639) | Dec 04, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [38c026cbb9](https://linux-hardware.org/?probe=38c026cbb9) | Nov 28, 2020 |
| Lenovo        | 0800-E3G                    | [82f0cc6d73](https://linux-hardware.org/?probe=82f0cc6d73) | Nov 24, 2020 |
| Lenovo        | 0800-E3G                    | [f7a3cae158](https://linux-hardware.org/?probe=f7a3cae158) | Nov 24, 2020 |
| HP            | 0AA8h                       | [5b9abc7e6e](https://linux-hardware.org/?probe=5b9abc7e6e) | Nov 21, 2020 |
| ASUSTek       | SABERTOOTH Z77              | [4497d1907e](https://linux-hardware.org/?probe=4497d1907e) | Nov 21, 2020 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [1945ae5a25](https://linux-hardware.org/?probe=1945ae5a25) | Nov 16, 2020 |
| ASUSTek       | P9X79 LE                    | [535bb960c8](https://linux-hardware.org/?probe=535bb960c8) | Nov 09, 2020 |
| ASUSTek       | PRIME X370-PRO              | [8cc1c3b402](https://linux-hardware.org/?probe=8cc1c3b402) | Nov 05, 2020 |
| ASUSTek       | PRIME X570-P                | [7cc067fb03](https://linux-hardware.org/?probe=7cc067fb03) | Nov 03, 2020 |
| ASUSTek       | PRIME X570-P                | [2a45f74eda](https://linux-hardware.org/?probe=2a45f74eda) | Nov 02, 2020 |
| ASUSTek       | EX-A320M-GAMING             | [d44d323649](https://linux-hardware.org/?probe=d44d323649) | Oct 31, 2020 |
| Gigabyte      | GA-970A-UD3                 | [1e3afeadf1](https://linux-hardware.org/?probe=1e3afeadf1) | Oct 31, 2020 |
| Gigabyte      | GA-970A-UD3                 | [c36062c763](https://linux-hardware.org/?probe=c36062c763) | Oct 31, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [509ec4584c](https://linux-hardware.org/?probe=509ec4584c) | Oct 31, 2020 |
| ASUSTek       | P8Z77-M                     | [ca7e76d821](https://linux-hardware.org/?probe=ca7e76d821) | Oct 30, 2020 |
| ASUSTek       | PRIME X370-PRO              | [01bfabd117](https://linux-hardware.org/?probe=01bfabd117) | Oct 29, 2020 |
| Gigabyte      | 970A-DS3P                   | [4c38164a20](https://linux-hardware.org/?probe=4c38164a20) | Oct 21, 2020 |
| ASRock        | X570 Extreme4               | [40e091c5f4](https://linux-hardware.org/?probe=40e091c5f4) | Oct 16, 2020 |
| Dell          | 00V62H A01                  | [d246c4d7c9](https://linux-hardware.org/?probe=d246c4d7c9) | Oct 15, 2020 |
| ASRock        | FM2A75M-HD+                 | [eb66178779](https://linux-hardware.org/?probe=eb66178779) | Oct 13, 2020 |
| ASRock        | X570 Extreme4               | [cad3c5d0ba](https://linux-hardware.org/?probe=cad3c5d0ba) | Oct 13, 2020 |
| Gigabyte      | MQLP5AP-00                  | [bec4249ac9](https://linux-hardware.org/?probe=bec4249ac9) | Oct 12, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | [80b8079281](https://linux-hardware.org/?probe=80b8079281) | Oct 02, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [4fa10cd09d](https://linux-hardware.org/?probe=4fa10cd09d) | Sep 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [07fab4cd26](https://linux-hardware.org/?probe=07fab4cd26) | Sep 29, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [7e8f9659ac](https://linux-hardware.org/?probe=7e8f9659ac) | Sep 28, 2020 |
| Gigabyte      | H310N                       | [af0cc1312f](https://linux-hardware.org/?probe=af0cc1312f) | Sep 28, 2020 |
| MSI           | X99A RAIDER                 | [dad099d968](https://linux-hardware.org/?probe=dad099d968) | Sep 28, 2020 |
| ASRock        | X570 Taichi                 | [60d17efc7c](https://linux-hardware.org/?probe=60d17efc7c) | Sep 25, 2020 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | [a7176bb601](https://linux-hardware.org/?probe=a7176bb601) | Sep 15, 2020 |
| ASUSTek       | P9X79 LE                    | [6cb5707322](https://linux-hardware.org/?probe=6cb5707322) | Sep 15, 2020 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | [576daf4d41](https://linux-hardware.org/?probe=576daf4d41) | Sep 15, 2020 |
| ASUSTek       | SABERTOOTH Z87              | [726f3b1370](https://linux-hardware.org/?probe=726f3b1370) | Sep 14, 2020 |
| ASUSTek       | SABERTOOTH Z87              | [d6885cac52](https://linux-hardware.org/?probe=d6885cac52) | Sep 14, 2020 |
| ASUSTek       | NARRA2                      | [54160f4cb5](https://linux-hardware.org/?probe=54160f4cb5) | Sep 10, 2020 |
| ASUSTek       | EX-A320M-GAMING             | [f604a231fa](https://linux-hardware.org/?probe=f604a231fa) | Sep 10, 2020 |
| ASUSTek       | PRIME X570-P                | [08210e360a](https://linux-hardware.org/?probe=08210e360a) | Sep 10, 2020 |
| ASUSTek       | X99-E WS                    | [e37af5c1c2](https://linux-hardware.org/?probe=e37af5c1c2) | Sep 05, 2020 |
| Gigabyte      | 970A-DS3P                   | [b1248e2b3b](https://linux-hardware.org/?probe=b1248e2b3b) | Sep 05, 2020 |
| MSI           | B350 TOMAHAWK               | [cf16a05fb6](https://linux-hardware.org/?probe=cf16a05fb6) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8f3f962b06](https://linux-hardware.org/?probe=8f3f962b06) | Sep 03, 2020 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [b3bb6fe3dc](https://linux-hardware.org/?probe=b3bb6fe3dc) | Aug 27, 2020 |
| MSI           | Z97S SLI Krait Edition      | [c4b10f778e](https://linux-hardware.org/?probe=c4b10f778e) | Aug 25, 2020 |
| ASUSTek       | X99-E WS                    | [ed9d8c885d](https://linux-hardware.org/?probe=ed9d8c885d) | Aug 25, 2020 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [a59b0acdfe](https://linux-hardware.org/?probe=a59b0acdfe) | Aug 24, 2020 |
| ASUSTek       | PRIME Z270-P                | [904934805a](https://linux-hardware.org/?probe=904934805a) | Aug 19, 2020 |
| ASUSTek       | Z170-P                      | [b15339e143](https://linux-hardware.org/?probe=b15339e143) | Aug 17, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | [58dce1215c](https://linux-hardware.org/?probe=58dce1215c) | Aug 13, 2020 |
| MSI           | B350M MORTAR ARCTIC         | [c6d5a14495](https://linux-hardware.org/?probe=c6d5a14495) | Aug 12, 2020 |
| MSI           | B350M MORTAR ARCTIC         | [143846fb82](https://linux-hardware.org/?probe=143846fb82) | Aug 12, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [e0855b4bf3](https://linux-hardware.org/?probe=e0855b4bf3) | Aug 09, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [9b4f4dc28b](https://linux-hardware.org/?probe=9b4f4dc28b) | Aug 07, 2020 |
| MSI           | Z87-G45 GAMING              | [edfa113106](https://linux-hardware.org/?probe=edfa113106) | Aug 03, 2020 |
| ASUSTek       | B85M-G                      | [917bed383b](https://linux-hardware.org/?probe=917bed383b) | Jul 26, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | [552295571e](https://linux-hardware.org/?probe=552295571e) | Jul 26, 2020 |
| MSI           | Z87-G45 GAMING              | [c91081e069](https://linux-hardware.org/?probe=c91081e069) | Jul 26, 2020 |
| ASUSTek       | B85M-G                      | [475dbf0ad7](https://linux-hardware.org/?probe=475dbf0ad7) | Jul 25, 2020 |
| MSI           | Z87-G45 GAMING              | [cd32144f93](https://linux-hardware.org/?probe=cd32144f93) | Jul 25, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [c6f296962b](https://linux-hardware.org/?probe=c6f296962b) | Jul 23, 2020 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | [76fb21829c](https://linux-hardware.org/?probe=76fb21829c) | Jul 07, 2020 |
| ASRock        | KBL-NUC                     | [0fb87b772d](https://linux-hardware.org/?probe=0fb87b772d) | Jul 05, 2020 |
| ASUSTek       | TUF Z270 MARK 2             | [e6aca4abae](https://linux-hardware.org/?probe=e6aca4abae) | Jul 01, 2020 |
| ASUSTek       | TUF Z270 MARK 2             | [3662f6e30e](https://linux-hardware.org/?probe=3662f6e30e) | Jul 01, 2020 |
| ASUSTek       | PRIME X570-P                | [d7dfd2a0d2](https://linux-hardware.org/?probe=d7dfd2a0d2) | Jun 30, 2020 |
| ASUSTek       | X99-E WS                    | [b1bdbcd5d8](https://linux-hardware.org/?probe=b1bdbcd5d8) | Jun 24, 2020 |
| Dell          | 02K9CR A01                  | [823eca4894](https://linux-hardware.org/?probe=823eca4894) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | [16394021f5](https://linux-hardware.org/?probe=16394021f5) | Jun 21, 2020 |
| ASUSTek       | PRIME X570-P                | [392a2f214f](https://linux-hardware.org/?probe=392a2f214f) | Jun 20, 2020 |
| ASUSTek       | Z170-P                      | [7bbf45616d](https://linux-hardware.org/?probe=7bbf45616d) | Jun 11, 2020 |
| ASUSTek       | SABERTOOTH X58              | [b96a58003f](https://linux-hardware.org/?probe=b96a58003f) | Jun 02, 2020 |
| ASUSTek       | M5A97 R2.0                  | [f83c6bc99a](https://linux-hardware.org/?probe=f83c6bc99a) | May 28, 2020 |
| ASUSTek       | M5A97 R2.0                  | [4479197ed4](https://linux-hardware.org/?probe=4479197ed4) | May 23, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [0580ffcbce](https://linux-hardware.org/?probe=0580ffcbce) | May 18, 2020 |
| ASUSTek       | SABERTOOTH X58              | [0ac27b4c34](https://linux-hardware.org/?probe=0ac27b4c34) | May 18, 2020 |
| ASUSTek       | SABERTOOTH X58              | [bc5ccb2621](https://linux-hardware.org/?probe=bc5ccb2621) | May 18, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [386740675c](https://linux-hardware.org/?probe=386740675c) | May 13, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [98d3987a61](https://linux-hardware.org/?probe=98d3987a61) | May 06, 2020 |
| ASUSTek       | H81I-PLUS                   | [33d922e46d](https://linux-hardware.org/?probe=33d922e46d) | May 05, 2020 |
| ASUSTek       | P8H77-I                     | [cd6981fca0](https://linux-hardware.org/?probe=cd6981fca0) | Apr 28, 2020 |
| ASUSTek       | P8H77-I                     | [9fdad4ca4b](https://linux-hardware.org/?probe=9fdad4ca4b) | Apr 28, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [5cae2ee3d0](https://linux-hardware.org/?probe=5cae2ee3d0) | Apr 28, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a5bf0d9b6b](https://linux-hardware.org/?probe=a5bf0d9b6b) | Apr 28, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [4e2748672a](https://linux-hardware.org/?probe=4e2748672a) | Apr 28, 2020 |
| HP            | 3397                        | [e6727c485f](https://linux-hardware.org/?probe=e6727c485f) | Apr 27, 2020 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | [6a5b331028](https://linux-hardware.org/?probe=6a5b331028) | Apr 11, 2020 |
| ASRock        | X99M Extreme4               | [45030fab5d](https://linux-hardware.org/?probe=45030fab5d) | Apr 11, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [a71754c00c](https://linux-hardware.org/?probe=a71754c00c) | Apr 07, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [2557527190](https://linux-hardware.org/?probe=2557527190) | Apr 06, 2020 |
| ASUSTek       | X99-E WS                    | [cab8397e58](https://linux-hardware.org/?probe=cab8397e58) | Apr 05, 2020 |
| HP            | 0A68h                       | [21961765f3](https://linux-hardware.org/?probe=21961765f3) | Apr 04, 2020 |
| ASUSTek       | X99-E WS                    | [535aa9a5c6](https://linux-hardware.org/?probe=535aa9a5c6) | Apr 01, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [83594d554f](https://linux-hardware.org/?probe=83594d554f) | Mar 26, 2020 |
| HP            | 0A68h                       | [e48c1d8956](https://linux-hardware.org/?probe=e48c1d8956) | Mar 21, 2020 |
| MSI           | Z270 GAMING PRO CARBON      | [a5c1f26d9c](https://linux-hardware.org/?probe=a5c1f26d9c) | Mar 21, 2020 |
| MSI           | B450M BAZOOKA               | [a97b201643](https://linux-hardware.org/?probe=a97b201643) | Mar 19, 2020 |
| MSI           | Z270 GAMING PRO CARBON      | [731ed47f34](https://linux-hardware.org/?probe=731ed47f34) | Mar 17, 2020 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [b5a0ec3283](https://linux-hardware.org/?probe=b5a0ec3283) | Mar 16, 2020 |
| Gigabyte      | B450 AORUS M                | [3c6e4bca36](https://linux-hardware.org/?probe=3c6e4bca36) | Mar 13, 2020 |
| Shuttle       | FS35V4                      | [c52e6f6535](https://linux-hardware.org/?probe=c52e6f6535) | Mar 02, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [5d7f28b50a](https://linux-hardware.org/?probe=5d7f28b50a) | Feb 29, 2020 |
| ASUSTek       | PRIME H270-PLUS             | [c89b46d092](https://linux-hardware.org/?probe=c89b46d092) | Feb 25, 2020 |
| Shuttle       | FS35V4                      | [86b9422986](https://linux-hardware.org/?probe=86b9422986) | Feb 23, 2020 |
| Pegatron      | 2AB5                        | [8cd66072e1](https://linux-hardware.org/?probe=8cd66072e1) | Feb 21, 2020 |
| Gigabyte      | Z270N-WIFI-CF               | [765c227e7c](https://linux-hardware.org/?probe=765c227e7c) | Feb 21, 2020 |
| ASRock        | H81M-ITX/WiFi               | [4b746c7d20](https://linux-hardware.org/?probe=4b746c7d20) | Feb 19, 2020 |
| Gigabyte      | GA-970A-UD3                 | [9d30831796](https://linux-hardware.org/?probe=9d30831796) | Feb 17, 2020 |
| Gigabyte      | GA-970A-UD3                 | [3d45ca6f5b](https://linux-hardware.org/?probe=3d45ca6f5b) | Feb 17, 2020 |
| Dell          | 0DF42J A00                  | [315459c675](https://linux-hardware.org/?probe=315459c675) | Feb 16, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [0be68258a3](https://linux-hardware.org/?probe=0be68258a3) | Feb 11, 2020 |
| Acer          | FRS690L                     | [da0aa833d2](https://linux-hardware.org/?probe=da0aa833d2) | Feb 07, 2020 |
| Acer          | FRS690L                     | [d2f7944838](https://linux-hardware.org/?probe=d2f7944838) | Feb 07, 2020 |
| Acer          | FRS690L                     | [52e677d939](https://linux-hardware.org/?probe=52e677d939) | Feb 07, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [174e1402cf](https://linux-hardware.org/?probe=174e1402cf) | Feb 03, 2020 |
| Dell          | 0MN1TX A02                  | [5c482e9676](https://linux-hardware.org/?probe=5c482e9676) | Jan 18, 2020 |
| Dell          | 0MN1TX A02                  | [5f652869cd](https://linux-hardware.org/?probe=5f652869cd) | Jan 18, 2020 |
| ASRock        | H81M-ITX/WiFi               | [b4fc494391](https://linux-hardware.org/?probe=b4fc494391) | Dec 30, 2019 |
| MSI           | MPG X570 GAMING EDGE WIF... | [6df8cd9ddd](https://linux-hardware.org/?probe=6df8cd9ddd) | Dec 20, 2019 |
| ASUSTek       | P7P55D                      | [a630b7494e](https://linux-hardware.org/?probe=a630b7494e) | Dec 07, 2019 |
| ASUSTek       | Z170-A                      | [23b0f48535](https://linux-hardware.org/?probe=23b0f48535) | Nov 24, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2581a2d661](https://linux-hardware.org/?probe=2581a2d661) | Nov 16, 2019 |
| Dell          | 06X1TJ A01                  | [9da4eeda28](https://linux-hardware.org/?probe=9da4eeda28) | Nov 05, 2019 |
| ASUSTek       | P9D WS                      | [549ecf66d0](https://linux-hardware.org/?probe=549ecf66d0) | Oct 23, 2019 |
| HP            | 2AE2                        | [ac16964bc3](https://linux-hardware.org/?probe=ac16964bc3) | Oct 15, 2019 |
| HP            | 2AE2                        | [ea13e02e53](https://linux-hardware.org/?probe=ea13e02e53) | Oct 01, 2019 |
| ASUSTek       | A8NE-FM                     | [741f8cff05](https://linux-hardware.org/?probe=741f8cff05) | Sep 29, 2019 |
| ASUSTek       | H87I-PLUS                   | [b74b1c5ad4](https://linux-hardware.org/?probe=b74b1c5ad4) | Sep 05, 2019 |
| ASUSTek       | M5A78L-M/USB3               | [7c2f30c389](https://linux-hardware.org/?probe=7c2f30c389) | Aug 25, 2019 |
| MSI           | 2AE0                        | [e8c2927bde](https://linux-hardware.org/?probe=e8c2927bde) | Aug 03, 2019 |
| MSI           | B450-A PRO                  | [b1e465082e](https://linux-hardware.org/?probe=b1e465082e) | Aug 02, 2019 |
| MSI           | B450-A PRO                  | [a1382a1557](https://linux-hardware.org/?probe=a1382a1557) | Jul 30, 2019 |
| ASRock        | Z390 Taichi Ultimate        | [62a28aa523](https://linux-hardware.org/?probe=62a28aa523) | Jul 30, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [cdc565d73d](https://linux-hardware.org/?probe=cdc565d73d) | Jul 23, 2019 |
| MSI           | Z97-G43 GAMING              | [5c83686f9c](https://linux-hardware.org/?probe=5c83686f9c) | Jul 14, 2019 |
| MSI           | H87I                        | [b0be456a64](https://linux-hardware.org/?probe=b0be456a64) | Jul 10, 2019 |
| ASUSTek       | B85M-G                      | [08d84a1ff9](https://linux-hardware.org/?probe=08d84a1ff9) | Jul 09, 2019 |
| HP            | 2AE2                        | [7827916e15](https://linux-hardware.org/?probe=7827916e15) | Jul 01, 2019 |
| HP            | 2AE2                        | [b999d6bd6d](https://linux-hardware.org/?probe=b999d6bd6d) | Jun 17, 2019 |
| ASUSTek       | SABERTOOTH P67              | [0eef21306d](https://linux-hardware.org/?probe=0eef21306d) | Jun 17, 2019 |
| Dell          | 06X1TJ A01                  | [9a78ee6839](https://linux-hardware.org/?probe=9a78ee6839) | May 28, 2019 |
| MSI           | X299 SLI PLUS               | [692c95368a](https://linux-hardware.org/?probe=692c95368a) | May 06, 2019 |
| ASUSTek       | STRIX H270I GAMING          | [fc59e7df18](https://linux-hardware.org/?probe=fc59e7df18) | May 04, 2019 |
| ASUSTek       | STRIX H270I GAMING          | [106016dd36](https://linux-hardware.org/?probe=106016dd36) | Apr 28, 2019 |
| ASUSTek       | STRIX H270I GAMING          | [2786657449](https://linux-hardware.org/?probe=2786657449) | Apr 12, 2019 |
| Intel         | DG45FC AAE27730-308         | [459dc2d57f](https://linux-hardware.org/?probe=459dc2d57f) | Apr 08, 2019 |
| Gigabyte      | Z97MX-Gaming 5              | [d94ade2c40](https://linux-hardware.org/?probe=d94ade2c40) | Mar 27, 2019 |
| Dell          | 0K240Y A01                  | [4683a284a4](https://linux-hardware.org/?probe=4683a284a4) | Mar 26, 2019 |
| MSI           | 2AE0                        | [5585935586](https://linux-hardware.org/?probe=5585935586) | Mar 25, 2019 |
| Dell          | 0HN7XN A01                  | [0b8a535d2a](https://linux-hardware.org/?probe=0b8a535d2a) | Mar 16, 2019 |
| ASUSTek       | SABERTOOTH P67              | [eaa09576b4](https://linux-hardware.org/?probe=eaa09576b4) | Mar 12, 2019 |
| Pegatron      | 2A72h                       | [aa54b4c1d3](https://linux-hardware.org/?probe=aa54b4c1d3) | Mar 07, 2019 |
| MSI           | Z68A-GD65                   | [883872e8b0](https://linux-hardware.org/?probe=883872e8b0) | Feb 18, 2019 |
| ASUSTek       | B85M-G                      | [b45f44a0f7](https://linux-hardware.org/?probe=b45f44a0f7) | Jan 23, 2019 |
| Lenovo        | 36EF SDK0J40700 WIN 3258... | [b077a03fb3](https://linux-hardware.org/?probe=b077a03fb3) | Jan 07, 2019 |
| HP            | 0B54h D                     | [1456dd6d91](https://linux-hardware.org/?probe=1456dd6d91) | Jan 06, 2019 |
| Dell          | 0RW203                      | [7773935ee9](https://linux-hardware.org/?probe=7773935ee9) | Dec 23, 2018 |
| Dell          | 0RW203                      | [bb86cab506](https://linux-hardware.org/?probe=bb86cab506) | Dec 23, 2018 |
| ASUSTek       | SABERTOOTH Z77              | [41b6e4c6b2](https://linux-hardware.org/?probe=41b6e4c6b2) | Dec 06, 2018 |
| ASUSTek       | EB1501P                     | [4a6eb1071a](https://linux-hardware.org/?probe=4a6eb1071a) | Oct 21, 2018 |
| Gigabyte      | F2A75M-D3H                  | [41a0eb1b0d](https://linux-hardware.org/?probe=41a0eb1b0d) | Oct 06, 2018 |
| ASUSTek       | AM1I-A                      | [e6a8378a5b](https://linux-hardware.org/?probe=e6a8378a5b) | Jun 15, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 40       | 13.89%  |
| Ubuntu 18.04                 | 22       | 7.64%   |
| Zorin 16                     | 8        | 2.78%   |
| Ubuntu 18.10                 | 8        | 2.78%   |
| OpenMandriva 4.2             | 8        | 2.78%   |
| Ubuntu 19.10                 | 7        | 2.43%   |
| Fedora 35                    | 7        | 2.43%   |
| Debian 11                    | 7        | 2.43%   |
| ArcoLinux Rolling            | 7        | 2.43%   |
| Arch Rolling                 | 7        | 2.43%   |
| Arch                         | 7        | 2.43%   |
| Pop!_OS 21.04                | 6        | 2.08%   |
| OpenMandriva 4.3             | 6        | 2.08%   |
| Fedora 32                    | 6        | 2.08%   |
| Ubuntu 22.04                 | 5        | 1.74%   |
| Ubuntu 20.10                 | 5        | 1.74%   |
| Pop!_OS 20.04                | 5        | 1.74%   |
| Zorin 15                     | 4        | 1.39%   |
| Ubuntu 21.10                 | 4        | 1.39%   |
| Ubuntu 19.04                 | 4        | 1.39%   |
| Pop!_OS 22.04                | 4        | 1.39%   |
| Pop!_OS 21.10                | 4        | 1.39%   |
| Pop!_OS 20.10                | 4        | 1.39%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.39%   |
| Linux Mint 20.2              | 4        | 1.39%   |
| Linux Mint 20.1              | 4        | 1.39%   |
| KDE neon 20.04               | 4        | 1.39%   |
| Fedora 34                    | 4        | 1.39%   |
| Fedora 33                    | 4        | 1.39%   |
| Debian 10                    | 4        | 1.39%   |
| Ubuntu 21.04                 | 3        | 1.04%   |
| Manjaro 20.1                 | 3        | 1.04%   |
| Manjaro                      | 3        | 1.04%   |
| Linux Mint 19.1              | 3        | 1.04%   |
| Kubuntu 20.04                | 3        | 1.04%   |
| Gentoo 2.7                   | 3        | 1.04%   |
| Fedora 36                    | 3        | 1.04%   |
| Fedora 31                    | 3        | 1.04%   |
| Manjaro 20.2.1               | 2        | 0.69%   |
| Linux Mint 19.3              | 2        | 0.69%   |
| Fedora 30                    | 2        | 0.69%   |
| Debian Unstable              | 2        | 0.69%   |
| Xubuntu 20.04                | 1        | 0.35%   |
| Xubuntu 19.10                | 1        | 0.35%   |
| Xubuntu 18.04                | 1        | 0.35%   |
| Ubuntu Studio 20.10          | 1        | 0.35%   |
| Ubuntu MATE 20.10            | 1        | 0.35%   |
| Ubuntu Budgie 22.04          | 1        | 0.35%   |
| Ubuntu Budgie 20.04          | 1        | 0.35%   |
| Ubuntu 17.04                 | 1        | 0.35%   |
| Solus 4.3                    | 1        | 0.35%   |
| ROSA R8.1                    | 1        | 0.35%   |
| ROSA R11.1                   | 1        | 0.35%   |
| ROSA R10                     | 1        | 0.35%   |
| openSUSE Leap-15.1           | 1        | 0.35%   |
| OpenMandriva 4.50            | 1        | 0.35%   |
| Manjaro 21.2.6               | 1        | 0.35%   |
| Manjaro 21.2.3               | 1        | 0.35%   |
| Manjaro 21.1.6               | 1        | 0.35%   |
| Manjaro 21.1.4               | 1        | 0.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 93       | 33.7%   |
| Fedora        | 26       | 9.42%   |
| Pop!_OS       | 20       | 7.25%   |
| Manjaro       | 16       | 5.8%    |
| Linux Mint    | 16       | 5.8%    |
| OpenMandriva  | 15       | 5.43%   |
| Debian        | 14       | 5.07%   |
| Arch          | 14       | 5.07%   |
| Zorin         | 12       | 4.35%   |
| ArcoLinux     | 7        | 2.54%   |
| openSUSE      | 5        | 1.81%   |
| KDE neon      | 5        | 1.81%   |
| Kubuntu       | 4        | 1.45%   |
| Gentoo        | 4        | 1.45%   |
| Clear Linux   | 4        | 1.45%   |
| Xubuntu       | 3        | 1.09%   |
| ROSA          | 3        | 1.09%   |
| Ubuntu Budgie | 2        | 0.72%   |
| EndeavourOS   | 2        | 0.72%   |
| CentOS        | 2        | 0.72%   |
| Alpine        | 2        | 0.72%   |
| Ubuntu Studio | 1        | 0.36%   |
| Ubuntu MATE   | 1        | 0.36%   |
| Solus         | 1        | 0.36%   |
| LMDE          | 1        | 0.36%   |
| Garuda Linux  | 1        | 0.36%   |
| Feren OS      | 1        | 0.36%   |
| Elementary    | 1        | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 8        | 2.49%   |
| 5.16.7-desktop-1omv4003  | 6        | 1.87%   |
| 4.18.0-16-generic        | 6        | 1.87%   |
| 5.11.0-38-generic        | 5        | 1.56%   |
| 5.4.0-47-generic         | 4        | 1.25%   |
| 5.4.0-42-generic         | 4        | 1.25%   |
| 5.15.0-41-generic        | 4        | 1.25%   |
| 5.8.0-7630-generic       | 3        | 0.93%   |
| 5.4.0-74-generic         | 3        | 0.93%   |
| 5.4.0-51-generic         | 3        | 0.93%   |
| 5.4.0-29-generic         | 3        | 0.93%   |
| 5.3.0-28-generic         | 3        | 0.93%   |
| 5.3.0-18-generic         | 3        | 0.93%   |
| 5.15.7-arch1-1           | 3        | 0.93%   |
| 5.13.0-40-generic        | 3        | 0.93%   |
| 5.13.0-21-generic        | 3        | 0.93%   |
| 5.11.0-7620-generic      | 3        | 0.93%   |
| 5.11.0-27-generic        | 3        | 0.93%   |
| 5.0.0-20-generic         | 3        | 0.93%   |
| 5.9.16-1-MANJARO         | 2        | 0.62%   |
| 5.8.0-48-generic         | 2        | 0.62%   |
| 5.8.0-43-generic         | 2        | 0.62%   |
| 5.8.0-26-generic         | 2        | 0.62%   |
| 5.7.9-arch1-1            | 2        | 0.62%   |
| 5.5.5-200.fc31.x86_64    | 2        | 0.62%   |
| 5.4.0-91-generic         | 2        | 0.62%   |
| 5.4.0-89-generic         | 2        | 0.62%   |
| 5.4.0-80-generic         | 2        | 0.62%   |
| 5.4.0-77-generic         | 2        | 0.62%   |
| 5.4.0-7642-generic       | 2        | 0.62%   |
| 5.4.0-72-generic         | 2        | 0.62%   |
| 5.4.0-70-generic         | 2        | 0.62%   |
| 5.4.0-58-generic         | 2        | 0.62%   |
| 5.4.0-48-generic         | 2        | 0.62%   |
| 5.4.0-37-generic         | 2        | 0.62%   |
| 5.4.0-26-generic         | 2        | 0.62%   |
| 5.4.0-100-generic        | 2        | 0.62%   |
| 5.3.0-46-generic         | 2        | 0.62%   |
| 5.3.0-45-generic         | 2        | 0.62%   |
| 5.3.0-42-generic         | 2        | 0.62%   |
| 5.3.0-40-generic         | 2        | 0.62%   |
| 5.3.0-26-generic         | 2        | 0.62%   |
| 5.3.0-24-generic         | 2        | 0.62%   |
| 5.17.6-300.fc36.x86_64   | 2        | 0.62%   |
| 5.17.5-arch1-1           | 2        | 0.62%   |
| 5.16.18-200.fc35.x86_64  | 2        | 0.62%   |
| 5.16.0-arch1-1           | 2        | 0.62%   |
| 5.15.4-zen1-1-zen        | 2        | 0.62%   |
| 5.15.15-76051515-generic | 2        | 0.62%   |
| 5.14.10-300.fc35.x86_64  | 2        | 0.62%   |
| 5.13.0-7614-generic      | 2        | 0.62%   |
| 5.13.0-37-generic        | 2        | 0.62%   |
| 5.11.0-40-generic        | 2        | 0.62%   |
| 5.11.0-34-generic        | 2        | 0.62%   |
| 5.0.0-32-generic         | 2        | 0.62%   |
| 5.0.0-23-generic         | 2        | 0.62%   |
| 4.19.0-16-amd64          | 2        | 0.62%   |
| 4.19.0-13-amd64          | 2        | 0.62%   |
| 4.18.0-25-generic        | 2        | 0.62%   |
| 4.18.0-17-generic        | 2        | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 48       | 15.84%  |
| 5.11.0  | 20       | 6.6%    |
| 5.3.0   | 16       | 5.28%   |
| 4.18.0  | 16       | 5.28%   |
| 5.8.0   | 15       | 4.95%   |
| 5.13.0  | 14       | 4.62%   |
| 4.15.0  | 11       | 3.63%   |
| 5.0.0   | 9        | 2.97%   |
| 5.10.14 | 8        | 2.64%   |
| 5.10.0  | 8        | 2.64%   |
| 5.15.0  | 7        | 2.31%   |
| 5.16.7  | 6        | 1.98%   |
| 5.16.0  | 5        | 1.65%   |
| 4.19.0  | 5        | 1.65%   |
| 5.9.16  | 3        | 0.99%   |
| 5.17.5  | 3        | 0.99%   |
| 5.15.7  | 3        | 0.99%   |
| 5.15.4  | 3        | 0.99%   |
| 5.14.10 | 3        | 0.99%   |
| 5.9.11  | 2        | 0.66%   |
| 5.8.6   | 2        | 0.66%   |
| 5.8.12  | 2        | 0.66%   |
| 5.7.9   | 2        | 0.66%   |
| 5.7.17  | 2        | 0.66%   |
| 5.7.12  | 2        | 0.66%   |
| 5.6.0   | 2        | 0.66%   |
| 5.5.5   | 2        | 0.66%   |
| 5.17.9  | 2        | 0.66%   |
| 5.17.6  | 2        | 0.66%   |
| 5.17.4  | 2        | 0.66%   |
| 5.16.9  | 2        | 0.66%   |
| 5.16.18 | 2        | 0.66%   |
| 5.15.8  | 2        | 0.66%   |
| 5.15.15 | 2        | 0.66%   |
| 5.13.4  | 2        | 0.66%   |
| 5.12.9  | 2        | 0.66%   |
| 5.11.11 | 2        | 0.66%   |
| 5.9.8   | 1        | 0.33%   |
| 5.9.3   | 1        | 0.33%   |
| 5.9.15  | 1        | 0.33%   |
| 5.9.1   | 1        | 0.33%   |
| 5.8.5   | 1        | 0.33%   |
| 5.8.2   | 1        | 0.33%   |
| 5.8.16  | 1        | 0.33%   |
| 5.8.11  | 1        | 0.33%   |
| 5.8.1   | 1        | 0.33%   |
| 5.7.4   | 1        | 0.33%   |
| 5.7.15  | 1        | 0.33%   |
| 5.7.0   | 1        | 0.33%   |
| 5.6.19  | 1        | 0.33%   |
| 5.6.13  | 1        | 0.33%   |
| 5.5.8   | 1        | 0.33%   |
| 5.5.3   | 1        | 0.33%   |
| 5.5.10  | 1        | 0.33%   |
| 5.5.0   | 1        | 0.33%   |
| 5.4.67  | 1        | 0.33%   |
| 5.4.57  | 1        | 0.33%   |
| 5.4.32  | 1        | 0.33%   |
| 5.4.3   | 1        | 0.33%   |
| 5.4.15  | 1        | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 53       | 17.67%  |
| 5.8     | 24       | 8%      |
| 5.15    | 24       | 8%      |
| 5.11    | 23       | 7.67%   |
| 5.13    | 21       | 7%      |
| 5.10    | 19       | 6.33%   |
| 5.3     | 17       | 5.67%   |
| 5.16    | 17       | 5.67%   |
| 4.18    | 16       | 5.33%   |
| 5.17    | 12       | 4%      |
| 4.15    | 11       | 3.67%   |
| 5.0     | 10       | 3.33%   |
| 5.9     | 9        | 3%      |
| 5.7     | 8        | 2.67%   |
| 5.5     | 6        | 2%      |
| 5.12    | 6        | 2%      |
| 5.14    | 5        | 1.67%   |
| 4.19    | 5        | 1.67%   |
| 5.6     | 4        | 1.33%   |
| 5.18    | 4        | 1.33%   |
| 4.9     | 1        | 0.33%   |
| 4.4     | 1        | 0.33%   |
| 4.12    | 1        | 0.33%   |
| 4.10    | 1        | 0.33%   |
| 4.1     | 1        | 0.33%   |
| 3.10    | 1        | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 265      | 99.25%  |
| i686   | 2        | 0.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 127      | 45.85%  |
| Unknown         | 53       | 19.13%  |
| KDE5            | 39       | 14.08%  |
| XFCE            | 16       | 5.78%   |
| KDE             | 11       | 3.97%   |
| X-Cinnamon      | 10       | 3.61%   |
| i3              | 5        | 1.81%   |
| Budgie          | 4        | 1.44%   |
| Cinnamon        | 3        | 1.08%   |
| MATE            | 2        | 0.72%   |
| qtile           | 1        | 0.36%   |
| Pantheon        | 1        | 0.36%   |
| LXDE            | 1        | 0.36%   |
| LeftWM          | 1        | 0.36%   |
| KDE4            | 1        | 0.36%   |
| i3-with-shmlog  | 1        | 0.36%   |
| GNOME Flashback | 1        | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 216      | 77.42%  |
| Wayland | 28       | 10.04%  |
| Unknown | 22       | 7.89%   |
| Tty     | 13       | 4.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 162      | 58.27%  |
| GDM     | 38       | 13.67%  |
| SDDM    | 37       | 13.31%  |
| LightDM | 16       | 5.76%   |
| GDM3    | 16       | 5.76%   |
| TDM     | 8        | 2.88%   |
| KDM     | 1        | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 129      | 47.25%  |
| nb_NO   | 56       | 20.51%  |
| Unknown | 41       | 15.02%  |
| en_GB   | 23       | 8.42%   |
| C       | 6        | 2.2%    |
| nn_NO   | 4        | 1.47%   |
| en_DK   | 4        | 1.47%   |
| fr_FR   | 2        | 0.73%   |
| de_DE   | 2        | 0.73%   |
| ru_RU   | 1        | 0.37%   |
| pt_PT   | 1        | 0.37%   |
| pl_PL   | 1        | 0.37%   |
| es_ES   | 1        | 0.37%   |
| en_CA   | 1        | 0.37%   |
| en_AG   | 1        | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 143      | 52.57%  |
| EFI  | 129      | 47.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 210      | 77.49%  |
| Btrfs   | 30       | 11.07%  |
| Overlay | 13       | 4.8%    |
| Unknown | 9        | 3.32%   |
| Zfs     | 3        | 1.11%   |
| Xfs     | 3        | 1.11%   |
| Ext2    | 3        | 1.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 159      | 58.67%  |
| GPT     | 86       | 31.73%  |
| MBR     | 26       | 9.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 218      | 78.99%  |
| Yes       | 58       | 21.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 175      | 63.87%  |
| Yes       | 99       | 36.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 112      | 41.95%  |
| Gigabyte Technology | 39       | 14.61%  |
| MSI                 | 31       | 11.61%  |
| ASRock              | 19       | 7.12%   |
| Dell                | 18       | 6.74%   |
| Hewlett-Packard     | 14       | 5.24%   |
| Lenovo              | 11       | 4.12%   |
| Acer                | 6        | 2.25%   |
| Pegatron            | 3        | 1.12%   |
| Intel               | 3        | 1.12%   |
| Wibtek              | 1        | 0.37%   |
| Supermicro          | 1        | 0.37%   |
| Shuttle             | 1        | 0.37%   |
| Packard Bell        | 1        | 0.37%   |
| Lenovo Product      | 1        | 0.37%   |
| Fujitsu Siemens     | 1        | 0.37%   |
| Fujitsu             | 1        | 0.37%   |
| Cisco Systems       | 1        | 0.37%   |
| ASRockRack          | 1        | 0.37%   |
| Acidanthera         | 1        | 0.37%   |
| Unknown             | 1        | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 13       | 4.87%   |
| ASUS ROG STRIX X570-F GAMING               | 4        | 1.5%    |
| ASUS ROG STRIX B360-F GAMING               | 4        | 1.5%    |
| ASUS M2R-FVM                               | 4        | 1.5%    |
| MSI MS-7885                                | 3        | 1.12%   |
| Gigabyte GA-970A-UD3                       | 3        | 1.12%   |
| Dell OptiPlex 9020                         | 3        | 1.12%   |
| Dell OptiPlex 7010                         | 3        | 1.12%   |
| ASUS SABERTOOTH P67                        | 3        | 1.12%   |
| ASUS PRIME X570-P                          | 3        | 1.12%   |
| MSI MS-7A37                                | 2        | 0.75%   |
| Gigabyte Z490I AORUS ULTRA                 | 2        | 0.75%   |
| Gigabyte X570 AORUS ELITE                  | 2        | 0.75%   |
| Gigabyte 970A-DS3P                         | 2        | 0.75%   |
| ASUS Z170 PRO GAMING                       | 2        | 0.75%   |
| ASUS SABERTOOTH Z77                        | 2        | 0.75%   |
| ASUS ROG STRIX X470-F GAMING               | 2        | 0.75%   |
| ASUS ROG STRIX B550-I GAMING               | 2        | 0.75%   |
| ASUS ROG STRIX B550-E GAMING               | 2        | 0.75%   |
| ASUS ROG STRIX B460-F GAMING               | 2        | 0.75%   |
| ASUS ROG STRIX B450-F GAMING               | 2        | 0.75%   |
| ASUS PRIME Z270-P                          | 2        | 0.75%   |
| ASUS PRIME X370-PRO                        | 2        | 0.75%   |
| ASUS P9X79 LE                              | 2        | 0.75%   |
| ASUS P8Z77-V LX                            | 2        | 0.75%   |
| ASUS Maximus VIII HERO                     | 2        | 0.75%   |
| ASUS M5A97 R2.0                            | 2        | 0.75%   |
| ASUS EX-A320M-GAMING                       | 2        | 0.75%   |
| ASUS CROSSHAIR VI HERO                     | 2        | 0.75%   |
| ASRock X570 Taichi                         | 2        | 0.75%   |
| Wibtek TH61G-S                             | 1        | 0.37%   |
| Supermicro SYS-7038A-I                     | 1        | 0.37%   |
| Shuttle XS35V4                             | 1        | 0.37%   |
| Pegatron TouchSmart 7320 Lavaca-B EU L6 PC | 1        | 0.37%   |
| Pegatron h8-1080sc                         | 1        | 0.37%   |
| Pegatron Compaq dx2450 Microtower PC       | 1        | 0.37%   |
| Packard Bell IXTREME M5120                 | 1        | 0.37%   |
| MSI MS-7D54                                | 1        | 0.37%   |
| MSI MS-7C94                                | 1        | 0.37%   |
| MSI MS-7C84                                | 1        | 0.37%   |
| MSI MS-7C37                                | 1        | 0.37%   |
| MSI MS-7C35                                | 1        | 0.37%   |
| MSI MS-7B98                                | 1        | 0.37%   |
| MSI MS-7B86                                | 1        | 0.37%   |
| MSI MS-7A93                                | 1        | 0.37%   |
| MSI MS-7A63                                | 1        | 0.37%   |
| MSI MS-7A38                                | 1        | 0.37%   |
| MSI MS-7A34                                | 1        | 0.37%   |
| MSI MS-7996                                | 1        | 0.37%   |
| MSI MS-7978                                | 1        | 0.37%   |
| MSI MS-7971                                | 1        | 0.37%   |
| MSI MS-7922                                | 1        | 0.37%   |
| MSI MS-7851                                | 1        | 0.37%   |
| MSI MS-7821                                | 1        | 0.37%   |
| MSI MS-7817                                | 1        | 0.37%   |
| MSI MS-7816                                | 1        | 0.37%   |
| MSI MS-7798                                | 1        | 0.37%   |
| MSI MS-7751                                | 1        | 0.37%   |
| MSI MS-7693                                | 1        | 0.37%   |
| MSI MS-7681                                | 1        | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 27       | 10.11%  |
| ASUS PRIME             | 16       | 5.99%   |
| ASUS All               | 13       | 4.87%   |
| Dell OptiPlex          | 12       | 4.49%   |
| Lenovo ThinkCentre     | 6        | 2.25%   |
| Gigabyte X570          | 6        | 2.25%   |
| ASUS TUF               | 6        | 2.25%   |
| ASUS SABERTOOTH        | 6        | 2.25%   |
| Gigabyte B550          | 4        | 1.5%    |
| Gigabyte B450          | 4        | 1.5%    |
| Dell Precision         | 4        | 1.5%    |
| ASUS STRIX             | 4        | 1.5%    |
| ASUS P8Z77-V           | 4        | 1.5%    |
| ASUS M2R-FVM           | 4        | 1.5%    |
| ASUS CROSSHAIR         | 4        | 1.5%    |
| ASRock X570            | 4        | 1.5%    |
| MSI MS-7885            | 3        | 1.12%   |
| HP EliteDesk           | 3        | 1.12%   |
| Gigabyte GA-970A-UD3   | 3        | 1.12%   |
| ASUS Maximus           | 3        | 1.12%   |
| MSI MS-7A37            | 2        | 0.75%   |
| HP Z240                | 2        | 0.75%   |
| HP Compaq              | 2        | 0.75%   |
| Gigabyte Z490I         | 2        | 0.75%   |
| Gigabyte 970A-DS3P     | 2        | 0.75%   |
| ASUS Z170              | 2        | 0.75%   |
| ASUS P9X79             | 2        | 0.75%   |
| ASUS M5A97             | 2        | 0.75%   |
| ASUS EX-A320M-GAMING   | 2        | 0.75%   |
| ASRock B450M           | 2        | 0.75%   |
| ASRock B450            | 2        | 0.75%   |
| Acer Predator          | 2        | 0.75%   |
| Acer Aspire            | 2        | 0.75%   |
| Wibtek TH61G-S         | 1        | 0.37%   |
| Supermicro SYS-7038A-I | 1        | 0.37%   |
| Shuttle XS35V4         | 1        | 0.37%   |
| Pegatron TouchSmart    | 1        | 0.37%   |
| Pegatron h8-1080sc     | 1        | 0.37%   |
| Pegatron Compaq        | 1        | 0.37%   |
| Packard Bell IXTREME   | 1        | 0.37%   |
| MSI MS-7D54            | 1        | 0.37%   |
| MSI MS-7C94            | 1        | 0.37%   |
| MSI MS-7C84            | 1        | 0.37%   |
| MSI MS-7C37            | 1        | 0.37%   |
| MSI MS-7C35            | 1        | 0.37%   |
| MSI MS-7B98            | 1        | 0.37%   |
| MSI MS-7B86            | 1        | 0.37%   |
| MSI MS-7A93            | 1        | 0.37%   |
| MSI MS-7A63            | 1        | 0.37%   |
| MSI MS-7A38            | 1        | 0.37%   |
| MSI MS-7A34            | 1        | 0.37%   |
| MSI MS-7996            | 1        | 0.37%   |
| MSI MS-7978            | 1        | 0.37%   |
| MSI MS-7971            | 1        | 0.37%   |
| MSI MS-7922            | 1        | 0.37%   |
| MSI MS-7851            | 1        | 0.37%   |
| MSI MS-7821            | 1        | 0.37%   |
| MSI MS-7817            | 1        | 0.37%   |
| MSI MS-7816            | 1        | 0.37%   |
| MSI MS-7798            | 1        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 33       | 12.36%  |
| 2019 | 30       | 11.24%  |
| 2020 | 26       | 9.74%   |
| 2013 | 26       | 9.74%   |
| 2012 | 25       | 9.36%   |
| 2015 | 22       | 8.24%   |
| 2017 | 21       | 7.87%   |
| 2014 | 18       | 6.74%   |
| 2016 | 14       | 5.24%   |
| 2011 | 13       | 4.87%   |
| 2010 | 10       | 3.75%   |
| 2009 | 8        | 3%      |
| 2021 | 7        | 2.62%   |
| 2006 | 5        | 1.87%   |
| 2008 | 3        | 1.12%   |
| 2007 | 3        | 1.12%   |
| 2005 | 2        | 0.75%   |
| 2001 | 1        | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 267      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 259      | 95.93%  |
| Enabled  | 11       | 4.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 267      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 87       | 32.34%  |
| 32.01-64.0      | 68       | 25.28%  |
| 8.01-16.0       | 35       | 13.01%  |
| 4.01-8.0        | 28       | 10.41%  |
| 3.01-4.0        | 22       | 8.18%   |
| 64.01-256.0     | 19       | 7.06%   |
| 24.01-32.0      | 4        | 1.49%   |
| More than 256.0 | 2        | 0.74%   |
| 1.01-2.0        | 2        | 0.74%   |
| 2.01-3.0        | 1        | 0.37%   |
| 0.01-0.5        | 1        | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 75       | 24.35%  |
| 4.01-8.0    | 71       | 23.05%  |
| 2.01-3.0    | 56       | 18.18%  |
| 3.01-4.0    | 43       | 13.96%  |
| 8.01-16.0   | 26       | 8.44%   |
| 0.51-1.0    | 17       | 5.52%   |
| 16.01-24.0  | 8        | 2.6%    |
| 32.01-64.0  | 4        | 1.3%    |
| 0.01-0.5    | 4        | 1.3%    |
| 24.01-32.0  | 3        | 0.97%   |
| 64.01-256.0 | 1        | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 82       | 29.82%  |
| 2      | 64       | 23.27%  |
| 3      | 48       | 17.45%  |
| 4      | 36       | 13.09%  |
| 5      | 14       | 5.09%   |
| 6      | 13       | 4.73%   |
| 7      | 6        | 2.18%   |
| 0      | 5        | 1.82%   |
| 8      | 3        | 1.09%   |
| 11     | 2        | 0.73%   |
| 9      | 2        | 0.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 63.33%  |
| Yes       | 99       | 36.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 264      | 98.88%  |
| No        | 3        | 1.12%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 136      | 50.75%  |
| Yes       | 132      | 49.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 173      | 64.31%  |
| Yes       | 96       | 35.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Norway  | 267      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Oslo          | 56       | 20.07%  |
| Trondheim     | 19       | 6.81%   |
| Stavanger     | 12       | 4.3%    |
| Bergen        | 9        | 3.23%   |
| Kristiansand  | 8        | 2.87%   |
| Sandefjord    | 6        | 2.15%   |
| Ålesund      | 6        | 2.15%   |
| Skien         | 5        | 1.79%   |
| Drammen       | 5        | 1.79%   |
| Nesttun       | 4        | 1.43%   |
| Kongsberg     | 4        | 1.43%   |
| Tromsø       | 3        | 1.08%   |
| Lillehammer   | 3        | 1.08%   |
| Harstad       | 3        | 1.08%   |
| Fornebu       | 3        | 1.08%   |
| Fetsund       | 3        | 1.08%   |
| Arendal       | 3        | 1.08%   |
| Vollen        | 2        | 0.72%   |
| Vennesla      | 2        | 0.72%   |
| Vanse         | 2        | 0.72%   |
| Storebo       | 2        | 0.72%   |
| Stokmarknes   | 2        | 0.72%   |
| Stjordal      | 2        | 0.72%   |
| Soreide       | 2        | 0.72%   |
| Sarpsborg     | 2        | 0.72%   |
| Sandnes       | 2        | 0.72%   |
| Ramfjordbotn  | 2        | 0.72%   |
| Porsgrunn     | 2        | 0.72%   |
| Mysen         | 2        | 0.72%   |
| Mo i Rana     | 2        | 0.72%   |
| Mjondalen     | 2        | 0.72%   |
| Lillestrøm   | 2        | 0.72%   |
| Lillesand     | 2        | 0.72%   |
| Kopervik      | 2        | 0.72%   |
| Jessheim      | 2        | 0.72%   |
| Honefoss      | 2        | 0.72%   |
| Holter        | 2        | 0.72%   |
| Heimdal       | 2        | 0.72%   |
| Haugesund     | 2        | 0.72%   |
| Fannrem       | 2        | 0.72%   |
| Egersund      | 2        | 0.72%   |
| Asker         | 2        | 0.72%   |
| As            | 2        | 0.72%   |
| Voyenenga     | 1        | 0.36%   |
| Tønsberg     | 1        | 0.36%   |
| Tranby        | 1        | 0.36%   |
| Svortland     | 1        | 0.36%   |
| Straume       | 1        | 0.36%   |
| Storsteinnes  | 1        | 0.36%   |
| Storas        | 1        | 0.36%   |
| Steinkjer     | 1        | 0.36%   |
| Sortland      | 1        | 0.36%   |
| Soknedal      | 1        | 0.36%   |
| Slattum       | 1        | 0.36%   |
| Skodje        | 1        | 0.36%   |
| Skjetten      | 1        | 0.36%   |
| Skeie         | 1        | 0.36%   |
| Skedsmokorset | 1        | 0.36%   |
| Sandvika      | 1        | 0.36%   |
| Saetre        | 1        | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives  | Percent |
|---------------------|----------|---------|---------|
| Samsung Electronics | 136      | 230     | 25.61%  |
| Seagate             | 100      | 194     | 18.83%  |
| WDC                 | 80       | 180     | 15.07%  |
| Kingston            | 50       | 73      | 9.42%   |
| Crucial             | 23       | 39      | 4.33%   |
| Intel               | 21       | 25      | 3.95%   |
| Toshiba             | 17       | 21      | 3.2%    |
| Corsair             | 16       | 24      | 3.01%   |
| Phison              | 13       | 17      | 2.45%   |
| Hitachi             | 13       | 17      | 2.45%   |
| HGST                | 10       | 17      | 1.88%   |
| SanDisk             | 9        | 13      | 1.69%   |
| OCZ                 | 9        | 9       | 1.69%   |
| PNY                 | 4        | 6       | 0.75%   |
| LITEONIT            | 4        | 4       | 0.75%   |
| Micron Technology   | 3        | 5       | 0.56%   |
| Apple               | 3        | 3       | 0.56%   |
| Silicon Motion      | 2        | 3       | 0.38%   |
| Intenso             | 2        | 2       | 0.38%   |
| Unknown             | 1        | 1       | 0.19%   |
| SPCC                | 1        | 1       | 0.19%   |
| SK hynix            | 1        | 1       | 0.19%   |
| SandForce           | 1        | 2       | 0.19%   |
| Radeon              | 1        | 1       | 0.19%   |
| Netac               | 1        | 1       | 0.19%   |
| MBED                | 1        | 1       | 0.19%   |
| LITEON              | 1        | 1       | 0.19%   |
| LDLC                | 1        | 1       | 0.19%   |
| KingSpec            | 1        | 2       | 0.19%   |
| JMicron Technology  | 1        | Unknown | 0.19%   |
| IET                 | 1        | 2       | 0.19%   |
| Goodram             | 1        | 1       | 0.19%   |
| Advantech           | 1        | 1       | 0.19%   |
| A-DATA Technology   | 1        | 1       | 0.19%   |
| Unknown             | 1        | 2       | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB            | 11       | 1.66%   |
| Samsung SSD 860 EVO 1TB              | 10       | 1.51%   |
| Samsung SSD 840 EVO 250GB            | 10       | 1.51%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 8        | 1.21%   |
| Seagate ST4000DM004-2CV104 4TB       | 8        | 1.21%   |
| Samsung SSD 850 EVO 500GB            | 8        | 1.21%   |
| Kingston SV300S37A120G 120GB SSD     | 8        | 1.21%   |
| WDC WD30EFRX-68EUZN0 3TB             | 7        | 1.06%   |
| Seagate ST2000DM001-1ER164 2TB       | 7        | 1.06%   |
| Samsung SSD 970 EVO Plus 1TB         | 7        | 1.06%   |
| Samsung SSD 860 EVO 500GB            | 7        | 1.06%   |
| Samsung NVMe SSD Drive 1TB           | 7        | 1.06%   |
| Kingston NVMe SSD Drive 1TB          | 7        | 1.06%   |
| Seagate ST1000DM003-1CH162 1TB       | 6        | 0.9%    |
| Samsung NVMe SSD Drive 500GB         | 6        | 0.9%    |
| Seagate ST1000DM010-2EP102 1TB       | 5        | 0.75%   |
| Samsung NVMe SSD Drive 256GB         | 5        | 0.75%   |
| Phison NVMe SSD Drive 1TB            | 5        | 0.75%   |
| Toshiba HDWD110 1TB                  | 4        | 0.6%    |
| Seagate ST4000VN008-2DR166 4TB       | 4        | 0.6%    |
| Seagate ST2000DM006-2DM164 2TB       | 4        | 0.6%    |
| Seagate ST2000DM001-9YN164 2TB       | 4        | 0.6%    |
| Seagate Backup+ Hub BK 4TB           | 4        | 0.6%    |
| Samsung SSD 860 EVO 250GB            | 4        | 0.6%    |
| Samsung SSD 840 EVO 120GB            | 4        | 0.6%    |
| Samsung NVMe SSD Drive 512GB         | 4        | 0.6%    |
| Samsung NVMe SSD Drive 250GB         | 4        | 0.6%    |
| Samsung MZ7LF192HCGS-000L1 192GB SSD | 4        | 0.6%    |
| Samsung HD753LJ 752GB                | 4        | 0.6%    |
| Samsung HD103SJ 1TB                  | 4        | 0.6%    |
| Kingston SUV400S37240G 240GB SSD     | 4        | 0.6%    |
| Kingston SA2000M81000G 1TB           | 4        | 0.6%    |
| WDC WD30EFRX-68AX9N0 3TB             | 3        | 0.45%   |
| WDC WD10EALX-009BA0 1TB              | 3        | 0.45%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 3        | 0.45%   |
| Toshiba NVMe SSD Drive 256GB         | 3        | 0.45%   |
| Seagate ST8000VN004-2M2101 8TB       | 3        | 0.45%   |
| Seagate ST4000DM005-2DP166 4TB       | 3        | 0.45%   |
| Seagate ST4000DM000-1F2168 4TB       | 3        | 0.45%   |
| Seagate ST3000DM008-2DM166 3TB       | 3        | 0.45%   |
| Seagate ST3000DM001-1ER166 3TB       | 3        | 0.45%   |
| Seagate BUP Slim BK 1TB              | 3        | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB       | 3        | 0.45%   |
| Samsung SSD 960 PRO 512GB            | 3        | 0.45%   |
| Samsung SSD 960 PRO 1TB              | 3        | 0.45%   |
| Samsung SSD 960 EVO 500GB            | 3        | 0.45%   |
| Samsung SSD 860 QVO 1TB              | 3        | 0.45%   |
| Samsung SSD 850 EVO 120GB            | 3        | 0.45%   |
| Samsung SSD 840 PRO Series 256GB     | 3        | 0.45%   |
| Samsung SP2504C 250GB                | 3        | 0.45%   |
| Samsung NVMe SSD Drive 2TB           | 3        | 0.45%   |
| Phison NVMe SSD Drive 960GB          | 3        | 0.45%   |
| Kingston SV300S37A480G 480GB SSD     | 3        | 0.45%   |
| Kingston SV300S37A240G 240GB SSD     | 3        | 0.45%   |
| Kingston SHFS37A240G 240GB SSD       | 3        | 0.45%   |
| Kingston SA400S37120G 120GB SSD      | 3        | 0.45%   |
| Kingston NVMe SSD Drive 500GB        | 3        | 0.45%   |
| Kingston NVMe SSD Drive 250GB        | 3        | 0.45%   |
| Intel SSDPEKNW010T8 1TB              | 3        | 0.45%   |
| Crucial CT500MX500SSD1 500GB         | 3        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 97       | 190    | 42.54%  |
| WDC                 | 68       | 148    | 29.82%  |
| Samsung Electronics | 22       | 34     | 9.65%   |
| Toshiba             | 13       | 14     | 5.7%    |
| Hitachi             | 13       | 17     | 5.7%    |
| HGST                | 10       | 17     | 4.39%   |
| Apple               | 3        | 3      | 1.32%   |
| Intenso             | 1        | 1      | 0.44%   |
| IET                 | 1        | 2      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 88       | 130    | 41.12%  |
| Kingston            | 34       | 46     | 15.89%  |
| Crucial             | 21       | 37     | 9.81%   |
| Intel               | 13       | 17     | 6.07%   |
| WDC                 | 12       | 22     | 5.61%   |
| Corsair             | 10       | 14     | 4.67%   |
| OCZ                 | 9        | 9      | 4.21%   |
| SanDisk             | 5        | 5      | 2.34%   |
| PNY                 | 4        | 6      | 1.87%   |
| LITEONIT            | 4        | 4      | 1.87%   |
| Micron Technology   | 3        | 5      | 1.4%    |
| SPCC                | 1        | 1      | 0.47%   |
| SK hynix            | 1        | 1      | 0.47%   |
| SandForce           | 1        | 2      | 0.47%   |
| Radeon              | 1        | 1      | 0.47%   |
| LITEON              | 1        | 1      | 0.47%   |
| LDLC                | 1        | 1      | 0.47%   |
| KingSpec            | 1        | 2      | 0.47%   |
| Intenso             | 1        | 1      | 0.47%   |
| Goodram             | 1        | 1      | 0.47%   |
| A-DATA Technology   | 1        | 1      | 0.47%   |
| Unknown             | 1        | 2      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 176      | 426    | 38.85%  |
| SSD     | 170      | 309    | 37.53%  |
| NVMe    | 100      | 160    | 22.08%  |
| Unknown | 7        | 6      | 1.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 231      | 710    | 65.63%  |
| NVMe | 100      | 160    | 28.41%  |
| SAS  | 21       | 31     | 5.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 178      | 332    | 43.95%  |
| 0.51-1.0   | 104      | 160    | 25.68%  |
| 1.01-2.0   | 40       | 73     | 9.88%   |
| 3.01-4.0   | 32       | 56     | 7.9%    |
| 2.01-3.0   | 30       | 57     | 7.41%   |
| 4.01-10.0  | 21       | 57     | 5.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 62       | 21.75%  |
| More than 3000 | 49       | 17.19%  |
| 501-1000       | 42       | 14.74%  |
| 251-500        | 39       | 13.68%  |
| 1001-2000      | 34       | 11.93%  |
| 2001-3000      | 17       | 5.96%   |
| Unknown        | 16       | 5.61%   |
| 1-20           | 12       | 4.21%   |
| 51-100         | 10       | 3.51%   |
| 21-50          | 4        | 1.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 81       | 27.18%  |
| 101-250        | 32       | 10.74%  |
| 501-1000       | 32       | 10.74%  |
| 51-100         | 31       | 10.4%   |
| 251-500        | 28       | 9.4%    |
| 1001-2000      | 25       | 8.39%   |
| More than 3000 | 22       | 7.38%   |
| 21-50          | 22       | 7.38%   |
| Unknown        | 16       | 5.37%   |
| 2001-3000      | 8        | 2.68%   |
| 0              | 1        | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                  | Desktops | Drives | Percent |
|----------------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00UU3A0 500GB           | 2        | 5      | 5.56%   |
| WDC WD30EFRX-68EUZN0 3TB               | 2        | 2      | 5.56%   |
| Seagate ST31000524AS 1TB               | 2        | 2      | 5.56%   |
| WDC WD800JB-00CRA1 80GB                | 1        | 1      | 2.78%   |
| WDC WD800BB-00CAA1 80GB                | 1        | 1      | 2.78%   |
| WDC WD60EFRX-68L0BN1 6TB               | 1        | 1      | 2.78%   |
| WDC WD5000AAJS-00YFA0 500GB            | 1        | 1      | 2.78%   |
| WDC WD3200AAKS-00V1A0 320GB            | 1        | 1      | 2.78%   |
| WDC WD10EALX-009BA0 1TB                | 1        | 1      | 2.78%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 1        | 1      | 2.78%   |
| Toshiba HDWD110 1TB                    | 1        | 1      | 2.78%   |
| Seagate ST9250827AS 250GB              | 1        | 1      | 2.78%   |
| Seagate ST4000VN008-2DR166 4TB         | 1        | 1      | 2.78%   |
| Seagate ST4000LM024-2AN17V 4TB         | 1        | 1      | 2.78%   |
| Seagate ST3500418AS 500GB              | 1        | 1      | 2.78%   |
| Seagate ST31000528AS 1TB               | 1        | 1      | 2.78%   |
| Seagate ST3000DM008-2DM166 3TB         | 1        | 1      | 2.78%   |
| Seagate ST3000DM001-1CH166 3TB         | 1        | 7      | 2.78%   |
| Seagate ST2000DM001-1E6164 2TB         | 1        | 1      | 2.78%   |
| Seagate ST1000DM010-2EP102 1TB         | 1        | 1      | 2.78%   |
| Seagate ST1000DM003-1CH162 1TB         | 1        | 1      | 2.78%   |
| SanDisk SSD PLUS 1000GB                | 1        | 1      | 2.78%   |
| Samsung Electronics SSD 970 EVO 500GB  | 1        | 1      | 2.78%   |
| Samsung Electronics SSD 840 EVO 250GB  | 1        | 1      | 2.78%   |
| Samsung Electronics SP1614C 160GB      | 1        | 1      | 2.78%   |
| OCZ VERTEX3 240GB SSD                  | 1        | 1      | 2.78%   |
| LITEON LCH-256V2S-11 2.5 7mm 256GB SSD | 1        | 1      | 2.78%   |
| Intel SSDSC2CT120A3 120GB              | 1        | 1      | 2.78%   |
| Intel SSDPEKKW256G7 256GB              | 1        | 1      | 2.78%   |
| Hitachi HTS541612J9SA00 120GB          | 1        | 1      | 2.78%   |
| Hitachi HDS722020ALA330 2TB            | 1        | 1      | 2.78%   |
| HGST HDS724040ALE640 4TB               | 1        | 2      | 2.78%   |
| Crucial CT1000P1SSD8 1TB               | 1        | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 18     | 32.35%  |
| WDC                 | 10       | 14     | 29.41%  |
| Samsung Electronics | 3        | 3      | 8.82%   |
| Intel               | 2        | 2      | 5.88%   |
| Hitachi             | 2        | 2      | 5.88%   |
| Toshiba             | 1        | 1      | 2.94%   |
| SanDisk             | 1        | 1      | 2.94%   |
| OCZ                 | 1        | 1      | 2.94%   |
| LITEON              | 1        | 1      | 2.94%   |
| HGST                | 1        | 2      | 2.94%   |
| Crucial             | 1        | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 18     | 42.31%  |
| WDC                 | 10       | 14     | 38.46%  |
| Hitachi             | 2        | 2      | 7.69%   |
| Toshiba             | 1        | 1      | 3.85%   |
| Samsung Electronics | 1        | 1      | 3.85%   |
| HGST                | 1        | 2      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 38     | 75%     |
| SSD  | 5        | 5      | 15.63%  |
| NVMe | 3        | 3      | 9.38%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB    | 3        | 3      | 75%     |
| Kingston SV300S37A120G 120GB SSD | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Apple    | 3        | 3      | 75%     |
| Kingston | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 163      | 545    | 53.44%  |
| Works    | 107      | 306    | 35.08%  |
| Malfunc  | 31       | 46     | 10.16%  |
| Failed   | 4        | 4      | 1.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 161      | 38.7%   |
| AMD                              | 104      | 25%     |
| Samsung Electronics              | 50       | 12.02%  |
| ASMedia Technology               | 20       | 4.81%   |
| Phison Electronics               | 18       | 4.33%   |
| Kingston Technology Company      | 18       | 4.33%   |
| SanDisk                          | 11       | 2.64%   |
| LSI Logic / Symbios Logic        | 6        | 1.44%   |
| Nvidia                           | 5        | 1.2%    |
| JMicron Technology               | 5        | 1.2%    |
| Toshiba America Info Systems     | 4        | 0.96%   |
| Marvell Technology Group         | 4        | 0.96%   |
| Silicon Motion                   | 2        | 0.48%   |
| Micron/Crucial Technology        | 2        | 0.48%   |
| Broadcom / LSI                   | 2        | 0.48%   |
| Silicon Integrated Systems [SiS] | 1        | 0.24%   |
| Silicon Image                    | 1        | 0.24%   |
| Seagate Technology               | 1        | 0.24%   |
| ADATA Technology                 | 1        | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 65       | 12.92%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 28       | 5.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 23       | 4.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 23       | 4.57%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 19       | 3.78%   |
| AMD 400 Series Chipset SATA Controller                                           | 19       | 3.78%   |
| Intel SATA Controller [RAID mode]                                                | 17       | 3.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 17       | 3.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 17       | 3.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 15       | 2.98%   |
| AMD 500 Series Chipset SATA Controller                                           | 15       | 2.98%   |
| Kingston Company A2000 NVMe SSD                                                  | 13       | 2.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 10       | 1.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 9        | 1.79%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 9        | 1.79%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 9        | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 9        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 9        | 1.79%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 8        | 1.59%   |
| Phison E12 NVMe Controller                                                       | 8        | 1.59%   |
| AMD 300 Series Chipset SATA Controller                                           | 6        | 1.19%   |
| Intel SSD 660P Series                                                            | 5        | 0.99%   |
| AMD X370 Series Chipset SATA Controller                                          | 5        | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 5        | 0.99%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 5        | 0.99%   |
| AMD SB600 IDE                                                                    | 5        | 0.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4        | 0.8%    |
| JMicron JMB362 SATA Controller                                                   | 4        | 0.8%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 4        | 0.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4        | 0.8%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 3        | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3        | 0.6%    |
| Kingston Company KC2000 NVMe SSD                                                 | 3        | 0.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3        | 0.6%    |
| Intel Comet Lake SATA AHCI Controller                                            | 3        | 0.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3        | 0.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3        | 0.6%    |
| AMD FCH IDE Controller                                                           | 3        | 0.6%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2        | 0.4%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2        | 0.4%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2        | 0.4%    |
| Phison E18 PCIe4 NVMe Controller                                                 | 2        | 0.4%    |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 2        | 0.4%    |
| Nvidia MCP61 SATA Controller                                                     | 2        | 0.4%    |
| Marvell Group 88SE91A3 SATA-600 Controller                                       | 2        | 0.4%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 2        | 0.4%    |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]          | 2        | 0.4%    |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                    | 2        | 0.4%    |
| Kingston Company Company Non-Volatile memory controller                          | 2        | 0.4%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 2        | 0.4%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2        | 0.4%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2        | 0.4%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2        | 0.4%    |
| AMD FCH SATA Controller D                                                        | 2        | 0.4%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1        | 0.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 0.2%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1        | 0.2%    |
| Silicon Integrated Systems [SiS] 182 SATA/RAID Controller                        | 1        | 0.2%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1        | 0.2%    |
| Seagate FireCuda 530 SSD                                                         | 1        | 0.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 235      | 58.46%  |
| NVMe | 101      | 25.12%  |
| IDE  | 38       | 9.45%   |
| RAID | 22       | 5.47%   |
| SAS  | 3        | 0.75%   |
| SCSI | 3        | 0.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 157      | 58.8%   |
| AMD    | 110      | 41.2%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor        | 10       | 3.73%   |
| AMD Ryzen 7 2700X Eight-Core Processor     | 8        | 2.99%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 7        | 2.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 6        | 2.24%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 6        | 2.24%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 6        | 2.24%   |
| AMD Ryzen 5 3600 6-Core Processor          | 6        | 2.24%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 5        | 1.87%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 5        | 1.87%   |
| Intel Core i7-5820K CPU @ 3.30GHz          | 4        | 1.49%   |
| Intel Core i7-3770K CPU @ 3.50GHz          | 4        | 1.49%   |
| Intel Core i7-2600K CPU @ 3.40GHz          | 4        | 1.49%   |
| Intel Core i5-4460 CPU @ 3.20GHz           | 4        | 1.49%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 4        | 1.49%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 4        | 1.49%   |
| AMD Athlon 64 X2 Dual Core Processor 5400+ | 4        | 1.49%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 3        | 1.12%   |
| Intel Core i7-6800K CPU @ 3.40GHz          | 3        | 1.12%   |
| Intel Core i5-6600K CPU @ 3.50GHz          | 3        | 1.12%   |
| Intel Core i5-4590 CPU @ 3.30GHz           | 3        | 1.12%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 3        | 1.12%   |
| AMD Ryzen 7 1700 Eight-Core Processor      | 3        | 1.12%   |
| AMD Ryzen 5 2600 Six-Core Processor        | 3        | 1.12%   |
| AMD FX-8350 Eight-Core Processor           | 3        | 1.12%   |
| AMD FX-6300 Six-Core Processor             | 3        | 1.12%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz        | 2        | 0.75%   |
| Intel Core i9-9900K CPU @ 3.60GHz          | 2        | 0.75%   |
| Intel Core i9-10900 CPU @ 2.80GHz          | 2        | 0.75%   |
| Intel Core i7-9700K CPU @ 3.60GHz          | 2        | 0.75%   |
| Intel Core i7-8700 CPU @ 3.20GHz           | 2        | 0.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz           | 2        | 0.75%   |
| Intel Core i7-6700 CPU @ 3.40GHz           | 2        | 0.75%   |
| Intel Core i7-2600 CPU @ 3.40GHz           | 2        | 0.75%   |
| Intel Core i5-9600K CPU @ 3.70GHz          | 2        | 0.75%   |
| Intel Core i5-7400 CPU @ 3.00GHz           | 2        | 0.75%   |
| Intel Core i5-4570S CPU @ 2.90GHz          | 2        | 0.75%   |
| Intel Core i5-3570K CPU @ 3.40GHz          | 2        | 0.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 2        | 0.75%   |
| Intel Core i5-10600K CPU @ 4.10GHz         | 2        | 0.75%   |
| Intel Core i3-4160 CPU @ 3.60GHz           | 2        | 0.75%   |
| Intel Core i3-3220 CPU @ 3.30GHz           | 2        | 0.75%   |
| Intel Core i3-2120 CPU @ 3.30GHz           | 2        | 0.75%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz       | 2        | 0.75%   |
| Intel Atom CPU D525 @ 1.80GHz              | 2        | 0.75%   |
| AMD Ryzen 9 3950X 16-Core Processor        | 2        | 0.75%   |
| AMD Ryzen 7 1700X Eight-Core Processor     | 2        | 0.75%   |
| AMD FX-6100 Six-Core Processor             | 2        | 0.75%   |
| AMD Athlon II X4 640 Processor             | 2        | 0.75%   |
| AMD A4-5300 APU with Radeon HD Graphics    | 2        | 0.75%   |
| AMD A10-6800K APU with Radeon HD Graphics  | 2        | 0.75%   |
| Intel Xeon CPU E5620 @ 2.40GHz             | 1        | 0.37%   |
| Intel Xeon CPU E5410 @ 2.33GHz             | 1        | 0.37%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz        | 1        | 0.37%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz         | 1        | 0.37%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz        | 1        | 0.37%   |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz        | 1        | 0.37%   |
| Intel Xeon CPU E3-1245 v6 @ 3.70GHz        | 1        | 0.37%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz        | 1        | 0.37%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz        | 1        | 0.37%   |
| Intel Pentium III (Coppermine)             | 1        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 58       | 21.64%  |
| Intel Core i5           | 46       | 17.16%  |
| AMD Ryzen 7             | 25       | 9.33%   |
| AMD Ryzen 5             | 24       | 8.96%   |
| AMD Ryzen 9             | 20       | 7.46%   |
| Intel Core i3           | 13       | 4.85%   |
| Intel Xeon              | 11       | 4.1%    |
| AMD FX                  | 11       | 4.1%    |
| Intel Core i9           | 8        | 2.99%   |
| AMD Athlon 64 X2        | 6        | 2.24%   |
| Other                   | 4        | 1.49%   |
| Intel Pentium           | 4        | 1.49%   |
| AMD A10                 | 4        | 1.49%   |
| Intel Celeron           | 3        | 1.12%   |
| AMD Phenom II X4        | 3        | 1.12%   |
| Intel Pentium Dual-Core | 2        | 0.75%   |
| Intel Core 2 Duo        | 2        | 0.75%   |
| Intel Core 2            | 2        | 0.75%   |
| Intel Atom              | 2        | 0.75%   |
| AMD Ryzen Threadripper  | 2        | 0.75%   |
| AMD Athlon II X4        | 2        | 0.75%   |
| AMD Athlon              | 2        | 0.75%   |
| AMD A4                  | 2        | 0.75%   |
| Intel Pentium III       | 1        | 0.37%   |
| Intel Pentium Dual      | 1        | 0.37%   |
| Intel Core 2 Quad       | 1        | 0.37%   |
| AMD Sempron             | 1        | 0.37%   |
| AMD Ryzen 7 PRO         | 1        | 0.37%   |
| AMD Ryzen 3             | 1        | 0.37%   |
| AMD Phenom II X6        | 1        | 0.37%   |
| AMD EPYC                | 1        | 0.37%   |
| AMD Dual Core Opteron   | 1        | 0.37%   |
| AMD Athlon Dual Core    | 1        | 0.37%   |
| AMD A8                  | 1        | 0.37%   |
| AMD A6                  | 1        | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 98       | 36.57%  |
| 6      | 45       | 16.79%  |
| 2      | 45       | 16.79%  |
| 8      | 36       | 13.43%  |
| 12     | 16       | 5.97%   |
| 16     | 8        | 2.99%   |
| 10     | 6        | 2.24%   |
| 3      | 6        | 2.24%   |
| 1      | 5        | 1.87%   |
| 32     | 1        | 0.37%   |
| 28     | 1        | 0.37%   |
| 24     | 1        | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 262      | 98.13%  |
| 2      | 5        | 1.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 188      | 70.41%  |
| 1      | 79       | 29.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 262      | 98.13%  |
| Unknown        | 4        | 1.5%    |
| 32-bit         | 1        | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 72       | 26.18%  |
| 0x306c3    | 25       | 9.09%   |
| 0x306a9    | 18       | 6.55%   |
| 0x08701021 | 14       | 5.09%   |
| 0x506e3    | 13       | 4.73%   |
| 0x906e9    | 11       | 4%      |
| 0x206a7    | 8        | 2.91%   |
| 0x08701013 | 8        | 2.91%   |
| 0x306f2    | 6        | 2.18%   |
| 0x06000852 | 6        | 2.18%   |
| 0x0a201016 | 5        | 1.82%   |
| 0x0a201009 | 5        | 1.82%   |
| 0x06001119 | 5        | 1.82%   |
| 0x906ea    | 4        | 1.45%   |
| 0x406f1    | 4        | 1.45%   |
| 0x1067a    | 4        | 1.45%   |
| 0x0800820d | 4        | 1.45%   |
| 0x906ed    | 3        | 1.09%   |
| 0x906ec    | 3        | 1.09%   |
| 0x0a201204 | 3        | 1.09%   |
| 0xa0655    | 2        | 0.73%   |
| 0x6fb      | 2        | 0.73%   |
| 0x6f6      | 2        | 0.73%   |
| 0x206d7    | 2        | 0.73%   |
| 0x106e5    | 2        | 0.73%   |
| 0x106ca    | 2        | 0.73%   |
| 0x0a50000c | 2        | 0.73%   |
| 0x08001129 | 2        | 0.73%   |
| 0x06003104 | 2        | 0.73%   |
| 0x0600063e | 2        | 0.73%   |
| 0xa0671    | 1        | 0.36%   |
| 0xa0653    | 1        | 0.36%   |
| 0x906eb    | 1        | 0.36%   |
| 0x90672    | 1        | 0.36%   |
| 0x806e9    | 1        | 0.36%   |
| 0x6fd      | 1        | 0.36%   |
| 0x68a      | 1        | 0.36%   |
| 0x506c9    | 1        | 0.36%   |
| 0x50657    | 1        | 0.36%   |
| 0x50654    | 1        | 0.36%   |
| 0x40651    | 1        | 0.36%   |
| 0x306e4    | 1        | 0.36%   |
| 0x306d4    | 1        | 0.36%   |
| 0x30673    | 1        | 0.36%   |
| 0x206c2    | 1        | 0.36%   |
| 0x20652    | 1        | 0.36%   |
| 0x106a5    | 1        | 0.36%   |
| 0x0a201205 | 1        | 0.36%   |
| 0x08600104 | 1        | 0.36%   |
| 0x08301025 | 1        | 0.36%   |
| 0x08108109 | 1        | 0.36%   |
| 0x08101013 | 1        | 0.36%   |
| 0x0800820b | 1        | 0.36%   |
| 0x08001227 | 1        | 0.36%   |
| 0x08001138 | 1        | 0.36%   |
| 0x0800110e | 1        | 0.36%   |
| 0x0700010f | 1        | 0.36%   |
| 0x06001116 | 1        | 0.36%   |
| 0x06000626 | 1        | 0.36%   |
| 0x010000dc | 1        | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 36       | 13.48%  |
| Zen 2            | 29       | 10.86%  |
| KabyLake         | 29       | 10.86%  |
| IvyBridge        | 22       | 8.24%   |
| Zen 3            | 21       | 7.87%   |
| Skylake          | 20       | 7.49%   |
| Zen+             | 14       | 5.24%   |
| Piledriver       | 14       | 5.24%   |
| SandyBridge      | 12       | 4.49%   |
| Zen              | 11       | 4.12%   |
| K8 Hammer        | 9        | 3.37%   |
| CometLake        | 7        | 2.62%   |
| Broadwell        | 7        | 2.62%   |
| K10              | 6        | 2.25%   |
| Core             | 5        | 1.87%   |
| Penryn           | 4        | 1.5%    |
| Westmere         | 3        | 1.12%   |
| Nehalem          | 3        | 1.12%   |
| Bulldozer        | 3        | 1.12%   |
| Steamroller      | 2        | 0.75%   |
| Bonnell          | 2        | 0.75%   |
| Unknown          | 2        | 0.75%   |
| TigerLake        | 1        | 0.37%   |
| Silvermont       | 1        | 0.37%   |
| P6               | 1        | 0.37%   |
| Jaguar           | 1        | 0.37%   |
| Goldmont         | 1        | 0.37%   |
| Alderlake Hybrid | 1        | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 132      | 45.99%  |
| AMD                        | 87       | 30.31%  |
| Intel                      | 66       | 23%     |
| Matrox Electronics Systems | 2        | 0.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 20       | 6.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 16       | 5.52%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 14       | 4.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 10       | 3.45%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 10       | 3.45%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 9        | 3.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 2.41%   |
| Intel HD Graphics 530                                                       | 7        | 2.41%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 6        | 2.07%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.72%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5        | 1.72%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5        | 1.72%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.72%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 1.72%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 1.38%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.38%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.38%   |
| Nvidia GF108 [GeForce GT 630]                                               | 4        | 1.38%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 4        | 1.38%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 1.38%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 1.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.38%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 3        | 1.03%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 1.03%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 1.03%   |
| Intel HD Graphics 630                                                       | 3        | 1.03%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 3        | 1.03%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 0.69%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 2        | 0.69%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.69%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.69%   |
| Nvidia GT218 [ION]                                                          | 2        | 0.69%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.69%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 2        | 0.69%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 2        | 0.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 0.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 0.69%   |
| AMD RV770 [Radeon HD 4870]                                                  | 2        | 0.69%   |
| AMD Richland [Radeon HD 8670D]                                              | 2        | 0.69%   |
| AMD Renoir                                                                  | 2        | 0.69%   |
| AMD Pitcairn XT [Radeon HD 7870 GHz Edition]                                | 2        | 0.69%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 0.69%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 2        | 0.69%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 0.69%   |
| AMD Cezanne                                                                 | 2        | 0.69%   |
| AMD Cayman PRO [Radeon HD 6950]                                             | 2        | 0.69%   |
| AMD Barts PRO [Radeon HD 6850]                                              | 2        | 0.69%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.34%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.34%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.34%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.34%   |
| Nvidia NV44 [GeForce 7100 GS]                                               | 1        | 0.34%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.34%   |
| Nvidia GT215 [GeForce GT 320]                                               | 1        | 0.34%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.34%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 0.34%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.34%   |
| Nvidia GP106GL [Quadro P2200]                                               | 1        | 0.34%   |
| Nvidia GP106GL [Quadro P2000]                                               | 1        | 0.34%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 120      | 44.28%  |
| 1 x AMD        | 80       | 29.52%  |
| 1 x Intel      | 55       | 20.3%   |
| Intel + Nvidia | 4        | 1.48%   |
| AMD + Nvidia   | 4        | 1.48%   |
| 2 x Nvidia     | 3        | 1.11%   |
| 1 x Matrox     | 2        | 0.74%   |
| Intel + AMD    | 2        | 0.74%   |
| Other          | 1        | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 173      | 62.91%  |
| Proprietary | 92       | 33.45%  |
| Unknown     | 10       | 3.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 98       | 35.51%  |
| 7.01-8.0   | 50       | 18.12%  |
| 1.01-2.0   | 37       | 13.41%  |
| 3.01-4.0   | 21       | 7.61%   |
| 0.01-0.5   | 18       | 6.52%   |
| 0.51-1.0   | 14       | 5.07%   |
| 5.01-6.0   | 12       | 4.35%   |
| 8.01-16.0  | 12       | 4.35%   |
| 2.01-3.0   | 10       | 3.62%   |
| 4.01-5.0   | 2        | 0.72%   |
| 16.01-24.0 | 2        | 0.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 65       | 21.59%  |
| Dell                 | 34       | 11.3%   |
| AOC                  | 28       | 9.3%    |
| Acer                 | 26       | 8.64%   |
| BenQ                 | 24       | 7.97%   |
| Philips              | 21       | 6.98%   |
| Ancor Communications | 21       | 6.98%   |
| Hewlett-Packard      | 13       | 4.32%   |
| ASUSTek Computer     | 9        | 2.99%   |
| Goldstar             | 7        | 2.33%   |
| Lenovo               | 6        | 1.99%   |
| NEC Computers        | 4        | 1.33%   |
| LG Electronics       | 3        | 1%      |
| HVR                  | 3        | 1%      |
| Grundig              | 3        | 1%      |
| Eizo                 | 3        | 1%      |
| AUS                  | 3        | 1%      |
| VOXICON              | 2        | 0.66%   |
| Unknown              | 2        | 0.66%   |
| Sony                 | 2        | 0.66%   |
| ViewSonic            | 1        | 0.33%   |
| Vestel Elektronik    | 1        | 0.33%   |
| Vestel               | 1        | 0.33%   |
| Toshiba              | 1        | 0.33%   |
| Sharp                | 1        | 0.33%   |
| Positivo             | 1        | 0.33%   |
| Pioneer Electronic   | 1        | 0.33%   |
| Panasonic            | 1        | 0.33%   |
| Packard Bell         | 1        | 0.33%   |
| MSI                  | 1        | 0.33%   |
| Medion               | 1        | 0.33%   |
| Matrox               | 1        | 0.33%   |
| Lenovo Group Limited | 1        | 0.33%   |
| ITE                  | 1        | 0.33%   |
| Iiyama               | 1        | 0.33%   |
| Gigabyte Technology  | 1        | 0.33%   |
| FUS                  | 1        | 0.33%   |
| Denver               | 1        | 0.33%   |
| CVT                  | 1        | 0.33%   |
| Compaq Computer      | 1        | 0.33%   |
| CHR                  | 1        | 0.33%   |
| Unknown              | 1        | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 5        | 1.53%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch   | 4        | 1.23%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 4        | 1.23%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                       | 4        | 1.23%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                         | 3        | 0.92%   |
| Hewlett-Packard Z32x HWP3275 3840x2160 697x392mm 31.5-inch             | 3        | 0.92%   |
| Grundig WUXGA GRU4448 1920x1080 1210x680mm 54.6-inch                   | 3        | 0.92%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 3        | 0.92%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                     | 3        | 0.92%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch           | 3        | 0.92%   |
| AOC AG273QS3R4 AOC2730 2560x1440 597x336mm 27.0-inch                   | 3        | 0.92%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 3        | 0.92%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 521x293mm 23.5-inch  | 3        | 0.92%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 2        | 0.61%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 459x296mm 21.5-inch   | 2        | 0.61%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch       | 2        | 0.61%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 0.61%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 2        | 0.61%   |
| Samsung Electronics LCD Monitor SAM0F0B 3840x2160 1210x680mm 54.6-inch | 2        | 0.61%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch    | 2        | 0.61%   |
| Samsung Electronics C34H89x SAM0E25 3440x1440 797x333mm 34.0-inch      | 2        | 0.61%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch      | 2        | 0.61%   |
| Philips LCD Monitor FTV 1920x1080                                      | 2        | 0.61%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                       | 2        | 0.61%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch              | 2        | 0.61%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 0.61%   |
| Eizo S2402W ENC1996 1920x1200 519x324mm 24.1-inch                      | 2        | 0.61%   |
| Dell U2713HM DEL4080 2560x1440 597x336mm 27.0-inch                     | 2        | 0.61%   |
| Dell P2212H DELA07F 1920x1080 531x299mm 24.0-inch                      | 2        | 0.61%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 2        | 0.61%   |
| ASUSTek Computer VZ249 AUS24CC 1920x1080 527x296mm 23.8-inch           | 2        | 0.61%   |
| AOC AG352QG2 AOC3520 2560x1080 820x346mm 35.0-inch                     | 2        | 0.61%   |
| Ancor Communications VG248 ACI24A5 1920x1080 531x299mm 24.0-inch       | 2        | 0.61%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 2        | 0.61%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 0.61%   |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch  | 2        | 0.61%   |
| Acer XB271HU ACR0490 2560x1440 598x336mm 27.0-inch                     | 2        | 0.61%   |
| VOXICON D32QO DUS3200 2560x1440 708x398mm 32.0-inch                    | 1        | 0.31%   |
| VOXICON D27Q0 DUS2700 2560x1440 597x336mm 27.0-inch                    | 1        | 0.31%   |
| ViewSonic VA2216w SERIE VSC2920 1680x1050 465x291mm 21.6-inch          | 1        | 0.31%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                              | 1        | 0.31%   |
| Vestel Elektronik 39FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch  | 1        | 0.31%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1        | 0.31%   |
| Unknown LCD Monitor Dell U4919DW 5120x1440                             | 1        | 0.31%   |
| Toshiba TV TSB1206 1360x768                                            | 1        | 0.31%   |
| Sony TV SNYEE01 1920x1080                                              | 1        | 0.31%   |
| Sony TV SNY2C02 1920x1080 708x398mm 32.0-inch                          | 1        | 0.31%   |
| Sharp LCD Monitor HDMI 1920x1080                                       | 1        | 0.31%   |
| Sharp HDMI SHP10AB 1920x1080 1329x748mm 60.0-inch                      | 1        | 0.31%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch      | 1        | 0.31%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch      | 1        | 0.31%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch      | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch   | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch   | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM0458 1360x768                        | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM043F 1920x1200 520x320mm 24.0-inch   | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM0423 1920x1200                       | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM03E6 1920x1200 550x340mm 25.5-inch   | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 380x300mm 19.1-inch   | 1        | 0.31%   |
| Samsung Electronics SMS27A550H SAM07CB 1680x1050 600x340mm 27.2-inch   | 1        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 121      | 41.3%   |
| 3840x2160 (4K)     | 41       | 13.99%  |
| 2560x1440 (QHD)    | 34       | 11.6%   |
| 1920x1200 (WUXGA)  | 19       | 6.48%   |
| 3440x1440          | 16       | 5.46%   |
| 3840x1080          | 11       | 3.75%   |
| Unknown            | 11       | 3.75%   |
| 1680x1050 (WSXGA+) | 9        | 3.07%   |
| 1280x1024 (SXGA)   | 6        | 2.05%   |
| 2560x1080          | 3        | 1.02%   |
| 2160x1200          | 3        | 1.02%   |
| 1600x1200          | 3        | 1.02%   |
| 5120x1440          | 2        | 0.68%   |
| 4480x1440          | 2        | 0.68%   |
| 3840x1600          | 2        | 0.68%   |
| 1360x768           | 2        | 0.68%   |
| 7680x1440          | 1        | 0.34%   |
| 7680x1080          | 1        | 0.34%   |
| 5760x2160          | 1        | 0.34%   |
| 5360x1440          | 1        | 0.34%   |
| 3840x1200          | 1        | 0.34%   |
| 3840x1024          | 1        | 0.34%   |
| 2560x1600          | 1        | 0.34%   |
| 1280x720 (HD)      | 1        | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 71       | 24.23%  |
| 27      | 55       | 18.77%  |
| Unknown | 46       | 15.7%   |
| 23      | 26       | 8.87%   |
| 34      | 14       | 4.78%   |
| 31      | 12       | 4.1%    |
| 21      | 9        | 3.07%   |
| 84      | 8        | 2.73%   |
| 48      | 8        | 2.73%   |
| 22      | 7        | 2.39%   |
| 54      | 5        | 1.71%   |
| 19      | 5        | 1.71%   |
| 25      | 4        | 1.37%   |
| 35      | 3        | 1.02%   |
| 32      | 3        | 1.02%   |
| 37      | 2        | 0.68%   |
| 33      | 2        | 0.68%   |
| 20      | 2        | 0.68%   |
| 72      | 1        | 0.34%   |
| 65      | 1        | 0.34%   |
| 60      | 1        | 0.34%   |
| 55      | 1        | 0.34%   |
| 44      | 1        | 0.34%   |
| 43      | 1        | 0.34%   |
| 40      | 1        | 0.34%   |
| 39      | 1        | 0.34%   |
| 30      | 1        | 0.34%   |
| 26      | 1        | 0.34%   |
| 18      | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 135      | 48.91%  |
| Unknown     | 46       | 16.67%  |
| 601-700     | 20       | 7.25%   |
| 701-800     | 18       | 6.52%   |
| 401-500     | 17       | 6.16%   |
| 1001-1500   | 16       | 5.8%    |
| 1501-2000   | 9        | 3.26%   |
| 801-900     | 8        | 2.9%    |
| 351-400     | 6        | 2.17%   |
| 901-1000    | 1        | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 160      | 59.48%  |
| Unknown | 37       | 13.75%  |
| 16/10   | 34       | 12.64%  |
| 21/9    | 19       | 7.06%   |
| 32/9    | 8        | 2.97%   |
| 5/4     | 5        | 1.86%   |
| 4/3     | 2        | 0.74%   |
| 3/2     | 2        | 0.74%   |
| 6/5     | 1        | 0.37%   |
| 3.76    | 1        | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 81       | 28.72%  |
| 301-350        | 56       | 19.86%  |
| Unknown        | 46       | 16.31%  |
| 351-500        | 34       | 12.06%  |
| 251-300        | 26       | 9.22%   |
| More than 1000 | 17       | 6.03%   |
| 501-1000       | 12       | 4.26%   |
| 151-200        | 10       | 3.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 151      | 55.31%  |
| Unknown | 46       | 16.85%  |
| 101-120 | 45       | 16.48%  |
| 121-160 | 13       | 4.76%   |
| 1-50    | 11       | 4.03%   |
| 161-240 | 7        | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 184      | 67.9%   |
| 2     | 55       | 20.3%   |
| 0     | 19       | 7.01%   |
| 3     | 11       | 4.06%   |
| 4     | 2        | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel                                  | 159      | 40.46%  |
| Realtek Semiconductor                  | 114      | 29.01%  |
| Qualcomm Atheros                       | 21       | 5.34%   |
| Broadcom                               | 15       | 3.82%   |
| NetGear                                | 9        | 2.29%   |
| Ralink                                 | 7        | 1.78%   |
| Ralink Technology                      | 6        | 1.53%   |
| TP-Link                                | 5        | 1.27%   |
| Nvidia                                 | 5        | 1.27%   |
| ASUSTek Computer                       | 5        | 1.27%   |
| Samsung Electronics                    | 4        | 1.02%   |
| Motorola PCS                           | 4        | 1.02%   |
| Linksys                                | 4        | 1.02%   |
| Aquantia                               | 4        | 1.02%   |
| Microchip Technology                   | 3        | 0.76%   |
| Marvell Technology Group               | 3        | 0.76%   |
| Chu Yuen Enterprise                    | 3        | 0.76%   |
| ASIX Electronics                       | 3        | 0.76%   |
| Sigma Designs                          | 2        | 0.51%   |
| Qualcomm Atheros Communications        | 2        | 0.51%   |
| Microsoft                              | 2        | 0.51%   |
| Winbond Electronics                    | 1        | 0.25%   |
| Wacom                                  | 1        | 0.25%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.25%   |
| SEGGER                                 | 1        | 0.25%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.25%   |
| MediaTek                               | 1        | 0.25%   |
| Huawei Technologies                    | 1        | 0.25%   |
| Holtek Semiconductor                   | 1        | 0.25%   |
| DisplayLink                            | 1        | 0.25%   |
| Cisco Systems                          | 1        | 0.25%   |
| ATEN International                     | 1        | 0.25%   |
| Arduino SA                             | 1        | 0.25%   |
| 3Com                                   | 1        | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 91       | 19.65%  |
| Intel I211 Gigabit Network Connection                             | 38       | 8.21%   |
| Intel Wi-Fi 6 AX200                                               | 28       | 6.05%   |
| Intel Ethernet Connection (2) I219-V                              | 20       | 4.32%   |
| Intel Ethernet Controller I225-V                                  | 13       | 2.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 2.16%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 8        | 1.73%   |
| Intel Ethernet Connection (7) I219-V                              | 8        | 1.73%   |
| Intel Ethernet Connection (2) I218-V                              | 8        | 1.73%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 1.73%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 7        | 1.51%   |
| Intel I210 Gigabit Network Connection                             | 6        | 1.3%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 1.08%   |
| Intel Wireless-AC 9260                                            | 5        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5        | 1.08%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.08%   |
| Motorola PCS moto g pure                                          | 4        | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.86%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.65%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3        | 0.65%   |
| Microchip HTC Hub Controller                                      | 3        | 0.65%   |
| Intel Wireless 7265                                               | 3        | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 0.65%   |
| Intel Centrino Wireless-N 2230                                    | 3        | 0.65%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.65%   |
| Chu Yuen Enterprise GN-WB32L 802.11n USB WLAN Card                | 3        | 0.65%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 0.43%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                   | 2        | 0.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.43%   |
| Realtek 802.11ac NIC                                              | 2        | 0.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.43%   |
| Ralink RT5592 PCIe Wireless Network Adapter                       | 2        | 0.43%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 2        | 0.43%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2        | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.43%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.43%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.43%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2        | 0.43%   |
| Linksys WUSB6400M                                                 | 2        | 0.43%   |
| Intel Wireless 8260                                               | 2        | 0.43%   |
| Intel Wireless 7260                                               | 2        | 0.43%   |
| Intel Wireless 3160                                               | 2        | 0.43%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.43%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.43%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 62       | 44.29%  |
| Realtek Semiconductor           | 14       | 10%     |
| Qualcomm Atheros                | 10       | 7.14%   |
| Broadcom                        | 10       | 7.14%   |
| NetGear                         | 9        | 6.43%   |
| Ralink                          | 7        | 5%      |
| Ralink Technology               | 6        | 4.29%   |
| TP-Link                         | 5        | 3.57%   |
| ASUSTek Computer                | 5        | 3.57%   |
| Linksys                         | 3        | 2.14%   |
| Chu Yuen Enterprise             | 3        | 2.14%   |
| Qualcomm Atheros Communications | 2        | 1.43%   |
| Microsoft                       | 2        | 1.43%   |
| Wacom                           | 1        | 0.71%   |
| MediaTek                        | 1        | 0.71%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 28       | 20%     |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]               | 8        | 5.71%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                        | 7        | 5%      |
| Intel Wireless-AC 9260                                                    | 5        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 5        | 3.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 4        | 2.86%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                  | 3        | 2.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 3        | 2.14%   |
| Intel Wireless 7265                                                       | 3        | 2.14%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 3        | 2.14%   |
| Intel Centrino Wireless-N 2230                                            | 3        | 2.14%   |
| Chu Yuen Enterprise GN-WB32L 802.11n USB WLAN Card                        | 3        | 2.14%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                | 2        | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2        | 1.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 2        | 1.43%   |
| Realtek 802.11ac NIC                                                      | 2        | 1.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 2        | 1.43%   |
| Ralink RT5592 PCIe Wireless Network Adapter                               | 2        | 1.43%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                 | 2        | 1.43%   |
| Ralink RT2561/RT61 802.11g PCI                                            | 2        | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 2        | 1.43%   |
| Qualcomm Atheros AR9271 802.11n                                           | 2        | 1.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 2        | 1.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 2        | 1.43%   |
| Linksys WUSB6400M                                                         | 2        | 1.43%   |
| Intel Wireless 8260                                                       | 2        | 1.43%   |
| Intel Wireless 7260                                                       | 2        | 1.43%   |
| Intel Wireless 3160                                                       | 2        | 1.43%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                        | 2        | 1.43%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                  | 1        | 0.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 1        | 0.71%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1        | 0.71%   |
| TP-Link 802.11ac NIC                                                      | 1        | 0.71%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1        | 0.71%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1        | 0.71%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1        | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 0.71%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                   | 1        | 0.71%   |
| Ralink RT5572 Wireless Adapter                                            | 1        | 0.71%   |
| Ralink RT5370 Wireless Adapter                                            | 1        | 0.71%   |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1        | 0.71%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                         | 1        | 0.71%   |
| Ralink RT2800 802.11n PCI                                                 | 1        | 0.71%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1        | 0.71%   |
| NetGear WNDA3100v2 802.11abgn [Broadcom BCM4323]                          | 1        | 0.71%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1        | 0.71%   |
| Microsoft Wireless XBox Controller Dongle                                 | 1        | 0.71%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 1        | 0.71%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                         | 1        | 0.71%   |
| Intel Wireless 8265 / 8275                                                | 1        | 0.71%   |
| Intel Ultimate N WiFi Link 5300                                           | 1        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                           | 1        | 0.71%   |
| Intel Centrino Advanced-N 6235                                            | 1        | 0.71%   |
| Intel Alder Lake-S PCH CNVi WiFi                                          | 1        | 0.71%   |
| Broadcom Network controller                                               | 1        | 0.71%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]           | 1        | 0.71%   |
| ASUS USB-AC68 802.11a/b/g/n/ac (4x4) Wireless Adapter [Realtek RTL8814AU] | 1        | 0.71%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]       | 1        | 0.71%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                       | 1        | 0.71%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]            | 1        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 140      | 47.78%  |
| Realtek Semiconductor         | 109      | 37.2%   |
| Qualcomm Atheros              | 13       | 4.44%   |
| Nvidia                        | 5        | 1.71%   |
| Broadcom                      | 5        | 1.71%   |
| Samsung Electronics           | 4        | 1.37%   |
| Aquantia                      | 4        | 1.37%   |
| Marvell Technology Group      | 3        | 1.02%   |
| ASIX Electronics              | 3        | 1.02%   |
| OnePlus Technology (Shenzhen) | 1        | 0.34%   |
| Linksys                       | 1        | 0.34%   |
| Huawei Technologies           | 1        | 0.34%   |
| DisplayLink                   | 1        | 0.34%   |
| Cisco Systems                 | 1        | 0.34%   |
| ATEN International            | 1        | 0.34%   |
| 3Com                          | 1        | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 91       | 29.45%  |
| Intel I211 Gigabit Network Connection                             | 38       | 12.3%   |
| Intel Ethernet Connection (2) I219-V                              | 20       | 6.47%   |
| Intel Ethernet Controller I225-V                                  | 13       | 4.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 3.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 3.56%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 3.24%   |
| Intel Ethernet Connection (7) I219-V                              | 8        | 2.59%   |
| Intel Ethernet Connection (2) I218-V                              | 8        | 2.59%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 2.59%   |
| Intel I210 Gigabit Network Connection                             | 6        | 1.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 1.62%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 1.29%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.97%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.97%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.97%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.97%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.65%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.65%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.65%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2        | 0.65%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.65%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.65%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 0.65%   |
| ASIX AX88772                                                      | 2        | 0.65%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.32%   |
| Realtek RTL-8129                                                  | 1        | 0.32%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.32%   |
| OnePlus (Shenzhen) OnePlus                                        | 1        | 0.32%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.32%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.32%   |
| Linksys Gigabit Ethernet Adapter                                  | 1        | 0.32%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.32%   |
| Intel Ethernet Controller X550                                    | 1        | 0.32%   |
| Intel Ethernet Connection I219-V                                  | 1        | 0.32%   |
| Intel Ethernet Connection I218-V                                  | 1        | 0.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.32%   |
| Intel Ethernet Connection (13) I219-V                             | 1        | 0.32%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.32%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 0.32%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 0.32%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.32%   |
| Huawei LYA-L09                                                    | 1        | 0.32%   |
| DisplayLink ThinkPad USB 3.0 Dock                                 | 1        | 0.32%   |
| Cisco Systems VIC Ethernet NIC Dynamic                            | 1        | 0.32%   |
| Cisco Systems VIC Ethernet NIC                                    | 1        | 0.32%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1        | 0.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.32%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 0.32%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.32%   |
| ATEN International 10Mbps Ethernet [klsi]                         | 1        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 264      | 64.39%  |
| WiFi     | 132      | 32.2%   |
| Modem    | 8        | 1.95%   |
| Unknown  | 6        | 1.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 206      | 75.74%  |
| WiFi     | 65       | 23.9%   |
| Unknown  | 1        | 0.37%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 152      | 56.51%  |
| 2     | 95       | 35.32%  |
| 3     | 18       | 6.69%   |
| 0     | 3        | 1.12%   |
| 4     | 1        | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 247      | 90.81%  |
| Yes  | 25       | 9.19%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 52       | 53.61%  |
| Cambridge Silicon Radio         | 20       | 20.62%  |
| ASUSTek Computer                | 10       | 10.31%  |
| Belkin Components               | 4        | 4.12%   |
| HTC (High Tech Computer)        | 3        | 3.09%   |
| Broadcom                        | 3        | 3.09%   |
| Realtek Semiconductor           | 2        | 2.06%   |
| Qualcomm Atheros Communications | 1        | 1.03%   |
| MediaTek                        | 1        | 1.03%   |
| Integrated System Solution      | 1        | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 23       | 23.47%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 20       | 20.41%  |
| Intel Bluetooth wireless interface                                   | 10       | 10.2%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 7        | 7.14%   |
| Intel Bluetooth Device                                               | 6        | 6.12%   |
| Intel AX210 Bluetooth                                                | 4        | 4.08%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 3.06%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 3.06%   |
| Intel AX201 Bluetooth                                                | 3        | 3.06%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3        | 3.06%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 3        | 3.06%   |
| Realtek Bluetooth Radio                                              | 2        | 2.04%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 2        | 2.04%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 1.02%   |
| MediaTek Wireless_Device                                             | 1        | 1.02%   |
| Integrated System Solution Bluetooth Device                          | 1        | 1.02%   |
| Broadcom Bluetooth 3.0 Device                                        | 1        | 1.02%   |
| Broadcom Bluetooth 2.1 Device                                        | 1        | 1.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 1.02%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 1.02%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 1.02%   |
| ASUS ASUS USB-BT500                                                  | 1        | 1.02%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 149      | 27.44%  |
| AMD                                          | 134      | 24.68%  |
| Nvidia                                       | 131      | 24.13%  |
| C-Media Electronics                          | 16       | 2.95%   |
| Logitech                                     | 12       | 2.21%   |
| SteelSeries ApS                              | 11       | 2.03%   |
| Kingston Technology                          | 7        | 1.29%   |
| Blue Microphones                             | 7        | 1.29%   |
| Creative Labs                                | 5        | 0.92%   |
| Corsair                                      | 5        | 0.92%   |
| Texas Instruments                            | 4        | 0.74%   |
| GN Netcom                                    | 4        | 0.74%   |
| Focusrite-Novation                           | 4        | 0.74%   |
| ASUSTek Computer                             | 4        | 0.74%   |
| SAVITECH                                     | 3        | 0.55%   |
| Realtek Semiconductor                        | 3        | 0.55%   |
| Razer USA                                    | 3        | 0.55%   |
| Yamaha                                       | 2        | 0.37%   |
| XMOS                                         | 2        | 0.37%   |
| RODE Microphones                             | 2        | 0.37%   |
| M-Audio                                      | 2        | 0.37%   |
| GYROCOM C&C                                  | 2        | 0.37%   |
| FiiO Electronics Technology                  | 2        | 0.37%   |
| Creative Technology                          | 2        | 0.37%   |
| Asahi Kasei Microsystems                     | 2        | 0.37%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.18%   |
| www.hirestech.com 2010 REV 1.4               | 1        | 0.18%   |
| Sony                                         | 1        | 0.18%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.18%   |
| Shenzhen Riitek Technology                   | 1        | 0.18%   |
| Sennheiser Communications                    | 1        | 0.18%   |
| Schiit Audio                                 | 1        | 0.18%   |
| Samson Technologies                          | 1        | 0.18%   |
| ROCCAT                                       | 1        | 0.18%   |
| PS Audio                                     | 1        | 0.18%   |
| Plantronics                                  | 1        | 0.18%   |
| Nuforce                                      | 1        | 0.18%   |
| Musical Fidelity                             | 1        | 0.18%   |
| Micronas                                     | 1        | 0.18%   |
| Micro Star International                     | 1        | 0.18%   |
| Mackie Designs                               | 1        | 0.18%   |
| JMTek                                        | 1        | 0.18%   |
| Giga-Byte Technology                         | 1        | 0.18%   |
| Evolution Electronics                        | 1        | 0.18%   |
| Elgato Systems                               | 1        | 0.18%   |
| DCMT Technology                              | 1        | 0.18%   |
| B & W Group                                  | 1        | 0.18%   |
| AudioQuest                                   | 1        | 0.18%   |
| Audio-Technica                               | 1        | 0.18%   |
| Astro Gaming                                 | 1        | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 46       | 7.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 24       | 3.85%   |
| Nvidia GP104 High Definition Audio Controller                              | 21       | 3.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 21       | 3.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20       | 3.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20       | 3.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19       | 3.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19       | 3.05%   |
| Nvidia GP106 High Definition Audio Controller                              | 17       | 2.73%   |
| Intel 200 Series PCH HD Audio                                              | 16       | 2.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 16       | 2.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 11       | 1.77%   |
| AMD Navi 10 HDMI Audio                                                     | 11       | 1.77%   |
| Nvidia GA104 High Definition Audio Controller                              | 10       | 1.61%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 10       | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 1.61%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 10       | 1.61%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 9        | 1.44%   |
| AMD FCH Azalia Controller                                                  | 9        | 1.44%   |
| Nvidia GA102 High Definition Audio Controller                              | 8        | 1.28%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8        | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 1.12%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7        | 1.12%   |
| Nvidia TU104 HD Audio Controller                                           | 6        | 0.96%   |
| Nvidia GM204 High Definition Audio Controller                              | 6        | 0.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 0.96%   |
| Kingston Technology HyperX 7.1 Audio                                       | 6        | 0.96%   |
| Blue Microphones Yeti Stereo Microphone                                    | 6        | 0.96%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 5        | 0.8%    |
| Nvidia GK104 HDMI Audio Controller                                         | 5        | 0.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 0.8%    |
| Nvidia High Definition Audio Controller                                    | 4        | 0.64%   |
| Nvidia GP102 HDMI Audio Controller                                         | 4        | 0.64%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 0.64%   |
| Nvidia GK110 High Definition Audio Controller                              | 4        | 0.64%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 0.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 0.64%   |
| C-Media Electronics Blue Snowball                                          | 4        | 0.64%   |
| AMD Trinity HDMI Audio Controller                                          | 4        | 0.64%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 0.64%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 0.64%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 0.48%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 3        | 0.48%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.48%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.48%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.48%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 3        | 0.48%   |
| ASUSTek Computer USB Audio                                                 | 3        | 0.48%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 3        | 0.48%   |
| XMOS X1S USB DAC                                                           | 2        | 0.32%   |
| SteelSeries ApS Arctis 7 wireless adapter                                  | 2        | 0.32%   |
| Realtek Semiconductor Realtek Audio USB                                    | 2        | 0.32%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.32%   |
| Nvidia TU102 High Definition Audio Controller                              | 2        | 0.32%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 2        | 0.32%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.32%   |
| Nvidia GF114 HDMI Audio Controller                                         | 2        | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 39       | 24.22%  |
| Corsair             | 35       | 21.74%  |
| Crucial             | 22       | 13.66%  |
| Unknown             | 16       | 9.94%   |
| G.Skill             | 14       | 8.7%    |
| SK hynix            | 13       | 8.07%   |
| Samsung Electronics | 10       | 6.21%   |
| Ramaxel Technology  | 3        | 1.86%   |
| Micron Technology   | 3        | 1.86%   |
| Patriot             | 1        | 0.62%   |
| GeIL                | 1        | 0.62%   |
| Elpida              | 1        | 0.62%   |
| Apacer              | 1        | 0.62%   |
| A-DATA Technology   | 1        | 0.62%   |
| Unknown             | 1        | 0.62%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 5        | 2.94%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s    | 5        | 2.94%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s | 4        | 2.35%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 4        | 2.35%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s         | 3        | 1.76%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s     | 3        | 1.76%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s     | 3        | 1.76%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 2        | 1.18%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8192MB DIMM DDR3 2000MT/s   | 2        | 1.18%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s    | 2        | 1.18%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s      | 2        | 1.18%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 2        | 1.18%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 2        | 1.18%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s       | 2        | 1.18%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s       | 2        | 1.18%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s   | 2        | 1.18%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s    | 2        | 1.18%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s     | 2        | 1.18%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 2        | 1.18%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s  | 2        | 1.18%   |
| Corsair RAM CMK8GX4M1A2400C14 8GB DIMM DDR4 2800MT/s      | 2        | 1.18%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s    | 2        | 1.18%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 0.59%   |
| Unknown RAM Module 4GB DIMM DDR3 667MT/s                  | 1        | 0.59%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 1        | 0.59%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 1        | 0.59%   |
| Unknown RAM Module 4096MB DIMM                            | 1        | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1        | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR 1066MT/s                  | 1        | 0.59%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s             | 1        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 1        | 0.59%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                  | 1        | 0.59%   |
| Unknown RAM Module 1024MB DIMM 1600MT/s                   | 1        | 0.59%   |
| SK hynix RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 0.59%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.59%   |
| SK hynix RAM HYMP512U72CP8-Y5 1024MB DIMM DDR2 667MT/s    | 1        | 0.59%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR 667MT/s        | 1        | 0.59%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s      | 1        | 0.59%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 0.59%   |
| SK hynix RAM HMT42GR7BFR4A-PB 16GB DIMM DDR3 1600MT/s     | 1        | 0.59%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s      | 1        | 0.59%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8192MB DIMM DDR3 1600MT/s   | 1        | 0.59%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 0.59%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s   | 1        | 0.59%   |
| SK hynix RAM HMT325U7BFR8C-H9 2048MB DIMM DDR3 1333MT/s   | 1        | 0.59%   |
| Samsung RAM Module 8192MB DIMM DDR4 2400MT/s              | 1        | 0.59%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                | 1        | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 1        | 0.59%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s      | 1        | 0.59%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s      | 1        | 0.59%   |
| Samsung RAM M378B5673GB0-CH9 2GB DIMM 1333MT/s            | 1        | 0.59%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s    | 1        | 0.59%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s       | 1        | 0.59%   |
| Samsung RAM M378B1G73CB0-CK0 8192MB DIMM DDR3 1600MT/s    | 1        | 0.59%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s       | 1        | 0.59%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s   | 1        | 0.59%   |
| Ramaxel RAM RMR5040EB68FAW1600 8GB DIMM DDR3 1600MT/s     | 1        | 0.59%   |
| Ramaxel RAM RMR1781ME68F9F1600 4GB DIMM DDR3 1600MT/s     | 1        | 0.59%   |
| Patriot RAM 3000 C16 Series 8192MB DIMM DDR4 3200MT/s     | 1        | 0.59%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s      | 1        | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 77       | 54.23%  |
| DDR3    | 46       | 32.39%  |
| DDR2    | 10       | 7.04%   |
| Unknown | 5        | 3.52%   |
| SDRAM   | 3        | 2.11%   |
| DDR     | 1        | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 134      | 95.04%  |
| SODIMM | 7        | 4.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 61       | 40.67%  |
| 16384 | 36       | 24%     |
| 4096  | 31       | 20.67%  |
| 2048  | 12       | 8%      |
| 32768 | 5        | 3.33%   |
| 1024  | 4        | 2.67%   |
| 128   | 1        | 0.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 28       | 17.95%  |
| 3600    | 18       | 11.54%  |
| 1333    | 14       | 8.97%   |
| 3200    | 13       | 8.33%   |
| 2400    | 13       | 8.33%   |
| 667     | 10       | 6.41%   |
| 3400    | 7        | 4.49%   |
| 3466    | 6        | 3.85%   |
| 2133    | 6        | 3.85%   |
| 3000    | 4        | 2.56%   |
| 2933    | 4        | 2.56%   |
| 2800    | 3        | 1.92%   |
| 1800    | 3        | 1.92%   |
| 3866    | 2        | 1.28%   |
| 3733    | 2        | 1.28%   |
| 3333    | 2        | 1.28%   |
| 3151    | 2        | 1.28%   |
| 3100    | 2        | 1.28%   |
| 2000    | 2        | 1.28%   |
| 1867    | 2        | 1.28%   |
| 1066    | 2        | 1.28%   |
| 4800    | 1        | 0.64%   |
| 4000    | 1        | 0.64%   |
| 3533    | 1        | 0.64%   |
| 2733    | 1        | 0.64%   |
| 2667    | 1        | 0.64%   |
| 2666    | 1        | 0.64%   |
| 2187    | 1        | 0.64%   |
| 2048    | 1        | 0.64%   |
| 800     | 1        | 0.64%   |
| 100     | 1        | 0.64%   |
| Unknown | 1        | 0.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 40%     |
| Brother Industries  | 3        | 30%     |
| Samsung Electronics | 1        | 10%     |
| Pantum              | 1        | 10%     |
| Canon               | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung M2020 Series                 | 1        | 10%     |
| Pantum P2500W series                 | 1        | 10%     |
| HP LaserJet Professional P 1102w     | 1        | 10%     |
| HP ENVY Photo 6200 series            | 1        | 10%     |
| HP DeskJet F300 series               | 1        | 10%     |
| HP Deskjet 2540 series               | 1        | 10%     |
| Canon PIXMA MX530 Series             | 1        | 10%     |
| Brother QL-800 P-touch Label Printer | 1        | 10%     |
| Brother QL-550 printer               | 1        | 10%     |
| Brother DCP-8085DN                   | 1        | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 200 | 1        | 50%     |
| Canon CanoScan LiDE 110 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 32       | 51.61%  |
| Microsoft                     | 5        | 8.06%   |
| Creative Technology           | 5        | 8.06%   |
| Microdia                      | 4        | 6.45%   |
| Sunplus Innovation Technology | 2        | 3.23%   |
| MacroSilicon                  | 2        | 3.23%   |
| Cubeternet                    | 2        | 3.23%   |
| Chicony Electronics           | 2        | 3.23%   |
| Apple                         | 2        | 3.23%   |
| Z-Star Microelectronics       | 1        | 1.61%   |
| Technologies                  | 1        | 1.61%   |
| Samsung Electronics           | 1        | 1.61%   |
| Razer USA                     | 1        | 1.61%   |
| Novatek Microelectronics      | 1        | 1.61%   |
| Alcor Micro                   | 1        | 1.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                         | 6        | 9.52%   |
| Logitech C922 Pro Stream Webcam                                     | 6        | 9.52%   |
| Logitech Webcam C270                                                | 5        | 7.94%   |
| Creative Live! Cam Chat HD [VF0700]                                 | 4        | 6.35%   |
| Microsoft LifeCam Cinema                                            | 3        | 4.76%   |
| MacroSilicon USB3.0 HD VIDEO                                        | 2        | 3.17%   |
| Logitech Webcam C930e                                               | 2        | 3.17%   |
| Logitech Webcam C170                                                | 2        | 3.17%   |
| Logitech Logi 4K Stream Edition                                     | 2        | 3.17%   |
| Logitech HD Webcam C525                                             | 2        | 3.17%   |
| Logitech B525 HD Webcam                                             | 2        | 3.17%   |
| Apple iPhone 5/5C/5S/6/SE                                           | 2        | 3.17%   |
| Z-Star Lenovo ThinkCentre Web Camera                                | 1        | 1.59%   |
| Technologies ZED 2i                                                 | 1        | 1.59%   |
| Sunplus Sandberg USB Webcam Pro                                     | 1        | 1.59%   |
| Sunplus HD 720P webcam                                              | 1        | 1.59%   |
| Samsung Galaxy A5 (MTP)                                             | 1        | 1.59%   |
| Razer USA Gaming Webcam [Kiyo]                                      | 1        | 1.59%   |
| Novatek HP High Definition 2MP Webcam                               | 1        | 1.59%   |
| Microsoft LifeCam Studio                                            | 1        | 1.59%   |
| Microsoft LifeCam HD-3000                                           | 1        | 1.59%   |
| Microdia PC Microscope camera                                       | 1        | 1.59%   |
| Microdia HDP Webcam USB                                             | 1        | 1.59%   |
| Microdia Camera                                                     | 1        | 1.59%   |
| Microdia AUKEY PCâW1                                           | 1        | 1.59%   |
| Logitech Webcam C310                                                | 1        | 1.59%   |
| Logitech StreamCam                                                  | 1        | 1.59%   |
| Logitech QuickCam Pro 9000                                          | 1        | 1.59%   |
| Logitech QuickCam E 3500                                            | 1        | 1.59%   |
| Logitech C920 PRO HD Webcam                                         | 1        | 1.59%   |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 1.59%   |
| Cubeternet Live Streaming USB Device                                | 1        | 1.59%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 1.59%   |
| Creative Live! Cam Optia                                            | 1        | 1.59%   |
| Chicony USB2.0 FHD UVC WebCam                                       | 1        | 1.59%   |
| Chicony ASUS USB2.0 Webcam                                          | 1        | 1.59%   |
| Alcor Micro USB 2.0 PC Camera                                       | 1        | 1.59%   |

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


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| OmniKey    | 2        | 66.67%  |
| Yubico.com | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121 | 2        | 66.67%  |
| Yubico.com Yubikey 4/5 CCID | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 210      | 78.36%  |
| 1     | 47       | 17.54%  |
| 2     | 8        | 2.99%   |
| 3     | 3        | 1.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 25       | 36.76%  |
| Unassigned class         | 14       | 20.59%  |
| Graphics card            | 12       | 17.65%  |
| Sound                    | 4        | 5.88%   |
| Wireless                 | 3        | 4.41%   |
| Net/ethernet             | 2        | 2.94%   |
| Chipcard                 | 2        | 2.94%   |
| Bluetooth                | 2        | 2.94%   |
| Multimedia controller    | 1        | 1.47%   |
| Dvb card                 | 1        | 1.47%   |
| Communication controller | 1        | 1.47%   |
| Camera                   | 1        | 1.47%   |

