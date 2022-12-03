Linux in Italy - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

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

Total: 3291

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MPG Z390 GAMING PRO CARB... | [f8a7663037](https://linux-hardware.org/?probe=f8a7663037) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [f0dba35258](https://linux-hardware.org/?probe=f0dba35258) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [baa969bf8b](https://linux-hardware.org/?probe=baa969bf8b) | Nov 30, 2022 |
| MSI           | Boston                      | [0564f7ed2d](https://linux-hardware.org/?probe=0564f7ed2d) | Nov 30, 2022 |
| HP            | 304Ah                       | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| MSI           | Z170A GAMING M3             | [dfe92c80c1](https://linux-hardware.org/?probe=dfe92c80c1) | Nov 30, 2022 |
| IBM           | MSI-9151 Boards             | [720ff829b9](https://linux-hardware.org/?probe=720ff829b9) | Nov 29, 2022 |
| HP            | 3048h                       | [6f5a8d1a09](https://linux-hardware.org/?probe=6f5a8d1a09) | Nov 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [719921de81](https://linux-hardware.org/?probe=719921de81) | Nov 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [f998b6a0d9](https://linux-hardware.org/?probe=f998b6a0d9) | Nov 29, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [d5702f8b2d](https://linux-hardware.org/?probe=d5702f8b2d) | Nov 29, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [640a031786](https://linux-hardware.org/?probe=640a031786) | Nov 29, 2022 |
| HP            | 843B                        | [19bd35484c](https://linux-hardware.org/?probe=19bd35484c) | Nov 28, 2022 |
| ASUSTek       | H110M-K                     | [becbfa5cc7](https://linux-hardware.org/?probe=becbfa5cc7) | Nov 28, 2022 |
| Gigabyte      | M61PME-S2P                  | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| MSI           | H510I PRO WIFI              | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | [02c62a5eb8](https://linux-hardware.org/?probe=02c62a5eb8) | Nov 27, 2022 |
| Dell          | 042P49 A01                  | [8f510e55e2](https://linux-hardware.org/?probe=8f510e55e2) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | [6206268283](https://linux-hardware.org/?probe=6206268283) | Nov 27, 2022 |
| Gigabyte      | F2A78M-HD2                  | [b5260b5609](https://linux-hardware.org/?probe=b5260b5609) | Nov 26, 2022 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [eb0921d1f6](https://linux-hardware.org/?probe=eb0921d1f6) | Nov 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [07363955de](https://linux-hardware.org/?probe=07363955de) | Nov 26, 2022 |
| HP            | 3397                        | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| Pegatron      | 2ACF                        | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 3397                        | [0605f9214a](https://linux-hardware.org/?probe=0605f9214a) | Nov 25, 2022 |
| ASUSTek       | P8H61-I LX/RM/SI            | [61cfa154b0](https://linux-hardware.org/?probe=61cfa154b0) | Nov 24, 2022 |
| MSI           | H81M-E33                    | [80ec8663ac](https://linux-hardware.org/?probe=80ec8663ac) | Nov 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [d6fe192013](https://linux-hardware.org/?probe=d6fe192013) | Nov 24, 2022 |
| ASRock        | 960GC-GS FX                 | [30081f61ca](https://linux-hardware.org/?probe=30081f61ca) | Nov 24, 2022 |
| ASRock        | 960GC-GS FX                 | [9e33d3b8f1](https://linux-hardware.org/?probe=9e33d3b8f1) | Nov 24, 2022 |
| Foxconn       | 2ADA                        | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| MSI           | B450M-A PRO MAX             | [e4904d14cc](https://linux-hardware.org/?probe=e4904d14cc) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [4b44aea106](https://linux-hardware.org/?probe=4b44aea106) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [1c232e6d70](https://linux-hardware.org/?probe=1c232e6d70) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [bd9c6238bc](https://linux-hardware.org/?probe=bd9c6238bc) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [393b7f7d3a](https://linux-hardware.org/?probe=393b7f7d3a) | Nov 23, 2022 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | [14c0f082d8](https://linux-hardware.org/?probe=14c0f082d8) | Nov 22, 2022 |
| ASRock        | 960GC-GS FX                 | [d0bd92a5e0](https://linux-hardware.org/?probe=d0bd92a5e0) | Nov 22, 2022 |
| ASRock        | 960GC-GS FX                 | [b4cc2dc00b](https://linux-hardware.org/?probe=b4cc2dc00b) | Nov 22, 2022 |
| HP            | 83E2                        | [b04e1014da](https://linux-hardware.org/?probe=b04e1014da) | Nov 22, 2022 |
| ASUSTek       | M4A78T-E                    | [aef32a0e69](https://linux-hardware.org/?probe=aef32a0e69) | Nov 22, 2022 |
| ASUSTek       | PRIME B460M-A               | [4ed396ae3f](https://linux-hardware.org/?probe=4ed396ae3f) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f13d80cf0b](https://linux-hardware.org/?probe=f13d80cf0b) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| Gigabyte      | B450 AORUS M                | [7ccd7842c1](https://linux-hardware.org/?probe=7ccd7842c1) | Nov 21, 2022 |
| ASUSTek       | P5E3 Deluxe                 | [c14020107c](https://linux-hardware.org/?probe=c14020107c) | Nov 21, 2022 |
| HP            | 2AF3                        | [babcb0bf93](https://linux-hardware.org/?probe=babcb0bf93) | Nov 21, 2022 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | [07ca09898f](https://linux-hardware.org/?probe=07ca09898f) | Nov 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [835c000337](https://linux-hardware.org/?probe=835c000337) | Nov 20, 2022 |
| Acer          | Nitro N50-620               | [ecd8e9ec1b](https://linux-hardware.org/?probe=ecd8e9ec1b) | Nov 20, 2022 |
| HP            | 8767 A                      | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f1724d63d5](https://linux-hardware.org/?probe=f1724d63d5) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| ASUSTek       | Z170-K                      | [1af696c23c](https://linux-hardware.org/?probe=1af696c23c) | Nov 19, 2022 |
| MSI           | H510M-A PRO                 | [e913feb821](https://linux-hardware.org/?probe=e913feb821) | Nov 18, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [a61b66e4ed](https://linux-hardware.org/?probe=a61b66e4ed) | Nov 18, 2022 |
| Lenovo        | 31900058 STD                | [1408b2dc5f](https://linux-hardware.org/?probe=1408b2dc5f) | Nov 18, 2022 |
| Acer          | E946GZ                      | [f084e099d5](https://linux-hardware.org/?probe=f084e099d5) | Nov 17, 2022 |
| Mediacom      | M-AO241/64                  | [8312099aa4](https://linux-hardware.org/?probe=8312099aa4) | Nov 16, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [e2492ba1c1](https://linux-hardware.org/?probe=e2492ba1c1) | Nov 16, 2022 |
| ASRock        | J3455B-ITX                  | [2a85d4fa3a](https://linux-hardware.org/?probe=2a85d4fa3a) | Nov 15, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [a7e5419c89](https://linux-hardware.org/?probe=a7e5419c89) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| ASUSTek       | A58M-A/USB3                 | [f6342a3d18](https://linux-hardware.org/?probe=f6342a3d18) | Nov 15, 2022 |
| Intel         | DB75EN AAG39650-400         | [07d6aa9adc](https://linux-hardware.org/?probe=07d6aa9adc) | Nov 14, 2022 |
| Huanan        | X99-F8                      | [503cf4b0ea](https://linux-hardware.org/?probe=503cf4b0ea) | Nov 14, 2022 |
| HP            | 802F                        | [8e7dbc3f9f](https://linux-hardware.org/?probe=8e7dbc3f9f) | Nov 14, 2022 |
| HP            | 802F                        | [89441a53f7](https://linux-hardware.org/?probe=89441a53f7) | Nov 14, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [c3573fb12b](https://linux-hardware.org/?probe=c3573fb12b) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | [e1f2995c6f](https://linux-hardware.org/?probe=e1f2995c6f) | Nov 14, 2022 |
| HP            | 3397                        | [035eb81bdf](https://linux-hardware.org/?probe=035eb81bdf) | Nov 13, 2022 |
| MSI           | Z97A GAMING 7               | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| Gigabyte      | Z77X-UP7                    | [e0edc946f9](https://linux-hardware.org/?probe=e0edc946f9) | Nov 13, 2022 |
| MSI           | ZH77A-G43                   | [a8f49c1ad8](https://linux-hardware.org/?probe=a8f49c1ad8) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [7d72f2fa26](https://linux-hardware.org/?probe=7d72f2fa26) | Nov 12, 2022 |
| MSI           | MS-7309                     | [bd4d6c72e3](https://linux-hardware.org/?probe=bd4d6c72e3) | Nov 12, 2022 |
| Gigabyte      | 970A-DS3                    | [7c25342680](https://linux-hardware.org/?probe=7c25342680) | Nov 12, 2022 |
| ASUSTek       | P8P67 EVO                   | [c033c311f3](https://linux-hardware.org/?probe=c033c311f3) | Nov 12, 2022 |
| Unknown       | 775i65G                     | [b872a779af](https://linux-hardware.org/?probe=b872a779af) | Nov 12, 2022 |
| ASUSTek       | P5L1394                     | [d4c699bf10](https://linux-hardware.org/?probe=d4c699bf10) | Nov 11, 2022 |
| Unknown       | 1.0                         | [d07852e419](https://linux-hardware.org/?probe=d07852e419) | Nov 11, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [4fddb7605a](https://linux-hardware.org/?probe=4fddb7605a) | Nov 11, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [779188af6a](https://linux-hardware.org/?probe=779188af6a) | Nov 11, 2022 |
| Intel         | DQ57TM AAE70931-403         | [1759cf3bec](https://linux-hardware.org/?probe=1759cf3bec) | Nov 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b4aa454d9a](https://linux-hardware.org/?probe=b4aa454d9a) | Nov 10, 2022 |
| ASRock        | B365 Pro4                   | [3069280223](https://linux-hardware.org/?probe=3069280223) | Nov 10, 2022 |
| MSI           | H61M-P31/W8                 | [933683bc04](https://linux-hardware.org/?probe=933683bc04) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | [d0cac7ee7b](https://linux-hardware.org/?probe=d0cac7ee7b) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | [cf0ed7acab](https://linux-hardware.org/?probe=cf0ed7acab) | Nov 10, 2022 |
| ASUSTek       | P5KPL-SE                    | [dafce5f727](https://linux-hardware.org/?probe=dafce5f727) | Nov 09, 2022 |
| MSI           | X299 RAIDER                 | [b7d117fc31](https://linux-hardware.org/?probe=b7d117fc31) | Nov 09, 2022 |
| ASRock        | X370 Gaming K4              | [f0634d863e](https://linux-hardware.org/?probe=f0634d863e) | Nov 08, 2022 |
| ASRock        | Z77 Pro4-M                  | [3a4a75d603](https://linux-hardware.org/?probe=3a4a75d603) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | [e7fb74c85e](https://linux-hardware.org/?probe=e7fb74c85e) | Nov 08, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | [92cf5ed7b4](https://linux-hardware.org/?probe=92cf5ed7b4) | Nov 07, 2022 |
| Dell          | 0X231R A01                  | [5846e23f06](https://linux-hardware.org/?probe=5846e23f06) | Nov 07, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [ddca3f4758](https://linux-hardware.org/?probe=ddca3f4758) | Nov 06, 2022 |
| ASRock        | B365 Pro4                   | [6c37cfce25](https://linux-hardware.org/?probe=6c37cfce25) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [958f0c8551](https://linux-hardware.org/?probe=958f0c8551) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [98a3c2457d](https://linux-hardware.org/?probe=98a3c2457d) | Nov 05, 2022 |
| Gigabyte      | 990XA-UD3                   | [a06275a0f2](https://linux-hardware.org/?probe=a06275a0f2) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [1cf71a1b5c](https://linux-hardware.org/?probe=1cf71a1b5c) | Nov 05, 2022 |
| ASRock        | B450M Pro4                  | [97e52df467](https://linux-hardware.org/?probe=97e52df467) | Nov 05, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [67369107e1](https://linux-hardware.org/?probe=67369107e1) | Nov 05, 2022 |
| AMI           | Cherry Trail CR             | [f731a55cc1](https://linux-hardware.org/?probe=f731a55cc1) | Nov 05, 2022 |
| ASRock        | J3455B-ITX                  | [deda12dd1f](https://linux-hardware.org/?probe=deda12dd1f) | Nov 05, 2022 |
| ASRock        | B450M Steel Legend          | [1534af11b9](https://linux-hardware.org/?probe=1534af11b9) | Nov 05, 2022 |
| HP            | 8053                        | [20c566d4e7](https://linux-hardware.org/?probe=20c566d4e7) | Nov 05, 2022 |
| ASUSTek       | P8H67                       | [0d98e4b3b3](https://linux-hardware.org/?probe=0d98e4b3b3) | Nov 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6494c493cb](https://linux-hardware.org/?probe=6494c493cb) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [f027f3a4e2](https://linux-hardware.org/?probe=f027f3a4e2) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [cb9374e939](https://linux-hardware.org/?probe=cb9374e939) | Nov 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [97d8c001ef](https://linux-hardware.org/?probe=97d8c001ef) | Nov 03, 2022 |
| Lenovo        | 3728 SDK0J40700 WIN 3258... | [6700909ef7](https://linux-hardware.org/?probe=6700909ef7) | Nov 03, 2022 |
| HP            | 8054                        | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| Dell          | 0W5363                      | [20c6f0d689](https://linux-hardware.org/?probe=20c6f0d689) | Nov 03, 2022 |
| Dell          | 0W5363                      | [7400a9beb1](https://linux-hardware.org/?probe=7400a9beb1) | Nov 03, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [e4206174ca](https://linux-hardware.org/?probe=e4206174ca) | Nov 03, 2022 |
| ASUSTek       | H81T                        | [7598a634e6](https://linux-hardware.org/?probe=7598a634e6) | Nov 02, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [c9041d22be](https://linux-hardware.org/?probe=c9041d22be) | Nov 02, 2022 |
| ASUSTek       | B85-PLUS                    | [dd24c26ffa](https://linux-hardware.org/?probe=dd24c26ffa) | Nov 02, 2022 |
| Dell          | 0GWHMW A01                  | [732eaeede7](https://linux-hardware.org/?probe=732eaeede7) | Nov 02, 2022 |
| MSI           | B75A-IE35                   | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| MSI           | Z370 GAMING PLUS            | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| ASUSTek       | BM2AD_D510MT_D310MT         | [8f2b0bc926](https://linux-hardware.org/?probe=8f2b0bc926) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| MSI           | H81M-E33                    | [ee4c33d7b1](https://linux-hardware.org/?probe=ee4c33d7b1) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | [a14fa00a56](https://linux-hardware.org/?probe=a14fa00a56) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | [bfa1db2eb1](https://linux-hardware.org/?probe=bfa1db2eb1) | Nov 01, 2022 |
| ASUSTek       | H61M-K                      | [ca5a47c66a](https://linux-hardware.org/?probe=ca5a47c66a) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z87              | [d39c952932](https://linux-hardware.org/?probe=d39c952932) | Nov 01, 2022 |
| MSI           | X570-A PRO                  | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| ASUSTek       | CG8480                      | [0f7c1dc1cf](https://linux-hardware.org/?probe=0f7c1dc1cf) | Oct 31, 2022 |
| MSI           | H110M PRO-VD PLUS           | [ced3229025](https://linux-hardware.org/?probe=ced3229025) | Oct 31, 2022 |
| HP            | 3397                        | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [e309413fea](https://linux-hardware.org/?probe=e309413fea) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | [13741c554f](https://linux-hardware.org/?probe=13741c554f) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | [e6e466cd8f](https://linux-hardware.org/?probe=e6e466cd8f) | Oct 31, 2022 |
| MSI           | 990FXA-GD80                 | [baaa1111ec](https://linux-hardware.org/?probe=baaa1111ec) | Oct 31, 2022 |
| Gigabyte      | X570S AERO G                | [600587e66a](https://linux-hardware.org/?probe=600587e66a) | Oct 31, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3fbcca75d5](https://linux-hardware.org/?probe=3fbcca75d5) | Oct 30, 2022 |
| ASRock        | FM2A88X-ITX+                | [08cf9e2ccd](https://linux-hardware.org/?probe=08cf9e2ccd) | Oct 30, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [c128f85cdc](https://linux-hardware.org/?probe=c128f85cdc) | Oct 30, 2022 |
| ASUSTek       | A88XM-PLUS                  | [10aa435a0b](https://linux-hardware.org/?probe=10aa435a0b) | Oct 30, 2022 |
| ASRock        | FM2A88X-ITX+                | [e28a25b18a](https://linux-hardware.org/?probe=e28a25b18a) | Oct 30, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [1f7df5159e](https://linux-hardware.org/?probe=1f7df5159e) | Oct 30, 2022 |
| ASUSTek       | P6TD DELUXE                 | [faa61ea635](https://linux-hardware.org/?probe=faa61ea635) | Oct 30, 2022 |
| MSI           | Z77A-G45 Thunderbolt        | [fa189cf50b](https://linux-hardware.org/?probe=fa189cf50b) | Oct 30, 2022 |
| HP            | 1495                        | [b62f9d83b9](https://linux-hardware.org/?probe=b62f9d83b9) | Oct 30, 2022 |
| MSI           | A320M-A PRO MAX             | [80d6d99bcf](https://linux-hardware.org/?probe=80d6d99bcf) | Oct 30, 2022 |
| HP            | 18E7                        | [d4a4ad62cb](https://linux-hardware.org/?probe=d4a4ad62cb) | Oct 29, 2022 |
| MSI           | B450M PRO-M2 MAX            | [6549416d9d](https://linux-hardware.org/?probe=6549416d9d) | Oct 29, 2022 |
| ASRock        | B450M Pro4                  | [0616272661](https://linux-hardware.org/?probe=0616272661) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| ASRock        | 890GX Extreme3              | [ff1af2eaf0](https://linux-hardware.org/?probe=ff1af2eaf0) | Oct 29, 2022 |
| ASUSTek       | LEUCITE3                    | [f51161d005](https://linux-hardware.org/?probe=f51161d005) | Oct 29, 2022 |
| ASUSTek       | LEUCITE3                    | [4c4e1b6871](https://linux-hardware.org/?probe=4c4e1b6871) | Oct 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [95af9b0439](https://linux-hardware.org/?probe=95af9b0439) | Oct 29, 2022 |
| Gigabyte      | EX58-UD3R                   | [0d76cc7e31](https://linux-hardware.org/?probe=0d76cc7e31) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| Acer          | MCP7A                       | [c14a31f6ab](https://linux-hardware.org/?probe=c14a31f6ab) | Oct 28, 2022 |
| Unknown       | 775V88+                     | [f1a685b497](https://linux-hardware.org/?probe=f1a685b497) | Oct 28, 2022 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [8c85b7ec2e](https://linux-hardware.org/?probe=8c85b7ec2e) | Oct 28, 2022 |
| Gigabyte      | H310M S2H x.x               | [acdf2a172f](https://linux-hardware.org/?probe=acdf2a172f) | Oct 28, 2022 |
| MSI           | H81M-P33                    | [16a78334cd](https://linux-hardware.org/?probe=16a78334cd) | Oct 28, 2022 |
| MSI           | Z370 KRAIT GAMING           | [cbf597cec1](https://linux-hardware.org/?probe=cbf597cec1) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [1759cbebe1](https://linux-hardware.org/?probe=1759cbebe1) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| Intel         | DH61DL AAG14066-205         | [9031f7b82b](https://linux-hardware.org/?probe=9031f7b82b) | Oct 27, 2022 |
| Lenovo        | 0B98401 PRO                 | [99f9bbd5ad](https://linux-hardware.org/?probe=99f9bbd5ad) | Oct 27, 2022 |
| MSI           | H110M PRO-VD PLUS           | [d3c4092754](https://linux-hardware.org/?probe=d3c4092754) | Oct 27, 2022 |
| Gigabyte      | Z77X-UP7                    | [c33d6de923](https://linux-hardware.org/?probe=c33d6de923) | Oct 27, 2022 |
| Packard Be... | IMEDIA S3810                | [f492fb9369](https://linux-hardware.org/?probe=f492fb9369) | Oct 27, 2022 |
| MSI           | H81M-E33                    | [f0613bfce8](https://linux-hardware.org/?probe=f0613bfce8) | Oct 27, 2022 |
| MSI           | X58 Pro                     | [6c449246c8](https://linux-hardware.org/?probe=6c449246c8) | Oct 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [b682a38061](https://linux-hardware.org/?probe=b682a38061) | Oct 27, 2022 |
| HP            | 1589                        | [4a15b6de0f](https://linux-hardware.org/?probe=4a15b6de0f) | Oct 27, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d2debd1dab](https://linux-hardware.org/?probe=d2debd1dab) | Oct 26, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [97d2bacb5d](https://linux-hardware.org/?probe=97d2bacb5d) | Oct 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [82fcc1ecc7](https://linux-hardware.org/?probe=82fcc1ecc7) | Oct 26, 2022 |
| Intel         | H55                         | [f634aefb9a](https://linux-hardware.org/?probe=f634aefb9a) | Oct 26, 2022 |
| MSI           | ZH77A-G43                   | [ff43c876e9](https://linux-hardware.org/?probe=ff43c876e9) | Oct 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [469345600b](https://linux-hardware.org/?probe=469345600b) | Oct 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [06f33f301b](https://linux-hardware.org/?probe=06f33f301b) | Oct 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8a718e0ade](https://linux-hardware.org/?probe=8a718e0ade) | Oct 26, 2022 |
| ASRock        | H77 Pro4/MVP                | [94d8bc13bb](https://linux-hardware.org/?probe=94d8bc13bb) | Oct 26, 2022 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | [2bed8fe9b1](https://linux-hardware.org/?probe=2bed8fe9b1) | Oct 26, 2022 |
| HP            | 1494                        | [fa63090109](https://linux-hardware.org/?probe=fa63090109) | Oct 26, 2022 |
| HP            | 8509                        | [81bfb5a782](https://linux-hardware.org/?probe=81bfb5a782) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Gigabyte      | B450 AORUS M                | [1603f6064b](https://linux-hardware.org/?probe=1603f6064b) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [705e51d33e](https://linux-hardware.org/?probe=705e51d33e) | Oct 25, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [50c68d9bb4](https://linux-hardware.org/?probe=50c68d9bb4) | Oct 25, 2022 |
| ASUSTek       | Z87-PRO                     | [a48316f550](https://linux-hardware.org/?probe=a48316f550) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [824eb583d8](https://linux-hardware.org/?probe=824eb583d8) | Oct 25, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [958c0a2ae7](https://linux-hardware.org/?probe=958c0a2ae7) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| Gigabyte      | H97M-D3H                    | [72532e08fe](https://linux-hardware.org/?probe=72532e08fe) | Oct 25, 2022 |
| Dell          | 040DDP A01                  | [cc0b502ddf](https://linux-hardware.org/?probe=cc0b502ddf) | Oct 25, 2022 |
| ASUSTek       | H110M-K                     | [06c00dc8d5](https://linux-hardware.org/?probe=06c00dc8d5) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| ASRock        | AB350 Pro4                  | [82ee095168](https://linux-hardware.org/?probe=82ee095168) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | [a38f9baa55](https://linux-hardware.org/?probe=a38f9baa55) | Oct 25, 2022 |
| MSI           | Z170A GAMING M5             | [b5dcdb6844](https://linux-hardware.org/?probe=b5dcdb6844) | Oct 25, 2022 |
| ASRock        | 4Core1600-GLAN/M            | [33bf20761f](https://linux-hardware.org/?probe=33bf20761f) | Oct 25, 2022 |
| Unknown       | 1.0                         | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-P                | [0eb9c3ebff](https://linux-hardware.org/?probe=0eb9c3ebff) | Oct 25, 2022 |
| Pegatron      | Benicia                     | [3735dca311](https://linux-hardware.org/?probe=3735dca311) | Oct 25, 2022 |
| HP            | 805F                        | [eaa3994f86](https://linux-hardware.org/?probe=eaa3994f86) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [ab5d5a6170](https://linux-hardware.org/?probe=ab5d5a6170) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [040714e135](https://linux-hardware.org/?probe=040714e135) | Oct 25, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [6a9d81591f](https://linux-hardware.org/?probe=6a9d81591f) | Oct 25, 2022 |
| Lenovo        | 318E NOK                    | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [ef9fdf5dcd](https://linux-hardware.org/?probe=ef9fdf5dcd) | Oct 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [0c63b974e1](https://linux-hardware.org/?probe=0c63b974e1) | Oct 25, 2022 |
| ASUSTek       | M3N78-VM                    | [1c68e176b6](https://linux-hardware.org/?probe=1c68e176b6) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Gigabyte      | F2A78M-HD2                  | [6cffc39cfc](https://linux-hardware.org/?probe=6cffc39cfc) | Oct 25, 2022 |
| Gigabyte      | Z690 UD DDR4                | [c838769296](https://linux-hardware.org/?probe=c838769296) | Oct 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [7b59865f68](https://linux-hardware.org/?probe=7b59865f68) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| MSI           | H61M-P31/W8                 | [7ba2ecf5f0](https://linux-hardware.org/?probe=7ba2ecf5f0) | Oct 25, 2022 |
| Acer          | Veriton M2631 V:1.0         | [1d5e3aa9f0](https://linux-hardware.org/?probe=1d5e3aa9f0) | Oct 25, 2022 |
| MSI           | Z97-G55 SLI                 | [25ddd5274f](https://linux-hardware.org/?probe=25ddd5274f) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [74ca211759](https://linux-hardware.org/?probe=74ca211759) | Oct 25, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [aa4a86445a](https://linux-hardware.org/?probe=aa4a86445a) | Oct 25, 2022 |
| ASRock        | B450 Gaming K4              | [122a54b0c2](https://linux-hardware.org/?probe=122a54b0c2) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | [a55a6ef774](https://linux-hardware.org/?probe=a55a6ef774) | Oct 25, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [52a4b91a1e](https://linux-hardware.org/?probe=52a4b91a1e) | Oct 25, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c77d3dfeba](https://linux-hardware.org/?probe=c77d3dfeba) | Oct 25, 2022 |
| Gigabyte      | Z87-HD3                     | [da7fe35832](https://linux-hardware.org/?probe=da7fe35832) | Oct 25, 2022 |
| MSI           | Z170A GAMING M7             | [3326f67ecf](https://linux-hardware.org/?probe=3326f67ecf) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [65c39a9702](https://linux-hardware.org/?probe=65c39a9702) | Oct 24, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [a0e0f661af](https://linux-hardware.org/?probe=a0e0f661af) | Oct 24, 2022 |
| ASRock        | H370M-ITX/ac                | [fa925dcefb](https://linux-hardware.org/?probe=fa925dcefb) | Oct 24, 2022 |
| MSI           | H510M-A PRO                 | [02e8dbe21d](https://linux-hardware.org/?probe=02e8dbe21d) | Oct 24, 2022 |
| ASUSTek       | PRIME Z390-P                | [261e670072](https://linux-hardware.org/?probe=261e670072) | Oct 24, 2022 |
| ASRock        | Z170 Gaming K4              | [184139e7bc](https://linux-hardware.org/?probe=184139e7bc) | Oct 24, 2022 |
| ASUSTek       | H81M-C                      | [1deed99314](https://linux-hardware.org/?probe=1deed99314) | Oct 24, 2022 |
| ASUSTek       | M4A78T-E                    | [ee86cdac2a](https://linux-hardware.org/?probe=ee86cdac2a) | Oct 24, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [df05c11ff4](https://linux-hardware.org/?probe=df05c11ff4) | Oct 24, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [581fb21345](https://linux-hardware.org/?probe=581fb21345) | Oct 24, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [aa82a1f3c9](https://linux-hardware.org/?probe=aa82a1f3c9) | Oct 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [c76c6f0a0e](https://linux-hardware.org/?probe=c76c6f0a0e) | Oct 24, 2022 |
| Gigabyte      | B365M D2V                   | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [f42213926f](https://linux-hardware.org/?probe=f42213926f) | Oct 24, 2022 |
| Dell          | 0M5WNK A00                  | [fad0f2f50e](https://linux-hardware.org/?probe=fad0f2f50e) | Oct 24, 2022 |
| ASUSTek       | Maximus VI EXTREME          | [e5264df501](https://linux-hardware.org/?probe=e5264df501) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [b63ff47508](https://linux-hardware.org/?probe=b63ff47508) | Oct 24, 2022 |
| ASUSTek       | H97-PLUS                    | [aaf3b72437](https://linux-hardware.org/?probe=aaf3b72437) | Oct 24, 2022 |
| ASUSTek       | H170 PRO GAMING             | [905f41afd6](https://linux-hardware.org/?probe=905f41afd6) | Oct 24, 2022 |
| Acer          | Aspire MC605 v1.0           | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| HP            | 3048h                       | [3c3f7eda5e](https://linux-hardware.org/?probe=3c3f7eda5e) | Oct 24, 2022 |
| ASRock        | X370 Gaming K4              | [5658dbff1b](https://linux-hardware.org/?probe=5658dbff1b) | Oct 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [1dea808353](https://linux-hardware.org/?probe=1dea808353) | Oct 24, 2022 |
| Gigabyte      | B85M-D3H                    | [f4182ec2e9](https://linux-hardware.org/?probe=f4182ec2e9) | Oct 24, 2022 |
| Gigabyte      | H310M H                     | [3a8627fb53](https://linux-hardware.org/?probe=3a8627fb53) | Oct 24, 2022 |
| MSI           | B350M PRO-VD PLUS           | [93068b4cf8](https://linux-hardware.org/?probe=93068b4cf8) | Oct 24, 2022 |
| ASUSTek       | PRIME B360M-A               | [19ccd70ee8](https://linux-hardware.org/?probe=19ccd70ee8) | Oct 24, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [01c09a61ae](https://linux-hardware.org/?probe=01c09a61ae) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| ASUSTek       | PRIME B450M-A               | [fb3feaef06](https://linux-hardware.org/?probe=fb3feaef06) | Oct 24, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [a8ab16a5c5](https://linux-hardware.org/?probe=a8ab16a5c5) | Oct 24, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | [164b8dd0d8](https://linux-hardware.org/?probe=164b8dd0d8) | Oct 24, 2022 |
| Dell          | 042P49 A02                  | [d9590e8d45](https://linux-hardware.org/?probe=d9590e8d45) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5010a8ef47](https://linux-hardware.org/?probe=5010a8ef47) | Oct 24, 2022 |
| Dell          | 0RW199                      | [dc99b64e62](https://linux-hardware.org/?probe=dc99b64e62) | Oct 24, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [37a0403fc9](https://linux-hardware.org/?probe=37a0403fc9) | Oct 24, 2022 |
| MSI           | Z390-A PRO                  | [40f916420e](https://linux-hardware.org/?probe=40f916420e) | Oct 23, 2022 |
| HP            | 3397                        | [6f58590d3d](https://linux-hardware.org/?probe=6f58590d3d) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [22ea226b97](https://linux-hardware.org/?probe=22ea226b97) | Oct 23, 2022 |
| Dell          | 0WR7PY A02                  | [07fb028e18](https://linux-hardware.org/?probe=07fb028e18) | Oct 22, 2022 |
| MSI           | X58 Pro                     | [96db21189e](https://linux-hardware.org/?probe=96db21189e) | Oct 22, 2022 |
| MSI           | PRO Z690-A                  | [9ea661d3b9](https://linux-hardware.org/?probe=9ea661d3b9) | Oct 22, 2022 |
| MSI           | MAG B460M BAZOOKA           | [9cfe9f3c51](https://linux-hardware.org/?probe=9cfe9f3c51) | Oct 22, 2022 |
| ASUSTek       | H110M-A                     | [7bd1ee25b3](https://linux-hardware.org/?probe=7bd1ee25b3) | Oct 21, 2022 |
| HP            | 87D6 SMVB                   | [86740d9460](https://linux-hardware.org/?probe=86740d9460) | Oct 21, 2022 |
| ASUSTek       | P7P55-M                     | [3ff254b938](https://linux-hardware.org/?probe=3ff254b938) | Oct 20, 2022 |
| ASUSTek       | Leonite2                    | [7640c7a49f](https://linux-hardware.org/?probe=7640c7a49f) | Oct 20, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e455bef105](https://linux-hardware.org/?probe=e455bef105) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [86950688ac](https://linux-hardware.org/?probe=86950688ac) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [ede27fb1d0](https://linux-hardware.org/?probe=ede27fb1d0) | Oct 19, 2022 |
| HP            | 805D                        | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [116fff483b](https://linux-hardware.org/?probe=116fff483b) | Oct 19, 2022 |
| Dell          | 0C522T A03                  | [20703ba8b3](https://linux-hardware.org/?probe=20703ba8b3) | Oct 18, 2022 |
| HP            | 3048h                       | [624ad8a33c](https://linux-hardware.org/?probe=624ad8a33c) | Oct 17, 2022 |
| HP            | 3048h                       | [1b3d31f720](https://linux-hardware.org/?probe=1b3d31f720) | Oct 17, 2022 |
| MSI           | MS-B1711                    | [231d1c3373](https://linux-hardware.org/?probe=231d1c3373) | Oct 16, 2022 |
| MSI           | MS-B1711                    | [964bad6988](https://linux-hardware.org/?probe=964bad6988) | Oct 16, 2022 |
| ASUSTek       | PRIME H270-PRO              | [3c2eef945d](https://linux-hardware.org/?probe=3c2eef945d) | Oct 16, 2022 |
| MSI           | MS-7309                     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| Packard Be... | IMEDIA S3712                | [d9aa81c4c3](https://linux-hardware.org/?probe=d9aa81c4c3) | Oct 15, 2022 |
| ASUSTek       | H87M-PRO                    | [4f1304fbdd](https://linux-hardware.org/?probe=4f1304fbdd) | Oct 15, 2022 |
| HP            | 198E                        | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| ASUSTek       | P5KPL-CM                    | [d00f5feebf](https://linux-hardware.org/?probe=d00f5feebf) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [b1eab51bd7](https://linux-hardware.org/?probe=b1eab51bd7) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8557c8b501](https://linux-hardware.org/?probe=8557c8b501) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek       | P8H77-V                     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| Intel         | STK2MV64CC H89290-502       | [85670dc1fe](https://linux-hardware.org/?probe=85670dc1fe) | Oct 14, 2022 |
| Supermicro    | C7P67                       | [70613229ac](https://linux-hardware.org/?probe=70613229ac) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d0d2949fd3](https://linux-hardware.org/?probe=d0d2949fd3) | Oct 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | [71970edbae](https://linux-hardware.org/?probe=71970edbae) | Oct 11, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [0e8d79a9a9](https://linux-hardware.org/?probe=0e8d79a9a9) | Oct 11, 2022 |
| ASUSTek       | Maximus VIII HERO ALPHA     | [c8ee640a4d](https://linux-hardware.org/?probe=c8ee640a4d) | Oct 09, 2022 |
| ASUSTek       | PRIME Z270-A                | [0f4a711f6a](https://linux-hardware.org/?probe=0f4a711f6a) | Oct 08, 2022 |
| ASRock        | H77M                        | [4ce05e4d0a](https://linux-hardware.org/?probe=4ce05e4d0a) | Oct 07, 2022 |
| Packard Be... | IMEDIA S3712                | [a528de7c22](https://linux-hardware.org/?probe=a528de7c22) | Oct 06, 2022 |
| ASUSTek       | PRIME H270-PRO              | [bbf95bf34d](https://linux-hardware.org/?probe=bbf95bf34d) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| HP            | 3398                        | [7dd62dded1](https://linux-hardware.org/?probe=7dd62dded1) | Oct 05, 2022 |
| HP            | 1906                        | [a6f705f119](https://linux-hardware.org/?probe=a6f705f119) | Oct 03, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | [f6a6361e08](https://linux-hardware.org/?probe=f6a6361e08) | Oct 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| ASUSTek       | P8Z68-V LX                  | [42b887e821](https://linux-hardware.org/?probe=42b887e821) | Oct 03, 2022 |
| Pegatron      | 2AC3                        | [0ea51f0746](https://linux-hardware.org/?probe=0ea51f0746) | Oct 03, 2022 |
| AZW           | Gemini X45                  | [721b4545a2](https://linux-hardware.org/?probe=721b4545a2) | Oct 02, 2022 |
| Packard Be... | IMEDIA S3712                | [1fd820d1d0](https://linux-hardware.org/?probe=1fd820d1d0) | Oct 01, 2022 |
| ASRock        | 970 Pro3 R2.0               | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| Dell          | 0YXT71 A02                  | [f36bc1d24e](https://linux-hardware.org/?probe=f36bc1d24e) | Sep 29, 2022 |
| ASRock        | J3160DC-ITX                 | [7e1818288f](https://linux-hardware.org/?probe=7e1818288f) | Sep 29, 2022 |
| Gigabyte      | F2A55M-DS2                  | [c17c689217](https://linux-hardware.org/?probe=c17c689217) | Sep 28, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [960c35d712](https://linux-hardware.org/?probe=960c35d712) | Sep 28, 2022 |
| Dell          | 09M8Y8 A01                  | [f129c4da4a](https://linux-hardware.org/?probe=f129c4da4a) | Sep 28, 2022 |
| Packard Be... | IMEDIA L4875 v1.0           | [bb57b80866](https://linux-hardware.org/?probe=bb57b80866) | Sep 27, 2022 |
| HP            | 8433 11                     | [a1d424bced](https://linux-hardware.org/?probe=a1d424bced) | Sep 27, 2022 |
| ASRock        | AB350 Gaming K4             | [184070d232](https://linux-hardware.org/?probe=184070d232) | Sep 26, 2022 |
| ASRock        | 775Dual-VSTA                | [9509fb65dd](https://linux-hardware.org/?probe=9509fb65dd) | Sep 26, 2022 |
| ASUSTek       | H81M-K                      | [badc988393](https://linux-hardware.org/?probe=badc988393) | Sep 26, 2022 |
| Packard Be... | IMEDIA L4875 v1.0           | [4ed673ff1a](https://linux-hardware.org/?probe=4ed673ff1a) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [65d54e7273](https://linux-hardware.org/?probe=65d54e7273) | Sep 25, 2022 |
| ASUSTek       | P8H61-M LX                  | [164f5bfea2](https://linux-hardware.org/?probe=164f5bfea2) | Sep 25, 2022 |
| HP            | 8433 11                     | [dffc61c155](https://linux-hardware.org/?probe=dffc61c155) | Sep 24, 2022 |
| ASRock        | 4CoreDual-SATA2             | [eb0e992df7](https://linux-hardware.org/?probe=eb0e992df7) | Sep 24, 2022 |
| ASUSTek       | P8B75-M LE                  | [8975676700](https://linux-hardware.org/?probe=8975676700) | Sep 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [fd43d92335](https://linux-hardware.org/?probe=fd43d92335) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a4ce7c179e](https://linux-hardware.org/?probe=a4ce7c179e) | Sep 23, 2022 |
| Fujitsu Si... | P5LD2-FM-DH-VP              | [0c6cbcc99d](https://linux-hardware.org/?probe=0c6cbcc99d) | Sep 22, 2022 |
| ASUSTek       | M3N78-VM                    | [edaab96cde](https://linux-hardware.org/?probe=edaab96cde) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [07dd388834](https://linux-hardware.org/?probe=07dd388834) | Sep 21, 2022 |
| Dell          | 0GM819                      | [951ce34bb2](https://linux-hardware.org/?probe=951ce34bb2) | Sep 21, 2022 |
| Lenovo        | ThinkCentre M57 6072WMD     | [eb8221088f](https://linux-hardware.org/?probe=eb8221088f) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [2c7466119d](https://linux-hardware.org/?probe=2c7466119d) | Sep 21, 2022 |
| Intel         | H55                         | [6de435d14c](https://linux-hardware.org/?probe=6de435d14c) | Sep 20, 2022 |
| ASUSTek       | G20CB                       | [34f4d43b97](https://linux-hardware.org/?probe=34f4d43b97) | Sep 20, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9c483616f6](https://linux-hardware.org/?probe=9c483616f6) | Sep 20, 2022 |
| Acer          | Aspire M3970                | [d135989361](https://linux-hardware.org/?probe=d135989361) | Sep 19, 2022 |
| Supermicro    | C7P67                       | [16bff71d62](https://linux-hardware.org/?probe=16bff71d62) | Sep 19, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [75be2db65c](https://linux-hardware.org/?probe=75be2db65c) | Sep 19, 2022 |
| HP            | 2B29                        | [391e407d29](https://linux-hardware.org/?probe=391e407d29) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | [2432fca2f8](https://linux-hardware.org/?probe=2432fca2f8) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| MSI           | Boston                      | [b884bd8c03](https://linux-hardware.org/?probe=b884bd8c03) | Sep 17, 2022 |
| ASUSTek       | P5K                         | [4cf17a7b6f](https://linux-hardware.org/?probe=4cf17a7b6f) | Sep 17, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [3ba3a4becf](https://linux-hardware.org/?probe=3ba3a4becf) | Sep 16, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [e6fe8aa148](https://linux-hardware.org/?probe=e6fe8aa148) | Sep 16, 2022 |
| ASUSTek       | ET1612I                     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| ASRock        | X370 Gaming K4              | [0858e80da7](https://linux-hardware.org/?probe=0858e80da7) | Sep 15, 2022 |
| ASUSTek       | PRIME H410M-E               | [91f1fdc978](https://linux-hardware.org/?probe=91f1fdc978) | Sep 14, 2022 |
| Dell          | 0WR7PY A02                  | [0a587d6fee](https://linux-hardware.org/?probe=0a587d6fee) | Sep 14, 2022 |
| ASRock        | H61M-DGS                    | [aeac7cfb74](https://linux-hardware.org/?probe=aeac7cfb74) | Sep 14, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [d3f957e34a](https://linux-hardware.org/?probe=d3f957e34a) | Sep 13, 2022 |
| ASUSTek       | G20CB                       | [a52ff97f3b](https://linux-hardware.org/?probe=a52ff97f3b) | Sep 12, 2022 |
| ASUSTek       | G20CB                       | [2d737743f4](https://linux-hardware.org/?probe=2d737743f4) | Sep 12, 2022 |
| ASRock        | B450 Gaming K4              | [2391f4673a](https://linux-hardware.org/?probe=2391f4673a) | Sep 12, 2022 |
| ASRock        | B450 Gaming K4              | [89963f6bf1](https://linux-hardware.org/?probe=89963f6bf1) | Sep 12, 2022 |
| MSI           | X58 Pro                     | [60406c82e8](https://linux-hardware.org/?probe=60406c82e8) | Sep 12, 2022 |
| Acer          | E415SM                      | [bc9ef15cab](https://linux-hardware.org/?probe=bc9ef15cab) | Sep 11, 2022 |
| Acer          | E415SM                      | [4f8a53c667](https://linux-hardware.org/?probe=4f8a53c667) | Sep 11, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [b76fc41706](https://linux-hardware.org/?probe=b76fc41706) | Sep 11, 2022 |
| Fujitsu Si... | P5LD2-FM-DH-VP              | [ad6a16f658](https://linux-hardware.org/?probe=ad6a16f658) | Sep 11, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4df5d0194d](https://linux-hardware.org/?probe=4df5d0194d) | Sep 11, 2022 |
| Gigabyte      | Z77X-UP7                    | [1634db2e78](https://linux-hardware.org/?probe=1634db2e78) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ee06685499](https://linux-hardware.org/?probe=ee06685499) | Sep 11, 2022 |
| Dell          | 09M8Y8 A01                  | [c719d7f544](https://linux-hardware.org/?probe=c719d7f544) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| ASRock        | J3160DC-ITX                 | [e854b82ab9](https://linux-hardware.org/?probe=e854b82ab9) | Sep 10, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [174c263499](https://linux-hardware.org/?probe=174c263499) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | [aeb2bae778](https://linux-hardware.org/?probe=aeb2bae778) | Sep 08, 2022 |
| Intel         | DH77DF AAG40293-300         | [217971d572](https://linux-hardware.org/?probe=217971d572) | Sep 08, 2022 |
| ASRock        | N3700-ITX                   | [5af515a1f9](https://linux-hardware.org/?probe=5af515a1f9) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | [d5040ffbda](https://linux-hardware.org/?probe=d5040ffbda) | Sep 08, 2022 |
| MSI           | H61M-P31                    | [56a8b0b2a7](https://linux-hardware.org/?probe=56a8b0b2a7) | Sep 08, 2022 |
| Pegatron      | 2A9Eh                       | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| HP            | 3397                        | [0ebeef29bf](https://linux-hardware.org/?probe=0ebeef29bf) | Sep 07, 2022 |
| Lenovo        | MAHOBAY                     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
| Pegatron      | Narra6                      | [b2a70f42a0](https://linux-hardware.org/?probe=b2a70f42a0) | Sep 07, 2022 |
| ASRock        | Q1900M                      | [05cf506f57](https://linux-hardware.org/?probe=05cf506f57) | Sep 06, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [42e666abe1](https://linux-hardware.org/?probe=42e666abe1) | Sep 06, 2022 |
| ASUSTek       | P8H77-V LE                  | [8a1c5532d6](https://linux-hardware.org/?probe=8a1c5532d6) | Sep 06, 2022 |
| ASUSTek       | P8H77-V LE                  | [cc631912bf](https://linux-hardware.org/?probe=cc631912bf) | Sep 06, 2022 |
| ASUSTek       | P9X79 PRO                   | [7e53f87cc4](https://linux-hardware.org/?probe=7e53f87cc4) | Sep 06, 2022 |
| ASUSTek       | H81M-PLUS                   | [826b486f77](https://linux-hardware.org/?probe=826b486f77) | Sep 05, 2022 |
| HP            | 0B4Ch D                     | [87c4023810](https://linux-hardware.org/?probe=87c4023810) | Sep 05, 2022 |
| ASRock        | Q1900M                      | [6b53538e90](https://linux-hardware.org/?probe=6b53538e90) | Sep 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | [312e33b434](https://linux-hardware.org/?probe=312e33b434) | Sep 05, 2022 |
| Dell          | 0MWYPT A01                  | [57b81c35c1](https://linux-hardware.org/?probe=57b81c35c1) | Sep 05, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e83fa739c9](https://linux-hardware.org/?probe=e83fa739c9) | Sep 05, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [502995e6f3](https://linux-hardware.org/?probe=502995e6f3) | Sep 05, 2022 |
| MSI           | B550-A PRO                  | [950b2a8eb5](https://linux-hardware.org/?probe=950b2a8eb5) | Sep 05, 2022 |
| ASUSTek       | P9X79 DELUXE                | [2aa7ada396](https://linux-hardware.org/?probe=2aa7ada396) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [127c2f5f75](https://linux-hardware.org/?probe=127c2f5f75) | Sep 05, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [26e63d2357](https://linux-hardware.org/?probe=26e63d2357) | Sep 05, 2022 |
| Dell          | 0HY9JP A02                  | [7cbf141461](https://linux-hardware.org/?probe=7cbf141461) | Sep 05, 2022 |
| Lenovo        | 367D 31900003 STD           | [c145bac65a](https://linux-hardware.org/?probe=c145bac65a) | Sep 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [7c87d1ad42](https://linux-hardware.org/?probe=7c87d1ad42) | Sep 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [43267285d4](https://linux-hardware.org/?probe=43267285d4) | Sep 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [008133bf59](https://linux-hardware.org/?probe=008133bf59) | Sep 04, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [9cd2bcff37](https://linux-hardware.org/?probe=9cd2bcff37) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [4a27f8b033](https://linux-hardware.org/?probe=4a27f8b033) | Sep 04, 2022 |
| ASRock        | Q1900M                      | [55a86f60b9](https://linux-hardware.org/?probe=55a86f60b9) | Sep 04, 2022 |
| ASUSTek       | P5P43TD                     | [cca9e79d90](https://linux-hardware.org/?probe=cca9e79d90) | Sep 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2cf13f4045](https://linux-hardware.org/?probe=2cf13f4045) | Sep 04, 2022 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | [ed16086671](https://linux-hardware.org/?probe=ed16086671) | Sep 04, 2022 |
| ASUSTek       | UN45                        | [87eca02296](https://linux-hardware.org/?probe=87eca02296) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [bf4936f3bc](https://linux-hardware.org/?probe=bf4936f3bc) | Sep 04, 2022 |
| ASRock        | H370M-ITX/ac                | [1a577be107](https://linux-hardware.org/?probe=1a577be107) | Sep 04, 2022 |
| ASUSTek       | PRIME A320M-K               | [878661705c](https://linux-hardware.org/?probe=878661705c) | Sep 04, 2022 |
| Dell          | 0T1D10 A01                  | [3064d08dc1](https://linux-hardware.org/?probe=3064d08dc1) | Sep 03, 2022 |
| ASUSTek       | PRIME H470-PLUS             | [e80ac4d271](https://linux-hardware.org/?probe=e80ac4d271) | Sep 03, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [312013ef36](https://linux-hardware.org/?probe=312013ef36) | Sep 03, 2022 |
| Dell          | 0HMF7C A01                  | [292123f83b](https://linux-hardware.org/?probe=292123f83b) | Sep 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [6de688d21a](https://linux-hardware.org/?probe=6de688d21a) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [159c1dcd33](https://linux-hardware.org/?probe=159c1dcd33) | Sep 03, 2022 |
| ASUSTek       | P5KC                        | [602e22310b](https://linux-hardware.org/?probe=602e22310b) | Sep 03, 2022 |
| MSI           | B450-A PRO MAX              | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | [e20b509508](https://linux-hardware.org/?probe=e20b509508) | Sep 03, 2022 |
| ASUSTek       | P7P55D                      | [ad2b0a0a89](https://linux-hardware.org/?probe=ad2b0a0a89) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [b9f43af7d0](https://linux-hardware.org/?probe=b9f43af7d0) | Sep 03, 2022 |
| ASRock        | H310CM-HDV                  | [df5d5f2e7f](https://linux-hardware.org/?probe=df5d5f2e7f) | Sep 03, 2022 |
| Gigabyte      | Z97X-UD5H-BK                | [97a21d48e0](https://linux-hardware.org/?probe=97a21d48e0) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [5dcc9cd8c8](https://linux-hardware.org/?probe=5dcc9cd8c8) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [9cab157472](https://linux-hardware.org/?probe=9cab157472) | Sep 03, 2022 |
| ASUSTek       | Z170-K                      | [d47c5fe35c](https://linux-hardware.org/?probe=d47c5fe35c) | Sep 03, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [9b8eef74b8](https://linux-hardware.org/?probe=9b8eef74b8) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [982df83fdf](https://linux-hardware.org/?probe=982df83fdf) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [32d39c8b65](https://linux-hardware.org/?probe=32d39c8b65) | Sep 03, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [709825bde3](https://linux-hardware.org/?probe=709825bde3) | Sep 03, 2022 |
| ASUSTek       | PRIME H270-PRO              | [5c0b32f572](https://linux-hardware.org/?probe=5c0b32f572) | Sep 03, 2022 |
| MSI           | H170 GAMING M3              | [b0d669cf4b](https://linux-hardware.org/?probe=b0d669cf4b) | Sep 03, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c13f075f83](https://linux-hardware.org/?probe=c13f075f83) | Sep 03, 2022 |
| ASRock        | 4CoreDual-SATA2             | [c64d84d331](https://linux-hardware.org/?probe=c64d84d331) | Sep 03, 2022 |
| ASRock        | X470 Taichi                 | [0a6ff089f1](https://linux-hardware.org/?probe=0a6ff089f1) | Sep 03, 2022 |
| MSI           | X470 GAMING PRO MAX         | [7f10b8002b](https://linux-hardware.org/?probe=7f10b8002b) | Sep 03, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [65562b09e0](https://linux-hardware.org/?probe=65562b09e0) | Sep 03, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [a591a1fecf](https://linux-hardware.org/?probe=a591a1fecf) | Sep 03, 2022 |
| ASRock        | FM2A88X-ITX+                | [9c22b70a4f](https://linux-hardware.org/?probe=9c22b70a4f) | Sep 03, 2022 |
| MSI           | B550-A PRO                  | [65bfdaa6ea](https://linux-hardware.org/?probe=65bfdaa6ea) | Sep 03, 2022 |
| Gigabyte      | B560M DS3H V2               | [4d9025cf5c](https://linux-hardware.org/?probe=4d9025cf5c) | Sep 03, 2022 |
| BESSTAR Te... | UM350                       | [02423b61e0](https://linux-hardware.org/?probe=02423b61e0) | Sep 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [acfa42b951](https://linux-hardware.org/?probe=acfa42b951) | Sep 03, 2022 |
| Dell          | 0F6X5P A00                  | [71ff7749aa](https://linux-hardware.org/?probe=71ff7749aa) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| HP            | 3397                        | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [7829cfc920](https://linux-hardware.org/?probe=7829cfc920) | Sep 02, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [5485918ea2](https://linux-hardware.org/?probe=5485918ea2) | Sep 02, 2022 |
| ASUSTek       | P8H77-V LE                  | [f77ecfe3bc](https://linux-hardware.org/?probe=f77ecfe3bc) | Sep 02, 2022 |
| Pegatron      | 2AB6                        | [c4ca3989e0](https://linux-hardware.org/?probe=c4ca3989e0) | Aug 31, 2022 |
| HP            | 18E9                        | [2dff78f303](https://linux-hardware.org/?probe=2dff78f303) | Aug 31, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [98e0a08e65](https://linux-hardware.org/?probe=98e0a08e65) | Aug 30, 2022 |
| ASUSTek       | P5QPL-AM                    | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| OEM           | G41 775 ICH7 8712           | [4225df6517](https://linux-hardware.org/?probe=4225df6517) | Aug 29, 2022 |
| ASUSTek       | Z97-C                       | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [7a2c713719](https://linux-hardware.org/?probe=7a2c713719) | Aug 29, 2022 |
| HP            | 8751                        | [62c8c2f25e](https://linux-hardware.org/?probe=62c8c2f25e) | Aug 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [17e8c1560b](https://linux-hardware.org/?probe=17e8c1560b) | Aug 28, 2022 |
| ASRock        | H61M-DGS                    | [023204fa1f](https://linux-hardware.org/?probe=023204fa1f) | Aug 28, 2022 |
| Gigabyte      | H97-HD3                     | [25e4d6c064](https://linux-hardware.org/?probe=25e4d6c064) | Aug 28, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [f74dc71ad8](https://linux-hardware.org/?probe=f74dc71ad8) | Aug 27, 2022 |
| Gigabyte      | Z490 UD                     | [a872472b1c](https://linux-hardware.org/?probe=a872472b1c) | Aug 26, 2022 |
| Intel         | D2550MUD2 AAG81497-700      | [a181512016](https://linux-hardware.org/?probe=a181512016) | Aug 26, 2022 |
| ASUSTek       | M5A78L LE                   | [e4a6425675](https://linux-hardware.org/?probe=e4a6425675) | Aug 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [a096217ea3](https://linux-hardware.org/?probe=a096217ea3) | Aug 24, 2022 |
| ASUSTek       | M4N68T-M-V2                 | [1528da74f6](https://linux-hardware.org/?probe=1528da74f6) | Aug 22, 2022 |
| ASUSTek       | PRIME Z390-P                | [ca7534d4dc](https://linux-hardware.org/?probe=ca7534d4dc) | Aug 22, 2022 |
| ASUSTek       | H110M-A/M.2                 | [dab0f526b0](https://linux-hardware.org/?probe=dab0f526b0) | Aug 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e064c453da](https://linux-hardware.org/?probe=e064c453da) | Aug 21, 2022 |
| Gigabyte      | P35-DS3L                    | [1ee42449ed](https://linux-hardware.org/?probe=1ee42449ed) | Aug 21, 2022 |
| OEM           | G41 775 ICH7 8712           | [71bfa72a22](https://linux-hardware.org/?probe=71bfa72a22) | Aug 21, 2022 |
| MSI           | G31M3                       | [3bb7906f56](https://linux-hardware.org/?probe=3bb7906f56) | Aug 20, 2022 |
| AZW           | MII-V                       | [59698f6b33](https://linux-hardware.org/?probe=59698f6b33) | Aug 20, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [57f1970999](https://linux-hardware.org/?probe=57f1970999) | Aug 20, 2022 |
| MSI           | Boston                      | [4a10f122a2](https://linux-hardware.org/?probe=4a10f122a2) | Aug 19, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [410c71e7ef](https://linux-hardware.org/?probe=410c71e7ef) | Aug 18, 2022 |
| Acer          | MRS600M                     | [ec4c10d06e](https://linux-hardware.org/?probe=ec4c10d06e) | Aug 17, 2022 |
| ASRock        | 775Dual-VSTA                | [89ac2bb6fe](https://linux-hardware.org/?probe=89ac2bb6fe) | Aug 17, 2022 |
| HP            | 1495                        | [34b69b08b1](https://linux-hardware.org/?probe=34b69b08b1) | Aug 15, 2022 |
| HP            | 1495                        | [6db4307c50](https://linux-hardware.org/?probe=6db4307c50) | Aug 15, 2022 |
| HP            | 1495                        | [c122ce06ab](https://linux-hardware.org/?probe=c122ce06ab) | Aug 15, 2022 |
| ASUSTek       | PRIME B450M-A II            | [4ba26713bc](https://linux-hardware.org/?probe=4ba26713bc) | Aug 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [2162cafc91](https://linux-hardware.org/?probe=2162cafc91) | Aug 13, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [6a0c6ab778](https://linux-hardware.org/?probe=6a0c6ab778) | Aug 13, 2022 |
| AZW           | U59                         | [344d4587f6](https://linux-hardware.org/?probe=344d4587f6) | Aug 12, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [e5e5d0d3a3](https://linux-hardware.org/?probe=e5e5d0d3a3) | Aug 11, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [93ecf84dcf](https://linux-hardware.org/?probe=93ecf84dcf) | Aug 11, 2022 |
| ASRock        | G41M-VS3                    | [4185ab0f97](https://linux-hardware.org/?probe=4185ab0f97) | Aug 10, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [7792f4471e](https://linux-hardware.org/?probe=7792f4471e) | Aug 10, 2022 |
| ASRock        | H55M-LE                     | [841c63de14](https://linux-hardware.org/?probe=841c63de14) | Aug 08, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7ca881aae7](https://linux-hardware.org/?probe=7ca881aae7) | Aug 08, 2022 |
| Acer          | Predator PO3-620            | [ff0507688f](https://linux-hardware.org/?probe=ff0507688f) | Aug 02, 2022 |
| Acer          | FIH57                       | [eec3e58c8c](https://linux-hardware.org/?probe=eec3e58c8c) | Aug 02, 2022 |
| Acer          | FIH57                       | [a6b9d91f36](https://linux-hardware.org/?probe=a6b9d91f36) | Jul 30, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [bace89cd10](https://linux-hardware.org/?probe=bace89cd10) | Jul 30, 2022 |
| ASUSTek       | P6T DELUXE V2               | [3c18081f88](https://linux-hardware.org/?probe=3c18081f88) | Jul 29, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [54d5ee0a3a](https://linux-hardware.org/?probe=54d5ee0a3a) | Jul 28, 2022 |
| MSI           | B250M PRO-VD                | [e58c8fca5a](https://linux-hardware.org/?probe=e58c8fca5a) | Jul 28, 2022 |
| ASUSTek       | Z97-C                       | [e292699b1c](https://linux-hardware.org/?probe=e292699b1c) | Jul 28, 2022 |
| Acer          | EM61SM/EM61PM               | [2de6d95c80](https://linux-hardware.org/?probe=2de6d95c80) | Jul 28, 2022 |
| HP            | 1495                        | [61a8f473e2](https://linux-hardware.org/?probe=61a8f473e2) | Jul 27, 2022 |
| Acer          | FIH57                       | [f351802c52](https://linux-hardware.org/?probe=f351802c52) | Jul 26, 2022 |
| Dell          | 0KH290                      | [74934828fa](https://linux-hardware.org/?probe=74934828fa) | Jul 26, 2022 |
| MSI           | Z490-A PRO                  | [fe48f1e5cd](https://linux-hardware.org/?probe=fe48f1e5cd) | Jul 26, 2022 |
| Acer          | FIH57                       | [df3c42e452](https://linux-hardware.org/?probe=df3c42e452) | Jul 25, 2022 |
| Acer          | EM61SM/EM61PM               | [e470dff38f](https://linux-hardware.org/?probe=e470dff38f) | Jul 25, 2022 |
| AMI           | Cherry Trail CR             | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| ASRock        | 990FX Extreme3              | [158c8d142b](https://linux-hardware.org/?probe=158c8d142b) | Jul 24, 2022 |
| Gigabyte      | P35-DS3L                    | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6e4f170da9](https://linux-hardware.org/?probe=6e4f170da9) | Jul 22, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [dfe6047aa7](https://linux-hardware.org/?probe=dfe6047aa7) | Jul 21, 2022 |
| ASUSTek       | H110M-A/M.2                 | [97f5b09dd2](https://linux-hardware.org/?probe=97f5b09dd2) | Jul 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6e4fbc6688](https://linux-hardware.org/?probe=6e4fbc6688) | Jul 20, 2022 |
| Gigabyte      | P35-DS3L                    | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Foxconn       | 2ABF                        | [765d75028c](https://linux-hardware.org/?probe=765d75028c) | Jul 19, 2022 |
| Dell          | 0F6X5P A00                  | [528f781464](https://linux-hardware.org/?probe=528f781464) | Jul 16, 2022 |
| Acer          | FIH57                       | [ea25a3cc88](https://linux-hardware.org/?probe=ea25a3cc88) | Jul 15, 2022 |
| ASUSTek       | P5QLD PRO                   | [fbf3a31304](https://linux-hardware.org/?probe=fbf3a31304) | Jul 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [8f2f28b1c3](https://linux-hardware.org/?probe=8f2f28b1c3) | Jul 15, 2022 |
| Intel         | DQ77MK AAG39642-500         | [7b6a43a9f1](https://linux-hardware.org/?probe=7b6a43a9f1) | Jul 15, 2022 |
| HP            | 2B4B                        | [6592fe9157](https://linux-hardware.org/?probe=6592fe9157) | Jul 13, 2022 |
| MSI           | Boston                      | [4966d9bfdf](https://linux-hardware.org/?probe=4966d9bfdf) | Jul 12, 2022 |
| ASUSTek       | Maximus VIII HERO           | [491e37bdfb](https://linux-hardware.org/?probe=491e37bdfb) | Jul 12, 2022 |
| Acer          | FIH57                       | [b052eec1d0](https://linux-hardware.org/?probe=b052eec1d0) | Jul 10, 2022 |
| ASRock        | N68C-S UCC                  | [8c5338cc67](https://linux-hardware.org/?probe=8c5338cc67) | Jul 10, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [6ed805403a](https://linux-hardware.org/?probe=6ed805403a) | Jul 10, 2022 |
| MSI           | Z390-A PRO                  | [f3a1f552c8](https://linux-hardware.org/?probe=f3a1f552c8) | Jul 09, 2022 |
| Unknown       | Unknown                     | [e7dfa60f77](https://linux-hardware.org/?probe=e7dfa60f77) | Jul 09, 2022 |
| MSI           | H110M GAMING                | [92f54d6efd](https://linux-hardware.org/?probe=92f54d6efd) | Jul 09, 2022 |
| HP            | 1495                        | [3e67bd3405](https://linux-hardware.org/?probe=3e67bd3405) | Jul 09, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [3db9c636d0](https://linux-hardware.org/?probe=3db9c636d0) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [d66a60be9a](https://linux-hardware.org/?probe=d66a60be9a) | Jul 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8b1a622249](https://linux-hardware.org/?probe=8b1a622249) | Jul 07, 2022 |
| MSI           | B250M PRO-VH                | [cab2cbb630](https://linux-hardware.org/?probe=cab2cbb630) | Jul 07, 2022 |
| Acer          | E91M                        | [4e55aacdd7](https://linux-hardware.org/?probe=4e55aacdd7) | Jul 06, 2022 |
| Acer          | FIH57                       | [75895f96b9](https://linux-hardware.org/?probe=75895f96b9) | Jul 05, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [0567d5e337](https://linux-hardware.org/?probe=0567d5e337) | Jul 05, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [5c8477b1a3](https://linux-hardware.org/?probe=5c8477b1a3) | Jul 04, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [161f8c2665](https://linux-hardware.org/?probe=161f8c2665) | Jul 03, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [15118ef9fd](https://linux-hardware.org/?probe=15118ef9fd) | Jul 03, 2022 |
| ASRock        | J4105M                      | [502c01c109](https://linux-hardware.org/?probe=502c01c109) | Jul 03, 2022 |
| Gigabyte      | G31M-S2L                    | [d555145d9f](https://linux-hardware.org/?probe=d555145d9f) | Jul 03, 2022 |
| ASUSTek       | P8H77-M PRO                 | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| ASRock        | AM1B-M                      | [e0e4a278c9](https://linux-hardware.org/?probe=e0e4a278c9) | Jul 02, 2022 |
| Intel         | D2500CC AAG81477-400        | [c9a6658803](https://linux-hardware.org/?probe=c9a6658803) | Jul 02, 2022 |
| ASRock        | 775Dual-VSTA                | [31825f35da](https://linux-hardware.org/?probe=31825f35da) | Jun 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6a2f1d22f1](https://linux-hardware.org/?probe=6a2f1d22f1) | Jun 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0a976062da](https://linux-hardware.org/?probe=0a976062da) | Jun 29, 2022 |
| Dell          | 0RF703                      | [7b1a5ddcb6](https://linux-hardware.org/?probe=7b1a5ddcb6) | Jun 27, 2022 |
| MSI           | B250 GAMING M3              | [b294a7b0b1](https://linux-hardware.org/?probe=b294a7b0b1) | Jun 26, 2022 |
| HP            | 3398                        | [4241fd0ba0](https://linux-hardware.org/?probe=4241fd0ba0) | Jun 26, 2022 |
| MSI           | B250 GAMING M3              | [f79c31ad28](https://linux-hardware.org/?probe=f79c31ad28) | Jun 26, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [01fcd4495e](https://linux-hardware.org/?probe=01fcd4495e) | Jun 25, 2022 |
| Foxconn       | 945 7MC Series              | [16836e63f5](https://linux-hardware.org/?probe=16836e63f5) | Jun 25, 2022 |
| MSI           | A78M-E45                    | [ca217e0ccb](https://linux-hardware.org/?probe=ca217e0ccb) | Jun 25, 2022 |
| ASRock        | H77 Pro4/MVP                | [f022b1b430](https://linux-hardware.org/?probe=f022b1b430) | Jun 24, 2022 |
| ASRock        | X370 Pro4                   | [df6751dcaa](https://linux-hardware.org/?probe=df6751dcaa) | Jun 22, 2022 |
| Intel         | DX58SO AAE29331-703         | [edb0ff1a68](https://linux-hardware.org/?probe=edb0ff1a68) | Jun 22, 2022 |
| MSI           | B450M-A PRO MAX             | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| Gigabyte      | H97M-D3H                    | [1529cf29a5](https://linux-hardware.org/?probe=1529cf29a5) | Jun 22, 2022 |
| Gigabyte      | H97M-D3H                    | [4a2493f02c](https://linux-hardware.org/?probe=4a2493f02c) | Jun 22, 2022 |
| ASUSTek       | M4N78-AM                    | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Unknown       | RS780-SB700                 | [a4649c2c4a](https://linux-hardware.org/?probe=a4649c2c4a) | Jun 21, 2022 |
| HP            | 0AA0h                       | [ccc94e1725](https://linux-hardware.org/?probe=ccc94e1725) | Jun 21, 2022 |
| MSI           | B550M-A PRO                 | [1765b91360](https://linux-hardware.org/?probe=1765b91360) | Jun 21, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [88a7cd954c](https://linux-hardware.org/?probe=88a7cd954c) | Jun 19, 2022 |
| Dell          | 040DDP A01                  | [a4091a0526](https://linux-hardware.org/?probe=a4091a0526) | Jun 19, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [7912825604](https://linux-hardware.org/?probe=7912825604) | Jun 19, 2022 |
| ASRock        | B85M DASH/OL R2.0           | [c5763f8865](https://linux-hardware.org/?probe=c5763f8865) | Jun 17, 2022 |
| ASUSTek       | M4N78-AM                    | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [fb36d0a844](https://linux-hardware.org/?probe=fb36d0a844) | Jun 15, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [8852623d3d](https://linux-hardware.org/?probe=8852623d3d) | Jun 15, 2022 |
| ASUSTek       | PRIME A320M-K               | [c8dfb12509](https://linux-hardware.org/?probe=c8dfb12509) | Jun 14, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [d827dcbe06](https://linux-hardware.org/?probe=d827dcbe06) | Jun 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | [1c1f01b85f](https://linux-hardware.org/?probe=1c1f01b85f) | Jun 12, 2022 |
| Foxconn       | Irvine HP P/N               | [551f18d133](https://linux-hardware.org/?probe=551f18d133) | Jun 11, 2022 |
| MSI           | Boston                      | [f44a102ffb](https://linux-hardware.org/?probe=f44a102ffb) | Jun 11, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [2dd49013ff](https://linux-hardware.org/?probe=2dd49013ff) | Jun 10, 2022 |
| T-bao         | MINI PC V1.0                | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [59f197c68d](https://linux-hardware.org/?probe=59f197c68d) | Jun 07, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [9756188040](https://linux-hardware.org/?probe=9756188040) | Jun 07, 2022 |
| ASRock        | 775Dual-VSTA                | [5dca8ae4cb](https://linux-hardware.org/?probe=5dca8ae4cb) | Jun 06, 2022 |
| ASRock        | 775Dual-VSTA                | [b627c94dff](https://linux-hardware.org/?probe=b627c94dff) | Jun 06, 2022 |
| MSI           | B550M PRO-VDH               | [8279a4df3a](https://linux-hardware.org/?probe=8279a4df3a) | Jun 06, 2022 |
| MSI           | Boston                      | [2497abc0c1](https://linux-hardware.org/?probe=2497abc0c1) | Jun 05, 2022 |
| MSI           | X570-A PRO                  | [95af0fa349](https://linux-hardware.org/?probe=95af0fa349) | Jun 04, 2022 |
| ASUSTek       | Z170-A                      | [ed86450031](https://linux-hardware.org/?probe=ed86450031) | Jun 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [61b90c102c](https://linux-hardware.org/?probe=61b90c102c) | Jun 03, 2022 |
| ASUSTek       | H110M-A/M.2                 | [990cfd2d12](https://linux-hardware.org/?probe=990cfd2d12) | May 31, 2022 |
| HP            | 3047h                       | [59affe5430](https://linux-hardware.org/?probe=59affe5430) | May 31, 2022 |
| Pegatron      | 2A73h                       | [c9af41f21f](https://linux-hardware.org/?probe=c9af41f21f) | May 28, 2022 |
| Pegatron      | 2A73h                       | [d09310f985](https://linux-hardware.org/?probe=d09310f985) | May 28, 2022 |
| MSI           | Boston                      | [53510ee8ef](https://linux-hardware.org/?probe=53510ee8ef) | May 28, 2022 |
| Dell          | 04YP6J A02                  | [5c0b3c0e56](https://linux-hardware.org/?probe=5c0b3c0e56) | May 28, 2022 |
| ASUSTek       | PRIME B460M-K               | [a6dafabf0c](https://linux-hardware.org/?probe=a6dafabf0c) | May 27, 2022 |
| ASRock        | AB350M Pro4                 | [dd39f18241](https://linux-hardware.org/?probe=dd39f18241) | May 25, 2022 |
| Dell          | 0RF703                      | [228efad4f1](https://linux-hardware.org/?probe=228efad4f1) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| T-bao         | MINI PC V1.0                | [1715d72a33](https://linux-hardware.org/?probe=1715d72a33) | May 25, 2022 |
| T-bao         | MINI PC V1.0                | [f964c9691e](https://linux-hardware.org/?probe=f964c9691e) | May 25, 2022 |
| Gigabyte      | P55-UD3L                    | [256b5355c3](https://linux-hardware.org/?probe=256b5355c3) | May 24, 2022 |
| HP            | 1495                        | [68ead7bd6a](https://linux-hardware.org/?probe=68ead7bd6a) | May 23, 2022 |
| Foxconn       | 946 7MA Series              | [9f88edf79e](https://linux-hardware.org/?probe=9f88edf79e) | May 19, 2022 |
| MSI           | Z97-G45 GAMING              | [1b02844b0b](https://linux-hardware.org/?probe=1b02844b0b) | May 18, 2022 |
| MSI           | Boston                      | [b49f5c367f](https://linux-hardware.org/?probe=b49f5c367f) | May 16, 2022 |
| ASUSTek       | M3N78 PRO                   | [246f442b9b](https://linux-hardware.org/?probe=246f442b9b) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0d9d6b919b](https://linux-hardware.org/?probe=0d9d6b919b) | May 15, 2022 |
| ASUSTek       | M3N78 PRO                   | [af5eec886b](https://linux-hardware.org/?probe=af5eec886b) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [c84b325929](https://linux-hardware.org/?probe=c84b325929) | May 13, 2022 |
| ASUSTek       | NARRA3                      | [ca524c9e95](https://linux-hardware.org/?probe=ca524c9e95) | May 13, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [df570dd8e0](https://linux-hardware.org/?probe=df570dd8e0) | May 12, 2022 |
| Unknown       | Unknown                     | [7931f8191f](https://linux-hardware.org/?probe=7931f8191f) | May 11, 2022 |
| Unknown       | Unknown                     | [271a8ba23e](https://linux-hardware.org/?probe=271a8ba23e) | May 11, 2022 |
| HP            | 2B4B                        | [868bd14401](https://linux-hardware.org/?probe=868bd14401) | May 11, 2022 |
| ASUSTek       | H61M-K                      | [64f2ed4df2](https://linux-hardware.org/?probe=64f2ed4df2) | May 11, 2022 |
| ASUSTek       | P9X79                       | [694affb24e](https://linux-hardware.org/?probe=694affb24e) | May 10, 2022 |
| MSI           | B450M PRO-VDH MAX           | [feafca0464](https://linux-hardware.org/?probe=feafca0464) | May 10, 2022 |
| Unknown       | HX90                        | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [17e7dcafe2](https://linux-hardware.org/?probe=17e7dcafe2) | May 08, 2022 |
| MSI           | MEG Z590 GODLIKE            | [0b88e8e449](https://linux-hardware.org/?probe=0b88e8e449) | May 06, 2022 |
| ASUSTek       | 2A73h                       | [458bf998ee](https://linux-hardware.org/?probe=458bf998ee) | May 06, 2022 |
| MSI           | MEG Z590 GODLIKE            | [ce253bc962](https://linux-hardware.org/?probe=ce253bc962) | May 05, 2022 |
| HP            | 18E7                        | [57194bb53c](https://linux-hardware.org/?probe=57194bb53c) | May 04, 2022 |
| ASUSTek       | CM6650                      | [d41d1228db](https://linux-hardware.org/?probe=d41d1228db) | May 04, 2022 |
| ASUSTek       | PRIME X370-A                | [4d1f9886c2](https://linux-hardware.org/?probe=4d1f9886c2) | May 03, 2022 |
| ASRock        | AB350M Pro4                 | [1d4a595342](https://linux-hardware.org/?probe=1d4a595342) | May 02, 2022 |
| ASUSTek       | H61M-K                      | [fbbae98a18](https://linux-hardware.org/?probe=fbbae98a18) | May 01, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [8d3881574d](https://linux-hardware.org/?probe=8d3881574d) | Apr 30, 2022 |
| HP            | 1494                        | [939f3b7987](https://linux-hardware.org/?probe=939f3b7987) | Apr 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | [8c1bf73769](https://linux-hardware.org/?probe=8c1bf73769) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [d0ca0e52ad](https://linux-hardware.org/?probe=d0ca0e52ad) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [a2f86e2fea](https://linux-hardware.org/?probe=a2f86e2fea) | Apr 28, 2022 |
| HP            | 1588h                       | [20624367eb](https://linux-hardware.org/?probe=20624367eb) | Apr 27, 2022 |
| HP            | 1588h                       | [831e4e5993](https://linux-hardware.org/?probe=831e4e5993) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [80792ef9d7](https://linux-hardware.org/?probe=80792ef9d7) | Apr 27, 2022 |
| HP            | 09F8h                       | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| Acer          | Aspire TC-780               | [501877dba5](https://linux-hardware.org/?probe=501877dba5) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [35975b7d55](https://linux-hardware.org/?probe=35975b7d55) | Apr 25, 2022 |
| ASUSTek       | P8H61-M LX2                 | [a60c0bf48d](https://linux-hardware.org/?probe=a60c0bf48d) | Apr 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [d3d995a41b](https://linux-hardware.org/?probe=d3d995a41b) | Apr 24, 2022 |
| ASUSTek       | P5GD1                       | [11b7aa3465](https://linux-hardware.org/?probe=11b7aa3465) | Apr 24, 2022 |
| HP            | 09F8h                       | [5042a34dcd](https://linux-hardware.org/?probe=5042a34dcd) | Apr 23, 2022 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [30f8dbd98c](https://linux-hardware.org/?probe=30f8dbd98c) | Apr 22, 2022 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [179d1e1a0f](https://linux-hardware.org/?probe=179d1e1a0f) | Apr 22, 2022 |
| Acer          | Veriton M2631 V:1.0         | [4f27720e96](https://linux-hardware.org/?probe=4f27720e96) | Apr 21, 2022 |
| Lenovo        | SDK0E50510 WIN              | [3d829a871e](https://linux-hardware.org/?probe=3d829a871e) | Apr 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [beab5308cb](https://linux-hardware.org/?probe=beab5308cb) | Apr 19, 2022 |
| ASUSTek       | PRIME H510M-A               | [59fb2af2c2](https://linux-hardware.org/?probe=59fb2af2c2) | Apr 18, 2022 |
| ASUSTek       | P8Z68 DELUXE                | [4df90e6250](https://linux-hardware.org/?probe=4df90e6250) | Apr 18, 2022 |
| Acer          | Aspire TC-115               | [16d5411ae8](https://linux-hardware.org/?probe=16d5411ae8) | Apr 18, 2022 |
| ASUSTek       | PRIME B460M-A               | [98637b4cf2](https://linux-hardware.org/?probe=98637b4cf2) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0169381aeb](https://linux-hardware.org/?probe=0169381aeb) | Apr 15, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [c3d8900f58](https://linux-hardware.org/?probe=c3d8900f58) | Apr 15, 2022 |
| Dell          | 0HN7XN A01                  | [5a9ba12201](https://linux-hardware.org/?probe=5a9ba12201) | Apr 15, 2022 |
| Gigabyte      | GA-A55M-S2V                 | [36d5c02824](https://linux-hardware.org/?probe=36d5c02824) | Apr 15, 2022 |
| ASUSTek       | P8Z68 DELUXE                | [7cc9a1bbb7](https://linux-hardware.org/?probe=7cc9a1bbb7) | Apr 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0e7314b7c9](https://linux-hardware.org/?probe=0e7314b7c9) | Apr 14, 2022 |
| MSI           | A68HM-P33                   | [8c395556de](https://linux-hardware.org/?probe=8c395556de) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | [e3a8701de2](https://linux-hardware.org/?probe=e3a8701de2) | Apr 13, 2022 |
| ASUSTek       | PRIME A520M-K               | [58dab53fb1](https://linux-hardware.org/?probe=58dab53fb1) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [6ac57575d9](https://linux-hardware.org/?probe=6ac57575d9) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [dc6799506a](https://linux-hardware.org/?probe=dc6799506a) | Apr 13, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [8c2362aa24](https://linux-hardware.org/?probe=8c2362aa24) | Apr 11, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [14b70a1c77](https://linux-hardware.org/?probe=14b70a1c77) | Apr 10, 2022 |
| ASUSTek       | M2N8L                       | [dc78c18c3f](https://linux-hardware.org/?probe=dc78c18c3f) | Apr 10, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [a56209b0c7](https://linux-hardware.org/?probe=a56209b0c7) | Apr 09, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [8d440b5da5](https://linux-hardware.org/?probe=8d440b5da5) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS M                | [1a4b90c894](https://linux-hardware.org/?probe=1a4b90c894) | Apr 08, 2022 |
| ASRock        | H61M-DGS                    | [1d08a53545](https://linux-hardware.org/?probe=1d08a53545) | Apr 08, 2022 |
| HP            | 3397                        | [d22ff33b0e](https://linux-hardware.org/?probe=d22ff33b0e) | Apr 08, 2022 |
| Lenovo        | ThinkStation S20 4157WC1    | [d64502fb70](https://linux-hardware.org/?probe=d64502fb70) | Apr 08, 2022 |
| Intel         | STK2MV64CC H89290-502       | [b2cb31c994](https://linux-hardware.org/?probe=b2cb31c994) | Apr 07, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [7da8a936ea](https://linux-hardware.org/?probe=7da8a936ea) | Apr 04, 2022 |
| ASRock        | C2750D4I                    | [b328ff82c5](https://linux-hardware.org/?probe=b328ff82c5) | Apr 03, 2022 |
| ASRock        | 970 Extreme4                | [cc65547e82](https://linux-hardware.org/?probe=cc65547e82) | Apr 03, 2022 |
| MSI           | Z590-A PRO                  | [229ed42b3d](https://linux-hardware.org/?probe=229ed42b3d) | Apr 03, 2022 |
| Acer          | Aspire M1920                | [00d3df045a](https://linux-hardware.org/?probe=00d3df045a) | Apr 02, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [3807eeb187](https://linux-hardware.org/?probe=3807eeb187) | Apr 02, 2022 |
| ASUSTek       | P5GD1 PRO                   | [9156c67116](https://linux-hardware.org/?probe=9156c67116) | Apr 01, 2022 |
| ASUSTek       | A68HM-K                     | [482d5e9c62](https://linux-hardware.org/?probe=482d5e9c62) | Apr 01, 2022 |
| ASRock        | 775Dual-VSTA                | [f5aea8ce64](https://linux-hardware.org/?probe=f5aea8ce64) | Apr 01, 2022 |
| MSI           | Z590-A PRO                  | [cafa6713f0](https://linux-hardware.org/?probe=cafa6713f0) | Apr 01, 2022 |
| Gigabyte      | G1.Sniper B6-CF             | [17ea484809](https://linux-hardware.org/?probe=17ea484809) | Mar 29, 2022 |
| Gigabyte      | H81M-S2PV                   | [79a7adfb69](https://linux-hardware.org/?probe=79a7adfb69) | Mar 29, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [641cb912c4](https://linux-hardware.org/?probe=641cb912c4) | Mar 29, 2022 |
| Gigabyte      | H81M-S2PV                   | [5a75a3f121](https://linux-hardware.org/?probe=5a75a3f121) | Mar 29, 2022 |
| ASUSTek       | AM1M-A                      | [29e10859da](https://linux-hardware.org/?probe=29e10859da) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Intel         | DH55HC AAE70933-505         | [0a58762fd9](https://linux-hardware.org/?probe=0a58762fd9) | Mar 29, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [9cd4056356](https://linux-hardware.org/?probe=9cd4056356) | Mar 28, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [9688bbdb3f](https://linux-hardware.org/?probe=9688bbdb3f) | Mar 28, 2022 |
| ASUSTek       | H110M-K                     | [4e238835bd](https://linux-hardware.org/?probe=4e238835bd) | Mar 28, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [6f66a7137f](https://linux-hardware.org/?probe=6f66a7137f) | Mar 28, 2022 |
| ASRock        | AMCP7AION-HT                | [23f929c975](https://linux-hardware.org/?probe=23f929c975) | Mar 27, 2022 |
| ASUSTek       | H110M-K                     | [14f509aa32](https://linux-hardware.org/?probe=14f509aa32) | Mar 26, 2022 |
| ASUSTek       | H110M-K                     | [31098e4c80](https://linux-hardware.org/?probe=31098e4c80) | Mar 26, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [e4526228cd](https://linux-hardware.org/?probe=e4526228cd) | Mar 26, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [402c4d5758](https://linux-hardware.org/?probe=402c4d5758) | Mar 26, 2022 |
| MSI           | IONA                        | [1a625c0505](https://linux-hardware.org/?probe=1a625c0505) | Mar 25, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [fc2b611797](https://linux-hardware.org/?probe=fc2b611797) | Mar 25, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [d5a1c13ab1](https://linux-hardware.org/?probe=d5a1c13ab1) | Mar 25, 2022 |
| BESSTAR Te... | UM700                       | [b1ff998755](https://linux-hardware.org/?probe=b1ff998755) | Mar 24, 2022 |
| Gigabyte      | MZBAYAP-D9                  | [2c077e2993](https://linux-hardware.org/?probe=2c077e2993) | Mar 24, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [58cfc7fbae](https://linux-hardware.org/?probe=58cfc7fbae) | Mar 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [481f4ad619](https://linux-hardware.org/?probe=481f4ad619) | Mar 23, 2022 |
| AMI           | Cherry Trail CR             | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| AMI           | Cherry Trail CR             | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| MSI           | B550-A PRO                  | [2f713e8db8](https://linux-hardware.org/?probe=2f713e8db8) | Mar 19, 2022 |
| Dell          | 033FF6 A00                  | [8ba917619e](https://linux-hardware.org/?probe=8ba917619e) | Mar 19, 2022 |
| Dell          | 033FF6 A00                  | [48c7f5e6ae](https://linux-hardware.org/?probe=48c7f5e6ae) | Mar 19, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [73bf7d8080](https://linux-hardware.org/?probe=73bf7d8080) | Mar 19, 2022 |
| MSI           | B550-A PRO                  | [b4a188ad90](https://linux-hardware.org/?probe=b4a188ad90) | Mar 19, 2022 |
| HP            | 3397                        | [fe1ae429b1](https://linux-hardware.org/?probe=fe1ae429b1) | Mar 18, 2022 |
| ASRock        | G31M-VS2                    | [129721c7ce](https://linux-hardware.org/?probe=129721c7ce) | Mar 17, 2022 |
| Acer          | EM61SM/EM61PM               | [a33e5dfb8e](https://linux-hardware.org/?probe=a33e5dfb8e) | Mar 17, 2022 |
| ASUSTek       | PRIME B460M-A               | [bb8e459621](https://linux-hardware.org/?probe=bb8e459621) | Mar 17, 2022 |
| ASUSTek       | PRIME A320M-K               | [42ce115c70](https://linux-hardware.org/?probe=42ce115c70) | Mar 17, 2022 |
| ASUSTek       | PRIME Z690-A                | [228a532955](https://linux-hardware.org/?probe=228a532955) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| HP            | ProLiant MicroServer Gen... | [9da39d2356](https://linux-hardware.org/?probe=9da39d2356) | Mar 15, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | [c8809e0561](https://linux-hardware.org/?probe=c8809e0561) | Mar 15, 2022 |
| ASRock        | B85M DASH/OL R2.0           | [162abf1031](https://linux-hardware.org/?probe=162abf1031) | Mar 15, 2022 |
| Packard Be... | P5N-E SLI                   | [7b991e7fe6](https://linux-hardware.org/?probe=7b991e7fe6) | Mar 14, 2022 |
| Dell          | 0GM819                      | [bf94874639](https://linux-hardware.org/?probe=bf94874639) | Mar 13, 2022 |
| MSI           | B360M MORTAR                | [a00a055108](https://linux-hardware.org/?probe=a00a055108) | Mar 13, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [dfef2d9492](https://linux-hardware.org/?probe=dfef2d9492) | Mar 13, 2022 |
| Dell          | 0GM819                      | [acc1399bb2](https://linux-hardware.org/?probe=acc1399bb2) | Mar 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [0b912c2834](https://linux-hardware.org/?probe=0b912c2834) | Mar 12, 2022 |
| ASUSTek       | X99-A                       | [4c62821984](https://linux-hardware.org/?probe=4c62821984) | Mar 12, 2022 |
| ECS           | Nettle3                     | [7a96fa9c3f](https://linux-hardware.org/?probe=7a96fa9c3f) | Mar 12, 2022 |
| ASRock        | H270 Pro4                   | [ae79ca8557](https://linux-hardware.org/?probe=ae79ca8557) | Mar 12, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [798e5f6c43](https://linux-hardware.org/?probe=798e5f6c43) | Mar 09, 2022 |
| Acer          | Veriton X2610G              | [1f5f3ecca1](https://linux-hardware.org/?probe=1f5f3ecca1) | Mar 09, 2022 |
| Gigabyte      | GA-A75-UD4H                 | [7d31af4995](https://linux-hardware.org/?probe=7d31af4995) | Mar 08, 2022 |
| HP            | 1497                        | [f67b96c14e](https://linux-hardware.org/?probe=f67b96c14e) | Mar 07, 2022 |
| Pegatron      | 2AC3                        | [8d0b8e2e12](https://linux-hardware.org/?probe=8d0b8e2e12) | Mar 07, 2022 |
| Pegatron      | 2AC3                        | [ea3781cdac](https://linux-hardware.org/?probe=ea3781cdac) | Mar 07, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [bde9b00de4](https://linux-hardware.org/?probe=bde9b00de4) | Mar 07, 2022 |
| ASUSTek       | PRIME H510M-A               | [4521c22268](https://linux-hardware.org/?probe=4521c22268) | Mar 06, 2022 |
| MSI           | Z590-A PRO                  | [5f37c84d61](https://linux-hardware.org/?probe=5f37c84d61) | Mar 06, 2022 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [68250a6d74](https://linux-hardware.org/?probe=68250a6d74) | Mar 06, 2022 |
| ASUSTek       | PRIME H510M-A               | [6381e8c673](https://linux-hardware.org/?probe=6381e8c673) | Mar 06, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [a4335990af](https://linux-hardware.org/?probe=a4335990af) | Mar 05, 2022 |
| HP            | 339A                        | [c26acecee2](https://linux-hardware.org/?probe=c26acecee2) | Mar 05, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [70405d9cb0](https://linux-hardware.org/?probe=70405d9cb0) | Mar 05, 2022 |
| SiComputer    | Activa Pico                 | [ff99171465](https://linux-hardware.org/?probe=ff99171465) | Mar 05, 2022 |
| Foxconn       | Irvine HP P/N               | [1d37020507](https://linux-hardware.org/?probe=1d37020507) | Mar 03, 2022 |
| Lenovo        | 31900058 STD                | [bc59b862f4](https://linux-hardware.org/?probe=bc59b862f4) | Mar 02, 2022 |
| Intel         | H61 V1.05                   | [51ad5bd7b7](https://linux-hardware.org/?probe=51ad5bd7b7) | Mar 02, 2022 |
| ASRock        | 990FX Extreme9              | [408514b026](https://linux-hardware.org/?probe=408514b026) | Mar 01, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [e40aac52d8](https://linux-hardware.org/?probe=e40aac52d8) | Feb 28, 2022 |
| HP            | 09F8h                       | [19dc89049d](https://linux-hardware.org/?probe=19dc89049d) | Feb 28, 2022 |
| MSI           | Boston                      | [b5bf0fa044](https://linux-hardware.org/?probe=b5bf0fa044) | Feb 26, 2022 |
| Clientron ... | L700                        | [c2cebca02b](https://linux-hardware.org/?probe=c2cebca02b) | Feb 26, 2022 |
| ASRock        | A75 Extreme6                | [8db778fe6e](https://linux-hardware.org/?probe=8db778fe6e) | Feb 26, 2022 |
| Gigabyte      | F2A88X-D3H                  | [bc86e829a1](https://linux-hardware.org/?probe=bc86e829a1) | Feb 26, 2022 |
| Acer          | Aspire XC-830               | [89acf6268c](https://linux-hardware.org/?probe=89acf6268c) | Feb 25, 2022 |
| Clientron ... | L700                        | [0a16915d4f](https://linux-hardware.org/?probe=0a16915d4f) | Feb 23, 2022 |
| Clientron ... | L700                        | [64f361f774](https://linux-hardware.org/?probe=64f361f774) | Feb 23, 2022 |
| ASRock        | H310M-ITX/ac                | [c5a3dacac5](https://linux-hardware.org/?probe=c5a3dacac5) | Feb 23, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [db5c30632e](https://linux-hardware.org/?probe=db5c30632e) | Feb 22, 2022 |
| MSI           | MAG B460M MORTAR WIFI       | [50536f1318](https://linux-hardware.org/?probe=50536f1318) | Feb 22, 2022 |
| MSI           | MAG B460M MORTAR WIFI       | [b6a9e09f78](https://linux-hardware.org/?probe=b6a9e09f78) | Feb 22, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [286998a230](https://linux-hardware.org/?probe=286998a230) | Feb 22, 2022 |
| ASRock        | X370 Taichi                 | [d4d5aa3b0a](https://linux-hardware.org/?probe=d4d5aa3b0a) | Feb 21, 2022 |
| ASRock        | ALiveNF6P-VSTA              | [eb361d0491](https://linux-hardware.org/?probe=eb361d0491) | Feb 20, 2022 |
| Lenovo        | 3098 0B98401 PRO            | [709ca2add8](https://linux-hardware.org/?probe=709ca2add8) | Feb 20, 2022 |
| Unknown       | Intel X79                   | [7968affda8](https://linux-hardware.org/?probe=7968affda8) | Feb 19, 2022 |
| Proline       | ProlinePartner              | [df914c13d7](https://linux-hardware.org/?probe=df914c13d7) | Feb 19, 2022 |
| ASRock        | A320M-HDV                   | [6678e3ba4a](https://linux-hardware.org/?probe=6678e3ba4a) | Feb 18, 2022 |
| ASRock        | A320M-HDV                   | [f37110c1d5](https://linux-hardware.org/?probe=f37110c1d5) | Feb 18, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [5a5f32380c](https://linux-hardware.org/?probe=5a5f32380c) | Feb 18, 2022 |
| BESSTAR Te... | UM270 V1.0                  | [3228f18f20](https://linux-hardware.org/?probe=3228f18f20) | Feb 17, 2022 |
| Gigabyte      | H97M-D3H                    | [da5a6a7160](https://linux-hardware.org/?probe=da5a6a7160) | Feb 17, 2022 |
| HP            | 1497                        | [8693cfc8c8](https://linux-hardware.org/?probe=8693cfc8c8) | Feb 17, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [dba2436c5c](https://linux-hardware.org/?probe=dba2436c5c) | Feb 17, 2022 |
| MSI           | A520M-A PRO                 | [dbe8ddd097](https://linux-hardware.org/?probe=dbe8ddd097) | Feb 17, 2022 |
| Pegatron      | 2AB6                        | [4659956809](https://linux-hardware.org/?probe=4659956809) | Feb 17, 2022 |
| HP            | 304Ah                       | [8bbd035899](https://linux-hardware.org/?probe=8bbd035899) | Feb 16, 2022 |
| ASRock        | Q1900B-ITX                  | [b205b32b2a](https://linux-hardware.org/?probe=b205b32b2a) | Feb 16, 2022 |
| ASUSTek       | P5QPL-AM                    | [c42862bbdb](https://linux-hardware.org/?probe=c42862bbdb) | Feb 15, 2022 |
| ASUSTek       | P5QPL-AM                    | [185fed2422](https://linux-hardware.org/?probe=185fed2422) | Feb 15, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [71ecb0275e](https://linux-hardware.org/?probe=71ecb0275e) | Feb 15, 2022 |
| Gigabyte      | H81M-D2V                    | [283cf4fd8d](https://linux-hardware.org/?probe=283cf4fd8d) | Feb 15, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [b11d43558e](https://linux-hardware.org/?probe=b11d43558e) | Feb 15, 2022 |
| BESSTAR Te... | UM270 V1.0                  | [a2ee2f6a38](https://linux-hardware.org/?probe=a2ee2f6a38) | Feb 15, 2022 |
| ASRock        | 880GMH/USB3                 | [2789041a4d](https://linux-hardware.org/?probe=2789041a4d) | Feb 15, 2022 |
| YANYU         | H17SL                       | [0a6638d9c9](https://linux-hardware.org/?probe=0a6638d9c9) | Feb 14, 2022 |
| BESSTAR Te... | UM270 V1.0                  | [1916cd8623](https://linux-hardware.org/?probe=1916cd8623) | Feb 14, 2022 |
| MSI           | MS-7360                     | [9f4470ea28](https://linux-hardware.org/?probe=9f4470ea28) | Feb 13, 2022 |
| ASUSTek       | P8H61-M LX                  | [f1b4a515a3](https://linux-hardware.org/?probe=f1b4a515a3) | Feb 13, 2022 |
| HP            | 339A                        | [05148d7fb4](https://linux-hardware.org/?probe=05148d7fb4) | Feb 13, 2022 |
| Gateway       | SX2865 V1.0                 | [890768bebd](https://linux-hardware.org/?probe=890768bebd) | Feb 12, 2022 |
| HP            | 8767 A                      | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP            | 8767 A                      | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| Dell          | 0KH290                      | [c4684237ef](https://linux-hardware.org/?probe=c4684237ef) | Feb 12, 2022 |
| Unknown       | Unknown                     | [b1ed0635ab](https://linux-hardware.org/?probe=b1ed0635ab) | Feb 12, 2022 |
| Lenovo        | SHARKBAY NOK                | [dec96a3fee](https://linux-hardware.org/?probe=dec96a3fee) | Feb 12, 2022 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | [51095189f7](https://linux-hardware.org/?probe=51095189f7) | Feb 12, 2022 |
| Acer          | EM61SM/EM61PM               | [8398f79f2a](https://linux-hardware.org/?probe=8398f79f2a) | Feb 12, 2022 |
| ASRock        | A320M-DVS R4.0              | [5356027467](https://linux-hardware.org/?probe=5356027467) | Feb 12, 2022 |
| MSI           | MS-7345                     | [3412e837ef](https://linux-hardware.org/?probe=3412e837ef) | Feb 12, 2022 |
| MSI           | 0A48                        | [29ea38af38](https://linux-hardware.org/?probe=29ea38af38) | Feb 12, 2022 |
| HP            | 304Bh                       | [ee8368a314](https://linux-hardware.org/?probe=ee8368a314) | Feb 11, 2022 |
| Gigabyte      | H170M-HD3 DDR3-CF           | [5503a29249](https://linux-hardware.org/?probe=5503a29249) | Feb 11, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [a8c18662ff](https://linux-hardware.org/?probe=a8c18662ff) | Feb 10, 2022 |
| HP            | 2B34                        | [1281e2e4dd](https://linux-hardware.org/?probe=1281e2e4dd) | Feb 10, 2022 |
| Packard Be... | FIH57                       | [d0d43c4388](https://linux-hardware.org/?probe=d0d43c4388) | Feb 10, 2022 |
| HP            | 83E0                        | [12a6ad4f59](https://linux-hardware.org/?probe=12a6ad4f59) | Feb 10, 2022 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | [421e056029](https://linux-hardware.org/?probe=421e056029) | Feb 10, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [5afe97188b](https://linux-hardware.org/?probe=5afe97188b) | Feb 10, 2022 |
| ASUSTek       | B150M-K D3                  | [2f698f5683](https://linux-hardware.org/?probe=2f698f5683) | Feb 10, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [0094ddce46](https://linux-hardware.org/?probe=0094ddce46) | Feb 10, 2022 |
| Dell          | 0C27VV A00                  | [4ce2b5c0b9](https://linux-hardware.org/?probe=4ce2b5c0b9) | Feb 09, 2022 |
| ASUSTek       | M4A77TD                     | [7c3ac4c29f](https://linux-hardware.org/?probe=7c3ac4c29f) | Feb 09, 2022 |
| Dell          | 0773VG A00                  | [e81f82fd5e](https://linux-hardware.org/?probe=e81f82fd5e) | Feb 09, 2022 |
| ASUSTek       | Rampage Formula             | [2cf0349fbe](https://linux-hardware.org/?probe=2cf0349fbe) | Feb 08, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | [de476d2b5a](https://linux-hardware.org/?probe=de476d2b5a) | Feb 08, 2022 |
| Gigabyte      | Z390 UD                     | [523ae21d77](https://linux-hardware.org/?probe=523ae21d77) | Feb 08, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [73da97a50b](https://linux-hardware.org/?probe=73da97a50b) | Feb 07, 2022 |
| YANYU         | H17SL                       | [cd763ca612](https://linux-hardware.org/?probe=cd763ca612) | Feb 06, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [4664ace096](https://linux-hardware.org/?probe=4664ace096) | Feb 05, 2022 |
| Acer          | Aspire TC-115               | [03188d20fc](https://linux-hardware.org/?probe=03188d20fc) | Feb 05, 2022 |
| ASRock        | J4105M                      | [2f9baf0de0](https://linux-hardware.org/?probe=2f9baf0de0) | Feb 05, 2022 |
| Dell          | 0N826N A03                  | [87c3ec3dac](https://linux-hardware.org/?probe=87c3ec3dac) | Feb 04, 2022 |
| ASUSTek       | Puffer                      | [a0a948ecf5](https://linux-hardware.org/?probe=a0a948ecf5) | Feb 04, 2022 |
| Gigabyte      | P35-DS3L                    | [20541a0b3c](https://linux-hardware.org/?probe=20541a0b3c) | Feb 02, 2022 |
| ASUSTek       | H87M-PRO                    | [0f96c91905](https://linux-hardware.org/?probe=0f96c91905) | Feb 01, 2022 |
| ASUSTek       | CM6870                      | [f217244fb2](https://linux-hardware.org/?probe=f217244fb2) | Jan 31, 2022 |
| ASRock        | 890GX Extreme3              | [30d08c4c1f](https://linux-hardware.org/?probe=30d08c4c1f) | Jan 31, 2022 |
| Chuwi         | RZBOX                       | [bea5e134d8](https://linux-hardware.org/?probe=bea5e134d8) | Jan 30, 2022 |
| Gigabyte      | H110M-S2H-CF                | [fe5bd0b5ed](https://linux-hardware.org/?probe=fe5bd0b5ed) | Jan 29, 2022 |
| ASUSTek       | Z170-K                      | [33d0a3b270](https://linux-hardware.org/?probe=33d0a3b270) | Jan 29, 2022 |
| ASUSTek       | P5Q PRO TURBO               | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| ASUSTek       | Z97-PRO                     | [256f789c6d](https://linux-hardware.org/?probe=256f789c6d) | Jan 27, 2022 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [044e014d11](https://linux-hardware.org/?probe=044e014d11) | Jan 26, 2022 |
| ASUSTek       | H97M-E                      | [5e3573c525](https://linux-hardware.org/?probe=5e3573c525) | Jan 26, 2022 |
| HP            | 1905                        | [d0ef619547](https://linux-hardware.org/?probe=d0ef619547) | Jan 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7f69220928](https://linux-hardware.org/?probe=7f69220928) | Jan 24, 2022 |
| ASUSTek       | H81M-K                      | [6b834ecf57](https://linux-hardware.org/?probe=6b834ecf57) | Jan 24, 2022 |
| ASRock        | AB350M Pro4                 | [cae6b39683](https://linux-hardware.org/?probe=cae6b39683) | Jan 24, 2022 |
| ASRock        | AB350M Pro4                 | [75e0b58fa2](https://linux-hardware.org/?probe=75e0b58fa2) | Jan 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [868c5fe3a4](https://linux-hardware.org/?probe=868c5fe3a4) | Jan 24, 2022 |
| ASRock        | AM1B-ITX                    | [5f089eb5bf](https://linux-hardware.org/?probe=5f089eb5bf) | Jan 24, 2022 |
| Acer          | FIH57                       | [af79e42583](https://linux-hardware.org/?probe=af79e42583) | Jan 23, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [ada27693c4](https://linux-hardware.org/?probe=ada27693c4) | Jan 21, 2022 |
| ASRock        | H510 Pro BTC+               | [ff2dd45add](https://linux-hardware.org/?probe=ff2dd45add) | Jan 21, 2022 |
| ASRock        | H510 Pro BTC+               | [234acd7143](https://linux-hardware.org/?probe=234acd7143) | Jan 21, 2022 |
| Gigabyte      | Z390 UD                     | [cf1efe764d](https://linux-hardware.org/?probe=cf1efe764d) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [3b7c230363](https://linux-hardware.org/?probe=3b7c230363) | Jan 21, 2022 |
| Unknown       | HX90                        | [43efcb00a2](https://linux-hardware.org/?probe=43efcb00a2) | Jan 20, 2022 |
| Gigabyte      | B460M D3H                   | [d64f06fd5a](https://linux-hardware.org/?probe=d64f06fd5a) | Jan 20, 2022 |
| Unknown       | HX90                        | [d12701e394](https://linux-hardware.org/?probe=d12701e394) | Jan 19, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [993543545b](https://linux-hardware.org/?probe=993543545b) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [7e0c6ebfc9](https://linux-hardware.org/?probe=7e0c6ebfc9) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [d531de56b2](https://linux-hardware.org/?probe=d531de56b2) | Jan 18, 2022 |
| Gigabyte      | MZBSWBP-00                  | [a8699a0a00](https://linux-hardware.org/?probe=a8699a0a00) | Jan 18, 2022 |
| ASRock        | H61M-HVS                    | [95bbde94a9](https://linux-hardware.org/?probe=95bbde94a9) | Jan 18, 2022 |
| HP            | 1495                        | [f67a5913e3](https://linux-hardware.org/?probe=f67a5913e3) | Jan 17, 2022 |
| ASRock        | B450M Pro4-F                | [f55512e3bc](https://linux-hardware.org/?probe=f55512e3bc) | Jan 17, 2022 |
| Gigabyte      | Z97M-D3H                    | [dfbc85bafe](https://linux-hardware.org/?probe=dfbc85bafe) | Jan 17, 2022 |
| ASUSTek       | Z87-A                       | [b6d5a58347](https://linux-hardware.org/?probe=b6d5a58347) | Jan 17, 2022 |
| Dell          | 0PP150 A00                  | [554774c3c8](https://linux-hardware.org/?probe=554774c3c8) | Jan 16, 2022 |
| Unknown       | K8Upgrade-1689              | [d2e29b9e82](https://linux-hardware.org/?probe=d2e29b9e82) | Jan 15, 2022 |
| ASUSTek       | H110-PLUS                   | [baea3e1d59](https://linux-hardware.org/?probe=baea3e1d59) | Jan 13, 2022 |
| Unknown       | T3 MRD                      | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| ASRock        | FM2A88M-HD+                 | [2d834a40f5](https://linux-hardware.org/?probe=2d834a40f5) | Jan 10, 2022 |
| Unknown       | RS780-SB700                 | [b5bd3c5c5d](https://linux-hardware.org/?probe=b5bd3c5c5d) | Jan 10, 2022 |
| HP            | 09F8h                       | [b17a2aef1b](https://linux-hardware.org/?probe=b17a2aef1b) | Jan 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [b431bed91e](https://linux-hardware.org/?probe=b431bed91e) | Jan 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1ef1dec7bc](https://linux-hardware.org/?probe=1ef1dec7bc) | Jan 09, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [cba57c7cfe](https://linux-hardware.org/?probe=cba57c7cfe) | Jan 09, 2022 |
| ASUSTek       | PRIME H310M-K               | [3b4d6e5abd](https://linux-hardware.org/?probe=3b4d6e5abd) | Jan 08, 2022 |
| ASUSTek       | P5K-E                       | [f3ebd22f2f](https://linux-hardware.org/?probe=f3ebd22f2f) | Jan 08, 2022 |
| ASUSTek       | P8P67 DELUXE                | [9bd6fe4b7c](https://linux-hardware.org/?probe=9bd6fe4b7c) | Jan 08, 2022 |
| ASUSTek       | H110-PLUS                   | [c3fd3de501](https://linux-hardware.org/?probe=c3fd3de501) | Jan 08, 2022 |
| HP            | 3397                        | [38a4d731fe](https://linux-hardware.org/?probe=38a4d731fe) | Jan 08, 2022 |
| ASRock        | N68-S3 UCC                  | [bfcf287c09](https://linux-hardware.org/?probe=bfcf287c09) | Jan 08, 2022 |
| MSI           | X570-A PRO                  | [8319fcd2fe](https://linux-hardware.org/?probe=8319fcd2fe) | Jan 07, 2022 |
| ASUSTek       | PRIME J4005I-C              | [b73988a1c9](https://linux-hardware.org/?probe=b73988a1c9) | Jan 07, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [be76fa91bc](https://linux-hardware.org/?probe=be76fa91bc) | Jan 05, 2022 |
| Gigabyte      | GA-970A-D3                  | [98280b3f37](https://linux-hardware.org/?probe=98280b3f37) | Jan 04, 2022 |
| Dell          | 0MM599                      | [82532cb19f](https://linux-hardware.org/?probe=82532cb19f) | Jan 03, 2022 |
| ASRock        | G41C-GS                     | [841dc47501](https://linux-hardware.org/?probe=841dc47501) | Jan 01, 2022 |
| ABIT          | AW9D-MAX                    | [104f0e6fde](https://linux-hardware.org/?probe=104f0e6fde) | Jan 01, 2022 |
| HP            | 0AA0h                       | [bf7b3e968e](https://linux-hardware.org/?probe=bf7b3e968e) | Jan 01, 2022 |
| MSI           | 760GM-P23                   | [96ce7a909b](https://linux-hardware.org/?probe=96ce7a909b) | Jan 01, 2022 |
| ASRock        | 970 Pro3 R2.0               | [398a0cf729](https://linux-hardware.org/?probe=398a0cf729) | Dec 30, 2021 |
| ASUSTek       | P8H61                       | [682efb70d7](https://linux-hardware.org/?probe=682efb70d7) | Dec 29, 2021 |
| ASRock        | Z87 Pro4                    | [2a8588f61e](https://linux-hardware.org/?probe=2a8588f61e) | Dec 29, 2021 |
| HP            | 2AF7                        | [646ae9f001](https://linux-hardware.org/?probe=646ae9f001) | Dec 29, 2021 |
| Gigabyte      | P35-DS3L                    | [e13fea24e4](https://linux-hardware.org/?probe=e13fea24e4) | Dec 27, 2021 |
| ASUSTek       | CM6870                      | [0a24371b49](https://linux-hardware.org/?probe=0a24371b49) | Dec 27, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [d139e4cfa0](https://linux-hardware.org/?probe=d139e4cfa0) | Dec 27, 2021 |
| MSI           | B450M MORTAR MAX            | [82cd3a640e](https://linux-hardware.org/?probe=82cd3a640e) | Dec 26, 2021 |
| MSI           | B450M MORTAR MAX            | [bcfc2dd514](https://linux-hardware.org/?probe=bcfc2dd514) | Dec 25, 2021 |
| Dell          | 0VNP2H A00                  | [e64f51e52a](https://linux-hardware.org/?probe=e64f51e52a) | Dec 24, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [fa1d026542](https://linux-hardware.org/?probe=fa1d026542) | Dec 23, 2021 |
| ASRock        | 970 Extreme4                | [1fbef2b76c](https://linux-hardware.org/?probe=1fbef2b76c) | Dec 23, 2021 |
| MSI           | A68HM-P33 V2                | [4b36ec9c1a](https://linux-hardware.org/?probe=4b36ec9c1a) | Dec 23, 2021 |
| ASUSTek       | P5P43TD PRO                 | [6019461793](https://linux-hardware.org/?probe=6019461793) | Dec 22, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | [c66f391530](https://linux-hardware.org/?probe=c66f391530) | Dec 22, 2021 |
| ASUSTek       | H97M-PLUS                   | [d81c8e7d01](https://linux-hardware.org/?probe=d81c8e7d01) | Dec 18, 2021 |
| Unknown       | Intel X79                   | [767fb84ac9](https://linux-hardware.org/?probe=767fb84ac9) | Dec 17, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [92f0b24884](https://linux-hardware.org/?probe=92f0b24884) | Dec 16, 2021 |
| Dell          | 0WR7PY A02                  | [459b162eab](https://linux-hardware.org/?probe=459b162eab) | Dec 16, 2021 |
| ASRock        | X58 Extreme                 | [ac26e59e63](https://linux-hardware.org/?probe=ac26e59e63) | Dec 15, 2021 |
| MSI           | Z97 GUARD-PRO               | [dcc4b73b5c](https://linux-hardware.org/?probe=dcc4b73b5c) | Dec 14, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [bdfec258d5](https://linux-hardware.org/?probe=bdfec258d5) | Dec 12, 2021 |
| HP            | 1495                        | [05cbcf49b8](https://linux-hardware.org/?probe=05cbcf49b8) | Dec 12, 2021 |
| ASUSTek       | M4A88TD-M EVO               | [815ae34e1d](https://linux-hardware.org/?probe=815ae34e1d) | Dec 11, 2021 |
| ASUSTek       | P6T DELUXE V2               | [def7aa454b](https://linux-hardware.org/?probe=def7aa454b) | Dec 11, 2021 |
| Acer          | Aspire X5950                | [26b0d257ef](https://linux-hardware.org/?probe=26b0d257ef) | Dec 10, 2021 |
| ASRock        | H170A-X1                    | [9e5931fa7d](https://linux-hardware.org/?probe=9e5931fa7d) | Dec 10, 2021 |
| ASUSTek       | Z170M-PLUS                  | [730046deb9](https://linux-hardware.org/?probe=730046deb9) | Dec 09, 2021 |
| Dell          | 040DDP A01                  | [b8e92a4957](https://linux-hardware.org/?probe=b8e92a4957) | Dec 09, 2021 |
| Gigabyte      | H77-DS3H                    | [5754691e4b](https://linux-hardware.org/?probe=5754691e4b) | Dec 08, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [160b6097cd](https://linux-hardware.org/?probe=160b6097cd) | Dec 08, 2021 |
| HP            | 8184 X4                     | [3a2d5e3c77](https://linux-hardware.org/?probe=3a2d5e3c77) | Dec 08, 2021 |
| HP            | 8184 X4                     | [e225665abc](https://linux-hardware.org/?probe=e225665abc) | Dec 08, 2021 |
| Acer          | Veriton E430 v1.0           | [5c857f1bb6](https://linux-hardware.org/?probe=5c857f1bb6) | Dec 08, 2021 |
| ASRock        | M3A770DE                    | [f0f197bdf8](https://linux-hardware.org/?probe=f0f197bdf8) | Dec 07, 2021 |
| MSI           | Z390-A PRO                  | [f67e3e407c](https://linux-hardware.org/?probe=f67e3e407c) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [4c55363bc2](https://linux-hardware.org/?probe=4c55363bc2) | Dec 04, 2021 |
| Gigabyte      | H310N x.x                   | [57267d12ff](https://linux-hardware.org/?probe=57267d12ff) | Dec 03, 2021 |
| ASRock        | X58 Extreme                 | [1a9d6547f0](https://linux-hardware.org/?probe=1a9d6547f0) | Dec 03, 2021 |
| ASUSTek       | LEONITE                     | [704345be69](https://linux-hardware.org/?probe=704345be69) | Dec 03, 2021 |
| Unknown       | Intel X79                   | [e1ef0e8dc9](https://linux-hardware.org/?probe=e1ef0e8dc9) | Dec 02, 2021 |
| Dell          | 040DDP A01                  | [b108ae97c2](https://linux-hardware.org/?probe=b108ae97c2) | Dec 02, 2021 |
| Lenovo        | ThinkCentre A52 8381W7G     | [3439a0acde](https://linux-hardware.org/?probe=3439a0acde) | Dec 02, 2021 |
| Gigabyte      | P35-DS3L                    | [2e5a8410bc](https://linux-hardware.org/?probe=2e5a8410bc) | Dec 01, 2021 |
| ASRock        | G41M-VS3                    | [e2d4b12fef](https://linux-hardware.org/?probe=e2d4b12fef) | Dec 01, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [1d6ece4240](https://linux-hardware.org/?probe=1d6ece4240) | Dec 01, 2021 |
| ASRock        | Q1900-ITX                   | [878cd074fb](https://linux-hardware.org/?probe=878cd074fb) | Nov 30, 2021 |
| ASRock        | Q1900-ITX                   | [3468f76ee4](https://linux-hardware.org/?probe=3468f76ee4) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | [fe3d4f5bc1](https://linux-hardware.org/?probe=fe3d4f5bc1) | Nov 30, 2021 |
| LattePanda    | Delta CDJQ-BI-7-S70GR200... | [25d7f6e054](https://linux-hardware.org/?probe=25d7f6e054) | Nov 30, 2021 |
| ASUSTek       | P5QL                        | [70e9ac5d75](https://linux-hardware.org/?probe=70e9ac5d75) | Nov 29, 2021 |
| Dell          | 0XPDFK A00                  | [50d479c71e](https://linux-hardware.org/?probe=50d479c71e) | Nov 29, 2021 |
| Unknown       | Unknown                     | [08926b737d](https://linux-hardware.org/?probe=08926b737d) | Nov 28, 2021 |
| HP            | 8299                        | [105c1751dc](https://linux-hardware.org/?probe=105c1751dc) | Nov 28, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [8ffbfad5e8](https://linux-hardware.org/?probe=8ffbfad5e8) | Nov 27, 2021 |
| Dell          | 0VNP2H A00                  | [803e55fd86](https://linux-hardware.org/?probe=803e55fd86) | Nov 27, 2021 |
| ASRock        | H61M-VS                     | [4aefcd6dd3](https://linux-hardware.org/?probe=4aefcd6dd3) | Nov 27, 2021 |
| ASRock        | ALiveNF6G-DVI               | [2761f434e8](https://linux-hardware.org/?probe=2761f434e8) | Nov 26, 2021 |
| ASRock        | 970M Pro3                   | [3c1b7aba70](https://linux-hardware.org/?probe=3c1b7aba70) | Nov 26, 2021 |
| Gigabyte      | H77M-D3H                    | [a2606aebd8](https://linux-hardware.org/?probe=a2606aebd8) | Nov 26, 2021 |
| MSI           | B450M-A PRO MAX             | [602d5d0655](https://linux-hardware.org/?probe=602d5d0655) | Nov 26, 2021 |
| Dell          | 0VNP2H A00                  | [fe9de9a896](https://linux-hardware.org/?probe=fe9de9a896) | Nov 25, 2021 |
| Acer          | EG43M                       | [328e16606e](https://linux-hardware.org/?probe=328e16606e) | Nov 25, 2021 |
| HP            | 8054                        | [28cdc58146](https://linux-hardware.org/?probe=28cdc58146) | Nov 25, 2021 |
| Lenovo        | ThinkCentre A52 8381W7G     | [6a0e22157b](https://linux-hardware.org/?probe=6a0e22157b) | Nov 24, 2021 |
| HP            | 339A                        | [1a13b170eb](https://linux-hardware.org/?probe=1a13b170eb) | Nov 23, 2021 |
| ASRock        | H81M-DGS R2.0               | [138f5b0109](https://linux-hardware.org/?probe=138f5b0109) | Nov 23, 2021 |
| HP            | 1495                        | [6be5bb9489](https://linux-hardware.org/?probe=6be5bb9489) | Nov 22, 2021 |
| ASRock        | P67 Extreme6                | [54cd91039c](https://linux-hardware.org/?probe=54cd91039c) | Nov 22, 2021 |
| ASRock        | ALiveNF6G-DVI               | [23a839f917](https://linux-hardware.org/?probe=23a839f917) | Nov 21, 2021 |
| HP            | 1495                        | [f52ded8998](https://linux-hardware.org/?probe=f52ded8998) | Nov 20, 2021 |
| Lenovo        | ThinkServer TS140           | [da5af2478e](https://linux-hardware.org/?probe=da5af2478e) | Nov 20, 2021 |
| ASUSTek       | PRIME H510M-K               | [dc3ffc2288](https://linux-hardware.org/?probe=dc3ffc2288) | Nov 20, 2021 |
| HP            | 3047h                       | [a8b27aa212](https://linux-hardware.org/?probe=a8b27aa212) | Nov 20, 2021 |
| HP            | 304Ah                       | [988e1e374a](https://linux-hardware.org/?probe=988e1e374a) | Nov 18, 2021 |
| HP            | 1494                        | [a1e8628159](https://linux-hardware.org/?probe=a1e8628159) | Nov 17, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [246e62e738](https://linux-hardware.org/?probe=246e62e738) | Nov 16, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9404dfb1fe](https://linux-hardware.org/?probe=9404dfb1fe) | Nov 16, 2021 |
| ASRock        | B450M Pro4                  | [2cdd151d75](https://linux-hardware.org/?probe=2cdd151d75) | Nov 14, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [71342b9603](https://linux-hardware.org/?probe=71342b9603) | Nov 14, 2021 |
| ASUSTek       | M4A77TD PRO                 | [fadecb8927](https://linux-hardware.org/?probe=fadecb8927) | Nov 14, 2021 |
| HP            | 1495                        | [5fd0d39362](https://linux-hardware.org/?probe=5fd0d39362) | Nov 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [7ae75212ce](https://linux-hardware.org/?probe=7ae75212ce) | Nov 13, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [5d283e7da8](https://linux-hardware.org/?probe=5d283e7da8) | Nov 13, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [f609e8c701](https://linux-hardware.org/?probe=f609e8c701) | Nov 12, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a13e2b71e5](https://linux-hardware.org/?probe=a13e2b71e5) | Nov 12, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu 20.04     | 369      | 15.6%   |
| Ubuntu 18.04     | 241      | 10.19%  |
| OpenMandriva 4.2 | 100      | 4.23%   |
| Ubuntu 22.04     | 83       | 3.51%   |
| OpenMandriva 4.3 | 66       | 2.79%   |
| Ubuntu 20.10     | 51       | 2.16%   |
| Ubuntu 19.04     | 47       | 1.99%   |
| Arch Rolling     | 46       | 1.95%   |
| Debian 11        | 43       | 1.82%   |
| Ubuntu 19.10     | 42       | 1.78%   |
| KDE neon 20.04   | 42       | 1.78%   |
| Fedora 36        | 42       | 1.78%   |
| Xubuntu 20.04    | 36       | 1.52%   |
| Arch             | 36       | 1.52%   |
| Xubuntu 18.04    | 33       | 1.4%    |
| ROSA R10         | 32       | 1.35%   |
| Ubuntu 21.10     | 31       | 1.31%   |
| Ubuntu 21.04     | 31       | 1.31%   |
| Linux Mint 20.3  | 30       | 1.27%   |
| Debian 10        | 29       | 1.23%   |
| Manjaro          | 28       | 1.18%   |
| Linux Mint 21    | 28       | 1.18%   |
| Zorin 16         | 26       | 1.1%    |
| Linux Mint 19.3  | 25       | 1.06%   |
| Kubuntu 20.04    | 25       | 1.06%   |
| Ubuntu 18.10     | 24       | 1.01%   |
| Linux Mint 20.1  | 22       | 0.93%   |
| Pop!_OS 22.04    | 21       | 0.89%   |
| Linux Mint 20.2  | 21       | 0.89%   |
| Linux Mint 20    | 21       | 0.89%   |
| ROSA R11         | 20       | 0.85%   |
| ROSA R9          | 19       | 0.8%    |
| Zorin 15         | 18       | 0.76%   |
| Pop!_OS 20.10    | 18       | 0.76%   |
| Fedora 35        | 17       | 0.72%   |
| Ubuntu 16.04     | 15       | 0.63%   |
| Fedora 33        | 15       | 0.63%   |
| Fedora 32        | 15       | 0.63%   |
| ROSA R11.1       | 14       | 0.59%   |
| Manjaro 22.0.0   | 14       | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 902      | 40.11%  |
| OpenMandriva  | 186      | 8.27%   |
| Linux Mint    | 158      | 7.03%   |
| Fedora        | 111      | 4.94%   |
| Xubuntu       | 103      | 4.58%   |
| Debian        | 95       | 4.22%   |
| ROSA          | 90       | 4%      |
| Arch          | 81       | 3.6%    |
| Manjaro       | 69       | 3.07%   |
| Pop!_OS       | 68       | 3.02%   |
| KDE neon      | 56       | 2.49%   |
| Kubuntu       | 55       | 2.45%   |
| Zorin         | 48       | 2.13%   |
| Lubuntu       | 25       | 1.11%   |
| Ubuntu MATE   | 21       | 0.93%   |
| Ubuntu Unity  | 17       | 0.76%   |
| EndeavourOS   | 17       | 0.76%   |
| Clear Linux   | 13       | 0.58%   |
| BlackPanther  | 13       | 0.58%   |
| openSUSE      | 12       | 0.53%   |
| Endless       | 10       | 0.44%   |
| Peppermint    | 9        | 0.4%    |
| Gentoo        | 9        | 0.4%    |
| LMDE          | 8        | 0.36%   |
| Elementary    | 8        | 0.36%   |
| Garuda Linux  | 6        | 0.27%   |
| ArcoLinux     | 6        | 0.27%   |
| Ubuntu Studio | 5        | 0.22%   |
| MX            | 5        | 0.22%   |
| Slackware     | 4        | 0.18%   |
| LinuxFX       | 4        | 0.18%   |
| CentOS        | 4        | 0.18%   |
| Q4OS          | 3        | 0.13%   |
| Ubuntu Budgie | 2        | 0.09%   |
| Rocky Linux   | 2        | 0.09%   |
| RHEL          | 2        | 0.09%   |
| Puppy         | 2        | 0.09%   |
| Parrot        | 2        | 0.09%   |
| Kali          | 2        | 0.09%   |
| Chrome OS     | 2        | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 98       | 3.72%   |
| 5.16.7-desktop-1omv4003         | 65       | 2.47%   |
| 5.15.0-52-generic               | 57       | 2.16%   |
| 5.4.0-42-generic                | 52       | 1.97%   |
| 5.4.0-52-generic                | 43       | 1.63%   |
| 5.15.0-47-generic               | 33       | 1.25%   |
| 5.4.0-58-generic                | 24       | 0.91%   |
| 5.4.0-48-generic                | 24       | 0.91%   |
| 5.3.0-46-generic                | 23       | 0.87%   |
| 5.3.0-40-generic                | 23       | 0.87%   |
| 5.4.0-56-generic                | 22       | 0.83%   |
| 5.4.0-29-generic                | 21       | 0.8%    |
| 5.4.0-26-generic                | 21       | 0.8%    |
| 5.4.0-54-generic                | 20       | 0.76%   |
| 5.15.0-46-generic               | 20       | 0.76%   |
| 5.4.0-40-generic                | 19       | 0.72%   |
| 5.4.0-28-generic                | 18       | 0.68%   |
| 5.11.0-38-generic               | 18       | 0.68%   |
| 5.0.0-32-generic                | 18       | 0.68%   |
| 5.8.0-59-generic                | 16       | 0.61%   |
| 5.4.0-37-generic                | 16       | 0.61%   |
| 5.8.0-41-generic                | 15       | 0.57%   |
| 5.4.0-65-generic                | 15       | 0.57%   |
| 5.4.0-33-generic                | 15       | 0.57%   |
| 5.3.0-42-generic                | 15       | 0.57%   |
| 5.4.0-47-generic                | 14       | 0.53%   |
| 5.4.0-31-generic                | 14       | 0.53%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 14       | 0.53%   |
| 4.18.0-25-generic               | 14       | 0.53%   |
| 5.8.0-48-generic                | 13       | 0.49%   |
| 5.13.0-39-generic               | 13       | 0.49%   |
| 5.11.0-27-generic               | 13       | 0.49%   |
| 4.18.16-desktop-1bP             | 13       | 0.49%   |
| 4.15.0-29-generic               | 13       | 0.49%   |
| 5.19.0-23-generic               | 12       | 0.46%   |
| 5.15.0-43-generic               | 12       | 0.46%   |
| 5.11.0-41-generic               | 12       | 0.46%   |
| 5.10.0-19-amd64                 | 12       | 0.46%   |
| 5.0.0-27-generic                | 12       | 0.46%   |
| 5.0.0-23-generic                | 12       | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 495      | 20.3%   |
| 4.15.0  | 208      | 8.53%   |
| 5.15.0  | 176      | 7.22%   |
| 5.8.0   | 162      | 6.64%   |
| 5.3.0   | 140      | 5.74%   |
| 5.11.0  | 115      | 4.72%   |
| 5.10.14 | 99       | 4.06%   |
| 5.0.0   | 99       | 4.06%   |
| 5.13.0  | 83       | 3.4%    |
| 5.16.7  | 66       | 2.71%   |
| 4.18.0  | 65       | 2.67%   |
| 5.10.0  | 50       | 2.05%   |
| 5.19.0  | 28       | 1.15%   |
| 6.0.2   | 27       | 1.11%   |
| 4.19.0  | 27       | 1.11%   |
| 4.9.60  | 18       | 0.74%   |
| 4.9.20  | 17       | 0.7%    |
| 5.19.6  | 15       | 0.62%   |
| 4.18.16 | 14       | 0.57%   |
| 5.19.16 | 13       | 0.53%   |
| 6.0.6   | 11       | 0.45%   |
| 5.17.5  | 10       | 0.41%   |
| 4.4.0   | 9        | 0.37%   |
| 5.12.4  | 8        | 0.33%   |
| 6.0.9   | 7        | 0.29%   |
| 6.0.5   | 7        | 0.29%   |
| 5.19.4  | 7        | 0.29%   |
| 5.18.12 | 7        | 0.29%   |
| 5.16.11 | 7        | 0.29%   |
| 6.0.8   | 6        | 0.25%   |
| 5.9.16  | 6        | 0.25%   |
| 5.4.32  | 6        | 0.25%   |
| 5.15.15 | 6        | 0.25%   |
| 4.1.34  | 6        | 0.25%   |
| 6.0.7   | 5        | 0.21%   |
| 5.9.1   | 5        | 0.21%   |
| 5.8.18  | 5        | 0.21%   |
| 5.15.7  | 5        | 0.21%   |
| 4.9.155 | 5        | 0.21%   |
| 5.9.14  | 4        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 521      | 21.63%  |
| 5.15    | 223      | 9.26%   |
| 4.15    | 209      | 8.68%   |
| 5.8     | 186      | 7.72%   |
| 5.10    | 177      | 7.35%   |
| 5.3     | 145      | 6.02%   |
| 5.11    | 134      | 5.56%   |
| 5.0     | 102      | 4.23%   |
| 5.16    | 92       | 3.82%   |
| 5.13    | 91       | 3.78%   |
| 5.19    | 86       | 3.57%   |
| 4.18    | 83       | 3.45%   |
| 6.0     | 66       | 2.74%   |
| 4.9     | 54       | 2.24%   |
| 4.19    | 37       | 1.54%   |
| 5.9     | 32       | 1.33%   |
| 5.17    | 28       | 1.16%   |
| 5.18    | 24       | 1%      |
| 5.6     | 20       | 0.83%   |
| 5.12    | 20       | 0.83%   |
| 5.7     | 18       | 0.75%   |
| 5.14    | 14       | 0.58%   |
| 4.1     | 10       | 0.42%   |
| 5.5     | 9        | 0.37%   |
| 4.4     | 9        | 0.37%   |
| 4.13    | 5        | 0.21%   |
| 5.1     | 2        | 0.08%   |
| 4.20    | 2        | 0.08%   |
| 6.1     | 1        | 0.04%   |
| 5.2     | 1        | 0.04%   |
| 4.8     | 1        | 0.04%   |
| 4.7     | 1        | 0.04%   |
| 4.17    | 1        | 0.04%   |
| 4.14    | 1        | 0.04%   |
| 4.12    | 1        | 0.04%   |
| 3.14    | 1        | 0.04%   |
| 3.10    | 1        | 0.04%   |
| 2.6.35  | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2084     | 95.29%  |
| i686   | 103      | 4.71%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 902      | 39.58%  |
| KDE5             | 397      | 17.42%  |
| Unknown          | 352      | 15.45%  |
| XFCE             | 184      | 8.07%   |
| X-Cinnamon       | 127      | 5.57%   |
| MATE             | 64       | 2.81%   |
| KDE              | 61       | 2.68%   |
| KDE4             | 57       | 2.5%    |
| LXQt             | 32       | 1.4%    |
| LXDE             | 19       | 0.83%   |
| Cinnamon         | 19       | 0.83%   |
| Unity            | 17       | 0.75%   |
| GNOME Flashback  | 10       | 0.44%   |
| Pantheon         | 7        | 0.31%   |
| GNOME Classic    | 6        | 0.26%   |
| Deepin           | 5        | 0.22%   |
| i3               | 4        | 0.18%   |
| Trinity          | 3        | 0.13%   |
| lightdm-xsession | 3        | 0.13%   |
| Budgie           | 3        | 0.13%   |
| Openbox          | 2        | 0.09%   |
| sway             | 1        | 0.04%   |
| Lubuntu          | 1        | 0.04%   |
| herbstluftwm     | 1        | 0.04%   |
| FVWM             | 1        | 0.04%   |
| bspwm            | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1812     | 80.89%  |
| Wayland | 211      | 9.42%   |
| Unknown | 184      | 8.21%   |
| Tty     | 33       | 1.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1219     | 53.58%  |
| SDDM    | 377      | 16.57%  |
| GDM3    | 189      | 8.31%   |
| GDM     | 184      | 8.09%   |
| LightDM | 178      | 7.82%   |
| TDM     | 61       | 2.68%   |
| KDM     | 59       | 2.59%   |
| XDM     | 4        | 0.18%   |
| GREETD  | 2        | 0.09%   |
| NODM    | 1        | 0.04%   |
| LXDM    | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| it_IT       | 1412     | 63.15%  |
| Unknown     | 382      | 17.08%  |
| en_US       | 342      | 15.3%   |
| en_GB       | 43       | 1.92%   |
| C           | 31       | 1.39%   |
| it_CH       | 4        | 0.18%   |
| ru_RU       | 3        | 0.13%   |
| de_DE       | 3        | 0.13%   |
| de_AT       | 3        | 0.13%   |
| fr_FR       | 2        | 0.09%   |
| en_IE       | 2        | 0.09%   |
| de_IT       | 2        | 0.09%   |
| it_ITutf8   | 1        | 0.04%   |
| hu_HU       | 1        | 0.04%   |
| es_MX       | 1        | 0.04%   |
| es_ES       | 1        | 0.04%   |
| en_US.ASCII | 1        | 0.04%   |
| en_AG       | 1        | 0.04%   |
| Default     | 1        | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1439     | 64.56%  |
| EFI  | 790      | 35.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1721     | 77.17%  |
| Overlay | 219      | 9.82%   |
| Unknown | 117      | 5.25%   |
| Btrfs   | 116      | 5.2%    |
| Xfs     | 26       | 1.17%   |
| Ext3    | 9        | 0.4%    |
| Zfs     | 8        | 0.36%   |
| Ext2    | 7        | 0.31%   |
| Tmpfs   | 3        | 0.13%   |
| Aufs    | 2        | 0.09%   |
| XXXX    | 1        | 0.04%   |
| F2fs    | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1314     | 58.82%  |
| GPT     | 605      | 27.08%  |
| MBR     | 315      | 14.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1756     | 78.39%  |
| Yes       | 484      | 21.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1290     | 57.74%  |
| Yes       | 944      | 42.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 707      | 32.37%  |
| ASRock              | 275      | 12.59%  |
| MSI                 | 259      | 11.86%  |
| Gigabyte Technology | 208      | 9.52%   |
| Hewlett-Packard     | 171      | 7.83%   |
| Dell                | 105      | 4.81%   |
| Acer                | 87       | 3.98%   |
| Lenovo              | 67       | 3.07%   |
| Intel               | 49       | 2.24%   |
| Pegatron            | 33       | 1.51%   |
| Unknown             | 29       | 1.33%   |
| Packard Bell        | 24       | 1.1%    |
| Fujitsu             | 23       | 1.05%   |
| Foxconn             | 21       | 0.96%   |
| Fujitsu Siemens     | 12       | 0.55%   |
| Supermicro          | 9        | 0.41%   |
| Biostar             | 8        | 0.37%   |
| BESSTAR Tech        | 7        | 0.32%   |
| AMI                 | 7        | 0.32%   |
| AZW                 | 6        | 0.27%   |
| ABIT                | 6        | 0.27%   |
| TYAN Computer       | 5        | 0.23%   |
| Sapphire            | 5        | 0.23%   |
| IBM                 | 5        | 0.23%   |
| Apple               | 5        | 0.23%   |
| Wistron             | 4        | 0.18%   |
| NEC Computers       | 4        | 0.18%   |
| Gateway             | 3        | 0.14%   |
| ECS                 | 3        | 0.14%   |
| Alienware           | 3        | 0.14%   |
| YANYU               | 2        | 0.09%   |
| Shuttle             | 2        | 0.09%   |
| Proline             | 2        | 0.09%   |
| OEM                 | 2        | 0.09%   |
| LattePanda          | 2        | 0.09%   |
| Huanan              | 2        | 0.09%   |
| eMachines           | 2        | 0.09%   |
| American Megatrends | 2        | 0.09%   |
| AAEON               | 2        | 0.09%   |
| ZOTAC               | 1        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 66       | 3.02%   |
| Unknown                          | 30       | 1.37%   |
| ASUS PRIME A320M-K               | 14       | 0.64%   |
| MSI MS-7C37                      | 13       | 0.6%    |
| MSI MS-7B86                      | 12       | 0.55%   |
| Dell OptiPlex 7010               | 12       | 0.55%   |
| MSI MS-7C56                      | 10       | 0.46%   |
| HP Compaq Elite 8300 SFF         | 10       | 0.46%   |
| ASUS TUF Gaming X570-PLUS        | 8        | 0.37%   |
| Supermicro H8DM8-2               | 7        | 0.32%   |
| HP Compaq 8200 Elite SFF PC      | 7        | 0.32%   |
| Gigabyte B450M DS3H              | 7        | 0.32%   |
| ASUS TUF Gaming B550-PLUS        | 7        | 0.32%   |
| ASUS P5KPL-SE                    | 7        | 0.32%   |
| ASRock Q1900M                    | 7        | 0.32%   |
| MSI MS-7C52                      | 6        | 0.27%   |
| MSI MS-7758                      | 6        | 0.27%   |
| Dell OptiPlex 390                | 6        | 0.27%   |
| ASUS ROG STRIX B550-F GAMING     | 6        | 0.27%   |
| ASUS P5KPL-AM SE                 | 6        | 0.27%   |
| ASRock N68C-S UCC                | 6        | 0.27%   |
| MSI MS-7C02                      | 5        | 0.23%   |
| MSI MS-7817                      | 5        | 0.23%   |
| HP Compaq 6000 Pro MT PC         | 5        | 0.23%   |
| Gigabyte X570 AORUS ELITE        | 5        | 0.23%   |
| Gigabyte X470 AORUS ULTRA GAMING | 5        | 0.23%   |
| Dell OptiPlex 990                | 5        | 0.23%   |
| Dell OptiPlex 780                | 5        | 0.23%   |
| Dell OptiPlex 760                | 5        | 0.23%   |
| Dell OptiPlex 3020               | 5        | 0.23%   |
| Dell OptiPlex 3010               | 5        | 0.23%   |
| ASUS ROG STRIX B450-F GAMING     | 5        | 0.23%   |
| ASUS P6T DELUXE V2               | 5        | 0.23%   |
| ASRock G31M-GS                   | 5        | 0.23%   |
| ASRock B450M-HDV R4.0            | 5        | 0.23%   |
| Acer Aspire T180                 | 5        | 0.23%   |
| MSI MS-7C91                      | 4        | 0.18%   |
| MSI MS-7C75                      | 4        | 0.18%   |
| MSI MS-7B79                      | 4        | 0.18%   |
| MSI MS-7A38                      | 4        | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 100      | 4.58%   |
| HP Compaq           | 79       | 3.62%   |
| ASUS All            | 66       | 3.02%   |
| Dell OptiPlex       | 64       | 2.93%   |
| Acer Aspire         | 50       | 2.29%   |
| ASUS TUF            | 44       | 2.01%   |
| ASUS ROG            | 43       | 1.97%   |
| Lenovo ThinkCentre  | 36       | 1.65%   |
| Unknown             | 30       | 1.37%   |
| Acer Veriton        | 24       | 1.1%    |
| Fujitsu ESPRIMO     | 20       | 0.92%   |
| Dell Precision      | 18       | 0.82%   |
| ASUS P8H61-M        | 18       | 0.82%   |
| Packard Bell IMEDIA | 17       | 0.78%   |
| HP Pavilion         | 15       | 0.69%   |
| Gigabyte X570       | 15       | 0.69%   |
| HP ProDesk          | 14       | 0.64%   |
| HP EliteDesk        | 14       | 0.64%   |
| MSI MS-7C37         | 13       | 0.6%    |
| MSI MS-7B86         | 12       | 0.55%   |
| Gigabyte B450       | 12       | 0.55%   |
| ASUS P5KPL-AM       | 12       | 0.55%   |
| MSI MS-7C56         | 10       | 0.46%   |
| Lenovo IdeaCentre   | 10       | 0.46%   |
| ASUS P5Q            | 10       | 0.46%   |
| ASUS P5K            | 10       | 0.46%   |
| ASUS M5A97          | 10       | 0.46%   |
| Gigabyte B450M      | 9        | 0.41%   |
| ASUS P6T            | 9        | 0.41%   |
| ASUS M5A78L-M       | 9        | 0.41%   |
| Lenovo ThinkStation | 8        | 0.37%   |
| Gigabyte Z390       | 8        | 0.37%   |
| ASUS P8P67          | 8        | 0.37%   |
| ASRock 970          | 8        | 0.37%   |
| Supermicro H8DM8-2  | 7        | 0.32%   |
| MSI Compaq          | 7        | 0.32%   |
| Lenovo H50-50       | 7        | 0.32%   |
| ASUS SABERTOOTH     | 7        | 0.32%   |
| ASUS P8Z77-V        | 7        | 0.32%   |
| ASUS P7H55-M        | 7        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 191      | 8.75%   |
| 2009    | 185      | 8.47%   |
| 2012    | 178      | 8.15%   |
| 2013    | 173      | 7.92%   |
| 2008    | 165      | 7.55%   |
| 2011    | 155      | 7.1%    |
| 2019    | 145      | 6.64%   |
| 2014    | 135      | 6.18%   |
| 2010    | 132      | 6.04%   |
| 2020    | 120      | 5.49%   |
| 2007    | 120      | 5.49%   |
| 2017    | 109      | 4.99%   |
| 2015    | 98       | 4.49%   |
| 2016    | 84       | 3.85%   |
| 2006    | 69       | 3.16%   |
| 2021    | 61       | 2.79%   |
| 2005    | 38       | 1.74%   |
| 2004    | 11       | 0.5%    |
| 2022    | 6        | 0.27%   |
| 2003    | 4        | 0.18%   |
| 2001    | 2        | 0.09%   |
| Unknown | 2        | 0.09%   |
| 2002    | 1        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2184     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2137     | 97.67%  |
| Enabled  | 51       | 2.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2184     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 474      | 21.36%  |
| 3.01-4.0        | 465      | 20.96%  |
| 16.01-24.0      | 457      | 20.59%  |
| 4.01-8.0        | 325      | 14.65%  |
| 32.01-64.0      | 212      | 9.55%   |
| 1.01-2.0        | 132      | 5.95%   |
| 64.01-256.0     | 55       | 2.48%   |
| 2.01-3.0        | 37       | 1.67%   |
| 24.01-32.0      | 36       | 1.62%   |
| 0.51-1.0        | 22       | 0.99%   |
| More than 256.0 | 2        | 0.09%   |
| 0.01-0.5        | 2        | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 1024     | 42.45%  |
| 2.01-3.0   | 528      | 21.89%  |
| 0.51-1.0   | 253      | 10.49%  |
| 3.01-4.0   | 250      | 10.36%  |
| 4.01-8.0   | 243      | 10.07%  |
| 8.01-16.0  | 66       | 2.74%   |
| 0.01-0.5   | 32       | 1.33%   |
| 16.01-24.0 | 10       | 0.41%   |
| 24.01-32.0 | 4        | 0.17%   |
| 32.01-64.0 | 1        | 0.04%   |
| Unknown    | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 857      | 37.62%  |
| 2       | 709      | 31.12%  |
| 3       | 357      | 15.67%  |
| 4       | 176      | 7.73%   |
| 5       | 85       | 3.73%   |
| 6       | 34       | 1.49%   |
| 0       | 27       | 1.19%   |
| 7       | 13       | 0.57%   |
| 8       | 9        | 0.4%    |
| 10      | 4        | 0.18%   |
| 9       | 3        | 0.13%   |
| 12      | 2        | 0.09%   |
| 13      | 1        | 0.04%   |
| Unknown | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1363     | 61.65%  |
| No        | 848      | 38.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2169     | 99.31%  |
| No        | 15       | 0.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1292     | 58.54%  |
| Yes       | 915      | 41.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1680     | 75.57%  |
| Yes       | 543      | 24.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Italy   | 2184     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milan                 | 256      | 10.45%  |
| Rome                  | 250      | 10.21%  |
| Turin                 | 79       | 3.23%   |
| Bologna               | 69       | 2.82%   |
| Naples                | 52       | 2.12%   |
| Florence              | 46       | 1.88%   |
| Genoa                 | 43       | 1.76%   |
| Palermo               | 29       | 1.18%   |
| Padova                | 28       | 1.14%   |
| Rho                   | 24       | 0.98%   |
| Verona                | 20       | 0.82%   |
| Venice                | 20       | 0.82%   |
| Catania               | 17       | 0.69%   |
| Brescia               | 17       | 0.69%   |
| Trieste               | 16       | 0.65%   |
| Reggio Emilia         | 16       | 0.65%   |
| Capriate San Gervasio | 16       | 0.65%   |
| Pescara               | 15       | 0.61%   |
| Cagliari              | 14       | 0.57%   |
| Bari                  | 13       | 0.53%   |
| Pisa                  | 12       | 0.49%   |
| Parma                 | 12       | 0.49%   |
| Trento                | 11       | 0.45%   |
| Sesto San Giovanni    | 11       | 0.45%   |
| Bergamo               | 11       | 0.45%   |
| Taranto               | 10       | 0.41%   |
| Monza                 | 10       | 0.41%   |
| Modena                | 10       | 0.41%   |
| Perugia               | 9        | 0.37%   |
| Lucca                 | 9        | 0.37%   |
| Treviso               | 8        | 0.33%   |
| Como                  | 8        | 0.33%   |
| Casalecchio di Reno   | 8        | 0.33%   |
| Vicenza               | 7        | 0.29%   |
| Mestre                | 7        | 0.29%   |
| Capannori             | 7        | 0.29%   |
| Bolzano               | 7        | 0.29%   |
| Udine                 | 6        | 0.24%   |
| Sesto Fiorentino      | 6        | 0.24%   |
| Rozzano               | 6        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 811      | 1338   | 20.82%  |
| WDC                       | 751      | 1223   | 19.28%  |
| Samsung Electronics       | 567      | 857    | 14.56%  |
| Kingston                  | 282      | 399    | 7.24%   |
| Crucial                   | 234      | 310    | 6.01%   |
| Toshiba                   | 186      | 294    | 4.78%   |
| Maxtor                    | 165      | 224    | 4.24%   |
| Hitachi                   | 143      | 194    | 3.67%   |
| SanDisk                   | 128      | 185    | 3.29%   |
| Unknown                   | 51       | 71     | 1.31%   |
| Phison                    | 50       | 70     | 1.28%   |
| China                     | 29       | 32     | 0.74%   |
| Corsair                   | 28       | 43     | 0.72%   |
| SPCC                      | 27       | 32     | 0.69%   |
| Intel                     | 26       | 33     | 0.67%   |
| HGST                      | 25       | 39     | 0.64%   |
| Micron/Crucial Technology | 22       | 27     | 0.56%   |
| Intenso                   | 22       | 30     | 0.56%   |
| A-DATA Technology         | 21       | 30     | 0.54%   |
| Transcend                 | 17       | 23     | 0.44%   |
| OCZ                       | 17       | 19     | 0.44%   |
| Micron Technology         | 17       | 18     | 0.44%   |
| PNY                       | 14       | 19     | 0.36%   |
| Patriot                   | 13       | 16     | 0.33%   |
| KingDian                  | 13       | 14     | 0.33%   |
| SK hynix                  | 10       | 11     | 0.26%   |
| Drevo                     | 10       | 11     | 0.26%   |
| Silicon Motion            | 9        | 12     | 0.23%   |
| Phison Electronics        | 9        | 11     | 0.23%   |
| GOODRAM                   | 9        | 13     | 0.23%   |
| Fujitsu                   | 9        | 10     | 0.23%   |
| TCSUNBOW                  | 8        | 9      | 0.21%   |
| XPG                       | 7        | 7      | 0.18%   |
| Team                      | 7        | 11     | 0.18%   |
| JMicron Technology        | 7        | 7      | 0.18%   |
| LITEONIT                  | 6        | 6      | 0.15%   |
| Lexar                     | 6        | 6      | 0.15%   |
| Dogfish                   | 6        | 9      | 0.15%   |
| LaCie                     | 5        | 7      | 0.13%   |
| ASMT                      | 5        | 5      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 91       | 2.02%   |
| Kingston SA400S37240G 240GB SSD  | 75       | 1.67%   |
| Samsung SSD 860 EVO 500GB        | 66       | 1.47%   |
| Samsung SSD 850 EVO 250GB        | 60       | 1.33%   |
| Seagate ST1000DM010-2EP102 1TB   | 58       | 1.29%   |
| Crucial CT500MX500SSD1 500GB     | 53       | 1.18%   |
| Toshiba DT01ACA100 1TB           | 51       | 1.13%   |
| Kingston SA400S37480G 480GB SSD  | 47       | 1.04%   |
| Seagate ST2000DM008-2FR102 2TB   | 43       | 0.95%   |
| Seagate ST3500418AS 500GB        | 42       | 0.93%   |
| Samsung SSD 850 EVO 500GB        | 41       | 0.91%   |
| Samsung SSD 860 EVO 250GB        | 40       | 0.89%   |
| Seagate ST31000528AS 1TB         | 35       | 0.78%   |
| WDC WD10EZEX-08WN4A0 1TB         | 33       | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB   | 33       | 0.73%   |
| Crucial CT240BX500SSD1 240GB     | 32       | 0.71%   |
| Seagate ST2000DM001-1ER164 2TB   | 29       | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB   | 28       | 0.62%   |
| Kingston SV300S37A120G 120GB SSD | 28       | 0.62%   |
| Kingston SA400S37120G 120GB SSD  | 28       | 0.62%   |
| Crucial CT1000MX500SSD1 1TB      | 27       | 0.6%    |
| Samsung NVMe SSD Drive 500GB     | 26       | 0.58%   |
| Seagate ST1000DM003-1SB10C 1TB   | 23       | 0.51%   |
| Samsung SSD 840 EVO 250GB        | 23       | 0.51%   |
| Toshiba DT01ACA050 500GB         | 22       | 0.49%   |
| Seagate ST3500413AS 500GB        | 22       | 0.49%   |
| Seagate ST2000DM006-2DM164 2TB   | 20       | 0.44%   |
| Seagate M3 Portable 4TB          | 20       | 0.44%   |
| Maxtor STM3250310AS 250GB        | 20       | 0.44%   |
| Crucial CT480BX500SSD1 480GB     | 20       | 0.44%   |
| Seagate ST1000DM003-9YN162 1TB   | 19       | 0.42%   |
| Phison Sabrent 512GB             | 19       | 0.42%   |
| SanDisk SSD PLUS 240GB           | 18       | 0.4%    |
| WDC WD30EFRX-68EUZN0 3TB         | 17       | 0.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 17       | 0.38%   |
| Toshiba DT01ACA200 2TB           | 17       | 0.38%   |
| Samsung SSD 850 PRO 256GB        | 17       | 0.38%   |
| Seagate Expansion 1TB            | 16       | 0.36%   |
| Samsung SSD 860 EVO 1TB          | 16       | 0.36%   |
| Samsung NVMe SSD Drive 1TB       | 16       | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 795      | 1303   | 37.34%  |
| WDC                 | 692      | 1109   | 32.5%   |
| Maxtor              | 165      | 224    | 7.75%   |
| Toshiba             | 163      | 260    | 7.66%   |
| Hitachi             | 143      | 194    | 6.72%   |
| Samsung Electronics | 91       | 114    | 4.27%   |
| HGST                | 25       | 39     | 1.17%   |
| Unknown             | 21       | 28     | 0.99%   |
| Fujitsu             | 9        | 10     | 0.42%   |
| ASMT                | 3        | 3      | 0.14%   |
| WD MediaMax         | 2        | 2      | 0.09%   |
| Inateck             | 2        | 2      | 0.09%   |
| IBM/Hitachi         | 2        | 2      | 0.09%   |
| HGST HTS            | 2        | 2      | 0.09%   |
| Apple               | 2        | 2      | 0.09%   |
| USB3.0              | 1        | 1      | 0.05%   |
| USB 3.0             | 1        | 2      | 0.05%   |
| USB                 | 1        | 1      | 0.05%   |
| Promise             | 1        | 1      | 0.05%   |
| PI-041              | 1        | 1      | 0.05%   |
| MARVELL             | 1        | 2      | 0.05%   |
| Intenso             | 1        | 3      | 0.05%   |
| Initio              | 1        | 1      | 0.05%   |
| Hewlett-Packard     | 1        | 1      | 0.05%   |
| FC-1307             | 1        | 2      | 0.05%   |
| Config              | 1        | 1      | 0.05%   |
| ASMT109x            | 1        | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 366      | 527    | 27.25%  |
| Kingston            | 266      | 375    | 19.81%  |
| Crucial             | 209      | 278    | 15.56%  |
| SanDisk             | 108      | 157    | 8.04%   |
| WDC                 | 56       | 80     | 4.17%   |
| China               | 29       | 32     | 2.16%   |
| Toshiba             | 23       | 29     | 1.71%   |
| SPCC                | 23       | 28     | 1.71%   |
| Corsair             | 22       | 36     | 1.64%   |
| Intenso             | 19       | 24     | 1.41%   |
| A-DATA Technology   | 17       | 26     | 1.27%   |
| OCZ                 | 16       | 18     | 1.19%   |
| Transcend           | 15       | 21     | 1.12%   |
| PNY                 | 14       | 19     | 1.04%   |
| Patriot             | 13       | 16     | 0.97%   |
| KingDian            | 13       | 14     | 0.97%   |
| Intel               | 12       | 17     | 0.89%   |
| GOODRAM             | 9        | 13     | 0.67%   |
| TCSUNBOW            | 8        | 9      | 0.6%    |
| Micron Technology   | 8        | 9      | 0.6%    |
| Team                | 6        | 10     | 0.45%   |
| LITEONIT            | 6        | 6      | 0.45%   |
| Drevo               | 6        | 6      | 0.45%   |
| Dogfish             | 6        | 9      | 0.45%   |
| Unknown             | 5        | 6      | 0.37%   |
| Verbatim            | 4        | 4      | 0.3%    |
| Lexar               | 4        | 4      | 0.3%    |
| BAITITON            | 4        | 4      | 0.3%    |
| Plextor             | 3        | 7      | 0.22%   |
| LITEON              | 3        | 4      | 0.22%   |
| KIOXIA-EXCERIA      | 3        | 3      | 0.22%   |
| Gigabyte Technology | 3        | 8      | 0.22%   |
| Apacer              | 3        | 3      | 0.22%   |
| USB3.0              | 2        | 2      | 0.15%   |
| TO Exter            | 2        | 2      | 0.15%   |
| SK hynix            | 2        | 2      | 0.15%   |
| S3+                 | 2        | 4      | 0.15%   |
| Netac               | 2        | 2      | 0.15%   |
| KingSpec            | 2        | 3      | 0.15%   |
| JMicron Technology  | 2        | 2      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1635     | 3311   | 50.7%   |
| SSD     | 1123     | 1849   | 34.82%  |
| NVMe    | 380      | 547    | 11.78%  |
| Unknown | 68       | 93     | 2.11%   |
| MMC     | 19       | 24     | 0.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2045     | 5079   | 79.48%  |
| NVMe | 375      | 538    | 14.57%  |
| SAS  | 134      | 183    | 5.21%   |
| MMC  | 19       | 24     | 0.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1691     | 3151   | 58.37%  |
| 0.51-1.0   | 743      | 1186   | 25.65%  |
| 1.01-2.0   | 253      | 439    | 8.73%   |
| 2.01-3.0   | 84       | 144    | 2.9%    |
| 3.01-4.0   | 77       | 136    | 2.66%   |
| 4.01-10.0  | 43       | 93     | 1.48%   |
| 10.01-20.0 | 6        | 11     | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 565      | 24.09%  |
| 251-500        | 402      | 17.14%  |
| 501-1000       | 308      | 13.13%  |
| 1001-2000      | 245      | 10.45%  |
| 1-20           | 192      | 8.19%   |
| 51-100         | 177      | 7.55%   |
| More than 3000 | 176      | 7.51%   |
| 2001-3000      | 118      | 5.03%   |
| Unknown        | 84       | 3.58%   |
| 21-50          | 78       | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 900      | 37.36%  |
| 21-50          | 330      | 13.7%   |
| 101-250        | 242      | 10.05%  |
| 51-100         | 224      | 9.3%    |
| 501-1000       | 193      | 8.01%   |
| 251-500        | 191      | 7.93%   |
| 1001-2000      | 119      | 4.94%   |
| Unknown        | 84       | 3.49%   |
| More than 3000 | 78       | 3.24%   |
| 2001-3000      | 48       | 1.99%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 14       | 16     | 4.95%   |
| Seagate ST3500418AS 500GB             | 8        | 12     | 2.83%   |
| Maxtor STM3250310AS 250GB             | 5        | 5      | 1.77%   |
| Unknown MM0500EANCR 500GB             | 4        | 9      | 1.41%   |
| Seagate ST31500341AS 1TB              | 4        | 4      | 1.41%   |
| Seagate ST31000528AS 1TB              | 4        | 7      | 1.41%   |
| Maxtor STM3320820AS 320GB             | 4        | 4      | 1.41%   |
| WDC WD40EFRX-68N32N0 4TB              | 3        | 4      | 1.06%   |
| WDC WD20EFRX-68EUZN0 2TB              | 3        | 4      | 1.06%   |
| Seagate ST3500413AS 500GB             | 3        | 5      | 1.06%   |
| Seagate ST3500320AS 500GB             | 3        | 3      | 1.06%   |
| Samsung Electronics HD103UJ 1TB       | 3        | 3      | 1.06%   |
| Maxtor 6Y080L0 81GB                   | 3        | 3      | 1.06%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 2        | 2      | 0.71%   |
| WDC WD40PURZ-85TTDY0 4TB              | 2        | 2      | 0.71%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 2      | 0.71%   |
| WDC WD10EADS-00M2B0 1TB               | 2        | 2      | 0.71%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2        | 2      | 0.71%   |
| Toshiba DT01ACA100 1TB                | 2        | 2      | 0.71%   |
| Toshiba DT01ACA050 500GB              | 2        | 2      | 0.71%   |
| Seagate ST9500530NS 500GB             | 2        | 3      | 0.71%   |
| Seagate ST9500325AS 500GB             | 2        | 2      | 0.71%   |
| Seagate ST3500620AS 500GB             | 2        | 2      | 0.71%   |
| Seagate ST3320620AS 320GB             | 2        | 3      | 0.71%   |
| Seagate ST3250820AS 250GB             | 2        | 3      | 0.71%   |
| Seagate ST3250318AS 250GB             | 2        | 2      | 0.71%   |
| Seagate ST3250310AS 250GB             | 2        | 2      | 0.71%   |
| Seagate ST2000DM006-2DM164 2TB        | 2        | 2      | 0.71%   |
| Seagate ST2000DM001-1ER164 2TB        | 2        | 6      | 0.71%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 2      | 0.71%   |
| Seagate ST1000DM003-1ER162 1TB        | 2        | 2      | 0.71%   |
| Seagate ST1000DM003-1CH162 1TB        | 2        | 2      | 0.71%   |
| SanDisk SSD PLUS 480GB                | 2        | 2      | 0.71%   |
| Samsung Electronics SSD 860 EVO 500GB | 2        | 3      | 0.71%   |
| OCZ AGILITY3 120GB SSD                | 2        | 2      | 0.71%   |
| Maxtor STM3500320AS 500GB             | 2        | 2      | 0.71%   |
| Maxtor STM3160815AS 160GB             | 2        | 2      | 0.71%   |
| Maxtor STM3160215AS 160GB             | 2        | 2      | 0.71%   |
| Kingston SA400S37480G 480GB SSD       | 2        | 2      | 0.71%   |
| Kingston SA400S37240G 240GB SSD       | 2        | 2      | 0.71%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 88       | 124    | 32.47%  |
| WDC                 | 67       | 82     | 24.72%  |
| Maxtor              | 30       | 33     | 11.07%  |
| Hitachi             | 22       | 25     | 8.12%   |
| Samsung Electronics | 19       | 22     | 7.01%   |
| Kingston            | 11       | 11     | 4.06%   |
| Toshiba             | 7        | 7      | 2.58%   |
| Crucial             | 5        | 5      | 1.85%   |
| Unknown             | 4        | 9      | 1.48%   |
| HGST                | 3        | 4      | 1.11%   |
| SanDisk             | 2        | 2      | 0.74%   |
| OCZ                 | 2        | 2      | 0.74%   |
| Intenso             | 2        | 2      | 0.74%   |
| WD MediaMax         | 1        | 1      | 0.37%   |
| TCSUNBOW            | 1        | 1      | 0.37%   |
| Micron Technology   | 1        | 1      | 0.37%   |
| LITEONIT            | 1        | 1      | 0.37%   |
| Fujitsu             | 1        | 1      | 0.37%   |
| Drevo               | 1        | 1      | 0.37%   |
| Corsair             | 1        | 2      | 0.37%   |
| BAITITON            | 1        | 1      | 0.37%   |
| ASMT                | 1        | 1      | 0.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 88       | 124    | 37.13%  |
| WDC                 | 66       | 80     | 27.85%  |
| Maxtor              | 30       | 33     | 12.66%  |
| Hitachi             | 22       | 25     | 9.28%   |
| Samsung Electronics | 14       | 15     | 5.91%   |
| Toshiba             | 7        | 7      | 2.95%   |
| Unknown             | 4        | 9      | 1.69%   |
| HGST                | 3        | 4      | 1.27%   |
| WD MediaMax         | 1        | 1      | 0.42%   |
| Fujitsu             | 1        | 1      | 0.42%   |
| ASMT                | 1        | 1      | 0.42%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 213      | 300    | 86.23%  |
| SSD  | 31       | 35     | 12.55%  |
| NVMe | 3        | 3      | 1.21%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 2        | 3      | 33.33%  |
| Seagate STM3250318AS 250GB      | 1        | 1      | 16.67%  |
| Seagate ST9500420AS 500GB       | 1        | 1      | 16.67%  |
| Hitachi HTS725050A7E630 500GB   | 1        | 1      | 16.67%  |
| Hitachi HTS543216L9A300 160GB   | 1        | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 66.67%  |
| Hitachi | 2        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1386     | 3551   | 57.04%  |
| Works    | 800      | 1928   | 32.92%  |
| Malfunc  | 238      | 338    | 9.79%   |
| Failed   | 6        | 7      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1433     | 48.48%  |
| AMD                              | 571      | 19.32%  |
| Samsung Electronics              | 165      | 5.58%   |
| Nvidia                           | 118      | 3.99%   |
| JMicron Technology               | 116      | 3.92%   |
| Marvell Technology Group         | 106      | 3.59%   |
| ASMedia Technology               | 99       | 3.35%   |
| Phison Electronics               | 69       | 2.33%   |
| Micron/Crucial Technology        | 48       | 1.62%   |
| VIA Technologies                 | 47       | 1.59%   |
| SanDisk                          | 41       | 1.39%   |
| Kingston Technology Company      | 23       | 0.78%   |
| Silicon Motion                   | 15       | 0.51%   |
| Adaptec                          | 15       | 0.51%   |
| Micron Technology                | 11       | 0.37%   |
| ADATA Technology                 | 10       | 0.34%   |
| SK hynix                         | 8        | 0.27%   |
| Silicon Integrated Systems [SiS] | 8        | 0.27%   |
| Silicon Image                    | 8        | 0.27%   |
| Toshiba America Info Systems     | 7        | 0.24%   |
| Broadcom / LSI                   | 7        | 0.24%   |
| LSI Logic / Symbios Logic        | 5        | 0.17%   |
| Realtek Semiconductor            | 4        | 0.14%   |
| Promise Technology               | 3        | 0.1%    |
| Broadcom                         | 3        | 0.1%    |
| ULi Electronics                  | 2        | 0.07%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.07%   |
| KIOXIA                           | 2        | 0.07%   |
| Integrated Technology Express    | 2        | 0.07%   |
| INNOGRIT                         | 2        | 0.07%   |
| HighPoint Technologies           | 2        | 0.07%   |
| Seagate Technology               | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.03%   |
| Initio                           | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 310      | 7.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 145      | 3.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 142      | 3.64%   |
| AMD 400 Series Chipset SATA Controller                                                  | 121      | 3.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 120      | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 109      | 2.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 107      | 2.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 101      | 2.59%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 96       | 2.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 92       | 2.36%   |
| Intel SATA Controller [RAID mode]                                                       | 92       | 2.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 92       | 2.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 80       | 2.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 78       | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 68       | 1.74%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 62       | 1.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 61       | 1.56%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 55       | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 49       | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 49       | 1.25%   |
| AMD 500 Series Chipset SATA Controller                                                  | 49       | 1.25%   |
| Phison E12 NVMe Controller                                                              | 47       | 1.2%    |
| Nvidia MCP61 SATA Controller                                                            | 47       | 1.2%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 44       | 1.13%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 42       | 1.08%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 42       | 1.08%   |
| Nvidia MCP61 IDE                                                                        | 40       | 1.02%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 36       | 0.92%   |
| Samsung NVMe SSD Controller 980                                                         | 33       | 0.85%   |
| JMicron JMB368 IDE controller                                                           | 33       | 0.85%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 32       | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 32       | 0.82%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 31       | 0.79%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 31       | 0.79%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 30       | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 29       | 0.74%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 27       | 0.69%   |
| AMD FCH SATA Controller D                                                               | 26       | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 25       | 0.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 24       | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1514     | 52.1%   |
| IDE  | 820      | 28.22%  |
| NVMe | 381      | 13.11%  |
| RAID | 175      | 6.02%   |
| SCSI | 9        | 0.31%   |
| SAS  | 7        | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 1514     | 69.32%  |
| AMD          | 669      | 30.63%  |
| CentaurHauls | 1        | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 39       | 1.78%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 36       | 1.64%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 33       | 1.51%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 32       | 1.46%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 27       | 1.23%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 25       | 1.14%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 23       | 1.05%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 23       | 1.05%   |
| Intel Pentium 4 CPU 3.00GHz                 | 21       | 0.96%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 21       | 0.96%   |
| AMD FX-8350 Eight-Core Processor            | 20       | 0.91%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 19       | 0.87%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 18       | 0.82%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 18       | 0.82%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 18       | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 16       | 0.73%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 16       | 0.73%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 15       | 0.68%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 15       | 0.68%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 15       | 0.68%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 15       | 0.68%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 14       | 0.64%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 14       | 0.64%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 14       | 0.64%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 14       | 0.64%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 14       | 0.64%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 14       | 0.64%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 14       | 0.64%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 14       | 0.64%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 13       | 0.59%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 13       | 0.59%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 13       | 0.59%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 12       | 0.55%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 12       | 0.55%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 12       | 0.55%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 12       | 0.55%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 12       | 0.55%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 12       | 0.55%   |
| AMD Phenom II X4 955 Processor              | 12       | 0.55%   |
| AMD FX-8320 Eight-Core Processor            | 12       | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 390      | 17.81%  |
| Intel Core i7           | 286      | 13.06%  |
| Intel Core i3           | 152      | 6.94%   |
| AMD Ryzen 5             | 137      | 6.26%   |
| AMD Ryzen 7             | 99       | 4.52%   |
| Intel Core 2 Quad       | 97       | 4.43%   |
| Intel Core 2 Duo        | 96       | 4.38%   |
| Intel Celeron           | 76       | 3.47%   |
| Intel Xeon              | 75       | 3.42%   |
| Intel Pentium Dual-Core | 70       | 3.2%    |
| AMD FX                  | 58       | 2.65%   |
| Intel Pentium 4         | 57       | 2.6%    |
| Intel Pentium           | 57       | 2.6%    |
| AMD Athlon 64 X2        | 46       | 2.1%    |
| AMD Ryzen 9             | 37       | 1.69%   |
| Intel Core 2            | 36       | 1.64%   |
| AMD Ryzen 3             | 31       | 1.42%   |
| Intel Pentium Dual      | 29       | 1.32%   |
| AMD Phenom II X4        | 26       | 1.19%   |
| Intel Atom              | 25       | 1.14%   |
| AMD A8                  | 25       | 1.14%   |
| Intel Pentium D         | 23       | 1.05%   |
| Other                   | 22       | 1%      |
| Intel Core i9           | 20       | 0.91%   |
| AMD Sempron             | 19       | 0.87%   |
| AMD Phenom II X6        | 19       | 0.87%   |
| AMD Athlon II X2        | 18       | 0.82%   |
| AMD A10                 | 15       | 0.68%   |
| AMD Phenom              | 14       | 0.64%   |
| AMD Athlon II X4        | 14       | 0.64%   |
| AMD Athlon 64           | 12       | 0.55%   |
| AMD Six-Core Opteron    | 11       | 0.5%    |
| AMD A6                  | 11       | 0.5%    |
| AMD A4                  | 11       | 0.5%    |
| AMD Athlon II X3        | 10       | 0.46%   |
| AMD Athlon              | 10       | 0.46%   |
| AMD Ryzen Threadripper  | 6        | 0.27%   |
| AMD Athlon X4           | 6        | 0.27%   |
| AMD Ryzen 5 PRO         | 4        | 0.18%   |
| AMD Quad-Core Opteron   | 4        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 901      | 41.16%  |
| 2       | 642      | 29.33%  |
| 6       | 250      | 11.42%  |
| 8       | 166      | 7.58%   |
| 1       | 121      | 5.53%   |
| 12      | 40       | 1.83%   |
| 3       | 30       | 1.37%   |
| 16      | 18       | 0.82%   |
| 10      | 14       | 0.64%   |
| 24      | 4        | 0.18%   |
| 64      | 1        | 0.05%   |
| 5       | 1        | 0.05%   |
| Unknown | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2149     | 98.4%   |
| 2      | 35       | 1.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1205     | 55.1%   |
| 2       | 981      | 44.86%  |
| Unknown | 1        | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2144     | 97.9%   |
| Unknown        | 25       | 1.14%   |
| 32-bit         | 21       | 0.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 436      | 19.27%  |
| 0x306c3    | 176      | 7.78%   |
| 0x206a7    | 135      | 5.97%   |
| 0x1067a    | 134      | 5.92%   |
| 0x306a9    | 112      | 4.95%   |
| 0x08701021 | 79       | 3.49%   |
| 0x506e3    | 77       | 3.4%    |
| 0x906e9    | 55       | 2.43%   |
| 0x6fb      | 55       | 2.43%   |
| 0x906ea    | 46       | 2.03%   |
| 0x0800820d | 37       | 1.64%   |
| 0x6fd      | 34       | 1.5%    |
| 0x010000c8 | 33       | 1.46%   |
| 0x06000852 | 32       | 1.41%   |
| 0x10676    | 27       | 1.19%   |
| 0x106e5    | 26       | 1.15%   |
| 0x6f6      | 25       | 1.11%   |
| 0x906ed    | 24       | 1.06%   |
| 0x06001119 | 24       | 1.06%   |
| 0x08701013 | 23       | 1.02%   |
| 0x08108109 | 23       | 1.02%   |
| 0x106a5    | 21       | 0.93%   |
| 0xa0653    | 20       | 0.88%   |
| 0x10677    | 19       | 0.84%   |
| 0xa0655    | 18       | 0.8%    |
| 0x20655    | 18       | 0.8%    |
| 0x0a201016 | 18       | 0.8%    |
| 0x0a50000c | 16       | 0.71%   |
| 0x08001138 | 16       | 0.71%   |
| 0xf43      | 15       | 0.66%   |
| 0x20652    | 15       | 0.66%   |
| 0x010000dc | 15       | 0.66%   |
| 0x306f2    | 14       | 0.62%   |
| 0x30678    | 14       | 0.62%   |
| 0x03000027 | 14       | 0.62%   |
| 0xf49      | 13       | 0.57%   |
| 0x06003106 | 13       | 0.57%   |
| 0xa0671    | 12       | 0.53%   |
| 0x706a1    | 12       | 0.53%   |
| 0xf41      | 11       | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 219      | 10%     |
| Penryn           | 206      | 9.41%   |
| KabyLake         | 180      | 8.22%   |
| SandyBridge      | 173      | 7.9%    |
| Core             | 143      | 6.53%   |
| IvyBridge        | 136      | 6.21%   |
| K10              | 131      | 5.98%   |
| Zen 2            | 119      | 5.44%   |
| Skylake          | 98       | 4.48%   |
| NetBurst         | 87       | 3.97%   |
| Piledriver       | 75       | 3.43%   |
| Zen+             | 73       | 3.33%   |
| K8 Hammer        | 72       | 3.29%   |
| Zen 3            | 64       | 2.92%   |
| Zen              | 64       | 2.92%   |
| Nehalem          | 62       | 2.83%   |
| Westmere         | 53       | 2.42%   |
| CometLake        | 53       | 2.42%   |
| Silvermont       | 42       | 1.92%   |
| Steamroller      | 17       | 0.78%   |
| K10 Llano        | 17       | 0.78%   |
| Goldmont plus    | 16       | 0.73%   |
| Goldmont         | 14       | 0.64%   |
| Bonnell          | 14       | 0.64%   |
| Excavator        | 12       | 0.55%   |
| Bulldozer        | 9        | 0.41%   |
| Icelake          | 8        | 0.37%   |
| Unknown          | 8        | 0.37%   |
| Jaguar           | 7        | 0.32%   |
| Puma             | 5        | 0.23%   |
| Bobcat           | 5        | 0.23%   |
| Alderlake Hybrid | 5        | 0.23%   |
| K6               | 1        | 0.05%   |
| Broadwell        | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 964      | 42.36%  |
| AMD                                          | 682      | 29.96%  |
| Intel                                        | 602      | 26.45%  |
| VIA Technologies                             | 10       | 0.44%   |
| Matrox Electronics Systems                   | 7        | 0.31%   |
| Silicon Integrated Systems [SiS]             | 5        | 0.22%   |
| XGI Technology (eXtreme Graphics Innovation) | 3        | 0.13%   |
| ASPEED Technology                            | 3        | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 82       | 3.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 80       | 3.42%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 77       | 3.3%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 63       | 2.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 58       | 2.48%   |
| Nvidia GT218 [GeForce 210]                                                               | 56       | 2.4%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 53       | 2.27%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 47       | 2.01%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 32       | 1.37%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 31       | 1.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 30       | 1.28%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 30       | 1.28%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 29       | 1.24%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 29       | 1.24%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 27       | 1.16%   |
| Intel HD Graphics 530                                                                    | 25       | 1.07%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 25       | 1.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 24       | 1.03%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 24       | 1.03%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 23       | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 23       | 0.98%   |
| Intel HD Graphics 630                                                                    | 22       | 0.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 22       | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22       | 0.94%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 21       | 0.9%    |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 21       | 0.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 20       | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 18       | 0.77%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 18       | 0.77%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 18       | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18       | 0.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 17       | 0.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16       | 0.68%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 16       | 0.68%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 15       | 0.64%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 15       | 0.64%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 14       | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 14       | 0.6%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 14       | 0.6%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 14       | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 926      | 42.11%  |
| 1 x AMD              | 614      | 27.92%  |
| 1 x Intel            | 542      | 24.65%  |
| 2 x AMD              | 42       | 1.91%   |
| Intel + Nvidia       | 17       | 0.77%   |
| AMD + Nvidia         | 14       | 0.64%   |
| 1 x VIA              | 10       | 0.45%   |
| Intel + AMD          | 7        | 0.32%   |
| 1 x SiS              | 5        | 0.23%   |
| 2 x Nvidia           | 4        | 0.18%   |
| 1 x XGI              | 3        | 0.14%   |
| Nvidia + Matrox      | 3        | 0.14%   |
| 1 x Matrox           | 3        | 0.14%   |
| 1 x ASPEED           | 3        | 0.14%   |
| Other                | 2        | 0.09%   |
| 3 x AMD              | 1        | 0.05%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.05%   |
| Intel + 2 x AMD      | 1        | 0.05%   |
| AMD + Matrox         | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1657     | 74.24%  |
| Proprietary | 501      | 22.45%  |
| Unknown     | 74       | 3.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 812      | 35.9%   |
| 1.01-2.0   | 361      | 15.96%  |
| 0.01-0.5   | 342      | 15.12%  |
| 0.51-1.0   | 316      | 13.97%  |
| 3.01-4.0   | 164      | 7.25%   |
| 7.01-8.0   | 125      | 5.53%   |
| 5.01-6.0   | 83       | 3.67%   |
| 2.01-3.0   | 33       | 1.46%   |
| 8.01-16.0  | 24       | 1.06%   |
| 4.01-5.0   | 1        | 0.04%   |
| 16.01-24.0 | 1        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 462      | 20.66%  |
| Hewlett-Packard         | 220      | 9.84%   |
| Goldstar                | 220      | 9.84%   |
| Philips                 | 216      | 9.66%   |
| Ancor Communications    | 196      | 8.77%   |
| Acer                    | 160      | 7.16%   |
| BenQ                    | 103      | 4.61%   |
| Dell                    | 102      | 4.56%   |
| AOC                     | 88       | 3.94%   |
| HannStar                | 34       | 1.52%   |
| LG Electronics          | 33       | 1.48%   |
| Lenovo                  | 33       | 1.48%   |
| Unknown                 | 32       | 1.43%   |
| Sony                    | 27       | 1.21%   |
| ASUSTek Computer        | 22       | 0.98%   |
| Fujitsu Siemens         | 15       | 0.67%   |
| Eizo                    | 14       | 0.63%   |
| Packard Bell            | 10       | 0.45%   |
| MSI                     | 10       | 0.45%   |
| NEC Computers           | 9        | 0.4%    |
| Belinea                 | 9        | 0.4%    |
| Sharp                   | 8        | 0.36%   |
| HPN                     | 8        | 0.36%   |
| Vestel Elektronik       | 7        | 0.31%   |
| CVT                     | 7        | 0.31%   |
| ViewSonic               | 6        | 0.27%   |
| OEM                     | 6        | 0.27%   |
| MiTAC                   | 6        | 0.27%   |
| Mi                      | 6        | 0.27%   |
| QBell                   | 5        | 0.22%   |
| Panasonic               | 5        | 0.22%   |
| Microstep               | 5        | 0.22%   |
| Lenovo Group Limited    | 5        | 0.22%   |
| Hyundai ImageQuest      | 5        | 0.22%   |
| HannStar Display        | 5        | 0.22%   |
| Chi Mei Optoelectronics | 5        | 0.22%   |
| RTK                     | 4        | 0.18%   |
| Iiyama                  | 4        | 0.18%   |
| FUS                     | 4        | 0.18%   |
| Compaq Computer         | 4        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 17       | 0.72%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 15       | 0.63%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 14       | 0.59%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 13       | 0.55%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 11       | 0.46%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 11       | 0.46%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 11       | 0.46%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 11       | 0.46%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                    | 11       | 0.46%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch      | 8        | 0.34%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                | 8        | 0.34%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 8        | 0.34%   |
| AOC Q27G2G4 AOC2702 2560x1440 597x336mm 27.0-inch                      | 8        | 0.34%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                        | 8        | 0.34%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                     | 8        | 0.34%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 7        | 0.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 7        | 0.3%    |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 7        | 0.3%    |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch      | 7        | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 7        | 0.3%    |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch             | 7        | 0.3%    |
| Dell 2009W DEL4042 1680x1050 433x270mm 20.1-inch                       | 7        | 0.3%    |
| Ancor Communications VE228 ACI22FA 1920x1080 531x299mm 24.0-inch       | 7        | 0.3%    |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch  | 7        | 0.3%    |
| Acer X223W ACR000D 1680x1050 470x300mm 22.0-inch                       | 7        | 0.3%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch   | 6        | 0.25%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                     | 6        | 0.25%   |
| Philips 190SW PHL086D 1440x900 408x255mm 18.9-inch                     | 6        | 0.25%   |
| Hewlett-Packard 27f HPN354C 1920x1080 598x336mm 27.0-inch              | 6        | 0.25%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch              | 6        | 0.25%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 476x268mm 21.5-inch             | 6        | 0.25%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 6        | 0.25%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 6        | 0.25%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 6        | 0.25%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                       | 6        | 0.25%   |
| Ancor Communications VW222 ACI22A2 1680x1050 473x296mm 22.0-inch       | 6        | 0.25%   |
| Ancor Communications ASUS VW193S ACI19D4 1440x900 408x255mm 18.9-inch  | 6        | 0.25%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 5        | 0.21%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 5        | 0.21%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch   | 5        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1041     | 47.3%   |
| 1280x1024 (SXGA)   | 253      | 11.49%  |
| 1680x1050 (WSXGA+) | 144      | 6.54%   |
| 3840x2160 (4K)     | 139      | 6.32%   |
| 1440x900 (WXGA+)   | 136      | 6.18%   |
| 2560x1440 (QHD)    | 94       | 4.27%   |
| 1366x768 (WXGA)    | 56       | 2.54%   |
| Unknown            | 50       | 2.27%   |
| 1360x768           | 47       | 2.14%   |
| 1920x1200 (WUXGA)  | 35       | 1.59%   |
| 1600x900 (HD+)     | 32       | 1.45%   |
| 2560x1080          | 30       | 1.36%   |
| 1024x768 (XGA)     | 28       | 1.27%   |
| 3840x1080          | 21       | 0.95%   |
| 3440x1440          | 15       | 0.68%   |
| 1600x1200          | 12       | 0.55%   |
| 1920x540           | 9        | 0.41%   |
| 1280x720 (HD)      | 8        | 0.36%   |
| 2560x1600          | 4        | 0.18%   |
| 4480x1440          | 3        | 0.14%   |
| 3200x1080          | 3        | 0.14%   |
| 2288x1287          | 3        | 0.14%   |
| 1280x768           | 3        | 0.14%   |
| 8960x2160          | 2        | 0.09%   |
| 5120x1440          | 2        | 0.09%   |
| 3840x1600          | 2        | 0.09%   |
| 2640x1024          | 2        | 0.09%   |
| 2304x1024          | 2        | 0.09%   |
| 1818x1022          | 2        | 0.09%   |
| 6784x2160          | 1        | 0.05%   |
| 5760x2160          | 1        | 0.05%   |
| 5760x1080          | 1        | 0.05%   |
| 5520x2160          | 1        | 0.05%   |
| 4480x1080          | 1        | 0.05%   |
| 4093x4093          | 1        | 0.05%   |
| 3968x1152          | 1        | 0.05%   |
| 3840x1920          | 1        | 0.05%   |
| 3840x1200          | 1        | 0.05%   |
| 3520x1080          | 1        | 0.05%   |
| 3360x1080          | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 288      | 12.86%  |
| 24      | 287      | 12.81%  |
| 27      | 284      | 12.68%  |
| Unknown | 278      | 12.41%  |
| 19      | 215      | 9.6%    |
| 23      | 212      | 9.46%   |
| 17      | 120      | 5.36%   |
| 18      | 106      | 4.73%   |
| 22      | 80       | 3.57%   |
| 20      | 75       | 3.35%   |
| 31      | 47       | 2.1%    |
| 34      | 45       | 2.01%   |
| 15      | 39       | 1.74%   |
| 84      | 20       | 0.89%   |
| 54      | 18       | 0.8%    |
| 72      | 16       | 0.71%   |
| 25      | 12       | 0.54%   |
| 40      | 11       | 0.49%   |
| 32      | 10       | 0.45%   |
| 42      | 7        | 0.31%   |
| 28      | 6        | 0.27%   |
| 52      | 5        | 0.22%   |
| 48      | 5        | 0.22%   |
| 47      | 5        | 0.22%   |
| 37      | 5        | 0.22%   |
| 39      | 4        | 0.18%   |
| 33      | 4        | 0.18%   |
| 142     | 3        | 0.13%   |
| 60      | 3        | 0.13%   |
| 50      | 3        | 0.13%   |
| 46      | 3        | 0.13%   |
| 29      | 3        | 0.13%   |
| 26      | 3        | 0.13%   |
| 14      | 3        | 0.13%   |
| 43      | 2        | 0.09%   |
| 16      | 2        | 0.09%   |
| 12      | 2        | 0.09%   |
| 75      | 1        | 0.04%   |
| 74      | 1        | 0.04%   |
| 65      | 1        | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 723      | 33.07%  |
| 401-500        | 632      | 28.91%  |
| Unknown        | 278      | 12.72%  |
| 301-350        | 154      | 7.04%   |
| 351-400        | 136      | 6.22%   |
| 601-700        | 83       | 3.8%    |
| 701-800        | 59       | 2.7%    |
| 1001-1500      | 46       | 2.1%    |
| 1501-2000      | 38       | 1.74%   |
| 801-900        | 21       | 0.96%   |
| 901-1000       | 8        | 0.37%   |
| 201-300        | 4        | 0.18%   |
| More than 2000 | 3        | 0.14%   |
| 101-200        | 1        | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1222     | 57.34%  |
| 16/10   | 309      | 14.5%   |
| Unknown | 239      | 11.22%  |
| 5/4     | 238      | 11.17%  |
| 4/3     | 53       | 2.49%   |
| 21/9    | 44       | 2.06%   |
| 6/5     | 9        | 0.42%   |
| 3/2     | 9        | 0.42%   |
| 32/9    | 4        | 0.19%   |
| 1.00    | 3        | 0.14%   |
| 2.65    | 1        | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 690      | 31.38%  |
| 151-200        | 406      | 18.46%  |
| 301-350        | 287      | 13.05%  |
| Unknown        | 278      | 12.64%  |
| 141-150        | 175      | 7.96%   |
| 351-500        | 105      | 4.77%   |
| 251-300        | 90       | 4.09%   |
| More than 1000 | 76       | 3.46%   |
| 501-1000       | 44       | 2%      |
| 101-110        | 37       | 1.68%   |
| 131-140        | 4        | 0.18%   |
| 71-80          | 2        | 0.09%   |
| 91-100         | 2        | 0.09%   |
| 81-90          | 1        | 0.05%   |
| 1-40           | 1        | 0.05%   |
| 111-120        | 1        | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1344     | 62.6%   |
| 101-120       | 373      | 17.37%  |
| Unknown       | 278      | 12.95%  |
| 1-50          | 73       | 3.4%    |
| 121-160       | 48       | 2.24%   |
| 161-240       | 30       | 1.4%    |
| More than 240 | 1        | 0.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1864     | 84.15%  |
| 2     | 242      | 10.93%  |
| 0     | 85       | 3.84%   |
| 3     | 24       | 1.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1307     | 42.37%  |
| Intel                            | 765      | 24.8%   |
| Qualcomm Atheros                 | 215      | 6.97%   |
| Broadcom                         | 96       | 3.11%   |
| Nvidia                           | 95       | 3.08%   |
| Ralink Technology                | 76       | 2.46%   |
| TP-Link                          | 67       | 2.17%   |
| Marvell Technology Group         | 58       | 1.88%   |
| Ralink                           | 37       | 1.2%    |
| Qualcomm Atheros Communications  | 35       | 1.13%   |
| D-Link System                    | 31       | 1%      |
| Broadcom Limited                 | 31       | 1%      |
| VIA Technologies                 | 27       | 0.88%   |
| Huawei Technologies              | 24       | 0.78%   |
| D-Link                           | 23       | 0.75%   |
| Sitecom Europe                   | 20       | 0.65%   |
| NetGear                          | 17       | 0.55%   |
| Samsung Electronics              | 15       | 0.49%   |
| ASUSTek Computer                 | 15       | 0.49%   |
| Xiaomi                           | 14       | 0.45%   |
| Microsoft                        | 10       | 0.32%   |
| MediaTek                         | 9        | 0.29%   |
| Gemtek                           | 8        | 0.26%   |
| Belkin Components                | 7        | 0.23%   |
| Aquantia                         | 7        | 0.23%   |
| Silicon Integrated Systems [SiS] | 6        | 0.19%   |
| Linksys                          | 5        | 0.16%   |
| AVM                              | 5        | 0.16%   |
| ASIX Electronics                 | 5        | 0.16%   |
| 3Com                             | 5        | 0.16%   |
| DisplayLink                      | 4        | 0.13%   |
| OPPO Electronics                 | 3        | 0.1%    |
| Motorola                         | 3        | 0.1%    |
| Microchip Technology             | 3        | 0.1%    |
| ZTE WCDMA Technologies MSM       | 2        | 0.06%   |
| Smart Link                       | 2        | 0.06%   |
| Qualcomm                         | 2        | 0.06%   |
| OnePlus Technology (Shenzhen)    | 2        | 0.06%   |
| Google                           | 2        | 0.06%   |
| Exar                             | 2        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1043     | 30.44%  |
| Intel Ethernet Connection (2) I219-V                              | 94       | 2.74%   |
| Intel I211 Gigabit Network Connection                             | 93       | 2.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 83       | 2.42%   |
| Intel Wi-Fi 6 AX200                                               | 74       | 2.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 56       | 1.63%   |
| Intel 82579V Gigabit Network Connection                           | 55       | 1.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 44       | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 41       | 1.2%    |
| Nvidia MCP61 Ethernet                                             | 38       | 1.11%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 38       | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                   | 34       | 0.99%   |
| Intel Ethernet Controller I225-V                                  | 34       | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 33       | 0.96%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 32       | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 32       | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 30       | 0.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 29       | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 29       | 0.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 28       | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 27       | 0.79%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 24       | 0.7%    |
| Realtek 802.11ac NIC                                              | 24       | 0.7%    |
| Intel Wireless 7265                                               | 24       | 0.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 21       | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21       | 0.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 21       | 0.61%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 21       | 0.61%   |
| Ralink MT7601U Wireless Adapter                                   | 20       | 0.58%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 19       | 0.55%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 17       | 0.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 17       | 0.5%    |
| Nvidia MCP77 Ethernet                                             | 16       | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 16       | 0.47%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 16       | 0.47%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 15       | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 15       | 0.44%   |
| Intel Wireless-AC 9260                                            | 15       | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.41%   |
| Ralink RT5370 Wireless Adapter                                    | 14       | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 262      | 26.76%  |
| Intel                           | 209      | 21.35%  |
| Qualcomm Atheros                | 111      | 11.34%  |
| Ralink Technology               | 76       | 7.76%   |
| TP-Link                         | 65       | 6.64%   |
| Ralink                          | 37       | 3.78%   |
| Broadcom                        | 37       | 3.78%   |
| Qualcomm Atheros Communications | 35       | 3.58%   |
| D-Link System                   | 23       | 2.35%   |
| D-Link                          | 23       | 2.35%   |
| Sitecom Europe                  | 20       | 2.04%   |
| NetGear                         | 17       | 1.74%   |
| ASUSTek Computer                | 14       | 1.43%   |
| Microsoft                       | 9        | 0.92%   |
| Gemtek                          | 8        | 0.82%   |
| Belkin Components               | 7        | 0.72%   |
| Linksys                         | 5        | 0.51%   |
| Broadcom Limited                | 5        | 0.51%   |
| AVM                             | 5        | 0.51%   |
| MediaTek                        | 2        | 0.2%    |
| Edimax Technology               | 2        | 0.2%    |
| ZyXEL Communications            | 1        | 0.1%    |
| ZyDAS                           | 1        | 0.1%    |
| Wilocity                        | 1        | 0.1%    |
| Wacom                           | 1        | 0.1%    |
| Samsung Electronics             | 1        | 0.1%    |
| Fiberline                       | 1        | 0.1%    |
| AboCom Systems                  | 1        | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 74       | 7.47%   |
| Qualcomm Atheros AR9271 802.11n                                               | 34       | 3.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 33       | 3.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 29       | 2.93%   |
| Realtek 802.11ac NIC                                                          | 24       | 2.42%   |
| Intel Wireless 7265                                                           | 24       | 2.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 21       | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 21       | 2.12%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 21       | 2.12%   |
| Ralink MT7601U Wireless Adapter                                               | 20       | 2.02%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 19       | 1.92%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 17       | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 17       | 1.72%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 16       | 1.61%   |
| Ralink RT2501/RT2573 Wireless Adapter                                         | 15       | 1.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 15       | 1.51%   |
| Intel Wireless-AC 9260                                                        | 15       | 1.51%   |
| Ralink RT5370 Wireless Adapter                                                | 14       | 1.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 13       | 1.31%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 12       | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 11       | 1.11%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 11       | 1.11%   |
| Intel Wireless 7260                                                           | 11       | 1.11%   |
| Intel Wireless 3165                                                           | 11       | 1.11%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 11       | 1.11%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 11       | 1.11%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 10       | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 10       | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 10       | 1.01%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 9        | 0.91%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 9        | 0.91%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 9        | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 9        | 0.91%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]            | 9        | 0.91%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 8        | 0.81%   |
| Realtek RTL8187 Wireless Adapter                                              | 8        | 0.81%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 8        | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 8        | 0.81%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 8        | 0.81%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 8        | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1212     | 51.42%  |
| Intel                             | 645      | 27.37%  |
| Qualcomm Atheros                  | 122      | 5.18%   |
| Nvidia                            | 95       | 4.03%   |
| Broadcom                          | 61       | 2.59%   |
| Marvell Technology Group          | 58       | 2.46%   |
| VIA Technologies                  | 26       | 1.1%    |
| Broadcom Limited                  | 26       | 1.1%    |
| Huawei Technologies               | 22       | 0.93%   |
| Xiaomi                            | 14       | 0.59%   |
| Samsung Electronics               | 14       | 0.59%   |
| D-Link System                     | 8        | 0.34%   |
| MediaTek                          | 7        | 0.3%    |
| Aquantia                          | 7        | 0.3%    |
| Silicon Integrated Systems [SiS]  | 6        | 0.25%   |
| ASIX Electronics                  | 5        | 0.21%   |
| 3Com                              | 5        | 0.21%   |
| DisplayLink                       | 4        | 0.17%   |
| OPPO Electronics                  | 3        | 0.13%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.08%   |
| TP-Link                           | 2        | 0.08%   |
| Qualcomm                          | 2        | 0.08%   |
| Google                            | 2        | 0.08%   |
| ULi Electronics                   | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus | 1        | 0.04%   |
| OnePlus Technology (Shenzhen)     | 1        | 0.04%   |
| Motorola PCS                      | 1        | 0.04%   |
| LG Electronics                    | 1        | 0.04%   |
| JMicron Technology                | 1        | 0.04%   |
| HTC (High Tech Computer)          | 1        | 0.04%   |
| HMD Global                        | 1        | 0.04%   |
| ASUSTek Computer                  | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1043     | 43.33%  |
| Intel Ethernet Connection (2) I219-V                              | 94       | 3.91%   |
| Intel I211 Gigabit Network Connection                             | 93       | 3.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 83       | 3.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 56       | 2.33%   |
| Intel 82579V Gigabit Network Connection                           | 55       | 2.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 44       | 1.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 41       | 1.7%    |
| Nvidia MCP61 Ethernet                                             | 38       | 1.58%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 38       | 1.58%   |
| Intel Ethernet Controller I225-V                                  | 34       | 1.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 32       | 1.33%   |
| Intel Ethernet Connection (7) I219-V                              | 32       | 1.33%   |
| Intel Ethernet Connection I217-LM                                 | 30       | 1.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 29       | 1.2%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 28       | 1.16%   |
| Intel Ethernet Connection I217-V                                  | 27       | 1.12%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 24       | 1%      |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 21       | 0.87%   |
| Nvidia MCP77 Ethernet                                             | 16       | 0.66%   |
| Intel Ethernet Connection (2) I218-V                              | 16       | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 14       | 0.58%   |
| Nvidia MCP73 Ethernet                                             | 14       | 0.58%   |
| Intel 82578DM Gigabit Network Connection                          | 13       | 0.54%   |
| Intel 82578DC Gigabit Network Connection                          | 13       | 0.54%   |
| Intel 82574L Gigabit Network Connection                           | 13       | 0.54%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 13       | 0.54%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 12       | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 11       | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11       | 0.46%   |
| Intel NM10/ICH7 Family LAN Controller                             | 11       | 0.46%   |
| Huawei SNE-LX1                                                    | 11       | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10       | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10       | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10       | 0.42%   |
| Nvidia MCP55 Ethernet                                             | 9        | 0.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 9        | 0.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 9        | 0.37%   |
| Intel I210 Gigabit Network Connection                             | 8        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2168     | 69.76%  |
| WiFi     | 913      | 29.38%  |
| Modem    | 24       | 0.77%   |
| Unknown  | 3        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1682     | 75.22%  |
| WiFi     | 553      | 24.73%  |
| Unknown  | 1        | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1519     | 69.17%  |
| 2     | 594      | 27.05%  |
| 3     | 63       | 2.87%   |
| 0     | 12       | 0.55%   |
| 4     | 4        | 0.18%   |
| 5     | 2        | 0.09%   |
| 12    | 1        | 0.05%   |
| 6     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2099     | 95.54%  |
| Yes  | 98       | 4.46%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 184      | 33.21%  |
| Cambridge Silicon Radio         | 173      | 31.23%  |
| Realtek Semiconductor           | 53       | 9.57%   |
| Broadcom                        | 41       | 7.4%    |
| ASUSTek Computer                | 36       | 6.5%    |
| Qualcomm Atheros Communications | 16       | 2.89%   |
| IMC Networks                    | 11       | 1.99%   |
| Apple                           | 11       | 1.99%   |
| Integrated System Solution      | 7        | 1.26%   |
| TP-Link                         | 3        | 0.54%   |
| Belkin Components               | 3        | 0.54%   |
| Sitecom Europe                  | 2        | 0.36%   |
| Lite-On Technology              | 2        | 0.36%   |
| D-Link System                   | 2        | 0.36%   |
| Unknown                         | 1        | 0.18%   |
| MediaTek                        | 1        | 0.18%   |
| Logitech                        | 1        | 0.18%   |
| HTC (High Tech Computer)        | 1        | 0.18%   |
| Hewlett-Packard                 | 1        | 0.18%   |
| Fujitsu Siemens Computers       | 1        | 0.18%   |
| Fujitsu                         | 1        | 0.18%   |
| Foxconn / Hon Hai               | 1        | 0.18%   |
| Dell                            | 1        | 0.18%   |
| Conwise Technology              | 1        | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 173      | 31.17%  |
| Intel AX200 Bluetooth                                     | 64       | 11.53%  |
| Intel Bluetooth wireless interface                        | 51       | 9.19%   |
| Realtek Bluetooth Radio                                   | 35       | 6.31%   |
| Intel AX201 Bluetooth                                     | 20       | 3.6%    |
| Intel Wireless-AC 3168 Bluetooth                          | 17       | 3.06%   |
| Realtek  Bluetooth 4.2 Adapter                            | 16       | 2.88%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 16       | 2.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 13       | 2.34%   |
| Qualcomm Atheros AR3011 Bluetooth                         | 12       | 2.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 11       | 1.98%   |
| Broadcom BCM2045 Bluetooth                                | 11       | 1.98%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 10       | 1.8%    |
| Intel AX210 Bluetooth                                     | 8        | 1.44%   |
| Apple Bluetooth USB Host Controller                       | 7        | 1.26%   |
| IMC Networks Bluetooth Device                             | 6        | 1.08%   |
| ASUS Bluetooth Radio                                      | 6        | 1.08%   |
| ASUS BCM20702A0                                           | 6        | 1.08%   |
| ASUS Qualcomm Bluetooth 4.1                               | 5        | 0.9%    |
| Integrated System Solution Bluetooth Device               | 4        | 0.72%   |
| IMC Networks Bluetooth Radio                              | 4        | 0.72%   |
| ASUS Bluetooth Adapter                                    | 4        | 0.72%   |
| TP-Link UB500 Adapter                                     | 3        | 0.54%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter     | 3        | 0.54%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter          | 3        | 0.54%   |
| Broadcom BCM2035 Bluetooth dongle                         | 3        | 0.54%   |
| ASUS Bluetooth Device                                     | 3        | 0.54%   |
| Realtek RTL8821A Bluetooth                                | 2        | 0.36%   |
| Qualcomm Atheros  Bluetooth Device                        | 2        | 0.36%   |
| Lite-On Bluetooth Device                                  | 2        | 0.36%   |
| D-Link System DBT-122 Bluetooth                           | 2        | 0.36%   |
| Broadcom Bluetooth 3.0 Device                             | 2        | 0.36%   |
| Belkin Components F8T012 Bluetooth Adapter                | 2        | 0.36%   |
| Apple Bluetooth HCI                                       | 2        | 0.36%   |
| Unknown Bluetooth Device                                  | 1        | 0.18%   |
| Sitecom Europe Sitecom bluetooth2.0 class 2 dongle CN-512 | 1        | 0.18%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1        | 0.18%   |
| Qualcomm Atheros Bluetooth USB Host Controller            | 1        | 0.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 1        | 0.18%   |
| MediaTek Wireless_Device                                  | 1        | 0.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 1399     | 39.51%  |
| Nvidia                               | 866      | 24.46%  |
| AMD                                  | 831      | 23.47%  |
| C-Media Electronics                  | 95       | 2.68%   |
| Creative Labs                        | 40       | 1.13%   |
| VIA Technologies                     | 32       | 0.9%    |
| Logitech                             | 31       | 0.88%   |
| Razer USA                            | 13       | 0.37%   |
| Creative Technology                  | 13       | 0.37%   |
| Texas Instruments                    | 12       | 0.34%   |
| M-Audio                              | 12       | 0.34%   |
| Focusrite-Novation                   | 12       | 0.34%   |
| JMTek                                | 11       | 0.31%   |
| Kingston Technology                  | 9        | 0.25%   |
| Tenx Technology                      | 8        | 0.23%   |
| Silicon Integrated Systems [SiS]     | 8        | 0.23%   |
| Trust                                | 7        | 0.2%    |
| GN Netcom                            | 7        | 0.2%    |
| Ensoniq                              | 7        | 0.2%    |
| Micro Star International             | 6        | 0.17%   |
| Generalplus Technology               | 6        | 0.17%   |
| BEHRINGER International              | 6        | 0.17%   |
| ASUSTek Computer                     | 6        | 0.17%   |
| Thesycon Systemsoftware & Consulting | 5        | 0.14%   |
| Samson Technologies                  | 5        | 0.14%   |
| Microsoft                            | 5        | 0.14%   |
| Dell                                 | 5        | 0.14%   |
| Yamaha                               | 4        | 0.11%   |
| SAVITECH                             | 4        | 0.11%   |
| Plantronics                          | 4        | 0.11%   |
| XMOS                                 | 3        | 0.08%   |
| Sennheiser Communications            | 3        | 0.08%   |
| Corsair                              | 3        | 0.08%   |
| Cambridge Silicon Radio              | 3        | 0.08%   |
| Astro Gaming                         | 3        | 0.08%   |
| ZOOM                                 | 2        | 0.06%   |
| ULi Electronics                      | 2        | 0.06%   |
| Studiologic                          | 2        | 0.06%   |
| SteelSeries ApS                      | 2        | 0.06%   |
| RODE Microphones                     | 2        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 167      | 4.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 153      | 3.84%   |
| AMD Starship/Matisse HD Audio Controller                                          | 153      | 3.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 152      | 3.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 152      | 3.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 114      | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 107      | 2.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 101      | 2.54%   |
| Intel 200 Series PCH HD Audio                                                     | 88       | 2.21%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 84       | 2.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 84       | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 83       | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 83       | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 82       | 2.06%   |
| Nvidia High Definition Audio Controller                                           | 79       | 1.98%   |
| AMD Family 17h/19h HD Audio Controller                                            | 78       | 1.96%   |
| AMD FCH Azalia Controller                                                         | 72       | 1.81%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 71       | 1.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 71       | 1.78%   |
| Intel Cannon Lake PCH cAVS                                                        | 67       | 1.68%   |
| Nvidia GP106 High Definition Audio Controller                                     | 51       | 1.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 51       | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                     | 50       | 1.26%   |
| Nvidia GF119 HDMI Audio Controller                                                | 49       | 1.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 48       | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 47       | 1.18%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 46       | 1.15%   |
| Nvidia MCP61 High Definition Audio                                                | 45       | 1.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 44       | 1.1%    |
| Nvidia TU116 High Definition Audio Controller                                     | 41       | 1.03%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 40       | 1%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 38       | 0.95%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 33       | 0.83%   |
| AMD Navi 10 HDMI Audio                                                            | 30       | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                | 29       | 0.73%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 29       | 0.73%   |
| Nvidia GP108 High Definition Audio Controller                                     | 28       | 0.7%    |
| Nvidia TU106 High Definition Audio Controller                                     | 26       | 0.65%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 26       | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                                     | 25       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 234      | 19.45%  |
| Unknown                      | 220      | 18.29%  |
| Corsair                      | 170      | 14.13%  |
| Crucial                      | 125      | 10.39%  |
| Samsung Electronics          | 102      | 8.48%   |
| SK hynix                     | 82       | 6.82%   |
| G.Skill                      | 69       | 5.74%   |
| Micron Technology            | 55       | 4.57%   |
| Team                         | 22       | 1.83%   |
| Patriot                      | 19       | 1.58%   |
| A-DATA Technology            | 14       | 1.16%   |
| Nanya Technology             | 13       | 1.08%   |
| Ramaxel Technology           | 10       | 0.83%   |
| Unknown (ABCD)               | 9        | 0.75%   |
| Elpida                       | 9        | 0.75%   |
| Unknown                      | 9        | 0.75%   |
| Unifosa                      | 5        | 0.42%   |
| Transcend                    | 5        | 0.42%   |
| ASint Technology             | 4        | 0.33%   |
| GeIL                         | 3        | 0.25%   |
| Unknown (AB)                 | 2        | 0.17%   |
| Qimonda                      | 2        | 0.17%   |
| PLEXHD                       | 2        | 0.17%   |
| Patriot Memory (PDP Systems) | 2        | 0.17%   |
| Hewlett-Packard              | 2        | 0.17%   |
| A Force                      | 2        | 0.17%   |
| V-Color                      | 1        | 0.08%   |
| TwinMOS                      | 1        | 0.08%   |
| Toshiba                      | 1        | 0.08%   |
| Thermaltake                  | 1        | 0.08%   |
| Silicon Power                | 1        | 0.08%   |
| PUSKILL                      | 1        | 0.08%   |
| Netac                        | 1        | 0.08%   |
| KomputerBay                  | 1        | 0.08%   |
| Kingmax                      | 1        | 0.08%   |
| Goodram                      | 1        | 0.08%   |
| Goldkey                      | 1        | 0.08%   |
| CSX                          | 1        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 21       | 1.57%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 17       | 1.27%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 15       | 1.12%   |
| Unknown RAM Module 4096MB DIMM DDR2 266MT/s                  | 13       | 0.97%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 13       | 0.97%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s      | 13       | 0.97%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s        | 11       | 0.82%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 9        | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 9        | 0.67%   |
| Unknown                                                      | 9        | 0.67%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8192MB DIMM DDR4 3733MT/s     | 8        | 0.6%    |
| Unknown RAM Module 2GB DIMM SDRAM                            | 7        | 0.52%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s       | 7        | 0.52%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s        | 7        | 0.52%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s           | 7        | 0.52%   |
| Unknown RAM Module 512MB DIMM SDRAM                          | 6        | 0.45%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                  | 6        | 0.45%   |
| Unknown RAM Module 1024MB DIMM                               | 6        | 0.45%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s      | 6        | 0.45%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 6        | 0.45%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s          | 6        | 0.45%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s          | 6        | 0.45%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s          | 6        | 0.45%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s            | 6        | 0.45%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 6        | 0.45%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s          | 6        | 0.45%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 6        | 0.45%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 5        | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                  | 5        | 0.37%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 5        | 0.37%   |
| Unknown RAM Module 1024MB DIMM SDRAM                         | 5        | 0.37%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s          | 5        | 0.37%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s           | 5        | 0.37%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                   | 5        | 0.37%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s          | 5        | 0.37%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 5        | 0.37%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 5        | 0.37%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s          | 5        | 0.37%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s       | 5        | 0.37%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s    | 5        | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 439      | 40.28%  |
| DDR3    | 367      | 33.67%  |
| DDR2    | 118      | 10.83%  |
| SDRAM   | 73       | 6.7%    |
| Unknown | 57       | 5.23%   |
| DDR     | 20       | 1.83%   |
| LPDDR4  | 10       | 0.92%   |
| LPDDR3  | 4        | 0.37%   |
| DDR5    | 2        | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1008     | 95.55%  |
| SODIMM  | 43       | 4.08%   |
| FB-DIMM | 4        | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 412      | 34.89%  |
| 4096  | 273      | 23.12%  |
| 2048  | 226      | 19.14%  |
| 16384 | 134      | 11.35%  |
| 1024  | 85       | 7.2%    |
| 32768 | 25       | 2.12%   |
| 512   | 19       | 1.61%   |
| 256   | 4        | 0.34%   |
| 3072  | 2        | 0.17%   |
| 32    | 1        | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 207      | 17.63%  |
| 1333    | 130      | 11.07%  |
| 3200    | 102      | 8.69%   |
| 3600    | 95       | 8.09%   |
| 800     | 69       | 5.88%   |
| 2400    | 61       | 5.2%    |
| 2667    | 47       | 4%      |
| 667     | 43       | 3.66%   |
| Unknown | 42       | 3.58%   |
| 2133    | 40       | 3.41%   |
| 1867    | 33       | 2.81%   |
| 3000    | 25       | 2.13%   |
| 3466    | 22       | 1.87%   |
| 2933    | 18       | 1.53%   |
| 1066    | 18       | 1.53%   |
| 3400    | 16       | 1.36%   |
| 1866    | 16       | 1.36%   |
| 3733    | 15       | 1.28%   |
| 1800    | 15       | 1.28%   |
| 266     | 15       | 1.28%   |
| 400     | 12       | 1.02%   |
| 2666    | 10       | 0.85%   |
| 1334    | 10       | 0.85%   |
| 3800    | 9        | 0.77%   |
| 2800    | 7        | 0.6%    |
| 533     | 7        | 0.6%    |
| 333     | 7        | 0.6%    |
| 2000    | 6        | 0.51%   |
| 2048    | 5        | 0.43%   |
| 49926   | 4        | 0.34%   |
| 3333    | 4        | 0.34%   |
| 2472    | 4        | 0.34%   |
| 1639    | 4        | 0.34%   |
| 1400    | 4        | 0.34%   |
| 1067    | 4        | 0.34%   |
| 4800    | 3        | 0.26%   |
| 3866    | 3        | 0.26%   |
| 3666    | 3        | 0.26%   |
| 3500    | 3        | 0.26%   |
| 3100    | 3        | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 74       | 39.78%  |
| Samsung Electronics   | 27       | 14.52%  |
| Canon                 | 24       | 12.9%   |
| Brother Industries    | 22       | 11.83%  |
| Seiko Epson           | 20       | 10.75%  |
| Lexmark International | 4        | 2.15%   |
| Xerox                 | 2        | 1.08%   |
| Prolific Technology   | 2        | 1.08%   |
| Oki Data              | 2        | 1.08%   |
| Dymo-CoStar           | 2        | 1.08%   |
| Toshiba TEC           | 1        | 0.54%   |
| Sato                  | 1        | 0.54%   |
| Ricoh                 | 1        | 0.54%   |
| QinHeng Electronics   | 1        | 0.54%   |
| Pantum                | 1        | 0.54%   |
| Kyocera               | 1        | 0.54%   |
| Apple                 | 1        | 0.54%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Seiko Epson WF-2510 Series                                            | 7        | 3.76%   |
| Samsung M2020 Series                                                  | 7        | 3.76%   |
| HP OfficeJet 6950                                                     | 7        | 3.76%   |
| HP Deskjet 2050 J510                                                  | 5        | 2.69%   |
| Samsung M267x 287x Series                                             | 4        | 2.15%   |
| HP LaserJet 1018                                                      | 4        | 2.15%   |
| HP ENVY 4520 series                                                   | 4        | 2.15%   |
| Canon PIXMA MG3600 Series                                             | 4        | 2.15%   |
| Seiko Epson Printer                                                   | 3        | 1.61%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 3        | 1.61%   |
| Samsung ML-216x Series Laser Printer                                  | 3        | 1.61%   |
| Samsung Composite Device                                              | 3        | 1.61%   |
| HP LaserJet Professional P 1102w                                      | 3        | 1.61%   |
| HP LaserJet P1005                                                     | 3        | 1.61%   |
| HP Deskjet F4500 series                                               | 3        | 1.61%   |
| Canon LiDE 400                                                        | 3        | 1.61%   |
| Brother MFC-L2700DW                                                   | 3        | 1.61%   |
| Brother DCP-1610W                                                     | 3        | 1.61%   |
| Samsung ML-1660 Series                                                | 2        | 1.08%   |
| Samsung ML-1640 Series Laser Printer                                  | 2        | 1.08%   |
| Prolific PL2305 Parallel Port                                         | 2        | 1.08%   |
| Oki Data USB Device                                                   | 2        | 1.08%   |
| Lexmark International InkJet Color Printer                            | 2        | 1.08%   |
| HP OfficeJet 5200 series                                              | 2        | 1.08%   |
| HP Officejet 4630 series                                              | 2        | 1.08%   |
| HP Officejet 4500 G510n-z                                             | 2        | 1.08%   |
| HP Officejet 2620 series                                              | 2        | 1.08%   |
| HP LaserJet P1102                                                     | 2        | 1.08%   |
| HP LaserJet 1200                                                      | 2        | 1.08%   |
| HP ENVY 5000 series                                                   | 2        | 1.08%   |
| HP DeskJet F4200 series                                               | 2        | 1.08%   |
| HP Deskjet 3050A                                                      | 2        | 1.08%   |
| HP DeskJet 2130 series                                                | 2        | 1.08%   |
| Canon PIXMA MX920 Series                                              | 2        | 1.08%   |
| Canon CanoScan LiDE 300                                               | 2        | 1.08%   |
| Brother MFC-1810                                                      | 2        | 1.08%   |
| Brother HL-3140CW series                                              | 2        | 1.08%   |
| Brother DCP-1510                                                      | 2        | 1.08%   |
| Xerox Phaser 6121MFP Scan                                             | 1        | 0.54%   |
| Xerox Phaser 6010N                                                    | 1        | 0.54%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 28       | 51.85%  |
| Seiko Epson        | 13       | 24.07%  |
| Hewlett-Packard    | 7        | 12.96%  |
| Mustek Systems     | 4        | 7.41%   |
| Ultima Electronics | 1        | 1.85%   |
| Plustek            | 1        | 1.85%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 6        | 11.11%  |
| Canon CanoScan LiDE 210                                                               | 5        | 9.26%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3        | 5.56%   |
| Canon CanoScan LiDE 120                                                               | 3        | 5.56%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 2        | 3.7%    |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2        | 3.7%    |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 2        | 3.7%    |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2        | 3.7%    |
| HP Scanjet 200                                                                        | 2        | 3.7%    |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 3.7%    |
| Canon CanoScan LiDE 100                                                               | 2        | 3.7%    |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 1.85%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1        | 1.85%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 1.85%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1        | 1.85%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 1.85%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1        | 1.85%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1        | 1.85%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1        | 1.85%   |
| Plustek 600DPI USB Scanner                                                            | 1        | 1.85%   |
| Mustek Systems SNAPSCAN e22                                                           | 1        | 1.85%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 1.85%   |
| HP ScanJet 3800c                                                                      | 1        | 1.85%   |
| HP ScanJet 3400cse                                                                    | 1        | 1.85%   |
| HP ScanJet 2400c                                                                      | 1        | 1.85%   |
| HP PSC 1200                                                                           | 1        | 1.85%   |
| HP HP4470C                                                                            | 1        | 1.85%   |
| Canon CanoScan LiDE 90                                                                | 1        | 1.85%   |
| Canon CanoScan LiDE 700F                                                              | 1        | 1.85%   |
| Canon CanoScan LiDE 600F                                                              | 1        | 1.85%   |
| Canon CanoScan LiDE 60                                                                | 1        | 1.85%   |
| Canon CanoScan LIDE 25                                                                | 1        | 1.85%   |
| Canon CanoScan LiDE 220                                                               | 1        | 1.85%   |
| Canon CanoScan 4200F                                                                  | 1        | 1.85%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                            | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech                                          | 147      | 34.59%  |
| Microdia                                          | 47       | 11.06%  |
| Microsoft                                         | 45       | 10.59%  |
| Sunplus Innovation Technology                     | 20       | 4.71%   |
| Trust                                             | 13       | 3.06%   |
| ARC International                                 | 12       | 2.82%   |
| Samsung Electronics                               | 11       | 2.59%   |
| Generalplus Technology                            | 11       | 2.59%   |
| Chicony Electronics                               | 10       | 2.35%   |
| Cubeternet                                        | 9        | 2.12%   |
| KYE Systems (Mouse Systems)                       | 7        | 1.65%   |
| Realtek Semiconductor                             | 6        | 1.41%   |
| Huawei Technologies                               | 6        | 1.41%   |
| GEMBIRD                                           | 6        | 1.41%   |
| Z-Star Microelectronics                           | 5        | 1.18%   |
| Sunplus IT                                        | 5        | 1.18%   |
| Apple                                             | 5        | 1.18%   |
| 2M UVC CAMERA                                     | 5        | 1.18%   |
| WaveRider Communications                          | 4        | 0.94%   |
| IMC Networks                                      | 4        | 0.94%   |
| MacroSilicon                                      | 3        | 0.71%   |
| Genesys Logic                                     | 3        | 0.71%   |
| Aveo Technology                                   | 3        | 0.71%   |
| Arkmicro Technologies                             | 3        | 0.71%   |
| Xiongmai                                          | 2        | 0.47%   |
| SunplusIT                                         | 2        | 0.47%   |
| LG Electronics                                    | 2        | 0.47%   |
| Jieli Technology                                  | 2        | 0.47%   |
| Hewlett-Packard                                   | 2        | 0.47%   |
| Creative Technology                               | 2        | 0.47%   |
| Unknown                                           | 1        | 0.24%   |
| TerraTec Electronic                               | 1        | 0.24%   |
| Syntek                                            | 1        | 0.24%   |
| Suyin                                             | 1        | 0.24%   |
| Sunplus Technology                                | 1        | 0.24%   |
| STMicroelectronics Imaging Division (VLSI Vision) | 1        | 0.24%   |
| Sonix Technology                                  | 1        | 0.24%   |
| Silicon Motion                                    | 1        | 0.24%   |
| SiGma Micro                                       | 1        | 0.24%   |
| Razer USA                                         | 1        | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 43       | 10.07%  |
| Microsoft LifeCam HD-3000                  | 22       | 5.15%   |
| Logitech Webcam C170                       | 21       | 4.92%   |
| Logitech HD Pro Webcam C920                | 18       | 4.22%   |
| ARC International Camera                   | 12       | 2.81%   |
| Samsung Galaxy series, misc. (MTP mode)    | 11       | 2.58%   |
| Microdia Camera                            | 11       | 2.58%   |
| Microdia Webcam Vitade AF                  | 9        | 2.11%   |
| Sunplus Aukey-PC-LM1E Camera               | 8        | 1.87%   |
| Microdia USB 2.0 Camera                    | 8        | 1.87%   |
| Microdia Sonix USB 2.0 Camera              | 8        | 1.87%   |
| Logitech Webcam C310                       | 8        | 1.87%   |
| Microsoft LifeCam VX-2000                  | 6        | 1.41%   |
| Microdia Integrated Camera                 | 6        | 1.41%   |
| Logitech QuickCam Pro 9000                 | 6        | 1.41%   |
| Huawei HiCamera                            | 6        | 1.41%   |
| Generalplus GENERAL WEBCAM                 | 6        | 1.41%   |
| Trust WB-6250X Webcam                      | 5        | 1.17%   |
| Sunplus IT AUKEY PC-LM1 USB Camera         | 5        | 1.17%   |
| Logitech HD Webcam C910                    | 5        | 1.17%   |
| Logitech HD Webcam C525                    | 5        | 1.17%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam        | 5        | 1.17%   |
| WaveRider USB 2.0 Camera                   | 4        | 0.94%   |
| Trust 17676 Webcam                         | 4        | 0.94%   |
| Microsoft LifeCam VX-5000                  | 4        | 0.94%   |
| Logitech Webcam C200                       | 4        | 0.94%   |
| Logitech QuickCam E 3500                   | 4        | 0.94%   |
| Logitech C922 Pro Stream Webcam            | 4        | 0.94%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 4        | 0.94%   |
| GEMBIRD USB2.0 PC CAMERA                   | 4        | 0.94%   |
| Apple iPhone 5/5C/5S/6/SE                  | 4        | 0.94%   |
| Trust Webcam                               | 3        | 0.7%    |
| Sunplus HD 720P webcam                     | 3        | 0.7%    |
| Sunplus FHD Camera Microphone              | 3        | 0.7%    |
| Microdia Hy-HD-Camera                      | 3        | 0.7%    |
| Logitech BRIO                              | 3        | 0.7%    |
| Generalplus 808 Camera                     | 3        | 0.7%    |
| Cubeternet USB2.0 Camera                   | 3        | 0.7%    |
| Cubeternet GL-UPC822 UVC WebCam            | 3        | 0.7%    |
| Z-Star Sirius USB2.0 Camera                | 2        | 0.47%   |

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


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 16       | 36.36%  |
| BIT4ID                    | 6        | 13.64%  |
| Realtek Semiconductor     | 5        | 11.36%  |
| Gemalto (was Gemplus)     | 4        | 9.09%   |
| Clay Logic                | 3        | 6.82%   |
| Alcor Micro               | 3        | 6.82%   |
| SCM Microsystems          | 2        | 4.55%   |
| OmniKey                   | 2        | 4.55%   |
| Reiner SCT Kartensysteme  | 1        | 2.27%   |
| Microchip Technology      | 1        | 2.27%   |
| Fujitsu Siemens Computers | 1        | 2.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader                               | 13       | 28.89%  |
| BIT4ID miniLector EVO                                                      | 6        | 13.33%  |
| Realtek Semiconductor Smart Card Reader Interface                          | 5        | 11.11%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 4        | 8.89%   |
| Clay Logic Nitrokey Pro                                                    | 3        | 6.67%   |
| Advanced Card Systems ACR122U                                              | 3        | 6.67%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 4.44%   |
| SCM Microsystems SCR35xx Smart Card Reader                                 | 1        | 2.22%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 2.22%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.22%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 2.22%   |
| OmniKey 3x21 Smart Card Reader                                             | 1        | 2.22%   |
| Microchip Technology SMSC USX101x Reader                                   | 1        | 2.22%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 2.22%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 1        | 2.22%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 2.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1927     | 86.61%  |
| 1     | 258      | 11.6%   |
| 2     | 29       | 1.3%    |
| 3     | 6        | 0.27%   |
| 5     | 3        | 0.13%   |
| 4     | 2        | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 96       | 28.66%  |
| Net/wireless             | 86       | 25.67%  |
| Communication controller | 35       | 10.45%  |
| Chipcard                 | 27       | 8.06%   |
| Unassigned class         | 23       | 6.87%   |
| Sound                    | 13       | 3.88%   |
| Multimedia controller    | 9        | 2.69%   |
| Card reader              | 9        | 2.69%   |
| Camera                   | 8        | 2.39%   |
| Modem                    | 6        | 1.79%   |
| Storage/raid             | 4        | 1.19%   |
| Firewire controller      | 4        | 1.19%   |
| Dvb card                 | 3        | 0.9%    |
| Bluetooth                | 3        | 0.9%    |
| Video                    | 2        | 0.6%    |
| Tv card                  | 2        | 0.6%    |
| Network                  | 2        | 0.6%    |
| Net/ethernet             | 2        | 0.6%    |
| Storage/ide              | 1        | 0.3%    |

