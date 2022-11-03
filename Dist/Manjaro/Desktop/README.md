Manjaro - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

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

Total: 3348

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 8054                        | [0f866b3605](https://linux-hardware.org/?probe=0f866b3605) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| MSI           | Z370 GAMING PLUS            | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [8ce0b9271b](https://linux-hardware.org/?probe=8ce0b9271b) | Nov 01, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Acer          | H410H6-M17 P21-A1           | [9333be5120](https://linux-hardware.org/?probe=9333be5120) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6e577f6de5](https://linux-hardware.org/?probe=6e577f6de5) | Nov 01, 2022 |
| HP            | 3397                        | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Gigabyte      | Z77M-D3H                    | [83cd207e4e](https://linux-hardware.org/?probe=83cd207e4e) | Oct 30, 2022 |
| ASRock        | X570 Pro4                   | [d2407c253b](https://linux-hardware.org/?probe=d2407c253b) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [06cb3f01ba](https://linux-hardware.org/?probe=06cb3f01ba) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| ASUSTek       | PRIME B365M-C               | [ccf9650f9a](https://linux-hardware.org/?probe=ccf9650f9a) | Oct 29, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| ASRock        | B550M Pro4                  | [b21b6b2908](https://linux-hardware.org/?probe=b21b6b2908) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| Unknown       | 1.0                         | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Acer          | Aspire MC605 v1.0           | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [4b88876126](https://linux-hardware.org/?probe=4b88876126) | Oct 24, 2022 |
| HP            | 828A                        | [2123f2610c](https://linux-hardware.org/?probe=2123f2610c) | Oct 24, 2022 |
| MSI           | Z68MA-G45                   | [3f398756eb](https://linux-hardware.org/?probe=3f398756eb) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | [d96627943d](https://linux-hardware.org/?probe=d96627943d) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [7cb3500943](https://linux-hardware.org/?probe=7cb3500943) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [e1dedae10a](https://linux-hardware.org/?probe=e1dedae10a) | Oct 22, 2022 |
| ASRock        | H310CM-HDV                  | [afe54b52c9](https://linux-hardware.org/?probe=afe54b52c9) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [7f069e1021](https://linux-hardware.org/?probe=7f069e1021) | Oct 20, 2022 |
| ASUSTek       | H110M-K                     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| ASUSTek       | H170 PRO GAMING             | [cb86d1ba99](https://linux-hardware.org/?probe=cb86d1ba99) | Oct 18, 2022 |
| ASRock        | X670E PG Lightning          | [c3ce6dce01](https://linux-hardware.org/?probe=c3ce6dce01) | Oct 18, 2022 |
| Foxconn       | 2ABF                        | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASRock        | H310CM-HDV                  | [2426012acb](https://linux-hardware.org/?probe=2426012acb) | Oct 18, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [98024d1066](https://linux-hardware.org/?probe=98024d1066) | Oct 17, 2022 |
| MACHINIST     | X79 V2.82H                  | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [7de3eff9df](https://linux-hardware.org/?probe=7de3eff9df) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [93e82a30ac](https://linux-hardware.org/?probe=93e82a30ac) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [eb9b7e329b](https://linux-hardware.org/?probe=eb9b7e329b) | Oct 16, 2022 |
| ASUSTek       | P8H77-V                     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| Gigabyte      | H510M H                     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| HP            | 802E                        | [6231a344aa](https://linux-hardware.org/?probe=6231a344aa) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [a71fb08b36](https://linux-hardware.org/?probe=a71fb08b36) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [abf7c780d2](https://linux-hardware.org/?probe=abf7c780d2) | Oct 13, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f55bb836c3](https://linux-hardware.org/?probe=f55bb836c3) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d006fa9a19](https://linux-hardware.org/?probe=d006fa9a19) | Oct 11, 2022 |
| Gigabyte      | B450M H                     | [36fc5f2c90](https://linux-hardware.org/?probe=36fc5f2c90) | Oct 10, 2022 |
| Gigabyte      | B450M H                     | [c3dc2e33df](https://linux-hardware.org/?probe=c3dc2e33df) | Oct 10, 2022 |
| HP            | 8460                        | [08601807cc](https://linux-hardware.org/?probe=08601807cc) | Oct 10, 2022 |
| HP            | 8460                        | [5be586f271](https://linux-hardware.org/?probe=5be586f271) | Oct 10, 2022 |
| ASUSTek       | P6X58-E-WS                  | [786a8ba316](https://linux-hardware.org/?probe=786a8ba316) | Oct 09, 2022 |
| Dell          | 0TTDMJ A00                  | [656b9369be](https://linux-hardware.org/?probe=656b9369be) | Oct 09, 2022 |
| ASRock        | B550M Steel Legend          | [740a5f78d8](https://linux-hardware.org/?probe=740a5f78d8) | Oct 09, 2022 |
| Gigabyte      | B450 GAMING X               | [a297c351ed](https://linux-hardware.org/?probe=a297c351ed) | Oct 09, 2022 |
| Dell          | 0NW73C A00                  | [2b0a3f91ea](https://linux-hardware.org/?probe=2b0a3f91ea) | Oct 08, 2022 |
| Dell          | 0M9KCM A01                  | [6fa93f6da5](https://linux-hardware.org/?probe=6fa93f6da5) | Oct 07, 2022 |
| Gigabyte      | P55M-UD2                    | [e9627c4c34](https://linux-hardware.org/?probe=e9627c4c34) | Oct 07, 2022 |
| Dell          | 0D24M8 A00                  | [8130af2fab](https://linux-hardware.org/?probe=8130af2fab) | Oct 06, 2022 |
| HP            | 87D6 SMVB                   | [03cf885086](https://linux-hardware.org/?probe=03cf885086) | Oct 05, 2022 |
| Gigabyte      | H510M H                     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| HP            | 21D0                        | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| Dell          | 0HN7XN A00                  | [77776da6f7](https://linux-hardware.org/?probe=77776da6f7) | Oct 03, 2022 |
| Dell          | 0HN7XN A00                  | [84d4748b3e](https://linux-hardware.org/?probe=84d4748b3e) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [668ad3e30a](https://linux-hardware.org/?probe=668ad3e30a) | Oct 02, 2022 |
| ASRock        | B450 Pro4                   | [402a7995c4](https://linux-hardware.org/?probe=402a7995c4) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [15a068e26b](https://linux-hardware.org/?probe=15a068e26b) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3a9d882d91](https://linux-hardware.org/?probe=3a9d882d91) | Oct 01, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dda857d7e6](https://linux-hardware.org/?probe=dda857d7e6) | Oct 01, 2022 |
| Gigabyte      | Z170X-Gaming GT             | [991ea6c93f](https://linux-hardware.org/?probe=991ea6c93f) | Oct 01, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [32a742b50d](https://linux-hardware.org/?probe=32a742b50d) | Oct 01, 2022 |
| Dell          | 07PR60 A01                  | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| Dell          | 0HN7XN A00                  | [c9126cd382](https://linux-hardware.org/?probe=c9126cd382) | Sep 30, 2022 |
| ASRock        | X399M Taichi                | [b7943d1645](https://linux-hardware.org/?probe=b7943d1645) | Sep 29, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| ASRock        | J3160DC-ITX                 | [7e1818288f](https://linux-hardware.org/?probe=7e1818288f) | Sep 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [c83049a0f6](https://linux-hardware.org/?probe=c83049a0f6) | Sep 29, 2022 |
| ASRock        | Z97 Pro3                    | [7b34a50df8](https://linux-hardware.org/?probe=7b34a50df8) | Sep 28, 2022 |
| ASRock        | B450 Pro4                   | [6a9066019c](https://linux-hardware.org/?probe=6a9066019c) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [27ce89f701](https://linux-hardware.org/?probe=27ce89f701) | Sep 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [30507c8461](https://linux-hardware.org/?probe=30507c8461) | Sep 27, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [e5b4fe8914](https://linux-hardware.org/?probe=e5b4fe8914) | Sep 25, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [c65cbf84dc](https://linux-hardware.org/?probe=c65cbf84dc) | Sep 25, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e47b2b85dc](https://linux-hardware.org/?probe=e47b2b85dc) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [719b20fd4e](https://linux-hardware.org/?probe=719b20fd4e) | Sep 24, 2022 |
| Huanan        | X99-TF                      | [1361d73bcd](https://linux-hardware.org/?probe=1361d73bcd) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1faf714086](https://linux-hardware.org/?probe=1faf714086) | Sep 21, 2022 |
| Minix         | NEO G41V-4 Max              | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6c7d6ef178](https://linux-hardware.org/?probe=6c7d6ef178) | Sep 20, 2022 |
| Dell          | 040DDP A01                  | [635c6895e1](https://linux-hardware.org/?probe=635c6895e1) | Sep 20, 2022 |
| Intel         | X99 V1.0                    | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [25d7dc8f0d](https://linux-hardware.org/?probe=25d7dc8f0d) | Sep 19, 2022 |
| Gigabyte      | A320M-H-CF                  | [a3e30957c7](https://linux-hardware.org/?probe=a3e30957c7) | Sep 19, 2022 |
| HP            | 212B                        | [c823e0060e](https://linux-hardware.org/?probe=c823e0060e) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [b0836f0c26](https://linux-hardware.org/?probe=b0836f0c26) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [a28b408f4a](https://linux-hardware.org/?probe=a28b408f4a) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [3b6b90fee6](https://linux-hardware.org/?probe=3b6b90fee6) | Sep 18, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [d11c4e27df](https://linux-hardware.org/?probe=d11c4e27df) | Sep 18, 2022 |
| Intel         | X99 V1.0                    | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Foxconn       | 2ADA                        | [b136916fb3](https://linux-hardware.org/?probe=b136916fb3) | Sep 16, 2022 |
| BESSTAR Te... | UM700                       | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| ASRock        | B450M Pro4                  | [19a46a2f8e](https://linux-hardware.org/?probe=19a46a2f8e) | Sep 16, 2022 |
| ASUSTek       | PRIME H410M-E               | [91f1fdc978](https://linux-hardware.org/?probe=91f1fdc978) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASUSTek       | X99-DELUXE II               | [8c9013ec12](https://linux-hardware.org/?probe=8c9013ec12) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Gigabyte      | H77M-D3H                    | [3767b84078](https://linux-hardware.org/?probe=3767b84078) | Sep 12, 2022 |
| Foxconn       | 2ADA                        | [1b43b0d291](https://linux-hardware.org/?probe=1b43b0d291) | Sep 11, 2022 |
| MSI           | B350M BAZOOKA               | [ff7d2e74a5](https://linux-hardware.org/?probe=ff7d2e74a5) | Sep 11, 2022 |
| ASRock        | J3160DC-ITX                 | [e854b82ab9](https://linux-hardware.org/?probe=e854b82ab9) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [70f5e3d77c](https://linux-hardware.org/?probe=70f5e3d77c) | Sep 08, 2022 |
| HP            | 3397                        | [0ebeef29bf](https://linux-hardware.org/?probe=0ebeef29bf) | Sep 07, 2022 |
| Intel         | Unknown                     | [2758407d23](https://linux-hardware.org/?probe=2758407d23) | Sep 07, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [d35810173c](https://linux-hardware.org/?probe=d35810173c) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| MSI           | Z87-G41 PC Mate             | [775e007fc8](https://linux-hardware.org/?probe=775e007fc8) | Sep 05, 2022 |
| Intel         | B75                         | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [43267285d4](https://linux-hardware.org/?probe=43267285d4) | Sep 04, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [518aa50eb0](https://linux-hardware.org/?probe=518aa50eb0) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [4a27f8b033](https://linux-hardware.org/?probe=4a27f8b033) | Sep 04, 2022 |
| HP            | 8054                        | [878115f808](https://linux-hardware.org/?probe=878115f808) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [65562b09e0](https://linux-hardware.org/?probe=65562b09e0) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ASUSTek       | P6X58D-E                    | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| HP            | 8054                        | [1586ce33d1](https://linux-hardware.org/?probe=1586ce33d1) | Sep 02, 2022 |
| ASRock        | N68-S                       | [df5d34428a](https://linux-hardware.org/?probe=df5d34428a) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [5ba264dfb2](https://linux-hardware.org/?probe=5ba264dfb2) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [169c9af937](https://linux-hardware.org/?probe=169c9af937) | Sep 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [f872d36cd5](https://linux-hardware.org/?probe=f872d36cd5) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [37695eb7e5](https://linux-hardware.org/?probe=37695eb7e5) | Aug 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d816d2ade0](https://linux-hardware.org/?probe=d816d2ade0) | Aug 30, 2022 |
| ASRock        | N68-S                       | [6aabf89438](https://linux-hardware.org/?probe=6aabf89438) | Aug 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [e05dcd4a08](https://linux-hardware.org/?probe=e05dcd4a08) | Aug 29, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | [422af9d6b5](https://linux-hardware.org/?probe=422af9d6b5) | Aug 29, 2022 |
| ASRock        | N68-S                       | [4fff0a6104](https://linux-hardware.org/?probe=4fff0a6104) | Aug 29, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [ec9f8ea30e](https://linux-hardware.org/?probe=ec9f8ea30e) | Aug 28, 2022 |
| ASRock        | B550M Pro4                  | [8c6b85a46c](https://linux-hardware.org/?probe=8c6b85a46c) | Aug 27, 2022 |
| ASRock        | B450M Pro4                  | [f4fe5fd168](https://linux-hardware.org/?probe=f4fe5fd168) | Aug 27, 2022 |
| Gigabyte      | B550 GAMING X V2            | [94e2f7cedc](https://linux-hardware.org/?probe=94e2f7cedc) | Aug 27, 2022 |
| Dell          | 0KWVT8 A02                  | [3f9c00b0da](https://linux-hardware.org/?probe=3f9c00b0da) | Aug 27, 2022 |
| ASRock        | X99 WS                      | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| ASUSTek       | Z170-P                      | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | B550M S2H                   | [8b5fe2494e](https://linux-hardware.org/?probe=8b5fe2494e) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0dbe2c5dfd](https://linux-hardware.org/?probe=0dbe2c5dfd) | Aug 22, 2022 |
| MACHINIST     | H81M-PRO S1 V2.0            | [12be75fa90](https://linux-hardware.org/?probe=12be75fa90) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [3b799e56c6](https://linux-hardware.org/?probe=3b799e56c6) | Aug 21, 2022 |
| MSI           | P55-GD55                    | [89f2c92fa1](https://linux-hardware.org/?probe=89f2c92fa1) | Aug 21, 2022 |
| ASUSTek       | PRIME B365M-C               | [8ae386a7a0](https://linux-hardware.org/?probe=8ae386a7a0) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1d1f39fd1b](https://linux-hardware.org/?probe=1d1f39fd1b) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d59342b7a4](https://linux-hardware.org/?probe=d59342b7a4) | Aug 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [e61c3cee8a](https://linux-hardware.org/?probe=e61c3cee8a) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [41b271c4e7](https://linux-hardware.org/?probe=41b271c4e7) | Aug 17, 2022 |
| Gigabyte      | H61M-S2P                    | [49aedf1cf8](https://linux-hardware.org/?probe=49aedf1cf8) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | [e04617befa](https://linux-hardware.org/?probe=e04617befa) | Aug 17, 2022 |
| MSI           | Z87-G41 PC Mate             | [08e79a0a1c](https://linux-hardware.org/?probe=08e79a0a1c) | Aug 16, 2022 |
| MSI           | X470 GAMING PRO             | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| ASRock        | Z77 Extreme4                | [07e825ed5b](https://linux-hardware.org/?probe=07e825ed5b) | Aug 16, 2022 |
| VS Company    | H61H2                       | [a0b88242a4](https://linux-hardware.org/?probe=a0b88242a4) | Aug 16, 2022 |
| Gigabyte      | B450 AORUS M                | [bdf5ba285f](https://linux-hardware.org/?probe=bdf5ba285f) | Aug 15, 2022 |
| Gigabyte      | B550M S2H                   | [db7b7b3126](https://linux-hardware.org/?probe=db7b7b3126) | Aug 15, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [2fb0eea98c](https://linux-hardware.org/?probe=2fb0eea98c) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [76e185a2e5](https://linux-hardware.org/?probe=76e185a2e5) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| ASRock        | 990FX Extreme3              | [646169ae62](https://linux-hardware.org/?probe=646169ae62) | Aug 14, 2022 |
| HP            | 82A2                        | [bc3d667d42](https://linux-hardware.org/?probe=bc3d667d42) | Aug 13, 2022 |
| MSI           | B350M PRO-VD PLUS           | [ba65d9b67e](https://linux-hardware.org/?probe=ba65d9b67e) | Aug 13, 2022 |
| MSI           | 970A SLI Krait Edition      | [a94fe940b1](https://linux-hardware.org/?probe=a94fe940b1) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [41560e8e13](https://linux-hardware.org/?probe=41560e8e13) | Aug 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f82761570b](https://linux-hardware.org/?probe=f82761570b) | Aug 12, 2022 |
| AZW           | U59                         | [344d4587f6](https://linux-hardware.org/?probe=344d4587f6) | Aug 12, 2022 |
| ASRock        | 990FX Extreme3              | [e3006f6ca1](https://linux-hardware.org/?probe=e3006f6ca1) | Aug 11, 2022 |
| ASUSTek       | Z87-PRO                     | [f8a688c41e](https://linux-hardware.org/?probe=f8a688c41e) | Aug 11, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [3219cc3946](https://linux-hardware.org/?probe=3219cc3946) | Aug 10, 2022 |
| HP            | 8053                        | [db80dc0ee1](https://linux-hardware.org/?probe=db80dc0ee1) | Aug 10, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| Unknown       | Unknown                     | [e4c7906333](https://linux-hardware.org/?probe=e4c7906333) | Aug 09, 2022 |
| Lenovo        | Bantry CRB NOK              | [fbeb21c99a](https://linux-hardware.org/?probe=fbeb21c99a) | Aug 09, 2022 |
| ASUSTek       | G10DK                       | [2401d4af44](https://linux-hardware.org/?probe=2401d4af44) | Aug 08, 2022 |
| MSI           | MAG B550M MORTAR            | [7cf010b820](https://linux-hardware.org/?probe=7cf010b820) | Aug 08, 2022 |
| ASRock        | B450 Pro4                   | [b87492e7c7](https://linux-hardware.org/?probe=b87492e7c7) | Aug 08, 2022 |
| Gigabyte      | B150M-D3H-CF                | [5235533a87](https://linux-hardware.org/?probe=5235533a87) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [a3aa8d0879](https://linux-hardware.org/?probe=a3aa8d0879) | Aug 05, 2022 |
| Dell          | 0XR1GT A00                  | [2e069ba5c2](https://linux-hardware.org/?probe=2e069ba5c2) | Aug 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [e963ce265b](https://linux-hardware.org/?probe=e963ce265b) | Aug 04, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [22b43d3149](https://linux-hardware.org/?probe=22b43d3149) | Aug 04, 2022 |
| ECS           | H61H2-MV                    | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [5951f66289](https://linux-hardware.org/?probe=5951f66289) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [30e0a23365](https://linux-hardware.org/?probe=30e0a23365) | Aug 01, 2022 |
| ASUSTek       | F2A55-M LK2                 | [97a5e9c390](https://linux-hardware.org/?probe=97a5e9c390) | Aug 01, 2022 |
| Dell          | 0D24M8 A00                  | [6367e245e6](https://linux-hardware.org/?probe=6367e245e6) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9ea9e6f737](https://linux-hardware.org/?probe=9ea9e6f737) | Jul 30, 2022 |
| MSI           | X470 GAMING PRO MAX         | [5651db0a63](https://linux-hardware.org/?probe=5651db0a63) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [1fd9e0ca3a](https://linux-hardware.org/?probe=1fd9e0ca3a) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [309df31c47](https://linux-hardware.org/?probe=309df31c47) | Jul 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [fa38197b4d](https://linux-hardware.org/?probe=fa38197b4d) | Jul 29, 2022 |
| Lenovo        | 3133 SDK0J40675 WIN 3305... | [4434d4d78a](https://linux-hardware.org/?probe=4434d4d78a) | Jul 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f666b16fde](https://linux-hardware.org/?probe=f666b16fde) | Jul 28, 2022 |
| Gigabyte      | H97-Gaming 3                | [90656d8ef4](https://linux-hardware.org/?probe=90656d8ef4) | Jul 27, 2022 |
| Lenovo        | 3717 SDK0J40697 WIN 3305... | [701f519b4c](https://linux-hardware.org/?probe=701f519b4c) | Jul 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [b41540a078](https://linux-hardware.org/?probe=b41540a078) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [331a99ef9a](https://linux-hardware.org/?probe=331a99ef9a) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [1f3433b9e1](https://linux-hardware.org/?probe=1f3433b9e1) | Jul 26, 2022 |
| Gigabyte      | 990XA-UD3                   | [803bd277e7](https://linux-hardware.org/?probe=803bd277e7) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| Gigabyte      | Z68P-DS3                    | [b03f1fee53](https://linux-hardware.org/?probe=b03f1fee53) | Jul 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e512b2f9f2](https://linux-hardware.org/?probe=e512b2f9f2) | Jul 23, 2022 |
| Dell          | 0GM819                      | [8c617c1c3f](https://linux-hardware.org/?probe=8c617c1c3f) | Jul 23, 2022 |
| BESSTAR Te... | HM90                        | [cb4da5b649](https://linux-hardware.org/?probe=cb4da5b649) | Jul 23, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9002ca2e54](https://linux-hardware.org/?probe=9002ca2e54) | Jul 23, 2022 |
| ASUSTek       | Maximus Formula             | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| BESSTAR Te... | HM90                        | [380230bbf6](https://linux-hardware.org/?probe=380230bbf6) | Jul 22, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [51c2b5bc3b](https://linux-hardware.org/?probe=51c2b5bc3b) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| ASUSTek       | P9X79                       | [5ff04691ce](https://linux-hardware.org/?probe=5ff04691ce) | Jul 21, 2022 |
| ASUSTek       | P9X79                       | [1bcee43b6e](https://linux-hardware.org/?probe=1bcee43b6e) | Jul 21, 2022 |
| ASRock        | Z77 Extreme4                | [492529f973](https://linux-hardware.org/?probe=492529f973) | Jul 21, 2022 |
| PCWare        | IPMH81G1                    | [cb66716a63](https://linux-hardware.org/?probe=cb66716a63) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [63489ff6e5](https://linux-hardware.org/?probe=63489ff6e5) | Jul 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [fd46c32d92](https://linux-hardware.org/?probe=fd46c32d92) | Jul 19, 2022 |
| ASUSTek       | Maximus Formula             | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [b28f8248b4](https://linux-hardware.org/?probe=b28f8248b4) | Jul 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [84d62872f5](https://linux-hardware.org/?probe=84d62872f5) | Jul 17, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [3b1f082065](https://linux-hardware.org/?probe=3b1f082065) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [3605f29c73](https://linux-hardware.org/?probe=3605f29c73) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [533392d790](https://linux-hardware.org/?probe=533392d790) | Jul 16, 2022 |
| Gigabyte      | A520M S2H                   | [dfc64d417f](https://linux-hardware.org/?probe=dfc64d417f) | Jul 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [06992e615b](https://linux-hardware.org/?probe=06992e615b) | Jul 15, 2022 |
| BESSTAR Te... | TL50                        | [c77ff65710](https://linux-hardware.org/?probe=c77ff65710) | Jul 15, 2022 |
| ASRock        | B550M Pro4                  | [dcdc04db9f](https://linux-hardware.org/?probe=dcdc04db9f) | Jul 14, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| MSI           | X470 GAMING PRO             | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| ASUSTek       | Maximus Formula             | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| MSI           | A320M-A PRO MAX             | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | [8bdaa5b844](https://linux-hardware.org/?probe=8bdaa5b844) | Jul 13, 2022 |
| BESSTAR Te... | UM350                       | [7437e30da5](https://linux-hardware.org/?probe=7437e30da5) | Jul 11, 2022 |
| MSI           | Z77A-G45                    | [ff2bae4518](https://linux-hardware.org/?probe=ff2bae4518) | Jul 11, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [5c8deeb62c](https://linux-hardware.org/?probe=5c8deeb62c) | Jul 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | [02cbc3a4ae](https://linux-hardware.org/?probe=02cbc3a4ae) | Jul 10, 2022 |
| MSI           | Z77A-G45                    | [2d4a011972](https://linux-hardware.org/?probe=2d4a011972) | Jul 10, 2022 |
| Gigabyte      | B365M DS3H                  | [8c2d8a89d0](https://linux-hardware.org/?probe=8c2d8a89d0) | Jul 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [5dc09a66d8](https://linux-hardware.org/?probe=5dc09a66d8) | Jul 08, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b46404cc89](https://linux-hardware.org/?probe=b46404cc89) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [6e17948aa5](https://linux-hardware.org/?probe=6e17948aa5) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [56b772ade4](https://linux-hardware.org/?probe=56b772ade4) | Jul 07, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d9dc513be7](https://linux-hardware.org/?probe=d9dc513be7) | Jul 06, 2022 |
| Fujitsu       | D2981-A1 S26361-D2981-A1    | [5e40d26a2b](https://linux-hardware.org/?probe=5e40d26a2b) | Jul 06, 2022 |
| Inventec      | D CLASS A02                 | [ac1652fd54](https://linux-hardware.org/?probe=ac1652fd54) | Jul 06, 2022 |
| ASUSTek       | PRIME B550M-A               | [a5e8e3a046](https://linux-hardware.org/?probe=a5e8e3a046) | Jul 05, 2022 |
| ASRock        | B550M Pro4                  | [39803eaf94](https://linux-hardware.org/?probe=39803eaf94) | Jul 04, 2022 |
| ASRock        | B550M Pro4                  | [747051c1fc](https://linux-hardware.org/?probe=747051c1fc) | Jul 04, 2022 |
| MSI           | B250M PRO-VDH               | [fb76db49bd](https://linux-hardware.org/?probe=fb76db49bd) | Jul 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| ASRock        | IMB-1213                    | [6e1ba0ba69](https://linux-hardware.org/?probe=6e1ba0ba69) | Jul 04, 2022 |
| HP            | 0A9Ch                       | [3dafdd1a3f](https://linux-hardware.org/?probe=3dafdd1a3f) | Jul 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [a381b573f6](https://linux-hardware.org/?probe=a381b573f6) | Jul 03, 2022 |
| ASUSTek       | PRIME X570-P                | [1a729c627d](https://linux-hardware.org/?probe=1a729c627d) | Jul 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [c633887935](https://linux-hardware.org/?probe=c633887935) | Jul 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [5763cb4576](https://linux-hardware.org/?probe=5763cb4576) | Jul 01, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [21dd020507](https://linux-hardware.org/?probe=21dd020507) | Jul 01, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [7f17faf180](https://linux-hardware.org/?probe=7f17faf180) | Jun 30, 2022 |
| HP            | 0B54h D                     | [bef89f554e](https://linux-hardware.org/?probe=bef89f554e) | Jun 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6a2f1d22f1](https://linux-hardware.org/?probe=6a2f1d22f1) | Jun 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0a976062da](https://linux-hardware.org/?probe=0a976062da) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | [e8d5e4ff14](https://linux-hardware.org/?probe=e8d5e4ff14) | Jun 29, 2022 |
| ASUSTek       | PRIME Z390-P                | [97613877b7](https://linux-hardware.org/?probe=97613877b7) | Jun 29, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [be4dd3360f](https://linux-hardware.org/?probe=be4dd3360f) | Jun 28, 2022 |
| Gigabyte      | A520M DS3H                  | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [0441b2cf28](https://linux-hardware.org/?probe=0441b2cf28) | Jun 27, 2022 |
| HP            | 212B                        | [687ca162d2](https://linux-hardware.org/?probe=687ca162d2) | Jun 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [ca055793c5](https://linux-hardware.org/?probe=ca055793c5) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-K               | [441cba3212](https://linux-hardware.org/?probe=441cba3212) | Jun 27, 2022 |
| Gigabyte      | H370M DS3H-CF               | [862d58f1a4](https://linux-hardware.org/?probe=862d58f1a4) | Jun 27, 2022 |
| MSI           | A320M PRO-M2 V2             | [a801c7c2ba](https://linux-hardware.org/?probe=a801c7c2ba) | Jun 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [da1c9472bd](https://linux-hardware.org/?probe=da1c9472bd) | Jun 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [0e8993f232](https://linux-hardware.org/?probe=0e8993f232) | Jun 27, 2022 |
| ASRock        | B550M Pro4                  | [92d424a6b5](https://linux-hardware.org/?probe=92d424a6b5) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | [4fd5881226](https://linux-hardware.org/?probe=4fd5881226) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | [01e2541b47](https://linux-hardware.org/?probe=01e2541b47) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | [6b2aa6c257](https://linux-hardware.org/?probe=6b2aa6c257) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | [dae78cdc9e](https://linux-hardware.org/?probe=dae78cdc9e) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | [b397f63621](https://linux-hardware.org/?probe=b397f63621) | Jun 26, 2022 |
| ASRock        | H61M-ITX                    | [6c9ee0dadd](https://linux-hardware.org/?probe=6c9ee0dadd) | Jun 26, 2022 |
| ASRock        | B450M Pro4 R2.0             | [f1e0998426](https://linux-hardware.org/?probe=f1e0998426) | Jun 25, 2022 |
| ASRock        | B450M Pro4 R2.0             | [abdb925c2a](https://linux-hardware.org/?probe=abdb925c2a) | Jun 24, 2022 |
| Gigabyte      | MQLP5AP-00                  | [fad6b4b320](https://linux-hardware.org/?probe=fad6b4b320) | Jun 24, 2022 |
| Gigabyte      | B450M S2H V2                | [e0e21604de](https://linux-hardware.org/?probe=e0e21604de) | Jun 24, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [4a8c282d59](https://linux-hardware.org/?probe=4a8c282d59) | Jun 24, 2022 |
| ASRock        | H510M-ITX/ac                | [f1e5f3d686](https://linux-hardware.org/?probe=f1e5f3d686) | Jun 23, 2022 |
| ECS           | H61H2-MV                    | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| Gigabyte      | 970A-DS3P                   | [43c1598008](https://linux-hardware.org/?probe=43c1598008) | Jun 22, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [0e6a585307](https://linux-hardware.org/?probe=0e6a585307) | Jun 21, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7063b6a7ef](https://linux-hardware.org/?probe=7063b6a7ef) | Jun 21, 2022 |
| ASRock        | B550M Pro4                  | [ab46a92e42](https://linux-hardware.org/?probe=ab46a92e42) | Jun 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1bd776020e](https://linux-hardware.org/?probe=1bd776020e) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [75d908e7db](https://linux-hardware.org/?probe=75d908e7db) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [df832fa379](https://linux-hardware.org/?probe=df832fa379) | Jun 18, 2022 |
| Gigabyte      | B450 AORUS M                | [8b1fb7056f](https://linux-hardware.org/?probe=8b1fb7056f) | Jun 17, 2022 |
| Gigabyte      | B450 AORUS M                | [277df992e4](https://linux-hardware.org/?probe=277df992e4) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [530c081484](https://linux-hardware.org/?probe=530c081484) | Jun 17, 2022 |
| ASRock        | AB350M-HDV                  | [65478d1857](https://linux-hardware.org/?probe=65478d1857) | Jun 17, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [b9de371265](https://linux-hardware.org/?probe=b9de371265) | Jun 17, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [d987e4522e](https://linux-hardware.org/?probe=d987e4522e) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4a8163d07f](https://linux-hardware.org/?probe=4a8163d07f) | Jun 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [cee122d15f](https://linux-hardware.org/?probe=cee122d15f) | Jun 16, 2022 |
| AZW           | U59                         | [5a661910dc](https://linux-hardware.org/?probe=5a661910dc) | Jun 16, 2022 |
| Unknown       | Unknown                     | [87eb57392c](https://linux-hardware.org/?probe=87eb57392c) | Jun 16, 2022 |
| MSI           | B360M PRO-VD                | [fa86b2da10](https://linux-hardware.org/?probe=fa86b2da10) | Jun 15, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [a46a8033f8](https://linux-hardware.org/?probe=a46a8033f8) | Jun 15, 2022 |
| ASRock        | B550M Pro4                  | [4dc0746a65](https://linux-hardware.org/?probe=4dc0746a65) | Jun 15, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [7587cca95a](https://linux-hardware.org/?probe=7587cca95a) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [d0050d4fcd](https://linux-hardware.org/?probe=d0050d4fcd) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| Dell          | 0D28YY A00                  | [18487dbcb1](https://linux-hardware.org/?probe=18487dbcb1) | Jun 14, 2022 |
| ASRock        | B550M Pro4                  | [5c9ca9542b](https://linux-hardware.org/?probe=5c9ca9542b) | Jun 13, 2022 |
| HP            | 212B                        | [2680c53ca7](https://linux-hardware.org/?probe=2680c53ca7) | Jun 13, 2022 |
| ASRock        | B550M Pro4                  | [275c522503](https://linux-hardware.org/?probe=275c522503) | Jun 13, 2022 |
| Unknown       | 1.0                         | [8c8f612260](https://linux-hardware.org/?probe=8c8f612260) | Jun 13, 2022 |
| Huanan        | X99-TF V2.0                 | [cf8091c979](https://linux-hardware.org/?probe=cf8091c979) | Jun 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [feca5f6bb5](https://linux-hardware.org/?probe=feca5f6bb5) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| HP            | 0A9Ch                       | [bd8345d324](https://linux-hardware.org/?probe=bd8345d324) | Jun 12, 2022 |
| Gigabyte      | H510M H                     | [7b1a78a681](https://linux-hardware.org/?probe=7b1a78a681) | Jun 11, 2022 |
| Gigabyte      | Z68P-DS3                    | [03554389d5](https://linux-hardware.org/?probe=03554389d5) | Jun 11, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| Gigabyte      | B550M DS3H                  | [32415f8bd1](https://linux-hardware.org/?probe=32415f8bd1) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0dd5653fc1](https://linux-hardware.org/?probe=0dd5653fc1) | Jun 10, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [294890a076](https://linux-hardware.org/?probe=294890a076) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [1b4307a298](https://linux-hardware.org/?probe=1b4307a298) | Jun 09, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [c18fee9219](https://linux-hardware.org/?probe=c18fee9219) | Jun 08, 2022 |
| MSI           | H81M-E33                    | [49191a1c98](https://linux-hardware.org/?probe=49191a1c98) | Jun 08, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [2f1acce421](https://linux-hardware.org/?probe=2f1acce421) | Jun 08, 2022 |
| HP            | 1998                        | [fd5184fe12](https://linux-hardware.org/?probe=fd5184fe12) | Jun 08, 2022 |
| ASRock        | B550M Pro4                  | [10fbde5027](https://linux-hardware.org/?probe=10fbde5027) | Jun 07, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [25213ed098](https://linux-hardware.org/?probe=25213ed098) | Jun 07, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | [1196dd3b41](https://linux-hardware.org/?probe=1196dd3b41) | Jun 06, 2022 |
| MSI           | B350M PRO-VDH               | [ae45bf67a3](https://linux-hardware.org/?probe=ae45bf67a3) | Jun 06, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | [15efe8a0a2](https://linux-hardware.org/?probe=15efe8a0a2) | Jun 06, 2022 |
| MSI           | H81M-E33                    | [6a2d6cbe74](https://linux-hardware.org/?probe=6a2d6cbe74) | Jun 04, 2022 |
| BESSTAR Te... | UM700                       | [ea24f8341e](https://linux-hardware.org/?probe=ea24f8341e) | Jun 02, 2022 |
| BESSTAR Te... | UM700                       | [d3799b37d7](https://linux-hardware.org/?probe=d3799b37d7) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [829ee446bd](https://linux-hardware.org/?probe=829ee446bd) | Jun 02, 2022 |
| MSI           | B350 TOMAHAWK               | [b9cdc775ea](https://linux-hardware.org/?probe=b9cdc775ea) | Jun 02, 2022 |
| ASRock        | B550M Pro4                  | [9ac2f5ba04](https://linux-hardware.org/?probe=9ac2f5ba04) | Jun 01, 2022 |
| MSI           | H81I                        | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| MSI           | B250M PRO-VDH               | [eede963720](https://linux-hardware.org/?probe=eede963720) | May 31, 2022 |
| MSI           | B250M PRO-VDH               | [e2dd690b16](https://linux-hardware.org/?probe=e2dd690b16) | May 31, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [a6506e0582](https://linux-hardware.org/?probe=a6506e0582) | May 30, 2022 |
| ASRock        | B550M Pro4                  | [a5eee874a5](https://linux-hardware.org/?probe=a5eee874a5) | May 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0050247c85](https://linux-hardware.org/?probe=0050247c85) | May 29, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1416d5a87d](https://linux-hardware.org/?probe=1416d5a87d) | May 29, 2022 |
| Google        | Guado                       | [d026c0565d](https://linux-hardware.org/?probe=d026c0565d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | [4e2d37a90d](https://linux-hardware.org/?probe=4e2d37a90d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | [b861a73ade](https://linux-hardware.org/?probe=b861a73ade) | May 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c3d1916e14](https://linux-hardware.org/?probe=c3d1916e14) | May 28, 2022 |
| Gigabyte      | MCMLUCB-00                  | [90c886e471](https://linux-hardware.org/?probe=90c886e471) | May 27, 2022 |
| Dell          | 0KP561                      | [2435960bba](https://linux-hardware.org/?probe=2435960bba) | May 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [63690e08a1](https://linux-hardware.org/?probe=63690e08a1) | May 27, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [d1891c2d3b](https://linux-hardware.org/?probe=d1891c2d3b) | May 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bf3f9d0ed3](https://linux-hardware.org/?probe=bf3f9d0ed3) | May 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c9c34c5c6f](https://linux-hardware.org/?probe=c9c34c5c6f) | May 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [c8f47b62d2](https://linux-hardware.org/?probe=c8f47b62d2) | May 26, 2022 |
| ASRock        | B550M Pro4                  | [d5df82a4ce](https://linux-hardware.org/?probe=d5df82a4ce) | May 25, 2022 |
| ASRock        | H670M-ITX/ax                | [c11c9ac073](https://linux-hardware.org/?probe=c11c9ac073) | May 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [0390e0a7c2](https://linux-hardware.org/?probe=0390e0a7c2) | May 25, 2022 |
| MSI           | X470 GAMING PRO             | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| ASRock        | B550M Pro4                  | [35ba2b5a7a](https://linux-hardware.org/?probe=35ba2b5a7a) | May 24, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [7375e6d7ec](https://linux-hardware.org/?probe=7375e6d7ec) | May 24, 2022 |
| Unknown       | Unknown                     | [62b61f57ef](https://linux-hardware.org/?probe=62b61f57ef) | May 24, 2022 |
| Gigabyte      | Z77M-D3H                    | [b7369242f9](https://linux-hardware.org/?probe=b7369242f9) | May 23, 2022 |
| Google        | Guado                       | [3245615e95](https://linux-hardware.org/?probe=3245615e95) | May 23, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [de3cd5c495](https://linux-hardware.org/?probe=de3cd5c495) | May 23, 2022 |
| ASRock        | Z77 Extreme4                | [198a8b039a](https://linux-hardware.org/?probe=198a8b039a) | May 22, 2022 |
| ASRock        | Z77 Extreme4                | [3c45f702eb](https://linux-hardware.org/?probe=3c45f702eb) | May 22, 2022 |
| MSI           | H97M-G43                    | [3869b1146e](https://linux-hardware.org/?probe=3869b1146e) | May 22, 2022 |
| ASRock        | B550M Pro4                  | [85974104c5](https://linux-hardware.org/?probe=85974104c5) | May 21, 2022 |
| MSI           | Z390-A PRO                  | [8baf319c52](https://linux-hardware.org/?probe=8baf319c52) | May 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [4dce3bdb3a](https://linux-hardware.org/?probe=4dce3bdb3a) | May 21, 2022 |
| Chatreey      | AC1-DP                      | [aefe90ce82](https://linux-hardware.org/?probe=aefe90ce82) | May 20, 2022 |
| HP            | 212B                        | [a52da35d02](https://linux-hardware.org/?probe=a52da35d02) | May 20, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [1efa62dcdb](https://linux-hardware.org/?probe=1efa62dcdb) | May 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [bcb2dd930d](https://linux-hardware.org/?probe=bcb2dd930d) | May 19, 2022 |
| HP            | 8053                        | [67ea3799ad](https://linux-hardware.org/?probe=67ea3799ad) | May 18, 2022 |
| MSI           | X99S GAMING 7               | [ff6fe109c0](https://linux-hardware.org/?probe=ff6fe109c0) | May 17, 2022 |
| ASUSTek       | PRIME X570-P                | [0e0b2d38d8](https://linux-hardware.org/?probe=0e0b2d38d8) | May 17, 2022 |
| ASUSTek       | PRIME X570-P                | [a80d230e6e](https://linux-hardware.org/?probe=a80d230e6e) | May 17, 2022 |
| ASRock        | B550M Pro4                  | [acd5c94fc8](https://linux-hardware.org/?probe=acd5c94fc8) | May 16, 2022 |
| HP            | 3031h                       | [9a6723ea52](https://linux-hardware.org/?probe=9a6723ea52) | May 16, 2022 |
| HP            | 3031h                       | [414614ec5d](https://linux-hardware.org/?probe=414614ec5d) | May 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [798d2cee16](https://linux-hardware.org/?probe=798d2cee16) | May 16, 2022 |
| Gigabyte      | MCMLUCB-00                  | [1ad57be6ad](https://linux-hardware.org/?probe=1ad57be6ad) | May 16, 2022 |
| ASUSTek       | PRIME Z390-P                | [a0c15e2a2f](https://linux-hardware.org/?probe=a0c15e2a2f) | May 16, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [6d1b1bca17](https://linux-hardware.org/?probe=6d1b1bca17) | May 16, 2022 |
| HP            | 8053                        | [35d3caac96](https://linux-hardware.org/?probe=35d3caac96) | May 16, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [178d910ec8](https://linux-hardware.org/?probe=178d910ec8) | May 15, 2022 |
| Gigabyte      | Z97M-DS3H                   | [82b98a2f7e](https://linux-hardware.org/?probe=82b98a2f7e) | May 15, 2022 |
| ASRock        | B550M Pro4                  | [289c04b1dd](https://linux-hardware.org/?probe=289c04b1dd) | May 14, 2022 |
| Dell          | 0C27VV A01                  | [bf0f5c5d07](https://linux-hardware.org/?probe=bf0f5c5d07) | May 14, 2022 |
| ASRock        | X570 Taichi                 | [4d3e26ea12](https://linux-hardware.org/?probe=4d3e26ea12) | May 14, 2022 |
| MSI           | B450M MORTAR MAX            | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| ASUSTek       | Acacia                      | [4b633150fa](https://linux-hardware.org/?probe=4b633150fa) | May 14, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [7a7065c273](https://linux-hardware.org/?probe=7a7065c273) | May 13, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [25654025a8](https://linux-hardware.org/?probe=25654025a8) | May 13, 2022 |
| ASRock        | B550M Pro4                  | [9f9e071e39](https://linux-hardware.org/?probe=9f9e071e39) | May 12, 2022 |
| ASRock        | B550M Pro4                  | [fad48ff5dd](https://linux-hardware.org/?probe=fad48ff5dd) | May 12, 2022 |
| ASUSTek       | P8P67 DELUXE                | [4293bc4b1c](https://linux-hardware.org/?probe=4293bc4b1c) | May 12, 2022 |
| ASUSTek       | P8Z77-V LX                  | [1c124eec80](https://linux-hardware.org/?probe=1c124eec80) | May 12, 2022 |
| Gigabyte      | B550 GAMING X V2            | [326b50009b](https://linux-hardware.org/?probe=326b50009b) | May 12, 2022 |
| ASUSTek       | PRIME X570-PRO              | [23b8b07484](https://linux-hardware.org/?probe=23b8b07484) | May 11, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3fa341f81f](https://linux-hardware.org/?probe=3fa341f81f) | May 11, 2022 |
| Gigabyte      | H97M-HD3                    | [5b0d379b54](https://linux-hardware.org/?probe=5b0d379b54) | May 11, 2022 |
| HP            | 1905                        | [91a5807da1](https://linux-hardware.org/?probe=91a5807da1) | May 10, 2022 |
| HP            | 1905                        | [40dbe34df3](https://linux-hardware.org/?probe=40dbe34df3) | May 10, 2022 |
| MSI           | Z170A GAMING M5             | [766ec913a6](https://linux-hardware.org/?probe=766ec913a6) | May 09, 2022 |
| BESSTAR Te... | UM350                       | [c5234552de](https://linux-hardware.org/?probe=c5234552de) | May 09, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1906da1cb4](https://linux-hardware.org/?probe=1906da1cb4) | May 08, 2022 |
| Intel         | X79M-S                      | [770b00ef16](https://linux-hardware.org/?probe=770b00ef16) | May 08, 2022 |
| ASRock        | B550M Steel Legend          | [a384972a7a](https://linux-hardware.org/?probe=a384972a7a) | May 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [21486c437b](https://linux-hardware.org/?probe=21486c437b) | May 08, 2022 |
| Pegatron      | NARRA5                      | [bfe1e3f80d](https://linux-hardware.org/?probe=bfe1e3f80d) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [027968f6e4](https://linux-hardware.org/?probe=027968f6e4) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [72ae77348e](https://linux-hardware.org/?probe=72ae77348e) | May 07, 2022 |
| ASRock        | X370 Taichi                 | [256b60b267](https://linux-hardware.org/?probe=256b60b267) | May 07, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [093d7ea1c9](https://linux-hardware.org/?probe=093d7ea1c9) | May 06, 2022 |
| ASRock        | H470M-HDV                   | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| MSI           | MEG Z590 GODLIKE            | [0b88e8e449](https://linux-hardware.org/?probe=0b88e8e449) | May 06, 2022 |
| ASRock        | AB350 Pro4                  | [2ce796a070](https://linux-hardware.org/?probe=2ce796a070) | May 05, 2022 |
| MSI           | MEG Z590 GODLIKE            | [ce253bc962](https://linux-hardware.org/?probe=ce253bc962) | May 05, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [3a3a4e634d](https://linux-hardware.org/?probe=3a3a4e634d) | May 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9a2b895663](https://linux-hardware.org/?probe=9a2b895663) | May 04, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [0a2ba1d529](https://linux-hardware.org/?probe=0a2ba1d529) | May 04, 2022 |
| ASUSTek       | P8Z77-V LX                  | [97185f1809](https://linux-hardware.org/?probe=97185f1809) | May 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [473e906b63](https://linux-hardware.org/?probe=473e906b63) | May 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9176b48887](https://linux-hardware.org/?probe=9176b48887) | May 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2089066a7d](https://linux-hardware.org/?probe=2089066a7d) | May 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [edc5f16866](https://linux-hardware.org/?probe=edc5f16866) | May 03, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [26aa108efd](https://linux-hardware.org/?probe=26aa108efd) | May 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | [142c1f1a2f](https://linux-hardware.org/?probe=142c1f1a2f) | May 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [1fea9af929](https://linux-hardware.org/?probe=1fea9af929) | May 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [d49d0283d4](https://linux-hardware.org/?probe=d49d0283d4) | May 03, 2022 |
| Gigabyte      | H81M-S1                     | [8a7d82f85b](https://linux-hardware.org/?probe=8a7d82f85b) | May 03, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [935eb1722b](https://linux-hardware.org/?probe=935eb1722b) | May 02, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [9967806049](https://linux-hardware.org/?probe=9967806049) | May 02, 2022 |
| Gigabyte      | A520M H                     | [80f3ccadb9](https://linux-hardware.org/?probe=80f3ccadb9) | May 02, 2022 |
| MSI           | B450 GAMING PLUS            | [a792e309de](https://linux-hardware.org/?probe=a792e309de) | May 02, 2022 |
| ASRock        | B550AM Gaming               | [e31ad2a03f](https://linux-hardware.org/?probe=e31ad2a03f) | May 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [45a9821bc8](https://linux-hardware.org/?probe=45a9821bc8) | May 02, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a19c88dc27](https://linux-hardware.org/?probe=a19c88dc27) | May 02, 2022 |
| MSI           | Z77A-G43                    | [2c6195f0b8](https://linux-hardware.org/?probe=2c6195f0b8) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | [a913401ce9](https://linux-hardware.org/?probe=a913401ce9) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | [726be8a4f1](https://linux-hardware.org/?probe=726be8a4f1) | May 02, 2022 |
| ASUSTek       | PRIME B350M-A               | [87542ba2c2](https://linux-hardware.org/?probe=87542ba2c2) | Apr 30, 2022 |
| Gigabyte      | H310N x.x                   | [d0daa33c07](https://linux-hardware.org/?probe=d0daa33c07) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [da04f72dfc](https://linux-hardware.org/?probe=da04f72dfc) | Apr 30, 2022 |
| ASRock        | Z370 Gaming K6              | [63d2d272b6](https://linux-hardware.org/?probe=63d2d272b6) | Apr 30, 2022 |
| MSI           | MEG Z590 GODLIKE            | [d0ca0e52ad](https://linux-hardware.org/?probe=d0ca0e52ad) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [29e1e28903](https://linux-hardware.org/?probe=29e1e28903) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [a2f86e2fea](https://linux-hardware.org/?probe=a2f86e2fea) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6f7b2f6a78](https://linux-hardware.org/?probe=6f7b2f6a78) | Apr 28, 2022 |
| ASRock        | B550M Pro4                  | [31f358fdd0](https://linux-hardware.org/?probe=31f358fdd0) | Apr 28, 2022 |
| Gigabyte      | X570 UD                     | [67f24b974b](https://linux-hardware.org/?probe=67f24b974b) | Apr 27, 2022 |
| ASRock        | AB350M-HDV                  | [6ee4ea44a8](https://linux-hardware.org/?probe=6ee4ea44a8) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | [7c7b023841](https://linux-hardware.org/?probe=7c7b023841) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | [eddac3b03f](https://linux-hardware.org/?probe=eddac3b03f) | Apr 27, 2022 |
| ASRock        | B550M Pro4                  | [003eab04ae](https://linux-hardware.org/?probe=003eab04ae) | Apr 26, 2022 |
| MSI           | MEG X570 UNIFY              | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| AZW           | U59                         | [ecee060925](https://linux-hardware.org/?probe=ecee060925) | Apr 26, 2022 |
| Gigabyte      | Z590 D                      | [afad17a56d](https://linux-hardware.org/?probe=afad17a56d) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | [6bee5ac8c6](https://linux-hardware.org/?probe=6bee5ac8c6) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | [a304ccdfb1](https://linux-hardware.org/?probe=a304ccdfb1) | Apr 26, 2022 |
| Alienware     | 02XRCM A01                  | [90cc83b1aa](https://linux-hardware.org/?probe=90cc83b1aa) | Apr 26, 2022 |
| ASRock        | H97 Pro4                    | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Dell          | 042P49 A02                  | [cc2266d5aa](https://linux-hardware.org/?probe=cc2266d5aa) | Apr 25, 2022 |
| MSI           | MEG B550 UNIFY              | [3cf3319591](https://linux-hardware.org/?probe=3cf3319591) | Apr 25, 2022 |
| Dell          | 0KP561                      | [0467bf679e](https://linux-hardware.org/?probe=0467bf679e) | Apr 25, 2022 |
| ASRock        | H110 Pro BTC+               | [1251ef669d](https://linux-hardware.org/?probe=1251ef669d) | Apr 24, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [81f1c06851](https://linux-hardware.org/?probe=81f1c06851) | Apr 23, 2022 |
| Alienware     | 07HV66 A00                  | [7b889c5010](https://linux-hardware.org/?probe=7b889c5010) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6af9cfacd0](https://linux-hardware.org/?probe=6af9cfacd0) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [afcef911ce](https://linux-hardware.org/?probe=afcef911ce) | Apr 23, 2022 |
| ASRock        | AB350M Pro4                 | [544c5dbbf7](https://linux-hardware.org/?probe=544c5dbbf7) | Apr 22, 2022 |
| ASUSTek       | H81M-K                      | [95a2757020](https://linux-hardware.org/?probe=95a2757020) | Apr 22, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [6c6203c7ff](https://linux-hardware.org/?probe=6c6203c7ff) | Apr 22, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [acc082b594](https://linux-hardware.org/?probe=acc082b594) | Apr 22, 2022 |
| Acer          | Predator G3610              | [a53edf84d4](https://linux-hardware.org/?probe=a53edf84d4) | Apr 22, 2022 |
| ASUSTek       | PRIME A320M-K               | [822db71f7a](https://linux-hardware.org/?probe=822db71f7a) | Apr 21, 2022 |
| Gigabyte      | B450 AORUS M                | [ff11434d18](https://linux-hardware.org/?probe=ff11434d18) | Apr 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [34c876e7e6](https://linux-hardware.org/?probe=34c876e7e6) | Apr 19, 2022 |
| Dell          | 0C522T A00                  | [8684c390a7](https://linux-hardware.org/?probe=8684c390a7) | Apr 19, 2022 |
| Dell          | 09M8Y8 A01                  | [8b989c82a2](https://linux-hardware.org/?probe=8b989c82a2) | Apr 18, 2022 |
| Dell          | 09M8Y8 A01                  | [fff624b795](https://linux-hardware.org/?probe=fff624b795) | Apr 18, 2022 |
| ECS           | H61H2-M13                   | [f3d574e81e](https://linux-hardware.org/?probe=f3d574e81e) | Apr 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ff70aec1ae](https://linux-hardware.org/?probe=ff70aec1ae) | Apr 18, 2022 |
| Foxconn       | 2ABF                        | [ce158f41e2](https://linux-hardware.org/?probe=ce158f41e2) | Apr 17, 2022 |
| MSI           | B350M PRO-VDH               | [884f15c1df](https://linux-hardware.org/?probe=884f15c1df) | Apr 17, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [271eb8380b](https://linux-hardware.org/?probe=271eb8380b) | Apr 17, 2022 |
| Lenovo        | 3714 NOK                    | [80ed454cc3](https://linux-hardware.org/?probe=80ed454cc3) | Apr 17, 2022 |
| ASUSTek       | P5K Deluxe                  | [e7b66178ce](https://linux-hardware.org/?probe=e7b66178ce) | Apr 17, 2022 |
| MSI           | MAG B460M MORTAR            | [278ccbaf44](https://linux-hardware.org/?probe=278ccbaf44) | Apr 17, 2022 |
| MSI           | MS-7438 100                 | [bac261ba9a](https://linux-hardware.org/?probe=bac261ba9a) | Apr 16, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [3e3e2fd22f](https://linux-hardware.org/?probe=3e3e2fd22f) | Apr 16, 2022 |
| MSI           | B450M PRO-M2 MAX            | [4702e93a67](https://linux-hardware.org/?probe=4702e93a67) | Apr 16, 2022 |
| ASUSTek       | GRYPHON Z87                 | [557390f9cf](https://linux-hardware.org/?probe=557390f9cf) | Apr 15, 2022 |
| Dell          | 0C522T A00                  | [593941cc0a](https://linux-hardware.org/?probe=593941cc0a) | Apr 15, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [bd378877e0](https://linux-hardware.org/?probe=bd378877e0) | Apr 14, 2022 |
| ASRock        | B550M Pro4                  | [e1b00199f8](https://linux-hardware.org/?probe=e1b00199f8) | Apr 14, 2022 |
| ASRock        | AB350 Pro4                  | [137e25f240](https://linux-hardware.org/?probe=137e25f240) | Apr 14, 2022 |
| ASUSTek       | PRIME B360M-C               | [417d3ab696](https://linux-hardware.org/?probe=417d3ab696) | Apr 14, 2022 |
| ASUSTek       | Maximus IX HERO             | [624c5a033e](https://linux-hardware.org/?probe=624c5a033e) | Apr 14, 2022 |
| ASRock        | AB350M                      | [f79bfabcf5](https://linux-hardware.org/?probe=f79bfabcf5) | Apr 14, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [5d45d7b3f7](https://linux-hardware.org/?probe=5d45d7b3f7) | Apr 13, 2022 |
| ASRock        | X570M Pro4                  | [b7373e1f8f](https://linux-hardware.org/?probe=b7373e1f8f) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [0056c8d32e](https://linux-hardware.org/?probe=0056c8d32e) | Apr 13, 2022 |
| Dell          | 03V3TG A00                  | [a91e96515c](https://linux-hardware.org/?probe=a91e96515c) | Apr 13, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| HP            | 18E4                        | [83cf0afd92](https://linux-hardware.org/?probe=83cf0afd92) | Apr 13, 2022 |
| HP            | 18E4                        | [61a163f744](https://linux-hardware.org/?probe=61a163f744) | Apr 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [81ef10ca5d](https://linux-hardware.org/?probe=81ef10ca5d) | Apr 13, 2022 |
| Gigabyte      | 970A-DS3P                   | [8101ed4e60](https://linux-hardware.org/?probe=8101ed4e60) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [bf61a75cfd](https://linux-hardware.org/?probe=bf61a75cfd) | Apr 12, 2022 |
| Intel         | SHARKBAY                    | [f676b9a255](https://linux-hardware.org/?probe=f676b9a255) | Apr 11, 2022 |
| ASRock        | B250M Performance           | [3d9af3df5a](https://linux-hardware.org/?probe=3d9af3df5a) | Apr 11, 2022 |
| MSI           | 760GM-P34                   | [c346a58754](https://linux-hardware.org/?probe=c346a58754) | Apr 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [1a475ba1e6](https://linux-hardware.org/?probe=1a475ba1e6) | Apr 11, 2022 |
| HP            | 1998                        | [28dcd611cc](https://linux-hardware.org/?probe=28dcd611cc) | Apr 10, 2022 |
| MSI           | Z370 PC PRO                 | [2d4574e9fe](https://linux-hardware.org/?probe=2d4574e9fe) | Apr 10, 2022 |
| Gigabyte      | H61M-S2PV                   | [8760e3254a](https://linux-hardware.org/?probe=8760e3254a) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | [b0ffa911b5](https://linux-hardware.org/?probe=b0ffa911b5) | Apr 10, 2022 |
| ASUSTek       | PRIME H410M-E               | [885cbd9d0c](https://linux-hardware.org/?probe=885cbd9d0c) | Apr 10, 2022 |
| ASUSTek       | P8Z77-V DELUXE              | [e890c4c2f7](https://linux-hardware.org/?probe=e890c4c2f7) | Apr 10, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [645fb7bb30](https://linux-hardware.org/?probe=645fb7bb30) | Apr 09, 2022 |
| ASUSTek       | Z87-K                       | [5264d55ce2](https://linux-hardware.org/?probe=5264d55ce2) | Apr 09, 2022 |
| ASRock        | Z77 Pro4                    | [38eeb648af](https://linux-hardware.org/?probe=38eeb648af) | Apr 09, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [a618981311](https://linux-hardware.org/?probe=a618981311) | Apr 09, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [2db23c062e](https://linux-hardware.org/?probe=2db23c062e) | Apr 08, 2022 |
| ASUSTek       | P8Z77-V LX                  | [94f4873110](https://linux-hardware.org/?probe=94f4873110) | Apr 06, 2022 |
| MSI           | Z370-A PRO                  | [c4f0f0573c](https://linux-hardware.org/?probe=c4f0f0573c) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [091190515b](https://linux-hardware.org/?probe=091190515b) | Apr 06, 2022 |
| Dell          | 0D24M8 A00                  | [4f81a4a54a](https://linux-hardware.org/?probe=4f81a4a54a) | Apr 06, 2022 |
| ASUSTek       | A8N-VM CSM                  | [eac824e348](https://linux-hardware.org/?probe=eac824e348) | Apr 06, 2022 |
| Biostar       | TB250-BTC                   | [d6ef15453d](https://linux-hardware.org/?probe=d6ef15453d) | Apr 05, 2022 |
| ASUSTek       | Z97-A-USB31                 | [cd6f73403e](https://linux-hardware.org/?probe=cd6f73403e) | Apr 05, 2022 |
| ASRock        | B450 Pro4                   | [47ff657a18](https://linux-hardware.org/?probe=47ff657a18) | Apr 04, 2022 |
| Dell          | 0C522T A00                  | [4a42777634](https://linux-hardware.org/?probe=4a42777634) | Apr 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5348103896](https://linux-hardware.org/?probe=5348103896) | Apr 03, 2022 |
| Intel         | DH67BL AAG10189-207         | [2daa6a85f4](https://linux-hardware.org/?probe=2daa6a85f4) | Apr 03, 2022 |
| MSI           | X470 GAMING PLUS            | [b7cf273d03](https://linux-hardware.org/?probe=b7cf273d03) | Apr 03, 2022 |
| ASRock        | 960GM-GS3 FX                | [cf80b64dad](https://linux-hardware.org/?probe=cf80b64dad) | Apr 02, 2022 |
| ASRock        | 960GM-GS3 FX                | [50c200ee58](https://linux-hardware.org/?probe=50c200ee58) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [a11d93b9d5](https://linux-hardware.org/?probe=a11d93b9d5) | Apr 02, 2022 |
| Acer          | Aspire TC-120               | [a92d7ab62a](https://linux-hardware.org/?probe=a92d7ab62a) | Apr 02, 2022 |
| ASUSTek       | Z97-A-USB31                 | [6f40a4ebce](https://linux-hardware.org/?probe=6f40a4ebce) | Apr 02, 2022 |
| Dell          | 0N867P A02                  | [aaf4c4cf2b](https://linux-hardware.org/?probe=aaf4c4cf2b) | Apr 01, 2022 |
| ASRock        | Z390 Taichi                 | [b5995c13e5](https://linux-hardware.org/?probe=b5995c13e5) | Mar 31, 2022 |
| ASRock        | Z390 Taichi                 | [308ec93236](https://linux-hardware.org/?probe=308ec93236) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [101c38851b](https://linux-hardware.org/?probe=101c38851b) | Mar 31, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [5f25594023](https://linux-hardware.org/?probe=5f25594023) | Mar 31, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [42e098223b](https://linux-hardware.org/?probe=42e098223b) | Mar 30, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0deba367b9](https://linux-hardware.org/?probe=0deba367b9) | Mar 30, 2022 |
| ASRock        | Z77 Extreme4                | [4ab227f4be](https://linux-hardware.org/?probe=4ab227f4be) | Mar 29, 2022 |
| Gigabyte      | Z87MX-D3H-CF                | [0401591ebc](https://linux-hardware.org/?probe=0401591ebc) | Mar 29, 2022 |
| HP            | 1998                        | [13b901f36a](https://linux-hardware.org/?probe=13b901f36a) | Mar 29, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [a10bdc00e2](https://linux-hardware.org/?probe=a10bdc00e2) | Mar 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0bcee9c78e](https://linux-hardware.org/?probe=0bcee9c78e) | Mar 28, 2022 |
| MSI           | H81M-E34                    | [42ff46ca6c](https://linux-hardware.org/?probe=42ff46ca6c) | Mar 28, 2022 |
| Gigabyte      | M68MT-D3P                   | [8d596570ed](https://linux-hardware.org/?probe=8d596570ed) | Mar 28, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3ed10cce06](https://linux-hardware.org/?probe=3ed10cce06) | Mar 27, 2022 |
| ASRock        | B550M Pro4                  | [4c69702c19](https://linux-hardware.org/?probe=4c69702c19) | Mar 27, 2022 |
| AMD           | 970A-D3                     | [010b978f01](https://linux-hardware.org/?probe=010b978f01) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| ASUSTek       | P8H61-M LE/BR               | [732876bdd8](https://linux-hardware.org/?probe=732876bdd8) | Mar 26, 2022 |
| Alienware     | 0R3FWM A00                  | [46a5c111c3](https://linux-hardware.org/?probe=46a5c111c3) | Mar 25, 2022 |
| Gigabyte      | 990XA-UD3                   | [913cf55cc3](https://linux-hardware.org/?probe=913cf55cc3) | Mar 25, 2022 |
| ASUSTek       | PRIME Z370-P                | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | [40ec2200ee](https://linux-hardware.org/?probe=40ec2200ee) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | [cb639d5f0a](https://linux-hardware.org/?probe=cb639d5f0a) | Mar 25, 2022 |
| Acer          | Veriton M6660G V:1.0        | [ee5d755daf](https://linux-hardware.org/?probe=ee5d755daf) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [994cca77b2](https://linux-hardware.org/?probe=994cca77b2) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [fe7be471b2](https://linux-hardware.org/?probe=fe7be471b2) | Mar 24, 2022 |
| ASRock        | B550 Taichi                 | [2c71d397fd](https://linux-hardware.org/?probe=2c71d397fd) | Mar 24, 2022 |
| Unknown       | Unknown                     | [52ce856be5](https://linux-hardware.org/?probe=52ce856be5) | Mar 24, 2022 |
| Unknown       | Unknown                     | [1dd07eeee0](https://linux-hardware.org/?probe=1dd07eeee0) | Mar 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [bb1d6b4aae](https://linux-hardware.org/?probe=bb1d6b4aae) | Mar 24, 2022 |
| Intel         | Unknown                     | [169b017d29](https://linux-hardware.org/?probe=169b017d29) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c5a0300da9](https://linux-hardware.org/?probe=c5a0300da9) | Mar 23, 2022 |
| ASUSTek       | B150I PRO GAMING/AURA       | [0839d5feb0](https://linux-hardware.org/?probe=0839d5feb0) | Mar 22, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [d24fcefe24](https://linux-hardware.org/?probe=d24fcefe24) | Mar 22, 2022 |
| Acer          | Veriton M6660G V:1.0        | [228974c486](https://linux-hardware.org/?probe=228974c486) | Mar 22, 2022 |
| Dell          | 0K3CM7 A00                  | [8f5ec6c004](https://linux-hardware.org/?probe=8f5ec6c004) | Mar 22, 2022 |
| Apple         | Mac-27AD2F918AE68F61        | [03e06a3a70](https://linux-hardware.org/?probe=03e06a3a70) | Mar 22, 2022 |
| Gigabyte      | G31M-ES2L                   | [90a8431fc2](https://linux-hardware.org/?probe=90a8431fc2) | Mar 22, 2022 |
| Gigabyte      | A320M-H-CF                  | [1462cd20b7](https://linux-hardware.org/?probe=1462cd20b7) | Mar 22, 2022 |
| MSI           | B450M PRO-VDH MAX           | [a6718f483b](https://linux-hardware.org/?probe=a6718f483b) | Mar 22, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [b7f10d6ec0](https://linux-hardware.org/?probe=b7f10d6ec0) | Mar 21, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | [747e4d92cf](https://linux-hardware.org/?probe=747e4d92cf) | Mar 21, 2022 |
| ASRock        | B550 Extreme4               | [9c194b83e5](https://linux-hardware.org/?probe=9c194b83e5) | Mar 21, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [daa5dd8024](https://linux-hardware.org/?probe=daa5dd8024) | Mar 20, 2022 |
| ASUSTek       | H170 PRO GAMING             | [8ce1eed900](https://linux-hardware.org/?probe=8ce1eed900) | Mar 20, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | [1897912bfc](https://linux-hardware.org/?probe=1897912bfc) | Mar 19, 2022 |
| TPV-INVENT... | 2AF2 A01                    | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| Dell          | 040DDP A01                  | [4cf633a014](https://linux-hardware.org/?probe=4cf633a014) | Mar 18, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [d2378fc2ac](https://linux-hardware.org/?probe=d2378fc2ac) | Mar 18, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [af8d9c8c06](https://linux-hardware.org/?probe=af8d9c8c06) | Mar 18, 2022 |
| ASUSTek       | PRIME B460M-A               | [bb8e459621](https://linux-hardware.org/?probe=bb8e459621) | Mar 17, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [9ebb2a429f](https://linux-hardware.org/?probe=9ebb2a429f) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b844e23ce9](https://linux-hardware.org/?probe=b844e23ce9) | Mar 17, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [04e11e3668](https://linux-hardware.org/?probe=04e11e3668) | Mar 16, 2022 |
| MSI           | B75MA-P45                   | [f617b8e30b](https://linux-hardware.org/?probe=f617b8e30b) | Mar 16, 2022 |
| System76      | Thelio thelio-r2            | [ac96c74ffa](https://linux-hardware.org/?probe=ac96c74ffa) | Mar 16, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ca405b99d5](https://linux-hardware.org/?probe=ca405b99d5) | Mar 16, 2022 |
| MSI           | MEG X570 UNIFY              | [0927f69114](https://linux-hardware.org/?probe=0927f69114) | Mar 15, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [1b6764fd97](https://linux-hardware.org/?probe=1b6764fd97) | Mar 15, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [a4cc8c4dda](https://linux-hardware.org/?probe=a4cc8c4dda) | Mar 15, 2022 |
| MSI           | MEG X570 UNIFY              | [a4dd59149a](https://linux-hardware.org/?probe=a4dd59149a) | Mar 15, 2022 |
| ASUSTek       | PRIME H410M-R               | [4bc060dc9d](https://linux-hardware.org/?probe=4bc060dc9d) | Mar 14, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [e0efdaa76a](https://linux-hardware.org/?probe=e0efdaa76a) | Mar 13, 2022 |
| Gigabyte      | H310M H x.x                 | [0a16c273a4](https://linux-hardware.org/?probe=0a16c273a4) | Mar 13, 2022 |
| ASRock        | H61 Pro BTC                 | [43528c8a20](https://linux-hardware.org/?probe=43528c8a20) | Mar 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [75561646a7](https://linux-hardware.org/?probe=75561646a7) | Mar 13, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [693ec12319](https://linux-hardware.org/?probe=693ec12319) | Mar 12, 2022 |
| MSI           | H81M-P33                    | [138594b67f](https://linux-hardware.org/?probe=138594b67f) | Mar 12, 2022 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | [e6c507dff4](https://linux-hardware.org/?probe=e6c507dff4) | Mar 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [e8c3922bb3](https://linux-hardware.org/?probe=e8c3922bb3) | Mar 12, 2022 |
| MSI           | H81M-E34                    | [8d5b326668](https://linux-hardware.org/?probe=8d5b326668) | Mar 12, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [bd9b6ec157](https://linux-hardware.org/?probe=bd9b6ec157) | Mar 11, 2022 |
| HP            | 1850                        | [7e0b4230d4](https://linux-hardware.org/?probe=7e0b4230d4) | Mar 11, 2022 |
| Gigabyte      | B75M-D3H                    | [30df05cc2f](https://linux-hardware.org/?probe=30df05cc2f) | Mar 11, 2022 |
| HP            | 3396                        | [7bd27c71ed](https://linux-hardware.org/?probe=7bd27c71ed) | Mar 11, 2022 |
| HP            | 3396                        | [adeef3162a](https://linux-hardware.org/?probe=adeef3162a) | Mar 11, 2022 |
| Gigabyte      | H61M-S2PV                   | [6b32e0c788](https://linux-hardware.org/?probe=6b32e0c788) | Mar 10, 2022 |
| ASRock        | H81M-VG4 R2.0               | [2d72940994](https://linux-hardware.org/?probe=2d72940994) | Mar 10, 2022 |
| Gigabyte      | X570 GAMING X               | [4f7aa0f57c](https://linux-hardware.org/?probe=4f7aa0f57c) | Mar 10, 2022 |
| HP            | 1497                        | [f67b96c14e](https://linux-hardware.org/?probe=f67b96c14e) | Mar 07, 2022 |
| ASRock        | H97 Pro4                    | [83df7fb05a](https://linux-hardware.org/?probe=83df7fb05a) | Mar 07, 2022 |
| Gigabyte      | Z68P-DS3                    | [0bb1088899](https://linux-hardware.org/?probe=0bb1088899) | Mar 06, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [783c8d9097](https://linux-hardware.org/?probe=783c8d9097) | Mar 06, 2022 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [68250a6d74](https://linux-hardware.org/?probe=68250a6d74) | Mar 06, 2022 |
| Dell          | 0YXT71 A03                  | [b1ac4ae8e7](https://linux-hardware.org/?probe=b1ac4ae8e7) | Mar 05, 2022 |
| MSI           | X99A SLI PLUS               | [b56033aa1d](https://linux-hardware.org/?probe=b56033aa1d) | Mar 05, 2022 |
| Gigabyte      | 2AC8                        | [af655fd169](https://linux-hardware.org/?probe=af655fd169) | Mar 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8e27cc62b4](https://linux-hardware.org/?probe=8e27cc62b4) | Mar 04, 2022 |
| ASRock        | AB350M Pro4                 | [6ea2fbdb95](https://linux-hardware.org/?probe=6ea2fbdb95) | Mar 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ee8029d2c8](https://linux-hardware.org/?probe=ee8029d2c8) | Mar 03, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [cff135fa1e](https://linux-hardware.org/?probe=cff135fa1e) | Mar 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [eb3d721453](https://linux-hardware.org/?probe=eb3d721453) | Mar 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5f0757c539](https://linux-hardware.org/?probe=5f0757c539) | Mar 02, 2022 |
| ASRock        | Z77 Pro4                    | [ae5611419f](https://linux-hardware.org/?probe=ae5611419f) | Mar 02, 2022 |
| ASRock        | X370 Killer SLI/ac          | [07f8fcde55](https://linux-hardware.org/?probe=07f8fcde55) | Mar 02, 2022 |
| HP            | 18E4                        | [192b302f41](https://linux-hardware.org/?probe=192b302f41) | Feb 27, 2022 |
| ASRock        | H61M-ITX                    | [081ea4e585](https://linux-hardware.org/?probe=081ea4e585) | Feb 26, 2022 |
| AIO           | H61H-G11                    | [137ec871e7](https://linux-hardware.org/?probe=137ec871e7) | Feb 25, 2022 |
| ASUSTek       | PRIME B450M-K               | [6f1958559b](https://linux-hardware.org/?probe=6f1958559b) | Feb 24, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [b6891f77df](https://linux-hardware.org/?probe=b6891f77df) | Feb 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [f2a6491fc3](https://linux-hardware.org/?probe=f2a6491fc3) | Feb 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [1c8a37fb2f](https://linux-hardware.org/?probe=1c8a37fb2f) | Feb 24, 2022 |
| HP            | 21D0                        | [448912eeb9](https://linux-hardware.org/?probe=448912eeb9) | Feb 24, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1c6d204561](https://linux-hardware.org/?probe=1c6d204561) | Feb 24, 2022 |
| Dell          | 00V62H A01                  | [e6564282e5](https://linux-hardware.org/?probe=e6564282e5) | Feb 23, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [2f53cef399](https://linux-hardware.org/?probe=2f53cef399) | Feb 23, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [6d2bec51f3](https://linux-hardware.org/?probe=6d2bec51f3) | Feb 23, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE Ser... | [17aa7b3d5b](https://linux-hardware.org/?probe=17aa7b3d5b) | Feb 23, 2022 |
| Gigabyte      | B460M DS3H                  | [c2ed3df75c](https://linux-hardware.org/?probe=c2ed3df75c) | Feb 23, 2022 |
| MSI           | 880G-E45                    | [e6f9c8c9f6](https://linux-hardware.org/?probe=e6f9c8c9f6) | Feb 23, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [db907dad62](https://linux-hardware.org/?probe=db907dad62) | Feb 21, 2022 |
| Gigabyte      | 2AC8                        | [90d30ccc29](https://linux-hardware.org/?probe=90d30ccc29) | Feb 21, 2022 |
| Gigabyte      | H61M-DS2 DVI                | [03491eae09](https://linux-hardware.org/?probe=03491eae09) | Feb 21, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [e1943c32e9](https://linux-hardware.org/?probe=e1943c32e9) | Feb 20, 2022 |
| HP            | 1998                        | [1cd99a92d0](https://linux-hardware.org/?probe=1cd99a92d0) | Feb 20, 2022 |
| Biostar       | TB250-BTC                   | [90154b9001](https://linux-hardware.org/?probe=90154b9001) | Feb 20, 2022 |
| Biostar       | TB250-BTC                   | [b42d2ce48e](https://linux-hardware.org/?probe=b42d2ce48e) | Feb 20, 2022 |
| ASRock        | H370M-ITX/ac                | [95b177e121](https://linux-hardware.org/?probe=95b177e121) | Feb 19, 2022 |
| Gigabyte      | C246-WU4-CF                 | [e849c7b27b](https://linux-hardware.org/?probe=e849c7b27b) | Feb 19, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [7ecf132718](https://linux-hardware.org/?probe=7ecf132718) | Feb 19, 2022 |
| Dell          | 0CRH6C A02                  | [726633bbcc](https://linux-hardware.org/?probe=726633bbcc) | Feb 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d08ed1959b](https://linux-hardware.org/?probe=d08ed1959b) | Feb 18, 2022 |
| HP            | 1497                        | [8693cfc8c8](https://linux-hardware.org/?probe=8693cfc8c8) | Feb 17, 2022 |
| ASRock        | Z370 Extreme4               | [304e498f77](https://linux-hardware.org/?probe=304e498f77) | Feb 17, 2022 |
| HP            | 2820h                       | [f45476e17a](https://linux-hardware.org/?probe=f45476e17a) | Feb 17, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [3dc3e4c8c8](https://linux-hardware.org/?probe=3dc3e4c8c8) | Feb 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [2dece71caa](https://linux-hardware.org/?probe=2dece71caa) | Feb 17, 2022 |
| HP            | 0AA8h                       | [cb11b8e6fb](https://linux-hardware.org/?probe=cb11b8e6fb) | Feb 16, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE Ser... | [922f3559c8](https://linux-hardware.org/?probe=922f3559c8) | Feb 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [913928e6e9](https://linux-hardware.org/?probe=913928e6e9) | Feb 16, 2022 |
| ASUSTek       | M5A97 EVO                   | [c80545d294](https://linux-hardware.org/?probe=c80545d294) | Feb 16, 2022 |
| ASUSTek       | M5A97 EVO                   | [98e8879090](https://linux-hardware.org/?probe=98e8879090) | Feb 16, 2022 |
| MSI           | B150M PRO-VD                | [b46943492e](https://linux-hardware.org/?probe=b46943492e) | Feb 15, 2022 |
| Gigabyte      | A520M H                     | [6f8f7c786e](https://linux-hardware.org/?probe=6f8f7c786e) | Feb 14, 2022 |
| Gigabyte      | A520M H                     | [b4c976a541](https://linux-hardware.org/?probe=b4c976a541) | Feb 14, 2022 |
| ASUSTek       | P5QL/EPU                    | [2a5bcaeec9](https://linux-hardware.org/?probe=2a5bcaeec9) | Feb 14, 2022 |
| ASRock        | B450M Pro4                  | [3bbcbc62f5](https://linux-hardware.org/?probe=3bbcbc62f5) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [cc35d4696d](https://linux-hardware.org/?probe=cc35d4696d) | Feb 13, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a25fea3795](https://linux-hardware.org/?probe=a25fea3795) | Feb 12, 2022 |
| HP            | 8618                        | [6976caf9ed](https://linux-hardware.org/?probe=6976caf9ed) | Feb 12, 2022 |
| HP            | 8618                        | [1038885608](https://linux-hardware.org/?probe=1038885608) | Feb 12, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | [73767731d9](https://linux-hardware.org/?probe=73767731d9) | Feb 11, 2022 |
| Intel         | DH67GD AAG10206-202         | [56c802164a](https://linux-hardware.org/?probe=56c802164a) | Feb 11, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [040550cdaa](https://linux-hardware.org/?probe=040550cdaa) | Feb 11, 2022 |
| ASUSTek       | Maximus Formula             | [130c778a64](https://linux-hardware.org/?probe=130c778a64) | Feb 11, 2022 |
| Acer          | Predator PO3-630            | [96dccc1214](https://linux-hardware.org/?probe=96dccc1214) | Feb 11, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [afc31097cd](https://linux-hardware.org/?probe=afc31097cd) | Feb 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a752207fe2](https://linux-hardware.org/?probe=a752207fe2) | Feb 09, 2022 |
| ASRock        | FM2A68M-HD+                 | [8545c3246e](https://linux-hardware.org/?probe=8545c3246e) | Feb 08, 2022 |
| Dell          | 00V62H A00                  | [7135f3c638](https://linux-hardware.org/?probe=7135f3c638) | Feb 07, 2022 |
| Dell          | 00V62H A00                  | [d6aefe2df6](https://linux-hardware.org/?probe=d6aefe2df6) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [9dd525ae45](https://linux-hardware.org/?probe=9dd525ae45) | Feb 07, 2022 |
| ASUSTek       | PRIME H510M-A               | [b2bc043c0b](https://linux-hardware.org/?probe=b2bc043c0b) | Feb 07, 2022 |
| HP            | 2820h                       | [347b6a83de](https://linux-hardware.org/?probe=347b6a83de) | Feb 07, 2022 |
| HP            | 2820h                       | [7c5fb9c18f](https://linux-hardware.org/?probe=7c5fb9c18f) | Feb 07, 2022 |
| ASRock        | B450M Pro4                  | [9efa6de9c0](https://linux-hardware.org/?probe=9efa6de9c0) | Feb 07, 2022 |
| ASRock        | H510M-HDV/M.2               | [11b7d331bc](https://linux-hardware.org/?probe=11b7d331bc) | Feb 06, 2022 |
| Intel         | H61 V124                    | [258b472104](https://linux-hardware.org/?probe=258b472104) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [497f20602c](https://linux-hardware.org/?probe=497f20602c) | Feb 05, 2022 |
| Acer          | Predator PO3-630            | [7d12bf5399](https://linux-hardware.org/?probe=7d12bf5399) | Feb 05, 2022 |
| MSI           | Z270I GAMING PRO CARBON ... | [424f798e37](https://linux-hardware.org/?probe=424f798e37) | Feb 05, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [4c27e1f600](https://linux-hardware.org/?probe=4c27e1f600) | Feb 05, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [055aea6734](https://linux-hardware.org/?probe=055aea6734) | Feb 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [035ccaeec8](https://linux-hardware.org/?probe=035ccaeec8) | Feb 04, 2022 |
| MSI           | MEG X570 UNIFY              | [5e8f4aba70](https://linux-hardware.org/?probe=5e8f4aba70) | Feb 03, 2022 |
| Dell          | 0XR1GT A00                  | [436259c69f](https://linux-hardware.org/?probe=436259c69f) | Feb 03, 2022 |
| Gigabyte      | F2A55M-DS2                  | [05d8bff376](https://linux-hardware.org/?probe=05d8bff376) | Feb 02, 2022 |
| ASUSTek       | PRIME Z390-A                | [8086fa496d](https://linux-hardware.org/?probe=8086fa496d) | Feb 02, 2022 |
| ASRock        | B450 Pro4                   | [01eb76fa65](https://linux-hardware.org/?probe=01eb76fa65) | Feb 01, 2022 |
| Dell          | 0HD5W2 A01                  | [9d172808c8](https://linux-hardware.org/?probe=9d172808c8) | Feb 01, 2022 |
| Intel         | X99 V1.0                    | [c342bd0bba](https://linux-hardware.org/?probe=c342bd0bba) | Jan 30, 2022 |
| Huanan        | X99-TF GAMING V2.0          | [aa1fb1fa56](https://linux-hardware.org/?probe=aa1fb1fa56) | Jan 29, 2022 |
| ASUSTek       | PRIME B450M-A               | [1ce7d1b347](https://linux-hardware.org/?probe=1ce7d1b347) | Jan 29, 2022 |
| ASUSTek       | P5QL/EPU                    | [c1e858090a](https://linux-hardware.org/?probe=c1e858090a) | Jan 28, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [bfc2cf603f](https://linux-hardware.org/?probe=bfc2cf603f) | Jan 27, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [ad887e6da9](https://linux-hardware.org/?probe=ad887e6da9) | Jan 27, 2022 |
| Dell          | 06D7TR A00                  | [1fdcf46e3b](https://linux-hardware.org/?probe=1fdcf46e3b) | Jan 26, 2022 |
| GALAX         | B365M G10b                  | [bd83b31919](https://linux-hardware.org/?probe=bd83b31919) | Jan 26, 2022 |
| Gigabyte      | 2AC8                        | [1480b4a02f](https://linux-hardware.org/?probe=1480b4a02f) | Jan 25, 2022 |
| Gigabyte      | 970A-DS3P                   | [d0dde4a553](https://linux-hardware.org/?probe=d0dde4a553) | Jan 24, 2022 |
| Gigabyte      | 965P-S3                     | [9e4aca104e](https://linux-hardware.org/?probe=9e4aca104e) | Jan 24, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [f48fe5a028](https://linux-hardware.org/?probe=f48fe5a028) | Jan 24, 2022 |
| MSI           | Z170A PC MATE               | [dd98b6fbca](https://linux-hardware.org/?probe=dd98b6fbca) | Jan 23, 2022 |
| ASRock        | H510M-ITX/ac                | [606c183545](https://linux-hardware.org/?probe=606c183545) | Jan 23, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [f950d7e322](https://linux-hardware.org/?probe=f950d7e322) | Jan 23, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1c15058d91](https://linux-hardware.org/?probe=1c15058d91) | Jan 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6d6c1565b7](https://linux-hardware.org/?probe=6d6c1565b7) | Jan 21, 2022 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [6cad862612](https://linux-hardware.org/?probe=6cad862612) | Jan 21, 2022 |
| Gigabyte      | Z590 VISION D               | [1d8fa44afd](https://linux-hardware.org/?probe=1d8fa44afd) | Jan 20, 2022 |
| Medion        | H110H4-EM                   | [64a2a3257d](https://linux-hardware.org/?probe=64a2a3257d) | Jan 20, 2022 |
| Dell          | 0YXT71 A03                  | [3609f04919](https://linux-hardware.org/?probe=3609f04919) | Jan 19, 2022 |
| Medion        | H110H4-EM                   | [6eab6bd21a](https://linux-hardware.org/?probe=6eab6bd21a) | Jan 19, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [993543545b](https://linux-hardware.org/?probe=993543545b) | Jan 18, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ce0d7ad7f6](https://linux-hardware.org/?probe=ce0d7ad7f6) | Jan 18, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [a7cc00f1bb](https://linux-hardware.org/?probe=a7cc00f1bb) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [7e0c6ebfc9](https://linux-hardware.org/?probe=7e0c6ebfc9) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [d531de56b2](https://linux-hardware.org/?probe=d531de56b2) | Jan 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5cccda3e40](https://linux-hardware.org/?probe=5cccda3e40) | Jan 18, 2022 |
| Dell          | 0R230R A00                  | [484bd19da3](https://linux-hardware.org/?probe=484bd19da3) | Jan 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2f8e734236](https://linux-hardware.org/?probe=2f8e734236) | Jan 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [42d55a089f](https://linux-hardware.org/?probe=42d55a089f) | Jan 16, 2022 |
| Dell          | 0R230R A00                  | [9b7d66cb9d](https://linux-hardware.org/?probe=9b7d66cb9d) | Jan 16, 2022 |
| MSI           | B350M MORTAR                | [5f93713b6d](https://linux-hardware.org/?probe=5f93713b6d) | Jan 16, 2022 |
| Dell          | 01XK1W A00                  | [eafa397038](https://linux-hardware.org/?probe=eafa397038) | Jan 14, 2022 |
| Acer          | Aspire XC-230               | [ba7ea12461](https://linux-hardware.org/?probe=ba7ea12461) | Jan 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [8ec42ce5c6](https://linux-hardware.org/?probe=8ec42ce5c6) | Jan 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d0ebb55aa3](https://linux-hardware.org/?probe=d0ebb55aa3) | Jan 12, 2022 |
| MSI           | X99S GAMING 7               | [66556a15be](https://linux-hardware.org/?probe=66556a15be) | Jan 11, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [4debe87ebd](https://linux-hardware.org/?probe=4debe87ebd) | Jan 11, 2022 |
| Intel         | D2550MUD2 AAG73892-600      | [7a18fc5ecf](https://linux-hardware.org/?probe=7a18fc5ecf) | Jan 11, 2022 |
| Gigabyte      | B450M DS3H V2               | [c4d0e193e1](https://linux-hardware.org/?probe=c4d0e193e1) | Jan 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8c319cd6fc](https://linux-hardware.org/?probe=8c319cd6fc) | Jan 11, 2022 |
| Dell          | 0KP561                      | [91846f4dc8](https://linux-hardware.org/?probe=91846f4dc8) | Jan 10, 2022 |
| ASRock        | H81M-VG4                    | [8678202106](https://linux-hardware.org/?probe=8678202106) | Jan 10, 2022 |
| ASUSTek       | P5WDG2 WS PRO               | [c22b31be4e](https://linux-hardware.org/?probe=c22b31be4e) | Jan 10, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [936bd6bf44](https://linux-hardware.org/?probe=936bd6bf44) | Jan 10, 2022 |
| Chatreey      | AC1-DP                      | [fb4af3e7ac](https://linux-hardware.org/?probe=fb4af3e7ac) | Jan 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [c8e28c5df0](https://linux-hardware.org/?probe=c8e28c5df0) | Jan 09, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | [6cb48fa647](https://linux-hardware.org/?probe=6cb48fa647) | Jan 08, 2022 |
| MSI           | B550-A PRO                  | [14e41b405a](https://linux-hardware.org/?probe=14e41b405a) | Jan 08, 2022 |
| Gigabyte      | H61M-S1                     | [50adc5f773](https://linux-hardware.org/?probe=50adc5f773) | Jan 08, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [b5fbd6f1c9](https://linux-hardware.org/?probe=b5fbd6f1c9) | Jan 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [4c8aea2ca5](https://linux-hardware.org/?probe=4c8aea2ca5) | Jan 08, 2022 |
| Gigabyte      | P55A-UD3                    | [46878503d2](https://linux-hardware.org/?probe=46878503d2) | Jan 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5b879a9c87](https://linux-hardware.org/?probe=5b879a9c87) | Jan 07, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [8a1611ac33](https://linux-hardware.org/?probe=8a1611ac33) | Jan 06, 2022 |
| MSI           | B85M-E33 V2                 | [ef65c0c144](https://linux-hardware.org/?probe=ef65c0c144) | Jan 05, 2022 |
| ASRock        | Z77 Pro4                    | [d83cbe9961](https://linux-hardware.org/?probe=d83cbe9961) | Jan 05, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | [a1e2cab707](https://linux-hardware.org/?probe=a1e2cab707) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [f5f5eadcd4](https://linux-hardware.org/?probe=f5f5eadcd4) | Jan 04, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [608b8edfd4](https://linux-hardware.org/?probe=608b8edfd4) | Jan 03, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [157c5615eb](https://linux-hardware.org/?probe=157c5615eb) | Jan 03, 2022 |
| Dell          | 08HPGT A01                  | [ce034fa823](https://linux-hardware.org/?probe=ce034fa823) | Jan 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [5209cf627a](https://linux-hardware.org/?probe=5209cf627a) | Jan 02, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [ec461a0a66](https://linux-hardware.org/?probe=ec461a0a66) | Jan 02, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | [8317742b36](https://linux-hardware.org/?probe=8317742b36) | Jan 01, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [255ef3cc1a](https://linux-hardware.org/?probe=255ef3cc1a) | Jan 01, 2022 |
| ASUSTek       | M51BC                       | [bdf0263352](https://linux-hardware.org/?probe=bdf0263352) | Dec 31, 2021 |
| MSI           | MAG B550 TORPEDO            | [b674024789](https://linux-hardware.org/?probe=b674024789) | Dec 30, 2021 |
| Dell          | 01XK1W A00                  | [5407438c6e](https://linux-hardware.org/?probe=5407438c6e) | Dec 30, 2021 |
| Dell          | 01XK1W A00                  | [0b80d9da29](https://linux-hardware.org/?probe=0b80d9da29) | Dec 30, 2021 |
| ASUSTek       | Rampage Formula             | [5c4181f9b7](https://linux-hardware.org/?probe=5c4181f9b7) | Dec 29, 2021 |
| MSI           | B150M PRO-VDH               | [6af03f4abc](https://linux-hardware.org/?probe=6af03f4abc) | Dec 28, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | [becfdd4806](https://linux-hardware.org/?probe=becfdd4806) | Dec 28, 2021 |
| ASRock        | B550M-ITX/ac                | [ea1a58e848](https://linux-hardware.org/?probe=ea1a58e848) | Dec 26, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b482ef13ea](https://linux-hardware.org/?probe=b482ef13ea) | Dec 26, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [9257b6fa8f](https://linux-hardware.org/?probe=9257b6fa8f) | Dec 26, 2021 |
| HP            | 1998                        | [fffadbe1cf](https://linux-hardware.org/?probe=fffadbe1cf) | Dec 25, 2021 |
| Acer          | Aspire XC-885 V:1.1         | [c7fcfb6f2a](https://linux-hardware.org/?probe=c7fcfb6f2a) | Dec 25, 2021 |
| HP            | 3047h                       | [71b6f0abea](https://linux-hardware.org/?probe=71b6f0abea) | Dec 25, 2021 |
| Gigabyte      | B450M DS3H V2               | [c3905a26bc](https://linux-hardware.org/?probe=c3905a26bc) | Dec 24, 2021 |
| MSI           | Z77A-G43                    | [f3b0f91998](https://linux-hardware.org/?probe=f3b0f91998) | Dec 23, 2021 |
| MSI           | Z77A-G43                    | [ec762046b0](https://linux-hardware.org/?probe=ec762046b0) | Dec 23, 2021 |
| Dell          | 0Y56T3 A00                  | [456cb4ebcc](https://linux-hardware.org/?probe=456cb4ebcc) | Dec 23, 2021 |
| HP            | 1494                        | [690d2204ea](https://linux-hardware.org/?probe=690d2204ea) | Dec 23, 2021 |
| MSI           | X470 GAMING PRO             | [d683987eea](https://linux-hardware.org/?probe=d683987eea) | Dec 23, 2021 |
| Intel         | X79 V1.3                    | [fbd3ea5fee](https://linux-hardware.org/?probe=fbd3ea5fee) | Dec 23, 2021 |
| MSI           | Z590-A PRO                  | [4b20c43b53](https://linux-hardware.org/?probe=4b20c43b53) | Dec 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | [1f334f4c1c](https://linux-hardware.org/?probe=1f334f4c1c) | Dec 22, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [32e8c7ccb2](https://linux-hardware.org/?probe=32e8c7ccb2) | Dec 22, 2021 |
| ASRock        | X399 Taichi                 | [2ebe7aff5f](https://linux-hardware.org/?probe=2ebe7aff5f) | Dec 21, 2021 |
| ASUSTek       | P5LD2-SE                    | [28771b0751](https://linux-hardware.org/?probe=28771b0751) | Dec 21, 2021 |
| MSI           | A78M-E45 V2                 | [abed6d2431](https://linux-hardware.org/?probe=abed6d2431) | Dec 19, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [69570e76ba](https://linux-hardware.org/?probe=69570e76ba) | Dec 19, 2021 |
| ASUSTek       | PRIME B350M-A               | [d38d7f8ea2](https://linux-hardware.org/?probe=d38d7f8ea2) | Dec 18, 2021 |
| HP            | 8169                        | [ed47c6784c](https://linux-hardware.org/?probe=ed47c6784c) | Dec 18, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [855061aa1a](https://linux-hardware.org/?probe=855061aa1a) | Dec 18, 2021 |
| ASRock        | H510M-HVS R2.0              | [99e3241324](https://linux-hardware.org/?probe=99e3241324) | Dec 18, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [13bfd7bbd2](https://linux-hardware.org/?probe=13bfd7bbd2) | Dec 18, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [856134876d](https://linux-hardware.org/?probe=856134876d) | Dec 18, 2021 |
| ASUSTek       | P5K SE                      | [bd3d222214](https://linux-hardware.org/?probe=bd3d222214) | Dec 17, 2021 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [bfe957f66c](https://linux-hardware.org/?probe=bfe957f66c) | Dec 17, 2021 |
| Intel         | DX58SO2 AAG10925-205        | [952c6df001](https://linux-hardware.org/?probe=952c6df001) | Dec 16, 2021 |
| Intel         | DX58SO2 AAG10925-205        | [376eb1624e](https://linux-hardware.org/?probe=376eb1624e) | Dec 16, 2021 |
| Gigabyte      | B460M DS3H                  | [83c339b963](https://linux-hardware.org/?probe=83c339b963) | Dec 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | [b7b779b709](https://linux-hardware.org/?probe=b7b779b709) | Dec 16, 2021 |
| Dell          | 0427JK A00                  | [5633e414a2](https://linux-hardware.org/?probe=5633e414a2) | Dec 16, 2021 |
| MSI           | A320M-A PRO                 | [f3f7e374e1](https://linux-hardware.org/?probe=f3f7e374e1) | Dec 16, 2021 |
| Gigabyte      | H61MS                       | [f5d1de8ec2](https://linux-hardware.org/?probe=f5d1de8ec2) | Dec 15, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [9ea3459352](https://linux-hardware.org/?probe=9ea3459352) | Dec 15, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [a6ddae1f31](https://linux-hardware.org/?probe=a6ddae1f31) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [3d9f848d7e](https://linux-hardware.org/?probe=3d9f848d7e) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [0db7a32c32](https://linux-hardware.org/?probe=0db7a32c32) | Dec 15, 2021 |
| Pegatron      | IPPPV-D3G                   | [bcdd9529a6](https://linux-hardware.org/?probe=bcdd9529a6) | Dec 15, 2021 |
| ASUSTek       | PRIME B360-PLUS             | [d0889ec2eb](https://linux-hardware.org/?probe=d0889ec2eb) | Dec 14, 2021 |
| Gigabyte      | 970A-DS3P                   | [da23db2916](https://linux-hardware.org/?probe=da23db2916) | Dec 13, 2021 |
| Dell          | 0427JK A00                  | [785650303f](https://linux-hardware.org/?probe=785650303f) | Dec 13, 2021 |
| ASUSTek       | SABERTOOTH X58              | [28e1968e2a](https://linux-hardware.org/?probe=28e1968e2a) | Dec 13, 2021 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [59932384de](https://linux-hardware.org/?probe=59932384de) | Dec 13, 2021 |
| ASUSTek       | Rampage III Extreme         | [e60b9ed6dd](https://linux-hardware.org/?probe=e60b9ed6dd) | Dec 12, 2021 |
| Huanan        | X79                         | [86c899a9ae](https://linux-hardware.org/?probe=86c899a9ae) | Dec 11, 2021 |
| ASRock        | QC6000M                     | [3475206cb1](https://linux-hardware.org/?probe=3475206cb1) | Dec 10, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [89dd614f98](https://linux-hardware.org/?probe=89dd614f98) | Dec 09, 2021 |
| MSI           | B365M PLUS                  | [2b5c7216f7](https://linux-hardware.org/?probe=2b5c7216f7) | Dec 08, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [d580dc1bf8](https://linux-hardware.org/?probe=d580dc1bf8) | Dec 08, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [db552307a3](https://linux-hardware.org/?probe=db552307a3) | Dec 07, 2021 |
| ASUSTek       | G20AJ                       | [8f17fe0c1e](https://linux-hardware.org/?probe=8f17fe0c1e) | Dec 07, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [1c81e561e7](https://linux-hardware.org/?probe=1c81e561e7) | Dec 06, 2021 |
| HP            | 2B2C                        | [7a51474f1a](https://linux-hardware.org/?probe=7a51474f1a) | Dec 05, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [a3209e0ed1](https://linux-hardware.org/?probe=a3209e0ed1) | Dec 04, 2021 |
| ASUSTek       | PRIME A320M-K               | [d9019c420c](https://linux-hardware.org/?probe=d9019c420c) | Dec 04, 2021 |
| MSI           | B450 GAMING PLUS            | [69b4695e8d](https://linux-hardware.org/?probe=69b4695e8d) | Dec 04, 2021 |
| ASUSTek       | Rampage III Extreme         | [50d31f61ab](https://linux-hardware.org/?probe=50d31f61ab) | Dec 04, 2021 |
| ASUSTek       | Rampage III Extreme         | [62fe653f0b](https://linux-hardware.org/?probe=62fe653f0b) | Dec 03, 2021 |
| Gigabyte      | B150M-D3H-CF                | [633a8b9f67](https://linux-hardware.org/?probe=633a8b9f67) | Dec 03, 2021 |
| Pegatron      | 2AD2A                       | [62775fc64d](https://linux-hardware.org/?probe=62775fc64d) | Dec 03, 2021 |
| Gigabyte      | GA-970A-DS3                 | [e22dd08488](https://linux-hardware.org/?probe=e22dd08488) | Dec 02, 2021 |
| ASUSTek       | PRIME B250-PRO              | [ca0a1ff745](https://linux-hardware.org/?probe=ca0a1ff745) | Dec 02, 2021 |
| Intel         | X99 V1.x                    | [727aef8ed6](https://linux-hardware.org/?probe=727aef8ed6) | Dec 02, 2021 |
| ASUSTek       | PRIME B250-PRO              | [51a3b8e589](https://linux-hardware.org/?probe=51a3b8e589) | Dec 02, 2021 |
| ASUSTek       | PRIME X399-A                | [069ca6ffe2](https://linux-hardware.org/?probe=069ca6ffe2) | Dec 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | [55a4727c30](https://linux-hardware.org/?probe=55a4727c30) | Dec 01, 2021 |
| ASRock        | G41M-VS3                    | [e2d4b12fef](https://linux-hardware.org/?probe=e2d4b12fef) | Dec 01, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [0a3e70b938](https://linux-hardware.org/?probe=0a3e70b938) | Dec 01, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [57587ffa8e](https://linux-hardware.org/?probe=57587ffa8e) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [6807edf501](https://linux-hardware.org/?probe=6807edf501) | Dec 01, 2021 |
| ASUSTek       | H110M-A/M.2                 | [7fe28eead2](https://linux-hardware.org/?probe=7fe28eead2) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | [fe3d4f5bc1](https://linux-hardware.org/?probe=fe3d4f5bc1) | Nov 30, 2021 |
| Gigabyte      | H61M-S2PV                   | [9feb65b15d](https://linux-hardware.org/?probe=9feb65b15d) | Nov 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6762543fa8](https://linux-hardware.org/?probe=6762543fa8) | Nov 30, 2021 |
| Gigabyte      | Z490 AORUS XTREME           | [e964d05300](https://linux-hardware.org/?probe=e964d05300) | Nov 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [69a76fd0b6](https://linux-hardware.org/?probe=69a76fd0b6) | Nov 29, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [d41428d9f6](https://linux-hardware.org/?probe=d41428d9f6) | Nov 29, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [ab1b265412](https://linux-hardware.org/?probe=ab1b265412) | Nov 29, 2021 |
| ASUSTek       | P5E-VM DO                   | [6c61c57e1d](https://linux-hardware.org/?probe=6c61c57e1d) | Nov 28, 2021 |
| Dell          | 0WN7Y6 A01                  | [f51a3541c8](https://linux-hardware.org/?probe=f51a3541c8) | Nov 28, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [f34bca522a](https://linux-hardware.org/?probe=f34bca522a) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [0cb5ca7e51](https://linux-hardware.org/?probe=0cb5ca7e51) | Nov 28, 2021 |
| ASUSTek       | P5E-VM DO                   | [a754ed7b33](https://linux-hardware.org/?probe=a754ed7b33) | Nov 27, 2021 |
| Dell          | 042P49 A02                  | [f6d9c481bd](https://linux-hardware.org/?probe=f6d9c481bd) | Nov 27, 2021 |
| ASUSTek       | PRIME B450M-A               | [4bbdbb4261](https://linux-hardware.org/?probe=4bbdbb4261) | Nov 27, 2021 |
| Gigabyte      | 945GCMX-S2                  | [7280b29922](https://linux-hardware.org/?probe=7280b29922) | Nov 27, 2021 |
| Gigabyte      | B450M DS3H-CF               | [9c3cc382a3](https://linux-hardware.org/?probe=9c3cc382a3) | Nov 26, 2021 |
| MSI           | X470 GAMING PLUS            | [289027e0cf](https://linux-hardware.org/?probe=289027e0cf) | Nov 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [e7cfc4b381](https://linux-hardware.org/?probe=e7cfc4b381) | Nov 25, 2021 |
| ASRock        | Z370 Taichi                 | [f0deb8e1ab](https://linux-hardware.org/?probe=f0deb8e1ab) | Nov 25, 2021 |
| HP            | 1589                        | [51a24550cd](https://linux-hardware.org/?probe=51a24550cd) | Nov 25, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [6016236fad](https://linux-hardware.org/?probe=6016236fad) | Nov 24, 2021 |
| Acer          | Aspire X1430G               | [de61443dc4](https://linux-hardware.org/?probe=de61443dc4) | Nov 24, 2021 |
| Acer          | Aspire X1430G               | [80780aa6df](https://linux-hardware.org/?probe=80780aa6df) | Nov 24, 2021 |
| Intel         | DH67BL AAG10189-208         | [dbf2659c98](https://linux-hardware.org/?probe=dbf2659c98) | Nov 23, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [81a6212074](https://linux-hardware.org/?probe=81a6212074) | Nov 23, 2021 |
| ASUSTek       | SABERTOOTH X58              | [35534f78a5](https://linux-hardware.org/?probe=35534f78a5) | Nov 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f5cadf9b2e](https://linux-hardware.org/?probe=f5cadf9b2e) | Nov 23, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | [19812541db](https://linux-hardware.org/?probe=19812541db) | Nov 23, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | [0eac4a44ef](https://linux-hardware.org/?probe=0eac4a44ef) | Nov 23, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [bc6d62f60a](https://linux-hardware.org/?probe=bc6d62f60a) | Nov 22, 2021 |
| Gigabyte      | B460M GAMING HD             | [b15ec9f086](https://linux-hardware.org/?probe=b15ec9f086) | Nov 21, 2021 |
| Gigabyte      | Z77M-D3H                    | [2443700844](https://linux-hardware.org/?probe=2443700844) | Nov 21, 2021 |
| Gigabyte      | H270-HD3-CF                 | [de03a1c3ee](https://linux-hardware.org/?probe=de03a1c3ee) | Nov 21, 2021 |
| ASRock        | 970 Extreme4                | [8cd3929553](https://linux-hardware.org/?probe=8cd3929553) | Nov 21, 2021 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [bd12b5a969](https://linux-hardware.org/?probe=bd12b5a969) | Nov 21, 2021 |
| Gigabyte      | B550 AORUS PRO              | [ccd0498c9b](https://linux-hardware.org/?probe=ccd0498c9b) | Nov 20, 2021 |
| Lenovo        | ThinkStation S20 4157FY2    | [b05be2384d](https://linux-hardware.org/?probe=b05be2384d) | Nov 20, 2021 |
| MSI           | H81M-P33                    | [cc4ed13747](https://linux-hardware.org/?probe=cc4ed13747) | Nov 19, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [bd795eb1c2](https://linux-hardware.org/?probe=bd795eb1c2) | Nov 19, 2021 |
| ASUSTek       | M51BC                       | [dfc2c68c8d](https://linux-hardware.org/?probe=dfc2c68c8d) | Nov 19, 2021 |
| Dell          | 0M9KCM A02                  | [0a32a05b5c](https://linux-hardware.org/?probe=0a32a05b5c) | Nov 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [633630572c](https://linux-hardware.org/?probe=633630572c) | Nov 18, 2021 |
| HP            | 82F2                        | [864b1b1731](https://linux-hardware.org/?probe=864b1b1731) | Nov 18, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2dc50bf90a](https://linux-hardware.org/?probe=2dc50bf90a) | Nov 18, 2021 |
| ASUSTek       | P8H67-M PRO                 | [019ff66515](https://linux-hardware.org/?probe=019ff66515) | Nov 18, 2021 |
| Dell          | 0M9KCM A02                  | [e19037ab0d](https://linux-hardware.org/?probe=e19037ab0d) | Nov 18, 2021 |
| MSI           | B450 TOMAHAWK               | [2e5006f24c](https://linux-hardware.org/?probe=2e5006f24c) | Nov 18, 2021 |
| ASUSTek       | P8H67-M PRO                 | [b378b1b259](https://linux-hardware.org/?probe=b378b1b259) | Nov 17, 2021 |
| Dell          | 0GXM1W A02                  | [0631623e1e](https://linux-hardware.org/?probe=0631623e1e) | Nov 17, 2021 |
| MSI           | H310M PRO-VDH               | [645d9fd97e](https://linux-hardware.org/?probe=645d9fd97e) | Nov 17, 2021 |
| MSI           | H310M PRO-VDH               | [d4f2aa5324](https://linux-hardware.org/?probe=d4f2aa5324) | Nov 17, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [e4375ff53a](https://linux-hardware.org/?probe=e4375ff53a) | Nov 16, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [b8aa4af077](https://linux-hardware.org/?probe=b8aa4af077) | Nov 16, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [3ffb20130b](https://linux-hardware.org/?probe=3ffb20130b) | Nov 16, 2021 |
| MSI           | MPG B550I GAMING EDGE MA... | [1ec9076975](https://linux-hardware.org/?probe=1ec9076975) | Nov 16, 2021 |
| ASRock        | B450M Pro4                  | [9070f5cc5f](https://linux-hardware.org/?probe=9070f5cc5f) | Nov 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [f30f49d634](https://linux-hardware.org/?probe=f30f49d634) | Nov 16, 2021 |
| Dell          | 0C27VV A01                  | [20f3d82708](https://linux-hardware.org/?probe=20f3d82708) | Nov 15, 2021 |
| Dell          | 0C27VV A01                  | [41db42ad22](https://linux-hardware.org/?probe=41db42ad22) | Nov 15, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [0ff55f060f](https://linux-hardware.org/?probe=0ff55f060f) | Nov 14, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [9a7d3c310f](https://linux-hardware.org/?probe=9a7d3c310f) | Nov 14, 2021 |
| MSI           | 970A-G43                    | [da61ca8b52](https://linux-hardware.org/?probe=da61ca8b52) | Nov 13, 2021 |
| MSI           | 970A-G43                    | [d27f131cce](https://linux-hardware.org/?probe=d27f131cce) | Nov 13, 2021 |
| MSI           | MPG B550I GAMING EDGE MA... | [a031da091f](https://linux-hardware.org/?probe=a031da091f) | Nov 13, 2021 |
| Dell          | 08HPGT A01                  | [933234f294](https://linux-hardware.org/?probe=933234f294) | Nov 12, 2021 |
| Gigabyte      | G31M-ES2L                   | [fccd73da9d](https://linux-hardware.org/?probe=fccd73da9d) | Nov 12, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [5a9d6ba46e](https://linux-hardware.org/?probe=5a9d6ba46e) | Nov 12, 2021 |
| Pegatron      | 2AD2A                       | [5e251eb093](https://linux-hardware.org/?probe=5e251eb093) | Nov 12, 2021 |
| Intel         | DP55WB AAE64798-207         | [f806b413c5](https://linux-hardware.org/?probe=f806b413c5) | Nov 11, 2021 |
| MSI           | H81M-P33                    | [a42a22a526](https://linux-hardware.org/?probe=a42a22a526) | Nov 11, 2021 |
| Gigabyte      | B550M DS3H                  | [51777be647](https://linux-hardware.org/?probe=51777be647) | Nov 11, 2021 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [7b125e4ba6](https://linux-hardware.org/?probe=7b125e4ba6) | Nov 11, 2021 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [b11f112034](https://linux-hardware.org/?probe=b11f112034) | Nov 11, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [d0f30ab5d2](https://linux-hardware.org/?probe=d0f30ab5d2) | Nov 10, 2021 |
| Intel         | D945GCL AAD75361-301        | [378e32942d](https://linux-hardware.org/?probe=378e32942d) | Nov 10, 2021 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [6219a911b9](https://linux-hardware.org/?probe=6219a911b9) | Nov 10, 2021 |
| ASUSTek       | PRIME X470-PRO              | [cd42c62b14](https://linux-hardware.org/?probe=cd42c62b14) | Nov 09, 2021 |
| ASUSTek       | X99-A                       | [99d97fbc79](https://linux-hardware.org/?probe=99d97fbc79) | Nov 09, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [a6a6f59d46](https://linux-hardware.org/?probe=a6a6f59d46) | Nov 09, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [3d661ce2df](https://linux-hardware.org/?probe=3d661ce2df) | Nov 09, 2021 |
| ASUSTek       | PRIME X570-PRO              | [a1a9bf0a7a](https://linux-hardware.org/?probe=a1a9bf0a7a) | Nov 09, 2021 |
| Acer          | Aspire XC-230               | [6ccebdc02f](https://linux-hardware.org/?probe=6ccebdc02f) | Nov 09, 2021 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [9f4639af3b](https://linux-hardware.org/?probe=9f4639af3b) | Nov 08, 2021 |
| Intel         | D945GCL AAD75361-301        | [510547811c](https://linux-hardware.org/?probe=510547811c) | Nov 08, 2021 |
| Gigabyte      | A520M S2H                   | [67a720ad20](https://linux-hardware.org/?probe=67a720ad20) | Nov 07, 2021 |
| ASUSTek       | Z97-A-USB31                 | [10a403bc34](https://linux-hardware.org/?probe=10a403bc34) | Nov 07, 2021 |
| ASRock        | B365 Pro4                   | [5010ca9e9a](https://linux-hardware.org/?probe=5010ca9e9a) | Nov 06, 2021 |
| Acer          | Aspire XC-230               | [5ec278c995](https://linux-hardware.org/?probe=5ec278c995) | Nov 05, 2021 |
| ASUSTek       | P5LD2-SE                    | [4f817c0167](https://linux-hardware.org/?probe=4f817c0167) | Nov 03, 2021 |
| ASUSTek       | PRIME B360M-A               | [e8ef49b867](https://linux-hardware.org/?probe=e8ef49b867) | Nov 03, 2021 |
| Gigabyte      | B85-HD3                     | [05eee3d7f5](https://linux-hardware.org/?probe=05eee3d7f5) | Nov 03, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [731013ba31](https://linux-hardware.org/?probe=731013ba31) | Nov 02, 2021 |
| ASUSTek       | P5LD2-SE                    | [8ba60d9634](https://linux-hardware.org/?probe=8ba60d9634) | Nov 01, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [f8a7da7b89](https://linux-hardware.org/?probe=f8a7da7b89) | Nov 01, 2021 |
| ASUSTek       | M3A78-EM                    | [f96e0bb7fc](https://linux-hardware.org/?probe=f96e0bb7fc) | Nov 01, 2021 |
| MSI           | B450M PRO-VDH MAX           | [4ecaef699b](https://linux-hardware.org/?probe=4ecaef699b) | Nov 01, 2021 |
| Gigabyte      | B550 AORUS PRO              | [b75ca3ba11](https://linux-hardware.org/?probe=b75ca3ba11) | Nov 01, 2021 |
| ASUSTek       | PRIME A320M-K               | [491d1a96cc](https://linux-hardware.org/?probe=491d1a96cc) | Oct 31, 2021 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [f3b1068713](https://linux-hardware.org/?probe=f3b1068713) | Oct 31, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b9c2fec8aa](https://linux-hardware.org/?probe=b9c2fec8aa) | Oct 30, 2021 |
| MSI           | Z170A SLI PLUS              | [2d4144d0b9](https://linux-hardware.org/?probe=2d4144d0b9) | Oct 30, 2021 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [179bbb4416](https://linux-hardware.org/?probe=179bbb4416) | Oct 29, 2021 |
| MSI           | B350M MORTAR                | [bab0e06723](https://linux-hardware.org/?probe=bab0e06723) | Oct 29, 2021 |
| ASUSTek       | LEONITE                     | [42098ee0e7](https://linux-hardware.org/?probe=42098ee0e7) | Oct 29, 2021 |
| ASUSTek       | P5Q-PRO                     | [f6317b60dd](https://linux-hardware.org/?probe=f6317b60dd) | Oct 28, 2021 |
| ASUSTek       | SABERTOOTH X79              | [2b361b1035](https://linux-hardware.org/?probe=2b361b1035) | Oct 28, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [3b46a4881d](https://linux-hardware.org/?probe=3b46a4881d) | Oct 27, 2021 |
| Huanan        | X99-F8 V2.0                 | [17b2218dab](https://linux-hardware.org/?probe=17b2218dab) | Oct 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [688a36c9df](https://linux-hardware.org/?probe=688a36c9df) | Oct 26, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Manjaro           | 948      | 39.58%  |
| Manjaro 20.1      | 135      | 5.64%   |
| Manjaro 20.2.1    | 108      | 4.51%   |
| Manjaro 20.2      | 89       | 3.72%   |
| Manjaro 20.0.3    | 81       | 3.38%   |
| Manjaro 18.1.5    | 56       | 2.34%   |
| Manjaro 21.2.6    | 53       | 2.21%   |
| Manjaro 21.2.5    | 53       | 2.21%   |
| Manjaro 21.1.0    | 53       | 2.21%   |
| Manjaro 22.0.0    | 48       | 2%      |
| Manjaro 18.0.4    | 46       | 1.92%   |
| Manjaro 21.2.0    | 45       | 1.88%   |
| Manjaro 20.0      | 45       | 1.88%   |
| Manjaro 21.1.6    | 38       | 1.59%   |
| Manjaro 21.0.7    | 36       | 1.5%    |
| Manjaro 21.0.5    | 35       | 1.46%   |
| Manjaro 21.0      | 35       | 1.46%   |
| Manjaro 19.0.2    | 31       | 1.29%   |
| Manjaro 20.1.2    | 29       | 1.21%   |
| Manjaro 20.0.1    | 29       | 1.21%   |
| Manjaro 21.2.3    | 27       | 1.13%   |
| Manjaro 20.1.1    | 24       | 1%      |
| Manjaro 21.2.1    | 23       | 0.96%   |
| Manjaro 21.3.7    | 17       | 0.71%   |
| Manjaro 21.3.6    | 17       | 0.71%   |
| Manjaro 21.0.4    | 16       | 0.67%   |
| Manjaro 21.0.1    | 14       | 0.58%   |
| Manjaro 21.0.2    | 13       | 0.54%   |
| Manjaro 21.2rc    | 12       | 0.5%    |
| Manjaro 21.2.4    | 12       | 0.5%    |
| Manjaro 21.1.2    | 12       | 0.5%    |
| Manjaro 21.0.3    | 12       | 0.5%    |
| Manjaro 18.0.0-rc | 12       | 0.5%    |
| Manjaro 21.3.1    | 11       | 0.46%   |
| Manjaro 21.1.5    | 11       | 0.46%   |
| Manjaro 21.3.0    | 10       | 0.42%   |
| Manjaro 21.2.2    | 10       | 0.42%   |
| Manjaro 21.1.4    | 10       | 0.42%   |
| Manjaro 18.1.3    | 9        | 0.38%   |
| Manjaro 18.0.0    | 9        | 0.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Manjaro | 2194     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.9.16-1-MANJARO  | 113      | 4.27%   |
| 5.8.6-1-MANJARO   | 68       | 2.57%   |
| 5.13.19-2-MANJARO | 65       | 2.46%   |
| 5.15.28-1-MANJARO | 49       | 1.85%   |
| 5.9.11-3-MANJARO  | 47       | 1.78%   |
| 5.8.11-1-MANJARO  | 46       | 1.74%   |
| 5.10.42-1-MANJARO | 40       | 1.51%   |
| 5.8.18-1-MANJARO  | 38       | 1.44%   |
| 5.15.32-1-MANJARO | 32       | 1.21%   |
| 5.6.16-1-MANJARO  | 31       | 1.17%   |
| 5.10.36-2-MANJARO | 30       | 1.13%   |
| 5.7.9-1-MANJARO   | 29       | 1.1%    |
| 5.15.12-1-MANJARO | 29       | 1.1%    |
| 5.15.60-1-MANJARO | 26       | 0.98%   |
| 5.8.3-2-MANJARO   | 25       | 0.95%   |
| 5.8.16-2-MANJARO  | 25       | 0.95%   |
| 5.6.19-2-MANJARO  | 24       | 0.91%   |
| 5.6.15-1-MANJARO  | 24       | 0.91%   |
| 5.17.1-3-MANJARO  | 24       | 0.91%   |
| 5.7.0-3-MANJARO   | 23       | 0.87%   |
| 5.10.2-2-MANJARO  | 23       | 0.87%   |
| 5.6.7-1-MANJARO   | 22       | 0.83%   |
| 5.6.12-1-MANJARO  | 22       | 0.83%   |
| 5.16.14-1-MANJARO | 22       | 0.83%   |
| 5.15.2-2-MANJARO  | 22       | 0.83%   |
| 5.10.23-1-MANJARO | 22       | 0.83%   |
| 5.9.1-1-MANJARO   | 21       | 0.79%   |
| 5.11.6-1-MANJARO  | 21       | 0.79%   |
| 5.4.15-2-MANJARO  | 20       | 0.76%   |
| 5.7.17-2-MANJARO  | 19       | 0.72%   |
| 5.4.6-2-MANJARO   | 19       | 0.72%   |
| 5.10.7-3-MANJARO  | 19       | 0.72%   |
| 5.10.15-1-MANJARO | 19       | 0.72%   |
| 5.14.10-1-MANJARO | 17       | 0.64%   |
| 5.11.2-1-MANJARO  | 17       | 0.64%   |
| 5.10.53-1-MANJARO | 17       | 0.64%   |
| 5.9.3-1-MANJARO   | 16       | 0.6%    |
| 5.6.11-1-MANJARO  | 16       | 0.6%    |
| 5.15.7-1-MANJARO  | 16       | 0.6%    |
| 5.15.41-1-MANJARO | 16       | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 113      | 4.27%   |
| 5.8.6   | 68       | 2.57%   |
| 5.13.19 | 65       | 2.46%   |
| 5.9.11  | 50       | 1.89%   |
| 5.15.28 | 49       | 1.85%   |
| 5.8.11  | 47       | 1.78%   |
| 5.10.42 | 40       | 1.51%   |
| 5.8.18  | 38       | 1.44%   |
| 5.15.32 | 32       | 1.21%   |
| 5.6.16  | 31       | 1.17%   |
| 5.10.36 | 30       | 1.13%   |
| 5.7.9   | 29       | 1.1%    |
| 5.7.0   | 29       | 1.1%    |
| 5.17.1  | 29       | 1.1%    |
| 5.15.12 | 29       | 1.1%    |
| 5.9.1   | 28       | 1.06%   |
| 5.6.19  | 27       | 1.02%   |
| 5.8.3   | 26       | 0.98%   |
| 5.15.60 | 26       | 0.98%   |
| 5.8.16  | 25       | 0.95%   |
| 5.6.15  | 24       | 0.91%   |
| 5.6.12  | 23       | 0.87%   |
| 5.15.2  | 23       | 0.87%   |
| 5.10.2  | 23       | 0.87%   |
| 5.6.7   | 22       | 0.83%   |
| 5.16.14 | 22       | 0.83%   |
| 5.10.23 | 22       | 0.83%   |
| 5.11.6  | 21       | 0.79%   |
| 5.7.17  | 20       | 0.76%   |
| 5.4.15  | 20       | 0.76%   |
| 5.10.7  | 20       | 0.76%   |
| 5.4.6   | 19       | 0.72%   |
| 5.10.15 | 19       | 0.72%   |
| 5.15.7  | 17       | 0.64%   |
| 5.14.10 | 17       | 0.64%   |
| 5.14.0  | 17       | 0.64%   |
| 5.11.2  | 17       | 0.64%   |
| 5.10.53 | 17       | 0.64%   |
| 5.9.3   | 16       | 0.61%   |
| 5.6.11  | 16       | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 351      | 14.14%  |
| 5.15    | 347      | 13.98%  |
| 5.4     | 252      | 10.15%  |
| 5.8     | 228      | 9.18%   |
| 5.9     | 227      | 9.14%   |
| 5.6     | 172      | 6.93%   |
| 5.13    | 125      | 5.03%   |
| 5.7     | 109      | 4.39%   |
| 5.11    | 91       | 3.66%   |
| 4.19    | 66       | 2.66%   |
| 5.17    | 64       | 2.58%   |
| 5.16    | 62       | 2.5%    |
| 5.14    | 61       | 2.46%   |
| 5.18    | 53       | 2.13%   |
| 5.12    | 49       | 1.97%   |
| 5.19    | 45       | 1.81%   |
| 5.5     | 39       | 1.57%   |
| 4.14    | 33       | 1.33%   |
| 5.3     | 23       | 0.93%   |
| 6.0     | 22       | 0.89%   |
| 5.2     | 17       | 0.68%   |
| 5.1     | 13       | 0.52%   |
| 5.0     | 11       | 0.44%   |
| 4.20    | 5        | 0.2%    |
| 4.18    | 5        | 0.2%    |
| 4.17    | 3        | 0.12%   |
| 4.16    | 3        | 0.12%   |
| 4.9     | 2        | 0.08%   |
| 4.7     | 2        | 0.08%   |
| 4.4     | 2        | 0.08%   |
| 6.1     | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2194     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| KDE5                     | 790      | 34.3%   |
| XFCE                     | 516      | 22.41%  |
| GNOME                    | 440      | 19.11%  |
| KDE                      | 243      | 10.55%  |
| Unknown                  | 98       | 4.26%   |
| X-Cinnamon               | 73       | 3.17%   |
| i3                       | 43       | 1.87%   |
| Cinnamon                 | 22       | 0.96%   |
| MATE                     | 21       | 0.91%   |
| Deepin                   | 21       | 0.91%   |
| Budgie                   | 12       | 0.52%   |
| LXQt                     | 7        | 0.3%    |
| Awesome                  | 4        | 0.17%   |
| bspwm                    | 3        | 0.13%   |
| sway                     | 2        | 0.09%   |
| ICEWM                    | 2        | 0.09%   |
| GNOME Classic            | 2        | 0.09%   |
| openbox                  | 1        | 0.04%   |
| LXDE                     | 1        | 0.04%   |
| DWM                      | 1        | 0.04%   |
| /usr/bin/openbox-session | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2017     | 90.33%  |
| Wayland | 156      | 6.99%   |
| Unknown | 37       | 1.66%   |
| Tty     | 23       | 1.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 942      | 41.53%  |
| SDDM    | 581      | 25.62%  |
| LightDM | 397      | 17.5%   |
| GDM     | 251      | 11.07%  |
| TDM     | 89       | 3.92%   |
| LXDM    | 4        | 0.18%   |
| SLiM    | 2        | 0.09%   |
| XDM     | 1        | 0.04%   |
| GREETD  | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 883      | 39.54%  |
| de_DE   | 190      | 8.51%   |
| ru_RU   | 181      | 8.11%   |
| Unknown | 151      | 6.76%   |
| en_GB   | 135      | 6.05%   |
| pt_BR   | 92       | 4.12%   |
| en_CA   | 62       | 2.78%   |
| fr_FR   | 55       | 2.46%   |
| es_ES   | 53       | 2.37%   |
| it_IT   | 46       | 2.06%   |
| pl_PL   | 41       | 1.84%   |
| en_AU   | 29       | 1.3%    |
| en_IN   | 19       | 0.85%   |
| ru_UA   | 18       | 0.81%   |
| nl_NL   | 17       | 0.76%   |
| sv_SE   | 14       | 0.63%   |
| de_AT   | 14       | 0.63%   |
| zh_CN   | 13       | 0.58%   |
| es_AR   | 12       | 0.54%   |
| fi_FI   | 11       | 0.49%   |
| es_MX   | 11       | 0.49%   |
| en_IE   | 11       | 0.49%   |
| en_ZA   | 9        | 0.4%    |
| hu_HU   | 8        | 0.36%   |
| fr_CA   | 8        | 0.36%   |
| en_NZ   | 8        | 0.36%   |
| da_DK   | 8        | 0.36%   |
| pt_PT   | 7        | 0.31%   |
| es_CL   | 7        | 0.31%   |
| en_PH   | 7        | 0.31%   |
| en_IL   | 6        | 0.27%   |
| cs_CZ   | 6        | 0.27%   |
| uk_UA   | 5        | 0.22%   |
| ja_JP   | 5        | 0.22%   |
| en_DK   | 5        | 0.22%   |
| tr_TR   | 4        | 0.18%   |
| nb_NO   | 4        | 0.18%   |
| fr_BE   | 4        | 0.18%   |
| es_UY   | 4        | 0.18%   |
| en_DE   | 4        | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1394     | 62.15%  |
| EFI  | 849      | 37.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1888     | 84.59%  |
| Btrfs   | 201      | 9.01%   |
| Unknown | 40       | 1.79%   |
| Xfs     | 37       | 1.66%   |
| Overlay | 34       | 1.52%   |
| F2fs    | 12       | 0.54%   |
| Tmpfs   | 9        | 0.4%    |
| Zfs     | 4        | 0.18%   |
| Ext2    | 3        | 0.13%   |
| Ext3    | 2        | 0.09%   |
| XXXX    | 1        | 0.04%   |
| XXXfs   | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1047     | 46.55%  |
| GPT     | 950      | 42.24%  |
| MBR     | 252      | 11.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1840     | 82.07%  |
| Yes       | 402      | 17.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1363     | 60.85%  |
| Yes       | 877      | 39.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 648      | 29.54%  |
| Gigabyte Technology | 461      | 21.01%  |
| MSI                 | 348      | 15.86%  |
| ASRock              | 242      | 11.03%  |
| Dell                | 110      | 5.01%   |
| Hewlett-Packard     | 104      | 4.74%   |
| Intel               | 51       | 2.32%   |
| Lenovo              | 43       | 1.96%   |
| Acer                | 27       | 1.23%   |
| Unknown             | 19       | 0.87%   |
| Biostar             | 17       | 0.77%   |
| Pegatron            | 14       | 0.64%   |
| Huanan              | 12       | 0.55%   |
| Foxconn             | 10       | 0.46%   |
| Medion              | 8        | 0.36%   |
| Fujitsu             | 7        | 0.32%   |
| ECS                 | 7        | 0.32%   |
| Apple               | 7        | 0.32%   |
| BESSTAR Tech        | 5        | 0.23%   |
| Alienware           | 4        | 0.18%   |
| Positivo            | 3        | 0.14%   |
| PCWare              | 3        | 0.14%   |
| AZW                 | 3        | 0.14%   |
| Shuttle             | 2        | 0.09%   |
| Minix               | 2        | 0.09%   |
| MACHINIST           | 2        | 0.09%   |
| Inventec            | 2        | 0.09%   |
| Google              | 2        | 0.09%   |
| Fujitsu Siemens     | 2        | 0.09%   |
| ZOTAC               | 1        | 0.05%   |
| XFX                 | 1        | 0.05%   |
| VS Company          | 1        | 0.05%   |
| TPV-INVENTA         | 1        | 0.05%   |
| SYWZ                | 1        | 0.05%   |
| System76            | 1        | 0.05%   |
| Supermicro          | 1        | 0.05%   |
| SiYW                | 1        | 0.05%   |
| Samsung Electronics | 1        | 0.05%   |
| Packard Bell        | 1        | 0.05%   |
| OEM                 | 1        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 63       | 2.87%   |
| Gigabyte B450M DS3H              | 25       | 1.14%   |
| MSI MS-7C37                      | 21       | 0.96%   |
| MSI MS-7C02                      | 21       | 0.96%   |
| Unknown                          | 21       | 0.96%   |
| ASUS TUF Gaming X570-PLUS        | 19       | 0.87%   |
| ASUS PRIME A320M-K               | 17       | 0.77%   |
| MSI MS-7B79                      | 15       | 0.68%   |
| ASRock B450M Pro4                | 15       | 0.68%   |
| MSI MS-7C91                      | 14       | 0.64%   |
| MSI MS-7B86                      | 13       | 0.59%   |
| ASUS ROG STRIX B450-F GAMING     | 13       | 0.59%   |
| MSI MS-7A38                      | 12       | 0.55%   |
| ASUS TUF Gaming B550M-PLUS       | 12       | 0.55%   |
| Gigabyte X570 AORUS ELITE        | 11       | 0.5%    |
| ASUS PRIME B450M-A               | 11       | 0.5%    |
| ASUS PRIME B350-PLUS             | 11       | 0.5%    |
| Gigabyte X570 AORUS MASTER       | 10       | 0.46%   |
| Gigabyte X470 AORUS ULTRA GAMING | 10       | 0.46%   |
| Gigabyte B450 AORUS M            | 10       | 0.46%   |
| Gigabyte 970A-DS3P               | 10       | 0.46%   |
| Dell OptiPlex 9020               | 10       | 0.46%   |
| MSI MS-7B89                      | 9        | 0.41%   |
| ASUS ROG STRIX X570-E GAMING     | 9        | 0.41%   |
| ASUS ROG CROSSHAIR VIII HERO     | 9        | 0.41%   |
| MSI MS-7C94                      | 8        | 0.36%   |
| MSI MS-7A34                      | 8        | 0.36%   |
| MSI MS-7817                      | 8        | 0.36%   |
| MSI MS-7693                      | 8        | 0.36%   |
| Dell OptiPlex 7010               | 8        | 0.36%   |
| ASUS ROG STRIX B550-F GAMING     | 8        | 0.36%   |
| ASUS PRIME X470-PRO              | 8        | 0.36%   |
| ASRock B450 Pro4                 | 8        | 0.36%   |
| Gigabyte B450 AORUS ELITE        | 7        | 0.32%   |
| ASUS PRIME X370-PRO              | 7        | 0.32%   |
| ASUS PRIME B450-PLUS             | 7        | 0.32%   |
| ASUS PRIME B350M-A               | 7        | 0.32%   |
| ASUS M5A78L-M PLUS/USB3          | 7        | 0.32%   |
| MSI MS-7C84                      | 6        | 0.27%   |
| MSI MS-7A32                      | 6        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 132      | 6.02%   |
| ASUS ROG           | 116      | 5.29%   |
| ASUS TUF           | 67       | 3.05%   |
| Dell OptiPlex      | 66       | 3.01%   |
| ASUS All           | 63       | 2.87%   |
| Gigabyte X570      | 44       | 2.01%   |
| Gigabyte B450M     | 40       | 1.82%   |
| HP Compaq          | 32       | 1.46%   |
| Gigabyte B450      | 30       | 1.37%   |
| ASRock B450M       | 23       | 1.05%   |
| Lenovo ThinkCentre | 22       | 1%      |
| MSI MS-7C37        | 21       | 0.96%   |
| MSI MS-7C02        | 21       | 0.96%   |
| Unknown            | 21       | 0.96%   |
| ASRock X570        | 17       | 0.77%   |
| ASRock B450        | 17       | 0.77%   |
| Acer Aspire        | 17       | 0.77%   |
| Dell Precision     | 16       | 0.73%   |
| MSI MS-7B79        | 15       | 0.68%   |
| HP EliteDesk       | 15       | 0.68%   |
| ASUS P8Z77-V       | 15       | 0.68%   |
| MSI MS-7C91        | 14       | 0.64%   |
| MSI MS-7B86        | 13       | 0.59%   |
| Gigabyte Z390      | 13       | 0.59%   |
| Gigabyte B550      | 13       | 0.59%   |
| ASUS M5A97         | 13       | 0.59%   |
| MSI MS-7A38        | 12       | 0.55%   |
| Gigabyte X470      | 12       | 0.55%   |
| ASUS M5A78L-M      | 12       | 0.55%   |
| ASUS P8H61-M       | 11       | 0.5%    |
| ASUS Maximus       | 11       | 0.5%    |
| Gigabyte 970A-DS3P | 10       | 0.46%   |
| MSI MS-7B89        | 9        | 0.41%   |
| HP Pavilion        | 9        | 0.41%   |
| ASRock X470        | 9        | 0.41%   |
| MSI MS-7C94        | 8        | 0.36%   |
| MSI MS-7A34        | 8        | 0.36%   |
| MSI MS-7817        | 8        | 0.36%   |
| MSI MS-7693        | 8        | 0.36%   |
| Gigabyte B550M     | 8        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 371      | 16.91%  |
| 2019    | 281      | 12.81%  |
| 2020    | 233      | 10.62%  |
| 2017    | 192      | 8.75%   |
| 2012    | 190      | 8.66%   |
| 2013    | 157      | 7.16%   |
| 2014    | 134      | 6.11%   |
| 2011    | 121      | 5.52%   |
| 2016    | 96       | 4.38%   |
| 2015    | 95       | 4.33%   |
| 2010    | 80       | 3.65%   |
| 2021    | 68       | 3.1%    |
| 2009    | 68       | 3.1%    |
| 2008    | 42       | 1.91%   |
| 2007    | 37       | 1.69%   |
| 2022    | 12       | 0.55%   |
| 2006    | 12       | 0.55%   |
| 2005    | 4        | 0.18%   |
| Unknown | 1        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2194     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2193     | 99.95%  |
| Enabled  | 1        | 0.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2192     | 99.91%  |
| Yes  | 2        | 0.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 822      | 36.79%  |
| 32.01-64.0  | 434      | 19.43%  |
| 8.01-16.0   | 419      | 18.76%  |
| 4.01-8.0    | 207      | 9.27%   |
| 3.01-4.0    | 159      | 7.12%   |
| 64.01-256.0 | 102      | 4.57%   |
| 24.01-32.0  | 58       | 2.6%    |
| 1.01-2.0    | 28       | 1.25%   |
| 2.01-3.0    | 5        | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 590      | 23.86%  |
| 1.01-2.0    | 580      | 23.45%  |
| 2.01-3.0    | 568      | 22.97%  |
| 3.01-4.0    | 395      | 15.97%  |
| 8.01-16.0   | 206      | 8.33%   |
| 0.51-1.0    | 69       | 2.79%   |
| 16.01-24.0  | 36       | 1.46%   |
| 0.01-0.5    | 11       | 0.44%   |
| 32.01-64.0  | 9        | 0.36%   |
| 24.01-32.0  | 8        | 0.32%   |
| 64.01-256.0 | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 687      | 29.79%  |
| 1      | 545      | 23.63%  |
| 3      | 469      | 20.34%  |
| 4      | 301      | 13.05%  |
| 5      | 171      | 7.42%   |
| 6      | 65       | 2.82%   |
| 7      | 34       | 1.47%   |
| 8      | 11       | 0.48%   |
| 0      | 9        | 0.39%   |
| 9      | 7        | 0.3%    |
| 11     | 4        | 0.17%   |
| 10     | 2        | 0.09%   |
| 12     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1456     | 65.35%  |
| Yes       | 772      | 34.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2169     | 98.86%  |
| No        | 25       | 1.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1202     | 54.1%   |
| Yes       | 1020     | 45.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1341     | 60.19%  |
| Yes       | 887      | 39.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 417      | 18.9%   |
| Germany      | 265      | 12.01%  |
| Russia       | 211      | 9.56%   |
| Brazil       | 130      | 5.89%   |
| Canada       | 93       | 4.22%   |
| France       | 77       | 3.49%   |
| Spain        | 72       | 3.26%   |
| UK           | 70       | 3.17%   |
| Poland       | 66       | 2.99%   |
| Italy        | 65       | 2.95%   |
| Ukraine      | 50       | 2.27%   |
| Netherlands  | 41       | 1.86%   |
| Sweden       | 40       | 1.81%   |
| Australia    | 31       | 1.41%   |
| Finland      | 28       | 1.27%   |
| Austria      | 28       | 1.27%   |
| Belgium      | 25       | 1.13%   |
| Mexico       | 24       | 1.09%   |
| India        | 22       | 1%      |
| Romania      | 21       | 0.95%   |
| Greece       | 19       | 0.86%   |
| Argentina    | 19       | 0.86%   |
| Norway       | 18       | 0.82%   |
| Portugal     | 17       | 0.77%   |
| Bulgaria     | 17       | 0.77%   |
| Hungary      | 15       | 0.68%   |
| Denmark      | 15       | 0.68%   |
| Switzerland  | 14       | 0.63%   |
| South Africa | 13       | 0.59%   |
| China        | 12       | 0.54%   |
| Belarus      | 12       | 0.54%   |
| Israel       | 11       | 0.5%    |
| New Zealand  | 10       | 0.45%   |
| Lithuania    | 10       | 0.45%   |
| Ireland      | 10       | 0.45%   |
| Czechia      | 10       | 0.45%   |
| Turkey       | 9        | 0.41%   |
| Saudi Arabia | 9        | 0.41%   |
| Bangladesh   | 9        | 0.41%   |
| Chile        | 8        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 50       | 2.16%   |
| St Petersburg     | 19       | 0.82%   |
| Warsaw            | 17       | 0.73%   |
| Kyiv              | 16       | 0.69%   |
| Berlin            | 16       | 0.69%   |
| Vienna            | 15       | 0.65%   |
| Toronto           | 14       | 0.6%    |
| Madrid            | 14       | 0.6%    |
| Athens            | 13       | 0.56%   |
| Sao Paulo         | 12       | 0.52%   |
| Helsinki          | 11       | 0.47%   |
| Stockholm         | 10       | 0.43%   |
| Rio de Janeiro    | 10       | 0.43%   |
| Paris             | 10       | 0.43%   |
| Amsterdam         | 10       | 0.43%   |
| Rome              | 9        | 0.39%   |
| Krakow            | 9        | 0.39%   |
| Hamburg           | 9        | 0.39%   |
| Frankfurt am Main | 9        | 0.39%   |
| Sydney            | 8        | 0.35%   |
| Stuttgart         | 8        | 0.35%   |
| Sofia             | 8        | 0.35%   |
| Portland          | 8        | 0.35%   |
| Milan             | 8        | 0.35%   |
| Miami             | 8        | 0.35%   |
| Copenhagen        | 8        | 0.35%   |
| Bucharest         | 8        | 0.35%   |
| Barcelona         | 8        | 0.35%   |
| Austin            | 8        | 0.35%   |
| Omsk              | 7        | 0.3%    |
| Montreal          | 7        | 0.3%    |
| Minsk             | 7        | 0.3%    |
| Melbourne         | 7        | 0.3%    |
| Indianapolis      | 7        | 0.3%    |
| Dallas            | 7        | 0.3%    |
| Yekaterinburg     | 6        | 0.26%   |
| Vilnius           | 6        | 0.26%   |
| Riyadh            | 6        | 0.26%   |
| Oslo              | 6        | 0.26%   |
| New York          | 6        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 870      | 1444   | 18.01%  |
| Seagate                   | 861      | 1375   | 17.83%  |
| Samsung Electronics       | 808      | 1387   | 16.73%  |
| Kingston                  | 311      | 435    | 6.44%   |
| Toshiba                   | 272      | 349    | 5.63%   |
| Crucial                   | 254      | 387    | 5.26%   |
| SanDisk                   | 231      | 298    | 4.78%   |
| Hitachi                   | 125      | 180    | 2.59%   |
| Intel                     | 95       | 130    | 1.97%   |
| Phison                    | 82       | 110    | 1.7%    |
| A-DATA Technology         | 75       | 101    | 1.55%   |
| HGST                      | 55       | 90     | 1.14%   |
| China                     | 40       | 59     | 0.83%   |
| PNY                       | 38       | 55     | 0.79%   |
| Silicon Motion            | 37       | 49     | 0.77%   |
| OCZ                       | 37       | 46     | 0.77%   |
| Unknown                   | 34       | 54     | 0.7%    |
| SPCC                      | 33       | 40     | 0.68%   |
| XPG                       | 32       | 36     | 0.66%   |
| Intenso                   | 31       | 46     | 0.64%   |
| Patriot                   | 29       | 35     | 0.6%    |
| Micron/Crucial Technology | 28       | 35     | 0.58%   |
| SK hynix                  | 27       | 31     | 0.56%   |
| Corsair                   | 26       | 36     | 0.54%   |
| Transcend                 | 21       | 21     | 0.43%   |
| Micron Technology         | 21       | 25     | 0.43%   |
| Plextor                   | 19       | 22     | 0.39%   |
| Team                      | 18       | 23     | 0.37%   |
| Lexar                     | 18       | 20     | 0.37%   |
| JMicron Technology        | 16       | 22     | 0.33%   |
| Goodram                   | 16       | 18     | 0.33%   |
| Realtek Semiconductor     | 15       | 19     | 0.31%   |
| Apacer                    | 14       | 16     | 0.29%   |
| Maxtor                    | 12       | 14     | 0.25%   |
| KingDian                  | 10       | 10     | 0.21%   |
| Hewlett-Packard           | 9        | 12     | 0.19%   |
| Gigabyte Technology       | 9        | 17     | 0.19%   |
| ASMT                      | 9        | 16     | 0.19%   |
| SABRENT                   | 8        | 8      | 0.17%   |
| Apple                     | 8        | 11     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 79       | 1.37%   |
| Samsung SSD 860 EVO 500GB        | 74       | 1.29%   |
| Seagate ST1000DM010-2EP102 1TB   | 71       | 1.24%   |
| Seagate ST2000DM008-2FR102 2TB   | 63       | 1.1%    |
| Samsung NVMe SSD Drive 500GB     | 63       | 1.1%    |
| Samsung SSD 850 EVO 500GB        | 58       | 1.01%   |
| Samsung SSD 850 EVO 250GB        | 57       | 0.99%   |
| Kingston SA400S37120G 120GB SSD  | 52       | 0.9%    |
| Toshiba DT01ACA100 1TB           | 50       | 0.87%   |
| Samsung NVMe SSD Drive 1TB       | 49       | 0.85%   |
| WDC WD10EZEX-08WN4A0 1TB         | 48       | 0.84%   |
| Samsung SSD 860 EVO 1TB          | 46       | 0.8%    |
| Crucial CT500MX500SSD1 500GB     | 42       | 0.73%   |
| Seagate ST2000DM006-2DM164 2TB   | 38       | 0.66%   |
| Seagate ST1000DM003-1ER162 1TB   | 38       | 0.66%   |
| Seagate ST500DM002-1BD142 500GB  | 37       | 0.64%   |
| Samsung SSD 860 EVO 250GB        | 37       | 0.64%   |
| WDC WD10EZEX-00BN5A0 1TB         | 35       | 0.61%   |
| Kingston SA400S37480G 480GB SSD  | 35       | 0.61%   |
| Crucial CT240BX500SSD1 240GB     | 34       | 0.59%   |
| Crucial CT1000MX500SSD1 1TB      | 34       | 0.59%   |
| Toshiba HDWD110 1TB              | 32       | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB   | 32       | 0.56%   |
| Seagate ST2000DM001-1ER164 2TB   | 31       | 0.54%   |
| SanDisk NVMe SSD Drive 500GB     | 31       | 0.54%   |
| Kingston SV300S37A120G 120GB SSD | 31       | 0.54%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 27       | 0.47%   |
| Seagate ST3500418AS 500GB        | 27       | 0.47%   |
| Toshiba DT01ACA050 500GB         | 25       | 0.44%   |
| Seagate ST2000DM001-1CH164 2TB   | 25       | 0.44%   |
| Seagate Expansion 2TB            | 25       | 0.44%   |
| Toshiba DT01ACA200 2TB           | 24       | 0.42%   |
| Seagate ST4000DM004-2CV104 4TB   | 24       | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB   | 24       | 0.42%   |
| Samsung NVMe SSD Drive 250GB     | 23       | 0.4%    |
| Samsung SSD 840 EVO 250GB        | 22       | 0.38%   |
| Phison NVMe SSD Drive 1TB        | 22       | 0.38%   |
| Seagate ST31000524AS 1TB         | 21       | 0.37%   |
| SanDisk NVMe SSD Drive 1TB       | 21       | 0.37%   |
| Samsung SSD 970 EVO 500GB        | 21       | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 845      | 1345   | 37.62%  |
| WDC                 | 775      | 1239   | 34.51%  |
| Toshiba             | 242      | 306    | 10.77%  |
| Samsung Electronics | 129      | 195    | 5.74%   |
| Hitachi             | 125      | 180    | 5.57%   |
| HGST                | 54       | 89     | 2.4%    |
| Unknown             | 16       | 23     | 0.71%   |
| Maxtor              | 12       | 14     | 0.53%   |
| SABRENT             | 8        | 8      | 0.36%   |
| Fujitsu             | 6        | 6      | 0.27%   |
| Apple               | 5        | 8      | 0.22%   |
| USB3.0              | 4        | 4      | 0.18%   |
| Intenso             | 4        | 7      | 0.18%   |
| HGST HTS            | 3        | 3      | 0.13%   |
| ASMT                | 3        | 6      | 0.13%   |
| ASMedia             | 3        | 3      | 0.13%   |
| USB                 | 2        | 2      | 0.09%   |
| Maxone              | 2        | 2      | 0.09%   |
| JMicron Technology  | 2        | 4      | 0.09%   |
| Hewlett-Packard     | 2        | 2      | 0.09%   |
| SATAFIRM            | 1        | 1      | 0.04%   |
| MaxDigital          | 1        | 1      | 0.04%   |
| Lenovo              | 1        | 1      | 0.04%   |
| IBM/Hitachi         | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 483      | 733    | 26.55%  |
| Kingston            | 275      | 374    | 15.12%  |
| Crucial             | 227      | 351    | 12.48%  |
| SanDisk             | 151      | 198    | 8.3%    |
| WDC                 | 113      | 159    | 6.21%   |
| A-DATA Technology   | 61       | 82     | 3.35%   |
| Intel               | 49       | 66     | 2.69%   |
| China               | 39       | 58     | 2.14%   |
| OCZ                 | 37       | 46     | 2.03%   |
| PNY                 | 33       | 50     | 1.81%   |
| SPCC                | 27       | 34     | 1.48%   |
| Patriot             | 27       | 33     | 1.48%   |
| Toshiba             | 22       | 32     | 1.21%   |
| Intenso             | 20       | 30     | 1.1%    |
| Lexar               | 18       | 20     | 0.99%   |
| Corsair             | 18       | 26     | 0.99%   |
| Plextor             | 17       | 20     | 0.93%   |
| Transcend           | 16       | 16     | 0.88%   |
| GOODRAM             | 15       | 17     | 0.82%   |
| Team                | 14       | 19     | 0.77%   |
| Apacer              | 14       | 16     | 0.77%   |
| Micron Technology   | 13       | 14     | 0.71%   |
| KingDian            | 10       | 10     | 0.55%   |
| SK hynix            | 9        | 10     | 0.49%   |
| Seagate             | 8        | 11     | 0.44%   |
| Gigabyte Technology | 7        | 10     | 0.38%   |
| Leven               | 6        | 6      | 0.33%   |
| ASMT                | 6        | 10     | 0.33%   |
| KingSpec            | 5        | 6      | 0.27%   |
| Mushkin             | 4        | 4      | 0.22%   |
| LITEONIT            | 4        | 5      | 0.22%   |
| LITEON              | 4        | 4      | 0.22%   |
| Hoodisk             | 4        | 4      | 0.22%   |
| NGFF                | 3        | 3      | 0.16%   |
| Kingmax             | 3        | 4      | 0.16%   |
| Apple               | 3        | 3      | 0.16%   |
| Verbatim            | 2        | 2      | 0.11%   |
| TO Exter            | 2        | 2      | 0.11%   |
| Smartbuy            | 2        | 2      | 0.11%   |
| Pioneer             | 2        | 2      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1621     | 3450   | 41.84%  |
| SSD     | 1411     | 2547   | 36.42%  |
| NVMe    | 764      | 1181   | 19.72%  |
| Unknown | 73       | 97     | 1.88%   |
| MMC     | 5        | 5      | 0.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2044     | 5806   | 68.16%  |
| NVMe | 756      | 1169   | 25.21%  |
| SAS  | 194      | 300    | 6.47%   |
| MMC  | 5        | 5      | 0.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1535     | 2923   | 44.19%  |
| 0.51-1.0   | 1072     | 1740   | 30.86%  |
| 1.01-2.0   | 490      | 736    | 14.1%   |
| 3.01-4.0   | 153      | 235    | 4.4%    |
| 2.01-3.0   | 110      | 170    | 3.17%   |
| 4.01-10.0  | 101      | 170    | 2.91%   |
| 10.01-20.0 | 13       | 23     | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 410      | 17.54%  |
| 1001-2000      | 391      | 16.72%  |
| 251-500        | 387      | 16.55%  |
| 501-1000       | 385      | 16.47%  |
| More than 3000 | 327      | 13.99%  |
| 2001-3000      | 203      | 8.68%   |
| 51-100         | 86       | 3.68%   |
| Unknown        | 79       | 3.38%   |
| 1-20           | 37       | 1.58%   |
| 21-50          | 33       | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 372      | 15.37%  |
| 1-20           | 364      | 15.04%  |
| 501-1000       | 310      | 12.81%  |
| 21-50          | 290      | 11.98%  |
| 251-500        | 276      | 11.4%   |
| 51-100         | 258      | 10.66%  |
| 1001-2000      | 237      | 9.79%   |
| More than 3000 | 139      | 5.74%   |
| 2001-3000      | 94       | 3.88%   |
| Unknown        | 79       | 3.26%   |
| 0              | 1        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7        | 9      | 2.35%   |
| WDC WD5000AAKX-001CA0 500GB           | 5        | 7      | 1.68%   |
| WDC WD10EARS-00Y5B1 1TB               | 5        | 5      | 1.68%   |
| Samsung Electronics HD103SJ 1TB       | 5        | 5      | 1.68%   |
| Hitachi HDS721010CLA332 1TB           | 5        | 5      | 1.68%   |
| Seagate ST3500413AS 500GB             | 4        | 5      | 1.34%   |
| Seagate ST1000DX001-1CM162 1TB        | 4        | 6      | 1.34%   |
| Samsung Electronics SSD 960 EVO 250GB | 4        | 5      | 1.34%   |
| Samsung Electronics HD103UJ 1TB       | 4        | 6      | 1.34%   |
| WDC WD15EARS-00MVWB0 1TB              | 3        | 3      | 1.01%   |
| WDC WD10EZEX-00RKKA0 1TB              | 3        | 3      | 1.01%   |
| WDC WD10EZEX-00BN5A0 1TB              | 3        | 3      | 1.01%   |
| WDC WD10EARX-00N0YB0 1TB              | 3        | 4      | 1.01%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 3        | 3      | 1.01%   |
| Toshiba MQ01ABD050 500GB              | 3        | 3      | 1.01%   |
| Seagate ST4000DM000-1F2168 4TB        | 3        | 6      | 1.01%   |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3        | 3      | 1.01%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 1.01%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2        | 2      | 0.67%   |
| WDC WD5000AAKX-003CA0 500GB           | 2        | 2      | 0.67%   |
| WDC WD5000AACS-00G8B1 500GB           | 2        | 2      | 0.67%   |
| WDC WD40EFRX-68WT0N0 4TB              | 2        | 3      | 0.67%   |
| WDC WD20EARX-00PASB0 2TB              | 2        | 2      | 0.67%   |
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 0.67%   |
| Seagate ST3250318AS 250GB             | 2        | 2      | 0.67%   |
| Seagate ST3250310AS 250GB             | 2        | 2      | 0.67%   |
| Seagate ST31000524AS 1TB              | 2        | 4      | 0.67%   |
| Seagate ST31000340NS 1TB              | 2        | 3      | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 0.67%   |
| Seagate ST2000DM001-1ER164 2TB        | 2        | 7      | 0.67%   |
| Seagate ST1000DX001-1NS162 1TB        | 2        | 3      | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB        | 2        | 2      | 0.67%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 3      | 0.67%   |
| SanDisk SSD PLUS 240GB                | 2        | 2      | 0.67%   |
| Samsung Electronics HD501LJ 500GB     | 2        | 2      | 0.67%   |
| Samsung Electronics HD322HJ 320GB     | 2        | 2      | 0.67%   |
| Kingston SA400S37480G 480GB SSD       | 2        | 2      | 0.67%   |
| Kingston SA400S37240G 240GB SSD       | 2        | 2      | 0.67%   |
| Kingston SA400S37120G 120GB SSD       | 2        | 2      | 0.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 93       | 106    | 32.52%  |
| Seagate             | 80       | 114    | 27.97%  |
| Samsung Electronics | 24       | 30     | 8.39%   |
| Hitachi             | 19       | 21     | 6.64%   |
| Kingston            | 11       | 11     | 3.85%   |
| Toshiba             | 10       | 13     | 3.5%    |
| Intel               | 9        | 10     | 3.15%   |
| SanDisk             | 7        | 10     | 2.45%   |
| HGST                | 7        | 7      | 2.45%   |
| Crucial             | 6        | 6      | 2.1%    |
| A-DATA Technology   | 4        | 4      | 1.4%    |
| Apacer              | 2        | 2      | 0.7%    |
| Transcend           | 1        | 1      | 0.35%   |
| SPCC                | 1        | 1      | 0.35%   |
| SK hynix            | 1        | 2      | 0.35%   |
| Phison              | 1        | 2      | 0.35%   |
| Patriot             | 1        | 1      | 0.35%   |
| OCZ                 | 1        | 1      | 0.35%   |
| Maxtor              | 1        | 1      | 0.35%   |
| MaxDigital          | 1        | 1      | 0.35%   |
| Intenso             | 1        | 4      | 0.35%   |
| Hewlett-Packard     | 1        | 1      | 0.35%   |
| Fujitsu             | 1        | 1      | 0.35%   |
| Drevo               | 1        | 1      | 0.35%   |
| Corsair             | 1        | 5      | 0.35%   |
| ASMT                | 1        | 5      | 0.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 92       | 105    | 40.35%  |
| Seagate             | 79       | 111    | 34.65%  |
| Hitachi             | 19       | 21     | 8.33%   |
| Samsung Electronics | 18       | 23     | 7.89%   |
| Toshiba             | 10       | 13     | 4.39%   |
| HGST                | 7        | 7      | 3.07%   |
| Maxtor              | 1        | 1      | 0.44%   |
| MaxDigital          | 1        | 1      | 0.44%   |
| Fujitsu             | 1        | 1      | 0.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 210      | 283    | 78.95%  |
| SSD  | 48       | 68     | 18.05%  |
| NVMe | 8        | 10     | 3.01%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB      | 1        | 1      | 8.33%   |
| WDC WD3200BPVT-24ZEST0 320GB      | 1        | 1      | 8.33%   |
| WDC WD1600AAJS-65WAA0 160GB       | 1        | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB          | 1        | 1      | 8.33%   |
| Toshiba MK1059GSM 1TB             | 1        | 1      | 8.33%   |
| Seagate ST9640320AS 640GB         | 1        | 1      | 8.33%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 8.33%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 8.33%   |
| Seagate ST31000524AS 1TB          | 1        | 2      | 8.33%   |
| Samsung Electronics HD321HJ 320GB | 1        | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 8.33%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 33.33%  |
| WDC                 | 3        | 3      | 25%     |
| Toshiba             | 2        | 2      | 16.67%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1423     | 4466   | 55.61%  |
| Works    | 872      | 2440   | 34.08%  |
| Malfunc  | 252      | 361    | 9.85%   |
| Failed   | 12       | 13     | 0.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1173     | 35.13%  |
| AMD                              | 1016     | 30.43%  |
| Samsung Electronics              | 329      | 9.85%   |
| ASMedia Technology               | 141      | 4.22%   |
| SanDisk                          | 112      | 3.35%   |
| Phison Electronics               | 104      | 3.11%   |
| Marvell Technology Group         | 65       | 1.95%   |
| Micron/Crucial Technology        | 57       | 1.71%   |
| Silicon Motion                   | 52       | 1.56%   |
| JMicron Technology               | 52       | 1.56%   |
| Kingston Technology Company      | 47       | 1.41%   |
| ADATA Technology                 | 38       | 1.14%   |
| Nvidia                           | 32       | 0.96%   |
| Realtek Semiconductor            | 26       | 0.78%   |
| SK hynix                         | 18       | 0.54%   |
| Toshiba America Info Systems     | 8        | 0.24%   |
| Micron Technology                | 8        | 0.24%   |
| LSI Logic / Symbios Logic        | 8        | 0.24%   |
| KIOXIA                           | 7        | 0.21%   |
| VIA Technologies                 | 6        | 0.18%   |
| Seagate Technology               | 6        | 0.18%   |
| Silicon Image                    | 5        | 0.15%   |
| Lite-On Technology               | 5        | 0.15%   |
| Broadcom / LSI                   | 4        | 0.12%   |
| Adaptec                          | 4        | 0.12%   |
| Integrated Technology Express    | 3        | 0.09%   |
| Shenzhen Longsys Electronics     | 2        | 0.06%   |
| Unknown                          | 1        | 0.03%   |
| Union Memory (Shenzhen)          | 1        | 0.03%   |
| Transcend                        | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| PMC-Sierra                       | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.03%   |
| Lenovo                           | 1        | 0.03%   |
| HighPoint Technologies           | 1        | 0.03%   |
| Dell                             | 1        | 0.03%   |
| Biwin Storage Technology         | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 694      | 16.54%  |
| AMD 400 Series Chipset SATA Controller                                                  | 307      | 7.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 209      | 4.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 140      | 3.34%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 139      | 3.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 116      | 2.76%   |
| AMD 500 Series Chipset SATA Controller                                                  | 115      | 2.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 99       | 2.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 98       | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 97       | 2.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 96       | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 89       | 2.12%   |
| AMD 300 Series Chipset SATA Controller                                                  | 82       | 1.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 75       | 1.79%   |
| Intel SATA Controller [RAID mode]                                                       | 70       | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 64       | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 59       | 1.41%   |
| Phison E12 NVMe Controller                                                              | 53       | 1.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 50       | 1.19%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 48       | 1.14%   |
| AMD FCH SATA Controller D                                                               | 45       | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 41       | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 41       | 0.98%   |
| AMD X370 Series Chipset SATA Controller                                                 | 40       | 0.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 39       | 0.93%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 38       | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 37       | 0.88%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 34       | 0.81%   |
| Kingston Company A2000 NVMe SSD                                                         | 34       | 0.81%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 33       | 0.79%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 32       | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 30       | 0.71%   |
| Intel SSD 660P Series                                                                   | 29       | 0.69%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 29       | 0.69%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 28       | 0.67%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 26       | 0.62%   |
| Samsung NVMe SSD Controller 980                                                         | 25       | 0.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 25       | 0.6%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 24       | 0.57%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 23       | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1944     | 61.19%  |
| NVMe | 761      | 23.95%  |
| IDE  | 341      | 10.73%  |
| RAID | 112      | 3.53%   |
| SAS  | 16       | 0.5%    |
| SCSI | 3        | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1148     | 52.32%  |
| AMD    | 1046     | 47.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 112      | 5.08%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 71       | 3.22%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 60       | 2.72%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 55       | 2.5%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 44       | 2%      |
| AMD Ryzen 7 2700 Eight-Core Processor       | 27       | 1.23%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 26       | 1.18%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 26       | 1.18%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 25       | 1.13%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 24       | 1.09%   |
| AMD FX-8350 Eight-Core Processor            | 23       | 1.04%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 21       | 0.95%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 21       | 0.95%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 21       | 0.95%   |
| AMD FX-6300 Six-Core Processor              | 21       | 0.95%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 20       | 0.91%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 20       | 0.91%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 20       | 0.91%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 20       | 0.91%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 19       | 0.86%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 19       | 0.86%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 19       | 0.86%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 19       | 0.86%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 19       | 0.86%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 18       | 0.82%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 17       | 0.77%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 17       | 0.77%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 17       | 0.77%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 17       | 0.77%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 16       | 0.73%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 16       | 0.73%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 15       | 0.68%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 15       | 0.68%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 15       | 0.68%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 15       | 0.68%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 14       | 0.64%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 14       | 0.64%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 14       | 0.64%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 14       | 0.64%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 14       | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 384      | 17.47%  |
| AMD Ryzen 5             | 348      | 15.83%  |
| Intel Core i7           | 307      | 13.97%  |
| AMD Ryzen 7             | 252      | 11.46%  |
| Intel Core i3           | 122      | 5.55%   |
| Intel Xeon              | 106      | 4.82%   |
| AMD FX                  | 99       | 4.5%    |
| AMD Ryzen 9             | 97       | 4.41%   |
| AMD Ryzen 3             | 43       | 1.96%   |
| Intel Core 2 Duo        | 40       | 1.82%   |
| Intel Celeron           | 33       | 1.5%    |
| Intel Pentium           | 30       | 1.36%   |
| Other                   | 29       | 1.32%   |
| AMD Ryzen Threadripper  | 26       | 1.18%   |
| AMD Phenom II X4        | 25       | 1.14%   |
| Intel Pentium Dual-Core | 21       | 0.96%   |
| Intel Core 2 Quad       | 21       | 0.96%   |
| Intel Core i9           | 18       | 0.82%   |
| AMD Athlon II X2        | 18       | 0.82%   |
| AMD A10                 | 17       | 0.77%   |
| AMD A8                  | 16       | 0.73%   |
| AMD A4                  | 14       | 0.64%   |
| AMD Phenom II X6        | 11       | 0.5%    |
| AMD Athlon 64 X2        | 11       | 0.5%    |
| Intel Core 2            | 10       | 0.45%   |
| AMD Athlon              | 10       | 0.45%   |
| AMD Ryzen 5 PRO         | 8        | 0.36%   |
| AMD Athlon X4           | 8        | 0.36%   |
| AMD Athlon II X4        | 8        | 0.36%   |
| Intel Atom              | 7        | 0.32%   |
| AMD Phenom              | 7        | 0.32%   |
| Intel Pentium Gold      | 6        | 0.27%   |
| Intel Pentium Dual      | 6        | 0.27%   |
| Intel Genuine           | 5        | 0.23%   |
| AMD Ryzen 7 PRO         | 5        | 0.23%   |
| Intel Pentium D         | 4        | 0.18%   |
| AMD Athlon II X3        | 4        | 0.18%   |
| AMD Sempron             | 3        | 0.14%   |
| AMD Phenom II X2        | 3        | 0.14%   |
| AMD E1                  | 3        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 792      | 36.02%  |
| 6       | 496      | 22.56%  |
| 2       | 352      | 16.01%  |
| 8       | 330      | 15.01%  |
| 12      | 89       | 4.05%   |
| 16      | 52       | 2.36%   |
| 3       | 39       | 1.77%   |
| 1       | 24       | 1.09%   |
| 10      | 14       | 0.64%   |
| 24      | 4        | 0.18%   |
| 32      | 3        | 0.14%   |
| Unknown | 2        | 0.09%   |
| 20      | 1        | 0.05%   |
| 14      | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2176     | 99.18%  |
| 2      | 18       | 0.82%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1455     | 66.14%  |
| 1       | 743      | 33.77%  |
| Unknown | 2        | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2166     | 98.5%   |
| Unknown        | 33       | 1.5%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1098     | 48.28%  |
| 0x08701021 | 123      | 5.41%   |
| 0x0800820d | 97       | 4.27%   |
| 0x306c3    | 95       | 4.18%   |
| 0x08701013 | 73       | 3.21%   |
| 0x306a9    | 64       | 2.81%   |
| 0x206a7    | 58       | 2.55%   |
| 0x906ea    | 55       | 2.42%   |
| 0x506e3    | 49       | 2.15%   |
| 0x06000852 | 43       | 1.89%   |
| 0x1067a    | 34       | 1.5%    |
| 0x08001138 | 28       | 1.23%   |
| 0x906e9    | 25       | 1.1%    |
| 0x306f2    | 22       | 0.97%   |
| 0x0a201009 | 21       | 0.92%   |
| 0x010000c8 | 21       | 0.92%   |
| 0x08108109 | 20       | 0.88%   |
| 0x08001137 | 19       | 0.84%   |
| 0x206d7    | 17       | 0.75%   |
| 0x0a201016 | 16       | 0.7%    |
| 0x06003106 | 13       | 0.57%   |
| 0xa0655    | 12       | 0.53%   |
| 0x106e5    | 12       | 0.53%   |
| 0x08101016 | 12       | 0.53%   |
| 0x06001119 | 12       | 0.53%   |
| 0x906ed    | 9        | 0.4%    |
| 0x08001129 | 9        | 0.4%    |
| 0x906ec    | 8        | 0.35%   |
| 0x906eb    | 8        | 0.35%   |
| 0x6fd      | 8        | 0.35%   |
| 0x0a50000c | 8        | 0.35%   |
| 0x08600106 | 8        | 0.35%   |
| 0xa0653    | 7        | 0.31%   |
| 0x10676    | 7        | 0.31%   |
| 0x010000dc | 7        | 0.31%   |
| 0xa0671    | 6        | 0.26%   |
| 0x206c2    | 6        | 0.26%   |
| 0x0810100b | 6        | 0.26%   |
| 0x90672    | 5        | 0.22%   |
| 0x6f6      | 5        | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 320      | 14.55%  |
| Haswell          | 237      | 10.77%  |
| KabyLake         | 226      | 10.27%  |
| Zen+             | 216      | 9.82%   |
| Zen              | 151      | 6.86%   |
| SandyBridge      | 144      | 6.55%   |
| IvyBridge        | 139      | 6.32%   |
| Piledriver       | 108      | 4.91%   |
| Zen 3            | 106      | 4.82%   |
| Skylake          | 102      | 4.64%   |
| Penryn           | 85       | 3.86%   |
| K10              | 75       | 3.41%   |
| CometLake        | 48       | 2.18%   |
| Core             | 33       | 1.5%    |
| Nehalem          | 32       | 1.45%   |
| Westmere         | 26       | 1.18%   |
| Steamroller      | 22       | 1%      |
| Unknown          | 21       | 0.95%   |
| Bulldozer        | 17       | 0.77%   |
| K8 Hammer        | 14       | 0.64%   |
| Broadwell        | 14       | 0.64%   |
| Excavator        | 8        | 0.36%   |
| Goldmont plus    | 7        | 0.32%   |
| Silvermont       | 6        | 0.27%   |
| NetBurst         | 6        | 0.27%   |
| Goldmont         | 6        | 0.27%   |
| Bonnell          | 6        | 0.27%   |
| Alderlake Hybrid | 5        | 0.23%   |
| K10 Llano        | 4        | 0.18%   |
| Jaguar           | 4        | 0.18%   |
| Icelake          | 4        | 0.18%   |
| Bobcat           | 4        | 0.18%   |
| Puma             | 2        | 0.09%   |
| Tremont          | 1        | 0.05%   |
| TigerLake        | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1118     | 47.41%  |
| AMD                        | 824      | 34.94%  |
| Intel                      | 414      | 17.56%  |
| Matrox Electronics Systems | 1        | 0.04%   |
| ATI Technologies           | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 215      | 8.88%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 85       | 3.51%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 78       | 3.22%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 76       | 3.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 76       | 3.14%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 56       | 2.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 51       | 2.11%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 50       | 2.06%   |
| Nvidia GK208B [GeForce GT 710]                                              | 46       | 1.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 44       | 1.82%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 41       | 1.69%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 39       | 1.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 36       | 1.49%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 36       | 1.49%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 33       | 1.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 32       | 1.32%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 30       | 1.24%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 30       | 1.24%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 28       | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 27       | 1.11%   |
| Intel HD Graphics 530                                                       | 26       | 1.07%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 25       | 1.03%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 25       | 1.03%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 24       | 0.99%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 23       | 0.95%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 23       | 0.95%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 22       | 0.91%   |
| Intel HD Graphics 630                                                       | 20       | 0.83%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 19       | 0.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 19       | 0.78%   |
| AMD Cezanne                                                                 | 19       | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 18       | 0.74%   |
| Nvidia GK208B [GeForce GT 730]                                              | 18       | 0.74%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 18       | 0.74%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 18       | 0.74%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 17       | 0.7%    |
| Nvidia GF119 [GeForce GT 610]                                               | 17       | 0.7%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 17       | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                  | 16       | 0.66%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 16       | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 1028     | 46.14%  |
| 1 x AMD            | 762      | 34.2%   |
| 1 x Intel          | 307      | 13.78%  |
| Intel + Nvidia     | 37       | 1.66%   |
| AMD + Nvidia       | 29       | 1.3%    |
| 2 x AMD            | 28       | 1.26%   |
| 2 x Nvidia         | 24       | 1.08%   |
| Intel + AMD        | 10       | 0.45%   |
| 1 x Matrox         | 1        | 0.04%   |
| Intel + 2 x Nvidia | 1        | 0.04%   |
| Intel + 2 x AMD    | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1302     | 58.57%  |
| Proprietary | 911      | 40.98%  |
| Unknown     | 10       | 0.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 882      | 39.01%  |
| 7.01-8.0   | 350      | 15.48%  |
| 1.01-2.0   | 293      | 12.96%  |
| 3.01-4.0   | 237      | 10.48%  |
| 5.01-6.0   | 162      | 7.16%   |
| 0.51-1.0   | 137      | 6.06%   |
| 8.01-16.0  | 76       | 3.36%   |
| 0.01-0.5   | 75       | 3.32%   |
| 2.01-3.0   | 39       | 1.72%   |
| 16.01-24.0 | 8        | 0.35%   |
| 4.01-5.0   | 2        | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 399      | 15.1%   |
| Goldstar             | 301      | 11.39%  |
| Dell                 | 250      | 9.46%   |
| Acer                 | 212      | 8.02%   |
| Ancor Communications | 166      | 6.28%   |
| AOC                  | 162      | 6.13%   |
| BenQ                 | 157      | 5.94%   |
| Hewlett-Packard      | 120      | 4.54%   |
| Philips              | 114      | 4.31%   |
| LG Electronics       | 84       | 3.18%   |
| ViewSonic            | 61       | 2.31%   |
| ASUSTek Computer     | 55       | 2.08%   |
| Lenovo               | 42       | 1.59%   |
| Unknown              | 38       | 1.44%   |
| Iiyama               | 36       | 1.36%   |
| Sony                 | 24       | 0.91%   |
| Vizio                | 20       | 0.76%   |
| AUS                  | 17       | 0.64%   |
| MSI                  | 16       | 0.61%   |
| Unknown              | 16       | 0.61%   |
| Eizo                 | 15       | 0.57%   |
| NEC Computers        | 14       | 0.53%   |
| Medion               | 12       | 0.45%   |
| Fujitsu Siemens      | 12       | 0.45%   |
| Sceptre Tech         | 11       | 0.42%   |
| Idek Iiyama          | 11       | 0.42%   |
| Gigabyte Technology  | 9        | 0.34%   |
| Vestel Elektronik    | 8        | 0.3%    |
| Sharp                | 8        | 0.3%    |
| Microstep            | 8        | 0.3%    |
| Panasonic            | 7        | 0.26%   |
| HannStar             | 7        | 0.26%   |
| Toshiba              | 6        | 0.23%   |
| Pixio                | 6        | 0.23%   |
| Apple                | 6        | 0.23%   |
| Vestel               | 5        | 0.19%   |
| Plain Tree Systems   | 5        | 0.19%   |
| Packard Bell         | 5        | 0.19%   |
| KTC                  | 5        | 0.19%   |
| HPN                  | 5        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 18       | 0.63%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 17       | 0.59%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 16       | 0.56%   |
| Unknown                                                                | 16       | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 12       | 0.42%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch               | 10       | 0.35%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                       | 10       | 0.35%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 9        | 0.31%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 9        | 0.31%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 8        | 0.28%   |
| Goldstar LG HDR WFHD GSM7715 2560x1080 800x340mm 34.2-inch             | 8        | 0.28%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 8        | 0.28%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                       | 8        | 0.28%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 7        | 0.24%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 7        | 0.24%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 7        | 0.24%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 7        | 0.24%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                      | 7        | 0.24%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 7        | 0.24%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 6        | 0.21%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 6        | 0.21%   |
| Goldstar E2350 GSM5791 1920x1080 510x290mm 23.1-inch                   | 6        | 0.21%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                 | 6        | 0.21%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 6        | 0.21%   |
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch           | 6        | 0.21%   |
| AOC 27B1 AOC2701 1920x1080 598x336mm 27.0-inch                         | 6        | 0.21%   |
| AOC 24G1WG3 AOC2401 1920x1080 521x293mm 23.5-inch                      | 6        | 0.21%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 6        | 0.21%   |
| Ancor Communications VG248 ACI24A4 1920x1080 530x300mm 24.0-inch       | 6        | 0.21%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 6        | 0.21%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 6        | 0.21%   |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch  | 6        | 0.21%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 5        | 0.17%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 5        | 0.17%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                   | 5        | 0.17%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 5        | 0.17%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 5        | 0.17%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 5        | 0.17%   |
| BenQ GL2580 BNQ78E5 1920x1080 544x303mm 24.5-inch                      | 5        | 0.17%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 5        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1136     | 44.24%  |
| 3840x2160 (4K)     | 235      | 9.15%   |
| 2560x1440 (QHD)    | 234      | 9.11%   |
| Unknown            | 137      | 5.33%   |
| 1680x1050 (WSXGA+) | 107      | 4.17%   |
| 1280x1024 (SXGA)   | 104      | 4.05%   |
| 1920x1200 (WUXGA)  | 71       | 2.76%   |
| 1366x768 (WXGA)    | 70       | 2.73%   |
| 3440x1440          | 63       | 2.45%   |
| 1440x900 (WXGA+)   | 63       | 2.45%   |
| 3840x1080          | 61       | 2.38%   |
| 2560x1080          | 60       | 2.34%   |
| 1600x900 (HD+)     | 54       | 2.1%    |
| 1360x768           | 24       | 0.93%   |
| 4480x1440          | 10       | 0.39%   |
| 1280x720 (HD)      | 10       | 0.39%   |
| 5120x1440          | 9        | 0.35%   |
| 1920x540           | 9        | 0.35%   |
| 1024x768 (XGA)     | 9        | 0.35%   |
| 5760x1080          | 8        | 0.31%   |
| 3600x1080          | 6        | 0.23%   |
| 5760x2160          | 5        | 0.19%   |
| 3840x1600          | 5        | 0.19%   |
| 3200x1080          | 5        | 0.19%   |
| 2560x1600          | 5        | 0.19%   |
| 6400x2160          | 4        | 0.16%   |
| 3840x1200          | 4        | 0.16%   |
| 3520x1080          | 4        | 0.16%   |
| 3360x1080          | 3        | 0.12%   |
| 3286x1080          | 3        | 0.12%   |
| 1600x1200          | 3        | 0.12%   |
| 7680x2160          | 2        | 0.08%   |
| 5504x1440          | 2        | 0.08%   |
| 4480x1080          | 2        | 0.08%   |
| 4240x1440          | 2        | 0.08%   |
| 3360x1050          | 2        | 0.08%   |
| 2880x900           | 2        | 0.08%   |
| 2720x1024          | 2        | 0.08%   |
| 2160x1200          | 2        | 0.08%   |
| 2048x1152          | 2        | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 422      | 16.54%  |
| 24      | 379      | 14.86%  |
| 27      | 365      | 14.31%  |
| 23      | 308      | 12.07%  |
| 21      | 265      | 10.39%  |
| 19      | 117      | 4.59%   |
| 34      | 96       | 3.76%   |
| 31      | 95       | 3.72%   |
| 22      | 74       | 2.9%    |
| 18      | 65       | 2.55%   |
| 20      | 59       | 2.31%   |
| 17      | 41       | 1.61%   |
| 84      | 34       | 1.33%   |
| 25      | 20       | 0.78%   |
| 54      | 19       | 0.74%   |
| 72      | 18       | 0.71%   |
| 32      | 18       | 0.71%   |
| 15      | 15       | 0.59%   |
| 49      | 10       | 0.39%   |
| 48      | 10       | 0.39%   |
| 65      | 9        | 0.35%   |
| 40      | 9        | 0.35%   |
| 46      | 8        | 0.31%   |
| 43      | 8        | 0.31%   |
| 28      | 8        | 0.31%   |
| 37      | 7        | 0.27%   |
| 33      | 7        | 0.27%   |
| 26      | 6        | 0.24%   |
| 39      | 5        | 0.2%    |
| 35      | 5        | 0.2%    |
| 14      | 5        | 0.2%    |
| 12      | 5        | 0.2%    |
| 36      | 4        | 0.16%   |
| 64      | 3        | 0.12%   |
| 60      | 3        | 0.12%   |
| 47      | 3        | 0.12%   |
| 42      | 3        | 0.12%   |
| 38      | 3        | 0.12%   |
| 29      | 3        | 0.12%   |
| 16      | 3        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 935      | 38.54%  |
| 401-500     | 501      | 20.65%  |
| Unknown     | 422      | 17.39%  |
| 601-700     | 138      | 5.69%   |
| 701-800     | 124      | 5.11%   |
| 351-400     | 75       | 3.09%   |
| 1001-1500   | 67       | 2.76%   |
| 1501-2000   | 56       | 2.31%   |
| 301-350     | 54       | 2.23%   |
| 801-900     | 30       | 1.24%   |
| 201-300     | 13       | 0.54%   |
| 901-1000    | 11       | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1411     | 61.21%  |
| Unknown | 393      | 17.05%  |
| 16/10   | 229      | 9.93%   |
| 21/9    | 105      | 4.56%   |
| 5/4     | 99       | 4.3%    |
| 4/3     | 27       | 1.17%   |
| 3/2     | 18       | 0.78%   |
| 32/9    | 14       | 0.61%   |
| 6/5     | 5        | 0.22%   |
| 3.20    | 1        | 0.04%   |
| 1.96    | 1        | 0.04%   |
| 1.03    | 1        | 0.04%   |
| 0.80    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 821      | 32.88%  |
| Unknown        | 422      | 16.9%   |
| 301-350        | 367      | 14.7%   |
| 151-200        | 237      | 9.49%   |
| 351-500        | 229      | 9.17%   |
| 251-300        | 136      | 5.45%   |
| More than 1000 | 101      | 4.04%   |
| 141-150        | 85       | 3.4%    |
| 501-1000       | 63       | 2.52%   |
| 101-110        | 17       | 0.68%   |
| 131-140        | 6        | 0.24%   |
| 71-80          | 5        | 0.2%    |
| 81-90          | 2        | 0.08%   |
| 51-60          | 2        | 0.08%   |
| 91-100         | 2        | 0.08%   |
| 121-130        | 1        | 0.04%   |
| 111-120        | 1        | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1279     | 54.03%  |
| 101-120 | 449      | 18.97%  |
| Unknown | 422      | 17.83%  |
| 1-50    | 81       | 3.42%   |
| 121-160 | 79       | 3.34%   |
| 161-240 | 57       | 2.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1623     | 72.33%  |
| 2     | 510      | 22.73%  |
| 3     | 75       | 3.34%   |
| 0     | 31       | 1.38%   |
| 4     | 5        | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1341     | 42.91%  |
| Intel                                  | 981      | 31.39%  |
| Qualcomm Atheros                       | 168      | 5.38%   |
| Broadcom                               | 87       | 2.78%   |
| Ralink Technology                      | 83       | 2.66%   |
| TP-Link                                | 75       | 2.4%    |
| Microsoft                              | 41       | 1.31%   |
| Nvidia                                 | 28       | 0.9%    |
| Aquantia                               | 28       | 0.9%    |
| Ralink                                 | 23       | 0.74%   |
| Qualcomm Atheros Communications        | 23       | 0.74%   |
| Xiaomi                                 | 18       | 0.58%   |
| Samsung Electronics                    | 15       | 0.48%   |
| Marvell Technology Group               | 15       | 0.48%   |
| ASUSTek Computer                       | 15       | 0.48%   |
| NetGear                                | 13       | 0.42%   |
| MediaTek                               | 13       | 0.42%   |
| D-Link                                 | 13       | 0.42%   |
| Huawei Technologies                    | 12       | 0.38%   |
| Broadcom Limited                       | 12       | 0.38%   |
| Linksys                                | 10       | 0.32%   |
| D-Link System                          | 8        | 0.26%   |
| Microchip Technology                   | 7        | 0.22%   |
| Edimax Technology                      | 7        | 0.22%   |
| Mellanox Technologies                  | 5        | 0.16%   |
| ASIX Electronics                       | 5        | 0.16%   |
| ZyXEL Communications                   | 4        | 0.13%   |
| Motorola PCS                           | 4        | 0.13%   |
| InterBiometrics                        | 4        | 0.13%   |
| T & A Mobile Phones                    | 3        | 0.1%    |
| Sony Ericsson Mobile Communications AB | 3        | 0.1%    |
| SEGGER                                 | 3        | 0.1%    |
| Qualcomm                               | 3        | 0.1%    |
| JMicron Technology                     | 3        | 0.1%    |
| IMC Networks                           | 3        | 0.1%    |
| Google                                 | 3        | 0.1%    |
| Belkin Components                      | 3        | 0.1%    |
| Tenda                                  | 2        | 0.06%   |
| OPPO Electronics                       | 2        | 0.06%   |
| OnePlus                                | 2        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1110     | 30.91%  |
| Intel I211 Gigabit Network Connection                             | 258      | 7.18%   |
| Intel Wi-Fi 6 AX200                                               | 166      | 4.62%   |
| Intel Ethernet Connection (2) I219-V                              | 114      | 3.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 112      | 3.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 66       | 1.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 61       | 1.7%    |
| Intel Ethernet Controller I225-V                                  | 53       | 1.48%   |
| Intel Ethernet Connection (7) I219-V                              | 50       | 1.39%   |
| Intel 82579V Gigabit Network Connection                           | 46       | 1.28%   |
| Intel Wireless-AC 9260                                            | 45       | 1.25%   |
| Intel Ethernet Connection (2) I218-V                              | 41       | 1.14%   |
| Intel Ethernet Connection I217-LM                                 | 34       | 0.95%   |
| Intel Ethernet Connection I217-V                                  | 32       | 0.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29       | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 29       | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 28       | 0.78%   |
| Ralink MT7601U Wireless Adapter                                   | 27       | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 26       | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 26       | 0.72%   |
| Qualcomm Atheros AR9271 802.11n                                   | 23       | 0.64%   |
| Microsoft Xbox 360 Wireless Adapter                               | 23       | 0.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 22       | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 22       | 0.61%   |
| Realtek 802.11ac NIC                                              | 21       | 0.58%   |
| Intel Wireless 7265                                               | 21       | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 19       | 0.53%   |
| Intel 82574L Gigabit Network Connection                           | 19       | 0.53%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.5%    |
| Nvidia MCP61 Ethernet                                             | 18       | 0.5%    |
| Intel Wireless 8265 / 8275                                        | 18       | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15       | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15       | 0.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15       | 0.42%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 15       | 0.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 15       | 0.42%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 15       | 0.42%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 15       | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 406      | 36.61%  |
| Realtek Semiconductor                 | 216      | 19.48%  |
| Qualcomm Atheros                      | 87       | 7.84%   |
| Ralink Technology                     | 83       | 7.48%   |
| TP-Link                               | 74       | 6.67%   |
| Broadcom                              | 55       | 4.96%   |
| Microsoft                             | 41       | 3.7%    |
| Ralink                                | 23       | 2.07%   |
| Qualcomm Atheros Communications       | 23       | 2.07%   |
| ASUSTek Computer                      | 15       | 1.35%   |
| NetGear                               | 13       | 1.17%   |
| D-Link                                | 13       | 1.17%   |
| Linksys                               | 10       | 0.9%    |
| MediaTek                              | 9        | 0.81%   |
| Edimax Technology                     | 7        | 0.63%   |
| D-Link System                         | 5        | 0.45%   |
| Broadcom Limited                      | 5        | 0.45%   |
| ZyXEL Communications                  | 4        | 0.36%   |
| IMC Networks                          | 3        | 0.27%   |
| Belkin Components                     | 3        | 0.27%   |
| Tenda                                 | 2        | 0.18%   |
| Mercucys                              | 2        | 0.18%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.18%   |
| ZyDAS                                 | 1        | 0.09%   |
| Xiaomi                                | 1        | 0.09%   |
| Wacom                                 | 1        | 0.09%   |
| Senao                                 | 1        | 0.09%   |
| Marvell Technology Group              | 1        | 0.09%   |
| Fujitsu Siemens Computers             | 1        | 0.09%   |
| Encore Electronics                    | 1        | 0.09%   |
| AVM                                   | 1        | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 166      | 14.82%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 61       | 5.45%   |
| Intel Wireless-AC 9260                                         | 45       | 4.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 29       | 2.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 28       | 2.5%    |
| Ralink MT7601U Wireless Adapter                                | 27       | 2.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 26       | 2.32%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 26       | 2.32%   |
| Qualcomm Atheros AR9271 802.11n                                | 23       | 2.05%   |
| Microsoft Xbox 360 Wireless Adapter                            | 23       | 2.05%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 22       | 1.96%   |
| Realtek 802.11ac NIC                                           | 21       | 1.88%   |
| Intel Wireless 7265                                            | 21       | 1.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 19       | 1.7%    |
| Intel Wireless 8265 / 8275                                     | 18       | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15       | 1.34%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 15       | 1.34%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 15       | 1.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 15       | 1.34%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 15       | 1.34%   |
| Ralink RT5370 Wireless Adapter                                 | 13       | 1.16%   |
| Microsoft XBOX ACC                                             | 13       | 1.16%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 12       | 1.07%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 12       | 1.07%   |
| Intel Wireless 3165                                            | 12       | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11       | 0.98%   |
| Intel Wireless 7260                                            | 11       | 0.98%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 9        | 0.8%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 9        | 0.8%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 9        | 0.8%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 8        | 0.71%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 8        | 0.71%   |
| TP-Link 802.11ac NIC                                           | 8        | 0.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 8        | 0.71%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 8        | 0.71%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 8        | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8        | 0.71%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 8        | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8        | 0.71%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 7        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1268     | 53.82%  |
| Intel                                  | 792      | 33.62%  |
| Qualcomm Atheros                       | 95       | 4.03%   |
| Broadcom                               | 34       | 1.44%   |
| Nvidia                                 | 28       | 1.19%   |
| Aquantia                               | 28       | 1.19%   |
| Xiaomi                                 | 17       | 0.72%   |
| Samsung Electronics                    | 15       | 0.64%   |
| Marvell Technology Group               | 14       | 0.59%   |
| Huawei Technologies                    | 10       | 0.42%   |
| Broadcom Limited                       | 7        | 0.3%    |
| Mellanox Technologies                  | 5        | 0.21%   |
| ASIX Electronics                       | 5        | 0.21%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.13%   |
| MediaTek                               | 3        | 0.13%   |
| JMicron Technology                     | 3        | 0.13%   |
| Google                                 | 3        | 0.13%   |
| D-Link System                          | 3        | 0.13%   |
| T & A Mobile Phones                    | 2        | 0.08%   |
| Qualcomm                               | 2        | 0.08%   |
| OPPO Electronics                       | 2        | 0.08%   |
| OnePlus                                | 2        | 0.08%   |
| National Semiconductor                 | 2        | 0.08%   |
| HMD Global                             | 2        | 0.08%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.04%   |
| VIA Technologies                       | 1        | 0.04%   |
| TP-Link                                | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus      | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.04%   |
| NetXen Incorporated                    | 1        | 0.04%   |
| Motorola PCS                           | 1        | 0.04%   |
| LG Electronics                         | 1        | 0.04%   |
| Foxconn / Hon Hai                      | 1        | 0.04%   |
| Apple                                  | 1        | 0.04%   |
| Accton Technology                      | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1110     | 45.59%  |
| Intel I211 Gigabit Network Connection                             | 258      | 10.6%   |
| Intel Ethernet Connection (2) I219-V                              | 114      | 4.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 112      | 4.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 66       | 2.71%   |
| Intel Ethernet Controller I225-V                                  | 53       | 2.18%   |
| Intel Ethernet Connection (7) I219-V                              | 50       | 2.05%   |
| Intel 82579V Gigabit Network Connection                           | 46       | 1.89%   |
| Intel Ethernet Connection (2) I218-V                              | 41       | 1.68%   |
| Intel Ethernet Connection I217-LM                                 | 34       | 1.4%    |
| Intel Ethernet Connection I217-V                                  | 32       | 1.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29       | 1.19%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 22       | 0.9%    |
| Intel 82574L Gigabit Network Connection                           | 19       | 0.78%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.74%   |
| Nvidia MCP61 Ethernet                                             | 18       | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15       | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15       | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14       | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14       | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13       | 0.53%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 11       | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 10       | 0.41%   |
| Intel Ethernet Connection (11) I219-V                             | 10       | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 9        | 0.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 0.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 8        | 0.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 8        | 0.33%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 8        | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 0.29%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 6        | 0.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.25%   |
| Intel Ethernet Connection (2) I218-LM                             | 6        | 0.25%   |
| Huawei LYA-L09                                                    | 6        | 0.25%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 6        | 0.25%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5        | 0.21%   |
| Nvidia MCP77 Ethernet                                             | 5        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2170     | 67.33%  |
| WiFi     | 1019     | 31.62%  |
| Modem    | 27       | 0.84%   |
| Unknown  | 7        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1743     | 76.25%  |
| WiFi     | 543      | 23.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1415     | 63.94%  |
| 2     | 671      | 30.32%  |
| 3     | 97       | 4.38%   |
| 0     | 18       | 0.81%   |
| 5     | 5        | 0.23%   |
| 4     | 5        | 0.23%   |
| 8     | 1        | 0.05%   |
| 7     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1881     | 84.27%  |
| Yes  | 351      | 15.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 382      | 41.52%  |
| Cambridge Silicon Radio         | 263      | 28.59%  |
| ASUSTek Computer                | 84       | 9.13%   |
| Realtek Semiconductor           | 57       | 6.2%    |
| Broadcom                        | 50       | 5.43%   |
| Qualcomm Atheros Communications | 15       | 1.63%   |
| Apple                           | 11       | 1.2%    |
| IMC Networks                    | 9        | 0.98%   |
| MediaTek                        | 6        | 0.65%   |
| Dynex                           | 6        | 0.65%   |
| HTC (High Tech Computer)        | 5        | 0.54%   |
| Lite-On Technology              | 4        | 0.43%   |
| Edimax Technology               | 4        | 0.43%   |
| Conwise Technology              | 4        | 0.43%   |
| SINO WEALTH                     | 3        | 0.33%   |
| Foxconn / Hon Hai               | 3        | 0.33%   |
| Belkin Components               | 3        | 0.33%   |
| TP-Link                         | 2        | 0.22%   |
| Realtek                         | 2        | 0.22%   |
| Ralink                          | 2        | 0.22%   |
| Integrated System Solution      | 2        | 0.22%   |
| Sitecom Europe                  | 1        | 0.11%   |
| Micro Star International        | 1        | 0.11%   |
| D-Link                          | 1        | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 263      | 28.49%  |
| Intel AX200 Bluetooth                                                | 153      | 16.58%  |
| Intel Bluetooth wireless interface                                   | 68       | 7.37%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 60       | 6.5%    |
| Realtek Bluetooth Radio                                              | 47       | 5.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 45       | 4.88%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 37       | 4.01%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 34       | 3.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 29       | 3.14%   |
| Intel AX210 Bluetooth                                                | 13       | 1.41%   |
| Intel AX201 Bluetooth                                                | 13       | 1.41%   |
| ASUS Bluetooth Radio                                                 | 13       | 1.41%   |
| ASUS Bluetooth Adapter                                               | 13       | 1.41%   |
| ASUS BCM20702A0                                                      | 9        | 0.98%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 8        | 0.87%   |
| Qualcomm Atheros  Bluetooth Device                                   | 6        | 0.65%   |
| MediaTek Wireless_Device                                             | 6        | 0.65%   |
| IMC Networks Bluetooth Radio                                         | 6        | 0.65%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 6        | 0.65%   |
| ASUS ASUS USB-BT500                                                  | 6        | 0.65%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 5        | 0.54%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 5        | 0.54%   |
| Apple Bluetooth USB Host Controller                                  | 5        | 0.54%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 4        | 0.43%   |
| Conwise CW6622                                                       | 4        | 0.43%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 3        | 0.33%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 3        | 0.33%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                            | 3        | 0.33%   |
| TP-Link TPuLink UB500 Adapter                                        | 2        | 0.22%   |
| Realtek Bluetooth Radio                                              | 2        | 0.22%   |
| Ralink RT3290 Bluetooth                                              | 2        | 0.22%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 0.22%   |
| Lite-On Bluetooth Device                                             | 2        | 0.22%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2        | 0.22%   |
| IMC Networks BCM20702A0                                              | 2        | 0.22%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 2        | 0.22%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 2        | 0.22%   |
| Edimax Bluetooth Adapter                                             | 2        | 0.22%   |
| Broadcom Bluetooth Controller                                        | 2        | 0.22%   |
| Broadcom Bluetooth 3.0 Device                                        | 2        | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 1237     | 29.06%  |
| Intel                                           | 1107     | 26.01%  |
| Nvidia                                          | 1067     | 25.07%  |
| C-Media Electronics                             | 157      | 3.69%   |
| Creative Labs                                   | 63       | 1.48%   |
| Logitech                                        | 61       | 1.43%   |
| Kingston Technology                             | 38       | 0.89%   |
| JMTek                                           | 35       | 0.82%   |
| Texas Instruments                               | 31       | 0.73%   |
| Corsair                                         | 30       | 0.7%    |
| SteelSeries ApS                                 | 27       | 0.63%   |
| Blue Microphones                                | 25       | 0.59%   |
| Focusrite-Novation                              | 24       | 0.56%   |
| Creative Technology                             | 24       | 0.56%   |
| Generalplus Technology                          | 20       | 0.47%   |
| Razer USA                                       | 18       | 0.42%   |
| BEHRINGER International                         | 18       | 0.42%   |
| ASUSTek Computer                                | 18       | 0.42%   |
| Plantronics                                     | 14       | 0.33%   |
| Sony                                            | 12       | 0.28%   |
| GYROCOM C&C                                     | 11       | 0.26%   |
| Realtek Semiconductor                           | 10       | 0.23%   |
| VIA Technologies                                | 9        | 0.21%   |
| M-Audio                                         | 9        | 0.21%   |
| Turtle Beach                                    | 7        | 0.16%   |
| Sennheiser Communications                       | 7        | 0.16%   |
| SAVITECH                                        | 7        | 0.16%   |
| Samson Technologies                             | 7        | 0.16%   |
| RODE Microphones                                | 7        | 0.16%   |
| Giga-Byte Technology                            | 7        | 0.16%   |
| Yamaha                                          | 6        | 0.14%   |
| GN Netcom                                       | 6        | 0.14%   |
| Valve Software                                  | 5        | 0.12%   |
| Elgato Systems                                  | 5        | 0.12%   |
| Dell                                            | 5        | 0.12%   |
| XMOS                                            | 4        | 0.09%   |
| Micro Star International                        | 4        | 0.09%   |
| Licensed by Sony Computer Entertainment America | 4        | 0.09%   |
| Barco Display Systems                           | 4        | 0.09%   |
| Astro Gaming                                    | 4        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 374      | 7.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 277      | 5.58%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 215      | 4.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 150      | 3.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 149      | 3%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 139      | 2.8%    |
| Intel 200 Series PCH HD Audio                                              | 122      | 2.46%   |
| AMD Family 17h/19h HD Audio Controller                                     | 117      | 2.36%   |
| Nvidia GP104 High Definition Audio Controller                              | 113      | 2.28%   |
| Nvidia GP106 High Definition Audio Controller                              | 110      | 2.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 103      | 2.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 99       | 1.99%   |
| AMD Navi 10 HDMI Audio                                                     | 99       | 1.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 98       | 1.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 89       | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 82       | 1.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 66       | 1.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 64       | 1.29%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 61       | 1.23%   |
| Nvidia TU116 High Definition Audio Controller                              | 60       | 1.21%   |
| AMD FCH Azalia Controller                                                  | 60       | 1.21%   |
| Nvidia GM204 High Definition Audio Controller                              | 59       | 1.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 55       | 1.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 55       | 1.11%   |
| Nvidia TU104 HD Audio Controller                                           | 54       | 1.09%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 52       | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                              | 49       | 0.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 49       | 0.99%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 42       | 0.85%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 41       | 0.83%   |
| Nvidia GM206 High Definition Audio Controller                              | 40       | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 40       | 0.81%   |
| Nvidia GP108 High Definition Audio Controller                              | 39       | 0.79%   |
| Nvidia GK104 HDMI Audio Controller                                         | 38       | 0.77%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 38       | 0.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 38       | 0.77%   |
| Nvidia GP102 HDMI Audio Controller                                         | 32       | 0.64%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 31       | 0.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 31       | 0.62%   |
| Nvidia High Definition Audio Controller                                    | 30       | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 278      | 18.82%  |
| Kingston                     | 262      | 17.74%  |
| G.Skill                      | 206      | 13.95%  |
| Unknown                      | 187      | 12.66%  |
| Crucial                      | 132      | 8.94%   |
| Samsung Electronics          | 87       | 5.89%   |
| SK hynix                     | 58       | 3.93%   |
| Micron Technology            | 44       | 2.98%   |
| A-DATA Technology            | 37       | 2.51%   |
| Team                         | 36       | 2.44%   |
| Patriot                      | 30       | 2.03%   |
| Nanya Technology             | 10       | 0.68%   |
| GOODRAM                      | 8        | 0.54%   |
| Unknown (ABCD)               | 7        | 0.47%   |
| Unknown                      | 7        | 0.47%   |
| Ramaxel Technology           | 6        | 0.41%   |
| Elpida                       | 6        | 0.41%   |
| Kllisre                      | 5        | 0.34%   |
| Transcend                    | 4        | 0.27%   |
| Smart                        | 4        | 0.27%   |
| PNY                          | 4        | 0.27%   |
| GeIL                         | 4        | 0.27%   |
| AMD                          | 4        | 0.27%   |
| Silicon Power                | 3        | 0.2%    |
| Kingmax                      | 3        | 0.2%    |
| CSX                          | 3        | 0.2%    |
| Apacer                       | 3        | 0.2%    |
| Unknown (08C8)               | 2        | 0.14%   |
| Qumo                         | 2        | 0.14%   |
| Patriot Memory               | 2        | 0.14%   |
| Neo Forza                    | 2        | 0.14%   |
| Wilk Elektronik              | 1        | 0.07%   |
| Unknown (AB)                 | 1        | 0.07%   |
| Unknown (0xAD44594E45540000) | 1        | 0.07%   |
| Unknown (0x8551)             | 1        | 0.07%   |
| Unknown (0x0416)             | 1        | 0.07%   |
| TwinMOS                      | 1        | 0.07%   |
| Thermaltake                  | 1        | 0.07%   |
| Super Talent                 | 1        | 0.07%   |
| SemsoTai                     | 1        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s     | 38       | 2.32%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 30       | 1.83%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 20       | 1.22%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 20       | 1.22%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 17       | 1.04%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 15       | 0.92%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 15       | 0.92%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s            | 14       | 0.86%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 13       | 0.79%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s           | 11       | 0.67%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 11       | 0.67%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 10       | 0.61%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 10       | 0.61%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s           | 10       | 0.61%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s          | 10       | 0.61%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                  | 10       | 0.61%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM 2667MT/s               | 9        | 0.55%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s        | 9        | 0.55%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s        | 9        | 0.55%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 8        | 0.49%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s          | 8        | 0.49%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s        | 8        | 0.49%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s          | 8        | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 7        | 0.43%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 7        | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s | 7        | 0.43%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s          | 7        | 0.43%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s          | 7        | 0.43%   |
| Unknown                                                      | 7        | 0.43%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 6        | 0.37%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s        | 6        | 0.37%   |
| Team RAM TEAMGROUP-UD4-3000 8192MB DIMM DDR4 3067MT/s        | 6        | 0.37%   |
| Kingston RAM KHX2666C15D4/4G 4096MB DIMM DDR4 3200MT/s       | 6        | 0.37%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s          | 6        | 0.37%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s           | 6        | 0.37%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s       | 6        | 0.37%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 5        | 0.31%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s          | 5        | 0.31%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 5        | 0.31%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 5        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 771      | 58.19%  |
| DDR3    | 380      | 28.68%  |
| Unknown | 75       | 5.66%   |
| DDR2    | 39       | 2.94%   |
| SDRAM   | 38       | 2.87%   |
| DDR     | 12       | 0.91%   |
| LPDDR4  | 7        | 0.53%   |
| LPDDR3  | 1        | 0.08%   |
| DRAM    | 1        | 0.08%   |
| DDR5    | 1        | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1278     | 97.56%  |
| SODIMM  | 28       | 2.14%   |
| FB-DIMM | 3        | 0.23%   |
| RIMM    | 1        | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 644      | 44.82%  |
| 4096  | 303      | 21.09%  |
| 16384 | 250      | 17.4%   |
| 2048  | 137      | 9.53%   |
| 32768 | 59       | 4.11%   |
| 1024  | 39       | 2.71%   |
| 512   | 4        | 0.28%   |
| 3072  | 1        | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 212      | 14.47%  |
| 3200    | 197      | 13.45%  |
| 3600    | 153      | 10.44%  |
| 1333    | 135      | 9.22%   |
| 2400    | 91       | 6.21%   |
| 2667    | 70       | 4.78%   |
| 2133    | 66       | 4.51%   |
| 3466    | 54       | 3.69%   |
| 1867    | 48       | 3.28%   |
| 3000    | 47       | 3.21%   |
| 3400    | 46       | 3.14%   |
| 800     | 43       | 2.94%   |
| 1866    | 29       | 1.98%   |
| 667     | 27       | 1.84%   |
| 3866    | 25       | 1.71%   |
| 3800    | 24       | 1.64%   |
| 2933    | 18       | 1.23%   |
| 3733    | 17       | 1.16%   |
| Unknown | 16       | 1.09%   |
| 2666    | 15       | 1.02%   |
| 1066    | 14       | 0.96%   |
| 2800    | 11       | 0.75%   |
| 1800    | 10       | 0.68%   |
| 3666    | 6        | 0.41%   |
| 3334    | 6        | 0.41%   |
| 3067    | 6        | 0.41%   |
| 1334    | 6        | 0.41%   |
| 3266    | 5        | 0.34%   |
| 1067    | 5        | 0.34%   |
| 333     | 5        | 0.34%   |
| 3500    | 4        | 0.27%   |
| 3100    | 4        | 0.27%   |
| 2048    | 4        | 0.27%   |
| 533     | 4        | 0.27%   |
| 400     | 4        | 0.27%   |
| 49926   | 3        | 0.2%    |
| 3066    | 3        | 0.2%    |
| 4400    | 2        | 0.14%   |
| 4000    | 2        | 0.14%   |
| 3333    | 2        | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 37       | 41.57%  |
| Brother Industries    | 18       | 20.22%  |
| Canon                 | 9        | 10.11%  |
| Seiko Epson           | 6        | 6.74%   |
| Samsung Electronics   | 5        | 5.62%   |
| Pantum                | 3        | 3.37%   |
| Xerox                 | 2        | 2.25%   |
| Prolific Technology   | 2        | 2.25%   |
| Apple                 | 2        | 2.25%   |
| Ricoh                 | 1        | 1.12%   |
| QinHeng Electronics   | 1        | 1.12%   |
| Oki Data              | 1        | 1.12%   |
| Lexmark International | 1        | 1.12%   |
| Dymo-CoStar           | 1        | 1.12%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| HP OfficeJet 5200 series                     | 3        | 3.33%   |
| HP LaserJet 1300                             | 3        | 3.33%   |
| Xerox Phaser 3020                            | 2        | 2.22%   |
| Seiko Epson L120 Series                      | 2        | 2.22%   |
| Prolific PL2305 Parallel Port                | 2        | 2.22%   |
| HP Officejet 2620 series                     | 2        | 2.22%   |
| HP DeskJet 2130 series                       | 2        | 2.22%   |
| HP Color LaserJet Pro M453-4                 | 2        | 2.22%   |
| Canon MG5700 series                          | 2        | 2.22%   |
| Brother HL-5370DW series                     | 2        | 2.22%   |
| Apple Gamesir-T1s 2.0b                       | 2        | 2.22%   |
| Seiko Epson Stylus NX230/SX235W Series       | 1        | 1.11%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 1.11%   |
| Seiko Epson L805 Series                      | 1        | 1.11%   |
| Seiko Epson ET-4760 Series                   | 1        | 1.11%   |
| Seiko Epson ET-3850 Series                   | 1        | 1.11%   |
| Samsung ML-1660 Series                       | 1        | 1.11%   |
| Samsung ML-1640 Series Laser Printer         | 1        | 1.11%   |
| Samsung M2020 Series                         | 1        | 1.11%   |
| Samsung CLX-3300 Series                      | 1        | 1.11%   |
| Samsung CLP-310 Color Laser Printer          | 1        | 1.11%   |
| Ricoh SP 112SU                               | 1        | 1.11%   |
| QinHeng CH340S                               | 1        | 1.11%   |
| Pantum P2500W series                         | 1        | 1.11%   |
| Pantum P2200 series                          | 1        | 1.11%   |
| Pantum M6500 series                          | 1        | 1.11%   |
| Oki Data USB Device                          | 1        | 1.11%   |
| Lexmark International Lexmark MS312dn        | 1        | 1.11%   |
| HP OfficeJet Pro 8020 series                 | 1        | 1.11%   |
| HP LaserJet P2015 series                     | 1        | 1.11%   |
| HP LaserJet P1005                            | 1        | 1.11%   |
| HP LaserJet 200 colorMFP M276nw              | 1        | 1.11%   |
| HP LaserJet 1020                             | 1        | 1.11%   |
| HP LaserJet 1018                             | 1        | 1.11%   |
| HP LaserJet 1012                             | 1        | 1.11%   |
| HP LaserJet 1010                             | 1        | 1.11%   |
| HP ENVY Photo 7100 series                    | 1        | 1.11%   |
| HP ENVY 6000 series                          | 1        | 1.11%   |
| HP ENVY 5000 series                          | 1        | 1.11%   |
| HP ENVY 4520 series                          | 1        | 1.11%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 11       | 50%     |
| Seiko Epson        | 5        | 22.73%  |
| Hewlett-Packard    | 2        | 9.09%   |
| Visioneer          | 1        | 4.55%   |
| Ultima Electronics | 1        | 4.55%   |
| Mustek Systems     | 1        | 4.55%   |
| AGFA-Gevaert NV    | 1        | 4.55%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 4        | 18.18%  |
| Canon CanoScan LiDE 220                                                               | 3        | 13.64%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 9.09%   |
| Canon CanoScan LIDE 25                                                                | 2        | 9.09%   |
| Visioneer OneTouch 5300 USB                                                           | 1        | 4.55%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 4.55%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 4.55%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 4.55%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1        | 4.55%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 4.55%   |
| HP ScanJet 3500c                                                                      | 1        | 4.55%   |
| HP ScanJet 3400cse                                                                    | 1        | 4.55%   |
| Canon CanoScan LiDE 90                                                                | 1        | 4.55%   |
| Canon CanoScan LiDE 120                                                               | 1        | 4.55%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1        | 4.55%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 211      | 42.12%  |
| Microsoft                              | 43       | 8.58%   |
| Microdia                               | 39       | 7.78%   |
| Samsung Electronics                    | 17       | 3.39%   |
| Z-Star Microelectronics                | 16       | 3.19%   |
| Sunplus Innovation Technology          | 12       | 2.4%    |
| Creative Technology                    | 11       | 2.2%    |
| Apple                                  | 9        | 1.8%    |
| MacroSilicon                           | 7        | 1.4%    |
| GEMBIRD                                | 7        | 1.4%    |
| Google                                 | 6        | 1.2%    |
| Generalplus Technology                 | 6        | 1.2%    |
| Cubeternet                             | 6        | 1.2%    |
| Chicony Electronics                    | 6        | 1.2%    |
| ARC International                      | 6        | 1.2%    |
| Valve Software                         | 5        | 1%      |
| LG Electronics                         | 5        | 1%      |
| Realtek Semiconductor                  | 4        | 0.8%    |
| KYE Systems (Mouse Systems)            | 4        | 0.8%    |
| Genesys Logic                          | 4        | 0.8%    |
| Aveo Technology                        | 4        | 0.8%    |
| Alcor Micro                            | 4        | 0.8%    |
| Xiongmai                               | 3        | 0.6%    |
| Sonix Technology                       | 3        | 0.6%    |
| SHENZHEN EMEET TECHNOLOGY              | 3        | 0.6%    |
| Razer USA                              | 3        | 0.6%    |
| Pixart Imaging                         | 3        | 0.6%    |
| Jieli Technology                       | 3        | 0.6%    |
| Huawei Technologies                    | 3        | 0.6%    |
| Arkmicro Technologies                  | 3        | 0.6%    |
| 2M UVC CAMERA                          | 3        | 0.6%    |
| WCM_USB                                | 2        | 0.4%    |
| WaveRider Communications               | 2        | 0.4%    |
| SJ-180517-N                            | 2        | 0.4%    |
| Silicon Motion                         | 2        | 0.4%    |
| Philips (or NXP)                       | 2        | 0.4%    |
| Cheng Uei Precision Industry (Foxlink) | 2        | 0.4%    |
| AVerMedia Technologies                 | 2        | 0.4%    |
| Acer                                   | 2        | 0.4%    |
| YGTek                                  | 1        | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 53       | 10.54%  |
| Logitech HD Pro Webcam C920                           | 38       | 7.55%   |
| Microsoft LifeCam HD-3000                             | 20       | 3.98%   |
| Samsung Galaxy series, misc. (MTP mode)               | 17       | 3.38%   |
| Logitech C922 Pro Stream Webcam                       | 15       | 2.98%   |
| Microdia Webcam Vitade AF                             | 13       | 2.58%   |
| Logitech Webcam C310                                  | 10       | 1.99%   |
| Z-Star Venus USB2.0 Camera                            | 8        | 1.59%   |
| Microdia USB Live camera                              | 8        | 1.59%   |
| Logitech HD Webcam C615                               | 8        | 1.59%   |
| MacroSilicon USB Video                                | 7        | 1.39%   |
| Logitech Webcam C930e                                 | 7        | 1.39%   |
| Logitech HD Webcam C525                               | 7        | 1.39%   |
| Apple iPhone 5/5C/5S/6/SE                             | 7        | 1.39%   |
| Sunplus FHD Camera Microphone                         | 6        | 1.19%   |
| Microsoft LifeCam VX-2000                             | 6        | 1.19%   |
| Microdia USB 2.0 Camera                               | 6        | 1.19%   |
| Logitech Webcam C170                                  | 6        | 1.19%   |
| Logitech StreamCam                                    | 6        | 1.19%   |
| Valve Software 3D Camera                              | 5        | 0.99%   |
| Sunplus Full HD webcam                                | 5        | 0.99%   |
| Logitech Webcam Pro 9000                              | 5        | 0.99%   |
| Logitech HD Webcam C910                               | 5        | 0.99%   |
| Logitech C920 PRO HD Webcam                           | 5        | 0.99%   |
| Logitech BRIO Ultra HD Webcam                         | 5        | 0.99%   |
| ARC International Camera                              | 5        | 0.99%   |
| Logitech HD Webcam C510                               | 4        | 0.8%    |
| Logitech B525 HD Webcam                               | 4        | 0.8%    |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 4        | 0.8%    |
| Google Nexus/Pixel Device (MTP + debug)               | 4        | 0.8%    |
| GEMBIRD USB2.0 PC CAMERA                              | 4        | 0.8%    |
| Creative Live! Cam Chat HD [VF0700]                   | 4        | 0.8%    |
| Z-Star USB2.0 Camera                                  | 3        | 0.6%    |
| Xiongmai web camera                                   | 3        | 0.6%    |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960        | 3        | 0.6%    |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 3        | 0.6%    |
| Microsoft MicrosoftÂ LifeCam Studio                  | 3        | 0.6%    |
| Microsoft LifeCam HD-5000                             | 3        | 0.6%    |
| Microsoft LifeCam Cinema                              | 3        | 0.6%    |
| Microdia Camera                                       | 3        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 3        | 50%     |
| STMicroelectronics    | 1        | 16.67%  |
| Futronic Technology   | 1        | 16.67%  |
| AuthenTec             | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 3        | 50%     |
| STMicroelectronics Fingerprint Reader       | 1        | 16.67%  |
| Futronic FS81 Fingerprint Scanner Module    | 1        | 16.67%  |
| AuthenTec AES1600                           | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 4        | 21.05%  |
| Gemalto (was Gemplus)             | 4        | 21.05%  |
| Alcor Micro                       | 4        | 21.05%  |
| VASCO Data Security International | 2        | 10.53%  |
| OmniKey                           | 2        | 10.53%  |
| SCM Microsystems                  | 1        | 5.26%   |
| Cherry                            | 1        | 5.26%   |
| BIT4ID                            | 1        | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface               | 4        | 21.05%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 4        | 21.05%  |
| Alcor Micro AU9540 Smartcard Reader                             | 3        | 15.79%  |
| OmniKey 3x21 Smart Card Reader                                  | 2        | 10.53%  |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1        | 5.26%   |
| VASCO Data Security International DIGIPASS 870                  | 1        | 5.26%   |
| SCM Microsystems SCR331 SmartCard Reader                        | 1        | 5.26%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                     | 1        | 5.26%   |
| BIT4ID miniLector EVO                                           | 1        | 5.26%   |
| Alcor Micro Watchdata W 1981                                    | 1        | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1935     | 86.65%  |
| 1     | 266      | 11.91%  |
| 2     | 29       | 1.3%    |
| 3     | 3        | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 128      | 40.38%  |
| Unassigned class         | 44       | 13.88%  |
| Graphics card            | 38       | 11.99%  |
| Camera                   | 15       | 4.73%   |
| Chipcard                 | 14       | 4.42%   |
| Sound                    | 11       | 3.47%   |
| Multimedia controller    | 11       | 3.47%   |
| Communication controller | 11       | 3.47%   |
| Net/ethernet             | 10       | 3.15%   |
| Bluetooth                | 9        | 2.84%   |
| Dvb card                 | 8        | 2.52%   |
| Fingerprint reader       | 5        | 1.58%   |
| Storage/raid             | 4        | 1.26%   |
| Network                  | 4        | 1.26%   |
| Storage/ide              | 2        | 0.63%   |
| Video                    | 1        | 0.32%   |
| Storage/ata              | 1        | 0.32%   |
| Storage                  | 1        | 0.32%   |

