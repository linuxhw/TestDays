ArcoLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ArcoLinux/Desktop/README.md) and [notebooks](/Dist/ArcoLinux/Notebook/README.md).

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

Total: 3059

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [b6b99bf7bd](https://linux-hardware.org/?probe=b6b99bf7bd) | Aug 12, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [3ea3856297](https://linux-hardware.org/?probe=3ea3856297) | Aug 12, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [e65db8d147](https://linux-hardware.org/?probe=e65db8d147) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [72899a615b](https://linux-hardware.org/?probe=72899a615b) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d387c8fec5](https://linux-hardware.org/?probe=d387c8fec5) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [c90f282238](https://linux-hardware.org/?probe=c90f282238) | Aug 11, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [6f323e0954](https://linux-hardware.org/?probe=6f323e0954) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [a9f30f8dd0](https://linux-hardware.org/?probe=a9f30f8dd0) | Aug 11, 2023 |
| HP            | 158A                        | Desktop     | [96e7fa3b8f](https://linux-hardware.org/?probe=96e7fa3b8f) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G513QY            | Notebook    | [eacd0cc54d](https://linux-hardware.org/?probe=eacd0cc54d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [c083cb5f2f](https://linux-hardware.org/?probe=c083cb5f2f) | Aug 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [980f6773f8](https://linux-hardware.org/?probe=980f6773f8) | Aug 10, 2023 |
| Lenovo        | ThinkPad P53s 20N6S00B00    | Notebook    | [c76e31ff8e](https://linux-hardware.org/?probe=c76e31ff8e) | Aug 10, 2023 |
| HP            | Folio 13                    | Notebook    | [67121fc711](https://linux-hardware.org/?probe=67121fc711) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [025afcb20d](https://linux-hardware.org/?probe=025afcb20d) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [6f422f386f](https://linux-hardware.org/?probe=6f422f386f) | Aug 10, 2023 |
| HP            | 829A                        | Mini pc     | [ae08c868cf](https://linux-hardware.org/?probe=ae08c868cf) | Aug 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e703bb179f](https://linux-hardware.org/?probe=e703bb179f) | Aug 10, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [60cfdb5283](https://linux-hardware.org/?probe=60cfdb5283) | Aug 10, 2023 |
| HP            | Folio 13                    | Notebook    | [889aae1772](https://linux-hardware.org/?probe=889aae1772) | Aug 10, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [817c5f9f93](https://linux-hardware.org/?probe=817c5f9f93) | Aug 09, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [12e0dbd72c](https://linux-hardware.org/?probe=12e0dbd72c) | Aug 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0cf2ab49c0](https://linux-hardware.org/?probe=0cf2ab49c0) | Aug 09, 2023 |
| HP            | Compaq 15                   | Notebook    | [387a3b8af2](https://linux-hardware.org/?probe=387a3b8af2) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [e22cd6fdac](https://linux-hardware.org/?probe=e22cd6fdac) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [2242417727](https://linux-hardware.org/?probe=2242417727) | Aug 09, 2023 |
| Lenovo        | ThinkPad X240 20AL00C6UK    | Notebook    | [d33c586eab](https://linux-hardware.org/?probe=d33c586eab) | Aug 09, 2023 |
| Dell          | 073Y7Y A00                  | Desktop     | [cbf4153713](https://linux-hardware.org/?probe=cbf4153713) | Aug 09, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [ccb4eadbca](https://linux-hardware.org/?probe=ccb4eadbca) | Aug 08, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [d79ab70370](https://linux-hardware.org/?probe=d79ab70370) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5babb790d3](https://linux-hardware.org/?probe=5babb790d3) | Aug 08, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [ff4ead4bd3](https://linux-hardware.org/?probe=ff4ead4bd3) | Aug 08, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [e5a8c891d0](https://linux-hardware.org/?probe=e5a8c891d0) | Aug 08, 2023 |
| Toshiba       | Satellite C50-A510          | Notebook    | [335af4e25a](https://linux-hardware.org/?probe=335af4e25a) | Aug 08, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [3ff7f02af7](https://linux-hardware.org/?probe=3ff7f02af7) | Aug 08, 2023 |
| Insyde        | BayTrail                    | Notebook    | [df18553ec6](https://linux-hardware.org/?probe=df18553ec6) | Aug 07, 2023 |
| HP            | 8876 11                     | Desktop     | [059d4c2db2](https://linux-hardware.org/?probe=059d4c2db2) | Aug 07, 2023 |
| HP            | 158A                        | Desktop     | [657812fbbf](https://linux-hardware.org/?probe=657812fbbf) | Aug 07, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [51c3d4511a](https://linux-hardware.org/?probe=51c3d4511a) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [5e64d2b59e](https://linux-hardware.org/?probe=5e64d2b59e) | Aug 06, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [458a26f70c](https://linux-hardware.org/?probe=458a26f70c) | Aug 06, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [5a254fe1d6](https://linux-hardware.org/?probe=5a254fe1d6) | Aug 06, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [f670b492a9](https://linux-hardware.org/?probe=f670b492a9) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [35bb5f3e65](https://linux-hardware.org/?probe=35bb5f3e65) | Aug 06, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [bd989967e7](https://linux-hardware.org/?probe=bd989967e7) | Aug 06, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [597461a5ac](https://linux-hardware.org/?probe=597461a5ac) | Aug 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [48cf16e31d](https://linux-hardware.org/?probe=48cf16e31d) | Aug 06, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [e815f65a97](https://linux-hardware.org/?probe=e815f65a97) | Aug 05, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [dfc4d46266](https://linux-hardware.org/?probe=dfc4d46266) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [eb92759c2a](https://linux-hardware.org/?probe=eb92759c2a) | Aug 05, 2023 |
| Dell          | G15 5520                    | Notebook    | [baca0d14f5](https://linux-hardware.org/?probe=baca0d14f5) | Aug 05, 2023 |
| HP            | Pavilion g6                 | Notebook    | [fafbd706de](https://linux-hardware.org/?probe=fafbd706de) | Aug 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [dd1767aec1](https://linux-hardware.org/?probe=dd1767aec1) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [af4f153b11](https://linux-hardware.org/?probe=af4f153b11) | Aug 04, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [c163ae3710](https://linux-hardware.org/?probe=c163ae3710) | Aug 04, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [656e917b79](https://linux-hardware.org/?probe=656e917b79) | Aug 04, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [363bee1696](https://linux-hardware.org/?probe=363bee1696) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [31d1c3bfbc](https://linux-hardware.org/?probe=31d1c3bfbc) | Aug 03, 2023 |
| HP            | 21D0                        | Desktop     | [44e0cbb52e](https://linux-hardware.org/?probe=44e0cbb52e) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7f601fe313](https://linux-hardware.org/?probe=7f601fe313) | Aug 03, 2023 |
| HP            | 21D0                        | Desktop     | [099fea9193](https://linux-hardware.org/?probe=099fea9193) | Aug 02, 2023 |
| HP            | Pavilion g7                 | Notebook    | [882d2d9a16](https://linux-hardware.org/?probe=882d2d9a16) | Aug 02, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [75c36d43c3](https://linux-hardware.org/?probe=75c36d43c3) | Aug 02, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [e391326d89](https://linux-hardware.org/?probe=e391326d89) | Aug 02, 2023 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [251b811e9b](https://linux-hardware.org/?probe=251b811e9b) | Aug 02, 2023 |
| HP            | Notebook                    | Notebook    | [258f6a82ad](https://linux-hardware.org/?probe=258f6a82ad) | Aug 02, 2023 |
| MSI           | H170M PRO-DH                | Desktop     | [e0b553c4dd](https://linux-hardware.org/?probe=e0b553c4dd) | Aug 02, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [eb2554dce9](https://linux-hardware.org/?probe=eb2554dce9) | Aug 02, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [451bfcf27d](https://linux-hardware.org/?probe=451bfcf27d) | Aug 02, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [79c3c3612b](https://linux-hardware.org/?probe=79c3c3612b) | Aug 02, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [19aa30337f](https://linux-hardware.org/?probe=19aa30337f) | Aug 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [589f0a8599](https://linux-hardware.org/?probe=589f0a8599) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [8da287a76b](https://linux-hardware.org/?probe=8da287a76b) | Aug 01, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [26cca552dd](https://linux-hardware.org/?probe=26cca552dd) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [93d193bdbc](https://linux-hardware.org/?probe=93d193bdbc) | Aug 01, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [8aaca0803f](https://linux-hardware.org/?probe=8aaca0803f) | Jul 31, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [18924cfab7](https://linux-hardware.org/?probe=18924cfab7) | Jul 31, 2023 |
| Samsung       | 535U3C                      | Notebook    | [8d0ebb957a](https://linux-hardware.org/?probe=8d0ebb957a) | Jul 31, 2023 |
| Samsung       | 535U3C                      | Notebook    | [030fc15fac](https://linux-hardware.org/?probe=030fc15fac) | Jul 31, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [93c8724c91](https://linux-hardware.org/?probe=93c8724c91) | Jul 31, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8559f3826b](https://linux-hardware.org/?probe=8559f3826b) | Jul 31, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [04b1a06dbd](https://linux-hardware.org/?probe=04b1a06dbd) | Jul 30, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e66bd4564e](https://linux-hardware.org/?probe=e66bd4564e) | Jul 30, 2023 |
| Apple         | MacBookAir1,1               | Notebook    | [ac140cf8c4](https://linux-hardware.org/?probe=ac140cf8c4) | Jul 30, 2023 |
| Unknown       | HX90                        | Desktop     | [2eba30b5be](https://linux-hardware.org/?probe=2eba30b5be) | Jul 30, 2023 |
| HP            | Folio 13                    | Notebook    | [baaa648a4b](https://linux-hardware.org/?probe=baaa648a4b) | Jul 29, 2023 |
| Dell          | Latitude E6230              | Notebook    | [462496c6db](https://linux-hardware.org/?probe=462496c6db) | Jul 29, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [60bf32a368](https://linux-hardware.org/?probe=60bf32a368) | Jul 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [fb2ba2d3eb](https://linux-hardware.org/?probe=fb2ba2d3eb) | Jul 29, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [1b9bb7c266](https://linux-hardware.org/?probe=1b9bb7c266) | Jul 29, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [51d9b57967](https://linux-hardware.org/?probe=51d9b57967) | Jul 29, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [081608e70c](https://linux-hardware.org/?probe=081608e70c) | Jul 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [e8368bcae8](https://linux-hardware.org/?probe=e8368bcae8) | Jul 28, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [32fcc0f81f](https://linux-hardware.org/?probe=32fcc0f81f) | Jul 28, 2023 |
| Intel         | HM570                       | Desktop     | [c969a88e87](https://linux-hardware.org/?probe=c969a88e87) | Jul 28, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [3c0f7ba188](https://linux-hardware.org/?probe=3c0f7ba188) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [d32fa8840b](https://linux-hardware.org/?probe=d32fa8840b) | Jul 27, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [1a6962dc65](https://linux-hardware.org/?probe=1a6962dc65) | Jul 27, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [0b04075e09](https://linux-hardware.org/?probe=0b04075e09) | Jul 27, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [20221ed288](https://linux-hardware.org/?probe=20221ed288) | Jul 27, 2023 |
| Lenovo        | 3743 SDK0J40700 WIN 3258... | Desktop     | [546f011b1a](https://linux-hardware.org/?probe=546f011b1a) | Jul 27, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [ba305b3271](https://linux-hardware.org/?probe=ba305b3271) | Jul 26, 2023 |
| HP            | Folio 13                    | Notebook    | [a3269c0930](https://linux-hardware.org/?probe=a3269c0930) | Jul 26, 2023 |
| Dell          | G3 3579                     | Notebook    | [b6b50ffa46](https://linux-hardware.org/?probe=b6b50ffa46) | Jul 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [aa34907e3a](https://linux-hardware.org/?probe=aa34907e3a) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [24c092f0b0](https://linux-hardware.org/?probe=24c092f0b0) | Jul 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [a5933aa510](https://linux-hardware.org/?probe=a5933aa510) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [74adf4cb3d](https://linux-hardware.org/?probe=74adf4cb3d) | Jul 26, 2023 |
| Lenovo        | Legion R9000X 2021 82HN     | Notebook    | [0079a4e7a0](https://linux-hardware.org/?probe=0079a4e7a0) | Jul 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [7cd1c7cdf2](https://linux-hardware.org/?probe=7cd1c7cdf2) | Jul 25, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [fcb6317c1b](https://linux-hardware.org/?probe=fcb6317c1b) | Jul 25, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [7da659326d](https://linux-hardware.org/?probe=7da659326d) | Jul 24, 2023 |
| Dell          | Latitude E6230              | Notebook    | [6f832e0bb3](https://linux-hardware.org/?probe=6f832e0bb3) | Jul 24, 2023 |
| SiS Techno... | 760                         | Desktop     | [1c5bd52522](https://linux-hardware.org/?probe=1c5bd52522) | Jul 24, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [176adf0a2b](https://linux-hardware.org/?probe=176adf0a2b) | Jul 24, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4a262a2a2d](https://linux-hardware.org/?probe=4a262a2a2d) | Jul 24, 2023 |
| ASUSTek       | PN61                        | Mini pc     | [78418a9a7f](https://linux-hardware.org/?probe=78418a9a7f) | Jul 24, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [df1a812c11](https://linux-hardware.org/?probe=df1a812c11) | Jul 24, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [bd66a96c97](https://linux-hardware.org/?probe=bd66a96c97) | Jul 24, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [579d5d5771](https://linux-hardware.org/?probe=579d5d5771) | Jul 24, 2023 |
| Dell          | Latitude 5410               | Notebook    | [29261ea2bb](https://linux-hardware.org/?probe=29261ea2bb) | Jul 24, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [f9bd193456](https://linux-hardware.org/?probe=f9bd193456) | Jul 23, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1e169f0ba8](https://linux-hardware.org/?probe=1e169f0ba8) | Jul 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ae4343c245](https://linux-hardware.org/?probe=ae4343c245) | Jul 23, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [b844b9a353](https://linux-hardware.org/?probe=b844b9a353) | Jul 23, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f2f1f87d0c](https://linux-hardware.org/?probe=f2f1f87d0c) | Jul 23, 2023 |
| Dell          | Latitude 5480               | Notebook    | [0595e16f65](https://linux-hardware.org/?probe=0595e16f65) | Jul 23, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [f291f72d81](https://linux-hardware.org/?probe=f291f72d81) | Jul 23, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [c4890b8f34](https://linux-hardware.org/?probe=c4890b8f34) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [23d73ededd](https://linux-hardware.org/?probe=23d73ededd) | Jul 23, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [af255054c3](https://linux-hardware.org/?probe=af255054c3) | Jul 22, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [afc4d3c307](https://linux-hardware.org/?probe=afc4d3c307) | Jul 22, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [be58f943df](https://linux-hardware.org/?probe=be58f943df) | Jul 22, 2023 |
| HP            | 21D0                        | Desktop     | [774375de1f](https://linux-hardware.org/?probe=774375de1f) | Jul 22, 2023 |
| Dell          | Latitude E7440              | Notebook    | [ffa2aad2b5](https://linux-hardware.org/?probe=ffa2aad2b5) | Jul 21, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [f3435d221b](https://linux-hardware.org/?probe=f3435d221b) | Jul 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [516853cca9](https://linux-hardware.org/?probe=516853cca9) | Jul 21, 2023 |
| Biostar       | A320MH                      | Desktop     | [5fd84925fd](https://linux-hardware.org/?probe=5fd84925fd) | Jul 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [874f8dff98](https://linux-hardware.org/?probe=874f8dff98) | Jul 20, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d1dee26c33](https://linux-hardware.org/?probe=d1dee26c33) | Jul 20, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [dc0a2fb7ef](https://linux-hardware.org/?probe=dc0a2fb7ef) | Jul 20, 2023 |
| Lenovo        | 330B SDK0T76530 WIN 3556... | Mini pc     | [f7218e4043](https://linux-hardware.org/?probe=f7218e4043) | Jul 20, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [13a6f964eb](https://linux-hardware.org/?probe=13a6f964eb) | Jul 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c8fa0f7219](https://linux-hardware.org/?probe=c8fa0f7219) | Jul 19, 2023 |
| Dell          | Latitude 5580               | Notebook    | [6efcf73621](https://linux-hardware.org/?probe=6efcf73621) | Jul 19, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d79851836e](https://linux-hardware.org/?probe=d79851836e) | Jul 19, 2023 |
| HP            | G62                         | Notebook    | [c36d4392da](https://linux-hardware.org/?probe=c36d4392da) | Jul 19, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [56e1ff54a3](https://linux-hardware.org/?probe=56e1ff54a3) | Jul 19, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | Notebook    | [dc091872ec](https://linux-hardware.org/?probe=dc091872ec) | Jul 18, 2023 |
| Acer          | One S1003                   | Tablet      | [380ae70fb2](https://linux-hardware.org/?probe=380ae70fb2) | Jul 18, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [ef3c6c941e](https://linux-hardware.org/?probe=ef3c6c941e) | Jul 18, 2023 |
| Google        | Kip                         | Notebook    | [00dd9a1c67](https://linux-hardware.org/?probe=00dd9a1c67) | Jul 18, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [5797e88a56](https://linux-hardware.org/?probe=5797e88a56) | Jul 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [322db1cde6](https://linux-hardware.org/?probe=322db1cde6) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [f0ecaa209e](https://linux-hardware.org/?probe=f0ecaa209e) | Jul 18, 2023 |
| Dell          | Latitude 5580               | Notebook    | [16f62b67d3](https://linux-hardware.org/?probe=16f62b67d3) | Jul 17, 2023 |
| Google        | Dragonair                   | Notebook    | [11d9394545](https://linux-hardware.org/?probe=11d9394545) | Jul 17, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [a83e3b42b3](https://linux-hardware.org/?probe=a83e3b42b3) | Jul 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [553cbdb79d](https://linux-hardware.org/?probe=553cbdb79d) | Jul 17, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [56a9ce9630](https://linux-hardware.org/?probe=56a9ce9630) | Jul 17, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [e46543841d](https://linux-hardware.org/?probe=e46543841d) | Jul 16, 2023 |
| Dell          | G15 5520                    | Notebook    | [ed22e67151](https://linux-hardware.org/?probe=ed22e67151) | Jul 16, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [8977d2e0a3](https://linux-hardware.org/?probe=8977d2e0a3) | Jul 16, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [19b39ef686](https://linux-hardware.org/?probe=19b39ef686) | Jul 16, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [61ed023e0c](https://linux-hardware.org/?probe=61ed023e0c) | Jul 16, 2023 |
| HP            | 8053                        | Desktop     | [bcdddcb036](https://linux-hardware.org/?probe=bcdddcb036) | Jul 15, 2023 |
| Dell          | G3 3779                     | Notebook    | [87b8ecffa4](https://linux-hardware.org/?probe=87b8ecffa4) | Jul 15, 2023 |
| Acer          | One S1003                   | Tablet      | [0e200bc1a5](https://linux-hardware.org/?probe=0e200bc1a5) | Jul 15, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [56448b6dd8](https://linux-hardware.org/?probe=56448b6dd8) | Jul 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [10946f1220](https://linux-hardware.org/?probe=10946f1220) | Jul 15, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [064a46bc1d](https://linux-hardware.org/?probe=064a46bc1d) | Jul 14, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [c56d5e4e7b](https://linux-hardware.org/?probe=c56d5e4e7b) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f1bbc61bb6](https://linux-hardware.org/?probe=f1bbc61bb6) | Jul 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0ac2423aa2](https://linux-hardware.org/?probe=0ac2423aa2) | Jul 14, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1577fae8ee](https://linux-hardware.org/?probe=1577fae8ee) | Jul 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [76513f6a7d](https://linux-hardware.org/?probe=76513f6a7d) | Jul 14, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [7816d37e02](https://linux-hardware.org/?probe=7816d37e02) | Jul 14, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [67b2bb6155](https://linux-hardware.org/?probe=67b2bb6155) | Jul 14, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [91145d3929](https://linux-hardware.org/?probe=91145d3929) | Jul 13, 2023 |
| Lenovo        | ThinkPad X280 20KES73S06    | Notebook    | [b301164e01](https://linux-hardware.org/?probe=b301164e01) | Jul 13, 2023 |
| ASUSTek       | N61Jv                       | Notebook    | [fa3485dbc6](https://linux-hardware.org/?probe=fa3485dbc6) | Jul 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2f943c811e](https://linux-hardware.org/?probe=2f943c811e) | Jul 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [9430a42f8b](https://linux-hardware.org/?probe=9430a42f8b) | Jul 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f73994358d](https://linux-hardware.org/?probe=f73994358d) | Jul 13, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b189eebd1c](https://linux-hardware.org/?probe=b189eebd1c) | Jul 13, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [99c9883e16](https://linux-hardware.org/?probe=99c9883e16) | Jul 12, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [85d4919b9c](https://linux-hardware.org/?probe=85d4919b9c) | Jul 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a167d41a74](https://linux-hardware.org/?probe=a167d41a74) | Jul 12, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [6e7ff15b27](https://linux-hardware.org/?probe=6e7ff15b27) | Jul 11, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [72454f0f8e](https://linux-hardware.org/?probe=72454f0f8e) | Jul 11, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [ea833bb195](https://linux-hardware.org/?probe=ea833bb195) | Jul 11, 2023 |
| HP            | Folio 13                    | Notebook    | [864b74d611](https://linux-hardware.org/?probe=864b74d611) | Jul 11, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [cc4f862316](https://linux-hardware.org/?probe=cc4f862316) | Jul 11, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [0549d09ceb](https://linux-hardware.org/?probe=0549d09ceb) | Jul 11, 2023 |
| HP            | 21D0                        | Desktop     | [a6d51a414c](https://linux-hardware.org/?probe=a6d51a414c) | Jul 11, 2023 |
| HP            | Folio 13                    | Notebook    | [35d5a3c2a3](https://linux-hardware.org/?probe=35d5a3c2a3) | Jul 11, 2023 |
| Dell          | Inspiron 7573               | Notebook    | [7cc0dc9187](https://linux-hardware.org/?probe=7cc0dc9187) | Jul 11, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [cf79171424](https://linux-hardware.org/?probe=cf79171424) | Jul 10, 2023 |
| MSI           | MS-7309                     | Desktop     | [16f6545b66](https://linux-hardware.org/?probe=16f6545b66) | Jul 10, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [ef2ca9e804](https://linux-hardware.org/?probe=ef2ca9e804) | Jul 10, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [3924343595](https://linux-hardware.org/?probe=3924343595) | Jul 10, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [61ac758cca](https://linux-hardware.org/?probe=61ac758cca) | Jul 10, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [7790bc9f7b](https://linux-hardware.org/?probe=7790bc9f7b) | Jul 09, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [ea2102a05b](https://linux-hardware.org/?probe=ea2102a05b) | Jul 09, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [655b6ba155](https://linux-hardware.org/?probe=655b6ba155) | Jul 09, 2023 |
| Intel         | H61                         | Desktop     | [11e024727c](https://linux-hardware.org/?probe=11e024727c) | Jul 09, 2023 |
| HP            | ZBook Studio x360 G5        | Convertible | [e01e0e6f7e](https://linux-hardware.org/?probe=e01e0e6f7e) | Jul 09, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [db2be54a62](https://linux-hardware.org/?probe=db2be54a62) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [ee4b75fe8e](https://linux-hardware.org/?probe=ee4b75fe8e) | Jul 09, 2023 |
| Notebook      | N141CU                      | Notebook    | [6d98546fa9](https://linux-hardware.org/?probe=6d98546fa9) | Jul 09, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [e23beb2c2a](https://linux-hardware.org/?probe=e23beb2c2a) | Jul 08, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [8ef192f620](https://linux-hardware.org/?probe=8ef192f620) | Jul 08, 2023 |
| HP            | 83E2                        | Desktop     | [7764034dad](https://linux-hardware.org/?probe=7764034dad) | Jul 08, 2023 |
| Dell          | Latitude 3380               | Notebook    | [b4403e7b15](https://linux-hardware.org/?probe=b4403e7b15) | Jul 07, 2023 |
| HP            | Folio 13                    | Notebook    | [dd1a09fa9d](https://linux-hardware.org/?probe=dd1a09fa9d) | Jul 07, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [28b2f72ea7](https://linux-hardware.org/?probe=28b2f72ea7) | Jul 07, 2023 |
| Acer          | Predator G3600              | Desktop     | [79f515acf1](https://linux-hardware.org/?probe=79f515acf1) | Jul 07, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1327d1ff3b](https://linux-hardware.org/?probe=1327d1ff3b) | Jul 07, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [dd071cd632](https://linux-hardware.org/?probe=dd071cd632) | Jul 07, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [fdb4fd8cb4](https://linux-hardware.org/?probe=fdb4fd8cb4) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e7a7107e85](https://linux-hardware.org/?probe=e7a7107e85) | Jul 07, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [7d1d71b0fe](https://linux-hardware.org/?probe=7d1d71b0fe) | Jul 06, 2023 |
| HP            | 8053                        | Desktop     | [66ee68d1ba](https://linux-hardware.org/?probe=66ee68d1ba) | Jul 05, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [56609b5da2](https://linux-hardware.org/?probe=56609b5da2) | Jul 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e6d6494e7a](https://linux-hardware.org/?probe=e6d6494e7a) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [cd2c46c45c](https://linux-hardware.org/?probe=cd2c46c45c) | Jul 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [54a88e79d1](https://linux-hardware.org/?probe=54a88e79d1) | Jul 04, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [941c70d512](https://linux-hardware.org/?probe=941c70d512) | Jul 04, 2023 |
| CompuLab      | fitlet                      | Mini pc     | [41b26129b6](https://linux-hardware.org/?probe=41b26129b6) | Jul 04, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [075cc6eb8a](https://linux-hardware.org/?probe=075cc6eb8a) | Jul 04, 2023 |
| Dell          | Inspiron 5765               | Notebook    | [7d34d64627](https://linux-hardware.org/?probe=7d34d64627) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [bba1bf2655](https://linux-hardware.org/?probe=bba1bf2655) | Jul 04, 2023 |
| Foxconn       | H81MXV/H81MXV-D             | Desktop     | [5920f3fec9](https://linux-hardware.org/?probe=5920f3fec9) | Jul 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [5d1b3596c1](https://linux-hardware.org/?probe=5d1b3596c1) | Jul 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [3290dd955a](https://linux-hardware.org/?probe=3290dd955a) | Jul 03, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [78bdc20fe8](https://linux-hardware.org/?probe=78bdc20fe8) | Jul 03, 2023 |
| HP            | 886C                        | Desktop     | [735b488512](https://linux-hardware.org/?probe=735b488512) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [b7222ef19f](https://linux-hardware.org/?probe=b7222ef19f) | Jul 03, 2023 |
| HP            | Folio 13                    | Notebook    | [faf3cb7d1f](https://linux-hardware.org/?probe=faf3cb7d1f) | Jul 03, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [f78f6977d9](https://linux-hardware.org/?probe=f78f6977d9) | Jul 03, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6ce7d33591](https://linux-hardware.org/?probe=6ce7d33591) | Jul 03, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [8120591fdf](https://linux-hardware.org/?probe=8120591fdf) | Jul 02, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e3285ce484](https://linux-hardware.org/?probe=e3285ce484) | Jul 02, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [4f24850748](https://linux-hardware.org/?probe=4f24850748) | Jul 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f341618e19](https://linux-hardware.org/?probe=f341618e19) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5a84f67b67](https://linux-hardware.org/?probe=5a84f67b67) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [80810e133e](https://linux-hardware.org/?probe=80810e133e) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [48df5942cf](https://linux-hardware.org/?probe=48df5942cf) | Jul 02, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [7bdc183ddc](https://linux-hardware.org/?probe=7bdc183ddc) | Jul 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f22f547276](https://linux-hardware.org/?probe=f22f547276) | Jul 01, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d3fb700ff1](https://linux-hardware.org/?probe=d3fb700ff1) | Jul 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a559729258](https://linux-hardware.org/?probe=a559729258) | Jul 01, 2023 |
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [6c8a67be9e](https://linux-hardware.org/?probe=6c8a67be9e) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [10467d9f3e](https://linux-hardware.org/?probe=10467d9f3e) | Jun 30, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [3e1517b7a7](https://linux-hardware.org/?probe=3e1517b7a7) | Jun 30, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [c959833db6](https://linux-hardware.org/?probe=c959833db6) | Jun 30, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [3932620fb9](https://linux-hardware.org/?probe=3932620fb9) | Jun 30, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [a73fd92e21](https://linux-hardware.org/?probe=a73fd92e21) | Jun 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [69cb8803e1](https://linux-hardware.org/?probe=69cb8803e1) | Jun 29, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [eb31590a2c](https://linux-hardware.org/?probe=eb31590a2c) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [b8194aee09](https://linux-hardware.org/?probe=b8194aee09) | Jun 28, 2023 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [031ec94437](https://linux-hardware.org/?probe=031ec94437) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [cb40f5d060](https://linux-hardware.org/?probe=cb40f5d060) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [13ac46e7fb](https://linux-hardware.org/?probe=13ac46e7fb) | Jun 28, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [966b21f9af](https://linux-hardware.org/?probe=966b21f9af) | Jun 28, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1ef6edecef](https://linux-hardware.org/?probe=1ef6edecef) | Jun 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [98ad52d973](https://linux-hardware.org/?probe=98ad52d973) | Jun 28, 2023 |
| AZW           | GTR V02                     | Desktop     | [d8a1975328](https://linux-hardware.org/?probe=d8a1975328) | Jun 27, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9128946047](https://linux-hardware.org/?probe=9128946047) | Jun 27, 2023 |
| HP            | 2B2C                        | Desktop     | [a8ec805431](https://linux-hardware.org/?probe=a8ec805431) | Jun 27, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [dc32791d25](https://linux-hardware.org/?probe=dc32791d25) | Jun 27, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [adf7a275be](https://linux-hardware.org/?probe=adf7a275be) | Jun 27, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [6958b0e619](https://linux-hardware.org/?probe=6958b0e619) | Jun 27, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9e3cbeb0f5](https://linux-hardware.org/?probe=9e3cbeb0f5) | Jun 27, 2023 |
| Dell          | Latitude E6230              | Notebook    | [b52e22e663](https://linux-hardware.org/?probe=b52e22e663) | Jun 27, 2023 |
| ASRock        | G31M-S                      | Desktop     | [2437008395](https://linux-hardware.org/?probe=2437008395) | Jun 26, 2023 |
| HP            | 859B                        | Desktop     | [63fdd4ed7e](https://linux-hardware.org/?probe=63fdd4ed7e) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [13c7f88d66](https://linux-hardware.org/?probe=13c7f88d66) | Jun 26, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [b598080123](https://linux-hardware.org/?probe=b598080123) | Jun 26, 2023 |
| MSI           | GP72MVR 7RGX                | Notebook    | [7fa12ec2d8](https://linux-hardware.org/?probe=7fa12ec2d8) | Jun 26, 2023 |
| HP            | 8599                        | Desktop     | [d72522f488](https://linux-hardware.org/?probe=d72522f488) | Jun 26, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [bc4e778aa5](https://linux-hardware.org/?probe=bc4e778aa5) | Jun 26, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [ad1a470baf](https://linux-hardware.org/?probe=ad1a470baf) | Jun 26, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [3b27404402](https://linux-hardware.org/?probe=3b27404402) | Jun 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3df76bbd0e](https://linux-hardware.org/?probe=3df76bbd0e) | Jun 26, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [49172baecf](https://linux-hardware.org/?probe=49172baecf) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1a21c582de](https://linux-hardware.org/?probe=1a21c582de) | Jun 26, 2023 |
| HP            | 2B2C                        | Desktop     | [3b82186362](https://linux-hardware.org/?probe=3b82186362) | Jun 26, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [1a5d46559c](https://linux-hardware.org/?probe=1a5d46559c) | Jun 25, 2023 |
| Intel         | X99H                        | Desktop     | [60f1f4a8ba](https://linux-hardware.org/?probe=60f1f4a8ba) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [62dd78e250](https://linux-hardware.org/?probe=62dd78e250) | Jun 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [f84d78f3cf](https://linux-hardware.org/?probe=f84d78f3cf) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5679200535](https://linux-hardware.org/?probe=5679200535) | Jun 24, 2023 |
| Intel         | H61                         | Desktop     | [0f1d3e1299](https://linux-hardware.org/?probe=0f1d3e1299) | Jun 24, 2023 |
| HP            | 0A54h                       | Desktop     | [7383b90fc8](https://linux-hardware.org/?probe=7383b90fc8) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [628fca0448](https://linux-hardware.org/?probe=628fca0448) | Jun 24, 2023 |
| AZW           | GT-R                        | Notebook    | [11f032f354](https://linux-hardware.org/?probe=11f032f354) | Jun 24, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b7ac1c1ba6](https://linux-hardware.org/?probe=b7ac1c1ba6) | Jun 24, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [cafe332307](https://linux-hardware.org/?probe=cafe332307) | Jun 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [007cf1edce](https://linux-hardware.org/?probe=007cf1edce) | Jun 23, 2023 |
| HP            | 0A54h                       | Desktop     | [8cf79bc35e](https://linux-hardware.org/?probe=8cf79bc35e) | Jun 23, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [abbe9c9751](https://linux-hardware.org/?probe=abbe9c9751) | Jun 23, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [70b7839ea8](https://linux-hardware.org/?probe=70b7839ea8) | Jun 23, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [645a24c7bc](https://linux-hardware.org/?probe=645a24c7bc) | Jun 23, 2023 |
| Dell          | G5 5505                     | Notebook    | [dbe52869d7](https://linux-hardware.org/?probe=dbe52869d7) | Jun 23, 2023 |
| Dell          | Latitude E6420              | Notebook    | [162293d893](https://linux-hardware.org/?probe=162293d893) | Jun 23, 2023 |
| Dell          | G5 5505                     | Notebook    | [f435440e91](https://linux-hardware.org/?probe=f435440e91) | Jun 23, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [7f87bb5b32](https://linux-hardware.org/?probe=7f87bb5b32) | Jun 23, 2023 |
| MSI           | GL73 8RD                    | Notebook    | [2739b46bbe](https://linux-hardware.org/?probe=2739b46bbe) | Jun 23, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [70b047f976](https://linux-hardware.org/?probe=70b047f976) | Jun 22, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [2807f81cc7](https://linux-hardware.org/?probe=2807f81cc7) | Jun 22, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [bbdbdd30a9](https://linux-hardware.org/?probe=bbdbdd30a9) | Jun 22, 2023 |
| HP            | 2B2C                        | Desktop     | [4303d28839](https://linux-hardware.org/?probe=4303d28839) | Jun 22, 2023 |
| HP            | 802F                        | Desktop     | [da2666b4b8](https://linux-hardware.org/?probe=da2666b4b8) | Jun 22, 2023 |
| Sony          | SVE1712C1EW                 | Notebook    | [12f0ee026f](https://linux-hardware.org/?probe=12f0ee026f) | Jun 22, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [3d506cafad](https://linux-hardware.org/?probe=3d506cafad) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [69dfee1765](https://linux-hardware.org/?probe=69dfee1765) | Jun 22, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [5199a5d1f8](https://linux-hardware.org/?probe=5199a5d1f8) | Jun 22, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [198b248306](https://linux-hardware.org/?probe=198b248306) | Jun 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [6609cc4a31](https://linux-hardware.org/?probe=6609cc4a31) | Jun 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [31d17d4d65](https://linux-hardware.org/?probe=31d17d4d65) | Jun 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [8845f67824](https://linux-hardware.org/?probe=8845f67824) | Jun 22, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [eba6a24be2](https://linux-hardware.org/?probe=eba6a24be2) | Jun 21, 2023 |
| MSI           | X99A SLI Krait Edition      | Desktop     | [2e86965134](https://linux-hardware.org/?probe=2e86965134) | Jun 21, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [fd3c5ae570](https://linux-hardware.org/?probe=fd3c5ae570) | Jun 21, 2023 |
| Emdoor        | AG958                       | Notebook    | [3574f89b15](https://linux-hardware.org/?probe=3574f89b15) | Jun 21, 2023 |
| HP            | 802F                        | Desktop     | [96b020f763](https://linux-hardware.org/?probe=96b020f763) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [fc06bc7209](https://linux-hardware.org/?probe=fc06bc7209) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [0a36c0985d](https://linux-hardware.org/?probe=0a36c0985d) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [0ccace2cfb](https://linux-hardware.org/?probe=0ccace2cfb) | Jun 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [3e09affd03](https://linux-hardware.org/?probe=3e09affd03) | Jun 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [529320d8fe](https://linux-hardware.org/?probe=529320d8fe) | Jun 20, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [b6b7fa0f5d](https://linux-hardware.org/?probe=b6b7fa0f5d) | Jun 19, 2023 |
| MSI           | Z170A GAMING M7             | Desktop     | [49e7c6d51b](https://linux-hardware.org/?probe=49e7c6d51b) | Jun 19, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [7b370bd18c](https://linux-hardware.org/?probe=7b370bd18c) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [63381e724a](https://linux-hardware.org/?probe=63381e724a) | Jun 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [3acc831573](https://linux-hardware.org/?probe=3acc831573) | Jun 19, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [6579287940](https://linux-hardware.org/?probe=6579287940) | Jun 18, 2023 |
| Razer         | Blade Stealth 13 (Early ... | Notebook    | [e3843be450](https://linux-hardware.org/?probe=e3843be450) | Jun 18, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [928b30815b](https://linux-hardware.org/?probe=928b30815b) | Jun 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [f4cf5bef09](https://linux-hardware.org/?probe=f4cf5bef09) | Jun 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [9fe2c6961e](https://linux-hardware.org/?probe=9fe2c6961e) | Jun 18, 2023 |
| Dell          | 06JWJY A01                  | Desktop     | [2131eadb5b](https://linux-hardware.org/?probe=2131eadb5b) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [8fe751618d](https://linux-hardware.org/?probe=8fe751618d) | Jun 18, 2023 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [8385742d7d](https://linux-hardware.org/?probe=8385742d7d) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [337d8e9d36](https://linux-hardware.org/?probe=337d8e9d36) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5c365e154b](https://linux-hardware.org/?probe=5c365e154b) | Jun 17, 2023 |
| Intel         | H55                         | Desktop     | [d47f462b1a](https://linux-hardware.org/?probe=d47f462b1a) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [4907b6927a](https://linux-hardware.org/?probe=4907b6927a) | Jun 16, 2023 |
| HP            | 886C                        | Desktop     | [ef429234c7](https://linux-hardware.org/?probe=ef429234c7) | Jun 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1412c501d2](https://linux-hardware.org/?probe=1412c501d2) | Jun 16, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [896d66d33f](https://linux-hardware.org/?probe=896d66d33f) | Jun 16, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [b26c331bfc](https://linux-hardware.org/?probe=b26c331bfc) | Jun 16, 2023 |
| Intel         | H55                         | Desktop     | [76c89618f1](https://linux-hardware.org/?probe=76c89618f1) | Jun 16, 2023 |
| CompuLab      | fitlet                      | Mini pc     | [82c3257031](https://linux-hardware.org/?probe=82c3257031) | Jun 16, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [4448a99385](https://linux-hardware.org/?probe=4448a99385) | Jun 16, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [16ad11571a](https://linux-hardware.org/?probe=16ad11571a) | Jun 15, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [c612df2e8c](https://linux-hardware.org/?probe=c612df2e8c) | Jun 15, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [9c446242a8](https://linux-hardware.org/?probe=9c446242a8) | Jun 15, 2023 |
| Intel         | H61                         | Desktop     | [ac2b137243](https://linux-hardware.org/?probe=ac2b137243) | Jun 15, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [74a69e5cca](https://linux-hardware.org/?probe=74a69e5cca) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [bd74568d10](https://linux-hardware.org/?probe=bd74568d10) | Jun 15, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [175aa8aae4](https://linux-hardware.org/?probe=175aa8aae4) | Jun 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [91af63490c](https://linux-hardware.org/?probe=91af63490c) | Jun 15, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [dba6acd01e](https://linux-hardware.org/?probe=dba6acd01e) | Jun 15, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [7670492b40](https://linux-hardware.org/?probe=7670492b40) | Jun 15, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [3dd5692b24](https://linux-hardware.org/?probe=3dd5692b24) | Jun 15, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [550aa0fda6](https://linux-hardware.org/?probe=550aa0fda6) | Jun 14, 2023 |
| ASRock        | Z97 Extreme6                | Desktop     | [8f727c50fb](https://linux-hardware.org/?probe=8f727c50fb) | Jun 14, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [0e499971b7](https://linux-hardware.org/?probe=0e499971b7) | Jun 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [5349772ea1](https://linux-hardware.org/?probe=5349772ea1) | Jun 14, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [192105166b](https://linux-hardware.org/?probe=192105166b) | Jun 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [3a8338d906](https://linux-hardware.org/?probe=3a8338d906) | Jun 13, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [0b917dc778](https://linux-hardware.org/?probe=0b917dc778) | Jun 13, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [e722fda49e](https://linux-hardware.org/?probe=e722fda49e) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [bd6a04d15d](https://linux-hardware.org/?probe=bd6a04d15d) | Jun 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [6a1f1e134c](https://linux-hardware.org/?probe=6a1f1e134c) | Jun 13, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [93cd1fd89c](https://linux-hardware.org/?probe=93cd1fd89c) | Jun 13, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c3ec3eaa27](https://linux-hardware.org/?probe=c3ec3eaa27) | Jun 13, 2023 |
| Acidanther... | Mac-AF89B6D9451A490B iMa... | All in one  | [b9e0fd4223](https://linux-hardware.org/?probe=b9e0fd4223) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [58235def6c](https://linux-hardware.org/?probe=58235def6c) | Jun 12, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [1fad9d3d52](https://linux-hardware.org/?probe=1fad9d3d52) | Jun 12, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [98a4801b23](https://linux-hardware.org/?probe=98a4801b23) | Jun 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7be8732d39](https://linux-hardware.org/?probe=7be8732d39) | Jun 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [66a01fdc35](https://linux-hardware.org/?probe=66a01fdc35) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [f92739d54b](https://linux-hardware.org/?probe=f92739d54b) | Jun 11, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [2fe8080014](https://linux-hardware.org/?probe=2fe8080014) | Jun 11, 2023 |
| HP            | OMEN by Laptop 15t-en000    | Notebook    | [cdda8d0103](https://linux-hardware.org/?probe=cdda8d0103) | Jun 11, 2023 |
| HP            | 2B0D A01                    | All in one  | [b4f5677d00](https://linux-hardware.org/?probe=b4f5677d00) | Jun 11, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [a192769f1b](https://linux-hardware.org/?probe=a192769f1b) | Jun 11, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [8a07e36a48](https://linux-hardware.org/?probe=8a07e36a48) | Jun 11, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [396e828c07](https://linux-hardware.org/?probe=396e828c07) | Jun 11, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [d71e612bbb](https://linux-hardware.org/?probe=d71e612bbb) | Jun 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7eda1ce433](https://linux-hardware.org/?probe=7eda1ce433) | Jun 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4fcc967374](https://linux-hardware.org/?probe=4fcc967374) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [864729436a](https://linux-hardware.org/?probe=864729436a) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [07dac575d9](https://linux-hardware.org/?probe=07dac575d9) | Jun 10, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [49ebfc0459](https://linux-hardware.org/?probe=49ebfc0459) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [7ab0866235](https://linux-hardware.org/?probe=7ab0866235) | Jun 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [29085f8fb4](https://linux-hardware.org/?probe=29085f8fb4) | Jun 10, 2023 |
| MSI           | MS-B9321                    | Desktop     | [a7a878dbe6](https://linux-hardware.org/?probe=a7a878dbe6) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0eae3567d9](https://linux-hardware.org/?probe=0eae3567d9) | Jun 10, 2023 |
| ASRock        | B550AM Gaming               | Desktop     | [eca79c3bbb](https://linux-hardware.org/?probe=eca79c3bbb) | Jun 10, 2023 |
| Lenovo        | ThinkPad T440 20B6005RUS    | Notebook    | [e7ea5a9368](https://linux-hardware.org/?probe=e7ea5a9368) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [5446a0003e](https://linux-hardware.org/?probe=5446a0003e) | Jun 10, 2023 |
| HP            | Notebook                    | Notebook    | [9487146a2f](https://linux-hardware.org/?probe=9487146a2f) | Jun 09, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [9b52b20f3e](https://linux-hardware.org/?probe=9b52b20f3e) | Jun 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [c5accf4cf8](https://linux-hardware.org/?probe=c5accf4cf8) | Jun 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [45e51a6b5d](https://linux-hardware.org/?probe=45e51a6b5d) | Jun 09, 2023 |
| HP            | 2B0D A01                    | All in one  | [84275606e0](https://linux-hardware.org/?probe=84275606e0) | Jun 09, 2023 |
| Acer          | Aspire A517-53              | Notebook    | [c14dcffa32](https://linux-hardware.org/?probe=c14dcffa32) | Jun 08, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3f04b950e8](https://linux-hardware.org/?probe=3f04b950e8) | Jun 08, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [4614addc21](https://linux-hardware.org/?probe=4614addc21) | Jun 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [b7f109f62e](https://linux-hardware.org/?probe=b7f109f62e) | Jun 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [8d48df5869](https://linux-hardware.org/?probe=8d48df5869) | Jun 07, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [73bc5d84c9](https://linux-hardware.org/?probe=73bc5d84c9) | Jun 07, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [281be42f34](https://linux-hardware.org/?probe=281be42f34) | Jun 07, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [6eeacffa3c](https://linux-hardware.org/?probe=6eeacffa3c) | Jun 07, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [db91b1b71c](https://linux-hardware.org/?probe=db91b1b71c) | Jun 07, 2023 |
| Dell          | 06D7TR A01                  | Desktop     | [8db1a8c132](https://linux-hardware.org/?probe=8db1a8c132) | Jun 06, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [d2c05f91c4](https://linux-hardware.org/?probe=d2c05f91c4) | Jun 06, 2023 |
| HP            | 8053                        | Desktop     | [29a84ce224](https://linux-hardware.org/?probe=29a84ce224) | Jun 06, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [249f9343d0](https://linux-hardware.org/?probe=249f9343d0) | Jun 06, 2023 |
| Win elemen... | M600                        | Desktop     | [360ab80d9b](https://linux-hardware.org/?probe=360ab80d9b) | Jun 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [bdfe605b6a](https://linux-hardware.org/?probe=bdfe605b6a) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [a9ea51ea77](https://linux-hardware.org/?probe=a9ea51ea77) | Jun 06, 2023 |
| Dell          | Precision 7510              | Notebook    | [2a465173d3](https://linux-hardware.org/?probe=2a465173d3) | Jun 06, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [18663e1382](https://linux-hardware.org/?probe=18663e1382) | Jun 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [38882f47af](https://linux-hardware.org/?probe=38882f47af) | Jun 05, 2023 |
| Toshiba       | Satellite L305              | Notebook    | [c11012336c](https://linux-hardware.org/?probe=c11012336c) | Jun 05, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [917462f8c8](https://linux-hardware.org/?probe=917462f8c8) | Jun 05, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [50f682ce84](https://linux-hardware.org/?probe=50f682ce84) | Jun 04, 2023 |
| SYWZ          | S200 Series                 | Desktop     | [577c490fb7](https://linux-hardware.org/?probe=577c490fb7) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [87b33e1181](https://linux-hardware.org/?probe=87b33e1181) | Jun 04, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [9a66179aaf](https://linux-hardware.org/?probe=9a66179aaf) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a39c2e8d55](https://linux-hardware.org/?probe=a39c2e8d55) | Jun 04, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [b0efe96508](https://linux-hardware.org/?probe=b0efe96508) | Jun 04, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [6f8af3d7af](https://linux-hardware.org/?probe=6f8af3d7af) | Jun 03, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [b92c18e955](https://linux-hardware.org/?probe=b92c18e955) | Jun 03, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [5ee3eec233](https://linux-hardware.org/?probe=5ee3eec233) | Jun 03, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [46920007ed](https://linux-hardware.org/?probe=46920007ed) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 2325SLU       | Notebook    | [3a1d630346](https://linux-hardware.org/?probe=3a1d630346) | Jun 03, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [30a95a3f53](https://linux-hardware.org/?probe=30a95a3f53) | Jun 03, 2023 |
| AZW           | SER V01                     | Mini pc     | [e28ef4a6b7](https://linux-hardware.org/?probe=e28ef4a6b7) | Jun 03, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [7837922f5b](https://linux-hardware.org/?probe=7837922f5b) | Jun 02, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [3de77b392a](https://linux-hardware.org/?probe=3de77b392a) | Jun 02, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [b4ba7702cb](https://linux-hardware.org/?probe=b4ba7702cb) | Jun 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c9e073b763](https://linux-hardware.org/?probe=c9e073b763) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2349GDU       | Notebook    | [ca1bce793b](https://linux-hardware.org/?probe=ca1bce793b) | Jun 01, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [1bd92e67d7](https://linux-hardware.org/?probe=1bd92e67d7) | Jun 01, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [d75bfc397f](https://linux-hardware.org/?probe=d75bfc397f) | Jun 01, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [6b3efa1ef7](https://linux-hardware.org/?probe=6b3efa1ef7) | May 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [270fcf5e69](https://linux-hardware.org/?probe=270fcf5e69) | May 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [79de4bed98](https://linux-hardware.org/?probe=79de4bed98) | May 31, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [6c814f5bb5](https://linux-hardware.org/?probe=6c814f5bb5) | May 31, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [d21f59bea5](https://linux-hardware.org/?probe=d21f59bea5) | May 31, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [9131b2b568](https://linux-hardware.org/?probe=9131b2b568) | May 31, 2023 |
| Acer          | Predator G9-793             | Notebook    | [26ea66d872](https://linux-hardware.org/?probe=26ea66d872) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2349GDU       | Notebook    | [eae4d1e9ba](https://linux-hardware.org/?probe=eae4d1e9ba) | May 31, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [2ad4b7fd55](https://linux-hardware.org/?probe=2ad4b7fd55) | May 30, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6dbaa9e2ff](https://linux-hardware.org/?probe=6dbaa9e2ff) | May 30, 2023 |
| HP            | 82DC 1000                   | All in one  | [8300907fc1](https://linux-hardware.org/?probe=8300907fc1) | May 30, 2023 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [4ed64d3d45](https://linux-hardware.org/?probe=4ed64d3d45) | May 30, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [5c089f9b06](https://linux-hardware.org/?probe=5c089f9b06) | May 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [8ec80f5e43](https://linux-hardware.org/?probe=8ec80f5e43) | May 30, 2023 |
| Dell          | 002KVM A01                  | Desktop     | [09d2d63c82](https://linux-hardware.org/?probe=09d2d63c82) | May 30, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8e0413af72](https://linux-hardware.org/?probe=8e0413af72) | May 30, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [9171b7f0f0](https://linux-hardware.org/?probe=9171b7f0f0) | May 29, 2023 |
| Lenovo        | ThinkPad T430 2349GDU       | Notebook    | [829c193554](https://linux-hardware.org/?probe=829c193554) | May 29, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [b90162f812](https://linux-hardware.org/?probe=b90162f812) | May 29, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [1aa973f6bc](https://linux-hardware.org/?probe=1aa973f6bc) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [77e5b682ff](https://linux-hardware.org/?probe=77e5b682ff) | May 28, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [04e50de864](https://linux-hardware.org/?probe=04e50de864) | May 28, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [519e04a228](https://linux-hardware.org/?probe=519e04a228) | May 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [e92f94ecb3](https://linux-hardware.org/?probe=e92f94ecb3) | May 27, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [f7f07e78d5](https://linux-hardware.org/?probe=f7f07e78d5) | May 27, 2023 |
| ASRock        | H87M Pro4                   | Desktop     | [efd2db0783](https://linux-hardware.org/?probe=efd2db0783) | May 27, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [cb642c7b9d](https://linux-hardware.org/?probe=cb642c7b9d) | May 27, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [b5fd752412](https://linux-hardware.org/?probe=b5fd752412) | May 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d5d9543a5a](https://linux-hardware.org/?probe=d5d9543a5a) | May 26, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [07ecf79e17](https://linux-hardware.org/?probe=07ecf79e17) | May 26, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [ca130b5f89](https://linux-hardware.org/?probe=ca130b5f89) | May 26, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [184afbb9c3](https://linux-hardware.org/?probe=184afbb9c3) | May 26, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [3392305134](https://linux-hardware.org/?probe=3392305134) | May 26, 2023 |
| HP            | 8437                        | Desktop     | [c1c9154683](https://linux-hardware.org/?probe=c1c9154683) | May 26, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [89b7c17d00](https://linux-hardware.org/?probe=89b7c17d00) | May 26, 2023 |
| ASUSTek       | X751LAB                     | Notebook    | [02b17f35d9](https://linux-hardware.org/?probe=02b17f35d9) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [13906a8f3d](https://linux-hardware.org/?probe=13906a8f3d) | May 26, 2023 |
| A14CR         | Unknown                     | Notebook    | [a504061244](https://linux-hardware.org/?probe=a504061244) | May 25, 2023 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [b00cde0e71](https://linux-hardware.org/?probe=b00cde0e71) | May 25, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [52e1964d2c](https://linux-hardware.org/?probe=52e1964d2c) | May 25, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [7389c979b6](https://linux-hardware.org/?probe=7389c979b6) | May 25, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [e52868c107](https://linux-hardware.org/?probe=e52868c107) | May 25, 2023 |
| Dell          | Precision 7510              | Notebook    | [8c677420fa](https://linux-hardware.org/?probe=8c677420fa) | May 25, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [1387725836](https://linux-hardware.org/?probe=1387725836) | May 24, 2023 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [e51dec5daf](https://linux-hardware.org/?probe=e51dec5daf) | May 24, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c309714d15](https://linux-hardware.org/?probe=c309714d15) | May 23, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [627afe1447](https://linux-hardware.org/?probe=627afe1447) | May 23, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3d594ff1da](https://linux-hardware.org/?probe=3d594ff1da) | May 23, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [a2986e9b7a](https://linux-hardware.org/?probe=a2986e9b7a) | May 23, 2023 |
| Lenovo        | ThinkPad T550 20CJS0S800    | Notebook    | [b7efa91563](https://linux-hardware.org/?probe=b7efa91563) | May 23, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [e250801798](https://linux-hardware.org/?probe=e250801798) | May 23, 2023 |
| Dell          | Precision 7510              | Notebook    | [15458a1b29](https://linux-hardware.org/?probe=15458a1b29) | May 22, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [87b976a24c](https://linux-hardware.org/?probe=87b976a24c) | May 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [5e89fe1dc9](https://linux-hardware.org/?probe=5e89fe1dc9) | May 22, 2023 |
| Lenovo        | ThinkPad T550 20CJS1V900    | Notebook    | [9bc275ef54](https://linux-hardware.org/?probe=9bc275ef54) | May 22, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [a1fb857bcc](https://linux-hardware.org/?probe=a1fb857bcc) | May 22, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | Notebook    | [7cba5b3595](https://linux-hardware.org/?probe=7cba5b3595) | May 22, 2023 |
| HP            | 8599                        | Desktop     | [2e9caaf13a](https://linux-hardware.org/?probe=2e9caaf13a) | May 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ab21a2a608](https://linux-hardware.org/?probe=ab21a2a608) | May 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [ef28026334](https://linux-hardware.org/?probe=ef28026334) | May 22, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [5534aabaf1](https://linux-hardware.org/?probe=5534aabaf1) | May 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [cf10c1fb13](https://linux-hardware.org/?probe=cf10c1fb13) | May 21, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [9db5706bfc](https://linux-hardware.org/?probe=9db5706bfc) | May 21, 2023 |
| ASUSTek       | X540SC                      | Notebook    | [240bb6c246](https://linux-hardware.org/?probe=240bb6c246) | May 21, 2023 |
| MSI           | A320M-HDV R4.0              | Desktop     | [e7a27c7429](https://linux-hardware.org/?probe=e7a27c7429) | May 21, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [2df0364d3c](https://linux-hardware.org/?probe=2df0364d3c) | May 21, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [222ebac915](https://linux-hardware.org/?probe=222ebac915) | May 21, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [bc16fc021e](https://linux-hardware.org/?probe=bc16fc021e) | May 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8f2ccf9c6d](https://linux-hardware.org/?probe=8f2ccf9c6d) | May 21, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1fdf5742d0](https://linux-hardware.org/?probe=1fdf5742d0) | May 21, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301VU_GZ3... | Tablet      | [3e94769b79](https://linux-hardware.org/?probe=3e94769b79) | May 20, 2023 |
| Lenovo        | ThinkPad T430 2347EA2       | Notebook    | [dc3fdbd5ff](https://linux-hardware.org/?probe=dc3fdbd5ff) | May 20, 2023 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [14e978a000](https://linux-hardware.org/?probe=14e978a000) | May 20, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [d687dbc74a](https://linux-hardware.org/?probe=d687dbc74a) | May 20, 2023 |
| HP            | 8433 11                     | Desktop     | [5d9e3a1dcc](https://linux-hardware.org/?probe=5d9e3a1dcc) | May 20, 2023 |
| Eluktronic... | MAG-15 1660Ti               | Notebook    | [55ced5d6bb](https://linux-hardware.org/?probe=55ced5d6bb) | May 20, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [b001b01a08](https://linux-hardware.org/?probe=b001b01a08) | May 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f76ac6d7b5](https://linux-hardware.org/?probe=f76ac6d7b5) | May 19, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [76592cf444](https://linux-hardware.org/?probe=76592cf444) | May 19, 2023 |
| NEC Comput... | PC-VK26TXZCM                | Notebook    | [064b725160](https://linux-hardware.org/?probe=064b725160) | May 19, 2023 |
| Lenovo        | ThinkPad T430 2347EA2       | Notebook    | [c718a18472](https://linux-hardware.org/?probe=c718a18472) | May 19, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [dde73bc060](https://linux-hardware.org/?probe=dde73bc060) | May 18, 2023 |
| Medion        | BTDD-TI                     | All in one  | [cc45e1f2f4](https://linux-hardware.org/?probe=cc45e1f2f4) | May 18, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [763654d8fc](https://linux-hardware.org/?probe=763654d8fc) | May 18, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [bf1eed0e60](https://linux-hardware.org/?probe=bf1eed0e60) | May 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [3c8dcfcf15](https://linux-hardware.org/?probe=3c8dcfcf15) | May 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [fd87e57fc3](https://linux-hardware.org/?probe=fd87e57fc3) | May 18, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [856242dc26](https://linux-hardware.org/?probe=856242dc26) | May 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [70b4a6b7f7](https://linux-hardware.org/?probe=70b4a6b7f7) | May 18, 2023 |
| HP            | 339A                        | Desktop     | [44a6e1f861](https://linux-hardware.org/?probe=44a6e1f861) | May 17, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [7f3487434e](https://linux-hardware.org/?probe=7f3487434e) | May 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7957c81218](https://linux-hardware.org/?probe=7957c81218) | May 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1aedc7da48](https://linux-hardware.org/?probe=1aedc7da48) | May 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e236450e11](https://linux-hardware.org/?probe=e236450e11) | May 17, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [0c26a47ae5](https://linux-hardware.org/?probe=0c26a47ae5) | May 17, 2023 |
| Acer          | Predator G9-793             | Notebook    | [1739ea2f45](https://linux-hardware.org/?probe=1739ea2f45) | May 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [f4514801d8](https://linux-hardware.org/?probe=f4514801d8) | May 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e31c83db5e](https://linux-hardware.org/?probe=e31c83db5e) | May 16, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d9b18c7990](https://linux-hardware.org/?probe=d9b18c7990) | May 16, 2023 |
| HP            | ENVY dv6                    | Notebook    | [2490803f28](https://linux-hardware.org/?probe=2490803f28) | May 16, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [b06c75ac5e](https://linux-hardware.org/?probe=b06c75ac5e) | May 16, 2023 |
| Lenovo        | ThinkPad T440 20B7S1MF0D    | Notebook    | [6173458650](https://linux-hardware.org/?probe=6173458650) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [8c10a0ad96](https://linux-hardware.org/?probe=8c10a0ad96) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [be5ad76a6e](https://linux-hardware.org/?probe=be5ad76a6e) | May 16, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [19feb08b89](https://linux-hardware.org/?probe=19feb08b89) | May 15, 2023 |
| Google        | Sumo                        | Desktop     | [1455a81901](https://linux-hardware.org/?probe=1455a81901) | May 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [93979d632e](https://linux-hardware.org/?probe=93979d632e) | May 15, 2023 |
| Toshiba       | TECRA Z40-A                 | Notebook    | [55210b06ca](https://linux-hardware.org/?probe=55210b06ca) | May 15, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [53f395d7fa](https://linux-hardware.org/?probe=53f395d7fa) | May 15, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f97e4e7fc1](https://linux-hardware.org/?probe=f97e4e7fc1) | May 15, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [9beabf1347](https://linux-hardware.org/?probe=9beabf1347) | May 15, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [eaef457c8a](https://linux-hardware.org/?probe=eaef457c8a) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [36df0e0f57](https://linux-hardware.org/?probe=36df0e0f57) | May 14, 2023 |
| Unknown       | HX90                        | Desktop     | [85edf2e24e](https://linux-hardware.org/?probe=85edf2e24e) | May 14, 2023 |
| ASUSTek       | G752VT                      | Notebook    | [e8459680a4](https://linux-hardware.org/?probe=e8459680a4) | May 14, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [5bd115a1b4](https://linux-hardware.org/?probe=5bd115a1b4) | May 14, 2023 |
| HP            | ENVY 15                     | Notebook    | [0d1450cd2d](https://linux-hardware.org/?probe=0d1450cd2d) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [49a47c559e](https://linux-hardware.org/?probe=49a47c559e) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [91986cf051](https://linux-hardware.org/?probe=91986cf051) | May 14, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [ced38114fc](https://linux-hardware.org/?probe=ced38114fc) | May 14, 2023 |
| Dell          | Latitude 5490               | Notebook    | [57e94dd4b7](https://linux-hardware.org/?probe=57e94dd4b7) | May 14, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [1556b05d13](https://linux-hardware.org/?probe=1556b05d13) | May 14, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [5e7cf34522](https://linux-hardware.org/?probe=5e7cf34522) | May 14, 2023 |
| MSI           | A320M-HDV R4.0              | Desktop     | [748e0f187f](https://linux-hardware.org/?probe=748e0f187f) | May 14, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [677e681a2d](https://linux-hardware.org/?probe=677e681a2d) | May 13, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [4bde221d90](https://linux-hardware.org/?probe=4bde221d90) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [d0f5ee2781](https://linux-hardware.org/?probe=d0f5ee2781) | May 13, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [71f2dc616d](https://linux-hardware.org/?probe=71f2dc616d) | May 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [82f01de919](https://linux-hardware.org/?probe=82f01de919) | May 12, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [c0841ef7e1](https://linux-hardware.org/?probe=c0841ef7e1) | May 12, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [bfb11f92b1](https://linux-hardware.org/?probe=bfb11f92b1) | May 11, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [ed18615cb3](https://linux-hardware.org/?probe=ed18615cb3) | May 11, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [12d23bdebb](https://linux-hardware.org/?probe=12d23bdebb) | May 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [efc35b1887](https://linux-hardware.org/?probe=efc35b1887) | May 11, 2023 |
| ASRock        | Z370 Extreme4               | Desktop     | [bdd9bcedf5](https://linux-hardware.org/?probe=bdd9bcedf5) | May 11, 2023 |
| Acer          | Predator G9-793             | Notebook    | [95595808a8](https://linux-hardware.org/?probe=95595808a8) | May 11, 2023 |
| ASUSTek       | TUF Gaming H670-PRO WIFI... | Desktop     | [0b4b06b5fa](https://linux-hardware.org/?probe=0b4b06b5fa) | May 10, 2023 |
| ASUSTek       | UX410UAK                    | Notebook    | [d68a2bc7c0](https://linux-hardware.org/?probe=d68a2bc7c0) | May 10, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [b65333ae05](https://linux-hardware.org/?probe=b65333ae05) | May 10, 2023 |
| Lenovo        | 36EB SDK0K17763 WIN 1801... | Desktop     | [4d68e2912b](https://linux-hardware.org/?probe=4d68e2912b) | May 10, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9ce4debe84](https://linux-hardware.org/?probe=9ce4debe84) | May 09, 2023 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [90bec72fa7](https://linux-hardware.org/?probe=90bec72fa7) | May 09, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [756ed502db](https://linux-hardware.org/?probe=756ed502db) | May 09, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [13bace1181](https://linux-hardware.org/?probe=13bace1181) | May 09, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d3de6b6b31](https://linux-hardware.org/?probe=d3de6b6b31) | May 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a4f7fc7b31](https://linux-hardware.org/?probe=a4f7fc7b31) | May 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d055c2e022](https://linux-hardware.org/?probe=d055c2e022) | May 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | Notebook    | [18b79bbfa4](https://linux-hardware.org/?probe=18b79bbfa4) | May 07, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [dbeb828b17](https://linux-hardware.org/?probe=dbeb828b17) | May 07, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d58e08c9ab](https://linux-hardware.org/?probe=d58e08c9ab) | May 07, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6a93900fb9](https://linux-hardware.org/?probe=6a93900fb9) | May 07, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [1eddb3203a](https://linux-hardware.org/?probe=1eddb3203a) | May 06, 2023 |
| System76      | Oryx Pro                    | Notebook    | [6026e88ad4](https://linux-hardware.org/?probe=6026e88ad4) | May 06, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [faabff7b74](https://linux-hardware.org/?probe=faabff7b74) | May 06, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [d905babc43](https://linux-hardware.org/?probe=d905babc43) | May 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1143344e93](https://linux-hardware.org/?probe=1143344e93) | May 06, 2023 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [d572509eb2](https://linux-hardware.org/?probe=d572509eb2) | May 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [91661b66d1](https://linux-hardware.org/?probe=91661b66d1) | May 06, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [5d12a9965b](https://linux-hardware.org/?probe=5d12a9965b) | May 06, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [bb7835495e](https://linux-hardware.org/?probe=bb7835495e) | May 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6a54ace5f8](https://linux-hardware.org/?probe=6a54ace5f8) | May 06, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [3bea2bcd99](https://linux-hardware.org/?probe=3bea2bcd99) | May 05, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [09e73cade8](https://linux-hardware.org/?probe=09e73cade8) | May 05, 2023 |
| ASRock        | H370 Pro4                   | Desktop     | [afffccef92](https://linux-hardware.org/?probe=afffccef92) | May 05, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e28a5499a4](https://linux-hardware.org/?probe=e28a5499a4) | May 05, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [624e1c3f06](https://linux-hardware.org/?probe=624e1c3f06) | May 05, 2023 |
| System76      | Oryx Pro                    | Notebook    | [fe799bc532](https://linux-hardware.org/?probe=fe799bc532) | May 04, 2023 |
| Gigabyte      | 2AC8                        | Desktop     | [4f5b51c45e](https://linux-hardware.org/?probe=4f5b51c45e) | May 04, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [2509256cea](https://linux-hardware.org/?probe=2509256cea) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [3e7b117db0](https://linux-hardware.org/?probe=3e7b117db0) | May 03, 2023 |
| Intel         | DG43GT AAE62768-300         | Desktop     | [e0f10df0f9](https://linux-hardware.org/?probe=e0f10df0f9) | May 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [728b1e3209](https://linux-hardware.org/?probe=728b1e3209) | May 03, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [c20844716d](https://linux-hardware.org/?probe=c20844716d) | May 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2b17563b98](https://linux-hardware.org/?probe=2b17563b98) | May 02, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [8b4f50125b](https://linux-hardware.org/?probe=8b4f50125b) | May 02, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [e5051f5355](https://linux-hardware.org/?probe=e5051f5355) | May 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [f4f7391b8a](https://linux-hardware.org/?probe=f4f7391b8a) | May 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9a43268d9b](https://linux-hardware.org/?probe=9a43268d9b) | May 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [8cb7a3612c](https://linux-hardware.org/?probe=8cb7a3612c) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [446a548122](https://linux-hardware.org/?probe=446a548122) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [f0a784354c](https://linux-hardware.org/?probe=f0a784354c) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [332a777929](https://linux-hardware.org/?probe=332a777929) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [fa805f77f7](https://linux-hardware.org/?probe=fa805f77f7) | Apr 29, 2023 |
| Acer          | Aspire A514-54G             | Notebook    | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [0ea5e1926e](https://linux-hardware.org/?probe=0ea5e1926e) | Apr 29, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [1ef93daf0b](https://linux-hardware.org/?probe=1ef93daf0b) | Apr 28, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [852dac1035](https://linux-hardware.org/?probe=852dac1035) | Apr 28, 2023 |
| Dell          | Latitude E6440              | Notebook    | [d55c77598b](https://linux-hardware.org/?probe=d55c77598b) | Apr 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [19c2a17ec5](https://linux-hardware.org/?probe=19c2a17ec5) | Apr 27, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [cde129cf45](https://linux-hardware.org/?probe=cde129cf45) | Apr 26, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [add3c03eef](https://linux-hardware.org/?probe=add3c03eef) | Apr 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9824006277](https://linux-hardware.org/?probe=9824006277) | Apr 26, 2023 |
| HP            | 18E7                        | Desktop     | [26ca79a633](https://linux-hardware.org/?probe=26ca79a633) | Apr 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [856de630ec](https://linux-hardware.org/?probe=856de630ec) | Apr 25, 2023 |
| System76      | Oryx Pro                    | Notebook    | [298bf97b70](https://linux-hardware.org/?probe=298bf97b70) | Apr 25, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [962bffed9f](https://linux-hardware.org/?probe=962bffed9f) | Apr 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a2c2f1f536](https://linux-hardware.org/?probe=a2c2f1f536) | Apr 25, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [c897ecd954](https://linux-hardware.org/?probe=c897ecd954) | Apr 25, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [90fa428095](https://linux-hardware.org/?probe=90fa428095) | Apr 25, 2023 |
| ZOTAC         | ZBOX-CI527/CI547NANO        | Mini pc     | [97f86da425](https://linux-hardware.org/?probe=97f86da425) | Apr 25, 2023 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [8a600077f6](https://linux-hardware.org/?probe=8a600077f6) | Apr 25, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [42908a7ab7](https://linux-hardware.org/?probe=42908a7ab7) | Apr 25, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [cb64c7f963](https://linux-hardware.org/?probe=cb64c7f963) | Apr 25, 2023 |
| ASRock        | Z690 Extreme                | Desktop     | [3767d30290](https://linux-hardware.org/?probe=3767d30290) | Apr 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [df85ceaa6b](https://linux-hardware.org/?probe=df85ceaa6b) | Apr 24, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [6a6beb844d](https://linux-hardware.org/?probe=6a6beb844d) | Apr 23, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [66d61baf71](https://linux-hardware.org/?probe=66d61baf71) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [03bcaf6334](https://linux-hardware.org/?probe=03bcaf6334) | Apr 21, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [5b14b21a19](https://linux-hardware.org/?probe=5b14b21a19) | Apr 21, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [7641434e4d](https://linux-hardware.org/?probe=7641434e4d) | Apr 21, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [4e69a80310](https://linux-hardware.org/?probe=4e69a80310) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [880ee85934](https://linux-hardware.org/?probe=880ee85934) | Apr 21, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [d48ffa8191](https://linux-hardware.org/?probe=d48ffa8191) | Apr 21, 2023 |
| Packard Be... | EasyNote TSX62HR            | Notebook    | [7e7dbc9acd](https://linux-hardware.org/?probe=7e7dbc9acd) | Apr 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c10e38e18e](https://linux-hardware.org/?probe=c10e38e18e) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [2afe988f2e](https://linux-hardware.org/?probe=2afe988f2e) | Apr 20, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [8e02f43636](https://linux-hardware.org/?probe=8e02f43636) | Apr 20, 2023 |
| Acer          | Predator G9-793             | Notebook    | [664d6de816](https://linux-hardware.org/?probe=664d6de816) | Apr 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d8025962bf](https://linux-hardware.org/?probe=d8025962bf) | Apr 20, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [46ade409df](https://linux-hardware.org/?probe=46ade409df) | Apr 20, 2023 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [bebc7ec91b](https://linux-hardware.org/?probe=bebc7ec91b) | Apr 19, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ec0b554256](https://linux-hardware.org/?probe=ec0b554256) | Apr 19, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [fdb308cd9f](https://linux-hardware.org/?probe=fdb308cd9f) | Apr 19, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [6cf066b06b](https://linux-hardware.org/?probe=6cf066b06b) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [618b59dac2](https://linux-hardware.org/?probe=618b59dac2) | Apr 19, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [954388c5e0](https://linux-hardware.org/?probe=954388c5e0) | Apr 19, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [e3ebb38e6b](https://linux-hardware.org/?probe=e3ebb38e6b) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4185aada87](https://linux-hardware.org/?probe=4185aada87) | Apr 19, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [512bad7a33](https://linux-hardware.org/?probe=512bad7a33) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [323dc7fa4b](https://linux-hardware.org/?probe=323dc7fa4b) | Apr 18, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [10bfabc1b8](https://linux-hardware.org/?probe=10bfabc1b8) | Apr 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6ce11cef12](https://linux-hardware.org/?probe=6ce11cef12) | Apr 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [efdcb6b99e](https://linux-hardware.org/?probe=efdcb6b99e) | Apr 18, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [3decfdc1f6](https://linux-hardware.org/?probe=3decfdc1f6) | Apr 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3738d57a9c](https://linux-hardware.org/?probe=3738d57a9c) | Apr 15, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [6f8dbb2e8e](https://linux-hardware.org/?probe=6f8dbb2e8e) | Apr 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [2e6b5600aa](https://linux-hardware.org/?probe=2e6b5600aa) | Apr 14, 2023 |
| Dell          | Latitude 3590               | Notebook    | [eed6f4df10](https://linux-hardware.org/?probe=eed6f4df10) | Apr 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [615a9d3871](https://linux-hardware.org/?probe=615a9d3871) | Apr 12, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ef5829077e](https://linux-hardware.org/?probe=ef5829077e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e0e2242a64](https://linux-hardware.org/?probe=e0e2242a64) | Apr 11, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | Desktop     | [415b7ce80b](https://linux-hardware.org/?probe=415b7ce80b) | Apr 10, 2023 |
| BESSTAR Te... | HX90                        | Desktop     | [2639d597e8](https://linux-hardware.org/?probe=2639d597e8) | Apr 10, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fa729987de](https://linux-hardware.org/?probe=fa729987de) | Apr 09, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [ca9fe9c7f1](https://linux-hardware.org/?probe=ca9fe9c7f1) | Apr 09, 2023 |
| HP            | ENVY 15                     | Notebook    | [5ecc7b36c8](https://linux-hardware.org/?probe=5ecc7b36c8) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c2e1cb3f46](https://linux-hardware.org/?probe=c2e1cb3f46) | Apr 09, 2023 |
| ASUSTek       | Zenbook UX7602ZM            | Notebook    | [aeded4c133](https://linux-hardware.org/?probe=aeded4c133) | Apr 08, 2023 |
| HP            | Pavilion dv4                | Notebook    | [a554538ed8](https://linux-hardware.org/?probe=a554538ed8) | Apr 07, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [2acb260eb1](https://linux-hardware.org/?probe=2acb260eb1) | Apr 07, 2023 |
| ASUSTek       | K54C                        | Notebook    | [4f37849c94](https://linux-hardware.org/?probe=4f37849c94) | Apr 07, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [cd157a6ebf](https://linux-hardware.org/?probe=cd157a6ebf) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [00fef3bb7b](https://linux-hardware.org/?probe=00fef3bb7b) | Apr 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [ebc3f9d008](https://linux-hardware.org/?probe=ebc3f9d008) | Apr 06, 2023 |
| HP            | Pavilion dv7                | Notebook    | [bdb5d286b5](https://linux-hardware.org/?probe=bdb5d286b5) | Apr 06, 2023 |
| Dell          | Latitude 3510               | Notebook    | [e927d04a2d](https://linux-hardware.org/?probe=e927d04a2d) | Apr 06, 2023 |
| Biostar       | TZ77B                       | Desktop     | [c5d5603dc4](https://linux-hardware.org/?probe=c5d5603dc4) | Apr 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b9e77efbb1](https://linux-hardware.org/?probe=b9e77efbb1) | Apr 05, 2023 |
| Shenzhen W... | GB1                         | Mini pc     | [ca02164e4d](https://linux-hardware.org/?probe=ca02164e4d) | Apr 01, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6eb533f1d7](https://linux-hardware.org/?probe=6eb533f1d7) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [2cc7a15de5](https://linux-hardware.org/?probe=2cc7a15de5) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490s 20NXS0DS0... | Notebook    | [1228998af5](https://linux-hardware.org/?probe=1228998af5) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [0ff3ab318e](https://linux-hardware.org/?probe=0ff3ab318e) | Mar 31, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [dbe7f7ac9b](https://linux-hardware.org/?probe=dbe7f7ac9b) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [09679af7dc](https://linux-hardware.org/?probe=09679af7dc) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e78d2454c](https://linux-hardware.org/?probe=1e78d2454c) | Mar 31, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [01492665ee](https://linux-hardware.org/?probe=01492665ee) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0b4fae8189](https://linux-hardware.org/?probe=0b4fae8189) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [13acfd725a](https://linux-hardware.org/?probe=13acfd725a) | Mar 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [514d8ed8d6](https://linux-hardware.org/?probe=514d8ed8d6) | Mar 30, 2023 |
| HP            | 8399                        | Desktop     | [d8c0ad05f5](https://linux-hardware.org/?probe=d8c0ad05f5) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a1d2ac5e6e](https://linux-hardware.org/?probe=a1d2ac5e6e) | Mar 30, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [7554f35f1d](https://linux-hardware.org/?probe=7554f35f1d) | Mar 30, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [8808e457a1](https://linux-hardware.org/?probe=8808e457a1) | Mar 29, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [2f1975360e](https://linux-hardware.org/?probe=2f1975360e) | Mar 28, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [5ac9dd16da](https://linux-hardware.org/?probe=5ac9dd16da) | Mar 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [4ac3cde372](https://linux-hardware.org/?probe=4ac3cde372) | Mar 27, 2023 |
| Dell          | 0W2F8G A02                  | Desktop     | [511510b501](https://linux-hardware.org/?probe=511510b501) | Mar 27, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [b960038661](https://linux-hardware.org/?probe=b960038661) | Mar 27, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [39802560c1](https://linux-hardware.org/?probe=39802560c1) | Mar 27, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [af90cee242](https://linux-hardware.org/?probe=af90cee242) | Mar 27, 2023 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [da016d15c7](https://linux-hardware.org/?probe=da016d15c7) | Mar 27, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [1ed601999d](https://linux-hardware.org/?probe=1ed601999d) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [1988691e71](https://linux-hardware.org/?probe=1988691e71) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [dd081eb573](https://linux-hardware.org/?probe=dd081eb573) | Mar 27, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [f1ed5dd70d](https://linux-hardware.org/?probe=f1ed5dd70d) | Mar 26, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [6ac498fa82](https://linux-hardware.org/?probe=6ac498fa82) | Mar 26, 2023 |
| Toshiba       | Satellite C50-A510          | Notebook    | [69eb2dad8f](https://linux-hardware.org/?probe=69eb2dad8f) | Mar 26, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [7c10ad8eb9](https://linux-hardware.org/?probe=7c10ad8eb9) | Mar 26, 2023 |
| MSI           | GT70                        | Notebook    | [8b00b28b12](https://linux-hardware.org/?probe=8b00b28b12) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [fe5c568f41](https://linux-hardware.org/?probe=fe5c568f41) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [22e7978cc8](https://linux-hardware.org/?probe=22e7978cc8) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [778f5948f1](https://linux-hardware.org/?probe=778f5948f1) | Mar 26, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [3772f7397b](https://linux-hardware.org/?probe=3772f7397b) | Mar 26, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [915cac124b](https://linux-hardware.org/?probe=915cac124b) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [f889f2ddf5](https://linux-hardware.org/?probe=f889f2ddf5) | Mar 26, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [513b14ace5](https://linux-hardware.org/?probe=513b14ace5) | Mar 25, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [9d9e4e184f](https://linux-hardware.org/?probe=9d9e4e184f) | Mar 25, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [6c4d5eee3f](https://linux-hardware.org/?probe=6c4d5eee3f) | Mar 25, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [765602e7bf](https://linux-hardware.org/?probe=765602e7bf) | Mar 24, 2023 |
| MSI           | A320M-HDV R4.0              | Desktop     | [a04e0acbcf](https://linux-hardware.org/?probe=a04e0acbcf) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [5b6af55009](https://linux-hardware.org/?probe=5b6af55009) | Mar 23, 2023 |
| HP            | 828A                        | Desktop     | [cce5214801](https://linux-hardware.org/?probe=cce5214801) | Mar 22, 2023 |
| Lenovo        | ThinkPad Edge S430 33643... | Notebook    | [f6b05c3b0b](https://linux-hardware.org/?probe=f6b05c3b0b) | Mar 21, 2023 |
| System76      | Oryx Pro                    | Notebook    | [b784685da3](https://linux-hardware.org/?probe=b784685da3) | Mar 21, 2023 |
| System76      | Pangolin                    | Notebook    | [ee7dd00fbf](https://linux-hardware.org/?probe=ee7dd00fbf) | Mar 19, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7c770db7fd](https://linux-hardware.org/?probe=7c770db7fd) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [49df72f291](https://linux-hardware.org/?probe=49df72f291) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [1f939ee045](https://linux-hardware.org/?probe=1f939ee045) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [5e6e5276e3](https://linux-hardware.org/?probe=5e6e5276e3) | Mar 18, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [e9d0a5dd9a](https://linux-hardware.org/?probe=e9d0a5dd9a) | Mar 18, 2023 |
| HP            | 18E8                        | Desktop     | [bf7c3c9080](https://linux-hardware.org/?probe=bf7c3c9080) | Mar 18, 2023 |
| Dell          | Latitude 3410               | Notebook    | [8c71ef60d0](https://linux-hardware.org/?probe=8c71ef60d0) | Mar 18, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd3a3e64c](https://linux-hardware.org/?probe=7bd3a3e64c) | Mar 18, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8681f176da](https://linux-hardware.org/?probe=8681f176da) | Mar 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [70a1f8041b](https://linux-hardware.org/?probe=70a1f8041b) | Mar 17, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [593bd6b3ac](https://linux-hardware.org/?probe=593bd6b3ac) | Mar 17, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [42391e1ac6](https://linux-hardware.org/?probe=42391e1ac6) | Mar 16, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7630033ffb](https://linux-hardware.org/?probe=7630033ffb) | Mar 15, 2023 |
| Lenovo        | 36EB NOK                    | Desktop     | [b6d8243d49](https://linux-hardware.org/?probe=b6d8243d49) | Mar 15, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [60bd2eeae4](https://linux-hardware.org/?probe=60bd2eeae4) | Mar 15, 2023 |
| HP            | 828A                        | Desktop     | [9d6df1b56e](https://linux-hardware.org/?probe=9d6df1b56e) | Mar 15, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [77b68431f7](https://linux-hardware.org/?probe=77b68431f7) | Mar 14, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [b94932937e](https://linux-hardware.org/?probe=b94932937e) | Mar 14, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [54d17115b9](https://linux-hardware.org/?probe=54d17115b9) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [79932e56ad](https://linux-hardware.org/?probe=79932e56ad) | Mar 13, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [1de50d9986](https://linux-hardware.org/?probe=1de50d9986) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [ff9cb78f74](https://linux-hardware.org/?probe=ff9cb78f74) | Mar 13, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b17210218f](https://linux-hardware.org/?probe=b17210218f) | Mar 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [1fc9174c06](https://linux-hardware.org/?probe=1fc9174c06) | Mar 11, 2023 |
| Dell          | Inspiron 5420               | Notebook    | [9e6843fe2e](https://linux-hardware.org/?probe=9e6843fe2e) | Mar 10, 2023 |
| Dell          | Inspiron 5420               | Notebook    | [77d13c9c12](https://linux-hardware.org/?probe=77d13c9c12) | Mar 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [dd06fbb0f9](https://linux-hardware.org/?probe=dd06fbb0f9) | Mar 10, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [bdf01893f8](https://linux-hardware.org/?probe=bdf01893f8) | Mar 10, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [23a97367b7](https://linux-hardware.org/?probe=23a97367b7) | Mar 09, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [b46bb47333](https://linux-hardware.org/?probe=b46bb47333) | Mar 09, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [24444c6d30](https://linux-hardware.org/?probe=24444c6d30) | Mar 08, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [f500d72edd](https://linux-hardware.org/?probe=f500d72edd) | Mar 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [42e5be35d6](https://linux-hardware.org/?probe=42e5be35d6) | Mar 08, 2023 |
| HP            | 8055                        | Desktop     | [0b9ddd5940](https://linux-hardware.org/?probe=0b9ddd5940) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4d15122995](https://linux-hardware.org/?probe=4d15122995) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc6e719e99](https://linux-hardware.org/?probe=cc6e719e99) | Mar 07, 2023 |
| Huanan        | X79-ZD3 INTEL (INTEL Xeo... | Desktop     | [0e00a19a03](https://linux-hardware.org/?probe=0e00a19a03) | Mar 07, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [676eaa7960](https://linux-hardware.org/?probe=676eaa7960) | Mar 06, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8f08518290](https://linux-hardware.org/?probe=8f08518290) | Mar 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [819f8b1cad](https://linux-hardware.org/?probe=819f8b1cad) | Mar 06, 2023 |
| Dell          | G7 7500                     | Notebook    | [d5abfa6d0d](https://linux-hardware.org/?probe=d5abfa6d0d) | Mar 06, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [a6c7741454](https://linux-hardware.org/?probe=a6c7741454) | Mar 06, 2023 |
| Dell          | G7 7500                     | Notebook    | [bfaad602b7](https://linux-hardware.org/?probe=bfaad602b7) | Mar 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8814af9b71](https://linux-hardware.org/?probe=8814af9b71) | Mar 05, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [e560390e4f](https://linux-hardware.org/?probe=e560390e4f) | Mar 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3d1560d3d1](https://linux-hardware.org/?probe=3d1560d3d1) | Mar 05, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c2f98c3014](https://linux-hardware.org/?probe=c2f98c3014) | Mar 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [3e484b7bac](https://linux-hardware.org/?probe=3e484b7bac) | Mar 04, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f163816260](https://linux-hardware.org/?probe=f163816260) | Mar 04, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [5523730c91](https://linux-hardware.org/?probe=5523730c91) | Mar 04, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [422fa2cf16](https://linux-hardware.org/?probe=422fa2cf16) | Mar 02, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [f441cc82e4](https://linux-hardware.org/?probe=f441cc82e4) | Mar 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [edf5f00bf8](https://linux-hardware.org/?probe=edf5f00bf8) | Mar 01, 2023 |
| Sony          | VPCEH10EB                   | Notebook    | [9c8bb09559](https://linux-hardware.org/?probe=9c8bb09559) | Mar 01, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [eca37862f3](https://linux-hardware.org/?probe=eca37862f3) | Mar 01, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [ecdef0f6db](https://linux-hardware.org/?probe=ecdef0f6db) | Mar 01, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [6bd63e7974](https://linux-hardware.org/?probe=6bd63e7974) | Mar 01, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [4f2c05c854](https://linux-hardware.org/?probe=4f2c05c854) | Feb 28, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [db5b346bd5](https://linux-hardware.org/?probe=db5b346bd5) | Feb 28, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [166a6bbb4b](https://linux-hardware.org/?probe=166a6bbb4b) | Feb 28, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [dd74cb518b](https://linux-hardware.org/?probe=dd74cb518b) | Feb 27, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [677e93841e](https://linux-hardware.org/?probe=677e93841e) | Feb 27, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [068ad292bd](https://linux-hardware.org/?probe=068ad292bd) | Feb 27, 2023 |
| Gigabyte      | X99-UD4P-CF                 | Desktop     | [b78a53985a](https://linux-hardware.org/?probe=b78a53985a) | Feb 26, 2023 |
| MSI           | Z97-G43 GAMING              | Desktop     | [b13f16cb2f](https://linux-hardware.org/?probe=b13f16cb2f) | Feb 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [267da4138c](https://linux-hardware.org/?probe=267da4138c) | Feb 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [de7aec7f12](https://linux-hardware.org/?probe=de7aec7f12) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8a2a361aff](https://linux-hardware.org/?probe=8a2a361aff) | Feb 26, 2023 |
| Lenovo        | ThinkPad L470 20J4003WGE    | Notebook    | [42f6425b2d](https://linux-hardware.org/?probe=42f6425b2d) | Feb 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS35H02    | Notebook    | [a396e54378](https://linux-hardware.org/?probe=a396e54378) | Feb 25, 2023 |
| Gigabyte      | B85N PHOENIX                | Desktop     | [5fe00f35c4](https://linux-hardware.org/?probe=5fe00f35c4) | Feb 25, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [31bd9738ca](https://linux-hardware.org/?probe=31bd9738ca) | Feb 25, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [4066713adb](https://linux-hardware.org/?probe=4066713adb) | Feb 24, 2023 |
| Dell          | 0MM599                      | Desktop     | [00304aefe6](https://linux-hardware.org/?probe=00304aefe6) | Feb 24, 2023 |
| AZW           | GTR V02                     | Desktop     | [c8d4bfd6e3](https://linux-hardware.org/?probe=c8d4bfd6e3) | Feb 23, 2023 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [e60b570c27](https://linux-hardware.org/?probe=e60b570c27) | Feb 23, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [950130a7b4](https://linux-hardware.org/?probe=950130a7b4) | Feb 23, 2023 |
| Lenovo        | 36EB NOK                    | Desktop     | [019ad99dd4](https://linux-hardware.org/?probe=019ad99dd4) | Feb 22, 2023 |
| ASUSTek       | X55VD                       | Notebook    | [6b71d8369a](https://linux-hardware.org/?probe=6b71d8369a) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming H670-PRO WIFI... | Desktop     | [d8b3285c55](https://linux-hardware.org/?probe=d8b3285c55) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [65f3a9d691](https://linux-hardware.org/?probe=65f3a9d691) | Feb 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [88be67bbc1](https://linux-hardware.org/?probe=88be67bbc1) | Feb 21, 2023 |
| Dell          | 0RN4PJ A01                  | Server      | [0c272543ed](https://linux-hardware.org/?probe=0c272543ed) | Feb 21, 2023 |
| MSI           | Z77A-GD65                   | Desktop     | [b5aebe4c92](https://linux-hardware.org/?probe=b5aebe4c92) | Feb 21, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [accbe9322f](https://linux-hardware.org/?probe=accbe9322f) | Feb 20, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f8a26128a4](https://linux-hardware.org/?probe=f8a26128a4) | Feb 20, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [28a0794b08](https://linux-hardware.org/?probe=28a0794b08) | Feb 20, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e87f489185](https://linux-hardware.org/?probe=e87f489185) | Feb 20, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [6f65703034](https://linux-hardware.org/?probe=6f65703034) | Feb 19, 2023 |
| HP            | ENVY 15                     | Notebook    | [7d53c3db41](https://linux-hardware.org/?probe=7d53c3db41) | Feb 19, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [1263eaf1f9](https://linux-hardware.org/?probe=1263eaf1f9) | Feb 19, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [2b1fc8eb09](https://linux-hardware.org/?probe=2b1fc8eb09) | Feb 19, 2023 |
| HP            | 8053                        | Desktop     | [e495e287bc](https://linux-hardware.org/?probe=e495e287bc) | Feb 18, 2023 |
| HP            | ENVY 15                     | Notebook    | [e59ac2cec0](https://linux-hardware.org/?probe=e59ac2cec0) | Feb 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [af76238a5c](https://linux-hardware.org/?probe=af76238a5c) | Feb 17, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [af86e6cb72](https://linux-hardware.org/?probe=af86e6cb72) | Feb 17, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [f36e84dcaf](https://linux-hardware.org/?probe=f36e84dcaf) | Feb 16, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [2cb0dc3d69](https://linux-hardware.org/?probe=2cb0dc3d69) | Feb 13, 2023 |
| ASRock        | Z690 Steel Legend           | Desktop     | [6935bc6a6e](https://linux-hardware.org/?probe=6935bc6a6e) | Feb 13, 2023 |
| Intel         | NUC7i3BNB J22859-316        | Mini pc     | [fc5fbe9d48](https://linux-hardware.org/?probe=fc5fbe9d48) | Feb 13, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [abe1e578c0](https://linux-hardware.org/?probe=abe1e578c0) | Feb 12, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [480da10129](https://linux-hardware.org/?probe=480da10129) | Feb 12, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [cbf6311f2c](https://linux-hardware.org/?probe=cbf6311f2c) | Feb 12, 2023 |
| Lenovo        | Yoga 720-12IKB 81B5         | Convertible | [fdbc3256cf](https://linux-hardware.org/?probe=fdbc3256cf) | Feb 12, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [19547b9a43](https://linux-hardware.org/?probe=19547b9a43) | Feb 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4344acac5e](https://linux-hardware.org/?probe=4344acac5e) | Feb 11, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [6047c68386](https://linux-hardware.org/?probe=6047c68386) | Feb 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e4340c10db](https://linux-hardware.org/?probe=e4340c10db) | Feb 10, 2023 |
| System76      | Oryx Pro                    | Notebook    | [20fad7d628](https://linux-hardware.org/?probe=20fad7d628) | Feb 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2f694f36cc](https://linux-hardware.org/?probe=2f694f36cc) | Feb 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a545753206](https://linux-hardware.org/?probe=a545753206) | Feb 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c7de2e3ca2](https://linux-hardware.org/?probe=c7de2e3ca2) | Feb 10, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [a60a4191b8](https://linux-hardware.org/?probe=a60a4191b8) | Feb 10, 2023 |
| Toshiba       | Satellite L70-B             | Notebook    | [f47ccc62c7](https://linux-hardware.org/?probe=f47ccc62c7) | Feb 09, 2023 |
| Toshiba       | Satellite L70-B             | Notebook    | [68ba5288c0](https://linux-hardware.org/?probe=68ba5288c0) | Feb 09, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [d68fb933eb](https://linux-hardware.org/?probe=d68fb933eb) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [5fe8eef781](https://linux-hardware.org/?probe=5fe8eef781) | Feb 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [47c66d7783](https://linux-hardware.org/?probe=47c66d7783) | Feb 08, 2023 |
| Quanta        | 2AF5 011                    | Desktop     | [e62b8a3165](https://linux-hardware.org/?probe=e62b8a3165) | Feb 07, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [420ccdfca6](https://linux-hardware.org/?probe=420ccdfca6) | Feb 07, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [2d40451b53](https://linux-hardware.org/?probe=2d40451b53) | Feb 06, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [a865465884](https://linux-hardware.org/?probe=a865465884) | Feb 04, 2023 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [a41f5126d3](https://linux-hardware.org/?probe=a41f5126d3) | Feb 04, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [a4b17f9deb](https://linux-hardware.org/?probe=a4b17f9deb) | Feb 04, 2023 |
| Unknown       | HX90                        | Desktop     | [60ade05817](https://linux-hardware.org/?probe=60ade05817) | Feb 03, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [395e2c6424](https://linux-hardware.org/?probe=395e2c6424) | Feb 03, 2023 |
| Monster       | TULPAR T5 V20.1             | Notebook    | [b224ac6a46](https://linux-hardware.org/?probe=b224ac6a46) | Feb 03, 2023 |
| Acer          | WMCP78M                     | Desktop     | [cd9dccabaf](https://linux-hardware.org/?probe=cd9dccabaf) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [62d193dd49](https://linux-hardware.org/?probe=62d193dd49) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [181cdf6a58](https://linux-hardware.org/?probe=181cdf6a58) | Feb 03, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [de152b340c](https://linux-hardware.org/?probe=de152b340c) | Feb 01, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [a2ff80e7dd](https://linux-hardware.org/?probe=a2ff80e7dd) | Feb 01, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [d7b81788e7](https://linux-hardware.org/?probe=d7b81788e7) | Feb 01, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5abc8dccdb](https://linux-hardware.org/?probe=5abc8dccdb) | Jan 31, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3aaad3b44c](https://linux-hardware.org/?probe=3aaad3b44c) | Jan 29, 2023 |
| SYWZ          | S210H Series                | Desktop     | [4d1018a808](https://linux-hardware.org/?probe=4d1018a808) | Jan 29, 2023 |
| HP            | 8053                        | Desktop     | [88120ce3f4](https://linux-hardware.org/?probe=88120ce3f4) | Jan 28, 2023 |
| MSI           | Raider GE76 12UHS           | Notebook    | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [2cf59bd38d](https://linux-hardware.org/?probe=2cf59bd38d) | Jan 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [85ad9c7e62](https://linux-hardware.org/?probe=85ad9c7e62) | Jan 25, 2023 |
| HP            | Folio 13                    | Notebook    | [214197bef4](https://linux-hardware.org/?probe=214197bef4) | Jan 25, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [a95489f0b7](https://linux-hardware.org/?probe=a95489f0b7) | Jan 24, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [5b2fd24ed7](https://linux-hardware.org/?probe=5b2fd24ed7) | Jan 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [3c2d563718](https://linux-hardware.org/?probe=3c2d563718) | Jan 23, 2023 |
| Dell          | Inspiron 7472               | Notebook    | [6395ea422c](https://linux-hardware.org/?probe=6395ea422c) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [d0f4730f71](https://linux-hardware.org/?probe=d0f4730f71) | Jan 23, 2023 |
| HP            | 8750                        | Desktop     | [e8b02ffbb5](https://linux-hardware.org/?probe=e8b02ffbb5) | Jan 23, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [66287c2f72](https://linux-hardware.org/?probe=66287c2f72) | Jan 22, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [369b022d8e](https://linux-hardware.org/?probe=369b022d8e) | Jan 22, 2023 |
| Timi          | TM1701                      | Notebook    | [bec2d3a691](https://linux-hardware.org/?probe=bec2d3a691) | Jan 22, 2023 |
| Dell          | Latitude E5400              | Notebook    | [ee6e466820](https://linux-hardware.org/?probe=ee6e466820) | Jan 22, 2023 |
| Dell          | Latitude E5400              | Notebook    | [f61d1e0868](https://linux-hardware.org/?probe=f61d1e0868) | Jan 22, 2023 |
| Dell          | Latitude 7480               | Notebook    | [0d4396d043](https://linux-hardware.org/?probe=0d4396d043) | Jan 21, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [ae81429a64](https://linux-hardware.org/?probe=ae81429a64) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [00d43f76e1](https://linux-hardware.org/?probe=00d43f76e1) | Jan 21, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [560159c251](https://linux-hardware.org/?probe=560159c251) | Jan 21, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [be0b035640](https://linux-hardware.org/?probe=be0b035640) | Jan 20, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [acf0fd5893](https://linux-hardware.org/?probe=acf0fd5893) | Jan 20, 2023 |
| MSI           | GL65 Leopard 10SFK          | Notebook    | [8aa69f1dae](https://linux-hardware.org/?probe=8aa69f1dae) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [09dbcb3ae4](https://linux-hardware.org/?probe=09dbcb3ae4) | Jan 20, 2023 |
| MSI           | GL65 Leopard 10SFK          | Notebook    | [0ea710bda6](https://linux-hardware.org/?probe=0ea710bda6) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [a929c23a1b](https://linux-hardware.org/?probe=a929c23a1b) | Jan 20, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [0f21d67175](https://linux-hardware.org/?probe=0f21d67175) | Jan 20, 2023 |
| Acer          | Predator G3-710             | Desktop     | [c7f97640a5](https://linux-hardware.org/?probe=c7f97640a5) | Jan 19, 2023 |
| AZW           | GTR V02                     | Desktop     | [524948189b](https://linux-hardware.org/?probe=524948189b) | Jan 19, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [b6a8598370](https://linux-hardware.org/?probe=b6a8598370) | Jan 19, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [68d2fcbdcf](https://linux-hardware.org/?probe=68d2fcbdcf) | Jan 18, 2023 |
| Alienware     | M17xR4                      | Notebook    | [5cce1e5932](https://linux-hardware.org/?probe=5cce1e5932) | Jan 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [e221c08388](https://linux-hardware.org/?probe=e221c08388) | Jan 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [d2bb65ed09](https://linux-hardware.org/?probe=d2bb65ed09) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [0306622813](https://linux-hardware.org/?probe=0306622813) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [84edd23a21](https://linux-hardware.org/?probe=84edd23a21) | Jan 18, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [8e4a061e95](https://linux-hardware.org/?probe=8e4a061e95) | Jan 16, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [60a0157a51](https://linux-hardware.org/?probe=60a0157a51) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [6643ab6cf1](https://linux-hardware.org/?probe=6643ab6cf1) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [91fed2c125](https://linux-hardware.org/?probe=91fed2c125) | Jan 16, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [37d6076330](https://linux-hardware.org/?probe=37d6076330) | Jan 15, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9fe6c51640](https://linux-hardware.org/?probe=9fe6c51640) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [d569a3f698](https://linux-hardware.org/?probe=d569a3f698) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [2141789e3a](https://linux-hardware.org/?probe=2141789e3a) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | Notebook    | [0ece2f508b](https://linux-hardware.org/?probe=0ece2f508b) | Jan 14, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [dd5156dd62](https://linux-hardware.org/?probe=dd5156dd62) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4f439c171e](https://linux-hardware.org/?probe=4f439c171e) | Jan 14, 2023 |
| HP            | 886C                        | Desktop     | [3f75def118](https://linux-hardware.org/?probe=3f75def118) | Jan 13, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [f34e2c982f](https://linux-hardware.org/?probe=f34e2c982f) | Jan 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e275cc7891](https://linux-hardware.org/?probe=e275cc7891) | Jan 13, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [5e5d5428a3](https://linux-hardware.org/?probe=5e5d5428a3) | Jan 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7c62282370](https://linux-hardware.org/?probe=7c62282370) | Jan 12, 2023 |
| AZW           | GTR V02                     | Desktop     | [cde45335ab](https://linux-hardware.org/?probe=cde45335ab) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [2dadad3f74](https://linux-hardware.org/?probe=2dadad3f74) | Jan 12, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | Notebook    | [d859e0ff10](https://linux-hardware.org/?probe=d859e0ff10) | Jan 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [71c61d98b9](https://linux-hardware.org/?probe=71c61d98b9) | Jan 10, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [4e7660a1e0](https://linux-hardware.org/?probe=4e7660a1e0) | Jan 10, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [a786384700](https://linux-hardware.org/?probe=a786384700) | Jan 10, 2023 |
| HP            | ENVY Notebook               | Notebook    | [ff8cd12017](https://linux-hardware.org/?probe=ff8cd12017) | Jan 10, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [787c4388c8](https://linux-hardware.org/?probe=787c4388c8) | Jan 09, 2023 |
| System76      | Oryx Pro                    | Notebook    | [e3f5a24a6e](https://linux-hardware.org/?probe=e3f5a24a6e) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [46ae333889](https://linux-hardware.org/?probe=46ae333889) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [2923dcfe6f](https://linux-hardware.org/?probe=2923dcfe6f) | Jan 09, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [bdc427771d](https://linux-hardware.org/?probe=bdc427771d) | Jan 08, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [ebf4546adf](https://linux-hardware.org/?probe=ebf4546adf) | Jan 08, 2023 |
| HP            | 2B2C                        | Desktop     | [1a74d92aaf](https://linux-hardware.org/?probe=1a74d92aaf) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6f2c3e2284](https://linux-hardware.org/?probe=6f2c3e2284) | Jan 08, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [16c789a53c](https://linux-hardware.org/?probe=16c789a53c) | Jan 07, 2023 |
| Dell          | Precision M3800             | Notebook    | [ca9cfa3f5a](https://linux-hardware.org/?probe=ca9cfa3f5a) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ef473bb212](https://linux-hardware.org/?probe=ef473bb212) | Jan 07, 2023 |
| Dell          | Precision M3800             | Notebook    | [454d4b6b55](https://linux-hardware.org/?probe=454d4b6b55) | Jan 07, 2023 |
| Acer          | Predator G9-793             | Notebook    | [5256ec6943](https://linux-hardware.org/?probe=5256ec6943) | Jan 07, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [a7fbae334f](https://linux-hardware.org/?probe=a7fbae334f) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [e9f54fc1f0](https://linux-hardware.org/?probe=e9f54fc1f0) | Jan 07, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [67b5b9902a](https://linux-hardware.org/?probe=67b5b9902a) | Jan 06, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [7281c172f4](https://linux-hardware.org/?probe=7281c172f4) | Jan 06, 2023 |
| Gigabyte      | P55-USB3                    | Desktop     | [7c741c709a](https://linux-hardware.org/?probe=7c741c709a) | Jan 06, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [74859544a4](https://linux-hardware.org/?probe=74859544a4) | Jan 06, 2023 |
| MSI           | A320M-HDV R4.0              | Desktop     | [922a46c59e](https://linux-hardware.org/?probe=922a46c59e) | Jan 06, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [42ee9415a1](https://linux-hardware.org/?probe=42ee9415a1) | Jan 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b345c4d626](https://linux-hardware.org/?probe=b345c4d626) | Jan 06, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [9320df061f](https://linux-hardware.org/?probe=9320df061f) | Jan 06, 2023 |
| System76      | Pangolin                    | Notebook    | [823d50a20f](https://linux-hardware.org/?probe=823d50a20f) | Jan 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [458cb8c4de](https://linux-hardware.org/?probe=458cb8c4de) | Jan 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a84d0d7b42](https://linux-hardware.org/?probe=a84d0d7b42) | Jan 06, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [8027cc9eeb](https://linux-hardware.org/?probe=8027cc9eeb) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [113e1b51b7](https://linux-hardware.org/?probe=113e1b51b7) | Jan 04, 2023 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [e6028c8640](https://linux-hardware.org/?probe=e6028c8640) | Jan 04, 2023 |
| HP            | ENVY 15                     | Notebook    | [e91c6321b3](https://linux-hardware.org/?probe=e91c6321b3) | Jan 04, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | Notebook    | [23bfcb7f4c](https://linux-hardware.org/?probe=23bfcb7f4c) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [2ede2771be](https://linux-hardware.org/?probe=2ede2771be) | Jan 03, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | Notebook    | [9ba40bc6b5](https://linux-hardware.org/?probe=9ba40bc6b5) | Jan 03, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [b55d0dfc1e](https://linux-hardware.org/?probe=b55d0dfc1e) | Jan 03, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [2ec9ac6337](https://linux-hardware.org/?probe=2ec9ac6337) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [893d1002f6](https://linux-hardware.org/?probe=893d1002f6) | Jan 02, 2023 |
| Dell          | Precision 7740              | Notebook    | [952da37737](https://linux-hardware.org/?probe=952da37737) | Jan 02, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [0229b8166f](https://linux-hardware.org/?probe=0229b8166f) | Jan 02, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | Notebook    | [31a0bdb593](https://linux-hardware.org/?probe=31a0bdb593) | Jan 02, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [5749628668](https://linux-hardware.org/?probe=5749628668) | Jan 01, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [63adf72d53](https://linux-hardware.org/?probe=63adf72d53) | Jan 01, 2023 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [56e961b0ca](https://linux-hardware.org/?probe=56e961b0ca) | Jan 01, 2023 |
| HP            | Folio 13                    | Notebook    | [9f00cfe432](https://linux-hardware.org/?probe=9f00cfe432) | Dec 31, 2022 |
| HP            | Folio 13                    | Notebook    | [3ed5b405cb](https://linux-hardware.org/?probe=3ed5b405cb) | Dec 31, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [bdd6f3912d](https://linux-hardware.org/?probe=bdd6f3912d) | Dec 30, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [056ae8185c](https://linux-hardware.org/?probe=056ae8185c) | Dec 30, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [6cf8d26754](https://linux-hardware.org/?probe=6cf8d26754) | Dec 30, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [33fd3ed258](https://linux-hardware.org/?probe=33fd3ed258) | Dec 29, 2022 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [9613dfc76b](https://linux-hardware.org/?probe=9613dfc76b) | Dec 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ArcoLinux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ArcoLinux Rolling     | 1857      | 90.9%   |
| ArcoLinux             | 138       | 6.75%   |
| ArcoLinux 20.6.5      | 11        | 0.54%   |
| ArcoLinux 20.7.5      | 8         | 0.39%   |
| ArcoLinux 20.3.4      | 4         | 0.2%    |
| ArcoLinux 20.3.3      | 3         | 0.15%   |
| ArcoLinux 20.2.12     | 3         | 0.15%   |
| ArcoLinux 19.12.15    | 3         | 0.15%   |
| ArcoLinux 19.07.11    | 3         | 0.15%   |
| ArcoLinux 20.1.4      | 2         | 0.1%    |
| ArcoLinux 19.02.4     | 2         | 0.1%    |
| ArcoLinux I3-v19.02.4 | 1         | 0.05%   |
| ArcoLinux 6.9.2       | 1         | 0.05%   |
| ArcoLinux 6.9.1       | 1         | 0.05%   |
| ArcoLinux 20.5.7      | 1         | 0.05%   |
| ArcoLinux 20.5.2      | 1         | 0.05%   |
| ArcoLinux 20.4.11     | 1         | 0.05%   |
| ArcoLinux 20.2.9      | 1         | 0.05%   |
| ArcoLinux 19.11.3     | 1         | 0.05%   |
| ArcoLinux 19.03.3     | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ArcoLinux | 2024      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.15.7-arch1-1  | 48        | 1.92%   |
| 5.15.10-arch1-1 | 39        | 1.56%   |
| 5.13.13-arch1-1 | 38        | 1.52%   |
| 6.3.9-arch1-1   | 29        | 1.16%   |
| 6.2.11-arch1-1  | 28        | 1.12%   |
| 6.3.8-arch1-1   | 26        | 1.04%   |
| 6.3.2-arch1-1   | 26        | 1.04%   |
| 5.14.14-arch1-1 | 26        | 1.04%   |
| 5.16.11-arch1-1 | 25        | 1%      |
| 6.2.8-arch1-1   | 23        | 0.92%   |
| 5.13.12-arch1-1 | 22        | 0.88%   |
| 5.14.12-arch1-1 | 21        | 0.84%   |
| 6.3.3-arch1-1   | 20        | 0.8%    |
| 6.1.12-arch1-1  | 20        | 0.8%    |
| 6.3.7-arch1-1   | 19        | 0.76%   |
| 5.17.1-arch1-1  | 18        | 0.72%   |
| 6.3.5-arch1-1   | 16        | 0.64%   |
| 5.8.14-arch1-1  | 16        | 0.64%   |
| 5.12.13-arch1-2 | 16        | 0.64%   |
| 6.3.4-arch1-1   | 15        | 0.6%    |
| 5.9.14-arch1-1  | 15        | 0.6%    |
| 5.19.13-arch1-1 | 15        | 0.6%    |
| 5.16.2-arch1-1  | 15        | 0.6%    |
| 5.12.15-arch1-1 | 15        | 0.6%    |
| 6.3.6-arch1-1   | 14        | 0.56%   |
| 6.3.1-arch2-1   | 14        | 0.56%   |
| 6.0.8-arch1-1   | 14        | 0.56%   |
| 5.15.5-arch1-1  | 14        | 0.56%   |
| 5.15.11-arch2-1 | 14        | 0.56%   |
| 6.4.8-arch1-1   | 13        | 0.52%   |
| 6.3.1-arch1-1   | 13        | 0.52%   |
| 6.0.12-arch1-1  | 13        | 0.52%   |
| 5.9.8-arch1-1   | 13        | 0.52%   |
| 5.17.9-arch1-1  | 13        | 0.52%   |
| 5.15.4-arch1-1  | 13        | 0.52%   |
| 5.12.12-arch1-1 | 13        | 0.52%   |
| 6.0.2-arch1-1   | 12        | 0.48%   |
| 5.9.1-arch1-1   | 12        | 0.48%   |
| 5.17.5-arch1-1  | 12        | 0.48%   |
| 5.15.2-arch1-1  | 12        | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.7  | 59        | 2.36%   |
| 6.3.8   | 41        | 1.64%   |
| 5.15.10 | 41        | 1.64%   |
| 5.13.13 | 38        | 1.52%   |
| 6.3.2   | 35        | 1.4%    |
| 6.3.9   | 33        | 1.32%   |
| 6.3.1   | 32        | 1.28%   |
| 6.2.11  | 31        | 1.24%   |
| 6.3.3   | 28        | 1.12%   |
| 6.1.12  | 28        | 1.12%   |
| 5.16.11 | 28        | 1.12%   |
| 6.2.8   | 26        | 1.04%   |
| 5.14.14 | 26        | 1.04%   |
| 6.0.2   | 25        | 1%      |
| 5.17.1  | 25        | 1%      |
| 6.3.5   | 24        | 0.96%   |
| 5.14.12 | 24        | 0.96%   |
| 5.13.12 | 24        | 0.96%   |
| 6.4.3   | 22        | 0.88%   |
| 6.3.7   | 22        | 0.88%   |
| 6.3.4   | 22        | 0.88%   |
| 6.4.2   | 21        | 0.84%   |
| 6.2.10  | 20        | 0.8%    |
| 6.4.7   | 19        | 0.76%   |
| 6.0.8   | 19        | 0.76%   |
| 5.9.14  | 19        | 0.76%   |
| 5.16.2  | 19        | 0.76%   |
| 5.9.8   | 18        | 0.72%   |
| 5.17.5  | 18        | 0.72%   |
| 5.15.4  | 18        | 0.72%   |
| 5.12.15 | 18        | 0.72%   |
| 5.12.13 | 18        | 0.72%   |
| 6.4.8   | 17        | 0.68%   |
| 6.4.1   | 17        | 0.68%   |
| 6.3.6   | 17        | 0.68%   |
| 5.8.14  | 17        | 0.68%   |
| 6.2.12  | 16        | 0.64%   |
| 5.9.6   | 16        | 0.64%   |
| 5.15.5  | 16        | 0.64%   |
| 6.1.39  | 15        | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15     | 300       | 12.56%  |
| 6.3      | 242       | 10.13%  |
| 5.10     | 214       | 8.96%   |
| 6.1      | 201       | 8.41%   |
| 6.2      | 145       | 6.07%   |
| 5.16     | 132       | 5.53%   |
| 5.14     | 131       | 5.48%   |
| 6.0      | 122       | 5.11%   |
| 6.4      | 118       | 4.94%   |
| 5.13     | 110       | 4.6%    |
| 5.9      | 109       | 4.56%   |
| 5.12     | 107       | 4.48%   |
| 5.17     | 92        | 3.85%   |
| 5.18     | 87        | 3.64%   |
| 5.11     | 77        | 3.22%   |
| 5.19     | 72        | 3.01%   |
| 5.4      | 60        | 2.51%   |
| 5.8      | 34        | 1.42%   |
| 5.6      | 7         | 0.29%   |
| 5.7      | 6         | 0.25%   |
| 5.5      | 5         | 0.21%   |
| 5.3      | 3         | 0.13%   |
| 5.0      | 3         | 0.13%   |
| 5.15.96  | 2         | 0.08%   |
| 4.19     | 2         | 0.08%   |
| 6.3.3    | 1         | 0.04%   |
| 6.3.0    | 1         | 0.04%   |
| 6.2.0    | 1         | 0.04%   |
| 5.2      | 1         | 0.04%   |
| 5.15.107 | 1         | 0.04%   |
| 4.20     | 1         | 0.04%   |
| 4.18     | 1         | 0.04%   |
| 4.17     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 2024      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| XFCE           | 711       | 32.8%   |
| KDE5           | 432       | 19.93%  |
| i3             | 147       | 6.78%   |
| GNOME          | 140       | 6.46%   |
| awesome        | 114       | 5.26%   |
| qtile          | 76        | 3.51%   |
| X-Cinnamon     | 65        | 3%      |
| bspwm          | 63        | 2.91%   |
| xmonad         | 52        | 2.4%    |
| Hyprland       | 46        | 2.12%   |
| DWM            | 44        | 2.03%   |
| Cinnamon       | 44        | 2.03%   |
| LeftWM         | 31        | 1.43%   |
| Deepin         | 28        | 1.29%   |
| Unknown        | 26        | 1.2%    |
| KDE            | 25        | 1.15%   |
| LXQt           | 18        | 0.83%   |
| MATE           | 16        | 0.74%   |
| chadwm         | 16        | 0.74%   |
| Budgie         | 16        | 0.74%   |
| i3-with-shmlog | 12        | 0.55%   |
| herbstluftwm   | 12        | 0.55%   |
| sway           | 6         | 0.28%   |
| ICEWM          | 4         | 0.18%   |
| Cutefish       | 4         | 0.18%   |
| Unity          | 3         | 0.14%   |
| spectrwm       | 3         | 0.14%   |
| openbox        | 3         | 0.14%   |
| cwm            | 3         | 0.14%   |
| Hypr           | 2         | 0.09%   |
| dusk           | 2         | 0.09%   |
| river          | 1         | 0.05%   |
| jwm            | 1         | 0.05%   |
| GNOME Classic  | 1         | 0.05%   |
| dwm-sc         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1815      | 87.98%  |
| Wayland | 128       | 6.2%    |
| Tty     | 99        | 4.8%    |
| Unknown | 21        | 1.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1237      | 57.64%  |
| LightDM | 368       | 17.15%  |
| TDM     | 295       | 13.75%  |
| Unknown | 180       | 8.39%   |
| GDM     | 52        | 2.42%   |
| Ly      | 8         | 0.37%   |
| LXDM    | 4         | 0.19%   |
| XDM     | 1         | 0.05%   |
| SLiM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1152      | 56.03%  |
| en_GB   | 167       | 8.12%   |
| de_DE   | 96        | 4.67%   |
| en_CA   | 68        | 3.31%   |
| en_IN   | 55        | 2.68%   |
| en_AU   | 41        | 1.99%   |
| fr_FR   | 40        | 1.95%   |
| C       | 38        | 1.85%   |
| ru_RU   | 33        | 1.61%   |
| pt_BR   | 33        | 1.61%   |
| es_ES   | 31        | 1.51%   |
| pl_PL   | 21        | 1.02%   |
| it_IT   | 20        | 0.97%   |
| en_ZA   | 17        | 0.83%   |
| tr_TR   | 14        | 0.68%   |
| es_MX   | 14        | 0.68%   |
| Unknown | 14        | 0.68%   |
| hu_HU   | 13        | 0.63%   |
| es_AR   | 13        | 0.63%   |
| sv_SE   | 12        | 0.58%   |
| nl_NL   | 9         | 0.44%   |
| zh_CN   | 8         | 0.39%   |
| en_IE   | 8         | 0.39%   |
| en_DK   | 8         | 0.39%   |
| fr_CA   | 7         | 0.34%   |
| en_PH   | 7         | 0.34%   |
| ru_UA   | 6         | 0.29%   |
| pt_PT   | 6         | 0.29%   |
| ja_JP   | 6         | 0.29%   |
| fi_FI   | 6         | 0.29%   |
| en_IL   | 6         | 0.29%   |
| nl_BE   | 5         | 0.24%   |
| en_SG   | 5         | 0.24%   |
| de_ch   | 5         | 0.24%   |
| da_DK   | 5         | 0.24%   |
| fr_BE   | 4         | 0.19%   |
| es_CO   | 4         | 0.19%   |
| en_AG   | 4         | 0.19%   |
| de_AT   | 4         | 0.19%   |
| uk_UA   | 3         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1505      | 73.59%  |
| BIOS | 540       | 26.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1494      | 71.86%  |
| Btrfs    | 435       | 20.92%  |
| Overlay  | 100       | 4.81%   |
| Xfs      | 26        | 1.25%   |
| F2fs     | 12        | 0.58%   |
| Unknown  | 8         | 0.38%   |
| Jfs      | 2         | 0.1%    |
| Tmpfs    | 1         | 0.05%   |
| Reiserfs | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1599      | 77.85%  |
| MBR     | 287       | 13.97%  |
| Unknown | 168       | 8.18%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1551      | 73.96%  |
| Yes       | 546       | 26.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1207      | 58.85%  |
| Yes       | 844       | 41.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 415       | 20.5%   |
| Lenovo              | 335       | 16.55%  |
| Hewlett-Packard     | 226       | 11.17%  |
| Dell                | 220       | 10.87%  |
| Gigabyte Technology | 161       | 7.95%   |
| MSI                 | 159       | 7.86%   |
| ASRock              | 81        | 4%      |
| Acer                | 81        | 4%      |
| Apple               | 50        | 2.47%   |
| Toshiba             | 23        | 1.14%   |
| Unknown             | 22        | 1.09%   |
| Intel               | 21        | 1.04%   |
| Supermicro          | 18        | 0.89%   |
| Sony                | 12        | 0.59%   |
| HUAWEI              | 12        | 0.59%   |
| Samsung Electronics | 11        | 0.54%   |
| Fujitsu             | 11        | 0.54%   |
| System76            | 10        | 0.49%   |
| Medion              | 10        | 0.49%   |
| Alienware           | 9         | 0.44%   |
| Razer               | 8         | 0.4%    |
| TUXEDO              | 7         | 0.35%   |
| Timi                | 7         | 0.35%   |
| Notebook            | 7         | 0.35%   |
| AZW                 | 7         | 0.35%   |
| Chuwi               | 6         | 0.3%    |
| Pegatron            | 4         | 0.2%    |
| Packard Bell        | 4         | 0.2%    |
| Microsoft           | 4         | 0.2%    |
| Google              | 4         | 0.2%    |
| Foxconn             | 4         | 0.2%    |
| Biostar             | 4         | 0.2%    |
| ZOTAC               | 3         | 0.15%   |
| Schenker            | 3         | 0.15%   |
| LG Electronics      | 3         | 0.15%   |
| Casper              | 3         | 0.15%   |
| BESSTAR Tech        | 3         | 0.15%   |
| Teclast             | 2         | 0.1%    |
| SYWZ                | 2         | 0.1%    |
| Shuttle             | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 27        | 1.33%   |
| ASUS TUF Gaming X570-PLUS        | 19        | 0.94%   |
| ASUS All Series                  | 18        | 0.89%   |
| ASUS ROG STRIX B550-F GAMING     | 12        | 0.59%   |
| Supermicro SYS-5019A-FTN4        | 10        | 0.49%   |
| ASUS PRIME X570-P                | 10        | 0.49%   |
| MSI MS-7C37                      | 9         | 0.44%   |
| MSI MS-7C91                      | 8         | 0.4%    |
| HP Pavilion Notebook             | 8         | 0.4%    |
| ASUS PRIME X470-PRO              | 8         | 0.4%    |
| MSI MS-7B89                      | 7         | 0.35%   |
| MSI MS-7B79                      | 7         | 0.35%   |
| MSI MS-7C02                      | 6         | 0.3%    |
| HP Notebook                      | 6         | 0.3%    |
| ASUS PRIME A320M-K               | 6         | 0.3%    |
| MSI MS-7C95                      | 5         | 0.25%   |
| MSI MS-7A38                      | 5         | 0.25%   |
| MSI MS-7971                      | 5         | 0.25%   |
| HP Laptop 15s-eq2xxx             | 5         | 0.25%   |
| Gigabyte X570 AORUS PRO WIFI     | 5         | 0.25%   |
| Gigabyte X570 AORUS MASTER       | 5         | 0.25%   |
| Gigabyte X570 AORUS ELITE        | 5         | 0.25%   |
| Gigabyte B450 AORUS ELITE        | 5         | 0.25%   |
| Dell OptiPlex 9020               | 5         | 0.25%   |
| Dell OptiPlex 9010               | 5         | 0.25%   |
| Dell OptiPlex 7010               | 5         | 0.25%   |
| ASUS ROG CROSSHAIR VIII HERO     | 5         | 0.25%   |
| ASUS PRIME B450M-A               | 5         | 0.25%   |
| ASUS M5A78L-M/USB3               | 5         | 0.25%   |
| ASRock B450M Pro4                | 5         | 0.25%   |
| Razer Blade                      | 4         | 0.2%    |
| MSI MS-7B98                      | 4         | 0.2%    |
| MSI MS-7B86                      | 4         | 0.2%    |
| Lenovo Legion 5 Pro 16ACH6H 82JQ | 4         | 0.2%    |
| Intel H61                        | 4         | 0.2%    |
| HUAWEI KLVL-WXX9                 | 4         | 0.2%    |
| HP ProDesk 600 G1 SFF            | 4         | 0.2%    |
| HP Laptop 15-da0xxx              | 4         | 0.2%    |
| HP EliteBook 840 G3              | 4         | 0.2%    |
| Gigabyte X570 GAMING X           | 4         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 159       | 7.86%   |
| ASUS ROG                  | 77        | 3.8%    |
| ASUS PRIME                | 76        | 3.75%   |
| Lenovo IdeaPad            | 67        | 3.31%   |
| Dell Inspiron             | 66        | 3.26%   |
| Dell Latitude             | 52        | 2.57%   |
| ASUS TUF                  | 51        | 2.52%   |
| Acer Aspire               | 50        | 2.47%   |
| HP Pavilion               | 45        | 2.22%   |
| Dell OptiPlex             | 32        | 1.58%   |
| HP Laptop                 | 30        | 1.48%   |
| ASUS VivoBook             | 30        | 1.48%   |
| Dell XPS                  | 29        | 1.43%   |
| Lenovo Legion             | 27        | 1.33%   |
| Unknown                   | 27        | 1.33%   |
| HP EliteBook              | 25        | 1.24%   |
| Gigabyte X570             | 22        | 1.09%   |
| Toshiba Satellite         | 19        | 0.94%   |
| HP ENVY                   | 19        | 0.94%   |
| Dell Precision            | 18        | 0.89%   |
| ASUS All                  | 18        | 0.89%   |
| Lenovo Yoga               | 16        | 0.79%   |
| Lenovo ThinkCentre        | 15        | 0.74%   |
| Gigabyte B450M            | 12        | 0.59%   |
| Dell Vostro               | 12        | 0.59%   |
| HP EliteDesk              | 11        | 0.54%   |
| Gigabyte B450             | 11        | 0.54%   |
| Acer Nitro                | 11        | 0.54%   |
| Supermicro SYS-5019A-FTN4 | 10        | 0.49%   |
| HP Compaq                 | 10        | 0.49%   |
| ASRock B450M              | 10        | 0.49%   |
| MSI MS-7C37               | 9         | 0.44%   |
| HP OMEN                   | 9         | 0.44%   |
| ASUS Zenbook              | 9         | 0.44%   |
| ASUS P8Z77-V              | 9         | 0.44%   |
| Razer Blade               | 8         | 0.4%    |
| MSI MS-7C91               | 8         | 0.4%    |
| HP ProDesk                | 8         | 0.4%    |
| HP ProBook                | 8         | 0.4%    |
| Fujitsu LIFEBOOK          | 8         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 272       | 13.44%  |
| 2020    | 263       | 12.99%  |
| 2018    | 253       | 12.5%   |
| 2017    | 173       | 8.55%   |
| 2021    | 172       | 8.5%    |
| 2013    | 125       | 6.18%   |
| 2016    | 121       | 5.98%   |
| 2012    | 117       | 5.78%   |
| 2015    | 108       | 5.34%   |
| 2011    | 104       | 5.14%   |
| 2014    | 93        | 4.59%   |
| 2022    | 67        | 3.31%   |
| 2010    | 67        | 3.31%   |
| 2009    | 27        | 1.33%   |
| 2008    | 26        | 1.28%   |
| 2023    | 16        | 0.79%   |
| 2007    | 11        | 0.54%   |
| 2006    | 6         | 0.3%    |
| 2005    | 1         | 0.05%   |
| 2004    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1034      | 51.09%  |
| Desktop     | 884       | 43.68%  |
| Convertible | 42        | 2.08%   |
| Mini pc     | 29        | 1.43%   |
| All in one  | 21        | 1.04%   |
| Tablet      | 8         | 0.4%    |
| Server      | 5         | 0.25%   |
| Stick pc    | 1         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2023      | 99.95%  |
| Enabled  | 1         | 0.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2016      | 99.6%   |
| Yes  | 8         | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 552       | 26.9%   |
| 4.01-8.0        | 457       | 22.27%  |
| 8.01-16.0       | 358       | 17.45%  |
| 32.01-64.0      | 333       | 16.23%  |
| 3.01-4.0        | 181       | 8.82%   |
| 64.01-256.0     | 89        | 4.34%   |
| 24.01-32.0      | 49        | 2.39%   |
| 1.01-2.0        | 22        | 1.07%   |
| 2.01-3.0        | 9         | 0.44%   |
| More than 256.0 | 1         | 0.05%   |
| Unknown         | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 678       | 29.54%  |
| 2.01-3.0   | 568       | 24.75%  |
| 4.01-8.0   | 375       | 16.34%  |
| 3.01-4.0   | 343       | 14.95%  |
| 0.51-1.0   | 187       | 8.15%   |
| 8.01-16.0  | 102       | 4.44%   |
| 0.01-0.5   | 28        | 1.22%   |
| 16.01-24.0 | 12        | 0.52%   |
| 24.01-32.0 | 1         | 0.04%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 962       | 45.68%  |
| 2      | 611       | 29.01%  |
| 3      | 254       | 12.06%  |
| 4      | 145       | 6.89%   |
| 5      | 72        | 3.42%   |
| 6      | 27        | 1.28%   |
| 7      | 15        | 0.71%   |
| 0      | 6         | 0.28%   |
| 9      | 5         | 0.24%   |
| 11     | 3         | 0.14%   |
| 8      | 3         | 0.14%   |
| 21     | 1         | 0.05%   |
| 19     | 1         | 0.05%   |
| 10     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1504      | 73.94%  |
| Yes       | 530       | 26.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1789      | 88%     |
| No        | 244       | 12%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1534      | 75.57%  |
| No        | 496       | 24.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1396      | 68%     |
| No        | 657       | 32%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 453       | 22.24%  |
| Germany      | 153       | 7.51%   |
| UK           | 116       | 5.69%   |
| Canada       | 91        | 4.47%   |
| India        | 82        | 4.03%   |
| Brazil       | 66        | 3.24%   |
| France       | 61        | 2.99%   |
| Spain        | 51        | 2.5%    |
| Russia       | 48        | 2.36%   |
| Belgium      | 48        | 2.36%   |
| Netherlands  | 44        | 2.16%   |
| Australia    | 44        | 2.16%   |
| Poland       | 41        | 2.01%   |
| Italy        | 41        | 2.01%   |
| Sweden       | 39        | 1.91%   |
| Turkey       | 38        | 1.87%   |
| Mexico       | 26        | 1.28%   |
| Switzerland  | 24        | 1.18%   |
| Hungary      | 24        | 1.18%   |
| Argentina    | 24        | 1.18%   |
| Romania      | 21        | 1.03%   |
| Norway       | 20        | 0.98%   |
| Ukraine      | 19        | 0.93%   |
| Indonesia    | 19        | 0.93%   |
| South Africa | 18        | 0.88%   |
| Portugal     | 18        | 0.88%   |
| Finland      | 18        | 0.88%   |
| Greece       | 17        | 0.83%   |
| Bulgaria     | 17        | 0.83%   |
| Denmark      | 14        | 0.69%   |
| Czechia      | 14        | 0.69%   |
| Austria      | 14        | 0.69%   |
| Japan        | 12        | 0.59%   |
| Ireland      | 12        | 0.59%   |
| Colombia     | 12        | 0.59%   |
| China        | 12        | 0.59%   |
| Bangladesh   | 12        | 0.59%   |
| Malaysia     | 11        | 0.54%   |
| Serbia       | 10        | 0.49%   |
| Philippines  | 10        | 0.49%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sydney            | 22        | 1.02%   |
| Berlin            | 20        | 0.92%   |
| Durham            | 17        | 0.79%   |
| Madrid            | 14        | 0.65%   |
| Paris             | 13        | 0.6%    |
| Istanbul          | 13        | 0.6%    |
| Warsaw            | 12        | 0.55%   |
| Toronto           | 12        | 0.55%   |
| New York          | 12        | 0.55%   |
| Moscow            | 12        | 0.55%   |
| Lier              | 11        | 0.51%   |
| Houston           | 11        | 0.51%   |
| Vienna            | 10        | 0.46%   |
| Sao Paulo         | 10        | 0.46%   |
| Pune              | 10        | 0.46%   |
| London            | 10        | 0.46%   |
| Helsinki          | 10        | 0.46%   |
| Amsterdam         | 10        | 0.46%   |
| Stockholm         | 9         | 0.42%   |
| Portland          | 9         | 0.42%   |
| Frankfurt am Main | 9         | 0.42%   |
| Atlanta           | 9         | 0.42%   |
| Sofia             | 8         | 0.37%   |
| Chicago           | 8         | 0.37%   |
| Budapest          | 8         | 0.37%   |
| Brooklyn          | 8         | 0.37%   |
| Brisbane          | 8         | 0.37%   |
| Bengaluru         | 8         | 0.37%   |
| Athens            | 8         | 0.37%   |
| Zurich            | 7         | 0.32%   |
| Wilrijk           | 7         | 0.32%   |
| St Petersburg     | 7         | 0.32%   |
| Singapore         | 7         | 0.32%   |
| Rio de Janeiro    | 7         | 0.32%   |
| Oslo              | 7         | 0.32%   |
| Milan             | 7         | 0.32%   |
| Melbourne         | 7         | 0.32%   |
| Dublin            | 7         | 0.32%   |
| Dhaka             | 7         | 0.32%   |
| Central           | 7         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 669       | 1156   | 19.05%  |
| WDC                         | 528       | 878    | 15.03%  |
| Seagate                     | 455       | 691    | 12.96%  |
| Toshiba                     | 204       | 260    | 5.81%   |
| SanDisk                     | 193       | 241    | 5.5%    |
| Kingston                    | 182       | 257    | 5.18%   |
| Crucial                     | 141       | 207    | 4.01%   |
| SK hynix                    | 92        | 119    | 2.62%   |
| Intel                       | 92        | 132    | 2.62%   |
| Hitachi                     | 69        | 81     | 1.96%   |
| Unknown                     | 68        | 100    | 1.94%   |
| A-DATA Technology           | 57        | 71     | 1.62%   |
| Micron Technology           | 44        | 52     | 1.25%   |
| HGST                        | 44        | 59     | 1.25%   |
| Phison Electronics          | 43        | 57     | 1.22%   |
| PNY                         | 31        | 45     | 0.88%   |
| Apple                       | 31        | 46     | 0.88%   |
| Micron/Crucial Technology   | 30        | 41     | 0.85%   |
| Phison                      | 28        | 45     | 0.8%    |
| KIOXIA                      | 25        | 29     | 0.71%   |
| Silicon Motion              | 24        | 28     | 0.68%   |
| SPCC                        | 23        | 29     | 0.65%   |
| China                       | 22        | 38     | 0.63%   |
| JMicron Technology          | 21        | 24     | 0.6%    |
| Kingston Technology Company | 19        | 25     | 0.54%   |
| Corsair                     | 19        | 36     | 0.54%   |
| LITEON                      | 15        | 19     | 0.43%   |
| Hewlett-Packard             | 13        | 17     | 0.37%   |
| Transcend                   | 12        | 16     | 0.34%   |
| SABRENT                     | 12        | 14     | 0.34%   |
| Patriot                     | 12        | 21     | 0.34%   |
| OCZ                         | 12        | 15     | 0.34%   |
| Gigabyte Technology         | 12        | 16     | 0.34%   |
| Realtek Semiconductor       | 11        | 13     | 0.31%   |
| LITEONIT                    | 11        | 11     | 0.31%   |
| Intenso                     | 11        | 17     | 0.31%   |
| ADATA Technology            | 11        | 11     | 0.31%   |
| XPG                         | 10        | 13     | 0.28%   |
| Plextor                     | 9         | 9      | 0.26%   |
| ASMT                        | 8         | 12     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 90        | 2.24%   |
| Samsung SSD 860 EVO 500GB                           | 54        | 1.34%   |
| Seagate ST1000LM035-1RK172 1TB                      | 43        | 1.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 43        | 1.07%   |
| Kingston SA400S37240G 240GB SSD                     | 43        | 1.07%   |
| Samsung SSD 850 EVO 250GB                           | 36        | 0.9%    |
| Crucial CT1000MX500SSD1 1TB                         | 31        | 0.77%   |
| Toshiba MQ01ABD100 1TB                              | 30        | 0.75%   |
| Samsung SSD 860 EVO 1TB                             | 30        | 0.75%   |
| Seagate ST1000DM010-2EP102 1TB                      | 28        | 0.7%    |
| Samsung SSD 850 EVO 500GB                           | 28        | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB                      | 25        | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 24        | 0.6%    |
| Samsung SSD 860 EVO 250GB                           | 24        | 0.6%    |
| Samsung SSD 970 EVO Plus 500GB                      | 23        | 0.57%   |
| Samsung SSD 970 EVO Plus 1TB                        | 23        | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 23        | 0.57%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 22        | 0.55%   |
| Toshiba MQ04ABF100 1TB                              | 21        | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 21        | 0.52%   |
| Kingston SA400S37480G 480GB SSD                     | 21        | 0.52%   |
| Kingston SA400S37120G 120GB SSD                     | 20        | 0.5%    |
| Unknown SD/MMC/MS PRO 128GB                         | 19        | 0.47%   |
| Samsung SSD 870 EVO 1TB                             | 19        | 0.47%   |
| Crucial CT500MX500SSD1 500GB                        | 19        | 0.47%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 18        | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB                      | 17        | 0.42%   |
| Seagate Expansion 1TB                               | 16        | 0.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 16        | 0.4%    |
| Phison E12 NVMe Controller 2TB                      | 16        | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 15        | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 15        | 0.37%   |
| Toshiba HDWD110 1TB                                 | 15        | 0.37%   |
| Samsung SSD 970 EVO 1TB                             | 15        | 0.37%   |
| Crucial CT240BX500SSD1 240GB                        | 15        | 0.37%   |
| Toshiba DT01ACA100 1TB                              | 14        | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB                      | 14        | 0.35%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 14        | 0.35%   |
| JMicron Generic 512GB                               | 14        | 0.35%   |
| Samsung SSD 980 1TB                                 | 13        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 441       | 661    | 36.51%  |
| WDC                 | 375       | 632    | 31.04%  |
| Toshiba             | 147       | 191    | 12.17%  |
| Hitachi             | 69        | 81     | 5.71%   |
| HGST                | 43        | 57     | 3.56%   |
| Samsung Electronics | 42        | 60     | 3.48%   |
| Unknown             | 21        | 29     | 1.74%   |
| JMicron Technology  | 15        | 17     | 1.24%   |
| Apple               | 9         | 16     | 0.75%   |
| ASMT                | 6         | 10     | 0.5%    |
| Maxtor              | 5         | 7      | 0.41%   |
| External            | 5         | 9      | 0.41%   |
| SSK                 | 4         | 4      | 0.33%   |
| Hewlett-Packard     | 4         | 5      | 0.33%   |
| USB3.0              | 2         | 3      | 0.17%   |
| LaCie               | 2         | 2      | 0.17%   |
| Intenso             | 2         | 2      | 0.17%   |
| Fujitsu             | 2         | 2      | 0.17%   |
| Fantom              | 2         | 5      | 0.17%   |
| ASMedia             | 2         | 3      | 0.17%   |
| WD MediaMax         | 1         | 1      | 0.08%   |
| RSH-319             | 1         | 1      | 0.08%   |
| PHD 3.0             | 1         | 1      | 0.08%   |
| KESU                | 1         | 1      | 0.08%   |
| Inateck             | 1         | 1      | 0.08%   |
| HGST HUS            | 1         | 1      | 0.08%   |
| HGST HTS            | 1         | 1      | 0.08%   |
| H/W                 | 1         | 6      | 0.08%   |
| ExcelStor           | 1         | 2      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 360       | 583    | 27.93%  |
| Kingston            | 145       | 196    | 11.25%  |
| Crucial             | 124       | 176    | 9.62%   |
| WDC                 | 110       | 152    | 8.53%   |
| SanDisk             | 105       | 124    | 8.15%   |
| A-DATA Technology   | 39        | 51     | 3.03%   |
| PNY                 | 30        | 41     | 2.33%   |
| SK hynix            | 29        | 45     | 2.25%   |
| Toshiba             | 23        | 30     | 1.78%   |
| Intel               | 23        | 29     | 1.78%   |
| China               | 22        | 38     | 1.71%   |
| Apple               | 20        | 22     | 1.55%   |
| SPCC                | 19        | 23     | 1.47%   |
| Micron Technology   | 19        | 23     | 1.47%   |
| Patriot             | 12        | 21     | 0.93%   |
| OCZ                 | 12        | 15     | 0.93%   |
| LITEON              | 12        | 16     | 0.93%   |
| Transcend           | 11        | 15     | 0.85%   |
| LITEONIT            | 11        | 11     | 0.85%   |
| Intenso             | 9         | 15     | 0.7%    |
| Corsair             | 8         | 17     | 0.62%   |
| Plextor             | 7         | 7      | 0.54%   |
| Hewlett-Packard     | 7         | 10     | 0.54%   |
| Team                | 6         | 7      | 0.47%   |
| GOODRAM             | 6         | 9      | 0.47%   |
| Gigabyte Technology | 6         | 7      | 0.47%   |
| TO Exter            | 5         | 5      | 0.39%   |
| Seagate             | 5         | 8      | 0.39%   |
| Mushkin             | 5         | 8      | 0.39%   |
| KingSpec            | 5         | 5      | 0.39%   |
| Verbatim            | 4         | 5      | 0.31%   |
| Lexar               | 4         | 4      | 0.31%   |
| Unknown             | 4         | 4      | 0.31%   |
| Unknown             | 3         | 3      | 0.23%   |
| Leven               | 3         | 3      | 0.23%   |
| HS-SSD-C100         | 3         | 4      | 0.23%   |
| Apacer              | 3         | 3      | 0.23%   |
| Acer                | 3         | 3      | 0.23%   |
| Zheino              | 2         | 2      | 0.16%   |
| Vaseky              | 2         | 4      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1050      | 1822   | 34.45%  |
| HDD     | 991       | 1812   | 32.51%  |
| NVMe    | 930       | 1459   | 30.51%  |
| MMC     | 45        | 65     | 1.48%   |
| Unknown | 32        | 45     | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1519      | 3378   | 56.53%  |
| NVMe | 928       | 1444   | 34.54%  |
| SAS  | 195       | 316    | 7.26%   |
| MMC  | 45        | 65     | 1.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1061      | 1819   | 47.99%  |
| 0.51-1.0   | 754       | 1127   | 34.1%   |
| 1.01-2.0   | 231       | 397    | 10.45%  |
| 3.01-4.0   | 72        | 125    | 3.26%   |
| 4.01-10.0  | 50        | 96     | 2.26%   |
| 2.01-3.0   | 38        | 61     | 1.72%   |
| 10.01-20.0 | 5         | 9      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 452       | 20.88%  |
| 251-500        | 429       | 19.82%  |
| 501-1000       | 345       | 15.94%  |
| More than 3000 | 269       | 12.42%  |
| 1001-2000      | 263       | 12.15%  |
| 2001-3000      | 100       | 4.62%   |
| Unknown        | 96        | 4.43%   |
| 1-20           | 92        | 4.25%   |
| 51-100         | 82        | 3.79%   |
| 21-50          | 37        | 1.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 555       | 24.48%  |
| 21-50          | 401       | 17.69%  |
| 101-250        | 342       | 15.09%  |
| 51-100         | 255       | 11.25%  |
| 251-500        | 219       | 9.66%   |
| 501-1000       | 180       | 7.94%   |
| 1001-2000      | 108       | 4.76%   |
| Unknown        | 96        | 4.23%   |
| More than 3000 | 65        | 2.87%   |
| 2001-3000      | 44        | 1.94%   |
| 0              | 2         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 11        | 11     | 2.57%   |
| Toshiba MQ01ABD100 1TB                                          | 10        | 13     | 2.34%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 8         | 9      | 1.87%   |
| Samsung Electronics SSD 870 EVO 1TB                             | 8         | 11     | 1.87%   |
| Toshiba MQ01ABF050 500GB                                        | 6         | 6      | 1.4%    |
| Seagate ST3500413AS 500GB                                       | 6         | 7      | 1.4%    |
| Seagate ST9320325AS 320GB                                       | 5         | 6      | 1.17%   |
| Seagate ST31000528AS 1TB                                        | 5         | 5      | 1.17%   |
| Hitachi HTS547575A9E384 752GB                                   | 5         | 5      | 1.17%   |
| Seagate ST1000DM003-9YN162 1TB                                  | 4         | 4      | 0.93%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 4         | 6      | 0.93%   |
| SanDisk SSD PLUS 1000GB                                         | 4         | 4      | 0.93%   |
| Hitachi HDS721010CLA332 1TB                                     | 4         | 5      | 0.93%   |
| WDC WD20EARS-00MVWB0 2TB                                        | 3         | 5      | 0.7%    |
| Seagate ST500LT012-1DG142 500GB                                 | 3         | 3      | 0.7%    |
| Seagate ST500LM021-1KJ152 500GB                                 | 3         | 3      | 0.7%    |
| Seagate ST3500312CS 500GB                                       | 3         | 5      | 0.7%    |
| Seagate ST2000DM001-1ER164 2TB                                  | 3         | 6      | 0.7%    |
| Seagate ST1000LM014-1EJ164 1TB                                  | 3         | 3      | 0.7%    |
| Samsung Electronics SSD 850 EVO 250GB                           | 3         | 4      | 0.7%    |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 3      | 0.7%    |
| Maxtor STM3250310AS 250GB                                       | 3         | 4      | 0.7%    |
| WDC WDS500G1X0E-00AFY0 500GB                                    | 2         | 2      | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 2         | 2      | 0.47%   |
| WDC WD6400AAKS-22A7B2 640GB                                     | 2         | 3      | 0.47%   |
| WDC WD5000AAKX-75U6AA0 500GB                                    | 2         | 2      | 0.47%   |
| WDC WD5000AAKX-603CA0 500GB                                     | 2         | 6      | 0.47%   |
| WDC WD5000AAKX-00ERMA0 500GB                                    | 2         | 2      | 0.47%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 2         | 3      | 0.47%   |
| WDC WD40EFRX-68N32N0 4TB                                        | 2         | 6      | 0.47%   |
| WDC WD3200AVJS-63B6A0 320GB                                     | 2         | 5      | 0.47%   |
| WDC WD3200AAJS-00L7A0 320GB                                     | 2         | 2      | 0.47%   |
| WDC WD20EFRX-68EUZN0 2TB                                        | 2         | 3      | 0.47%   |
| WDC WD20EARX-00PASB0 2TB                                        | 2         | 2      | 0.47%   |
| WDC WD2002FAEX-007BA0 2TB                                       | 2         | 2      | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 2         | 2      | 0.47%   |
| WDC WD10EZEX-00WN4A0 1TB                                        | 2         | 2      | 0.47%   |
| WDC WD10EARS-22Y5B1 1TB                                         | 2         | 3      | 0.47%   |
| WDC WD10EARS-00Y5B1 1TB                                         | 2         | 5      | 0.47%   |
| WDC WD10EADS-11M2B1 1TB                                         | 2         | 2      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 105       | 129    | 25.8%   |
| WDC                       | 100       | 156    | 24.57%  |
| Samsung Electronics       | 35        | 49     | 8.6%    |
| Toshiba                   | 33        | 41     | 8.11%   |
| Hitachi                   | 24        | 28     | 5.9%    |
| HGST                      | 12        | 16     | 2.95%   |
| SanDisk                   | 11        | 11     | 2.7%    |
| Kingston                  | 10        | 13     | 2.46%   |
| Intel                     | 10        | 14     | 2.46%   |
| SK hynix                  | 7         | 8      | 1.72%   |
| Crucial                   | 6         | 6      | 1.47%   |
| Micron Technology         | 5         | 8      | 1.23%   |
| A-DATA Technology         | 5         | 5      | 1.23%   |
| Maxtor                    | 4         | 6      | 0.98%   |
| Corsair                   | 4         | 13     | 0.98%   |
| Transcend                 | 3         | 3      | 0.74%   |
| Hewlett-Packard           | 3         | 3      | 0.74%   |
| Micron/Crucial Technology | 2         | 4      | 0.49%   |
| LITEONIT                  | 2         | 2      | 0.49%   |
| Drevo                     | 2         | 2      | 0.49%   |
| China                     | 2         | 3      | 0.49%   |
| ASMedia                   | 2         | 3      | 0.49%   |
| Apple                     | 2         | 2      | 0.49%   |
| Unknown                   | 2         | 2      | 0.49%   |
| XPG                       | 1         | 1      | 0.25%   |
| USB3.0                    | 1         | 2      | 0.25%   |
| Team                      | 1         | 1      | 0.25%   |
| SSSTC                     | 1         | 1      | 0.25%   |
| SPCC                      | 1         | 1      | 0.25%   |
| Realtek Semiconductor     | 1         | 1      | 0.25%   |
| Plextor                   | 1         | 1      | 0.25%   |
| Patriot                   | 1         | 1      | 0.25%   |
| Mushkin                   | 1         | 1      | 0.25%   |
| Lenovo                    | 1         | 1      | 0.25%   |
| LaCie                     | 1         | 1      | 0.25%   |
| JMicron Technology        | 1         | 1      | 0.25%   |
| Inateck                   | 1         | 1      | 0.25%   |
| HS-SSD-C100               | 1         | 1      | 0.25%   |
| HGST HTS                  | 1         | 1      | 0.25%   |
| Colorful                  | 1         | 1      | 0.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 105       | 129    | 35.84%  |
| WDC                 | 96        | 149    | 32.76%  |
| Toshiba             | 30        | 38     | 10.24%  |
| Hitachi             | 24        | 28     | 8.19%   |
| HGST                | 12        | 16     | 4.1%    |
| Samsung Electronics | 10        | 12     | 3.41%   |
| Maxtor              | 4         | 6      | 1.37%   |
| Hewlett-Packard     | 2         | 2      | 0.68%   |
| ASMedia             | 2         | 3      | 0.68%   |
| Apple               | 2         | 2      | 0.68%   |
| USB3.0              | 1         | 2      | 0.34%   |
| LaCie               | 1         | 1      | 0.34%   |
| JMicron Technology  | 1         | 1      | 0.34%   |
| Inateck             | 1         | 1      | 0.34%   |
| HGST HTS            | 1         | 1      | 0.34%   |
| Unknown             | 1         | 1      | 0.34%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 270       | 392    | 70.13%  |
| SSD  | 92        | 119    | 23.9%   |
| NVMe | 23        | 33     | 5.97%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB                      | 1         | 1      | 9.09%   |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 9.09%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 9.09%   |
| Seagate ST32000641AS 2TB                         | 1         | 2      | 9.09%   |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 9.09%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 9.09%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 9.09%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 36.36%  |
| Samsung Electronics | 3         | 3      | 27.27%  |
| WDC                 | 2         | 2      | 18.18%  |
| HGST                | 2         | 2      | 18.18%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1684      | 3913   | 68.48%  |
| Detected | 391       | 734    | 15.9%   |
| Malfunc  | 373       | 544    | 15.17%  |
| Failed   | 11        | 12     | 0.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1269      | 43.46%  |
| AMD                              | 530       | 18.15%  |
| Samsung Electronics              | 374       | 12.81%  |
| SanDisk                          | 157       | 5.38%   |
| Phison Electronics               | 89        | 3.05%   |
| SK hynix                         | 64        | 2.19%   |
| Kingston Technology Company      | 61        | 2.09%   |
| ASMedia Technology               | 53        | 1.82%   |
| Micron/Crucial Technology        | 49        | 1.68%   |
| Marvell Technology Group         | 32        | 1.1%    |
| Toshiba America Info Systems     | 31        | 1.06%   |
| Silicon Motion                   | 30        | 1.03%   |
| KIOXIA                           | 30        | 1.03%   |
| ADATA Technology                 | 29        | 0.99%   |
| Micron Technology                | 27        | 0.92%   |
| Realtek Semiconductor            | 18        | 0.62%   |
| Nvidia                           | 16        | 0.55%   |
| Seagate Technology               | 10        | 0.34%   |
| Lite-On Technology               | 7         | 0.24%   |
| JMicron Technology               | 7         | 0.24%   |
| Union Memory (Shenzhen)          | 6         | 0.21%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.14%   |
| Lenovo                           | 3         | 0.1%    |
| Apple                            | 3         | 0.1%    |
| VIA Technologies                 | 2         | 0.07%   |
| Silicon Image                    | 2         | 0.07%   |
| Shenzhen Longsys Electronics     | 2         | 0.07%   |
| Netac Technology                 | 2         | 0.07%   |
| LSI Logic / Symbios Logic        | 2         | 0.07%   |
| Broadcom / LSI                   | 2         | 0.07%   |
| Adaptec                          | 2         | 0.07%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| TenaFe                           | 1         | 0.03%   |
| Solid State Storage Technology   | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| INNOGRIT                         | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 388       | 11.9%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 203       | 6.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 119       | 3.65%   |
| AMD 400 Series Chipset SATA Controller                                         | 116       | 3.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 90        | 2.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 82        | 2.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 71        | 2.18%   |
| AMD 500 Series Chipset SATA Controller                                         | 69        | 2.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 65        | 1.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 65        | 1.99%   |
| Samsung NVMe SSD Controller 980                                                | 60        | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 58        | 1.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 57        | 1.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 51        | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 51        | 1.56%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 51        | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 48        | 1.47%   |
| Phison E12 NVMe Controller                                                     | 46        | 1.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 43        | 1.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 41        | 1.26%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 40        | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 36        | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 33        | 1.01%   |
| Intel Volume Management Device NVMe RAID Controller                            | 33        | 1.01%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 32        | 0.98%   |
| Intel SSD 660P Series                                                          | 32        | 0.98%   |
| Intel SATA Controller [RAID mode]                                              | 32        | 0.98%   |
| Phison E16 PCIe4 NVMe Controller                                               | 30        | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 29        | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 29        | 0.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 28        | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 28        | 0.86%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 27        | 0.83%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 26        | 0.8%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 26        | 0.8%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 25        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 23        | 0.71%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 22        | 0.67%   |
| Intel Tiger Lake-LP SATA Controller                                            | 22        | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 22        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1592      | 56.72%  |
| NVMe | 929       | 33.1%   |
| RAID | 167       | 5.95%   |
| IDE  | 113       | 4.03%   |
| SAS  | 4         | 0.14%   |
| SCSI | 2         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1401      | 69.22%  |
| AMD     | 622       | 30.73%  |
| Unknown | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 36        | 1.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 29        | 1.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 27        | 1.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 26        | 1.28%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 24        | 1.18%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 23        | 1.13%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 23        | 1.13%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 23        | 1.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 21        | 1.03%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 21        | 1.03%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 20        | 0.99%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 20        | 0.99%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 19        | 0.94%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 19        | 0.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 17        | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 17        | 0.84%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 17        | 0.84%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 16        | 0.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 16        | 0.79%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 16        | 0.79%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 16        | 0.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 14        | 0.69%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 14        | 0.69%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 14        | 0.69%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 13        | 0.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 13        | 0.64%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 13        | 0.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 12        | 0.59%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 12        | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 12        | 0.59%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 12        | 0.59%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 12        | 0.59%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 12        | 0.59%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 12        | 0.59%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 12        | 0.59%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 11        | 0.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 11        | 0.54%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 11        | 0.54%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 11        | 0.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 11        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 483       | 23.8%   |
| Intel Core i7           | 455       | 22.42%  |
| AMD Ryzen 5             | 200       | 9.86%   |
| AMD Ryzen 7             | 176       | 8.67%   |
| Other                   | 117       | 5.77%   |
| Intel Core i3           | 109       | 5.37%   |
| AMD Ryzen 9             | 77        | 3.79%   |
| Intel Xeon              | 47        | 2.32%   |
| Intel Celeron           | 45        | 2.22%   |
| Intel Pentium           | 43        | 2.12%   |
| AMD Ryzen 3             | 42        | 2.07%   |
| Intel Core 2 Duo        | 28        | 1.38%   |
| Intel Core i9           | 25        | 1.23%   |
| Intel Atom              | 23        | 1.13%   |
| AMD FX                  | 23        | 1.13%   |
| AMD A6                  | 13        | 0.64%   |
| AMD A10                 | 12        | 0.59%   |
| AMD Ryzen 7 PRO         | 9         | 0.44%   |
| Intel Pentium Dual-Core | 7         | 0.34%   |
| AMD Phenom II X4        | 7         | 0.34%   |
| AMD A8                  | 7         | 0.34%   |
| AMD A4                  | 7         | 0.34%   |
| AMD Ryzen Threadripper  | 6         | 0.3%    |
| AMD A12                 | 6         | 0.3%    |
| Intel Pentium Silver    | 5         | 0.25%   |
| Intel Pentium Dual      | 5         | 0.25%   |
| Intel Core 2 Quad       | 5         | 0.25%   |
| Intel Core 2            | 4         | 0.2%    |
| AMD Ryzen 5 PRO         | 4         | 0.2%    |
| AMD Athlon 64 X2        | 4         | 0.2%    |
| AMD Athlon              | 4         | 0.2%    |
| Intel Xeon Silver       | 3         | 0.15%   |
| Intel Core m3           | 3         | 0.15%   |
| AMD E2                  | 3         | 0.15%   |
| AMD E1                  | 3         | 0.15%   |
| AMD Athlon II X2        | 3         | 0.15%   |
| Intel Pentium Gold      | 2         | 0.1%    |
| Intel Genuine           | 2         | 0.1%    |
| AMD Phenom II X6        | 2         | 0.1%    |
| Intel Pentium 4         | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 715       | 35.22%  |
| 2       | 586       | 28.87%  |
| 6       | 334       | 16.45%  |
| 8       | 257       | 12.66%  |
| 12      | 55        | 2.71%   |
| 16      | 27        | 1.33%   |
| 10      | 18        | 0.89%   |
| 1       | 12        | 0.59%   |
| 3       | 11        | 0.54%   |
| 14      | 8         | 0.39%   |
| 24      | 3         | 0.15%   |
| 40      | 1         | 0.05%   |
| 32      | 1         | 0.05%   |
| 18      | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2020      | 99.75%  |
| 2       | 4         | 0.2%    |
| Unknown | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1591      | 78.53%  |
| 1       | 434       | 21.42%  |
| Unknown | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2017      | 99.65%  |
| Unknown        | 7         | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 492       | 23.37%  |
| 0x306c3    | 93        | 4.42%   |
| 0x906ea    | 91        | 4.32%   |
| 0x306a9    | 88        | 4.18%   |
| 0x206a7    | 78        | 3.71%   |
| 0x08701021 | 73        | 3.47%   |
| 0x906e9    | 60        | 2.85%   |
| 0x806ea    | 50        | 2.38%   |
| 0x806e9    | 48        | 2.28%   |
| 0x506e3    | 48        | 2.28%   |
| 0x0800820d | 45        | 2.14%   |
| 0x406e3    | 43        | 2.04%   |
| 0x0a50000c | 42        | 2%      |
| 0x0a201016 | 37        | 1.76%   |
| 0x806ec    | 34        | 1.62%   |
| 0x40651    | 34        | 1.62%   |
| 0x806c1    | 33        | 1.57%   |
| 0x08108109 | 33        | 1.57%   |
| 0x08600106 | 31        | 1.47%   |
| 0x306d4    | 28        | 1.33%   |
| 0xa0652    | 24        | 1.14%   |
| 0x08108102 | 24        | 1.14%   |
| 0x20655    | 23        | 1.09%   |
| 0x08701013 | 23        | 1.09%   |
| 0x1067a    | 22        | 1.05%   |
| 0x0a201009 | 22        | 1.05%   |
| 0x08608103 | 20        | 0.95%   |
| 0x706e5    | 15        | 0.71%   |
| 0xa0655    | 14        | 0.67%   |
| 0x0a50000d | 14        | 0.67%   |
| 0x806eb    | 12        | 0.57%   |
| 0x106e5    | 12        | 0.57%   |
| 0x08101016 | 12        | 0.57%   |
| 0x0810100b | 12        | 0.57%   |
| 0xa0653    | 11        | 0.52%   |
| 0x30678    | 11        | 0.52%   |
| 0x0a20120a | 11        | 0.52%   |
| 0x08600103 | 11        | 0.52%   |
| 0x06006705 | 11        | 0.52%   |
| 0x906ed    | 10        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 427       | 21.03%  |
| Haswell          | 181       | 8.92%   |
| Zen 2            | 165       | 8.13%   |
| Zen 3            | 153       | 7.54%   |
| IvyBridge        | 139       | 6.85%   |
| Skylake          | 127       | 6.26%   |
| Zen+             | 115       | 5.67%   |
| SandyBridge      | 105       | 5.17%   |
| CometLake        | 66        | 3.25%   |
| TigerLake        | 50        | 2.46%   |
| Zen              | 47        | 2.32%   |
| Westmere         | 43        | 2.12%   |
| Broadwell        | 43        | 2.12%   |
| Unknown          | 42        | 2.07%   |
| Icelake          | 37        | 1.82%   |
| Penryn           | 35        | 1.72%   |
| Alderlake Hybrid | 35        | 1.72%   |
| Silvermont       | 34        | 1.67%   |
| Excavator        | 32        | 1.58%   |
| Piledriver       | 29        | 1.43%   |
| Goldmont plus    | 20        | 0.99%   |
| Goldmont         | 18        | 0.89%   |
| K10              | 17        | 0.84%   |
| Nehalem          | 16        | 0.79%   |
| Core             | 16        | 0.79%   |
| Steamroller      | 8         | 0.39%   |
| K8 Hammer        | 6         | 0.3%    |
| Puma             | 5         | 0.25%   |
| Jaguar           | 5         | 0.25%   |
| Tremont          | 3         | 0.15%   |
| Bulldozer        | 3         | 0.15%   |
| Bonnell          | 3         | 0.15%   |
| Bobcat           | 2         | 0.1%    |
| NetBurst         | 1         | 0.05%   |
| K8 & K10 hybrid  | 1         | 0.05%   |
| K10 Llano        | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1054      | 42.62%  |
| Nvidia                     | 815       | 32.96%  |
| AMD                        | 587       | 23.74%  |
| ASPEED Technology          | 15        | 0.61%   |
| Matrox Electronics Systems | 1         | 0.04%   |
| ATI Technologies           | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 80        | 3.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 76        | 3%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 66        | 2.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 66        | 2.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 63        | 2.49%   |
| Intel HD Graphics 620                                                                    | 59        | 2.33%   |
| Intel UHD Graphics 620                                                                   | 56        | 2.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 52        | 2.05%   |
| AMD Renoir                                                                               | 50        | 1.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 49        | 1.94%   |
| Intel HD Graphics 630                                                                    | 48        | 1.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 45        | 1.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 44        | 1.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 39        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 38        | 1.5%    |
| Intel HD Graphics 530                                                                    | 37        | 1.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 33        | 1.3%    |
| Intel HD Graphics 5500                                                                   | 33        | 1.3%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 33        | 1.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 30        | 1.19%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 29        | 1.15%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 29        | 1.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.11%   |
| AMD Lucienne                                                                             | 26        | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 25        | 0.99%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 25        | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 23        | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 22        | 0.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 21        | 0.83%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 20        | 0.79%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 19        | 0.75%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 19        | 0.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 19        | 0.75%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 17        | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 0.67%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 16        | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 16        | 0.63%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 16        | 0.63%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 16        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 650       | 31.82%  |
| 1 x AMD        | 464       | 22.71%  |
| 1 x Nvidia     | 447       | 21.88%  |
| Intel + Nvidia | 325       | 15.91%  |
| Intel + AMD    | 49        | 2.4%    |
| AMD + Nvidia   | 42        | 2.06%   |
| 2 x AMD        | 35        | 1.71%   |
| 1 x ASPEED     | 14        | 0.69%   |
| 2 x Intel      | 8         | 0.39%   |
| 2 x Nvidia     | 4         | 0.2%    |
| Other          | 3         | 0.15%   |
| 1 x Matrox     | 1         | 0.05%   |
| AMD + ASPEED   | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1440      | 70.24%  |
| Proprietary | 558       | 27.22%  |
| Unknown     | 52        | 2.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1046      | 50.51%  |
| 1.01-2.0   | 197       | 9.51%   |
| 7.01-8.0   | 185       | 8.93%   |
| 0.01-0.5   | 172       | 8.31%   |
| 3.01-4.0   | 165       | 7.97%   |
| 5.01-6.0   | 91        | 4.39%   |
| 0.51-1.0   | 91        | 4.39%   |
| 8.01-16.0  | 90        | 4.35%   |
| 2.01-3.0   | 24        | 1.16%   |
| 16.01-24.0 | 8         | 0.39%   |
| 4.01-5.0   | 2         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 272       | 11.45%  |
| AU Optronics            | 219       | 9.22%   |
| LG Display              | 210       | 8.84%   |
| BOE                     | 187       | 7.87%   |
| Chimei Innolux          | 183       | 7.71%   |
| Dell                    | 173       | 7.28%   |
| Goldstar                | 157       | 6.61%   |
| Acer                    | 94        | 3.96%   |
| AOC                     | 76        | 3.2%    |
| BenQ                    | 74        | 3.12%   |
| Hewlett-Packard         | 71        | 2.99%   |
| Ancor Communications    | 70        | 2.95%   |
| Sharp                   | 44        | 1.85%   |
| Philips                 | 40        | 1.68%   |
| Apple                   | 40        | 1.68%   |
| Lenovo                  | 34        | 1.43%   |
| ASUSTek Computer        | 33        | 1.39%   |
| ViewSonic               | 27        | 1.14%   |
| PANDA                   | 26        | 1.09%   |
| Sony                    | 25        | 1.05%   |
| MSI                     | 23        | 0.97%   |
| Iiyama                  | 21        | 0.88%   |
| Chi Mei Optoelectronics | 18        | 0.76%   |
| Eizo                    | 16        | 0.67%   |
| CSO                     | 15        | 0.63%   |
| Vizio                   | 12        | 0.51%   |
| Sceptre Tech            | 12        | 0.51%   |
| Unknown                 | 11        | 0.46%   |
| Panasonic               | 10        | 0.42%   |
| LG Electronics          | 10        | 0.42%   |
| InfoVision              | 10        | 0.42%   |
| Toshiba                 | 9         | 0.38%   |
| Unknown                 | 9         | 0.38%   |
| HannStar                | 8         | 0.34%   |
| Gigabyte Technology     | 8         | 0.34%   |
| Vestel Elektronik       | 5         | 0.21%   |
| VIE                     | 4         | 0.17%   |
| MStar                   | 4         | 0.17%   |
| Microstep               | 4         | 0.17%   |
| Fujitsu Siemens         | 4         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 14        | 0.57%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 12        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 12        | 0.49%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 11        | 0.45%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9         | 0.36%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 9         | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 9         | 0.36%   |
| Unknown                                                               | 9         | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 8         | 0.32%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 8         | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 8         | 0.32%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 8         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 7         | 0.28%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 7         | 0.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.28%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch            | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 7         | 0.28%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 7         | 0.28%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 6         | 0.24%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 6         | 0.24%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 6         | 0.24%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 6         | 0.24%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                      | 6         | 0.24%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 6         | 0.24%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 6         | 0.24%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 5         | 0.2%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 5         | 0.2%    |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 5         | 0.2%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.2%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 5         | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 5         | 0.2%    |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 5         | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 5         | 0.2%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 5         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1094      | 48.88%  |
| 1366x768 (WXGA)    | 306       | 13.67%  |
| 2560x1440 (QHD)    | 188       | 8.4%    |
| 3840x2160 (4K)     | 159       | 7.1%    |
| 1600x900 (HD+)     | 67        | 2.99%   |
| 2560x1080          | 47        | 2.1%    |
| 1920x1200 (WUXGA)  | 43        | 1.92%   |
| 1680x1050 (WSXGA+) | 42        | 1.88%   |
| 1440x900 (WXGA+)   | 39        | 1.74%   |
| 1280x1024 (SXGA)   | 37        | 1.65%   |
| 3440x1440          | 33        | 1.47%   |
| 1280x800 (WXGA)    | 27        | 1.21%   |
| Unknown            | 18        | 0.8%    |
| 3840x1080          | 17        | 0.76%   |
| 2880x1800          | 16        | 0.71%   |
| 1360x768           | 16        | 0.71%   |
| 2560x1600          | 14        | 0.63%   |
| 2160x1440          | 10        | 0.45%   |
| 1920x540           | 10        | 0.45%   |
| 1600x1200          | 7         | 0.31%   |
| 3840x2400          | 6         | 0.27%   |
| 3200x1800 (QHD+)   | 6         | 0.27%   |
| 3840x1600          | 5         | 0.22%   |
| 2288x1287          | 2         | 0.09%   |
| 2160x1350          | 2         | 0.09%   |
| 2048x1152          | 2         | 0.09%   |
| 1024x768 (XGA)     | 2         | 0.09%   |
| 1024x600           | 2         | 0.09%   |
| 7280x1440          | 1         | 0.04%   |
| 6400x1440          | 1         | 0.04%   |
| 5760x2160          | 1         | 0.04%   |
| 5520x1080          | 1         | 0.04%   |
| 5360x1440          | 1         | 0.04%   |
| 480x1920           | 1         | 0.04%   |
| 4096x2160          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3840x1100          | 1         | 0.04%   |
| 3520x1080          | 1         | 0.04%   |
| 3286x1080          | 1         | 0.04%   |
| 3280x1080          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 540       | 22.84%  |
| 27      | 241       | 10.19%  |
| 24      | 209       | 8.84%   |
| 14      | 175       | 7.4%    |
| 13      | 163       | 6.9%    |
| 23      | 157       | 6.64%   |
| 21      | 148       | 6.26%   |
| 17      | 117       | 4.95%   |
| 31      | 87        | 3.68%   |
| Unknown | 81        | 3.43%   |
| 34      | 67        | 2.83%   |
| 12      | 41        | 1.73%   |
| 19      | 40        | 1.69%   |
| 18      | 39        | 1.65%   |
| 22      | 32        | 1.35%   |
| 20      | 21        | 0.89%   |
| 84      | 19        | 0.8%    |
| 72      | 18        | 0.76%   |
| 32      | 17        | 0.72%   |
| 54      | 15        | 0.63%   |
| 40      | 15        | 0.63%   |
| 16      | 15        | 0.63%   |
| 28      | 11        | 0.47%   |
| 25      | 11        | 0.47%   |
| 11      | 10        | 0.42%   |
| 26      | 9         | 0.38%   |
| 48      | 6         | 0.25%   |
| 52      | 5         | 0.21%   |
| 49      | 5         | 0.21%   |
| 39      | 5         | 0.21%   |
| 10      | 5         | 0.21%   |
| 65      | 4         | 0.17%   |
| 43      | 4         | 0.17%   |
| 42      | 4         | 0.17%   |
| 37      | 4         | 0.17%   |
| 35      | 4         | 0.17%   |
| 29      | 4         | 0.17%   |
| 46      | 3         | 0.13%   |
| 74      | 2         | 0.08%   |
| 36      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 804       | 34.94%  |
| 501-600        | 556       | 24.16%  |
| 401-500        | 255       | 11.08%  |
| 201-300        | 148       | 6.43%   |
| 351-400        | 126       | 5.48%   |
| 601-700        | 124       | 5.39%   |
| 701-800        | 87        | 3.78%   |
| Unknown        | 81        | 3.52%   |
| 1001-1500      | 41        | 1.78%   |
| 1501-2000      | 39        | 1.69%   |
| 801-900        | 30        | 1.3%    |
| 901-1000       | 9         | 0.39%   |
| More than 2000 | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1648      | 78.89%  |
| 16/10   | 202       | 9.67%   |
| 21/9    | 86        | 4.12%   |
| Unknown | 64        | 3.06%   |
| 5/4     | 33        | 1.58%   |
| 3/2     | 22        | 1.05%   |
| 4/3     | 17        | 0.81%   |
| 32/9    | 8         | 0.38%   |
| 6/5     | 4         | 0.19%   |
| 3.40    | 1         | 0.05%   |
| 2.00    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |
| 0.80    | 1         | 0.05%   |
| 0.25    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 532       | 22.77%  |
| 201-250        | 448       | 19.18%  |
| 81-90          | 272       | 11.64%  |
| 301-350        | 247       | 10.57%  |
| 351-500        | 180       | 7.71%   |
| 121-130        | 94        | 4.02%   |
| 151-200        | 91        | 3.9%    |
| Unknown        | 81        | 3.47%   |
| 251-300        | 77        | 3.3%    |
| More than 1000 | 69        | 2.95%   |
| 71-80          | 65        | 2.78%   |
| 141-150        | 52        | 2.23%   |
| 501-1000       | 45        | 1.93%   |
| 61-70          | 37        | 1.58%   |
| 51-60          | 12        | 0.51%   |
| 111-120        | 12        | 0.51%   |
| 131-140        | 9         | 0.39%   |
| 91-100         | 9         | 0.39%   |
| 41-50          | 4         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 752       | 33.63%  |
| 121-160       | 630       | 28.18%  |
| 101-120       | 546       | 24.42%  |
| 161-240       | 124       | 5.55%   |
| Unknown       | 81        | 3.62%   |
| 1-50          | 54        | 2.42%   |
| More than 240 | 49        | 2.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1517      | 73.18%  |
| 2     | 435       | 20.98%  |
| 0     | 64        | 3.09%   |
| 3     | 53        | 2.56%   |
| 4     | 4         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1142      | 38.25%  |
| Intel                             | 1131      | 37.88%  |
| Qualcomm Atheros                  | 292       | 9.78%   |
| Broadcom                          | 112       | 3.75%   |
| MediaTek                          | 39        | 1.31%   |
| Ralink Technology                 | 27        | 0.9%    |
| TP-Link                           | 24        | 0.8%    |
| Broadcom Limited                  | 24        | 0.8%    |
| Nvidia                            | 13        | 0.44%   |
| Marvell Technology Group          | 13        | 0.44%   |
| ASIX Electronics                  | 13        | 0.44%   |
| Sierra Wireless                   | 11        | 0.37%   |
| Ralink                            | 10        | 0.33%   |
| Microsoft                         | 10        | 0.33%   |
| Samsung Electronics               | 9         | 0.3%    |
| DisplayLink                       | 8         | 0.27%   |
| Dell                              | 8         | 0.27%   |
| Aquantia                          | 8         | 0.27%   |
| Qualcomm                          | 7         | 0.23%   |
| Ericsson Business Mobile Networks | 6         | 0.2%    |
| D-Link System                     | 6         | 0.2%    |
| Qualcomm Atheros Communications   | 5         | 0.17%   |
| Lenovo                            | 5         | 0.17%   |
| Huawei Technologies               | 5         | 0.17%   |
| Xiaomi                            | 4         | 0.13%   |
| NetGear                           | 4         | 0.13%   |
| Insyde Software                   | 4         | 0.13%   |
| Hewlett-Packard                   | 4         | 0.13%   |
| JMicron Technology                | 3         | 0.1%    |
| Fibocom                           | 3         | 0.1%    |
| D-Link                            | 3         | 0.1%    |
| T & A Mobile Phones               | 2         | 0.07%   |
| Oculus VR                         | 2         | 0.07%   |
| Motorola PCS                      | 2         | 0.07%   |
| Emulex                            | 2         | 0.07%   |
| ASUSTek Computer                  | 2         | 0.07%   |
| vivo                              | 1         | 0.03%   |
| VIA Technologies                  | 1         | 0.03%   |
| U-Blox                            | 1         | 0.03%   |
| Tenda                             | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 839       | 23.43%  |
| Intel Wi-Fi 6 AX200                                               | 168       | 4.69%   |
| Intel I211 Gigabit Network Connection                             | 100       | 2.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 94        | 2.62%   |
| Intel Wireless 8265 / 8275                                        | 70        | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 69        | 1.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69        | 1.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 67        | 1.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 57        | 1.59%   |
| Intel Wireless 7260                                               | 54        | 1.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 53        | 1.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 52        | 1.45%   |
| Intel Ethernet Connection (2) I219-V                              | 52        | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 46        | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 44        | 1.23%   |
| Intel Ethernet Controller I225-V                                  | 43        | 1.2%    |
| Intel Wireless 8260                                               | 42        | 1.17%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 1.06%   |
| Intel Wireless-AC 9260                                            | 37        | 1.03%   |
| Intel Wireless 7265                                               | 37        | 1.03%   |
| Intel Wi-Fi 6 AX201                                               | 36        | 1.01%   |
| Intel Ethernet Connection (7) I219-V                              | 36        | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 36        | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 35        | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 34        | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 33        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 32        | 0.89%   |
| Intel Wireless 3165                                               | 31        | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 22        | 0.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 21        | 0.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 19        | 0.53%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 19        | 0.53%   |
| Intel Wireless 3160                                               | 18        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 0.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 17        | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 17        | 0.47%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 16        | 0.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 16        | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 16        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 863       | 53.87%  |
| Realtek Semiconductor                 | 256       | 15.98%  |
| Qualcomm Atheros                      | 229       | 14.29%  |
| Broadcom                              | 81        | 5.06%   |
| MediaTek                              | 39        | 2.43%   |
| Ralink Technology                     | 27        | 1.69%   |
| TP-Link                               | 21        | 1.31%   |
| Broadcom Limited                      | 18        | 1.12%   |
| Sierra Wireless                       | 11        | 0.69%   |
| Ralink                                | 10        | 0.62%   |
| Microsoft                             | 10        | 0.62%   |
| Qualcomm Atheros Communications       | 5         | 0.31%   |
| NetGear                               | 4         | 0.25%   |
| Dell                                  | 4         | 0.25%   |
| Marvell Technology Group              | 3         | 0.19%   |
| Fibocom                               | 3         | 0.19%   |
| D-Link System                         | 3         | 0.19%   |
| D-Link                                | 3         | 0.19%   |
| Hewlett-Packard                       | 2         | 0.12%   |
| Ericsson Business Mobile Networks     | 2         | 0.12%   |
| ASUSTek Computer                      | 2         | 0.12%   |
| Xiaomi                                | 1         | 0.06%   |
| Ovislink                              | 1         | 0.06%   |
| IMC Networks                          | 1         | 0.06%   |
| Edimax Technology                     | 1         | 0.06%   |
| CyberTAN Technology                   | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 168       | 10.42%  |
| Intel Wireless 8265 / 8275                                     | 70        | 4.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 69        | 4.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 57        | 3.54%   |
| Intel Wireless 7260                                            | 54        | 3.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 53        | 3.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 46        | 2.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 44        | 2.73%   |
| Intel Wireless 8260                                            | 42        | 2.61%   |
| Intel Wireless-AC 9260                                         | 37        | 2.3%    |
| Intel Wireless 7265                                            | 37        | 2.3%    |
| Intel Wi-Fi 6 AX201                                            | 36        | 2.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 36        | 2.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 35        | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 34        | 2.11%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 33        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 32        | 1.99%   |
| Intel Wireless 3165                                            | 31        | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 22        | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 21        | 1.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 19        | 1.18%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 19        | 1.18%   |
| Intel Wireless 3160                                            | 18        | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 17        | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 17        | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 16        | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16        | 0.99%   |
| Intel Centrino Ultimate-N 6300                                 | 16        | 0.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 15        | 0.93%   |
| Ralink MT7601U Wireless Adapter                                | 14        | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 14        | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 13        | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 13        | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 0.81%   |
| Intel Centrino Advanced-N 6200                                 | 13        | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12        | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 12        | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 12        | 0.74%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 12        | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 11        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1049      | 55.5%   |
| Intel                                  | 591       | 31.27%  |
| Qualcomm Atheros                       | 89        | 4.71%   |
| Broadcom                               | 51        | 2.7%    |
| Nvidia                                 | 13        | 0.69%   |
| ASIX Electronics                       | 13        | 0.69%   |
| Marvell Technology Group               | 10        | 0.53%   |
| DisplayLink                            | 8         | 0.42%   |
| Aquantia                               | 8         | 0.42%   |
| Qualcomm                               | 7         | 0.37%   |
| Broadcom Limited                       | 6         | 0.32%   |
| Samsung Electronics                    | 5         | 0.26%   |
| Lenovo                                 | 4         | 0.21%   |
| Insyde Software                        | 4         | 0.21%   |
| Xiaomi                                 | 3         | 0.16%   |
| TP-Link                                | 3         | 0.16%   |
| JMicron Technology                     | 3         | 0.16%   |
| Huawei Technologies                    | 3         | 0.16%   |
| D-Link System                          | 3         | 0.16%   |
| T & A Mobile Phones                    | 2         | 0.11%   |
| Motorola PCS                           | 2         | 0.11%   |
| Emulex                                 | 2         | 0.11%   |
| VIA Technologies                       | 1         | 0.05%   |
| Tenda                                  | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Solarflare Communications              | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.05%   |
| Novatel Wireless                       | 1         | 0.05%   |
| MediaTek                               | 1         | 0.05%   |
| ICS Advent                             | 1         | 0.05%   |
| Google                                 | 1         | 0.05%   |
| Apple                                  | 1         | 0.05%   |
| 3Com                                   | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 839       | 43.2%   |
| Intel I211 Gigabit Network Connection                             | 100       | 5.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 94        | 4.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69        | 3.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 67        | 3.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 52        | 2.68%   |
| Intel Ethernet Connection (2) I219-V                              | 52        | 2.68%   |
| Intel Ethernet Controller I225-V                                  | 43        | 2.21%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 1.96%   |
| Intel Ethernet Connection (7) I219-V                              | 36        | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 0.93%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.88%   |
| Intel Ethernet Connection I217-V                                  | 16        | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 15        | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 14        | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 11        | 0.57%   |
| Intel I210 Gigabit Network Connection                             | 11        | 0.57%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 10        | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 0.51%   |
| Intel Ethernet Connection X553 1GbE                               | 10        | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                             | 9         | 0.46%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 9         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.41%   |
| Intel Ethernet Connection I219-V                                  | 8         | 0.41%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 8         | 0.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 0.36%   |
| Intel Ethernet Connection (6) I219-V                              | 7         | 0.36%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.31%   |
| Intel Ethernet Connection (12) I219-V                             | 6         | 0.31%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1784      | 53.33%  |
| WiFi     | 1534      | 45.86%  |
| Modem    | 25        | 0.75%   |
| Unknown  | 2         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1147      | 53.93%  |
| Ethernet | 980       | 46.07%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1137      | 55.93%  |
| 1     | 797       | 39.2%   |
| 3     | 65        | 3.2%    |
| 4     | 20        | 0.98%   |
| 0     | 11        | 0.54%   |
| 5     | 2         | 0.1%    |
| 9     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1557      | 75.18%  |
| Yes  | 514       | 24.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 743       | 52.47%  |
| Realtek Semiconductor           | 141       | 9.96%   |
| Qualcomm Atheros Communications | 101       | 7.13%   |
| Cambridge Silicon Radio         | 90        | 6.36%   |
| IMC Networks                    | 64        | 4.52%   |
| Broadcom                        | 53        | 3.74%   |
| Apple                           | 51        | 3.6%    |
| Lite-On Technology              | 38        | 2.68%   |
| ASUSTek Computer                | 38        | 2.68%   |
| Foxconn / Hon Hai               | 32        | 2.26%   |
| MediaTek                        | 14        | 0.99%   |
| Dell                            | 9         | 0.64%   |
| Toshiba                         | 6         | 0.42%   |
| Realtek                         | 6         | 0.42%   |
| TP-Link                         | 5         | 0.35%   |
| Belkin Components               | 4         | 0.28%   |
| Edimax Technology               | 3         | 0.21%   |
| Dynex                           | 3         | 0.21%   |
| Ralink Technology               | 2         | 0.14%   |
| Ralink                          | 2         | 0.14%   |
| Marvell Semiconductor           | 2         | 0.14%   |
| HTC (High Tech Computer)        | 2         | 0.14%   |
| Hewlett-Packard                 | 2         | 0.14%   |
| SINO WEALTH                     | 1         | 0.07%   |
| Opticis                         | 1         | 0.07%   |
| Creative Technology             | 1         | 0.07%   |
| Chicony Electronics             | 1         | 0.07%   |
| Actions                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 244       | 17.21%  |
| Intel AX200 Bluetooth                               | 162       | 11.42%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 102       | 7.19%   |
| Intel AX201 Bluetooth                               | 98        | 6.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 90        | 6.35%   |
| Realtek Bluetooth Radio                             | 82        | 5.78%   |
| Qualcomm Atheros  Bluetooth Device                  | 66        | 4.65%   |
| Intel Wireless-AC 3168 Bluetooth                    | 43        | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 39        | 2.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 38        | 2.68%   |
| Apple Bluetooth USB Host Controller                 | 25        | 1.76%   |
| IMC Networks Bluetooth Radio                        | 21        | 1.48%   |
| Apple Bluetooth Host Controller                     | 20        | 1.41%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 1.34%   |
| IMC Networks Bluetooth Device                       | 19        | 1.34%   |
| Broadcom BCM2045B (BDC-2.1)                         | 17        | 1.2%    |
| Intel Bluetooth Device                              | 15        | 1.06%   |
| Lite-On Bluetooth Device                            | 14        | 0.99%   |
| Intel AX210 Bluetooth                               | 14        | 0.99%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 14        | 0.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 0.92%   |
| MediaTek Wireless_Device                            | 13        | 0.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 0.92%   |
| IMC Networks Wireless_Device                        | 13        | 0.92%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 13        | 0.92%   |
| ASUS ASUS USB-BT500                                 | 11        | 0.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.71%   |
| Realtek RTL8821A Bluetooth                          | 9         | 0.63%   |
| Foxconn / Hon Hai Bluetooth Device                  | 9         | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.49%   |
| Realtek 802.11ac WLAN Adapter                       | 6         | 0.42%   |
| Dell BCM20702A0 Bluetooth Module                    | 6         | 0.42%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.42%   |
| TP-Link UB500 Adapter                               | 5         | 0.35%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 0.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.28%   |
| Realtek RTL8723B Bluetooth                          | 4         | 0.28%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 4         | 0.28%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 4         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1357      | 42.29%  |
| AMD                                  | 730       | 22.75%  |
| Nvidia                               | 656       | 20.44%  |
| C-Media Electronics                  | 70        | 2.18%   |
| Logitech                             | 48        | 1.5%    |
| Texas Instruments                    | 27        | 0.84%   |
| Kingston Technology                  | 26        | 0.81%   |
| Razer USA                            | 17        | 0.53%   |
| JMTek                                | 17        | 0.53%   |
| Focusrite-Novation                   | 16        | 0.5%    |
| Corsair                              | 14        | 0.44%   |
| Realtek Semiconductor                | 12        | 0.37%   |
| Creative Technology                  | 12        | 0.37%   |
| SteelSeries ApS                      | 11        | 0.34%   |
| Creative Labs                        | 10        | 0.31%   |
| ASUSTek Computer                     | 10        | 0.31%   |
| Generalplus Technology               | 9         | 0.28%   |
| GN Netcom                            | 8         | 0.25%   |
| RODE Microphones                     | 7         | 0.22%   |
| BEHRINGER International              | 7         | 0.22%   |
| SAVITECH                             | 6         | 0.19%   |
| Samson Technologies                  | 6         | 0.19%   |
| DSEA A/S                             | 6         | 0.19%   |
| XMOS                                 | 5         | 0.16%   |
| Sony                                 | 5         | 0.16%   |
| Lenovo                               | 5         | 0.16%   |
| Blue Microphones                     | 5         | 0.16%   |
| Yamaha                               | 4         | 0.12%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.12%   |
| Scarlett                             | 4         | 0.12%   |
| PreSonus Audio Electronics           | 4         | 0.12%   |
| Plantronics                          | 4         | 0.12%   |
| VIA Technologies                     | 3         | 0.09%   |
| Native Instruments                   | 3         | 0.09%   |
| Hewlett-Packard                      | 3         | 0.09%   |
| FIFINE Microphones                   | 3         | 0.09%   |
| Audio-Technica                       | 3         | 0.09%   |
| Asahi Kasei Microsystems             | 3         | 0.09%   |
| Turtle Beach                         | 2         | 0.06%   |
| Project                              | 2         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 249       | 6.54%   |
| AMD Starship/Matisse HD Audio Controller                                   | 187       | 4.91%   |
| Intel Sunrise Point-LP HD Audio                                            | 177       | 4.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 129       | 3.39%   |
| Intel Cannon Lake PCH cAVS                                                 | 128       | 3.36%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 122       | 3.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 107       | 2.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 106       | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 77        | 2.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 76        | 2%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 76        | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 75        | 1.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 66        | 1.73%   |
| Intel 200 Series PCH HD Audio                                              | 65        | 1.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 55        | 1.44%   |
| Nvidia TU106 High Definition Audio Controller                              | 55        | 1.44%   |
| Nvidia GP106 High Definition Audio Controller                              | 55        | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 54        | 1.42%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 54        | 1.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 50        | 1.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 50        | 1.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 49        | 1.29%   |
| Nvidia GP104 High Definition Audio Controller                              | 48        | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 45        | 1.18%   |
| Intel 8 Series HD Audio Controller                                         | 45        | 1.18%   |
| Intel Comet Lake PCH cAVS                                                  | 43        | 1.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 40        | 1.05%   |
| Intel Broadwell-U Audio Controller                                         | 40        | 1.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 38        | 1%      |
| Nvidia GA104 High Definition Audio Controller                              | 36        | 0.95%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 35        | 0.92%   |
| Intel CM238 HD Audio Controller                                            | 34        | 0.89%   |
| AMD Navi 10 HDMI Audio                                                     | 34        | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 32        | 0.84%   |
| Intel Comet Lake PCH-LP cAVS                                               | 30        | 0.79%   |
| Nvidia TU104 HD Audio Controller                                           | 29        | 0.76%   |
| AMD FCH Azalia Controller                                                  | 29        | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 25        | 0.66%   |
| Nvidia GA106 High Definition Audio Controller                              | 25        | 0.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 25        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 455       | 20.64%  |
| SK hynix            | 372       | 16.88%  |
| Kingston            | 230       | 10.44%  |
| Micron Technology   | 214       | 9.71%   |
| Corsair             | 211       | 9.57%   |
| Crucial             | 171       | 7.76%   |
| G.Skill             | 131       | 5.94%   |
| Unknown             | 122       | 5.54%   |
| A-DATA Technology   | 40        | 1.81%   |
| Ramaxel Technology  | 35        | 1.59%   |
| Team                | 31        | 1.41%   |
| Nanya Technology    | 22        | 1%      |
| Elpida              | 19        | 0.86%   |
| Patriot             | 16        | 0.73%   |
| Unknown (ABCD)      | 11        | 0.5%    |
| Unknown             | 11        | 0.5%    |
| GOODRAM             | 10        | 0.45%   |
| Avant               | 7         | 0.32%   |
| Apacer              | 7         | 0.32%   |
| Silicon Power       | 6         | 0.27%   |
| Transcend           | 5         | 0.23%   |
| PNY                 | 5         | 0.23%   |
| Goldkey             | 5         | 0.23%   |
| Neo Forza           | 4         | 0.18%   |
| ASint Technology    | 4         | 0.18%   |
| Smart               | 3         | 0.14%   |
| Kingmax             | 3         | 0.14%   |
| CSX                 | 3         | 0.14%   |
| AMD                 | 3         | 0.14%   |
| Unknown (0x0B5E)    | 2         | 0.09%   |
| Unifosa             | 2         | 0.09%   |
| Timetec             | 2         | 0.09%   |
| Teikon              | 2         | 0.09%   |
| Sesame              | 2         | 0.09%   |
| Lexar               | 2         | 0.09%   |
| GeIL                | 2         | 0.09%   |
| Wodposit            | 1         | 0.05%   |
| V-Color             | 1         | 0.05%   |
| Unknown (8AF1)      | 1         | 0.05%   |
| Unknown (898F)      | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 23        | 0.97%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 23        | 0.97%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 22        | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 21        | 0.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 0.8%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.8%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 19        | 0.8%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 18        | 0.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 0.63%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 15        | 0.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.55%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 13        | 0.55%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.51%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16384MB DIMM DDR4 3200MT/s         | 12        | 0.51%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 12        | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 12        | 0.51%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 12        | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.46%   |
| Unknown                                                          | 11        | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 10        | 0.42%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 10        | 0.42%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s        | 10        | 0.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 0.38%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 9         | 0.38%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 0.34%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 8         | 0.34%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM 1334MT/s                | 8         | 0.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.34%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 8         | 0.34%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.34%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 8         | 0.34%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.3%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 7         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1131      | 60.29%  |
| DDR3    | 549       | 29.26%  |
| LPDDR4  | 42        | 2.24%   |
| LPDDR3  | 39        | 2.08%   |
| Unknown | 31        | 1.65%   |
| DDR5    | 25        | 1.33%   |
| DDR2    | 25        | 1.33%   |
| SDRAM   | 24        | 1.28%   |
| LPDDR5  | 7         | 0.37%   |
| DDR     | 3         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 986       | 52.34%  |
| DIMM         | 787       | 41.77%  |
| Row Of Chips | 98        | 5.2%    |
| Chip         | 10        | 0.53%   |
| RIMM         | 2         | 0.11%   |
| Unknown      | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 932       | 45.11%  |
| 4096  | 522       | 25.27%  |
| 16384 | 367       | 17.76%  |
| 2048  | 136       | 6.58%   |
| 32768 | 84        | 4.07%   |
| 1024  | 19        | 0.92%   |
| 512   | 2         | 0.1%    |
| 49152 | 1         | 0.05%   |
| 12288 | 1         | 0.05%   |
| 64    | 1         | 0.05%   |
| 16    | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 391       | 18.7%   |
| 3200    | 359       | 17.17%  |
| 2667    | 334       | 15.97%  |
| 2400    | 182       | 8.7%    |
| 2133    | 99        | 4.73%   |
| 3600    | 94        | 4.5%    |
| 1333    | 93        | 4.45%   |
| 1334    | 39        | 1.87%   |
| 1867    | 38        | 1.82%   |
| 3733    | 29        | 1.39%   |
| 3000    | 29        | 1.39%   |
| 3400    | 27        | 1.29%   |
| 3266    | 25        | 1.2%    |
| 1067    | 22        | 1.05%   |
| Unknown | 18        | 0.86%   |
| 3800    | 17        | 0.81%   |
| 1866    | 17        | 0.81%   |
| 667     | 17        | 0.81%   |
| 800     | 16        | 0.77%   |
| 4800    | 15        | 0.72%   |
| 4267    | 15        | 0.72%   |
| 3533    | 15        | 0.72%   |
| 1800    | 14        | 0.67%   |
| 3866    | 13        | 0.62%   |
| 2933    | 13        | 0.62%   |
| 2800    | 13        | 0.62%   |
| 3466    | 12        | 0.57%   |
| 2666    | 12        | 0.57%   |
| 3666    | 8         | 0.38%   |
| 4199    | 7         | 0.33%   |
| 8400    | 6         | 0.29%   |
| 6400    | 6         | 0.29%   |
| 3334    | 6         | 0.29%   |
| 5200    | 5         | 0.24%   |
| 4266    | 5         | 0.24%   |
| 3534    | 5         | 0.24%   |
| 3333    | 5         | 0.24%   |
| 2465    | 5         | 0.24%   |
| 2048    | 5         | 0.24%   |
| 1648    | 5         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 17        | 34%     |
| Brother Industries    | 16        | 32%     |
| Canon                 | 6         | 12%     |
| Seiko Epson           | 5         | 10%     |
| Samsung Electronics   | 2         | 4%      |
| MIIIW                 | 1         | 2%      |
| Lexmark International | 1         | 2%      |
| Gprinter              | 1         | 2%      |
| Dymo-CoStar           | 1         | 2%      |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon PIXMA MG3600 Series              | 3         | 5.88%   |
| Seiko Epson ET-4700 Series             | 2         | 3.92%   |
| HP DeskJet F4100 Printer series        | 2         | 3.92%   |
| HP DeskJet 2620 All-in-One Printer     | 2         | 3.92%   |
| Brother Printer                        | 2         | 3.92%   |
| Brother DCP-7055 scanner/printer       | 2         | 3.92%   |
| Seiko Epson XP-240 Series              | 1         | 1.96%   |
| Seiko Epson XP-2100 Series             | 1         | 1.96%   |
| Seiko Epson ET-2710 Series             | 1         | 1.96%   |
| Samsung SCX-3400 Series                | 1         | 1.96%   |
| Samsung SCX-3200 Series                | 1         | 1.96%   |
| MIIIW MW Keyboard Air Mini             | 1         | 1.96%   |
| Lexmark International B2236dw          | 1         | 1.96%   |
| HP PSC 1400                            | 1         | 1.96%   |
| HP OfficeJet Pro 8020 series           | 1         | 1.96%   |
| HP OfficeJet Pro 6960                  | 1         | 1.96%   |
| HP OfficeJet 5200 series               | 1         | 1.96%   |
| HP OfficeJet 4650 series               | 1         | 1.96%   |
| HP LaserJet Professional P1102w        | 1         | 1.96%   |
| HP LaserJet P1005                      | 1         | 1.96%   |
| HP LaserJet M203-M206                  | 1         | 1.96%   |
| HP LaserJet 1015                       | 1         | 1.96%   |
| HP ENVY 4500 series                    | 1         | 1.96%   |
| HP Deskjet 4640 series                 | 1         | 1.96%   |
| HP DeskJet 3700 series                 | 1         | 1.96%   |
| HP DeskJet 2700 series                 | 1         | 1.96%   |
| HP Deskjet 1050 J410                   | 1         | 1.96%   |
| Gprinter GP-58                         | 1         | 1.96%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 1.96%   |
| Canon TS5100 series                    | 1         | 1.96%   |
| Canon G2000 series                     | 1         | 1.96%   |
| Canon CanoScan LiDE 300                | 1         | 1.96%   |
| Brother MFC-L3770CDW series            | 1         | 1.96%   |
| Brother MFC-L3750CDW                   | 1         | 1.96%   |
| Brother MFC-J6545DW                    | 1         | 1.96%   |
| Brother MFC-J497DW                     | 1         | 1.96%   |
| Brother MFC-J485DW                     | 1         | 1.96%   |
| Brother MFC-J450DW                     | 1         | 1.96%   |
| Brother MFC-7460DN                     | 1         | 1.96%   |
| Brother HL-L2300D series               | 1         | 1.96%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 2         | 50%     |
| Hewlett-Packard | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 25%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1         | 25%     |
| HP ScanJet 2400c                                        | 1         | 25%     |
| HP ScanJet 2200c                                        | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 279       | 22.83%  |
| IMC Networks                           | 130       | 10.64%  |
| Logitech                               | 100       | 8.18%   |
| Realtek Semiconductor                  | 92        | 7.53%   |
| Microdia                               | 92        | 7.53%   |
| Sunplus Innovation Technology          | 66        | 5.4%    |
| Bison Electronics                      | 56        | 4.58%   |
| Quanta                                 | 50        | 4.09%   |
| Acer                                   | 48        | 3.93%   |
| Apple                                  | 41        | 3.36%   |
| Cheng Uei Precision Industry (Foxlink) | 36        | 2.95%   |
| Syntek                                 | 28        | 2.29%   |
| Lite-On Technology                     | 24        | 1.96%   |
| Suyin                                  | 22        | 1.8%    |
| Luxvisions Innotech Limited            | 15        | 1.23%   |
| Lenovo                                 | 11        | 0.9%    |
| Silicon Motion                         | 10        | 0.82%   |
| Samsung Electronics                    | 10        | 0.82%   |
| Microsoft                              | 10        | 0.82%   |
| Sonix Technology                       | 8         | 0.65%   |
| Primax Electronics                     | 6         | 0.49%   |
| Generalplus Technology                 | 6         | 0.49%   |
| Alcor Micro                            | 6         | 0.49%   |
| Razer USA                              | 5         | 0.41%   |
| KYE Systems (Mouse Systems)            | 5         | 0.41%   |
| GEMBIRD                                | 5         | 0.41%   |
| Creative Technology                    | 5         | 0.41%   |
| Hewlett-Packard                        | 4         | 0.33%   |
| Z-Star Microelectronics                | 3         | 0.25%   |
| Ricoh                                  | 3         | 0.25%   |
| MacroSilicon                           | 3         | 0.25%   |
| Importek                               | 3         | 0.25%   |
| ARC International                      | 3         | 0.25%   |
| WaveRider Communications               | 2         | 0.16%   |
| Sunplus Technology                     | 2         | 0.16%   |
| Ruision                                | 2         | 0.16%   |
| OPPO Electronics                       | 2         | 0.16%   |
| icSpring                               | 2         | 0.16%   |
| Hopewin Electronic Material            | 2         | 0.16%   |
| Google                                 | 2         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 74        | 6.02%   |
| IMC Networks Integrated Camera                      | 39        | 3.17%   |
| Microdia Integrated_Webcam_HD                       | 37        | 3.01%   |
| Realtek Integrated_Webcam_HD                        | 35        | 2.85%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 32        | 2.6%    |
| Chicony HD WebCam                                   | 28        | 2.28%   |
| Logitech HD Pro Webcam C920                         | 25        | 2.03%   |
| Logitech Webcam C270                                | 22        | 1.79%   |
| Acer Integrated Camera                              | 21        | 1.71%   |
| Sunplus Integrated_Webcam_HD                        | 19        | 1.55%   |
| Syntek Integrated Camera                            | 18        | 1.46%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 17        | 1.38%   |
| Lite-On Integrated Camera                           | 14        | 1.14%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 14        | 1.14%   |
| Chicony USB2.0 Camera                               | 13        | 1.06%   |
| Bison Integrated Camera                             | 13        | 1.06%   |
| Logitech C922 Pro Stream Webcam                     | 12        | 0.98%   |
| Chicony HP Wide Vision HD Camera                    | 12        | 0.98%   |
| Chicony USB2.0 VGA UVC WebCam                       | 11        | 0.9%    |
| Chicony HP Truevision HD                            | 11        | 0.9%    |
| Apple Built-in iSight                               | 11        | 0.9%    |
| Samsung Galaxy series, misc. (MTP mode)             | 10        | 0.81%   |
| Microdia Integrated Webcam                          | 10        | 0.81%   |
| Quanta HP TrueVision HD Camera                      | 9         | 0.73%   |
| Quanta HD Webcam                                    | 9         | 0.73%   |
| Chicony HP HD Camera                                | 9         | 0.73%   |
| Chicony EasyCamera                                  | 9         | 0.73%   |
| Acer BisonCam,NB Pro                                | 9         | 0.73%   |
| Quanta HD User Facing                               | 8         | 0.65%   |
| Microdia USB 2.0 Camera                             | 8         | 0.65%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 8         | 0.65%   |
| Chicony Integrated Camera (1280x720@30)             | 8         | 0.65%   |
| Chicony HP Truevision HD camera                     | 8         | 0.65%   |
| Chicony HD User Facing                              | 8         | 0.65%   |
| Bison BisonCam, NB Pro                              | 8         | 0.65%   |
| Apple FaceTime HD Camera (Built-in)                 | 8         | 0.65%   |
| Realtek Integrated Webcam HD                        | 7         | 0.57%   |
| Chicony USB2.0 HD UVC WebCam                        | 7         | 0.57%   |
| Chicony TOSHIBA Web Camera - HD                     | 7         | 0.57%   |
| Bison EasyCamera                                    | 7         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 79        | 38.54%  |
| Synaptics                  | 51        | 24.88%  |
| Shenzhen Goodix Technology | 32        | 15.61%  |
| Elan Microelectronics      | 14        | 6.83%   |
| Upek                       | 11        | 5.37%   |
| LighTuning Technology      | 10        | 4.88%   |
| AuthenTec                  | 6         | 2.93%   |
| STMicroelectronics         | 1         | 0.49%   |
| DigitalPersona             | 1         | 0.49%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 20        | 9.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 19        | 9.27%   |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 7.32%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 5.85%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 5.37%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 5.37%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 4.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 4.39%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 3.41%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 3.41%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 3.41%   |
| Elan ELAN:Fingerprint                                                      | 7         | 3.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.93%   |
| Synaptics  WBDI                                                            | 6         | 2.93%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 2.44%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 2.44%   |
| Elan ELAN:ARM-M4                                                           | 5         | 2.44%   |
| Synaptics UWP WBDI                                                         | 4         | 1.95%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.46%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.46%   |
| Validity Sensors VFS491                                                    | 2         | 0.98%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.98%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.98%   |
| Synaptics WBDI Device                                                      | 2         | 0.98%   |
| Synaptics WBDI                                                             | 2         | 0.98%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.98%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 0.98%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.98%   |
| AuthenTec AES1600                                                          | 2         | 0.98%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.49%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.49%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.49%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.49%   |
| Synaptics Fingerprint scanner                                              | 1         | 0.49%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.49%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.49%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.49%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.49%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.49%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 36        | 39.13%  |
| Broadcom              | 34        | 36.96%  |
| O2 Micro              | 6         | 6.52%   |
| Upek                  | 5         | 5.43%   |
| Lenovo                | 4         | 4.35%   |
| Gemalto (was Gemplus) | 2         | 2.17%   |
| Yubico.com            | 1         | 1.09%   |
| SCM Microsystems      | 1         | 1.09%   |
| OmniKey               | 1         | 1.09%   |
| Clay Logic            | 1         | 1.09%   |
| Cherry                | 1         | 1.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 36        | 39.13%  |
| Broadcom 5880                                                                | 12        | 13.04%  |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 8.7%    |
| Broadcom 58200                                                               | 7         | 7.61%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 6.52%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 5.43%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 5.43%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.35%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 2.17%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 1.09%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 1.09%   |
| OmniKey CardMan 1021                                                         | 1         | 1.09%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.09%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.09%   |
| Cherry Smart Card Reader USB                                                 | 1         | 1.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1519      | 73.42%  |
| 1     | 442       | 21.36%  |
| 2     | 99        | 4.78%   |
| 3     | 5         | 0.24%   |
| 4     | 4         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 205       | 31.88%  |
| Graphics card            | 168       | 26.13%  |
| Chipcard                 | 88        | 13.69%  |
| Net/wireless             | 56        | 8.71%   |
| Multimedia controller    | 30        | 4.67%   |
| Camera                   | 30        | 4.67%   |
| Unassigned class         | 17        | 2.64%   |
| Communication controller | 16        | 2.49%   |
| Bluetooth                | 10        | 1.56%   |
| Network                  | 5         | 0.78%   |
| Net/ethernet             | 5         | 0.78%   |
| Card reader              | 3         | 0.47%   |
| Storage/nvme             | 2         | 0.31%   |
| Storage                  | 2         | 0.31%   |
| Modem                    | 2         | 0.31%   |
| Dvb card                 | 2         | 0.31%   |
| Wireless                 | 1         | 0.16%   |
| Sound                    | 1         | 0.16%   |

