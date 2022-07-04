Zorin 16 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

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

Total: 881

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B360M HD3                   | [b35e9f3e5c](https://linux-hardware.org/?probe=b35e9f3e5c) | Jun 28, 2022 |
| Dell          | 0U880P A00                  | [e14832f09c](https://linux-hardware.org/?probe=e14832f09c) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [6262e08c1f](https://linux-hardware.org/?probe=6262e08c1f) | Jun 26, 2022 |
| Pegatron      | IPPSB-DB                    | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Dell          | 08NPPY A00                  | [3dc935ecb1](https://linux-hardware.org/?probe=3dc935ecb1) | Jun 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c78b132d02](https://linux-hardware.org/?probe=c78b132d02) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [b232a434fd](https://linux-hardware.org/?probe=b232a434fd) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [0297d9c8c1](https://linux-hardware.org/?probe=0297d9c8c1) | Jun 25, 2022 |
| Gigabyte      | Z77-DS3H                    | [fbde5d214f](https://linux-hardware.org/?probe=fbde5d214f) | Jun 24, 2022 |
| Gigabyte      | EP45-UD3P                   | [05449d9e5c](https://linux-hardware.org/?probe=05449d9e5c) | Jun 24, 2022 |
| MSI           | A75A-G35                    | [9e3dd8051c](https://linux-hardware.org/?probe=9e3dd8051c) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [a24305d670](https://linux-hardware.org/?probe=a24305d670) | Jun 23, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [b21a0caebf](https://linux-hardware.org/?probe=b21a0caebf) | Jun 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ecea2bb4ad](https://linux-hardware.org/?probe=ecea2bb4ad) | Jun 22, 2022 |
| Gigabyte      | EX58-UD3R                   | [4014366c8a](https://linux-hardware.org/?probe=4014366c8a) | Jun 21, 2022 |
| Lenovo        | SDK0J40700 WIN              | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| MSI           | B85M-E45                    | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [85a022001e](https://linux-hardware.org/?probe=85a022001e) | Jun 16, 2022 |
| Dell          | 0X501H A02                  | [b9cb2a1e48](https://linux-hardware.org/?probe=b9cb2a1e48) | Jun 15, 2022 |
| Acer          | Aspire M3970                | [b966120966](https://linux-hardware.org/?probe=b966120966) | Jun 14, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [aa63e13a60](https://linux-hardware.org/?probe=aa63e13a60) | Jun 13, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [ba6786bbe8](https://linux-hardware.org/?probe=ba6786bbe8) | Jun 13, 2022 |
| ASUSTek       | P5GC-MX/1333                | [428eebd42f](https://linux-hardware.org/?probe=428eebd42f) | Jun 13, 2022 |
| MSI           | MEG Z690 UNIFY              | [4e227cff8b](https://linux-hardware.org/?probe=4e227cff8b) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2a772cecf4](https://linux-hardware.org/?probe=2a772cecf4) | Jun 12, 2022 |
| ASUSTek       | PRIME B550M-A               | [14b9e721b7](https://linux-hardware.org/?probe=14b9e721b7) | Jun 11, 2022 |
| Dell          | 0XFWHV A00                  | [4102e98034](https://linux-hardware.org/?probe=4102e98034) | Jun 09, 2022 |
| ASUSTek       | Benicia                     | [4b56f8a972](https://linux-hardware.org/?probe=4b56f8a972) | Jun 08, 2022 |
| Dell          | 0WR7PY A03                  | [902546cb45](https://linux-hardware.org/?probe=902546cb45) | Jun 06, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [e993e32a56](https://linux-hardware.org/?probe=e993e32a56) | Jun 06, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [07808a7cbf](https://linux-hardware.org/?probe=07808a7cbf) | Jun 05, 2022 |
| HP            | 8350                        | [63a9e40af6](https://linux-hardware.org/?probe=63a9e40af6) | Jun 05, 2022 |
| Biostar       | A68N-2100K                  | [480a4c12b1](https://linux-hardware.org/?probe=480a4c12b1) | Jun 05, 2022 |
| ASRock        | 970 Extreme3                | [d5648a1a95](https://linux-hardware.org/?probe=d5648a1a95) | Jun 04, 2022 |
| MSI           | B85M-G43                    | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [94c2c3411a](https://linux-hardware.org/?probe=94c2c3411a) | Jun 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9404638832](https://linux-hardware.org/?probe=9404638832) | Jun 03, 2022 |
| BESSTAR Te... | TL50                        | [0455aba8a3](https://linux-hardware.org/?probe=0455aba8a3) | Jun 03, 2022 |
| HP            | 3029h                       | [d536fb8e36](https://linux-hardware.org/?probe=d536fb8e36) | Jun 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [61b90c102c](https://linux-hardware.org/?probe=61b90c102c) | Jun 03, 2022 |
| ASUSTek       | P5E-VM DO                   | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| Biostar       | A78MD                       | [206b04b6d8](https://linux-hardware.org/?probe=206b04b6d8) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [5c9f7b1ab9](https://linux-hardware.org/?probe=5c9f7b1ab9) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [0e1e2765fc](https://linux-hardware.org/?probe=0e1e2765fc) | Jun 01, 2022 |
| Biostar       | A78MD                       | [49ea0bd0e4](https://linux-hardware.org/?probe=49ea0bd0e4) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [951bd2ea8d](https://linux-hardware.org/?probe=951bd2ea8d) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [7bfeaeb75b](https://linux-hardware.org/?probe=7bfeaeb75b) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [3ca7484fcf](https://linux-hardware.org/?probe=3ca7484fcf) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [d078b8d5dd](https://linux-hardware.org/?probe=d078b8d5dd) | May 30, 2022 |
| Gigabyte      | H410M H V3                  | [1dbf357f4f](https://linux-hardware.org/?probe=1dbf357f4f) | May 30, 2022 |
| Gigabyte      | G1.Sniper Z97               | [2c3ba3123f](https://linux-hardware.org/?probe=2c3ba3123f) | May 29, 2022 |
| ASUSTek       | P7P55D DELUXE               | [ba2d55d308](https://linux-hardware.org/?probe=ba2d55d308) | May 29, 2022 |
| ASRock        | B450 Pro4                   | [fa0b4c98df](https://linux-hardware.org/?probe=fa0b4c98df) | May 29, 2022 |
| Dell          | 0HN7XN A01                  | [9ebd09a280](https://linux-hardware.org/?probe=9ebd09a280) | May 29, 2022 |
| Gigabyte      | F2A58M-DS2                  | [3b95da87e9](https://linux-hardware.org/?probe=3b95da87e9) | May 28, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [4e77d22694](https://linux-hardware.org/?probe=4e77d22694) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [1137f80fcd](https://linux-hardware.org/?probe=1137f80fcd) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [57dbc86807](https://linux-hardware.org/?probe=57dbc86807) | May 27, 2022 |
| ASUSTek       | H81M-A/BR                   | [5df43d2ecd](https://linux-hardware.org/?probe=5df43d2ecd) | May 26, 2022 |
| Dell          | 088DT1 A01                  | [19d760099e](https://linux-hardware.org/?probe=19d760099e) | May 25, 2022 |
| Dell          | 088DT1 A01                  | [3334efe1e7](https://linux-hardware.org/?probe=3334efe1e7) | May 25, 2022 |
| Intel         | D946GZIS AAD66165-301       | [24c058da74](https://linux-hardware.org/?probe=24c058da74) | May 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [6e45ae9f7c](https://linux-hardware.org/?probe=6e45ae9f7c) | May 24, 2022 |
| MSI           | MEG Z390 GODLIKE            | [4249d49f41](https://linux-hardware.org/?probe=4249d49f41) | May 22, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [dffc3ea80a](https://linux-hardware.org/?probe=dffc3ea80a) | May 21, 2022 |
| ASUSTek       | Z97-DELUXE                  | [084bacdad3](https://linux-hardware.org/?probe=084bacdad3) | May 21, 2022 |
| MSI           | Z170A GAMING PRO            | [3a9789ed8a](https://linux-hardware.org/?probe=3a9789ed8a) | May 20, 2022 |
| ASUSTek       | PRIME B550M-A               | [1d5fec86a8](https://linux-hardware.org/?probe=1d5fec86a8) | May 20, 2022 |
| MSI           | 760GM-P21                   | [b6b5e0738c](https://linux-hardware.org/?probe=b6b5e0738c) | May 19, 2022 |
| MSI           | B85M-G43                    | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| Foxconn       | 2AAF                        | [dd1193f7ab](https://linux-hardware.org/?probe=dd1193f7ab) | May 18, 2022 |
| ASUSTek       | H81M-K                      | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [2b889fc85b](https://linux-hardware.org/?probe=2b889fc85b) | May 17, 2022 |
| ASUSTek       | G15DK                       | [1df44e40e2](https://linux-hardware.org/?probe=1df44e40e2) | May 17, 2022 |
| Gigabyte      | M61PME-S2P                  | [7ab57b617f](https://linux-hardware.org/?probe=7ab57b617f) | May 17, 2022 |
| Dell          | 0C27VV A01                  | [aea8e14bff](https://linux-hardware.org/?probe=aea8e14bff) | May 17, 2022 |
| Dell          | 0GTK4K A02                  | [fba6de28d9](https://linux-hardware.org/?probe=fba6de28d9) | May 16, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [ebbd363703](https://linux-hardware.org/?probe=ebbd363703) | May 16, 2022 |
| Intel         | D946GZIS AAD66165-301       | [4555cff448](https://linux-hardware.org/?probe=4555cff448) | May 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [7fcd8503ab](https://linux-hardware.org/?probe=7fcd8503ab) | May 16, 2022 |
| ASRock        | A88M-G                      | [81d094b2ec](https://linux-hardware.org/?probe=81d094b2ec) | May 15, 2022 |
| ASRock        | A88M-G                      | [8883591354](https://linux-hardware.org/?probe=8883591354) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0d9d6b919b](https://linux-hardware.org/?probe=0d9d6b919b) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [770fbfefd3](https://linux-hardware.org/?probe=770fbfefd3) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [8baee6f2e6](https://linux-hardware.org/?probe=8baee6f2e6) | May 14, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [08ba1e652c](https://linux-hardware.org/?probe=08ba1e652c) | May 14, 2022 |
| Intel         | DH77EB AAG39073-304         | [f45bf21321](https://linux-hardware.org/?probe=f45bf21321) | May 12, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| Pegatron      | 2A99h                       | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| AOpen         | i67QMx-DV R1.00BC1 55MP6... | [151db99970](https://linux-hardware.org/?probe=151db99970) | May 11, 2022 |
| Acer          | Aspire X3990                | [c6753ff37f](https://linux-hardware.org/?probe=c6753ff37f) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [8f62053ddd](https://linux-hardware.org/?probe=8f62053ddd) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [018c90008f](https://linux-hardware.org/?probe=018c90008f) | May 11, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [b1d977cd69](https://linux-hardware.org/?probe=b1d977cd69) | May 11, 2022 |
| Gigabyte      | EX58-EXTREME                | [b558000bcc](https://linux-hardware.org/?probe=b558000bcc) | May 10, 2022 |
| Dell          | 0DR845                      | [ab501b0efe](https://linux-hardware.org/?probe=ab501b0efe) | May 10, 2022 |
| Gigabyte      | X58A-UD3R                   | [838a99f17a](https://linux-hardware.org/?probe=838a99f17a) | May 10, 2022 |
| Gigabyte      | B365M GAMING HD             | [5590d9a0f3](https://linux-hardware.org/?probe=5590d9a0f3) | May 10, 2022 |
| Dell          | 0GXM1W A02                  | [1606b44e03](https://linux-hardware.org/?probe=1606b44e03) | May 09, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [485a4916ed](https://linux-hardware.org/?probe=485a4916ed) | May 09, 2022 |
| ASRock        | H87M                        | [9c031f1e71](https://linux-hardware.org/?probe=9c031f1e71) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | [bf028580b1](https://linux-hardware.org/?probe=bf028580b1) | May 09, 2022 |
| Gateway       | SX2185                      | [ddb64bc283](https://linux-hardware.org/?probe=ddb64bc283) | May 09, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [be0cecd40a](https://linux-hardware.org/?probe=be0cecd40a) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [9a00d24f58](https://linux-hardware.org/?probe=9a00d24f58) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [3f3089216f](https://linux-hardware.org/?probe=3f3089216f) | May 09, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [5c2fec5833](https://linux-hardware.org/?probe=5c2fec5833) | May 08, 2022 |
| Gigabyte      | H410M H V3                  | [c401229392](https://linux-hardware.org/?probe=c401229392) | May 08, 2022 |
| Gigabyte      | X570 GAMING X               | [ffc6dac164](https://linux-hardware.org/?probe=ffc6dac164) | May 07, 2022 |
| Gigabyte      | H410M H V3                  | [4c6f4d04bb](https://linux-hardware.org/?probe=4c6f4d04bb) | May 07, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [79c87fe48c](https://linux-hardware.org/?probe=79c87fe48c) | May 07, 2022 |
| Gigabyte      | X570 GAMING X               | [816a78b4cd](https://linux-hardware.org/?probe=816a78b4cd) | May 06, 2022 |
| ASUSTek       | 2A73h                       | [458bf998ee](https://linux-hardware.org/?probe=458bf998ee) | May 06, 2022 |
| Intel         | H55                         | [138637d12c](https://linux-hardware.org/?probe=138637d12c) | May 06, 2022 |
| Gigabyte      | G41M-Combo                  | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Gigabyte      | G41MT-S2                    | [fd9ed9a035](https://linux-hardware.org/?probe=fd9ed9a035) | May 05, 2022 |
| HP            | 1906                        | [6f7f0536a9](https://linux-hardware.org/?probe=6f7f0536a9) | May 05, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [31eaff1b28](https://linux-hardware.org/?probe=31eaff1b28) | May 04, 2022 |
| MSI           | B85M-G43                    | [f5deeb2d19](https://linux-hardware.org/?probe=f5deeb2d19) | May 04, 2022 |
| MSI           | Z590 PRO WIFI               | [17aad0bb78](https://linux-hardware.org/?probe=17aad0bb78) | May 03, 2022 |
| HP            | 1906                        | [60ce09d82e](https://linux-hardware.org/?probe=60ce09d82e) | May 03, 2022 |
| Gigabyte      | B365M GAMING HD             | [637890bd75](https://linux-hardware.org/?probe=637890bd75) | May 03, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [7f9e8dd9f6](https://linux-hardware.org/?probe=7f9e8dd9f6) | May 02, 2022 |
| ASUSTek       | H97I-PLUS                   | [c8e857524b](https://linux-hardware.org/?probe=c8e857524b) | May 01, 2022 |
| ASRock        | B365M-HDV                   | [51b0e7e57f](https://linux-hardware.org/?probe=51b0e7e57f) | May 01, 2022 |
| Dell          | 0M017G A01                  | [653212f53c](https://linux-hardware.org/?probe=653212f53c) | May 01, 2022 |
| HP            | 1791                        | [877270ede6](https://linux-hardware.org/?probe=877270ede6) | Apr 30, 2022 |
| Intel         | DCP847SKE G80890-105        | [45dc47c8aa](https://linux-hardware.org/?probe=45dc47c8aa) | Apr 30, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [89323fb22d](https://linux-hardware.org/?probe=89323fb22d) | Apr 30, 2022 |
| Foxconn       | 2A92                        | [298326d530](https://linux-hardware.org/?probe=298326d530) | Apr 30, 2022 |
| Foxconn       | 2A92                        | [a710d4a58f](https://linux-hardware.org/?probe=a710d4a58f) | Apr 30, 2022 |
| Gigabyte      | Z68AP-D3                    | [af8b52acd3](https://linux-hardware.org/?probe=af8b52acd3) | Apr 29, 2022 |
| Gigabyte      | P31-ES3G                    | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [965985d6f4](https://linux-hardware.org/?probe=965985d6f4) | Apr 29, 2022 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [277754d8c1](https://linux-hardware.org/?probe=277754d8c1) | Apr 29, 2022 |
| BESSTAR Te... | HM90                        | [814f90b822](https://linux-hardware.org/?probe=814f90b822) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                    | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [97a2717eb9](https://linux-hardware.org/?probe=97a2717eb9) | Apr 27, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [68fdd1e81a](https://linux-hardware.org/?probe=68fdd1e81a) | Apr 27, 2022 |
| ASUSTek       | Hematite                    | [a6eec927f0](https://linux-hardware.org/?probe=a6eec927f0) | Apr 26, 2022 |
| MSI           | B450 TOMAHAWK               | [148f1cc5e8](https://linux-hardware.org/?probe=148f1cc5e8) | Apr 25, 2022 |
| Dell          | 0HN7XN A01                  | [a282e15540](https://linux-hardware.org/?probe=a282e15540) | Apr 25, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [392c7e4d0d](https://linux-hardware.org/?probe=392c7e4d0d) | Apr 25, 2022 |
| MSI           | 760GM-P21                   | [3582362347](https://linux-hardware.org/?probe=3582362347) | Apr 24, 2022 |
| ASUSTek       | H97I-PLUS                   | [1b392b96c3](https://linux-hardware.org/?probe=1b392b96c3) | Apr 24, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [b36aa38e8a](https://linux-hardware.org/?probe=b36aa38e8a) | Apr 24, 2022 |
| Gigabyte      | A320M-H-CF                  | [da2e3a603d](https://linux-hardware.org/?probe=da2e3a603d) | Apr 23, 2022 |
| Dell          | 0GDG8Y A00                  | [a0ab7e8078](https://linux-hardware.org/?probe=a0ab7e8078) | Apr 22, 2022 |
| Acer          | Nitro N50-600 V:1.1         | [15332404e6](https://linux-hardware.org/?probe=15332404e6) | Apr 21, 2022 |
| Acer          | Nitro N50-600 V:1.1         | [b272388aa6](https://linux-hardware.org/?probe=b272388aa6) | Apr 21, 2022 |
| ASUSTek       | P5GC-MX                     | [810607b312](https://linux-hardware.org/?probe=810607b312) | Apr 20, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [f830e867e5](https://linux-hardware.org/?probe=f830e867e5) | Apr 20, 2022 |
| Gigabyte      | Z68AP-D3                    | [76d25fd5c1](https://linux-hardware.org/?probe=76d25fd5c1) | Apr 20, 2022 |
| MSI           | 2AE0                        | [da90dbf2f2](https://linux-hardware.org/?probe=da90dbf2f2) | Apr 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [73dbb7e52a](https://linux-hardware.org/?probe=73dbb7e52a) | Apr 19, 2022 |
| HP            | 8265                        | [6a7abd0db8](https://linux-hardware.org/?probe=6a7abd0db8) | Apr 19, 2022 |
| Huanan        | X79 249PC V2.2              | [209e881793](https://linux-hardware.org/?probe=209e881793) | Apr 18, 2022 |
| ASRock        | X570 Taichi Razer Editio... | [b3f2a146ea](https://linux-hardware.org/?probe=b3f2a146ea) | Apr 18, 2022 |
| ASRock        | X570 Taichi Razer Editio... | [d597e4df9c](https://linux-hardware.org/?probe=d597e4df9c) | Apr 18, 2022 |
| Acer          | Aspire TC-115               | [16d5411ae8](https://linux-hardware.org/?probe=16d5411ae8) | Apr 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f20c2c3665](https://linux-hardware.org/?probe=f20c2c3665) | Apr 16, 2022 |
| HP            | 845A                        | [cc8c320581](https://linux-hardware.org/?probe=cc8c320581) | Apr 16, 2022 |
| MSI           | 2AE0                        | [b1059198e0](https://linux-hardware.org/?probe=b1059198e0) | Apr 15, 2022 |
| ASRock        | H170M Pro4                  | [0dd1b326c0](https://linux-hardware.org/?probe=0dd1b326c0) | Apr 15, 2022 |
| MSI           | MAG B460M MORTAR            | [eeccee9c29](https://linux-hardware.org/?probe=eeccee9c29) | Apr 15, 2022 |
| ASUSTek       | F2A85-V                     | [6200a8f946](https://linux-hardware.org/?probe=6200a8f946) | Apr 14, 2022 |
| Gigabyte      | Z77-D3H                     | [2ddb0d0765](https://linux-hardware.org/?probe=2ddb0d0765) | Apr 13, 2022 |
| ASRock        | B460M-ITX/ac                | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [ba5d8c783b](https://linux-hardware.org/?probe=ba5d8c783b) | Apr 12, 2022 |
| Gigabyte      | A520 AORUS ELITE            | [a0ff638057](https://linux-hardware.org/?probe=a0ff638057) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [cadff96ec0](https://linux-hardware.org/?probe=cadff96ec0) | Apr 11, 2022 |
| ASUSTek       | H81M-A                      | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [a751b63d6b](https://linux-hardware.org/?probe=a751b63d6b) | Apr 11, 2022 |
| Dell          | 0JP3NX A01                  | [266d7d3a62](https://linux-hardware.org/?probe=266d7d3a62) | Apr 11, 2022 |
| ASRock        | B450 Steel Legend           | [b9b9565fae](https://linux-hardware.org/?probe=b9b9565fae) | Apr 10, 2022 |
| ASUSTek       | P8B75-V                     | [218db09adf](https://linux-hardware.org/?probe=218db09adf) | Apr 10, 2022 |
| Medion        | MS-7366                     | [206ab01c63](https://linux-hardware.org/?probe=206ab01c63) | Apr 10, 2022 |
| Foxconn       | 2A92                        | [d7dc8e0a2b](https://linux-hardware.org/?probe=d7dc8e0a2b) | Apr 10, 2022 |
| ASUSTek       | PRIME Z390-A                | [9f3f45d840](https://linux-hardware.org/?probe=9f3f45d840) | Apr 09, 2022 |
| ASRock        | Z87 Pro4                    | [03ee27c2ea](https://linux-hardware.org/?probe=03ee27c2ea) | Apr 09, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [73628a9025](https://linux-hardware.org/?probe=73628a9025) | Apr 09, 2022 |
| Medion        | MS-7366                     | [86884e1cf1](https://linux-hardware.org/?probe=86884e1cf1) | Apr 09, 2022 |
| ASRock        | H61M-DGS                    | [1d08a53545](https://linux-hardware.org/?probe=1d08a53545) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | [2e37b66578](https://linux-hardware.org/?probe=2e37b66578) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | [e7b1a0df67](https://linux-hardware.org/?probe=e7b1a0df67) | Apr 08, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [fe36e7827a](https://linux-hardware.org/?probe=fe36e7827a) | Apr 08, 2022 |
| ASUSTek       | PRIME Z390-A                | [8ac05d8917](https://linux-hardware.org/?probe=8ac05d8917) | Apr 07, 2022 |
| Gigabyte      | B365M GAMING HD             | [94b6fc5131](https://linux-hardware.org/?probe=94b6fc5131) | Apr 07, 2022 |
| Alienware     | 0H869M A00                  | [f6a1c02c3e](https://linux-hardware.org/?probe=f6a1c02c3e) | Apr 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1592895310](https://linux-hardware.org/?probe=1592895310) | Apr 07, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | [f76a15be2a](https://linux-hardware.org/?probe=f76a15be2a) | Apr 06, 2022 |
| Gigabyte      | Z77-DS3H                    | [a3d3ff5ac5](https://linux-hardware.org/?probe=a3d3ff5ac5) | Apr 06, 2022 |
| Unknown       | Unknown                     | [c8049ac14a](https://linux-hardware.org/?probe=c8049ac14a) | Apr 06, 2022 |
| ASUSTek       | P5GC-MX                     | [ce2aaa12ab](https://linux-hardware.org/?probe=ce2aaa12ab) | Apr 06, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [55eda86e20](https://linux-hardware.org/?probe=55eda86e20) | Apr 05, 2022 |
| Dell          | 09KPNV A00                  | [0a06779a5a](https://linux-hardware.org/?probe=0a06779a5a) | Apr 05, 2022 |
| Foxconn       | 2A92                        | [dd802e925f](https://linux-hardware.org/?probe=dd802e925f) | Apr 05, 2022 |
| MSI           | MS-7204                     | [e04077c3ac](https://linux-hardware.org/?probe=e04077c3ac) | Apr 05, 2022 |
| MSI           | MS-7204                     | [817c6f06bf](https://linux-hardware.org/?probe=817c6f06bf) | Apr 05, 2022 |
| Dell          | 0DR845                      | [26a919fc82](https://linux-hardware.org/?probe=26a919fc82) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | [26032ef606](https://linux-hardware.org/?probe=26032ef606) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | [fed309fdf1](https://linux-hardware.org/?probe=fed309fdf1) | Apr 04, 2022 |
| MSI           | B75A-G41                    | [80ec6aed14](https://linux-hardware.org/?probe=80ec6aed14) | Apr 04, 2022 |
| Unknown       | Unknown                     | [f6bc1c6219](https://linux-hardware.org/?probe=f6bc1c6219) | Apr 03, 2022 |
| ASUSTek       | PRIME X570-P                | [e237e56d72](https://linux-hardware.org/?probe=e237e56d72) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2315db07e2](https://linux-hardware.org/?probe=2315db07e2) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [448e59a9a6](https://linux-hardware.org/?probe=448e59a9a6) | Apr 02, 2022 |
| ASUSTek       | F2A85-V                     | [6056351804](https://linux-hardware.org/?probe=6056351804) | Apr 02, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [0d1d941941](https://linux-hardware.org/?probe=0d1d941941) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [fc477a4cb4](https://linux-hardware.org/?probe=fc477a4cb4) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [23b384fa80](https://linux-hardware.org/?probe=23b384fa80) | Apr 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [e94a772f2b](https://linux-hardware.org/?probe=e94a772f2b) | Apr 02, 2022 |
| Biostar       | X370GT5                     | [efe58d6ab1](https://linux-hardware.org/?probe=efe58d6ab1) | Mar 31, 2022 |
| MSI           | P45 Neo2-FR                 | [23fa0ec187](https://linux-hardware.org/?probe=23fa0ec187) | Mar 31, 2022 |
| Google        | Panther                     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| Gigabyte      | G1.Sniper B6-CF             | [17ea484809](https://linux-hardware.org/?probe=17ea484809) | Mar 29, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [99acee5d56](https://linux-hardware.org/?probe=99acee5d56) | Mar 29, 2022 |
| Intel         | DH55HC AAE70933-505         | [0a58762fd9](https://linux-hardware.org/?probe=0a58762fd9) | Mar 29, 2022 |
| HP            | 18E5                        | [39cb47db55](https://linux-hardware.org/?probe=39cb47db55) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [a50c8cdd0d](https://linux-hardware.org/?probe=a50c8cdd0d) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [5f779f4af0](https://linux-hardware.org/?probe=5f779f4af0) | Mar 27, 2022 |
| Pegatron      | Benicia                     | [cd70e5d6f6](https://linux-hardware.org/?probe=cd70e5d6f6) | Mar 27, 2022 |
| HP            | 18E5                        | [061d716ce1](https://linux-hardware.org/?probe=061d716ce1) | Mar 27, 2022 |
| ASRock        | H61M-HVS                    | [7ebb094ad8](https://linux-hardware.org/?probe=7ebb094ad8) | Mar 25, 2022 |
| Dell          | 0P096C A01                  | [fff71ec7de](https://linux-hardware.org/?probe=fff71ec7de) | Mar 24, 2022 |
| Gigabyte      | H67MA-USB3-B3               | [c5ad9a2c99](https://linux-hardware.org/?probe=c5ad9a2c99) | Mar 24, 2022 |
| ASUSTek       | H81M-A                      | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| ASUSTek       | H81M-CS/BR                  | [17a0a5394e](https://linux-hardware.org/?probe=17a0a5394e) | Mar 24, 2022 |
| Dell          | 0KWVT8 A00                  | [5e2b36f808](https://linux-hardware.org/?probe=5e2b36f808) | Mar 24, 2022 |
| ASRock        | B550 Steel Legend           | [5c1495ecf1](https://linux-hardware.org/?probe=5c1495ecf1) | Mar 21, 2022 |
| ASRock        | B550 Steel Legend           | [00ea7017ff](https://linux-hardware.org/?probe=00ea7017ff) | Mar 20, 2022 |
| Gigabyte      | Z690 UD DDR4                | [03bfb9a66b](https://linux-hardware.org/?probe=03bfb9a66b) | Mar 20, 2022 |
| ASUSTek       | NODUSM3                     | [14c35dc52c](https://linux-hardware.org/?probe=14c35dc52c) | Mar 20, 2022 |
| Dell          | 0GDG8Y A00                  | [1deed3b4bb](https://linux-hardware.org/?probe=1deed3b4bb) | Mar 20, 2022 |
| Biostar       | B460GTQ                     | [7c912f57c6](https://linux-hardware.org/?probe=7c912f57c6) | Mar 20, 2022 |
| HP            | 1497                        | [2aac5eaf08](https://linux-hardware.org/?probe=2aac5eaf08) | Mar 19, 2022 |
| HP            | 1497                        | [ec392b9979](https://linux-hardware.org/?probe=ec392b9979) | Mar 19, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [3ba6de8cdd](https://linux-hardware.org/?probe=3ba6de8cdd) | Mar 19, 2022 |
| Dell          | 09KPNV A00                  | [f71ac898a8](https://linux-hardware.org/?probe=f71ac898a8) | Mar 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [34fb0ae26f](https://linux-hardware.org/?probe=34fb0ae26f) | Mar 19, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7cafe0766c](https://linux-hardware.org/?probe=7cafe0766c) | Mar 18, 2022 |
| ASUSTek       | Hematite                    | [e4258e3376](https://linux-hardware.org/?probe=e4258e3376) | Mar 17, 2022 |
| ASUSTek       | M2A-VM HDMI                 | [ea35877485](https://linux-hardware.org/?probe=ea35877485) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | [0af153934b](https://linux-hardware.org/?probe=0af153934b) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | [2071129adb](https://linux-hardware.org/?probe=2071129adb) | Mar 17, 2022 |
| Shuttle       | X50V2PLUS V1.00             | [0bd650dfff](https://linux-hardware.org/?probe=0bd650dfff) | Mar 16, 2022 |
| Dell          | 0WMJ54 A01                  | [fe21b2c644](https://linux-hardware.org/?probe=fe21b2c644) | Mar 15, 2022 |
| HP            | 1791                        | [f183c3d0f0](https://linux-hardware.org/?probe=f183c3d0f0) | Mar 15, 2022 |
| HP            | 1497                        | [0aaa7bf906](https://linux-hardware.org/?probe=0aaa7bf906) | Mar 15, 2022 |
| TYAN Compu... | D2568 S26361-D2568-A11      | [fd7cbc2300](https://linux-hardware.org/?probe=fd7cbc2300) | Mar 15, 2022 |
| Dell          | 0CU409                      | [2e684afab9](https://linux-hardware.org/?probe=2e684afab9) | Mar 14, 2022 |
| MSI           | B85M-G43                    | [3869d4fdc0](https://linux-hardware.org/?probe=3869d4fdc0) | Mar 14, 2022 |
| ASUSTek       | Maximus VIII GENE           | [f264de34b1](https://linux-hardware.org/?probe=f264de34b1) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | [fd7e52fdd3](https://linux-hardware.org/?probe=fd7e52fdd3) | Mar 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [a90ce91192](https://linux-hardware.org/?probe=a90ce91192) | Mar 12, 2022 |
| ASUSTek       | P8P67                       | [33bf33cb8d](https://linux-hardware.org/?probe=33bf33cb8d) | Mar 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | [67ead34e9e](https://linux-hardware.org/?probe=67ead34e9e) | Mar 10, 2022 |
| Google        | Buddy                       | [848034437d](https://linux-hardware.org/?probe=848034437d) | Mar 09, 2022 |
| Google        | Buddy                       | [db18fd0c96](https://linux-hardware.org/?probe=db18fd0c96) | Mar 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [798e5f6c43](https://linux-hardware.org/?probe=798e5f6c43) | Mar 09, 2022 |
| MSI           | H110M PRO-VH PLUS           | [fc3707d356](https://linux-hardware.org/?probe=fc3707d356) | Mar 09, 2022 |
| ASUSTek       | P5E-VM DO                   | [876e876df1](https://linux-hardware.org/?probe=876e876df1) | Mar 09, 2022 |
| MSI           | A75A-G35                    | [8dfa30cef5](https://linux-hardware.org/?probe=8dfa30cef5) | Mar 07, 2022 |
| ASUSTek       | Z97-DELUXE                  | [7ea271a455](https://linux-hardware.org/?probe=7ea271a455) | Mar 05, 2022 |
| MSI           | B85M-G43                    | [d5e3087569](https://linux-hardware.org/?probe=d5e3087569) | Mar 04, 2022 |
| Intel         | H61                         | [86f2038ab2](https://linux-hardware.org/?probe=86f2038ab2) | Mar 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | [78089f6e8c](https://linux-hardware.org/?probe=78089f6e8c) | Mar 03, 2022 |
| Gigabyte      | Z77-DS3H                    | [16268a74aa](https://linux-hardware.org/?probe=16268a74aa) | Mar 03, 2022 |
| MSI           | A68HM-E33 V2                | [53dd60c906](https://linux-hardware.org/?probe=53dd60c906) | Mar 02, 2022 |
| ASUSTek       | PRIME X370-PRO              | [b74317d80e](https://linux-hardware.org/?probe=b74317d80e) | Mar 02, 2022 |
| ASRock        | H110M-DGS R3.0              | [d7b8815296](https://linux-hardware.org/?probe=d7b8815296) | Feb 28, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | [61f8410abd](https://linux-hardware.org/?probe=61f8410abd) | Feb 28, 2022 |
| BESSTAR Te... | TL50                        | [54383b0005](https://linux-hardware.org/?probe=54383b0005) | Feb 28, 2022 |
| HP            | 821D                        | [fdfcbe172a](https://linux-hardware.org/?probe=fdfcbe172a) | Feb 28, 2022 |
| Acer          | Aspire TC-875 V:1.0         | [47018f3ae4](https://linux-hardware.org/?probe=47018f3ae4) | Feb 28, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| ASRock        | H77M                        | [e49dce2077](https://linux-hardware.org/?probe=e49dce2077) | Feb 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | [ac9099b0e4](https://linux-hardware.org/?probe=ac9099b0e4) | Feb 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | [52c633564d](https://linux-hardware.org/?probe=52c633564d) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| MSI           | B85M-E45                    | [42fba9424e](https://linux-hardware.org/?probe=42fba9424e) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [e1ba37c64a](https://linux-hardware.org/?probe=e1ba37c64a) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [5d56069677](https://linux-hardware.org/?probe=5d56069677) | Feb 27, 2022 |
| Gigabyte      | N3160TN                     | [f080ac90fa](https://linux-hardware.org/?probe=f080ac90fa) | Feb 26, 2022 |
| ASUSTek       | PRIME H510M-D               | [5e8e80fa4c](https://linux-hardware.org/?probe=5e8e80fa4c) | Feb 25, 2022 |
| Intel         | X79M-S                      | [a175e713d6](https://linux-hardware.org/?probe=a175e713d6) | Feb 25, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [c9447d244f](https://linux-hardware.org/?probe=c9447d244f) | Feb 24, 2022 |
| Gigabyte      | Z87-HD3                     | [d1fd917c74](https://linux-hardware.org/?probe=d1fd917c74) | Feb 24, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [40de7f3fd4](https://linux-hardware.org/?probe=40de7f3fd4) | Feb 23, 2022 |
| Medion        | MS-7707                     | [563fc4ee5a](https://linux-hardware.org/?probe=563fc4ee5a) | Feb 23, 2022 |
| Medion        | MS-7707                     | [f3b9e8796b](https://linux-hardware.org/?probe=f3b9e8796b) | Feb 23, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [8efe63496f](https://linux-hardware.org/?probe=8efe63496f) | Feb 22, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [979289afcb](https://linux-hardware.org/?probe=979289afcb) | Feb 21, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [62fc974ec7](https://linux-hardware.org/?probe=62fc974ec7) | Feb 21, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [435006f81f](https://linux-hardware.org/?probe=435006f81f) | Feb 20, 2022 |
| Gigabyte      | B560M AORUS ELITE           | [9264e93f98](https://linux-hardware.org/?probe=9264e93f98) | Feb 20, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [1990e2040f](https://linux-hardware.org/?probe=1990e2040f) | Feb 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [c545739154](https://linux-hardware.org/?probe=c545739154) | Feb 18, 2022 |
| ASUSTek       | P5E-VM DO                   | [c204579cc4](https://linux-hardware.org/?probe=c204579cc4) | Feb 18, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [bccc2f8988](https://linux-hardware.org/?probe=bccc2f8988) | Feb 18, 2022 |
| MSI           | B360M PRO-VDH               | [dfb03c38d4](https://linux-hardware.org/?probe=dfb03c38d4) | Feb 18, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| ASUSTek       | P8P67                       | [e52f9b0748](https://linux-hardware.org/?probe=e52f9b0748) | Feb 15, 2022 |
| HP            | 2B15A                       | [ca58e13d8f](https://linux-hardware.org/?probe=ca58e13d8f) | Feb 15, 2022 |
| Pegatron      | 2AC2                        | [092df404d4](https://linux-hardware.org/?probe=092df404d4) | Feb 15, 2022 |
| ASUSTek       | PRIME X370-PRO              | [54a56f3b09](https://linux-hardware.org/?probe=54a56f3b09) | Feb 15, 2022 |
| Intel         | X79M-S                      | [b655865606](https://linux-hardware.org/?probe=b655865606) | Feb 14, 2022 |
| IBM           | 81077AG                     | [934878ed63](https://linux-hardware.org/?probe=934878ed63) | Feb 14, 2022 |
| ASUSTek       | P8H61-M EVO                 | [40ed7abcc5](https://linux-hardware.org/?probe=40ed7abcc5) | Feb 14, 2022 |
| ASRock        | X299 Taichi                 | [cb4047cf07](https://linux-hardware.org/?probe=cb4047cf07) | Feb 13, 2022 |
| ASUSTek       | P8H61-M EVO                 | [94bcb91d02](https://linux-hardware.org/?probe=94bcb91d02) | Feb 13, 2022 |
| ASRock        | 970A-G                      | [7b3694013f](https://linux-hardware.org/?probe=7b3694013f) | Feb 13, 2022 |
| HP            | 0B54h D                     | [c9f9611ea4](https://linux-hardware.org/?probe=c9f9611ea4) | Feb 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | [d97414cfe4](https://linux-hardware.org/?probe=d97414cfe4) | Feb 12, 2022 |
| Dell          | 0T10XW A01                  | [a9034f065e](https://linux-hardware.org/?probe=a9034f065e) | Feb 11, 2022 |
| Dell          | 0T10XW A01                  | [c0cce21524](https://linux-hardware.org/?probe=c0cce21524) | Feb 11, 2022 |
| Intel         | H61                         | [e06357425a](https://linux-hardware.org/?probe=e06357425a) | Feb 11, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [b79b4aaf10](https://linux-hardware.org/?probe=b79b4aaf10) | Feb 11, 2022 |
| HP            | 198E                        | [f4781dd683](https://linux-hardware.org/?probe=f4781dd683) | Feb 10, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [0c13bfa27b](https://linux-hardware.org/?probe=0c13bfa27b) | Feb 10, 2022 |
| Dell          | 096JG8 A01                  | [c56c62ab01](https://linux-hardware.org/?probe=c56c62ab01) | Feb 10, 2022 |
| Gigabyte      | Z87N-WIFI                   | [e86fa9ee02](https://linux-hardware.org/?probe=e86fa9ee02) | Feb 09, 2022 |
| Gigabyte      | Z87N-WIFI                   | [1b6aa0ce08](https://linux-hardware.org/?probe=1b6aa0ce08) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [961be2a608](https://linux-hardware.org/?probe=961be2a608) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [4ab26645c2](https://linux-hardware.org/?probe=4ab26645c2) | Feb 09, 2022 |
| HP            | 8350                        | [31f2f10b25](https://linux-hardware.org/?probe=31f2f10b25) | Feb 08, 2022 |
| HP            | 1906                        | [c2107ad290](https://linux-hardware.org/?probe=c2107ad290) | Feb 08, 2022 |
| HP            | 1906                        | [9f08673e43](https://linux-hardware.org/?probe=9f08673e43) | Feb 08, 2022 |
| MSI           | 2AE0                        | [7026cf0c86](https://linux-hardware.org/?probe=7026cf0c86) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [cec6148a23](https://linux-hardware.org/?probe=cec6148a23) | Feb 07, 2022 |
| MSI           | B85M-E45                    | [3653d29a0a](https://linux-hardware.org/?probe=3653d29a0a) | Feb 07, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [c5db8c7811](https://linux-hardware.org/?probe=c5db8c7811) | Feb 06, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [96e92c90a5](https://linux-hardware.org/?probe=96e92c90a5) | Feb 06, 2022 |
| Gigabyte      | G1.Sniper Z97               | [5ef683a8ed](https://linux-hardware.org/?probe=5ef683a8ed) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [81b3cfa233](https://linux-hardware.org/?probe=81b3cfa233) | Feb 06, 2022 |
| Acer          | Aspire TC-115               | [03188d20fc](https://linux-hardware.org/?probe=03188d20fc) | Feb 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [80cf2c4065](https://linux-hardware.org/?probe=80cf2c4065) | Feb 04, 2022 |
| ASUSTek       | Maximus V GENE              | [749946734b](https://linux-hardware.org/?probe=749946734b) | Feb 03, 2022 |
| Dell          | 0HN7XN A01                  | [5bb62c21b7](https://linux-hardware.org/?probe=5bb62c21b7) | Feb 03, 2022 |
| ASUSTek       | M4A785-M                    | [421c016644](https://linux-hardware.org/?probe=421c016644) | Feb 02, 2022 |
| Gigabyte      | B450 AORUS M                | [b76b53bf53](https://linux-hardware.org/?probe=b76b53bf53) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | [45f03f7991](https://linux-hardware.org/?probe=45f03f7991) | Jan 31, 2022 |
| Gigabyte      | B450 AORUS M                | [690eba21e0](https://linux-hardware.org/?probe=690eba21e0) | Jan 30, 2022 |
| Dell          | 0HN7XN A01                  | [af1d1e8c47](https://linux-hardware.org/?probe=af1d1e8c47) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [7450ea2cad](https://linux-hardware.org/?probe=7450ea2cad) | Jan 30, 2022 |
| ASRock        | H81M-DGS                    | [05fc3bd63b](https://linux-hardware.org/?probe=05fc3bd63b) | Jan 29, 2022 |
| HP            | 3047h                       | [48f624cbea](https://linux-hardware.org/?probe=48f624cbea) | Jan 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bcdcd2eeb6](https://linux-hardware.org/?probe=bcdcd2eeb6) | Jan 29, 2022 |
| ASUSTek       | M2A74-AM SE                 | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| MSI           | 2AE0                        | [1a55336eb9](https://linux-hardware.org/?probe=1a55336eb9) | Jan 28, 2022 |
| Gigabyte      | GA-MA790GP-DS4H             | [ef8894e69d](https://linux-hardware.org/?probe=ef8894e69d) | Jan 28, 2022 |
| Wortmann      | TERRA_PC                    | [4fea20e2bf](https://linux-hardware.org/?probe=4fea20e2bf) | Jan 28, 2022 |
| Dell          | 0Y2MRG A00                  | [1a1b794c06](https://linux-hardware.org/?probe=1a1b794c06) | Jan 28, 2022 |
| Gigabyte      | Z270N-WIFI-CF               | [78f310c42a](https://linux-hardware.org/?probe=78f310c42a) | Jan 27, 2022 |
| ASRock        | G31M-S                      | [e579ce1757](https://linux-hardware.org/?probe=e579ce1757) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | [2c70e74055](https://linux-hardware.org/?probe=2c70e74055) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | [6a692a4e11](https://linux-hardware.org/?probe=6a692a4e11) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [72374dc22c](https://linux-hardware.org/?probe=72374dc22c) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [78cdf0490a](https://linux-hardware.org/?probe=78cdf0490a) | Jan 26, 2022 |
| Dell          | 07KY25 A00                  | [102d10e806](https://linux-hardware.org/?probe=102d10e806) | Jan 26, 2022 |
| MSI           | H97 GAMING 3                | [75f4b47111](https://linux-hardware.org/?probe=75f4b47111) | Jan 26, 2022 |
| Dell          | 06NWYK A01                  | [dbc44c9f4a](https://linux-hardware.org/?probe=dbc44c9f4a) | Jan 25, 2022 |
| HP            | 1497                        | [a32eadf3ab](https://linux-hardware.org/?probe=a32eadf3ab) | Jan 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e521380180](https://linux-hardware.org/?probe=e521380180) | Jan 25, 2022 |
| ASUSTek       | Q87T                        | [1bcaa6dedf](https://linux-hardware.org/?probe=1bcaa6dedf) | Jan 24, 2022 |
| Foxconn       | 2ABF                        | [e5723eaa42](https://linux-hardware.org/?probe=e5723eaa42) | Jan 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a0034083eb](https://linux-hardware.org/?probe=a0034083eb) | Jan 22, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [2a8b893eb6](https://linux-hardware.org/?probe=2a8b893eb6) | Jan 22, 2022 |
| Foxconn       | 2ABF                        | [af38735785](https://linux-hardware.org/?probe=af38735785) | Jan 22, 2022 |
| MSI           | A75A-G35                    | [e2148dff19](https://linux-hardware.org/?probe=e2148dff19) | Jan 22, 2022 |
| Dell          | 0CU409                      | [8fc6c3decf](https://linux-hardware.org/?probe=8fc6c3decf) | Jan 21, 2022 |
| Dell          | 0CU409                      | [953718318f](https://linux-hardware.org/?probe=953718318f) | Jan 21, 2022 |
| Gigabyte      | F2A58M-DS2                  | [a89dd04d3a](https://linux-hardware.org/?probe=a89dd04d3a) | Jan 20, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [586012f45e](https://linux-hardware.org/?probe=586012f45e) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | [2ab8f0375c](https://linux-hardware.org/?probe=2ab8f0375c) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | [5308c77880](https://linux-hardware.org/?probe=5308c77880) | Jan 19, 2022 |
| ASUSTek       | H81M-K                      | [637ad5d9e4](https://linux-hardware.org/?probe=637ad5d9e4) | Jan 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [ffaca9cabf](https://linux-hardware.org/?probe=ffaca9cabf) | Jan 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [940b702411](https://linux-hardware.org/?probe=940b702411) | Jan 16, 2022 |
| MSI           | H61M-P25                    | [3433cb58a1](https://linux-hardware.org/?probe=3433cb58a1) | Jan 14, 2022 |
| MSI           | MS-7053                     | [8844db2984](https://linux-hardware.org/?probe=8844db2984) | Jan 13, 2022 |
| EVGA          | 152-HR-E979                 | [669c7a3ef6](https://linux-hardware.org/?probe=669c7a3ef6) | Jan 12, 2022 |
| EVGA          | 152-HR-E979                 | [075a31a3c5](https://linux-hardware.org/?probe=075a31a3c5) | Jan 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [368df270dc](https://linux-hardware.org/?probe=368df270dc) | Jan 11, 2022 |
| Gigabyte      | F2A58M-DS2                  | [b7ee3c3e93](https://linux-hardware.org/?probe=b7ee3c3e93) | Jan 11, 2022 |
| ASUSTek       | P8H61-I R2.0                | [5b08de311b](https://linux-hardware.org/?probe=5b08de311b) | Jan 10, 2022 |
| Dell          | 06NWYK A01                  | [98c10ce544](https://linux-hardware.org/?probe=98c10ce544) | Jan 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [6759388aa1](https://linux-hardware.org/?probe=6759388aa1) | Jan 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [6a368aefbd](https://linux-hardware.org/?probe=6a368aefbd) | Jan 09, 2022 |
| ASUSTek       | PRIME H310M-K               | [3b4d6e5abd](https://linux-hardware.org/?probe=3b4d6e5abd) | Jan 08, 2022 |
| ASRock        | G31M-S                      | [b33a983889](https://linux-hardware.org/?probe=b33a983889) | Jan 08, 2022 |
| MSI           | H61M-P25                    | [5f095c2bf8](https://linux-hardware.org/?probe=5f095c2bf8) | Jan 08, 2022 |
| Dell          | 042P49 A02                  | [b2a3538121](https://linux-hardware.org/?probe=b2a3538121) | Jan 08, 2022 |
| ASRock        | AM1B-ITX                    | [c374329271](https://linux-hardware.org/?probe=c374329271) | Jan 07, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [e51ad2ec06](https://linux-hardware.org/?probe=e51ad2ec06) | Jan 07, 2022 |
| Dell          | 0YXT71 A02                  | [682c40786b](https://linux-hardware.org/?probe=682c40786b) | Jan 07, 2022 |
| Gigabyte      | H61M-S2PV                   | [398f9ebe03](https://linux-hardware.org/?probe=398f9ebe03) | Jan 06, 2022 |
| ASUSTek       | Benicia                     | [5459dba29c](https://linux-hardware.org/?probe=5459dba29c) | Jan 06, 2022 |
| Dell          | 0GDG8Y A00                  | [e89e415451](https://linux-hardware.org/?probe=e89e415451) | Jan 05, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [fc860fdb7a](https://linux-hardware.org/?probe=fc860fdb7a) | Jan 05, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [dad1a9143d](https://linux-hardware.org/?probe=dad1a9143d) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | [5694489e55](https://linux-hardware.org/?probe=5694489e55) | Jan 05, 2022 |
| Gigabyte      | H370M D3H-CF                | [ab12119d4f](https://linux-hardware.org/?probe=ab12119d4f) | Jan 05, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [32d0fda197](https://linux-hardware.org/?probe=32d0fda197) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | [2c3f24c851](https://linux-hardware.org/?probe=2c3f24c851) | Jan 04, 2022 |
| MSI           | H61M-P25                    | [3679d16bdb](https://linux-hardware.org/?probe=3679d16bdb) | Jan 04, 2022 |
| HP            | 3047h                       | [8faa43060a](https://linux-hardware.org/?probe=8faa43060a) | Jan 04, 2022 |
| MSI           | H61M-P25                    | [004392f0ef](https://linux-hardware.org/?probe=004392f0ef) | Jan 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [b838b1e1cc](https://linux-hardware.org/?probe=b838b1e1cc) | Jan 04, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [d2a528221c](https://linux-hardware.org/?probe=d2a528221c) | Jan 03, 2022 |
| ASRock        | B450M Steel Legend          | [81a98f588a](https://linux-hardware.org/?probe=81a98f588a) | Jan 02, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [a769ac4242](https://linux-hardware.org/?probe=a769ac4242) | Jan 01, 2022 |
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
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [69d74c89b4](https://linux-hardware.org/?probe=69d74c89b4) | Dec 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4453e33b88](https://linux-hardware.org/?probe=4453e33b88) | Dec 22, 2021 |
| ASRock        | B450 Pro4                   | [0832f6d0fd](https://linux-hardware.org/?probe=0832f6d0fd) | Dec 22, 2021 |
| ASUSTek       | P8Z77-M                     | [667e676c78](https://linux-hardware.org/?probe=667e676c78) | Dec 21, 2021 |
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
| Dell          | 0Y2K8N A01                  | [2e29930670](https://linux-hardware.org/?probe=2e29930670) | Dec 17, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [dfbadf6708](https://linux-hardware.org/?probe=dfbadf6708) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | [cd4d96fefa](https://linux-hardware.org/?probe=cd4d96fefa) | Dec 17, 2021 |
| Acer          | Aspire XC-330               | [61dd8de51b](https://linux-hardware.org/?probe=61dd8de51b) | Dec 16, 2021 |
| Dell          | 0D24M8 A01                  | [a306863279](https://linux-hardware.org/?probe=a306863279) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| HP            | 18E5                        | [88f87a7a1b](https://linux-hardware.org/?probe=88f87a7a1b) | Dec 14, 2021 |
| ASUSTek       | AM1M-A                      | [5113655631](https://linux-hardware.org/?probe=5113655631) | Dec 14, 2021 |
| HP            | 2179                        | [c2dd79384a](https://linux-hardware.org/?probe=c2dd79384a) | Dec 14, 2021 |
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
| HP            | 2179                        | [121210497a](https://linux-hardware.org/?probe=121210497a) | Nov 25, 2021 |
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
| ASUSTek       | TUF Gaming X570-PRO         | [0625659706](https://linux-hardware.org/?probe=0625659706) | Sep 27, 2021 |
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
| Sapphire      | Pure Platinum 970A-PLUS     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| ASRock        | FM2A58M-DG3+                | [183fc0dd5e](https://linux-hardware.org/?probe=183fc0dd5e) | Sep 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bc3e2da7f3](https://linux-hardware.org/?probe=bc3e2da7f3) | Sep 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [e8f361170f](https://linux-hardware.org/?probe=e8f361170f) | Sep 18, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [30f36dc15d](https://linux-hardware.org/?probe=30f36dc15d) | Sep 17, 2021 |
| ASRock        | B450 Pro4                   | [042032eec7](https://linux-hardware.org/?probe=042032eec7) | Sep 16, 2021 |
| Intel         | X99                         | [814b3326d1](https://linux-hardware.org/?probe=814b3326d1) | Sep 15, 2021 |
| NCR           | Talladega                   | [95445fa221](https://linux-hardware.org/?probe=95445fa221) | Sep 14, 2021 |
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
| Gigabyte      | 970A-DS3P                   | [8b0f703471](https://linux-hardware.org/?probe=8b0f703471) | Sep 11, 2021 |
| Lenovo        | SDK0E50519 WIN              | [7c58527193](https://linux-hardware.org/?probe=7c58527193) | Sep 11, 2021 |
| Intel         | X79M-S                      | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| ASUSTek       | P5GC-MX/1333                | [1ff7b16ce4](https://linux-hardware.org/?probe=1ff7b16ce4) | Sep 10, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [dab9a23b27](https://linux-hardware.org/?probe=dab9a23b27) | Sep 10, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [34e6b7697f](https://linux-hardware.org/?probe=34e6b7697f) | Sep 09, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [5ce713a2f7](https://linux-hardware.org/?probe=5ce713a2f7) | Sep 09, 2021 |
| HP            | 2187 A01                    | [0c11e3b726](https://linux-hardware.org/?probe=0c11e3b726) | Sep 09, 2021 |
| MSI           | B450M MORTAR MAX            | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| Dell          | 09KPNV A01                  | [f3c9b271f1](https://linux-hardware.org/?probe=f3c9b271f1) | Sep 08, 2021 |
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
| HP            | 339A                        | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | 339A                        | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4c711d446d](https://linux-hardware.org/?probe=4c711d446d) | Aug 31, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [efb9bccc60](https://linux-hardware.org/?probe=efb9bccc60) | Aug 31, 2021 |
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


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.11.0-38-generic           | 62       | 9.41%   |
| 5.11.0-27-generic           | 56       | 8.5%    |
| 5.11.0-40-generic           | 50       | 7.59%   |
| 5.13.0-39-generic           | 48       | 7.28%   |
| 5.11.0-41-generic           | 41       | 6.22%   |
| 5.13.0-40-generic           | 38       | 5.77%   |
| 5.11.0-43-generic           | 36       | 5.46%   |
| 5.11.0-37-generic           | 35       | 5.31%   |
| 5.13.0-30-generic           | 31       | 4.7%    |
| 5.11.0-34-generic           | 31       | 4.7%    |
| 5.13.0-28-generic           | 29       | 4.4%    |
| 5.13.0-35-generic           | 27       | 4.1%    |
| 5.13.0-27-generic           | 26       | 3.95%   |
| 5.13.0-41-generic           | 25       | 3.79%   |
| 5.13.0-44-generic           | 22       | 3.34%   |
| 5.11.0-44-generic           | 14       | 2.12%   |
| 5.13.0-51-generic           | 13       | 1.97%   |
| 5.11.0-36-generic           | 12       | 1.82%   |
| 5.13.0-37-generic           | 11       | 1.67%   |
| 5.8.0-53-generic            | 7        | 1.06%   |
| 5.13.0-48-generic           | 7        | 1.06%   |
| 5.11.0-46-generic           | 6        | 0.91%   |
| 5.8.0-50-generic            | 5        | 0.76%   |
| 5.8.0-59-generic            | 4        | 0.61%   |
| 5.8.0-55-generic            | 4        | 0.61%   |
| 5.11.0-25-generic           | 4        | 0.61%   |
| 5.8.0-49-generic            | 3        | 0.46%   |
| 5.8.0-63-generic            | 2        | 0.3%    |
| 5.13.0-25-generic           | 2        | 0.3%    |
| 5.8.0-45-generic            | 1        | 0.15%   |
| 5.4.0-58-generic            | 1        | 0.15%   |
| 5.17.9-051709-generic       | 1        | 0.15%   |
| 5.17.1-051701-generic       | 1        | 0.15%   |
| 5.15.13-051513-generic      | 1        | 0.15%   |
| 5.15.0-10.2-liquorix-amd64  | 1        | 0.15%   |
| 5.14.0-1010-oem             | 1        | 0.15%   |
| 5.13.0-352203222222-generic | 1        | 0.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 333      | 53.88%  |
| 5.13.0  | 254      | 41.1%   |
| 5.8.0   | 25       | 4.05%   |
| 5.4.0   | 1        | 0.16%   |
| 5.17.9  | 1        | 0.16%   |
| 5.17.1  | 1        | 0.16%   |
| 5.15.13 | 1        | 0.16%   |
| 5.15.0  | 1        | 0.16%   |
| 5.14.0  | 1        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 333      | 53.88%  |
| 5.13    | 254      | 41.1%   |
| 5.8     | 25       | 4.05%   |
| 5.17    | 2        | 0.32%   |
| 5.15    | 2        | 0.32%   |
| 5.4     | 1        | 0.16%   |
| 5.14    | 1        | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 601      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME    | 547      | 90.56%  |
| XFCE     | 51       | 8.44%   |
| Unknown  | 4        | 0.66%   |
| MATE     | 1        | 0.17%   |
| Cinnamon | 1        | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 599      | 99.17%  |
| Wayland | 3        | 0.5%    |
| Tty     | 1        | 0.17%   |
| Unknown | 1        | 0.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 513      | 84.79%  |
| GDM3    | 45       | 7.44%   |
| GDM     | 39       | 6.45%   |
| LightDM | 7        | 1.16%   |
| TDM     | 1        | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 236      | 39.2%   |
| de_DE       | 68       | 11.3%   |
| en_GB       | 47       | 7.81%   |
| pt_BR       | 40       | 6.64%   |
| pl_PL       | 19       | 3.16%   |
| es_ES       | 17       | 2.82%   |
| it_IT       | 15       | 2.49%   |
| nl_NL       | 14       | 2.33%   |
| fr_FR       | 14       | 2.33%   |
| en_CA       | 14       | 2.33%   |
| en_AU       | 12       | 1.99%   |
| ru_RU       | 10       | 1.66%   |
| en_IN       | 10       | 1.66%   |
| es_MX       | 8        | 1.33%   |
| hu_HU       | 6        | 1%      |
| es_AR       | 6        | 1%      |
| fr_CA       | 5        | 0.83%   |
| en_ZA       | 5        | 0.83%   |
| tr_TR       | 4        | 0.66%   |
| pt_PT       | 4        | 0.66%   |
| cs_CZ       | 4        | 0.66%   |
| sv_SE       | 3        | 0.5%    |
| nl_BE       | 3        | 0.5%    |
| el_GR       | 3        | 0.5%    |
| da_DK       | 3        | 0.5%    |
| sl_SI       | 2        | 0.33%   |
| ja_JP       | 2        | 0.33%   |
| es_EC       | 2        | 0.33%   |
| es_CL       | 2        | 0.33%   |
| en_NZ       | 2        | 0.33%   |
| de_CH       | 2        | 0.33%   |
| ar_EG       | 2        | 0.33%   |
| zh_TW       | 1        | 0.17%   |
| zh_CN       | 1        | 0.17%   |
| sr_RS@latin | 1        | 0.17%   |
| sr_RS       | 1        | 0.17%   |
| sk_SK       | 1        | 0.17%   |
| ru_UA       | 1        | 0.17%   |
| nb_NO       | 1        | 0.17%   |
| hr_HR       | 1        | 0.17%   |
| he_IL       | 1        | 0.17%   |
| fr_CH       | 1        | 0.17%   |
| es_VE       | 1        | 0.17%   |
| es_PE       | 1        | 0.17%   |
| es_PA       | 1        | 0.17%   |
| es_NI       | 1        | 0.17%   |
| es_GT       | 1        | 0.17%   |
| en_SG       | 1        | 0.17%   |
| C           | 1        | 0.17%   |
| bg_BG       | 1        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 346      | 57.28%  |
| EFI  | 258      | 42.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 563      | 93.68%  |
| Zfs      | 14       | 2.33%   |
| Overlay  | 11       | 1.83%   |
| Btrfs    | 7        | 1.16%   |
| Xfs      | 2        | 0.33%   |
| Ext3     | 2        | 0.33%   |
| Reiserfs | 1        | 0.17%   |
| Ext2     | 1        | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 556      | 92.21%  |
| GPT     | 38       | 6.3%    |
| MBR     | 9        | 1.49%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 581      | 96.51%  |
| Yes       | 21       | 3.49%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 530      | 88.04%  |
| Yes       | 72       | 11.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 160      | 26.62%  |
| Gigabyte Technology | 101      | 16.81%  |
| Dell                | 64       | 10.65%  |
| MSI                 | 61       | 10.15%  |
| ASRock              | 52       | 8.65%   |
| Hewlett-Packard     | 47       | 7.82%   |
| Lenovo              | 26       | 4.33%   |
| Intel               | 19       | 3.16%   |
| Biostar             | 10       | 1.66%   |
| Foxconn             | 9        | 1.5%    |
| Acer                | 8        | 1.33%   |
| Fujitsu             | 7        | 1.16%   |
| Pegatron            | 6        | 1%      |
| Unknown             | 4        | 0.67%   |
| Shuttle             | 2        | 0.33%   |
| Positivo            | 2        | 0.33%   |
| Medion              | 2        | 0.33%   |
| Google              | 2        | 0.33%   |
| ECS                 | 2        | 0.33%   |
| BESSTAR Tech        | 2        | 0.33%   |
| Apple               | 2        | 0.33%   |
| Alienware           | 2        | 0.33%   |
| Wortmann AG         | 1        | 0.17%   |
| TYAN Computer       | 1        | 0.17%   |
| Sapphire            | 1        | 0.17%   |
| NCR                 | 1        | 0.17%   |
| LattePanda          | 1        | 0.17%   |
| IBM                 | 1        | 0.17%   |
| Huanan              | 1        | 0.17%   |
| Gateway             | 1        | 0.17%   |
| EVGA                | 1        | 0.17%   |
| eMachines           | 1        | 0.17%   |
| AOpen               | 1        | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 17       | 2.83%   |
| Dell OptiPlex 7010               | 7        | 1.16%   |
| Dell OptiPlex 990                | 5        | 0.83%   |
| Dell OptiPlex 790                | 5        | 0.83%   |
| ASUS M5A78L-M/USB3               | 5        | 0.83%   |
| Unknown                          | 5        | 0.83%   |
| MSI MS-7C02                      | 4        | 0.67%   |
| MSI MS-7817                      | 4        | 0.67%   |
| Intel X79M-S                     | 3        | 0.5%    |
| HP Compaq 6200 Pro SFF PC        | 3        | 0.5%    |
| Gigabyte X570 AORUS ELITE        | 3        | 0.5%    |
| Gigabyte B450 AORUS M            | 3        | 0.5%    |
| Gigabyte A320M-S2H               | 3        | 0.5%    |
| Dell Precision WorkStation T3500 | 3        | 0.5%    |
| Dell Inspiron 3847               | 3        | 0.5%    |
| ASUS TUF Gaming X570-PLUS        | 3        | 0.5%    |
| ASUS P8Z77-V LX                  | 3        | 0.5%    |
| ASUS M5A97 R2.0                  | 3        | 0.5%    |
| ASRock B450M Pro4                | 3        | 0.5%    |
| ASRock B450 Pro4                 | 3        | 0.5%    |
| MSI MS-7D19                      | 2        | 0.33%   |
| MSI MS-7C37                      | 2        | 0.33%   |
| MSI MS-7B89                      | 2        | 0.33%   |
| MSI MS-7B85                      | 2        | 0.33%   |
| MSI MS-7693                      | 2        | 0.33%   |
| Intel H61                        | 2        | 0.33%   |
| Intel DQ77MK-R01                 | 2        | 0.33%   |
| HP Z230 SFF Workstation          | 2        | 0.33%   |
| HP ProOne 400 G1 AiO             | 2        | 0.33%   |
| HP ProDesk 600 G1 SFF            | 2        | 0.33%   |
| HP EliteDesk 800 G1 USDT         | 2        | 0.33%   |
| HP Compaq Pro 6300 SFF           | 2        | 0.33%   |
| Gigabyte Z77-D3H                 | 2        | 0.33%   |
| Gigabyte X570 AORUS MASTER       | 2        | 0.33%   |
| Gigabyte H410M H V3              | 2        | 0.33%   |
| Gigabyte GA-78LMT-USB3 6.0       | 2        | 0.33%   |
| Gigabyte GA-78LMT-USB3           | 2        | 0.33%   |
| Gigabyte G31M-ES2L               | 2        | 0.33%   |
| Gigabyte B75M-D3H                | 2        | 0.33%   |
| Gigabyte B560M AORUS ELITE       | 2        | 0.33%   |
| Gigabyte B450 AORUS PRO WIFI     | 2        | 0.33%   |
| Gigabyte 970A-DS3P               | 2        | 0.33%   |
| Dell XPS420                      | 2        | 0.33%   |
| Dell Vostro 260                  | 2        | 0.33%   |
| Dell Vostro 200                  | 2        | 0.33%   |
| Dell Precision T1600             | 2        | 0.33%   |
| Dell OptiPlex 780                | 2        | 0.33%   |
| Dell OptiPlex 755                | 2        | 0.33%   |
| Dell OptiPlex 7040               | 2        | 0.33%   |
| Dell OptiPlex 380                | 2        | 0.33%   |
| Dell OptiPlex 3050               | 2        | 0.33%   |
| Dell OptiPlex 3020               | 2        | 0.33%   |
| Dell OptiPlex 3010               | 2        | 0.33%   |
| Biostar A320MH                   | 2        | 0.33%   |
| ASUS UNLOCK INSTALL              | 2        | 0.33%   |
| ASUS ROG STRIX B450-F GAMING     | 2        | 0.33%   |
| ASUS ROG Maximus XIII HERO       | 2        | 0.33%   |
| ASUS PRIME X570-PRO              | 2        | 0.33%   |
| ASUS PRIME X570-P                | 2        | 0.33%   |
| ASUS PRIME X370-PRO              | 2        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 37       | 6.16%   |
| ASUS PRIME             | 23       | 3.83%   |
| ASUS ROG               | 19       | 3.16%   |
| ASUS All               | 17       | 2.83%   |
| Lenovo ThinkCentre     | 14       | 2.33%   |
| ASUS TUF               | 13       | 2.16%   |
| HP Compaq              | 12       | 2%      |
| HP EliteDesk           | 8        | 1.33%   |
| Gigabyte B450          | 8        | 1.33%   |
| ASUS M5A78L-M          | 8        | 1.33%   |
| Gigabyte X570          | 7        | 1.16%   |
| Acer Aspire            | 7        | 1.16%   |
| Dell Precision         | 6        | 1%      |
| Dell Inspiron          | 6        | 1%      |
| ASUS M5A97             | 6        | 1%      |
| Gigabyte GA-78LMT-USB3 | 5        | 0.83%   |
| Fujitsu ESPRIMO        | 5        | 0.83%   |
| Dell Vostro            | 5        | 0.83%   |
| ASUS P8H61-M           | 5        | 0.83%   |
| ASRock B450M           | 5        | 0.83%   |
| ASRock B450            | 5        | 0.83%   |
| Unknown                | 5        | 0.83%   |
| MSI MS-7C02            | 4        | 0.67%   |
| MSI MS-7817            | 4        | 0.67%   |
| Lenovo IdeaCentre      | 4        | 0.67%   |
| ASUS P8Z77-V           | 4        | 0.67%   |
| Intel X79M-S           | 3        | 0.5%    |
| HP ProDesk             | 3        | 0.5%    |
| Gigabyte G1.Sniper     | 3        | 0.5%    |
| Gigabyte B450M         | 3        | 0.5%    |
| Gigabyte A320M-S2H     | 3        | 0.5%    |
| Dell XPS               | 3        | 0.5%    |
| Dell Studio            | 3        | 0.5%    |
| ASUS P5KPL-AM          | 3        | 0.5%    |
| ASUS P5GC-MX           | 3        | 0.5%    |
| ASUS P5G41T-M          | 3        | 0.5%    |
| ASUS Maximus           | 3        | 0.5%    |
| MSI MS-7D19            | 2        | 0.33%   |
| MSI MS-7C37            | 2        | 0.33%   |
| MSI MS-7B89            | 2        | 0.33%   |
| MSI MS-7B85            | 2        | 0.33%   |
| MSI MS-7693            | 2        | 0.33%   |
| Lenovo ThinkStation    | 2        | 0.33%   |
| Lenovo Legion          | 2        | 0.33%   |
| Intel H61              | 2        | 0.33%   |
| Intel DQ77MK-R01       | 2        | 0.33%   |
| HP Z230                | 2        | 0.33%   |
| HP Z220                | 2        | 0.33%   |
| HP t620                | 2        | 0.33%   |
| HP ProOne              | 2        | 0.33%   |
| HP 290                 | 2        | 0.33%   |
| Gigabyte Z77-D3H       | 2        | 0.33%   |
| Gigabyte H410M         | 2        | 0.33%   |
| Gigabyte G31M-ES2L     | 2        | 0.33%   |
| Gigabyte B75M-D3H      | 2        | 0.33%   |
| Gigabyte B560M         | 2        | 0.33%   |
| Gigabyte B550M         | 2        | 0.33%   |
| Gigabyte B550          | 2        | 0.33%   |
| Gigabyte 970A-DS3P     | 2        | 0.33%   |
| Foxconn Pro            | 2        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 63       | 10.48%  |
| 2013    | 62       | 10.32%  |
| 2012    | 62       | 10.32%  |
| 2011    | 54       | 8.99%   |
| 2014    | 50       | 8.32%   |
| 2019    | 43       | 7.15%   |
| 2020    | 37       | 6.16%   |
| 2021    | 34       | 5.66%   |
| 2010    | 34       | 5.66%   |
| 2017    | 31       | 5.16%   |
| 2008    | 31       | 5.16%   |
| 2009    | 29       | 4.83%   |
| 2016    | 23       | 3.83%   |
| 2007    | 18       | 3%      |
| 2015    | 17       | 2.83%   |
| 2006    | 6        | 1%      |
| 2022    | 3        | 0.5%    |
| 2005    | 3        | 0.5%    |
| Unknown | 1        | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 601      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 570      | 94.53%  |
| Enabled  | 33       | 5.47%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 599      | 99.67%  |
| Yes  | 2        | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 155      | 25.54%  |
| 8.01-16.0   | 143      | 23.56%  |
| 4.01-8.0    | 87       | 14.33%  |
| 32.01-64.0  | 85       | 14%     |
| 3.01-4.0    | 85       | 14%     |
| 64.01-256.0 | 19       | 3.13%   |
| 1.01-2.0    | 15       | 2.47%   |
| 24.01-32.0  | 11       | 1.81%   |
| 2.01-3.0    | 7        | 1.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 267      | 41.98%  |
| 2.01-3.0   | 195      | 30.66%  |
| 3.01-4.0   | 80       | 12.58%  |
| 4.01-8.0   | 75       | 11.79%  |
| 8.01-16.0  | 12       | 1.89%   |
| 0.51-1.0   | 5        | 0.79%   |
| 16.01-24.0 | 2        | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 251      | 40.88%  |
| 2      | 179      | 29.15%  |
| 3      | 83       | 13.52%  |
| 4      | 38       | 6.19%   |
| 5      | 25       | 4.07%   |
| 6      | 19       | 3.09%   |
| 7      | 7        | 1.14%   |
| 0      | 6        | 0.98%   |
| 8      | 5        | 0.81%   |
| 11     | 1        | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 317      | 52.57%  |
| No        | 286      | 47.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 593      | 98.67%  |
| No        | 8        | 1.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 307      | 51%     |
| Yes       | 295      | 49%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 413      | 67.93%  |
| Yes       | 195      | 32.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Desktops | Percent |
|---------------------|----------|---------|
| USA                 | 159      | 26.41%  |
| Germany             | 67       | 11.13%  |
| UK                  | 44       | 7.31%   |
| Brazil              | 43       | 7.14%   |
| Canada              | 22       | 3.65%   |
| Netherlands         | 20       | 3.32%   |
| Poland              | 19       | 3.16%   |
| Italy               | 18       | 2.99%   |
| Spain               | 17       | 2.82%   |
| Australia           | 13       | 2.16%   |
| France              | 12       | 1.99%   |
| India               | 10       | 1.66%   |
| Russia              | 9        | 1.5%    |
| Hungary             | 9        | 1.5%    |
| Mexico              | 8        | 1.33%   |
| Sweden              | 7        | 1.16%   |
| Denmark             | 7        | 1.16%   |
| Argentina           | 7        | 1.16%   |
| Switzerland         | 6        | 1%      |
| Norway              | 6        | 1%      |
| Turkey              | 5        | 0.83%   |
| South Africa        | 5        | 0.83%   |
| Slovenia            | 4        | 0.66%   |
| Serbia              | 4        | 0.66%   |
| Portugal            | 4        | 0.66%   |
| Greece              | 4        | 0.66%   |
| Egypt               | 4        | 0.66%   |
| Czechia             | 4        | 0.66%   |
| Croatia             | 4        | 0.66%   |
| Belgium             | 4        | 0.66%   |
| Ukraine             | 3        | 0.5%    |
| Romania             | 3        | 0.5%    |
| Malaysia            | 3        | 0.5%    |
| Japan               | 3        | 0.5%    |
| Chile               | 3        | 0.5%    |
| Austria             | 3        | 0.5%    |
| Taiwan              | 2        | 0.33%   |
| Slovakia            | 2        | 0.33%   |
| New Zealand         | 2        | 0.33%   |
| Indonesia           | 2        | 0.33%   |
| El Salvador         | 2        | 0.33%   |
| Ecuador             | 2        | 0.33%   |
| China               | 2        | 0.33%   |
| Bangladesh          | 2        | 0.33%   |
| Vietnam             | 1        | 0.17%   |
| Venezuela           | 1        | 0.17%   |
| Trinidad and Tobago | 1        | 0.17%   |
| Thailand            | 1        | 0.17%   |
| Puerto Rico         | 1        | 0.17%   |
| Peru                | 1        | 0.17%   |
| Panama              | 1        | 0.17%   |
| Palestine           | 1        | 0.17%   |
| Nicaragua           | 1        | 0.17%   |
| Mozambique          | 1        | 0.17%   |
| Malta               | 1        | 0.17%   |
| Lithuania           | 1        | 0.17%   |
| Lebanon             | 1        | 0.17%   |
| Latvia              | 1        | 0.17%   |
| Jamaica             | 1        | 0.17%   |
| Israel              | 1        | 0.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Berlin          | 6        | 0.99%   |
| Sao Paulo       | 4        | 0.66%   |
| Munich          | 4        | 0.66%   |
| Dallas          | 4        | 0.66%   |
| Athens          | 4        | 0.66%   |
| Vienna          | 3        | 0.49%   |
| Sydney          | 3        | 0.49%   |
| Rio de Janeiro  | 3        | 0.49%   |
| Richmond        | 3        | 0.49%   |
| Portland        | 3        | 0.49%   |
| Milan           | 3        | 0.49%   |
| Mentor          | 3        | 0.49%   |
| Laval           | 3        | 0.49%   |
| Houston         | 3        | 0.49%   |
| Hamburg         | 3        | 0.49%   |
| Fortaleza       | 3        | 0.49%   |
| Dayton          | 3        | 0.49%   |
| Cape Town       | 3        | 0.49%   |
| Buenos Aires    | 3        | 0.49%   |
| Brasília       | 3        | 0.49%   |
| Almería        | 3        | 0.49%   |
| Zurich          | 2        | 0.33%   |
| Zagreb          | 2        | 0.33%   |
| Wylie           | 2        | 0.33%   |
| Warsaw          | 2        | 0.33%   |
| Victoria        | 2        | 0.33%   |
| Vadodara        | 2        | 0.33%   |
| Twickenham      | 2        | 0.33%   |
| The Hague       | 2        | 0.33%   |
| Stuttgart       | 2        | 0.33%   |
| Stoke-on-Trent  | 2        | 0.33%   |
| Santo André    | 2        | 0.33%   |
| Salt Lake City  | 2        | 0.33%   |
| Rotterdam       | 2        | 0.33%   |
| Roosendaal      | 2        | 0.33%   |
| Rome            | 2        | 0.33%   |
| Queens          | 2        | 0.33%   |
| Prague          | 2        | 0.33%   |
| Poznan          | 2        | 0.33%   |
| Porto Velho     | 2        | 0.33%   |
| Plano           | 2        | 0.33%   |
| Petaling Jaya   | 2        | 0.33%   |
| Oslo            | 2        | 0.33%   |
| Neath           | 2        | 0.33%   |
| Mount Olive     | 2        | 0.33%   |
| Milwaukee       | 2        | 0.33%   |
| Melbourne       | 2        | 0.33%   |
| Los Angeles     | 2        | 0.33%   |
| Lomas de Zamora | 2        | 0.33%   |
| Livingston      | 2        | 0.33%   |
| Lilienthal      | 2        | 0.33%   |
| Kyiv            | 2        | 0.33%   |
| Kiel            | 2        | 0.33%   |
| Jakarta         | 2        | 0.33%   |
| Istanbul        | 2        | 0.33%   |
| Helensburgh     | 2        | 0.33%   |
| Gillingham      | 2        | 0.33%   |
| Drummondville   | 2        | 0.33%   |
| Denver          | 2        | 0.33%   |
| Copenhagen      | 2        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 226      | 346    | 20.93%  |
| WDC                       | 178      | 253    | 16.48%  |
| Samsung Electronics       | 145      | 230    | 13.43%  |
| Kingston                  | 74       | 96     | 6.85%   |
| SanDisk                   | 59       | 70     | 5.46%   |
| Toshiba                   | 58       | 69     | 5.37%   |
| Hitachi                   | 55       | 68     | 5.09%   |
| Crucial                   | 39       | 49     | 3.61%   |
| Phison                    | 17       | 19     | 1.57%   |
| Silicon Motion            | 16       | 23     | 1.48%   |
| A-DATA Technology         | 16       | 20     | 1.48%   |
| Unknown                   | 12       | 25     | 1.11%   |
| China                     | 12       | 13     | 1.11%   |
| Intel                     | 10       | 12     | 0.93%   |
| HGST                      | 10       | 13     | 0.93%   |
| OCZ                       | 8        | 9      | 0.74%   |
| Hewlett-Packard           | 7        | 11     | 0.65%   |
| Gigabyte Technology       | 7        | 9      | 0.65%   |
| SK hynix                  | 6        | 10     | 0.56%   |
| PNY                       | 6        | 8      | 0.56%   |
| Micron Technology         | 6        | 6      | 0.56%   |
| Maxtor                    | 6        | 7      | 0.56%   |
| Lexar                     | 6        | 6      | 0.56%   |
| XPG                       | 5        | 5      | 0.46%   |
| Realtek Semiconductor     | 5        | 5      | 0.46%   |
| JMicron Technology        | 5        | 6      | 0.46%   |
| Super Talent              | 4        | 5      | 0.37%   |
| SPCC                      | 4        | 5      | 0.37%   |
| SABRENT                   | 4        | 4      | 0.37%   |
| Micron/Crucial Technology | 4        | 4      | 0.37%   |
| Intenso                   | 4        | 4      | 0.37%   |
| Goodram                   | 4        | 4      | 0.37%   |
| Netac                     | 3        | 3      | 0.28%   |
| KingSpec                  | 3        | 4      | 0.28%   |
| Corsair                   | 3        | 3      | 0.28%   |
| Apple                     | 3        | 3      | 0.28%   |
| Apacer                    | 3        | 3      | 0.28%   |
| XrayDisk                  | 2        | 3      | 0.19%   |
| Transcend                 | 2        | 2      | 0.19%   |
| Team                      | 2        | 3      | 0.19%   |
| Plextor                   | 2        | 3      | 0.19%   |
| Pioneer                   | 2        | 2      | 0.19%   |
| Patriot                   | 2        | 4      | 0.19%   |
| Leven                     | 2        | 2      | 0.19%   |
| KIOXIA-EXCERIA            | 2        | 5      | 0.19%   |
| KingFast                  | 2        | 2      | 0.19%   |
| HS-SSD-C100               | 2        | 2      | 0.19%   |
| Dogfish                   | 2        | 3      | 0.19%   |
| Unknown                   | 2        | 2      | 0.19%   |
| WD MediaMax               | 1        | 3      | 0.09%   |
| WALRAM                    | 1        | 1      | 0.09%   |
| Verbatim                  | 1        | 1      | 0.09%   |
| USB3.2                    | 1        | 1      | 0.09%   |
| USB3.0                    | 1        | 2      | 0.09%   |
| TwinMOS                   | 1        | 1      | 0.09%   |
| Teclast                   | 1        | 1      | 0.09%   |
| SuperSSpeed               | 1        | 2      | 0.09%   |
| Smartbuy                  | 1        | 1      | 0.09%   |
| OWC                       | 1        | 1      | 0.09%   |
| ORTIAL                    | 1        | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB        | 25       | 1.97%   |
| Kingston SA400S37240G 240GB SSD        | 19       | 1.49%   |
| Samsung SSD 860 EVO 500GB              | 15       | 1.18%   |
| WDC WD10EZEX-08WN4A0 1TB               | 14       | 1.1%    |
| Seagate ST1000DM010-2EP102 1TB         | 14       | 1.1%    |
| Samsung NVMe SSD Drive 1TB             | 14       | 1.1%    |
| Samsung SSD 850 EVO 250GB              | 13       | 1.02%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 13       | 1.02%   |
| Seagate ST1000DM003-1CH162 1TB         | 11       | 0.86%   |
| Seagate ST3500418AS 500GB              | 10       | 0.79%   |
| Seagate ST3500413AS 500GB              | 10       | 0.79%   |
| Toshiba HDWD110 1TB                    | 9        | 0.71%   |
| Seagate ST3500312CS 500GB              | 9        | 0.71%   |
| Samsung HD103SJ 1TB                    | 9        | 0.71%   |
| Kingston SV300S37A120G 120GB SSD       | 9        | 0.71%   |
| Kingston SA400S37120G 120GB SSD        | 9        | 0.71%   |
| Crucial CT240BX500SSD1 240GB           | 9        | 0.71%   |
| Toshiba DT01ACA100 1TB                 | 7        | 0.55%   |
| Toshiba DT01ACA050 500GB               | 7        | 0.55%   |
| Seagate ST2000DM008-2FR102 2TB         | 7        | 0.55%   |
| SanDisk SSD PLUS 240GB                 | 7        | 0.55%   |
| SanDisk NVMe SSD Drive 1TB             | 7        | 0.55%   |
| Samsung SSD 850 EVO 500GB              | 7        | 0.55%   |
| Samsung SSD 840 EVO 250GB              | 7        | 0.55%   |
| Crucial CT500MX500SSD1 500GB           | 7        | 0.55%   |
| WDC WD10EZEX-00WN4A0 1TB               | 6        | 0.47%   |
| Seagate ST4000DM004-2CV104 4TB         | 6        | 0.47%   |
| Seagate ST4000DM000-1F2168 4TB         | 6        | 0.47%   |
| Seagate ST2000DM001-1CH164 2TB         | 6        | 0.47%   |
| Seagate ST1000DM003-1SB102 1TB         | 6        | 0.47%   |
| Seagate ST1000DM003-1ER162 1TB         | 6        | 0.47%   |
| SanDisk NVMe SSD Drive 500GB           | 6        | 0.47%   |
| Samsung SSD 870 EVO 1TB                | 6        | 0.47%   |
| Samsung SSD 840 EVO 120GB              | 6        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB            | 6        | 0.47%   |
| Unknown SD/MMC/MS PRO 128GB            | 5        | 0.39%   |
| Seagate ST2000DM001-9YN164 2TB         | 5        | 0.39%   |
| Seagate Expansion+ Desk 4TB            | 5        | 0.39%   |
| Seagate Expansion 1TB                  | 5        | 0.39%   |
| Samsung SSD 870 QVO 1TB                | 5        | 0.39%   |
| Samsung SSD 860 EVO 250GB              | 5        | 0.39%   |
| Samsung HD103UJ 1TB                    | 5        | 0.39%   |
| Phison NVMe SSD Drive 512GB            | 5        | 0.39%   |
| Phison NVMe SSD Drive 1TB              | 5        | 0.39%   |
| Kingston SA400S37480G 480GB SSD        | 5        | 0.39%   |
| Kingston NVMe SSD Drive 500GB          | 5        | 0.39%   |
| Hitachi HUA723020ALA641 2TB            | 5        | 0.39%   |
| Crucial CT480BX500SSD1 480GB           | 5        | 0.39%   |
| WDC WDBNCE5000PNC 500GB SSD            | 4        | 0.31%   |
| WDC WD1600AAJS-75M0A0 160GB            | 4        | 0.31%   |
| WDC WD10EARS-00Y5B1 1TB                | 4        | 0.31%   |
| Toshiba DT01ACA200 2TB                 | 4        | 0.31%   |
| Silicon Motion NVMe SSD Drive 512GB    | 4        | 0.31%   |
| Silicon Motion NVMe SSD Drive 128GB    | 4        | 0.31%   |
| Silicon Motion NVMe SSD Drive 1024GB   | 4        | 0.31%   |
| Seagate ST9500420AS 500GB              | 4        | 0.31%   |
| Seagate ST8000DM004-2CX188 8TB         | 4        | 0.31%   |
| Seagate ST3320820AS 320GB              | 4        | 0.31%   |
| Seagate ST3250318AS 250GB              | 4        | 0.31%   |
| Seagate ST31000524AS 1TB               | 4        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 224      | 335    | 40.51%  |
| WDC                 | 168      | 231    | 30.38%  |
| Hitachi             | 55       | 68     | 9.95%   |
| Toshiba             | 49       | 60     | 8.86%   |
| Samsung Electronics | 28       | 38     | 5.06%   |
| HGST                | 10       | 13     | 1.81%   |
| Maxtor              | 6        | 7      | 1.08%   |
| Unknown             | 5        | 7      | 0.9%    |
| Hewlett-Packard     | 3        | 6      | 0.54%   |
| JMicron Technology  | 2        | 2      | 0.36%   |
| Apple               | 2        | 2      | 0.36%   |
| USB3.0              | 1        | 2      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 88       | 125    | 22.62%  |
| Kingston            | 60       | 78     | 15.42%  |
| SanDisk             | 43       | 52     | 11.05%  |
| Crucial             | 38       | 48     | 9.77%   |
| WDC                 | 17       | 20     | 4.37%   |
| A-DATA Technology   | 15       | 19     | 3.86%   |
| China               | 12       | 13     | 3.08%   |
| OCZ                 | 8        | 9      | 2.06%   |
| Intel               | 7        | 8      | 1.8%    |
| PNY                 | 6        | 8      | 1.54%   |
| Lexar               | 6        | 6      | 1.54%   |
| Gigabyte Technology | 6        | 7      | 1.54%   |
| Toshiba             | 5        | 5      | 1.29%   |
| Micron Technology   | 5        | 5      | 1.29%   |
| Super Talent        | 4        | 5      | 1.03%   |
| SPCC                | 4        | 5      | 1.03%   |
| Intenso             | 4        | 4      | 1.03%   |
| Hewlett-Packard     | 4        | 5      | 1.03%   |
| Goodram             | 4        | 4      | 1.03%   |
| SK hynix            | 3        | 3      | 0.77%   |
| Seagate             | 3        | 4      | 0.77%   |
| Netac               | 3        | 3      | 0.77%   |
| KingSpec            | 3        | 4      | 0.77%   |
| Apacer              | 3        | 3      | 0.77%   |
| Transcend           | 2        | 2      | 0.51%   |
| Team                | 2        | 3      | 0.51%   |
| Plextor             | 2        | 3      | 0.51%   |
| Pioneer             | 2        | 2      | 0.51%   |
| Patriot             | 2        | 4      | 0.51%   |
| Leven               | 2        | 2      | 0.51%   |
| KIOXIA-EXCERIA      | 2        | 5      | 0.51%   |
| Dogfish             | 2        | 3      | 0.51%   |
| Corsair             | 2        | 2      | 0.51%   |
| Verbatim            | 1        | 1      | 0.26%   |
| TwinMOS             | 1        | 1      | 0.26%   |
| Teclast             | 1        | 1      | 0.26%   |
| SuperSSpeed         | 1        | 2      | 0.26%   |
| Smartbuy            | 1        | 1      | 0.26%   |
| Phison              | 1        | 1      | 0.26%   |
| OWC                 | 1        | 1      | 0.26%   |
| ORTIAL              | 1        | 1      | 0.26%   |
| OCZ-VERTEX          | 1        | 1      | 0.26%   |
| MyDigitalSSD        | 1        | 1      | 0.26%   |
| Mushkin             | 1        | 1      | 0.26%   |
| LITEON              | 1        | 1      | 0.26%   |
| INNOVATION IT       | 1        | 1      | 0.26%   |
| GALAX               | 1        | 1      | 0.26%   |
| FORESEE             | 1        | 1      | 0.26%   |
| Drevo               | 1        | 1      | 0.26%   |
| Apple               | 1        | 1      | 0.26%   |
| AFOX                | 1        | 1      | 0.26%   |
| Acer                | 1        | 1      | 0.26%   |
| Unknown             | 1        | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 416      | 771    | 46.38%  |
| SSD     | 323      | 490    | 36.01%  |
| NVMe    | 131      | 186    | 14.6%   |
| Unknown | 25       | 40     | 2.79%   |
| MMC     | 2        | 3      | 0.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 561      | 1232   | 75.81%  |
| NVMe | 129      | 182    | 17.43%  |
| SAS  | 48       | 73     | 6.49%   |
| MMC  | 2        | 3      | 0.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 430      | 700    | 53.55%  |
| 0.51-1.0   | 220      | 336    | 27.4%   |
| 1.01-2.0   | 83       | 120    | 10.34%  |
| 3.01-4.0   | 34       | 52     | 4.23%   |
| 4.01-10.0  | 20       | 29     | 2.49%   |
| 2.01-3.0   | 16       | 24     | 1.99%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 172      | 27.83%  |
| 251-500        | 141      | 22.82%  |
| 501-1000       | 97       | 15.7%   |
| 1001-2000      | 53       | 8.58%   |
| More than 3000 | 52       | 8.41%   |
| 51-100         | 42       | 6.8%    |
| 2001-3000      | 23       | 3.72%   |
| 1-20           | 15       | 2.43%   |
| 21-50          | 14       | 2.27%   |
| Unknown        | 9        | 1.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 226      | 35.2%   |
| 21-50          | 162      | 25.23%  |
| 51-100         | 76       | 11.84%  |
| 101-250        | 46       | 7.17%   |
| 251-500        | 35       | 5.45%   |
| More than 3000 | 29       | 4.52%   |
| 501-1000       | 29       | 4.52%   |
| 1001-2000      | 24       | 3.74%   |
| Unknown        | 9        | 1.4%    |
| 2001-3000      | 6        | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| WDC WD3200AAKS-22B3A0 320GB          | 1        | 1      | 5.56%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 1      | 5.56%   |
| WDC WD10EZEX-21M2NA0 1TB             | 1        | 2      | 5.56%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1        | 1      | 5.56%   |
| Toshiba MK3265GSX 320GB              | 1        | 1      | 5.56%   |
| Toshiba MG03ACA200 2TB               | 1        | 1      | 5.56%   |
| Silicon Motion Inland NVMe SSD 256GB | 1        | 1      | 5.56%   |
| Seagate ST9500420AS 500GB            | 1        | 1      | 5.56%   |
| Seagate ST4000DM004-2CV104 4TB       | 1        | 1      | 5.56%   |
| Seagate ST3500514NS 500GB            | 1        | 1      | 5.56%   |
| Seagate ST3500413AS 500GB            | 1        | 1      | 5.56%   |
| Seagate ST3320620AS 320GB            | 1        | 1      | 5.56%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1        | 1      | 5.56%   |
| Seagate ST2000DM001-9YN164 2TB       | 1        | 1      | 5.56%   |
| Seagate ST2000DL003-9VT166 2TB       | 1        | 1      | 5.56%   |
| OCZ VERTEX3 120GB SSD                | 1        | 1      | 5.56%   |
| Kingston SNS4151S316GD 16GB SSD      | 1        | 1      | 5.56%   |
| A-DATA Technology SX8200PNP 256GB    | 1        | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 7        | 8      | 41.18%  |
| WDC               | 4        | 5      | 23.53%  |
| Toshiba           | 2        | 2      | 11.76%  |
| Silicon Motion    | 1        | 1      | 5.88%   |
| OCZ               | 1        | 1      | 5.88%   |
| Kingston          | 1        | 1      | 5.88%   |
| A-DATA Technology | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 7        | 8      | 53.85%  |
| WDC     | 4        | 5      | 30.77%  |
| Toshiba | 2        | 2      | 15.38%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 15     | 75%     |
| NVMe | 2        | 2      | 12.5%   |
| SSD  | 2        | 2      | 12.5%   |

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
| Detected | 555      | 1354   | 89.23%  |
| Works    | 51       | 117    | 8.2%    |
| Malfunc  | 16       | 19     | 2.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 398      | 49.5%   |
| AMD                          | 190      | 23.63%  |
| Samsung Electronics          | 46       | 5.72%   |
| ASMedia Technology           | 25       | 3.11%   |
| Phison Electronics           | 18       | 2.24%   |
| JMicron Technology           | 18       | 2.24%   |
| SanDisk                      | 17       | 2.11%   |
| Silicon Motion               | 16       | 1.99%   |
| Kingston Technology Company  | 16       | 1.99%   |
| Nvidia                       | 12       | 1.49%   |
| Marvell Technology Group     | 12       | 1.49%   |
| Silicon Image                | 5        | 0.62%   |
| Realtek Semiconductor        | 5        | 0.62%   |
| Micron/Crucial Technology    | 5        | 0.62%   |
| ADATA Technology             | 5        | 0.62%   |
| VIA Technologies             | 4        | 0.5%    |
| Toshiba America Info Systems | 3        | 0.37%   |
| SK hynix                     | 3        | 0.37%   |
| Seagate Technology           | 2        | 0.25%   |
| Broadcom / LSI               | 2        | 0.25%   |
| Micron Technology            | 1        | 0.12%   |
| KIOXIA                       | 1        | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 102      | 9.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 59       | 5.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 42       | 4.09%   |
| AMD 400 Series Chipset SATA Controller                                                  | 41       | 4%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 38       | 3.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 35       | 3.41%   |
| Intel SATA Controller [RAID mode]                                                       | 31       | 3.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 30       | 2.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 30       | 2.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 27       | 2.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 25       | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 25       | 2.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 23       | 2.24%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 23       | 2.24%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 20       | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 20       | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 19       | 1.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 17       | 1.66%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 16       | 1.56%   |
| AMD 500 Series Chipset SATA Controller                                                  | 14       | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 13       | 1.27%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 12       | 1.17%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 12       | 1.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 11       | 1.07%   |
| Phison E12 NVMe Controller                                                              | 9        | 0.88%   |
| Kingston Company A2000 NVMe SSD                                                         | 9        | 0.88%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 9        | 0.88%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 9        | 0.88%   |
| AMD FCH SATA Controller D                                                               | 9        | 0.88%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 0.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8        | 0.78%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7        | 0.68%   |
| AMD X370 Series Chipset SATA Controller                                                 | 7        | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6        | 0.58%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 0.58%   |
| JMicron JMB368 IDE controller                                                           | 6        | 0.58%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 6        | 0.58%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 6        | 0.58%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 6        | 0.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6        | 0.58%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6        | 0.58%   |
| AMD FCH IDE Controller                                                                  | 6        | 0.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5        | 0.49%   |
| Samsung NVMe SSD Controller 980                                                         | 5        | 0.49%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 0.49%   |
| Nvidia MCP61 IDE                                                                        | 5        | 0.49%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 0.49%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 0.49%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 4        | 0.39%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 4        | 0.39%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 0.39%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 4        | 0.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 0.39%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 4        | 0.39%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 0.39%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 3        | 0.29%   |
| Silicon Motion Non-Volatile memory controller                                           | 3        | 0.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.29%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 0.29%   |
| SanDisk Non-Volatile memory controller                                                  | 3        | 0.29%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 469      | 57.55%  |
| IDE  | 166      | 20.37%  |
| NVMe | 128      | 15.71%  |
| RAID | 48       | 5.89%   |
| SAS  | 2        | 0.25%   |
| SCSI | 2        | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 401      | 66.72%  |
| AMD    | 200      | 33.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 16       | 2.66%   |
| AMD Ryzen 5 3600 6-Core Processor           | 14       | 2.33%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 11       | 1.83%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 10       | 1.66%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 9        | 1.5%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 9        | 1.5%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 8        | 1.33%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8        | 1.33%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 7        | 1.16%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 7        | 1.16%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 7        | 1.16%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 6        | 1%      |
| Intel Core i5-4460 CPU @ 3.20GHz            | 6        | 1%      |
| Intel Core i3-4160 CPU @ 3.60GHz            | 6        | 1%      |
| AMD Ryzen 9 5900X 12-Core Processor         | 6        | 1%      |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5        | 0.83%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 5        | 0.83%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 0.83%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 5        | 0.83%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 5        | 0.83%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 5        | 0.83%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 5        | 0.83%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 5        | 0.83%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 5        | 0.83%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 0.83%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 0.83%   |
| AMD FX-8350 Eight-Core Processor            | 5        | 0.83%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 4        | 0.67%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 4        | 0.67%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 4        | 0.67%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 0.67%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 4        | 0.67%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 0.67%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 0.67%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 4        | 0.67%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 4        | 0.67%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 0.67%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 0.67%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 0.67%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 0.67%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 0.67%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 0.67%   |
| AMD FX-6300 Six-Core Processor              | 4        | 0.67%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 3        | 0.5%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 3        | 0.5%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3        | 0.5%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 0.5%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.5%    |
| Intel Core i7 CPU 870 @ 2.93GHz             | 3        | 0.5%    |
| Intel Core i5-9600K CPU @ 3.70GHz           | 3        | 0.5%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.5%    |
| Intel Core i5-10400F CPU @ 2.90GHz          | 3        | 0.5%    |
| Intel Core i3 CPU 540 @ 3.07GHz             | 3        | 0.5%    |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 3        | 0.5%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 0.5%    |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 0.5%    |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 0.5%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 0.5%    |
| AMD Phenom II X6 1090T Processor            | 3        | 0.5%    |
| AMD Phenom II X4 965 Processor              | 3        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 124      | 20.63%  |
| Intel Core i7           | 66       | 10.98%  |
| Intel Core i3           | 63       | 10.48%  |
| AMD Ryzen 5             | 49       | 8.15%   |
| Intel Xeon              | 30       | 4.99%   |
| AMD FX                  | 29       | 4.83%   |
| AMD Ryzen 7             | 24       | 3.99%   |
| Intel Core 2 Quad       | 17       | 2.83%   |
| Intel Celeron           | 17       | 2.83%   |
| Intel Core 2 Duo        | 16       | 2.66%   |
| Other                   | 14       | 2.33%   |
| AMD Ryzen 9             | 14       | 2.33%   |
| Intel Pentium Dual-Core | 13       | 2.16%   |
| Intel Pentium Dual      | 11       | 1.83%   |
| Intel Pentium           | 10       | 1.66%   |
| AMD Ryzen 3             | 10       | 1.66%   |
| AMD Phenom II X4        | 7        | 1.16%   |
| AMD Athlon II X2        | 7        | 1.16%   |
| AMD A10                 | 7        | 1.16%   |
| AMD Athlon II X4        | 6        | 1%      |
| AMD A8                  | 6        | 1%      |
| AMD A6                  | 6        | 1%      |
| Intel Core i9           | 5        | 0.83%   |
| AMD Phenom II X6        | 5        | 0.83%   |
| AMD Athlon 64 X2        | 5        | 0.83%   |
| Intel Pentium Gold      | 3        | 0.5%    |
| Intel Pentium 4         | 3        | 0.5%    |
| Intel Core 2            | 3        | 0.5%    |
| Intel Atom              | 3        | 0.5%    |
| AMD E1                  | 3        | 0.5%    |
| AMD Athlon II X3        | 3        | 0.5%    |
| AMD Athlon              | 3        | 0.5%    |
| Intel Pentium D         | 2        | 0.33%   |
| AMD PRO A10             | 2        | 0.33%   |
| AMD GX                  | 2        | 0.33%   |
| AMD Athlon X4           | 2        | 0.33%   |
| AMD Athlon 64           | 2        | 0.33%   |
| Intel Core m3           | 1        | 0.17%   |
| Intel Celeron D         | 1        | 0.17%   |
| AMD Sempron             | 1        | 0.17%   |
| AMD Ryzen Threadripper  | 1        | 0.17%   |
| AMD Ryzen 5 PRO         | 1        | 0.17%   |
| AMD Phenom              | 1        | 0.17%   |
| AMD Opteron             | 1        | 0.17%   |
| AMD Athlon Dual Core    | 1        | 0.17%   |
| AMD A4                  | 1        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 254      | 42.26%  |
| 2      | 172      | 28.62%  |
| 6      | 84       | 13.98%  |
| 8      | 44       | 7.32%   |
| 1      | 13       | 2.16%   |
| 3      | 12       | 2%      |
| 12     | 11       | 1.83%   |
| 16     | 6        | 1%      |
| 10     | 5        | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 597      | 99.33%  |
| 2      | 4        | 0.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 307      | 51.08%  |
| 1      | 294      | 48.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 601      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 69       | 11.39%  |
| 0x306a9    | 52       | 8.58%   |
| 0x206a7    | 48       | 7.92%   |
| Unknown    | 48       | 7.92%   |
| 0x1067a    | 39       | 6.44%   |
| 0x08701021 | 28       | 4.62%   |
| 0x506e3    | 24       | 3.96%   |
| 0x06000852 | 21       | 3.47%   |
| 0x906ea    | 14       | 2.31%   |
| 0x0800820d | 14       | 2.31%   |
| 0xa0653    | 12       | 1.98%   |
| 0x0a201016 | 12       | 1.98%   |
| 0x06001119 | 12       | 1.98%   |
| 0x906e9    | 11       | 1.82%   |
| 0x6fd      | 10       | 1.65%   |
| 0xa0655    | 9        | 1.49%   |
| 0x6fb      | 9        | 1.49%   |
| 0x906ed    | 8        | 1.32%   |
| 0x906eb    | 8        | 1.32%   |
| 0x0600063e | 8        | 1.32%   |
| 0xa0671    | 7        | 1.16%   |
| 0x010000dc | 7        | 1.16%   |
| 0x010000c8 | 7        | 1.16%   |
| 0x08701013 | 6        | 0.99%   |
| 0x010000db | 6        | 0.99%   |
| 0x106a5    | 5        | 0.83%   |
| 0x08101016 | 5        | 0.83%   |
| 0x08001137 | 5        | 0.83%   |
| 0x0700010f | 5        | 0.83%   |
| 0x90672    | 4        | 0.66%   |
| 0x10676    | 4        | 0.66%   |
| 0x08108109 | 4        | 0.66%   |
| 0x06003106 | 4        | 0.66%   |
| 0x406c4    | 3        | 0.5%    |
| 0x306e4    | 3        | 0.5%    |
| 0x30678    | 3        | 0.5%    |
| 0x206d7    | 3        | 0.5%    |
| 0x20655    | 3        | 0.5%    |
| 0x20652    | 3        | 0.5%    |
| 0x106e5    | 3        | 0.5%    |
| 0x0a50000c | 3        | 0.5%    |
| 0x0a201009 | 3        | 0.5%    |
| 0x08001138 | 3        | 0.5%    |
| 0x010000c7 | 3        | 0.5%    |
| 0xf47      | 2        | 0.33%   |
| 0x6f6      | 2        | 0.33%   |
| 0x40651    | 2        | 0.33%   |
| 0x206c2    | 2        | 0.33%   |
| 0x106a4    | 2        | 0.33%   |
| 0x10677    | 2        | 0.33%   |
| 0x0a50000b | 2        | 0.33%   |
| 0x0810100b | 2        | 0.33%   |
| 0x07030106 | 2        | 0.33%   |
| 0x06006705 | 2        | 0.33%   |
| 0xf65      | 1        | 0.17%   |
| 0xf4a      | 1        | 0.17%   |
| 0xf49      | 1        | 0.17%   |
| 0xf43      | 1        | 0.17%   |
| 0x906ec    | 1        | 0.17%   |
| 0x806e9    | 1        | 0.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 77       | 12.81%  |
| IvyBridge        | 55       | 9.15%   |
| SandyBridge      | 54       | 8.99%   |
| Penryn           | 46       | 7.65%   |
| KabyLake         | 46       | 7.65%   |
| Zen 2            | 37       | 6.16%   |
| Piledriver       | 34       | 5.66%   |
| K10              | 29       | 4.83%   |
| Zen 3            | 25       | 4.16%   |
| Skylake          | 25       | 4.16%   |
| Core             | 24       | 3.99%   |
| CometLake        | 22       | 3.66%   |
| Zen+             | 20       | 3.33%   |
| Zen              | 18       | 3%      |
| Nehalem          | 12       | 2%      |
| K8 Hammer        | 9        | 1.5%    |
| Westmere         | 8        | 1.33%   |
| Bulldozer        | 8        | 1.33%   |
| Silvermont       | 7        | 1.16%   |
| Icelake          | 7        | 1.16%   |
| NetBurst         | 6        | 1%      |
| Jaguar           | 6        | 1%      |
| Excavator        | 5        | 0.83%   |
| Steamroller      | 4        | 0.67%   |
| Puma             | 4        | 0.67%   |
| Alderlake Hybrid | 3        | 0.5%    |
| Broadwell        | 2        | 0.33%   |
| Bonnell          | 2        | 0.33%   |
| Unknown          | 2        | 0.33%   |
| TigerLake        | 1        | 0.17%   |
| K10 Llano        | 1        | 0.17%   |
| Goldmont plus    | 1        | 0.17%   |
| Goldmont         | 1        | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 256      | 39.88%  |
| Intel            | 201      | 31.31%  |
| AMD              | 184      | 28.66%  |
| VIA Technologies | 1        | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 35       | 5.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30       | 4.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 21       | 3.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 19       | 2.93%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 18       | 2.77%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 14       | 2.16%   |
| Intel HD Graphics 530                                                                    | 12       | 1.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12       | 1.85%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 11       | 1.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 10       | 1.54%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 10       | 1.54%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 10       | 1.54%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 10       | 1.54%   |
| Intel HD Graphics 630                                                                    | 9        | 1.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 9        | 1.39%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8        | 1.23%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 8        | 1.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8        | 1.23%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 7        | 1.08%   |
| AMD RS780L [Radeon 3000]                                                                 | 7        | 1.08%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 6        | 0.92%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 6        | 0.92%   |
| Nvidia GT218 [GeForce 210]                                                               | 6        | 0.92%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6        | 0.92%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 6        | 0.92%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 6        | 0.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 6        | 0.92%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6        | 0.92%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 6        | 0.92%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 5        | 0.77%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 5        | 0.77%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5        | 0.77%   |
| AMD RS880 [Radeon HD 4200]                                                               | 5        | 0.77%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 5        | 0.77%   |
| AMD Cezanne                                                                              | 5        | 0.77%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 4        | 0.62%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 4        | 0.62%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 4        | 0.62%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 4        | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 0.62%   |
| Intel AlderLake-S GT1                                                                    | 4        | 0.62%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 4        | 0.62%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4        | 0.62%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 4        | 0.62%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 3        | 0.46%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3        | 0.46%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 3        | 0.46%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 3        | 0.46%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 3        | 0.46%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 0.46%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3        | 0.46%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 3        | 0.46%   |
| Nvidia GK107GL [Quadro K600]                                                             | 3        | 0.46%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 3        | 0.46%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                        | 3        | 0.46%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3        | 0.46%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 3        | 0.46%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 3        | 0.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3        | 0.46%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 3        | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 244      | 40.26%  |
| 1 x Intel      | 172      | 28.38%  |
| 1 x AMD        | 170      | 28.05%  |
| Intel + AMD    | 6        | 0.99%   |
| Intel + Nvidia | 5        | 0.83%   |
| 2 x AMD        | 4        | 0.66%   |
| AMD + Nvidia   | 3        | 0.5%    |
| 2 x Nvidia     | 1        | 0.17%   |
| 1 x VIA        | 1        | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 400      | 66.33%  |
| Proprietary | 170      | 28.19%  |
| Unknown     | 33       | 5.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 244      | 40.13%  |
| 0.51-1.0   | 88       | 14.47%  |
| 1.01-2.0   | 81       | 13.32%  |
| 0.01-0.5   | 58       | 9.54%   |
| 3.01-4.0   | 51       | 8.39%   |
| 7.01-8.0   | 43       | 7.07%   |
| 5.01-6.0   | 17       | 2.8%    |
| 8.01-16.0  | 16       | 2.63%   |
| 2.01-3.0   | 6        | 0.99%   |
| 16.01-24.0 | 4        | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 97       | 16.19%  |
| Dell                 | 57       | 9.52%   |
| Goldstar             | 52       | 8.68%   |
| Hewlett-Packard      | 50       | 8.35%   |
| Acer                 | 38       | 6.34%   |
| AOC                  | 34       | 5.68%   |
| Philips              | 33       | 5.51%   |
| BenQ                 | 25       | 4.17%   |
| Ancor Communications | 24       | 4.01%   |
| LG Electronics       | 19       | 3.17%   |
| Unknown              | 12       | 2%      |
| ViewSonic            | 11       | 1.84%   |
| Iiyama               | 10       | 1.67%   |
| Lenovo               | 8        | 1.34%   |
| Sony                 | 7        | 1.17%   |
| Sceptre Tech         | 7        | 1.17%   |
| NEC Computers        | 7        | 1.17%   |
| HPN                  | 7        | 1.17%   |
| ASUSTek Computer     | 7        | 1.17%   |
| Unknown              | 6        | 1%      |
| Vizio                | 5        | 0.83%   |
| Panasonic            | 4        | 0.67%   |
| Microstep            | 4        | 0.67%   |
| Medion               | 4        | 0.67%   |
| Fujitsu Siemens      | 4        | 0.67%   |
| AUS                  | 4        | 0.67%   |
| Vestel               | 3        | 0.5%    |
| Sharp                | 3        | 0.5%    |
| Toshiba              | 2        | 0.33%   |
| PKB                  | 2        | 0.33%   |
| OEM                  | 2        | 0.33%   |
| Lenovo Group Limited | 2        | 0.33%   |
| HannStar             | 2        | 0.33%   |
| Gigabyte Technology  | 2        | 0.33%   |
| GDH                  | 2        | 0.33%   |
| FUS                  | 2        | 0.33%   |
| Eizo                 | 2        | 0.33%   |
| ZZZ                  | 1        | 0.17%   |
| Xiaomi               | 1        | 0.17%   |
| Westinghouse         | 1        | 0.17%   |
| WAN                  | 1        | 0.17%   |
| VOR                  | 1        | 0.17%   |
| VIZ                  | 1        | 0.17%   |
| Viotek               | 1        | 0.17%   |
| Vestel Elektronik    | 1        | 0.17%   |
| Unknown (AAA)        | 1        | 0.17%   |
| STD                  | 1        | 0.17%   |
| SKY                  | 1        | 0.17%   |
| Seiki                | 1        | 0.17%   |
| Sceptre              | 1        | 0.17%   |
| SANYO                | 1        | 0.17%   |
| PRI                  | 1        | 0.17%   |
| Pixio                | 1        | 0.17%   |
| Packard Bell         | 1        | 0.17%   |
| OOO                  | 1        | 0.17%   |
| ONN                  | 1        | 0.17%   |
| MSI                  | 1        | 0.17%   |
| Mitsubishi           | 1        | 0.17%   |
| MiTAC                | 1        | 0.17%   |
| MEB                  | 1        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown                                                                | 12       | 1.91%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 4        | 0.64%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 4        | 0.64%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                              | 3        | 0.48%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch      | 3        | 0.48%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                    | 3        | 0.48%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                       | 3        | 0.48%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch  | 3        | 0.48%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch              | 2        | 0.32%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch   | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SAM0F9F 3840x2160 1210x680mm 54.6-inch | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 1210x680mm 54.6-inch | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 700x390mm 31.5-inch   | 2        | 0.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2        | 0.32%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 2        | 0.32%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2        | 0.32%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 2        | 0.32%   |
| Philips LCD Monitor FTV 1920x1080                                      | 2        | 0.32%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                        | 2        | 0.32%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                       | 2        | 0.32%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 2        | 0.32%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch            | 2        | 0.32%   |
| Hewlett-Packard LCD Monitor w1907 3120x1050                            | 2        | 0.32%   |
| Hewlett-Packard 24fh HPN3546 1920x1080 527x296mm 23.8-inch             | 2        | 0.32%   |
| Goldstar M2280D GSM57B9 1920x1080 480x270mm 21.7-inch                  | 2        | 0.32%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch              | 2        | 0.32%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                   | 2        | 0.32%   |
| GDH PHILCO GDH0030 1920x540 708x398mm 32.0-inch                        | 2        | 0.32%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                     | 2        | 0.32%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                      | 2        | 0.32%   |
| Dell P190S DEL405B 1280x1024 376x301mm 19.0-inch                       | 2        | 0.32%   |
| Dell LCD Monitor E228WFP                                               | 2        | 0.32%   |
| Dell E2213 DELD04E 1680x1050 473x296mm 22.0-inch                       | 2        | 0.32%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 2        | 0.32%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                     | 2        | 0.32%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                      | 2        | 0.32%   |
| Ancor Communications LCD Monitor VE247 3840x1080                       | 2        | 0.32%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                       | 2        | 0.32%   |
| ZZZ HDMI ZZZE435 1600x900 442x240mm 19.8-inch                          | 1        | 0.16%   |
| Xiaomi Mi TV XMD00E2 1920x1080 708x398mm 32.0-inch                     | 1        | 0.16%   |
| Westinghouse SK-26H735S WDE6030 1366x768 576x324mm 26.0-inch           | 1        | 0.16%   |
| WAN 27MQ95FSHDRU WAN2700 2560x1440 600x330mm 27.0-inch                 | 1        | 0.16%   |
| VOR LED19204 VOR1950 1366x768 410x220mm 18.3-inch                      | 1        | 0.16%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                     | 1        | 0.16%   |
| Vizio E40-D0 VIZ2001 1920x1080 885x498mm 40.0-inch                     | 1        | 0.16%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                    | 1        | 0.16%   |
| VIZ LCD Monitor 320AR 1360x768                                         | 1        | 0.16%   |
| Viotek GNV27DB VTK2700 2560x1440 597x336mm 27.0-inch                   | 1        | 0.16%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1        | 0.16%   |
| ViewSonic VX3258 series VSCA037 1920x1080 700x390mm 31.5-inch          | 1        | 0.16%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                 | 1        | 0.16%   |
| ViewSonic VX2370 SERIES VSC342C 1920x1080 509x286mm 23.0-inch          | 1        | 0.16%   |
| ViewSonic VG510s VSCCA18 1024x768 304x228mm 15.0-inch                  | 1        | 0.16%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch          | 1        | 0.16%   |
| ViewSonic Q9-2 Series VSCC01D 1280x1024 380x300mm 19.1-inch            | 1        | 0.16%   |
| ViewSonic LCD Monitor VSC7731 1920x1080 480x270mm 21.7-inch            | 1        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 252      | 42.64%  |
| 3840x2160 (4K)     | 52       | 8.8%    |
| 1680x1050 (WSXGA+) | 34       | 5.75%   |
| Unknown            | 34       | 5.75%   |
| 1280x1024 (SXGA)   | 33       | 5.58%   |
| 1600x900 (HD+)     | 29       | 4.91%   |
| 1366x768 (WXGA)    | 25       | 4.23%   |
| 2560x1440 (QHD)    | 20       | 3.38%   |
| 1440x900 (WXGA+)   | 18       | 3.05%   |
| 1360x768           | 15       | 2.54%   |
| 3840x1080          | 14       | 2.37%   |
| 1920x1200 (WUXGA)  | 13       | 2.2%    |
| 3440x1440          | 10       | 1.69%   |
| 2560x1080          | 6        | 1.02%   |
| 1920x540           | 4        | 0.68%   |
| 4480x1440          | 3        | 0.51%   |
| 1024x768 (XGA)     | 3        | 0.51%   |
| 5760x2160          | 2        | 0.34%   |
| 3360x1080          | 2        | 0.34%   |
| 3200x1200          | 2        | 0.34%   |
| 3120x1050          | 2        | 0.34%   |
| 2560x1600          | 2        | 0.34%   |
| 1600x1200          | 2        | 0.34%   |
| 6400x1440          | 1        | 0.17%   |
| 5440x1080          | 1        | 0.17%   |
| 4160x1440          | 1        | 0.17%   |
| 3840x1600          | 1        | 0.17%   |
| 3780x2160          | 1        | 0.17%   |
| 3600x1080          | 1        | 0.17%   |
| 3360x1050          | 1        | 0.17%   |
| 3040x1050          | 1        | 0.17%   |
| 2944x1080          | 1        | 0.17%   |
| 2720x1024          | 1        | 0.17%   |
| 2464x900           | 1        | 0.17%   |
| 1850x1030          | 1        | 0.17%   |
| 1834x1031          | 1        | 0.17%   |
| 1280x720 (HD)      | 1        | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 131      | 22.47%  |
| 24      | 62       | 10.63%  |
| 27      | 55       | 9.43%   |
| 23      | 48       | 8.23%   |
| 21      | 48       | 8.23%   |
| 19      | 39       | 6.69%   |
| 31      | 30       | 5.15%   |
| 20      | 27       | 4.63%   |
| 18      | 25       | 4.29%   |
| 22      | 24       | 4.12%   |
| 17      | 15       | 2.57%   |
| 84      | 10       | 1.72%   |
| 34      | 10       | 1.72%   |
| 40      | 7        | 1.2%    |
| 32      | 7        | 1.2%    |
| 54      | 6        | 1.03%   |
| 26      | 6        | 1.03%   |
| 25      | 5        | 0.86%   |
| 15      | 4        | 0.69%   |
| 72      | 3        | 0.51%   |
| 52      | 3        | 0.51%   |
| 48      | 2        | 0.34%   |
| 41      | 2        | 0.34%   |
| 35      | 2        | 0.34%   |
| 33      | 2        | 0.34%   |
| 28      | 2        | 0.34%   |
| 75      | 1        | 0.17%   |
| 74      | 1        | 0.17%   |
| 65      | 1        | 0.17%   |
| 43      | 1        | 0.17%   |
| 42      | 1        | 0.17%   |
| 37      | 1        | 0.17%   |
| 36      | 1        | 0.17%   |
| 29      | 1        | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 155      | 27.39%  |
| 401-500     | 142      | 25.09%  |
| Unknown     | 131      | 23.14%  |
| 601-700     | 41       | 7.24%   |
| 701-800     | 20       | 3.53%   |
| 351-400     | 19       | 3.36%   |
| 301-350     | 17       | 3%      |
| 1501-2000   | 15       | 2.65%   |
| 1001-1500   | 12       | 2.12%   |
| 801-900     | 10       | 1.77%   |
| 901-1000    | 4        | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 306      | 55.84%  |
| Unknown | 126      | 22.99%  |
| 16/10   | 64       | 11.68%  |
| 5/4     | 28       | 5.11%   |
| 21/9    | 14       | 2.55%   |
| 4/3     | 6        | 1.09%   |
| 6/5     | 2        | 0.36%   |
| 32/9    | 1        | 0.18%   |
| 3/2     | 1        | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 148      | 25.65%  |
| Unknown        | 131      | 22.7%   |
| 151-200        | 84       | 14.56%  |
| 301-350        | 56       | 9.71%   |
| 351-500        | 53       | 9.19%   |
| 141-150        | 33       | 5.72%   |
| More than 1000 | 26       | 4.51%   |
| 251-300        | 26       | 4.51%   |
| 501-1000       | 14       | 2.43%   |
| 101-110        | 4        | 0.69%   |
| 131-140        | 1        | 0.17%   |
| 121-130        | 1        | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 299      | 54.46%  |
| Unknown | 131      | 23.86%  |
| 101-120 | 71       | 12.93%  |
| 1-50    | 24       | 4.37%   |
| 121-160 | 17       | 3.1%    |
| 161-240 | 7        | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 487      | 80.63%  |
| 2     | 78       | 12.91%  |
| 0     | 33       | 5.46%   |
| 3     | 6        | 0.99%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 372      | 42.08%  |
| Intel                                 | 234      | 26.47%  |
| Qualcomm Atheros                      | 63       | 7.13%   |
| Broadcom                              | 32       | 3.62%   |
| Ralink Technology                     | 30       | 3.39%   |
| TP-Link                               | 23       | 2.6%    |
| Ralink                                | 18       | 2.04%   |
| Nvidia                                | 11       | 1.24%   |
| NetGear                               | 10       | 1.13%   |
| MediaTek                              | 8        | 0.9%    |
| Microsoft                             | 6        | 0.68%   |
| D-Link                                | 6        | 0.68%   |
| Samsung Electronics                   | 5        | 0.57%   |
| Qualcomm Atheros Communications       | 5        | 0.57%   |
| D-Link System                         | 5        | 0.57%   |
| Xiaomi                                | 4        | 0.45%   |
| Marvell Technology Group              | 4        | 0.45%   |
| Huawei Technologies                   | 4        | 0.45%   |
| Edimax Technology                     | 4        | 0.45%   |
| Broadcom Limited                      | 4        | 0.45%   |
| ASIX Electronics                      | 4        | 0.45%   |
| Motorola PCS                          | 3        | 0.34%   |
| DisplayLink                           | 3        | 0.34%   |
| Gemtek                                | 2        | 0.23%   |
| ASUSTek Computer                      | 2        | 0.23%   |
| Aquantia                              | 2        | 0.23%   |
| ZyDAS                                 | 1        | 0.11%   |
| TRENDnet                              | 1        | 0.11%   |
| T & A Mobile Phones                   | 1        | 0.11%   |
| Sundance Technology Inc / IC Plus     | 1        | 0.11%   |
| Research In Motion                    | 1        | 0.11%   |
| QinHeng Electronics                   | 1        | 0.11%   |
| Panasonic (Matsushita)                | 1        | 0.11%   |
| Padix (Rockfire)                      | 1        | 0.11%   |
| OPPO Electronics                      | 1        | 0.11%   |
| Motorola                              | 1        | 0.11%   |
| Linksys                               | 1        | 0.11%   |
| Lenovo                                | 1        | 0.11%   |
| JMicron Technology                    | 1        | 0.11%   |
| Google                                | 1        | 0.11%   |
| Exar                                  | 1        | 0.11%   |
| Belkin Components                     | 1        | 0.11%   |
| AVM                                   | 1        | 0.11%   |
| Arduino SA                            | 1        | 0.11%   |
| ADMtek                                | 1        | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 295      | 29.47%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38       | 3.8%    |
| Intel I211 Gigabit Network Connection                             | 30       | 3%      |
| Realtek RTL8125 2.5GbE Controller                                 | 25       | 2.5%    |
| Intel Wi-Fi 6 AX200                                               | 25       | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20       | 2%      |
| Intel Ethernet Connection (2) I219-V                              | 19       | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 18       | 1.8%    |
| Ralink MT7601U Wireless Adapter                                   | 15       | 1.5%    |
| Realtek 802.11ac NIC                                              | 13       | 1.3%    |
| Intel Ethernet Controller I225-V                                  | 13       | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 10       | 1%      |
| Intel Wireless-AC 9260                                            | 9        | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 9        | 0.9%    |
| Intel Ethernet Connection I217-V                                  | 9        | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 9        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 9        | 0.9%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 8        | 0.8%    |
| Intel Wireless 7265                                               | 8        | 0.8%    |
| Intel 82579V Gigabit Network Connection                           | 8        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7        | 0.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 7        | 0.7%    |
| Intel Ethernet Connection (2) I218-V                              | 7        | 0.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 7        | 0.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 6        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 0.6%    |
| Ralink RT5370 Wireless Adapter                                    | 6        | 0.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6        | 0.6%    |
| Nvidia MCP61 Ethernet                                             | 6        | 0.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 5        | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 5        | 0.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5        | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                   | 5        | 0.5%    |
| NetGear A6210                                                     | 5        | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 5        | 0.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 4        | 0.4%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 4        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 0.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4        | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 4        | 0.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4        | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4        | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 0.4%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 4        | 0.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4        | 0.4%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 4        | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.4%    |
| Intel Ethernet Connection (14) I219-V                             | 4        | 0.4%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4        | 0.4%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 0.4%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 4        | 0.4%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 3        | 0.3%    |
| TP-Link 802.11ac WLAN Adapter                                     | 3        | 0.3%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3        | 0.3%    |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter           | 3        | 0.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.3%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 3        | 0.3%    |
| Ralink RT2561/RT61 802.11g PCI                                    | 3        | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 85       | 25.53%  |
| Realtek Semiconductor                 | 75       | 22.52%  |
| Ralink Technology                     | 30       | 9.01%   |
| Qualcomm Atheros                      | 30       | 9.01%   |
| TP-Link                               | 22       | 6.61%   |
| Ralink                                | 18       | 5.41%   |
| Broadcom                              | 16       | 4.8%    |
| NetGear                               | 10       | 3%      |
| Microsoft                             | 6        | 1.8%    |
| MediaTek                              | 6        | 1.8%    |
| D-Link                                | 6        | 1.8%    |
| Qualcomm Atheros Communications       | 5        | 1.5%    |
| Edimax Technology                     | 4        | 1.2%    |
| D-Link System                         | 4        | 1.2%    |
| Broadcom Limited                      | 3        | 0.9%    |
| Gemtek                                | 2        | 0.6%    |
| ASUSTek Computer                      | 2        | 0.6%    |
| ZyDAS                                 | 1        | 0.3%    |
| Xiaomi                                | 1        | 0.3%    |
| TRENDnet                              | 1        | 0.3%    |
| Panasonic (Matsushita)                | 1        | 0.3%    |
| Linksys                               | 1        | 0.3%    |
| Belkin Components                     | 1        | 0.3%    |
| AVM                                   | 1        | 0.3%    |
| ADMtek                                | 1        | 0.3%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 25       | 7.42%   |
| Ralink MT7601U Wireless Adapter                                      | 15       | 4.45%   |
| Realtek 802.11ac NIC                                                 | 13       | 3.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 10       | 2.97%   |
| Intel Wireless-AC 9260                                               | 9        | 2.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 9        | 2.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 9        | 2.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 8        | 2.37%   |
| Intel Wireless 7265                                                  | 8        | 2.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 7        | 2.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 7        | 2.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 6        | 1.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 6        | 1.78%   |
| Ralink RT5370 Wireless Adapter                                       | 6        | 1.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 6        | 1.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 5        | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 5        | 1.48%   |
| Qualcomm Atheros AR9271 802.11n                                      | 5        | 1.48%   |
| NetGear A6210                                                        | 5        | 1.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 4        | 1.19%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 4        | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4        | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 4        | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 4        | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 4        | 1.19%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 4        | 1.19%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 4        | 1.19%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 3        | 0.89%   |
| TP-Link 802.11ac WLAN Adapter                                        | 3        | 0.89%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 3        | 0.89%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter              | 3        | 0.89%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                            | 3        | 0.89%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 3        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 3        | 0.89%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 3        | 0.89%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]          | 3        | 0.89%   |
| Microsoft XBOX ACC                                                   | 3        | 0.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 3        | 0.89%   |
| Intel Wireless 8260                                                  | 3        | 0.89%   |
| Intel Wireless 7260                                                  | 3        | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3        | 0.89%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 3        | 0.89%   |
| TP-Link Archer T4U ver.3                                             | 2        | 0.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2        | 0.59%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                      | 2        | 0.59%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 2        | 0.59%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                            | 2        | 0.59%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 2        | 0.59%   |
| Ralink RT2500 Wireless 802.11bg                                      | 2        | 0.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2        | 0.59%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter           | 2        | 0.59%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 2        | 0.59%   |
| MediaTek WiFi                                                        | 2        | 0.59%   |
| Intel Wireless 8265 / 8275                                           | 2        | 0.59%   |
| Intel Wireless 3165                                                  | 2        | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2        | 0.59%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2        | 0.59%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                    | 2        | 0.59%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 2        | 0.59%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]             | 2        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 351      | 55.1%   |
| Intel                             | 188      | 29.51%  |
| Qualcomm Atheros                  | 35       | 5.49%   |
| Broadcom                          | 16       | 2.51%   |
| Nvidia                            | 11       | 1.73%   |
| Samsung Electronics               | 5        | 0.78%   |
| Marvell Technology Group          | 4        | 0.63%   |
| Huawei Technologies               | 4        | 0.63%   |
| ASIX Electronics                  | 4        | 0.63%   |
| Xiaomi                            | 3        | 0.47%   |
| DisplayLink                       | 3        | 0.47%   |
| MediaTek                          | 2        | 0.31%   |
| Aquantia                          | 2        | 0.31%   |
| TP-Link                           | 1        | 0.16%   |
| Sundance Technology Inc / IC Plus | 1        | 0.16%   |
| Research In Motion                | 1        | 0.16%   |
| OPPO Electronics                  | 1        | 0.16%   |
| Motorola PCS                      | 1        | 0.16%   |
| JMicron Technology                | 1        | 0.16%   |
| Google                            | 1        | 0.16%   |
| D-Link System                     | 1        | 0.16%   |
| Broadcom Limited                  | 1        | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 295      | 45.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 38       | 5.8%    |
| Intel I211 Gigabit Network Connection                                      | 30       | 4.58%   |
| Realtek RTL8125 2.5GbE Controller                                          | 25       | 3.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 20       | 3.05%   |
| Intel Ethernet Connection (2) I219-V                                       | 19       | 2.9%    |
| Intel Ethernet Connection I217-LM                                          | 18       | 2.75%   |
| Intel Ethernet Controller I225-V                                           | 13       | 1.98%   |
| Intel Ethernet Connection I217-V                                           | 9        | 1.37%   |
| Intel Ethernet Connection (7) I219-V                                       | 9        | 1.37%   |
| Intel 82579V Gigabit Network Connection                                    | 8        | 1.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 7        | 1.07%   |
| Intel Ethernet Connection (2) I218-V                                       | 7        | 1.07%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 6        | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 6        | 0.92%   |
| Nvidia MCP61 Ethernet                                                      | 6        | 0.92%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 5        | 0.76%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 5        | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 4        | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 4        | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 4        | 0.61%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 4        | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 4        | 0.61%   |
| Intel Ethernet Connection (14) I219-V                                      | 4        | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4        | 0.61%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3        | 0.46%   |
| Nvidia MCP51 Ethernet Controller                                           | 3        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                                      | 3        | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                                      | 3        | 0.46%   |
| Intel Ethernet Connection (12) I219-V                                      | 3        | 0.46%   |
| Intel 82574L Gigabit Network Connection                                    | 3        | 0.46%   |
| Intel 82566DC-2 Gigabit Network Connection                                 | 3        | 0.46%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                     | 3        | 0.46%   |
| Huawei COL-L29                                                             | 3        | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 2        | 0.31%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 2        | 0.31%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 2        | 0.31%   |
| Nvidia MCP73 Ethernet                                                      | 2        | 0.31%   |
| MediaTek TECNO SPARK 3                                                     | 2        | 0.31%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 0.31%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 0.31%   |
| Intel Ethernet Connection (5) I219-LM                                      | 2        | 0.31%   |
| Intel 82578DC Gigabit Network Connection                                   | 2        | 0.31%   |
| Intel 82562V-2 10/100 Network Connection                                   | 2        | 0.31%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                            | 2        | 0.31%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 2        | 0.31%   |
| ASIX AX88772                                                               | 2        | 0.31%   |
| ASIX AX88179 Gigabit Ethernet                                              | 2        | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.15%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]            | 1        | 0.15%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.15%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.15%   |
| Research In Motion BlackBerry                                              | 1        | 0.15%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.15%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 1        | 0.15%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.15%   |
| OPPO Find X2 Lite                                                          | 1        | 0.15%   |
| Motorola PCS moto g stylus                                                 | 1        | 0.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 593      | 66.04%  |
| WiFi     | 296      | 32.96%  |
| Modem    | 5        | 0.56%   |
| Unknown  | 4        | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 443      | 70.65%  |
| WiFi     | 182      | 29.03%  |
| Modem    | 1        | 0.16%   |
| Unknown  | 1        | 0.16%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 390      | 64.57%  |
| 2     | 182      | 30.13%  |
| 3     | 23       | 3.81%   |
| 0     | 6        | 0.99%   |
| 7     | 1        | 0.17%   |
| 5     | 1        | 0.17%   |
| 4     | 1        | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 417      | 68.59%  |
| Yes  | 191      | 31.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 68       | 34%     |
| Cambridge Silicon Radio         | 47       | 23.5%   |
| Realtek Semiconductor           | 28       | 14%     |
| Broadcom                        | 14       | 7%      |
| Qualcomm Atheros Communications | 10       | 5%      |
| ASUSTek Computer                | 8        | 4%      |
| IMC Networks                    | 5        | 2.5%    |
| Apple                           | 4        | 2%      |
| MediaTek                        | 3        | 1.5%    |
| Dynex                           | 3        | 1.5%    |
| Dell                            | 2        | 1%      |
| TP-Link                         | 1        | 0.5%    |
| National Semiconductor          | 1        | 0.5%    |
| Micro Star International        | 1        | 0.5%    |
| Lite-On Technology              | 1        | 0.5%    |
| Integrated System Solution      | 1        | 0.5%    |
| Foxconn / Hon Hai               | 1        | 0.5%    |
| D-Link System                   | 1        | 0.5%    |
| Belkin Components               | 1        | 0.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 47       | 23.5%   |
| Realtek Bluetooth Radio                               | 26       | 13%     |
| Intel AX200 Bluetooth                                 | 18       | 9%      |
| Intel Bluetooth wireless interface                    | 17       | 8.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 10       | 5%      |
| Intel Wireless-AC 3168 Bluetooth                      | 8        | 4%      |
| Intel AX210 Bluetooth                                 | 8        | 4%      |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 6        | 3%      |
| Qualcomm Atheros AR9462 Bluetooth                     | 3        | 1.5%    |
| Qualcomm Atheros AR3011 Bluetooth                     | 3        | 1.5%    |
| MediaTek Wireless_Device                              | 3        | 1.5%    |
| Intel Bluetooth Device                                | 3        | 1.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 1.5%    |
| IMC Networks Bluetooth Radio                          | 3        | 1.5%    |
| Dynex BCM20702A0                                      | 3        | 1.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 1.5%    |
| Dell BT Mini-Receiver                                 | 2        | 1%      |
| Broadcom HP Portable Bumble Bee                       | 2        | 1%      |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 2        | 1%      |
| ASUS Qualcomm Bluetooth 4.1                           | 2        | 1%      |
| ASUS Bluetooth Radio                                  | 2        | 1%      |
| Apple Bluetooth USB Host Controller                   | 2        | 1%      |
| TP-Link UB500 Adapter                                 | 1        | 0.5%    |
| Realtek RTL8821A Bluetooth                            | 1        | 0.5%    |
| Realtek RTL8723B Bluetooth                            | 1        | 0.5%    |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 0.5%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.5%    |
| Qualcomm Atheros Bluetooth                            | 1        | 0.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1        | 0.5%    |
| National Bluetooth Dongle                             | 1        | 0.5%    |
| Micro Star International Bluetooth Device             | 1        | 0.5%    |
| Lite-On Bluetooth Device                              | 1        | 0.5%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 0.5%    |
| Integrated System Solution Bluetooth Device           | 1        | 0.5%    |
| IMC Networks Bluetooth Module                         | 1        | 0.5%    |
| IMC Networks Bluetooth Device                         | 1        | 0.5%    |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 0.5%    |
| D-Link System DBT-122 Bluetooth                       | 1        | 0.5%    |
| Broadcom HP Bluetooth Module                          | 1        | 0.5%    |
| Broadcom Bluetooth Device                             | 1        | 0.5%    |
| Broadcom Bluetooth 2.0+EDR dongle                     | 1        | 0.5%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 0.5%    |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 0.5%    |
| ASUS BCM20702A0                                       | 1        | 0.5%    |
| Apple Bluetooth Host Controller                       | 1        | 0.5%    |
| Apple Bluetooth HCI                                   | 1        | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 391      | 38.87%  |
| AMD                                  | 260      | 25.84%  |
| Nvidia                               | 239      | 23.76%  |
| C-Media Electronics                  | 26       | 2.58%   |
| Creative Labs                        | 11       | 1.09%   |
| Kingston Technology                  | 8        | 0.8%    |
| JMTek                                | 7        | 0.7%    |
| Logitech                             | 6        | 0.6%    |
| Texas Instruments                    | 5        | 0.5%    |
| VIA Technologies                     | 4        | 0.4%    |
| Razer USA                            | 4        | 0.4%    |
| Plantronics                          | 4        | 0.4%    |
| GN Netcom                            | 3        | 0.3%    |
| ASUSTek Computer                     | 3        | 0.3%    |
| Creative Technology                  | 2        | 0.2%    |
| XMOS                                 | 1        | 0.1%    |
| Valve Software                       | 1        | 0.1%    |
| Thesycon Systemsoftware & Consulting | 1        | 0.1%    |
| Tenx Technology                      | 1        | 0.1%    |
| Swissonic                            | 1        | 0.1%    |
| SteelSeries ApS                      | 1        | 0.1%    |
| Silicon Labs                         | 1        | 0.1%    |
| SAVITECH                             | 1        | 0.1%    |
| ROCCAT                               | 1        | 0.1%    |
| Realtek Semiconductor                | 1        | 0.1%    |
| Qualcomm                             | 1        | 0.1%    |
| Numark                               | 1        | 0.1%    |
| Microsoft                            | 1        | 0.1%    |
| Micronas                             | 1        | 0.1%    |
| Micro Star International             | 1        | 0.1%    |
| Medeli Electronics                   | 1        | 0.1%    |
| LucidSound                           | 1        | 0.1%    |
| Klipsch Audio                        | 1        | 0.1%    |
| Jieli Technology                     | 1        | 0.1%    |
| Insignia (Best Buy)                  | 1        | 0.1%    |
| iCreate Technologies                 | 1        | 0.1%    |
| iConnectivity                        | 1        | 0.1%    |
| Google                               | 1        | 0.1%    |
| GEMBIRD                              | 1        | 0.1%    |
| Focusrite-Novation                   | 1        | 0.1%    |
| FIFINE Microphones                   | 1        | 0.1%    |
| Evolution Electronics                | 1        | 0.1%    |
| Corsair                              | 1        | 0.1%    |
| Blue Microphones                     | 1        | 0.1%    |
| AudioQuest                           | 1        | 0.1%    |
| Audio-Technica                       | 1        | 0.1%    |
| Asahi Kasei Microsystems             | 1        | 0.1%    |
| A4Tech                               | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 68       | 5.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 61       | 5.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 55       | 4.79%   |
| AMD Starship/Matisse HD Audio Controller                                          | 54       | 4.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 42       | 3.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 39       | 3.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 34       | 2.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 31       | 2.7%    |
| AMD FCH Azalia Controller                                                         | 27       | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                        | 25       | 2.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 24       | 2.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 24       | 2.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 21       | 1.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 19       | 1.65%   |
| AMD Family 17h/19h HD Audio Controller                                            | 19       | 1.65%   |
| Intel 200 Series PCH HD Audio                                                     | 18       | 1.57%   |
| Nvidia GF119 HDMI Audio Controller                                                | 17       | 1.48%   |
| Nvidia GF108 High Definition Audio Controller                                     | 15       | 1.31%   |
| Nvidia TU116 High Definition Audio Controller                                     | 14       | 1.22%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 14       | 1.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 14       | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 13       | 1.13%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 13       | 1.13%   |
| AMD Navi 10 HDMI Audio                                                            | 12       | 1.04%   |
| Nvidia TU106 High Definition Audio Controller                                     | 11       | 0.96%   |
| Nvidia High Definition Audio Controller                                           | 11       | 0.96%   |
| Intel Audio device                                                                | 11       | 0.96%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 11       | 0.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 11       | 0.96%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 11       | 0.96%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 11       | 0.96%   |
| Nvidia GP106 High Definition Audio Controller                                     | 10       | 0.87%   |
| Nvidia GK107 HDMI Audio Controller                                                | 10       | 0.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 10       | 0.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 10       | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                                     | 9        | 0.78%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 9        | 0.78%   |
| AMD Kabini HDMI/DP Audio                                                          | 9        | 0.78%   |
| Intel Comet Lake PCH-V cAVS                                                       | 8        | 0.7%    |
| Nvidia GM204 High Definition Audio Controller                                     | 7        | 0.61%   |
| Nvidia GA102 High Definition Audio Controller                                     | 7        | 0.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 7        | 0.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 6        | 0.52%   |
| Nvidia TU104 HD Audio Controller                                                  | 6        | 0.52%   |
| Nvidia MCP61 High Definition Audio                                                | 6        | 0.52%   |
| Nvidia GP108 High Definition Audio Controller                                     | 6        | 0.52%   |
| Nvidia GM206 High Definition Audio Controller                                     | 6        | 0.52%   |
| Nvidia GK104 HDMI Audio Controller                                                | 6        | 0.52%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 6        | 0.52%   |
| AMD Trinity HDMI Audio Controller                                                 | 6        | 0.52%   |
| Nvidia GK106 HDMI Audio Controller                                                | 5        | 0.44%   |
| Nvidia Audio device                                                               | 5        | 0.44%   |
| JMTek USB PnP Audio Device                                                        | 5        | 0.44%   |
| Intel Alder Lake-S HD Audio Controller                                            | 5        | 0.44%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 5        | 0.44%   |
| C-Media Electronics USB Advanced Audio Device                                     | 5        | 0.44%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 5        | 0.44%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 5        | 0.44%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 5        | 0.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 5        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 15       | 17.86%  |
| Kingston            | 12       | 14.29%  |
| G.Skill             | 10       | 11.9%   |
| Corsair             | 10       | 11.9%   |
| Samsung Electronics | 9        | 10.71%  |
| SK hynix            | 6        | 7.14%   |
| Crucial             | 6        | 7.14%   |
| Micron Technology   | 5        | 5.95%   |
| Team                | 3        | 3.57%   |
| Ramaxel Technology  | 2        | 2.38%   |
| Patriot             | 1        | 1.19%   |
| Nanya Technology    | 1        | 1.19%   |
| Goldkey             | 1        | 1.19%   |
| F7852C80            | 1        | 1.19%   |
| Elpida              | 1        | 1.19%   |
| Unknown             | 1        | 1.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                      | 2        | 2.2%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2        | 2.2%    |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s               | 2        | 2.2%    |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s               | 2        | 2.2%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                 | 2        | 2.2%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s               | 2        | 2.2%    |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s           | 1        | 1.1%    |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                         | 1        | 1.1%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 1        | 1.1%    |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s                      | 1        | 1.1%    |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                      | 1        | 1.1%    |
| Unknown RAM Module 4GB DIMM 400MT/s                               | 1        | 1.1%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                              | 1        | 1.1%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1        | 1.1%    |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                      | 1        | 1.1%    |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s                       | 1        | 1.1%    |
| Unknown RAM Module 4096MB DIMM 667MT/s                            | 1        | 1.1%    |
| Unknown RAM Module 2GB DIMM DDR2                                  | 1        | 1.1%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 1        | 1.1%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                      | 1        | 1.1%    |
| Unknown RAM Module 2048MB DIMM DDR2 1333MT/s                      | 1        | 1.1%    |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                          | 1        | 1.1%    |
| Unknown RAM Module 1GB DIMM 400MT/s                               | 1        | 1.1%    |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s                | 1        | 1.1%    |
| Team RAM TEAMGROUP-UD4-3600 32GB DIMM DDR4 3600MT/s               | 1        | 1.1%    |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s               | 1        | 1.1%    |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s                | 1        | 1.1%    |
| SK hynix RAM HMT41GU6AFR8A-PB 8192MB DIMM DDR3 1600MT/s           | 1        | 1.1%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s              | 1        | 1.1%    |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s              | 1        | 1.1%    |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s              | 1        | 1.1%    |
| SK hynix RAM HKNNNFBMAVAR-NEH 2048MB Row Of Chips LPDDR4 3200MT/s | 1        | 1.1%    |
| Samsung RAM Module 8192MB DIMM DDR4 2133MT/s                      | 1        | 1.1%    |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1600MT/s                  | 1        | 1.1%    |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s               | 1        | 1.1%    |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1866MT/s            | 1        | 1.1%    |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s               | 1        | 1.1%    |
| Ramaxel RAM RMUA5110ME78HAF-2666 8GB DIMM DDR4 2667MT/s           | 1        | 1.1%    |
| Ramaxel RAM RMR5030ED58E8W1600 2048MB DIMM DDR3 1600MT/s          | 1        | 1.1%    |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s                | 1        | 1.1%    |
| Nanya RAM Module 4096MB DIMM DDR4 2400MT/s                        | 1        | 1.1%    |
| Micron RAM Module 4096MB FB-DIMM DDR2 800MT/s                     | 1        | 1.1%    |
| Micron RAM 8KTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s            | 1        | 1.1%    |
| Micron RAM 36KSF1G72PZ-1 8192MB DIMM DDR3 1600MT/s                | 1        | 1.1%    |
| Micron RAM 36JSF2G72PZ-1 16384MB DIMM DDR3 1866MT/s               | 1        | 1.1%    |
| Micron RAM 16KTF1G64AZ-1G6P1 8GB DIMM DDR3 1600MT/s               | 1        | 1.1%    |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s               | 1        | 1.1%    |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s               | 1        | 1.1%    |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                 | 1        | 1.1%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s               | 1        | 1.1%    |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s             | 1        | 1.1%    |
| Kingston RAM KF3200C16D4/16GX 16384MB DIMM DDR4 3200MT/s          | 1        | 1.1%    |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s             | 1        | 1.1%    |
| Kingston RAM 99U5471-033.A00LF 4096MB DIMM DDR3                   | 1        | 1.1%    |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s             | 1        | 1.1%    |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s        | 1        | 1.1%    |
| Kingston RAM 99U5403-065.A00LF 4GB DIMM DDR3 1600MT/s             | 1        | 1.1%    |
| Goldkey RAM BKH200UD25608-1333 2GB DIMM DDR3 1400MT/s             | 1        | 1.1%    |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 2933MT/s               | 1        | 1.1%    |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s            | 1        | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 32       | 43.24%  |
| DDR3    | 29       | 39.19%  |
| Unknown | 7        | 9.46%   |
| DDR2    | 4        | 5.41%   |
| LPDDR4  | 1        | 1.35%   |
| DDR     | 1        | 1.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 70       | 94.59%  |
| SODIMM       | 2        | 2.7%    |
| Row Of Chips | 1        | 1.35%   |
| FB-DIMM      | 1        | 1.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 37       | 45.12%  |
| 4096  | 23       | 28.05%  |
| 16384 | 8        | 9.76%   |
| 2048  | 8        | 9.76%   |
| 32768 | 4        | 4.88%   |
| 1024  | 2        | 2.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 18       | 22.22%  |
| 1333    | 10       | 12.35%  |
| 3600    | 8        | 9.88%   |
| 3200    | 8        | 9.88%   |
| 2133    | 5        | 6.17%   |
| 3466    | 4        | 4.94%   |
| 2400    | 4        | 4.94%   |
| 2667    | 3        | 3.7%    |
| 1800    | 3        | 3.7%    |
| 3000    | 2        | 2.47%   |
| 1866    | 2        | 2.47%   |
| 4000    | 1        | 1.23%   |
| 3333    | 1        | 1.23%   |
| 2933    | 1        | 1.23%   |
| 2800    | 1        | 1.23%   |
| 2666    | 1        | 1.23%   |
| 2200    | 1        | 1.23%   |
| 1867    | 1        | 1.23%   |
| 1400    | 1        | 1.23%   |
| 976     | 1        | 1.23%   |
| 800     | 1        | 1.23%   |
| 667     | 1        | 1.23%   |
| 400     | 1        | 1.23%   |
| 333     | 1        | 1.23%   |
| Unknown | 1        | 1.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson         | 5        | 20%     |
| Samsung Electronics | 5        | 20%     |
| Hewlett-Packard     | 5        | 20%     |
| Canon               | 5        | 20%     |
| Brother Industries  | 5        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson L3110 Series             | 2        | 8%      |
| Seiko Epson XP-7100 Series           | 1        | 4%      |
| Seiko Epson XP-202 203 206 Series    | 1        | 4%      |
| Seiko Epson ET-2820 Series           | 1        | 4%      |
| Samsung SCX-483x 5x3x Series         | 1        | 4%      |
| Samsung SCX-4200 series              | 1        | 4%      |
| Samsung SCX-3400 Series              | 1        | 4%      |
| Samsung ML-216x Series Laser Printer | 1        | 4%      |
| Samsung C460 Series                  | 1        | 4%      |
| HP Smart Tank 510 series             | 1        | 4%      |
| HP OfficeJet 4650 series             | 1        | 4%      |
| HP LaserJet Professional P1102w      | 1        | 4%      |
| HP ENVY 4520 series                  | 1        | 4%      |
| HP DeskJet 2700 series               | 1        | 4%      |
| Canon TS3100 series                  | 1        | 4%      |
| Canon TR4500 series                  | 1        | 4%      |
| Canon PIXMA MG2500 Series            | 1        | 4%      |
| Canon LiDE 400                       | 1        | 4%      |
| Canon iP4200                         | 1        | 4%      |
| Brother MFC-J1010DW                  | 1        | 4%      |
| Brother MFC-9140CDN                  | 1        | 4%      |
| Brother HL-3142CW series             | 1        | 4%      |
| Brother HL-2140 series               | 1        | 4%      |
| Brother DCP-L2540DW                  | 1        | 4%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 3        | 75%     |
| Hewlett-Packard | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP ScanJet 2400c        | 1        | 25%     |
| Canon CanoScan LiDE 110 | 1        | 25%     |
| Canon CanoScan LiDE 100 | 1        | 25%     |
| Canon CanoScan 8800F    | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 27       | 28.13%  |
| Microdia                      | 11       | 11.46%  |
| Samsung Electronics           | 6        | 6.25%   |
| Microsoft                     | 6        | 6.25%   |
| Sunplus Innovation Technology | 5        | 5.21%   |
| Generalplus Technology        | 5        | 5.21%   |
| Chicony Electronics           | 4        | 4.17%   |
| ARC International             | 4        | 4.17%   |
| Realtek Semiconductor         | 2        | 2.08%   |
| Razer USA                     | 2        | 2.08%   |
| Jieli Technology              | 2        | 2.08%   |
| Guillemot                     | 2        | 2.08%   |
| Creative Technology           | 2        | 2.08%   |
| Apple                         | 2        | 2.08%   |
| Xiongmai                      | 1        | 1.04%   |
| Unknown                       | 1        | 1.04%   |
| Teslong Camera                | 1        | 1.04%   |
| Suyin                         | 1        | 1.04%   |
| Sunplus Technology            | 1        | 1.04%   |
| Sonix Technology              | 1        | 1.04%   |
| lihappe8                      | 1        | 1.04%   |
| INOGENI                       | 1        | 1.04%   |
| IMC Networks                  | 1        | 1.04%   |
| Hewlett-Packard               | 1        | 1.04%   |
| Genesys Logic                 | 1        | 1.04%   |
| Cubeternet                    | 1        | 1.04%   |
| AVerMedia Technologies        | 1        | 1.04%   |
| Arkmicro Technologies         | 1        | 1.04%   |
| Alcor Micro                   | 1        | 1.04%   |
| 2M UVC CAMERA                 | 1        | 1.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 8        | 8.16%   |
| Samsung Galaxy series, misc. (MTP mode) | 6        | 6.12%   |
| Microsoft LifeCam HD-3000               | 4        | 4.08%   |
| Generalplus GENERAL WEBCAM              | 4        | 4.08%   |
| ARC International Camera                | 4        | 4.08%   |
| Sunplus Full HD webcam                  | 3        | 3.06%   |
| Logitech HD Pro Webcam C920             | 3        | 3.06%   |
| Chicony HP High Definition 1MP Webcam   | 3        | 3.06%   |
| Razer USA Gaming Webcam [Kiyo]          | 2        | 2.04%   |
| Microdia Webcam Vitade AF               | 2        | 2.04%   |
| Microdia USB Live camera                | 2        | 2.04%   |
| Microdia USB 2.0 Camera                 | 2        | 2.04%   |
| Logitech HD Webcam C910                 | 2        | 2.04%   |
| Logitech HD Webcam C615                 | 2        | 2.04%   |
| Logitech C922 Pro Stream Webcam         | 2        | 2.04%   |
| Logitech C920 PRO HD Webcam             | 2        | 2.04%   |
| Jieli USB PHY 2.0                       | 2        | 2.04%   |
| Apple iPhone 5/5C/5S/6/SE               | 2        | 2.04%   |
| Xiongmai web camera                     | 1        | 1.02%   |
| Unknown HD camera                       | 1        | 1.02%   |
| Teslong Camera Teslong Camera           | 1        | 1.02%   |
| Suyin HD WebCam                         | 1        | 1.02%   |
| Sunplus General Image Device            | 1        | 1.02%   |
| Sunplus FHD Camera Microphone           | 1        | 1.02%   |
| Sunplus Aukey-PC-LM1E Camera            | 1        | 1.02%   |
| Sonix USB 2.0 Camera                    | 1        | 1.02%   |
| Realtek WEB CAMERA M9 Pro               | 1        | 1.02%   |
| Realtek HP High Definition 1MP Webcam   | 1        | 1.02%   |
| Microsoft MicrosoftÂ LifeCam Cinema    | 1        | 1.02%   |
| Microsoft LifeCam VX-2000               | 1        | 1.02%   |
| Microdia PC Camera (SN9C110)            | 1        | 1.02%   |
| Microdia NEXIGO HD Webcam               | 1        | 1.02%   |
| Microdia Integrated Camera              | 1        | 1.02%   |
| Microdia Camera                         | 1        | 1.02%   |
| Microdia AUKEY PC-W1                    | 1        | 1.02%   |
| Logitech Webcam Pro 9000                | 1        | 1.02%   |
| Logitech Webcam C310                    | 1        | 1.02%   |
| Logitech Webcam C260                    | 1        | 1.02%   |
| Logitech QuickCam Pro for Notebooks     | 1        | 1.02%   |
| Logitech QuickCam Pro 4000              | 1        | 1.02%   |
| Logitech QuickCam E 3500                | 1        | 1.02%   |
| Logitech Portable Webcam C905           | 1        | 1.02%   |
| Logitech HD Webcam C525                 | 1        | 1.02%   |
| Logitech HD Webcam B990                 | 1        | 1.02%   |
| Logitech CrystalCam                     | 1        | 1.02%   |
| lihappe8 USB 2.0 Camera                 | 1        | 1.02%   |
| INOGENI 1C2F-INOGENI 4K2USB3            | 1        | 1.02%   |
| IMC Networks USB2.0 UVC 1.3M WebCam     | 1        | 1.02%   |
| HP Webcam HD 2300                       | 1        | 1.02%   |
| Guillemot Hercules HD Sunset            | 1        | 1.02%   |
| Guillemot Hercules HD Emotion           | 1        | 1.02%   |
| Genesys Logic Camera                    | 1        | 1.02%   |
| Generalplus 808 Camera                  | 1        | 1.02%   |
| Cubeternet GL-UPC822 UVC WebCam         | 1        | 1.02%   |
| Creative Live! Cam Sync HD [VF0770]     | 1        | 1.02%   |
| Creative Live! Cam Chat HD [VF0700]     | 1        | 1.02%   |
| Chicony CNF8050 Webcam                  | 1        | 1.02%   |
| AVerMedia Live Streamer CAM 313         | 1        | 1.02%   |
| Arkmicro USB2.0 PC CAMERA               | 1        | 1.02%   |
| Alcor Micro USB 2.0 PC Camera           | 1        | 1.02%   |

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
| Reiner SCT Kartensysteme | 1        | 25%     |
| Realtek Semiconductor    | 1        | 25%     |
| Alcor Micro              | 1        | 25%     |
| Advanced Card Systems    | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack e-com/pinpad   | 1        | 25%     |
| Realtek Semiconductor Smart Card Reader Interface | 1        | 25%     |
| Alcor Micro AU9540 Smartcard Reader               | 1        | 25%     |
| Advanced Card Systems ACR39U                      | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 504      | 83.31%  |
| 1     | 90       | 14.88%  |
| 2     | 10       | 1.65%   |
| 3     | 1        | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 45       | 41.67%  |
| Graphics card            | 43       | 39.81%  |
| Communication controller | 5        | 4.63%   |
| Multimedia controller    | 3        | 2.78%   |
| Chipcard                 | 3        | 2.78%   |
| Unassigned class         | 2        | 1.85%   |
| Camera                   | 2        | 1.85%   |
| Storage/raid             | 1        | 0.93%   |
| Storage/ide              | 1        | 0.93%   |
| Sound                    | 1        | 0.93%   |
| Modem                    | 1        | 0.93%   |
| Card reader              | 1        | 0.93%   |

