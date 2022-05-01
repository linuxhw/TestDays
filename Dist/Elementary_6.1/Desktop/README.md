Elementary 6.1 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

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

Total: 139

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| HP       | 0B48h                       | [4c6e5824f2](https://linux-hardware.org/?probe=4c6e5824f2) | Apr 30, 2022 |
| ASUSTek  | P8Z77-V                     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| Dell     | 0J3C2F A00                  | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [1f10d820f8](https://linux-hardware.org/?probe=1f10d820f8) | Apr 27, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [dfadead480](https://linux-hardware.org/?probe=dfadead480) | Apr 27, 2022 |
| Gigabyte | B150N Phoenix-WIFI-CF       | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek  | ROG STRIX Z590-F GAMING ... | [1b0a41c232](https://linux-hardware.org/?probe=1b0a41c232) | Apr 25, 2022 |
| AZW      | GTi                         | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW      | GTi                         | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ECS      | H61H2-MV                    | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| MSI      | X99A SLI PLUS               | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| ASRock   | Z490 Pro4                   | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Dell     | 0KV62T A01                  | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell     | 0KV62T A01                  | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI      | B450M PRO-VDH MAX           | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| HP       | 1494                        | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| Gigabyte | H61M-D2H-USB3               | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Fujitsu  | D3531-A1 S26361-D3531-A1    | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| ASUSTek  | B85M-G                      | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| Gigabyte | B450 AORUS ELITE            | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek  | B85M-G                      | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte | B450 AORUS ELITE            | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Dell     | 0K240Y A01                  | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| ASUSTek  | TUF X470-PLUS GAMING        | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Lenovo   | 3178 SDK0J40700 WIN 3258... | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| ASUSTek  | PRIME Z390-A                | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| Pegatron | IPMH61P1                    | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| ASUSTek  | H110I-PLUS                  | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| ASRock   | C226 WS                     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ASUSTek  | STRIKER II FORMULA          | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek  | STRIKER II FORMULA          | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| ASUSTek  | TUF Gaming B460M-PLUS       | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| Lenovo   | ThinkCentre M58 6258D3G     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo   | ThinkCentre M58 6258D3G     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI      | H97 GAMING 3                | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI      | MEG X570 ACE                | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| ASUSTek  | Rampage IV GENE             | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Dell     | 0C522T A00                  | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell     | 0C522T A00                  | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| MSI      | MPG B550 GAMING EDGE WIF... | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Gigabyte | A320M-S2H-CF                | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel    | X79Turbo V1.x               | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| AMI      | Cherry Trail CR             | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| AMI      | Cherry Trail CR             | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| ASUSTek  | Rampage IV GENE             | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| ASUSTek  | Rampage IV GENE             | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| ASUSTek  | P8H61-M LX3 R2.0            | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| AOpen    | D1009 A1A4                  | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| MSI      | B85I                        | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| ASRock   | B450M Pro4                  | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| Gigabyte | B150N Phoenix-WIFI-CF       | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar  | N68S3B                      | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| ASUSTek  | M11AD                       | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Biostar  | H61MLV2                     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP       | 2ADC                        | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI      | B85I                        | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Dell     | 0PU052                      | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell     | 0PU052                      | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| HP       | 1589                        | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| HP       | 802E                        | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| ASRock   | FM2A58M-DG3+                | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| HP       | 805D                        | [2a09665009](https://linux-hardware.org/?probe=2a09665009) | Mar 02, 2022 |
| ASUSTek  | M4N72-E                     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek  | H81-PLUS                    | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| Gigabyte | X470 AORUS ULTRA GAMING-... | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| Gigabyte | Z390 UD                     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| MSI      | B85I                        | [24674e9e3a](https://linux-hardware.org/?probe=24674e9e3a) | Feb 20, 2022 |
| Intel    | DH61BE AAG14062-210         | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| MSI      | B85I                        | [633f6bf495](https://linux-hardware.org/?probe=633f6bf495) | Feb 19, 2022 |
| ASUSTek  | M11AD                       | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| ASUSTek  | P5B                         | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel    | H61                         | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| ASUSTek  | PRIME Z590-A                | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar  | A68MD PRO                   | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| MSI      | B85I                        | [28c1f1b8ae](https://linux-hardware.org/?probe=28c1f1b8ae) | Feb 13, 2022 |
| ASUSTek  | PRIME Z590-A                | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| MSI      | B85I                        | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Gigabyte | F2A68HM-H                   | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Gigabyte | F2A68HM-H                   | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| ASUSTek  | PRIME A320M-K               | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek  | PRIME B360M-K               | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| ASUSTek  | H110M-C                     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| MSI      | B450I GAMING PLUS AC        | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| ECS      | H55H-M                      | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| ASUSTek  | ROG STRIX B360-H GAMING     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Lenovo   | NO DPK                      | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| HP       | 802E                        | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| ASUSTek  | H110M-C                     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek  | P5B                         | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn  | NETBOX nT-435/535 Ver       | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn  | NETBOX nT-435/535 Ver       | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP       | ProLiant ML110 G7           | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| ASUSTek  | H110M-C                     | [4d2233f824](https://linux-hardware.org/?probe=4d2233f824) | Feb 03, 2022 |
| HP       | 339A                        | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| Unknown  | Unknown                     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| HP       | 805D                        | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| ASUSTek  | H110I-PLUS                  | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte | B75M-D3H                    | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| MSI      | Z270 KRAIT GAMING           | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Gigabyte | H61M-DS2                    | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| ASRock   | H61M-HVS                    | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock   | H61M-HVS                    | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer     | ConceptD CM100-51A V:1.1    | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| FIRICH   | J1900                       | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| ASUSTek  | ROG STRIX B360-H GAMING     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| ASUSTek  | ROG STRIX X570-E GAMING     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| ASUSTek  | TUF B365M-PLUS GAMING       | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI      | B450 TOMAHAWK MAX II        | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| MSI      | B450M-A PRO MAX             | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| ASUSTek  | H61M-CS                     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| Unknown  | T3 MRD                      | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI      | X470 GAMING PLUS MAX        | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek  | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Foxconn  | 2AB1                        | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| Foxconn  | 2AB1                        | [de61623232](https://linux-hardware.org/?probe=de61623232) | Jan 11, 2022 |
| ASUSTek  | H110M-C                     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Gigabyte | X570 AORUS ELITE            | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| HP       | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte | GA-970A-D3                  | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock   | Z370 Pro4                   | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| ASRock   | B450M-HDV R4.0              | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Gigabyte | B85M-DS3H-A                 | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| MSI      | 2A9C                        | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| HP       | 3397                        | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek  | X79-DELUXE                  | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| HP       | 1589                        | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn  | 2AB1                        | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Gigabyte | Z390 UD                     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| Apple    | Mac-F42C88C8 Proto1         | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| ASUSTek  | H97-PLUS                    | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| MSI      | B450-A PRO MAX              | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte | H310M S2P                   | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Foxconn  | 2AB1                        | [d9077a5d94](https://linux-hardware.org/?probe=d9077a5d94) | Dec 18, 2021 |
| Foxconn  | 2AB1                        | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Gigabyte | Z590 AORUS ELITE AX         | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| ASUSTek  | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.11.0-43-generic    | 24       | 21.62%  |
| 5.13.0-39-generic    | 16       | 14.41%  |
| 5.13.0-28-generic    | 16       | 14.41%  |
| 5.13.0-30-generic    | 10       | 9.01%   |
| 5.13.0-27-generic    | 9        | 8.11%   |
| 5.13.0-35-generic    | 7        | 6.31%   |
| 5.13.0-40-generic    | 6        | 5.41%   |
| 5.13.0-37-generic    | 5        | 4.5%    |
| 5.11.0-41-generic    | 5        | 4.5%    |
| 5.11.0-44-generic    | 4        | 3.6%    |
| 5.13.0-25-generic    | 2        | 1.8%    |
| 5.11.0-46-generic    | 2        | 1.8%    |
| 5.13.0-28-lowlatency | 1        | 0.9%    |
| 5.13.0-22-generic    | 1        | 0.9%    |
| 5.11.0-43-lowlatency | 1        | 0.9%    |
| 5.11.0-40-generic    | 1        | 0.9%    |
| 5.11.0-37-generic    | 1        | 0.9%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 67       | 65.05%  |
| 5.11.0  | 36       | 34.95%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 67       | 65.05%  |
| 5.11    | 36       | 34.95%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 101      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 101      | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 101      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 87       | 86.14%  |
| LightDM | 14       | 13.86%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 39       | 38.61%  |
| de_DE | 15       | 14.85%  |
| es_ES | 10       | 9.9%    |
| fr_FR | 7        | 6.93%   |
| en_GB | 7        | 6.93%   |
| ru_RU | 4        | 3.96%   |
| it_IT | 4        | 3.96%   |
| pl_PL | 3        | 2.97%   |
| tr_TR | 2        | 1.98%   |
| pt_BR | 2        | 1.98%   |
| ja_JP | 2        | 1.98%   |
| uk_UA | 1        | 0.99%   |
| sr_RS | 1        | 0.99%   |
| pt_PT | 1        | 0.99%   |
| fr_CA | 1        | 0.99%   |
| en_CA | 1        | 0.99%   |
| en_AU | 1        | 0.99%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 57       | 56.44%  |
| BIOS | 44       | 43.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 98       | 97.03%  |
| Btrfs | 2        | 1.98%   |
| Xfs   | 1        | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 91       | 90.1%   |
| GPT     | 8        | 7.92%   |
| MBR     | 2        | 1.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 96.04%  |
| Yes       | 4        | 3.96%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 96.04%  |
| Yes       | 4        | 3.96%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 28       | 27.72%  |
| Gigabyte Technology | 15       | 14.85%  |
| MSI                 | 13       | 12.87%  |
| Hewlett-Packard     | 10       | 9.9%    |
| ASRock              | 7        | 6.93%   |
| Dell                | 5        | 4.95%   |
| Lenovo              | 3        | 2.97%   |
| Intel               | 3        | 2.97%   |
| Biostar             | 3        | 2.97%   |
| Foxconn             | 2        | 1.98%   |
| ECS                 | 2        | 1.98%   |
| Unknown             | 2        | 1.98%   |
| Pegatron            | 1        | 0.99%   |
| Fujitsu             | 1        | 0.99%   |
| FIRICH              | 1        | 0.99%   |
| AZW                 | 1        | 0.99%   |
| Apple               | 1        | 0.99%   |
| AOpen               | 1        | 0.99%   |
| AMI                 | 1        | 0.99%   |
| Acer                | 1        | 0.99%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS All Series                         | 3        | 2.97%   |
| Gigabyte Z390 UD                        | 2        | 1.98%   |
| ASUS TUF GAMING B550M-PLUS              | 2        | 1.98%   |
| Unknown                                 | 2        | 1.98%   |
| Pegatron IPMH61P1                       | 1        | 0.99%   |
| MSI PPPPP-CCC#MMMMMMMM                  | 1        | 0.99%   |
| MSI MS-7C91                             | 1        | 0.99%   |
| MSI MS-7C52                             | 1        | 0.99%   |
| MSI MS-7C35                             | 1        | 0.99%   |
| MSI MS-7C02                             | 1        | 0.99%   |
| MSI MS-7B86                             | 1        | 0.99%   |
| MSI MS-7B79                             | 1        | 0.99%   |
| MSI MS-7A59                             | 1        | 0.99%   |
| MSI MS-7A40                             | 1        | 0.99%   |
| MSI MS-7A38                             | 1        | 0.99%   |
| MSI MS-7918                             | 1        | 0.99%   |
| MSI MS-7885                             | 1        | 0.99%   |
| MSI MS-7851                             | 1        | 0.99%   |
| Lenovo ThinkCentre M72e 3664AD7         | 1        | 0.99%   |
| Lenovo ThinkCentre M58 6258D3G          | 1        | 0.99%   |
| Lenovo IdeaCentre 510S-07ICK 90LX006TGE | 1        | 0.99%   |
| Intel X79                               | 1        | 0.99%   |
| Intel H61                               | 1        | 0.99%   |
| Intel DH61BE AAG14062-210               | 1        | 0.99%   |
| HP Z420 Workstation                     | 1        | 0.99%   |
| HP Z240 SFF Workstation                 | 1        | 0.99%   |
| HP Z200 SFF Workstation                 | 1        | 0.99%   |
| HP ProLiant ML110 G7                    | 1        | 0.99%   |
| HP ProDesk 600 G5 SFF                   | 1        | 0.99%   |
| HP ProDesk 600 G2 SFF                   | 1        | 0.99%   |
| HP Compaq Pro 6300 MT                   | 1        | 0.99%   |
| HP Compaq Elite 8300 SFF                | 1        | 0.99%   |
| HP Compaq 8200 Elite CMT PC             | 1        | 0.99%   |
| HP 520-1175a                            | 1        | 0.99%   |
| Gigabyte Z590 AORUS ELITE AX            | 1        | 0.99%   |
| Gigabyte X570 AORUS ELITE               | 1        | 0.99%   |
| Gigabyte X470 AORUS ULTRA GAMING        | 1        | 0.99%   |
| Gigabyte H61M-DS2                       | 1        | 0.99%   |
| Gigabyte H61M-D2H-USB3                  | 1        | 0.99%   |
| Gigabyte H310M S2P 2.0                  | 1        | 0.99%   |
| Gigabyte GA-970A-D3                     | 1        | 0.99%   |
| Gigabyte F2A68HM-H                      | 1        | 0.99%   |
| Gigabyte B85M-DS3H-A                    | 1        | 0.99%   |
| Gigabyte B75M-D3H                       | 1        | 0.99%   |
| Gigabyte B450 AORUS ELITE               | 1        | 0.99%   |
| Gigabyte B150N Phoenix-WIFI             | 1        | 0.99%   |
| Gigabyte A320M-S2H                      | 1        | 0.99%   |
| Fujitsu ESPRIMO D757                    | 1        | 0.99%   |
| Foxconn p6616f                          | 1        | 0.99%   |
| Foxconn nT435/nT535                     | 1        | 0.99%   |
| FIRICH J1900                            | 1        | 0.99%   |
| ECS H61H2-MV                            | 1        | 0.99%   |
| ECS H55H-M                              | 1        | 0.99%   |
| Dell Precision Tower 5810               | 1        | 0.99%   |
| Dell OptiPlex 980                       | 1        | 0.99%   |
| Dell OptiPlex 9010                      | 1        | 0.99%   |
| Dell OptiPlex 790                       | 1        | 0.99%   |
| Dell OptiPlex 755                       | 1        | 0.99%   |
| Biostar N68S3B                          | 1        | 0.99%   |
| Biostar H61MLV2                         | 1        | 0.99%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS TUF               | 5        | 4.95%   |
| Dell OptiPlex          | 4        | 3.96%   |
| ASUS ROG               | 4        | 3.96%   |
| ASUS PRIME             | 4        | 3.96%   |
| HP Compaq              | 3        | 2.97%   |
| ASUS All               | 3        | 2.97%   |
| Lenovo ThinkCentre     | 2        | 1.98%   |
| HP ProDesk             | 2        | 1.98%   |
| Gigabyte Z390          | 2        | 1.98%   |
| Unknown                | 2        | 1.98%   |
| Pegatron IPMH61P1      | 1        | 0.99%   |
| MSI PPPPP-CCC#MMMMMMMM | 1        | 0.99%   |
| MSI MS-7C91            | 1        | 0.99%   |
| MSI MS-7C52            | 1        | 0.99%   |
| MSI MS-7C35            | 1        | 0.99%   |
| MSI MS-7C02            | 1        | 0.99%   |
| MSI MS-7B86            | 1        | 0.99%   |
| MSI MS-7B79            | 1        | 0.99%   |
| MSI MS-7A59            | 1        | 0.99%   |
| MSI MS-7A40            | 1        | 0.99%   |
| MSI MS-7A38            | 1        | 0.99%   |
| MSI MS-7918            | 1        | 0.99%   |
| MSI MS-7885            | 1        | 0.99%   |
| MSI MS-7851            | 1        | 0.99%   |
| Lenovo IdeaCentre      | 1        | 0.99%   |
| Intel X79              | 1        | 0.99%   |
| Intel H61              | 1        | 0.99%   |
| Intel DH61BE           | 1        | 0.99%   |
| HP Z420                | 1        | 0.99%   |
| HP Z240                | 1        | 0.99%   |
| HP Z200                | 1        | 0.99%   |
| HP ProLiant            | 1        | 0.99%   |
| HP 520-1175a           | 1        | 0.99%   |
| Gigabyte Z590          | 1        | 0.99%   |
| Gigabyte X570          | 1        | 0.99%   |
| Gigabyte X470          | 1        | 0.99%   |
| Gigabyte H61M-DS2      | 1        | 0.99%   |
| Gigabyte H61M-D2H-USB3 | 1        | 0.99%   |
| Gigabyte H310M         | 1        | 0.99%   |
| Gigabyte GA-970A-D3    | 1        | 0.99%   |
| Gigabyte F2A68HM-H     | 1        | 0.99%   |
| Gigabyte B85M-DS3H-A   | 1        | 0.99%   |
| Gigabyte B75M-D3H      | 1        | 0.99%   |
| Gigabyte B450          | 1        | 0.99%   |
| Gigabyte B150N         | 1        | 0.99%   |
| Gigabyte A320M-S2H     | 1        | 0.99%   |
| Fujitsu ESPRIMO        | 1        | 0.99%   |
| Foxconn p6616f         | 1        | 0.99%   |
| Foxconn nT435          | 1        | 0.99%   |
| FIRICH J1900           | 1        | 0.99%   |
| ECS H61H2-MV           | 1        | 0.99%   |
| ECS H55H-M             | 1        | 0.99%   |
| Dell Precision         | 1        | 0.99%   |
| Biostar N68S3B         | 1        | 0.99%   |
| Biostar H61MLV2        | 1        | 0.99%   |
| Biostar A68MD          | 1        | 0.99%   |
| AZW GTi                | 1        | 0.99%   |
| ASUS X79-DELUXE        | 1        | 0.99%   |
| ASUS STRIKER           | 1        | 0.99%   |
| ASUS Rampage           | 1        | 0.99%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 14       | 13.86%  |
| 2018 | 13       | 12.87%  |
| 2019 | 10       | 9.9%    |
| 2011 | 9        | 8.91%   |
| 2021 | 8        | 7.92%   |
| 2020 | 8        | 7.92%   |
| 2015 | 7        | 6.93%   |
| 2014 | 7        | 6.93%   |
| 2010 | 7        | 6.93%   |
| 2013 | 6        | 5.94%   |
| 2017 | 4        | 3.96%   |
| 2016 | 3        | 2.97%   |
| 2022 | 1        | 0.99%   |
| 2009 | 1        | 0.99%   |
| 2008 | 1        | 0.99%   |
| 2007 | 1        | 0.99%   |
| 2006 | 1        | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 101      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 96       | 95.05%  |
| Enabled  | 5        | 4.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 101      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 25       | 24.51%  |
| 32.01-64.0  | 21       | 20.59%  |
| 8.01-16.0   | 20       | 19.61%  |
| 4.01-8.0    | 17       | 16.67%  |
| 3.01-4.0    | 11       | 10.78%  |
| 64.01-256.0 | 3        | 2.94%   |
| 24.01-32.0  | 2        | 1.96%   |
| 1.01-2.0    | 2        | 1.96%   |
| 2.01-3.0    | 1        | 0.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 44       | 39.64%  |
| 2.01-3.0  | 33       | 29.73%  |
| 4.01-8.0  | 16       | 14.41%  |
| 3.01-4.0  | 13       | 11.71%  |
| 8.01-16.0 | 4        | 3.6%    |
| 0.51-1.0  | 1        | 0.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 36       | 34.95%  |
| 2      | 34       | 33.01%  |
| 3      | 13       | 12.62%  |
| 4      | 11       | 10.68%  |
| 5      | 5        | 4.85%   |
| 7      | 2        | 1.94%   |
| 6      | 2        | 1.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 56.86%  |
| Yes       | 44       | 43.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 101      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 50.5%   |
| Yes       | 50       | 49.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 63.37%  |
| Yes       | 37       | 36.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 15       | 14.85%  |
| USA          | 9        | 8.91%   |
| UK           | 8        | 7.92%   |
| Spain        | 8        | 7.92%   |
| France       | 6        | 5.94%   |
| Russia       | 4        | 3.96%   |
| Poland       | 4        | 3.96%   |
| Italy        | 4        | 3.96%   |
| Japan        | 3        | 2.97%   |
| Indonesia    | 3        | 2.97%   |
| India        | 3        | 2.97%   |
| Canada       | 3        | 2.97%   |
| Brazil       | 3        | 2.97%   |
| Australia    | 3        | 2.97%   |
| Turkey       | 2        | 1.98%   |
| Switzerland  | 2        | 1.98%   |
| Iran         | 2        | 1.98%   |
| Austria      | 2        | 1.98%   |
| Argentina    | 2        | 1.98%   |
| Thailand     | 1        | 0.99%   |
| Sweden       | 1        | 0.99%   |
| Sri Lanka    | 1        | 0.99%   |
| South Africa | 1        | 0.99%   |
| Serbia       | 1        | 0.99%   |
| Romania      | 1        | 0.99%   |
| Norway       | 1        | 0.99%   |
| New Zealand  | 1        | 0.99%   |
| Netherlands  | 1        | 0.99%   |
| Mexico       | 1        | 0.99%   |
| Malaysia     | 1        | 0.99%   |
| Lithuania    | 1        | 0.99%   |
| Hong Kong    | 1        | 0.99%   |
| Egypt        | 1        | 0.99%   |
| Czechia      | 1        | 0.99%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Warsaw                  | 3        | 2.78%   |
| Hamburg                 | 3        | 2.78%   |
| Brisbane                | 2        | 1.85%   |
| Znojmo                  | 1        | 0.93%   |
| Yokohama                | 1        | 0.93%   |
| Wroclaw                 | 1        | 0.93%   |
| Woolloongabba           | 1        | 0.93%   |
| Wolgast                 | 1        | 0.93%   |
| Wattala                 | 1        | 0.93%   |
| Vilanova i la GeltrÃº | 1        | 0.93%   |
| Vienna                  | 1        | 0.93%   |
| Vanse                   | 1        | 0.93%   |
| Uppsala                 | 1        | 0.93%   |
| Tournus                 | 1        | 0.93%   |
| Toronto                 | 1        | 0.93%   |
| Thrissur                | 1        | 0.93%   |
| Tehran                  | 1        | 0.93%   |
| Tangerang               | 1        | 0.93%   |
| Sydney                  | 1        | 0.93%   |
| Suresnes                | 1        | 0.93%   |
| Spello                  | 1        | 0.93%   |
| Southampton             | 1        | 0.93%   |
| Sornay                  | 1        | 0.93%   |
| Sentmenat               | 1        | 0.93%   |
| Sarrebourg              | 1        | 0.93%   |
| Sao Paulo               | 1        | 0.93%   |
| Saguenay                | 1        | 0.93%   |
| Russell                 | 1        | 0.93%   |
| Rueso                   | 1        | 0.93%   |
| Rotterdam               | 1        | 0.93%   |
| Revere                  | 1        | 0.93%   |
| Pune                    | 1        | 0.93%   |
| Plano                   | 1        | 0.93%   |
| Paris                   | 1        | 0.93%   |
| Oldham                  | 1        | 0.93%   |
| Oldenburg               | 1        | 0.93%   |
| Nuremberg               | 1        | 0.93%   |
| Novi Sad                | 1        | 0.93%   |
| Neubrandenburg          | 1        | 0.93%   |
| Muralto                 | 1        | 0.93%   |
| Munich                  | 1        | 0.93%   |
| Moscow                  | 1        | 0.93%   |
| Monmouth                | 1        | 0.93%   |
| Milan                   | 1        | 0.93%   |
| McKinney                | 1        | 0.93%   |
| MÃ¡laga               | 1        | 0.93%   |
| Madrid                  | 1        | 0.93%   |
| MaÅ¾eikiai            | 1        | 0.93%   |
| Lyngdal                 | 1        | 0.93%   |
| London                  | 1        | 0.93%   |
| Lauterbach              | 1        | 0.93%   |
| Lasino                  | 1        | 0.93%   |
| Las Rozas de Madrid     | 1        | 0.93%   |
| Larnage                 | 1        | 0.93%   |
| La Plata                | 1        | 0.93%   |
| Krenglbach              | 1        | 0.93%   |
| Krasnodar               | 1        | 0.93%   |
| Kobe                    | 1        | 0.93%   |
| Kingston                | 1        | 0.93%   |
| Kilchberg               | 1        | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 32       | 44     | 16.75%  |
| Seagate                   | 30       | 39     | 15.71%  |
| Samsung Electronics       | 26       | 38     | 13.61%  |
| Kingston                  | 21       | 25     | 10.99%  |
| Toshiba                   | 13       | 16     | 6.81%   |
| Crucial                   | 8        | 10     | 4.19%   |
| Unknown                   | 5        | 12     | 2.62%   |
| SanDisk                   | 5        | 7      | 2.62%   |
| Micron/Crucial Technology | 5        | 7      | 2.62%   |
| Intel                     | 5        | 5      | 2.62%   |
| Hitachi                   | 4        | 4      | 2.09%   |
| A-DATA Technology         | 4        | 4      | 2.09%   |
| PNY                       | 3        | 5      | 1.57%   |
| Phison                    | 3        | 3      | 1.57%   |
| Micron Technology         | 3        | 3      | 1.57%   |
| MAXTOR                    | 3        | 3      | 1.57%   |
| ASMT                      | 3        | 3      | 1.57%   |
| Team                      | 2        | 2      | 1.05%   |
| PLEXTOR                   | 2        | 2      | 1.05%   |
| XPG                       | 1        | 1      | 0.52%   |
| Transcend                 | 1        | 1      | 0.52%   |
| Realtek Semiconductor     | 1        | 1      | 0.52%   |
| OCZ                       | 1        | 1      | 0.52%   |
| Netac                     | 1        | 1      | 0.52%   |
| MidasForce                | 1        | 1      | 0.52%   |
| LITEON                    | 1        | 1      | 0.52%   |
| Leven                     | 1        | 1      | 0.52%   |
| JMicron                   | 1        | 1      | 0.52%   |
| Intenso                   | 1        | 1      | 0.52%   |
| Hewlett-Packard           | 1        | 1      | 0.52%   |
| GOODRAM                   | 1        | 1      | 0.52%   |
| Gigabyte Technology       | 1        | 1      | 0.52%   |
| Corsair                   | 1        | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB       | 5        | 2.33%   |
| Toshiba DT01ACA050 500GB           | 4        | 1.86%   |
| Micron/Crucial NVMe SSD Drive 1TB  | 4        | 1.86%   |
| Kingston SA400S37120G 120GB SSD    | 4        | 1.86%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 3        | 1.4%    |
| Seagate ST3500418AS 500GB          | 3        | 1.4%    |
| Samsung SSD 860 EVO 250GB          | 3        | 1.4%    |
| Kingston SA400S37240G 240GB SSD    | 3        | 1.4%    |
| Kingston NVMe SSD Drive 1TB        | 3        | 1.4%    |
| Crucial CT240BX500SSD1 240GB       | 3        | 1.4%    |
| WDC WD40EFRX-68N32N0 4TB           | 2        | 0.93%   |
| WDC WD10EZEX-00BN5A0 1TB           | 2        | 0.93%   |
| Unknown SD/MMC 16GB                | 2        | 0.93%   |
| Unknown M.S./M.S.Pro/HG 16GB       | 2        | 0.93%   |
| Toshiba HDWD110 1TB                | 2        | 0.93%   |
| Seagate ST2000DX002-2DV164 2TB     | 2        | 0.93%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 0.93%   |
| Seagate ST1000DM003-1ER162 1TB     | 2        | 0.93%   |
| Samsung SSD 850 EVO 250GB          | 2        | 0.93%   |
| Samsung SSD 840 EVO 120GB          | 2        | 0.93%   |
| Samsung NVMe SSD Drive 1TB         | 2        | 0.93%   |
| Samsung HD322HJ 320GB              | 2        | 0.93%   |
| PNY CS900 480GB SSD                | 2        | 0.93%   |
| Phison NVMe SSD Drive 1TB          | 2        | 0.93%   |
| Kingston SV300S37A120G 120GB SSD   | 2        | 0.93%   |
| Kingston SA400S37960G 960GB SSD    | 2        | 0.93%   |
| Kingston NVMe SSD Drive 500GB      | 2        | 0.93%   |
| Crucial CT1000MX500SSD1 1TB        | 2        | 0.93%   |
| XPG NVMe SSD Drive 512GB           | 1        | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.47%   |
| WDC WDS500G1B0A-00H9H0 500GB SSD   | 1        | 0.47%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD   | 1        | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1        | 0.47%   |
| WDC WD6401AALS-00L3B2 640GB        | 1        | 0.47%   |
| WDC WD5000LPLX-60ZNTT2 500GB       | 1        | 0.47%   |
| WDC WD5000AVDS-63U7B1 500GB        | 1        | 0.47%   |
| WDC WD5000AAKX-003CA0 500GB        | 1        | 0.47%   |
| WDC WD5000AAKX-001CA0 500GB        | 1        | 0.47%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 1        | 0.47%   |
| WDC WD5000AAKS-00A7B2 500GB        | 1        | 0.47%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1        | 0.47%   |
| WDC WD3200AVJS-63B6A0 320GB        | 1        | 0.47%   |
| WDC WD3200AAJS-00L7A0 320GB        | 1        | 0.47%   |
| WDC WD30PURX-64P6ZY0 3TB           | 1        | 0.47%   |
| WDC WD30EZRX-00SPEB0 3TB           | 1        | 0.47%   |
| WDC WD3003FZEX-00Z4SA0 3TB         | 1        | 0.47%   |
| WDC WD2500JS-23MHB0 250GB          | 1        | 0.47%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 0.47%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 0.47%   |
| WDC WD1600JS-55NCB1 160GB          | 1        | 0.47%   |
| WDC WD15EARX-00PASB0 1TB           | 1        | 0.47%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1        | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 0.47%   |
| WDC WD10EZEX-08M2NA0 1TB           | 1        | 0.47%   |
| WDC WD10EZEX-00ZF5A0 1TB           | 1        | 0.47%   |
| WDC WD10EZEX-00UD2A0 1TB           | 1        | 0.47%   |
| WDC WD10EADS-00L5B1 1TB            | 1        | 0.47%   |
| WDC SSC-D0064SC-2100 64GB          | 1        | 0.47%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB | 1        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 33     | 33.75%  |
| Seagate             | 27       | 36     | 33.75%  |
| Toshiba             | 12       | 15     | 15%     |
| Samsung Electronics | 4        | 5      | 5%      |
| Hitachi             | 4        | 4      | 5%      |
| MAXTOR              | 2        | 2      | 2.5%    |
| ASMT                | 2        | 2      | 2.5%    |
| Unknown             | 1        | 1      | 1.25%   |
| Hewlett-Packard     | 1        | 1      | 1.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 16       | 21     | 20.78%  |
| Kingston            | 16       | 19     | 20.78%  |
| Crucial             | 8        | 10     | 10.39%  |
| WDC                 | 5        | 9      | 6.49%   |
| SanDisk             | 5        | 6      | 6.49%   |
| PNY                 | 3        | 5      | 3.9%    |
| Intel               | 3        | 3      | 3.9%    |
| A-DATA Technology   | 3        | 3      | 3.9%    |
| Team                | 2        | 2      | 2.6%    |
| PLEXTOR             | 2        | 2      | 2.6%    |
| Micron Technology   | 2        | 2      | 2.6%    |
| Transcend           | 1        | 1      | 1.3%    |
| Toshiba             | 1        | 1      | 1.3%    |
| Seagate             | 1        | 1      | 1.3%    |
| OCZ                 | 1        | 1      | 1.3%    |
| MidasForce          | 1        | 1      | 1.3%    |
| MAXTOR              | 1        | 1      | 1.3%    |
| LITEON              | 1        | 1      | 1.3%    |
| Leven               | 1        | 1      | 1.3%    |
| Intenso             | 1        | 1      | 1.3%    |
| GOODRAM             | 1        | 1      | 1.3%    |
| Gigabyte Technology | 1        | 1      | 1.3%    |
| Corsair             | 1        | 1      | 1.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 66       | 94     | 39.76%  |
| HDD     | 64       | 99     | 38.55%  |
| NVMe    | 28       | 38     | 16.87%  |
| Unknown | 6        | 13     | 3.61%   |
| MMC     | 2        | 2      | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 93       | 189    | 70.45%  |
| NVMe | 28       | 38     | 21.21%  |
| SAS  | 9        | 17     | 6.82%   |
| MMC  | 2        | 2      | 1.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 72       | 121    | 58.06%  |
| 0.51-1.0   | 28       | 44     | 22.58%  |
| 1.01-2.0   | 9        | 10     | 7.26%   |
| 3.01-4.0   | 7        | 8      | 5.65%   |
| 2.01-3.0   | 4        | 6      | 3.23%   |
| 4.01-10.0  | 4        | 4      | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 32       | 30.48%  |
| 251-500        | 25       | 23.81%  |
| 501-1000       | 20       | 19.05%  |
| More than 3000 | 8        | 7.62%   |
| 1001-2000      | 8        | 7.62%   |
| 51-100         | 8        | 7.62%   |
| 21-50          | 3        | 2.86%   |
| 2001-3000      | 1        | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 45       | 40.91%  |
| 21-50          | 17       | 15.45%  |
| 101-250        | 16       | 14.55%  |
| 251-500        | 9        | 8.18%   |
| 51-100         | 9        | 8.18%   |
| 501-1000       | 7        | 6.36%   |
| 1001-2000      | 4        | 3.64%   |
| More than 3000 | 2        | 1.82%   |
| 2001-3000      | 1        | 0.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500312CS 500GB | 1        | 1      | 50%     |
| SanDisk SSD PLUS 240GB    | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 50%     |
| SanDisk | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 50%     |
| HDD  | 1        | 1      | 50%     |

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
| Detected | 93       | 224    | 89.42%  |
| Works    | 9        | 20     | 8.65%   |
| Malfunc  | 2        | 2      | 1.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 71       | 50.71%  |
| AMD                         | 26       | 18.57%  |
| Samsung Electronics         | 10       | 7.14%   |
| Kingston Technology Company | 6        | 4.29%   |
| Micron/Crucial Technology   | 5        | 3.57%   |
| ASMedia Technology          | 4        | 2.86%   |
| Phison Electronics          | 3        | 2.14%   |
| Nvidia                      | 3        | 2.14%   |
| Marvell Technology Group    | 3        | 2.14%   |
| Seagate Technology          | 2        | 1.43%   |
| Sandisk                     | 2        | 1.43%   |
| Realtek Semiconductor       | 2        | 1.43%   |
| Micron Technology           | 1        | 0.71%   |
| JMicron Technology          | 1        | 0.71%   |
| ADATA Technology            | 1        | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 8.14%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 6.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 5.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 4.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 3.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 2.91%   |
| Kingston Company A2000 NVMe SSD                                                         | 5        | 2.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 2.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 2.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.91%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 4        | 2.33%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 2.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.74%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.74%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.16%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 1.16%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.16%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.16%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 1.16%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.16%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.16%   |
| Seagate FireCuda 530 SSD                                                                | 1        | 0.58%   |
| Seagate FireCuda 510 SSD                                                                | 1        | 0.58%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.58%   |
| Sandisk Non-Volatile memory controller                                                  | 1        | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.58%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.58%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.58%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.58%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.58%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 0.58%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 0.58%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.58%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.58%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.58%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.58%   |
| Micron/Crucial Non-Volatile memory controller                                           | 1        | 0.58%   |
| Micron Non-Volatile memory controller                                                   | 1        | 0.58%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.58%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                      | 1        | 0.58%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.58%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1        | 0.58%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1        | 0.58%   |
| Intel SSD 660P Series                                                                   | 1        | 0.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.58%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.58%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.58%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.58%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.58%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.58%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.58%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 0.58%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 84       | 60.43%  |
| NVMe | 28       | 20.14%  |
| IDE  | 22       | 15.83%  |
| RAID | 4        | 2.88%   |
| SAS  | 1        | 0.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 73       | 72.28%  |
| AMD    | 28       | 27.72%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz        | 4        | 3.96%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 4        | 3.96%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3        | 2.97%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 3        | 2.97%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 2        | 1.98%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2        | 1.98%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2        | 1.98%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 2        | 1.98%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 2        | 1.98%   |
| Intel Core i3 CPU 530 @ 2.93GHz         | 2        | 1.98%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 2        | 1.98%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2        | 1.98%   |
| AMD Ryzen 5 2600X Six-Core Processor    | 2        | 1.98%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 2        | 1.98%   |
| Intel Xeon CPU E5462 @ 2.80GHz          | 1        | 0.99%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1        | 0.99%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz      | 1        | 0.99%   |
| Intel Xeon CPU E5-1660 0 @ 3.30GHz      | 1        | 0.99%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz     | 1        | 0.99%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz     | 1        | 0.99%   |
| Intel Xeon CPU E31270 @ 3.40GHz         | 1        | 0.99%   |
| Intel Xeon CPU E31240 @ 3.30GHz         | 1        | 0.99%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz     | 1        | 0.99%   |
| Intel Pentium CPU G630 @ 2.70GHz        | 1        | 0.99%   |
| Intel Pentium CPU G620 @ 2.60GHz        | 1        | 0.99%   |
| Intel Pentium CPU G2030 @ 3.00GHz       | 1        | 0.99%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 1        | 0.99%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 1        | 0.99%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1        | 0.99%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1        | 0.99%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1        | 0.99%   |
| Intel Core i7-4930K CPU @ 3.40GHz       | 1        | 0.99%   |
| Intel Core i7-4790S CPU @ 3.20GHz       | 1        | 0.99%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 1        | 0.99%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1        | 0.99%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 1        | 0.99%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1        | 0.99%   |
| Intel Core i7-10700K CPU @ 3.80GHz      | 1        | 0.99%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1        | 0.99%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 1        | 0.99%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 1        | 0.99%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 1        | 0.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1        | 0.99%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 1        | 0.99%   |
| Intel Core i5-10400 CPU @ 2.90GHz       | 1        | 0.99%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 1        | 0.99%   |
| Intel Core i3-9100F CPU @ 3.60GHz       | 1        | 0.99%   |
| Intel Core i3-9100 CPU @ 3.60GHz        | 1        | 0.99%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 1        | 0.99%   |
| Intel Core i3-6100 CPU @ 3.70GHz        | 1        | 0.99%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 1        | 0.99%   |
| Intel Core i3-3220 CPU @ 3.30GHz        | 1        | 0.99%   |
| Intel Core i3 CPU 550 @ 3.20GHz         | 1        | 0.99%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz   | 1        | 0.99%   |
| Intel Core 2 Quad CPU @ 2.40GHz         | 1        | 0.99%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 1        | 0.99%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz    | 1        | 0.99%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 1        | 0.99%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 1        | 0.99%   |
| Intel Celeron CPU G530 @ 2.40GHz        | 1        | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 19       | 18.81%  |
| Intel Core i7     | 15       | 14.85%  |
| Intel Core i3     | 11       | 10.89%  |
| Intel Xeon        | 9        | 8.91%   |
| AMD Ryzen 5       | 8        | 7.92%   |
| AMD Ryzen 7       | 6        | 5.94%   |
| Other             | 4        | 3.96%   |
| Intel Celeron     | 4        | 3.96%   |
| Intel Pentium     | 3        | 2.97%   |
| Intel Atom        | 3        | 2.97%   |
| AMD Ryzen 9       | 3        | 2.97%   |
| AMD Phenom II X4  | 3        | 2.97%   |
| Intel Core 2 Quad | 2        | 1.98%   |
| Intel Core 2 Duo  | 2        | 1.98%   |
| AMD Athlon        | 2        | 1.98%   |
| Intel Core i9     | 1        | 0.99%   |
| AMD Ryzen 3       | 1        | 0.99%   |
| AMD FX            | 1        | 0.99%   |
| AMD Athlon X4     | 1        | 0.99%   |
| AMD Athlon II X2  | 1        | 0.99%   |
| AMD A8            | 1        | 0.99%   |
| AMD A10           | 1        | 0.99%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 40       | 39.6%   |
| 2      | 25       | 24.75%  |
| 8      | 17       | 16.83%  |
| 6      | 15       | 14.85%  |
| 12     | 3        | 2.97%   |
| 1      | 1        | 0.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 100      | 99.01%  |
| 2      | 1        | 0.99%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 60       | 59.41%  |
| 1      | 41       | 40.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 101      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 12       | 11.88%  |
| 0x306c3    | 8        | 7.92%   |
| 0x306a9    | 8        | 7.92%   |
| 0x08701021 | 6        | 5.94%   |
| Unknown    | 5        | 4.95%   |
| 0x506e3    | 4        | 3.96%   |
| 0xa0671    | 3        | 2.97%   |
| 0x906ed    | 3        | 2.97%   |
| 0x906eb    | 3        | 2.97%   |
| 0x906ea    | 3        | 2.97%   |
| 0x906e9    | 3        | 2.97%   |
| 0x206d7    | 3        | 2.97%   |
| 0x08108109 | 3        | 2.97%   |
| 0x0800820d | 3        | 2.97%   |
| 0x406c4    | 2        | 1.98%   |
| 0x20655    | 2        | 1.98%   |
| 0x20652    | 2        | 1.98%   |
| 0x1067a    | 2        | 1.98%   |
| 0x06003106 | 2        | 1.98%   |
| 0x010000c8 | 2        | 1.98%   |
| 0xa0655    | 1        | 0.99%   |
| 0xa0653    | 1        | 0.99%   |
| 0x906ec    | 1        | 0.99%   |
| 0x806c1    | 1        | 0.99%   |
| 0x706a8    | 1        | 0.99%   |
| 0x6fb      | 1        | 0.99%   |
| 0x6f7      | 1        | 0.99%   |
| 0x306f2    | 1        | 0.99%   |
| 0x306e4    | 1        | 0.99%   |
| 0x30678    | 1        | 0.99%   |
| 0x106ca    | 1        | 0.99%   |
| 0x10676    | 1        | 0.99%   |
| 0x0a50000c | 1        | 0.99%   |
| 0x0a201016 | 1        | 0.99%   |
| 0x0a201009 | 1        | 0.99%   |
| 0x08701013 | 1        | 0.99%   |
| 0x08101016 | 1        | 0.99%   |
| 0x08001138 | 1        | 0.99%   |
| 0x06001119 | 1        | 0.99%   |
| 0x0600063e | 1        | 0.99%   |
| 0x010000db | 1        | 0.99%   |
| 0x010000c7 | 1        | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 16       | 15.84%  |
| KabyLake      | 14       | 13.86%  |
| Haswell       | 10       | 9.9%    |
| IvyBridge     | 9        | 8.91%   |
| Zen 2         | 8        | 7.92%   |
| Zen+          | 7        | 6.93%   |
| Westmere      | 4        | 3.96%   |
| Skylake       | 4        | 3.96%   |
| K10           | 4        | 3.96%   |
| Zen 3         | 3        | 2.97%   |
| Silvermont    | 3        | 2.97%   |
| Penryn        | 3        | 2.97%   |
| Icelake       | 3        | 2.97%   |
| Zen           | 2        | 1.98%   |
| Steamroller   | 2        | 1.98%   |
| Core          | 2        | 1.98%   |
| CometLake     | 2        | 1.98%   |
| TigerLake     | 1        | 0.99%   |
| Piledriver    | 1        | 0.99%   |
| Goldmont plus | 1        | 0.99%   |
| Bulldozer     | 1        | 0.99%   |
| Bonnell       | 1        | 0.99%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 40       | 37.04%  |
| AMD    | 35       | 32.41%  |
| Intel  | 33       | 30.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10       | 9.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 3.6%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4        | 3.6%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4        | 3.6%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 3        | 2.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 2.7%    |
| Intel HD Graphics 530                                                                    | 3        | 2.7%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3        | 2.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 1.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1.8%    |
| Nvidia GF108 [GeForce GT 430]                                                            | 2        | 1.8%    |
| Intel HD Graphics 630                                                                    | 2        | 1.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 1.8%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 1.8%    |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 1.8%    |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 0.9%    |
| Nvidia TU106 [GeForce GTX 1650]                                                          | 1        | 0.9%    |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.9%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.9%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.9%    |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1        | 0.9%    |
| Nvidia GP107GL [Quadro P1000]                                                            | 1        | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 0.9%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 0.9%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.9%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.9%    |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1        | 0.9%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.9%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.9%    |
| Nvidia GK110B [GeForce GTX TITAN Black]                                                  | 1        | 0.9%    |
| Nvidia GK104 [GeForce GTX 680]                                                           | 1        | 0.9%    |
| Nvidia GK104 [GeForce GTX 670]                                                           | 1        | 0.9%    |
| Nvidia GF119 [GeForce GT 625 OEM]                                                        | 1        | 0.9%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.9%    |
| Nvidia GF110 [GeForce GTX 580]                                                           | 1        | 0.9%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 0.9%    |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 0.9%    |
| Nvidia GF100 [GeForce GTX 470]                                                           | 1        | 0.9%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 0.9%    |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1        | 0.9%    |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 1        | 0.9%    |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 0.9%    |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1        | 0.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 0.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 0.9%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 0.9%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 0.9%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 0.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 0.9%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 0.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 0.9%    |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 1        | 0.9%    |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                                        | 1        | 0.9%    |
| AMD RV730 PRO [Radeon HD 4650]                                                           | 1        | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 38       | 36.89%  |
| 1 x AMD        | 31       | 30.1%   |
| 1 x Intel      | 29       | 28.16%  |
| 2 x AMD        | 2        | 1.94%   |
| Intel + Nvidia | 1        | 0.97%   |
| Intel + AMD    | 1        | 0.97%   |
| AMD + Nvidia   | 1        | 0.97%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 78       | 75.73%  |
| Proprietary | 25       | 24.27%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 29.81%  |
| 1.01-2.0   | 18       | 17.31%  |
| 3.01-4.0   | 17       | 16.35%  |
| 0.51-1.0   | 14       | 13.46%  |
| 7.01-8.0   | 9        | 8.65%   |
| 5.01-6.0   | 5        | 4.81%   |
| 0.01-0.5   | 4        | 3.85%   |
| 2.01-3.0   | 3        | 2.88%   |
| 8.01-16.0  | 3        | 2.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 16       | 13.68%  |
| Acer                 | 14       | 11.97%  |
| Hewlett-Packard      | 11       | 9.4%    |
| Goldstar             | 11       | 9.4%    |
| Philips              | 10       | 8.55%   |
| Dell                 | 8        | 6.84%   |
| BenQ                 | 6        | 5.13%   |
| Ancor Communications | 5        | 4.27%   |
| Lenovo               | 4        | 3.42%   |
| AOC                  | 4        | 3.42%   |
| Unknown              | 3        | 2.56%   |
| NEC Computers        | 2        | 1.71%   |
| LG Electronics       | 2        | 1.71%   |
| HPN                  | 2        | 1.71%   |
| Fujitsu Siemens      | 2        | 1.71%   |
| AUS                  | 2        | 1.71%   |
| ___                  | 1        | 0.85%   |
| Vizio                | 1        | 0.85%   |
| ViewSonic            | 1        | 0.85%   |
| Vestel               | 1        | 0.85%   |
| SPC                  | 1        | 0.85%   |
| MSI                  | 1        | 0.85%   |
| Mi                   | 1        | 0.85%   |
| IOD                  | 1        | 0.85%   |
| Iiyama               | 1        | 0.85%   |
| Element              | 1        | 0.85%   |
| Eizo                 | 1        | 0.85%   |
| CHR                  | 1        | 0.85%   |
| CHD                  | 1        | 0.85%   |
| BOE                  | 1        | 0.85%   |
| Unknown              | 1        | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch              | 3        | 2.42%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch                     | 2        | 1.61%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                          | 2        | 1.61%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                             | 2        | 1.61%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch          | 2        | 1.61%   |
| ___ LCDTV16 ___9000 1360x768                                                   | 1        | 0.81%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                            | 1        | 0.81%   |
| ViewSonic LCD Monitor VX2260WM 3840x1080                                       | 1        | 0.81%   |
| ViewSonic LCD Monitor VX2260WM                                                 | 1        | 0.81%   |
| Vestel LCD Monitor 49FHD_LCD_TV 1920x1080                                      | 1        | 0.81%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                             | 1        | 0.81%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                          | 1        | 0.81%   |
| Unknown LCD Monitor Bit 3 LE2262 1680x1050                                     | 1        | 0.81%   |
| SPC LCD Monitor SPC1900 1440x900 368x207mm 16.6-inch                           | 1        | 0.81%   |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch              | 1        | 0.81%   |
| Samsung Electronics SyncMaster SAM0421 1920x1200 518x324mm 24.1-inch           | 1        | 0.81%   |
| Samsung Electronics SMBX2035 SAM06FD 1600x900 443x249mm 20.0-inch              | 1        | 0.81%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch           | 1        | 0.81%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch           | 1        | 0.81%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch              | 1        | 0.81%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch              | 1        | 0.81%   |
| Samsung Electronics LCD Monitor SAM0C3F 3840x2160 1050x590mm 47.4-inch         | 1        | 0.81%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch           | 1        | 0.81%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch         | 1        | 0.81%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch           | 1        | 0.81%   |
| Samsung Electronics LCD Monitor SAM0530 1360x768                               | 1        | 0.81%   |
| Samsung Electronics LCD Monitor S22D300                                        | 1        | 0.81%   |
| Samsung Electronics LC32G5xT SAM7088 2560x1440 698x393mm 31.5-inch             | 1        | 0.81%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch                      | 1        | 0.81%   |
| Philips PHL 345E2 PHLC237 3440x1440 800x335mm 34.1-inch                        | 1        | 0.81%   |
| Philips PHL 275E1 PHLC20C 2560x1440 597x336mm 27.0-inch                        | 1        | 0.81%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch                        | 1        | 0.81%   |
| Philips PHL 203V5 PHLC0CE 1600x900 434x236mm 19.4-inch                         | 1        | 0.81%   |
| Philips LCD Monitor PHL 498P9 3840x1080                                        | 1        | 0.81%   |
| Philips LCD Monitor PHL 323E7 1920x1080                                        | 1        | 0.81%   |
| Philips LCD Monitor PHL 276E8V 7680x2160                                       | 1        | 0.81%   |
| Philips LCD Monitor PHL 276E8V 3840x2160                                       | 1        | 0.81%   |
| Philips LCD Monitor PHL 276E8V                                                 | 1        | 0.81%   |
| Philips LCD Monitor 19B 1280x1024                                              | 1        | 0.81%   |
| Philips 190CW PHLC023 1440x900 408x255mm 18.9-inch                             | 1        | 0.81%   |
| NEC Computers EA221WMe NEC6778 1680x1050 474x296mm 22.0-inch                   | 1        | 0.81%   |
| NEC Computers 70GX2 NEC6691 1280x1024 338x270mm 17.0-inch                      | 1        | 0.81%   |
| MSI Optix G27C2 MSI1462 1920x1080 600x340mm 27.2-inch                          | 1        | 0.81%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                               | 1        | 0.81%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                               | 1        | 0.81%   |
| LG Electronics LCD Monitor 2D FHD LG TV 3840x1080                              | 1        | 0.81%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                           | 1        | 0.81%   |
| Lenovo L2250p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch                       | 1        | 0.81%   |
| Lenovo D22-20 LEN66AD 1920x1080 477x268mm 21.5-inch                            | 1        | 0.81%   |
| Lenovo C24-25 LEN66B0 1920x1080 527x296mm 23.8-inch                            | 1        | 0.81%   |
| IOD LCD-AD221F-T IOD1687 1920x1080 477x268mm 21.5-inch                         | 1        | 0.81%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                         | 1        | 0.81%   |
| HPN LCD Monitor HP P244 1920x1080                                              | 1        | 0.81%   |
| HPN LCD Monitor HP 27fw 1920x1080                                              | 1        | 0.81%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch                    | 1        | 0.81%   |
| Hewlett-Packard VH27 HPN3525 1920x1080 598x336mm 27.0-inch                     | 1        | 0.81%   |
| Hewlett-Packard v220 HWP26FE 1680x1050 473x296mm 22.0-inch                     | 1        | 0.81%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch                      | 1        | 0.81%   |
| Hewlett-Packard TouchSmart HP_touchsmart HWP4211 1920x1080 509x286mm 23.0-inch | 1        | 0.81%   |
| Hewlett-Packard OMEN by HP 32 HPN3378 2560x1440 708x399mm 32.0-inch            | 1        | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 46       | 38.98%  |
| 3840x2160 (4K)     | 13       | 11.02%  |
| 1680x1050 (WSXGA+) | 12       | 10.17%  |
| 2560x1440 (QHD)    | 11       | 9.32%   |
| 1366x768 (WXGA)    | 8        | 6.78%   |
| 1440x900 (WXGA+)   | 5        | 4.24%   |
| 1600x900 (HD+)     | 4        | 3.39%   |
| Unknown            | 4        | 3.39%   |
| 3840x1080          | 3        | 2.54%   |
| 1920x1200 (WUXGA)  | 3        | 2.54%   |
| 1360x768           | 3        | 2.54%   |
| 3440x1440          | 2        | 1.69%   |
| 1280x1024 (SXGA)   | 2        | 1.69%   |
| 7680x2160          | 1        | 0.85%   |
| 5120x1440          | 1        | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 20.18%  |
| 21      | 15       | 13.16%  |
| 24      | 12       | 10.53%  |
| 27      | 11       | 9.65%   |
| 23      | 11       | 9.65%   |
| 22      | 11       | 9.65%   |
| 31      | 6        | 5.26%   |
| 18      | 4        | 3.51%   |
| 32      | 3        | 2.63%   |
| 20      | 3        | 2.63%   |
| 34      | 2        | 1.75%   |
| 19      | 2        | 1.75%   |
| 17      | 2        | 1.75%   |
| 15      | 2        | 1.75%   |
| 84      | 1        | 0.88%   |
| 72      | 1        | 0.88%   |
| 55      | 1        | 0.88%   |
| 48      | 1        | 0.88%   |
| 43      | 1        | 0.88%   |
| 26      | 1        | 0.88%   |
| 16      | 1        | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 33       | 29.73%  |
| 501-600     | 31       | 27.93%  |
| Unknown     | 23       | 20.72%  |
| 601-700     | 9        | 8.11%   |
| 701-800     | 5        | 4.5%    |
| 301-350     | 3        | 2.7%    |
| 351-400     | 2        | 1.8%    |
| 1501-2000   | 2        | 1.8%    |
| 1001-1500   | 2        | 1.8%    |
| 901-1000    | 1        | 0.9%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 63       | 60%     |
| Unknown | 21       | 20%     |
| 16/10   | 18       | 17.14%  |
| 21/9    | 2        | 1.9%    |
| 5/4     | 1        | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 36       | 32.43%  |
| Unknown        | 23       | 20.72%  |
| 351-500        | 11       | 9.91%   |
| 301-350        | 11       | 9.91%   |
| 151-200        | 10       | 9.01%   |
| 251-300        | 7        | 6.31%   |
| More than 1000 | 4        | 3.6%    |
| 141-150        | 4        | 3.6%    |
| 131-140        | 1        | 0.9%    |
| 111-120        | 1        | 0.9%    |
| 101-110        | 1        | 0.9%    |
| 501-1000       | 1        | 0.9%    |
| 91-100         | 1        | 0.9%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 53       | 48.18%  |
| 101-120 | 24       | 21.82%  |
| Unknown | 23       | 20.91%  |
| 121-160 | 6        | 5.45%   |
| 1-50    | 4        | 3.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 84       | 81.55%  |
| 2     | 17       | 16.5%   |
| 3     | 2        | 1.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 62       | 42.18%  |
| Intel                    | 50       | 34.01%  |
| Qualcomm Atheros         | 7        | 4.76%   |
| Ralink Technology        | 4        | 2.72%   |
| Broadcom                 | 4        | 2.72%   |
| TP-Link                  | 3        | 2.04%   |
| Samsung Electronics      | 3        | 2.04%   |
| Nvidia                   | 2        | 1.36%   |
| Xiaomi                   | 1        | 0.68%   |
| TRENDnet                 | 1        | 0.68%   |
| Ralink                   | 1        | 0.68%   |
| Motorola PCS             | 1        | 0.68%   |
| Microsoft                | 1        | 0.68%   |
| Marvell Technology Group | 1        | 0.68%   |
| Linksys                  | 1        | 0.68%   |
| LG Electronics           | 1        | 0.68%   |
| Huawei Technologies      | 1        | 0.68%   |
| D-Link System            | 1        | 0.68%   |
| Broadcom Limited         | 1        | 0.68%   |
| AVM                      | 1        | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                 | 43       | 25.9%   |
| Intel Wi-Fi 6 AX200                                                               | 10       | 6.02%   |
| Realtek RTL8125 2.5GbE Controller                                                 | 7        | 4.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 7        | 4.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 5        | 3.01%   |
| Intel I211 Gigabit Network Connection                                             | 5        | 3.01%   |
| Intel Ethernet Connection (2) I219-V                                              | 5        | 3.01%   |
| Realtek 802.11ac NIC                                                              | 4        | 2.41%   |
| Intel Ethernet Controller I225-V                                                  | 4        | 2.41%   |
| Intel 82579V Gigabit Network Connection                                           | 4        | 2.41%   |
| Ralink MT7601U Wireless Adapter                                                   | 3        | 1.81%   |
| Samsung Galaxy series, misc. (tethering mode)                                     | 2        | 1.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 2        | 1.2%    |
| Intel Ethernet Connection (7) I219-V                                              | 2        | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                                             | 2        | 1.2%    |
| Intel 82578DM Gigabit Network Connection                                          | 2        | 1.2%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 2        | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                    | 1        | 0.6%    |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.6%    |
| TP-Link Archer T4U ver.3                                                          | 1        | 0.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1        | 0.6%    |
| TP-Link 802.11ac NIC                                                              | 1        | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                       | 1        | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.6%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.6%    |
| Realtek RTL8191SEvA Wireless LAN Controller                                       | 1        | 0.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 1        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 1        | 0.6%    |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 1        | 0.6%    |
| Realtek RTL8187 Wireless Adapter                                                  | 1        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                             | 1        | 0.6%    |
| Realtek 802.11n WLAN Adapter                                                      | 1        | 0.6%    |
| Ralink RT5372 Wireless Adapter                                                    | 1        | 0.6%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                         | 1        | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                         | 1        | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                         | 1        | 0.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                          | 1        | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                        | 1        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                     | 1        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                          | 1        | 0.6%    |
| Nvidia MCP61 Ethernet                                                             | 1        | 0.6%    |
| Nvidia MCP55 Ethernet                                                             | 1        | 0.6%    |
| Motorola PCS moto g(30)                                                           | 1        | 0.6%    |
| Microsoft Xbox 360 Wireless Adapter                                               | 1        | 0.6%    |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                               | 1        | 0.6%    |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                         | 1        | 0.6%    |
| LG AN-WF100 802.11abgn Wireless Adapter [Broadcom BCM4323]                        | 1        | 0.6%    |
| Intel Wireless-AC 9260                                                            | 1        | 0.6%    |
| Intel Wireless 8260                                                               | 1        | 0.6%    |
| Intel Wireless 3165                                                               | 1        | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 1        | 0.6%    |
| Intel Wi-Fi 6 AX201                                                               | 1        | 0.6%    |
| Intel Tiger Lake PCH CNVi WiFi                                                    | 1        | 0.6%    |
| Intel I210 Gigabit Network Connection                                             | 1        | 0.6%    |
| Intel Ethernet Connection I217-LM                                                 | 1        | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                                             | 1        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                                              | 1        | 0.6%    |
| Intel Ethernet Connection (12) I219-V                                             | 1        | 0.6%    |
| Intel Ethernet Connection (11) I219-V                                             | 1        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 20       | 37.04%  |
| Realtek Semiconductor    | 13       | 24.07%  |
| Ralink Technology        | 4        | 7.41%   |
| Broadcom                 | 4        | 7.41%   |
| TP-Link                  | 3        | 5.56%   |
| TRENDnet                 | 1        | 1.85%   |
| Ralink                   | 1        | 1.85%   |
| Qualcomm Atheros         | 1        | 1.85%   |
| Microsoft                | 1        | 1.85%   |
| Marvell Technology Group | 1        | 1.85%   |
| Linksys                  | 1        | 1.85%   |
| LG Electronics           | 1        | 1.85%   |
| D-Link System            | 1        | 1.85%   |
| Broadcom Limited         | 1        | 1.85%   |
| AVM                      | 1        | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 10       | 18.18%  |
| Realtek 802.11ac NIC                                                              | 4        | 7.27%   |
| Ralink MT7601U Wireless Adapter                                                   | 3        | 5.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 2        | 3.64%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 2        | 3.64%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 1.82%   |
| TP-Link Archer T4U ver.3                                                          | 1        | 1.82%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1        | 1.82%   |
| TP-Link 802.11ac NIC                                                              | 1        | 1.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 1.82%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 1.82%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                       | 1        | 1.82%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 1        | 1.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 1        | 1.82%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 1        | 1.82%   |
| Realtek RTL8187 Wireless Adapter                                                  | 1        | 1.82%   |
| Realtek 802.11n WLAN Adapter                                                      | 1        | 1.82%   |
| Ralink RT5372 Wireless Adapter                                                    | 1        | 1.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                         | 1        | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1        | 1.82%   |
| Microsoft Xbox 360 Wireless Adapter                                               | 1        | 1.82%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                               | 1        | 1.82%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                         | 1        | 1.82%   |
| LG AN-WF100 802.11abgn Wireless Adapter [Broadcom BCM4323]                        | 1        | 1.82%   |
| Intel Wireless-AC 9260                                                            | 1        | 1.82%   |
| Intel Wireless 8260                                                               | 1        | 1.82%   |
| Intel Wireless 3165                                                               | 1        | 1.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 1        | 1.82%   |
| Intel Wi-Fi 6 AX201                                                               | 1        | 1.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                                    | 1        | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 1        | 1.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                   | 1        | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                      | 1        | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 1        | 1.82%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]                 | 1        | 1.82%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                            | 1        | 1.82%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                       | 1        | 1.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                                   | 1        | 1.82%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                              | 1        | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 56       | 50.45%  |
| Intel                 | 41       | 36.94%  |
| Qualcomm Atheros      | 6        | 5.41%   |
| Samsung Electronics   | 3        | 2.7%    |
| Nvidia                | 2        | 1.8%    |
| Xiaomi                | 1        | 0.9%    |
| Motorola PCS          | 1        | 0.9%    |
| Huawei Technologies   | 1        | 0.9%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43       | 38.74%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 6.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 6.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 4.5%    |
| Intel I211 Gigabit Network Connection                             | 5        | 4.5%    |
| Intel Ethernet Connection (2) I219-V                              | 5        | 4.5%    |
| Intel Ethernet Controller I225-V                                  | 4        | 3.6%    |
| Intel 82579V Gigabit Network Connection                           | 4        | 3.6%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.8%    |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.8%    |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.8%    |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.9%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.9%    |
| Nvidia MCP61 Ethernet                                             | 1        | 0.9%    |
| Nvidia MCP55 Ethernet                                             | 1        | 0.9%    |
| Motorola PCS moto g(30)                                           | 1        | 0.9%    |
| Intel I210 Gigabit Network Connection                             | 1        | 0.9%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.9%    |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.9%    |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.9%    |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.9%    |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.9%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.9%    |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.9%    |
| Huawei JNY-LX1                                                    | 1        | 0.9%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 101      | 66.45%  |
| WiFi     | 51       | 33.55%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 91       | 72.22%  |
| WiFi     | 35       | 27.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 65       | 64.36%  |
| 2     | 29       | 28.71%  |
| 3     | 6        | 5.94%   |
| 0     | 1        | 0.99%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 76       | 73.79%  |
| Yes  | 27       | 26.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 18       | 47.37%  |
| Cambridge Silicon Radio | 11       | 28.95%  |
| Realtek Semiconductor   | 3        | 7.89%   |
| Apple                   | 2        | 5.26%   |
| Qcom                    | 1        | 2.63%   |
| IMC Networks            | 1        | 2.63%   |
| Broadcom                | 1        | 2.63%   |
| ASUSTek Computer        | 1        | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 28.95%  |
| Intel AX200 Bluetooth                               | 9        | 23.68%  |
| Intel Bluetooth wireless interface                  | 3        | 7.89%   |
| Realtek Bluetooth Radio                             | 2        | 5.26%   |
| Intel Bluetooth Device                              | 2        | 5.26%   |
| Realtek Bluetooth 5.1 Radio                         | 1        | 2.63%   |
| Qcom Bluetooth USB                                  | 1        | 2.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 2.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 2.63%   |
| Intel AX210 Bluetooth                               | 1        | 2.63%   |
| IMC Networks BCM20702A0                             | 1        | 2.63%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 2.63%   |
| ASUS BCM20702A0                                     | 1        | 2.63%   |
| Apple Bluetooth USB Host Controller                 | 1        | 2.63%   |
| Apple Bluetooth HCI                                 | 1        | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 66       | 37.93%  |
| AMD                    | 42       | 24.14%  |
| Nvidia                 | 40       | 22.99%  |
| C-Media Electronics    | 8        | 4.6%    |
| Creative Labs          | 7        | 4.02%   |
| Logitech               | 2        | 1.15%   |
| Focusrite-Novation     | 2        | 1.15%   |
| Razer USA              | 1        | 0.57%   |
| Native Instruments     | 1        | 0.57%   |
| GN Netcom              | 1        | 0.57%   |
| Generalplus Technology | 1        | 0.57%   |
| Creative Technology    | 1        | 0.57%   |
| Corsair                | 1        | 0.57%   |
| ASUSTek Computer       | 1        | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 16       | 8.25%   |
| AMD Starship/Matisse HD Audio Controller                                          | 8        | 4.12%   |
| Intel Cannon Lake PCH cAVS                                                        | 7        | 3.61%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 7        | 3.61%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 2.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5        | 2.58%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 2.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 2.58%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 2.58%   |
| AMD Family 17h/19h HD Audio Controller                                            | 5        | 2.58%   |
| Nvidia TU104 HD Audio Controller                                                  | 4        | 2.06%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4        | 2.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 4        | 2.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4        | 2.06%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 4        | 2.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 2.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 4        | 2.06%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 2.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3        | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 1.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 1.55%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 1.55%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3        | 1.55%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 3        | 1.55%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 1.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3        | 1.55%   |
| AMD FCH Azalia Controller                                                         | 3        | 1.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 1.03%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 1.03%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 1.03%   |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 1.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2        | 1.03%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 1.03%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 2        | 1.03%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 2        | 1.03%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 1.03%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver]        | 1        | 0.52%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.52%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 0.52%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.52%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 0.52%   |
| Nvidia MCP55 High Definition Audio                                                | 1        | 0.52%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1        | 0.52%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.52%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1        | 0.52%   |
| Nvidia GK110 High Definition Audio Controller                                     | 1        | 0.52%   |
| Nvidia GF110 High Definition Audio Controller                                     | 1        | 0.52%   |
| Nvidia GF100 High Definition Audio Controller                                     | 1        | 0.52%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 0.52%   |
| Native Instruments Traktor Audio 2 MK2                                            | 1        | 0.52%   |
| Logitech Headset H340                                                             | 1        | 0.52%   |
| Logitech G733 Gaming Headset                                                      | 1        | 0.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1        | 0.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1        | 0.52%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 0.52%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 0.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 0.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 0.52%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 25%     |
| SK Hynix            | 3        | 18.75%  |
| Kingston            | 3        | 18.75%  |
| Corsair             | 2        | 12.5%   |
| Unknown             | 1        | 6.25%   |
| Ramaxel Technology  | 1        | 6.25%   |
| PNY                 | 1        | 6.25%   |
| Patriot             | 1        | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s              | 1        | 6.25%   |
| SK Hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s     | 1        | 6.25%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 6.25%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1        | 6.25%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s              | 1        | 6.25%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s  | 1        | 6.25%   |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s       | 1        | 6.25%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s       | 1        | 6.25%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s | 1        | 6.25%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 3200MT/s    | 1        | 6.25%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s        | 1        | 6.25%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s     | 1        | 6.25%   |
| Kingston RAM 9905625-030.A00G 8GB DIMM DDR4 2133MT/s      | 1        | 6.25%   |
| Kingston RAM 9905471-015.A00LF 4096MB DIMM DDR3 1333MT/s  | 1        | 6.25%   |
| Corsair RAM CMX8GX3M1A1600C11 8GB DIMM DDR3 1600MT/s      | 1        | 6.25%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s      | 1        | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 6        | 50%     |
| DDR3 | 6        | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 11       | 91.67%  |
| SODIMM | 1        | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 50%     |
| 4096  | 3        | 25%     |
| 16384 | 2        | 16.67%  |
| 32768 | 1        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 2        | 15.38%  |
| 1600  | 2        | 15.38%  |
| 1066  | 2        | 15.38%  |
| 3600  | 1        | 7.69%   |
| 2800  | 1        | 7.69%   |
| 2666  | 1        | 7.69%   |
| 2200  | 1        | 7.69%   |
| 2133  | 1        | 7.69%   |
| 1800  | 1        | 7.69%   |
| 1333  | 1        | 7.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 33.33%  |
| Dymo-CoStar     | 1        | 33.33%  |
| Canon           | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP Ink Tank 110 series      | 1        | 33.33%  |
| Dymo-CoStar LabelWriter 450 | 1        | 33.33%  |
| Canon PIXMA MG3600 Series   | 1        | 33.33%  |

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
| Logitech                      | 6        | 35.29%  |
| Microsoft                     | 2        | 11.76%  |
| Apple                         | 2        | 11.76%  |
| Sunplus Innovation Technology | 1        | 5.88%   |
| Razer USA                     | 1        | 5.88%   |
| Microdia                      | 1        | 5.88%   |
| CQG-5693-201019               | 1        | 5.88%   |
| Chicony Electronics           | 1        | 5.88%   |
| ANYKA                         | 1        | 5.88%   |
| Alcor Micro                   | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Apple iPhone 5/5C/5S/6/SE             | 2        | 11.76%  |
| Sunplus Integrated_Webcam_HD          | 1        | 5.88%   |
| Razer USA Razer Kiyo Pro              | 1        | 5.88%   |
| Microsoft LifeCam VX-800              | 1        | 5.88%   |
| Microsoft LifeCam HD-3000             | 1        | 5.88%   |
| Microdia USB 2.0 Camera               | 1        | 5.88%   |
| Logitech Webcam C925e                 | 1        | 5.88%   |
| Logitech QuickCam Communicate Deluxe  | 1        | 5.88%   |
| Logitech HD Webcam C910               | 1        | 5.88%   |
| Logitech HD Webcam C615               | 1        | 5.88%   |
| Logitech BRIO 4K Stream Edition       | 1        | 5.88%   |
| Logitech B525 HD Webcam               | 1        | 5.88%   |
| CQG-5693-201019 Real QHD(2592x1944)   | 1        | 5.88%   |
| Chicony HP High Definition 1MP Webcam | 1        | 5.88%   |
| ANYKA V380 FHD Camera                 | 1        | 5.88%   |
| Alcor Micro USB 2.0 PC Camera         | 1        | 5.88%   |

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
| 0     | 88       | 86.27%  |
| 1     | 12       | 11.76%  |
| 4     | 1        | 0.98%   |
| 2     | 1        | 0.98%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 9        | 52.94%  |
| Unassigned class      | 2        | 11.76%  |
| Sound                 | 2        | 11.76%  |
| Storage/ide           | 1        | 5.88%   |
| Multimedia controller | 1        | 5.88%   |
| Fingerprint reader    | 1        | 5.88%   |
| Bluetooth             | 1        | 5.88%   |

