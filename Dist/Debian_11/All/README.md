Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro10,1              | Notebook    | [1ff67401db](https://linux-hardware.org/?probe=1ff67401db) | Sep 09, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [7add887914](https://linux-hardware.org/?probe=7add887914) | Sep 08, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5c6f3696b2](https://linux-hardware.org/?probe=5c6f3696b2) | Sep 08, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [0baa540bf5](https://linux-hardware.org/?probe=0baa540bf5) | Sep 08, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d21daec9ea](https://linux-hardware.org/?probe=d21daec9ea) | Sep 08, 2021 |
| Lenovo        | ThinkPad T430 2349D10       | Notebook    | [11ab5d413d](https://linux-hardware.org/?probe=11ab5d413d) | Sep 08, 2021 |
| Foxconn       | nT-A3000 series FAB         | Desktop     | [9e22d6dc70](https://linux-hardware.org/?probe=9e22d6dc70) | Sep 08, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [f8aae7ade2](https://linux-hardware.org/?probe=f8aae7ade2) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a826f2f4c9](https://linux-hardware.org/?probe=a826f2f4c9) | Sep 08, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [5aa6e46608](https://linux-hardware.org/?probe=5aa6e46608) | Sep 08, 2021 |
| Lenovo        | ThinkPad X230 2325B12       | Notebook    | [a55f42da78](https://linux-hardware.org/?probe=a55f42da78) | Sep 08, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [2626e29c5f](https://linux-hardware.org/?probe=2626e29c5f) | Sep 08, 2021 |
| ASUSTek       | Z87-A                       | Desktop     | [04ecb299d9](https://linux-hardware.org/?probe=04ecb299d9) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [b521805956](https://linux-hardware.org/?probe=b521805956) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [c4f6c7da11](https://linux-hardware.org/?probe=c4f6c7da11) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a4acb4b4d7](https://linux-hardware.org/?probe=a4acb4b4d7) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [33ae3adcc6](https://linux-hardware.org/?probe=33ae3adcc6) | Sep 08, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [cb2158566c](https://linux-hardware.org/?probe=cb2158566c) | Sep 08, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [65e545345d](https://linux-hardware.org/?probe=65e545345d) | Sep 07, 2021 |
| ASUSTek       | K52F                        | Notebook    | [b1f04036d8](https://linux-hardware.org/?probe=b1f04036d8) | Sep 07, 2021 |
| MSI           | GF63 8RD                    | Notebook    | [19cfc85441](https://linux-hardware.org/?probe=19cfc85441) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [55f595b53f](https://linux-hardware.org/?probe=55f595b53f) | Sep 07, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [41ab6b2f21](https://linux-hardware.org/?probe=41ab6b2f21) | Sep 07, 2021 |
| ASUSTek       | K52F                        | Notebook    | [0d72cf73ac](https://linux-hardware.org/?probe=0d72cf73ac) | Sep 07, 2021 |
| MSI           | GF63 8RD                    | Notebook    | [498dd20152](https://linux-hardware.org/?probe=498dd20152) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6fc35e97d8](https://linux-hardware.org/?probe=6fc35e97d8) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [5acaf42867](https://linux-hardware.org/?probe=5acaf42867) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [4d6ad821df](https://linux-hardware.org/?probe=4d6ad821df) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [511d2e120b](https://linux-hardware.org/?probe=511d2e120b) | Sep 07, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [13256468d1](https://linux-hardware.org/?probe=13256468d1) | Sep 07, 2021 |
| ASUSTek       | P5Q3                        | Desktop     | [3f08e7bf37](https://linux-hardware.org/?probe=3f08e7bf37) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [bcd1f7553d](https://linux-hardware.org/?probe=bcd1f7553d) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [0c0ccb21d8](https://linux-hardware.org/?probe=0c0ccb21d8) | Sep 07, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [cf59508b79](https://linux-hardware.org/?probe=cf59508b79) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [1c85c31f57](https://linux-hardware.org/?probe=1c85c31f57) | Sep 07, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [0183fb8d78](https://linux-hardware.org/?probe=0183fb8d78) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [6cf8ebc24c](https://linux-hardware.org/?probe=6cf8ebc24c) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [bf328adcb8](https://linux-hardware.org/?probe=bf328adcb8) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [09e28c958c](https://linux-hardware.org/?probe=09e28c958c) | Sep 07, 2021 |
| HP            | 212A                        | Desktop     | [7f51e384f7](https://linux-hardware.org/?probe=7f51e384f7) | Sep 07, 2021 |
| HP            | 212A                        | Desktop     | [c89a2196ab](https://linux-hardware.org/?probe=c89a2196ab) | Sep 07, 2021 |
| Dell          | Latitude 7480               | Notebook    | [844ab8df38](https://linux-hardware.org/?probe=844ab8df38) | Sep 06, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [9256f3fece](https://linux-hardware.org/?probe=9256f3fece) | Sep 06, 2021 |
| ASUSTek       | STRIX B250H GAMING          | Desktop     | [265822ee2e](https://linux-hardware.org/?probe=265822ee2e) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [7f6c0d6337](https://linux-hardware.org/?probe=7f6c0d6337) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [e6ea97df06](https://linux-hardware.org/?probe=e6ea97df06) | Sep 06, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [a0d1d9b2e6](https://linux-hardware.org/?probe=a0d1d9b2e6) | Sep 06, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [4aec08beef](https://linux-hardware.org/?probe=4aec08beef) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [3aedb68952](https://linux-hardware.org/?probe=3aedb68952) | Sep 06, 2021 |
| Samsung       | NC10                        | Notebook    | [98ba59d155](https://linux-hardware.org/?probe=98ba59d155) | Sep 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e42726b566](https://linux-hardware.org/?probe=e42726b566) | Sep 06, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [b6e28c84c8](https://linux-hardware.org/?probe=b6e28c84c8) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2a4adea555](https://linux-hardware.org/?probe=2a4adea555) | Sep 05, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [28c59930e4](https://linux-hardware.org/?probe=28c59930e4) | Sep 05, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [20f947223f](https://linux-hardware.org/?probe=20f947223f) | Sep 05, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [fe8833475a](https://linux-hardware.org/?probe=fe8833475a) | Sep 05, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [0a1850f760](https://linux-hardware.org/?probe=0a1850f760) | Sep 05, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [4ba7363e9e](https://linux-hardware.org/?probe=4ba7363e9e) | Sep 05, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [18fe596fba](https://linux-hardware.org/?probe=18fe596fba) | Sep 04, 2021 |
| HP            | Presario CQ62               | Notebook    | [4cdec89015](https://linux-hardware.org/?probe=4cdec89015) | Sep 04, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [af5a140c2e](https://linux-hardware.org/?probe=af5a140c2e) | Sep 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [9e235c4228](https://linux-hardware.org/?probe=9e235c4228) | Sep 04, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [0e32e6945b](https://linux-hardware.org/?probe=0e32e6945b) | Sep 03, 2021 |
| ASRock        | TRX40 Creator               | Desktop     | [0734c9bbd0](https://linux-hardware.org/?probe=0734c9bbd0) | Sep 03, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [db35296aa1](https://linux-hardware.org/?probe=db35296aa1) | Sep 03, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [fafd031d1f](https://linux-hardware.org/?probe=fafd031d1f) | Sep 03, 2021 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [ced0e47579](https://linux-hardware.org/?probe=ced0e47579) | Sep 02, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1449c0a9cd](https://linux-hardware.org/?probe=1449c0a9cd) | Sep 02, 2021 |
| ASUSTek       | UX303LNB                    | Notebook    | [e0756d7ae6](https://linux-hardware.org/?probe=e0756d7ae6) | Sep 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5d183d4587](https://linux-hardware.org/?probe=5d183d4587) | Sep 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [666c4fef08](https://linux-hardware.org/?probe=666c4fef08) | Sep 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [d6ee033eb7](https://linux-hardware.org/?probe=d6ee033eb7) | Sep 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [28fbb3d82d](https://linux-hardware.org/?probe=28fbb3d82d) | Sep 02, 2021 |
| ECS           | G31T-M9                     | Desktop     | [0757de543d](https://linux-hardware.org/?probe=0757de543d) | Sep 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [27c2ebc917](https://linux-hardware.org/?probe=27c2ebc917) | Sep 02, 2021 |
| Gigabyte      | 8I945P-G                    | Desktop     | [a1eb33a5f1](https://linux-hardware.org/?probe=a1eb33a5f1) | Sep 02, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [1d9e3a7503](https://linux-hardware.org/?probe=1d9e3a7503) | Sep 02, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [97c9e2dc1f](https://linux-hardware.org/?probe=97c9e2dc1f) | Sep 02, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d4c78cc3c4](https://linux-hardware.org/?probe=d4c78cc3c4) | Sep 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [6bf33dd2cb](https://linux-hardware.org/?probe=6bf33dd2cb) | Sep 01, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ca0e00bc0f](https://linux-hardware.org/?probe=ca0e00bc0f) | Sep 01, 2021 |
| Lenovo        | ThinkPad X250 20CLS2DK00    | Notebook    | [f1cad98694](https://linux-hardware.org/?probe=f1cad98694) | Sep 01, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [e96ab5fb39](https://linux-hardware.org/?probe=e96ab5fb39) | Sep 01, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [78fafc3314](https://linux-hardware.org/?probe=78fafc3314) | Sep 01, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [d542a6b8f9](https://linux-hardware.org/?probe=d542a6b8f9) | Sep 01, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [d8083308fc](https://linux-hardware.org/?probe=d8083308fc) | Sep 01, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [12a5a0f9c5](https://linux-hardware.org/?probe=12a5a0f9c5) | Sep 01, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [450ffd830c](https://linux-hardware.org/?probe=450ffd830c) | Sep 01, 2021 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [dadb397ef1](https://linux-hardware.org/?probe=dadb397ef1) | Sep 01, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3267eec643](https://linux-hardware.org/?probe=3267eec643) | Sep 01, 2021 |
| Pegatron      | TRUCKEE                     | Desktop     | [68f16e9542](https://linux-hardware.org/?probe=68f16e9542) | Sep 01, 2021 |
| Dell          | 094MXG A00                  | All in one  | [7fe3c46d72](https://linux-hardware.org/?probe=7fe3c46d72) | Sep 01, 2021 |
| Timi          | TM1613                      | Notebook    | [f25eeca060](https://linux-hardware.org/?probe=f25eeca060) | Sep 01, 2021 |
| Lenovo        | ThinkPad T430 2349S9E       | Notebook    | [bc224fb15f](https://linux-hardware.org/?probe=bc224fb15f) | Aug 31, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [9510c18df6](https://linux-hardware.org/?probe=9510c18df6) | Aug 31, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [6521e0d6be](https://linux-hardware.org/?probe=6521e0d6be) | Aug 31, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [783955d696](https://linux-hardware.org/?probe=783955d696) | Aug 31, 2021 |
| Lenovo        | ThinkPad X250 20CLS2DK00    | Notebook    | [db94fcaf10](https://linux-hardware.org/?probe=db94fcaf10) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [9c31643811](https://linux-hardware.org/?probe=9c31643811) | Aug 31, 2021 |
| ASUSTek       | P7P55D-E                    | Desktop     | [4c05b36e94](https://linux-hardware.org/?probe=4c05b36e94) | Aug 31, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [baf38e8736](https://linux-hardware.org/?probe=baf38e8736) | Aug 31, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [33a45018fc](https://linux-hardware.org/?probe=33a45018fc) | Aug 31, 2021 |
| Pine Micro... | Pine64+                     | Soc         | [433d54a30d](https://linux-hardware.org/?probe=433d54a30d) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [37c3e457bc](https://linux-hardware.org/?probe=37c3e457bc) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [0d38048f46](https://linux-hardware.org/?probe=0d38048f46) | Aug 31, 2021 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [d7eaf975a0](https://linux-hardware.org/?probe=d7eaf975a0) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [df9b303eec](https://linux-hardware.org/?probe=df9b303eec) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [d9af23fb86](https://linux-hardware.org/?probe=d9af23fb86) | Aug 31, 2021 |
| AOpen         | D1001 C26361-D1001          | Desktop     | [e27239d870](https://linux-hardware.org/?probe=e27239d870) | Aug 31, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [1470c8cc7f](https://linux-hardware.org/?probe=1470c8cc7f) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [ba7144c0dc](https://linux-hardware.org/?probe=ba7144c0dc) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [7204a77b38](https://linux-hardware.org/?probe=7204a77b38) | Aug 31, 2021 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [b26e82328a](https://linux-hardware.org/?probe=b26e82328a) | Aug 31, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [70835c3aa7](https://linux-hardware.org/?probe=70835c3aa7) | Aug 30, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [3e22f55c7b](https://linux-hardware.org/?probe=3e22f55c7b) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [b73b366bb6](https://linux-hardware.org/?probe=b73b366bb6) | Aug 30, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [c6a754129a](https://linux-hardware.org/?probe=c6a754129a) | Aug 30, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [e1b2dc4810](https://linux-hardware.org/?probe=e1b2dc4810) | Aug 30, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e94ab065a3](https://linux-hardware.org/?probe=e94ab065a3) | Aug 30, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [a251dca266](https://linux-hardware.org/?probe=a251dca266) | Aug 30, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [b1425fa900](https://linux-hardware.org/?probe=b1425fa900) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [b5a84f215b](https://linux-hardware.org/?probe=b5a84f215b) | Aug 30, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [f2dbdea931](https://linux-hardware.org/?probe=f2dbdea931) | Aug 30, 2021 |
| Intel         | DH67BL AAG10189-206         | Desktop     | [b7b3f489f2](https://linux-hardware.org/?probe=b7b3f489f2) | Aug 30, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [ca46b71791](https://linux-hardware.org/?probe=ca46b71791) | Aug 30, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [d255f48a39](https://linux-hardware.org/?probe=d255f48a39) | Aug 30, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [dc0abe4fcd](https://linux-hardware.org/?probe=dc0abe4fcd) | Aug 30, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [fc61c24624](https://linux-hardware.org/?probe=fc61c24624) | Aug 30, 2021 |
| Dell          | Latitude E6330              | Notebook    | [95d65375e2](https://linux-hardware.org/?probe=95d65375e2) | Aug 30, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [9d1b86643e](https://linux-hardware.org/?probe=9d1b86643e) | Aug 30, 2021 |
| Lenovo        | ThinkPad T61 7661BF3        | Notebook    | [69b6d76471](https://linux-hardware.org/?probe=69b6d76471) | Aug 30, 2021 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [acbb96ba48](https://linux-hardware.org/?probe=acbb96ba48) | Aug 29, 2021 |
| ASUSTek       | K56CB                       | Notebook    | [1a44fc7e8f](https://linux-hardware.org/?probe=1a44fc7e8f) | Aug 29, 2021 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [6fcfbde79d](https://linux-hardware.org/?probe=6fcfbde79d) | Aug 29, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [17ae4593ea](https://linux-hardware.org/?probe=17ae4593ea) | Aug 28, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b9595196ea](https://linux-hardware.org/?probe=b9595196ea) | Aug 28, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [8625d6f2f1](https://linux-hardware.org/?probe=8625d6f2f1) | Aug 28, 2021 |
| NC9VL         | 1.0                         | Desktop     | [9c4b8ad466](https://linux-hardware.org/?probe=9c4b8ad466) | Aug 28, 2021 |
| HP            | 0B50 Rev.A                  | All in one  | [4701ae6e71](https://linux-hardware.org/?probe=4701ae6e71) | Aug 27, 2021 |
| MSI           | B150A GAMING PRO            | Desktop     | [06de6cd826](https://linux-hardware.org/?probe=06de6cd826) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [46eacf8d5c](https://linux-hardware.org/?probe=46eacf8d5c) | Aug 27, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [202fe67100](https://linux-hardware.org/?probe=202fe67100) | Aug 27, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [321f53f711](https://linux-hardware.org/?probe=321f53f711) | Aug 27, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [06f4334a82](https://linux-hardware.org/?probe=06f4334a82) | Aug 27, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [d215521170](https://linux-hardware.org/?probe=d215521170) | Aug 27, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [2c85ec0205](https://linux-hardware.org/?probe=2c85ec0205) | Aug 27, 2021 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [7f3a68dd2a](https://linux-hardware.org/?probe=7f3a68dd2a) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [2737cfb67d](https://linux-hardware.org/?probe=2737cfb67d) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [dc9428d8b4](https://linux-hardware.org/?probe=dc9428d8b4) | Aug 27, 2021 |
| Lenovo        | ThinkPad T440p 20AN006GU... | Notebook    | [bca7704bb0](https://linux-hardware.org/?probe=bca7704bb0) | Aug 27, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [14747d88b3](https://linux-hardware.org/?probe=14747d88b3) | Aug 26, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [87904cbe92](https://linux-hardware.org/?probe=87904cbe92) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1c2e910793](https://linux-hardware.org/?probe=1c2e910793) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4a69118897](https://linux-hardware.org/?probe=4a69118897) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [474216fba9](https://linux-hardware.org/?probe=474216fba9) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [76d9383f33](https://linux-hardware.org/?probe=76d9383f33) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [213d3f817b](https://linux-hardware.org/?probe=213d3f817b) | Aug 26, 2021 |
| HP            | 0B0Ch                       | Desktop     | [b5933fde35](https://linux-hardware.org/?probe=b5933fde35) | Aug 26, 2021 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [8c051a0ce9](https://linux-hardware.org/?probe=8c051a0ce9) | Aug 26, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [f26ade88cd](https://linux-hardware.org/?probe=f26ade88cd) | Aug 26, 2021 |
| Dell          | 0WR7PY A00                  | Desktop     | [cb25b1811b](https://linux-hardware.org/?probe=cb25b1811b) | Aug 26, 2021 |
| Gigabyte      | AORUS 15G KB                | Notebook    | [6afefe68d7](https://linux-hardware.org/?probe=6afefe68d7) | Aug 26, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [8dd8862b4b](https://linux-hardware.org/?probe=8dd8862b4b) | Aug 26, 2021 |
| HP            | ProBook 4530s               | Notebook    | [2b4cab4d7c](https://linux-hardware.org/?probe=2b4cab4d7c) | Aug 25, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [7bab6dd9db](https://linux-hardware.org/?probe=7bab6dd9db) | Aug 25, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [a2f161dee0](https://linux-hardware.org/?probe=a2f161dee0) | Aug 25, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [e1e5a14c77](https://linux-hardware.org/?probe=e1e5a14c77) | Aug 25, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [16f399259c](https://linux-hardware.org/?probe=16f399259c) | Aug 25, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [d37f13917f](https://linux-hardware.org/?probe=d37f13917f) | Aug 25, 2021 |
| ASRock        | C2750D4I                    | Desktop     | [6daa3c26bf](https://linux-hardware.org/?probe=6daa3c26bf) | Aug 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0a79171c9e](https://linux-hardware.org/?probe=0a79171c9e) | Aug 25, 2021 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [feed9e2921](https://linux-hardware.org/?probe=feed9e2921) | Aug 25, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [3da8591ac6](https://linux-hardware.org/?probe=3da8591ac6) | Aug 25, 2021 |
| HP            | 630                         | Notebook    | [004d2b364d](https://linux-hardware.org/?probe=004d2b364d) | Aug 25, 2021 |
| Biostar       | Hi-Fi A85W                  | Desktop     | [ffb66dafd4](https://linux-hardware.org/?probe=ffb66dafd4) | Aug 25, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [b06c4079a7](https://linux-hardware.org/?probe=b06c4079a7) | Aug 25, 2021 |
| Dell          | Latitude 7490               | Notebook    | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2882cf9963](https://linux-hardware.org/?probe=2882cf9963) | Aug 25, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [557d74beb9](https://linux-hardware.org/?probe=557d74beb9) | Aug 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [65d82bc8e7](https://linux-hardware.org/?probe=65d82bc8e7) | Aug 24, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [e1bd0ec7fd](https://linux-hardware.org/?probe=e1bd0ec7fd) | Aug 24, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [e5c92fe4ad](https://linux-hardware.org/?probe=e5c92fe4ad) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8a72f87e7b](https://linux-hardware.org/?probe=8a72f87e7b) | Aug 24, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [441b8b892e](https://linux-hardware.org/?probe=441b8b892e) | Aug 24, 2021 |
| ASRock        | P4i65G                      | Desktop     | [43ce3e711f](https://linux-hardware.org/?probe=43ce3e711f) | Aug 24, 2021 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [c2179206a9](https://linux-hardware.org/?probe=c2179206a9) | Aug 24, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [1f257714a9](https://linux-hardware.org/?probe=1f257714a9) | Aug 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [102aea0211](https://linux-hardware.org/?probe=102aea0211) | Aug 24, 2021 |
| Unknown       | 1.0                         | Desktop     | [5e638360a8](https://linux-hardware.org/?probe=5e638360a8) | Aug 24, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [f755838fd8](https://linux-hardware.org/?probe=f755838fd8) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5cc74103a8](https://linux-hardware.org/?probe=5cc74103a8) | Aug 24, 2021 |
| HP            | 250 G4                      | Notebook    | [5d47aa9804](https://linux-hardware.org/?probe=5d47aa9804) | Aug 24, 2021 |
| ASUSTek       | UX430UAR                    | Notebook    | [77ce457de4](https://linux-hardware.org/?probe=77ce457de4) | Aug 24, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [df0fa8e968](https://linux-hardware.org/?probe=df0fa8e968) | Aug 24, 2021 |
| ASUSTek       | GA35DX                      | Desktop     | [3843ea048e](https://linux-hardware.org/?probe=3843ea048e) | Aug 24, 2021 |
| Sony          | VPCF115FM                   | Notebook    | [9f9abf79b2](https://linux-hardware.org/?probe=9f9abf79b2) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8a88eabb1c](https://linux-hardware.org/?probe=8a88eabb1c) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c4ecd51a21](https://linux-hardware.org/?probe=c4ecd51a21) | Aug 23, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [1c9d3bb8b4](https://linux-hardware.org/?probe=1c9d3bb8b4) | Aug 23, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [45ec27282a](https://linux-hardware.org/?probe=45ec27282a) | Aug 23, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [e92004f46a](https://linux-hardware.org/?probe=e92004f46a) | Aug 23, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [14af647cc5](https://linux-hardware.org/?probe=14af647cc5) | Aug 23, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [06c9a1ed3a](https://linux-hardware.org/?probe=06c9a1ed3a) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5bc9372587](https://linux-hardware.org/?probe=5bc9372587) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8bcb9e62e1](https://linux-hardware.org/?probe=8bcb9e62e1) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [6c44c4f7e3](https://linux-hardware.org/?probe=6c44c4f7e3) | Aug 23, 2021 |
| Google        | Enguarde                    | Notebook    | [12a2003770](https://linux-hardware.org/?probe=12a2003770) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [7f190e4ed2](https://linux-hardware.org/?probe=7f190e4ed2) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2db5cafda3](https://linux-hardware.org/?probe=2db5cafda3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [abcab36e0c](https://linux-hardware.org/?probe=abcab36e0c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f3ccb91568](https://linux-hardware.org/?probe=f3ccb91568) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [0d8fa16f47](https://linux-hardware.org/?probe=0d8fa16f47) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [680e8106ec](https://linux-hardware.org/?probe=680e8106ec) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c18b0215e9](https://linux-hardware.org/?probe=c18b0215e9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [fcc821b941](https://linux-hardware.org/?probe=fcc821b941) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [59f760dbb9](https://linux-hardware.org/?probe=59f760dbb9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e22a8e2ea4](https://linux-hardware.org/?probe=e22a8e2ea4) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4fc69342da](https://linux-hardware.org/?probe=4fc69342da) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f2fcae5696](https://linux-hardware.org/?probe=f2fcae5696) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2f823b2f52](https://linux-hardware.org/?probe=2f823b2f52) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [adf5b71331](https://linux-hardware.org/?probe=adf5b71331) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [618c1c7838](https://linux-hardware.org/?probe=618c1c7838) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [0dff1056d5](https://linux-hardware.org/?probe=0dff1056d5) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [fb0cf0a7a3](https://linux-hardware.org/?probe=fb0cf0a7a3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6b9f550210](https://linux-hardware.org/?probe=6b9f550210) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4b22440e91](https://linux-hardware.org/?probe=4b22440e91) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6bab7cdc7c](https://linux-hardware.org/?probe=6bab7cdc7c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [d2a08022bd](https://linux-hardware.org/?probe=d2a08022bd) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f39d94cf1b](https://linux-hardware.org/?probe=f39d94cf1b) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e35bbfda2d](https://linux-hardware.org/?probe=e35bbfda2d) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [60170675ca](https://linux-hardware.org/?probe=60170675ca) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [64a6aa27db](https://linux-hardware.org/?probe=64a6aa27db) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [06b1dab7a0](https://linux-hardware.org/?probe=06b1dab7a0) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [cec5c36945](https://linux-hardware.org/?probe=cec5c36945) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6f38e35f9a](https://linux-hardware.org/?probe=6f38e35f9a) | Aug 23, 2021 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [06234ebe05](https://linux-hardware.org/?probe=06234ebe05) | Aug 23, 2021 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [3c03ce796f](https://linux-hardware.org/?probe=3c03ce796f) | Aug 23, 2021 |
| MSI           | Z270-A PRO                  | Desktop     | [73b14ecca0](https://linux-hardware.org/?probe=73b14ecca0) | Aug 23, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [4a647bfabc](https://linux-hardware.org/?probe=4a647bfabc) | Aug 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [e70b15e489](https://linux-hardware.org/?probe=e70b15e489) | Aug 22, 2021 |
| HP            | EliteBook 840 G4            | Notebook    | [ebe40b3244](https://linux-hardware.org/?probe=ebe40b3244) | Aug 22, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [d98bdb0d1c](https://linux-hardware.org/?probe=d98bdb0d1c) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [d688bffa01](https://linux-hardware.org/?probe=d688bffa01) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [3d52884b6e](https://linux-hardware.org/?probe=3d52884b6e) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | Notebook    | [57b847b12c](https://linux-hardware.org/?probe=57b847b12c) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | Notebook    | [db4b9878fa](https://linux-hardware.org/?probe=db4b9878fa) | Aug 22, 2021 |
| Dell          | Inspiron 6000               | Notebook    | [67c6b36361](https://linux-hardware.org/?probe=67c6b36361) | Aug 22, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [eea45758b7](https://linux-hardware.org/?probe=eea45758b7) | Aug 22, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [dfed5d8b7a](https://linux-hardware.org/?probe=dfed5d8b7a) | Aug 21, 2021 |
| HP            | 085Ch                       | Desktop     | [2e649d07a0](https://linux-hardware.org/?probe=2e649d07a0) | Aug 21, 2021 |
| Dell          | Latitude E7470              | Notebook    | [e954672cb2](https://linux-hardware.org/?probe=e954672cb2) | Aug 21, 2021 |
| HP            | 085Ch                       | Desktop     | [c5b36c5187](https://linux-hardware.org/?probe=c5b36c5187) | Aug 21, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [4d43bca615](https://linux-hardware.org/?probe=4d43bca615) | Aug 21, 2021 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| ASRock        | Z97 Pro3                    | Desktop     | [0f9abf9c63](https://linux-hardware.org/?probe=0f9abf9c63) | Aug 21, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [7f83e1b3c8](https://linux-hardware.org/?probe=7f83e1b3c8) | Aug 21, 2021 |
| HP            | 14s-dq2003nw                | Notebook    | [f4dcd70da5](https://linux-hardware.org/?probe=f4dcd70da5) | Aug 21, 2021 |
| Lenovo        | ThinkPad E570 20H500B4GE    | Notebook    | [be964b556b](https://linux-hardware.org/?probe=be964b556b) | Aug 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [5ecdc39ac1](https://linux-hardware.org/?probe=5ecdc39ac1) | Aug 21, 2021 |
| ASUSTek       | P5B SE                      | Desktop     | [81634fcb22](https://linux-hardware.org/?probe=81634fcb22) | Aug 21, 2021 |
| Dell          | Precision 7520              | Notebook    | [372d627a69](https://linux-hardware.org/?probe=372d627a69) | Aug 21, 2021 |
| MSI           | Z270-A PRO                  | Desktop     | [e59c9482f6](https://linux-hardware.org/?probe=e59c9482f6) | Aug 21, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [daa01f79aa](https://linux-hardware.org/?probe=daa01f79aa) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [a96a7ada4f](https://linux-hardware.org/?probe=a96a7ada4f) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c8305c0d4c](https://linux-hardware.org/?probe=c8305c0d4c) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [77359352d0](https://linux-hardware.org/?probe=77359352d0) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5312257240](https://linux-hardware.org/?probe=5312257240) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [75e262ddba](https://linux-hardware.org/?probe=75e262ddba) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [bd216572a3](https://linux-hardware.org/?probe=bd216572a3) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e57aeadfef](https://linux-hardware.org/?probe=e57aeadfef) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [7211565d4a](https://linux-hardware.org/?probe=7211565d4a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [1c490522df](https://linux-hardware.org/?probe=1c490522df) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [16f0b9c14a](https://linux-hardware.org/?probe=16f0b9c14a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [691bb379e5](https://linux-hardware.org/?probe=691bb379e5) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [fe880ac0c8](https://linux-hardware.org/?probe=fe880ac0c8) | Aug 20, 2021 |
| Supermicro    | X10SLM-F                    | Server      | [801ee74858](https://linux-hardware.org/?probe=801ee74858) | Aug 20, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [a5a146e42a](https://linux-hardware.org/?probe=a5a146e42a) | Aug 20, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [580838bf3c](https://linux-hardware.org/?probe=580838bf3c) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [cba7d82942](https://linux-hardware.org/?probe=cba7d82942) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [62068f391f](https://linux-hardware.org/?probe=62068f391f) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c60ef3fa1e](https://linux-hardware.org/?probe=c60ef3fa1e) | Aug 20, 2021 |
| Supermicro    | X10DRW-iT                   | Server      | [aaeee85be7](https://linux-hardware.org/?probe=aaeee85be7) | Aug 20, 2021 |
| Timi          | TM1612                      | Notebook    | [485caf5846](https://linux-hardware.org/?probe=485caf5846) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [c980f2d201](https://linux-hardware.org/?probe=c980f2d201) | Aug 20, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [2a61705899](https://linux-hardware.org/?probe=2a61705899) | Aug 20, 2021 |
| Dell          | 0Y2K8N A01                  | Desktop     | [6b0fd02c91](https://linux-hardware.org/?probe=6b0fd02c91) | Aug 20, 2021 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [17c70c7886](https://linux-hardware.org/?probe=17c70c7886) | Aug 19, 2021 |
| SLIMBOOK      | TITAN                       | Notebook    | [a2abd981d1](https://linux-hardware.org/?probe=a2abd981d1) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1ce6738560](https://linux-hardware.org/?probe=1ce6738560) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [e134a1f7c3](https://linux-hardware.org/?probe=e134a1f7c3) | Aug 19, 2021 |
| HP            | 339A                        | Desktop     | [57d5bbd1e4](https://linux-hardware.org/?probe=57d5bbd1e4) | Aug 19, 2021 |
| RuggedPC      | Caterpillar T20             | Tablet      | [1bf2275be4](https://linux-hardware.org/?probe=1bf2275be4) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [87fa430aab](https://linux-hardware.org/?probe=87fa430aab) | Aug 19, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2151b5cdae](https://linux-hardware.org/?probe=2151b5cdae) | Aug 19, 2021 |
| HP            | 1587h                       | Desktop     | [3ddbdb3101](https://linux-hardware.org/?probe=3ddbdb3101) | Aug 19, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [0489699bc4](https://linux-hardware.org/?probe=0489699bc4) | Aug 19, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [cc54b8955c](https://linux-hardware.org/?probe=cc54b8955c) | Aug 19, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [757e261c56](https://linux-hardware.org/?probe=757e261c56) | Aug 19, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [df15656fce](https://linux-hardware.org/?probe=df15656fce) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c989eac16b](https://linux-hardware.org/?probe=c989eac16b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [3169e477dd](https://linux-hardware.org/?probe=3169e477dd) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5fcb7fdb26](https://linux-hardware.org/?probe=5fcb7fdb26) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [7afbba35b0](https://linux-hardware.org/?probe=7afbba35b0) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [f1d159bbd1](https://linux-hardware.org/?probe=f1d159bbd1) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [38e8211556](https://linux-hardware.org/?probe=38e8211556) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [bd587e5998](https://linux-hardware.org/?probe=bd587e5998) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [3fa54711ec](https://linux-hardware.org/?probe=3fa54711ec) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [4a7f287161](https://linux-hardware.org/?probe=4a7f287161) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6f5485edfc](https://linux-hardware.org/?probe=6f5485edfc) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [fed5f28778](https://linux-hardware.org/?probe=fed5f28778) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [0ba8599928](https://linux-hardware.org/?probe=0ba8599928) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [e31d43b39d](https://linux-hardware.org/?probe=e31d43b39d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [703cdcf766](https://linux-hardware.org/?probe=703cdcf766) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [9b8ce55c3d](https://linux-hardware.org/?probe=9b8ce55c3d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2b4af51f46](https://linux-hardware.org/?probe=2b4af51f46) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [b802b4a25b](https://linux-hardware.org/?probe=b802b4a25b) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [cb421b796b](https://linux-hardware.org/?probe=cb421b796b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [f6c7230675](https://linux-hardware.org/?probe=f6c7230675) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [7116839a4b](https://linux-hardware.org/?probe=7116839a4b) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [04817bfb7f](https://linux-hardware.org/?probe=04817bfb7f) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [1fce0ab0e8](https://linux-hardware.org/?probe=1fce0ab0e8) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [92b401a705](https://linux-hardware.org/?probe=92b401a705) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [f2a438a9be](https://linux-hardware.org/?probe=f2a438a9be) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c9239b499b](https://linux-hardware.org/?probe=c9239b499b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [b708a97ef1](https://linux-hardware.org/?probe=b708a97ef1) | Aug 18, 2021 |
| Lenovo        | Board                       | Desktop     | [3de8569fe7](https://linux-hardware.org/?probe=3de8569fe7) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [31dc792a8b](https://linux-hardware.org/?probe=31dc792a8b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [76a48b344d](https://linux-hardware.org/?probe=76a48b344d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [244aba47d4](https://linux-hardware.org/?probe=244aba47d4) | Aug 18, 2021 |
| ASUSTek       | H81M-R                      | Desktop     | [8598ad2248](https://linux-hardware.org/?probe=8598ad2248) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [b2391216c6](https://linux-hardware.org/?probe=b2391216c6) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [53b311c24c](https://linux-hardware.org/?probe=53b311c24c) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [61de56951c](https://linux-hardware.org/?probe=61de56951c) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [7fd7f1ea77](https://linux-hardware.org/?probe=7fd7f1ea77) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [2a090f8b2a](https://linux-hardware.org/?probe=2a090f8b2a) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [62e4ff915a](https://linux-hardware.org/?probe=62e4ff915a) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [eada085a33](https://linux-hardware.org/?probe=eada085a33) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [474e20b9f2](https://linux-hardware.org/?probe=474e20b9f2) | Aug 18, 2021 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [61b641914c](https://linux-hardware.org/?probe=61b641914c) | Aug 18, 2021 |
| ASUSTek       | B150M-K                     | Desktop     | [3f706a2a69](https://linux-hardware.org/?probe=3f706a2a69) | Aug 18, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [9f3381d34c](https://linux-hardware.org/?probe=9f3381d34c) | Aug 18, 2021 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [85cfabd795](https://linux-hardware.org/?probe=85cfabd795) | Aug 18, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [765f5d340e](https://linux-hardware.org/?probe=765f5d340e) | Aug 18, 2021 |
| ASRock        | J4205-ITX                   | Desktop     | [30de75d2c8](https://linux-hardware.org/?probe=30de75d2c8) | Aug 18, 2021 |
| ASUSTek       | UX305CA                     | Notebook    | [6ab6beca67](https://linux-hardware.org/?probe=6ab6beca67) | Aug 18, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [c7155dfa07](https://linux-hardware.org/?probe=c7155dfa07) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [451fe761a6](https://linux-hardware.org/?probe=451fe761a6) | Aug 18, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [b2ed4bc6fe](https://linux-hardware.org/?probe=b2ed4bc6fe) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [dd0de8b832](https://linux-hardware.org/?probe=dd0de8b832) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [a6ac2782a6](https://linux-hardware.org/?probe=a6ac2782a6) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [d32e974941](https://linux-hardware.org/?probe=d32e974941) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [fe90c1da98](https://linux-hardware.org/?probe=fe90c1da98) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c3d98780bf](https://linux-hardware.org/?probe=c3d98780bf) | Aug 17, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [4b38b9e598](https://linux-hardware.org/?probe=4b38b9e598) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2c30321150](https://linux-hardware.org/?probe=2c30321150) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2f6317ebc5](https://linux-hardware.org/?probe=2f6317ebc5) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [707606ff5e](https://linux-hardware.org/?probe=707606ff5e) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [0c43bb89c0](https://linux-hardware.org/?probe=0c43bb89c0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [fcb540b848](https://linux-hardware.org/?probe=fcb540b848) | Aug 17, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [46240d5ef9](https://linux-hardware.org/?probe=46240d5ef9) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6e85db6058](https://linux-hardware.org/?probe=6e85db6058) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2e26440865](https://linux-hardware.org/?probe=2e26440865) | Aug 17, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [5ad65197ad](https://linux-hardware.org/?probe=5ad65197ad) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c185e120f1](https://linux-hardware.org/?probe=c185e120f1) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [ee22c0dcc0](https://linux-hardware.org/?probe=ee22c0dcc0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [b3fd5bee39](https://linux-hardware.org/?probe=b3fd5bee39) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [d68e571cd0](https://linux-hardware.org/?probe=d68e571cd0) | Aug 17, 2021 |
| Dell          | Latitude 7480               | Notebook    | [49272ed382](https://linux-hardware.org/?probe=49272ed382) | Aug 17, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [be9383850e](https://linux-hardware.org/?probe=be9383850e) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [28c2f85e9c](https://linux-hardware.org/?probe=28c2f85e9c) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [1f8c3f9487](https://linux-hardware.org/?probe=1f8c3f9487) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [9f6a737d07](https://linux-hardware.org/?probe=9f6a737d07) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4eb4afec6b](https://linux-hardware.org/?probe=4eb4afec6b) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [5949002919](https://linux-hardware.org/?probe=5949002919) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [b0d4ba09f6](https://linux-hardware.org/?probe=b0d4ba09f6) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [12377bdf65](https://linux-hardware.org/?probe=12377bdf65) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f345284082](https://linux-hardware.org/?probe=f345284082) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6229638b59](https://linux-hardware.org/?probe=6229638b59) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [b95e1787ff](https://linux-hardware.org/?probe=b95e1787ff) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f1d344625b](https://linux-hardware.org/?probe=f1d344625b) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [4d7eaa38ba](https://linux-hardware.org/?probe=4d7eaa38ba) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [8be28c3080](https://linux-hardware.org/?probe=8be28c3080) | Aug 17, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [9e66245080](https://linux-hardware.org/?probe=9e66245080) | Aug 17, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [d8f20bc651](https://linux-hardware.org/?probe=d8f20bc651) | Aug 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | Desktop     | [7911fbd6a6](https://linux-hardware.org/?probe=7911fbd6a6) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [cfdf77fbd9](https://linux-hardware.org/?probe=cfdf77fbd9) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [6e84dfb541](https://linux-hardware.org/?probe=6e84dfb541) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [2549683d9f](https://linux-hardware.org/?probe=2549683d9f) | Aug 17, 2021 |
| Dell          | Latitude 7410               | Notebook    | [f7f6e5a4d5](https://linux-hardware.org/?probe=f7f6e5a4d5) | Aug 17, 2021 |
| ASUSTek       | 1225B                       | Notebook    | [1dd6877b22](https://linux-hardware.org/?probe=1dd6877b22) | Aug 17, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [6972c43e80](https://linux-hardware.org/?probe=6972c43e80) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Google        | Enguarde                    | Notebook    | [0bdebdb178](https://linux-hardware.org/?probe=0bdebdb178) | Aug 16, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [86cf4755a0](https://linux-hardware.org/?probe=86cf4755a0) | Aug 16, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [3a489f9498](https://linux-hardware.org/?probe=3a489f9498) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [635d3ab3e5](https://linux-hardware.org/?probe=635d3ab3e5) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2e04ae93d1](https://linux-hardware.org/?probe=2e04ae93d1) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [dffcb4d4f6](https://linux-hardware.org/?probe=dffcb4d4f6) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e3816a3d3a](https://linux-hardware.org/?probe=e3816a3d3a) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [d76cf98938](https://linux-hardware.org/?probe=d76cf98938) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [fc7b752ce3](https://linux-hardware.org/?probe=fc7b752ce3) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [346d3ca919](https://linux-hardware.org/?probe=346d3ca919) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [eb7cdde4b5](https://linux-hardware.org/?probe=eb7cdde4b5) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [ae1b239645](https://linux-hardware.org/?probe=ae1b239645) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [d7e9112089](https://linux-hardware.org/?probe=d7e9112089) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [35ab4c3075](https://linux-hardware.org/?probe=35ab4c3075) | Aug 16, 2021 |
| Lenovo        | ThinkPad E490 20N8001EUS    | Notebook    | [40796d62c2](https://linux-hardware.org/?probe=40796d62c2) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1fa30fb77a](https://linux-hardware.org/?probe=1fa30fb77a) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [81f2a65461](https://linux-hardware.org/?probe=81f2a65461) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [a54d2e496c](https://linux-hardware.org/?probe=a54d2e496c) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [d0581c16e9](https://linux-hardware.org/?probe=d0581c16e9) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [4704dd7dc2](https://linux-hardware.org/?probe=4704dd7dc2) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2d48e28c72](https://linux-hardware.org/?probe=2d48e28c72) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [dcded26792](https://linux-hardware.org/?probe=dcded26792) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [de06f0cb03](https://linux-hardware.org/?probe=de06f0cb03) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [3171a06ab2](https://linux-hardware.org/?probe=3171a06ab2) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [154d3f4aac](https://linux-hardware.org/?probe=154d3f4aac) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 20J10046US      | Notebook    | [6943b835e5](https://linux-hardware.org/?probe=6943b835e5) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [56e2f75dab](https://linux-hardware.org/?probe=56e2f75dab) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [7e070c3cee](https://linux-hardware.org/?probe=7e070c3cee) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [be42bbb09a](https://linux-hardware.org/?probe=be42bbb09a) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [42a5d4fb48](https://linux-hardware.org/?probe=42a5d4fb48) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [845219864e](https://linux-hardware.org/?probe=845219864e) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99531c5564](https://linux-hardware.org/?probe=99531c5564) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [7e2e8d1364](https://linux-hardware.org/?probe=7e2e8d1364) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [c9b0773c42](https://linux-hardware.org/?probe=c9b0773c42) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [947e3524e3](https://linux-hardware.org/?probe=947e3524e3) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [a30c87c3fe](https://linux-hardware.org/?probe=a30c87c3fe) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [edaac7af9f](https://linux-hardware.org/?probe=edaac7af9f) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [94047a5fdc](https://linux-hardware.org/?probe=94047a5fdc) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [ccd9ef4a72](https://linux-hardware.org/?probe=ccd9ef4a72) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [97aab17694](https://linux-hardware.org/?probe=97aab17694) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [3112135337](https://linux-hardware.org/?probe=3112135337) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8da303b571](https://linux-hardware.org/?probe=8da303b571) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [449ea4adf6](https://linux-hardware.org/?probe=449ea4adf6) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5bd9662328](https://linux-hardware.org/?probe=5bd9662328) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [079ef9affe](https://linux-hardware.org/?probe=079ef9affe) | Aug 16, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [3d63a976ed](https://linux-hardware.org/?probe=3d63a976ed) | Aug 16, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [c847e8acf2](https://linux-hardware.org/?probe=c847e8acf2) | Aug 16, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [ec9367ff70](https://linux-hardware.org/?probe=ec9367ff70) | Aug 16, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [ea9196699a](https://linux-hardware.org/?probe=ea9196699a) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [9e81b88eb8](https://linux-hardware.org/?probe=9e81b88eb8) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [7b614dd679](https://linux-hardware.org/?probe=7b614dd679) | Aug 16, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [2cd1a890fa](https://linux-hardware.org/?probe=2cd1a890fa) | Aug 16, 2021 |
| Dell          | G3 3590                     | Notebook    | [05e11ad38d](https://linux-hardware.org/?probe=05e11ad38d) | Aug 16, 2021 |
| HP            | 630                         | Notebook    | [a57ed15001](https://linux-hardware.org/?probe=a57ed15001) | Aug 15, 2021 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [51f9388874](https://linux-hardware.org/?probe=51f9388874) | Aug 15, 2021 |
| ASUSTek       | STRIX B250H GAMING          | Desktop     | [88160f850f](https://linux-hardware.org/?probe=88160f850f) | Aug 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [31fcb375f4](https://linux-hardware.org/?probe=31fcb375f4) | Aug 15, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [53aff8d681](https://linux-hardware.org/?probe=53aff8d681) | Aug 15, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | Notebook    | [e3fd79d228](https://linux-hardware.org/?probe=e3fd79d228) | Aug 15, 2021 |
| ECS           | KBN-I                       | Desktop     | [bbfe1ba1a2](https://linux-hardware.org/?probe=bbfe1ba1a2) | Aug 15, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [daf1b7a963](https://linux-hardware.org/?probe=daf1b7a963) | Aug 15, 2021 |
| AMI           | Intel                       | Convertible | [c96146f531](https://linux-hardware.org/?probe=c96146f531) | Aug 15, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [987ab1f3bf](https://linux-hardware.org/?probe=987ab1f3bf) | Aug 15, 2021 |
| Hardkernel    | Odroid XU4                  | Soc         | [dbc542cf3e](https://linux-hardware.org/?probe=dbc542cf3e) | Aug 15, 2021 |
| Hardkernel    | Odroid XU4                  | Soc         | [130a903db8](https://linux-hardware.org/?probe=130a903db8) | Aug 15, 2021 |
| Hardkernel    | Odroid XU4                  | Soc         | [7cfc2e8121](https://linux-hardware.org/?probe=7cfc2e8121) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [0b7f4b2da5](https://linux-hardware.org/?probe=0b7f4b2da5) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | Desktop     | [a6e0859eac](https://linux-hardware.org/?probe=a6e0859eac) | Aug 14, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [f6b6388040](https://linux-hardware.org/?probe=f6b6388040) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | Desktop     | [5ce5d800d3](https://linux-hardware.org/?probe=5ce5d800d3) | Aug 14, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [dfe51161fe](https://linux-hardware.org/?probe=dfe51161fe) | Aug 14, 2021 |
| HP            | Compaq nc6320 (EV073AV)     | Notebook    | [bf6050f750](https://linux-hardware.org/?probe=bf6050f750) | Aug 14, 2021 |
| ASRock        | Z97 Pro3                    | Desktop     | [0e5746a060](https://linux-hardware.org/?probe=0e5746a060) | Aug 14, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [f3506aaa1c](https://linux-hardware.org/?probe=f3506aaa1c) | Aug 14, 2021 |
| Dell          | 0X9M3X A01                  | Desktop     | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| Dell          | Latitude 7490               | Notebook    | [6ca174eba8](https://linux-hardware.org/?probe=6ca174eba8) | Aug 14, 2021 |
| HP            | 3397                        | Desktop     | [a3425b956c](https://linux-hardware.org/?probe=a3425b956c) | Aug 14, 2021 |
| Dell          | Latitude 7490               | Notebook    | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [cac72ff077](https://linux-hardware.org/?probe=cac72ff077) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [8c489e2c59](https://linux-hardware.org/?probe=8c489e2c59) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [d79905590c](https://linux-hardware.org/?probe=d79905590c) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [7efce8d06b](https://linux-hardware.org/?probe=7efce8d06b) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [c53a0803e7](https://linux-hardware.org/?probe=c53a0803e7) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [410a4b2e26](https://linux-hardware.org/?probe=410a4b2e26) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [cbc9f75923](https://linux-hardware.org/?probe=cbc9f75923) | Aug 13, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [62faddbfaa](https://linux-hardware.org/?probe=62faddbfaa) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [4ca322af56](https://linux-hardware.org/?probe=4ca322af56) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [2af4090c36](https://linux-hardware.org/?probe=2af4090c36) | Aug 13, 2021 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [f59179a579](https://linux-hardware.org/?probe=f59179a579) | Aug 13, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [0fb5cb1e91](https://linux-hardware.org/?probe=0fb5cb1e91) | Aug 13, 2021 |
| ASUSTek       | Z170-PRO                    | Desktop     | [7f9b5606a5](https://linux-hardware.org/?probe=7f9b5606a5) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [43919a91f3](https://linux-hardware.org/?probe=43919a91f3) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [c93dcd9531](https://linux-hardware.org/?probe=c93dcd9531) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [8e7147d832](https://linux-hardware.org/?probe=8e7147d832) | Aug 12, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [65a4eb9f2c](https://linux-hardware.org/?probe=65a4eb9f2c) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [e9f95dc0ed](https://linux-hardware.org/?probe=e9f95dc0ed) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [3b5b9d1698](https://linux-hardware.org/?probe=3b5b9d1698) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [e423d1eee6](https://linux-hardware.org/?probe=e423d1eee6) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [1f00600e9b](https://linux-hardware.org/?probe=1f00600e9b) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [88adc88ccd](https://linux-hardware.org/?probe=88adc88ccd) | Aug 12, 2021 |
| Notebook      | NL4x_NL5xLU                 | Notebook    | [82a8b9c657](https://linux-hardware.org/?probe=82a8b9c657) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [2434eac448](https://linux-hardware.org/?probe=2434eac448) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [d766910df0](https://linux-hardware.org/?probe=d766910df0) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [c0516ce965](https://linux-hardware.org/?probe=c0516ce965) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [728007c621](https://linux-hardware.org/?probe=728007c621) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [b808ac5856](https://linux-hardware.org/?probe=b808ac5856) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [326cc3aae3](https://linux-hardware.org/?probe=326cc3aae3) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [1fddcb2525](https://linux-hardware.org/?probe=1fddcb2525) | Aug 12, 2021 |
| Lenovo        | ThinkPad T440s 20AR0011M... | Notebook    | [df7a1d9358](https://linux-hardware.org/?probe=df7a1d9358) | Aug 12, 2021 |
| Dell          | G7 7790                     | Notebook    | [99dd172940](https://linux-hardware.org/?probe=99dd172940) | Aug 12, 2021 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [2bc14051d8](https://linux-hardware.org/?probe=2bc14051d8) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CM001RMS    | Notebook    | [d0dfc1011e](https://linux-hardware.org/?probe=d0dfc1011e) | Aug 12, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [c0bae6c52e](https://linux-hardware.org/?probe=c0bae6c52e) | Aug 12, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [cbe8c5170f](https://linux-hardware.org/?probe=cbe8c5170f) | Aug 12, 2021 |
| HP            | ProBook 4530s               | Notebook    | [14a78c65a1](https://linux-hardware.org/?probe=14a78c65a1) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| HP            | 3048h                       | Desktop     | [894950911f](https://linux-hardware.org/?probe=894950911f) | Aug 11, 2021 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [7e6788485b](https://linux-hardware.org/?probe=7e6788485b) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [4139a3a855](https://linux-hardware.org/?probe=4139a3a855) | Aug 11, 2021 |
| Notebook      | N13_N140ZU                  | Notebook    | [cbaecf1d3e](https://linux-hardware.org/?probe=cbaecf1d3e) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [48573ed425](https://linux-hardware.org/?probe=48573ed425) | Aug 11, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9b62457757](https://linux-hardware.org/?probe=9b62457757) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [4d023d9be2](https://linux-hardware.org/?probe=4d023d9be2) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [927a3673b9](https://linux-hardware.org/?probe=927a3673b9) | Aug 11, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f174ea79a1](https://linux-hardware.org/?probe=f174ea79a1) | Aug 11, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a5a2ea2cda](https://linux-hardware.org/?probe=a5a2ea2cda) | Aug 11, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [cabe0ebbc8](https://linux-hardware.org/?probe=cabe0ebbc8) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1dcbf85471](https://linux-hardware.org/?probe=1dcbf85471) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [0c67490330](https://linux-hardware.org/?probe=0c67490330) | Aug 10, 2021 |
| HP            | 2AF7                        | Desktop     | [649ed7df8e](https://linux-hardware.org/?probe=649ed7df8e) | Aug 10, 2021 |
| Dell          | Precision 3551              | Notebook    | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| Intel         | DQ45CB AAE30148-207         | Desktop     | [56a573eeed](https://linux-hardware.org/?probe=56a573eeed) | Aug 10, 2021 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [6f4ad31000](https://linux-hardware.org/?probe=6f4ad31000) | Aug 10, 2021 |
| ASUSTek       | STRIX B250H GAMING          | Desktop     | [78223998b6](https://linux-hardware.org/?probe=78223998b6) | Aug 10, 2021 |
| HP            | 250 G4                      | Notebook    | [5640b0689d](https://linux-hardware.org/?probe=5640b0689d) | Aug 10, 2021 |
| MSI           | B250M PRO-VDH               | Desktop     | [d6be998202](https://linux-hardware.org/?probe=d6be998202) | Aug 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [d650ff0c3e](https://linux-hardware.org/?probe=d650ff0c3e) | Aug 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4ce98656a4](https://linux-hardware.org/?probe=4ce98656a4) | Aug 10, 2021 |
| Dell          | Inspiron ME051              | Notebook    | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Lenovo        | B51-35 80LH                 | Notebook    | [5f87168a65](https://linux-hardware.org/?probe=5f87168a65) | Aug 10, 2021 |
| Dell          | 04MFRM A01                  | Desktop     | [c0094def97](https://linux-hardware.org/?probe=c0094def97) | Aug 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6ab68482c0](https://linux-hardware.org/?probe=6ab68482c0) | Aug 09, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [58b4f52cc0](https://linux-hardware.org/?probe=58b4f52cc0) | Aug 09, 2021 |
| Lenovo        | ThinkPad T470s 20HGS3R80... | Notebook    | [fbc29e2063](https://linux-hardware.org/?probe=fbc29e2063) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [e4ce236efd](https://linux-hardware.org/?probe=e4ce236efd) | Aug 09, 2021 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [7ca1257064](https://linux-hardware.org/?probe=7ca1257064) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [1c26f935e6](https://linux-hardware.org/?probe=1c26f935e6) | Aug 09, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [538a15f3cc](https://linux-hardware.org/?probe=538a15f3cc) | Aug 09, 2021 |
| HP            | 2000                        | Notebook    | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [fffaf4c700](https://linux-hardware.org/?probe=fffaf4c700) | Aug 09, 2021 |
| Lenovo        | ThinkPad T580 20L9001AUS    | Notebook    | [65e201224c](https://linux-hardware.org/?probe=65e201224c) | Aug 09, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [516f3cd4e5](https://linux-hardware.org/?probe=516f3cd4e5) | Aug 09, 2021 |
| Gigabyte      | H470M DS3H                  | Desktop     | [29de4693d8](https://linux-hardware.org/?probe=29de4693d8) | Aug 09, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [1a19648b3b](https://linux-hardware.org/?probe=1a19648b3b) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| ASRock        | 970A-G                      | Desktop     | [f1e9959894](https://linux-hardware.org/?probe=f1e9959894) | Aug 09, 2021 |
| Lenovo        | ThinkPad T410 2537E49       | Notebook    | [ea10aead92](https://linux-hardware.org/?probe=ea10aead92) | Aug 08, 2021 |
| Toshiba       | STI 910090 STIJ             | Desktop     | [389ebd7675](https://linux-hardware.org/?probe=389ebd7675) | Aug 08, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [575a84d010](https://linux-hardware.org/?probe=575a84d010) | Aug 08, 2021 |
| Clevo         | W55xEU                      | Notebook    | [ee96e1ca32](https://linux-hardware.org/?probe=ee96e1ca32) | Aug 08, 2021 |
| ASRock        | X370 Killer SLI             | Desktop     | [8a0885afb6](https://linux-hardware.org/?probe=8a0885afb6) | Aug 08, 2021 |
| Lenovo        | ThinkPad W500 406152G       | Notebook    | [b400f1bc46](https://linux-hardware.org/?probe=b400f1bc46) | Aug 08, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [eac37d633f](https://linux-hardware.org/?probe=eac37d633f) | Aug 08, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [43aae04fa6](https://linux-hardware.org/?probe=43aae04fa6) | Aug 08, 2021 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b1f5babbfb](https://linux-hardware.org/?probe=b1f5babbfb) | Aug 08, 2021 |
| Lenovo        | ThinkPad X230 23252FG       | Notebook    | [1c7914d660](https://linux-hardware.org/?probe=1c7914d660) | Aug 08, 2021 |
| ASRock        | Z97 Pro4                    | Desktop     | [090d12a96f](https://linux-hardware.org/?probe=090d12a96f) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [39eb5a1578](https://linux-hardware.org/?probe=39eb5a1578) | Aug 08, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c5ef006a35](https://linux-hardware.org/?probe=c5ef006a35) | Aug 08, 2021 |
| Toshiba       | STI 005038 G31T-M7          | Desktop     | [faa8f15725](https://linux-hardware.org/?probe=faa8f15725) | Aug 08, 2021 |
| Acer          | Swift SF314-51              | Notebook    | [88fa728376](https://linux-hardware.org/?probe=88fa728376) | Aug 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [e18202a558](https://linux-hardware.org/?probe=e18202a558) | Aug 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [a89cdf06f5](https://linux-hardware.org/?probe=a89cdf06f5) | Aug 07, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| Clevo         | P170EM                      | Notebook    | [f101b2b318](https://linux-hardware.org/?probe=f101b2b318) | Aug 07, 2021 |
| Acer          | Aspire E5-575               | Notebook    | [3caca4f238](https://linux-hardware.org/?probe=3caca4f238) | Aug 07, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [1dbaeef7d2](https://linux-hardware.org/?probe=1dbaeef7d2) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9dafe47483](https://linux-hardware.org/?probe=9dafe47483) | Aug 07, 2021 |
| Google        | Parrot                      | Notebook    | [2efb04c61c](https://linux-hardware.org/?probe=2efb04c61c) | Aug 07, 2021 |
| Lenovo        | ThinkPad T61 7661BK7        | Notebook    | [bbabc03a27](https://linux-hardware.org/?probe=bbabc03a27) | Aug 07, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [da833ac33e](https://linux-hardware.org/?probe=da833ac33e) | Aug 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [80c7711147](https://linux-hardware.org/?probe=80c7711147) | Aug 07, 2021 |
| Sony          | VPCF21AFX                   | Notebook    | [40aa5144f7](https://linux-hardware.org/?probe=40aa5144f7) | Aug 07, 2021 |
| Lenovo        | ThinkPad T450 20BUS16700    | Notebook    | [8123256638](https://linux-hardware.org/?probe=8123256638) | Aug 07, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [e82d4c3561](https://linux-hardware.org/?probe=e82d4c3561) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [4ff5966d22](https://linux-hardware.org/?probe=4ff5966d22) | Aug 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5839492cd8](https://linux-hardware.org/?probe=5839492cd8) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [412f800d01](https://linux-hardware.org/?probe=412f800d01) | Aug 07, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [733a3e325c](https://linux-hardware.org/?probe=733a3e325c) | Aug 07, 2021 |
| Dell          | 08WKV3 A01                  | Desktop     | [8ab0ff9442](https://linux-hardware.org/?probe=8ab0ff9442) | Aug 07, 2021 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | Notebook    | [701a99b60f](https://linux-hardware.org/?probe=701a99b60f) | Aug 07, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [69696c0e3a](https://linux-hardware.org/?probe=69696c0e3a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X200 7458B64       | Notebook    | [110a19b1b7](https://linux-hardware.org/?probe=110a19b1b7) | Aug 07, 2021 |
| MSI           | MEG X399 CREATION           | Desktop     | [7cada9aaed](https://linux-hardware.org/?probe=7cada9aaed) | Aug 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS0BU0T    | Notebook    | [f22b591a0a](https://linux-hardware.org/?probe=f22b591a0a) | Aug 07, 2021 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | Notebook    | [3d02d8b67f](https://linux-hardware.org/?probe=3d02d8b67f) | Aug 07, 2021 |
| HP            | 630                         | Notebook    | [b2d03b8717](https://linux-hardware.org/?probe=b2d03b8717) | Aug 07, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [368abe4066](https://linux-hardware.org/?probe=368abe4066) | Aug 07, 2021 |
| MSI           | B250M PRO-VDH               | Desktop     | [187e4dd872](https://linux-hardware.org/?probe=187e4dd872) | Aug 07, 2021 |
| HP            | 630                         | Notebook    | [428ee9672e](https://linux-hardware.org/?probe=428ee9672e) | Aug 07, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SNZ... | Notebook    | [669874ee19](https://linux-hardware.org/?probe=669874ee19) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [ad24cf2899](https://linux-hardware.org/?probe=ad24cf2899) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [9f994fc086](https://linux-hardware.org/?probe=9f994fc086) | Aug 07, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e2b8c558f7](https://linux-hardware.org/?probe=e2b8c558f7) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | Notebook    | [8cc604abc2](https://linux-hardware.org/?probe=8cc604abc2) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c9c4b53460](https://linux-hardware.org/?probe=c9c4b53460) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | Notebook    | [f54c45ab89](https://linux-hardware.org/?probe=f54c45ab89) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [81fef8f548](https://linux-hardware.org/?probe=81fef8f548) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | Notebook    | [4e000b3710](https://linux-hardware.org/?probe=4e000b3710) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | Notebook    | [493e2762bc](https://linux-hardware.org/?probe=493e2762bc) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2eb3a16b53](https://linux-hardware.org/?probe=2eb3a16b53) | Aug 06, 2021 |
| Dell          | Precision 3540              | Notebook    | [1b8206cd29](https://linux-hardware.org/?probe=1b8206cd29) | Aug 06, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [10811e8109](https://linux-hardware.org/?probe=10811e8109) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [bba0c0a13c](https://linux-hardware.org/?probe=bba0c0a13c) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [25f1a5ecdf](https://linux-hardware.org/?probe=25f1a5ecdf) | Aug 06, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [a7114078e2](https://linux-hardware.org/?probe=a7114078e2) | Aug 06, 2021 |
| Lenovo        | ThinkPad W520 4284CY1       | Notebook    | [5e1c9e9e30](https://linux-hardware.org/?probe=5e1c9e9e30) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [639bb0ca17](https://linux-hardware.org/?probe=639bb0ca17) | Aug 06, 2021 |
| Dell          | G3 3579                     | Notebook    | [5a268dbc14](https://linux-hardware.org/?probe=5a268dbc14) | Aug 06, 2021 |
| Dell          | G3 3579                     | Notebook    | [6aae1a533f](https://linux-hardware.org/?probe=6aae1a533f) | Aug 06, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [545f7195ab](https://linux-hardware.org/?probe=545f7195ab) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [41d352c625](https://linux-hardware.org/?probe=41d352c625) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [3256d646b0](https://linux-hardware.org/?probe=3256d646b0) | Aug 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [9ec5eaeaf9](https://linux-hardware.org/?probe=9ec5eaeaf9) | Aug 06, 2021 |
| HP            | 2AF7                        | Desktop     | [1737071720](https://linux-hardware.org/?probe=1737071720) | Aug 06, 2021 |
| HP            | 2AF7                        | Desktop     | [c504247f44](https://linux-hardware.org/?probe=c504247f44) | Aug 06, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [31d159af99](https://linux-hardware.org/?probe=31d159af99) | Aug 06, 2021 |
| Dell          | Latitude E7240              | Notebook    | [4dd840f3dd](https://linux-hardware.org/?probe=4dd840f3dd) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [64b6992b74](https://linux-hardware.org/?probe=64b6992b74) | Aug 06, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [249a58dd07](https://linux-hardware.org/?probe=249a58dd07) | Aug 05, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [fa1f3da353](https://linux-hardware.org/?probe=fa1f3da353) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [812e20e37e](https://linux-hardware.org/?probe=812e20e37e) | Aug 05, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [b90c18f9a0](https://linux-hardware.org/?probe=b90c18f9a0) | Aug 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| Lenovo        | Board                       | Desktop     | [18138486db](https://linux-hardware.org/?probe=18138486db) | Aug 05, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [7caf949908](https://linux-hardware.org/?probe=7caf949908) | Aug 05, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [103dba0476](https://linux-hardware.org/?probe=103dba0476) | Aug 05, 2021 |
| HP            | ProBook 6450b               | Notebook    | [ec02a5333b](https://linux-hardware.org/?probe=ec02a5333b) | Aug 05, 2021 |
| HP            | 3085B                       | Notebook    | [6be769f55c](https://linux-hardware.org/?probe=6be769f55c) | Aug 05, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [0a79f49420](https://linux-hardware.org/?probe=0a79f49420) | Aug 05, 2021 |
| HP            | Pavilion dm4                | Notebook    | [7ba854b03e](https://linux-hardware.org/?probe=7ba854b03e) | Aug 05, 2021 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [f71032cd7f](https://linux-hardware.org/?probe=f71032cd7f) | Aug 05, 2021 |
| Unknown       | Intel X79                   | Desktop     | [fc0dedbb3c](https://linux-hardware.org/?probe=fc0dedbb3c) | Aug 05, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [10e9ef3d45](https://linux-hardware.org/?probe=10e9ef3d45) | Aug 05, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [4882999fd5](https://linux-hardware.org/?probe=4882999fd5) | Aug 04, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [a0e7632e28](https://linux-hardware.org/?probe=a0e7632e28) | Aug 04, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [803a6be591](https://linux-hardware.org/?probe=803a6be591) | Aug 04, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [8a70054744](https://linux-hardware.org/?probe=8a70054744) | Aug 04, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [cca5aa2900](https://linux-hardware.org/?probe=cca5aa2900) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2c8c33becf](https://linux-hardware.org/?probe=2c8c33becf) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [97f8f86784](https://linux-hardware.org/?probe=97f8f86784) | Aug 04, 2021 |
| Notebook      | NJ50_70CU                   | Notebook    | [a9b3790d07](https://linux-hardware.org/?probe=a9b3790d07) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2d764714a4](https://linux-hardware.org/?probe=2d764714a4) | Aug 04, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [a3914442ca](https://linux-hardware.org/?probe=a3914442ca) | Aug 04, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [b2a62f65d6](https://linux-hardware.org/?probe=b2a62f65d6) | Aug 04, 2021 |
| AMD           | 970A-D3                     | Desktop     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [09a6257403](https://linux-hardware.org/?probe=09a6257403) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [eafaf5ece3](https://linux-hardware.org/?probe=eafaf5ece3) | Aug 04, 2021 |
| ASUSTek       | N53Ta                       | Notebook    | [896a02b57b](https://linux-hardware.org/?probe=896a02b57b) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c0bf2b7b10](https://linux-hardware.org/?probe=c0bf2b7b10) | Aug 03, 2021 |
| HP            | 3047h                       | Desktop     | [6294617672](https://linux-hardware.org/?probe=6294617672) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [3d29b58c58](https://linux-hardware.org/?probe=3d29b58c58) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [8b35a81ed6](https://linux-hardware.org/?probe=8b35a81ed6) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [87bca8ecbc](https://linux-hardware.org/?probe=87bca8ecbc) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [fbbd748072](https://linux-hardware.org/?probe=fbbd748072) | Aug 03, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [a7bdbd8ebe](https://linux-hardware.org/?probe=a7bdbd8ebe) | Aug 03, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [55cd593df1](https://linux-hardware.org/?probe=55cd593df1) | Aug 03, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [71738ebf7e](https://linux-hardware.org/?probe=71738ebf7e) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [06d86172a1](https://linux-hardware.org/?probe=06d86172a1) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [aa415746d6](https://linux-hardware.org/?probe=aa415746d6) | Aug 03, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c8674581d0](https://linux-hardware.org/?probe=c8674581d0) | Aug 03, 2021 |
| Dell          | Latitude E4310              | Notebook    | [75a9aa20f2](https://linux-hardware.org/?probe=75a9aa20f2) | Aug 03, 2021 |
| Google        | Enguarde                    | Notebook    | [c758164470](https://linux-hardware.org/?probe=c758164470) | Aug 03, 2021 |
| Lenovo        | ThinkPad R61e 7650DHU       | Notebook    | [82f2f3a1a7](https://linux-hardware.org/?probe=82f2f3a1a7) | Aug 03, 2021 |
| ASUSTek       | 1005HA                      | Notebook    | [1f83d95a2a](https://linux-hardware.org/?probe=1f83d95a2a) | Aug 03, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | Notebook    | [c14dd630ed](https://linux-hardware.org/?probe=c14dd630ed) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [93b6f212af](https://linux-hardware.org/?probe=93b6f212af) | Aug 02, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99ccdd5455](https://linux-hardware.org/?probe=99ccdd5455) | Aug 02, 2021 |
| Supermicro    | X11SSH-F                    | Desktop     | [641e4fd8ce](https://linux-hardware.org/?probe=641e4fd8ce) | Aug 02, 2021 |
| Lenovo        | Reno                        | Server      | [91a367ab6d](https://linux-hardware.org/?probe=91a367ab6d) | Aug 02, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [aa5aaf6fd0](https://linux-hardware.org/?probe=aa5aaf6fd0) | Aug 02, 2021 |
| SimpliVity    | 04N3DF A03                  | Server      | [c5705e6436](https://linux-hardware.org/?probe=c5705e6436) | Aug 02, 2021 |
| Google        | Stout                       | Notebook    | [e4463bb3d4](https://linux-hardware.org/?probe=e4463bb3d4) | Aug 02, 2021 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [75a544682e](https://linux-hardware.org/?probe=75a544682e) | Aug 02, 2021 |
| Google        | Enguarde                    | Notebook    | [09406c6908](https://linux-hardware.org/?probe=09406c6908) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [01315f2df2](https://linux-hardware.org/?probe=01315f2df2) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e6ca37026c](https://linux-hardware.org/?probe=e6ca37026c) | Aug 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [70647a7f66](https://linux-hardware.org/?probe=70647a7f66) | Aug 02, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek       | P5QL-E                      | Desktop     | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | Notebook    | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ace43d8e9f](https://linux-hardware.org/?probe=ace43d8e9f) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [384ffe1123](https://linux-hardware.org/?probe=384ffe1123) | Aug 02, 2021 |
| ASUSTek       | A88X-PRO                    | Desktop     | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP            | 2187 A01                    | Desktop     | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [9c7fb8e911](https://linux-hardware.org/?probe=9c7fb8e911) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [8f40021fde](https://linux-hardware.org/?probe=8f40021fde) | Aug 01, 2021 |
| ASRock        | J1900D2Y                    | Desktop     | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | Notebook    | [9c317f536b](https://linux-hardware.org/?probe=9c317f536b) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [f851abbdf5](https://linux-hardware.org/?probe=f851abbdf5) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell          | 0WVYMC A00                  | Desktop     | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| Dell          | Vostro 5502                 | Notebook    | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | Notebook    | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0A60... | Notebook    | [8a3c585de4](https://linux-hardware.org/?probe=8a3c585de4) | Jul 30, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [a46cb950a4](https://linux-hardware.org/?probe=a46cb950a4) | Jul 29, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [acff56e8e3](https://linux-hardware.org/?probe=acff56e8e3) | Jul 29, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [704ead0e75](https://linux-hardware.org/?probe=704ead0e75) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| MSI           | Q45MDO                      | Desktop     | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [55c54d17ad](https://linux-hardware.org/?probe=55c54d17ad) | Jul 29, 2021 |
| MSI           | Q45MDO                      | Desktop     | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1bb07ffc9f](https://linux-hardware.org/?probe=1bb07ffc9f) | Jul 29, 2021 |
| Dell          | 0TY915                      | Desktop     | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek       | LEONITE                     | Desktop     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn       | 2AA9                        | Desktop     | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [16aeb37a86](https://linux-hardware.org/?probe=16aeb37a86) | Jul 29, 2021 |
| ASRock        | B85M Pro4                   | Desktop     | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| Acer          | Nitro AN517-41              | Notebook    | [ccc850c1da](https://linux-hardware.org/?probe=ccc850c1da) | Jul 29, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| Lenovo        | ThinkPad T420s 4174PEG      | Notebook    | [e448710e41](https://linux-hardware.org/?probe=e448710e41) | Jul 28, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [89d3c0f09d](https://linux-hardware.org/?probe=89d3c0f09d) | Jul 28, 2021 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | Notebook    | [bee4fd945a](https://linux-hardware.org/?probe=bee4fd945a) | Jul 28, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [21c6bb9dde](https://linux-hardware.org/?probe=21c6bb9dde) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [cc099348c2](https://linux-hardware.org/?probe=cc099348c2) | Jul 28, 2021 |
| Lenovo        | ThinkPad T470 20HES1UD00    | Notebook    | [6034f6a417](https://linux-hardware.org/?probe=6034f6a417) | Jul 28, 2021 |
| Lenovo        | ThinkPad X230 2325BQ3       | Notebook    | [79a19ade20](https://linux-hardware.org/?probe=79a19ade20) | Jul 28, 2021 |
| Dell          | Inspiron 8600               | Notebook    | [2f49d18738](https://linux-hardware.org/?probe=2f49d18738) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | Notebook    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| Shuttle       | FX79R                       | Desktop     | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| Acer          | Swift SF313-52G             | Notebook    | [87add43827](https://linux-hardware.org/?probe=87add43827) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| Casper        | C17B                        | Notebook    | [6f56921ba5](https://linux-hardware.org/?probe=6f56921ba5) | Jul 27, 2021 |
| ASRockRack    | X570D4U-2L2T                | Desktop     | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | Notebook    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [bc4f8acaf2](https://linux-hardware.org/?probe=bc4f8acaf2) | Jul 27, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [72032bc046](https://linux-hardware.org/?probe=72032bc046) | Jul 27, 2021 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn       | 915MH Series                | Desktop     | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| HP            | ProBook 635 Aero G7 Note... | Notebook    | [e6ee486690](https://linux-hardware.org/?probe=e6ee486690) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | Notebook    | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | Notebook    | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | Notebook    | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| ASRock        | Z97 Pro3                    | Desktop     | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| ASUSTek       | ZenBook Q536FD_Q536FD       | Convertible | [52e5d3e16d](https://linux-hardware.org/?probe=52e5d3e16d) | Jul 26, 2021 |
| MSI           | Z370 SLI PLUS               | Desktop     | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [e7aeecff98](https://linux-hardware.org/?probe=e7aeecff98) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | Notebook    | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | Notebook    | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Dell          | Studio 1555                 | Notebook    | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | Notebook    | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | Notebook    | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | Notebook    | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | Notebook    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | Notebook    | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | Notebook    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1e2b68b7d8](https://linux-hardware.org/?probe=1e2b68b7d8) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | Notebook    | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | Desktop     | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | Desktop     | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | Desktop     | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | Desktop     | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| IBM           | I/O Port                    | Server      | [8538814cd6](https://linux-hardware.org/?probe=8538814cd6) | Jul 25, 2021 |
| Dell          | 0Y1057                      | Desktop     | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | Notebook    | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | Desktop     | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | Notebook    | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | Desktop     | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | Notebook    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | Notebook    | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | Notebook    | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | Notebook    | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | Notebook    | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | Desktop     | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [f8ad21d44a](https://linux-hardware.org/?probe=f8ad21d44a) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | Notebook    | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | Desktop     | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| Lenovo        | 3110 SDK0J40697 WIN 3305... | All in one  | [84b6274afe](https://linux-hardware.org/?probe=84b6274afe) | Jul 25, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e1db015807](https://linux-hardware.org/?probe=e1db015807) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | Notebook    | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | Notebook    | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | Notebook    | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | Notebook    | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Compulab      | fitlet2                     | Mini pc     | [9d1571afa4](https://linux-hardware.org/?probe=9d1571afa4) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | Desktop     | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | Desktop     | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | Notebook    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | Notebook    | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | Notebook    | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Protectli     | FW6                         | Desktop     | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Lenovo        | Yoga 710-11ISK 80TX         | Convertible | [c34bcc095c](https://linux-hardware.org/?probe=c34bcc095c) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | Desktop     | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | Desktop     | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | Desktop     | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [0c49a20e7c](https://linux-hardware.org/?probe=0c49a20e7c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | Desktop     | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | Notebook    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | Notebook    | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [d3a887bf62](https://linux-hardware.org/?probe=d3a887bf62) | Jul 22, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [c3aac7e847](https://linux-hardware.org/?probe=c3aac7e847) | Jul 22, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [eeb04ca8d9](https://linux-hardware.org/?probe=eeb04ca8d9) | Jul 22, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [650e0a4954](https://linux-hardware.org/?probe=650e0a4954) | Jul 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| Supermicro    | X11DDW-L                    | Server      | [6fab4e3135](https://linux-hardware.org/?probe=6fab4e3135) | Jul 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| Dell          | 0H5J4J A01                  | Server      | [fbdf83f7ff](https://linux-hardware.org/?probe=fbdf83f7ff) | Jul 17, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | Notebook    | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [be4679a65b](https://linux-hardware.org/?probe=be4679a65b) | Jul 14, 2021 |
| Itautec       | Infoway                     | Notebook    | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8691cb3cb9](https://linux-hardware.org/?probe=8691cb3cb9) | Jul 12, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [d7722f9bbf](https://linux-hardware.org/?probe=d7722f9bbf) | Jul 12, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3eceba473e](https://linux-hardware.org/?probe=3eceba473e) | Jul 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [85da1219ad](https://linux-hardware.org/?probe=85da1219ad) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [145ca872cf](https://linux-hardware.org/?probe=145ca872cf) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [5ab6c73674](https://linux-hardware.org/?probe=5ab6c73674) | Jul 08, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [bccfe7e145](https://linux-hardware.org/?probe=bccfe7e145) | Jul 08, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [73a418aad6](https://linux-hardware.org/?probe=73a418aad6) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| Acer          | Aspire E5-573               | Notebook    | [d946214a58](https://linux-hardware.org/?probe=d946214a58) | Jul 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c80bd2ff96](https://linux-hardware.org/?probe=c80bd2ff96) | Jul 05, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e8da9b3b84](https://linux-hardware.org/?probe=e8da9b3b84) | Jul 05, 2021 |
| HP            | Compaq 6830s                | Notebook    | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| MSI           | MS-6712                     | Desktop     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| HP            | Compaq 6830s                | Notebook    | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [457f309f39](https://linux-hardware.org/?probe=457f309f39) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [945a4600c4](https://linux-hardware.org/?probe=945a4600c4) | Jul 02, 2021 |
| ASRock        | H77 Pro4-M                  | Desktop     | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [4ff716ad3a](https://linux-hardware.org/?probe=4ff716ad3a) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| ASUSTek       | K42Jv                       | Notebook    | [88ee690bb2](https://linux-hardware.org/?probe=88ee690bb2) | Jun 30, 2021 |
| Sony          | SVE1512G1RB                 | Notebook    | [41dd93f0c7](https://linux-hardware.org/?probe=41dd93f0c7) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | Notebook    | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [51edb744b9](https://linux-hardware.org/?probe=51edb744b9) | Jun 29, 2021 |
| MSI           | B85M-G43                    | Desktop     | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2) (... | Phone       | [6805b89f3d](https://linux-hardware.org/?probe=6805b89f3d) | Jun 25, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [25956c35fb](https://linux-hardware.org/?probe=25956c35fb) | Jun 24, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | Desktop     | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [f952173995](https://linux-hardware.org/?probe=f952173995) | Jun 23, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| Gigabyte      | B85M-D2V                    | Desktop     | [25f911e59c](https://linux-hardware.org/?probe=25f911e59c) | Jun 23, 2021 |
| Dell          | 04WYPY A04                  | Server      | [20fa770830](https://linux-hardware.org/?probe=20fa770830) | Jun 22, 2021 |
| Gigabyte      | B360M H                     | Desktop     | [fcddb198ec](https://linux-hardware.org/?probe=fcddb198ec) | Jun 22, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Gigabyte      | B85M-D2V                    | Desktop     | [a719f039de](https://linux-hardware.org/?probe=a719f039de) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [16cf7bfb30](https://linux-hardware.org/?probe=16cf7bfb30) | Jun 21, 2021 |
| Dell          | Precision 3560              | Notebook    | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | Notebook    | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [19fb8aa218](https://linux-hardware.org/?probe=19fb8aa218) | Jun 18, 2021 |
| HP            | ProBook 455 G1              | Notebook    | [c334d50b1f](https://linux-hardware.org/?probe=c334d50b1f) | Jun 18, 2021 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [a1f50d7038](https://linux-hardware.org/?probe=a1f50d7038) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [1dc449cb66](https://linux-hardware.org/?probe=1dc449cb66) | Jun 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [6511e56d8f](https://linux-hardware.org/?probe=6511e56d8f) | Jun 16, 2021 |
| Gigabyte      | B360M H                     | Desktop     | [44fd3744da](https://linux-hardware.org/?probe=44fd3744da) | Jun 16, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| ASUSTek       | P7H55                       | Desktop     | [c8abc22ac7](https://linux-hardware.org/?probe=c8abc22ac7) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | Desktop     | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [dc6ae81a40](https://linux-hardware.org/?probe=dc6ae81a40) | Jun 11, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [359862901e](https://linux-hardware.org/?probe=359862901e) | Jun 11, 2021 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [b081ed3973](https://linux-hardware.org/?probe=b081ed3973) | Jun 11, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [0de49e4ceb](https://linux-hardware.org/?probe=0de49e4ceb) | Jun 11, 2021 |
| Unknown       | Helios64                    | Soc         | [33c6248333](https://linux-hardware.org/?probe=33c6248333) | Jun 11, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| Dell          | Latitude E7470              | Notebook    | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | Desktop     | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| Clevo         | W250ENQ / W270ENQ           | Notebook    | [95fe5984c2](https://linux-hardware.org/?probe=95fe5984c2) | Jun 09, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [50a33d0c01](https://linux-hardware.org/?probe=50a33d0c01) | Jun 09, 2021 |
| Clevo         | W250ENQ / W270ENQ           | Notebook    | [b992eee8b5](https://linux-hardware.org/?probe=b992eee8b5) | Jun 09, 2021 |
| ASUSTek       | P5QL-CM                     | Desktop     | [2eb12a165a](https://linux-hardware.org/?probe=2eb12a165a) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | Notebook    | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| Gigabyte      | P43-ES3G                    | Desktop     | [86c3abf0e6](https://linux-hardware.org/?probe=86c3abf0e6) | Jun 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [15fdd98402](https://linux-hardware.org/?probe=15fdd98402) | Jun 07, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | Notebook    | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f543bd7919](https://linux-hardware.org/?probe=f543bd7919) | Jun 02, 2021 |
| Pegatron      | A15                         | Notebook    | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| Intel         | DP965LT AAD41694-209        | Desktop     | [64b76f3b3d](https://linux-hardware.org/?probe=64b76f3b3d) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [446457dc79](https://linux-hardware.org/?probe=446457dc79) | Jun 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [d71fba3e59](https://linux-hardware.org/?probe=d71fba3e59) | Jun 01, 2021 |
| ASUSTek       | P5QL-CM                     | Desktop     | [53e36afc53](https://linux-hardware.org/?probe=53e36afc53) | Jun 01, 2021 |
| Intel         | DG965RY AAD41691-206        | Desktop     | [1b04d7a76f](https://linux-hardware.org/?probe=1b04d7a76f) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | Notebook    | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f77e2ebb10](https://linux-hardware.org/?probe=f77e2ebb10) | May 31, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [31547cbbcf](https://linux-hardware.org/?probe=31547cbbcf) | May 31, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [4392e54288](https://linux-hardware.org/?probe=4392e54288) | May 31, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [2fda3b392d](https://linux-hardware.org/?probe=2fda3b392d) | May 31, 2021 |
| Medion        | MS-7616                     | Desktop     | [c3730db7dd](https://linux-hardware.org/?probe=c3730db7dd) | May 31, 2021 |
| ASUSTek       | P7H55                       | Desktop     | [ac572ef424](https://linux-hardware.org/?probe=ac572ef424) | May 31, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [41c4d75b72](https://linux-hardware.org/?probe=41c4d75b72) | May 31, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [8b834e3fc0](https://linux-hardware.org/?probe=8b834e3fc0) | May 31, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [8932eef460](https://linux-hardware.org/?probe=8932eef460) | May 31, 2021 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Toshiba       | Satellite U800W             | Notebook    | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [eb3d04e089](https://linux-hardware.org/?probe=eb3d04e089) | May 29, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [92aa2017b9](https://linux-hardware.org/?probe=92aa2017b9) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI           | CX700                       | Notebook    | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [7ca350189c](https://linux-hardware.org/?probe=7ca350189c) | May 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | Notebook    | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | Notebook    | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [e00920532d](https://linux-hardware.org/?probe=e00920532d) | May 27, 2021 |
| Lenovo        | Z710 20250                  | Notebook    | [76d72eb45f](https://linux-hardware.org/?probe=76d72eb45f) | May 27, 2021 |
| Aquarius      | NS585                       | Notebook    | [e2035017ff](https://linux-hardware.org/?probe=e2035017ff) | May 26, 2021 |
| Aquarius      | NS585                       | Notebook    | [d2b5b53798](https://linux-hardware.org/?probe=d2b5b53798) | May 26, 2021 |
| Aquarius      | NS585                       | Notebook    | [1c84a98f48](https://linux-hardware.org/?probe=1c84a98f48) | May 26, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Gigabyte      | H81M-S1                     | Desktop     | [07fcf530f1](https://linux-hardware.org/?probe=07fcf530f1) | May 24, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [834e2e7b7e](https://linux-hardware.org/?probe=834e2e7b7e) | May 24, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [71c9c1e86f](https://linux-hardware.org/?probe=71c9c1e86f) | May 21, 2021 |
| Dell          | Latitude 7410               | Convertible | [bc7c58f248](https://linux-hardware.org/?probe=bc7c58f248) | May 21, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [8947349c20](https://linux-hardware.org/?probe=8947349c20) | May 21, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [1c271464f4](https://linux-hardware.org/?probe=1c271464f4) | May 21, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [95f4bad7b5](https://linux-hardware.org/?probe=95f4bad7b5) | May 20, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7410               | Convertible | [cbd8832f44](https://linux-hardware.org/?probe=cbd8832f44) | May 19, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | Notebook    | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| sunxi         | Unknown                     | Soc         | [d54c3a2a33](https://linux-hardware.org/?probe=d54c3a2a33) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [f2d7c64e1c](https://linux-hardware.org/?probe=f2d7c64e1c) | May 18, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [b471b7cf95](https://linux-hardware.org/?probe=b471b7cf95) | May 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FEA0... | Convertible | [2a0eca4670](https://linux-hardware.org/?probe=2a0eca4670) | May 17, 2021 |
| HP            | Compaq Presario C700        | Notebook    | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [1699c8eab5](https://linux-hardware.org/?probe=1699c8eab5) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [bd2a3417a0](https://linux-hardware.org/?probe=bd2a3417a0) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [3a27d20178](https://linux-hardware.org/?probe=3a27d20178) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [17ff2add7a](https://linux-hardware.org/?probe=17ff2add7a) | May 14, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [07ea2a4b8e](https://linux-hardware.org/?probe=07ea2a4b8e) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [823bbbb4ed](https://linux-hardware.org/?probe=823bbbb4ed) | May 12, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [af6e17ac8c](https://linux-hardware.org/?probe=af6e17ac8c) | May 12, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [f6d2299c81](https://linux-hardware.org/?probe=f6d2299c81) | May 12, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [380bf2eacc](https://linux-hardware.org/?probe=380bf2eacc) | May 11, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [589d53b7ce](https://linux-hardware.org/?probe=589d53b7ce) | May 11, 2021 |
| ASUSTek       | T100TAS                     | Notebook    | [0b8e360f8a](https://linux-hardware.org/?probe=0b8e360f8a) | May 07, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| HP            | Split 13 x2 PC              | Notebook    | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [0c87980ed4](https://linux-hardware.org/?probe=0c87980ed4) | Apr 29, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [372d11517d](https://linux-hardware.org/?probe=372d11517d) | Apr 28, 2021 |
| Pegatron      | C15B                        | Desktop     | [54d1d5cde0](https://linux-hardware.org/?probe=54d1d5cde0) | Apr 27, 2021 |
| Lenovo        | G550 20023                  | Notebook    | [69b57eec89](https://linux-hardware.org/?probe=69b57eec89) | Apr 27, 2021 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| Biostar       | B450MH                      | Desktop     | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [89d9898d88](https://linux-hardware.org/?probe=89d9898d88) | Apr 26, 2021 |
| HP            | 3399                        | Desktop     | [4085344b20](https://linux-hardware.org/?probe=4085344b20) | Apr 26, 2021 |
| ASUSTek       | P8Z77-M                     | Desktop     | [8495ecf36e](https://linux-hardware.org/?probe=8495ecf36e) | Apr 26, 2021 |
| Acer          | Aspire 5560                 | Notebook    | [853337664f](https://linux-hardware.org/?probe=853337664f) | Apr 26, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [446238dd0c](https://linux-hardware.org/?probe=446238dd0c) | Apr 25, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [bb76391a12](https://linux-hardware.org/?probe=bb76391a12) | Apr 25, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1c397e42c6](https://linux-hardware.org/?probe=1c397e42c6) | Apr 23, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [fc24c1c56f](https://linux-hardware.org/?probe=fc24c1c56f) | Apr 23, 2021 |
| Dell          | Latitude E6330              | Notebook    | [d2a06d1cde](https://linux-hardware.org/?probe=d2a06d1cde) | Apr 22, 2021 |
| HP            | 3399                        | Desktop     | [a265b73c37](https://linux-hardware.org/?probe=a265b73c37) | Apr 22, 2021 |
| Gigabyte      | H410M S2H                   | Desktop     | [88f270d1d0](https://linux-hardware.org/?probe=88f270d1d0) | Apr 22, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [60eb0d02a7](https://linux-hardware.org/?probe=60eb0d02a7) | Apr 21, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | Notebook    | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6cdd8afad1](https://linux-hardware.org/?probe=6cdd8afad1) | Apr 19, 2021 |
| ECS           | G31T-M7                     | Desktop     | [4e1e8d1c1a](https://linux-hardware.org/?probe=4e1e8d1c1a) | Apr 19, 2021 |
| ECS           | G31T-M7                     | Desktop     | [2ffcd0d78d](https://linux-hardware.org/?probe=2ffcd0d78d) | Apr 19, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [921cfbf363](https://linux-hardware.org/?probe=921cfbf363) | Apr 18, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [92866f8994](https://linux-hardware.org/?probe=92866f8994) | Apr 17, 2021 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |
| HP            | 3399                        | Desktop     | [ae0ed46819](https://linux-hardware.org/?probe=ae0ed46819) | Apr 16, 2021 |
| MSI           | G41M-P28                    | Desktop     | [0b714b1814](https://linux-hardware.org/?probe=0b714b1814) | Apr 16, 2021 |
| HP            | Pavilion g6                 | Notebook    | [7a88de99e8](https://linux-hardware.org/?probe=7a88de99e8) | Apr 16, 2021 |
| Intel         | DQ45CB AAE30148-206         | Desktop     | [6a9f891230](https://linux-hardware.org/?probe=6a9f891230) | Apr 15, 2021 |
| HP            | Pavilion g6                 | Notebook    | [8f9f4e211d](https://linux-hardware.org/?probe=8f9f4e211d) | Apr 15, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [7a1d829bbb](https://linux-hardware.org/?probe=7a1d829bbb) | Apr 14, 2021 |
| HP            | Pavilion g6                 | Notebook    | [d3e2f03de0](https://linux-hardware.org/?probe=d3e2f03de0) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [97a320e9df](https://linux-hardware.org/?probe=97a320e9df) | Apr 14, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [c0536c5433](https://linux-hardware.org/?probe=c0536c5433) | Apr 13, 2021 |
| HP            | Pavilion 17                 | Notebook    | [9bd4ef879a](https://linux-hardware.org/?probe=9bd4ef879a) | Apr 12, 2021 |
| Sony          | VPCEJ3S1R                   | Notebook    | [a57c607409](https://linux-hardware.org/?probe=a57c607409) | Apr 12, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [9f79d5f548](https://linux-hardware.org/?probe=9f79d5f548) | Apr 09, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [d90f3a34d1](https://linux-hardware.org/?probe=d90f3a34d1) | Apr 08, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [2f2f027581](https://linux-hardware.org/?probe=2f2f027581) | Apr 07, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [a0bb6867cd](https://linux-hardware.org/?probe=a0bb6867cd) | Apr 07, 2021 |
| ASUSTek       | P5B                         | Desktop     | [e6f18312ca](https://linux-hardware.org/?probe=e6f18312ca) | Apr 07, 2021 |
| Dell          | Latitude E6330              | Notebook    | [46855c6116](https://linux-hardware.org/?probe=46855c6116) | Apr 07, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [1ae4d948e8](https://linux-hardware.org/?probe=1ae4d948e8) | Apr 06, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [b8439c6414](https://linux-hardware.org/?probe=b8439c6414) | Apr 04, 2021 |
| Notebook      | N650DU                      | Notebook    | [34efc4fdfe](https://linux-hardware.org/?probe=34efc4fdfe) | Apr 02, 2021 |
| ECS           | G31T-M9                     | Desktop     | [769cb653f7](https://linux-hardware.org/?probe=769cb653f7) | Apr 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 20HRC... | Notebook    | [354cd6e94e](https://linux-hardware.org/?probe=354cd6e94e) | Apr 02, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [6ba14141a6](https://linux-hardware.org/?probe=6ba14141a6) | Apr 01, 2021 |
| Acer          | TravelMate P259-MG          | Notebook    | [9acbd94cd7](https://linux-hardware.org/?probe=9acbd94cd7) | Apr 01, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [f2e276c03d](https://linux-hardware.org/?probe=f2e276c03d) | Apr 01, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [b93f919e23](https://linux-hardware.org/?probe=b93f919e23) | Mar 31, 2021 |
| Intel         | DG33FB AAD81072-303         | Desktop     | [df4527f66c](https://linux-hardware.org/?probe=df4527f66c) | Mar 31, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [2e925f1ee2](https://linux-hardware.org/?probe=2e925f1ee2) | Mar 30, 2021 |
| ASUSTek       | P5K-VM                      | Desktop     | [4c297474dc](https://linux-hardware.org/?probe=4c297474dc) | Mar 30, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [8d09fd5fad](https://linux-hardware.org/?probe=8d09fd5fad) | Mar 29, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [d22bc80177](https://linux-hardware.org/?probe=d22bc80177) | Mar 29, 2021 |
| Micro Elec... | MG-VCTR002-2060             | Notebook    | [3724755eea](https://linux-hardware.org/?probe=3724755eea) | Mar 28, 2021 |
| HP            | ProBook 4520s               | Notebook    | [7577a208f6](https://linux-hardware.org/?probe=7577a208f6) | Mar 22, 2021 |
| ASUSTek       | Z87I-DELUXE                 | Desktop     | [34a8087893](https://linux-hardware.org/?probe=34a8087893) | Mar 22, 2021 |
| Lenovo        | 3706 SDK0J40700 WIN 3258... | Desktop     | [3876e9ed84](https://linux-hardware.org/?probe=3876e9ed84) | Mar 21, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [2d50a5e736](https://linux-hardware.org/?probe=2d50a5e736) | Mar 21, 2021 |
| Acer          | One S1003                   | Tablet      | [5e5544872a](https://linux-hardware.org/?probe=5e5544872a) | Mar 20, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [be20eafb4f](https://linux-hardware.org/?probe=be20eafb4f) | Mar 20, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [0dd442a763](https://linux-hardware.org/?probe=0dd442a763) | Mar 19, 2021 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [f4050ccf53](https://linux-hardware.org/?probe=f4050ccf53) | Mar 18, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [f20eacbf5c](https://linux-hardware.org/?probe=f20eacbf5c) | Mar 18, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [e3d85d4006](https://linux-hardware.org/?probe=e3d85d4006) | Mar 15, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [3c8f0ff2d4](https://linux-hardware.org/?probe=3c8f0ff2d4) | Mar 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [bcdd60dc85](https://linux-hardware.org/?probe=bcdd60dc85) | Mar 14, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [2f3f591fd0](https://linux-hardware.org/?probe=2f3f591fd0) | Mar 10, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [bd5d97f7e7](https://linux-hardware.org/?probe=bd5d97f7e7) | Mar 07, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [d2ee782761](https://linux-hardware.org/?probe=d2ee782761) | Mar 07, 2021 |
| ASUSTek       | K53E                        | Notebook    | [f84c0f2b1b](https://linux-hardware.org/?probe=f84c0f2b1b) | Mar 05, 2021 |
| Micro Elec... | MG-VCTR002-2060             | Notebook    | [f86910b3b3](https://linux-hardware.org/?probe=f86910b3b3) | Mar 05, 2021 |
| ASUSTek       | K53E                        | Notebook    | [8a98e99c2f](https://linux-hardware.org/?probe=8a98e99c2f) | Mar 05, 2021 |
| Intel         | DG31PR AAD97573-301         | Desktop     | [09e15a8c00](https://linux-hardware.org/?probe=09e15a8c00) | Mar 04, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [db2b8a39be](https://linux-hardware.org/?probe=db2b8a39be) | Mar 03, 2021 |
| Lenovo        | ThinkPad T430 2349PS9       | Notebook    | [4f805206d4](https://linux-hardware.org/?probe=4f805206d4) | Mar 03, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [d8b4e607e1](https://linux-hardware.org/?probe=d8b4e607e1) | Mar 02, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [eca0e7f55f](https://linux-hardware.org/?probe=eca0e7f55f) | Mar 02, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [88c5aee182](https://linux-hardware.org/?probe=88c5aee182) | Mar 02, 2021 |
| Lenovo        | V570 HuronRiver Platform    | Notebook    | [d93b0955fa](https://linux-hardware.org/?probe=d93b0955fa) | Feb 27, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [744852fa69](https://linux-hardware.org/?probe=744852fa69) | Feb 25, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [720734ca06](https://linux-hardware.org/?probe=720734ca06) | Feb 25, 2021 |
| Dell          | Inspiron 5759               | Notebook    | [3710e0320f](https://linux-hardware.org/?probe=3710e0320f) | Feb 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3bb9f3d0f3](https://linux-hardware.org/?probe=3bb9f3d0f3) | Feb 23, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [88bab7f6e7](https://linux-hardware.org/?probe=88bab7f6e7) | Feb 22, 2021 |
| HP            | ENVY Notebook               | Notebook    | [e4cc508565](https://linux-hardware.org/?probe=e4cc508565) | Feb 21, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [6642872403](https://linux-hardware.org/?probe=6642872403) | Feb 19, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [da5067a065](https://linux-hardware.org/?probe=da5067a065) | Feb 18, 2021 |
| Dell          | Latitude E6440              | Notebook    | [ce086f8df0](https://linux-hardware.org/?probe=ce086f8df0) | Feb 18, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [77da992403](https://linux-hardware.org/?probe=77da992403) | Feb 14, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [2e19efe5b1](https://linux-hardware.org/?probe=2e19efe5b1) | Feb 12, 2021 |
| Dell          | Inspiron 5759               | Notebook    | [e7c528c9be](https://linux-hardware.org/?probe=e7c528c9be) | Feb 11, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [97e14d7021](https://linux-hardware.org/?probe=97e14d7021) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [954514a52a](https://linux-hardware.org/?probe=954514a52a) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [67f2a70d2a](https://linux-hardware.org/?probe=67f2a70d2a) | Feb 09, 2021 |
| Dell          | Inspiron 5759               | Notebook    | [cd72d5cd68](https://linux-hardware.org/?probe=cd72d5cd68) | Feb 09, 2021 |
| Dell          | Latitude 7400               | Notebook    | [32c7787bcb](https://linux-hardware.org/?probe=32c7787bcb) | Feb 04, 2021 |
| MSI           | MS-7329                     | Desktop     | [d67a4df7d0](https://linux-hardware.org/?probe=d67a4df7d0) | Feb 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [9b82b49d40](https://linux-hardware.org/?probe=9b82b49d40) | Feb 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [6acba7c545](https://linux-hardware.org/?probe=6acba7c545) | Feb 03, 2021 |
| Unknown       | Unknown                     | Notebook    | [ad10dd6be0](https://linux-hardware.org/?probe=ad10dd6be0) | Feb 03, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [935ccffcd5](https://linux-hardware.org/?probe=935ccffcd5) | Feb 01, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [96d6904297](https://linux-hardware.org/?probe=96d6904297) | Feb 01, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [67cfeeb58a](https://linux-hardware.org/?probe=67cfeeb58a) | Jan 31, 2021 |
| Dell          | 0KWVT8 A02                  | Desktop     | [4bff426962](https://linux-hardware.org/?probe=4bff426962) | Jan 31, 2021 |
| Unknown       | Unknown                     | Notebook    | [ea0d120a2b](https://linux-hardware.org/?probe=ea0d120a2b) | Jan 31, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [288a08d946](https://linux-hardware.org/?probe=288a08d946) | Jan 26, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5d23694899](https://linux-hardware.org/?probe=5d23694899) | Jan 24, 2021 |
| Positivo      | C14CR21                     | Notebook    | [0807ce46f1](https://linux-hardware.org/?probe=0807ce46f1) | Jan 19, 2021 |
| Unknown       | Shenzhen Amediatech Tech... | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [4bdbb16f3d](https://linux-hardware.org/?probe=4bdbb16f3d) | Jan 17, 2021 |
| Acer          | Aspire 5750Z                | Notebook    | [14ca9bb504](https://linux-hardware.org/?probe=14ca9bb504) | Jan 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [286214a4e2](https://linux-hardware.org/?probe=286214a4e2) | Jan 15, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [04b6596686](https://linux-hardware.org/?probe=04b6596686) | Jan 13, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [1ec8c1ccd1](https://linux-hardware.org/?probe=1ec8c1ccd1) | Jan 13, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [6afcc11fef](https://linux-hardware.org/?probe=6afcc11fef) | Jan 08, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [1708c28c7b](https://linux-hardware.org/?probe=1708c28c7b) | Jan 08, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [3653c47477](https://linux-hardware.org/?probe=3653c47477) | Jan 07, 2021 |
| Dell          | 0K83V0 A00                  | Desktop     | [54858a0cb0](https://linux-hardware.org/?probe=54858a0cb0) | Jan 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [1d09a49510](https://linux-hardware.org/?probe=1d09a49510) | Jan 04, 2021 |
| sunxi         | Unknown                     | Soc         | [604dd9d393](https://linux-hardware.org/?probe=604dd9d393) | Feb 25, 2020 |
| Lenovo        | ThinkPad E480 20KN001NMX    | Notebook    | [4f055c0cf5](https://linux-hardware.org/?probe=4f055c0cf5) | Oct 08, 2019 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [8d9dbecbba](https://linux-hardware.org/?probe=8d9dbecbba) | Aug 11, 2019 |
| Dell          | Inspiron 11-3168            | Notebook    | [3831423c95](https://linux-hardware.org/?probe=3831423c95) | Jun 30, 2019 |
| Dell          | Inspiron 11-3168            | Notebook    | [4343600da2](https://linux-hardware.org/?probe=4343600da2) | Jun 30, 2019 |
| Dell          | Inspiron 11-3168            | Notebook    | [a1f5874ef6](https://linux-hardware.org/?probe=a1f5874ef6) | Jun 30, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.0-8-amd64                 | 621       | 57.13%  |
| 5.10.0-7-amd64                 | 178       | 16.38%  |
| 5.10.0-2-amd64                 | 105       | 9.66%   |
| 5.10.0-6-amd64                 | 44        | 4.05%   |
| 5.10.0-3-amd64                 | 14        | 1.29%   |
| 5.10.0-8-686-pae               | 10        | 0.92%   |
| 5.10.0-4-amd64                 | 10        | 0.92%   |
| 5.10.0-5-amd64                 | 8         | 0.74%   |
| 5.10.0-8-686                   | 7         | 0.64%   |
| 5.10.0-1-amd64                 | 6         | 0.55%   |
| 5.11.22-1-pve                  | 5         | 0.46%   |
| 5.10-sunxi64                   | 4         | 0.37%   |
| 5.12.0-19.3-liquorix-amd64     | 3         | 0.28%   |
| 5.11.22-2-pve                  | 3         | 0.28%   |
| 5.10.0-8-armmp-lpae            | 3         | 0.28%   |
| 5.13.0-13.1-liquorix-amd64     | 2         | 0.18%   |
| 5.11.22-3-pve                  | 2         | 0.18%   |
| 5.10.42+truenas                | 2         | 0.18%   |
| 5.10.0-8-rt-amd64              | 2         | 0.18%   |
| 4.19.0-14-amd64                | 2         | 0.18%   |
| 5.9.0-arm-64                   | 1         | 0.09%   |
| 5.8.0-3-amd64                  | 1         | 0.09%   |
| 5.4.18-sunxi64                 | 1         | 0.09%   |
| 5.4.0-73-generic               | 1         | 0.09%   |
| 5.14.0-rc3-prygun              | 1         | 0.09%   |
| 5.14.0+                        | 1         | 0.09%   |
| 5.13.8-xanmod1                 | 1         | 0.09%   |
| 5.13.8-gnu                     | 1         | 0.09%   |
| 5.13.8                         | 1         | 0.09%   |
| 5.13.5-xanmod1                 | 1         | 0.09%   |
| 5.13.4-e5520                   | 1         | 0.09%   |
| 5.13.4                         | 1         | 0.09%   |
| 5.13.1a                        | 1         | 0.09%   |
| 5.13.13-arch1-1                | 1         | 0.09%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1         | 0.09%   |
| 5.13.0-10.3-liquorix-amd64     | 1         | 0.09%   |
| 5.12.4                         | 1         | 0.09%   |
| 5.12.18-amd64-desktop          | 1         | 0.09%   |
| 5.12.14-amd64-desktop          | 1         | 0.09%   |
| 5.12.10                        | 1         | 0.09%   |
| 5.12.1                         | 1         | 0.09%   |
| 5.12.0-9.2-liquorix-amd64      | 1         | 0.09%   |
| 5.12.0-14.2-liquorix-amd64     | 1         | 0.09%   |
| 5.11.9+                        | 1         | 0.09%   |
| 5.11.15-terranz                | 1         | 0.09%   |
| 5.11.15-051115-generic         | 1         | 0.09%   |
| 5.11.14                        | 1         | 0.09%   |
| 5.11.0-rc6                     | 1         | 0.09%   |
| 5.11.0-21.1-liquorix-amd64     | 1         | 0.09%   |
| 5.11.0-16.1-liquorix-amd64     | 1         | 0.09%   |
| 5.11.0-11.1-liquorix-amd64     | 1         | 0.09%   |
| 5.10.52-v8+                    | 1         | 0.09%   |
| 5.10.46custom                  | 1         | 0.09%   |
| 5.10.40-ismynik                | 1         | 0.09%   |
| 5.10.38-falcot                 | 1         | 0.09%   |
| 5.10.35-rockchip64             | 1         | 0.09%   |
| 5.10.21-sunxi                  | 1         | 0.09%   |
| 5.10.18-xanmod1                | 1         | 0.09%   |
| 5.10.12-sunxi                  | 1         | 0.09%   |
| 5.10.10-64                     | 1         | 0.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 985       | 93.28%  |
| 5.11.22  | 10        | 0.95%   |
| 4.19.0   | 6         | 0.57%   |
| 5.13.0   | 4         | 0.38%   |
| 5.12.0   | 4         | 0.38%   |
| 5.11.0   | 4         | 0.38%   |
| 5.10     | 4         | 0.38%   |
| 5.13.8   | 3         | 0.28%   |
| 5.14.0   | 2         | 0.19%   |
| 5.13.4   | 2         | 0.19%   |
| 5.11.15  | 2         | 0.19%   |
| 5.10.42  | 2         | 0.19%   |
| 5.10.10  | 2         | 0.19%   |
| 5.1.0    | 2         | 0.19%   |
| 5.9.0    | 1         | 0.09%   |
| 5.8.0    | 1         | 0.09%   |
| 5.4.18   | 1         | 0.09%   |
| 5.4.0    | 1         | 0.09%   |
| 5.13.5   | 1         | 0.09%   |
| 5.13.13  | 1         | 0.09%   |
| 5.13.1   | 1         | 0.09%   |
| 5.12.4   | 1         | 0.09%   |
| 5.12.18  | 1         | 0.09%   |
| 5.12.14  | 1         | 0.09%   |
| 5.12.10  | 1         | 0.09%   |
| 5.12.1   | 1         | 0.09%   |
| 5.11.9   | 1         | 0.09%   |
| 5.11.14  | 1         | 0.09%   |
| 5.10.52  | 1         | 0.09%   |
| 5.10.46  | 1         | 0.09%   |
| 5.10.40  | 1         | 0.09%   |
| 5.10.38  | 1         | 0.09%   |
| 5.10.35  | 1         | 0.09%   |
| 5.10.21  | 1         | 0.09%   |
| 5.10.18  | 1         | 0.09%   |
| 5.10.12  | 1         | 0.09%   |
| 5.1.12   | 1         | 0.09%   |
| 4.19.181 | 1         | 0.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 996       | 94.41%  |
| 5.11    | 18        | 1.71%   |
| 5.13    | 12        | 1.14%   |
| 5.12    | 9         | 0.85%   |
| 4.19    | 7         | 0.66%   |
| 5       | 4         | 0.38%   |
| 5.1     | 3         | 0.28%   |
| 5.4     | 2         | 0.19%   |
| 5.14    | 2         | 0.19%   |
| 5.9     | 1         | 0.09%   |
| 5.8     | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1016      | 96.58%  |
| i686    | 22        | 2.09%   |
| aarch64 | 9         | 0.86%   |
| armv7l  | 5         | 0.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 465       | 43.83%  |
| GNOME            | 210       | 19.79%  |
| KDE5             | 123       | 11.59%  |
| XFCE             | 79        | 7.45%   |
| MATE             | 44        | 4.15%   |
| KDE              | 23        | 2.17%   |
| i3               | 20        | 1.89%   |
| Cinnamon         | 18        | 1.7%    |
| X-Cinnamon       | 16        | 1.51%   |
| LXQt             | 15        | 1.41%   |
| LXDE             | 15        | 1.41%   |
| lightdm-xsession | 7         | 0.66%   |
| Trinity          | 6         | 0.57%   |
| GNOME Flashback  | 5         | 0.47%   |
| openbox          | 3         | 0.28%   |
| sway             | 2         | 0.19%   |
| Enlightenment    | 2         | 0.19%   |
| Budgie           | 2         | 0.19%   |
| awesome          | 2         | 0.19%   |
| ICEWM            | 1         | 0.09%   |
| GNUstep          | 1         | 0.09%   |
| default          | 1         | 0.09%   |
| Deepin           | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 435       | 41.04%  |
| Unknown | 416       | 39.25%  |
| Wayland | 151       | 14.25%  |
| Tty     | 58        | 5.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 554       | 52.31%  |
| GDM     | 176       | 16.62%  |
| TDM     | 155       | 14.64%  |
| SDDM    | 127       | 11.99%  |
| LightDM | 39        | 3.68%   |
| SLiM    | 3         | 0.28%   |
| XDM     | 2         | 0.19%   |
| NODM    | 1         | 0.09%   |
| KDM     | 1         | 0.09%   |
| GDM3    | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 301       | 28.53%  |
| Unknown | 233       | 22.09%  |
| ru_RU   | 202       | 19.15%  |
| en_GB   | 47        | 4.45%   |
| fr_FR   | 36        | 3.41%   |
| de_DE   | 34        | 3.22%   |
| es_ES   | 23        | 2.18%   |
| pt_BR   | 21        | 1.99%   |
| pl_PL   | 15        | 1.42%   |
| C       | 11        | 1.04%   |
| en_AU   | 9         | 0.85%   |
| en_IN   | 8         | 0.76%   |
| it_IT   | 7         | 0.66%   |
| en_CA   | 7         | 0.66%   |
| tr_TR   | 6         | 0.57%   |
| sv_SE   | 6         | 0.57%   |
| es_MX   | 6         | 0.57%   |
| de_CH   | 6         | 0.57%   |
| nl_BE   | 5         | 0.47%   |
| ja_JP   | 5         | 0.47%   |
| pt_PT   | 4         | 0.38%   |
| hu_HU   | 4         | 0.38%   |
| zh_CN   | 3         | 0.28%   |
| nn_NO   | 3         | 0.28%   |
| nl_NL   | 3         | 0.28%   |
| fi_FI   | 3         | 0.28%   |
| es_VE   | 3         | 0.28%   |
| en_IE   | 3         | 0.28%   |
| de_AT   | 3         | 0.28%   |
| cs_CZ   | 3         | 0.28%   |
| uk_UA   | 2         | 0.19%   |
| sk_SK   | 2         | 0.19%   |
| ru_UA   | 2         | 0.19%   |
| ro_RO   | 2         | 0.19%   |
| hr_HR   | 2         | 0.19%   |
| es_CO   | 2         | 0.19%   |
| es_AR   | 2         | 0.19%   |
| en_ZA   | 2         | 0.19%   |
| en_SG   | 2         | 0.19%   |
| en_NZ   | 2         | 0.19%   |
| en_HK   | 2         | 0.19%   |
| bg_BG   | 2         | 0.19%   |
| sr_RS   | 1         | 0.09%   |
| gl_ES   | 1         | 0.09%   |
| es_UY   | 1         | 0.09%   |
| es_US   | 1         | 0.09%   |
| es_GT   | 1         | 0.09%   |
| es_EC   | 1         | 0.09%   |
| eo      | 1         | 0.09%   |
| en_SI   | 1         | 0.09%   |
| en_PH   | 1         | 0.09%   |
| en_DK   | 1         | 0.09%   |
| ca_ES   | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 632       | 59.74%  |
| BIOS | 426       | 40.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 536       | 50.95%  |
| Overlay | 432       | 41.06%  |
| Btrfs   | 51        | 4.85%   |
| Zfs     | 11        | 1.05%   |
| Xfs     | 8         | 0.76%   |
| Ext3    | 6         | 0.57%   |
| Unknown | 4         | 0.38%   |
| Rootfs  | 2         | 0.19%   |
| Tmpfs   | 1         | 0.1%    |
| Ext2    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 678       | 64.2%   |
| MBR     | 277       | 26.23%  |
| Unknown | 101       | 9.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 941       | 89.28%  |
| Yes       | 113       | 10.72%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 727       | 68.91%  |
| Yes       | 328       | 31.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 164       | 15.59%  |
| Apple                   | 158       | 15.02%  |
| ASUSTek Computer        | 145       | 13.78%  |
| Hewlett-Packard         | 94        | 8.94%   |
| Dell                    | 91        | 8.65%   |
| Gigabyte Technology     | 70        | 6.65%   |
| ASRock                  | 65        | 6.18%   |
| Google                  | 49        | 4.66%   |
| Acer                    | 42        | 3.99%   |
| MSI                     | 40        | 3.8%    |
| Intel                   | 20        | 1.9%    |
| Fujitsu                 | 8         | 0.76%   |
| ECS                     | 7         | 0.67%   |
| Supermicro              | 5         | 0.48%   |
| Unknown                 | 5         | 0.48%   |
| Toshiba                 | 4         | 0.38%   |
| Sony                    | 4         | 0.38%   |
| Samsung Electronics     | 4         | 0.38%   |
| Pine Microsystems       | 4         | 0.38%   |
| Notebook                | 4         | 0.38%   |
| HUAWEI                  | 4         | 0.38%   |
| Hardkernel              | 4         | 0.38%   |
| Foxconn                 | 4         | 0.38%   |
| Clevo                   | 4         | 0.38%   |
| sunxi                   | 3         | 0.29%   |
| Pegatron                | 3         | 0.29%   |
| AMI                     | 3         | 0.29%   |
| Timi                    | 2         | 0.19%   |
| SLIMBOOK                | 2         | 0.19%   |
| Semp Toshiba            | 2         | 0.19%   |
| Raspberry Pi Foundation | 2         | 0.19%   |
| Huanan                  | 2         | 0.19%   |
| Fujitsu Siemens         | 2         | 0.19%   |
| Biostar                 | 2         | 0.19%   |
| Aquarius                | 2         | 0.19%   |
| ZOTAC                   | 1         | 0.1%    |
| YJKC                    | 1         | 0.1%    |
| UNOWHY                  | 1         | 0.1%    |
| TUXEDO                  | 1         | 0.1%    |
| SimpliVity              | 1         | 0.1%    |
| Shuttle                 | 1         | 0.1%    |
| RuggedPC                | 1         | 0.1%    |
| Quanta                  | 1         | 0.1%    |
| QIYIDA                  | 1         | 0.1%    |
| Protectli               | 1         | 0.1%    |
| Positivo                | 1         | 0.1%    |
| PC Specialist           | 1         | 0.1%    |
| Panasonic               | 1         | 0.1%    |
| NC9VL                   | 1         | 0.1%    |
| Monster                 | 1         | 0.1%    |
| Microsoft               | 1         | 0.1%    |
| Micro Electronics       | 1         | 0.1%    |
| Medion                  | 1         | 0.1%    |
| LG Electronics          | 1         | 0.1%    |
| Itautec                 | 1         | 0.1%    |
| IBM                     | 1         | 0.1%    |
| HPE                     | 1         | 0.1%    |
| Compulab                | 1         | 0.1%    |
| Chuwi                   | 1         | 0.1%    |
| Casper                  | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Apple MacBookAir7,1                      | 74        | 7.03%   |
| Apple MacBookAir7,2                      | 66        | 6.27%   |
| Google Enguarde                          | 47        | 4.47%   |
| ASUS All Series                          | 27        | 2.57%   |
| ASRock H470M-HVS                         | 20        | 1.9%    |
| Acer Aspire A315-23                      | 15        | 1.43%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US    | 14        | 1.33%   |
| Unknown                                  | 7         | 0.67%   |
| Gigabyte H81M-S2V                        | 6         | 0.57%   |
| ASRock H61M-VG4                          | 6         | 0.57%   |
| Gigabyte H61M-DS2 REV 1.2                | 4         | 0.38%   |
| Dell XPS 13 9310                         | 4         | 0.38%   |
| Dell Latitude 7480                       | 4         | 0.38%   |
| ASUS P8H61-M LX3 R2.0                    | 4         | 0.38%   |
| MSI MS-7996                              | 3         | 0.29%   |
| Lenovo ThinkPad E475 20H40006US          | 3         | 0.29%   |
| Intel Pro, Std, Elt Series               | 3         | 0.29%   |
| HP EliteBook 8460p                       | 3         | 0.29%   |
| Hardkernel Odroid XU4                    | 3         | 0.29%   |
| Gigabyte Z77-D3H                         | 3         | 0.29%   |
| Gigabyte B550I AORUS PRO AX              | 3         | 0.29%   |
| Gigabyte A320M-S2H                       | 3         | 0.29%   |
| Fujitsu ESPRIMO P720                     | 3         | 0.29%   |
| ASUS PRIME A320M-K                       | 3         | 0.29%   |
| ASRock B450M Pro4                        | 3         | 0.29%   |
| Apple iMac11,2                           | 3         | 0.29%   |
| Semp Toshiba STI                         | 2         | 0.19%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 2         | 0.19%   |
| MSI MS-7A71                              | 2         | 0.19%   |
| MSI MS-7A70                              | 2         | 0.19%   |
| MSI MS-7721                              | 2         | 0.19%   |
| Lenovo ThinkPad T490 20N2CTO1WW          | 2         | 0.19%   |
| Lenovo ThinkBook 14 G2 ARE 20VF          | 2         | 0.19%   |
| Lenovo IdeaPad L340-15API 81LW           | 2         | 0.19%   |
| Lenovo IdeaPad 700-15ISK 80RU            | 2         | 0.19%   |
| Lenovo G50-80 80E5                       | 2         | 0.19%   |
| Intel DN2820FYK H24582-201               | 2         | 0.19%   |
| HUAWEI NBLK-WAX9X                        | 2         | 0.19%   |
| HP Z620 Workstation                      | 2         | 0.19%   |
| HP Pavilion Gaming Laptop 15-ec2xxx      | 2         | 0.19%   |
| HP Laptop 15s-fq2xxx                     | 2         | 0.19%   |
| HP Laptop 15s-eq1xxx                     | 2         | 0.19%   |
| HP Compaq nx6125 (PZ849UA#ABA)           | 2         | 0.19%   |
| HP Compaq nx6110 (PZ065UA#ABA)           | 2         | 0.19%   |
| Gigabyte Z370 AORUS Gaming 5             | 2         | 0.19%   |
| Gigabyte X570 I AORUS PRO WIFI           | 2         | 0.19%   |
| Gigabyte B360M H                         | 2         | 0.19%   |
| Gigabyte 970A-DS3P                       | 2         | 0.19%   |
| ECS H61H2-M13                            | 2         | 0.19%   |
| ECS G31T-M9                              | 2         | 0.19%   |
| Dell XPS 13 9370                         | 2         | 0.19%   |
| Dell XPS 13 7390                         | 2         | 0.19%   |
| Dell Vostro 5490                         | 2         | 0.19%   |
| Dell Precision 3540                      | 2         | 0.19%   |
| Dell OptiPlex 760                        | 2         | 0.19%   |
| Dell OptiPlex 7010                       | 2         | 0.19%   |
| Dell OptiPlex 3020                       | 2         | 0.19%   |
| Dell Latitude E7470                      | 2         | 0.19%   |
| Dell Latitude E6330                      | 2         | 0.19%   |
| Dell Latitude 7410                       | 2         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Apple MacBookAir7        | 140       | 13.31%  |
| Lenovo ThinkPad          | 115       | 10.93%  |
| Google Enguarde          | 47        | 4.47%   |
| Acer Aspire              | 34        | 3.23%   |
| Dell Inspiron            | 27        | 2.57%   |
| ASUS All                 | 27        | 2.57%   |
| Lenovo IdeaPad           | 23        | 2.19%   |
| ASUS PRIME               | 22        | 2.09%   |
| ASRock H470M-HVS         | 20        | 1.9%    |
| Dell Latitude            | 16        | 1.52%   |
| ASUS ROG                 | 16        | 1.52%   |
| HP ProBook               | 14        | 1.33%   |
| HP Compaq                | 14        | 1.33%   |
| Dell XPS                 | 14        | 1.33%   |
| HP EliteBook             | 13        | 1.24%   |
| Dell OptiPlex            | 13        | 1.24%   |
| Dell Precision           | 11        | 1.05%   |
| HP Pavilion              | 10        | 0.95%   |
| HP Laptop                | 10        | 0.95%   |
| Unknown                  | 7         | 0.67%   |
| Gigabyte H81M-S2V        | 6         | 0.57%   |
| ASUS ZenBook             | 6         | 0.57%   |
| ASRock H61M-VG4          | 6         | 0.57%   |
| Lenovo Yoga              | 5         | 0.48%   |
| Lenovo ThinkCentre       | 5         | 0.48%   |
| ASUS VivoBook            | 5         | 0.48%   |
| ASUS TUF                 | 5         | 0.48%   |
| Toshiba Satellite        | 4         | 0.38%   |
| Gigabyte H61M-DS2        | 4         | 0.38%   |
| Gigabyte A320M-S2H       | 4         | 0.38%   |
| Fujitsu ESPRIMO          | 4         | 0.38%   |
| Dell Vostro              | 4         | 0.38%   |
| ASUS P8H61-M             | 4         | 0.38%   |
| ASRock B450M             | 4         | 0.38%   |
| Apple iMac11             | 4         | 0.38%   |
| Pine Microsystems Pine64 | 3         | 0.29%   |
| MSI MS-7996              | 3         | 0.29%   |
| Lenovo ThinkBook         | 3         | 0.29%   |
| Intel Pro                | 3         | 0.29%   |
| HP ProLiant              | 3         | 0.29%   |
| HP ENVY                  | 3         | 0.29%   |
| HP 250                   | 3         | 0.29%   |
| Hardkernel Odroid        | 3         | 0.29%   |
| Gigabyte Z77-D3H         | 3         | 0.29%   |
| Gigabyte B550I           | 3         | 0.29%   |
| Fujitsu LIFEBOOK         | 3         | 0.29%   |
| ASRock Z97               | 3         | 0.29%   |
| Acer Swift               | 3         | 0.29%   |
| Semp Toshiba STI         | 2         | 0.19%   |
| RPi Raspberry            | 2         | 0.19%   |
| MSI MS-7A71              | 2         | 0.19%   |
| MSI MS-7A70              | 2         | 0.19%   |
| MSI MS-7721              | 2         | 0.19%   |
| Lenovo G50-80            | 2         | 0.19%   |
| Intel DN2820FYK          | 2         | 0.19%   |
| HUAWEI NBLK-WAX9X        | 2         | 0.19%   |
| HP ZBook                 | 2         | 0.19%   |
| HP Z620                  | 2         | 0.19%   |
| HP Presario              | 2         | 0.19%   |
| HP OMEN                  | 2         | 0.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 241       | 22.91%  |
| 2021    | 190       | 18.06%  |
| 2019    | 155       | 14.73%  |
| 2018    | 77        | 7.32%   |
| 2014    | 54        | 5.13%   |
| 2015    | 43        | 4.09%   |
| 2013    | 42        | 3.99%   |
| 2012    | 39        | 3.71%   |
| 2016    | 35        | 3.33%   |
| 2011    | 35        | 3.33%   |
| 2009    | 31        | 2.95%   |
| 2010    | 27        | 2.57%   |
| 2008    | 25        | 2.38%   |
| 2017    | 23        | 2.19%   |
| Unknown | 14        | 1.33%   |
| 2007    | 8         | 0.76%   |
| 2006    | 5         | 0.48%   |
| 2005    | 4         | 0.38%   |
| 2004    | 3         | 0.29%   |
| 2001    | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 614       | 58.37%  |
| Desktop        | 374       | 35.55%  |
| Convertible    | 16        | 1.52%   |
| Mini pc        | 13        | 1.24%   |
| System on chip | 11        | 1.05%   |
| Server         | 9         | 0.86%   |
| All in one     | 8         | 0.76%   |
| Tablet         | 4         | 0.38%   |
| Phone          | 3         | 0.29%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 997       | 94.59%  |
| Enabled  | 57        | 5.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1002      | 95.25%  |
| Yes  | 50        | 4.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 259       | 24.57%  |
| 3.01-4.0        | 244       | 23.15%  |
| 16.01-24.0      | 194       | 18.41%  |
| 8.01-16.0       | 142       | 13.47%  |
| 32.01-64.0      | 93        | 8.82%   |
| 1.01-2.0        | 45        | 4.27%   |
| 64.01-256.0     | 33        | 3.13%   |
| 2.01-3.0        | 19        | 1.8%    |
| 0.51-1.0        | 9         | 0.85%   |
| 24.01-32.0      | 7         | 0.66%   |
| 0.01-0.5        | 5         | 0.47%   |
| More than 256.0 | 4         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 373       | 34.7%   |
| 0.51-1.0    | 223       | 20.74%  |
| 2.01-3.0    | 162       | 15.07%  |
| 4.01-8.0    | 120       | 11.16%  |
| 3.01-4.0    | 90        | 8.37%   |
| 8.01-16.0   | 46        | 4.28%   |
| 0.01-0.5    | 38        | 3.53%   |
| 16.01-24.0  | 12        | 1.12%   |
| 32.01-64.0  | 4         | 0.37%   |
| 24.01-32.0  | 4         | 0.37%   |
| 64.01-256.0 | 3         | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 704       | 66.73%  |
| 2      | 226       | 21.42%  |
| 3      | 54        | 5.12%   |
| 4      | 29        | 2.75%   |
| 5      | 16        | 1.52%   |
| 8      | 7         | 0.66%   |
| 6      | 5         | 0.47%   |
| 0      | 4         | 0.38%   |
| 10     | 3         | 0.28%   |
| 9      | 3         | 0.28%   |
| 28     | 1         | 0.09%   |
| 13     | 1         | 0.09%   |
| 12     | 1         | 0.09%   |
| 7      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 784       | 74.52%  |
| Yes       | 268       | 25.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 777       | 73.86%  |
| No        | 275       | 26.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 737       | 70.06%  |
| No        | 315       | 29.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 646       | 61.35%  |
| No        | 407       | 38.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country       | Computers | Percent |
|---------------|-----------|---------|
| USA           | 361       | 34.22%  |
| Russia        | 204       | 19.34%  |
| Germany       | 54        | 5.12%   |
| France        | 52        | 4.93%   |
| UK            | 33        | 3.13%   |
| Spain         | 33        | 3.13%   |
| Poland        | 27        | 2.56%   |
| Ukraine       | 24        | 2.27%   |
| Brazil        | 24        | 2.27%   |
| Netherlands   | 13        | 1.23%   |
| Canada        | 12        | 1.14%   |
| Switzerland   | 11        | 1.04%   |
| Australia     | 11        | 1.04%   |
| Sweden        | 10        | 0.95%   |
| Mexico        | 10        | 0.95%   |
| Italy         | 10        | 0.95%   |
| Turkey        | 9         | 0.85%   |
| Portugal      | 9         | 0.85%   |
| India         | 9         | 0.85%   |
| Norway        | 8         | 0.76%   |
| Czechia       | 8         | 0.76%   |
| Belgium       | 8         | 0.76%   |
| Austria       | 8         | 0.76%   |
| Argentina     | 7         | 0.66%   |
| Greece        | 6         | 0.57%   |
| China         | 6         | 0.57%   |
| Bulgaria      | 6         | 0.57%   |
| Japan         | 5         | 0.47%   |
| Hungary       | 5         | 0.47%   |
| Finland       | 5         | 0.47%   |
| Venezuela     | 4         | 0.38%   |
| Thailand      | 4         | 0.38%   |
| Kazakhstan    | 4         | 0.38%   |
| Ecuador       | 4         | 0.38%   |
| Belarus       | 4         | 0.38%   |
| Singapore     | 3         | 0.28%   |
| Romania       | 3         | 0.28%   |
| Croatia       | 3         | 0.28%   |
| South Africa  | 2         | 0.19%   |
| Slovenia      | 2         | 0.19%   |
| Philippines   | 2         | 0.19%   |
| New Zealand   | 2         | 0.19%   |
| Ireland       | 2         | 0.19%   |
| Indonesia     | 2         | 0.19%   |
| Denmark       | 2         | 0.19%   |
| Colombia      | 2         | 0.19%   |
| Vietnam       | 1         | 0.09%   |
| Uruguay       | 1         | 0.09%   |
| Syria         | 1         | 0.09%   |
| South Sudan   | 1         | 0.09%   |
| Slovakia      | 1         | 0.09%   |
| Serbia        | 1         | 0.09%   |
| New Caledonia | 1         | 0.09%   |
| Morocco       | 1         | 0.09%   |
| Mongolia      | 1         | 0.09%   |
| Moldova       | 1         | 0.09%   |
| Malaysia      | 1         | 0.09%   |
| Madagascar    | 1         | 0.09%   |
| Lebanon       | 1         | 0.09%   |
| Iceland       | 1         | 0.09%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Portland       | 234       | 21.97%  |
| Voronezh       | 155       | 14.55%  |
| St Petersburg  | 15        | 1.41%   |
| Paris          | 11        | 1.03%   |
| London         | 10        | 0.94%   |
| Frankfort      | 10        | 0.94%   |
| Lyon           | 9         | 0.85%   |
| Hampden        | 9         | 0.85%   |
| Vienna         | 8         | 0.75%   |
| Kyiv           | 8         | 0.75%   |
| Warsaw         | 6         | 0.56%   |
| Ocala          | 6         | 0.56%   |
| Berlin         | 6         | 0.56%   |
| Valencia       | 5         | 0.47%   |
| Sofia          | 5         | 0.47%   |
| Moscow         | 5         | 0.47%   |
| Madrid         | 5         | 0.47%   |
| Kalamazoo      | 5         | 0.47%   |
| Athens         | 5         | 0.47%   |
| Amsterdam      | 5         | 0.47%   |
| Sydney         | 4         | 0.38%   |
| Stockholm      | 4         | 0.38%   |
| Sevastopol     | 4         | 0.38%   |
| S??o Paulo     | 4         | 0.38%   |
| Perm           | 4         | 0.38%   |
| Mesa           | 4         | 0.38%   |
| Ensenada       | 4         | 0.38%   |
| Bengaluru      | 4         | 0.38%   |
| Bangkok        | 4         | 0.38%   |
| Zurich         | 3         | 0.28%   |
| Vladivostok    | 3         | 0.28%   |
| Sunnyvale      | 3         | 0.28%   |
| San Jose       | 3         | 0.28%   |
| Rio de Janeiro | 3         | 0.28%   |
| Istanbul       | 3         | 0.28%   |
| Halstead       | 3         | 0.28%   |
| Gloucester     | 3         | 0.28%   |
| Clitheroe      | 3         | 0.28%   |
| Barcelona      | 3         | 0.28%   |
| Ankara         | 3         | 0.28%   |
| Zagreb         | 2         | 0.19%   |
| Yevpatoriya    | 2         | 0.19%   |
| Wroclaw        | 2         | 0.19%   |
| Waregem        | 2         | 0.19%   |
| Valladolid     | 2         | 0.19%   |
| Tyreso Strand  | 2         | 0.19%   |
| Toronto        | 2         | 0.19%   |
| Thermopolis    | 2         | 0.19%   |
| Springfield    | 2         | 0.19%   |
| Singapore      | 2         | 0.19%   |
| Shizuoka       | 2         | 0.19%   |
| Sevastopol'    | 2         | 0.19%   |
| Saratov        | 2         | 0.19%   |
| Saint-Denis    | 2         | 0.19%   |
| Roseville      | 2         | 0.19%   |
| Riegelwood     | 2         | 0.19%   |
| Rennes         | 2         | 0.19%   |
| Prague         | 2         | 0.19%   |
| Plano          | 2         | 0.19%   |
| Oleksandrivka  | 2         | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 225       | 293    | 15.65%  |
| Seagate                   | 187       | 268    | 13%     |
| WDC                       | 182       | 281    | 12.66%  |
| Apple                     | 145       | 146    | 10.08%  |
| Unknown                   | 95        | 114    | 6.61%   |
| Toshiba                   | 92        | 119    | 6.4%    |
| Kingston                  | 74        | 88     | 5.15%   |
| Crucial                   | 62        | 70     | 4.31%   |
| SanDisk                   | 44        | 50     | 3.06%   |
| Intel                     | 36        | 45     | 2.5%    |
| Hitachi                   | 36        | 37     | 2.5%    |
| SK Hynix                  | 21        | 29     | 1.46%   |
| Netac                     | 20        | 22     | 1.39%   |
| SABRENT                   | 19        | 19     | 1.32%   |
| A-DATA Technology         | 19        | 24     | 1.32%   |
| HGST                      | 18        | 23     | 1.25%   |
| Micron Technology         | 14        | 14     | 0.97%   |
| China                     | 13        | 13     | 0.9%    |
| Transcend                 | 8         | 9      | 0.56%   |
| PNY                       | 8         | 8      | 0.56%   |
| LITEON                    | 7         | 7      | 0.49%   |
| Fujitsu                   | 7         | 7      | 0.49%   |
| SPCC                      | 6         | 6      | 0.42%   |
| MAXTOR                    | 6         | 8      | 0.42%   |
| JMicron                   | 6         | 6      | 0.42%   |
| KIOXIA                    | 5         | 6      | 0.35%   |
| Intenso                   | 5         | 6      | 0.35%   |
| Union Memory              | 4         | 4      | 0.28%   |
| Phison                    | 4         | 7      | 0.28%   |
| Patriot                   | 4         | 4      | 0.28%   |
| Corsair                   | 4         | 4      | 0.28%   |
| Team                      | 3         | 3      | 0.21%   |
| Silicon Motion            | 3         | 4      | 0.21%   |
| Phison Electronics        | 3         | 3      | 0.21%   |
| OCZ                       | 3         | 3      | 0.21%   |
| LITEONIT                  | 3         | 3      | 0.21%   |
| Lexar                     | 3         | 4      | 0.21%   |
| Lenovo                    | 3         | 3      | 0.21%   |
| Gigabyte Technology       | 3         | 3      | 0.21%   |
| ZTC                       | 2         | 4      | 0.14%   |
| XPG                       | 2         | 2      | 0.14%   |
| PLEXTOR                   | 2         | 4      | 0.14%   |
| Mass                      | 2         | 2      | 0.14%   |
| Hewlett-Packard           | 2         | 3      | 0.14%   |
| GOODRAM                   | 2         | 2      | 0.14%   |
| Apacer                    | 2         | 2      | 0.14%   |
| Xinhaike                  | 1         | 1      | 0.07%   |
| TrueNAS                   | 1         | 1      | 0.07%   |
| T-FORCE                   | 1         | 1      | 0.07%   |
| SILICONMOTION             | 1         | 1      | 0.07%   |
| PNY USB                   | 1         | 1      | 0.07%   |
| Pioneer                   | 1         | 1      | 0.07%   |
| NAS                       | 1         | 5      | 0.07%   |
| MyDigitalSSD              | 1         | 1      | 0.07%   |
| Mushkin                   | 1         | 1      | 0.07%   |
| Micron/Crucial Technology | 1         | 1      | 0.07%   |
| Maximus                   | 1         | 1      | 0.07%   |
| MaxDigital                | 1         | 2      | 0.07%   |
| LDLC                      | 1         | 1      | 0.07%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.07%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Apple SSD AP0128H 121GB              | 74        | 4.7%    |
| Apple SSD SM0128G 121GB              | 65        | 4.13%   |
| Unknown AGND3R  16GB                 | 25        | 1.59%   |
| Toshiba HDWD110 1TB                  | 23        | 1.46%   |
| Seagate ST1000LM035-1RK172 1TB       | 20        | 1.27%   |
| Netac SSD 240GB                      | 20        | 1.27%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 19        | 1.21%   |
| Unknown HAG2e  16GB                  | 19        | 1.21%   |
| SABRENT Disk 1TB                     | 19        | 1.21%   |
| Samsung SSD 970 EVO Plus 1TB         | 15        | 0.95%   |
| Seagate ST500DM002-1BD142 500GB      | 14        | 0.89%   |
| Kingston SA400S37240G 240GB SSD      | 14        | 0.89%   |
| Samsung SSD 860 EVO 250GB            | 13        | 0.83%   |
| Samsung SSD 860 EVO 1TB              | 13        | 0.83%   |
| Kingston SA400S37120G 120GB SSD      | 13        | 0.83%   |
| Kingston SV300S37A120G 120GB SSD     | 12        | 0.76%   |
| Samsung SSD 970 EVO Plus 500GB       | 11        | 0.7%    |
| Samsung SSD 870 EVO 500GB            | 11        | 0.7%    |
| Samsung SSD 850 EVO 500GB            | 10        | 0.64%   |
| Samsung SSD 850 EVO 250GB            | 10        | 0.64%   |
| Crucial CT500MX500SSD1 500GB         | 10        | 0.64%   |
| Toshiba MQ04ABF100 1TB               | 9         | 0.57%   |
| Samsung SSD 860 EVO 500GB            | 9         | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB       | 8         | 0.51%   |
| Seagate ST1000DM003-1ER162 1TB       | 8         | 0.51%   |
| SanDisk SD8SN8U128G1001 128GB SSD    | 8         | 0.51%   |
| Samsung MZNTY128HDHP-000L1 128GB SSD | 7         | 0.45%   |
| Crucial CT250MX500SSD1 250GB         | 7         | 0.45%   |
| Crucial CT240BX500SSD1 240GB         | 7         | 0.45%   |
| Unknown MMC Card  32GB               | 6         | 0.38%   |
| Toshiba DT01ACA100 1TB               | 6         | 0.38%   |
| Toshiba DT01ACA050 500GB             | 6         | 0.38%   |
| Seagate ST4000DM004-2CV104 4TB       | 6         | 0.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 6         | 0.38%   |
| SanDisk SD8SBAT128G1122 128GB SSD    | 6         | 0.38%   |
| Samsung SSD 970 EVO 500GB            | 6         | 0.38%   |
| Hitachi HDS721050CLA362 500GB        | 6         | 0.38%   |
| HGST HTS721010A9E630 1TB             | 6         | 0.38%   |
| Crucial CT1000MX500SSD1 1TB          | 6         | 0.38%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 5         | 0.32%   |
| Seagate ST2000DM001-1ER164 2TB       | 5         | 0.32%   |
| Samsung SSD 980 PRO 1TB              | 5         | 0.32%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 4         | 0.25%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 0.25%   |
| Unknown MMC Card  64GB               | 4         | 0.25%   |
| Toshiba DT01ACA300 3TB               | 4         | 0.25%   |
| Toshiba DT01ACA200 2TB               | 4         | 0.25%   |
| Seagate ST2000DM008-2FR102 2TB       | 4         | 0.25%   |
| Seagate Backup+ Hub BK 10TB          | 4         | 0.25%   |
| SanDisk SSD PLUS 240GB               | 4         | 0.25%   |
| Samsung SSD 960 EVO 250GB            | 4         | 0.25%   |
| Samsung SSD 850 PRO 1TB              | 4         | 0.25%   |
| Samsung SSD 840 EVO 250GB            | 4         | 0.25%   |
| Samsung NVMe SSD Drive 1TB           | 4         | 0.25%   |
| Kingston SV300S37A240G 240GB SSD     | 4         | 0.25%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.25%   |
| Crucial CT500P1SSD8 500GB            | 4         | 0.25%   |
| Crucial CT480BX500SSD1 480GB         | 4         | 0.25%   |
| Crucial CT1000P1SSD8 1TB             | 4         | 0.25%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 3         | 0.19%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 179       | 248    | 37.68%  |
| WDC                 | 137       | 219    | 28.84%  |
| Toshiba             | 73        | 97     | 15.37%  |
| Hitachi             | 36        | 37     | 7.58%   |
| HGST                | 18        | 23     | 3.79%   |
| Samsung Electronics | 14        | 16     | 2.95%   |
| Fujitsu             | 7         | 7      | 1.47%   |
| MAXTOR              | 5         | 5      | 1.05%   |
| SILICONMOTION       | 1         | 1      | 0.21%   |
| NAS                 | 1         | 5      | 0.21%   |
| MaxDigital          | 1         | 2      | 0.21%   |
| IBM-ESXS            | 1         | 2      | 0.21%   |
| Apple               | 1         | 1      | 0.21%   |
| 128MB               | 1         | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 132       | 167    | 24.31%  |
| Apple               | 69        | 69     | 12.71%  |
| Kingston            | 65        | 78     | 11.97%  |
| Crucial             | 50        | 55     | 9.21%   |
| SanDisk             | 34        | 39     | 6.26%   |
| Netac               | 20        | 22     | 3.68%   |
| SABRENT             | 19        | 19     | 3.5%    |
| WDC                 | 17        | 20     | 3.13%   |
| Intel               | 12        | 13     | 2.21%   |
| China               | 12        | 12     | 2.21%   |
| A-DATA Technology   | 12        | 14     | 2.21%   |
| Transcend           | 8         | 9      | 1.47%   |
| SK Hynix            | 7         | 7      | 1.29%   |
| Toshiba             | 6         | 8      | 1.1%    |
| PNY                 | 6         | 6      | 1.1%    |
| SPCC                | 5         | 5      | 0.92%   |
| Micron Technology   | 5         | 5      | 0.92%   |
| LITEON              | 5         | 5      | 0.92%   |
| JMicron             | 5         | 5      | 0.92%   |
| Seagate             | 4         | 4      | 0.74%   |
| Patriot             | 4         | 4      | 0.74%   |
| Intenso             | 4         | 4      | 0.74%   |
| Unknown             | 3         | 3      | 0.55%   |
| Team                | 3         | 3      | 0.55%   |
| OCZ                 | 3         | 3      | 0.55%   |
| LITEONIT            | 3         | 3      | 0.55%   |
| Lexar               | 3         | 4      | 0.55%   |
| ZTC                 | 2         | 4      | 0.37%   |
| PLEXTOR             | 2         | 4      | 0.37%   |
| GOODRAM             | 2         | 2      | 0.37%   |
| Apacer              | 2         | 2      | 0.37%   |
| Xinhaike            | 1         | 1      | 0.18%   |
| Union Memory        | 1         | 1      | 0.18%   |
| TrueNAS             | 1         | 1      | 0.18%   |
| T-FORCE             | 1         | 1      | 0.18%   |
| PNY USB             | 1         | 1      | 0.18%   |
| Pioneer             | 1         | 1      | 0.18%   |
| MyDigitalSSD        | 1         | 1      | 0.18%   |
| Mushkin             | 1         | 1      | 0.18%   |
| Maxtor              | 1         | 3      | 0.18%   |
| Maximus             | 1         | 1      | 0.18%   |
| LDLC                | 1         | 1      | 0.18%   |
| KingDian            | 1         | 1      | 0.18%   |
| Hikvision           | 1         | 1      | 0.18%   |
| Gigabyte Technology | 1         | 1      | 0.18%   |
| FORESEE             | 1         | 1      | 0.18%   |
| DOGFISH             | 1         | 1      | 0.18%   |
| ASUS-PHISON         | 1         | 1      | 0.18%   |
| AMD                 | 1         | 2      | 0.18%   |
| 2-Power             | 1         | 1      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 502       | 620    | 37.27%  |
| HDD     | 415       | 664    | 30.81%  |
| NVMe    | 324       | 393    | 24.05%  |
| MMC     | 90        | 111    | 6.68%   |
| Unknown | 16        | 26     | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 739       | 1229   | 61.12%  |
| NVMe | 324       | 393    | 26.8%   |
| MMC  | 90        | 111    | 7.44%   |
| SAS  | 56        | 81     | 4.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 573       | 752    | 60.13%  |
| 0.51-1.0   | 256       | 308    | 26.86%  |
| 1.01-2.0   | 59        | 80     | 6.19%   |
| 3.01-4.0   | 28        | 60     | 2.94%   |
| 4.01-10.0  | 18        | 40     | 1.89%   |
| 2.01-3.0   | 14        | 21     | 1.47%   |
| 10.01-20.0 | 5         | 23     | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 331       | 31.26%  |
| Unknown        | 187       | 17.66%  |
| 251-500        | 142       | 13.41%  |
| 1-20           | 103       | 9.73%   |
| 501-1000       | 93        | 8.78%   |
| 1001-2000      | 64        | 6.04%   |
| More than 3000 | 54        | 5.1%    |
| 51-100         | 42        | 3.97%   |
| 21-50          | 26        | 2.46%   |
| 2001-3000      | 17        | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 429       | 40.21%  |
| Unknown        | 187       | 17.53%  |
| 101-250        | 109       | 10.22%  |
| 21-50          | 87        | 8.15%   |
| 51-100         | 77        | 7.22%   |
| 251-500        | 61        | 5.72%   |
| 501-1000       | 51        | 4.78%   |
| 1001-2000      | 29        | 2.72%   |
| More than 3000 | 22        | 2.06%   |
| 2001-3000      | 9         | 0.84%   |
| 0              | 6         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB          | 12        | 12     | 8.89%   |
| Seagate ST500DM002-1BD142 500GB       | 3         | 3      | 2.22%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 3      | 2.22%   |
| WDC WD20EARS-00MVWB0 2TB              | 2         | 2      | 1.48%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 2      | 1.48%   |
| Seagate ST3160813AS 160GB             | 2         | 2      | 1.48%   |
| Intel SSDPEKKW128G7 128GB             | 2         | 3      | 1.48%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 1         | 1      | 0.74%   |
| WDC WD7500BPVT-80HXZT3 752GB          | 1         | 1      | 0.74%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1         | 1      | 0.74%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1         | 2      | 0.74%   |
| WDC WD5002AALX-00J37A0 500GB          | 1         | 1      | 0.74%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1         | 1      | 0.74%   |
| WDC WD5000AAKX-00U6AA0 500GB          | 1         | 1      | 0.74%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1         | 1      | 0.74%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1         | 1      | 0.74%   |
| WDC WD5000AAJS-22A8B0 500GB           | 1         | 1      | 0.74%   |
| WDC WD40EFZX-68AWUN0 4TB              | 1         | 6      | 0.74%   |
| WDC WD400BB-00DEA0 40GB               | 1         | 1      | 0.74%   |
| WDC WD3200AAJS-08L7A0 320GB           | 1         | 1      | 0.74%   |
| WDC WD3200AAJS-00L7A0 320GB           | 1         | 1      | 0.74%   |
| WDC WD30EZRX-00AZ6B0 3TB              | 1         | 1      | 0.74%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 2      | 0.74%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 0.74%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1         | 1      | 0.74%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 0.74%   |
| WDC WD10JPVT-75A1YT0 1TB              | 1         | 1      | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 0.74%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1         | 1      | 0.74%   |
| WDC WD1001FALS-75J7B0 1TB             | 1         | 1      | 0.74%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 0.74%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 0.74%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 0.74%   |
| Toshiba MK2565GSX 250GB               | 1         | 1      | 0.74%   |
| Toshiba DT01ACA050 500GB              | 1         | 1      | 0.74%   |
| SK Hynix PC401 NVMe 512GB             | 1         | 6      | 0.74%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 0.74%   |
| Seagate ST960822A 64GB                | 1         | 1      | 0.74%   |
| Seagate ST9500325AS 500GB             | 1         | 2      | 0.74%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 0.74%   |
| Seagate ST9160310AS 160GB             | 1         | 1      | 0.74%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 0.74%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 0.74%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 1      | 0.74%   |
| Seagate ST380215A 80GB                | 1         | 1      | 0.74%   |
| Seagate ST340014A 40GB                | 1         | 1      | 0.74%   |
| Seagate ST3320620A 320GB              | 1         | 1      | 0.74%   |
| Seagate ST3320613AS 320GB             | 1         | 1      | 0.74%   |
| Seagate ST3250310AS 250GB             | 1         | 1      | 0.74%   |
| Seagate ST3200827AS 200GB             | 1         | 2      | 0.74%   |
| Seagate ST32000542AS 2TB              | 1         | 1      | 0.74%   |
| Seagate ST31500341AS 1TB              | 1         | 1      | 0.74%   |
| Seagate ST3120827AS 120GB             | 1         | 2      | 0.74%   |
| Seagate ST3120811AS 120GB             | 1         | 1      | 0.74%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 0.74%   |
| Seagate ST31000333AS 1TB              | 1         | 1      | 0.74%   |
| Seagate ST3000DM001-9YN166 3TB        | 1         | 1      | 0.74%   |
| Seagate ST250DM000-1BD141 250GB       | 1         | 1      | 0.74%   |
| Seagate ST2000LX001-1RG174 2TB        | 1         | 1      | 0.74%   |
| Seagate ST2000DM001-9YN164 2TB        | 1         | 1      | 0.74%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 46     | 29.32%  |
| Seagate             | 33        | 38     | 24.81%  |
| Hitachi             | 14        | 14     | 10.53%  |
| Samsung Electronics | 9         | 10     | 6.77%   |
| Intel               | 8         | 11     | 6.02%   |
| Toshiba             | 5         | 5      | 3.76%   |
| Kingston            | 5         | 5      | 3.76%   |
| A-DATA Technology   | 5         | 6      | 3.76%   |
| SK Hynix            | 2         | 7      | 1.5%    |
| SanDisk             | 2         | 2      | 1.5%    |
| Maxtor              | 2         | 2      | 1.5%    |
| PNY                 | 1         | 1      | 0.75%   |
| Micron Technology   | 1         | 1      | 0.75%   |
| LITEONIT            | 1         | 1      | 0.75%   |
| LITEON              | 1         | 1      | 0.75%   |
| KingDian            | 1         | 1      | 0.75%   |
| JMicron             | 1         | 1      | 0.75%   |
| HGST                | 1         | 1      | 0.75%   |
| Crucial             | 1         | 1      | 0.75%   |
| China               | 1         | 1      | 0.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 46     | 39.39%  |
| Seagate             | 33        | 38     | 33.33%  |
| Hitachi             | 14        | 14     | 14.14%  |
| Toshiba             | 5         | 5      | 5.05%   |
| Samsung Electronics | 5         | 5      | 5.05%   |
| Maxtor              | 2         | 2      | 2.02%   |
| HGST                | 1         | 1      | 1.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 94        | 111    | 73.44%  |
| SSD  | 28        | 31     | 21.88%  |
| NVMe | 6         | 13     | 4.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST500DM005 HD502HJ 500GB | 1         | 1      | 50%     |
| Seagate ST3500830AS 500GB        | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 816       | 1283   | 70.34%  |
| Detected | 219       | 374    | 18.88%  |
| Malfunc  | 123       | 155    | 10.6%   |
| Failed   | 2         | 2      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 583       | 48.34%  |
| Samsung Electronics           | 166       | 13.76%  |
| AMD                           | 165       | 13.68%  |
| Apple                         | 74        | 6.14%   |
| Sandisk                       | 42        | 3.48%   |
| Marvell Technology Group      | 20        | 1.66%   |
| Phison Electronics            | 15        | 1.24%   |
| JMicron Technology            | 15        | 1.24%   |
| SK Hynix                      | 14        | 1.16%   |
| Micron/Crucial Technology     | 14        | 1.16%   |
| ASMedia Technology            | 13        | 1.08%   |
| Toshiba America Info Systems  | 10        | 0.83%   |
| Kingston Technology Company   | 10        | 0.83%   |
| Nvidia                        | 9         | 0.75%   |
| Micron Technology             | 9         | 0.75%   |
| ADATA Technology              | 9         | 0.75%   |
| KIOXIA                        | 8         | 0.66%   |
| Silicon Motion                | 5         | 0.41%   |
| Broadcom / LSI                | 5         | 0.41%   |
| VIA Technologies              | 4         | 0.33%   |
| Union Memory (Shenzhen)       | 3         | 0.25%   |
| Lenovo                        | 3         | 0.25%   |
| LSI Logic / Symbios Logic     | 2         | 0.17%   |
| Lite-On Technology            | 2         | 0.17%   |
| Silicon Image                 | 1         | 0.08%   |
| Seagate Technology            | 1         | 0.08%   |
| OCZ Technology Group          | 1         | 0.08%   |
| Integrated Technology Express | 1         | 0.08%   |
| Hewlett-Packard               | 1         | 0.08%   |
| Adaptec                       | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 124       | 9.01%   |
| Apple S1X NVMe Controller                                                               | 74        | 5.38%   |
| Samsung Electronics SATA controller                                                     | 67        | 4.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 61        | 4.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 60        | 4.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 59        | 4.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 42        | 3.05%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 37        | 2.69%   |
| AMD 400 Series Chipset SATA Controller                                                  | 26        | 1.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 22        | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 22        | 1.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 21        | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 20        | 1.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 17        | 1.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 17        | 1.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 17        | 1.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 17        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 17        | 1.24%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 16        | 1.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15        | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 15        | 1.09%   |
| Samsung NVMe Controller                                                                 | 14        | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13        | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13        | 0.94%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 12        | 0.87%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 12        | 0.87%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11        | 0.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10        | 0.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 10        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 10        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 10        | 0.73%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 10        | 0.73%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 9         | 0.65%   |
| Phison E12 NVMe Controller                                                              | 9         | 0.65%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 9         | 0.65%   |
| Micron Non-Volatile memory controller                                                   | 9         | 0.65%   |
| Intel SSD 600P Series                                                                   | 9         | 0.65%   |
| Intel SATA Controller [RAID mode]                                                       | 9         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 8         | 0.58%   |
| KIOXIA Non-Volatile memory controller                                                   | 8         | 0.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 8         | 0.58%   |
| AMD FCH SATA Controller D                                                               | 8         | 0.58%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 7         | 0.51%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 7         | 0.51%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7         | 0.51%   |
| Intel SSD 660P Series                                                                   | 7         | 0.51%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 7         | 0.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 0.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 0.51%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7         | 0.51%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6         | 0.44%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6         | 0.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 0.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6         | 0.44%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6         | 0.44%   |
| JMicron JMB368 IDE controller                                                           | 5         | 0.36%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 0.36%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 0.36%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 710       | 58.34%  |
| NVMe | 324       | 26.62%  |
| IDE  | 121       | 9.94%   |
| RAID | 54        | 4.44%   |
| SAS  | 8         | 0.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 845       | 80.32%  |
| AMD          | 192       | 18.25%  |
| ARM          | 14        | 1.33%   |
| CentaurHauls | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-5250U CPU @ 1.60GHz             | 139       | 13.21%  |
| Intel Celeron CPU N2840 @ 2.16GHz             | 48        | 4.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 23        | 2.19%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 22        | 2.09%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 18        | 1.71%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 15        | 1.43%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 1.24%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 0.95%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 10        | 0.95%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 0.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 0.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.76%   |
| ARM Processor                                 | 8         | 0.76%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 8         | 0.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 0.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 0.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 0.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 0.57%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 6         | 0.57%   |
| Intel Core i3-3210 CPU @ 3.20GHz              | 6         | 0.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.48%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.48%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 5         | 0.48%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 0.48%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.48%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.48%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 5         | 0.48%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 5         | 0.48%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 5         | 0.48%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 0.48%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 5         | 0.48%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 0.48%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 4         | 0.38%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 4         | 0.38%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 4         | 0.38%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.38%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.38%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 4         | 0.38%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.38%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 0.38%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.38%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 0.38%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 4         | 0.38%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 4         | 0.38%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 0.38%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.38%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.38%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 3         | 0.29%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.29%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 3         | 0.29%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 3         | 0.29%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 3         | 0.29%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 3         | 0.29%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.29%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 320       | 30.42%  |
| Intel Core i7           | 171       | 16.25%  |
| Intel Celeron           | 89        | 8.46%   |
| Intel Core i3           | 68        | 6.46%   |
| AMD Ryzen 5             | 61        | 5.8%    |
| Intel Pentium           | 50        | 4.75%   |
| Intel Core 2 Duo        | 39        | 3.71%   |
| Other                   | 37        | 3.52%   |
| AMD Ryzen 7             | 33        | 3.14%   |
| Intel Xeon              | 22        | 2.09%   |
| AMD Ryzen 9             | 11        | 1.05%   |
| AMD Ryzen 3             | 11        | 1.05%   |
| Intel Atom              | 10        | 0.95%   |
| AMD FX                  | 10        | 0.95%   |
| Intel Pentium Dual-Core | 8         | 0.76%   |
| Intel Core 2 Quad       | 8         | 0.76%   |
| AMD Ryzen Threadripper  | 8         | 0.76%   |
| Intel Core 2            | 7         | 0.67%   |
| AMD Ryzen 7 PRO         | 7         | 0.67%   |
| AMD A8                  | 6         | 0.57%   |
| Intel Pentium M         | 5         | 0.48%   |
| Intel Pentium Gold      | 5         | 0.48%   |
| Intel Pentium 4         | 5         | 0.48%   |
| AMD Phenom II X4        | 5         | 0.48%   |
| Intel Core i9           | 4         | 0.38%   |
| AMD Athlon              | 4         | 0.38%   |
| Intel Celeron M         | 3         | 0.29%   |
| AMD A4                  | 3         | 0.29%   |
| AMD A10                 | 3         | 0.29%   |
| Intel Pentium Dual      | 2         | 0.19%   |
| Intel Genuine           | 2         | 0.19%   |
| Intel Core m7           | 2         | 0.19%   |
| AMD Turion 64 Mobile    | 2         | 0.19%   |
| AMD E                   | 2         | 0.19%   |
| AMD Athlon X4           | 2         | 0.19%   |
| AMD Athlon II X2        | 2         | 0.19%   |
| AMD Athlon 64 X2        | 2         | 0.19%   |
| AMD A6                  | 2         | 0.19%   |
| AMD A12                 | 2         | 0.19%   |
| Intel Xeon Silver       | 1         | 0.1%    |
| Intel Pentium Silver    | 1         | 0.1%    |
| Intel Core m3           | 1         | 0.1%    |
| CentaurHauls VIA Eden   | 1         | 0.1%    |
| ARM BCM                 | 1         | 0.1%    |
| ARM Allwinner           | 1         | 0.1%    |
| ARM AArch64             | 1         | 0.1%    |
| AMD Sempron             | 1         | 0.1%    |
| AMD PRO A8              | 1         | 0.1%    |
| AMD Phenom II X6        | 1         | 0.1%    |
| AMD Phenom II X3        | 1         | 0.1%    |
| AMD Opteron             | 1         | 0.1%    |
| AMD GX                  | 1         | 0.1%    |
| AMD E1                  | 1         | 0.1%    |
| AMD C-30                | 1         | 0.1%    |
| AMD Athlon XP           | 1         | 0.1%    |
| AMD Athlon II Neo       | 1         | 0.1%    |
| AMD Athlon Dual Core    | 1         | 0.1%    |
| AMD Athlon 64           | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 557       | 52.95%  |
| 4      | 291       | 27.66%  |
| 8      | 80        | 7.6%    |
| 6      | 67        | 6.37%   |
| 1      | 31        | 2.95%   |
| 16     | 9         | 0.86%   |
| 12     | 9         | 0.86%   |
| 32     | 2         | 0.19%   |
| 24     | 2         | 0.19%   |
| 44     | 1         | 0.1%    |
| 28     | 1         | 0.1%    |
| 14     | 1         | 0.1%    |
| 3      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1038      | 98.67%  |
| 2      | 14        | 1.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 708       | 67.3%   |
| 1      | 344       | 32.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1025      | 97.43%  |
| 32-bit         | 16        | 1.52%   |
| Unknown        | 7         | 0.67%   |
| 64-bit         | 4         | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 163       | 15.39%  |
| 0x306d4    | 156       | 14.73%  |
| 0x306c3    | 60        | 5.67%   |
| 0x306a9    | 52        | 4.91%   |
| 0x30678    | 51        | 4.82%   |
| 0x206a7    | 44        | 4.15%   |
| 0x806e9    | 38        | 3.59%   |
| 0x1067a    | 34        | 3.21%   |
| 0x08108109 | 30        | 2.83%   |
| 0xa0655    | 23        | 2.17%   |
| 0x406e3    | 20        | 1.89%   |
| 0x806ec    | 19        | 1.79%   |
| 0x906ea    | 18        | 1.7%    |
| 0x806c1    | 18        | 1.7%    |
| 0x08701021 | 18        | 1.7%    |
| 0x806ea    | 16        | 1.51%   |
| 0x906e9    | 15        | 1.42%   |
| 0x506e3    | 15        | 1.42%   |
| 0x40651    | 12        | 1.13%   |
| 0x20655    | 11        | 1.04%   |
| 0xa0652    | 10        | 0.94%   |
| 0x706e5    | 9         | 0.85%   |
| 0x08600106 | 9         | 0.85%   |
| 0x806eb    | 8         | 0.76%   |
| 0x6fd      | 8         | 0.76%   |
| 0x206d7    | 8         | 0.76%   |
| 0x6d8      | 6         | 0.57%   |
| 0x506c9    | 6         | 0.57%   |
| 0x306f2    | 6         | 0.57%   |
| 0x0a201009 | 6         | 0.57%   |
| 0x0800820d | 6         | 0.57%   |
| 0x06003106 | 6         | 0.57%   |
| 0x6f6      | 5         | 0.47%   |
| 0x08600104 | 5         | 0.47%   |
| 0x0600611a | 5         | 0.47%   |
| 0x010000c8 | 5         | 0.47%   |
| 0xa0653    | 4         | 0.38%   |
| 0x706a8    | 4         | 0.38%   |
| 0x6fb      | 4         | 0.38%   |
| 0x406c4    | 4         | 0.38%   |
| 0x10676    | 4         | 0.38%   |
| 0x0a50000b | 4         | 0.38%   |
| 0x0a201016 | 4         | 0.38%   |
| 0x08600103 | 4         | 0.38%   |
| 0x08001138 | 4         | 0.38%   |
| 0x06000852 | 4         | 0.38%   |
| 0xf29      | 3         | 0.28%   |
| 0x906ed    | 3         | 0.28%   |
| 0x906eb    | 3         | 0.28%   |
| 0x106e5    | 3         | 0.28%   |
| 0x106c2    | 3         | 0.28%   |
| 0x10677    | 3         | 0.28%   |
| 0x08608103 | 3         | 0.28%   |
| 0x08108102 | 3         | 0.28%   |
| 0x08101016 | 3         | 0.28%   |
| 0x06001119 | 3         | 0.28%   |
| 0x010000b6 | 3         | 0.28%   |
| 0xa0660    | 2         | 0.19%   |
| 0x906ec    | 2         | 0.19%   |
| 0x6fa      | 2         | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Broadwell     | 159       | 15.11%  |
| KabyLake      | 152       | 14.45%  |
| Haswell       | 97        | 9.22%   |
| IvyBridge     | 66        | 6.27%   |
| Silvermont    | 63        | 5.99%   |
| SandyBridge   | 58        | 5.51%   |
| Zen 2         | 51        | 4.85%   |
| Zen+          | 48        | 4.56%   |
| Skylake       | 48        | 4.56%   |
| Penryn        | 45        | 4.28%   |
| CometLake     | 40        | 3.8%    |
| Core          | 24        | 2.28%   |
| Westmere      | 23        | 2.19%   |
| TigerLake     | 22        | 2.09%   |
| Unknown       | 19        | 1.81%   |
| Zen 3         | 18        | 1.71%   |
| Zen           | 15        | 1.43%   |
| K10           | 11        | 1.05%   |
| IceLake       | 11        | 1.05%   |
| Piledriver    | 10        | 0.95%   |
| Excavator     | 9         | 0.86%   |
| P6            | 8         | 0.76%   |
| Steamroller   | 7         | 0.67%   |
| Nehalem       | 7         | 0.67%   |
| Goldmont      | 7         | 0.67%   |
| NetBurst      | 6         | 0.57%   |
| K8 Hammer     | 6         | 0.57%   |
| Goldmont plus | 5         | 0.48%   |
| Puma          | 3         | 0.29%   |
| Bulldozer     | 3         | 0.29%   |
| Bonnell       | 3         | 0.29%   |
| Bobcat        | 3         | 0.29%   |
| K10 Llano     | 2         | 0.19%   |
| Jaguar        | 2         | 0.19%   |
| K6            | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 685       | 58.85%  |
| Nvidia                     | 262       | 22.51%  |
| AMD                        | 201       | 17.27%  |
| ASPEED Technology          | 10        | 0.86%   |
| Matrox Electronics Systems | 4         | 0.34%   |
| VIA Technologies           | 2         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 6000                                                                   | 140       | 11.75%  |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 54        | 4.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 39        | 3.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 37        | 3.11%   |
| AMD Picasso                                                                              | 37        | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 27        | 2.27%   |
| Intel HD Graphics 620                                                                    | 26        | 2.18%   |
| Intel UHD Graphics 620                                                                   | 23        | 1.93%   |
| AMD Renoir                                                                               | 22        | 1.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 1.76%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 20        | 1.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20        | 1.68%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 19        | 1.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 1.6%    |
| Intel HD Graphics 5500                                                                   | 17        | 1.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 1.43%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 16        | 1.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 13        | 1.09%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 13        | 1.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.01%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 12        | 1.01%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 0.84%   |
| Intel HD Graphics 630                                                                    | 10        | 0.84%   |
| Intel HD Graphics 530                                                                    | 10        | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.84%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10        | 0.84%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 10        | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 9         | 0.76%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 9         | 0.76%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 9         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 8         | 0.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 8         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 0.59%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 7         | 0.59%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6         | 0.5%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 6         | 0.5%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 6         | 0.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 0.5%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 0.5%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.5%    |
| AMD Cezanne                                                                              | 6         | 0.5%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.42%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.42%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 5         | 0.42%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.42%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.42%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 5         | 0.42%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 4         | 0.34%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 0.34%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 4         | 0.34%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.34%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 4         | 0.34%   |
| Intel HD Graphics 515                                                                    | 4         | 0.34%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 572       | 54.17%  |
| 1 x AMD            | 168       | 15.91%  |
| 1 x Nvidia         | 167       | 15.81%  |
| Intel + Nvidia     | 85        | 8.05%   |
| Other              | 15        | 1.42%   |
| Intel + AMD        | 15        | 1.42%   |
| 1 x ASPEED         | 9         | 0.85%   |
| 2 x AMD            | 8         | 0.76%   |
| AMD + Nvidia       | 8         | 0.76%   |
| 1 x Matrox         | 3         | 0.28%   |
| 1 x VIA            | 2         | 0.19%   |
| Intel + 2 x Nvidia | 2         | 0.19%   |
| Nvidia + Matrox    | 1         | 0.09%   |
| AMD + ASPEED       | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 765       | 72.65%  |
| Unknown     | 186       | 17.66%  |
| Proprietary | 102       | 9.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 815       | 77.03%  |
| 0.01-0.5   | 63        | 5.95%   |
| 1.01-2.0   | 48        | 4.54%   |
| 0.51-1.0   | 43        | 4.06%   |
| 3.01-4.0   | 38        | 3.59%   |
| 7.01-8.0   | 33        | 3.12%   |
| 5.01-6.0   | 10        | 0.95%   |
| 8.01-16.0  | 3         | 0.28%   |
| 2.01-3.0   | 2         | 0.19%   |
| 16.01-24.0 | 2         | 0.19%   |
| 24.01-32.0 | 1         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Apple                   | 156       | 16.03%  |
| BOE                     | 109       | 11.2%   |
| AU Optronics            | 102       | 10.48%  |
| Samsung Electronics     | 76        | 7.81%   |
| Chimei Innolux          | 71        | 7.3%    |
| LG Display              | 65        | 6.68%   |
| Dell                    | 50        | 5.14%   |
| Goldstar                | 40        | 4.11%   |
| Ancor Communications    | 29        | 2.98%   |
| Acer                    | 27        | 2.77%   |
| Hewlett-Packard         | 22        | 2.26%   |
| BenQ                    | 22        | 2.26%   |
| Sharp                   | 21        | 2.16%   |
| Philips                 | 20        | 2.06%   |
| Lenovo                  | 20        | 2.06%   |
| ViewSonic               | 13        | 1.34%   |
| AOC                     | 12        | 1.23%   |
| NEC Computers           | 11        | 1.13%   |
| InfoVision              | 11        | 1.13%   |
| Unknown                 | 8         | 0.82%   |
| Chi Mei Optoelectronics | 8         | 0.82%   |
| Iiyama                  | 6         | 0.62%   |
| ASUSTek Computer        | 6         | 0.62%   |
| Sony                    | 5         | 0.51%   |
| Eizo                    | 5         | 0.51%   |
| PANDA                   | 4         | 0.41%   |
| MSI                     | 3         | 0.31%   |
| LG Philips              | 3         | 0.31%   |
| LG Electronics          | 3         | 0.31%   |
| CPT                     | 3         | 0.31%   |
| Vizio                   | 2         | 0.21%   |
| Vestel Elektronik       | 2         | 0.21%   |
| ITL                     | 2         | 0.21%   |
| HannStar                | 2         | 0.21%   |
| ___                     | 1         | 0.1%    |
| WTC                     | 1         | 0.1%    |
| VMO                     | 1         | 0.1%    |
| TEO                     | 1         | 0.1%    |
| TCL                     | 1         | 0.1%    |
| SGT                     | 1         | 0.1%    |
| Quanta Display          | 1         | 0.1%    |
| Prestigio               | 1         | 0.1%    |
| ONN                     | 1         | 0.1%    |
| ODH                     | 1         | 0.1%    |
| NCS                     | 1         | 0.1%    |
| Mitsubishi              | 1         | 0.1%    |
| MIT                     | 1         | 0.1%    |
| Mi                      | 1         | 0.1%    |
| Medion                  | 1         | 0.1%    |
| LPL                     | 1         | 0.1%    |
| Lenovo Group Limited    | 1         | 0.1%    |
| JXG                     | 1         | 0.1%    |
| JVC                     | 1         | 0.1%    |
| JRY                     | 1         | 0.1%    |
| IOD                     | 1         | 0.1%    |
| INFOTRONIC              | 1         | 0.1%    |
| Idek Iiyama             | 1         | 0.1%    |
| Hyundai ImageQuest      | 1         | 0.1%    |
| HXF                     | 1         | 0.1%    |
| HKC                     | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 40        | 4.02%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 39        | 3.92%   |
| Apple Color LCD APP9CF2 1366x768 260x140mm 11.6-inch                      | 34        | 3.42%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 30        | 3.02%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 23        | 2.31%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 10        | 1.01%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch             | 10        | 1.01%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 9         | 0.9%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 6         | 0.6%    |
| InfoVision LCD Monitor IVO0533 1366x768 293x164mm 13.2-inch               | 6         | 0.6%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch            | 6         | 0.6%    |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                    | 5         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 5         | 0.5%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch            | 5         | 0.5%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 5         | 0.5%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 5         | 0.5%    |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 4         | 0.4%    |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                   | 4         | 0.4%    |
| NEC Computers LCD1550V NEC65C6 1024x768 304x228mm 15.0-inch               | 4         | 0.4%    |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch               | 4         | 0.4%    |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                         | 4         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 4         | 0.4%    |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 4         | 0.4%    |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                      | 4         | 0.4%    |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch    | 4         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch      | 3         | 0.3%    |
| Philips 220WS PHL0851 1680x1050 474x296mm 22.0-inch                       | 3         | 0.3%    |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 3         | 0.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 3         | 0.3%    |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch               | 3         | 0.3%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 3         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 3         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 3         | 0.3%    |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 3         | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 3         | 0.3%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 3         | 0.3%    |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch              | 3         | 0.3%    |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch                 | 2         | 0.2%    |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 2         | 0.2%    |
| Sony TV *00 SNY8004 3840x2160 1085x610mm 49.0-inch                        | 2         | 0.2%    |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                   | 2         | 0.2%    |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                   | 2         | 0.2%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 2         | 0.2%    |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch      | 2         | 0.2%    |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch      | 2         | 0.2%    |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch        | 2         | 0.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.2%    |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 1050x590mm 47.4-inch    | 2         | 0.2%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 2         | 0.2%    |
| NEC Computers EA244WMi NEC68D7 1920x1080 520x320mm 24.0-inch              | 2         | 0.2%    |
| NEC Computers EA244WMi NEC68D5 1920x1200 520x320mm 24.0-inch              | 2         | 0.2%    |
| LG Philips LCD Monitor LPL1151 1024x768 304x228mm 15.0-inch               | 2         | 0.2%    |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch              | 2         | 0.2%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 2         | 0.2%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 2         | 0.2%    |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch              | 2         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 338       | 35.77%  |
| 1366x768 (WXGA)    | 244       | 25.82%  |
| 1440x900 (WXGA+)   | 77        | 8.15%   |
| 3840x2160 (4K)     | 42        | 4.44%   |
| 2560x1440 (QHD)    | 38        | 4.02%   |
| 1280x1024 (SXGA)   | 30        | 3.17%   |
| 1920x1200 (WUXGA)  | 28        | 2.96%   |
| 1600x900 (HD+)     | 28        | 2.96%   |
| 1680x1050 (WSXGA+) | 22        | 2.33%   |
| 1280x800 (WXGA)    | 21        | 2.22%   |
| 1024x768 (XGA)     | 14        | 1.48%   |
| Unknown            | 9         | 0.95%   |
| 2560x1080          | 7         | 0.74%   |
| 2288x1287          | 6         | 0.63%   |
| 3840x1080          | 5         | 0.53%   |
| 3440x1440          | 5         | 0.53%   |
| 2560x1600          | 4         | 0.42%   |
| 1600x1200          | 4         | 0.42%   |
| 1024x600           | 4         | 0.42%   |
| 2880x1800          | 3         | 0.32%   |
| 3200x1800 (QHD+)   | 2         | 0.21%   |
| 2160x1440          | 2         | 0.21%   |
| 7680x4320          | 1         | 0.11%   |
| 5760x1080          | 1         | 0.11%   |
| 5360x1440          | 1         | 0.11%   |
| 4480x1440          | 1         | 0.11%   |
| 3840x2400          | 1         | 0.11%   |
| 3360x1080          | 1         | 0.11%   |
| 2880x1920          | 1         | 0.11%   |
| 2256x1504          | 1         | 0.11%   |
| 1920x540           | 1         | 0.11%   |
| 1800x1200          | 1         | 0.11%   |
| 1792x768           | 1         | 0.11%   |
| 1360x768           | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 169       | 17.59%  |
| 15      | 156       | 16.23%  |
| 11      | 133       | 13.84%  |
| 14      | 70        | 7.28%   |
| 24      | 69        | 7.18%   |
| 23      | 51        | 5.31%   |
| 27      | 48        | 4.99%   |
| 17      | 41        | 4.27%   |
| 21      | 39        | 4.06%   |
| 12      | 35        | 3.64%   |
| Unknown | 24        | 2.5%    |
| 19      | 17        | 1.77%   |
| 22      | 15        | 1.56%   |
| 31      | 13        | 1.35%   |
| 18      | 12        | 1.25%   |
| 34      | 10        | 1.04%   |
| 20      | 9         | 0.94%   |
| 142     | 6         | 0.62%   |
| 25      | 5         | 0.52%   |
| 10      | 5         | 0.52%   |
| 84      | 4         | 0.42%   |
| 32      | 4         | 0.42%   |
| 28      | 4         | 0.42%   |
| 72      | 2         | 0.21%   |
| 65      | 2         | 0.21%   |
| 48      | 2         | 0.21%   |
| 47      | 2         | 0.21%   |
| 40      | 2         | 0.21%   |
| 29      | 2         | 0.21%   |
| 16      | 2         | 0.21%   |
| 74      | 1         | 0.1%    |
| 55      | 1         | 0.1%    |
| 54      | 1         | 0.1%    |
| 49      | 1         | 0.1%    |
| 46      | 1         | 0.1%    |
| 38      | 1         | 0.1%    |
| 33      | 1         | 0.1%    |
| 26      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 295       | 31.09%  |
| 201-300        | 288       | 30.35%  |
| 501-600        | 156       | 16.44%  |
| 401-500        | 80        | 8.43%   |
| 351-400        | 39        | 4.11%   |
| 601-700        | 27        | 2.85%   |
| Unknown        | 24        | 2.53%   |
| 701-800        | 14        | 1.48%   |
| 1001-1500      | 10        | 1.05%   |
| 1501-2000      | 7         | 0.74%   |
| More than 2000 | 6         | 0.63%   |
| 801-900        | 3         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 641       | 71.54%  |
| 16/10   | 150       | 16.74%  |
| 5/4     | 27        | 3.01%   |
| Unknown | 23        | 2.57%   |
| 4/3     | 22        | 2.46%   |
| 21/9    | 13        | 1.45%   |
| 3/2     | 10        | 1.12%   |
| 1.00    | 7         | 0.78%   |
| 6/5     | 1         | 0.11%   |
| 32/9    | 1         | 0.11%   |
| 1.96    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 159       | 16.61%  |
| 101-110        | 156       | 16.3%   |
| 51-60          | 133       | 13.9%   |
| 201-250        | 131       | 13.69%  |
| 71-80          | 81        | 8.46%   |
| 301-350        | 48        | 5.02%   |
| 151-200        | 40        | 4.18%   |
| 251-300        | 34        | 3.55%   |
| 61-70          | 33        | 3.45%   |
| 351-500        | 32        | 3.34%   |
| 141-150        | 27        | 2.82%   |
| Unknown        | 24        | 2.51%   |
| 121-130        | 23        | 2.4%    |
| More than 1000 | 17        | 1.78%   |
| 501-1000       | 8         | 0.84%   |
| 41-50          | 5         | 0.52%   |
| 131-140        | 3         | 0.31%   |
| 91-100         | 2         | 0.21%   |
| 111-120        | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 435       | 46.28%  |
| 51-100        | 250       | 26.6%   |
| 101-120       | 153       | 16.28%  |
| 161-240       | 51        | 5.43%   |
| Unknown       | 24        | 2.55%   |
| 1-50          | 16        | 1.7%    |
| More than 240 | 11        | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 725       | 68.66%  |
| 0     | 194       | 18.37%  |
| 2     | 123       | 11.65%  |
| 3     | 13        | 1.23%   |
| 4     | 1         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 466       | 33.55%  |
| Realtek Semiconductor             | 461       | 33.19%  |
| Broadcom Limited                  | 156       | 11.23%  |
| Qualcomm Atheros                  | 135       | 9.72%   |
| Broadcom                          | 63        | 4.54%   |
| Marvell Technology Group          | 12        | 0.86%   |
| Nvidia                            | 9         | 0.65%   |
| Ralink                            | 8         | 0.58%   |
| Ralink Technology                 | 7         | 0.5%    |
| Sierra Wireless                   | 6         | 0.43%   |
| TP-Link                           | 4         | 0.29%   |
| Microsoft                         | 4         | 0.29%   |
| JMicron Technology                | 4         | 0.29%   |
| Ericsson Business Mobile Networks | 4         | 0.29%   |
| Dell                              | 4         | 0.29%   |
| Lenovo                            | 3         | 0.22%   |
| DisplayLink                       | 3         | 0.22%   |
| AMD                               | 3         | 0.22%   |
| Xiaomi                            | 2         | 0.14%   |
| VIA Technologies                  | 2         | 0.14%   |
| Qualcomm Atheros Communications   | 2         | 0.14%   |
| Microchip Technology              | 2         | 0.14%   |
| Mellanox Technologies             | 2         | 0.14%   |
| MEDIATEK                          | 2         | 0.14%   |
| Edimax Technology                 | 2         | 0.14%   |
| D-Link                            | 2         | 0.14%   |
| Cypress Semiconductor             | 2         | 0.14%   |
| Aquantia                          | 2         | 0.14%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.07%   |
| Wilocity                          | 1         | 0.07%   |
| U-Blox                            | 1         | 0.07%   |
| Qualcomm                          | 1         | 0.07%   |
| NetGear                           | 1         | 0.07%   |
| Micro Star International          | 1         | 0.07%   |
| IMC Networks                      | 1         | 0.07%   |
| IBM                               | 1         | 0.07%   |
| Huawei Technologies               | 1         | 0.07%   |
| Hewlett-Packard                   | 1         | 0.07%   |
| Google                            | 1         | 0.07%   |
| Fibocom                           | 1         | 0.07%   |
| Attansic Technology               | 1         | 0.07%   |
| ASUSTek Computer                  | 1         | 0.07%   |
| ASIX Electronics                  | 1         | 0.07%   |
| American Megatrends               | 1         | 0.07%   |
| ADMtek                            | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 351       | 21.75%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 140       | 8.67%   |
| Intel Wireless 7260                                               | 65        | 4.03%   |
| Intel Wireless 8265 / 8275                                        | 45        | 2.79%   |
| Intel Wi-Fi 6 AX200                                               | 45        | 2.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 42        | 2.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 39        | 2.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 1.98%   |
| Intel I211 Gigabit Network Connection                             | 24        | 1.49%   |
| Intel Ethernet Connection (4) I219-V                              | 24        | 1.49%   |
| Intel Wireless 8260                                               | 22        | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 19        | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 1.12%   |
| Intel Wireless 7265                                               | 17        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 0.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 0.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 0.81%   |
| Intel Wi-Fi 6 AX201                                               | 13        | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 0.74%   |
| Intel Wireless 3165                                               | 12        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12        | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 0.68%   |
| Intel I210 Gigabit Network Connection                             | 11        | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 0.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 0.62%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 0.56%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 8         | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 8         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.43%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 0.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 0.43%   |
| Intel Centrino Wireless-N 2230                                    | 7         | 0.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 0.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.37%   |
| Intel Wireless-AC 9260                                            | 6         | 0.37%   |
| Intel Wireless 3160                                               | 6         | 0.37%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.37%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.37%   |
| Intel Centrino Ultimate-N 6300                                    | 6         | 0.37%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 0.37%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 5         | 0.31%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.31%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.31%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 5         | 0.31%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 0.31%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.31%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.31%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 0.31%   |
| Sierra Wireless EM7345 4G LTE                                     | 4         | 0.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 357       | 47.35%  |
| Broadcom Limited                | 148       | 19.63%  |
| Qualcomm Atheros                | 105       | 13.93%  |
| Realtek Semiconductor           | 71        | 9.42%   |
| Broadcom                        | 33        | 4.38%   |
| Ralink                          | 8         | 1.06%   |
| Ralink Technology               | 7         | 0.93%   |
| Microsoft                       | 4         | 0.53%   |
| TP-Link                         | 3         | 0.4%    |
| Sierra Wireless                 | 2         | 0.27%   |
| Qualcomm Atheros Communications | 2         | 0.27%   |
| MEDIATEK                        | 2         | 0.27%   |
| Edimax Technology               | 2         | 0.27%   |
| Dell                            | 2         | 0.27%   |
| Wilocity                        | 1         | 0.13%   |
| Qualcomm                        | 1         | 0.13%   |
| NetGear                         | 1         | 0.13%   |
| Micro Star International        | 1         | 0.13%   |
| IMC Networks                    | 1         | 0.13%   |
| Fibocom                         | 1         | 0.13%   |
| D-Link                          | 1         | 0.13%   |
| ASUSTek Computer                | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 140       | 18.47%  |
| Intel Wireless 7260                                                     | 65        | 8.58%   |
| Intel Wireless 8265 / 8275                                              | 45        | 5.94%   |
| Intel Wi-Fi 6 AX200                                                     | 45        | 5.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 39        | 5.15%   |
| Intel Wireless 8260                                                     | 22        | 2.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 2.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 2.37%   |
| Intel Wireless 7265                                                     | 17        | 2.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 1.72%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.58%   |
| Intel Wireless 3165                                                     | 12        | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 1.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 8         | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 0.92%   |
| Intel Centrino Wireless-N 2230                                          | 7         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 0.79%   |
| Intel Wireless-AC 9260                                                  | 6         | 0.79%   |
| Intel Wireless 3160                                                     | 6         | 0.79%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 0.79%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.53%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 4         | 0.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 0.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.53%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.53%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 0.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.4%    |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.4%    |
| Microsoft Xbox 360 Wireless Adapter                                     | 3         | 0.4%    |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.4%    |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.4%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3         | 0.4%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.4%    |
| Sierra Wireless EM7455                                                  | 2         | 0.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.26%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.26%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.26%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 0.26%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.26%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.26%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.26%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 0.26%   |
| MEDIATEK Network controller                                             | 2         | 0.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.26%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 0.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 428       | 52.26%  |
| Intel                      | 250       | 30.53%  |
| Broadcom                   | 38        | 4.64%   |
| Qualcomm Atheros           | 37        | 4.52%   |
| Marvell Technology Group   | 12        | 1.47%   |
| Nvidia                     | 9         | 1.1%    |
| Broadcom Limited           | 9         | 1.1%    |
| Sierra Wireless            | 4         | 0.49%   |
| JMicron Technology         | 4         | 0.49%   |
| Lenovo                     | 3         | 0.37%   |
| DisplayLink                | 3         | 0.37%   |
| Xiaomi                     | 2         | 0.24%   |
| VIA Technologies           | 2         | 0.24%   |
| Microchip Technology       | 2         | 0.24%   |
| Mellanox Technologies      | 2         | 0.24%   |
| Cypress Semiconductor      | 2         | 0.24%   |
| Aquantia                   | 2         | 0.24%   |
| ZTE WCDMA Technologies MSM | 1         | 0.12%   |
| TP-Link                    | 1         | 0.12%   |
| IBM                        | 1         | 0.12%   |
| Huawei Technologies        | 1         | 0.12%   |
| Google                     | 1         | 0.12%   |
| D-Link                     | 1         | 0.12%   |
| Attansic Technology        | 1         | 0.12%   |
| ASIX Electronics           | 1         | 0.12%   |
| American Megatrends        | 1         | 0.12%   |
| ADMtek                     | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 351       | 41.79%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 42        | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 3.81%   |
| Intel I211 Gigabit Network Connection                             | 24        | 2.86%   |
| Intel Ethernet Connection (4) I219-V                              | 24        | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 1.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 1.43%   |
| Intel I210 Gigabit Network Connection                             | 11        | 1.31%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 1.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.95%   |
| Intel Ethernet Connection I217-V                                  | 8         | 0.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.71%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.6%    |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.6%    |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.6%    |
| Intel 82574L Gigabit Network Connection                           | 5         | 0.6%    |
| Sierra Wireless EM7345 4G LTE                                     | 4         | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.48%   |
| Nvidia MCP61 Ethernet                                             | 4         | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 4         | 0.48%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 0.48%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 3         | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3         | 0.36%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.36%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.36%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.36%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.36%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.36%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.36%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 3         | 0.36%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 0.36%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 0.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.24%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2         | 0.24%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.24%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2         | 0.24%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.24%   |
| Nvidia MCP89 Ethernet                                             | 2         | 0.24%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.24%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2         | 0.24%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.24%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.24%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 2         | 0.24%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.24%   |
| Intel Ethernet Controller 10G X550T                               | 2         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 777       | 50.92%  |
| WiFi     | 733       | 48.03%  |
| Modem    | 16        | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 655       | 50.31%  |
| WiFi     | 645       | 49.54%  |
| Modem    | 2         | 0.15%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 555       | 52.76%  |
| 2     | 448       | 42.59%  |
| 3     | 20        | 1.9%    |
| 0     | 19        | 1.81%   |
| 4     | 5         | 0.48%   |
| 6     | 3         | 0.29%   |
| 13    | 1         | 0.1%    |
| 5     | 1         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 924       | 87.67%  |
| Yes  | 130       | 12.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 288       | 44.38%  |
| Apple                           | 156       | 24.04%  |
| Realtek Semiconductor           | 38        | 5.86%   |
| Qualcomm Atheros Communications | 35        | 5.39%   |
| Broadcom                        | 31        | 4.78%   |
| Lite-On Technology              | 27        | 4.16%   |
| Cambridge Silicon Radio         | 22        | 3.39%   |
| IMC Networks                    | 12        | 1.85%   |
| Foxconn / Hon Hai               | 9         | 1.39%   |
| ASUSTek Computer                | 8         | 1.23%   |
| Hewlett-Packard                 | 5         | 0.77%   |
| Toshiba                         | 3         | 0.46%   |
| Realtek                         | 3         | 0.46%   |
| Ralink                          | 3         | 0.46%   |
| Dell                            | 3         | 0.46%   |
| Taiyo Yuden                     | 2         | 0.31%   |
| Belkin Components               | 2         | 0.31%   |
| Sitecom Europe                  | 1         | 0.15%   |
| Micro Star International        | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 173       | 26.62%  |
| Apple Bluetooth USB Host Controller                                                 | 142       | 21.85%  |
| Intel Bluetooth wireless interface                                                  | 65        | 10%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 29        | 4.46%   |
| Realtek Bluetooth Radio                                                             | 26        | 4%      |
| Qualcomm Atheros  Bluetooth Device                                                  | 24        | 3.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 22        | 3.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 19        | 2.92%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 1.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 7         | 1.08%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 1.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 7         | 1.08%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 0.92%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 0.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 6         | 0.92%   |
| Apple Bluetooth Host Controller                                                     | 6         | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 0.62%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 0.62%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 0.62%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 0.62%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 4         | 0.62%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.46%   |
| Realtek Bluetooth Radio                                                             | 3         | 0.46%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.46%   |
| Lite-On Bluetooth Device                                                            | 3         | 0.46%   |
| IMC Networks Bluetooth                                                              | 3         | 0.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.31%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.31%   |
| Lite-On BCM43142A0                                                                  | 2         | 0.31%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.31%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.31%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.31%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 0.31%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.31%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.31%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 2         | 0.31%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                                           | 2         | 0.31%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)                                             | 1         | 0.15%   |
| Taiyo Yuden Bluetooth Device                                                        | 1         | 0.15%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521                           | 1         | 0.15%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.15%   |
| Realtek CSR BS8510                                                                  | 1         | 0.15%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.15%   |
| Micro Star International Bluetooth EDR Device                                       | 1         | 0.15%   |
| Lite-On Wireless_Device                                                             | 1         | 0.15%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.15%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.15%   |
| IMC Networks Bluetooth module                                                       | 1         | 0.15%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.15%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.15%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.15%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 1         | 0.15%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.15%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.15%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.15%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.15%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.15%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 811       | 60.03%  |
| AMD                        | 219       | 16.21%  |
| Nvidia                     | 205       | 15.17%  |
| C-Media Electronics        | 17        | 1.26%   |
| Logitech                   | 11        | 0.81%   |
| Generalplus Technology     | 9         | 0.67%   |
| GN Netcom                  | 5         | 0.37%   |
| Creative Labs              | 5         | 0.37%   |
| VIA Technologies           | 4         | 0.3%    |
| Plantronics                | 4         | 0.3%    |
| Lenovo                     | 4         | 0.3%    |
| GYROCOM C&C                | 4         | 0.3%    |
| Unknown                    | 3         | 0.22%   |
| Texas Instruments          | 3         | 0.22%   |
| RODE Microphones           | 3         | 0.22%   |
| JMTek                      | 3         | 0.22%   |
| Creative Technology        | 3         | 0.22%   |
| Yamaha                     | 2         | 0.15%   |
| XMOS                       | 2         | 0.15%   |
| Sennheiser Communications  | 2         | 0.15%   |
| Samson Technologies        | 2         | 0.15%   |
| Cambridge Silicon Radio    | 2         | 0.15%   |
| BEHRINGER International    | 2         | 0.15%   |
| ASUSTek Computer           | 2         | 0.15%   |
| TerraTec Electronic        | 1         | 0.07%   |
| TEAC                       | 1         | 0.07%   |
| SteelSeries ApS            | 1         | 0.07%   |
| SAVITECH                   | 1         | 0.07%   |
| ROCCAT                     | 1         | 0.07%   |
| Razer USA                  | 1         | 0.07%   |
| PreSonus Audio Electronics | 1         | 0.07%   |
| Musical Fidelity           | 1         | 0.07%   |
| Microsoft                  | 1         | 0.07%   |
| Micronas                   | 1         | 0.07%   |
| M-Audio                    | 1         | 0.07%   |
| Kingston Technology        | 1         | 0.07%   |
| Hewlett-Packard            | 1         | 0.07%   |
| Hangzhou Worlde            | 1         | 0.07%   |
| Focusrite-Novation         | 1         | 0.07%   |
| Dell                       | 1         | 0.07%   |
| C&T12L5V                   | 1         | 0.07%   |
| Blue Microphones           | 1         | 0.07%   |
| B & W Group                | 1         | 0.07%   |
| AXELVOX                    | 1         | 0.07%   |
| AVID Technology            | 1         | 0.07%   |
| Audioengine                | 1         | 0.07%   |
| Apple                      | 1         | 0.07%   |
| Alesis                     | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wildcat Point-LP High Definition Audio Controller                    | 157       | 9.22%   |
| Intel Broadwell-U Audio Controller                                         | 157       | 9.22%   |
| Intel Sunrise Point-LP HD Audio                                            | 90        | 5.28%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 75        | 4.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 62        | 3.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 62        | 3.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 52        | 3.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 51        | 2.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 47        | 2.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 41        | 2.41%   |
| AMD Starship/Matisse HD Audio Controller                                   | 38        | 2.23%   |
| Intel Comet Lake PCH cAVS                                                  | 35        | 2.06%   |
| Nvidia GF108 High Definition Audio Controller                              | 31        | 1.82%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 27        | 1.59%   |
| Nvidia TU106 High Definition Audio Controller                              | 26        | 1.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 26        | 1.53%   |
| Intel Cannon Lake PCH cAVS                                                 | 25        | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 22        | 1.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 22        | 1.29%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 22        | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 22        | 1.29%   |
| Intel Comet Lake PCH-LP cAVS                                               | 21        | 1.23%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 21        | 1.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 21        | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                      | 18        | 1.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 18        | 1.06%   |
| Intel 8 Series HD Audio Controller                                         | 18        | 1.06%   |
| Intel 200 Series PCH HD Audio                                              | 18        | 1.06%   |
| AMD FCH Azalia Controller                                                  | 18        | 1.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 18        | 1.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 16        | 0.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13        | 0.76%   |
| AMD Navi 10 HDMI Audio                                                     | 12        | 0.7%    |
| AMD Kabini HDMI/DP Audio                                                   | 12        | 0.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 11        | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 11        | 0.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 10        | 0.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10        | 0.59%   |
| Nvidia GP104 High Definition Audio Controller                              | 9         | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                         | 9         | 0.53%   |
| Generalplus Technology USB Audio Device                                    | 9         | 0.53%   |
| Nvidia High Definition Audio Controller                                    | 8         | 0.47%   |
| Nvidia GF119 HDMI Audio Controller                                         | 8         | 0.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 7         | 0.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 7         | 0.41%   |
| Nvidia GP108 High Definition Audio Controller                              | 6         | 0.35%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 0.35%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 6         | 0.35%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6         | 0.35%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 6         | 0.35%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6         | 0.35%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.29%   |
| Nvidia GM204 High Definition Audio Controller                              | 5         | 0.29%   |
| Nvidia GF116 High Definition Audio Controller                              | 5         | 0.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.29%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5         | 0.29%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 5         | 0.29%   |
| Nvidia MCP61 High Definition Audio                                         | 4         | 0.23%   |
| Nvidia GK104 HDMI Audio Controller                                         | 4         | 0.23%   |
| Nvidia GA102 High Definition Audio Controller                              | 4         | 0.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 271       | 25.47%  |
| SK Hynix                | 164       | 15.41%  |
| Kingston                | 127       | 11.94%  |
| Unknown                 | 97        | 9.12%   |
| Crucial                 | 81        | 7.61%   |
| Micron Technology       | 80        | 7.52%   |
| Elpida                  | 54        | 5.08%   |
| Corsair                 | 47        | 4.42%   |
| G.Skill                 | 25        | 2.35%   |
| Hikvision               | 20        | 1.88%   |
| A-DATA Technology       | 15        | 1.41%   |
| Ramaxel Technology      | 14        | 1.32%   |
| Patriot                 | 11        | 1.03%   |
| Nanya Technology        | 9         | 0.85%   |
| Team                    | 5         | 0.47%   |
| AMD                     | 4         | 0.38%   |
| Unknown (ABCD)          | 3         | 0.28%   |
| Smart                   | 3         | 0.28%   |
| Kllisre                 | 3         | 0.28%   |
| GOODRAM                 | 3         | 0.28%   |
| Unknown (0x07D5)        | 2         | 0.19%   |
| PNY                     | 2         | 0.19%   |
| Infineon                | 2         | 0.19%   |
| Goldkey                 | 2         | 0.19%   |
| ASint Technology        | 2         | 0.19%   |
| Apacer                  | 2         | 0.19%   |
| Wilk                    | 1         | 0.09%   |
| V-Color                 | 1         | 0.09%   |
| Unknown (0080000080AD)  | 1         | 0.09%   |
| Unknown (000000000FE02) | 1         | 0.09%   |
| Unknown (0000000002C80) | 1         | 0.09%   |
| Unifosa                 | 1         | 0.09%   |
| Transcend               | 1         | 0.09%   |
| SMART Brazil            | 1         | 0.09%   |
| Silicon Power           | 1         | 0.09%   |
| Sesame                  | 1         | 0.09%   |
| Qimonda                 | 1         | 0.09%   |
| OCZ                     | 1         | 0.09%   |
| Novatech                | 1         | 0.09%   |
| Kingmax                 | 1         | 0.09%   |
| KETECH                  | 1         | 0.09%   |
| GeIL                    | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                         | 59        | 5.22%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s               | 38        | 3.36%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 30        | 2.65%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 20        | 1.77%   |
| Hikvision RAM HKED4161DAA1D0MA1 16384MB DIMM DDR4 2667MT/s          | 20        | 1.77%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 19        | 1.68%   |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1600MT/s            | 19        | 1.68%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 18        | 1.59%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s              | 17        | 1.5%    |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                          | 15        | 1.33%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s                | 10        | 0.88%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 8         | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 8         | 0.71%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 6         | 0.53%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 6         | 0.53%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 6         | 0.53%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s            | 6         | 0.53%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 5         | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                         | 5         | 0.44%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 5         | 0.44%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.44%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 0.44%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s              | 5         | 0.44%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s               | 5         | 0.44%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 4         | 0.35%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                         | 4         | 0.35%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.35%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 0.35%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 4         | 0.35%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.35%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 4         | 0.35%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 0.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 4         | 0.35%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 4         | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                           | 3         | 0.27%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 3         | 0.27%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 3         | 0.27%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                              | 3         | 0.27%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 0.27%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 0.27%   |
| SK Hynix RAM 4GBPC1600PB N0 4096MB DIMM DDR3 1067MT/s               | 3         | 0.27%   |
| Samsung RAM Module 1GB SODIMM DDR2 533MT/s                          | 3         | 0.27%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 3         | 0.27%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.27%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.27%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 3         | 0.27%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 3         | 0.27%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 3         | 0.27%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                   | 3         | 0.27%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s                 | 3         | 0.27%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s                 | 3         | 0.27%   |
| Kingston RAM 99U5474-010.A00LF 2048MB DIMM DDR3 1333MT/s            | 3         | 0.27%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s          | 3         | 0.27%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s              | 3         | 0.27%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s          | 3         | 0.27%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s               | 3         | 0.27%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s            | 3         | 0.27%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                              | 2         | 0.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 457       | 48%     |
| DDR4    | 357       | 37.5%   |
| DDR2    | 45        | 4.73%   |
| LPDDR3  | 24        | 2.52%   |
| Unknown | 23        | 2.42%   |
| SDRAM   | 21        | 2.21%   |
| DDR     | 13        | 1.37%   |
| LPDDR4  | 11        | 1.16%   |
| DRAM    | 1         | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 568       | 59.6%   |
| DIMM         | 340       | 35.68%  |
| Row Of Chips | 36        | 3.78%   |
| Chip         | 7         | 0.73%   |
| RIMM         | 1         | 0.1%    |
| Unknown      | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 309       | 30.35%  |
| 8192  | 281       | 27.6%   |
| 2048  | 223       | 21.91%  |
| 16384 | 115       | 11.3%   |
| 1024  | 46        | 4.52%   |
| 32768 | 25        | 2.46%   |
| 512   | 13        | 1.28%   |
| 256   | 5         | 0.49%   |
| 65536 | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 358       | 35.24%  |
| 2667    | 149       | 14.67%  |
| 3200    | 99        | 9.74%   |
| 1333    | 81        | 7.97%   |
| 2400    | 53        | 5.22%   |
| 2133    | 42        | 4.13%   |
| 800     | 24        | 2.36%   |
| 1334    | 23        | 2.26%   |
| 1867    | 21        | 2.07%   |
| 667     | 20        | 1.97%   |
| Unknown | 19        | 1.87%   |
| 3600    | 15        | 1.48%   |
| 1067    | 12        | 1.18%   |
| 2666    | 10        | 0.98%   |
| 2933    | 8         | 0.79%   |
| 1866    | 8         | 0.79%   |
| 1066    | 8         | 0.79%   |
| 533     | 7         | 0.69%   |
| 3000    | 6         | 0.59%   |
| 400     | 6         | 0.59%   |
| 3466    | 5         | 0.49%   |
| 333     | 5         | 0.49%   |
| 4267    | 4         | 0.39%   |
| 4199    | 3         | 0.3%    |
| 3400    | 3         | 0.3%    |
| 1800    | 3         | 0.3%    |
| 4333    | 2         | 0.2%    |
| 3533    | 2         | 0.2%    |
| 3500    | 2         | 0.2%    |
| 3100    | 2         | 0.2%    |
| 2000    | 2         | 0.2%    |
| 975     | 2         | 0.2%    |
| 4266    | 1         | 0.1%    |
| 3866    | 1         | 0.1%    |
| 3733    | 1         | 0.1%    |
| 3066    | 1         | 0.1%    |
| 2866    | 1         | 0.1%    |
| 2465    | 1         | 0.1%    |
| 2267    | 1         | 0.1%    |
| 2187    | 1         | 0.1%    |
| 2048    | 1         | 0.1%    |
| 1400    | 1         | 0.1%    |
| 1367    | 1         | 0.1%    |
| 66      | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 50%     |
| Samsung Electronics | 3         | 18.75%  |
| Canon               | 2         | 12.5%   |
| Brother Industries  | 2         | 12.5%   |
| Konica Minolta      | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| HP LaserJet 1200                    | 2         | 12.5%   |
| Samsung SCX-4650 4x21S Series       | 1         | 6.25%   |
| Samsung ML-2010P Mono Laser Printer | 1         | 6.25%   |
| Samsung ML-1660 Series              | 1         | 6.25%   |
| Konica Minolta bizhub 4402P         | 1         | 6.25%   |
| HP LaserJet P1006                   | 1         | 6.25%   |
| HP LaserJet M101-M106               | 1         | 6.25%   |
| HP LaserJet 400 M401dn              | 1         | 6.25%   |
| HP LaserJet 1150                    | 1         | 6.25%   |
| HP ENVY 5000 series                 | 1         | 6.25%   |
| HP ENVY 4520 series                 | 1         | 6.25%   |
| Canon LiDE 400                      | 1         | 6.25%   |
| Canon iP2700 series                 | 1         | 6.25%   |
| Brother MFC-L2710DW series          | 1         | 6.25%   |
| Brother MFC-L2707DW                 | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 4         | 66.67%  |
| Canon       | 2         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 33.33%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 16.67%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 1         | 16.67%  |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]            | 1         | 16.67%  |
| Seiko Epson GT-7700U [Perfection 1240U]                  | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 108       | 21.51%  |
| Quanta                                 | 68        | 13.55%  |
| IMC Networks                           | 52        | 10.36%  |
| Acer                                   | 45        | 8.96%   |
| Microdia                               | 39        | 7.77%   |
| Realtek Semiconductor                  | 34        | 6.77%   |
| Logitech                               | 28        | 5.58%   |
| Suyin                                  | 16        | 3.19%   |
| Apple                                  | 14        | 2.79%   |
| Sunplus Innovation Technology          | 13        | 2.59%   |
| Lite-On Technology                     | 13        | 2.59%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 1.99%   |
| Syntek                                 | 8         | 1.59%   |
| Luxvisions Innotech Limited            | 6         | 1.2%    |
| Lenovo                                 | 6         | 1.2%    |
| Samsung Electronics                    | 4         | 0.8%    |
| Z-Star Microelectronics                | 3         | 0.6%    |
| Silicon Motion                         | 3         | 0.6%    |
| Primax Electronics                     | 3         | 0.6%    |
| Generalplus Technology                 | 3         | 0.6%    |
| Microsoft                              | 2         | 0.4%    |
| Genesys Logic                          | 2         | 0.4%    |
| eMPIA Technology                       | 2         | 0.4%    |
| Alcor Micro                            | 2         | 0.4%    |
| Xiongmai                               | 1         | 0.2%    |
| Unknown                                | 1         | 0.2%    |
| SiGma Micro                            | 1         | 0.2%    |
| Ricoh                                  | 1         | 0.2%    |
| Razer USA                              | 1         | 0.2%    |
| Pixart Imaging                         | 1         | 0.2%    |
| Philips (or NXP)                       | 1         | 0.2%    |
| Novatek Microelectronics               | 1         | 0.2%    |
| KYE Systems (Mouse Systems)            | 1         | 0.2%    |
| Jieli Technology                       | 1         | 0.2%    |
| Huawei Technologies                    | 1         | 0.2%    |
| Hewlett-Packard                        | 1         | 0.2%    |
| Creative Technology                    | 1         | 0.2%    |
| AVerMedia Technologies                 | 1         | 0.2%    |
| ARC International                      | 1         | 0.2%    |
| ALi                                    | 1         | 0.2%    |
| A4Tech                                 | 1         | 0.2%    |
| 8SSC20F27114V1SR11K1SE2                | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 41        | 8.13%   |
| Quanta Chromebook HD Camera                         | 37        | 7.34%   |
| Acer Integrated Camera                              | 23        | 4.56%   |
| Quanta VGA WebCam                                   | 18        | 3.57%   |
| IMC Networks Integrated Camera                      | 18        | 3.57%   |
| Microdia Integrated_Webcam_HD                       | 17        | 3.37%   |
| Realtek Integrated_Webcam_HD                        | 15        | 2.98%   |
| Chicony HD Webcam                                   | 14        | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 10        | 1.98%   |
| Chicony Chromebook HD Camera                        | 10        | 1.98%   |
| Logitech Webcam C270                                | 7         | 1.39%   |
| Chicony HP HD Camera                                | 7         | 1.39%   |
| Apple Built-in iSight                               | 6         | 1.19%   |
| Microdia Webcam Vitade AF                           | 5         | 0.99%   |
| Logitech HD Pro Webcam C920                         | 5         | 0.99%   |
| Lite-On Integrated Camera                           | 5         | 0.99%   |
| Syntek Integrated Camera                            | 4         | 0.79%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 0.79%   |
| Samsung Galaxy A5 (MTP)                             | 4         | 0.79%   |
| Lenovo Integrated Webcam                            | 4         | 0.79%   |
| Chicony USB2.0 Camera                               | 4         | 0.79%   |
| Chicony Integrated Camera (1280x720@30)             | 4         | 0.79%   |
| Acer Lenovo EasyCamera                              | 4         | 0.79%   |
| Acer BisonCam, NB Pro                               | 4         | 0.79%   |
| Realtek Integrated Webcam                           | 3         | 0.6%    |
| Quanta HP TrueVision HD Camera                      | 3         | 0.6%    |
| Microdia USB 2.0 Camera                             | 3         | 0.6%    |
| Microdia Integrated Webcam HD                       | 3         | 0.6%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 0.6%    |
| Lite-On HP HD Camera                                | 3         | 0.6%    |
| IMC Networks UVC VGA Webcam                         | 3         | 0.6%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 0.6%    |
| IMC Networks USB2.0 HD IR UVC WebCam                | 3         | 0.6%    |
| IMC Networks SunplusIT Integrated Camera            | 3         | 0.6%    |
| IMC Networks HP TrueVision HD Camera                | 3         | 0.6%    |
| Chicony Lenovo EasyCamera                           | 3         | 0.6%    |
| Chicony EasyCamera                                  | 3         | 0.6%    |
| Acer ThinkPad Integrated Camera                     | 3         | 0.6%    |
| Acer EasyCamera                                     | 3         | 0.6%    |
| Syntek Lenovo EasyCamera                            | 2         | 0.4%    |
| Suyin Integrated_Webcam_HD                          | 2         | 0.4%    |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 0.4%    |
| Suyin 1.3M HD WebCam                                | 2         | 0.4%    |
| Sunplus HP Universal Camera                         | 2         | 0.4%    |
| Realtek USB Camera                                  | 2         | 0.4%    |
| Realtek Integrated Webcam_HD                        | 2         | 0.4%    |
| Realtek Integrated Webcam HD                        | 2         | 0.4%    |
| Realtek EasyCamera                                  | 2         | 0.4%    |
| Quanta HP Wide Vision HD Camera                     | 2         | 0.4%    |
| Quanta HP Webcam                                    | 2         | 0.4%    |
| Quanta HD Webcam                                    | 2         | 0.4%    |
| Microsoft LifeCam HD-3000                           | 2         | 0.4%    |
| Microdia Integrated Webcam                          | 2         | 0.4%    |
| Luxvisions Innotech Limited HP HD Camera            | 2         | 0.4%    |
| Logitech HD Webcam C910                             | 2         | 0.4%    |
| Logitech HD Webcam C615                             | 2         | 0.4%    |
| Logitech C505 HD Webcam                             | 2         | 0.4%    |
| Lite-On HP Webcam                                   | 2         | 0.4%    |
| IMC Networks ov9734_azurewave_camera                | 2         | 0.4%    |
| IMC Networks Lenovo EasyCamera                      | 2         | 0.4%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 43        | 40.95%  |
| Synaptics                  | 24        | 22.86%  |
| Shenzhen Goodix Technology | 17        | 16.19%  |
| Upek                       | 7         | 6.67%   |
| AuthenTec                  | 6         | 5.71%   |
| Elan Microelectronics      | 4         | 3.81%   |
| LighTuning Technology      | 3         | 2.86%   |
| STMicroelectronics         | 1         | 0.95%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 16.19%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 9.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 7.62%   |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 7.62%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 5.71%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 5.71%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 4.76%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 4.76%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.81%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 2.86%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.86%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.9%    |
| Unknown                                                                    | 2         | 1.9%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.95%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.95%   |
| Synaptics  WBDI                                                            | 1         | 0.95%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.95%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.95%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.95%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 15        | 32.61%  |
| Alcor Micro           | 15        | 32.61%  |
| Lenovo                | 6         | 13.04%  |
| Upek                  | 5         | 10.87%  |
| Yubico.com            | 1         | 2.17%   |
| OmniKey               | 1         | 2.17%   |
| O2 Micro              | 1         | 2.17%   |
| Gemalto (was Gemplus) | 1         | 2.17%   |
| Cherry                | 1         | 2.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 32.61%  |
| Lenovo Integrated Smart Card Reader                                          | 6         | 13.04%  |
| Broadcom 5880                                                                | 6         | 13.04%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 10.87%  |
| Broadcom 58200                                                               | 5         | 10.87%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 4.35%   |
| Yubico.com Yubikey 4 CCID                                                    | 1         | 2.17%   |
| OmniKey CardMan 4321                                                         | 1         | 2.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.17%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 2.17%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 2.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 556       | 52.55%  |
| 1     | 432       | 40.83%  |
| 2     | 62        | 5.86%   |
| 3     | 5         | 0.47%   |
| 5     | 2         | 0.19%   |
| 4     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 196       | 35.77%  |
| Multimedia controller    | 154       | 28.1%   |
| Fingerprint reader       | 105       | 19.16%  |
| Chipcard                 | 37        | 6.75%   |
| Net/wireless             | 15        | 2.74%   |
| Communication controller | 14        | 2.55%   |
| Unassigned class         | 8         | 1.46%   |
| Bluetooth                | 5         | 0.91%   |
| Storage                  | 4         | 0.73%   |
| Network                  | 3         | 0.55%   |
| Sound                    | 2         | 0.36%   |
| Card reader              | 2         | 0.36%   |
| Net/ethernet             | 1         | 0.18%   |
| Modem                    | 1         | 0.18%   |
| Firewire controller      | 1         | 0.18%   |

