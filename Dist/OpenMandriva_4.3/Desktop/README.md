OpenMandriva 4.3 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

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

Total: 1940

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0VHWTR A01                  | [7544868958](https://linux-hardware.org/?probe=7544868958) | Feb 01, 2023 |
| ASUSTek       | Z97-K                       | [e3f865cd20](https://linux-hardware.org/?probe=e3f865cd20) | Jan 28, 2023 |
| Dell          | 0773VG A00                  | [328dae4014](https://linux-hardware.org/?probe=328dae4014) | Jan 26, 2023 |
| HP            | 3048h                       | [caabf4189f](https://linux-hardware.org/?probe=caabf4189f) | Jan 25, 2023 |
| AZW           | U59                         | [6d2b672b77](https://linux-hardware.org/?probe=6d2b672b77) | Jan 25, 2023 |
| ASRock        | 775XFire-VSTA               | [e80788f790](https://linux-hardware.org/?probe=e80788f790) | Jan 24, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [dcecec2239](https://linux-hardware.org/?probe=dcecec2239) | Jan 22, 2023 |
| Gigabyte      | N3050ND3H                   | [1663928526](https://linux-hardware.org/?probe=1663928526) | Jan 21, 2023 |
| ASUSTek       | Z77-A                       | [10081492a7](https://linux-hardware.org/?probe=10081492a7) | Jan 19, 2023 |
| ASUSTek       | C60M1-I                     | [defd3912ae](https://linux-hardware.org/?probe=defd3912ae) | Jan 18, 2023 |
| Unknown       | HX90                        | [2b034e44e2](https://linux-hardware.org/?probe=2b034e44e2) | Jan 18, 2023 |
| Medion        | MS-7621                     | [67b535d88f](https://linux-hardware.org/?probe=67b535d88f) | Jan 18, 2023 |
| Gigabyte      | F2A55M-HD2                  | [74a62575d2](https://linux-hardware.org/?probe=74a62575d2) | Jan 17, 2023 |
| ASUSTek       | P8B75-V                     | [276102bb1a](https://linux-hardware.org/?probe=276102bb1a) | Jan 16, 2023 |
| Lenovo        | SDK0F82993 WIN              | [48f294dfb4](https://linux-hardware.org/?probe=48f294dfb4) | Jan 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [291dceb273](https://linux-hardware.org/?probe=291dceb273) | Jan 14, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [79d2961429](https://linux-hardware.org/?probe=79d2961429) | Jan 14, 2023 |
| HP            | 8054                        | [faf1c97cea](https://linux-hardware.org/?probe=faf1c97cea) | Jan 14, 2023 |
| HP            | 18E5                        | [614faa708b](https://linux-hardware.org/?probe=614faa708b) | Jan 14, 2023 |
| Pegatron      | IPM41-D3                    | [23a918874b](https://linux-hardware.org/?probe=23a918874b) | Jan 14, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [12f29d53ba](https://linux-hardware.org/?probe=12f29d53ba) | Jan 13, 2023 |
| Gigabyte      | H81M-S2PV                   | [72e7e2e1cf](https://linux-hardware.org/?probe=72e7e2e1cf) | Jan 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [805d82d697](https://linux-hardware.org/?probe=805d82d697) | Jan 10, 2023 |
| Gigabyte      | H170-D3H-CF                 | [8064745798](https://linux-hardware.org/?probe=8064745798) | Jan 10, 2023 |
| HP            | 0AA4h                       | [e0776de36f](https://linux-hardware.org/?probe=e0776de36f) | Jan 09, 2023 |
| HP            | 802F                        | [1dd3655605](https://linux-hardware.org/?probe=1dd3655605) | Jan 09, 2023 |
| Gigabyte      | Z68XP-UD3                   | [e2f62062de](https://linux-hardware.org/?probe=e2f62062de) | Jan 09, 2023 |
| Dell          | 0654JC A01                  | [c3016e1823](https://linux-hardware.org/?probe=c3016e1823) | Jan 09, 2023 |
| HP            | 8265                        | [83897e98cf](https://linux-hardware.org/?probe=83897e98cf) | Jan 08, 2023 |
| MSI           | 990XA-GD55                  | [b4525a8431](https://linux-hardware.org/?probe=b4525a8431) | Jan 08, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [c1c8654cde](https://linux-hardware.org/?probe=c1c8654cde) | Jan 07, 2023 |
| Acer          | Veriton N4640G              | [3392dd3c90](https://linux-hardware.org/?probe=3392dd3c90) | Jan 07, 2023 |
| Alienware     | 04VWF2 A02                  | [15f4ed4e31](https://linux-hardware.org/?probe=15f4ed4e31) | Jan 07, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ddeffc27a7](https://linux-hardware.org/?probe=ddeffc27a7) | Jan 05, 2023 |
| Pegatron      | 2AC3                        | [4ce129e600](https://linux-hardware.org/?probe=4ce129e600) | Jan 05, 2023 |
| Dell          | 0M5DCD A00                  | [c64a1198cd](https://linux-hardware.org/?probe=c64a1198cd) | Jan 04, 2023 |
| MSI           | A88X-G45 GAMING             | [1caf5c85d9](https://linux-hardware.org/?probe=1caf5c85d9) | Jan 04, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | [55627fc077](https://linux-hardware.org/?probe=55627fc077) | Jan 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [5f0eeeb9e7](https://linux-hardware.org/?probe=5f0eeeb9e7) | Jan 03, 2023 |
| Dell          | 0XCR8D A03                  | [faccba61cf](https://linux-hardware.org/?probe=faccba61cf) | Jan 03, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [afe5105302](https://linux-hardware.org/?probe=afe5105302) | Jan 03, 2023 |
| ASUSTek       | Berkeley                    | [746d7be693](https://linux-hardware.org/?probe=746d7be693) | Jan 03, 2023 |
| Dell          | 0MM599                      | [95763443e3](https://linux-hardware.org/?probe=95763443e3) | Jan 03, 2023 |
| ASRock        | B450M-HDV R4.0              | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| Gigabyte      | H61M-S2PV                   | [85ad98c994](https://linux-hardware.org/?probe=85ad98c994) | Jan 02, 2023 |
| AZW           | MINI S                      | [ad7c4329eb](https://linux-hardware.org/?probe=ad7c4329eb) | Jan 02, 2023 |
| Gigabyte      | B550M DS3H                  | [509cc939cc](https://linux-hardware.org/?probe=509cc939cc) | Jan 01, 2023 |
| OEM           | Intel H81                   | [1700a7a4c7](https://linux-hardware.org/?probe=1700a7a4c7) | Jan 01, 2023 |
| Gigabyte      | B365 HD3                    | [195240c264](https://linux-hardware.org/?probe=195240c264) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | UN45                        | [bde2e2efb1](https://linux-hardware.org/?probe=bde2e2efb1) | Dec 31, 2022 |
| MSI           | MS-7502 Fab D               | [9126e1035f](https://linux-hardware.org/?probe=9126e1035f) | Dec 31, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [b0dd8fc6b5](https://linux-hardware.org/?probe=b0dd8fc6b5) | Dec 31, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [3258ffa0c1](https://linux-hardware.org/?probe=3258ffa0c1) | Dec 29, 2022 |
| Gigabyte      | H61M-D2H                    | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| MSI           | Z97 PC Mate                 | [1b7e70ab6e](https://linux-hardware.org/?probe=1b7e70ab6e) | Dec 29, 2022 |
| ASUSTek       | P5K SE/EPU                  | [3f0c89985c](https://linux-hardware.org/?probe=3f0c89985c) | Dec 29, 2022 |
| Gigabyte      | MJPLNBB-00                  | [879a5b77ff](https://linux-hardware.org/?probe=879a5b77ff) | Dec 28, 2022 |
| Dell          | 0HN7XN A01                  | [43a0d87199](https://linux-hardware.org/?probe=43a0d87199) | Dec 28, 2022 |
| Pegatron      | APX85-GS                    | [82db9f15c6](https://linux-hardware.org/?probe=82db9f15c6) | Dec 27, 2022 |
| Acer          | Aspire TC-865 V:1.1         | [0c8add55fe](https://linux-hardware.org/?probe=0c8add55fe) | Dec 27, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [bc68280036](https://linux-hardware.org/?probe=bc68280036) | Dec 26, 2022 |
| Lenovo        | SHARKBAY NOK                | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| Gigabyte      | G41MT-S2PT                  | [14611d6c99](https://linux-hardware.org/?probe=14611d6c99) | Dec 26, 2022 |
| HP            | 2AF7                        | [96344d97ba](https://linux-hardware.org/?probe=96344d97ba) | Dec 26, 2022 |
| Gigabyte      | B450M S2H                   | [500abd4186](https://linux-hardware.org/?probe=500abd4186) | Dec 25, 2022 |
| ASUSTek       | NARRA3                      | [cc0a64d0df](https://linux-hardware.org/?probe=cc0a64d0df) | Dec 25, 2022 |
| Pegatron      | IPPPV-D3G                   | [4d1a2299dc](https://linux-hardware.org/?probe=4d1a2299dc) | Dec 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [9e269ee2a4](https://linux-hardware.org/?probe=9e269ee2a4) | Dec 24, 2022 |
| ASRock        | FM2A68M-DG3+                | [11eb39826a](https://linux-hardware.org/?probe=11eb39826a) | Dec 24, 2022 |
| Dell          | 0J3C2F A00                  | [f993ebb9ed](https://linux-hardware.org/?probe=f993ebb9ed) | Dec 23, 2022 |
| MSI           | 880GM-E41                   | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | [561b98afc3](https://linux-hardware.org/?probe=561b98afc3) | Dec 23, 2022 |
| Dell          | 0JJW8N A03                  | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| ASRock        | FM2A88M-HD+                 | [18b83ae613](https://linux-hardware.org/?probe=18b83ae613) | Dec 22, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [003ac98d7f](https://linux-hardware.org/?probe=003ac98d7f) | Dec 21, 2022 |
| PERTOSA       | GA-H110TN-M                 | [048d8cca49](https://linux-hardware.org/?probe=048d8cca49) | Dec 21, 2022 |
| Dell          | 0VHWTR A01                  | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| ECS           | G31T-M7                     | [327ac25b68](https://linux-hardware.org/?probe=327ac25b68) | Dec 20, 2022 |
| Gigabyte      | 945GCMX-S2                  | [3b9937e6df](https://linux-hardware.org/?probe=3b9937e6df) | Dec 20, 2022 |
| MSI           | H81M-E34                    | [3aa811568d](https://linux-hardware.org/?probe=3aa811568d) | Dec 19, 2022 |
| ASUSTek       | P5QL PRO                    | [5f3343c803](https://linux-hardware.org/?probe=5f3343c803) | Dec 19, 2022 |
| Gigabyte      | H61M-DS2                    | [b5c4e6cf61](https://linux-hardware.org/?probe=b5c4e6cf61) | Dec 19, 2022 |
| Dell          | 0M858N A00                  | [e46a95080d](https://linux-hardware.org/?probe=e46a95080d) | Dec 18, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [71ebf721cc](https://linux-hardware.org/?probe=71ebf721cc) | Dec 17, 2022 |
| HP            | 8055                        | [6c7fa83dc9](https://linux-hardware.org/?probe=6c7fa83dc9) | Dec 17, 2022 |
| Dell          | 0RW203                      | [2f5bede488](https://linux-hardware.org/?probe=2f5bede488) | Dec 16, 2022 |
| Gigabyte      | F2A85X-UP4                  | [80358a5ba1](https://linux-hardware.org/?probe=80358a5ba1) | Dec 15, 2022 |
| Acer          | Veriton N2620G              | [a626bf668e](https://linux-hardware.org/?probe=a626bf668e) | Dec 15, 2022 |
| Pegatron      | IPM41-D3                    | [a41e0d92a7](https://linux-hardware.org/?probe=a41e0d92a7) | Dec 15, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [ffe60f958c](https://linux-hardware.org/?probe=ffe60f958c) | Dec 15, 2022 |
| Dell          | 0FR6WH A01                  | [46d6c645fe](https://linux-hardware.org/?probe=46d6c645fe) | Dec 15, 2022 |
| Gigabyte      | F2A68HM-H                   | [f18234034f](https://linux-hardware.org/?probe=f18234034f) | Dec 15, 2022 |
| HP            | 2AFB                        | [4c57ea0ee7](https://linux-hardware.org/?probe=4c57ea0ee7) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [587fac961e](https://linux-hardware.org/?probe=587fac961e) | Dec 15, 2022 |
| Dell          | 0VD92X A00                  | [9feb549665](https://linux-hardware.org/?probe=9feb549665) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0a564c9f0f](https://linux-hardware.org/?probe=0a564c9f0f) | Dec 14, 2022 |
| Datto         | SSD                         | [a9bff0a51c](https://linux-hardware.org/?probe=a9bff0a51c) | Dec 14, 2022 |
| HP            | 304Ah                       | [d8b600f39e](https://linux-hardware.org/?probe=d8b600f39e) | Dec 13, 2022 |
| ECS           | H61H2-M2                    | [8525777743](https://linux-hardware.org/?probe=8525777743) | Dec 13, 2022 |
| Dell          | 0T10XW A02                  | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| ASUSTek       | Z10PH-D16 Series            | [18911cf243](https://linux-hardware.org/?probe=18911cf243) | Dec 13, 2022 |
| Gigabyte      | H310M S2V                   | [6895902fe7](https://linux-hardware.org/?probe=6895902fe7) | Dec 12, 2022 |
| ASUSTek       | AM1M-A                      | [260a382d54](https://linux-hardware.org/?probe=260a382d54) | Dec 12, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [62f6fd5f8d](https://linux-hardware.org/?probe=62f6fd5f8d) | Dec 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [9537bff125](https://linux-hardware.org/?probe=9537bff125) | Dec 11, 2022 |
| Dell          | 0KG317                      | [cf7f697a0a](https://linux-hardware.org/?probe=cf7f697a0a) | Dec 11, 2022 |
| ASUSTek       | P8Z77-V LX                  | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| Dell          | 01TKCC A01                  | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| HP            | 18E7                        | [9759493e06](https://linux-hardware.org/?probe=9759493e06) | Dec 09, 2022 |
| ASRock        | 945GCM-S                    | [926787ea67](https://linux-hardware.org/?probe=926787ea67) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| Dell          | 0P301D A02                  | [8ab7a916f1](https://linux-hardware.org/?probe=8ab7a916f1) | Dec 08, 2022 |
| MSI           | 760GM-P23                   | [29337f7359](https://linux-hardware.org/?probe=29337f7359) | Dec 08, 2022 |
| ASRock        | B550 Taichi                 | [0203e79add](https://linux-hardware.org/?probe=0203e79add) | Dec 08, 2022 |
| Gigabyte      | Z370M D3H-CF                | [dabda33265](https://linux-hardware.org/?probe=dabda33265) | Dec 07, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [c3fc86b5d4](https://linux-hardware.org/?probe=c3fc86b5d4) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [664d064b07](https://linux-hardware.org/?probe=664d064b07) | Dec 06, 2022 |
| Lenovo        | 0x36A017AA 31900058 STD     | [ccc212b757](https://linux-hardware.org/?probe=ccc212b757) | Dec 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| Intel         | HURONRIVER                  | [d8a4f4a923](https://linux-hardware.org/?probe=d8a4f4a923) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| ECS           | 945P/PL-A                   | [8db8eec28d](https://linux-hardware.org/?probe=8db8eec28d) | Dec 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [fa3aeacc17](https://linux-hardware.org/?probe=fa3aeacc17) | Dec 05, 2022 |
| Dell          | 0M863N A01                  | [ee8183087b](https://linux-hardware.org/?probe=ee8183087b) | Dec 04, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [e98fcde376](https://linux-hardware.org/?probe=e98fcde376) | Dec 04, 2022 |
| Lenovo        | SHARKBAY NOK                | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [1dbda8e648](https://linux-hardware.org/?probe=1dbda8e648) | Dec 04, 2022 |
| Acer          | Aspire X3950                | [96044c1932](https://linux-hardware.org/?probe=96044c1932) | Dec 03, 2022 |
| ASUSTek       | H97-PLUS                    | [c79b15a3cf](https://linux-hardware.org/?probe=c79b15a3cf) | Dec 03, 2022 |
| HP            | 8648                        | [79673ee467](https://linux-hardware.org/?probe=79673ee467) | Dec 02, 2022 |
| ASUSTek       | P7P55D PRO                  | [b566591b3c](https://linux-hardware.org/?probe=b566591b3c) | Dec 02, 2022 |
| ASUSTek       | M5A97 PLUS                  | [63820e3937](https://linux-hardware.org/?probe=63820e3937) | Dec 01, 2022 |
| ASUSTek       | PRIME B250M-K               | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| Medion        | MS-7748                     | [0e92aa55ca](https://linux-hardware.org/?probe=0e92aa55ca) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| Medion        | MS-7800                     | [a5658a6933](https://linux-hardware.org/?probe=a5658a6933) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | [1d20e4ba6d](https://linux-hardware.org/?probe=1d20e4ba6d) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| ECS           | 945P/PL-A                   | [ff47651dd8](https://linux-hardware.org/?probe=ff47651dd8) | Nov 29, 2022 |
| Biostar       | H81MHV3 5.0                 | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Gigabyte      | B450 AORUS M                | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| ASRock        | B550M-ITX/ac                | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | [c218724cb4](https://linux-hardware.org/?probe=c218724cb4) | Nov 27, 2022 |
| MSI           | Z77MA-G45                   | [feb165c344](https://linux-hardware.org/?probe=feb165c344) | Nov 27, 2022 |
| ASRock        | A88M-G                      | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| MSI           | P55-CD53                    | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| HP            | 3397                        | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [9419d2017e](https://linux-hardware.org/?probe=9419d2017e) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2L                   | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| HP            | 0AECh D                     | [857616948b](https://linux-hardware.org/?probe=857616948b) | Nov 26, 2022 |
| HP            | 1589                        | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | [7948a35f59](https://linux-hardware.org/?probe=7948a35f59) | Nov 25, 2022 |
| HP            | 2215                        | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| Wistron       | ProLiant ML110 G6           | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| Foxconn       | 2A92                        | [e21715c047](https://linux-hardware.org/?probe=e21715c047) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| Foxconn       | 2ADA                        | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| Wistron       | ProLiant ML110 G5           | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| Dell          | 0M863N A01                  | [ca7e5eab8d](https://linux-hardware.org/?probe=ca7e5eab8d) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| Intel         | DG41TY AAE47335-302         | [ae2fb8d0b3](https://linux-hardware.org/?probe=ae2fb8d0b3) | Nov 22, 2022 |
| HP            | 3399                        | [bce6df1ffb](https://linux-hardware.org/?probe=bce6df1ffb) | Nov 21, 2022 |
| ASUSTek       | F1A55-M LE                  | [f2120128c1](https://linux-hardware.org/?probe=f2120128c1) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASRock        | B450M Steel Legend          | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Pegatron      | NARRA5                      | [d8632e2872](https://linux-hardware.org/?probe=d8632e2872) | Nov 21, 2022 |
| ASRock        | P67 Extreme4                | [569fd8178d](https://linux-hardware.org/?probe=569fd8178d) | Nov 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [049f06f11d](https://linux-hardware.org/?probe=049f06f11d) | Nov 21, 2022 |
| AZW           | SEi                         | [a8e813c483](https://linux-hardware.org/?probe=a8e813c483) | Nov 21, 2022 |
| Dell          | 00NNT0 A00                  | [c25787d8b9](https://linux-hardware.org/?probe=c25787d8b9) | Nov 20, 2022 |
| ASUSTek       | H81M-PLUS                   | [880e6565e8](https://linux-hardware.org/?probe=880e6565e8) | Nov 20, 2022 |
| ASUSTek       | Z97-C                       | [733140c078](https://linux-hardware.org/?probe=733140c078) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI             | [5b31194732](https://linux-hardware.org/?probe=5b31194732) | Nov 20, 2022 |
| Shuttle       | FS61                        | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| Pegatron      | 2A94h                       | [be99475703](https://linux-hardware.org/?probe=be99475703) | Nov 19, 2022 |
| ECS           | G41T-M7                     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Intel         | X99                         | [c95c1d173b](https://linux-hardware.org/?probe=c95c1d173b) | Nov 18, 2022 |
| TPV-INVENT... | 2AC6 A01                    | [04b3ba4242](https://linux-hardware.org/?probe=04b3ba4242) | Nov 18, 2022 |
| Gigabyte      | 970A-DS3P                   | [fc7b21bd04](https://linux-hardware.org/?probe=fc7b21bd04) | Nov 18, 2022 |
| Gigabyte      | A520M H                     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Huanan        | X99-8M-F V1.1               | [b1d1b0ad4c](https://linux-hardware.org/?probe=b1d1b0ad4c) | Nov 18, 2022 |
| ASUSTek       | P5KPL/1600                  | [24b13d1967](https://linux-hardware.org/?probe=24b13d1967) | Nov 16, 2022 |
| HP            | 843B                        | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| Intel         | H61                         | [faeac27433](https://linux-hardware.org/?probe=faeac27433) | Nov 16, 2022 |
| Medion        | MS-7728                     | [813d86814d](https://linux-hardware.org/?probe=813d86814d) | Nov 16, 2022 |
| Acer          | Veriton N4630G              | [f4566a57a9](https://linux-hardware.org/?probe=f4566a57a9) | Nov 16, 2022 |
| ALDO          | C2016-BSWI-D2               | [0e4c4c6806](https://linux-hardware.org/?probe=0e4c4c6806) | Nov 16, 2022 |
| AZW           | Gemini M                    | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| ASUSTek       | H81M-A                      | [ff63827781](https://linux-hardware.org/?probe=ff63827781) | Nov 15, 2022 |
| ASRock        | B450M Steel Legend          | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| HP            | 22F8                        | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | [2d904e2be7](https://linux-hardware.org/?probe=2d904e2be7) | Nov 13, 2022 |
| HP            | 84FD                        | [6ee4b6828c](https://linux-hardware.org/?probe=6ee4b6828c) | Nov 13, 2022 |
| Deltron       | H81H3-M4                    | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| MSI           | H97 GUARD-PRO               | [3ea9d7a74a](https://linux-hardware.org/?probe=3ea9d7a74a) | Nov 13, 2022 |
| Gigabyte      | H87-HD3                     | [e5a8d4700d](https://linux-hardware.org/?probe=e5a8d4700d) | Nov 12, 2022 |
| ASRock        | B450M Pro4 R2.0             | [c5952a73e7](https://linux-hardware.org/?probe=c5952a73e7) | Nov 12, 2022 |
| ASUSTek       | H81M-K                      | [052f42f29a](https://linux-hardware.org/?probe=052f42f29a) | Nov 12, 2022 |
| ASUSTek       | P5K SE/EPU                  | [d5e58b3718](https://linux-hardware.org/?probe=d5e58b3718) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| ASRock        | B365M Pro4-F                | [aa006ea111](https://linux-hardware.org/?probe=aa006ea111) | Nov 10, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [4488e0a71a](https://linux-hardware.org/?probe=4488e0a71a) | Nov 10, 2022 |
| Acer          | RS880M05                    | [cb216f090c](https://linux-hardware.org/?probe=cb216f090c) | Nov 09, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [fb87099a0d](https://linux-hardware.org/?probe=fb87099a0d) | Nov 09, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [ac916f47fc](https://linux-hardware.org/?probe=ac916f47fc) | Nov 08, 2022 |
| ASUSTek       | P5E-VM SE                   | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| Acer          | Aspire X1700                | [764516b8f0](https://linux-hardware.org/?probe=764516b8f0) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| ASRock        | Z170 Extreme4               | [f0b56da15d](https://linux-hardware.org/?probe=f0b56da15d) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [09c5b6e39e](https://linux-hardware.org/?probe=09c5b6e39e) | Nov 06, 2022 |
| Pegatron      | 2AE3                        | [19ae75aacc](https://linux-hardware.org/?probe=19ae75aacc) | Nov 06, 2022 |
| ASRock        | 4CoreDual-SATA2             | [e1a81edea7](https://linux-hardware.org/?probe=e1a81edea7) | Nov 05, 2022 |
| MSI           | GF615M-P33                  | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| HP            | 2820h                       | [6378a2e9c3](https://linux-hardware.org/?probe=6378a2e9c3) | Nov 05, 2022 |
| VS Company    | MCP61M                      | [ef6adc510d](https://linux-hardware.org/?probe=ef6adc510d) | Nov 05, 2022 |
| ASUSTek       | H170I-PLUS D3               | [74df37995c](https://linux-hardware.org/?probe=74df37995c) | Nov 04, 2022 |
| ASUSTek       | PRIME B365M-K               | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| Acer          | Aspire X1430                | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| ASUSTek       | M4A78 PLUS                  | [bac044cd22](https://linux-hardware.org/?probe=bac044cd22) | Oct 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | [c23efa8caa](https://linux-hardware.org/?probe=c23efa8caa) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Apple         | Mac-F221BEC8                | [12b6232cdd](https://linux-hardware.org/?probe=12b6232cdd) | Oct 30, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [2a7d6b757b](https://linux-hardware.org/?probe=2a7d6b757b) | Oct 29, 2022 |
| MSI           | P45 Platinum                | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| ASUSTek       | M5A87                       | [88e6b582c9](https://linux-hardware.org/?probe=88e6b582c9) | Oct 28, 2022 |
| Dell          | 0WMJ54 A01                  | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| Unknown       | Unknown                     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| ASUSTek       | P8B75-V                     | [ca5c26654a](https://linux-hardware.org/?probe=ca5c26654a) | Oct 27, 2022 |
| ASRock        | B550M-HDV                   | [4d5068a3be](https://linux-hardware.org/?probe=4d5068a3be) | Oct 27, 2022 |
| Acer          | Veriton M275                | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Dell          | 0WR7PY A03                  | [fa0daeab26](https://linux-hardware.org/?probe=fa0daeab26) | Oct 26, 2022 |
| Acer          | Veriton NBU                 | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| Gigabyte      | G41MT-S2PT                  | [2fb43f4be2](https://linux-hardware.org/?probe=2fb43f4be2) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | [218d55e0ca](https://linux-hardware.org/?probe=218d55e0ca) | Oct 25, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| Dell          | 0GX297                      | [a047bbd7a0](https://linux-hardware.org/?probe=a047bbd7a0) | Oct 24, 2022 |
| ASRock        | N68-VS3 UCC                 | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Gigabyte      | H310M S2H x.x               | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| ASUSTek       | P5QL-E                      | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| Acer          | WMCP78M                     | [f4e3945dea](https://linux-hardware.org/?probe=f4e3945dea) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| ASRock        | B450M Pro4                  | [12b83ecfd4](https://linux-hardware.org/?probe=12b83ecfd4) | Oct 22, 2022 |
| Dell          | 0HX555                      | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| Philco        | DTC-A55                     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| Acer          | WG43M                       | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Gigabyte      | GA-790FXTA-UD5              | [78218a5b63](https://linux-hardware.org/?probe=78218a5b63) | Oct 21, 2022 |
| MSI           | H61M-P20                    | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6c32002395](https://linux-hardware.org/?probe=6c32002395) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| HP            | 1825                        | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| Dell          | 0M5DCD A00                  | [e14791bb51](https://linux-hardware.org/?probe=e14791bb51) | Oct 19, 2022 |
| HP            | 805D                        | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| Intel         | DH61BF AAG81311-101         | [770d8bf876](https://linux-hardware.org/?probe=770d8bf876) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| ASUSTek       | P5KPL-E                     | [2f1e1cbbf4](https://linux-hardware.org/?probe=2f1e1cbbf4) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | [5823a0c5d0](https://linux-hardware.org/?probe=5823a0c5d0) | Oct 18, 2022 |
| Dell          | 02YYK5 A01                  | [5872b35f8c](https://linux-hardware.org/?probe=5872b35f8c) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| ASRock        | Z87 Pro3                    | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Dell          | 0XFWHV A00                  | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| HP            | 1850                        | [eda9bb7861](https://linux-hardware.org/?probe=eda9bb7861) | Oct 15, 2022 |
| Gigabyte      | H61M-D2H                    | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| Intel         | DP45SG AAE27733-403         | [f391a78f4d](https://linux-hardware.org/?probe=f391a78f4d) | Oct 15, 2022 |
| ASUSTek       | PRIME H510M-A               | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| Gigabyte      | F2A55M-DS2                  | [1feb9942e8](https://linux-hardware.org/?probe=1feb9942e8) | Oct 14, 2022 |
| ASUSTek       | PRIME H410M-A               | [8dc5e6f530](https://linux-hardware.org/?probe=8dc5e6f530) | Oct 14, 2022 |
| ASUSTek       | PRIME B450M-A II            | [6144d2247a](https://linux-hardware.org/?probe=6144d2247a) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| HP            | 1497                        | [ff6d690da4](https://linux-hardware.org/?probe=ff6d690da4) | Oct 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| ASUSTek       | PRIME H410M-A               | [dc990d0395](https://linux-hardware.org/?probe=dc990d0395) | Oct 12, 2022 |
| AMD           | A88                         | [1ee2502537](https://linux-hardware.org/?probe=1ee2502537) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| Dell          | 0T656F A01                  | [1680fa50c0](https://linux-hardware.org/?probe=1680fa50c0) | Oct 11, 2022 |
| HP            | 2171                        | [105af7e899](https://linux-hardware.org/?probe=105af7e899) | Oct 11, 2022 |
| Gigabyte      | B75M-D3H                    | [4bc40092b2](https://linux-hardware.org/?probe=4bc40092b2) | Oct 11, 2022 |
| Lenovo        | ThinkCentre M58 7359WES     | [1c00ee45c1](https://linux-hardware.org/?probe=1c00ee45c1) | Oct 11, 2022 |
| ASRock        | G41C-GS R2.0                | [92ab2501ea](https://linux-hardware.org/?probe=92ab2501ea) | Oct 11, 2022 |
| Acer          | Aspire XC-230               | [d213bca85f](https://linux-hardware.org/?probe=d213bca85f) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| ASUSTek       | PRIME H410I-PLUS            | [10709dd95e](https://linux-hardware.org/?probe=10709dd95e) | Oct 10, 2022 |
| Gigabyte      | F2A58M-HD2                  | [a219433035](https://linux-hardware.org/?probe=a219433035) | Oct 10, 2022 |
| AZW           | U59                         | [8300f61a93](https://linux-hardware.org/?probe=8300f61a93) | Oct 10, 2022 |
| HP            | 805D                        | [8938f51322](https://linux-hardware.org/?probe=8938f51322) | Oct 09, 2022 |
| Lenovo        | Dory CRB                    | [33ae78632a](https://linux-hardware.org/?probe=33ae78632a) | Oct 09, 2022 |
| ASUSTek       | PRIME Z590-P                | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| Chuwi         | RZBOX                       | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| MSI           | A55M-P33                    | [127b8f180e](https://linux-hardware.org/?probe=127b8f180e) | Oct 08, 2022 |
| ASRock        | M3N78D FX                   | [e40ba3988f](https://linux-hardware.org/?probe=e40ba3988f) | Oct 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [feb96964b1](https://linux-hardware.org/?probe=feb96964b1) | Oct 08, 2022 |
| Dell          | 0MN1TX A01                  | [a9faf44fe8](https://linux-hardware.org/?probe=a9faf44fe8) | Oct 07, 2022 |
| MSI           | H110M PRO-VH PLUS           | [9dc72dc357](https://linux-hardware.org/?probe=9dc72dc357) | Oct 07, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [7a7bc387f4](https://linux-hardware.org/?probe=7a7bc387f4) | Oct 06, 2022 |
| Medion        | MS-7797                     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| ASUSTek       | M2V-MX                      | [55b3f7f6b0](https://linux-hardware.org/?probe=55b3f7f6b0) | Oct 06, 2022 |
| HP            | 18E4                        | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Dell          | 01TKCC A01                  | [65103a04c3](https://linux-hardware.org/?probe=65103a04c3) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| ASUSTek       | P5W DH Deluxe               | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Intel         | H55                         | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | [f6a6361e08](https://linux-hardware.org/?probe=f6a6361e08) | Oct 03, 2022 |
| ASRock        | G41C-GS R2.0                | [c6e6708366](https://linux-hardware.org/?probe=c6e6708366) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M58p 6234FB9    | [3c772e3e1d](https://linux-hardware.org/?probe=3c772e3e1d) | Oct 02, 2022 |
| MSI           | A75A-G35                    | [66b1d71092](https://linux-hardware.org/?probe=66b1d71092) | Oct 02, 2022 |
| Biostar       | A75MG                       | [ba1785b4b6](https://linux-hardware.org/?probe=ba1785b4b6) | Oct 02, 2022 |
| MSI           | B75MA-E33                   | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | [ce1567bb35](https://linux-hardware.org/?probe=ce1567bb35) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| MSI           | MS-7235                     | [838e2c27f1](https://linux-hardware.org/?probe=838e2c27f1) | Oct 01, 2022 |
| Lenovo        | 0x30F617AA NOK              | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| MSI           | B350M PRO-VDH               | [1a0d8b695d](https://linux-hardware.org/?probe=1a0d8b695d) | Oct 01, 2022 |
| Lenovo        | 3098 NOK                    | [a46521af41](https://linux-hardware.org/?probe=a46521af41) | Oct 01, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [982b143d73](https://linux-hardware.org/?probe=982b143d73) | Oct 01, 2022 |
| ASUSTek       | M5A78L-M LX                 | [d967f57569](https://linux-hardware.org/?probe=d967f57569) | Oct 01, 2022 |
| ASUSTek       | M5A87                       | [89ca067566](https://linux-hardware.org/?probe=89ca067566) | Oct 01, 2022 |
| Gigabyte      | GA-970A-D3                  | [8c24fa2271](https://linux-hardware.org/?probe=8c24fa2271) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| ASRock        | B450M Pro4-F                | [75b0aa3c75](https://linux-hardware.org/?probe=75b0aa3c75) | Sep 30, 2022 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | [a6b14fdcf3](https://linux-hardware.org/?probe=a6b14fdcf3) | Sep 30, 2022 |
| Acer          | Batman A01                  | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | PRIME B450M-A               | [cfe1aba7e6](https://linux-hardware.org/?probe=cfe1aba7e6) | Sep 30, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [66877298d4](https://linux-hardware.org/?probe=66877298d4) | Sep 30, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Corei... | [a40d59533c](https://linux-hardware.org/?probe=a40d59533c) | Sep 29, 2022 |
| Acer          | Veriton M275                | [f871926a8e](https://linux-hardware.org/?probe=f871926a8e) | Sep 29, 2022 |
| Intel         | DQ67SW AAG12527-310         | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | [5a7ad7dba9](https://linux-hardware.org/?probe=5a7ad7dba9) | Sep 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [3bafc34ffc](https://linux-hardware.org/?probe=3bafc34ffc) | Sep 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [8749a17d26](https://linux-hardware.org/?probe=8749a17d26) | Sep 25, 2022 |
| ASUSTek       | CM1740                      | [6ebc913933](https://linux-hardware.org/?probe=6ebc913933) | Sep 25, 2022 |
| Dell          | 0NV0M7 A02                  | [02925c7220](https://linux-hardware.org/?probe=02925c7220) | Sep 24, 2022 |
| MSI           | Z390-A PRO                  | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| ASRock        | X300M-STX                   | [c354f2b293](https://linux-hardware.org/?probe=c354f2b293) | Sep 24, 2022 |
| Intel         | DG41WV AAE90316-103         | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Dell          | 0M5DCD A00                  | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| Dell          | 0PTTT9 A00                  | [21bde061e9](https://linux-hardware.org/?probe=21bde061e9) | Sep 23, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| ASUSTek       | PRIME B560M-A AC            | [a99682c38d](https://linux-hardware.org/?probe=a99682c38d) | Sep 23, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| HP            | 1998                        | [5148539ae1](https://linux-hardware.org/?probe=5148539ae1) | Sep 21, 2022 |
| MACHINIST     | B75 PRO V1.0                | [752cb8efae](https://linux-hardware.org/?probe=752cb8efae) | Sep 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [a82f4ceccc](https://linux-hardware.org/?probe=a82f4ceccc) | Sep 20, 2022 |
| Lenovo        | 3728 SDK0R32862 WIN 3258... | [d78d85bde3](https://linux-hardware.org/?probe=d78d85bde3) | Sep 20, 2022 |
| HP            | 2B34                        | [a9e82bbb40](https://linux-hardware.org/?probe=a9e82bbb40) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| HP            | 2B29                        | [391e407d29](https://linux-hardware.org/?probe=391e407d29) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| HP            | 843F                        | [7694ed2ffa](https://linux-hardware.org/?probe=7694ed2ffa) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [f75308c465](https://linux-hardware.org/?probe=f75308c465) | Sep 17, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| HP            | 1495                        | [462389df36](https://linux-hardware.org/?probe=462389df36) | Sep 14, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [832824de54](https://linux-hardware.org/?probe=832824de54) | Sep 14, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [6ee9d3e2c4](https://linux-hardware.org/?probe=6ee9d3e2c4) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Gigabyte      | X570 AORUS PRO              | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| MSI           | Z97 MPOWER                  | [a98aedda05](https://linux-hardware.org/?probe=a98aedda05) | Sep 13, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [0937dcb89c](https://linux-hardware.org/?probe=0937dcb89c) | Sep 12, 2022 |
| ASRock        | X99 Taichi                  | [2eb979e980](https://linux-hardware.org/?probe=2eb979e980) | Sep 12, 2022 |
| Dell          | 0H8052                      | [1ade497706](https://linux-hardware.org/?probe=1ade497706) | Sep 12, 2022 |
| Gigabyte      | EX58-UD3R                   | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| Shuttle       | XH310V2                     | [c99efae947](https://linux-hardware.org/?probe=c99efae947) | Sep 12, 2022 |
| MSI           | MAG Z390M MORTAR            | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| HP            | 158B                        | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| HP            | 304Bh                       | [0a7bcbdd9e](https://linux-hardware.org/?probe=0a7bcbdd9e) | Sep 11, 2022 |
| MSI           | B560M PRO                   | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| MSI           | 0A48                        | [2619140b48](https://linux-hardware.org/?probe=2619140b48) | Sep 10, 2022 |
| Dell          | 01TKCC A01                  | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| ASUSTek       | P8B75-M LX                  | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
| Dell          | 03NVJ6 A00                  | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| ASRock        | G41M-VS3                    | [021bcda428](https://linux-hardware.org/?probe=021bcda428) | Sep 10, 2022 |
| Gigabyte      | Z68AP-D3                    | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| Dell          | 0J3C2F A00                  | [40c43aff10](https://linux-hardware.org/?probe=40c43aff10) | Sep 10, 2022 |
| Apple         | Mac-F221BEC8                | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [cd84312899](https://linux-hardware.org/?probe=cd84312899) | Sep 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [36b349b529](https://linux-hardware.org/?probe=36b349b529) | Sep 09, 2022 |
| Dell          | 0M5DCD A00                  | [1a5c8e32b7](https://linux-hardware.org/?probe=1a5c8e32b7) | Sep 09, 2022 |
| Gigabyte      | A520M DS3H                  | [036c262ad4](https://linux-hardware.org/?probe=036c262ad4) | Sep 08, 2022 |
| ASRock        | Z170 Extreme4               | [70e3d85420](https://linux-hardware.org/?probe=70e3d85420) | Sep 07, 2022 |
| MSI           | IONA                        | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| MSI           | A320M PRO-M2 V2             | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [8a66fbdadd](https://linux-hardware.org/?probe=8a66fbdadd) | Sep 06, 2022 |
| ECS           | GeForce 8000 series         | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [537708f71a](https://linux-hardware.org/?probe=537708f71a) | Sep 06, 2022 |
| MSI           | B350M PRO-VDH               | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| HP            | 8076                        | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| ASRock        | B450 Pro4                   | [4d5b865aed](https://linux-hardware.org/?probe=4d5b865aed) | Sep 05, 2022 |
| Unknown       | Unknown                     | [e2115bf207](https://linux-hardware.org/?probe=e2115bf207) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [b36d7be7c1](https://linux-hardware.org/?probe=b36d7be7c1) | Sep 04, 2022 |
| HP            | 304Bh                       | [d395dd6c91](https://linux-hardware.org/?probe=d395dd6c91) | Sep 04, 2022 |
| Gigabyte      | H97N-WIFI                   | [fb64be85f1](https://linux-hardware.org/?probe=fb64be85f1) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [792cbc3418](https://linux-hardware.org/?probe=792cbc3418) | Sep 04, 2022 |
| HP            | 8767 A                      | [33800541e3](https://linux-hardware.org/?probe=33800541e3) | Sep 04, 2022 |
| Gigabyte      | B560 AORUS PRO AX           | [fbd2e39516](https://linux-hardware.org/?probe=fbd2e39516) | Sep 04, 2022 |
| ECS           | H61H-G11/7.0                | [790b93cbee](https://linux-hardware.org/?probe=790b93cbee) | Sep 03, 2022 |
| Unknown       | Intel X79                   | [9e666e1530](https://linux-hardware.org/?probe=9e666e1530) | Sep 02, 2022 |
| HP            | 8053                        | [2e48f3f13e](https://linux-hardware.org/?probe=2e48f3f13e) | Sep 02, 2022 |
| Dell          | 0TP412                      | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| ASRock        | A320M-DVS R4.0              | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| Foxconn       | 2ABF                        | [c9a801a4d2](https://linux-hardware.org/?probe=c9a801a4d2) | Sep 01, 2022 |
| ASRock        | X99 Taichi                  | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| ASRock        | B550M-ITX/ac                | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| MSI           | H510M-A PRO                 | [120400698e](https://linux-hardware.org/?probe=120400698e) | Aug 31, 2022 |
| Vorke         | V1 Plus                     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI           | Z97 GAMING 7                | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| ASRock        | N68C-S UCC                  | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Gigabyte      | VM900M                      | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| Dell          | 0R230R A00                  | [0ea749e83c](https://linux-hardware.org/?probe=0ea749e83c) | Aug 30, 2022 |
| HP            | 0A60h                       | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [33aaa7baf4](https://linux-hardware.org/?probe=33aaa7baf4) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | [0099ab3432](https://linux-hardware.org/?probe=0099ab3432) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M58p 6234CL2    | [14449a705a](https://linux-hardware.org/?probe=14449a705a) | Aug 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| ASUSTek       | A88XM-A                     | [d8a4e4d954](https://linux-hardware.org/?probe=d8a4e4d954) | Aug 28, 2022 |
| Medion        | B460H6-EM                   | [91371e505d](https://linux-hardware.org/?probe=91371e505d) | Aug 28, 2022 |
| Gigabyte      | GA-MA78LMT-S2               | [a18db0fafd](https://linux-hardware.org/?probe=a18db0fafd) | Aug 27, 2022 |
| ASUSTek       | P8B WS                      | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [f74dc71ad8](https://linux-hardware.org/?probe=f74dc71ad8) | Aug 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [67712f11d9](https://linux-hardware.org/?probe=67712f11d9) | Aug 27, 2022 |
| ASUSTek       | PRIME Z390-A                | [459c7c1eee](https://linux-hardware.org/?probe=459c7c1eee) | Aug 27, 2022 |
| MSI           | G31TM-P21                   | [cf0bc232f5](https://linux-hardware.org/?probe=cf0bc232f5) | Aug 26, 2022 |
| ASRock        | FM2A68M-HD+                 | [22cc477cd2](https://linux-hardware.org/?probe=22cc477cd2) | Aug 26, 2022 |
| MSI           | 760GM-P21                   | [7e45cde899](https://linux-hardware.org/?probe=7e45cde899) | Aug 26, 2022 |
| HP            | 1497                        | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | M5A78L LE                   | [e4a6425675](https://linux-hardware.org/?probe=e4a6425675) | Aug 26, 2022 |
| Dell          | 0RJ290                      | [ca82162ed5](https://linux-hardware.org/?probe=ca82162ed5) | Aug 25, 2022 |
| Acer          | Aspire XC-710 V:1.1         | [0b76e0f97d](https://linux-hardware.org/?probe=0b76e0f97d) | Aug 25, 2022 |
| Foxconn       | H61M/H61M-S                 | [18e7da32e9](https://linux-hardware.org/?probe=18e7da32e9) | Aug 25, 2022 |
| ASRock        | N68C-GS4 FX                 | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| ASUSTek       | PRIME B350M-A               | [1c98247f4c](https://linux-hardware.org/?probe=1c98247f4c) | Aug 25, 2022 |
| OEM           | A320                        | [4dffd629cf](https://linux-hardware.org/?probe=4dffd629cf) | Aug 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d1cae6aca8](https://linux-hardware.org/?probe=d1cae6aca8) | Aug 24, 2022 |
| HP            | 21D0                        | [1bd58d519c](https://linux-hardware.org/?probe=1bd58d519c) | Aug 24, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | [e75751c55b](https://linux-hardware.org/?probe=e75751c55b) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Gigabyte      | F2A68HM-H                   | [c824203d0a](https://linux-hardware.org/?probe=c824203d0a) | Aug 24, 2022 |
| Dell          | 08HPGT A01                  | [744f838dc2](https://linux-hardware.org/?probe=744f838dc2) | Aug 24, 2022 |
| ICP / iEi     | B217 V1.0                   | [9b540ece9f](https://linux-hardware.org/?probe=9b540ece9f) | Aug 23, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [7dae220687](https://linux-hardware.org/?probe=7dae220687) | Aug 23, 2022 |
| Dell          | 0YJPT1 A00                  | [1de0aeba8f](https://linux-hardware.org/?probe=1de0aeba8f) | Aug 22, 2022 |
| ASUSTek       | PRIME Z390-P                | [ca7534d4dc](https://linux-hardware.org/?probe=ca7534d4dc) | Aug 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [fa5f1121d5](https://linux-hardware.org/?probe=fa5f1121d5) | Aug 22, 2022 |
| Intel         | H61                         | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| ASUSTek       | Z87-C                       | [8de83c544f](https://linux-hardware.org/?probe=8de83c544f) | Aug 21, 2022 |
| HP            | 1998                        | [69b6b04268](https://linux-hardware.org/?probe=69b6b04268) | Aug 21, 2022 |
| ASRock        | N68C-S UCC                  | [bb19c0586c](https://linux-hardware.org/?probe=bb19c0586c) | Aug 20, 2022 |
| Gigabyte      | B365M DS3H WIFI             | [142e25352d](https://linux-hardware.org/?probe=142e25352d) | Aug 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | [56a34e0816](https://linux-hardware.org/?probe=56a34e0816) | Aug 20, 2022 |
| ASUSTek       | P5KPL-SE                    | [2925e63a87](https://linux-hardware.org/?probe=2925e63a87) | Aug 20, 2022 |
| AZW           | MII-V                       | [59698f6b33](https://linux-hardware.org/?probe=59698f6b33) | Aug 20, 2022 |
| OEM           | Intel H81                   | [5e354c60d1](https://linux-hardware.org/?probe=5e354c60d1) | Aug 20, 2022 |
| ASUSTek       | P5KPL-VM                    | [803031cd3b](https://linux-hardware.org/?probe=803031cd3b) | Aug 19, 2022 |
| Gigabyte      | B450M S2H                   | [a0a7a845e3](https://linux-hardware.org/?probe=a0a7a845e3) | Aug 18, 2022 |
| Gigabyte      | P43-ES3G                    | [de6e02672c](https://linux-hardware.org/?probe=de6e02672c) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | [859884934f](https://linux-hardware.org/?probe=859884934f) | Aug 17, 2022 |
| Acer          | MRS600M                     | [ec4c10d06e](https://linux-hardware.org/?probe=ec4c10d06e) | Aug 17, 2022 |
| ASUSTek       | PRIME B250-PRO              | [870d7102f5](https://linux-hardware.org/?probe=870d7102f5) | Aug 17, 2022 |
| Gigabyte      | H410M S2 V2                 | [944a99ea66](https://linux-hardware.org/?probe=944a99ea66) | Aug 17, 2022 |
| Gigabyte      | H81M-S2PH                   | [c8f8e78df8](https://linux-hardware.org/?probe=c8f8e78df8) | Aug 17, 2022 |
| Gigabyte      | B460M DS3H                  | [2b97e09efa](https://linux-hardware.org/?probe=2b97e09efa) | Aug 17, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [7b3d6b544c](https://linux-hardware.org/?probe=7b3d6b544c) | Aug 16, 2022 |
| Dell          | 0T656F A01                  | [ec4014a549](https://linux-hardware.org/?probe=ec4014a549) | Aug 16, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [08e3444b3c](https://linux-hardware.org/?probe=08e3444b3c) | Aug 15, 2022 |
| HP            | 2AE2                        | [1fd0bb70dc](https://linux-hardware.org/?probe=1fd0bb70dc) | Aug 15, 2022 |
| Gigabyte      | P43-ES3G                    | [2b0691bddd](https://linux-hardware.org/?probe=2b0691bddd) | Aug 15, 2022 |
| Dell          | 0PC5F7 A03                  | [56ee42afe3](https://linux-hardware.org/?probe=56ee42afe3) | Aug 15, 2022 |
| Dell          | 0NC2VH A01                  | [170b178361](https://linux-hardware.org/?probe=170b178361) | Aug 15, 2022 |
| HP            | 18E7                        | [06374a6240](https://linux-hardware.org/?probe=06374a6240) | Aug 14, 2022 |
| ASRock        | 960GM-VGS3 FX               | [55c4e8059c](https://linux-hardware.org/?probe=55c4e8059c) | Aug 14, 2022 |
| MSI           | X570-A PRO                  | [30146876c6](https://linux-hardware.org/?probe=30146876c6) | Aug 14, 2022 |
| ASRock        | J3455-ITX                   | [4386fccad1](https://linux-hardware.org/?probe=4386fccad1) | Aug 14, 2022 |
| Lenovo        | SHARKBAY NOK                | [ee169e47b3](https://linux-hardware.org/?probe=ee169e47b3) | Aug 13, 2022 |
| Dell          | 08WKV3 A00                  | [4e57c20454](https://linux-hardware.org/?probe=4e57c20454) | Aug 13, 2022 |
| Lenovo        | ThinkCentre XXXX 739527G    | [ca5fe11e2c](https://linux-hardware.org/?probe=ca5fe11e2c) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | [fd41ccab04](https://linux-hardware.org/?probe=fd41ccab04) | Aug 13, 2022 |
| HP            | 1850                        | [33933e3e5d](https://linux-hardware.org/?probe=33933e3e5d) | Aug 12, 2022 |
| ASRock        | H61M-DGS                    | [50b7221c5a](https://linux-hardware.org/?probe=50b7221c5a) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A II            | [bc32ff70b7](https://linux-hardware.org/?probe=bc32ff70b7) | Aug 12, 2022 |
| Gigabyte      | EP35C-DS3R                  | [762d78160d](https://linux-hardware.org/?probe=762d78160d) | Aug 12, 2022 |
| MSI           | A68HM-E33 V2                | [2f3db9cd91](https://linux-hardware.org/?probe=2f3db9cd91) | Aug 12, 2022 |
| ASRock        | Z97M Pro4                   | [245d189a61](https://linux-hardware.org/?probe=245d189a61) | Aug 11, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [73bf30c596](https://linux-hardware.org/?probe=73bf30c596) | Aug 11, 2022 |
| Gigabyte      | P35-DS3L                    | [c765f5b81c](https://linux-hardware.org/?probe=c765f5b81c) | Aug 11, 2022 |
| Foxconn       | 2ABF                        | [3b20387bcc](https://linux-hardware.org/?probe=3b20387bcc) | Aug 10, 2022 |
| ASRock        | H81M-DGS                    | [31bdc504d4](https://linux-hardware.org/?probe=31bdc504d4) | Aug 10, 2022 |
| Dell          | 07KY25 A00                  | [676025f81a](https://linux-hardware.org/?probe=676025f81a) | Aug 10, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | [62d813423e](https://linux-hardware.org/?probe=62d813423e) | Aug 10, 2022 |
| MSI           | X470 GAMING M7 AC           | [58947090d5](https://linux-hardware.org/?probe=58947090d5) | Aug 09, 2022 |
| eMachines     | Veriton V2110               | [3492540d77](https://linux-hardware.org/?probe=3492540d77) | Aug 09, 2022 |
| ASRock        | AB350 Pro4                  | [2df31a9fbf](https://linux-hardware.org/?probe=2df31a9fbf) | Aug 09, 2022 |
| ASUSTek       | Z87-PRO                     | [89a77b442f](https://linux-hardware.org/?probe=89a77b442f) | Aug 09, 2022 |
| Gigabyte      | EP35-DS3P                   | [5c29aee903](https://linux-hardware.org/?probe=5c29aee903) | Aug 08, 2022 |
| ASUSTek       | AT3IONT-I DELUXE            | [642e31466d](https://linux-hardware.org/?probe=642e31466d) | Aug 08, 2022 |
| Dell          | 0782GW A01                  | [b3ebc3aed3](https://linux-hardware.org/?probe=b3ebc3aed3) | Aug 08, 2022 |
| HP            | 304Bh                       | [e1e3f301cb](https://linux-hardware.org/?probe=e1e3f301cb) | Aug 08, 2022 |
| Intel         | H61                         | [eabc8be629](https://linux-hardware.org/?probe=eabc8be629) | Aug 08, 2022 |
| Gigabyte      | H55M-UD2H                   | [4d6a861120](https://linux-hardware.org/?probe=4d6a861120) | Aug 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [95f444c24c](https://linux-hardware.org/?probe=95f444c24c) | Aug 07, 2022 |
| Gigabyte      | EP45-UD3R                   | [6c434341ce](https://linux-hardware.org/?probe=6c434341ce) | Aug 07, 2022 |
| ASUSTek       | M3A78 PRO                   | [0b63e92a55](https://linux-hardware.org/?probe=0b63e92a55) | Aug 07, 2022 |
| HP            | 2215                        | [75304ada6c](https://linux-hardware.org/?probe=75304ada6c) | Aug 06, 2022 |
| Toshiba       | STI 006998G                 | [3de3fa77fc](https://linux-hardware.org/?probe=3de3fa77fc) | Aug 06, 2022 |
| ASRock        | H110M-STX                   | [62b1924710](https://linux-hardware.org/?probe=62b1924710) | Aug 06, 2022 |
| Gigabyte      | A320M-H-CF                  | [4015089c1e](https://linux-hardware.org/?probe=4015089c1e) | Aug 06, 2022 |
| MSI           | 2A9C                        | [8913065613](https://linux-hardware.org/?probe=8913065613) | Aug 06, 2022 |
| Dell          | 0NV0M7 A02                  | [dbf000aacd](https://linux-hardware.org/?probe=dbf000aacd) | Aug 06, 2022 |
| Gigabyte      | A520M S2H                   | [daa1f68f01](https://linux-hardware.org/?probe=daa1f68f01) | Aug 06, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | [a722bef081](https://linux-hardware.org/?probe=a722bef081) | Aug 06, 2022 |
| MSI           | Z87-G43 GAMING              | [490239de9e](https://linux-hardware.org/?probe=490239de9e) | Aug 05, 2022 |
| Dell          | 0GY6Y8 A01                  | [1ad9e54625](https://linux-hardware.org/?probe=1ad9e54625) | Aug 05, 2022 |
| ASUSTek       | M2N68-AM SE2                | [b68c110fde](https://linux-hardware.org/?probe=b68c110fde) | Aug 05, 2022 |
| ASRock        | A300M-STX                   | [f6b820d15f](https://linux-hardware.org/?probe=f6b820d15f) | Aug 05, 2022 |
| ASRock        | H270M-ITX/ac                | [273c214064](https://linux-hardware.org/?probe=273c214064) | Aug 05, 2022 |
| Dell          | 0KG317                      | [65c105e2be](https://linux-hardware.org/?probe=65c105e2be) | Aug 04, 2022 |
| ASUSTek       | A68HM-K                     | [d5d981cf7b](https://linux-hardware.org/?probe=d5d981cf7b) | Aug 04, 2022 |
| ASUSTek       | H110M-K                     | [8c6442a868](https://linux-hardware.org/?probe=8c6442a868) | Aug 04, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [7893ade7cb](https://linux-hardware.org/?probe=7893ade7cb) | Aug 04, 2022 |
| ASUSTek       | PRIME B350M-E               | [f9e07e62c2](https://linux-hardware.org/?probe=f9e07e62c2) | Aug 04, 2022 |
| Unknown       | Unknown                     | [0725792da0](https://linux-hardware.org/?probe=0725792da0) | Aug 04, 2022 |
| Gigabyte      | B360M GAMING HD             | [95e1eb0fcb](https://linux-hardware.org/?probe=95e1eb0fcb) | Aug 03, 2022 |
| Lenovo        | 3102                        | [73e0fee2bc](https://linux-hardware.org/?probe=73e0fee2bc) | Aug 03, 2022 |
| Gigabyte      | Z170X-UD3-CF                | [450fee0496](https://linux-hardware.org/?probe=450fee0496) | Aug 03, 2022 |
| HP            | 2B29                        | [5fcf3a8320](https://linux-hardware.org/?probe=5fcf3a8320) | Aug 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [97dba8f5e3](https://linux-hardware.org/?probe=97dba8f5e3) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [6b790e8a9b](https://linux-hardware.org/?probe=6b790e8a9b) | Aug 02, 2022 |
| Acer          | EM61SM/EM61PM               | [1a35a6d7dc](https://linux-hardware.org/?probe=1a35a6d7dc) | Aug 02, 2022 |
| Foxconn       | 2ABF                        | [4f1fca6662](https://linux-hardware.org/?probe=4f1fca6662) | Aug 02, 2022 |
| ASUSTek       | P8H67                       | [508b0275e3](https://linux-hardware.org/?probe=508b0275e3) | Aug 02, 2022 |
| Gigabyte      | H61M-S2PH                   | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| Gigabyte      | H87-HD3                     | [daaf600950](https://linux-hardware.org/?probe=daaf600950) | Aug 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [b5fded6824](https://linux-hardware.org/?probe=b5fded6824) | Aug 01, 2022 |
| HP            | 339A                        | [251a764917](https://linux-hardware.org/?probe=251a764917) | Aug 01, 2022 |
| ASUSTek       | P7P55D-E PRO                | [d58be7b6d1](https://linux-hardware.org/?probe=d58be7b6d1) | Aug 01, 2022 |
| MSI           | Z590-A PRO                  | [7051f56dda](https://linux-hardware.org/?probe=7051f56dda) | Aug 01, 2022 |
| MSI           | Z77A-GD65                   | [fcadad42a5](https://linux-hardware.org/?probe=fcadad42a5) | Aug 01, 2022 |
| HP            | 843F                        | [eeba83fecb](https://linux-hardware.org/?probe=eeba83fecb) | Aug 01, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [7e6cd7bcb3](https://linux-hardware.org/?probe=7e6cd7bcb3) | Jul 31, 2022 |
| ASUSTek       | P8B75-M LX                  | [653f46c8e3](https://linux-hardware.org/?probe=653f46c8e3) | Jul 31, 2022 |
| ASUSTek       | P5G41C-M LX                 | [4e30dc6361](https://linux-hardware.org/?probe=4e30dc6361) | Jul 31, 2022 |
| MSI           | B85M-P33                    | [6e9af1d1e4](https://linux-hardware.org/?probe=6e9af1d1e4) | Jul 31, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [cb7c9442d6](https://linux-hardware.org/?probe=cb7c9442d6) | Jul 31, 2022 |
| Unknown       | Unknown                     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| ASUSTek       | Z97-A-USB31                 | [25db3983fe](https://linux-hardware.org/?probe=25db3983fe) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [10ece2cb6c](https://linux-hardware.org/?probe=10ece2cb6c) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [edd98c5418](https://linux-hardware.org/?probe=edd98c5418) | Jul 30, 2022 |
| ASRock        | J5040-ITX                   | [2cc4fd5d75](https://linux-hardware.org/?probe=2cc4fd5d75) | Jul 30, 2022 |
| ASUSTek       | M3A78 PRO                   | [c30fca013c](https://linux-hardware.org/?probe=c30fca013c) | Jul 30, 2022 |
| HP            | 2ADC                        | [86608333bc](https://linux-hardware.org/?probe=86608333bc) | Jul 29, 2022 |
| PCWare        | IPMH61R2                    | [b3245af28d](https://linux-hardware.org/?probe=b3245af28d) | Jul 29, 2022 |
| HP            | 0AA0h                       | [5d21c69a99](https://linux-hardware.org/?probe=5d21c69a99) | Jul 29, 2022 |
| HP            | 18E4                        | [d13265fa57](https://linux-hardware.org/?probe=d13265fa57) | Jul 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e1d666e84a](https://linux-hardware.org/?probe=e1d666e84a) | Jul 29, 2022 |
| Dell          | OptiPlex 780                | [7a029315b9](https://linux-hardware.org/?probe=7a029315b9) | Jul 28, 2022 |
| ASRock        | Z97 Anniversary             | [768b11cbe4](https://linux-hardware.org/?probe=768b11cbe4) | Jul 28, 2022 |
| MSI           | G31TM-P35                   | [1bc8def241](https://linux-hardware.org/?probe=1bc8def241) | Jul 28, 2022 |
| MSI           | AM1I                        | [63e6d4040e](https://linux-hardware.org/?probe=63e6d4040e) | Jul 28, 2022 |
| Gigabyte      | B450M H                     | [1357e3b3d3](https://linux-hardware.org/?probe=1357e3b3d3) | Jul 28, 2022 |
| ASUSTek       | H110M-A/M.2                 | [93ad7b0efb](https://linux-hardware.org/?probe=93ad7b0efb) | Jul 28, 2022 |
| ASRock        | B450M Steel Legend          | [db492973ec](https://linux-hardware.org/?probe=db492973ec) | Jul 28, 2022 |
| ASRock        | A320M-HDV                   | [cc72c3c914](https://linux-hardware.org/?probe=cc72c3c914) | Jul 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [24e94dd87e](https://linux-hardware.org/?probe=24e94dd87e) | Jul 28, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [0068653ca3](https://linux-hardware.org/?probe=0068653ca3) | Jul 28, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [d64175b64b](https://linux-hardware.org/?probe=d64175b64b) | Jul 28, 2022 |
| ASRock        | A88M-ITX/ac                 | [e339941033](https://linux-hardware.org/?probe=e339941033) | Jul 27, 2022 |
| Intel         | D54250WYK H13922-303        | [71b03b93a2](https://linux-hardware.org/?probe=71b03b93a2) | Jul 27, 2022 |
| Acer          | Aspire X1930                | [6a650f512e](https://linux-hardware.org/?probe=6a650f512e) | Jul 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [d0ef6d20cf](https://linux-hardware.org/?probe=d0ef6d20cf) | Jul 27, 2022 |
| Foxconn       | A76ML-K 30                  | [7b118c6a6b](https://linux-hardware.org/?probe=7b118c6a6b) | Jul 27, 2022 |
| Dell          | 09KPNV A00                  | [610282a0e6](https://linux-hardware.org/?probe=610282a0e6) | Jul 27, 2022 |
| Dell          | 0YF8P5 A00                  | [04ebe8cd88](https://linux-hardware.org/?probe=04ebe8cd88) | Jul 27, 2022 |
| ASRock        | B450M Pro4                  | [5b4bccdf27](https://linux-hardware.org/?probe=5b4bccdf27) | Jul 27, 2022 |
| HP            | 1495                        | [61a8f473e2](https://linux-hardware.org/?probe=61a8f473e2) | Jul 27, 2022 |
| MSI           | B250M PRO-VDH               | [eb1ff40d2d](https://linux-hardware.org/?probe=eb1ff40d2d) | Jul 27, 2022 |
| ASUSTek       | Z97-P                       | [eeb9068dca](https://linux-hardware.org/?probe=eeb9068dca) | Jul 27, 2022 |
| Gigabyte      | H55M-S2H                    | [a9a6ab85ac](https://linux-hardware.org/?probe=a9a6ab85ac) | Jul 27, 2022 |
| Dell          | 0NW6H5 A00                  | [b76e9e02fa](https://linux-hardware.org/?probe=b76e9e02fa) | Jul 27, 2022 |
| Gigabyte      | H81M-HD3                    | [0cfb15d654](https://linux-hardware.org/?probe=0cfb15d654) | Jul 27, 2022 |
| ASRock        | FM2A88X-ITX+                | [24e0844619](https://linux-hardware.org/?probe=24e0844619) | Jul 27, 2022 |
| Acer          | IPXHW-RL                    | [d99b7cb71e](https://linux-hardware.org/?probe=d99b7cb71e) | Jul 27, 2022 |
| Intel         | DH67VR AAG27177-201         | [3aeca135cd](https://linux-hardware.org/?probe=3aeca135cd) | Jul 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [05947b595a](https://linux-hardware.org/?probe=05947b595a) | Jul 26, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [e487b063ea](https://linux-hardware.org/?probe=e487b063ea) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [17954b8ac5](https://linux-hardware.org/?probe=17954b8ac5) | Jul 26, 2022 |
| Dell          | 0C27VV A03                  | [c1c4edd1e5](https://linux-hardware.org/?probe=c1c4edd1e5) | Jul 26, 2022 |
| Dell          | 042P49 A01                  | [f9003ad850](https://linux-hardware.org/?probe=f9003ad850) | Jul 26, 2022 |
| Login Info... | LOG-H310M-G                 | [f02a0ed6dd](https://linux-hardware.org/?probe=f02a0ed6dd) | Jul 26, 2022 |
| Acer          | Aspire XC-830               | [02572035c8](https://linux-hardware.org/?probe=02572035c8) | Jul 26, 2022 |
| Dell          | 04YP6J A02                  | [8161693c82](https://linux-hardware.org/?probe=8161693c82) | Jul 26, 2022 |
| Pegatron      | 2AE2                        | [772ded1d83](https://linux-hardware.org/?probe=772ded1d83) | Jul 25, 2022 |
| Dell          | 0V8WGR A01                  | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Acer          | EM61SM/EM61PM               | [e470dff38f](https://linux-hardware.org/?probe=e470dff38f) | Jul 25, 2022 |
| Lenovo        | ThinkCentre M58p 6137B28    | [5473e97fa6](https://linux-hardware.org/?probe=5473e97fa6) | Jul 25, 2022 |
| Gigabyte      | H170M-D3H-GSM-CF            | [ace82a6273](https://linux-hardware.org/?probe=ace82a6273) | Jul 25, 2022 |
| Gigabyte      | G31M-S2L                    | [2e1715f154](https://linux-hardware.org/?probe=2e1715f154) | Jul 25, 2022 |
| Wistron       | ProLiant ML110 G5           | [fdb0300292](https://linux-hardware.org/?probe=fdb0300292) | Jul 24, 2022 |
| Dell          | 0VHWTR A01                  | [9796d6eca3](https://linux-hardware.org/?probe=9796d6eca3) | Jul 24, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [7923ed68b5](https://linux-hardware.org/?probe=7923ed68b5) | Jul 24, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [7af6c5cebe](https://linux-hardware.org/?probe=7af6c5cebe) | Jul 24, 2022 |
| ASRock        | AB350 Pro4                  | [7bb0cce634](https://linux-hardware.org/?probe=7bb0cce634) | Jul 24, 2022 |
| MSI           | X470 GAMING PLUS            | [ea3f7e3b48](https://linux-hardware.org/?probe=ea3f7e3b48) | Jul 23, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [dc8bafd932](https://linux-hardware.org/?probe=dc8bafd932) | Jul 23, 2022 |
| ASRock        | A300M-STX                   | [bad4adf823](https://linux-hardware.org/?probe=bad4adf823) | Jul 23, 2022 |
| Gigabyte      | 970A-UD3P                   | [72a44c6eea](https://linux-hardware.org/?probe=72a44c6eea) | Jul 23, 2022 |
| Pegatron      | NARRA5                      | [368503425d](https://linux-hardware.org/?probe=368503425d) | Jul 23, 2022 |
| ASUSTek       | P7H55-M/USB3                | [7e7606e64d](https://linux-hardware.org/?probe=7e7606e64d) | Jul 23, 2022 |
| HP            | 0A68h                       | [cc4b39e6d0](https://linux-hardware.org/?probe=cc4b39e6d0) | Jul 22, 2022 |
| Lenovo        | MAHOBAY NOK                 | [8fc99169c3](https://linux-hardware.org/?probe=8fc99169c3) | Jul 22, 2022 |
| Gigabyte      | B75M-D3H                    | [80dcd8a0f7](https://linux-hardware.org/?probe=80dcd8a0f7) | Jul 22, 2022 |
| Gigabyte      | Z87-HD3                     | [e6bf6ea62f](https://linux-hardware.org/?probe=e6bf6ea62f) | Jul 21, 2022 |
| Gigabyte      | B75M-HD3                    | [321d2817a3](https://linux-hardware.org/?probe=321d2817a3) | Jul 21, 2022 |
| HP            | 1998                        | [82c8302941](https://linux-hardware.org/?probe=82c8302941) | Jul 21, 2022 |
| Lenovo        | 1.0                         | [e520e716cf](https://linux-hardware.org/?probe=e520e716cf) | Jul 21, 2022 |
| ASUSTek       | H110M-R                     | [34942a8abc](https://linux-hardware.org/?probe=34942a8abc) | Jul 20, 2022 |
| ECS           | H61H2-M2                    | [c1d1e739cf](https://linux-hardware.org/?probe=c1d1e739cf) | Jul 20, 2022 |
| Acer          | Veriton M290                | [647393aa0c](https://linux-hardware.org/?probe=647393aa0c) | Jul 20, 2022 |
| PCChips       | A15G                        | [4cdd689308](https://linux-hardware.org/?probe=4cdd689308) | Jul 20, 2022 |
| ASRock        | B450M-HDV                   | [e45f2cd5d8](https://linux-hardware.org/?probe=e45f2cd5d8) | Jul 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [bece300d92](https://linux-hardware.org/?probe=bece300d92) | Jul 20, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [55fdb6713c](https://linux-hardware.org/?probe=55fdb6713c) | Jul 19, 2022 |
| Acer          | Veriton M2110G              | [060e101a26](https://linux-hardware.org/?probe=060e101a26) | Jul 19, 2022 |
| ASUSTek       | H110M-R                     | [8d52662820](https://linux-hardware.org/?probe=8d52662820) | Jul 19, 2022 |
| Gigabyte      | P31-DS3L                    | [3b8118fb89](https://linux-hardware.org/?probe=3b8118fb89) | Jul 19, 2022 |
| Gigabyte      | B365M H                     | [879d413452](https://linux-hardware.org/?probe=879d413452) | Jul 19, 2022 |
| Gigabyte      | Z590 GAMING X               | [4a97996102](https://linux-hardware.org/?probe=4a97996102) | Jul 18, 2022 |
| ASUSTek       | M4A78                       | [d04747e05b](https://linux-hardware.org/?probe=d04747e05b) | Jul 17, 2022 |
| HP            | 8906 SMVB                   | [3b89e3e952](https://linux-hardware.org/?probe=3b89e3e952) | Jul 17, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | [3e2c54f9f1](https://linux-hardware.org/?probe=3e2c54f9f1) | Jul 17, 2022 |
| Foxconn       | 2ABF                        | [2349372af2](https://linux-hardware.org/?probe=2349372af2) | Jul 16, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [478e424482](https://linux-hardware.org/?probe=478e424482) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e6b47dedd7](https://linux-hardware.org/?probe=e6b47dedd7) | Jul 15, 2022 |
| ASUSTek       | P5QLD PRO                   | [fbf3a31304](https://linux-hardware.org/?probe=fbf3a31304) | Jul 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [e5638d3552](https://linux-hardware.org/?probe=e5638d3552) | Jul 15, 2022 |
| Intel         | DQ77MK AAG39642-500         | [7b6a43a9f1](https://linux-hardware.org/?probe=7b6a43a9f1) | Jul 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [775050f5d9](https://linux-hardware.org/?probe=775050f5d9) | Jul 15, 2022 |
| MSI           | H110M PRO-VD PLUS           | [03eaa344c6](https://linux-hardware.org/?probe=03eaa344c6) | Jul 15, 2022 |
| MSI           | G41M-P28                    | [8bd39aa164](https://linux-hardware.org/?probe=8bd39aa164) | Jul 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [20ea8fab3f](https://linux-hardware.org/?probe=20ea8fab3f) | Jul 14, 2022 |
| Gigabyte      | GA-MA770T-UD3               | [eebcfac8a3](https://linux-hardware.org/?probe=eebcfac8a3) | Jul 14, 2022 |
| MSI           | B250M PRO-VH                | [d0a4b76e78](https://linux-hardware.org/?probe=d0a4b76e78) | Jul 13, 2022 |
| HP            | 83E8                        | [a2dc0fc924](https://linux-hardware.org/?probe=a2dc0fc924) | Jul 13, 2022 |
| Foxconn       | 945 7MD Series              | [30585b93f0](https://linux-hardware.org/?probe=30585b93f0) | Jul 13, 2022 |
| Dell          | 048DY8 A01                  | [aad36ba2cd](https://linux-hardware.org/?probe=aad36ba2cd) | Jul 13, 2022 |
| Intel         | DH55TC AAE70932-303         | [0005417882](https://linux-hardware.org/?probe=0005417882) | Jul 13, 2022 |
| Gigabyte      | A320M-H-CF                  | [9b24417251](https://linux-hardware.org/?probe=9b24417251) | Jul 12, 2022 |
| Gigabyte      | H310M S2H x.x               | [8dbe4d55a5](https://linux-hardware.org/?probe=8dbe4d55a5) | Jul 11, 2022 |
| Colorful T... | H310M-T PRO V21             | [b922e2142b](https://linux-hardware.org/?probe=b922e2142b) | Jul 11, 2022 |
| HP            | 339A                        | [a4606d9234](https://linux-hardware.org/?probe=a4606d9234) | Jul 10, 2022 |
| ASRock        | N68C-S UCC                  | [8c5338cc67](https://linux-hardware.org/?probe=8c5338cc67) | Jul 10, 2022 |
| ASRock        | AMCP7A-ION                  | [339f0e7944](https://linux-hardware.org/?probe=339f0e7944) | Jul 10, 2022 |
| Acer          | FMCP7AM                     | [f2fc2e98c3](https://linux-hardware.org/?probe=f2fc2e98c3) | Jul 10, 2022 |
| ASUSTek       | A8N-VM CSM                  | [3cf6a895cd](https://linux-hardware.org/?probe=3cf6a895cd) | Jul 10, 2022 |
| Gigabyte      | GA-A75-UD4H                 | [eba82e4b87](https://linux-hardware.org/?probe=eba82e4b87) | Jul 10, 2022 |
| Gigabyte      | P35-DS3L                    | [67182580cc](https://linux-hardware.org/?probe=67182580cc) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [ee629832da](https://linux-hardware.org/?probe=ee629832da) | Jul 09, 2022 |
| Gigabyte      | 945PL-S3                    | [72ffb35881](https://linux-hardware.org/?probe=72ffb35881) | Jul 09, 2022 |
| ASUSTek       | M5A97 R2.0                  | [03f898f89a](https://linux-hardware.org/?probe=03f898f89a) | Jul 09, 2022 |
| ASRock        | A320M-HDV R4.0              | [a39b9bab73](https://linux-hardware.org/?probe=a39b9bab73) | Jul 09, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [96de3e0656](https://linux-hardware.org/?probe=96de3e0656) | Jul 08, 2022 |
| Dell          | 0R849J A01                  | [3ea68d63c3](https://linux-hardware.org/?probe=3ea68d63c3) | Jul 08, 2022 |
| Gigabyte      | EP45-UD3                    | [195c60abeb](https://linux-hardware.org/?probe=195c60abeb) | Jul 08, 2022 |
| Gigabyte      | 990FXA-UD5                  | [9c7f4deae5](https://linux-hardware.org/?probe=9c7f4deae5) | Jul 08, 2022 |
| ASUSTek       | P5K                         | [31df9a51bc](https://linux-hardware.org/?probe=31df9a51bc) | Jul 08, 2022 |
| Gigabyte      | MBHM87P-00                  | [c02df16b43](https://linux-hardware.org/?probe=c02df16b43) | Jul 08, 2022 |
| ASUSTek       | P5B                         | [0c722e5ec0](https://linux-hardware.org/?probe=0c722e5ec0) | Jul 07, 2022 |
| MSI           | B250M PRO-VH                | [cab2cbb630](https://linux-hardware.org/?probe=cab2cbb630) | Jul 07, 2022 |
| ASUSTek       | ROG Maximus X APEX          | [e1fa4e4923](https://linux-hardware.org/?probe=e1fa4e4923) | Jul 06, 2022 |
| Intel         | X79Turbo V1.x               | [497c3810d8](https://linux-hardware.org/?probe=497c3810d8) | Jul 06, 2022 |
| Intel         | DQ35MP AAD82086-702         | [a0cae9f6a9](https://linux-hardware.org/?probe=a0cae9f6a9) | Jul 06, 2022 |
| Gigabyte      | H410M H V3                  | [0d26f198ff](https://linux-hardware.org/?probe=0d26f198ff) | Jul 06, 2022 |
| MSI           | G41M-P23                    | [8885c18d8c](https://linux-hardware.org/?probe=8885c18d8c) | Jul 06, 2022 |
| HP            | 843C                        | [5f218ccb19](https://linux-hardware.org/?probe=5f218ccb19) | Jul 06, 2022 |
| MSI           | Z97 XPOWER AC               | [b7324cb6ab](https://linux-hardware.org/?probe=b7324cb6ab) | Jul 05, 2022 |
| Biostar       | H310MHC2                    | [9fc3974ab1](https://linux-hardware.org/?probe=9fc3974ab1) | Jul 05, 2022 |
| Gigabyte      | H97M-D3H                    | [46d0a033ca](https://linux-hardware.org/?probe=46d0a033ca) | Jul 05, 2022 |
| ASRock        | H61M-VS                     | [c68e40b7eb](https://linux-hardware.org/?probe=c68e40b7eb) | Jul 05, 2022 |
| Intel         | H61                         | [da6d35599a](https://linux-hardware.org/?probe=da6d35599a) | Jul 04, 2022 |
| Gigabyte      | Z97X-UD5H                   | [8b5f0f789c](https://linux-hardware.org/?probe=8b5f0f789c) | Jul 04, 2022 |
| Dell          | 0Y5DDC A00                  | [e99c8ae46f](https://linux-hardware.org/?probe=e99c8ae46f) | Jul 04, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [440b013dd2](https://linux-hardware.org/?probe=440b013dd2) | Jul 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | [a1ca3ddb17](https://linux-hardware.org/?probe=a1ca3ddb17) | Jul 03, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [98c7e055a3](https://linux-hardware.org/?probe=98c7e055a3) | Jul 03, 2022 |
| ASUSTek       | P5K-VM                      | [ad9d0f9183](https://linux-hardware.org/?probe=ad9d0f9183) | Jul 02, 2022 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [ac6fde7f04](https://linux-hardware.org/?probe=ac6fde7f04) | Jul 02, 2022 |
| HP            | 212B                        | [bd8ef053fd](https://linux-hardware.org/?probe=bd8ef053fd) | Jul 02, 2022 |
| Intel         | DH67BL AAG10189-211         | [ef2f004b52](https://linux-hardware.org/?probe=ef2f004b52) | Jul 02, 2022 |
| ASRock        | Z390 Pro4                   | [25bd784ca6](https://linux-hardware.org/?probe=25bd784ca6) | Jul 02, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [924f16c3d0](https://linux-hardware.org/?probe=924f16c3d0) | Jul 02, 2022 |
| Pegatron      | IPM41-D3                    | [a7cc8d2654](https://linux-hardware.org/?probe=a7cc8d2654) | Jul 01, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [a082da0857](https://linux-hardware.org/?probe=a082da0857) | Jun 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [06ca24d4e1](https://linux-hardware.org/?probe=06ca24d4e1) | Jun 30, 2022 |
| ASUSTek       | P8H77-V LE                  | [0ecaca17cb](https://linux-hardware.org/?probe=0ecaca17cb) | Jun 30, 2022 |
| Gigabyte      | H470 HD3                    | [4857a7b7bf](https://linux-hardware.org/?probe=4857a7b7bf) | Jun 30, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [7a90f7795b](https://linux-hardware.org/?probe=7a90f7795b) | Jun 30, 2022 |
| Biostar       | A68N-5600E                  | [d5cfa78343](https://linux-hardware.org/?probe=d5cfa78343) | Jun 29, 2022 |
| ASUSTek       | PRIME Z270-A                | [da80c0d1cd](https://linux-hardware.org/?probe=da80c0d1cd) | Jun 29, 2022 |
| MSI           | A320M PRO-VD/S V2           | [fc5a5d812c](https://linux-hardware.org/?probe=fc5a5d812c) | Jun 29, 2022 |
| Gigabyte      | EP45-UD3                    | [bb62363ad2](https://linux-hardware.org/?probe=bb62363ad2) | Jun 29, 2022 |
| HP            | 18E9                        | [67a4877415](https://linux-hardware.org/?probe=67a4877415) | Jun 29, 2022 |
| Gigabyte      | X58A-UD3R                   | [c414829bec](https://linux-hardware.org/?probe=c414829bec) | Jun 28, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f2f78497e6](https://linux-hardware.org/?probe=f2f78497e6) | Jun 28, 2022 |
| Intel         | DP43BF AAE78171-302         | [0115160101](https://linux-hardware.org/?probe=0115160101) | Jun 28, 2022 |
| Dell          | 0KRC95 A00                  | [04aacdbccd](https://linux-hardware.org/?probe=04aacdbccd) | Jun 28, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0f4c661912](https://linux-hardware.org/?probe=0f4c661912) | Jun 27, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [371c2586d6](https://linux-hardware.org/?probe=371c2586d6) | Jun 27, 2022 |
| HP            | 3047h                       | [32eb7049a1](https://linux-hardware.org/?probe=32eb7049a1) | Jun 27, 2022 |
| ASRock        | 890GM Pro3 R2.0             | [4b7b86cf21](https://linux-hardware.org/?probe=4b7b86cf21) | Jun 27, 2022 |
| ASRock        | A320M-HDV                   | [ec991b1524](https://linux-hardware.org/?probe=ec991b1524) | Jun 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5fa355f7ec](https://linux-hardware.org/?probe=5fa355f7ec) | Jun 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [1f3399d205](https://linux-hardware.org/?probe=1f3399d205) | Jun 26, 2022 |
| Gigabyte      | GA-880GM-USB3               | [4d48252e22](https://linux-hardware.org/?probe=4d48252e22) | Jun 26, 2022 |
| ASRock        | 990FX Killer                | [1e18ee882c](https://linux-hardware.org/?probe=1e18ee882c) | Jun 26, 2022 |
| MSI           | H81M-P33                    | [d690a68389](https://linux-hardware.org/?probe=d690a68389) | Jun 25, 2022 |
| Gigabyte      | Z690 UD                     | [2c21dadeed](https://linux-hardware.org/?probe=2c21dadeed) | Jun 25, 2022 |
| ASUSTek       | H81M-R 2016-11-08           | [f9ac4d3e81](https://linux-hardware.org/?probe=f9ac4d3e81) | Jun 25, 2022 |
| Foxconn       | 945 7MC Series              | [16836e63f5](https://linux-hardware.org/?probe=16836e63f5) | Jun 25, 2022 |
| MSI           | A78M-E45                    | [ca217e0ccb](https://linux-hardware.org/?probe=ca217e0ccb) | Jun 25, 2022 |
| ASUSTek       | P5GC-MX/1333                | [30692c3fdb](https://linux-hardware.org/?probe=30692c3fdb) | Jun 23, 2022 |
| HP            | 3646h                       | [d27deccf27](https://linux-hardware.org/?probe=d27deccf27) | Jun 22, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [6fd11970ae](https://linux-hardware.org/?probe=6fd11970ae) | Jun 22, 2022 |
| MSI           | Z170A KRAIT GAMING          | [7f2adf56e4](https://linux-hardware.org/?probe=7f2adf56e4) | Jun 21, 2022 |
| Dell          | 0G919G A00                  | [753f0bf2a8](https://linux-hardware.org/?probe=753f0bf2a8) | Jun 21, 2022 |
| ASRock        | M3N78D                      | [8ae000afb6](https://linux-hardware.org/?probe=8ae000afb6) | Jun 21, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [73aff9ca4a](https://linux-hardware.org/?probe=73aff9ca4a) | Jun 21, 2022 |
| Gigabyte      | H410M S2 V3                 | [79ac3d3f38](https://linux-hardware.org/?probe=79ac3d3f38) | Jun 21, 2022 |
| ASUSTek       | M2NPV-VM                    | [818e78cbe0](https://linux-hardware.org/?probe=818e78cbe0) | Jun 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ecc6e0f4ef](https://linux-hardware.org/?probe=ecc6e0f4ef) | Jun 21, 2022 |
| ASUSTek       | P8Z68-V LE                  | [5aa18e7ef9](https://linux-hardware.org/?probe=5aa18e7ef9) | Jun 20, 2022 |
| ASUSTek       | M5A97 PLUS                  | [bef449f943](https://linux-hardware.org/?probe=bef449f943) | Jun 20, 2022 |
| ASUSTek       | P8H61-M LE                  | [f3ceed4c58](https://linux-hardware.org/?probe=f3ceed4c58) | Jun 20, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [a0d16e2b3c](https://linux-hardware.org/?probe=a0d16e2b3c) | Jun 20, 2022 |
| ASUSTek       | G10DK                       | [3882552921](https://linux-hardware.org/?probe=3882552921) | Jun 19, 2022 |
| Intel         | DH77KC AAG39641-401         | [3d2faf0e14](https://linux-hardware.org/?probe=3d2faf0e14) | Jun 19, 2022 |
| HP            | 843B                        | [21619041e8](https://linux-hardware.org/?probe=21619041e8) | Jun 19, 2022 |
| ASRock        | B365M Pro4                  | [1cc64b4898](https://linux-hardware.org/?probe=1cc64b4898) | Jun 19, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [ff71b93299](https://linux-hardware.org/?probe=ff71b93299) | Jun 19, 2022 |
| Acer          | Aspire TC-605               | [7356d9b33a](https://linux-hardware.org/?probe=7356d9b33a) | Jun 18, 2022 |
| ASUSTek       | PRIME A520M-K               | [e41f474842](https://linux-hardware.org/?probe=e41f474842) | Jun 18, 2022 |
| MSI           | 870-G45                     | [f116a1cf99](https://linux-hardware.org/?probe=f116a1cf99) | Jun 18, 2022 |
| Intel         | H61                         | [358da63cbc](https://linux-hardware.org/?probe=358da63cbc) | Jun 18, 2022 |
| ASRock        | FM2A68M-DG3+                | [494419a571](https://linux-hardware.org/?probe=494419a571) | Jun 17, 2022 |
| ASRock        | QC6000M                     | [176afb6dcc](https://linux-hardware.org/?probe=176afb6dcc) | Jun 17, 2022 |
| Gigabyte      | F2A78M-HD2                  | [d6be55432d](https://linux-hardware.org/?probe=d6be55432d) | Jun 16, 2022 |
| ASUSTek       | P7H55                       | [eda50025d7](https://linux-hardware.org/?probe=eda50025d7) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [dab54fda61](https://linux-hardware.org/?probe=dab54fda61) | Jun 16, 2022 |
| ASUSTek       | P8B75-M                     | [9ab6f4690f](https://linux-hardware.org/?probe=9ab6f4690f) | Jun 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [fb36d0a844](https://linux-hardware.org/?probe=fb36d0a844) | Jun 15, 2022 |
| ASUSTek       | PRIME A320M-K               | [67c7179045](https://linux-hardware.org/?probe=67c7179045) | Jun 15, 2022 |
| Gigabyte      | B450M DS3H V2               | [684cf228c4](https://linux-hardware.org/?probe=684cf228c4) | Jun 15, 2022 |
| ASUSTek       | P5QPL-AM                    | [f67a5f860e](https://linux-hardware.org/?probe=f67a5f860e) | Jun 15, 2022 |
| MSI           | Z77A-G43                    | [ead05322dd](https://linux-hardware.org/?probe=ead05322dd) | Jun 15, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [88104c621b](https://linux-hardware.org/?probe=88104c621b) | Jun 15, 2022 |
| ASUSTek       | PRIME A520M-E               | [d381bbec9f](https://linux-hardware.org/?probe=d381bbec9f) | Jun 15, 2022 |
| ASUSTek       | H81T                        | [6687cc21f3](https://linux-hardware.org/?probe=6687cc21f3) | Jun 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | [0ca08532ce](https://linux-hardware.org/?probe=0ca08532ce) | Jun 14, 2022 |
| MSI           | A320M PRO-VH                | [47f765c61f](https://linux-hardware.org/?probe=47f765c61f) | Jun 14, 2022 |
| Packard Be... | MCP73                       | [0542e4233e](https://linux-hardware.org/?probe=0542e4233e) | Jun 14, 2022 |
| Intel         | DH67BL AAG10189-211         | [8bb84d5aaf](https://linux-hardware.org/?probe=8bb84d5aaf) | Jun 14, 2022 |
| Gigabyte      | H510M H                     | [75fd209e13](https://linux-hardware.org/?probe=75fd209e13) | Jun 14, 2022 |
| MSI           | MS-7360                     | [fe6f5deaa0](https://linux-hardware.org/?probe=fe6f5deaa0) | Jun 13, 2022 |
| HP            | 18E7                        | [f2d50ba3c2](https://linux-hardware.org/?probe=f2d50ba3c2) | Jun 13, 2022 |
| Dell          | 09KPNV A00                  | [ed59551343](https://linux-hardware.org/?probe=ed59551343) | Jun 13, 2022 |
| langchao      | IPM41-D3                    | [bb1a55c140](https://linux-hardware.org/?probe=bb1a55c140) | Jun 13, 2022 |
| Gigabyte      | GA-MA78LMT-S2               | [be77f2ffd4](https://linux-hardware.org/?probe=be77f2ffd4) | Jun 12, 2022 |
| Gigabyte      | P55A-UD3                    | [66062b5350](https://linux-hardware.org/?probe=66062b5350) | Jun 12, 2022 |
| MSI           | MS-7360                     | [df15dd80d4](https://linux-hardware.org/?probe=df15dd80d4) | Jun 12, 2022 |
| MSI           | H55M-E33                    | [1fa7005827](https://linux-hardware.org/?probe=1fa7005827) | Jun 12, 2022 |
| Gigabyte      | 990FXA-UD3                  | [df35df715a](https://linux-hardware.org/?probe=df35df715a) | Jun 12, 2022 |
| Gigabyte      | F2A88XN-WIFI                | [4a67ad74b7](https://linux-hardware.org/?probe=4a67ad74b7) | Jun 12, 2022 |
| ASUSTek       | H110I-PLUS                  | [36389b33b6](https://linux-hardware.org/?probe=36389b33b6) | Jun 12, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [4e830e41ec](https://linux-hardware.org/?probe=4e830e41ec) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [b0e6137115](https://linux-hardware.org/?probe=b0e6137115) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [576fc8e8ed](https://linux-hardware.org/?probe=576fc8e8ed) | Jun 11, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [6818c8dc03](https://linux-hardware.org/?probe=6818c8dc03) | Jun 11, 2022 |
| ASUSTek       | PRIME X470-PRO              | [712464602f](https://linux-hardware.org/?probe=712464602f) | Jun 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [839663a1af](https://linux-hardware.org/?probe=839663a1af) | Jun 10, 2022 |
| Acer          | Aspire M3970                | [66016e2c0d](https://linux-hardware.org/?probe=66016e2c0d) | Jun 10, 2022 |
| ASUSTek       | M5A97 PLUS                  | [668b715efd](https://linux-hardware.org/?probe=668b715efd) | Jun 10, 2022 |
| Unknown       | SKYBAY                      | [ca3c55b50a](https://linux-hardware.org/?probe=ca3c55b50a) | Jun 10, 2022 |
| Acer          | TPDS05 R3700                | [0203dde7bd](https://linux-hardware.org/?probe=0203dde7bd) | Jun 09, 2022 |
| Lenovo        | ThinkCentre M58p 9965A5G    | [35ee376f8a](https://linux-hardware.org/?probe=35ee376f8a) | Jun 09, 2022 |
| MSI           | NF980-G65                   | [81348124ff](https://linux-hardware.org/?probe=81348124ff) | Jun 09, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [f498a9e83f](https://linux-hardware.org/?probe=f498a9e83f) | Jun 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a307c95089](https://linux-hardware.org/?probe=a307c95089) | Jun 08, 2022 |
| ASRock        | N68C-S UCC                  | [ca2987cf23](https://linux-hardware.org/?probe=ca2987cf23) | Jun 08, 2022 |
| Foxconn       | H55MXV-LE                   | [b1c70f54f5](https://linux-hardware.org/?probe=b1c70f54f5) | Jun 08, 2022 |
| Intel         | DG33FB AAD81072-306         | [78abe45a29](https://linux-hardware.org/?probe=78abe45a29) | Jun 08, 2022 |
| Foxconn       | 2ADA                        | [469b57fa93](https://linux-hardware.org/?probe=469b57fa93) | Jun 08, 2022 |
| Medion        | H110H4-CM2                  | [6c7f5da497](https://linux-hardware.org/?probe=6c7f5da497) | Jun 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [ffceb89203](https://linux-hardware.org/?probe=ffceb89203) | Jun 07, 2022 |
| HP            | 843F                        | [59bbcdff88](https://linux-hardware.org/?probe=59bbcdff88) | Jun 07, 2022 |
| Dell          | 088DT1 A00                  | [b585cb1f70](https://linux-hardware.org/?probe=b585cb1f70) | Jun 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [74c4c38cae](https://linux-hardware.org/?probe=74c4c38cae) | Jun 07, 2022 |
| Lenovo        | 3140 NOK                    | [03619a223f](https://linux-hardware.org/?probe=03619a223f) | Jun 07, 2022 |
| Shuttle       | FL10J                       | [8c27549c9e](https://linux-hardware.org/?probe=8c27549c9e) | Jun 07, 2022 |
| Gigabyte      | G41MT-S2                    | [f1c3ae3db4](https://linux-hardware.org/?probe=f1c3ae3db4) | Jun 06, 2022 |
| ASUSTek       | PRIME A320M-K               | [ba86261552](https://linux-hardware.org/?probe=ba86261552) | Jun 06, 2022 |
| MSI           | A55M-P33                    | [7b11750186](https://linux-hardware.org/?probe=7b11750186) | Jun 06, 2022 |
| ASRock        | A520M-HDV                   | [a8ade4e46f](https://linux-hardware.org/?probe=a8ade4e46f) | Jun 06, 2022 |
| OEM           | H110                        | [d9bb28c841](https://linux-hardware.org/?probe=d9bb28c841) | Jun 05, 2022 |
| HP            | 8648                        | [155bf69660](https://linux-hardware.org/?probe=155bf69660) | Jun 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [1504d60bf5](https://linux-hardware.org/?probe=1504d60bf5) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [aca6d1da03](https://linux-hardware.org/?probe=aca6d1da03) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [c0eb59d595](https://linux-hardware.org/?probe=c0eb59d595) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [80832b1c72](https://linux-hardware.org/?probe=80832b1c72) | Jun 05, 2022 |
| Dell          | 0GY6Y8 A03                  | [4668e3772e](https://linux-hardware.org/?probe=4668e3772e) | Jun 05, 2022 |
| ASRock        | 880GM-LE FX                 | [cd7a02b187](https://linux-hardware.org/?probe=cd7a02b187) | Jun 05, 2022 |
| Acer          | Veriton N4670G              | [0b85f95c4c](https://linux-hardware.org/?probe=0b85f95c4c) | Jun 05, 2022 |
| ASRock        | Z97 Anniversary             | [b6a332c085](https://linux-hardware.org/?probe=b6a332c085) | Jun 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [4d3213676b](https://linux-hardware.org/?probe=4d3213676b) | Jun 04, 2022 |
| Gigabyte      | H110M-S2H-CF                | [7ccdf657a0](https://linux-hardware.org/?probe=7ccdf657a0) | Jun 04, 2022 |
| Gigabyte      | F2A88X-D3H                  | [5b7b255faf](https://linux-hardware.org/?probe=5b7b255faf) | Jun 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8ac5eb21ad](https://linux-hardware.org/?probe=8ac5eb21ad) | Jun 04, 2022 |
| ASUSTek       | P5B-VM                      | [0ee6de9e23](https://linux-hardware.org/?probe=0ee6de9e23) | Jun 03, 2022 |
| ASUSTek       | Z170-A                      | [ed86450031](https://linux-hardware.org/?probe=ed86450031) | Jun 03, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [f011e99578](https://linux-hardware.org/?probe=f011e99578) | Jun 03, 2022 |
| HP            | 1998                        | [e1bd6ae3e1](https://linux-hardware.org/?probe=e1bd6ae3e1) | Jun 03, 2022 |
| ASRock        | Q1900B-ITX                  | [cec9d6d159](https://linux-hardware.org/?probe=cec9d6d159) | Jun 03, 2022 |
| Dell          | 040DDP A01                  | [208a2ee137](https://linux-hardware.org/?probe=208a2ee137) | Jun 02, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [eca3bd70a8](https://linux-hardware.org/?probe=eca3bd70a8) | Jun 02, 2022 |
| Dell          | 0GDG8Y A00                  | [ae659a73f9](https://linux-hardware.org/?probe=ae659a73f9) | Jun 02, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | [536c6e19de](https://linux-hardware.org/?probe=536c6e19de) | Jun 01, 2022 |
| Dell          | 00V62H A00                  | [7622f595c6](https://linux-hardware.org/?probe=7622f595c6) | Jun 01, 2022 |
| HP            | 8054                        | [7d7b7577db](https://linux-hardware.org/?probe=7d7b7577db) | Jun 01, 2022 |
| Intel         | D2700DC AAG32420-602        | [a55bb5f425](https://linux-hardware.org/?probe=a55bb5f425) | Jun 01, 2022 |
| Dell          | 0J3C2F A02                  | [9ff329a1fd](https://linux-hardware.org/?probe=9ff329a1fd) | May 31, 2022 |
| Lenovo        | ThinkCentre M57 00P4496     | [07ba75838a](https://linux-hardware.org/?probe=07ba75838a) | May 31, 2022 |
| HP            | 3047h                       | [59affe5430](https://linux-hardware.org/?probe=59affe5430) | May 31, 2022 |
| Lenovo        | 3148 SDK0K13476 WIN 3306... | [5723328e24](https://linux-hardware.org/?probe=5723328e24) | May 31, 2022 |
| Gigabyte      | X570 AORUS PRO              | [c39f904361](https://linux-hardware.org/?probe=c39f904361) | May 30, 2022 |
| ASUSTek       | Maximus II Formula          | [84df720c51](https://linux-hardware.org/?probe=84df720c51) | May 30, 2022 |
| ASRock        | A88M-G                      | [9b82b09acc](https://linux-hardware.org/?probe=9b82b09acc) | May 30, 2022 |
| Lenovo        | ThinkCentre M90p 5536WAZ    | [c6c32dc36b](https://linux-hardware.org/?probe=c6c32dc36b) | May 30, 2022 |
| Intel         | DG43GT AAE62768-300         | [643ebac3b3](https://linux-hardware.org/?probe=643ebac3b3) | May 29, 2022 |
| Fujitsu Si... | D2464-A1 S26361-D2464-A1    | [2f5bdf6497](https://linux-hardware.org/?probe=2f5bdf6497) | May 29, 2022 |
| ASRock        | B85M-HDS                    | [54a1e6b445](https://linux-hardware.org/?probe=54a1e6b445) | May 29, 2022 |
| Gigabyte      | A320M-H-CF                  | [522da9476b](https://linux-hardware.org/?probe=522da9476b) | May 29, 2022 |
| Gigabyte      | GA-MA770-UD3                | [d1c4685112](https://linux-hardware.org/?probe=d1c4685112) | May 29, 2022 |
| MSI           | Z590-A PRO                  | [55a37b3d9c](https://linux-hardware.org/?probe=55a37b3d9c) | May 29, 2022 |
| ASUSTek       | AM1M-A/BR                   | [c8532fbb66](https://linux-hardware.org/?probe=c8532fbb66) | May 29, 2022 |
| HP            | 81C3                        | [7a57cdec90](https://linux-hardware.org/?probe=7a57cdec90) | May 28, 2022 |
| Gigabyte      | B560M H                     | [7e17227514](https://linux-hardware.org/?probe=7e17227514) | May 27, 2022 |
| MSI           | 785G-E53                    | [18ee1d0980](https://linux-hardware.org/?probe=18ee1d0980) | May 27, 2022 |
| Positivo      | POS-PIQ57BQA                | [f33ecab5de](https://linux-hardware.org/?probe=f33ecab5de) | May 27, 2022 |
| ASRock        | H270M-ITX/ac                | [e77300d74a](https://linux-hardware.org/?probe=e77300d74a) | May 27, 2022 |
| MSI           | Boston                      | [7e3c443fb1](https://linux-hardware.org/?probe=7e3c443fb1) | May 27, 2022 |
| BESSTAR Te... | UM350                       | [e4082f489e](https://linux-hardware.org/?probe=e4082f489e) | May 27, 2022 |
| HP            | 212B                        | [14db1a01c5](https://linux-hardware.org/?probe=14db1a01c5) | May 26, 2022 |
| Intel         | DP67BA AAG10219-300         | [005b9cdb8e](https://linux-hardware.org/?probe=005b9cdb8e) | May 26, 2022 |
| Gigabyte      | 990XA-UD3                   | [6cc0861cc3](https://linux-hardware.org/?probe=6cc0861cc3) | May 26, 2022 |
| Positivo      | POS-PIQ57BQA                | [2175bbae83](https://linux-hardware.org/?probe=2175bbae83) | May 26, 2022 |
| ASRock        | ALiveNF6G-GLAN              | [ae17b83ca5](https://linux-hardware.org/?probe=ae17b83ca5) | May 26, 2022 |
| Gigabyte      | B85M-D3H-A                  | [36e5918bc8](https://linux-hardware.org/?probe=36e5918bc8) | May 25, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [93d4bd3b14](https://linux-hardware.org/?probe=93d4bd3b14) | May 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [7260e3bf3b](https://linux-hardware.org/?probe=7260e3bf3b) | May 24, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [b3958742aa](https://linux-hardware.org/?probe=b3958742aa) | May 24, 2022 |
| ASUSTek       | B150M-A/M.2                 | [3aea6596c6](https://linux-hardware.org/?probe=3aea6596c6) | May 23, 2022 |
| Intel         | DH55HC AAE70933-505         | [6c27613f85](https://linux-hardware.org/?probe=6c27613f85) | May 23, 2022 |
| HP            | 1495                        | [68ead7bd6a](https://linux-hardware.org/?probe=68ead7bd6a) | May 23, 2022 |
| MSI           | B450I GAMING PLUS AC        | [dbc555961b](https://linux-hardware.org/?probe=dbc555961b) | May 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | [ee4d26d407](https://linux-hardware.org/?probe=ee4d26d407) | May 23, 2022 |
| Unknown       | P4M800Pro-8237              | [31c80b1ea7](https://linux-hardware.org/?probe=31c80b1ea7) | May 23, 2022 |
| Foxconn       | 2A8C                        | [eda69f1faf](https://linux-hardware.org/?probe=eda69f1faf) | May 22, 2022 |
| Lenovo        | SDK0E50510 WIN              | [6efef2bd1e](https://linux-hardware.org/?probe=6efef2bd1e) | May 22, 2022 |
| MSI           | MS-7235                     | [cb9b6ded76](https://linux-hardware.org/?probe=cb9b6ded76) | May 22, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [da237b1570](https://linux-hardware.org/?probe=da237b1570) | May 21, 2022 |
| MSI           | B350M PRO-VD PLUS           | [6098005a1a](https://linux-hardware.org/?probe=6098005a1a) | May 21, 2022 |
| MSI           | MS-7235                     | [4dfaad64fd](https://linux-hardware.org/?probe=4dfaad64fd) | May 21, 2022 |
| Gigabyte      | Z77P-D3                     | [fc0a2b2595](https://linux-hardware.org/?probe=fc0a2b2595) | May 21, 2022 |
| MSI           | 970 GAMING                  | [082a1ac531](https://linux-hardware.org/?probe=082a1ac531) | May 21, 2022 |
| MSI           | MS-7309                     | [9093ca0773](https://linux-hardware.org/?probe=9093ca0773) | May 20, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [886a958a28](https://linux-hardware.org/?probe=886a958a28) | May 20, 2022 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [ccf347729e](https://linux-hardware.org/?probe=ccf347729e) | May 19, 2022 |
| Gigabyte      | A520M S2H                   | [74a45b7cec](https://linux-hardware.org/?probe=74a45b7cec) | May 19, 2022 |
| ASRock        | A88M-G                      | [e2baae7114](https://linux-hardware.org/?probe=e2baae7114) | May 19, 2022 |
| Lenovo        | ThinkCentre M57 9181A28     | [51ec46a243](https://linux-hardware.org/?probe=51ec46a243) | May 19, 2022 |
| Dell          | 05842Y A00                  | [7c67079823](https://linux-hardware.org/?probe=7c67079823) | May 19, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [95ac26b654](https://linux-hardware.org/?probe=95ac26b654) | May 19, 2022 |
| MSI           | B450-A PRO MAX              | [7b1a855704](https://linux-hardware.org/?probe=7b1a855704) | May 19, 2022 |
| Biostar       | A68N-5600E                  | [025e31f0d1](https://linux-hardware.org/?probe=025e31f0d1) | May 19, 2022 |
| EVGA          | 151-IB-E699                 | [7df0c6167d](https://linux-hardware.org/?probe=7df0c6167d) | May 18, 2022 |
| Gigabyte      | H55M-S2                     | [4d68acc78c](https://linux-hardware.org/?probe=4d68acc78c) | May 18, 2022 |
| MSI           | Z97-G45 GAMING              | [1b02844b0b](https://linux-hardware.org/?probe=1b02844b0b) | May 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [91638ab9be](https://linux-hardware.org/?probe=91638ab9be) | May 17, 2022 |
| Gigabyte      | B75N                        | [b3e561590b](https://linux-hardware.org/?probe=b3e561590b) | May 17, 2022 |
| ASUSTek       | P5QL PRO                    | [60e61a51df](https://linux-hardware.org/?probe=60e61a51df) | May 17, 2022 |
| ASUSTek       | P5Q                         | [614f6cf0c6](https://linux-hardware.org/?probe=614f6cf0c6) | May 16, 2022 |
| ASUSTek       | H110T                       | [e1d711b496](https://linux-hardware.org/?probe=e1d711b496) | May 16, 2022 |
| HP            | 8056                        | [e9d15128a7](https://linux-hardware.org/?probe=e9d15128a7) | May 16, 2022 |
| Dell          | 0Y2MRG A00                  | [1cf635a476](https://linux-hardware.org/?probe=1cf635a476) | May 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [39824d4e4d](https://linux-hardware.org/?probe=39824d4e4d) | May 15, 2022 |
| ASUSTek       | M4N68T-M-V2                 | [528659dab4](https://linux-hardware.org/?probe=528659dab4) | May 15, 2022 |
| ASUSTek       | B85M-G                      | [dd305c13de](https://linux-hardware.org/?probe=dd305c13de) | May 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [52c0b4a6e0](https://linux-hardware.org/?probe=52c0b4a6e0) | May 14, 2022 |
| ASUSTek       | M2A-VM                      | [7708e385fb](https://linux-hardware.org/?probe=7708e385fb) | May 14, 2022 |
| ASUSTek       | H110M-K                     | [d0f043ff65](https://linux-hardware.org/?probe=d0f043ff65) | May 14, 2022 |
| Dell          | 0FM586                      | [82aefc332b](https://linux-hardware.org/?probe=82aefc332b) | May 14, 2022 |
| Gigabyte      | P55-UD3R                    | [638e77ebd8](https://linux-hardware.org/?probe=638e77ebd8) | May 13, 2022 |
| ASUSTek       | B85M-G                      | [6dee77b5ca](https://linux-hardware.org/?probe=6dee77b5ca) | May 13, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [434d2b0bec](https://linux-hardware.org/?probe=434d2b0bec) | May 13, 2022 |
| Lenovo        | ThinkCentre M58 7360WQK     | [9002375046](https://linux-hardware.org/?probe=9002375046) | May 13, 2022 |
| ASUSTek       | NARRA3                      | [ca524c9e95](https://linux-hardware.org/?probe=ca524c9e95) | May 13, 2022 |
| ASRock        | H61M-HP4                    | [f0bda638ba](https://linux-hardware.org/?probe=f0bda638ba) | May 13, 2022 |
| ASUSTek       | H110M-R                     | [adbb3eb389](https://linux-hardware.org/?probe=adbb3eb389) | May 12, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | [a83103153b](https://linux-hardware.org/?probe=a83103153b) | May 12, 2022 |
| Biostar       | G31M+                       | [7440220607](https://linux-hardware.org/?probe=7440220607) | May 12, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [3494019436](https://linux-hardware.org/?probe=3494019436) | May 11, 2022 |
| HP            | 0AA8h                       | [7d29587a1a](https://linux-hardware.org/?probe=7d29587a1a) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | [96f6c5bf2a](https://linux-hardware.org/?probe=96f6c5bf2a) | May 10, 2022 |
| MSI           | 760GM-P34                   | [85bea22dfe](https://linux-hardware.org/?probe=85bea22dfe) | May 09, 2022 |
| HP            | 1998                        | [b717b34f5b](https://linux-hardware.org/?probe=b717b34f5b) | May 08, 2022 |
| Positivo      | POS-PIG41BA                 | [40a9a00430](https://linux-hardware.org/?probe=40a9a00430) | May 08, 2022 |
| ASUSTek       | PRIME B365M-A               | [a281b3c075](https://linux-hardware.org/?probe=a281b3c075) | May 07, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [d7c94f5e83](https://linux-hardware.org/?probe=d7c94f5e83) | May 07, 2022 |
| HP            | 802F                        | [5afe279c1b](https://linux-hardware.org/?probe=5afe279c1b) | May 07, 2022 |
| Lenovo        | SDK0E50510 WIN 262504835... | [5565a2f131](https://linux-hardware.org/?probe=5565a2f131) | May 07, 2022 |
| Positivo      | POS-PIH81DI                 | [f7b64e05f8](https://linux-hardware.org/?probe=f7b64e05f8) | May 06, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [76e6cc98aa](https://linux-hardware.org/?probe=76e6cc98aa) | May 05, 2022 |
| ASUSTek       | A68HM-PLUS                  | [149d1c8c87](https://linux-hardware.org/?probe=149d1c8c87) | May 05, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [8f15e66f2d](https://linux-hardware.org/?probe=8f15e66f2d) | May 05, 2022 |
| ASRock        | QC5000-ITX/WiFi             | [ec48bca283](https://linux-hardware.org/?probe=ec48bca283) | May 05, 2022 |
| Gigabyte      | B150N-GSM-CF                | [b49d3deec3](https://linux-hardware.org/?probe=b49d3deec3) | May 05, 2022 |
| HP            | 18E7                        | [57194bb53c](https://linux-hardware.org/?probe=57194bb53c) | May 04, 2022 |
| HP            | 1998                        | [b35fc936e5](https://linux-hardware.org/?probe=b35fc936e5) | May 04, 2022 |
| MSI           | B360M PRO-VDH               | [23b80ec93e](https://linux-hardware.org/?probe=23b80ec93e) | May 04, 2022 |
| Dell          | 03NVJ6 A04                  | [ebacf887d7](https://linux-hardware.org/?probe=ebacf887d7) | May 04, 2022 |
| Lenovo        | 3102 NOK                    | [8ef837bdb4](https://linux-hardware.org/?probe=8ef837bdb4) | May 04, 2022 |
| HP            | 2B47                        | [e7433db9d1](https://linux-hardware.org/?probe=e7433db9d1) | May 03, 2022 |
| ASUSTek       | PRIME X370-A                | [4d1f9886c2](https://linux-hardware.org/?probe=4d1f9886c2) | May 03, 2022 |
| Acer          | H57M01                      | [180132b3e1](https://linux-hardware.org/?probe=180132b3e1) | May 03, 2022 |
| Dell          | 0M9KCM A01                  | [76d9159d32](https://linux-hardware.org/?probe=76d9159d32) | May 03, 2022 |
| Acer          | Aspire XC-230               | [b80fa8b04f](https://linux-hardware.org/?probe=b80fa8b04f) | May 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [d874b5668c](https://linux-hardware.org/?probe=d874b5668c) | May 02, 2022 |
| Positivo      | POS-EIBTPDC                 | [a9a49f094d](https://linux-hardware.org/?probe=a9a49f094d) | May 01, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [5498c8b84f](https://linux-hardware.org/?probe=5498c8b84f) | May 01, 2022 |
| MSI           | MS-7267                     | [12ef52bd6d](https://linux-hardware.org/?probe=12ef52bd6d) | May 01, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [18daf9705b](https://linux-hardware.org/?probe=18daf9705b) | Apr 30, 2022 |
| MSI           | A320M-A PRO MAX             | [dc1c0d091e](https://linux-hardware.org/?probe=dc1c0d091e) | Apr 30, 2022 |
| ASRock        | 880GM-LE FX                 | [f695420d7e](https://linux-hardware.org/?probe=f695420d7e) | Apr 30, 2022 |
| ASUSTek       | P5QL                        | [121da21f08](https://linux-hardware.org/?probe=121da21f08) | Apr 30, 2022 |
| Gigabyte      | M68MT-S2                    | [f3b89e43d4](https://linux-hardware.org/?probe=f3b89e43d4) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [e8fee79ec7](https://linux-hardware.org/?probe=e8fee79ec7) | Apr 30, 2022 |
| Lenovo        | ThinkCentre M58 7627AD5     | [05a686b922](https://linux-hardware.org/?probe=05a686b922) | Apr 30, 2022 |
| ASUSTek       | P5KPL-AM                    | [7c398e1d2b](https://linux-hardware.org/?probe=7c398e1d2b) | Apr 30, 2022 |
| HP            | 1497                        | [559a844943](https://linux-hardware.org/?probe=559a844943) | Apr 30, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [13fd8e249d](https://linux-hardware.org/?probe=13fd8e249d) | Apr 30, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [3b9e57fc42](https://linux-hardware.org/?probe=3b9e57fc42) | Apr 30, 2022 |
| ASRock        | ALiveNF6G-GLAN              | [7dfb4ca9f5](https://linux-hardware.org/?probe=7dfb4ca9f5) | Apr 29, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [af2b0de49b](https://linux-hardware.org/?probe=af2b0de49b) | Apr 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7e84138ea1](https://linux-hardware.org/?probe=7e84138ea1) | Apr 29, 2022 |
| Intel         | X79 V2.72B                  | [396faf60b6](https://linux-hardware.org/?probe=396faf60b6) | Apr 29, 2022 |
| Foxconn       | 2A8C                        | [eb747a3063](https://linux-hardware.org/?probe=eb747a3063) | Apr 29, 2022 |
| ASUSTek       | B150M-A                     | [fa213f6681](https://linux-hardware.org/?probe=fa213f6681) | Apr 28, 2022 |
| ECS           | H61H2-CM                    | [00620504c7](https://linux-hardware.org/?probe=00620504c7) | Apr 27, 2022 |
| Dell          | 0YJHYD A00                  | [6111a9976e](https://linux-hardware.org/?probe=6111a9976e) | Apr 27, 2022 |
| ASUSTek       | M51BC                       | [f997f2d1c1](https://linux-hardware.org/?probe=f997f2d1c1) | Apr 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [b15f34dd41](https://linux-hardware.org/?probe=b15f34dd41) | Apr 27, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [d354934f98](https://linux-hardware.org/?probe=d354934f98) | Apr 27, 2022 |
| Foxconn       | H61MXE                      | [d8168e72e7](https://linux-hardware.org/?probe=d8168e72e7) | Apr 27, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | [4db68ede02](https://linux-hardware.org/?probe=4db68ede02) | Apr 27, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [00728feb75](https://linux-hardware.org/?probe=00728feb75) | Apr 26, 2022 |
| Gigabyte      | B85M-D2V                    | [ca876d7b83](https://linux-hardware.org/?probe=ca876d7b83) | Apr 26, 2022 |
| Acer          | Aspire TC-780               | [501877dba5](https://linux-hardware.org/?probe=501877dba5) | Apr 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [f4f8108d1e](https://linux-hardware.org/?probe=f4f8108d1e) | Apr 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.3/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003       | 1859     | 96.52%  |
| 5.16.13-desktop-1omv4003      | 58       | 3.01%   |
| 5.17.1-desktop-2omv4050       | 2        | 0.1%    |
| 5.16.5-desktop-2omv4003       | 2        | 0.1%    |
| 5.16.3-desktop-2omv4050       | 2        | 0.1%    |
| 5.17.7-desktop-1omv4090       | 1        | 0.05%   |
| 5.16.7-desktop-clang-1omv4003 | 1        | 0.05%   |
| 5.10.14-desktop-1omv4002      | 1        | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16.7  | 1860     | 96.57%  |
| 5.16.13 | 58       | 3.01%   |
| 5.17.1  | 2        | 0.1%    |
| 5.16.5  | 2        | 0.1%    |
| 5.16.3  | 2        | 0.1%    |
| 5.17.7  | 1        | 0.05%   |
| 5.10.14 | 1        | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16    | 1920     | 99.79%  |
| 5.17    | 3        | 0.16%   |
| 5.10    | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1924     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 1919     | 99.74%  |
| Unknown | 3        | 0.16%   |
| LXQt    | 2        | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1903     | 98.91%  |
| Wayland | 21       | 1.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SDDM | 1924     | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 1073     | 55.74%  |
| de_DE | 177      | 9.19%   |
| ru_RU | 130      | 6.75%   |
| fr_FR | 82       | 4.26%   |
| pt_BR | 81       | 4.21%   |
| pl_PL | 52       | 2.7%    |
| it_IT | 43       | 2.23%   |
| es_ES | 37       | 1.92%   |
| en_GB | 32       | 1.66%   |
| es_AR | 28       | 1.45%   |
| de_AT | 18       | 0.94%   |
| cs_CZ | 18       | 0.94%   |
| en_IN | 16       | 0.83%   |
| es_MX | 14       | 0.73%   |
| hu_HU | 10       | 0.52%   |
| en_CA | 10       | 0.52%   |
| tr_TR | 9        | 0.47%   |
| en_AU | 9        | 0.47%   |
| fr_CA | 8        | 0.42%   |
| ru_UA | 6        | 0.31%   |
| es_CO | 6        | 0.31%   |
| de_CH | 6        | 0.31%   |
| pt_PT | 5        | 0.26%   |
| nl_NL | 5        | 0.26%   |
| es_VE | 5        | 0.26%   |
| es_PE | 4        | 0.21%   |
| es_CL | 4        | 0.21%   |
| da_DK | 4        | 0.21%   |
| nb_NO | 3        | 0.16%   |
| fr_BE | 3        | 0.16%   |
| es_CR | 3        | 0.16%   |
| uk_UA | 2        | 0.1%    |
| es_UY | 2        | 0.1%    |
| es_SV | 2        | 0.1%    |
| en_ZA | 2        | 0.1%    |
| en_IL | 2        | 0.1%    |
| en_HK | 2        | 0.1%    |
| ar_SA | 2        | 0.1%    |
| ro_RO | 1        | 0.05%   |
| nl_BE | 1        | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1057     | 54.94%  |
| EFI  | 867      | 45.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Overlay  | 1659     | 86.14%  |
| Ext4     | 260      | 13.5%   |
| Xfs      | 2        | 0.1%    |
| F2fs     | 2        | 0.1%    |
| Reiserfs | 1        | 0.05%   |
| Ext3     | 1        | 0.05%   |
| Btrfs    | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1184     | 61.51%  |
| MBR     | 724      | 37.61%  |
| Unknown | 17       | 0.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1192     | 61.95%  |
| No        | 732      | 38.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1083     | 56.29%  |
| No        | 841      | 43.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 436      | 22.66%  |
| Gigabyte Technology | 362      | 18.81%  |
| MSI                 | 210      | 10.91%  |
| ASRock              | 173      | 8.99%   |
| Hewlett-Packard     | 154      | 8%      |
| Dell                | 153      | 7.95%   |
| Lenovo              | 82       | 4.26%   |
| Intel               | 60       | 3.12%   |
| Acer                | 52       | 2.7%    |
| Fujitsu             | 27       | 1.4%    |
| Foxconn             | 24       | 1.25%   |
| Biostar             | 24       | 1.25%   |
| Pegatron            | 22       | 1.14%   |
| ECS                 | 15       | 0.78%   |
| Medion              | 13       | 0.68%   |
| Unknown             | 11       | 0.57%   |
| Positivo            | 10       | 0.52%   |
| AZW                 | 8        | 0.42%   |
| Shuttle             | 6        | 0.31%   |
| Alienware           | 6        | 0.31%   |
| Fujitsu Siemens     | 5        | 0.26%   |
| BESSTAR Tech        | 5        | 0.26%   |
| Packard Bell        | 4        | 0.21%   |
| OEM                 | 4        | 0.21%   |
| MACHINIST           | 4        | 0.21%   |
| Wistron             | 3        | 0.16%   |
| PCWare              | 3        | 0.16%   |
| Apple               | 3        | 0.16%   |
| Supermicro          | 2        | 0.1%    |
| Login Informatica   | 2        | 0.1%    |
| Itautec             | 2        | 0.1%    |
| Huanan              | 2        | 0.1%    |
| Gateway             | 2        | 0.1%    |
| VS Company          | 1        | 0.05%   |
| Vorke               | 1        | 0.05%   |
| TPV-INVENTA         | 1        | 0.05%   |
| Semp Toshiba        | 1        | 0.05%   |
| Proline             | 1        | 0.05%   |
| Philco              | 1        | 0.05%   |
| PERTOSA             | 1        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 39       | 2.03%   |
| Gigabyte H410M H V3              | 27       | 1.4%    |
| ASUS SABERTOOTH Z77              | 19       | 0.99%   |
| Dell OptiPlex 7010               | 15       | 0.78%   |
| Unknown                          | 11       | 0.57%   |
| Intel H61                        | 9        | 0.47%   |
| Dell OptiPlex 780                | 9        | 0.47%   |
| MSI MS-7C91                      | 8        | 0.42%   |
| Dell OptiPlex 790                | 8        | 0.42%   |
| Dell OptiPlex 380                | 8        | 0.42%   |
| ASUS PRIME B450M-A II            | 8        | 0.42%   |
| Dell OptiPlex 9020               | 7        | 0.36%   |
| MSI MS-7C37                      | 6        | 0.31%   |
| MSI MS-7B79                      | 6        | 0.31%   |
| MSI MS-7A38                      | 6        | 0.31%   |
| MSI MS-7721                      | 6        | 0.31%   |
| HP EliteDesk 800 G1 SFF          | 6        | 0.31%   |
| HP Compaq Pro 6300 SFF           | 6        | 0.31%   |
| Gigabyte 970A-DS3P               | 6        | 0.31%   |
| Dell OptiPlex 745                | 6        | 0.31%   |
| Dell OptiPlex 7020               | 6        | 0.31%   |
| Dell OptiPlex 3020               | 6        | 0.31%   |
| ASUS TUF Gaming B550-PLUS        | 6        | 0.31%   |
| ASUS ROG STRIX B550-F GAMING     | 6        | 0.31%   |
| MSI MS-7C84                      | 5        | 0.26%   |
| MSI MS-7C02                      | 5        | 0.26%   |
| HP ProDesk 600 G1 SFF            | 5        | 0.26%   |
| HP Compaq 8100 Elite CMT PC      | 5        | 0.26%   |
| Gigabyte B550M AORUS PRO-P       | 5        | 0.26%   |
| Gigabyte B450M DS3H              | 5        | 0.26%   |
| Gigabyte A320M-S2H               | 5        | 0.26%   |
| Dell Precision WorkStation T3500 | 5        | 0.26%   |
| Dell OptiPlex 760                | 5        | 0.26%   |
| Dell OptiPlex 390                | 5        | 0.26%   |
| ASUS TUF Gaming B550M-PLUS       | 5        | 0.26%   |
| ASUS PRIME B450-PLUS             | 5        | 0.26%   |
| ASUS PRIME A320M-K               | 5        | 0.26%   |
| ASUS M5A78L-M/USB3               | 5        | 0.26%   |
| ASRock N68C-S UCC                | 5        | 0.26%   |
| ASRock B450M Steel Legend        | 5        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 106      | 5.51%   |
| ASUS PRIME             | 78       | 4.05%   |
| Lenovo ThinkCentre     | 55       | 2.86%   |
| HP Compaq              | 53       | 2.75%   |
| ASUS All               | 39       | 2.03%   |
| ASUS TUF               | 36       | 1.87%   |
| Acer Aspire            | 36       | 1.87%   |
| ASUS ROG               | 32       | 1.66%   |
| Gigabyte H410M         | 31       | 1.61%   |
| HP EliteDesk           | 27       | 1.4%    |
| ASUS SABERTOOTH        | 25       | 1.3%    |
| HP ProDesk             | 23       | 1.2%    |
| Fujitsu ESPRIMO        | 23       | 1.2%    |
| ASUS M5A78L-M          | 17       | 0.88%   |
| Dell Precision         | 16       | 0.83%   |
| Gigabyte B450M         | 13       | 0.68%   |
| Dell Inspiron          | 12       | 0.62%   |
| Dell Vostro            | 11       | 0.57%   |
| Acer Veriton           | 11       | 0.57%   |
| Unknown                | 11       | 0.57%   |
| Intel H61              | 10       | 0.52%   |
| Gigabyte Z390          | 10       | 0.52%   |
| Gigabyte X570          | 10       | 0.52%   |
| ASUS M5A97             | 10       | 0.52%   |
| ASRock B450M           | 10       | 0.52%   |
| HP Pavilion            | 9        | 0.47%   |
| Gigabyte B550M         | 9        | 0.47%   |
| Gigabyte B450          | 9        | 0.47%   |
| MSI MS-7C91            | 8        | 0.42%   |
| Lenovo IdeaCentre      | 8        | 0.42%   |
| Gigabyte GA-78LMT-USB3 | 8        | 0.42%   |
| ASUS P8H61-M           | 8        | 0.42%   |
| ASRock A320M-HDV       | 8        | 0.42%   |
| MSI MS-7C37            | 6        | 0.31%   |
| MSI MS-7B79            | 6        | 0.31%   |
| MSI MS-7A38            | 6        | 0.31%   |
| MSI MS-7721            | 6        | 0.31%   |
| HP Slim                | 6        | 0.31%   |
| Gigabyte H310M         | 6        | 0.31%   |
| Gigabyte 970A-DS3P     | 6        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 209      | 10.86%  |
| 2013 | 180      | 9.36%   |
| 2018 | 169      | 8.78%   |
| 2011 | 152      | 7.9%    |
| 2021 | 137      | 7.12%   |
| 2020 | 135      | 7.02%   |
| 2010 | 132      | 6.86%   |
| 2014 | 131      | 6.81%   |
| 2019 | 115      | 5.98%   |
| 2009 | 112      | 5.82%   |
| 2008 | 90       | 4.68%   |
| 2017 | 84       | 4.37%   |
| 2016 | 77       | 4%      |
| 2015 | 76       | 3.95%   |
| 2007 | 60       | 3.12%   |
| 2006 | 42       | 2.18%   |
| 2022 | 19       | 0.99%   |
| 2005 | 4        | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1924     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1924     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1924     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 438      | 22.77%  |
| 16.01-24.0      | 399      | 20.74%  |
| 4.01-8.0        | 384      | 19.96%  |
| 3.01-4.0        | 355      | 18.45%  |
| 32.01-64.0      | 193      | 10.03%  |
| 1.01-2.0        | 53       | 2.75%   |
| 64.01-256.0     | 41       | 2.13%   |
| 24.01-32.0      | 38       | 1.98%   |
| 2.01-3.0        | 18       | 0.94%   |
| 0.51-1.0        | 3        | 0.16%   |
| More than 256.0 | 2        | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 1288     | 66.94%  |
| 0.51-1.0  | 427      | 22.19%  |
| 2.01-3.0  | 133      | 6.91%   |
| 0.01-0.5  | 41       | 2.13%   |
| 3.01-4.0  | 20       | 1.04%   |
| 4.01-8.0  | 10       | 0.52%   |
| 8.01-16.0 | 5        | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 822      | 42.72%  |
| 2      | 524      | 27.23%  |
| 3      | 262      | 13.62%  |
| 4      | 153      | 7.95%   |
| 5      | 64       | 3.33%   |
| 0      | 46       | 2.39%   |
| 6      | 27       | 1.4%    |
| 7      | 11       | 0.57%   |
| 8      | 6        | 0.31%   |
| 9      | 4        | 0.21%   |
| 12     | 2        | 0.1%    |
| 15     | 1        | 0.05%   |
| 11     | 1        | 0.05%   |
| 10     | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1094     | 56.86%  |
| No        | 830      | 43.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1907     | 99.12%  |
| No        | 17       | 0.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1258     | 65.35%  |
| Yes       | 667      | 34.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1504     | 78.13%  |
| Yes       | 421      | 21.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 244      | 12.68%  |
| USA         | 238      | 12.37%  |
| Russia      | 157      | 8.16%   |
| Brazil      | 129      | 6.7%    |
| France      | 125      | 6.5%    |
| Poland      | 103      | 5.35%   |
| Italy       | 74       | 3.85%   |
| Canada      | 53       | 2.75%   |
| Spain       | 50       | 2.6%    |
| UK          | 49       | 2.55%   |
| Australia   | 44       | 2.29%   |
| India       | 41       | 2.13%   |
| Mexico      | 32       | 1.66%   |
| Argentina   | 31       | 1.61%   |
| Japan       | 27       | 1.4%    |
| Czechia     | 27       | 1.4%    |
| Ukraine     | 26       | 1.35%   |
| Austria     | 26       | 1.35%   |
| Netherlands | 24       | 1.25%   |
| Indonesia   | 18       | 0.94%   |
| Turkey      | 17       | 0.88%   |
| Sweden      | 17       | 0.88%   |
| Hungary     | 17       | 0.88%   |
| Switzerland | 16       | 0.83%   |
| Serbia      | 15       | 0.78%   |
| Romania     | 14       | 0.73%   |
| Portugal    | 13       | 0.68%   |
| Egypt       | 12       | 0.62%   |
| Belgium     | 12       | 0.62%   |
| Israel      | 11       | 0.57%   |
| Venezuela   | 10       | 0.52%   |
| Uruguay     | 10       | 0.52%   |
| Finland     | 10       | 0.52%   |
| Slovakia    | 9        | 0.47%   |
| Peru        | 9        | 0.47%   |
| Colombia    | 9        | 0.47%   |
| China       | 9        | 0.47%   |
| Algeria     | 9        | 0.47%   |
| Slovenia    | 8        | 0.42%   |
| Greece      | 8        | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 29       | 1.51%   |
| Gonikoppal        | 22       | 1.14%   |
| Strzyzow          | 17       | 0.88%   |
| Warsaw            | 15       | 0.78%   |
| Sao Paulo         | 15       | 0.78%   |
| Berlin            | 15       | 0.78%   |
| Vienna            | 13       | 0.68%   |
| St Petersburg     | 13       | 0.68%   |
| Sydney            | 10       | 0.52%   |
| Mexico City       | 10       | 0.52%   |
| Paris             | 9        | 0.47%   |
| Munich            | 9        | 0.47%   |
| Milan             | 9        | 0.47%   |
| Rio de Janeiro    | 8        | 0.42%   |
| Istanbul          | 8        | 0.42%   |
| Cairo             | 8        | 0.42%   |
| Brisbane          | 8        | 0.42%   |
| Rome              | 7        | 0.36%   |
| Nizhniy Novgorod  | 7        | 0.36%   |
| Montevideo        | 7        | 0.36%   |
| Lima              | 7        | 0.36%   |
| Jakarta           | 7        | 0.36%   |
| Buenos Aires      | 7        | 0.36%   |
| Braganca Paulista | 7        | 0.36%   |
| Belgrade          | 7        | 0.36%   |
| Yekaterinburg     | 6        | 0.31%   |
| Marseille         | 6        | 0.31%   |
| Kyiv              | 6        | 0.31%   |
| Hamburg           | 6        | 0.31%   |
| Zagreb            | 5        | 0.26%   |
| Wroclaw           | 5        | 0.26%   |
| Tel Aviv          | 5        | 0.26%   |
| San Marcos        | 5        | 0.26%   |
| San José         | 5        | 0.26%   |
| Rochester         | 5        | 0.26%   |
| Prague            | 5        | 0.26%   |
| Poznan            | 5        | 0.26%   |
| Nuremberg         | 5        | 0.26%   |
| Niterói          | 5        | 0.26%   |
| Madrid            | 5        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 645      | 836    | 19.64%  |
| Seagate             | 596      | 760    | 18.15%  |
| Samsung Electronics | 439      | 558    | 13.37%  |
| Kingston            | 199      | 220    | 6.06%   |
| Toshiba             | 182      | 198    | 5.54%   |
| Crucial             | 166      | 199    | 5.05%   |
| SanDisk             | 139      | 162    | 4.23%   |
| Hitachi             | 127      | 134    | 3.87%   |
| A-DATA Technology   | 97       | 103    | 2.95%   |
| China               | 41       | 47     | 1.25%   |
| Unknown             | 33       | 43     | 1%      |
| Maxtor              | 30       | 35     | 0.91%   |
| HGST                | 29       | 34     | 0.88%   |
| Intel               | 27       | 28     | 0.82%   |
| SPCC                | 26       | 30     | 0.79%   |
| PNY                 | 24       | 31     | 0.73%   |
| GOODRAM             | 23       | 25     | 0.7%    |
| Patriot             | 21       | 23     | 0.64%   |
| Gigabyte Technology | 19       | 19     | 0.58%   |
| Apacer              | 19       | 20     | 0.58%   |
| OCZ                 | 17       | 17     | 0.52%   |
| Netac               | 17       | 18     | 0.52%   |
| Intenso             | 17       | 18     | 0.52%   |
| Corsair             | 17       | 18     | 0.52%   |
| Unknown             | 17       | 18     | 0.52%   |
| Phison              | 16       | 18     | 0.49%   |
| Micron Technology   | 14       | 14     | 0.43%   |
| JMicron Technology  | 14       | 15     | 0.43%   |
| SK hynix            | 13       | 13     | 0.4%    |
| Hewlett-Packard     | 13       | 16     | 0.4%    |
| ASMT                | 13       | 15     | 0.4%    |
| Transcend           | 12       | 14     | 0.37%   |
| Team                | 12       | 12     | 0.37%   |
| XPG                 | 11       | 14     | 0.33%   |
| KIOXIA-EXCERIA      | 8        | 8      | 0.24%   |
| KingSpec            | 8        | 8      | 0.24%   |
| Silicon Motion      | 7        | 8      | 0.21%   |
| LITEON              | 7        | 7      | 0.21%   |
| KingFast            | 7        | 7      | 0.21%   |
| Apple               | 7        | 7      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 64       | 1.69%   |
| Seagate ST1000DM010-2EP102 1TB   | 52       | 1.37%   |
| Kingston SA400S37240G 240GB SSD  | 47       | 1.24%   |
| WDC WD10EZEX-08WN4A0 1TB         | 35       | 0.93%   |
| Seagate ST2000DM008-2FR102 2TB   | 33       | 0.87%   |
| Toshiba DT01ACA100 1TB           | 32       | 0.85%   |
| Crucial CT500MX500SSD1 500GB     | 31       | 0.82%   |
| Samsung SSD 860 EVO 250GB        | 30       | 0.79%   |
| Samsung SSD 860 EVO 500GB        | 28       | 0.74%   |
| Samsung SSD 850 EVO 250GB        | 28       | 0.74%   |
| Kingston SA400S37480G 480GB SSD  | 27       | 0.71%   |
| Kingston SA400S37120G 120GB SSD  | 27       | 0.71%   |
| Toshiba DT01ACA050 500GB         | 26       | 0.69%   |
| Seagate ST1000DM003-1ER162 1TB   | 23       | 0.61%   |
| A-DATA SU750 256GB SSD           | 22       | 0.58%   |
| Samsung SSD 970 EVO Plus 500GB   | 21       | 0.56%   |
| Kingston SV300S37A120G 120GB SSD | 20       | 0.53%   |
| Crucial CT1000MX500SSD1 1TB      | 20       | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 19       | 0.5%    |
| Crucial CT240BX500SSD1 240GB     | 19       | 0.5%    |
| Toshiba HDWD110 1TB              | 18       | 0.48%   |
| Seagate ST1000DM003-1CH162 1TB   | 18       | 0.48%   |
| Samsung HD502HJ 500GB            | 18       | 0.48%   |
| Crucial CT480BX500SSD1 480GB     | 18       | 0.48%   |
| Unknown SD/MMC/MS PRO 2GB        | 17       | 0.45%   |
| Seagate ST3500418AS 500GB        | 17       | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB   | 17       | 0.45%   |
| Seagate ST1000DM003-1SB102 1TB   | 17       | 0.45%   |
| Unknown                          | 17       | 0.45%   |
| Seagate ST3500413AS 500GB        | 16       | 0.42%   |
| SanDisk SSD PLUS 240GB           | 15       | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB     | 15       | 0.4%    |
| Samsung SSD 850 EVO 500GB        | 15       | 0.4%    |
| Seagate ST31000528AS 1TB         | 14       | 0.37%   |
| SanDisk SDSSDA240G 240GB         | 14       | 0.37%   |
| Samsung HD322HJ 320GB            | 14       | 0.37%   |
| WDC WD10EZEX-00BN5A0 1TB         | 13       | 0.34%   |
| Toshiba DT01ACA200 2TB           | 13       | 0.34%   |
| Seagate ST31000524AS 1TB         | 13       | 0.34%   |
| Seagate Expansion 240GB          | 12       | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 587      | 743    | 34.13%  |
| WDC                 | 563      | 698    | 32.73%  |
| Toshiba             | 168      | 184    | 9.77%   |
| Samsung Electronics | 142      | 162    | 8.26%   |
| Hitachi             | 127      | 134    | 7.38%   |
| Maxtor              | 29       | 34     | 1.69%   |
| HGST                | 29       | 34     | 1.69%   |
| Unknown             | 18       | 18     | 1.05%   |
| ASMT                | 13       | 15     | 0.76%   |
| Apple               | 7        | 7      | 0.41%   |
| Fujitsu             | 5        | 5      | 0.29%   |
| USB3.0              | 4        | 4      | 0.23%   |
| WD MediaMax         | 3        | 4      | 0.17%   |
| SABRENT             | 3        | 4      | 0.17%   |
| Intenso             | 3        | 3      | 0.17%   |
| IBM/Hitachi         | 3        | 3      | 0.17%   |
| Magnetic Data       | 2        | 2      | 0.12%   |
| JMicron Technology  | 2        | 2      | 0.12%   |
| HPE                 | 2        | 2      | 0.12%   |
| Hewlett-Packard     | 2        | 2      | 0.12%   |
| Unknown             | 2        | 2      | 0.12%   |
| RSH-339             | 1        | 1      | 0.06%   |
| Quantum             | 1        | 1      | 0.06%   |
| MARVELL             | 1        | 1      | 0.06%   |
| ExcelStor           | 1        | 1      | 0.06%   |
| Config              | 1        | 1      | 0.06%   |
| China               | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 223      | 259    | 18%     |
| Kingston            | 170      | 184    | 13.72%  |
| Crucial             | 138      | 163    | 11.14%  |
| SanDisk             | 126      | 145    | 10.17%  |
| A-DATA Technology   | 80       | 80     | 6.46%   |
| WDC                 | 78       | 88     | 6.3%    |
| China               | 40       | 46     | 3.23%   |
| GOODRAM             | 21       | 21     | 1.69%   |
| PNY                 | 20       | 25     | 1.61%   |
| SPCC                | 19       | 22     | 1.53%   |
| Intel               | 18       | 19     | 1.45%   |
| Patriot             | 17       | 19     | 1.37%   |
| OCZ                 | 17       | 17     | 1.37%   |
| Apacer              | 17       | 17     | 1.37%   |
| Unknown             | 15       | 16     | 1.21%   |
| Netac               | 13       | 14     | 1.05%   |
| Micron Technology   | 13       | 13     | 1.05%   |
| Intenso             | 13       | 14     | 1.05%   |
| Team                | 12       | 12     | 0.97%   |
| Gigabyte Technology | 12       | 12     | 0.97%   |
| Toshiba             | 11       | 11     | 0.89%   |
| Transcend           | 10       | 11     | 0.81%   |
| JMicron Technology  | 9        | 10     | 0.73%   |
| KingSpec            | 8        | 8      | 0.65%   |
| Hewlett-Packard     | 8        | 10     | 0.65%   |
| KingFast            | 7        | 7      | 0.56%   |
| LITEON              | 6        | 6      | 0.48%   |
| KIOXIA-EXCERIA      | 6        | 6      | 0.48%   |
| Corsair             | 6        | 6      | 0.48%   |
| TO Exter            | 5        | 5      | 0.4%    |
| SK hynix            | 4        | 4      | 0.32%   |
| Seagate             | 4        | 4      | 0.32%   |
| LITEONIT            | 4        | 4      | 0.32%   |
| KingDian            | 4        | 4      | 0.32%   |
| Colorful            | 4        | 4      | 0.32%   |
| Mushkin             | 3        | 3      | 0.24%   |
| Leven               | 3        | 3      | 0.24%   |
| Emtec               | 3        | 3      | 0.24%   |
| Zheino              | 2        | 3      | 0.16%   |
| XrayDisk            | 2        | 2      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1351     | 2068   | 49.71%  |
| SSD     | 979      | 1368   | 36.02%  |
| NVMe    | 351      | 446    | 12.91%  |
| Unknown | 31       | 43     | 1.14%   |
| MMC     | 6        | 7      | 0.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1794     | 3300   | 77.97%  |
| NVMe | 349      | 440    | 15.17%  |
| SAS  | 152      | 185    | 6.61%   |
| MMC  | 6        | 7      | 0.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1440     | 2096   | 57.74%  |
| 0.51-1.0   | 668      | 870    | 26.78%  |
| 1.01-2.0   | 216      | 253    | 8.66%   |
| 2.01-3.0   | 65       | 75     | 2.61%   |
| 3.01-4.0   | 49       | 68     | 1.96%   |
| 4.01-10.0  | 48       | 66     | 1.92%   |
| 10.01-20.0 | 8        | 8      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1046     | 54.34%  |
| Unknown        | 267      | 13.87%  |
| 101-250        | 224      | 11.64%  |
| 251-500        | 137      | 7.12%   |
| 501-1000       | 72       | 3.74%   |
| 21-50          | 71       | 3.69%   |
| 51-100         | 59       | 3.06%   |
| 1001-2000      | 29       | 1.51%   |
| More than 3000 | 12       | 0.62%   |
| 2001-3000      | 8        | 0.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1510     | 78.4%   |
| Unknown        | 267      | 13.86%  |
| 101-250        | 40       | 2.08%   |
| 21-50          | 29       | 1.51%   |
| 51-100         | 26       | 1.35%   |
| 251-500        | 22       | 1.14%   |
| 501-1000       | 19       | 0.99%   |
| 1001-2000      | 9        | 0.47%   |
| More than 3000 | 2        | 0.1%    |
| 2001-3000      | 2        | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 27       | 28     | 3.72%   |
| Samsung Electronics HD322HJ 320GB | 9        | 10     | 1.24%   |
| Seagate ST3500413AS 500GB         | 8        | 8      | 1.1%    |
| Seagate ST1000DM010-2EP102 1TB    | 8        | 8      | 1.1%    |
| Seagate ST1000DM003-9YN162 1TB    | 8        | 8      | 1.1%    |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 6        | 6      | 0.83%   |
| Seagate ST9500325AS 500GB         | 6        | 6      | 0.83%   |
| Seagate ST3500418AS 500GB         | 6        | 6      | 0.83%   |
| Seagate ST31000524AS 1TB          | 6        | 6      | 0.83%   |
| Seagate ST2000DM001-1CH164 2TB    | 6        | 6      | 0.83%   |
| Samsung Electronics HD502HJ 500GB | 6        | 6      | 0.83%   |
| Kingston SV300S37A120G 120GB SSD  | 6        | 6      | 0.83%   |
| WDC WD5000AAKS-00V1A0 500GB       | 5        | 5      | 0.69%   |
| WDC WD5000AADS-00S9B0 500GB       | 5        | 5      | 0.69%   |
| Seagate ST3320418AS 320GB         | 5        | 5      | 0.69%   |
| Seagate ST1000DM003-1SB102 1TB    | 5        | 5      | 0.69%   |
| Seagate ST1000DM003-1CH162 1TB    | 5        | 5      | 0.69%   |
| SanDisk SSD PLUS 240GB            | 5        | 5      | 0.69%   |
| Hitachi HDS721050CLA362 500GB     | 5        | 5      | 0.69%   |
| GOODRAM SSD 120GB                 | 5        | 5      | 0.69%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 4        | 4      | 0.55%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 4        | 4      | 0.55%   |
| WDC WD3200AAJS-00L7A0 320GB       | 4        | 4      | 0.55%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 4        | 4      | 0.55%   |
| WDC WD10EZEX-08WN4A0 1TB          | 4        | 4      | 0.55%   |
| WDC WD10EARS-00Y5B1 1TB           | 4        | 5      | 0.55%   |
| WDC WD10EALX-009BA0 1TB           | 4        | 4      | 0.55%   |
| Toshiba DT01ACA100 1TB            | 4        | 4      | 0.55%   |
| Toshiba DT01ACA050 500GB          | 4        | 4      | 0.55%   |
| Seagate ST92505610AS 250GB        | 4        | 4      | 0.55%   |
| Seagate ST380013AS 80GB           | 4        | 4      | 0.55%   |
| Seagate ST31000528AS 1TB          | 4        | 4      | 0.55%   |
| Seagate ST250DM000-1BD141 250GB   | 4        | 4      | 0.55%   |
| Samsung Electronics SP2504C 250GB | 4        | 4      | 0.55%   |
| Samsung Electronics HD753LJ 752GB | 4        | 4      | 0.55%   |
| Samsung Electronics HD502HI 500GB | 4        | 4      | 0.55%   |
| Samsung Electronics HD161HJ 160GB | 4        | 4      | 0.55%   |
| Samsung Electronics HD160JJ 160GB | 4        | 4      | 0.55%   |
| Maxtor STM3250310AS 250GB         | 4        | 4      | 0.55%   |
| Hitachi HDS721010DLE630 1TB       | 4        | 4      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 207      | 224    | 29.96%  |
| WDC                 | 193      | 212    | 27.93%  |
| Samsung Electronics | 76       | 81     | 11%     |
| Hitachi             | 55       | 57     | 7.96%   |
| Toshiba             | 24       | 24     | 3.47%   |
| Maxtor              | 19       | 20     | 2.75%   |
| SanDisk             | 17       | 17     | 2.46%   |
| Kingston            | 17       | 17     | 2.46%   |
| HGST                | 11       | 12     | 1.59%   |
| Crucial             | 8        | 9      | 1.16%   |
| A-DATA Technology   | 7        | 7      | 1.01%   |
| Intel               | 6        | 6      | 0.87%   |
| GOODRAM             | 5        | 5      | 0.72%   |
| ASMT                | 4        | 4      | 0.58%   |
| OCZ                 | 3        | 3      | 0.43%   |
| Micron Technology   | 3        | 3      | 0.43%   |
| IBM/Hitachi         | 3        | 3      | 0.43%   |
| SPCC                | 2        | 2      | 0.29%   |
| Patriot             | 2        | 2      | 0.29%   |
| Fujitsu             | 2        | 2      | 0.29%   |
| China               | 2        | 2      | 0.29%   |
| Unknown             | 2        | 2      | 0.29%   |
| WDC WDS2            | 1        | 1      | 0.14%   |
| WD MediaMax         | 1        | 1      | 0.14%   |
| USB3.0              | 1        | 1      | 0.14%   |
| Transcend           | 1        | 1      | 0.14%   |
| TO Exter            | 1        | 1      | 0.14%   |
| TEXTORM             | 1        | 1      | 0.14%   |
| TCSUNBOW            | 1        | 1      | 0.14%   |
| RSH-339             | 1        | 1      | 0.14%   |
| Neo                 | 1        | 1      | 0.14%   |
| LITEONIT            | 1        | 1      | 0.14%   |
| LITEON              | 1        | 1      | 0.14%   |
| KingSpec            | 1        | 1      | 0.14%   |
| Kingmax             | 1        | 1      | 0.14%   |
| KingDian            | 1        | 1      | 0.14%   |
| INNOVATION IT       | 1        | 1      | 0.14%   |
| Initio              | 1        | 1      | 0.14%   |
| HPE                 | 1        | 1      | 0.14%   |
| Hewlett-Packard     | 1        | 1      | 0.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 207      | 224    | 35.45%  |
| WDC                 | 184      | 201    | 31.51%  |
| Samsung Electronics | 69       | 74     | 11.82%  |
| Hitachi             | 55       | 57     | 9.42%   |
| Toshiba             | 24       | 24     | 4.11%   |
| Maxtor              | 19       | 20     | 3.25%   |
| HGST                | 11       | 12     | 1.88%   |
| ASMT                | 4        | 4      | 0.68%   |
| IBM/Hitachi         | 3        | 3      | 0.51%   |
| Fujitsu             | 2        | 2      | 0.34%   |
| WD MediaMax         | 1        | 1      | 0.17%   |
| USB3.0              | 1        | 1      | 0.17%   |
| RSH-339             | 1        | 1      | 0.17%   |
| HPE                 | 1        | 1      | 0.17%   |
| ExcelStor           | 1        | 1      | 0.17%   |
| Unknown             | 1        | 1      | 0.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 516      | 627    | 83.09%  |
| SSD  | 101      | 106    | 16.26%  |
| NVMe | 4        | 5      | 0.64%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Samsung Electronics HD103SJ 1TB                  | 3        | 3      | 12.5%   |
| Apple HDD HTS541010A9E662 1TB                    | 3        | 3      | 12.5%   |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1        | 1      | 4.17%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1        | 1      | 4.17%   |
| WDC WD1600YS-23SHB0 160GB                        | 1        | 1      | 4.17%   |
| Toshiba MQ01ABD050 500GB                         | 1        | 1      | 4.17%   |
| Toshiba MK3256GSY 320GB                          | 1        | 1      | 4.17%   |
| Toshiba DT01ACA100 1TB                           | 1        | 1      | 4.17%   |
| Seagate STM31000528AS 1TB                        | 1        | 1      | 4.17%   |
| Seagate ST980811AS 80GB                          | 1        | 1      | 4.17%   |
| Seagate ST3250318AS 249GB                        | 1        | 1      | 4.17%   |
| Seagate ST3160215A 160GB                         | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 980 500GB                | 1        | 1      | 4.17%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 4.17%   |
| Samsung Electronics HM160HI 160GB                | 1        | 1      | 4.17%   |
| Samsung Electronics HD103UJ 1TB                  | 1        | 1      | 4.17%   |
| Hitachi HTS725050A7E630 500GB                    | 1        | 1      | 4.17%   |
| Hitachi HDS721010DLE630 1TB                      | 1        | 1      | 4.17%   |
| Hitachi HDP725050GLA360 500GB                    | 1        | 1      | 4.17%   |
| GOODRAM SSDPR-PX500-256-80 256GB                 | 1        | 1      | 4.17%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 7      | 29.17%  |
| Seagate             | 4        | 4      | 16.67%  |
| WDC                 | 3        | 3      | 12.5%   |
| Toshiba             | 3        | 3      | 12.5%   |
| Hitachi             | 3        | 3      | 12.5%   |
| Apple               | 3        | 3      | 12.5%   |
| GOODRAM             | 1        | 1      | 4.17%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1578     | 3000   | 67.23%  |
| Malfunc  | 603      | 738    | 25.69%  |
| Detected | 143      | 170    | 6.09%   |
| Failed   | 23       | 24     | 0.98%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1273     | 49.84%  |
| AMD                              | 575      | 22.51%  |
| Samsung Electronics              | 119      | 4.66%   |
| JMicron Technology               | 80       | 3.13%   |
| ASMedia Technology               | 69       | 2.7%    |
| Marvell Technology Group         | 66       | 2.58%   |
| Nvidia                           | 62       | 2.43%   |
| SanDisk                          | 60       | 2.35%   |
| Phison Electronics               | 46       | 1.8%    |
| Kingston Technology Company      | 34       | 1.33%   |
| Micron/Crucial Technology        | 32       | 1.25%   |
| Silicon Motion                   | 29       | 1.14%   |
| VIA Technologies                 | 20       | 0.78%   |
| ADATA Technology                 | 18       | 0.7%    |
| Realtek Semiconductor            | 12       | 0.47%   |
| SK hynix                         | 8        | 0.31%   |
| Seagate Technology               | 7        | 0.27%   |
| Integrated Technology Express    | 5        | 0.2%    |
| Broadcom / LSI                   | 5        | 0.2%    |
| Toshiba America Info Systems     | 4        | 0.16%   |
| Micron Technology                | 4        | 0.16%   |
| Lite-On Technology               | 4        | 0.16%   |
| MAXIO Technology (Hangzhou)      | 3        | 0.12%   |
| LSI Logic / Symbios Logic        | 3        | 0.12%   |
| Union Memory (Shenzhen)          | 2        | 0.08%   |
| Silicon Image                    | 2        | 0.08%   |
| KIOXIA                           | 2        | 0.08%   |
| Adaptec                          | 2        | 0.08%   |
| Yangtze Memory Technologies      | 1        | 0.04%   |
| Silicon Integrated Systems [SiS] | 1        | 0.04%   |
| Shenzhen Longsys Electronics     | 1        | 0.04%   |
| Netac Technology                 | 1        | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.04%   |
| INNOGRIT                         | 1        | 0.04%   |
| Hewlett-Packard                  | 1        | 0.04%   |
| 3ware                            | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 285      | 8.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 176      | 5.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 119      | 3.64%   |
| AMD 400 Series Chipset SATA Controller                                                  | 107      | 3.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 106      | 3.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 103      | 3.15%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 93       | 2.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 85       | 2.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 83       | 2.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 76       | 2.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 76       | 2.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 71       | 2.17%   |
| AMD 500 Series Chipset SATA Controller                                                  | 71       | 2.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 64       | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 63       | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 63       | 1.93%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 63       | 1.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 61       | 1.86%   |
| Intel SATA Controller [RAID mode]                                                       | 59       | 1.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 58       | 1.77%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 53       | 1.62%   |
| Nvidia MCP61 SATA Controller                                                            | 37       | 1.13%   |
| AMD FCH SATA Controller D                                                               | 37       | 1.13%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 32       | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 32       | 0.98%   |
| Nvidia MCP61 IDE                                                                        | 31       | 0.95%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 31       | 0.95%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 30       | 0.92%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 30       | 0.92%   |
| AMD FCH IDE Controller                                                                  | 29       | 0.89%   |
| Phison E12 NVMe Controller                                                              | 24       | 0.73%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 24       | 0.73%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 23       | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 22       | 0.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 22       | 0.67%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 22       | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 21       | 0.64%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 21       | 0.64%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 20       | 0.61%   |
| AMD 300 Series Chipset SATA Controller                                                  | 20       | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1468     | 57.86%  |
| IDE  | 616      | 24.28%  |
| NVMe | 346      | 13.64%  |
| RAID | 95       | 3.74%   |
| SAS  | 8        | 0.32%   |
| SCSI | 4        | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1295     | 67.31%  |
| AMD    | 629      | 32.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-10400 CPU @ 2.90GHz           | 40       | 2.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 30       | 1.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 26       | 1.35%   |
| AMD Ryzen 5 3600 6-Core Processor           | 25       | 1.3%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 24       | 1.25%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 23       | 1.2%    |
| Intel Core i5-3570K CPU @ 3.40GHz           | 22       | 1.14%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 22       | 1.14%   |
| AMD FX-8350 Eight-Core Processor            | 21       | 1.09%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 20       | 1.04%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 19       | 0.99%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 19       | 0.99%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 18       | 0.94%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 18       | 0.94%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 17       | 0.88%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 17       | 0.88%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 17       | 0.88%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 16       | 0.83%   |
| AMD FX-6300 Six-Core Processor              | 16       | 0.83%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 15       | 0.78%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 15       | 0.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 15       | 0.78%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 14       | 0.73%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 14       | 0.73%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 13       | 0.68%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 13       | 0.68%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 12       | 0.62%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 12       | 0.62%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 12       | 0.62%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 12       | 0.62%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 12       | 0.62%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 11       | 0.57%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 11       | 0.57%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 11       | 0.57%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 11       | 0.57%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 11       | 0.57%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 10       | 0.52%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 10       | 0.52%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 10       | 0.52%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 10       | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 404      | 21%     |
| Intel Core i3           | 196      | 10.19%  |
| Intel Core i7           | 156      | 8.11%   |
| AMD Ryzen 5             | 125      | 6.5%    |
| Intel Core 2 Duo        | 88       | 4.57%   |
| Intel Celeron           | 79       | 4.11%   |
| AMD FX                  | 79       | 4.11%   |
| AMD Ryzen 7             | 76       | 3.95%   |
| Intel Pentium           | 71       | 3.69%   |
| Intel Xeon              | 65       | 3.38%   |
| Intel Core 2 Quad       | 62       | 3.22%   |
| Intel Pentium Dual-Core | 48       | 2.49%   |
| Other                   | 43       | 2.23%   |
| AMD Ryzen 3             | 36       | 1.87%   |
| AMD A8                  | 32       | 1.66%   |
| AMD Phenom II X4        | 29       | 1.51%   |
| AMD Athlon II X2        | 28       | 1.46%   |
| AMD A4                  | 22       | 1.14%   |
| AMD Ryzen 9             | 21       | 1.09%   |
| AMD A10                 | 21       | 1.09%   |
| AMD Athlon 64 X2        | 20       | 1.04%   |
| AMD Athlon              | 20       | 1.04%   |
| Intel Core 2            | 18       | 0.94%   |
| Intel Pentium Dual      | 15       | 0.78%   |
| AMD A6                  | 15       | 0.78%   |
| Intel Core i9           | 14       | 0.73%   |
| Intel Pentium Gold      | 10       | 0.52%   |
| AMD Ryzen 5 PRO         | 10       | 0.52%   |
| AMD Athlon II X4        | 10       | 0.52%   |
| Intel Atom              | 9        | 0.47%   |
| AMD Phenom              | 9        | 0.47%   |
| AMD Athlon X4           | 9        | 0.47%   |
| AMD Athlon II X3        | 9        | 0.47%   |
| Intel Pentium D         | 8        | 0.42%   |
| AMD Sempron             | 7        | 0.36%   |
| Intel Pentium 4         | 6        | 0.31%   |
| AMD Phenom II X2        | 6        | 0.31%   |
| AMD Ryzen 3 PRO         | 5        | 0.26%   |
| AMD Phenom II X6        | 5        | 0.26%   |
| AMD Athlon 64           | 5        | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 726      | 37.73%  |
| 2      | 683      | 35.5%   |
| 6      | 264      | 13.72%  |
| 8      | 118      | 6.13%   |
| 1      | 48       | 2.49%   |
| 3      | 35       | 1.82%   |
| 12     | 23       | 1.2%    |
| 16     | 15       | 0.78%   |
| 10     | 7        | 0.36%   |
| 14     | 2        | 0.1%    |
| 44     | 1        | 0.05%   |
| 28     | 1        | 0.05%   |
| 20     | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1910     | 99.27%  |
| 2      | 14       | 0.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 974      | 50.62%  |
| 2      | 948      | 49.27%  |
| 4      | 2        | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1923     | 99.95%  |
| Unknown        | 1        | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 211      | 10.97%  |
| 0x1067a    | 151      | 7.85%   |
| 0x306a9    | 147      | 7.64%   |
| 0x206a7    | 137      | 7.12%   |
| 0x08701021 | 68       | 3.53%   |
| 0x906ea    | 67       | 3.48%   |
| 0x506e3    | 63       | 3.27%   |
| Unknown    | 47       | 2.44%   |
| 0xa0655    | 46       | 2.39%   |
| 0x906e9    | 46       | 2.39%   |
| 0xa0653    | 36       | 1.87%   |
| 0x6fb      | 35       | 1.82%   |
| 0x010000c8 | 35       | 1.82%   |
| 0x0800820d | 34       | 1.77%   |
| 0x06001119 | 34       | 1.77%   |
| 0x08108109 | 29       | 1.51%   |
| 0x06000822 | 28       | 1.46%   |
| 0x0a50000c | 26       | 1.35%   |
| 0x06003106 | 25       | 1.3%    |
| 0x106e5    | 24       | 1.25%   |
| 0x20655    | 23       | 1.2%    |
| 0xa0671    | 21       | 1.09%   |
| 0x6fd      | 20       | 1.04%   |
| 0x08101016 | 20       | 1.04%   |
| 0x010000b6 | 20       | 1.04%   |
| 0x10676    | 19       | 0.99%   |
| 0x906eb    | 18       | 0.94%   |
| 0x0a201016 | 18       | 0.94%   |
| 0x08001138 | 15       | 0.78%   |
| 0x906ec    | 13       | 0.68%   |
| 0x90672    | 13       | 0.68%   |
| 0x106a5    | 13       | 0.68%   |
| 0x08600106 | 13       | 0.68%   |
| 0x0600081c | 12       | 0.62%   |
| 0x03000027 | 12       | 0.62%   |
| 0x206d7    | 11       | 0.57%   |
| 0x20652    | 11       | 0.57%   |
| 0x0700010b | 11       | 0.57%   |
| 0x00000000 | 11       | 0.57%   |
| 0x6f6      | 10       | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 226      | 11.75%  |
| Penryn           | 180      | 9.36%   |
| KabyLake         | 160      | 8.32%   |
| IvyBridge        | 156      | 8.11%   |
| SandyBridge      | 150      | 7.8%    |
| K10              | 102      | 5.3%    |
| Piledriver       | 101      | 5.25%   |
| Zen 2            | 91       | 4.73%   |
| CometLake        | 82       | 4.26%   |
| Core             | 80       | 4.16%   |
| Zen+             | 73       | 3.79%   |
| Zen 3            | 68       | 3.53%   |
| Skylake          | 66       | 3.43%   |
| Zen              | 59       | 3.07%   |
| Westmere         | 42       | 2.18%   |
| Nehalem          | 39       | 2.03%   |
| Steamroller      | 30       | 1.56%   |
| K8 Hammer        | 29       | 1.51%   |
| Icelake          | 21       | 1.09%   |
| NetBurst         | 17       | 0.88%   |
| K10 Llano        | 17       | 0.88%   |
| Alderlake Hybrid | 17       | 0.88%   |
| Excavator        | 16       | 0.83%   |
| Silvermont       | 14       | 0.73%   |
| Bulldozer        | 14       | 0.73%   |
| Jaguar           | 13       | 0.68%   |
| Goldmont plus    | 13       | 0.68%   |
| Puma             | 11       | 0.57%   |
| Goldmont         | 8        | 0.42%   |
| Broadwell        | 8        | 0.42%   |
| Bonnell          | 8        | 0.42%   |
| Tremont          | 7        | 0.36%   |
| Bobcat           | 5        | 0.26%   |
| TigerLake        | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 694      | 35%     |
| Nvidia                     | 686      | 34.59%  |
| AMD                        | 594      | 29.95%  |
| VIA Technologies           | 3        | 0.15%   |
| Matrox Electronics Systems | 3        | 0.15%   |
| Conexant Systems           | 1        | 0.05%   |
| ATI Technologies           | 1        | 0.05%   |
| ASPEED Technology          | 1        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 113      | 5.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 89       | 4.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 68       | 3.38%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 67       | 3.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 58       | 2.89%   |
| Nvidia GK208B [GeForce GT 710]                                              | 55       | 2.74%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 53       | 2.64%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 40       | 1.99%   |
| Nvidia GT218 [GeForce 210]                                                  | 38       | 1.89%   |
| Intel HD Graphics 530                                                       | 38       | 1.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 38       | 1.89%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 33       | 1.64%   |
| Nvidia GK208B [GeForce GT 730]                                              | 30       | 1.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 30       | 1.49%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 29       | 1.44%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 27       | 1.34%   |
| Intel HD Graphics 630                                                       | 25       | 1.24%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 24       | 1.19%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 22       | 1.1%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 21       | 1.05%   |
| Nvidia GF108 [GeForce GT 630]                                               | 21       | 1.05%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 19       | 0.95%   |
| Intel Core Processor Integrated Graphics Controller                         | 17       | 0.85%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 17       | 0.85%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 17       | 0.85%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 15       | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 15       | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 15       | 0.75%   |
| AMD Renoir                                                                  | 15       | 0.75%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 15       | 0.75%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 14       | 0.7%    |
| Nvidia GF119 [GeForce GT 610]                                               | 14       | 0.7%    |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 14       | 0.7%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 13       | 0.65%   |
| AMD RS780L [Radeon 3000]                                                    | 13       | 0.65%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 13       | 0.65%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 13       | 0.65%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 12       | 0.6%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 11       | 0.55%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 11       | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 661      | 34.36%  |
| 1 x Intel                | 640      | 33.26%  |
| 1 x AMD                  | 563      | 29.26%  |
| 2 x AMD                  | 20       | 1.04%   |
| Intel + Nvidia           | 15       | 0.78%   |
| Intel + AMD              | 7        | 0.36%   |
| 2 x Nvidia               | 5        | 0.26%   |
| AMD + Nvidia             | 4        | 0.21%   |
| 1 x VIA                  | 3        | 0.16%   |
| 1 x Matrox               | 3        | 0.16%   |
| 3 x AMD                  | 1        | 0.05%   |
| Nvidia + ASPEED          | 1        | 0.05%   |
| Intel + Conexant Systems | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1848     | 96.05%  |
| Unknown     | 74       | 3.85%   |
| Proprietary | 2        | 0.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 711      | 36.95%  |
| 1.01-2.0   | 332      | 17.26%  |
| 0.51-1.0   | 291      | 15.12%  |
| 0.01-0.5   | 242      | 12.58%  |
| 3.01-4.0   | 128      | 6.65%   |
| 7.01-8.0   | 121      | 6.29%   |
| 5.01-6.0   | 51       | 2.65%   |
| 2.01-3.0   | 25       | 1.3%    |
| 8.01-16.0  | 19       | 0.99%   |
| 16.01-24.0 | 4        | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 323      | 17.05%  |
| Goldstar             | 214      | 11.3%   |
| Dell                 | 184      | 9.71%   |
| Hewlett-Packard      | 174      | 9.19%   |
| Acer                 | 139      | 7.34%   |
| Philips              | 121      | 6.39%   |
| AOC                  | 118      | 6.23%   |
| BenQ                 | 80       | 4.22%   |
| Ancor Communications | 66       | 3.48%   |
| ViewSonic            | 56       | 2.96%   |
| Iiyama               | 32       | 1.69%   |
| Lenovo               | 27       | 1.43%   |
| ASUSTek Computer     | 22       | 1.16%   |
| Sony                 | 21       | 1.11%   |
| Eizo                 | 18       | 0.95%   |
| NEC Computers        | 16       | 0.84%   |
| Fujitsu Siemens      | 15       | 0.79%   |
| HannStar             | 13       | 0.69%   |
| Panasonic            | 11       | 0.58%   |
| Sceptre Tech         | 9        | 0.48%   |
| Toshiba              | 8        | 0.42%   |
| MSI                  | 8        | 0.42%   |
| Medion               | 8        | 0.42%   |
| Hitachi              | 8        | 0.42%   |
| Unknown              | 7        | 0.37%   |
| TCL                  | 7        | 0.37%   |
| ___                  | 6        | 0.32%   |
| Vestel Elektronik    | 6        | 0.32%   |
| Unknown (XXX)        | 6        | 0.32%   |
| Packard Bell         | 5        | 0.26%   |
| MiTAC                | 5        | 0.26%   |
| IOD                  | 5        | 0.26%   |
| GDH                  | 5        | 0.26%   |
| CHD                  | 5        | 0.26%   |
| Belinea              | 5        | 0.26%   |
| Xiaomi               | 4        | 0.21%   |
| MStar                | 4        | 0.21%   |
| Mitsubishi           | 4        | 0.21%   |
| Gigabyte Technology  | 4        | 0.21%   |
| Envision             | 4        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                      | 22       | 1.14%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 16       | 0.83%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                 | 14       | 0.73%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 8        | 0.41%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 8        | 0.41%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 8        | 0.41%   |
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                    | 8        | 0.41%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                   | 7        | 0.36%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 6        | 0.31%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 6        | 0.31%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 6        | 0.31%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 6        | 0.31%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 6        | 0.31%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 6        | 0.31%   |
| AOC 2217 AOC2217 1680x1050 470x300mm 22.0-inch                        | 6        | 0.31%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch      | 6        | 0.31%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 6        | 0.31%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch  | 5        | 0.26%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 5        | 0.26%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch     | 5        | 0.26%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch  | 5        | 0.26%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 5        | 0.26%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 5        | 0.26%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 5        | 0.26%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 5        | 0.26%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 5        | 0.26%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 5        | 0.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 4        | 0.21%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 4        | 0.21%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 4        | 0.21%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch            | 4        | 0.21%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 4        | 0.21%   |
| Hewlett-Packard 22w HPN342E 1920x1080 476x268mm 21.5-inch             | 4        | 0.21%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 4        | 0.21%   |
| GDH Digital TV GDH0030 1920x540                                       | 4        | 0.21%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 4        | 0.21%   |
| BenQ EX2780Q BNQ7F76 2560x1440 597x336mm 27.0-inch                    | 4        | 0.21%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 4        | 0.21%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 4        | 0.21%   |
| ___ LCDTV16 ___0101 1360x768                                          | 3        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 903      | 48.42%  |
| 1280x1024 (SXGA)   | 167      | 8.95%   |
| 3840x2160 (4K)     | 147      | 7.88%   |
| 1366x768 (WXGA)    | 110      | 5.9%    |
| 2560x1440 (QHD)    | 104      | 5.58%   |
| 1680x1050 (WSXGA+) | 102      | 5.47%   |
| 1440x900 (WXGA+)   | 77       | 4.13%   |
| 1600x900 (HD+)     | 70       | 3.75%   |
| 1920x1200 (WUXGA)  | 51       | 2.73%   |
| 1360x768           | 37       | 1.98%   |
| 3440x1440          | 22       | 1.18%   |
| 2560x1080          | 17       | 0.91%   |
| 1920x540           | 13       | 0.7%    |
| 1024x768 (XGA)     | 11       | 0.59%   |
| 1600x1200          | 8        | 0.43%   |
| 1280x720 (HD)      | 6        | 0.32%   |
| 2288x1287          | 4        | 0.21%   |
| 2048x1152          | 4        | 0.21%   |
| 1280x960           | 4        | 0.21%   |
| 2560x1600          | 2        | 0.11%   |
| 1280x768           | 2        | 0.11%   |
| 3840x1600          | 1        | 0.05%   |
| 3840x1200          | 1        | 0.05%   |
| 3840x1080          | 1        | 0.05%   |
| Unknown            | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 268      | 14.16%  |
| 21      | 262      | 13.85%  |
| 27      | 254      | 13.42%  |
| 24      | 219      | 11.58%  |
| 19      | 162      | 8.56%   |
| 18      | 113      | 5.97%   |
| 17      | 92       | 4.86%   |
| 22      | 84       | 4.44%   |
| 31      | 81       | 4.28%   |
| 20      | 63       | 3.33%   |
| 84      | 35       | 1.85%   |
| 34      | 35       | 1.85%   |
| 15      | 30       | 1.59%   |
| 32      | 24       | 1.27%   |
| Unknown | 22       | 1.16%   |
| 40      | 19       | 1%      |
| 72      | 16       | 0.85%   |
| 54      | 13       | 0.69%   |
| 25      | 11       | 0.58%   |
| 26      | 9        | 0.48%   |
| 52      | 8        | 0.42%   |
| 65      | 7        | 0.37%   |
| 48      | 6        | 0.32%   |
| 39      | 6        | 0.32%   |
| 33      | 6        | 0.32%   |
| 46      | 5        | 0.26%   |
| 43      | 5        | 0.26%   |
| 47      | 4        | 0.21%   |
| 42      | 4        | 0.21%   |
| 35      | 4        | 0.21%   |
| 29      | 4        | 0.21%   |
| 28      | 4        | 0.21%   |
| 142     | 3        | 0.16%   |
| 12      | 3        | 0.16%   |
| 55      | 2        | 0.11%   |
| 37      | 2        | 0.11%   |
| 14      | 2        | 0.11%   |
| 60      | 1        | 0.05%   |
| 58      | 1        | 0.05%   |
| 50      | 1        | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 712      | 38.34%  |
| 401-500        | 600      | 32.31%  |
| 301-350        | 117      | 6.3%    |
| 601-700        | 107      | 5.76%   |
| 351-400        | 89       | 4.79%   |
| 701-800        | 64       | 3.45%   |
| 1501-2000      | 51       | 2.75%   |
| 1001-1500      | 49       | 2.64%   |
| 801-900        | 32       | 1.72%   |
| Unknown        | 22       | 1.18%   |
| 901-1000       | 8        | 0.43%   |
| More than 2000 | 3        | 0.16%   |
| 201-300        | 3        | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1316     | 71.99%  |
| 16/10   | 257      | 14.06%  |
| 5/4     | 162      | 8.86%   |
| 21/9    | 39       | 2.13%   |
| 4/3     | 33       | 1.81%   |
| 3/2     | 8        | 0.44%   |
| 6/5     | 5        | 0.27%   |
| 1.00    | 3        | 0.16%   |
| 32/9    | 2        | 0.11%   |
| 3.20    | 1        | 0.05%   |
| 1.96    | 1        | 0.05%   |
| Unknown | 1        | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 680      | 36.38%  |
| 151-200        | 302      | 16.16%  |
| 301-350        | 261      | 13.96%  |
| 141-150        | 180      | 9.63%   |
| 351-500        | 150      | 8.03%   |
| 251-300        | 92       | 4.92%   |
| More than 1000 | 91       | 4.87%   |
| 501-1000       | 51       | 2.73%   |
| 101-110        | 22       | 1.18%   |
| Unknown        | 22       | 1.18%   |
| 111-120        | 7        | 0.37%   |
| 131-140        | 4        | 0.21%   |
| 71-80          | 3        | 0.16%   |
| 81-90          | 2        | 0.11%   |
| 121-130        | 1        | 0.05%   |
| 91-100         | 1        | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1296     | 70.86%  |
| 101-120 | 353      | 19.3%   |
| 1-50    | 85       | 4.65%   |
| 121-160 | 48       | 2.62%   |
| 161-240 | 25       | 1.37%   |
| Unknown | 22       | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1723     | 89.55%  |
| 2     | 150      | 7.8%    |
| 0     | 37       | 1.92%   |
| 3     | 12       | 0.62%   |
| 7     | 1        | 0.05%   |
| 4     | 1        | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1243     | 49.19%  |
| Intel                           | 666      | 26.36%  |
| Qualcomm Atheros                | 160      | 6.33%   |
| Ralink Technology               | 77       | 3.05%   |
| Broadcom                        | 64       | 2.53%   |
| Nvidia                          | 50       | 1.98%   |
| TP-Link                         | 31       | 1.23%   |
| Ralink                          | 31       | 1.23%   |
| Marvell Technology Group        | 20       | 0.79%   |
| Qualcomm Atheros Communications | 17       | 0.67%   |
| Broadcom Limited                | 17       | 0.67%   |
| D-Link System                   | 12       | 0.47%   |
| NetGear                         | 10       | 0.4%    |
| D-Link                          | 10       | 0.4%    |
| VIA Technologies                | 9        | 0.36%   |
| Huawei Technologies             | 9        | 0.36%   |
| Motorola PCS                    | 8        | 0.32%   |
| Samsung Electronics             | 7        | 0.28%   |
| Microsoft                       | 7        | 0.28%   |
| MediaTek                        | 6        | 0.24%   |
| Belkin Components               | 6        | 0.24%   |
| Aquantia                        | 6        | 0.24%   |
| IMC Networks                    | 5        | 0.2%    |
| Edimax Technology               | 5        | 0.2%    |
| ASUSTek Computer                | 5        | 0.2%    |
| ASIX Electronics                | 4        | 0.16%   |
| Xiaomi                          | 3        | 0.12%   |
| AVM                             | 3        | 0.12%   |
| 3Com                            | 3        | 0.12%   |
| ZTE WCDMA Technologies MSM      | 2        | 0.08%   |
| Spreadtrum Communications       | 2        | 0.08%   |
| OnePlus Technology (Shenzhen)   | 2        | 0.08%   |
| Mellanox Technologies           | 2        | 0.08%   |
| JMicron Technology              | 2        | 0.08%   |
| HTC (High Tech Computer)        | 2        | 0.08%   |
| Chu Yuen Enterprise             | 2        | 0.08%   |
| ZyDAS                           | 1        | 0.04%   |
| U.S. Robotics                   | 1        | 0.04%   |
| TRENDnet                        | 1        | 0.04%   |
| T & A Mobile Phones             | 1        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1035     | 37.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 72       | 2.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 64       | 2.3%    |
| Intel Ethernet Connection I217-LM                                 | 62       | 2.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 60       | 2.16%   |
| Intel I211 Gigabit Network Connection                             | 57       | 2.05%   |
| Intel Wi-Fi 6 AX200                                               | 54       | 1.94%   |
| Intel Ethernet Connection (2) I219-V                              | 50       | 1.8%    |
| Intel 82579V Gigabit Network Connection                           | 38       | 1.37%   |
| Intel Ethernet Connection (7) I219-V                              | 35       | 1.26%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 35       | 1.26%   |
| Ralink MT7601U Wireless Adapter                                   | 31       | 1.11%   |
| Nvidia MCP61 Ethernet                                             | 31       | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 29       | 1.04%   |
| Intel Ethernet Controller I225-V                                  | 29       | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 27       | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25       | 0.9%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 23       | 0.83%   |
| Intel Ethernet Connection I217-V                                  | 20       | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 18       | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17       | 0.61%   |
| Intel Wireless-AC 9260                                            | 16       | 0.57%   |
| Intel Wireless 3165                                               | 16       | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 15       | 0.54%   |
| Ralink RT5370 Wireless Adapter                                    | 14       | 0.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 14       | 0.5%    |
| Intel Wireless 7260                                               | 13       | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 13       | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 13       | 0.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13       | 0.47%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 12       | 0.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 12       | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                   | 12       | 0.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 12       | 0.43%   |
| Intel Wireless 7265                                               | 12       | 0.43%   |
| Intel 82578DM Gigabit Network Connection                          | 12       | 0.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 11       | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 11       | 0.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 11       | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 11       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 202      | 29.15%  |
| Realtek Semiconductor                 | 169      | 24.39%  |
| Qualcomm Atheros                      | 86       | 12.41%  |
| Ralink Technology                     | 77       | 11.11%  |
| Ralink                                | 31       | 4.47%   |
| TP-Link                               | 30       | 4.33%   |
| Qualcomm Atheros Communications       | 17       | 2.45%   |
| NetGear                               | 10       | 1.44%   |
| D-Link                                | 10       | 1.44%   |
| Broadcom                              | 9        | 1.3%    |
| Microsoft                             | 7        | 1.01%   |
| Belkin Components                     | 6        | 0.87%   |
| MediaTek                              | 5        | 0.72%   |
| IMC Networks                          | 5        | 0.72%   |
| Edimax Technology                     | 5        | 0.72%   |
| D-Link System                         | 5        | 0.72%   |
| ASUSTek Computer                      | 5        | 0.72%   |
| AVM                                   | 3        | 0.43%   |
| Chu Yuen Enterprise                   | 2        | 0.29%   |
| Broadcom Limited                      | 2        | 0.29%   |
| ZyDAS                                 | 1        | 0.14%   |
| TRENDnet                              | 1        | 0.14%   |
| Philips (or NXP)                      | 1        | 0.14%   |
| Logitec                               | 1        | 0.14%   |
| Linksys                               | 1        | 0.14%   |
| Gemtek                                | 1        | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 54       | 7.76%   |
| Ralink MT7601U Wireless Adapter                            | 31       | 4.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 29       | 4.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 27       | 3.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 23       | 3.3%    |
| Intel Wireless-AC 9260                                     | 16       | 2.3%    |
| Intel Wireless 3165                                        | 16       | 2.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 15       | 2.16%   |
| Ralink RT5370 Wireless Adapter                             | 14       | 2.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 14       | 2.01%   |
| Intel Wireless 7260                                        | 13       | 1.87%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 12       | 1.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 12       | 1.72%   |
| Qualcomm Atheros AR9271 802.11n                            | 12       | 1.72%   |
| Intel Wireless 7265                                        | 12       | 1.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 11       | 1.58%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 11       | 1.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 11       | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 11       | 1.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 10       | 1.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 10       | 1.44%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter            | 9        | 1.29%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 9        | 1.29%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 8        | 1.15%   |
| Realtek 802.11ac NIC                                       | 8        | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 7        | 1.01%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                     | 7        | 1.01%   |
| Ralink RT2561/RT61 802.11g PCI                             | 7        | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 7        | 1.01%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 7        | 1.01%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 6        | 0.86%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 6        | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 6        | 0.86%   |
| Microsoft Xbox 360 Wireless Adapter                        | 6        | 0.86%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 6        | 0.86%   |
| Ralink RT5372 Wireless Adapter                             | 5        | 0.72%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                  | 5        | 0.72%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                       | 5        | 0.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 5        | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 5        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1185     | 58.63%  |
| Intel                             | 539      | 26.67%  |
| Qualcomm Atheros                  | 81       | 4.01%   |
| Broadcom                          | 55       | 2.72%   |
| Nvidia                            | 50       | 2.47%   |
| Marvell Technology Group          | 20       | 0.99%   |
| Broadcom Limited                  | 15       | 0.74%   |
| VIA Technologies                  | 9        | 0.45%   |
| Huawei Technologies               | 9        | 0.45%   |
| Samsung Electronics               | 7        | 0.35%   |
| D-Link System                     | 7        | 0.35%   |
| Aquantia                          | 6        | 0.3%    |
| Motorola PCS                      | 4        | 0.2%    |
| ASIX Electronics                  | 4        | 0.2%    |
| Xiaomi                            | 3        | 0.15%   |
| 3Com                              | 3        | 0.15%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.1%    |
| Spreadtrum Communications         | 2        | 0.1%    |
| OnePlus Technology (Shenzhen)     | 2        | 0.1%    |
| Mellanox Technologies             | 2        | 0.1%    |
| JMicron Technology                | 2        | 0.1%    |
| HTC (High Tech Computer)          | 2        | 0.1%    |
| TP-Link                           | 1        | 0.05%   |
| T & A Mobile Phones               | 1        | 0.05%   |
| Sundance Technology Inc / IC Plus | 1        | 0.05%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.05%   |
| Qualcomm                          | 1        | 0.05%   |
| OPPO Electronics                  | 1        | 0.05%   |
| Netchip Technology                | 1        | 0.05%   |
| MediaTek                          | 1        | 0.05%   |
| Emulex                            | 1        | 0.05%   |
| DisplayLink                       | 1        | 0.05%   |
| Davicom Semiconductor             | 1        | 0.05%   |
| Adnaco Technology                 | 1        | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1035     | 49.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 72       | 3.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 64       | 3.08%   |
| Intel Ethernet Connection I217-LM                                 | 62       | 2.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 60       | 2.88%   |
| Intel I211 Gigabit Network Connection                             | 57       | 2.74%   |
| Intel Ethernet Connection (2) I219-V                              | 50       | 2.4%    |
| Intel 82579V Gigabit Network Connection                           | 38       | 1.83%   |
| Intel Ethernet Connection (7) I219-V                              | 35       | 1.68%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 35       | 1.68%   |
| Nvidia MCP61 Ethernet                                             | 31       | 1.49%   |
| Intel Ethernet Controller I225-V                                  | 29       | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25       | 1.2%    |
| Intel Ethernet Connection I217-V                                  | 20       | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                             | 18       | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17       | 0.82%   |
| Intel Ethernet Connection (2) I218-V                              | 13       | 0.62%   |
| Intel 82574L Gigabit Network Connection                           | 13       | 0.62%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13       | 0.62%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 12       | 0.58%   |
| Intel 82578DM Gigabit Network Connection                          | 12       | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 11       | 0.53%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 11       | 0.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11       | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10       | 0.48%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 9        | 0.43%   |
| Intel 82578DC Gigabit Network Connection                          | 9        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 8        | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8        | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8        | 0.38%   |
| Intel Ethernet Connection (14) I219-V                             | 8        | 0.38%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 8        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 7        | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.34%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 6        | 0.29%   |
| Intel Ethernet Connection (2) I218-LM                             | 6        | 0.29%   |
| Intel Ethernet Connection (12) I219-V                             | 6        | 0.29%   |
| Intel Ethernet Connection (11) I219-V                             | 6        | 0.29%   |
| Intel 82567V-2 Gigabit Network Connection                         | 6        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1907     | 73.91%  |
| WiFi     | 667      | 25.85%  |
| Unknown  | 5        | 0.19%   |
| Modem    | 1        | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1621     | 85.68%  |
| WiFi     | 271      | 14.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1361     | 70.74%  |
| 2     | 499      | 25.94%  |
| 3     | 42       | 2.18%   |
| 0     | 17       | 0.88%   |
| 4     | 5        | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1360     | 70.69%  |
| Yes  | 564      | 29.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 184      | 43.09%  |
| Cambridge Silicon Radio         | 119      | 27.87%  |
| Realtek Semiconductor           | 31       | 7.26%   |
| ASUSTek Computer                | 23       | 5.39%   |
| Qualcomm Atheros Communications | 18       | 4.22%   |
| Broadcom                        | 17       | 3.98%   |
| IMC Networks                    | 11       | 2.58%   |
| MediaTek                        | 3        | 0.7%    |
| Lite-On Technology              | 3        | 0.7%    |
| Apple                           | 3        | 0.7%    |
| TP-Link                         | 2        | 0.47%   |
| Integrated System Solution      | 2        | 0.47%   |
| Unknown                         | 2        | 0.47%   |
| Unknown                         | 1        | 0.23%   |
| SIN                             | 1        | 0.23%   |
| Ralink                          | 1        | 0.23%   |
| Primax Electronics              | 1        | 0.23%   |
| Foxconn / Hon Hai               | 1        | 0.23%   |
| Edimax Technology               | 1        | 0.23%   |
| Dynex                           | 1        | 0.23%   |
| Dell                            | 1        | 0.23%   |
| Belkin Components               | 1        | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 119      | 27.87%  |
| Intel Bluetooth wireless interface                    | 51       | 11.94%  |
| Intel AX200 Bluetooth                                 | 51       | 11.94%  |
| Intel Wireless-AC 3168 Bluetooth                      | 24       | 5.62%   |
| Realtek Bluetooth Radio                               | 18       | 4.22%   |
| Intel Bluetooth Device                                | 16       | 3.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 15       | 3.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 12       | 2.81%   |
| Realtek  Bluetooth 4.2 Adapter                        | 11       | 2.58%   |
| Intel AX210 Bluetooth                                 | 11       | 2.58%   |
| IMC Networks Bluetooth Radio                          | 9        | 2.11%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 9        | 2.11%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 9        | 2.11%   |
| Qualcomm Atheros  Bluetooth Device                    | 7        | 1.64%   |
| ASUS ASUS USB-BT500                                   | 7        | 1.64%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 4        | 0.94%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 4        | 0.94%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3        | 0.7%    |
| MediaTek Wireless_Device                              | 3        | 0.7%    |
| TP-Link TPuLink UB500 Adapter                         | 2        | 0.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2        | 0.47%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 2        | 0.47%   |
| Lite-On Bluetooth Device                              | 2        | 0.47%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 2        | 0.47%   |
| ASUS Bluetooth Radio                                  | 2        | 0.47%   |
| ASUS Bluetooth Adapter                                | 2        | 0.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 2        | 0.47%   |
| Unknown                                               | 2        | 0.47%   |
| Unknown Bluetooth Device                              | 1        | 0.23%   |
| SIN Bluetooth Keyboard                                | 1        | 0.23%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 1        | 0.23%   |
| Realtek RTL8821A Bluetooth                            | 1        | 0.23%   |
| Ralink RT3290 Bluetooth                               | 1        | 0.23%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter         | 1        | 0.23%   |
| Lite-On Atheros AR3012 Bluetooth                      | 1        | 0.23%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 0.23%   |
| Integrated System Solution Bluetooth Device           | 1        | 0.23%   |
| IMC Networks Bluetooth Module                         | 1        | 0.23%   |
| IMC Networks Bluetooth Device                         | 1        | 0.23%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1245     | 42.1%   |
| AMD                                          | 777      | 26.28%  |
| Nvidia                                       | 636      | 21.51%  |
| C-Media Electronics                          | 70       | 2.37%   |
| Creative Labs                                | 46       | 1.56%   |
| Logitech                                     | 25       | 0.85%   |
| Texas Instruments                            | 17       | 0.57%   |
| Creative Technology                          | 11       | 0.37%   |
| JMTek                                        | 10       | 0.34%   |
| ASUSTek Computer                             | 10       | 0.34%   |
| VIA Technologies                             | 7        | 0.24%   |
| GN Netcom                                    | 7        | 0.24%   |
| Generalplus Technology                       | 7        | 0.24%   |
| XMOS                                         | 4        | 0.14%   |
| Tenx Technology                              | 4        | 0.14%   |
| Blue Microphones                             | 4        | 0.14%   |
| SteelSeries ApS                              | 3        | 0.1%    |
| Sony                                         | 3        | 0.1%    |
| Razer USA                                    | 3        | 0.1%    |
| Plantronics                                  | 3        | 0.1%    |
| KTMicro                                      | 3        | 0.1%    |
| Kingston Technology                          | 3        | 0.1%    |
| Trust                                        | 2        | 0.07%   |
| Samson Technologies                          | 2        | 0.07%   |
| ROCCAT                                       | 2        | 0.07%   |
| PreSonus Audio Electronics                   | 2        | 0.07%   |
| Hewlett-Packard                              | 2        | 0.07%   |
| GYROCOM C&C                                  | 2        | 0.07%   |
| Giga-Byte Technology                         | 2        | 0.07%   |
| FiiO Electronics Technology                  | 2        | 0.07%   |
| BEHRINGER International                      | 2        | 0.07%   |
| Audient                                      | 2        | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.03%   |
| ZOOM                                         | 1        | 0.03%   |
| Xilinx                                       | 1        | 0.03%   |
| Valve Software                               | 1        | 0.03%   |
| USB MICROPHONE                               | 1        | 0.03%   |
| Unknown                                      | 1        | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.03%   |
| Sonuus Limited                               | 1        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 179      | 5.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 168      | 4.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 157      | 4.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 135      | 3.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 120      | 3.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 115      | 3.32%   |
| AMD FCH Azalia Controller                                                         | 110      | 3.17%   |
| AMD Family 17h/19h HD Audio Controller                                            | 108      | 3.12%   |
| AMD Starship/Matisse HD Audio Controller                                          | 103      | 2.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 96       | 2.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 77       | 2.22%   |
| Intel 200 Series PCH HD Audio                                                     | 75       | 2.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 69       | 1.99%   |
| Intel Cannon Lake PCH cAVS                                                        | 65       | 1.88%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 64       | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 62       | 1.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 59       | 1.7%    |
| Nvidia High Definition Audio Controller                                           | 58       | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 56       | 1.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 55       | 1.59%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 55       | 1.59%   |
| Intel Audio device                                                                | 49       | 1.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 49       | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                                     | 46       | 1.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 42       | 1.21%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 37       | 1.07%   |
| Nvidia MCP61 High Definition Audio                                                | 36       | 1.04%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 33       | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 32       | 0.92%   |
| Nvidia GP106 High Definition Audio Controller                                     | 31       | 0.89%   |
| Nvidia GF119 HDMI Audio Controller                                                | 31       | 0.89%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 27       | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                     | 26       | 0.75%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 25       | 0.72%   |
| Nvidia GP108 High Definition Audio Controller                                     | 24       | 0.69%   |
| AMD Kabini HDMI/DP Audio                                                          | 24       | 0.69%   |
| AMD Trinity HDMI Audio Controller                                                 | 23       | 0.66%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 23       | 0.66%   |
| AMD Navi 10 HDMI Audio                                                            | 22       | 0.63%   |
| Intel Comet Lake PCH-V cAVS                                                       | 21       | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 421      | 18.47%  |
| Kingston            | 408      | 17.9%   |
| Samsung Electronics | 233      | 10.22%  |
| Corsair             | 176      | 7.72%   |
| SK hynix            | 165      | 7.24%   |
| Crucial             | 157      | 6.89%   |
| G.Skill             | 147      | 6.45%   |
| Micron Technology   | 125      | 5.48%   |
| A-DATA Technology   | 50       | 2.19%   |
| Unknown             | 43       | 1.89%   |
| Patriot             | 34       | 1.49%   |
| Ramaxel Technology  | 30       | 1.32%   |
| Nanya Technology    | 28       | 1.23%   |
| Team                | 23       | 1.01%   |
| Elpida              | 20       | 0.88%   |
| Transcend           | 18       | 0.79%   |
| Smart               | 17       | 0.75%   |
| GOODRAM             | 16       | 0.7%    |
| AMD                 | 10       | 0.44%   |
| Silicon Power       | 8        | 0.35%   |
| Unknown (ABCD)      | 7        | 0.31%   |
| PNY                 | 7        | 0.31%   |
| Kingmax             | 7        | 0.31%   |
| GeIL                | 7        | 0.31%   |
| Apacer              | 7        | 0.31%   |
| Unifosa             | 6        | 0.26%   |
| CSX                 | 6        | 0.26%   |
| Qimonda             | 5        | 0.22%   |
| Teikon              | 4        | 0.18%   |
| OM Nanotech         | 4        | 0.18%   |
| Super Talent        | 3        | 0.13%   |
| Ramos Technology    | 3        | 0.13%   |
| Kllisre             | 3        | 0.13%   |
| KLEVV               | 3        | 0.13%   |
| Wilk Elektronik     | 2        | 0.09%   |
| V-GeN               | 2        | 0.09%   |
| Unknown (2C0B)      | 2        | 0.09%   |
| Unknown (0x0DD5)    | 2        | 0.09%   |
| Sesame              | 2        | 0.09%   |
| OCZ                 | 2        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown                                               | 43       | 1.72%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 32       | 1.28%   |
| Unknown RAM Module 2GB DIMM SDRAM                     | 31       | 1.24%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 31       | 1.24%   |
| Unknown RAM Module 2GB DIMM 800MT/s                   | 24       | 0.96%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 19       | 0.76%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s   | 19       | 0.76%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s              | 18       | 0.72%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s | 18       | 0.72%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s | 18       | 0.72%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 17       | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s              | 16       | 0.64%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s   | 16       | 0.64%   |
| Unknown RAM Module 1GB DIMM SDRAM                     | 15       | 0.6%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s  | 15       | 0.6%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s             | 14       | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s             | 14       | 0.56%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3            | 14       | 0.56%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s   | 13       | 0.52%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s   | 13       | 0.52%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s              | 12       | 0.48%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s   | 12       | 0.48%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s   | 12       | 0.48%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s     | 12       | 0.48%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s   | 12       | 0.48%   |
| Unknown RAM Module 2GB DIMM 400MT/s                   | 11       | 0.44%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s              | 11       | 0.44%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s   | 11       | 0.44%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s   | 11       | 0.44%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s | 11       | 0.44%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s  | 10       | 0.4%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s     | 10       | 0.4%    |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 10       | 0.4%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                  | 9        | 0.36%   |
| Unknown RAM Module 4GB DIMM SDRAM                     | 9        | 0.36%   |
| Unknown RAM Module 4GB DIMM 400MT/s                   | 9        | 0.36%   |
| Unknown RAM Module 1GB DIMM 800MT/s                   | 9        | 0.36%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s  | 9        | 0.36%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s   | 9        | 0.36%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s             | 8        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 800      | 40.96%  |
| DDR4    | 665      | 34.05%  |
| Unknown | 160      | 8.19%   |
| DDR2    | 158      | 8.09%   |
| SDRAM   | 131      | 6.71%   |
| DDR     | 27       | 1.38%   |
| LPDDR4  | 8        | 0.41%   |
| DDR5    | 3        | 0.15%   |
| DRAM    | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1790     | 93.82%  |
| SODIMM  | 114      | 5.97%   |
| RIMM    | 2        | 0.1%    |
| FB-DIMM | 2        | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 718      | 33.09%  |
| 4096  | 641      | 29.54%  |
| 2048  | 448      | 20.65%  |
| 16384 | 183      | 8.43%   |
| 1024  | 131      | 6.04%   |
| 32768 | 33       | 1.52%   |
| 512   | 16       | 0.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 484      | 22.15%  |
| 1333    | 333      | 15.24%  |
| 800     | 127      | 5.81%   |
| 3200    | 123      | 5.63%   |
| 2400    | 121      | 5.54%   |
| 3600    | 107      | 4.9%    |
| 2667    | 98       | 4.49%   |
| 2133    | 93       | 4.26%   |
| 667     | 76       | 3.48%   |
| Unknown | 73       | 3.34%   |
| 2666    | 55       | 2.52%   |
| 1867    | 50       | 2.29%   |
| 1866    | 45       | 2.06%   |
| 3400    | 33       | 1.51%   |
| 3000    | 30       | 1.37%   |
| 1066    | 27       | 1.24%   |
| 400     | 22       | 1.01%   |
| 1800    | 21       | 0.96%   |
| 533     | 21       | 0.96%   |
| 2933    | 19       | 0.87%   |
| 1067    | 19       | 0.87%   |
| 3866    | 16       | 0.73%   |
| 3466    | 13       | 0.59%   |
| 2048    | 12       | 0.55%   |
| 3733    | 11       | 0.5%    |
| 2800    | 11       | 0.5%    |
| 1334    | 11       | 0.5%    |
| 49926   | 8        | 0.37%   |
| 3066    | 8        | 0.37%   |
| 3266    | 7        | 0.32%   |
| 2000    | 7        | 0.32%   |
| 333     | 7        | 0.32%   |
| 3800    | 6        | 0.27%   |
| 1648    | 6        | 0.27%   |
| 1639    | 6        | 0.27%   |
| 3666    | 5        | 0.23%   |
| 3334    | 4        | 0.18%   |
| 3007    | 4        | 0.18%   |
| 2465    | 4        | 0.18%   |
| 41632   | 3        | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 48       | 39.34%  |
| Brother Industries    | 28       | 22.95%  |
| Canon                 | 16       | 13.11%  |
| Samsung Electronics   | 11       | 9.02%   |
| Seiko Epson           | 7        | 5.74%   |
| Lexmark International | 4        | 3.28%   |
| Xerox                 | 2        | 1.64%   |
| Kyocera               | 2        | 1.64%   |
| Ricoh                 | 1        | 0.82%   |
| QinHeng Electronics   | 1        | 0.82%   |
| NXP Semiconductors    | 1        | 0.82%   |
| Citizen               | 1        | 0.82%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| HP LaserJet 1010                             | 3        | 2.46%   |
| Seiko Epson ET-4760 Series                   | 2        | 1.64%   |
| Samsung SCX-3400 Series                      | 2        | 1.64%   |
| Samsung M2070 Series                         | 2        | 1.64%   |
| Samsung M2020 Series                         | 2        | 1.64%   |
| Samsung CLP-310 Color Laser Printer          | 2        | 1.64%   |
| HP LaserJet P1005                            | 2        | 1.64%   |
| HP LaserJet 1020                             | 2        | 1.64%   |
| HP Ink Tank Wireless 410 series              | 2        | 1.64%   |
| HP ENVY 4520 series                          | 2        | 1.64%   |
| HP ENVY 4500 series                          | 2        | 1.64%   |
| HP DeskJet 2700 series                       | 2        | 1.64%   |
| HP Deskjet 1050 J410                         | 2        | 1.64%   |
| Canon TS5100 series                          | 2        | 1.64%   |
| Brother MFC-L2710DW series                   | 2        | 1.64%   |
| Brother MFC-J470DW                           | 2        | 1.64%   |
| Brother DCP-T310                             | 2        | 1.64%   |
| Xerox Phaser 6510                            | 1        | 0.82%   |
| Xerox Phaser 6010N                           | 1        | 0.82%   |
| Seiko Epson XP-2100 Series                   | 1        | 0.82%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.82%   |
| Seiko Epson L365 Series                      | 1        | 0.82%   |
| Seiko Epson L120 Series                      | 1        | 0.82%   |
| Seiko Epson ET-3750 Series                   | 1        | 0.82%   |
| Samsung ML-2850 Series                       | 1        | 0.82%   |
| Samsung ML-1640 Series Laser Printer         | 1        | 0.82%   |
| Samsung M267x 287x Series                    | 1        | 0.82%   |
| Ricoh SP 211                                 | 1        | 0.82%   |
| QinHeng CH340S                               | 1        | 0.82%   |
| NXP Semiconductors Printer-80                | 1        | 0.82%   |
| Lexmark International X364dn                 | 1        | 0.82%   |
| Lexmark International MS710                  | 1        | 0.82%   |
| Lexmark International CX410de                | 1        | 0.82%   |
| Lexmark International B2236dw                | 1        | 0.82%   |
| Kyocera ECOSYS P5021cdw                      | 1        | 0.82%   |
| Kyocera ECOSYS P2040dw                       | 1        | 0.82%   |
| HP PSC 1400                                  | 1        | 0.82%   |
| HP PhotoSmart P1000                          | 1        | 0.82%   |
| HP Officejet Pro 8100                        | 1        | 0.82%   |
| HP OfficeJet Pro 7740 series                 | 1        | 0.82%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 13       | 72.22%  |
| Seiko Epson     | 2        | 11.11%  |
| Mustek Systems  | 2        | 11.11%  |
| Hewlett-Packard | 1        | 5.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 2        | 11.11%  |
| Canon CanoScan N670U/N676U/LiDE 20            | 2        | 11.11%  |
| Canon CanoScan N1240U/LiDE 30                 | 2        | 11.11%  |
| Canon CanoScan LiDE 120                       | 2        | 11.11%  |
| Canon CanoScan LiDE 110                       | 2        | 11.11%  |
| Canon CanoScan LiDE 100                       | 2        | 11.11%  |
| Mustek Systems SNAPSCAN e22                   | 1        | 5.56%   |
| Mustek Systems ScanExpress 1200 CU            | 1        | 5.56%   |
| HP ScanJet 2400c                              | 1        | 5.56%   |
| Canon CanoScan LIDE 25                        | 1        | 5.56%   |
| Canon CanoScan LiDE 210                       | 1        | 5.56%   |
| Canon CanoScan 5200F                          | 1        | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 101      | 41.06%  |
| Microsoft                     | 16       | 6.5%    |
| Microdia                      | 15       | 6.1%    |
| Generalplus Technology        | 8        | 3.25%   |
| Realtek Semiconductor         | 7        | 2.85%   |
| Z-Star Microelectronics       | 6        | 2.44%   |
| KYE Systems (Mouse Systems)   | 6        | 2.44%   |
| Chicony Electronics           | 6        | 2.44%   |
| Sunplus Innovation Technology | 5        | 2.03%   |
| Samsung Electronics           | 5        | 2.03%   |
| Hewlett-Packard               | 5        | 2.03%   |
| Aveo Technology               | 5        | 2.03%   |
| Apple                         | 5        | 2.03%   |
| Trust                         | 4        | 1.63%   |
| Cubeternet                    | 4        | 1.63%   |
| ARC International             | 4        | 1.63%   |
| Unknown                       | 3        | 1.22%   |
| Jieli Technology              | 3        | 1.22%   |
| Creative Technology           | 3        | 1.22%   |
| Pixart Imaging                | 2        | 0.81%   |
| MacroSilicon                  | 2        | 0.81%   |
| IMC Networks                  | 2        | 0.81%   |
| Genesys Logic                 | 2        | 0.81%   |
| GEMBIRD                       | 2        | 0.81%   |
| AVerMedia Technologies        | 2        | 0.81%   |
| 2M UVC CAMERA                 | 2        | 0.81%   |
| WCM_USB                       | 1        | 0.41%   |
| Valve Software                | 1        | 0.41%   |
| USB3.0 HD Audio Capture       | 1        | 0.41%   |
| SunplusIT                     | 1        | 0.41%   |
| Sonix Technology              | 1        | 0.41%   |
| Silicon Motion                | 1        | 0.41%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 0.41%   |
| Razer USA                     | 1        | 0.41%   |
| OPPO Electronics              | 1        | 0.41%   |
| Novatek Microelectronics      | 1        | 0.41%   |
| Huawei Technologies           | 1        | 0.41%   |
| Guillemot                     | 1        | 0.41%   |
| eMeet-200611                  | 1        | 0.41%   |
| EC2U200                       | 1        | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 26       | 10.48%  |
| Logitech HD Pro Webcam C920           | 12       | 4.84%   |
| Logitech HD Webcam C525               | 11       | 4.44%   |
| Microsoft LifeCam HD-3000             | 9        | 3.63%   |
| Generalplus GENERAL WEBCAM            | 8        | 3.23%   |
| Logitech Webcam C170                  | 7        | 2.82%   |
| Logitech HD Webcam C615               | 7        | 2.82%   |
| Samsung Galaxy A5 (MTP)               | 5        | 2.02%   |
| Microdia USB 2.0 Camera               | 5        | 2.02%   |
| Logitech Webcam C310                  | 5        | 2.02%   |
| Apple iPhone 5/5C/5S/6/SE             | 5        | 2.02%   |
| Aveo USB2.0 Camera                    | 4        | 1.61%   |
| ARC International Camera              | 4        | 1.61%   |
| Unknown HD camera                     | 3        | 1.21%   |
| Microdia Webcam Vitade AF             | 3        | 1.21%   |
| Microdia Camera                       | 3        | 1.21%   |
| Logitech Webcam Pro 9000              | 3        | 1.21%   |
| Logitech C922 Pro Stream Webcam       | 3        | 1.21%   |
| Jieli USB PHY 2.0                     | 3        | 1.21%   |
| HP Webcam HD 2300                     | 3        | 1.21%   |
| Cubeternet USB2.0 Camera              | 3        | 1.21%   |
| Z-Star A4 TECH USB2.0 PC Camera J     | 2        | 0.81%   |
| Trust WB-6250X Webcam                 | 2        | 0.81%   |
| Sunplus HD 720P webcam                | 2        | 0.81%   |
| Sunplus Full HD webcam                | 2        | 0.81%   |
| Realtek USB Camera                    | 2        | 0.81%   |
| Realtek Realtek USB MIC               | 2        | 0.81%   |
| Realtek NexiGo N660P FHD Webcam       | 2        | 0.81%   |
| Realtek Full HD Webcam                | 2        | 0.81%   |
| Microsoft LifeCam Cinema              | 2        | 0.81%   |
| Microdia Laptop_Integrated_Webcam_FHD | 2        | 0.81%   |
| MacroSilicon USB Video                | 2        | 0.81%   |
| Logitech Webcam C930e                 | 2        | 0.81%   |
| Logitech Webcam C925e                 | 2        | 0.81%   |
| Logitech Webcam C250                  | 2        | 0.81%   |
| Logitech Webcam C110                  | 2        | 0.81%   |
| Logitech QuickCam Pro 9000            | 2        | 0.81%   |
| Logitech HD Webcam C910               | 2        | 0.81%   |
| Logitech HD Webcam C510               | 2        | 0.81%   |
| Logitech BRIO Ultra HD Webcam         | 2        | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Upek                  | 1        | 50%     |
| LighTuning Technology | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 50%     |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 28.57%  |
| Gemalto (was Gemplus) | 2        | 28.57%  |
| SCM Microsystems      | 1        | 14.29%  |
| Cherry                | 1        | 14.29%  |
| BIT4ID                | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 2        | 28.57%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 2        | 28.57%  |
| SCM Microsystems CLOUD 2700 F Smart Card Reader   | 1        | 14.29%  |
| Cherry Smart Terminal XX44                        | 1        | 14.29%  |
| BIT4ID miniLector EVO                             | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1741     | 90.44%  |
| 1     | 172      | 8.94%   |
| 2     | 9        | 0.47%   |
| 7     | 1        | 0.05%   |
| 4     | 1        | 0.05%   |
| 3     | 1        | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 91       | 47.64%  |
| Net/wireless             | 37       | 19.37%  |
| Unassigned class         | 13       | 6.81%   |
| Communication controller | 13       | 6.81%   |
| Multimedia controller    | 8        | 4.19%   |
| Bluetooth                | 7        | 3.66%   |
| Chipcard                 | 6        | 3.14%   |
| Wireless                 | 3        | 1.57%   |
| Network                  | 3        | 1.57%   |
| Camera                   | 3        | 1.57%   |
| Net/ethernet             | 2        | 1.05%   |
| Fingerprint reader       | 2        | 1.05%   |
| Card reader              | 2        | 1.05%   |
| Storage/raid             | 1        | 0.52%   |

