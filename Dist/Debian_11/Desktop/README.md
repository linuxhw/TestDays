Debian 11 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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
| Gigabyte      | M61PME-S2P                  | [0baa540bf5](https://linux-hardware.org/?probe=0baa540bf5) | Sep 08, 2021 |
| Foxconn       | nT-A3000 series FAB         | [9e22d6dc70](https://linux-hardware.org/?probe=9e22d6dc70) | Sep 08, 2021 |
| ASUSTek       | P6T DELUXE V2               | [f8aae7ade2](https://linux-hardware.org/?probe=f8aae7ade2) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | [a826f2f4c9](https://linux-hardware.org/?probe=a826f2f4c9) | Sep 08, 2021 |
| Gigabyte      | H61M-DS2                    | [5aa6e46608](https://linux-hardware.org/?probe=5aa6e46608) | Sep 08, 2021 |
| Gigabyte      | M61PME-S2P                  | [2626e29c5f](https://linux-hardware.org/?probe=2626e29c5f) | Sep 08, 2021 |
| ASUSTek       | Z87-A                       | [04ecb299d9](https://linux-hardware.org/?probe=04ecb299d9) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | [b521805956](https://linux-hardware.org/?probe=b521805956) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | [c4f6c7da11](https://linux-hardware.org/?probe=c4f6c7da11) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | [a4acb4b4d7](https://linux-hardware.org/?probe=a4acb4b4d7) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | [33ae3adcc6](https://linux-hardware.org/?probe=33ae3adcc6) | Sep 08, 2021 |
| Gigabyte      | H81M-S2V                    | [cb2158566c](https://linux-hardware.org/?probe=cb2158566c) | Sep 08, 2021 |
| Dell          | 0X8DXD A00                  | [65e545345d](https://linux-hardware.org/?probe=65e545345d) | Sep 07, 2021 |
| Gigabyte      | M61PME-S2P                  | [41ab6b2f21](https://linux-hardware.org/?probe=41ab6b2f21) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [5acaf42867](https://linux-hardware.org/?probe=5acaf42867) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [4d6ad821df](https://linux-hardware.org/?probe=4d6ad821df) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [511d2e120b](https://linux-hardware.org/?probe=511d2e120b) | Sep 07, 2021 |
| Gigabyte      | H81M-S2V                    | [13256468d1](https://linux-hardware.org/?probe=13256468d1) | Sep 07, 2021 |
| ASUSTek       | P5Q3                        | [3f08e7bf37](https://linux-hardware.org/?probe=3f08e7bf37) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [bcd1f7553d](https://linux-hardware.org/?probe=bcd1f7553d) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [0c0ccb21d8](https://linux-hardware.org/?probe=0c0ccb21d8) | Sep 07, 2021 |
| ASUSTek       | H81M-C                      | [cf59508b79](https://linux-hardware.org/?probe=cf59508b79) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [1c85c31f57](https://linux-hardware.org/?probe=1c85c31f57) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [6cf8ebc24c](https://linux-hardware.org/?probe=6cf8ebc24c) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [bf328adcb8](https://linux-hardware.org/?probe=bf328adcb8) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [09e28c958c](https://linux-hardware.org/?probe=09e28c958c) | Sep 07, 2021 |
| HP            | 212A                        | [7f51e384f7](https://linux-hardware.org/?probe=7f51e384f7) | Sep 07, 2021 |
| HP            | 212A                        | [c89a2196ab](https://linux-hardware.org/?probe=c89a2196ab) | Sep 07, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [265822ee2e](https://linux-hardware.org/?probe=265822ee2e) | Sep 06, 2021 |
| ASUSTek       | P5Q-PRO                     | [a0d1d9b2e6](https://linux-hardware.org/?probe=a0d1d9b2e6) | Sep 06, 2021 |
| ECS           | H61H2-M13                   | [4aec08beef](https://linux-hardware.org/?probe=4aec08beef) | Sep 06, 2021 |
| Dell          | 0X8DXD A00                  | [28c59930e4](https://linux-hardware.org/?probe=28c59930e4) | Sep 05, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | [20f947223f](https://linux-hardware.org/?probe=20f947223f) | Sep 05, 2021 |
| ASUSTek       | PRIME H410M-E               | [af5a140c2e](https://linux-hardware.org/?probe=af5a140c2e) | Sep 04, 2021 |
| ASRock        | TRX40 Creator               | [0734c9bbd0](https://linux-hardware.org/?probe=0734c9bbd0) | Sep 03, 2021 |
| ASRock        | 960GM/U3S3 FX               | [ced0e47579](https://linux-hardware.org/?probe=ced0e47579) | Sep 02, 2021 |
| ECS           | G31T-M9                     | [0757de543d](https://linux-hardware.org/?probe=0757de543d) | Sep 02, 2021 |
| Gigabyte      | 8I945P-G                    | [a1eb33a5f1](https://linux-hardware.org/?probe=a1eb33a5f1) | Sep 02, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d4c78cc3c4](https://linux-hardware.org/?probe=d4c78cc3c4) | Sep 02, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ca0e00bc0f](https://linux-hardware.org/?probe=ca0e00bc0f) | Sep 01, 2021 |
| ECS           | H61H2-M13                   | [e96ab5fb39](https://linux-hardware.org/?probe=e96ab5fb39) | Sep 01, 2021 |
| MSI           | H110M PRO-VD                | [78fafc3314](https://linux-hardware.org/?probe=78fafc3314) | Sep 01, 2021 |
| Dell          | 0M863N A00                  | [d8083308fc](https://linux-hardware.org/?probe=d8083308fc) | Sep 01, 2021 |
| ASRock        | N68-VS3 FX                  | [450ffd830c](https://linux-hardware.org/?probe=450ffd830c) | Sep 01, 2021 |
| Intel         | DH77KC AAG39641-400         | [dadb397ef1](https://linux-hardware.org/?probe=dadb397ef1) | Sep 01, 2021 |
| Pegatron      | TRUCKEE                     | [68f16e9542](https://linux-hardware.org/?probe=68f16e9542) | Sep 01, 2021 |
| ASRock        | H61M-VG4                    | [6521e0d6be](https://linux-hardware.org/?probe=6521e0d6be) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [9c31643811](https://linux-hardware.org/?probe=9c31643811) | Aug 31, 2021 |
| ASUSTek       | P7P55D-E                    | [4c05b36e94](https://linux-hardware.org/?probe=4c05b36e94) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [37c3e457bc](https://linux-hardware.org/?probe=37c3e457bc) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [0d38048f46](https://linux-hardware.org/?probe=0d38048f46) | Aug 31, 2021 |
| Intel         | DH77KC AAG39641-400         | [d7eaf975a0](https://linux-hardware.org/?probe=d7eaf975a0) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [df9b303eec](https://linux-hardware.org/?probe=df9b303eec) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [d9af23fb86](https://linux-hardware.org/?probe=d9af23fb86) | Aug 31, 2021 |
| AOpen         | D1001 C26361-D1001          | [e27239d870](https://linux-hardware.org/?probe=e27239d870) | Aug 31, 2021 |
| ASUSTek       | B85M-G                      | [1470c8cc7f](https://linux-hardware.org/?probe=1470c8cc7f) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [ba7144c0dc](https://linux-hardware.org/?probe=ba7144c0dc) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [7204a77b38](https://linux-hardware.org/?probe=7204a77b38) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [c6a754129a](https://linux-hardware.org/?probe=c6a754129a) | Aug 30, 2021 |
| ASRock        | H470M-HVS                   | [a251dca266](https://linux-hardware.org/?probe=a251dca266) | Aug 30, 2021 |
| Intel         | DH67BL AAG10189-206         | [b7b3f489f2](https://linux-hardware.org/?probe=b7b3f489f2) | Aug 30, 2021 |
| Gigabyte      | H81M-S2V                    | [d255f48a39](https://linux-hardware.org/?probe=d255f48a39) | Aug 30, 2021 |
| ASRock        | H61M-VG4                    | [dc0abe4fcd](https://linux-hardware.org/?probe=dc0abe4fcd) | Aug 30, 2021 |
| ASRock        | H61M-VG4                    | [fc61c24624](https://linux-hardware.org/?probe=fc61c24624) | Aug 30, 2021 |
| Gigabyte      | H81M-S2V                    | [9d1b86643e](https://linux-hardware.org/?probe=9d1b86643e) | Aug 30, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [b9595196ea](https://linux-hardware.org/?probe=b9595196ea) | Aug 28, 2021 |
| NC9VL         | 1.0                         | [9c4b8ad466](https://linux-hardware.org/?probe=9c4b8ad466) | Aug 28, 2021 |
| MSI           | B150A GAMING PRO            | [06de6cd826](https://linux-hardware.org/?probe=06de6cd826) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | [46eacf8d5c](https://linux-hardware.org/?probe=46eacf8d5c) | Aug 27, 2021 |
| Intel         | DN2820FYK H24582-201        | [06f4334a82](https://linux-hardware.org/?probe=06f4334a82) | Aug 27, 2021 |
| ASUSTek       | WS X299 SAGE                | [7f3a68dd2a](https://linux-hardware.org/?probe=7f3a68dd2a) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | [2737cfb67d](https://linux-hardware.org/?probe=2737cfb67d) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | [dc9428d8b4](https://linux-hardware.org/?probe=dc9428d8b4) | Aug 27, 2021 |
| HP            | 0B0Ch                       | [b5933fde35](https://linux-hardware.org/?probe=b5933fde35) | Aug 26, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [f26ade88cd](https://linux-hardware.org/?probe=f26ade88cd) | Aug 26, 2021 |
| Dell          | 0WR7PY A00                  | [cb25b1811b](https://linux-hardware.org/?probe=cb25b1811b) | Aug 26, 2021 |
| Dell          | 0X8DXD A00                  | [8dd8862b4b](https://linux-hardware.org/?probe=8dd8862b4b) | Aug 26, 2021 |
| ASRock        | H470M-HVS                   | [d37f13917f](https://linux-hardware.org/?probe=d37f13917f) | Aug 25, 2021 |
| ASRock        | C2750D4I                    | [6daa3c26bf](https://linux-hardware.org/?probe=6daa3c26bf) | Aug 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0a79171c9e](https://linux-hardware.org/?probe=0a79171c9e) | Aug 25, 2021 |
| ASUSTek       | P5KPL-CM                    | [feed9e2921](https://linux-hardware.org/?probe=feed9e2921) | Aug 25, 2021 |
| Biostar       | Hi-Fi A85W                  | [ffb66dafd4](https://linux-hardware.org/?probe=ffb66dafd4) | Aug 25, 2021 |
| AAEON         | MF-001 V1.0                 | [b06c4079a7](https://linux-hardware.org/?probe=b06c4079a7) | Aug 25, 2021 |
| Dell          | 040DDP A01                  | [557d74beb9](https://linux-hardware.org/?probe=557d74beb9) | Aug 25, 2021 |
| ASRock        | H470M-HVS                   | [e5c92fe4ad](https://linux-hardware.org/?probe=e5c92fe4ad) | Aug 24, 2021 |
| ASRock        | H470M-HVS                   | [441b8b892e](https://linux-hardware.org/?probe=441b8b892e) | Aug 24, 2021 |
| ASRock        | P4i65G                      | [43ce3e711f](https://linux-hardware.org/?probe=43ce3e711f) | Aug 24, 2021 |
| ASRock        | H77 Pro4/MVP                | [c2179206a9](https://linux-hardware.org/?probe=c2179206a9) | Aug 24, 2021 |
| Unknown       | 1.0                         | [5e638360a8](https://linux-hardware.org/?probe=5e638360a8) | Aug 24, 2021 |
| ASUSTek       | GA35DX                      | [3843ea048e](https://linux-hardware.org/?probe=3843ea048e) | Aug 24, 2021 |
| ASRock        | H470M-HVS                   | [e92004f46a](https://linux-hardware.org/?probe=e92004f46a) | Aug 23, 2021 |
| ASRock        | H470M-HVS                   | [06c9a1ed3a](https://linux-hardware.org/?probe=06c9a1ed3a) | Aug 23, 2021 |
| ASUSTek       | P5KPL-CM                    | [06234ebe05](https://linux-hardware.org/?probe=06234ebe05) | Aug 23, 2021 |
| MSI           | Z270-A PRO                  | [73b14ecca0](https://linux-hardware.org/?probe=73b14ecca0) | Aug 23, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [eea45758b7](https://linux-hardware.org/?probe=eea45758b7) | Aug 22, 2021 |
| HP            | 085Ch                       | [2e649d07a0](https://linux-hardware.org/?probe=2e649d07a0) | Aug 21, 2021 |
| HP            | 085Ch                       | [c5b36c5187](https://linux-hardware.org/?probe=c5b36c5187) | Aug 21, 2021 |
| ASRock        | Z97 Pro3                    | [0f9abf9c63](https://linux-hardware.org/?probe=0f9abf9c63) | Aug 21, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [7f83e1b3c8](https://linux-hardware.org/?probe=7f83e1b3c8) | Aug 21, 2021 |
| ASUSTek       | P5B SE                      | [81634fcb22](https://linux-hardware.org/?probe=81634fcb22) | Aug 21, 2021 |
| MSI           | Z270-A PRO                  | [e59c9482f6](https://linux-hardware.org/?probe=e59c9482f6) | Aug 21, 2021 |
| ASRock        | H470M-HVS                   | [cba7d82942](https://linux-hardware.org/?probe=cba7d82942) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | [62068f391f](https://linux-hardware.org/?probe=62068f391f) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | [c980f2d201](https://linux-hardware.org/?probe=c980f2d201) | Aug 20, 2021 |
| Dell          | 0Y2K8N A01                  | [6b0fd02c91](https://linux-hardware.org/?probe=6b0fd02c91) | Aug 20, 2021 |
| Intel         | DG33BU AAD79951-407         | [17c70c7886](https://linux-hardware.org/?probe=17c70c7886) | Aug 19, 2021 |
| HP            | 339A                        | [57d5bbd1e4](https://linux-hardware.org/?probe=57d5bbd1e4) | Aug 19, 2021 |
| Gigabyte      | A320M-S2H-CF                | [2151b5cdae](https://linux-hardware.org/?probe=2151b5cdae) | Aug 19, 2021 |
| HP            | 1587h                       | [3ddbdb3101](https://linux-hardware.org/?probe=3ddbdb3101) | Aug 19, 2021 |
| ASRock        | H470M-HVS                   | [0489699bc4](https://linux-hardware.org/?probe=0489699bc4) | Aug 19, 2021 |
| MSI           | B450M PRO-M2 MAX            | [cc54b8955c](https://linux-hardware.org/?probe=cc54b8955c) | Aug 19, 2021 |
| ASRock        | H470M-HVS                   | [757e261c56](https://linux-hardware.org/?probe=757e261c56) | Aug 19, 2021 |
| Lenovo        | MAHOBAY                     | [df15656fce](https://linux-hardware.org/?probe=df15656fce) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6f5485edfc](https://linux-hardware.org/?probe=6f5485edfc) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [1fce0ab0e8](https://linux-hardware.org/?probe=1fce0ab0e8) | Aug 18, 2021 |
| Lenovo        | Board                       | [3de8569fe7](https://linux-hardware.org/?probe=3de8569fe7) | Aug 18, 2021 |
| ASUSTek       | H81M-R                      | [8598ad2248](https://linux-hardware.org/?probe=8598ad2248) | Aug 18, 2021 |
| ASUSTek       | B150M-K                     | [3f706a2a69](https://linux-hardware.org/?probe=3f706a2a69) | Aug 18, 2021 |
| ASUSTek       | P7H55-M SI                  | [9f3381d34c](https://linux-hardware.org/?probe=9f3381d34c) | Aug 18, 2021 |
| ASRock        | B460 Phantom Gaming 4       | [85cfabd795](https://linux-hardware.org/?probe=85cfabd795) | Aug 18, 2021 |
| ASUSTek       | P7H55-M SI                  | [765f5d340e](https://linux-hardware.org/?probe=765f5d340e) | Aug 18, 2021 |
| ASRock        | J4205-ITX                   | [30de75d2c8](https://linux-hardware.org/?probe=30de75d2c8) | Aug 18, 2021 |
| ASUSTek       | A68HM-PLUS                  | [b2ed4bc6fe](https://linux-hardware.org/?probe=b2ed4bc6fe) | Aug 18, 2021 |
| Gigabyte      | Z97N-WIFI                   | [be9383850e](https://linux-hardware.org/?probe=be9383850e) | Aug 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [7911fbd6a6](https://linux-hardware.org/?probe=7911fbd6a6) | Aug 17, 2021 |
| MSI           | FM2-A55M-E33                | [6972c43e80](https://linux-hardware.org/?probe=6972c43e80) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Intel         | DN2820FYK H24582-201        | [86cf4755a0](https://linux-hardware.org/?probe=86cf4755a0) | Aug 16, 2021 |
| ASRock        | B460 Phantom Gaming 4       | [51f9388874](https://linux-hardware.org/?probe=51f9388874) | Aug 15, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [88160f850f](https://linux-hardware.org/?probe=88160f850f) | Aug 15, 2021 |
| ASUSTek       | M5A99X EVO                  | [53aff8d681](https://linux-hardware.org/?probe=53aff8d681) | Aug 15, 2021 |
| ECS           | KBN-I                       | [bbfe1ba1a2](https://linux-hardware.org/?probe=bbfe1ba1a2) | Aug 15, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [987ab1f3bf](https://linux-hardware.org/?probe=987ab1f3bf) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | [a6e0859eac](https://linux-hardware.org/?probe=a6e0859eac) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | [5ce5d800d3](https://linux-hardware.org/?probe=5ce5d800d3) | Aug 14, 2021 |
| ASUSTek       | PRIME Z390-P                | [dfe51161fe](https://linux-hardware.org/?probe=dfe51161fe) | Aug 14, 2021 |
| ASRock        | Z97 Pro3                    | [0e5746a060](https://linux-hardware.org/?probe=0e5746a060) | Aug 14, 2021 |
| Dell          | 0X9M3X A01                  | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| HP            | 3397                        | [a3425b956c](https://linux-hardware.org/?probe=a3425b956c) | Aug 14, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [62faddbfaa](https://linux-hardware.org/?probe=62faddbfaa) | Aug 13, 2021 |
| ASUSTek       | X99-DELUXE                  | [f59179a579](https://linux-hardware.org/?probe=f59179a579) | Aug 13, 2021 |
| ASUSTek       | Z170-PRO                    | [7f9b5606a5](https://linux-hardware.org/?probe=7f9b5606a5) | Aug 13, 2021 |
| HP            | 3048h                       | [894950911f](https://linux-hardware.org/?probe=894950911f) | Aug 11, 2021 |
| Gigabyte      | 970A-DS3P                   | [9b62457757](https://linux-hardware.org/?probe=9b62457757) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| HP            | 2AF7                        | [649ed7df8e](https://linux-hardware.org/?probe=649ed7df8e) | Aug 10, 2021 |
| Intel         | DQ45CB AAE30148-207         | [56a573eeed](https://linux-hardware.org/?probe=56a573eeed) | Aug 10, 2021 |
| ASUSTek       | P7H55-M/USB3                | [6f4ad31000](https://linux-hardware.org/?probe=6f4ad31000) | Aug 10, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [78223998b6](https://linux-hardware.org/?probe=78223998b6) | Aug 10, 2021 |
| MSI           | B250M PRO-VDH               | [d6be998202](https://linux-hardware.org/?probe=d6be998202) | Aug 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Dell          | 04MFRM A01                  | [c0094def97](https://linux-hardware.org/?probe=c0094def97) | Aug 09, 2021 |
| MSI           | B450 TOMAHAWK               | [58b4f52cc0](https://linux-hardware.org/?probe=58b4f52cc0) | Aug 09, 2021 |
| ASUSTek       | P7H55-M/USB3                | [7ca1257064](https://linux-hardware.org/?probe=7ca1257064) | Aug 09, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [fffaf4c700](https://linux-hardware.org/?probe=fffaf4c700) | Aug 09, 2021 |
| Gigabyte      | H470M DS3H                  | [29de4693d8](https://linux-hardware.org/?probe=29de4693d8) | Aug 09, 2021 |
| ASRock        | 970A-G                      | [f1e9959894](https://linux-hardware.org/?probe=f1e9959894) | Aug 09, 2021 |
| Toshiba       | STI 910090 STIJ             | [389ebd7675](https://linux-hardware.org/?probe=389ebd7675) | Aug 08, 2021 |
| ASRock        | X370 Killer SLI             | [8a0885afb6](https://linux-hardware.org/?probe=8a0885afb6) | Aug 08, 2021 |
| MSI           | Z490-A PRO                  | [eac37d633f](https://linux-hardware.org/?probe=eac37d633f) | Aug 08, 2021 |
| ASRock        | Z97 Pro4                    | [090d12a96f](https://linux-hardware.org/?probe=090d12a96f) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [39eb5a1578](https://linux-hardware.org/?probe=39eb5a1578) | Aug 08, 2021 |
| Toshiba       | STI 005038 G31T-M7          | [faa8f15725](https://linux-hardware.org/?probe=faa8f15725) | Aug 08, 2021 |
| Gigabyte      | Z77-D3H                     | [9dafe47483](https://linux-hardware.org/?probe=9dafe47483) | Aug 07, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [da833ac33e](https://linux-hardware.org/?probe=da833ac33e) | Aug 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [80c7711147](https://linux-hardware.org/?probe=80c7711147) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | [4ff5966d22](https://linux-hardware.org/?probe=4ff5966d22) | Aug 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | [5839492cd8](https://linux-hardware.org/?probe=5839492cd8) | Aug 07, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [733a3e325c](https://linux-hardware.org/?probe=733a3e325c) | Aug 07, 2021 |
| Dell          | 08WKV3 A01                  | [8ab0ff9442](https://linux-hardware.org/?probe=8ab0ff9442) | Aug 07, 2021 |
| MSI           | MEG X399 CREATION           | [7cada9aaed](https://linux-hardware.org/?probe=7cada9aaed) | Aug 07, 2021 |
| MSI           | B250M PRO-VDH               | [187e4dd872](https://linux-hardware.org/?probe=187e4dd872) | Aug 07, 2021 |
| ASRock        | H470M-HVS                   | [545f7195ab](https://linux-hardware.org/?probe=545f7195ab) | Aug 06, 2021 |
| Gigabyte      | H81M-S2V                    | [9ec5eaeaf9](https://linux-hardware.org/?probe=9ec5eaeaf9) | Aug 06, 2021 |
| HP            | 2AF7                        | [1737071720](https://linux-hardware.org/?probe=1737071720) | Aug 06, 2021 |
| HP            | 2AF7                        | [c504247f44](https://linux-hardware.org/?probe=c504247f44) | Aug 06, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [31d159af99](https://linux-hardware.org/?probe=31d159af99) | Aug 06, 2021 |
| Lenovo        | Board                       | [18138486db](https://linux-hardware.org/?probe=18138486db) | Aug 05, 2021 |
| Intel         | DN2820FYK H24582-201        | [7caf949908](https://linux-hardware.org/?probe=7caf949908) | Aug 05, 2021 |
| Unknown       | Intel X79                   | [fc0dedbb3c](https://linux-hardware.org/?probe=fc0dedbb3c) | Aug 05, 2021 |
| Gigabyte      | H81M-S2V                    | [10e9ef3d45](https://linux-hardware.org/?probe=10e9ef3d45) | Aug 05, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [8a70054744](https://linux-hardware.org/?probe=8a70054744) | Aug 04, 2021 |
| AMD           | 970A-D3                     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| HP            | 3047h                       | [6294617672](https://linux-hardware.org/?probe=6294617672) | Aug 03, 2021 |
| ASRock        | FM2A68M-HD+                 | [a7bdbd8ebe](https://linux-hardware.org/?probe=a7bdbd8ebe) | Aug 03, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [55cd593df1](https://linux-hardware.org/?probe=55cd593df1) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| MSI           | 760GM-P23                   | [93b6f212af](https://linux-hardware.org/?probe=93b6f212af) | Aug 02, 2021 |
| Supermicro    | X11SSH-F                    | [641e4fd8ce](https://linux-hardware.org/?probe=641e4fd8ce) | Aug 02, 2021 |
| ASRock        | H310CM-DVS                  | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek       | P5QL-E                      | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| ASUSTek       | A88X-PRO                    | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP            | 2187 A01                    | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Gigabyte      | 970A-DS3P                   | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| ASRock        | J1900D2Y                    | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell          | 0WVYMC A00                  | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| ASRock        | Z370M-ITX/ac                | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| MSI           | Z490-A PRO                  | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| MSI           | Q45MDO                      | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| MSI           | Q45MDO                      | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| Dell          | 0TY915                      | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek       | LEONITE                     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn       | 2AA9                        | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| ASRock        | B85M Pro4                   | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| ASRock        | FM2A88X Extreme6+           | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| ECS           | H61H2-M12                   | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| MSI           | B450M PRO-VDH PLUS          | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| Gigabyte      | H61M-DS2                    | [21c6bb9dde](https://linux-hardware.org/?probe=21c6bb9dde) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| Shuttle       | FX79R                       | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| ASRockRack    | X570D4U-2L2T                | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| ASRock        | B450M-HDV R4.0              | [72032bc046](https://linux-hardware.org/?probe=72032bc046) | Jul 27, 2021 |
| ASUSTek       | A88X-PLUS/USB               | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock        | N68C-GS FX                  | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek       | PRIME Z490-P                | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell          | 0X8DXD A00                  | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek       | M4A785D-M PRO               | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn       | 915MH Series                | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell          | 0WMJ54 A01                  | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
| Dell          | 0M863N A00                  | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| ASRock        | Z97 Pro3                    | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| MSI           | Z370 SLI PLUS               | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP            | 2B38                        | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | 970 Pro3 R2.0               | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASRock        | X570 Steel Legend           | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| Dell          | 0Y1057                      | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| HP            | 158A                        | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| HP            | 158A                        | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Protectli     | FW6                         | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [d3a887bf62](https://linux-hardware.org/?probe=d3a887bf62) | Jul 22, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [c3aac7e847](https://linux-hardware.org/?probe=c3aac7e847) | Jul 22, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [eeb04ca8d9](https://linux-hardware.org/?probe=eeb04ca8d9) | Jul 22, 2021 |
| Gigabyte      | B450M S2H V2                | [650e0a4954](https://linux-hardware.org/?probe=650e0a4954) | Jul 21, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| HP            | ProLiant MicroServer        | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| Gigabyte      | H61M-DS2                    | [be4679a65b](https://linux-hardware.org/?probe=be4679a65b) | Jul 14, 2021 |
| MSI           | A68HM-E33 V2                | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| ASUSTek       | PRIME B450M-K               | [8691cb3cb9](https://linux-hardware.org/?probe=8691cb3cb9) | Jul 12, 2021 |
| Huanan        | X99-F8 V2.0                 | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| ASRock        | H470M-HVS                   | [145ca872cf](https://linux-hardware.org/?probe=145ca872cf) | Jul 09, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| ASRock        | H470M-HVS                   | [5ab6c73674](https://linux-hardware.org/?probe=5ab6c73674) | Jul 08, 2021 |
| HP            | 2215                        | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| Gigabyte      | H61M-DS2                    | [c80bd2ff96](https://linux-hardware.org/?probe=c80bd2ff96) | Jul 05, 2021 |
| Gigabyte      | B85M-D3H                    | [e8da9b3b84](https://linux-hardware.org/?probe=e8da9b3b84) | Jul 05, 2021 |
| MSI           | MS-6712                     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| ASRock        | H77 Pro4-M                  | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| ASUSTek       | H81M-PLUS                   | [4ff716ad3a](https://linux-hardware.org/?probe=4ff716ad3a) | Jul 02, 2021 |
| Gigabyte      | AX370-Gaming K7             | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| Intel         | DG41RQ AAE54511-205         | [51edb744b9](https://linux-hardware.org/?probe=51edb744b9) | Jun 29, 2021 |
| MSI           | B85M-G43                    | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| Huanan        | X99-8M-F V1.1               | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Gigabyte      | H61M-DS2                    | [25956c35fb](https://linux-hardware.org/?probe=25956c35fb) | Jun 24, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| ASUSTek       | H110M-R                     | [f952173995](https://linux-hardware.org/?probe=f952173995) | Jun 23, 2021 |
| Gigabyte      | B85M-D2V                    | [25f911e59c](https://linux-hardware.org/?probe=25f911e59c) | Jun 23, 2021 |
| Gigabyte      | B360M H                     | [fcddb198ec](https://linux-hardware.org/?probe=fcddb198ec) | Jun 22, 2021 |
| Gigabyte      | B85M-D2V                    | [a719f039de](https://linux-hardware.org/?probe=a719f039de) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [16cf7bfb30](https://linux-hardware.org/?probe=16cf7bfb30) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| MSI           | B450M MORTAR MAX            | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| Acer          | H11H4-AI V:1.0              | [19fb8aa218](https://linux-hardware.org/?probe=19fb8aa218) | Jun 18, 2021 |
| Acer          | H11H4-AI V:1.0              | [a1f50d7038](https://linux-hardware.org/?probe=a1f50d7038) | Jun 18, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [1dc449cb66](https://linux-hardware.org/?probe=1dc449cb66) | Jun 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [6511e56d8f](https://linux-hardware.org/?probe=6511e56d8f) | Jun 16, 2021 |
| Gigabyte      | B360M H                     | [44fd3744da](https://linux-hardware.org/?probe=44fd3744da) | Jun 16, 2021 |
| ASUSTek       | P7H55                       | [c8abc22ac7](https://linux-hardware.org/?probe=c8abc22ac7) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-A               | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| ASUSTek       | P9X79                       | [dc6ae81a40](https://linux-hardware.org/?probe=dc6ae81a40) | Jun 11, 2021 |
| ASUSTek       | P9X79                       | [359862901e](https://linux-hardware.org/?probe=359862901e) | Jun 11, 2021 |
| QIYIDA        | X99-H9 V2.0                 | [b081ed3973](https://linux-hardware.org/?probe=b081ed3973) | Jun 11, 2021 |
| Dell          | 0Y7WYT A00                  | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| Gigabyte      | H61M-S2PV                   | [50a33d0c01](https://linux-hardware.org/?probe=50a33d0c01) | Jun 09, 2021 |
| ASUSTek       | P5QL-CM                     | [2eb12a165a](https://linux-hardware.org/?probe=2eb12a165a) | Jun 09, 2021 |
| ASRock        | B450M Pro4                  | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| Gigabyte      | P43-ES3G                    | [86c3abf0e6](https://linux-hardware.org/?probe=86c3abf0e6) | Jun 07, 2021 |
| ASUSTek       | B85M-G                      | [15fdd98402](https://linux-hardware.org/?probe=15fdd98402) | Jun 07, 2021 |
| ASUSTek       | PRIME A320M-K               | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| ASRock        | B450M Pro4                  | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| ASUSTek       | M4A88T-M/USB3               | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Gigabyte      | H61M-DS2                    | [f543bd7919](https://linux-hardware.org/?probe=f543bd7919) | Jun 02, 2021 |
| Dell          | 0YXT71 A02                  | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| Intel         | DP965LT AAD41694-209        | [64b76f3b3d](https://linux-hardware.org/?probe=64b76f3b3d) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| Gigabyte      | H61M-DS2                    | [446457dc79](https://linux-hardware.org/?probe=446457dc79) | Jun 01, 2021 |
| ASUSTek       | P5QL-CM                     | [53e36afc53](https://linux-hardware.org/?probe=53e36afc53) | Jun 01, 2021 |
| Intel         | DG965RY AAD41691-206        | [1b04d7a76f](https://linux-hardware.org/?probe=1b04d7a76f) | Jun 01, 2021 |
| Medion        | MS-7616                     | [c3730db7dd](https://linux-hardware.org/?probe=c3730db7dd) | May 31, 2021 |
| ASUSTek       | P7H55                       | [ac572ef424](https://linux-hardware.org/?probe=ac572ef424) | May 31, 2021 |
| ASUSTek       | P5B-Deluxe                  | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| Gigabyte      | H81M-S2V                    | [e00920532d](https://linux-hardware.org/?probe=e00920532d) | May 27, 2021 |
| MSI           | B250M BAZOOKA               | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| Gigabyte      | H81M-S1                     | [07fcf530f1](https://linux-hardware.org/?probe=07fcf530f1) | May 24, 2021 |
| MSI           | B450I GAMING PLUS AC        | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| ASRock        | A320M-HDV R3.0              | [8947349c20](https://linux-hardware.org/?probe=8947349c20) | May 21, 2021 |
| Gigabyte      | H81M-S2V                    | [95f4bad7b5](https://linux-hardware.org/?probe=95f4bad7b5) | May 20, 2021 |
| Gigabyte      | Z170X-GamingG1              | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| ASRock        | H61M-VG4                    | [f2d7c64e1c](https://linux-hardware.org/?probe=f2d7c64e1c) | May 18, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [b471b7cf95](https://linux-hardware.org/?probe=b471b7cf95) | May 18, 2021 |
| ASRock        | H61M-VG4                    | [1699c8eab5](https://linux-hardware.org/?probe=1699c8eab5) | May 14, 2021 |
| ASRock        | H61M-VG4                    | [bd2a3417a0](https://linux-hardware.org/?probe=bd2a3417a0) | May 14, 2021 |
| ASRock        | H61M-VG4                    | [3a27d20178](https://linux-hardware.org/?probe=3a27d20178) | May 14, 2021 |
| ASRock        | H61M-VG4                    | [17ff2add7a](https://linux-hardware.org/?probe=17ff2add7a) | May 14, 2021 |
| Gigabyte      | A320M-S2H-CF                | [07ea2a4b8e](https://linux-hardware.org/?probe=07ea2a4b8e) | May 14, 2021 |
| ASRock        | H61M-VG4                    | [823bbbb4ed](https://linux-hardware.org/?probe=823bbbb4ed) | May 12, 2021 |
| ASRock        | G31M-VS2                    | [af6e17ac8c](https://linux-hardware.org/?probe=af6e17ac8c) | May 12, 2021 |
| ASRock        | B450M Pro4-F                | [f6d2299c81](https://linux-hardware.org/?probe=f6d2299c81) | May 12, 2021 |
| Gigabyte      | H61M-DS2                    | [380bf2eacc](https://linux-hardware.org/?probe=380bf2eacc) | May 11, 2021 |
| Gigabyte      | Z77-D3H                     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Gigabyte      | H81M-DS2                    | [589d53b7ce](https://linux-hardware.org/?probe=589d53b7ce) | May 11, 2021 |
| Lenovo        | MAHOBAY                     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| Foxconn       | H61MXL/H61MXL-K             | [0c87980ed4](https://linux-hardware.org/?probe=0c87980ed4) | Apr 29, 2021 |
| Pegatron      | C15B                        | [54d1d5cde0](https://linux-hardware.org/?probe=54d1d5cde0) | Apr 27, 2021 |
| Biostar       | B450MH                      | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| ASRock        | 970M Pro3                   | [89d9898d88](https://linux-hardware.org/?probe=89d9898d88) | Apr 26, 2021 |
| HP            | 3399                        | [4085344b20](https://linux-hardware.org/?probe=4085344b20) | Apr 26, 2021 |
| ASUSTek       | P8Z77-M                     | [8495ecf36e](https://linux-hardware.org/?probe=8495ecf36e) | Apr 26, 2021 |
| ASUSTek       | PRIME A320M-K               | [1c397e42c6](https://linux-hardware.org/?probe=1c397e42c6) | Apr 23, 2021 |
| ASUSTek       | PRIME B450M-K               | [fc24c1c56f](https://linux-hardware.org/?probe=fc24c1c56f) | Apr 23, 2021 |
| HP            | 3399                        | [a265b73c37](https://linux-hardware.org/?probe=a265b73c37) | Apr 22, 2021 |
| Gigabyte      | H410M S2H                   | [88f270d1d0](https://linux-hardware.org/?probe=88f270d1d0) | Apr 22, 2021 |
| Gigabyte      | A320M-S2H-CF                | [6cdd8afad1](https://linux-hardware.org/?probe=6cdd8afad1) | Apr 19, 2021 |
| ECS           | G31T-M7                     | [4e1e8d1c1a](https://linux-hardware.org/?probe=4e1e8d1c1a) | Apr 19, 2021 |
| ECS           | G31T-M7                     | [2ffcd0d78d](https://linux-hardware.org/?probe=2ffcd0d78d) | Apr 19, 2021 |
| Gigabyte      | EG41MF-US2H                 | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |
| HP            | 3399                        | [ae0ed46819](https://linux-hardware.org/?probe=ae0ed46819) | Apr 16, 2021 |
| MSI           | G41M-P28                    | [0b714b1814](https://linux-hardware.org/?probe=0b714b1814) | Apr 16, 2021 |
| Intel         | DQ45CB AAE30148-206         | [6a9f891230](https://linux-hardware.org/?probe=6a9f891230) | Apr 15, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [7a1d829bbb](https://linux-hardware.org/?probe=7a1d829bbb) | Apr 14, 2021 |
| Gigabyte      | H81M-S2V                    | [97a320e9df](https://linux-hardware.org/?probe=97a320e9df) | Apr 14, 2021 |
| MSI           | H110M PRO-D                 | [9f79d5f548](https://linux-hardware.org/?probe=9f79d5f548) | Apr 09, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [2f2f027581](https://linux-hardware.org/?probe=2f2f027581) | Apr 07, 2021 |
| ASUSTek       | P5B                         | [e6f18312ca](https://linux-hardware.org/?probe=e6f18312ca) | Apr 07, 2021 |
| Gigabyte      | G41M-ES2L                   | [1ae4d948e8](https://linux-hardware.org/?probe=1ae4d948e8) | Apr 06, 2021 |
| ECS           | G31T-M9                     | [769cb653f7](https://linux-hardware.org/?probe=769cb653f7) | Apr 02, 2021 |
| MSI           | H110M PRO-VD                | [6ba14141a6](https://linux-hardware.org/?probe=6ba14141a6) | Apr 01, 2021 |
| MSI           | H110M PRO-VD                | [f2e276c03d](https://linux-hardware.org/?probe=f2e276c03d) | Apr 01, 2021 |
| Intel         | DG33FB AAD81072-303         | [df4527f66c](https://linux-hardware.org/?probe=df4527f66c) | Mar 31, 2021 |
| ASUSTek       | P5K-VM                      | [4c297474dc](https://linux-hardware.org/?probe=4c297474dc) | Mar 30, 2021 |
| ASUSTek       | Z87I-DELUXE                 | [34a8087893](https://linux-hardware.org/?probe=34a8087893) | Mar 22, 2021 |
| Lenovo        | 3706 SDK0J40700 WIN 3258... | [3876e9ed84](https://linux-hardware.org/?probe=3876e9ed84) | Mar 21, 2021 |
| ASUSTek       | H81M-K                      | [be20eafb4f](https://linux-hardware.org/?probe=be20eafb4f) | Mar 20, 2021 |
| ASUSTek       | H81M-K                      | [0dd442a763](https://linux-hardware.org/?probe=0dd442a763) | Mar 19, 2021 |
| HPE           | ProLiant MicroServer Gen... | [2f3f591fd0](https://linux-hardware.org/?probe=2f3f591fd0) | Mar 10, 2021 |
| Intel         | DG31PR AAD97573-301         | [09e15a8c00](https://linux-hardware.org/?probe=09e15a8c00) | Mar 04, 2021 |
| MSI           | MS-7329                     | [d67a4df7d0](https://linux-hardware.org/?probe=d67a4df7d0) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | [96d6904297](https://linux-hardware.org/?probe=96d6904297) | Feb 01, 2021 |
| Dell          | 0KWVT8 A02                  | [4bff426962](https://linux-hardware.org/?probe=4bff426962) | Jan 31, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | [5d23694899](https://linux-hardware.org/?probe=5d23694899) | Jan 24, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [04b6596686](https://linux-hardware.org/?probe=04b6596686) | Jan 13, 2021 |
| Dell          | 0K83V0 A00                  | [54858a0cb0](https://linux-hardware.org/?probe=54858a0cb0) | Jan 06, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [8d9dbecbba](https://linux-hardware.org/?probe=8d9dbecbba) | Aug 11, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.0-8-amd64                 | 158      | 41.04%  |
| 5.10.0-7-amd64                 | 100      | 25.97%  |
| 5.10.0-2-amd64                 | 76       | 19.74%  |
| 5.10.0-6-amd64                 | 13       | 3.38%   |
| 5.10.0-4-amd64                 | 4        | 1.04%   |
| 5.11.22-1-pve                  | 3        | 0.78%   |
| 5.10.0-8-686-pae               | 3        | 0.78%   |
| 5.11.22-2-pve                  | 2        | 0.52%   |
| 5.10.0-8-rt-amd64              | 2        | 0.52%   |
| 5.10.0-8-686                   | 2        | 0.52%   |
| 5.10.0-5-amd64                 | 2        | 0.52%   |
| 5.10.0-3-amd64                 | 2        | 0.52%   |
| 5.8.0-3-amd64                  | 1        | 0.26%   |
| 5.13.8-gnu                     | 1        | 0.26%   |
| 5.13.4                         | 1        | 0.26%   |
| 5.13.1a                        | 1        | 0.26%   |
| 5.13.13-arch1-1                | 1        | 0.26%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1        | 0.26%   |
| 5.12.18-amd64-desktop          | 1        | 0.26%   |
| 5.11.22-3-pve                  | 1        | 0.26%   |
| 5.11.0-21.1-liquorix-amd64     | 1        | 0.26%   |
| 5.11.0-16.1-liquorix-amd64     | 1        | 0.26%   |
| 5.10.46custom                  | 1        | 0.26%   |
| 5.10.42+truenas                | 1        | 0.26%   |
| 5.10.38-falcot                 | 1        | 0.26%   |
| 5.10.10                        | 1        | 0.26%   |
| 5.10.0-7-686-pae               | 1        | 0.26%   |
| 5.10.0-1-amd64                 | 1        | 0.26%   |
| 5.1.0-20.1-liquorix-amd64      | 1        | 0.26%   |
| 4.19.0-9-686-pae               | 1        | 0.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 353      | 94.39%  |
| 5.11.22 | 6        | 1.6%    |
| 5.11.0  | 2        | 0.53%   |
| 5.8.0   | 1        | 0.27%   |
| 5.13.8  | 1        | 0.27%   |
| 5.13.4  | 1        | 0.27%   |
| 5.13.13 | 1        | 0.27%   |
| 5.13.1  | 1        | 0.27%   |
| 5.13.0  | 1        | 0.27%   |
| 5.12.18 | 1        | 0.27%   |
| 5.10.46 | 1        | 0.27%   |
| 5.10.42 | 1        | 0.27%   |
| 5.10.38 | 1        | 0.27%   |
| 5.10.10 | 1        | 0.27%   |
| 5.1.0   | 1        | 0.27%   |
| 4.19.0  | 1        | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 357      | 95.45%  |
| 5.11    | 8        | 2.14%   |
| 5.13    | 5        | 1.34%   |
| 5.8     | 1        | 0.27%   |
| 5.12    | 1        | 0.27%   |
| 5.1     | 1        | 0.27%   |
| 4.19    | 1        | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 366      | 97.86%  |
| i686   | 8        | 2.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 161      | 42.71%  |
| GNOME            | 63       | 16.71%  |
| KDE5             | 42       | 11.14%  |
| XFCE             | 27       | 7.16%   |
| MATE             | 21       | 5.57%   |
| Cinnamon         | 12       | 3.18%   |
| i3               | 8        | 2.12%   |
| X-Cinnamon       | 7        | 1.86%   |
| LXQt             | 7        | 1.86%   |
| LXDE             | 7        | 1.86%   |
| Trinity          | 6        | 1.59%   |
| KDE              | 6        | 1.59%   |
| lightdm-xsession | 2        | 0.53%   |
| GNOME Flashback  | 2        | 0.53%   |
| Budgie           | 2        | 0.53%   |
| sway             | 1        | 0.27%   |
| openbox          | 1        | 0.27%   |
| GNUstep          | 1        | 0.27%   |
| awesome          | 1        | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 173      | 46.01%  |
| Unknown | 137      | 36.44%  |
| Wayland | 34       | 9.04%   |
| Tty     | 32       | 8.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 191      | 50.93%  |
| TDM     | 71       | 18.93%  |
| GDM     | 48       | 12.8%   |
| SDDM    | 41       | 10.93%  |
| LightDM | 18       | 4.8%    |
| SLiM    | 3        | 0.8%    |
| XDM     | 1        | 0.27%   |
| NODM    | 1        | 0.27%   |
| GDM3    | 1        | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 140      | 37.43%  |
| en_US   | 116      | 31.02%  |
| fr_FR   | 17       | 4.55%   |
| en_GB   | 17       | 4.55%   |
| de_DE   | 11       | 2.94%   |
| Unknown | 10       | 2.67%   |
| pt_BR   | 9        | 2.41%   |
| es_ES   | 6        | 1.6%    |
| en_AU   | 5        | 1.34%   |
| C       | 5        | 1.34%   |
| pl_PL   | 4        | 1.07%   |
| nl_BE   | 4        | 1.07%   |
| en_CA   | 3        | 0.8%    |
| ja_JP   | 2        | 0.53%   |
| hu_HU   | 2        | 0.53%   |
| uk_UA   | 1        | 0.27%   |
| tr_TR   | 1        | 0.27%   |
| sv_SE   | 1        | 0.27%   |
| sr_RS   | 1        | 0.27%   |
| ru_UA   | 1        | 0.27%   |
| ro_RO   | 1        | 0.27%   |
| pt_PT   | 1        | 0.27%   |
| nl_NL   | 1        | 0.27%   |
| it_IT   | 1        | 0.27%   |
| hr_HR   | 1        | 0.27%   |
| es_VE   | 1        | 0.27%   |
| es_US   | 1        | 0.27%   |
| es_MX   | 1        | 0.27%   |
| es_AR   | 1        | 0.27%   |
| en_PH   | 1        | 0.27%   |
| en_NZ   | 1        | 0.27%   |
| en_IN   | 1        | 0.27%   |
| en_IE   | 1        | 0.27%   |
| en_HK   | 1        | 0.27%   |
| de_CH   | 1        | 0.27%   |
| de_AT   | 1        | 0.27%   |
| cs_CZ   | 1        | 0.27%   |
| bg_BG   | 1        | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 241      | 64.1%   |
| EFI  | 135      | 35.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 187      | 50%     |
| Overlay | 147      | 39.3%   |
| Btrfs   | 21       | 5.61%   |
| Ext3    | 6        | 1.6%    |
| Zfs     | 5        | 1.34%   |
| Xfs     | 5        | 1.34%   |
| Rootfs  | 1        | 0.27%   |
| Ext2    | 1        | 0.27%   |
| Unknown | 1        | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 172      | 45.74%  |
| GPT     | 168      | 44.68%  |
| Unknown | 36       | 9.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 312      | 83.2%   |
| Yes       | 63       | 16.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 191      | 50.93%  |
| No        | 184      | 49.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 110      | 29.41%  |
| Gigabyte Technology | 67       | 17.91%  |
| ASRock              | 65       | 17.38%  |
| MSI                 | 32       | 8.56%   |
| Dell                | 22       | 5.88%   |
| Hewlett-Packard     | 19       | 5.08%   |
| Intel               | 14       | 3.74%   |
| ECS                 | 7        | 1.87%   |
| Lenovo              | 5        | 1.34%   |
| Fujitsu             | 5        | 1.34%   |
| Foxconn             | 4        | 1.07%   |
| Supermicro          | 2        | 0.53%   |
| Semp Toshiba        | 2        | 0.53%   |
| Pegatron            | 2        | 0.53%   |
| Huanan              | 2        | 0.53%   |
| Biostar             | 2        | 0.53%   |
| Unknown             | 2        | 0.53%   |
| Shuttle             | 1        | 0.27%   |
| QIYIDA              | 1        | 0.27%   |
| Protectli           | 1        | 0.27%   |
| NC9VL               | 1        | 0.27%   |
| Medion              | 1        | 0.27%   |
| HPE                 | 1        | 0.27%   |
| HARDKERNEL          | 1        | 0.27%   |
| Fujitsu Siemens     | 1        | 0.27%   |
| ASRockRack          | 1        | 0.27%   |
| AOpen               | 1        | 0.27%   |
| Acer                | 1        | 0.27%   |
| AAEON               | 1        | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 27       | 7.22%   |
| ASRock H470M-HVS               | 20       | 5.35%   |
| Gigabyte H81M-S2V              | 6        | 1.6%    |
| ASRock H61M-VG4                | 6        | 1.6%    |
| Gigabyte H61M-DS2 REV 1.2      | 4        | 1.07%   |
| ASUS P8H61-M LX3 R2.0          | 4        | 1.07%   |
| MSI MS-7996                    | 3        | 0.8%    |
| Intel Pro, Std, Elt Series     | 3        | 0.8%    |
| Gigabyte Z77-D3H               | 3        | 0.8%    |
| Gigabyte B550I AORUS PRO AX    | 3        | 0.8%    |
| Gigabyte A320M-S2H             | 3        | 0.8%    |
| Fujitsu ESPRIMO P720           | 3        | 0.8%    |
| ASUS PRIME A320M-K             | 3        | 0.8%    |
| ASRock B450M Pro4              | 3        | 0.8%    |
| Semp Toshiba STI               | 2        | 0.53%   |
| MSI MS-7A71                    | 2        | 0.53%   |
| MSI MS-7A70                    | 2        | 0.53%   |
| MSI MS-7721                    | 2        | 0.53%   |
| Intel DN2820FYK H24582-201     | 2        | 0.53%   |
| HP Z620 Workstation            | 2        | 0.53%   |
| Gigabyte Z370 AORUS Gaming 5   | 2        | 0.53%   |
| Gigabyte X570 I AORUS PRO WIFI | 2        | 0.53%   |
| Gigabyte B360M H               | 2        | 0.53%   |
| Gigabyte 970A-DS3P             | 2        | 0.53%   |
| ECS H61H2-M13                  | 2        | 0.53%   |
| ECS G31T-M9                    | 2        | 0.53%   |
| Dell OptiPlex 760              | 2        | 0.53%   |
| Dell OptiPlex 7010             | 2        | 0.53%   |
| Dell OptiPlex 3020             | 2        | 0.53%   |
| ASUS TUF GAMING X570-PRO       | 2        | 0.53%   |
| ASUS ROG STRIX B450-F GAMING   | 2        | 0.53%   |
| ASUS PRIME B550-PLUS           | 2        | 0.53%   |
| ASUS PRIME B450M-K             | 2        | 0.53%   |
| ASUS PRIME B450M-A             | 2        | 0.53%   |
| ASUS P5QL-CM                   | 2        | 0.53%   |
| ASUS P5KPL-CM                  | 2        | 0.53%   |
| Unknown                        | 2        | 0.53%   |
| Supermicro SYS-5038MA-H24TRF   | 1        | 0.27%   |
| Supermicro SYS-5019S-MR        | 1        | 0.27%   |
| Shuttle SX79R                  | 1        | 0.27%   |
| QIYIDA X99-H9 V2.0             | 1        | 0.27%   |
| Protectli FW6                  | 1        | 0.27%   |
| Pegatron NP267AA-A2L e9180f    | 1        | 0.27%   |
| Pegatron C15B                  | 1        | 0.27%   |
| NC9VL 1.0                      | 1        | 0.27%   |
| MSI MS-7C94                    | 1        | 0.27%   |
| MSI MS-7C84                    | 1        | 0.27%   |
| MSI MS-7C75                    | 1        | 0.27%   |
| MSI MS-7C56                    | 1        | 0.27%   |
| MSI MS-7C35                    | 1        | 0.27%   |
| MSI MS-7C02                    | 1        | 0.27%   |
| MSI MS-7B92                    | 1        | 0.27%   |
| MSI MS-7B89                    | 1        | 0.27%   |
| MSI MS-7B84                    | 1        | 0.27%   |
| MSI MS-7B79                    | 1        | 0.27%   |
| MSI MS-7B46                    | 1        | 0.27%   |
| MSI MS-7B09                    | 1        | 0.27%   |
| MSI MS-7A40                    | 1        | 0.27%   |
| MSI MS-7A38                    | 1        | 0.27%   |
| MSI MS-7995                    | 1        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All                     | 27       | 7.22%   |
| ASUS PRIME                   | 22       | 5.88%   |
| ASRock H470M-HVS             | 20       | 5.35%   |
| Dell OptiPlex                | 13       | 3.48%   |
| ASUS ROG                     | 12       | 3.21%   |
| HP Compaq                    | 6        | 1.6%    |
| Gigabyte H81M-S2V            | 6        | 1.6%    |
| Dell Precision               | 6        | 1.6%    |
| ASRock H61M-VG4              | 6        | 1.6%    |
| Gigabyte H61M-DS2            | 4        | 1.07%   |
| Gigabyte A320M-S2H           | 4        | 1.07%   |
| Fujitsu ESPRIMO              | 4        | 1.07%   |
| ASUS TUF                     | 4        | 1.07%   |
| ASUS P8H61-M                 | 4        | 1.07%   |
| ASRock B450M                 | 4        | 1.07%   |
| MSI MS-7996                  | 3        | 0.8%    |
| Lenovo ThinkCentre           | 3        | 0.8%    |
| Intel Pro                    | 3        | 0.8%    |
| Gigabyte Z77-D3H             | 3        | 0.8%    |
| Gigabyte B550I               | 3        | 0.8%    |
| ASRock Z97                   | 3        | 0.8%    |
| Semp Toshiba STI             | 2        | 0.53%   |
| MSI MS-7A71                  | 2        | 0.53%   |
| MSI MS-7A70                  | 2        | 0.53%   |
| MSI MS-7721                  | 2        | 0.53%   |
| Intel DN2820FYK              | 2        | 0.53%   |
| HP Z620                      | 2        | 0.53%   |
| HP ProLiant                  | 2        | 0.53%   |
| Gigabyte Z370                | 2        | 0.53%   |
| Gigabyte X570                | 2        | 0.53%   |
| Gigabyte B450M               | 2        | 0.53%   |
| Gigabyte B360M               | 2        | 0.53%   |
| Gigabyte 970A-DS3P           | 2        | 0.53%   |
| ECS H61H2-M13                | 2        | 0.53%   |
| ECS G31T-M9                  | 2        | 0.53%   |
| Dell Inspiron                | 2        | 0.53%   |
| ASUS Pro                     | 2        | 0.53%   |
| ASUS P7H55-M                 | 2        | 0.53%   |
| ASUS P5QL-CM                 | 2        | 0.53%   |
| ASUS P5KPL-CM                | 2        | 0.53%   |
| ASUS P5B                     | 2        | 0.53%   |
| ASRock X570                  | 2        | 0.53%   |
| ASRock H77                   | 2        | 0.53%   |
| Unknown                      | 2        | 0.53%   |
| Supermicro SYS-5038MA-H24TRF | 1        | 0.27%   |
| Supermicro SYS-5019S-MR      | 1        | 0.27%   |
| Shuttle SX79R                | 1        | 0.27%   |
| QIYIDA X99-H9                | 1        | 0.27%   |
| Protectli FW6                | 1        | 0.27%   |
| Pegatron NP267AA-A2L         | 1        | 0.27%   |
| Pegatron C15B                | 1        | 0.27%   |
| NC9VL 1.0                    | 1        | 0.27%   |
| MSI MS-7C94                  | 1        | 0.27%   |
| MSI MS-7C84                  | 1        | 0.27%   |
| MSI MS-7C75                  | 1        | 0.27%   |
| MSI MS-7C56                  | 1        | 0.27%   |
| MSI MS-7C35                  | 1        | 0.27%   |
| MSI MS-7C02                  | 1        | 0.27%   |
| MSI MS-7B92                  | 1        | 0.27%   |
| MSI MS-7B89                  | 1        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 49       | 13.1%   |
| 2021 | 47       | 12.57%  |
| 2014 | 39       | 10.43%  |
| 2018 | 38       | 10.16%  |
| 2019 | 36       | 9.63%   |
| 2015 | 24       | 6.42%   |
| 2013 | 21       | 5.61%   |
| 2010 | 20       | 5.35%   |
| 2009 | 20       | 5.35%   |
| 2016 | 18       | 4.81%   |
| 2012 | 18       | 4.81%   |
| 2011 | 15       | 4.01%   |
| 2008 | 10       | 2.67%   |
| 2017 | 8        | 2.14%   |
| 2007 | 5        | 1.34%   |
| 2006 | 3        | 0.8%    |
| 2005 | 1        | 0.27%   |
| 2004 | 1        | 0.27%   |
| 2001 | 1        | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 374      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 371      | 99.2%   |
| Enabled  | 3        | 0.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 373      | 99.73%  |
| Yes  | 1        | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 77       | 20.53%  |
| 3.01-4.0        | 64       | 17.07%  |
| 8.01-16.0       | 64       | 17.07%  |
| 32.01-64.0      | 63       | 16.8%   |
| 4.01-8.0        | 46       | 12.27%  |
| 64.01-256.0     | 25       | 6.67%   |
| 1.01-2.0        | 19       | 5.07%   |
| 2.01-3.0        | 6        | 1.6%    |
| 24.01-32.0      | 5        | 1.33%   |
| More than 256.0 | 3        | 0.8%    |
| 0.51-1.0        | 2        | 0.53%   |
| 0.01-0.5        | 1        | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.51-1.0    | 147      | 38.68%  |
| 1.01-2.0    | 49       | 12.89%  |
| 4.01-8.0    | 47       | 12.37%  |
| 2.01-3.0    | 44       | 11.58%  |
| 3.01-4.0    | 41       | 10.79%  |
| 8.01-16.0   | 17       | 4.47%   |
| 0.01-0.5    | 16       | 4.21%   |
| 16.01-24.0  | 10       | 2.63%   |
| 24.01-32.0  | 4        | 1.05%   |
| 32.01-64.0  | 3        | 0.79%   |
| 64.01-256.0 | 2        | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 179      | 47.86%  |
| 2      | 92       | 24.6%   |
| 3      | 44       | 11.76%  |
| 4      | 25       | 6.68%   |
| 5      | 14       | 3.74%   |
| 8      | 5        | 1.34%   |
| 6      | 5        | 1.34%   |
| 9      | 3        | 0.8%    |
| 10     | 2        | 0.53%   |
| 0      | 2        | 0.53%   |
| 13     | 1        | 0.27%   |
| 12     | 1        | 0.27%   |
| 7      | 1        | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 234      | 62.57%  |
| Yes       | 140      | 37.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 372      | 99.47%  |
| No        | 2        | 0.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 285      | 76.2%   |
| Yes       | 89       | 23.8%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 295      | 78.88%  |
| Yes       | 79       | 21.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| Russia                 | 142      | 37.87%  |
| USA                    | 61       | 16.27%  |
| France                 | 21       | 5.6%    |
| Germany                | 19       | 5.07%   |
| UK                     | 15       | 4%      |
| Ukraine                | 12       | 3.2%    |
| Spain                  | 10       | 2.67%   |
| Brazil                 | 9        | 2.4%    |
| Poland                 | 8        | 2.13%   |
| Belgium                | 6        | 1.6%    |
| Australia              | 6        | 1.6%    |
| Sweden                 | 4        | 1.07%   |
| Netherlands            | 4        | 1.07%   |
| Mexico                 | 4        | 1.07%   |
| Canada                 | 4        | 1.07%   |
| Bulgaria               | 4        | 1.07%   |
| Portugal               | 3        | 0.8%    |
| Norway                 | 3        | 0.8%    |
| Italy                  | 3        | 0.8%    |
| Czechia                | 3        | 0.8%    |
| Austria                | 3        | 0.8%    |
| Argentina              | 3        | 0.8%    |
| Venezuela              | 2        | 0.53%   |
| Switzerland            | 2        | 0.53%   |
| Singapore              | 2        | 0.53%   |
| Romania                | 2        | 0.53%   |
| Japan                  | 2        | 0.53%   |
| Hungary                | 2        | 0.53%   |
| Finland                | 2        | 0.53%   |
| Turkey                 | 1        | 0.27%   |
| Syria                  | 1        | 0.27%   |
| Serbia                 | 1        | 0.27%   |
| New Zealand            | 1        | 0.27%   |
| New Caledonia          | 1        | 0.27%   |
| Madagascar             | 1        | 0.27%   |
| Ireland                | 1        | 0.27%   |
| India                  | 1        | 0.27%   |
| Hong Kong              | 1        | 0.27%   |
| Greece                 | 1        | 0.27%   |
| Ecuador                | 1        | 0.27%   |
| Croatia                | 1        | 0.27%   |
| Bosnia and Herzegovina | 1        | 0.27%   |
| Bolivia                | 1        | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Voronezh             | 121      | 32.1%   |
| Portland             | 7        | 1.86%   |
| Ocala                | 6        | 1.59%   |
| Kyiv                 | 6        | 1.59%   |
| Lyon                 | 5        | 1.33%   |
| London               | 5        | 1.33%   |
| Sofia                | 4        | 1.06%   |
| Vienna               | 3        | 0.8%    |
| Stockholm            | 3        | 0.8%    |
| Moscow               | 3        | 0.8%    |
| Kalamazoo            | 3        | 0.8%    |
| Frankfort            | 3        | 0.8%    |
| Ensenada             | 3        | 0.8%    |
| Warsaw               | 2        | 0.53%   |
| St Petersburg        | 2        | 0.53%   |
| S??o Paulo           | 2        | 0.53%   |
| Saint-Denis          | 2        | 0.53%   |
| Perm                 | 2        | 0.53%   |
| Paris                | 2        | 0.53%   |
| New York             | 2        | 0.53%   |
| Las Vegas            | 2        | 0.53%   |
| Kharkiv              | 2        | 0.53%   |
| Iasi                 | 2        | 0.53%   |
| Herndon              | 2        | 0.53%   |
| Clitheroe            | 2        | 0.53%   |
| Berlin               | 2        | 0.53%   |
| Barcelona            | 2        | 0.53%   |
| Athens               | 2        | 0.53%   |
| Amsterdam            | 2        | 0.53%   |
| Érd                 | 1        | 0.27%   |
| Zastavka             | 1        | 0.27%   |
| Zagreb               | 1        | 0.27%   |
| Yuncos               | 1        | 0.27%   |
| Ypres                | 1        | 0.27%   |
| Yekaterinburg        | 1        | 0.27%   |
| Wroclaw              | 1        | 0.27%   |
| Woolloongabba        | 1        | 0.27%   |
| Woodstock            | 1        | 0.27%   |
| West Islip           | 1        | 0.27%   |
| Wenatchee            | 1        | 0.27%   |
| Waregem              | 1        | 0.27%   |
| Voerde               | 1        | 0.27%   |
| Vladivostok          | 1        | 0.27%   |
| Vladimir             | 1        | 0.27%   |
| V?�nissieux          | 1        | 0.27%   |
| Vandoeuvre-les-Nancy | 1        | 0.27%   |
| Vancouver            | 1        | 0.27%   |
| Valladolid           | 1        | 0.27%   |
| Valera               | 1        | 0.27%   |
| Vaasa                | 1        | 0.27%   |
| Ulyanovsk            | 1        | 0.27%   |
| Ufa                  | 1        | 0.27%   |
| Tyler                | 1        | 0.27%   |
| Turku                | 1        | 0.27%   |
| Trinidad             | 1        | 0.27%   |
| Toulouse             | 1        | 0.27%   |
| Torrox Costa         | 1        | 0.27%   |
| Thionville           | 1        | 0.27%   |
| Tai Kok Tsui         | 1        | 0.27%   |
| Sydney               | 1        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 123      | 191    | 19.84%  |
| WDC                 | 113      | 168    | 18.23%  |
| Samsung Electronics | 93       | 133    | 15%     |
| Toshiba             | 53       | 78     | 8.55%   |
| Kingston            | 39       | 47     | 6.29%   |
| Crucial             | 39       | 44     | 6.29%   |
| Hitachi             | 21       | 22     | 3.39%   |
| Netac               | 20       | 22     | 3.23%   |
| SanDisk             | 16       | 19     | 2.58%   |
| Intel               | 13       | 20     | 2.1%    |
| HGST                | 10       | 13     | 1.61%   |
| A-DATA Technology   | 7        | 10     | 1.13%   |
| PNY                 | 6        | 6      | 0.97%   |
| China               | 6        | 6      | 0.97%   |
| Unknown             | 5        | 5      | 0.81%   |
| SPCC                | 5        | 5      | 0.81%   |
| MAXTOR              | 5        | 5      | 0.81%   |
| OCZ                 | 3        | 3      | 0.48%   |
| Gigabyte Technology | 3        | 3      | 0.48%   |
| Corsair             | 3        | 3      | 0.48%   |
| Transcend           | 2        | 3      | 0.32%   |
| SABRENT             | 2        | 2      | 0.32%   |
| PLEXTOR             | 2        | 4      | 0.32%   |
| Phison Electronics  | 2        | 2      | 0.32%   |
| Phison              | 2        | 2      | 0.32%   |
| Patriot             | 2        | 2      | 0.32%   |
| Micron Technology   | 2        | 2      | 0.32%   |
| Intenso             | 2        | 3      | 0.32%   |
| Hewlett-Packard     | 2        | 3      | 0.32%   |
| Xinhaike            | 1        | 1      | 0.16%   |
| Team                | 1        | 1      | 0.16%   |
| T-FORCE             | 1        | 1      | 0.16%   |
| SK Hynix            | 1        | 6      | 0.16%   |
| PNY USB             | 1        | 1      | 0.16%   |
| Pioneer             | 1        | 1      | 0.16%   |
| NAS                 | 1        | 5      | 0.16%   |
| Mushkin             | 1        | 1      | 0.16%   |
| MaxDigital          | 1        | 2      | 0.16%   |
| LITEON              | 1        | 1      | 0.16%   |
| Lexar               | 1        | 1      | 0.16%   |
| KingDian            | 1        | 1      | 0.16%   |
| GOODRAM             | 1        | 1      | 0.16%   |
| Elite               | 1        | 2      | 0.16%   |
| DOGFISH             | 1        | 1      | 0.16%   |
| Apple               | 1        | 1      | 0.16%   |
| Apacer              | 1        | 1      | 0.16%   |
| 2-Power             | 1        | 1      | 0.16%   |
| 128MB               | 1        | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Toshiba HDWD110 1TB               | 23       | 3.19%   |
| Netac SSD 240GB                   | 20       | 2.78%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 19       | 2.64%   |
| Seagate ST500DM002-1BD142 500GB   | 14       | 1.94%   |
| Samsung SSD 860 EVO 1TB           | 9        | 1.25%   |
| Kingston SV300S37A120G 120GB SSD  | 9        | 1.25%   |
| Kingston SA400S37240G 240GB SSD   | 9        | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB    | 8        | 1.11%   |
| Seagate ST1000DM003-1ER162 1TB    | 8        | 1.11%   |
| Samsung SSD 970 EVO Plus 1TB      | 8        | 1.11%   |
| Samsung SSD 870 EVO 500GB         | 7        | 0.97%   |
| Samsung SSD 860 EVO 250GB         | 7        | 0.97%   |
| Kingston SA400S37120G 120GB SSD   | 7        | 0.97%   |
| Toshiba DT01ACA100 1TB            | 6        | 0.83%   |
| Toshiba DT01ACA050 500GB          | 6        | 0.83%   |
| Seagate ST4000DM004-2CV104 4TB    | 6        | 0.83%   |
| Samsung SSD 970 EVO Plus 500GB    | 6        | 0.83%   |
| Samsung SSD 970 EVO 500GB         | 6        | 0.83%   |
| Samsung SSD 850 EVO 500GB         | 6        | 0.83%   |
| Samsung SSD 850 EVO 250GB         | 6        | 0.83%   |
| Hitachi HDS721050CLA362 500GB     | 6        | 0.83%   |
| Crucial CT240BX500SSD1 240GB      | 6        | 0.83%   |
| Seagate ST2000DM001-1ER164 2TB    | 5        | 0.69%   |
| Samsung SSD 980 PRO 1TB           | 5        | 0.69%   |
| Crucial CT500MX500SSD1 500GB      | 5        | 0.69%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 4        | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB          | 4        | 0.56%   |
| Toshiba DT01ACA300 3TB            | 4        | 0.56%   |
| Toshiba DT01ACA200 2TB            | 4        | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB    | 4        | 0.56%   |
| Samsung SSD 860 EVO 500GB         | 4        | 0.56%   |
| Crucial CT480BX500SSD1 480GB      | 4        | 0.56%   |
| Crucial CT250MX500SSD1 250GB      | 4        | 0.56%   |
| WDC WDS500G3X0C-00SJG0 500GB      | 3        | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 3        | 0.42%   |
| WDC WD40EFRX-68N32N0 4TB          | 3        | 0.42%   |
| WDC WD20EFRX-68EUZN0 2TB          | 3        | 0.42%   |
| WDC WD10EZEX-00BN5A0 1TB          | 3        | 0.42%   |
| Seagate ST3000DM001-1CH166 3TB    | 3        | 0.42%   |
| Seagate Backup+ Hub BK 10TB       | 3        | 0.42%   |
| SanDisk SD8SBAT128G1122 128GB SSD | 3        | 0.42%   |
| MAXTOR STM3500320AS 500GB         | 3        | 0.42%   |
| Kingston SV300S37A240G 240GB SSD  | 3        | 0.42%   |
| Hitachi HUS724040ALE641 4TB       | 3        | 0.42%   |
| Crucial CT500P1SSD8 500GB         | 3        | 0.42%   |
| Crucial CT120BX500SSD1 120GB      | 3        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB       | 3        | 0.42%   |
| WDC WDS500G2B0C-00PXH0 500GB      | 2        | 0.28%   |
| WDC WDS100T1X0E-00AFY0 1TB        | 2        | 0.28%   |
| WDC WD5000AADS-00S9B0 500GB       | 2        | 0.28%   |
| WDC WD40EZRZ-00GXCB0 4TB          | 2        | 0.28%   |
| WDC WD3200AAJS-00L7A0 320GB       | 2        | 0.28%   |
| WDC WD20EZAZ-00GGJB0 2TB          | 2        | 0.28%   |
| WDC WD20EARX-00PASB0 2TB          | 2        | 0.28%   |
| WDC WD20EARS-00MVWB0 2TB          | 2        | 0.28%   |
| WDC WD10EFRX-68FYTN0 1TB          | 2        | 0.28%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 2        | 0.28%   |
| Seagate ST4000VN008-2DR166 4TB    | 2        | 0.28%   |
| Seagate ST4000DM000-1F2168 4TB    | 2        | 0.28%   |
| Seagate ST3500413AS 500GB         | 2        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 119      | 175    | 37.3%   |
| WDC                 | 98       | 143    | 30.72%  |
| Toshiba             | 51       | 74     | 15.99%  |
| Hitachi             | 21       | 22     | 6.58%   |
| Samsung Electronics | 11       | 13     | 3.45%   |
| HGST                | 10       | 13     | 3.13%   |
| MAXTOR              | 5        | 5      | 1.57%   |
| NAS                 | 1        | 5      | 0.31%   |
| MaxDigital          | 1        | 2      | 0.31%   |
| Apple               | 1        | 1      | 0.31%   |
| 128MB               | 1        | 1      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 56       | 74     | 25%     |
| Kingston            | 38       | 45     | 16.96%  |
| Crucial             | 33       | 35     | 14.73%  |
| Netac               | 20       | 22     | 8.93%   |
| SanDisk             | 12       | 14     | 5.36%   |
| WDC                 | 11       | 12     | 4.91%   |
| A-DATA Technology   | 7        | 9      | 3.13%   |
| China               | 5        | 5      | 2.23%   |
| SPCC                | 4        | 4      | 1.79%   |
| PNY                 | 4        | 4      | 1.79%   |
| OCZ                 | 3        | 3      | 1.34%   |
| Unknown             | 2        | 2      | 0.89%   |
| Transcend           | 2        | 3      | 0.89%   |
| Toshiba             | 2        | 4      | 0.89%   |
| Seagate             | 2        | 2      | 0.89%   |
| SABRENT             | 2        | 2      | 0.89%   |
| PLEXTOR             | 2        | 4      | 0.89%   |
| Patriot             | 2        | 2      | 0.89%   |
| Intel               | 2        | 2      | 0.89%   |
| Xinhaike            | 1        | 1      | 0.45%   |
| Team                | 1        | 1      | 0.45%   |
| T-FORCE             | 1        | 1      | 0.45%   |
| PNY USB             | 1        | 1      | 0.45%   |
| Pioneer             | 1        | 1      | 0.45%   |
| Mushkin             | 1        | 1      | 0.45%   |
| Micron Technology   | 1        | 1      | 0.45%   |
| Lexar               | 1        | 1      | 0.45%   |
| KingDian            | 1        | 1      | 0.45%   |
| Intenso             | 1        | 1      | 0.45%   |
| GOODRAM             | 1        | 1      | 0.45%   |
| Gigabyte Technology | 1        | 1      | 0.45%   |
| DOGFISH             | 1        | 1      | 0.45%   |
| Apacer              | 1        | 1      | 0.45%   |
| 2-Power             | 1        | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 263      | 454    | 46.88%  |
| SSD     | 204      | 263    | 36.36%  |
| NVMe    | 82       | 117    | 14.62%  |
| Unknown | 9        | 19     | 1.6%    |
| MMC     | 3        | 3      | 0.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 346      | 705    | 76.89%  |
| NVMe | 82       | 117    | 18.22%  |
| SAS  | 19       | 31     | 4.22%   |
| MMC  | 3        | 3      | 0.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 269      | 369    | 54.02%  |
| 0.51-1.0   | 126      | 161    | 25.3%   |
| 1.01-2.0   | 46       | 64     | 9.24%   |
| 3.01-4.0   | 25       | 54     | 5.02%   |
| 4.01-10.0  | 15       | 31     | 3.01%   |
| 2.01-3.0   | 13       | 20     | 2.61%   |
| 10.01-20.0 | 4        | 18     | 0.8%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 132      | 35.29%  |
| More than 3000 | 42       | 11.23%  |
| 251-500        | 39       | 10.43%  |
| 101-250        | 36       | 9.63%   |
| 501-1000       | 36       | 9.63%   |
| 1001-2000      | 29       | 7.75%   |
| 1-20           | 24       | 6.42%   |
| 2001-3000      | 15       | 4.01%   |
| 51-100         | 15       | 4.01%   |
| 21-50          | 6        | 1.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 132      | 35.2%   |
| 1-20           | 69       | 18.4%   |
| 101-250        | 32       | 8.53%   |
| 501-1000       | 27       | 7.2%    |
| 251-500        | 23       | 6.13%   |
| 51-100         | 23       | 6.13%   |
| 21-50          | 22       | 5.87%   |
| More than 3000 | 20       | 5.33%   |
| 1001-2000      | 18       | 4.8%    |
| 2001-3000      | 8        | 2.13%   |
| 0              | 1        | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB          | 12       | 12     | 13.64%  |
| Seagate ST500DM002-1BD142 500GB       | 3        | 3      | 3.41%   |
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 2.27%   |
| Seagate ST3160813AS 160GB             | 2        | 2      | 2.27%   |
| Kingston SV300S37A120G 120GB SSD      | 2        | 2      | 2.27%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1        | 1      | 1.14%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1        | 2      | 1.14%   |
| WDC WD5002AALX-00J37A0 500GB          | 1        | 1      | 1.14%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1        | 1      | 1.14%   |
| WDC WD5000AAKX-00U6AA0 500GB          | 1        | 1      | 1.14%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 1.14%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1        | 1      | 1.14%   |
| WDC WD5000AAJS-22A8B0 500GB           | 1        | 1      | 1.14%   |
| WDC WD40EFZX-68AWUN0 4TB              | 1        | 6      | 1.14%   |
| WDC WD400BB-00DEA0 40GB               | 1        | 1      | 1.14%   |
| WDC WD3200AAJS-08L7A0 320GB           | 1        | 1      | 1.14%   |
| WDC WD3200AAJS-00L7A0 320GB           | 1        | 1      | 1.14%   |
| WDC WD30EZRX-00AZ6B0 3TB              | 1        | 1      | 1.14%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 1.14%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 1.14%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1        | 1      | 1.14%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1        | 1      | 1.14%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 1.14%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 1.14%   |
| WDC WD1001FALS-75J7B0 1TB             | 1        | 1      | 1.14%   |
| Toshiba MK2565GSX 250GB               | 1        | 1      | 1.14%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 1.14%   |
| SK Hynix PC401 NVMe 512GB             | 1        | 6      | 1.14%   |
| Seagate ST9500325AS 500GB             | 1        | 2      | 1.14%   |
| Seagate ST380215A 80GB                | 1        | 1      | 1.14%   |
| Seagate ST340014A 40GB                | 1        | 1      | 1.14%   |
| Seagate ST3320620A 320GB              | 1        | 1      | 1.14%   |
| Seagate ST3320613AS 320GB             | 1        | 1      | 1.14%   |
| Seagate ST3250310AS 250GB             | 1        | 1      | 1.14%   |
| Seagate ST3200827AS 200GB             | 1        | 2      | 1.14%   |
| Seagate ST32000542AS 2TB              | 1        | 1      | 1.14%   |
| Seagate ST31500341AS 1TB              | 1        | 1      | 1.14%   |
| Seagate ST3120827AS 120GB             | 1        | 2      | 1.14%   |
| Seagate ST3120811AS 120GB             | 1        | 1      | 1.14%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 1.14%   |
| Seagate ST31000333AS 1TB              | 1        | 1      | 1.14%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 1.14%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 1.14%   |
| Seagate ST2000DM001-9YN164 2TB        | 1        | 1      | 1.14%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 1.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 1.14%   |
| Seagate ST1000DM003-9YN162 1TB        | 1        | 1      | 1.14%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 1.14%   |
| Seagate ST10000NE0004-1ZF101 10TB     | 1        | 1      | 1.14%   |
| SanDisk SSD PLUS 120 GB               | 1        | 1      | 1.14%   |
| Samsung Electronics SSD 970 EVO 250GB | 1        | 1      | 1.14%   |
| Samsung Electronics SP0842N 80GB      | 1        | 1      | 1.14%   |
| Samsung Electronics HD321KJ 320GB     | 1        | 1      | 1.14%   |
| Samsung Electronics HD161GJ 160GB     | 1        | 1      | 1.14%   |
| Samsung Electronics HD103SI 1TB       | 1        | 1      | 1.14%   |
| PNY SSD2SC240G3LC709B121-460P 240GB   | 1        | 1      | 1.14%   |
| MAXTOR STM3500320AS 500GB             | 1        | 1      | 1.14%   |
| Maxtor 6B300S0 304GB                  | 1        | 1      | 1.14%   |
| Kingston SE100S3100G 100GB SSD        | 1        | 1      | 1.14%   |
| KingDian S280 240GB                   | 1        | 1      | 1.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 34       | 41     | 39.53%  |
| Seagate             | 24       | 29     | 27.91%  |
| Samsung Electronics | 5        | 5      | 5.81%   |
| Hitachi             | 5        | 5      | 5.81%   |
| A-DATA Technology   | 4        | 5      | 4.65%   |
| Kingston            | 3        | 3      | 3.49%   |
| Toshiba             | 2        | 2      | 2.33%   |
| Maxtor              | 2        | 2      | 2.33%   |
| SK Hynix            | 1        | 6      | 1.16%   |
| SanDisk             | 1        | 1      | 1.16%   |
| PNY                 | 1        | 1      | 1.16%   |
| KingDian            | 1        | 1      | 1.16%   |
| Intel               | 1        | 2      | 1.16%   |
| Crucial             | 1        | 1      | 1.16%   |
| China               | 1        | 1      | 1.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 34       | 41     | 47.89%  |
| Seagate             | 24       | 29     | 33.8%   |
| Hitachi             | 5        | 5      | 7.04%   |
| Samsung Electronics | 4        | 4      | 5.63%   |
| Toshiba             | 2        | 2      | 2.82%   |
| Maxtor              | 2        | 2      | 2.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 66       | 83     | 81.48%  |
| SSD  | 12       | 13     | 14.81%  |
| NVMe | 3        | 9      | 3.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1      | 50%     |
| Seagate ST3500830AS 500GB        | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 302      | 626    | 70.56%  |
| Malfunc  | 76       | 105    | 17.76%  |
| Detected | 48       | 123    | 11.21%  |
| Failed   | 2        | 2      | 0.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 259      | 51.19%  |
| AMD                           | 108      | 21.34%  |
| Samsung Electronics           | 40       | 7.91%   |
| Marvell Technology Group      | 18       | 3.56%   |
| JMicron Technology            | 14       | 2.77%   |
| ASMedia Technology            | 13       | 2.57%   |
| Sandisk                       | 12       | 2.37%   |
| Phison Electronics            | 11       | 2.17%   |
| Micron/Crucial Technology     | 7        | 1.38%   |
| Nvidia                        | 5        | 0.99%   |
| VIA Technologies              | 4        | 0.79%   |
| Broadcom / LSI                | 3        | 0.59%   |
| Silicon Motion                | 2        | 0.4%    |
| Kingston Technology Company   | 2        | 0.4%    |
| SK Hynix                      | 1        | 0.2%    |
| Silicon Image                 | 1        | 0.2%    |
| Seagate Technology            | 1        | 0.2%    |
| Micron Technology             | 1        | 0.2%    |
| Lite-On Technology            | 1        | 0.2%    |
| Integrated Technology Express | 1        | 0.2%    |
| ADATA Technology              | 1        | 0.2%    |
| Adaptec                       | 1        | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 72       | 11.21%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 49       | 7.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 28       | 4.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 26       | 4.05%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 25       | 3.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 20       | 3.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17       | 2.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 16       | 2.49%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16       | 2.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 15       | 2.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13       | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 2.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 12       | 1.87%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11       | 1.71%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 10       | 1.56%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 1.4%    |
| AMD FCH SATA Controller D                                                               | 8        | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7        | 1.09%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 1.09%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 6        | 0.93%   |
| Phison E12 NVMe Controller                                                              | 6        | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 0.93%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 0.93%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 5        | 0.78%   |
| JMicron JMB368 IDE controller                                                           | 5        | 0.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 0.78%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 0.78%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 5        | 0.78%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 0.78%   |
| AMD X399 Series Chipset SATA Controller                                                 | 5        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 0.78%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4        | 0.62%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 0.62%   |
| Nvidia MCP61 IDE                                                                        | 4        | 0.62%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 4        | 0.62%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 4        | 0.62%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 4        | 0.62%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 0.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 0.62%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.62%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.62%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.47%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 0.47%   |
| Intel SSD 660P Series                                                                   | 3        | 0.47%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.47%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 0.47%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 0.47%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.47%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.47%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3        | 0.47%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 0.47%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 0.47%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 3        | 0.47%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 0.47%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 0.47%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.47%   |
| AMD X370 Series Chipset SATA Controller                                                 | 3        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 307      | 61.16%  |
| IDE  | 90       | 17.93%  |
| NVMe | 82       | 16.33%  |
| RAID | 17       | 3.39%   |
| SAS  | 6        | 1.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 259      | 69.25%  |
| AMD          | 114      | 30.48%  |
| CentaurHauls | 1        | 0.27%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-10700 CPU @ 2.90GHz              | 22       | 5.88%   |
| Intel Pentium CPU G3420 @ 3.20GHz              | 18       | 4.81%   |
| AMD Ryzen 5 3600 6-Core Processor              | 10       | 2.67%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 9        | 2.41%   |
| Intel Core i3-3210 CPU @ 3.20GHz               | 6        | 1.6%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 5        | 1.34%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz           | 5        | 1.34%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 5        | 1.34%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 5        | 1.34%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 4        | 1.07%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 4        | 1.07%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 4        | 1.07%   |
| Intel Core i3-10100 CPU @ 3.60GHz              | 4        | 1.07%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz           | 4        | 1.07%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 4        | 1.07%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz    | 3        | 0.8%    |
| Intel Pentium CPU G630 @ 2.70GHz               | 3        | 0.8%    |
| Intel Pentium CPU G4400 @ 3.30GHz              | 3        | 0.8%    |
| Intel Pentium CPU G3220 @ 3.00GHz              | 3        | 0.8%    |
| Intel Core i7-7700 CPU @ 3.60GHz               | 3        | 0.8%    |
| Intel Core i7-3770 CPU @ 3.40GHz               | 3        | 0.8%    |
| Intel Core i5-7500 CPU @ 3.40GHz               | 3        | 0.8%    |
| Intel Core i5-6400 CPU @ 2.70GHz               | 3        | 0.8%    |
| Intel Core i5-4460 CPU @ 3.20GHz               | 3        | 0.8%    |
| Intel Core i5 CPU 650 @ 3.20GHz                | 3        | 0.8%    |
| Intel Core i3-3220 CPU @ 3.30GHz               | 3        | 0.8%    |
| AMD Ryzen 7 2700X Eight-Core Processor         | 3        | 0.8%    |
| AMD Ryzen 5 5600X 6-Core Processor             | 3        | 0.8%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 3        | 0.8%    |
| AMD Ryzen 5 1600 Six-Core Processor            | 3        | 0.8%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 3        | 0.8%    |
| AMD Phenom II X4 965 Processor                 | 3        | 0.8%    |
| AMD Athlon 3000G with Radeon Vega Graphics     | 3        | 0.8%    |
| Intel Pentium Gold G5420 CPU @ 3.80GHz         | 2        | 0.53%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz         | 2        | 0.53%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 2        | 0.53%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 2        | 0.53%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 0.53%   |
| Intel Core i7-8086K CPU @ 4.00GHz              | 2        | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 0.53%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 2        | 0.53%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 2        | 0.53%   |
| Intel Core i5-6600 CPU @ 3.30GHz               | 2        | 0.53%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 2        | 0.53%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 2        | 0.53%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 2        | 0.53%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 2        | 0.53%   |
| Intel Core i5-2320 CPU @ 3.00GHz               | 2        | 0.53%   |
| Intel Core i3-2130 CPU @ 3.40GHz               | 2        | 0.53%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 2        | 0.53%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz          | 2        | 0.53%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz          | 2        | 0.53%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 2        | 0.53%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz           | 2        | 0.53%   |
| Intel Celeron CPU N2820 @ 2.13GHz              | 2        | 0.53%   |
| Intel Atom CPU C2750 @ 2.40GHz                 | 2        | 0.53%   |
| AMD Ryzen Threadripper 2950X 16-Core Processor | 2        | 0.53%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 2        | 0.53%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 2        | 0.53%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 56       | 14.97%  |
| Intel Core i5           | 50       | 13.37%  |
| Intel Pentium           | 38       | 10.16%  |
| Intel Core i3           | 35       | 9.36%   |
| AMD Ryzen 5             | 29       | 7.75%   |
| Intel Core 2 Duo        | 21       | 5.61%   |
| AMD Ryzen 7             | 19       | 5.08%   |
| Intel Xeon              | 14       | 3.74%   |
| AMD FX                  | 10       | 2.67%   |
| Intel Celeron           | 9        | 2.41%   |
| AMD Ryzen 3             | 9        | 2.41%   |
| Intel Core 2 Quad       | 8        | 2.14%   |
| AMD Ryzen Threadripper  | 8        | 2.14%   |
| Intel Pentium Dual-Core | 7        | 1.87%   |
| AMD Ryzen 9             | 7        | 1.87%   |
| Intel Pentium 4         | 5        | 1.34%   |
| AMD Phenom II X4        | 5        | 1.34%   |
| Intel Pentium Gold      | 4        | 1.07%   |
| Intel Core i9           | 4        | 1.07%   |
| Intel Core 2            | 4        | 1.07%   |
| Intel Atom              | 3        | 0.8%    |
| AMD Athlon              | 3        | 0.8%    |
| AMD A10                 | 3        | 0.8%    |
| AMD Athlon X4           | 2        | 0.53%   |
| AMD Athlon II X2        | 2        | 0.53%   |
| AMD Athlon 64 X2        | 2        | 0.53%   |
| AMD A8                  | 2        | 0.53%   |
| Other                   | 1        | 0.27%   |
| CentaurHauls VIA Eden   | 1        | 0.27%   |
| AMD Sempron             | 1        | 0.27%   |
| AMD PRO A8              | 1        | 0.27%   |
| AMD Phenom II X6        | 1        | 0.27%   |
| AMD Phenom II X3        | 1        | 0.27%   |
| AMD Opteron             | 1        | 0.27%   |
| AMD GX                  | 1        | 0.27%   |
| AMD E1                  | 1        | 0.27%   |
| AMD E                   | 1        | 0.27%   |
| AMD Athlon XP           | 1        | 0.27%   |
| AMD Athlon II Neo       | 1        | 0.27%   |
| AMD Athlon Dual Core    | 1        | 0.27%   |
| AMD A6                  | 1        | 0.27%   |
| AMD A4                  | 1        | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 140      | 37.43%  |
| 4      | 114      | 30.48%  |
| 8      | 51       | 13.64%  |
| 6      | 36       | 9.63%   |
| 1      | 11       | 2.94%   |
| 16     | 7        | 1.87%   |
| 12     | 7        | 1.87%   |
| 32     | 2        | 0.53%   |
| 24     | 2        | 0.53%   |
| 44     | 1        | 0.27%   |
| 28     | 1        | 0.27%   |
| 14     | 1        | 0.27%   |
| 3      | 1        | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 370      | 98.93%  |
| 2      | 4        | 1.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 207      | 55.35%  |
| 1      | 167      | 44.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 368      | 98.4%   |
| 32-bit         | 5        | 1.34%   |
| Unknown        | 1        | 0.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 53       | 14.13%  |
| 0x306c3    | 51       | 13.6%   |
| 0xa0655    | 23       | 6.13%   |
| 0x1067a    | 23       | 6.13%   |
| 0x306a9    | 20       | 5.33%   |
| 0x206a7    | 19       | 5.07%   |
| 0x08701021 | 18       | 4.8%    |
| 0x506e3    | 12       | 3.2%    |
| 0x906e9    | 10       | 2.67%   |
| 0x08108109 | 8        | 2.13%   |
| 0x906ea    | 7        | 1.87%   |
| 0x0a201009 | 6        | 1.6%    |
| 0x0800820d | 6        | 1.6%    |
| 0x06003106 | 6        | 1.6%    |
| 0x306f2    | 5        | 1.33%   |
| 0x206d7    | 5        | 1.33%   |
| 0x010000c8 | 5        | 1.33%   |
| 0xa0653    | 4        | 1.07%   |
| 0x20655    | 4        | 1.07%   |
| 0x0a201016 | 4        | 1.07%   |
| 0x08001138 | 4        | 1.07%   |
| 0x06000852 | 4        | 1.07%   |
| 0xf29      | 3        | 0.8%    |
| 0x906ed    | 3        | 0.8%    |
| 0x6fd      | 3        | 0.8%    |
| 0x6fb      | 3        | 0.8%    |
| 0x10677    | 3        | 0.8%    |
| 0x08101016 | 3        | 0.8%    |
| 0x010000b6 | 3        | 0.8%    |
| 0x906ec    | 2        | 0.53%   |
| 0x6f6      | 2        | 0.53%   |
| 0x6f2      | 2        | 0.53%   |
| 0x50654    | 2        | 0.53%   |
| 0x30673    | 2        | 0.53%   |
| 0x106a5    | 2        | 0.53%   |
| 0x10676    | 2        | 0.53%   |
| 0x08701013 | 2        | 0.53%   |
| 0x08301039 | 2        | 0.53%   |
| 0x08001137 | 2        | 0.53%   |
| 0x0700010f | 2        | 0.53%   |
| 0x06001119 | 2        | 0.53%   |
| 0x0600063e | 2        | 0.53%   |
| 0xf49      | 1        | 0.27%   |
| 0xf43      | 1        | 0.27%   |
| 0xf41      | 1        | 0.27%   |
| 0xa0671    | 1        | 0.27%   |
| 0xa0660    | 1        | 0.27%   |
| 0x906eb    | 1        | 0.27%   |
| 0x806e9    | 1        | 0.27%   |
| 0x706a1    | 1        | 0.27%   |
| 0x506c9    | 1        | 0.27%   |
| 0x406f1    | 1        | 0.27%   |
| 0x406e3    | 1        | 0.27%   |
| 0x406d8    | 1        | 0.27%   |
| 0x406c4    | 1        | 0.27%   |
| 0x406c3    | 1        | 0.27%   |
| 0x40651    | 1        | 0.27%   |
| 0x306e4    | 1        | 0.27%   |
| 0x30678    | 1        | 0.27%   |
| 0x20652    | 1        | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 65       | 17.38%  |
| Penryn        | 31       | 8.29%   |
| Zen 2         | 30       | 8.02%   |
| KabyLake      | 28       | 7.49%   |
| CometLake     | 28       | 7.49%   |
| SandyBridge   | 26       | 6.95%   |
| IvyBridge     | 25       | 6.68%   |
| Zen+          | 21       | 5.61%   |
| Skylake       | 17       | 4.55%   |
| Zen           | 13       | 3.48%   |
| Zen 3         | 11       | 2.94%   |
| K10           | 11       | 2.94%   |
| Core          | 11       | 2.94%   |
| Piledriver    | 9        | 2.41%   |
| Steamroller   | 7        | 1.87%   |
| Silvermont    | 7        | 1.87%   |
| Westmere      | 6        | 1.6%    |
| NetBurst      | 6        | 1.6%    |
| Nehalem       | 5        | 1.34%   |
| K8 Hammer     | 3        | 0.8%    |
| Bulldozer     | 3        | 0.8%    |
| Jaguar        | 2        | 0.53%   |
| Excavator     | 2        | 0.53%   |
| Unknown       | 2        | 0.53%   |
| K6            | 1        | 0.27%   |
| Goldmont plus | 1        | 0.27%   |
| Goldmont      | 1        | 0.27%   |
| Broadwell     | 1        | 0.27%   |
| Bobcat        | 1        | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 164      | 40.8%   |
| Intel                      | 133      | 33.08%  |
| AMD                        | 96       | 23.88%  |
| ASPEED Technology          | 6        | 1.49%   |
| VIA Technologies           | 2        | 0.5%    |
| Matrox Electronics Systems | 1        | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 27       | 6.63%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 20       | 4.91%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 19       | 4.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 19       | 4.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 13       | 3.19%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 12       | 2.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12       | 2.95%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 11       | 2.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10       | 2.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 9        | 2.21%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 9        | 2.21%   |
| AMD Picasso                                                                              | 9        | 2.21%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 9        | 2.21%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 8        | 1.97%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6        | 1.47%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 6        | 1.47%   |
| Intel HD Graphics 530                                                                    | 5        | 1.23%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5        | 1.23%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 5        | 1.23%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4        | 0.98%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 4        | 0.98%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 4        | 0.98%   |
| Intel HD Graphics 630                                                                    | 4        | 0.98%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 4        | 0.98%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4        | 0.98%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 3        | 0.74%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 3        | 0.74%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3        | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 0.74%   |
| Intel 82865G Integrated Graphics Controller                                              | 3        | 0.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 0.74%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2        | 0.49%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2        | 0.49%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2        | 0.49%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 0.49%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2        | 0.49%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 0.49%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 2        | 0.49%   |
| Nvidia GK104 [GeForce GTX 670]                                                           | 2        | 0.49%   |
| Nvidia GF119 [NVS 310]                                                                   | 2        | 0.49%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                    | 2        | 0.49%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 2        | 0.49%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 2        | 0.49%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 2        | 0.49%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2        | 0.49%   |
| Nvidia G98 [Quadro NVS 295]                                                              | 2        | 0.49%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2        | 0.49%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 2        | 0.49%   |
| Intel HD Graphics 510                                                                    | 2        | 0.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 0.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.49%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2        | 0.49%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 0.49%   |
| AMD RV730 XT [Radeon HD 4670]                                                            | 2        | 0.49%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 0.49%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2        | 0.49%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                            | 1        | 0.25%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro]            | 1        | 0.25%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 150      | 39.89%  |
| 1 x Intel          | 110      | 29.26%  |
| 1 x AMD            | 90       | 23.94%  |
| Intel + Nvidia     | 11       | 2.93%   |
| 1 x ASPEED         | 5        | 1.33%   |
| 2 x AMD            | 3        | 0.8%    |
| 1 x VIA            | 2        | 0.53%   |
| Intel + 2 x Nvidia | 2        | 0.53%   |
| 1 x Matrox         | 1        | 0.27%   |
| AMD + Nvidia       | 1        | 0.27%   |
| AMD + ASPEED       | 1        | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 176      | 47.06%  |
| Unknown     | 134      | 35.83%  |
| Proprietary | 64       | 17.11%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 236      | 62.77%  |
| 7.01-8.0   | 31       | 8.24%   |
| 1.01-2.0   | 26       | 6.91%   |
| 3.01-4.0   | 24       | 6.38%   |
| 0.51-1.0   | 24       | 6.38%   |
| 0.01-0.5   | 19       | 5.05%   |
| 5.01-6.0   | 8        | 2.13%   |
| 8.01-16.0  | 3        | 0.8%    |
| 2.01-3.0   | 2        | 0.53%   |
| 16.01-24.0 | 2        | 0.53%   |
| 24.01-32.0 | 1        | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 38       | 13.82%  |
| Dell                    | 37       | 13.45%  |
| Goldstar                | 31       | 11.27%  |
| Acer                    | 22       | 8%      |
| Ancor Communications    | 20       | 7.27%   |
| BenQ                    | 18       | 6.55%   |
| Hewlett-Packard         | 16       | 5.82%   |
| Philips                 | 12       | 4.36%   |
| AOC                     | 10       | 3.64%   |
| ViewSonic               | 7        | 2.55%   |
| Unknown                 | 5        | 1.82%   |
| Iiyama                  | 5        | 1.82%   |
| Eizo                    | 5        | 1.82%   |
| ASUSTek Computer        | 5        | 1.82%   |
| Sony                    | 4        | 1.45%   |
| NEC Computers           | 4        | 1.45%   |
| LG Electronics          | 3        | 1.09%   |
| Lenovo                  | 3        | 1.09%   |
| Vizio                   | 2        | 0.73%   |
| MSI                     | 2        | 0.73%   |
| Chi Mei Optoelectronics | 2        | 0.73%   |
| WTC                     | 1        | 0.36%   |
| VMO                     | 1        | 0.36%   |
| Vestel Elektronik       | 1        | 0.36%   |
| SGT                     | 1        | 0.36%   |
| Prestigio               | 1        | 0.36%   |
| ONN                     | 1        | 0.36%   |
| ODH                     | 1        | 0.36%   |
| Mitsubishi              | 1        | 0.36%   |
| MIT                     | 1        | 0.36%   |
| Mi                      | 1        | 0.36%   |
| Medion                  | 1        | 0.36%   |
| Lenovo Group Limited    | 1        | 0.36%   |
| JVC                     | 1        | 0.36%   |
| INFOTRONIC              | 1        | 0.36%   |
| Idek Iiyama             | 1        | 0.36%   |
| Hyundai ImageQuest      | 1        | 0.36%   |
| HXF                     | 1        | 0.36%   |
| HKC                     | 1        | 0.36%   |
| Hitachi                 | 1        | 0.36%   |
| HannStar Display        | 1        | 0.36%   |
| Fujitsu Siemens         | 1        | 0.36%   |
| COBY                    | 1        | 0.36%   |
| Belinea                 | 1        | 0.36%   |
| AU Optronics            | 1        | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 4        | 1.38%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 3        | 1.03%   |
| Philips 220WS PHL0851 1680x1050 474x296mm 22.0-inch                    | 3        | 1.03%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 3        | 1.03%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 3        | 1.03%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 3        | 1.03%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3        | 1.03%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 3        | 1.03%   |
| Sony TV *00 SNY8004 3840x2160 1085x610mm 49.0-inch                     | 2        | 0.69%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 2        | 0.69%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch   | 2        | 0.69%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch     | 2        | 0.69%   |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch               | 2        | 0.69%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2        | 0.69%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 0.69%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2        | 0.69%   |
| Dell P2415Q DELA0BE 2048x1280 530x300mm 24.0-inch                      | 2        | 0.69%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2        | 0.69%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                      | 2        | 0.69%   |
| Acer K272HUL ACR0524 2560x1440 598x336mm 27.0-inch                     | 2        | 0.69%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2        | 0.69%   |
| WTC FW1420S WTC1400 1024x768 304x228mm 15.0-inch                       | 1        | 0.34%   |
| VMO WQX DP VMO1507 2560x1600 1600x1000mm 74.3-inch                     | 1        | 0.34%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                     | 1        | 0.34%   |
| Vizio D32f-F1 VIZ1027 1920x1080 698x392mm 31.5-inch                    | 1        | 0.34%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch              | 1        | 0.34%   |
| ViewSonic VG2860 SERIES VSC1F30 3840x2160 621x341mm 27.9-inch          | 1        | 0.34%   |
| ViewSonic VA926 Series VSC7D20 1280x1024 376x301mm 19.0-inch           | 1        | 0.34%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch              | 1        | 0.34%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.34%   |
| Unknown LCD Monitor TCT DP1080P60 1920x1080                            | 1        | 0.34%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.34%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1        | 0.34%   |
| SGT LCD Monitor SGT1900 1440x900 400x270mm 19.0-inch                   | 1        | 0.34%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch      | 1        | 0.34%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch      | 1        | 0.34%   |
| Samsung Electronics U24E850 SAM0CCF 3840x2160 521x293mm 23.5-inch      | 1        | 0.34%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch      | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM0564 1024x768 410x230mm 18.5-inch    | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch    | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch    | 1        | 0.34%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch     | 1        | 0.34%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch  | 1        | 0.34%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch   | 1        | 0.34%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1        | 0.34%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch      | 1        | 0.34%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch      | 1        | 0.34%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 0.34%   |
| Samsung Electronics S24E650 SAM0CBE 1920x1200 520x320mm 24.0-inch      | 1        | 0.34%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 0.34%   |
| Samsung Electronics S23B350 SAM08D6 1920x1080 510x287mm 23.0-inch      | 1        | 0.34%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch      | 1        | 0.34%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch       | 1        | 0.34%   |
| Samsung Electronics Monitor SAM1057 1280x1024 306x230mm 15.1-inch      | 1        | 0.34%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.34%   |
| Samsung Electronics LF27T850 SAM704F 2560x1440 597x336mm 27.0-inch     | 1        | 0.34%   |
| Samsung Electronics LCD Monitor SyncMaster 5760x1080                   | 1        | 0.34%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 1        | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 110      | 40.44%  |
| 2560x1440 (QHD)    | 24       | 8.82%   |
| 3840x2160 (4K)     | 23       | 8.46%   |
| 1280x1024 (SXGA)   | 22       | 8.09%   |
| 1680x1050 (WSXGA+) | 18       | 6.62%   |
| 1920x1200 (WUXGA)  | 10       | 3.68%   |
| 1366x768 (WXGA)    | 9        | 3.31%   |
| Unknown            | 8        | 2.94%   |
| 2560x1080          | 7        | 2.57%   |
| 1600x900 (HD+)     | 7        | 2.57%   |
| 1440x900 (WXGA+)   | 5        | 1.84%   |
| 1024x768 (XGA)     | 5        | 1.84%   |
| 2288x1287          | 4        | 1.47%   |
| 3840x1080          | 3        | 1.1%    |
| 3440x1440          | 3        | 1.1%    |
| 2560x1600          | 3        | 1.1%    |
| 1600x1200          | 3        | 1.1%    |
| 7680x4320          | 1        | 0.37%   |
| 5760x1080          | 1        | 0.37%   |
| 5360x1440          | 1        | 0.37%   |
| 4480x1440          | 1        | 0.37%   |
| 3360x1080          | 1        | 0.37%   |
| 1920x540           | 1        | 0.37%   |
| 1360x768           | 1        | 0.37%   |
| 1024x600           | 1        | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 41       | 15.3%   |
| 27      | 38       | 14.18%  |
| 23      | 38       | 14.18%  |
| 21      | 22       | 8.21%   |
| Unknown | 21       | 7.84%   |
| 22      | 13       | 4.85%   |
| 17      | 13       | 4.85%   |
| 19      | 12       | 4.48%   |
| 31      | 10       | 3.73%   |
| 15      | 10       | 3.73%   |
| 18      | 9        | 3.36%   |
| 34      | 8        | 2.99%   |
| 20      | 8        | 2.99%   |
| 142     | 4        | 1.49%   |
| 28      | 3        | 1.12%   |
| 84      | 2        | 0.75%   |
| 65      | 2        | 0.75%   |
| 32      | 2        | 0.75%   |
| 29      | 2        | 0.75%   |
| 74      | 1        | 0.37%   |
| 72      | 1        | 0.37%   |
| 55      | 1        | 0.37%   |
| 49      | 1        | 0.37%   |
| 48      | 1        | 0.37%   |
| 38      | 1        | 0.37%   |
| 26      | 1        | 0.37%   |
| 25      | 1        | 0.37%   |
| 16      | 1        | 0.37%   |
| 10      | 1        | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 107      | 41.15%  |
| 401-500        | 56       | 21.54%  |
| 301-350        | 24       | 9.23%   |
| Unknown        | 21       | 8.08%   |
| 601-700        | 20       | 7.69%   |
| 701-800        | 9        | 3.46%   |
| 351-400        | 8        | 3.08%   |
| 1001-1500      | 5        | 1.92%   |
| More than 2000 | 4        | 1.54%   |
| 1501-2000      | 4        | 1.54%   |
| 801-900        | 1        | 0.38%   |
| 201-300        | 1        | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 151      | 59.22%  |
| 16/10   | 34       | 13.33%  |
| Unknown | 20       | 7.84%   |
| 5/4     | 19       | 7.45%   |
| 4/3     | 11       | 4.31%   |
| 21/9    | 10       | 3.92%   |
| 1.00    | 5        | 1.96%   |
| 3/2     | 3        | 1.18%   |
| 6/5     | 1        | 0.39%   |
| 1.96    | 1        | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 90       | 34.35%  |
| 301-350        | 38       | 14.5%   |
| 151-200        | 27       | 10.31%  |
| 351-500        | 23       | 8.78%   |
| Unknown        | 21       | 8.02%   |
| 141-150        | 19       | 7.25%   |
| 251-300        | 18       | 6.87%   |
| More than 1000 | 11       | 4.2%    |
| 101-110        | 9        | 3.44%   |
| 131-140        | 2        | 0.76%   |
| 501-1000       | 2        | 0.76%   |
| 41-50          | 1        | 0.38%   |
| 111-120        | 1        | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 159      | 62.35%  |
| 101-120 | 44       | 17.25%  |
| Unknown | 21       | 8.24%   |
| 121-160 | 13       | 5.1%    |
| 1-50    | 9        | 3.53%   |
| 161-240 | 9        | 3.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 182      | 48.66%  |
| 0     | 139      | 37.17%  |
| 2     | 47       | 12.57%  |
| 3     | 5        | 1.34%   |
| 4     | 1        | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 234      | 50.98%  |
| Intel                           | 134      | 29.19%  |
| Qualcomm Atheros                | 34       | 7.41%   |
| Broadcom                        | 13       | 2.83%   |
| Ralink Technology               | 6        | 1.31%   |
| Nvidia                          | 5        | 1.09%   |
| Microsoft                       | 4        | 0.87%   |
| Ralink                          | 3        | 0.65%   |
| Marvell Technology Group        | 3        | 0.65%   |
| Broadcom Limited                | 3        | 0.65%   |
| VIA Technologies                | 2        | 0.44%   |
| TP-Link                         | 2        | 0.44%   |
| Mellanox Technologies           | 2        | 0.44%   |
| Aquantia                        | 2        | 0.44%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.22%   |
| Xiaomi                          | 1        | 0.22%   |
| Wilocity                        | 1        | 0.22%   |
| Qualcomm Atheros Communications | 1        | 0.22%   |
| NetGear                         | 1        | 0.22%   |
| Micro Star International        | 1        | 0.22%   |
| IMC Networks                    | 1        | 0.22%   |
| Edimax Technology               | 1        | 0.22%   |
| D-Link                          | 1        | 0.22%   |
| ASIX Electronics                | 1        | 0.22%   |
| American Megatrends             | 1        | 0.22%   |
| ADMtek                          | 1        | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 201      | 40.04%  |
| Intel I211 Gigabit Network Connection                             | 23       | 4.58%   |
| Intel Wi-Fi 6 AX200                                               | 17       | 3.39%   |
| Intel Ethernet Connection (2) I219-V                              | 14       | 2.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13       | 2.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 2.39%   |
| Intel I210 Gigabit Network Connection                             | 10       | 1.99%   |
| Intel Ethernet Connection I217-V                                  | 8        | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6        | 1.2%    |
| Intel 82579V Gigabit Network Connection                           | 6        | 1.2%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 1.2%    |
| Intel Wireless 7260                                               | 5        | 1%      |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.8%    |
| Nvidia MCP61 Ethernet                                             | 4        | 0.8%    |
| Intel 82574L Gigabit Network Connection                           | 4        | 0.8%    |
| Ralink MT7601U Wireless Adapter                                   | 3        | 0.6%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.6%    |
| Microsoft Xbox 360 Wireless Adapter                               | 3        | 0.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.6%    |
| Intel Ethernet Controller I225-V                                  | 3        | 0.6%    |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 0.4%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2        | 0.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2        | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.4%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.4%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2        | 0.4%    |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 0.4%    |
| Intel Wireless 8260                                               | 2        | 0.4%    |
| Intel Wireless 3165                                               | 2        | 0.4%    |
| Intel Ethernet Controller 10G X550T                               | 2        | 0.4%    |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.4%    |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.4%    |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 0.4%    |
| Intel 82566DC-2 Gigabit Network Connection                        | 2        | 0.4%    |
| Intel 82566DC Gigabit Network Connection                          | 2        | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.4%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 0.4%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 0.4%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.4%    |
| ZTE WCDMA MSM ZTE MSM                                             | 1        | 0.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.2%    |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1        | 0.2%    |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1        | 0.2%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.2%    |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1        | 0.2%    |
| TP-Link Archer T4U ver.3                                          | 1        | 0.2%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.2%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 37       | 39.78%  |
| Qualcomm Atheros                | 15       | 16.13%  |
| Realtek Semiconductor           | 13       | 13.98%  |
| Ralink Technology               | 6        | 6.45%   |
| Broadcom                        | 6        | 6.45%   |
| Microsoft                       | 4        | 4.3%    |
| Ralink                          | 3        | 3.23%   |
| TP-Link                         | 2        | 2.15%   |
| Wilocity                        | 1        | 1.08%   |
| Qualcomm Atheros Communications | 1        | 1.08%   |
| NetGear                         | 1        | 1.08%   |
| Micro Star International        | 1        | 1.08%   |
| IMC Networks                    | 1        | 1.08%   |
| Edimax Technology               | 1        | 1.08%   |
| D-Link                          | 1        | 1.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 17       | 18.28%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6        | 6.45%   |
| Intel Wireless 7260                                                     | 5        | 5.38%   |
| Ralink MT7601U Wireless Adapter                                         | 3        | 3.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3        | 3.23%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 3        | 3.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2        | 2.15%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2        | 2.15%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2        | 2.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2        | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2        | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2        | 2.15%   |
| Intel Wireless 8260                                                     | 2        | 2.15%   |
| Intel Wireless 3165                                                     | 2        | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2        | 2.15%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2        | 2.15%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                      | 1        | 1.08%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 1        | 1.08%   |
| TP-Link Archer T4U ver.3                                                | 1        | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.08%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.08%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1        | 1.08%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 1.08%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1        | 1.08%   |
| Realtek 802.11ac NIC                                                    | 1        | 1.08%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 1.08%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 1.08%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 1.08%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1        | 1.08%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 1        | 1.08%   |
| Ralink RT2800 802.11n PCI                                               | 1        | 1.08%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1        | 1.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1        | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 1.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1        | 1.08%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1        | 1.08%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1        | 1.08%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                 | 1        | 1.08%   |
| Microsoft Wireless XBox Controller Dongle                               | 1        | 1.08%   |
| Micro Star International RT2573                                         | 1        | 1.08%   |
| Intel Wireless-AC 9260                                                  | 1        | 1.08%   |
| Intel Wireless 8265 / 8275                                              | 1        | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 1.08%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                    | 1        | 1.08%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1        | 1.08%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 1.08%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1        | 1.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1        | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1        | 1.08%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1        | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 229      | 57.97%  |
| Intel                      | 117      | 29.62%  |
| Qualcomm Atheros           | 20       | 5.06%   |
| Broadcom                   | 7        | 1.77%   |
| Nvidia                     | 5        | 1.27%   |
| Marvell Technology Group   | 3        | 0.76%   |
| Broadcom Limited           | 3        | 0.76%   |
| VIA Technologies           | 2        | 0.51%   |
| Mellanox Technologies      | 2        | 0.51%   |
| Aquantia                   | 2        | 0.51%   |
| ZTE WCDMA Technologies MSM | 1        | 0.25%   |
| Xiaomi                     | 1        | 0.25%   |
| ASIX Electronics           | 1        | 0.25%   |
| American Megatrends        | 1        | 0.25%   |
| ADMtek                     | 1        | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 201      | 49.14%  |
| Intel I211 Gigabit Network Connection                             | 23       | 5.62%   |
| Intel Ethernet Connection (2) I219-V                              | 14       | 3.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13       | 3.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 2.93%   |
| Intel I210 Gigabit Network Connection                             | 10       | 2.44%   |
| Intel Ethernet Connection I217-V                                  | 8        | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 1.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1.47%   |
| Intel 82579V Gigabit Network Connection                           | 6        | 1.47%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 1.47%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.98%   |
| Nvidia MCP61 Ethernet                                             | 4        | 0.98%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.73%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.73%   |
| Intel Ethernet Controller I225-V                                  | 3        | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.49%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.49%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.49%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 0.49%   |
| Intel Ethernet Controller 10G X550T                               | 2        | 0.49%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.49%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.49%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.49%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 2        | 0.49%   |
| Intel 82566DC Gigabit Network Connection                          | 2        | 0.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.49%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 0.49%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.49%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1        | 0.24%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.24%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1        | 0.24%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.24%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.24%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.24%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.24%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.24%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.24%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.24%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.24%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.24%   |
| Intel Ethernet Virtual Function 700 Series                        | 1        | 0.24%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 0.24%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.24%   |
| Intel Ethernet Connection I354                                    | 1        | 0.24%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 0.24%   |
| Intel Ethernet Connection (6) I219-V                              | 1        | 0.24%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.24%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.24%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.24%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.24%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 372      | 80.69%  |
| WiFi     | 89       | 19.31%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 351      | 85.4%   |
| WiFi     | 60       | 14.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 270      | 72.19%  |
| 2     | 85       | 22.73%  |
| 3     | 13       | 3.48%   |
| 4     | 2        | 0.53%   |
| 13    | 1        | 0.27%   |
| 6     | 1        | 0.27%   |
| 5     | 1        | 0.27%   |
| 0     | 1        | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 327      | 87.43%  |
| Yes  | 47       | 12.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 35       | 43.21%  |
| Cambridge Silicon Radio         | 17       | 20.99%  |
| Broadcom                        | 10       | 12.35%  |
| ASUSTek Computer                | 7        | 8.64%   |
| Realtek Semiconductor           | 3        | 3.7%    |
| Qualcomm Atheros Communications | 3        | 3.7%    |
| IMC Networks                    | 2        | 2.47%   |
| Belkin Components               | 2        | 2.47%   |
| Sitecom Europe                  | 1        | 1.23%   |
| Micro Star International        | 1        | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Intel Bluetooth Device                                    | 22       | 27.16%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 17       | 20.99%  |
| Intel Wireless-AC 3168 Bluetooth                          | 5        | 6.17%   |
| Intel Bluetooth wireless interface                        | 4        | 4.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 4        | 4.94%   |
| Realtek Bluetooth Radio                                   | 3        | 3.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 2        | 2.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 2        | 2.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 2        | 2.47%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1        | 1.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 1        | 1.23%   |
| Qualcomm Atheros Bluetooth USB Host Controller            | 1        | 1.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 1        | 1.23%   |
| Micro Star International Bluetooth EDR Device             | 1        | 1.23%   |
| IMC Networks Bluetooth Radio                              | 1        | 1.23%   |
| IMC Networks Bluetooth                                    | 1        | 1.23%   |
| Broadcom HP Portable Bumble Bee                           | 1        | 1.23%   |
| Broadcom Bluetooth 3.0 Device                             | 1        | 1.23%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter          | 1        | 1.23%   |
| Broadcom BCM43142A0 Bluetooth 4.0                         | 1        | 1.23%   |
| Broadcom BCM2045 Bluetooth                                | 1        | 1.23%   |
| Broadcom BCM2035 Bluetooth dongle                         | 1        | 1.23%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter     | 1        | 1.23%   |
| Belkin Components F8T012 Bluetooth Adapter                | 1        | 1.23%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 1        | 1.23%   |
| ASUS Bluetooth Radio                                      | 1        | 1.23%   |
| ASUS Bluetooth Device                                     | 1        | 1.23%   |
| ASUS Bluetooth Adapter                                    | 1        | 1.23%   |
| ASUS BCM20702A0                                           | 1        | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 242      | 40.4%   |
| Nvidia                     | 149      | 24.87%  |
| AMD                        | 130      | 21.7%   |
| C-Media Electronics        | 11       | 1.84%   |
| Logitech                   | 7        | 1.17%   |
| Creative Labs              | 5        | 0.83%   |
| VIA Technologies           | 4        | 0.67%   |
| GYROCOM C&C                | 4        | 0.67%   |
| Generalplus Technology     | 4        | 0.67%   |
| Unknown                    | 3        | 0.5%    |
| RODE Microphones           | 3        | 0.5%    |
| Yamaha                     | 2        | 0.33%   |
| XMOS                       | 2        | 0.33%   |
| Samson Technologies        | 2        | 0.33%   |
| JMTek                      | 2        | 0.33%   |
| GN Netcom                  | 2        | 0.33%   |
| Cambridge Silicon Radio    | 2        | 0.33%   |
| BEHRINGER International    | 2        | 0.33%   |
| ASUSTek Computer           | 2        | 0.33%   |
| Texas Instruments          | 1        | 0.17%   |
| TerraTec Electronic        | 1        | 0.17%   |
| TEAC                       | 1        | 0.17%   |
| SteelSeries ApS            | 1        | 0.17%   |
| ROCCAT                     | 1        | 0.17%   |
| PreSonus Audio Electronics | 1        | 0.17%   |
| Plantronics                | 1        | 0.17%   |
| Musical Fidelity           | 1        | 0.17%   |
| Micronas                   | 1        | 0.17%   |
| M-Audio                    | 1        | 0.17%   |
| Kingston Technology        | 1        | 0.17%   |
| Hangzhou Worlde            | 1        | 0.17%   |
| Focusrite-Novation         | 1        | 0.17%   |
| Dell                       | 1        | 0.17%   |
| Creative Technology        | 1        | 0.17%   |
| Blue Microphones           | 1        | 0.17%   |
| B & W Group                | 1        | 0.17%   |
| AXELVOX                    | 1        | 0.17%   |
| AVID Technology            | 1        | 0.17%   |
| Audioengine                | 1        | 0.17%   |
| Alesis                     | 1        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 49       | 7.07%   |
| AMD Starship/Matisse HD Audio Controller                                   | 38       | 5.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 36       | 5.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 28       | 4.04%   |
| Nvidia GF108 High Definition Audio Controller                              | 26       | 3.75%   |
| Intel Comet Lake PCH cAVS                                                  | 24       | 3.46%   |
| Nvidia TU106 High Definition Audio Controller                              | 21       | 3.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 20       | 2.89%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19       | 2.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 18       | 2.6%    |
| Intel 200 Series PCH HD Audio                                              | 17       | 2.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 16       | 2.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16       | 2.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15       | 2.16%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 15       | 2.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13       | 1.88%   |
| AMD FCH Azalia Controller                                                  | 12       | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11       | 1.59%   |
| AMD Navi 10 HDMI Audio                                                     | 11       | 1.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10       | 1.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10       | 1.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8        | 1.15%   |
| Nvidia GP104 High Definition Audio Controller                              | 7        | 1.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 1.01%   |
| Nvidia High Definition Audio Controller                                    | 6        | 0.87%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 0.87%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 6        | 0.87%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6        | 0.87%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 6        | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6        | 0.87%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 0.87%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 0.72%   |
| Nvidia GF116 High Definition Audio Controller                              | 5        | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 0.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5        | 0.72%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 5        | 0.72%   |
| Nvidia MCP61 High Definition Audio                                         | 4        | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 0.58%   |
| Nvidia GK104 HDMI Audio Controller                                         | 4        | 0.58%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 0.58%   |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 0.58%   |
| Generalplus Technology USB Audio Device                                    | 4        | 0.58%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 0.58%   |
| AMD Kabini HDMI/DP Audio                                                   | 4        | 0.58%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 4        | 0.58%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 0.43%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.43%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.43%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller             | 3        | 0.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 0.43%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                       | 3        | 0.43%   |
| GYROCOM C&C Fiio E10                                                       | 3        | 0.43%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 0.43%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 2        | 0.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.29%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.29%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.29%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.29%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.29%   |
| Nvidia GF106 High Definition Audio Controller                              | 2        | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Kingston                | 85       | 22.49%  |
| Unknown                 | 63       | 16.67%  |
| Corsair                 | 39       | 10.32%  |
| Samsung Electronics     | 34       | 8.99%   |
| SK Hynix                | 33       | 8.73%   |
| Crucial                 | 33       | 8.73%   |
| G.Skill                 | 23       | 6.08%   |
| Hikvision               | 20       | 5.29%   |
| Patriot                 | 11       | 2.91%   |
| Micron Technology       | 7        | 1.85%   |
| A-DATA Technology       | 3        | 0.79%   |
| Team                    | 2        | 0.53%   |
| Nanya Technology        | 2        | 0.53%   |
| Kllisre                 | 2        | 0.53%   |
| Elpida                  | 2        | 0.53%   |
| Apacer                  | 2        | 0.53%   |
| AMD                     | 2        | 0.53%   |
| V-Color                 | 1        | 0.26%   |
| Unknown (ABCD)          | 1        | 0.26%   |
| Unknown (000000000FE02) | 1        | 0.26%   |
| Unknown (0000000002C80) | 1        | 0.26%   |
| Transcend               | 1        | 0.26%   |
| Smart                   | 1        | 0.26%   |
| Ramaxel Technology      | 1        | 0.26%   |
| Qimonda                 | 1        | 0.26%   |
| OCZ                     | 1        | 0.26%   |
| Kingmax                 | 1        | 0.26%   |
| KETECH                  | 1        | 0.26%   |
| Infineon                | 1        | 0.26%   |
| GOODRAM                 | 1        | 0.26%   |
| Goldkey                 | 1        | 0.26%   |
| GeIL                    | 1        | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Hikvision RAM HKED4161DAA1D0MA1 16384MB DIMM DDR4 2667MT/s | 20       | 4.82%   |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1600MT/s   | 19       | 4.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 5        | 1.2%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 5        | 1.2%    |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s     | 5        | 1.2%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s      | 5        | 1.2%    |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 4        | 0.96%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                | 4        | 0.96%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s      | 4        | 0.96%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                  | 3        | 0.72%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 3        | 0.72%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 3        | 0.72%   |
| SK Hynix RAM 4GBPC1600PB N0 4096MB DIMM DDR3 1067MT/s      | 3        | 0.72%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s          | 3        | 0.72%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s        | 3        | 0.72%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s        | 3        | 0.72%   |
| Kingston RAM 99U5474-010.A00LF 2048MB DIMM DDR3 1333MT/s   | 3        | 0.72%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s     | 3        | 0.72%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s      | 3        | 0.72%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s   | 3        | 0.72%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                  | 2        | 0.48%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                 | 2        | 0.48%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                    | 2        | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                   | 2        | 0.48%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 2        | 0.48%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                       | 2        | 0.48%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                    | 2        | 0.48%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                   | 2        | 0.48%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                 | 2        | 0.48%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                | 2        | 0.48%   |
| Unknown RAM 99[2/7/4]164(F/R) 4GB DIMM DDR3 1600MT/s       | 2        | 0.48%   |
| SK Hynix RAM HMAA2GU6AJR8N-XN 16GB DIMM DDR4 3200MT/s      | 2        | 0.48%   |
| SK Hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2666MT/s      | 2        | 0.48%   |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s        | 2        | 0.48%   |
| Samsung RAM M378B5273CH0-CK0 4096MB DIMM DDR3 2000MT/s     | 2        | 0.48%   |
| Samsung RAM M378A1K43DB2-CTD 8192MB DIMM DDR4 4333MT/s     | 2        | 0.48%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s        | 2        | 0.48%   |
| Patriot RAM PSD38G13332 8192MB DIMM DDR3 1333MT/s          | 2        | 0.48%   |
| Patriot RAM PSD32G13332 2048MB DIMM DDR3 1333MT/s          | 2        | 0.48%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s         | 2        | 0.48%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s       | 2        | 0.48%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s          | 2        | 0.48%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1866MT/s     | 2        | 0.48%   |
| Kingston RAM 99P5474-013.A00LF 4096MB DIMM DDR3 1600MT/s   | 2        | 0.48%   |
| Kingston RAM 9905702-120.A00G 8192MB DIMM DDR4 2667MT/s    | 2        | 0.48%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s     | 2        | 0.48%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s     | 2        | 0.48%   |
| Crucial RAM CT51264BD160B.C16F 4096MB DIMM DDR3 1600MT/s   | 2        | 0.48%   |
| Crucial RAM CT51264BA160BJ.C8 4096MB DIMM DDR3 1600MT/s    | 2        | 0.48%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4096MB DIMM DDR4 2133MT/s  | 2        | 0.48%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s      | 2        | 0.48%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s     | 2        | 0.48%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s      | 2        | 0.48%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s      | 2        | 0.48%   |
| AMD RAM R748G2400U2S 8GB DIMM DDR4 2400MT/s                | 2        | 0.48%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s           | 1        | 0.24%   |
| Unknown RAM V02D4LF8GB5285282400 8192MB DIMM DDR4 2400MT/s | 1        | 0.24%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1        | 0.24%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                       | 1        | 0.24%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                    | 1        | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 145      | 42.52%  |
| DDR3    | 129      | 37.83%  |
| DDR2    | 22       | 6.45%   |
| Unknown | 22       | 6.45%   |
| SDRAM   | 16       | 4.69%   |
| DDR     | 6        | 1.76%   |
| LPDDR4  | 1        | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 329      | 96.76%  |
| SODIMM | 10       | 2.94%   |
| RIMM   | 1        | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 117      | 31.62%  |
| 4096  | 87       | 23.51%  |
| 16384 | 61       | 16.49%  |
| 2048  | 58       | 15.68%  |
| 1024  | 21       | 5.68%   |
| 32768 | 15       | 4.05%   |
| 512   | 7        | 1.89%   |
| 256   | 3        | 0.81%   |
| 65536 | 1        | 0.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 87       | 23.32%  |
| 1333    | 46       | 12.33%  |
| 2667    | 42       | 11.26%  |
| 3200    | 26       | 6.97%   |
| 800     | 22       | 5.9%    |
| 2400    | 18       | 4.83%   |
| 3600    | 15       | 4.02%   |
| 2133    | 14       | 3.75%   |
| 2666    | 10       | 2.68%   |
| Unknown | 10       | 2.68%   |
| 667     | 9        | 2.41%   |
| 2933    | 7        | 1.88%   |
| 1867    | 7        | 1.88%   |
| 1866    | 7        | 1.88%   |
| 3000    | 6        | 1.61%   |
| 1067    | 6        | 1.61%   |
| 1066    | 6        | 1.61%   |
| 3466    | 5        | 1.34%   |
| 3400    | 3        | 0.8%    |
| 1800    | 3        | 0.8%    |
| 400     | 3        | 0.8%    |
| 4333    | 2        | 0.54%   |
| 3533    | 2        | 0.54%   |
| 3500    | 2        | 0.54%   |
| 3100    | 2        | 0.54%   |
| 2000    | 2        | 0.54%   |
| 3866    | 1        | 0.27%   |
| 3733    | 1        | 0.27%   |
| 3066    | 1        | 0.27%   |
| 2866    | 1        | 0.27%   |
| 2465    | 1        | 0.27%   |
| 2187    | 1        | 0.27%   |
| 2048    | 1        | 0.27%   |
| 1400    | 1        | 0.27%   |
| 1367    | 1        | 0.27%   |
| 333     | 1        | 0.27%   |
| 66      | 1        | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 8        | 61.54%  |
| Samsung Electronics | 2        | 15.38%  |
| Konica Minolta      | 1        | 7.69%   |
| Canon               | 1        | 7.69%   |
| Brother Industries  | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| HP LaserJet 1200              | 2        | 15.38%  |
| Samsung SCX-4650 4x21S Series | 1        | 7.69%   |
| Samsung ML-1660 Series        | 1        | 7.69%   |
| Konica Minolta bizhub 4402P   | 1        | 7.69%   |
| HP LaserJet P1006             | 1        | 7.69%   |
| HP LaserJet M101-M106         | 1        | 7.69%   |
| HP LaserJet 400 M401dn        | 1        | 7.69%   |
| HP LaserJet 1150              | 1        | 7.69%   |
| HP ENVY 5000 series           | 1        | 7.69%   |
| HP ENVY 4520 series           | 1        | 7.69%   |
| Canon iP2700 series           | 1        | 7.69%   |
| Brother MFC-L2710DW series    | 1        | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 50%     |
| Canon       | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 19       | 33.33%  |
| Microdia                      | 9        | 15.79%  |
| Samsung Electronics           | 4        | 7.02%   |
| Generalplus Technology        | 3        | 5.26%   |
| Sunplus Innovation Technology | 2        | 3.51%   |
| Microsoft                     | 2        | 3.51%   |
| Genesys Logic                 | 2        | 3.51%   |
| Z-Star Microelectronics       | 1        | 1.75%   |
| Xiongmai                      | 1        | 1.75%   |
| Unknown                       | 1        | 1.75%   |
| SiGma Micro                   | 1        | 1.75%   |
| Razer USA                     | 1        | 1.75%   |
| Novatek Microelectronics      | 1        | 1.75%   |
| Lenovo                        | 1        | 1.75%   |
| Jieli Technology              | 1        | 1.75%   |
| Huawei Technologies           | 1        | 1.75%   |
| Hewlett-Packard               | 1        | 1.75%   |
| eMPIA Technology              | 1        | 1.75%   |
| Creative Technology           | 1        | 1.75%   |
| Chicony Electronics           | 1        | 1.75%   |
| AVerMedia Technologies        | 1        | 1.75%   |
| ARC International             | 1        | 1.75%   |
| Apple                         | 1        | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 5        | 8.77%   |
| Samsung Galaxy A5 (MTP)               | 4        | 7.02%   |
| Microdia Webcam Vitade AF             | 4        | 7.02%   |
| Logitech HD Pro Webcam C920           | 4        | 7.02%   |
| Microsoft LifeCam HD-3000             | 2        | 3.51%   |
| Microdia USB 2.0 Camera               | 2        | 3.51%   |
| Logitech HD Webcam C910               | 2        | 3.51%   |
| Logitech HD Webcam C615               | 2        | 3.51%   |
| Generalplus GENERAL WEBCAM            | 2        | 3.51%   |
| Z-Star Venus USB2.0 Camera            | 1        | 1.75%   |
| Xiongmai web camera                   | 1        | 1.75%   |
| Unknown Konftel Cam20                 | 1        | 1.75%   |
| Sunplus HD USB Camaer 4K              | 1        | 1.75%   |
| Sunplus HD 720P webcam                | 1        | 1.75%   |
| SiGma Micro WebCam SiGma Micro        | 1        | 1.75%   |
| Razer USA Razer Kiyo                  | 1        | 1.75%   |
| Novatek HP High Definition 2MP Webcam | 1        | 1.75%   |
| Microdia Sonix USB 2.0 Camera         | 1        | 1.75%   |
| Microdia Integrated Camera            | 1        | 1.75%   |
| Microdia Camera                       | 1        | 1.75%   |
| Logitech Webcam C925e                 | 1        | 1.75%   |
| Logitech Webcam C260                  | 1        | 1.75%   |
| Logitech Webcam C170                  | 1        | 1.75%   |
| Logitech Quickcam 3000 For Business   | 1        | 1.75%   |
| Logitech HD Webcam B910               | 1        | 1.75%   |
| Logitech BRIO Ultra HD Webcam         | 1        | 1.75%   |
| Lenovo FHD Webcam                     | 1        | 1.75%   |
| Jieli USB PHY 2.0                     | 1        | 1.75%   |
| Huawei HiCamera                       | 1        | 1.75%   |
| HP Webcam 3110                        | 1        | 1.75%   |
| Genesys Logic USB2.0 Digital Camera   | 1        | 1.75%   |
| Genesys Logic Camera                  | 1        | 1.75%   |
| Generalplus 808 Camera                | 1        | 1.75%   |
| eMPIA M035 Compact Web Cam            | 1        | 1.75%   |
| Creative Live! Cam Chat HD [VF0700]   | 1        | 1.75%   |
| Chicony USB2.0 HD UVC WebCam          | 1        | 1.75%   |
| AVerMedia Live Gamer Ultra-Video      | 1        | 1.75%   |
| ARC International Camera              | 1        | 1.75%   |
| Apple iPhone 5/5C/5S/6/SE             | 1        | 1.75%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Yubico.com            | 1        | 50%     |
| Gemalto (was Gemplus) | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4 CCID                         | 1        | 50%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 223      | 59.63%  |
| 1     | 136      | 36.36%  |
| 2     | 13       | 3.48%   |
| 5     | 1        | 0.27%   |
| 3     | 1        | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 137      | 90.13%  |
| Unassigned class         | 5        | 3.29%   |
| Sound                    | 2        | 1.32%   |
| Net/wireless             | 2        | 1.32%   |
| Multimedia controller    | 2        | 1.32%   |
| Communication controller | 2        | 1.32%   |
| Network                  | 1        | 0.66%   |
| Bluetooth                | 1        | 0.66%   |

