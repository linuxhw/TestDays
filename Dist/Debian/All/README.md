Debian - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Debian.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian/Desktop/README.md) and [notebooks](/Dist/Debian/Notebook/README.md).

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

Total: 13080

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Tactus        | GeoBook 140                 | Notebook    | [0ceb5a3b7c](https://linux-hardware.org/?probe=0ceb5a3b7c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [4787e68a9c](https://linux-hardware.org/?probe=4787e68a9c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [12e105f6da](https://linux-hardware.org/?probe=12e105f6da) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6fd833b58c](https://linux-hardware.org/?probe=6fd833b58c) | Apr 01, 2023 |
| Unknown       | Unknown                     | Soc         | [15a1a38207](https://linux-hardware.org/?probe=15a1a38207) | Apr 01, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [f75af97954](https://linux-hardware.org/?probe=f75af97954) | Apr 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2175527bda](https://linux-hardware.org/?probe=2175527bda) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a5c21e7892](https://linux-hardware.org/?probe=a5c21e7892) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4b873550ab](https://linux-hardware.org/?probe=4b873550ab) | Apr 01, 2023 |
| HP            | Pavilion dv7                | Notebook    | [00bbec023a](https://linux-hardware.org/?probe=00bbec023a) | Apr 01, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [3c163a3b34](https://linux-hardware.org/?probe=3c163a3b34) | Mar 31, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [8d2858a444](https://linux-hardware.org/?probe=8d2858a444) | Mar 31, 2023 |
| ASUSTek       | X202E                       | Notebook    | [cdcccb09e7](https://linux-hardware.org/?probe=cdcccb09e7) | Mar 31, 2023 |
| ASUSTek       | X202E                       | Notebook    | [ac12ec53a3](https://linux-hardware.org/?probe=ac12ec53a3) | Mar 31, 2023 |
| ASUSTek       | TS10                        | Desktop     | [054de4f36a](https://linux-hardware.org/?probe=054de4f36a) | Mar 31, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [35e4f876ca](https://linux-hardware.org/?probe=35e4f876ca) | Mar 31, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [fca09d31a2](https://linux-hardware.org/?probe=fca09d31a2) | Mar 31, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [47f6f4653b](https://linux-hardware.org/?probe=47f6f4653b) | Mar 31, 2023 |
| ASRock        | B760M Pro RS/D4             | Desktop     | [6a63402e9c](https://linux-hardware.org/?probe=6a63402e9c) | Mar 31, 2023 |
| Lenovo        | Yoga 3 11 80J8              | Notebook    | [fce7483fa0](https://linux-hardware.org/?probe=fce7483fa0) | Mar 31, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [3806b33cae](https://linux-hardware.org/?probe=3806b33cae) | Mar 31, 2023 |
| Intel         | S1200BTL E98681-352         | Server      | [6d9ff27de2](https://linux-hardware.org/?probe=6d9ff27de2) | Mar 31, 2023 |
| Intel         | S1200BTL E98681-352         | Server      | [50c3fba233](https://linux-hardware.org/?probe=50c3fba233) | Mar 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [624d23335b](https://linux-hardware.org/?probe=624d23335b) | Mar 31, 2023 |
| Dell          | Latitude E6330              | Notebook    | [ae7a7254b8](https://linux-hardware.org/?probe=ae7a7254b8) | Mar 31, 2023 |
| Dell          | Latitude E6330              | Notebook    | [2239e12384](https://linux-hardware.org/?probe=2239e12384) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [3399c2f210](https://linux-hardware.org/?probe=3399c2f210) | Mar 31, 2023 |
| Dell          | Precision M4700             | Notebook    | [7c93bc178e](https://linux-hardware.org/?probe=7c93bc178e) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [d6b6c88578](https://linux-hardware.org/?probe=d6b6c88578) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [704145641e](https://linux-hardware.org/?probe=704145641e) | Mar 31, 2023 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [56c886069b](https://linux-hardware.org/?probe=56c886069b) | Mar 31, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | Desktop     | [050875ba5f](https://linux-hardware.org/?probe=050875ba5f) | Mar 30, 2023 |
| AZW           | U59                         | Desktop     | [c87edfe3b6](https://linux-hardware.org/?probe=c87edfe3b6) | Mar 30, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [2ca1607b80](https://linux-hardware.org/?probe=2ca1607b80) | Mar 30, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [3494b0fdd9](https://linux-hardware.org/?probe=3494b0fdd9) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | Desktop     | [fbcdd4ed13](https://linux-hardware.org/?probe=fbcdd4ed13) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [de5bf4239c](https://linux-hardware.org/?probe=de5bf4239c) | Mar 30, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [f310910b0e](https://linux-hardware.org/?probe=f310910b0e) | Mar 30, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [990f324256](https://linux-hardware.org/?probe=990f324256) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [76e79f5f19](https://linux-hardware.org/?probe=76e79f5f19) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [78d1316a55](https://linux-hardware.org/?probe=78d1316a55) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [b6226ae481](https://linux-hardware.org/?probe=b6226ae481) | Mar 30, 2023 |
| Fujitsu Si... | D2764-A1 S26361-D2764-A1    | Desktop     | [08af010307](https://linux-hardware.org/?probe=08af010307) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [bf3d484605](https://linux-hardware.org/?probe=bf3d484605) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [3e4d9fac89](https://linux-hardware.org/?probe=3e4d9fac89) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [244ffc8736](https://linux-hardware.org/?probe=244ffc8736) | Mar 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [4d6ae3ef0f](https://linux-hardware.org/?probe=4d6ae3ef0f) | Mar 30, 2023 |
| HP            | 213D A01                    | Desktop     | [d5fb38a71b](https://linux-hardware.org/?probe=d5fb38a71b) | Mar 30, 2023 |
| HP            | 213D A01                    | Desktop     | [79d8e1b64f](https://linux-hardware.org/?probe=79d8e1b64f) | Mar 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [18f4d18529](https://linux-hardware.org/?probe=18f4d18529) | Mar 30, 2023 |
| HP            | 3048h                       | Desktop     | [1a4d86fca8](https://linux-hardware.org/?probe=1a4d86fca8) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e85544a3d7](https://linux-hardware.org/?probe=e85544a3d7) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [82118905ba](https://linux-hardware.org/?probe=82118905ba) | Mar 30, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [4976f6b6b2](https://linux-hardware.org/?probe=4976f6b6b2) | Mar 30, 2023 |
| Dell          | Precision M4800             | Notebook    | [ebd0442adc](https://linux-hardware.org/?probe=ebd0442adc) | Mar 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [6cc34607d1](https://linux-hardware.org/?probe=6cc34607d1) | Mar 30, 2023 |
| Lenovo        | ThinkPad T60 195143U        | Notebook    | [4de196550b](https://linux-hardware.org/?probe=4de196550b) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9251f2d561](https://linux-hardware.org/?probe=9251f2d561) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2d28ba397e](https://linux-hardware.org/?probe=2d28ba397e) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [a771622660](https://linux-hardware.org/?probe=a771622660) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [1e0c5a90c9](https://linux-hardware.org/?probe=1e0c5a90c9) | Mar 29, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [e772d0e916](https://linux-hardware.org/?probe=e772d0e916) | Mar 29, 2023 |
| AZW           | U59                         | Desktop     | [3776cd7fb3](https://linux-hardware.org/?probe=3776cd7fb3) | Mar 29, 2023 |
| AZW           | U59                         | Desktop     | [f7958b8f39](https://linux-hardware.org/?probe=f7958b8f39) | Mar 29, 2023 |
| Medion        | TJ4125                      | Desktop     | [e03693b0f0](https://linux-hardware.org/?probe=e03693b0f0) | Mar 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [38e3ecfb84](https://linux-hardware.org/?probe=38e3ecfb84) | Mar 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [fc06b01f31](https://linux-hardware.org/?probe=fc06b01f31) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [5ac693dbd4](https://linux-hardware.org/?probe=5ac693dbd4) | Mar 29, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [47c758c261](https://linux-hardware.org/?probe=47c758c261) | Mar 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [7d3374d52b](https://linux-hardware.org/?probe=7d3374d52b) | Mar 29, 2023 |
| Intel         | 945GCT-M                    | Desktop     | [d7e65e945e](https://linux-hardware.org/?probe=d7e65e945e) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| HP            | 1495                        | Desktop     | [75702f8b1d](https://linux-hardware.org/?probe=75702f8b1d) | Mar 29, 2023 |
| HP            | 1495                        | Desktop     | [c342260a77](https://linux-hardware.org/?probe=c342260a77) | Mar 29, 2023 |
| ECS           | G31T-M                      | Desktop     | [d6149cbd0d](https://linux-hardware.org/?probe=d6149cbd0d) | Mar 29, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [5c6734f5e6](https://linux-hardware.org/?probe=5c6734f5e6) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [dadeec8815](https://linux-hardware.org/?probe=dadeec8815) | Mar 29, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [bf9252a1ac](https://linux-hardware.org/?probe=bf9252a1ac) | Mar 29, 2023 |
| Medion        | P7641 MD99856               | Notebook    | [7347a28d53](https://linux-hardware.org/?probe=7347a28d53) | Mar 28, 2023 |
| HP            | 89B4 A                      | Desktop     | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| HP            | Pavilion dv5000 (EW771EA... | Notebook    | [db28f35ce0](https://linux-hardware.org/?probe=db28f35ce0) | Mar 28, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [289bd8c2fd](https://linux-hardware.org/?probe=289bd8c2fd) | Mar 28, 2023 |
| THUNDEROBO... | 911 Plus                    | Notebook    | [6617ad47b7](https://linux-hardware.org/?probe=6617ad47b7) | Mar 28, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [4fe0ddab4b](https://linux-hardware.org/?probe=4fe0ddab4b) | Mar 28, 2023 |
| Pegatron      | Maureen                     | Desktop     | [0fdcf4a5bc](https://linux-hardware.org/?probe=0fdcf4a5bc) | Mar 28, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [caf2461355](https://linux-hardware.org/?probe=caf2461355) | Mar 28, 2023 |
| Google        | Swanky                      | Notebook    | [0f32e48b38](https://linux-hardware.org/?probe=0f32e48b38) | Mar 28, 2023 |
| Unknown       | FT2000plus Generic Borad... | Desktop     | [43ec5396f3](https://linux-hardware.org/?probe=43ec5396f3) | Mar 28, 2023 |
| Unknown       | FT2000plus Generic Borad... | Desktop     | [c305aa7562](https://linux-hardware.org/?probe=c305aa7562) | Mar 28, 2023 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [21cf1ad0bb](https://linux-hardware.org/?probe=21cf1ad0bb) | Mar 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [8f1561c37b](https://linux-hardware.org/?probe=8f1561c37b) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [5969fea8f0](https://linux-hardware.org/?probe=5969fea8f0) | Mar 28, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [f281edd494](https://linux-hardware.org/?probe=f281edd494) | Mar 28, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [11cb22743c](https://linux-hardware.org/?probe=11cb22743c) | Mar 27, 2023 |
| Gigabyte      | H97M-HD3                    | Desktop     | [1b531d5ada](https://linux-hardware.org/?probe=1b531d5ada) | Mar 27, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B9C... | Notebook    | [0744b26f5c](https://linux-hardware.org/?probe=0744b26f5c) | Mar 27, 2023 |
| ASRock        | 770 Extreme3                | Desktop     | [9cd5d1485c](https://linux-hardware.org/?probe=9cd5d1485c) | Mar 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [58d5e99cd1](https://linux-hardware.org/?probe=58d5e99cd1) | Mar 27, 2023 |
| HP            | 18E6                        | Desktop     | [a406dc2463](https://linux-hardware.org/?probe=a406dc2463) | Mar 27, 2023 |
| Medion        | TJ4125                      | Desktop     | [571b476915](https://linux-hardware.org/?probe=571b476915) | Mar 27, 2023 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [6180e562dd](https://linux-hardware.org/?probe=6180e562dd) | Mar 27, 2023 |
| GPD           | P3 MAX                      | Notebook    | [b3627909f1](https://linux-hardware.org/?probe=b3627909f1) | Mar 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [17794caffa](https://linux-hardware.org/?probe=17794caffa) | Mar 27, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c1e74d51ee](https://linux-hardware.org/?probe=c1e74d51ee) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ebed945eae](https://linux-hardware.org/?probe=ebed945eae) | Mar 27, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [7cd7234999](https://linux-hardware.org/?probe=7cd7234999) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fd16b858df](https://linux-hardware.org/?probe=fd16b858df) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [33608bbcda](https://linux-hardware.org/?probe=33608bbcda) | Mar 27, 2023 |
| HP            | 895D                        | Desktop     | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [dd84425bc7](https://linux-hardware.org/?probe=dd84425bc7) | Mar 27, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [46fbf61289](https://linux-hardware.org/?probe=46fbf61289) | Mar 27, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [645c8515a1](https://linux-hardware.org/?probe=645c8515a1) | Mar 27, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [cfb8c9d396](https://linux-hardware.org/?probe=cfb8c9d396) | Mar 27, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [5dcd20300a](https://linux-hardware.org/?probe=5dcd20300a) | Mar 27, 2023 |
| ASRockRack    | D1541D4U-2T8R               | Desktop     | [012c10ae8c](https://linux-hardware.org/?probe=012c10ae8c) | Mar 27, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [d1f406ffe7](https://linux-hardware.org/?probe=d1f406ffe7) | Mar 26, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [a4f4013e4e](https://linux-hardware.org/?probe=a4f4013e4e) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [af88fa64c6](https://linux-hardware.org/?probe=af88fa64c6) | Mar 26, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e67759f49b](https://linux-hardware.org/?probe=e67759f49b) | Mar 26, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [2d83ebd124](https://linux-hardware.org/?probe=2d83ebd124) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [d2f95decbe](https://linux-hardware.org/?probe=d2f95decbe) | Mar 26, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [d1c982b241](https://linux-hardware.org/?probe=d1c982b241) | Mar 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [f0d9554e41](https://linux-hardware.org/?probe=f0d9554e41) | Mar 26, 2023 |
| HP            | 83E2                        | Desktop     | [00f64e69cd](https://linux-hardware.org/?probe=00f64e69cd) | Mar 26, 2023 |
| Dell          | Precision 5570              | Notebook    | [454590a1a8](https://linux-hardware.org/?probe=454590a1a8) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [1377a2ea15](https://linux-hardware.org/?probe=1377a2ea15) | Mar 26, 2023 |
| Medion        | TJ4125                      | Desktop     | [74b96baec4](https://linux-hardware.org/?probe=74b96baec4) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [fb8706575a](https://linux-hardware.org/?probe=fb8706575a) | Mar 25, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [76338f95ea](https://linux-hardware.org/?probe=76338f95ea) | Mar 25, 2023 |
| Dell          | Latitude E6330              | Notebook    | [32833b4683](https://linux-hardware.org/?probe=32833b4683) | Mar 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6e459078e7](https://linux-hardware.org/?probe=6e459078e7) | Mar 25, 2023 |
| HP            | 83E2                        | Desktop     | [cd40c6aa18](https://linux-hardware.org/?probe=cd40c6aa18) | Mar 25, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [eb1d734a53](https://linux-hardware.org/?probe=eb1d734a53) | Mar 25, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [de369a751a](https://linux-hardware.org/?probe=de369a751a) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0C40... | Notebook    | [39b2a59543](https://linux-hardware.org/?probe=39b2a59543) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a05e768cca](https://linux-hardware.org/?probe=a05e768cca) | Mar 25, 2023 |
| Dell          | 0PU052                      | Desktop     | [ccea2ad8e8](https://linux-hardware.org/?probe=ccea2ad8e8) | Mar 25, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [9b8ddda3c3](https://linux-hardware.org/?probe=9b8ddda3c3) | Mar 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [9b9a21b7da](https://linux-hardware.org/?probe=9b9a21b7da) | Mar 24, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [cea1787057](https://linux-hardware.org/?probe=cea1787057) | Mar 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [728f83932f](https://linux-hardware.org/?probe=728f83932f) | Mar 24, 2023 |
| ALLDOCUBE     | i1025P                      | Tablet      | [d4acdf3439](https://linux-hardware.org/?probe=d4acdf3439) | Mar 24, 2023 |
| Packard Be... | H17HV                       | Notebook    | [c4bddccbd8](https://linux-hardware.org/?probe=c4bddccbd8) | Mar 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [58f8d5849a](https://linux-hardware.org/?probe=58f8d5849a) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [e6ecf47eda](https://linux-hardware.org/?probe=e6ecf47eda) | Mar 24, 2023 |
| Dell          | Inspiron 7348               | Notebook    | [4011322039](https://linux-hardware.org/?probe=4011322039) | Mar 24, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [4b563f19dd](https://linux-hardware.org/?probe=4b563f19dd) | Mar 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [5a94081c24](https://linux-hardware.org/?probe=5a94081c24) | Mar 24, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [cde421908c](https://linux-hardware.org/?probe=cde421908c) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [1f7c1bfa41](https://linux-hardware.org/?probe=1f7c1bfa41) | Mar 24, 2023 |
| Sony          | SVE1512M6ESI                | Notebook    | [db00c70eb7](https://linux-hardware.org/?probe=db00c70eb7) | Mar 24, 2023 |
| AZW           | U59                         | Desktop     | [b4058b773d](https://linux-hardware.org/?probe=b4058b773d) | Mar 24, 2023 |
| ASUSTek       | N56VJ                       | Notebook    | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| ALLDOCUBE     | i1025P                      | Tablet      | [080e9de73f](https://linux-hardware.org/?probe=080e9de73f) | Mar 23, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [6be57a7e6f](https://linux-hardware.org/?probe=6be57a7e6f) | Mar 23, 2023 |
| Iskratel, ... | IN6011AX                    | Desktop     | [037350830e](https://linux-hardware.org/?probe=037350830e) | Mar 23, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c65fd15277](https://linux-hardware.org/?probe=c65fd15277) | Mar 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c9a721f7d1](https://linux-hardware.org/?probe=c9a721f7d1) | Mar 23, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [6b3cdb2b1a](https://linux-hardware.org/?probe=6b3cdb2b1a) | Mar 23, 2023 |
| HP            | 8715                        | Mini pc     | [9ce704a4b9](https://linux-hardware.org/?probe=9ce704a4b9) | Mar 23, 2023 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [05eb6d08bd](https://linux-hardware.org/?probe=05eb6d08bd) | Mar 23, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [7aa41dd248](https://linux-hardware.org/?probe=7aa41dd248) | Mar 23, 2023 |
| ECS           | G31T-M9                     | Desktop     | [e314bf5403](https://linux-hardware.org/?probe=e314bf5403) | Mar 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [32a4fc1880](https://linux-hardware.org/?probe=32a4fc1880) | Mar 23, 2023 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [26ca87e272](https://linux-hardware.org/?probe=26ca87e272) | Mar 23, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [cb6e3973c8](https://linux-hardware.org/?probe=cb6e3973c8) | Mar 23, 2023 |
| HP            | 0A68h                       | Desktop     | [527cad6ad0](https://linux-hardware.org/?probe=527cad6ad0) | Mar 23, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [517da38f28](https://linux-hardware.org/?probe=517da38f28) | Mar 23, 2023 |
| Acer          | Aspire VN7-791              | Notebook    | [054efde4e8](https://linux-hardware.org/?probe=054efde4e8) | Mar 22, 2023 |
| Unknown       | BQ-H616                     | Soc         | [ba0b4036b6](https://linux-hardware.org/?probe=ba0b4036b6) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [5e97d4fdf3](https://linux-hardware.org/?probe=5e97d4fdf3) | Mar 22, 2023 |
| Gigabyte      | H97M-HD3                    | Desktop     | [ab4dce8483](https://linux-hardware.org/?probe=ab4dce8483) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [92208949d5](https://linux-hardware.org/?probe=92208949d5) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [aa71c25dba](https://linux-hardware.org/?probe=aa71c25dba) | Mar 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [ef5bf53c45](https://linux-hardware.org/?probe=ef5bf53c45) | Mar 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e2fe65e540](https://linux-hardware.org/?probe=e2fe65e540) | Mar 22, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [7b10e71784](https://linux-hardware.org/?probe=7b10e71784) | Mar 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [b96104604a](https://linux-hardware.org/?probe=b96104604a) | Mar 22, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [1f5d2a057c](https://linux-hardware.org/?probe=1f5d2a057c) | Mar 22, 2023 |
| HP            | 3048h                       | Desktop     | [5163f9de22](https://linux-hardware.org/?probe=5163f9de22) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | Notebook    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [468588ab96](https://linux-hardware.org/?probe=468588ab96) | Mar 21, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [849f9d23c7](https://linux-hardware.org/?probe=849f9d23c7) | Mar 21, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [57a69bcf57](https://linux-hardware.org/?probe=57a69bcf57) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230s 20AHS0070... | Notebook    | [9d86eaf558](https://linux-hardware.org/?probe=9d86eaf558) | Mar 21, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [4f2e83ab00](https://linux-hardware.org/?probe=4f2e83ab00) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [4c7add7cd1](https://linux-hardware.org/?probe=4c7add7cd1) | Mar 21, 2023 |
| Gigabyte      | EX38-DS4                    | Desktop     | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [5ca3a1b044](https://linux-hardware.org/?probe=5ca3a1b044) | Mar 21, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6b25c70b9f](https://linux-hardware.org/?probe=6b25c70b9f) | Mar 21, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [8657b8d645](https://linux-hardware.org/?probe=8657b8d645) | Mar 21, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [3b06195ff0](https://linux-hardware.org/?probe=3b06195ff0) | Mar 21, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c5c907b643](https://linux-hardware.org/?probe=c5c907b643) | Mar 21, 2023 |
| Google        | Teemo                       | Desktop     | [3e60b11752](https://linux-hardware.org/?probe=3e60b11752) | Mar 21, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [0acde77545](https://linux-hardware.org/?probe=0acde77545) | Mar 21, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [da9a9373a6](https://linux-hardware.org/?probe=da9a9373a6) | Mar 20, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [b9bf22cc53](https://linux-hardware.org/?probe=b9bf22cc53) | Mar 20, 2023 |
| Dell          | Latitude E6420              | Notebook    | [e564f25125](https://linux-hardware.org/?probe=e564f25125) | Mar 20, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [1d9fe6158b](https://linux-hardware.org/?probe=1d9fe6158b) | Mar 20, 2023 |
| Supermicro    | X10DRi-T4+                  | Desktop     | [3aa5aebaee](https://linux-hardware.org/?probe=3aa5aebaee) | Mar 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [7bc035af43](https://linux-hardware.org/?probe=7bc035af43) | Mar 20, 2023 |
| HP            | 1825                        | Desktop     | [73a2e18f3a](https://linux-hardware.org/?probe=73a2e18f3a) | Mar 20, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [0c4119f8b3](https://linux-hardware.org/?probe=0c4119f8b3) | Mar 20, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [67b681a703](https://linux-hardware.org/?probe=67b681a703) | Mar 20, 2023 |
| Dell          | Latitude 7480               | Notebook    | [00d8228ec6](https://linux-hardware.org/?probe=00d8228ec6) | Mar 20, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [40d6f69489](https://linux-hardware.org/?probe=40d6f69489) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1a21f25ce5](https://linux-hardware.org/?probe=1a21f25ce5) | Mar 20, 2023 |
| Dell          | G3 3590                     | Notebook    | [cba689e7f5](https://linux-hardware.org/?probe=cba689e7f5) | Mar 20, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [ea415770cb](https://linux-hardware.org/?probe=ea415770cb) | Mar 20, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | Notebook    | [9d44bf5769](https://linux-hardware.org/?probe=9d44bf5769) | Mar 20, 2023 |
| TUXEDO        | N13xWU                      | Notebook    | [e9614af654](https://linux-hardware.org/?probe=e9614af654) | Mar 19, 2023 |
| Dell          | Latitude 7480               | Notebook    | [bbdb75bdce](https://linux-hardware.org/?probe=bbdb75bdce) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [b5d9053f1c](https://linux-hardware.org/?probe=b5d9053f1c) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [660ae0f7ed](https://linux-hardware.org/?probe=660ae0f7ed) | Mar 19, 2023 |
| HP            | Pavilion g7                 | Notebook    | [e591ea2173](https://linux-hardware.org/?probe=e591ea2173) | Mar 19, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B8M... | Notebook    | [4cb81db618](https://linux-hardware.org/?probe=4cb81db618) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [d7b27c1822](https://linux-hardware.org/?probe=d7b27c1822) | Mar 19, 2023 |
| Acer          | Aspire V5-552PG             | Notebook    | [d895f0f391](https://linux-hardware.org/?probe=d895f0f391) | Mar 19, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [22bd6400f6](https://linux-hardware.org/?probe=22bd6400f6) | Mar 19, 2023 |
| Intel         | STK2M3W64CC H89289-506      | Desktop     | [5386cc221b](https://linux-hardware.org/?probe=5386cc221b) | Mar 19, 2023 |
| Toshiba       | Satellite C655              | Notebook    | [229dcc2cb0](https://linux-hardware.org/?probe=229dcc2cb0) | Mar 19, 2023 |
| Toshiba       | Satellite C655              | Notebook    | [5037090da8](https://linux-hardware.org/?probe=5037090da8) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [5308592de8](https://linux-hardware.org/?probe=5308592de8) | Mar 19, 2023 |
| Intel         | 945GCT-M                    | Desktop     | [ac83eeefb9](https://linux-hardware.org/?probe=ac83eeefb9) | Mar 19, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [715b1e5c6b](https://linux-hardware.org/?probe=715b1e5c6b) | Mar 18, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [eea214ee38](https://linux-hardware.org/?probe=eea214ee38) | Mar 18, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [b939c61b5a](https://linux-hardware.org/?probe=b939c61b5a) | Mar 18, 2023 |
| Medion        | TJ4125                      | Desktop     | [6895b929a4](https://linux-hardware.org/?probe=6895b929a4) | Mar 18, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1e96b578fa](https://linux-hardware.org/?probe=1e96b578fa) | Mar 18, 2023 |
| Supermicro    | X10SRi-FB                   | Server      | [746daacc72](https://linux-hardware.org/?probe=746daacc72) | Mar 18, 2023 |
| Gigabyte      | Q270M-D3H                   | Desktop     | [b244f2a8fd](https://linux-hardware.org/?probe=b244f2a8fd) | Mar 18, 2023 |
| ASRock        | X570 PG Velocita            | Desktop     | [bc3f2240b9](https://linux-hardware.org/?probe=bc3f2240b9) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d1a16fdb17](https://linux-hardware.org/?probe=d1a16fdb17) | Mar 18, 2023 |
| Fujitsu       | D3601-A1 S26361-D3601-A1    | Desktop     | [ec47c2dcb7](https://linux-hardware.org/?probe=ec47c2dcb7) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [08572d5e7c](https://linux-hardware.org/?probe=08572d5e7c) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [82914cf856](https://linux-hardware.org/?probe=82914cf856) | Mar 18, 2023 |
| Lenovo        | ThinkServer TS440           | Desktop     | [f34d8572e9](https://linux-hardware.org/?probe=f34d8572e9) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d58b6cfe61](https://linux-hardware.org/?probe=d58b6cfe61) | Mar 18, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [262faf6d70](https://linux-hardware.org/?probe=262faf6d70) | Mar 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [252cd1ff88](https://linux-hardware.org/?probe=252cd1ff88) | Mar 18, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [3cdb0bbdf6](https://linux-hardware.org/?probe=3cdb0bbdf6) | Mar 17, 2023 |
| HP            | 198E                        | Desktop     | [23e214216d](https://linux-hardware.org/?probe=23e214216d) | Mar 17, 2023 |
| HP            | 198E                        | Desktop     | [d5d5af66a8](https://linux-hardware.org/?probe=d5d5af66a8) | Mar 17, 2023 |
| Aquarius      | NS585                       | Notebook    | [cd1e92458f](https://linux-hardware.org/?probe=cd1e92458f) | Mar 17, 2023 |
| Dell          | PowerEdge M620              | Desktop     | [c628cb7f90](https://linux-hardware.org/?probe=c628cb7f90) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [2020cf3584](https://linux-hardware.org/?probe=2020cf3584) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [e7ebc0ec0e](https://linux-hardware.org/?probe=e7ebc0ec0e) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [c343e79a84](https://linux-hardware.org/?probe=c343e79a84) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [5391c84cf4](https://linux-hardware.org/?probe=5391c84cf4) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [8fcb466fab](https://linux-hardware.org/?probe=8fcb466fab) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [7aa3efb2fd](https://linux-hardware.org/?probe=7aa3efb2fd) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [8319fcb9da](https://linux-hardware.org/?probe=8319fcb9da) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [6bf9694348](https://linux-hardware.org/?probe=6bf9694348) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [c3c0ef4a31](https://linux-hardware.org/?probe=c3c0ef4a31) | Mar 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [551bb0a214](https://linux-hardware.org/?probe=551bb0a214) | Mar 17, 2023 |
| HP            | 871A                        | Mini pc     | [b4b1c552ad](https://linux-hardware.org/?probe=b4b1c552ad) | Mar 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7a45a46793](https://linux-hardware.org/?probe=7a45a46793) | Mar 17, 2023 |
| Gigabyte      | M52L-S3P                    | Desktop     | [89660a09c2](https://linux-hardware.org/?probe=89660a09c2) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [66f4a76724](https://linux-hardware.org/?probe=66f4a76724) | Mar 17, 2023 |
| HP            | 255 G3                      | Notebook    | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Intel         | NUC12SNKi72 M45201-500      | Mini pc     | [67985889b2](https://linux-hardware.org/?probe=67985889b2) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Dell          | Latitude 7480               | Notebook    | [ee6015f962](https://linux-hardware.org/?probe=ee6015f962) | Mar 17, 2023 |
| MSI           | GF72 8RE                    | Notebook    | [4610dffdcc](https://linux-hardware.org/?probe=4610dffdcc) | Mar 17, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | Desktop     | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| HP            | Notebook                    | Notebook    | [e901631805](https://linux-hardware.org/?probe=e901631805) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [b50b834744](https://linux-hardware.org/?probe=b50b834744) | Mar 16, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [f3ee556fb5](https://linux-hardware.org/?probe=f3ee556fb5) | Mar 16, 2023 |
| Gigabyte      | MZ92-FS0-00 01010101        | Server      | [f1a315b89b](https://linux-hardware.org/?probe=f1a315b89b) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [97d434b3b5](https://linux-hardware.org/?probe=97d434b3b5) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [dd101b4b05](https://linux-hardware.org/?probe=dd101b4b05) | Mar 16, 2023 |
| Dell          | Precision M6800             | Notebook    | [db62a370ed](https://linux-hardware.org/?probe=db62a370ed) | Mar 16, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [e8d00684ac](https://linux-hardware.org/?probe=e8d00684ac) | Mar 16, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [71a45943c1](https://linux-hardware.org/?probe=71a45943c1) | Mar 16, 2023 |
| MicroByte     | ezpad                       | Tablet      | [745babb415](https://linux-hardware.org/?probe=745babb415) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [57f2de5da4](https://linux-hardware.org/?probe=57f2de5da4) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [2a316e6d03](https://linux-hardware.org/?probe=2a316e6d03) | Mar 16, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [c6aa050dd1](https://linux-hardware.org/?probe=c6aa050dd1) | Mar 16, 2023 |
| Dell          | Latitude 7480               | Notebook    | [72069037ca](https://linux-hardware.org/?probe=72069037ca) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [372deb4bed](https://linux-hardware.org/?probe=372deb4bed) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [d8e1601e65](https://linux-hardware.org/?probe=d8e1601e65) | Mar 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [0b9755873a](https://linux-hardware.org/?probe=0b9755873a) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [4e61f760cb](https://linux-hardware.org/?probe=4e61f760cb) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [b7671cbae5](https://linux-hardware.org/?probe=b7671cbae5) | Mar 16, 2023 |
| Gigabyte      | Q270M-D3H                   | Desktop     | [8841b23ef7](https://linux-hardware.org/?probe=8841b23ef7) | Mar 16, 2023 |
| ASRock        | X570 PG Velocita            | Desktop     | [bd8bc5740e](https://linux-hardware.org/?probe=bd8bc5740e) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [3f7d27d637](https://linux-hardware.org/?probe=3f7d27d637) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [bdb510861b](https://linux-hardware.org/?probe=bdb510861b) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [75a93c0ac6](https://linux-hardware.org/?probe=75a93c0ac6) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [e670ea3583](https://linux-hardware.org/?probe=e670ea3583) | Mar 16, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [108d237ebe](https://linux-hardware.org/?probe=108d237ebe) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [b78130eae1](https://linux-hardware.org/?probe=b78130eae1) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [8ea6223dc5](https://linux-hardware.org/?probe=8ea6223dc5) | Mar 16, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b843a727ce](https://linux-hardware.org/?probe=b843a727ce) | Mar 15, 2023 |
| HP            | 8715                        | Mini pc     | [7f9acb1f3e](https://linux-hardware.org/?probe=7f9acb1f3e) | Mar 15, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ee177d0e61](https://linux-hardware.org/?probe=ee177d0e61) | Mar 15, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [a22bba0e53](https://linux-hardware.org/?probe=a22bba0e53) | Mar 15, 2023 |
| Acer          | AO756                       | Notebook    | [21ba8b2996](https://linux-hardware.org/?probe=21ba8b2996) | Mar 15, 2023 |
| Cincoze       | P1101.01.001                | Desktop     | [9443379d5e](https://linux-hardware.org/?probe=9443379d5e) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | Desktop     | [2d3c739ac5](https://linux-hardware.org/?probe=2d3c739ac5) | Mar 15, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [c8c6ab5fce](https://linux-hardware.org/?probe=c8c6ab5fce) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | Desktop     | [f6f29a0f8a](https://linux-hardware.org/?probe=f6f29a0f8a) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [ea280402ca](https://linux-hardware.org/?probe=ea280402ca) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [513385d981](https://linux-hardware.org/?probe=513385d981) | Mar 15, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [82e7940a77](https://linux-hardware.org/?probe=82e7940a77) | Mar 15, 2023 |
| Acer          | Aspire 7720                 | Notebook    | [0f040d8292](https://linux-hardware.org/?probe=0f040d8292) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [0eb13c3117](https://linux-hardware.org/?probe=0eb13c3117) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [6e24f7a3c1](https://linux-hardware.org/?probe=6e24f7a3c1) | Mar 15, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [b952483e9a](https://linux-hardware.org/?probe=b952483e9a) | Mar 15, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f4926b859a](https://linux-hardware.org/?probe=f4926b859a) | Mar 15, 2023 |
| HP            | Mini 210-1000               | Notebook    | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| Unknown       | Unknown                     | Soc         | [946622b351](https://linux-hardware.org/?probe=946622b351) | Mar 15, 2023 |
| HP            | 1495                        | Desktop     | [72769abb34](https://linux-hardware.org/?probe=72769abb34) | Mar 15, 2023 |
| Gigabyte      | H97M-HD3                    | Desktop     | [6831505433](https://linux-hardware.org/?probe=6831505433) | Mar 14, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [15d4cdae49](https://linux-hardware.org/?probe=15d4cdae49) | Mar 14, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [37a6b115cb](https://linux-hardware.org/?probe=37a6b115cb) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [634ae1ae2b](https://linux-hardware.org/?probe=634ae1ae2b) | Mar 14, 2023 |
| ASUSTek       | ZenBook UX534FAC_UX533FA... | Notebook    | [83351958e6](https://linux-hardware.org/?probe=83351958e6) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [a897cf713a](https://linux-hardware.org/?probe=a897cf713a) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [63cbbd1f57](https://linux-hardware.org/?probe=63cbbd1f57) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [f5cbc232d7](https://linux-hardware.org/?probe=f5cbc232d7) | Mar 14, 2023 |
| Dell          | 064N3D A00                  | All in one  | [4721bf0213](https://linux-hardware.org/?probe=4721bf0213) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [aeb56fbebc](https://linux-hardware.org/?probe=aeb56fbebc) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [ee034131c0](https://linux-hardware.org/?probe=ee034131c0) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [438caf3588](https://linux-hardware.org/?probe=438caf3588) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [57d173995a](https://linux-hardware.org/?probe=57d173995a) | Mar 14, 2023 |
| Acer          | Aspire 7739G                | Notebook    | [aeff2df11c](https://linux-hardware.org/?probe=aeff2df11c) | Mar 14, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [812104dae3](https://linux-hardware.org/?probe=812104dae3) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [27c3c24dfc](https://linux-hardware.org/?probe=27c3c24dfc) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [714f8e1321](https://linux-hardware.org/?probe=714f8e1321) | Mar 14, 2023 |
| Acer          | Aspire 7720                 | Notebook    | [b80fa5f7ff](https://linux-hardware.org/?probe=b80fa5f7ff) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [500bee4bb7](https://linux-hardware.org/?probe=500bee4bb7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [189b1a8ec7](https://linux-hardware.org/?probe=189b1a8ec7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [9be2c9ee2b](https://linux-hardware.org/?probe=9be2c9ee2b) | Mar 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [054bb62a67](https://linux-hardware.org/?probe=054bb62a67) | Mar 14, 2023 |
| HP            | ProLiant SL4540 Gen8        | Desktop     | [fb493ce600](https://linux-hardware.org/?probe=fb493ce600) | Mar 14, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [3a99fb6400](https://linux-hardware.org/?probe=3a99fb6400) | Mar 14, 2023 |
| sunxi         | LeMaker Banana Pi           | Soc         | [d27d307085](https://linux-hardware.org/?probe=d27d307085) | Mar 14, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [7a992ff109](https://linux-hardware.org/?probe=7a992ff109) | Mar 14, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [36bcd11bd3](https://linux-hardware.org/?probe=36bcd11bd3) | Mar 14, 2023 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [7733f89d7d](https://linux-hardware.org/?probe=7733f89d7d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d9d4f5649a](https://linux-hardware.org/?probe=d9d4f5649a) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [aca12aa4c5](https://linux-hardware.org/?probe=aca12aa4c5) | Mar 13, 2023 |
| Schenker      | VIA 15 Pro                  | Notebook    | [ef02f8156e](https://linux-hardware.org/?probe=ef02f8156e) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [5c4b7a9754](https://linux-hardware.org/?probe=5c4b7a9754) | Mar 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [6c76af84cb](https://linux-hardware.org/?probe=6c76af84cb) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [481073d13f](https://linux-hardware.org/?probe=481073d13f) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [497a7bdef5](https://linux-hardware.org/?probe=497a7bdef5) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cc878090ee](https://linux-hardware.org/?probe=cc878090ee) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [07ceb1e102](https://linux-hardware.org/?probe=07ceb1e102) | Mar 13, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [8100c63113](https://linux-hardware.org/?probe=8100c63113) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [79fdcb1951](https://linux-hardware.org/?probe=79fdcb1951) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [73e4261a63](https://linux-hardware.org/?probe=73e4261a63) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [44784531d4](https://linux-hardware.org/?probe=44784531d4) | Mar 13, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [e58e88f5fd](https://linux-hardware.org/?probe=e58e88f5fd) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [267c6693a0](https://linux-hardware.org/?probe=267c6693a0) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [bdb4c28449](https://linux-hardware.org/?probe=bdb4c28449) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [d9226f0ad6](https://linux-hardware.org/?probe=d9226f0ad6) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [906f70a5e9](https://linux-hardware.org/?probe=906f70a5e9) | Mar 13, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [f762c7cc29](https://linux-hardware.org/?probe=f762c7cc29) | Mar 13, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [9793c62af0](https://linux-hardware.org/?probe=9793c62af0) | Mar 13, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [9841e70d67](https://linux-hardware.org/?probe=9841e70d67) | Mar 13, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [088b681bdd](https://linux-hardware.org/?probe=088b681bdd) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [0cee087c15](https://linux-hardware.org/?probe=0cee087c15) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4d7dad3628](https://linux-hardware.org/?probe=4d7dad3628) | Mar 13, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [a35e76c9bf](https://linux-hardware.org/?probe=a35e76c9bf) | Mar 13, 2023 |
| Dell          | 09N44V A05                  | Server      | [d1a141052c](https://linux-hardware.org/?probe=d1a141052c) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [881e48f258](https://linux-hardware.org/?probe=881e48f258) | Mar 13, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [bd231fbff6](https://linux-hardware.org/?probe=bd231fbff6) | Mar 12, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6ddc564b5d](https://linux-hardware.org/?probe=6ddc564b5d) | Mar 12, 2023 |
| HP            | 1825                        | Desktop     | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [fd6d58db15](https://linux-hardware.org/?probe=fd6d58db15) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [f69ef4ff89](https://linux-hardware.org/?probe=f69ef4ff89) | Mar 12, 2023 |
| Medion        | TJ4125                      | Desktop     | [5b8893bf40](https://linux-hardware.org/?probe=5b8893bf40) | Mar 12, 2023 |
| Lenovo        | ThinkPad X131e 3367AG9      | Notebook    | [0ff86711d1](https://linux-hardware.org/?probe=0ff86711d1) | Mar 12, 2023 |
| Dell          | Latitude 3510               | Notebook    | [13ed29770d](https://linux-hardware.org/?probe=13ed29770d) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [4dd7be5be9](https://linux-hardware.org/?probe=4dd7be5be9) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [ce0343a044](https://linux-hardware.org/?probe=ce0343a044) | Mar 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2e839dd9f0](https://linux-hardware.org/?probe=2e839dd9f0) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [55a73e2e07](https://linux-hardware.org/?probe=55a73e2e07) | Mar 12, 2023 |
| HP            | ProBook 4415s               | Notebook    | [8b974a2717](https://linux-hardware.org/?probe=8b974a2717) | Mar 12, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | Desktop     | [daf687f0a1](https://linux-hardware.org/?probe=daf687f0a1) | Mar 12, 2023 |
| Medion        | TJ4125                      | Desktop     | [a93f645a7b](https://linux-hardware.org/?probe=a93f645a7b) | Mar 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [158d246d65](https://linux-hardware.org/?probe=158d246d65) | Mar 11, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [c91efb0de0](https://linux-hardware.org/?probe=c91efb0de0) | Mar 11, 2023 |
| MSI           | MS-B1831                    | Desktop     | [a9bfb4f294](https://linux-hardware.org/?probe=a9bfb4f294) | Mar 11, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [988d270005](https://linux-hardware.org/?probe=988d270005) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | Desktop     | [2d0fdf6553](https://linux-hardware.org/?probe=2d0fdf6553) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | Desktop     | [34a92205b4](https://linux-hardware.org/?probe=34a92205b4) | Mar 11, 2023 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | Desktop     | [eff63861e7](https://linux-hardware.org/?probe=eff63861e7) | Mar 11, 2023 |
| Dell          | Precision 5570              | Notebook    | [470ba58973](https://linux-hardware.org/?probe=470ba58973) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | Desktop     | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | Notebook    | [f066472937](https://linux-hardware.org/?probe=f066472937) | Mar 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5d7fdfa3ab](https://linux-hardware.org/?probe=5d7fdfa3ab) | Mar 11, 2023 |
| HP            | 8076 MVB,A                  | Desktop     | [20150077f5](https://linux-hardware.org/?probe=20150077f5) | Mar 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [92e7dacbc6](https://linux-hardware.org/?probe=92e7dacbc6) | Mar 11, 2023 |
| Dell          | Latitude E6430              | Notebook    | [080ad6aa2a](https://linux-hardware.org/?probe=080ad6aa2a) | Mar 11, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [f8e050789f](https://linux-hardware.org/?probe=f8e050789f) | Mar 11, 2023 |
| AZW           | SER                         | Mini pc     | [86a3944105](https://linux-hardware.org/?probe=86a3944105) | Mar 11, 2023 |
| AZW           | SER                         | Mini pc     | [96c3aadd1e](https://linux-hardware.org/?probe=96c3aadd1e) | Mar 11, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [dc1a94966b](https://linux-hardware.org/?probe=dc1a94966b) | Mar 11, 2023 |
| Dell          | Latitude 3320               | Notebook    | [2a58a07005](https://linux-hardware.org/?probe=2a58a07005) | Mar 11, 2023 |
| Dell          | Latitude 3320               | Notebook    | [d17364c0ef](https://linux-hardware.org/?probe=d17364c0ef) | Mar 11, 2023 |
| ASUSTek       | AT3N7A-I                    | Desktop     | [59de62aac5](https://linux-hardware.org/?probe=59de62aac5) | Mar 11, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [c528b16696](https://linux-hardware.org/?probe=c528b16696) | Mar 10, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [823c3530a1](https://linux-hardware.org/?probe=823c3530a1) | Mar 10, 2023 |
| System76      | Gazelle Professional        | Notebook    | [42f5755b1d](https://linux-hardware.org/?probe=42f5755b1d) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [ffb66872c2](https://linux-hardware.org/?probe=ffb66872c2) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [9736a383d7](https://linux-hardware.org/?probe=9736a383d7) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [f9bd57cf06](https://linux-hardware.org/?probe=f9bd57cf06) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [a71d5d0d96](https://linux-hardware.org/?probe=a71d5d0d96) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [35ab0f32c5](https://linux-hardware.org/?probe=35ab0f32c5) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [dd67a26e98](https://linux-hardware.org/?probe=dd67a26e98) | Mar 10, 2023 |
| HP            | ProLiant DL380 Gen9         | Server      | [5f85fdadf1](https://linux-hardware.org/?probe=5f85fdadf1) | Mar 10, 2023 |
| Dell          | 072XWF A03                  | Server      | [87ee1b58e4](https://linux-hardware.org/?probe=87ee1b58e4) | Mar 10, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [87aa621d6a](https://linux-hardware.org/?probe=87aa621d6a) | Mar 10, 2023 |
| Dell          | Latitude 7285               | Notebook    | [dfc4961010](https://linux-hardware.org/?probe=dfc4961010) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [91985ffa00](https://linux-hardware.org/?probe=91985ffa00) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [40499e56d1](https://linux-hardware.org/?probe=40499e56d1) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [3abbf961d5](https://linux-hardware.org/?probe=3abbf961d5) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [734afe2673](https://linux-hardware.org/?probe=734afe2673) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [364b9159c4](https://linux-hardware.org/?probe=364b9159c4) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [276ce8bd7c](https://linux-hardware.org/?probe=276ce8bd7c) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | Notebook    | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [cfacdb386a](https://linux-hardware.org/?probe=cfacdb386a) | Mar 09, 2023 |
| Dell          | Latitude E6440              | Notebook    | [b00f44cd46](https://linux-hardware.org/?probe=b00f44cd46) | Mar 09, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [495614211e](https://linux-hardware.org/?probe=495614211e) | Mar 09, 2023 |
| FriendlyEl... | NanoPC-T4                   | Soc         | [901194d1e1](https://linux-hardware.org/?probe=901194d1e1) | Mar 09, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9946c1c6dc](https://linux-hardware.org/?probe=9946c1c6dc) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5bc1f5d6d8](https://linux-hardware.org/?probe=5bc1f5d6d8) | Mar 09, 2023 |
| Dell          | Latitude E6440              | Notebook    | [3b9229e07a](https://linux-hardware.org/?probe=3b9229e07a) | Mar 09, 2023 |
| ASRock        | G31M-VS2                    | Desktop     | [c098fa3ee0](https://linux-hardware.org/?probe=c098fa3ee0) | Mar 09, 2023 |
| AZW           | MINI S                      | Desktop     | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | Notebook    | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [326cdc81b2](https://linux-hardware.org/?probe=326cdc81b2) | Mar 09, 2023 |
| libre-comp... | aml-s905x-cc                | Soc         | [fba90acf4d](https://linux-hardware.org/?probe=fba90acf4d) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [7f3075e65e](https://linux-hardware.org/?probe=7f3075e65e) | Mar 08, 2023 |
| Medion        | E122X                       | Notebook    | [dad02f1ac7](https://linux-hardware.org/?probe=dad02f1ac7) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [07f425d57f](https://linux-hardware.org/?probe=07f425d57f) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [f62ef69dcc](https://linux-hardware.org/?probe=f62ef69dcc) | Mar 08, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [588a008ee1](https://linux-hardware.org/?probe=588a008ee1) | Mar 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0a5c3f157b](https://linux-hardware.org/?probe=0a5c3f157b) | Mar 08, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [4f55573ba6](https://linux-hardware.org/?probe=4f55573ba6) | Mar 08, 2023 |
| Dell          | Precision 3560              | Notebook    | [0873d45206](https://linux-hardware.org/?probe=0873d45206) | Mar 08, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [d059dad473](https://linux-hardware.org/?probe=d059dad473) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [fc0152a6de](https://linux-hardware.org/?probe=fc0152a6de) | Mar 08, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ac75dbf1f6](https://linux-hardware.org/?probe=ac75dbf1f6) | Mar 08, 2023 |
| HP            | 0AACh                       | Desktop     | [2f4ba72670](https://linux-hardware.org/?probe=2f4ba72670) | Mar 08, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [32d1af5dee](https://linux-hardware.org/?probe=32d1af5dee) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [69dd85d8cf](https://linux-hardware.org/?probe=69dd85d8cf) | Mar 07, 2023 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [cfb630c626](https://linux-hardware.org/?probe=cfb630c626) | Mar 07, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [ced1079ce2](https://linux-hardware.org/?probe=ced1079ce2) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [e6cbad4861](https://linux-hardware.org/?probe=e6cbad4861) | Mar 07, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [cca3440ed3](https://linux-hardware.org/?probe=cca3440ed3) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [6fa1bc8547](https://linux-hardware.org/?probe=6fa1bc8547) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [ce9ba5580b](https://linux-hardware.org/?probe=ce9ba5580b) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [9a8f396913](https://linux-hardware.org/?probe=9a8f396913) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [07709f5f79](https://linux-hardware.org/?probe=07709f5f79) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [8bbc04cb55](https://linux-hardware.org/?probe=8bbc04cb55) | Mar 07, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [a3682a5cb6](https://linux-hardware.org/?probe=a3682a5cb6) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [7b1918ab47](https://linux-hardware.org/?probe=7b1918ab47) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [0d996d4041](https://linux-hardware.org/?probe=0d996d4041) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [eb4c28b498](https://linux-hardware.org/?probe=eb4c28b498) | Mar 07, 2023 |
| MSI           | 880GM-E43                   | Desktop     | [f4027fb865](https://linux-hardware.org/?probe=f4027fb865) | Mar 07, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [e4e709f69a](https://linux-hardware.org/?probe=e4e709f69a) | Mar 07, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [124045e654](https://linux-hardware.org/?probe=124045e654) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ac92e5ce13](https://linux-hardware.org/?probe=ac92e5ce13) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [92f8093adb](https://linux-hardware.org/?probe=92f8093adb) | Mar 07, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [8659fe0f82](https://linux-hardware.org/?probe=8659fe0f82) | Mar 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [242bd44f0c](https://linux-hardware.org/?probe=242bd44f0c) | Mar 07, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [5a1521197e](https://linux-hardware.org/?probe=5a1521197e) | Mar 07, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [119a07048d](https://linux-hardware.org/?probe=119a07048d) | Mar 06, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [91db409270](https://linux-hardware.org/?probe=91db409270) | Mar 06, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [5f0ab2a253](https://linux-hardware.org/?probe=5f0ab2a253) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [a0bccf2d2b](https://linux-hardware.org/?probe=a0bccf2d2b) | Mar 06, 2023 |
| ASUSTek       | X550JX                      | Notebook    | [a9a82b2395](https://linux-hardware.org/?probe=a9a82b2395) | Mar 06, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [19a72f502b](https://linux-hardware.org/?probe=19a72f502b) | Mar 06, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [e93c6204c1](https://linux-hardware.org/?probe=e93c6204c1) | Mar 06, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [ae0bbd2f73](https://linux-hardware.org/?probe=ae0bbd2f73) | Mar 06, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [3f57fb1495](https://linux-hardware.org/?probe=3f57fb1495) | Mar 06, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [423b13a62d](https://linux-hardware.org/?probe=423b13a62d) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [2f63b318f6](https://linux-hardware.org/?probe=2f63b318f6) | Mar 06, 2023 |
| Gigabyte      | Z68X-UD3-B3                 | Desktop     | [f2be73745e](https://linux-hardware.org/?probe=f2be73745e) | Mar 06, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [7d708fea96](https://linux-hardware.org/?probe=7d708fea96) | Mar 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [eb5b9b8cb9](https://linux-hardware.org/?probe=eb5b9b8cb9) | Mar 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [4a0130d910](https://linux-hardware.org/?probe=4a0130d910) | Mar 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [2194ce4568](https://linux-hardware.org/?probe=2194ce4568) | Mar 06, 2023 |
| MSI           | PS42 8RB                    | Notebook    | [57231416e1](https://linux-hardware.org/?probe=57231416e1) | Mar 06, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [31a734c56b](https://linux-hardware.org/?probe=31a734c56b) | Mar 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [db088a95ce](https://linux-hardware.org/?probe=db088a95ce) | Mar 06, 2023 |
| AZW           | MINI S                      | Desktop     | [cb0b08973d](https://linux-hardware.org/?probe=cb0b08973d) | Mar 06, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [fc381c78e7](https://linux-hardware.org/?probe=fc381c78e7) | Mar 05, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [308b516329](https://linux-hardware.org/?probe=308b516329) | Mar 05, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [641d1c6a8f](https://linux-hardware.org/?probe=641d1c6a8f) | Mar 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS37F0... | Notebook    | [48677f9f86](https://linux-hardware.org/?probe=48677f9f86) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [b9677c823b](https://linux-hardware.org/?probe=b9677c823b) | Mar 05, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [ca566e314e](https://linux-hardware.org/?probe=ca566e314e) | Mar 05, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [cadbbe841e](https://linux-hardware.org/?probe=cadbbe841e) | Mar 05, 2023 |
| Dell          | G5 5500                     | Notebook    | [7da5494dea](https://linux-hardware.org/?probe=7da5494dea) | Mar 05, 2023 |
| HP            | G42                         | Notebook    | [7dee433139](https://linux-hardware.org/?probe=7dee433139) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [47f08e4094](https://linux-hardware.org/?probe=47f08e4094) | Mar 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| Dell          | Latitude E5450              | Notebook    | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| Intel         | powered classmate PC        | Notebook    | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [ea14c47abb](https://linux-hardware.org/?probe=ea14c47abb) | Mar 04, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [82acbe37f7](https://linux-hardware.org/?probe=82acbe37f7) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [545e7119e9](https://linux-hardware.org/?probe=545e7119e9) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | Notebook    | [1bfad93a1e](https://linux-hardware.org/?probe=1bfad93a1e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | Notebook    | [f782f8e288](https://linux-hardware.org/?probe=f782f8e288) | Mar 04, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c4def038d9](https://linux-hardware.org/?probe=c4def038d9) | Mar 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [10c4eda3a2](https://linux-hardware.org/?probe=10c4eda3a2) | Mar 04, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [1bef11c91d](https://linux-hardware.org/?probe=1bef11c91d) | Mar 04, 2023 |
| HP            | 82B4                        | Desktop     | [47d445cfa6](https://linux-hardware.org/?probe=47d445cfa6) | Mar 04, 2023 |
| Lenovo        | ThinkPad X220 429035U       | Notebook    | [83266c1006](https://linux-hardware.org/?probe=83266c1006) | Mar 04, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [29fa7c0b23](https://linux-hardware.org/?probe=29fa7c0b23) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ae03ade800](https://linux-hardware.org/?probe=ae03ade800) | Mar 04, 2023 |
| Unknown       | i855-W83627HF               | Desktop     | [e60d4877f4](https://linux-hardware.org/?probe=e60d4877f4) | Mar 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [a9c39c2b82](https://linux-hardware.org/?probe=a9c39c2b82) | Mar 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [55ca2f6ac5](https://linux-hardware.org/?probe=55ca2f6ac5) | Mar 03, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [a4e8543fe2](https://linux-hardware.org/?probe=a4e8543fe2) | Mar 03, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [cdaf43afa8](https://linux-hardware.org/?probe=cdaf43afa8) | Mar 03, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [02df2ea534](https://linux-hardware.org/?probe=02df2ea534) | Mar 03, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [7471275fc7](https://linux-hardware.org/?probe=7471275fc7) | Mar 03, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [31fc7e49b2](https://linux-hardware.org/?probe=31fc7e49b2) | Mar 03, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [f102669f1f](https://linux-hardware.org/?probe=f102669f1f) | Mar 03, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [7adf1c211e](https://linux-hardware.org/?probe=7adf1c211e) | Mar 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [7afe06d070](https://linux-hardware.org/?probe=7afe06d070) | Mar 03, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [54a92cd736](https://linux-hardware.org/?probe=54a92cd736) | Mar 03, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [916405bd1c](https://linux-hardware.org/?probe=916405bd1c) | Mar 03, 2023 |
| HP            | 635                         | Notebook    | [108b9443ea](https://linux-hardware.org/?probe=108b9443ea) | Mar 03, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [1a83a85925](https://linux-hardware.org/?probe=1a83a85925) | Mar 03, 2023 |
| Dell          | Latitude E7440              | Notebook    | [36439d1a64](https://linux-hardware.org/?probe=36439d1a64) | Mar 03, 2023 |
| Win elemen... | M600                        | Desktop     | [36ce350e0c](https://linux-hardware.org/?probe=36ce350e0c) | Mar 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [845ed95f72](https://linux-hardware.org/?probe=845ed95f72) | Mar 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [180f5c9379](https://linux-hardware.org/?probe=180f5c9379) | Mar 03, 2023 |
| Dell          | Vostro1710                  | Notebook    | [c24eab7e3d](https://linux-hardware.org/?probe=c24eab7e3d) | Mar 02, 2023 |
| Unknown       | Unknown                     | Soc         | [59b899bee2](https://linux-hardware.org/?probe=59b899bee2) | Mar 02, 2023 |
| Unknown       | Unknown                     | Soc         | [71faa2a8b1](https://linux-hardware.org/?probe=71faa2a8b1) | Mar 02, 2023 |
| Dell          | 0D6H9T A02                  | Desktop     | [0027e59622](https://linux-hardware.org/?probe=0027e59622) | Mar 02, 2023 |
| Acer          | Aspire 1640Z                | Notebook    | [915a8900d0](https://linux-hardware.org/?probe=915a8900d0) | Mar 02, 2023 |
| Dell          | Latitude E7440              | Notebook    | [b84f760e8e](https://linux-hardware.org/?probe=b84f760e8e) | Mar 02, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8f61a5507b](https://linux-hardware.org/?probe=8f61a5507b) | Mar 02, 2023 |
| AMI           | Intel                       | Desktop     | [b6d932a0ed](https://linux-hardware.org/?probe=b6d932a0ed) | Mar 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0e66878368](https://linux-hardware.org/?probe=0e66878368) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | Desktop     | [93e91a76bf](https://linux-hardware.org/?probe=93e91a76bf) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | Desktop     | [1774000cc4](https://linux-hardware.org/?probe=1774000cc4) | Mar 02, 2023 |
| ASUSTek       | X556UR                      | Notebook    | [70c4807d21](https://linux-hardware.org/?probe=70c4807d21) | Mar 02, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [11c1bf8316](https://linux-hardware.org/?probe=11c1bf8316) | Mar 02, 2023 |
| ECS           | G31T-M9                     | Desktop     | [88447490cb](https://linux-hardware.org/?probe=88447490cb) | Mar 02, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [21d1213402](https://linux-hardware.org/?probe=21d1213402) | Mar 02, 2023 |
| MSI           | Creator 15M A9SD            | Notebook    | [b19d8d936c](https://linux-hardware.org/?probe=b19d8d936c) | Mar 02, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [b53826c91c](https://linux-hardware.org/?probe=b53826c91c) | Mar 02, 2023 |
| Supermicro    | X11SPM-TF                   | Server      | [6d1f207293](https://linux-hardware.org/?probe=6d1f207293) | Mar 02, 2023 |
| Supermicro    | X11SPM-TF                   | Server      | [c4eb62ca69](https://linux-hardware.org/?probe=c4eb62ca69) | Mar 02, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [e055e73b69](https://linux-hardware.org/?probe=e055e73b69) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | Desktop     | [977be97551](https://linux-hardware.org/?probe=977be97551) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | Desktop     | [2191c9e96a](https://linux-hardware.org/?probe=2191c9e96a) | Mar 02, 2023 |
| Supermicro    | X8DT6                       | Server      | [6e08baab68](https://linux-hardware.org/?probe=6e08baab68) | Mar 02, 2023 |
| Supermicro    | X10DRC-LN4+                 | Server      | [6b0669d84c](https://linux-hardware.org/?probe=6b0669d84c) | Mar 02, 2023 |
| Dell          | Latitude 3510               | Notebook    | [0bad8d504d](https://linux-hardware.org/?probe=0bad8d504d) | Mar 02, 2023 |
| PC Special... | 14 Fusion IV                | Notebook    | [e465178d82](https://linux-hardware.org/?probe=e465178d82) | Mar 02, 2023 |
| Supermicro    | X11DPi-NT                   | Server      | [be6bb6833c](https://linux-hardware.org/?probe=be6bb6833c) | Mar 02, 2023 |
| Supermicro    | X11DPi-NT                   | Server      | [5a9cc71286](https://linux-hardware.org/?probe=5a9cc71286) | Mar 02, 2023 |
| Supermicro    | X11DPi-NT                   | Server      | [0dbca183b8](https://linux-hardware.org/?probe=0dbca183b8) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | Desktop     | [5b8c79ac33](https://linux-hardware.org/?probe=5b8c79ac33) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | Desktop     | [80644bb1ec](https://linux-hardware.org/?probe=80644bb1ec) | Mar 02, 2023 |
| Supermicro    | X10DRC-LN4+                 | Server      | [7faa52f1c0](https://linux-hardware.org/?probe=7faa52f1c0) | Mar 02, 2023 |
| Supermicro    | X8DT6                       | Server      | [3bf2cd3526](https://linux-hardware.org/?probe=3bf2cd3526) | Mar 02, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2894a5929b](https://linux-hardware.org/?probe=2894a5929b) | Mar 02, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [9036fa2ef1](https://linux-hardware.org/?probe=9036fa2ef1) | Mar 02, 2023 |
| GMKtec        | NucBox5                     | Notebook    | [fc11280fe6](https://linux-hardware.org/?probe=fc11280fe6) | Mar 02, 2023 |
| ZOTAC         | ZBOX-CI331NANO              | Mini pc     | [6d26f07cd1](https://linux-hardware.org/?probe=6d26f07cd1) | Mar 01, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f6b780ae7e](https://linux-hardware.org/?probe=f6b780ae7e) | Mar 01, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [aea23f5903](https://linux-hardware.org/?probe=aea23f5903) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [25112e4f96](https://linux-hardware.org/?probe=25112e4f96) | Mar 01, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [8089ba23b4](https://linux-hardware.org/?probe=8089ba23b4) | Mar 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [da2fc6826a](https://linux-hardware.org/?probe=da2fc6826a) | Mar 01, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [6e5e4d848d](https://linux-hardware.org/?probe=6e5e4d848d) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [52ecc1a9fb](https://linux-hardware.org/?probe=52ecc1a9fb) | Mar 01, 2023 |
| AZW           | MINI S                      | Desktop     | [2206d30a53](https://linux-hardware.org/?probe=2206d30a53) | Mar 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a91c417b74](https://linux-hardware.org/?probe=a91c417b74) | Mar 01, 2023 |
| HP            | 8433 11                     | Desktop     | [15dccf1191](https://linux-hardware.org/?probe=15dccf1191) | Mar 01, 2023 |
| HP            | ProBook 4415s               | Notebook    | [4e909ec0ad](https://linux-hardware.org/?probe=4e909ec0ad) | Mar 01, 2023 |
| Umbrel        | Home                        | Mini pc     | [f4afc80a6c](https://linux-hardware.org/?probe=f4afc80a6c) | Feb 28, 2023 |
| Medion        | TJ4125                      | Desktop     | [2024916642](https://linux-hardware.org/?probe=2024916642) | Feb 28, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [46c17d2c14](https://linux-hardware.org/?probe=46c17d2c14) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [89822406cc](https://linux-hardware.org/?probe=89822406cc) | Feb 28, 2023 |
| HP            | 83E2                        | Desktop     | [fdbe4ec1cb](https://linux-hardware.org/?probe=fdbe4ec1cb) | Feb 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [19fd766ea6](https://linux-hardware.org/?probe=19fd766ea6) | Feb 28, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [17fcfc2758](https://linux-hardware.org/?probe=17fcfc2758) | Feb 28, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [26a7db2ed8](https://linux-hardware.org/?probe=26a7db2ed8) | Feb 28, 2023 |
| AZW           | MINI S                      | Desktop     | [e65b0d1ef6](https://linux-hardware.org/?probe=e65b0d1ef6) | Feb 28, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [49205269e7](https://linux-hardware.org/?probe=49205269e7) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [672684e416](https://linux-hardware.org/?probe=672684e416) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [edf2240a74](https://linux-hardware.org/?probe=edf2240a74) | Feb 28, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [a5469adf59](https://linux-hardware.org/?probe=a5469adf59) | Feb 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b4bfab8974](https://linux-hardware.org/?probe=b4bfab8974) | Feb 28, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4d3d5e02a1](https://linux-hardware.org/?probe=4d3d5e02a1) | Feb 28, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3948048a11](https://linux-hardware.org/?probe=3948048a11) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| ASRock        | X370 Professional Gaming    | Desktop     | [3a670fbd63](https://linux-hardware.org/?probe=3a670fbd63) | Feb 27, 2023 |
| HP            | 3397                        | Desktop     | [8081d24eb1](https://linux-hardware.org/?probe=8081d24eb1) | Feb 27, 2023 |
| IBM           | 00D4062                     | Server      | [16c68a28d8](https://linux-hardware.org/?probe=16c68a28d8) | Feb 27, 2023 |
| Dell          | 0MH651                      | Desktop     | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Aquarius      | AQH310CM                    | Desktop     | [a2f4d0f77e](https://linux-hardware.org/?probe=a2f4d0f77e) | Feb 27, 2023 |
| Dell          | Latitude 5400               | Notebook    | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| Dell          | Latitude 3510               | Notebook    | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [7a8e478900](https://linux-hardware.org/?probe=7a8e478900) | Feb 27, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [29f6c3c897](https://linux-hardware.org/?probe=29f6c3c897) | Feb 27, 2023 |
| ASUSTek       | K52F                        | Notebook    | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [ee5b36d127](https://linux-hardware.org/?probe=ee5b36d127) | Feb 27, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [dd2f99b3ca](https://linux-hardware.org/?probe=dd2f99b3ca) | Feb 27, 2023 |
| Dell          | G3 3590                     | Notebook    | [eb9009fad9](https://linux-hardware.org/?probe=eb9009fad9) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| HP            | Pavilion g6                 | Notebook    | [41e4ef16e4](https://linux-hardware.org/?probe=41e4ef16e4) | Feb 26, 2023 |
| Olimex        | A20-OLinuXino-LIME          | Soc         | [bcb9e7b9e7](https://linux-hardware.org/?probe=bcb9e7b9e7) | Feb 26, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [787ddfd44c](https://linux-hardware.org/?probe=787ddfd44c) | Feb 26, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [3c4718f66e](https://linux-hardware.org/?probe=3c4718f66e) | Feb 26, 2023 |
| Panasonic     | CF-31WEUEEBE                | Notebook    | [40782ba0a7](https://linux-hardware.org/?probe=40782ba0a7) | Feb 26, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Server      | [ffa58f1702](https://linux-hardware.org/?probe=ffa58f1702) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430 2349GUU       | Notebook    | [95cc420bd5](https://linux-hardware.org/?probe=95cc420bd5) | Feb 26, 2023 |
| Medion        | BEAST X25                   | Notebook    | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | Notebook    | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9c64d6366e](https://linux-hardware.org/?probe=9c64d6366e) | Feb 26, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BX... | Notebook    | [633fb08804](https://linux-hardware.org/?probe=633fb08804) | Feb 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [aaa112feae](https://linux-hardware.org/?probe=aaa112feae) | Feb 26, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b05fb1c01b](https://linux-hardware.org/?probe=b05fb1c01b) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [3b2a19c835](https://linux-hardware.org/?probe=3b2a19c835) | Feb 26, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [7d7953a826](https://linux-hardware.org/?probe=7d7953a826) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| Unknown       | T3 MRD                      | Notebook    | [ae88920ea5](https://linux-hardware.org/?probe=ae88920ea5) | Feb 25, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| MSI           | B85M-E45                    | Desktop     | [a7748c0e8b](https://linux-hardware.org/?probe=a7748c0e8b) | Feb 25, 2023 |
| HUAWEI        | WRT-WX9                     | Notebook    | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [67e31f8e42](https://linux-hardware.org/?probe=67e31f8e42) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2bb4e30118](https://linux-hardware.org/?probe=2bb4e30118) | Feb 25, 2023 |
| Medion        | TJ4125                      | Desktop     | [bde9228741](https://linux-hardware.org/?probe=bde9228741) | Feb 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [f1db9ad466](https://linux-hardware.org/?probe=f1db9ad466) | Feb 25, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [ff08a846b0](https://linux-hardware.org/?probe=ff08a846b0) | Feb 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [2c5d6ab621](https://linux-hardware.org/?probe=2c5d6ab621) | Feb 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [15b5511875](https://linux-hardware.org/?probe=15b5511875) | Feb 25, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [b3b189e875](https://linux-hardware.org/?probe=b3b189e875) | Feb 25, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [d615820c71](https://linux-hardware.org/?probe=d615820c71) | Feb 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [3d8e9cb31b](https://linux-hardware.org/?probe=3d8e9cb31b) | Feb 24, 2023 |
| Intel         | JSL MRD                     | Desktop     | [84a33f3c84](https://linux-hardware.org/?probe=84a33f3c84) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [27e2d41750](https://linux-hardware.org/?probe=27e2d41750) | Feb 24, 2023 |
| Acer          | AO756                       | Notebook    | [ca83ee78ec](https://linux-hardware.org/?probe=ca83ee78ec) | Feb 24, 2023 |
| Lenovo        | KaiTian N70z G1d            | Notebook    | [cbc8e4e008](https://linux-hardware.org/?probe=cbc8e4e008) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [c2ca1fb2f3](https://linux-hardware.org/?probe=c2ca1fb2f3) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7fe6e0dcde](https://linux-hardware.org/?probe=7fe6e0dcde) | Feb 24, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [f5b4a5da72](https://linux-hardware.org/?probe=f5b4a5da72) | Feb 24, 2023 |
| HP            | Presario CQ57               | Notebook    | [b41de6d094](https://linux-hardware.org/?probe=b41de6d094) | Feb 24, 2023 |
| HP            | 82F2 A01                    | Desktop     | [efc9b2fdbf](https://linux-hardware.org/?probe=efc9b2fdbf) | Feb 24, 2023 |
| HP            | 82F2 A01                    | Desktop     | [24dc4341d3](https://linux-hardware.org/?probe=24dc4341d3) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3f28f459bf](https://linux-hardware.org/?probe=3f28f459bf) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8ed4158090](https://linux-hardware.org/?probe=8ed4158090) | Feb 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [5070b384cc](https://linux-hardware.org/?probe=5070b384cc) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [1989031eb6](https://linux-hardware.org/?probe=1989031eb6) | Feb 24, 2023 |
| Dell          | Latitude D620               | Notebook    | [fba80b099d](https://linux-hardware.org/?probe=fba80b099d) | Feb 24, 2023 |
| Dell          | 0CNWVK A02                  | Desktop     | [1fd825c3df](https://linux-hardware.org/?probe=1fd825c3df) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5da2f709bb](https://linux-hardware.org/?probe=5da2f709bb) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [bf32299a30](https://linux-hardware.org/?probe=bf32299a30) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [54279e4e30](https://linux-hardware.org/?probe=54279e4e30) | Feb 24, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [788e0929de](https://linux-hardware.org/?probe=788e0929de) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [52b14c9235](https://linux-hardware.org/?probe=52b14c9235) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [a09d17dd16](https://linux-hardware.org/?probe=a09d17dd16) | Feb 24, 2023 |
| Samsung       | N150P                       | Notebook    | [662488621d](https://linux-hardware.org/?probe=662488621d) | Feb 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e3f8cf325d](https://linux-hardware.org/?probe=e3f8cf325d) | Feb 24, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
| Unknown       | Unknown                     | Soc         | [23a808c1e1](https://linux-hardware.org/?probe=23a808c1e1) | Feb 24, 2023 |
| Unknown       | Unknown                     | Soc         | [44fdfeedf2](https://linux-hardware.org/?probe=44fdfeedf2) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [0806dcb9ca](https://linux-hardware.org/?probe=0806dcb9ca) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [e3cdd0b411](https://linux-hardware.org/?probe=e3cdd0b411) | Feb 24, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [e44618f1c3](https://linux-hardware.org/?probe=e44618f1c3) | Feb 23, 2023 |
| ASUSTek       | KRPA-U16 Series             | Desktop     | [e417ffd8e7](https://linux-hardware.org/?probe=e417ffd8e7) | Feb 23, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [885478dd47](https://linux-hardware.org/?probe=885478dd47) | Feb 23, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [53eb80a44b](https://linux-hardware.org/?probe=53eb80a44b) | Feb 23, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [8d4b399341](https://linux-hardware.org/?probe=8d4b399341) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [4f19f71811](https://linux-hardware.org/?probe=4f19f71811) | Feb 23, 2023 |
| Dell          | 01V648 A03                  | Server      | [c0b7421a8b](https://linux-hardware.org/?probe=c0b7421a8b) | Feb 23, 2023 |
| LincPlus      | P2                          | Notebook    | [5d4e528621](https://linux-hardware.org/?probe=5d4e528621) | Feb 23, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [a3ea522d78](https://linux-hardware.org/?probe=a3ea522d78) | Feb 23, 2023 |
| Intel         | H61                         | Desktop     | [de757dd659](https://linux-hardware.org/?probe=de757dd659) | Feb 23, 2023 |
| Lenovo        | ThinkPad E14 20RA0036HV     | Notebook    | [eef601ff61](https://linux-hardware.org/?probe=eef601ff61) | Feb 23, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [09070f52bb](https://linux-hardware.org/?probe=09070f52bb) | Feb 23, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| AZW           | U59                         | Desktop     | [9289537f45](https://linux-hardware.org/?probe=9289537f45) | Feb 22, 2023 |
| Fujitsu       | LIFEBOOK E753               | Notebook    | [8fa3315cca](https://linux-hardware.org/?probe=8fa3315cca) | Feb 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9d233c96b5](https://linux-hardware.org/?probe=9d233c96b5) | Feb 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [8227fec538](https://linux-hardware.org/?probe=8227fec538) | Feb 22, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [fb050eaf3c](https://linux-hardware.org/?probe=fb050eaf3c) | Feb 22, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [7cf8754a48](https://linux-hardware.org/?probe=7cf8754a48) | Feb 22, 2023 |
| Acer          | AO756                       | Notebook    | [58f52941c7](https://linux-hardware.org/?probe=58f52941c7) | Feb 22, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1d2132b142](https://linux-hardware.org/?probe=1d2132b142) | Feb 22, 2023 |
| AZW           | U59                         | Desktop     | [368562790b](https://linux-hardware.org/?probe=368562790b) | Feb 22, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4009d82fc8](https://linux-hardware.org/?probe=4009d82fc8) | Feb 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [5cf4127d47](https://linux-hardware.org/?probe=5cf4127d47) | Feb 21, 2023 |
| Dell          | Latitude 7530               | Notebook    | [4844568edb](https://linux-hardware.org/?probe=4844568edb) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [de56e36164](https://linux-hardware.org/?probe=de56e36164) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | Notebook    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| Dell          | Inspiron 3468               | Notebook    | [e5977ee094](https://linux-hardware.org/?probe=e5977ee094) | Feb 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJA0... | Convertible | [aba497a637](https://linux-hardware.org/?probe=aba497a637) | Feb 21, 2023 |
| Dell          | 0TT740 A00                  | Server      | [2e77448a7d](https://linux-hardware.org/?probe=2e77448a7d) | Feb 21, 2023 |
| Dell          | 0TT740 A00                  | Server      | [ec75c9762a](https://linux-hardware.org/?probe=ec75c9762a) | Feb 21, 2023 |
| HP            | ProLiant ML110 G7           | Desktop     | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [6ab7953740](https://linux-hardware.org/?probe=6ab7953740) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| HP            | Stream 8 Tablet             | Tablet      | [211438a893](https://linux-hardware.org/?probe=211438a893) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Acer          | Extensa 2520G               | Notebook    | [823c5829a9](https://linux-hardware.org/?probe=823c5829a9) | Feb 20, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [0cb773d407](https://linux-hardware.org/?probe=0cb773d407) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | Notebook    | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58e 7269E3S    | Desktop     | [6b30da3a31](https://linux-hardware.org/?probe=6b30da3a31) | Feb 20, 2023 |
| Dell          | Latitude E7270              | Notebook    | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [53ba72d592](https://linux-hardware.org/?probe=53ba72d592) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [b778aa73ca](https://linux-hardware.org/?probe=b778aa73ca) | Feb 19, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [a2250b4489](https://linux-hardware.org/?probe=a2250b4489) | Feb 19, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [e259c81376](https://linux-hardware.org/?probe=e259c81376) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [2e3da97146](https://linux-hardware.org/?probe=2e3da97146) | Feb 19, 2023 |
| Dell          | 0NHNHP A01                  | Server      | [da74244bff](https://linux-hardware.org/?probe=da74244bff) | Feb 19, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [aa198228bc](https://linux-hardware.org/?probe=aa198228bc) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| Dell          | 0T065F A01                  | Desktop     | [c8b1f8651a](https://linux-hardware.org/?probe=c8b1f8651a) | Feb 19, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [d442995b00](https://linux-hardware.org/?probe=d442995b00) | Feb 19, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [22fdba9212](https://linux-hardware.org/?probe=22fdba9212) | Feb 19, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [537c2d1b64](https://linux-hardware.org/?probe=537c2d1b64) | Feb 18, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [3158f1e0d5](https://linux-hardware.org/?probe=3158f1e0d5) | Feb 18, 2023 |
| Supermicro    | X11SCA-WA                   | Server      | [065427c37f](https://linux-hardware.org/?probe=065427c37f) | Feb 18, 2023 |
| Intel         | JSL MRD                     | Desktop     | [5e021f6a92](https://linux-hardware.org/?probe=5e021f6a92) | Feb 18, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | Notebook    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a782ccbba9](https://linux-hardware.org/?probe=a782ccbba9) | Feb 18, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [22b75dc114](https://linux-hardware.org/?probe=22b75dc114) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Dell          | Latitude E5450              | Notebook    | [56827b29dc](https://linux-hardware.org/?probe=56827b29dc) | Feb 18, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [cc805e31b0](https://linux-hardware.org/?probe=cc805e31b0) | Feb 17, 2023 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [3159aede6c](https://linux-hardware.org/?probe=3159aede6c) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Notebook    | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [bd6636c99d](https://linux-hardware.org/?probe=bd6636c99d) | Feb 17, 2023 |
| Intel         | H61                         | Desktop     | [90e4a9358f](https://linux-hardware.org/?probe=90e4a9358f) | Feb 17, 2023 |
| MSI           | X399 SLI PLUS               | Desktop     | [8741094cd9](https://linux-hardware.org/?probe=8741094cd9) | Feb 17, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [423c7bb57a](https://linux-hardware.org/?probe=423c7bb57a) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [02e6818311](https://linux-hardware.org/?probe=02e6818311) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [4bf1ccfe74](https://linux-hardware.org/?probe=4bf1ccfe74) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [288e753767](https://linux-hardware.org/?probe=288e753767) | Feb 17, 2023 |
| Dell          | System XPS L702X            | Notebook    | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Lenovo        | 3164 NOK                    | Desktop     | [f69ff4a8c8](https://linux-hardware.org/?probe=f69ff4a8c8) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | Desktop     | [cfdcc68921](https://linux-hardware.org/?probe=cfdcc68921) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | Desktop     | [7bb3c6268f](https://linux-hardware.org/?probe=7bb3c6268f) | Feb 16, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [c812182e32](https://linux-hardware.org/?probe=c812182e32) | Feb 16, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [63747d1456](https://linux-hardware.org/?probe=63747d1456) | Feb 16, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [cda38b5b9b](https://linux-hardware.org/?probe=cda38b5b9b) | Feb 16, 2023 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [387881f288](https://linux-hardware.org/?probe=387881f288) | Feb 16, 2023 |
| Dell          | Precision 5570              | Notebook    | [d5f9d13ae3](https://linux-hardware.org/?probe=d5f9d13ae3) | Feb 16, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bbce6ba3b1](https://linux-hardware.org/?probe=bbce6ba3b1) | Feb 16, 2023 |
| Lenovo        | 1030 SDK0J40705 WIN 3425... | Desktop     | [daed0124f0](https://linux-hardware.org/?probe=daed0124f0) | Feb 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [a4fd7cdaa8](https://linux-hardware.org/?probe=a4fd7cdaa8) | Feb 16, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [940563622b](https://linux-hardware.org/?probe=940563622b) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Gigabyte      | H270M-D3H-CF                | Desktop     | [7a58ceb644](https://linux-hardware.org/?probe=7a58ceb644) | Feb 15, 2023 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [c5b8952fdb](https://linux-hardware.org/?probe=c5b8952fdb) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |
| Dell          | Precision 5570              | Notebook    | [d0f2fa25c3](https://linux-hardware.org/?probe=d0f2fa25c3) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [13866e78a2](https://linux-hardware.org/?probe=13866e78a2) | Feb 15, 2023 |
| Google        | Grunt                       | Notebook    | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| Gigabyte      | EP43-S3L                    | Desktop     | [82730ed699](https://linux-hardware.org/?probe=82730ed699) | Feb 15, 2023 |
| Itautec       | ST 4265                     | Desktop     | [84023fa8ac](https://linux-hardware.org/?probe=84023fa8ac) | Feb 15, 2023 |
| ASUSTek       | P5GD1 PRO                   | Desktop     | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| ASUSTek       | K53U                        | Notebook    | [e9a6a69e01](https://linux-hardware.org/?probe=e9a6a69e01) | Feb 15, 2023 |
| ASRock        | Z77 Extreme6                | Desktop     | [48328ab864](https://linux-hardware.org/?probe=48328ab864) | Feb 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [fe12f077df](https://linux-hardware.org/?probe=fe12f077df) | Feb 15, 2023 |
| Unknown       | T3 MRD                      | Notebook    | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [5ebd73227b](https://linux-hardware.org/?probe=5ebd73227b) | Feb 14, 2023 |
| Acer          | Aspire V5-572G              | Notebook    | [7f360258ff](https://linux-hardware.org/?probe=7f360258ff) | Feb 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [0ac84e31dd](https://linux-hardware.org/?probe=0ac84e31dd) | Feb 14, 2023 |
| Dell          | 0RN474                      | Desktop     | [5c1bf45372](https://linux-hardware.org/?probe=5c1bf45372) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [0a0e30ba0a](https://linux-hardware.org/?probe=0a0e30ba0a) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| HP            | 3648h                       | Desktop     | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f6bcdb7c6b](https://linux-hardware.org/?probe=f6bcdb7c6b) | Feb 14, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [67b141272c](https://linux-hardware.org/?probe=67b141272c) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [345021f7f6](https://linux-hardware.org/?probe=345021f7f6) | Feb 14, 2023 |
| Lenovo        | ThinkPad P51 20HJS0AR16     | Notebook    | [ad0f22fe34](https://linux-hardware.org/?probe=ad0f22fe34) | Feb 14, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [c69ee15636](https://linux-hardware.org/?probe=c69ee15636) | Feb 14, 2023 |
| Dell          | 0RN474                      | Desktop     | [20f3c37dc2](https://linux-hardware.org/?probe=20f3c37dc2) | Feb 14, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [579388a539](https://linux-hardware.org/?probe=579388a539) | Feb 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [34ad4bac16](https://linux-hardware.org/?probe=34ad4bac16) | Feb 13, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [4750f3ad3a](https://linux-hardware.org/?probe=4750f3ad3a) | Feb 13, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [55e684c121](https://linux-hardware.org/?probe=55e684c121) | Feb 13, 2023 |
| Dell          | Latitude D630               | Notebook    | [04c083db36](https://linux-hardware.org/?probe=04c083db36) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [c49317ce12](https://linux-hardware.org/?probe=c49317ce12) | Feb 13, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [855634fadc](https://linux-hardware.org/?probe=855634fadc) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [b1d1f36f51](https://linux-hardware.org/?probe=b1d1f36f51) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [6fe738fa6d](https://linux-hardware.org/?probe=6fe738fa6d) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [122eded37e](https://linux-hardware.org/?probe=122eded37e) | Feb 13, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [517a5a9e81](https://linux-hardware.org/?probe=517a5a9e81) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [e83cd923a5](https://linux-hardware.org/?probe=e83cd923a5) | Feb 13, 2023 |
| Google        | Droid                       | Notebook    | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| retsamarre... | 000-F4423-UK000-2000        | Tablet      | [c24b5a1f84](https://linux-hardware.org/?probe=c24b5a1f84) | Feb 12, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [89c31e6f8c](https://linux-hardware.org/?probe=89c31e6f8c) | Feb 12, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [124d65cd04](https://linux-hardware.org/?probe=124d65cd04) | Feb 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [72ce8d1929](https://linux-hardware.org/?probe=72ce8d1929) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [c0d18ab501](https://linux-hardware.org/?probe=c0d18ab501) | Feb 12, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [54e092f58f](https://linux-hardware.org/?probe=54e092f58f) | Feb 12, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [09266b8b06](https://linux-hardware.org/?probe=09266b8b06) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [09dff429cd](https://linux-hardware.org/?probe=09dff429cd) | Feb 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [b54b603772](https://linux-hardware.org/?probe=b54b603772) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [52674d23ad](https://linux-hardware.org/?probe=52674d23ad) | Feb 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [9fa2cd7dfb](https://linux-hardware.org/?probe=9fa2cd7dfb) | Feb 12, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [4829b991be](https://linux-hardware.org/?probe=4829b991be) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [4a6ea9bd99](https://linux-hardware.org/?probe=4a6ea9bd99) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [063d6eb482](https://linux-hardware.org/?probe=063d6eb482) | Feb 12, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [1589cfe790](https://linux-hardware.org/?probe=1589cfe790) | Feb 11, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [22fdde82eb](https://linux-hardware.org/?probe=22fdde82eb) | Feb 11, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [3932889971](https://linux-hardware.org/?probe=3932889971) | Feb 11, 2023 |
| Notebook      | MAM2120                     | Notebook    | [300a622d96](https://linux-hardware.org/?probe=300a622d96) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ed3233c97b](https://linux-hardware.org/?probe=ed3233c97b) | Feb 11, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [94ee6da4d3](https://linux-hardware.org/?probe=94ee6da4d3) | Feb 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [27323a90bb](https://linux-hardware.org/?probe=27323a90bb) | Feb 11, 2023 |
| Acer          | Predator G9-793             | Notebook    | [8c11736bf0](https://linux-hardware.org/?probe=8c11736bf0) | Feb 11, 2023 |
| ASUSTek       | P5VD2-X                     | Desktop     | [32a509e760](https://linux-hardware.org/?probe=32a509e760) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [2695a9350a](https://linux-hardware.org/?probe=2695a9350a) | Feb 11, 2023 |
| Dell          | Latitude E6330              | Notebook    | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [d003016397](https://linux-hardware.org/?probe=d003016397) | Feb 11, 2023 |
| AZW           | U59                         | Desktop     | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [a3f08d08aa](https://linux-hardware.org/?probe=a3f08d08aa) | Feb 11, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [5483d83053](https://linux-hardware.org/?probe=5483d83053) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [5b2605691d](https://linux-hardware.org/?probe=5b2605691d) | Feb 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [7b6a31ec69](https://linux-hardware.org/?probe=7b6a31ec69) | Feb 11, 2023 |
| AMD           | CM-iGLX Platform Board R... | Desktop     | [c256a73072](https://linux-hardware.org/?probe=c256a73072) | Feb 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [35b93693a5](https://linux-hardware.org/?probe=35b93693a5) | Feb 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| Maxtang       | EHL30 V1.0                  | Desktop     | [4d133c615c](https://linux-hardware.org/?probe=4d133c615c) | Feb 10, 2023 |
| ASRockRack    | X570D4U                     | Desktop     | [bb2c98768e](https://linux-hardware.org/?probe=bb2c98768e) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | Notebook    | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [65e66dbf71](https://linux-hardware.org/?probe=65e66dbf71) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| Intel         | H61                         | Desktop     | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| ASUSTek       | M4N78                       | Desktop     | [34ddf02a41](https://linux-hardware.org/?probe=34ddf02a41) | Feb 10, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | Notebook    | [8f22e1beaa](https://linux-hardware.org/?probe=8f22e1beaa) | Feb 10, 2023 |
| Samsung       | 550XDA                      | Notebook    | [45d947c9f9](https://linux-hardware.org/?probe=45d947c9f9) | Feb 10, 2023 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [0730c9228d](https://linux-hardware.org/?probe=0730c9228d) | Feb 10, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [84eb5f0ad8](https://linux-hardware.org/?probe=84eb5f0ad8) | Feb 09, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [8c4ab545de](https://linux-hardware.org/?probe=8c4ab545de) | Feb 09, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [fd0b6a7a49](https://linux-hardware.org/?probe=fd0b6a7a49) | Feb 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [02adcb8587](https://linux-hardware.org/?probe=02adcb8587) | Feb 09, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [fe1dac78bb](https://linux-hardware.org/?probe=fe1dac78bb) | Feb 09, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [209d4693fe](https://linux-hardware.org/?probe=209d4693fe) | Feb 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [82173d3b08](https://linux-hardware.org/?probe=82173d3b08) | Feb 09, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | Notebook    | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| AMI           | Cherry Trail CR             | Notebook    | [e7eab93323](https://linux-hardware.org/?probe=e7eab93323) | Feb 09, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [a0132107aa](https://linux-hardware.org/?probe=a0132107aa) | Feb 08, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [6231dbe6d4](https://linux-hardware.org/?probe=6231dbe6d4) | Feb 08, 2023 |
| Dell          | Latitude E6330              | Notebook    | [291e0fd64f](https://linux-hardware.org/?probe=291e0fd64f) | Feb 08, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [965758f3ea](https://linux-hardware.org/?probe=965758f3ea) | Feb 08, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [bbaa8165e4](https://linux-hardware.org/?probe=bbaa8165e4) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [cc897fe72d](https://linux-hardware.org/?probe=cc897fe72d) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Lenovo        | 3164 NOK                    | Desktop     | [750d30cb48](https://linux-hardware.org/?probe=750d30cb48) | Feb 08, 2023 |
| Intel         | DH67CL AAG10212-208         | Desktop     | [e53a89d83d](https://linux-hardware.org/?probe=e53a89d83d) | Feb 08, 2023 |
| Dell          | Precision 5570              | Notebook    | [6c257e667d](https://linux-hardware.org/?probe=6c257e667d) | Feb 08, 2023 |
| TYAN Compu... | S4985                       | Server      | [40ea5a6601](https://linux-hardware.org/?probe=40ea5a6601) | Feb 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d37cc19110](https://linux-hardware.org/?probe=d37cc19110) | Feb 08, 2023 |
| Dell          | Precision 5570              | Notebook    | [e81b3de663](https://linux-hardware.org/?probe=e81b3de663) | Feb 08, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [f5aeb173ba](https://linux-hardware.org/?probe=f5aeb173ba) | Feb 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3245fc2fec](https://linux-hardware.org/?probe=3245fc2fec) | Feb 08, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [8fb3a20b27](https://linux-hardware.org/?probe=8fb3a20b27) | Feb 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [def4679f84](https://linux-hardware.org/?probe=def4679f84) | Feb 07, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [eca3a05d41](https://linux-hardware.org/?probe=eca3a05d41) | Feb 07, 2023 |
| Panasonic     | CF-54-1                     | Notebook    | [32a2acc07e](https://linux-hardware.org/?probe=32a2acc07e) | Feb 07, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [69f96bffa5](https://linux-hardware.org/?probe=69f96bffa5) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Dell          | Latitude E7250              | Notebook    | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| Dell          | Precision 5570              | Notebook    | [d279e97c00](https://linux-hardware.org/?probe=d279e97c00) | Feb 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7e020b928e](https://linux-hardware.org/?probe=7e020b928e) | Feb 07, 2023 |
| Inspur        | Shuyu                       | Server      | [37c2630b8f](https://linux-hardware.org/?probe=37c2630b8f) | Feb 07, 2023 |
| Toshiba       | Satellite C655              | Notebook    | [a0c2eb7db1](https://linux-hardware.org/?probe=a0c2eb7db1) | Feb 07, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [83380dcad6](https://linux-hardware.org/?probe=83380dcad6) | Feb 07, 2023 |
| Dell          | 08DM12 A00                  | Server      | [4fcfb3fb2a](https://linux-hardware.org/?probe=4fcfb3fb2a) | Feb 07, 2023 |
| Intel         | NUC5CPYB H61145-402         | Mini pc     | [9cb000ed27](https://linux-hardware.org/?probe=9cb000ed27) | Feb 06, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [4b19274da1](https://linux-hardware.org/?probe=4b19274da1) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| HP            | 3397                        | Desktop     | [2fb7638874](https://linux-hardware.org/?probe=2fb7638874) | Feb 06, 2023 |
| Google        | Terra                       | Notebook    | [edfe00266c](https://linux-hardware.org/?probe=edfe00266c) | Feb 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [7d2d46a579](https://linux-hardware.org/?probe=7d2d46a579) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | Notebook    | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [b3169f788f](https://linux-hardware.org/?probe=b3169f788f) | Feb 06, 2023 |
| ASUSTek       | X71Q                        | Notebook    | [c89b078e8f](https://linux-hardware.org/?probe=c89b078e8f) | Feb 06, 2023 |
| Aquarius      | NS585                       | Notebook    | [e9deef3f9e](https://linux-hardware.org/?probe=e9deef3f9e) | Feb 06, 2023 |
| AZW           | U59                         | Desktop     | [b97c4f6277](https://linux-hardware.org/?probe=b97c4f6277) | Feb 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | Notebook    | [112a65a03e](https://linux-hardware.org/?probe=112a65a03e) | Feb 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2891f201f0](https://linux-hardware.org/?probe=2891f201f0) | Feb 06, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [db292bc714](https://linux-hardware.org/?probe=db292bc714) | Feb 05, 2023 |
| HP            | 0A64h                       | Desktop     | [40ef639345](https://linux-hardware.org/?probe=40ef639345) | Feb 05, 2023 |
| Huanan        | X99-T8D V1.2                | Desktop     | [cb7e750cee](https://linux-hardware.org/?probe=cb7e750cee) | Feb 05, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [b708cdc12f](https://linux-hardware.org/?probe=b708cdc12f) | Feb 05, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7b81bb188c](https://linux-hardware.org/?probe=7b81bb188c) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [6023defc83](https://linux-hardware.org/?probe=6023defc83) | Feb 05, 2023 |
| Intel         | S5500HCV E40912-458         | Server      | [1445c60562](https://linux-hardware.org/?probe=1445c60562) | Feb 05, 2023 |
| Intel         | S5500HCV E40912-458         | Server      | [95ff55d958](https://linux-hardware.org/?probe=95ff55d958) | Feb 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [2f56f41681](https://linux-hardware.org/?probe=2f56f41681) | Feb 05, 2023 |
| Google        | Ampton                      | Notebook    | [74d5b6aa4d](https://linux-hardware.org/?probe=74d5b6aa4d) | Feb 05, 2023 |
| HP            | 2B36                        | Desktop     | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [5a491991ef](https://linux-hardware.org/?probe=5a491991ef) | Feb 05, 2023 |
| Google        | Ampton                      | Notebook    | [2785bde3f9](https://linux-hardware.org/?probe=2785bde3f9) | Feb 05, 2023 |
| HP            | 255 G3                      | Notebook    | [dfa2e96880](https://linux-hardware.org/?probe=dfa2e96880) | Feb 05, 2023 |
| MSI           | A320M PRO-M2                | Desktop     | [3fa2ac81f2](https://linux-hardware.org/?probe=3fa2ac81f2) | Feb 05, 2023 |
| Dell          | 0D4MD1 A00                  | Desktop     | [7198c3d131](https://linux-hardware.org/?probe=7198c3d131) | Feb 05, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [e0a93d257b](https://linux-hardware.org/?probe=e0a93d257b) | Feb 05, 2023 |
| OEM           | Intel H81                   | Desktop     | [806280459d](https://linux-hardware.org/?probe=806280459d) | Feb 05, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [f2423d1d75](https://linux-hardware.org/?probe=f2423d1d75) | Feb 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 5891      | 63.42%  |
| Debian 10                       | 1757      | 18.91%  |
| Debian Testing                  | 644       | 6.93%   |
| Debian 9                        | 321       | 3.46%   |
| Debian                          | 271       | 2.92%   |
| Debian Unstable                 | 263       | 2.83%   |
| Debian 11-updates               | 47        | 0.51%   |
| Debian 8                        | 38        | 0.41%   |
| Debian 12                       | 36        | 0.39%   |
| Debian Sid                      | 6         | 0.06%   |
| Debian Testing/unstable         | 5         | 0.05%   |
| Debian 7                        | 5         | 0.05%   |
| Debian Testing-proposed-updates | 3         | 0.03%   |
| Debian 99                       | 1         | 0.01%   |
| Debian 6                        | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Debian | 9025      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.10.0-8-amd64        | 980       | 9.52%   |
| 5.10.0-7-amd64        | 691       | 6.71%   |
| 5.10.0-10-amd64       | 576       | 5.59%   |
| 5.10.0-16-amd64       | 370       | 3.59%   |
| 5.10.0-9-amd64        | 328       | 3.19%   |
| 5.10.0-20-amd64       | 316       | 3.07%   |
| 5.10.0-21-amd64       | 314       | 3.05%   |
| 5.10.0-19-amd64       | 288       | 2.8%    |
| 5.10.0-18-amd64       | 287       | 2.79%   |
| 5.10.0-13-amd64       | 262       | 2.54%   |
| 5.10.0-11-amd64       | 194       | 1.88%   |
| 5.10.0-2-amd64        | 167       | 1.62%   |
| 4.19.0-6-amd64        | 145       | 1.41%   |
| 4.19.0-9-amd64        | 143       | 1.39%   |
| 5.10.0-14-amd64       | 141       | 1.37%   |
| 5.10.0-17-amd64       | 126       | 1.22%   |
| 4.19.0-13-amd64       | 125       | 1.21%   |
| 4.19.0-8-amd64        | 120       | 1.17%   |
| 4.19.0-16-amd64       | 109       | 1.06%   |
| 4.19.0-14-amd64       | 104       | 1.01%   |
| 5.10.0-15-amd64       | 99        | 0.96%   |
| 5.15.0-2-amd64        | 95        | 0.92%   |
| 4.19.0-17-amd64       | 94        | 0.91%   |
| 4.19.0-12-amd64       | 88        | 0.85%   |
| 4.19.0-10-amd64       | 87        | 0.84%   |
| 5.10.0-12-amd64       | 73        | 0.71%   |
| 4.9.0-8-amd64         | 70        | 0.68%   |
| 5.10.0-6-amd64        | 66        | 0.64%   |
| 5.6.0-2-amd64         | 53        | 0.51%   |
| 5.18.0-2-amd64        | 52        | 0.5%    |
| 6.0.0-6-amd64         | 50        | 0.49%   |
| 4.19.0-5-amd64        | 48        | 0.47%   |
| 5.4.0-4-amd64         | 45        | 0.44%   |
| 5.7.0-1-amd64         | 44        | 0.43%   |
| 5.10.0-3-amd64        | 44        | 0.43%   |
| 6.0.0-0.deb11.6-amd64 | 43        | 0.42%   |
| 5.17.0-1-amd64        | 42        | 0.41%   |
| 5.19.0-2-amd64        | 41        | 0.4%    |
| 6.0.0-2-amd64         | 40        | 0.39%   |
| 5.19.0-1-amd64        | 40        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 5214      | 54.32%  |
| 4.19.0  | 1239      | 12.91%  |
| 6.0.0   | 243       | 2.53%   |
| 4.9.0   | 241       | 2.51%   |
| 5.18.0  | 197       | 2.05%   |
| 6.1.0   | 161       | 1.68%   |
| 5.15.0  | 161       | 1.68%   |
| 5.9.0   | 150       | 1.56%   |
| 5.16.0  | 133       | 1.39%   |
| 5.7.0   | 121       | 1.26%   |
| 5.8.0   | 120       | 1.25%   |
| 5.4.0   | 118       | 1.23%   |
| 5.19.0  | 118       | 1.23%   |
| 5.6.0   | 100       | 1.04%   |
| 5.14.0  | 91        | 0.95%   |
| 5.17.0  | 71        | 0.74%   |
| 5.13.19 | 59        | 0.61%   |
| 5.3.0   | 39        | 0.41%   |
| 5.5.0   | 32        | 0.33%   |
| 5.15.74 | 29        | 0.3%    |
| 5.11.22 | 28        | 0.29%   |
| 5.2.0   | 21        | 0.22%   |
| 4.18.0  | 21        | 0.22%   |
| 5.15.85 | 20        | 0.21%   |
| 5.15.32 | 19        | 0.2%    |
| 5.15.39 | 18        | 0.19%   |
| 5.15.30 | 18        | 0.19%   |
| 3.16.0  | 18        | 0.19%   |
| 5.15.83 | 17        | 0.18%   |
| 5.15.35 | 17        | 0.18%   |
| 5.15.84 | 16        | 0.17%   |
| 5.4.106 | 15        | 0.16%   |
| 5.15.76 | 15        | 0.16%   |
| 5.10.92 | 15        | 0.16%   |
| 5.15.53 | 14        | 0.15%   |
| 4.15.18 | 14        | 0.15%   |
| 5.15.61 | 13        | 0.14%   |
| 5.4.78  | 11        | 0.11%   |
| 5.13.0  | 10        | 0.1%    |
| 5.4.65  | 9         | 0.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 5322      | 55.72%  |
| 4.19    | 1258      | 13.17%  |
| 5.15    | 406       | 4.25%   |
| 6.0     | 258       | 2.7%    |
| 4.9     | 252       | 2.64%   |
| 5.4     | 219       | 2.29%   |
| 5.18    | 210       | 2.2%    |
| 6.1     | 181       | 1.89%   |
| 5.9     | 159       | 1.66%   |
| 5.16    | 145       | 1.52%   |
| 5.19    | 138       | 1.44%   |
| 5.8     | 132       | 1.38%   |
| 5.7     | 129       | 1.35%   |
| 5.6     | 110       | 1.15%   |
| 5.14    | 101       | 1.06%   |
| 5.17    | 86        | 0.9%    |
| 5.13    | 82        | 0.86%   |
| 5.3     | 65        | 0.68%   |
| 5.11    | 51        | 0.53%   |
| 5.5     | 38        | 0.4%    |
| 5.2     | 27        | 0.28%   |
| 4.18    | 22        | 0.23%   |
| 4.15    | 19        | 0.2%    |
| 3.16    | 18        | 0.19%   |
| 5.12    | 16        | 0.17%   |
| 5.0     | 13        | 0.14%   |
| 4.4     | 13        | 0.14%   |
| 5       | 11        | 0.12%   |
| 6.2     | 8         | 0.08%   |
| 4.17    | 8         | 0.08%   |
| 4.1     | 8         | 0.08%   |
| 4.14    | 7         | 0.07%   |
| 5.1     | 6         | 0.06%   |
| 3.10    | 4         | 0.04%   |
| 4.8     | 3         | 0.03%   |
| 4.20    | 3         | 0.03%   |
| 4.16    | 3         | 0.03%   |
| 4.13    | 3         | 0.03%   |
| 4.10    | 2         | 0.02%   |
| 3.18    | 2         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 8446      | 93.56%  |
| i686    | 303       | 3.36%   |
| aarch64 | 200       | 2.22%   |
| armv7l  | 52        | 0.58%   |
| riscv64 | 9         | 0.1%    |
| ppc64   | 7         | 0.08%   |
| i586    | 3         | 0.03%   |
| ppc64le | 2         | 0.02%   |
| mips64  | 2         | 0.02%   |
| sparc64 | 1         | 0.01%   |
| sh4a    | 1         | 0.01%   |
| armv6l  | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 2971      | 32.18%  |
| GNOME             | 2055      | 22.26%  |
| XFCE              | 1128      | 12.22%  |
| KDE5              | 1062      | 11.5%   |
| MATE              | 380       | 4.12%   |
| X-Cinnamon        | 306       | 3.31%   |
| LXDE              | 275       | 2.98%   |
| Cinnamon          | 266       | 2.88%   |
| KDE               | 210       | 2.27%   |
| LXQt              | 135       | 1.46%   |
| i3                | 132       | 1.43%   |
| Openbox           | 59        | 0.64%   |
| GNOME Flashback   | 56        | 0.61%   |
| lightdm-xsession  | 44        | 0.48%   |
| Trinity           | 25        | 0.27%   |
| Budgie            | 25        | 0.27%   |
| GNOME Classic     | 22        | 0.24%   |
| awesome           | 10        | 0.11%   |
| sway              | 8         | 0.09%   |
| fluxbox           | 8         | 0.09%   |
| KDE4              | 6         | 0.06%   |
| Enlightenment     | 6         | 0.06%   |
| ICEWM             | 4         | 0.04%   |
| DWM               | 4         | 0.04%   |
| bspwm             | 4         | 0.04%   |
| xmonad            | 3         | 0.03%   |
| x-session-manager | 3         | 0.03%   |
| default           | 3         | 0.03%   |
| Cutefish          | 3         | 0.03%   |
| Unity             | 2         | 0.02%   |
| Phosh:GNOME       | 2         | 0.02%   |
| GNUstep           | 2         | 0.02%   |
| fvwm              | 2         | 0.02%   |
| wmaker-common     | 1         | 0.01%   |
| UKUI              | 1         | 0.01%   |
| matchbox          | 1         | 0.01%   |
| jwm               | 1         | 0.01%   |
| i3-with-shmlog    | 1         | 0.01%   |
| i3-gaps           | 1         | 0.01%   |
| gnome-xorg        | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 4863      | 52.9%   |
| Unknown     | 2000      | 21.76%  |
| Wayland     | 1366      | 14.86%  |
| Tty         | 960       | 10.44%  |
| Web         | 2         | 0.02%   |
| Unspecified | 2         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4210      | 45.63%  |
| GDM     | 1478      | 16.02%  |
| LightDM | 1448      | 15.69%  |
| SDDM    | 1023      | 11.09%  |
| TDM     | 598       | 6.48%   |
| GDM3    | 353       | 3.83%   |
| XDM     | 39        | 0.42%   |
| SLiM    | 30        | 0.33%   |
| NODM    | 19        | 0.21%   |
| KDM     | 13        | 0.14%   |
| LXDM    | 9         | 0.1%    |
| Ly      | 3         | 0.03%   |
| WDM     | 2         | 0.02%   |
| GREETD  | 2         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2944      | 32.1%   |
| Unknown | 1446      | 15.77%  |
| ru_RU   | 1089      | 11.87%  |
| de_DE   | 551       | 6.01%   |
| fr_FR   | 447       | 4.87%   |
| en_GB   | 441       | 4.81%   |
| pt_BR   | 271       | 2.95%   |
| es_ES   | 254       | 2.77%   |
| it_IT   | 218       | 2.38%   |
| C       | 137       | 1.49%   |
| pl_PL   | 134       | 1.46%   |
| en_CA   | 116       | 1.26%   |
| en_AU   | 110       | 1.2%    |
| zh_CN   | 61        | 0.67%   |
| es_MX   | 60        | 0.65%   |
| en_IN   | 56        | 0.61%   |
| es_AR   | 48        | 0.52%   |
| en_IE   | 48        | 0.52%   |
| hu_HU   | 43        | 0.47%   |
| es_VE   | 38        | 0.41%   |
| es_CL   | 36        | 0.39%   |
| de_CH   | 35        | 0.38%   |
| de_AT   | 32        | 0.35%   |
| ja_JP   | 31        | 0.34%   |
| pt_PT   | 30        | 0.33%   |
| nl_NL   | 26        | 0.28%   |
| en_NZ   | 25        | 0.27%   |
| cs_CZ   | 25        | 0.27%   |
| fi_FI   | 21        | 0.23%   |
| en_ZA   | 21        | 0.23%   |
| sv_SE   | 20        | 0.22%   |
| nl_BE   | 17        | 0.19%   |
| fr_BE   | 17        | 0.19%   |
| es_CO   | 16        | 0.17%   |
| ru_UA   | 15        | 0.16%   |
| ca_ES   | 14        | 0.15%   |
| uk_UA   | 13        | 0.14%   |
| en_SG   | 13        | 0.14%   |
| tr_TR   | 12        | 0.13%   |
| ko_KR   | 12        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4831      | 52.87%  |
| BIOS | 4306      | 47.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Computers | Percent |
|------------|-----------|---------|
| Ext4       | 6379      | 70.13%  |
| Overlay    | 1882      | 20.69%  |
| Btrfs      | 314       | 3.45%   |
| Unknown    | 168       | 1.85%   |
| Zfs        | 132       | 1.45%   |
| Xfs        | 113       | 1.24%   |
| Ext3       | 30        | 0.33%   |
| Ext2       | 24        | 0.26%   |
| Tmpfs      | 17        | 0.19%   |
| Rootfs     | 17        | 0.19%   |
| Aufs       | 7         | 0.08%   |
| F2fs       | 6         | 0.07%   |
| XXXXXXX    | 2         | 0.02%   |
| Ubifs      | 2         | 0.02%   |
| Jfs        | 2         | 0.02%   |
| Fuse.sshfs | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 5131      | 55.84%  |
| MBR     | 2326      | 25.31%  |
| Unknown | 1732      | 18.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7468      | 81.76%  |
| Yes       | 1666      | 18.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6446      | 70.63%  |
| Yes       | 2681      | 29.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1397      | 15.48%  |
| Lenovo                  | 1314      | 14.56%  |
| Hewlett-Packard         | 980       | 10.86%  |
| Dell                    | 959       | 10.63%  |
| Apple                   | 712       | 7.89%   |
| Gigabyte Technology     | 590       | 6.54%   |
| MSI                     | 430       | 4.76%   |
| ASRock                  | 359       | 3.98%   |
| Acer                    | 332       | 3.68%   |
| Intel                   | 207       | 2.29%   |
| Google                  | 148       | 1.64%   |
| Raspberry Pi Foundation | 132       | 1.46%   |
| Unknown                 | 131       | 1.45%   |
| Supermicro              | 93        | 1.03%   |
| Samsung Electronics     | 77        | 0.85%   |
| Toshiba                 | 76        | 0.84%   |
| Fujitsu                 | 59        | 0.65%   |
| ECS                     | 54        | 0.6%    |
| Aquarius                | 47        | 0.52%   |
| HUAWEI                  | 41        | 0.45%   |
| Sony                    | 40        | 0.44%   |
| Foxconn                 | 37        | 0.41%   |
| AZW                     | 33        | 0.37%   |
| ASRockRack              | 29        | 0.32%   |
| Notebook                | 28        | 0.31%   |
| Positivo                | 25        | 0.28%   |
| Medion                  | 24        | 0.27%   |
| IBM                     | 22        | 0.24%   |
| Pegatron                | 21        | 0.23%   |
| Microsoft               | 19        | 0.21%   |
| Fujitsu Siemens         | 19        | 0.21%   |
| Biostar                 | 19        | 0.21%   |
| Alienware               | 17        | 0.19%   |
| sunxi                   | 14        | 0.16%   |
| Panasonic               | 14        | 0.16%   |
| Packard Bell            | 14        | 0.16%   |
| Hardkernel              | 14        | 0.16%   |
| AMI                     | 14        | 0.16%   |
| TUXEDO                  | 13        | 0.14%   |
| Pine Microsystems       | 13        | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 354       | 3.92%   |
| Unknown                                   | 159       | 1.76%   |
| ASUS All Series                           | 115       | 1.27%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 114       | 1.26%   |
| Apple MacBookAir7,2                       | 77        | 0.85%   |
| Apple MacBookAir7,1                       | 77        | 0.85%   |
| Google Enguarde                           | 74        | 0.82%   |
| Apple MacBook2,1                          | 56        | 0.62%   |
| ASUS S20 K29                              | 55        | 0.61%   |
| Aquarius NS585                            | 44        | 0.49%   |
| MSI MS-7996                               | 38        | 0.42%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 28        | 0.31%   |
| Supermicro Super Server                   | 24        | 0.27%   |
| Lenovo ThinkPad E475 20H40006US           | 24        | 0.27%   |
| MSI MS-7817                               | 23        | 0.25%   |
| HP Notebook                               | 23        | 0.25%   |
| Google Terra                              | 23        | 0.25%   |
| ECS G31T-M9                               | 23        | 0.25%   |
| Apple MacBook4,1                          | 23        | 0.25%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 21        | 0.23%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 21        | 0.23%   |
| ASRock H470M-HVS                          | 20        | 0.22%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 19        | 0.21%   |
| Dell OptiPlex 7010                        | 19        | 0.21%   |
| ASUS PRIME H510M-A                        | 19        | 0.21%   |
| Gigabyte H81M-S2V                         | 18        | 0.2%    |
| HP Pavilion g6                            | 17        | 0.19%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.18%   |
| Gigabyte H410M S2H                        | 16        | 0.18%   |
| Gigabyte B450M DS3H                       | 16        | 0.18%   |
| ECS H61H2-M13                             | 16        | 0.18%   |
| Acer Aspire A315-23                       | 16        | 0.18%   |
| ASUS P8H61-M LX3 R2.0                     | 15        | 0.17%   |
| ASUS 1005HA                               | 15        | 0.17%   |
| ASUS TUF Gaming X570-PLUS                 | 14        | 0.16%   |
| ASRock B450M Pro4                         | 14        | 0.16%   |
| Dell Latitude E7440                       | 13        | 0.14%   |
| ASUS PRIME B450M-A                        | 13        | 0.14%   |
| ASUS PRIME A320M-K                        | 13        | 0.14%   |
| MSI MS-7C56                               | 12        | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 805       | 8.92%   |
| Apple MacBook5     | 355       | 3.93%   |
| Dell Latitude      | 260       | 2.88%   |
| Dell Inspiron      | 229       | 2.54%   |
| Acer Aspire        | 212       | 2.35%   |
| ASUS PRIME         | 187       | 2.07%   |
| Lenovo IdeaPad     | 179       | 1.98%   |
| Unknown            | 159       | 1.76%   |
| Apple MacBookAir7  | 154       | 1.71%   |
| HP EliteBook       | 146       | 1.62%   |
| RPi Raspberry      | 132       | 1.46%   |
| HP Pavilion        | 123       | 1.36%   |
| Dell OptiPlex      | 123       | 1.36%   |
| ASUS All           | 115       | 1.27%   |
| HP Compaq          | 101       | 1.12%   |
| Dell Precision     | 96        | 1.06%   |
| ASUS ROG           | 91        | 1.01%   |
| HP ProBook         | 88        | 0.98%   |
| HP Laptop          | 88        | 0.98%   |
| Dell XPS           | 83        | 0.92%   |
| Google Enguarde    | 74        | 0.82%   |
| Dell Vostro        | 70        | 0.78%   |
| Lenovo ThinkCentre | 69        | 0.76%   |
| ASUS TUF           | 68        | 0.75%   |
| ASUS VivoBook      | 63        | 0.7%    |
| Toshiba Satellite  | 59        | 0.65%   |
| Apple MacBook2     | 56        | 0.62%   |
| ASUS S20           | 55        | 0.61%   |
| Dell PowerEdge     | 53        | 0.59%   |
| HP ProLiant        | 50        | 0.55%   |
| Aquarius NS585     | 44        | 0.49%   |
| MSI MS-7996        | 38        | 0.42%   |
| Gigabyte B450M     | 36        | 0.4%    |
| Lenovo Yoga        | 35        | 0.39%   |
| ASUS ZenBook       | 34        | 0.38%   |
| ASUS P8H61-M       | 34        | 0.38%   |
| HP ENVY            | 32        | 0.35%   |
| HP ZBook           | 30        | 0.33%   |
| Lenovo Legion      | 29        | 0.32%   |
| HP 250             | 29        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 959       | 10.63%  |
| 2019    | 781       | 8.65%   |
| 2018    | 721       | 7.99%   |
| 2009    | 687       | 7.61%   |
| 2021    | 667       | 7.39%   |
| 2012    | 641       | 7.1%    |
| 2011    | 539       | 5.97%   |
| 2013    | 531       | 5.88%   |
| 2017    | 530       | 5.87%   |
| 2015    | 495       | 5.48%   |
| 2016    | 471       | 5.22%   |
| 2014    | 411       | 4.55%   |
| 2010    | 350       | 3.88%   |
| 2022    | 320       | 3.55%   |
| 2008    | 277       | 3.07%   |
| Unknown | 240       | 2.66%   |
| 2007    | 229       | 2.54%   |
| 2006    | 78        | 0.86%   |
| 2005    | 46        | 0.51%   |
| 2004    | 19        | 0.21%   |
| 2003    | 16        | 0.18%   |
| 2023    | 9         | 0.1%    |
| 2002    | 3         | 0.03%   |
| 2001    | 3         | 0.03%   |
| 2000    | 2         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4615      | 51.14%  |
| Desktop        | 3430      | 38.01%  |
| Convertible    | 261       | 2.89%   |
| System on chip | 219       | 2.43%   |
| Server         | 185       | 2.05%   |
| Mini pc        | 183       | 2.03%   |
| All in one     | 70        | 0.78%   |
| Tablet         | 51        | 0.57%   |
| Phone          | 10        | 0.11%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 8584      | 94.64%  |
| Enabled  | 486       | 5.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8854      | 98.09%  |
| Yes  | 172       | 1.91%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1917      | 21.01%  |
| 16.01-24.0      | 1692      | 18.54%  |
| 3.01-4.0        | 1608      | 17.62%  |
| 8.01-16.0       | 1357      | 14.87%  |
| 32.01-64.0      | 813       | 8.91%   |
| 1.01-2.0        | 760       | 8.33%   |
| 64.01-256.0     | 400       | 4.38%   |
| 2.01-3.0        | 177       | 1.94%   |
| 0.51-1.0        | 158       | 1.73%   |
| 24.01-32.0      | 147       | 1.61%   |
| 0.01-0.5        | 48        | 0.53%   |
| More than 256.0 | 30        | 0.33%   |
| Unknown         | 18        | 0.2%    |
| 0               | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 3040      | 31.34%  |
| 2.01-3.0        | 1767      | 18.21%  |
| 0.51-1.0        | 1477      | 15.23%  |
| 4.01-8.0        | 1295      | 13.35%  |
| 3.01-4.0        | 955       | 9.84%   |
| 8.01-16.0       | 451       | 4.65%   |
| 0.01-0.5        | 426       | 4.39%   |
| 16.01-24.0      | 126       | 1.3%    |
| 32.01-64.0      | 67        | 0.69%   |
| 24.01-32.0      | 44        | 0.45%   |
| Unknown         | 26        | 0.27%   |
| 64.01-256.0     | 24        | 0.25%   |
| More than 256.0 | 2         | 0.02%   |
| 0               | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5841      | 63.41%  |
| 2       | 1880      | 20.41%  |
| 3       | 616       | 6.69%   |
| 4       | 359       | 3.9%    |
| 5       | 169       | 1.83%   |
| 6       | 91        | 0.99%   |
| 0       | 68        | 0.74%   |
| 7       | 60        | 0.65%   |
| 8       | 46        | 0.5%    |
| 9       | 22        | 0.24%   |
| 10      | 15        | 0.16%   |
| 13      | 11        | 0.12%   |
| 11      | 7         | 0.08%   |
| 14      | 6         | 0.07%   |
| 12      | 6         | 0.07%   |
| Unknown | 3         | 0.03%   |
| 28      | 2         | 0.02%   |
| 16      | 2         | 0.02%   |
| 46      | 1         | 0.01%   |
| 29      | 1         | 0.01%   |
| 27      | 1         | 0.01%   |
| 26      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |
| 21      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |
| 17      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6075      | 66.91%  |
| Yes       | 3004      | 33.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7834      | 86.62%  |
| No        | 1210      | 13.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6128      | 67.62%  |
| No        | 2934      | 32.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5028      | 55.3%   |
| No        | 4065      | 44.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 2047      | 22.58%  |
| Russia       | 1254      | 13.83%  |
| Germany      | 877       | 9.67%   |
| France       | 590       | 6.51%   |
| Brazil       | 422       | 4.66%   |
| Spain        | 366       | 4.04%   |
| Italy        | 327       | 3.61%   |
| UK           | 250       | 2.76%   |
| Poland       | 213       | 2.35%   |
| Canada       | 189       | 2.08%   |
| Switzerland  | 148       | 1.63%   |
| Netherlands  | 146       | 1.61%   |
| Australia    | 139       | 1.53%   |
| China        | 116       | 1.28%   |
| Mexico       | 98        | 1.08%   |
| Ukraine      | 93        | 1.03%   |
| India        | 85        | 0.94%   |
| Sweden       | 80        | 0.88%   |
| Hungary      | 80        | 0.88%   |
| Belgium      | 80        | 0.88%   |
| Austria      | 80        | 0.88%   |
| Argentina    | 78        | 0.86%   |
| Portugal     | 68        | 0.75%   |
| Finland      | 66        | 0.73%   |
| Czechia      | 60        | 0.66%   |
| Turkey       | 56        | 0.62%   |
| Norway       | 51        | 0.56%   |
| Romania      | 47        | 0.52%   |
| Japan        | 46        | 0.51%   |
| Chile        | 46        | 0.51%   |
| Venezuela    | 44        | 0.49%   |
| Greece       | 39        | 0.43%   |
| Bulgaria     | 39        | 0.43%   |
| Ireland      | 36        | 0.4%    |
| New Zealand  | 34        | 0.38%   |
| Denmark      | 31        | 0.34%   |
| Colombia     | 31        | 0.34%   |
| Indonesia    | 30        | 0.33%   |
| South Africa | 29        | 0.32%   |
| Belarus      | 29        | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangor            | 752       | 7.88%   |
| Voronezh          | 732       | 7.67%   |
| Dover-Foxcroft    | 305       | 3.2%    |
| Moscow            | 129       | 1.35%   |
| St Petersburg     | 115       | 1.21%   |
| Paris             | 99        | 1.04%   |
| Berlin            | 77        | 0.81%   |
| Sao Paulo         | 68        | 0.71%   |
| Vienna            | 61        | 0.64%   |
| Madrid            | 61        | 0.64%   |
| Seville           | 58        | 0.61%   |
| Zurich            | 53        | 0.56%   |
| Warsaw            | 49        | 0.51%   |
| Munich            | 48        | 0.5%    |
| Amsterdam         | 47        | 0.49%   |
| Milan             | 44        | 0.46%   |
| Barcelona         | 40        | 0.42%   |
| Hamburg           | 38        | 0.4%    |
| Sydney            | 37        | 0.39%   |
| Budapest          | 34        | 0.36%   |
| London            | 32        | 0.34%   |
| Helsinki          | 32        | 0.34%   |
| Frankfurt am Main | 32        | 0.34%   |
| Toronto           | 31        | 0.32%   |
| Perm              | 31        | 0.32%   |
| Falkenstein       | 29        | 0.3%    |
| Rio de Janeiro    | 28        | 0.29%   |
| Prague            | 28        | 0.29%   |
| Melbourne         | 27        | 0.28%   |
| Brisbane          | 26        | 0.27%   |
| San Jose          | 24        | 0.25%   |
| Cologne           | 24        | 0.25%   |
| Yekaterinburg     | 23        | 0.24%   |
| New York          | 23        | 0.24%   |
| Kyiv              | 23        | 0.24%   |
| Stuttgart         | 22        | 0.23%   |
| Rome              | 22        | 0.23%   |
| Istanbul          | 22        | 0.23%   |
| Dublin            | 22        | 0.23%   |
| Brasília         | 22        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1974      | 2930   | 15.33%  |
| WDC                 | 1855      | 3081   | 14.4%   |
| Seagate             | 1749      | 2959   | 13.58%  |
| Toshiba             | 884       | 1312   | 6.86%   |
| Kingston            | 764       | 985    | 5.93%   |
| Unknown             | 686       | 904    | 5.33%   |
| Crucial             | 573       | 741    | 4.45%   |
| SanDisk             | 523       | 674    | 4.06%   |
| Hitachi             | 391       | 543    | 3.04%   |
| Intel               | 298       | 416    | 2.31%   |
| Fujitsu             | 298       | 309    | 2.31%   |
| SK hynix            | 257       | 327    | 2%      |
| A-DATA Technology   | 230       | 361    | 1.79%   |
| HGST                | 215       | 340    | 1.67%   |
| Apple               | 213       | 263    | 1.65%   |
| Micron Technology   | 156       | 187    | 1.21%   |
| China               | 110       | 130    | 0.85%   |
| SPCC                | 76        | 86     | 0.59%   |
| Phison              | 75        | 105    | 0.58%   |
| Transcend           | 73        | 83     | 0.57%   |
| KIOXIA              | 68        | 83     | 0.53%   |
| Unknown             | 67        | 70     | 0.52%   |
| PNY                 | 63        | 106    | 0.49%   |
| OCZ                 | 59        | 72     | 0.46%   |
| Intenso             | 53        | 72     | 0.41%   |
| Corsair             | 52        | 77     | 0.4%    |
| LITEON              | 49        | 58     | 0.38%   |
| Hewlett-Packard     | 46        | 77     | 0.36%   |
| Patriot             | 45        | 55     | 0.35%   |
| Maxtor              | 44        | 57     | 0.34%   |
| JMicron Technology  | 42        | 44     | 0.33%   |
| Silicon Motion      | 37        | 45     | 0.29%   |
| Netac               | 36        | 100    | 0.28%   |
| GOODRAM             | 36        | 54     | 0.28%   |
| SABRENT             | 32        | 34     | 0.25%   |
| Gigabyte Technology | 32        | 38     | 0.25%   |
| Team                | 25        | 42     | 0.19%   |
| ASMT                | 24        | 34     | 0.19%   |
| LITEONIT            | 23        | 28     | 0.18%   |
| XPG                 | 22        | 33     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 238       | 1.67%   |
| Kingston SA400S37240G 240GB SSD    | 166       | 1.16%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 133       | 0.93%   |
| Seagate ST500DM002-1BD142 500GB    | 106       | 0.74%   |
| Kingston SA400S37120G 120GB SSD    | 105       | 0.74%   |
| Crucial CT480BX500SSD1 480GB       | 86        | 0.6%    |
| Samsung SSD 860 EVO 500GB          | 85        | 0.6%    |
| Kingston SV300S37A120G 120GB SSD   | 82        | 0.57%   |
| Kingston SA400S37480G 480GB SSD    | 82        | 0.57%   |
| Samsung SSD 850 EVO 250GB          | 81        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB     | 80        | 0.56%   |
| Apple SSD AP0128H 121GB            | 77        | 0.54%   |
| Samsung SSD 860 EVO 250GB          | 76        | 0.53%   |
| Samsung SSD 860 EVO 1TB            | 76        | 0.53%   |
| Seagate ST1000LM035-1RK172 1TB     | 75        | 0.53%   |
| Apple SSD SM0128G 121GB            | 74        | 0.52%   |
| Toshiba DT01ACA050 500GB           | 71        | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB       | 71        | 0.5%    |
| Crucial CT500MX500SSD1 500GB       | 70        | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 67        | 0.47%   |
| Unknown                            | 67        | 0.47%   |
| Unknown MMC Card  32GB             | 66        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB        | 62        | 0.43%   |
| Crucial CT240BX500SSD1 240GB       | 59        | 0.41%   |
| Samsung SSD 850 EVO 500GB          | 56        | 0.39%   |
| Toshiba DT01ACA100 1TB             | 55        | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB     | 55        | 0.39%   |
| Toshiba MK1655GSXF 160GB           | 53        | 0.37%   |
| Toshiba MQ01ABD100 1TB             | 51        | 0.36%   |
| A-DATA SU800 512GB SSD             | 51        | 0.36%   |
| HGST HTS721010A9E630 1TB           | 49        | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB           | 47        | 0.33%   |
| Toshiba HDWD110 1TB                | 45        | 0.32%   |
| Unknown MMC Card  64GB             | 43        | 0.3%    |
| Toshiba MK1653GSX 160GB            | 43        | 0.3%    |
| Seagate ST2000DM008-2FR102 2TB     | 43        | 0.3%    |
| Seagate ST1000DM003-1ER162 1TB     | 41        | 0.29%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 40        | 0.28%   |
| Unknown AGND3R  16GB               | 40        | 0.28%   |
| Seagate ST1000DM003-1CH162 1TB     | 40        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1704      | 2875   | 33%     |
| WDC                 | 1426      | 2452   | 27.61%  |
| Toshiba             | 708       | 1082   | 13.71%  |
| Hitachi             | 390       | 541    | 7.55%   |
| Fujitsu             | 298       | 309    | 5.77%   |
| HGST                | 214       | 338    | 4.14%   |
| Samsung Electronics | 184       | 241    | 3.56%   |
| Maxtor              | 42        | 49     | 0.81%   |
| Unknown             | 38        | 52     | 0.74%   |
| SABRENT             | 32        | 34     | 0.62%   |
| Apple               | 22        | 26     | 0.43%   |
| ASMT                | 16        | 25     | 0.31%   |
| Hewlett-Packard     | 9         | 23     | 0.17%   |
| Intenso             | 8         | 10     | 0.15%   |
| ASMedia             | 7         | 7      | 0.14%   |
| IBM/Hitachi         | 6         | 7      | 0.12%   |
| HPE                 | 5         | 10     | 0.1%    |
| USB3.0              | 4         | 4      | 0.08%   |
| JMicron Technology  | 4         | 5      | 0.08%   |
| QNAP                | 3         | 5      | 0.06%   |
| IBM-ESXS            | 3         | 6      | 0.06%   |
| SILICONMOTION       | 2         | 2      | 0.04%   |
| Pear 2TB            | 2         | 2      | 0.04%   |
| NETAPP              | 2         | 6      | 0.04%   |
| IET                 | 2         | 2      | 0.04%   |
| USB 3.0             | 1         | 2      | 0.02%   |
| USB                 | 1         | 1      | 0.02%   |
| Unknown (CF)        | 1         | 1      | 0.02%   |
| TrueNAS             | 1         | 1      | 0.02%   |
| Synology            | 1         | 1      | 0.02%   |
| StoreJet            | 1         | 1      | 0.02%   |
| SD                  | 1         | 1      | 0.02%   |
| SAGE                | 1         | 1      | 0.02%   |
| RSH-319             | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| pqi                 | 1         | 1      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| NAS                 | 1         | 10     | 0.02%   |
| Maxone              | 1         | 1      | 0.02%   |
| MaxDigital          | 1         | 4      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 933       | 1295   | 21.67%  |
| Kingston            | 647       | 841    | 15.03%  |
| Crucial             | 516       | 664    | 11.98%  |
| SanDisk             | 373       | 486    | 8.66%   |
| WDC                 | 199       | 248    | 4.62%   |
| A-DATA Technology   | 171       | 274    | 3.97%   |
| Intel               | 128       | 181    | 2.97%   |
| China               | 108       | 128    | 2.51%   |
| Apple               | 105       | 113    | 2.44%   |
| Micron Technology   | 74        | 97     | 1.72%   |
| Toshiba             | 68        | 88     | 1.58%   |
| Transcend           | 66        | 76     | 1.53%   |
| SPCC                | 61        | 67     | 1.42%   |
| OCZ                 | 59        | 72     | 1.37%   |
| SK hynix            | 57        | 70     | 1.32%   |
| PNY                 | 47        | 83     | 1.09%   |
| Intenso             | 41        | 55     | 0.95%   |
| LITEON              | 38        | 45     | 0.88%   |
| Patriot             | 37        | 43     | 0.86%   |
| Netac               | 36        | 100    | 0.84%   |
| GOODRAM             | 30        | 39     | 0.7%    |
| LITEONIT            | 23        | 28     | 0.53%   |
| Corsair             | 23        | 28     | 0.53%   |
| Team                | 22        | 38     | 0.51%   |
| JMicron Technology  | 20        | 21     | 0.46%   |
| KingDian            | 19        | 20     | 0.44%   |
| Plextor             | 18        | 24     | 0.42%   |
| Seagate             | 17        | 21     | 0.39%   |
| Hewlett-Packard     | 17        | 23     | 0.39%   |
| Gigabyte Technology | 16        | 18     | 0.37%   |
| Apacer              | 15        | 15     | 0.35%   |
| Unknown             | 14        | 15     | 0.33%   |
| Unknown             | 13        | 16     | 0.3%    |
| LDLC                | 12        | 12     | 0.28%   |
| KingSpec            | 10        | 11     | 0.23%   |
| TO Exter            | 9         | 9      | 0.21%   |
| Mushkin             | 9         | 10     | 0.21%   |
| Lexar               | 8         | 11     | 0.19%   |
| Hajaan              | 8         | 11     | 0.19%   |
| FORESEE             | 7         | 8      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4348      | 8174   | 37.59%  |
| SSD     | 3780      | 5692   | 32.68%  |
| NVMe    | 2600      | 3732   | 22.48%  |
| MMC     | 695       | 889    | 6.01%   |
| Unknown | 144       | 210    | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6607      | 13223  | 63.65%  |
| NVMe | 2594      | 3714   | 24.99%  |
| MMC  | 695       | 889    | 6.7%    |
| SAS  | 484       | 871    | 4.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives  | Percent |
|-------------|-----------|---------|---------|
| 0.01-0.5    | 5143      | 7631    | 59.7%   |
| 0.51-1.0    | 2106      | 3264    | 24.45%  |
| 1.01-2.0    | 627       | 1132    | 7.28%   |
| 3.01-4.0    | 272       | 640     | 3.16%   |
| 4.01-10.0   | 248       | 651     | 2.88%   |
| 2.01-3.0    | 162       | 303     | 1.88%   |
| 10.01-20.0  | 54        | 240     | 0.63%   |
| 20.01-50.0  | 1         | 1       | 0.01%   |
| 50.01-100.0 | 1         | 4       | 0.01%   |
| 0           | 1         | Unknown | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2084      | 22.32%  |
| 251-500        | 1682      | 18.01%  |
| Unknown        | 1624      | 17.39%  |
| 501-1000       | 1141      | 12.22%  |
| 1001-2000      | 623       | 6.67%   |
| 51-100         | 610       | 6.53%   |
| More than 3000 | 506       | 5.42%   |
| 1-20           | 442       | 4.73%   |
| 21-50          | 386       | 4.13%   |
| 2001-3000      | 241       | 2.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3193      | 33.29%  |
| Unknown        | 1624      | 16.93%  |
| 101-250        | 1071      | 11.17%  |
| 21-50          | 1016      | 10.59%  |
| 51-100         | 843       | 8.79%   |
| 251-500        | 669       | 6.97%   |
| 501-1000       | 515       | 5.37%   |
| 1001-2000      | 301       | 3.14%   |
| More than 3000 | 217       | 2.26%   |
| 2001-3000      | 120       | 1.25%   |
| 0              | 23        | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 26        | 34     | 1.92%   |
| Fujitsu MHZ2160BH FFS G1 160GB     | 25        | 25     | 1.85%   |
| Kingston SV300S37A120G 120GB SSD   | 23        | 23     | 1.7%    |
| WDC WD5000AAKX-60U6AA0 500GB       | 21        | 25     | 1.55%   |
| Seagate ST9500325AS 500GB          | 13        | 15     | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 13        | 16     | 0.96%   |
| Hitachi HTS543216L9SA02 160GB      | 11        | 11     | 0.81%   |
| Toshiba MQ01ABD100 1TB             | 10        | 10     | 0.74%   |
| Hitachi HDS721050CLA362 500GB      | 10        | 10     | 0.74%   |
| Toshiba MK1655GSXF 160GB           | 9         | 9      | 0.67%   |
| Toshiba MK1653GSX 160GB            | 9         | 9      | 0.67%   |
| Seagate ST9500420AS 500GB          | 9         | 9      | 0.67%   |
| Seagate ST31500341AS 1TB           | 9         | 15     | 0.67%   |
| Seagate ST1000DM003-9YN162 1TB     | 9         | 10     | 0.67%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 8         | 8      | 0.59%   |
| Seagate ST3500418AS 500GB          | 8         | 12     | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB     | 8         | 9      | 0.59%   |
| Toshiba DT01ACA100 1TB             | 7         | 9      | 0.52%   |
| Toshiba DT01ACA050 500GB           | 7         | 8      | 0.52%   |
| Seagate ST500LT012-9WS142 500GB    | 7         | 8      | 0.52%   |
| Seagate ST500LM021-1KJ152 500GB    | 7         | 7      | 0.52%   |
| Seagate ST3250318AS 250GB          | 7         | 8      | 0.52%   |
| Seagate ST31000528AS 1TB           | 7         | 7      | 0.52%   |
| Seagate ST250DM000-1BD141 250GB    | 7         | 7      | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB     | 7         | 7      | 0.52%   |
| HGST HTS725050A7E630 500GB         | 7         | 9      | 0.52%   |
| WDC WD5000AAKX-001CA0 500GB        | 6         | 8      | 0.44%   |
| Seagate ST3320613AS 320GB          | 6         | 6      | 0.44%   |
| Seagate ST3160815AS 160GB          | 6         | 8      | 0.44%   |
| Hitachi HTS545050B9A300 500GB      | 6         | 6      | 0.44%   |
| Hitachi HDS721050DLE630 500GB      | 6         | 11     | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 5         | 5      | 0.37%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 5         | 6      | 0.37%   |
| WDC WD20EFRX-68EUZN0 2TB           | 5         | 16     | 0.37%   |
| WDC WD20EARX-00PASB0 2TB           | 5         | 7      | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB           | 5         | 5      | 0.37%   |
| WDC WD10EARS-00Y5B1 1TB            | 5         | 5      | 0.37%   |
| WDC WD10EADS-00M2B0 1TB            | 5         | 5      | 0.37%   |
| Seagate ST3500413AS 500GB          | 5         | 6      | 0.37%   |
| Seagate ST320LT007-9ZV142 320GB    | 5         | 7      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 350       | 467    | 26.8%   |
| WDC                 | 277       | 366    | 21.21%  |
| Hitachi             | 128       | 158    | 9.8%    |
| Samsung Electronics | 98        | 108    | 7.5%    |
| Toshiba             | 94        | 105    | 7.2%    |
| Kingston            | 56        | 63     | 4.29%   |
| Intel               | 41        | 51     | 3.14%   |
| Fujitsu             | 40        | 41     | 3.06%   |
| HGST                | 31        | 34     | 2.37%   |
| Crucial             | 26        | 32     | 1.99%   |
| A-DATA Technology   | 23        | 31     | 1.76%   |
| SK hynix            | 22        | 27     | 1.68%   |
| SanDisk             | 22        | 27     | 1.68%   |
| Micron Technology   | 17        | 22     | 1.3%    |
| Maxtor              | 14        | 15     | 1.07%   |
| OCZ                 | 8         | 9      | 0.61%   |
| LITEONIT            | 5         | 6      | 0.38%   |
| KingDian            | 5         | 5      | 0.38%   |
| China               | 5         | 5      | 0.38%   |
| LITEON              | 4         | 4      | 0.31%   |
| Corsair             | 4         | 4      | 0.31%   |
| Unknown             | 2         | 2      | 0.15%   |
| PNY                 | 2         | 7      | 0.15%   |
| Plextor             | 2         | 3      | 0.15%   |
| JMicron Technology  | 2         | 2      | 0.15%   |
| IBM/Hitachi         | 2         | 2      | 0.15%   |
| Hewlett-Packard     | 2         | 3      | 0.15%   |
| Apple               | 2         | 2      | 0.15%   |
| Apacer              | 2         | 2      | 0.15%   |
| Unknown             | 2         | 2      | 0.15%   |
| Zheino              | 1         | 1      | 0.08%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Transcend           | 1         | 1      | 0.08%   |
| Teclast             | 1         | 1      | 0.08%   |
| Team                | 1         | 1      | 0.08%   |
| SSSTC               | 1         | 1      | 0.08%   |
| SPCC                | 1         | 1      | 0.08%   |
| ShiJi               | 1         | 1      | 0.08%   |
| Netac               | 1         | 1      | 0.08%   |
| Lenovo              | 1         | 1      | 0.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 350       | 467    | 35.32%  |
| WDC                 | 268       | 356    | 27.04%  |
| Hitachi             | 128       | 158    | 12.92%  |
| Toshiba             | 91        | 102    | 9.18%   |
| Samsung Electronics | 58        | 63     | 5.85%   |
| Fujitsu             | 40        | 41     | 4.04%   |
| HGST                | 31        | 34     | 3.13%   |
| Maxtor              | 14        | 15     | 1.41%   |
| IBM/Hitachi         | 2         | 2      | 0.2%    |
| Hewlett-Packard     | 2         | 3      | 0.2%    |
| USB3.0              | 1         | 1      | 0.1%    |
| Unknown             | 1         | 1      | 0.1%    |
| JMicron Technology  | 1         | 1      | 0.1%    |
| IBM                 | 1         | 1      | 0.1%    |
| ASMT                | 1         | 2      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |
| Apple               | 1         | 1      | 0.1%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 932       | 1249   | 74.8%   |
| SSD  | 275       | 330    | 22.07%  |
| NVMe | 39        | 45     | 3.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2         | 3      | 6.9%    |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 2         | 5      | 6.9%    |
| WDC WD5000BEVT-35A0RT0 500GB                     | 1         | 1      | 3.45%   |
| WDC WD4001FFSX-68JNUN0 4TB                       | 1         | 1      | 3.45%   |
| WDC WD30EZRS-00J99B0 3TB                         | 1         | 1      | 3.45%   |
| Toshiba MK6465GSX 640GB                          | 1         | 1      | 3.45%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 3.45%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 3.45%   |
| Seagate ST500DM005 HD502HJ 500GB                 | 1         | 1      | 3.45%   |
| Seagate ST3500830AS 500GB                        | 1         | 1      | 3.45%   |
| Seagate ST3500630A 500GB                         | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 980 250GB                | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 3.45%   |
| Samsung Electronics SP0802N 80GB                 | 1         | 1      | 3.45%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB     | 1         | 1      | 3.45%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD  | 1         | 1      | 3.45%   |
| Samsung Electronics HE103SJ 1TB                  | 1         | 2      | 3.45%   |
| Samsung Electronics HD253GJ 250GB                | 1         | 1      | 3.45%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 3.45%   |
| KingDian S400 120GB SSD                          | 1         | 1      | 3.45%   |
| IBM-ESXS ST9300605SS 304GB                       | 1         | 2      | 3.45%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 3.45%   |
| HGST HUH728080ALN600 8TB                         | 1         | 1      | 3.45%   |
| HGST HTS725050A7E630 500GB                       | 1         | 2      | 3.45%   |
| HGST HDN724040ALE640 4TB                         | 1         | 1      | 3.45%   |
| Hewlett-Packard SSD S700 500GB                   | 1         | 2      | 3.45%   |
| Crucial CT1000P1SSD8 1TB                         | 1         | 1      | 3.45%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 14     | 34.48%  |
| Seagate             | 7         | 8      | 24.14%  |
| WDC                 | 3         | 3      | 10.34%  |
| HGST                | 3         | 4      | 10.34%  |
| Toshiba             | 1         | 1      | 3.45%   |
| KingDian            | 1         | 1      | 3.45%   |
| IBM-ESXS            | 1         | 2      | 3.45%   |
| Hitachi             | 1         | 2      | 3.45%   |
| Hewlett-Packard     | 1         | 2      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 6203      | 11832  | 61.54%  |
| Detected | 2639      | 5201   | 26.18%  |
| Malfunc  | 1206      | 1624   | 11.97%  |
| Failed   | 29        | 38     | 0.29%   |
| Limited  | 2         | 2      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5496      | 50.42%  |
| AMD                              | 1499      | 13.75%  |
| Samsung Electronics              | 1073      | 9.84%   |
| Nvidia                           | 471       | 4.32%   |
| SanDisk                          | 402       | 3.69%   |
| ASMedia Technology               | 192       | 1.76%   |
| SK hynix                         | 186       | 1.71%   |
| Phison Electronics               | 165       | 1.51%   |
| Marvell Technology Group         | 145       | 1.33%   |
| Kingston Technology Company      | 129       | 1.18%   |
| Toshiba America Info Systems     | 120       | 1.1%    |
| JMicron Technology               | 101       | 0.93%   |
| LSI Logic / Symbios Logic        | 94        | 0.86%   |
| Apple                            | 87        | 0.8%    |
| Micron/Crucial Technology        | 83        | 0.76%   |
| Micron Technology                | 83        | 0.76%   |
| Silicon Motion                   | 82        | 0.75%   |
| ADATA Technology                 | 80        | 0.73%   |
| KIOXIA                           | 75        | 0.69%   |
| Broadcom / LSI                   | 62        | 0.57%   |
| VIA Technologies                 | 44        | 0.4%    |
| Silicon Image                    | 23        | 0.21%   |
| Hewlett-Packard                  | 23        | 0.21%   |
| Solid State Storage Technology   | 22        | 0.2%    |
| Adaptec                          | 22        | 0.2%    |
| Lite-On Technology               | 17        | 0.16%   |
| Realtek Semiconductor            | 16        | 0.15%   |
| Silicon Integrated Systems [SiS] | 15        | 0.14%   |
| Seagate Technology               | 15        | 0.14%   |
| Union Memory (Shenzhen)          | 13        | 0.12%   |
| MAXIO Technology (Hangzhou)      | 10        | 0.09%   |
| Shenzhen Longsys Electronics     | 6         | 0.06%   |
| Lenovo                           | 5         | 0.05%   |
| IBM                              | 5         | 0.05%   |
| Biwin Storage Technology         | 5         | 0.05%   |
| ULi Electronics                  | 4         | 0.04%   |
| Jiangsu Huacun Elec.             | 4         | 0.04%   |
| Integrated Technology Express    | 4         | 0.04%   |
| INNOGRIT                         | 4         | 0.04%   |
| 3ware                            | 4         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1019      | 8.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 584       | 4.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 414       | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 392       | 3.1%    |
| Nvidia MCP79 AHCI Controller                                                            | 371       | 2.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 323       | 2.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 226       | 1.79%   |
| AMD 400 Series Chipset SATA Controller                                                  | 223       | 1.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 219       | 1.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 205       | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 203       | 1.61%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 195       | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 193       | 1.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 190       | 1.5%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 176       | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 176       | 1.39%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 166       | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 158       | 1.25%   |
| Samsung NVMe SSD Controller 980                                                         | 156       | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 155       | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 148       | 1.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 137       | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 130       | 1.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 129       | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 121       | 0.96%   |
| AMD 500 Series Chipset SATA Controller                                                  | 115       | 0.91%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 105       | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 105       | 0.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 105       | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 102       | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 95        | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 93        | 0.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 92        | 0.73%   |
| Samsung Electronics SATA controller                                                     | 91        | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 90        | 0.71%   |
| Intel SATA Controller [RAID mode]                                                       | 88        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 88        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 87        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 87        | 0.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 85        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6354      | 57.25%  |
| NVMe | 2607      | 23.49%  |
| IDE  | 1324      | 11.93%  |
| RAID | 667       | 6.01%   |
| SAS  | 108       | 0.97%   |
| SCSI | 38        | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 6943      | 76.92%  |
| AMD                   | 1796      | 19.9%   |
| ARM                   | 242       | 2.68%   |
| CentaurHauls          | 11        | 0.12%   |
| Unknown               | 10        | 0.11%   |
| CHRP IBM,8233-E8B     | 5         | 0.06%   |
| sifive,u74-mc         | 4         | 0.04%   |
| sifive,bullet0        | 3         | 0.03%   |
| Phytium               | 3         | 0.03%   |
| Qualcomm              | 2         | 0.02%   |
| CHRP IBM,9131-52A     | 2         | 0.02%   |
| PowerNV FP5466G2      | 1         | 0.01%   |
| PowerNV C829UAG3      | 1         | 0.01%   |
| Marvell Semiconductor | 1         | 0.01%   |
| HISILICON             | 1         | 0.01%   |
| AppliedMicro          | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 356       | 3.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 195       | 2.16%   |
| ARM Processor                                 | 181       | 2%      |
| Intel Core i5-5250U CPU @ 1.60GHz             | 148       | 1.64%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 95        | 1.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 89        | 0.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 84        | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 82        | 0.91%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 76        | 0.84%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 68        | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 68        | 0.75%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 67        | 0.74%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 64        | 0.71%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 62        | 0.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 60        | 0.66%   |
| AMD Ryzen 5 3600 6-Core Processor             | 59        | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 58        | 0.64%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 53        | 0.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 52        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 49        | 0.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 49        | 0.54%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 47        | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 44        | 0.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 39        | 0.43%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 39        | 0.43%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 38        | 0.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 38        | 0.42%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 37        | 0.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 35        | 0.39%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 35        | 0.39%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 34        | 0.38%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 33        | 0.37%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 33        | 0.37%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 33        | 0.37%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 33        | 0.37%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 32        | 0.35%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 32        | 0.35%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 30        | 0.33%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 30        | 0.33%   |
| Intel Celeron N5105 @ 2.00GHz                 | 30        | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1777      | 19.67%  |
| Intel Core i7           | 1294      | 14.33%  |
| Other                   | 843       | 9.33%   |
| Intel Core 2 Duo        | 694       | 7.68%   |
| Intel Core i3           | 644       | 7.13%   |
| Intel Celeron           | 581       | 6.43%   |
| AMD Ryzen 5             | 430       | 4.76%   |
| Intel Xeon              | 358       | 3.96%   |
| AMD Ryzen 7             | 320       | 3.54%   |
| Intel Pentium           | 282       | 3.12%   |
| Intel Atom              | 200       | 2.21%   |
| AMD Ryzen 9             | 124       | 1.37%   |
| AMD FX                  | 114       | 1.26%   |
| Intel Core 2            | 102       | 1.13%   |
| Intel Pentium Dual-Core | 91        | 1.01%   |
| AMD Ryzen 3             | 78        | 0.86%   |
| Intel Core 2 Quad       | 63        | 0.7%    |
| AMD Ryzen 7 PRO         | 51        | 0.56%   |
| AMD A8                  | 44        | 0.49%   |
| AMD A10                 | 42        | 0.46%   |
| Intel Core i9           | 41        | 0.45%   |
| AMD A6                  | 39        | 0.43%   |
| AMD Ryzen Threadripper  | 37        | 0.41%   |
| Intel Pentium Dual      | 35        | 0.39%   |
| AMD A4                  | 35        | 0.39%   |
| Intel Pentium 4         | 34        | 0.38%   |
| Intel Pentium M         | 33        | 0.37%   |
| AMD Athlon II X2        | 33        | 0.37%   |
| AMD Athlon              | 33        | 0.37%   |
| AMD Ryzen 5 PRO         | 32        | 0.35%   |
| AMD Phenom II X4        | 32        | 0.35%   |
| AMD Athlon 64 X2        | 32        | 0.35%   |
| Intel Pentium Gold      | 30        | 0.33%   |
| Intel Genuine           | 29        | 0.32%   |
| Intel Pentium Silver    | 25        | 0.28%   |
| ARM Allwinner           | 22        | 0.24%   |
| AMD E                   | 22        | 0.24%   |
| AMD E1                  | 21        | 0.23%   |
| AMD Phenom II X6        | 16        | 0.18%   |
| AMD GX                  | 15        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3796      | 41.99%  |
| 4       | 3076      | 34.02%  |
| 6       | 776       | 8.58%   |
| 8       | 600       | 6.64%   |
| 1       | 322       | 3.56%   |
| 12      | 144       | 1.59%   |
| 16      | 112       | 1.24%   |
| 10      | 54        | 0.6%    |
| 3       | 40        | 0.44%   |
| 14      | 29        | 0.32%   |
| Unknown | 23        | 0.25%   |
| 32      | 19        | 0.21%   |
| 24      | 16        | 0.18%   |
| 20      | 13        | 0.14%   |
| 18      | 4         | 0.04%   |
| 64      | 3         | 0.03%   |
| 44      | 3         | 0.03%   |
| 28      | 3         | 0.03%   |
| 48      | 2         | 0.02%   |
| 22      | 2         | 0.02%   |
| 128     | 1         | 0.01%   |
| 80      | 1         | 0.01%   |
| 56      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8827      | 97.74%  |
| 2       | 173       | 1.92%   |
| Unknown | 23        | 0.25%   |
| 4       | 4         | 0.04%   |
| 3       | 2         | 0.02%   |
| 16      | 1         | 0.01%   |
| 8       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5400      | 59.74%  |
| 1       | 3608      | 39.92%  |
| Unknown | 23        | 0.25%   |
| 4       | 7         | 0.08%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 8627      | 95.46%  |
| Unknown        | 233       | 2.58%   |
| 32-bit         | 156       | 1.73%   |
| 64-bit         | 21        | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2107      | 22.78%  |
| 0x1067a    | 629       | 6.8%    |
| 0x306a9    | 399       | 4.31%   |
| 0x206a7    | 396       | 4.28%   |
| 0x306c3    | 383       | 4.14%   |
| 0x806c1    | 307       | 3.32%   |
| 0x306d4    | 260       | 2.81%   |
| 0x806ec    | 210       | 2.27%   |
| 0x906ea    | 208       | 2.25%   |
| 0x506e3    | 172       | 1.86%   |
| 0x806e9    | 166       | 1.79%   |
| 0x806ea    | 156       | 1.69%   |
| 0x30678    | 142       | 1.54%   |
| 0x40651    | 134       | 1.45%   |
| 0x406e3    | 123       | 1.33%   |
| 0x906e9    | 115       | 1.24%   |
| 0x08701021 | 115       | 1.24%   |
| 0x08108109 | 103       | 1.11%   |
| 0x406c4    | 94        | 1.02%   |
| 0xa0653    | 85        | 0.92%   |
| 0x20655    | 83        | 0.9%    |
| 0x6f6      | 80        | 0.87%   |
| 0x0a50000c | 79        | 0.85%   |
| 0x08600106 | 77        | 0.83%   |
| 0x10676    | 70        | 0.76%   |
| 0x906eb    | 69        | 0.75%   |
| 0x6fd      | 68        | 0.74%   |
| 0xa0652    | 67        | 0.72%   |
| 0x706a8    | 63        | 0.68%   |
| 0x0800820d | 61        | 0.66%   |
| 0x906c0    | 58        | 0.63%   |
| 0x506c9    | 58        | 0.63%   |
| 0x706e5    | 55        | 0.59%   |
| 0x08108102 | 55        | 0.59%   |
| 0xa0655    | 53        | 0.57%   |
| 0x0a201016 | 50        | 0.54%   |
| 0x08608103 | 49        | 0.53%   |
| 0x206d7    | 48        | 0.52%   |
| 0x906a3    | 47        | 0.51%   |
| 0x106c2    | 47        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1307      | 14.46%  |
| Penryn           | 783       | 8.66%   |
| Haswell          | 716       | 7.92%   |
| SandyBridge      | 575       | 6.36%   |
| IvyBridge        | 556       | 6.15%   |
| Unknown          | 468       | 5.18%   |
| Skylake          | 431       | 4.77%   |
| TigerLake        | 353       | 3.91%   |
| Zen 2            | 351       | 3.88%   |
| Silvermont       | 334       | 3.7%    |
| Broadwell        | 324       | 3.58%   |
| Zen+             | 293       | 3.24%   |
| Core             | 268       | 2.96%   |
| CometLake        | 250       | 2.77%   |
| Zen 3            | 232       | 2.57%   |
| Westmere         | 206       | 2.28%   |
| Zen              | 162       | 1.79%   |
| K10              | 146       | 1.62%   |
| Piledriver       | 122       | 1.35%   |
| Bonnell          | 115       | 1.27%   |
| Goldmont plus    | 114       | 1.26%   |
| Excavator        | 108       | 1.19%   |
| Icelake          | 94        | 1.04%   |
| Goldmont         | 84        | 0.93%   |
| Alderlake Hybrid | 82        | 0.91%   |
| Nehalem          | 73        | 0.81%   |
| P6               | 72        | 0.8%    |
| K8 Hammer        | 71        | 0.79%   |
| Tremont          | 61        | 0.67%   |
| NetBurst         | 58        | 0.64%   |
| Bobcat           | 53        | 0.59%   |
| Steamroller      | 41        | 0.45%   |
| Jaguar           | 36        | 0.4%    |
| Puma             | 34        | 0.38%   |
| Bulldozer        | 31        | 0.34%   |
| K10 Llano        | 21        | 0.23%   |
| K8 & K10 hybrid  | 7         | 0.08%   |
| K6               | 6         | 0.07%   |
| Geode            | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5214      | 52.3%   |
| Nvidia                                       | 2571      | 25.79%  |
| AMD                                          | 1896      | 19.02%  |
| Matrox Electronics Systems                   | 140       | 1.4%    |
| ASPEED Technology                            | 115       | 1.15%   |
| VIA Technologies                             | 11        | 0.11%   |
| Silicon Integrated Systems [SiS]             | 9         | 0.09%   |
| Zhaoxin                                      | 4         | 0.04%   |
| S3 Graphics                                  | 2         | 0.02%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| Silicon Motion                               | 1         | 0.01%   |
| Neomagic                                     | 1         | 0.01%   |
| Loongson Technology                          | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| Cirrus Logic                                 | 1         | 0.01%   |
| ATI Technologies                             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 382       | 3.7%    |
| Nvidia C79 [GeForce 9400M G]                                                             | 354       | 3.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 329       | 3.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 290       | 2.81%   |
| Intel UHD Graphics 620                                                                   | 210       | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 203       | 1.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 190       | 1.84%   |
| Intel HD Graphics 620                                                                    | 187       | 1.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 178       | 1.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 178       | 1.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 172       | 1.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 161       | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 157       | 1.52%   |
| Intel HD Graphics 6000                                                                   | 156       | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 151       | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 146       | 1.42%   |
| AMD Renoir                                                                               | 143       | 1.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 132       | 1.28%   |
| Intel HD Graphics 5500                                                                   | 124       | 1.2%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 118       | 1.14%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 115       | 1.12%   |
| Intel HD Graphics 530                                                                    | 111       | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 108       | 1.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 104       | 1.01%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 102       | 0.99%   |
| Intel HD Graphics 630                                                                    | 101       | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 100       | 0.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 96        | 0.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 96        | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 93        | 0.9%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 90        | 0.87%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 85        | 0.82%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 81        | 0.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 77        | 0.75%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 76        | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 75        | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 75        | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 72        | 0.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 71        | 0.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 68        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 4150      | 45.74%  |
| 1 x Nvidia                        | 1637      | 18.04%  |
| 1 x AMD                           | 1531      | 16.87%  |
| Intel + Nvidia                    | 804       | 8.86%   |
| Other                             | 287       | 3.16%   |
| Intel + AMD                       | 169       | 1.86%   |
| 1 x Matrox                        | 132       | 1.45%   |
| 2 x AMD                           | 93        | 1.02%   |
| 1 x ASPEED                        | 92        | 1.01%   |
| AMD + Nvidia                      | 89        | 0.98%   |
| 2 x Nvidia                        | 14        | 0.15%   |
| Nvidia + ASPEED                   | 13        | 0.14%   |
| 1 x VIA                           | 11        | 0.12%   |
| 1 x SiS                           | 9         | 0.1%    |
| AMD + ASPEED                      | 8         | 0.09%   |
| 2 x Intel                         | 6         | 0.07%   |
| Nvidia + Matrox                   | 6         | 0.07%   |
| Intel + 2 x Nvidia                | 5         | 0.06%   |
| 1 x Zhaoxin                       | 4         | 0.04%   |
| AMD + Matrox                      | 3         | 0.03%   |
| 1 x S3 Graphics                   | 2         | 0.02%   |
| 3 x AMD                           | 1         | 0.01%   |
| 2 x Nvidia + 1 x ASPEED           | 1         | 0.01%   |
| 2 x Loongson Technology           | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.01%   |
| 1 x Silicon Motion                | 1         | 0.01%   |
| Nvidia + XGI                      | 1         | 0.01%   |
| Nvidia + Huawei Technologies      | 1         | 0.01%   |
| 1 x Neomagic                      | 1         | 0.01%   |
| 1 x Cirrus Logic                  | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6639      | 72.94%  |
| Unknown     | 1508      | 16.57%  |
| Proprietary | 955       | 10.49%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 6354      | 69.3%   |
| 0.01-0.5       | 999       | 10.9%   |
| 1.01-2.0       | 598       | 6.52%   |
| 0.51-1.0       | 408       | 4.45%   |
| 3.01-4.0       | 356       | 3.88%   |
| 7.01-8.0       | 219       | 2.39%   |
| 5.01-6.0       | 124       | 1.35%   |
| 8.01-16.0      | 51        | 0.56%   |
| 2.01-3.0       | 44        | 0.48%   |
| 16.01-24.0     | 12        | 0.13%   |
| 4.01-5.0       | 2         | 0.02%   |
| More than 64.0 | 1         | 0.01%   |
| 24.01-32.0     | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1016      | 12.1%   |
| Samsung Electronics     | 896       | 10.67%  |
| BOE                     | 689       | 8.21%   |
| Apple                   | 681       | 8.11%   |
| LG Display              | 633       | 7.54%   |
| Chimei Innolux          | 581       | 6.92%   |
| Dell                    | 504       | 6%      |
| Goldstar                | 382       | 4.55%   |
| Hewlett-Packard         | 264       | 3.14%   |
| Acer                    | 228       | 2.72%   |
| BenQ                    | 227       | 2.7%    |
| Philips                 | 200       | 2.38%   |
| AOC                     | 193       | 2.3%    |
| Lenovo                  | 168       | 2%      |
| Ancor Communications    | 158       | 1.88%   |
| Sharp                   | 114       | 1.36%   |
| Iiyama                  | 113       | 1.35%   |
| ViewSonic               | 95        | 1.13%   |
| Chi Mei Optoelectronics | 92        | 1.1%    |
| Unknown                 | 82        | 0.98%   |
| InfoVision              | 81        | 0.96%   |
| PANDA                   | 55        | 0.65%   |
| ASUSTek Computer        | 55        | 0.65%   |
| Eizo                    | 53        | 0.63%   |
| Sony                    | 47        | 0.56%   |
| HannStar                | 42        | 0.5%    |
| NEC Computers           | 40        | 0.48%   |
| LG Electronics          | 39        | 0.46%   |
| LG Philips              | 31        | 0.37%   |
| CSO                     | 28        | 0.33%   |
| Panasonic               | 20        | 0.24%   |
| MSI                     | 19        | 0.23%   |
| Fujitsu Siemens         | 19        | 0.23%   |
| Medion                  | 17        | 0.2%    |
| Vizio                   | 16        | 0.19%   |
| Vestel Elektronik       | 16        | 0.19%   |
| CPT                     | 16        | 0.19%   |
| Unknown                 | 15        | 0.18%   |
| Toshiba                 | 14        | 0.17%   |
| Hitachi                 | 12        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                   | 210       | 2.43%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                 | 189       | 2.18%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch         | 112       | 1.29%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                   | 52        | 0.6%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 46        | 0.53%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 44        | 0.51%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch          | 43        | 0.5%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 42        | 0.49%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                   | 41        | 0.47%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 38        | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 38        | 0.44%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                   | 37        | 0.43%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                   | 29        | 0.33%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                   | 28        | 0.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 27        | 0.31%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch          | 26        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 25        | 0.29%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch        | 24        | 0.28%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch              | 23        | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 23        | 0.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 22        | 0.25%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                   | 22        | 0.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 20        | 0.23%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 19        | 0.22%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 19        | 0.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 17        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 17        | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 17        | 0.2%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 17        | 0.2%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 16        | 0.18%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                  | 16        | 0.18%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch          | 16        | 0.18%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 16        | 0.18%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 15        | 0.17%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 15        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 15        | 0.17%   |
| Unknown                                                                | 15        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 14        | 0.16%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 14        | 0.16%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 14        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3252      | 40.25%  |
| 1366x768 (WXGA)    | 1419      | 17.56%  |
| 1280x800 (WXGA)    | 573       | 7.09%   |
| 3840x2160 (4K)     | 437       | 5.41%   |
| 2560x1440 (QHD)    | 329       | 4.07%   |
| 1280x1024 (SXGA)   | 322       | 3.99%   |
| 1600x900 (HD+)     | 276       | 3.42%   |
| 1920x1200 (WUXGA)  | 225       | 2.78%   |
| 1440x900 (WXGA+)   | 220       | 2.72%   |
| 1680x1050 (WSXGA+) | 195       | 2.41%   |
| Unknown            | 104       | 1.29%   |
| 2560x1080          | 78        | 0.97%   |
| 1024x600           | 68        | 0.84%   |
| 3440x1440          | 59        | 0.73%   |
| 1024x768 (XGA)     | 54        | 0.67%   |
| 1360x768           | 52        | 0.64%   |
| 2288x1287          | 48        | 0.59%   |
| 2560x1600          | 46        | 0.57%   |
| 3840x1080          | 39        | 0.48%   |
| 1600x1200          | 37        | 0.46%   |
| 3840x2400          | 26        | 0.32%   |
| 1920x540           | 20        | 0.25%   |
| 2880x1800          | 19        | 0.24%   |
| 2160x1440          | 13        | 0.16%   |
| 3200x1800 (QHD+)   | 11        | 0.14%   |
| 1280x720 (HD)      | 11        | 0.14%   |
| 2736x1824          | 9         | 0.11%   |
| 4480x1440          | 8         | 0.1%    |
| 1920x1280          | 8         | 0.1%    |
| 1400x1050          | 8         | 0.1%    |
| 5760x2160          | 6         | 0.07%   |
| 5760x1080          | 6         | 0.07%   |
| 3840x1600          | 6         | 0.07%   |
| 3200x1080          | 6         | 0.07%   |
| 7680x2160          | 5         | 0.06%   |
| 2048x1152          | 5         | 0.06%   |
| 3840x1200          | 4         | 0.05%   |
| 2240x1400          | 4         | 0.05%   |
| 1800x1200          | 4         | 0.05%   |
| 3840x1100          | 3         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1610      | 19.26%  |
| 13      | 1344      | 16.07%  |
| 14      | 673       | 8.05%   |
| 24      | 610       | 7.3%    |
| 27      | 516       | 6.17%   |
| 23      | 494       | 5.91%   |
| 17      | 423       | 5.06%   |
| 21      | 406       | 4.86%   |
| Unknown | 343       | 4.1%    |
| 11      | 287       | 3.43%   |
| 19      | 235       | 2.81%   |
| 12      | 202       | 2.42%   |
| 18      | 159       | 1.9%    |
| 31      | 129       | 1.54%   |
| 22      | 125       | 1.5%    |
| 20      | 110       | 1.32%   |
| 34      | 109       | 1.3%    |
| 10      | 76        | 0.91%   |
| 84      | 52        | 0.62%   |
| 25      | 48        | 0.57%   |
| 142     | 46        | 0.55%   |
| 72      | 41        | 0.49%   |
| 16      | 38        | 0.45%   |
| 54      | 33        | 0.39%   |
| 32      | 33        | 0.39%   |
| 40      | 30        | 0.36%   |
| 26      | 23        | 0.28%   |
| 29      | 19        | 0.23%   |
| 28      | 16        | 0.19%   |
| 52      | 14        | 0.17%   |
| 48      | 10        | 0.12%   |
| 65      | 9         | 0.11%   |
| 46      | 9         | 0.11%   |
| 43      | 9         | 0.11%   |
| 8       | 8         | 0.1%    |
| 39      | 7         | 0.08%   |
| 33      | 7         | 0.08%   |
| 49      | 6         | 0.07%   |
| 37      | 6         | 0.07%   |
| 47      | 5         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2797      | 33.99%  |
| 201-300        | 1519      | 18.46%  |
| 501-600        | 1517      | 18.43%  |
| 401-500        | 875       | 10.63%  |
| 351-400        | 473       | 5.75%   |
| Unknown        | 343       | 4.17%   |
| 601-700        | 236       | 2.87%   |
| 701-800        | 151       | 1.83%   |
| 1001-1500      | 101       | 1.23%   |
| 1501-2000      | 96        | 1.17%   |
| 801-900        | 51        | 0.62%   |
| More than 2000 | 47        | 0.57%   |
| 901-1000       | 13        | 0.16%   |
| 101-200        | 11        | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5314      | 69.7%   |
| 16/10   | 1310      | 17.18%  |
| 5/4     | 300       | 3.93%   |
| Unknown | 284       | 3.73%   |
| 21/9    | 130       | 1.71%   |
| 4/3     | 123       | 1.61%   |
| 3/2     | 71        | 0.93%   |
| 1.00    | 48        | 0.63%   |
| 6/5     | 14        | 0.18%   |
| 32/9    | 10        | 0.13%   |
| 2.65    | 5         | 0.07%   |
| 3.40    | 3         | 0.04%   |
| 3.20    | 3         | 0.04%   |
| 2.00    | 2         | 0.03%   |
| 1.96    | 2         | 0.03%   |
| 0.56    | 2         | 0.03%   |
| 3.73    | 1         | 0.01%   |
| 11/10   | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1592      | 19.21%  |
| 81-90          | 1550      | 18.7%   |
| 201-250        | 1278      | 15.42%  |
| 301-350        | 531       | 6.41%   |
| 71-80          | 471       | 5.68%   |
| 151-200        | 470       | 5.67%   |
| Unknown        | 343       | 4.14%   |
| 351-500        | 306       | 3.69%   |
| 51-60          | 291       | 3.51%   |
| 141-150        | 275       | 3.32%   |
| 251-300        | 269       | 3.25%   |
| 121-130        | 231       | 2.79%   |
| More than 1000 | 220       | 2.65%   |
| 61-70          | 185       | 2.23%   |
| 501-1000       | 85        | 1.03%   |
| 41-50          | 75        | 0.91%   |
| 131-140        | 45        | 0.54%   |
| 111-120        | 36        | 0.43%   |
| 91-100         | 23        | 0.28%   |
| 1-40           | 11        | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2460      | 30.52%  |
| 121-160       | 2228      | 27.64%  |
| 101-120       | 2166      | 26.87%  |
| 161-240       | 544       | 6.75%   |
| Unknown       | 344       | 4.27%   |
| 1-50          | 189       | 2.34%   |
| More than 240 | 129       | 1.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 6211      | 67.48%  |
| 0     | 1668      | 18.12%  |
| 2     | 1188      | 12.91%  |
| 3     | 131       | 1.42%   |
| 4     | 5         | 0.05%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4287      | 32.7%   |
| Intel                             | 4171      | 31.82%  |
| Qualcomm Atheros                  | 1287      | 9.82%   |
| Broadcom                          | 973       | 7.42%   |
| Nvidia                            | 451       | 3.44%   |
| Broadcom Limited                  | 309       | 2.36%   |
| Marvell Technology Group          | 195       | 1.49%   |
| Ralink Technology                 | 120       | 0.92%   |
| MediaTek                          | 105       | 0.8%    |
| Ralink                            | 97        | 0.74%   |
| TP-Link                           | 96        | 0.73%   |
| ASIX Electronics                  | 81        | 0.62%   |
| Samsung Electronics               | 56        | 0.43%   |
| Dell                              | 43        | 0.33%   |
| Huawei Technologies               | 36        | 0.27%   |
| Lenovo                            | 35        | 0.27%   |
| Microchip Technology              | 34        | 0.26%   |
| Sierra Wireless                   | 33        | 0.25%   |
| Qualcomm Atheros Communications   | 29        | 0.22%   |
| Mellanox Technologies             | 29        | 0.22%   |
| Aquantia                          | 29        | 0.22%   |
| JMicron Technology                | 28        | 0.21%   |
| D-Link System                     | 28        | 0.21%   |
| Xiaomi                            | 26        | 0.2%    |
| Qualcomm                          | 26        | 0.2%    |
| Ericsson Business Mobile Networks | 25        | 0.19%   |
| DisplayLink                       | 24        | 0.18%   |
| Microsoft                         | 21        | 0.16%   |
| ASUSTek Computer                  | 21        | 0.16%   |
| NetGear                           | 20        | 0.15%   |
| D-Link                            | 19        | 0.14%   |
| Hewlett-Packard                   | 17        | 0.13%   |
| VIA Technologies                  | 16        | 0.12%   |
| IBM                               | 15        | 0.11%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.11%   |
| Fibocom                           | 14        | 0.11%   |
| Edimax Technology                 | 14        | 0.11%   |
| American Megatrends               | 13        | 0.1%    |
| Dresden Elektronik                | 12        | 0.09%   |
| 3Com                              | 11        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3019      | 19.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 463       | 3.02%   |
| Nvidia MCP79 Ethernet                                             | 372       | 2.43%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 366       | 2.39%   |
| Intel Wi-Fi 6 AX200                                               | 296       | 1.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 295       | 1.92%   |
| Intel Wi-Fi 6 AX201                                               | 286       | 1.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 237       | 1.55%   |
| Intel Wireless 8265 / 8275                                        | 231       | 1.51%   |
| Intel Wireless 7260                                               | 226       | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 217       | 1.42%   |
| Intel Wireless 7265                                               | 201       | 1.31%   |
| Intel I211 Gigabit Network Connection                             | 193       | 1.26%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 166       | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 160       | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 158       | 1.03%   |
| Intel Ethernet Connection (13) I219-V                             | 143       | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 142       | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 136       | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 136       | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 134       | 0.87%   |
| Intel Wireless 8260                                               | 125       | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 122       | 0.8%    |
| Intel Wireless 3165                                               | 121       | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 121       | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 117       | 0.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 107       | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 107       | 0.7%    |
| Intel I210 Gigabit Network Connection                             | 105       | 0.68%   |
| Intel Ethernet Connection (2) I219-V                              | 100       | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 96        | 0.63%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 91        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 86        | 0.56%   |
| Intel 82579V Gigabit Network Connection                           | 86        | 0.56%   |
| Intel Wireless-AC 9260                                            | 85        | 0.55%   |
| Intel Ethernet Controller I225-V                                  | 81        | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 80        | 0.52%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 76        | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 75        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 70        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2938      | 46.06%  |
| Qualcomm Atheros                      | 1047      | 16.41%  |
| Realtek Semiconductor                 | 823       | 12.9%   |
| Broadcom                              | 677       | 10.61%  |
| Broadcom Limited                      | 234       | 3.67%   |
| Ralink Technology                     | 120       | 1.88%   |
| Ralink                                | 97        | 1.52%   |
| MediaTek                              | 95        | 1.49%   |
| TP-Link                               | 71        | 1.11%   |
| Sierra Wireless                       | 33        | 0.52%   |
| Qualcomm Atheros Communications       | 29        | 0.45%   |
| Dell                                  | 24        | 0.38%   |
| ASUSTek Computer                      | 21        | 0.33%   |
| NetGear                               | 20        | 0.31%   |
| D-Link                                | 17        | 0.27%   |
| D-Link System                         | 16        | 0.25%   |
| Marvell Technology Group              | 14        | 0.22%   |
| Fibocom                               | 14        | 0.22%   |
| Edimax Technology                     | 14        | 0.22%   |
| Microsoft                             | 13        | 0.2%    |
| Qualcomm                              | 10        | 0.16%   |
| Belkin Components                     | 9         | 0.14%   |
| IMC Networks                          | 5         | 0.08%   |
| Gemtek                                | 5         | 0.08%   |
| Wilocity                              | 4         | 0.06%   |
| Linksys                               | 4         | 0.06%   |
| Hewlett-Packard                       | 3         | 0.05%   |
| Quectel Wireless Solutions            | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| AVM                                   | 2         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.03%   |
| 3Com                                  | 2         | 0.03%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| ZyDAS                                 | 1         | 0.02%   |
| Z-Com                                 | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| TRENDnet                              | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| PLANEX                                | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 366       | 5.71%   |
| Intel Wi-Fi 6 AX200                                                                   | 296       | 4.62%   |
| Intel Wi-Fi 6 AX201                                                                   | 286       | 4.46%   |
| Intel Wireless 8265 / 8275                                                            | 231       | 3.6%    |
| Intel Wireless 7260                                                                   | 226       | 3.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 217       | 3.38%   |
| Intel Wireless 7265                                                                   | 201       | 3.13%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 166       | 2.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 158       | 2.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 142       | 2.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 136       | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 136       | 2.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 134       | 2.09%   |
| Intel Wireless 8260                                                                   | 125       | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 122       | 1.9%    |
| Intel Wireless 3165                                                                   | 121       | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 121       | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 117       | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 107       | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 107       | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 91        | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 86        | 1.34%   |
| Intel Wireless-AC 9260                                                                | 85        | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 80        | 1.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 76        | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 66        | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 63        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 60        | 0.94%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 60        | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 58        | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 51        | 0.8%    |
| Intel Wireless 3160                                                                   | 48        | 0.75%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 45        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 44        | 0.69%   |
| Ralink MT7601U Wireless Adapter                                                       | 44        | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 42        | 0.66%   |
| Intel Centrino Ultimate-N 6300                                                        | 42        | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 41        | 0.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 41        | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 41        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3960      | 46.92%  |
| Intel                             | 2422      | 28.7%   |
| Nvidia                            | 451       | 5.34%   |
| Qualcomm Atheros                  | 364       | 4.31%   |
| Broadcom                          | 356       | 4.22%   |
| Marvell Technology Group          | 182       | 2.16%   |
| ASIX Electronics                  | 81        | 0.96%   |
| Broadcom Limited                  | 78        | 0.92%   |
| Samsung Electronics               | 56        | 0.66%   |
| Lenovo                            | 35        | 0.41%   |
| Microchip Technology              | 33        | 0.39%   |
| Aquantia                          | 29        | 0.34%   |
| JMicron Technology                | 28        | 0.33%   |
| Xiaomi                            | 26        | 0.31%   |
| TP-Link                           | 25        | 0.3%    |
| Mellanox Technologies             | 25        | 0.3%    |
| Huawei Technologies               | 25        | 0.3%    |
| DisplayLink                       | 24        | 0.28%   |
| VIA Technologies                  | 16        | 0.19%   |
| IBM                               | 15        | 0.18%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.17%   |
| Qualcomm                          | 14        | 0.17%   |
| American Megatrends               | 13        | 0.15%   |
| D-Link System                     | 12        | 0.14%   |
| ICS Advent                        | 10        | 0.12%   |
| OPPO Electronics                  | 9         | 0.11%   |
| MediaTek                          | 9         | 0.11%   |
| 3Com                              | 9         | 0.11%   |
| Motorola PCS                      | 8         | 0.09%   |
| Microsoft                         | 8         | 0.09%   |
| Cypress Semiconductor             | 8         | 0.09%   |
| Standard Microsystems             | 6         | 0.07%   |
| Hewlett-Packard                   | 6         | 0.07%   |
| Attansic Technology               | 6         | 0.07%   |
| Apple                             | 6         | 0.07%   |
| Sundance Technology Inc / IC Plus | 5         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.05%   |
| Spreadtrum Communications         | 4         | 0.05%   |
| QLogic                            | 4         | 0.05%   |
| NetXen Incorporated               | 4         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3019      | 34.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 463       | 5.32%   |
| Nvidia MCP79 Ethernet                                             | 372       | 4.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 295       | 3.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 237       | 2.72%   |
| Intel I211 Gigabit Network Connection                             | 193       | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 160       | 1.84%   |
| Intel Ethernet Connection (13) I219-V                             | 143       | 1.64%   |
| Intel I210 Gigabit Network Connection                             | 105       | 1.21%   |
| Intel Ethernet Connection (2) I219-V                              | 100       | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 96        | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 86        | 0.99%   |
| Intel Ethernet Controller I225-V                                  | 81        | 0.93%   |
| Intel 82574L Gigabit Network Connection                           | 75        | 0.86%   |
| Intel Ethernet Connection (4) I219-V                              | 70        | 0.8%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 65        | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 64        | 0.73%   |
| Intel I350 Gigabit Network Connection                             | 64        | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 64        | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                     | 61        | 0.7%    |
| Intel Ethernet Connection (6) I219-V                              | 60        | 0.69%   |
| Intel Ethernet Connection I218-LM                                 | 59        | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 58        | 0.67%   |
| Intel Ethernet Connection (7) I219-V                              | 57        | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 55        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 54        | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 53        | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 47        | 0.54%   |
| Intel Ethernet Connection (14) I219-V                             | 45        | 0.52%   |
| Nvidia MCP61 Ethernet                                             | 44        | 0.51%   |
| Intel 82577LM Gigabit Network Connection                          | 42        | 0.48%   |
| Intel Ethernet Connection (10) I219-V                             | 41        | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 39        | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 36        | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 35        | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 35        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 35        | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 33        | 0.38%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 33        | 0.38%   |
| Intel 82567LM Gigabit Network Connection                          | 33        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7827      | 55.31%  |
| WiFi     | 6115      | 43.22%  |
| Modem    | 189       | 1.34%   |
| Unknown  | 19        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4732      | 52.18%  |
| WiFi     | 4337      | 47.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4703      | 51.96%  |
| 1     | 3555      | 39.28%  |
| 0     | 354       | 3.91%   |
| 3     | 259       | 2.86%   |
| 4     | 104       | 1.15%   |
| 6     | 29        | 0.32%   |
| 5     | 22        | 0.24%   |
| 8     | 12        | 0.13%   |
| 7     | 3         | 0.03%   |
| 20    | 2         | 0.02%   |
| 10    | 2         | 0.02%   |
| 9     | 2         | 0.02%   |
| 21    | 1         | 0.01%   |
| 14    | 1         | 0.01%   |
| 13    | 1         | 0.01%   |
| 12    | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 7715      | 84.41%  |
| Yes     | 1424      | 15.58%  |
| Unknown | 1         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2376      | 46.64%  |
| Apple                           | 694       | 13.62%  |
| Realtek Semiconductor           | 402       | 7.89%   |
| Qualcomm Atheros Communications | 381       | 7.48%   |
| Cambridge Silicon Radio         | 246       | 4.83%   |
| Broadcom                        | 235       | 4.61%   |
| IMC Networks                    | 163       | 3.2%    |
| Lite-On Technology              | 143       | 2.81%   |
| Foxconn / Hon Hai               | 102       | 2%      |
| ASUSTek Computer                | 90        | 1.77%   |
| Dell                            | 63        | 1.24%   |
| Hewlett-Packard                 | 45        | 0.88%   |
| Realtek                         | 24        | 0.47%   |
| Toshiba                         | 23        | 0.45%   |
| MediaTek                        | 22        | 0.43%   |
| Ralink                          | 19        | 0.37%   |
| Foxconn International           | 9         | 0.18%   |
| TP-Link                         | 6         | 0.12%   |
| Alps Electric                   | 6         | 0.12%   |
| Ralink Technology               | 5         | 0.1%    |
| Marvell Semiconductor           | 5         | 0.1%    |
| Edimax Technology               | 4         | 0.08%   |
| Belkin Components               | 4         | 0.08%   |
| Taiyo Yuden                     | 3         | 0.06%   |
| USI                             | 2         | 0.04%   |
| Qcom                            | 2         | 0.04%   |
| Micro Star International        | 2         | 0.04%   |
| Integrated System Solution      | 2         | 0.04%   |
| Fujitsu                         | 2         | 0.04%   |
| Chicony Electronics             | 2         | 0.04%   |
| Unknown                         | 2         | 0.04%   |
| Unknown                         | 1         | 0.02%   |
| Smart Modular Technologies      | 1         | 0.02%   |
| Sitecom Europe                  | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Microsoft                       | 1         | 0.02%   |
| Kensington                      | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Com One                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 900       | 17.65%  |
| Intel AX201 Bluetooth                               | 502       | 9.84%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 370       | 7.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 332       | 6.51%   |
| Intel AX200 Bluetooth                               | 285       | 5.59%   |
| Realtek Bluetooth Radio                             | 251       | 4.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 246       | 4.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 213       | 4.18%   |
| Apple Bluetooth USB Host Controller                 | 175       | 3.43%   |
| Realtek  Bluetooth 4.2 Adapter                      | 96        | 1.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 84        | 1.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 80        | 1.57%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 79        | 1.55%   |
| Intel Bluetooth Device                              | 61        | 1.2%    |
| Apple Bluetooth Host Controller                     | 56        | 1.1%    |
| Intel AX210 Bluetooth                               | 53        | 1.04%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 52        | 1.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 49        | 0.96%   |
| IMC Networks Bluetooth Radio                        | 49        | 0.96%   |
| IMC Networks Bluetooth Device                       | 47        | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 45        | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 41        | 0.8%    |
| Lite-On Bluetooth Device                            | 39        | 0.76%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 0.76%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 38        | 0.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 35        | 0.69%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 34        | 0.67%   |
| Foxconn / Hon Hai Bluetooth Device                  | 34        | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 32        | 0.63%   |
| Foxconn / Hon Hai Wireless_Device                   | 29        | 0.57%   |
| IMC Networks Wireless_Device                        | 26        | 0.51%   |
| Realtek Bluetooth Radio                             | 24        | 0.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 24        | 0.47%   |
| Realtek RTL8723B Bluetooth                          | 22        | 0.43%   |
| Lite-On Atheros AR3012 Bluetooth                    | 22        | 0.43%   |
| MediaTek Wireless_Device                            | 21        | 0.41%   |
| Dell DW375 Bluetooth Module                         | 21        | 0.41%   |
| HP Broadcom 2070 Bluetooth Combo                    | 20        | 0.39%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.37%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 18        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 6106      | 54.71%  |
| AMD                                          | 2020      | 18.1%   |
| Nvidia                                       | 1972      | 17.67%  |
| C-Media Electronics                          | 158       | 1.42%   |
| Logitech                                     | 86        | 0.77%   |
| Creative Labs                                | 56        | 0.5%    |
| Texas Instruments                            | 46        | 0.41%   |
| ASUSTek Computer                             | 39        | 0.35%   |
| Lenovo                                       | 37        | 0.33%   |
| Realtek Semiconductor                        | 36        | 0.32%   |
| GN Netcom                                    | 36        | 0.32%   |
| Plantronics                                  | 33        | 0.3%    |
| Generalplus Technology                       | 32        | 0.29%   |
| JMTek                                        | 26        | 0.23%   |
| Creative Technology                          | 25        | 0.22%   |
| Focusrite-Novation                           | 24        | 0.22%   |
| VIA Technologies                             | 20        | 0.18%   |
| Kingston Technology                          | 20        | 0.18%   |
| Dell                                         | 17        | 0.15%   |
| Micro Star International                     | 16        | 0.14%   |
| Silicon Integrated Systems [SiS]             | 15        | 0.13%   |
| KTMicro                                      | 15        | 0.13%   |
| Hewlett-Packard                              | 15        | 0.13%   |
| RODE Microphones                             | 13        | 0.12%   |
| BEHRINGER International                      | 13        | 0.12%   |
| SteelSeries ApS                              | 12        | 0.11%   |
| Razer USA                                    | 12        | 0.11%   |
| Microsoft                                    | 11        | 0.1%    |
| GYROCOM C&C                                  | 10        | 0.09%   |
| Corsair                                      | 10        | 0.09%   |
| Blue Microphones                             | 10        | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 9         | 0.08%   |
| Sennheiser Communications                    | 9         | 0.08%   |
| Yamaha                                       | 7         | 0.06%   |
| M-Audio                                      | 7         | 0.06%   |
| Tenx Technology                              | 6         | 0.05%   |
| Cambridge Silicon Radio                      | 6         | 0.05%   |
| XMOS                                         | 5         | 0.04%   |
| Samsung Electronics                          | 5         | 0.04%   |
| Samson Technologies                          | 5         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 617       | 4.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 605       | 4.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 503       | 3.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 489       | 3.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 408       | 3.09%   |
| Nvidia MCP79 High Definition Audio                                                                | 375       | 2.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 363       | 2.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 351       | 2.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 331       | 2.51%   |
| Intel Broadwell-U Audio Controller                                                                | 296       | 2.24%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 292       | 2.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 291       | 2.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 286       | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 266       | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 264       | 2%      |
| Intel Cannon Lake PCH cAVS                                                                        | 249       | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 214       | 1.62%   |
| Intel 200 Series PCH HD Audio                                                                     | 195       | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 188       | 1.42%   |
| AMD FCH Azalia Controller                                                                         | 184       | 1.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 180       | 1.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 180       | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 175       | 1.33%   |
| Intel 8 Series HD Audio Controller                                                                | 175       | 1.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 164       | 1.24%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 163       | 1.23%   |
| Intel Comet Lake PCH cAVS                                                                         | 151       | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 150       | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 147       | 1.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 137       | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 136       | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 134       | 1.02%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 126       | 0.95%   |
| AMD Kabini HDMI/DP Audio                                                                          | 119       | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 113       | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 102       | 0.77%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 97        | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 91        | 0.69%   |
| Nvidia High Definition Audio Controller                                                           | 82        | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 82        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1757      | 21.11%  |
| SK hynix            | 1638      | 19.68%  |
| Kingston            | 968       | 11.63%  |
| Unknown             | 887       | 10.65%  |
| Micron Technology   | 676       | 8.12%   |
| Crucial             | 621       | 7.46%   |
| Corsair             | 331       | 3.98%   |
| G.Skill             | 237       | 2.85%   |
| Elpida              | 155       | 1.86%   |
| A-DATA Technology   | 143       | 1.72%   |
| Ramaxel Technology  | 111       | 1.33%   |
| Patriot             | 85        | 1.02%   |
| Unknown (ABCD)      | 78        | 0.94%   |
| Nanya Technology    | 74        | 0.89%   |
| Unknown             | 49        | 0.59%   |
| Smart               | 48        | 0.58%   |
| Team                | 44        | 0.53%   |
| Transcend           | 38        | 0.46%   |
| GOODRAM             | 31        | 0.37%   |
| AMD                 | 28        | 0.34%   |
| Hikvision           | 21        | 0.25%   |
| Hewlett-Packard     | 19        | 0.23%   |
| Apacer              | 19        | 0.23%   |
| Teikon              | 13        | 0.16%   |
| Qimonda             | 12        | 0.14%   |
| 48spaces            | 12        | 0.14%   |
| Silicon Power       | 11        | 0.13%   |
| Timetec             | 9         | 0.11%   |
| PNY                 | 9         | 0.11%   |
| GeIL                | 8         | 0.1%    |
| ASint Technology    | 8         | 0.1%    |
| Wilk                | 6         | 0.07%   |
| Smart Brazil        | 6         | 0.07%   |
| Goldkey             | 6         | 0.07%   |
| Avant               | 6         | 0.07%   |
| Infineon            | 5         | 0.06%   |
| Unifosa             | 4         | 0.05%   |
| Toshiba             | 4         | 0.05%   |
| Neo Forza           | 4         | 0.05%   |
| Kllisre             | 4         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 264       | 2.95%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 154       | 1.72%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 0.76%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 68        | 0.76%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 0.7%    |
| Unknown                                                          | 49        | 0.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 48        | 0.54%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 46        | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 45        | 0.5%    |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 42        | 0.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 42        | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 41        | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 41        | 0.46%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 41        | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 40        | 0.45%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 39        | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 37        | 0.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 37        | 0.41%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 36        | 0.4%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 36        | 0.4%    |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s            | 36        | 0.4%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 35        | 0.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 34        | 0.38%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 33        | 0.37%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 32        | 0.36%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 31        | 0.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 31        | 0.35%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s            | 31        | 0.35%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.32%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.32%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s           | 29        | 0.32%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 28        | 0.31%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 28        | 0.31%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 27        | 0.3%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 27        | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 26        | 0.29%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.29%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.28%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 25        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 3115      | 42.31%  |
| DDR3         | 2473      | 33.59%  |
| DDR2         | 774       | 10.51%  |
| SDRAM        | 241       | 3.27%   |
| Unknown      | 238       | 3.23%   |
| LPDDR4       | 218       | 2.96%   |
| LPDDR3       | 147       | 2%      |
| DDR          | 74        | 1.01%   |
| DDR5         | 45        | 0.61%   |
| LPDDR5       | 20        | 0.27%   |
| DRAM         | 15        | 0.2%    |
| RAM          | 1         | 0.01%   |
| DDR2 FB-DIMM | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 4072      | 55.58%  |
| DIMM         | 2823      | 38.53%  |
| Row Of Chips | 337       | 4.6%    |
| Unknown      | 41        | 0.56%   |
| Chip         | 35        | 0.48%   |
| FB-DIMM      | 14        | 0.19%   |
| RIMM         | 5         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 2578      | 32.4%   |
| 4096    | 1984      | 24.93%  |
| 2048    | 1217      | 15.29%  |
| 16384   | 1055      | 13.26%  |
| 1024    | 714       | 8.97%   |
| 32768   | 293       | 3.68%   |
| 512     | 77        | 0.97%   |
| 256     | 22        | 0.28%   |
| 65536   | 7         | 0.09%   |
| 1536    | 4         | 0.05%   |
| 128     | 4         | 0.05%   |
| 384     | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1657      | 20.97%  |
| 3200    | 1017      | 12.87%  |
| 2667    | 1017      | 12.87%  |
| 1333    | 549       | 6.95%   |
| 800     | 547       | 6.92%   |
| 2400    | 513       | 6.49%   |
| 2133    | 381       | 4.82%   |
| 667     | 280       | 3.54%   |
| Unknown | 220       | 2.78%   |
| 1334    | 182       | 2.3%    |
| 3600    | 156       | 1.97%   |
| 1867    | 117       | 1.48%   |
| 2666    | 92        | 1.16%   |
| 1067    | 92        | 1.16%   |
| 1866    | 89        | 1.13%   |
| 1066    | 78        | 0.99%   |
| 4267    | 74        | 0.94%   |
| 3266    | 64        | 0.81%   |
| 3400    | 57        | 0.72%   |
| 2933    | 55        | 0.7%    |
| 3000    | 47        | 0.59%   |
| 4800    | 40        | 0.51%   |
| 3733    | 40        | 0.51%   |
| 533     | 40        | 0.51%   |
| 3466    | 35        | 0.44%   |
| 4199    | 34        | 0.43%   |
| 2048    | 30        | 0.38%   |
| 400     | 29        | 0.37%   |
| 2866    | 27        | 0.34%   |
| 6400    | 23        | 0.29%   |
| 1800    | 22        | 0.28%   |
| 3800    | 21        | 0.27%   |
| 975     | 19        | 0.24%   |
| 8400    | 17        | 0.22%   |
| 333     | 17        | 0.22%   |
| 4266    | 14        | 0.18%   |
| 3866    | 14        | 0.18%   |
| 266     | 13        | 0.16%   |
| 3666    | 10        | 0.13%   |
| 3534    | 10        | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 59        | 30.89%  |
| Brother Industries     | 36        | 18.85%  |
| Canon                  | 23        | 12.04%  |
| Samsung Electronics    | 15        | 7.85%   |
| Seiko Epson            | 10        | 5.24%   |
| Xerox                  | 8         | 4.19%   |
| Dymo-CoStar            | 6         | 3.14%   |
| Prolific Technology    | 5         | 2.62%   |
| Zebra                  | 4         | 2.09%   |
| Kyocera                | 4         | 2.09%   |
| Pantum                 | 3         | 1.57%   |
| Lexmark International  | 3         | 1.57%   |
| STMicroelectronics     | 2         | 1.05%   |
| QinHeng Electronics    | 2         | 1.05%   |
| Datamax-O'Neil         | 2         | 1.05%   |
| Xiaomi                 | 1         | 0.52%   |
| Ricoh                  | 1         | 0.52%   |
| Printer                | 1         | 0.52%   |
| Panasonic (Matsushita) | 1         | 0.52%   |
| Oki Data               | 1         | 0.52%   |
| Konica Minolta         | 1         | 0.52%   |
| GODEX INTERNATIONAL    | 1         | 0.52%   |
| Dell                   | 1         | 0.52%   |
| Apple                  | 1         | 0.52%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 7         | 3.63%   |
| HP LaserJet 1020                                          | 7         | 3.63%   |
| Prolific PL2305 Parallel Port                             | 5         | 2.59%   |
| HP LaserJet 1200                                          | 4         | 2.07%   |
| HP DeskJet 2130 series                                    | 4         | 2.07%   |
| Samsung ML-1660 Series                                    | 3         | 1.55%   |
| HP LaserJet M101-M106                                     | 3         | 1.55%   |
| Canon PIXMA MG3600 Series                                 | 3         | 1.55%   |
| Brother HL-52x0 series                                    | 3         | 1.55%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.04%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.04%   |
| QinHeng CH340S                                            | 2         | 1.04%   |
| Pantum P2500W series                                      | 2         | 1.04%   |
| Lexmark International CS417dn                             | 2         | 1.04%   |
| HP LaserJet Pro M404-M405                                 | 2         | 1.04%   |
| HP LaserJet P1005                                         | 2         | 1.04%   |
| HP LaserJet M14-M17                                       | 2         | 1.04%   |
| HP LaserJet 400 M401a                                     | 2         | 1.04%   |
| HP LaserJet 1150                                          | 2         | 1.04%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.04%   |
| HP ENVY 4520 series                                       | 2         | 1.04%   |
| HP DeskJet Plus 4100 series                               | 2         | 1.04%   |
| HP DeskJet 2600 series                                    | 2         | 1.04%   |
| Dymo-CoStar LabelWriter 450                               | 2         | 1.04%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 2         | 1.04%   |
| Datamax-O'Neil Datamax E-4304                             | 2         | 1.04%   |
| Canon PIXMA MX920 Series                                  | 2         | 1.04%   |
| Canon MF4410                                              | 2         | 1.04%   |
| Canon LiDE 400                                            | 2         | 1.04%   |
| Canon G3010 series                                        | 2         | 1.04%   |
| Brother PT-9500PC                                         | 2         | 1.04%   |
| Brother Printer                                           | 2         | 1.04%   |
| Brother MFC-L2710DW series                                | 2         | 1.04%   |
| Brother HL-L2395DW series                                 | 2         | 1.04%   |
| Brother HL-3040CN series                                  | 2         | 1.04%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 1         | 0.52%   |
| Zebra ZTC ZD420-203dpi ZPL                                | 1         | 0.52%   |
| Zebra ZTC S4M-200dpi ZPL                                  | 1         | 0.52%   |
| Zebra Printer                                             | 1         | 0.52%   |
| Xiaomi MiMouse 2                                          | 1         | 0.52%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 30        | 56.6%   |
| Seiko Epson        | 12        | 22.64%  |
| Hewlett-Packard    | 6         | 11.32%  |
| Mustek Systems     | 2         | 3.77%   |
| AGFA-Gevaert NV    | 2         | 3.77%   |
| Ultima Electronics | 1         | 1.89%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 8         | 15.09%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 6         | 11.32%  |
| Canon CanoScan LiDE 220                                                               | 4         | 7.55%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 3.77%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 3.77%   |
| Canon CanoScan LIDE 25                                                                | 2         | 3.77%   |
| Canon CanoScan LiDE 210                                                               | 2         | 3.77%   |
| Canon CanoScan LiDE 120                                                               | 2         | 3.77%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2         | 3.77%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 1.89%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 1.89%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 1.89%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1         | 1.89%   |
| Seiko Epson GT-9800F [Perfection 3200]                                                | 1         | 1.89%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 1.89%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 1.89%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1         | 1.89%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 1.89%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1         | 1.89%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 1         | 1.89%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 1.89%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1         | 1.89%   |
| HP ScanJet Pro 2500 f1                                                                | 1         | 1.89%   |
| HP ScanJet 82x0C                                                                      | 1         | 1.89%   |
| HP ScanJet 7650                                                                       | 1         | 1.89%   |
| HP ScanJet 3970c                                                                      | 1         | 1.89%   |
| HP Scanjet 300                                                                        | 1         | 1.89%   |
| HP Scanjet 200                                                                        | 1         | 1.89%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1         | 1.89%   |
| Canon CanoScan 9000F Mark II                                                          | 1         | 1.89%   |
| Canon CanoScan 8800F                                                                  | 1         | 1.89%   |
| Canon CanoScan 5600F                                                                  | 1         | 1.89%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 988       | 21.82%  |
| IMC Networks                           | 427       | 9.43%   |
| Microdia                               | 354       | 7.82%   |
| Realtek Semiconductor                  | 318       | 7.02%   |
| Acer                                   | 296       | 6.54%   |
| Logitech                               | 293       | 6.47%   |
| Quanta                                 | 274       | 6.05%   |
| Sunplus Innovation Technology          | 215       | 4.75%   |
| Bison Electronics                      | 181       | 4%      |
| Suyin                                  | 116       | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) | 116       | 2.56%   |
| Apple                                  | 115       | 2.54%   |
| Syntek                                 | 92        | 2.03%   |
| Lite-On Technology                     | 91        | 2.01%   |
| Luxvisions Innotech Limited            | 72        | 1.59%   |
| Silicon Motion                         | 54        | 1.19%   |
| Alcor Micro                            | 50        | 1.1%    |
| Microsoft                              | 38        | 0.84%   |
| Samsung Electronics                    | 36        | 0.8%    |
| Z-Star Microelectronics                | 34        | 0.75%   |
| Lenovo                                 | 32        | 0.71%   |
| Ricoh                                  | 30        | 0.66%   |
| Generalplus Technology                 | 24        | 0.53%   |
| Primax Electronics                     | 18        | 0.4%    |
| Sonix Technology                       | 16        | 0.35%   |
| Creative Technology                    | 16        | 0.35%   |
| Genesys Logic                          | 13        | 0.29%   |
| GEMBIRD                                | 12        | 0.27%   |
| ARC International                      | 12        | 0.27%   |
| Jieli Technology                       | 11        | 0.24%   |
| KYE Systems (Mouse Systems)            | 10        | 0.22%   |
| Importek                               | 10        | 0.22%   |
| ALi                                    | 10        | 0.22%   |
| USB Camera                             | 8         | 0.18%   |
| SunplusIT                              | 8         | 0.18%   |
| MacroSilicon                           | 8         | 0.18%   |
| Cubeternet                             | 7         | 0.15%   |
| Shenzhen Kingcome Optoelectronic       | 6         | 0.13%   |
| Intel                                  | 6         | 0.13%   |
| OmniVision Technologies                | 5         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 294       | 6.39%   |
| Microdia Integrated_Webcam_HD                       | 149       | 3.24%   |
| IMC Networks Integrated Camera                      | 141       | 3.07%   |
| Realtek Integrated_Webcam_HD                        | 122       | 2.65%   |
| Bison Integrated Camera                             | 118       | 2.57%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 96        | 2.09%   |
| Chicony HD WebCam                                   | 78        | 1.7%    |
| Logitech Webcam C270                                | 74        | 1.61%   |
| Sunplus Integrated_Webcam_HD                        | 73        | 1.59%   |
| Bison Integrated 5M Camera                          | 73        | 1.59%   |
| Quanta Lenovo EasyCamera                            | 69        | 1.5%    |
| Acer BisonCam, NB Pro                               | 58        | 1.26%   |
| Acer Integrated Camera                              | 55        | 1.2%    |
| Syntek Integrated Camera                            | 50        | 1.09%   |
| Chicony HP HD Camera                                | 49        | 1.07%   |
| Logitech HD Pro Webcam C920                         | 43        | 0.93%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 43        | 0.93%   |
| Chicony USB2.0 HD UVC WebCam                        | 43        | 0.93%   |
| Chicony Integrated 5M Camera                        | 43        | 0.93%   |
| Quanta HP TrueVision HD Camera                      | 37        | 0.8%    |
| Samsung Galaxy A5 (MTP)                             | 35        | 0.76%   |
| Microdia Integrated Webcam                          | 35        | 0.76%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 35        | 0.76%   |
| Lite-On Integrated Camera                           | 34        | 0.74%   |
| Apple Built-in iSight                               | 33        | 0.72%   |
| Quanta HD User Facing                               | 32        | 0.7%    |
| Acer SunplusIT Integrated Camera                    | 32        | 0.7%    |
| Chicony Integrated Camera (1280x720@30)             | 30        | 0.65%   |
| Acer Lenovo EasyCamera                              | 30        | 0.65%   |
| Quanta HP HD Camera                                 | 29        | 0.63%   |
| Quanta VGA WebCam                                   | 27        | 0.59%   |
| Microdia USB 2.0 Camera                             | 26        | 0.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 26        | 0.57%   |
| Chicony EasyCamera                                  | 26        | 0.57%   |
| Apple FaceTime HD Camera (Built-in)                 | 26        | 0.57%   |
| Logitech C922 Pro Stream Webcam                     | 25        | 0.54%   |
| Chicony HP TrueVision HD Camera                     | 25        | 0.54%   |
| Sunplus HD WebCam                                   | 24        | 0.52%   |
| Realtek USB Camera                                  | 24        | 0.52%   |
| Chicony HD User Facing                              | 23        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 384       | 41.16%  |
| Validity Sensors                   | 262       | 28.08%  |
| Shenzhen Goodix Technology         | 111       | 11.9%   |
| Upek                               | 44        | 4.72%   |
| AuthenTec                          | 44        | 4.72%   |
| Elan Microelectronics              | 43        | 4.61%   |
| LighTuning Technology              | 22        | 2.36%   |
| STMicroelectronics                 | 16        | 1.71%   |
| Samsung Electronics                | 4         | 0.43%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.21%   |
| Microsoft                          | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 222       | 23.79%  |
| Shenzhen Goodix  FingerPrint Device                                        | 62        | 6.65%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 56        | 6%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 52        | 5.57%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 45        | 4.82%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 40        | 4.29%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 32        | 3.43%   |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 3.22%   |
| Elan ELAN:Fingerprint                                                      | 26        | 2.79%   |
| Validity Sensors Synaptics WBDI                                            | 25        | 2.68%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 22        | 2.36%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 19        | 2.04%   |
| Shenzhen Goodix FingerPrint                                                | 19        | 2.04%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 18        | 1.93%   |
| AuthenTec AES2810                                                          | 18        | 1.93%   |
| Synaptics  WBDI                                                            | 16        | 1.71%   |
| Elan ELAN:ARM-M4                                                           | 16        | 1.71%   |
| Synaptics WBDI                                                             | 15        | 1.61%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 15        | 1.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 1.5%    |
| STMicroelectronics Fingerprint Reader                                      | 14        | 1.5%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.5%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.5%    |
| Validity Sensors VFS491                                                    | 12        | 1.29%   |
| Synaptics UWP WBDI                                                         | 11        | 1.18%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.07%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 1.07%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 0.96%   |
| Validity Sensors VFS Fingerprint sensor                                    | 9         | 0.96%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 0.64%   |
| Synaptics UWP WBDI Device                                                  | 6         | 0.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.64%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 0.54%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 0.54%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.43%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.43%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.43%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.43%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 0.32%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 153       | 34.93%  |
| Alcor Micro                | 152       | 34.7%   |
| O2 Micro                   | 28        | 6.39%   |
| Lenovo                     | 28        | 6.39%   |
| Upek                       | 27        | 6.16%   |
| Gemalto (was Gemplus)      | 8         | 1.83%   |
| SCM Microsystems           | 7         | 1.6%    |
| Clay Logic                 | 6         | 1.37%   |
| Yubico.com                 | 5         | 1.14%   |
| Cherry                     | 4         | 0.91%   |
| Aladdin Knowledge Systems  | 4         | 0.91%   |
| Advanced Card Systems      | 4         | 0.91%   |
| Realtek Semiconductor      | 3         | 0.68%   |
| Reiner SCT Kartensysteme   | 2         | 0.46%   |
| Chicony Electronics        | 2         | 0.46%   |
| OmniKey                    | 1         | 0.23%   |
| Hewlett-Packard            | 1         | 0.23%   |
| Feitian Technologies       | 1         | 0.23%   |
| C3PO                       | 1         | 0.23%   |
| Athena Smartcard Solutions | 1         | 0.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 148       | 33.79%  |
| Broadcom BCM5880 Secure Applications Processor                               | 48        | 10.96%  |
| Broadcom 58200                                                               | 40        | 9.13%   |
| Broadcom 5880                                                                | 37        | 8.45%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 27        | 6.16%   |
| Lenovo Integrated Smart Card Reader                                          | 27        | 6.16%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 26        | 5.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 5.48%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 1.14%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 4         | 0.91%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 0.91%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 0.91%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 0.91%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 3         | 0.68%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.68%   |
| Clay Logic Nitrokey Start                                                    | 3         | 0.68%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.68%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.46%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.46%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.46%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 0.46%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.46%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.46%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.46%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.23%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.23%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.23%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.23%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.23%   |
| OmniKey CardMan 4321                                                         | 1         | 0.23%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.23%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.23%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.23%   |
| Feitian Technologies SCR301                                                  | 1         | 0.23%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.23%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                   | 1         | 0.23%   |
| C3PO LTC31v2                                                                 | 1         | 0.23%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5562      | 60.62%  |
| 1     | 2835      | 30.9%   |
| 2     | 612       | 6.67%   |
| 3     | 128       | 1.4%    |
| 4     | 24        | 0.26%   |
| 5     | 9         | 0.1%    |
| 6     | 3         | 0.03%   |
| 7     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1689      | 39.11%  |
| Fingerprint reader       | 929       | 21.51%  |
| Chipcard                 | 383       | 8.87%   |
| Net/wireless             | 355       | 8.22%   |
| Multimedia controller    | 296       | 6.85%   |
| Communication controller | 174       | 4.03%   |
| Unassigned class         | 106       | 2.45%   |
| Bluetooth                | 77        | 1.78%   |
| Camera                   | 68        | 1.57%   |
| Sound                    | 52        | 1.2%    |
| Card reader              | 51        | 1.18%   |
| Storage                  | 40        | 0.93%   |
| Net/ethernet             | 37        | 0.86%   |
| Network                  | 18        | 0.42%   |
| Modem                    | 11        | 0.25%   |
| Storage/raid             | 8         | 0.19%   |
| Storage/ide              | 7         | 0.16%   |
| Flash memory             | 5         | 0.12%   |
| Tv card                  | 4         | 0.09%   |
| Dvb card                 | 4         | 0.09%   |
| Firewire controller      | 3         | 0.07%   |
| Wireless                 | 1         | 0.02%   |
| Storage/ata              | 1         | 0.02%   |

