Elementary - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Elementary.

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

Total: 424

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | 0B48h                       | [4c6e5824f2](https://linux-hardware.org/?probe=4c6e5824f2) | Apr 30, 2022 |
| ASUSTek   | P8Z77-V                     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| Dell      | 0J3C2F A00                  | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [1f10d820f8](https://linux-hardware.org/?probe=1f10d820f8) | Apr 27, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [dfadead480](https://linux-hardware.org/?probe=dfadead480) | Apr 27, 2022 |
| Gigabyte  | B150N Phoenix-WIFI-CF       | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek   | ROG STRIX Z590-F GAMING ... | [1b0a41c232](https://linux-hardware.org/?probe=1b0a41c232) | Apr 25, 2022 |
| AZW       | GTi                         | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW       | GTi                         | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ECS       | H61H2-MV                    | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| MSI       | X99A SLI PLUS               | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| Inventec  | D CLASS A02                 | [d00d37285b](https://linux-hardware.org/?probe=d00d37285b) | Apr 19, 2022 |
| ASRock    | Z490 Pro4                   | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Dell      | 0KV62T A01                  | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell      | 0KV62T A01                  | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI       | B450M PRO-VDH MAX           | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| HP        | 1494                        | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| Gigabyte  | H61M-D2H-USB3               | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Fujitsu   | D3531-A1 S26361-D3531-A1    | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| ASUSTek   | B85M-G                      | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| Gigabyte  | B450 AORUS ELITE            | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek   | B85M-G                      | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte  | B450 AORUS ELITE            | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Dell      | 0K240Y A01                  | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| ASUSTek   | TUF X470-PLUS GAMING        | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Lenovo    | 3178 SDK0J40700 WIN 3258... | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| ASUSTek   | PRIME Z390-A                | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| Pegatron  | IPMH61P1                    | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| ASUSTek   | H110I-PLUS                  | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| ASUSTek   | P8H61-M LX3 R2.0            | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| ASRock    | C226 WS                     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ASUSTek   | STRIKER II FORMULA          | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek   | STRIKER II FORMULA          | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| Gigabyte  | B450M DS3H-CF               | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
| ASUSTek   | TUF Gaming B460M-PLUS       | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| Lenovo    | ThinkCentre M58 6258D3G     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo    | ThinkCentre M58 6258D3G     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI       | H97 GAMING 3                | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI       | MEG X570 ACE                | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| HP        | 18E7                        | [ead4fcc358](https://linux-hardware.org/?probe=ead4fcc358) | Mar 29, 2022 |
| ASUSTek   | Rampage IV GENE             | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Dell      | 0C522T A00                  | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell      | 0C522T A00                  | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| MSI       | MPG B550 GAMING EDGE WIF... | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Gigabyte  | A320M-S2H-CF                | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel     | X79Turbo V1.x               | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| AMI       | Cherry Trail CR             | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| AMI       | Cherry Trail CR             | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| ASUSTek   | Rampage IV GENE             | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| ASUSTek   | Rampage IV GENE             | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| ASUSTek   | P8H61-M LX3 R2.0            | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| AOpen     | D1009 A1A4                  | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| MSI       | B85I                        | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| ASRock    | B450M Pro4                  | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| Gigabyte  | B150N Phoenix-WIFI-CF       | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar   | N68S3B                      | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| Dell      | 0HMX8D A01                  | [cfff92df80](https://linux-hardware.org/?probe=cfff92df80) | Mar 09, 2022 |
| ASUSTek   | M11AD                       | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Biostar   | H61MLV2                     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP        | 2ADC                        | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI       | B85I                        | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Dell      | 0PU052                      | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell      | 0PU052                      | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| HP        | 1589                        | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| HP        | 802E                        | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| ASRock    | FM2A58M-DG3+                | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| HP        | 805D                        | [2a09665009](https://linux-hardware.org/?probe=2a09665009) | Mar 02, 2022 |
| ASUSTek   | M4N72-E                     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek   | H81-PLUS                    | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek   | H81-PLUS                    | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| Gigabyte  | X470 AORUS ULTRA GAMING-... | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| Gigabyte  | Z390 UD                     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| ASUSTek   | PRIME B450M-GAMING/BR       | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| MSI       | B85I                        | [24674e9e3a](https://linux-hardware.org/?probe=24674e9e3a) | Feb 20, 2022 |
| Intel     | DH61BE AAG14062-210         | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| MSI       | B85I                        | [633f6bf495](https://linux-hardware.org/?probe=633f6bf495) | Feb 19, 2022 |
| ASUSTek   | M11AD                       | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| ASUSTek   | P5B                         | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel     | H61                         | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| ASUSTek   | PRIME Z590-A                | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar   | A68MD PRO                   | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| ASUSTek   | PRIME B250-PRO              | [be377c733e](https://linux-hardware.org/?probe=be377c733e) | Feb 14, 2022 |
| MSI       | B85I                        | [28c1f1b8ae](https://linux-hardware.org/?probe=28c1f1b8ae) | Feb 13, 2022 |
| ASUSTek   | PRIME Z590-A                | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| MSI       | B85I                        | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Gigabyte  | F2A68HM-H                   | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Gigabyte  | F2A68HM-H                   | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| ASUSTek   | PRIME A320M-K               | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek   | PRIME B360M-K               | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| ASUSTek   | H110M-C                     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| MSI       | B450I GAMING PLUS AC        | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| ECS       | H55H-M                      | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| ASUSTek   | ROG STRIX B360-H GAMING     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Lenovo    | NO DPK                      | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| HP        | 802E                        | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| ASUSTek   | H110M-C                     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek   | P5B                         | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn   | NETBOX nT-435/535 Ver       | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn   | NETBOX nT-435/535 Ver       | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP        | ProLiant ML110 G7           | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| ASUSTek   | H110M-C                     | [4d2233f824](https://linux-hardware.org/?probe=4d2233f824) | Feb 03, 2022 |
| HP        | 339A                        | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| Unknown   | Unknown                     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| HP        | 805D                        | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| ASUSTek   | H110I-PLUS                  | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte  | B75M-D3H                    | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| MSI       | Z270 KRAIT GAMING           | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Gigabyte  | H61M-DS2                    | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| ASRock    | H61M-HVS                    | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock    | H61M-HVS                    | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer      | ConceptD CM100-51A V:1.1    | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| FIRICH    | J1900                       | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| ASUSTek   | ROG STRIX B360-H GAMING     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| ASUSTek   | ROG STRIX X570-E GAMING     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek   | TUF GAMING B550M-PLUS       | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| ASUSTek   | TUF B365M-PLUS GAMING       | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI       | B450 TOMAHAWK MAX II        | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| MSI       | B450M-A PRO MAX             | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| ASUSTek   | P8H61-M LX3 R2.0            | [a76b9e67bb](https://linux-hardware.org/?probe=a76b9e67bb) | Jan 14, 2022 |
| ASUSTek   | H61M-CS                     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| Unknown   | T3 MRD                      | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI       | X470 GAMING PLUS MAX        | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek   | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Foxconn   | 2AB1                        | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| Foxconn   | 2AB1                        | [de61623232](https://linux-hardware.org/?probe=de61623232) | Jan 11, 2022 |
| ASUSTek   | H110M-C                     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Gigabyte  | X570 AORUS ELITE            | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| HP        | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte  | GA-970A-D3                  | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock    | Z370 Pro4                   | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| ASRock    | B450M-HDV R4.0              | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| ASRock    | H97M Pro4                   | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| ASRock    | AB350M Pro4                 | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| Gigabyte  | B85M-DS3H-A                 | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| MSI       | 2A9C                        | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| HP        | 3397                        | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek   | X79-DELUXE                  | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| HP        | 1589                        | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn   | 2AB1                        | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| ASUSTek   | TUF GAMING B550M-PLUS       | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Gigabyte  | Z390 UD                     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| ASRock    | Z590 Phantom Gaming 4/ac    | [b52ca671f7](https://linux-hardware.org/?probe=b52ca671f7) | Dec 24, 2021 |
| Apple     | Mac-F42C88C8 Proto1         | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| ASUSTek   | H97-PLUS                    | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| MSI       | B450-A PRO MAX              | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte  | H310M S2P                   | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Foxconn   | 2AB1                        | [d9077a5d94](https://linux-hardware.org/?probe=d9077a5d94) | Dec 18, 2021 |
| Foxconn   | 2AB1                        | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Gigabyte  | Z590 AORUS ELITE AX         | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| ASUSTek   | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| Pegatron  | IPMH61P1                    | [1ba6ea2ee9](https://linux-hardware.org/?probe=1ba6ea2ee9) | Dec 14, 2021 |
| Acer      | ConceptD CM100-51A V:1.1    | [0b3e5753fc](https://linux-hardware.org/?probe=0b3e5753fc) | Dec 13, 2021 |
| ASUSTek   | TUF GAMING B560M-PLUS       | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek   | PRIME A320M-K               | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| ASUSTek   | H81M-C                      | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| Dell      | 0MGK50 A02                  | [df4bb96e67](https://linux-hardware.org/?probe=df4bb96e67) | Dec 08, 2021 |
| ASUSTek   | M5A78L-M LX/BR              | [5c46f5e832](https://linux-hardware.org/?probe=5c46f5e832) | Dec 07, 2021 |
| Gigabyte  | AX370-Gaming-CF se1         | [7cb1ebd6c9](https://linux-hardware.org/?probe=7cb1ebd6c9) | Dec 07, 2021 |
| Gigabyte  | X570 AORUS PRO WIFI         | [a8e4016566](https://linux-hardware.org/?probe=a8e4016566) | Dec 06, 2021 |
| Gigabyte  | X570 AORUS PRO WIFI         | [ebfed157e7](https://linux-hardware.org/?probe=ebfed157e7) | Dec 06, 2021 |
| Acer      | Aspire X3990                | [e291d06394](https://linux-hardware.org/?probe=e291d06394) | Dec 05, 2021 |
| MSI       | Z370 KRAIT GAMING           | [b213dc07b8](https://linux-hardware.org/?probe=b213dc07b8) | Dec 04, 2021 |
| MSI       | Z370 KRAIT GAMING           | [b562e90f75](https://linux-hardware.org/?probe=b562e90f75) | Dec 04, 2021 |
| ASRock    | Z370 Pro4                   | [4ada22b406](https://linux-hardware.org/?probe=4ada22b406) | Dec 04, 2021 |
| Pegatron  | Benicia                     | [51dae15bcd](https://linux-hardware.org/?probe=51dae15bcd) | Dec 03, 2021 |
| Gigabyte  | AX370-Gaming-CF se1         | [313d4d0bd8](https://linux-hardware.org/?probe=313d4d0bd8) | Dec 03, 2021 |
| HP        | 8653 A                      | [85d1730019](https://linux-hardware.org/?probe=85d1730019) | Dec 01, 2021 |
| Gigabyte  | B85M-DS3H-A                 | [fbe4820444](https://linux-hardware.org/?probe=fbe4820444) | Dec 01, 2021 |
| ASUSTek   | ROG STRIX Z490-F GAMING     | [500f9c8851](https://linux-hardware.org/?probe=500f9c8851) | Dec 01, 2021 |
| ASUSTek   | PRIME B365M-A               | [c7cbb50843](https://linux-hardware.org/?probe=c7cbb50843) | Nov 30, 2021 |
| Chuwi     | LarkBox Pro                 | [4af62a6057](https://linux-hardware.org/?probe=4af62a6057) | Nov 29, 2021 |
| Biostar   | TH55XE                      | [9e420cc495](https://linux-hardware.org/?probe=9e420cc495) | Nov 28, 2021 |
| MSI       | H81M-P33                    | [8812103632](https://linux-hardware.org/?probe=8812103632) | Nov 28, 2021 |
| HP        | 1497                        | [6f042fb99c](https://linux-hardware.org/?probe=6f042fb99c) | Nov 28, 2021 |
| ASUSTek   | PRIME X470-PRO              | [2845eaa223](https://linux-hardware.org/?probe=2845eaa223) | Nov 27, 2021 |
| Acer      | Aspire X3990                | [5559b2d988](https://linux-hardware.org/?probe=5559b2d988) | Nov 27, 2021 |
| Foxconn   | 2AB1                        | [09a8a91f9e](https://linux-hardware.org/?probe=09a8a91f9e) | Nov 26, 2021 |
| HP        | 1825                        | [3648c360a9](https://linux-hardware.org/?probe=3648c360a9) | Nov 26, 2021 |
| Gigabyte  | B450 I AORUS PRO WIFI-CF    | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Gigabyte  | Z390 GAMING X-CF            | [34e71f1e27](https://linux-hardware.org/?probe=34e71f1e27) | Nov 25, 2021 |
| Gigabyte  | B450M DS3H-CF               | [0fccfea38c](https://linux-hardware.org/?probe=0fccfea38c) | Nov 25, 2021 |
| ASUSTek   | P8H61-MX R2.0               | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| Biostar   | TA790GXE 128M               | [93ff10a9c2](https://linux-hardware.org/?probe=93ff10a9c2) | Nov 21, 2021 |
| Gigabyte  | B85M-D3V-A                  | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| MSI       | X470 GAMING PLUS MAX        | [9e7d926319](https://linux-hardware.org/?probe=9e7d926319) | Nov 19, 2021 |
| HP        | 0AECh D                     | [c81bcc92ca](https://linux-hardware.org/?probe=c81bcc92ca) | Nov 19, 2021 |
| Foxconn   | 2AB1                        | [f965bf0bd8](https://linux-hardware.org/?probe=f965bf0bd8) | Nov 18, 2021 |
| Apple     | Mac-F4208DC8 PVT            | [3369764322](https://linux-hardware.org/?probe=3369764322) | Nov 17, 2021 |
| Gigabyte  | EP43T-USB3                  | [a24bb09910](https://linux-hardware.org/?probe=a24bb09910) | Nov 15, 2021 |
| Gigabyte  | H81M-H                      | [a895ed29e0](https://linux-hardware.org/?probe=a895ed29e0) | Nov 14, 2021 |
| ASRock    | X570 Extreme4               | [e49fdf2db4](https://linux-hardware.org/?probe=e49fdf2db4) | Nov 13, 2021 |
| MSI       | 970A-G43                    | [19714dd1a0](https://linux-hardware.org/?probe=19714dd1a0) | Nov 08, 2021 |
| Gigabyte  | Z270X-Gaming 5              | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| Intel     | DG35EC AAE29266-205         | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel     | DG35EC AAE29266-205         | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| ASRock    | P67 Extreme4                | [a70eb2d3f8](https://linux-hardware.org/?probe=a70eb2d3f8) | Oct 29, 2021 |
| ASRock    | P67 Extreme4                | [0a07f4c735](https://linux-hardware.org/?probe=0a07f4c735) | Oct 29, 2021 |
| MSI       | 2A9Ch                       | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Foxconn   | 2AB1                        | [49aef5b72e](https://linux-hardware.org/?probe=49aef5b72e) | Oct 26, 2021 |
| HP        | 158B                        | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| HP        | 339A                        | [d9c6208191](https://linux-hardware.org/?probe=d9c6208191) | Oct 16, 2021 |
| Dell      | 0M9KCM A02                  | [a925b0f3d1](https://linux-hardware.org/?probe=a925b0f3d1) | Oct 12, 2021 |
| Gigabyte  | AB350-Gaming 3-CF           | [f6e75d0258](https://linux-hardware.org/?probe=f6e75d0258) | Oct 09, 2021 |
| MSI       | B460M PRO-VDH WIFI          | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASUSTek   | TUF GAMING B560M-PLUS       | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
| Shuttle   | FS61                        | [b25047a516](https://linux-hardware.org/?probe=b25047a516) | Oct 01, 2021 |
| Gigabyte  | H67A-USB3-B3                | [9440c234ae](https://linux-hardware.org/?probe=9440c234ae) | Sep 28, 2021 |
| Gigabyte  | H67A-USB3-B3                | [aaabb5b80f](https://linux-hardware.org/?probe=aaabb5b80f) | Sep 28, 2021 |
| Apple     | Mac-F221BEC8                | [1754c64091](https://linux-hardware.org/?probe=1754c64091) | Sep 27, 2021 |
| ASUSTek   | P7H55-M                     | [3367bc011a](https://linux-hardware.org/?probe=3367bc011a) | Sep 25, 2021 |
| Dell      | 0Y5DDC A00                  | [df95ea94b8](https://linux-hardware.org/?probe=df95ea94b8) | Sep 25, 2021 |
| Dell      | 0Y5DDC A00                  | [10ee1abc07](https://linux-hardware.org/?probe=10ee1abc07) | Sep 25, 2021 |
| ASRock    | M3A790GXH/128M              | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| Gigabyte  | H67A-USB3-B3                | [0aab60dbc8](https://linux-hardware.org/?probe=0aab60dbc8) | Sep 24, 2021 |
| Intel     | X79 V1.x                    | [19223e911c](https://linux-hardware.org/?probe=19223e911c) | Sep 22, 2021 |
| Gigabyte  | H67A-USB3-B3                | [772b49f342](https://linux-hardware.org/?probe=772b49f342) | Sep 21, 2021 |
| ASUSTek   | M4N78-AM                    | [3d8e0efc00](https://linux-hardware.org/?probe=3d8e0efc00) | Sep 21, 2021 |
| ASRock    | A320M-HDV                   | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Gigabyte  | Z68P-DS3                    | [1ddd2fcf1d](https://linux-hardware.org/?probe=1ddd2fcf1d) | Sep 14, 2021 |
| Intel     | H61                         | [0010dbcb5e](https://linux-hardware.org/?probe=0010dbcb5e) | Sep 10, 2021 |
| HP        | 8767 A                      | [7f022c67ac](https://linux-hardware.org/?probe=7f022c67ac) | Sep 09, 2021 |
| Gigabyte  | B450M DS3H V2               | [633441bc2b](https://linux-hardware.org/?probe=633441bc2b) | Sep 05, 2021 |
| ASUSTek   | ROG STRIX Z590-F GAMING ... | [c9476d5d06](https://linux-hardware.org/?probe=c9476d5d06) | Sep 02, 2021 |
| Gigabyte  | F2A55M-HD2                  | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| ASRock    | H81TM-ITX R2.0              | [4f04e7309e](https://linux-hardware.org/?probe=4f04e7309e) | Aug 30, 2021 |
| ASUSTek   | M5A78L-M LX/BR              | [d0ff1c6977](https://linux-hardware.org/?probe=d0ff1c6977) | Aug 25, 2021 |
| ASUSTek   | P6X58D-E                    | [db1ef28e92](https://linux-hardware.org/?probe=db1ef28e92) | Aug 20, 2021 |
| MSI       | X470 GAMING PLUS MAX        | [1176a287c7](https://linux-hardware.org/?probe=1176a287c7) | Aug 19, 2021 |
| ASUSTek   | TUF GAMING B450M-PRO II     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| Gigabyte  | X570 I AORUS PRO WIFI       | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Gigabyte  | H310M M.2 x.x               | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte  | H310M M.2 x.x               | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| Acer      | Aspire XC-603G              | [8a37f28ecc](https://linux-hardware.org/?probe=8a37f28ecc) | Jul 31, 2021 |
| ASUSTek   | P5KPL-AM SE                 | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Biostar   | H61MH                       | [adca68749a](https://linux-hardware.org/?probe=adca68749a) | Jul 23, 2021 |
| Biostar   | H61MH                       | [2c690e433f](https://linux-hardware.org/?probe=2c690e433f) | Jul 23, 2021 |
| ASUSTek   | ROG STRIX Z390-H GAMING     | [9e27318e84](https://linux-hardware.org/?probe=9e27318e84) | Jul 14, 2021 |
| ASRock    | B450 Pro4                   | [c5d0611f79](https://linux-hardware.org/?probe=c5d0611f79) | Jun 13, 2021 |
| ASUSTek   | PRIME A320M-K               | [5e0580b431](https://linux-hardware.org/?probe=5e0580b431) | Jun 08, 2021 |
| ASUSTek   | H81M-K                      | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| ASUSTek   | TUF GAMING B550M-PLUS       | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| ASUSTek   | TUF GAMING B550M-PLUS       | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| ASUSTek   | ROG STRIX B450-I GAMING     | [a208e8a358](https://linux-hardware.org/?probe=a208e8a358) | May 01, 2021 |
| Gigabyte  | AB350M-DS3H V2-CF           | [98d6e8f2d2](https://linux-hardware.org/?probe=98d6e8f2d2) | Apr 15, 2021 |
| ASUSTek   | SABERTOOTH Z87              | [542d0b7163](https://linux-hardware.org/?probe=542d0b7163) | Apr 13, 2021 |
| Dell      | 06NWYK A01                  | [304541ce36](https://linux-hardware.org/?probe=304541ce36) | Apr 08, 2021 |
| Dell      | 06NWYK A01                  | [47766de8d9](https://linux-hardware.org/?probe=47766de8d9) | Apr 07, 2021 |
| MSI       | H61M-P31                    | [867b109a0b](https://linux-hardware.org/?probe=867b109a0b) | Apr 07, 2021 |
| HP        | 843F                        | [d5b68ba3fb](https://linux-hardware.org/?probe=d5b68ba3fb) | Apr 07, 2021 |
| MSI       | B450M PRO-VDH MAX           | [9a1463fd59](https://linux-hardware.org/?probe=9a1463fd59) | Mar 22, 2021 |
| HP        | 843F                        | [de77cd09ab](https://linux-hardware.org/?probe=de77cd09ab) | Mar 22, 2021 |
| Gigabyte  | H61M-S2PV                   | [bbe4962b33](https://linux-hardware.org/?probe=bbe4962b33) | Mar 22, 2021 |
| HP        | 843F                        | [a4fc49c430](https://linux-hardware.org/?probe=a4fc49c430) | Mar 09, 2021 |
| MSI       | B450M PRO-VDH MAX           | [65c7806bad](https://linux-hardware.org/?probe=65c7806bad) | Mar 09, 2021 |
| MSI       | B450M PRO-VDH MAX           | [e1289a40a1](https://linux-hardware.org/?probe=e1289a40a1) | Feb 28, 2021 |
| Lenovo    | MAHOBAY NOK                 | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| MSI       | B450M PRO-VDH MAX           | [d152990d34](https://linux-hardware.org/?probe=d152990d34) | Feb 13, 2021 |
| ASUSTek   | ROG STRIX B350-F GAMING     | [268b9f895a](https://linux-hardware.org/?probe=268b9f895a) | Feb 10, 2021 |
| Gigabyte  | Z77-DS3H                    | [a5a556b691](https://linux-hardware.org/?probe=a5a556b691) | Feb 09, 2021 |
| Gigabyte  | A320M-S2H V2-CF             | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| MSI       | B450M PRO-VDH MAX           | [895ec88c20](https://linux-hardware.org/?probe=895ec88c20) | Feb 08, 2021 |
| MSI       | B450M PRO-VDH MAX           | [458481448c](https://linux-hardware.org/?probe=458481448c) | Feb 07, 2021 |
| ASRock    | Z75 Pro3                    | [f2d919b5c5](https://linux-hardware.org/?probe=f2d919b5c5) | Feb 03, 2021 |
| Biostar   | Hi-Fi A70U3P                | [c2727e98b9](https://linux-hardware.org/?probe=c2727e98b9) | Feb 02, 2021 |
| Biostar   | Hi-Fi A70U3P                | [2c11d020c7](https://linux-hardware.org/?probe=2c11d020c7) | Feb 02, 2021 |
| MSI       | B450M PRO-VDH MAX           | [98cc7a4bca](https://linux-hardware.org/?probe=98cc7a4bca) | Jan 15, 2021 |
| Gigabyte  | GA-MA78GM-S2H               | [d40272076d](https://linux-hardware.org/?probe=d40272076d) | Jan 13, 2021 |
| Gigabyte  | GA-MA78GM-S2H               | [d31c109973](https://linux-hardware.org/?probe=d31c109973) | Jan 13, 2021 |
| EVGA      | 132-CK-NF79 2               | [44c54ae3df](https://linux-hardware.org/?probe=44c54ae3df) | Jan 09, 2021 |
| MSI       | P35 Platinum                | [105ebcfc8d](https://linux-hardware.org/?probe=105ebcfc8d) | Jan 08, 2021 |
| Gigabyte  | G31M-ES2L                   | [4e7d5b4879](https://linux-hardware.org/?probe=4e7d5b4879) | Jan 07, 2021 |
| ASUSTek   | M5A97                       | [0f975cd5e6](https://linux-hardware.org/?probe=0f975cd5e6) | Jan 03, 2021 |
| ASUSTek   | CM6330_CM6630_CM6730_CM6... | [721dd0a694](https://linux-hardware.org/?probe=721dd0a694) | Jan 03, 2021 |
| MSI       | B450M PRO-VDH MAX           | [7197a45b8a](https://linux-hardware.org/?probe=7197a45b8a) | Dec 30, 2020 |
| Dell      | 0T656F A02                  | [1830ce642b](https://linux-hardware.org/?probe=1830ce642b) | Dec 29, 2020 |
| ASUSTek   | M5A97                       | [800aa16703](https://linux-hardware.org/?probe=800aa16703) | Dec 29, 2020 |
| MSI       | B450M PRO-VDH MAX           | [803e6b6194](https://linux-hardware.org/?probe=803e6b6194) | Dec 25, 2020 |
| ASUSTek   | M5A99X EVO R2.0             | [f7d949f5a7](https://linux-hardware.org/?probe=f7d949f5a7) | Dec 23, 2020 |
| Biostar   | TA785G3 HD                  | [ed91ded9e9](https://linux-hardware.org/?probe=ed91ded9e9) | Dec 23, 2020 |
| ASRock    | Z87E-ITX                    | [861b40ea1d](https://linux-hardware.org/?probe=861b40ea1d) | Dec 21, 2020 |
| Dell      | 0GN723                      | [a952bf5fa6](https://linux-hardware.org/?probe=a952bf5fa6) | Dec 20, 2020 |
| HP        | 8433 11                     | [691ef58a05](https://linux-hardware.org/?probe=691ef58a05) | Dec 09, 2020 |
| ASUSTek   | PRIME H310M-E R2.0          | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Gigabyte  | H61M-DS2                    | [49263df7ee](https://linux-hardware.org/?probe=49263df7ee) | Dec 02, 2020 |
| HP        | 304Bh                       | [d30d065810](https://linux-hardware.org/?probe=d30d065810) | Nov 30, 2020 |
| Gigabyte  | Z77M-D3H                    | [47c75561ac](https://linux-hardware.org/?probe=47c75561ac) | Nov 21, 2020 |
| ASUSTek   | TUF GAMING X570-PLUS        | [10e9d31bdb](https://linux-hardware.org/?probe=10e9d31bdb) | Nov 20, 2020 |
| MSI       | B450M PRO-VDH MAX           | [29e128bea9](https://linux-hardware.org/?probe=29e128bea9) | Nov 20, 2020 |
| ASUSTek   | PRIME Z270-A                | [d47493ecae](https://linux-hardware.org/?probe=d47493ecae) | Nov 16, 2020 |
| Gigabyte  | H81M-S2H                    | [54fd3c5678](https://linux-hardware.org/?probe=54fd3c5678) | Nov 15, 2020 |
| MSI       | B450M PRO-M2 MAX            | [f2face0a01](https://linux-hardware.org/?probe=f2face0a01) | Nov 07, 2020 |
| ASUSTek   | PRIME A320I-K               | [6bfc04099a](https://linux-hardware.org/?probe=6bfc04099a) | Nov 06, 2020 |
| eMachines | EL1358G                     | [9aabea4465](https://linux-hardware.org/?probe=9aabea4465) | Oct 28, 2020 |
| HP        | 8433 11                     | [670028bf54](https://linux-hardware.org/?probe=670028bf54) | Oct 16, 2020 |
| MSI       | P35 Platinum                | [232a14759f](https://linux-hardware.org/?probe=232a14759f) | Oct 14, 2020 |
| MSI       | MAG B550M MORTAR            | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| HP        | 304Ah                       | [5143880fd9](https://linux-hardware.org/?probe=5143880fd9) | Oct 09, 2020 |
| ASUSTek   | PRIME A320M-K               | [55e4fca971](https://linux-hardware.org/?probe=55e4fca971) | Oct 08, 2020 |
| ASUSTek   | TUF B360-PLUS GAMING        | [1779589a19](https://linux-hardware.org/?probe=1779589a19) | Oct 08, 2020 |
| Gigabyte  | Z390 DESIGNARE-CF           | [f304a2629f](https://linux-hardware.org/?probe=f304a2629f) | Oct 04, 2020 |
| Acer      | WMCP78M                     | [2510b2bc49](https://linux-hardware.org/?probe=2510b2bc49) | Oct 02, 2020 |
| Intel     | DG41RQ AAE54511-204         | [651cef3c94](https://linux-hardware.org/?probe=651cef3c94) | Sep 29, 2020 |
| MSI       | FM2-A55M-E33                | [50d8cc3e2d](https://linux-hardware.org/?probe=50d8cc3e2d) | Sep 28, 2020 |
| ASUSTek   | Z170-DELUXE                 | [8eef95cd00](https://linux-hardware.org/?probe=8eef95cd00) | Sep 12, 2020 |
| MSI       | B450 TOMAHAWK MAX           | [73d7e76e09](https://linux-hardware.org/?probe=73d7e76e09) | Sep 11, 2020 |
| Dell      | 0Y958C A00                  | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Gigabyte  | F2A88XN-WIFI                | [3b51467541](https://linux-hardware.org/?probe=3b51467541) | Sep 06, 2020 |
| Lenovo    | MAHOBAY NOK                 | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| ASUSTek   | CM6330_CM6630_CM6730_CM6... | [78ec970ee1](https://linux-hardware.org/?probe=78ec970ee1) | Aug 29, 2020 |
| ASUSTek   | STRIX Z270H GAMING          | [ce54993f5d](https://linux-hardware.org/?probe=ce54993f5d) | Aug 29, 2020 |
| ASUSTek   | M5A78L-M PLUS/USB3          | [40f5f91c4e](https://linux-hardware.org/?probe=40f5f91c4e) | Aug 26, 2020 |
| HP        | 81B4                        | [6747078a67](https://linux-hardware.org/?probe=6747078a67) | Aug 24, 2020 |
| HP        | 81B4                        | [ff66e031e4](https://linux-hardware.org/?probe=ff66e031e4) | Aug 18, 2020 |
| ASUSTek   | SABERTOOTH Z87              | [86ff4005e2](https://linux-hardware.org/?probe=86ff4005e2) | Aug 15, 2020 |
| MSI       | B450M PRO-VDH MAX           | [ae51610784](https://linux-hardware.org/?probe=ae51610784) | Aug 09, 2020 |
| ASUSTek   | H81I-PLUS                   | [7259e07174](https://linux-hardware.org/?probe=7259e07174) | Aug 07, 2020 |
| SYS       | H310CH5-TI2                 | [fb33742784](https://linux-hardware.org/?probe=fb33742784) | Aug 06, 2020 |
| Gigabyte  | Z97-D3H-CF                  | [fd308ae7e8](https://linux-hardware.org/?probe=fd308ae7e8) | Aug 03, 2020 |
| ASUSTek   | P8H61-M LX3 R2.0            | [6cf9ba1da5](https://linux-hardware.org/?probe=6cf9ba1da5) | Jul 24, 2020 |
| ASUSTek   | P8H61-M LX3 R2.0            | [9372988884](https://linux-hardware.org/?probe=9372988884) | Jul 24, 2020 |
| Dell      | 08NPPY A00                  | [ca6080756b](https://linux-hardware.org/?probe=ca6080756b) | Jul 24, 2020 |
| Dell      | 08NPPY A00                  | [41e1632a84](https://linux-hardware.org/?probe=41e1632a84) | Jul 24, 2020 |
| HP        | 2ADC                        | [2faf91f855](https://linux-hardware.org/?probe=2faf91f855) | Jul 02, 2020 |
| MSI       | B450M PRO-VDH MAX           | [9159f538a0](https://linux-hardware.org/?probe=9159f538a0) | Jun 28, 2020 |
| ASUSTek   | CM6330_CM6630_CM6730_CM6... | [f7a297ae2c](https://linux-hardware.org/?probe=f7a297ae2c) | Jun 23, 2020 |
| Gigabyte  | G31M-ES2L                   | [f9f7ec4c96](https://linux-hardware.org/?probe=f9f7ec4c96) | May 27, 2020 |
| ASUSTek   | P8Z77-V LX                  | [aa53a3eba5](https://linux-hardware.org/?probe=aa53a3eba5) | May 26, 2020 |
| MSI       | B450M PRO-VDH MAX           | [0e7c8d0cdc](https://linux-hardware.org/?probe=0e7c8d0cdc) | May 25, 2020 |
| Acer      | EQ45M                       | [a682473a39](https://linux-hardware.org/?probe=a682473a39) | May 23, 2020 |
| ASUSTek   | PRIME A320M-K               | [14dfb9eb8c](https://linux-hardware.org/?probe=14dfb9eb8c) | May 22, 2020 |
| ASUSTek   | PRIME A320M-K               | [299eb96cce](https://linux-hardware.org/?probe=299eb96cce) | May 22, 2020 |
| ASUSTek   | CM6330_CM6630_CM6730_CM6... | [cb10b79124](https://linux-hardware.org/?probe=cb10b79124) | May 16, 2020 |
| ASUSTek   | CM6330_CM6630_CM6730_CM6... | [592e93d734](https://linux-hardware.org/?probe=592e93d734) | May 16, 2020 |
| MSI       | GF615M-P33 V2               | [e6c02461aa](https://linux-hardware.org/?probe=e6c02461aa) | May 14, 2020 |
| ASRock    | B450M-HDV R4.0              | [484cc8fd5a](https://linux-hardware.org/?probe=484cc8fd5a) | May 07, 2020 |
| ASRock    | B450M-HDV R4.0              | [dbbea9cdaf](https://linux-hardware.org/?probe=dbbea9cdaf) | May 07, 2020 |
| Intel     | DG33FB AAD81072-306         | [2c0b3102ba](https://linux-hardware.org/?probe=2c0b3102ba) | May 01, 2020 |
| ASUSTek   | CM6330_CM6630_CM6730_CM6... | [7a18707ff5](https://linux-hardware.org/?probe=7a18707ff5) | Apr 26, 2020 |
| Acer      | EQ45M                       | [03e154e2dc](https://linux-hardware.org/?probe=03e154e2dc) | Apr 21, 2020 |
| eMachines | EL1358G                     | [0ec6f0c0df](https://linux-hardware.org/?probe=0ec6f0c0df) | Apr 20, 2020 |
| ASUSTek   | ROG STRIX B360-I GAMING     | [7fa6504e44](https://linux-hardware.org/?probe=7fa6504e44) | Apr 18, 2020 |
| ASUSTek   | ROG STRIX B350-F GAMING     | [21eac3f5ab](https://linux-hardware.org/?probe=21eac3f5ab) | Apr 14, 2020 |
| MSI       | H110M PRO-VD                | [a69e76d844](https://linux-hardware.org/?probe=a69e76d844) | Apr 11, 2020 |
| ASUSTek   | TUF B365M-PLUS GAMING       | [fb24b9471a](https://linux-hardware.org/?probe=fb24b9471a) | Apr 08, 2020 |
| ASUSTek   | TUF B365M-PLUS GAMING       | [9ba07d6518](https://linux-hardware.org/?probe=9ba07d6518) | Apr 08, 2020 |
| ASUSTek   | P5K                         | [60860911b6](https://linux-hardware.org/?probe=60860911b6) | Apr 03, 2020 |
| MSI       | MPG Z390 GAMING PRO CARB... | [d69e7b9642](https://linux-hardware.org/?probe=d69e7b9642) | Apr 02, 2020 |
| ECS       | H55H-M                      | [1673d5808e](https://linux-hardware.org/?probe=1673d5808e) | Mar 31, 2020 |
| ASRock    | Z77 Extreme4                | [1ea076e57b](https://linux-hardware.org/?probe=1ea076e57b) | Mar 19, 2020 |
| MSI       | B450 GAMING PLUS MAX        | [642694d59f](https://linux-hardware.org/?probe=642694d59f) | Mar 19, 2020 |
| ASUSTek   | P5K                         | [64c435a307](https://linux-hardware.org/?probe=64c435a307) | Mar 17, 2020 |
| ASUSTek   | P5K                         | [d532983f25](https://linux-hardware.org/?probe=d532983f25) | Mar 17, 2020 |
| MSI       | B450 GAMING PLUS MAX        | [86896f4c65](https://linux-hardware.org/?probe=86896f4c65) | Mar 17, 2020 |
| ASRock    | Z77 Extreme4                | [847badc92c](https://linux-hardware.org/?probe=847badc92c) | Mar 17, 2020 |
| ASRock    | B85M Pro3                   | [765094a989](https://linux-hardware.org/?probe=765094a989) | Mar 10, 2020 |
| MSI       | Z170A PC MATE               | [201d14e45c](https://linux-hardware.org/?probe=201d14e45c) | Mar 09, 2020 |
| ASUSTek   | P8B75-M                     | [56ae5142e3](https://linux-hardware.org/?probe=56ae5142e3) | Feb 24, 2020 |
| ASUSTek   | SABERTOOTH 990FX/GEN3 R2... | [9c21c6ca8e](https://linux-hardware.org/?probe=9c21c6ca8e) | Feb 17, 2020 |
| ASUSTek   | SABERTOOTH 990FX/GEN3 R2... | [fa7ad30945](https://linux-hardware.org/?probe=fa7ad30945) | Feb 17, 2020 |
| ASUSTek   | SABERTOOTH 990FX/GEN3 R2... | [8eb7f19502](https://linux-hardware.org/?probe=8eb7f19502) | Feb 17, 2020 |
| ASUSTek   | Maximus V FORMULA           | [713f5c5aaf](https://linux-hardware.org/?probe=713f5c5aaf) | Feb 14, 2020 |
| Gigabyte  | H67M-D2-B3                  | [8b9d4bcb86](https://linux-hardware.org/?probe=8b9d4bcb86) | Feb 01, 2020 |
| Gigabyte  | GA-990X-Gaming SLI-CF       | [03eef2b7d3](https://linux-hardware.org/?probe=03eef2b7d3) | Feb 01, 2020 |
| Gigabyte  | GA-990X-Gaming SLI-CF       | [d0ec134fe1](https://linux-hardware.org/?probe=d0ec134fe1) | Jan 31, 2020 |
| Gigabyte  | GA-990X-Gaming SLI-CF       | [cd4d0236ad](https://linux-hardware.org/?probe=cd4d0236ad) | Jan 30, 2020 |
| MSI       | FM2-A55M-E33                | [4587ab8edd](https://linux-hardware.org/?probe=4587ab8edd) | Jan 25, 2020 |
| MSI       | FM2-A55M-E33                | [93fb1697b5](https://linux-hardware.org/?probe=93fb1697b5) | Jan 25, 2020 |
| Gigabyte  | H97-HD3                     | [80245136bd](https://linux-hardware.org/?probe=80245136bd) | Jan 18, 2020 |
| ASRock    | Z87 Extreme6                | [ffb3f65bcd](https://linux-hardware.org/?probe=ffb3f65bcd) | Jan 18, 2020 |
| Dell      | 0KWVT8 A00                  | [55b5255c24](https://linux-hardware.org/?probe=55b5255c24) | Jan 18, 2020 |
| ASRock    | N68-GS4/USB3 FX R2.0        | [1a903c9d61](https://linux-hardware.org/?probe=1a903c9d61) | Jan 14, 2020 |
| Pegatron  | IPMH61P1                    | [2a47818e18](https://linux-hardware.org/?probe=2a47818e18) | Jan 06, 2020 |
| ASRock    | H87M Pro4                   | [40dee920a9](https://linux-hardware.org/?probe=40dee920a9) | Dec 25, 2019 |
| Gigabyte  | Z390 GAMING SLI-CF          | [41795f04de](https://linux-hardware.org/?probe=41795f04de) | Dec 24, 2019 |
| MSI       | A320M PRO-VD PLUS           | [805e960aa9](https://linux-hardware.org/?probe=805e960aa9) | Dec 18, 2019 |
| ASRock    | X399 Phantom Gaming 6       | [b89b031eb9](https://linux-hardware.org/?probe=b89b031eb9) | Dec 14, 2019 |
| MSI       | B150M BAZOOKA               | [3afe42946d](https://linux-hardware.org/?probe=3afe42946d) | Dec 12, 2019 |
| Gigabyte  | H61M-S1                     | [2302b497cc](https://linux-hardware.org/?probe=2302b497cc) | Dec 11, 2019 |
| Intel     | DH67BL AAG10189-208         | [c9400c1fcb](https://linux-hardware.org/?probe=c9400c1fcb) | Dec 11, 2019 |
| Intel     | DH67BL AAG10189-208         | [18d758491c](https://linux-hardware.org/?probe=18d758491c) | Dec 11, 2019 |
| Gigabyte  | H61M-S1                     | [cfbe6b0f33](https://linux-hardware.org/?probe=cfbe6b0f33) | Dec 11, 2019 |
| Gigabyte  | H61M-S1                     | [c5b3e3f258](https://linux-hardware.org/?probe=c5b3e3f258) | Dec 11, 2019 |
| ASUSTek   | ROG STRIX Z390-F GAMING     | [a548b448e7](https://linux-hardware.org/?probe=a548b448e7) | Dec 09, 2019 |
| MSI       | PH67A-C43                   | [35ffc61791](https://linux-hardware.org/?probe=35ffc61791) | Dec 06, 2019 |
| MSI       | PH67A-C43                   | [1a5faa8a98](https://linux-hardware.org/?probe=1a5faa8a98) | Dec 05, 2019 |
| Lenovo    | Board                       | [209a9171b1](https://linux-hardware.org/?probe=209a9171b1) | Dec 04, 2019 |
| ASUSTek   | SABERTOOTH Z77              | [889648300b](https://linux-hardware.org/?probe=889648300b) | Oct 04, 2019 |
| ASUSTek   | SABERTOOTH Z77              | [28d0871f17](https://linux-hardware.org/?probe=28d0871f17) | Oct 02, 2019 |
| ASUSTek   | SABERTOOTH Z77              | [1233b680f5](https://linux-hardware.org/?probe=1233b680f5) | Oct 02, 2019 |
| ASUSTek   | SABERTOOTH Z77              | [22a74597d5](https://linux-hardware.org/?probe=22a74597d5) | Oct 02, 2019 |
| ASUSTek   | SABERTOOTH Z77              | [31f72c0672](https://linux-hardware.org/?probe=31f72c0672) | Oct 02, 2019 |
| Dell      | 048DY8 A00                  | [500dc4f9f5](https://linux-hardware.org/?probe=500dc4f9f5) | Sep 11, 2019 |
| ASRock    | H97M Pro4                   | [168644ddd0](https://linux-hardware.org/?probe=168644ddd0) | Sep 04, 2019 |
| Gigabyte  | H310M S2P                   | [6fffbe0439](https://linux-hardware.org/?probe=6fffbe0439) | Sep 02, 2019 |
| MSI       | Z97A GAMING 6               | [6a9086bf86](https://linux-hardware.org/?probe=6a9086bf86) | Jul 06, 2019 |
| ASUSTek   | PRIME A320M-K               | [0f2ef33214](https://linux-hardware.org/?probe=0f2ef33214) | Jun 27, 2019 |
| Dell      | 09KPNV A00                  | [b1769092a2](https://linux-hardware.org/?probe=b1769092a2) | Jun 22, 2019 |
| Dell      | 01TKCC A01                  | [c133935d4f](https://linux-hardware.org/?probe=c133935d4f) | Jun 19, 2019 |
| ASUSTek   | STRIKER II NSE              | [13d6ead175](https://linux-hardware.org/?probe=13d6ead175) | May 22, 2019 |
| ASRock    | H97M Pro4                   | [410a594809](https://linux-hardware.org/?probe=410a594809) | May 21, 2019 |
| ASUSTek   | ROG Maximus X HERO          | [d7d3d4f56b](https://linux-hardware.org/?probe=d7d3d4f56b) | May 19, 2019 |
| MSI       | B450 TOMAHAWK               | [336d0df071](https://linux-hardware.org/?probe=336d0df071) | May 03, 2019 |
| Intel     | DG35EC AAE29266-205         | [1ddb0e459f](https://linux-hardware.org/?probe=1ddb0e459f) | Apr 26, 2019 |
| Intel     | SHARKBAY                    | [d411643b19](https://linux-hardware.org/?probe=d411643b19) | Apr 23, 2019 |
| Dell      | 01TKCC A01                  | [3cfa230457](https://linux-hardware.org/?probe=3cfa230457) | Apr 12, 2019 |
| Dell      | 01TKCC A01                  | [94e2e60839](https://linux-hardware.org/?probe=94e2e60839) | Apr 11, 2019 |
| MSI       | Z87M-G43                    | [cbb0c4be39](https://linux-hardware.org/?probe=cbb0c4be39) | Apr 11, 2019 |
| MSI       | Z87M-G43                    | [6fb3422b8b](https://linux-hardware.org/?probe=6fb3422b8b) | Apr 11, 2019 |
| Gigabyte  | G31M-ES2L                   | [2344aec798](https://linux-hardware.org/?probe=2344aec798) | Apr 04, 2019 |
| HP        | 158A                        | [61be039d0f](https://linux-hardware.org/?probe=61be039d0f) | Apr 02, 2019 |
| Intel     | DH55HC AAE70933-502         | [8f109c807c](https://linux-hardware.org/?probe=8f109c807c) | Feb 15, 2019 |
| Intel     | DH55HC AAE70933-502         | [be7548c062](https://linux-hardware.org/?probe=be7548c062) | Feb 15, 2019 |
| Wibtek    | H61-M HDMI2                 | [6f082a4f2d](https://linux-hardware.org/?probe=6f082a4f2d) | Feb 12, 2019 |
| Wibtek    | H61-M HDMI2                 | [3a44341e10](https://linux-hardware.org/?probe=3a44341e10) | Feb 12, 2019 |
| ECS       | H61H2-M2                    | [ed1e345718](https://linux-hardware.org/?probe=ed1e345718) | Feb 02, 2019 |
| ECS       | H61H2-M2                    | [554a16077e](https://linux-hardware.org/?probe=554a16077e) | Feb 01, 2019 |
| Gigabyte  | G31M-ES2L                   | [d69a897cf8](https://linux-hardware.org/?probe=d69a897cf8) | Jan 07, 2019 |
| Gigabyte  | G31M-ES2L                   | [75827661a7](https://linux-hardware.org/?probe=75827661a7) | Jan 07, 2019 |
| Gigabyte  | G31M-ES2L                   | [8531feefb2](https://linux-hardware.org/?probe=8531feefb2) | Jan 07, 2019 |
| Gigabyte  | A320M-S2H-CF                | [a72d5458ff](https://linux-hardware.org/?probe=a72d5458ff) | Nov 23, 2018 |
| Gigabyte  | B85M-D3H                    | [d206454b5f](https://linux-hardware.org/?probe=d206454b5f) | Aug 27, 2018 |
| ASUSTek   | P5GD1 PRO                   | [7f52004043](https://linux-hardware.org/?probe=7f52004043) | Aug 02, 2018 |
| ECS       | H61H2-M2                    | [765806fe73](https://linux-hardware.org/?probe=765806fe73) | Jun 01, 2018 |
| Gigabyte  | GA-990FXA-UD3               | [2e67236dbb](https://linux-hardware.org/?probe=2e67236dbb) | Feb 23, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Elementary 6.1   | 101      | 33.22%  |
| Elementary 6     | 68       | 22.37%  |
| Elementary 5.1.7 | 62       | 20.39%  |
| Elementary 5.1   | 17       | 5.59%   |
| Elementary 5.0   | 16       | 5.26%   |
| Elementary 5.1.2 | 10       | 3.29%   |
| Elementary 5.1.4 | 7        | 2.3%    |
| Elementary 5.1.3 | 7        | 2.3%    |
| Elementary 5.1.6 | 6        | 1.97%   |
| Elementary 0.4.1 | 6        | 1.97%   |
| Elementary 6.0   | 2        | 0.66%   |
| Elementary 5.1.5 | 2        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Elementary | 284      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.11.0-43-generic  | 24       | 7.16%   |
| 5.11.0-41-generic  | 20       | 5.97%   |
| 5.11.0-40-generic  | 17       | 5.07%   |
| 5.13.0-39-generic  | 16       | 4.78%   |
| 5.13.0-28-generic  | 16       | 4.78%   |
| 5.0.0-37-generic   | 11       | 3.28%   |
| 5.13.0-30-generic  | 10       | 2.99%   |
| 5.11.0-27-generic  | 10       | 2.99%   |
| 5.4.0-42-generic   | 9        | 2.69%   |
| 5.13.0-27-generic  | 9        | 2.69%   |
| 5.4.0-48-generic   | 8        | 2.39%   |
| 5.13.0-35-generic  | 7        | 2.09%   |
| 5.11.0-37-generic  | 7        | 2.09%   |
| 5.4.0-65-generic   | 6        | 1.79%   |
| 5.4.0-54-generic   | 6        | 1.79%   |
| 5.13.0-40-generic  | 6        | 1.79%   |
| 5.11.0-25-generic  | 6        | 1.79%   |
| 5.4.0-58-generic   | 5        | 1.49%   |
| 5.3.0-46-generic   | 5        | 1.49%   |
| 5.3.0-40-generic   | 5        | 1.49%   |
| 5.13.0-37-generic  | 5        | 1.49%   |
| 5.11.0-38-generic  | 5        | 1.49%   |
| 5.11.0-44-generic  | 4        | 1.19%   |
| 5.8.0-50-generic   | 3        | 0.9%    |
| 5.4.0-56-generic   | 3        | 0.9%    |
| 5.4.0-52-generic   | 3        | 0.9%    |
| 5.4.0-47-generic   | 3        | 0.9%    |
| 5.3.0-53-generic   | 3        | 0.9%    |
| 5.3.0-28-generic   | 3        | 0.9%    |
| 4.15.0-51-generic  | 3        | 0.9%    |
| 4.15.0-47-generic  | 3        | 0.9%    |
| 5.4.0-90-generic   | 2        | 0.6%    |
| 5.4.0-80-generic   | 2        | 0.6%    |
| 5.4.0-71-generic   | 2        | 0.6%    |
| 5.4.0-70-generic   | 2        | 0.6%    |
| 5.4.0-60-generic   | 2        | 0.6%    |
| 5.4.0-53-generic   | 2        | 0.6%    |
| 5.3.0-62-generic   | 2        | 0.6%    |
| 5.3.0-51-generic   | 2        | 0.6%    |
| 5.3.0-45-generic   | 2        | 0.6%    |
| 5.3.0-42-generic   | 2        | 0.6%    |
| 5.3.0-26-generic   | 2        | 0.6%    |
| 5.13.0-25-generic  | 2        | 0.6%    |
| 5.11.0-46-generic  | 2        | 0.6%    |
| 5.11.0-36-generic  | 2        | 0.6%    |
| 5.11.0-34-generic  | 2        | 0.6%    |
| 4.15.0-96-generic  | 2        | 0.6%    |
| 4.15.0-45-generic  | 2        | 0.6%    |
| 4.15.0-161-generic | 2        | 0.6%    |
| 4.15.0-128-generic | 2        | 0.6%    |
| 4.15.0-112-generic | 2        | 0.6%    |
| 5.8.0-63-generic   | 1        | 0.3%    |
| 5.8.0-55-generic   | 1        | 0.3%    |
| 5.4.0-94-generic   | 1        | 0.3%    |
| 5.4.0-91-generic   | 1        | 0.3%    |
| 5.4.0-84-generic   | 1        | 0.3%    |
| 5.4.0-77-generic   | 1        | 0.3%    |
| 5.4.0-74-generic   | 1        | 0.3%    |
| 5.4.0-73-generic   | 1        | 0.3%    |
| 5.4.0-67-generic   | 1        | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 94       | 31.76%  |
| 5.13.0  | 67       | 22.64%  |
| 5.4.0   | 59       | 19.93%  |
| 5.3.0   | 24       | 8.11%   |
| 4.15.0  | 22       | 7.43%   |
| 5.0.0   | 14       | 4.73%   |
| 5.8.0   | 5        | 1.69%   |
| 4.18.0  | 3        | 1.01%   |
| 4.4.0   | 2        | 0.68%   |
| 5.2.11  | 1        | 0.34%   |
| 5.17.0  | 1        | 0.34%   |
| 5.15.12 | 1        | 0.34%   |
| 5.15.1  | 1        | 0.34%   |
| 5.0.11  | 1        | 0.34%   |
| 4.10.0  | 1        | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 94       | 31.76%  |
| 5.13    | 67       | 22.64%  |
| 5.4     | 59       | 19.93%  |
| 5.3     | 24       | 8.11%   |
| 4.15    | 22       | 7.43%   |
| 5.0     | 15       | 5.07%   |
| 5.8     | 5        | 1.69%   |
| 4.18    | 3        | 1.01%   |
| 5.15    | 2        | 0.68%   |
| 4.4     | 2        | 0.68%   |
| 5.2     | 1        | 0.34%   |
| 5.17    | 1        | 0.34%   |
| 4.10    | 1        | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 284      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 261      | 90%     |
| Unknown  | 26       | 8.97%   |
| GNOME    | 2        | 0.69%   |
| MATE     | 1        | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 283      | 99.65%  |
| Unknown | 1        | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 240      | 83.04%  |
| LightDM | 32       | 11.07%  |
| TDM     | 15       | 5.19%   |
| SDDM    | 1        | 0.35%   |
| GDM     | 1        | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 109      | 37.59%  |
| de_DE   | 31       | 10.69%  |
| Unknown | 23       | 7.93%   |
| es_ES   | 22       | 7.59%   |
| en_GB   | 16       | 5.52%   |
| ru_RU   | 10       | 3.45%   |
| fr_FR   | 10       | 3.45%   |
| pt_BR   | 9        | 3.1%    |
| en_CA   | 7        | 2.41%   |
| pl_PL   | 6        | 2.07%   |
| it_IT   | 6        | 2.07%   |
| tr_TR   | 5        | 1.72%   |
| es_MX   | 3        | 1.03%   |
| en_AU   | 3        | 1.03%   |
| pt_PT   | 2        | 0.69%   |
| ja_JP   | 2        | 0.69%   |
| en_IN   | 2        | 0.69%   |
| de_CH   | 2        | 0.69%   |
| zh_CN   | 1        | 0.34%   |
| uk_UA   | 1        | 0.34%   |
| sv_SE   | 1        | 0.34%   |
| sr_RS   | 1        | 0.34%   |
| nl_NL   | 1        | 0.34%   |
| hu_HU   | 1        | 0.34%   |
| gl_ES   | 1        | 0.34%   |
| fr_CA   | 1        | 0.34%   |
| fr_BE   | 1        | 0.34%   |
| fi_FI   | 1        | 0.34%   |
| es_VE   | 1        | 0.34%   |
| es_SV   | 1        | 0.34%   |
| es_PA   | 1        | 0.34%   |
| es_EC   | 1        | 0.34%   |
| en_PH   | 1        | 0.34%   |
| en_IE   | 1        | 0.34%   |
| en_HK   | 1        | 0.34%   |
| el_GR   | 1        | 0.34%   |
| de_AT   | 1        | 0.34%   |
| cs_CZ   | 1        | 0.34%   |
| ca_ES   | 1        | 0.34%   |
| ar_EG   | 1        | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 146      | 50.69%  |
| BIOS | 142      | 49.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 269      | 93.4%   |
| Btrfs   | 10       | 3.47%   |
| Unknown | 6        | 2.08%   |
| Xfs     | 3        | 1.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 252      | 87.8%   |
| GPT     | 21       | 7.32%   |
| MBR     | 14       | 4.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 262      | 92.25%  |
| Yes       | 22       | 7.75%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 237      | 83.16%  |
| Yes       | 48       | 16.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 75       | 26.41%  |
| Gigabyte Technology | 51       | 17.96%  |
| MSI                 | 35       | 12.32%  |
| Hewlett-Packard     | 25       | 8.8%    |
| ASRock              | 25       | 8.8%    |
| Dell                | 18       | 6.34%   |
| Intel               | 10       | 3.52%   |
| Biostar             | 8        | 2.82%   |
| Lenovo              | 5        | 1.76%   |
| Acer                | 5        | 1.76%   |
| Pegatron            | 3        | 1.06%   |
| Foxconn             | 3        | 1.06%   |
| ECS                 | 3        | 1.06%   |
| Apple               | 3        | 1.06%   |
| Wibtek              | 2        | 0.7%    |
| Unknown             | 2        | 0.7%    |
| SYS                 | 1        | 0.35%   |
| Shuttle             | 1        | 0.35%   |
| Inventec            | 1        | 0.35%   |
| Fujitsu             | 1        | 0.35%   |
| FIRICH              | 1        | 0.35%   |
| EVGA                | 1        | 0.35%   |
| eMachines           | 1        | 0.35%   |
| Chuwi               | 1        | 0.35%   |
| AZW                 | 1        | 0.35%   |
| AOpen               | 1        | 0.35%   |
| AMI                 | 1        | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS All Series                         | 7        | 2.46%   |
| ASUS P8H61-M LX3 R2.0                   | 4        | 1.41%   |
| MSI MS-7C02                             | 3        | 1.06%   |
| ASUS PRIME A320M-K                      | 3        | 1.06%   |
| Wibtek H61-M HDMI2                      | 2        | 0.7%    |
| Pegatron IPMH61P1                       | 2        | 0.7%    |
| MSI MS-7B86                             | 2        | 0.7%    |
| MSI MS-7721                             | 2        | 0.7%    |
| Intel H61                               | 2        | 0.7%    |
| Gigabyte Z390 UD                        | 2        | 0.7%    |
| Gigabyte H61M-DS2                       | 2        | 0.7%    |
| ECS H55H-M                              | 2        | 0.7%    |
| Dell OptiPlex 9010                      | 2        | 0.7%    |
| ASUS TUF GAMING B550M-PLUS              | 2        | 0.7%    |
| ASUS ROG STRIX B350-F GAMING            | 2        | 0.7%    |
| ASRock B450M-HDV R4.0                   | 2        | 0.7%    |
| Unknown                                 | 2        | 0.7%    |
| SYS H310CH5-TI2                         | 1        | 0.35%   |
| Shuttle DS61                            | 1        | 0.35%   |
| Pegatron KJ379AA-ABA a6400f             | 1        | 0.35%   |
| MSI PPPPP-CCC#MMMMMMMM                  | 1        | 0.35%   |
| MSI P35 Platinum(MS-7345)               | 1        | 0.35%   |
| MSI MS-7C94                             | 1        | 0.35%   |
| MSI MS-7C91                             | 1        | 0.35%   |
| MSI MS-7C83                             | 1        | 0.35%   |
| MSI MS-7C52                             | 1        | 0.35%   |
| MSI MS-7C35                             | 1        | 0.35%   |
| MSI MS-7B84                             | 1        | 0.35%   |
| MSI MS-7B79                             | 1        | 0.35%   |
| MSI MS-7B46                             | 1        | 0.35%   |
| MSI MS-7B38                             | 1        | 0.35%   |
| MSI MS-7B17                             | 1        | 0.35%   |
| MSI MS-7A59                             | 1        | 0.35%   |
| MSI MS-7A40                             | 1        | 0.35%   |
| MSI MS-7A38                             | 1        | 0.35%   |
| MSI MS-7996                             | 1        | 0.35%   |
| MSI MS-7971                             | 1        | 0.35%   |
| MSI MS-7918                             | 1        | 0.35%   |
| MSI MS-7917                             | 1        | 0.35%   |
| MSI MS-7885                             | 1        | 0.35%   |
| MSI MS-7851                             | 1        | 0.35%   |
| MSI MS-7823                             | 1        | 0.35%   |
| MSI MS-7817                             | 1        | 0.35%   |
| MSI MS-7788                             | 1        | 0.35%   |
| MSI MS-7693                             | 1        | 0.35%   |
| MSI MS-7673                             | 1        | 0.35%   |
| MSI MS-7597                             | 1        | 0.35%   |
| MSI Elite 7100 Microtower PC            | 1        | 0.35%   |
| Lenovo ThinkCentre M92p 3227D13         | 1        | 0.35%   |
| Lenovo ThinkCentre M72e 3664AD7         | 1        | 0.35%   |
| Lenovo ThinkCentre M58 6258D3G          | 1        | 0.35%   |
| Lenovo ThinkCentre M55E 9632BU8         | 1        | 0.35%   |
| Lenovo IdeaCentre 510S-07ICK 90LX006TGE | 1        | 0.35%   |
| Inventec D CLASS                        | 1        | 0.35%   |
| Intel X79                               | 1        | 0.35%   |
| Intel X64                               | 1        | 0.35%   |
| Intel SHARKBAY                          | 1        | 0.35%   |
| Intel DH67BL AAG10189-208               | 1        | 0.35%   |
| Intel DH61BE AAG14062-210               | 1        | 0.35%   |
| Intel DH55HC AAE70933-502               | 1        | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 13       | 4.58%   |
| Dell OptiPlex          | 12       | 4.23%   |
| ASUS ROG               | 11       | 3.87%   |
| ASUS TUF               | 9        | 3.17%   |
| ASUS All               | 7        | 2.46%   |
| HP Compaq              | 6        | 2.11%   |
| Gigabyte Z390          | 5        | 1.76%   |
| Lenovo ThinkCentre     | 4        | 1.41%   |
| Dell Precision         | 4        | 1.41%   |
| ASUS P8H61-M           | 4        | 1.41%   |
| MSI MS-7C02            | 3        | 1.06%   |
| HP ProDesk             | 3        | 1.06%   |
| Gigabyte X570          | 3        | 1.06%   |
| ASUS M5A78L-M          | 3        | 1.06%   |
| Acer Aspire            | 3        | 1.06%   |
| Wibtek H61-M           | 2        | 0.7%    |
| Pegatron IPMH61P1      | 2        | 0.7%    |
| MSI MS-7B86            | 2        | 0.7%    |
| MSI MS-7721            | 2        | 0.7%    |
| Intel H61              | 2        | 0.7%    |
| HP Pavilion            | 2        | 0.7%    |
| Gigabyte H61M-DS2      | 2        | 0.7%    |
| Gigabyte H310M         | 2        | 0.7%    |
| Gigabyte B450M         | 2        | 0.7%    |
| Gigabyte B450          | 2        | 0.7%    |
| Gigabyte A320M-S2H     | 2        | 0.7%    |
| ECS H55H-M             | 2        | 0.7%    |
| ASUS STRIKER           | 2        | 0.7%    |
| ASUS SABERTOOTH        | 2        | 0.7%    |
| ASUS P8Z77-V           | 2        | 0.7%    |
| ASRock B450M-HDV       | 2        | 0.7%    |
| Unknown                | 2        | 0.7%    |
| SYS H310CH5-TI2        | 1        | 0.35%   |
| Shuttle DS61           | 1        | 0.35%   |
| Pegatron KJ379AA-ABA   | 1        | 0.35%   |
| MSI PPPPP-CCC#MMMMMMMM | 1        | 0.35%   |
| MSI P35                | 1        | 0.35%   |
| MSI MS-7C94            | 1        | 0.35%   |
| MSI MS-7C91            | 1        | 0.35%   |
| MSI MS-7C83            | 1        | 0.35%   |
| MSI MS-7C52            | 1        | 0.35%   |
| MSI MS-7C35            | 1        | 0.35%   |
| MSI MS-7B84            | 1        | 0.35%   |
| MSI MS-7B79            | 1        | 0.35%   |
| MSI MS-7B46            | 1        | 0.35%   |
| MSI MS-7B38            | 1        | 0.35%   |
| MSI MS-7B17            | 1        | 0.35%   |
| MSI MS-7A59            | 1        | 0.35%   |
| MSI MS-7A40            | 1        | 0.35%   |
| MSI MS-7A38            | 1        | 0.35%   |
| MSI MS-7996            | 1        | 0.35%   |
| MSI MS-7971            | 1        | 0.35%   |
| MSI MS-7918            | 1        | 0.35%   |
| MSI MS-7917            | 1        | 0.35%   |
| MSI MS-7885            | 1        | 0.35%   |
| MSI MS-7851            | 1        | 0.35%   |
| MSI MS-7823            | 1        | 0.35%   |
| MSI MS-7817            | 1        | 0.35%   |
| MSI MS-7788            | 1        | 0.35%   |
| MSI MS-7693            | 1        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 37       | 13.03%  |
| 2018 | 35       | 12.32%  |
| 2013 | 29       | 10.21%  |
| 2011 | 26       | 9.15%   |
| 2019 | 25       | 8.8%    |
| 2010 | 19       | 6.69%   |
| 2017 | 18       | 6.34%   |
| 2020 | 16       | 5.63%   |
| 2015 | 15       | 5.28%   |
| 2014 | 15       | 5.28%   |
| 2016 | 11       | 3.87%   |
| 2008 | 11       | 3.87%   |
| 2021 | 10       | 3.52%   |
| 2009 | 10       | 3.52%   |
| 2007 | 4        | 1.41%   |
| 2022 | 1        | 0.35%   |
| 2006 | 1        | 0.35%   |
| 2005 | 1        | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 284      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 273      | 96.13%  |
| Enabled  | 11       | 3.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 284      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 67       | 23.51%  |
| 8.01-16.0   | 60       | 21.05%  |
| 4.01-8.0    | 54       | 18.95%  |
| 32.01-64.0  | 49       | 17.19%  |
| 3.01-4.0    | 35       | 12.28%  |
| 64.01-256.0 | 7        | 2.46%   |
| 24.01-32.0  | 5        | 1.75%   |
| 1.01-2.0    | 5        | 1.75%   |
| 2.01-3.0    | 3        | 1.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 119      | 37.3%   |
| 2.01-3.0   | 93       | 29.15%  |
| 4.01-8.0   | 46       | 14.42%  |
| 3.01-4.0   | 46       | 14.42%  |
| 8.01-16.0  | 8        | 2.51%   |
| 0.51-1.0   | 6        | 1.88%   |
| 32.01-64.0 | 1        | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 106      | 36.18%  |
| 2      | 105      | 35.84%  |
| 3      | 36       | 12.29%  |
| 4      | 23       | 7.85%   |
| 5      | 13       | 4.44%   |
| 7      | 4        | 1.37%   |
| 6      | 4        | 1.37%   |
| 8      | 1        | 0.34%   |
| 0      | 1        | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 167      | 57.59%  |
| Yes       | 123      | 42.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 280      | 98.59%  |
| No        | 4        | 1.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 148      | 51.57%  |
| Yes       | 139      | 48.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 192      | 67.13%  |
| Yes       | 94       | 32.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 30       | 10.53%  |
| USA          | 28       | 9.82%   |
| Brazil       | 20       | 7.02%   |
| UK           | 19       | 6.67%   |
| Spain        | 16       | 5.61%   |
| Russia       | 14       | 4.91%   |
| Canada       | 13       | 4.56%   |
| France       | 10       | 3.51%   |
| Poland       | 8        | 2.81%   |
| Mexico       | 8        | 2.81%   |
| Indonesia    | 8        | 2.81%   |
| Italy        | 7        | 2.46%   |
| India        | 7        | 2.46%   |
| Turkey       | 6        | 2.11%   |
| Argentina    | 6        | 2.11%   |
| Austria      | 5        | 1.75%   |
| Australia    | 5        | 1.75%   |
| Sweden       | 4        | 1.4%    |
| Netherlands  | 4        | 1.4%    |
| Egypt        | 4        | 1.4%    |
| Ukraine      | 3        | 1.05%   |
| Malaysia     | 3        | 1.05%   |
| Japan        | 3        | 1.05%   |
| Greece       | 3        | 1.05%   |
| Finland      | 3        | 1.05%   |
| Czechia      | 3        | 1.05%   |
| Bulgaria     | 3        | 1.05%   |
| Venezuela    | 2        | 0.7%    |
| Switzerland  | 2        | 0.7%    |
| Romania      | 2        | 0.7%    |
| Philippines  | 2        | 0.7%    |
| Iran         | 2        | 0.7%    |
| Hong Kong    | 2        | 0.7%    |
| Costa Rica   | 2        | 0.7%    |
| Belgium      | 2        | 0.7%    |
| Vietnam      | 1        | 0.35%   |
| Thailand     | 1        | 0.35%   |
| Sri Lanka    | 1        | 0.35%   |
| South Africa | 1        | 0.35%   |
| Sint Maarten | 1        | 0.35%   |
| Serbia       | 1        | 0.35%   |
| Portugal     | 1        | 0.35%   |
| Panama       | 1        | 0.35%   |
| Norway       | 1        | 0.35%   |
| New Zealand  | 1        | 0.35%   |
| Luxembourg   | 1        | 0.35%   |
| Lithuania    | 1        | 0.35%   |
| Kosovo       | 1        | 0.35%   |
| Kenya        | 1        | 0.35%   |
| Ireland      | 1        | 0.35%   |
| Hungary      | 1        | 0.35%   |
| Estonia      | 1        | 0.35%   |
| El Salvador  | 1        | 0.35%   |
| Ecuador      | 1        | 0.35%   |
| Denmark      | 1        | 0.35%   |
| Colombia     | 1        | 0.35%   |
| China        | 1        | 0.35%   |
| Chile        | 1        | 0.35%   |
| Belarus      | 1        | 0.35%   |
| Bangladesh   | 1        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Fortaleza                 | 4        | 1.32%   |
| Berlin                    | 4        | 1.32%   |
| Warsaw                    | 3        | 0.99%   |
| Vienna                    | 3        | 0.99%   |
| Sofia                     | 3        | 0.99%   |
| Rio de Janeiro            | 3        | 0.99%   |
| Paris                     | 3        | 0.99%   |
| Montreal                  | 3        | 0.99%   |
| Hamburg                   | 3        | 0.99%   |
| Brisbane                  | 3        | 0.99%   |
| Sao Paulo                 | 2        | 0.66%   |
| Novosibirsk               | 2        | 0.66%   |
| Moscow                    | 2        | 0.66%   |
| Morelia                   | 2        | 0.66%   |
| Montenegro                | 2        | 0.66%   |
| Milan                     | 2        | 0.66%   |
| Mexico City               | 2        | 0.66%   |
| Istanbul                  | 2        | 0.66%   |
| Giza                      | 2        | 0.66%   |
| Central                   | 2        | 0.66%   |
| Caracas                   | 2        | 0.66%   |
| Cairo                     | 2        | 0.66%   |
| Znojmo                    | 1        | 0.33%   |
| Zabrze                    | 1        | 0.33%   |
| Yokohama                  | 1        | 0.33%   |
| Xicheng District          | 1        | 0.33%   |
| Wroclaw                   | 1        | 0.33%   |
| Wriezen                   | 1        | 0.33%   |
| Woolloongabba             | 1        | 0.33%   |
| Wolgast                   | 1        | 0.33%   |
| Wigan                     | 1        | 0.33%   |
| Whiting Bay               | 1        | 0.33%   |
| Wattala                   | 1        | 0.33%   |
| VitÃ³ria                | 1        | 0.33%   |
| Vinhedo                   | 1        | 0.33%   |
| Vilvoorde                 | 1        | 0.33%   |
| Villahermosa              | 1        | 0.33%   |
| Vilanova i la GeltrÃº   | 1        | 0.33%   |
| Vantaa                    | 1        | 0.33%   |
| Vanse                     | 1        | 0.33%   |
| Vannes                    | 1        | 0.33%   |
| Vancouver                 | 1        | 0.33%   |
| Vaenersborg               | 1        | 0.33%   |
| Uppsala                   | 1        | 0.33%   |
| Ullastrell                | 1        | 0.33%   |
| Tucson                    | 1        | 0.33%   |
| Tseung Kwan O             | 1        | 0.33%   |
| Trivandrum                | 1        | 0.33%   |
| Tournus                   | 1        | 0.33%   |
| Toronto                   | 1        | 0.33%   |
| Tolyatti                  | 1        | 0.33%   |
| Toluca                    | 1        | 0.33%   |
| Thrissur                  | 1        | 0.33%   |
| Thessaloniki              | 1        | 0.33%   |
| Tehran                    | 1        | 0.33%   |
| Tangerang                 | 1        | 0.33%   |
| Tampere                   | 1        | 0.33%   |
| Tallinn                   | 1        | 0.33%   |
| SГЈo JosГ© dos Campos | 1        | 0.33%   |
| Sydney                    | 1        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 94       | 134    | 18.29%  |
| WDC                       | 92       | 134    | 17.9%   |
| Samsung Electronics       | 75       | 124    | 14.59%  |
| Kingston                  | 46       | 68     | 8.95%   |
| SanDisk                   | 26       | 29     | 5.06%   |
| Crucial                   | 26       | 34     | 5.06%   |
| Toshiba                   | 25       | 45     | 4.86%   |
| Hitachi                   | 15       | 16     | 2.92%   |
| Unknown                   | 10       | 19     | 1.95%   |
| Intel                     | 10       | 10     | 1.95%   |
| A-DATA Technology         | 9        | 10     | 1.75%   |
| Phison                    | 5        | 6      | 0.97%   |
| OCZ                       | 5        | 7      | 0.97%   |
| Micron/Crucial Technology | 5        | 9      | 0.97%   |
| Transcend                 | 4        | 4      | 0.78%   |
| PNY                       | 4        | 7      | 0.78%   |
| Micron Technology         | 4        | 4      | 0.78%   |
| HGST                      | 4        | 8      | 0.78%   |
| Corsair                   | 4        | 4      | 0.78%   |
| China                     | 4        | 4      | 0.78%   |
| Team                      | 3        | 3      | 0.58%   |
| PLEXTOR                   | 3        | 3      | 0.58%   |
| Patriot                   | 3        | 3      | 0.58%   |
| MAXTOR                    | 3        | 3      | 0.58%   |
| Intenso                   | 3        | 3      | 0.58%   |
| ASMT                      | 3        | 3      | 0.58%   |
| LITEON                    | 2        | 2      | 0.39%   |
| GOODRAM                   | 2        | 6      | 0.39%   |
| Gigabyte Technology       | 2        | 2      | 0.39%   |
| XPG                       | 1        | 1      | 0.19%   |
| WDC WDS                   | 1        | 1      | 0.19%   |
| USB3.1                    | 1        | 1      | 0.19%   |
| SPCC                      | 1        | 1      | 0.19%   |
| SK Hynix                  | 1        | 1      | 0.19%   |
| ROG                       | 1        | 1      | 0.19%   |
| Realtek Semiconductor     | 1        | 1      | 0.19%   |
| OWC                       | 1        | 1      | 0.19%   |
| OCZ-VERTEX3               | 1        | 1      | 0.19%   |
| OCZ-VERTEX2               | 1        | 1      | 0.19%   |
| Netac                     | 1        | 1      | 0.19%   |
| MidasForce                | 1        | 1      | 0.19%   |
| Leven                     | 1        | 1      | 0.19%   |
| KingSpec                  | 1        | 1      | 0.19%   |
| Kingmax                   | 1        | 1      | 0.19%   |
| JMicron                   | 1        | 1      | 0.19%   |
| HS-SSD-C100               | 1        | 1      | 0.19%   |
| Hikvision                 | 1        | 1      | 0.19%   |
| Hewlett-Packard           | 1        | 1      | 0.19%   |
| GeIL                      | 1        | 1      | 0.19%   |
| GALAX                     | 1        | 1      | 0.19%   |
| Apple                     | 1        | 1      | 0.19%   |
| Apacer                    | 1        | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD   | 14       | 2.38%   |
| Samsung NVMe SSD Drive 500GB      | 11       | 1.87%   |
| Samsung SSD 850 EVO 250GB         | 9        | 1.53%   |
| WDC WD10EZEX-08WN4A0 1TB          | 8        | 1.36%   |
| Kingston SA400S37120G 120GB SSD   | 8        | 1.36%   |
| Samsung NVMe SSD Drive 1TB        | 7        | 1.19%   |
| Kingston SV300S37A120G 120GB SSD  | 7        | 1.19%   |
| Toshiba DT01ACA050 500GB          | 6        | 1.02%   |
| Toshiba DT01ACA100 1TB            | 5        | 0.85%   |
| Seagate ST500DM002-1BD142 500GB   | 5        | 0.85%   |
| Seagate ST3500418AS 500GB         | 5        | 0.85%   |
| Seagate ST1000DM010-2EP102 1TB    | 5        | 0.85%   |
| Seagate ST1000DM003-1ER162 1TB    | 5        | 0.85%   |
| Samsung SSD 860 EVO 250GB         | 5        | 0.85%   |
| Samsung SSD 860 EVO 1TB           | 5        | 0.85%   |
| Crucial CT240BX500SSD1 240GB      | 5        | 0.85%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 4        | 0.68%   |
| Seagate ST3500312CS 500GB         | 4        | 0.68%   |
| Seagate ST31000528AS 1TB          | 4        | 0.68%   |
| SanDisk SSD PLUS 480GB            | 4        | 0.68%   |
| Sandisk NVMe SSD Drive 500GB      | 4        | 0.68%   |
| Samsung SSD 860 EVO 500GB         | 4        | 0.68%   |
| Samsung SSD 850 EVO 500GB         | 4        | 0.68%   |
| Samsung SSD 840 EVO 120GB         | 4        | 0.68%   |
| Micron/Crucial NVMe SSD Drive 1TB | 4        | 0.68%   |
| WDC WD5000AAKX-001CA0 500GB       | 3        | 0.51%   |
| WDC WD5000AAKS-00A7B2 500GB       | 3        | 0.51%   |
| WDC WD10EZEX-00BN5A0 1TB          | 3        | 0.51%   |
| Unknown SD/MMC 16GB               | 3        | 0.51%   |
| Unknown M.S./M.S.Pro/HG 16GB      | 3        | 0.51%   |
| Toshiba HDWD110 1TB               | 3        | 0.51%   |
| Seagate ST3250310AS 250GB         | 3        | 0.51%   |
| Seagate ST2000DM008-2FR102 2TB    | 3        | 0.51%   |
| Seagate ST2000DM001-1CH164 2TB    | 3        | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB    | 3        | 0.51%   |
| SanDisk SSD PLUS 240GB            | 3        | 0.51%   |
| Samsung SSD 870 QVO 1TB           | 3        | 0.51%   |
| Samsung SSD 850 PRO 256GB         | 3        | 0.51%   |
| Samsung SSD 840 EVO 500GB         | 3        | 0.51%   |
| Samsung SSD 840 EVO 250GB         | 3        | 0.51%   |
| Samsung NVMe SSD Drive 256GB      | 3        | 0.51%   |
| Phison NVMe SSD Drive 1TB         | 3        | 0.51%   |
| Kingston SA400S37480G 480GB SSD   | 3        | 0.51%   |
| Kingston NVMe SSD Drive 1TB       | 3        | 0.51%   |
| Intel NVMe SSD Drive 512GB        | 3        | 0.51%   |
| Crucial CT240BX200SSD1 240GB      | 3        | 0.51%   |
| Crucial CT120BX300SSD1 120GB      | 3        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB       | 3        | 0.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 2        | 0.34%   |
| WDC WD5000AAKX-003CA0 500GB       | 2        | 0.34%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 2        | 0.34%   |
| WDC WD40EFRX-68N32N0 4TB          | 2        | 0.34%   |
| WDC WD20EARX-00PASB0 2TB          | 2        | 0.34%   |
| WDC WD10EZEX-60WN4A0 1TB          | 2        | 0.34%   |
| WDC WD10EZEX-22MFCA0 1TB          | 2        | 0.34%   |
| WDC WD10EZEX-08M2NA0 1TB          | 2        | 0.34%   |
| WDC WD10EURX-63UY4Y0 1TB          | 2        | 0.34%   |
| Unknown SD/MMC/MS PRO 16GB        | 2        | 0.34%   |
| Toshiba DT01ACA300 3TB            | 2        | 0.34%   |
| Seagate ST3160815AS 160GB         | 2        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 91       | 129    | 38.56%  |
| WDC                 | 80       | 111    | 33.9%   |
| Toshiba             | 24       | 44     | 10.17%  |
| Hitachi             | 15       | 16     | 6.36%   |
| Samsung Electronics | 14       | 16     | 5.93%   |
| HGST                | 4        | 8      | 1.69%   |
| Unknown             | 2        | 3      | 0.85%   |
| MAXTOR              | 2        | 2      | 0.85%   |
| ASMT                | 2        | 2      | 0.85%   |
| Hewlett-Packard     | 1        | 1      | 0.42%   |
| Apple               | 1        | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 49       | 70     | 22.17%  |
| Kingston            | 41       | 51     | 18.55%  |
| Crucial             | 26       | 34     | 11.76%  |
| SanDisk             | 20       | 21     | 9.05%   |
| WDC                 | 13       | 20     | 5.88%   |
| A-DATA Technology   | 8        | 9      | 3.62%   |
| OCZ                 | 5        | 7      | 2.26%   |
| Intel               | 5        | 5      | 2.26%   |
| Transcend           | 4        | 4      | 1.81%   |
| PNY                 | 4        | 7      | 1.81%   |
| Corsair             | 4        | 4      | 1.81%   |
| China               | 4        | 4      | 1.81%   |
| Team                | 3        | 3      | 1.36%   |
| PLEXTOR             | 3        | 3      | 1.36%   |
| Patriot             | 3        | 3      | 1.36%   |
| Intenso             | 3        | 3      | 1.36%   |
| Micron Technology   | 2        | 2      | 0.9%    |
| LITEON              | 2        | 2      | 0.9%    |
| GOODRAM             | 2        | 6      | 0.9%    |
| WDC WDS             | 1        | 1      | 0.45%   |
| Toshiba             | 1        | 1      | 0.45%   |
| SPCC                | 1        | 1      | 0.45%   |
| SK Hynix            | 1        | 1      | 0.45%   |
| Seagate             | 1        | 1      | 0.45%   |
| ROG                 | 1        | 1      | 0.45%   |
| OWC                 | 1        | 1      | 0.45%   |
| OCZ-VERTEX3         | 1        | 1      | 0.45%   |
| OCZ-VERTEX2         | 1        | 1      | 0.45%   |
| MidasForce          | 1        | 1      | 0.45%   |
| MAXTOR              | 1        | 1      | 0.45%   |
| Leven               | 1        | 1      | 0.45%   |
| KingSpec            | 1        | 1      | 0.45%   |
| Kingmax             | 1        | 1      | 0.45%   |
| HS-SSD-C100         | 1        | 1      | 0.45%   |
| Hikvision           | 1        | 1      | 0.45%   |
| Gigabyte Technology | 1        | 1      | 0.45%   |
| GeIL                | 1        | 1      | 0.45%   |
| GALAX               | 1        | 1      | 0.45%   |
| Apacer              | 1        | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 189      | 333    | 43.15%  |
| SSD     | 178      | 278    | 40.64%  |
| NVMe    | 58       | 95     | 13.24%  |
| Unknown | 10       | 18     | 2.28%   |
| MMC     | 3        | 3      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 267      | 598    | 76.95%  |
| NVMe | 58       | 95     | 16.71%  |
| SAS  | 19       | 31     | 5.48%   |
| MMC  | 3        | 3      | 0.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 220      | 387    | 59.14%  |
| 0.51-1.0   | 98       | 146    | 26.34%  |
| 1.01-2.0   | 23       | 32     | 6.18%   |
| 2.01-3.0   | 12       | 24     | 3.23%   |
| 3.01-4.0   | 11       | 13     | 2.96%   |
| 4.01-10.0  | 8        | 9      | 2.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 89       | 29.57%  |
| 251-500        | 72       | 23.92%  |
| 501-1000       | 50       | 16.61%  |
| 1001-2000      | 26       | 8.64%   |
| 51-100         | 20       | 6.64%   |
| More than 3000 | 18       | 5.98%   |
| 21-50          | 16       | 5.32%   |
| 2001-3000      | 8        | 2.66%   |
| 1-20           | 2        | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 116      | 36.59%  |
| 21-50          | 58       | 18.3%   |
| 101-250        | 41       | 12.93%  |
| 51-100         | 36       | 11.36%  |
| 251-500        | 22       | 6.94%   |
| 501-1000       | 21       | 6.62%   |
| 1001-2000      | 13       | 4.1%    |
| More than 3000 | 6        | 1.89%   |
| 2001-3000      | 4        | 1.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB      | 1        | 1      | 4.55%   |
| WDC WD5000AAKX-221CA1 500GB       | 1        | 1      | 4.55%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 4.55%   |
| WDC WD3200AAJS-56B4A0 320GB       | 1        | 1      | 4.55%   |
| WDC WD10EZEX-00KUWA0 1TB          | 1        | 1      | 4.55%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 1      | 4.55%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 4.55%   |
| Seagate ST3500414CS 500GB         | 1        | 2      | 4.55%   |
| Seagate ST3500312CS 500GB         | 1        | 1      | 4.55%   |
| Seagate ST3320613AS 320GB         | 1        | 1      | 4.55%   |
| Seagate ST3160813AS 160GB         | 1        | 1      | 4.55%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1      | 4.55%   |
| SanDisk SSD PLUS 240GB            | 1        | 1      | 4.55%   |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 4.55%   |
| Samsung Electronics HD204UI 2TB   | 1        | 1      | 4.55%   |
| Samsung Electronics HD160JJ 160GB | 1        | 1      | 4.55%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 4.55%   |
| Hitachi HTS542525K9SA00 250GB     | 1        | 1      | 4.55%   |
| Hitachi HDT721064SLA360 640GB     | 1        | 1      | 4.55%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 4.55%   |
| HGST HUS724030ALA640 3TB          | 1        | 1      | 4.55%   |
| Crucial CT256M550SSD1 256GB       | 1        | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 27.27%  |
| Seagate             | 6        | 7      | 27.27%  |
| Samsung Electronics | 3        | 3      | 13.64%  |
| Hitachi             | 3        | 3      | 13.64%  |
| SanDisk             | 1        | 1      | 4.55%   |
| Kingston            | 1        | 1      | 4.55%   |
| HGST                | 1        | 1      | 4.55%   |
| Crucial             | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 31.58%  |
| Seagate             | 6        | 7      | 31.58%  |
| Samsung Electronics | 3        | 3      | 15.79%  |
| Hitachi             | 3        | 3      | 15.79%  |
| HGST                | 1        | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 20     | 84.21%  |
| SSD  | 3        | 3      | 15.79%  |

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
| Detected | 253      | 633    | 83.77%  |
| Works    | 31       | 71     | 10.26%  |
| Malfunc  | 18       | 23     | 5.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 197      | 51.84%  |
| AMD                         | 76       | 20%     |
| Samsung Electronics         | 30       | 7.89%   |
| ASMedia Technology          | 14       | 3.68%   |
| Nvidia                      | 10       | 2.63%   |
| Sandisk                     | 9        | 2.37%   |
| Marvell Technology Group    | 8        | 2.11%   |
| Kingston Technology Company | 7        | 1.84%   |
| JMicron Technology          | 7        | 1.84%   |
| Phison Electronics          | 5        | 1.32%   |
| Micron/Crucial Technology   | 5        | 1.32%   |
| Seagate Technology          | 2        | 0.53%   |
| Realtek Semiconductor       | 2        | 0.53%   |
| Micron Technology           | 2        | 0.53%   |
| ADATA Technology            | 2        | 0.53%   |
| VIA Technologies            | 1        | 0.26%   |
| Silicon Image               | 1        | 0.26%   |
| LSI Logic / Symbios Logic   | 1        | 0.26%   |
| Broadcom / LSI              | 1        | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 47       | 9.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 24       | 4.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23       | 4.72%   |
| AMD 400 Series Chipset SATA Controller                                                  | 23       | 4.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 18       | 3.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 18       | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 16       | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 16       | 3.29%   |
| Intel SATA Controller [RAID mode]                                                       | 15       | 3.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 15       | 3.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13       | 2.67%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 13       | 2.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 2.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10       | 2.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 1.44%   |
| AMD FCH SATA Controller D                                                               | 7        | 1.44%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 1.44%   |
| Kingston Company A2000 NVMe SSD                                                         | 6        | 1.23%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.82%   |
| Samsung NVMe SSD Controller 980                                                         | 4        | 0.82%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 0.82%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 4        | 0.82%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 0.82%   |
| Intel SSD 660P Series                                                                   | 4        | 0.82%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.82%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 0.82%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 4        | 0.82%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 0.82%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3        | 0.62%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 0.62%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 3        | 0.62%   |
| Nvidia MCP55 SATA Controller                                                            | 3        | 0.62%   |
| Nvidia MCP55 IDE                                                                        | 3        | 0.62%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 3        | 0.62%   |
| JMicron JMB368 IDE controller                                                           | 3        | 0.62%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 0.62%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 0.62%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.62%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 0.62%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.62%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.41%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.41%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.41%   |
| Sandisk Non-Volatile memory controller                                                  | 2        | 0.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.41%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2        | 0.41%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.41%   |
| Micron Non-Volatile memory controller                                                   | 2        | 0.41%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 2        | 0.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 0.41%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.41%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 0.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.41%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 219      | 58.71%  |
| IDE  | 70       | 18.77%  |
| NVMe | 60       | 16.09%  |
| RAID | 20       | 5.36%   |
| SAS  | 3        | 0.8%    |
| SCSI | 1        | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 200      | 70.42%  |
| AMD    | 84       | 29.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 10       | 3.52%   |
| AMD Ryzen 5 3600 6-Core Processor           | 8        | 2.82%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 2.11%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 5        | 1.76%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 5        | 1.76%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 1.41%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 1.41%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 1.41%   |
| Intel Core i5-3330S CPU @ 2.70GHz           | 4        | 1.41%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 4        | 1.41%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 4        | 1.41%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 1.41%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 1.41%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 1.06%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 1.06%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 1.06%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3        | 1.06%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 1.06%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz     | 3        | 1.06%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 3        | 1.06%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 1.06%   |
| AMD FX-6100 Six-Core Processor              | 3        | 1.06%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2        | 0.7%    |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 0.7%    |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 0.7%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 0.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 0.7%    |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.7%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.7%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.7%    |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 0.7%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.7%    |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.7%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 0.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.7%    |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.7%    |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.7%    |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 0.7%    |
| Intel Core i5-2320 CPU @ 3.00GHz            | 2        | 0.7%    |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 0.7%    |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 0.7%    |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 0.7%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 0.7%    |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 0.7%    |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 0.7%    |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 0.7%    |
| Intel Celeron CPU G530 @ 2.40GHz            | 2        | 0.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2        | 0.7%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 0.7%    |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 0.7%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 0.7%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 0.7%    |
| AMD Phenom II X4 965 Processor              | 2        | 0.7%    |
| AMD Phenom II X4 955 Processor              | 2        | 0.7%    |
| AMD FX-8350 Eight-Core Processor            | 2        | 0.7%    |
| AMD A4-5300 APU with Radeon HD Graphics     | 2        | 0.7%    |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 0.35%   |
| Intel Xeon CPU W3505 @ 2.53GHz              | 1        | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 63       | 22.18%  |
| Intel Core i7           | 43       | 15.14%  |
| AMD Ryzen 5             | 24       | 8.45%   |
| Intel Core i3           | 23       | 8.1%    |
| Intel Xeon              | 19       | 6.69%   |
| Intel Celeron           | 13       | 4.58%   |
| AMD Ryzen 7             | 11       | 3.87%   |
| Intel Core 2 Quad       | 9        | 3.17%   |
| AMD FX                  | 9        | 3.17%   |
| Intel Core 2 Duo        | 7        | 2.46%   |
| AMD Phenom II X4        | 7        | 2.46%   |
| Intel Pentium           | 6        | 2.11%   |
| AMD Ryzen 9             | 6        | 2.11%   |
| AMD Ryzen 3             | 6        | 2.11%   |
| Other                   | 5        | 1.76%   |
| Intel Core i9           | 4        | 1.41%   |
| Intel Atom              | 3        | 1.06%   |
| AMD Athlon II X4        | 3        | 1.06%   |
| AMD A8                  | 3        | 1.06%   |
| AMD A4                  | 3        | 1.06%   |
| Intel Pentium Dual-Core | 2        | 0.7%    |
| AMD Phenom              | 2        | 0.7%    |
| AMD Athlon              | 2        | 0.7%    |
| AMD A10                 | 2        | 0.7%    |
| Intel Pentium Dual      | 1        | 0.35%   |
| Intel Pentium D         | 1        | 0.35%   |
| Intel Pentium 4         | 1        | 0.35%   |
| AMD Ryzen Threadripper  | 1        | 0.35%   |
| AMD G                   | 1        | 0.35%   |
| AMD Athlon X4           | 1        | 0.35%   |
| AMD Athlon II X3        | 1        | 0.35%   |
| AMD Athlon II X2        | 1        | 0.35%   |
| AMD A6                  | 1        | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 131      | 46.13%  |
| 2      | 60       | 21.13%  |
| 6      | 40       | 14.08%  |
| 8      | 31       | 10.92%  |
| 12     | 8        | 2.82%   |
| 3      | 6        | 2.11%   |
| 1      | 6        | 2.11%   |
| 16     | 1        | 0.35%   |
| 10     | 1        | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 279      | 98.24%  |
| 2      | 5        | 1.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 151      | 53.17%  |
| 1      | 133      | 46.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 280      | 98.25%  |
| Unknown        | 5        | 1.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 32       | 11.07%  |
| 0x306c3    | 30       | 10.38%  |
| 0x306a9    | 23       | 7.96%   |
| Unknown    | 18       | 6.23%   |
| 0x08701021 | 15       | 5.19%   |
| 0x906ea    | 10       | 3.46%   |
| 0x906e9    | 9        | 3.11%   |
| 0x506e3    | 8        | 2.77%   |
| 0x1067a    | 8        | 2.77%   |
| 0x0800820d | 8        | 2.77%   |
| 0x906ed    | 7        | 2.42%   |
| 0x906eb    | 7        | 2.42%   |
| 0x010000c8 | 6        | 2.08%   |
| 0x206d7    | 5        | 1.73%   |
| 0x20652    | 5        | 1.73%   |
| 0x08108109 | 5        | 1.73%   |
| 0x06000852 | 5        | 1.73%   |
| 0xa0671    | 4        | 1.38%   |
| 0x6fb      | 4        | 1.38%   |
| 0x10676    | 4        | 1.38%   |
| 0x08701013 | 4        | 1.38%   |
| 0x06001119 | 4        | 1.38%   |
| 0x0600063e | 4        | 1.38%   |
| 0xa0655    | 3        | 1.04%   |
| 0x20655    | 3        | 1.04%   |
| 0x106e5    | 3        | 1.04%   |
| 0x106a5    | 3        | 1.04%   |
| 0x08001138 | 3        | 1.04%   |
| 0x0600611a | 3        | 1.04%   |
| 0x06003106 | 3        | 1.04%   |
| 0x010000db | 3        | 1.04%   |
| 0xa0653    | 2        | 0.69%   |
| 0x906ec    | 2        | 0.69%   |
| 0x706a8    | 2        | 0.69%   |
| 0x406c4    | 2        | 0.69%   |
| 0x306e4    | 2        | 0.69%   |
| 0x0a201016 | 2        | 0.69%   |
| 0x08101016 | 2        | 0.69%   |
| 0x0810100b | 2        | 0.69%   |
| 0x0800820b | 2        | 0.69%   |
| 0xf47      | 1        | 0.35%   |
| 0xf43      | 1        | 0.35%   |
| 0x806c1    | 1        | 0.35%   |
| 0x6fd      | 1        | 0.35%   |
| 0x6f7      | 1        | 0.35%   |
| 0x6f6      | 1        | 0.35%   |
| 0x306f2    | 1        | 0.35%   |
| 0x30678    | 1        | 0.35%   |
| 0x30673    | 1        | 0.35%   |
| 0x206c2    | 1        | 0.35%   |
| 0x106ca    | 1        | 0.35%   |
| 0x10677    | 1        | 0.35%   |
| 0x0a50000c | 1        | 0.35%   |
| 0x0a201009 | 1        | 0.35%   |
| 0x08101007 | 1        | 0.35%   |
| 0x08001137 | 1        | 0.35%   |
| 0x08001129 | 1        | 0.35%   |
| 0x0800111c | 1        | 0.35%   |
| 0x05000119 | 1        | 0.35%   |
| 0x010000c7 | 1        | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 39       | 13.73%  |
| KabyLake      | 38       | 13.38%  |
| Haswell       | 35       | 12.32%  |
| IvyBridge     | 25       | 8.8%    |
| Zen 2         | 19       | 6.69%   |
| Zen+          | 16       | 5.63%   |
| K10           | 14       | 4.93%   |
| Penryn        | 13       | 4.58%   |
| Zen           | 11       | 3.87%   |
| Westmere      | 9        | 3.17%   |
| Piledriver    | 9        | 3.17%   |
| Skylake       | 8        | 2.82%   |
| Core          | 8        | 2.82%   |
| Nehalem       | 6        | 2.11%   |
| CometLake     | 5        | 1.76%   |
| Zen 3         | 4        | 1.41%   |
| Silvermont    | 4        | 1.41%   |
| Icelake       | 4        | 1.41%   |
| Bulldozer     | 4        | 1.41%   |
| Steamroller   | 3        | 1.06%   |
| Excavator     | 3        | 1.06%   |
| NetBurst      | 2        | 0.7%    |
| Goldmont plus | 2        | 0.7%    |
| TigerLake     | 1        | 0.35%   |
| Bonnell       | 1        | 0.35%   |
| Bobcat        | 1        | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 124      | 40%     |
| AMD              | 96       | 30.97%  |
| Intel            | 88       | 28.39%  |
| Conexant Systems | 1        | 0.32%   |
| ATI Technologies | 1        | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20       | 6.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16       | 5.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 14       | 4.4%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11       | 3.46%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10       | 3.14%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 7        | 2.2%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 6        | 1.89%   |
| Intel HD Graphics 530                                                                    | 6        | 1.89%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 5        | 1.57%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 5        | 1.57%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5        | 1.57%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 1.57%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 5        | 1.57%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 4        | 1.26%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 1.26%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 4        | 1.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 1.26%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.26%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 1.26%   |
| Intel HD Graphics 630                                                                    | 4        | 1.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4        | 1.26%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 4        | 1.26%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 0.94%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3        | 0.94%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3        | 0.94%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 3        | 0.94%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3        | 0.94%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3        | 0.94%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 3        | 0.94%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 3        | 0.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3        | 0.94%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 0.94%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 3        | 0.94%   |
| AMD RV730 PRO [Radeon HD 4650]                                                           | 3        | 0.94%   |
| AMD RS880 [Radeon HD 4200]                                                               | 3        | 0.94%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 3        | 0.94%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3        | 0.94%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2        | 0.63%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2        | 0.63%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 2        | 0.63%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 2        | 0.63%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 0.63%   |
| Nvidia GK104 [GeForce GTX 770]                                                           | 2        | 0.63%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 2        | 0.63%   |
| Nvidia GF110 [GeForce GTX 580]                                                           | 2        | 0.63%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 0.63%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 0.63%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 2        | 0.63%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2        | 0.63%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 2        | 0.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 0.63%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2        | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 0.63%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2        | 0.63%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 0.63%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                                        | 2        | 0.63%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                                         | 2        | 0.63%   |
| AMD RS780D [Radeon HD 3300]                                                              | 2        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| 1 x Nvidia                     | 115      | 40.07%  |
| 1 x AMD                        | 86       | 29.97%  |
| 1 x Intel                      | 69       | 24.04%  |
| Intel + Nvidia                 | 5        | 1.74%   |
| 2 x AMD                        | 4        | 1.39%   |
| Intel + AMD                    | 3        | 1.05%   |
| AMD + Nvidia                   | 2        | 0.7%    |
| 2 x Nvidia                     | 1        | 0.35%   |
| 2 x AMD + 1 x Conexant Systems | 1        | 0.35%   |
| Intel + 2 x AMD                | 1        | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 201      | 69.79%  |
| Proprietary | 82       | 28.47%  |
| Unknown     | 5        | 1.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 77       | 26.64%  |
| 1.01-2.0   | 60       | 20.76%  |
| 0.51-1.0   | 38       | 13.15%  |
| 3.01-4.0   | 36       | 12.46%  |
| 7.01-8.0   | 32       | 11.07%  |
| 0.01-0.5   | 22       | 7.61%   |
| 5.01-6.0   | 14       | 4.84%   |
| 8.01-16.0  | 6        | 2.08%   |
| 2.01-3.0   | 4        | 1.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 52       | 16.4%   |
| Goldstar             | 34       | 10.73%  |
| Hewlett-Packard      | 28       | 8.83%   |
| Dell                 | 27       | 8.52%   |
| Acer                 | 26       | 8.2%    |
| AOC                  | 19       | 5.99%   |
| Ancor Communications | 17       | 5.36%   |
| BenQ                 | 16       | 5.05%   |
| Philips              | 15       | 4.73%   |
| LG Electronics       | 14       | 4.42%   |
| ViewSonic            | 6        | 1.89%   |
| Unknown              | 6        | 1.89%   |
| Lenovo               | 6        | 1.89%   |
| Vizio                | 4        | 1.26%   |
| NEC Computers        | 3        | 0.95%   |
| HPN                  | 3        | 0.95%   |
| Fujitsu Siemens      | 3        | 0.95%   |
| ___                  | 2        | 0.63%   |
| Iiyama               | 2        | 0.63%   |
| Grundig              | 2        | 0.63%   |
| CHR                  | 2        | 0.63%   |
| AUS                  | 2        | 0.63%   |
| Apple                | 2        | 0.63%   |
| Unknown              | 2        | 0.63%   |
| Vestel               | 1        | 0.32%   |
| TBD                  | 1        | 0.32%   |
| SPC                  | 1        | 0.32%   |
| SKY                  | 1        | 0.32%   |
| SAC                  | 1        | 0.32%   |
| Ruijiang             | 1        | 0.32%   |
| MSI                  | 1        | 0.32%   |
| Mi                   | 1        | 0.32%   |
| LLL                  | 1        | 0.32%   |
| Lenovo Group Limited | 1        | 0.32%   |
| KIV                  | 1        | 0.32%   |
| ITR INFOTRONIC       | 1        | 0.32%   |
| ITE                  | 1        | 0.32%   |
| IOD                  | 1        | 0.32%   |
| IBM                  | 1        | 0.32%   |
| HOP                  | 1        | 0.32%   |
| HKC                  | 1        | 0.32%   |
| Haier                | 1        | 0.32%   |
| Element              | 1        | 0.32%   |
| Eizo                 | 1        | 0.32%   |
| Denver               | 1        | 0.32%   |
| CHD                  | 1        | 0.32%   |
| BOE                  | 1        | 0.32%   |
| ASUSTek Computer     | 1        | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                           | 4        | 1.19%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch           | 3        | 0.9%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch              | 3        | 0.9%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch              | 3        | 0.9%    |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch                     | 3        | 0.9%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                         | 3        | 0.9%    |
| AOC 2369 AOC2369 1920x1080 509x286mm 23.0-inch                                 | 3        | 0.9%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch          | 3        | 0.9%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                          | 2        | 0.6%    |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch           | 2        | 0.6%    |
| Samsung Electronics LCD Monitor C32F391 1920x1080                              | 2        | 0.6%    |
| Philips LCD Monitor PHL 276E8V 3840x2160                                       | 2        | 0.6%    |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch                    | 2        | 0.6%    |
| Hewlett-Packard TouchSmart HP_touchsmart HWP4211 1920x1080 509x286mm 23.0-inch | 2        | 0.6%    |
| Grundig UHD GRU4448 3840x2160 1210x680mm 54.6-inch                             | 2        | 0.6%    |
| Goldstar E2211 GSM5838 1920x1080 477x268mm 21.5-inch                           | 2        | 0.6%    |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                          | 2        | 0.6%    |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                              | 2        | 0.6%    |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                              | 2        | 0.6%    |
| CHR CH7511B CHR7511 1280x768 519x324mm 24.1-inch                               | 2        | 0.6%    |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                             | 2        | 0.6%    |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                            | 2        | 0.6%    |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                               | 2        | 0.6%    |
| AOC 24E1W1 AOC2401 1920x1080 527x296mm 23.8-inch                               | 2        | 0.6%    |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                             | 2        | 0.6%    |
| Unknown                                                                        | 2        | 0.6%    |
| ___ LCDTV16 ___9000 1360x768                                                   | 1        | 0.3%    |
| ___ LCDTV16 ___0101 1360x768                                                   | 1        | 0.3%    |
| Vizio M260VA VIZ0067 1360x768 575x323mm 26.0-inch                              | 1        | 0.3%    |
| Vizio E321VL VIZ0083 1920x1080 700x400mm 31.7-inch                             | 1        | 0.3%    |
| Vizio D39h-D0 VIZ1002 1366x768 853x479mm 38.5-inch                             | 1        | 0.3%    |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                            | 1        | 0.3%    |
| ViewSonic VX2476 Series VSCD332 1920x1080 527x296mm 23.8-inch                  | 1        | 0.3%    |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch                  | 1        | 0.3%    |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch                  | 1        | 0.3%    |
| ViewSonic VA2055 Series VSC3C31 1920x1080 435x239mm 19.5-inch                  | 1        | 0.3%    |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch                   | 1        | 0.3%    |
| ViewSonic LCD Monitor VX2260WM 3840x1080                                       | 1        | 0.3%    |
| ViewSonic LCD Monitor VX2260WM                                                 | 1        | 0.3%    |
| Vestel LCD Monitor 49FHD_LCD_TV 1920x1080                                      | 1        | 0.3%    |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                             | 1        | 0.3%    |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                            | 1        | 0.3%    |
| Unknown LCD Monitor VIE LED MONITOR 1920x1080                                  | 1        | 0.3%    |
| Unknown LCD Monitor Bit 3 LE2262 1680x1050                                     | 1        | 0.3%    |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                                  | 1        | 0.3%    |
| SPC LCD Monitor SPC1900 1440x900 368x207mm 16.6-inch                           | 1        | 0.3%    |
| SKY TV Monitor SKY0001 1920x1080 885x498mm 40.0-inch                           | 1        | 0.3%    |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch              | 1        | 0.3%    |
| Samsung Electronics U28H75x SAM0E00 3840x2160 610x350mm 27.7-inch              | 1        | 0.3%    |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch              | 1        | 0.3%    |
| Samsung Electronics T27C370 SAM0ADE 1920x1080 598x336mm 27.0-inch              | 1        | 0.3%    |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch              | 1        | 0.3%    |
| Samsung Electronics SyncMaster SAM0595 2048x1152 510x287mm 23.0-inch           | 1        | 0.3%    |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch           | 1        | 0.3%    |
| Samsung Electronics SyncMaster SAM0421 1920x1200 518x324mm 24.1-inch           | 1        | 0.3%    |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch            | 1        | 0.3%    |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch            | 1        | 0.3%    |
| Samsung Electronics SMS23A350H SAM07D4 1920x1080 510x290mm 23.1-inch           | 1        | 0.3%    |
| Samsung Electronics SMBX2035 SAM06FD 1600x900 443x249mm 20.0-inch              | 1        | 0.3%    |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch           | 1        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 132      | 42.72%  |
| 3840x2160 (4K)     | 24       | 7.77%   |
| 2560x1440 (QHD)    | 24       | 7.77%   |
| 1680x1050 (WSXGA+) | 22       | 7.12%   |
| 1600x900 (HD+)     | 18       | 5.83%   |
| 1366x768 (WXGA)    | 14       | 4.53%   |
| Unknown            | 14       | 4.53%   |
| 1280x1024 (SXGA)   | 11       | 3.56%   |
| 3840x1080          | 8        | 2.59%   |
| 1440x900 (WXGA+)   | 8        | 2.59%   |
| 1920x1200 (WUXGA)  | 5        | 1.62%   |
| 3440x1440          | 4        | 1.29%   |
| 2560x1080          | 4        | 1.29%   |
| 1360x768           | 4        | 1.29%   |
| 5120x1440          | 2        | 0.65%   |
| 2560x1600          | 2        | 0.65%   |
| 1600x1200          | 2        | 0.65%   |
| 7680x2160          | 1        | 0.32%   |
| 7680x1600          | 1        | 0.32%   |
| 5760x2160          | 1        | 0.32%   |
| 5760x1080          | 1        | 0.32%   |
| 4480x1440          | 1        | 0.32%   |
| 3968x1280          | 1        | 0.32%   |
| 3840x1600          | 1        | 0.32%   |
| 3600x1080          | 1        | 0.32%   |
| 2288x1287          | 1        | 0.32%   |
| 2048x1152          | 1        | 0.32%   |
| 1024x768 (XGA)     | 1        | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 72       | 23.23%  |
| 21      | 35       | 11.29%  |
| 27      | 30       | 9.68%   |
| 24      | 30       | 9.68%   |
| 23      | 29       | 9.35%   |
| 22      | 17       | 5.48%   |
| 19      | 15       | 4.84%   |
| 20      | 13       | 4.19%   |
| 31      | 10       | 3.23%   |
| 18      | 8        | 2.58%   |
| 32      | 7        | 2.26%   |
| 17      | 6        | 1.94%   |
| 34      | 5        | 1.61%   |
| 54      | 4        | 1.29%   |
| 15      | 4        | 1.29%   |
| 84      | 3        | 0.97%   |
| 72      | 3        | 0.97%   |
| 29      | 3        | 0.97%   |
| 49      | 2        | 0.65%   |
| 33      | 2        | 0.65%   |
| 25      | 2        | 0.65%   |
| 57      | 1        | 0.32%   |
| 55      | 1        | 0.32%   |
| 48      | 1        | 0.32%   |
| 43      | 1        | 0.32%   |
| 40      | 1        | 0.32%   |
| 39      | 1        | 0.32%   |
| 38      | 1        | 0.32%   |
| 28      | 1        | 0.32%   |
| 26      | 1        | 0.32%   |
| 16      | 1        | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 79       | 26.51%  |
| 401-500     | 79       | 26.51%  |
| Unknown     | 72       | 24.16%  |
| 601-700     | 20       | 6.71%   |
| 701-800     | 14       | 4.7%    |
| 301-350     | 9        | 3.02%   |
| 1001-1500   | 9        | 3.02%   |
| 351-400     | 6        | 2.01%   |
| 1501-2000   | 6        | 2.01%   |
| 801-900     | 3        | 1.01%   |
| 901-1000    | 1        | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 156      | 55.71%  |
| Unknown | 69       | 24.64%  |
| 16/10   | 33       | 11.79%  |
| 5/4     | 9        | 3.21%   |
| 21/9    | 7        | 2.5%    |
| 4/3     | 2        | 0.71%   |
| 32/9    | 2        | 0.71%   |
| 3/2     | 2        | 0.71%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 85       | 28.24%  |
| Unknown        | 72       | 23.92%  |
| 151-200        | 36       | 11.96%  |
| 301-350        | 31       | 10.3%   |
| 351-500        | 26       | 8.64%   |
| 251-300        | 14       | 4.65%   |
| More than 1000 | 13       | 4.32%   |
| 141-150        | 12       | 3.99%   |
| 501-1000       | 6        | 1.99%   |
| 101-110        | 3        | 1%      |
| 131-140        | 1        | 0.33%   |
| 111-120        | 1        | 0.33%   |
| 91-100         | 1        | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 146      | 50.69%  |
| Unknown | 72       | 25%     |
| 101-120 | 52       | 18.06%  |
| 1-50    | 10       | 3.47%   |
| 121-160 | 8        | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 229      | 78.69%  |
| 2     | 46       | 15.81%  |
| 3     | 10       | 3.44%   |
| 0     | 6        | 2.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 177      | 43.07%  |
| Intel                           | 111      | 27.01%  |
| Qualcomm Atheros                | 22       | 5.35%   |
| TP-Link                         | 18       | 4.38%   |
| Broadcom                        | 18       | 4.38%   |
| Ralink Technology               | 13       | 3.16%   |
| Nvidia                          | 7        | 1.7%    |
| Samsung Electronics             | 6        | 1.46%   |
| Xiaomi                          | 4        | 0.97%   |
| Qualcomm Atheros Communications | 3        | 0.73%   |
| Microsoft                       | 3        | 0.73%   |
| Marvell Technology Group        | 3        | 0.73%   |
| D-Link System                   | 3        | 0.73%   |
| Ralink                          | 2        | 0.49%   |
| Linksys                         | 2        | 0.49%   |
| Huawei Technologies             | 2        | 0.49%   |
| D-Link                          | 2        | 0.49%   |
| Broadcom Limited                | 2        | 0.49%   |
| VIA Technologies                | 1        | 0.24%   |
| TRENDnet                        | 1        | 0.24%   |
| OPPO Electronics                | 1        | 0.24%   |
| NetGear                         | 1        | 0.24%   |
| Motorola PCS                    | 1        | 0.24%   |
| Mercucys                        | 1        | 0.24%   |
| MediaTek                        | 1        | 0.24%   |
| LG Electronics                  | 1        | 0.24%   |
| Input Club                      | 1        | 0.24%   |
| Edimax Technology               | 1        | 0.24%   |
| BUFFALO                         | 1        | 0.24%   |
| AVM                             | 1        | 0.24%   |
| ASUSTek Computer                | 1        | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                 | 138      | 29.68%  |
| Intel I211 Gigabit Network Connection                                             | 18       | 3.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 14       | 3.01%   |
| Intel Wi-Fi 6 AX200                                                               | 13       | 2.8%    |
| Intel Ethernet Connection (2) I219-V                                              | 11       | 2.37%   |
| Realtek RTL8125 2.5GbE Controller                                                 | 10       | 2.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 10       | 2.15%   |
| Intel Ethernet Connection (7) I219-V                                              | 9        | 1.94%   |
| Ralink MT7601U Wireless Adapter                                                   | 8        | 1.72%   |
| Intel 82579V Gigabit Network Connection                                           | 8        | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 7        | 1.51%   |
| Realtek 802.11ac NIC                                                              | 6        | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 5        | 1.08%   |
| Intel Ethernet Connection I217-LM                                                 | 5        | 1.08%   |
| Intel 82574L Gigabit Network Connection                                           | 5        | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                    | 4        | 0.86%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                               | 4        | 0.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 4        | 0.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                          | 4        | 0.86%   |
| Intel Ethernet Controller I225-V                                                  | 4        | 0.86%   |
| Intel Ethernet Connection I217-V                                                  | 4        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 4        | 0.86%   |
| Intel 82578DM Gigabit Network Connection                                          | 4        | 0.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 4        | 0.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 3        | 0.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 3        | 0.65%   |
| TP-Link 802.11ac NIC                                                              | 3        | 0.65%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                       | 3        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                                     | 3        | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 3        | 0.65%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 3        | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                             | 3        | 0.65%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 3        | 0.65%   |
| Nvidia MCP61 Ethernet                                                             | 3        | 0.65%   |
| Microsoft Xbox 360 Wireless Adapter                                               | 3        | 0.65%   |
| Intel Wireless-AC 9260                                                            | 3        | 0.65%   |
| Intel Ethernet Connection (2) I218-V                                              | 3        | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                                        | 3        | 0.65%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 3        | 0.65%   |
| Broadcom BCM43228 802.11a/b/g/n                                                   | 3        | 0.65%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 2        | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                   | 2        | 0.43%   |
| Realtek RTL8187 Wireless Adapter                                                  | 2        | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                         | 2        | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                          | 2        | 0.43%   |
| Nvidia MCP77 Ethernet                                                             | 2        | 0.43%   |
| Nvidia MCP55 Ethernet                                                             | 2        | 0.43%   |
| Intel Wireless 8260                                                               | 2        | 0.43%   |
| Intel Wireless 7260                                                               | 2        | 0.43%   |
| Intel Wireless 3165                                                               | 2        | 0.43%   |
| Intel Tiger Lake PCH CNVi WiFi                                                    | 2        | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                                             | 2        | 0.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 2        | 0.43%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                            | 2        | 0.43%   |
| Huawei JNY-LX1                                                                    | 2        | 0.43%   |
| VIA VT6105/VT6106S [Rhine-III]                                                    | 1        | 0.22%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.22%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 1        | 0.22%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                             | 1        | 0.22%   |
| TP-Link Archer T4U ver.3                                                          | 1        | 0.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 39       | 25.49%  |
| Intel                           | 37       | 24.18%  |
| TP-Link                         | 18       | 11.76%  |
| Ralink Technology               | 13       | 8.5%    |
| Broadcom                        | 12       | 7.84%   |
| Qualcomm Atheros                | 9        | 5.88%   |
| Qualcomm Atheros Communications | 3        | 1.96%   |
| Microsoft                       | 3        | 1.96%   |
| Ralink                          | 2        | 1.31%   |
| Linksys                         | 2        | 1.31%   |
| D-Link System                   | 2        | 1.31%   |
| D-Link                          | 2        | 1.31%   |
| Broadcom Limited                | 2        | 1.31%   |
| TRENDnet                        | 1        | 0.65%   |
| NetGear                         | 1        | 0.65%   |
| Mercucys                        | 1        | 0.65%   |
| Marvell Technology Group        | 1        | 0.65%   |
| LG Electronics                  | 1        | 0.65%   |
| Edimax Technology               | 1        | 0.65%   |
| BUFFALO                         | 1        | 0.65%   |
| AVM                             | 1        | 0.65%   |
| ASUSTek Computer                | 1        | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 13       | 8.33%   |
| Ralink MT7601U Wireless Adapter                                                   | 8        | 5.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 7        | 4.49%   |
| Realtek 802.11ac NIC                                                              | 6        | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 5        | 3.21%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                               | 4        | 2.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 4        | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 4        | 2.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 4        | 2.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 3        | 1.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 3        | 1.92%   |
| TP-Link 802.11ac NIC                                                              | 3        | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 3        | 1.92%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 3        | 1.92%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 3        | 1.92%   |
| Microsoft Xbox 360 Wireless Adapter                                               | 3        | 1.92%   |
| Intel Wireless-AC 9260                                                            | 3        | 1.92%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 3        | 1.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                                   | 3        | 1.92%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 2        | 1.28%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                   | 2        | 1.28%   |
| Realtek RTL8187 Wireless Adapter                                                  | 2        | 1.28%   |
| Intel Wireless 8260                                                               | 2        | 1.28%   |
| Intel Wireless 7260                                                               | 2        | 1.28%   |
| Intel Wireless 3165                                                               | 2        | 1.28%   |
| Intel Tiger Lake PCH CNVi WiFi                                                    | 2        | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 2        | 1.28%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 1        | 0.64%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                             | 1        | 0.64%   |
| TP-Link Archer T4U ver.3                                                          | 1        | 0.64%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                         | 1        | 0.64%   |
| TP-Link 802.11ac WLAN Adapter                                                     | 1        | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                   | 1        | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.64%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                           | 1        | 0.64%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                   | 1        | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                   | 1        | 0.64%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 1        | 0.64%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                   | 1        | 0.64%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                       | 1        | 0.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 1        | 0.64%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 1        | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                                        | 1        | 0.64%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                         | 1        | 0.64%   |
| Realtek 802.11n WLAN Adapter                                                      | 1        | 0.64%   |
| Ralink RT5572 Wireless Adapter                                                    | 1        | 0.64%   |
| Ralink RT5372 Wireless Adapter                                                    | 1        | 0.64%   |
| Ralink RT5370 Wireless Adapter                                                    | 1        | 0.64%   |
| Ralink RT3072 Wireless Adapter                                                    | 1        | 0.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                                             | 1        | 0.64%   |
| Ralink RT5592 PCIe Wireless Network Adapter                                       | 1        | 0.64%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                         | 1        | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 1        | 0.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                  | 1        | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                    | 1        | 0.64%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]            | 1        | 0.64%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]                            | 1        | 0.64%   |
| Mercucys 802.11n NIC                                                              | 1        | 0.64%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                               | 1        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 162      | 53.64%  |
| Intel                    | 95       | 31.46%  |
| Qualcomm Atheros         | 13       | 4.3%    |
| Nvidia                   | 7        | 2.32%   |
| Samsung Electronics      | 6        | 1.99%   |
| Broadcom                 | 6        | 1.99%   |
| Xiaomi                   | 4        | 1.32%   |
| Marvell Technology Group | 2        | 0.66%   |
| Huawei Technologies      | 2        | 0.66%   |
| VIA Technologies         | 1        | 0.33%   |
| OPPO Electronics         | 1        | 0.33%   |
| Motorola PCS             | 1        | 0.33%   |
| MediaTek                 | 1        | 0.33%   |
| D-Link System            | 1        | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 138      | 44.81%  |
| Intel I211 Gigabit Network Connection                             | 18       | 5.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14       | 4.55%   |
| Intel Ethernet Connection (2) I219-V                              | 11       | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 3.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10       | 3.25%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 2.92%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 2.6%    |
| Intel Ethernet Connection I217-LM                                 | 5        | 1.62%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4        | 1.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 1.3%    |
| Intel Ethernet Controller I225-V                                  | 4        | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 4        | 1.3%    |
| Intel 82578DM Gigabit Network Connection                          | 4        | 1.3%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3        | 0.97%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.97%   |
| Nvidia MCP61 Ethernet                                             | 3        | 0.97%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.97%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.65%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.65%   |
| Nvidia MCP55 Ethernet                                             | 2        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.65%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 2        | 0.65%   |
| Huawei JNY-LX1                                                    | 2        | 0.65%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.32%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.32%   |
| OPPO SDM665-IDP _SN:18689828                                      | 1        | 0.32%   |
| Motorola PCS moto g(30)                                           | 1        | 0.32%   |
| MediaTek NOA N2                                                   | 1        | 0.32%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.32%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.32%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.32%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.32%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.32%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.32%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.32%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.32%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 0.32%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.32%   |
| D-Link System DGE-530T Gigabit Ethernet Adapter (rev 11)          | 1        | 0.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.32%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.32%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1        | 0.32%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 0.32%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 0.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 280      | 66.35%  |
| WiFi     | 141      | 33.41%  |
| Modem    | 1        | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 258      | 70.68%  |
| WiFi     | 107      | 29.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 194      | 68.07%  |
| 2     | 74       | 25.96%  |
| 3     | 12       | 4.21%   |
| 0     | 4        | 1.4%    |
| 4     | 1        | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 235      | 81.6%   |
| Yes  | 53       | 18.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 35       | 36.08%  |
| Intel                           | 34       | 35.05%  |
| Realtek Semiconductor           | 7        | 7.22%   |
| ASUSTek Computer                | 6        | 6.19%   |
| Apple                           | 5        | 5.15%   |
| Broadcom                        | 4        | 4.12%   |
| IMC Networks                    | 2        | 2.06%   |
| Belkin Components               | 2        | 2.06%   |
| Qualcomm Atheros Communications | 1        | 1.03%   |
| Qcom                            | 1        | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 35       | 36.08%  |
| Intel AX200 Bluetooth                                 | 12       | 12.37%  |
| Intel Bluetooth wireless interface                    | 7        | 7.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 6        | 6.19%   |
| Realtek  Bluetooth 4.2 Adapter                        | 3        | 3.09%   |
| Realtek Bluetooth Radio                               | 3        | 3.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3        | 3.09%   |
| Intel Bluetooth Device                                | 3        | 3.09%   |
| Apple Bluetooth USB Host Controller                   | 3        | 3.09%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 2.06%   |
| IMC Networks BCM20702A0                               | 2        | 2.06%   |
| Belkin Components Bluetooth Mini Dongle               | 2        | 2.06%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 2.06%   |
| ASUS BCM20702A0                                       | 2        | 2.06%   |
| Realtek Bluetooth 5.1 Radio                           | 1        | 1.03%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 1.03%   |
| Qcom Bluetooth USB                                    | 1        | 1.03%   |
| Intel AX210 Bluetooth                                 | 1        | 1.03%   |
| Broadcom HP Portable Bumble Bee                       | 1        | 1.03%   |
| Broadcom Bluetooth dongle                             | 1        | 1.03%   |
| Broadcom Bluetooth 3.0 Dongle                         | 1        | 1.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 1.03%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.03%   |
| ASUS Bluetooth Radio                                  | 1        | 1.03%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 1        | 1.03%   |
| Apple Bluetooth HCI                                   | 1        | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 187      | 37.47%  |
| AMD                                  | 121      | 24.25%  |
| Nvidia                               | 119      | 23.85%  |
| C-Media Electronics                  | 22       | 4.41%   |
| Creative Labs                        | 11       | 2.2%    |
| Logitech                             | 6        | 1.2%    |
| Generalplus Technology               | 5        | 1%      |
| JMTek                                | 4        | 0.8%    |
| Creative Technology                  | 4        | 0.8%    |
| Razer USA                            | 3        | 0.6%    |
| GN Netcom                            | 2        | 0.4%    |
| Focusrite-Novation                   | 2        | 0.4%    |
| BEHRINGER International              | 2        | 0.4%    |
| Thesycon Systemsoftware & Consulting | 1        | 0.2%    |
| Texas Instruments                    | 1        | 0.2%    |
| PreSonus Audio Electronics           | 1        | 0.2%    |
| Plantronics                          | 1        | 0.2%    |
| Native Instruments                   | 1        | 0.2%    |
| Hewlett-Packard                      | 1        | 0.2%    |
| Corsair                              | 1        | 0.2%    |
| BY EDIFIER                           | 1        | 0.2%    |
| ATI Technologies                     | 1        | 0.2%    |
| ASUSTek Computer                     | 1        | 0.2%    |
| Astro Gaming                         | 1        | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 41       | 7.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 24       | 4.23%   |
| AMD Starship/Matisse HD Audio Controller                                          | 20       | 3.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 20       | 3.53%   |
| Intel Cannon Lake PCH cAVS                                                        | 19       | 3.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 16       | 2.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 15       | 2.65%   |
| Intel 200 Series PCH HD Audio                                                     | 15       | 2.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 15       | 2.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 14       | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 13       | 2.29%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 13       | 2.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 11       | 1.94%   |
| AMD Family 17h/19h HD Audio Controller                                            | 11       | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 10       | 1.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 10       | 1.76%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 9        | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 9        | 1.59%   |
| Nvidia GP106 High Definition Audio Controller                                     | 8        | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                                     | 8        | 1.41%   |
| AMD FCH Azalia Controller                                                         | 8        | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7        | 1.23%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 1.23%   |
| Nvidia GP104 High Definition Audio Controller                                     | 6        | 1.06%   |
| Nvidia GM204 High Definition Audio Controller                                     | 6        | 1.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 1.06%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 6        | 1.06%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 6        | 1.06%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 6        | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                                     | 5        | 0.88%   |
| Nvidia TU104 HD Audio Controller                                                  | 5        | 0.88%   |
| Nvidia High Definition Audio Controller                                           | 5        | 0.88%   |
| Nvidia GK104 HDMI Audio Controller                                                | 5        | 0.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5        | 0.88%   |
| Generalplus Technology USB Audio Device                                           | 5        | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4        | 0.71%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4        | 0.71%   |
| Nvidia MCP61 High Definition Audio                                                | 4        | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                                | 4        | 0.71%   |
| JMTek USB PnP Audio Device                                                        | 4        | 0.71%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 4        | 0.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 4        | 0.71%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 0.71%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 3        | 0.53%   |
| Nvidia MCP55 High Definition Audio                                                | 3        | 0.53%   |
| Nvidia GP102 HDMI Audio Controller                                                | 3        | 0.53%   |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 0.53%   |
| Nvidia GA104 High Definition Audio Controller                                     | 3        | 0.53%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 0.53%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 3        | 0.53%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 3        | 0.53%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 3        | 0.53%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                        | 3        | 0.53%   |
| C-Media Electronics USB Audio Device                                              | 3        | 0.53%   |
| AMD Trinity HDMI Audio Controller                                                 | 3        | 0.53%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 3        | 0.53%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 0.53%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 3        | 0.53%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.35%   |
| Nvidia GF116 High Definition Audio Controller                                     | 2        | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 23       | 26.14%  |
| Unknown             | 10       | 11.36%  |
| SK Hynix            | 9        | 10.23%  |
| Samsung Electronics | 9        | 10.23%  |
| Corsair             | 9        | 10.23%  |
| G.Skill             | 7        | 7.95%   |
| Crucial             | 6        | 6.82%   |
| Patriot             | 3        | 3.41%   |
| Ramaxel Technology  | 2        | 2.27%   |
| Nanya Technology    | 2        | 2.27%   |
| Micron Technology   | 2        | 2.27%   |
| Unknown (82B5)      | 1        | 1.14%   |
| Transcend           | 1        | 1.14%   |
| Team                | 1        | 1.14%   |
| PNY                 | 1        | 1.14%   |
| Neo Forza           | 1        | 1.14%   |
| Apacer              | 1        | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 2        | 2.15%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                     | 2        | 2.15%   |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s            | 2        | 2.15%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s             | 2        | 2.15%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                            | 1        | 1.08%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                    | 1        | 1.08%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                         | 1        | 1.08%   |
| Unknown RAM Module 512MB DIMM SDRAM                             | 1        | 1.08%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                    | 1        | 1.08%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1        | 1.08%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                     | 1        | 1.08%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                      | 1        | 1.08%   |
| Unknown RAM Module 1024MB DIMM SDRAM                            | 1        | 1.08%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                     | 1        | 1.08%   |
| Unknown (82B5) RAM OP 117100 05/14 2M 4096MB DIMM DDR3 1333MT/s | 1        | 1.08%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s               | 1        | 1.08%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s              | 1        | 1.08%   |
| SK Hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 1639MT/s            | 1        | 1.08%   |
| SK Hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s           | 1        | 1.08%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s         | 1        | 1.08%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s            | 1        | 1.08%   |
| SK Hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s         | 1        | 1.08%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1        | 1.08%   |
| SK Hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s         | 1        | 1.08%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                    | 1        | 1.08%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s        | 1        | 1.08%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s        | 1        | 1.08%   |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s             | 1        | 1.08%   |
| Samsung RAM M393B1K70CHD-CH9 8GB DIMM DDR3 1333MT/s             | 1        | 1.08%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s                  | 1        | 1.08%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s             | 1        | 1.08%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s             | 1        | 1.08%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s             | 1        | 1.08%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s       | 1        | 1.08%   |
| Ramaxel RAM RMR1870ED48E8F1333 2048MB DIMM DDR3 1333MT/s        | 1        | 1.08%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 3200MT/s          | 1        | 1.08%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                 | 1        | 1.08%   |
| Patriot RAM PSD22G8002 2GB DIMM DDR2 800MT/s                    | 1        | 1.08%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s              | 1        | 1.08%   |
| Neo Forza RAM NMUD380D81-1600D 8GB DIMM DDR3 1333MT/s           | 1        | 1.08%   |
| Nanya RAM Module 4GB FB-DIMM DDR2 667MT/s                       | 1        | 1.08%   |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                         | 1        | 1.08%   |
| Micron RAM 16JTF25664AZ-1G4F 2GB DIMM DDR3 1333MT/s             | 1        | 1.08%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM SDRAM 1600MT/s            | 1        | 1.08%   |
| Kingston RAM Module 4GB FB-DIMM DDR2 667MT/s                    | 1        | 1.08%   |
| Kingston RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 1        | 1.08%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 1.08%   |
| Kingston RAM KHX3466C16D4/8GX 8192MB DIMM DDR4 3466MT/s         | 1        | 1.08%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s          | 1        | 1.08%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s               | 1        | 1.08%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s             | 1        | 1.08%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s             | 1        | 1.08%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s             | 1        | 1.08%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s            | 1        | 1.08%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s             | 1        | 1.08%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s           | 1        | 1.08%   |
| Kingston RAM HP497157-B88-ELDW 2048MB DIMM DDR3 1333MT/s        | 1        | 1.08%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1600MT/s           | 1        | 1.08%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s           | 1        | 1.08%   |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s               | 1        | 1.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 31       | 45.59%  |
| DDR4    | 23       | 33.82%  |
| DDR2    | 7        | 10.29%  |
| SDRAM   | 3        | 4.41%   |
| Unknown | 3        | 4.41%   |
| DDR     | 1        | 1.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 64       | 94.12%  |
| SODIMM  | 3        | 4.41%   |
| FB-DIMM | 1        | 1.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 32       | 40.51%  |
| 4096  | 19       | 24.05%  |
| 2048  | 13       | 16.46%  |
| 16384 | 9        | 11.39%  |
| 1024  | 4        | 5.06%   |
| 32768 | 1        | 1.27%   |
| 512   | 1        | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 17       | 21.52%  |
| 1600    | 13       | 16.46%  |
| 3200    | 6        | 7.59%   |
| 667     | 5        | 6.33%   |
| 3600    | 4        | 5.06%   |
| 2400    | 4        | 5.06%   |
| 3466    | 3        | 3.8%    |
| 2133    | 3        | 3.8%    |
| 1867    | 3        | 3.8%    |
| 1800    | 3        | 3.8%    |
| 800     | 3        | 3.8%    |
| 3000    | 2        | 2.53%   |
| 1066    | 2        | 2.53%   |
| 3334    | 1        | 1.27%   |
| 3007    | 1        | 1.27%   |
| 2934    | 1        | 1.27%   |
| 2933    | 1        | 1.27%   |
| 2800    | 1        | 1.27%   |
| 2666    | 1        | 1.27%   |
| 2200    | 1        | 1.27%   |
| 1866    | 1        | 1.27%   |
| 1639    | 1        | 1.27%   |
| 133     | 1        | 1.27%   |
| Unknown | 1        | 1.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 7        | 53.85%  |
| Brother Industries | 3        | 23.08%  |
| Canon              | 2        | 15.38%  |
| Dymo-CoStar        | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP Printing Support         | 1        | 7.69%   |
| HP LaserJet Pro M201dw      | 1        | 7.69%   |
| HP LaserJet M101-M106       | 1        | 7.69%   |
| HP LaserJet 1320            | 1        | 7.69%   |
| HP Ink Tank 110 series      | 1        | 7.69%   |
| HP Deskjet 2050 J510        | 1        | 7.69%   |
| HP Deskjet 1000 J110 series | 1        | 7.69%   |
| Dymo-CoStar LabelWriter 450 | 1        | 7.69%   |
| Canon TR8500 series         | 1        | 7.69%   |
| Canon PIXMA MG3600 Series   | 1        | 7.69%   |
| Brother MFC-T910DW          | 1        | 7.69%   |
| Brother HL-4140CN series    | 1        | 7.69%   |
| Brother DCP-L2550DN series  | 1        | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 22       | 34.92%  |
| Microsoft                     | 6        | 9.52%   |
| Microdia                      | 6        | 9.52%   |
| Apple                         | 4        | 6.35%   |
| Sunplus Innovation Technology | 3        | 4.76%   |
| Chicony Electronics           | 3        | 4.76%   |
| Z-Star Microelectronics       | 2        | 3.17%   |
| Generalplus Technology        | 2        | 3.17%   |
| Cubeternet                    | 2        | 3.17%   |
| Alcor Micro                   | 2        | 3.17%   |
| Teslong Camera                | 1        | 1.59%   |
| Samsung Electronics           | 1        | 1.59%   |
| Realtek Semiconductor         | 1        | 1.59%   |
| Razer USA                     | 1        | 1.59%   |
| LG Electronics                | 1        | 1.59%   |
| KYE Systems (Mouse Systems)   | 1        | 1.59%   |
| Hewlett-Packard               | 1        | 1.59%   |
| Guillemot                     | 1        | 1.59%   |
| Creative Technology           | 1        | 1.59%   |
| CQG-5693-201019               | 1        | 1.59%   |
| ANYKA                         | 1        | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                           | 6        | 9.52%   |
| Logitech Webcam C270                                  | 3        | 4.76%   |
| Apple iPhone 5/5C/5S/6/SE                             | 3        | 4.76%   |
| Sunplus Integrated_Webcam_HD                          | 2        | 3.17%   |
| Microsoft LifeCam HD-3000                             | 2        | 3.17%   |
| Microdia Laptop_Integrated_Webcam_FHD                 | 2        | 3.17%   |
| Logitech HD Webcam C615                               | 2        | 3.17%   |
| Logitech BRIO 4K Stream Edition                       | 2        | 3.17%   |
| Logitech B525 HD Webcam                               | 2        | 3.17%   |
| Generalplus GENERAL WEBCAM                            | 2        | 3.17%   |
| Cubeternet GL-UPC822 UVC WebCam                       | 2        | 3.17%   |
| Z-Star Venus USB2.0 Camera                            | 1        | 1.59%   |
| Z-Star Sirius USB2.0 Camera                           | 1        | 1.59%   |
| Teslong Camera                                        | 1        | 1.59%   |
| Sunplus Aukey-PC-LM1E Camera                          | 1        | 1.59%   |
| Samsung Galaxy A5 (MTP)                               | 1        | 1.59%   |
| Realtek FULL HD 1080P Webcam                          | 1        | 1.59%   |
| Razer USA Razer Kiyo Pro                              | 1        | 1.59%   |
| Microsoft Xbox NUI Camera                             | 1        | 1.59%   |
| Microsoft LifeCam VX-800                              | 1        | 1.59%   |
| Microsoft LifeCam VX-2000                             | 1        | 1.59%   |
| Microsoft LifeCam HD-5000                             | 1        | 1.59%   |
| Microdia Webcam Vitade AF                             | 1        | 1.59%   |
| Microdia USB 2.0 Camera                               | 1        | 1.59%   |
| Microdia Sonix USB 2.0 Camera                         | 1        | 1.59%   |
| Microdia JP001                                        | 1        | 1.59%   |
| Logitech Webcam C925e                                 | 1        | 1.59%   |
| Logitech Webcam C310                                  | 1        | 1.59%   |
| Logitech Webcam C250                                  | 1        | 1.59%   |
| Logitech QuickCam Communicate Deluxe                  | 1        | 1.59%   |
| Logitech HD Webcam C910                               | 1        | 1.59%   |
| Logitech C505 HD Webcam                               | 1        | 1.59%   |
| Logitech BCC950 ConferenceCam                         | 1        | 1.59%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 1.59%   |
| KYE Systems (Mouse Systems) Genius Webcam             | 1        | 1.59%   |
| HP Webcam HD-2200                                     | 1        | 1.59%   |
| Guillemot Hercules Dualpix Exchange                   | 1        | 1.59%   |
| Creative Live! Cam Sync 1080p                         | 1        | 1.59%   |
| CQG-5693-201019 Real QHD(2592x1944)                   | 1        | 1.59%   |
| Chicony USB2.0 UVC VGA                                | 1        | 1.59%   |
| Chicony HP High Definition 1MP Webcam                 | 1        | 1.59%   |
| Chicony HP 1.0MP High Definition Webcam               | 1        | 1.59%   |
| Apple iPhone 4                                        | 1        | 1.59%   |
| ANYKA V380 FHD Camera                                 | 1        | 1.59%   |
| Alcor Micro USB 2.0 Web Camera                        | 1        | 1.59%   |
| Alcor Micro USB 2.0 PC Camera                         | 1        | 1.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Chicony Electronics | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 253      | 87.24%  |
| 1     | 31       | 10.69%  |
| 2     | 3        | 1.03%   |
| 4     | 2        | 0.69%   |
| 3     | 1        | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 21       | 48.84%  |
| Graphics card            | 6        | 13.95%  |
| Sound                    | 4        | 9.3%    |
| Unassigned class         | 2        | 4.65%   |
| Network                  | 2        | 4.65%   |
| Camera                   | 2        | 4.65%   |
| Storage/ide              | 1        | 2.33%   |
| Multimedia controller    | 1        | 2.33%   |
| Fingerprint reader       | 1        | 2.33%   |
| Communication controller | 1        | 2.33%   |
| Card reader              | 1        | 2.33%   |
| Bluetooth                | 1        | 2.33%   |

