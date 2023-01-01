Kubuntu 20.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 20.04.

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

Total: 807

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Z170 PRO GAMING/AURA        | [87e8ae1350](https://linux-hardware.org/?probe=87e8ae1350) | Dec 29, 2022 |
| Pegatron      | 2AB6                        | [742c9ebcca](https://linux-hardware.org/?probe=742c9ebcca) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | [9e95c7e7c7](https://linux-hardware.org/?probe=9e95c7e7c7) | Dec 28, 2022 |
| Gigabyte      | Z590 UD AC                  | [895bd1b0b2](https://linux-hardware.org/?probe=895bd1b0b2) | Dec 13, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [3892b54ac4](https://linux-hardware.org/?probe=3892b54ac4) | Dec 08, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [eced972f80](https://linux-hardware.org/?probe=eced972f80) | Dec 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [d37c93af89](https://linux-hardware.org/?probe=d37c93af89) | Dec 05, 2022 |
| ASRock        | B75 Pro3-M                  | [db7e5686f3](https://linux-hardware.org/?probe=db7e5686f3) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1b361e2f17](https://linux-hardware.org/?probe=1b361e2f17) | Dec 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [9866b7f07f](https://linux-hardware.org/?probe=9866b7f07f) | Dec 01, 2022 |
| ASUSTek       | M4A88TD-M EVO               | [e4514feafe](https://linux-hardware.org/?probe=e4514feafe) | Nov 20, 2022 |
| ASUSTek       | TUF Z270 MARK 1             | [dc1aa01b01](https://linux-hardware.org/?probe=dc1aa01b01) | Nov 17, 2022 |
| Gigabyte      | Z77X-UP7                    | [e0edc946f9](https://linux-hardware.org/?probe=e0edc946f9) | Nov 13, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [518979e264](https://linux-hardware.org/?probe=518979e264) | Nov 11, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a9a0e77be4](https://linux-hardware.org/?probe=a9a0e77be4) | Nov 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [8b8ec08876](https://linux-hardware.org/?probe=8b8ec08876) | Nov 02, 2022 |
| ASUSTek       | P7P55D-E PRO                | [1e0daee604](https://linux-hardware.org/?probe=1e0daee604) | Oct 30, 2022 |
| Dell          | 0KRC95 A02                  | [8afc3da46d](https://linux-hardware.org/?probe=8afc3da46d) | Oct 28, 2022 |
| Gigabyte      | Z77X-UP7                    | [c33d6de923](https://linux-hardware.org/?probe=c33d6de923) | Oct 27, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [65c39a9702](https://linux-hardware.org/?probe=65c39a9702) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [f42213926f](https://linux-hardware.org/?probe=f42213926f) | Oct 24, 2022 |
| Dell          | 0RW199                      | [dc99b64e62](https://linux-hardware.org/?probe=dc99b64e62) | Oct 24, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [ddc08ffe48](https://linux-hardware.org/?probe=ddc08ffe48) | Oct 22, 2022 |
| Medion        | H110H4-EM2                  | [7bd38709d3](https://linux-hardware.org/?probe=7bd38709d3) | Oct 09, 2022 |
| ASRock        | A75M                        | [b3df324d02](https://linux-hardware.org/?probe=b3df324d02) | Oct 08, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [8a89e7f4da](https://linux-hardware.org/?probe=8a89e7f4da) | Oct 06, 2022 |
| Dell          | 0C27VV A00                  | [0866f99d43](https://linux-hardware.org/?probe=0866f99d43) | Oct 06, 2022 |
| ASUSTek       | M4A88TD-M EVO               | [6e0ea7e989](https://linux-hardware.org/?probe=6e0ea7e989) | Oct 03, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [7221bbf8e7](https://linux-hardware.org/?probe=7221bbf8e7) | Oct 01, 2022 |
| Gigabyte      | P35C-DS3R                   | [eb49db3a8c](https://linux-hardware.org/?probe=eb49db3a8c) | Sep 14, 2022 |
| Gigabyte      | Z77X-UP7                    | [1634db2e78](https://linux-hardware.org/?probe=1634db2e78) | Sep 11, 2022 |
| ASUSTek       | H81M-P PLUS                 | [1ede09cb8a](https://linux-hardware.org/?probe=1ede09cb8a) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0789b27bdb](https://linux-hardware.org/?probe=0789b27bdb) | Sep 02, 2022 |
| Gigabyte      | H81M-DS2                    | [373a11a297](https://linux-hardware.org/?probe=373a11a297) | Aug 29, 2022 |
| Gigabyte      | GA-MA770T-UD3               | [f6c6b627f7](https://linux-hardware.org/?probe=f6c6b627f7) | Aug 28, 2022 |
| MSI           | A320M PRO-VD/S              | [676e223d96](https://linux-hardware.org/?probe=676e223d96) | Aug 25, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [b12d6e7967](https://linux-hardware.org/?probe=b12d6e7967) | Aug 20, 2022 |
| Gigabyte      | H61M-S1                     | [18f3dd56e8](https://linux-hardware.org/?probe=18f3dd56e8) | Aug 11, 2022 |
| ASUSTek       | PRIME X570-P                | [ca185c2301](https://linux-hardware.org/?probe=ca185c2301) | Aug 10, 2022 |
| Gigabyte      | 970A-DS3P                   | [23905636a4](https://linux-hardware.org/?probe=23905636a4) | Aug 06, 2022 |
| ASUSTek       | PRIME X570-P                | [49390f2f0e](https://linux-hardware.org/?probe=49390f2f0e) | Aug 06, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | [83e4b444ae](https://linux-hardware.org/?probe=83e4b444ae) | Aug 01, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | [4e335cb7ce](https://linux-hardware.org/?probe=4e335cb7ce) | Aug 01, 2022 |
| Dell          | 0F8098                      | [4e6058685a](https://linux-hardware.org/?probe=4e6058685a) | Jul 30, 2022 |
| HP            | 158A                        | [788844c3df](https://linux-hardware.org/?probe=788844c3df) | Jul 29, 2022 |
| ASUSTek       | Z87M-PLUS                   | [1b47c32e5d](https://linux-hardware.org/?probe=1b47c32e5d) | Jul 29, 2022 |
| Gigabyte      | Z77-D3H                     | [2d3706b78b](https://linux-hardware.org/?probe=2d3706b78b) | Jul 28, 2022 |
| HP            | 86E9 A                      | [6634eaee32](https://linux-hardware.org/?probe=6634eaee32) | Jul 27, 2022 |
| Gigabyte      | 970A-DS3P                   | [379da1a196](https://linux-hardware.org/?probe=379da1a196) | Jul 21, 2022 |
| HP            | 8054                        | [466d7f5591](https://linux-hardware.org/?probe=466d7f5591) | Jul 21, 2022 |
| HP            | 1790                        | [ff91b0d921](https://linux-hardware.org/?probe=ff91b0d921) | Jul 15, 2022 |
| ASRock        | J4105M                      | [509b122b9b](https://linux-hardware.org/?probe=509b122b9b) | Jul 12, 2022 |
| Dell          | 06NWYK A01                  | [91408af847](https://linux-hardware.org/?probe=91408af847) | Jul 01, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [530c44caa8](https://linux-hardware.org/?probe=530c44caa8) | Jun 30, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [86a93d8ea0](https://linux-hardware.org/?probe=86a93d8ea0) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [554ba1726f](https://linux-hardware.org/?probe=554ba1726f) | Jun 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3dffa312da](https://linux-hardware.org/?probe=3dffa312da) | Jun 24, 2022 |
| Apple         | Mac-F221BEC8                | [ba64ef130a](https://linux-hardware.org/?probe=ba64ef130a) | Jun 23, 2022 |
| HP            | 0A98h                       | [d3c54ab2d6](https://linux-hardware.org/?probe=d3c54ab2d6) | Jun 10, 2022 |
| ASRock        | 960GM-VGS3 FX               | [82aa782cce](https://linux-hardware.org/?probe=82aa782cce) | Jun 08, 2022 |
| ASRock        | X470 Master SLI             | [eb62d09265](https://linux-hardware.org/?probe=eb62d09265) | Jun 05, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [b450673fc0](https://linux-hardware.org/?probe=b450673fc0) | May 31, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [326c7a11e6](https://linux-hardware.org/?probe=326c7a11e6) | May 28, 2022 |
| ASUSTek       | PRIME B460M-K               | [765d22e752](https://linux-hardware.org/?probe=765d22e752) | May 23, 2022 |
| ASUSTek       | P7P55D-E PRO                | [dfa1010543](https://linux-hardware.org/?probe=dfa1010543) | May 21, 2022 |
| MSI           | 2AE0                        | [d99294cadc](https://linux-hardware.org/?probe=d99294cadc) | May 21, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [b098eb44db](https://linux-hardware.org/?probe=b098eb44db) | May 18, 2022 |
| Gigabyte      | 990FXA-UD3                  | [4bc8f93383](https://linux-hardware.org/?probe=4bc8f93383) | May 17, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [78fe695a2f](https://linux-hardware.org/?probe=78fe695a2f) | May 16, 2022 |
| Gigabyte      | 990FXA-UD3                  | [89b16a89c5](https://linux-hardware.org/?probe=89b16a89c5) | May 16, 2022 |
| Foxconn       | 2ADA                        | [cd20eb0809](https://linux-hardware.org/?probe=cd20eb0809) | May 14, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [dc9b228486](https://linux-hardware.org/?probe=dc9b228486) | May 08, 2022 |
| ASUSTek       | EB1501P                     | [f1d427d32b](https://linux-hardware.org/?probe=f1d427d32b) | May 06, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [71c0c4f257](https://linux-hardware.org/?probe=71c0c4f257) | May 05, 2022 |
| ASUSTek       | P7P55 LX                    | [82c13f2b01](https://linux-hardware.org/?probe=82c13f2b01) | Apr 25, 2022 |
| ASRock        | Z87 Pro4                    | [0c4cc8712f](https://linux-hardware.org/?probe=0c4cc8712f) | Apr 22, 2022 |
| MSI           | A320M-A PRO MAX             | [b925b403ca](https://linux-hardware.org/?probe=b925b403ca) | Apr 20, 2022 |
| Dell          | 0HY9JP A00                  | [a767ef8b4e](https://linux-hardware.org/?probe=a767ef8b4e) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | [5ce6ef2934](https://linux-hardware.org/?probe=5ce6ef2934) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | [fed643b7ec](https://linux-hardware.org/?probe=fed643b7ec) | Apr 16, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [78a785e4a9](https://linux-hardware.org/?probe=78a785e4a9) | Apr 15, 2022 |
| Pegatron      | 2AD5                        | [e172be90b8](https://linux-hardware.org/?probe=e172be90b8) | Apr 14, 2022 |
| MSI           | Z270 SLI PLUS               | [fa00f6ccd6](https://linux-hardware.org/?probe=fa00f6ccd6) | Apr 13, 2022 |
| ASRock        | H97 Pro4                    | [db6bf8f1b9](https://linux-hardware.org/?probe=db6bf8f1b9) | Apr 13, 2022 |
| ASRock        | H110M-ITX                   | [13dff6f000](https://linux-hardware.org/?probe=13dff6f000) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [272c9f107a](https://linux-hardware.org/?probe=272c9f107a) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [f98a0cf73b](https://linux-hardware.org/?probe=f98a0cf73b) | Apr 05, 2022 |
| HP            | 805D                        | [709488e1da](https://linux-hardware.org/?probe=709488e1da) | Mar 31, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [5dae1dd2a5](https://linux-hardware.org/?probe=5dae1dd2a5) | Mar 28, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [dc2a2c1054](https://linux-hardware.org/?probe=dc2a2c1054) | Mar 25, 2022 |
| Gigabyte      | B75M-HD3                    | [b886cf0849](https://linux-hardware.org/?probe=b886cf0849) | Mar 23, 2022 |
| Dell          | 0NK70N A03                  | [e5fe628a7b](https://linux-hardware.org/?probe=e5fe628a7b) | Mar 23, 2022 |
| HP            | 1589                        | [998f465bfc](https://linux-hardware.org/?probe=998f465bfc) | Mar 19, 2022 |
| Dell          | 0RY206                      | [df958219ab](https://linux-hardware.org/?probe=df958219ab) | Mar 18, 2022 |
| Dell          | 0RY206                      | [d46b854bd5](https://linux-hardware.org/?probe=d46b854bd5) | Mar 18, 2022 |
| ASRock        | 990FX Killer                | [acdee8aa65](https://linux-hardware.org/?probe=acdee8aa65) | Mar 15, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | [c8809e0561](https://linux-hardware.org/?probe=c8809e0561) | Mar 15, 2022 |
| ASRock        | B360 Gaming K4              | [ae6cb3bea9](https://linux-hardware.org/?probe=ae6cb3bea9) | Mar 11, 2022 |
| HP            | 82F1                        | [390462d20a](https://linux-hardware.org/?probe=390462d20a) | Mar 10, 2022 |
| HP            | 82F1                        | [63273af14a](https://linux-hardware.org/?probe=63273af14a) | Mar 10, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [2032fbba77](https://linux-hardware.org/?probe=2032fbba77) | Mar 09, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [456b0dd391](https://linux-hardware.org/?probe=456b0dd391) | Mar 06, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [19c66b47da](https://linux-hardware.org/?probe=19c66b47da) | Mar 06, 2022 |
| HP            | 8266                        | [e0991ef205](https://linux-hardware.org/?probe=e0991ef205) | Mar 06, 2022 |
| MSI           | H81M-E34                    | [563e906e47](https://linux-hardware.org/?probe=563e906e47) | Mar 01, 2022 |
| Dell          | 042P49 A01                  | [25c0e14020](https://linux-hardware.org/?probe=25c0e14020) | Feb 28, 2022 |
| MSI           | B350 PC MATE                | [2e06b2fed8](https://linux-hardware.org/?probe=2e06b2fed8) | Feb 27, 2022 |
| ASUSTek       | B85-PRO GAMER               | [3f97cefeb4](https://linux-hardware.org/?probe=3f97cefeb4) | Feb 26, 2022 |
| Biostar       | B450MH                      | [40f413ddcb](https://linux-hardware.org/?probe=40f413ddcb) | Feb 26, 2022 |
| ASUSTek       | B85M-G                      | [8e648c583a](https://linux-hardware.org/?probe=8e648c583a) | Feb 25, 2022 |
| Unknown       | TB-4000                     | [70155eb876](https://linux-hardware.org/?probe=70155eb876) | Feb 24, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | [9d9c4fe241](https://linux-hardware.org/?probe=9d9c4fe241) | Feb 23, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | [84b8eefa6d](https://linux-hardware.org/?probe=84b8eefa6d) | Feb 23, 2022 |
| Supermicro    | X10DAI                      | [4de85d4700](https://linux-hardware.org/?probe=4de85d4700) | Feb 23, 2022 |
| MSI           | Z170-A PRO                  | [9628754bf4](https://linux-hardware.org/?probe=9628754bf4) | Feb 17, 2022 |
| Dell          | 0J8G6F A03                  | [c4314fa1c4](https://linux-hardware.org/?probe=c4314fa1c4) | Feb 17, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [9773bc9c72](https://linux-hardware.org/?probe=9773bc9c72) | Feb 16, 2022 |
| Gateway       | IPISB-VR                    | [af56b8d361](https://linux-hardware.org/?probe=af56b8d361) | Feb 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | [4e3b8bfbb1](https://linux-hardware.org/?probe=4e3b8bfbb1) | Feb 16, 2022 |
| MSI           | MEG X570 GODLIKE            | [b4db24332b](https://linux-hardware.org/?probe=b4db24332b) | Feb 14, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a98c8db3ad](https://linux-hardware.org/?probe=a98c8db3ad) | Feb 12, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [ed39168e58](https://linux-hardware.org/?probe=ed39168e58) | Feb 12, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [2885a7e3ed](https://linux-hardware.org/?probe=2885a7e3ed) | Feb 11, 2022 |
| MSI           | MAG B550M MORTAR            | [5e071a1807](https://linux-hardware.org/?probe=5e071a1807) | Feb 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [3e8a21888f](https://linux-hardware.org/?probe=3e8a21888f) | Feb 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [df711c6514](https://linux-hardware.org/?probe=df711c6514) | Feb 03, 2022 |
| Gigabyte      | H81M-H                      | [4c55c42084](https://linux-hardware.org/?probe=4c55c42084) | Feb 03, 2022 |
| MSI           | B450M MORTAR                | [a2fbd7d84e](https://linux-hardware.org/?probe=a2fbd7d84e) | Feb 03, 2022 |
| ASUSTek       | Q87M-E                      | [99abdcb1fe](https://linux-hardware.org/?probe=99abdcb1fe) | Feb 02, 2022 |
| Gigabyte      | F2A88XM-D3HP                | [0404256996](https://linux-hardware.org/?probe=0404256996) | Feb 01, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [e8b6865345](https://linux-hardware.org/?probe=e8b6865345) | Jan 31, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [1c6777fb1a](https://linux-hardware.org/?probe=1c6777fb1a) | Jan 31, 2022 |
| ASUSTek       | P7P55D-E PRO                | [7daa77d5ba](https://linux-hardware.org/?probe=7daa77d5ba) | Jan 27, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [a23be61a14](https://linux-hardware.org/?probe=a23be61a14) | Jan 26, 2022 |
| ASUSTek       | EB1501P                     | [bd43e4b748](https://linux-hardware.org/?probe=bd43e4b748) | Jan 22, 2022 |
| ASUSTek       | EB1501P                     | [fec419577b](https://linux-hardware.org/?probe=fec419577b) | Jan 22, 2022 |
| Dell          | 0PC5F7 A03                  | [bc00e00b3d](https://linux-hardware.org/?probe=bc00e00b3d) | Jan 15, 2022 |
| MSI           | B85I                        | [dc1862e477](https://linux-hardware.org/?probe=dc1862e477) | Jan 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [20cc8ef2ea](https://linux-hardware.org/?probe=20cc8ef2ea) | Jan 11, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [a7be44496a](https://linux-hardware.org/?probe=a7be44496a) | Jan 11, 2022 |
| Gigabyte      | A320M-H-CF                  | [c09f135f63](https://linux-hardware.org/?probe=c09f135f63) | Jan 09, 2022 |
| Dell          | 0DR845                      | [daa833f06d](https://linux-hardware.org/?probe=daa833f06d) | Jan 08, 2022 |
| ASUSTek       | H61M-A/BR                   | [82aa762a97](https://linux-hardware.org/?probe=82aa762a97) | Jan 08, 2022 |
| ASUSTek       | PRIME B560M-K               | [b44e84f8a6](https://linux-hardware.org/?probe=b44e84f8a6) | Jan 06, 2022 |
| ASRock        | B75 Pro3-M                  | [2daf055722](https://linux-hardware.org/?probe=2daf055722) | Jan 05, 2022 |
| ASRock        | Z77 Pro4-M                  | [c3ddad9a30](https://linux-hardware.org/?probe=c3ddad9a30) | Jan 03, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [6324598512](https://linux-hardware.org/?probe=6324598512) | Dec 30, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [38dda4af6b](https://linux-hardware.org/?probe=38dda4af6b) | Dec 30, 2021 |
| Gigabyte      | B550 VISION D-P             | [6f2dc843e9](https://linux-hardware.org/?probe=6f2dc843e9) | Dec 27, 2021 |
| ASRock        | Z87 Pro4                    | [8459ac43a8](https://linux-hardware.org/?probe=8459ac43a8) | Dec 27, 2021 |
| Acer          | Aspire T3-605               | [7acbb546e6](https://linux-hardware.org/?probe=7acbb546e6) | Dec 26, 2021 |
| Lenovo        | SHARKBAY NOK                | [2a7c56982c](https://linux-hardware.org/?probe=2a7c56982c) | Dec 26, 2021 |
| MSI           | B450 TOMAHAWK               | [dc6fd4bfc7](https://linux-hardware.org/?probe=dc6fd4bfc7) | Dec 25, 2021 |
| Gigabyte      | A320M-S2H-CF                | [6c56118d24](https://linux-hardware.org/?probe=6c56118d24) | Dec 25, 2021 |
| Gigabyte      | B550 VISION D-P             | [8fdab6dc11](https://linux-hardware.org/?probe=8fdab6dc11) | Dec 23, 2021 |
| ASUSTek       | Z97-A                       | [1d27772094](https://linux-hardware.org/?probe=1d27772094) | Dec 21, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [992c6c4350](https://linux-hardware.org/?probe=992c6c4350) | Dec 21, 2021 |
| Gigabyte      | GA-870A-UD3                 | [c4b9060346](https://linux-hardware.org/?probe=c4b9060346) | Dec 18, 2021 |
| Lenovo        | Unknown                     | [64951d70ab](https://linux-hardware.org/?probe=64951d70ab) | Dec 16, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [463119e0f9](https://linux-hardware.org/?probe=463119e0f9) | Dec 09, 2021 |
| HP            | 8750                        | [b6c8c71af0](https://linux-hardware.org/?probe=b6c8c71af0) | Dec 07, 2021 |
| HP            | 8750                        | [5c912921e0](https://linux-hardware.org/?probe=5c912921e0) | Dec 07, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [fc34582970](https://linux-hardware.org/?probe=fc34582970) | Nov 29, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [5e81a55ce3](https://linux-hardware.org/?probe=5e81a55ce3) | Nov 28, 2021 |
| Dell          | 0N4YC8 A00                  | [6960aecc48](https://linux-hardware.org/?probe=6960aecc48) | Nov 28, 2021 |
| ASRock        | H61M-VS                     | [4aefcd6dd3](https://linux-hardware.org/?probe=4aefcd6dd3) | Nov 27, 2021 |
| MSI           | B460M PRO-VDH               | [4c7d18cb37](https://linux-hardware.org/?probe=4c7d18cb37) | Nov 26, 2021 |
| HP            | 212B                        | [0377d5dc76](https://linux-hardware.org/?probe=0377d5dc76) | Nov 23, 2021 |
| HP            | 304Ah                       | [ff34cb9fb8](https://linux-hardware.org/?probe=ff34cb9fb8) | Nov 20, 2021 |
| ASUSTek       | PRIME B560M-K               | [571e7e5de4](https://linux-hardware.org/?probe=571e7e5de4) | Nov 19, 2021 |
| HP            | 8599                        | [4103117abb](https://linux-hardware.org/?probe=4103117abb) | Nov 18, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [941a3ff2ca](https://linux-hardware.org/?probe=941a3ff2ca) | Nov 15, 2021 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | [a9a66b59f1](https://linux-hardware.org/?probe=a9a66b59f1) | Nov 09, 2021 |
| Gigabyte      | B365M DS3H                  | [8e3176012c](https://linux-hardware.org/?probe=8e3176012c) | Nov 05, 2021 |
| Biostar       | A68MD PRO                   | [19a6612e0a](https://linux-hardware.org/?probe=19a6612e0a) | Nov 03, 2021 |
| Biostar       | A68MD PRO                   | [417cbcba6a](https://linux-hardware.org/?probe=417cbcba6a) | Nov 02, 2021 |
| HP            | 212B                        | [9d2a807f08](https://linux-hardware.org/?probe=9d2a807f08) | Oct 29, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [03af7df5b2](https://linux-hardware.org/?probe=03af7df5b2) | Oct 28, 2021 |
| Lenovo        | ThinkCentre M71e 3157RV2    | [6d4dc3e8af](https://linux-hardware.org/?probe=6d4dc3e8af) | Oct 26, 2021 |
| ASUSTek       | PRIME B350M-A               | [f20f2bfc32](https://linux-hardware.org/?probe=f20f2bfc32) | Oct 26, 2021 |
| Gigabyte      | A320M-S2H-CF                | [633fc31d82](https://linux-hardware.org/?probe=633fc31d82) | Oct 26, 2021 |
| HP            | 212B                        | [b72e4a7240](https://linux-hardware.org/?probe=b72e4a7240) | Oct 26, 2021 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | [afbb381cf3](https://linux-hardware.org/?probe=afbb381cf3) | Oct 25, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [3134454d4f](https://linux-hardware.org/?probe=3134454d4f) | Oct 24, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [eb97afcaa6](https://linux-hardware.org/?probe=eb97afcaa6) | Oct 24, 2021 |
| Intel         | D54250WYK H13922-303        | [21b715e26a](https://linux-hardware.org/?probe=21b715e26a) | Oct 17, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [8b87eef23f](https://linux-hardware.org/?probe=8b87eef23f) | Oct 16, 2021 |
| ASRock        | Z370 Pro4                   | [4603126532](https://linux-hardware.org/?probe=4603126532) | Oct 15, 2021 |
| ASUSTek       | PRIME B450M-A               | [0b5ca0df4e](https://linux-hardware.org/?probe=0b5ca0df4e) | Oct 14, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [a0c897a604](https://linux-hardware.org/?probe=a0c897a604) | Oct 13, 2021 |
| Gigabyte      | 970A-DS3P                   | [9dc8d76ce0](https://linux-hardware.org/?probe=9dc8d76ce0) | Oct 12, 2021 |
| ASUSTek       | PRIME B450M-A               | [138c57899f](https://linux-hardware.org/?probe=138c57899f) | Oct 11, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [bc7f078524](https://linux-hardware.org/?probe=bc7f078524) | Oct 07, 2021 |
| ASUSTek       | PRIME X570-P                | [07b92ffa9f](https://linux-hardware.org/?probe=07b92ffa9f) | Oct 06, 2021 |
| ASUSTek       | PRIME X570-P                | [90c1b2e414](https://linux-hardware.org/?probe=90c1b2e414) | Oct 06, 2021 |
| Intel         | DH67CL AAG10212-206         | [459d0f2e53](https://linux-hardware.org/?probe=459d0f2e53) | Oct 04, 2021 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | [a667195cd1](https://linux-hardware.org/?probe=a667195cd1) | Oct 03, 2021 |
| Gigabyte      | 970A-DS3P                   | [cdb8dd9b53](https://linux-hardware.org/?probe=cdb8dd9b53) | Oct 03, 2021 |
| ASRock        | B550M Steel Legend          | [6b9d5f5444](https://linux-hardware.org/?probe=6b9d5f5444) | Oct 02, 2021 |
| ASUSTek       | SABERTOOTH P67              | [8366a7edd1](https://linux-hardware.org/?probe=8366a7edd1) | Sep 29, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | [c91a5b0d8d](https://linux-hardware.org/?probe=c91a5b0d8d) | Sep 25, 2021 |
| Intel         | Eaglelake Fab D             | [acd05f91f6](https://linux-hardware.org/?probe=acd05f91f6) | Sep 21, 2021 |
| Gigabyte      | H310M S2H x.x               | [d8df9a881c](https://linux-hardware.org/?probe=d8df9a881c) | Sep 20, 2021 |
| Acer          | Aspire XC-830               | [c2479661bc](https://linux-hardware.org/?probe=c2479661bc) | Sep 18, 2021 |
| ASUSTek       | P8P67                       | [8c1582c3ed](https://linux-hardware.org/?probe=8c1582c3ed) | Sep 18, 2021 |
| Gigabyte      | X99-UD3-CF                  | [c70024afd4](https://linux-hardware.org/?probe=c70024afd4) | Sep 16, 2021 |
| Dell          | 0J8H4R A00                  | [d482d475f7](https://linux-hardware.org/?probe=d482d475f7) | Sep 15, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [15fa98aa93](https://linux-hardware.org/?probe=15fa98aa93) | Sep 14, 2021 |
| HP            | 0AECh D                     | [42d762e479](https://linux-hardware.org/?probe=42d762e479) | Sep 12, 2021 |
| Gigabyte      | H110M-S2PV-CF               | [fb3c4b683c](https://linux-hardware.org/?probe=fb3c4b683c) | Sep 08, 2021 |
| HP            | 0AECh D                     | [be336df1da](https://linux-hardware.org/?probe=be336df1da) | Sep 08, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [014c8bb745](https://linux-hardware.org/?probe=014c8bb745) | Sep 07, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [922e1625b6](https://linux-hardware.org/?probe=922e1625b6) | Sep 07, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [07db84c018](https://linux-hardware.org/?probe=07db84c018) | Sep 07, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | [10f34cd263](https://linux-hardware.org/?probe=10f34cd263) | Sep 05, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [d532b9c69c](https://linux-hardware.org/?probe=d532b9c69c) | Aug 30, 2021 |
| Dell          | 0D28YY A01                  | [c56901e13e](https://linux-hardware.org/?probe=c56901e13e) | Aug 30, 2021 |
| Gigabyte      | F2A55M-HD2                  | [d2ce2247c6](https://linux-hardware.org/?probe=d2ce2247c6) | Aug 30, 2021 |
| MSI           | 970A SLI Krait Edition      | [7b8f7d0fb9](https://linux-hardware.org/?probe=7b8f7d0fb9) | Aug 29, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [a113806a4a](https://linux-hardware.org/?probe=a113806a4a) | Aug 29, 2021 |
| Gigabyte      | B75M-D3V                    | [7f53bb7787](https://linux-hardware.org/?probe=7f53bb7787) | Aug 28, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [5374669067](https://linux-hardware.org/?probe=5374669067) | Aug 26, 2021 |
| ASUSTek       | H61-PLUS                    | [806118d8b3](https://linux-hardware.org/?probe=806118d8b3) | Aug 22, 2021 |
| Dell          | 0D28YY A01                  | [6f08d0dd20](https://linux-hardware.org/?probe=6f08d0dd20) | Aug 20, 2021 |
| ASUSTek       | Z170-WS                     | [ac73f29c0f](https://linux-hardware.org/?probe=ac73f29c0f) | Aug 18, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [56d35bbff9](https://linux-hardware.org/?probe=56d35bbff9) | Aug 16, 2021 |
| Dell          | 0D28YY A01                  | [599f91ad85](https://linux-hardware.org/?probe=599f91ad85) | Aug 14, 2021 |
| HP            | 8653 A                      | [7ba975c504](https://linux-hardware.org/?probe=7ba975c504) | Aug 13, 2021 |
| SYWZ          | S210H Series                | [72d2c9aafc](https://linux-hardware.org/?probe=72d2c9aafc) | Aug 13, 2021 |
| ASUSTek       | M4A87TD                     | [c5c19a5f46](https://linux-hardware.org/?probe=c5c19a5f46) | Aug 11, 2021 |
| MSI           | B450M GAMING PLUS           | [18ff34f941](https://linux-hardware.org/?probe=18ff34f941) | Aug 10, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [e3508d3cd3](https://linux-hardware.org/?probe=e3508d3cd3) | Aug 10, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [bd0ee7aa7f](https://linux-hardware.org/?probe=bd0ee7aa7f) | Aug 08, 2021 |
| Gigabyte      | H310M M.2                   | [9218549ef6](https://linux-hardware.org/?probe=9218549ef6) | Aug 06, 2021 |
| Gigabyte      | H310M M.2                   | [1f289dd5ed](https://linux-hardware.org/?probe=1f289dd5ed) | Aug 06, 2021 |
| MSI           | B85M-E45                    | [85f98480a8](https://linux-hardware.org/?probe=85f98480a8) | Aug 05, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2a9fe5f63c](https://linux-hardware.org/?probe=2a9fe5f63c) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1c5dccfd22](https://linux-hardware.org/?probe=1c5dccfd22) | Jul 31, 2021 |
| ASUSTek       | P5G41T-M LX3                | [7c3d5f062e](https://linux-hardware.org/?probe=7c3d5f062e) | Jul 30, 2021 |
| ASRock        | FM2A88X Extreme6+           | [30e4889c5a](https://linux-hardware.org/?probe=30e4889c5a) | Jul 30, 2021 |
| Intel         | DP55WB AAE64798-206         | [7c880b70f2](https://linux-hardware.org/?probe=7c880b70f2) | Jul 27, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [6df63b2eac](https://linux-hardware.org/?probe=6df63b2eac) | Jul 27, 2021 |
| MSI           | B85M-E45                    | [d06bc5e141](https://linux-hardware.org/?probe=d06bc5e141) | Jul 26, 2021 |
| ASUSTek       | M3A78-EM                    | [021f8f6a56](https://linux-hardware.org/?probe=021f8f6a56) | Jul 25, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [4ae6eba2f6](https://linux-hardware.org/?probe=4ae6eba2f6) | Jul 25, 2021 |
| Gigabyte      | AX370-Gaming K5-CF          | [abb23e508c](https://linux-hardware.org/?probe=abb23e508c) | Jul 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | [6c1a9d102e](https://linux-hardware.org/?probe=6c1a9d102e) | Jul 23, 2021 |
| Foxconn       | ELA01                       | [13bcd06d5f](https://linux-hardware.org/?probe=13bcd06d5f) | Jul 23, 2021 |
| Foxconn       | ELA01                       | [a73982649a](https://linux-hardware.org/?probe=a73982649a) | Jul 22, 2021 |
| ASUSTek       | P6T DELUXE V2               | [09f145783b](https://linux-hardware.org/?probe=09f145783b) | Jul 22, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [696645fa69](https://linux-hardware.org/?probe=696645fa69) | Jul 17, 2021 |
| Dell          | 0YXT71 A02                  | [1c944ecf6b](https://linux-hardware.org/?probe=1c944ecf6b) | Jul 16, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [380f5c41bf](https://linux-hardware.org/?probe=380f5c41bf) | Jul 12, 2021 |
| Dell          | 0KWVT8 A02                  | [b0ed7c660f](https://linux-hardware.org/?probe=b0ed7c660f) | Jul 12, 2021 |
| Gigabyte      | GA-790XT-USB3               | [72f5d673d9](https://linux-hardware.org/?probe=72f5d673d9) | Jul 11, 2021 |
| ASRock        | 760GM-HDV                   | [f58961af45](https://linux-hardware.org/?probe=f58961af45) | Jul 11, 2021 |
| Lenovo        | SDK0E50510 WIN              | [d37ee6f754](https://linux-hardware.org/?probe=d37ee6f754) | Jul 04, 2021 |
| Lenovo        | SDK0E50510 WIN              | [2d6120fa61](https://linux-hardware.org/?probe=2d6120fa61) | Jul 04, 2021 |
| ASRock        | A320M-DGS                   | [1039b9c2f5](https://linux-hardware.org/?probe=1039b9c2f5) | Jul 04, 2021 |
| MSI           | MPG B460I GAMING EDGE WI... | [1567387500](https://linux-hardware.org/?probe=1567387500) | Jul 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [c198cbd693](https://linux-hardware.org/?probe=c198cbd693) | Jul 02, 2021 |
| Biostar       | TA790GXB A2+                | [9fb8b9219e](https://linux-hardware.org/?probe=9fb8b9219e) | Jun 30, 2021 |
| ASRock        | N68-S3 UCC                  | [da689c7012](https://linux-hardware.org/?probe=da689c7012) | Jun 26, 2021 |
| MSI           | MAG B550M MORTAR            | [dfa95a4efd](https://linux-hardware.org/?probe=dfa95a4efd) | Jun 26, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a26c01da62](https://linux-hardware.org/?probe=a26c01da62) | Jun 26, 2021 |
| ASUSTek       | PRIME X470-PRO              | [fca4787959](https://linux-hardware.org/?probe=fca4787959) | Jun 22, 2021 |
| Intel         | X99                         | [436dda258b](https://linux-hardware.org/?probe=436dda258b) | Jun 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | [98be9faa06](https://linux-hardware.org/?probe=98be9faa06) | Jun 21, 2021 |
| Dell          | 0D28YY A01                  | [5cdcacb2f2](https://linux-hardware.org/?probe=5cdcacb2f2) | Jun 20, 2021 |
| ASRock        | AB350 Pro4                  | [6c9f9a3c6f](https://linux-hardware.org/?probe=6c9f9a3c6f) | Jun 20, 2021 |
| ASRock        | X300M-STX                   | [270961254a](https://linux-hardware.org/?probe=270961254a) | Jun 20, 2021 |
| ASRock        | X300M-STX                   | [441c0bb81f](https://linux-hardware.org/?probe=441c0bb81f) | Jun 19, 2021 |
| ASUSTek       | H87-PRO                     | [acd35c74b5](https://linux-hardware.org/?probe=acd35c74b5) | Jun 17, 2021 |
| Intel         | H55                         | [c6c7036ebd](https://linux-hardware.org/?probe=c6c7036ebd) | Jun 16, 2021 |
| Gigabyte      | F2A78M-DS2                  | [85c3988842](https://linux-hardware.org/?probe=85c3988842) | Jun 15, 2021 |
| HP            | 198E                        | [4d38d777c3](https://linux-hardware.org/?probe=4d38d777c3) | Jun 13, 2021 |
| ASUSTek       | P5Q PRO TURBO               | [d99f5ee668](https://linux-hardware.org/?probe=d99f5ee668) | Jun 12, 2021 |
| ASUSTek       | P5Q PRO TURBO               | [cfa0cf242c](https://linux-hardware.org/?probe=cfa0cf242c) | Jun 11, 2021 |
| ASRock        | Z170 Extreme7+              | [442ebaf444](https://linux-hardware.org/?probe=442ebaf444) | Jun 10, 2021 |
| HP            | 198E                        | [683e970f55](https://linux-hardware.org/?probe=683e970f55) | Jun 10, 2021 |
| Lenovo        | Tilapia CRB                 | [1b9acc3bdf](https://linux-hardware.org/?probe=1b9acc3bdf) | Jun 08, 2021 |
| Gigabyte      | H81M-H                      | [cfc0aceaf9](https://linux-hardware.org/?probe=cfc0aceaf9) | Jun 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [5e73374bbc](https://linux-hardware.org/?probe=5e73374bbc) | Jun 06, 2021 |
| ASRock        | Z390 Taichi Ultimate        | [fa126d0d5f](https://linux-hardware.org/?probe=fa126d0d5f) | Jun 05, 2021 |
| MSI           | 970 GAMING                  | [dcae361982](https://linux-hardware.org/?probe=dcae361982) | Jun 05, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a580ef9f5c](https://linux-hardware.org/?probe=a580ef9f5c) | Jun 04, 2021 |
| HP            | 304Bh                       | [4f331fec6f](https://linux-hardware.org/?probe=4f331fec6f) | Jun 04, 2021 |
| MSI           | 970 GAMING                  | [fe8cc5a05e](https://linux-hardware.org/?probe=fe8cc5a05e) | Jun 04, 2021 |
| HP            | 304Bh                       | [a41a097984](https://linux-hardware.org/?probe=a41a097984) | Jun 04, 2021 |
| ASUSTek       | PRIME A320M-K               | [c540bad35d](https://linux-hardware.org/?probe=c540bad35d) | Jun 03, 2021 |
| Huanan        | X99-TF                      | [b92f4485e6](https://linux-hardware.org/?probe=b92f4485e6) | May 31, 2021 |
| Gigabyte      | B450M DS3H-CF               | [d71af3d423](https://linux-hardware.org/?probe=d71af3d423) | May 31, 2021 |
| Gigabyte      | Z270X-UD3-CF                | [834a7ae73b](https://linux-hardware.org/?probe=834a7ae73b) | May 30, 2021 |
| ASRock        | B550M Steel Legend          | [f39108e22f](https://linux-hardware.org/?probe=f39108e22f) | May 29, 2021 |
| MSI           | 970 GAMING                  | [d0fd1ce0e8](https://linux-hardware.org/?probe=d0fd1ce0e8) | May 28, 2021 |
| Foxconn       | 2ABF                        | [57ffe115ac](https://linux-hardware.org/?probe=57ffe115ac) | May 26, 2021 |
| ASRock        | Z170 Extreme7+              | [3de199f8f3](https://linux-hardware.org/?probe=3de199f8f3) | May 26, 2021 |
| Dell          | 0D28YY A01                  | [4bd51e385d](https://linux-hardware.org/?probe=4bd51e385d) | May 25, 2021 |
| MSI           | Z490-A PRO                  | [e034d1b339](https://linux-hardware.org/?probe=e034d1b339) | May 23, 2021 |
| HP            | 158B                        | [e7d78d4e6c](https://linux-hardware.org/?probe=e7d78d4e6c) | May 21, 2021 |
| MSI           | H81M-E34                    | [ea9b132e77](https://linux-hardware.org/?probe=ea9b132e77) | May 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [54a21bec35](https://linux-hardware.org/?probe=54a21bec35) | May 19, 2021 |
| MSI           | Z170A GAMING M5             | [7493d31acb](https://linux-hardware.org/?probe=7493d31acb) | May 18, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [f12c26f48d](https://linux-hardware.org/?probe=f12c26f48d) | May 18, 2021 |
| HP            | 21B4 A01                    | [45752d3232](https://linux-hardware.org/?probe=45752d3232) | May 18, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [426ecdf62e](https://linux-hardware.org/?probe=426ecdf62e) | May 17, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [d01af38384](https://linux-hardware.org/?probe=d01af38384) | May 17, 2021 |
| Intel         | DX79SI AAG28808-600         | [4d5e452411](https://linux-hardware.org/?probe=4d5e452411) | May 16, 2021 |
| ASRock        | A320M-DGS                   | [e5a3726b96](https://linux-hardware.org/?probe=e5a3726b96) | May 16, 2021 |
| Foxconn       | 2ABF                        | [6e96a8df5f](https://linux-hardware.org/?probe=6e96a8df5f) | May 16, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [57b918a36e](https://linux-hardware.org/?probe=57b918a36e) | May 15, 2021 |
| ASUSTek       | PRIME B360M-A               | [22b412f033](https://linux-hardware.org/?probe=22b412f033) | May 15, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [2c5c989a79](https://linux-hardware.org/?probe=2c5c989a79) | May 14, 2021 |
| ASUSTek       | B85M-G                      | [29ad7fb8e1](https://linux-hardware.org/?probe=29ad7fb8e1) | May 12, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [3fd70c5b87](https://linux-hardware.org/?probe=3fd70c5b87) | May 12, 2021 |
| Dell          | 088DT1 A01                  | [3a544adcc9](https://linux-hardware.org/?probe=3a544adcc9) | May 11, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | [9ad8acccaa](https://linux-hardware.org/?probe=9ad8acccaa) | May 08, 2021 |
| MSI           | H110M PRO-VD                | [86167086f7](https://linux-hardware.org/?probe=86167086f7) | May 06, 2021 |
| ASRock        | Z170 Extreme7+              | [1e8acae283](https://linux-hardware.org/?probe=1e8acae283) | May 01, 2021 |
| ASRock        | Z170 Extreme7+              | [7de0627698](https://linux-hardware.org/?probe=7de0627698) | May 01, 2021 |
| Dell          | 0M858N A01                  | [5cf29d108d](https://linux-hardware.org/?probe=5cf29d108d) | Apr 29, 2021 |
| Dell          | 0M858N A01                  | [6db1d18e09](https://linux-hardware.org/?probe=6db1d18e09) | Apr 29, 2021 |
| Dell          | 0N13T1 A01                  | [7c02e11615](https://linux-hardware.org/?probe=7c02e11615) | Apr 28, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [0113cc8ad1](https://linux-hardware.org/?probe=0113cc8ad1) | Apr 26, 2021 |
| ASRock        | N68C-GS4 FX                 | [48953fbb84](https://linux-hardware.org/?probe=48953fbb84) | Apr 26, 2021 |
| Gigabyte      | Z170X-Gaming 5              | [54a619054a](https://linux-hardware.org/?probe=54a619054a) | Apr 24, 2021 |
| Gigabyte      | B450M GAMING                | [8ed2b2284e](https://linux-hardware.org/?probe=8ed2b2284e) | Apr 24, 2021 |
| HP            | 1497                        | [cfa3220a15](https://linux-hardware.org/?probe=cfa3220a15) | Apr 23, 2021 |
| HP            | 1497                        | [6d68a38b71](https://linux-hardware.org/?probe=6d68a38b71) | Apr 23, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [092f84c945](https://linux-hardware.org/?probe=092f84c945) | Apr 23, 2021 |
| HP            | 3397                        | [cbbaaa3476](https://linux-hardware.org/?probe=cbbaaa3476) | Apr 23, 2021 |
| Gigabyte      | F2A88X-D3HP                 | [9f418e1758](https://linux-hardware.org/?probe=9f418e1758) | Apr 23, 2021 |
| Gigabyte      | F2A88X-D3HP                 | [f05632d235](https://linux-hardware.org/?probe=f05632d235) | Apr 23, 2021 |
| HP            | 21B4 A01                    | [399b0bbaf6](https://linux-hardware.org/?probe=399b0bbaf6) | Apr 22, 2021 |
| Unknown       | Unknown                     | [39a0744819](https://linux-hardware.org/?probe=39a0744819) | Apr 20, 2021 |
| Dell          | 0G7W4R A00                  | [477ba6a2a6](https://linux-hardware.org/?probe=477ba6a2a6) | Apr 19, 2021 |
| Gigabyte      | P67A-D3-B3                  | [5bf2da0f2e](https://linux-hardware.org/?probe=5bf2da0f2e) | Apr 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1bd86cbcae](https://linux-hardware.org/?probe=1bd86cbcae) | Apr 17, 2021 |
| Gigabyte      | B365M DS3H                  | [1749421eaa](https://linux-hardware.org/?probe=1749421eaa) | Apr 16, 2021 |
| MSI           | B350 TOMAHAWK               | [382673d3f6](https://linux-hardware.org/?probe=382673d3f6) | Apr 15, 2021 |
| Unknown       | Unknown                     | [5ed47267b8](https://linux-hardware.org/?probe=5ed47267b8) | Apr 13, 2021 |
| MSI           | H110M PRO-VD                | [346db366ae](https://linux-hardware.org/?probe=346db366ae) | Apr 13, 2021 |
| MSI           | A320M-A PRO MAX             | [834cdeef2d](https://linux-hardware.org/?probe=834cdeef2d) | Apr 12, 2021 |
| Gigabyte      | AX370-Gaming K7             | [312edcd189](https://linux-hardware.org/?probe=312edcd189) | Apr 12, 2021 |
| Gigabyte      | AX370-Gaming K7             | [9fec121fac](https://linux-hardware.org/?probe=9fec121fac) | Apr 10, 2021 |
| MSI           | PH67S-C43                   | [bf84a891cc](https://linux-hardware.org/?probe=bf84a891cc) | Apr 10, 2021 |
| Gigabyte      | AX370-Gaming K7             | [88c4aeb7cb](https://linux-hardware.org/?probe=88c4aeb7cb) | Apr 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | [c367f0f682](https://linux-hardware.org/?probe=c367f0f682) | Apr 10, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [59cb82d24c](https://linux-hardware.org/?probe=59cb82d24c) | Apr 09, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [035b6fca1d](https://linux-hardware.org/?probe=035b6fca1d) | Apr 08, 2021 |
| MSI           | A320M-A PRO MAX             | [37a29de2c0](https://linux-hardware.org/?probe=37a29de2c0) | Apr 07, 2021 |
| ASRock        | J3355B-ITX                  | [8f3bd77b70](https://linux-hardware.org/?probe=8f3bd77b70) | Apr 06, 2021 |
| ASUSTek       | P8H61-M LE                  | [b7ca2f4a18](https://linux-hardware.org/?probe=b7ca2f4a18) | Apr 04, 2021 |
| Gigabyte      | A320M-H-CF                  | [0b31a00f14](https://linux-hardware.org/?probe=0b31a00f14) | Apr 04, 2021 |
| Unknown       | Unknown                     | [831b3f8c68](https://linux-hardware.org/?probe=831b3f8c68) | Apr 04, 2021 |
| Dell          | 0M5DCD A00                  | [0eaf54f4f5](https://linux-hardware.org/?probe=0eaf54f4f5) | Apr 03, 2021 |
| ASUSTek       | M4N68T-M LE                 | [819d6e7ad3](https://linux-hardware.org/?probe=819d6e7ad3) | Apr 03, 2021 |
| Dell          | 0M5DCD A00                  | [51543dbb4d](https://linux-hardware.org/?probe=51543dbb4d) | Apr 03, 2021 |
| ASUSTek       | H110M-C                     | [5809742ae4](https://linux-hardware.org/?probe=5809742ae4) | Apr 02, 2021 |
| ASRock        | Z270 Gaming-ITX/ac          | [c4b61cff94](https://linux-hardware.org/?probe=c4b61cff94) | Apr 02, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [4080e1b43f](https://linux-hardware.org/?probe=4080e1b43f) | Apr 01, 2021 |
| HP            | 8299                        | [12120a16f6](https://linux-hardware.org/?probe=12120a16f6) | Mar 30, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [d4f182e3de](https://linux-hardware.org/?probe=d4f182e3de) | Mar 30, 2021 |
| MSI           | X399 SLI PLUS               | [4caff5f0c4](https://linux-hardware.org/?probe=4caff5f0c4) | Mar 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [26427e6d23](https://linux-hardware.org/?probe=26427e6d23) | Mar 29, 2021 |
| ASUSTek       | P9X79                       | [262c2c82c1](https://linux-hardware.org/?probe=262c2c82c1) | Mar 29, 2021 |
| Gigabyte      | Z390 AORUS PRO-CF           | [9e88c8329e](https://linux-hardware.org/?probe=9e88c8329e) | Mar 28, 2021 |
| ASUSTek       | PRIME H270-PRO              | [c849cdad45](https://linux-hardware.org/?probe=c849cdad45) | Mar 27, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [bb2ba9b142](https://linux-hardware.org/?probe=bb2ba9b142) | Mar 24, 2021 |
| ASUSTek       | P8H77-V LE                  | [973d60c63e](https://linux-hardware.org/?probe=973d60c63e) | Mar 24, 2021 |
| Acer          | FIH57                       | [ddb03d82a0](https://linux-hardware.org/?probe=ddb03d82a0) | Mar 24, 2021 |
| MSI           | B365M PRO-VDH               | [85eae8241f](https://linux-hardware.org/?probe=85eae8241f) | Mar 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | [b139612360](https://linux-hardware.org/?probe=b139612360) | Mar 21, 2021 |
| Gigabyte      | A320M-H-CF                  | [6270efa573](https://linux-hardware.org/?probe=6270efa573) | Mar 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e2f4d3b86f](https://linux-hardware.org/?probe=e2f4d3b86f) | Mar 20, 2021 |
| Seco          | C40 C                       | [70a92f2d8a](https://linux-hardware.org/?probe=70a92f2d8a) | Mar 19, 2021 |
| Gigabyte      | Z170X-UD5-CF                | [edac373896](https://linux-hardware.org/?probe=edac373896) | Mar 19, 2021 |
| MSI           | H110M PRO-VD                | [4c78db6d10](https://linux-hardware.org/?probe=4c78db6d10) | Mar 18, 2021 |
| ASUSTek       | Maximus IV Extreme          | [42afab4523](https://linux-hardware.org/?probe=42afab4523) | Mar 18, 2021 |
| ASRock        | H67DE3                      | [14e5916050](https://linux-hardware.org/?probe=14e5916050) | Mar 18, 2021 |
| Gigabyte      | Z87-HD3                     | [ff76102e23](https://linux-hardware.org/?probe=ff76102e23) | Mar 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [4d8d7a3551](https://linux-hardware.org/?probe=4d8d7a3551) | Mar 17, 2021 |
| ASRock        | G41C-VS                     | [6ef4d0ea12](https://linux-hardware.org/?probe=6ef4d0ea12) | Mar 16, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [402cbaf164](https://linux-hardware.org/?probe=402cbaf164) | Mar 15, 2021 |
| MSI           | MPG Z490M GAMING EDGE WI... | [b8d7e8ae57](https://linux-hardware.org/?probe=b8d7e8ae57) | Mar 14, 2021 |
| Gigabyte      | B365M DS3H                  | [50735eb518](https://linux-hardware.org/?probe=50735eb518) | Mar 13, 2021 |
| Dell          | 0KRC95 A02                  | [ced325be18](https://linux-hardware.org/?probe=ced325be18) | Mar 12, 2021 |
| Gigabyte      | GA-970-Gaming SLI-CF        | [e3f7effc1c](https://linux-hardware.org/?probe=e3f7effc1c) | Mar 03, 2021 |
| Acer          | Aspire X3400                | [37dca6b989](https://linux-hardware.org/?probe=37dca6b989) | Mar 03, 2021 |
| HP            | 8299                        | [e8e31dfc6e](https://linux-hardware.org/?probe=e8e31dfc6e) | Mar 01, 2021 |
| Foxconn       | 2AB1                        | [94f5daf626](https://linux-hardware.org/?probe=94f5daf626) | Feb 28, 2021 |
| Dell          | 0XPDFK A01                  | [88dfa8bfe4](https://linux-hardware.org/?probe=88dfa8bfe4) | Feb 27, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0560c0ea42](https://linux-hardware.org/?probe=0560c0ea42) | Feb 27, 2021 |
| HP            | 1589                        | [8784e0d9ad](https://linux-hardware.org/?probe=8784e0d9ad) | Feb 22, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [e6bcb06746](https://linux-hardware.org/?probe=e6bcb06746) | Feb 20, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [25a2434de6](https://linux-hardware.org/?probe=25a2434de6) | Feb 19, 2021 |
| Gigabyte      | EP45-UD3P                   | [2caf18393e](https://linux-hardware.org/?probe=2caf18393e) | Feb 18, 2021 |
| Gigabyte      | F2A88X-D3H                  | [ea95229d12](https://linux-hardware.org/?probe=ea95229d12) | Feb 18, 2021 |
| ASUSTek       | PRIME A320M-K               | [acdf8601fd](https://linux-hardware.org/?probe=acdf8601fd) | Feb 18, 2021 |
| MSI           | X470 GAMING PLUS            | [51e50d143a](https://linux-hardware.org/?probe=51e50d143a) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [65b32aa4a5](https://linux-hardware.org/?probe=65b32aa4a5) | Feb 16, 2021 |
| MSI           | A320M-A PRO MAX             | [fb6179a8ee](https://linux-hardware.org/?probe=fb6179a8ee) | Feb 16, 2021 |
| Dell          | 0HN7XN A01                  | [848bce680c](https://linux-hardware.org/?probe=848bce680c) | Feb 15, 2021 |
| JINGSHA       | Unknown                     | [8f0c5a3c20](https://linux-hardware.org/?probe=8f0c5a3c20) | Feb 14, 2021 |
| Lenovo        | ThinkCentre M90p 5498PK8    | [df39a8847b](https://linux-hardware.org/?probe=df39a8847b) | Feb 14, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [99b31bd894](https://linux-hardware.org/?probe=99b31bd894) | Feb 13, 2021 |
| MSI           | B85M-E45                    | [16c99d1061](https://linux-hardware.org/?probe=16c99d1061) | Feb 13, 2021 |
| ASRock        | X570 Extreme4               | [3f2929b8fd](https://linux-hardware.org/?probe=3f2929b8fd) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [d993271043](https://linux-hardware.org/?probe=d993271043) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [ab8c311c17](https://linux-hardware.org/?probe=ab8c311c17) | Feb 11, 2021 |
| Dell          | 0F896N A03                  | [2dd5786964](https://linux-hardware.org/?probe=2dd5786964) | Feb 10, 2021 |
| AZW           | Gemini M                    | [a610efb6d7](https://linux-hardware.org/?probe=a610efb6d7) | Feb 08, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [dd9e4c1dde](https://linux-hardware.org/?probe=dd9e4c1dde) | Feb 07, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [1835552ae4](https://linux-hardware.org/?probe=1835552ae4) | Feb 06, 2021 |
| Intel         | D33217GKE G76540-205        | [acd358e227](https://linux-hardware.org/?probe=acd358e227) | Feb 06, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [c40d5bfeff](https://linux-hardware.org/?probe=c40d5bfeff) | Feb 05, 2021 |
| ASRock        | A300M-STX                   | [ceda1f734f](https://linux-hardware.org/?probe=ceda1f734f) | Feb 04, 2021 |
| Gigabyte      | GA-790XT-USB3               | [d14e71b6b4](https://linux-hardware.org/?probe=d14e71b6b4) | Feb 03, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [d88bfb96f9](https://linux-hardware.org/?probe=d88bfb96f9) | Feb 01, 2021 |
| MSI           | Z170A SLI PLUS              | [2e49a21374](https://linux-hardware.org/?probe=2e49a21374) | Feb 01, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1292b81dfa](https://linux-hardware.org/?probe=1292b81dfa) | Feb 01, 2021 |
| HP            | 8299                        | [16e50ec1cd](https://linux-hardware.org/?probe=16e50ec1cd) | Jan 31, 2021 |
| ASRock        | Z170 Extreme7+              | [8f8b3ad8e1](https://linux-hardware.org/?probe=8f8b3ad8e1) | Jan 31, 2021 |
| ASRock        | E350M1/USB3                 | [fc0abf0e10](https://linux-hardware.org/?probe=fc0abf0e10) | Jan 30, 2021 |
| ASUSTek       | AM1M-A/BR                   | [f8f1db15da](https://linux-hardware.org/?probe=f8f1db15da) | Jan 26, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [8c7c26863a](https://linux-hardware.org/?probe=8c7c26863a) | Jan 26, 2021 |
| ASUSTek       | AM1M-A/BR                   | [f44186ef76](https://linux-hardware.org/?probe=f44186ef76) | Jan 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [b1f5eac9a6](https://linux-hardware.org/?probe=b1f5eac9a6) | Jan 23, 2021 |
| Gigabyte      | H110M-A-CF                  | [d8b9528d50](https://linux-hardware.org/?probe=d8b9528d50) | Jan 23, 2021 |
| MSI           | X58 Pro-E                   | [b5a0f60525](https://linux-hardware.org/?probe=b5a0f60525) | Jan 22, 2021 |
| ASRock        | N68C-S UCC                  | [4296bcfa3c](https://linux-hardware.org/?probe=4296bcfa3c) | Jan 21, 2021 |
| Pegatron      | M2N-VM1394                  | [5405301d47](https://linux-hardware.org/?probe=5405301d47) | Jan 21, 2021 |
| ASRock        | A300M-STX                   | [4f8794ed64](https://linux-hardware.org/?probe=4f8794ed64) | Jan 21, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [c1bf2c43e1](https://linux-hardware.org/?probe=c1bf2c43e1) | Jan 21, 2021 |
| Gigabyte      | B365M HD3                   | [32878b3dae](https://linux-hardware.org/?probe=32878b3dae) | Jan 20, 2021 |
| Gigabyte      | B365M HD3                   | [03b73f8223](https://linux-hardware.org/?probe=03b73f8223) | Jan 20, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [09f7b419ec](https://linux-hardware.org/?probe=09f7b419ec) | Jan 20, 2021 |
| ASUSTek       | PRIME Q270M-C               | [c485dcca0d](https://linux-hardware.org/?probe=c485dcca0d) | Jan 20, 2021 |
| Pegatron      | M2N-VM1394                  | [837561f3bf](https://linux-hardware.org/?probe=837561f3bf) | Jan 19, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [c765adbbfc](https://linux-hardware.org/?probe=c765adbbfc) | Jan 18, 2021 |
| ASRock        | Z170 Extreme7+              | [293421172c](https://linux-hardware.org/?probe=293421172c) | Jan 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [866d489976](https://linux-hardware.org/?probe=866d489976) | Jan 15, 2021 |
| Huanan        | X79 VAA1                    | [d88d20e6fc](https://linux-hardware.org/?probe=d88d20e6fc) | Jan 15, 2021 |
| MSI           | X570-A PRO                  | [c121653064](https://linux-hardware.org/?probe=c121653064) | Jan 14, 2021 |
| MSI           | X570-A PRO                  | [07bd3ed250](https://linux-hardware.org/?probe=07bd3ed250) | Jan 14, 2021 |
| ASUSTek       | P8Z77-V LX                  | [f631333cfc](https://linux-hardware.org/?probe=f631333cfc) | Jan 13, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [a732f970ee](https://linux-hardware.org/?probe=a732f970ee) | Jan 13, 2021 |
| Gigabyte      | G33-DS3R                    | [490a799d8b](https://linux-hardware.org/?probe=490a799d8b) | Jan 13, 2021 |
| ASUSTek       | Berkeley                    | [4db5f0b0aa](https://linux-hardware.org/?probe=4db5f0b0aa) | Jan 12, 2021 |
| Gigabyte      | GA-790XT-USB3               | [637d6c6ea6](https://linux-hardware.org/?probe=637d6c6ea6) | Jan 11, 2021 |
| ASRock        | Z170 Extreme7+              | [7fdf42857e](https://linux-hardware.org/?probe=7fdf42857e) | Jan 08, 2021 |
| ASRock        | Z170 Extreme7+              | [73f1457335](https://linux-hardware.org/?probe=73f1457335) | Jan 08, 2021 |
| ASUSTek       | AM1M-A/BR                   | [2641a0bb89](https://linux-hardware.org/?probe=2641a0bb89) | Jan 06, 2021 |
| MSI           | B75A-G43                    | [23c8b4ee0a](https://linux-hardware.org/?probe=23c8b4ee0a) | Jan 06, 2021 |
| Gigabyte      | G41MT-S2                    | [ee6e390e3c](https://linux-hardware.org/?probe=ee6e390e3c) | Jan 06, 2021 |
| ASRock        | B450M Pro4                  | [c5fba295b9](https://linux-hardware.org/?probe=c5fba295b9) | Jan 05, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [1a2f4429b1](https://linux-hardware.org/?probe=1a2f4429b1) | Jan 05, 2021 |
| Alienware     | 0T76PD A01                  | [453a903a3b](https://linux-hardware.org/?probe=453a903a3b) | Jan 03, 2021 |
| ASRock        | 775Dual-VSTA                | [e45a885545](https://linux-hardware.org/?probe=e45a885545) | Jan 03, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [b4f32eead2](https://linux-hardware.org/?probe=b4f32eead2) | Jan 03, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [d4b2a29860](https://linux-hardware.org/?probe=d4b2a29860) | Jan 03, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [7b4723037b](https://linux-hardware.org/?probe=7b4723037b) | Jan 03, 2021 |
| ASRock        | N68C-GS4 FX                 | [cf19e9b8ee](https://linux-hardware.org/?probe=cf19e9b8ee) | Jan 03, 2021 |
| MSI           | H310M PRO-M2                | [d3ae82193a](https://linux-hardware.org/?probe=d3ae82193a) | Jan 02, 2021 |
| ASRock        | A300M-STX                   | [bd23fb61ad](https://linux-hardware.org/?probe=bd23fb61ad) | Jan 01, 2021 |
| Gigabyte      | F2A88XM-HD3                 | [3656c88417](https://linux-hardware.org/?probe=3656c88417) | Jan 01, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [6fddc5c5e3](https://linux-hardware.org/?probe=6fddc5c5e3) | Dec 31, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [d31654b018](https://linux-hardware.org/?probe=d31654b018) | Dec 31, 2020 |
| Biostar       | TA790GXB A2+                | [f308fe673b](https://linux-hardware.org/?probe=f308fe673b) | Dec 30, 2020 |
| Intel         | X58M                        | [e0308437db](https://linux-hardware.org/?probe=e0308437db) | Dec 30, 2020 |
| Intel         | H110                        | [61d0cc0b0d](https://linux-hardware.org/?probe=61d0cc0b0d) | Dec 29, 2020 |
| MSI           | H61M-P20                    | [f402863234](https://linux-hardware.org/?probe=f402863234) | Dec 29, 2020 |
| ASUSTek       | PRIME A320M-K               | [cc4041e701](https://linux-hardware.org/?probe=cc4041e701) | Dec 28, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [095b9feabe](https://linux-hardware.org/?probe=095b9feabe) | Dec 28, 2020 |
| MSI           | Z77A-G41                    | [171be87aa0](https://linux-hardware.org/?probe=171be87aa0) | Dec 27, 2020 |
| ASRock        | P67 Extreme6                | [276b4b3251](https://linux-hardware.org/?probe=276b4b3251) | Dec 26, 2020 |
| ASRock        | P67 Extreme6                | [49ac9f184b](https://linux-hardware.org/?probe=49ac9f184b) | Dec 26, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [dcef8dba06](https://linux-hardware.org/?probe=dcef8dba06) | Dec 25, 2020 |
| ASUSTek       | PRIME A320M-C R2.0          | [c2463308c5](https://linux-hardware.org/?probe=c2463308c5) | Dec 24, 2020 |
| Gigabyte      | F2A88XM-HD3                 | [eb82a63318](https://linux-hardware.org/?probe=eb82a63318) | Dec 24, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ba557d3a92](https://linux-hardware.org/?probe=ba557d3a92) | Dec 23, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f10fd9d89d](https://linux-hardware.org/?probe=f10fd9d89d) | Dec 23, 2020 |
| Gigabyte      | GA-990FXA-UD3               | [191e84568a](https://linux-hardware.org/?probe=191e84568a) | Dec 22, 2020 |
| MSI           | MS-7388                     | [2470f3c112](https://linux-hardware.org/?probe=2470f3c112) | Dec 22, 2020 |
| ASUSTek       | PRIME A320M-K/BR            | [6af7f81ca3](https://linux-hardware.org/?probe=6af7f81ca3) | Dec 20, 2020 |
| ASRock        | P55 Pro                     | [2c93457122](https://linux-hardware.org/?probe=2c93457122) | Dec 18, 2020 |
| Lenovo        | MAHOBAY                     | [0f2eefc2e9](https://linux-hardware.org/?probe=0f2eefc2e9) | Dec 18, 2020 |
| Gigabyte      | Z77-DS3H                    | [e7d015bde4](https://linux-hardware.org/?probe=e7d015bde4) | Dec 16, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2711b7a9b7](https://linux-hardware.org/?probe=2711b7a9b7) | Dec 13, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | [a7dd5ba89e](https://linux-hardware.org/?probe=a7dd5ba89e) | Dec 10, 2020 |
| HP            | 339A                        | [81a0e65daf](https://linux-hardware.org/?probe=81a0e65daf) | Dec 09, 2020 |
| Gigabyte      | B360M D3H-CF                | [27f9412b8a](https://linux-hardware.org/?probe=27f9412b8a) | Dec 08, 2020 |
| Dell          | 09KPNV A01                  | [7615b677f1](https://linux-hardware.org/?probe=7615b677f1) | Dec 05, 2020 |
| Pegatron      | 2AB5                        | [070afe6a00](https://linux-hardware.org/?probe=070afe6a00) | Dec 04, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [e9fb942639](https://linux-hardware.org/?probe=e9fb942639) | Dec 04, 2020 |
| Gigabyte      | GA-MA74GM-S2H               | [17333fb7fd](https://linux-hardware.org/?probe=17333fb7fd) | Dec 03, 2020 |
| HP            | 2129                        | [2d6a252f42](https://linux-hardware.org/?probe=2d6a252f42) | Dec 02, 2020 |
| MSI           | NF980-G65                   | [905c03a3d4](https://linux-hardware.org/?probe=905c03a3d4) | Dec 02, 2020 |
| Dell          | 0R849J A01                  | [a9811d7fbd](https://linux-hardware.org/?probe=a9811d7fbd) | Dec 01, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [2c52f626c8](https://linux-hardware.org/?probe=2c52f626c8) | Dec 01, 2020 |
| Dell          | 0R849J A01                  | [024d1c547d](https://linux-hardware.org/?probe=024d1c547d) | Nov 30, 2020 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [cedd6ad29f](https://linux-hardware.org/?probe=cedd6ad29f) | Nov 29, 2020 |
| MSI           | MAG B550M MORTAR            | [37f28ef73f](https://linux-hardware.org/?probe=37f28ef73f) | Nov 29, 2020 |
| ASUSTek       | AM1I-A                      | [b3202de053](https://linux-hardware.org/?probe=b3202de053) | Nov 26, 2020 |
| MSI           | MEG X570 UNIFY              | [a50e9bd7bb](https://linux-hardware.org/?probe=a50e9bd7bb) | Nov 25, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [c433b6c798](https://linux-hardware.org/?probe=c433b6c798) | Nov 24, 2020 |
| ECS           | GeForce6100PM-M2            | [ff1cc0b0b7](https://linux-hardware.org/?probe=ff1cc0b0b7) | Nov 21, 2020 |
| Dell          | 048DY8 A01                  | [206fc66c5c](https://linux-hardware.org/?probe=206fc66c5c) | Nov 19, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [490fa38293](https://linux-hardware.org/?probe=490fa38293) | Nov 19, 2020 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [fabdb78a80](https://linux-hardware.org/?probe=fabdb78a80) | Nov 19, 2020 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [8b1f5d16fc](https://linux-hardware.org/?probe=8b1f5d16fc) | Nov 18, 2020 |
| ASRock        | AB350 Pro4                  | [c8af4ac482](https://linux-hardware.org/?probe=c8af4ac482) | Nov 18, 2020 |
| Biostar       | B350GT3                     | [35a9330750](https://linux-hardware.org/?probe=35a9330750) | Nov 17, 2020 |
| Biostar       | B350GT3                     | [2f41a7e32d](https://linux-hardware.org/?probe=2f41a7e32d) | Nov 17, 2020 |
| MSI           | MEG X570 ACE                | [df9073af0d](https://linux-hardware.org/?probe=df9073af0d) | Nov 16, 2020 |
| MSI           | B75A-G43                    | [3674b1e802](https://linux-hardware.org/?probe=3674b1e802) | Nov 16, 2020 |
| Gigabyte      | 970A-DS3P                   | [401a871151](https://linux-hardware.org/?probe=401a871151) | Nov 15, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | [bdb4536081](https://linux-hardware.org/?probe=bdb4536081) | Nov 15, 2020 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [50cab28a32](https://linux-hardware.org/?probe=50cab28a32) | Nov 14, 2020 |
| MSI           | B85-G41 PC Mate             | [37775c5053](https://linux-hardware.org/?probe=37775c5053) | Nov 12, 2020 |
| ASRock        | P55 Pro/USB3                | [c6d943db90](https://linux-hardware.org/?probe=c6d943db90) | Nov 12, 2020 |
| ASUSTek       | A88XM-E                     | [52b7c8a912](https://linux-hardware.org/?probe=52b7c8a912) | Nov 12, 2020 |
| Dell          | 0M3918                      | [1ae4feee32](https://linux-hardware.org/?probe=1ae4feee32) | Nov 10, 2020 |
| ASUSTek       | A55BM-K                     | [bff939ac49](https://linux-hardware.org/?probe=bff939ac49) | Nov 09, 2020 |
| ASRock        | N68-S3 FX                   | [3d560dcd13](https://linux-hardware.org/?probe=3d560dcd13) | Nov 08, 2020 |
| Gigabyte      | F2A88X-D3H                  | [2846226b13](https://linux-hardware.org/?probe=2846226b13) | Nov 08, 2020 |
| Dell          | 054KM3 A00                  | [e24f78dcc5](https://linux-hardware.org/?probe=e24f78dcc5) | Nov 05, 2020 |
| ASUSTek       | P8P67-M PRO                 | [45a8acd5b2](https://linux-hardware.org/?probe=45a8acd5b2) | Nov 05, 2020 |
| MSI           | NF980-G65                   | [91f0882001](https://linux-hardware.org/?probe=91f0882001) | Nov 04, 2020 |
| Dell          | 0KWVT8 A02                  | [2403e6e21e](https://linux-hardware.org/?probe=2403e6e21e) | Nov 03, 2020 |
| MSI           | X370 GAMING PLUS            | [bc7b255540](https://linux-hardware.org/?probe=bc7b255540) | Oct 31, 2020 |
| HP            | 1497                        | [522b4035a5](https://linux-hardware.org/?probe=522b4035a5) | Oct 31, 2020 |
| ASRock        | Z170 OC Formula             | [067d0719a1](https://linux-hardware.org/?probe=067d0719a1) | Oct 30, 2020 |
| Packard Be... | Veriton M275                | [0d3ab22c33](https://linux-hardware.org/?probe=0d3ab22c33) | Oct 30, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | [08b544552e](https://linux-hardware.org/?probe=08b544552e) | Oct 29, 2020 |
| MSI           | Z270 SLI                    | [f8adb0fcd7](https://linux-hardware.org/?probe=f8adb0fcd7) | Oct 29, 2020 |
| Dell          | 0X75JG A00                  | [b984a93bcc](https://linux-hardware.org/?probe=b984a93bcc) | Oct 29, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | [3f18f3f21e](https://linux-hardware.org/?probe=3f18f3f21e) | Oct 28, 2020 |
| ASRock        | Z170 Extreme7+              | [68232dd449](https://linux-hardware.org/?probe=68232dd449) | Oct 28, 2020 |
| Foxconn       | 2AB1                        | [abc0471a17](https://linux-hardware.org/?probe=abc0471a17) | Oct 27, 2020 |
| Dell          | 03NVJ6 A01                  | [10f9e6c3d8](https://linux-hardware.org/?probe=10f9e6c3d8) | Oct 25, 2020 |
| Lenovo        | 3706 SDK0J40700 WIN 3258... | [d19a6fb1ad](https://linux-hardware.org/?probe=d19a6fb1ad) | Oct 24, 2020 |
| ASUSTek       | PRIME Z390-P                | [7e20defaed](https://linux-hardware.org/?probe=7e20defaed) | Oct 24, 2020 |
| MSI           | NF980-G65                   | [b37787e43b](https://linux-hardware.org/?probe=b37787e43b) | Oct 24, 2020 |
| Packard Be... | M2N-NM                      | [52db91efa6](https://linux-hardware.org/?probe=52db91efa6) | Oct 23, 2020 |
| ASRock        | Z170 Extreme7+              | [892b8db889](https://linux-hardware.org/?probe=892b8db889) | Oct 23, 2020 |
| Dell          | 0XPDFK A01                  | [0224c9fc78](https://linux-hardware.org/?probe=0224c9fc78) | Oct 22, 2020 |
| Gigabyte      | 970A-DS3P                   | [4c38164a20](https://linux-hardware.org/?probe=4c38164a20) | Oct 21, 2020 |
| Gigabyte      | F2A88X-D3H                  | [c48530abc5](https://linux-hardware.org/?probe=c48530abc5) | Oct 21, 2020 |
| Dell          | 088DT1 A01                  | [41919737ef](https://linux-hardware.org/?probe=41919737ef) | Oct 20, 2020 |
| ASUSTek       | PRIME Z390-P                | [98ab87075c](https://linux-hardware.org/?probe=98ab87075c) | Oct 18, 2020 |
| MSI           | Z370M MORTAR                | [0a86954ea1](https://linux-hardware.org/?probe=0a86954ea1) | Oct 18, 2020 |
| Acer          | Aspire XC-605               | [77bfaa4cf4](https://linux-hardware.org/?probe=77bfaa4cf4) | Oct 17, 2020 |
| Pegatron      | M2N-VM1394                  | [1fe28c5fbb](https://linux-hardware.org/?probe=1fe28c5fbb) | Oct 15, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [b252bc95af](https://linux-hardware.org/?probe=b252bc95af) | Oct 15, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | [e0f9f6a923](https://linux-hardware.org/?probe=e0f9f6a923) | Oct 14, 2020 |
| ZOTAC         | MEK Mini                    | [9e475e6609](https://linux-hardware.org/?probe=9e475e6609) | Oct 14, 2020 |
| Pegatron      | IPM31G                      | [e42252fd1c](https://linux-hardware.org/?probe=e42252fd1c) | Oct 14, 2020 |
| Pegatron      | IPM31G                      | [5026b30c12](https://linux-hardware.org/?probe=5026b30c12) | Oct 13, 2020 |
| Intel         | H55                         | [9b6779ffba](https://linux-hardware.org/?probe=9b6779ffba) | Oct 13, 2020 |
| Gigabyte      | Z77-D3H                     | [f788b311f5](https://linux-hardware.org/?probe=f788b311f5) | Oct 12, 2020 |
| Gigabyte      | Z68XP-UD3                   | [ee0649427b](https://linux-hardware.org/?probe=ee0649427b) | Oct 12, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [ede21e126b](https://linux-hardware.org/?probe=ede21e126b) | Oct 12, 2020 |
| ASRock        | AB350M-HDV R3.0             | [368bc3c902](https://linux-hardware.org/?probe=368bc3c902) | Oct 11, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [47dc69334e](https://linux-hardware.org/?probe=47dc69334e) | Oct 10, 2020 |
| WeiBu         | WTGLKC1R120 SD-BS-CJ41G-... | [bf41c99f19](https://linux-hardware.org/?probe=bf41c99f19) | Oct 10, 2020 |
| ASUSTek       | Z87-A                       | [7e99ba9f73](https://linux-hardware.org/?probe=7e99ba9f73) | Oct 08, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [5d3f7000fa](https://linux-hardware.org/?probe=5d3f7000fa) | Oct 08, 2020 |
| HP            | 1998                        | [36f71f3062](https://linux-hardware.org/?probe=36f71f3062) | Oct 07, 2020 |
| Gigabyte      | X570 GAMING X               | [1d28040300](https://linux-hardware.org/?probe=1d28040300) | Oct 05, 2020 |
| Gigabyte      | B360M HD3                   | [e0aadcb07c](https://linux-hardware.org/?probe=e0aadcb07c) | Oct 04, 2020 |
| ASRock        | A300M-STX                   | [48d09a0a0f](https://linux-hardware.org/?probe=48d09a0a0f) | Oct 03, 2020 |
| ASRock        | B450 Pro4                   | [e7a5537652](https://linux-hardware.org/?probe=e7a5537652) | Oct 02, 2020 |
| MSI           | B350M MORTAR ARCTIC         | [afa58777a9](https://linux-hardware.org/?probe=afa58777a9) | Oct 02, 2020 |
| Biostar       | A320MH                      | [ee41403938](https://linux-hardware.org/?probe=ee41403938) | Oct 02, 2020 |
| Gigabyte      | 970A-DS3P                   | [fcd36c5060](https://linux-hardware.org/?probe=fcd36c5060) | Oct 02, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [c32337249b](https://linux-hardware.org/?probe=c32337249b) | Sep 30, 2020 |
| Gigabyte      | Z97X-Gaming 5               | [3bee2f38f1](https://linux-hardware.org/?probe=3bee2f38f1) | Sep 29, 2020 |
| Gigabyte      | Z97X-Gaming 5               | [7478c9e282](https://linux-hardware.org/?probe=7478c9e282) | Sep 29, 2020 |
| WeiBu         | WTGLKC1R120 SD-BS-CJ41G-... | [ee0a5bb389](https://linux-hardware.org/?probe=ee0a5bb389) | Sep 29, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [47838e477e](https://linux-hardware.org/?probe=47838e477e) | Sep 29, 2020 |
| ASUSTek       | PRIME B450M-A               | [a36b437918](https://linux-hardware.org/?probe=a36b437918) | Sep 28, 2020 |
| Gigabyte      | B450M DS3H-CF               | [b49235a2e5](https://linux-hardware.org/?probe=b49235a2e5) | Sep 28, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [cf7fb176a2](https://linux-hardware.org/?probe=cf7fb176a2) | Sep 28, 2020 |
| MSI           | Z97A SLI Krait Edition      | [8204be4261](https://linux-hardware.org/?probe=8204be4261) | Sep 28, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | [a0ef0c68c8](https://linux-hardware.org/?probe=a0ef0c68c8) | Sep 28, 2020 |
| Gigabyte      | F2A88XM-D3H                 | [ea4ebc4c7c](https://linux-hardware.org/?probe=ea4ebc4c7c) | Sep 27, 2020 |
| ASRock        | 775Dual-VSTA                | [40ed4cc83b](https://linux-hardware.org/?probe=40ed4cc83b) | Sep 24, 2020 |
| WeiBu         | WTGLKC1R120 SD-BS-CJ41G-... | [c42578d8e4](https://linux-hardware.org/?probe=c42578d8e4) | Sep 24, 2020 |
| ASUSTek       | B85M-E/BR                   | [b3089d3cb7](https://linux-hardware.org/?probe=b3089d3cb7) | Sep 24, 2020 |
| ASUSTek       | B85M-E/BR                   | [d734e4f3a6](https://linux-hardware.org/?probe=d734e4f3a6) | Sep 24, 2020 |
| Foxconn       | 2AB1                        | [49ad44dfa5](https://linux-hardware.org/?probe=49ad44dfa5) | Sep 22, 2020 |
| ASRock        | H110M-HG4                   | [bf0521b64f](https://linux-hardware.org/?probe=bf0521b64f) | Sep 22, 2020 |
| MSI           | MPG Z390 GAMING EDGE AC     | [de8040f8f2](https://linux-hardware.org/?probe=de8040f8f2) | Sep 20, 2020 |
| ASRock        | B450M-HDV                   | [18c72cc162](https://linux-hardware.org/?probe=18c72cc162) | Sep 20, 2020 |
| Koloe         | X58                         | [81d474ab62](https://linux-hardware.org/?probe=81d474ab62) | Sep 20, 2020 |
| Pegatron      | 2AB5                        | [00d244942e](https://linux-hardware.org/?probe=00d244942e) | Sep 18, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0cf8ee1ae8](https://linux-hardware.org/?probe=0cf8ee1ae8) | Sep 16, 2020 |
| Dell          | 0M5DCD A00                  | [a309e5b32f](https://linux-hardware.org/?probe=a309e5b32f) | Sep 16, 2020 |
| Dell          | 0M5DCD A00                  | [3b0cfbae5d](https://linux-hardware.org/?probe=3b0cfbae5d) | Sep 16, 2020 |
| Gigabyte      | B550M DS3H                  | [b2f1c44a0a](https://linux-hardware.org/?probe=b2f1c44a0a) | Sep 14, 2020 |
| ASRock        | H110M-HG4                   | [21fae97e39](https://linux-hardware.org/?probe=21fae97e39) | Sep 13, 2020 |
| Gigabyte      | A320M-S2H-CF                | [c7631d7914](https://linux-hardware.org/?probe=c7631d7914) | Sep 12, 2020 |
| Gigabyte      | M68MT-S2P                   | [b23396f446](https://linux-hardware.org/?probe=b23396f446) | Sep 10, 2020 |
| MSI           | B450M PRO-VDH MAX           | [044c2421f2](https://linux-hardware.org/?probe=044c2421f2) | Sep 10, 2020 |
| HP            | 3031h                       | [55e0edb811](https://linux-hardware.org/?probe=55e0edb811) | Sep 09, 2020 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [fe6668f9b4](https://linux-hardware.org/?probe=fe6668f9b4) | Sep 08, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [c45b64a8d0](https://linux-hardware.org/?probe=c45b64a8d0) | Sep 08, 2020 |
| Gigabyte      | B360M HD3                   | [7521b3b6e2](https://linux-hardware.org/?probe=7521b3b6e2) | Sep 07, 2020 |
| ASUSTek       | P6T                         | [5b4f0b4a9d](https://linux-hardware.org/?probe=5b4f0b4a9d) | Sep 06, 2020 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [6435c0f263](https://linux-hardware.org/?probe=6435c0f263) | Sep 06, 2020 |
| Gigabyte      | M68MT-S2P                   | [e27a9041fe](https://linux-hardware.org/?probe=e27a9041fe) | Sep 06, 2020 |
| ASUSTek       | Z170-A                      | [543b18512b](https://linux-hardware.org/?probe=543b18512b) | Sep 05, 2020 |
| Gigabyte      | 970A-DS3P                   | [b1248e2b3b](https://linux-hardware.org/?probe=b1248e2b3b) | Sep 05, 2020 |
| HP            | 843B                        | [9af121301d](https://linux-hardware.org/?probe=9af121301d) | Sep 05, 2020 |
| Gigabyte      | F2A75M-D3H                  | [ffa4fe7acd](https://linux-hardware.org/?probe=ffa4fe7acd) | Sep 04, 2020 |
| ASUSTek       | H170 PRO GAMING             | [2e8f4e982d](https://linux-hardware.org/?probe=2e8f4e982d) | Sep 04, 2020 |
| ASUSTek       | H170 PRO GAMING             | [b079daad2c](https://linux-hardware.org/?probe=b079daad2c) | Sep 04, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | [242f9cb8c6](https://linux-hardware.org/?probe=242f9cb8c6) | Sep 03, 2020 |
| MSI           | MAG B550 TOMAHAWK           | [84ab08b92f](https://linux-hardware.org/?probe=84ab08b92f) | Sep 03, 2020 |
| MSI           | MAG B550 TOMAHAWK           | [57787ad63d](https://linux-hardware.org/?probe=57787ad63d) | Sep 03, 2020 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [66f1d9fde1](https://linux-hardware.org/?probe=66f1d9fde1) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [13e0a80ca9](https://linux-hardware.org/?probe=13e0a80ca9) | Sep 03, 2020 |
| MSI           | Z97-G45 GAMING              | [23d327ddd1](https://linux-hardware.org/?probe=23d327ddd1) | Sep 02, 2020 |
| HP            | 3031h                       | [07f0c3ce98](https://linux-hardware.org/?probe=07f0c3ce98) | Sep 01, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [1f74a97af3](https://linux-hardware.org/?probe=1f74a97af3) | Sep 01, 2020 |
| ECS           | 945GCT-M3                   | [f9ba0e8e03](https://linux-hardware.org/?probe=f9ba0e8e03) | Sep 01, 2020 |
| MSI           | Boston                      | [90c8e43351](https://linux-hardware.org/?probe=90c8e43351) | Aug 31, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [78553c451b](https://linux-hardware.org/?probe=78553c451b) | Aug 31, 2020 |
| Dell          | 048DY8 A01                  | [bc89fe6963](https://linux-hardware.org/?probe=bc89fe6963) | Aug 31, 2020 |
| ASUSTek       | P5Q SE                      | [37d2955943](https://linux-hardware.org/?probe=37d2955943) | Aug 30, 2020 |
| ASUSTek       | PRIME B450M-A               | [e4cd61504d](https://linux-hardware.org/?probe=e4cd61504d) | Aug 29, 2020 |
| MSI           | B550-A PRO                  | [8a0712da96](https://linux-hardware.org/?probe=8a0712da96) | Aug 28, 2020 |
| HP            | 0266                        | [b2d762f823](https://linux-hardware.org/?probe=b2d762f823) | Aug 27, 2020 |
| ASRock        | Z87E-ITX                    | [e286963b35](https://linux-hardware.org/?probe=e286963b35) | Aug 26, 2020 |
| ASRock        | H410M-HVS                   | [6fb6841972](https://linux-hardware.org/?probe=6fb6841972) | Aug 26, 2020 |
| ASUSTek       | H110M-CS/BR                 | [e1f992e468](https://linux-hardware.org/?probe=e1f992e468) | Aug 26, 2020 |
| HP            | 339A                        | [6565380ec2](https://linux-hardware.org/?probe=6565380ec2) | Aug 26, 2020 |
| ASRock        | Z170 Extreme7+              | [019aa19877](https://linux-hardware.org/?probe=019aa19877) | Aug 25, 2020 |
| ASUSTek       | PRIME Z390-P                | [4889be0d7d](https://linux-hardware.org/?probe=4889be0d7d) | Aug 22, 2020 |
| Gigabyte      | F2A75M-D3H                  | [d958b35d39](https://linux-hardware.org/?probe=d958b35d39) | Aug 21, 2020 |
| HP            | 212B                        | [2ec5e51a63](https://linux-hardware.org/?probe=2ec5e51a63) | Aug 21, 2020 |
| Pegatron      | 2AB5                        | [954d271b91](https://linux-hardware.org/?probe=954d271b91) | Aug 20, 2020 |
| ASRock        | B360M Performance           | [52345bce36](https://linux-hardware.org/?probe=52345bce36) | Aug 19, 2020 |
| MSI           | B450-A PRO MAX              | [a8bb7acbbc](https://linux-hardware.org/?probe=a8bb7acbbc) | Aug 19, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [5c09a8571d](https://linux-hardware.org/?probe=5c09a8571d) | Aug 19, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [316ac04cd7](https://linux-hardware.org/?probe=316ac04cd7) | Aug 17, 2020 |
| ASRock        | Z170 Extreme7+              | [d254d96179](https://linux-hardware.org/?probe=d254d96179) | Aug 16, 2020 |
| MSI           | Z370-A PRO                  | [e37fd4a94f](https://linux-hardware.org/?probe=e37fd4a94f) | Aug 14, 2020 |
| MSI           | B350 PC MATE                | [0d1eb9465b](https://linux-hardware.org/?probe=0d1eb9465b) | Aug 12, 2020 |
| MSI           | B250M BAZOOKA               | [78bb05b2c6](https://linux-hardware.org/?probe=78bb05b2c6) | Aug 12, 2020 |
| ASRock        | A320M-HDV R4.0              | [a00f58a226](https://linux-hardware.org/?probe=a00f58a226) | Aug 11, 2020 |
| Gigabyte      | Z77-DS3H                    | [e238793adb](https://linux-hardware.org/?probe=e238793adb) | Aug 08, 2020 |
| Gigabyte      | Z87M-D3H                    | [69126c9388](https://linux-hardware.org/?probe=69126c9388) | Aug 08, 2020 |
| ASRock        | Z87 Pro3                    | [9fc26dbca3](https://linux-hardware.org/?probe=9fc26dbca3) | Aug 07, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [3e788a2bd9](https://linux-hardware.org/?probe=3e788a2bd9) | Aug 07, 2020 |
| ASRock        | Z87 Pro3                    | [fda49e84b2](https://linux-hardware.org/?probe=fda49e84b2) | Aug 06, 2020 |
| ASRock        | Z170 Extreme7+              | [8f00b6e4d5](https://linux-hardware.org/?probe=8f00b6e4d5) | Aug 05, 2020 |
| Gigabyte      | H97M-D3H                    | [2cd61abaf3](https://linux-hardware.org/?probe=2cd61abaf3) | Aug 05, 2020 |
| Gigabyte      | H97M-D3H                    | [35d7a6081d](https://linux-hardware.org/?probe=35d7a6081d) | Aug 05, 2020 |
| Intel         | E5 (INTEL Xeon E5/Core i... | [3917eb1849](https://linux-hardware.org/?probe=3917eb1849) | Aug 05, 2020 |
| ASUSTek       | PRIME Z390-P                | [66421b347c](https://linux-hardware.org/?probe=66421b347c) | Aug 03, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | [3e56d4fbe5](https://linux-hardware.org/?probe=3e56d4fbe5) | Aug 02, 2020 |
| Gigabyte      | P67X-UD3-B3                 | [2a8cccd919](https://linux-hardware.org/?probe=2a8cccd919) | Aug 02, 2020 |
| Gigabyte      | B450M DS3H-CF               | [0ecb4938d1](https://linux-hardware.org/?probe=0ecb4938d1) | Aug 02, 2020 |
| ASRock        | 775Dual-VSTA                | [a2ad60fd2b](https://linux-hardware.org/?probe=a2ad60fd2b) | Aug 01, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [747e731b16](https://linux-hardware.org/?probe=747e731b16) | Jul 30, 2020 |
| ASRock        | Z370 Gaming K6              | [d2b117ce8f](https://linux-hardware.org/?probe=d2b117ce8f) | Jul 29, 2020 |
| HP            | 1495                        | [8a51ce66a3](https://linux-hardware.org/?probe=8a51ce66a3) | Jul 27, 2020 |
| ASUSTek       | Z97-A                       | [94b11d033b](https://linux-hardware.org/?probe=94b11d033b) | Jul 26, 2020 |
| Gigabyte      | GA-78LMT-S2                 | [d5f013fb10](https://linux-hardware.org/?probe=d5f013fb10) | Jul 25, 2020 |
| Gigabyte      | H110M-S2V-CF                | [8fde64525d](https://linux-hardware.org/?probe=8fde64525d) | Jul 24, 2020 |
| ASUSTek       | PRIME X570-P                | [f8f7d2d073](https://linux-hardware.org/?probe=f8f7d2d073) | Jul 24, 2020 |
| Gigabyte      | H110M-S2V-CF                | [780c10c662](https://linux-hardware.org/?probe=780c10c662) | Jul 24, 2020 |
| Gigabyte      | X570 AORUS PRO              | [f6f1267e91](https://linux-hardware.org/?probe=f6f1267e91) | Jul 23, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | [746d3cea84](https://linux-hardware.org/?probe=746d3cea84) | Jul 23, 2020 |
| MSI           | H97 GUARD-PRO               | [ca29557f55](https://linux-hardware.org/?probe=ca29557f55) | Jul 23, 2020 |
| Huanan        | X79-ZD3 INTEL (INTEL Xeo... | [f1727aeef0](https://linux-hardware.org/?probe=f1727aeef0) | Jul 22, 2020 |
| ASUSTek       | M4N72-E                     | [d77d4e79eb](https://linux-hardware.org/?probe=d77d4e79eb) | Jul 22, 2020 |
| ASUSTek       | B85-PRO GAMER               | [f69af5d26f](https://linux-hardware.org/?probe=f69af5d26f) | Jul 21, 2020 |
| Gigabyte      | A320M-S2H-CF                | [6284319c25](https://linux-hardware.org/?probe=6284319c25) | Jul 20, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [3f740083f9](https://linux-hardware.org/?probe=3f740083f9) | Jul 19, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [f1c586d370](https://linux-hardware.org/?probe=f1c586d370) | Jul 19, 2020 |
| Gigabyte      | H97-Gaming 3                | [2298274454](https://linux-hardware.org/?probe=2298274454) | Jul 17, 2020 |
| Gigabyte      | H97-Gaming 3                | [2f5df8729a](https://linux-hardware.org/?probe=2f5df8729a) | Jul 17, 2020 |
| Dell          | 0XPDFK A01                  | [97e1cc5928](https://linux-hardware.org/?probe=97e1cc5928) | Jul 17, 2020 |
| Dell          | 00V62H A00                  | [34a7d1db11](https://linux-hardware.org/?probe=34a7d1db11) | Jul 17, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b3cf909105](https://linux-hardware.org/?probe=b3cf909105) | Jul 17, 2020 |
| ASUSTek       | AM1I-A                      | [9425979073](https://linux-hardware.org/?probe=9425979073) | Jul 14, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | [de4ad13bb4](https://linux-hardware.org/?probe=de4ad13bb4) | Jul 14, 2020 |
| ASRock        | H61M-VG4                    | [2f9520527b](https://linux-hardware.org/?probe=2f9520527b) | Jul 11, 2020 |
| ASRock        | H61M-VG4                    | [b36bc5f47e](https://linux-hardware.org/?probe=b36bc5f47e) | Jul 11, 2020 |
| ECS           | A790GXM-AD3                 | [dc63f56959](https://linux-hardware.org/?probe=dc63f56959) | Jul 10, 2020 |
| ECS           | A790GXM-AD3                 | [f692211349](https://linux-hardware.org/?probe=f692211349) | Jul 10, 2020 |
| MSI           | B450M PRO-M2 MAX            | [79aa82328a](https://linux-hardware.org/?probe=79aa82328a) | Jul 10, 2020 |
| HP            | 3646h                       | [717ed10c8e](https://linux-hardware.org/?probe=717ed10c8e) | Jul 09, 2020 |
| ASRock        | AM2NF3-VSTA                 | [3231309a17](https://linux-hardware.org/?probe=3231309a17) | Jul 09, 2020 |
| Dell          | 048DY8 A01                  | [fc9d7c9dbe](https://linux-hardware.org/?probe=fc9d7c9dbe) | Jul 09, 2020 |
| MSI           | G41M-P33 Combo              | [eb330d82bf](https://linux-hardware.org/?probe=eb330d82bf) | Jul 09, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | [9465d6fd4e](https://linux-hardware.org/?probe=9465d6fd4e) | Jul 09, 2020 |
| ASUSTek       | PRIME Z390-P                | [e70d8ca32d](https://linux-hardware.org/?probe=e70d8ca32d) | Jul 08, 2020 |
| Foxconn       | 2ABF                        | [910a91e8d2](https://linux-hardware.org/?probe=910a91e8d2) | Jul 07, 2020 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [e7446f8931](https://linux-hardware.org/?probe=e7446f8931) | Jul 06, 2020 |
| Acer          | Aspire MC605 v1.0           | [1ddf75d3b7](https://linux-hardware.org/?probe=1ddf75d3b7) | Jul 06, 2020 |
| HP            | 3646h                       | [e30378adda](https://linux-hardware.org/?probe=e30378adda) | Jul 01, 2020 |
| MSI           | G41M-P33 Combo              | [f4d356b23c](https://linux-hardware.org/?probe=f4d356b23c) | Jul 01, 2020 |
| MSI           | G41M-P33 Combo              | [aff1817a63](https://linux-hardware.org/?probe=aff1817a63) | Jul 01, 2020 |
| MSI           | H97 PC Mate                 | [f913833d11](https://linux-hardware.org/?probe=f913833d11) | Jun 30, 2020 |
| MSI           | G41M-P33 Combo              | [0ee105915b](https://linux-hardware.org/?probe=0ee105915b) | Jun 30, 2020 |
| HP            | 1495                        | [e653a7c634](https://linux-hardware.org/?probe=e653a7c634) | Jun 30, 2020 |
| Acer          | Aspire T3-715A              | [af6b734a68](https://linux-hardware.org/?probe=af6b734a68) | Jun 30, 2020 |
| Acer          | Aspire T3-715A              | [43d21108b1](https://linux-hardware.org/?probe=43d21108b1) | Jun 30, 2020 |
| MSI           | X370 SLI PLUS               | [3a3835d50f](https://linux-hardware.org/?probe=3a3835d50f) | Jun 30, 2020 |
| MSI           | B350 PC MATE                | [2d20d8d586](https://linux-hardware.org/?probe=2d20d8d586) | Jun 28, 2020 |
| MSI           | G41M-P33 Combo              | [ba89294f76](https://linux-hardware.org/?probe=ba89294f76) | Jun 27, 2020 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [345d74a8be](https://linux-hardware.org/?probe=345d74a8be) | Jun 26, 2020 |
| Gigabyte      | 970-GAMING                  | [e78780d56d](https://linux-hardware.org/?probe=e78780d56d) | Jun 24, 2020 |
| Gigabyte      | 970-GAMING                  | [f3886361af](https://linux-hardware.org/?probe=f3886361af) | Jun 24, 2020 |
| ASUSTek       | PRIME X470-PRO              | [5d95482dd3](https://linux-hardware.org/?probe=5d95482dd3) | Jun 24, 2020 |
| ASUSTek       | PRIME B450M-A               | [6533c926f7](https://linux-hardware.org/?probe=6533c926f7) | Jun 23, 2020 |
| Gigabyte      | B365M DS3H                  | [e5a5391106](https://linux-hardware.org/?probe=e5a5391106) | Jun 23, 2020 |
| ASRock        | AM2NF3-VSTA                 | [2a17598f66](https://linux-hardware.org/?probe=2a17598f66) | Jun 23, 2020 |
| ASUSTek       | PRIME X470-PRO              | [bec57f19ed](https://linux-hardware.org/?probe=bec57f19ed) | Jun 23, 2020 |
| ASUSTek       | PRIME X570-PRO              | [e578876ee9](https://linux-hardware.org/?probe=e578876ee9) | Jun 23, 2020 |
| ASRock        | AM2NF3-VSTA                 | [5ecf090d54](https://linux-hardware.org/?probe=5ecf090d54) | Jun 21, 2020 |
| MSI           | G41M-P33 Combo              | [bd024d4ce2](https://linux-hardware.org/?probe=bd024d4ce2) | Jun 20, 2020 |
| MSI           | G41M-P33 Combo              | [4569a83fa0](https://linux-hardware.org/?probe=4569a83fa0) | Jun 20, 2020 |
| Gigabyte      | X99-UD4-CF                  | [f2f35bedba](https://linux-hardware.org/?probe=f2f35bedba) | Jun 20, 2020 |
| Gigabyte      | B365M DS3H                  | [3c311dbb3d](https://linux-hardware.org/?probe=3c311dbb3d) | Jun 20, 2020 |
| ASRock        | B450M/ac                    | [9ef30975fb](https://linux-hardware.org/?probe=9ef30975fb) | Jun 19, 2020 |
| Lenovo        | MAHOBAY NOK                 | [0d8f915ebe](https://linux-hardware.org/?probe=0d8f915ebe) | Jun 18, 2020 |
| ASRock        | A320M-HDV R3.0              | [e33cafa4a6](https://linux-hardware.org/?probe=e33cafa4a6) | Jun 17, 2020 |
| Dell          | 048DY8 A01                  | [a01da8b9cb](https://linux-hardware.org/?probe=a01da8b9cb) | Jun 16, 2020 |
| Gigabyte      | X99-UD4-CF                  | [22ca9e31e5](https://linux-hardware.org/?probe=22ca9e31e5) | Jun 15, 2020 |
| Gigabyte      | B365M DS3H                  | [13f8a3088a](https://linux-hardware.org/?probe=13f8a3088a) | Jun 15, 2020 |
| MSI           | X370 SLI PLUS               | [796d817286](https://linux-hardware.org/?probe=796d817286) | Jun 14, 2020 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4b8ab04c19](https://linux-hardware.org/?probe=4b8ab04c19) | Jun 13, 2020 |
| MSI           | X399 GAMING PRO CARBON A... | [f14aaa2c68](https://linux-hardware.org/?probe=f14aaa2c68) | Jun 13, 2020 |
| HP            | 1495                        | [c9c1099add](https://linux-hardware.org/?probe=c9c1099add) | Jun 12, 2020 |
| ASUSTek       | X99-A                       | [9f73fa9aef](https://linux-hardware.org/?probe=9f73fa9aef) | Jun 12, 2020 |
| ASUSTek       | A88XM-E                     | [2bfa6a1ebb](https://linux-hardware.org/?probe=2bfa6a1ebb) | Jun 11, 2020 |
| HP            | 8591                        | [27ba8cf5b9](https://linux-hardware.org/?probe=27ba8cf5b9) | Jun 11, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [96ea0d1786](https://linux-hardware.org/?probe=96ea0d1786) | Jun 10, 2020 |
| Acer          | Aspire MC605 v1.0           | [351886a313](https://linux-hardware.org/?probe=351886a313) | Jun 10, 2020 |
| ZOTAC         | Cherry Trail FFD            | [18e726a7e2](https://linux-hardware.org/?probe=18e726a7e2) | Jun 10, 2020 |
| Gigabyte      | AX370-Gaming K3             | [c5e79c39f3](https://linux-hardware.org/?probe=c5e79c39f3) | Jun 10, 2020 |
| Dell          | 0C2XKD A00                  | [739ceaf54e](https://linux-hardware.org/?probe=739ceaf54e) | Jun 09, 2020 |
| Dell          | 088DT1 A01                  | [4cc00c0b24](https://linux-hardware.org/?probe=4cc00c0b24) | Jun 08, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [b03c6bffae](https://linux-hardware.org/?probe=b03c6bffae) | Jun 08, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [067e65da66](https://linux-hardware.org/?probe=067e65da66) | Jun 07, 2020 |
| ASUSTek       | A88XM-PLUS                  | [9c57c2c81d](https://linux-hardware.org/?probe=9c57c2c81d) | Jun 06, 2020 |
| ASUSTek       | A88XM-PLUS                  | [2a6d578647](https://linux-hardware.org/?probe=2a6d578647) | Jun 06, 2020 |
| Lenovo        | ThinkCentre M58p 7479AD4    | [67ffdf7c6b](https://linux-hardware.org/?probe=67ffdf7c6b) | Jun 03, 2020 |
| Lenovo        | ThinkCentre M58p 7479AD4    | [b061f7cdf0](https://linux-hardware.org/?probe=b061f7cdf0) | Jun 01, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [5c36dd075c](https://linux-hardware.org/?probe=5c36dd075c) | May 28, 2020 |
| HP            | 822A                        | [1e9ccee3cc](https://linux-hardware.org/?probe=1e9ccee3cc) | May 28, 2020 |
| ASUSTek       | P8B75-M                     | [ee88269196](https://linux-hardware.org/?probe=ee88269196) | May 28, 2020 |
| ASUSTek       | P8B75-M                     | [b03ff365bd](https://linux-hardware.org/?probe=b03ff365bd) | May 28, 2020 |
| Acer          | Aspire MC605 v1.0           | [7c514cba36](https://linux-hardware.org/?probe=7c514cba36) | May 26, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [5d99916419](https://linux-hardware.org/?probe=5d99916419) | May 26, 2020 |
| Acer          | Aspire MC605 v1.0           | [367c03176d](https://linux-hardware.org/?probe=367c03176d) | May 26, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [f9b28ed0fd](https://linux-hardware.org/?probe=f9b28ed0fd) | May 25, 2020 |
| Dell          | 0C27VV A01                  | [1192d26033](https://linux-hardware.org/?probe=1192d26033) | May 25, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [4570574009](https://linux-hardware.org/?probe=4570574009) | May 24, 2020 |
| Gigabyte      | G41MT-S2                    | [f8702707c6](https://linux-hardware.org/?probe=f8702707c6) | May 22, 2020 |
| HP            | 2B05                        | [18cf8082cf](https://linux-hardware.org/?probe=18cf8082cf) | May 21, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [aa40c0bbfe](https://linux-hardware.org/?probe=aa40c0bbfe) | May 20, 2020 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [a4f4b1886e](https://linux-hardware.org/?probe=a4f4b1886e) | May 20, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [52d692bb22](https://linux-hardware.org/?probe=52d692bb22) | May 18, 2020 |
| Gigabyte      | B450M S2H                   | [aae61a6dd0](https://linux-hardware.org/?probe=aae61a6dd0) | May 18, 2020 |
| ASUSTek       | Maximus III Formula         | [68098da61c](https://linux-hardware.org/?probe=68098da61c) | May 16, 2020 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [5a2fb87ad8](https://linux-hardware.org/?probe=5a2fb87ad8) | May 16, 2020 |
| HP            | 2B05                        | [3d400c1712](https://linux-hardware.org/?probe=3d400c1712) | May 16, 2020 |
| ASUSTek       | P5N-D                       | [b25cc2b7d0](https://linux-hardware.org/?probe=b25cc2b7d0) | May 15, 2020 |
| ASUSTek       | B75M-A                      | [c2166b0fd6](https://linux-hardware.org/?probe=c2166b0fd6) | May 14, 2020 |
| ASUSTek       | B75M-A                      | [1f7883ca50](https://linux-hardware.org/?probe=1f7883ca50) | May 14, 2020 |
| MSI           | H61MA-E35                   | [86a0188756](https://linux-hardware.org/?probe=86a0188756) | May 12, 2020 |
| HP            | 8593                        | [1e043f3437](https://linux-hardware.org/?probe=1e043f3437) | May 12, 2020 |
| ASUSTek       | PRIME Z390-A                | [293425d26e](https://linux-hardware.org/?probe=293425d26e) | May 12, 2020 |
| ASUSTek       | Z97-A-USB31                 | [33e83e91d6](https://linux-hardware.org/?probe=33e83e91d6) | May 11, 2020 |
| ASUSTek       | Z97-A-USB31                 | [a912cfd29f](https://linux-hardware.org/?probe=a912cfd29f) | May 11, 2020 |
| ASUSTek       | M5A78L LE                   | [bfd4db6986](https://linux-hardware.org/?probe=bfd4db6986) | May 09, 2020 |
| Dell          | 0HN7XN A00                  | [bf437b3d4d](https://linux-hardware.org/?probe=bf437b3d4d) | May 09, 2020 |
| Dell          | 0HN7XN A00                  | [0b20f22d3e](https://linux-hardware.org/?probe=0b20f22d3e) | May 09, 2020 |
| Acer          | Aspire XC600                | [037ab363ad](https://linux-hardware.org/?probe=037ab363ad) | May 07, 2020 |
| MSI           | H97 PC Mate                 | [25f66d5708](https://linux-hardware.org/?probe=25f66d5708) | May 06, 2020 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [683ea6779d](https://linux-hardware.org/?probe=683ea6779d) | May 05, 2020 |
| Dell          | 0PC5F7 A01                  | [541846e7d7](https://linux-hardware.org/?probe=541846e7d7) | May 01, 2020 |
| ASUSTek       | M5A78L LE                   | [c86ac0eb55](https://linux-hardware.org/?probe=c86ac0eb55) | Apr 28, 2020 |
| ASUSTek       | M5A78L LE                   | [451f27f05c](https://linux-hardware.org/?probe=451f27f05c) | Apr 25, 2020 |
| MSI           | H97 PC Mate                 | [2565308a86](https://linux-hardware.org/?probe=2565308a86) | Apr 24, 2020 |
| ASRock        | X370 Gaming X               | [ee40a22fd6](https://linux-hardware.org/?probe=ee40a22fd6) | Apr 23, 2020 |
| MSI           | Z97I GAMING AC              | [0ecedca18a](https://linux-hardware.org/?probe=0ecedca18a) | Apr 20, 2020 |
| MSI           | H61MA-E35                   | [2e35363058](https://linux-hardware.org/?probe=2e35363058) | Apr 18, 2020 |
| MSI           | Z97I GAMING AC              | [38c8205309](https://linux-hardware.org/?probe=38c8205309) | Apr 16, 2020 |
| ASUSTek       | Z87-PRO                     | [ff19591c79](https://linux-hardware.org/?probe=ff19591c79) | Apr 12, 2020 |
| MSI           | Z370-A PRO                  | [5709f429d1](https://linux-hardware.org/?probe=5709f429d1) | Apr 12, 2020 |
| ASRock        | H81 Pro BTC R2.0            | [ce2286218c](https://linux-hardware.org/?probe=ce2286218c) | Apr 01, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [18e07bee29](https://linux-hardware.org/?probe=18e07bee29) | Mar 26, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [6fc123427e](https://linux-hardware.org/?probe=6fc123427e) | Mar 21, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [ec5fdd7cf2](https://linux-hardware.org/?probe=ec5fdd7cf2) | Mar 21, 2020 |
| MSI           | H61MA-E35                   | [7a334444a5](https://linux-hardware.org/?probe=7a334444a5) | Mar 10, 2020 |
| ASRock        | H81 Pro BTC R2.0            | [9ad122a9b9](https://linux-hardware.org/?probe=9ad122a9b9) | Jan 16, 2020 |
| Gigabyte      | 970A-UD3P                   | [cfcec9bcbb](https://linux-hardware.org/?probe=cfcec9bcbb) | Dec 02, 2019 |
| Gigabyte      | 970A-UD3P                   | [75358150da](https://linux-hardware.org/?probe=75358150da) | Dec 02, 2019 |
| MSI           | H61MA-E35                   | [60dfc4f073](https://linux-hardware.org/?probe=60dfc4f073) | Nov 23, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu_20.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.0-42-generic  | 38       | 5.87%   |
| 5.4.0-52-generic  | 24       | 3.71%   |
| 5.4.0-58-generic  | 19       | 2.94%   |
| 5.4.0-48-generic  | 19       | 2.94%   |
| 5.4.0-40-generic  | 18       | 2.78%   |
| 5.4.0-65-generic  | 15       | 2.32%   |
| 5.4.0-37-generic  | 15       | 2.32%   |
| 5.4.0-47-generic  | 14       | 2.16%   |
| 5.4.0-54-generic  | 13       | 2.01%   |
| 5.4.0-45-generic  | 13       | 2.01%   |
| 5.8.0-50-generic  | 11       | 1.7%    |
| 5.8.0-48-generic  | 11       | 1.7%    |
| 5.4.0-29-generic  | 11       | 1.7%    |
| 5.11.0-37-generic | 10       | 1.55%   |
| 5.8.0-45-generic  | 9        | 1.39%   |
| 5.4.0-74-generic  | 9        | 1.39%   |
| 5.13.0-28-generic | 9        | 1.39%   |
| 5.11.0-43-generic | 9        | 1.39%   |
| 5.8.0-53-generic  | 8        | 1.24%   |
| 5.8.0-43-generic  | 8        | 1.24%   |
| 5.4.0-70-generic  | 8        | 1.24%   |
| 5.4.0-26-generic  | 8        | 1.24%   |
| 5.8.0-63-generic  | 7        | 1.08%   |
| 5.8.0-55-generic  | 7        | 1.08%   |
| 5.4.0-91-generic  | 7        | 1.08%   |
| 5.4.0-73-generic  | 7        | 1.08%   |
| 5.4.0-66-generic  | 7        | 1.08%   |
| 5.4.0-56-generic  | 7        | 1.08%   |
| 5.4.0-39-generic  | 7        | 1.08%   |
| 5.4.0-33-generic  | 7        | 1.08%   |
| 5.13.0-39-generic | 7        | 1.08%   |
| 5.11.0-27-generic | 7        | 1.08%   |
| 5.4.0-99-generic  | 6        | 0.93%   |
| 5.4.0-81-generic  | 6        | 0.93%   |
| 5.4.0-60-generic  | 6        | 0.93%   |
| 5.4.0-31-generic  | 6        | 0.93%   |
| 5.11.0-34-generic | 6        | 0.93%   |
| 5.11.0-25-generic | 6        | 0.93%   |
| 5.4.0-80-generic  | 5        | 0.77%   |
| 5.4.0-77-generic  | 5        | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 360      | 61.54%  |
| 5.8.0   | 72       | 12.31%  |
| 5.11.0  | 51       | 8.72%   |
| 5.13.0  | 38       | 6.5%    |
| 5.15.0  | 23       | 3.93%   |
| 5.6.0   | 7        | 1.2%    |
| 5.10.0  | 3        | 0.51%   |
| 5.9.0   | 2        | 0.34%   |
| 5.8.18  | 2        | 0.34%   |
| 5.7.10  | 2        | 0.34%   |
| 5.3.0   | 2        | 0.34%   |
| 5.9.6   | 1        | 0.17%   |
| 5.9.16  | 1        | 0.17%   |
| 5.8.5   | 1        | 0.17%   |
| 5.8.2   | 1        | 0.17%   |
| 5.8.12  | 1        | 0.17%   |
| 5.8.1   | 1        | 0.17%   |
| 5.7.6   | 1        | 0.17%   |
| 5.7.15  | 1        | 0.17%   |
| 5.7.1   | 1        | 0.17%   |
| 5.6.7   | 1        | 0.17%   |
| 5.6.15  | 1        | 0.17%   |
| 5.6.11  | 1        | 0.17%   |
| 5.4.78  | 1        | 0.17%   |
| 5.4.72  | 1        | 0.17%   |
| 5.4.42  | 1        | 0.17%   |
| 5.18.11 | 1        | 0.17%   |
| 5.16.0  | 1        | 0.17%   |
| 5.15.49 | 1        | 0.17%   |
| 5.14.10 | 1        | 0.17%   |
| 5.12.7  | 1        | 0.17%   |
| 5.12.6  | 1        | 0.17%   |
| 5.11.15 | 1        | 0.17%   |
| 5.10.26 | 1        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 362      | 61.99%  |
| 5.8     | 78       | 13.36%  |
| 5.11    | 52       | 8.9%    |
| 5.13    | 38       | 6.51%   |
| 5.15    | 24       | 4.11%   |
| 5.6     | 10       | 1.71%   |
| 5.7     | 5        | 0.86%   |
| 5.9     | 4        | 0.68%   |
| 5.10    | 4        | 0.68%   |
| 5.3     | 2        | 0.34%   |
| 5.12    | 2        | 0.34%   |
| 5.18    | 1        | 0.17%   |
| 5.16    | 1        | 0.17%   |
| 5.14    | 1        | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 571      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 360      | 62.5%   |
| KDE      | 202      | 35.07%  |
| GNOME    | 5        | 0.87%   |
| Cinnamon | 3        | 0.52%   |
| Budgie   | 3        | 0.52%   |
| XFCE     | 2        | 0.35%   |
| MATE     | 1        | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 554      | 97.02%  |
| Tty     | 11       | 1.93%   |
| Wayland | 6        | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 322      | 56%     |
| Unknown | 206      | 35.83%  |
| GDM     | 28       | 4.87%   |
| LightDM | 9        | 1.57%   |
| TDM     | 5        | 0.87%   |
| GDM3    | 4        | 0.7%    |
| SLiM    | 1        | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 240      | 41.81%  |
| de_DE   | 51       | 8.89%   |
| ru_RU   | 38       | 6.62%   |
| en_GB   | 35       | 6.1%    |
| fr_FR   | 31       | 5.4%    |
| pt_BR   | 26       | 4.53%   |
| it_IT   | 20       | 3.48%   |
| pl_PL   | 12       | 2.09%   |
| es_ES   | 11       | 1.92%   |
| en_CA   | 10       | 1.74%   |
| en_AU   | 9        | 1.57%   |
| es_AR   | 7        | 1.22%   |
| ru_UA   | 5        | 0.87%   |
| el_GR   | 5        | 0.87%   |
| cs_CZ   | 5        | 0.87%   |
| uk_UA   | 4        | 0.7%    |
| nl_NL   | 4        | 0.7%    |
| en_ZA   | 4        | 0.7%    |
| zh_TW   | 3        | 0.52%   |
| hu_HU   | 3        | 0.52%   |
| en_NZ   | 3        | 0.52%   |
| en_IN   | 3        | 0.52%   |
| en_IL   | 3        | 0.52%   |
| C       | 3        | 0.52%   |
| sl_SI   | 2        | 0.35%   |
| nl_BE   | 2        | 0.35%   |
| ja_JP   | 2        | 0.35%   |
| fi_FI   | 2        | 0.35%   |
| es_VE   | 2        | 0.35%   |
| es_PE   | 2        | 0.35%   |
| es_MX   | 2        | 0.35%   |
| es_CO   | 2        | 0.35%   |
| en_DK   | 2        | 0.35%   |
| en_DE   | 2        | 0.35%   |
| de_AT   | 2        | 0.35%   |
| Unknown | 2        | 0.35%   |
| zh_CN   | 1        | 0.17%   |
| tr_TR   | 1        | 0.17%   |
| sv_SE   | 1        | 0.17%   |
| sk_SK   | 1        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 296      | 51.39%  |
| BIOS | 280      | 48.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 516      | 90.05%  |
| Btrfs   | 30       | 5.24%   |
| Xfs     | 12       | 2.09%   |
| Overlay | 9        | 1.57%   |
| Zfs     | 2        | 0.35%   |
| XXXX    | 1        | 0.17%   |
| Jfs     | 1        | 0.17%   |
| Ext3    | 1        | 0.17%   |
| Ext2    | 1        | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 249      | 43.23%  |
| Unknown | 238      | 41.32%  |
| MBR     | 89       | 15.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 456      | 78.62%  |
| Yes       | 124      | 21.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 321      | 55.83%  |
| Yes       | 254      | 44.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 140      | 24.52%  |
| Gigabyte Technology | 122      | 21.37%  |
| MSI                 | 84       | 14.71%  |
| ASRock              | 61       | 10.68%  |
| Dell                | 42       | 7.36%   |
| Hewlett-Packard     | 39       | 6.83%   |
| Lenovo              | 17       | 2.98%   |
| Intel               | 11       | 1.93%   |
| Acer                | 8        | 1.4%    |
| Pegatron            | 7        | 1.23%   |
| Fujitsu             | 5        | 0.88%   |
| Foxconn             | 5        | 0.88%   |
| Biostar             | 5        | 0.88%   |
| Huanan              | 4        | 0.7%    |
| ECS                 | 4        | 0.7%    |
| ZOTAC               | 2        | 0.35%   |
| Packard Bell        | 2        | 0.35%   |
| Unknown             | 2        | 0.35%   |
| WeiBu               | 1        | 0.18%   |
| SYWZ                | 1        | 0.18%   |
| Supermicro          | 1        | 0.18%   |
| Seco                | 1        | 0.18%   |
| Medion              | 1        | 0.18%   |
| Koloe               | 1        | 0.18%   |
| JINGSHA             | 1        | 0.18%   |
| Gateway             | 1        | 0.18%   |
| AZW                 | 1        | 0.18%   |
| Apple               | 1        | 0.18%   |
| Alienware           | 1        | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 16       | 2.8%    |
| Gigabyte 970A-DS3P                 | 6        | 1.05%   |
| Gigabyte A320M-S2H                 | 5        | 0.88%   |
| MSI MS-7A34                        | 4        | 0.7%    |
| MSI MS-7817                        | 4        | 0.7%    |
| Gigabyte B450M DS3H                | 4        | 0.7%    |
| Dell OptiPlex 9020                 | 4        | 0.7%    |
| ASUS PRIME B450M-A                 | 4        | 0.7%    |
| Unknown                            | 4        | 0.7%    |
| MSI MS-7C91                        | 3        | 0.53%   |
| MSI MS-7C52                        | 3        | 0.53%   |
| MSI MS-7C37                        | 3        | 0.53%   |
| MSI MS-7996                        | 3        | 0.53%   |
| Gigabyte X570 AORUS ELITE          | 3        | 0.53%   |
| Gigabyte B550 AORUS ELITE          | 3        | 0.53%   |
| Gigabyte A320M-H                   | 3        | 0.53%   |
| Dell OptiPlex 780                  | 3        | 0.53%   |
| Dell OptiPlex 7010                 | 3        | 0.53%   |
| ASUS Z170 PRO GAMING               | 3        | 0.53%   |
| ASUS TUF Gaming X570-PLUS          | 3        | 0.53%   |
| ASUS TUF B450M-PLUS GAMING         | 3        | 0.53%   |
| ASUS ROG STRIX B550-F GAMING       | 3        | 0.53%   |
| ASUS PRIME X570-P                  | 3        | 0.53%   |
| ASUS PRIME B350-PLUS               | 3        | 0.53%   |
| Pegatron ECOQUIET 630A             | 2        | 0.35%   |
| MSI MS-7C94                        | 2        | 0.35%   |
| MSI MS-7C35                        | 2        | 0.35%   |
| MSI MS-7B93                        | 2        | 0.35%   |
| MSI MS-7B48                        | 2        | 0.35%   |
| MSI MS-7B17                        | 2        | 0.35%   |
| MSI MS-7B09                        | 2        | 0.35%   |
| MSI MS-7A59                        | 2        | 0.35%   |
| MSI MS-7A33                        | 2        | 0.35%   |
| MSI MS-7850                        | 2        | 0.35%   |
| MSI MS-7758                        | 2        | 0.35%   |
| MSI MS-7693                        | 2        | 0.35%   |
| MSI MS-7612                        | 2        | 0.35%   |
| HP Z440 Workstation                | 2        | 0.35%   |
| HP Z420 Workstation                | 2        | 0.35%   |
| HP Compaq dc7900 Small Form Factor | 2        | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 29       | 5.08%   |
| Dell OptiPlex          | 21       | 3.68%   |
| ASUS ROG               | 20       | 3.5%    |
| ASUS All               | 16       | 2.8%    |
| ASUS TUF               | 14       | 2.45%   |
| Lenovo ThinkCentre     | 13       | 2.28%   |
| HP Compaq              | 12       | 2.1%    |
| Dell Precision         | 9        | 1.58%   |
| Gigabyte X570          | 8        | 1.4%    |
| Acer Aspire            | 8        | 1.4%    |
| Gigabyte B450M         | 6        | 1.05%   |
| Gigabyte A320M-S2H     | 6        | 1.05%   |
| Gigabyte 970A-DS3P     | 6        | 1.05%   |
| Gigabyte B550          | 5        | 0.88%   |
| Dell Inspiron          | 5        | 0.88%   |
| ASUS SABERTOOTH        | 5        | 0.88%   |
| MSI MS-7A34            | 4        | 0.7%    |
| MSI MS-7817            | 4        | 0.7%    |
| HP EliteDesk           | 4        | 0.7%    |
| Fujitsu ESPRIMO        | 4        | 0.7%    |
| ASUS Z170              | 4        | 0.7%    |
| ASRock AB350           | 4        | 0.7%    |
| Unknown                | 4        | 0.7%    |
| MSI MS-7C91            | 3        | 0.53%   |
| MSI MS-7C52            | 3        | 0.53%   |
| MSI MS-7C37            | 3        | 0.53%   |
| MSI MS-7996            | 3        | 0.53%   |
| HP ProDesk             | 3        | 0.53%   |
| Gigabyte GA-78LMT-USB3 | 3        | 0.53%   |
| Gigabyte B450          | 3        | 0.53%   |
| Gigabyte AX370-Gaming  | 3        | 0.53%   |
| Gigabyte A320M-H       | 3        | 0.53%   |
| ASUS P8Z77-V           | 3        | 0.53%   |
| ASUS Maximus           | 3        | 0.53%   |
| ASRock Z170            | 3        | 0.53%   |
| ASRock B450            | 3        | 0.53%   |
| Pegatron Elite         | 2        | 0.35%   |
| Pegatron ECOQUIET      | 2        | 0.35%   |
| MSI MS-7C94            | 2        | 0.35%   |
| MSI MS-7C35            | 2        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 82       | 14.36%  |
| 2013    | 61       | 10.68%  |
| 2019    | 57       | 9.98%   |
| 2017    | 49       | 8.58%   |
| 2012    | 48       | 8.41%   |
| 2020    | 46       | 8.06%   |
| 2011    | 39       | 6.83%   |
| 2015    | 36       | 6.3%    |
| 2014    | 34       | 5.95%   |
| 2010    | 28       | 4.9%    |
| 2016    | 27       | 4.73%   |
| 2009    | 24       | 4.2%    |
| 2008    | 17       | 2.98%   |
| 2021    | 10       | 1.75%   |
| 2007    | 8        | 1.4%    |
| 2006    | 2        | 0.35%   |
| 2005    | 2        | 0.35%   |
| Unknown | 1        | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 571      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 559      | 97.9%   |
| Enabled  | 12       | 2.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 570      | 99.82%  |
| Yes  | 1        | 0.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 182      | 31.49%  |
| 32.01-64.0  | 119      | 20.59%  |
| 8.01-16.0   | 101      | 17.47%  |
| 4.01-8.0    | 80       | 13.84%  |
| 3.01-4.0    | 49       | 8.48%   |
| 64.01-256.0 | 24       | 4.15%   |
| 24.01-32.0  | 18       | 3.11%   |
| 1.01-2.0    | 4        | 0.69%   |
| 2.01-3.0    | 1        | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 164      | 26.67%  |
| 1.01-2.0   | 140      | 22.76%  |
| 2.01-3.0   | 137      | 22.28%  |
| 3.01-4.0   | 98       | 15.93%  |
| 8.01-16.0  | 48       | 7.8%    |
| 0.51-1.0   | 14       | 2.28%   |
| 16.01-24.0 | 7        | 1.14%   |
| 24.01-32.0 | 4        | 0.65%   |
| 0.01-0.5   | 3        | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 173      | 29.03%  |
| 1      | 160      | 26.85%  |
| 3      | 122      | 20.47%  |
| 4      | 71       | 11.91%  |
| 5      | 36       | 6.04%   |
| 6      | 18       | 3.02%   |
| 7      | 9        | 1.51%   |
| 8      | 3        | 0.5%    |
| 9      | 2        | 0.34%   |
| 11     | 1        | 0.17%   |
| 10     | 1        | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 313      | 54.34%  |
| Yes       | 263      | 45.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 567      | 99.3%   |
| No        | 4        | 0.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 358      | 62.15%  |
| Yes       | 218      | 37.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 374      | 65.27%  |
| Yes       | 199      | 34.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 122      | 21.29%  |
| Germany      | 64       | 11.17%  |
| Russia       | 51       | 8.9%    |
| France       | 36       | 6.28%   |
| Brazil       | 36       | 6.28%   |
| UK           | 28       | 4.89%   |
| Italy        | 26       | 4.54%   |
| Netherlands  | 17       | 2.97%   |
| Poland       | 16       | 2.79%   |
| Ukraine      | 15       | 2.62%   |
| Spain        | 15       | 2.62%   |
| Canada       | 12       | 2.09%   |
| Argentina    | 11       | 1.92%   |
| Australia    | 8        | 1.4%    |
| Greece       | 7        | 1.22%   |
| Hungary      | 6        | 1.05%   |
| Finland      | 5        | 0.87%   |
| Czechia      | 5        | 0.87%   |
| Belgium      | 5        | 0.87%   |
| South Africa | 4        | 0.7%    |
| Serbia       | 4        | 0.7%    |
| Israel       | 4        | 0.7%    |
| India        | 4        | 0.7%    |
| Estonia      | 4        | 0.7%    |
| Austria      | 4        | 0.7%    |
| Taiwan       | 3        | 0.52%   |
| Switzerland  | 3        | 0.52%   |
| Sweden       | 3        | 0.52%   |
| Romania      | 3        | 0.52%   |
| Peru         | 3        | 0.52%   |
| Norway       | 3        | 0.52%   |
| New Zealand  | 3        | 0.52%   |
| Mexico       | 3        | 0.52%   |
| Japan        | 3        | 0.52%   |
| Colombia     | 3        | 0.52%   |
| Chile        | 3        | 0.52%   |
| Bulgaria     | 3        | 0.52%   |
| Belarus      | 3        | 0.52%   |
| Venezuela    | 2        | 0.35%   |
| Turkey       | 2        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Paris             | 10       | 1.71%   |
| Moscow            | 10       | 1.71%   |
| Berlin            | 8        | 1.37%   |
| St Petersburg     | 7        | 1.19%   |
| Sao Paulo         | 7        | 1.19%   |
| Warsaw            | 6        | 1.02%   |
| Rome              | 6        | 1.02%   |
| Kyiv              | 6        | 1.02%   |
| Novosibirsk       | 5        | 0.85%   |
| Munich            | 4        | 0.68%   |
| London            | 4        | 0.68%   |
| Hamburg           | 4        | 0.68%   |
| Frankfurt am Main | 4        | 0.68%   |
| Tartu             | 3        | 0.51%   |
| Sydney            | 3        | 0.51%   |
| Seattle           | 3        | 0.51%   |
| Sao Carlos        | 3        | 0.51%   |
| Oryol             | 3        | 0.51%   |
| Melbourne         | 3        | 0.51%   |
| Manchester        | 3        | 0.51%   |
| Liverpool         | 3        | 0.51%   |
| Irkutsk           | 3        | 0.51%   |
| Chicago           | 3        | 0.51%   |
| Bologna           | 3        | 0.51%   |
| Belgrade          | 3        | 0.51%   |
| Auckland          | 3        | 0.51%   |
| Athens            | 3        | 0.51%   |
| Amsterdam         | 3        | 0.51%   |
| Zurich            | 2        | 0.34%   |
| Valencia          | 2        | 0.34%   |
| Thessaloniki      | 2        | 0.34%   |
| Strongsville      | 2        | 0.34%   |
| St Louis          | 2        | 0.34%   |
| Santo André      | 2        | 0.34%   |
| San Diego         | 2        | 0.34%   |
| Ryazan            | 2        | 0.34%   |
| Rio de Janeiro    | 2        | 0.34%   |
| Pretoria          | 2        | 0.34%   |
| Ponchatoula       | 2        | 0.34%   |
| Plano             | 2        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 224      | 408    | 19.24%  |
| Seagate               | 214      | 320    | 18.38%  |
| Samsung Electronics   | 194      | 311    | 16.67%  |
| Kingston              | 73       | 92     | 6.27%   |
| Toshiba               | 60       | 90     | 5.15%   |
| Crucial               | 56       | 67     | 4.81%   |
| SanDisk               | 47       | 53     | 4.04%   |
| Hitachi               | 44       | 54     | 3.78%   |
| Intel                 | 18       | 28     | 1.55%   |
| A-DATA Technology     | 17       | 17     | 1.46%   |
| Unknown               | 16       | 22     | 1.37%   |
| HGST                  | 16       | 16     | 1.37%   |
| Phison                | 13       | 18     | 1.12%   |
| OCZ                   | 12       | 14     | 1.03%   |
| Micron Technology     | 10       | 12     | 0.86%   |
| Corsair               | 9        | 18     | 0.77%   |
| Silicon Motion        | 8        | 8      | 0.69%   |
| Patriot               | 8        | 10     | 0.69%   |
| Maxtor                | 8        | 8      | 0.69%   |
| Intenso               | 7        | 7      | 0.6%    |
| XPG                   | 6        | 6      | 0.52%   |
| PNY                   | 6        | 6      | 0.52%   |
| GOODRAM               | 6        | 16     | 0.52%   |
| China                 | 6        | 7      | 0.52%   |
| Team                  | 5        | 5      | 0.43%   |
| Transcend             | 4        | 4      | 0.34%   |
| SPCC                  | 4        | 6      | 0.34%   |
| LDLC                  | 4        | 12     | 0.34%   |
| KingSpec              | 4        | 4      | 0.34%   |
| Gigabyte Technology   | 4        | 4      | 0.34%   |
| SK hynix              | 3        | 3      | 0.26%   |
| SABRENT               | 3        | 3      | 0.26%   |
| Mushkin               | 3        | 3      | 0.26%   |
| JMicron Technology    | 3        | 3      | 0.26%   |
| Apacer                | 3        | 3      | 0.26%   |
| Verbatim              | 2        | 2      | 0.17%   |
| VENO                  | 2        | 4      | 0.17%   |
| Realtek Semiconductor | 2        | 2      | 0.17%   |
| MDT                   | 2        | 4      | 0.17%   |
| LITEON                | 2        | 3      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB          | 18       | 1.29%   |
| Samsung SSD 850 EVO 250GB          | 16       | 1.15%   |
| Seagate ST1000DM003-1ER162 1TB     | 14       | 1%      |
| Kingston SA400S37480G 480GB SSD    | 14       | 1%      |
| Seagate ST1000DM010-2EP102 1TB     | 12       | 0.86%   |
| Seagate ST1000DM003-1CH162 1TB     | 12       | 0.86%   |
| Samsung SSD 860 EVO 1TB            | 11       | 0.79%   |
| Samsung SSD 850 EVO 500GB          | 11       | 0.79%   |
| Toshiba HDWD110 1TB                | 10       | 0.72%   |
| Seagate ST500DM002-1BD142 500GB    | 10       | 0.72%   |
| Seagate ST2000DM001-1ER164 2TB     | 10       | 0.72%   |
| Kingston SA400S37240G 240GB SSD    | 10       | 0.72%   |
| WDC WD20EARX-00PASB0 2TB           | 9        | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB           | 9        | 0.65%   |
| Toshiba DT01ACA100 1TB             | 9        | 0.65%   |
| SanDisk SSD PLUS 480GB             | 9        | 0.65%   |
| Samsung SSD 970 EVO Plus 1TB       | 9        | 0.65%   |
| Crucial CT1000MX500SSD1 1TB        | 9        | 0.65%   |
| Toshiba DT01ACA200 2TB             | 8        | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB     | 8        | 0.57%   |
| Samsung NVMe SSD Drive 500GB       | 8        | 0.57%   |
| Samsung NVMe SSD Drive 1TB         | 8        | 0.57%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 7        | 0.5%    |
| WDC WD1003FZEX-00K3CA0 1TB         | 7        | 0.5%    |
| Seagate ST4000DM004-2CV104 4TB     | 7        | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB     | 7        | 0.5%    |
| Seagate ST2000DM006-2DM164 2TB     | 7        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 7        | 0.5%    |
| Kingston SA2000M81000G 1TB         | 7        | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 6        | 0.43%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 6        | 0.43%   |
| Seagate ST3500413AS 500GB          | 6        | 0.43%   |
| Seagate ST2000DM001-1CH164 2TB     | 6        | 0.43%   |
| Seagate Expansion 4TB              | 6        | 0.43%   |
| Samsung SSD 970 EVO 1TB            | 6        | 0.43%   |
| Samsung SSD 860 EVO 250GB          | 6        | 0.43%   |
| Kingston SV300S37A240G 240GB SSD   | 6        | 0.43%   |
| Hitachi HDS721010CLA332 1TB        | 6        | 0.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 5        | 0.36%   |
| Toshiba DT01ACA050 500GB           | 5        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 211      | 316    | 36.07%  |
| WDC                 | 200      | 368    | 34.19%  |
| Toshiba             | 53       | 81     | 9.06%   |
| Hitachi             | 44       | 54     | 7.52%   |
| Samsung Electronics | 40       | 65     | 6.84%   |
| HGST                | 16       | 16     | 2.74%   |
| Maxtor              | 8        | 8      | 1.37%   |
| Unknown             | 7        | 7      | 1.2%    |
| WD MediaMax         | 1        | 1      | 0.17%   |
| USB                 | 1        | 1      | 0.17%   |
| Magnetic Data       | 1        | 2      | 0.17%   |
| LaCie               | 1        | 1      | 0.17%   |
| Hewlett-Packard     | 1        | 2      | 0.17%   |
| ASMT                | 1        | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 113      | 148    | 26.97%  |
| Kingston            | 62       | 78     | 14.8%   |
| Crucial             | 46       | 56     | 10.98%  |
| SanDisk             | 36       | 41     | 8.59%   |
| WDC                 | 24       | 26     | 5.73%   |
| A-DATA Technology   | 13       | 13     | 3.1%    |
| OCZ                 | 12       | 14     | 2.86%   |
| Intel               | 10       | 16     | 2.39%   |
| Patriot             | 8        | 10     | 1.91%   |
| Micron Technology   | 7        | 8      | 1.67%   |
| Intenso             | 7        | 7      | 1.67%   |
| Corsair             | 7        | 16     | 1.67%   |
| Toshiba             | 6        | 7      | 1.43%   |
| GOODRAM             | 6        | 16     | 1.43%   |
| China               | 6        | 7      | 1.43%   |
| Team                | 5        | 5      | 1.19%   |
| SPCC                | 4        | 5      | 0.95%   |
| PNY                 | 4        | 4      | 0.95%   |
| KingSpec            | 4        | 4      | 0.95%   |
| Transcend           | 3        | 3      | 0.72%   |
| Mushkin             | 3        | 3      | 0.72%   |
| Apacer              | 3        | 3      | 0.72%   |
| Verbatim            | 2        | 2      | 0.48%   |
| VENO                | 2        | 4      | 0.48%   |
| LITEON              | 2        | 3      | 0.48%   |
| Leven               | 2        | 3      | 0.48%   |
| LDLC                | 2        | 2      | 0.48%   |
| JMicron Technology  | 2        | 2      | 0.48%   |
| Gigabyte Technology | 2        | 2      | 0.48%   |
| Unknown             | 1        | 1      | 0.24%   |
| TCSUNBOW            | 1        | 1      | 0.24%   |
| Super Talent        | 1        | 1      | 0.24%   |
| Smartbuy            | 1        | 2      | 0.24%   |
| Seagate             | 1        | 1      | 0.24%   |
| PNY USB             | 1        | 1      | 0.24%   |
| Plextor             | 1        | 2      | 0.24%   |
| Netac               | 1        | 1      | 0.24%   |
| LITEONIT            | 1        | 1      | 0.24%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.24%   |
| Hewlett-Packard     | 1        | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 423      | 923    | 44.53%  |
| SSD     | 341      | 527    | 35.89%  |
| NVMe    | 162      | 226    | 17.05%  |
| Unknown | 21       | 38     | 2.21%   |
| MMC     | 3        | 5      | 0.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 528      | 1429   | 71.16%  |
| NVMe | 161      | 223    | 21.7%   |
| SAS  | 50       | 62     | 6.74%   |
| MMC  | 3        | 5      | 0.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 373      | 646    | 42.48%  |
| 0.51-1.0   | 262      | 421    | 29.84%  |
| 1.01-2.0   | 122      | 205    | 13.9%   |
| 3.01-4.0   | 56       | 88     | 6.38%   |
| 2.01-3.0   | 33       | 42     | 3.76%   |
| 4.01-10.0  | 28       | 42     | 3.19%   |
| 10.01-20.0 | 4        | 6      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 113      | 19.19%  |
| 251-500        | 107      | 18.17%  |
| 501-1000       | 104      | 17.66%  |
| 101-250        | 97       | 16.47%  |
| 1001-2000      | 81       | 13.75%  |
| 2001-3000      | 44       | 7.47%   |
| 51-100         | 19       | 3.23%   |
| 1-20           | 11       | 1.87%   |
| 21-50          | 8        | 1.36%   |
| Unknown        | 5        | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 101      | 16.83%  |
| 101-250        | 92       | 15.33%  |
| 51-100         | 73       | 12.17%  |
| 501-1000       | 72       | 12%     |
| 251-500        | 63       | 10.5%   |
| 21-50          | 61       | 10.17%  |
| More than 3000 | 58       | 9.67%   |
| 1001-2000      | 51       | 8.5%    |
| 2001-3000      | 24       | 4%      |
| Unknown        | 5        | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| Seagate ST1000DM003-1CH162 1TB       | 3        | 4      | 3.03%   |
| WDC WD5000AAKS-00V1A0 500GB          | 2        | 3      | 2.02%   |
| WDC WD5000AAKS-00A7B0 500GB          | 2        | 2      | 2.02%   |
| WDC WD30EZRX-00MMMB0 3TB             | 2        | 2      | 2.02%   |
| Seagate ST31000528AS 1TB             | 2        | 2      | 2.02%   |
| SanDisk SSD PLUS 240 GB              | 2        | 2      | 2.02%   |
| Intel SSDSA2M080G2GC 80GB            | 2        | 2      | 2.02%   |
| Crucial CT275MX300SSD1 275GB         | 2        | 3      | 2.02%   |
| WDC WD5000AAKS-00UU3A0 500GB         | 1        | 2      | 1.01%   |
| WDC WD5000AADS-56S9B1 500GB          | 1        | 1      | 1.01%   |
| WDC WD40EZRZ-00GXCB0 4TB             | 1        | 1      | 1.01%   |
| WDC WD40EZRX-00SPEB0 4TB             | 1        | 1      | 1.01%   |
| WDC WD40EFRX-68N32N0 4TB             | 1        | 2      | 1.01%   |
| WDC WD4003FZEX-00Z4SA0 4TB           | 1        | 2      | 1.01%   |
| WDC WD3200AAKX-001CA0 320GB          | 1        | 1      | 1.01%   |
| WDC WD30EZRX-00DC0B0 3TB             | 1        | 1      | 1.01%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 1      | 1.01%   |
| WDC WD2500AAJS-00B4A0 250GB          | 1        | 1      | 1.01%   |
| WDC WD20EARX-00PASB0 2TB             | 1        | 1      | 1.01%   |
| WDC WD1600AAJS-22L7A0 160GB          | 1        | 1      | 1.01%   |
| WDC WD15EARS-00Z5B1 1TB              | 1        | 1      | 1.01%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1        | 1      | 1.01%   |
| WDC WD10EZEX-75M2NA0 1TB             | 1        | 1      | 1.01%   |
| WDC WD10EZEX-60WN4A1 1TB             | 1        | 1      | 1.01%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1        | 1      | 1.01%   |
| WDC WD10EZEX-21WN4A0 1TB             | 1        | 1      | 1.01%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 1      | 1.01%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 1      | 1.01%   |
| WDC WD10EARS-22Y5B1 1TB              | 1        | 1      | 1.01%   |
| WDC WD10EARS-00Y5B1 1TB              | 1        | 1      | 1.01%   |
| WDC WD10EARS-00MVWB0 1TB             | 1        | 3      | 1.01%   |
| WDC WD10EADS-00M2B0 1TB              | 1        | 1      | 1.01%   |
| WDC WD1003FZEX-00K3CA0 1TB           | 1        | 1      | 1.01%   |
| WDC WD1002FBYS-02A6B0 1TB            | 1        | 1      | 1.01%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 1        | 1      | 1.01%   |
| WDC WD1001FALS-00U9B0 1TB            | 1        | 1      | 1.01%   |
| WDC WD1001FALS-00J7B1 1TB            | 1        | 1      | 1.01%   |
| VENO SCORP SSD 240GB                 | 1        | 1      | 1.01%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD | 1        | 1      | 1.01%   |
| Toshiba HDWE150 5TB                  | 1        | 2      | 1.01%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 35       | 41     | 35.71%  |
| Seagate             | 18       | 22     | 18.37%  |
| Samsung Electronics | 12       | 13     | 12.24%  |
| Toshiba             | 6        | 7      | 6.12%   |
| Hitachi             | 6        | 6      | 6.12%   |
| Intel               | 5        | 5      | 5.1%    |
| SanDisk             | 4        | 4      | 4.08%   |
| Crucial             | 4        | 6      | 4.08%   |
| OCZ                 | 2        | 2      | 2.04%   |
| Kingston            | 2        | 2      | 2.04%   |
| VENO                | 1        | 1      | 1.02%   |
| SPCC                | 1        | 1      | 1.02%   |
| Micron Technology   | 1        | 1      | 1.02%   |
| A-DATA Technology   | 1        | 1      | 1.02%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 35       | 41     | 47.95%  |
| Seagate             | 18       | 22     | 24.66%  |
| Samsung Electronics | 9        | 10     | 12.33%  |
| Hitachi             | 6        | 6      | 8.22%   |
| Toshiba             | 5        | 6      | 6.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 66       | 85     | 72.53%  |
| SSD  | 22       | 24     | 24.18%  |
| NVMe | 3        | 3      | 3.3%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| OCZ VERTEX460A 480GB SSD | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| OCZ    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 332      | 755    | 48.54%  |
| Detected | 264      | 851    | 38.6%   |
| Malfunc  | 87       | 112    | 12.72%  |
| Failed   | 1        | 1      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 336      | 41.48%  |
| AMD                          | 221      | 27.28%  |
| Samsung Electronics          | 69       | 8.52%   |
| ASMedia Technology           | 31       | 3.83%   |
| SanDisk                      | 20       | 2.47%   |
| Phison Electronics           | 20       | 2.47%   |
| Nvidia                       | 16       | 1.98%   |
| Marvell Technology Group     | 13       | 1.6%    |
| JMicron Technology           | 13       | 1.6%    |
| Silicon Motion               | 12       | 1.48%   |
| Kingston Technology Company  | 12       | 1.48%   |
| Micron/Crucial Technology    | 9        | 1.11%   |
| ADATA Technology             | 8        | 0.99%   |
| Broadcom / LSI               | 6        | 0.74%   |
| Realtek Semiconductor        | 5        | 0.62%   |
| Micron Technology            | 4        | 0.49%   |
| VIA Technologies             | 3        | 0.37%   |
| Toshiba America Info Systems | 3        | 0.37%   |
| SK hynix                     | 3        | 0.37%   |
| Silicon Image                | 2        | 0.25%   |
| LSI Logic / Symbios Logic    | 1        | 0.12%   |
| INNOGRIT                     | 1        | 0.12%   |
| Adaptec                      | 1        | 0.12%   |
| 3ware                        | 1        | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 145      | 14.31%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 52       | 5.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 45       | 4.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 44       | 4.34%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 36       | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 33       | 3.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 30       | 2.96%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 29       | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 29       | 2.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 28       | 2.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 25       | 2.47%   |
| AMD 500 Series Chipset SATA Controller                                                  | 23       | 2.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 21       | 2.07%   |
| AMD FCH SATA Controller D                                                               | 21       | 2.07%   |
| Intel SATA Controller [RAID mode]                                                       | 19       | 1.88%   |
| AMD 300 Series Chipset SATA Controller                                                  | 19       | 1.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 16       | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 14       | 1.38%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 12       | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 11       | 1.09%   |
| Kingston Company A2000 NVMe SSD                                                         | 11       | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 11       | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11       | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11       | 1.09%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 10       | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 10       | 0.99%   |
| Phison E12 NVMe Controller                                                              | 9        | 0.89%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 9        | 0.89%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 8        | 0.79%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 0.79%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 0.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8        | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 7        | 0.69%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 7        | 0.69%   |
| Nvidia MCP61 IDE                                                                        | 7        | 0.69%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 7        | 0.69%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 6        | 0.59%   |
| Intel SSD 660P Series                                                                   | 6        | 0.59%   |
| AMD X370 Series Chipset SATA Controller                                                 | 6        | 0.59%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 5        | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 490      | 61.17%  |
| NVMe | 160      | 19.98%  |
| IDE  | 105      | 13.11%  |
| RAID | 37       | 4.62%   |
| SAS  | 6        | 0.75%   |
| SCSI | 3        | 0.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 335      | 58.67%  |
| AMD    | 236      | 41.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 22       | 3.83%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 18       | 3.14%   |
| AMD Ryzen 5 3600 6-Core Processor           | 18       | 3.14%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 13       | 2.26%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 11       | 1.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 9        | 1.57%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 9        | 1.57%   |
| AMD FX-8350 Eight-Core Processor            | 9        | 1.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 8        | 1.39%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 8        | 1.39%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 7        | 1.22%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 7        | 1.22%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 6        | 1.05%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 6        | 1.05%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 6        | 1.05%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 6        | 1.05%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 6        | 1.05%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 6        | 1.05%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 6        | 1.05%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 0.87%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 5        | 0.87%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 5        | 0.87%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 0.87%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 5        | 0.87%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 5        | 0.87%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 0.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 4        | 0.7%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 4        | 0.7%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 0.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 0.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.7%    |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 0.7%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 4        | 0.7%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 4        | 0.7%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 0.7%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 0.7%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 0.7%    |
| AMD FX-8320 Eight-Core Processor            | 4        | 0.7%    |
| Intel Pentium CPU G4560 @ 3.50GHz           | 3        | 0.52%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 118      | 20.56%  |
| Intel Core i7           | 88       | 15.33%  |
| AMD Ryzen 5             | 63       | 10.98%  |
| AMD Ryzen 7             | 50       | 8.71%   |
| Intel Xeon              | 32       | 5.57%   |
| Intel Core i3           | 27       | 4.7%    |
| AMD FX                  | 24       | 4.18%   |
| AMD Ryzen 9             | 23       | 4.01%   |
| Intel Core 2 Duo        | 15       | 2.61%   |
| Intel Pentium           | 12       | 2.09%   |
| AMD Phenom II X4        | 11       | 1.92%   |
| Intel Core i9           | 9        | 1.57%   |
| AMD Ryzen 3             | 9        | 1.57%   |
| Intel Core 2 Quad       | 8        | 1.39%   |
| Intel Celeron           | 8        | 1.39%   |
| AMD A10                 | 8        | 1.39%   |
| AMD Athlon II X4        | 7        | 1.22%   |
| AMD A8                  | 6        | 1.05%   |
| Other                   | 5        | 0.87%   |
| Intel Pentium Dual-Core | 5        | 0.87%   |
| AMD Athlon              | 5        | 0.87%   |
| AMD Ryzen Threadripper  | 4        | 0.7%    |
| AMD Athlon 64 X2        | 4        | 0.7%    |
| AMD Sempron             | 3        | 0.52%   |
| AMD Phenom II X6        | 3        | 0.52%   |
| AMD Phenom II X2        | 3        | 0.52%   |
| Intel Pentium D         | 2        | 0.35%   |
| Intel Pentium 4         | 2        | 0.35%   |
| Intel Atom              | 2        | 0.35%   |
| AMD Phenom              | 2        | 0.35%   |
| AMD Athlon II X2        | 2        | 0.35%   |
| AMD Athlon 64           | 2        | 0.35%   |
| AMD A4                  | 2        | 0.35%   |
| Intel Xeon Bronze       | 1        | 0.17%   |
| Intel Pentium Silver    | 1        | 0.17%   |
| Intel Pentium Dual      | 1        | 0.17%   |
| AMD Ryzen Embedded      | 1        | 0.17%   |
| AMD Ryzen 7 PRO         | 1        | 0.17%   |
| AMD GX                  | 1        | 0.17%   |
| AMD E                   | 1        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 249      | 43.46%  |
| 2      | 106      | 18.5%   |
| 6      | 91       | 15.88%  |
| 8      | 79       | 13.79%  |
| 12     | 25       | 4.36%   |
| 1      | 9        | 1.57%   |
| 16     | 7        | 1.22%   |
| 3      | 3        | 0.52%   |
| 24     | 2        | 0.35%   |
| 20     | 1        | 0.17%   |
| 18     | 1        | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 561      | 98.25%  |
| 2      | 10       | 1.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 348      | 60.84%  |
| 1      | 224      | 39.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 571      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 63       | 10.82%  |
| 0x306c3    | 56       | 9.62%   |
| 0x08701021 | 44       | 7.56%   |
| 0x306a9    | 37       | 6.36%   |
| 0x206a7    | 35       | 6.01%   |
| 0x0800820d | 29       | 4.98%   |
| 0x506e3    | 24       | 4.12%   |
| 0x08701013 | 23       | 3.95%   |
| 0x906e9    | 22       | 3.78%   |
| 0x1067a    | 22       | 3.78%   |
| 0x06000852 | 20       | 3.44%   |
| 0x906ea    | 18       | 3.09%   |
| 0x010000c8 | 13       | 2.23%   |
| 0x08108109 | 9        | 1.55%   |
| 0x010000db | 9        | 1.55%   |
| 0x906ed    | 8        | 1.37%   |
| 0x306f2    | 8        | 1.37%   |
| 0xa0653    | 7        | 1.2%    |
| 0x106a5    | 7        | 1.2%    |
| 0x906ec    | 6        | 1.03%   |
| 0x106e5    | 6        | 1.03%   |
| 0x06001119 | 6        | 1.03%   |
| 0xa0655    | 5        | 0.86%   |
| 0x306e4    | 5        | 0.86%   |
| 0x10676    | 5        | 0.86%   |
| 0x08001138 | 5        | 0.86%   |
| 0x08001137 | 5        | 0.86%   |
| 0x06003106 | 5        | 0.86%   |
| 0xa0671    | 4        | 0.69%   |
| 0x6fb      | 4        | 0.69%   |
| 0x206d7    | 4        | 0.69%   |
| 0x0a201009 | 4        | 0.69%   |
| 0x0810100b | 4        | 0.69%   |
| 0x0a201016 | 3        | 0.52%   |
| 0x08101016 | 3        | 0.52%   |
| 0x0800111c | 3        | 0.52%   |
| 0x0700010f | 3        | 0.52%   |
| 0x010000dc | 3        | 0.52%   |
| 0xf64      | 2        | 0.34%   |
| 0xf41      | 2        | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 73       | 12.74%  |
| Haswell       | 71       | 12.39%  |
| KabyLake      | 62       | 10.82%  |
| Zen+          | 46       | 8.03%   |
| IvyBridge     | 45       | 7.85%   |
| SandyBridge   | 43       | 7.5%    |
| Piledriver    | 31       | 5.41%   |
| Skylake       | 30       | 5.24%   |
| K10           | 29       | 5.06%   |
| Penryn        | 28       | 4.89%   |
| Zen           | 25       | 4.36%   |
| Nehalem       | 15       | 2.62%   |
| CometLake     | 13       | 2.27%   |
| Zen 3         | 10       | 1.75%   |
| Steamroller   | 7        | 1.22%   |
| K8 Hammer     | 7        | 1.22%   |
| Westmere      | 6        | 1.05%   |
| Core          | 6        | 1.05%   |
| NetBurst      | 4        | 0.7%    |
| Jaguar        | 4        | 0.7%    |
| Icelake       | 4        | 0.7%    |
| Goldmont plus | 4        | 0.7%    |
| Excavator     | 2        | 0.35%   |
| Silvermont    | 1        | 0.17%   |
| K10 Llano     | 1        | 0.17%   |
| Goldmont      | 1        | 0.17%   |
| Bulldozer     | 1        | 0.17%   |
| Broadwell     | 1        | 0.17%   |
| Bonnell       | 1        | 0.17%   |
| Bobcat        | 1        | 0.17%   |
| Unknown       | 1        | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 277      | 46.09%  |
| AMD               | 192      | 31.95%  |
| Intel             | 131      | 21.8%   |
| ASPEED Technology | 1        | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 35       | 5.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 27       | 4.4%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 21       | 3.42%   |
| Nvidia GK208B [GeForce GT 710]                                              | 17       | 2.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 16       | 2.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 15       | 2.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 15       | 2.44%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 14       | 2.28%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 11       | 1.79%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 10       | 1.63%   |
| Intel HD Graphics 530                                                       | 10       | 1.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 10       | 1.63%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 1.47%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 9        | 1.47%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 9        | 1.47%   |
| Nvidia GT218 [GeForce 210]                                                  | 8        | 1.3%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 8        | 1.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 8        | 1.3%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 8        | 1.3%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 7        | 1.14%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 1.14%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 7        | 1.14%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 6        | 0.98%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 6        | 0.98%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 6        | 0.98%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 6        | 0.98%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 6        | 0.98%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 6        | 0.98%   |
| Nvidia GF119 [GeForce GT 610]                                               | 6        | 0.98%   |
| Intel HD Graphics 630                                                       | 6        | 0.98%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 6        | 0.98%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 6        | 0.98%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 5        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.81%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 0.81%   |
| AMD RS780L [Radeon 3000]                                                    | 5        | 0.81%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 5        | 0.81%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 5        | 0.81%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 5        | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 256      | 44.44%  |
| 1 x AMD         | 180      | 31.25%  |
| 1 x Intel       | 112      | 19.44%  |
| 2 x Nvidia      | 6        | 1.04%   |
| Intel + Nvidia  | 6        | 1.04%   |
| AMD + Nvidia    | 6        | 1.04%   |
| 2 x AMD         | 5        | 0.87%   |
| Intel + AMD     | 3        | 0.52%   |
| 3 x Nvidia      | 1        | 0.17%   |
| Nvidia + ASPEED | 1        | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 345      | 59.38%  |
| Proprietary | 228      | 39.24%  |
| Unknown     | 8        | 1.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 153      | 26.38%  |
| 1.01-2.0   | 84       | 14.48%  |
| 7.01-8.0   | 80       | 13.79%  |
| 0.51-1.0   | 77       | 13.28%  |
| 3.01-4.0   | 74       | 12.76%  |
| 0.01-0.5   | 47       | 8.1%    |
| 5.01-6.0   | 36       | 6.21%   |
| 8.01-16.0  | 15       | 2.59%   |
| 2.01-3.0   | 12       | 2.07%   |
| 32.01-64.0 | 1        | 0.17%   |
| 4.01-5.0   | 1        | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 114      | 16.69%  |
| Goldstar                | 75       | 10.98%  |
| Dell                    | 75       | 10.98%  |
| Acer                    | 52       | 7.61%   |
| Hewlett-Packard         | 42       | 6.15%   |
| BenQ                    | 40       | 5.86%   |
| Ancor Communications    | 40       | 5.86%   |
| AOC                     | 31       | 4.54%   |
| Philips                 | 25       | 3.66%   |
| ViewSonic               | 23       | 3.37%   |
| LG Electronics          | 16       | 2.34%   |
| Iiyama                  | 13       | 1.9%    |
| ASUSTek Computer        | 13       | 1.9%    |
| Unknown                 | 11       | 1.61%   |
| Sony                    | 8        | 1.17%   |
| Panasonic               | 6        | 0.88%   |
| Lenovo                  | 6        | 0.88%   |
| Eizo                    | 5        | 0.73%   |
| NEC Computers           | 4        | 0.59%   |
| Medion                  | 4        | 0.59%   |
| Viotek                  | 3        | 0.44%   |
| Idek Iiyama             | 3        | 0.44%   |
| HPN                     | 3        | 0.44%   |
| DENON                   | 3        | 0.44%   |
| Unknown (XXX)           | 2        | 0.29%   |
| Sceptre Tech            | 2        | 0.29%   |
| Sceptre                 | 2        | 0.29%   |
| ONN                     | 2        | 0.29%   |
| Onkyo                   | 2        | 0.29%   |
| Hitachi                 | 2        | 0.29%   |
| HannStar                | 2        | 0.29%   |
| Grundig                 | 2        | 0.29%   |
| Gateway                 | 2        | 0.29%   |
| Fujitsu Siemens         | 2        | 0.29%   |
| Envision                | 2        | 0.29%   |
| Chi Mei Optoelectronics | 2        | 0.29%   |
| AUS                     | 2        | 0.29%   |
| Yamaha                  | 1        | 0.15%   |
| Xiaomi                  | 1        | 0.15%   |
| VST                     | 1        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 7        | 0.94%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 7        | 0.94%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 4        | 0.53%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 4        | 0.53%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 3        | 0.4%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 3        | 0.4%    |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 3        | 0.4%    |
| Hewlett-Packard L1740 HWP2649 1280x1024 338x270mm 17.0-inch           | 3        | 0.4%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 3        | 0.4%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 3        | 0.4%    |
| Dell UP2716D DEL40DD 2560x1440 597x336mm 27.0-inch                    | 3        | 0.4%    |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                     | 3        | 0.4%    |
| BenQ GL2780 BNQ78EC 1920x1080 598x336mm 27.0-inch                     | 3        | 0.4%    |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 3        | 0.4%    |
| Viotek GN34CW VTK3400 3440x1440 795x334mm 33.9-inch                   | 2        | 0.27%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 2        | 0.27%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 2        | 0.27%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2        | 0.27%   |
| Samsung Electronics SyncMaster STN0046 1280x1024 338x270mm 17.0-inch  | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch  | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 2        | 0.27%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 2        | 0.27%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 2        | 0.27%   |
| Samsung Electronics S22B350 SAM08D4 1920x1080 480x270mm 21.7-inch     | 2        | 0.27%   |
| Samsung Electronics LCD Monitor SAM04FD 1360x768                      | 2        | 0.27%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 2        | 0.27%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 2        | 0.27%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2        | 0.27%   |
| Panasonic LCD Monitor TV 1920x1080                                    | 2        | 0.27%   |
| Panasonic LCD Monitor TV                                              | 2        | 0.27%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 2        | 0.27%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                      | 2        | 0.27%   |
| LG Electronics LCD Monitor LG IPS FULLHD                              | 2        | 0.27%   |
| Lenovo LT2252p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch             | 2        | 0.27%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 2        | 0.27%   |
| Hewlett-Packard 24er HWP3320 1920x1080 527x296mm 23.8-inch            | 2        | 0.27%   |
| Grundig WXGA GRU4448 1600x1200                                        | 2        | 0.27%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2        | 0.27%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2        | 0.27%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 2        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 308      | 46.6%   |
| 3840x2160 (4K)     | 56       | 8.47%   |
| 2560x1440 (QHD)    | 47       | 7.11%   |
| 1280x1024 (SXGA)   | 37       | 5.6%    |
| 1680x1050 (WSXGA+) | 32       | 4.84%   |
| 1920x1200 (WUXGA)  | 29       | 4.39%   |
| Unknown            | 29       | 4.39%   |
| 2560x1080          | 15       | 2.27%   |
| 1440x900 (WXGA+)   | 15       | 2.27%   |
| 1600x900 (HD+)     | 14       | 2.12%   |
| 1366x768 (WXGA)    | 12       | 1.82%   |
| 3440x1440          | 10       | 1.51%   |
| 3840x1080          | 9        | 1.36%   |
| 1920x540           | 6        | 0.91%   |
| 1360x768           | 5        | 0.76%   |
| 5760x1080          | 3        | 0.45%   |
| 4480x1440          | 3        | 0.45%   |
| 3840x1600          | 3        | 0.45%   |
| 3600x1080          | 3        | 0.45%   |
| 1600x1200          | 3        | 0.45%   |
| 3840x1200          | 2        | 0.3%    |
| 3200x1080          | 2        | 0.3%    |
| 2560x1600          | 2        | 0.3%    |
| 1280x720 (HD)      | 2        | 0.3%    |
| 1024x768 (XGA)     | 2        | 0.3%    |
| 7680x2160          | 1        | 0.15%   |
| 6400x2160          | 1        | 0.15%   |
| 4480x1600          | 1        | 0.15%   |
| 4480x1080          | 1        | 0.15%   |
| 3840x1920          | 1        | 0.15%   |
| 3600x1200          | 1        | 0.15%   |
| 3360x1080          | 1        | 0.15%   |
| 2880x1440          | 1        | 0.15%   |
| 2048x1152          | 1        | 0.15%   |
| 1921x1080          | 1        | 0.15%   |
| 1400x1050          | 1        | 0.15%   |
| 1280x960           | 1        | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 105      | 15.46%  |
| 24      | 102      | 15.02%  |
| 27      | 98       | 14.43%  |
| 23      | 80       | 11.78%  |
| 21      | 76       | 11.19%  |
| 19      | 38       | 5.6%    |
| 31      | 27       | 3.98%   |
| 22      | 22       | 3.24%   |
| 34      | 21       | 3.09%   |
| 17      | 20       | 2.95%   |
| 20      | 19       | 2.8%    |
| 25      | 10       | 1.47%   |
| 18      | 10       | 1.47%   |
| 84      | 5        | 0.74%   |
| 54      | 5        | 0.74%   |
| 72      | 4        | 0.59%   |
| 37      | 4        | 0.59%   |
| 47      | 3        | 0.44%   |
| 43      | 3        | 0.44%   |
| 32      | 3        | 0.44%   |
| 26      | 3        | 0.44%   |
| 15      | 3        | 0.44%   |
| 48      | 2        | 0.29%   |
| 40      | 2        | 0.29%   |
| 39      | 2        | 0.29%   |
| 74      | 1        | 0.15%   |
| 65      | 1        | 0.15%   |
| 60      | 1        | 0.15%   |
| 57      | 1        | 0.15%   |
| 55      | 1        | 0.15%   |
| 52      | 1        | 0.15%   |
| 46      | 1        | 0.15%   |
| 30      | 1        | 0.15%   |
| 29      | 1        | 0.15%   |
| 28      | 1        | 0.15%   |
| 12      | 1        | 0.15%   |
| 3       | 1        | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 249      | 38.97%  |
| 401-500     | 134      | 20.97%  |
| Unknown     | 105      | 16.43%  |
| 601-700     | 43       | 6.73%   |
| 351-400     | 25       | 3.91%   |
| 701-800     | 24       | 3.76%   |
| 301-350     | 20       | 3.13%   |
| 1001-1500   | 16       | 2.5%    |
| 1501-2000   | 10       | 1.56%   |
| 801-900     | 8        | 1.25%   |
| 901-1000    | 3        | 0.47%   |
| 201-300     | 1        | 0.16%   |
| 1-100       | 1        | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 366      | 59.03%  |
| Unknown | 93       | 15%     |
| 16/10   | 82       | 13.23%  |
| 5/4     | 38       | 6.13%   |
| 21/9    | 24       | 3.87%   |
| 4/3     | 6        | 0.97%   |
| 32/9    | 5        | 0.81%   |
| 6/5     | 2        | 0.32%   |
| 3/2     | 2        | 0.32%   |
| 1.96    | 2        | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 206      | 31.45%  |
| Unknown        | 105      | 16.03%  |
| 301-350        | 99       | 15.11%  |
| 151-200        | 74       | 11.3%   |
| 351-500        | 54       | 8.24%   |
| 251-300        | 48       | 7.33%   |
| 141-150        | 26       | 3.97%   |
| More than 1000 | 19       | 2.9%    |
| 501-1000       | 16       | 2.44%   |
| 101-110        | 3        | 0.46%   |
| 131-140        | 2        | 0.31%   |
| 71-80          | 1        | 0.15%   |
| 1-40           | 1        | 0.15%   |
| 121-130        | 1        | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 351      | 56.34%  |
| 101-120       | 117      | 18.78%  |
| Unknown       | 105      | 16.85%  |
| 121-160       | 21       | 3.37%   |
| 1-50          | 17       | 2.73%   |
| 161-240       | 11       | 1.77%   |
| More than 240 | 1        | 0.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 408      | 70.71%  |
| 2     | 142      | 24.61%  |
| 3     | 18       | 3.12%   |
| 0     | 8        | 1.39%   |
| 4     | 1        | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 334      | 42.39%  |
| Intel                           | 242      | 30.71%  |
| Qualcomm Atheros                | 52       | 6.6%    |
| Ralink Technology               | 24       | 3.05%   |
| TP-Link                         | 15       | 1.9%    |
| Broadcom                        | 15       | 1.9%    |
| Nvidia                          | 13       | 1.65%   |
| Microsoft                       | 10       | 1.27%   |
| Ralink                          | 8        | 1.02%   |
| Aquantia                        | 8        | 1.02%   |
| Xiaomi                          | 4        | 0.51%   |
| Samsung Electronics             | 4        | 0.51%   |
| Qualcomm Atheros Communications | 4        | 0.51%   |
| NetGear                         | 4        | 0.51%   |
| D-Link System                   | 4        | 0.51%   |
| Broadcom Limited                | 4        | 0.51%   |
| DisplayLink                     | 3        | 0.38%   |
| Wacom                           | 2        | 0.25%   |
| STMicroelectronics              | 2        | 0.25%   |
| Marvell Technology Group        | 2        | 0.25%   |
| Edimax Technology               | 2        | 0.25%   |
| D-Link                          | 2        | 0.25%   |
| Belkin Components               | 2        | 0.25%   |
| ASIX Electronics                | 2        | 0.25%   |
| Apple                           | 2        | 0.25%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.13%   |
| Wilocity                        | 1        | 0.13%   |
| VIA Technologies                | 1        | 0.13%   |
| Sigma Designs                   | 1        | 0.13%   |
| Seeed Technology                | 1        | 0.13%   |
| Qualcomm                        | 1        | 0.13%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.13%   |
| Motorola BCS                    | 1        | 0.13%   |
| Micro Star International        | 1        | 0.13%   |
| Mercucys                        | 1        | 0.13%   |
| Mellanox Technologies           | 1        | 0.13%   |
| MediaTek                        | 1        | 0.13%   |
| Linksys                         | 1        | 0.13%   |
| Lenovo                          | 1        | 0.13%   |
| Huawei Technologies             | 1        | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 277      | 30.85%  |
| Intel I211 Gigabit Network Connection                             | 55       | 6.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 31       | 3.45%   |
| Intel Wi-Fi 6 AX200                                               | 29       | 3.23%   |
| Intel Ethernet Connection (2) I219-V                              | 27       | 3.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26       | 2.9%    |
| Intel Ethernet Connection (7) I219-V                              | 16       | 1.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12       | 1.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 1.22%   |
| Ralink MT7601U Wireless Adapter                                   | 11       | 1.22%   |
| Intel Wireless-AC 9260                                            | 11       | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 11       | 1.22%   |
| Intel 82579V Gigabit Network Connection                           | 10       | 1.11%   |
| Intel Ethernet Connection I217-V                                  | 9        | 1%      |
| Intel Ethernet Connection (2) I218-V                              | 9        | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8        | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 0.89%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8        | 0.89%   |
| Intel I210 Gigabit Network Connection                             | 7        | 0.78%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.67%   |
| Microsoft Xbox 360 Wireless Adapter                               | 6        | 0.67%   |
| Intel Wireless 7260                                               | 6        | 0.67%   |
| Intel Ethernet Controller I225-V                                  | 6        | 0.67%   |
| Realtek 802.11ac NIC                                              | 5        | 0.56%   |
| Ralink RT5370 Wireless Adapter                                    | 5        | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5        | 0.56%   |
| Nvidia MCP61 Ethernet                                             | 5        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 5        | 0.56%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 0.56%   |
| TP-Link Archer T4U ver.3                                          | 4        | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4        | 0.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4        | 0.45%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4        | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.45%   |
| Nvidia MCP77 Ethernet                                             | 4        | 0.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 79       | 33.19%  |
| Realtek Semiconductor                 | 41       | 17.23%  |
| Qualcomm Atheros                      | 27       | 11.34%  |
| Ralink Technology                     | 24       | 10.08%  |
| TP-Link                               | 15       | 6.3%    |
| Microsoft                             | 10       | 4.2%    |
| Ralink                                | 8        | 3.36%   |
| Broadcom                              | 5        | 2.1%    |
| Qualcomm Atheros Communications       | 4        | 1.68%   |
| NetGear                               | 4        | 1.68%   |
| Wacom                                 | 2        | 0.84%   |
| Edimax Technology                     | 2        | 0.84%   |
| D-Link System                         | 2        | 0.84%   |
| D-Link                                | 2        | 0.84%   |
| Broadcom Limited                      | 2        | 0.84%   |
| Belkin Components                     | 2        | 0.84%   |
| Wilocity                              | 1        | 0.42%   |
| Micro Star International              | 1        | 0.42%   |
| Mercucys                              | 1        | 0.42%   |
| Linksys                               | 1        | 0.42%   |
| Gemtek                                | 1        | 0.42%   |
| AVM                                   | 1        | 0.42%   |
| AirTies Wireless Networks             | 1        | 0.42%   |
| Accton Technology                     | 1        | 0.42%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 29       | 12.08%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 12       | 5%      |
| Ralink MT7601U Wireless Adapter                                                               | 11       | 4.58%   |
| Intel Wireless-AC 9260                                                                        | 11       | 4.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 6        | 2.5%    |
| Microsoft Xbox 360 Wireless Adapter                                                           | 6        | 2.5%    |
| Intel Wireless 7260                                                                           | 6        | 2.5%    |
| Realtek 802.11ac NIC                                                                          | 5        | 2.08%   |
| Ralink RT5370 Wireless Adapter                                                                | 5        | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5        | 2.08%   |
| TP-Link Archer T4U ver.3                                                                      | 4        | 1.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 4        | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 4        | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 4        | 1.67%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 4        | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4        | 1.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 4        | 1.67%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 3        | 1.25%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 3        | 1.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 1.25%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 3        | 1.25%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 3        | 1.25%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 3        | 1.25%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                                   | 3        | 1.25%   |
| Intel Wireless 7265                                                                           | 3        | 1.25%   |
| Intel Wireless 3165                                                                           | 3        | 1.25%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                                      | 2        | 0.83%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2        | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.83%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 2        | 0.83%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 2        | 0.83%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 0.83%   |
| Ralink RT5572 Wireless Adapter                                                                | 2        | 0.83%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 2        | 0.83%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                                   | 2        | 0.83%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 2        | 0.83%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 2        | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 322      | 51.69%  |
| Intel                         | 208      | 33.39%  |
| Qualcomm Atheros              | 29       | 4.65%   |
| Nvidia                        | 13       | 2.09%   |
| Broadcom                      | 10       | 1.61%   |
| Aquantia                      | 8        | 1.28%   |
| Xiaomi                        | 4        | 0.64%   |
| Samsung Electronics           | 4        | 0.64%   |
| DisplayLink                   | 3        | 0.48%   |
| Marvell Technology Group      | 2        | 0.32%   |
| D-Link System                 | 2        | 0.32%   |
| Broadcom Limited              | 2        | 0.32%   |
| ASIX Electronics              | 2        | 0.32%   |
| Apple                         | 2        | 0.32%   |
| ZTE WCDMA Technologies MSM    | 1        | 0.16%   |
| VIA Technologies              | 1        | 0.16%   |
| Qualcomm                      | 1        | 0.16%   |
| OnePlus Technology (Shenzhen) | 1        | 0.16%   |
| Motorola BCS                  | 1        | 0.16%   |
| Mellanox Technologies         | 1        | 0.16%   |
| MediaTek                      | 1        | 0.16%   |
| Lenovo                        | 1        | 0.16%   |
| Huawei Technologies           | 1        | 0.16%   |
| Elecom                        | 1        | 0.16%   |
| Davicom Semiconductor         | 1        | 0.16%   |
| 3Com                          | 1        | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 277      | 42.42%  |
| Intel I211 Gigabit Network Connection                             | 55       | 8.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 31       | 4.75%   |
| Intel Ethernet Connection (2) I219-V                              | 27       | 4.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26       | 3.98%   |
| Intel Ethernet Connection (7) I219-V                              | 16       | 2.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 1.68%   |
| Intel Ethernet Connection I217-LM                                 | 11       | 1.68%   |
| Intel 82579V Gigabit Network Connection                           | 10       | 1.53%   |
| Intel Ethernet Connection I217-V                                  | 9        | 1.38%   |
| Intel Ethernet Connection (2) I218-V                              | 9        | 1.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8        | 1.23%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 1.23%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8        | 1.23%   |
| Intel I210 Gigabit Network Connection                             | 7        | 1.07%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7        | 1.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.92%   |
| Intel Ethernet Controller I225-V                                  | 6        | 0.92%   |
| Nvidia MCP61 Ethernet                                             | 5        | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 5        | 0.77%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.61%   |
| Nvidia MCP77 Ethernet                                             | 4        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 0.46%   |
| Intel Ethernet Connection (2) I218-LM                             | 3        | 0.46%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3        | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2        | 0.31%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.31%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.31%   |
| Nvidia MCP67 Ethernet                                             | 2        | 0.31%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.31%   |
| Intel Ethernet Connection (5) I219-LM                             | 2        | 0.31%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.31%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.31%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 567      | 71.68%  |
| WiFi     | 219      | 27.69%  |
| Modem    | 5        | 0.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 471      | 77.98%  |
| WiFi     | 133      | 22.02%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 391      | 68.36%  |
| 2     | 154      | 26.92%  |
| 3     | 20       | 3.5%    |
| 4     | 4        | 0.7%    |
| 0     | 2        | 0.35%   |
| 6     | 1        | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 505      | 87.07%  |
| Yes  | 75       | 12.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 75       | 36.59%  |
| Cambridge Silicon Radio         | 65       | 31.71%  |
| Broadcom                        | 20       | 9.76%   |
| Realtek Semiconductor           | 13       | 6.34%   |
| ASUSTek Computer                | 11       | 5.37%   |
| Qualcomm Atheros Communications | 8        | 3.9%    |
| Lite-On Technology              | 2        | 0.98%   |
| Belkin Components               | 2        | 0.98%   |
| TP-Link                         | 1        | 0.49%   |
| Realtek                         | 1        | 0.49%   |
| Micro Star International        | 1        | 0.49%   |
| Integrated System Solution      | 1        | 0.49%   |
| IMC Networks                    | 1        | 0.49%   |
| Dynex                           | 1        | 0.49%   |
| Creative Technology             | 1        | 0.49%   |
| Apple                           | 1        | 0.49%   |
| AboCom Systems                  | 1        | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 65       | 31.55%  |
| Intel AX200 Bluetooth                                    | 28       | 13.59%  |
| Intel Bluetooth wireless interface                       | 15       | 7.28%   |
| Intel Wireless-AC 3168 Bluetooth                         | 12       | 5.83%   |
| Realtek Bluetooth Radio                                  | 10       | 4.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 10       | 4.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 10       | 4.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 8        | 3.88%   |
| ASUS Bluetooth Device                                    | 6        | 2.91%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 3        | 1.46%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2        | 0.97%   |
| Qualcomm Atheros  Bluetooth Device                       | 2        | 0.97%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 0.97%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 2        | 0.97%   |
| Broadcom BCM92045B3 ROM                                  | 2        | 0.97%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 2        | 0.97%   |
| TP-Link UB500 Adapter                                    | 1        | 0.49%   |
| Realtek RTL8821A Bluetooth                               | 1        | 0.49%   |
| Realtek Bluetooth Radio                                  | 1        | 0.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 1        | 0.49%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 0.49%   |
| Micro Star International Bluetooth Device                | 1        | 0.49%   |
| Lite-On Bluetooth Device                                 | 1        | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1        | 0.49%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.49%   |
| Intel AX210 Bluetooth                                    | 1        | 0.49%   |
| Intel AX201 Bluetooth                                    | 1        | 0.49%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 1        | 0.49%   |
| IMC Networks Bluetooth Radio                             | 1        | 0.49%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.49%   |
| Creative Bluetooth Audio W2                              | 1        | 0.49%   |
| Broadcom Bluetooth Controller                            | 1        | 0.49%   |
| Broadcom Bluetooth 3.0 Dongle                            | 1        | 0.49%   |
| Broadcom Bluetooth 3.0 Device                            | 1        | 0.49%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle      | 1        | 0.49%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 1        | 0.49%   |
| Broadcom BCM2045 Bluetooth                               | 1        | 0.49%   |
| Broadcom BCM2035B3 Bluetooth Adapter                     | 1        | 0.49%   |
| Broadcom ANYCOM Blue USB-200/250                         | 1        | 0.49%   |
| ASUS Bluetooth Radio                                     | 1        | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 325      | 31.1%   |
| AMD                       | 289      | 27.66%  |
| Nvidia                    | 265      | 25.36%  |
| C-Media Electronics       | 33       | 3.16%   |
| Creative Labs             | 13       | 1.24%   |
| Logitech                  | 11       | 1.05%   |
| JMTek                     | 10       | 0.96%   |
| Corsair                   | 7        | 0.67%   |
| Texas Instruments         | 6        | 0.57%   |
| GN Netcom                 | 6        | 0.57%   |
| ASUSTek Computer          | 5        | 0.48%   |
| Razer USA                 | 4        | 0.38%   |
| Plantronics               | 4        | 0.38%   |
| Focusrite-Novation        | 4        | 0.38%   |
| Creative Technology       | 4        | 0.38%   |
| Tenx Technology           | 3        | 0.29%   |
| SAVITECH                  | 3        | 0.29%   |
| Realtek Semiconductor     | 3        | 0.29%   |
| Kingston Technology       | 3        | 0.29%   |
| Yamaha                    | 2        | 0.19%   |
| XMOS                      | 2        | 0.19%   |
| VIA Technologies          | 2        | 0.19%   |
| Trust                     | 2        | 0.19%   |
| SteelSeries ApS           | 2        | 0.19%   |
| Sony                      | 2        | 0.19%   |
| Samson Technologies       | 2        | 0.19%   |
| RODE Microphones          | 2        | 0.19%   |
| ONN                       | 2        | 0.19%   |
| Native Instruments        | 2        | 0.19%   |
| Hewlett-Packard           | 2        | 0.19%   |
| Generalplus Technology    | 2        | 0.19%   |
| Fry's Electronics         | 2        | 0.19%   |
| Bose                      | 2        | 0.19%   |
| BEHRINGER International   | 2        | 0.19%   |
| Valve Software            | 1        | 0.1%    |
| USB MICROPHONE            | 1        | 0.1%    |
| Turtle Beach              | 1        | 0.1%    |
| TEAC                      | 1        | 0.1%    |
| Sennheiser Communications | 1        | 0.1%    |
| Schiit Audio              | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 78       | 6.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 50       | 4.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 47       | 3.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 45       | 3.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 43       | 3.58%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 37       | 3.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 36       | 3%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 33       | 2.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 31       | 2.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 29       | 2.41%   |
| Intel 200 Series PCH HD Audio                                              | 28       | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 25       | 2.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 25       | 2.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 23       | 1.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 23       | 1.91%   |
| AMD Family 17h/19h HD Audio Controller                                     | 23       | 1.91%   |
| Nvidia GP106 High Definition Audio Controller                              | 22       | 1.83%   |
| Nvidia GP104 High Definition Audio Controller                              | 18       | 1.5%    |
| AMD FCH Azalia Controller                                                  | 18       | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 17       | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 16       | 1.33%   |
| AMD Navi 10 HDMI Audio                                                     | 16       | 1.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 14       | 1.16%   |
| Nvidia High Definition Audio Controller                                    | 13       | 1.08%   |
| Nvidia GM204 High Definition Audio Controller                              | 13       | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 13       | 1.08%   |
| Nvidia GM206 High Definition Audio Controller                              | 12       | 1%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 12       | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 11       | 0.92%   |
| Nvidia GF119 HDMI Audio Controller                                         | 10       | 0.83%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 10       | 0.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10       | 0.83%   |
| Nvidia TU104 HD Audio Controller                                           | 9        | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                              | 9        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9        | 0.75%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 9        | 0.75%   |
| Nvidia MCP61 High Definition Audio                                         | 8        | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                              | 8        | 0.67%   |
| JMTek USB PnP Audio Device                                                 | 8        | 0.67%   |
| Intel Comet Lake PCH-V cAVS                                                | 8        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 89       | 21.04%  |
| Corsair             | 63       | 14.89%  |
| Unknown             | 51       | 12.06%  |
| Crucial             | 49       | 11.58%  |
| G.Skill             | 46       | 10.87%  |
| SK hynix            | 31       | 7.33%   |
| Samsung Electronics | 29       | 6.86%   |
| Micron Technology   | 12       | 2.84%   |
| Patriot             | 8        | 1.89%   |
| A-DATA Technology   | 7        | 1.65%   |
| Team                | 6        | 1.42%   |
| Transcend           | 4        | 0.95%   |
| Nanya Technology    | 4        | 0.95%   |
| GOODRAM             | 4        | 0.95%   |
| Ramaxel Technology  | 3        | 0.71%   |
| Silicon Power       | 2        | 0.47%   |
| AMD                 | 2        | 0.47%   |
| Unknown (82B5)      | 1        | 0.24%   |
| Unifosa             | 1        | 0.24%   |
| Smart               | 1        | 0.24%   |
| Reboto              | 1        | 0.24%   |
| Kllisre             | 1        | 0.24%   |
| Hewlett-Packard     | 1        | 0.24%   |
| GeIL                | 1        | 0.24%   |
| Elpida              | 1        | 0.24%   |
| Centon              | 1        | 0.24%   |
| Avant               | 1        | 0.24%   |
| ASint Technology    | 1        | 0.24%   |
| Apacer              | 1        | 0.24%   |
| Ankowall            | 1        | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 10       | 2.07%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 6        | 1.24%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 4        | 0.83%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 4        | 0.83%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 4        | 0.83%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 4        | 0.83%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 3        | 0.62%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                  | 3        | 0.62%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 3        | 0.62%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s       | 3        | 0.62%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 3        | 0.62%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s      | 3        | 0.62%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s     | 3        | 0.62%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 3        | 0.62%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s        | 3        | 0.62%   |
| Kingston RAM 99U5471-066.A00LF 8192MB DIMM DDR3 1600MT/s | 3        | 0.62%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 3        | 0.62%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 3        | 0.62%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s   | 3        | 0.62%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 2        | 0.41%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                   | 2        | 0.41%   |
| Unknown RAM Module 4096MB DIMM SDRAM                     | 2        | 0.41%   |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s              | 2        | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 2        | 0.41%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 2        | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 2        | 0.41%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8192MB DIMM DDR3 1600MT/s  | 2        | 0.41%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s     | 2        | 0.41%   |
| Samsung RAM M393B2G70DB0 16GB DIMM DDR3 1866MT/s         | 2        | 0.41%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s      | 2        | 0.41%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 2        | 0.41%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 2        | 0.41%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s      | 2        | 0.41%   |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s      | 2        | 0.41%   |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s     | 2        | 0.41%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 2        | 0.41%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 2        | 0.41%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s  | 2        | 0.41%   |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s     | 2        | 0.41%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s      | 2        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 197      | 51.44%  |
| DDR3    | 135      | 35.25%  |
| Unknown | 21       | 5.48%   |
| DDR2    | 18       | 4.7%    |
| SDRAM   | 10       | 2.61%   |
| DDR     | 2        | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 361      | 95.25%  |
| SODIMM  | 16       | 4.22%   |
| FB-DIMM | 2        | 0.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 162      | 38.48%  |
| 4096  | 91       | 21.62%  |
| 16384 | 90       | 21.38%  |
| 2048  | 57       | 13.54%  |
| 32768 | 11       | 2.61%   |
| 1024  | 10       | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 81       | 18.93%  |
| 1333    | 50       | 11.68%  |
| 3200    | 41       | 9.58%   |
| 3600    | 38       | 8.88%   |
| 2400    | 29       | 6.78%   |
| 2667    | 24       | 5.61%   |
| 2133    | 23       | 5.37%   |
| 800     | 16       | 3.74%   |
| 3400    | 12       | 2.8%    |
| 2666    | 12       | 2.8%    |
| 3000    | 10       | 2.34%   |
| 667     | 10       | 2.34%   |
| 3733    | 8        | 1.87%   |
| 3800    | 7        | 1.64%   |
| 3466    | 6        | 1.4%    |
| 2933    | 6        | 1.4%    |
| 1866    | 6        | 1.4%    |
| 1066    | 5        | 1.17%   |
| Unknown | 4        | 0.93%   |
| 3866    | 3        | 0.7%    |
| 3151    | 3        | 0.7%    |
| 2800    | 3        | 0.7%    |
| 1800    | 3        | 0.7%    |
| 1334    | 3        | 0.7%    |
| 400     | 3        | 0.7%    |
| 3333    | 2        | 0.47%   |
| 2132    | 2        | 0.47%   |
| 2000    | 2        | 0.47%   |
| 1867    | 2        | 0.47%   |
| 1067    | 2        | 0.47%   |
| 49926   | 1        | 0.23%   |
| 3467    | 1        | 0.23%   |
| 3334    | 1        | 0.23%   |
| 3066    | 1        | 0.23%   |
| 2866    | 1        | 0.23%   |
| 2473    | 1        | 0.23%   |
| 2176    | 1        | 0.23%   |
| 2134    | 1        | 0.23%   |
| 2048    | 1        | 0.23%   |
| 880     | 1        | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 18       | 42.86%  |
| Brother Industries     | 13       | 30.95%  |
| Seiko Epson            | 3        | 7.14%   |
| Samsung Electronics    | 2        | 4.76%   |
| Canon                  | 2        | 4.76%   |
| SAT                    | 1        | 2.38%   |
| Prolific Technology    | 1        | 2.38%   |
| Pantum                 | 1        | 2.38%   |
| Panasonic (Matsushita) | 1        | 2.38%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson Printer                  | 1        | 2.33%   |
| Seiko Epson L3150 Series             | 1        | 2.33%   |
| Seiko Epson L120 Series              | 1        | 2.33%   |
| SAT SAT38TUSE                        | 1        | 2.33%   |
| Samsung ML-216x Series Laser Printer | 1        | 2.33%   |
| Samsung CLX-3180 Series              | 1        | 2.33%   |
| Prolific PL2305 Parallel Port        | 1        | 2.33%   |
| Pantum P2200 series                  | 1        | 2.33%   |
| Panasonic (Matsushita) KX-MB1500RU   | 1        | 2.33%   |
| HP OfficeJet Pro 9010 series         | 1        | 2.33%   |
| HP Officejet 4630 series             | 1        | 2.33%   |
| HP OfficeJet 3830 series             | 1        | 2.33%   |
| HP LaserJet Pro M202dw               | 1        | 2.33%   |
| HP LaserJet P2035                    | 1        | 2.33%   |
| HP LaserJet P2015 series             | 1        | 2.33%   |
| HP LaserJet P1102                    | 1        | 2.33%   |
| HP LaserJet M101-M106                | 1        | 2.33%   |
| HP LaserJet CP1025nw                 | 1        | 2.33%   |
| HP LaserJet 200 color M251nw         | 1        | 2.33%   |
| HP LaserJet 1022                     | 1        | 2.33%   |
| HP LaserJet 1018                     | 1        | 2.33%   |
| HP LaserJet 1010                     | 1        | 2.33%   |
| HP ENVY 4500 series                  | 1        | 2.33%   |
| HP Deskjet F4500 series              | 1        | 2.33%   |
| HP DeskJet 930c                      | 1        | 2.33%   |
| HP DeskJet 2700 series               | 1        | 2.33%   |
| HP DeskJet 2620 All-in-One Printer   | 1        | 2.33%   |
| HP Deskjet 2540 series               | 1        | 2.33%   |
| Canon PIXMA MP495                    | 1        | 2.33%   |
| Canon PIXMA MG2500 Series            | 1        | 2.33%   |
| Brother MFC-L3770CDW series          | 1        | 2.33%   |
| Brother MFC-L2710DW series           | 1        | 2.33%   |
| Brother MFC-J805DW                   | 1        | 2.33%   |
| Brother MFC-J491DW                   | 1        | 2.33%   |
| Brother MFC-9330CDW                  | 1        | 2.33%   |
| Brother MFC-7460DN                   | 1        | 2.33%   |
| Brother MFC-7420                     | 1        | 2.33%   |
| Brother HL-L2320D series             | 1        | 2.33%   |
| Brother HL-L2300D series             | 1        | 2.33%   |
| Brother HL-5340 series               | 1        | 2.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 3        | 50%     |
| Seiko Epson     | 2        | 33.33%  |
| Hewlett-Packard | 1        | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1        | 16.67%  |
| Seiko Epson ES-D200 [GT-S50]                            | 1        | 16.67%  |
| HP ScanJet G4010                                        | 1        | 16.67%  |
| Canon CanoScan LiDE 220                                 | 1        | 16.67%  |
| Canon CanoScan LiDE 120                                 | 1        | 16.67%  |
| Canon CanoScan LiDE 110                                 | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 63       | 41.72%  |
| Samsung Electronics           | 9        | 5.96%   |
| Microsoft                     | 9        | 5.96%   |
| Microdia                      | 9        | 5.96%   |
| Sunplus Innovation Technology | 5        | 3.31%   |
| KYE Systems (Mouse Systems)   | 5        | 3.31%   |
| Z-Star Microelectronics       | 4        | 2.65%   |
| MacroSilicon                  | 4        | 2.65%   |
| ARC International             | 4        | 2.65%   |
| Generalplus Technology        | 3        | 1.99%   |
| Chicony Electronics           | 3        | 1.99%   |
| Apple                         | 3        | 1.99%   |
| Alcor Micro                   | 3        | 1.99%   |
| Lenovo                        | 2        | 1.32%   |
| Huawei Technologies           | 2        | 1.32%   |
| Genesys Logic                 | 2        | 1.32%   |
| Cubeternet                    | 2        | 1.32%   |
| Creative Technology           | 2        | 1.32%   |
| Arkmicro Technologies         | 2        | 1.32%   |
| A4Tech                        | 2        | 1.32%   |
| Xiongmai                      | 1        | 0.66%   |
| Valve Software                | 1        | 0.66%   |
| Unknown                       | 1        | 0.66%   |
| Realtek Semiconductor         | 1        | 0.66%   |
| Razer USA                     | 1        | 0.66%   |
| Pixart Imaging                | 1        | 0.66%   |
| Philips (or NXP)              | 1        | 0.66%   |
| MediaTek                      | 1        | 0.66%   |
| lihappe8                      | 1        | 0.66%   |
| Intel                         | 1        | 0.66%   |
| HDR webcam                    | 1        | 0.66%   |
| HD 2MP WEBCAM                 | 1        | 0.66%   |
| GEMBIRD                       | 1        | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 15       | 9.68%   |
| Logitech HD Pro Webcam C920                    | 11       | 7.1%    |
| Samsung Galaxy A5 (MTP)                        | 8        | 5.16%   |
| Microsoft LifeCam HD-3000                      | 6        | 3.87%   |
| Logitech HD Webcam C615                        | 6        | 3.87%   |
| Logitech Webcam Pro 9000                       | 5        | 3.23%   |
| Microdia Webcam Vitade AF                      | 4        | 2.58%   |
| MacroSilicon USB Video                         | 4        | 2.58%   |
| Logitech HD Webcam C525                        | 4        | 2.58%   |
| ARC International Camera                       | 4        | 2.58%   |
| Microdia Camera                                | 3        | 1.94%   |
| Logitech Webcam C930e                          | 3        | 1.94%   |
| Logitech C922 Pro Stream Webcam                | 3        | 1.94%   |
| Z-Star Vimicro USB Camera (Altair)             | 2        | 1.29%   |
| Z-Star Venus USB2.0 Camera                     | 2        | 1.29%   |
| Microdia USB 2.0 Camera                        | 2        | 1.29%   |
| Logitech Webcam C210                           | 2        | 1.29%   |
| Logitech Webcam C200                           | 2        | 1.29%   |
| Logitech Webcam C170                           | 2        | 1.29%   |
| Logitech QuickCam Sphere                       | 2        | 1.29%   |
| Logitech B525 HD Webcam                        | 2        | 1.29%   |
| Lenovo FHD Webcam Audio                        | 2        | 1.29%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 2        | 1.29%   |
| Huawei UVC Camera                              | 2        | 1.29%   |
| Generalplus GENERAL WEBCAM                     | 2        | 1.29%   |
| Creative Live! Cam Chat HD [VF0700]            | 2        | 1.29%   |
| Arkmicro USB2.0 PC CAMERA                      | 2        | 1.29%   |
| Apple iPhone5/5C/5S/6                          | 2        | 1.29%   |
| Xiongmai web camera                            | 1        | 0.65%   |
| Valve Software 3D Camera                       | 1        | 0.65%   |
| Unknown Integrated RGB Camera                  | 1        | 0.65%   |
| Sunplus SPCA2650 AV Camera                     | 1        | 0.65%   |
| Sunplus NexiGo N930AF FHD Webcam               | 1        | 0.65%   |
| Sunplus Feeltek Full HD Webcam 1080P           | 1        | 0.65%   |
| Sunplus Aukey-PC-LM1E Camera                   | 1        | 0.65%   |
| Sunplus 2K FHD camera                          | 1        | 0.65%   |
| Samsung Galaxy (debugging mode)                | 1        | 0.65%   |
| Realtek USB Camera                             | 1        | 0.65%   |
| Razer USA Gaming Webcam [Kiyo]                 | 1        | 0.65%   |
| Pixart Imaging Webcam Genius iLook 300         | 1        | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| STMicroelectronics | 1        | 33.33%  |
| DigitalPersona     | 1        | 33.33%  |
| AuthenTec          | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader | 1        | 33.33%  |
| DigitalPersona Fingerprint Reader     | 1        | 33.33%  |
| AuthenTec AES1600                     | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| SCM Microsystems         | 2        | 15.38%  |
| Reiner SCT Kartensysteme | 2        | 15.38%  |
| OmniKey                  | 2        | 15.38%  |
| Alcor Micro              | 2        | 15.38%  |
| Advanced Card Systems    | 2        | 15.38%  |
| Gemalto (was Gemplus)    | 1        | 7.69%   |
| Aladdin R.D.             | 1        | 7.69%   |
| Aktiv                    | 1        | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader                               | 2        | 15.38%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 1        | 7.69%   |
| SCM Microsystems SCR331 SmartCard Reader                                   | 1        | 7.69%   |
| Reiner SCT Kartensysteme tanJack USB                                       | 1        | 7.69%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 7.69%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 7.69%   |
| OmniKey CardMan 1021                                                       | 1        | 7.69%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 1        | 7.69%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 7.69%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 1        | 7.69%   |
| Aladdin R.D. JaCarta                                                       | 1        | 7.69%   |
| Aktiv Rutoken lite                                                         | 1        | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 499      | 86.18%  |
| 1     | 65       | 11.23%  |
| 2     | 9        | 1.55%   |
| 4     | 4        | 0.69%   |
| 6     | 1        | 0.17%   |
| 3     | 1        | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 22       | 22.68%  |
| Net/wireless             | 17       | 17.53%  |
| Unassigned class         | 11       | 11.34%  |
| Sound                    | 11       | 11.34%  |
| Camera                   | 10       | 10.31%  |
| Chipcard                 | 5        | 5.15%   |
| Bluetooth                | 5        | 5.15%   |
| Communication controller | 4        | 4.12%   |
| Multimedia controller    | 3        | 3.09%   |
| Fingerprint reader       | 3        | 3.09%   |
| Network                  | 2        | 2.06%   |
| Storage/ide              | 1        | 1.03%   |
| Net/ethernet             | 1        | 1.03%   |
| Firewire controller      | 1        | 1.03%   |
| Card reader              | 1        | 1.03%   |

