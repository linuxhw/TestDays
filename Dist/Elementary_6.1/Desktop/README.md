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

Total: 166

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF X470-PLUS GAMING        | [80a981f992](https://linux-hardware.org/?probe=80a981f992) | Jul 01, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| ASRock        | Z490 Pro4                   | [f84c8a756c](https://linux-hardware.org/?probe=f84c8a756c) | Jun 25, 2022 |
| MSI           | B85I                        | [886f971d22](https://linux-hardware.org/?probe=886f971d22) | Jun 25, 2022 |
| HP            | 339A                        | [822467af7f](https://linux-hardware.org/?probe=822467af7f) | Jun 25, 2022 |
| T-bao         | MINI PC                     | [6b18c66487](https://linux-hardware.org/?probe=6b18c66487) | Jun 18, 2022 |
| Pegatron      | 2ACD                        | [8c8275099b](https://linux-hardware.org/?probe=8c8275099b) | Jun 16, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [5b8ae292bf](https://linux-hardware.org/?probe=5b8ae292bf) | Jun 14, 2022 |
| ASUSTek       | SABERTOOTH X58              | [4cc4a7c1b3](https://linux-hardware.org/?probe=4cc4a7c1b3) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH X58              | [25a8936801](https://linux-hardware.org/?probe=25a8936801) | Jun 11, 2022 |
| HP            | 2B43                        | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [9756188040](https://linux-hardware.org/?probe=9756188040) | Jun 07, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [0d57c069a8](https://linux-hardware.org/?probe=0d57c069a8) | Jun 05, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [16f3fff6ad](https://linux-hardware.org/?probe=16f3fff6ad) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [b3d970d061](https://linux-hardware.org/?probe=b3d970d061) | Jun 04, 2022 |
| MSI           | B85I                        | [5f29683d93](https://linux-hardware.org/?probe=5f29683d93) | Jun 03, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [9f4aa60f60](https://linux-hardware.org/?probe=9f4aa60f60) | Jun 02, 2022 |
| ASUSTek       | P5B                         | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| ASUSTek       | P5B                         | [845c2f114b](https://linux-hardware.org/?probe=845c2f114b) | May 31, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [a4f2a9b24b](https://linux-hardware.org/?probe=a4f2a9b24b) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [3143793e8f](https://linux-hardware.org/?probe=3143793e8f) | May 27, 2022 |
| ASUSTek       | P8H61                       | [5514e95c95](https://linux-hardware.org/?probe=5514e95c95) | May 24, 2022 |
| ASUSTek       | P8H61                       | [873dd31f8e](https://linux-hardware.org/?probe=873dd31f8e) | May 23, 2022 |
| MSI           | H97M-P35                    | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Biostar       | GF8200C M2+                 | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [6f6a104d35](https://linux-hardware.org/?probe=6f6a104d35) | May 21, 2022 |
| MSI           | B85I                        | [c822196290](https://linux-hardware.org/?probe=c822196290) | May 18, 2022 |
| MSI           | MEG X570 UNIFY              | [4d00452dcb](https://linux-hardware.org/?probe=4d00452dcb) | May 15, 2022 |
| ASUSTek       | SABERTOOTH X58              | [c276639676](https://linux-hardware.org/?probe=c276639676) | May 08, 2022 |
| ASUSTek       | H81M-K                      | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| ASRock        | X570 Extreme4               | [98e5f20999](https://linux-hardware.org/?probe=98e5f20999) | May 04, 2022 |
| HP            | 0B48h                       | [4c6e5824f2](https://linux-hardware.org/?probe=4c6e5824f2) | Apr 30, 2022 |
| ASUSTek       | P8Z77-V                     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| Dell          | 0J3C2F A00                  | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1f10d820f8](https://linux-hardware.org/?probe=1f10d820f8) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [dfadead480](https://linux-hardware.org/?probe=dfadead480) | Apr 27, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [1b0a41c232](https://linux-hardware.org/?probe=1b0a41c232) | Apr 25, 2022 |
| AZW           | GTi                         | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW           | GTi                         | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ECS           | H61H2-MV                    | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| MSI           | X99A SLI PLUS               | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| ASRock        | Z490 Pro4                   | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Dell          | 0KV62T A01                  | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| HP            | 1494                        | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Dell          | 0K240Y A01                  | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| ASUSTek       | PRIME Z390-A                | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| Pegatron      | IPMH61P1                    | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| ASUSTek       | H110I-PLUS                  | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| ASRock        | C226 WS                     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI           | H97 GAMING 3                | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| ASUSTek       | Rampage IV GENE             | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Dell          | 0C522T A00                  | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel         | X79Turbo V1.x               | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| AMI           | Cherry Trail CR             | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| AMI           | Cherry Trail CR             | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| ASUSTek       | Rampage IV GENE             | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| AOpen         | D1009 A1A4                  | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| MSI           | B85I                        | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| ASRock        | B450M Pro4                  | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar       | N68S3B                      | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| ASUSTek       | M11AD                       | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Biostar       | H61MLV2                     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP            | 2ADC                        | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI           | B85I                        | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Dell          | 0PU052                      | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell          | 0PU052                      | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| HP            | 1589                        | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| HP            | 802E                        | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| ASRock        | FM2A58M-DG3+                | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| HP            | 805D                        | [2a09665009](https://linux-hardware.org/?probe=2a09665009) | Mar 02, 2022 |
| ASUSTek       | M4N72-E                     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek       | H81-PLUS                    | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| Gigabyte      | Z390 UD                     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| Intel         | DH61BE AAG14062-210         | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| ASUSTek       | M11AD                       | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| ASUSTek       | P5B                         | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel         | H61                         | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| ASUSTek       | PRIME Z590-A                | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar       | A68MD PRO                   | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| ASUSTek       | PRIME Z590-A                | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| MSI           | B85I                        | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek       | PRIME B360M-K               | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| ECS           | H55H-M                      | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Lenovo        | NO DPK                      | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| HP            | 802E                        | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| ASUSTek       | H110M-C                     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | P5B                         | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| HP            | 339A                        | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| Unknown       | Unknown                     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| HP            | 805D                        | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| ASUSTek       | H110I-PLUS                  | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte      | B75M-D3H                    | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| MSI           | Z270 KRAIT GAMING           | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Gigabyte      | H61M-DS2                    | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| ASRock        | H61M-HVS                    | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| FIRICH        | J1900                       | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| MSI           | B450M-A PRO MAX             | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| ASUSTek       | H61M-CS                     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| ASUSTek       | H110M-C                     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| HP            | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte      | GA-970A-D3                  | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock        | Z370 Pro4                   | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| ASRock        | B450M-HDV R4.0              | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| MSI           | 2A9C                        | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| HP            | 3397                        | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek       | X79-DELUXE                  | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| HP            | 1589                        | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Gigabyte      | Z390 UD                     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| MSI           | B450-A PRO MAX              | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Foxconn       | 2AB1                        | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| ASUSTek       | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.11.0-43-generic    | 26       | 19.55%  |
| 5.13.0-39-generic    | 17       | 12.78%  |
| 5.13.0-28-generic    | 16       | 12.03%  |
| 5.13.0-30-generic    | 10       | 7.52%   |
| 5.13.0-40-generic    | 9        | 6.77%   |
| 5.13.0-27-generic    | 9        | 6.77%   |
| 5.13.0-35-generic    | 7        | 5.26%   |
| 5.13.0-37-generic    | 5        | 3.76%   |
| 5.11.0-41-generic    | 5        | 3.76%   |
| 5.13.0-51-generic    | 4        | 3.01%   |
| 5.13.0-44-generic    | 4        | 3.01%   |
| 5.11.0-44-generic    | 4        | 3.01%   |
| 5.13.0-48-generic    | 3        | 2.26%   |
| 5.13.0-41-generic    | 2        | 1.5%    |
| 5.13.0-25-generic    | 2        | 1.5%    |
| 5.11.0-46-generic    | 2        | 1.5%    |
| 5.17.3-xanmod1       | 1        | 0.75%   |
| 5.15.36-xanmod1      | 1        | 0.75%   |
| 5.14.0-1042-oem      | 1        | 0.75%   |
| 5.13.0-28-lowlatency | 1        | 0.75%   |
| 5.13.0-22-generic    | 1        | 0.75%   |
| 5.11.0-43-lowlatency | 1        | 0.75%   |
| 5.11.0-40-generic    | 1        | 0.75%   |
| 5.11.0-37-generic    | 1        | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 81       | 66.39%  |
| 5.11.0  | 38       | 31.15%  |
| 5.17.3  | 1        | 0.82%   |
| 5.15.36 | 1        | 0.82%   |
| 5.14.0  | 1        | 0.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 81       | 66.39%  |
| 5.11    | 38       | 31.15%  |
| 5.17    | 1        | 0.82%   |
| 5.15    | 1        | 0.82%   |
| 5.14    | 1        | 0.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 119      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 119      | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 119      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 100      | 83.33%  |
| LightDM | 20       | 16.67%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 48       | 40%     |
| de_DE | 16       | 13.33%  |
| es_ES | 11       | 9.17%   |
| fr_FR | 9        | 7.5%    |
| en_GB | 7        | 5.83%   |
| ru_RU | 4        | 3.33%   |
| pt_BR | 4        | 3.33%   |
| it_IT | 4        | 3.33%   |
| pl_PL | 3        | 2.5%    |
| tr_TR | 2        | 1.67%   |
| ja_JP | 2        | 1.67%   |
| en_CA | 2        | 1.67%   |
| zh_CN | 1        | 0.83%   |
| uk_UA | 1        | 0.83%   |
| sr_RS | 1        | 0.83%   |
| pt_PT | 1        | 0.83%   |
| id_ID | 1        | 0.83%   |
| fr_CA | 1        | 0.83%   |
| en_AU | 1        | 0.83%   |
| de_CH | 1        | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 65       | 54.17%  |
| BIOS | 55       | 45.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 114      | 95.8%   |
| Btrfs   | 3        | 2.52%   |
| Xfs     | 1        | 0.84%   |
| Overlay | 1        | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 104      | 86.67%  |
| GPT     | 13       | 10.83%  |
| MBR     | 3        | 2.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 114      | 95%     |
| Yes       | 6        | 5%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 92.5%   |
| Yes       | 9        | 7.5%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 33       | 27.73%  |
| MSI                 | 16       | 13.45%  |
| Gigabyte Technology | 16       | 13.45%  |
| Hewlett-Packard     | 12       | 10.08%  |
| ASRock              | 8        | 6.72%   |
| Dell                | 6        | 5.04%   |
| Lenovo              | 4        | 3.36%   |
| Biostar             | 4        | 3.36%   |
| Intel               | 3        | 2.52%   |
| Pegatron            | 2        | 1.68%   |
| Foxconn             | 2        | 1.68%   |
| ECS                 | 2        | 1.68%   |
| Unknown             | 2        | 1.68%   |
| T-bao               | 1        | 0.84%   |
| LORD ELECTRONICS    | 1        | 0.84%   |
| Fujitsu             | 1        | 0.84%   |
| FIRICH              | 1        | 0.84%   |
| AZW                 | 1        | 0.84%   |
| Apple               | 1        | 0.84%   |
| AOpen               | 1        | 0.84%   |
| AMI                 | 1        | 0.84%   |
| Acer                | 1        | 0.84%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| ASUS All Series                                   | 4        | 3.36%   |
| MSI MS-7C35                                       | 2        | 1.68%   |
| HP Compaq Pro 6300 MT                             | 2        | 1.68%   |
| Gigabyte Z390 UD                                  | 2        | 1.68%   |
| ASUS TUF Gaming B550M-PLUS                        | 2        | 1.68%   |
| Unknown                                           | 2        | 1.68%   |
| T-bao MINI PC                                     | 1        | 0.84%   |
| Pegatron p7-1174                                  | 1        | 0.84%   |
| Pegatron IPMH61P1                                 | 1        | 0.84%   |
| MSI PPPPP-CCC#MMMMMMMM                            | 1        | 0.84%   |
| MSI MS-7D52                                       | 1        | 0.84%   |
| MSI MS-7C91                                       | 1        | 0.84%   |
| MSI MS-7C52                                       | 1        | 0.84%   |
| MSI MS-7C02                                       | 1        | 0.84%   |
| MSI MS-7B86                                       | 1        | 0.84%   |
| MSI MS-7B79                                       | 1        | 0.84%   |
| MSI MS-7A59                                       | 1        | 0.84%   |
| MSI MS-7A40                                       | 1        | 0.84%   |
| MSI MS-7A38                                       | 1        | 0.84%   |
| MSI MS-7918                                       | 1        | 0.84%   |
| MSI MS-7885                                       | 1        | 0.84%   |
| MSI MS-7851                                       | 1        | 0.84%   |
| MSI MS-7817                                       | 1        | 0.84%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 1        | 0.84%   |
| Lenovo ThinkCentre M73 10B6001SUS                 | 1        | 0.84%   |
| Lenovo ThinkCentre M72e 3664AD7                   | 1        | 0.84%   |
| Lenovo ThinkCentre M58 6258D3G                    | 1        | 0.84%   |
| Lenovo IdeaCentre 510S-07ICK 90LX006TGE           | 1        | 0.84%   |
| Intel X79                                         | 1        | 0.84%   |
| Intel H61                                         | 1        | 0.84%   |
| Intel DH61BE AAG14062-210                         | 1        | 0.84%   |
| HP Z420 Workstation                               | 1        | 0.84%   |
| HP Z240 SFF Workstation                           | 1        | 0.84%   |
| HP Z200 SFF Workstation                           | 1        | 0.84%   |
| HP ProLiant ML110 G7                              | 1        | 0.84%   |
| HP ProDesk 600 G5 SFF                             | 1        | 0.84%   |
| HP ProDesk 600 G2 SFF                             | 1        | 0.84%   |
| HP Compaq Elite 8300 SFF                          | 1        | 0.84%   |
| HP Compaq 8200 Elite CMT PC                       | 1        | 0.84%   |
| HP 520-1175a                                      | 1        | 0.84%   |
| HP 23-q120d                                       | 1        | 0.84%   |
| Gigabyte Z690 AORUS MASTER                        | 1        | 0.84%   |
| Gigabyte Z590 AORUS ELITE AX                      | 1        | 0.84%   |
| Gigabyte X570 AORUS ELITE                         | 1        | 0.84%   |
| Gigabyte X470 AORUS ULTRA GAMING                  | 1        | 0.84%   |
| Gigabyte H61M-DS2                                 | 1        | 0.84%   |
| Gigabyte H61M-D2H-USB3                            | 1        | 0.84%   |
| Gigabyte H310M S2P 2.0                            | 1        | 0.84%   |
| Gigabyte GA-970A-D3                               | 1        | 0.84%   |
| Gigabyte F2A68HM-H                                | 1        | 0.84%   |
| Gigabyte B85M-DS3H-A                              | 1        | 0.84%   |
| Gigabyte B75M-D3H                                 | 1        | 0.84%   |
| Gigabyte B450 AORUS ELITE                         | 1        | 0.84%   |
| Gigabyte B150N Phoenix-WIFI                       | 1        | 0.84%   |
| Gigabyte A320M-S2H                                | 1        | 0.84%   |
| Fujitsu ESPRIMO D757                              | 1        | 0.84%   |
| Foxconn p6616f                                    | 1        | 0.84%   |
| Foxconn nT435/nT535                               | 1        | 0.84%   |
| FIRICH J1900                                      | 1        | 0.84%   |
| ECS H61H2-MV                                      | 1        | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 6        | 5.04%   |
| Dell OptiPlex          | 5        | 4.2%    |
| ASUS TUF               | 5        | 4.2%    |
| HP Compaq              | 4        | 3.36%   |
| ASUS ROG               | 4        | 3.36%   |
| ASUS All               | 4        | 3.36%   |
| Lenovo ThinkCentre     | 3        | 2.52%   |
| MSI MS-7C35            | 2        | 1.68%   |
| HP ProDesk             | 2        | 1.68%   |
| Gigabyte Z390          | 2        | 1.68%   |
| ASUS P8H61-M           | 2        | 1.68%   |
| Unknown                | 2        | 1.68%   |
| T-bao MINI             | 1        | 0.84%   |
| Pegatron p7-1174       | 1        | 0.84%   |
| Pegatron IPMH61P1      | 1        | 0.84%   |
| MSI PPPPP-CCC#MMMMMMMM | 1        | 0.84%   |
| MSI MS-7D52            | 1        | 0.84%   |
| MSI MS-7C91            | 1        | 0.84%   |
| MSI MS-7C52            | 1        | 0.84%   |
| MSI MS-7C02            | 1        | 0.84%   |
| MSI MS-7B86            | 1        | 0.84%   |
| MSI MS-7B79            | 1        | 0.84%   |
| MSI MS-7A59            | 1        | 0.84%   |
| MSI MS-7A40            | 1        | 0.84%   |
| MSI MS-7A38            | 1        | 0.84%   |
| MSI MS-7918            | 1        | 0.84%   |
| MSI MS-7885            | 1        | 0.84%   |
| MSI MS-7851            | 1        | 0.84%   |
| MSI MS-7817            | 1        | 0.84%   |
| LORD ELECTRONICS LORD  | 1        | 0.84%   |
| Lenovo IdeaCentre      | 1        | 0.84%   |
| Intel X79              | 1        | 0.84%   |
| Intel H61              | 1        | 0.84%   |
| Intel DH61BE           | 1        | 0.84%   |
| HP Z420                | 1        | 0.84%   |
| HP Z240                | 1        | 0.84%   |
| HP Z200                | 1        | 0.84%   |
| HP ProLiant            | 1        | 0.84%   |
| HP 520-1175a           | 1        | 0.84%   |
| HP 23-q120d            | 1        | 0.84%   |
| Gigabyte Z690          | 1        | 0.84%   |
| Gigabyte Z590          | 1        | 0.84%   |
| Gigabyte X570          | 1        | 0.84%   |
| Gigabyte X470          | 1        | 0.84%   |
| Gigabyte H61M-DS2      | 1        | 0.84%   |
| Gigabyte H61M-D2H-USB3 | 1        | 0.84%   |
| Gigabyte H310M         | 1        | 0.84%   |
| Gigabyte GA-970A-D3    | 1        | 0.84%   |
| Gigabyte F2A68HM-H     | 1        | 0.84%   |
| Gigabyte B85M-DS3H-A   | 1        | 0.84%   |
| Gigabyte B75M-D3H      | 1        | 0.84%   |
| Gigabyte B450          | 1        | 0.84%   |
| Gigabyte B150N         | 1        | 0.84%   |
| Gigabyte A320M-S2H     | 1        | 0.84%   |
| Fujitsu ESPRIMO        | 1        | 0.84%   |
| Foxconn p6616f         | 1        | 0.84%   |
| Foxconn nT435          | 1        | 0.84%   |
| FIRICH J1900           | 1        | 0.84%   |
| ECS H61H2-MV           | 1        | 0.84%   |
| ECS H55H-M             | 1        | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 15       | 12.61%  |
| 2018 | 13       | 10.92%  |
| 2019 | 12       | 10.08%  |
| 2020 | 11       | 9.24%   |
| 2011 | 11       | 9.24%   |
| 2015 | 9        | 7.56%   |
| 2021 | 8        | 6.72%   |
| 2010 | 8        | 6.72%   |
| 2014 | 7        | 5.88%   |
| 2013 | 7        | 5.88%   |
| 2017 | 5        | 4.2%    |
| 2016 | 5        | 4.2%    |
| 2022 | 3        | 2.52%   |
| 2008 | 2        | 1.68%   |
| 2009 | 1        | 0.84%   |
| 2007 | 1        | 0.84%   |
| 2006 | 1        | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 119      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 113      | 94.96%  |
| Enabled  | 6        | 5.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 119      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 28       | 23.33%  |
| 8.01-16.0   | 25       | 20.83%  |
| 32.01-64.0  | 24       | 20%     |
| 4.01-8.0    | 18       | 15%     |
| 3.01-4.0    | 15       | 12.5%   |
| 64.01-256.0 | 4        | 3.33%   |
| 1.01-2.0    | 3        | 2.5%    |
| 24.01-32.0  | 2        | 1.67%   |
| 2.01-3.0    | 1        | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 52       | 39.1%   |
| 2.01-3.0  | 37       | 27.82%  |
| 4.01-8.0  | 19       | 14.29%  |
| 3.01-4.0  | 18       | 13.53%  |
| 8.01-16.0 | 4        | 3.01%   |
| 0.51-1.0  | 3        | 2.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 41       | 33.88%  |
| 1      | 40       | 33.06%  |
| 3      | 19       | 15.7%   |
| 4      | 12       | 9.92%   |
| 5      | 5        | 4.13%   |
| 7      | 2        | 1.65%   |
| 6      | 2        | 1.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 53.33%  |
| Yes       | 56       | 46.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 119      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 51.67%  |
| Yes       | 58       | 48.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 61.67%  |
| Yes       | 46       | 38.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 15       | 12.61%  |
| USA          | 13       | 10.92%  |
| UK           | 8        | 6.72%   |
| Spain        | 8        | 6.72%   |
| France       | 8        | 6.72%   |
| Indonesia    | 6        | 5.04%   |
| Canada       | 5        | 4.2%    |
| Brazil       | 5        | 4.2%    |
| Russia       | 4        | 3.36%   |
| Poland       | 4        | 3.36%   |
| Italy        | 4        | 3.36%   |
| Turkey       | 3        | 2.52%   |
| Switzerland  | 3        | 2.52%   |
| Japan        | 3        | 2.52%   |
| India        | 3        | 2.52%   |
| Australia    | 3        | 2.52%   |
| Iran         | 2        | 1.68%   |
| Austria      | 2        | 1.68%   |
| Argentina    | 2        | 1.68%   |
| Thailand     | 1        | 0.84%   |
| Sweden       | 1        | 0.84%   |
| Sri Lanka    | 1        | 0.84%   |
| South Africa | 1        | 0.84%   |
| Serbia       | 1        | 0.84%   |
| Romania      | 1        | 0.84%   |
| Norway       | 1        | 0.84%   |
| New Zealand  | 1        | 0.84%   |
| Netherlands  | 1        | 0.84%   |
| Mexico       | 1        | 0.84%   |
| Malaysia     | 1        | 0.84%   |
| Lithuania    | 1        | 0.84%   |
| Israel       | 1        | 0.84%   |
| Hong Kong    | 1        | 0.84%   |
| Egypt        | 1        | 0.84%   |
| Czechia      | 1        | 0.84%   |
| Colombia     | 1        | 0.84%   |
| China        | 1        | 0.84%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Warsaw           | 3        | 2.34%   |
| Hamburg          | 3        | 2.34%   |
| Tangerang        | 2        | 1.56%   |
| Paris            | 2        | 1.56%   |
| Moscow           | 2        | 1.56%   |
| Istanbul         | 2        | 1.56%   |
| Brisbane         | 2        | 1.56%   |
| Yucca Valley     | 1        | 0.78%   |
| Yokohama         | 1        | 0.78%   |
| Yarang           | 1        | 0.78%   |
| Wroclaw          | 1        | 0.78%   |
| Woolloongabba    | 1        | 0.78%   |
| Wolgast          | 1        | 0.78%   |
| Vienna           | 1        | 0.78%   |
| Vanse            | 1        | 0.78%   |
| Tournus          | 1        | 0.78%   |
| Toronto          | 1        | 0.78%   |
| Thrissur         | 1        | 0.78%   |
| Tel Aviv         | 1        | 0.78%   |
| Tehran           | 1        | 0.78%   |
| Sydney           | 1        | 0.78%   |
| Suresnes         | 1        | 0.78%   |
| Spello           | 1        | 0.78%   |
| Songkhla         | 1        | 0.78%   |
| Sollentuna       | 1        | 0.78%   |
| Sentmenat        | 1        | 0.78%   |
| Sarrebourg       | 1        | 0.78%   |
| Sao Paulo        | 1        | 0.78%   |
| Sant Joan Despí | 1        | 0.78%   |
| Saguenay         | 1        | 0.78%   |
| Rotterdam        | 1        | 0.78%   |
| Rio de Janeiro   | 1        | 0.78%   |
| Revere           | 1        | 0.78%   |
| Ragama           | 1        | 0.78%   |
| Purley           | 1        | 0.78%   |
| Pune             | 1        | 0.78%   |
| Porto Mantovano  | 1        | 0.78%   |
| Plano            | 1        | 0.78%   |
| Plan-de-Cuques   | 1        | 0.78%   |
| Ottawa           | 1        | 0.78%   |
| Oldham           | 1        | 0.78%   |
| Oldenburg        | 1        | 0.78%   |
| Nuremberg        | 1        | 0.78%   |
| Novi Sad         | 1        | 0.78%   |
| Norton           | 1        | 0.78%   |
| New Carlisle     | 1        | 0.78%   |
| Neubrandenburg   | 1        | 0.78%   |
| Muralto          | 1        | 0.78%   |
| Munich           | 1        | 0.78%   |
| Mount Pleasant   | 1        | 0.78%   |
| Montreal         | 1        | 0.78%   |
| Montbrison       | 1        | 0.78%   |
| Monmouth         | 1        | 0.78%   |
| Milan            | 1        | 0.78%   |
| McKinney         | 1        | 0.78%   |
| Mažeikiai       | 1        | 0.78%   |
| Málaga          | 1        | 0.78%   |
| Madrid           | 1        | 0.78%   |
| Lyngdal          | 1        | 0.78%   |
| Louhans          | 1        | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 39       | 60     | 17.41%  |
| Seagate                   | 38       | 50     | 16.96%  |
| Samsung Electronics       | 30       | 48     | 13.39%  |
| Kingston                  | 22       | 27     | 9.82%   |
| Toshiba                   | 15       | 20     | 6.7%    |
| Crucial                   | 10       | 13     | 4.46%   |
| SanDisk                   | 6        | 8      | 2.68%   |
| Unknown                   | 5        | 12     | 2.23%   |
| Micron/Crucial Technology | 5        | 8      | 2.23%   |
| Intel                     | 5        | 5      | 2.23%   |
| A-DATA Technology         | 5        | 5      | 2.23%   |
| Phison                    | 4        | 4      | 1.79%   |
| Hitachi                   | 4        | 4      | 1.79%   |
| PNY                       | 3        | 7      | 1.34%   |
| Micron Technology         | 3        | 3      | 1.34%   |
| Maxtor                    | 3        | 3      | 1.34%   |
| ASMT                      | 3        | 3      | 1.34%   |
| Team                      | 2        | 3      | 0.89%   |
| Realtek Semiconductor     | 2        | 2      | 0.89%   |
| Plextor                   | 2        | 2      | 0.89%   |
| JMicron Technology        | 2        | 2      | 0.89%   |
| XPG                       | 1        | 1      | 0.45%   |
| Transcend                 | 1        | 1      | 0.45%   |
| tigo                      | 1        | 1      | 0.45%   |
| Silicon Motion            | 1        | 1      | 0.45%   |
| OCZ-VERTEX2               | 1        | 1      | 0.45%   |
| OCZ                       | 1        | 1      | 0.45%   |
| Netac                     | 1        | 1      | 0.45%   |
| MidasForce                | 1        | 1      | 0.45%   |
| LITEON                    | 1        | 1      | 0.45%   |
| Leven                     | 1        | 1      | 0.45%   |
| Intenso                   | 1        | 1      | 0.45%   |
| Hewlett-Packard           | 1        | 1      | 0.45%   |
| Goodram                   | 1        | 1      | 0.45%   |
| Gigabyte Technology       | 1        | 1      | 0.45%   |
| Corsair                   | 1        | 1      | 0.45%   |
| China                     | 1        | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 6        | 2.39%   |
| Toshiba DT01ACA050 500GB               | 4        | 1.59%   |
| Samsung SSD 860 EVO 250GB              | 4        | 1.59%   |
| Micron/Crucial NVMe SSD Drive 1TB      | 4        | 1.59%   |
| Kingston SA400S37120G 120GB SSD        | 4        | 1.59%   |
| Crucial CT240BX500SSD1 240GB           | 4        | 1.59%   |
| WDC WD5000AAKX-00ERMA0 500GB           | 3        | 1.2%    |
| Seagate ST3500418AS 500GB              | 3        | 1.2%    |
| Seagate ST1000DM010-2EP102 1TB         | 3        | 1.2%    |
| Seagate ST1000DM003-1ER162 1TB         | 3        | 1.2%    |
| Phison NVMe SSD Drive 1TB              | 3        | 1.2%    |
| Kingston SA400S37240G 240GB SSD        | 3        | 1.2%    |
| Kingston NVMe SSD Drive 1TB            | 3        | 1.2%    |
| WDC WD5000AAKX-001CA0 500GB            | 2        | 0.8%    |
| WDC WD5000AAKS-00UU3A0 500GB           | 2        | 0.8%    |
| WDC WD40EFRX-68N32N0 4TB               | 2        | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB               | 2        | 0.8%    |
| WDC WD10EZEX-00BN5A0 1TB               | 2        | 0.8%    |
| Unknown SD/MMC 16GB                    | 2        | 0.8%    |
| Unknown M.S./M.S.Pro/HG 16GB           | 2        | 0.8%    |
| Toshiba HDWD110 1TB                    | 2        | 0.8%    |
| Toshiba DT01ACA100 1TB                 | 2        | 0.8%    |
| Seagate ST2000DX002-2DV164 2TB         | 2        | 0.8%    |
| Seagate ST2000DM001-9YN164 2TB         | 2        | 0.8%    |
| Seagate ST1000DM003-1CH162 1TB         | 2        | 0.8%    |
| Samsung SSD 850 PRO 256GB              | 2        | 0.8%    |
| Samsung SSD 850 EVO 250GB              | 2        | 0.8%    |
| Samsung SSD 840 EVO 120GB              | 2        | 0.8%    |
| Samsung NVMe SSD Drive 1TB             | 2        | 0.8%    |
| Samsung HD322HJ 320GB                  | 2        | 0.8%    |
| PNY CS900 480GB SSD                    | 2        | 0.8%    |
| Kingston SV300S37A120G 120GB SSD       | 2        | 0.8%    |
| Kingston SA400S37960G 960GB SSD        | 2        | 0.8%    |
| Kingston NVMe SSD Drive 500GB          | 2        | 0.8%    |
| JMicron Tech 250GB                     | 2        | 0.8%    |
| Crucial CT1000MX500SSD1 1TB            | 2        | 0.8%    |
| XPG NVMe SSD Drive 512GB               | 1        | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1        | 0.4%    |
| WDC WDS500G1B0A-00H9H0 500GB SSD       | 1        | 0.4%    |
| WDC WDS250G1B0A-00H9H0 250GB SSD       | 1        | 0.4%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 1        | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1        | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1        | 0.4%    |
| WDC WD6401AALS-00L3B2 640GB            | 1        | 0.4%    |
| WDC WD5000LPLX-60ZNTT2 500GB           | 1        | 0.4%    |
| WDC WD5000AVDS-63U7B1 500GB            | 1        | 0.4%    |
| WDC WD5000AAKX-003CA0 500GB            | 1        | 0.4%    |
| WDC WD5000AAKS-00A7B2 500GB            | 1        | 0.4%    |
| WDC WD40EZAZ-00SF3B0 4TB               | 1        | 0.4%    |
| WDC WD3200AVJS-63B6A0 320GB            | 1        | 0.4%    |
| WDC WD3200AAJS-00L7A0 320GB            | 1        | 0.4%    |
| WDC WD30PURX-64P6ZY0 3TB               | 1        | 0.4%    |
| WDC WD30EZRZ-00Z5HB0 3TB               | 1        | 0.4%    |
| WDC WD30EZRX-00SPEB0 3TB               | 1        | 0.4%    |
| WDC WD3003FZEX-00Z4SA0 3TB             | 1        | 0.4%    |
| WDC WD2500JS-23MHB0 250GB              | 1        | 0.4%    |
| WDC WD20EZRX-00D8PB0 2TB               | 1        | 0.4%    |
| WDC WD20EFRX-68EUZN0 2TB               | 1        | 0.4%    |
| WDC WD20EARX-00PASB0 2TB               | 1        | 0.4%    |
| WDC WD1600JS-55NCB1 160GB              | 1        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 35       | 46     | 36.08%  |
| WDC                 | 33       | 47     | 34.02%  |
| Toshiba             | 14       | 19     | 14.43%  |
| Samsung Electronics | 5        | 6      | 5.15%   |
| Hitachi             | 4        | 4      | 4.12%   |
| Maxtor              | 2        | 2      | 2.06%   |
| ASMT                | 2        | 2      | 2.06%   |
| Unknown             | 1        | 1      | 1.03%   |
| Hewlett-Packard     | 1        | 1      | 1.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 27     | 20.93%  |
| Kingston            | 16       | 19     | 18.6%   |
| Crucial             | 9        | 11     | 10.47%  |
| WDC                 | 6        | 10     | 6.98%   |
| SanDisk             | 6        | 7      | 6.98%   |
| A-DATA Technology   | 4        | 4      | 4.65%   |
| PNY                 | 3        | 7      | 3.49%   |
| Intel               | 3        | 3      | 3.49%   |
| Team                | 2        | 3      | 2.33%   |
| Plextor             | 2        | 2      | 2.33%   |
| Micron Technology   | 2        | 2      | 2.33%   |
| Transcend           | 1        | 1      | 1.16%   |
| Toshiba             | 1        | 1      | 1.16%   |
| tigo                | 1        | 1      | 1.16%   |
| Seagate             | 1        | 2      | 1.16%   |
| OCZ-VERTEX2         | 1        | 1      | 1.16%   |
| OCZ                 | 1        | 1      | 1.16%   |
| MidasForce          | 1        | 1      | 1.16%   |
| Maxtor              | 1        | 1      | 1.16%   |
| LITEON              | 1        | 1      | 1.16%   |
| Leven               | 1        | 1      | 1.16%   |
| Intenso             | 1        | 1      | 1.16%   |
| Goodram             | 1        | 1      | 1.16%   |
| Gigabyte Technology | 1        | 1      | 1.16%   |
| Corsair             | 1        | 1      | 1.16%   |
| China               | 1        | 1      | 1.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 78       | 128    | 40%     |
| SSD     | 74       | 111    | 37.95%  |
| NVMe    | 34       | 49     | 17.44%  |
| Unknown | 7        | 15     | 3.59%   |
| MMC     | 2        | 2      | 1.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 109      | 235    | 69.87%  |
| NVMe | 34       | 49     | 21.79%  |
| SAS  | 11       | 19     | 7.05%   |
| MMC  | 2        | 2      | 1.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 84       | 145    | 58.33%  |
| 0.51-1.0   | 33       | 57     | 22.92%  |
| 1.01-2.0   | 11       | 14     | 7.64%   |
| 3.01-4.0   | 6        | 7      | 4.17%   |
| 2.01-3.0   | 5        | 10     | 3.47%   |
| 4.01-10.0  | 5        | 6      | 3.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 39       | 31.2%   |
| 251-500        | 28       | 22.4%   |
| 501-1000       | 25       | 20%     |
| 1001-2000      | 11       | 8.8%    |
| More than 3000 | 8        | 6.4%    |
| 51-100         | 8        | 6.4%    |
| 21-50          | 4        | 3.2%    |
| 2001-3000      | 2        | 1.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 54       | 40.6%   |
| 21-50          | 19       | 14.29%  |
| 101-250        | 19       | 14.29%  |
| 51-100         | 15       | 11.28%  |
| 251-500        | 11       | 8.27%   |
| 501-1000       | 8        | 6.02%   |
| 1001-2000      | 4        | 3.01%   |
| More than 3000 | 2        | 1.5%    |
| 2001-3000      | 1        | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00UU3A0 500GB | 1        | 1      | 33.33%  |
| Seagate ST3500312CS 500GB    | 1        | 1      | 33.33%  |
| SanDisk SSD PLUS 240GB       | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |
| SanDisk | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 66.67%  |
| SSD  | 1        | 1      | 33.33%  |

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
| Detected | 106      | 270    | 85.48%  |
| Works    | 15       | 32     | 12.1%   |
| Malfunc  | 3        | 3      | 2.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 81       | 48.21%  |
| AMD                         | 33       | 19.64%  |
| Samsung Electronics         | 12       | 7.14%   |
| Kingston Technology Company | 7        | 4.17%   |
| Micron/Crucial Technology   | 6        | 3.57%   |
| Phison Electronics          | 4        | 2.38%   |
| Nvidia                      | 4        | 2.38%   |
| Marvell Technology Group    | 4        | 2.38%   |
| ASMedia Technology          | 4        | 2.38%   |
| Realtek Semiconductor       | 3        | 1.79%   |
| Seagate Technology          | 2        | 1.19%   |
| SanDisk                     | 2        | 1.19%   |
| JMicron Technology          | 2        | 1.19%   |
| Silicon Motion              | 1        | 0.6%    |
| Micron Technology           | 1        | 0.6%    |
| LSI Logic / Symbios Logic   | 1        | 0.6%    |
| ADATA Technology            | 1        | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 20       | 9.71%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 5.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 4.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 3.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 3.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 3.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 2.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 2.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 2.91%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 5        | 2.43%   |
| Kingston Company A2000 NVMe SSD                                                         | 5        | 2.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.94%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 1.94%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.46%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.46%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 0.97%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.97%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2        | 0.97%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.97%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 0.97%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.97%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.97%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 0.97%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.97%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.49%   |
| Seagate FireCuda 530 SSD                                                                | 1        | 0.49%   |
| Seagate FireCuda 510 SSD                                                                | 1        | 0.49%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.49%   |
| SanDisk Non-Volatile memory controller                                                  | 1        | 0.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.49%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.49%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.49%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 1        | 0.49%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.49%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1        | 0.49%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 0.49%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.49%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.49%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.49%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.49%   |
| Micron/Crucial Non-Volatile memory controller                                           | 1        | 0.49%   |
| Micron Non-Volatile memory controller                                                   | 1        | 0.49%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.49%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.49%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                                 | 1        | 0.49%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 0.49%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                      | 1        | 0.49%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.49%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.49%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1        | 0.49%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1        | 0.49%   |
| Intel SSD 660P Series                                                                   | 1        | 0.49%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 99       | 59.64%  |
| NVMe | 34       | 20.48%  |
| IDE  | 26       | 15.66%  |
| RAID | 6        | 3.61%   |
| SAS  | 1        | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 83       | 69.75%  |
| AMD    | 36       | 30.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz        | 4        | 3.36%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 4        | 3.36%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 3        | 2.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3        | 2.52%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 3        | 2.52%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 3        | 2.52%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 2        | 1.68%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 2        | 1.68%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2        | 1.68%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 2        | 1.68%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 2        | 1.68%   |
| Intel Core i3 CPU 530 @ 2.93GHz         | 2        | 1.68%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz    | 2        | 1.68%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 2        | 1.68%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2        | 1.68%   |
| AMD Ryzen 5 2600X Six-Core Processor    | 2        | 1.68%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 2        | 1.68%   |
| Intel Xeon CPU E5462 @ 2.80GHz          | 1        | 0.84%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1        | 0.84%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz      | 1        | 0.84%   |
| Intel Xeon CPU E5-1660 0 @ 3.30GHz      | 1        | 0.84%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz     | 1        | 0.84%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz     | 1        | 0.84%   |
| Intel Xeon CPU E31270 @ 3.40GHz         | 1        | 0.84%   |
| Intel Xeon CPU E31240 @ 3.30GHz         | 1        | 0.84%   |
| Intel Xeon CPU E3-1283L v4 @ 2.90GHz    | 1        | 0.84%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz     | 1        | 0.84%   |
| Intel Pentium CPU G630 @ 2.70GHz        | 1        | 0.84%   |
| Intel Pentium CPU G620 @ 2.60GHz        | 1        | 0.84%   |
| Intel Pentium CPU G2030 @ 3.00GHz       | 1        | 0.84%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 1        | 0.84%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 1        | 0.84%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1        | 0.84%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1        | 0.84%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1        | 0.84%   |
| Intel Core i7-4930K CPU @ 3.40GHz       | 1        | 0.84%   |
| Intel Core i7-4790S CPU @ 3.20GHz       | 1        | 0.84%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 1        | 0.84%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1        | 0.84%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1        | 0.84%   |
| Intel Core i7-10700K CPU @ 3.80GHz      | 1        | 0.84%   |
| Intel Core i7 CPU 950 @ 3.07GHz         | 1        | 0.84%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1        | 0.84%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 1        | 0.84%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 1        | 0.84%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 1        | 0.84%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1        | 0.84%   |
| Intel Core i5-4460T CPU @ 1.90GHz       | 1        | 0.84%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 1        | 0.84%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1        | 0.84%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 1        | 0.84%   |
| Intel Core i5-10400 CPU @ 2.90GHz       | 1        | 0.84%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 1        | 0.84%   |
| Intel Core i3-9100F CPU @ 3.60GHz       | 1        | 0.84%   |
| Intel Core i3-9100 CPU @ 3.60GHz        | 1        | 0.84%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 1        | 0.84%   |
| Intel Core i3-6100 CPU @ 3.70GHz        | 1        | 0.84%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 1        | 0.84%   |
| Intel Core i3-3220 CPU @ 3.30GHz        | 1        | 0.84%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 1        | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 22       | 18.49%  |
| Intel Core i7     | 18       | 15.13%  |
| Intel Core i3     | 12       | 10.08%  |
| Intel Xeon        | 10       | 8.4%    |
| AMD Ryzen 7       | 9        | 7.56%   |
| AMD Ryzen 5       | 9        | 7.56%   |
| Other             | 5        | 4.2%    |
| AMD Ryzen 9       | 5        | 4.2%    |
| Intel Celeron     | 4        | 3.36%   |
| Intel Pentium     | 3        | 2.52%   |
| Intel Core 2 Duo  | 3        | 2.52%   |
| Intel Atom        | 3        | 2.52%   |
| AMD Phenom II X4  | 3        | 2.52%   |
| Intel Core 2 Quad | 2        | 1.68%   |
| AMD Athlon II X2  | 2        | 1.68%   |
| AMD Athlon        | 2        | 1.68%   |
| AMD A8            | 2        | 1.68%   |
| Intel Core i9     | 1        | 0.84%   |
| AMD Ryzen 3       | 1        | 0.84%   |
| AMD FX            | 1        | 0.84%   |
| AMD Athlon X4     | 1        | 0.84%   |
| AMD A10           | 1        | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 50       | 41.32%  |
| 2      | 28       | 23.14%  |
| 8      | 19       | 15.7%   |
| 6      | 16       | 13.22%  |
| 12     | 5        | 4.13%   |
| 1      | 2        | 1.65%   |
| 16     | 1        | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 118      | 99.16%  |
| 2      | 1        | 0.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 71       | 59.17%  |
| 1      | 49       | 40.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 119      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 13       | 10.83%  |
| 0x306c3    | 11       | 9.17%   |
| 0x306a9    | 9        | 7.5%    |
| Unknown    | 8        | 6.67%   |
| 0x08701021 | 6        | 5%      |
| 0x506e3    | 5        | 4.17%   |
| 0x08108109 | 4        | 3.33%   |
| 0xa0671    | 3        | 2.5%    |
| 0x906ed    | 3        | 2.5%    |
| 0x906eb    | 3        | 2.5%    |
| 0x906ea    | 3        | 2.5%    |
| 0x906e9    | 3        | 2.5%    |
| 0x206d7    | 3        | 2.5%    |
| 0x0800820d | 3        | 2.5%    |
| 0x6fb      | 2        | 1.67%   |
| 0x406c4    | 2        | 1.67%   |
| 0x20655    | 2        | 1.67%   |
| 0x20652    | 2        | 1.67%   |
| 0x1067a    | 2        | 1.67%   |
| 0x0a50000c | 2        | 1.67%   |
| 0x0a201016 | 2        | 1.67%   |
| 0x08001138 | 2        | 1.67%   |
| 0x06003106 | 2        | 1.67%   |
| 0x010000c8 | 2        | 1.67%   |
| 0xa0655    | 1        | 0.83%   |
| 0xa0653    | 1        | 0.83%   |
| 0x906ec    | 1        | 0.83%   |
| 0x90672    | 1        | 0.83%   |
| 0x806c1    | 1        | 0.83%   |
| 0x706a8    | 1        | 0.83%   |
| 0x6f7      | 1        | 0.83%   |
| 0x40671    | 1        | 0.83%   |
| 0x306f2    | 1        | 0.83%   |
| 0x306e4    | 1        | 0.83%   |
| 0x30678    | 1        | 0.83%   |
| 0x106ca    | 1        | 0.83%   |
| 0x106a5    | 1        | 0.83%   |
| 0x10676    | 1        | 0.83%   |
| 0x0a201205 | 1        | 0.83%   |
| 0x0a201009 | 1        | 0.83%   |
| 0x08701013 | 1        | 0.83%   |
| 0x08101016 | 1        | 0.83%   |
| 0x06001119 | 1        | 0.83%   |
| 0x0600063e | 1        | 0.83%   |
| 0x03000027 | 1        | 0.83%   |
| 0x010000db | 1        | 0.83%   |
| 0x010000c7 | 1        | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 17       | 14.29%  |
| KabyLake         | 14       | 11.76%  |
| Haswell          | 13       | 10.92%  |
| IvyBridge        | 10       | 8.4%    |
| Zen+             | 8        | 6.72%   |
| Zen 2            | 8        | 6.72%   |
| Zen 3            | 7        | 5.88%   |
| Skylake          | 5        | 4.2%    |
| K10              | 5        | 4.2%    |
| Westmere         | 4        | 3.36%   |
| Zen              | 3        | 2.52%   |
| Silvermont       | 3        | 2.52%   |
| Penryn           | 3        | 2.52%   |
| Icelake          | 3        | 2.52%   |
| Core             | 3        | 2.52%   |
| Steamroller      | 2        | 1.68%   |
| CometLake        | 2        | 1.68%   |
| TigerLake        | 1        | 0.84%   |
| Piledriver       | 1        | 0.84%   |
| Nehalem          | 1        | 0.84%   |
| K10 Llano        | 1        | 0.84%   |
| Goldmont plus    | 1        | 0.84%   |
| Bulldozer        | 1        | 0.84%   |
| Broadwell        | 1        | 0.84%   |
| Bonnell          | 1        | 0.84%   |
| Alderlake Hybrid | 1        | 0.84%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 45       | 35.16%  |
| Nvidia | 44       | 34.38%  |
| Intel  | 39       | 30.47%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11       | 8.4%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5        | 3.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 3.05%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4        | 3.05%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 3        | 2.29%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 2.29%   |
| Intel HD Graphics 530                                                                    | 3        | 2.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 2.29%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3        | 2.29%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 1.53%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1.53%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 1.53%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2        | 1.53%   |
| Intel HD Graphics 630                                                                    | 2        | 1.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.53%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 1.53%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 1.53%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 1.53%   |
| AMD Cezanne                                                                              | 2        | 1.53%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 1.53%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.76%   |
| Nvidia TU106 [GeForce GTX 1650]                                                          | 1        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1        | 0.76%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.76%   |
| Nvidia GP107GL [Quadro P620]                                                             | 1        | 0.76%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 0.76%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.76%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1        | 0.76%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.76%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.76%   |
| Nvidia GK110B [GeForce GTX TITAN Black]                                                  | 1        | 0.76%   |
| Nvidia GK104 [GeForce GTX 680]                                                           | 1        | 0.76%   |
| Nvidia GK104 [GeForce GTX 670]                                                           | 1        | 0.76%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                                        | 1        | 0.76%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.76%   |
| Nvidia GF110 [GeForce GTX 580]                                                           | 1        | 0.76%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 0.76%   |
| Nvidia GF100 [GeForce GTX 470]                                                           | 1        | 0.76%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 0.76%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1        | 0.76%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 1        | 0.76%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 0.76%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1        | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 0.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 0.76%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 0.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 0.76%   |
| Intel Iris Pro Graphics P6300                                                            | 1        | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 0.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 42       | 34.71%  |
| 1 x AMD        | 40       | 33.06%  |
| 1 x Intel      | 33       | 27.27%  |
| 2 x AMD        | 2        | 1.65%   |
| Intel + AMD    | 2        | 1.65%   |
| Intel + Nvidia | 1        | 0.83%   |
| AMD + Nvidia   | 1        | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 95       | 78.51%  |
| Proprietary | 25       | 20.66%  |
| Unknown     | 1        | 0.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 38       | 30.89%  |
| 1.01-2.0   | 22       | 17.89%  |
| 3.01-4.0   | 18       | 14.63%  |
| 0.51-1.0   | 17       | 13.82%  |
| 7.01-8.0   | 9        | 7.32%   |
| 0.01-0.5   | 7        | 5.69%   |
| 5.01-6.0   | 6        | 4.88%   |
| 2.01-3.0   | 3        | 2.44%   |
| 8.01-16.0  | 3        | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 21       | 15.44%  |
| Acer                 | 15       | 11.03%  |
| Goldstar             | 14       | 10.29%  |
| Hewlett-Packard      | 12       | 8.82%   |
| Philips              | 10       | 7.35%   |
| Dell                 | 9        | 6.62%   |
| BenQ                 | 6        | 4.41%   |
| Ancor Communications | 6        | 4.41%   |
| Lenovo               | 5        | 3.68%   |
| AOC                  | 5        | 3.68%   |
| Unknown              | 3        | 2.21%   |
| NEC Computers        | 2        | 1.47%   |
| LG Electronics       | 2        | 1.47%   |
| HPN                  | 2        | 1.47%   |
| Fujitsu Siemens      | 2        | 1.47%   |
| AUS                  | 2        | 1.47%   |
| ___                  | 1        | 0.74%   |
| Vizio                | 1        | 0.74%   |
| ViewSonic            | 1        | 0.74%   |
| Vestel               | 1        | 0.74%   |
| SPC                  | 1        | 0.74%   |
| Sony                 | 1        | 0.74%   |
| Sharp                | 1        | 0.74%   |
| Onkyo                | 1        | 0.74%   |
| MSI                  | 1        | 0.74%   |
| Mi                   | 1        | 0.74%   |
| LLP                  | 1        | 0.74%   |
| IOD                  | 1        | 0.74%   |
| Iiyama               | 1        | 0.74%   |
| Hitachi              | 1        | 0.74%   |
| Element              | 1        | 0.74%   |
| Eizo                 | 1        | 0.74%   |
| CHR                  | 1        | 0.74%   |
| CHD                  | 1        | 0.74%   |
| BOE                  | 1        | 0.74%   |
| Unknown              | 1        | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3        | 2.07%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2        | 1.38%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                  | 2        | 1.38%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                     | 2        | 1.38%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 2        | 1.38%   |
| ___ LCDTV16 ___9000 1360x768                                           | 1        | 0.69%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                    | 1        | 0.69%   |
| ViewSonic LCD Monitor VX2260WM 3840x1080                               | 1        | 0.69%   |
| ViewSonic LCD Monitor VX2260WM                                         | 1        | 0.69%   |
| Vestel LCD Monitor 49FHD_LCD_TV 1920x1080                              | 1        | 0.69%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 0.69%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 1        | 0.69%   |
| Unknown LCD Monitor Bit 3 LE2262 1680x1050                             | 1        | 0.69%   |
| SPC LCD Monitor SPC1900 1440x900 368x207mm 16.6-inch                   | 1        | 0.69%   |
| Sony TV SNYD703 1360x768                                               | 1        | 0.69%   |
| Sharp HDMI SHP108E 1360x768 820x460mm 37.0-inch                        | 1        | 0.69%   |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch      | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM0421 1920x1200 518x324mm 24.1-inch   | 1        | 0.69%   |
| Samsung Electronics SMBX2035 SAM06FD 1600x900 443x249mm 20.0-inch      | 1        | 0.69%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch   | 1        | 0.69%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch   | 1        | 0.69%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 598x336mm 27.0-inch      | 1        | 0.69%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch      | 1        | 0.69%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch      | 1        | 0.69%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch      | 1        | 0.69%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch       | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0C3F 3840x2160 1050x590mm 47.4-inch | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch   | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch   | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0530 1360x768                       | 1        | 0.69%   |
| Samsung Electronics LCD Monitor S22D300                                | 1        | 0.69%   |
| Samsung Electronics LC32G5xT SAM7088 2560x1440 698x393mm 31.5-inch     | 1        | 0.69%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch     | 1        | 0.69%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch              | 1        | 0.69%   |
| Philips PHL 345E2 PHLC237 3440x1440 800x335mm 34.1-inch                | 1        | 0.69%   |
| Philips PHL 275E1 PHLC20C 2560x1440 600x340mm 27.2-inch                | 1        | 0.69%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch                | 1        | 0.69%   |
| Philips PHL 203V5 PHLC0CE 1600x900 434x236mm 19.4-inch                 | 1        | 0.69%   |
| Philips LCD Monitor PHL 498P9 5120x1440                                | 1        | 0.69%   |
| Philips LCD Monitor PHL 498P9 3840x1080                                | 1        | 0.69%   |
| Philips LCD Monitor PHL 323E7 1920x1080                                | 1        | 0.69%   |
| Philips LCD Monitor PHL 276E8V 7680x2160                               | 1        | 0.69%   |
| Philips LCD Monitor PHL 276E8V 3840x2160                               | 1        | 0.69%   |
| Philips LCD Monitor PHL 276E8V                                         | 1        | 0.69%   |
| Philips LCD Monitor 19B 1280x1024                                      | 1        | 0.69%   |
| Philips 190CW PHLC023 1440x900 408x255mm 18.9-inch                     | 1        | 0.69%   |
| Onkyo PA-R200 ONK0C6B 1920x1080                                        | 1        | 0.69%   |
| NEC Computers EA221WMe NEC6778 1680x1050 474x296mm 22.0-inch           | 1        | 0.69%   |
| NEC Computers 70GX2 NEC6691 1280x1024 338x270mm 17.0-inch              | 1        | 0.69%   |
| MSI Optix MAG24C MSI1462 1920x1080 520x290mm 23.4-inch                 | 1        | 0.69%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                       | 1        | 0.69%   |
| LLP 32V3H-H6A LLP4C54 1440x900 697x392mm 31.5-inch                     | 1        | 0.69%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                       | 1        | 0.69%   |
| LG Electronics LCD Monitor 2D FHD LG TV 3840x1080                      | 1        | 0.69%   |
| Lenovo LXM-L17AB LEN17AB 1280x1024 340x270mm 17.1-inch                 | 1        | 0.69%   |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch             | 1        | 0.69%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                   | 1        | 0.69%   |
| Lenovo D22-20 LEN66AD 1920x1080 477x268mm 21.5-inch                    | 1        | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 54       | 39.42%  |
| 3840x2160 (4K)     | 13       | 9.49%   |
| 1680x1050 (WSXGA+) | 13       | 9.49%   |
| 2560x1440 (QHD)    | 11       | 8.03%   |
| 1366x768 (WXGA)    | 10       | 7.3%    |
| 1600x900 (HD+)     | 5        | 3.65%   |
| 1440x900 (WXGA+)   | 5        | 3.65%   |
| 1360x768           | 5        | 3.65%   |
| 3840x1080          | 4        | 2.92%   |
| 1280x1024 (SXGA)   | 4        | 2.92%   |
| Unknown            | 4        | 2.92%   |
| 1920x1200 (WUXGA)  | 3        | 2.19%   |
| 5120x1440          | 2        | 1.46%   |
| 3440x1440          | 2        | 1.46%   |
| 7680x2160          | 1        | 0.73%   |
| 2560x1080          | 1        | 0.73%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 17.91%  |
| 21      | 17       | 12.69%  |
| 24      | 14       | 10.45%  |
| 27      | 13       | 9.7%    |
| 23      | 13       | 9.7%    |
| 22      | 12       | 8.96%   |
| 31      | 8        | 5.97%   |
| 18      | 6        | 4.48%   |
| 32      | 3        | 2.24%   |
| 20      | 3        | 2.24%   |
| 19      | 3        | 2.24%   |
| 17      | 3        | 2.24%   |
| 72      | 2        | 1.49%   |
| 34      | 2        | 1.49%   |
| 15      | 2        | 1.49%   |
| 84      | 1        | 0.75%   |
| 55      | 1        | 0.75%   |
| 49      | 1        | 0.75%   |
| 48      | 1        | 0.75%   |
| 43      | 1        | 0.75%   |
| 37      | 1        | 0.75%   |
| 28      | 1        | 0.75%   |
| 26      | 1        | 0.75%   |
| 16      | 1        | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 39       | 29.77%  |
| 501-600     | 37       | 28.24%  |
| Unknown     | 24       | 18.32%  |
| 601-700     | 12       | 9.16%   |
| 701-800     | 5        | 3.82%   |
| 301-350     | 4        | 3.05%   |
| 1501-2000   | 3        | 2.29%   |
| 1001-1500   | 3        | 2.29%   |
| 351-400     | 2        | 1.53%   |
| 801-900     | 1        | 0.76%   |
| 901-1000    | 1        | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 77       | 62.6%   |
| Unknown | 21       | 17.07%  |
| 16/10   | 19       | 15.45%  |
| 21/9    | 3        | 2.44%   |
| 5/4     | 2        | 1.63%   |
| 32/9    | 1        | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 42       | 32.06%  |
| Unknown        | 24       | 18.32%  |
| 351-500        | 13       | 9.92%   |
| 301-350        | 13       | 9.92%   |
| 151-200        | 11       | 8.4%    |
| 251-300        | 9        | 6.87%   |
| 141-150        | 7        | 5.34%   |
| More than 1000 | 5        | 3.82%   |
| 501-1000       | 3        | 2.29%   |
| 131-140        | 1        | 0.76%   |
| 111-120        | 1        | 0.76%   |
| 101-110        | 1        | 0.76%   |
| 91-100         | 1        | 0.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 67       | 51.54%  |
| 101-120 | 26       | 20%     |
| Unknown | 24       | 18.46%  |
| 1-50    | 7        | 5.38%   |
| 121-160 | 6        | 4.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 98       | 80.99%  |
| 2     | 20       | 16.53%  |
| 3     | 2        | 1.65%   |
| 0     | 1        | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 75       | 42.86%  |
| Intel                           | 56       | 32%     |
| Qualcomm Atheros                | 7        | 4%      |
| Broadcom                        | 5        | 2.86%   |
| Samsung Electronics             | 4        | 2.29%   |
| Ralink Technology               | 4        | 2.29%   |
| TP-Link                         | 3        | 1.71%   |
| Nvidia                          | 3        | 1.71%   |
| Xiaomi                          | 2        | 1.14%   |
| Ralink                          | 2        | 1.14%   |
| vivo                            | 1        | 0.57%   |
| TRENDnet                        | 1        | 0.57%   |
| Qualcomm Atheros Communications | 1        | 0.57%   |
| Motorola PCS                    | 1        | 0.57%   |
| Microsoft                       | 1        | 0.57%   |
| Marvell Technology Group        | 1        | 0.57%   |
| Linksys                         | 1        | 0.57%   |
| LG Electronics                  | 1        | 0.57%   |
| Huawei Technologies             | 1        | 0.57%   |
| D-Link System                   | 1        | 0.57%   |
| Broadcom Limited                | 1        | 0.57%   |
| AVM                             | 1        | 0.57%   |
| Aquantia                        | 1        | 0.57%   |
| AboCom Systems                  | 1        | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                 | 52       | 26.53%  |
| Intel Wi-Fi 6 AX200                                                               | 11       | 5.61%   |
| Realtek RTL8125 2.5GbE Controller                                                 | 9        | 4.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 8        | 4.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 6        | 3.06%   |
| Intel I211 Gigabit Network Connection                                             | 6        | 3.06%   |
| Intel Ethernet Connection (2) I219-V                                              | 6        | 3.06%   |
| Realtek 802.11ac NIC                                                              | 4        | 2.04%   |
| Intel Ethernet Controller I225-V                                                  | 4        | 2.04%   |
| Intel 82579V Gigabit Network Connection                                           | 4        | 2.04%   |
| Ralink MT7601U Wireless Adapter                                                   | 3        | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                    | 2        | 1.02%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                       | 2        | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                                     | 2        | 1.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 2        | 1.02%   |
| Intel Ethernet Connection (7) I219-V                                              | 2        | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                                             | 2        | 1.02%   |
| Intel 82578DM Gigabit Network Connection                                          | 2        | 1.02%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 2        | 1.02%   |
| vivo 1806                                                                         | 1        | 0.51%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.51%   |
| TP-Link Archer T4U ver.3                                                          | 1        | 0.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1        | 0.51%   |
| TP-Link 802.11ac NIC                                                              | 1        | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.51%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.51%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                       | 1        | 0.51%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 1        | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 1        | 0.51%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 1        | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 1        | 0.51%   |
| Realtek RTL8187 Wireless Adapter                                                  | 1        | 0.51%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                        | 1        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                             | 1        | 0.51%   |
| Realtek 802.11n WLAN Adapter                                                      | 1        | 0.51%   |
| Ralink RT5372 Wireless Adapter                                                    | 1        | 0.51%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                         | 1        | 0.51%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                         | 1        | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                         | 1        | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                         | 1        | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                          | 1        | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                        | 1        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                     | 1        | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                          | 1        | 0.51%   |
| Nvidia MCP77 Ethernet                                                             | 1        | 0.51%   |
| Nvidia MCP61 Ethernet                                                             | 1        | 0.51%   |
| Nvidia MCP55 Ethernet                                                             | 1        | 0.51%   |
| Motorola PCS moto g stylus                                                        | 1        | 0.51%   |
| Microsoft Xbox 360 Wireless Adapter                                               | 1        | 0.51%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                               | 1        | 0.51%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                         | 1        | 0.51%   |
| LG AN-WF100 802.11abgn Wireless Adapter [Broadcom BCM4323]                        | 1        | 0.51%   |
| Intel Wireless-AC 9260                                                            | 1        | 0.51%   |
| Intel Wireless 8260                                                               | 1        | 0.51%   |
| Intel Wireless 3165                                                               | 1        | 0.51%   |
| Intel Wireless 3160                                                               | 1        | 0.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 1        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 23       | 36.51%  |
| Realtek Semiconductor           | 15       | 23.81%  |
| Broadcom                        | 5        | 7.94%   |
| Ralink Technology               | 4        | 6.35%   |
| TP-Link                         | 3        | 4.76%   |
| Ralink                          | 2        | 3.17%   |
| TRENDnet                        | 1        | 1.59%   |
| Qualcomm Atheros Communications | 1        | 1.59%   |
| Qualcomm Atheros                | 1        | 1.59%   |
| Microsoft                       | 1        | 1.59%   |
| Marvell Technology Group        | 1        | 1.59%   |
| Linksys                         | 1        | 1.59%   |
| LG Electronics                  | 1        | 1.59%   |
| D-Link System                   | 1        | 1.59%   |
| Broadcom Limited                | 1        | 1.59%   |
| AVM                             | 1        | 1.59%   |
| AboCom Systems                  | 1        | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 11       | 17.19%  |
| Realtek 802.11ac NIC                                                              | 4        | 6.25%   |
| Ralink MT7601U Wireless Adapter                                                   | 3        | 4.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 2        | 3.13%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 2        | 3.13%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 1.56%   |
| TP-Link Archer T4U ver.3                                                          | 1        | 1.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1        | 1.56%   |
| TP-Link 802.11ac NIC                                                              | 1        | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 1.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 1.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 1.56%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                       | 1        | 1.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 1        | 1.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 1        | 1.56%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 1        | 1.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 1        | 1.56%   |
| Realtek RTL8187 Wireless Adapter                                                  | 1        | 1.56%   |
| Realtek 802.11n WLAN Adapter                                                      | 1        | 1.56%   |
| Ralink RT5372 Wireless Adapter                                                    | 1        | 1.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                         | 1        | 1.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                         | 1        | 1.56%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1        | 1.56%   |
| Microsoft Xbox 360 Wireless Adapter                                               | 1        | 1.56%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                               | 1        | 1.56%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                         | 1        | 1.56%   |
| LG AN-WF100 802.11abgn Wireless Adapter [Broadcom BCM4323]                        | 1        | 1.56%   |
| Intel Wireless-AC 9260                                                            | 1        | 1.56%   |
| Intel Wireless 8260                                                               | 1        | 1.56%   |
| Intel Wireless 3165                                                               | 1        | 1.56%   |
| Intel Wireless 3160                                                               | 1        | 1.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 1        | 1.56%   |
| Intel Wi-Fi 6 AX201                                                               | 1        | 1.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                                    | 1        | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 1        | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                   | 1        | 1.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                      | 1        | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 1        | 1.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                  | 1        | 1.56%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]                 | 1        | 1.56%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                            | 1        | 1.56%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                       | 1        | 1.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                                   | 1        | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                                     | 1        | 1.56%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                              | 1        | 1.56%   |
| AboCom Systems AboCom Systems Inc [WN2001 Prolink Wireless-N Nano Adapter]        | 1        | 1.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 69       | 52.27%  |
| Intel                 | 44       | 33.33%  |
| Qualcomm Atheros      | 6        | 4.55%   |
| Samsung Electronics   | 4        | 3.03%   |
| Nvidia                | 3        | 2.27%   |
| Xiaomi                | 2        | 1.52%   |
| vivo                  | 1        | 0.76%   |
| Motorola PCS          | 1        | 0.76%   |
| Huawei Technologies   | 1        | 0.76%   |
| Aquantia              | 1        | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52       | 39.39%  |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 6.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 6.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 4.55%   |
| Intel I211 Gigabit Network Connection                             | 6        | 4.55%   |
| Intel Ethernet Connection (2) I219-V                              | 6        | 4.55%   |
| Intel Ethernet Controller I225-V                                  | 4        | 3.03%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 3.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 1.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2        | 1.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.52%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.52%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.52%   |
| vivo 1806                                                         | 1        | 0.76%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.76%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.76%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.76%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.76%   |
| Motorola PCS moto g stylus                                        | 1        | 0.76%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.76%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.76%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.76%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.76%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.76%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.76%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.76%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.76%   |
| Huawei COL-L29                                                    | 1        | 0.76%   |
| Aquantia Ethernet controller                                      | 1        | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 119      | 66.85%  |
| WiFi     | 59       | 33.15%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 88       | 77.88%  |
| WiFi     | 25       | 22.12%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 78       | 65%     |
| 2     | 35       | 29.17%  |
| 3     | 6        | 5%      |
| 0     | 1        | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 89       | 73.55%  |
| Yes  | 32       | 26.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 22       | 46.81%  |
| Cambridge Silicon Radio | 12       | 25.53%  |
| Realtek Semiconductor   | 4        | 8.51%   |
| Broadcom                | 3        | 6.38%   |
| ASUSTek Computer        | 2        | 4.26%   |
| Apple                   | 2        | 4.26%   |
| Qcom                    | 1        | 2.13%   |
| IMC Networks            | 1        | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12       | 25.53%  |
| Intel AX200 Bluetooth                               | 10       | 21.28%  |
| Intel Bluetooth wireless interface                  | 4        | 8.51%   |
| Realtek Bluetooth Radio                             | 3        | 6.38%   |
| Intel Bluetooth Device                              | 3        | 6.38%   |
| Intel AX210 Bluetooth                               | 2        | 4.26%   |
| Realtek Bluetooth 5.1 Radio                         | 1        | 2.13%   |
| Qcom Bluetooth USB                                  | 1        | 2.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 2.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 2.13%   |
| IMC Networks BCM20702A0                             | 1        | 2.13%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 2.13%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 2.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 2.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 2.13%   |
| ASUS BCM20702A0                                     | 1        | 2.13%   |
| Apple Bluetooth USB Host Controller                 | 1        | 2.13%   |
| Apple Bluetooth HCI                                 | 1        | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 76       | 37.81%  |
| AMD                      | 51       | 25.37%  |
| Nvidia                   | 45       | 22.39%  |
| C-Media Electronics      | 9        | 4.48%   |
| Creative Labs            | 7        | 3.48%   |
| Logitech                 | 3        | 1.49%   |
| Focusrite-Novation       | 2        | 1%      |
| Razer USA                | 1        | 0.5%    |
| Native Instruments       | 1        | 0.5%    |
| Micro Star International | 1        | 0.5%    |
| GN Netcom                | 1        | 0.5%    |
| Generalplus Technology   | 1        | 0.5%    |
| Creative Technology      | 1        | 0.5%    |
| Corsair                  | 1        | 0.5%    |
| ASUSTek Computer         | 1        | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 17       | 7.39%   |
| AMD Starship/Matisse HD Audio Controller                                          | 11       | 4.78%   |
| Intel Cannon Lake PCH cAVS                                                        | 7        | 3.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 7        | 3.04%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7        | 3.04%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 7        | 3.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6        | 2.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6        | 2.61%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6        | 2.61%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 2.17%   |
| Nvidia GF108 High Definition Audio Controller                                     | 5        | 2.17%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 2.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 5        | 2.17%   |
| Nvidia TU104 HD Audio Controller                                                  | 4        | 1.74%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4        | 1.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4        | 1.74%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 4        | 1.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.74%   |
| AMD FCH Azalia Controller                                                         | 4        | 1.74%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 1.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3        | 1.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 1.3%    |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 1.3%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3        | 1.3%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 1.3%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 3        | 1.3%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 0.87%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 0.87%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 0.87%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 0.87%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 0.87%   |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 0.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 0.87%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 0.87%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 2        | 0.87%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 0.87%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 0.87%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 0.87%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 2        | 0.87%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 0.87%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver]        | 1        | 0.43%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 0.43%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 0.43%   |
| Nvidia MCP55 High Definition Audio                                                | 1        | 0.43%   |
| Nvidia High Definition Audio Controller                                           | 1        | 0.43%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1        | 0.43%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.43%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1        | 0.43%   |
| Nvidia GK110 High Definition Audio Controller                                     | 1        | 0.43%   |
| Nvidia GF110 High Definition Audio Controller                                     | 1        | 0.43%   |
| Nvidia GF100 High Definition Audio Controller                                     | 1        | 0.43%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 0.43%   |
| Native Instruments Traktor Audio 2 MK2                                            | 1        | 0.43%   |
| Micro Star International USB Audio                                                | 1        | 0.43%   |
| Logitech Headset H340                                                             | 1        | 0.43%   |
| Logitech G933 Wireless Headset Dongle                                             | 1        | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 20.83%  |
| Kingston            | 5        | 20.83%  |
| SK hynix            | 3        | 12.5%   |
| Unknown             | 2        | 8.33%   |
| Corsair             | 2        | 8.33%   |
| Ramaxel Technology  | 1        | 4.17%   |
| PNY                 | 1        | 4.17%   |
| Patriot             | 1        | 4.17%   |
| Micron Technology   | 1        | 4.17%   |
| G.Skill             | 1        | 4.17%   |
| Crucial             | 1        | 4.17%   |
| A-DATA Technology   | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s              | 1        | 4.17%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                   | 1        | 4.17%   |
| SK hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s     | 1        | 4.17%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 4.17%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1        | 4.17%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s              | 1        | 4.17%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1        | 4.17%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1        | 4.17%   |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s       | 1        | 4.17%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s       | 1        | 4.17%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s | 1        | 4.17%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3200MT/s       | 1        | 4.17%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s        | 1        | 4.17%   |
| Micron RAM Module 16384MB DIMM DDR3 1600MT/s              | 1        | 4.17%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s         | 1        | 4.17%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s     | 1        | 4.17%   |
| Kingston RAM 9905783-049.A01G 16384MB DIMM 4800MT/s       | 1        | 4.17%   |
| Kingston RAM 9905625-030.A00G 8GB DIMM 2133MT/s           | 1        | 4.17%   |
| Kingston RAM 9905471-015.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 4.17%   |
| G.Skill RAM F3-14900CL9-2GBXM 2048MB DIMM DDR3 1600MT/s   | 1        | 4.17%   |
| Crucial RAM CT25664BA1339.C8FE 2048MB DIMM DDR3 1333MT/s  | 1        | 4.17%   |
| Corsair RAM CMX8GX3M1A1600C11 8192MB DIMM DDR3 1600MT/s   | 1        | 4.17%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s      | 1        | 4.17%   |
| A-DATA RAM Module 4096MB DIMM DDR4 2400MT/s               | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 9        | 50%     |
| DDR4    | 7        | 38.89%  |
| Unknown | 2        | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 16       | 88.89%  |
| SODIMM | 2        | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 42.11%  |
| 4096  | 5        | 26.32%  |
| 16384 | 4        | 21.05%  |
| 32768 | 1        | 5.26%   |
| 2048  | 1        | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 23.81%  |
| 1066  | 3        | 14.29%  |
| 3200  | 2        | 9.52%   |
| 1333  | 2        | 9.52%   |
| 4800  | 1        | 4.76%   |
| 3600  | 1        | 4.76%   |
| 2933  | 1        | 4.76%   |
| 2800  | 1        | 4.76%   |
| 2666  | 1        | 4.76%   |
| 2400  | 1        | 4.76%   |
| 2200  | 1        | 4.76%   |
| 2133  | 1        | 4.76%   |
| 1800  | 1        | 4.76%   |

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
| Logitech                      | 6        | 33.33%  |
| Microsoft                     | 2        | 11.11%  |
| Chicony Electronics           | 2        | 11.11%  |
| Apple                         | 2        | 11.11%  |
| SunplusIT                     | 1        | 5.56%   |
| Sunplus Innovation Technology | 1        | 5.56%   |
| Razer USA                     | 1        | 5.56%   |
| Microdia                      | 1        | 5.56%   |
| ANYKA                         | 1        | 5.56%   |
| Alcor Micro                   | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Chicony HP High Definition 1MP Webcam | 2        | 11.11%  |
| Apple iPhone 5/5C/5S/6/SE             | 2        | 11.11%  |
| SunplusIT MTD camera                  | 1        | 5.56%   |
| Sunplus FHD Camera Microphone         | 1        | 5.56%   |
| Razer USA Razer Kiyo Pro              | 1        | 5.56%   |
| Microsoft LifeCam VX-800              | 1        | 5.56%   |
| Microsoft LifeCam HD-3000             | 1        | 5.56%   |
| Microdia Rapoo camera                 | 1        | 5.56%   |
| Logitech Webcam C925e                 | 1        | 5.56%   |
| Logitech QuickCam Communicate Deluxe  | 1        | 5.56%   |
| Logitech Logi 4K Stream Edition       | 1        | 5.56%   |
| Logitech HD Webcam C910               | 1        | 5.56%   |
| Logitech HD Webcam C615               | 1        | 5.56%   |
| Logitech B525 HD Webcam               | 1        | 5.56%   |
| ANYKA V380 FHD Camera                 | 1        | 5.56%   |
| Alcor Micro USB 2.0 PC Camera         | 1        | 5.56%   |

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
| 0     | 105      | 86.07%  |
| 1     | 14       | 11.48%  |
| 2     | 2        | 1.64%   |
| 4     | 1        | 0.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 10       | 50%     |
| Unassigned class      | 2        | 10%     |
| Sound                 | 2        | 10%     |
| Graphics card         | 2        | 10%     |
| Storage/ide           | 1        | 5%      |
| Multimedia controller | 1        | 5%      |
| Fingerprint reader    | 1        | 5%      |
| Bluetooth             | 1        | 5%      |

