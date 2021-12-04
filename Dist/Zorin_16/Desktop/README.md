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


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.11.0-27-generic | 55       | 20.75%  |
| 5.11.0-38-generic | 50       | 18.87%  |
| 5.11.0-40-generic | 46       | 17.36%  |
| 5.11.0-37-generic | 34       | 12.83%  |
| 5.11.0-34-generic | 31       | 11.7%   |
| 5.11.0-36-generic | 12       | 4.53%   |
| 5.11.0-41-generic | 8        | 3.02%   |
| 5.8.0-53-generic  | 7        | 2.64%   |
| 5.8.0-55-generic  | 5        | 1.89%   |
| 5.8.0-50-generic  | 5        | 1.89%   |
| 5.8.0-59-generic  | 3        | 1.13%   |
| 5.8.0-49-generic  | 3        | 1.13%   |
| 5.11.0-25-generic | 3        | 1.13%   |
| 5.8.0-63-generic  | 2        | 0.75%   |
| 5.8.0-45-generic  | 1        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 234      | 90.35%  |
| 5.8.0   | 25       | 9.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 234      | 90.35%  |
| 5.8     | 25       | 9.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 254      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME    | 247      | 96.86%  |
| XFCE     | 3        | 1.18%   |
| Unknown  | 3        | 1.18%   |
| MATE     | 1        | 0.39%   |
| Cinnamon | 1        | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 254      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 229      | 90.16%  |
| GDM3    | 12       | 4.72%   |
| GDM     | 12       | 4.72%   |
| TDM     | 1        | 0.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 105      | 41.34%  |
| de_DE | 27       | 10.63%  |
| en_GB | 26       | 10.24%  |
| pt_BR | 16       | 6.3%    |
| en_IN | 8        | 3.15%   |
| en_CA | 7        | 2.76%   |
| nl_NL | 6        | 2.36%   |
| it_IT | 6        | 2.36%   |
| es_ES | 6        | 2.36%   |
| pl_PL | 5        | 1.97%   |
| es_MX | 5        | 1.97%   |
| fr_FR | 3        | 1.18%   |
| en_ZA | 3        | 1.18%   |
| tr_TR | 2        | 0.79%   |
| nl_BE | 2        | 0.79%   |
| hu_HU | 2        | 0.79%   |
| fr_CA | 2        | 0.79%   |
| en_AU | 2        | 0.79%   |
| de_CH | 2        | 0.79%   |
| zh_CN | 1        | 0.39%   |
| sv_SE | 1        | 0.39%   |
| sr_RS | 1        | 0.39%   |
| sl_SI | 1        | 0.39%   |
| ru_RU | 1        | 0.39%   |
| pt_PT | 1        | 0.39%   |
| nb_NO | 1        | 0.39%   |
| he_IL | 1        | 0.39%   |
| fr_CH | 1        | 0.39%   |
| es_PE | 1        | 0.39%   |
| es_PA | 1        | 0.39%   |
| es_GT | 1        | 0.39%   |
| es_CL | 1        | 0.39%   |
| es_AR | 1        | 0.39%   |
| en_SG | 1        | 0.39%   |
| en_NZ | 1        | 0.39%   |
| el_GR | 1        | 0.39%   |
| cs_CZ | 1        | 0.39%   |
| C     | 1        | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 144      | 56.47%  |
| EFI  | 111      | 43.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 239      | 94.09%  |
| Zfs     | 5        | 1.97%   |
| Overlay | 4        | 1.57%   |
| Btrfs   | 3        | 1.18%   |
| Xfs     | 1        | 0.39%   |
| Ext3    | 1        | 0.39%   |
| Ext2    | 1        | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 238      | 93.7%   |
| GPT     | 12       | 4.72%   |
| MBR     | 4        | 1.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 244      | 95.69%  |
| Yes       | 11       | 4.31%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 225      | 88.58%  |
| Yes       | 29       | 11.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUSTek Computer            | 70       | 27.56%  |
| Gigabyte Technology         | 43       | 16.93%  |
| Dell                        | 27       | 10.63%  |
| MSI                         | 24       | 9.45%   |
| Hewlett-Packard             | 23       | 9.06%   |
| ASRock                      | 23       | 9.06%   |
| Lenovo                      | 14       | 5.51%   |
| Intel                       | 6        | 2.36%   |
| Biostar                     | 5        | 1.97%   |
| Fujitsu                     | 3        | 1.18%   |
| Foxconn                     | 3        | 1.18%   |
| Pegatron                    | 2        | 0.79%   |
| Unknown                     | 2        | 0.79%   |
| Sapphire Technology Limited | 1        | 0.39%   |
| Positivo                    | 1        | 0.39%   |
| NCR                         | 1        | 0.39%   |
| Medion                      | 1        | 0.39%   |
| LattePanda                  | 1        | 0.39%   |
| eMachines                   | 1        | 0.39%   |
| ECS                         | 1        | 0.39%   |
| Alienware                   | 1        | 0.39%   |
| Acer                        | 1        | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| ASUS All Series                          | 7        | 2.76%   |
| Dell OptiPlex 990                        | 5        | 1.97%   |
| Dell OptiPlex 790                        | 4        | 1.57%   |
| Dell OptiPlex 7010                       | 4        | 1.57%   |
| Gigabyte A320M-S2H                       | 3        | 1.18%   |
| ASUS P8Z77-V LX                          | 3        | 1.18%   |
| ASUS M5A78L-M/USB3                       | 3        | 1.18%   |
| Unknown                                  | 3        | 1.18%   |
| MSI MS-7C02                              | 2        | 0.79%   |
| MSI MS-7B89                              | 2        | 0.79%   |
| MSI MS-7817                              | 2        | 0.79%   |
| Intel DQ77MK-R01                         | 2        | 0.79%   |
| HP ProDesk 600 G1 SFF                    | 2        | 0.79%   |
| HP Compaq Pro 6300 SFF                   | 2        | 0.79%   |
| Gigabyte G31M-ES2L                       | 2        | 0.79%   |
| Gigabyte B75M-D3H                        | 2        | 0.79%   |
| Gigabyte 970A-DS3P                       | 2        | 0.79%   |
| Dell XPS420                              | 2        | 0.79%   |
| ASUS PRIME B450M-GAMING/BR               | 2        | 0.79%   |
| ASUS P5G41T-M LX3                        | 2        | 0.79%   |
| ASUS M5A97 LE R2.0                       | 2        | 0.79%   |
| ASUS A68HM-PLUS                          | 2        | 0.79%   |
| Sapphire Limited PURE PLATINUM 970A-PLUS | 1        | 0.39%   |
| Positivo POS-PIH81DI                     | 1        | 0.39%   |
| Pegatron NY537AA-ABA 300-1025            | 1        | 0.39%   |
| Pegatron NE502AV-ABA a6750t              | 1        | 0.39%   |
| NCR xxxx-xxxx-xxxx                       | 1        | 0.39%   |
| MSI WE136AA-UUZ p6337ch                  | 1        | 0.39%   |
| MSI Pro 3515 Series                      | 1        | 0.39%   |
| MSI p6745nl                              | 1        | 0.39%   |
| MSI MS-7D18                              | 1        | 0.39%   |
| MSI MS-7C94                              | 1        | 0.39%   |
| MSI MS-7C79                              | 1        | 0.39%   |
| MSI MS-7C37                              | 1        | 0.39%   |
| MSI MS-7B85                              | 1        | 0.39%   |
| MSI MS-7B84                              | 1        | 0.39%   |
| MSI MS-7B53                              | 1        | 0.39%   |
| MSI MS-7A71                              | 1        | 0.39%   |
| MSI MS-7A33                              | 1        | 0.39%   |
| MSI MS-7914                              | 1        | 0.39%   |
| MSI MS-7816                              | 1        | 0.39%   |
| MSI MS-7798                              | 1        | 0.39%   |
| MSI MS-7750                              | 1        | 0.39%   |
| MSI MS-7693                              | 1        | 0.39%   |
| MSI MS-7592                              | 1        | 0.39%   |
| Medion MS-7707                           | 1        | 0.39%   |
| Lenovo ThinkStation P510 30B4S0F616      | 1        | 0.39%   |
| Lenovo ThinkCentre M93p 10AAS1DP00       | 1        | 0.39%   |
| Lenovo ThinkCentre M93p 10AAS0ME00       | 1        | 0.39%   |
| Lenovo ThinkCentre M83 MT-M 10AJ-0003MB  | 1        | 0.39%   |
| Lenovo ThinkCentre M81 0385AW6           | 1        | 0.39%   |
| Lenovo ThinkCentre M78 10BTA00ELM        | 1        | 0.39%   |
| Lenovo ThinkCentre M73 10B7S02L00        | 1        | 0.39%   |
| Lenovo ThinkCentre M58 3231W2Y           | 1        | 0.39%   |
| Lenovo SHARKBAY SDK0E50510 WIN           | 1        | 0.39%   |
| Lenovo Legion C530-19ICB 90JX0040GE      | 1        | 0.39%   |
| Lenovo IdeaCentre K330                   | 1        | 0.39%   |
| Lenovo IdeaCentre 510S-08IKL 90GB004RUS  | 1        | 0.39%   |
| Lenovo IdeaCentre 310S-08ASR 90G9002VUK  | 1        | 0.39%   |
| LattePanda Alpha                         | 1        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 20       | 7.87%   |
| ASUS PRIME             | 10       | 3.94%   |
| Lenovo ThinkCentre     | 7        | 2.76%   |
| ASUS ROG               | 7        | 2.76%   |
| ASUS All               | 7        | 2.76%   |
| HP Compaq              | 6        | 2.36%   |
| ASUS M5A78L-M          | 5        | 1.97%   |
| ASUS P8Z77-V           | 4        | 1.57%   |
| ASUS M5A97             | 4        | 1.57%   |
| Lenovo IdeaCentre      | 3        | 1.18%   |
| HP EliteDesk           | 3        | 1.18%   |
| Gigabyte B450          | 3        | 1.18%   |
| Gigabyte A320M-S2H     | 3        | 1.18%   |
| ASUS P8H61-M           | 3        | 1.18%   |
| Unknown                | 3        | 1.18%   |
| MSI MS-7C02            | 2        | 0.79%   |
| MSI MS-7B89            | 2        | 0.79%   |
| MSI MS-7817            | 2        | 0.79%   |
| Intel DQ77MK-R01       | 2        | 0.79%   |
| HP t620                | 2        | 0.79%   |
| HP ProDesk             | 2        | 0.79%   |
| Gigabyte X570          | 2        | 0.79%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.79%   |
| Gigabyte G31M-ES2L     | 2        | 0.79%   |
| Gigabyte B75M-D3H      | 2        | 0.79%   |
| Gigabyte B550M         | 2        | 0.79%   |
| Gigabyte B450M         | 2        | 0.79%   |
| Gigabyte 970A-DS3P     | 2        | 0.79%   |
| Fujitsu ESPRIMO        | 2        | 0.79%   |
| Dell XPS420            | 2        | 0.79%   |
| Dell XPS               | 2        | 0.79%   |
| Dell Precision         | 2        | 0.79%   |
| ASUS P5K               | 2        | 0.79%   |
| ASUS P5G41T-M          | 2        | 0.79%   |
| ASUS M5A78L            | 2        | 0.79%   |
| ASUS A68HM-PLUS        | 2        | 0.79%   |
| ASRock B450M           | 2        | 0.79%   |
| ASRock B450            | 2        | 0.79%   |
| Sapphire Limited PURE  | 1        | 0.39%   |
| Positivo POS-PIH81DI   | 1        | 0.39%   |
| Pegatron NY537AA-ABA   | 1        | 0.39%   |
| Pegatron NE502AV-ABA   | 1        | 0.39%   |
| NCR xxxx-xxxx-xxxx     | 1        | 0.39%   |
| MSI WE136AA-UUZ        | 1        | 0.39%   |
| MSI Pro                | 1        | 0.39%   |
| MSI p6745nl            | 1        | 0.39%   |
| MSI MS-7D18            | 1        | 0.39%   |
| MSI MS-7C94            | 1        | 0.39%   |
| MSI MS-7C79            | 1        | 0.39%   |
| MSI MS-7C37            | 1        | 0.39%   |
| MSI MS-7B85            | 1        | 0.39%   |
| MSI MS-7B84            | 1        | 0.39%   |
| MSI MS-7B53            | 1        | 0.39%   |
| MSI MS-7A71            | 1        | 0.39%   |
| MSI MS-7A33            | 1        | 0.39%   |
| MSI MS-7914            | 1        | 0.39%   |
| MSI MS-7816            | 1        | 0.39%   |
| MSI MS-7798            | 1        | 0.39%   |
| MSI MS-7750            | 1        | 0.39%   |
| MSI MS-7693            | 1        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 30       | 11.81%  |
| 2021 | 29       | 11.42%  |
| 2018 | 27       | 10.63%  |
| 2014 | 22       | 8.66%   |
| 2013 | 21       | 8.27%   |
| 2012 | 21       | 8.27%   |
| 2015 | 20       | 7.87%   |
| 2010 | 19       | 7.48%   |
| 2019 | 16       | 6.3%    |
| 2011 | 15       | 5.91%   |
| 2016 | 11       | 4.33%   |
| 2009 | 8        | 3.15%   |
| 2008 | 6        | 2.36%   |
| 2017 | 4        | 1.57%   |
| 2007 | 3        | 1.18%   |
| 2006 | 2        | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 254      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 238      | 92.97%  |
| Enabled  | 18       | 7.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 254      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 71       | 27.52%  |
| 16.01-24.0  | 65       | 25.19%  |
| 4.01-8.0    | 37       | 14.34%  |
| 3.01-4.0    | 35       | 13.57%  |
| 32.01-64.0  | 34       | 13.18%  |
| 1.01-2.0    | 8        | 3.1%    |
| 24.01-32.0  | 4        | 1.55%   |
| 64.01-256.0 | 4        | 1.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 120      | 45.8%   |
| 2.01-3.0   | 78       | 29.77%  |
| 3.01-4.0   | 30       | 11.45%  |
| 4.01-8.0   | 29       | 11.07%  |
| 8.01-16.0  | 2        | 0.76%   |
| 0.51-1.0   | 2        | 0.76%   |
| 16.01-24.0 | 1        | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 100      | 38.76%  |
| 2      | 81       | 31.4%   |
| 3      | 32       | 12.4%   |
| 4      | 18       | 6.98%   |
| 5      | 12       | 4.65%   |
| 6      | 9        | 3.49%   |
| 8      | 3        | 1.16%   |
| 0      | 2        | 0.78%   |
| 7      | 1        | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 133      | 52.16%  |
| No        | 122      | 47.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 254      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 131      | 51.57%  |
| Yes       | 123      | 48.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 178      | 69.26%  |
| Yes       | 79       | 30.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 69       | 27.17%  |
| Germany      | 28       | 11.02%  |
| UK           | 26       | 10.24%  |
| Brazil       | 17       | 6.69%   |
| Canada       | 10       | 3.94%   |
| Netherlands  | 9        | 3.54%   |
| Italy        | 8        | 3.15%   |
| India        | 8        | 3.15%   |
| Spain        | 6        | 2.36%   |
| Poland       | 5        | 1.97%   |
| Mexico       | 5        | 1.97%   |
| Hungary      | 5        | 1.97%   |
| Switzerland  | 4        | 1.57%   |
| Norway       | 4        | 1.57%   |
| Denmark      | 4        | 1.57%   |
| Turkey       | 3        | 1.18%   |
| South Africa | 3        | 1.18%   |
| Australia    | 3        | 1.18%   |
| Sweden       | 2        | 0.79%   |
| Serbia       | 2        | 0.79%   |
| Russia       | 2        | 0.79%   |
| Malaysia     | 2        | 0.79%   |
| France       | 2        | 0.79%   |
| El Salvador  | 2        | 0.79%   |
| Chile        | 2        | 0.79%   |
| Belgium      | 2        | 0.79%   |
| Austria      | 2        | 0.79%   |
| Argentina    | 2        | 0.79%   |
| Vietnam      | 1        | 0.39%   |
| Taiwan       | 1        | 0.39%   |
| Slovenia     | 1        | 0.39%   |
| Romania      | 1        | 0.39%   |
| Portugal     | 1        | 0.39%   |
| Peru         | 1        | 0.39%   |
| Panama       | 1        | 0.39%   |
| New Zealand  | 1        | 0.39%   |
| Mozambique   | 1        | 0.39%   |
| Jamaica      | 1        | 0.39%   |
| Israel       | 1        | 0.39%   |
| Indonesia    | 1        | 0.39%   |
| Guatemala    | 1        | 0.39%   |
| Czechia      | 1        | 0.39%   |
| Croatia      | 1        | 0.39%   |
| China        | 1        | 0.39%   |
| Algeria      | 1        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Munich                 | 3        | 1.18%   |
| Berlin                 | 3        | 1.18%   |
| Vienna                 | 2        | 0.78%   |
| Vadodara               | 2        | 0.78%   |
| Stoke-on-Trent         | 2        | 0.78%   |
| Rio de Janeiro         | 2        | 0.78%   |
| Milan                  | 2        | 0.78%   |
| Mentor                 | 2        | 0.78%   |
| Melbourne              | 2        | 0.78%   |
| Livingston             | 2        | 0.78%   |
| Kuala Lumpur           | 2        | 0.78%   |
| Hamburg                | 2        | 0.78%   |
| Drummondville          | 2        | 0.78%   |
| Contagem               | 2        | 0.78%   |
| Cape Town              | 2        | 0.78%   |
| Bryan                  | 2        | 0.78%   |
| Ankara                 | 2        | 0.78%   |
| Zurich                 | 1        | 0.39%   |
| Zephyrhills            | 1        | 0.39%   |
| Zagreb                 | 1        | 0.39%   |
| Xalapa                 | 1        | 0.39%   |
| Wysoka Glogowska       | 1        | 0.39%   |
| Wylie                  | 1        | 0.39%   |
| Winnipeg               | 1        | 0.39%   |
| Williamsburg           | 1        | 0.39%   |
| Wijnegem               | 1        | 0.39%   |
| Wigan                  | 1        | 0.39%   |
| West Valley City       | 1        | 0.39%   |
| Warsaw                 | 1        | 0.39%   |
| Warrenton              | 1        | 0.39%   |
| Warner Robins          | 1        | 0.39%   |
| Vouvry                 | 1        | 0.39%   |
| Victoria               | 1        | 0.39%   |
| Vespasiano             | 1        | 0.39%   |
| Vechelde               | 1        | 0.39%   |
| Vancouver              | 1        | 0.39%   |
| Twickenham             | 1        | 0.39%   |
| Tucson                 | 1        | 0.39%   |
| Trujillo               | 1        | 0.39%   |
| Titusville             | 1        | 0.39%   |
| The Hague              | 1        | 0.39%   |
| Thame                  | 1        | 0.39%   |
| Tel Aviv               | 1        | 0.39%   |
| Taby                   | 1        | 0.39%   |
| São Bernardo do Campo | 1        | 0.39%   |
| Szombathely            | 1        | 0.39%   |
| Szigetvar              | 1        | 0.39%   |
| Suldalsosen            | 1        | 0.39%   |
| Stuttgart              | 1        | 0.39%   |
| Stockholm              | 1        | 0.39%   |
| Spring Hill            | 1        | 0.39%   |
| Spartanburg            | 1        | 0.39%   |
| Spanish Town           | 1        | 0.39%   |
| Southend-on-Sea        | 1        | 0.39%   |
| Solingen               | 1        | 0.39%   |
| Skien                  | 1        | 0.39%   |
| Sherbrooke             | 1        | 0.39%   |
| Shenzhen               | 1        | 0.39%   |
| Sheffield              | 1        | 0.39%   |
| Sertaozinho            | 1        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 89       | 135    | 18.94%  |
| WDC                       | 85       | 111    | 18.09%  |
| Samsung Electronics       | 65       | 93     | 13.83%  |
| Sandisk                   | 34       | 41     | 7.23%   |
| Toshiba                   | 28       | 32     | 5.96%   |
| Kingston                  | 27       | 32     | 5.74%   |
| Hitachi                   | 25       | 30     | 5.32%   |
| Crucial                   | 10       | 15     | 2.13%   |
| Phison                    | 9        | 10     | 1.91%   |
| Silicon Motion            | 8        | 12     | 1.7%    |
| Unknown                   | 7        | 12     | 1.49%   |
| China                     | 7        | 7      | 1.49%   |
| HGST                      | 6        | 8      | 1.28%   |
| A-DATA Technology         | 6        | 7      | 1.28%   |
| PNY                       | 4        | 5      | 0.85%   |
| Lexar                     | 4        | 4      | 0.85%   |
| JMicron                   | 4        | 5      | 0.85%   |
| Intel                     | 4        | 4      | 0.85%   |
| Hewlett-Packard           | 4        | 5      | 0.85%   |
| SK Hynix                  | 3        | 4      | 0.64%   |
| MAXTOR                    | 3        | 3      | 0.64%   |
| Gigabyte Technology       | 3        | 3      | 0.64%   |
| XPG                       | 2        | 2      | 0.43%   |
| Super Talent              | 2        | 2      | 0.43%   |
| OCZ                       | 2        | 2      | 0.43%   |
| Micron/Crucial Technology | 2        | 2      | 0.43%   |
| Micron Technology         | 2        | 2      | 0.43%   |
| XrayDisk                  | 1        | 1      | 0.21%   |
| Verbatim                  | 1        | 1      | 0.21%   |
| Team                      | 1        | 2      | 0.21%   |
| SuperSSpeed               | 1        | 2      | 0.21%   |
| SPCC                      | 1        | 1      | 0.21%   |
| Smartbuy                  | 1        | 1      | 0.21%   |
| SABRENT                   | 1        | 1      | 0.21%   |
| Realtek Semiconductor     | 1        | 1      | 0.21%   |
| Patriot                   | 1        | 1      | 0.21%   |
| OWC                       | 1        | 1      | 0.21%   |
| ORTIAL                    | 1        | 1      | 0.21%   |
| Netac                     | 1        | 1      | 0.21%   |
| MyDigitalSSD              | 1        | 1      | 0.21%   |
| Mushkin                   | 1        | 1      | 0.21%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.21%   |
| KingSpec                  | 1        | 2      | 0.21%   |
| KingFast                  | 1        | 1      | 0.21%   |
| Intenso                   | 1        | 1      | 0.21%   |
| INNOVATION IT             | 1        | 1      | 0.21%   |
| HS-SSD-C100               | 1        | 1      | 0.21%   |
| GOODRAM                   | 1        | 1      | 0.21%   |
| Dogfish                   | 1        | 1      | 0.21%   |
| Corsair                   | 1        | 1      | 0.21%   |
| Config                    | 1        | 1      | 0.21%   |
| Apacer                    | 1        | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 11       | 1.99%   |
| Kingston SA400S37240G 240GB SSD      | 9        | 1.63%   |
| Samsung SSD 860 EVO 500GB            | 8        | 1.45%   |
| WDC WD10EZEX-08WN4A0 1TB             | 7        | 1.27%   |
| Samsung NVMe SSD Drive 500GB         | 7        | 1.27%   |
| Seagate ST3500418AS 500GB            | 6        | 1.09%   |
| Toshiba HDWD110 1TB                  | 5        | 0.91%   |
| Seagate ST2000DM001-9YN164 2TB       | 5        | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB       | 5        | 0.91%   |
| Samsung SSD 840 EVO 250GB            | 5        | 0.91%   |
| Samsung NVMe SSD Drive 1TB           | 5        | 0.91%   |
| Samsung HD103UJ 1TB                  | 5        | 0.91%   |
| Phison NVMe SSD Drive 1TB            | 5        | 0.91%   |
| Kingston SV300S37A120G 120GB SSD     | 5        | 0.91%   |
| Seagate ST2000DM008-2FR102 2TB       | 4        | 0.72%   |
| Seagate ST1000DM003-1CH162 1TB       | 4        | 0.72%   |
| Seagate Expansion 1TB                | 4        | 0.72%   |
| Samsung SSD 870 EVO 1TB              | 4        | 0.72%   |
| Samsung SSD 850 EVO 250GB            | 4        | 0.72%   |
| Kingston SA400S37120G 120GB SSD      | 4        | 0.72%   |
| Crucial CT500MX500SSD1 500GB         | 4        | 0.72%   |
| WDC WD1600AAJS-75M0A0 160GB          | 3        | 0.54%   |
| WDC WD10EZEX-60M2NA0 1TB             | 3        | 0.54%   |
| Unknown SD/MMC/MS PRO 394GB          | 3        | 0.54%   |
| Toshiba DT01ACA200 2TB               | 3        | 0.54%   |
| Toshiba DT01ACA100 1TB               | 3        | 0.54%   |
| Silicon Motion NVMe SSD Drive 128GB  | 3        | 0.54%   |
| Seagate ST4000DM000-1F2168 4TB       | 3        | 0.54%   |
| Seagate ST3500413AS 500GB            | 3        | 0.54%   |
| Seagate ST2000DM001-1CH164 2TB       | 3        | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB       | 3        | 0.54%   |
| SanDisk SDSSDA240G 240GB             | 3        | 0.54%   |
| Sandisk NVMe SSD Drive 500GB         | 3        | 0.54%   |
| Samsung SSD 870 QVO 1TB              | 3        | 0.54%   |
| Samsung SSD 860 EVO 250GB            | 3        | 0.54%   |
| Samsung SSD 850 EVO 500GB            | 3        | 0.54%   |
| Samsung HD103SJ 1TB                  | 3        | 0.54%   |
| PNY CS900 240GB SSD                  | 3        | 0.54%   |
| Phison NVMe SSD Drive 512GB          | 3        | 0.54%   |
| WDC WDS250G2B0A-00SM50 250GB SSD     | 2        | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2        | 0.36%   |
| WDC WD800JD-75MSA3 80GB              | 2        | 0.36%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 2        | 0.36%   |
| WDC WD1200BEVS-22UST0 120GB          | 2        | 0.36%   |
| WDC WD10EZEX-60WN4A0 1TB             | 2        | 0.36%   |
| WDC WD10EZEX-08M2NA0 1TB             | 2        | 0.36%   |
| WDC WD10EZEX-00BN5A0 1TB             | 2        | 0.36%   |
| WDC WD10EARS-00Y5B1 1TB              | 2        | 0.36%   |
| WDC WD10EADX-22TDHB0 1TB             | 2        | 0.36%   |
| Unknown SD/MMC 16GB                  | 2        | 0.36%   |
| Unknown M.S./M.S.Pro/HG 16GB         | 2        | 0.36%   |
| Toshiba TR200 240GB SSD              | 2        | 0.36%   |
| Toshiba MQ01ABD032 320GB             | 2        | 0.36%   |
| Toshiba DT01ACA050 500GB             | 2        | 0.36%   |
| Silicon Motion NVMe SSD Drive 512GB  | 2        | 0.36%   |
| Silicon Motion NVMe SSD Drive 1024GB | 2        | 0.36%   |
| Seagate ST8000DM004-2CX188 8TB       | 2        | 0.36%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2        | 0.36%   |
| Seagate ST4000DM004-2CV104 4TB       | 2        | 0.36%   |
| Seagate ST3320820AS 320GB            | 2        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 89       | 130    | 35.6%   |
| WDC                 | 84       | 106    | 33.6%   |
| Toshiba             | 25       | 29     | 10%     |
| Hitachi             | 25       | 30     | 10%     |
| Samsung Electronics | 13       | 19     | 5.2%    |
| HGST                | 6        | 8      | 2.4%    |
| Unknown             | 3        | 5      | 1.2%    |
| MAXTOR              | 3        | 3      | 1.2%    |
| Hewlett-Packard     | 2        | 3      | 0.8%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 41       | 51     | 24.26%  |
| SanDisk             | 27       | 33     | 15.98%  |
| Kingston            | 25       | 30     | 14.79%  |
| Crucial             | 10       | 15     | 5.92%   |
| China               | 7        | 7      | 4.14%   |
| A-DATA Technology   | 6        | 7      | 3.55%   |
| WDC                 | 5        | 5      | 2.96%   |
| PNY                 | 4        | 5      | 2.37%   |
| Lexar               | 4        | 4      | 2.37%   |
| Intel               | 3        | 3      | 1.78%   |
| Gigabyte Technology | 3        | 3      | 1.78%   |
| Toshiba             | 2        | 2      | 1.18%   |
| Super Talent        | 2        | 2      | 1.18%   |
| Seagate             | 2        | 2      | 1.18%   |
| OCZ                 | 2        | 2      | 1.18%   |
| Micron Technology   | 2        | 2      | 1.18%   |
| Hewlett-Packard     | 2        | 2      | 1.18%   |
| Verbatim            | 1        | 1      | 0.59%   |
| Team                | 1        | 2      | 0.59%   |
| SuperSSpeed         | 1        | 2      | 0.59%   |
| SPCC                | 1        | 1      | 0.59%   |
| Smartbuy            | 1        | 1      | 0.59%   |
| SK Hynix            | 1        | 1      | 0.59%   |
| PHISON              | 1        | 1      | 0.59%   |
| Patriot             | 1        | 1      | 0.59%   |
| OWC                 | 1        | 1      | 0.59%   |
| ORTIAL              | 1        | 1      | 0.59%   |
| Netac               | 1        | 1      | 0.59%   |
| MyDigitalSSD        | 1        | 1      | 0.59%   |
| Mushkin             | 1        | 1      | 0.59%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.59%   |
| KingSpec            | 1        | 2      | 0.59%   |
| JMicron             | 1        | 1      | 0.59%   |
| Intenso             | 1        | 1      | 0.59%   |
| INNOVATION IT       | 1        | 1      | 0.59%   |
| GOODRAM             | 1        | 1      | 0.59%   |
| Dogfish             | 1        | 1      | 0.59%   |
| Corsair             | 1        | 1      | 0.59%   |
| Apacer              | 1        | 1      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 184      | 333    | 47.92%  |
| SSD     | 138      | 200    | 35.94%  |
| NVMe    | 50       | 65     | 13.02%  |
| Unknown | 12       | 18     | 3.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 244      | 520    | 77.71%  |
| NVMe | 50       | 64     | 15.92%  |
| SAS  | 20       | 32     | 6.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 186      | 283    | 52.1%   |
| 0.51-1.0   | 108      | 162    | 30.25%  |
| 1.01-2.0   | 38       | 51     | 10.64%  |
| 3.01-4.0   | 14       | 20     | 3.92%   |
| 4.01-10.0  | 7        | 10     | 1.96%   |
| 2.01-3.0   | 4        | 7      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 61       | 23.74%  |
| 251-500        | 55       | 21.4%   |
| 501-1000       | 44       | 17.12%  |
| 1001-2000      | 26       | 10.12%  |
| 51-100         | 23       | 8.95%   |
| More than 3000 | 21       | 8.17%   |
| 2001-3000      | 11       | 4.28%   |
| 21-50          | 6        | 2.33%   |
| 1-20           | 6        | 2.33%   |
| Unknown        | 4        | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 94       | 35.88%  |
| 21-50          | 59       | 22.52%  |
| 51-100         | 29       | 11.07%  |
| 101-250        | 23       | 8.78%   |
| 501-1000       | 16       | 6.11%   |
| More than 3000 | 14       | 5.34%   |
| 1001-2000      | 11       | 4.2%    |
| 251-500        | 10       | 3.82%   |
| Unknown        | 4        | 1.53%   |
| 2001-3000      | 2        | 0.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD3200AAKS-22B3A0 320GB    | 1        | 1      | 11.11%  |
| WDC WD10EZEX-21M2NA0 1TB       | 1        | 2      | 11.11%  |
| Toshiba MK3265GSX 320GB        | 1        | 1      | 11.11%  |
| Seagate ST9500420AS 500GB      | 1        | 1      | 11.11%  |
| Seagate ST4000DM004-2CV104 4TB | 1        | 1      | 11.11%  |
| Seagate ST3500514NS 500GB      | 1        | 1      | 11.11%  |
| Seagate ST3320620AS 320GB      | 1        | 1      | 11.11%  |
| Seagate ST2000DM001-9YN164 2TB | 1        | 1      | 11.11%  |
| Seagate ST2000DL003-9VT166 2TB | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 6      | 62.5%   |
| WDC     | 2        | 3      | 25%     |
| Toshiba | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 6      | 62.5%   |
| WDC     | 2        | 3      | 25%     |
| Toshiba | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 10     | 100%    |

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
| Detected | 238      | 569    | 90.49%  |
| Works    | 18       | 37     | 6.84%   |
| Malfunc  | 7        | 10     | 2.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 166      | 50.3%   |
| AMD                          | 82       | 24.85%  |
| Samsung Electronics          | 18       | 5.45%   |
| Phison Electronics           | 9        | 2.73%   |
| ASMedia Technology           | 9        | 2.73%   |
| Silicon Motion               | 8        | 2.42%   |
| Sandisk                      | 7        | 2.12%   |
| Marvell Technology Group     | 5        | 1.52%   |
| Nvidia                       | 4        | 1.21%   |
| JMicron Technology           | 4        | 1.21%   |
| VIA Technologies             | 3        | 0.91%   |
| Silicon Image                | 3        | 0.91%   |
| SK Hynix                     | 2        | 0.61%   |
| Micron/Crucial Technology    | 2        | 0.61%   |
| Kingston Technology Company  | 2        | 0.61%   |
| Broadcom / LSI               | 2        | 0.61%   |
| ADATA Technology             | 2        | 0.61%   |
| Toshiba America Info Systems | 1        | 0.3%    |
| Realtek Semiconductor        | 1        | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 40       | 9.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 26       | 6.07%   |
| AMD 400 Series Chipset SATA Controller                                                  | 22       | 5.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 19       | 4.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 18       | 4.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 17       | 3.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 17       | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 3.74%   |
| Intel SATA Controller [RAID mode]                                                       | 15       | 3.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14       | 3.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 2.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 2.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 1.87%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 1.64%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 1.64%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 6        | 1.4%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5        | 1.17%   |
| AMD FCH SATA Controller D                                                               | 5        | 1.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.93%   |
| Phison E12 NVMe Controller                                                              | 4        | 0.93%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 4        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 4        | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.93%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 0.7%    |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.7%    |
| Nvidia MCP61 IDE                                                                        | 3        | 0.7%    |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 3        | 0.7%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 0.7%    |
| AMD FCH IDE Controller                                                                  | 3        | 0.7%    |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 2        | 0.47%   |
| Silicon Motion Non-Volatile memory controller                                           | 2        | 0.47%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 2        | 0.47%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.47%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.47%   |
| Sandisk Non-Volatile memory controller                                                  | 2        | 0.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.47%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.47%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.47%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.47%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.47%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.47%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.47%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.47%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.47%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.47%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.47%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.47%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 0.47%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.47%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 0.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.47%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 0.47%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.47%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.47%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 193      | 56.1%   |
| IDE  | 74       | 21.51%  |
| NVMe | 50       | 14.53%  |
| RAID | 24       | 6.98%   |
| SCSI | 2        | 0.58%   |
| SAS  | 1        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 169      | 66.54%  |
| AMD    | 85       | 33.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 10       | 3.94%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 9        | 3.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 2.36%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5        | 1.97%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 1.97%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 5        | 1.97%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 4        | 1.57%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 1.57%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 4        | 1.57%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 1.57%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 1.57%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 1.57%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 4        | 1.57%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 1.18%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 3        | 1.18%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 1.18%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 3        | 1.18%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 1.18%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 3        | 1.18%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 3        | 1.18%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 1.18%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 1.18%   |
| AMD FX-6300 Six-Core Processor              | 3        | 1.18%   |
| AMD FX-6100 Six-Core Processor              | 3        | 1.18%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2        | 0.79%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 2        | 0.79%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.79%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.79%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.79%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 2        | 0.79%   |
| Intel Core i5-3340 CPU @ 3.10GHz            | 2        | 0.79%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 0.79%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 0.79%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.79%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.79%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 0.79%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 0.79%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 0.79%   |
| AMD FX-8320E Eight-Core Processor           | 2        | 0.79%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 0.79%   |
| AMD FX-4100 Quad-Core Processor             | 2        | 0.79%   |
| AMD Athlon II X2 245 Processor              | 2        | 0.79%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.39%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 1        | 0.39%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 0.39%   |
| Intel Xeon CPU E5430 @ 2.66GHz              | 1        | 0.39%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 0.39%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.39%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz         | 1        | 0.39%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.39%   |
| Intel Xeon CPU E31225 @ 3.10GHz             | 1        | 0.39%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz         | 1        | 0.39%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.39%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz      | 1        | 0.39%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.39%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.39%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 0.39%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.39%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1        | 0.39%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 55       | 21.65%  |
| Intel Core i7           | 32       | 12.6%   |
| Intel Core i3           | 26       | 10.24%  |
| AMD Ryzen 5             | 22       | 8.66%   |
| AMD FX                  | 17       | 6.69%   |
| Intel Xeon              | 10       | 3.94%   |
| Intel Core 2 Quad       | 10       | 3.94%   |
| Intel Pentium Dual-Core | 8        | 3.15%   |
| AMD Ryzen 7             | 8        | 3.15%   |
| AMD Ryzen 3             | 8        | 3.15%   |
| Intel Core 2 Duo        | 7        | 2.76%   |
| Intel Celeron           | 5        | 1.97%   |
| Intel Pentium Dual      | 4        | 1.57%   |
| AMD Ryzen 9             | 3        | 1.18%   |
| AMD Phenom II X4        | 3        | 1.18%   |
| AMD Athlon II X2        | 3        | 1.18%   |
| AMD A6                  | 3        | 1.18%   |
| Other                   | 2        | 0.79%   |
| Intel Pentium Gold      | 2        | 0.79%   |
| Intel Pentium           | 2        | 0.79%   |
| Intel Core i9           | 2        | 0.79%   |
| AMD GX                  | 2        | 0.79%   |
| AMD Athlon X4           | 2        | 0.79%   |
| AMD Athlon II X3        | 2        | 0.79%   |
| AMD A8                  | 2        | 0.79%   |
| AMD A10                 | 2        | 0.79%   |
| Intel Pentium D         | 1        | 0.39%   |
| Intel Pentium 4         | 1        | 0.39%   |
| Intel Core m3           | 1        | 0.39%   |
| Intel Core 2            | 1        | 0.39%   |
| AMD Ryzen 5 PRO         | 1        | 0.39%   |
| AMD Phenom II X6        | 1        | 0.39%   |
| AMD Opteron             | 1        | 0.39%   |
| AMD E1                  | 1        | 0.39%   |
| AMD Athlon II X4        | 1        | 0.39%   |
| AMD Athlon 64 X2        | 1        | 0.39%   |
| AMD Athlon 64           | 1        | 0.39%   |
| AMD A4                  | 1        | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 117      | 46.06%  |
| 2      | 71       | 27.95%  |
| 6      | 34       | 13.39%  |
| 8      | 13       | 5.12%   |
| 3      | 9        | 3.54%   |
| 1      | 5        | 1.97%   |
| 12     | 2        | 0.79%   |
| 10     | 2        | 0.79%   |
| 16     | 1        | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 254      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 131      | 51.57%  |
| 1      | 123      | 48.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 254      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 30       | 11.72%  |
| 0x206a7    | 24       | 9.38%   |
| 0x306a9    | 23       | 8.98%   |
| 0x1067a    | 19       | 7.42%   |
| 0x08701021 | 15       | 5.86%   |
| Unknown    | 15       | 5.86%   |
| 0x506e3    | 12       | 4.69%   |
| 0x06000852 | 12       | 4.69%   |
| 0x6fb      | 8        | 3.13%   |
| 0x06001119 | 6        | 2.34%   |
| 0x0600063e | 6        | 2.34%   |
| 0xa0655    | 5        | 1.95%   |
| 0x906ea    | 5        | 1.95%   |
| 0x0800820d | 5        | 1.95%   |
| 0x6fd      | 4        | 1.56%   |
| 0x08701013 | 4        | 1.56%   |
| 0x010000c8 | 4        | 1.56%   |
| 0xa0653    | 3        | 1.17%   |
| 0x906eb    | 3        | 1.17%   |
| 0x906e9    | 3        | 1.17%   |
| 0x0a201016 | 3        | 1.17%   |
| 0x08108109 | 3        | 1.17%   |
| 0x08001137 | 3        | 1.17%   |
| 0xa0671    | 2        | 0.78%   |
| 0x30678    | 2        | 0.78%   |
| 0x20652    | 2        | 0.78%   |
| 0x10676    | 2        | 0.78%   |
| 0x08101016 | 2        | 0.78%   |
| 0x0700010f | 2        | 0.78%   |
| 0x06003106 | 2        | 0.78%   |
| 0x010000dc | 2        | 0.78%   |
| 0x010000c7 | 2        | 0.78%   |
| 0xf47      | 1        | 0.39%   |
| 0xf43      | 1        | 0.39%   |
| 0x906ed    | 1        | 0.39%   |
| 0x906ec    | 1        | 0.39%   |
| 0x806e9    | 1        | 0.39%   |
| 0x706a1    | 1        | 0.39%   |
| 0x6f6      | 1        | 0.39%   |
| 0x406f1    | 1        | 0.39%   |
| 0x40651    | 1        | 0.39%   |
| 0x306f2    | 1        | 0.39%   |
| 0x306e4    | 1        | 0.39%   |
| 0x206d7    | 1        | 0.39%   |
| 0x206c2    | 1        | 0.39%   |
| 0x20655    | 1        | 0.39%   |
| 0x106e5    | 1        | 0.39%   |
| 0x106a4    | 1        | 0.39%   |
| 0x0a201009 | 1        | 0.39%   |
| 0x08600106 | 1        | 0.39%   |
| 0x0810100b | 1        | 0.39%   |
| 0x08001138 | 1        | 0.39%   |
| 0x07030106 | 1        | 0.39%   |
| 0x06006705 | 1        | 0.39%   |
| 0x010000db | 1        | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 35       | 13.78%  |
| SandyBridge   | 26       | 10.24%  |
| IvyBridge     | 24       | 9.45%   |
| Penryn        | 21       | 8.27%   |
| Zen 2         | 20       | 7.87%   |
| Piledriver    | 18       | 7.09%   |
| KabyLake      | 16       | 6.3%    |
| Core          | 13       | 5.12%   |
| Skylake       | 12       | 4.72%   |
| K10           | 10       | 3.94%   |
| Zen+          | 9        | 3.54%   |
| Zen           | 9        | 3.54%   |
| CometLake     | 8        | 3.15%   |
| Bulldozer     | 6        | 2.36%   |
| Zen 3         | 4        | 1.57%   |
| Westmere      | 4        | 1.57%   |
| Jaguar        | 3        | 1.18%   |
| Steamroller   | 2        | 0.79%   |
| Silvermont    | 2        | 0.79%   |
| NetBurst      | 2        | 0.79%   |
| Nehalem       | 2        | 0.79%   |
| K8 Hammer     | 2        | 0.79%   |
| Icelake       | 2        | 0.79%   |
| Puma          | 1        | 0.39%   |
| Goldmont plus | 1        | 0.39%   |
| Excavator     | 1        | 0.39%   |
| Broadwell     | 1        | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 117      | 42.86%  |
| AMD              | 79       | 28.94%  |
| Intel            | 76       | 27.84%  |
| VIA Technologies | 1        | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 17       | 6.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 15       | 5.45%   |
| Nvidia GK208B [GeForce GT 710]                                                | 11       | 4%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 9        | 3.27%   |
| Nvidia GF119 [GeForce GT 610]                                                 | 7        | 2.55%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 6        | 2.18%   |
| Nvidia GK208B [GeForce GT 730]                                                | 6        | 2.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 6        | 2.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 6        | 2.18%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 6        | 2.18%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                            | 5        | 1.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 4        | 1.45%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 4        | 1.45%   |
| Intel HD Graphics 530                                                         | 4        | 1.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 4        | 1.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 4        | 1.45%   |
| AMD RS780L [Radeon 3000]                                                      | 4        | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 4        | 1.45%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 4        | 1.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 3        | 1.09%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 3        | 1.09%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                         | 3        | 1.09%   |
| Nvidia GT218 [GeForce 210]                                                    | 3        | 1.09%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 3        | 1.09%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 3        | 1.09%   |
| Nvidia GF108 [GeForce GT 730]                                                 | 3        | 1.09%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 3        | 1.09%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                | 3        | 1.09%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 2        | 0.73%   |
| Nvidia TU116 [GeForce GTX 1660]                                               | 2        | 0.73%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                         | 2        | 0.73%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 2        | 0.73%   |
| Nvidia TU104 [GeForce RTX 2060]                                               | 2        | 0.73%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 2        | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 2        | 0.73%   |
| Nvidia GK106 [GeForce GTX 660]                                                | 2        | 0.73%   |
| Nvidia GK104 [GeForce GTX 760]                                                | 2        | 0.73%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 2        | 0.73%   |
| Nvidia GA106 [GeForce RTX 3060]                                               | 2        | 0.73%   |
| Nvidia G96C [GeForce GT 120]                                                  | 2        | 0.73%   |
| Intel HD Graphics 630                                                         | 2        | 0.73%   |
| Intel Core Processor Integrated Graphics Controller                           | 2        | 0.73%   |
| Intel 82Q35 Express Integrated Graphics Controller                            | 2        | 0.73%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 2        | 0.73%   |
| AMD Turks XT [Radeon HD 6670/7670]                                            | 2        | 0.73%   |
| AMD Trinity 2 [Radeon HD 7540D]                                               | 2        | 0.73%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                             | 2        | 0.73%   |
| AMD RV710 [Radeon HD 4350/4550]                                               | 2        | 0.73%   |
| AMD RS880 [Radeon HD 4250]                                                    | 2        | 0.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2        | 0.73%   |
| AMD Park [Mobility Radeon HD 5430]                                            | 2        | 0.73%   |
| AMD Kaveri [Radeon R7 Graphics]                                               | 2        | 0.73%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                            | 2        | 0.73%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]           | 2        | 0.73%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.36%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1        | 0.36%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 1        | 0.36%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                        | 1        | 0.36%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 1        | 0.36%   |
| Nvidia GT215 [GeForce GT 320]                                                 | 1        | 0.36%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 111      | 43.36%  |
| 1 x AMD        | 73       | 28.52%  |
| 1 x Intel      | 62       | 24.22%  |
| Intel + Nvidia | 4        | 1.56%   |
| 2 x AMD        | 2        | 0.78%   |
| Intel + AMD    | 2        | 0.78%   |
| 1 x VIA        | 1        | 0.39%   |
| AMD + Nvidia   | 1        | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 159      | 62.6%   |
| Proprietary | 81       | 31.89%  |
| Unknown     | 14       | 5.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 93       | 36.33%  |
| 1.01-2.0   | 48       | 18.75%  |
| 0.51-1.0   | 36       | 14.06%  |
| 0.01-0.5   | 24       | 9.38%   |
| 3.01-4.0   | 18       | 7.03%   |
| 7.01-8.0   | 17       | 6.64%   |
| 5.01-6.0   | 10       | 3.91%   |
| 2.01-3.0   | 5        | 1.95%   |
| 8.01-16.0  | 4        | 1.56%   |
| 16.01-24.0 | 1        | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 43       | 16.8%   |
| Goldstar             | 22       | 8.59%   |
| Acer                 | 22       | 8.59%   |
| Hewlett-Packard      | 20       | 7.81%   |
| Dell                 | 20       | 7.81%   |
| AOC                  | 17       | 6.64%   |
| BenQ                 | 14       | 5.47%   |
| Philips              | 12       | 4.69%   |
| LG Electronics       | 8        | 3.13%   |
| Ancor Communications | 7        | 2.73%   |
| ViewSonic            | 5        | 1.95%   |
| Unknown              | 5        | 1.95%   |
| Iiyama               | 5        | 1.95%   |
| Lenovo               | 4        | 1.56%   |
| HPN                  | 4        | 1.56%   |
| Unknown              | 4        | 1.56%   |
| Vizio                | 3        | 1.17%   |
| Vestel               | 3        | 1.17%   |
| Sony                 | 3        | 1.17%   |
| Sceptre Tech         | 3        | 1.17%   |
| Microstep            | 3        | 1.17%   |
| Toshiba              | 2        | 0.78%   |
| Panasonic            | 2        | 0.78%   |
| NEC Computers        | 2        | 0.78%   |
| Fujitsu Siemens      | 2        | 0.78%   |
| AUS                  | 2        | 0.78%   |
| Xiaomi               | 1        | 0.39%   |
| Vestel Elektronik    | 1        | 0.39%   |
| Sharp                | 1        | 0.39%   |
| Seiki                | 1        | 0.39%   |
| Sceptre              | 1        | 0.39%   |
| Sanyo                | 1        | 0.39%   |
| PKB                  | 1        | 0.39%   |
| ONN                  | 1        | 0.39%   |
| OEM                  | 1        | 0.39%   |
| Medion               | 1        | 0.39%   |
| Lenovo Group Limited | 1        | 0.39%   |
| KTC                  | 1        | 0.39%   |
| HCL                  | 1        | 0.39%   |
| Gigabyte Technology  | 1        | 0.39%   |
| GDH                  | 1        | 0.39%   |
| Gateway              | 1        | 0.39%   |
| CVT                  | 1        | 0.39%   |
| Belinea              | 1        | 0.39%   |
| Arnos Instruments    | 1        | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 4        | 1.48%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 3        | 1.11%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                     | 3        | 1.11%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch               | 2        | 0.74%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 2        | 0.74%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch    | 2        | 0.74%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 2        | 0.74%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2        | 0.74%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                      | 2        | 0.74%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 480x270mm 21.7-inch   | 2        | 0.74%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                        | 2        | 0.74%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                      | 1        | 0.37%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1        | 0.37%   |
| ViewSonic VX3258 series VSCA037 1920x1080 700x390mm 31.5-inch           | 1        | 0.37%   |
| ViewSonic VG510s VSCCA18 1024x768 304x228mm 15.0-inch                   | 1        | 0.37%   |
| ViewSonic LCD Monitor VP3268-4K 1920x1080                               | 1        | 0.37%   |
| ViewSonic LCD Monitor VA2718-FHD 1920x1080                              | 1        | 0.37%   |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                           | 1        | 0.37%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 1        | 0.37%   |
| Unknown LCD Monitor SAMSUNG 2464x900                                    | 1        | 0.37%   |
| Unknown LCD Monitor RTK                                                 | 1        | 0.37%   |
| Unknown LCD Monitor OPD PX227H-HDMI1 4160x1440                          | 1        | 0.37%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                               | 1        | 0.37%   |
| Unknown LCD Monitor Kingston Technology 40'TV 1834x1031                 | 1        | 0.37%   |
| Unknown LCD Monitor GKK MONITOR 1920x1080                               | 1        | 0.37%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                        | 1        | 0.37%   |
| Toshiba LCD Monitor TV                                                  | 1        | 0.37%   |
| Sony TV SNYEE01 1920x1080 1600x900mm 72.3-inch                          | 1        | 0.37%   |
| Sony TV *00 SNYA405 3840x2160 952x535mm 43.0-inch                       | 1        | 0.37%   |
| Sony LCD Monitor TV 3840x1080                                           | 1        | 0.37%   |
| Sony AVAMP SNY9301 1280x720 708x398mm 32.0-inch                         | 1        | 0.37%   |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                       | 1        | 0.37%   |
| Seiki SE19HT01 SEK0C76 1360x768 410x230mm 18.5-inch                     | 1        | 0.37%   |
| Sceptre Tech Sceptre M25 SPT09FB 1920x1080 540x300mm 24.3-inch          | 1        | 0.37%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1        | 0.37%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch           | 1        | 0.37%   |
| Sceptre LCD Monitor M24 3840x1080                                       | 1        | 0.37%   |
| Sceptre LCD Monitor M24                                                 | 1        | 0.37%   |
| Sanyo LED MONITOR SAN952D 1920x1080 443x249mm 20.0-inch                 | 1        | 0.37%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch       | 1        | 0.37%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch       | 1        | 0.37%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch       | 1        | 0.37%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch       | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0626 1920x1080                        | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0604 1920x1080                        | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch    | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM049A 1920x1080 477x268mm 21.5-inch    | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch    | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0373 1680x1050 459x296mm 21.5-inch    | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0350 1440x900 428x255mm 19.6-inch     | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch    | 1        | 0.37%   |
| Samsung Electronics SMS27A550H SAM07CB 1680x1050 600x340mm 27.2-inch    | 1        | 0.37%   |
| Samsung Electronics SMS22A200/460 SAM0832 1920x1080 477x268mm 21.5-inch | 1        | 0.37%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1        | 0.37%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch       | 1        | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.37%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch       | 1        | 0.37%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch       | 1        | 0.37%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 116      | 45.85%  |
| 3840x2160 (4K)     | 22       | 8.7%    |
| Unknown            | 19       | 7.51%   |
| 1680x1050 (WSXGA+) | 15       | 5.93%   |
| 3840x1080          | 11       | 4.35%   |
| 1366x768 (WXGA)    | 9        | 3.56%   |
| 2560x1440 (QHD)    | 7        | 2.77%   |
| 1600x900 (HD+)     | 7        | 2.77%   |
| 1440x900 (WXGA+)   | 7        | 2.77%   |
| 1280x1024 (SXGA)   | 7        | 2.77%   |
| 1920x1200 (WUXGA)  | 5        | 1.98%   |
| 1360x768           | 5        | 1.98%   |
| 3440x1440          | 4        | 1.58%   |
| 5760x2160          | 2        | 0.79%   |
| 1024x768 (XGA)     | 2        | 0.79%   |
| 4480x1440          | 1        | 0.4%    |
| 4160x1440          | 1        | 0.4%    |
| 3780x2160          | 1        | 0.4%    |
| 3600x1080          | 1        | 0.4%    |
| 3360x1080          | 1        | 0.4%    |
| 3360x1050          | 1        | 0.4%    |
| 3200x1200          | 1        | 0.4%    |
| 3120x1050          | 1        | 0.4%    |
| 2944x1080          | 1        | 0.4%    |
| 2560x1080          | 1        | 0.4%    |
| 2464x900           | 1        | 0.4%    |
| 1920x540           | 1        | 0.4%    |
| 1834x1031          | 1        | 0.4%    |
| 1600x1200          | 1        | 0.4%    |
| 1280x720 (HD)      | 1        | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 66       | 26.94%  |
| 24      | 29       | 11.84%  |
| 21      | 24       | 9.8%    |
| 27      | 23       | 9.39%   |
| 23      | 15       | 6.12%   |
| 22      | 15       | 6.12%   |
| 31      | 13       | 5.31%   |
| 18      | 10       | 4.08%   |
| 19      | 9        | 3.67%   |
| 20      | 8        | 3.27%   |
| 17      | 6        | 2.45%   |
| 84      | 4        | 1.63%   |
| 34      | 4        | 1.63%   |
| 72      | 2        | 0.82%   |
| 48      | 2        | 0.82%   |
| 41      | 2        | 0.82%   |
| 32      | 2        | 0.82%   |
| 15      | 2        | 0.82%   |
| 74      | 1        | 0.41%   |
| 52      | 1        | 0.41%   |
| 46      | 1        | 0.41%   |
| 43      | 1        | 0.41%   |
| 40      | 1        | 0.41%   |
| 36      | 1        | 0.41%   |
| 33      | 1        | 0.41%   |
| 26      | 1        | 0.41%   |
| 25      | 1        | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 66       | 28.09%  |
| 501-600     | 61       | 25.96%  |
| 401-500     | 59       | 25.11%  |
| 601-700     | 17       | 7.23%   |
| 701-800     | 8        | 3.4%    |
| 1501-2000   | 7        | 2.98%   |
| 301-350     | 6        | 2.55%   |
| 1001-1500   | 4        | 1.7%    |
| 351-400     | 3        | 1.28%   |
| 901-1000    | 3        | 1.28%   |
| 801-900     | 1        | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 119      | 52.42%  |
| Unknown | 64       | 28.19%  |
| 16/10   | 30       | 13.22%  |
| 5/4     | 6        | 2.64%   |
| 21/9    | 4        | 1.76%   |
| 4/3     | 3        | 1.32%   |
| 32/9    | 1        | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 68       | 28.1%   |
| Unknown        | 66       | 27.27%  |
| 301-350        | 23       | 9.5%    |
| 151-200        | 22       | 9.09%   |
| 351-500        | 20       | 8.26%   |
| 251-300        | 12       | 4.96%   |
| 141-150        | 12       | 4.96%   |
| More than 1000 | 9        | 3.72%   |
| 501-1000       | 7        | 2.89%   |
| 101-110        | 2        | 0.83%   |
| 121-130        | 1        | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 113      | 49.13%  |
| Unknown | 66       | 28.7%   |
| 101-120 | 31       | 13.48%  |
| 121-160 | 10       | 4.35%   |
| 1-50    | 9        | 3.91%   |
| 161-240 | 1        | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 195      | 76.17%  |
| 2     | 43       | 16.8%   |
| 0     | 17       | 6.64%   |
| 3     | 1        | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 159      | 42.51%  |
| Intel                           | 99       | 26.47%  |
| Qualcomm Atheros                | 30       | 8.02%   |
| Ralink Technology               | 17       | 4.55%   |
| TP-Link                         | 13       | 3.48%   |
| Ralink                          | 9        | 2.41%   |
| Broadcom                        | 6        | 1.6%    |
| Nvidia                          | 4        | 1.07%   |
| Samsung Electronics             | 3        | 0.8%    |
| Microsoft                       | 3        | 0.8%    |
| Edimax Technology               | 3        | 0.8%    |
| D-Link System                   | 3        | 0.8%    |
| Xiaomi                          | 2        | 0.53%   |
| Qualcomm Atheros Communications | 2        | 0.53%   |
| NetGear                         | 2        | 0.53%   |
| Motorola PCS                    | 2        | 0.53%   |
| Huawei Technologies             | 2        | 0.53%   |
| Broadcom Limited                | 2        | 0.53%   |
| Panasonic (Matsushita)          | 1        | 0.27%   |
| OPPO Electronics                | 1        | 0.27%   |
| MediaTek                        | 1        | 0.27%   |
| Marvell Technology Group        | 1        | 0.27%   |
| Linksys                         | 1        | 0.27%   |
| Lenovo                          | 1        | 0.27%   |
| Google                          | 1        | 0.27%   |
| Gemtek                          | 1        | 0.27%   |
| Exar                            | 1        | 0.27%   |
| DisplayLink                     | 1        | 0.27%   |
| D-Link                          | 1        | 0.27%   |
| Arduino SA                      | 1        | 0.27%   |
| ADMtek                          | 1        | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 128      | 30.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 23       | 5.45%   |
| Intel Wi-Fi 6 AX200                                                  | 12       | 2.84%   |
| Ralink MT7601U Wireless Adapter                                      | 10       | 2.37%   |
| Realtek RTL8125 2.5GbE Controller                                    | 9        | 2.13%   |
| Intel I211 Gigabit Network Connection                                | 9        | 2.13%   |
| Intel Ethernet Connection I217-LM                                    | 8        | 1.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7        | 1.66%   |
| Intel Ethernet Connection (2) I219-V                                 | 7        | 1.66%   |
| Realtek 802.11ac NIC                                                 | 6        | 1.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 5        | 1.18%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 5        | 1.18%   |
| Intel Ethernet Connection (2) I218-V                                 | 5        | 1.18%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 4        | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4        | 0.95%   |
| Intel Ethernet Controller I225-V                                     | 4        | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 4        | 0.95%   |
| Intel 82579V Gigabit Network Connection                              | 4        | 0.95%   |
| TP-Link TL WN823N RTL8192EU                                          | 3        | 0.71%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 3        | 0.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 3        | 0.71%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 3        | 0.71%   |
| Ralink RT5370 Wireless Adapter                                       | 3        | 0.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3        | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 3        | 0.71%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 3        | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 3        | 0.71%   |
| Nvidia MCP61 Ethernet                                                | 3        | 0.71%   |
| Intel Wireless 7265                                                  | 3        | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 3        | 0.71%   |
| Intel Ethernet Connection I217-V                                     | 3        | 0.71%   |
| Intel Ethernet Connection (7) I219-V                                 | 3        | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 3        | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 2        | 0.47%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 2        | 0.47%   |
| TP-Link 802.11ac WLAN Adapter                                        | 2        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 2        | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2        | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2        | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2        | 0.47%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                            | 2        | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 0.47%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 2        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 2        | 0.47%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 2        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 2        | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 2        | 0.47%   |
| Intel Wireless-AC 9260                                               | 2        | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                                | 2        | 0.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2        | 0.47%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2        | 0.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2        | 0.47%   |
| Intel 82574L Gigabit Network Connection                              | 2        | 0.47%   |
| Intel 82566DM-2 Gigabit Network Connection                           | 2        | 0.47%   |
| Intel 82566DC-2 Gigabit Network Connection                           | 2        | 0.47%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT2870]             | 2        | 0.47%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 2        | 0.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                     | 2        | 0.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 2        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 32       | 23.02%  |
| Realtek Semiconductor           | 31       | 22.3%   |
| Ralink Technology               | 17       | 12.23%  |
| Qualcomm Atheros                | 15       | 10.79%  |
| TP-Link                         | 13       | 9.35%   |
| Ralink                          | 9        | 6.47%   |
| Microsoft                       | 3        | 2.16%   |
| Edimax Technology               | 3        | 2.16%   |
| Broadcom                        | 3        | 2.16%   |
| Qualcomm Atheros Communications | 2        | 1.44%   |
| NetGear                         | 2        | 1.44%   |
| D-Link System                   | 2        | 1.44%   |
| Broadcom Limited                | 2        | 1.44%   |
| Panasonic (Matsushita)          | 1        | 0.72%   |
| Linksys                         | 1        | 0.72%   |
| Gemtek                          | 1        | 0.72%   |
| D-Link                          | 1        | 0.72%   |
| ADMtek                          | 1        | 0.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 12       | 8.51%   |
| Ralink MT7601U Wireless Adapter                                                         | 10       | 7.09%   |
| Realtek 802.11ac NIC                                                                    | 6        | 4.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 5        | 3.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                            | 4        | 2.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 4        | 2.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 4        | 2.84%   |
| TP-Link TL WN823N RTL8192EU                                                             | 3        | 2.13%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                         | 3        | 2.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                   | 3        | 2.13%   |
| Ralink RT5370 Wireless Adapter                                                          | 3        | 2.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                   | 3        | 2.13%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                        | 3        | 2.13%   |
| Intel Wireless 7265                                                                     | 3        | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                  | 3        | 2.13%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                  | 2        | 1.42%   |
| TP-Link 802.11ac WLAN Adapter                                                           | 2        | 1.42%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                | 2        | 1.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 2        | 1.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                              | 2        | 1.42%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                               | 2        | 1.42%   |
| Qualcomm Atheros AR9271 802.11n                                                         | 2        | 1.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                        | 2        | 1.42%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                        | 2        | 1.42%   |
| Intel Wireless-AC 9260                                                                  | 2        | 1.42%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                         | 2        | 1.42%   |
| Intel Comet Lake PCH CNVi WiFi                                                          | 2        | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                                         | 2        | 1.42%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT2870]                                | 2        | 1.42%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]                    | 2        | 1.42%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 2        | 1.42%   |
| TP-Link Archer T4U ver.3                                                                | 1        | 0.71%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                              | 1        | 0.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                | 1        | 0.71%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 0.71%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                 | 1        | 0.71%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                              | 1        | 0.71%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                  | 1        | 0.71%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                  | 1        | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                                              | 1        | 0.71%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                                | 1        | 0.71%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 0.71%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                               | 1        | 0.71%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                   | 1        | 0.71%   |
| Ralink RT5592 PCIe Wireless Network Adapter                                             | 1        | 0.71%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                    | 1        | 0.71%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                    | 1        | 0.71%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                               | 1        | 0.71%   |
| Ralink RT2600 802.11 MIMO                                                               | 1        | 0.71%   |
| Ralink RT2561/RT61 802.11g PCI                                                          | 1        | 0.71%   |
| Ralink RT2500 Wireless 802.11bg                                                         | 1        | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 1        | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 1        | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 1        | 0.71%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]          | 1        | 0.71%   |
| Panasonic (Matsushita) N5HBZ0000055 802.11abgn Wireless Adapter [Atheros AR7010+AR9280] | 1        | 0.71%   |
| NetGear WNDA3100v2 802.11abgn [Broadcom BCM4323]                                        | 1        | 0.71%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                             | 1        | 0.71%   |
| Microsoft XBOX ACC                                                                      | 1        | 0.71%   |
| Microsoft Xbox 360 Wireless Adapter                                                     | 1        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 151      | 56.13%  |
| Intel                    | 81       | 30.11%  |
| Qualcomm Atheros         | 16       | 5.95%   |
| Nvidia                   | 4        | 1.49%   |
| Samsung Electronics      | 3        | 1.12%   |
| Broadcom                 | 3        | 1.12%   |
| Xiaomi                   | 2        | 0.74%   |
| Huawei Technologies      | 2        | 0.74%   |
| OPPO Electronics         | 1        | 0.37%   |
| Motorola PCS             | 1        | 0.37%   |
| MediaTek                 | 1        | 0.37%   |
| Marvell Technology Group | 1        | 0.37%   |
| Google                   | 1        | 0.37%   |
| DisplayLink              | 1        | 0.37%   |
| D-Link System            | 1        | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 128      | 46.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 23       | 8.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 3.25%   |
| Intel I211 Gigabit Network Connection                             | 9        | 3.25%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 2.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 2.53%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 1.81%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.81%   |
| Intel Ethernet Controller I225-V                                  | 4        | 1.44%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 1.08%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.08%   |
| Intel Ethernet Connection I217-V                                  | 3        | 1.08%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.72%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2        | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.72%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.72%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 2        | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.36%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.36%   |
| OPPO RMX2027                                                      | 1        | 0.36%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.36%   |
| Motorola PCS moto g(6) plus                                       | 1        | 0.36%   |
| MediaTek REVVL V+ 5G                                              | 1        | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.36%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.36%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.36%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.36%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.36%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.36%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.36%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.36%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.36%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 0.36%   |
| Huawei E353/E3131                                                 | 1        | 0.36%   |
| Huawei DRA-L01                                                    | 1        | 0.36%   |
| Google Nexus 4/5/7/10 (tether)                                    | 1        | 0.36%   |
| DisplayLink USB3.0 Dual Video Dock                                | 1        | 0.36%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.36%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 0.36%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 254      | 66.49%  |
| WiFi     | 124      | 32.46%  |
| Modem    | 2        | 0.52%   |
| Unknown  | 2        | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 246      | 69.69%  |
| WiFi     | 106      | 30.03%  |
| Unknown  | 1        | 0.28%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 169      | 66.54%  |
| 2     | 78       | 30.71%  |
| 3     | 4        | 1.57%   |
| 0     | 2        | 0.79%   |
| 5     | 1        | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 178      | 68.99%  |
| Yes  | 80       | 31.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 25       | 30.49%  |
| Cambridge Silicon Radio         | 23       | 28.05%  |
| Realtek Semiconductor           | 12       | 14.63%  |
| Broadcom                        | 7        | 8.54%   |
| ASUSTek Computer                | 4        | 4.88%   |
| Qualcomm Atheros Communications | 3        | 3.66%   |
| Dell                            | 2        | 2.44%   |
| National Semiconductor          | 1        | 1.22%   |
| Micro Star International        | 1        | 1.22%   |
| Lite-On Technology              | 1        | 1.22%   |
| IMC Networks                    | 1        | 1.22%   |
| Foxconn / Hon Hai               | 1        | 1.22%   |
| Belkin Components               | 1        | 1.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 23       | 28.05%  |
| Realtek Bluetooth Radio                               | 11       | 13.41%  |
| Intel AX200 Bluetooth                                 | 7        | 8.54%   |
| Intel Bluetooth wireless interface                    | 6        | 7.32%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 4.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3        | 3.66%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 3.66%   |
| Intel Bluetooth Device                                | 2        | 2.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 2.44%   |
| Intel AX210 Bluetooth                                 | 2        | 2.44%   |
| Dell BT Mini-Receiver                                 | 2        | 2.44%   |
| ASUS Qualcomm Bluetooth 4.1                           | 2        | 2.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 2.44%   |
| Realtek RTL8821A Bluetooth                            | 1        | 1.22%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 1.22%   |
| Qualcomm Atheros Bluetooth                            | 1        | 1.22%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 1.22%   |
| National Bluetooth Dongle                             | 1        | 1.22%   |
| Micro Star International Bluetooth Device             | 1        | 1.22%   |
| Lite-On Bluetooth Device                              | 1        | 1.22%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.22%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 1.22%   |
| Broadcom HP Bluetooth Module                          | 1        | 1.22%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 1.22%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 1.22%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 1.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 162      | 37.07%  |
| AMD                                  | 113      | 25.86%  |
| Nvidia                               | 111      | 25.4%   |
| C-Media Electronics                  | 7        | 1.6%    |
| Creative Labs                        | 6        | 1.37%   |
| Razer USA                            | 4        | 0.92%   |
| JMTek                                | 4        | 0.92%   |
| Texas Instruments                    | 3        | 0.69%   |
| Logitech                             | 3        | 0.69%   |
| Plantronics                          | 2        | 0.46%   |
| GN Netcom                            | 2        | 0.46%   |
| XMOS                                 | 1        | 0.23%   |
| VIA Technologies                     | 1        | 0.23%   |
| Valve Software                       | 1        | 0.23%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.23%   |
| Tenx Technology                      | 1        | 0.23%   |
| SteelSeries ApS                      | 1        | 0.23%   |
| SAVITECH                             | 1        | 0.23%   |
| ROCCAT                               | 1        | 0.23%   |
| Numark                               | 1        | 0.23%   |
| Micronas                             | 1        | 0.23%   |
| LucidSound                           | 1        | 0.23%   |
| Klipsch Audio                        | 1        | 0.23%   |
| Kingston Technology                  | 1        | 0.23%   |
| Insignia (Best Buy)                  | 1        | 0.23%   |
| iConnectivity                        | 1        | 0.23%   |
| GEMBIRD                              | 1        | 0.23%   |
| Focusrite-Novation                   | 1        | 0.23%   |
| FIFINE Microphones                   | 1        | 0.23%   |
| Corsair                              | 1        | 0.23%   |
| ASUSTek Computer                     | 1        | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 29       | 5.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 27       | 5.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 27       | 5.39%   |
| AMD Starship/Matisse HD Audio Controller                                          | 22       | 4.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 21       | 4.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 20       | 3.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 18       | 3.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 16       | 3.19%   |
| AMD FCH Azalia Controller                                                         | 12       | 2.4%    |
| Intel Cannon Lake PCH cAVS                                                        | 10       | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10       | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 9        | 1.8%    |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 9        | 1.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 9        | 1.8%    |
| Nvidia TU116 High Definition Audio Controller                                     | 8        | 1.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 8        | 1.6%    |
| Nvidia GF108 High Definition Audio Controller                                     | 8        | 1.6%    |
| Nvidia TU106 High Definition Audio Controller                                     | 7        | 1.4%    |
| Nvidia GP106 High Definition Audio Controller                                     | 7        | 1.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7        | 1.4%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 7        | 1.4%    |
| Nvidia High Definition Audio Controller                                           | 6        | 1.2%    |
| Nvidia GF119 HDMI Audio Controller                                                | 6        | 1.2%    |
| Intel 200 Series PCH HD Audio                                                     | 6        | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 6        | 1.2%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 6        | 1.2%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 6        | 1.2%    |
| Nvidia GM204 High Definition Audio Controller                                     | 5        | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 1%      |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 0.8%    |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 0.8%    |
| Nvidia GK104 HDMI Audio Controller                                                | 4        | 0.8%    |
| JMTek USB PnP Audio Device                                                        | 4        | 0.8%    |
| Intel Comet Lake PCH cAVS                                                         | 4        | 0.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 4        | 0.8%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 0.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4        | 0.8%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 4        | 0.8%    |
| AMD Navi 10 HDMI Audio                                                            | 4        | 0.8%    |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 0.6%    |
| Nvidia MCP61 High Definition Audio                                                | 3        | 0.6%    |
| AMD Trinity HDMI Audio Controller                                                 | 3        | 0.6%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 0.6%    |
| AMD Kabini HDMI/DP Audio                                                          | 3        | 0.6%    |
| Razer USA Kraken Tournament Edition                                               | 2        | 0.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 0.4%    |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 0.4%    |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 0.4%    |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.4%    |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 0.4%    |
| Nvidia Audio device                                                               | 2        | 0.4%    |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 0.4%    |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 0.4%    |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 0.4%    |
| Intel Audio device                                                                | 2        | 0.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.4%    |
| GN Netcom Jabra Link 370                                                          | 2        | 0.4%    |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 2        | 0.4%    |
| C-Media Electronics USB Advanced Audio Device                                     | 2        | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 7        | 22.58%  |
| Corsair             | 6        | 19.35%  |
| Samsung Electronics | 3        | 9.68%   |
| Kingston            | 3        | 9.68%   |
| Crucial             | 3        | 9.68%   |
| SK Hynix            | 2        | 6.45%   |
| Ramaxel Technology  | 2        | 6.45%   |
| G.Skill             | 2        | 6.45%   |
| Team                | 1        | 3.23%   |
| Micron Technology   | 1        | 3.23%   |
| F7852C80            | 1        | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s    | 1        | 2.94%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                  | 1        | 2.94%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                       | 1        | 2.94%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s               | 1        | 2.94%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1        | 2.94%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1        | 2.94%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s               | 1        | 2.94%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s                | 1        | 2.94%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s               | 1        | 2.94%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s         | 1        | 2.94%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s        | 1        | 2.94%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1        | 2.94%   |
| SK Hynix RAM HMT325U6EFR8C-PB 2048MB DIMM DDR3 1600MT/s    | 1        | 2.94%   |
| Samsung RAM Module 8192MB DIMM DDR4 2133MT/s               | 1        | 2.94%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s        | 1        | 2.94%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s        | 1        | 2.94%   |
| Ramaxel RAM RMUA5110ME78HAF-2666 8192MB DIMM DDR4 2667MT/s | 1        | 2.94%   |
| Ramaxel RAM RMR5030ED58E8W1600 2048MB DIMM DDR3 1600MT/s   | 1        | 2.94%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s        | 1        | 2.94%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1867MT/s     | 1        | 2.94%   |
| Kingston RAM 99U5471-012.A00LF 4096MB DIMM DDR3 1600MT/s   | 1        | 2.94%   |
| Kingston RAM 99U5403-065.A00LF 4GB DIMM DDR3 1600MT/s      | 1        | 2.94%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 2933MT/s        | 1        | 2.94%   |
| G.Skill RAM F4-2666C15-8GVR 8GB DIMM DDR4 2800MT/s         | 1        | 2.94%   |
| F7852C80 RAM F641GU67F1600G0000 8GB DIMM DDR3 1333MT/s     | 1        | 2.94%   |
| Crucial RAM CT51264BA160BJ.C8F 4096MB DIMM DDR3 1600MT/s   | 1        | 2.94%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s      | 1        | 2.94%   |
| Crucial RAM BL8G32C16U4R.M8FE 8GB DIMM DDR4 2133MT/s       | 1        | 2.94%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s     | 1        | 2.94%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s       | 1        | 2.94%   |
| Corsair RAM CMK32GX4M4D3600C18 8192MB DIMM DDR4 3600MT/s   | 1        | 2.94%   |
| Corsair RAM CMH32GX4M2D3600C18 16384MB DIMM DDR4 2133MT/s  | 1        | 2.94%   |
| Corsair RAM CMD16GX4M2A2666C15 8192MB DIMM DDR4 2667MT/s   | 1        | 2.94%   |
| Corsair RAM CMD16GX3M2A18 8192MB DIMM DDR3 1333MT/s        | 1        | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 12       | 44.44%  |
| DDR4    | 11       | 40.74%  |
| Unknown | 3        | 11.11%  |
| DDR     | 1        | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 27       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 14       | 50%     |
| 4096  | 9        | 32.14%  |
| 16384 | 2        | 7.14%   |
| 2048  | 2        | 7.14%   |
| 32768 | 1        | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 8        | 28.57%  |
| 2133  | 5        | 17.86%  |
| 1333  | 5        | 17.86%  |
| 2667  | 3        | 10.71%  |
| 3200  | 2        | 7.14%   |
| 3600  | 1        | 3.57%   |
| 2933  | 1        | 3.57%   |
| 2800  | 1        | 3.57%   |
| 2400  | 1        | 3.57%   |
| 1867  | 1        | 3.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 4        | 36.36%  |
| Hewlett-Packard     | 3        | 27.27%  |
| Samsung Electronics | 2        | 18.18%  |
| Seiko Epson         | 1        | 9.09%   |
| Brother Industries  | 1        | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson XP-202 203 206 Series | 1        | 9.09%   |
| Samsung SCX-483x 5x3x Series      | 1        | 9.09%   |
| Samsung SCX-3400 Series           | 1        | 9.09%   |
| HP OfficeJet 4650 series          | 1        | 9.09%   |
| HP LaserJet Professional P1102w   | 1        | 9.09%   |
| HP DeskJet 2700 series            | 1        | 9.09%   |
| Canon TS3100 series               | 1        | 9.09%   |
| Canon TR4500 series               | 1        | 9.09%   |
| Canon PIXMA MG2500 Series         | 1        | 9.09%   |
| Canon LiDE 400                    | 1        | 9.09%   |
| Brother DCP-L2540DW               | 1        | 9.09%   |

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
| Logitech                      | 10       | 23.81%  |
| Microsoft                     | 4        | 9.52%   |
| Microdia                      | 4        | 9.52%   |
| Generalplus Technology        | 3        | 7.14%   |
| ARC International             | 3        | 7.14%   |
| Sunplus Innovation Technology | 2        | 4.76%   |
| Samsung Electronics           | 2        | 4.76%   |
| Razer USA                     | 2        | 4.76%   |
| Teslong Camera                | 1        | 2.38%   |
| Sonix Technology              | 1        | 2.38%   |
| SHENZHEN Fullhan              | 1        | 2.38%   |
| Realtek Semiconductor         | 1        | 2.38%   |
| Jieli Technology              | 1        | 2.38%   |
| Guillemot                     | 1        | 2.38%   |
| Genesys Logic                 | 1        | 2.38%   |
| Creative Technology           | 1        | 2.38%   |
| Chicony Electronics           | 1        | 2.38%   |
| Arkmicro Technologies         | 1        | 2.38%   |
| Apple                         | 1        | 2.38%   |
| Alcor Micro                   | 1        | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000            | 3        | 7.14%   |
| Logitech Webcam C270                 | 3        | 7.14%   |
| Generalplus GENERAL WEBCAM           | 3        | 7.14%   |
| ARC International Camera             | 3        | 7.14%   |
| Samsung Galaxy A5 (MTP)              | 2        | 4.76%   |
| Razer USA Gaming Webcam [Kiyo]       | 2        | 4.76%   |
| Logitech HD Pro Webcam C920          | 2        | 4.76%   |
| Teslong Camera Teslong Camera        | 1        | 2.38%   |
| Sunplus HD 720P webcam               | 1        | 2.38%   |
| Sunplus FHD Camera Microphone        | 1        | 2.38%   |
| Sonix USB 2.0 Camera                 | 1        | 2.38%   |
| SHENZHEN Fullhan webcam              | 1        | 2.38%   |
| Realtek WEB CAMERA M9 Pro            | 1        | 2.38%   |
| Microsoft Microsoft?� LifeCam Cinema | 1        | 2.38%   |
| Microdia Webcam Vitade AF            | 1        | 2.38%   |
| Microdia PC Camera (SN9C110)         | 1        | 2.38%   |
| Microdia Integrated Camera           | 1        | 2.38%   |
| Microdia Camera                      | 1        | 2.38%   |
| Logitech Webcam C260                 | 1        | 2.38%   |
| Logitech Portable Webcam C905        | 1        | 2.38%   |
| Logitech HD Webcam C910              | 1        | 2.38%   |
| Logitech HD Webcam C615              | 1        | 2.38%   |
| Logitech C922 Pro Stream Webcam      | 1        | 2.38%   |
| Jieli USB PHY 2.0                    | 1        | 2.38%   |
| Guillemot Hercules HD Sunset         | 1        | 2.38%   |
| Genesys Logic USB2.0 UVC PC Camera   | 1        | 2.38%   |
| Creative Live! Cam Chat HD [VF0700]  | 1        | 2.38%   |
| Chicony CNF8050 Webcam               | 1        | 2.38%   |
| Arkmicro USB2.0 PC CAMERA            | 1        | 2.38%   |
| Apple iPhone 5/5C/5S/6/SE            | 1        | 2.38%   |
| Alcor Micro USB Audio Device         | 1        | 2.38%   |

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
| 0     | 210      | 82.03%  |
| 1     | 41       | 16.02%  |
| 2     | 5        | 1.95%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 21       | 43.75%  |
| Graphics card            | 19       | 39.58%  |
| Unassigned class         | 2        | 4.17%   |
| Chipcard                 | 2        | 4.17%   |
| Storage/ide              | 1        | 2.08%   |
| Sound                    | 1        | 2.08%   |
| Communication controller | 1        | 2.08%   |
| Camera                   | 1        | 2.08%   |

