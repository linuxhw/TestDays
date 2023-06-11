Linux in Belgium - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Belgium.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Belgium/Desktop/README.md) and [notebooks](/Location/Belgium/Notebook/README.md).

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

Total: 2757

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Notebook      | NS50_70MU                   | Notebook    | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [b46a96183b](https://linux-hardware.org/?probe=b46a96183b) | Jun 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [a302ecd3cd](https://linux-hardware.org/?probe=a302ecd3cd) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [43c70efbe7](https://linux-hardware.org/?probe=43c70efbe7) | Jun 05, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [9a66179aaf](https://linux-hardware.org/?probe=9a66179aaf) | Jun 04, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [bfe6623b23](https://linux-hardware.org/?probe=bfe6623b23) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [c3dae64ee6](https://linux-hardware.org/?probe=c3dae64ee6) | Jun 03, 2023 |
| MSI           | 890FXA-GD70                 | Desktop     | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [3fb05bfb0b](https://linux-hardware.org/?probe=3fb05bfb0b) | May 31, 2023 |
| Dell          | Latitude 5510               | Notebook    | [78bd1ae0e0](https://linux-hardware.org/?probe=78bd1ae0e0) | May 31, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [3718997542](https://linux-hardware.org/?probe=3718997542) | May 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [caa2968187](https://linux-hardware.org/?probe=caa2968187) | May 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [8ec80f5e43](https://linux-hardware.org/?probe=8ec80f5e43) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [1aa973f6bc](https://linux-hardware.org/?probe=1aa973f6bc) | May 28, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [fd8a08639d](https://linux-hardware.org/?probe=fd8a08639d) | May 28, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9cbdd21a81](https://linux-hardware.org/?probe=9cbdd21a81) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [76a357994a](https://linux-hardware.org/?probe=76a357994a) | May 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [21653cfe83](https://linux-hardware.org/?probe=21653cfe83) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [41755306e6](https://linux-hardware.org/?probe=41755306e6) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [5a4cf4d2e3](https://linux-hardware.org/?probe=5a4cf4d2e3) | May 23, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [a7794f4f9e](https://linux-hardware.org/?probe=a7794f4f9e) | May 21, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| HP            | Elite x2 1013 G3            | Tablet      | [0da06960ac](https://linux-hardware.org/?probe=0da06960ac) | May 19, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [0dadbeca5b](https://linux-hardware.org/?probe=0dadbeca5b) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [0de060a93f](https://linux-hardware.org/?probe=0de060a93f) | May 18, 2023 |
| HP            | 0A54h                       | Desktop     | [76953e42f8](https://linux-hardware.org/?probe=76953e42f8) | May 18, 2023 |
| MSI           | GS70 2PC Stealth            | Notebook    | [254f42a469](https://linux-hardware.org/?probe=254f42a469) | May 18, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [05379205f4](https://linux-hardware.org/?probe=05379205f4) | May 18, 2023 |
| HP            | 620                         | Notebook    | [6b688ce696](https://linux-hardware.org/?probe=6b688ce696) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [874dcebbaa](https://linux-hardware.org/?probe=874dcebbaa) | May 17, 2023 |
| Dell          | 0M3F6C A01                  | Desktop     | [d0fc9b65d0](https://linux-hardware.org/?probe=d0fc9b65d0) | May 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1b931dc36f](https://linux-hardware.org/?probe=1b931dc36f) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [af16278f1e](https://linux-hardware.org/?probe=af16278f1e) | May 17, 2023 |
| Emdoor        | AG958                       | Notebook    | [7ff5858830](https://linux-hardware.org/?probe=7ff5858830) | May 17, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f97e4e7fc1](https://linux-hardware.org/?probe=f97e4e7fc1) | May 15, 2023 |
| Medion        | Akoya P6660 MD99790         | Notebook    | [20ecc9b5dc](https://linux-hardware.org/?probe=20ecc9b5dc) | May 15, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [8e0efa6d0a](https://linux-hardware.org/?probe=8e0efa6d0a) | May 14, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [ced38114fc](https://linux-hardware.org/?probe=ced38114fc) | May 14, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [4bde221d90](https://linux-hardware.org/?probe=4bde221d90) | May 13, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [0a23198016](https://linux-hardware.org/?probe=0a23198016) | May 13, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [c0841ef7e1](https://linux-hardware.org/?probe=c0841ef7e1) | May 12, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [ed18615cb3](https://linux-hardware.org/?probe=ed18615cb3) | May 11, 2023 |
| Medion        | E2292                       | Convertible | [116727a473](https://linux-hardware.org/?probe=116727a473) | May 11, 2023 |
| FriendlyEl... | NanoPi NEO3                 | Soc         | [5384ed47e6](https://linux-hardware.org/?probe=5384ed47e6) | May 10, 2023 |
| FriendlyEl... | NanoPi NEO3                 | Soc         | [c182a0679c](https://linux-hardware.org/?probe=c182a0679c) | May 10, 2023 |
| ASUSTek       | UX410UAK                    | Notebook    | [d68a2bc7c0](https://linux-hardware.org/?probe=d68a2bc7c0) | May 10, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9ce4debe84](https://linux-hardware.org/?probe=9ce4debe84) | May 09, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [434f1425a4](https://linux-hardware.org/?probe=434f1425a4) | May 09, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [9a4e4763d4](https://linux-hardware.org/?probe=9a4e4763d4) | May 09, 2023 |
| MSI           | Katana 17 B12UCXK           | Notebook    | [15b9d97c10](https://linux-hardware.org/?probe=15b9d97c10) | May 09, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [e7ffe2585f](https://linux-hardware.org/?probe=e7ffe2585f) | May 09, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [29d129229b](https://linux-hardware.org/?probe=29d129229b) | May 08, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [ddf0cb8a28](https://linux-hardware.org/?probe=ddf0cb8a28) | May 08, 2023 |
| Dell          | Latitude 7390               | Notebook    | [dc5c96e431](https://linux-hardware.org/?probe=dc5c96e431) | May 08, 2023 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | Desktop     | [2a26d32cc3](https://linux-hardware.org/?probe=2a26d32cc3) | May 07, 2023 |
| MSI           | CR61 3M                     | Notebook    | [f41852fa6e](https://linux-hardware.org/?probe=f41852fa6e) | May 07, 2023 |
| MSI           | CR61 3M                     | Notebook    | [7b5d49d859](https://linux-hardware.org/?probe=7b5d49d859) | May 07, 2023 |
| MSI           | GS70 2PC Stealth            | Notebook    | [370f9304b6](https://linux-hardware.org/?probe=370f9304b6) | May 07, 2023 |
| Intel         | DP43TF AAE34878-403         | Desktop     | [9d5ca00c7c](https://linux-hardware.org/?probe=9d5ca00c7c) | May 07, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [6bea90b569](https://linux-hardware.org/?probe=6bea90b569) | May 07, 2023 |
| Intel         | DP43TF AAE34878-403         | Desktop     | [6353d110f5](https://linux-hardware.org/?probe=6353d110f5) | May 07, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [db0ab14831](https://linux-hardware.org/?probe=db0ab14831) | May 07, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [1eddb3203a](https://linux-hardware.org/?probe=1eddb3203a) | May 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [2e02937097](https://linux-hardware.org/?probe=2e02937097) | May 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [051da44921](https://linux-hardware.org/?probe=051da44921) | May 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6a54ace5f8](https://linux-hardware.org/?probe=6a54ace5f8) | May 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [68c7b6891b](https://linux-hardware.org/?probe=68c7b6891b) | May 06, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [b0464a0b99](https://linux-hardware.org/?probe=b0464a0b99) | May 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c490e68d59](https://linux-hardware.org/?probe=c490e68d59) | May 03, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [16ac84221b](https://linux-hardware.org/?probe=16ac84221b) | May 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [29636a9923](https://linux-hardware.org/?probe=29636a9923) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [7bb2ae638b](https://linux-hardware.org/?probe=7bb2ae638b) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [bd0458e8a9](https://linux-hardware.org/?probe=bd0458e8a9) | May 01, 2023 |
| Medion        | P6630                       | Notebook    | [93abad41dd](https://linux-hardware.org/?probe=93abad41dd) | Apr 30, 2023 |
| Dell          | Latitude 5521               | Notebook    | [1629b4efc4](https://linux-hardware.org/?probe=1629b4efc4) | Apr 30, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [ff24454021](https://linux-hardware.org/?probe=ff24454021) | Apr 29, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [fa805f77f7](https://linux-hardware.org/?probe=fa805f77f7) | Apr 29, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [9081fc703d](https://linux-hardware.org/?probe=9081fc703d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S56G00    | Notebook    | [8da21e9a17](https://linux-hardware.org/?probe=8da21e9a17) | Apr 28, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [f8aee85cd4](https://linux-hardware.org/?probe=f8aee85cd4) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d138bfdf52](https://linux-hardware.org/?probe=d138bfdf52) | Apr 28, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [f4d7a6ed92](https://linux-hardware.org/?probe=f4d7a6ed92) | Apr 28, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [15b900cf50](https://linux-hardware.org/?probe=15b900cf50) | Apr 27, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [d5b1ec921a](https://linux-hardware.org/?probe=d5b1ec921a) | Apr 27, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [de581801e8](https://linux-hardware.org/?probe=de581801e8) | Apr 27, 2023 |
| Dell          | Latitude E6440              | Notebook    | [d55c77598b](https://linux-hardware.org/?probe=d55c77598b) | Apr 27, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [cb64c7f963](https://linux-hardware.org/?probe=cb64c7f963) | Apr 25, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | Notebook    | [2e542c241d](https://linux-hardware.org/?probe=2e542c241d) | Apr 25, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [0e79aaac72](https://linux-hardware.org/?probe=0e79aaac72) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | Notebook    | [587e06aeb7](https://linux-hardware.org/?probe=587e06aeb7) | Apr 24, 2023 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [d7e9027e6a](https://linux-hardware.org/?probe=d7e9027e6a) | Apr 24, 2023 |
| Emdoor        | AG958                       | Notebook    | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [60251e08f5](https://linux-hardware.org/?probe=60251e08f5) | Apr 22, 2023 |
| Dell          | Latitude E6330              | Notebook    | [b532a9756c](https://linux-hardware.org/?probe=b532a9756c) | Apr 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [d342e4d24c](https://linux-hardware.org/?probe=d342e4d24c) | Apr 22, 2023 |
| Emdoor        | AG958                       | Notebook    | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | Notebook    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [841c2f241b](https://linux-hardware.org/?probe=841c2f241b) | Apr 19, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [e3ebb38e6b](https://linux-hardware.org/?probe=e3ebb38e6b) | Apr 19, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [5b77cc21f4](https://linux-hardware.org/?probe=5b77cc21f4) | Apr 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [efdcb6b99e](https://linux-hardware.org/?probe=efdcb6b99e) | Apr 18, 2023 |
| Dell          | 0J4NFV A01                  | Desktop     | [a6b3ac3ff2](https://linux-hardware.org/?probe=a6b3ac3ff2) | Apr 17, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [38aeb226af](https://linux-hardware.org/?probe=38aeb226af) | Apr 17, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [1a55ffc593](https://linux-hardware.org/?probe=1a55ffc593) | Apr 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [7230f64c9b](https://linux-hardware.org/?probe=7230f64c9b) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [a7f312ea0a](https://linux-hardware.org/?probe=a7f312ea0a) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [f1afe43806](https://linux-hardware.org/?probe=f1afe43806) | Apr 16, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [f44bbda528](https://linux-hardware.org/?probe=f44bbda528) | Apr 16, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [6ac02f43f2](https://linux-hardware.org/?probe=6ac02f43f2) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7c35c1ba82](https://linux-hardware.org/?probe=7c35c1ba82) | Apr 15, 2023 |
| HP            | 0A5Ch                       | Desktop     | [636d94a346](https://linux-hardware.org/?probe=636d94a346) | Apr 15, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | Notebook    | [b87471108a](https://linux-hardware.org/?probe=b87471108a) | Apr 14, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [43d0d0a55e](https://linux-hardware.org/?probe=43d0d0a55e) | Apr 14, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [721a60ff30](https://linux-hardware.org/?probe=721a60ff30) | Apr 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS29J05    | Notebook    | [60c50f0a10](https://linux-hardware.org/?probe=60c50f0a10) | Apr 13, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [6037aee790](https://linux-hardware.org/?probe=6037aee790) | Apr 11, 2023 |
| Sony          | SVE1713A1EW                 | Notebook    | [402fae93d5](https://linux-hardware.org/?probe=402fae93d5) | Apr 09, 2023 |
| MSI           | B150M BAZOOKA               | Desktop     | [ce60e4a299](https://linux-hardware.org/?probe=ce60e4a299) | Apr 08, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [269e742eb7](https://linux-hardware.org/?probe=269e742eb7) | Apr 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b220308aa1](https://linux-hardware.org/?probe=b220308aa1) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [00fef3bb7b](https://linux-hardware.org/?probe=00fef3bb7b) | Apr 06, 2023 |
| HP            | 620                         | Notebook    | [ad46cdbb0d](https://linux-hardware.org/?probe=ad46cdbb0d) | Apr 06, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | Notebook    | [d9d2e73619](https://linux-hardware.org/?probe=d9d2e73619) | Apr 05, 2023 |
| Medion        | BTDD-EAIO                   | All in one  | [2bbf3378ef](https://linux-hardware.org/?probe=2bbf3378ef) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [8eb8bb5119](https://linux-hardware.org/?probe=8eb8bb5119) | Apr 03, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [95a98c59b1](https://linux-hardware.org/?probe=95a98c59b1) | Apr 03, 2023 |
| Clevo         | P170HMx                     | Notebook    | [c963b350fc](https://linux-hardware.org/?probe=c963b350fc) | Apr 03, 2023 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [0aefaba90e](https://linux-hardware.org/?probe=0aefaba90e) | Apr 03, 2023 |
| HP            | 8430 1000                   | All in one  | [380754e2f6](https://linux-hardware.org/?probe=380754e2f6) | Apr 02, 2023 |
| HP            | 3397                        | Desktop     | [04943f0d5f](https://linux-hardware.org/?probe=04943f0d5f) | Apr 02, 2023 |
| AZW           | Speed S                     | Notebook    | [52292a4968](https://linux-hardware.org/?probe=52292a4968) | Apr 02, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [12319c9ee3](https://linux-hardware.org/?probe=12319c9ee3) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [98cd4ea3a6](https://linux-hardware.org/?probe=98cd4ea3a6) | Apr 01, 2023 |
| HP            | Pavilion g7                 | Notebook    | [7820d2ca67](https://linux-hardware.org/?probe=7820d2ca67) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [4787e68a9c](https://linux-hardware.org/?probe=4787e68a9c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [12e105f6da](https://linux-hardware.org/?probe=12e105f6da) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [0ff3ab318e](https://linux-hardware.org/?probe=0ff3ab318e) | Mar 31, 2023 |
| HP            | Compaq 6730b (GB987ET#UU... | Notebook    | [6c6ceb9bc3](https://linux-hardware.org/?probe=6c6ceb9bc3) | Mar 31, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [01492665ee](https://linux-hardware.org/?probe=01492665ee) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0b4fae8189](https://linux-hardware.org/?probe=0b4fae8189) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [13acfd725a](https://linux-hardware.org/?probe=13acfd725a) | Mar 31, 2023 |
| Medion        | MS-7728                     | Desktop     | [cf66e81623](https://linux-hardware.org/?probe=cf66e81623) | Mar 31, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [c73c5374a4](https://linux-hardware.org/?probe=c73c5374a4) | Mar 30, 2023 |
| Medion        | P8614                       | Notebook    | [a66fe7042e](https://linux-hardware.org/?probe=a66fe7042e) | Mar 29, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7e04c0e7cd](https://linux-hardware.org/?probe=7e04c0e7cd) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [0ab4054ab9](https://linux-hardware.org/?probe=0ab4054ab9) | Mar 26, 2023 |
| MSI           | GT70                        | Notebook    | [8b00b28b12](https://linux-hardware.org/?probe=8b00b28b12) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [fe5c568f41](https://linux-hardware.org/?probe=fe5c568f41) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [778f5948f1](https://linux-hardware.org/?probe=778f5948f1) | Mar 26, 2023 |
| Dell          | Latitude E6330              | Notebook    | [32833b4683](https://linux-hardware.org/?probe=32833b4683) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | Desktop     | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eeeac5db0f](https://linux-hardware.org/?probe=eeeac5db0f) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [311e49c553](https://linux-hardware.org/?probe=311e49c553) | Mar 23, 2023 |
| Alienware     | m17 R3                      | Notebook    | [6c62c223ed](https://linux-hardware.org/?probe=6c62c223ed) | Mar 21, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [7622701d31](https://linux-hardware.org/?probe=7622701d31) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [846f31de3e](https://linux-hardware.org/?probe=846f31de3e) | Mar 21, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| HP            | Pavilion g7                 | Notebook    | [e591ea2173](https://linux-hardware.org/?probe=e591ea2173) | Mar 19, 2023 |
| Acer          | Aspire XC-705               | Desktop     | [2ef61db0a6](https://linux-hardware.org/?probe=2ef61db0a6) | Mar 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [837ed83646](https://linux-hardware.org/?probe=837ed83646) | Mar 18, 2023 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5a70cf923e](https://linux-hardware.org/?probe=5a70cf923e) | Mar 18, 2023 |
| Lenovo        | ThinkPad W510 4389AP5       | Notebook    | [1825764856](https://linux-hardware.org/?probe=1825764856) | Mar 17, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [7ab2e7b0ab](https://linux-hardware.org/?probe=7ab2e7b0ab) | Mar 16, 2023 |
| Intel         | NUC8i7HVB J68196-602        | Mini pc     | [68b65fda4c](https://linux-hardware.org/?probe=68b65fda4c) | Mar 15, 2023 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [13a4e703dc](https://linux-hardware.org/?probe=13a4e703dc) | Mar 14, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [cde6fff1ad](https://linux-hardware.org/?probe=cde6fff1ad) | Mar 13, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [f762c7cc29](https://linux-hardware.org/?probe=f762c7cc29) | Mar 13, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | Notebook    | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| Lenovo        | ThinkPad W510 4389AP5       | Notebook    | [2c01c1fd0e](https://linux-hardware.org/?probe=2c01c1fd0e) | Mar 11, 2023 |
| MSI           | H270 GAMING M3              | Desktop     | [dfbb481b02](https://linux-hardware.org/?probe=dfbb481b02) | Mar 11, 2023 |
| Medion        | Akoya E1318T                | Notebook    | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| ASUSTek       | K52F                        | Notebook    | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [a63cd6d4aa](https://linux-hardware.org/?probe=a63cd6d4aa) | Mar 09, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [0dc84b30aa](https://linux-hardware.org/?probe=0dc84b30aa) | Mar 09, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [72eed5b458](https://linux-hardware.org/?probe=72eed5b458) | Mar 08, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [1563e26ae3](https://linux-hardware.org/?probe=1563e26ae3) | Mar 07, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [44b690055c](https://linux-hardware.org/?probe=44b690055c) | Mar 07, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [d595ae284e](https://linux-hardware.org/?probe=d595ae284e) | Mar 07, 2023 |
| Alienware     | x14                         | Notebook    | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8f08518290](https://linux-hardware.org/?probe=8f08518290) | Mar 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [819f8b1cad](https://linux-hardware.org/?probe=819f8b1cad) | Mar 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [e560390e4f](https://linux-hardware.org/?probe=e560390e4f) | Mar 05, 2023 |
| Lenovo        | ThinkCentre XXXX 739527G    | Desktop     | [c3e39b21f9](https://linux-hardware.org/?probe=c3e39b21f9) | Mar 05, 2023 |
| Acer          | Aspire 6530G                | Notebook    | [a4077c8432](https://linux-hardware.org/?probe=a4077c8432) | Mar 05, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c2f98c3014](https://linux-hardware.org/?probe=c2f98c3014) | Mar 05, 2023 |
| Toshiba       | Satellite C855-112          | Notebook    | [8635f2eecd](https://linux-hardware.org/?probe=8635f2eecd) | Mar 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [d850dacb6a](https://linux-hardware.org/?probe=d850dacb6a) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ac3640b913](https://linux-hardware.org/?probe=ac3640b913) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [0cd2798326](https://linux-hardware.org/?probe=0cd2798326) | Mar 03, 2023 |
| HP            | 620                         | Notebook    | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a877190b1c](https://linux-hardware.org/?probe=a877190b1c) | Mar 02, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [639a660b02](https://linux-hardware.org/?probe=639a660b02) | Mar 02, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [f441cc82e4](https://linux-hardware.org/?probe=f441cc82e4) | Mar 01, 2023 |
| ASUSTek       | F70SL                       | Notebook    | [5870cf8326](https://linux-hardware.org/?probe=5870cf8326) | Mar 01, 2023 |
| Dell          | Latitude 5530               | Notebook    | [b1d7964fc7](https://linux-hardware.org/?probe=b1d7964fc7) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9ba7cfbdeb](https://linux-hardware.org/?probe=9ba7cfbdeb) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [fa757fb12a](https://linux-hardware.org/?probe=fa757fb12a) | Mar 01, 2023 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [0de52a6150](https://linux-hardware.org/?probe=0de52a6150) | Feb 28, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [0710c7be6e](https://linux-hardware.org/?probe=0710c7be6e) | Feb 28, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [057c307bf5](https://linux-hardware.org/?probe=057c307bf5) | Feb 28, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [4acd4aa811](https://linux-hardware.org/?probe=4acd4aa811) | Feb 27, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [068ad292bd](https://linux-hardware.org/?probe=068ad292bd) | Feb 27, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [41330b2783](https://linux-hardware.org/?probe=41330b2783) | Feb 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [de7aec7f12](https://linux-hardware.org/?probe=de7aec7f12) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e7bf168729](https://linux-hardware.org/?probe=e7bf168729) | Feb 25, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [e257e205bf](https://linux-hardware.org/?probe=e257e205bf) | Feb 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a53235325f](https://linux-hardware.org/?probe=a53235325f) | Feb 23, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [950130a7b4](https://linux-hardware.org/?probe=950130a7b4) | Feb 23, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [c2117fed20](https://linux-hardware.org/?probe=c2117fed20) | Feb 22, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [abfe4c823a](https://linux-hardware.org/?probe=abfe4c823a) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | Notebook    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7e5789e02b](https://linux-hardware.org/?probe=7e5789e02b) | Feb 21, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJA0... | Convertible | [aba497a637](https://linux-hardware.org/?probe=aba497a637) | Feb 21, 2023 |
| HP            | 1850                        | Desktop     | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [da5050e2f8](https://linux-hardware.org/?probe=da5050e2f8) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [b335ec1cc3](https://linux-hardware.org/?probe=b335ec1cc3) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | Notebook    | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Medion        | MS-7800                     | Desktop     | [2f542347f9](https://linux-hardware.org/?probe=2f542347f9) | Feb 19, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [9eca2efc88](https://linux-hardware.org/?probe=9eca2efc88) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | Notebook    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [831d4806fb](https://linux-hardware.org/?probe=831d4806fb) | Feb 18, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [09b0c2bf17](https://linux-hardware.org/?probe=09b0c2bf17) | Feb 17, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Notebook    | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [caeb6bc93f](https://linux-hardware.org/?probe=caeb6bc93f) | Feb 17, 2023 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [4a92de7e43](https://linux-hardware.org/?probe=4a92de7e43) | Feb 17, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| Alienware     | 17 R2                       | Notebook    | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [2b0904349a](https://linux-hardware.org/?probe=2b0904349a) | Feb 16, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e718a6af67](https://linux-hardware.org/?probe=e718a6af67) | Feb 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [01319ac289](https://linux-hardware.org/?probe=01319ac289) | Feb 13, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [2a14385869](https://linux-hardware.org/?probe=2a14385869) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [c0d18ab501](https://linux-hardware.org/?probe=c0d18ab501) | Feb 12, 2023 |
| Packard Be... | DOT S                       | Notebook    | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| Dell          | Latitude E6330              | Notebook    | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [9c458e5a66](https://linux-hardware.org/?probe=9c458e5a66) | Feb 11, 2023 |
| Acer          | Aspire V5-122               | Notebook    | [99fd12250b](https://linux-hardware.org/?probe=99fd12250b) | Feb 10, 2023 |
| Teclast       | F15S                        | Notebook    | [951ded8432](https://linux-hardware.org/?probe=951ded8432) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [26fb33ec6c](https://linux-hardware.org/?probe=26fb33ec6c) | Feb 08, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [997020aeb0](https://linux-hardware.org/?probe=997020aeb0) | Feb 08, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [c90f2404df](https://linux-hardware.org/?probe=c90f2404df) | Feb 08, 2023 |
| Dell          | 06JWJY A01                  | Desktop     | [ee53c6f627](https://linux-hardware.org/?probe=ee53c6f627) | Feb 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [870ba1caa7](https://linux-hardware.org/?probe=870ba1caa7) | Feb 07, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [81ece9483e](https://linux-hardware.org/?probe=81ece9483e) | Feb 07, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| Medion        | P6624                       | Notebook    | [5a31124376](https://linux-hardware.org/?probe=5a31124376) | Feb 06, 2023 |
| BESSTAR Te... | CB9                         | Mini pc     | [23fe29b164](https://linux-hardware.org/?probe=23fe29b164) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | GL703VD                     | Notebook    | [62e1e79469](https://linux-hardware.org/?probe=62e1e79469) | Feb 03, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [a630801a13](https://linux-hardware.org/?probe=a630801a13) | Feb 03, 2023 |
| Dell          | Precision 7550              | Notebook    | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [72bdb7165c](https://linux-hardware.org/?probe=72bdb7165c) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [2261a77abb](https://linux-hardware.org/?probe=2261a77abb) | Feb 01, 2023 |
| Google        | Pantheon                    | Notebook    | [12e0b96dd1](https://linux-hardware.org/?probe=12e0b96dd1) | Feb 01, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [8641149603](https://linux-hardware.org/?probe=8641149603) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [f6be582448](https://linux-hardware.org/?probe=f6be582448) | Jan 30, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [358b908129](https://linux-hardware.org/?probe=358b908129) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| HP            | 89E9 0100                   | All in one  | [f5311b2134](https://linux-hardware.org/?probe=f5311b2134) | Jan 28, 2023 |
| HP            | 89E9 0100                   | All in one  | [4afdd5b9fc](https://linux-hardware.org/?probe=4afdd5b9fc) | Jan 28, 2023 |
| Acer          | Peppy                       | Notebook    | [9a16262be8](https://linux-hardware.org/?probe=9a16262be8) | Jan 27, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [77a6b88d58](https://linux-hardware.org/?probe=77a6b88d58) | Jan 27, 2023 |
| Intel         | DG965SS AAD41678-306        | Desktop     | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| MSI           | Z270 GAMING M5              | Desktop     | [218f278cab](https://linux-hardware.org/?probe=218f278cab) | Jan 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [85ad9c7e62](https://linux-hardware.org/?probe=85ad9c7e62) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| HP            | 304Ah                       | Desktop     | [a41a25807f](https://linux-hardware.org/?probe=a41a25807f) | Jan 25, 2023 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [37c4aa5f03](https://linux-hardware.org/?probe=37c4aa5f03) | Jan 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [2c8424ac3d](https://linux-hardware.org/?probe=2c8424ac3d) | Jan 22, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [19bb445ee4](https://linux-hardware.org/?probe=19bb445ee4) | Jan 22, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [6228476153](https://linux-hardware.org/?probe=6228476153) | Jan 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [c228c064b7](https://linux-hardware.org/?probe=c228c064b7) | Jan 20, 2023 |
| Medion        | P6624                       | Notebook    | [344d427f44](https://linux-hardware.org/?probe=344d427f44) | Jan 20, 2023 |
| HP            | 843B                        | Desktop     | [2af17234ba](https://linux-hardware.org/?probe=2af17234ba) | Jan 20, 2023 |
| Dell          | Latitude 5320               | Notebook    | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [9476823c0b](https://linux-hardware.org/?probe=9476823c0b) | Jan 19, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| MSI           | Katana GF76 11UC            | Notebook    | [8c0b32cf24](https://linux-hardware.org/?probe=8c0b32cf24) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f3b27e21a7](https://linux-hardware.org/?probe=f3b27e21a7) | Jan 16, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [c06c7eedaf](https://linux-hardware.org/?probe=c06c7eedaf) | Jan 16, 2023 |
| Medion        | MS-7501                     | Desktop     | [abd269d539](https://linux-hardware.org/?probe=abd269d539) | Jan 15, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9fe6c51640](https://linux-hardware.org/?probe=9fe6c51640) | Jan 15, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [e3b9b73877](https://linux-hardware.org/?probe=e3b9b73877) | Jan 14, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [406649acdf](https://linux-hardware.org/?probe=406649acdf) | Jan 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [5047da7461](https://linux-hardware.org/?probe=5047da7461) | Jan 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f59adc6dcd](https://linux-hardware.org/?probe=f59adc6dcd) | Jan 13, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [bbecf2579c](https://linux-hardware.org/?probe=bbecf2579c) | Jan 13, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [425fb5340d](https://linux-hardware.org/?probe=425fb5340d) | Jan 13, 2023 |
| HP            | 3397                        | Desktop     | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | Notebook    | [10c4bcf564](https://linux-hardware.org/?probe=10c4bcf564) | Jan 12, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [60c16871ac](https://linux-hardware.org/?probe=60c16871ac) | Jan 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8193577e0b](https://linux-hardware.org/?probe=8193577e0b) | Jan 11, 2023 |
| HP            | Pavilion dv6000 (RY604EA... | Notebook    | [a8ec5eb86a](https://linux-hardware.org/?probe=a8ec5eb86a) | Jan 11, 2023 |
| Acer          | Aspire 7560                 | Notebook    | [58cd9d7ad2](https://linux-hardware.org/?probe=58cd9d7ad2) | Jan 09, 2023 |
| Dell          | XPS L521X                   | Notebook    | [2930493243](https://linux-hardware.org/?probe=2930493243) | Jan 09, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [e6cb9446f5](https://linux-hardware.org/?probe=e6cb9446f5) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [8ec4c19bf3](https://linux-hardware.org/?probe=8ec4c19bf3) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [0f1543c21d](https://linux-hardware.org/?probe=0f1543c21d) | Jan 09, 2023 |
| Notebook      | P7xxDM3(-G)                 | Notebook    | [7cafa98138](https://linux-hardware.org/?probe=7cafa98138) | Jan 08, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d1eaa576e7](https://linux-hardware.org/?probe=d1eaa576e7) | Jan 07, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [4673ec60ea](https://linux-hardware.org/?probe=4673ec60ea) | Jan 07, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [cbd020e86f](https://linux-hardware.org/?probe=cbd020e86f) | Jan 07, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [bb893b2d93](https://linux-hardware.org/?probe=bb893b2d93) | Jan 07, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [89eccb038f](https://linux-hardware.org/?probe=89eccb038f) | Jan 06, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0232b39536](https://linux-hardware.org/?probe=0232b39536) | Jan 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [458cb8c4de](https://linux-hardware.org/?probe=458cb8c4de) | Jan 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a84d0d7b42](https://linux-hardware.org/?probe=a84d0d7b42) | Jan 06, 2023 |
| Medion        | S4214                       | Notebook    | [58131e715e](https://linux-hardware.org/?probe=58131e715e) | Jan 06, 2023 |
| HP            | Pavilion g7                 | Notebook    | [9f029a8cdb](https://linux-hardware.org/?probe=9f029a8cdb) | Jan 06, 2023 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [b1911d1ae5](https://linux-hardware.org/?probe=b1911d1ae5) | Jan 01, 2023 |
| Dell          | System XPS L702X            | Notebook    | [7030c340cc](https://linux-hardware.org/?probe=7030c340cc) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0A    | Notebook    | [82168627b7](https://linux-hardware.org/?probe=82168627b7) | Dec 31, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [28822be06e](https://linux-hardware.org/?probe=28822be06e) | Dec 29, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| HP            | Notebook                    | Notebook    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Acer          | Aspire M3920                | Desktop     | [49cb4f51a8](https://linux-hardware.org/?probe=49cb4f51a8) | Dec 28, 2022 |
| Dell          | Latitude 5580               | Notebook    | [7c006e8c6d](https://linux-hardware.org/?probe=7c006e8c6d) | Dec 28, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [bf50da5153](https://linux-hardware.org/?probe=bf50da5153) | Dec 28, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [415c0ff63e](https://linux-hardware.org/?probe=415c0ff63e) | Dec 27, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [9eee40dd50](https://linux-hardware.org/?probe=9eee40dd50) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [5d26c7c543](https://linux-hardware.org/?probe=5d26c7c543) | Dec 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9811949dd](https://linux-hardware.org/?probe=e9811949dd) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| HP            | 0AACh                       | Desktop     | [b83da338ee](https://linux-hardware.org/?probe=b83da338ee) | Dec 25, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| HP            | Stream x360 Convertible ... | Convertible | [e01713ca07](https://linux-hardware.org/?probe=e01713ca07) | Dec 24, 2022 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [355d32cbac](https://linux-hardware.org/?probe=355d32cbac) | Dec 24, 2022 |
| HP            | 0AACh                       | Desktop     | [4a7840e1cf](https://linux-hardware.org/?probe=4a7840e1cf) | Dec 24, 2022 |
| HP            | Pavilion g7                 | Notebook    | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| Sony          | SVS1311N9ES                 | Notebook    | [5c1a4bed5b](https://linux-hardware.org/?probe=5c1a4bed5b) | Dec 24, 2022 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d407c538c4](https://linux-hardware.org/?probe=d407c538c4) | Dec 24, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [59d46f37db](https://linux-hardware.org/?probe=59d46f37db) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a2d763d722](https://linux-hardware.org/?probe=a2d763d722) | Dec 21, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [60683b36c2](https://linux-hardware.org/?probe=60683b36c2) | Dec 20, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [d854f4c5ad](https://linux-hardware.org/?probe=d854f4c5ad) | Dec 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [2f061a6d8d](https://linux-hardware.org/?probe=2f061a6d8d) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Dell          | 0D6H9T A03                  | Desktop     | [835cdeea5e](https://linux-hardware.org/?probe=835cdeea5e) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | Notebook    | [6c56016ed0](https://linux-hardware.org/?probe=6c56016ed0) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | Notebook    | [abd93a5cca](https://linux-hardware.org/?probe=abd93a5cca) | Dec 19, 2022 |
| HP            | ProBook 6570b               | Notebook    | [4deb8fc518](https://linux-hardware.org/?probe=4deb8fc518) | Dec 19, 2022 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [3684f593d4](https://linux-hardware.org/?probe=3684f593d4) | Dec 18, 2022 |
| Lenovo        | 3716 SDK0T76461 WIN 3422... | Desktop     | [15f724ada5](https://linux-hardware.org/?probe=15f724ada5) | Dec 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [9c513daaf3](https://linux-hardware.org/?probe=9c513daaf3) | Dec 17, 2022 |
| Medion        | WIM2210                     | Notebook    | [d1a64f7b3b](https://linux-hardware.org/?probe=d1a64f7b3b) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3db1266e41](https://linux-hardware.org/?probe=3db1266e41) | Dec 17, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [c17bee3b4a](https://linux-hardware.org/?probe=c17bee3b4a) | Dec 17, 2022 |
| Lenovo        | ThinkPad T570 20H9S04C00    | Notebook    | [f3093ba13c](https://linux-hardware.org/?probe=f3093ba13c) | Dec 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [26aae3342c](https://linux-hardware.org/?probe=26aae3342c) | Dec 16, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [4e9bbbaa1f](https://linux-hardware.org/?probe=4e9bbbaa1f) | Dec 16, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1398958777](https://linux-hardware.org/?probe=1398958777) | Dec 14, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [88c6ca8956](https://linux-hardware.org/?probe=88c6ca8956) | Dec 14, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e008a86cd5](https://linux-hardware.org/?probe=e008a86cd5) | Dec 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [45efd7615d](https://linux-hardware.org/?probe=45efd7615d) | Dec 12, 2022 |
| Lenovo        | ThinkPad T430 2349L26       | Notebook    | [9d0bcbdc75](https://linux-hardware.org/?probe=9d0bcbdc75) | Dec 11, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [5749b67534](https://linux-hardware.org/?probe=5749b67534) | Dec 10, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [d1b6c31805](https://linux-hardware.org/?probe=d1b6c31805) | Dec 09, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [69e83bcd80](https://linux-hardware.org/?probe=69e83bcd80) | Dec 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9d240437ee](https://linux-hardware.org/?probe=9d240437ee) | Dec 08, 2022 |
| Lenovo        | ThinkPad T520 4243CJ2       | Notebook    | [93e5e0ca9b](https://linux-hardware.org/?probe=93e5e0ca9b) | Dec 08, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [7ba193202d](https://linux-hardware.org/?probe=7ba193202d) | Dec 08, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [5e5a1fd920](https://linux-hardware.org/?probe=5e5a1fd920) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [185bfcb7fa](https://linux-hardware.org/?probe=185bfcb7fa) | Dec 04, 2022 |
| HP            | Pavilion Laptop             | Notebook    | [2e2f1d44c1](https://linux-hardware.org/?probe=2e2f1d44c1) | Dec 03, 2022 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [6dbc014a04](https://linux-hardware.org/?probe=6dbc014a04) | Dec 03, 2022 |
| HP            | ProBook 6550b               | Notebook    | [564bf050f2](https://linux-hardware.org/?probe=564bf050f2) | Dec 02, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [cccf492c06](https://linux-hardware.org/?probe=cccf492c06) | Dec 01, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [4c7e1d5bc4](https://linux-hardware.org/?probe=4c7e1d5bc4) | Dec 01, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [bb49870780](https://linux-hardware.org/?probe=bb49870780) | Nov 28, 2022 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [b6af703e1a](https://linux-hardware.org/?probe=b6af703e1a) | Nov 28, 2022 |
| Dell          | G3 3779                     | Notebook    | [1cf1d8aa20](https://linux-hardware.org/?probe=1cf1d8aa20) | Nov 26, 2022 |
| Dell          | G3 3779                     | Notebook    | [4bc02c1721](https://linux-hardware.org/?probe=4bc02c1721) | Nov 26, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [2eb5cc0a12](https://linux-hardware.org/?probe=2eb5cc0a12) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [c0102f2633](https://linux-hardware.org/?probe=c0102f2633) | Nov 25, 2022 |
| Acer          | NC-ES1-512-C3AH             | Notebook    | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [62e12083b5](https://linux-hardware.org/?probe=62e12083b5) | Nov 23, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [495d972ae3](https://linux-hardware.org/?probe=495d972ae3) | Nov 23, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [66383ce902](https://linux-hardware.org/?probe=66383ce902) | Nov 22, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [0354f9cb0e](https://linux-hardware.org/?probe=0354f9cb0e) | Nov 21, 2022 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [c6b206401a](https://linux-hardware.org/?probe=c6b206401a) | Nov 21, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [d7ee80553a](https://linux-hardware.org/?probe=d7ee80553a) | Nov 20, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [f55a45b87f](https://linux-hardware.org/?probe=f55a45b87f) | Nov 20, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [e3d6c78ed4](https://linux-hardware.org/?probe=e3d6c78ed4) | Nov 20, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [dfd1c98a18](https://linux-hardware.org/?probe=dfd1c98a18) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [de8b7d8220](https://linux-hardware.org/?probe=de8b7d8220) | Nov 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [a7ca712256](https://linux-hardware.org/?probe=a7ca712256) | Nov 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [571dc553f9](https://linux-hardware.org/?probe=571dc553f9) | Nov 19, 2022 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d0d37dd251](https://linux-hardware.org/?probe=d0d37dd251) | Nov 17, 2022 |
| Dell          | Latitude 5530               | Notebook    | [35a6ba0a9f](https://linux-hardware.org/?probe=35a6ba0a9f) | Nov 17, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [7c8d905b3d](https://linux-hardware.org/?probe=7c8d905b3d) | Nov 17, 2022 |
| Dell          | Precision 7560              | Notebook    | [0ee8814502](https://linux-hardware.org/?probe=0ee8814502) | Nov 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [5d11a28230](https://linux-hardware.org/?probe=5d11a28230) | Nov 16, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9876aa0fd](https://linux-hardware.org/?probe=c9876aa0fd) | Nov 16, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [f56f2c6a53](https://linux-hardware.org/?probe=f56f2c6a53) | Nov 14, 2022 |
| ASRock        | B660M-HDV                   | Desktop     | [eeaa5c82ea](https://linux-hardware.org/?probe=eeaa5c82ea) | Nov 13, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [94e5dec391](https://linux-hardware.org/?probe=94e5dec391) | Nov 12, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [022a97b52e](https://linux-hardware.org/?probe=022a97b52e) | Nov 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [3f11ca7016](https://linux-hardware.org/?probe=3f11ca7016) | Nov 11, 2022 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [929685d936](https://linux-hardware.org/?probe=929685d936) | Nov 11, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [07bae444fc](https://linux-hardware.org/?probe=07bae444fc) | Nov 11, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [331a1db69d](https://linux-hardware.org/?probe=331a1db69d) | Nov 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [d703e1c63c](https://linux-hardware.org/?probe=d703e1c63c) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| Acer          | Aspire 1825PTZ              | Notebook    | [c2dc801a81](https://linux-hardware.org/?probe=c2dc801a81) | Nov 09, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [9fda4c3798](https://linux-hardware.org/?probe=9fda4c3798) | Nov 08, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e9389bc87e](https://linux-hardware.org/?probe=e9389bc87e) | Nov 08, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [25756ad3c1](https://linux-hardware.org/?probe=25756ad3c1) | Nov 07, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [5505ec9b09](https://linux-hardware.org/?probe=5505ec9b09) | Nov 06, 2022 |
| HP            | Pavilion 17                 | Notebook    | [958de69d5b](https://linux-hardware.org/?probe=958de69d5b) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [4e35f6b15e](https://linux-hardware.org/?probe=4e35f6b15e) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | Notebook    | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [681d0b959b](https://linux-hardware.org/?probe=681d0b959b) | Nov 05, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [3e390c5fb3](https://linux-hardware.org/?probe=3e390c5fb3) | Nov 04, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [0f4bdc1677](https://linux-hardware.org/?probe=0f4bdc1677) | Nov 04, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [3e8fbc43d7](https://linux-hardware.org/?probe=3e8fbc43d7) | Nov 04, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [ff19454b61](https://linux-hardware.org/?probe=ff19454b61) | Nov 04, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [e7254fb467](https://linux-hardware.org/?probe=e7254fb467) | Nov 04, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [2069a0e7fc](https://linux-hardware.org/?probe=2069a0e7fc) | Nov 02, 2022 |
| Dell          | Latitude 5580               | Notebook    | [92545fb976](https://linux-hardware.org/?probe=92545fb976) | Nov 02, 2022 |
| Dell          | Precision 7550              | Notebook    | [2065f4ab5f](https://linux-hardware.org/?probe=2065f4ab5f) | Nov 02, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [95e2a1e7d9](https://linux-hardware.org/?probe=95e2a1e7d9) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [034414a73e](https://linux-hardware.org/?probe=034414a73e) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6f635f46c6](https://linux-hardware.org/?probe=6f635f46c6) | Nov 01, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [4eff9900f2](https://linux-hardware.org/?probe=4eff9900f2) | Oct 28, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [6cfd4bdb14](https://linux-hardware.org/?probe=6cfd4bdb14) | Oct 28, 2022 |
| PC Special... | Recoil II                   | Notebook    | [9ec5a6ef20](https://linux-hardware.org/?probe=9ec5a6ef20) | Oct 27, 2022 |
| PC Special... | Recoil II                   | Notebook    | [38ec5a7708](https://linux-hardware.org/?probe=38ec5a7708) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [7527f4a200](https://linux-hardware.org/?probe=7527f4a200) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [1f6fc12b09](https://linux-hardware.org/?probe=1f6fc12b09) | Oct 25, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [18dad8d151](https://linux-hardware.org/?probe=18dad8d151) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [76fa0d836f](https://linux-hardware.org/?probe=76fa0d836f) | Oct 25, 2022 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | Desktop     | [0d21d658ee](https://linux-hardware.org/?probe=0d21d658ee) | Oct 24, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [0e12d15b78](https://linux-hardware.org/?probe=0e12d15b78) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8b0377a420](https://linux-hardware.org/?probe=8b0377a420) | Oct 24, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [9023ea833f](https://linux-hardware.org/?probe=9023ea833f) | Oct 24, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [f82a2d8d8e](https://linux-hardware.org/?probe=f82a2d8d8e) | Oct 23, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [25295c680c](https://linux-hardware.org/?probe=25295c680c) | Oct 23, 2022 |
| ASUSTek       | P9X79 WS                    | Desktop     | [86f91e4898](https://linux-hardware.org/?probe=86f91e4898) | Oct 23, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [a7bffc7d13](https://linux-hardware.org/?probe=a7bffc7d13) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [39c064d0df](https://linux-hardware.org/?probe=39c064d0df) | Oct 22, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [e34cb7ea31](https://linux-hardware.org/?probe=e34cb7ea31) | Oct 20, 2022 |
| Lenovo        | ThinkPad E590 20NB002BMB    | Notebook    | [4b272ef951](https://linux-hardware.org/?probe=4b272ef951) | Oct 20, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [f5d5e3fb86](https://linux-hardware.org/?probe=f5d5e3fb86) | Oct 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [aa8a459961](https://linux-hardware.org/?probe=aa8a459961) | Oct 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [70d12e710f](https://linux-hardware.org/?probe=70d12e710f) | Oct 18, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9d471dbf37](https://linux-hardware.org/?probe=9d471dbf37) | Oct 18, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [f6c1e8e061](https://linux-hardware.org/?probe=f6c1e8e061) | Oct 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [901d7614e5](https://linux-hardware.org/?probe=901d7614e5) | Oct 17, 2022 |
| Shuttle       | FS81                        | Desktop     | [61c0ca02f3](https://linux-hardware.org/?probe=61c0ca02f3) | Oct 16, 2022 |
| ASUSTek       | GD30CI                      | Desktop     | [e002a9ef5c](https://linux-hardware.org/?probe=e002a9ef5c) | Oct 16, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [fda3302752](https://linux-hardware.org/?probe=fda3302752) | Oct 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [76f457f2aa](https://linux-hardware.org/?probe=76f457f2aa) | Oct 16, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c22c1df016](https://linux-hardware.org/?probe=c22c1df016) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [870d58dd75](https://linux-hardware.org/?probe=870d58dd75) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [27e1ded122](https://linux-hardware.org/?probe=27e1ded122) | Oct 15, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [73f8df6ec6](https://linux-hardware.org/?probe=73f8df6ec6) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0bc0bf85be](https://linux-hardware.org/?probe=0bc0bf85be) | Oct 14, 2022 |
| Dell          | Latitude E6330              | Notebook    | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Dell          | Precision M3800             | Notebook    | [96ea6a1a31](https://linux-hardware.org/?probe=96ea6a1a31) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| Dell          | Latitude 5530               | Notebook    | [9453558076](https://linux-hardware.org/?probe=9453558076) | Oct 12, 2022 |
| ASUSTek       | X756UVK                     | Notebook    | [8d2e9a5e1e](https://linux-hardware.org/?probe=8d2e9a5e1e) | Oct 12, 2022 |
| HP            | 82A5                        | Mini pc     | [5a8ea35493](https://linux-hardware.org/?probe=5a8ea35493) | Oct 11, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | Notebook    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b26ceb2206](https://linux-hardware.org/?probe=b26ceb2206) | Oct 10, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [bc86477fff](https://linux-hardware.org/?probe=bc86477fff) | Oct 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [24d18c0f7f](https://linux-hardware.org/?probe=24d18c0f7f) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1798b09b89](https://linux-hardware.org/?probe=1798b09b89) | Oct 08, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [b419239d57](https://linux-hardware.org/?probe=b419239d57) | Oct 06, 2022 |
| Gigabyte      | Spring Peak                 | Notebook    | [45794008e2](https://linux-hardware.org/?probe=45794008e2) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [03dc83a686](https://linux-hardware.org/?probe=03dc83a686) | Oct 05, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| Notebook      | W330SU2                     | Notebook    | [a5d5500584](https://linux-hardware.org/?probe=a5d5500584) | Oct 01, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| Dell          | Latitude 5530               | Notebook    | [43874dad6d](https://linux-hardware.org/?probe=43874dad6d) | Sep 30, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [02c5cd53e9](https://linux-hardware.org/?probe=02c5cd53e9) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d658b9dcbe](https://linux-hardware.org/?probe=d658b9dcbe) | Sep 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [e948792d3d](https://linux-hardware.org/?probe=e948792d3d) | Sep 30, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [e8ebe97f13](https://linux-hardware.org/?probe=e8ebe97f13) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [56e5d25094](https://linux-hardware.org/?probe=56e5d25094) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMB    | Notebook    | [0c8a6ce686](https://linux-hardware.org/?probe=0c8a6ce686) | Sep 29, 2022 |
| Razer         | Blade                       | Notebook    | [63a4e5f829](https://linux-hardware.org/?probe=63a4e5f829) | Sep 29, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [81ddb430e3](https://linux-hardware.org/?probe=81ddb430e3) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [757d465447](https://linux-hardware.org/?probe=757d465447) | Sep 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [70f86aa587](https://linux-hardware.org/?probe=70f86aa587) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [d09f4c4501](https://linux-hardware.org/?probe=d09f4c4501) | Sep 25, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [3d7933270a](https://linux-hardware.org/?probe=3d7933270a) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [1e6b1b068a](https://linux-hardware.org/?probe=1e6b1b068a) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [a978086f1b](https://linux-hardware.org/?probe=a978086f1b) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [dc49b2baf4](https://linux-hardware.org/?probe=dc49b2baf4) | Sep 21, 2022 |
| Lenovo        | B570e 476025G               | Notebook    | [ab67a90ba7](https://linux-hardware.org/?probe=ab67a90ba7) | Sep 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [153aed4d7c](https://linux-hardware.org/?probe=153aed4d7c) | Sep 19, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e728637650](https://linux-hardware.org/?probe=e728637650) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3da12828c0](https://linux-hardware.org/?probe=3da12828c0) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [798bb8eda6](https://linux-hardware.org/?probe=798bb8eda6) | Sep 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [3e023f86c9](https://linux-hardware.org/?probe=3e023f86c9) | Sep 17, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [90871c217b](https://linux-hardware.org/?probe=90871c217b) | Sep 17, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [324cafa8d2](https://linux-hardware.org/?probe=324cafa8d2) | Sep 17, 2022 |
| Dell          | Precision 7720              | Notebook    | [9658507a0b](https://linux-hardware.org/?probe=9658507a0b) | Sep 17, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [b8e79c9c77](https://linux-hardware.org/?probe=b8e79c9c77) | Sep 16, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [2600793890](https://linux-hardware.org/?probe=2600793890) | Sep 15, 2022 |
| Medion        | MS-7857                     | Desktop     | [98a978898c](https://linux-hardware.org/?probe=98a978898c) | Sep 14, 2022 |
| Medion        | MS-7857                     | Desktop     | [54237e3276](https://linux-hardware.org/?probe=54237e3276) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | Notebook    | [916aa5cc5d](https://linux-hardware.org/?probe=916aa5cc5d) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | Notebook    | [3f97043d7a](https://linux-hardware.org/?probe=3f97043d7a) | Sep 14, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [ddac4b0175](https://linux-hardware.org/?probe=ddac4b0175) | Sep 13, 2022 |
| Sony          | SVE1712L1EW                 | Notebook    | [18400c7a0d](https://linux-hardware.org/?probe=18400c7a0d) | Sep 13, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f062dd3ff8](https://linux-hardware.org/?probe=f062dd3ff8) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [864a5abac7](https://linux-hardware.org/?probe=864a5abac7) | Sep 12, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [6a6e7e4207](https://linux-hardware.org/?probe=6a6e7e4207) | Sep 12, 2022 |
| HP            | 158B                        | Desktop     | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| Sony          | SVE1712L1EW                 | Notebook    | [6a797dc1cf](https://linux-hardware.org/?probe=6a797dc1cf) | Sep 12, 2022 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [8d76919c1a](https://linux-hardware.org/?probe=8d76919c1a) | Sep 11, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [c7eb1fd4ca](https://linux-hardware.org/?probe=c7eb1fd4ca) | Sep 11, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [857e841fb7](https://linux-hardware.org/?probe=857e841fb7) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | Notebook    | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [603514ef84](https://linux-hardware.org/?probe=603514ef84) | Sep 09, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [90908282f2](https://linux-hardware.org/?probe=90908282f2) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [32e71c2905](https://linux-hardware.org/?probe=32e71c2905) | Sep 01, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [af0da080ec](https://linux-hardware.org/?probe=af0da080ec) | Sep 01, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [9f80ee3a09](https://linux-hardware.org/?probe=9f80ee3a09) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1f8274de5a](https://linux-hardware.org/?probe=1f8274de5a) | Aug 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [567bf4b44a](https://linux-hardware.org/?probe=567bf4b44a) | Aug 31, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [748558225a](https://linux-hardware.org/?probe=748558225a) | Aug 30, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [14f4c7e248](https://linux-hardware.org/?probe=14f4c7e248) | Aug 29, 2022 |
| Lenovo        | ThinkPad P1 20MDS0FC00      | Notebook    | [dcdde00f17](https://linux-hardware.org/?probe=dcdde00f17) | Aug 29, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [3a448c33f9](https://linux-hardware.org/?probe=3a448c33f9) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4210c6a219](https://linux-hardware.org/?probe=4210c6a219) | Aug 28, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | Notebook    | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| Dell          | Latitude 5511               | Notebook    | [22c835a93a](https://linux-hardware.org/?probe=22c835a93a) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [413cc5a3c3](https://linux-hardware.org/?probe=413cc5a3c3) | Aug 24, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fdc1bb0c75](https://linux-hardware.org/?probe=fdc1bb0c75) | Aug 23, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [fca17b512f](https://linux-hardware.org/?probe=fca17b512f) | Aug 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [47b1480e61](https://linux-hardware.org/?probe=47b1480e61) | Aug 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d1fb1214f6](https://linux-hardware.org/?probe=d1fb1214f6) | Aug 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fc1a1cd41f](https://linux-hardware.org/?probe=fc1a1cd41f) | Aug 20, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [7dbac78a87](https://linux-hardware.org/?probe=7dbac78a87) | Aug 20, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [abbb1d7360](https://linux-hardware.org/?probe=abbb1d7360) | Aug 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c3e335499f](https://linux-hardware.org/?probe=c3e335499f) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| MSI           | MS-AE611 100                | All in one  | [336e0dfd12](https://linux-hardware.org/?probe=336e0dfd12) | Aug 18, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | 872B                        | Desktop     | [466f4962fe](https://linux-hardware.org/?probe=466f4962fe) | Aug 17, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [bd808084a5](https://linux-hardware.org/?probe=bd808084a5) | Aug 16, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [07e825ed5b](https://linux-hardware.org/?probe=07e825ed5b) | Aug 16, 2022 |
| HP            | 2AB6                        | Desktop     | [bf0c915ea8](https://linux-hardware.org/?probe=bf0c915ea8) | Aug 15, 2022 |
| HP            | 2AB6                        | Desktop     | [2fe34984da](https://linux-hardware.org/?probe=2fe34984da) | Aug 15, 2022 |
| HP            | 1825                        | Desktop     | [bceae72004](https://linux-hardware.org/?probe=bceae72004) | Aug 15, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [97f14bc24c](https://linux-hardware.org/?probe=97f14bc24c) | Aug 14, 2022 |
| Lenovo        | ThinkCentre XXXX 739527G    | Desktop     | [ca5fe11e2c](https://linux-hardware.org/?probe=ca5fe11e2c) | Aug 13, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3e63b30226](https://linux-hardware.org/?probe=3e63b30226) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [bc32ff70b7](https://linux-hardware.org/?probe=bc32ff70b7) | Aug 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [d7735b3387](https://linux-hardware.org/?probe=d7735b3387) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ba9961565a](https://linux-hardware.org/?probe=ba9961565a) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fe91d8cdd3](https://linux-hardware.org/?probe=fe91d8cdd3) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | Notebook    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [26b1a32b84](https://linux-hardware.org/?probe=26b1a32b84) | Aug 11, 2022 |
| MSI           | MS-AE611 100                | All in one  | [94bcb206d3](https://linux-hardware.org/?probe=94bcb206d3) | Aug 10, 2022 |
| Dell          | Latitude D630               | Notebook    | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [8913065613](https://linux-hardware.org/?probe=8913065613) | Aug 06, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aee6d50427](https://linux-hardware.org/?probe=aee6d50427) | Aug 05, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [882cec3541](https://linux-hardware.org/?probe=882cec3541) | Aug 02, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [f6f97a58c4](https://linux-hardware.org/?probe=f6f97a58c4) | Aug 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [e650b177cc](https://linux-hardware.org/?probe=e650b177cc) | Aug 02, 2022 |
| Dell          | Latitude 5520               | Notebook    | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [b59f87dd02](https://linux-hardware.org/?probe=b59f87dd02) | Aug 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [9e219bd7c2](https://linux-hardware.org/?probe=9e219bd7c2) | Jul 29, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [e6f2cdc55e](https://linux-hardware.org/?probe=e6f2cdc55e) | Jul 29, 2022 |
| Dell          | Latitude 5590               | Notebook    | [ab7d6b9f02](https://linux-hardware.org/?probe=ab7d6b9f02) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [c4a4fed104](https://linux-hardware.org/?probe=c4a4fed104) | Jul 28, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [356556d83a](https://linux-hardware.org/?probe=356556d83a) | Jul 28, 2022 |
| Dell          | Latitude D630               | Notebook    | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [e5d7cc54e7](https://linux-hardware.org/?probe=e5d7cc54e7) | Jul 28, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [bf64b6cf98](https://linux-hardware.org/?probe=bf64b6cf98) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [d8b47ea062](https://linux-hardware.org/?probe=d8b47ea062) | Jul 27, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [c2f56b2458](https://linux-hardware.org/?probe=c2f56b2458) | Jul 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [910067609e](https://linux-hardware.org/?probe=910067609e) | Jul 27, 2022 |
| Toshiba       | Satellite C870D-116         | Notebook    | [d92af8246c](https://linux-hardware.org/?probe=d92af8246c) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [f27c511d04](https://linux-hardware.org/?probe=f27c511d04) | Jul 26, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b2e54629e5](https://linux-hardware.org/?probe=b2e54629e5) | Jul 25, 2022 |
| Panasonic     | FZ55-2                      | Notebook    | [a190a7d890](https://linux-hardware.org/?probe=a190a7d890) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [7ac84940b8](https://linux-hardware.org/?probe=7ac84940b8) | Jul 24, 2022 |
| Toshiba       | Portable PC                 | Notebook    | [00cd85e866](https://linux-hardware.org/?probe=00cd85e866) | Jul 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [1860c6d71f](https://linux-hardware.org/?probe=1860c6d71f) | Jul 23, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [d13d96da02](https://linux-hardware.org/?probe=d13d96da02) | Jul 23, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [f8ce34248a](https://linux-hardware.org/?probe=f8ce34248a) | Jul 22, 2022 |
| Lenovo        | ThinkPad E580 20KSS0GK01    | Notebook    | [b2d902cbc6](https://linux-hardware.org/?probe=b2d902cbc6) | Jul 21, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| MSI           | Z97-G43 GAMING              | Desktop     | [f7f43ba6ed](https://linux-hardware.org/?probe=f7f43ba6ed) | Jul 18, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [bffac60888](https://linux-hardware.org/?probe=bffac60888) | Jul 16, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [d52eabbac8](https://linux-hardware.org/?probe=d52eabbac8) | Jul 16, 2022 |
| HP            | ProBook 650 G5              | Notebook    | [471b64a407](https://linux-hardware.org/?probe=471b64a407) | Jul 16, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [5b07f65ff5](https://linux-hardware.org/?probe=5b07f65ff5) | Jul 16, 2022 |
| Sony          | SVE1513H1EW                 | Notebook    | [6e4d66c2ee](https://linux-hardware.org/?probe=6e4d66c2ee) | Jul 15, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [cb6916e513](https://linux-hardware.org/?probe=cb6916e513) | Jul 15, 2022 |
| Medion        | MS-7797                     | Desktop     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | Notebook    | [b85cc7c80c](https://linux-hardware.org/?probe=b85cc7c80c) | Jul 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Acer          | Aspire M3920                | Desktop     | [9b12bf66ac](https://linux-hardware.org/?probe=9b12bf66ac) | Jul 11, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [b40a6c6b15](https://linux-hardware.org/?probe=b40a6c6b15) | Jul 09, 2022 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [e541b7743e](https://linux-hardware.org/?probe=e541b7743e) | Jul 08, 2022 |
| HP            | 2820h                       | Desktop     | [bfc5afa2c8](https://linux-hardware.org/?probe=bfc5afa2c8) | Jul 07, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [b08ab62885](https://linux-hardware.org/?probe=b08ab62885) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e7c2f09e51](https://linux-hardware.org/?probe=e7c2f09e51) | Jul 05, 2022 |
| NEC Comput... | NEC Versa M370              | Notebook    | [d4dbd6878c](https://linux-hardware.org/?probe=d4dbd6878c) | Jul 04, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [238f7bf18c](https://linux-hardware.org/?probe=238f7bf18c) | Jul 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| HP            | Pavilion dm1                | Notebook    | [927f5b38e0](https://linux-hardware.org/?probe=927f5b38e0) | Jun 29, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [66a8fd4642](https://linux-hardware.org/?probe=66a8fd4642) | Jun 28, 2022 |
| Medion        | E7214                       | Notebook    | [439509e70a](https://linux-hardware.org/?probe=439509e70a) | Jun 28, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [90a56ffa69](https://linux-hardware.org/?probe=90a56ffa69) | Jun 27, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Dell          | Latitude E6330              | Notebook    | [969981b8cb](https://linux-hardware.org/?probe=969981b8cb) | Jun 25, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [9421b03b9e](https://linux-hardware.org/?probe=9421b03b9e) | Jun 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c2e6e05eea](https://linux-hardware.org/?probe=c2e6e05eea) | Jun 25, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| MSI           | IONA                        | Desktop     | [9f4e8871a7](https://linux-hardware.org/?probe=9f4e8871a7) | Jun 24, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [34e3aad338](https://linux-hardware.org/?probe=34e3aad338) | Jun 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9f67f6836e](https://linux-hardware.org/?probe=9f67f6836e) | Jun 23, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [32a4f6d3e0](https://linux-hardware.org/?probe=32a4f6d3e0) | Jun 23, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [f3ceed4c58](https://linux-hardware.org/?probe=f3ceed4c58) | Jun 20, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [d872e88532](https://linux-hardware.org/?probe=d872e88532) | Jun 20, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [17e0b3e4c0](https://linux-hardware.org/?probe=17e0b3e4c0) | Jun 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b070339877](https://linux-hardware.org/?probe=b070339877) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [6647ddd346](https://linux-hardware.org/?probe=6647ddd346) | Jun 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [812caba8bf](https://linux-hardware.org/?probe=812caba8bf) | Jun 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c1efcc5411](https://linux-hardware.org/?probe=c1efcc5411) | Jun 16, 2022 |
| Unknown       | MediaTek krane sku176       | Soc         | [c992270582](https://linux-hardware.org/?probe=c992270582) | Jun 15, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [5ef81d4b82](https://linux-hardware.org/?probe=5ef81d4b82) | Jun 15, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d4e4001c4c](https://linux-hardware.org/?probe=d4e4001c4c) | Jun 15, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [4b6c230717](https://linux-hardware.org/?probe=4b6c230717) | Jun 12, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3ddbde438b](https://linux-hardware.org/?probe=3ddbde438b) | Jun 12, 2022 |
| MSI           | H55M-E33                    | Desktop     | [1fa7005827](https://linux-hardware.org/?probe=1fa7005827) | Jun 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [6acd8f6081](https://linux-hardware.org/?probe=6acd8f6081) | Jun 12, 2022 |
| Dell          | 0XCR8D A03                  | Desktop     | [7b5fb1809b](https://linux-hardware.org/?probe=7b5fb1809b) | Jun 09, 2022 |
| HP            | Compaq 8710w                | Notebook    | [666f2ebcf0](https://linux-hardware.org/?probe=666f2ebcf0) | Jun 08, 2022 |
| Dell          | 0HX555                      | Desktop     | [41ae8a1dd5](https://linux-hardware.org/?probe=41ae8a1dd5) | Jun 08, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [9e49a2cbac](https://linux-hardware.org/?probe=9e49a2cbac) | Jun 05, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [bfd4aab236](https://linux-hardware.org/?probe=bfd4aab236) | Jun 04, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [68a1616b4a](https://linux-hardware.org/?probe=68a1616b4a) | Jun 03, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [ea56369709](https://linux-hardware.org/?probe=ea56369709) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [909d9cb8d5](https://linux-hardware.org/?probe=909d9cb8d5) | Jun 03, 2022 |
| Samsung       | 750XED                      | Notebook    | [1a900ee340](https://linux-hardware.org/?probe=1a900ee340) | Jun 02, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [d81154a7e1](https://linux-hardware.org/?probe=d81154a7e1) | Jun 02, 2022 |
| ASUSTek       | G11CD-K                     | Desktop     | [6550f85808](https://linux-hardware.org/?probe=6550f85808) | Jun 01, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [88ef811c4d](https://linux-hardware.org/?probe=88ef811c4d) | May 31, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [70313d6ed4](https://linux-hardware.org/?probe=70313d6ed4) | May 31, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [820a9fb182](https://linux-hardware.org/?probe=820a9fb182) | May 30, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [1029a819d7](https://linux-hardware.org/?probe=1029a819d7) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [c4e27f4d19](https://linux-hardware.org/?probe=c4e27f4d19) | May 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [077be5d10b](https://linux-hardware.org/?probe=077be5d10b) | May 28, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [475315dc10](https://linux-hardware.org/?probe=475315dc10) | May 28, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [397d64e10c](https://linux-hardware.org/?probe=397d64e10c) | May 27, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [a74cc1410a](https://linux-hardware.org/?probe=a74cc1410a) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6e5dd6f76f](https://linux-hardware.org/?probe=6e5dd6f76f) | May 25, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [4107e267d7](https://linux-hardware.org/?probe=4107e267d7) | May 24, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fdc743e9e1](https://linux-hardware.org/?probe=fdc743e9e1) | May 23, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| Medion        | P6624                       | Notebook    | [ed8bd28269](https://linux-hardware.org/?probe=ed8bd28269) | May 21, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d1ca28a2fb](https://linux-hardware.org/?probe=d1ca28a2fb) | May 21, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [a0597ba198](https://linux-hardware.org/?probe=a0597ba198) | May 20, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [9d14cc23ca](https://linux-hardware.org/?probe=9d14cc23ca) | May 20, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP            | 82A2                        | Desktop     | [56d6c8d749](https://linux-hardware.org/?probe=56d6c8d749) | May 19, 2022 |
| HP            | 82A2                        | Desktop     | [6e0efeba1d](https://linux-hardware.org/?probe=6e0efeba1d) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [2886b99972](https://linux-hardware.org/?probe=2886b99972) | May 17, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [2f26e2ec6e](https://linux-hardware.org/?probe=2f26e2ec6e) | May 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [74cb2084ef](https://linux-hardware.org/?probe=74cb2084ef) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | Notebook    | [0f8829e460](https://linux-hardware.org/?probe=0f8829e460) | May 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS4X50... | Notebook    | [0fb588c686](https://linux-hardware.org/?probe=0fb588c686) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | Notebook    | [83b27998e5](https://linux-hardware.org/?probe=83b27998e5) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6adb7e22c5](https://linux-hardware.org/?probe=6adb7e22c5) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3f84f4220e](https://linux-hardware.org/?probe=3f84f4220e) | May 14, 2022 |
| Sony          | VPCEH1M0E                   | Notebook    | [eefe7eee06](https://linux-hardware.org/?probe=eefe7eee06) | May 13, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [06030eee20](https://linux-hardware.org/?probe=06030eee20) | May 13, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9722abbde0](https://linux-hardware.org/?probe=9722abbde0) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [3f20d2bc2b](https://linux-hardware.org/?probe=3f20d2bc2b) | May 12, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [0026740e3f](https://linux-hardware.org/?probe=0026740e3f) | May 12, 2022 |
| Acer          | Aspire M3985                | Desktop     | [e650ae1a26](https://linux-hardware.org/?probe=e650ae1a26) | May 11, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [a6f5c6215d](https://linux-hardware.org/?probe=a6f5c6215d) | May 11, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4f87a5b748](https://linux-hardware.org/?probe=4f87a5b748) | May 10, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [eaa10a050b](https://linux-hardware.org/?probe=eaa10a050b) | May 10, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0066686d1d](https://linux-hardware.org/?probe=0066686d1d) | May 10, 2022 |
| Dell          | 0KV3RP A00                  | Desktop     | [6ef8c2f171](https://linux-hardware.org/?probe=6ef8c2f171) | May 10, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [05b7c2c72c](https://linux-hardware.org/?probe=05b7c2c72c) | May 09, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a9e6ecf483](https://linux-hardware.org/?probe=a9e6ecf483) | May 09, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [8080b9becd](https://linux-hardware.org/?probe=8080b9becd) | May 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1d84f1a74a](https://linux-hardware.org/?probe=1d84f1a74a) | May 07, 2022 |
| HP            | 82F2                        | Desktop     | [cb49a04bce](https://linux-hardware.org/?probe=cb49a04bce) | May 07, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8e2da684e0](https://linux-hardware.org/?probe=8e2da684e0) | May 07, 2022 |
| Dell          | Latitude E6330              | Notebook    | [cbfc4e6f78](https://linux-hardware.org/?probe=cbfc4e6f78) | May 07, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [093d7ea1c9](https://linux-hardware.org/?probe=093d7ea1c9) | May 06, 2022 |
| Lenovo        | ThinkPad X280 20KES94F05    | Notebook    | [16b4cbc9fb](https://linux-hardware.org/?probe=16b4cbc9fb) | May 05, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| Dell          | 0VHRW1 A03                  | Desktop     | [2a5880a214](https://linux-hardware.org/?probe=2a5880a214) | May 03, 2022 |
| Dell          | 0VHRW1 A03                  | Desktop     | [8204a08a04](https://linux-hardware.org/?probe=8204a08a04) | May 03, 2022 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [a7396f278d](https://linux-hardware.org/?probe=a7396f278d) | May 02, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [01a95b61fe](https://linux-hardware.org/?probe=01a95b61fe) | May 02, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [5625deb6aa](https://linux-hardware.org/?probe=5625deb6aa) | May 01, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [130944084d](https://linux-hardware.org/?probe=130944084d) | May 01, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [cc016ce0c5](https://linux-hardware.org/?probe=cc016ce0c5) | May 01, 2022 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [0e0d0dd3aa](https://linux-hardware.org/?probe=0e0d0dd3aa) | Apr 30, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [f140b54261](https://linux-hardware.org/?probe=f140b54261) | Apr 30, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [2543d87831](https://linux-hardware.org/?probe=2543d87831) | Apr 30, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [21fcbc1850](https://linux-hardware.org/?probe=21fcbc1850) | Apr 27, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [edf60be002](https://linux-hardware.org/?probe=edf60be002) | Apr 26, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [de010dfc55](https://linux-hardware.org/?probe=de010dfc55) | Apr 24, 2022 |
| BLAUPUNKT     | Discovery 1011WI            | Notebook    | [c20b87673e](https://linux-hardware.org/?probe=c20b87673e) | Apr 24, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [c668e0d48e](https://linux-hardware.org/?probe=c668e0d48e) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | Notebook    | [762843e768](https://linux-hardware.org/?probe=762843e768) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | Notebook    | [11ec4d291b](https://linux-hardware.org/?probe=11ec4d291b) | Apr 23, 2022 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [ca56dc9824](https://linux-hardware.org/?probe=ca56dc9824) | Apr 21, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [cc5ed34db8](https://linux-hardware.org/?probe=cc5ed34db8) | Apr 21, 2022 |
| Lenovo        | ThinkPad T520 4243AP1       | Notebook    | [7723ab4bd9](https://linux-hardware.org/?probe=7723ab4bd9) | Apr 19, 2022 |
| Medion        | D3F3-EM2                    | Desktop     | [733df830d1](https://linux-hardware.org/?probe=733df830d1) | Apr 19, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [0e53d4286d](https://linux-hardware.org/?probe=0e53d4286d) | Apr 19, 2022 |
| MSI           | GL65 Leopard 10SER          | Notebook    | [2bdfe0279e](https://linux-hardware.org/?probe=2bdfe0279e) | Apr 19, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [4b6d535621](https://linux-hardware.org/?probe=4b6d535621) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440s 20ARS1940... | Notebook    | [a7fbe1af34](https://linux-hardware.org/?probe=a7fbe1af34) | Apr 18, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [dfbc0779e8](https://linux-hardware.org/?probe=dfbc0779e8) | Apr 17, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | Notebook    | [7b1d2ec5a1](https://linux-hardware.org/?probe=7b1d2ec5a1) | Apr 17, 2022 |
| Acer          | Aspire 5735                 | Notebook    | [e43434e15c](https://linux-hardware.org/?probe=e43434e15c) | Apr 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [4639b09a3e](https://linux-hardware.org/?probe=4639b09a3e) | Apr 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5bdba5a921](https://linux-hardware.org/?probe=5bdba5a921) | Apr 14, 2022 |
| MSI           | B250M MORTAR                | Desktop     | [8bf9715804](https://linux-hardware.org/?probe=8bf9715804) | Apr 14, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [4a90b659fc](https://linux-hardware.org/?probe=4a90b659fc) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b80dc08588](https://linux-hardware.org/?probe=b80dc08588) | Apr 14, 2022 |
| Dell          | Latitude 5591               | Notebook    | [3f3f097a1a](https://linux-hardware.org/?probe=3f3f097a1a) | Apr 13, 2022 |
| ASRock        | H170M Pro4                  | Desktop     | [a8bd162bf1](https://linux-hardware.org/?probe=a8bd162bf1) | Apr 13, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2ddb0d0765](https://linux-hardware.org/?probe=2ddb0d0765) | Apr 13, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [5aafaf0890](https://linux-hardware.org/?probe=5aafaf0890) | Apr 13, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [983dbbf9e8](https://linux-hardware.org/?probe=983dbbf9e8) | Apr 13, 2022 |
| Medion        | BTDD-EAIO                   | All in one  | [8de03f374b](https://linux-hardware.org/?probe=8de03f374b) | Apr 13, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [7ea9773813](https://linux-hardware.org/?probe=7ea9773813) | Apr 12, 2022 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [938b601307](https://linux-hardware.org/?probe=938b601307) | Apr 11, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [09f8f09862](https://linux-hardware.org/?probe=09f8f09862) | Apr 11, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [da1cd5bf6e](https://linux-hardware.org/?probe=da1cd5bf6e) | Apr 11, 2022 |
| Google        | Akali 360                   | Notebook    | [dccccb359b](https://linux-hardware.org/?probe=dccccb359b) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [2ce1788c33](https://linux-hardware.org/?probe=2ce1788c33) | Apr 11, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [01f57dd952](https://linux-hardware.org/?probe=01f57dd952) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7f71b84230](https://linux-hardware.org/?probe=7f71b84230) | Apr 10, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [a6aee71c13](https://linux-hardware.org/?probe=a6aee71c13) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [1d1cdbd95c](https://linux-hardware.org/?probe=1d1cdbd95c) | Apr 09, 2022 |
| Dell          | Latitude E6430              | Notebook    | [dd09c863c8](https://linux-hardware.org/?probe=dd09c863c8) | Apr 08, 2022 |
| ASRockRack    | ROMED8-2T                   | Server      | [49aedaee61](https://linux-hardware.org/?probe=49aedaee61) | Apr 08, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [8bcbe236a7](https://linux-hardware.org/?probe=8bcbe236a7) | Apr 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [af324f356f](https://linux-hardware.org/?probe=af324f356f) | Apr 07, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [27bddd0a9c](https://linux-hardware.org/?probe=27bddd0a9c) | Apr 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [fc358abe4b](https://linux-hardware.org/?probe=fc358abe4b) | Apr 06, 2022 |
| HP            | 470 G7 Notebook PC          | Notebook    | [34fc91d9ac](https://linux-hardware.org/?probe=34fc91d9ac) | Apr 06, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [dff8141976](https://linux-hardware.org/?probe=dff8141976) | Apr 06, 2022 |
| MSI           | Eclipse SLI                 | Desktop     | [e488b9407a](https://linux-hardware.org/?probe=e488b9407a) | Apr 05, 2022 |
| MSI           | Eclipse SLI                 | Desktop     | [aebfec44b2](https://linux-hardware.org/?probe=aebfec44b2) | Apr 05, 2022 |
| Dell          | Latitude 5410               | Notebook    | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [8c4011afa9](https://linux-hardware.org/?probe=8c4011afa9) | Apr 04, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [b8d47c54c3](https://linux-hardware.org/?probe=b8d47c54c3) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [53da5b2d7c](https://linux-hardware.org/?probe=53da5b2d7c) | Apr 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [94a9015090](https://linux-hardware.org/?probe=94a9015090) | Apr 03, 2022 |
| ASRock        | B75M-GL                     | Desktop     | [087381b93e](https://linux-hardware.org/?probe=087381b93e) | Apr 02, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [1de292a85c](https://linux-hardware.org/?probe=1de292a85c) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [732406d8b0](https://linux-hardware.org/?probe=732406d8b0) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [086261ecef](https://linux-hardware.org/?probe=086261ecef) | Apr 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [4731581e9b](https://linux-hardware.org/?probe=4731581e9b) | Mar 31, 2022 |
| HP            | ZBook Studio G4             | Notebook    | [d5ec5c3e8e](https://linux-hardware.org/?probe=d5ec5c3e8e) | Mar 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [670f83f6bb](https://linux-hardware.org/?probe=670f83f6bb) | Mar 29, 2022 |
| Medion        | Crawler E25                 | Notebook    | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| HP            | 82A2                        | Desktop     | [5736762c06](https://linux-hardware.org/?probe=5736762c06) | Mar 28, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b8969bf34b](https://linux-hardware.org/?probe=b8969bf34b) | Mar 27, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e04592bee1](https://linux-hardware.org/?probe=e04592bee1) | Mar 27, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c4b697295e](https://linux-hardware.org/?probe=c4b697295e) | Mar 26, 2022 |
| Acer          | Aspire 8930                 | Notebook    | [6774be59d3](https://linux-hardware.org/?probe=6774be59d3) | Mar 26, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [bbdb3c316f](https://linux-hardware.org/?probe=bbdb3c316f) | Mar 25, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [6096fbc1ba](https://linux-hardware.org/?probe=6096fbc1ba) | Mar 25, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [7ad46659a5](https://linux-hardware.org/?probe=7ad46659a5) | Mar 24, 2022 |
| Packard Be... | DOT S                       | Notebook    | [591be1d465](https://linux-hardware.org/?probe=591be1d465) | Mar 22, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | Notebook    | [26cd5cf250](https://linux-hardware.org/?probe=26cd5cf250) | Mar 20, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [9e38b0860e](https://linux-hardware.org/?probe=9e38b0860e) | Mar 19, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [1feeb83fb4](https://linux-hardware.org/?probe=1feeb83fb4) | Mar 19, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5415b5f876](https://linux-hardware.org/?probe=5415b5f876) | Mar 18, 2022 |
| Acer          | Aspire 8930                 | Notebook    | [79f6f7d9c1](https://linux-hardware.org/?probe=79f6f7d9c1) | Mar 18, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [2692e4dfd1](https://linux-hardware.org/?probe=2692e4dfd1) | Mar 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6a5b5cd15e](https://linux-hardware.org/?probe=6a5b5cd15e) | Mar 17, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [908e3fe366](https://linux-hardware.org/?probe=908e3fe366) | Mar 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a3444ce232](https://linux-hardware.org/?probe=a3444ce232) | Mar 16, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [605d83cd15](https://linux-hardware.org/?probe=605d83cd15) | Mar 15, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [1b6764fd97](https://linux-hardware.org/?probe=1b6764fd97) | Mar 15, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [00edfc8f9b](https://linux-hardware.org/?probe=00edfc8f9b) | Mar 14, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [37a24fa0b8](https://linux-hardware.org/?probe=37a24fa0b8) | Mar 13, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.304     | Desktop     | [e2e15f011b](https://linux-hardware.org/?probe=e2e15f011b) | Mar 12, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [30ec3132c4](https://linux-hardware.org/?probe=30ec3132c4) | Mar 12, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | Notebook    | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | Notebook    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| Lenovo        | ThinkPad L390 20NSS1YV0B    | Notebook    | [a48bd2e59b](https://linux-hardware.org/?probe=a48bd2e59b) | Mar 10, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8d3cfb2f81](https://linux-hardware.org/?probe=8d3cfb2f81) | Mar 09, 2022 |
| HP            | Pavilion zd8000 (EL052EA... | Notebook    | [18f42a184c](https://linux-hardware.org/?probe=18f42a184c) | Mar 08, 2022 |
| Dell          | Latitude 5500               | Notebook    | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Dell          | Latitude 5500               | Notebook    | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo        | ThinkPad W541 20EFA013MB    | Notebook    | [b4087fab13](https://linux-hardware.org/?probe=b4087fab13) | Mar 06, 2022 |
| Dell          | Latitude E6330              | Notebook    | [f4491d2da7](https://linux-hardware.org/?probe=f4491d2da7) | Mar 06, 2022 |
| Medion        | MS-7797                     | Desktop     | [88982d8ccb](https://linux-hardware.org/?probe=88982d8ccb) | Mar 05, 2022 |
| Supermicro    | X11DPi-N                    | Server      | [73518731a1](https://linux-hardware.org/?probe=73518731a1) | Mar 03, 2022 |
| Lenovo        | 36F4 SDK0J40709 WIN 3259... | All in one  | [68b6455d7a](https://linux-hardware.org/?probe=68b6455d7a) | Mar 03, 2022 |
| Supermicro    | X11DPi-N                    | Server      | [2ffd17de74](https://linux-hardware.org/?probe=2ffd17de74) | Mar 03, 2022 |
| HP            | 1825                        | Desktop     | [a7ce5b6b11](https://linux-hardware.org/?probe=a7ce5b6b11) | Mar 03, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [435c237f8f](https://linux-hardware.org/?probe=435c237f8f) | Mar 02, 2022 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [f67c401f47](https://linux-hardware.org/?probe=f67c401f47) | Feb 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [d04802b99e](https://linux-hardware.org/?probe=d04802b99e) | Feb 27, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e72fbddbc9](https://linux-hardware.org/?probe=e72fbddbc9) | Feb 25, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [163b1f4a34](https://linux-hardware.org/?probe=163b1f4a34) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8166a6711c](https://linux-hardware.org/?probe=8166a6711c) | Feb 25, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | Desktop     | [866eeb024c](https://linux-hardware.org/?probe=866eeb024c) | Feb 24, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | Desktop     | [9e1c3db4b1](https://linux-hardware.org/?probe=9e1c3db4b1) | Feb 24, 2022 |
| HP            | 2129                        | Desktop     | [b4445ac549](https://linux-hardware.org/?probe=b4445ac549) | Feb 24, 2022 |
| Packard Be... | EasyNote_MX67               | Notebook    | [0687a8a072](https://linux-hardware.org/?probe=0687a8a072) | Feb 23, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [a85780aaae](https://linux-hardware.org/?probe=a85780aaae) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [fb10931f05](https://linux-hardware.org/?probe=fb10931f05) | Feb 23, 2022 |
| Dell          | Latitude E5550              | Notebook    | [7eb0675554](https://linux-hardware.org/?probe=7eb0675554) | Feb 22, 2022 |
| HP            | Pavilion 15                 | Notebook    | [6aaa686668](https://linux-hardware.org/?probe=6aaa686668) | Feb 22, 2022 |
| Sony          | VGN-FW51JF_H                | Notebook    | [03c4e88514](https://linux-hardware.org/?probe=03c4e88514) | Feb 22, 2022 |
| Dell          | 054KM3 A01                  | Desktop     | [f00a30a31e](https://linux-hardware.org/?probe=f00a30a31e) | Feb 22, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [0be5823fc2](https://linux-hardware.org/?probe=0be5823fc2) | Feb 22, 2022 |
| Lenovo        | ThinkPad W541 20EFA013MB    | Notebook    | [99676b9365](https://linux-hardware.org/?probe=99676b9365) | Feb 21, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [e7013b772d](https://linux-hardware.org/?probe=e7013b772d) | Feb 21, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [59476747e2](https://linux-hardware.org/?probe=59476747e2) | Feb 20, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [5b9ec4cd6a](https://linux-hardware.org/?probe=5b9ec4cd6a) | Feb 20, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [ad3eb03b54](https://linux-hardware.org/?probe=ad3eb03b54) | Feb 20, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [83b3333eb0](https://linux-hardware.org/?probe=83b3333eb0) | Feb 20, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [962c444158](https://linux-hardware.org/?probe=962c444158) | Feb 19, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [4f87ec9849](https://linux-hardware.org/?probe=4f87ec9849) | Feb 19, 2022 |
| ASUSTek       | P751JA                      | Notebook    | [54c2cab341](https://linux-hardware.org/?probe=54c2cab341) | Feb 18, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [757a05c274](https://linux-hardware.org/?probe=757a05c274) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [973f8ebf5e](https://linux-hardware.org/?probe=973f8ebf5e) | Feb 17, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [b32ffb9adc](https://linux-hardware.org/?probe=b32ffb9adc) | Feb 17, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [3bb86aa608](https://linux-hardware.org/?probe=3bb86aa608) | Feb 17, 2022 |
| ASUSTek       | P751JA                      | Notebook    | [8e2a0e2970](https://linux-hardware.org/?probe=8e2a0e2970) | Feb 16, 2022 |
| HP            | 82A2                        | Desktop     | [5efad9b732](https://linux-hardware.org/?probe=5efad9b732) | Feb 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [df46a37f1a](https://linux-hardware.org/?probe=df46a37f1a) | Feb 15, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [70b0938bc3](https://linux-hardware.org/?probe=70b0938bc3) | Feb 15, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [918d93ea7a](https://linux-hardware.org/?probe=918d93ea7a) | Feb 15, 2022 |
| HP            | Pavilion 15                 | Notebook    | [67825b30b9](https://linux-hardware.org/?probe=67825b30b9) | Feb 15, 2022 |
| HP            | ProBook 6560b               | Notebook    | [425caa152d](https://linux-hardware.org/?probe=425caa152d) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [ed2717ae86](https://linux-hardware.org/?probe=ed2717ae86) | Feb 14, 2022 |
| Lenovo        | ThinkPad X260 20F5S3FY00    | Notebook    | [08006b1c3a](https://linux-hardware.org/?probe=08006b1c3a) | Feb 13, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [1b9f62185f](https://linux-hardware.org/?probe=1b9f62185f) | Feb 13, 2022 |
| HP            | 18E7                        | Desktop     | [b047f83746](https://linux-hardware.org/?probe=b047f83746) | Feb 12, 2022 |
| ASUSTek       | N501JW                      | Notebook    | [7937164c8a](https://linux-hardware.org/?probe=7937164c8a) | Feb 11, 2022 |
| Packard Be... | IMEDIA S2190                | Desktop     | [d0b8d7064b](https://linux-hardware.org/?probe=d0b8d7064b) | Feb 10, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [d455b09330](https://linux-hardware.org/?probe=d455b09330) | Feb 10, 2022 |
| HP            | 198E                        | Desktop     | [f4781dd683](https://linux-hardware.org/?probe=f4781dd683) | Feb 10, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [804f3b74e0](https://linux-hardware.org/?probe=804f3b74e0) | Feb 10, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [9e1c3acaf3](https://linux-hardware.org/?probe=9e1c3acaf3) | Feb 10, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [1da45b4476](https://linux-hardware.org/?probe=1da45b4476) | Feb 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [baf12e4099](https://linux-hardware.org/?probe=baf12e4099) | Feb 09, 2022 |
| GPD           | G1621-02                    | Notebook    | [d823ea2989](https://linux-hardware.org/?probe=d823ea2989) | Feb 09, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [00f0fe6cd3](https://linux-hardware.org/?probe=00f0fe6cd3) | Feb 09, 2022 |
| HP            | Pavilion dv7                | Notebook    | [03b19f857f](https://linux-hardware.org/?probe=03b19f857f) | Feb 09, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [746ddfc621](https://linux-hardware.org/?probe=746ddfc621) | Feb 09, 2022 |
| Lenovo        | ThinkPad T500 20828VG       | Notebook    | [f79076499b](https://linux-hardware.org/?probe=f79076499b) | Feb 09, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [b6b1889923](https://linux-hardware.org/?probe=b6b1889923) | Feb 09, 2022 |
| PC Special... | GK5NPFO                     | Notebook    | [14695b59b4](https://linux-hardware.org/?probe=14695b59b4) | Feb 08, 2022 |
| Toshiba       | Satellite C855-112          | Notebook    | [99cb514a47](https://linux-hardware.org/?probe=99cb514a47) | Feb 07, 2022 |
| HP            | 82F2                        | Desktop     | [6c8626b785](https://linux-hardware.org/?probe=6c8626b785) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [48b1ca5fbc](https://linux-hardware.org/?probe=48b1ca5fbc) | Feb 07, 2022 |
| Lenovo        | ThinkPad E495 20NES01600    | Notebook    | [c40a0c5222](https://linux-hardware.org/?probe=c40a0c5222) | Feb 07, 2022 |
| Sony          | VGN-FW51JF_H                | Notebook    | [0e5f92c7b7](https://linux-hardware.org/?probe=0e5f92c7b7) | Feb 07, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [bfe6169921](https://linux-hardware.org/?probe=bfe6169921) | Feb 07, 2022 |
| Intel         | H61 V124                    | Desktop     | [258b472104](https://linux-hardware.org/?probe=258b472104) | Feb 06, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [5714dfdd29](https://linux-hardware.org/?probe=5714dfdd29) | Feb 06, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [51a06ffad3](https://linux-hardware.org/?probe=51a06ffad3) | Feb 05, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [c4bd8c53df](https://linux-hardware.org/?probe=c4bd8c53df) | Feb 05, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [01ac407ee8](https://linux-hardware.org/?probe=01ac407ee8) | Feb 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [63a70836f3](https://linux-hardware.org/?probe=63a70836f3) | Feb 05, 2022 |
| ASUSTek       | K73SV                       | Notebook    | [0610b130c8](https://linux-hardware.org/?probe=0610b130c8) | Feb 05, 2022 |
| ASUSTek       | K73SV                       | Notebook    | [519bc1d808](https://linux-hardware.org/?probe=519bc1d808) | Feb 05, 2022 |
| ASUSTek       | PRIME TRX40-PRO S           | Desktop     | [cc04fe990c](https://linux-hardware.org/?probe=cc04fe990c) | Feb 03, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [0b95e33d17](https://linux-hardware.org/?probe=0b95e33d17) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | Desktop     | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [690ef309e9](https://linux-hardware.org/?probe=690ef309e9) | Feb 03, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [3171e9710d](https://linux-hardware.org/?probe=3171e9710d) | Feb 03, 2022 |
| ASUSTek       | K95VJ                       | Notebook    | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [a43204a8d7](https://linux-hardware.org/?probe=a43204a8d7) | Feb 02, 2022 |
| Dell          | G3 3500                     | Notebook    | [141e63ae77](https://linux-hardware.org/?probe=141e63ae77) | Feb 02, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [824ae3f413](https://linux-hardware.org/?probe=824ae3f413) | Feb 02, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [e5f15a17d5](https://linux-hardware.org/?probe=e5f15a17d5) | Feb 02, 2022 |
| Sony          | SVE1713F1EW                 | Notebook    | [34db9cd3c0](https://linux-hardware.org/?probe=34db9cd3c0) | Feb 01, 2022 |
| Sony          | VGN-FE31H                   | Notebook    | [a7185cc26a](https://linux-hardware.org/?probe=a7185cc26a) | Feb 01, 2022 |
| Sony          | SVE1713F1EW                 | Notebook    | [591b6e4d01](https://linux-hardware.org/?probe=591b6e4d01) | Feb 01, 2022 |
| BESSTAR Te... | UM300 V1.0                  | Desktop     | [13b724ceeb](https://linux-hardware.org/?probe=13b724ceeb) | Feb 01, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [7b6c2d4857](https://linux-hardware.org/?probe=7b6c2d4857) | Feb 01, 2022 |
| EVGA          | 131-HE-E095                 | Desktop     | [6d45d47131](https://linux-hardware.org/?probe=6d45d47131) | Jan 31, 2022 |
| Unknown       | Unknown                     | Notebook    | [f3b0dd4384](https://linux-hardware.org/?probe=f3b0dd4384) | Jan 31, 2022 |
| BESSTAR Te... | UM300 V1.0                  | Desktop     | [66320a8981](https://linux-hardware.org/?probe=66320a8981) | Jan 31, 2022 |
| MSI           | GE70 2OC\2OD\2OE            | Notebook    | [f9efba7bbf](https://linux-hardware.org/?probe=f9efba7bbf) | Jan 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belgium/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 300       | 15.43%  |
| Ubuntu 18.04                 | 141       | 7.25%   |
| Ubuntu 22.04                 | 97        | 4.99%   |
| Debian 11                    | 50        | 2.57%   |
| OpenMandriva 4.2             | 44        | 2.26%   |
| ArcoLinux Rolling            | 44        | 2.26%   |
| Zorin 16                     | 42        | 2.16%   |
| OpenMandriva 4.3             | 38        | 1.95%   |
| Fedora 36                    | 33        | 1.7%    |
| Ubuntu 20.10                 | 31        | 1.59%   |
| Linux Mint 20.1              | 29        | 1.49%   |
| Ubuntu 19.10                 | 27        | 1.39%   |
| Linux Mint 20.3              | 27        | 1.39%   |
| Manjaro                      | 26        | 1.34%   |
| Linux Mint 19.3              | 26        | 1.34%   |
| Fedora 35                    | 26        | 1.34%   |
| Arch                         | 26        | 1.34%   |
| Xubuntu 20.04                | 24        | 1.23%   |
| Linux Mint 20.2              | 23        | 1.18%   |
| Arch Rolling                 | 22        | 1.13%   |
| Fedora 34                    | 21        | 1.08%   |
| Ubuntu 19.04                 | 20        | 1.03%   |
| Pop!_OS 22.04                | 20        | 1.03%   |
| Pop!_OS 20.04                | 20        | 1.03%   |
| Linux Mint 21                | 20        | 1.03%   |
| openSUSE Tumbleweed-XXXXXXXX | 19        | 0.98%   |
| Linux Mint 20                | 19        | 0.98%   |
| Ubuntu 21.10                 | 17        | 0.87%   |
| OpenMandriva 23.01           | 17        | 0.87%   |
| Ubuntu 21.04                 | 16        | 0.82%   |
| Pop!_OS 21.04                | 16        | 0.82%   |
| KDE neon 20.04               | 16        | 0.82%   |
| Fedora 37                    | 16        | 0.82%   |
| Fedora 33                    | 16        | 0.82%   |
| Fedora 32                    | 15        | 0.77%   |
| Debian 10                    | 15        | 0.77%   |
| EndeavourOS Rolling          | 14        | 0.72%   |
| Ubuntu 18.10                 | 13        | 0.67%   |
| Elementary 6.1               | 13        | 0.67%   |
| Ubuntu 22.10                 | 12        | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 655       | 36.31%  |
| Linux Mint    | 166       | 9.2%    |
| OpenMandriva  | 118       | 6.54%   |
| Fedora        | 117       | 6.49%   |
| Debian        | 87        | 4.82%   |
| Pop!_OS       | 65        | 3.6%    |
| Manjaro       | 62        | 3.44%   |
| Zorin         | 54        | 2.99%   |
| Xubuntu       | 50        | 2.77%   |
| Arch          | 46        | 2.55%   |
| ArcoLinux     | 45        | 2.49%   |
| Kubuntu       | 37        | 2.05%   |
| ROSA          | 30        | 1.66%   |
| openSUSE      | 27        | 1.5%    |
| KDE neon      | 24        | 1.33%   |
| Elementary    | 20        | 1.11%   |
| Ubuntu Unity  | 18        | 1%      |
| Lubuntu       | 18        | 1%      |
| Ubuntu MATE   | 16        | 0.89%   |
| EndeavourOS   | 16        | 0.89%   |
| Gentoo        | 14        | 0.78%   |
| CentOS        | 12        | 0.67%   |
| Kali          | 11        | 0.61%   |
| Endless       | 10        | 0.55%   |
| LMDE          | 8         | 0.44%   |
| BlackPanther  | 8         | 0.44%   |
| Garuda Linux  | 7         | 0.39%   |
| Ubuntu Budgie | 6         | 0.33%   |
| SteamOS       | 6         | 0.33%   |
| Clear Linux   | 5         | 0.28%   |
| MX            | 4         | 0.22%   |
| Ubuntu Studio | 3         | 0.17%   |
| Nobara        | 3         | 0.17%   |
| LinuxFX       | 3         | 0.17%   |
| Rocky Linux   | 2         | 0.11%   |
| Raspbian      | 2         | 0.11%   |
| Peppermint    | 2         | 0.11%   |
| Parrot        | 2         | 0.11%   |
| NixOS         | 2         | 0.11%   |
| Feren OS      | 2         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 43        | 1.93%   |
| 5.16.7-desktop-1omv4003  | 37        | 1.66%   |
| 5.4.0-42-generic         | 29        | 1.3%    |
| 5.4.0-58-generic         | 22        | 0.99%   |
| 5.15.0-56-generic        | 22        | 0.99%   |
| 5.4.0-48-generic         | 21        | 0.94%   |
| 5.3.0-42-generic         | 20        | 0.9%    |
| 5.15.0-46-generic        | 18        | 0.81%   |
| 5.15.0-58-generic        | 17        | 0.76%   |
| 5.15.0-52-generic        | 17        | 0.76%   |
| 5.8.0-48-generic         | 15        | 0.67%   |
| 5.8.0-43-generic         | 15        | 0.67%   |
| 5.4.0-65-generic         | 15        | 0.67%   |
| 5.15.0-48-generic        | 15        | 0.67%   |
| 6.1.1-desktop-1omv2290   | 14        | 0.63%   |
| 5.4.0-66-generic         | 14        | 0.63%   |
| 5.4.0-29-generic         | 14        | 0.63%   |
| 5.3.0-46-generic         | 14        | 0.63%   |
| 5.11.0-38-generic        | 14        | 0.63%   |
| 5.4.0-74-generic         | 13        | 0.58%   |
| 5.4.0-52-generic         | 13        | 0.58%   |
| 5.4.0-40-generic         | 13        | 0.58%   |
| 6.2.6-desktop-1omv2390   | 12        | 0.54%   |
| 5.4.0-37-generic         | 12        | 0.54%   |
| 5.4.0-26-generic         | 12        | 0.54%   |
| 5.19.0-35-generic        | 12        | 0.54%   |
| 5.15.0-53-generic        | 12        | 0.54%   |
| 5.15.0-47-generic        | 12        | 0.54%   |
| 5.15.0-41-generic        | 12        | 0.54%   |
| 5.13.0-28-generic        | 12        | 0.54%   |
| 5.10.0-21-amd64          | 12        | 0.54%   |
| 5.11.0-43-generic        | 11        | 0.49%   |
| 5.11.0-41-generic        | 11        | 0.49%   |
| 5.8.0-53-generic         | 10        | 0.45%   |
| 5.4.0-91-generic         | 10        | 0.45%   |
| 5.4.0-54-generic         | 10        | 0.45%   |
| 5.13.0-39-generic        | 10        | 0.45%   |
| 5.4.0-56-generic         | 9         | 0.4%    |
| 5.3.0-40-generic         | 9         | 0.4%    |
| 5.15.0-60-generic        | 9         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 349       | 16.75%  |
| 5.15.0  | 194       | 9.31%   |
| 5.8.0   | 118       | 5.66%   |
| 4.15.0  | 107       | 5.14%   |
| 5.11.0  | 106       | 5.09%   |
| 5.13.0  | 86        | 4.13%   |
| 5.3.0   | 83        | 3.98%   |
| 5.10.0  | 62        | 2.98%   |
| 5.19.0  | 54        | 2.59%   |
| 5.0.0   | 51        | 2.45%   |
| 5.10.14 | 43        | 2.06%   |
| 5.16.7  | 37        | 1.78%   |
| 4.18.0  | 37        | 1.78%   |
| 4.19.0  | 16        | 0.77%   |
| 6.2.6   | 15        | 0.72%   |
| 6.1.1   | 14        | 0.67%   |
| 4.18.16 | 10        | 0.48%   |
| 6.1.0   | 9         | 0.43%   |
| 6.0.12  | 9         | 0.43%   |
| 6.0.0   | 9         | 0.43%   |
| 5.17.5  | 9         | 0.43%   |
| 4.9.20  | 9         | 0.43%   |
| 6.2.11  | 8         | 0.38%   |
| 5.14.10 | 8         | 0.38%   |
| 6.2.0   | 7         | 0.34%   |
| 6.1.12  | 7         | 0.34%   |
| 5.18.12 | 7         | 0.34%   |
| 5.9.11  | 6         | 0.29%   |
| 5.8.5   | 6         | 0.29%   |
| 5.16.0  | 6         | 0.29%   |
| 5.13.12 | 6         | 0.29%   |
| 4.9.60  | 6         | 0.29%   |
| 4.4.0   | 6         | 0.29%   |
| 3.10.0  | 6         | 0.29%   |
| 6.3.1   | 5         | 0.24%   |
| 6.0.7   | 5         | 0.24%   |
| 6.0.5   | 5         | 0.24%   |
| 6.0.2   | 5         | 0.24%   |
| 5.9.16  | 5         | 0.24%   |
| 5.3.18  | 5         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 378       | 18.63%  |
| 5.15    | 248       | 12.22%  |
| 5.8     | 140       | 6.9%    |
| 5.10    | 139       | 6.85%   |
| 5.11    | 133       | 6.55%   |
| 4.15    | 107       | 5.27%   |
| 5.13    | 105       | 5.17%   |
| 5.3     | 92        | 4.53%   |
| 5.19    | 78        | 3.84%   |
| 5.16    | 73        | 3.6%    |
| 5.0     | 57        | 2.81%   |
| 6.2     | 51        | 2.51%   |
| 6.0     | 48        | 2.37%   |
| 4.18    | 48        | 2.37%   |
| 6.1     | 42        | 2.07%   |
| 5.17    | 38        | 1.87%   |
| 5.18    | 33        | 1.63%   |
| 5.14    | 27        | 1.33%   |
| 5.9     | 26        | 1.28%   |
| 4.9     | 26        | 1.28%   |
| 5.12    | 24        | 1.18%   |
| 4.19    | 23        | 1.13%   |
| 5.6     | 22        | 1.08%   |
| 5.5     | 13        | 0.64%   |
| 5.7     | 12        | 0.59%   |
| 6.3     | 9         | 0.44%   |
| 4.4     | 6         | 0.3%    |
| 3.10    | 6         | 0.3%    |
| 4.13    | 5         | 0.25%   |
| 5.2     | 4         | 0.2%    |
| 5.1     | 4         | 0.2%    |
| 4.12    | 3         | 0.15%   |
| 5.15.96 | 2         | 0.1%    |
| 4.17    | 2         | 0.1%    |
| 4.1     | 2         | 0.1%    |
| 4.2     | 1         | 0.05%   |
| 4.10    | 1         | 0.05%   |
| 2.6     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1664      | 96.69%  |
| i686    | 40        | 2.32%   |
| aarch64 | 14        | 0.81%   |
| armv7l  | 2         | 0.12%   |
| armv6l  | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 788       | 42.71%  |
| KDE5             | 278       | 15.07%  |
| Unknown          | 239       | 12.95%  |
| XFCE             | 156       | 8.46%   |
| X-Cinnamon       | 120       | 6.5%    |
| MATE             | 54        | 2.93%   |
| KDE              | 37        | 2.01%   |
| LXQt             | 26        | 1.41%   |
| Cinnamon         | 20        | 1.08%   |
| Pantheon         | 19        | 1.03%   |
| i3               | 19        | 1.03%   |
| Unity            | 18        | 0.98%   |
| KDE4             | 14        | 0.76%   |
| Budgie           | 10        | 0.54%   |
| sway             | 5         | 0.27%   |
| LXDE             | 5         | 0.27%   |
| GNOME Flashback  | 5         | 0.27%   |
| LeftWM           | 4         | 0.22%   |
| Hyprland         | 4         | 0.22%   |
| Deepin           | 4         | 0.22%   |
| awesome          | 3         | 0.16%   |
| Trinity          | 2         | 0.11%   |
| Openbox          | 2         | 0.11%   |
| lightdm-xsession | 2         | 0.11%   |
| ICEWM            | 2         | 0.11%   |
| chadwm           | 2         | 0.11%   |
| bspwm            | 2         | 0.11%   |
| xmonad           | 1         | 0.05%   |
| spectrwm         | 1         | 0.05%   |
| qtile            | 1         | 0.05%   |
| GNOME Classic    | 1         | 0.05%   |
| Enlightenment    | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1369      | 76.65%  |
| Wayland | 254       | 14.22%  |
| Unknown | 133       | 7.45%   |
| Tty     | 30        | 1.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 866       | 47.74%  |
| SDDM    | 282       | 15.55%  |
| GDM     | 233       | 12.84%  |
| GDM3    | 196       | 10.8%   |
| LightDM | 151       | 8.32%   |
| TDM     | 68        | 3.75%   |
| KDM     | 13        | 0.72%   |
| XDM     | 4         | 0.22%   |
| SLiM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 569       | 31.73%  |
| fr_BE      | 323       | 18.01%  |
| nl_BE      | 287       | 16.01%  |
| Unknown    | 224       | 12.49%  |
| fr_FR      | 100       | 5.58%   |
| en_GB      | 92        | 5.13%   |
| nl_NL      | 82        | 4.57%   |
| C          | 29        | 1.62%   |
| de_DE      | 14        | 0.78%   |
| de_BE      | 10        | 0.56%   |
| pl_PL      | 8         | 0.45%   |
| en_IE      | 7         | 0.39%   |
| ru_RU      | 6         | 0.33%   |
| es_ES      | 5         | 0.28%   |
| ro_RO      | 3         | 0.17%   |
| pt_PT      | 3         | 0.17%   |
| POSIX      | 3         | 0.17%   |
| it_IT      | 3         | 0.17%   |
| en_US.UTF8 | 2         | 0.11%   |
| en_CA      | 2         | 0.11%   |
| en_BE      | 2         | 0.11%   |
| C.UTF8     | 2         | 0.11%   |
| tt_RU      | 1         | 0.06%   |
| tr_TR      | 1         | 0.06%   |
| pt_BR      | 1         | 0.06%   |
| nl_BE.UTF8 | 1         | 0.06%   |
| nl_AW      | 1         | 0.06%   |
| li_BE      | 1         | 0.06%   |
| ku_TR      | 1         | 0.06%   |
| it_CH      | 1         | 0.06%   |
| hu_HU      | 1         | 0.06%   |
| fr_LU      | 1         | 0.06%   |
| fr_FR.UTF8 | 1         | 0.06%   |
| fr_CH      | 1         | 0.06%   |
| en_ZA      | 1         | 0.06%   |
| en_NZ      | 1         | 0.06%   |
| en_IN      | 1         | 0.06%   |
| en_DK      | 1         | 0.06%   |
| bg_BG      | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 887       | 50.28%  |
| EFI  | 877       | 49.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1361      | 76.5%   |
| Btrfs    | 162       | 9.11%   |
| Overlay  | 135       | 7.59%   |
| Unknown  | 64        | 3.6%    |
| Xfs      | 26        | 1.46%   |
| Tmpfs    | 11        | 0.62%   |
| Zfs      | 9         | 0.51%   |
| Ext2     | 8         | 0.45%   |
| Reiserfs | 1         | 0.06%   |
| F2fs     | 1         | 0.06%   |
| Ext3     | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 918       | 51.92%  |
| GPT     | 656       | 37.1%   |
| MBR     | 194       | 10.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1454      | 82.66%  |
| Yes       | 305       | 17.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1222      | 69.71%  |
| Yes       | 531       | 30.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 272       | 15.82%  |
| Hewlett-Packard         | 270       | 15.71%  |
| Dell                    | 230       | 13.38%  |
| Lenovo                  | 228       | 13.26%  |
| MSI                     | 119       | 6.92%   |
| Acer                    | 96        | 5.58%   |
| Gigabyte Technology     | 91        | 5.29%   |
| Medion                  | 57        | 3.32%   |
| ASRock                  | 46        | 2.68%   |
| Apple                   | 39        | 2.27%   |
| Toshiba                 | 32        | 1.86%   |
| Intel                   | 31        | 1.8%    |
| Sony                    | 26        | 1.51%   |
| Packard Bell            | 22        | 1.28%   |
| Notebook                | 22        | 1.28%   |
| Unknown                 | 13        | 0.76%   |
| Raspberry Pi Foundation | 12        | 0.7%    |
| Fujitsu                 | 11        | 0.64%   |
| TUXEDO                  | 9         | 0.52%   |
| Samsung Electronics     | 8         | 0.47%   |
| Valve                   | 7         | 0.41%   |
| Supermicro              | 5         | 0.29%   |
| Fujitsu Siemens         | 5         | 0.29%   |
| Foxconn                 | 5         | 0.29%   |
| PC Specialist           | 4         | 0.23%   |
| Alienware               | 4         | 0.23%   |
| Pegatron                | 3         | 0.17%   |
| Microsoft               | 3         | 0.17%   |
| HUAWEI                  | 3         | 0.17%   |
| Google                  | 3         | 0.17%   |
| Clevo                   | 3         | 0.17%   |
| BESSTAR Tech            | 3         | 0.17%   |
| AMI                     | 3         | 0.17%   |
| Teclast                 | 2         | 0.12%   |
| Shuttle                 | 2         | 0.12%   |
| Razer                   | 2         | 0.12%   |
| Panasonic               | 2         | 0.12%   |
| Nvidia                  | 2         | 0.12%   |
| AZW                     | 2         | 0.12%   |
| YJKC                    | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 23        | 1.34%   |
| Unknown                          | 17        | 0.99%   |
| Valve Jupiter                    | 7         | 0.41%   |
| HP Pavilion g7                   | 7         | 0.41%   |
| HP Pavilion Notebook             | 6         | 0.35%   |
| ASRock B450M Pro4                | 6         | 0.35%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5 | 5         | 0.29%   |
| HP ProBook 6570b                 | 5         | 0.29%   |
| HP ProBook 650 G1                | 5         | 0.29%   |
| HP Pavilion dv7                  | 5         | 0.29%   |
| Dell XPS 13 7390                 | 5         | 0.29%   |
| Dell OptiPlex 780                | 5         | 0.29%   |
| Dell Latitude 5530               | 5         | 0.29%   |
| Toshiba Satellite C660           | 4         | 0.23%   |
| RPi Raspberry Pi                 | 4         | 0.23%   |
| MSI MS-7C91                      | 4         | 0.23%   |
| MSI MS-7C37                      | 4         | 0.23%   |
| MSI MS-7B86                      | 4         | 0.23%   |
| HP Pavilion Laptop 15-eh1xxx     | 4         | 0.23%   |
| HP Pavilion Laptop 15-cw0xxx     | 4         | 0.23%   |
| HP Pavilion dv6                  | 4         | 0.23%   |
| HP Pavilion 17                   | 4         | 0.23%   |
| HP EliteBook 850 G8 Notebook PC  | 4         | 0.23%   |
| HP Compaq Elite 8300 SFF         | 4         | 0.23%   |
| Gigabyte X570 AORUS MASTER       | 4         | 0.23%   |
| Gigabyte Spring Peak             | 4         | 0.23%   |
| Gigabyte GB-BRR7H-4800           | 4         | 0.23%   |
| Dell XPS 13 9370                 | 4         | 0.23%   |
| Dell OptiPlex 3010               | 4         | 0.23%   |
| Dell Latitude 5520               | 4         | 0.23%   |
| ASUS ROG STRIX X570-E GAMING     | 4         | 0.23%   |
| ASUS PRIME X570-PRO              | 4         | 0.23%   |
| MSI MS-7A38                      | 3         | 0.17%   |
| MSI MS-7A34                      | 3         | 0.17%   |
| MSI MS-7850                      | 3         | 0.17%   |
| Medion MS-7728                   | 3         | 0.17%   |
| Lenovo Yoga 530-14IKB 81EK       | 3         | 0.17%   |
| Lenovo ThinkPad L390 20NSS1YV0B  | 3         | 0.17%   |
| Lenovo Legion 5 15ARH05 82B5     | 3         | 0.17%   |
| HP ProBook 470 G2                | 3         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 115       | 6.69%   |
| Dell Latitude         | 86        | 5%      |
| Acer Aspire           | 74        | 4.3%    |
| HP Pavilion           | 59        | 3.43%   |
| HP EliteBook          | 54        | 3.14%   |
| HP ProBook            | 41        | 2.39%   |
| Dell XPS              | 37        | 2.15%   |
| HP Compaq             | 36        | 2.09%   |
| Lenovo IdeaPad        | 34        | 1.98%   |
| Dell OptiPlex         | 34        | 1.98%   |
| ASUS PRIME            | 32        | 1.86%   |
| Toshiba Satellite     | 28        | 1.63%   |
| Dell Inspiron         | 25        | 1.45%   |
| ASUS ROG              | 25        | 1.45%   |
| ASUS All              | 23        | 1.34%   |
| Dell Precision        | 22        | 1.28%   |
| Lenovo Yoga           | 17        | 0.99%   |
| HP Laptop             | 17        | 0.99%   |
| ASUS TUF              | 17        | 0.99%   |
| Unknown               | 17        | 0.99%   |
| Lenovo Legion         | 14        | 0.81%   |
| Medion Akoya          | 13        | 0.76%   |
| RPi Raspberry         | 12        | 0.7%    |
| Packard Bell EasyNote | 12        | 0.7%    |
| Lenovo ThinkCentre    | 11        | 0.64%   |
| Dell Vostro           | 11        | 0.64%   |
| HP ZBook              | 9         | 0.52%   |
| HP ENVY               | 9         | 0.52%   |
| Gigabyte X570         | 9         | 0.52%   |
| Valve Jupiter         | 7         | 0.41%   |
| ASUS VivoBook         | 7         | 0.41%   |
| Lenovo ThinkBook      | 6         | 0.35%   |
| Lenovo IdeaCentre     | 6         | 0.35%   |
| HP ProDesk            | 6         | 0.35%   |
| ASRock B450M          | 6         | 0.35%   |
| Acer Nitro            | 6         | 0.35%   |
| Dell Studio           | 5         | 0.29%   |
| ASUS ZenBook          | 5         | 0.29%   |
| ASUS STRIX            | 5         | 0.29%   |
| Packard Bell IMEDIA   | 4         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 168       | 9.77%   |
| 2020    | 163       | 9.48%   |
| 2019    | 156       | 9.08%   |
| 2012    | 139       | 8.09%   |
| 2013    | 126       | 7.33%   |
| 2011    | 125       | 7.27%   |
| 2017    | 103       | 5.99%   |
| 2014    | 100       | 5.82%   |
| 2021    | 93        | 5.41%   |
| 2015    | 86        | 5%      |
| 2008    | 82        | 4.77%   |
| 2010    | 79        | 4.6%    |
| 2016    | 75        | 4.36%   |
| 2009    | 68        | 3.96%   |
| 2022    | 52        | 3.03%   |
| 2007    | 50        | 2.91%   |
| 2006    | 26        | 1.51%   |
| Unknown | 19        | 1.11%   |
| 2005    | 4         | 0.23%   |
| 2023    | 3         | 0.17%   |
| 2004    | 2         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 969       | 56.37%  |
| Desktop        | 618       | 35.95%  |
| Convertible    | 51        | 2.97%   |
| Mini pc        | 22        | 1.28%   |
| All in one     | 19        | 1.11%   |
| System on chip | 17        | 0.99%   |
| Server         | 13        | 0.76%   |
| Tablet         | 10        | 0.58%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1583      | 91.19%  |
| Enabled  | 153       | 8.81%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1715      | 99.77%  |
| Yes  | 4         | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 381       | 21.65%  |
| 16.01-24.0      | 371       | 21.08%  |
| 8.01-16.0       | 330       | 18.75%  |
| 3.01-4.0        | 309       | 17.56%  |
| 32.01-64.0      | 178       | 10.11%  |
| 1.01-2.0        | 60        | 3.41%   |
| 64.01-256.0     | 54        | 3.07%   |
| 24.01-32.0      | 31        | 1.76%   |
| 2.01-3.0        | 22        | 1.25%   |
| 0.51-1.0        | 17        | 0.97%   |
| More than 256.0 | 4         | 0.23%   |
| 0.01-0.5        | 3         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 664       | 33.84%  |
| 2.01-3.0    | 492       | 25.08%  |
| 4.01-8.0    | 283       | 14.42%  |
| 3.01-4.0    | 254       | 12.95%  |
| 0.51-1.0    | 127       | 6.47%   |
| 8.01-16.0   | 94        | 4.79%   |
| 0.01-0.5    | 32        | 1.63%   |
| 24.01-32.0  | 7         | 0.36%   |
| 16.01-24.0  | 7         | 0.36%   |
| 64.01-256.0 | 1         | 0.05%   |
| Unknown     | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1025      | 57.39%  |
| 2       | 449       | 25.14%  |
| 3       | 138       | 7.73%   |
| 4       | 80        | 4.48%   |
| 5       | 43        | 2.41%   |
| 6       | 20        | 1.12%   |
| 0       | 16        | 0.9%    |
| 9       | 4         | 0.22%   |
| 8       | 4         | 0.22%   |
| 7       | 4         | 0.22%   |
| 16      | 1         | 0.06%   |
| 10      | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 976       | 56.32%  |
| Yes       | 757       | 43.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1547      | 89.47%  |
| No        | 182       | 10.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1301      | 75.2%   |
| No        | 429       | 24.8%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1013      | 57.95%  |
| No        | 735       | 42.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Belgium | 1719      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Brussels       | 232       | 12.15%  |
| Antwerp        | 120       | 6.29%   |
| Ghent          | 79        | 4.14%   |
| Liège         | 51        | 2.67%   |
| Ixelles-Elsene | 45        | 2.36%   |
| Mechelen       | 31        | 1.62%   |
| Leuven         | 26        | 1.36%   |
| Bruges         | 20        | 1.05%   |
| Turnhout       | 19        | 1%      |
| Schaarbeek     | 18        | 0.94%   |
| Uccle          | 16        | 0.84%   |
| Hasselt        | 16        | 0.84%   |
| Anderlecht     | 16        | 0.84%   |
| Aalst          | 15        | 0.79%   |
| Mons           | 14        | 0.73%   |
| La Louvière   | 13        | 0.68%   |
| Namur          | 12        | 0.63%   |
| Lier           | 12        | 0.63%   |
| Etterbeek      | 12        | 0.63%   |
| Wilrijk        | 11        | 0.58%   |
| Sint-Niklaas   | 11        | 0.58%   |
| Roeselare      | 11        | 0.58%   |
| Jette          | 11        | 0.58%   |
| Gavere         | 11        | 0.58%   |
| Charleroi      | 11        | 0.58%   |
| Boom           | 11        | 0.58%   |
| Tournai        | 10        | 0.52%   |
| Seraing        | 10        | 0.52%   |
| Kontich        | 10        | 0.52%   |
| Kanne          | 10        | 0.52%   |
| Duffel         | 10        | 0.52%   |
| Deurne         | 10        | 0.52%   |
| Bilzen         | 10        | 0.52%   |
| Waregem        | 9         | 0.47%   |
| Vilvoorde      | 9         | 0.47%   |
| Sint-Truiden   | 9         | 0.47%   |
| Mortsel        | 9         | 0.47%   |
| Langdorp       | 9         | 0.47%   |
| Harelbeke      | 9         | 0.47%   |
| Brasschaat     | 9         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 523       | 920    | 20.75%  |
| WDC                         | 377       | 623    | 14.96%  |
| Seagate                     | 376       | 636    | 14.92%  |
| Toshiba                     | 165       | 226    | 6.55%   |
| Kingston                    | 137       | 208    | 5.44%   |
| SanDisk                     | 113       | 148    | 4.48%   |
| Unknown                     | 96        | 132    | 3.81%   |
| Crucial                     | 88        | 125    | 3.49%   |
| Hitachi                     | 80        | 105    | 3.17%   |
| SK hynix                    | 76        | 95     | 3.02%   |
| Intel                       | 69        | 82     | 2.74%   |
| Micron Technology           | 42        | 46     | 1.67%   |
| HGST                        | 42        | 62     | 1.67%   |
| Apple                       | 20        | 25     | 0.79%   |
| Phison                      | 18        | 21     | 0.71%   |
| LITEON                      | 18        | 24     | 0.71%   |
| KIOXIA                      | 18        | 20     | 0.71%   |
| Maxtor                      | 16        | 19     | 0.63%   |
| Intenso                     | 16        | 24     | 0.63%   |
| Corsair                     | 15        | 16     | 0.6%    |
| Fujitsu                     | 13        | 19     | 0.52%   |
| A-DATA Technology           | 13        | 18     | 0.52%   |
| OCZ                         | 12        | 14     | 0.48%   |
| China                       | 12        | 15     | 0.48%   |
| Micron/Crucial Technology   | 11        | 18     | 0.44%   |
| PNY                         | 9         | 10     | 0.36%   |
| LaCie                       | 9         | 12     | 0.36%   |
| LITEONIT                    | 8         | 11     | 0.32%   |
| Transcend                   | 7         | 11     | 0.28%   |
| Silicon Motion              | 7         | 10     | 0.28%   |
| Phison Electronics          | 6         | 7      | 0.24%   |
| LDLC                        | 6         | 7      | 0.24%   |
| Kingston Technology Company | 5         | 5      | 0.2%    |
| KingSpec                    | 5         | 5      | 0.2%    |
| GOODRAM                     | 5         | 8      | 0.2%    |
| ASMT                        | 5         | 5      | 0.2%    |
| SSSTC                       | 4         | 4      | 0.16%   |
| KingFast                    | 4         | 4      | 0.16%   |
| JMicron Technology          | 4         | 6      | 0.16%   |
| XPG                         | 3         | 7      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 31        | 1.09%   |
| Samsung NVMe SSD Drive 1TB                          | 27        | 0.95%   |
| Samsung SSD 850 EVO 250GB                           | 24        | 0.84%   |
| Samsung SSD 850 EVO 500GB                           | 23        | 0.81%   |
| Samsung NVMe SSD Drive 512GB                        | 23        | 0.81%   |
| Kingston SV300S37A120G 120GB SSD                    | 23        | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB                      | 22        | 0.77%   |
| Samsung NVMe SSD Drive 500GB                        | 21        | 0.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 21        | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 20        | 0.7%    |
| Kingston SA400S37120G 120GB SSD                     | 20        | 0.7%    |
| Samsung SSD 860 EVO 250GB                           | 19        | 0.67%   |
| Samsung SSD 860 EVO 1TB                             | 18        | 0.63%   |
| Toshiba DT01ACA100 1TB                              | 17        | 0.6%    |
| Seagate ST2000DM001-1ER164 2TB                      | 16        | 0.56%   |
| Seagate Expansion 1TB                               | 15        | 0.53%   |
| Kingston SA400S37240G 240GB SSD                     | 15        | 0.53%   |
| Intel NVMe SSD Drive 512GB                          | 15        | 0.53%   |
| Toshiba MQ01ABD100 1TB                              | 14        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 0.49%   |
| Samsung SSD 870 EVO 1TB                             | 14        | 0.49%   |
| Unknown MMC Card  32GB                              | 13        | 0.46%   |
| SK hynix NVMe SSD Drive 512GB                       | 13        | 0.46%   |
| Seagate ST9500325AS 500GB                           | 13        | 0.46%   |
| Seagate ST2000DM001-1CH164 2TB                      | 13        | 0.46%   |
| Samsung SSD 840 EVO 250GB                           | 13        | 0.46%   |
| HGST HTS721010A9E630 1TB                            | 13        | 0.46%   |
| Unknown MMC Card  64GB                              | 12        | 0.42%   |
| Seagate ST500DM002-1BD142 500GB                     | 12        | 0.42%   |
| Samsung SSD 970 EVO 1TB                             | 12        | 0.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 12        | 0.42%   |
| Unknown SD/MMC/MS PRO 64GB                          | 11        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB                        | 11        | 0.39%   |
| Samsung SSD 870 QVO 1TB                             | 11        | 0.39%   |
| Crucial CT480BX500SSD1 480GB                        | 11        | 0.39%   |
| Unknown MMC Card  128GB                             | 10        | 0.35%   |
| Seagate ST3500418AS 500GB                           | 10        | 0.35%   |
| Seagate ST2000DM008-2FR102 2TB                      | 10        | 0.35%   |
| Seagate ST1000DM010-2EP102 1TB                      | 10        | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB                      | 10        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 365       | 619    | 36%     |
| WDC                 | 310       | 523    | 30.57%  |
| Toshiba             | 119       | 159    | 11.74%  |
| Hitachi             | 80        | 105    | 7.89%   |
| HGST                | 42        | 62     | 4.14%   |
| Samsung Electronics | 38        | 61     | 3.75%   |
| Maxtor              | 16        | 19     | 1.58%   |
| Fujitsu             | 13        | 18     | 1.28%   |
| Unknown             | 11        | 20     | 1.08%   |
| Apple               | 6         | 6      | 0.59%   |
| LaCie               | 2         | 2      | 0.2%    |
| Hewlett-Packard     | 2         | 4      | 0.2%    |
| WD MediaMax         | 1         | 1      | 0.1%    |
| SINTECHI            | 1         | 1      | 0.1%    |
| Magnetic Data       | 1         | 1      | 0.1%    |
| Lenovo              | 1         | 2      | 0.1%    |
| KESU                | 1         | 3      | 0.1%    |
| Intenso             | 1         | 4      | 0.1%    |
| IET                 | 1         | 3      | 0.1%    |
| Dell                | 1         | 1      | 0.1%    |
| ASMT                | 1         | 1      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 287       | 486    | 34.87%  |
| Kingston            | 109       | 168    | 13.24%  |
| Crucial             | 75        | 108    | 9.11%   |
| SanDisk             | 66        | 89     | 8.02%   |
| WDC                 | 47        | 55     | 5.71%   |
| SK hynix            | 22        | 34     | 2.67%   |
| Toshiba             | 21        | 25     | 2.55%   |
| Intel               | 21        | 24     | 2.55%   |
| Micron Technology   | 16        | 17     | 1.94%   |
| LITEON              | 15        | 21     | 1.82%   |
| Intenso             | 14        | 18     | 1.7%    |
| OCZ                 | 12        | 14     | 1.46%   |
| China               | 12        | 15     | 1.46%   |
| Apple               | 10        | 14     | 1.22%   |
| Corsair             | 9         | 10     | 1.09%   |
| PNY                 | 8         | 9      | 0.97%   |
| LITEONIT            | 8         | 11     | 0.97%   |
| A-DATA Technology   | 7         | 11     | 0.85%   |
| Transcend           | 6         | 10     | 0.73%   |
| GOODRAM             | 5         | 8      | 0.61%   |
| KingSpec            | 4         | 4      | 0.49%   |
| ASMT                | 4         | 4      | 0.49%   |
| Emtec               | 3         | 3      | 0.36%   |
| Zheino              | 2         | 2      | 0.24%   |
| Seagate             | 2         | 2      | 0.24%   |
| Plextor             | 2         | 2      | 0.24%   |
| Phison              | 2         | 2      | 0.24%   |
| KingFast            | 2         | 2      | 0.24%   |
| JMicron Technology  | 2         | 3      | 0.24%   |
| Unknown             | 2         | 2      | 0.24%   |
| WDC WDS             | 1         | 1      | 0.12%   |
| Verbatim            | 1         | 1      | 0.12%   |
| Vaseky              | 1         | 1      | 0.12%   |
| TO Exter            | 1         | 1      | 0.12%   |
| tigo                | 1         | 1      | 0.12%   |
| Teclast             | 1         | 1      | 0.12%   |
| SPCC                | 1         | 2      | 0.12%   |
| SABRENT             | 1         | 1      | 0.12%   |
| Reeinno             | 1         | 3      | 0.12%   |
| Patriot             | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 841       | 1616   | 37.06%  |
| SSD     | 733       | 1208   | 32.3%   |
| NVMe    | 580       | 871    | 25.56%  |
| MMC     | 76        | 93     | 3.35%   |
| Unknown | 39        | 58     | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1257      | 2673   | 61.95%  |
| NVMe | 580       | 871    | 28.59%  |
| SAS  | 116       | 209    | 5.72%   |
| MMC  | 76        | 93     | 3.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 969       | 1595   | 57.44%  |
| 0.51-1.0   | 449       | 761    | 26.62%  |
| 1.01-2.0   | 149       | 254    | 8.83%   |
| 3.01-4.0   | 57        | 109    | 3.38%   |
| 2.01-3.0   | 29        | 46     | 1.72%   |
| 4.01-10.0  | 29        | 50     | 1.72%   |
| 10.01-20.0 | 5         | 9      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 477       | 25.66%  |
| 251-500        | 425       | 22.86%  |
| 501-1000       | 256       | 13.77%  |
| 1001-2000      | 166       | 8.93%   |
| 51-100         | 111       | 5.97%   |
| 1-20           | 110       | 5.92%   |
| More than 3000 | 108       | 5.81%   |
| 2001-3000      | 74        | 3.98%   |
| Unknown        | 73        | 3.93%   |
| 21-50          | 59        | 3.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 694       | 35.83%  |
| 21-50          | 285       | 14.71%  |
| 101-250        | 262       | 13.53%  |
| 51-100         | 195       | 10.07%  |
| 251-500        | 157       | 8.11%   |
| 501-1000       | 121       | 6.25%   |
| 1001-2000      | 86        | 4.44%   |
| Unknown        | 73        | 3.77%   |
| More than 3000 | 33        | 1.7%    |
| 2001-3000      | 31        | 1.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 5         | 25     | 3.23%   |
| Seagate ST9500325AS 500GB           | 4         | 4      | 2.58%   |
| Seagate ST3500418AS 500GB           | 3         | 9      | 1.94%   |
| WDC WD10EZEX-21M2NA0 1TB            | 2         | 2      | 1.29%   |
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 1.29%   |
| Seagate ST9750420AS 752GB           | 2         | 2      | 1.29%   |
| Seagate ST4000DM000-1F2168 4TB      | 2         | 4      | 1.29%   |
| Seagate ST320LT007-9ZV142 320GB     | 2         | 5      | 1.29%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 7      | 1.29%   |
| Samsung Electronics SSD 970 EVO 1TB | 2         | 3      | 1.29%   |
| Kingston SV300S37A120G 120GB SSD    | 2         | 2      | 1.29%   |
| Hitachi HTS545050A7E380 500GB       | 2         | 3      | 1.29%   |
| HGST HTS725050A7E630 500GB          | 2         | 2      | 1.29%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1         | 1      | 0.65%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 0.65%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1         | 1      | 0.65%   |
| WDC WD5000AAKX-07U6AA0 500GB        | 1         | 1      | 0.65%   |
| WDC WD5000AAKS-22A7B0 500GB         | 1         | 1      | 0.65%   |
| WDC WD5000AADS-00S9B0 500GB         | 1         | 1      | 0.65%   |
| WDC WD40EFRX-68N32N0 4TB            | 1         | 1      | 0.65%   |
| WDC WD3200BPVT-55JJ5T0 320GB        | 1         | 1      | 0.65%   |
| WDC WD3200BEVT-60A23T0 320GB        | 1         | 1      | 0.65%   |
| WDC WD3200BEKT-75PVMT1 320GB        | 1         | 5      | 0.65%   |
| WDC WD3200BEKT-60PVMT0 320GB        | 1         | 1      | 0.65%   |
| WDC WD1600JS-60MHB5 160GB           | 1         | 1      | 0.65%   |
| WDC WD10SPCX-60HWST0 1TB            | 1         | 1      | 0.65%   |
| WDC WD10EZRX-00L4HB0 1TB            | 1         | 1      | 0.65%   |
| WDC WD10EZRX-00A8LB0 1TB            | 1         | 1      | 0.65%   |
| WDC WD10EARS-22Y5B1 1TB             | 1         | 1      | 0.65%   |
| WDC WD10EARS-00Y5B1 1TB             | 1         | 2      | 0.65%   |
| WDC WD10EALX-009BA0 1TB             | 1         | 1      | 0.65%   |
| WDC WD10EALS-00Z8A0 1TB             | 1         | 1      | 0.65%   |
| WDC WD10EADS-00P8B0 1TB             | 1         | 1      | 0.65%   |
| WDC WD10EADS-00M2B0 1TB             | 1         | 1      | 0.65%   |
| WDC WD Green M.2 2280 480GB         | 1         | 1      | 0.65%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 0.65%   |
| Toshiba MQ01ABD032 320GB            | 1         | 1      | 0.65%   |
| Toshiba MK6476GSX 640GB             | 1         | 1      | 0.65%   |
| Toshiba MK5075GSX 500GB             | 1         | 1      | 0.65%   |
| Toshiba MK3263GSXN 320GB            | 1         | 1      | 0.65%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 87     | 28.77%  |
| WDC                 | 21        | 29     | 14.38%  |
| Samsung Electronics | 13        | 16     | 8.9%    |
| Hitachi             | 13        | 14     | 8.9%    |
| Toshiba             | 9         | 9      | 6.16%   |
| Intel               | 7         | 7      | 4.79%   |
| Crucial             | 7         | 8      | 4.79%   |
| SK hynix            | 6         | 9      | 4.11%   |
| SanDisk             | 5         | 5      | 3.42%   |
| Kingston            | 5         | 10     | 3.42%   |
| HGST                | 5         | 5      | 3.42%   |
| Maxtor              | 4         | 4      | 2.74%   |
| Fujitsu             | 4         | 8      | 2.74%   |
| Micron Technology   | 2         | 2      | 1.37%   |
| OCZ                 | 1         | 1      | 0.68%   |
| KingFast            | 1         | 1      | 0.68%   |
| A-DATA Technology   | 1         | 1      | 0.68%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 87     | 41.58%  |
| WDC                 | 19        | 27     | 18.81%  |
| Hitachi             | 13        | 14     | 12.87%  |
| Toshiba             | 8         | 8      | 7.92%   |
| Samsung Electronics | 6         | 8      | 5.94%   |
| HGST                | 5         | 5      | 4.95%   |
| Maxtor              | 4         | 4      | 3.96%   |
| Fujitsu             | 4         | 8      | 3.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 99        | 161    | 69.23%  |
| SSD  | 37        | 47     | 25.87%  |
| NVMe | 7         | 8      | 4.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BUCT-63TWBY0 320GB                 | 1         | 1      | 25%     |
| Samsung Electronics MZVLW128HEGR-000L2 128GB | 1         | 2      | 25%     |
| Hitachi HDS721010DLE630 1TB                  | 1         | 1      | 25%     |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 2      | 25%     |
| Hitachi             | 1         | 1      | 25%     |
| HGST                | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1036      | 2333   | 55.64%  |
| Works    | 683       | 1292   | 36.68%  |
| Malfunc  | 139       | 216    | 7.47%   |
| Failed   | 4         | 5      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1179      | 53.88%  |
| AMD                              | 284       | 12.98%  |
| Samsung Electronics              | 255       | 11.65%  |
| SanDisk                          | 73        | 3.34%   |
| SK hynix                         | 52        | 2.38%   |
| Kingston Technology Company      | 33        | 1.51%   |
| JMicron Technology               | 31        | 1.42%   |
| ASMedia Technology               | 31        | 1.42%   |
| Marvell Technology Group         | 30        | 1.37%   |
| Toshiba America Info Systems     | 27        | 1.23%   |
| Phison Electronics               | 27        | 1.23%   |
| Micron Technology                | 26        | 1.19%   |
| Micron/Crucial Technology        | 25        | 1.14%   |
| Nvidia                           | 21        | 0.96%   |
| KIOXIA                           | 18        | 0.82%   |
| ADATA Technology                 | 9         | 0.41%   |
| Union Memory (Shenzhen)          | 8         | 0.37%   |
| Solid State Storage Technology   | 7         | 0.32%   |
| Silicon Motion                   | 7         | 0.32%   |
| Silicon Image                    | 5         | 0.23%   |
| Seagate Technology               | 5         | 0.23%   |
| Broadcom / LSI                   | 5         | 0.23%   |
| LSI Logic / Symbios Logic        | 4         | 0.18%   |
| VIA Technologies                 | 3         | 0.14%   |
| Lite-On Technology               | 3         | 0.14%   |
| Hewlett-Packard                  | 3         | 0.14%   |
| Apple                            | 3         | 0.14%   |
| Transcend                        | 2         | 0.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.09%   |
| Adaptec                          | 2         | 0.09%   |
| Realtek Semiconductor            | 1         | 0.05%   |
| PMC-Sierra                       | 1         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.05%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| HighPoint Technologies           | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |
| Areca Technology                 | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 195       | 7.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 151       | 5.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 95        | 3.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 79        | 3.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 78        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 68        | 2.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 60        | 2.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 48        | 1.89%   |
| AMD 400 Series Chipset SATA Controller                                         | 48        | 1.89%   |
| Samsung NVMe SSD Controller 980                                                | 42        | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 41        | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 37        | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 37        | 1.46%   |
| Intel SATA Controller [RAID mode]                                              | 35        | 1.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 35        | 1.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 34        | 1.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 32        | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 32        | 1.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 32        | 1.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 29        | 1.14%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 29        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 29        | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 28        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 28        | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 27        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 27        | 1.06%   |
| AMD 500 Series Chipset SATA Controller                                         | 27        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 26        | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 26        | 1.02%   |
| Micron NVMe Storage Controller                                                 | 25        | 0.98%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 24        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 23        | 0.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 22        | 0.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 18        | 0.71%   |
| JMicron JMB363 SATA/IDE Controller                                             | 18        | 0.71%   |
| Intel SSD 660P Series                                                          | 18        | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 18        | 0.71%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 16        | 0.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 16        | 0.63%   |
| Intel Comet Lake SATA AHCI Controller                                          | 16        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1232      | 55.35%  |
| NVMe | 585       | 26.28%  |
| IDE  | 232       | 10.42%  |
| RAID | 162       | 7.28%   |
| SAS  | 13        | 0.58%   |
| SCSI | 2         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1338      | 77.84%  |
| AMD     | 364       | 21.18%  |
| ARM     | 15        | 0.87%   |
| Unknown | 2         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 27        | 1.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 22        | 1.28%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 22        | 1.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 20        | 1.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 19        | 1.1%    |
| AMD Ryzen 5 3600 6-Core Processor       | 19        | 1.1%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 16        | 0.93%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 15        | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 14        | 0.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 14        | 0.81%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 14        | 0.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 13        | 0.75%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 12        | 0.7%    |
| ARM Processor                           | 12        | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 11        | 0.64%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 11        | 0.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 11        | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 11        | 0.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 11        | 0.64%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 11        | 0.64%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 11        | 0.64%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 10        | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 10        | 0.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 0.58%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 10        | 0.58%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 10        | 0.58%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 10        | 0.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 10        | 0.58%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 9         | 0.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 9         | 0.52%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 9         | 0.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 9         | 0.52%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 9         | 0.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 8         | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 8         | 0.46%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 8         | 0.46%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 8         | 0.46%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 8         | 0.46%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 8         | 0.46%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 7         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 400       | 23.26%  |
| Intel Core i5           | 385       | 22.38%  |
| Intel Core i3           | 124       | 7.21%   |
| Other                   | 119       | 6.92%   |
| Intel Core 2 Duo        | 91        | 5.29%   |
| AMD Ryzen 5             | 89        | 5.17%   |
| AMD Ryzen 7             | 75        | 4.36%   |
| Intel Celeron           | 45        | 2.62%   |
| AMD Ryzen 9             | 38        | 2.21%   |
| Intel Xeon              | 33        | 1.92%   |
| Intel Pentium           | 30        | 1.74%   |
| Intel Pentium Dual-Core | 22        | 1.28%   |
| Intel Atom              | 22        | 1.28%   |
| Intel Core 2            | 20        | 1.16%   |
| Intel Core 2 Quad       | 19        | 1.1%    |
| AMD Ryzen 7 PRO         | 13        | 0.76%   |
| Intel Core i9           | 12        | 0.7%    |
| AMD E1                  | 12        | 0.7%    |
| AMD Ryzen 5 PRO         | 11        | 0.64%   |
| AMD Ryzen 3             | 10        | 0.58%   |
| AMD E                   | 10        | 0.58%   |
| AMD A8                  | 10        | 0.58%   |
| AMD FX                  | 9         | 0.52%   |
| AMD A6                  | 9         | 0.52%   |
| AMD A4                  | 9         | 0.52%   |
| Intel Pentium Dual      | 8         | 0.47%   |
| Intel Genuine           | 8         | 0.47%   |
| AMD A10                 | 8         | 0.47%   |
| Intel Pentium Silver    | 7         | 0.41%   |
| AMD Phenom II X4        | 7         | 0.41%   |
| Intel Pentium 4         | 5         | 0.29%   |
| AMD Phenom              | 5         | 0.29%   |
| AMD Athlon II X2        | 4         | 0.23%   |
| Intel Xeon Silver       | 3         | 0.17%   |
| Intel Celeron M         | 3         | 0.17%   |
| ARM BCM                 | 3         | 0.17%   |
| AMD Turion 64 X2 Mobile | 3         | 0.17%   |
| AMD Ryzen Threadripper  | 3         | 0.17%   |
| AMD Phenom II X6        | 3         | 0.17%   |
| AMD Athlon II X4        | 3         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 653       | 37.92%  |
| 2       | 649       | 37.69%  |
| 6       | 168       | 9.76%   |
| 8       | 128       | 7.43%   |
| 12      | 42        | 2.44%   |
| 1       | 29        | 1.68%   |
| 10      | 17        | 0.99%   |
| 16      | 12        | 0.7%    |
| Unknown | 7         | 0.41%   |
| 3       | 6         | 0.35%   |
| 14      | 4         | 0.23%   |
| 64      | 2         | 0.12%   |
| 32      | 2         | 0.12%   |
| 128     | 1         | 0.06%   |
| 24      | 1         | 0.06%   |
| 20      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1698      | 98.78%  |
| 2       | 17        | 0.99%   |
| Unknown | 3         | 0.17%   |
| 3       | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1175      | 68.23%  |
| 1       | 540       | 31.36%  |
| Unknown | 7         | 0.41%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1674      | 96.99%  |
| Unknown        | 39        | 2.26%   |
| 32-bit         | 12        | 0.7%    |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 408       | 22.69%  |
| 0x306a9    | 114       | 6.34%   |
| 0x206a7    | 105       | 5.84%   |
| 0x306c3    | 94        | 5.23%   |
| 0x1067a    | 62        | 3.45%   |
| 0x906e9    | 48        | 2.67%   |
| 0x806ea    | 45        | 2.5%    |
| 0x906ea    | 44        | 2.45%   |
| 0x806ec    | 43        | 2.39%   |
| 0x40651    | 37        | 2.06%   |
| 0x506e3    | 33        | 1.84%   |
| 0x20655    | 33        | 1.84%   |
| 0x806c1    | 32        | 1.78%   |
| 0x806e9    | 31        | 1.72%   |
| 0x306d4    | 30        | 1.67%   |
| 0x406e3    | 29        | 1.61%   |
| 0x6fd      | 27        | 1.5%    |
| 0x08701021 | 27        | 1.5%    |
| 0x10676    | 22        | 1.22%   |
| 0xa0652    | 18        | 1%      |
| 0x08600106 | 18        | 1%      |
| 0x0a50000c | 17        | 0.95%   |
| 0x30678    | 15        | 0.83%   |
| 0x106e5    | 15        | 0.83%   |
| 0x08701013 | 15        | 0.83%   |
| 0x6f6      | 14        | 0.78%   |
| 0x806eb    | 13        | 0.72%   |
| 0x6fb      | 13        | 0.72%   |
| 0x08608103 | 13        | 0.72%   |
| 0x08108109 | 12        | 0.67%   |
| 0x206d7    | 11        | 0.61%   |
| 0x20652    | 11        | 0.61%   |
| 0x08600103 | 11        | 0.61%   |
| 0x0a201009 | 10        | 0.56%   |
| 0x05000119 | 10        | 0.56%   |
| 0x010000c8 | 10        | 0.56%   |
| 0x0800820d | 9         | 0.5%    |
| 0x07030105 | 9         | 0.5%    |
| 0x06001119 | 9         | 0.5%    |
| 0x906a4    | 8         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 294       | 17.08%  |
| Haswell          | 166       | 9.65%   |
| IvyBridge        | 140       | 8.13%   |
| SandyBridge      | 138       | 8.02%   |
| Zen 2            | 100       | 5.81%   |
| Penryn           | 98        | 5.69%   |
| Skylake          | 80        | 4.65%   |
| Core             | 74        | 4.3%    |
| Unknown          | 68        | 3.95%   |
| Westmere         | 54        | 3.14%   |
| Zen 3            | 52        | 3.02%   |
| TigerLake        | 47        | 2.73%   |
| CometLake        | 41        | 2.38%   |
| Broadwell        | 39        | 2.27%   |
| Zen+             | 37        | 2.15%   |
| Silvermont       | 37        | 2.15%   |
| Zen              | 27        | 1.57%   |
| K10              | 27        | 1.57%   |
| Nehalem          | 26        | 1.51%   |
| Alderlake Hybrid | 24        | 1.39%   |
| Piledriver       | 19        | 1.1%    |
| Icelake          | 18        | 1.05%   |
| Bobcat           | 17        | 0.99%   |
| Goldmont plus    | 14        | 0.81%   |
| Puma             | 13        | 0.76%   |
| Excavator        | 13        | 0.76%   |
| Jaguar           | 10        | 0.58%   |
| Bonnell          | 10        | 0.58%   |
| K8 Hammer        | 9         | 0.52%   |
| NetBurst         | 8         | 0.46%   |
| P6               | 7         | 0.41%   |
| Goldmont         | 5         | 0.29%   |
| K8 & K10 hybrid  | 3         | 0.17%   |
| Tremont          | 2         | 0.12%   |
| Steamroller      | 2         | 0.12%   |
| K10 Llano        | 2         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 962       | 47.51%  |
| Nvidia                           | 621       | 30.67%  |
| AMD                              | 428       | 21.14%  |
| Matrox Electronics Systems       | 9         | 0.44%   |
| ASPEED Technology                | 3         | 0.15%   |
| VIA Technologies                 | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 87        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 84        | 4.03%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 50        | 2.4%    |
| Intel UHD Graphics 620                                                                   | 49        | 2.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 46        | 2.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 44        | 2.11%   |
| AMD Renoir                                                                               | 37        | 1.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 35        | 1.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 34        | 1.63%   |
| Intel HD Graphics 630                                                                    | 32        | 1.53%   |
| Intel HD Graphics 620                                                                    | 30        | 1.44%   |
| Intel HD Graphics 5500                                                                   | 30        | 1.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 29        | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 29        | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 28        | 1.34%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 25        | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 1.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 25        | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 22        | 1.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 0.91%   |
| Intel HD Graphics 530                                                                    | 19        | 0.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 19        | 0.91%   |
| AMD Lucienne                                                                             | 19        | 0.91%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 18        | 0.86%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 17        | 0.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 17        | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 16        | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 14        | 0.67%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 13        | 0.62%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 13        | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12        | 0.58%   |
| Nvidia GT218 [GeForce 210]                                                               | 11        | 0.53%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 11        | 0.53%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 10        | 0.48%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 10        | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 674       | 38.76%  |
| 1 x Nvidia         | 376       | 21.62%  |
| 1 x AMD            | 337       | 19.38%  |
| Intel + Nvidia     | 217       | 12.48%  |
| Intel + AMD        | 52        | 2.99%   |
| AMD + Nvidia       | 24        | 1.38%   |
| Other              | 21        | 1.21%   |
| 2 x AMD            | 17        | 0.98%   |
| 1 x Matrox         | 9         | 0.52%   |
| 2 x Nvidia         | 3         | 0.17%   |
| 2 x Intel          | 3         | 0.17%   |
| 1 x ASPEED         | 2         | 0.12%   |
| 1 x VIA            | 1         | 0.06%   |
| 1 x SiS            | 1         | 0.06%   |
| Nvidia + ASPEED    | 1         | 0.06%   |
| Intel + 2 x Nvidia | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1353      | 76.79%  |
| Proprietary | 326       | 18.5%   |
| Unknown     | 83        | 4.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 949       | 53.17%  |
| 1.01-2.0   | 217       | 12.16%  |
| 0.01-0.5   | 212       | 11.88%  |
| 0.51-1.0   | 146       | 8.18%   |
| 3.01-4.0   | 98        | 5.49%   |
| 7.01-8.0   | 83        | 4.65%   |
| 5.01-6.0   | 40        | 2.24%   |
| 8.01-16.0  | 25        | 1.4%    |
| 2.01-3.0   | 11        | 0.62%   |
| 16.01-24.0 | 4         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 269       | 14.38%  |
| AU Optronics            | 264       | 14.11%  |
| LG Display              | 185       | 9.89%   |
| Chimei Innolux          | 128       | 6.84%   |
| BOE                     | 113       | 6.04%   |
| Dell                    | 101       | 5.4%    |
| Iiyama                  | 78        | 4.17%   |
| Goldstar                | 70        | 3.74%   |
| Philips                 | 62        | 3.31%   |
| Hewlett-Packard         | 62        | 3.31%   |
| AOC                     | 43        | 2.3%    |
| BenQ                    | 40        | 2.14%   |
| Sharp                   | 38        | 2.03%   |
| Acer                    | 37        | 1.98%   |
| Medion                  | 34        | 1.82%   |
| Lenovo                  | 31        | 1.66%   |
| Chi Mei Optoelectronics | 31        | 1.66%   |
| Apple                   | 31        | 1.66%   |
| Ancor Communications    | 27        | 1.44%   |
| Sony                    | 16        | 0.86%   |
| Unknown                 | 13        | 0.69%   |
| Fujitsu Siemens         | 12        | 0.64%   |
| InfoVision              | 10        | 0.53%   |
| ASUSTek Computer        | 10        | 0.53%   |
| PANDA                   | 9         | 0.48%   |
| LG Philips              | 9         | 0.48%   |
| Eizo                    | 9         | 0.48%   |
| Vestel Elektronik       | 8         | 0.43%   |
| CSO                     | 8         | 0.43%   |
| Idek Iiyama             | 7         | 0.37%   |
| Valve                   | 6         | 0.32%   |
| Panasonic               | 6         | 0.32%   |
| LG Electronics          | 6         | 0.32%   |
| Arnos Instruments       | 6         | 0.32%   |
| Seiko/Epson             | 5         | 0.27%   |
| Packard Bell            | 5         | 0.27%   |
| NEC Computers           | 5         | 0.27%   |
| ViewSonic               | 4         | 0.21%   |
| Toshiba                 | 4         | 0.21%   |
| Quanta Display          | 4         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 17        | 0.86%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 14        | 0.71%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 9         | 0.46%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch            | 9         | 0.46%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 9         | 0.46%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch      | 8         | 0.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 8         | 0.41%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 7         | 0.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 0.35%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 7         | 0.35%   |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch         | 6         | 0.3%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 6         | 0.3%    |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                     | 6         | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 6         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 6         | 0.3%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 5         | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 5         | 0.25%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 5         | 0.25%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch         | 5         | 0.25%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 5         | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 5         | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 5         | 0.25%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                     | 5         | 0.25%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                         | 5         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch          | 5         | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch  | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO149E 1600x900 382x214mm 17.2-inch             | 5         | 0.25%   |
| AOC 27P2DG5 AOC2702 1920x1080 598x336mm 27.0-inch                         | 5         | 0.25%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 4         | 0.2%    |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 4         | 0.2%    |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch       | 4         | 0.2%    |
| Samsung Electronics S24R65x SAM1022 1920x1080 527x296mm 23.8-inch         | 4         | 0.2%    |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch         | 4         | 0.2%    |
| Medion MD 20430 MED36A2 1920x1080 521x293mm 23.5-inch                     | 4         | 0.2%    |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 4         | 0.2%    |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch               | 4         | 0.2%    |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 4         | 0.2%    |
| Iiyama PL2792UH IVM664D 3840x2160 596x335mm 26.9-inch                     | 4         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 789       | 43.88%  |
| 1366x768 (WXGA)    | 221       | 12.29%  |
| 3840x2160 (4K)     | 130       | 7.23%   |
| 1600x900 (HD+)     | 120       | 6.67%   |
| 2560x1440 (QHD)    | 103       | 5.73%   |
| 1680x1050 (WSXGA+) | 68        | 3.78%   |
| 1280x1024 (SXGA)   | 59        | 3.28%   |
| 1440x900 (WXGA+)   | 49        | 2.73%   |
| 1920x1200 (WUXGA)  | 43        | 2.39%   |
| 1280x800 (WXGA)    | 35        | 1.95%   |
| Unknown            | 25        | 1.39%   |
| 3440x1440          | 21        | 1.17%   |
| 3840x1080          | 17        | 0.95%   |
| 2560x1600          | 11        | 0.61%   |
| 2560x1080          | 10        | 0.56%   |
| 1360x768           | 10        | 0.56%   |
| 3840x2400          | 8         | 0.44%   |
| 1600x1200          | 8         | 0.44%   |
| 1024x600           | 7         | 0.39%   |
| 800x1280           | 6         | 0.33%   |
| 3200x1800 (QHD+)   | 6         | 0.33%   |
| 2880x1800          | 5         | 0.28%   |
| 1680x945           | 5         | 0.28%   |
| 1024x768 (XGA)     | 5         | 0.28%   |
| 5760x1080          | 3         | 0.17%   |
| 2736x1824          | 3         | 0.17%   |
| 3840x1600          | 2         | 0.11%   |
| 2960x1050          | 2         | 0.11%   |
| 2256x1504          | 2         | 0.11%   |
| 2048x1152          | 2         | 0.11%   |
| 1920x540           | 2         | 0.11%   |
| 1920x1280          | 2         | 0.11%   |
| 1280x960           | 2         | 0.11%   |
| 7680x2160          | 1         | 0.06%   |
| 6320x1800          | 1         | 0.06%   |
| 5120x1440          | 1         | 0.06%   |
| 4480x1080          | 1         | 0.06%   |
| 3840x1200          | 1         | 0.06%   |
| 3600x1080          | 1         | 0.06%   |
| 3520x1080          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 459       | 24.35%  |
| 17      | 173       | 9.18%   |
| 27      | 165       | 8.75%   |
| 13      | 147       | 7.8%    |
| 24      | 141       | 7.48%   |
| 23      | 129       | 6.84%   |
| Unknown | 109       | 5.78%   |
| 14      | 104       | 5.52%   |
| 21      | 94        | 4.99%   |
| 19      | 49        | 2.6%    |
| 22      | 37        | 1.96%   |
| 18      | 29        | 1.54%   |
| 34      | 28        | 1.49%   |
| 31      | 28        | 1.49%   |
| 20      | 27        | 1.43%   |
| 12      | 24        | 1.27%   |
| 11      | 18        | 0.95%   |
| 25      | 14        | 0.74%   |
| 72      | 12        | 0.64%   |
| 16      | 12        | 0.64%   |
| 84      | 11        | 0.58%   |
| 10      | 11        | 0.58%   |
| 32      | 8         | 0.42%   |
| 54      | 7         | 0.37%   |
| 40      | 7         | 0.37%   |
| 49      | 5         | 0.27%   |
| 7       | 5         | 0.27%   |
| 65      | 3         | 0.16%   |
| 29      | 3         | 0.16%   |
| 26      | 3         | 0.16%   |
| 52      | 2         | 0.11%   |
| 48      | 2         | 0.11%   |
| 46      | 2         | 0.11%   |
| 42      | 2         | 0.11%   |
| 39      | 2         | 0.11%   |
| 37      | 2         | 0.11%   |
| 33      | 2         | 0.11%   |
| 3       | 2         | 0.11%   |
| 142     | 1         | 0.05%   |
| 63      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 625       | 33.55%  |
| 501-600        | 400       | 21.47%  |
| 351-400        | 213       | 11.43%  |
| 401-500        | 195       | 10.47%  |
| 201-300        | 147       | 7.89%   |
| Unknown        | 109       | 5.85%   |
| 601-700        | 67        | 3.6%    |
| 701-800        | 38        | 2.04%   |
| 1001-1500      | 24        | 1.29%   |
| 1501-2000      | 23        | 1.23%   |
| 801-900        | 12        | 0.64%   |
| 1-100          | 6         | 0.32%   |
| 901-1000       | 3         | 0.16%   |
| More than 2000 | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1244      | 73.83%  |
| 16/10   | 219       | 13%     |
| Unknown | 90        | 5.34%   |
| 5/4     | 53        | 3.15%   |
| 21/9    | 31        | 1.84%   |
| 4/3     | 17        | 1.01%   |
| 3/2     | 12        | 0.71%   |
| 6/5     | 6         | 0.36%   |
| 32/9    | 5         | 0.3%    |
| 0.67    | 5         | 0.3%    |
| 1.00    | 2         | 0.12%   |
| 3.73    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 459       | 24.62%  |
| 201-250        | 314       | 16.85%  |
| 301-350        | 169       | 9.07%   |
| 81-90          | 166       | 8.91%   |
| 121-130        | 134       | 7.19%   |
| 151-200        | 115       | 6.17%   |
| Unknown        | 109       | 5.85%   |
| 71-80          | 86        | 4.61%   |
| 351-500        | 69        | 3.7%    |
| 251-300        | 59        | 3.17%   |
| More than 1000 | 40        | 2.15%   |
| 141-150        | 31        | 1.66%   |
| 131-140        | 25        | 1.34%   |
| 61-70          | 22        | 1.18%   |
| 501-1000       | 21        | 1.13%   |
| 51-60          | 18        | 0.97%   |
| 41-50          | 11        | 0.59%   |
| 111-120        | 8         | 0.43%   |
| 1-40           | 6         | 0.32%   |
| 91-100         | 2         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 581       | 31.98%  |
| 121-160       | 492       | 27.08%  |
| 101-120       | 437       | 24.05%  |
| 161-240       | 117       | 6.44%   |
| Unknown       | 109       | 6%      |
| More than 240 | 50        | 2.75%   |
| 1-50          | 31        | 1.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1368      | 77.29%  |
| 2     | 277       | 15.65%  |
| 0     | 90        | 5.08%   |
| 3     | 34        | 1.92%   |
| 4     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 918       | 35.44%  |
| Realtek Semiconductor             | 884       | 34.13%  |
| Qualcomm Atheros                  | 283       | 10.93%  |
| Broadcom                          | 142       | 5.48%   |
| Marvell Technology Group          | 31        | 1.2%    |
| Broadcom Limited                  | 31        | 1.2%    |
| TP-Link                           | 30        | 1.16%   |
| Ralink                            | 24        | 0.93%   |
| MediaTek                          | 24        | 0.93%   |
| Nvidia                            | 20        | 0.77%   |
| D-Link System                     | 17        | 0.66%   |
| ASIX Electronics                  | 15        | 0.58%   |
| Ralink Technology                 | 14        | 0.54%   |
| Lenovo                            | 10        | 0.39%   |
| Dell                              | 10        | 0.39%   |
| IMC Networks                      | 8         | 0.31%   |
| DisplayLink                       | 8         | 0.31%   |
| Sierra Wireless                   | 7         | 0.27%   |
| Microsoft                         | 7         | 0.27%   |
| D-Link                            | 7         | 0.27%   |
| Ericsson Business Mobile Networks | 6         | 0.23%   |
| ASUSTek Computer                  | 6         | 0.23%   |
| Microchip Technology              | 5         | 0.19%   |
| Linksys                           | 5         | 0.19%   |
| JMicron Technology                | 5         | 0.19%   |
| Sitecom Europe                    | 4         | 0.15%   |
| Hewlett-Packard                   | 4         | 0.15%   |
| Fibocom                           | 4         | 0.15%   |
| Aquantia                          | 4         | 0.15%   |
| Samsung Electronics               | 3         | 0.12%   |
| Qualcomm Atheros Communications   | 3         | 0.12%   |
| Qualcomm                          | 3         | 0.12%   |
| Arduino SA                        | 3         | 0.12%   |
| Xiaomi                            | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.08%   |
| Motorola PCS                      | 2         | 0.08%   |
| MosChip Semiconductor             | 2         | 0.08%   |
| Huawei Technologies               | 2         | 0.08%   |
| Google                            | 2         | 0.08%   |
| Edimax Technology                 | 2         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 608       | 19.63%  |
| Intel Wi-Fi 6 AX200                                               | 115       | 3.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 79        | 2.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 76        | 2.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 60        | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 52        | 1.68%   |
| Intel I211 Gigabit Network Connection                             | 49        | 1.58%   |
| Intel Wireless 7260                                               | 47        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 46        | 1.49%   |
| Intel Wireless 8265 / 8275                                        | 44        | 1.42%   |
| Intel Wireless 7265                                               | 37        | 1.19%   |
| Intel Wi-Fi 6 AX201                                               | 35        | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 35        | 1.13%   |
| Intel Wireless 8260                                               | 32        | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 31        | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 31        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 30        | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 30        | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 29        | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 27        | 0.87%   |
| Intel Wireless-AC 9260                                            | 25        | 0.81%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 25        | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 21        | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.61%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 0.61%   |
| Intel Centrino Wireless-N 2230                                    | 19        | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.55%   |
| Intel Ethernet Controller I225-V                                  | 16        | 0.52%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 16        | 0.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 16        | 0.52%   |
| Intel WiFi Link 5100                                              | 15        | 0.48%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 697       | 51.14%  |
| Qualcomm Atheros                      | 221       | 16.21%  |
| Realtek Semiconductor                 | 174       | 12.77%  |
| Broadcom                              | 92        | 6.75%   |
| Ralink                                | 24        | 1.76%   |
| MediaTek                              | 20        | 1.47%   |
| TP-Link                               | 18        | 1.32%   |
| Broadcom Limited                      | 17        | 1.25%   |
| Ralink Technology                     | 14        | 1.03%   |
| D-Link System                         | 14        | 1.03%   |
| IMC Networks                          | 8         | 0.59%   |
| Sierra Wireless                       | 7         | 0.51%   |
| D-Link                                | 7         | 0.51%   |
| Microsoft                             | 6         | 0.44%   |
| ASUSTek Computer                      | 6         | 0.44%   |
| Linksys                               | 5         | 0.37%   |
| Sitecom Europe                        | 4         | 0.29%   |
| Fibocom                               | 4         | 0.29%   |
| Dell                                  | 4         | 0.29%   |
| Qualcomm Atheros Communications       | 3         | 0.22%   |
| Qualcomm                              | 3         | 0.22%   |
| Marvell Technology Group              | 2         | 0.15%   |
| Edimax Technology                     | 2         | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.15%   |
| Z-Com                                 | 1         | 0.07%   |
| Texas Instruments                     | 1         | 0.07%   |
| Realtek                               | 1         | 0.07%   |
| Panasonic (Matsushita)                | 1         | 0.07%   |
| Hewlett-Packard                       | 1         | 0.07%   |
| Guillemot                             | 1         | 0.07%   |
| Gemtek                                | 1         | 0.07%   |
| Belkin Components                     | 1         | 0.07%   |
| AVM                                   | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 115       | 8.38%   |
| Intel Wireless 7260                                                     | 47        | 3.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 46        | 3.35%   |
| Intel Wireless 8265 / 8275                                              | 44        | 3.21%   |
| Intel Wireless 7265                                                     | 37        | 2.7%    |
| Intel Wi-Fi 6 AX201                                                     | 35        | 2.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 35        | 2.55%   |
| Intel Wireless 8260                                                     | 32        | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 31        | 2.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 31        | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 30        | 2.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 30        | 2.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 29        | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.97%   |
| Intel Wireless-AC 9260                                                  | 25        | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 25        | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 25        | 1.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 21        | 1.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 19        | 1.38%   |
| Intel Centrino Wireless-N 2230                                          | 19        | 1.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 16        | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 1.17%   |
| Intel WiFi Link 5100                                                    | 15        | 1.09%   |
| Intel Centrino Advanced-N 6235                                          | 15        | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 14        | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 1.02%   |
| Intel Centrino Advanced-N 6200                                          | 14        | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                           | 14        | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 0.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 13        | 0.95%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 0.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 0.87%   |
| Intel Wireless 3165                                                     | 12        | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 0.87%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 10        | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 0.73%   |
| Intel Wireless 3160                                                     | 10        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 816       | 49.57%  |
| Intel                                  | 497       | 30.19%  |
| Qualcomm Atheros                       | 109       | 6.62%   |
| Broadcom                               | 67        | 4.07%   |
| Marvell Technology Group               | 29        | 1.76%   |
| Nvidia                                 | 20        | 1.22%   |
| ASIX Electronics                       | 15        | 0.91%   |
| Broadcom Limited                       | 14        | 0.85%   |
| TP-Link                                | 11        | 0.67%   |
| Lenovo                                 | 10        | 0.61%   |
| DisplayLink                            | 8         | 0.49%   |
| JMicron Technology                     | 5         | 0.3%    |
| Microchip Technology                   | 4         | 0.24%   |
| MediaTek                               | 4         | 0.24%   |
| Aquantia                               | 4         | 0.24%   |
| Hewlett-Packard                        | 3         | 0.18%   |
| D-Link System                          | 3         | 0.18%   |
| Xiaomi                                 | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.12%   |
| Samsung Electronics                    | 2         | 0.12%   |
| Motorola PCS                           | 2         | 0.12%   |
| MosChip Semiconductor                  | 2         | 0.12%   |
| Google                                 | 2         | 0.12%   |
| Attansic Technology                    | 2         | 0.12%   |
| Apple                                  | 2         | 0.12%   |
| ADMtek                                 | 2         | 0.12%   |
| VIA Technologies                       | 1         | 0.06%   |
| Tehuti Networks                        | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| OPPO Electronics                       | 1         | 0.06%   |
| OpenMoko                               | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| Microsoft                              | 1         | 0.06%   |
| IBM                                    | 1         | 0.06%   |
| Huawei Technologies                    | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 608       | 35.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 79        | 4.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 76        | 4.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 60        | 3.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 52        | 3.08%   |
| Intel I211 Gigabit Network Connection                             | 49        | 2.9%    |
| Intel Ethernet Connection (2) I219-V                              | 25        | 1.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 1.36%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 1.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 1.12%   |
| Intel Ethernet Connection I217-V                                  | 19        | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 1.12%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 1.01%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 1.01%   |
| Intel Ethernet Controller I225-V                                  | 16        | 0.95%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.89%   |
| Intel Ethernet Connection (2) I218-V                              | 15        | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 14        | 0.83%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 0.71%   |
| Intel Ethernet Connection (6) I219-LM                             | 11        | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.65%   |
| Intel 82567LM Gigabit Network Connection                          | 11        | 0.65%   |
| Intel I210 Gigabit Network Connection                             | 10        | 0.59%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.59%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 9         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.53%   |
| Intel 82574L Gigabit Network Connection                           | 8         | 0.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.47%   |
| Intel Ethernet Connection (5) I219-LM                             | 7         | 0.41%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 7         | 0.41%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1541      | 53.56%  |
| WiFi     | 1302      | 45.26%  |
| Modem    | 30        | 1.04%   |
| Unknown  | 4         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 952       | 52.34%  |
| Ethernet | 867       | 47.66%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 990       | 57.29%  |
| 1     | 644       | 37.27%  |
| 3     | 48        | 2.78%   |
| 0     | 34        | 1.97%   |
| 4     | 6         | 0.35%   |
| 5     | 3         | 0.17%   |
| 6     | 2         | 0.12%   |
| 7     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1254      | 70.33%  |
| Yes  | 529       | 29.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 533       | 51.85%  |
| Realtek Semiconductor           | 82        | 7.98%   |
| Qualcomm Atheros Communications | 60        | 5.84%   |
| Broadcom                        | 50        | 4.86%   |
| Cambridge Silicon Radio         | 44        | 4.28%   |
| IMC Networks                    | 41        | 3.99%   |
| Foxconn / Hon Hai               | 36        | 3.5%    |
| Apple                           | 34        | 3.31%   |
| ASUSTek Computer                | 27        | 2.63%   |
| Lite-On Technology              | 25        | 2.43%   |
| Dell                            | 25        | 2.43%   |
| Hewlett-Packard                 | 23        | 2.24%   |
| Toshiba                         | 11        | 1.07%   |
| Belkin Components               | 8         | 0.78%   |
| Ralink                          | 5         | 0.49%   |
| MediaTek                        | 5         | 0.49%   |
| Alps Electric                   | 5         | 0.49%   |
| Foxconn International           | 4         | 0.39%   |
| Ralink Technology               | 2         | 0.19%   |
| Marvell Semiconductor           | 2         | 0.19%   |
| TP-Link                         | 1         | 0.1%    |
| Realtek                         | 1         | 0.1%    |
| Qcom                            | 1         | 0.1%    |
| Micro Star International        | 1         | 0.1%    |
| Logitech                        | 1         | 0.1%    |
| HTC (High Tech Computer)        | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 179       | 17.38%  |
| Intel AX200 Bluetooth                                 | 113       | 10.97%  |
| Intel AX201 Bluetooth                                 | 81        | 7.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 70        | 6.8%    |
| Realtek Bluetooth Radio                               | 47        | 4.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 44        | 4.27%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 29        | 2.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 25        | 2.43%   |
| Realtek  Bluetooth 4.2 Adapter                        | 22        | 2.14%   |
| Intel Bluetooth Device                                | 17        | 1.65%   |
| Qualcomm Atheros  Bluetooth Device                    | 16        | 1.55%   |
| IMC Networks Bluetooth Radio                          | 16        | 1.55%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 15        | 1.46%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 14        | 1.36%   |
| Apple Bluetooth Host Controller                       | 14        | 1.36%   |
| IMC Networks Bluetooth Device                         | 13        | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                    | 13        | 1.26%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 12        | 1.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 11        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 10        | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                      | 10        | 0.97%   |
| HP Broadcom 2070 Bluetooth Combo                      | 10        | 0.97%   |
| Dell DW375 Bluetooth Module                           | 10        | 0.97%   |
| Broadcom HP Portable SoftSailing                      | 10        | 0.97%   |
| Apple Bluetooth USB Host Controller                   | 10        | 0.97%   |
| Intel AX210 Bluetooth                                 | 9         | 0.87%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 9         | 0.87%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 8         | 0.78%   |
| Broadcom BCM2045B (BDC-2.1)                           | 8         | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                      | 7         | 0.68%   |
| Dell BCM20702A0 Bluetooth Module                      | 7         | 0.68%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 6         | 0.58%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 6         | 0.58%   |
| Ralink RT3290 Bluetooth                               | 5         | 0.49%   |
| Lite-On Bluetooth Device                              | 5         | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 5         | 0.49%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 5         | 0.49%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 5         | 0.49%   |
| ASUS ASUS USB-BT500                                   | 5         | 0.49%   |
| Apple Bluetooth HCI                                   | 5         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1287      | 51.87%  |
| Nvidia                               | 466       | 18.78%  |
| AMD                                  | 448       | 18.06%  |
| C-Media Electronics                  | 41        | 1.65%   |
| Logitech                             | 21        | 0.85%   |
| Creative Labs                        | 16        | 0.64%   |
| Kingston Technology                  | 15        | 0.6%    |
| Realtek Semiconductor                | 13        | 0.52%   |
| GN Netcom                            | 11        | 0.44%   |
| Corsair                              | 11        | 0.44%   |
| Plantronics                          | 10        | 0.4%    |
| Hewlett-Packard                      | 9         | 0.36%   |
| Focusrite-Novation                   | 9         | 0.36%   |
| JMTek                                | 7         | 0.28%   |
| RODE Microphones                     | 6         | 0.24%   |
| Razer USA                            | 6         | 0.24%   |
| ASUSTek Computer                     | 6         | 0.24%   |
| VIA Technologies                     | 5         | 0.2%    |
| Texas Instruments                    | 5         | 0.2%    |
| Micro Star International             | 5         | 0.2%    |
| Audio-Technica                       | 5         | 0.2%    |
| SteelSeries ApS                      | 4         | 0.16%   |
| Roland                               | 4         | 0.16%   |
| Generalplus Technology               | 4         | 0.16%   |
| Blue Microphones                     | 4         | 0.16%   |
| Astro Gaming                         | 4         | 0.16%   |
| Sennheiser Communications            | 3         | 0.12%   |
| Lenovo                               | 3         | 0.12%   |
| Trust                                | 2         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.08%   |
| Sony                                 | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.08%   |
| OPPO Electronics                     | 2         | 0.08%   |
| M-Audio                              | 2         | 0.08%   |
| Harman International                 | 2         | 0.08%   |
| GYROCOM C&C                          | 2         | 0.08%   |
| FIFINE Microphones                   | 2         | 0.08%   |
| DSEA A/S                             | 2         | 0.08%   |
| Creative Technology                  | 2         | 0.08%   |
| BEHRINGER International              | 2         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 138       | 4.78%   |
| AMD Family 17h/19h HD Audio Controller                                     | 127       | 4.39%   |
| Intel Sunrise Point-LP HD Audio                                            | 126       | 4.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 120       | 4.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 89        | 3.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 82        | 2.84%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 75        | 2.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 69        | 2.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 69        | 2.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 65        | 2.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 57        | 1.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 54        | 1.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 47        | 1.63%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 47        | 1.63%   |
| Intel Haswell-ULT HD Audio Controller                                      | 45        | 1.56%   |
| Intel 8 Series HD Audio Controller                                         | 45        | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 43        | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 42        | 1.45%   |
| AMD FCH Azalia Controller                                                  | 42        | 1.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 41        | 1.42%   |
| Intel 200 Series PCH HD Audio                                              | 38        | 1.31%   |
| Intel Broadwell-U Audio Controller                                         | 35        | 1.21%   |
| Intel Comet Lake PCH cAVS                                                  | 33        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 32        | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 32        | 1.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 31        | 1.07%   |
| Nvidia High Definition Audio Controller                                    | 30        | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 30        | 1.04%   |
| Nvidia GK107 HDMI Audio Controller                                         | 28        | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                              | 28        | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                   | 28        | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 27        | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 27        | 0.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 27        | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                              | 26        | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                               | 26        | 0.9%    |
| Intel CM238 HD Audio Controller                                            | 25        | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 24        | 0.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 23        | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 22        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 251       | 23.81%  |
| SK hynix            | 196       | 18.6%   |
| Kingston            | 125       | 11.86%  |
| Corsair             | 112       | 10.63%  |
| Micron Technology   | 100       | 9.49%   |
| Unknown             | 77        | 7.31%   |
| Crucial             | 54        | 5.12%   |
| G.Skill             | 31        | 2.94%   |
| Elpida              | 21        | 1.99%   |
| Ramaxel Technology  | 19        | 1.8%    |
| Nanya Technology    | 18        | 1.71%   |
| A-DATA Technology   | 10        | 0.95%   |
| Unknown (ABCD)      | 6         | 0.57%   |
| Unifosa             | 5         | 0.47%   |
| Unknown             | 5         | 0.47%   |
| Transcend           | 4         | 0.38%   |
| Timetec             | 2         | 0.19%   |
| Team                | 2         | 0.19%   |
| Patriot             | 2         | 0.19%   |
| GOODRAM             | 2         | 0.19%   |
| Unknown (0x8551)    | 1         | 0.09%   |
| Unknown (09D5)      | 1         | 0.09%   |
| TRS STAR            | 1         | 0.09%   |
| TakeMS              | 1         | 0.09%   |
| Qimonda             | 1         | 0.09%   |
| PNY                 | 1         | 0.09%   |
| OCZ                 | 1         | 0.09%   |
| J&A Information     | 1         | 0.09%   |
| GeIL                | 1         | 0.09%   |
| Corsair SerNum0     | 1         | 0.09%   |
| Aeneon              | 1         | 0.09%   |
| A-DA                | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 1.24%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.79%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.79%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 9         | 0.79%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 9         | 0.79%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.71%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.71%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 0.71%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.62%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 7         | 0.62%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.53%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 6         | 0.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.53%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 6         | 0.53%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 6         | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 5         | 0.44%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 5         | 0.44%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.44%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.44%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s                   | 5         | 0.44%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 5         | 0.44%   |
| Unknown                                                          | 5         | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 4         | 0.35%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 4         | 0.35%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.35%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 4         | 0.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.35%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.35%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 4         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 451       | 47.62%  |
| DDR3    | 320       | 33.79%  |
| DDR2    | 55        | 5.81%   |
| SDRAM   | 37        | 3.91%   |
| LPDDR3  | 28        | 2.96%   |
| LPDDR4  | 23        | 2.43%   |
| Unknown | 18        | 1.9%    |
| DDR5    | 7         | 0.74%   |
| LPDDR5  | 4         | 0.42%   |
| DDR     | 4         | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 546       | 58.9%   |
| DIMM         | 315       | 33.98%  |
| Row Of Chips | 59        | 6.36%   |
| Chip         | 4         | 0.43%   |
| FB-DIMM      | 2         | 0.22%   |
| RIMM         | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 370       | 37.07%  |
| 4096  | 273       | 27.35%  |
| 16384 | 170       | 17.03%  |
| 2048  | 119       | 11.92%  |
| 1024  | 32        | 3.21%   |
| 32768 | 28        | 2.81%   |
| 512   | 5         | 0.5%    |
| 8     | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 208       | 20.47%  |
| 3200    | 158       | 15.55%  |
| 2667    | 140       | 13.78%  |
| 2400    | 76        | 7.48%   |
| 1333    | 70        | 6.89%   |
| 2133    | 58        | 5.71%   |
| 1334    | 32        | 3.15%   |
| 667     | 32        | 3.15%   |
| 3600    | 25        | 2.46%   |
| 800     | 21        | 2.07%   |
| 1867    | 16        | 1.57%   |
| Unknown | 15        | 1.48%   |
| 1067    | 14        | 1.38%   |
| 4267    | 10        | 0.98%   |
| 3400    | 10        | 0.98%   |
| 2048    | 10        | 0.98%   |
| 1800    | 10        | 0.98%   |
| 3533    | 9         | 0.89%   |
| 3866    | 8         | 0.79%   |
| 2666    | 8         | 0.79%   |
| 3266    | 7         | 0.69%   |
| 4800    | 6         | 0.59%   |
| 3534    | 6         | 0.59%   |
| 3000    | 6         | 0.59%   |
| 1066    | 5         | 0.49%   |
| 6400    | 4         | 0.39%   |
| 4199    | 4         | 0.39%   |
| 3666    | 4         | 0.39%   |
| 975     | 4         | 0.39%   |
| 533     | 4         | 0.39%   |
| 8400    | 3         | 0.3%    |
| 3800    | 3         | 0.3%    |
| 3733    | 3         | 0.3%    |
| 3100    | 3         | 0.3%    |
| 1866    | 3         | 0.3%    |
| 1639    | 3         | 0.3%    |
| 5200    | 2         | 0.2%    |
| 5600    | 1         | 0.1%    |
| 4266    | 1         | 0.1%    |
| 3933    | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 21        | 41.18%  |
| Brother Industries  | 12        | 23.53%  |
| Canon               | 6         | 11.76%  |
| Seiko Epson         | 5         | 9.8%    |
| Samsung Electronics | 3         | 5.88%   |
| Ricoh               | 1         | 1.96%   |
| Prolific Technology | 1         | 1.96%   |
| Kyocera             | 1         | 1.96%   |
| Dymo-CoStar         | 1         | 1.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                                 | 2         | 3.85%   |
| Samsung ML-1660 Series                                     | 2         | 3.85%   |
| HP ENVY 4500 series                                        | 2         | 3.85%   |
| HP DeskJet 3630 series                                     | 2         | 3.85%   |
| Seiko Epson WF-3010 Series                                 | 1         | 1.92%   |
| Seiko Epson ET-8550 Series                                 | 1         | 1.92%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 1.92%   |
| Samsung SCX-472x Series                                    | 1         | 1.92%   |
| Ricoh SP C250SF                                            | 1         | 1.92%   |
| Prolific PL2305 Parallel Port                              | 1         | 1.92%   |
| Kyocera TASKalfa 250ci                                     | 1         | 1.92%   |
| HP OfficeJet Pro 6960                                      | 1         | 1.92%   |
| HP OfficeJet Pro 69                                        | 1         | 1.92%   |
| HP LaserJet Professional P 1102w                           | 1         | 1.92%   |
| HP LaserJet Pro M148f-M149f                                | 1         | 1.92%   |
| HP LaserJet P4015                                          | 1         | 1.92%   |
| HP LaserJet CM1415fn                                       | 1         | 1.92%   |
| HP LaserJet 3015                                           | 1         | 1.92%   |
| HP LaserJet 1015                                           | 1         | 1.92%   |
| HP EWS UPD                                                 | 1         | 1.92%   |
| HP ENVY Photo 6200 series                                  | 1         | 1.92%   |
| HP ENVY 5540 series                                        | 1         | 1.92%   |
| HP ENVY 4520 series                                        | 1         | 1.92%   |
| HP Deskjet F4500 series                                    | 1         | 1.92%   |
| HP DeskJet F300 series                                     | 1         | 1.92%   |
| HP DeskJet 5650c                                           | 1         | 1.92%   |
| HP DeskJet 5150c                                           | 1         | 1.92%   |
| HP DeskJet 2600 series                                     | 1         | 1.92%   |
| Dymo-CoStar LabelWriter 450                                | 1         | 1.92%   |
| Canon TS5300 series                                        | 1         | 1.92%   |
| Canon TS5100 series                                        | 1         | 1.92%   |
| Canon PIXMA MX920 Series                                   | 1         | 1.92%   |
| Canon PIXMA MP240                                          | 1         | 1.92%   |
| Canon MG5700 series                                        | 1         | 1.92%   |
| Canon iP4900 series                                        | 1         | 1.92%   |
| Brother Printer                                            | 1         | 1.92%   |
| Brother MFC-L2710DW series                                 | 1         | 1.92%   |
| Brother MFC-J6530DW                                        | 1         | 1.92%   |
| Brother MFC-J5730DW                                        | 1         | 1.92%   |
| Brother MFC-J491DW                                         | 1         | 1.92%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 6         | 37.5%   |
| Seiko Epson     | 5         | 31.25%  |
| Canon           | 4         | 25%     |
| AGFA-Gevaert NV | 1         | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]        | 1         | 6.25%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1         | 6.25%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 6.25%   |
| Seiko Epson GT-F700 [Perfection V350]                   | 1         | 6.25%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 6.25%   |
| HP ScanJet G4010                                        | 1         | 6.25%   |
| HP scanjet 8270                                         | 1         | 6.25%   |
| HP ScanJet 4370                                         | 1         | 6.25%   |
| HP ScanJet 3800c                                        | 1         | 6.25%   |
| HP ScanJet 3670                                         | 1         | 6.25%   |
| HP ScanJet 3400cse                                      | 1         | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 6.25%   |
| Canon CanoScan LiDE 210                                 | 1         | 6.25%   |
| Canon CanoScan LiDE 110                                 | 1         | 6.25%   |
| Canon CanoScan 3200F                                    | 1         | 6.25%   |
| AGFA-Gevaert NV Snapscan e40                            | 1         | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 241       | 22.65%  |
| Microdia                               | 109       | 10.24%  |
| Realtek Semiconductor                  | 84        | 7.89%   |
| Logitech                               | 77        | 7.24%   |
| IMC Networks                           | 73        | 6.86%   |
| Sunplus Innovation Technology          | 51        | 4.79%   |
| Acer                                   | 42        | 3.95%   |
| Suyin                                  | 40        | 3.76%   |
| Quanta                                 | 39        | 3.67%   |
| Cheng Uei Precision Industry (Foxlink) | 37        | 3.48%   |
| Bison Electronics                      | 37        | 3.48%   |
| Lite-On Technology                     | 35        | 3.29%   |
| Syntek                                 | 33        | 3.1%    |
| Apple                                  | 33        | 3.1%    |
| Alcor Micro                            | 16        | 1.5%    |
| Ricoh                                  | 14        | 1.32%   |
| Luxvisions Innotech Limited            | 14        | 1.32%   |
| Samsung Electronics                    | 9         | 0.85%   |
| Silicon Motion                         | 6         | 0.56%   |
| Primax Electronics                     | 5         | 0.47%   |
| Lenovo                                 | 5         | 0.47%   |
| Microsoft                              | 4         | 0.38%   |
| Jieli Technology                       | 4         | 0.38%   |
| Generalplus Technology                 | 4         | 0.38%   |
| Creative Technology                    | 4         | 0.38%   |
| Z-Star Microelectronics                | 3         | 0.28%   |
| Trust                                  | 3         | 0.28%   |
| Importek                               | 3         | 0.28%   |
| ALi                                    | 3         | 0.28%   |
| WaveRider Communications               | 2         | 0.19%   |
| Sunplus Technology                     | 2         | 0.19%   |
| STEREOLABS                             | 2         | 0.19%   |
| Pixart Imaging                         | 2         | 0.19%   |
| KYE Systems (Mouse Systems)            | 2         | 0.19%   |
| Hewlett-Packard                        | 2         | 0.19%   |
| GEMBIRD                                | 2         | 0.19%   |
| webcam                                 | 1         | 0.09%   |
| Valve Software                         | 1         | 0.09%   |
| Sweex                                  | 1         | 0.09%   |
| SunplusIT                              | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                    | 38        | 3.55%   |
| Chicony Integrated Camera                                       | 36        | 3.36%   |
| Microdia Integrated_Webcam_HD                                   | 32        | 2.99%   |
| IMC Networks Integrated Camera                                  | 31        | 2.9%    |
| Syntek Integrated Camera                                        | 22        | 2.06%   |
| Chicony HD Webcam                                               | 18        | 1.68%   |
| Microdia Integrated Webcam                                      | 16        | 1.5%    |
| Chicony USB2.0 Camera                                           | 14        | 1.31%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 13        | 1.21%   |
| Bison Integrated Camera                                         | 13        | 1.21%   |
| Quanta HP HD Camera                                             | 12        | 1.12%   |
| Logitech HD Webcam C525                                         | 12        | 1.12%   |
| Logitech HD Pro Webcam C920                                     | 12        | 1.12%   |
| Lite-On HP HD Camera                                            | 12        | 1.12%   |
| Chicony HP HD Webcam                                            | 12        | 1.12%   |
| Lite-On Integrated Camera                                       | 11        | 1.03%   |
| Chicony HP Wide Vision HD Camera                                | 11        | 1.03%   |
| Acer Integrated Camera                                          | 11        | 1.03%   |
| Sunplus HD WebCam                                               | 10        | 0.93%   |
| Chicony HP HD Camera                                            | 10        | 0.93%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 10        | 0.93%   |
| Apple Built-in iSight                                           | 10        | 0.93%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 9         | 0.84%   |
| Chicony USB2.0 HD UVC WebCam                                    | 9         | 0.84%   |
| Acer BisonCam,NB Pro                                            | 9         | 0.84%   |
| Microdia Camera                                                 | 8         | 0.75%   |
| Logitech Webcam C270                                            | 8         | 0.75%   |
| Chicony USB 2.0 Camera                                          | 8         | 0.75%   |
| Chicony TOSHIBA Web Camera - HD                                 | 8         | 0.75%   |
| Chicony Integrated Camera (1280x720@30)                         | 8         | 0.75%   |
| Chicony EasyCamera                                              | 8         | 0.75%   |
| Apple FaceTime HD Camera (Built-in)                             | 8         | 0.75%   |
| Acer HD Webcam                                                  | 8         | 0.75%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 7         | 0.65%   |
| Realtek USB Camera                                              | 7         | 0.65%   |
| Logitech C922 Pro Stream Webcam                                 | 7         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 7         | 0.65%   |
| Microdia Laptop_Integrated_Webcam_2M                            | 6         | 0.56%   |
| Chicony Integrated HP HD Webcam                                 | 6         | 0.56%   |
| Chicony HP TrueVision HD Camera                                 | 6         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 87        | 38.16%  |
| Validity Sensors           | 76        | 33.33%  |
| Shenzhen Goodix Technology | 22        | 9.65%   |
| AuthenTec                  | 15        | 6.58%   |
| LighTuning Technology      | 9         | 3.95%   |
| Upek                       | 7         | 3.07%   |
| STMicroelectronics         | 7         | 3.07%   |
| Elan Microelectronics      | 4         | 1.75%   |
| DigitalPersona             | 1         | 0.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 11.4%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 25        | 10.96%  |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 4.39%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 8         | 3.51%   |
| Synaptics WBDI                                                             | 8         | 3.51%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 3.51%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 3.51%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 3.07%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 3.07%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 3.07%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 2.63%   |
| Synaptics UWP WBDI                                                         | 6         | 2.63%   |
| Synaptics  WBDI                                                            | 6         | 2.63%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 2.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 2.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 2.63%   |
| Validity Sensors VFS491                                                    | 5         | 2.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 2.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 2.19%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.19%   |
| AuthenTec AES2810                                                          | 5         | 2.19%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.75%   |
| Synaptics WBDI Device                                                      | 4         | 1.75%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 1.75%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.32%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.32%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.32%   |
| AuthenTec AES1600                                                          | 3         | 1.32%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.88%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.88%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.88%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.88%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.88%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.44%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.44%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.44%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.44%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 62        | 32.63%  |
| Alcor Micro                       | 52        | 27.37%  |
| VASCO Data Security International | 20        | 10.53%  |
| Realtek Semiconductor             | 16        | 8.42%   |
| O2 Micro                          | 13        | 6.84%   |
| Lenovo                            | 10        | 5.26%   |
| Advanced Card Systems             | 5         | 2.63%   |
| OmniKey                           | 3         | 1.58%   |
| Upek                              | 2         | 1.05%   |
| Yubico.com                        | 1         | 0.53%   |
| SCM Microsystems                  | 1         | 0.53%   |
| Integrated Technology Express     | 1         | 0.53%   |
| Gemalto (was Gemplus)             | 1         | 0.53%   |
| Feitian Technologies              | 1         | 0.53%   |
| Clay Logic                        | 1         | 0.53%   |
| Cherry                            | 1         | 0.53%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 50        | 26.32%  |
| Broadcom 58200                                                               | 24        | 12.63%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 8.95%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 16        | 8.42%   |
| Broadcom 5880                                                                | 13        | 6.84%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 12        | 6.32%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 5.26%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 5.26%   |
| VASCO Data Security International DIGIPASS 870                               | 8         | 4.21%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 4.21%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 2.11%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.58%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.05%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.05%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.05%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.53%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.53%   |
| OmniKey CardMan 4321                                                         | 1         | 0.53%   |
| Integrated Technology Express SmartCard Reader                               | 1         | 0.53%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.53%   |
| Feitian Technologies SCR301                                                  | 1         | 0.53%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.53%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.53%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.53%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1149      | 64.44%  |
| 1     | 504       | 28.27%  |
| 2     | 100       | 5.61%   |
| 3     | 20        | 1.12%   |
| 4     | 6         | 0.34%   |
| 6     | 2         | 0.11%   |
| 8     | 1         | 0.06%   |
| 5     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 223       | 29.5%   |
| Graphics card            | 154       | 20.37%  |
| Chipcard                 | 133       | 17.59%  |
| Net/wireless             | 64        | 8.47%   |
| Multimedia controller    | 41        | 5.42%   |
| Communication controller | 26        | 3.44%   |
| Camera                   | 19        | 2.51%   |
| Unassigned class         | 17        | 2.25%   |
| Bluetooth                | 17        | 2.25%   |
| Card reader              | 15        | 1.98%   |
| Sound                    | 12        | 1.59%   |
| Storage                  | 11        | 1.46%   |
| Net/ethernet             | 9         | 1.19%   |
| Network                  | 4         | 0.53%   |
| Flash memory             | 4         | 0.53%   |
| Modem                    | 3         | 0.4%    |
| Dvb card                 | 2         | 0.26%   |
| Storage/raid             | 1         | 0.13%   |
| Storage/ide              | 1         | 0.13%   |

