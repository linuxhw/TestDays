Zorin 16 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | H110M-H-CF                  | [4754d83d04](https://linux-hardware.org/?probe=4754d83d04) | Jan 01, 2022 |
| Acer          | Aspire M3970                | [e10ce7d132](https://linux-hardware.org/?probe=e10ce7d132) | Dec 31, 2021 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [5b97adba13](https://linux-hardware.org/?probe=5b97adba13) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [8cd5d79924](https://linux-hardware.org/?probe=8cd5d79924) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [9ebfb53472](https://linux-hardware.org/?probe=9ebfb53472) | Dec 31, 2021 |
| HP            | 1998                        | [07bdd01c09](https://linux-hardware.org/?probe=07bdd01c09) | Dec 31, 2021 |
| Dell          | 088DT1 A01                  | [2599126547](https://linux-hardware.org/?probe=2599126547) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | [1c32c6a027](https://linux-hardware.org/?probe=1c32c6a027) | Dec 30, 2021 |
| MSI           | H81M-P33                    | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| ASRock        | Z87 Pro4                    | [2a8588f61e](https://linux-hardware.org/?probe=2a8588f61e) | Dec 29, 2021 |
| Gigabyte      | Z97-HD3                     | [5536599b58](https://linux-hardware.org/?probe=5536599b58) | Dec 28, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [127916f66f](https://linux-hardware.org/?probe=127916f66f) | Dec 28, 2021 |
| ASUSTek       | H81-PLUS                    | [60ba71333c](https://linux-hardware.org/?probe=60ba71333c) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | [cb83ad3d6c](https://linux-hardware.org/?probe=cb83ad3d6c) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | [76e7cab82a](https://linux-hardware.org/?probe=76e7cab82a) | Dec 26, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [39f562f189](https://linux-hardware.org/?probe=39f562f189) | Dec 25, 2021 |
| Dell          | 0VNP2H A00                  | [e64f51e52a](https://linux-hardware.org/?probe=e64f51e52a) | Dec 24, 2021 |
| Gigabyte      | H57M-USB3                   | [ee70d6b4b4](https://linux-hardware.org/?probe=ee70d6b4b4) | Dec 24, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [5c4ae9536f](https://linux-hardware.org/?probe=5c4ae9536f) | Dec 24, 2021 |
| Gigabyte      | EG41MFT-US2H                | [2bfb4702c3](https://linux-hardware.org/?probe=2bfb4702c3) | Dec 23, 2021 |
| Gigabyte      | EG41MFT-US2H                | [b29d64341c](https://linux-hardware.org/?probe=b29d64341c) | Dec 23, 2021 |
| ASUSTek       | TUF GAMING X570-PRO WIFI... | [69d74c89b4](https://linux-hardware.org/?probe=69d74c89b4) | Dec 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4453e33b88](https://linux-hardware.org/?probe=4453e33b88) | Dec 22, 2021 |
| ASRock        | B450 Pro4                   | [0832f6d0fd](https://linux-hardware.org/?probe=0832f6d0fd) | Dec 22, 2021 |
| ASUSTek       | P8Z77-M                     | [667e676c78](https://linux-hardware.org/?probe=667e676c78) | Dec 21, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [200701934f](https://linux-hardware.org/?probe=200701934f) | Dec 21, 2021 |
| ASRock        | A320M-DVS R4.0              | [c38dcdb848](https://linux-hardware.org/?probe=c38dcdb848) | Dec 21, 2021 |
| Dell          | 03NVJ6 A02                  | [685819bc74](https://linux-hardware.org/?probe=685819bc74) | Dec 20, 2021 |
| ASRock        | B450M-HDV R4.0              | [210f1589c4](https://linux-hardware.org/?probe=210f1589c4) | Dec 20, 2021 |
| ASRock        | B450M Pro4                  | [b40c57df26](https://linux-hardware.org/?probe=b40c57df26) | Dec 20, 2021 |
| ASUSTek       | PRIME B350M-A               | [09d76b803c](https://linux-hardware.org/?probe=09d76b803c) | Dec 20, 2021 |
| Intel         | B75                         | [9178fa9053](https://linux-hardware.org/?probe=9178fa9053) | Dec 19, 2021 |
| ASRock        | B450M-HDV R4.0              | [35182a65bb](https://linux-hardware.org/?probe=35182a65bb) | Dec 19, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [717b852409](https://linux-hardware.org/?probe=717b852409) | Dec 19, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [38a4bbf8d3](https://linux-hardware.org/?probe=38a4bbf8d3) | Dec 19, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f86ed2049c](https://linux-hardware.org/?probe=f86ed2049c) | Dec 19, 2021 |
| Dell          | 0HY9JP A02                  | [063c3ec5d2](https://linux-hardware.org/?probe=063c3ec5d2) | Dec 19, 2021 |
| ASUSTek       | P5Q PRO TURBO               | [4c845a464c](https://linux-hardware.org/?probe=4c845a464c) | Dec 19, 2021 |
| Acer          | Aspire XC-330               | [1803a4622c](https://linux-hardware.org/?probe=1803a4622c) | Dec 19, 2021 |
| ASUSTek       | Benicia                     | [e572d5ceff](https://linux-hardware.org/?probe=e572d5ceff) | Dec 19, 2021 |
| Shuttle       | FH61V                       | [39d341d8be](https://linux-hardware.org/?probe=39d341d8be) | Dec 19, 2021 |
| MSI           | MS-7053                     | [3e9330e811](https://linux-hardware.org/?probe=3e9330e811) | Dec 18, 2021 |
| MSI           | MS-7053                     | [b32db3cd18](https://linux-hardware.org/?probe=b32db3cd18) | Dec 18, 2021 |
| Unknown       | C51GM-M                     | [91386c4f7c](https://linux-hardware.org/?probe=91386c4f7c) | Dec 17, 2021 |
| Lenovo        | ThinkCentre M57e 9489W1U    | [ba5156ef68](https://linux-hardware.org/?probe=ba5156ef68) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | [49e9492dd4](https://linux-hardware.org/?probe=49e9492dd4) | Dec 17, 2021 |
| Dell          | 0Y2K8N A01                  | [2e29930670](https://linux-hardware.org/?probe=2e29930670) | Dec 17, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [dfbadf6708](https://linux-hardware.org/?probe=dfbadf6708) | Dec 17, 2021 |
| Intel         | B75                         | [95258dab55](https://linux-hardware.org/?probe=95258dab55) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | [cd4d96fefa](https://linux-hardware.org/?probe=cd4d96fefa) | Dec 17, 2021 |
| Acer          | Aspire XC-330               | [61dd8de51b](https://linux-hardware.org/?probe=61dd8de51b) | Dec 16, 2021 |
| Dell          | 0D24M8 A01                  | [a306863279](https://linux-hardware.org/?probe=a306863279) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| HP            | 18E5                        | [88f87a7a1b](https://linux-hardware.org/?probe=88f87a7a1b) | Dec 14, 2021 |
| ASUSTek       | AM1M-A                      | [5113655631](https://linux-hardware.org/?probe=5113655631) | Dec 14, 2021 |
| ASUSTek       | VM40B                       | [c53952beab](https://linux-hardware.org/?probe=c53952beab) | Dec 14, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [788c6b0550](https://linux-hardware.org/?probe=788c6b0550) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [b471a79340](https://linux-hardware.org/?probe=b471a79340) | Dec 13, 2021 |
| Dell          | 0M5DCD A00                  | [447bffefc3](https://linux-hardware.org/?probe=447bffefc3) | Dec 13, 2021 |
| Intel         | DQ87PG AAG74154-403         | [e2a6d57861](https://linux-hardware.org/?probe=e2a6d57861) | Dec 13, 2021 |
| Intel         | B75                         | [652828f7b9](https://linux-hardware.org/?probe=652828f7b9) | Dec 13, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [6b33adaacf](https://linux-hardware.org/?probe=6b33adaacf) | Dec 13, 2021 |
| ASUSTek       | PRIME B350M-A               | [aa92a82326](https://linux-hardware.org/?probe=aa92a82326) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [8e659f2b89](https://linux-hardware.org/?probe=8e659f2b89) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-K               | [abb6a94373](https://linux-hardware.org/?probe=abb6a94373) | Dec 12, 2021 |
| Gigabyte      | H97M-D3H                    | [d9e04ee743](https://linux-hardware.org/?probe=d9e04ee743) | Dec 12, 2021 |
| Gigabyte      | H97M-D3H                    | [1d768c3c63](https://linux-hardware.org/?probe=1d768c3c63) | Dec 12, 2021 |
| ASRock        | B450M Pro4                  | [6a8480268d](https://linux-hardware.org/?probe=6a8480268d) | Dec 12, 2021 |
| Dell          | 02YYK5 A01                  | [1301218290](https://linux-hardware.org/?probe=1301218290) | Dec 11, 2021 |
| HP            | 339A                        | [7081fc45a3](https://linux-hardware.org/?probe=7081fc45a3) | Dec 11, 2021 |
| HP            | 304Ah                       | [6d87535158](https://linux-hardware.org/?probe=6d87535158) | Dec 10, 2021 |
| eMachines     | EL1850G                     | [ccd7758cbe](https://linux-hardware.org/?probe=ccd7758cbe) | Dec 10, 2021 |
| ASUSTek       | NARRA3                      | [028ad01454](https://linux-hardware.org/?probe=028ad01454) | Dec 09, 2021 |
| Biostar       | A320MH                      | [fbbe7a436a](https://linux-hardware.org/?probe=fbbe7a436a) | Dec 09, 2021 |
| Biostar       | A320MH                      | [3870a17dfe](https://linux-hardware.org/?probe=3870a17dfe) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | [0e19f8e2ae](https://linux-hardware.org/?probe=0e19f8e2ae) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | [a37d2cc42f](https://linux-hardware.org/?probe=a37d2cc42f) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | [1a5b0a8d39](https://linux-hardware.org/?probe=1a5b0a8d39) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | [f4d8f580dc](https://linux-hardware.org/?probe=f4d8f580dc) | Dec 09, 2021 |
| ASUSTek       | NARRA3                      | [c64aed90a9](https://linux-hardware.org/?probe=c64aed90a9) | Dec 08, 2021 |
| ASUSTek       | M3A78-EM                    | [b041919f38](https://linux-hardware.org/?probe=b041919f38) | Dec 08, 2021 |
| HP            | 87C3                        | [16cc7e0bcb](https://linux-hardware.org/?probe=16cc7e0bcb) | Dec 07, 2021 |
| HP            | 339A                        | [50c24f7d34](https://linux-hardware.org/?probe=50c24f7d34) | Dec 07, 2021 |
| HP            | 81B4 01                     | [1477bd5a44](https://linux-hardware.org/?probe=1477bd5a44) | Dec 07, 2021 |
| Dell          | 0T656F A01                  | [552210319c](https://linux-hardware.org/?probe=552210319c) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [2ce114a1c7](https://linux-hardware.org/?probe=2ce114a1c7) | Dec 06, 2021 |
| ASRock        | M3A770DE                    | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [ce3d88a2a2](https://linux-hardware.org/?probe=ce3d88a2a2) | Dec 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [49fe509dd2](https://linux-hardware.org/?probe=49fe509dd2) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [e6b7b57ea7](https://linux-hardware.org/?probe=e6b7b57ea7) | Dec 04, 2021 |
| Dell          | 0G254H A00                  | [11897b38da](https://linux-hardware.org/?probe=11897b38da) | Dec 03, 2021 |
| HP            | 2B44                        | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [e39465a63b](https://linux-hardware.org/?probe=e39465a63b) | Dec 03, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [ad90caf60d](https://linux-hardware.org/?probe=ad90caf60d) | Dec 03, 2021 |
| Pegatron      | JESSE                       | [9091bacc33](https://linux-hardware.org/?probe=9091bacc33) | Dec 03, 2021 |
| ASUSTek       | LEONITE                     | [704345be69](https://linux-hardware.org/?probe=704345be69) | Dec 03, 2021 |
| Biostar       | A780L3C                     | [a50e3d0532](https://linux-hardware.org/?probe=a50e3d0532) | Dec 02, 2021 |
| Foxconn       | 2A8C                        | [8d24862bd6](https://linux-hardware.org/?probe=8d24862bd6) | Dec 02, 2021 |
| Biostar       | A780L3C                     | [497f29a343](https://linux-hardware.org/?probe=497f29a343) | Dec 02, 2021 |
| Dell          | 0WR7PY A02                  | [1255f30eea](https://linux-hardware.org/?probe=1255f30eea) | Dec 01, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [bd33efb6f7](https://linux-hardware.org/?probe=bd33efb6f7) | Dec 01, 2021 |
| HP            | 339A                        | [4a377796cf](https://linux-hardware.org/?probe=4a377796cf) | Dec 01, 2021 |
| Dell          | 0PU052                      | [a943d9f217](https://linux-hardware.org/?probe=a943d9f217) | Dec 01, 2021 |
| Dell          | 0WR7PY A02                  | [d51c794107](https://linux-hardware.org/?probe=d51c794107) | Nov 30, 2021 |
| Dell          | 0WMJ54 A01                  | [5fa96d5863](https://linux-hardware.org/?probe=5fa96d5863) | Nov 30, 2021 |
| HP            | 8299                        | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| Medion        | MS-7707                     | [3d0a46f2ef](https://linux-hardware.org/?probe=3d0a46f2ef) | Nov 30, 2021 |
| ASRock        | H67DE3                      | [d710784470](https://linux-hardware.org/?probe=d710784470) | Nov 30, 2021 |
| HP            | 8299                        | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [24b15affa6](https://linux-hardware.org/?probe=24b15affa6) | Nov 29, 2021 |
| ASUSTek       | P8Z77-V LX                  | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| ECS           | GeForce6100PM-M2            | [032a2baaca](https://linux-hardware.org/?probe=032a2baaca) | Nov 28, 2021 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | [382bfc4a86](https://linux-hardware.org/?probe=382bfc4a86) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [cd296f933b](https://linux-hardware.org/?probe=cd296f933b) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [44c0cf428f](https://linux-hardware.org/?probe=44c0cf428f) | Nov 28, 2021 |
| MSI           | X370 GAMING PLUS            | [0b71d2652d](https://linux-hardware.org/?probe=0b71d2652d) | Nov 27, 2021 |
| Dell          | 0VNP2H A00                  | [803e55fd86](https://linux-hardware.org/?probe=803e55fd86) | Nov 27, 2021 |
| ASUSTek       | M4A78T-E                    | [df3010e1b8](https://linux-hardware.org/?probe=df3010e1b8) | Nov 27, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [ae57475767](https://linux-hardware.org/?probe=ae57475767) | Nov 27, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [3925ce16ae](https://linux-hardware.org/?probe=3925ce16ae) | Nov 27, 2021 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | [cd58d98b6a](https://linux-hardware.org/?probe=cd58d98b6a) | Nov 27, 2021 |
| ASRock        | B450M Pro4                  | [bb642022a6](https://linux-hardware.org/?probe=bb642022a6) | Nov 27, 2021 |
| ASRock        | ALiveNF6G-DVI               | [2761f434e8](https://linux-hardware.org/?probe=2761f434e8) | Nov 26, 2021 |
| Dell          | 0VNP2H A00                  | [fe9de9a896](https://linux-hardware.org/?probe=fe9de9a896) | Nov 25, 2021 |
| HP            | 18E7                        | [7385ca30d4](https://linux-hardware.org/?probe=7385ca30d4) | Nov 23, 2021 |
| Pegatron      | 2A86E01                     | [b57d9ec4a4](https://linux-hardware.org/?probe=b57d9ec4a4) | Nov 23, 2021 |
| Gigabyte      | H61N-USB3                   | [83e388363c](https://linux-hardware.org/?probe=83e388363c) | Nov 23, 2021 |
| Dell          | 0PU052                      | [a41541bab5](https://linux-hardware.org/?probe=a41541bab5) | Nov 23, 2021 |
| Gigabyte      | G41MT-S2                    | [8031417427](https://linux-hardware.org/?probe=8031417427) | Nov 23, 2021 |
| Intel         | DB65AL AAG12530-309         | [44c8025eee](https://linux-hardware.org/?probe=44c8025eee) | Nov 23, 2021 |
| MSI           | B360M PRO-VD                | [e1f68c6698](https://linux-hardware.org/?probe=e1f68c6698) | Nov 22, 2021 |
| Gigabyte      | H77M-D3H                    | [2819a870a8](https://linux-hardware.org/?probe=2819a870a8) | Nov 22, 2021 |
| HP            | 0AA4h                       | [22c6e4fffd](https://linux-hardware.org/?probe=22c6e4fffd) | Nov 22, 2021 |
| ASRock        | P67 Extreme6                | [54cd91039c](https://linux-hardware.org/?probe=54cd91039c) | Nov 22, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [fa922e6e20](https://linux-hardware.org/?probe=fa922e6e20) | Nov 22, 2021 |
| ASRock        | 775i945GZ                   | [8d3cfee95d](https://linux-hardware.org/?probe=8d3cfee95d) | Nov 22, 2021 |
| ASRock        | ALiveNF6G-DVI               | [23a839f917](https://linux-hardware.org/?probe=23a839f917) | Nov 21, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [ae91e01910](https://linux-hardware.org/?probe=ae91e01910) | Nov 21, 2021 |
| Dell          | 03NVJ6 A02                  | [00a8a0ab87](https://linux-hardware.org/?probe=00a8a0ab87) | Nov 21, 2021 |
| Gigabyte      | B450M GAMING                | [2355c29da1](https://linux-hardware.org/?probe=2355c29da1) | Nov 21, 2021 |
| Gigabyte      | H55M-UD2H                   | [16e0d2d71a](https://linux-hardware.org/?probe=16e0d2d71a) | Nov 21, 2021 |
| Dell          | 0KWVT8 A00                  | [a6f003d198](https://linux-hardware.org/?probe=a6f003d198) | Nov 20, 2021 |
| LattePanda    | Alpha                       | [24c2fc6f7b](https://linux-hardware.org/?probe=24c2fc6f7b) | Nov 20, 2021 |
| LattePanda    | Alpha                       | [4aa879f7ac](https://linux-hardware.org/?probe=4aa879f7ac) | Nov 20, 2021 |
| ASRock        | B450M Pro4 R2.0             | [8a53d67102](https://linux-hardware.org/?probe=8a53d67102) | Nov 19, 2021 |
| MSI           | 970 GAMING                  | [ac8f38525e](https://linux-hardware.org/?probe=ac8f38525e) | Nov 19, 2021 |
| ASUSTek       | P8Z77-V LX                  | [6807e3fa8c](https://linux-hardware.org/?probe=6807e3fa8c) | Nov 18, 2021 |
| Dell          | 0KWVT8 A00                  | [93b90c3da4](https://linux-hardware.org/?probe=93b90c3da4) | Nov 18, 2021 |
| ASRock        | G31M-VS2                    | [8bc6042d3f](https://linux-hardware.org/?probe=8bc6042d3f) | Nov 17, 2021 |
| ASRock        | X370M-HDV                   | [a991fee412](https://linux-hardware.org/?probe=a991fee412) | Nov 17, 2021 |
| Dell          | 0GXM1W A01                  | [7e9f638277](https://linux-hardware.org/?probe=7e9f638277) | Nov 17, 2021 |
| ASUSTek       | P5KPL-AM                    | [0cae2ebf49](https://linux-hardware.org/?probe=0cae2ebf49) | Nov 16, 2021 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [bb50b7d97c](https://linux-hardware.org/?probe=bb50b7d97c) | Nov 16, 2021 |
| MSI           | 2A9C                        | [80ef0caf18](https://linux-hardware.org/?probe=80ef0caf18) | Nov 15, 2021 |
| MSI           | 2A9C                        | [44e1dcea05](https://linux-hardware.org/?probe=44e1dcea05) | Nov 15, 2021 |
| Gigabyte      | H170-D3HP-CF                | [e90a1881c7](https://linux-hardware.org/?probe=e90a1881c7) | Nov 14, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [a92c32b60a](https://linux-hardware.org/?probe=a92c32b60a) | Nov 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [542b1538bf](https://linux-hardware.org/?probe=542b1538bf) | Nov 14, 2021 |
| HP            | 8653 A                      | [88b53507c9](https://linux-hardware.org/?probe=88b53507c9) | Nov 13, 2021 |
| HP            | 3048h                       | [200317605d](https://linux-hardware.org/?probe=200317605d) | Nov 13, 2021 |
| Dell          | 0GXM1W A02                  | [d446993ec9](https://linux-hardware.org/?probe=d446993ec9) | Nov 13, 2021 |
| ASUSTek       | P5G41T-M LX3                | [8977322809](https://linux-hardware.org/?probe=8977322809) | Nov 13, 2021 |
| HP            | 1790                        | [e86cdf904a](https://linux-hardware.org/?probe=e86cdf904a) | Nov 12, 2021 |
| ASUSTek       | M5A78L LE                   | [d342b54224](https://linux-hardware.org/?probe=d342b54224) | Nov 12, 2021 |
| HP            | 339A                        | [6dc037bf1f](https://linux-hardware.org/?probe=6dc037bf1f) | Nov 11, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [d0eae9ef10](https://linux-hardware.org/?probe=d0eae9ef10) | Nov 11, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [7a2464824d](https://linux-hardware.org/?probe=7a2464824d) | Nov 11, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [c8e4265515](https://linux-hardware.org/?probe=c8e4265515) | Nov 11, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [eece1d5528](https://linux-hardware.org/?probe=eece1d5528) | Nov 11, 2021 |
| ASUSTek       | H81M-P PLUS                 | [1841ab2aff](https://linux-hardware.org/?probe=1841ab2aff) | Nov 10, 2021 |
| ASUSTek       | A68HM-PLUS                  | [0e688f660f](https://linux-hardware.org/?probe=0e688f660f) | Nov 10, 2021 |
| ASUSTek       | M5A97                       | [20a705fd56](https://linux-hardware.org/?probe=20a705fd56) | Nov 10, 2021 |
| HP            | 8653 A                      | [f84c67582a](https://linux-hardware.org/?probe=f84c67582a) | Nov 09, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [e7579f2fcf](https://linux-hardware.org/?probe=e7579f2fcf) | Nov 09, 2021 |
| HP            | 1790                        | [6030cabe49](https://linux-hardware.org/?probe=6030cabe49) | Nov 09, 2021 |
| HP            | 1825                        | [7cf6c3590a](https://linux-hardware.org/?probe=7cf6c3590a) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | [d4c15ae33a](https://linux-hardware.org/?probe=d4c15ae33a) | Nov 08, 2021 |
| MSI           | B450M MORTAR MAX            | [84c316ee57](https://linux-hardware.org/?probe=84c316ee57) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | [886c08185e](https://linux-hardware.org/?probe=886c08185e) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | [e141b2d36a](https://linux-hardware.org/?probe=e141b2d36a) | Nov 08, 2021 |
| Foxconn       | H61M/H61M-S                 | [62ae26dca0](https://linux-hardware.org/?probe=62ae26dca0) | Nov 07, 2021 |
| Dell          | 0HY9JP A00                  | [05c38bf92c](https://linux-hardware.org/?probe=05c38bf92c) | Nov 07, 2021 |
| ASUSTek       | A68HM-PLUS                  | [384fb31833](https://linux-hardware.org/?probe=384fb31833) | Nov 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [f57575ffaf](https://linux-hardware.org/?probe=f57575ffaf) | Nov 06, 2021 |
| Dell          | 0VNP2H A02                  | [5402226d98](https://linux-hardware.org/?probe=5402226d98) | Nov 06, 2021 |
| ASUSTek       | M5A78L-M LX                 | [e6e813115f](https://linux-hardware.org/?probe=e6e813115f) | Nov 06, 2021 |
| HP            | 0A98h                       | [110c37e799](https://linux-hardware.org/?probe=110c37e799) | Nov 06, 2021 |
| ASUSTek       | A68HM-PLUS                  | [7b21a0bc71](https://linux-hardware.org/?probe=7b21a0bc71) | Nov 06, 2021 |
| Dell          | 0NKW6Y A00                  | [82a09e132d](https://linux-hardware.org/?probe=82a09e132d) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| Gigabyte      | F2A78M-D3H                  | [43e09b8e80](https://linux-hardware.org/?probe=43e09b8e80) | Nov 05, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | [1383828428](https://linux-hardware.org/?probe=1383828428) | Nov 05, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | [f5ee7a26d5](https://linux-hardware.org/?probe=f5ee7a26d5) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [3e4d5dd09d](https://linux-hardware.org/?probe=3e4d5dd09d) | Nov 05, 2021 |
| Foxconn       | H61M/H61M-S                 | [7f3894059d](https://linux-hardware.org/?probe=7f3894059d) | Nov 04, 2021 |
| HP            | 18E4                        | [3069846b25](https://linux-hardware.org/?probe=3069846b25) | Nov 04, 2021 |
| MSI           | G41M-P23                    | [82e51e3f78](https://linux-hardware.org/?probe=82e51e3f78) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [d7a405763d](https://linux-hardware.org/?probe=d7a405763d) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [2d26d5b578](https://linux-hardware.org/?probe=2d26d5b578) | Nov 02, 2021 |
| ASUSTek       | P8Z77-V LX                  | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| ASUSTek       | M11AD                       | [0cb5032c53](https://linux-hardware.org/?probe=0cb5032c53) | Nov 02, 2021 |
| Gigabyte      | GA-E6010N                   | [3c81474040](https://linux-hardware.org/?probe=3c81474040) | Nov 01, 2021 |
| Gigabyte      | GA-E6010N                   | [2a2aaffd43](https://linux-hardware.org/?probe=2a2aaffd43) | Nov 01, 2021 |
| ASRock        | FM2A55M-HD+                 | [42cd4d28bd](https://linux-hardware.org/?probe=42cd4d28bd) | Nov 01, 2021 |
| eMachines     | EL1850G                     | [01dbf1b5ec](https://linux-hardware.org/?probe=01dbf1b5ec) | Oct 31, 2021 |
| MSI           | P55-CD53                    | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| Unknown       | Unknown                     | [75cc8a67e9](https://linux-hardware.org/?probe=75cc8a67e9) | Oct 31, 2021 |
| ASRock        | B85M-HDS                    | [111e98ddef](https://linux-hardware.org/?probe=111e98ddef) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [6cee757cf0](https://linux-hardware.org/?probe=6cee757cf0) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [96c9053284](https://linux-hardware.org/?probe=96c9053284) | Oct 31, 2021 |
| Dell          | 06NWYK A01                  | [497c824fd5](https://linux-hardware.org/?probe=497c824fd5) | Oct 31, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [0981774043](https://linux-hardware.org/?probe=0981774043) | Oct 30, 2021 |
| ASRock        | B85M-HDS                    | [69dd0cf598](https://linux-hardware.org/?probe=69dd0cf598) | Oct 30, 2021 |
| Dell          | 06NWYK A01                  | [1d0625eb89](https://linux-hardware.org/?probe=1d0625eb89) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [867e533368](https://linux-hardware.org/?probe=867e533368) | Oct 30, 2021 |
| ASUSTek       | P5K SE/EPU                  | [80adff7646](https://linux-hardware.org/?probe=80adff7646) | Oct 30, 2021 |
| Dell          | 0GY6Y8 A02                  | [1a267b14d3](https://linux-hardware.org/?probe=1a267b14d3) | Oct 29, 2021 |
| Dell          | 0GY6Y8 A02                  | [5b4cea000b](https://linux-hardware.org/?probe=5b4cea000b) | Oct 29, 2021 |
| ASRock        | B450 Gaming K4              | [b67ec8af25](https://linux-hardware.org/?probe=b67ec8af25) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | [4e19df8e3c](https://linux-hardware.org/?probe=4e19df8e3c) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | [c220480b4c](https://linux-hardware.org/?probe=c220480b4c) | Oct 29, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [a73fabcd4c](https://linux-hardware.org/?probe=a73fabcd4c) | Oct 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [528cec41bc](https://linux-hardware.org/?probe=528cec41bc) | Oct 28, 2021 |
| Alienware     | 08PG26 A00                  | [bb2fd997ab](https://linux-hardware.org/?probe=bb2fd997ab) | Oct 28, 2021 |
| ASRock        | FM2A88X Extreme6+           | [b676d9030a](https://linux-hardware.org/?probe=b676d9030a) | Oct 28, 2021 |
| MSI           | MAG B550M MORTAR            | [08819513f2](https://linux-hardware.org/?probe=08819513f2) | Oct 27, 2021 |
| MSI           | MAG B550M MORTAR            | [4207c6eaac](https://linux-hardware.org/?probe=4207c6eaac) | Oct 27, 2021 |
| ASUSTek       | PRIME Z270-P                | [dfb2070b53](https://linux-hardware.org/?probe=dfb2070b53) | Oct 26, 2021 |
| Alienware     | 08PG26 A00                  | [7d6b559bf8](https://linux-hardware.org/?probe=7d6b559bf8) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| ASRock        | FM2A55M-HD+                 | [a1cf5282ba](https://linux-hardware.org/?probe=a1cf5282ba) | Oct 25, 2021 |
| ASRock        | H110M-HDS R3.0              | [718ad346b7](https://linux-hardware.org/?probe=718ad346b7) | Oct 25, 2021 |
| MSI           | 2AE0                        | [64a3b3ae41](https://linux-hardware.org/?probe=64a3b3ae41) | Oct 24, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [cc46a59d6c](https://linux-hardware.org/?probe=cc46a59d6c) | Oct 24, 2021 |
| MSI           | P55-CD53                    | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [fca2aa4310](https://linux-hardware.org/?probe=fca2aa4310) | Oct 23, 2021 |
| Dell          | 0VHXCD A00                  | [7c99a6ed29](https://linux-hardware.org/?probe=7c99a6ed29) | Oct 22, 2021 |
| ASRock        | 970 Pro3 R2.0               | [915961c057](https://linux-hardware.org/?probe=915961c057) | Oct 22, 2021 |
| Biostar       | A68N-5100                   | [bc5b7a2417](https://linux-hardware.org/?probe=bc5b7a2417) | Oct 22, 2021 |
| MSI           | Z68A-G43                    | [b781916d8e](https://linux-hardware.org/?probe=b781916d8e) | Oct 22, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [baee5192b6](https://linux-hardware.org/?probe=baee5192b6) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| HP            | 1589                        | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Unknown       | Phitronics G41-M3           | [a6ccedb5bd](https://linux-hardware.org/?probe=a6ccedb5bd) | Oct 20, 2021 |
| Unknown       | Phitronics G41-M3           | [fbe886aee7](https://linux-hardware.org/?probe=fbe886aee7) | Oct 20, 2021 |
| Unknown       | Unknown                     | [8c412b3b5b](https://linux-hardware.org/?probe=8c412b3b5b) | Oct 20, 2021 |
| Gigabyte      | B75M-D2V                    | [9fc60b0ba8](https://linux-hardware.org/?probe=9fc60b0ba8) | Oct 19, 2021 |
| HP            | 2B38                        | [2cf327f158](https://linux-hardware.org/?probe=2cf327f158) | Oct 18, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [2f5f509752](https://linux-hardware.org/?probe=2f5f509752) | Oct 18, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | [a7ea75f7c5](https://linux-hardware.org/?probe=a7ea75f7c5) | Oct 18, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [9f22e32d08](https://linux-hardware.org/?probe=9f22e32d08) | Oct 17, 2021 |
| ASUSTek       | P6T                         | [69397b40d4](https://linux-hardware.org/?probe=69397b40d4) | Oct 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [058d7e8e3e](https://linux-hardware.org/?probe=058d7e8e3e) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [ce2e0740c8](https://linux-hardware.org/?probe=ce2e0740c8) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [a3dbbf3c03](https://linux-hardware.org/?probe=a3dbbf3c03) | Oct 17, 2021 |
| Lenovo        | SHARKBAY NOK                | [5de4ff60b0](https://linux-hardware.org/?probe=5de4ff60b0) | Oct 16, 2021 |
| Gigabyte      | H61M-S2PV                   | [e3806f5c09](https://linux-hardware.org/?probe=e3806f5c09) | Oct 16, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [a89127ff6a](https://linux-hardware.org/?probe=a89127ff6a) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [7de05cdbc3](https://linux-hardware.org/?probe=7de05cdbc3) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [66b0e77a10](https://linux-hardware.org/?probe=66b0e77a10) | Oct 15, 2021 |
| Dell          | 0VHXCD A00                  | [ccd75d2752](https://linux-hardware.org/?probe=ccd75d2752) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | [c0beced761](https://linux-hardware.org/?probe=c0beced761) | Oct 14, 2021 |
| ASUSTek       | M5A78L                      | [a027b0f5ba](https://linux-hardware.org/?probe=a027b0f5ba) | Oct 12, 2021 |
| HP            | 81C7 MVB 0C                 | [23d528f392](https://linux-hardware.org/?probe=23d528f392) | Oct 12, 2021 |
| ASUSTek       | M5A78L                      | [071d7e45a0](https://linux-hardware.org/?probe=071d7e45a0) | Oct 11, 2021 |
| Biostar       | G41-M7                      | [94efede651](https://linux-hardware.org/?probe=94efede651) | Oct 10, 2021 |
| ASUSTek       | P7H55-M PRO                 | [1892bf50b9](https://linux-hardware.org/?probe=1892bf50b9) | Oct 09, 2021 |
| HP            | 81C7 MVB 0C                 | [5bfcd88031](https://linux-hardware.org/?probe=5bfcd88031) | Oct 09, 2021 |
| Biostar       | G41-M7                      | [4f1889a1de](https://linux-hardware.org/?probe=4f1889a1de) | Oct 09, 2021 |
| Dell          | 0D28YY A02                  | [237a82041b](https://linux-hardware.org/?probe=237a82041b) | Oct 09, 2021 |
| ASUSTek       | H87M-PLUS                   | [f0a1062216](https://linux-hardware.org/?probe=f0a1062216) | Oct 09, 2021 |
| Dell          | 0VHXCD A00                  | [7a2b25ff42](https://linux-hardware.org/?probe=7a2b25ff42) | Oct 08, 2021 |
| Dell          | 04Y8V0 A01                  | [453beab8c3](https://linux-hardware.org/?probe=453beab8c3) | Oct 08, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [c9d3dce156](https://linux-hardware.org/?probe=c9d3dce156) | Oct 08, 2021 |
| ASUSTek       | CM5570                      | [75b8bca0fa](https://linux-hardware.org/?probe=75b8bca0fa) | Oct 07, 2021 |
| HP            | 8591                        | [22dca8a98c](https://linux-hardware.org/?probe=22dca8a98c) | Oct 07, 2021 |
| Dell          | 0VHXCD A00                  | [7f81996b23](https://linux-hardware.org/?probe=7f81996b23) | Oct 07, 2021 |
| Dell          | 0D6H9T A02                  | [42b9320d55](https://linux-hardware.org/?probe=42b9320d55) | Oct 06, 2021 |
| Gigabyte      | H61M-S2PV                   | [ed77d40eeb](https://linux-hardware.org/?probe=ed77d40eeb) | Oct 05, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [173104cfcf](https://linux-hardware.org/?probe=173104cfcf) | Oct 04, 2021 |
| ASUSTek       | PRIME B360M-K               | [163b47753d](https://linux-hardware.org/?probe=163b47753d) | Oct 03, 2021 |
| MSI           | B150M MORTAR                | [224b713b5c](https://linux-hardware.org/?probe=224b713b5c) | Oct 03, 2021 |
| Gigabyte      | B560M AORUS ELITE           | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| Gigabyte      | H81M-S2PV                   | [a02538183c](https://linux-hardware.org/?probe=a02538183c) | Oct 01, 2021 |
| Gigabyte      | 970A-UD3P                   | [10d8a84245](https://linux-hardware.org/?probe=10d8a84245) | Oct 01, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [2a8da86d79](https://linux-hardware.org/?probe=2a8da86d79) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [b6eca9083a](https://linux-hardware.org/?probe=b6eca9083a) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [415f0d9244](https://linux-hardware.org/?probe=415f0d9244) | Oct 01, 2021 |
| Dell          | 0HN7XN A00                  | [cc8a68bbd6](https://linux-hardware.org/?probe=cc8a68bbd6) | Sep 30, 2021 |
| ASRock        | Z490 Extreme4               | [8137456421](https://linux-hardware.org/?probe=8137456421) | Sep 30, 2021 |
| ASRock        | Z490 Extreme4               | [3411428e31](https://linux-hardware.org/?probe=3411428e31) | Sep 30, 2021 |
| Dell          | 0HN7XN A00                  | [5f56956871](https://linux-hardware.org/?probe=5f56956871) | Sep 30, 2021 |
| ASRock        | H61M-VG4                    | [33c6d2d214](https://linux-hardware.org/?probe=33c6d2d214) | Sep 30, 2021 |
| Lenovo        | IdeaCentre K330             | [ed6e765fea](https://linux-hardware.org/?probe=ed6e765fea) | Sep 29, 2021 |
| Gigabyte      | J4005ND2P-CF                | [699985f9e6](https://linux-hardware.org/?probe=699985f9e6) | Sep 28, 2021 |
| Gigabyte      | J4005ND2P-CF                | [d82bdfcf17](https://linux-hardware.org/?probe=d82bdfcf17) | Sep 28, 2021 |
| ASUSTek       | PRIME B450M-A               | [d5b8eb94d7](https://linux-hardware.org/?probe=d5b8eb94d7) | Sep 28, 2021 |
| Dell          | 0TNXNR A01                  | [781c19cc33](https://linux-hardware.org/?probe=781c19cc33) | Sep 27, 2021 |
| Dell          | 0D6H9T A02                  | [30e914656e](https://linux-hardware.org/?probe=30e914656e) | Sep 27, 2021 |
| Unknown       | Unknown                     | [0625659706](https://linux-hardware.org/?probe=0625659706) | Sep 27, 2021 |
| Dell          | 0TP406                      | [39f9e67ae2](https://linux-hardware.org/?probe=39f9e67ae2) | Sep 26, 2021 |
| HP            | 18E7                        | [94f692683b](https://linux-hardware.org/?probe=94f692683b) | Sep 26, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [4bc5eb3bbc](https://linux-hardware.org/?probe=4bc5eb3bbc) | Sep 25, 2021 |
| eMachines     | EL1850G                     | [f5b47069bb](https://linux-hardware.org/?probe=f5b47069bb) | Sep 25, 2021 |
| Lenovo        | ThinkCentre M58 3231W2Y     | [a2da2733ac](https://linux-hardware.org/?probe=a2da2733ac) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [5cc1a01b2f](https://linux-hardware.org/?probe=5cc1a01b2f) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [2b341862f1](https://linux-hardware.org/?probe=2b341862f1) | Sep 25, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [65ebe53761](https://linux-hardware.org/?probe=65ebe53761) | Sep 25, 2021 |
| MSI           | B75MA-P45                   | [663af51c43](https://linux-hardware.org/?probe=663af51c43) | Sep 24, 2021 |
| MSI           | B75MA-P45                   | [4d4844cfbe](https://linux-hardware.org/?probe=4d4844cfbe) | Sep 24, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | [dc87018670](https://linux-hardware.org/?probe=dc87018670) | Sep 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8617cbbc27](https://linux-hardware.org/?probe=8617cbbc27) | Sep 24, 2021 |
| ASRock        | 775VM800                    | [e07158e4ab](https://linux-hardware.org/?probe=e07158e4ab) | Sep 24, 2021 |
| HP            | 18E7                        | [29fa39d7e9](https://linux-hardware.org/?probe=29fa39d7e9) | Sep 23, 2021 |
| ASRock        | 880GMH/U3S3                 | [ec55312287](https://linux-hardware.org/?probe=ec55312287) | Sep 23, 2021 |
| Gigabyte      | B75M-D3H                    | [cb23f25d7f](https://linux-hardware.org/?probe=cb23f25d7f) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [74410f0d0c](https://linux-hardware.org/?probe=74410f0d0c) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ad81766325](https://linux-hardware.org/?probe=ad81766325) | Sep 23, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [bc7d0dc232](https://linux-hardware.org/?probe=bc7d0dc232) | Sep 22, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | [529a9f4c74](https://linux-hardware.org/?probe=529a9f4c74) | Sep 22, 2021 |
| HP            | 213D A01                    | [8d4dd8359c](https://linux-hardware.org/?probe=8d4dd8359c) | Sep 21, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [3354edcb58](https://linux-hardware.org/?probe=3354edcb58) | Sep 21, 2021 |
| Gigabyte      | B75M-D3H                    | [3ef59689e6](https://linux-hardware.org/?probe=3ef59689e6) | Sep 21, 2021 |
| MSI           | H81M-E33                    | [5ef84c22e6](https://linux-hardware.org/?probe=5ef84c22e6) | Sep 20, 2021 |
| MSI           | H81M-E33                    | [db96085729](https://linux-hardware.org/?probe=db96085729) | Sep 20, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [a0b7d0cf25](https://linux-hardware.org/?probe=a0b7d0cf25) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c05636068f](https://linux-hardware.org/?probe=c05636068f) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [1a012b3021](https://linux-hardware.org/?probe=1a012b3021) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [b9259e3604](https://linux-hardware.org/?probe=b9259e3604) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [9eb1254056](https://linux-hardware.org/?probe=9eb1254056) | Sep 19, 2021 |
| Gigabyte      | Z77-D3H                     | [c86625aa34](https://linux-hardware.org/?probe=c86625aa34) | Sep 19, 2021 |
| HP            | 2B28                        | [14681c925a](https://linux-hardware.org/?probe=14681c925a) | Sep 19, 2021 |
| Sapphire T... | PURE PLATINUM 970A-PLUS     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| ASRock        | FM2A58M-DG3+                | [183fc0dd5e](https://linux-hardware.org/?probe=183fc0dd5e) | Sep 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bc3e2da7f3](https://linux-hardware.org/?probe=bc3e2da7f3) | Sep 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [e8f361170f](https://linux-hardware.org/?probe=e8f361170f) | Sep 18, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [30f36dc15d](https://linux-hardware.org/?probe=30f36dc15d) | Sep 17, 2021 |
| ASRock        | B450 Pro4                   | [042032eec7](https://linux-hardware.org/?probe=042032eec7) | Sep 16, 2021 |
| Intel         | X99                         | [814b3326d1](https://linux-hardware.org/?probe=814b3326d1) | Sep 15, 2021 |
| NCR           | Talladega                   | [95445fa221](https://linux-hardware.org/?probe=95445fa221) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | [93a071ca7e](https://linux-hardware.org/?probe=93a071ca7e) | Sep 14, 2021 |
| Foxconn       | 17A0                        | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | [874dcada55](https://linux-hardware.org/?probe=874dcada55) | Sep 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [b3b1991c64](https://linux-hardware.org/?probe=b3b1991c64) | Sep 14, 2021 |
| ASUSTek       | NARRA3                      | [93db4618cc](https://linux-hardware.org/?probe=93db4618cc) | Sep 14, 2021 |
| ASUSTek       | Benicia                     | [2a764dd662](https://linux-hardware.org/?probe=2a764dd662) | Sep 13, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [6928772253](https://linux-hardware.org/?probe=6928772253) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [93a0d7ac6a](https://linux-hardware.org/?probe=93a0d7ac6a) | Sep 12, 2021 |
| HP            | 339A                        | [9284a70a92](https://linux-hardware.org/?probe=9284a70a92) | Sep 12, 2021 |
| ASUSTek       | P5Q                         | [8693b86435](https://linux-hardware.org/?probe=8693b86435) | Sep 12, 2021 |
| NCR           | Talladega                   | [6de6d8c2a3](https://linux-hardware.org/?probe=6de6d8c2a3) | Sep 12, 2021 |
| ASUSTek       | NARRA3                      | [6b02d3fa6f](https://linux-hardware.org/?probe=6b02d3fa6f) | Sep 11, 2021 |
| Gigabyte      | 970A-DS3P                   | [8b0f703471](https://linux-hardware.org/?probe=8b0f703471) | Sep 11, 2021 |
| Lenovo        | SDK0E50519 WIN              | [7c58527193](https://linux-hardware.org/?probe=7c58527193) | Sep 11, 2021 |
| Intel         | X79M-S                      | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| ASUSTek       | P5GC-MX/1333                | [1ff7b16ce4](https://linux-hardware.org/?probe=1ff7b16ce4) | Sep 10, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [dab9a23b27](https://linux-hardware.org/?probe=dab9a23b27) | Sep 10, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [34e6b7697f](https://linux-hardware.org/?probe=34e6b7697f) | Sep 09, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [5ce713a2f7](https://linux-hardware.org/?probe=5ce713a2f7) | Sep 09, 2021 |
| ASUSTek       | NARRA3                      | [52b22746e0](https://linux-hardware.org/?probe=52b22746e0) | Sep 09, 2021 |
| HP            | 2187 A01                    | [0c11e3b726](https://linux-hardware.org/?probe=0c11e3b726) | Sep 09, 2021 |
| MSI           | B450M MORTAR MAX            | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| Dell          | 09KPNV A01                  | [f3c9b271f1](https://linux-hardware.org/?probe=f3c9b271f1) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [7dbf053877](https://linux-hardware.org/?probe=7dbf053877) | Sep 08, 2021 |
| MSI           | H81M-P33                    | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [17c58396b6](https://linux-hardware.org/?probe=17c58396b6) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [dfe73847d3](https://linux-hardware.org/?probe=dfe73847d3) | Sep 08, 2021 |
| Dell          | 0D28YY A03                  | [3eb7b9cb7b](https://linux-hardware.org/?probe=3eb7b9cb7b) | Sep 08, 2021 |
| ASUSTek       | P5G41T-M LX3                | [2f680da4b8](https://linux-hardware.org/?probe=2f680da4b8) | Sep 07, 2021 |
| Unknown       | Unknown                     | [b00795951c](https://linux-hardware.org/?probe=b00795951c) | Sep 07, 2021 |
| MSI           | B560M PRO-VDH               | [807eed7553](https://linux-hardware.org/?probe=807eed7553) | Sep 06, 2021 |
| ASRock        | Q1900M                      | [3f08533d5f](https://linux-hardware.org/?probe=3f08533d5f) | Sep 06, 2021 |
| ASRock        | Q1900M                      | [d342919044](https://linux-hardware.org/?probe=d342919044) | Sep 06, 2021 |
| Intel         | X79M-S                      | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| ASUSTek       | M5A97                       | [28754f0456](https://linux-hardware.org/?probe=28754f0456) | Sep 06, 2021 |
| Gigabyte      | G31M-ES2L                   | [d94c35ce11](https://linux-hardware.org/?probe=d94c35ce11) | Sep 05, 2021 |
| MSI           | IONA                        | [8a4454604a](https://linux-hardware.org/?probe=8a4454604a) | Sep 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [791768dfbd](https://linux-hardware.org/?probe=791768dfbd) | Sep 04, 2021 |
| MSI           | IONA                        | [b775cef84a](https://linux-hardware.org/?probe=b775cef84a) | Sep 04, 2021 |
| ASUSTek       | NARRA3                      | [920ab9b385](https://linux-hardware.org/?probe=920ab9b385) | Sep 04, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | [149099265c](https://linux-hardware.org/?probe=149099265c) | Sep 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | [391c101a92](https://linux-hardware.org/?probe=391c101a92) | Sep 04, 2021 |
| HP            | 2B4B                        | [d36296bddf](https://linux-hardware.org/?probe=d36296bddf) | Sep 04, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [9e6ccaa1f3](https://linux-hardware.org/?probe=9e6ccaa1f3) | Sep 04, 2021 |
| Biostar       | X470NH                      | [f0449b9946](https://linux-hardware.org/?probe=f0449b9946) | Sep 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | [126d9974b1](https://linux-hardware.org/?probe=126d9974b1) | Sep 03, 2021 |
| HP            | 1497                        | [fd4cf5c840](https://linux-hardware.org/?probe=fd4cf5c840) | Sep 01, 2021 |
| Gigabyte      | B460M DS3H                  | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | [baa289fe51](https://linux-hardware.org/?probe=baa289fe51) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | [cc326a093e](https://linux-hardware.org/?probe=cc326a093e) | Aug 31, 2021 |
| HP            | 339A                        | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | 339A                        | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [4c711d446d](https://linux-hardware.org/?probe=4c711d446d) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [efb9bccc60](https://linux-hardware.org/?probe=efb9bccc60) | Aug 31, 2021 |
| Intel         | DQ77MK AAG39642-500         | [000d760a55](https://linux-hardware.org/?probe=000d760a55) | Aug 30, 2021 |
| Positivo      | POS-PIH81DI                 | [3b05a7b317](https://linux-hardware.org/?probe=3b05a7b317) | Aug 30, 2021 |
| MSI           | Z87-G43                     | [a219ff197d](https://linux-hardware.org/?probe=a219ff197d) | Aug 29, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [01a43874df](https://linux-hardware.org/?probe=01a43874df) | Aug 28, 2021 |
| ASUSTek       | PRIME A320M-K               | [f7a948129f](https://linux-hardware.org/?probe=f7a948129f) | Aug 28, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | [5cd3f43e28](https://linux-hardware.org/?probe=5cd3f43e28) | Aug 28, 2021 |
| Gigabyte      | A320M-S2H-CF                | [6ed5f8c32b](https://linux-hardware.org/?probe=6ed5f8c32b) | Aug 27, 2021 |
| ASRock        | Z390 Phantom Gaming 4-IB    | [b01269fbc1](https://linux-hardware.org/?probe=b01269fbc1) | Aug 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [51661e959e](https://linux-hardware.org/?probe=51661e959e) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3a7eb89cd8](https://linux-hardware.org/?probe=3a7eb89cd8) | Aug 25, 2021 |
| HP            | 802E                        | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Dell          | 088DT1 A01                  | [8620323354](https://linux-hardware.org/?probe=8620323354) | Aug 25, 2021 |
| Dell          | 0TP406                      | [72a3d9ac12](https://linux-hardware.org/?probe=72a3d9ac12) | Aug 25, 2021 |
| HP            | 2B4B                        | [4c5411522b](https://linux-hardware.org/?probe=4c5411522b) | Aug 25, 2021 |
| Gigabyte      | B85M-D3H                    | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| ASUSTek       | P8Z77-V LE                  | [a720e3326a](https://linux-hardware.org/?probe=a720e3326a) | Aug 23, 2021 |
| MSI           | B450M PRO-M2 MAX            | [e6f053c5be](https://linux-hardware.org/?probe=e6f053c5be) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [15175b4f4f](https://linux-hardware.org/?probe=15175b4f4f) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [02ccc1eb70](https://linux-hardware.org/?probe=02ccc1eb70) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | [372a125910](https://linux-hardware.org/?probe=372a125910) | Aug 22, 2021 |
| Lenovo        | Unknown                     | [b4e9579228](https://linux-hardware.org/?probe=b4e9579228) | Aug 21, 2021 |
| Lenovo        | Unknown                     | [12088eed17](https://linux-hardware.org/?probe=12088eed17) | Aug 21, 2021 |
| MSI           | B450M PRO-M2 MAX            | [68c6a2734b](https://linux-hardware.org/?probe=68c6a2734b) | Aug 21, 2021 |
| Intel         | DB75EN AAG39650-303         | [4bbb9f60f9](https://linux-hardware.org/?probe=4bbb9f60f9) | Aug 20, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| MSI           | Z97 XPOWER AC               | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [d78450d852](https://linux-hardware.org/?probe=d78450d852) | Aug 19, 2021 |
| Acer          | Aspire XC-605G              | [8bb6f8ef72](https://linux-hardware.org/?probe=8bb6f8ef72) | Aug 18, 2021 |
| ASUSTek       | B85M-G R2.0                 | [daf6bf889f](https://linux-hardware.org/?probe=daf6bf889f) | Aug 18, 2021 |
| MSI           | Z270-A PRO                  | [3be5b7f90e](https://linux-hardware.org/?probe=3be5b7f90e) | Aug 18, 2021 |
| Gigabyte      | B550M DS3H                  | [4b687b4c17](https://linux-hardware.org/?probe=4b687b4c17) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [97b71d18de](https://linux-hardware.org/?probe=97b71d18de) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [06872ddde7](https://linux-hardware.org/?probe=06872ddde7) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [a1f448c1f6](https://linux-hardware.org/?probe=a1f448c1f6) | Aug 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | [fb7eb46b29](https://linux-hardware.org/?probe=fb7eb46b29) | Aug 11, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | [fb8a0b07d1](https://linux-hardware.org/?probe=fb8a0b07d1) | Aug 10, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [4d9eaaf5a8](https://linux-hardware.org/?probe=4d9eaaf5a8) | Aug 09, 2021 |
| Gigabyte      | B550M H                     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [9c841a04d6](https://linux-hardware.org/?probe=9c841a04d6) | Aug 01, 2021 |
| Gigabyte      | H61M-USB3-B3                | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| Dell          | 0V8WGR A00                  | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| ASUSTek       | P8H61-M LE                  | [b0270beb17](https://linux-hardware.org/?probe=b0270beb17) | Jul 11, 2021 |
| ASUSTek       | P8H61-M LE                  | [896e6feb8a](https://linux-hardware.org/?probe=896e6feb8a) | Jul 11, 2021 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [20bf622c31](https://linux-hardware.org/?probe=20bf622c31) | Jun 25, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [35605881d6](https://linux-hardware.org/?probe=35605881d6) | Jun 23, 2021 |
| MSI           | 2AE0                        | [bce75d51cd](https://linux-hardware.org/?probe=bce75d51cd) | Jun 23, 2021 |
| MSI           | 2AE0                        | [0412c710eb](https://linux-hardware.org/?probe=0412c710eb) | Jun 22, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [b9d86eb932](https://linux-hardware.org/?probe=b9d86eb932) | Jun 17, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [71de5617aa](https://linux-hardware.org/?probe=71de5617aa) | Jun 17, 2021 |
| ASUSTek       | PRIME X570-P                | [bca1e1b92f](https://linux-hardware.org/?probe=bca1e1b92f) | Jun 16, 2021 |
| ASUSTek       | PRIME X570-P                | [b3f6c76103](https://linux-hardware.org/?probe=b3f6c76103) | Jun 16, 2021 |
| Gigabyte      | B85-HD3                     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| HP            | 843C                        | [ccff6e4f39](https://linux-hardware.org/?probe=ccff6e4f39) | Jun 08, 2021 |
| ASRock        | 990FX Extreme6              | [fc3b27abac](https://linux-hardware.org/?probe=fc3b27abac) | Jun 03, 2021 |
| HP            | 8591                        | [6f71430d88](https://linux-hardware.org/?probe=6f71430d88) | Jun 01, 2021 |
| HP            | 8591                        | [fc12c57885](https://linux-hardware.org/?probe=fc12c57885) | Jun 01, 2021 |
| ASRock        | 990FX Extreme6              | [0a228b18c1](https://linux-hardware.org/?probe=0a228b18c1) | May 30, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [0144616bb9](https://linux-hardware.org/?probe=0144616bb9) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [887dbc1614](https://linux-hardware.org/?probe=887dbc1614) | May 24, 2021 |
| Biostar       | A320MH                      | [db3a18e1c3](https://linux-hardware.org/?probe=db3a18e1c3) | May 23, 2021 |
| Biostar       | A320MH                      | [ccb22fc057](https://linux-hardware.org/?probe=ccb22fc057) | May 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0c314899c1](https://linux-hardware.org/?probe=0c314899c1) | May 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c41eec9cd3](https://linux-hardware.org/?probe=c41eec9cd3) | May 21, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ca773b28ee](https://linux-hardware.org/?probe=ca773b28ee) | May 19, 2021 |
| ASUSTek       | P8H61-I R2.0                | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek       | P8H61-I R2.0                | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| Lenovo        | Annapurna CRB NOK           | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo        | Annapurna CRB NOK           | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Dell          | 06D7TR A00                  | [1ccb5b0600](https://linux-hardware.org/?probe=1ccb5b0600) | May 01, 2021 |
| Pegatron      | Benicia                     | [df847c36d5](https://linux-hardware.org/?probe=df847c36d5) | Apr 25, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [7f46cdb7ab](https://linux-hardware.org/?probe=7f46cdb7ab) | Apr 24, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [b00e95f3db](https://linux-hardware.org/?probe=b00e95f3db) | Apr 22, 2021 |
| ASUSTek       | P5K                         | [0149b6c450](https://linux-hardware.org/?probe=0149b6c450) | Apr 22, 2021 |
| Dell          | 0PGKWF A02                  | [f963717b2c](https://linux-hardware.org/?probe=f963717b2c) | Apr 18, 2021 |
| Acer          | Aspire XC-605G              | [79d3d3a05e](https://linux-hardware.org/?probe=79d3d3a05e) | Mar 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.11.0-27-generic          | 55       | 16.52%  |
| 5.11.0-38-generic          | 54       | 16.22%  |
| 5.11.0-40-generic          | 48       | 14.41%  |
| 5.11.0-41-generic          | 38       | 11.41%  |
| 5.11.0-37-generic          | 35       | 10.51%  |
| 5.11.0-34-generic          | 31       | 9.31%   |
| 5.11.0-43-generic          | 29       | 8.71%   |
| 5.11.0-36-generic          | 12       | 3.6%    |
| 5.8.0-53-generic           | 7        | 2.1%    |
| 5.8.0-55-generic           | 5        | 1.5%    |
| 5.8.0-50-generic           | 5        | 1.5%    |
| 5.8.0-59-generic           | 3        | 0.9%    |
| 5.8.0-49-generic           | 3        | 0.9%    |
| 5.11.0-25-generic          | 3        | 0.9%    |
| 5.8.0-63-generic           | 2        | 0.6%    |
| 5.8.0-45-generic           | 1        | 0.3%    |
| 5.15.0-10.2-liquorix-amd64 | 1        | 0.3%    |
| 5.14.0-1010-oem            | 1        | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 297      | 91.67%  |
| 5.8.0   | 25       | 7.72%   |
| 5.15.0  | 1        | 0.31%   |
| 5.14.0  | 1        | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 297      | 91.67%  |
| 5.8     | 25       | 7.72%   |
| 5.15    | 1        | 0.31%   |
| 5.14    | 1        | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 319      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME    | 302      | 94.38%  |
| XFCE     | 13       | 4.06%   |
| Unknown  | 3        | 0.94%   |
| MATE     | 1        | 0.31%   |
| Cinnamon | 1        | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 319      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 283      | 88.71%  |
| GDM     | 19       | 5.96%   |
| GDM3    | 16       | 5.02%   |
| TDM     | 1        | 0.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 129      | 40.44%  |
| de_DE       | 37       | 11.6%   |
| en_GB       | 29       | 9.09%   |
| pt_BR       | 17       | 5.33%   |
| pl_PL       | 8        | 2.51%   |
| es_ES       | 8        | 2.51%   |
| en_IN       | 8        | 2.51%   |
| en_CA       | 8        | 2.51%   |
| nl_NL       | 7        | 2.19%   |
| it_IT       | 7        | 2.19%   |
| fr_FR       | 7        | 2.19%   |
| es_MX       | 5        | 1.57%   |
| en_ZA       | 4        | 1.25%   |
| tr_TR       | 3        | 0.94%   |
| hu_HU       | 3        | 0.94%   |
| es_AR       | 3        | 0.94%   |
| en_AU       | 3        | 0.94%   |
| sv_SE       | 2        | 0.63%   |
| sl_SI       | 2        | 0.63%   |
| ru_RU       | 2        | 0.63%   |
| pt_PT       | 2        | 0.63%   |
| nl_BE       | 2        | 0.63%   |
| fr_CA       | 2        | 0.63%   |
| es_CL       | 2        | 0.63%   |
| en_NZ       | 2        | 0.63%   |
| el_GR       | 2        | 0.63%   |
| de_CH       | 2        | 0.63%   |
| zh_TW       | 1        | 0.31%   |
| zh_CN       | 1        | 0.31%   |
| sr_RS@latin | 1        | 0.31%   |
| sr_RS       | 1        | 0.31%   |
| nb_NO       | 1        | 0.31%   |
| he_IL       | 1        | 0.31%   |
| fr_CH       | 1        | 0.31%   |
| es_PE       | 1        | 0.31%   |
| es_PA       | 1        | 0.31%   |
| es_GT       | 1        | 0.31%   |
| en_SG       | 1        | 0.31%   |
| cs_CZ       | 1        | 0.31%   |
| C           | 1        | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 183      | 57.19%  |
| EFI  | 137      | 42.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 299      | 93.73%  |
| Zfs      | 6        | 1.88%   |
| Overlay  | 5        | 1.57%   |
| Btrfs    | 5        | 1.57%   |
| Xfs      | 1        | 0.31%   |
| Reiserfs | 1        | 0.31%   |
| Ext3     | 1        | 0.31%   |
| Ext2     | 1        | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 296      | 92.79%  |
| GPT     | 17       | 5.33%   |
| MBR     | 6        | 1.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 308      | 96.25%  |
| Yes       | 12       | 3.75%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 283      | 88.71%  |
| Yes       | 36       | 11.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUSTek Computer            | 84       | 26.33%  |
| Gigabyte Technology         | 51       | 15.99%  |
| Dell                        | 35       | 10.97%  |
| MSI                         | 31       | 9.72%   |
| ASRock                      | 30       | 9.4%    |
| Hewlett-Packard             | 29       | 9.09%   |
| Lenovo                      | 17       | 5.33%   |
| Intel                       | 9        | 2.82%   |
| Biostar                     | 6        | 1.88%   |
| Fujitsu                     | 4        | 1.25%   |
| Foxconn                     | 4        | 1.25%   |
| Acer                        | 3        | 0.94%   |
| Unknown                     | 3        | 0.94%   |
| Pegatron                    | 2        | 0.63%   |
| ECS                         | 2        | 0.63%   |
| Shuttle                     | 1        | 0.31%   |
| Sapphire Technology Limited | 1        | 0.31%   |
| Positivo                    | 1        | 0.31%   |
| NCR                         | 1        | 0.31%   |
| Medion                      | 1        | 0.31%   |
| LattePanda                  | 1        | 0.31%   |
| eMachines                   | 1        | 0.31%   |
| Apple                       | 1        | 0.31%   |
| Alienware                   | 1        | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| ASUS All Series                          | 9        | 2.82%   |
| Dell OptiPlex 990                        | 5        | 1.57%   |
| Dell OptiPlex 790                        | 5        | 1.57%   |
| Dell OptiPlex 7010                       | 4        | 1.25%   |
| Unknown                                  | 4        | 1.25%   |
| MSI MS-7C02                              | 3        | 0.94%   |
| MSI MS-7817                              | 3        | 0.94%   |
| Gigabyte A320M-S2H                       | 3        | 0.94%   |
| ASUS P8Z77-V LX                          | 3        | 0.94%   |
| ASUS M5A78L-M/USB3                       | 3        | 0.94%   |
| ASRock B450M Pro4                        | 3        | 0.94%   |
| MSI MS-7B89                              | 2        | 0.63%   |
| MSI MS-7693                              | 2        | 0.63%   |
| Intel DQ77MK-R01                         | 2        | 0.63%   |
| HP ProDesk 600 G1 SFF                    | 2        | 0.63%   |
| HP Compaq Pro 6300 SFF                   | 2        | 0.63%   |
| Gigabyte G31M-ES2L                       | 2        | 0.63%   |
| Gigabyte B75M-D3H                        | 2        | 0.63%   |
| Gigabyte 970A-DS3P                       | 2        | 0.63%   |
| Dell XPS420                              | 2        | 0.63%   |
| Dell Inspiron 3847                       | 2        | 0.63%   |
| Biostar A320MH                           | 2        | 0.63%   |
| ASUS PRIME B450M-GAMING/BR               | 2        | 0.63%   |
| ASUS PRIME B360M-K                       | 2        | 0.63%   |
| ASUS P5G41T-M LX3                        | 2        | 0.63%   |
| ASUS M5A97 LE R2.0                       | 2        | 0.63%   |
| ASUS A68HM-PLUS                          | 2        | 0.63%   |
| ASRock B450 Pro4                         | 2        | 0.63%   |
| Shuttle XH61V                            | 1        | 0.31%   |
| Sapphire Limited PURE PLATINUM 970A-PLUS | 1        | 0.31%   |
| Positivo POS-PIH81DI                     | 1        | 0.31%   |
| Pegatron NY537AA-ABA 300-1025            | 1        | 0.31%   |
| Pegatron NE502AV-ABA a6750t              | 1        | 0.31%   |
| NCR xxxx-xxxx-xxxx                       | 1        | 0.31%   |
| MSI WE136AA-UUZ p6337ch                  | 1        | 0.31%   |
| MSI Pro 3515 Series                      | 1        | 0.31%   |
| MSI p6745nl                              | 1        | 0.31%   |
| MSI MS-7D18                              | 1        | 0.31%   |
| MSI MS-7D17                              | 1        | 0.31%   |
| MSI MS-7C94                              | 1        | 0.31%   |
| MSI MS-7C79                              | 1        | 0.31%   |
| MSI MS-7C56                              | 1        | 0.31%   |
| MSI MS-7C37                              | 1        | 0.31%   |
| MSI MS-7B85                              | 1        | 0.31%   |
| MSI MS-7B84                              | 1        | 0.31%   |
| MSI MS-7B53                              | 1        | 0.31%   |
| MSI MS-7B51                              | 1        | 0.31%   |
| MSI MS-7A71                              | 1        | 0.31%   |
| MSI MS-7A33                              | 1        | 0.31%   |
| MSI MS-7914                              | 1        | 0.31%   |
| MSI MS-7816                              | 1        | 0.31%   |
| MSI MS-7798                              | 1        | 0.31%   |
| MSI MS-7750                              | 1        | 0.31%   |
| MSI MS-7592                              | 1        | 0.31%   |
| MSI MS-7053                              | 1        | 0.31%   |
| Medion MS-7707                           | 1        | 0.31%   |
| Lenovo ThinkStation P510 30B4S0F616      | 1        | 0.31%   |
| Lenovo ThinkCentre M93p 10AAS1DP00       | 1        | 0.31%   |
| Lenovo ThinkCentre M93p 10AAS0ME00       | 1        | 0.31%   |
| Lenovo ThinkCentre M83 MT-M 10AJ-0003MB  | 1        | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 25       | 7.84%   |
| ASUS PRIME             | 12       | 3.76%   |
| Lenovo ThinkCentre     | 9        | 2.82%   |
| ASUS All               | 9        | 2.82%   |
| ASUS ROG               | 8        | 2.51%   |
| HP Compaq              | 7        | 2.19%   |
| HP EliteDesk           | 5        | 1.57%   |
| ASUS M5A78L-M          | 5        | 1.57%   |
| ASUS P8Z77-V           | 4        | 1.25%   |
| ASUS M5A97             | 4        | 1.25%   |
| ASRock B450M           | 4        | 1.25%   |
| Unknown                | 4        | 1.25%   |
| MSI MS-7C02            | 3        | 0.94%   |
| MSI MS-7817            | 3        | 0.94%   |
| Lenovo IdeaCentre      | 3        | 0.94%   |
| Gigabyte B450M         | 3        | 0.94%   |
| Gigabyte B450          | 3        | 0.94%   |
| Gigabyte A320M-S2H     | 3        | 0.94%   |
| Fujitsu ESPRIMO        | 3        | 0.94%   |
| Dell Precision         | 3        | 0.94%   |
| ASUS P8H61-M           | 3        | 0.94%   |
| ASRock B450            | 3        | 0.94%   |
| Acer Aspire            | 3        | 0.94%   |
| MSI MS-7B89            | 2        | 0.63%   |
| MSI MS-7693            | 2        | 0.63%   |
| Intel DQ77MK-R01       | 2        | 0.63%   |
| HP t620                | 2        | 0.63%   |
| HP ProDesk             | 2        | 0.63%   |
| Gigabyte X570          | 2        | 0.63%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.63%   |
| Gigabyte G31M-ES2L     | 2        | 0.63%   |
| Gigabyte B75M-D3H      | 2        | 0.63%   |
| Gigabyte B550M         | 2        | 0.63%   |
| Gigabyte 970A-DS3P     | 2        | 0.63%   |
| Dell XPS420            | 2        | 0.63%   |
| Dell XPS               | 2        | 0.63%   |
| Dell Inspiron          | 2        | 0.63%   |
| Biostar A320MH         | 2        | 0.63%   |
| ASUS TUF               | 2        | 0.63%   |
| ASUS P5Q               | 2        | 0.63%   |
| ASUS P5K               | 2        | 0.63%   |
| ASUS P5G41T-M          | 2        | 0.63%   |
| ASUS M5A78L            | 2        | 0.63%   |
| ASUS A68HM-PLUS        | 2        | 0.63%   |
| Shuttle XH61V          | 1        | 0.31%   |
| Sapphire Limited PURE  | 1        | 0.31%   |
| Positivo POS-PIH81DI   | 1        | 0.31%   |
| Pegatron NY537AA-ABA   | 1        | 0.31%   |
| Pegatron NE502AV-ABA   | 1        | 0.31%   |
| NCR xxxx-xxxx-xxxx     | 1        | 0.31%   |
| MSI WE136AA-UUZ        | 1        | 0.31%   |
| MSI Pro                | 1        | 0.31%   |
| MSI p6745nl            | 1        | 0.31%   |
| MSI MS-7D18            | 1        | 0.31%   |
| MSI MS-7D17            | 1        | 0.31%   |
| MSI MS-7C94            | 1        | 0.31%   |
| MSI MS-7C79            | 1        | 0.31%   |
| MSI MS-7C56            | 1        | 0.31%   |
| MSI MS-7C37            | 1        | 0.31%   |
| MSI MS-7B85            | 1        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 38       | 11.91%  |
| 2020 | 37       | 11.6%   |
| 2018 | 30       | 9.4%    |
| 2015 | 27       | 8.46%   |
| 2014 | 26       | 8.15%   |
| 2019 | 23       | 7.21%   |
| 2013 | 23       | 7.21%   |
| 2010 | 23       | 7.21%   |
| 2012 | 22       | 6.9%    |
| 2011 | 19       | 5.96%   |
| 2016 | 15       | 4.7%    |
| 2008 | 13       | 4.08%   |
| 2009 | 9        | 2.82%   |
| 2017 | 6        | 1.88%   |
| 2007 | 5        | 1.57%   |
| 2006 | 2        | 0.63%   |
| 2005 | 1        | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 319      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 302      | 94.08%  |
| Enabled  | 19       | 5.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 319      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 86       | 26.63%  |
| 8.01-16.0   | 84       | 26.01%  |
| 3.01-4.0    | 46       | 14.24%  |
| 4.01-8.0    | 45       | 13.93%  |
| 32.01-64.0  | 39       | 12.07%  |
| 1.01-2.0    | 10       | 3.1%    |
| 64.01-256.0 | 6        | 1.86%   |
| 24.01-32.0  | 4        | 1.24%   |
| 2.01-3.0    | 3        | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 151      | 45.9%   |
| 2.01-3.0   | 98       | 29.79%  |
| 3.01-4.0   | 37       | 11.25%  |
| 4.01-8.0   | 35       | 10.64%  |
| 8.01-16.0  | 4        | 1.22%   |
| 0.51-1.0   | 3        | 0.91%   |
| 16.01-24.0 | 1        | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 129      | 39.81%  |
| 2      | 97       | 29.94%  |
| 3      | 44       | 13.58%  |
| 4      | 21       | 6.48%   |
| 5      | 14       | 4.32%   |
| 6      | 11       | 3.4%    |
| 8      | 4        | 1.23%   |
| 7      | 2        | 0.62%   |
| 0      | 2        | 0.62%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 163      | 50.94%  |
| No        | 157      | 49.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 317      | 99.37%  |
| No        | 2        | 0.63%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 165      | 51.72%  |
| Yes       | 154      | 48.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 224      | 69.35%  |
| Yes       | 99       | 30.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 89       | 27.9%   |
| Germany      | 38       | 11.91%  |
| UK           | 28       | 8.78%   |
| Brazil       | 19       | 5.96%   |
| Netherlands  | 11       | 3.45%   |
| Canada       | 11       | 3.45%   |
| Italy        | 9        | 2.82%   |
| India        | 8        | 2.51%   |
| Spain        | 7        | 2.19%   |
| Poland       | 7        | 2.19%   |
| France       | 7        | 2.19%   |
| Hungary      | 6        | 1.88%   |
| Mexico       | 5        | 1.57%   |
| Turkey       | 4        | 1.25%   |
| Switzerland  | 4        | 1.25%   |
| South Africa | 4        | 1.25%   |
| Norway       | 4        | 1.25%   |
| Denmark      | 4        | 1.25%   |
| Australia    | 4        | 1.25%   |
| Argentina    | 4        | 1.25%   |
| Sweden       | 3        | 0.94%   |
| Russia       | 3        | 0.94%   |
| Malaysia     | 3        | 0.94%   |
| Croatia      | 3        | 0.94%   |
| Chile        | 3        | 0.94%   |
| Taiwan       | 2        | 0.63%   |
| Slovenia     | 2        | 0.63%   |
| Serbia       | 2        | 0.63%   |
| Romania      | 2        | 0.63%   |
| Portugal     | 2        | 0.63%   |
| New Zealand  | 2        | 0.63%   |
| El Salvador  | 2        | 0.63%   |
| Belgium      | 2        | 0.63%   |
| Austria      | 2        | 0.63%   |
| Vietnam      | 1        | 0.31%   |
| Peru         | 1        | 0.31%   |
| Panama       | 1        | 0.31%   |
| Mozambique   | 1        | 0.31%   |
| Jamaica      | 1        | 0.31%   |
| Israel       | 1        | 0.31%   |
| Indonesia    | 1        | 0.31%   |
| Guatemala    | 1        | 0.31%   |
| Greece       | 1        | 0.31%   |
| Czechia      | 1        | 0.31%   |
| Cyprus       | 1        | 0.31%   |
| China        | 1        | 0.31%   |
| Algeria      | 1        | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Berlin                 | 4        | 1.25%   |
| Munich                 | 3        | 0.94%   |
| Mentor                 | 3        | 0.94%   |
| Cape Town              | 3        | 0.94%   |
| Zagreb                 | 2        | 0.63%   |
| Vienna                 | 2        | 0.63%   |
| Vadodara               | 2        | 0.63%   |
| Twickenham             | 2        | 0.63%   |
| Stoke-on-Trent         | 2        | 0.63%   |
| Rio de Janeiro         | 2        | 0.63%   |
| Queens                 | 2        | 0.63%   |
| Milan                  | 2        | 0.63%   |
| Melbourne              | 2        | 0.63%   |
| Livingston             | 2        | 0.63%   |
| Kuala Lumpur           | 2        | 0.63%   |
| Hamburg                | 2        | 0.63%   |
| Drummondville          | 2        | 0.63%   |
| Dayton                 | 2        | 0.63%   |
| Dallas                 | 2        | 0.63%   |
| Contagem               | 2        | 0.63%   |
| Budapest               | 2        | 0.63%   |
| Bryan                  | 2        | 0.63%   |
| Bernau bei Berlin      | 2        | 0.63%   |
| Ankara                 | 2        | 0.63%   |
| Alexandria             | 2        | 0.63%   |
| Zurich                 | 1        | 0.31%   |
| Zephyrhills            | 1        | 0.31%   |
| Xalapa                 | 1        | 0.31%   |
| Wysoka Glogowska       | 1        | 0.31%   |
| Wylie                  | 1        | 0.31%   |
| Wuppertal              | 1        | 0.31%   |
| Winnipeg               | 1        | 0.31%   |
| Williamsburg           | 1        | 0.31%   |
| Wilkau-Hasslau         | 1        | 0.31%   |
| Wijnegem               | 1        | 0.31%   |
| Wigan                  | 1        | 0.31%   |
| West Valley City       | 1        | 0.31%   |
| Wellington             | 1        | 0.31%   |
| Warsaw                 | 1        | 0.31%   |
| Warrenton              | 1        | 0.31%   |
| Warner Robins          | 1        | 0.31%   |
| Wanstead               | 1        | 0.31%   |
| Vouvry                 | 1        | 0.31%   |
| Victoria               | 1        | 0.31%   |
| Vespasiano             | 1        | 0.31%   |
| Vechelde               | 1        | 0.31%   |
| Vancouver              | 1        | 0.31%   |
| Tustin                 | 1        | 0.31%   |
| Tucson                 | 1        | 0.31%   |
| Trujillo               | 1        | 0.31%   |
| Titusville             | 1        | 0.31%   |
| The Hague              | 1        | 0.31%   |
| Thame                  | 1        | 0.31%   |
| Tel Aviv               | 1        | 0.31%   |
| Taby                   | 1        | 0.31%   |
| São Bernardo do Campo | 1        | 0.31%   |
| Szombathely            | 1        | 0.31%   |
| Szigetvar              | 1        | 0.31%   |
| Sydney                 | 1        | 0.31%   |
| Suldalsosen            | 1        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 121      | 177    | 20.61%  |
| WDC                       | 103      | 136    | 17.55%  |
| Samsung Electronics       | 79       | 117    | 13.46%  |
| Sandisk                   | 38       | 45     | 6.47%   |
| Toshiba                   | 35       | 39     | 5.96%   |
| Kingston                  | 34       | 42     | 5.79%   |
| Hitachi                   | 30       | 35     | 5.11%   |
| Crucial                   | 17       | 22     | 2.9%    |
| PHISON                    | 12       | 14     | 2.04%   |
| Unknown                   | 9        | 15     | 1.53%   |
| A-DATA Technology         | 9        | 10     | 1.53%   |
| Silicon Motion            | 8        | 12     | 1.36%   |
| China                     | 8        | 8      | 1.36%   |
| HGST                      | 7        | 9      | 1.19%   |
| MAXTOR                    | 5        | 5      | 0.85%   |
| Lexar                     | 5        | 5      | 0.85%   |
| Intel                     | 5        | 5      | 0.85%   |
| Hewlett-Packard           | 5        | 6      | 0.85%   |
| SK Hynix                  | 4        | 5      | 0.68%   |
| PNY                       | 4        | 5      | 0.68%   |
| JMicron                   | 4        | 5      | 0.68%   |
| Gigabyte Technology       | 4        | 4      | 0.68%   |
| Micron Technology         | 3        | 3      | 0.51%   |
| XPG                       | 2        | 2      | 0.34%   |
| Super Talent              | 2        | 2      | 0.34%   |
| SABRENT                   | 2        | 2      | 0.34%   |
| Realtek Semiconductor     | 2        | 2      | 0.34%   |
| OCZ                       | 2        | 2      | 0.34%   |
| Micron/Crucial Technology | 2        | 2      | 0.34%   |
| KIOXIA-EXCERIA            | 2        | 2      | 0.34%   |
| KingFast                  | 2        | 2      | 0.34%   |
| Intenso                   | 2        | 2      | 0.34%   |
| XrayDisk                  | 1        | 1      | 0.17%   |
| Verbatim                  | 1        | 1      | 0.17%   |
| Team                      | 1        | 2      | 0.17%   |
| SuperSSpeed               | 1        | 2      | 0.17%   |
| SPCC                      | 1        | 1      | 0.17%   |
| Smartbuy                  | 1        | 1      | 0.17%   |
| Patriot                   | 1        | 1      | 0.17%   |
| OWC                       | 1        | 1      | 0.17%   |
| ORTIAL                    | 1        | 1      | 0.17%   |
| Netac                     | 1        | 1      | 0.17%   |
| MyDigitalSSD              | 1        | 1      | 0.17%   |
| Mushkin                   | 1        | 1      | 0.17%   |
| KingSpec                  | 1        | 2      | 0.17%   |
| INNOVATION IT             | 1        | 1      | 0.17%   |
| HS-SSD-C100               | 1        | 1      | 0.17%   |
| GOODRAM                   | 1        | 1      | 0.17%   |
| Dogfish                   | 1        | 2      | 0.17%   |
| Corsair                   | 1        | 1      | 0.17%   |
| Config                    | 1        | 1      | 0.17%   |
| Apacer                    | 1        | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 13       | 1.88%   |
| Kingston SA400S37240G 240GB SSD     | 12       | 1.74%   |
| WDC WD10EZEX-08WN4A0 1TB            | 10       | 1.45%   |
| Samsung SSD 860 EVO 500GB           | 10       | 1.45%   |
| Seagate ST3500418AS 500GB           | 8        | 1.16%   |
| Samsung NVMe SSD Drive 500GB        | 8        | 1.16%   |
| Seagate ST1000DM010-2EP102 1TB      | 7        | 1.01%   |
| Toshiba HDWD110 1TB                 | 6        | 0.87%   |
| Toshiba DT01ACA100 1TB              | 6        | 0.87%   |
| Seagate ST2000DM008-2FR102 2TB      | 6        | 0.87%   |
| Samsung SSD 840 EVO 250GB           | 6        | 0.87%   |
| Samsung NVMe SSD Drive 1TB          | 6        | 0.87%   |
| Kingston SA400S37120G 120GB SSD     | 6        | 0.87%   |
| Seagate ST3500413AS 500GB           | 5        | 0.72%   |
| Seagate ST2000DM001-9YN164 2TB      | 5        | 0.72%   |
| Seagate ST1000DM003-1ER162 1TB      | 5        | 0.72%   |
| Seagate ST1000DM003-1CH162 1TB      | 5        | 0.72%   |
| Samsung SSD 850 EVO 250GB           | 5        | 0.72%   |
| Samsung HD103UJ 1TB                 | 5        | 0.72%   |
| Phison NVMe SSD Drive 512GB         | 5        | 0.72%   |
| Phison NVMe SSD Drive 1TB           | 5        | 0.72%   |
| Kingston SV300S37A120G 120GB SSD    | 5        | 0.72%   |
| Crucial CT500MX500SSD1 500GB        | 5        | 0.72%   |
| Unknown SD/MMC/MS PRO 7GB           | 4        | 0.58%   |
| Toshiba DT01ACA050 500GB            | 4        | 0.58%   |
| Seagate Expansion 1TB               | 4        | 0.58%   |
| Sandisk NVMe SSD Drive 500GB        | 4        | 0.58%   |
| Samsung SSD 870 QVO 1TB             | 4        | 0.58%   |
| Samsung SSD 870 EVO 1TB             | 4        | 0.58%   |
| Samsung HD103SJ 1TB                 | 4        | 0.58%   |
| Crucial CT480BX500SSD1 480GB        | 4        | 0.58%   |
| WDC WD1600AAJS-75M0A0 160GB         | 3        | 0.43%   |
| WDC WD10EZEX-60M2NA0 1TB            | 3        | 0.43%   |
| WDC WD10EARS-00Y5B1 1TB             | 3        | 0.43%   |
| Toshiba DT01ACA200 2TB              | 3        | 0.43%   |
| Silicon Motion NVMe SSD Drive 128GB | 3        | 0.43%   |
| Seagate ST8000DM004-2CX188 8TB      | 3        | 0.43%   |
| Seagate ST4000DM004-2CV104 4TB      | 3        | 0.43%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 0.43%   |
| Seagate ST2000DM001-1CH164 2TB      | 3        | 0.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3        | 0.43%   |
| Seagate ST1000DX002-2DV162 1TB      | 3        | 0.43%   |
| Seagate Expansion Desk 5TB          | 3        | 0.43%   |
| Seagate Backup+ Hub BK 8TB          | 3        | 0.43%   |
| SanDisk SDSSDH3512G 512GB           | 3        | 0.43%   |
| SanDisk SDSSDA240G 240GB            | 3        | 0.43%   |
| Sandisk NVMe SSD Drive 1TB          | 3        | 0.43%   |
| Samsung SSD 860 EVO 250GB           | 3        | 0.43%   |
| Samsung SSD 850 EVO 500GB           | 3        | 0.43%   |
| Samsung SSD 840 EVO 120GB           | 3        | 0.43%   |
| PNY CS900 240GB SSD                 | 3        | 0.43%   |
| Gigabyte GP-GSTFS31120GNTD 120GB    | 3        | 0.43%   |
| Crucial CT240BX500SSD1 240GB        | 3        | 0.43%   |
| WDC WDS250G2B0A-00SM50 250GB SSD    | 2        | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2        | 0.29%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 2        | 0.29%   |
| WDC WD800JD-75MSA3 80GB             | 2        | 0.29%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 2        | 0.29%   |
| WDC WD5000AADS-00S9B0 500GB         | 2        | 0.29%   |
| WDC WD40EFRX-68WT0N0 4TB            | 2        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 120      | 166    | 37.85%  |
| WDC                 | 100      | 129    | 31.55%  |
| Toshiba             | 32       | 36     | 10.09%  |
| Hitachi             | 30       | 35     | 9.46%   |
| Samsung Electronics | 15       | 22     | 4.73%   |
| HGST                | 7        | 9      | 2.21%   |
| MAXTOR              | 5        | 5      | 1.58%   |
| Unknown             | 4        | 6      | 1.26%   |
| SABRENT             | 2        | 2      | 0.63%   |
| Hewlett-Packard     | 2        | 3      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 50       | 66     | 24.39%  |
| Kingston            | 31       | 38     | 15.12%  |
| SanDisk             | 29       | 35     | 14.15%  |
| Crucial             | 17       | 22     | 8.29%   |
| A-DATA Technology   | 9        | 10     | 4.39%   |
| China               | 8        | 8      | 3.9%    |
| WDC                 | 7        | 7      | 3.41%   |
| Lexar               | 5        | 5      | 2.44%   |
| PNY                 | 4        | 5      | 1.95%   |
| Gigabyte Technology | 4        | 4      | 1.95%   |
| Micron Technology   | 3        | 3      | 1.46%   |
| Intel               | 3        | 3      | 1.46%   |
| Hewlett-Packard     | 3        | 3      | 1.46%   |
| Toshiba             | 2        | 2      | 0.98%   |
| Super Talent        | 2        | 2      | 0.98%   |
| Seagate             | 2        | 2      | 0.98%   |
| OCZ                 | 2        | 2      | 0.98%   |
| KIOXIA-EXCERIA      | 2        | 2      | 0.98%   |
| Intenso             | 2        | 2      | 0.98%   |
| Verbatim            | 1        | 1      | 0.49%   |
| Team                | 1        | 2      | 0.49%   |
| SuperSSpeed         | 1        | 2      | 0.49%   |
| SPCC                | 1        | 1      | 0.49%   |
| Smartbuy            | 1        | 1      | 0.49%   |
| SK Hynix            | 1        | 1      | 0.49%   |
| PHISON              | 1        | 1      | 0.49%   |
| Patriot             | 1        | 1      | 0.49%   |
| OWC                 | 1        | 1      | 0.49%   |
| ORTIAL              | 1        | 1      | 0.49%   |
| Netac               | 1        | 1      | 0.49%   |
| MyDigitalSSD        | 1        | 1      | 0.49%   |
| Mushkin             | 1        | 1      | 0.49%   |
| KingSpec            | 1        | 2      | 0.49%   |
| JMicron             | 1        | 1      | 0.49%   |
| INNOVATION IT       | 1        | 1      | 0.49%   |
| GOODRAM             | 1        | 1      | 0.49%   |
| Dogfish             | 1        | 2      | 0.49%   |
| Corsair             | 1        | 1      | 0.49%   |
| Apacer              | 1        | 1      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 232      | 413    | 48.33%  |
| SSD     | 167      | 245    | 34.79%  |
| NVMe    | 63       | 82     | 13.13%  |
| Unknown | 17       | 24     | 3.54%   |
| MMC     | 1        | 2      | 0.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 305      | 639    | 76.63%  |
| NVMe | 63       | 82     | 15.83%  |
| SAS  | 29       | 43     | 7.29%   |
| MMC  | 1        | 2      | 0.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 234      | 353    | 52.12%  |
| 0.51-1.0   | 135      | 198    | 30.07%  |
| 1.01-2.0   | 46       | 60     | 10.24%  |
| 3.01-4.0   | 19       | 26     | 4.23%   |
| 4.01-10.0  | 9        | 12     | 2%      |
| 2.01-3.0   | 6        | 9      | 1.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 88       | 27.24%  |
| 251-500        | 69       | 21.36%  |
| 501-1000       | 53       | 16.41%  |
| 1001-2000      | 33       | 10.22%  |
| More than 3000 | 27       | 8.36%   |
| 51-100         | 24       | 7.43%   |
| 2001-3000      | 12       | 3.72%   |
| 21-50          | 7        | 2.17%   |
| 1-20           | 6        | 1.86%   |
| Unknown        | 4        | 1.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 123      | 37.16%  |
| 21-50          | 75       | 22.66%  |
| 51-100         | 37       | 11.18%  |
| 101-250        | 28       | 8.46%   |
| More than 3000 | 17       | 5.14%   |
| 501-1000       | 17       | 5.14%   |
| 1001-2000      | 15       | 4.53%   |
| 251-500        | 13       | 3.93%   |
| Unknown        | 4        | 1.21%   |
| 2001-3000      | 2        | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD3200AAKS-22B3A0 320GB    | 1        | 1      | 10%     |
| WDC WD30EFRX-68EUZN0 3TB       | 1        | 1      | 10%     |
| WDC WD10EZEX-21M2NA0 1TB       | 1        | 2      | 10%     |
| Toshiba MK3265GSX 320GB        | 1        | 1      | 10%     |
| Seagate ST9500420AS 500GB      | 1        | 1      | 10%     |
| Seagate ST4000DM004-2CV104 4TB | 1        | 1      | 10%     |
| Seagate ST3500514NS 500GB      | 1        | 1      | 10%     |
| Seagate ST3320620AS 320GB      | 1        | 1      | 10%     |
| Seagate ST2000DM001-9YN164 2TB | 1        | 1      | 10%     |
| Seagate ST2000DL003-9VT166 2TB | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 6      | 55.56%  |
| WDC     | 3        | 4      | 33.33%  |
| Toshiba | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 6      | 55.56%  |
| WDC     | 3        | 4      | 33.33%  |
| Toshiba | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 11     | 100%    |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 297      | 705    | 90%     |
| Works    | 25       | 50     | 7.58%   |
| Malfunc  | 8        | 11     | 2.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 210      | 50.48%  |
| AMD                          | 101      | 24.28%  |
| Samsung Electronics          | 21       | 5.05%   |
| ASMedia Technology           | 13       | 3.13%   |
| Phison Electronics           | 12       | 2.88%   |
| Sandisk                      | 9        | 2.16%   |
| Silicon Motion               | 8        | 1.92%   |
| Nvidia                       | 6        | 1.44%   |
| Marvell Technology Group     | 6        | 1.44%   |
| Kingston Technology Company  | 5        | 1.2%    |
| JMicron Technology           | 5        | 1.2%    |
| VIA Technologies             | 4        | 0.96%   |
| SK Hynix                     | 3        | 0.72%   |
| Silicon Image                | 3        | 0.72%   |
| Realtek Semiconductor        | 2        | 0.48%   |
| Micron/Crucial Technology    | 2        | 0.48%   |
| Broadcom / LSI               | 2        | 0.48%   |
| ADATA Technology             | 2        | 0.48%   |
| Toshiba America Info Systems | 1        | 0.24%   |
| Seagate Technology           | 1        | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 53       | 9.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 36       | 6.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 29       | 5.36%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 21       | 3.88%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 21       | 3.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 20       | 3.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 19       | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 19       | 3.51%   |
| Intel SATA Controller [RAID mode]                                                       | 17       | 3.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 17       | 3.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 2.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13       | 2.4%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 12       | 2.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 11       | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11       | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 1.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 1.66%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 7        | 1.29%   |
| AMD FCH SATA Controller D                                                               | 7        | 1.29%   |
| Phison E12 NVMe Controller                                                              | 6        | 1.11%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 1.11%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5        | 0.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.74%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 0.74%   |
| Nvidia MCP61 IDE                                                                        | 4        | 0.74%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.74%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.74%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 4        | 0.74%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 4        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.74%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 3        | 0.55%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 3        | 0.55%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 0.55%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 3        | 0.55%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 0.55%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 0.55%   |
| AMD FCH IDE Controller                                                                  | 3        | 0.55%   |
| Silicon Motion Non-Volatile memory controller                                           | 2        | 0.37%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 2        | 0.37%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.37%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.37%   |
| Sandisk Non-Volatile memory controller                                                  | 2        | 0.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.37%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 0.37%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 0.37%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.37%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.37%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2        | 0.37%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.37%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.37%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.37%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.37%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.37%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.37%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.37%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.37%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 0.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 243      | 56.78%  |
| IDE  | 91       | 21.26%  |
| NVMe | 63       | 14.72%  |
| RAID | 28       | 6.54%   |
| SCSI | 2        | 0.47%   |
| SAS  | 1        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 213      | 66.77%  |
| AMD    | 106      | 33.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 11       | 3.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 9        | 2.82%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 7        | 2.19%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 1.88%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 6        | 1.88%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5        | 1.57%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 1.57%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 1.57%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 1.57%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 1.25%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 4        | 1.25%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 4        | 1.25%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 1.25%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 4        | 1.25%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 1.25%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 1.25%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 1.25%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 1.25%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 3        | 0.94%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 3        | 0.94%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 0.94%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.94%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.94%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 0.94%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 3        | 0.94%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 0.94%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 0.94%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 3        | 0.94%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 0.94%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 0.94%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 0.94%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 0.94%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 0.94%   |
| AMD FX-6300 Six-Core Processor              | 3        | 0.94%   |
| AMD FX-6100 Six-Core Processor              | 3        | 0.94%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2        | 0.63%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.63%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.63%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 0.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.63%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 2        | 0.63%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 2        | 0.63%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.63%   |
| Intel Core i5-3340 CPU @ 3.10GHz            | 2        | 0.63%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 0.63%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 0.63%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.63%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 2        | 0.63%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 0.63%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 0.63%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 0.63%   |
| AMD Phenom II X4 965 Processor              | 2        | 0.63%   |
| AMD FX-8320E Eight-Core Processor           | 2        | 0.63%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 0.63%   |
| AMD FX-4100 Quad-Core Processor             | 2        | 0.63%   |
| AMD Athlon II X2 245 Processor              | 2        | 0.63%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1        | 0.31%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.31%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 1        | 0.31%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 66       | 20.69%  |
| Intel Core i7           | 38       | 11.91%  |
| Intel Core i3           | 34       | 10.66%  |
| AMD Ryzen 5             | 27       | 8.46%   |
| AMD FX                  | 18       | 5.64%   |
| Intel Xeon              | 12       | 3.76%   |
| Intel Core 2 Quad       | 12       | 3.76%   |
| AMD Ryzen 7             | 11       | 3.45%   |
| Intel Core 2 Duo        | 10       | 3.13%   |
| AMD Ryzen 3             | 10       | 3.13%   |
| Intel Pentium Dual-Core | 8        | 2.51%   |
| Intel Celeron           | 8        | 2.51%   |
| Intel Pentium Dual      | 7        | 2.19%   |
| Other                   | 5        | 1.57%   |
| Intel Pentium           | 4        | 1.25%   |
| AMD Ryzen 9             | 4        | 1.25%   |
| AMD Phenom II X4        | 4        | 1.25%   |
| AMD A10                 | 4        | 1.25%   |
| AMD Athlon II X3        | 3        | 0.94%   |
| AMD Athlon II X2        | 3        | 0.94%   |
| AMD A6                  | 3        | 0.94%   |
| Intel Pentium Gold      | 2        | 0.63%   |
| Intel Pentium 4         | 2        | 0.63%   |
| Intel Core i9           | 2        | 0.63%   |
| AMD GX                  | 2        | 0.63%   |
| AMD Athlon X4           | 2        | 0.63%   |
| AMD Athlon II X4        | 2        | 0.63%   |
| AMD Athlon 64           | 2        | 0.63%   |
| AMD A8                  | 2        | 0.63%   |
| Intel Pentium D         | 1        | 0.31%   |
| Intel Core m3           | 1        | 0.31%   |
| Intel Core 2            | 1        | 0.31%   |
| Intel Atom              | 1        | 0.31%   |
| AMD Ryzen 5 PRO         | 1        | 0.31%   |
| AMD Phenom II X6        | 1        | 0.31%   |
| AMD Phenom              | 1        | 0.31%   |
| AMD Opteron             | 1        | 0.31%   |
| AMD E1                  | 1        | 0.31%   |
| AMD Athlon 64 X2        | 1        | 0.31%   |
| AMD Athlon              | 1        | 0.31%   |
| AMD A4                  | 1        | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 143      | 44.83%  |
| 2      | 93       | 29.15%  |
| 6      | 42       | 13.17%  |
| 8      | 18       | 5.64%   |
| 3      | 10       | 3.13%   |
| 1      | 7        | 2.19%   |
| 12     | 3        | 0.94%   |
| 10     | 2        | 0.63%   |
| 16     | 1        | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 318      | 99.69%  |
| 2      | 1        | 0.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 160      | 50.16%  |
| 1      | 159      | 49.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 319      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 42       | 13.08%  |
| 0x306a9    | 28       | 8.72%   |
| 0x206a7    | 27       | 8.41%   |
| 0x1067a    | 23       | 7.17%   |
| Unknown    | 18       | 5.61%   |
| 0x08701021 | 17       | 5.3%    |
| 0x506e3    | 15       | 4.67%   |
| 0x06000852 | 13       | 4.05%   |
| 0x6fb      | 9        | 2.8%    |
| 0x0800820d | 9        | 2.8%    |
| 0x906ea    | 8        | 2.49%   |
| 0x6fd      | 7        | 2.18%   |
| 0x906e9    | 6        | 1.87%   |
| 0x06001119 | 6        | 1.87%   |
| 0x0600063e | 6        | 1.87%   |
| 0xa0655    | 5        | 1.56%   |
| 0x08701013 | 5        | 1.56%   |
| 0x08108109 | 4        | 1.25%   |
| 0x010000c8 | 4        | 1.25%   |
| 0xa0671    | 3        | 0.93%   |
| 0xa0653    | 3        | 0.93%   |
| 0x906eb    | 3        | 0.93%   |
| 0x20652    | 3        | 0.93%   |
| 0x0a201016 | 3        | 0.93%   |
| 0x08101016 | 3        | 0.93%   |
| 0x08001137 | 3        | 0.93%   |
| 0x0700010f | 3        | 0.93%   |
| 0x010000dc | 3        | 0.93%   |
| 0x010000db | 3        | 0.93%   |
| 0x30678    | 2        | 0.62%   |
| 0x10676    | 2        | 0.62%   |
| 0x08001138 | 2        | 0.62%   |
| 0x06006705 | 2        | 0.62%   |
| 0x06003106 | 2        | 0.62%   |
| 0x010000c7 | 2        | 0.62%   |
| 0xf4a      | 1        | 0.31%   |
| 0xf47      | 1        | 0.31%   |
| 0xf43      | 1        | 0.31%   |
| 0x906ed    | 1        | 0.31%   |
| 0x906ec    | 1        | 0.31%   |
| 0x90672    | 1        | 0.31%   |
| 0x806e9    | 1        | 0.31%   |
| 0x706a1    | 1        | 0.31%   |
| 0x6f6      | 1        | 0.31%   |
| 0x406f1    | 1        | 0.31%   |
| 0x406c4    | 1        | 0.31%   |
| 0x40651    | 1        | 0.31%   |
| 0x306f2    | 1        | 0.31%   |
| 0x306e4    | 1        | 0.31%   |
| 0x206d7    | 1        | 0.31%   |
| 0x206c2    | 1        | 0.31%   |
| 0x20655    | 1        | 0.31%   |
| 0x106e5    | 1        | 0.31%   |
| 0x106a4    | 1        | 0.31%   |
| 0x10677    | 1        | 0.31%   |
| 0x0a201204 | 1        | 0.31%   |
| 0x0a201009 | 1        | 0.31%   |
| 0x08600106 | 1        | 0.31%   |
| 0x0810100b | 1        | 0.31%   |
| 0x07030106 | 1        | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 47       | 14.73%  |
| SandyBridge   | 29       | 9.09%   |
| IvyBridge     | 29       | 9.09%   |
| Penryn        | 26       | 8.15%   |
| Zen 2         | 23       | 7.21%   |
| KabyLake      | 22       | 6.9%    |
| Piledriver    | 19       | 5.96%   |
| Core          | 17       | 5.33%   |
| Skylake       | 15       | 4.7%    |
| Zen+          | 14       | 4.39%   |
| K10           | 14       | 4.39%   |
| Zen           | 11       | 3.45%   |
| CometLake     | 8        | 2.51%   |
| Bulldozer     | 6        | 1.88%   |
| Zen 3         | 5        | 1.57%   |
| Westmere      | 5        | 1.57%   |
| Jaguar        | 4        | 1.25%   |
| Excavator     | 4        | 1.25%   |
| Silvermont    | 3        | 0.94%   |
| NetBurst      | 3        | 0.94%   |
| Nehalem       | 3        | 0.94%   |
| K8 Hammer     | 3        | 0.94%   |
| Icelake       | 3        | 0.94%   |
| Steamroller   | 2        | 0.63%   |
| Puma          | 1        | 0.31%   |
| Goldmont plus | 1        | 0.31%   |
| Broadwell     | 1        | 0.31%   |
| Unknown       | 1        | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 145      | 42.27%  |
| Intel            | 99       | 28.86%  |
| AMD              | 98       | 28.57%  |
| VIA Technologies | 1        | 0.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 24       | 6.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 16       | 4.62%   |
| Nvidia GK208B [GeForce GT 710]                                              | 14       | 4.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 11       | 3.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 2.31%   |
| Nvidia GK208B [GeForce GT 730]                                              | 7        | 2.02%   |
| Nvidia GF119 [GeForce GT 610]                                               | 7        | 2.02%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 7        | 2.02%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 6        | 1.73%   |
| Nvidia GF108 [GeForce GT 730]                                               | 6        | 1.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 1.73%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 1.45%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.45%   |
| Intel HD Graphics 530                                                       | 5        | 1.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 1.45%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.45%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 5        | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.16%   |
| Intel HD Graphics 630                                                       | 4        | 1.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 1.16%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 4        | 1.16%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 1.16%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.87%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 3        | 0.87%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3        | 0.87%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 0.87%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 0.87%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 0.87%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 0.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 0.87%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.58%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 2        | 0.58%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.58%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2        | 0.58%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.58%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.58%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 0.58%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 0.58%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 2        | 0.58%   |
| Nvidia GF116 [GeForce GT 545]                                               | 2        | 0.58%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 0.58%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 2        | 0.58%   |
| Nvidia G96C [GeForce GT 120]                                                | 2        | 0.58%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 0.58%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 0.58%   |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 2        | 0.58%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 2        | 0.58%   |
| AMD RV770 [Radeon HD 4850]                                                  | 2        | 0.58%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 2        | 0.58%   |
| AMD RS880 [Radeon HD 4250]                                                  | 2        | 0.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 0.58%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 0.58%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 0.58%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 2        | 0.58%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 2        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 138      | 42.99%  |
| 1 x AMD        | 89       | 27.73%  |
| 1 x Intel      | 80       | 24.92%  |
| Intel + Nvidia | 5        | 1.56%   |
| Intel + AMD    | 4        | 1.25%   |
| 2 x AMD        | 3        | 0.93%   |
| 1 x VIA        | 1        | 0.31%   |
| AMD + Nvidia   | 1        | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 204      | 63.95%  |
| Proprietary | 99       | 31.03%  |
| Unknown     | 16       | 5.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 118      | 36.76%  |
| 1.01-2.0   | 56       | 17.45%  |
| 0.51-1.0   | 47       | 14.64%  |
| 0.01-0.5   | 31       | 9.66%   |
| 3.01-4.0   | 25       | 7.79%   |
| 7.01-8.0   | 22       | 6.85%   |
| 5.01-6.0   | 11       | 3.43%   |
| 2.01-3.0   | 6        | 1.87%   |
| 8.01-16.0  | 4        | 1.25%   |
| 16.01-24.0 | 1        | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 51       | 15.99%  |
| Hewlett-Packard      | 27       | 8.46%   |
| Goldstar             | 27       | 8.46%   |
| Dell                 | 26       | 8.15%   |
| Acer                 | 24       | 7.52%   |
| AOC                  | 22       | 6.9%    |
| Philips              | 17       | 5.33%   |
| BenQ                 | 16       | 5.02%   |
| Ancor Communications | 12       | 3.76%   |
| LG Electronics       | 10       | 3.13%   |
| ViewSonic            | 7        | 2.19%   |
| Iiyama               | 6        | 1.88%   |
| Unknown              | 6        | 1.88%   |
| Unknown              | 5        | 1.57%   |
| HPN                  | 5        | 1.57%   |
| Vizio                | 4        | 1.25%   |
| Lenovo               | 4        | 1.25%   |
| Vestel               | 3        | 0.94%   |
| Sony                 | 3        | 0.94%   |
| Sceptre Tech         | 3        | 0.94%   |
| Microstep            | 3        | 0.94%   |
| Fujitsu Siemens      | 3        | 0.94%   |
| Toshiba              | 2        | 0.63%   |
| Panasonic            | 2        | 0.63%   |
| OEM                  | 2        | 0.63%   |
| NEC Computers        | 2        | 0.63%   |
| AUS                  | 2        | 0.63%   |
| Xiaomi               | 1        | 0.31%   |
| Westinghouse         | 1        | 0.31%   |
| WAN                  | 1        | 0.31%   |
| Viotek               | 1        | 0.31%   |
| Vestel Elektronik    | 1        | 0.31%   |
| Unknown (AAA)        | 1        | 0.31%   |
| Sharp                | 1        | 0.31%   |
| Seiki                | 1        | 0.31%   |
| Sceptre              | 1        | 0.31%   |
| Sanyo                | 1        | 0.31%   |
| PKB                  | 1        | 0.31%   |
| ONN                  | 1        | 0.31%   |
| Medion               | 1        | 0.31%   |
| Lenovo Group Limited | 1        | 0.31%   |
| KTC                  | 1        | 0.31%   |
| HCL                  | 1        | 0.31%   |
| HannStar Display     | 1        | 0.31%   |
| HannStar             | 1        | 0.31%   |
| Gigabyte Technology  | 1        | 0.31%   |
| GDH                  | 1        | 0.31%   |
| Gateway              | 1        | 0.31%   |
| CVT                  | 1        | 0.31%   |
| Belinea              | 1        | 0.31%   |
| BBY                  | 1        | 0.31%   |
| Arnos Instruments    | 1        | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown                                                                | 6        | 1.79%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                              | 3        | 0.89%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                    | 3        | 0.89%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3        | 0.89%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch              | 2        | 0.6%    |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 2        | 0.6%    |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch   | 2        | 0.6%    |
| Samsung Electronics LCD Monitor SAM07BC 1360x768                       | 2        | 0.6%    |
| OEM 32W_LCD_TV OEM3700 1920x1080                                       | 2        | 0.6%    |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch            | 2        | 0.6%    |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch              | 2        | 0.6%    |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                   | 2        | 0.6%    |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                     | 2        | 0.6%    |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                     | 2        | 0.6%    |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                      | 2        | 0.6%    |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 480x270mm 21.7-inch  | 2        | 0.6%    |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                       | 2        | 0.6%    |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                     | 1        | 0.3%    |
| Westinghouse SK-26H735S WDE6030 1366x768 576x324mm 26.0-inch           | 1        | 0.3%    |
| WAN 27MQ95FSHDRU WAN2700 2560x1440 600x330mm 27.0-inch                 | 1        | 0.3%    |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1        | 0.3%    |
| Vizio E220MV VIZ0062 1920x1080 509x286mm 23.0-inch                     | 1        | 0.3%    |
| Viotek GNV27DB VTK2700 2560x1440 597x336mm 27.0-inch                   | 1        | 0.3%    |
| ViewSonic VX3258 series VSCA037 1920x1080 700x390mm 31.5-inch          | 1        | 0.3%    |
| ViewSonic VG510s VSCCA18 1024x768 304x228mm 15.0-inch                  | 1        | 0.3%    |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch          | 1        | 0.3%    |
| ViewSonic VA2252 SERIES VSC7731 1920x1080 476x268mm 21.5-inch          | 1        | 0.3%    |
| ViewSonic LCD Monitor VP3268-4K 1920x1080                              | 1        | 0.3%    |
| ViewSonic LCD Monitor VA2718-FHD 1920x1080                             | 1        | 0.3%    |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                          | 1        | 0.3%    |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.3%    |
| Unknown LCD Monitor SAMSUNG 2464x900                                   | 1        | 0.3%    |
| Unknown LCD Monitor RTK                                                | 1        | 0.3%    |
| Unknown LCD Monitor OPD PX227H-HDMI1 4160x1440                         | 1        | 0.3%    |
| Unknown LCD Monitor LHC TE-3125 1920x1080                              | 1        | 0.3%    |
| Unknown LCD Monitor Kingston Technology 40'TV 1834x1031                | 1        | 0.3%    |
| Unknown LCD Monitor GKK MONITOR 1920x1080                              | 1        | 0.3%    |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch               | 1        | 0.3%    |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                       | 1        | 0.3%    |
| Toshiba LCD Monitor TV                                                 | 1        | 0.3%    |
| Sony TV SNYEE01 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.3%    |
| Sony TV *00 SNYA405 3840x2160 952x535mm 43.0-inch                      | 1        | 0.3%    |
| Sony LCD Monitor TV 3840x1080                                          | 1        | 0.3%    |
| Sony AVAMP SNY9301 1280x720 708x398mm 32.0-inch                        | 1        | 0.3%    |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                      | 1        | 0.3%    |
| Seiki SE19HT01 SEK0C76 1360x768 410x230mm 18.5-inch                    | 1        | 0.3%    |
| Sceptre Tech Sceptre M25 SPT09FB 1920x1080 540x300mm 24.3-inch         | 1        | 0.3%    |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                 | 1        | 0.3%    |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch          | 1        | 0.3%    |
| Sceptre LCD Monitor M24 3840x1080                                      | 1        | 0.3%    |
| Sceptre LCD Monitor M24                                                | 1        | 0.3%    |
| Sanyo LED MONITOR SAN952D 1920x1080 443x249mm 20.0-inch                | 1        | 0.3%    |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch      | 1        | 0.3%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1        | 0.3%    |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch      | 1        | 0.3%    |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch      | 1        | 0.3%    |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch      | 1        | 0.3%    |
| Samsung Electronics SyncMaster SAM0626 1920x1080                       | 1        | 0.3%    |
| Samsung Electronics SyncMaster SAM0604 1920x1080                       | 1        | 0.3%    |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch   | 1        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 138      | 43.81%  |
| 3840x2160 (4K)     | 28       | 8.89%   |
| 1680x1050 (WSXGA+) | 21       | 6.67%   |
| Unknown            | 20       | 6.35%   |
| 1366x768 (WXGA)    | 14       | 4.44%   |
| 3840x1080          | 11       | 3.49%   |
| 1600x900 (HD+)     | 11       | 3.49%   |
| 1280x1024 (SXGA)   | 11       | 3.49%   |
| 2560x1440 (QHD)    | 10       | 3.17%   |
| 1440x900 (WXGA+)   | 9        | 2.86%   |
| 1360x768           | 8        | 2.54%   |
| 1920x1200 (WUXGA)  | 7        | 2.22%   |
| 3440x1440          | 4        | 1.27%   |
| 5760x2160          | 2        | 0.63%   |
| 1920x540           | 2        | 0.63%   |
| 1024x768 (XGA)     | 2        | 0.63%   |
| 6400x1440          | 1        | 0.32%   |
| 4480x1440          | 1        | 0.32%   |
| 4160x1440          | 1        | 0.32%   |
| 3840x1600          | 1        | 0.32%   |
| 3780x2160          | 1        | 0.32%   |
| 3600x1080          | 1        | 0.32%   |
| 3360x1080          | 1        | 0.32%   |
| 3360x1050          | 1        | 0.32%   |
| 3200x1200          | 1        | 0.32%   |
| 3120x1050          | 1        | 0.32%   |
| 2944x1080          | 1        | 0.32%   |
| 2560x1600          | 1        | 0.32%   |
| 2560x1080          | 1        | 0.32%   |
| 2464x900           | 1        | 0.32%   |
| 1834x1031          | 1        | 0.32%   |
| 1600x1200          | 1        | 0.32%   |
| 1280x720 (HD)      | 1        | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 77       | 25.08%  |
| 24      | 32       | 10.42%  |
| 21      | 28       | 9.12%   |
| 27      | 27       | 8.79%   |
| 23      | 24       | 7.82%   |
| 22      | 20       | 6.51%   |
| 31      | 17       | 5.54%   |
| 19      | 16       | 5.21%   |
| 18      | 14       | 4.56%   |
| 20      | 12       | 3.91%   |
| 17      | 6        | 1.95%   |
| 84      | 4        | 1.3%    |
| 34      | 4        | 1.3%    |
| 32      | 3        | 0.98%   |
| 72      | 2        | 0.65%   |
| 54      | 2        | 0.65%   |
| 48      | 2        | 0.65%   |
| 41      | 2        | 0.65%   |
| 40      | 2        | 0.65%   |
| 33      | 2        | 0.65%   |
| 26      | 2        | 0.65%   |
| 15      | 2        | 0.65%   |
| 74      | 1        | 0.33%   |
| 52      | 1        | 0.33%   |
| 43      | 1        | 0.33%   |
| 42      | 1        | 0.33%   |
| 37      | 1        | 0.33%   |
| 36      | 1        | 0.33%   |
| 25      | 1        | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 79       | 26.6%   |
| 501-600     | 77       | 25.93%  |
| Unknown     | 77       | 25.93%  |
| 601-700     | 22       | 7.41%   |
| 701-800     | 10       | 3.37%   |
| 351-400     | 7        | 2.36%   |
| 1501-2000   | 7        | 2.36%   |
| 301-350     | 6        | 2.02%   |
| 1001-1500   | 5        | 1.68%   |
| 901-1000    | 4        | 1.35%   |
| 801-900     | 3        | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 153      | 53.31%  |
| Unknown | 75       | 26.13%  |
| 16/10   | 40       | 13.94%  |
| 5/4     | 9        | 3.14%   |
| 21/9    | 5        | 1.74%   |
| 4/3     | 3        | 1.05%   |
| 6/5     | 1        | 0.35%   |
| 32/9    | 1        | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 86       | 28.38%  |
| Unknown        | 77       | 25.41%  |
| 151-200        | 34       | 11.22%  |
| 301-350        | 27       | 8.91%   |
| 351-500        | 26       | 8.58%   |
| 141-150        | 16       | 5.28%   |
| 251-300        | 14       | 4.62%   |
| More than 1000 | 11       | 3.63%   |
| 501-1000       | 9        | 2.97%   |
| 101-110        | 2        | 0.66%   |
| 121-130        | 1        | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 146      | 50.34%  |
| Unknown | 77       | 26.55%  |
| 101-120 | 40       | 13.79%  |
| 1-50    | 13       | 4.48%   |
| 121-160 | 13       | 4.48%   |
| 161-240 | 1        | 0.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 253      | 78.82%  |
| 2     | 46       | 14.33%  |
| 0     | 19       | 5.92%   |
| 3     | 3        | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 200      | 42.74%  |
| Intel                           | 121      | 25.85%  |
| Qualcomm Atheros                | 38       | 8.12%   |
| Ralink Technology               | 24       | 5.13%   |
| TP-Link                         | 15       | 3.21%   |
| Ralink                          | 11       | 2.35%   |
| Broadcom                        | 10       | 2.14%   |
| Nvidia                          | 6        | 1.28%   |
| Samsung Electronics             | 3        | 0.64%   |
| Qualcomm Atheros Communications | 3        | 0.64%   |
| Microsoft                       | 3        | 0.64%   |
| Edimax Technology               | 3        | 0.64%   |
| DisplayLink                     | 3        | 0.64%   |
| D-Link System                   | 3        | 0.64%   |
| Xiaomi                          | 2        | 0.43%   |
| NetGear                         | 2        | 0.43%   |
| Motorola PCS                    | 2        | 0.43%   |
| MEDIATEK                        | 2        | 0.43%   |
| Marvell Technology Group        | 2        | 0.43%   |
| Huawei Technologies             | 2        | 0.43%   |
| Broadcom Limited                | 2        | 0.43%   |
| Research In Motion              | 1        | 0.21%   |
| Panasonic (Matsushita)          | 1        | 0.21%   |
| OPPO Electronics                | 1        | 0.21%   |
| Linksys                         | 1        | 0.21%   |
| Lenovo                          | 1        | 0.21%   |
| Google                          | 1        | 0.21%   |
| Gemtek                          | 1        | 0.21%   |
| Exar                            | 1        | 0.21%   |
| D-Link                          | 1        | 0.21%   |
| Arduino SA                      | 1        | 0.21%   |
| ADMtek                          | 1        | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 163      | 30.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24       | 4.54%   |
| Intel Wi-Fi 6 AX200                                               | 13       | 2.46%   |
| Intel Ethernet Connection I217-LM                                 | 13       | 2.46%   |
| Ralink MT7601U Wireless Adapter                                   | 11       | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 1.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9        | 1.7%    |
| Intel I211 Gigabit Network Connection                             | 9        | 1.7%    |
| Realtek 802.11ac NIC                                              | 8        | 1.51%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 1.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 6        | 1.13%   |
| Intel Ethernet Controller I225-V                                  | 6        | 1.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5        | 0.95%   |
| Ralink RT5370 Wireless Adapter                                    | 5        | 0.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5        | 0.95%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5        | 0.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 4        | 0.76%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.76%   |
| Nvidia MCP61 Ethernet                                             | 4        | 0.76%   |
| Intel Wireless 7265                                               | 4        | 0.76%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.76%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 0.76%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 3        | 0.57%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 3        | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3        | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.57%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3        | 0.57%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3        | 0.57%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 3        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.57%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 3        | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.38%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 0.38%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2        | 0.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 0.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 0.38%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                         | 2        | 0.38%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2        | 0.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2        | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.38%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.38%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2        | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.38%   |
| Intel Wireless-AC 9260                                            | 2        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 42       | 24.14%  |
| Intel                           | 39       | 22.41%  |
| Ralink Technology               | 24       | 13.79%  |
| Qualcomm Atheros                | 18       | 10.34%  |
| TP-Link                         | 15       | 8.62%   |
| Ralink                          | 11       | 6.32%   |
| Broadcom                        | 4        | 2.3%    |
| Qualcomm Atheros Communications | 3        | 1.72%   |
| Microsoft                       | 3        | 1.72%   |
| Edimax Technology               | 3        | 1.72%   |
| NetGear                         | 2        | 1.15%   |
| D-Link System                   | 2        | 1.15%   |
| Broadcom Limited                | 2        | 1.15%   |
| Panasonic (Matsushita)          | 1        | 0.57%   |
| MEDIATEK                        | 1        | 0.57%   |
| Linksys                         | 1        | 0.57%   |
| Gemtek                          | 1        | 0.57%   |
| D-Link                          | 1        | 0.57%   |
| ADMtek                          | 1        | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 13       | 7.39%   |
| Ralink MT7601U Wireless Adapter                                      | 11       | 6.25%   |
| Realtek 802.11ac NIC                                                 | 8        | 4.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 6        | 3.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 5        | 2.84%   |
| Ralink RT5370 Wireless Adapter                                       | 5        | 2.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 5        | 2.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 5        | 2.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 4        | 2.27%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 4        | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4        | 2.27%   |
| Intel Wireless 7265                                                  | 4        | 2.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 3        | 1.7%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 3        | 1.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 3        | 1.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 3        | 1.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 1.7%    |
| Qualcomm Atheros AR9271 802.11n                                      | 3        | 1.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 3        | 1.7%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 3        | 1.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2        | 1.14%   |
| TP-Link 802.11ac WLAN Adapter                                        | 2        | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 2        | 1.14%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 2        | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2        | 1.14%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                            | 2        | 1.14%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                            | 2        | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 2        | 1.14%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 1.14%   |
| Intel Wireless-AC 9260                                               | 2        | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2        | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2        | 1.14%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT2870]             | 2        | 1.14%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 2        | 1.14%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 2        | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2        | 1.14%   |
| TP-Link Archer T4U ver.3                                             | 1        | 0.57%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 0.57%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 1        | 0.57%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                      | 1        | 0.57%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1        | 0.57%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                               | 1        | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 0.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 0.57%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter             | 1        | 0.57%   |
| Realtek RTL8187 Wireless Adapter                                     | 1        | 0.57%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller            | 1        | 0.57%   |
| Ralink RT5372 Wireless Adapter                                       | 1        | 0.57%   |
| Ralink RT2501/RT2573 Wireless Adapter                                | 1        | 0.57%   |
| Ralink RT5592 PCIe Wireless Network Adapter                          | 1        | 0.57%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1        | 0.57%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                 | 1        | 0.57%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 1        | 0.57%   |
| Ralink RT2600 802.11 MIMO                                            | 1        | 0.57%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 1        | 0.57%   |
| Ralink RT2500 Wireless 802.11bg                                      | 1        | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1        | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 190      | 56.05%  |
| Intel                    | 98       | 28.91%  |
| Qualcomm Atheros         | 21       | 6.19%   |
| Nvidia                   | 6        | 1.77%   |
| Broadcom                 | 6        | 1.77%   |
| Samsung Electronics      | 3        | 0.88%   |
| DisplayLink              | 3        | 0.88%   |
| Xiaomi                   | 2        | 0.59%   |
| Marvell Technology Group | 2        | 0.59%   |
| Huawei Technologies      | 2        | 0.59%   |
| Research In Motion       | 1        | 0.29%   |
| OPPO Electronics         | 1        | 0.29%   |
| Motorola PCS             | 1        | 0.29%   |
| MediaTek                 | 1        | 0.29%   |
| Google                   | 1        | 0.29%   |
| D-Link System            | 1        | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 163      | 46.7%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24       | 6.88%   |
| Intel Ethernet Connection I217-LM                                 | 13       | 3.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 2.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9        | 2.58%   |
| Intel I211 Gigabit Network Connection                             | 9        | 2.58%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 2.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1.72%   |
| Intel Ethernet Controller I225-V                                  | 6        | 1.72%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 1.15%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.15%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.15%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.15%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.86%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 3        | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.57%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.57%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2        | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.57%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                             | 2        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.57%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.57%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.29%   |
| Research In Motion BlackBerry                                     | 1        | 0.29%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.29%   |
| OPPO realme X50 Pro 5G                                            | 1        | 0.29%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.29%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.29%   |
| Motorola PCS moto g 5G                                            | 1        | 0.29%   |
| MediaTek WP5 Pro                                                  | 1        | 0.29%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.29%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.29%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.29%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.29%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.29%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.29%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.29%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller     | 1        | 0.29%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 0.29%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.29%   |
| Huawei ELE-AL00                                                   | 1        | 0.29%   |
| Huawei E353/E3131                                                 | 1        | 0.29%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 0.29%   |
| DisplayLink PR08 DisplayPort Dock                                 | 1        | 0.29%   |
| DisplayLink LAPDOCK                                               | 1        | 0.29%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1        | 0.29%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 317      | 66.6%   |
| WiFi     | 155      | 32.56%  |
| Modem    | 2        | 0.42%   |
| Unknown  | 2        | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 308      | 70%     |
| WiFi     | 131      | 29.77%  |
| Unknown  | 1        | 0.23%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 213      | 66.77%  |
| 2     | 94       | 29.47%  |
| 3     | 8        | 2.51%   |
| 0     | 3        | 0.94%   |
| 5     | 1        | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 225      | 69.66%  |
| Yes  | 98       | 30.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 30       | 29.41%  |
| Cambridge Silicon Radio         | 25       | 24.51%  |
| Realtek Semiconductor           | 17       | 16.67%  |
| Broadcom                        | 10       | 9.8%    |
| ASUSTek Computer                | 5        | 4.9%    |
| Qualcomm Atheros Communications | 4        | 3.92%   |
| Dynex                           | 2        | 1.96%   |
| Dell                            | 2        | 1.96%   |
| National Semiconductor          | 1        | 0.98%   |
| Micro Star International        | 1        | 0.98%   |
| MediaTek                        | 1        | 0.98%   |
| Lite-On Technology              | 1        | 0.98%   |
| IMC Networks                    | 1        | 0.98%   |
| Foxconn / Hon Hai               | 1        | 0.98%   |
| Belkin Components               | 1        | 0.98%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 25       | 24.51%  |
| Realtek Bluetooth Radio                                  | 16       | 15.69%  |
| Intel Bluetooth Device                                   | 9        | 8.82%   |
| Intel Bluetooth wireless interface                       | 7        | 6.86%   |
| Intel AX200 Bluetooth                                    | 7        | 6.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 6        | 5.88%   |
| Intel Wireless-AC 3168 Bluetooth                         | 4        | 3.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 3        | 2.94%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 2        | 1.96%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 2        | 1.96%   |
| Dell BT Mini-Receiver                                    | 2        | 1.96%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 2        | 1.96%   |
| ASUS Qualcomm Bluetooth 4.1                              | 2        | 1.96%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 2        | 1.96%   |
| Realtek RTL8723B Bluetooth                               | 1        | 0.98%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1        | 0.98%   |
| Qualcomm Atheros Bluetooth                               | 1        | 0.98%   |
| National Bluetooth Dongle                                | 1        | 0.98%   |
| Micro Star International Bluetooth Device                | 1        | 0.98%   |
| MediaTek Wireless_Device                                 | 1        | 0.98%   |
| Lite-On Bluetooth Device                                 | 1        | 0.98%   |
| IMC Networks Bluetooth Radio                             | 1        | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1        | 0.98%   |
| Broadcom HP Bluetooth Module                             | 1        | 0.98%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 1        | 0.98%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 1        | 0.98%   |
| ASUS Bluetooth Radio                                     | 1        | 0.98%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 203      | 36.98%  |
| AMD                                  | 142      | 25.87%  |
| Nvidia                               | 137      | 24.95%  |
| C-Media Electronics                  | 12       | 2.19%   |
| Creative Labs                        | 7        | 1.28%   |
| Logitech                             | 5        | 0.91%   |
| Razer USA                            | 4        | 0.73%   |
| JMTek                                | 4        | 0.73%   |
| Texas Instruments                    | 3        | 0.55%   |
| VIA Technologies                     | 2        | 0.36%   |
| Plantronics                          | 2        | 0.36%   |
| Kingston Technology                  | 2        | 0.36%   |
| GN Netcom                            | 2        | 0.36%   |
| ASUSTek Computer                     | 2        | 0.36%   |
| XMOS                                 | 1        | 0.18%   |
| Valve Software                       | 1        | 0.18%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.18%   |
| Tenx Technology                      | 1        | 0.18%   |
| Swissonic                            | 1        | 0.18%   |
| SteelSeries ApS                      | 1        | 0.18%   |
| Silicon Labs                         | 1        | 0.18%   |
| SAVITECH                             | 1        | 0.18%   |
| ROCCAT                               | 1        | 0.18%   |
| Numark                               | 1        | 0.18%   |
| Microsoft                            | 1        | 0.18%   |
| Micronas                             | 1        | 0.18%   |
| LucidSound                           | 1        | 0.18%   |
| Klipsch Audio                        | 1        | 0.18%   |
| Insignia (Best Buy)                  | 1        | 0.18%   |
| iConnectivity                        | 1        | 0.18%   |
| Google                               | 1        | 0.18%   |
| GEMBIRD                              | 1        | 0.18%   |
| Focusrite-Novation                   | 1        | 0.18%   |
| FIFINE Microphones                   | 1        | 0.18%   |
| Corsair                              | 1        | 0.18%   |
| Asahi Kasei Microsystems             | 1        | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 37       | 5.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 34       | 5.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 31       | 4.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 27       | 4.31%   |
| AMD Starship/Matisse HD Audio Controller                                          | 26       | 4.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 23       | 3.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 23       | 3.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 19       | 3.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 14       | 2.23%   |
| Intel Cannon Lake PCH cAVS                                                        | 13       | 2.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 13       | 2.07%   |
| AMD FCH Azalia Controller                                                         | 13       | 2.07%   |
| Nvidia GF108 High Definition Audio Controller                                     | 11       | 1.75%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 11       | 1.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 11       | 1.75%   |
| Nvidia TU116 High Definition Audio Controller                                     | 9        | 1.44%   |
| Nvidia TU106 High Definition Audio Controller                                     | 8        | 1.28%   |
| Nvidia High Definition Audio Controller                                           | 8        | 1.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 8        | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 8        | 1.28%   |
| Intel 200 Series PCH HD Audio                                                     | 8        | 1.28%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 8        | 1.28%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 8        | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                                     | 7        | 1.12%   |
| Nvidia GF119 HDMI Audio Controller                                                | 7        | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7        | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 7        | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 6        | 0.96%   |
| Nvidia GM204 High Definition Audio Controller                                     | 6        | 0.96%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 6        | 0.96%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6        | 0.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 6        | 0.96%   |
| AMD Navi 10 HDMI Audio                                                            | 6        | 0.96%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 6        | 0.96%   |
| Nvidia GK104 HDMI Audio Controller                                                | 5        | 0.8%    |
| AMD Kabini HDMI/DP Audio                                                          | 5        | 0.8%    |
| Nvidia MCP61 High Definition Audio                                                | 4        | 0.64%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 0.64%   |
| JMTek USB PnP Audio Device                                                        | 4        | 0.64%   |
| Intel Comet Lake PCH cAVS                                                         | 4        | 0.64%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 0.64%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 4        | 0.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 4        | 0.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3        | 0.48%   |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 0.48%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 0.48%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 0.48%   |
| Nvidia GF116 High Definition Audio Controller                                     | 3        | 0.48%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 0.48%   |
| C-Media Electronics USB Advanced Audio Device                                     | 3        | 0.48%   |
| AMD Trinity HDMI Audio Controller                                                 | 3        | 0.48%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                        | 3        | 0.48%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 0.48%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 3        | 0.48%   |
| Razer USA Razer USB Audio Controller                                              | 2        | 0.32%   |
| Nvidia GM200 High Definition Audio                                                | 2        | 0.32%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 0.32%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.32%   |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 0.32%   |
| Nvidia Audio device                                                               | 2        | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 9        | 22.5%   |
| Corsair             | 6        | 15%     |
| G.Skill             | 5        | 12.5%   |
| Samsung Electronics | 4        | 10%     |
| Kingston            | 4        | 10%     |
| SK Hynix            | 3        | 7.5%    |
| Crucial             | 3        | 7.5%    |
| Ramaxel Technology  | 2        | 5%      |
| Team                | 1        | 2.5%    |
| Micron Technology   | 1        | 2.5%    |
| Goldkey             | 1        | 2.5%    |
| F7852C80            | 1        | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s       | 2        | 4.55%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s    | 1        | 2.27%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                  | 1        | 2.27%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                       | 1        | 2.27%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s               | 1        | 2.27%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1        | 2.27%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1        | 2.27%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s               | 1        | 2.27%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s                | 1        | 2.27%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                     | 1        | 2.27%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s               | 1        | 2.27%   |
| Unknown RAM Module 2048MB DIMM DDR2 1333MT/s               | 1        | 2.27%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s         | 1        | 2.27%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s      | 1        | 2.27%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s       | 1        | 2.27%   |
| SK Hynix RAM HMT325U6EFR8C-PB 2048MB DIMM DDR3 1600MT/s    | 1        | 2.27%   |
| Samsung RAM Module 8192MB DIMM DDR4 2133MT/s               | 1        | 2.27%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s     | 1        | 2.27%   |
| Samsung RAM M378B1G73EB0-CK0 8192MB DIMM DDR3 1600MT/s     | 1        | 2.27%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s        | 1        | 2.27%   |
| Ramaxel RAM RMUA5110ME78HAF-2666 8192MB DIMM DDR4 2667MT/s | 1        | 2.27%   |
| Ramaxel RAM RMR5030ED58E8W1600 2048MB DIMM DDR3 1600MT/s   | 1        | 2.27%   |
| Micron RAM 8KTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s     | 1        | 2.27%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1867MT/s        | 1        | 2.27%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s      | 1        | 2.27%   |
| Kingston RAM 99U5469-046.A00LF 4GB SODIMM DDR3 1333MT/s    | 1        | 2.27%   |
| Kingston RAM 99U5403-065.A00LF 4GB DIMM DDR3 1600MT/s      | 1        | 2.27%   |
| Goldkey RAM BKH200UD25608-1333 2048MB DIMM DDR3 1400MT/s   | 1        | 2.27%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 2933MT/s        | 1        | 2.27%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s        | 1        | 2.27%   |
| G.Skill RAM F4-2666C15-8GVR 8GB DIMM DDR4 2800MT/s         | 1        | 2.27%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2400MT/s         | 1        | 2.27%   |
| G.Skill RAM F4-2400C15-8GIS 8192MB DIMM DDR4 2400MT/s      | 1        | 2.27%   |
| F7852C80 RAM F641GU67F1600G0000 8GB DIMM DDR3 1333MT/s     | 1        | 2.27%   |
| Crucial RAM CT51264BA160BJ.C8F 4096MB DIMM DDR3 1600MT/s   | 1        | 2.27%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s      | 1        | 2.27%   |
| Crucial RAM BL8G32C16U4R.M8FE 8GB DIMM DDR4 2133MT/s       | 1        | 2.27%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s     | 1        | 2.27%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s       | 1        | 2.27%   |
| Corsair RAM CMK32GX4M4D3600C18 8192MB DIMM DDR4 3600MT/s   | 1        | 2.27%   |
| Corsair RAM CMH32GX4M2D3600C18 16384MB DIMM DDR4 2133MT/s  | 1        | 2.27%   |
| Corsair RAM CMD16GX4M2A2666C15 8192MB DIMM DDR4 2667MT/s   | 1        | 2.27%   |
| Corsair RAM CMD16GX3M2A18 8192MB DIMM DDR3 1333MT/s        | 1        | 2.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 16       | 44.44%  |
| DDR4    | 14       | 38.89%  |
| Unknown | 4        | 11.11%  |
| DDR2    | 1        | 2.78%   |
| DDR     | 1        | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 35       | 97.22%  |
| SODIMM | 1        | 2.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 18       | 48.65%  |
| 4096  | 12       | 32.43%  |
| 2048  | 4        | 10.81%  |
| 16384 | 2        | 5.41%   |
| 32768 | 1        | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 10       | 26.32%  |
| 1333  | 7        | 18.42%  |
| 2133  | 5        | 13.16%  |
| 3200  | 3        | 7.89%   |
| 2667  | 3        | 7.89%   |
| 2400  | 3        | 7.89%   |
| 3600  | 1        | 2.63%   |
| 2933  | 1        | 2.63%   |
| 2800  | 1        | 2.63%   |
| 1867  | 1        | 2.63%   |
| 1800  | 1        | 2.63%   |
| 1400  | 1        | 2.63%   |
| 667   | 1        | 2.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 4        | 33.33%  |
| Hewlett-Packard     | 3        | 25%     |
| Samsung Electronics | 2        | 16.67%  |
| Brother Industries  | 2        | 16.67%  |
| Seiko Epson         | 1        | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson XP-202 203 206 Series | 1        | 8.33%   |
| Samsung SCX-483x 5x3x Series      | 1        | 8.33%   |
| Samsung SCX-3400 Series           | 1        | 8.33%   |
| HP OfficeJet 4650 series          | 1        | 8.33%   |
| HP LaserJet Professional P1102w   | 1        | 8.33%   |
| HP DeskJet 2700 series            | 1        | 8.33%   |
| Canon TS3100 series               | 1        | 8.33%   |
| Canon TR4500 series               | 1        | 8.33%   |
| Canon PIXMA MG2500 Series         | 1        | 8.33%   |
| Canon LiDE 400                    | 1        | 8.33%   |
| Brother MFC-9140CDN               | 1        | 8.33%   |
| Brother DCP-L2540DW               | 1        | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 50%     |
| Canon           | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| HP ScanJet 2400c     | 1        | 50%     |
| Canon CanoScan 8800F | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 15       | 27.78%  |
| Microdia                      | 6        | 11.11%  |
| Microsoft                     | 5        | 9.26%   |
| Samsung Electronics           | 4        | 7.41%   |
| Generalplus Technology        | 3        | 5.56%   |
| ARC International             | 3        | 5.56%   |
| Sunplus Innovation Technology | 2        | 3.7%    |
| Realtek Semiconductor         | 2        | 3.7%    |
| Razer USA                     | 2        | 3.7%    |
| Xiongmai                      | 1        | 1.85%   |
| Teslong Camera                | 1        | 1.85%   |
| Sonix Technology              | 1        | 1.85%   |
| Jieli Technology              | 1        | 1.85%   |
| HD WEBCAM                     | 1        | 1.85%   |
| Guillemot                     | 1        | 1.85%   |
| Genesys Logic                 | 1        | 1.85%   |
| Creative Technology           | 1        | 1.85%   |
| Chicony Electronics           | 1        | 1.85%   |
| Arkmicro Technologies         | 1        | 1.85%   |
| Apple                         | 1        | 1.85%   |
| Alcor Micro                   | 1        | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)               | 4        | 7.41%   |
| Logitech HD Pro Webcam C920           | 4        | 7.41%   |
| Microsoft LifeCam HD-3000             | 3        | 5.56%   |
| Logitech Webcam C270                  | 3        | 5.56%   |
| Generalplus GENERAL WEBCAM            | 3        | 5.56%   |
| ARC International Camera              | 3        | 5.56%   |
| Razer USA Gaming Webcam [Kiyo]        | 2        | 3.7%    |
| Xiongmai web camera                   | 1        | 1.85%   |
| Teslong Camera Teslong Camera         | 1        | 1.85%   |
| Sunplus HD 720P webcam                | 1        | 1.85%   |
| Sunplus Depstech webcam MIC           | 1        | 1.85%   |
| Sonix USB 2.0 Camera                  | 1        | 1.85%   |
| Realtek WEB CAMERA M9 Pro             | 1        | 1.85%   |
| Realtek HP High Definition 1MP Webcam | 1        | 1.85%   |
| Microsoft Microsoft?� LifeCam Cinema  | 1        | 1.85%   |
| Microsoft LifeCam VX-2000             | 1        | 1.85%   |
| Microdia Webcam Vitade AF             | 1        | 1.85%   |
| Microdia USB Live camera              | 1        | 1.85%   |
| Microdia USB 2.0 Camera               | 1        | 1.85%   |
| Microdia PC Camera (SN9C110)          | 1        | 1.85%   |
| Microdia Integrated Camera            | 1        | 1.85%   |
| Microdia Camera                       | 1        | 1.85%   |
| Logitech Webcam Pro 9000              | 1        | 1.85%   |
| Logitech Webcam C260                  | 1        | 1.85%   |
| Logitech QuickCam Pro for Notebooks   | 1        | 1.85%   |
| Logitech Portable Webcam C905         | 1        | 1.85%   |
| Logitech HD Webcam C910               | 1        | 1.85%   |
| Logitech HD Webcam C615               | 1        | 1.85%   |
| Logitech HD Webcam B990               | 1        | 1.85%   |
| Logitech C922 Pro Stream Webcam       | 1        | 1.85%   |
| Jieli USB PHY 2.0                     | 1        | 1.85%   |
| HD WEBCAM HD WEBCAM                   | 1        | 1.85%   |
| Guillemot Hercules HD Sunset          | 1        | 1.85%   |
| Genesys Logic Camera                  | 1        | 1.85%   |
| Creative Live! Cam Chat HD [VF0700]   | 1        | 1.85%   |
| Chicony CNF8050 Webcam                | 1        | 1.85%   |
| Arkmicro Acme CA04                    | 1        | 1.85%   |
| Apple iPhone 5/5C/5S/6/SE             | 1        | 1.85%   |
| Alcor Micro USB 2.0 PC Camera         | 1        | 1.85%   |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Reiner SCT Kartensysteme | 1        | 33.33%  |
| Alcor Micro              | 1        | 33.33%  |
| Advanced Card Systems    | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack e-com/pinpad | 1        | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader             | 1        | 33.33%  |
| Advanced Card Systems ACR39U                    | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 265      | 82.55%  |
| 1     | 49       | 15.26%  |
| 2     | 7        | 2.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 27       | 45.76%  |
| Graphics card            | 22       | 37.29%  |
| Unassigned class         | 2        | 3.39%   |
| Multimedia controller    | 2        | 3.39%   |
| Chipcard                 | 2        | 3.39%   |
| Storage/ide              | 1        | 1.69%   |
| Sound                    | 1        | 1.69%   |
| Communication controller | 1        | 1.69%   |
| Camera                   | 1        | 1.69%   |

