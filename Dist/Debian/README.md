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

Total: 17860

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite C55-C             | Notebook    | [256b476a15](https://linux-hardware.org/?probe=256b476a15) | Dec 24, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [9eff3f535e](https://linux-hardware.org/?probe=9eff3f535e) | Dec 24, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [d698ea94f5](https://linux-hardware.org/?probe=d698ea94f5) | Dec 24, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [bfe0870fab](https://linux-hardware.org/?probe=bfe0870fab) | Dec 24, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [d6c1f0d202](https://linux-hardware.org/?probe=d6c1f0d202) | Dec 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ee7b7ce7cc](https://linux-hardware.org/?probe=ee7b7ce7cc) | Dec 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [43718a5746](https://linux-hardware.org/?probe=43718a5746) | Dec 24, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [f76e4b41dc](https://linux-hardware.org/?probe=f76e4b41dc) | Dec 24, 2023 |
| Toshiba       | Satellite A205              | Notebook    | [c3680bfd29](https://linux-hardware.org/?probe=c3680bfd29) | Dec 24, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [27124f064a](https://linux-hardware.org/?probe=27124f064a) | Dec 24, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [e12710e5bd](https://linux-hardware.org/?probe=e12710e5bd) | Dec 24, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [1fe8e8f18d](https://linux-hardware.org/?probe=1fe8e8f18d) | Dec 24, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [381955efac](https://linux-hardware.org/?probe=381955efac) | Dec 24, 2023 |
| HP            | Pavilion g7                 | Notebook    | [bbe3fb1914](https://linux-hardware.org/?probe=bbe3fb1914) | Dec 24, 2023 |
| HP            | 1998                        | Desktop     | [c2e72e513c](https://linux-hardware.org/?probe=c2e72e513c) | Dec 23, 2023 |
| IBM           | ThinkPad R50e 1842QDU       | Notebook    | [32a349ab97](https://linux-hardware.org/?probe=32a349ab97) | Dec 23, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | Notebook    | [c2681f33cc](https://linux-hardware.org/?probe=c2681f33cc) | Dec 23, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ba4e48312e](https://linux-hardware.org/?probe=ba4e48312e) | Dec 23, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [fe6c638acc](https://linux-hardware.org/?probe=fe6c638acc) | Dec 23, 2023 |
| Intel         | S5000PSL                    | Server      | [4abb5e39fc](https://linux-hardware.org/?probe=4abb5e39fc) | Dec 23, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [e91530e41d](https://linux-hardware.org/?probe=e91530e41d) | Dec 23, 2023 |
| HP            | ProBook 655 G2              | Notebook    | [033325e722](https://linux-hardware.org/?probe=033325e722) | Dec 23, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [58bbd67a73](https://linux-hardware.org/?probe=58bbd67a73) | Dec 23, 2023 |
| AVITA         | NS14A6                      | Notebook    | [adf732b1b6](https://linux-hardware.org/?probe=adf732b1b6) | Dec 23, 2023 |
| T-bao Tian... | GOD78                       | Desktop     | [cd28753d06](https://linux-hardware.org/?probe=cd28753d06) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [8753b04999](https://linux-hardware.org/?probe=8753b04999) | Dec 23, 2023 |
| eMachines     | EMCP61M                     | Desktop     | [d464b480dd](https://linux-hardware.org/?probe=d464b480dd) | Dec 23, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [6c9e82db47](https://linux-hardware.org/?probe=6c9e82db47) | Dec 23, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [4d38d67af1](https://linux-hardware.org/?probe=4d38d67af1) | Dec 23, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [bbd50ba27b](https://linux-hardware.org/?probe=bbd50ba27b) | Dec 23, 2023 |
| Intel         | NUC10i3FNB M38070-308       | Mini pc     | [006c2edbad](https://linux-hardware.org/?probe=006c2edbad) | Dec 22, 2023 |
| Google        | Reks                        | Notebook    | [52375a57c5](https://linux-hardware.org/?probe=52375a57c5) | Dec 22, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [5e8dc79e2c](https://linux-hardware.org/?probe=5e8dc79e2c) | Dec 22, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a11f0a948c](https://linux-hardware.org/?probe=a11f0a948c) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [f71924e3e4](https://linux-hardware.org/?probe=f71924e3e4) | Dec 22, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [1310ad15a9](https://linux-hardware.org/?probe=1310ad15a9) | Dec 22, 2023 |
| Irbis         | NB264                       | Notebook    | [8821679765](https://linux-hardware.org/?probe=8821679765) | Dec 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [5d41a0e0d5](https://linux-hardware.org/?probe=5d41a0e0d5) | Dec 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [ad67aeb103](https://linux-hardware.org/?probe=ad67aeb103) | Dec 22, 2023 |
| HP            | ENVY 15                     | Notebook    | [2997ffe5cf](https://linux-hardware.org/?probe=2997ffe5cf) | Dec 22, 2023 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [c6cefd749d](https://linux-hardware.org/?probe=c6cefd749d) | Dec 22, 2023 |
| MSI           | B75A-G43                    | Desktop     | [70c44f3ff8](https://linux-hardware.org/?probe=70c44f3ff8) | Dec 22, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dfc1d4289e](https://linux-hardware.org/?probe=dfc1d4289e) | Dec 22, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [cdff1cf322](https://linux-hardware.org/?probe=cdff1cf322) | Dec 22, 2023 |
| ASUSTek       | B150-PRO D3                 | Desktop     | [a686071950](https://linux-hardware.org/?probe=a686071950) | Dec 22, 2023 |
| HP            | ENVY Notebook               | Notebook    | [ca2e6f9061](https://linux-hardware.org/?probe=ca2e6f9061) | Dec 22, 2023 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [26743f9015](https://linux-hardware.org/?probe=26743f9015) | Dec 22, 2023 |
| Gigabyte      | MZ72-HB0-00 01020102        | Server      | [771f7edd98](https://linux-hardware.org/?probe=771f7edd98) | Dec 22, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [3256f09051](https://linux-hardware.org/?probe=3256f09051) | Dec 22, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [aa3d919a29](https://linux-hardware.org/?probe=aa3d919a29) | Dec 22, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [1c225a853e](https://linux-hardware.org/?probe=1c225a853e) | Dec 21, 2023 |
| Lenovo        | ThinkPad T490 20N3S5GP12    | Notebook    | [093906d110](https://linux-hardware.org/?probe=093906d110) | Dec 21, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [82304c2a5f](https://linux-hardware.org/?probe=82304c2a5f) | Dec 21, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [2e9f8a97e5](https://linux-hardware.org/?probe=2e9f8a97e5) | Dec 21, 2023 |
| Google        | Reks                        | Notebook    | [9a6f15c5d9](https://linux-hardware.org/?probe=9a6f15c5d9) | Dec 21, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [b87a575222](https://linux-hardware.org/?probe=b87a575222) | Dec 21, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [22b9c27eb8](https://linux-hardware.org/?probe=22b9c27eb8) | Dec 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a102e5839d](https://linux-hardware.org/?probe=a102e5839d) | Dec 21, 2023 |
| sunxi         | Unknown                     | Soc         | [07307d0820](https://linux-hardware.org/?probe=07307d0820) | Dec 21, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [4b020f53e1](https://linux-hardware.org/?probe=4b020f53e1) | Dec 21, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [d41c926291](https://linux-hardware.org/?probe=d41c926291) | Dec 21, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [3a065e8d32](https://linux-hardware.org/?probe=3a065e8d32) | Dec 21, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [edc5223b9b](https://linux-hardware.org/?probe=edc5223b9b) | Dec 21, 2023 |
| AZW           | EQ                          | Desktop     | [11b8a012c0](https://linux-hardware.org/?probe=11b8a012c0) | Dec 21, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [47d1d26375](https://linux-hardware.org/?probe=47d1d26375) | Dec 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [1c3113c9b9](https://linux-hardware.org/?probe=1c3113c9b9) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d5f60126bb](https://linux-hardware.org/?probe=d5f60126bb) | Dec 20, 2023 |
| HP            | 3396                        | Desktop     | [d0d084ecc8](https://linux-hardware.org/?probe=d0d084ecc8) | Dec 20, 2023 |
| Cisco Syst... | UCSC-C220-M4S 74-12419-0... | Server      | [80f235148b](https://linux-hardware.org/?probe=80f235148b) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [2464a532b8](https://linux-hardware.org/?probe=2464a532b8) | Dec 20, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [2c968508ee](https://linux-hardware.org/?probe=2c968508ee) | Dec 20, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [25a077d35e](https://linux-hardware.org/?probe=25a077d35e) | Dec 20, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [2785a8b9c6](https://linux-hardware.org/?probe=2785a8b9c6) | Dec 20, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [74136911a0](https://linux-hardware.org/?probe=74136911a0) | Dec 20, 2023 |
| ASUSTek       | V6-P5G31E                   | Desktop     | [83a8408a7e](https://linux-hardware.org/?probe=83a8408a7e) | Dec 20, 2023 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [4b6f645ef6](https://linux-hardware.org/?probe=4b6f645ef6) | Dec 20, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [ef17f12758](https://linux-hardware.org/?probe=ef17f12758) | Dec 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [32f0587c3f](https://linux-hardware.org/?probe=32f0587c3f) | Dec 20, 2023 |
| HP            | ENVY m6                     | Notebook    | [237331a1ba](https://linux-hardware.org/?probe=237331a1ba) | Dec 20, 2023 |
| Dynabook      | CS40L-HB                    | Notebook    | [da68e155cd](https://linux-hardware.org/?probe=da68e155cd) | Dec 20, 2023 |
| Clevo         | W240BU                      | Notebook    | [a0d883bb3d](https://linux-hardware.org/?probe=a0d883bb3d) | Dec 20, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [54ed87ec87](https://linux-hardware.org/?probe=54ed87ec87) | Dec 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [2ff77e3571](https://linux-hardware.org/?probe=2ff77e3571) | Dec 20, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a641f9b41d](https://linux-hardware.org/?probe=a641f9b41d) | Dec 20, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [8e678ffb8c](https://linux-hardware.org/?probe=8e678ffb8c) | Dec 20, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [b6b4165e86](https://linux-hardware.org/?probe=b6b4165e86) | Dec 20, 2023 |
| Cisco Syst... | UCSC-C220-M4S 74-12419-0... | Server      | [ccb072d03a](https://linux-hardware.org/?probe=ccb072d03a) | Dec 20, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fecbe03785](https://linux-hardware.org/?probe=fecbe03785) | Dec 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3eead324a8](https://linux-hardware.org/?probe=3eead324a8) | Dec 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [85233c464d](https://linux-hardware.org/?probe=85233c464d) | Dec 19, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [ca0eab5d48](https://linux-hardware.org/?probe=ca0eab5d48) | Dec 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [acebee7435](https://linux-hardware.org/?probe=acebee7435) | Dec 19, 2023 |
| Unknown       | Unknown                     | Other       | [92d87c0e52](https://linux-hardware.org/?probe=92d87c0e52) | Dec 19, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [9b8d8ec134](https://linux-hardware.org/?probe=9b8d8ec134) | Dec 19, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [7fe77a3476](https://linux-hardware.org/?probe=7fe77a3476) | Dec 19, 2023 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [65b6d3dcc0](https://linux-hardware.org/?probe=65b6d3dcc0) | Dec 19, 2023 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [ab5bffcf0a](https://linux-hardware.org/?probe=ab5bffcf0a) | Dec 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [9f3471e435](https://linux-hardware.org/?probe=9f3471e435) | Dec 19, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [752a59a0cc](https://linux-hardware.org/?probe=752a59a0cc) | Dec 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [bff7dced45](https://linux-hardware.org/?probe=bff7dced45) | Dec 19, 2023 |
| Dell          | G7 7790                     | Notebook    | [bcc6b4046b](https://linux-hardware.org/?probe=bcc6b4046b) | Dec 19, 2023 |
| Lenovo        | IdeaPadFlex 4-1570 80SB     | Convertible | [c55227422a](https://linux-hardware.org/?probe=c55227422a) | Dec 19, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [61211b72bb](https://linux-hardware.org/?probe=61211b72bb) | Dec 19, 2023 |
| DellInc.      | Venue 8 Pro 5830            | Notebook    | [d6408a26a1](https://linux-hardware.org/?probe=d6408a26a1) | Dec 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [993b9536cf](https://linux-hardware.org/?probe=993b9536cf) | Dec 19, 2023 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [782dad2128](https://linux-hardware.org/?probe=782dad2128) | Dec 19, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [619bbec719](https://linux-hardware.org/?probe=619bbec719) | Dec 19, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [6a962e40ec](https://linux-hardware.org/?probe=6a962e40ec) | Dec 19, 2023 |
| Acer          | Aspire AV15-52              | Notebook    | [daf4aa326d](https://linux-hardware.org/?probe=daf4aa326d) | Dec 19, 2023 |
| Biostar       | A55MH                       | Desktop     | [f1106ef8c7](https://linux-hardware.org/?probe=f1106ef8c7) | Dec 19, 2023 |
| MSI           | B450M BAZOOKA               | Desktop     | [0bfcb5be94](https://linux-hardware.org/?probe=0bfcb5be94) | Dec 19, 2023 |
| ASUSTek       | ROG STRIX B560-E GAMING ... | Desktop     | [fd9a0ec0c4](https://linux-hardware.org/?probe=fd9a0ec0c4) | Dec 19, 2023 |
| MSI           | Pulse 17 B13VGK             | Notebook    | [71d0660568](https://linux-hardware.org/?probe=71d0660568) | Dec 18, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [e94e9e0fd9](https://linux-hardware.org/?probe=e94e9e0fd9) | Dec 18, 2023 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [020e3af833](https://linux-hardware.org/?probe=020e3af833) | Dec 18, 2023 |
| Gigabyte      | AORUS 17H BXF               | Notebook    | [ad8b646e5c](https://linux-hardware.org/?probe=ad8b646e5c) | Dec 18, 2023 |
| HP            | 2B45                        | All in one  | [dbc7094ab4](https://linux-hardware.org/?probe=dbc7094ab4) | Dec 18, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [baf5b47a47](https://linux-hardware.org/?probe=baf5b47a47) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [f47c731a09](https://linux-hardware.org/?probe=f47c731a09) | Dec 18, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [229df442f5](https://linux-hardware.org/?probe=229df442f5) | Dec 18, 2023 |
| HP            | 1998                        | Desktop     | [1d45f9958a](https://linux-hardware.org/?probe=1d45f9958a) | Dec 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [95d29a0474](https://linux-hardware.org/?probe=95d29a0474) | Dec 18, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [5a5f20e49a](https://linux-hardware.org/?probe=5a5f20e49a) | Dec 18, 2023 |
| Dell          | 072T6D A05                  | Server      | [70a0b85bf3](https://linux-hardware.org/?probe=70a0b85bf3) | Dec 18, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [dd9d263269](https://linux-hardware.org/?probe=dd9d263269) | Dec 18, 2023 |
| Dell          | 072T6D A05                  | Server      | [b9942f8526](https://linux-hardware.org/?probe=b9942f8526) | Dec 18, 2023 |
| Unknown       | Unknown                     | Soc         | [86edce9654](https://linux-hardware.org/?probe=86edce9654) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5fae29f23f](https://linux-hardware.org/?probe=5fae29f23f) | Dec 18, 2023 |
| Gigabyte      | H510M H V2                  | Desktop     | [3228539880](https://linux-hardware.org/?probe=3228539880) | Dec 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [3764b249f4](https://linux-hardware.org/?probe=3764b249f4) | Dec 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ec4da8d1a3](https://linux-hardware.org/?probe=ec4da8d1a3) | Dec 18, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [f46bf3981f](https://linux-hardware.org/?probe=f46bf3981f) | Dec 18, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [1293ea8b65](https://linux-hardware.org/?probe=1293ea8b65) | Dec 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [81187bebc0](https://linux-hardware.org/?probe=81187bebc0) | Dec 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [709891824c](https://linux-hardware.org/?probe=709891824c) | Dec 18, 2023 |
| MSI           | Vector GP77 13VG            | Notebook    | [7b6b5a14f8](https://linux-hardware.org/?probe=7b6b5a14f8) | Dec 18, 2023 |
| MSI           | A75MA-G55                   | Desktop     | [6af3c61744](https://linux-hardware.org/?probe=6af3c61744) | Dec 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [94757e986e](https://linux-hardware.org/?probe=94757e986e) | Dec 18, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [9133031c56](https://linux-hardware.org/?probe=9133031c56) | Dec 18, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [2eb95b1a7c](https://linux-hardware.org/?probe=2eb95b1a7c) | Dec 18, 2023 |
| Unknown       | Unknown                     | Soc         | [86e857365e](https://linux-hardware.org/?probe=86e857365e) | Dec 18, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [79c73e5927](https://linux-hardware.org/?probe=79c73e5927) | Dec 17, 2023 |
| Panasonic     | FZ-M1CCA17E3                | Notebook    | [87024c17b5](https://linux-hardware.org/?probe=87024c17b5) | Dec 17, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [bb37946b48](https://linux-hardware.org/?probe=bb37946b48) | Dec 17, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [fd17674af7](https://linux-hardware.org/?probe=fd17674af7) | Dec 17, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [a4753bb26d](https://linux-hardware.org/?probe=a4753bb26d) | Dec 17, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [af666cc67d](https://linux-hardware.org/?probe=af666cc67d) | Dec 17, 2023 |
| Panasonic     | FZ-M1CCA17E3                | Notebook    | [8f2a76eb09](https://linux-hardware.org/?probe=8f2a76eb09) | Dec 17, 2023 |
| Medion        | BEAST X30                   | Notebook    | [cec06735ba](https://linux-hardware.org/?probe=cec06735ba) | Dec 17, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b61d950623](https://linux-hardware.org/?probe=b61d950623) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [d38e1077ae](https://linux-hardware.org/?probe=d38e1077ae) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0134ee9104](https://linux-hardware.org/?probe=0134ee9104) | Dec 17, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [9d204d6a41](https://linux-hardware.org/?probe=9d204d6a41) | Dec 17, 2023 |
| MSI           | Vector GP77 13VG            | Notebook    | [267679e074](https://linux-hardware.org/?probe=267679e074) | Dec 17, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [058c14cd39](https://linux-hardware.org/?probe=058c14cd39) | Dec 17, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [7ff498fc83](https://linux-hardware.org/?probe=7ff498fc83) | Dec 17, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [b6b44f1b80](https://linux-hardware.org/?probe=b6b44f1b80) | Dec 17, 2023 |
| HP            | Compaq 6730s                | Notebook    | [628e8cf362](https://linux-hardware.org/?probe=628e8cf362) | Dec 17, 2023 |
| ASUSTek       | P4P800-VM                   | Desktop     | [8fb6faae11](https://linux-hardware.org/?probe=8fb6faae11) | Dec 17, 2023 |
| HP            | Compaq 6730s                | Notebook    | [774f3d4feb](https://linux-hardware.org/?probe=774f3d4feb) | Dec 17, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [b9738c48b0](https://linux-hardware.org/?probe=b9738c48b0) | Dec 17, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [02e1fcae39](https://linux-hardware.org/?probe=02e1fcae39) | Dec 17, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [c878de7adb](https://linux-hardware.org/?probe=c878de7adb) | Dec 17, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [ad7f762f22](https://linux-hardware.org/?probe=ad7f762f22) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b212e62ef7](https://linux-hardware.org/?probe=b212e62ef7) | Dec 17, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [720421dab6](https://linux-hardware.org/?probe=720421dab6) | Dec 17, 2023 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [90024d365b](https://linux-hardware.org/?probe=90024d365b) | Dec 17, 2023 |
| Samsung       | 760XDA                      | Notebook    | [53ab21d486](https://linux-hardware.org/?probe=53ab21d486) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [e0fa989ed0](https://linux-hardware.org/?probe=e0fa989ed0) | Dec 17, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [a155267edc](https://linux-hardware.org/?probe=a155267edc) | Dec 17, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4d81e6300c](https://linux-hardware.org/?probe=4d81e6300c) | Dec 17, 2023 |
| Alienware     | m18 R1                      | Notebook    | [a136406723](https://linux-hardware.org/?probe=a136406723) | Dec 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5059d80ef9](https://linux-hardware.org/?probe=5059d80ef9) | Dec 16, 2023 |
| HP            | 829A                        | Mini pc     | [e0b2d004a0](https://linux-hardware.org/?probe=e0b2d004a0) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [7162b25b98](https://linux-hardware.org/?probe=7162b25b98) | Dec 16, 2023 |
| ASUSTek       | Pro WS W680M-ACE SE         | Desktop     | [f1b9ec56ea](https://linux-hardware.org/?probe=f1b9ec56ea) | Dec 16, 2023 |
| PC Special... | N150CU                      | Notebook    | [92a4f7a5a4](https://linux-hardware.org/?probe=92a4f7a5a4) | Dec 16, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [0aa5382212](https://linux-hardware.org/?probe=0aa5382212) | Dec 16, 2023 |
| PC Special... | N150CU                      | Notebook    | [07686d110e](https://linux-hardware.org/?probe=07686d110e) | Dec 16, 2023 |
| FriendlyEl... | NanoPC-T6                   | Soc         | [e4c855bedc](https://linux-hardware.org/?probe=e4c855bedc) | Dec 16, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [5f19b6ce4f](https://linux-hardware.org/?probe=5f19b6ce4f) | Dec 16, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e8847d53ec](https://linux-hardware.org/?probe=e8847d53ec) | Dec 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [314b3b98d7](https://linux-hardware.org/?probe=314b3b98d7) | Dec 16, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [ca117be9d4](https://linux-hardware.org/?probe=ca117be9d4) | Dec 16, 2023 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | Desktop     | [6f4f0f65bb](https://linux-hardware.org/?probe=6f4f0f65bb) | Dec 15, 2023 |
| Lenovo        | ThinkPad P1 20MDS02BGE      | Notebook    | [65eb962233](https://linux-hardware.org/?probe=65eb962233) | Dec 15, 2023 |
| Dell          | 0M5WNK A02                  | Desktop     | [f47a8fcf1f](https://linux-hardware.org/?probe=f47a8fcf1f) | Dec 15, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [ec4a48125c](https://linux-hardware.org/?probe=ec4a48125c) | Dec 15, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [d43271b873](https://linux-hardware.org/?probe=d43271b873) | Dec 15, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [a785d6574b](https://linux-hardware.org/?probe=a785d6574b) | Dec 15, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [98e30b12f1](https://linux-hardware.org/?probe=98e30b12f1) | Dec 15, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [a8677e8420](https://linux-hardware.org/?probe=a8677e8420) | Dec 15, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [059918d809](https://linux-hardware.org/?probe=059918d809) | Dec 15, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [969d4fd521](https://linux-hardware.org/?probe=969d4fd521) | Dec 15, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [a80537094f](https://linux-hardware.org/?probe=a80537094f) | Dec 15, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [06ed7608bf](https://linux-hardware.org/?probe=06ed7608bf) | Dec 15, 2023 |
| Biostar       | A32M2                       | Desktop     | [f3fb9d0673](https://linux-hardware.org/?probe=f3fb9d0673) | Dec 15, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [ef9cf1d767](https://linux-hardware.org/?probe=ef9cf1d767) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [b4bcda5523](https://linux-hardware.org/?probe=b4bcda5523) | Dec 15, 2023 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [e0e94706d7](https://linux-hardware.org/?probe=e0e94706d7) | Dec 15, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [46178ea298](https://linux-hardware.org/?probe=46178ea298) | Dec 14, 2023 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [0305f80c2d](https://linux-hardware.org/?probe=0305f80c2d) | Dec 14, 2023 |
| Gigabyte      | P35-DS4                     | Desktop     | [23e146afdc](https://linux-hardware.org/?probe=23e146afdc) | Dec 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [69e37f3d93](https://linux-hardware.org/?probe=69e37f3d93) | Dec 14, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [dfa5dc9cd9](https://linux-hardware.org/?probe=dfa5dc9cd9) | Dec 14, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [de24d459c5](https://linux-hardware.org/?probe=de24d459c5) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [09a184f2e4](https://linux-hardware.org/?probe=09a184f2e4) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7232... | Notebook    | [d9de3edb6b](https://linux-hardware.org/?probe=d9de3edb6b) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7232... | Notebook    | [84f162f88f](https://linux-hardware.org/?probe=84f162f88f) | Dec 14, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [67a32f0dd0](https://linux-hardware.org/?probe=67a32f0dd0) | Dec 14, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [283dc2dab5](https://linux-hardware.org/?probe=283dc2dab5) | Dec 14, 2023 |
| HP            | 8463                        | Desktop     | [0d01616e1c](https://linux-hardware.org/?probe=0d01616e1c) | Dec 14, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [545a3cecbc](https://linux-hardware.org/?probe=545a3cecbc) | Dec 14, 2023 |
| Sony          | VPCEG18FG                   | Notebook    | [3cf20aa9ea](https://linux-hardware.org/?probe=3cf20aa9ea) | Dec 14, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [f1860954b3](https://linux-hardware.org/?probe=f1860954b3) | Dec 14, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [1ed13ea8f2](https://linux-hardware.org/?probe=1ed13ea8f2) | Dec 14, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [eafb9ad287](https://linux-hardware.org/?probe=eafb9ad287) | Dec 14, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [3504153caa](https://linux-hardware.org/?probe=3504153caa) | Dec 14, 2023 |
| Lenovo        | IdeaPadFlex 5-1470 81C9     | Convertible | [8e1afeddd0](https://linux-hardware.org/?probe=8e1afeddd0) | Dec 14, 2023 |
| HP            | ProBook 4540s               | Notebook    | [24875256cd](https://linux-hardware.org/?probe=24875256cd) | Dec 14, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [83034fb404](https://linux-hardware.org/?probe=83034fb404) | Dec 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [d2b1e67451](https://linux-hardware.org/?probe=d2b1e67451) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [05c8fb1ded](https://linux-hardware.org/?probe=05c8fb1ded) | Dec 13, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [f2efee9279](https://linux-hardware.org/?probe=f2efee9279) | Dec 13, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [0e23ff0a06](https://linux-hardware.org/?probe=0e23ff0a06) | Dec 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c4e3486e91](https://linux-hardware.org/?probe=c4e3486e91) | Dec 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5200cedaa0](https://linux-hardware.org/?probe=5200cedaa0) | Dec 13, 2023 |
| Lenovo        | Flex 2 Pro-15               | Notebook    | [da278da4b6](https://linux-hardware.org/?probe=da278da4b6) | Dec 13, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [1668553525](https://linux-hardware.org/?probe=1668553525) | Dec 13, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [89bef2fed5](https://linux-hardware.org/?probe=89bef2fed5) | Dec 13, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [0ed1d85207](https://linux-hardware.org/?probe=0ed1d85207) | Dec 13, 2023 |
| Acer          | Aspire 1510 Rev.A           | Desktop     | [452be93d1b](https://linux-hardware.org/?probe=452be93d1b) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [68e68f1683](https://linux-hardware.org/?probe=68e68f1683) | Dec 13, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [5fc8de17bb](https://linux-hardware.org/?probe=5fc8de17bb) | Dec 13, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5a65590bed](https://linux-hardware.org/?probe=5a65590bed) | Dec 13, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [e6205fb709](https://linux-hardware.org/?probe=e6205fb709) | Dec 13, 2023 |
| Unknown       | Unknown                     | Soc         | [50c635dba3](https://linux-hardware.org/?probe=50c635dba3) | Dec 13, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [6f5272ea27](https://linux-hardware.org/?probe=6f5272ea27) | Dec 13, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [cfa115323d](https://linux-hardware.org/?probe=cfa115323d) | Dec 13, 2023 |
| HP            | Pavilion g6                 | Notebook    | [920939b6c0](https://linux-hardware.org/?probe=920939b6c0) | Dec 13, 2023 |
| Dell          | Latitude 5424 Rugged        | Notebook    | [ce56e420fc](https://linux-hardware.org/?probe=ce56e420fc) | Dec 13, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [1ac3287ee1](https://linux-hardware.org/?probe=1ac3287ee1) | Dec 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [75bcf5966c](https://linux-hardware.org/?probe=75bcf5966c) | Dec 12, 2023 |
| Unknown       | AMedia X96 Max+             | Soc         | [4df1c17523](https://linux-hardware.org/?probe=4df1c17523) | Dec 12, 2023 |
| Lenovo        | IdeaPadFlex 6-14ARR 81HA    | Convertible | [676e339cc5](https://linux-hardware.org/?probe=676e339cc5) | Dec 12, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [e28730f84d](https://linux-hardware.org/?probe=e28730f84d) | Dec 12, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [f90b33b7d5](https://linux-hardware.org/?probe=f90b33b7d5) | Dec 12, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [97ca767d40](https://linux-hardware.org/?probe=97ca767d40) | Dec 12, 2023 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [1ef755944c](https://linux-hardware.org/?probe=1ef755944c) | Dec 12, 2023 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [e4fcf233c5](https://linux-hardware.org/?probe=e4fcf233c5) | Dec 12, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [774925ed25](https://linux-hardware.org/?probe=774925ed25) | Dec 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | Notebook    | [e99a0bd1db](https://linux-hardware.org/?probe=e99a0bd1db) | Dec 12, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [6b62180e3e](https://linux-hardware.org/?probe=6b62180e3e) | Dec 12, 2023 |
| Intel         | JSL MRD                     | Desktop     | [c811c8be03](https://linux-hardware.org/?probe=c811c8be03) | Dec 12, 2023 |
| Dell          | 0MGK50 A01                  | Desktop     | [7471a7b26e](https://linux-hardware.org/?probe=7471a7b26e) | Dec 12, 2023 |
| Positivo      | H14BT58                     | Notebook    | [74530bb40a](https://linux-hardware.org/?probe=74530bb40a) | Dec 12, 2023 |
| Dell          | 0VD5HY A10                  | Desktop     | [366f1ac830](https://linux-hardware.org/?probe=366f1ac830) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [53ee047174](https://linux-hardware.org/?probe=53ee047174) | Dec 12, 2023 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [a9059220f3](https://linux-hardware.org/?probe=a9059220f3) | Dec 12, 2023 |
| Fujitsu       | JIH61Y3                     | Desktop     | [cb566e2fd0](https://linux-hardware.org/?probe=cb566e2fd0) | Dec 12, 2023 |
| Acer          | Aspire one                  | Notebook    | [fb1f2ccd2e](https://linux-hardware.org/?probe=fb1f2ccd2e) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [756283ec58](https://linux-hardware.org/?probe=756283ec58) | Dec 12, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [4053f6be95](https://linux-hardware.org/?probe=4053f6be95) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [c258c213e6](https://linux-hardware.org/?probe=c258c213e6) | Dec 12, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a4bdf16134](https://linux-hardware.org/?probe=a4bdf16134) | Dec 12, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [1bec383138](https://linux-hardware.org/?probe=1bec383138) | Dec 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [79c6d70468](https://linux-hardware.org/?probe=79c6d70468) | Dec 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [0d7abecf9b](https://linux-hardware.org/?probe=0d7abecf9b) | Dec 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [3dcb225ff4](https://linux-hardware.org/?probe=3dcb225ff4) | Dec 11, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [f5b7104728](https://linux-hardware.org/?probe=f5b7104728) | Dec 11, 2023 |
| HP            | Laptop 14s-dy5xxx           | Notebook    | [bfe021294b](https://linux-hardware.org/?probe=bfe021294b) | Dec 11, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [d5500a3830](https://linux-hardware.org/?probe=d5500a3830) | Dec 11, 2023 |
| Google        | Electro                     | Notebook    | [503645df79](https://linux-hardware.org/?probe=503645df79) | Dec 11, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [88b93b571e](https://linux-hardware.org/?probe=88b93b571e) | Dec 11, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [57a80d9d1b](https://linux-hardware.org/?probe=57a80d9d1b) | Dec 11, 2023 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [29590179a8](https://linux-hardware.org/?probe=29590179a8) | Dec 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [9d7ed9efae](https://linux-hardware.org/?probe=9d7ed9efae) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [2c6a120dd2](https://linux-hardware.org/?probe=2c6a120dd2) | Dec 10, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [4a2deac69b](https://linux-hardware.org/?probe=4a2deac69b) | Dec 10, 2023 |
| Packard Be... | MCP73PV                     | Desktop     | [9d707e64d4](https://linux-hardware.org/?probe=9d707e64d4) | Dec 10, 2023 |
| HP            | 0968h                       | Desktop     | [b1fb94198e](https://linux-hardware.org/?probe=b1fb94198e) | Dec 10, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [201fa157d6](https://linux-hardware.org/?probe=201fa157d6) | Dec 10, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [18f6c41058](https://linux-hardware.org/?probe=18f6c41058) | Dec 10, 2023 |
| Acer          | Aspire Z24-890              | All in one  | [2853098aad](https://linux-hardware.org/?probe=2853098aad) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [324e195003](https://linux-hardware.org/?probe=324e195003) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [f60e90cfd0](https://linux-hardware.org/?probe=f60e90cfd0) | Dec 10, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [25d8aaca3c](https://linux-hardware.org/?probe=25d8aaca3c) | Dec 10, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [bb7ea992e6](https://linux-hardware.org/?probe=bb7ea992e6) | Dec 09, 2023 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [c1d93cb6b2](https://linux-hardware.org/?probe=c1d93cb6b2) | Dec 09, 2023 |
| Lenovo        | ThinkPad T530 242922G       | Notebook    | [2b8062d3cc](https://linux-hardware.org/?probe=2b8062d3cc) | Dec 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [93f24d2411](https://linux-hardware.org/?probe=93f24d2411) | Dec 09, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [b2743fd826](https://linux-hardware.org/?probe=b2743fd826) | Dec 09, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ae61f1039f](https://linux-hardware.org/?probe=ae61f1039f) | Dec 09, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [1435c0e9db](https://linux-hardware.org/?probe=1435c0e9db) | Dec 09, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [c02997fc15](https://linux-hardware.org/?probe=c02997fc15) | Dec 09, 2023 |
| Dell          | Latitude 7490               | Notebook    | [ad002286ac](https://linux-hardware.org/?probe=ad002286ac) | Dec 09, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [9d633902a0](https://linux-hardware.org/?probe=9d633902a0) | Dec 09, 2023 |
| AZW           | MINI S                      | Desktop     | [2512b54e60](https://linux-hardware.org/?probe=2512b54e60) | Dec 09, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [2b1117b052](https://linux-hardware.org/?probe=2b1117b052) | Dec 09, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4106c6dbcf](https://linux-hardware.org/?probe=4106c6dbcf) | Dec 09, 2023 |
| ASUSTek       | X507UB                      | Notebook    | [f1a1ea60e6](https://linux-hardware.org/?probe=f1a1ea60e6) | Dec 09, 2023 |
| Dell          | Precision 3550              | Notebook    | [a3be7ab761](https://linux-hardware.org/?probe=a3be7ab761) | Dec 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [af22ca1731](https://linux-hardware.org/?probe=af22ca1731) | Dec 08, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [647f96ad2c](https://linux-hardware.org/?probe=647f96ad2c) | Dec 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [cc6cd166f2](https://linux-hardware.org/?probe=cc6cd166f2) | Dec 08, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [0257ed619f](https://linux-hardware.org/?probe=0257ed619f) | Dec 08, 2023 |
| Intel         | NUC13SBBi9 M58736-303       | Mini pc     | [0ce9d18c51](https://linux-hardware.org/?probe=0ce9d18c51) | Dec 08, 2023 |
| Toshiba       | Satellite L50-A-19P         | Notebook    | [cd3314169e](https://linux-hardware.org/?probe=cd3314169e) | Dec 08, 2023 |
| HP            | G42                         | Notebook    | [f23e6ffe56](https://linux-hardware.org/?probe=f23e6ffe56) | Dec 08, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [7ca4962c57](https://linux-hardware.org/?probe=7ca4962c57) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [b53080f09f](https://linux-hardware.org/?probe=b53080f09f) | Dec 08, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [67371c6af4](https://linux-hardware.org/?probe=67371c6af4) | Dec 08, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [b008f53987](https://linux-hardware.org/?probe=b008f53987) | Dec 08, 2023 |
| MSI           | G31TM-P35                   | Desktop     | [e241cfaeca](https://linux-hardware.org/?probe=e241cfaeca) | Dec 08, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1502CBA    | Notebook    | [b46d0490b6](https://linux-hardware.org/?probe=b46d0490b6) | Dec 08, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ba71538aed](https://linux-hardware.org/?probe=ba71538aed) | Dec 08, 2023 |
| Hardkernel    | ODROID-M1                   | Soc         | [39d65538cb](https://linux-hardware.org/?probe=39d65538cb) | Dec 08, 2023 |
| Dell          | 0X45NX A01                  | Server      | [b89424543d](https://linux-hardware.org/?probe=b89424543d) | Dec 08, 2023 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | Notebook    | [0e2900b443](https://linux-hardware.org/?probe=0e2900b443) | Dec 08, 2023 |
| MSI           | MEG X399 CREATION           | Desktop     | [02adc5ef8b](https://linux-hardware.org/?probe=02adc5ef8b) | Dec 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS8H800    | Notebook    | [49fbd4df76](https://linux-hardware.org/?probe=49fbd4df76) | Dec 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS8C000    | Notebook    | [bff5eac6db](https://linux-hardware.org/?probe=bff5eac6db) | Dec 08, 2023 |
| Dell          | 0KP561                      | Desktop     | [bd0971e9cc](https://linux-hardware.org/?probe=bd0971e9cc) | Dec 08, 2023 |
| Dell          | 04YP6J A01                  | Desktop     | [186bb25f07](https://linux-hardware.org/?probe=186bb25f07) | Dec 08, 2023 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [1229fd52f5](https://linux-hardware.org/?probe=1229fd52f5) | Dec 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [031fd2298b](https://linux-hardware.org/?probe=031fd2298b) | Dec 07, 2023 |
| HP            | G62                         | Notebook    | [c2f10412aa](https://linux-hardware.org/?probe=c2f10412aa) | Dec 07, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c723bcc62a](https://linux-hardware.org/?probe=c723bcc62a) | Dec 07, 2023 |
| Intel         | JSL MRD                     | Desktop     | [fb3b75c8cc](https://linux-hardware.org/?probe=fb3b75c8cc) | Dec 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e7fabdedad](https://linux-hardware.org/?probe=e7fabdedad) | Dec 07, 2023 |
| HP            | 339A                        | Desktop     | [a114886e67](https://linux-hardware.org/?probe=a114886e67) | Dec 07, 2023 |
| Dell          | 0GVPNP A03                  | Server      | [c618310d44](https://linux-hardware.org/?probe=c618310d44) | Dec 07, 2023 |
| Acer          | Extensa 4210                | Notebook    | [4f8a82394a](https://linux-hardware.org/?probe=4f8a82394a) | Dec 07, 2023 |
| Aquarius      | NS585                       | Notebook    | [b6b0a78cfa](https://linux-hardware.org/?probe=b6b0a78cfa) | Dec 07, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [b1c3e47458](https://linux-hardware.org/?probe=b1c3e47458) | Dec 07, 2023 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [116dce4b93](https://linux-hardware.org/?probe=116dce4b93) | Dec 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [39a966c6da](https://linux-hardware.org/?probe=39a966c6da) | Dec 07, 2023 |
| Dell          | Precision 7550              | Notebook    | [11f63c8ba3](https://linux-hardware.org/?probe=11f63c8ba3) | Dec 07, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [256fbd42a6](https://linux-hardware.org/?probe=256fbd42a6) | Dec 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dcb3b62f73](https://linux-hardware.org/?probe=dcb3b62f73) | Dec 06, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [21b8166e02](https://linux-hardware.org/?probe=21b8166e02) | Dec 06, 2023 |
| Intel         | H61                         | Desktop     | [fbc4dc7436](https://linux-hardware.org/?probe=fbc4dc7436) | Dec 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [b118593b9d](https://linux-hardware.org/?probe=b118593b9d) | Dec 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [600935b467](https://linux-hardware.org/?probe=600935b467) | Dec 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [d4ece1c445](https://linux-hardware.org/?probe=d4ece1c445) | Dec 06, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [523404e018](https://linux-hardware.org/?probe=523404e018) | Dec 06, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b7070058fb](https://linux-hardware.org/?probe=b7070058fb) | Dec 06, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [280a9a93e6](https://linux-hardware.org/?probe=280a9a93e6) | Dec 06, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [d54ba07f49](https://linux-hardware.org/?probe=d54ba07f49) | Dec 06, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [46bc5ee727](https://linux-hardware.org/?probe=46bc5ee727) | Dec 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [b5430476af](https://linux-hardware.org/?probe=b5430476af) | Dec 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [6e61bec2ab](https://linux-hardware.org/?probe=6e61bec2ab) | Dec 06, 2023 |
| HP            | ENVY Notebook               | Notebook    | [26a4295a68](https://linux-hardware.org/?probe=26a4295a68) | Dec 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0cb29ce493](https://linux-hardware.org/?probe=0cb29ce493) | Dec 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6d4537080b](https://linux-hardware.org/?probe=6d4537080b) | Dec 05, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [ce624b95df](https://linux-hardware.org/?probe=ce624b95df) | Dec 05, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [7bd10d1922](https://linux-hardware.org/?probe=7bd10d1922) | Dec 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6e7c9a6ebc](https://linux-hardware.org/?probe=6e7c9a6ebc) | Dec 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [71c469e9dd](https://linux-hardware.org/?probe=71c469e9dd) | Dec 05, 2023 |
| ASUSTek       | P553UJ                      | Notebook    | [e5ed994bf9](https://linux-hardware.org/?probe=e5ed994bf9) | Dec 05, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [68784031ca](https://linux-hardware.org/?probe=68784031ca) | Dec 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [1b39d673f8](https://linux-hardware.org/?probe=1b39d673f8) | Dec 05, 2023 |
| ASUSTek       | ROG Strix G614JU_G614JU     | Notebook    | [68ec81b134](https://linux-hardware.org/?probe=68ec81b134) | Dec 04, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [8132e0caf0](https://linux-hardware.org/?probe=8132e0caf0) | Dec 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [56dab5d412](https://linux-hardware.org/?probe=56dab5d412) | Dec 04, 2023 |
| HP            | Spectre Notebook            | Notebook    | [95b8230b80](https://linux-hardware.org/?probe=95b8230b80) | Dec 04, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [da8437565a](https://linux-hardware.org/?probe=da8437565a) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [de877c77b2](https://linux-hardware.org/?probe=de877c77b2) | Dec 04, 2023 |
| MSI           | Thin GF63 12VE              | Notebook    | [ada68f6d8a](https://linux-hardware.org/?probe=ada68f6d8a) | Dec 04, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [82dedf4be4](https://linux-hardware.org/?probe=82dedf4be4) | Dec 04, 2023 |
| MSI           | GF65 Thin 10SER             | Notebook    | [f382271478](https://linux-hardware.org/?probe=f382271478) | Dec 04, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [03fe12170c](https://linux-hardware.org/?probe=03fe12170c) | Dec 04, 2023 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [969efab4b8](https://linux-hardware.org/?probe=969efab4b8) | Dec 04, 2023 |
| Acer          | Extensa 215-55              | Notebook    | [87616f0d71](https://linux-hardware.org/?probe=87616f0d71) | Dec 04, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [76fdeed52e](https://linux-hardware.org/?probe=76fdeed52e) | Dec 04, 2023 |
| Dell          | 0RN474                      | Desktop     | [17392605bb](https://linux-hardware.org/?probe=17392605bb) | Dec 04, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [fde3c9253f](https://linux-hardware.org/?probe=fde3c9253f) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | Notebook    | [01485bc011](https://linux-hardware.org/?probe=01485bc011) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [23cf3c751a](https://linux-hardware.org/?probe=23cf3c751a) | Dec 04, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [890efb3114](https://linux-hardware.org/?probe=890efb3114) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [22b736c30d](https://linux-hardware.org/?probe=22b736c30d) | Dec 04, 2023 |
| Supermicro    | X8DTU                       | Server      | [d2bc04d563](https://linux-hardware.org/?probe=d2bc04d563) | Dec 04, 2023 |
| Supermicro    | X8DTU                       | Server      | [436a64c8fb](https://linux-hardware.org/?probe=436a64c8fb) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [3f26c37883](https://linux-hardware.org/?probe=3f26c37883) | Dec 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS3L502    | Notebook    | [592eb925fd](https://linux-hardware.org/?probe=592eb925fd) | Dec 04, 2023 |
| HP            | 8619                        | Desktop     | [a33e273f33](https://linux-hardware.org/?probe=a33e273f33) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | Notebook    | [75603d3c20](https://linux-hardware.org/?probe=75603d3c20) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [7afcab06a4](https://linux-hardware.org/?probe=7afcab06a4) | Dec 04, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [961b00cfbe](https://linux-hardware.org/?probe=961b00cfbe) | Dec 04, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [7c16c8b9ac](https://linux-hardware.org/?probe=7c16c8b9ac) | Dec 03, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [830b83bf5c](https://linux-hardware.org/?probe=830b83bf5c) | Dec 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [bbd413d34b](https://linux-hardware.org/?probe=bbd413d34b) | Dec 03, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [83b954a1cd](https://linux-hardware.org/?probe=83b954a1cd) | Dec 03, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [848e0dbd37](https://linux-hardware.org/?probe=848e0dbd37) | Dec 03, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [b8af3ee6d5](https://linux-hardware.org/?probe=b8af3ee6d5) | Dec 03, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [c4e675a705](https://linux-hardware.org/?probe=c4e675a705) | Dec 03, 2023 |
| Acer          | Unknown                     | Notebook    | [6555dd06ac](https://linux-hardware.org/?probe=6555dd06ac) | Dec 03, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [67efae847f](https://linux-hardware.org/?probe=67efae847f) | Dec 03, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [47222bf19c](https://linux-hardware.org/?probe=47222bf19c) | Dec 03, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [5a5296e72f](https://linux-hardware.org/?probe=5a5296e72f) | Dec 03, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2afc97f78a](https://linux-hardware.org/?probe=2afc97f78a) | Dec 03, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [595fc0137d](https://linux-hardware.org/?probe=595fc0137d) | Dec 03, 2023 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [41ef064705](https://linux-hardware.org/?probe=41ef064705) | Dec 03, 2023 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [b14a847625](https://linux-hardware.org/?probe=b14a847625) | Dec 03, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [3c6a13271b](https://linux-hardware.org/?probe=3c6a13271b) | Dec 03, 2023 |
| Dell          | Precision M4800             | Notebook    | [ff01ff15f9](https://linux-hardware.org/?probe=ff01ff15f9) | Dec 03, 2023 |
| Jumper        | EZbook                      | Notebook    | [54cf2bf1d4](https://linux-hardware.org/?probe=54cf2bf1d4) | Dec 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [3222457362](https://linux-hardware.org/?probe=3222457362) | Dec 03, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [a28372598e](https://linux-hardware.org/?probe=a28372598e) | Dec 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [bb1b02ee0c](https://linux-hardware.org/?probe=bb1b02ee0c) | Dec 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [5aeec2e399](https://linux-hardware.org/?probe=5aeec2e399) | Dec 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [89effd522f](https://linux-hardware.org/?probe=89effd522f) | Dec 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2492e6ae2e](https://linux-hardware.org/?probe=2492e6ae2e) | Dec 02, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [a24f117537](https://linux-hardware.org/?probe=a24f117537) | Dec 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [daa56bab51](https://linux-hardware.org/?probe=daa56bab51) | Dec 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [744c430aa7](https://linux-hardware.org/?probe=744c430aa7) | Dec 02, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [1462381824](https://linux-hardware.org/?probe=1462381824) | Dec 02, 2023 |
| HP            | ProLiant DL380 Gen9         | Server      | [c0f6772db1](https://linux-hardware.org/?probe=c0f6772db1) | Dec 02, 2023 |
| Lenovo        | MAHOBAY No DPK              | All in one  | [d97ecb484d](https://linux-hardware.org/?probe=d97ecb484d) | Dec 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0869816e7a](https://linux-hardware.org/?probe=0869816e7a) | Dec 02, 2023 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [99293a328c](https://linux-hardware.org/?probe=99293a328c) | Dec 02, 2023 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [b8e3a992b3](https://linux-hardware.org/?probe=b8e3a992b3) | Dec 02, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [138a63b91b](https://linux-hardware.org/?probe=138a63b91b) | Dec 02, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [f366381075](https://linux-hardware.org/?probe=f366381075) | Dec 02, 2023 |
| Sony          | VPCEB46FX                   | Notebook    | [b331dc017f](https://linux-hardware.org/?probe=b331dc017f) | Dec 02, 2023 |
| Lenovo        | ThinkPad X220 4291OL3       | Notebook    | [d07f89fdd6](https://linux-hardware.org/?probe=d07f89fdd6) | Dec 02, 2023 |
| Gigabyte      | H97M-HD3                    | Desktop     | [aa52a8ceac](https://linux-hardware.org/?probe=aa52a8ceac) | Dec 02, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [73c15b7e61](https://linux-hardware.org/?probe=73c15b7e61) | Dec 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [d0bbc73e29](https://linux-hardware.org/?probe=d0bbc73e29) | Dec 02, 2023 |
| Gigabyte      | H470 HD3                    | Desktop     | [0b9cf3a0a5](https://linux-hardware.org/?probe=0b9cf3a0a5) | Dec 02, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [109cecbcba](https://linux-hardware.org/?probe=109cecbcba) | Dec 01, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3cbadbe556](https://linux-hardware.org/?probe=3cbadbe556) | Dec 01, 2023 |
| Sony          | VPCF11M1E                   | Notebook    | [f185cc14da](https://linux-hardware.org/?probe=f185cc14da) | Dec 01, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [13e072ec20](https://linux-hardware.org/?probe=13e072ec20) | Dec 01, 2023 |
| Dell          | Latitude 7440               | Notebook    | [b4179d70c3](https://linux-hardware.org/?probe=b4179d70c3) | Dec 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [d4a1f56f8d](https://linux-hardware.org/?probe=d4a1f56f8d) | Dec 01, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | Desktop     | [8a625099b1](https://linux-hardware.org/?probe=8a625099b1) | Dec 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [fc30a356f0](https://linux-hardware.org/?probe=fc30a356f0) | Dec 01, 2023 |
| HP            | 212B                        | Desktop     | [dc1382e549](https://linux-hardware.org/?probe=dc1382e549) | Dec 01, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [c4f3b7fec9](https://linux-hardware.org/?probe=c4f3b7fec9) | Dec 01, 2023 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [b0c7a29604](https://linux-hardware.org/?probe=b0c7a29604) | Dec 01, 2023 |
| Toshiba       | Satellite L775              | Notebook    | [da7cc192f7](https://linux-hardware.org/?probe=da7cc192f7) | Dec 01, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [f17a1eb208](https://linux-hardware.org/?probe=f17a1eb208) | Dec 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 4 21H1C... | Notebook    | [7590036270](https://linux-hardware.org/?probe=7590036270) | Dec 01, 2023 |
| Lenovo        | G700 20251                  | Notebook    | [e4e63d5300](https://linux-hardware.org/?probe=e4e63d5300) | Nov 30, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [4ab4cd31f3](https://linux-hardware.org/?probe=4ab4cd31f3) | Nov 30, 2023 |
| MSI           | A78M-E45                    | Desktop     | [fd9a5e65e4](https://linux-hardware.org/?probe=fd9a5e65e4) | Nov 30, 2023 |
| ASUSTek       | P5N-MX                      | Desktop     | [c586157333](https://linux-hardware.org/?probe=c586157333) | Nov 30, 2023 |
| Supermicro    | X11SSL-F                    | Server      | [0ad16d30ae](https://linux-hardware.org/?probe=0ad16d30ae) | Nov 30, 2023 |
| HP            | 8053                        | Desktop     | [a2b9b5d498](https://linux-hardware.org/?probe=a2b9b5d498) | Nov 30, 2023 |
| Supermicro    | X8DTU                       | Server      | [35b42f6bdb](https://linux-hardware.org/?probe=35b42f6bdb) | Nov 30, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [cf7d8fdbf1](https://linux-hardware.org/?probe=cf7d8fdbf1) | Nov 30, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4bac6b7cd5](https://linux-hardware.org/?probe=4bac6b7cd5) | Nov 30, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ede8970ea9](https://linux-hardware.org/?probe=ede8970ea9) | Nov 30, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [a828388299](https://linux-hardware.org/?probe=a828388299) | Nov 30, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [6642e4462f](https://linux-hardware.org/?probe=6642e4462f) | Nov 30, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [2b0642c446](https://linux-hardware.org/?probe=2b0642c446) | Nov 30, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [c7b394b498](https://linux-hardware.org/?probe=c7b394b498) | Nov 30, 2023 |
| Lenovo        | ThinkPad T590 20N5S56P00    | Notebook    | [352fffb7a9](https://linux-hardware.org/?probe=352fffb7a9) | Nov 30, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [38e526321f](https://linux-hardware.org/?probe=38e526321f) | Nov 29, 2023 |
| Dell          | 0PU052                      | Desktop     | [9035e39786](https://linux-hardware.org/?probe=9035e39786) | Nov 29, 2023 |
| Toshiba       | Satellite L455D             | Notebook    | [d08710e3d3](https://linux-hardware.org/?probe=d08710e3d3) | Nov 29, 2023 |
| MACHINIST     | X99 RS9                     | Desktop     | [722f516451](https://linux-hardware.org/?probe=722f516451) | Nov 29, 2023 |
| HP            | 304Ah                       | Desktop     | [03437e0238](https://linux-hardware.org/?probe=03437e0238) | Nov 29, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [01aee620f1](https://linux-hardware.org/?probe=01aee620f1) | Nov 29, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [384fc3c571](https://linux-hardware.org/?probe=384fc3c571) | Nov 29, 2023 |
| HP            | Pavilion dv6                | Notebook    | [ddce26dd72](https://linux-hardware.org/?probe=ddce26dd72) | Nov 29, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [dae10e70d0](https://linux-hardware.org/?probe=dae10e70d0) | Nov 29, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [1b7f8a15dd](https://linux-hardware.org/?probe=1b7f8a15dd) | Nov 29, 2023 |
| Supermicro    | X13SAE-F                    | Server      | [6fa7511431](https://linux-hardware.org/?probe=6fa7511431) | Nov 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d2284172c7](https://linux-hardware.org/?probe=d2284172c7) | Nov 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [4521051e77](https://linux-hardware.org/?probe=4521051e77) | Nov 29, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [6a2c279391](https://linux-hardware.org/?probe=6a2c279391) | Nov 29, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [bf583ba008](https://linux-hardware.org/?probe=bf583ba008) | Nov 29, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5894ef78ae](https://linux-hardware.org/?probe=5894ef78ae) | Nov 29, 2023 |
| Lenovo        | 1048 SDK0J40697 WIN 3305... | Desktop     | [af727ea890](https://linux-hardware.org/?probe=af727ea890) | Nov 29, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [ef2a2ab2a9](https://linux-hardware.org/?probe=ef2a2ab2a9) | Nov 29, 2023 |
| ASUSTek       | M50Vc                       | Notebook    | [0eba431c7a](https://linux-hardware.org/?probe=0eba431c7a) | Nov 29, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [7ff2232073](https://linux-hardware.org/?probe=7ff2232073) | Nov 29, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6865be0fd7](https://linux-hardware.org/?probe=6865be0fd7) | Nov 29, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [414132dc07](https://linux-hardware.org/?probe=414132dc07) | Nov 29, 2023 |
| Lenovo        | ThinkPad T520 4243VU3       | Notebook    | [6cbaf1893d](https://linux-hardware.org/?probe=6cbaf1893d) | Nov 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [66847c493b](https://linux-hardware.org/?probe=66847c493b) | Nov 29, 2023 |
| Dell          | Precision 7560              | Notebook    | [035f0d6f41](https://linux-hardware.org/?probe=035f0d6f41) | Nov 29, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [bb3faeeed7](https://linux-hardware.org/?probe=bb3faeeed7) | Nov 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cf46975c18](https://linux-hardware.org/?probe=cf46975c18) | Nov 28, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [0d6a4cd900](https://linux-hardware.org/?probe=0d6a4cd900) | Nov 28, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [b01d99f799](https://linux-hardware.org/?probe=b01d99f799) | Nov 28, 2023 |
| ASRock        | B365 Phantom Gaming 4       | Desktop     | [b3de42156e](https://linux-hardware.org/?probe=b3de42156e) | Nov 28, 2023 |
| ASRock        | H61DE/S3                    | Desktop     | [50d5c63e0f](https://linux-hardware.org/?probe=50d5c63e0f) | Nov 28, 2023 |
| MSI           | X299 GAMING PRO CARBON      | Desktop     | [07d105a830](https://linux-hardware.org/?probe=07d105a830) | Nov 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [416a759973](https://linux-hardware.org/?probe=416a759973) | Nov 28, 2023 |
| Dell          | 0WCJNT A04                  | Server      | [3adc9b76ee](https://linux-hardware.org/?probe=3adc9b76ee) | Nov 28, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [6b10244910](https://linux-hardware.org/?probe=6b10244910) | Nov 28, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [d24b2b8298](https://linux-hardware.org/?probe=d24b2b8298) | Nov 28, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [413049d0f4](https://linux-hardware.org/?probe=413049d0f4) | Nov 28, 2023 |
| MSI           | Prestige 16Studio A13VF     | Notebook    | [4d8fb7dd05](https://linux-hardware.org/?probe=4d8fb7dd05) | Nov 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [66554ab5d7](https://linux-hardware.org/?probe=66554ab5d7) | Nov 28, 2023 |
| Gigabyte      | H470 HD3                    | Desktop     | [0ecb969c2c](https://linux-hardware.org/?probe=0ecb969c2c) | Nov 28, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [1f87fc5fca](https://linux-hardware.org/?probe=1f87fc5fca) | Nov 28, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [760cc39516](https://linux-hardware.org/?probe=760cc39516) | Nov 27, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [2289ab10b3](https://linux-hardware.org/?probe=2289ab10b3) | Nov 27, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [93d9d89a9a](https://linux-hardware.org/?probe=93d9d89a9a) | Nov 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [3fe11b3243](https://linux-hardware.org/?probe=3fe11b3243) | Nov 27, 2023 |
| Lenovo        | Flex 2 Pro-15               | Notebook    | [7e7f94ca3b](https://linux-hardware.org/?probe=7e7f94ca3b) | Nov 27, 2023 |
| ASUSTek       | F52Q                        | Notebook    | [705aa34dce](https://linux-hardware.org/?probe=705aa34dce) | Nov 27, 2023 |
| ASUSTek       | F52Q                        | Notebook    | [569db41ca1](https://linux-hardware.org/?probe=569db41ca1) | Nov 27, 2023 |
| Daten Tecn... | DCM3A-4                     | Notebook    | [66b8d06d48](https://linux-hardware.org/?probe=66b8d06d48) | Nov 27, 2023 |
| HP            | 895F                        | All in one  | [9322fd4f07](https://linux-hardware.org/?probe=9322fd4f07) | Nov 27, 2023 |
| AZW           | MINI S                      | Desktop     | [ea6ad73049](https://linux-hardware.org/?probe=ea6ad73049) | Nov 27, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d185d53d8a](https://linux-hardware.org/?probe=d185d53d8a) | Nov 27, 2023 |
| AZW           | MINI S                      | Desktop     | [54b3a350cc](https://linux-hardware.org/?probe=54b3a350cc) | Nov 27, 2023 |
| Lenovo        | ThinkPad T490 20N3S2YS00    | Notebook    | [635d73bd44](https://linux-hardware.org/?probe=635d73bd44) | Nov 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5d7a20cf12](https://linux-hardware.org/?probe=5d7a20cf12) | Nov 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [2715c8329f](https://linux-hardware.org/?probe=2715c8329f) | Nov 27, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [4609a7f037](https://linux-hardware.org/?probe=4609a7f037) | Nov 27, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [a7890b3e79](https://linux-hardware.org/?probe=a7890b3e79) | Nov 27, 2023 |
| Google        | Terra                       | Notebook    | [b21072bf0e](https://linux-hardware.org/?probe=b21072bf0e) | Nov 27, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [1660aa24b1](https://linux-hardware.org/?probe=1660aa24b1) | Nov 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [97e207d679](https://linux-hardware.org/?probe=97e207d679) | Nov 27, 2023 |
| IBM           | 94Y7718 SIT                 | Server      | [b784691187](https://linux-hardware.org/?probe=b784691187) | Nov 27, 2023 |
| IBM           | 69Y1006 SIT                 | Server      | [1e36c88b83](https://linux-hardware.org/?probe=1e36c88b83) | Nov 27, 2023 |
| ECS           | G31T-M9                     | Desktop     | [fa44ca9239](https://linux-hardware.org/?probe=fa44ca9239) | Nov 27, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [419daf1e57](https://linux-hardware.org/?probe=419daf1e57) | Nov 27, 2023 |
| Lenovo        | ThinkPad X200 7458PN6       | Notebook    | [e37f4ef1d4](https://linux-hardware.org/?probe=e37f4ef1d4) | Nov 27, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [182a3875c4](https://linux-hardware.org/?probe=182a3875c4) | Nov 27, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [196be5def7](https://linux-hardware.org/?probe=196be5def7) | Nov 27, 2023 |
| ASUSTek       | P8Z77-M                     | Desktop     | [02ece75e31](https://linux-hardware.org/?probe=02ece75e31) | Nov 27, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [13c14b2399](https://linux-hardware.org/?probe=13c14b2399) | Nov 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [5cf9f0b3e1](https://linux-hardware.org/?probe=5cf9f0b3e1) | Nov 27, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [f18c7cb67b](https://linux-hardware.org/?probe=f18c7cb67b) | Nov 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [007cf510b3](https://linux-hardware.org/?probe=007cf510b3) | Nov 26, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [f0b4d1d85c](https://linux-hardware.org/?probe=f0b4d1d85c) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [332eec50ca](https://linux-hardware.org/?probe=332eec50ca) | Nov 26, 2023 |
| ASRock        | B365 Phantom Gaming 4       | Desktop     | [97dfb05d56](https://linux-hardware.org/?probe=97dfb05d56) | Nov 26, 2023 |
| MSI           | B85M-G43                    | Desktop     | [c8c114c2df](https://linux-hardware.org/?probe=c8c114c2df) | Nov 26, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [5bf94efca1](https://linux-hardware.org/?probe=5bf94efca1) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [6005ac3fdd](https://linux-hardware.org/?probe=6005ac3fdd) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9e05915f77](https://linux-hardware.org/?probe=9e05915f77) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [ff1af2d7d2](https://linux-hardware.org/?probe=ff1af2d7d2) | Nov 26, 2023 |
| Acidanther... | Mac-AF89B6D9451A490B iMa... | All in one  | [281c935424](https://linux-hardware.org/?probe=281c935424) | Nov 26, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [e4c365b554](https://linux-hardware.org/?probe=e4c365b554) | Nov 26, 2023 |
| Acidanther... | Mac-AF89B6D9451A490B iMa... | All in one  | [abd56e94a2](https://linux-hardware.org/?probe=abd56e94a2) | Nov 26, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [484699c792](https://linux-hardware.org/?probe=484699c792) | Nov 26, 2023 |
| Chuwi         | Hi10 plus tablet            | Tablet      | [d5306a60da](https://linux-hardware.org/?probe=d5306a60da) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [aaf90bfd52](https://linux-hardware.org/?probe=aaf90bfd52) | Nov 25, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [bebbc2f6c4](https://linux-hardware.org/?probe=bebbc2f6c4) | Nov 25, 2023 |
| ASRock        | H61M-GS                     | Desktop     | [b1448b5814](https://linux-hardware.org/?probe=b1448b5814) | Nov 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0f05f2568e](https://linux-hardware.org/?probe=0f05f2568e) | Nov 25, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [73eebdebc2](https://linux-hardware.org/?probe=73eebdebc2) | Nov 25, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [8cba28d4a5](https://linux-hardware.org/?probe=8cba28d4a5) | Nov 25, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [1e4a3ed089](https://linux-hardware.org/?probe=1e4a3ed089) | Nov 25, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2bbfbaca9](https://linux-hardware.org/?probe=e2bbfbaca9) | Nov 25, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [a6ab0954e0](https://linux-hardware.org/?probe=a6ab0954e0) | Nov 25, 2023 |
| Unknown       | HX90                        | Desktop     | [b4eef50430](https://linux-hardware.org/?probe=b4eef50430) | Nov 25, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | Notebook    | [f740e978fc](https://linux-hardware.org/?probe=f740e978fc) | Nov 25, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [a0480513dd](https://linux-hardware.org/?probe=a0480513dd) | Nov 25, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [e01ac99a92](https://linux-hardware.org/?probe=e01ac99a92) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [84fefe8e38](https://linux-hardware.org/?probe=84fefe8e38) | Nov 25, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [7e541895b2](https://linux-hardware.org/?probe=7e541895b2) | Nov 25, 2023 |
| HP            | Compaq 6730b (NB027EA#AK... | Notebook    | [3b3bf03eee](https://linux-hardware.org/?probe=3b3bf03eee) | Nov 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [9620d48b2f](https://linux-hardware.org/?probe=9620d48b2f) | Nov 25, 2023 |
| Dell          | Latitude 3510               | Notebook    | [0ebe37e56d](https://linux-hardware.org/?probe=0ebe37e56d) | Nov 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [eb4379efae](https://linux-hardware.org/?probe=eb4379efae) | Nov 24, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [6a4204f060](https://linux-hardware.org/?probe=6a4204f060) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [52e54c41e4](https://linux-hardware.org/?probe=52e54c41e4) | Nov 24, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [dc456b5cc5](https://linux-hardware.org/?probe=dc456b5cc5) | Nov 24, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [4b725b7022](https://linux-hardware.org/?probe=4b725b7022) | Nov 24, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [6497745451](https://linux-hardware.org/?probe=6497745451) | Nov 24, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [9a8395f2ac](https://linux-hardware.org/?probe=9a8395f2ac) | Nov 24, 2023 |
| Acer          | Veriton N4660G              | Desktop     | [2d59329fc6](https://linux-hardware.org/?probe=2d59329fc6) | Nov 24, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [59a3d34f64](https://linux-hardware.org/?probe=59a3d34f64) | Nov 24, 2023 |
| AZW           | U59                         | Desktop     | [b03056a1ad](https://linux-hardware.org/?probe=b03056a1ad) | Nov 24, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [00ef59a95d](https://linux-hardware.org/?probe=00ef59a95d) | Nov 24, 2023 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [f99cb416db](https://linux-hardware.org/?probe=f99cb416db) | Nov 24, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [d8e9de7c1d](https://linux-hardware.org/?probe=d8e9de7c1d) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [499c7927dd](https://linux-hardware.org/?probe=499c7927dd) | Nov 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9102327ebf](https://linux-hardware.org/?probe=9102327ebf) | Nov 23, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [a293e791bf](https://linux-hardware.org/?probe=a293e791bf) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1e5ad7dda0](https://linux-hardware.org/?probe=1e5ad7dda0) | Nov 23, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [d6ab9c6df5](https://linux-hardware.org/?probe=d6ab9c6df5) | Nov 23, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [9d776a8aa8](https://linux-hardware.org/?probe=9d776a8aa8) | Nov 23, 2023 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [d850b7a222](https://linux-hardware.org/?probe=d850b7a222) | Nov 23, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6706fb6f0f](https://linux-hardware.org/?probe=6706fb6f0f) | Nov 23, 2023 |
| Supermicro    | X8DTH                       | Server      | [585c41a46b](https://linux-hardware.org/?probe=585c41a46b) | Nov 23, 2023 |
| Lenovo        | ThinkPad T460 20FMS57C00    | Notebook    | [adabeb3e91](https://linux-hardware.org/?probe=adabeb3e91) | Nov 23, 2023 |
| Acer          | Veriton K8-680G V:1.0       | Desktop     | [415b88184f](https://linux-hardware.org/?probe=415b88184f) | Nov 23, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [b6496b25f7](https://linux-hardware.org/?probe=b6496b25f7) | Nov 23, 2023 |
| Unknown       | Libre Computer AML-S905X... | Soc         | [32e27eeecd](https://linux-hardware.org/?probe=32e27eeecd) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [be47adc197](https://linux-hardware.org/?probe=be47adc197) | Nov 23, 2023 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [101c96a0c0](https://linux-hardware.org/?probe=101c96a0c0) | Nov 22, 2023 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [f990b64367](https://linux-hardware.org/?probe=f990b64367) | Nov 22, 2023 |
| Google        | Edgar                       | Notebook    | [12d8e1b6af](https://linux-hardware.org/?probe=12d8e1b6af) | Nov 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [0337023dbe](https://linux-hardware.org/?probe=0337023dbe) | Nov 22, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [1a0c353a8e](https://linux-hardware.org/?probe=1a0c353a8e) | Nov 22, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [ace74e0228](https://linux-hardware.org/?probe=ace74e0228) | Nov 22, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [d05f324edf](https://linux-hardware.org/?probe=d05f324edf) | Nov 22, 2023 |
| Dell          | Precision M4600             | Notebook    | [864f0c5cfe](https://linux-hardware.org/?probe=864f0c5cfe) | Nov 22, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [eff446af17](https://linux-hardware.org/?probe=eff446af17) | Nov 22, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | Desktop     | [04e88a7e08](https://linux-hardware.org/?probe=04e88a7e08) | Nov 22, 2023 |
| Lenovo        | ThinkPad P52 20MAS21905     | Notebook    | [ada7aab2dd](https://linux-hardware.org/?probe=ada7aab2dd) | Nov 22, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [e0781004e0](https://linux-hardware.org/?probe=e0781004e0) | Nov 22, 2023 |
| Huanan        | X99-F8D PLUS V1.2           | Desktop     | [2edde2bb35](https://linux-hardware.org/?probe=2edde2bb35) | Nov 22, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [43a399828f](https://linux-hardware.org/?probe=43a399828f) | Nov 22, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c95cbb7ba7](https://linux-hardware.org/?probe=c95cbb7ba7) | Nov 22, 2023 |
| ASUSTek       | BM2AD_D510MT_D310MT         | Desktop     | [03140aee39](https://linux-hardware.org/?probe=03140aee39) | Nov 22, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [b72fbdf43a](https://linux-hardware.org/?probe=b72fbdf43a) | Nov 22, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [942a2e278a](https://linux-hardware.org/?probe=942a2e278a) | Nov 22, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [11bf0b075f](https://linux-hardware.org/?probe=11bf0b075f) | Nov 22, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [f6c29a55ad](https://linux-hardware.org/?probe=f6c29a55ad) | Nov 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [adb43d89ab](https://linux-hardware.org/?probe=adb43d89ab) | Nov 22, 2023 |
| Dell          | Latitude 7440               | Notebook    | [fa13937043](https://linux-hardware.org/?probe=fa13937043) | Nov 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [96e98f8c80](https://linux-hardware.org/?probe=96e98f8c80) | Nov 22, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [f892ee3011](https://linux-hardware.org/?probe=f892ee3011) | Nov 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [a38fd35585](https://linux-hardware.org/?probe=a38fd35585) | Nov 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [26da233e2b](https://linux-hardware.org/?probe=26da233e2b) | Nov 21, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [618916ad03](https://linux-hardware.org/?probe=618916ad03) | Nov 21, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [a51c296185](https://linux-hardware.org/?probe=a51c296185) | Nov 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dd61ef221a](https://linux-hardware.org/?probe=dd61ef221a) | Nov 21, 2023 |
| IBM           | 94Y7718 SIT                 | Server      | [c2e0a4cefc](https://linux-hardware.org/?probe=c2e0a4cefc) | Nov 21, 2023 |
| IBM           | 69Y1006 SIT                 | Server      | [729045e89d](https://linux-hardware.org/?probe=729045e89d) | Nov 21, 2023 |
| IBM           | 94Y7718 SIT                 | Server      | [80a223d120](https://linux-hardware.org/?probe=80a223d120) | Nov 21, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [09b6107952](https://linux-hardware.org/?probe=09b6107952) | Nov 20, 2023 |
| MSI           | G31M3                       | Desktop     | [d9e2a5683a](https://linux-hardware.org/?probe=d9e2a5683a) | Nov 20, 2023 |
| Dell          | 0D6H9T A02                  | Desktop     | [034fe5ff39](https://linux-hardware.org/?probe=034fe5ff39) | Nov 20, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [885444b8af](https://linux-hardware.org/?probe=885444b8af) | Nov 20, 2023 |
| HP            | G62                         | Notebook    | [de2f290631](https://linux-hardware.org/?probe=de2f290631) | Nov 20, 2023 |
| Panasonic     | CF-33-1                     | Tablet      | [a2bfa66a7e](https://linux-hardware.org/?probe=a2bfa66a7e) | Nov 20, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [7c6999858f](https://linux-hardware.org/?probe=7c6999858f) | Nov 20, 2023 |
| HP            | 1905                        | Desktop     | [7718b065fd](https://linux-hardware.org/?probe=7718b065fd) | Nov 20, 2023 |
| Dell          | 0DPRKF A04                  | Server      | [99d59495ed](https://linux-hardware.org/?probe=99d59495ed) | Nov 20, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [9fab1b4add](https://linux-hardware.org/?probe=9fab1b4add) | Nov 20, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [7d8f15f875](https://linux-hardware.org/?probe=7d8f15f875) | Nov 20, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [48a562a1b6](https://linux-hardware.org/?probe=48a562a1b6) | Nov 20, 2023 |
| ADLINK Tec... | MXE5400                     | Desktop     | [ae09533003](https://linux-hardware.org/?probe=ae09533003) | Nov 20, 2023 |
| Dell          | 072T6D A05                  | Server      | [146f803f7a](https://linux-hardware.org/?probe=146f803f7a) | Nov 20, 2023 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [67cba6139f](https://linux-hardware.org/?probe=67cba6139f) | Nov 20, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3ec9fbcdea](https://linux-hardware.org/?probe=3ec9fbcdea) | Nov 20, 2023 |
| Dell          | 072T6D A05                  | Server      | [3837a0359c](https://linux-hardware.org/?probe=3837a0359c) | Nov 20, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e394aadce0](https://linux-hardware.org/?probe=e394aadce0) | Nov 20, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [eccc68d336](https://linux-hardware.org/?probe=eccc68d336) | Nov 20, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [9d71a8e453](https://linux-hardware.org/?probe=9d71a8e453) | Nov 20, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [66b4ff8f76](https://linux-hardware.org/?probe=66b4ff8f76) | Nov 20, 2023 |
| Dell          | Latitude 5401               | Notebook    | [b3698296b0](https://linux-hardware.org/?probe=b3698296b0) | Nov 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [a090e73dbf](https://linux-hardware.org/?probe=a090e73dbf) | Nov 20, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [e0d3e7cba3](https://linux-hardware.org/?probe=e0d3e7cba3) | Nov 19, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [2567713f24](https://linux-hardware.org/?probe=2567713f24) | Nov 19, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [a40bc78bcf](https://linux-hardware.org/?probe=a40bc78bcf) | Nov 19, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ac68da4f7c](https://linux-hardware.org/?probe=ac68da4f7c) | Nov 19, 2023 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [4173fd74a2](https://linux-hardware.org/?probe=4173fd74a2) | Nov 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [c9b5f09ea5](https://linux-hardware.org/?probe=c9b5f09ea5) | Nov 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [c76562a6ce](https://linux-hardware.org/?probe=c76562a6ce) | Nov 19, 2023 |
| IBM           | ThinkPad T42 2374GB1        | Notebook    | [455a2c937b](https://linux-hardware.org/?probe=455a2c937b) | Nov 19, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ebfe063207](https://linux-hardware.org/?probe=ebfe063207) | Nov 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [80d502e7c1](https://linux-hardware.org/?probe=80d502e7c1) | Nov 19, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [65f7027c84](https://linux-hardware.org/?probe=65f7027c84) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [deea1f8184](https://linux-hardware.org/?probe=deea1f8184) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [08f1313c20](https://linux-hardware.org/?probe=08f1313c20) | Nov 19, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [866a100b18](https://linux-hardware.org/?probe=866a100b18) | Nov 19, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [2ffe9e80d4](https://linux-hardware.org/?probe=2ffe9e80d4) | Nov 19, 2023 |
| Acer          | Predator G3620              | Desktop     | [16a30abb8e](https://linux-hardware.org/?probe=16a30abb8e) | Nov 19, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fa116d20dc](https://linux-hardware.org/?probe=fa116d20dc) | Nov 19, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [aacf668d6c](https://linux-hardware.org/?probe=aacf668d6c) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [a566513a93](https://linux-hardware.org/?probe=a566513a93) | Nov 19, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [8ebb2df251](https://linux-hardware.org/?probe=8ebb2df251) | Nov 18, 2023 |
| HP            | 8754                        | Mini pc     | [869f3e6995](https://linux-hardware.org/?probe=869f3e6995) | Nov 18, 2023 |
| MSI           | N6105                       | Notebook    | [647e6d71a4](https://linux-hardware.org/?probe=647e6d71a4) | Nov 18, 2023 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [674a7d1154](https://linux-hardware.org/?probe=674a7d1154) | Nov 18, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [9a96aff4c7](https://linux-hardware.org/?probe=9a96aff4c7) | Nov 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [666f76f4e9](https://linux-hardware.org/?probe=666f76f4e9) | Nov 18, 2023 |
| Shuttle       | SW580                       | Desktop     | [31e6c1c2bf](https://linux-hardware.org/?probe=31e6c1c2bf) | Nov 18, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [10abd64eac](https://linux-hardware.org/?probe=10abd64eac) | Nov 18, 2023 |
| Intel         | JSL MRD                     | Desktop     | [fe873e258e](https://linux-hardware.org/?probe=fe873e258e) | Nov 18, 2023 |
| Intel         | JSL MRD                     | Desktop     | [f25d22654a](https://linux-hardware.org/?probe=f25d22654a) | Nov 18, 2023 |
| Dell          | Latitude E6230              | Notebook    | [2a2d7c242e](https://linux-hardware.org/?probe=2a2d7c242e) | Nov 18, 2023 |
| HP            | Stream Notebook             | Notebook    | [5d318f7956](https://linux-hardware.org/?probe=5d318f7956) | Nov 18, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [e5673cd079](https://linux-hardware.org/?probe=e5673cd079) | Nov 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [0fcb08b949](https://linux-hardware.org/?probe=0fcb08b949) | Nov 18, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | Desktop     | [1b1258a703](https://linux-hardware.org/?probe=1b1258a703) | Nov 17, 2023 |
| ASUSTek       | ProArt Z790-CREATOR WIFI    | Desktop     | [c475259455](https://linux-hardware.org/?probe=c475259455) | Nov 17, 2023 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [34b83fef89](https://linux-hardware.org/?probe=34b83fef89) | Nov 17, 2023 |
| BananaPi      | RK3568-BPI-R2PRO-PC HDMI... | Soc         | [9395029e63](https://linux-hardware.org/?probe=9395029e63) | Nov 17, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [95e4318549](https://linux-hardware.org/?probe=95e4318549) | Nov 17, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [416018ed84](https://linux-hardware.org/?probe=416018ed84) | Nov 17, 2023 |
| Irbis         | NB120                       | Notebook    | [a90949861b](https://linux-hardware.org/?probe=a90949861b) | Nov 17, 2023 |
| Supermicro    | X10SRi-FB                   | Server      | [6237baa616](https://linux-hardware.org/?probe=6237baa616) | Nov 17, 2023 |
| SIEMENS       | A5E49569366 RS-AF           | Desktop     | [07d3a028ec](https://linux-hardware.org/?probe=07d3a028ec) | Nov 17, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [204303d116](https://linux-hardware.org/?probe=204303d116) | Nov 17, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [c8af1c096b](https://linux-hardware.org/?probe=c8af1c096b) | Nov 17, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [026b13382d](https://linux-hardware.org/?probe=026b13382d) | Nov 17, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [be914025c2](https://linux-hardware.org/?probe=be914025c2) | Nov 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [11a05c0944](https://linux-hardware.org/?probe=11a05c0944) | Nov 17, 2023 |
| Lenovo        | ThinkPad T590 20N4S02F00    | Notebook    | [f61bc8d881](https://linux-hardware.org/?probe=f61bc8d881) | Nov 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [3486cc9544](https://linux-hardware.org/?probe=3486cc9544) | Nov 17, 2023 |
| Lenovo        | ThinkPad T590 20N4S02F00    | Notebook    | [53dd735333](https://linux-hardware.org/?probe=53dd735333) | Nov 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [24ea543d99](https://linux-hardware.org/?probe=24ea543d99) | Nov 17, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [893762777e](https://linux-hardware.org/?probe=893762777e) | Nov 17, 2023 |
| Supermicro    | X8DTH                       | Server      | [ac2b5e4a3d](https://linux-hardware.org/?probe=ac2b5e4a3d) | Nov 17, 2023 |
| Gigabyte      | B360M H                     | Desktop     | [05634e2369](https://linux-hardware.org/?probe=05634e2369) | Nov 17, 2023 |
| Gigabyte      | B360M H                     | Desktop     | [bea2b1a0b7](https://linux-hardware.org/?probe=bea2b1a0b7) | Nov 17, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [04206b8a50](https://linux-hardware.org/?probe=04206b8a50) | Nov 17, 2023 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [8031c90846](https://linux-hardware.org/?probe=8031c90846) | Nov 17, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [2a9ba6fc77](https://linux-hardware.org/?probe=2a9ba6fc77) | Nov 17, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [b0eba2e921](https://linux-hardware.org/?probe=b0eba2e921) | Nov 16, 2023 |
| Lenovo        | ThinkPad T480 20L6S55K00    | Notebook    | [ba85d81d10](https://linux-hardware.org/?probe=ba85d81d10) | Nov 16, 2023 |
| Schenker      | VIA 15 Pro                  | Notebook    | [604f785353](https://linux-hardware.org/?probe=604f785353) | Nov 16, 2023 |
| Lenovo        | ThinkPad T480 20L6S55K00    | Notebook    | [b2c3886395](https://linux-hardware.org/?probe=b2c3886395) | Nov 16, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [5b38f976c4](https://linux-hardware.org/?probe=5b38f976c4) | Nov 16, 2023 |
| Intel         | NUC7i5DNB J57626-507        | Mini pc     | [110973f4a4](https://linux-hardware.org/?probe=110973f4a4) | Nov 16, 2023 |
| LG Electro... | 22V30R FAB1                 | All in one  | [868b385080](https://linux-hardware.org/?probe=868b385080) | Nov 16, 2023 |
| Aquarius      | Catfish AQC624CF            | Server      | [2f79afe06c](https://linux-hardware.org/?probe=2f79afe06c) | Nov 16, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [0331447937](https://linux-hardware.org/?probe=0331447937) | Nov 16, 2023 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [9ac3245bda](https://linux-hardware.org/?probe=9ac3245bda) | Nov 16, 2023 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [e66475e9e4](https://linux-hardware.org/?probe=e66475e9e4) | Nov 16, 2023 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [54383b8394](https://linux-hardware.org/?probe=54383b8394) | Nov 16, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [b166167703](https://linux-hardware.org/?probe=b166167703) | Nov 16, 2023 |
| NZXT          | N7 B650E                    | Desktop     | [588de38c13](https://linux-hardware.org/?probe=588de38c13) | Nov 16, 2023 |
| Dell          | Latitude 5530               | Notebook    | [4490ae8afe](https://linux-hardware.org/?probe=4490ae8afe) | Nov 16, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [7f136c3e39](https://linux-hardware.org/?probe=7f136c3e39) | Nov 16, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [e7e00bb090](https://linux-hardware.org/?probe=e7e00bb090) | Nov 16, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [23bd3ec971](https://linux-hardware.org/?probe=23bd3ec971) | Nov 16, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [494b815098](https://linux-hardware.org/?probe=494b815098) | Nov 16, 2023 |
| Dell          | Latitude 3320               | Notebook    | [19a9472e3c](https://linux-hardware.org/?probe=19a9472e3c) | Nov 16, 2023 |
| Dell          | Latitude 3320               | Notebook    | [285ad2f27a](https://linux-hardware.org/?probe=285ad2f27a) | Nov 16, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [496e69e1e4](https://linux-hardware.org/?probe=496e69e1e4) | Nov 16, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [3c8c80409b](https://linux-hardware.org/?probe=3c8c80409b) | Nov 15, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [07a1bedd9b](https://linux-hardware.org/?probe=07a1bedd9b) | Nov 15, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [2e59ea85e9](https://linux-hardware.org/?probe=2e59ea85e9) | Nov 15, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [a21066a759](https://linux-hardware.org/?probe=a21066a759) | Nov 15, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [c7c8df77be](https://linux-hardware.org/?probe=c7c8df77be) | Nov 15, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [182484eef8](https://linux-hardware.org/?probe=182484eef8) | Nov 15, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [1c21a56b5c](https://linux-hardware.org/?probe=1c21a56b5c) | Nov 15, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3f0b4a0bfe](https://linux-hardware.org/?probe=3f0b4a0bfe) | Nov 15, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d2cafb1814](https://linux-hardware.org/?probe=d2cafb1814) | Nov 15, 2023 |
| Acer          | Extensa 215-32              | Notebook    | [477b965e66](https://linux-hardware.org/?probe=477b965e66) | Nov 15, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [694833562c](https://linux-hardware.org/?probe=694833562c) | Nov 15, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a7404738ed](https://linux-hardware.org/?probe=a7404738ed) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [1063cc1572](https://linux-hardware.org/?probe=1063cc1572) | Nov 15, 2023 |
| Lenovo        | XiaoXinPro 16 IRH8 83AQ     | Notebook    | [1eb15d0477](https://linux-hardware.org/?probe=1eb15d0477) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [8ee2dc1361](https://linux-hardware.org/?probe=8ee2dc1361) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [6ff4b2ddd5](https://linux-hardware.org/?probe=6ff4b2ddd5) | Nov 15, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e8e0ef7485](https://linux-hardware.org/?probe=e8e0ef7485) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [98dd1a4a4f](https://linux-hardware.org/?probe=98dd1a4a4f) | Nov 15, 2023 |
| Supermicro    | X11SPM-F                    | Server      | [fa3fb34e95](https://linux-hardware.org/?probe=fa3fb34e95) | Nov 15, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [fd459af24b](https://linux-hardware.org/?probe=fd459af24b) | Nov 15, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [e91aa41101](https://linux-hardware.org/?probe=e91aa41101) | Nov 15, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [7bfb7a76bb](https://linux-hardware.org/?probe=7bfb7a76bb) | Nov 15, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [b259a4a4bd](https://linux-hardware.org/?probe=b259a4a4bd) | Nov 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [049356e4bc](https://linux-hardware.org/?probe=049356e4bc) | Nov 15, 2023 |
| Lenovo        | ThinkPad X280 20KES5840A    | Notebook    | [8800b951d8](https://linux-hardware.org/?probe=8800b951d8) | Nov 14, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [1d0338a823](https://linux-hardware.org/?probe=1d0338a823) | Nov 14, 2023 |
| Phoenix/Si... | M730SR                      | Notebook    | [59e9d07293](https://linux-hardware.org/?probe=59e9d07293) | Nov 14, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [e90f4e1799](https://linux-hardware.org/?probe=e90f4e1799) | Nov 14, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [6dbb14b567](https://linux-hardware.org/?probe=6dbb14b567) | Nov 14, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [bdac7a70aa](https://linux-hardware.org/?probe=bdac7a70aa) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ec3e7b63cb](https://linux-hardware.org/?probe=ec3e7b63cb) | Nov 14, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [4470b846a0](https://linux-hardware.org/?probe=4470b846a0) | Nov 14, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [01ce54e1ed](https://linux-hardware.org/?probe=01ce54e1ed) | Nov 14, 2023 |
| Acer          | Extensa 2540                | Notebook    | [22e65d0a5b](https://linux-hardware.org/?probe=22e65d0a5b) | Nov 14, 2023 |
| Packard Be... | EasyNote TK81               | Notebook    | [a44fd2dc7a](https://linux-hardware.org/?probe=a44fd2dc7a) | Nov 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c5f890cb08](https://linux-hardware.org/?probe=c5f890cb08) | Nov 14, 2023 |
| Dell          | 0FJM8V A03                  | Server      | [358c84ceae](https://linux-hardware.org/?probe=358c84ceae) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [c419dad9b3](https://linux-hardware.org/?probe=c419dad9b3) | Nov 14, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [c505d16c82](https://linux-hardware.org/?probe=c505d16c82) | Nov 14, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [e0349fcb14](https://linux-hardware.org/?probe=e0349fcb14) | Nov 14, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [f7a8d7d27e](https://linux-hardware.org/?probe=f7a8d7d27e) | Nov 14, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [149bf90d88](https://linux-hardware.org/?probe=149bf90d88) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [1b4972f4e1](https://linux-hardware.org/?probe=1b4972f4e1) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [9e2ced6a3b](https://linux-hardware.org/?probe=9e2ced6a3b) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [7d0e39fe9f](https://linux-hardware.org/?probe=7d0e39fe9f) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [a6e2f5e7f9](https://linux-hardware.org/?probe=a6e2f5e7f9) | Nov 14, 2023 |
| HP            | 871A                        | Mini pc     | [f9bfe70cef](https://linux-hardware.org/?probe=f9bfe70cef) | Nov 14, 2023 |
| HP            | 871A                        | Mini pc     | [af04867373](https://linux-hardware.org/?probe=af04867373) | Nov 14, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [edc5aa4d33](https://linux-hardware.org/?probe=edc5aa4d33) | Nov 13, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [d44803c611](https://linux-hardware.org/?probe=d44803c611) | Nov 13, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [42d05f19a2](https://linux-hardware.org/?probe=42d05f19a2) | Nov 13, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [57e4a13fab](https://linux-hardware.org/?probe=57e4a13fab) | Nov 13, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [63e36c8c1e](https://linux-hardware.org/?probe=63e36c8c1e) | Nov 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [137d579104](https://linux-hardware.org/?probe=137d579104) | Nov 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [aacc7d1f61](https://linux-hardware.org/?probe=aacc7d1f61) | Nov 13, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [429add2d41](https://linux-hardware.org/?probe=429add2d41) | Nov 13, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [2bc7d7c816](https://linux-hardware.org/?probe=2bc7d7c816) | Nov 13, 2023 |
| WanYou        | WanYouChunXiao              | Desktop     | [82c62804fc](https://linux-hardware.org/?probe=82c62804fc) | Nov 13, 2023 |
| HP            | Presario CQ57               | Notebook    | [0d4999d483](https://linux-hardware.org/?probe=0d4999d483) | Nov 13, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [fe2966d899](https://linux-hardware.org/?probe=fe2966d899) | Nov 13, 2023 |
| ASRock        | QC5000-ITX/PH               | Desktop     | [983df9a44c](https://linux-hardware.org/?probe=983df9a44c) | Nov 13, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [3c0f8e3cdd](https://linux-hardware.org/?probe=3c0f8e3cdd) | Nov 13, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8b8d073259](https://linux-hardware.org/?probe=8b8d073259) | Nov 13, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [189c917237](https://linux-hardware.org/?probe=189c917237) | Nov 13, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [960b3732b0](https://linux-hardware.org/?probe=960b3732b0) | Nov 13, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [0d2accfed1](https://linux-hardware.org/?probe=0d2accfed1) | Nov 13, 2023 |
| Supermicro    | X13SAE-F                    | Server      | [aa50e2cf9c](https://linux-hardware.org/?probe=aa50e2cf9c) | Nov 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fa552b9901](https://linux-hardware.org/?probe=fa552b9901) | Nov 13, 2023 |
| Lenovo        | 3744 WIN SDK0T76466 3424... | All in one  | [765a9d56c1](https://linux-hardware.org/?probe=765a9d56c1) | Nov 12, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [bbc6a54b40](https://linux-hardware.org/?probe=bbc6a54b40) | Nov 12, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [27f69cd90a](https://linux-hardware.org/?probe=27f69cd90a) | Nov 12, 2023 |
| Google        | Hanawl                      | Notebook    | [39b8f28b8e](https://linux-hardware.org/?probe=39b8f28b8e) | Nov 12, 2023 |
| Google        | Hana                        | Notebook    | [80ae861cdf](https://linux-hardware.org/?probe=80ae861cdf) | Nov 12, 2023 |
| Google        | cozmo                       | Soc         | [71a554097a](https://linux-hardware.org/?probe=71a554097a) | Nov 12, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [539da3b61a](https://linux-hardware.org/?probe=539da3b61a) | Nov 12, 2023 |
| Google        | Akemi                       | Notebook    | [c0722184e7](https://linux-hardware.org/?probe=c0722184e7) | Nov 12, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [02a5498c27](https://linux-hardware.org/?probe=02a5498c27) | Nov 12, 2023 |
| Lenovo        | ThinkPad Edge E535 32607... | Notebook    | [f5bea4eb8b](https://linux-hardware.org/?probe=f5bea4eb8b) | Nov 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [929afc7ae1](https://linux-hardware.org/?probe=929afc7ae1) | Nov 12, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dfd502b2af](https://linux-hardware.org/?probe=dfd502b2af) | Nov 12, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [d3d9b9a9ba](https://linux-hardware.org/?probe=d3d9b9a9ba) | Nov 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3b86ff657d](https://linux-hardware.org/?probe=3b86ff657d) | Nov 12, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2fa8b97688](https://linux-hardware.org/?probe=2fa8b97688) | Nov 12, 2023 |
| Intel         | NUC5i5RYB H40999-505        | Mini pc     | [26e08a35c7](https://linux-hardware.org/?probe=26e08a35c7) | Nov 12, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [d3fd2f491d](https://linux-hardware.org/?probe=d3fd2f491d) | Nov 12, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [e89b871c81](https://linux-hardware.org/?probe=e89b871c81) | Nov 12, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [4a9666ef8a](https://linux-hardware.org/?probe=4a9666ef8a) | Nov 12, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [d61e9c84e5](https://linux-hardware.org/?probe=d61e9c84e5) | Nov 12, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [b310ceb608](https://linux-hardware.org/?probe=b310ceb608) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e086a0153d](https://linux-hardware.org/?probe=e086a0153d) | Nov 12, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [15601ebf87](https://linux-hardware.org/?probe=15601ebf87) | Nov 12, 2023 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [d15a200351](https://linux-hardware.org/?probe=d15a200351) | Nov 11, 2023 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [a0230d58fd](https://linux-hardware.org/?probe=a0230d58fd) | Nov 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d49ee32dd4](https://linux-hardware.org/?probe=d49ee32dd4) | Nov 11, 2023 |
| HP            | 15                          | Notebook    | [dbd704fdbb](https://linux-hardware.org/?probe=dbd704fdbb) | Nov 11, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [29b6fb8a4f](https://linux-hardware.org/?probe=29b6fb8a4f) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [daab2f9dc6](https://linux-hardware.org/?probe=daab2f9dc6) | Nov 11, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | Notebook    | [e713ed7256](https://linux-hardware.org/?probe=e713ed7256) | Nov 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X8... | Notebook    | [4bf49cfb42](https://linux-hardware.org/?probe=4bf49cfb42) | Nov 11, 2023 |
| Dell          | 0J4NFV A01                  | Desktop     | [d77b36d8b7](https://linux-hardware.org/?probe=d77b36d8b7) | Nov 11, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [f08c831e30](https://linux-hardware.org/?probe=f08c831e30) | Nov 11, 2023 |
| ASUSTek       | TS10                        | Desktop     | [c35ca1dadb](https://linux-hardware.org/?probe=c35ca1dadb) | Nov 11, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [3da6dfb4b3](https://linux-hardware.org/?probe=3da6dfb4b3) | Nov 11, 2023 |
| Wistron       | X3xx A                      | Desktop     | [30dbd2bb2b](https://linux-hardware.org/?probe=30dbd2bb2b) | Nov 11, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [de5f1aa77e](https://linux-hardware.org/?probe=de5f1aa77e) | Nov 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f4dc3b24c4](https://linux-hardware.org/?probe=f4dc3b24c4) | Nov 11, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [26a111bc63](https://linux-hardware.org/?probe=26a111bc63) | Nov 11, 2023 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [6ea7323880](https://linux-hardware.org/?probe=6ea7323880) | Nov 11, 2023 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [71a3f3197c](https://linux-hardware.org/?probe=71a3f3197c) | Nov 11, 2023 |
| HP            | Stream Notebook             | Notebook    | [f93159b053](https://linux-hardware.org/?probe=f93159b053) | Nov 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [70792a111c](https://linux-hardware.org/?probe=70792a111c) | Nov 10, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [b88ecdebac](https://linux-hardware.org/?probe=b88ecdebac) | Nov 10, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [a83ac39876](https://linux-hardware.org/?probe=a83ac39876) | Nov 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [518492850b](https://linux-hardware.org/?probe=518492850b) | Nov 10, 2023 |
| HP            | ProBook 4510s               | Notebook    | [9b83dea197](https://linux-hardware.org/?probe=9b83dea197) | Nov 10, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [3a7e86a61d](https://linux-hardware.org/?probe=3a7e86a61d) | Nov 10, 2023 |
| Aquarius      | NS585                       | Notebook    | [0f0c55bda1](https://linux-hardware.org/?probe=0f0c55bda1) | Nov 10, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [715a6e7831](https://linux-hardware.org/?probe=715a6e7831) | Nov 10, 2023 |
| MSI           | B75A-G43                    | Desktop     | [8dcfda3039](https://linux-hardware.org/?probe=8dcfda3039) | Nov 10, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [95ea718240](https://linux-hardware.org/?probe=95ea718240) | Nov 10, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e8ad5598b6](https://linux-hardware.org/?probe=e8ad5598b6) | Nov 10, 2023 |
| Acer          | EG43M                       | Desktop     | [53270970b2](https://linux-hardware.org/?probe=53270970b2) | Nov 09, 2023 |
| Lenovo        | ThinkPad T420 4180AZ8       | Notebook    | [089405c957](https://linux-hardware.org/?probe=089405c957) | Nov 09, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4023c4bc2d](https://linux-hardware.org/?probe=4023c4bc2d) | Nov 09, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [448165ceca](https://linux-hardware.org/?probe=448165ceca) | Nov 09, 2023 |
| MSI           | Z170-A PRO                  | Desktop     | [2bdf6b2a2f](https://linux-hardware.org/?probe=2bdf6b2a2f) | Nov 09, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [0e5628865a](https://linux-hardware.org/?probe=0e5628865a) | Nov 09, 2023 |
| Unknown       | 0JP31P A13                  | Server      | [3f7d95a947](https://linux-hardware.org/?probe=3f7d95a947) | Nov 09, 2023 |
| ASUSTek       | Vivobook Go E1504GA_E150... | Notebook    | [50b3f888e9](https://linux-hardware.org/?probe=50b3f888e9) | Nov 09, 2023 |
| Dell          | 0C27VV A01                  | Desktop     | [cc977cc459](https://linux-hardware.org/?probe=cc977cc459) | Nov 09, 2023 |
| ASUSTek       | X99-A                       | Desktop     | [9c40898369](https://linux-hardware.org/?probe=9c40898369) | Nov 09, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [280a15fb6e](https://linux-hardware.org/?probe=280a15fb6e) | Nov 09, 2023 |
| ASUSTek       | Vivobook Go E1504GA_E150... | Notebook    | [a2c63a08f3](https://linux-hardware.org/?probe=a2c63a08f3) | Nov 09, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [983877d365](https://linux-hardware.org/?probe=983877d365) | Nov 09, 2023 |
| HP            | 83E2                        | Mini pc     | [565701f119](https://linux-hardware.org/?probe=565701f119) | Nov 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [ca05ff684b](https://linux-hardware.org/?probe=ca05ff684b) | Nov 09, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [0cfb1d6280](https://linux-hardware.org/?probe=0cfb1d6280) | Nov 09, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [542759f111](https://linux-hardware.org/?probe=542759f111) | Nov 09, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [babe4865df](https://linux-hardware.org/?probe=babe4865df) | Nov 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [406de45098](https://linux-hardware.org/?probe=406de45098) | Nov 09, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [41bf6a7181](https://linux-hardware.org/?probe=41bf6a7181) | Nov 09, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [606524d77e](https://linux-hardware.org/?probe=606524d77e) | Nov 09, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [d52ce3ac0c](https://linux-hardware.org/?probe=d52ce3ac0c) | Nov 09, 2023 |
| MSI           | 970A-G43                    | Desktop     | [c4aecb23af](https://linux-hardware.org/?probe=c4aecb23af) | Nov 09, 2023 |
| MSI           | 970A-G43                    | Desktop     | [7c748629cb](https://linux-hardware.org/?probe=7c748629cb) | Nov 09, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [50a18dd494](https://linux-hardware.org/?probe=50a18dd494) | Nov 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [4b96ca83d1](https://linux-hardware.org/?probe=4b96ca83d1) | Nov 09, 2023 |
| Dell          | Latitude 5420               | Notebook    | [efa8caa859](https://linux-hardware.org/?probe=efa8caa859) | Nov 09, 2023 |
| Intel         | NUC7i5DNB J57626-507        | Mini pc     | [42845cfd6f](https://linux-hardware.org/?probe=42845cfd6f) | Nov 09, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [c8c4c09226](https://linux-hardware.org/?probe=c8c4c09226) | Nov 08, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [39e2c7584e](https://linux-hardware.org/?probe=39e2c7584e) | Nov 08, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [afeda2ac5e](https://linux-hardware.org/?probe=afeda2ac5e) | Nov 08, 2023 |
| HP            | Stream Notebook PC 13       | Notebook    | [25387a2c6f](https://linux-hardware.org/?probe=25387a2c6f) | Nov 08, 2023 |
| Lenovo        | ThinkPad X121e 30515YG      | Notebook    | [4008ec0eb0](https://linux-hardware.org/?probe=4008ec0eb0) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [46458a043d](https://linux-hardware.org/?probe=46458a043d) | Nov 08, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [cddd4ac163](https://linux-hardware.org/?probe=cddd4ac163) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [52b0129f48](https://linux-hardware.org/?probe=52b0129f48) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [b05a5bff97](https://linux-hardware.org/?probe=b05a5bff97) | Nov 08, 2023 |
| MACHENIKE     | L16P                        | Notebook    | [c8e67672f3](https://linux-hardware.org/?probe=c8e67672f3) | Nov 08, 2023 |
| Samsung       | 767XCL                      | Notebook    | [beba8edd4f](https://linux-hardware.org/?probe=beba8edd4f) | Nov 08, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [ed339d2cbb](https://linux-hardware.org/?probe=ed339d2cbb) | Nov 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [0fceea6321](https://linux-hardware.org/?probe=0fceea6321) | Nov 08, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [b111aacb49](https://linux-hardware.org/?probe=b111aacb49) | Nov 08, 2023 |
| ZOTAC         | ZBOX                        | Mini pc     | [c2064210a3](https://linux-hardware.org/?probe=c2064210a3) | Nov 08, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [7461a3b207](https://linux-hardware.org/?probe=7461a3b207) | Nov 08, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [6e215a4ade](https://linux-hardware.org/?probe=6e215a4ade) | Nov 08, 2023 |
| MSI           | MEG Z690 UNIFY              | Desktop     | [7cf2301cb1](https://linux-hardware.org/?probe=7cf2301cb1) | Nov 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [54b91fa265](https://linux-hardware.org/?probe=54b91fa265) | Nov 08, 2023 |
| Dell          | Latitude 5414               | Notebook    | [ad924833a5](https://linux-hardware.org/?probe=ad924833a5) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [696f32a866](https://linux-hardware.org/?probe=696f32a866) | Nov 08, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [24a63b1a77](https://linux-hardware.org/?probe=24a63b1a77) | Nov 07, 2023 |
| Google        | Akemi                       | Notebook    | [e3010845ab](https://linux-hardware.org/?probe=e3010845ab) | Nov 07, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [18013e6256](https://linux-hardware.org/?probe=18013e6256) | Nov 07, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c44e7d92c2](https://linux-hardware.org/?probe=c44e7d92c2) | Nov 07, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [dcbc2d171e](https://linux-hardware.org/?probe=dcbc2d171e) | Nov 07, 2023 |
| Aquarius      | NS585                       | Notebook    | [a5b5734657](https://linux-hardware.org/?probe=a5b5734657) | Nov 07, 2023 |
| Lenovo        | ThinkPad T470 20HES3JR02    | Notebook    | [4cdded6623](https://linux-hardware.org/?probe=4cdded6623) | Nov 07, 2023 |
| Aquarius      | NS585                       | Notebook    | [d9d5e97f89](https://linux-hardware.org/?probe=d9d5e97f89) | Nov 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [988072756b](https://linux-hardware.org/?probe=988072756b) | Nov 07, 2023 |
| Aquarius      | NS585                       | Notebook    | [83a4894072](https://linux-hardware.org/?probe=83a4894072) | Nov 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [1d557ddec8](https://linux-hardware.org/?probe=1d557ddec8) | Nov 07, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [a1650d3328](https://linux-hardware.org/?probe=a1650d3328) | Nov 07, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [2ff1e288bf](https://linux-hardware.org/?probe=2ff1e288bf) | Nov 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [beca8ba507](https://linux-hardware.org/?probe=beca8ba507) | Nov 07, 2023 |
| MSI           | X299 RAIDER                 | Desktop     | [a30007c9f1](https://linux-hardware.org/?probe=a30007c9f1) | Nov 07, 2023 |
| ASUSTek       | X200CA                      | Notebook    | [a982252e30](https://linux-hardware.org/?probe=a982252e30) | Nov 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [eda7dcde73](https://linux-hardware.org/?probe=eda7dcde73) | Nov 07, 2023 |
| Shuttle       | FA76 V10                    | Desktop     | [7007593ff3](https://linux-hardware.org/?probe=7007593ff3) | Nov 07, 2023 |
| Lenovo        | ThinkPad T430 23475H2       | Notebook    | [3dcdf3830e](https://linux-hardware.org/?probe=3dcdf3830e) | Nov 07, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [8cf5696a9e](https://linux-hardware.org/?probe=8cf5696a9e) | Nov 07, 2023 |
| Dell          | 0T2HR0 A02                  | Desktop     | [359d864b50](https://linux-hardware.org/?probe=359d864b50) | Nov 07, 2023 |
| MSI           | MS-6657                     | All in one  | [7d3b32e1cd](https://linux-hardware.org/?probe=7d3b32e1cd) | Nov 07, 2023 |
| MSI           | Modern 15 A10M              | Notebook    | [e1120cd270](https://linux-hardware.org/?probe=e1120cd270) | Nov 06, 2023 |
| ASUSTek       | P4SD-VL                     | Desktop     | [3f224de54f](https://linux-hardware.org/?probe=3f224de54f) | Nov 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d4f7fedd00](https://linux-hardware.org/?probe=d4f7fedd00) | Nov 06, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [240fd7c644](https://linux-hardware.org/?probe=240fd7c644) | Nov 06, 2023 |
| MSI           | Sword 15 A12UGS             | Notebook    | [956c05cdfe](https://linux-hardware.org/?probe=956c05cdfe) | Nov 06, 2023 |
| Unknown       | Unknown                     | Soc         | [cd38000c82](https://linux-hardware.org/?probe=cd38000c82) | Nov 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [5c2d84d61d](https://linux-hardware.org/?probe=5c2d84d61d) | Nov 06, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [83e5c381b2](https://linux-hardware.org/?probe=83e5c381b2) | Nov 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [e84ce1e0d3](https://linux-hardware.org/?probe=e84ce1e0d3) | Nov 06, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [ef03031eaa](https://linux-hardware.org/?probe=ef03031eaa) | Nov 06, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [cc6b66c576](https://linux-hardware.org/?probe=cc6b66c576) | Nov 06, 2023 |
| Medion        | MS-7708                     | Desktop     | [9170f4dd42](https://linux-hardware.org/?probe=9170f4dd42) | Nov 06, 2023 |
| Aquarius      | NS585                       | Notebook    | [ddc8256647](https://linux-hardware.org/?probe=ddc8256647) | Nov 06, 2023 |
| Aquarius      | NS585                       | Notebook    | [2f4e49837d](https://linux-hardware.org/?probe=2f4e49837d) | Nov 06, 2023 |
| Aquarius      | NS585                       | Notebook    | [4fea63336a](https://linux-hardware.org/?probe=4fea63336a) | Nov 06, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [5b992d974a](https://linux-hardware.org/?probe=5b992d974a) | Nov 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [bb021ca517](https://linux-hardware.org/?probe=bb021ca517) | Nov 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c8c8d15e25](https://linux-hardware.org/?probe=c8c8d15e25) | Nov 06, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a2ad36d26c](https://linux-hardware.org/?probe=a2ad36d26c) | Nov 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [eef004b620](https://linux-hardware.org/?probe=eef004b620) | Nov 05, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [67a67e246c](https://linux-hardware.org/?probe=67a67e246c) | Nov 05, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [864877692e](https://linux-hardware.org/?probe=864877692e) | Nov 05, 2023 |
| sunxi         | Banana Pi BPI-M2-Zero       | Soc         | [fc24faaa0c](https://linux-hardware.org/?probe=fc24faaa0c) | Nov 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [42cbdffa93](https://linux-hardware.org/?probe=42cbdffa93) | Nov 05, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [f0399efc08](https://linux-hardware.org/?probe=f0399efc08) | Nov 05, 2023 |
| Shuttle       | FH87                        | Desktop     | [1488ef29c3](https://linux-hardware.org/?probe=1488ef29c3) | Nov 05, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [01e74da42d](https://linux-hardware.org/?probe=01e74da42d) | Nov 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9213826ac6](https://linux-hardware.org/?probe=9213826ac6) | Nov 05, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [22b09dfb91](https://linux-hardware.org/?probe=22b09dfb91) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [92ed6d25c3](https://linux-hardware.org/?probe=92ed6d25c3) | Nov 05, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [5b5425c6d8](https://linux-hardware.org/?probe=5b5425c6d8) | Nov 05, 2023 |
| HP            | Mini 210-3000               | Notebook    | [8b55a876a9](https://linux-hardware.org/?probe=8b55a876a9) | Nov 05, 2023 |
| Google        | Nami                        | Notebook    | [19c94b9484](https://linux-hardware.org/?probe=19c94b9484) | Nov 05, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [5c50c142b3](https://linux-hardware.org/?probe=5c50c142b3) | Nov 05, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [d6cd277a79](https://linux-hardware.org/?probe=d6cd277a79) | Nov 05, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [7d9395e4a7](https://linux-hardware.org/?probe=7d9395e4a7) | Nov 05, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [1bb894cf19](https://linux-hardware.org/?probe=1bb894cf19) | Nov 04, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [62798aa8cf](https://linux-hardware.org/?probe=62798aa8cf) | Nov 04, 2023 |
| Supermicro    | X10SRA                      | Server      | [87045c1939](https://linux-hardware.org/?probe=87045c1939) | Nov 04, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [dade20f823](https://linux-hardware.org/?probe=dade20f823) | Nov 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6a44cc2c3c](https://linux-hardware.org/?probe=6a44cc2c3c) | Nov 04, 2023 |
| Acer          | AO532h                      | Notebook    | [0b3d66b04a](https://linux-hardware.org/?probe=0b3d66b04a) | Nov 04, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [03f4055831](https://linux-hardware.org/?probe=03f4055831) | Nov 04, 2023 |
| Dell          | Inspiron 16 5620            | Notebook    | [04d425d450](https://linux-hardware.org/?probe=04d425d450) | Nov 04, 2023 |
| Google        | Bluebird                    | Notebook    | [55dbc11653](https://linux-hardware.org/?probe=55dbc11653) | Nov 04, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [3521a1f918](https://linux-hardware.org/?probe=3521a1f918) | Nov 04, 2023 |
| Google        | Bluebird                    | Notebook    | [9e12130a28](https://linux-hardware.org/?probe=9e12130a28) | Nov 04, 2023 |
| HP            | OMEN by Laptop 17-ck1xxx    | Notebook    | [bea6a6babf](https://linux-hardware.org/?probe=bea6a6babf) | Nov 04, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | Notebook    | [0767db36fe](https://linux-hardware.org/?probe=0767db36fe) | Nov 04, 2023 |
| Dell          | Precision 7560              | Notebook    | [54a8deb305](https://linux-hardware.org/?probe=54a8deb305) | Nov 04, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7d06f443c7](https://linux-hardware.org/?probe=7d06f443c7) | Nov 03, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [20bee22e0a](https://linux-hardware.org/?probe=20bee22e0a) | Nov 03, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [3ff2e66179](https://linux-hardware.org/?probe=3ff2e66179) | Nov 03, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [fbbb34a0cb](https://linux-hardware.org/?probe=fbbb34a0cb) | Nov 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [43ccf36bf0](https://linux-hardware.org/?probe=43ccf36bf0) | Nov 03, 2023 |
| Google        | Enguarde                    | Notebook    | [bc6a541eb9](https://linux-hardware.org/?probe=bc6a541eb9) | Nov 03, 2023 |
| ZOTAC         | ZBOXNANO-AD10               | Mini pc     | [2b0fbc5661](https://linux-hardware.org/?probe=2b0fbc5661) | Nov 03, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [8b855ce4f4](https://linux-hardware.org/?probe=8b855ce4f4) | Nov 03, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [b87ccd7768](https://linux-hardware.org/?probe=b87ccd7768) | Nov 03, 2023 |
| Rockchip      | Orange Pi 5 Plus            | Soc         | [9c30c8c8b4](https://linux-hardware.org/?probe=9c30c8c8b4) | Nov 03, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [c4aa915297](https://linux-hardware.org/?probe=c4aa915297) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1bdfa38b3e](https://linux-hardware.org/?probe=1bdfa38b3e) | Nov 03, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [f96f6e6127](https://linux-hardware.org/?probe=f96f6e6127) | Nov 03, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [b29e9ebfbe](https://linux-hardware.org/?probe=b29e9ebfbe) | Nov 03, 2023 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [9495d53da4](https://linux-hardware.org/?probe=9495d53da4) | Nov 03, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [18f018a8ae](https://linux-hardware.org/?probe=18f018a8ae) | Nov 03, 2023 |
| Dell          | 0CN7X8 A05                  | Server      | [afe0c7dfbe](https://linux-hardware.org/?probe=afe0c7dfbe) | Nov 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [1889111d8a](https://linux-hardware.org/?probe=1889111d8a) | Nov 03, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [212105774f](https://linux-hardware.org/?probe=212105774f) | Nov 02, 2023 |
| HP            | 18E7                        | Desktop     | [212d6dba47](https://linux-hardware.org/?probe=212d6dba47) | Nov 02, 2023 |
| HP            | 18E7                        | Desktop     | [7064df5d87](https://linux-hardware.org/?probe=7064df5d87) | Nov 02, 2023 |
| Unknown       | X99-GT                      | Desktop     | [751ea1add9](https://linux-hardware.org/?probe=751ea1add9) | Nov 02, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [9493bec7e6](https://linux-hardware.org/?probe=9493bec7e6) | Nov 02, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [7c06ac2664](https://linux-hardware.org/?probe=7c06ac2664) | Nov 02, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [33a984f9f8](https://linux-hardware.org/?probe=33a984f9f8) | Nov 02, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [d48f7514df](https://linux-hardware.org/?probe=d48f7514df) | Nov 02, 2023 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [de79fbf182](https://linux-hardware.org/?probe=de79fbf182) | Nov 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [db23a9b8d4](https://linux-hardware.org/?probe=db23a9b8d4) | Nov 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [425bafc788](https://linux-hardware.org/?probe=425bafc788) | Nov 02, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [5ce5b321b0](https://linux-hardware.org/?probe=5ce5b321b0) | Nov 02, 2023 |
| ASRock        | Z77 WS                      | Desktop     | [73b9354a1a](https://linux-hardware.org/?probe=73b9354a1a) | Nov 02, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8c9de8be4f](https://linux-hardware.org/?probe=8c9de8be4f) | Nov 02, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [2b76c45313](https://linux-hardware.org/?probe=2b76c45313) | Nov 02, 2023 |
| HP            | Pavilion g6                 | Notebook    | [c35f9a55aa](https://linux-hardware.org/?probe=c35f9a55aa) | Nov 02, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 6801      | 53.15%  |
| Debian 12                       | 2425      | 18.95%  |
| Debian 10                       | 1786      | 13.96%  |
| Debian Testing                  | 644       | 5.03%   |
| Debian                          | 405       | 3.17%   |
| Debian 9                        | 324       | 2.53%   |
| Debian Unstable                 | 263       | 2.06%   |
| Debian 11-updates               | 47        | 0.37%   |
| Debian 8                        | 40        | 0.31%   |
| Debian Testing/unstable         | 31        | 0.24%   |
| Debian Sid                      | 7         | 0.05%   |
| Debian 7                        | 5         | 0.04%   |
| Debian 23                       | 5         | 0.04%   |
| Debian Testing-proposed-updates | 3         | 0.02%   |
| Debian 6                        | 3         | 0.02%   |
| Debian 22                       | 3         | 0.02%   |
| Debian 12-updates               | 2         | 0.02%   |
| Debian 99                       | 1         | 0.01%   |
| Debian 23100609                 | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Debian | 12087     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.10.0-8-amd64  | 983       | 6.99%   |
| 5.10.0-7-amd64  | 691       | 4.91%   |
| 5.10.0-10-amd64 | 578       | 4.11%   |
| 6.1.0-13-amd64  | 528       | 3.76%   |
| 5.10.0-21-amd64 | 478       | 3.4%    |
| 5.10.0-20-amd64 | 374       | 2.66%   |
| 5.10.0-16-amd64 | 372       | 2.65%   |
| 5.10.0-9-amd64  | 330       | 2.35%   |
| 6.1.0-10-amd64  | 304       | 2.16%   |
| 6.1.0-9-amd64   | 302       | 2.15%   |
| 5.10.0-19-amd64 | 294       | 2.09%   |
| 5.10.0-18-amd64 | 294       | 2.09%   |
| 6.1.0-11-amd64  | 290       | 2.06%   |
| 5.10.0-13-amd64 | 265       | 1.88%   |
| 6.1.0-4-amd64   | 226       | 1.61%   |
| 5.10.0-23-amd64 | 215       | 1.53%   |
| 6.1.0-12-amd64  | 206       | 1.47%   |
| 5.10.0-11-amd64 | 196       | 1.39%   |
| 5.10.0-2-amd64  | 167       | 1.19%   |
| 4.19.0-6-amd64  | 145       | 1.03%   |
| 4.19.0-9-amd64  | 143       | 1.02%   |
| 5.10.0-14-amd64 | 142       | 1.01%   |
| 5.10.0-17-amd64 | 127       | 0.9%    |
| 4.19.0-13-amd64 | 125       | 0.89%   |
| 4.19.0-8-amd64  | 120       | 0.85%   |
| 4.19.0-16-amd64 | 110       | 0.78%   |
| 5.10.0-15-amd64 | 109       | 0.78%   |
| 5.10.0-22-amd64 | 107       | 0.76%   |
| 4.19.0-14-amd64 | 104       | 0.74%   |
| 5.15.0-2-amd64  | 96        | 0.68%   |
| 6.1.0-7-amd64   | 95        | 0.68%   |
| 4.19.0-17-amd64 | 94        | 0.67%   |
| 4.19.0-10-amd64 | 92        | 0.65%   |
| 4.19.0-12-amd64 | 88        | 0.63%   |
| 5.10.0-12-amd64 | 74        | 0.53%   |
| 4.9.0-8-amd64   | 70        | 0.5%    |
| 5.10.0-6-amd64  | 66        | 0.47%   |
| 5.10.0-26-amd64 | 63        | 0.45%   |
| 6.1.0-16-amd64  | 55        | 0.39%   |
| 6.0.0-6-amd64   | 53        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 5866      | 44.5%   |
| 6.1.0    | 2273      | 17.24%  |
| 4.19.0   | 1261      | 9.57%   |
| 6.0.0    | 264       | 2%      |
| 4.9.0    | 242       | 1.84%   |
| 5.18.0   | 201       | 1.52%   |
| 5.15.0   | 169       | 1.28%   |
| 5.9.0    | 150       | 1.14%   |
| 5.16.0   | 137       | 1.04%   |
| 5.19.0   | 123       | 0.93%   |
| 5.7.0    | 121       | 0.92%   |
| 6.5.0    | 120       | 0.91%   |
| 5.8.0    | 120       | 0.91%   |
| 5.4.0    | 118       | 0.9%    |
| 5.6.0    | 100       | 0.76%   |
| 6.2.16   | 97        | 0.74%   |
| 5.14.0   | 92        | 0.7%    |
| 6.4.0    | 84        | 0.64%   |
| 5.17.0   | 71        | 0.54%   |
| 5.13.19  | 60        | 0.46%   |
| 6.3.0    | 54        | 0.41%   |
| 5.3.0    | 39        | 0.3%    |
| 5.15.107 | 35        | 0.27%   |
| 5.10.10  | 35        | 0.27%   |
| 6.1.21   | 32        | 0.24%   |
| 5.5.0    | 32        | 0.24%   |
| 5.15.74  | 32        | 0.24%   |
| 5.11.22  | 28        | 0.21%   |
| 5.2.0    | 21        | 0.16%   |
| 5.15.85  | 21        | 0.16%   |
| 4.18.0   | 21        | 0.16%   |
| 6.5.11   | 20        | 0.15%   |
| 5.15.84  | 20        | 0.15%   |
| 5.15.102 | 20        | 0.15%   |
| 3.16.0   | 20        | 0.15%   |
| 5.15.83  | 19        | 0.14%   |
| 5.15.32  | 19        | 0.14%   |
| 5.15.39  | 18        | 0.14%   |
| 5.15.30  | 18        | 0.14%   |
| 5.15.35  | 17        | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 6028      | 45.97%  |
| 6.1     | 2371      | 18.08%  |
| 4.19    | 1281      | 9.77%   |
| 5.15    | 509       | 3.88%   |
| 6.0     | 285       | 2.17%   |
| 4.9     | 255       | 1.94%   |
| 5.4     | 222       | 1.69%   |
| 5.18    | 214       | 1.63%   |
| 5.9     | 159       | 1.21%   |
| 6.5     | 155       | 1.18%   |
| 5.16    | 150       | 1.14%   |
| 5.19    | 144       | 1.1%    |
| 5.8     | 132       | 1.01%   |
| 6.2     | 130       | 0.99%   |
| 5.7     | 129       | 0.98%   |
| 5.6     | 110       | 0.84%   |
| 6.4     | 108       | 0.82%   |
| 5.14    | 102       | 0.78%   |
| 5.17    | 86        | 0.66%   |
| 5.13    | 83        | 0.63%   |
| 6.3     | 67        | 0.51%   |
| 5.3     | 66        | 0.5%    |
| 5.11    | 51        | 0.39%   |
| 5.5     | 38        | 0.29%   |
| 5.2     | 27        | 0.21%   |
| 6.6     | 23        | 0.18%   |
| 4.18    | 22        | 0.17%   |
| 3.16    | 20        | 0.15%   |
| 4.15    | 19        | 0.14%   |
| 5.12    | 16        | 0.12%   |
| 5.0     | 13        | 0.1%    |
| 4.4     | 13        | 0.1%    |
| 5       | 11        | 0.08%   |
| 4.14    | 9         | 0.07%   |
| 4.17    | 8         | 0.06%   |
| 4.1     | 8         | 0.06%   |
| 5.1     | 6         | 0.05%   |
| 6       | 4         | 0.03%   |
| 3.10    | 4         | 0.03%   |
| 4.8     | 3         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 11328     | 93.71%  |
| i686        | 352       | 2.91%   |
| aarch64     | 304       | 2.51%   |
| armv7l      | 65        | 0.54%   |
| riscv64     | 19        | 0.16%   |
| ppc64       | 7         | 0.06%   |
| mips64      | 3         | 0.02%   |
| i586        | 3         | 0.02%   |
| ppc64le     | 2         | 0.02%   |
| loongarch64 | 2         | 0.02%   |
| sparc64     | 1         | 0.01%   |
| sh4a        | 1         | 0.01%   |
| i486        | 1         | 0.01%   |
| armv6l      | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 3610      | 29.14%  |
| GNOME             | 2998      | 24.2%   |
| KDE5              | 1644      | 13.27%  |
| XFCE              | 1499      | 12.1%   |
| MATE              | 520       | 4.2%    |
| X-Cinnamon        | 446       | 3.6%    |
| LXDE              | 380       | 3.07%   |
| Cinnamon          | 315       | 2.54%   |
| KDE               | 220       | 1.78%   |
| LXQt              | 189       | 1.53%   |
| i3                | 163       | 1.32%   |
| Openbox           | 72        | 0.58%   |
| GNOME Flashback   | 70        | 0.57%   |
| lightdm-xsession  | 50        | 0.4%    |
| Budgie            | 35        | 0.28%   |
| GNOME Classic     | 33        | 0.27%   |
| Trinity           | 30        | 0.24%   |
| awesome           | 11        | 0.09%   |
| sway              | 10        | 0.08%   |
| fluxbox           | 8         | 0.06%   |
| GNUstep           | 7         | 0.06%   |
| Enlightenment     | 7         | 0.06%   |
| dwm               | 7         | 0.06%   |
| LXDE-pi-wayfire   | 6         | 0.05%   |
| KDE4              | 6         | 0.05%   |
| x-session-manager | 5         | 0.04%   |
| bspwm             | 5         | 0.04%   |
| Unity             | 4         | 0.03%   |
| Phosh:GNOME       | 4         | 0.03%   |
| ICEWM             | 4         | 0.03%   |
| Cutefish          | 4         | 0.03%   |
| xmonad            | 3         | 0.02%   |
| default           | 3         | 0.02%   |
| BunsenLabs        | 3         | 0.02%   |
| fvwm              | 2         | 0.02%   |
| Deepin            | 2         | 0.02%   |
| wmaker-common     | 1         | 0.01%   |
| UKUI              | 1         | 0.01%   |
| TOS:GNOME         | 1         | 0.01%   |
| qtile             | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 6337      | 51.32%  |
| Unknown     | 2317      | 18.76%  |
| Wayland     | 2291      | 18.55%  |
| Tty         | 1391      | 11.26%  |
| Web         | 6         | 0.05%   |
| Unspecified | 6         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 5409      | 43.68%  |
| LightDM | 2132      | 17.22%  |
| GDM     | 1655      | 13.36%  |
| SDDM    | 1458      | 11.77%  |
| GDM3    | 946       | 7.64%   |
| TDM     | 600       | 4.84%   |
| NODM    | 51        | 0.41%   |
| XDM     | 45        | 0.36%   |
| SLiM    | 36        | 0.29%   |
| LXDM    | 20        | 0.16%   |
| KDM     | 15        | 0.12%   |
| Ly      | 6         | 0.05%   |
| WDM     | 4         | 0.03%   |
| GREETD  | 4         | 0.03%   |
| SU      | 2         | 0.02%   |
| LDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 4288      | 34.91%  |
| Unknown | 1548      | 12.6%   |
| ru_RU   | 1334      | 10.86%  |
| de_DE   | 782       | 6.37%   |
| en_GB   | 637       | 5.19%   |
| fr_FR   | 604       | 4.92%   |
| pt_BR   | 362       | 2.95%   |
| es_ES   | 329       | 2.68%   |
| it_IT   | 293       | 2.39%   |
| C       | 194       | 1.58%   |
| pl_PL   | 177       | 1.44%   |
| en_CA   | 167       | 1.36%   |
| en_AU   | 148       | 1.2%    |
| zh_CN   | 91        | 0.74%   |
| en_IN   | 88        | 0.72%   |
| es_MX   | 85        | 0.69%   |
| es_AR   | 75        | 0.61%   |
| en_IE   | 66        | 0.54%   |
| hu_HU   | 58        | 0.47%   |
| es_VE   | 48        | 0.39%   |
| sv_SE   | 46        | 0.37%   |
| es_CL   | 46        | 0.37%   |
| de_CH   | 45        | 0.37%   |
| de_AT   | 44        | 0.36%   |
| nl_NL   | 37        | 0.3%    |
| en_ZA   | 37        | 0.3%    |
| pt_PT   | 36        | 0.29%   |
| ja_JP   | 36        | 0.29%   |
| cs_CZ   | 33        | 0.27%   |
| fi_FI   | 30        | 0.24%   |
| en_NZ   | 30        | 0.24%   |
| fr_BE   | 26        | 0.21%   |
| nl_BE   | 22        | 0.18%   |
| es_CO   | 22        | 0.18%   |
| tr_TR   | 21        | 0.17%   |
| ca_ES   | 21        | 0.17%   |
| fr_CH   | 20        | 0.16%   |
| ru_UA   | 17        | 0.14%   |
| zh_TW   | 16        | 0.13%   |
| en_SG   | 15        | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 6614      | 54.04%  |
| BIOS | 5625      | 45.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type       | Computers | Percent |
|------------|-----------|---------|
| Ext4       | 8804      | 72.13%  |
| Overlay    | 2199      | 18.02%  |
| Btrfs      | 459       | 3.76%   |
| Zfs        | 200       | 1.64%   |
| Unknown    | 171       | 1.4%    |
| Xfs        | 148       | 1.21%   |
| Tmpfs      | 86        | 0.7%    |
| Rootfs     | 47        | 0.39%   |
| Ext3       | 36        | 0.29%   |
| Ext2       | 30        | 0.25%   |
| F2fs       | 8         | 0.07%   |
| Aufs       | 8         | 0.07%   |
| Jfs        | 3         | 0.02%   |
| XXXXXXX    | 2         | 0.02%   |
| Ubifs      | 2         | 0.02%   |
| XXXXX      | 1         | 0.01%   |
| Fuse.sshfs | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 7031      | 57.21%  |
| MBR     | 2939      | 23.91%  |
| Unknown | 2320      | 18.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 10106     | 82.38%  |
| Yes       | 2161      | 17.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 8710      | 71.24%  |
| Yes       | 3516      | 28.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1831      | 15.15%  |
| Lenovo                  | 1773      | 14.67%  |
| Hewlett-Packard         | 1343      | 11.11%  |
| Dell                    | 1296      | 10.72%  |
| Gigabyte Technology     | 788       | 6.52%   |
| Apple                   | 783       | 6.48%   |
| MSI                     | 607       | 5.02%   |
| Acer                    | 485       | 4.01%   |
| ASRock                  | 444       | 3.67%   |
| Intel                   | 277       | 2.29%   |
| Unknown                 | 213       | 1.76%   |
| Google                  | 210       | 1.74%   |
| Raspberry Pi Foundation | 193       | 1.6%    |
| Supermicro              | 131       | 1.08%   |
| Toshiba                 | 104       | 0.86%   |
| Samsung Electronics     | 96        | 0.79%   |
| Fujitsu                 | 94        | 0.78%   |
| ECS                     | 59        | 0.49%   |
| HUAWEI                  | 58        | 0.48%   |
| AZW                     | 57        | 0.47%   |
| Aquarius                | 52        | 0.43%   |
| Sony                    | 50        | 0.41%   |
| Foxconn                 | 44        | 0.36%   |
| ASRockRack              | 40        | 0.33%   |
| Notebook                | 33        | 0.27%   |
| Medion                  | 33        | 0.27%   |
| Positivo                | 30        | 0.25%   |
| Biostar                 | 29        | 0.24%   |
| Pegatron                | 28        | 0.23%   |
| IBM                     | 26        | 0.22%   |
| AMI                     | 26        | 0.22%   |
| Microsoft               | 25        | 0.21%   |
| Packard Bell            | 23        | 0.19%   |
| Alienware               | 23        | 0.19%   |
| Fujitsu Siemens         | 21        | 0.17%   |
| BESSTAR Tech            | 21        | 0.17%   |
| sunxi                   | 20        | 0.17%   |
| Shuttle                 | 19        | 0.16%   |
| Panasonic               | 18        | 0.15%   |
| Inventec                | 17        | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 355       | 2.94%   |
| Unknown                                   | 252       | 2.08%   |
| ASUS All Series                           | 140       | 1.16%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 114       | 0.94%   |
| Apple MacBookAir7,2                       | 81        | 0.67%   |
| Apple MacBookAir7,1                       | 77        | 0.64%   |
| Google Enguarde                           | 74        | 0.61%   |
| Apple MacBook2,1                          | 58        | 0.48%   |
| ASUS S20 K29                              | 55        | 0.46%   |
| Aquarius NS585                            | 48        | 0.4%    |
| MSI MS-7996                               | 45        | 0.37%   |
| Google Reks                               | 45        | 0.37%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 37        | 0.31%   |
| Supermicro Super Server                   | 31        | 0.26%   |
| HP Notebook                               | 28        | 0.23%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 27        | 0.22%   |
| MSI MS-7817                               | 27        | 0.22%   |
| ECS G31T-M9                               | 25        | 0.21%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 24        | 0.2%    |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 24        | 0.2%    |
| Lenovo ThinkPad E475 20H40006US           | 24        | 0.2%    |
| Google Terra                              | 24        | 0.2%    |
| Gigabyte H81M-S2V                         | 24        | 0.2%    |
| Apple MacBook4,1                          | 23        | 0.19%   |
| RPi Raspberry Pi 4 Model B Rev 1.5        | 22        | 0.18%   |
| Dell OptiPlex 7010                        | 21        | 0.17%   |
| ASUS PRIME H510M-A                        | 20        | 0.17%   |
| ASRock H470M-HVS                          | 20        | 0.17%   |
| Gigabyte B450M DS3H                       | 19        | 0.16%   |
| ASUS TUF Gaming X570-PLUS                 | 19        | 0.16%   |
| HP Pavilion g6                            | 18        | 0.15%   |
| ASUS PRIME A320M-K                        | 18        | 0.15%   |
| ECS H61H2-M13                             | 17        | 0.14%   |
| Acer Aspire A315-23                       | 17        | 0.14%   |
| RPi Raspberry Pi                          | 16        | 0.13%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.13%   |
| Gigabyte H410M S2H                        | 16        | 0.13%   |
| ASUS P8H61-M LX3 R2.0                     | 16        | 0.13%   |
| ASUS H110M-R                              | 16        | 0.13%   |
| ASUS PRIME B450M-A                        | 15        | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 1039      | 8.6%    |
| Apple MacBook5     | 357       | 2.95%   |
| Dell Latitude      | 349       | 2.89%   |
| Acer Aspire        | 308       | 2.55%   |
| Dell Inspiron      | 283       | 2.34%   |
| ASUS PRIME         | 268       | 2.22%   |
| Unknown            | 252       | 2.08%   |
| Lenovo IdeaPad     | 240       | 1.99%   |
| HP EliteBook       | 203       | 1.68%   |
| RPi Raspberry      | 193       | 1.6%    |
| Dell OptiPlex      | 175       | 1.45%   |
| HP Pavilion        | 165       | 1.37%   |
| Apple MacBookAir7  | 158       | 1.31%   |
| ASUS ROG           | 149       | 1.23%   |
| ASUS All           | 140       | 1.16%   |
| Dell Precision     | 129       | 1.07%   |
| HP Laptop          | 128       | 1.06%   |
| Dell XPS           | 124       | 1.03%   |
| HP Compaq          | 121       | 1%      |
| HP ProBook         | 120       | 0.99%   |
| Lenovo ThinkCentre | 115       | 0.95%   |
| ASUS VivoBook      | 100       | 0.83%   |
| ASUS TUF           | 99        | 0.82%   |
| Dell Vostro        | 89        | 0.74%   |
| Dell PowerEdge     | 86        | 0.71%   |
| Toshiba Satellite  | 81        | 0.67%   |
| Google Enguarde    | 74        | 0.61%   |
| HP ProLiant        | 61        | 0.5%    |
| Apple MacBook2     | 58        | 0.48%   |
| Lenovo Yoga        | 55        | 0.46%   |
| ASUS S20           | 55        | 0.46%   |
| HP ENVY            | 49        | 0.41%   |
| ASUS ASUS          | 49        | 0.41%   |
| HP EliteDesk       | 48        | 0.4%    |
| Aquarius NS585     | 48        | 0.4%    |
| MSI MS-7996        | 45        | 0.37%   |
| Lenovo Legion      | 45        | 0.37%   |
| Google Reks        | 45        | 0.37%   |
| Gigabyte B450M     | 45        | 0.37%   |
| ASUS ZenBook       | 43        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 1220      | 10.09%  |
| 2019    | 985       | 8.15%   |
| 2021    | 981       | 8.12%   |
| 2018    | 950       | 7.86%   |
| 2012    | 827       | 6.84%   |
| 2009    | 773       | 6.4%    |
| 2017    | 689       | 5.7%    |
| 2013    | 686       | 5.68%   |
| 2011    | 677       | 5.6%    |
| 2022    | 646       | 5.34%   |
| 2016    | 595       | 4.92%   |
| 2014    | 583       | 4.82%   |
| 2015    | 526       | 4.35%   |
| 2010    | 452       | 3.74%   |
| Unknown | 363       | 3%      |
| 2007    | 360       | 2.98%   |
| 2008    | 349       | 2.89%   |
| 2023    | 231       | 1.91%   |
| 2006    | 87        | 0.72%   |
| 2005    | 53        | 0.44%   |
| 2004    | 26        | 0.22%   |
| 2003    | 17        | 0.14%   |
| 2002    | 4         | 0.03%   |
| 2001    | 3         | 0.02%   |
| 2024    | 2         | 0.02%   |
| 2000    | 2         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 6054      | 50.09%  |
| Desktop        | 4626      | 38.27%  |
| System on chip | 333       | 2.76%   |
| Convertible    | 323       | 2.67%   |
| Mini pc        | 289       | 2.39%   |
| Server         | 267       | 2.21%   |
| All in one     | 110       | 0.91%   |
| Tablet         | 69        | 0.57%   |
| Phone          | 11        | 0.09%   |
| Other          | 2         | 0.02%   |
| Stick pc       | 2         | 0.02%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 11444     | 94.16%  |
| Enabled  | 710       | 5.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 11855     | 98.07%  |
| Yes  | 233       | 1.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 2576      | 20.86%  |
| 16.01-24.0      | 2301      | 18.63%  |
| 3.01-4.0        | 2017      | 16.33%  |
| 8.01-16.0       | 1968      | 15.94%  |
| 32.01-64.0      | 1238      | 10.02%  |
| 1.01-2.0        | 870       | 7.04%   |
| 64.01-256.0     | 615       | 4.98%   |
| 24.01-32.0      | 222       | 1.8%    |
| 2.01-3.0        | 220       | 1.78%   |
| 0.51-1.0        | 194       | 1.57%   |
| 0.01-0.5        | 56        | 0.45%   |
| More than 256.0 | 52        | 0.42%   |
| Unknown         | 19        | 0.15%   |
| 0               | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 3813      | 29.21%  |
| 2.01-3.0        | 2452      | 18.78%  |
| 4.01-8.0        | 1915      | 14.67%  |
| 0.51-1.0        | 1812      | 13.88%  |
| 3.01-4.0        | 1411      | 10.81%  |
| 8.01-16.0       | 647       | 4.96%   |
| 0.01-0.5        | 583       | 4.47%   |
| 16.01-24.0      | 175       | 1.34%   |
| 32.01-64.0      | 95        | 0.73%   |
| 24.01-32.0      | 73        | 0.56%   |
| 64.01-256.0     | 47        | 0.36%   |
| Unknown         | 28        | 0.21%   |
| More than 256.0 | 3         | 0.02%   |
| 0               | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7667      | 61.96%  |
| 2       | 2621      | 21.18%  |
| 3       | 871       | 7.04%   |
| 4       | 486       | 3.93%   |
| 5       | 229       | 1.85%   |
| 6       | 135       | 1.09%   |
| 0       | 101       | 0.82%   |
| 7       | 81        | 0.65%   |
| 8       | 57        | 0.46%   |
| 9       | 34        | 0.27%   |
| 10      | 20        | 0.16%   |
| 13      | 12        | 0.1%    |
| 11      | 10        | 0.08%   |
| 12      | 9         | 0.07%   |
| 14      | 7         | 0.06%   |
| 19      | 4         | 0.03%   |
| 16      | 4         | 0.03%   |
| 21      | 3         | 0.02%   |
| 17      | 3         | 0.02%   |
| Unknown | 3         | 0.02%   |
| 29      | 2         | 0.02%   |
| 28      | 2         | 0.02%   |
| 27      | 2         | 0.02%   |
| 26      | 2         | 0.02%   |
| 18      | 2         | 0.02%   |
| 79      | 1         | 0.01%   |
| 70      | 1         | 0.01%   |
| 47      | 1         | 0.01%   |
| 46      | 1         | 0.01%   |
| 32      | 1         | 0.01%   |
| 23      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 8345      | 68.64%  |
| Yes       | 3813      | 31.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10418     | 85.98%  |
| No        | 1699      | 14.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8235      | 67.86%  |
| No        | 3901      | 32.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6806      | 55.85%  |
| No        | 5380      | 44.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 2537      | 20.89%  |
| Russia       | 1585      | 13.05%  |
| Germany      | 1238      | 10.19%  |
| France       | 783       | 6.45%   |
| Brazil       | 552       | 4.54%   |
| Spain        | 474       | 3.9%    |
| Italy        | 456       | 3.75%   |
| UK           | 349       | 2.87%   |
| Canada       | 306       | 2.52%   |
| Poland       | 289       | 2.38%   |
| Netherlands  | 205       | 1.69%   |
| Australia    | 195       | 1.61%   |
| Switzerland  | 189       | 1.56%   |
| China        | 167       | 1.37%   |
| Mexico       | 146       | 1.2%    |
| Sweden       | 132       | 1.09%   |
| India        | 127       | 1.05%   |
| Austria      | 121       | 1%      |
| Argentina    | 117       | 0.96%   |
| Belgium      | 109       | 0.9%    |
| Ukraine      | 105       | 0.86%   |
| Hungary      | 104       | 0.86%   |
| Finland      | 91        | 0.75%   |
| Czechia      | 91        | 0.75%   |
| Portugal     | 88        | 0.72%   |
| Turkey       | 86        | 0.71%   |
| Norway       | 74        | 0.61%   |
| Romania      | 63        | 0.52%   |
| Greece       | 61        | 0.5%    |
| Japan        | 59        | 0.49%   |
| Chile        | 57        | 0.47%   |
| Venezuela    | 56        | 0.46%   |
| Bulgaria     | 53        | 0.44%   |
| Ireland      | 49        | 0.4%    |
| Denmark      | 48        | 0.4%    |
| South Africa | 47        | 0.39%   |
| Indonesia    | 45        | 0.37%   |
| New Zealand  | 42        | 0.35%   |
| Colombia     | 42        | 0.35%   |
| Slovakia     | 39        | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Voronezh          | 857       | 6.7%    |
| Bangor            | 824       | 6.44%   |
| Dover-Foxcroft    | 304       | 2.38%   |
| Moscow            | 197       | 1.54%   |
| St Petersburg     | 148       | 1.16%   |
| Paris             | 129       | 1.01%   |
| Berlin            | 103       | 0.81%   |
| Vienna            | 80        | 0.63%   |
| Sao Paulo         | 79        | 0.62%   |
| Madrid            | 76        | 0.59%   |
| Seville           | 66        | 0.52%   |
| Milan             | 65        | 0.51%   |
| Zurich            | 64        | 0.5%    |
| Warsaw            | 61        | 0.48%   |
| Amsterdam         | 59        | 0.46%   |
| Sydney            | 54        | 0.42%   |
| Munich            | 52        | 0.41%   |
| Toronto           | 50        | 0.39%   |
| Hamburg           | 50        | 0.39%   |
| Frankfurt am Main | 50        | 0.39%   |
| Barcelona         | 48        | 0.38%   |
| Budapest          | 44        | 0.34%   |
| Perm              | 43        | 0.34%   |
| Prague            | 41        | 0.32%   |
| Rio de Janeiro    | 40        | 0.31%   |
| Helsinki          | 40        | 0.31%   |
| Melbourne         | 38        | 0.3%    |
| Falkenstein       | 37        | 0.29%   |
| London            | 36        | 0.28%   |
| Dublin            | 35        | 0.27%   |
| Cologne           | 34        | 0.27%   |
| Brisbane          | 34        | 0.27%   |
| Brasília         | 34        | 0.27%   |
| Athens            | 33        | 0.26%   |
| Stuttgart         | 32        | 0.25%   |
| Rome              | 32        | 0.25%   |
| Istanbul          | 32        | 0.25%   |
| Beijing           | 31        | 0.24%   |
| San José         | 28        | 0.22%   |
| New York          | 28        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2709      | 4183   | 15.54%  |
| WDC                         | 2432      | 4184   | 13.95%  |
| Seagate                     | 2213      | 3988   | 12.69%  |
| Toshiba                     | 1114      | 1661   | 6.39%   |
| Kingston                    | 1014      | 1325   | 5.82%   |
| Unknown                     | 941       | 1252   | 5.4%    |
| Crucial                     | 802       | 1082   | 4.6%    |
| SanDisk                     | 745       | 968    | 4.27%   |
| Hitachi                     | 489       | 702    | 2.8%    |
| Intel                       | 413       | 589    | 2.37%   |
| SK hynix                    | 378       | 476    | 2.17%   |
| Fujitsu                     | 304       | 324    | 1.74%   |
| HGST                        | 302       | 616    | 1.73%   |
| A-DATA Technology           | 296       | 494    | 1.7%    |
| Micron Technology           | 262       | 309    | 1.5%    |
| Apple                       | 248       | 319    | 1.42%   |
| China                       | 175       | 206    | 1%      |
| Unknown                     | 132       | 148    | 0.76%   |
| KIOXIA                      | 115       | 132    | 0.66%   |
| SPCC                        | 106       | 129    | 0.61%   |
| Transcend                   | 101       | 121    | 0.58%   |
| Phison                      | 101       | 136    | 0.58%   |
| PNY                         | 89        | 156    | 0.51%   |
| Patriot                     | 74        | 90     | 0.42%   |
| Intenso                     | 73        | 96     | 0.42%   |
| Corsair                     | 72        | 103    | 0.41%   |
| OCZ                         | 70        | 83     | 0.4%    |
| JMicron Technology          | 67        | 75     | 0.38%   |
| LITEON                      | 64        | 77     | 0.37%   |
| Hewlett-Packard             | 64        | 103    | 0.37%   |
| Silicon Motion              | 61        | 74     | 0.35%   |
| Netac                       | 57        | 142    | 0.33%   |
| Maxtor                      | 55        | 69     | 0.32%   |
| GOODRAM                     | 48        | 80     | 0.28%   |
| Kingston Technology Company | 46        | 58     | 0.26%   |
| Gigabyte Technology         | 46        | 54     | 0.26%   |
| Micron/Crucial Technology   | 40        | 48     | 0.23%   |
| Team                        | 39        | 68     | 0.22%   |
| SABRENT                     | 38        | 40     | 0.22%   |
| Apacer                      | 37        | 48     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                      | 239       | 1.23%   |
| Kingston SA400S37240G 240GB SSD                     | 210       | 1.08%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 138       | 0.71%   |
| Unknown                                             | 132       | 0.68%   |
| Seagate ST500DM002-1BD142 500GB                     | 129       | 0.66%   |
| Kingston SA400S37120G 120GB SSD                     | 129       | 0.66%   |
| Samsung SSD 860 EVO 500GB                           | 112       | 0.58%   |
| Kingston SA400S37480G 480GB SSD                     | 112       | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB                      | 108       | 0.56%   |
| Crucial CT500MX500SSD1 500GB                        | 108       | 0.56%   |
| Samsung SSD 850 EVO 250GB                           | 104       | 0.54%   |
| Crucial CT480BX500SSD1 480GB                        | 104       | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB                        | 101       | 0.52%   |
| Samsung SSD 860 EVO 250GB                           | 98        | 0.5%    |
| Kingston SV300S37A120G 120GB SSD                    | 96        | 0.49%   |
| Samsung SSD 860 EVO 1TB                             | 93        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB                         | 92        | 0.47%   |
| Seagate ST1000LM035-1RK172 1TB                      | 90        | 0.46%   |
| Toshiba DT01ACA050 500GB                            | 89        | 0.46%   |
| Unknown MMC Card  32GB                              | 84        | 0.43%   |
| Crucial CT240BX500SSD1 240GB                        | 82        | 0.42%   |
| Samsung SSD 850 EVO 500GB                           | 78        | 0.4%    |
| Apple SSD SM0128G 121GB                             | 77        | 0.4%    |
| Apple SSD AP0128H 121GB                             | 77        | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 76        | 0.39%   |
| Toshiba DT01ACA100 1TB                              | 74        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB                      | 67        | 0.34%   |
| Toshiba MQ01ABD100 1TB                              | 65        | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB                      | 63        | 0.32%   |
| HGST HTS721010A9E630 1TB                            | 62        | 0.32%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 61        | 0.31%   |
| Seagate ST1000DM003-1ER162 1TB                      | 61        | 0.31%   |
| SanDisk NVMe SSD Drive 1TB                          | 61        | 0.31%   |
| Samsung SSD 870 EVO 500GB                           | 59        | 0.3%    |
| Unknown MMC Card  64GB                              | 58        | 0.3%    |
| Samsung SSD 980 1TB                                 | 58        | 0.3%    |
| A-DATA SU800 512GB SSD                              | 55        | 0.28%   |
| Samsung SSD 980 PRO 1TB                             | 54        | 0.28%   |
| Toshiba MK1655GSXF 160GB                            | 53        | 0.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 51        | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2151      | 3872   | 33.25%  |
| WDC                 | 1846      | 3301   | 28.53%  |
| Toshiba             | 878       | 1359   | 13.57%  |
| Hitachi             | 488       | 700    | 7.54%   |
| Fujitsu             | 304       | 324    | 4.7%    |
| HGST                | 300       | 612    | 4.64%   |
| Samsung Electronics | 221       | 286    | 3.42%   |
| Unknown             | 54        | 68     | 0.83%   |
| Maxtor              | 52        | 60     | 0.8%    |
| Apple               | 38        | 44     | 0.59%   |
| Hewlett-Packard     | 13        | 31     | 0.2%    |
| TO Exter            | 11        | 12     | 0.17%   |
| Intenso             | 8         | 10     | 0.12%   |
| ASMT                | 8         | 16     | 0.12%   |
| IBM/Hitachi         | 6         | 7      | 0.09%   |
| External            | 6         | 8      | 0.09%   |
| ASMedia             | 6         | 6      | 0.09%   |
| JMicron Technology  | 5         | 9      | 0.08%   |
| HPE                 | 5         | 13     | 0.08%   |
| USB3.0              | 4         | 4      | 0.06%   |
| QNAP                | 4         | 6      | 0.06%   |
| IBM-ESXS            | 4         | 7      | 0.06%   |
| USB                 | 3         | 3      | 0.05%   |
| LaCie               | 3         | 3      | 0.05%   |
| StoreJet            | 2         | 2      | 0.03%   |
| SILICONMOTION       | 2         | 2      | 0.03%   |
| Pear 2TB            | 2         | 2      | 0.03%   |
| NETAPP              | 2         | 6      | 0.03%   |
| Inateck             | 2         | 2      | 0.03%   |
| IET                 | 2         | 2      | 0.03%   |
| IBM                 | 2         | 2      | 0.03%   |
| H/W                 | 2         | 10     | 0.03%   |
| DELLBOSS            | 2         | 3      | 0.03%   |
| Unknown             | 2         | 2      | 0.03%   |
| WD MediaMax         | 1         | 6      | 0.02%   |
| WALRAM              | 1         | 1      | 0.02%   |
| USB 3.0             | 1         | 2      | 0.02%   |
| Unknown (CF)        | 1         | 1      | 0.02%   |
| Synology            | 1         | 1      | 0.02%   |
| SYMTEC              | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1237      | 1761   | 21.42%  |
| Kingston            | 835       | 1100   | 14.46%  |
| Crucial             | 685       | 916    | 11.86%  |
| SanDisk             | 464       | 615    | 8.03%   |
| WDC                 | 283       | 363    | 4.9%    |
| A-DATA Technology   | 212       | 371    | 3.67%   |
| China               | 172       | 203    | 2.98%   |
| Intel               | 167       | 248    | 2.89%   |
| Apple               | 122       | 139    | 2.11%   |
| Micron Technology   | 104       | 135    | 1.8%    |
| Transcend           | 88        | 107    | 1.52%   |
| SPCC                | 84        | 101    | 1.45%   |
| Toshiba             | 83        | 106    | 1.44%   |
| SK hynix            | 79        | 94     | 1.37%   |
| OCZ                 | 70        | 83     | 1.21%   |
| PNY                 | 69        | 129    | 1.19%   |
| Intenso             | 61        | 78     | 1.06%   |
| Patriot             | 60        | 70     | 1.04%   |
| LITEON              | 52        | 62     | 0.9%    |
| Netac               | 51        | 136    | 0.88%   |
| GOODRAM             | 42        | 61     | 0.73%   |
| Team                | 34        | 60     | 0.59%   |
| JMicron Technology  | 30        | 32     | 0.52%   |
| Apacer              | 30        | 36     | 0.52%   |
| LITEONIT            | 28        | 38     | 0.48%   |
| Corsair             | 28        | 33     | 0.48%   |
| Hewlett-Packard     | 27        | 36     | 0.47%   |
| Plextor             | 24        | 30     | 0.42%   |
| Unknown             | 23        | 28     | 0.4%    |
| Seagate             | 21        | 27     | 0.36%   |
| Gigabyte Technology | 21        | 23     | 0.36%   |
| KingDian            | 20        | 21     | 0.35%   |
| ASMT                | 18        | 22     | 0.31%   |
| Lexar               | 16        | 19     | 0.28%   |
| KingSpec            | 14        | 15     | 0.24%   |
| Unknown             | 13        | 16     | 0.23%   |
| LDLC                | 13        | 13     | 0.23%   |
| Mushkin             | 12        | 13     | 0.21%   |
| KIOXIA-EXCERIA      | 12        | 15     | 0.21%   |
| FORESEE             | 11        | 12     | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 5442      | 10858  | 34.84%  |
| SSD     | 5041      | 7807   | 32.27%  |
| NVMe    | 3962      | 5864   | 25.36%  |
| MMC     | 971       | 1256   | 6.22%   |
| Unknown | 204       | 308    | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 8514      | 17733  | 60.48%  |
| NVMe | 3920      | 5788   | 27.84%  |
| MMC  | 971       | 1256   | 6.9%    |
| SAS  | 673       | 1316   | 4.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives  | Percent |
|-------------|-----------|---------|---------|
| 0.01-0.5    | 6478      | 9674    | 57.88%  |
| 0.51-1.0    | 2832      | 4555    | 25.3%   |
| 1.01-2.0    | 856       | 1643    | 7.65%   |
| 3.01-4.0    | 385       | 988     | 3.44%   |
| 4.01-10.0   | 332       | 1026    | 2.97%   |
| 2.01-3.0    | 222       | 437     | 1.98%   |
| 10.01-20.0  | 84        | 337     | 0.75%   |
| 20.01-50.0  | 1         | 1       | 0.01%   |
| 50.01-100.0 | 1         | 4       | 0.01%   |
| 0           | 1         | Unknown | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2785      | 22.19%  |
| 251-500        | 2349      | 18.72%  |
| Unknown        | 1896      | 15.11%  |
| 501-1000       | 1619      | 12.9%   |
| 1001-2000      | 859       | 6.84%   |
| 51-100         | 837       | 6.67%   |
| More than 3000 | 718       | 5.72%   |
| 1-20           | 639       | 5.09%   |
| 21-50          | 517       | 4.12%   |
| 2001-3000      | 331       | 2.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 4446      | 34.44%  |
| Unknown        | 1896      | 14.69%  |
| 21-50          | 1469      | 11.38%  |
| 101-250        | 1447      | 11.21%  |
| 51-100         | 1155      | 8.95%   |
| 251-500        | 926       | 7.17%   |
| 501-1000       | 676       | 5.24%   |
| 1001-2000      | 407       | 3.15%   |
| More than 3000 | 303       | 2.35%   |
| 2001-3000      | 159       | 1.23%   |
| 0              | 25        | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB      | 32        | 47     | 1.8%    |
| Kingston SV300S37A120G 120GB SSD     | 26        | 28     | 1.46%   |
| Fujitsu MHZ2160BH FFS G1 160GB       | 25        | 25     | 1.41%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 22        | 38     | 1.24%   |
| Seagate ST9500325AS 500GB            | 17        | 19     | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 14        | 17     | 0.79%   |
| Toshiba MQ01ABD100 1TB               | 13        | 14     | 0.73%   |
| Seagate ST3500418AS 500GB            | 13        | 19     | 0.73%   |
| Hitachi HDS721050CLA362 500GB        | 12        | 14     | 0.68%   |
| Seagate ST9500420AS 500GB            | 11        | 11     | 0.62%   |
| Seagate ST31000528AS 1TB             | 11        | 13     | 0.62%   |
| Seagate ST1000DM003-9YN162 1TB       | 11        | 12     | 0.62%   |
| Hitachi HTS543216L9SA02 160GB        | 11        | 11     | 0.62%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 9         | 9      | 0.51%   |
| Toshiba MK1655GSXF 160GB             | 9         | 9      | 0.51%   |
| Toshiba MK1653GSX 160GB              | 9         | 9      | 0.51%   |
| Seagate ST3250318AS 250GB            | 9         | 10     | 0.51%   |
| Seagate ST31500341AS 1TB             | 9         | 15     | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB       | 9         | 12     | 0.51%   |
| HGST HTS725050A7E630 500GB           | 9         | 12     | 0.51%   |
| Toshiba DT01ACA050 500GB             | 8         | 9      | 0.45%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 8         | 10     | 0.45%   |
| Seagate ST500LM021-1KJ152 500GB      | 8         | 8      | 0.45%   |
| Seagate ST3250410AS 250GB            | 8         | 9      | 0.45%   |
| Hitachi HTS545050B9A300 500GB        | 8         | 8      | 0.45%   |
| HGST HTS541010A9E680 1TB             | 8         | 8      | 0.45%   |
| WDC WD20EARX-00PASB0 2TB             | 7         | 9      | 0.39%   |
| WDC WD20EARS-00MVWB0 2TB             | 7         | 7      | 0.39%   |
| Toshiba MQ01ABF050 500GB             | 7         | 7      | 0.39%   |
| Toshiba DT01ACA100 1TB               | 7         | 9      | 0.39%   |
| Seagate ST500LT012-9WS142 500GB      | 7         | 8      | 0.39%   |
| Seagate ST3320613AS 320GB            | 7         | 7      | 0.39%   |
| Seagate ST3160815AS 160GB            | 7         | 9      | 0.39%   |
| Seagate ST250DM000-1BD141 250GB      | 7         | 7      | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB       | 7         | 8      | 0.39%   |
| Seagate ST1000DM003-1CH162 1TB       | 7         | 7      | 0.39%   |
| Kingston SA400S37240G 240GB SSD      | 7         | 8      | 0.39%   |
| HGST HTS545050A7E680 500GB           | 7         | 7      | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 6         | 6      | 0.34%   |
| WDC WD5000AAKX-001CA0 500GB          | 6         | 8      | 0.34%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 436       | 594    | 25.5%   |
| WDC                 | 359       | 511    | 20.99%  |
| Hitachi             | 159       | 196    | 9.3%    |
| Samsung Electronics | 134       | 150    | 7.84%   |
| Toshiba             | 125       | 141    | 7.31%   |
| Kingston            | 69        | 79     | 4.04%   |
| Intel               | 54        | 71     | 3.16%   |
| HGST                | 49        | 53     | 2.87%   |
| Fujitsu             | 41        | 43     | 2.4%    |
| Crucial             | 37        | 44     | 2.16%   |
| SK hynix            | 35        | 42     | 2.05%   |
| SanDisk             | 29        | 34     | 1.7%    |
| A-DATA Technology   | 29        | 37     | 1.7%    |
| Micron Technology   | 23        | 30     | 1.35%   |
| Maxtor              | 21        | 23     | 1.23%   |
| OCZ                 | 10        | 11     | 0.58%   |
| LITEON              | 7         | 7      | 0.41%   |
| Corsair             | 7         | 7      | 0.41%   |
| China               | 7         | 7      | 0.41%   |
| Apple               | 6         | 7      | 0.35%   |
| LITEONIT            | 5         | 6      | 0.29%   |
| KingDian            | 5         | 5      | 0.29%   |
| JMicron Technology  | 4         | 5      | 0.23%   |
| SSSTC               | 3         | 3      | 0.18%   |
| SPCC                | 3         | 3      | 0.18%   |
| KingSpec            | 3         | 3      | 0.18%   |
| Hewlett-Packard     | 3         | 5      | 0.18%   |
| Unknown             | 2         | 2      | 0.12%   |
| Transcend           | 2         | 2      | 0.12%   |
| ShiJi               | 2         | 5      | 0.12%   |
| PNY                 | 2         | 7      | 0.12%   |
| Plextor             | 2         | 3      | 0.12%   |
| Netac               | 2         | 3      | 0.12%   |
| Lenovo              | 2         | 2      | 0.12%   |
| IBM/Hitachi         | 2         | 2      | 0.12%   |
| IBM                 | 2         | 2      | 0.12%   |
| Apacer              | 2         | 2      | 0.12%   |
| Unknown             | 2         | 2      | 0.12%   |
| ZHITAI              | 1         | 1      | 0.06%   |
| Zheino              | 1         | 1      | 0.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 436       | 594    | 34.69%  |
| WDC                 | 344       | 494    | 27.37%  |
| Hitachi             | 159       | 196    | 12.65%  |
| Toshiba             | 121       | 137    | 9.63%   |
| Samsung Electronics | 68        | 74     | 5.41%   |
| HGST                | 49        | 53     | 3.9%    |
| Fujitsu             | 41        | 43     | 3.26%   |
| Maxtor              | 21        | 23     | 1.67%   |
| Apple               | 5         | 6      | 0.4%    |
| Hewlett-Packard     | 3         | 5      | 0.24%   |
| JMicron Technology  | 2         | 3      | 0.16%   |
| IBM/Hitachi         | 2         | 2      | 0.16%   |
| IBM                 | 2         | 2      | 0.16%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |
| ASMT                | 1         | 2      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1175      | 1637   | 72.31%  |
| SSD     | 374       | 443    | 23.02%  |
| NVMe    | 75        | 95     | 4.62%   |
| Unknown | 1         | 1      | 0.06%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2         | 3      | 5.56%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 2         | 5      | 5.56%   |
| WDC WD5000BEVT-35A0RT0 500GB                     | 1         | 1      | 2.78%   |
| WDC WD4001FFSX-68JNUN0 4TB                       | 1         | 1      | 2.78%   |
| WDC WD30EZRS-00J99B0 3TB                         | 1         | 1      | 2.78%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 2.78%   |
| Toshiba MK6465GSX 640GB                          | 1         | 1      | 2.78%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.78%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 2.78%   |
| Seagate ST500DM005 HD502HJ 500GB                 | 1         | 1      | 2.78%   |
| Seagate ST3500830AS 500GB                        | 1         | 1      | 2.78%   |
| Seagate ST3500630A 500GB                         | 1         | 1      | 2.78%   |
| Seagate ST3500418ASQ 500GB                       | 1         | 1      | 2.78%   |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 2.78%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB      | 1         | 1      | 2.78%   |
| Samsung Electronics SSD 980 250GB                | 1         | 1      | 2.78%   |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 2.78%   |
| Samsung Electronics SP0802N 80GB                 | 1         | 1      | 2.78%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB     | 1         | 1      | 2.78%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD  | 1         | 1      | 2.78%   |
| Samsung Electronics HE103SJ 1TB                  | 1         | 2      | 2.78%   |
| Samsung Electronics HD253GJ 250GB                | 1         | 1      | 2.78%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 2      | 2.78%   |
| KingDian S400 120GB                              | 1         | 1      | 2.78%   |
| Intel SSDSC2KW256G8 256GB                        | 1         | 1      | 2.78%   |
| Inland SATA SSD 128GB                            | 1         | 1      | 2.78%   |
| IBM-ESXS ST9300605SS 304GB                       | 1         | 2      | 2.78%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 2.78%   |
| HGST HUH728080ALN600 8TB                         | 1         | 1      | 2.78%   |
| HGST HTS725050A7E630 500GB                       | 1         | 2      | 2.78%   |
| HGST HDN724040ALE640 4TB                         | 1         | 1      | 2.78%   |
| Hewlett-Packard SSD S700 500GB                   | 1         | 2      | 2.78%   |
| Crucial CT500P2SSD8 500GB                        | 1         | 1      | 2.78%   |
| Crucial CT1000P1SSD8 1TB                         | 1         | 1      | 2.78%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 16     | 30.56%  |
| Seagate             | 9         | 10     | 25%     |
| WDC                 | 3         | 3      | 8.33%   |
| HGST                | 3         | 4      | 8.33%   |
| Toshiba             | 2         | 2      | 5.56%   |
| Crucial             | 2         | 2      | 5.56%   |
| KingDian            | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| Inland              | 1         | 1      | 2.78%   |
| IBM-ESXS            | 1         | 2      | 2.78%   |
| Hitachi             | 1         | 2      | 2.78%   |
| Hewlett-Packard     | 1         | 2      | 2.78%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 8225      | 16509  | 60.73%  |
| Detected | 3701      | 7359   | 27.33%  |
| Malfunc  | 1578      | 2176   | 11.65%  |
| Failed   | 36        | 46     | 0.27%   |
| Limited  | 3         | 3      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7302      | 48.78%  |
| AMD                              | 2057      | 13.74%  |
| Samsung Electronics              | 1521      | 10.16%  |
| SanDisk                          | 625       | 4.18%   |
| Nvidia                           | 503       | 3.36%   |
| SK hynix                         | 283       | 1.89%   |
| ASMedia Technology               | 276       | 1.84%   |
| Phison Electronics               | 243       | 1.62%   |
| Kingston Technology Company      | 235       | 1.57%   |
| Marvell Technology Group         | 187       | 1.25%   |
| Toshiba America Info Systems     | 172       | 1.15%   |
| Micron/Crucial Technology        | 168       | 1.12%   |
| Micron Technology                | 160       | 1.07%   |
| JMicron Technology               | 131       | 0.88%   |
| Silicon Motion                   | 118       | 0.79%   |
| LSI Logic / Symbios Logic        | 117       | 0.78%   |
| ADATA Technology                 | 117       | 0.78%   |
| KIOXIA                           | 116       | 0.77%   |
| Broadcom / LSI                   | 100       | 0.67%   |
| Apple                            | 91        | 0.61%   |
| VIA Technologies                 | 51        | 0.34%   |
| Adaptec                          | 38        | 0.25%   |
| MAXIO Technology (Hangzhou)      | 37        | 0.25%   |
| Solid State Storage Technology   | 34        | 0.23%   |
| Realtek Semiconductor            | 30        | 0.2%    |
| Hewlett-Packard                  | 29        | 0.19%   |
| Silicon Image                    | 28        | 0.19%   |
| Union Memory (Shenzhen)          | 24        | 0.16%   |
| Seagate Technology               | 24        | 0.16%   |
| Silicon Integrated Systems [SiS] | 20        | 0.13%   |
| Lite-On Technology               | 19        | 0.13%   |
| Shenzhen Longsys Electronics     | 15        | 0.1%    |
| INNOGRIT                         | 12        | 0.08%   |
| Yangtze Memory Technologies      | 11        | 0.07%   |
| Biwin Storage Technology         | 9         | 0.06%   |
| Transcend                        | 6         | 0.04%   |
| Lenovo                           | 6         | 0.04%   |
| IBM                              | 5         | 0.03%   |
| 3ware                            | 5         | 0.03%   |
| ULi Electronics                  | 4         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1400      | 8.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 743       | 4.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 523       | 3.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 521       | 3.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 403       | 2.34%   |
| Nvidia MCP79 AHCI Controller                                                   | 379       | 2.2%    |
| AMD 400 Series Chipset SATA Controller                                         | 310       | 1.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 293       | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 285       | 1.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 275       | 1.6%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 264       | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 262       | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 261       | 1.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 257       | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 245       | 1.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 242       | 1.41%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 237       | 1.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 230       | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 230       | 1.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 202       | 1.17%   |
| Intel Comet Lake SATA AHCI Controller                                          | 195       | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 189       | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 183       | 1.06%   |
| AMD 500 Series Chipset SATA Controller                                         | 181       | 1.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 162       | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 156       | 0.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 152       | 0.88%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 150       | 0.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 143       | 0.83%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 125       | 0.73%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 125       | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 125       | 0.73%   |
| Intel SATA Controller [RAID mode]                                              | 121       | 0.7%    |
| Intel Tiger Lake-LP SATA Controller                                            | 114       | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 113       | 0.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 113       | 0.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 112       | 0.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 111       | 0.64%   |
| Phison E12 NVMe Controller                                                     | 109       | 0.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 108       | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 8410      | 55.75%  |
| NVMe | 3931      | 26.06%  |
| IDE  | 1590      | 10.54%  |
| RAID | 950       | 6.3%    |
| SAS  | 155       | 1.03%   |
| SCSI | 49        | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9124      | 75.47%  |
| AMD                   | 2546      | 21.06%  |
| ARM                   | 354       | 2.93%   |
| Unknown               | 16        | 0.13%   |
| CentaurHauls          | 12        | 0.1%    |
| sifive,u74-mc         | 10        | 0.08%   |
| Qualcomm              | 6         | 0.05%   |
| CHRP IBM,8233-E8B     | 5         | 0.04%   |
| Phytium               | 4         | 0.03%   |
| sifive,bullet0        | 3         | 0.02%   |
| Marvell Semiconductor | 2         | 0.02%   |
| Loongson              | 2         | 0.02%   |
| CHRP IBM,9131-52A     | 2         | 0.02%   |
| PowerNV FP5466G2      | 1         | 0.01%   |
| PowerNV C829UAG3      | 1         | 0.01%   |
| HISILICON             | 1         | 0.01%   |
| AppliedMicro          | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 357       | 2.94%   |
| ARM Processor                                 | 281       | 2.32%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 214       | 1.76%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 152       | 1.25%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 136       | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 100       | 0.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 99        | 0.82%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 99        | 0.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 93        | 0.77%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 90        | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 85        | 0.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 82        | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 81        | 0.67%   |
| AMD Ryzen 5 3600 6-Core Processor             | 78        | 0.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 72        | 0.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 71        | 0.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 70        | 0.58%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 67        | 0.55%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 63        | 0.52%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 63        | 0.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 62        | 0.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 62        | 0.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 58        | 0.48%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 56        | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 52        | 0.43%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 51        | 0.42%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 50        | 0.41%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 50        | 0.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 48        | 0.4%    |
| AMD Ryzen 9 5950X 16-Core Processor           | 46        | 0.38%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 46        | 0.38%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 45        | 0.37%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 45        | 0.37%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 44        | 0.36%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 44        | 0.36%   |
| Intel Celeron N5105 @ 2.00GHz                 | 44        | 0.36%   |
| Intel 12th Gen Core i5-1235U                  | 43        | 0.35%   |
| Intel 12th Gen Core i7-12700H                 | 42        | 0.35%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 42        | 0.35%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 42        | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2309      | 19.07%  |
| Intel Core i7           | 1683      | 13.9%   |
| Other                   | 1384      | 11.43%  |
| Intel Core i3           | 804       | 6.64%   |
| Intel Celeron           | 791       | 6.53%   |
| Intel Core 2 Duo        | 774       | 6.39%   |
| AMD Ryzen 5             | 629       | 5.19%   |
| AMD Ryzen 7             | 504       | 4.16%   |
| Intel Xeon              | 502       | 4.15%   |
| Intel Pentium           | 344       | 2.84%   |
| Intel Atom              | 251       | 2.07%   |
| AMD Ryzen 9             | 216       | 1.78%   |
| AMD FX                  | 142       | 1.17%   |
| Intel Pentium Dual-Core | 124       | 1.02%   |
| Intel Core 2            | 120       | 0.99%   |
| AMD Ryzen 3             | 115       | 0.95%   |
| Intel Core 2 Quad       | 77        | 0.64%   |
| AMD Ryzen 7 PRO         | 74        | 0.61%   |
| AMD A6                  | 59        | 0.49%   |
| Intel Core i9           | 57        | 0.47%   |
| AMD A8                  | 57        | 0.47%   |
| AMD Ryzen 5 PRO         | 52        | 0.43%   |
| AMD A10                 | 50        | 0.41%   |
| AMD A4                  | 45        | 0.37%   |
| AMD Athlon              | 44        | 0.36%   |
| Intel Pentium Dual      | 41        | 0.34%   |
| Intel Pentium 4         | 40        | 0.33%   |
| AMD Ryzen Threadripper  | 40        | 0.33%   |
| Intel Pentium Silver    | 39        | 0.32%   |
| AMD Athlon 64 X2        | 38        | 0.31%   |
| Intel Pentium M         | 37        | 0.31%   |
| Intel Genuine           | 37        | 0.31%   |
| AMD Phenom II X4        | 37        | 0.31%   |
| AMD Athlon II X2        | 35        | 0.29%   |
| Intel Pentium Gold      | 34        | 0.28%   |
| AMD E                   | 34        | 0.28%   |
| ARM Allwinner           | 28        | 0.23%   |
| AMD GX                  | 24        | 0.2%    |
| AMD E1                  | 24        | 0.2%    |
| Intel Xeon Silver       | 21        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4729      | 39.02%  |
| 4       | 4089      | 33.74%  |
| 6       | 1122      | 9.26%   |
| 8       | 908       | 7.49%   |
| 1       | 377       | 3.11%   |
| 12      | 254       | 2.1%    |
| 16      | 165       | 1.36%   |
| 10      | 147       | 1.21%   |
| 14      | 82        | 0.68%   |
| Unknown | 64        | 0.53%   |
| 3       | 54        | 0.45%   |
| 24      | 48        | 0.4%    |
| 32      | 23        | 0.19%   |
| 20      | 15        | 0.12%   |
| 28      | 8         | 0.07%   |
| 18      | 5         | 0.04%   |
| 64      | 4         | 0.03%   |
| 48      | 4         | 0.03%   |
| 44      | 4         | 0.03%   |
| 22      | 4         | 0.03%   |
| 40      | 3         | 0.02%   |
| 36      | 3         | 0.02%   |
| 5       | 3         | 0.02%   |
| 192     | 1         | 0.01%   |
| 128     | 1         | 0.01%   |
| 96      | 1         | 0.01%   |
| 80      | 1         | 0.01%   |
| 56      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 11777     | 97.37%  |
| 2       | 238       | 1.97%   |
| Unknown | 63        | 0.52%   |
| 4       | 8         | 0.07%   |
| 3       | 6         | 0.05%   |
| 16      | 1         | 0.01%   |
| 8       | 1         | 0.01%   |
| 0       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 7422      | 61.29%  |
| 1       | 4616      | 38.12%  |
| Unknown | 64        | 0.53%   |
| 4       | 7         | 0.06%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 11624     | 96.07%  |
| Unknown        | 263       | 2.17%   |
| 32-bit         | 182       | 1.5%    |
| 64-bit         | 30        | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3203      | 25.78%  |
| 0x1067a    | 703       | 5.66%   |
| 0x306a9    | 494       | 3.98%   |
| 0x306c3    | 491       | 3.95%   |
| 0x206a7    | 480       | 3.86%   |
| 0x806c1    | 381       | 3.07%   |
| 0x306d4    | 292       | 2.35%   |
| 0x806ec    | 261       | 2.1%    |
| 0x906ea    | 252       | 2.03%   |
| 0x506e3    | 229       | 1.84%   |
| 0x806e9    | 206       | 1.66%   |
| 0x806ea    | 199       | 1.6%    |
| 0x40651    | 166       | 1.34%   |
| 0x406e3    | 165       | 1.33%   |
| 0x30678    | 161       | 1.3%    |
| 0x906e9    | 160       | 1.29%   |
| 0x08108109 | 152       | 1.22%   |
| 0x406c4    | 143       | 1.15%   |
| 0x08701021 | 136       | 1.09%   |
| 0x0a50000c | 111       | 0.89%   |
| 0x20655    | 107       | 0.86%   |
| 0x08600106 | 101       | 0.81%   |
| 0xa0653    | 100       | 0.8%    |
| 0x706a8    | 92        | 0.74%   |
| 0x906c0    | 91        | 0.73%   |
| 0x906a3    | 89        | 0.72%   |
| 0xa0652    | 85        | 0.68%   |
| 0x6f6      | 84        | 0.68%   |
| 0x6fd      | 83        | 0.67%   |
| 0x10676    | 83        | 0.67%   |
| 0x906eb    | 78        | 0.63%   |
| 0x08608103 | 78        | 0.63%   |
| 0x0a50000d | 77        | 0.62%   |
| 0x506c9    | 76        | 0.61%   |
| 0x0800820d | 72        | 0.58%   |
| 0x906a4    | 69        | 0.56%   |
| 0x706e5    | 64        | 0.52%   |
| 0x0a201016 | 64        | 0.52%   |
| 0x906ed    | 60        | 0.48%   |
| 0x08108102 | 60        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1701      | 14.03%  |
| Haswell          | 949       | 7.82%   |
| Penryn           | 897       | 7.4%    |
| Unknown          | 853       | 7.03%   |
| SandyBridge      | 712       | 5.87%   |
| IvyBridge        | 707       | 5.83%   |
| Skylake          | 597       | 4.92%   |
| TigerLake        | 462       | 3.81%   |
| Zen 2            | 455       | 3.75%   |
| Silvermont       | 431       | 3.55%   |
| Zen 3            | 430       | 3.55%   |
| Broadwell        | 389       | 3.21%   |
| Zen+             | 382       | 3.15%   |
| Core             | 326       | 2.69%   |
| CometLake        | 324       | 2.67%   |
| Westmere         | 270       | 2.23%   |
| Alderlake Hybrid | 255       | 2.1%    |
| Zen              | 207       | 1.71%   |
| K10              | 171       | 1.41%   |
| Goldmont plus    | 171       | 1.41%   |
| Piledriver       | 159       | 1.31%   |
| IceLake          | 150       | 1.24%   |
| Bonnell          | 138       | 1.14%   |
| Excavator        | 136       | 1.12%   |
| Goldmont         | 106       | 0.87%   |
| Tremont          | 105       | 0.87%   |
| Nehalem          | 97        | 0.8%    |
| P6               | 85        | 0.7%    |
| K8 Hammer        | 82        | 0.68%   |
| Bobcat           | 79        | 0.65%   |
| NetBurst         | 68        | 0.56%   |
| Jaguar           | 51        | 0.42%   |
| Steamroller      | 47        | 0.39%   |
| Puma             | 46        | 0.38%   |
| Bulldozer        | 36        | 0.3%    |
| K10 Llano        | 27        | 0.22%   |
| K8 & K10 hybrid  | 10        | 0.08%   |
| Gracemont        | 9         | 0.07%   |
| K6               | 7         | 0.06%   |
| Geode            | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 6926      | 51.83%  |
| Nvidia                                       | 3328      | 24.91%  |
| AMD                                          | 2703      | 20.23%  |
| Matrox Electronics Systems                   | 196       | 1.47%   |
| ASPEED Technology                            | 165       | 1.23%   |
| VIA Technologies                             | 13        | 0.1%    |
| Silicon Integrated Systems [SiS]             | 13        | 0.1%    |
| Zhaoxin                                      | 4         | 0.03%   |
| Loongson Technology                          | 3         | 0.02%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.01%   |
| S3 Graphics                                  | 2         | 0.01%   |
| Huawei Technologies                          | 2         | 0.01%   |
| Silicon Motion                               | 1         | 0.01%   |
| Neomagic                                     | 1         | 0.01%   |
| Cirrus Logic                                 | 1         | 0.01%   |
| ATI Technologies                             | 1         | 0.01%   |
| 3DLabs                                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 477       | 3.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 421       | 3.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 361       | 2.62%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 355       | 2.57%   |
| Intel UHD Graphics 620                                                                   | 268       | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 258       | 1.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 257       | 1.86%   |
| Intel HD Graphics 620                                                                    | 252       | 1.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 221       | 1.6%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 221       | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 218       | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 211       | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 208       | 1.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 203       | 1.47%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 197       | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 191       | 1.38%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 186       | 1.35%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 165       | 1.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 165       | 1.2%    |
| Intel HD Graphics 6000                                                                   | 162       | 1.17%   |
| Intel HD Graphics 530                                                                    | 160       | 1.16%   |
| Intel HD Graphics 5500                                                                   | 158       | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 150       | 1.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 144       | 1.04%   |
| Intel HD Graphics 630                                                                    | 140       | 1.02%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 134       | 0.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 129       | 0.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 128       | 0.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 126       | 0.91%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 122       | 0.88%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 116       | 0.84%   |
| AMD Lucienne                                                                             | 114       | 0.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 102       | 0.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 97        | 0.7%    |
| Intel JasperLake [UHD Graphics]                                                          | 96        | 0.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 96        | 0.7%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 93        | 0.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 90        | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 86        | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 86        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 5457      | 44.89%  |
| 1 x AMD                           | 2178      | 17.92%  |
| 1 x Nvidia                        | 2014      | 16.57%  |
| Intel + Nvidia                    | 1105      | 9.09%   |
| Other                             | 425       | 3.5%    |
| Intel + AMD                       | 220       | 1.81%   |
| 1 x Matrox                        | 186       | 1.53%   |
| AMD + Nvidia                      | 155       | 1.28%   |
| 1 x ASPEED                        | 134       | 1.1%    |
| 2 x AMD                           | 128       | 1.05%   |
| 2 x Intel                         | 40        | 0.33%   |
| 2 x Nvidia                        | 19        | 0.16%   |
| Nvidia + ASPEED                   | 17        | 0.14%   |
| 1 x VIA                           | 13        | 0.11%   |
| 1 x SiS                           | 13        | 0.11%   |
| AMD + ASPEED                      | 11        | 0.09%   |
| Nvidia + Matrox                   | 7         | 0.06%   |
| Intel + 2 x Nvidia                | 5         | 0.04%   |
| 1 x Zhaoxin                       | 4         | 0.03%   |
| AMD + Matrox                      | 4         | 0.03%   |
| 2 x Nvidia + 1 x ASPEED           | 3         | 0.02%   |
| 3 x AMD                           | 2         | 0.02%   |
| 1 x S3 Graphics                   | 2         | 0.02%   |
| 2 x Nvidia + 1 x Matrox           | 1         | 0.01%   |
| 2 x Loongson Technology           | 1         | 0.01%   |
| 2 x Intel + 1 x Nvidia            | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.01%   |
| 1 x XGI                           | 1         | 0.01%   |
| 1 x Silicon Motion                | 1         | 0.01%   |
| Nvidia + XGI                      | 1         | 0.01%   |
| Nvidia + Huawei Technologies      | 1         | 0.01%   |
| 1 x Neomagic                      | 1         | 0.01%   |
| 1 x Loongson Technology           | 1         | 0.01%   |
| 1 x Huawei Technologies           | 1         | 0.01%   |
| 1 x Cirrus Logic                  | 1         | 0.01%   |
| AMD + Loongson Technology         | 1         | 0.01%   |
| AMD + 3DLabs                      | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 8975      | 73.43%  |
| Unknown     | 1992      | 16.3%   |
| Proprietary | 1255      | 10.27%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 8573      | 69.81%  |
| 0.01-0.5       | 1244      | 10.13%  |
| 1.01-2.0       | 791       | 6.44%   |
| 0.51-1.0       | 504       | 4.1%    |
| 3.01-4.0       | 500       | 4.07%   |
| 7.01-8.0       | 312       | 2.54%   |
| 5.01-6.0       | 174       | 1.42%   |
| 8.01-16.0      | 88        | 0.72%   |
| 2.01-3.0       | 61        | 0.5%    |
| 16.01-24.0     | 24        | 0.2%    |
| 4.01-5.0       | 6         | 0.05%   |
| More than 64.0 | 1         | 0.01%   |
| 32.01-64.0     | 1         | 0.01%   |
| 24.01-32.0     | 1         | 0.01%   |
| 0              | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1370      | 12.1%   |
| Samsung Electronics     | 1230      | 10.87%  |
| BOE                     | 950       | 8.39%   |
| LG Display              | 819       | 7.24%   |
| Chimei Innolux          | 818       | 7.23%   |
| Apple                   | 736       | 6.5%    |
| Dell                    | 711       | 6.28%   |
| Goldstar                | 533       | 4.71%   |
| Hewlett-Packard         | 355       | 3.14%   |
| Acer                    | 310       | 2.74%   |
| BenQ                    | 295       | 2.61%   |
| Philips                 | 274       | 2.42%   |
| AOC                     | 265       | 2.34%   |
| Lenovo                  | 244       | 2.16%   |
| Ancor Communications    | 226       | 2%      |
| Sharp                   | 163       | 1.44%   |
| Iiyama                  | 144       | 1.27%   |
| ViewSonic               | 132       | 1.17%   |
| InfoVision              | 116       | 1.02%   |
| Chi Mei Optoelectronics | 110       | 0.97%   |
| Unknown                 | 103       | 0.91%   |
| ASUSTek Computer        | 94        | 0.83%   |
| PANDA                   | 89        | 0.79%   |
| Eizo                    | 67        | 0.59%   |
| Sony                    | 64        | 0.57%   |
| LG Electronics          | 55        | 0.49%   |
| NEC Computers           | 54        | 0.48%   |
| HannStar                | 53        | 0.47%   |
| CSO                     | 50        | 0.44%   |
| LG Philips              | 43        | 0.38%   |
| Unknown                 | 30        | 0.27%   |
| Fujitsu Siemens         | 28        | 0.25%   |
| MSI                     | 26        | 0.23%   |
| Vizio                   | 23        | 0.2%    |
| Panasonic               | 23        | 0.2%    |
| Medion                  | 22        | 0.19%   |
| Sceptre Tech            | 21        | 0.19%   |
| RTK                     | 19        | 0.17%   |
| CPT                     | 19        | 0.17%   |
| Toshiba                 | 18        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                  | 210       | 1.8%    |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 191       | 1.64%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch        | 112       | 0.96%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                  | 70        | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 61        | 0.52%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 59        | 0.51%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 48        | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 48        | 0.41%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 48        | 0.41%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 45        | 0.39%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 42        | 0.36%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 38        | 0.33%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 35        | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 32        | 0.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 32        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 31        | 0.27%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 31        | 0.27%   |
| Unknown                                                               | 30        | 0.26%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 29        | 0.25%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 28        | 0.24%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 27        | 0.23%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 26        | 0.22%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 25        | 0.21%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 25        | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 24        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 24        | 0.21%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 24        | 0.21%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                  | 23        | 0.2%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 21        | 0.18%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                | 20        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 20        | 0.17%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 20        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 20        | 0.17%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 19        | 0.16%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 19        | 0.16%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 19        | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 18        | 0.15%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 18        | 0.15%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 18        | 0.15%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 18        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4523      | 41.65%  |
| 1366x768 (WXGA)    | 1811      | 16.68%  |
| 3840x2160 (4K)     | 636       | 5.86%   |
| 1280x800 (WXGA)    | 618       | 5.69%   |
| 2560x1440 (QHD)    | 498       | 4.59%   |
| 1280x1024 (SXGA)   | 402       | 3.7%    |
| 1600x900 (HD+)     | 365       | 3.36%   |
| 1920x1200 (WUXGA)  | 332       | 3.06%   |
| 1440x900 (WXGA+)   | 269       | 2.48%   |
| 1680x1050 (WSXGA+) | 253       | 2.33%   |
| Unknown            | 138       | 1.27%   |
| 2560x1080          | 99        | 0.91%   |
| 3440x1440          | 96        | 0.88%   |
| 1024x600           | 81        | 0.75%   |
| 2560x1600          | 79        | 0.73%   |
| 1024x768 (XGA)     | 71        | 0.65%   |
| 1360x768           | 66        | 0.61%   |
| 2288x1287          | 61        | 0.56%   |
| 3840x1080          | 52        | 0.48%   |
| 1600x1200          | 45        | 0.41%   |
| 3840x2400          | 37        | 0.34%   |
| 2880x1800          | 34        | 0.31%   |
| 1920x540           | 27        | 0.25%   |
| 2160x1440          | 19        | 0.17%   |
| 2736x1824          | 15        | 0.14%   |
| 3200x1800 (QHD+)   | 13        | 0.12%   |
| 4480x1440          | 12        | 0.11%   |
| 1280x720 (HD)      | 12        | 0.11%   |
| 2256x1504          | 11        | 0.1%    |
| 1920x1280          | 11        | 0.1%    |
| 1400x1050          | 11        | 0.1%    |
| 3840x1600          | 10        | 0.09%   |
| 5760x2160          | 8         | 0.07%   |
| 3840x1200          | 7         | 0.06%   |
| 3200x1080          | 7         | 0.06%   |
| 3072x1920          | 7         | 0.06%   |
| 3000x2000          | 7         | 0.06%   |
| 2048x1152          | 7         | 0.06%   |
| 7680x2160          | 6         | 0.06%   |
| 5760x1080          | 6         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2220      | 19.72%  |
| 13      | 1598      | 14.2%   |
| 14      | 936       | 8.32%   |
| 24      | 853       | 7.58%   |
| 27      | 766       | 6.81%   |
| 23      | 660       | 5.86%   |
| 21      | 587       | 5.21%   |
| 17      | 541       | 4.81%   |
| Unknown | 445       | 3.95%   |
| 11      | 365       | 3.24%   |
| 19      | 302       | 2.68%   |
| 12      | 257       | 2.28%   |
| 18      | 209       | 1.86%   |
| 31      | 201       | 1.79%   |
| 20      | 157       | 1.39%   |
| 22      | 154       | 1.37%   |
| 34      | 149       | 1.32%   |
| 16      | 102       | 0.91%   |
| 10      | 89        | 0.79%   |
| 84      | 70        | 0.62%   |
| 142     | 59        | 0.52%   |
| 25      | 56        | 0.5%    |
| 32      | 54        | 0.48%   |
| 72      | 52        | 0.46%   |
| 54      | 45        | 0.4%    |
| 40      | 42        | 0.37%   |
| 26      | 32        | 0.28%   |
| 28      | 31        | 0.28%   |
| 29      | 23        | 0.2%    |
| 52      | 20        | 0.18%   |
| 48      | 19        | 0.17%   |
| 65      | 14        | 0.12%   |
| 46      | 13        | 0.12%   |
| 33      | 13        | 0.12%   |
| 43      | 12        | 0.11%   |
| 8       | 12        | 0.11%   |
| 39      | 11        | 0.1%    |
| 49      | 10        | 0.09%   |
| 35      | 10        | 0.09%   |
| 37      | 8         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3867      | 34.93%  |
| 501-600        | 2128      | 19.22%  |
| 201-300        | 1798      | 16.24%  |
| 401-500        | 1207      | 10.9%   |
| 351-400        | 614       | 5.55%   |
| Unknown        | 445       | 4.02%   |
| 601-700        | 347       | 3.13%   |
| 701-800        | 222       | 2.01%   |
| 1001-1500      | 143       | 1.29%   |
| 1501-2000      | 129       | 1.17%   |
| 801-900        | 73        | 0.66%   |
| More than 2000 | 60        | 0.54%   |
| 901-1000       | 21        | 0.19%   |
| 101-200        | 15        | 0.14%   |
| 1-100          | 3         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 7287      | 71.16%  |
| 16/10   | 1636      | 15.98%  |
| 5/4     | 373       | 3.64%   |
| Unknown | 367       | 3.58%   |
| 21/9    | 183       | 1.79%   |
| 4/3     | 156       | 1.52%   |
| 3/2     | 107       | 1.04%   |
| 1.00    | 63        | 0.62%   |
| 6/5     | 20        | 0.2%    |
| 32/9    | 19        | 0.19%   |
| 2.65    | 6         | 0.06%   |
| 0.56    | 5         | 0.05%   |
| 3.40    | 3         | 0.03%   |
| 3.20    | 3         | 0.03%   |
| 1.96    | 3         | 0.03%   |
| 2.00    | 2         | 0.02%   |
| 0.67    | 2         | 0.02%   |
| 0.45    | 2         | 0.02%   |
| 3.73    | 1         | 0.01%   |
| 11/10   | 1         | 0.01%   |
| 0.58    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2205      | 19.74%  |
| 81-90          | 1969      | 17.63%  |
| 201-250        | 1780      | 15.94%  |
| 301-350        | 788       | 7.06%   |
| 151-200        | 626       | 5.61%   |
| 71-80          | 569       | 5.09%   |
| 351-500        | 466       | 4.17%   |
| Unknown        | 445       | 3.98%   |
| 51-60          | 368       | 3.3%    |
| 141-150        | 356       | 3.19%   |
| 251-300        | 347       | 3.11%   |
| 121-130        | 305       | 2.73%   |
| More than 1000 | 303       | 2.71%   |
| 61-70          | 234       | 2.1%    |
| 501-1000       | 119       | 1.07%   |
| 111-120        | 93        | 0.83%   |
| 41-50          | 88        | 0.79%   |
| 131-140        | 61        | 0.55%   |
| 91-100         | 28        | 0.25%   |
| 1-40           | 18        | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 3334      | 30.71%  |
| 121-160       | 3088      | 28.45%  |
| 101-120       | 2771      | 25.53%  |
| 161-240       | 764       | 7.04%   |
| Unknown       | 446       | 4.11%   |
| 1-50          | 258       | 2.38%   |
| More than 240 | 195       | 1.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 8370      | 67.87%  |
| 0     | 2187      | 17.73%  |
| 2     | 1585      | 12.85%  |
| 3     | 182       | 1.48%   |
| 4     | 8         | 0.06%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5874      | 33.39%  |
| Intel                             | 5692      | 32.36%  |
| Qualcomm Atheros                  | 1606      | 9.13%   |
| Broadcom                          | 1198      | 6.81%   |
| Nvidia                            | 477       | 2.71%   |
| Broadcom Limited                  | 360       | 2.05%   |
| MediaTek                          | 271       | 1.54%   |
| Marvell Technology Group          | 238       | 1.35%   |
| Ralink Technology                 | 164       | 0.93%   |
| TP-Link                           | 147       | 0.84%   |
| ASIX Electronics                  | 121       | 0.69%   |
| Ralink                            | 118       | 0.67%   |
| Samsung Electronics               | 78        | 0.44%   |
| Qualcomm                          | 55        | 0.31%   |
| Dell                              | 54        | 0.31%   |
| Xiaomi                            | 52        | 0.3%    |
| Lenovo                            | 51        | 0.29%   |
| Sierra Wireless                   | 49        | 0.28%   |
| Aquantia                          | 45        | 0.26%   |
| Microchip Technology              | 44        | 0.25%   |
| Mellanox Technologies             | 42        | 0.24%   |
| Huawei Technologies               | 41        | 0.23%   |
| Qualcomm Atheros Communications   | 36        | 0.2%    |
| JMicron Technology                | 36        | 0.2%    |
| DisplayLink                       | 35        | 0.2%    |
| D-Link System                     | 32        | 0.18%   |
| Microsoft                         | 31        | 0.18%   |
| Ericsson Business Mobile Networks | 30        | 0.17%   |
| ASUSTek Computer                  | 29        | 0.16%   |
| D-Link                            | 28        | 0.16%   |
| NetGear                           | 27        | 0.15%   |
| Hewlett-Packard                   | 24        | 0.14%   |
| Edimax Technology                 | 23        | 0.13%   |
| American Megatrends               | 23        | 0.13%   |
| VIA Technologies                  | 19        | 0.11%   |
| IBM                               | 19        | 0.11%   |
| Fibocom                           | 19        | 0.11%   |
| Silicon Integrated Systems [SiS]  | 18        | 0.1%    |
| Sigma Designs                     | 16        | 0.09%   |
| QinHeng Electronics               | 16        | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 4068      | 19.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 561       | 2.71%   |
| Intel Wi-Fi 6 AX200                                                  | 398       | 1.92%   |
| Nvidia MCP79 Ethernet                                                | 382       | 1.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 378       | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 374       | 1.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 363       | 1.76%   |
| Intel Wi-Fi 6 AX201                                                  | 359       | 1.74%   |
| Intel Wireless 8265 / 8275                                           | 317       | 1.53%   |
| Realtek RTL8125 2.5GbE Controller                                    | 296       | 1.43%   |
| Intel Wireless 7265                                                  | 289       | 1.4%    |
| Intel Wireless 7260                                                  | 273       | 1.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 270       | 1.31%   |
| Intel I211 Gigabit Network Connection                                | 243       | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 205       | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 184       | 0.89%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 180       | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 177       | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 174       | 0.84%   |
| Intel Wireless 8260                                                  | 173       | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 170       | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 165       | 0.8%    |
| Intel Ethernet Controller I225-V                                     | 164       | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 163       | 0.79%   |
| Intel Ethernet Connection (13) I219-V                                | 155       | 0.75%   |
| Intel Wireless 3165                                                  | 152       | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 151       | 0.73%   |
| Intel Ethernet Connection I217-LM                                    | 150       | 0.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 145       | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 144       | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 142       | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                 | 141       | 0.68%   |
| Intel I210 Gigabit Network Connection                                | 135       | 0.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 122       | 0.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 121       | 0.59%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 119       | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 116       | 0.56%   |
| Intel Wireless-AC 9260                                               | 109       | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                                | 108       | 0.52%   |
| Intel 82579V Gigabit Network Connection                              | 104       | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3988      | 46.24%  |
| Qualcomm Atheros                      | 1299      | 15.06%  |
| Realtek Semiconductor                 | 1206      | 13.98%  |
| Broadcom                              | 807       | 9.36%   |
| Broadcom Limited                      | 268       | 3.11%   |
| MediaTek                              | 252       | 2.92%   |
| Ralink Technology                     | 164       | 1.9%    |
| TP-Link                               | 118       | 1.37%   |
| Ralink                                | 118       | 1.37%   |
| Sierra Wireless                       | 49        | 0.57%   |
| Qualcomm Atheros Communications       | 36        | 0.42%   |
| Qualcomm                              | 34        | 0.39%   |
| Dell                                  | 32        | 0.37%   |
| ASUSTek Computer                      | 29        | 0.34%   |
| NetGear                               | 27        | 0.31%   |
| D-Link                                | 25        | 0.29%   |
| Marvell Technology Group              | 23        | 0.27%   |
| Edimax Technology                     | 23        | 0.27%   |
| Fibocom                               | 19        | 0.22%   |
| Microsoft                             | 18        | 0.21%   |
| D-Link System                         | 17        | 0.2%    |
| Belkin Components                     | 11        | 0.13%   |
| Wilocity                              | 7         | 0.08%   |
| Linksys                               | 7         | 0.08%   |
| Gemtek                                | 6         | 0.07%   |
| IMC Networks                          | 5         | 0.06%   |
| Hewlett-Packard                       | 5         | 0.06%   |
| Ericsson Business Mobile Networks     | 5         | 0.06%   |
| AVM                                   | 3         | 0.03%   |
| Quectel Wireless Solutions            | 2         | 0.02%   |
| Micro Star International              | 2         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.02%   |
| 3Com                                  | 2         | 0.02%   |
| ZyXEL Communications                  | 1         | 0.01%   |
| ZyDAS                                 | 1         | 0.01%   |
| Z-Com                                 | 1         | 0.01%   |
| Xiaomi                                | 1         | 0.01%   |
| Winbond Electronics                   | 1         | 0.01%   |
| Wacom                                 | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 398       | 4.59%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 378       | 4.36%   |
| Intel Wi-Fi 6 AX201                                                                   | 359       | 4.14%   |
| Intel Wireless 8265 / 8275                                                            | 317       | 3.66%   |
| Intel Wireless 7265                                                                   | 289       | 3.33%   |
| Intel Wireless 7260                                                                   | 273       | 3.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 270       | 3.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 205       | 2.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 184       | 2.12%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 180       | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 177       | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 174       | 2.01%   |
| Intel Wireless 8260                                                                   | 173       | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 170       | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 165       | 1.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 163       | 1.88%   |
| Intel Wireless 3165                                                                   | 152       | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 151       | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 145       | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 144       | 1.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 142       | 1.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 122       | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 121       | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                                        | 119       | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 116       | 1.34%   |
| Intel Wireless-AC 9260                                                                | 109       | 1.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 97        | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 93        | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 77        | 0.89%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 62        | 0.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 61        | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 60        | 0.69%   |
| Ralink MT7601U Wireless Adapter                                                       | 60        | 0.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 60        | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 59        | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 59        | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 56        | 0.65%   |
| Intel Wireless 3160                                                                   | 56        | 0.65%   |
| Realtek 802.11ac NIC                                                                  | 53        | 0.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 53        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5391      | 47.7%   |
| Intel                             | 3305      | 29.24%  |
| Broadcom                          | 483       | 4.27%   |
| Nvidia                            | 476       | 4.21%   |
| Qualcomm Atheros                  | 462       | 4.09%   |
| Marvell Technology Group          | 216       | 1.91%   |
| ASIX Electronics                  | 121       | 1.07%   |
| Broadcom Limited                  | 96        | 0.85%   |
| Xiaomi                            | 51        | 0.45%   |
| Lenovo                            | 51        | 0.45%   |
| Samsung Electronics               | 50        | 0.44%   |
| Aquantia                          | 45        | 0.4%    |
| Microchip Technology              | 42        | 0.37%   |
| Mellanox Technologies             | 39        | 0.35%   |
| JMicron Technology                | 36        | 0.32%   |
| DisplayLink                       | 35        | 0.31%   |
| TP-Link                           | 29        | 0.26%   |
| Huawei Technologies               | 29        | 0.26%   |
| American Megatrends               | 23        | 0.2%    |
| VIA Technologies                  | 19        | 0.17%   |
| Qualcomm                          | 19        | 0.17%   |
| IBM                               | 19        | 0.17%   |
| Silicon Integrated Systems [SiS]  | 18        | 0.16%   |
| MediaTek                          | 18        | 0.16%   |
| D-Link System                     | 15        | 0.13%   |
| Google                            | 13        | 0.12%   |
| OPPO Electronics                  | 12        | 0.11%   |
| Microsoft                         | 12        | 0.11%   |
| ICS Advent                        | 12        | 0.11%   |
| 3Com                              | 12        | 0.11%   |
| Motorola PCS                      | 11        | 0.1%    |
| Hewlett-Packard                   | 10        | 0.09%   |
| Dell                              | 10        | 0.09%   |
| Standard Microsystems             | 9         | 0.08%   |
| Cypress Semiconductor             | 9         | 0.08%   |
| Emulex                            | 8         | 0.07%   |
| Attansic Technology               | 8         | 0.07%   |
| Insyde Software                   | 7         | 0.06%   |
| Apple                             | 7         | 0.06%   |
| Sundance Technology Inc / IC Plus | 5         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4068      | 34.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 561       | 4.79%   |
| Nvidia MCP79 Ethernet                                             | 382       | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 374       | 3.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 363       | 3.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 296       | 2.53%   |
| Intel I211 Gigabit Network Connection                             | 243       | 2.08%   |
| Intel Ethernet Controller I225-V                                  | 164       | 1.4%    |
| Intel Ethernet Connection (13) I219-V                             | 155       | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 150       | 1.28%   |
| Intel Ethernet Connection (2) I219-V                              | 141       | 1.2%    |
| Intel I210 Gigabit Network Connection                             | 135       | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 108       | 0.92%   |
| Intel 82579V Gigabit Network Connection                           | 104       | 0.89%   |
| Intel I350 Gigabit Network Connection                             | 94        | 0.8%    |
| ASIX AX88179 Gigabit Ethernet                                     | 94        | 0.8%    |
| Intel 82574L Gigabit Network Connection                           | 91        | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 89        | 0.76%   |
| Intel Ethernet Connection (4) I219-V                              | 86        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 78        | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 77        | 0.66%   |
| Intel Ethernet Connection (6) I219-V                              | 74        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 70        | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 69        | 0.59%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 68        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 68        | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 66        | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 63        | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 57        | 0.49%   |
| Intel Ethernet Connection (10) I219-V                             | 55        | 0.47%   |
| Intel Ethernet Connection (14) I219-V                             | 54        | 0.46%   |
| Intel 82577LM Gigabit Network Connection                          | 52        | 0.44%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 49        | 0.42%   |
| Nvidia MCP61 Ethernet                                             | 48        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 47        | 0.4%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 47        | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 46        | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 46        | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 45        | 0.38%   |
| Intel 82567LM Gigabit Network Connection                          | 45        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 10408     | 55.01%  |
| WiFi     | 8219      | 43.44%  |
| Modem    | 265       | 1.4%    |
| Unknown  | 28        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6418      | 52.96%  |
| WiFi     | 5698      | 47.02%  |
| Modem    | 3         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 6228      | 51.31%  |
| 1     | 4758      | 39.2%   |
| 0     | 497       | 4.09%   |
| 3     | 360       | 2.97%   |
| 4     | 171       | 1.41%   |
| 6     | 50        | 0.41%   |
| 5     | 28        | 0.23%   |
| 8     | 18        | 0.15%   |
| 7     | 11        | 0.09%   |
| 9     | 4         | 0.03%   |
| 12    | 3         | 0.02%   |
| 20    | 2         | 0.02%   |
| 10    | 2         | 0.02%   |
| 33    | 1         | 0.01%   |
| 21    | 1         | 0.01%   |
| 17    | 1         | 0.01%   |
| 16    | 1         | 0.01%   |
| 14    | 1         | 0.01%   |
| 13    | 1         | 0.01%   |
| 11    | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 10005     | 81.59%  |
| Yes     | 2257      | 18.4%   |
| Unknown | 1         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3263      | 47.32%  |
| Apple                           | 757       | 10.98%  |
| Realtek Semiconductor           | 627       | 9.09%   |
| Qualcomm Atheros Communications | 473       | 6.86%   |
| Cambridge Silicon Radio         | 320       | 4.64%   |
| Broadcom                        | 293       | 4.25%   |
| IMC Networks                    | 257       | 3.73%   |
| Lite-On Technology              | 193       | 2.8%    |
| Foxconn / Hon Hai               | 176       | 2.55%   |
| ASUSTek Computer                | 119       | 1.73%   |
| Dell                            | 73        | 1.06%   |
| MediaTek                        | 68        | 0.99%   |
| Hewlett-Packard                 | 59        | 0.86%   |
| Realtek                         | 38        | 0.55%   |
| Toshiba                         | 35        | 0.51%   |
| Ralink                          | 21        | 0.3%    |
| TP-Link                         | 18        | 0.26%   |
| USI                             | 13        | 0.19%   |
| Foxconn International           | 13        | 0.19%   |
| Marvell Semiconductor           | 11        | 0.16%   |
| Ralink Technology               | 9         | 0.13%   |
| Alps Electric                   | 8         | 0.12%   |
| Taiyo Yuden                     | 5         | 0.07%   |
| Edimax Technology               | 5         | 0.07%   |
| Belkin Components               | 5         | 0.07%   |
| Micro Star International        | 4         | 0.06%   |
| Integrated System Solution      | 4         | 0.06%   |
| Fujitsu                         | 4         | 0.06%   |
| Dynex                           | 3         | 0.04%   |
| Qcom                            | 2         | 0.03%   |
| Opticis                         | 2         | 0.03%   |
| Chicony Electronics             | 2         | 0.03%   |
| Askey Computer                  | 2         | 0.03%   |
| Actions                         | 2         | 0.03%   |
| Unknown                         | 2         | 0.03%   |
| Unknown                         | 1         | 0.01%   |
| Smart Modular Technologies      | 1         | 0.01%   |
| Sitecom Europe                  | 1         | 0.01%   |
| SINO WEALTH                     | 1         | 0.01%   |
| Microsoft                       | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1191      | 17.26%  |
| Intel AX201 Bluetooth                               | 669       | 9.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 434       | 6.29%   |
| Realtek Bluetooth Radio                             | 382       | 5.53%   |
| Intel AX200 Bluetooth                               | 379       | 5.49%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 378       | 5.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 320       | 4.64%   |
| Qualcomm Atheros  Bluetooth Device                  | 254       | 3.68%   |
| Apple Bluetooth USB Host Controller                 | 193       | 2.8%    |
| Intel Bluetooth Device                              | 177       | 2.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 122       | 1.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 112       | 1.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 105       | 1.52%   |
| Intel AX210 Bluetooth                               | 103       | 1.49%   |
| Apple Bluetooth Host Controller                     | 87        | 1.26%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 79        | 1.14%   |
| IMC Networks Bluetooth Radio                        | 74        | 1.07%   |
| Realtek 802.11ac WLAN Adapter                       | 68        | 0.99%   |
| IMC Networks Wireless_Device                        | 68        | 0.99%   |
| MediaTek Wireless_Device                            | 67        | 0.97%   |
| IMC Networks Bluetooth Device                       | 66        | 0.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 64        | 0.93%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 63        | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 59        | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 57        | 0.83%   |
| Foxconn / Hon Hai Bluetooth Device                  | 56        | 0.81%   |
| Lite-On Bluetooth Device                            | 50        | 0.72%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 47        | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                         | 46        | 0.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 44        | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 42        | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 36        | 0.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 34        | 0.49%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 33        | 0.48%   |
| Lite-On Wireless_Device                             | 30        | 0.43%   |
| Realtek 802.11ac WLAN Adapter                       | 29        | 0.42%   |
| HP Broadcom 2070 Bluetooth Combo                    | 28        | 0.41%   |
| Foxconn / Hon Hai Wireless_Device                   | 27        | 0.39%   |
| Realtek RTL8723B Bluetooth                          | 26        | 0.38%   |
| Lite-On Atheros AR3012 Bluetooth                    | 26        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 8118      | 53.82%  |
| AMD                                          | 2862      | 18.98%  |
| Nvidia                                       | 2559      | 16.97%  |
| C-Media Electronics                          | 231       | 1.53%   |
| Logitech                                     | 118       | 0.78%   |
| Creative Labs                                | 75        | 0.5%    |
| ASUSTek Computer                             | 64        | 0.42%   |
| Realtek Semiconductor                        | 61        | 0.4%    |
| Texas Instruments                            | 59        | 0.39%   |
| Lenovo                                       | 56        | 0.37%   |
| GN Netcom                                    | 46        | 0.3%    |
| Generalplus Technology                       | 45        | 0.3%    |
| Plantronics                                  | 42        | 0.28%   |
| JMTek                                        | 41        | 0.27%   |
| Focusrite-Novation                           | 35        | 0.23%   |
| Creative Technology                          | 34        | 0.23%   |
| Micro Star International                     | 32        | 0.21%   |
| Kingston Technology                          | 27        | 0.18%   |
| VIA Technologies                             | 26        | 0.17%   |
| KTMicro                                      | 26        | 0.17%   |
| Zoran Co. Personal Media Division (Nogatech) | 24        | 0.16%   |
| SteelSeries ApS                              | 23        | 0.15%   |
| Hewlett-Packard                              | 23        | 0.15%   |
| Silicon Integrated Systems [SiS]             | 20        | 0.13%   |
| Dell                                         | 20        | 0.13%   |
| Razer USA                                    | 18        | 0.12%   |
| Corsair                                      | 15        | 0.1%    |
| BEHRINGER International                      | 15        | 0.1%    |
| Microsoft                                    | 14        | 0.09%   |
| Blue Microphones                             | 14        | 0.09%   |
| RODE Microphones                             | 13        | 0.09%   |
| GYROCOM C&C                                  | 11        | 0.07%   |
| DSEA A/S                                     | 11        | 0.07%   |
| Cambridge Silicon Radio                      | 11        | 0.07%   |
| BR25                                         | 11        | 0.07%   |
| Yamaha                                       | 10        | 0.07%   |
| M-Audio                                      | 10        | 0.07%   |
| Tenx Technology                              | 9         | 0.06%   |
| Apple                                        | 9         | 0.06%   |
| Sennheiser Communications                    | 7         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 995       | 5.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 808       | 4.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 631       | 3.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 620       | 3.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 549       | 3.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 502       | 2.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 460       | 2.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 431       | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 428       | 2.39%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 402       | 2.24%   |
| Nvidia MCP79 High Definition Audio                                                                | 386       | 2.15%   |
| Intel Broadwell-U Audio Controller                                                                | 342       | 1.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 340       | 1.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 338       | 1.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 333       | 1.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 319       | 1.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 297       | 1.66%   |
| Intel 200 Series PCH HD Audio                                                                     | 264       | 1.47%   |
| AMD FCH Azalia Controller                                                                         | 244       | 1.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 242       | 1.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 239       | 1.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 229       | 1.28%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 227       | 1.27%   |
| Intel 8 Series HD Audio Controller                                                                | 227       | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 215       | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 206       | 1.15%   |
| Intel Comet Lake PCH cAVS                                                                         | 194       | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 186       | 1.04%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 183       | 1.02%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 174       | 0.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 173       | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 169       | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 168       | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 168       | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 158       | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 158       | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 152       | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 126       | 0.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 121       | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 114       | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2373      | 21.42%  |
| SK hynix            | 2065      | 18.64%  |
| Kingston            | 1305      | 11.78%  |
| Unknown             | 1094      | 9.88%   |
| Micron Technology   | 971       | 8.77%   |
| Crucial             | 808       | 7.29%   |
| Corsair             | 456       | 4.12%   |
| G.Skill             | 341       | 3.08%   |
| A-DATA Technology   | 202       | 1.82%   |
| Elpida              | 188       | 1.7%    |
| Ramaxel Technology  | 158       | 1.43%   |
| Unknown (ABCD)      | 106       | 0.96%   |
| Patriot             | 106       | 0.96%   |
| Unknown             | 99        | 0.89%   |
| Nanya Technology    | 93        | 0.84%   |
| Team                | 65        | 0.59%   |
| Smart               | 64        | 0.58%   |
| Transcend           | 49        | 0.44%   |
| GOODRAM             | 39        | 0.35%   |
| AMD                 | 35        | 0.32%   |
| Hewlett-Packard     | 22        | 0.2%    |
| Apacer              | 22        | 0.2%    |
| Hikvision           | 21        | 0.19%   |
| Timetec             | 17        | 0.15%   |
| Teikon              | 16        | 0.14%   |
| Qimonda             | 14        | 0.13%   |
| Silicon Power       | 13        | 0.12%   |
| Avant               | 13        | 0.12%   |
| 48spaces            | 12        | 0.11%   |
| PNY                 | 11        | 0.1%    |
| ASint Technology    | 11        | 0.1%    |
| GeIL                | 9         | 0.08%   |
| 4ea5                | 9         | 0.08%   |
| Micro Memory Bank   | 8         | 0.07%   |
| ff                  | 8         | 0.07%   |
| Unknown (0x5846)    | 7         | 0.06%   |
| Wilk                | 6         | 0.05%   |
| Unifosa             | 6         | 0.05%   |
| Toshiba             | 6         | 0.05%   |
| Smart Brazil        | 6         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                       | 265       | 2.23%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 176       | 1.48%   |
| Unknown                                                           | 99        | 0.83%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                       | 69        | 0.58%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s             | 69        | 0.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 67        | 0.56%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                       | 63        | 0.53%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 55        | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 55        | 0.46%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 55        | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 53        | 0.45%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 53        | 0.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 52        | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 51        | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 51        | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 51        | 0.43%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s           | 50        | 0.42%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 49        | 0.41%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                      | 48        | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 47        | 0.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 47        | 0.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 47        | 0.4%    |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                        | 46        | 0.39%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s             | 45        | 0.38%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                   | 44        | 0.37%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 43        | 0.36%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 40        | 0.34%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s             | 40        | 0.34%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 39        | 0.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 38        | 0.32%   |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1866MT/s          | 38        | 0.32%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s             | 38        | 0.32%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 37        | 0.31%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4096MB DIMM DDR4 2133MT/s         | 36        | 0.3%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 35        | 0.29%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s          | 34        | 0.29%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 33        | 0.28%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 32        | 0.27%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 32        | 0.27%   |
| Unknown RAM Module 1GB DIMM SDRAM                                 | 31        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 4289      | 43.95%  |
| DDR3         | 3083      | 31.59%  |
| DDR2         | 871       | 8.93%   |
| LPDDR4       | 307       | 3.15%   |
| Unknown      | 305       | 3.13%   |
| SDRAM        | 295       | 3.02%   |
| LPDDR3       | 246       | 2.52%   |
| DDR5         | 173       | 1.77%   |
| DDR          | 90        | 0.92%   |
| LPDDR5       | 69        | 0.71%   |
| DRAM         | 29        | 0.3%    |
| RAM          | 1         | 0.01%   |
| DDR2 FB-DIMM | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 5321      | 54.74%  |
| DIMM         | 3718      | 38.25%  |
| Row Of Chips | 500       | 5.14%   |
| Unknown      | 113       | 1.16%   |
| Chip         | 40        | 0.41%   |
| FB-DIMM      | 17        | 0.17%   |
| RIMM         | 12        | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 3599      | 34.01%  |
| 4096    | 2469      | 23.33%  |
| 16384   | 1538      | 14.53%  |
| 2048    | 1517      | 14.33%  |
| 1024    | 798       | 7.54%   |
| 32768   | 510       | 4.82%   |
| 512     | 96        | 0.91%   |
| 256     | 25        | 0.24%   |
| 65536   | 13        | 0.12%   |
| 1536    | 5         | 0.05%   |
| 128     | 4         | 0.04%   |
| 49152   | 1         | 0.01%   |
| 24576   | 1         | 0.01%   |
| 16315   | 1         | 0.01%   |
| 8072    | 1         | 0.01%   |
| 6144    | 1         | 0.01%   |
| 3072    | 1         | 0.01%   |
| 384     | 1         | 0.01%   |
| 64      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1986      | 18.94%  |
| 3200    | 1631      | 15.55%  |
| 2667    | 1315      | 12.54%  |
| 2400    | 681       | 6.49%   |
| 1333    | 674       | 6.43%   |
| 800     | 593       | 5.65%   |
| 2133    | 516       | 4.92%   |
| 667     | 328       | 3.13%   |
| Unknown | 274       | 2.61%   |
| 1334    | 237       | 2.26%   |
| 3600    | 232       | 2.21%   |
| 1867    | 201       | 1.92%   |
| 1067    | 120       | 1.14%   |
| 4800    | 116       | 1.11%   |
| 1866    | 115       | 1.1%    |
| 2666    | 107       | 1.02%   |
| 4267    | 104       | 0.99%   |
| 1066    | 100       | 0.95%   |
| 6400    | 73        | 0.7%    |
| 3733    | 71        | 0.68%   |
| 3266    | 69        | 0.66%   |
| 2933    | 68        | 0.65%   |
| 3400    | 61        | 0.58%   |
| 3000    | 58        | 0.55%   |
| 1800    | 53        | 0.51%   |
| 533     | 50        | 0.48%   |
| 4199    | 42        | 0.4%    |
| 2048    | 38        | 0.36%   |
| 3800    | 37        | 0.35%   |
| 400     | 35        | 0.33%   |
| 2866    | 27        | 0.26%   |
| 3466    | 25        | 0.24%   |
| 5600    | 24        | 0.23%   |
| 975     | 24        | 0.23%   |
| 6000    | 22        | 0.21%   |
| 8400    | 20        | 0.19%   |
| 3533    | 20        | 0.19%   |
| 333     | 20        | 0.19%   |
| 4266    | 19        | 0.18%   |
| 4333    | 16        | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 77        | 30.68%  |
| Brother Industries     | 48        | 19.12%  |
| Canon                  | 34        | 13.55%  |
| Samsung Electronics    | 18        | 7.17%   |
| Seiko Epson            | 15        | 5.98%   |
| Xerox                  | 9         | 3.59%   |
| Dymo-CoStar            | 9         | 3.59%   |
| Prolific Technology    | 6         | 2.39%   |
| Lexmark International  | 6         | 2.39%   |
| Zebra                  | 4         | 1.59%   |
| Pantum                 | 4         | 1.59%   |
| Kyocera                | 4         | 1.59%   |
| STMicroelectronics     | 2         | 0.8%    |
| QinHeng Electronics    | 2         | 0.8%    |
| Oki Data               | 2         | 0.8%    |
| Datamax-O'Neil         | 2         | 0.8%    |
| Xiaomi                 | 1         | 0.4%    |
| Ricoh                  | 1         | 0.4%    |
| Printer                | 1         | 0.4%    |
| Panasonic (Matsushita) | 1         | 0.4%    |
| nemonic                | 1         | 0.4%    |
| Konica Minolta         | 1         | 0.4%    |
| GODEX INTERNATIONAL    | 1         | 0.4%    |
| Dell                   | 1         | 0.4%    |
| Apple                  | 1         | 0.4%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 7         | 2.76%   |
| HP LaserJet 1020                                          | 7         | 2.76%   |
| Prolific PL2305 Parallel Port                             | 6         | 2.36%   |
| HP LaserJet 1200                                          | 6         | 2.36%   |
| Canon LiDE 400                                            | 5         | 1.97%   |
| HP DeskJet 2130 series                                    | 4         | 1.57%   |
| Canon PIXMA MG3600 Series                                 | 4         | 1.57%   |
| Seiko Epson Printer                                       | 3         | 1.18%   |
| Samsung ML-1660 Series                                    | 3         | 1.18%   |
| Pantum P2500W series                                      | 3         | 1.18%   |
| HP LaserJet P1005                                         | 3         | 1.18%   |
| HP LaserJet M101-M106                                     | 3         | 1.18%   |
| HP DeskJet 2700 series                                    | 3         | 1.18%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 3         | 1.18%   |
| Brother HL-52x0 series                                    | 3         | 1.18%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 0.79%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 0.79%   |
| Samsung M2020 Series                                      | 2         | 0.79%   |
| QinHeng CH340S                                            | 2         | 0.79%   |
| Oki Data USB Device                                       | 2         | 0.79%   |
| Lexmark International CS417dn                             | 2         | 0.79%   |
| HP LaserJet Pro M404-M405                                 | 2         | 0.79%   |
| HP LaserJet M14-M17                                       | 2         | 0.79%   |
| HP LaserJet 400 M401a                                     | 2         | 0.79%   |
| HP LaserJet 1150                                          | 2         | 0.79%   |
| HP LaserJet 1022                                          | 2         | 0.79%   |
| HP LaserJet 1018                                          | 2         | 0.79%   |
| HP ENVY Photo 6200 series                                 | 2         | 0.79%   |
| HP ENVY 4520 series                                       | 2         | 0.79%   |
| HP DeskJet Plus 4100 series                               | 2         | 0.79%   |
| HP DeskJet 2620 All-in-One Printer                        | 2         | 0.79%   |
| Dymo-CoStar LabelWriter 450                               | 2         | 0.79%   |
| Datamax-O'Neil Datamax E-4304                             | 2         | 0.79%   |
| Canon PIXMA MX920 Series                                  | 2         | 0.79%   |
| Canon MF4410                                              | 2         | 0.79%   |
| Canon MF3010                                              | 2         | 0.79%   |
| Canon G3010 series                                        | 2         | 0.79%   |
| Canon CanoScan LiDE 300                                   | 2         | 0.79%   |
| Brother PT-9500PC                                         | 2         | 0.79%   |
| Brother Printer                                           | 2         | 0.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 43        | 58.9%   |
| Seiko Epson        | 16        | 21.92%  |
| Hewlett-Packard    | 6         | 8.22%   |
| Mustek Systems     | 3         | 4.11%   |
| Ultima Electronics | 2         | 2.74%   |
| AGFA-Gevaert NV    | 2         | 2.74%   |
| Plustek            | 1         | 1.37%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 9         | 12.33%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 7         | 9.59%   |
| Canon CanoScan LiDE 210                                                               | 7         | 9.59%   |
| Canon CanoScan LiDE 220                                                               | 5         | 6.85%   |
| Canon CanoScan LIDE 25                                                                | 3         | 4.11%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 2.74%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 2         | 2.74%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 2         | 2.74%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 2.74%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 2.74%   |
| Canon CanoScan LiDE 60                                                                | 2         | 2.74%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 2         | 2.74%   |
| Canon CanoScan LiDE 120                                                               | 2         | 2.74%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2         | 2.74%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 1.37%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 1.37%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1         | 1.37%   |
| Seiko Epson GT-9800F [Perfection 3200]                                                | 1         | 1.37%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 1.37%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 1.37%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1         | 1.37%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1         | 1.37%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 1         | 1.37%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1         | 1.37%   |
| Plustek 1200dpi USB Scanner                                                           | 1         | 1.37%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 1.37%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1         | 1.37%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 1         | 1.37%   |
| HP ScanJet Pro 2500 f1                                                                | 1         | 1.37%   |
| HP ScanJet 82x0C                                                                      | 1         | 1.37%   |
| HP ScanJet 7650                                                                       | 1         | 1.37%   |
| HP ScanJet 3970c                                                                      | 1         | 1.37%   |
| HP Scanjet 300                                                                        | 1         | 1.37%   |
| HP Scanjet 200                                                                        | 1         | 1.37%   |
| Canon CanoScan 9000F Mark II                                                          | 1         | 1.37%   |
| Canon CanoScan 8800F                                                                  | 1         | 1.37%   |
| Canon CanoScan 5600F                                                                  | 1         | 1.37%   |
| Canon CanoScan 4400F                                                                  | 1         | 1.37%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1323      | 21.37%  |
| IMC Networks                           | 556       | 8.98%   |
| Microdia                               | 464       | 7.5%    |
| Bison Electronics                      | 450       | 7.27%   |
| Realtek Semiconductor                  | 403       | 6.51%   |
| Quanta                                 | 398       | 6.43%   |
| Logitech                               | 393       | 6.35%   |
| Sunplus Innovation Technology          | 306       | 4.94%   |
| Acer                                   | 206       | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 168       | 2.71%   |
| Apple                                  | 163       | 2.63%   |
| Suyin                                  | 147       | 2.37%   |
| Syntek                                 | 136       | 2.2%    |
| Lite-On Technology                     | 136       | 2.2%    |
| Luxvisions Innotech Limited            | 129       | 2.08%   |
| Silicon Motion                         | 68        | 1.1%    |
| Microsoft                              | 60        | 0.97%   |
| Alcor Micro                            | 58        | 0.94%   |
| Samsung Electronics                    | 50        | 0.81%   |
| Z-Star Microelectronics                | 42        | 0.68%   |
| Lenovo                                 | 42        | 0.68%   |
| Sonix Technology                       | 41        | 0.66%   |
| Ricoh                                  | 36        | 0.58%   |
| Generalplus Technology                 | 34        | 0.55%   |
| Primax Electronics                     | 21        | 0.34%   |
| GEMBIRD                                | 20        | 0.32%   |
| Jieli Technology                       | 19        | 0.31%   |
| Creative Technology                    | 19        | 0.31%   |
| KYE Systems (Mouse Systems)            | 15        | 0.24%   |
| ARC International                      | 15        | 0.24%   |
| SunplusIT                              | 14        | 0.23%   |
| icSpring                               | 14        | 0.23%   |
| Genesys Logic                          | 13        | 0.21%   |
| ALi                                    | 13        | 0.21%   |
| MacroSilicon                           | 12        | 0.19%   |
| Importek                               | 12        | 0.19%   |
| OmniVision Technologies                | 10        | 0.16%   |
| Intel                                  | 7         | 0.11%   |
| Huawei Technologies                    | 7         | 0.11%   |
| Cubeternet                             | 7         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 372       | 5.95%   |
| Bison Integrated Camera                             | 206       | 3.3%    |
| Microdia Integrated_Webcam_HD                       | 195       | 3.12%   |
| IMC Networks Integrated Camera                      | 187       | 2.99%   |
| Realtek Integrated_Webcam_HD                        | 153       | 2.45%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 137       | 2.19%   |
| Quanta Chromebook HD Camera                         | 102       | 1.63%   |
| Chicony HD WebCam                                   | 102       | 1.63%   |
| Logitech Webcam C270                                | 96        | 1.54%   |
| Sunplus Integrated_Webcam_HD                        | 93        | 1.49%   |
| Syntek Integrated Camera                            | 82        | 1.31%   |
| Acer Integrated 5M Camera                           | 73        | 1.17%   |
| Chicony HP HD Camera                                | 69        | 1.1%    |
| Acer BisonCam, NB Pro                               | 63        | 1.01%   |
| Logitech HD Pro Webcam C920                         | 59        | 0.94%   |
| Lite-On Integrated Camera                           | 53        | 0.85%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 52        | 0.83%   |
| Quanta HP TrueVision HD Camera                      | 51        | 0.82%   |
| Quanta HD User Facing                               | 50        | 0.8%    |
| Chicony USB2.0 HD UVC WebCam                        | 50        | 0.8%    |
| Samsung Galaxy series, misc. (MTP mode)             | 49        | 0.78%   |
| Apple Built-in iSight                               | 48        | 0.77%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 44        | 0.7%    |
| Chicony Integrated 5M Camera                        | 44        | 0.7%    |
| Bison SunplusIT Integrated Camera                   | 43        | 0.69%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 43        | 0.69%   |
| Microdia Integrated Webcam                          | 41        | 0.66%   |
| Chicony Integrated Camera (1280x720@30)             | 40        | 0.64%   |
| Quanta HP HD Camera                                 | 39        | 0.62%   |
| Lite-On HP HD Camera                                | 39        | 0.62%   |
| Chicony HD User Facing                              | 39        | 0.62%   |
| Apple FaceTime HD Camera (Built-in)                 | 37        | 0.59%   |
| Logitech C922 Pro Stream Webcam                     | 35        | 0.56%   |
| Chicony HP TrueVision HD Camera                     | 35        | 0.56%   |
| Sunplus HD WebCam                                   | 34        | 0.54%   |
| Chicony EasyCamera                                  | 34        | 0.54%   |
| Realtek USB Camera                                  | 33        | 0.53%   |
| Bison HD Webcam                                     | 33        | 0.53%   |
| Quanta VGA WebCam                                   | 31        | 0.5%    |
| Sonix USB2.0 HD UVC WebCam                          | 29        | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 491       | 39.98%  |
| Validity Sensors                   | 340       | 27.69%  |
| Shenzhen Goodix Technology         | 147       | 11.97%  |
| Elan Microelectronics              | 64        | 5.21%   |
| Upek                               | 59        | 4.8%    |
| AuthenTec                          | 59        | 4.8%    |
| LighTuning Technology              | 32        | 2.61%   |
| STMicroelectronics                 | 19        | 1.55%   |
| Realtek USB2.0 Finger Print Bridge | 6         | 0.49%   |
| Samsung Electronics                | 4         | 0.33%   |
| Focal-systems.Corp                 | 3         | 0.24%   |
| DigitalPersona                     | 2         | 0.16%   |
| Microsoft                          | 1         | 0.08%   |
| HOLTEK                             | 1         | 0.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 263       | 21.42%  |
| Shenzhen Goodix  Fingerprint Device                                        | 85        | 6.92%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 67        | 5.46%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 61        | 4.97%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 59        | 4.8%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 53        | 4.32%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 52        | 4.23%   |
| Shenzhen Goodix Fingerprint Reader                                         | 40        | 3.26%   |
| Validity Sensors Synaptics WBDI                                            | 38        | 3.09%   |
| Elan ELAN:Fingerprint                                                      | 33        | 2.69%   |
| Elan ELAN:ARM-M4                                                           | 30        | 2.44%   |
| AuthenTec AES2810                                                          | 26        | 2.12%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 25        | 2.04%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 24        | 1.95%   |
| Shenzhen Goodix FingerPrint                                                | 22        | 1.79%   |
| Synaptics Fingerprint reader [HP G6]                                       | 21        | 1.71%   |
| Synaptics WBDI                                                             | 20        | 1.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 20        | 1.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 20        | 1.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 19        | 1.55%   |
| Synaptics  WBDI                                                            | 19        | 1.55%   |
| Validity Sensors VFS491                                                    | 17        | 1.38%   |
| STMicroelectronics Fingerprint Reader                                      | 17        | 1.38%   |
| Synaptics UWP WBDI Device                                                  | 14        | 1.14%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 1.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 0.98%   |
| Synaptics UWP WBDI                                                         | 12        | 0.98%   |
| Validity Sensors VFS Fingerprint sensor                                    | 11        | 0.9%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 0.9%    |
| Validity Sensors Fingerprint scanner                                       | 10        | 0.81%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 0.73%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 8         | 0.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 8         | 0.65%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 0.65%   |
| Upek TCS5B Fingerprint sensor                                              | 6         | 0.49%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 6         | 0.49%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 0.49%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.41%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 5         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 214       | 36.46%  |
| Alcor Micro                | 207       | 35.26%  |
| Upek                       | 36        | 6.13%   |
| Lenovo                     | 34        | 5.79%   |
| O2 Micro                   | 31        | 5.28%   |
| Gemalto (was Gemplus)      | 11        | 1.87%   |
| SCM Microsystems           | 8         | 1.36%   |
| Yubico.com                 | 7         | 1.19%   |
| Advanced Card Systems      | 7         | 1.19%   |
| Clay Logic                 | 6         | 1.02%   |
| Cherry                     | 5         | 0.85%   |
| Realtek Semiconductor      | 4         | 0.68%   |
| Chicony Electronics        | 4         | 0.68%   |
| Aladdin Knowledge Systems  | 4         | 0.68%   |
| Reiner SCT Kartensysteme   | 3         | 0.51%   |
| OmniKey                    | 2         | 0.34%   |
| Hewlett-Packard            | 1         | 0.17%   |
| Feitian Technologies       | 1         | 0.17%   |
| C3PO                       | 1         | 0.17%   |
| Athena Smartcard Solutions | 1         | 0.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 203       | 34.58%  |
| Broadcom 58200                                                               | 63        | 10.73%  |
| Broadcom BCM5880 Secure Applications Processor                               | 58        | 9.88%   |
| Broadcom 5880                                                                | 52        | 8.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 39        | 6.64%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 36        | 6.13%   |
| Lenovo Integrated Smart Card Reader                                          | 33        | 5.62%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 26        | 4.43%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 7         | 1.19%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 5         | 0.85%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 0.85%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 0.68%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 4         | 0.68%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 0.68%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 0.68%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 3         | 0.51%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 3         | 0.51%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.51%   |
| Clay Logic Nitrokey Start                                                    | 3         | 0.51%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.51%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 3         | 0.51%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 2         | 0.34%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.34%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.34%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.34%   |
| Advanced Card Systems ACR122U                                                | 2         | 0.34%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.17%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.17%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.17%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.17%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.17%   |
| OmniKey CardMan 4321                                                         | 1         | 0.17%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.17%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.17%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.17%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.17%   |
| Feitian Technologies SCR301                                                  | 1         | 0.17%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.17%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                   | 1         | 0.17%   |
| C3PO LTC31v2                                                                 | 1         | 0.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 7378      | 59.82%  |
| 1     | 3876      | 31.43%  |
| 2     | 825       | 6.69%   |
| 3     | 183       | 1.48%   |
| 4     | 42        | 0.34%   |
| 5     | 19        | 0.15%   |
| 6     | 8         | 0.06%   |
| 7     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 2319      | 38.79%  |
| Fingerprint reader       | 1222      | 20.44%  |
| Net/wireless             | 549       | 9.18%   |
| Chipcard                 | 515       | 8.61%   |
| Multimedia controller    | 369       | 6.17%   |
| Communication controller | 256       | 4.28%   |
| Unassigned class         | 165       | 2.76%   |
| Camera                   | 135       | 2.26%   |
| Bluetooth                | 110       | 1.84%   |
| Sound                    | 83        | 1.39%   |
| Card reader              | 65        | 1.09%   |
| Storage                  | 50        | 0.84%   |
| Net/ethernet             | 46        | 0.77%   |
| Network                  | 24        | 0.4%    |
| Storage/raid             | 16        | 0.27%   |
| Modem                    | 15        | 0.25%   |
| Storage/ide              | 9         | 0.15%   |
| Flash memory             | 7         | 0.12%   |
| Dvb card                 | 7         | 0.12%   |
| Wireless                 | 5         | 0.08%   |
| Tv card                  | 5         | 0.08%   |
| Firewire controller      | 3         | 0.05%   |
| Storage/nvme             | 2         | 0.03%   |
| Storage/ata              | 1         | 0.02%   |

