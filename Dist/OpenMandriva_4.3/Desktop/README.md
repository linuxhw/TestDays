OpenMandriva 4.3 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

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

Total: 2311

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [2815b29936](https://linux-hardware.org/?probe=2815b29936) | Dec 25, 2024 |
| Intel         | H61                         | [3b41c83d54](https://linux-hardware.org/?probe=3b41c83d54) | Dec 22, 2024 |
| MACHINIST     | E5-K9 V1.0                  | [0454705976](https://linux-hardware.org/?probe=0454705976) | Dec 19, 2024 |
| Gigabyte      | G41MT-S2PT                  | [a4239ba143](https://linux-hardware.org/?probe=a4239ba143) | Dec 17, 2024 |
| Lenovo        | SHARKBAY NOK                | [5cd46a0402](https://linux-hardware.org/?probe=5cd46a0402) | Dec 11, 2024 |
| Dell          | 0VRWRC A00                  | [e5eed30893](https://linux-hardware.org/?probe=e5eed30893) | Dec 07, 2024 |
| ASUSTek       | Z87-PRO                     | [d86d8eeada](https://linux-hardware.org/?probe=d86d8eeada) | Nov 10, 2024 |
| Unknown       | P43R1600Twins-110DB         | [c600d2b183](https://linux-hardware.org/?probe=c600d2b183) | Nov 08, 2024 |
| MSI           | MS-7345                     | [aa2fdabfba](https://linux-hardware.org/?probe=aa2fdabfba) | Oct 28, 2024 |
| Intel         | DG31PR AAD97573-205         | [4b573de034](https://linux-hardware.org/?probe=4b573de034) | Oct 23, 2024 |
| Gigabyte      | M68MT-S2P                   | [4364777496](https://linux-hardware.org/?probe=4364777496) | Oct 13, 2024 |
| Gigabyte      | M68MT-S2P                   | [8ec2ec3822](https://linux-hardware.org/?probe=8ec2ec3822) | Oct 12, 2024 |
| Gigabyte      | GA-78LMT-S2                 | [ced9a3f102](https://linux-hardware.org/?probe=ced9a3f102) | Sep 27, 2024 |
| Dell          | 0G214D A00                  | [14a759b600](https://linux-hardware.org/?probe=14a759b600) | Sep 03, 2024 |
| ASUSTek       | P5W DH Deluxe               | [00b4a6bc5d](https://linux-hardware.org/?probe=00b4a6bc5d) | Sep 02, 2024 |
| ASRock        | B450M-HDV R4.0              | [30c8ac7aa5](https://linux-hardware.org/?probe=30c8ac7aa5) | Aug 25, 2024 |
| Gigabyte      | EP45-UD3L                   | [b547815742](https://linux-hardware.org/?probe=b547815742) | Aug 24, 2024 |
| MSI           | A320M-A PRO MAX             | [ae173ca405](https://linux-hardware.org/?probe=ae173ca405) | Aug 11, 2024 |
| Dell          | 0HHV7N A00                  | [cdb750e171](https://linux-hardware.org/?probe=cdb750e171) | Aug 03, 2024 |
| ECS           | H81H3-WM                    | [7527b5c842](https://linux-hardware.org/?probe=7527b5c842) | Aug 03, 2024 |
| Dell          | 0WG261                      | [4cb003db71](https://linux-hardware.org/?probe=4cb003db71) | Aug 01, 2024 |
| MSI           | A320M-A PRO                 | [5cfda460bb](https://linux-hardware.org/?probe=5cfda460bb) | Jul 31, 2024 |
| Gigabyte      | GA-880GA-UD3H               | [11fd69223a](https://linux-hardware.org/?probe=11fd69223a) | Jul 20, 2024 |
| ASUSTek       | P9X79                       | [a7b620dd59](https://linux-hardware.org/?probe=a7b620dd59) | Jul 07, 2024 |
| MSI           | PRO H610M-G DDR4            | [8624f4c5fe](https://linux-hardware.org/?probe=8624f4c5fe) | Jun 25, 2024 |
| Unknown       | X79                         | [69bf2d4204](https://linux-hardware.org/?probe=69bf2d4204) | Jun 12, 2024 |
| MSI           | H510M-A PRO                 | [70b4e886ab](https://linux-hardware.org/?probe=70b4e886ab) | May 30, 2024 |
| ASUSTek       | H87-PRO                     | [fb958f35d6](https://linux-hardware.org/?probe=fb958f35d6) | May 10, 2024 |
| ASRock        | B550 Phantom Gaming 4/ac    | [eb876823d7](https://linux-hardware.org/?probe=eb876823d7) | May 10, 2024 |
| Gigabyte      | G41MT-S2PT                  | [a415a1e824](https://linux-hardware.org/?probe=a415a1e824) | May 08, 2024 |
| ASRock        | B550 Phantom Gaming 4/ac    | [72d8d32749](https://linux-hardware.org/?probe=72d8d32749) | May 07, 2024 |
| Gigabyte      | B550M DS3H AC               | [0a5a41e025](https://linux-hardware.org/?probe=0a5a41e025) | Apr 30, 2024 |
| HP            | 0A54h                       | [603811635b](https://linux-hardware.org/?probe=603811635b) | Apr 28, 2024 |
| ASUSTek       | X99-A                       | [eab08c37f7](https://linux-hardware.org/?probe=eab08c37f7) | Apr 28, 2024 |
| HP            | 2B02                        | [5272c37a4c](https://linux-hardware.org/?probe=5272c37a4c) | Apr 18, 2024 |
| MSI           | Z77MA-G45                   | [7a6ac2c320](https://linux-hardware.org/?probe=7a6ac2c320) | Apr 11, 2024 |
| ASRock        | B450 Steel Legend           | [8acd2823d2](https://linux-hardware.org/?probe=8acd2823d2) | Apr 06, 2024 |
| ASRock        | AB350M Pro4                 | [705e1fd7bf](https://linux-hardware.org/?probe=705e1fd7bf) | Apr 05, 2024 |
| ASRock        | H61M-ITX                    | [56a5b3ae2f](https://linux-hardware.org/?probe=56a5b3ae2f) | Apr 03, 2024 |
| ASUSTek       | M4A785-M                    | [cb33f5a0f5](https://linux-hardware.org/?probe=cb33f5a0f5) | Mar 30, 2024 |
| Dell          | 0NDYHG A01                  | [fd065468fe](https://linux-hardware.org/?probe=fd065468fe) | Mar 15, 2024 |
| Gigabyte      | X570S UD                    | [6331209e18](https://linux-hardware.org/?probe=6331209e18) | Mar 07, 2024 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | [130cc65dca](https://linux-hardware.org/?probe=130cc65dca) | Feb 18, 2024 |
| Dell          | 088DT1 A01                  | [1656499259](https://linux-hardware.org/?probe=1656499259) | Feb 17, 2024 |
| MSI           | 760GM-P21                   | [18f56af6bd](https://linux-hardware.org/?probe=18f56af6bd) | Feb 09, 2024 |
| Pegatron      | 2A86E01                     | [9f5ddccda6](https://linux-hardware.org/?probe=9f5ddccda6) | Feb 04, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6a6209d599](https://linux-hardware.org/?probe=6a6209d599) | Feb 04, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | [f0bd42b414](https://linux-hardware.org/?probe=f0bd42b414) | Feb 01, 2024 |
| MSI           | H110M PRO-VD                | [2dcaa98349](https://linux-hardware.org/?probe=2dcaa98349) | Jan 30, 2024 |
| HP            | 1791                        | [e301050210](https://linux-hardware.org/?probe=e301050210) | Jan 29, 2024 |
| ASUSTek       | M4N68T-M-V2                 | [5c4d08e0c4](https://linux-hardware.org/?probe=5c4d08e0c4) | Jan 28, 2024 |
| MSI           | Z97 GAMING 3                | [5a4ad9cb67](https://linux-hardware.org/?probe=5a4ad9cb67) | Jan 28, 2024 |
| Unknown       | P43R1600Twins-110DB         | [0741a919e4](https://linux-hardware.org/?probe=0741a919e4) | Jan 26, 2024 |
| Gigabyte      | Z390 UD V2                  | [b2693bec37](https://linux-hardware.org/?probe=b2693bec37) | Jan 25, 2024 |
| HP            | 198E                        | [15f15e41f1](https://linux-hardware.org/?probe=15f15e41f1) | Jan 11, 2024 |
| ASUSTek       | M5A78L-M LX3                | [6b0c1cd101](https://linux-hardware.org/?probe=6b0c1cd101) | Jan 10, 2024 |
| MSI           | A75A-G35                    | [288caa413e](https://linux-hardware.org/?probe=288caa413e) | Jan 09, 2024 |
| Intel         | B75                         | [648128d27a](https://linux-hardware.org/?probe=648128d27a) | Jan 06, 2024 |
| HP            | 8055                        | [e27c0366a9](https://linux-hardware.org/?probe=e27c0366a9) | Jan 02, 2024 |
| MSI           | G31TM-P21                   | [c80f741175](https://linux-hardware.org/?probe=c80f741175) | Dec 26, 2023 |
| ASUSTek       | H61M-A/BR                   | [e50028a157](https://linux-hardware.org/?probe=e50028a157) | Dec 25, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | [9d3fa026ff](https://linux-hardware.org/?probe=9d3fa026ff) | Dec 25, 2023 |
| Gigabyte      | 965P-S3                     | [b73dd61ca5](https://linux-hardware.org/?probe=b73dd61ca5) | Dec 09, 2023 |
| HP            | 18E5                        | [7b54dc44b4](https://linux-hardware.org/?probe=7b54dc44b4) | Dec 06, 2023 |
| HP            | 8265                        | [1faa811cf0](https://linux-hardware.org/?probe=1faa811cf0) | Dec 03, 2023 |
| MSI           | A320M-A PRO MAX             | [40327ad292](https://linux-hardware.org/?probe=40327ad292) | Nov 20, 2023 |
| HP            | 1589                        | [3e5f417056](https://linux-hardware.org/?probe=3e5f417056) | Nov 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [68aadf1f9b](https://linux-hardware.org/?probe=68aadf1f9b) | Nov 17, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [199a544882](https://linux-hardware.org/?probe=199a544882) | Nov 16, 2023 |
| HP            | 1998                        | [eb9bb55c96](https://linux-hardware.org/?probe=eb9bb55c96) | Nov 16, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [fd1391a823](https://linux-hardware.org/?probe=fd1391a823) | Nov 15, 2023 |
| Foxconn       | 2A92                        | [6cd9ba6728](https://linux-hardware.org/?probe=6cd9ba6728) | Nov 15, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [780d61593a](https://linux-hardware.org/?probe=780d61593a) | Nov 14, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | [0342a78240](https://linux-hardware.org/?probe=0342a78240) | Nov 13, 2023 |
| HP            | 1850                        | [10595f0ac3](https://linux-hardware.org/?probe=10595f0ac3) | Nov 10, 2023 |
| ASUSTek       | PRIME Q270M-C               | [0fcd993247](https://linux-hardware.org/?probe=0fcd993247) | Nov 10, 2023 |
| ASUSTek       | A68HM-K                     | [c3e5415128](https://linux-hardware.org/?probe=c3e5415128) | Nov 06, 2023 |
| ASRock        | FM2A68M-HD+                 | [2b5c984cd8](https://linux-hardware.org/?probe=2b5c984cd8) | Nov 04, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [09d5186c37](https://linux-hardware.org/?probe=09d5186c37) | Oct 30, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [0be3861a6a](https://linux-hardware.org/?probe=0be3861a6a) | Oct 29, 2023 |
| HP            | 8054                        | [3f9ecca91a](https://linux-hardware.org/?probe=3f9ecca91a) | Oct 26, 2023 |
| ASUSTek       | P8H77-M PRO                 | [968efc7996](https://linux-hardware.org/?probe=968efc7996) | Oct 20, 2023 |
| Lenovo        | 30D0 NOK                    | [e67eff74dc](https://linux-hardware.org/?probe=e67eff74dc) | Oct 20, 2023 |
| ASRock        | H110M-HDV R3.0              | [491538303f](https://linux-hardware.org/?probe=491538303f) | Oct 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [6e81d4f878](https://linux-hardware.org/?probe=6e81d4f878) | Oct 18, 2023 |
| Acer          | Aspire GX-281               | [17fad55365](https://linux-hardware.org/?probe=17fad55365) | Oct 16, 2023 |
| ACTION        | M5A78L-M lX V2              | [fe141a8a31](https://linux-hardware.org/?probe=fe141a8a31) | Oct 15, 2023 |
| HP            | 158A                        | [9e43d14a8e](https://linux-hardware.org/?probe=9e43d14a8e) | Oct 10, 2023 |
| MSI           | MS-7235                     | [afb00bf553](https://linux-hardware.org/?probe=afb00bf553) | Oct 07, 2023 |
| Gigabyte      | GA-K8NE                     | [8cb50a99b7](https://linux-hardware.org/?probe=8cb50a99b7) | Oct 07, 2023 |
| Gigabyte      | F2A55M-DS2                  | [75d90cf644](https://linux-hardware.org/?probe=75d90cf644) | Oct 07, 2023 |
| Pegatron      | Benicia                     | [b70dfb3fc8](https://linux-hardware.org/?probe=b70dfb3fc8) | Oct 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [a3ea9b4b56](https://linux-hardware.org/?probe=a3ea9b4b56) | Oct 04, 2023 |
| Gigabyte      | F2A88X-D3H                  | [6ea97d511f](https://linux-hardware.org/?probe=6ea97d511f) | Oct 04, 2023 |
| Lenovo        | ThinkCentre M58p 7484ANU    | [edc20561a3](https://linux-hardware.org/?probe=edc20561a3) | Oct 03, 2023 |
| MSI           | 970 GAMING                  | [c095e62997](https://linux-hardware.org/?probe=c095e62997) | Oct 02, 2023 |
| MSI           | B350M PRO-VD PLUS           | [a8c796cebf](https://linux-hardware.org/?probe=a8c796cebf) | Oct 01, 2023 |
| HP            | 3398                        | [13aa132a7d](https://linux-hardware.org/?probe=13aa132a7d) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | [b31e10d01b](https://linux-hardware.org/?probe=b31e10d01b) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | [ba340393f7](https://linux-hardware.org/?probe=ba340393f7) | Sep 29, 2023 |
| Pegatron      | Benicia                     | [840b02e356](https://linux-hardware.org/?probe=840b02e356) | Sep 29, 2023 |
| MSI           | B450M BAZOOKA V2            | [c815d636ce](https://linux-hardware.org/?probe=c815d636ce) | Sep 28, 2023 |
| MSI           | Z97-G45 GAMING              | [19c07d0fca](https://linux-hardware.org/?probe=19c07d0fca) | Sep 27, 2023 |
| Lenovo        | ThinkCentre A70z 0401B7P    | [21a635940f](https://linux-hardware.org/?probe=21a635940f) | Sep 24, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [3d3b14f0f9](https://linux-hardware.org/?probe=3d3b14f0f9) | Sep 21, 2023 |
| ASUSTek       | B150M-C D3                  | [179a66ec43](https://linux-hardware.org/?probe=179a66ec43) | Sep 19, 2023 |
| Pegatron      | 2AB5                        | [b21eddb040](https://linux-hardware.org/?probe=b21eddb040) | Sep 19, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | [fa9b30f699](https://linux-hardware.org/?probe=fa9b30f699) | Sep 18, 2023 |
| Gigabyte      | A520M H                     | [24efefc447](https://linux-hardware.org/?probe=24efefc447) | Sep 17, 2023 |
| Dell          | 048DY8 A00                  | [3cc67a5e62](https://linux-hardware.org/?probe=3cc67a5e62) | Sep 15, 2023 |
| ASUSTek       | P5KPL-AM                    | [3f55a69040](https://linux-hardware.org/?probe=3f55a69040) | Sep 11, 2023 |
| Toshiba       | STI 006998G                 | [d34aadcc92](https://linux-hardware.org/?probe=d34aadcc92) | Sep 07, 2023 |
| ASRock        | Z68 Pro3                    | [757ebbe056](https://linux-hardware.org/?probe=757ebbe056) | Sep 06, 2023 |
| Foxconn       | G31MX Series                | [4b4c5fb5f8](https://linux-hardware.org/?probe=4b4c5fb5f8) | Sep 04, 2023 |
| Acer          | Aspire XC-830               | [a3356b9a91](https://linux-hardware.org/?probe=a3356b9a91) | Sep 03, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [f11dacb362](https://linux-hardware.org/?probe=f11dacb362) | Sep 01, 2023 |
| ASRock        | AB350M Pro4                 | [0f9de0fdf4](https://linux-hardware.org/?probe=0f9de0fdf4) | Sep 01, 2023 |
| Foxconn       | A6VMX 0A                    | [338cdb7d40](https://linux-hardware.org/?probe=338cdb7d40) | Sep 01, 2023 |
| ASRock        | H97M Pro4                   | [ff1be33f8e](https://linux-hardware.org/?probe=ff1be33f8e) | Sep 01, 2023 |
| Gigabyte      | X58A-UD3R                   | [8ee240ba0b](https://linux-hardware.org/?probe=8ee240ba0b) | Sep 01, 2023 |
| MSI           | PRO B660M-A DDR4            | [b6a24176aa](https://linux-hardware.org/?probe=b6a24176aa) | Aug 31, 2023 |
| HP            | 18E5                        | [75c3b34f87](https://linux-hardware.org/?probe=75c3b34f87) | Aug 31, 2023 |
| Gigabyte      | B450M K-CF                  | [2086d348b2](https://linux-hardware.org/?probe=2086d348b2) | Aug 31, 2023 |
| ASUSTek       | P8H61 EVO                   | [facd465366](https://linux-hardware.org/?probe=facd465366) | Aug 30, 2023 |
| MSI           | G41M-P33 Combo              | [23712e9380](https://linux-hardware.org/?probe=23712e9380) | Aug 28, 2023 |
| Positivo      | POS-PQ45AU                  | [aba45a4f14](https://linux-hardware.org/?probe=aba45a4f14) | Aug 27, 2023 |
| ASUSTek       | P8Z77-V LX                  | [9f1872b5e9](https://linux-hardware.org/?probe=9f1872b5e9) | Aug 26, 2023 |
| GEEKOM        | GM08i3T                     | [36ea06968d](https://linux-hardware.org/?probe=36ea06968d) | Aug 23, 2023 |
| ASRock        | 890GX Pro3                  | [c36b43c52a](https://linux-hardware.org/?probe=c36b43c52a) | Aug 21, 2023 |
| Gigabyte      | GA-N680SLI-DQ6              | [0838a31aaf](https://linux-hardware.org/?probe=0838a31aaf) | Aug 19, 2023 |
| Intel         | DE3815TYKH H26998-402       | [a2a8c567a3](https://linux-hardware.org/?probe=a2a8c567a3) | Aug 17, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [83e6c3323d](https://linux-hardware.org/?probe=83e6c3323d) | Aug 16, 2023 |
| HP            | 3031h                       | [2f9084013a](https://linux-hardware.org/?probe=2f9084013a) | Aug 13, 2023 |
| ASUSTek       | P7P55D DELUXE               | [f900ebabde](https://linux-hardware.org/?probe=f900ebabde) | Aug 13, 2023 |
| ASUSTek       | Rampage IV GENE             | [2a494a04b5](https://linux-hardware.org/?probe=2a494a04b5) | Aug 12, 2023 |
| HP            | 18E7                        | [ff27f888f0](https://linux-hardware.org/?probe=ff27f888f0) | Aug 10, 2023 |
| Dell          | 040DDP A00                  | [13d99d66da](https://linux-hardware.org/?probe=13d99d66da) | Aug 09, 2023 |
| Dell          | 0P301D A00                  | [e5091194fb](https://linux-hardware.org/?probe=e5091194fb) | Aug 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c94a18b924](https://linux-hardware.org/?probe=c94a18b924) | Aug 02, 2023 |
| HP            | 18E7                        | [339050cd65](https://linux-hardware.org/?probe=339050cd65) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3a500cdb55](https://linux-hardware.org/?probe=3a500cdb55) | Aug 01, 2023 |
| Dell          | 0C27VV A03                  | [75ff82774b](https://linux-hardware.org/?probe=75ff82774b) | Jul 31, 2023 |
| PCWare        | IPX1800E2                   | [ee17cd82e7](https://linux-hardware.org/?probe=ee17cd82e7) | Jul 27, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [1d4e6c23cf](https://linux-hardware.org/?probe=1d4e6c23cf) | Jul 27, 2023 |
| HP            | 212B                        | [8e6a290d51](https://linux-hardware.org/?probe=8e6a290d51) | Jul 25, 2023 |
| Dell          | 0VD92X A00                  | [675e646d05](https://linux-hardware.org/?probe=675e646d05) | Jul 23, 2023 |
| Intel         | JSL MRD                     | [4c9c765884](https://linux-hardware.org/?probe=4c9c765884) | Jul 21, 2023 |
| Dell          | 0M863N A01                  | [682fc212b6](https://linux-hardware.org/?probe=682fc212b6) | Jul 20, 2023 |
| Intel X79     | Unknown                     | [360facd1fb](https://linux-hardware.org/?probe=360facd1fb) | Jul 19, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [87763ca861](https://linux-hardware.org/?probe=87763ca861) | Jul 16, 2023 |
| Foxconn       | 2ABF                        | [e302c823fc](https://linux-hardware.org/?probe=e302c823fc) | Jul 13, 2023 |
| HP            | 18E8                        | [b892f0dd28](https://linux-hardware.org/?probe=b892f0dd28) | Jul 12, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [7a8f3c985f](https://linux-hardware.org/?probe=7a8f3c985f) | Jul 11, 2023 |
| Gigabyte      | B450M DS3H-CF               | [144cb029ba](https://linux-hardware.org/?probe=144cb029ba) | Jul 08, 2023 |
| Dell          | 01TKCC A01                  | [b3ab41fd8f](https://linux-hardware.org/?probe=b3ab41fd8f) | Jul 08, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [c9ccceb765](https://linux-hardware.org/?probe=c9ccceb765) | Jul 07, 2023 |
| ASRock        | H510M-HDV R2.0              | [2cb98a7961](https://linux-hardware.org/?probe=2cb98a7961) | Jul 06, 2023 |
| ECS           | H55H-M2                     | [344ce5bb17](https://linux-hardware.org/?probe=344ce5bb17) | Jul 03, 2023 |
| ASUSTek       | UN45                        | [487845dd55](https://linux-hardware.org/?probe=487845dd55) | Jul 03, 2023 |
| Gigabyte      | 965P-S3                     | [7aa7550205](https://linux-hardware.org/?probe=7aa7550205) | Jul 02, 2023 |
| MSI           | PRO X670-P WIFI             | [7beeaf657d](https://linux-hardware.org/?probe=7beeaf657d) | Jul 02, 2023 |
| Gigabyte      | H61M-S1                     | [b6be2d7f9f](https://linux-hardware.org/?probe=b6be2d7f9f) | Jun 30, 2023 |
| Acer          | Aspire TC-705               | [326f873ac3](https://linux-hardware.org/?probe=326f873ac3) | Jun 29, 2023 |
| ASUSTek       | M5A97 PLUS                  | [2faeb24e37](https://linux-hardware.org/?probe=2faeb24e37) | Jun 27, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [90067b8232](https://linux-hardware.org/?probe=90067b8232) | Jun 27, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [a31908b24b](https://linux-hardware.org/?probe=a31908b24b) | Jun 25, 2023 |
| Intel         | DH61WW AAG23116-204         | [4269ca2c0b](https://linux-hardware.org/?probe=4269ca2c0b) | Jun 25, 2023 |
| HP            | 8055                        | [7fac5a1354](https://linux-hardware.org/?probe=7fac5a1354) | Jun 24, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [9408842ffc](https://linux-hardware.org/?probe=9408842ffc) | Jun 24, 2023 |
| MSI           | MS-7360                     | [9a0d46b069](https://linux-hardware.org/?probe=9a0d46b069) | Jun 23, 2023 |
| Dell          | 0WMJ54 A01                  | [0b8cf1cae7](https://linux-hardware.org/?probe=0b8cf1cae7) | Jun 22, 2023 |
| ASUSTek       | PRIME B365M-A               | [4e877b9c8d](https://linux-hardware.org/?probe=4e877b9c8d) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | [4560c6d34d](https://linux-hardware.org/?probe=4560c6d34d) | Jun 19, 2023 |
| ASUSTek       | P8H61-M LX                  | [35de204113](https://linux-hardware.org/?probe=35de204113) | Jun 19, 2023 |
| MSI           | 2AE0                        | [fdfc88e5da](https://linux-hardware.org/?probe=fdfc88e5da) | Jun 18, 2023 |
| Gigabyte      | B450M DS3H-CF               | [3c45e54fd2](https://linux-hardware.org/?probe=3c45e54fd2) | Jun 17, 2023 |
| ASUSTek       | H97-PLUS                    | [adc38f998a](https://linux-hardware.org/?probe=adc38f998a) | Jun 17, 2023 |
| ASUSTek       | H61M-A/BR                   | [a587493314](https://linux-hardware.org/?probe=a587493314) | Jun 16, 2023 |
| Lenovo        | SDK0E50510 WIN              | [8571bdf994](https://linux-hardware.org/?probe=8571bdf994) | Jun 15, 2023 |
| Acer          | Veriton M6630G V:1.0        | [d58cd3aa7d](https://linux-hardware.org/?probe=d58cd3aa7d) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [922c598503](https://linux-hardware.org/?probe=922c598503) | Jun 14, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [26e6a1f816](https://linux-hardware.org/?probe=26e6a1f816) | Jun 13, 2023 |
| Lenovo        | 103D SDK0Q40112 WIN 3305... | [5c2eef3678](https://linux-hardware.org/?probe=5c2eef3678) | Jun 12, 2023 |
| ASUSTek       | P8Z77-V LX                  | [b5b264d1e8](https://linux-hardware.org/?probe=b5b264d1e8) | Jun 12, 2023 |
| ASRock        | G41M-VS3                    | [d592b19e9b](https://linux-hardware.org/?probe=d592b19e9b) | Jun 10, 2023 |
| Wistron       | ProLiant ML110 G5           | [eea1c44d94](https://linux-hardware.org/?probe=eea1c44d94) | Jun 10, 2023 |
| Biostar       | H610MH                      | [2cd4e157d4](https://linux-hardware.org/?probe=2cd4e157d4) | Jun 08, 2023 |
| HP            | 1850                        | [bddc14be8b](https://linux-hardware.org/?probe=bddc14be8b) | Jun 05, 2023 |
| HP            | 1495                        | [0cbf6bee1f](https://linux-hardware.org/?probe=0cbf6bee1f) | Jun 04, 2023 |
| MSI           | Boston                      | [95b4d5183d](https://linux-hardware.org/?probe=95b4d5183d) | Jun 04, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [417320253a](https://linux-hardware.org/?probe=417320253a) | May 31, 2023 |
| TPV-INVENT... | 2AC6 A01                    | [1ac394c97c](https://linux-hardware.org/?probe=1ac394c97c) | May 30, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [528f7440b7](https://linux-hardware.org/?probe=528f7440b7) | May 29, 2023 |
| Gigabyte      | H61M-DS2 x.x                | [e58b7bfc92](https://linux-hardware.org/?probe=e58b7bfc92) | May 29, 2023 |
| Gigabyte      | GA-MA78LMT-S2               | [bf3b702d7a](https://linux-hardware.org/?probe=bf3b702d7a) | May 28, 2023 |
| MSI           | A520M-A PRO                 | [6f1a19d503](https://linux-hardware.org/?probe=6f1a19d503) | May 25, 2023 |
| Gigabyte      | B365M DS3H                  | [149a19eeeb](https://linux-hardware.org/?probe=149a19eeeb) | May 24, 2023 |
| ASUSTek       | H81M-K                      | [f65eac842b](https://linux-hardware.org/?probe=f65eac842b) | May 23, 2023 |
| Gigabyte      | H510M H                     | [39725fefa4](https://linux-hardware.org/?probe=39725fefa4) | May 19, 2023 |
| HP            | 0A54h                       | [76953e42f8](https://linux-hardware.org/?probe=76953e42f8) | May 18, 2023 |
| Gigabyte      | B450M H                     | [4bd367b4c7](https://linux-hardware.org/?probe=4bd367b4c7) | May 17, 2023 |
| HP            | 18E5                        | [5e25e2156a](https://linux-hardware.org/?probe=5e25e2156a) | May 16, 2023 |
| ASRock        | G41M-GS3                    | [8859685e86](https://linux-hardware.org/?probe=8859685e86) | May 13, 2023 |
| Dell          | 09KPNV A01                  | [cbd408a1a6](https://linux-hardware.org/?probe=cbd408a1a6) | May 13, 2023 |
| Dell          | 0W0CHX A00                  | [60defd2bfe](https://linux-hardware.org/?probe=60defd2bfe) | May 12, 2023 |
| Acer          | RS880M05                    | [5952c105f6](https://linux-hardware.org/?probe=5952c105f6) | May 12, 2023 |
| Gigabyte      | H61M-S1                     | [db910d4ee1](https://linux-hardware.org/?probe=db910d4ee1) | May 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [68afb54270](https://linux-hardware.org/?probe=68afb54270) | May 10, 2023 |
| ASUSTek       | M4A78L-M                    | [1a843c3a7f](https://linux-hardware.org/?probe=1a843c3a7f) | May 10, 2023 |
| ASUSTek       | P8H67                       | [eeb083abcd](https://linux-hardware.org/?probe=eeb083abcd) | May 07, 2023 |
| Shuttle       | FZ77                        | [e4a71bcb2d](https://linux-hardware.org/?probe=e4a71bcb2d) | May 07, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [c9a5bee99d](https://linux-hardware.org/?probe=c9a5bee99d) | May 05, 2023 |
| MSI           | 760GM-P34                   | [cb75fca473](https://linux-hardware.org/?probe=cb75fca473) | May 04, 2023 |
| MSI           | MS-7025                     | [a15dc17cfc](https://linux-hardware.org/?probe=a15dc17cfc) | May 02, 2023 |
| MAXSUN        | MS-A86FX FS M.3             | [3ce20d3b05](https://linux-hardware.org/?probe=3ce20d3b05) | May 01, 2023 |
| DIEBOLD       | NM70-I                      | [c01a40d58c](https://linux-hardware.org/?probe=c01a40d58c) | Apr 30, 2023 |
| ASUSTek       | H81M-C/BR                   | [32942be783](https://linux-hardware.org/?probe=32942be783) | Apr 29, 2023 |
| AZW           | MINI S 10                   | [12ba32f977](https://linux-hardware.org/?probe=12ba32f977) | Apr 28, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [238598d9ab](https://linux-hardware.org/?probe=238598d9ab) | Apr 26, 2023 |
| ASUSTek       | P8P67 LE                    | [e46f340908](https://linux-hardware.org/?probe=e46f340908) | Apr 25, 2023 |
| ASRock        | AB350M-HDV                  | [44ac797451](https://linux-hardware.org/?probe=44ac797451) | Apr 25, 2023 |
| ASUSTek       | A68HM-K                     | [ae90303c3a](https://linux-hardware.org/?probe=ae90303c3a) | Apr 25, 2023 |
| Lenovo        | ThinkCentre A70z 0401G6G    | [b1b8bf3df6](https://linux-hardware.org/?probe=b1b8bf3df6) | Apr 25, 2023 |
| HP            | 0AA8h                       | [b927834a03](https://linux-hardware.org/?probe=b927834a03) | Apr 23, 2023 |
| Gigabyte      | H61M-S2PH                   | [ec36f4ada2](https://linux-hardware.org/?probe=ec36f4ada2) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | [bf1dbf49a8](https://linux-hardware.org/?probe=bf1dbf49a8) | Apr 22, 2023 |
| Gigabyte      | EP45-UD3                    | [5d45f63468](https://linux-hardware.org/?probe=5d45f63468) | Apr 22, 2023 |
| Biostar       | A75MG                       | [50cb5c256e](https://linux-hardware.org/?probe=50cb5c256e) | Apr 22, 2023 |
| Intel         | DB65AL AAG12530-310         | [c625f3747a](https://linux-hardware.org/?probe=c625f3747a) | Apr 21, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [5f1a1c6abd](https://linux-hardware.org/?probe=5f1a1c6abd) | Apr 20, 2023 |
| Foxconn       | 2ABF                        | [53d3a8d066](https://linux-hardware.org/?probe=53d3a8d066) | Apr 19, 2023 |
| Gigabyte      | G31M-ES2L                   | [0244194778](https://linux-hardware.org/?probe=0244194778) | Apr 17, 2023 |
| ASUSTek       | PRIME X570-P                | [337102cd4c](https://linux-hardware.org/?probe=337102cd4c) | Apr 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [7ac461b735](https://linux-hardware.org/?probe=7ac461b735) | Apr 15, 2023 |
| Gigabyte      | P55-UD3R                    | [5e8538987d](https://linux-hardware.org/?probe=5e8538987d) | Apr 14, 2023 |
| Dell          | 0GXM1W A00                  | [f96d907026](https://linux-hardware.org/?probe=f96d907026) | Apr 13, 2023 |
| ASRock        | M3N78D FX                   | [618073d9e9](https://linux-hardware.org/?probe=618073d9e9) | Apr 12, 2023 |
| Dell          | 0WR7PY A02                  | [2cec768fe1](https://linux-hardware.org/?probe=2cec768fe1) | Apr 11, 2023 |
| ASRock        | X570 Pro4                   | [feb08fab62](https://linux-hardware.org/?probe=feb08fab62) | Apr 09, 2023 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [54fabc7712](https://linux-hardware.org/?probe=54fabc7712) | Apr 09, 2023 |
| ASUSTek       | AM1M-A                      | [120f5780bd](https://linux-hardware.org/?probe=120f5780bd) | Apr 09, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [2d355e87d7](https://linux-hardware.org/?probe=2d355e87d7) | Apr 07, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | [10c9b38ed6](https://linux-hardware.org/?probe=10c9b38ed6) | Apr 07, 2023 |
| Gigabyte      | H61M-S2PV                   | [8c4f851451](https://linux-hardware.org/?probe=8c4f851451) | Apr 07, 2023 |
| ASUSTek       | M4N98TD EVO                 | [8a2a2cf1ce](https://linux-hardware.org/?probe=8a2a2cf1ce) | Apr 07, 2023 |
| ASRock        | H61M-DGS                    | [e2dd28ca36](https://linux-hardware.org/?probe=e2dd28ca36) | Apr 06, 2023 |
| Gigabyte      | F2A55M-DS2                  | [fea5792a8b](https://linux-hardware.org/?probe=fea5792a8b) | Apr 06, 2023 |
| ASUSTek       | H170-PRO                    | [8756f8891c](https://linux-hardware.org/?probe=8756f8891c) | Apr 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9e99b4150b](https://linux-hardware.org/?probe=9e99b4150b) | Apr 06, 2023 |
| ASRock        | A320M-DVS R4.0              | [6da0293a4b](https://linux-hardware.org/?probe=6da0293a4b) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [540d1f11a6](https://linux-hardware.org/?probe=540d1f11a6) | Apr 05, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [d8dc8a37b1](https://linux-hardware.org/?probe=d8dc8a37b1) | Apr 04, 2023 |
| ASRock        | 990FX Extreme3              | [013cd9b246](https://linux-hardware.org/?probe=013cd9b246) | Apr 03, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [de861c6d3f](https://linux-hardware.org/?probe=de861c6d3f) | Apr 03, 2023 |
| Acer          | Veriton X2632G V:1.0        | [f5eafafc96](https://linux-hardware.org/?probe=f5eafafc96) | Apr 02, 2023 |
| ASUSTek       | PRIME X470-PRO              | [96fcc41161](https://linux-hardware.org/?probe=96fcc41161) | Apr 01, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | [f54ccba86f](https://linux-hardware.org/?probe=f54ccba86f) | Apr 01, 2023 |
| HP            | 2AFA                        | [d177838277](https://linux-hardware.org/?probe=d177838277) | Mar 31, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [fc9a42e387](https://linux-hardware.org/?probe=fc9a42e387) | Mar 31, 2023 |
| HP            | 3047h                       | [c4f4f0c51d](https://linux-hardware.org/?probe=c4f4f0c51d) | Mar 28, 2023 |
| Gigabyte      | GA-780T-D3L                 | [4f523c6409](https://linux-hardware.org/?probe=4f523c6409) | Mar 28, 2023 |
| Lenovo        | NO DPK                      | [220c640743](https://linux-hardware.org/?probe=220c640743) | Mar 28, 2023 |
| Gigabyte      | B450M S2H                   | [0901eb1e27](https://linux-hardware.org/?probe=0901eb1e27) | Mar 27, 2023 |
| ASUSTek       | P8H77-M                     | [6fc56d2339](https://linux-hardware.org/?probe=6fc56d2339) | Mar 25, 2023 |
| MSI           | A520M PRO                   | [c27ea21be5](https://linux-hardware.org/?probe=c27ea21be5) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [5c811e496f](https://linux-hardware.org/?probe=5c811e496f) | Mar 24, 2023 |
| Lenovo        | SDK0E50519 WIN              | [2fb6bb5874](https://linux-hardware.org/?probe=2fb6bb5874) | Mar 24, 2023 |
| ASUSTek       | M4N98TD EVO                 | [9cb4b84924](https://linux-hardware.org/?probe=9cb4b84924) | Mar 24, 2023 |
| Dell          | 0NDYHG A01                  | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| MSI           | MS-7255                     | [7322068101](https://linux-hardware.org/?probe=7322068101) | Mar 23, 2023 |
| Gigabyte      | P43-ES3G                    | [60a7dc4c2e](https://linux-hardware.org/?probe=60a7dc4c2e) | Mar 20, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [db3e17d5f1](https://linux-hardware.org/?probe=db3e17d5f1) | Mar 20, 2023 |
| ASUSTek       | PRIME B350M-A               | [9ee81ffe32](https://linux-hardware.org/?probe=9ee81ffe32) | Mar 20, 2023 |
| ASRock        | 970A-G                      | [52b0aa69ba](https://linux-hardware.org/?probe=52b0aa69ba) | Mar 20, 2023 |
| HP            | 18E7                        | [9e4b5010d8](https://linux-hardware.org/?probe=9e4b5010d8) | Mar 20, 2023 |
| Gigabyte      | A520M H                     | [a3cee7c278](https://linux-hardware.org/?probe=a3cee7c278) | Mar 19, 2023 |
| Gigabyte      | 990FXA-UD5                  | [0daa99f732](https://linux-hardware.org/?probe=0daa99f732) | Mar 19, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [2a1291ac22](https://linux-hardware.org/?probe=2a1291ac22) | Mar 18, 2023 |
| MSI           | H55M-P31                    | [e95e62df99](https://linux-hardware.org/?probe=e95e62df99) | Mar 18, 2023 |
| Medion        | H81H3-EM2 H81EM2W08.217     | [1e1a430355](https://linux-hardware.org/?probe=1e1a430355) | Mar 17, 2023 |
| Dell          | 0T1D10 A01                  | [c640b09a8b](https://linux-hardware.org/?probe=c640b09a8b) | Mar 17, 2023 |
| Pegatron      | 2AB5                        | [7ab2e7b0ab](https://linux-hardware.org/?probe=7ab2e7b0ab) | Mar 16, 2023 |
| ASUSTek       | CG5290                      | [e0ab58dbfe](https://linux-hardware.org/?probe=e0ab58dbfe) | Mar 16, 2023 |
| ASUSTek       | VC62B                       | [9bf2d226a8](https://linux-hardware.org/?probe=9bf2d226a8) | Mar 15, 2023 |
| MSI           | H61M-P20                    | [8129a4f5a4](https://linux-hardware.org/?probe=8129a4f5a4) | Mar 15, 2023 |
| ASRock        | G31M-S                      | [7672cc15a2](https://linux-hardware.org/?probe=7672cc15a2) | Mar 13, 2023 |
| Gigabyte      | B85M-D3H-A                  | [4265744c52](https://linux-hardware.org/?probe=4265744c52) | Mar 12, 2023 |
| Dell          | 00V62H A01                  | [a45ebd1b85](https://linux-hardware.org/?probe=a45ebd1b85) | Mar 12, 2023 |
| Pegatron      | 2AC2                        | [a6084e8904](https://linux-hardware.org/?probe=a6084e8904) | Mar 11, 2023 |
| ASUSTek       | P7P55D DELUXE               | [d2b402f3c0](https://linux-hardware.org/?probe=d2b402f3c0) | Mar 11, 2023 |
| HP            | 0AA0h                       | [f86f0bc187](https://linux-hardware.org/?probe=f86f0bc187) | Mar 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [bf4c797c87](https://linux-hardware.org/?probe=bf4c797c87) | Mar 10, 2023 |
| ASRock        | H61M-ITX                    | [ab7e81c6ca](https://linux-hardware.org/?probe=ab7e81c6ca) | Mar 09, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [b1a69ac03b](https://linux-hardware.org/?probe=b1a69ac03b) | Mar 08, 2023 |
| ECS           | MCP61PM-GM                  | [ac561937e3](https://linux-hardware.org/?probe=ac561937e3) | Mar 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c6f9f5a58d](https://linux-hardware.org/?probe=c6f9f5a58d) | Mar 06, 2023 |
| Gigabyte      | P35-DS3L                    | [31aeecfcb9](https://linux-hardware.org/?probe=31aeecfcb9) | Mar 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9b72e94139](https://linux-hardware.org/?probe=9b72e94139) | Mar 06, 2023 |
| Gigabyte      | Z370M D3H-CF                | [d000dc6718](https://linux-hardware.org/?probe=d000dc6718) | Mar 04, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [914a9990c4](https://linux-hardware.org/?probe=914a9990c4) | Mar 04, 2023 |
| Gigabyte      | B450M DS3H-CF               | [84e37e870d](https://linux-hardware.org/?probe=84e37e870d) | Mar 03, 2023 |
| Intel         | DB75EN AAG39650-302         | [e828686fc3](https://linux-hardware.org/?probe=e828686fc3) | Mar 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [1da5b61697](https://linux-hardware.org/?probe=1da5b61697) | Mar 02, 2023 |
| ASUSTek       | F2A85-V PRO                 | [aa7d308d7e](https://linux-hardware.org/?probe=aa7d308d7e) | Mar 01, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [6f1de5f17c](https://linux-hardware.org/?probe=6f1de5f17c) | Feb 28, 2023 |
| ASUSTek       | PRIME B550M-A               | [a6af4042ea](https://linux-hardware.org/?probe=a6af4042ea) | Feb 28, 2023 |
| Foxconn       | G31MX Series                | [79ee8e5da3](https://linux-hardware.org/?probe=79ee8e5da3) | Feb 28, 2023 |
| MSI           | B450M MORTAR MAX            | [0335729036](https://linux-hardware.org/?probe=0335729036) | Feb 27, 2023 |
| Intel         | H61                         | [b61ef1ed65](https://linux-hardware.org/?probe=b61ef1ed65) | Feb 27, 2023 |
| MSI           | NF750-G55                   | [f279251ffa](https://linux-hardware.org/?probe=f279251ffa) | Feb 27, 2023 |
| Acer          | EG43M                       | [d533c457eb](https://linux-hardware.org/?probe=d533c457eb) | Feb 26, 2023 |
| ASUSTek       | PRIME Q270M-C               | [edf748dbbb](https://linux-hardware.org/?probe=edf748dbbb) | Feb 26, 2023 |
| Dell          | 0VHWTR A01                  | [ab8247e106](https://linux-hardware.org/?probe=ab8247e106) | Feb 24, 2023 |
| MSI           | B360M PRO-VH                | [fad0bd20e1](https://linux-hardware.org/?probe=fad0bd20e1) | Feb 24, 2023 |
| MSI           | G41M-P33 Combo              | [91c8d45121](https://linux-hardware.org/?probe=91c8d45121) | Feb 24, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9171567db4](https://linux-hardware.org/?probe=9171567db4) | Feb 24, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [b410c9f493](https://linux-hardware.org/?probe=b410c9f493) | Feb 24, 2023 |
| HP            | 1998                        | [145c009f05](https://linux-hardware.org/?probe=145c009f05) | Feb 24, 2023 |
| ASUSTek       | M2N-MX SE Plus              | [21aa20cd64](https://linux-hardware.org/?probe=21aa20cd64) | Feb 24, 2023 |
| Gigabyte      | Z97-HD3                     | [016a51a4af](https://linux-hardware.org/?probe=016a51a4af) | Feb 23, 2023 |
| MSI           | H110M PRO-VH PLUS           | [de05d0d3f6](https://linux-hardware.org/?probe=de05d0d3f6) | Feb 23, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [cfe5ecec44](https://linux-hardware.org/?probe=cfe5ecec44) | Feb 23, 2023 |
| Biostar       | N68S3B                      | [4572b3d965](https://linux-hardware.org/?probe=4572b3d965) | Feb 23, 2023 |
| Foxconn       | 2ADA                        | [75b2eb9c1f](https://linux-hardware.org/?probe=75b2eb9c1f) | Feb 23, 2023 |
| Gigabyte      | H81M-S2PV                   | [ad365efca1](https://linux-hardware.org/?probe=ad365efca1) | Feb 22, 2023 |
| Gigabyte      | X570 GAMING X               | [4803e8ee01](https://linux-hardware.org/?probe=4803e8ee01) | Feb 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [2d36b57c9c](https://linux-hardware.org/?probe=2d36b57c9c) | Feb 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [9523a0ccc2](https://linux-hardware.org/?probe=9523a0ccc2) | Feb 22, 2023 |
| ASUSTek       | M5A78L/USB3                 | [b4288b76ee](https://linux-hardware.org/?probe=b4288b76ee) | Feb 21, 2023 |
| MSI           | Z170A XPOWER GAMING TITA... | [b644019f77](https://linux-hardware.org/?probe=b644019f77) | Feb 21, 2023 |
| MSI           | H510M-A PRO                 | [bbef057c8f](https://linux-hardware.org/?probe=bbef057c8f) | Feb 21, 2023 |
| ASUSTek       | PRIME Z390-P                | [d81ff5358a](https://linux-hardware.org/?probe=d81ff5358a) | Feb 20, 2023 |
| MSI           | G41M-P23                    | [04211b9202](https://linux-hardware.org/?probe=04211b9202) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [119e106d80](https://linux-hardware.org/?probe=119e106d80) | Feb 20, 2023 |
| ASRock        | 880GM-LE FX                 | [db290cd703](https://linux-hardware.org/?probe=db290cd703) | Feb 19, 2023 |
| MSI           | Z97M GAMING                 | [e983a3704e](https://linux-hardware.org/?probe=e983a3704e) | Feb 19, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [8dd1992835](https://linux-hardware.org/?probe=8dd1992835) | Feb 18, 2023 |
| ASRock        | 880GM-LE FX                 | [1d45a444a3](https://linux-hardware.org/?probe=1d45a444a3) | Feb 18, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [3ed988e135](https://linux-hardware.org/?probe=3ed988e135) | Feb 17, 2023 |
| Gigabyte      | H87M-HD3                    | [778b7898e3](https://linux-hardware.org/?probe=778b7898e3) | Feb 17, 2023 |
| EVGA          | 151-IB-E699                 | [9e975c7966](https://linux-hardware.org/?probe=9e975c7966) | Feb 17, 2023 |
| Pegatron      | IPM31G                      | [42d112d7e0](https://linux-hardware.org/?probe=42d112d7e0) | Feb 17, 2023 |
| HP            | 2820h                       | [552bdc9930](https://linux-hardware.org/?probe=552bdc9930) | Feb 17, 2023 |
| MSI           | H61M-E33                    | [f0c902ce04](https://linux-hardware.org/?probe=f0c902ce04) | Feb 16, 2023 |
| MSI           | Z97-G45 GAMING              | [c6a7d3a755](https://linux-hardware.org/?probe=c6a7d3a755) | Feb 16, 2023 |
| Gigabyte      | MZAPLBP-00                  | [b043125d6e](https://linux-hardware.org/?probe=b043125d6e) | Feb 16, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [3ce39f40e7](https://linux-hardware.org/?probe=3ce39f40e7) | Feb 16, 2023 |
| MSI           | B350M PRO-VD PLUS           | [63789621e0](https://linux-hardware.org/?probe=63789621e0) | Feb 16, 2023 |
| Lenovo        | ThinkCentre M91 4518E4S     | [91b1fb7e03](https://linux-hardware.org/?probe=91b1fb7e03) | Feb 16, 2023 |
| Philco        | DTC-A55                     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| Gigabyte      | F2A78M-HD2                  | [9f9cc6f9e2](https://linux-hardware.org/?probe=9f9cc6f9e2) | Feb 16, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | [8e521a2efc](https://linux-hardware.org/?probe=8e521a2efc) | Feb 16, 2023 |
| ASUSTek       | H81T                        | [51aa090e9a](https://linux-hardware.org/?probe=51aa090e9a) | Feb 16, 2023 |
| HP            | 3031h                       | [2b0cc2bd6e](https://linux-hardware.org/?probe=2b0cc2bd6e) | Feb 16, 2023 |
| MSI           | MS-7235                     | [519f3742a3](https://linux-hardware.org/?probe=519f3742a3) | Feb 15, 2023 |
| Dell          | 0NK5PH A00                  | [5455b577db](https://linux-hardware.org/?probe=5455b577db) | Feb 15, 2023 |
| Gigabyte      | P43-ES3G                    | [528ffce1c7](https://linux-hardware.org/?probe=528ffce1c7) | Feb 15, 2023 |
| ASUSTek       | PRIME B365M-K               | [20b88dda19](https://linux-hardware.org/?probe=20b88dda19) | Feb 15, 2023 |
| Dell          | 0GXM1W A00                  | [3ab6d305fc](https://linux-hardware.org/?probe=3ab6d305fc) | Feb 15, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | [f0d6ada218](https://linux-hardware.org/?probe=f0d6ada218) | Feb 15, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [b30e6a84c8](https://linux-hardware.org/?probe=b30e6a84c8) | Feb 14, 2023 |
| MSI           | Z97-G45 GAMING              | [f9318d4390](https://linux-hardware.org/?probe=f9318d4390) | Feb 14, 2023 |
| ASRock        | E350M1                      | [ac69adceb6](https://linux-hardware.org/?probe=ac69adceb6) | Feb 13, 2023 |
| ASUSTek       | P7P55D-E EVO                | [f1ec250753](https://linux-hardware.org/?probe=f1ec250753) | Feb 13, 2023 |
| Dell          | 0YXT71 A01                  | [cdc2dedbcd](https://linux-hardware.org/?probe=cdc2dedbcd) | Feb 13, 2023 |
| HP            | 3031h                       | [f9a0848388](https://linux-hardware.org/?probe=f9a0848388) | Feb 11, 2023 |
| ASUSTek       | PRIME X570-PRO              | [f0f4d31de2](https://linux-hardware.org/?probe=f0f4d31de2) | Feb 10, 2023 |
| Medion        | TJ4105                      | [cd654518c0](https://linux-hardware.org/?probe=cd654518c0) | Feb 09, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | [8532f05156](https://linux-hardware.org/?probe=8532f05156) | Feb 09, 2023 |
| HP            | 1905                        | [a442e1de06](https://linux-hardware.org/?probe=a442e1de06) | Feb 07, 2023 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | [a527005a2a](https://linux-hardware.org/?probe=a527005a2a) | Feb 06, 2023 |
| Dell          | 084J0R A00                  | [7fe633b52f](https://linux-hardware.org/?probe=7fe633b52f) | Feb 05, 2023 |
| ASUSTek       | Z97-K                       | [e3f865cd20](https://linux-hardware.org/?probe=e3f865cd20) | Jan 28, 2023 |
| Dell          | 0773VG A00                  | [328dae4014](https://linux-hardware.org/?probe=328dae4014) | Jan 26, 2023 |
| HP            | 3048h                       | [caabf4189f](https://linux-hardware.org/?probe=caabf4189f) | Jan 25, 2023 |
| AZW           | U59                         | [6d2b672b77](https://linux-hardware.org/?probe=6d2b672b77) | Jan 25, 2023 |
| ASRock        | 775XFire-VSTA               | [e80788f790](https://linux-hardware.org/?probe=e80788f790) | Jan 24, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [dcecec2239](https://linux-hardware.org/?probe=dcecec2239) | Jan 22, 2023 |
| Gigabyte      | N3050ND3H                   | [1663928526](https://linux-hardware.org/?probe=1663928526) | Jan 21, 2023 |
| ASUSTek       | Z77-A                       | [10081492a7](https://linux-hardware.org/?probe=10081492a7) | Jan 19, 2023 |
| ASUSTek       | C60M1-I                     | [defd3912ae](https://linux-hardware.org/?probe=defd3912ae) | Jan 18, 2023 |
| Unknown       | HX90                        | [2b034e44e2](https://linux-hardware.org/?probe=2b034e44e2) | Jan 18, 2023 |
| Medion        | MS-7621                     | [67b535d88f](https://linux-hardware.org/?probe=67b535d88f) | Jan 18, 2023 |
| Gigabyte      | F2A55M-HD2                  | [74a62575d2](https://linux-hardware.org/?probe=74a62575d2) | Jan 17, 2023 |
| ASUSTek       | P8B75-V                     | [276102bb1a](https://linux-hardware.org/?probe=276102bb1a) | Jan 16, 2023 |
| Lenovo        | SDK0F82993 WIN              | [48f294dfb4](https://linux-hardware.org/?probe=48f294dfb4) | Jan 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [291dceb273](https://linux-hardware.org/?probe=291dceb273) | Jan 14, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [79d2961429](https://linux-hardware.org/?probe=79d2961429) | Jan 14, 2023 |
| HP            | 8054                        | [faf1c97cea](https://linux-hardware.org/?probe=faf1c97cea) | Jan 14, 2023 |
| HP            | 18E5                        | [614faa708b](https://linux-hardware.org/?probe=614faa708b) | Jan 14, 2023 |
| Pegatron      | IPM41-D3                    | [23a918874b](https://linux-hardware.org/?probe=23a918874b) | Jan 14, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [12f29d53ba](https://linux-hardware.org/?probe=12f29d53ba) | Jan 13, 2023 |
| Gigabyte      | H81M-S2PV                   | [72e7e2e1cf](https://linux-hardware.org/?probe=72e7e2e1cf) | Jan 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [805d82d697](https://linux-hardware.org/?probe=805d82d697) | Jan 10, 2023 |
| Gigabyte      | H170-D3H-CF                 | [8064745798](https://linux-hardware.org/?probe=8064745798) | Jan 10, 2023 |
| HP            | 0AA4h                       | [e0776de36f](https://linux-hardware.org/?probe=e0776de36f) | Jan 09, 2023 |
| HP            | 802F                        | [1dd3655605](https://linux-hardware.org/?probe=1dd3655605) | Jan 09, 2023 |
| Gigabyte      | Z68XP-UD3                   | [e2f62062de](https://linux-hardware.org/?probe=e2f62062de) | Jan 09, 2023 |
| Dell          | 0654JC A01                  | [c3016e1823](https://linux-hardware.org/?probe=c3016e1823) | Jan 09, 2023 |
| HP            | 8265                        | [83897e98cf](https://linux-hardware.org/?probe=83897e98cf) | Jan 08, 2023 |
| MSI           | 990XA-GD55                  | [b4525a8431](https://linux-hardware.org/?probe=b4525a8431) | Jan 08, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [c1c8654cde](https://linux-hardware.org/?probe=c1c8654cde) | Jan 07, 2023 |
| Acer          | Veriton N4640G              | [3392dd3c90](https://linux-hardware.org/?probe=3392dd3c90) | Jan 07, 2023 |
| Alienware     | 04VWF2 A02                  | [15f4ed4e31](https://linux-hardware.org/?probe=15f4ed4e31) | Jan 07, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ddeffc27a7](https://linux-hardware.org/?probe=ddeffc27a7) | Jan 05, 2023 |
| Pegatron      | 2AC3                        | [4ce129e600](https://linux-hardware.org/?probe=4ce129e600) | Jan 05, 2023 |
| Dell          | 0M5DCD A00                  | [c64a1198cd](https://linux-hardware.org/?probe=c64a1198cd) | Jan 04, 2023 |
| MSI           | A88X-G45 GAMING             | [1caf5c85d9](https://linux-hardware.org/?probe=1caf5c85d9) | Jan 04, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | [55627fc077](https://linux-hardware.org/?probe=55627fc077) | Jan 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [5f0eeeb9e7](https://linux-hardware.org/?probe=5f0eeeb9e7) | Jan 03, 2023 |
| Dell          | 0XCR8D A03                  | [faccba61cf](https://linux-hardware.org/?probe=faccba61cf) | Jan 03, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [afe5105302](https://linux-hardware.org/?probe=afe5105302) | Jan 03, 2023 |
| ASUSTek       | Berkeley                    | [746d7be693](https://linux-hardware.org/?probe=746d7be693) | Jan 03, 2023 |
| Dell          | 0MM599                      | [95763443e3](https://linux-hardware.org/?probe=95763443e3) | Jan 03, 2023 |
| ASRock        | B450M-HDV R4.0              | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| Gigabyte      | H61M-S2PV                   | [85ad98c994](https://linux-hardware.org/?probe=85ad98c994) | Jan 02, 2023 |
| AZW           | MINI S                      | [ad7c4329eb](https://linux-hardware.org/?probe=ad7c4329eb) | Jan 02, 2023 |
| Gigabyte      | B550M DS3H                  | [509cc939cc](https://linux-hardware.org/?probe=509cc939cc) | Jan 01, 2023 |
| OEM           | Intel H81                   | [1700a7a4c7](https://linux-hardware.org/?probe=1700a7a4c7) | Jan 01, 2023 |
| Gigabyte      | B365 HD3                    | [195240c264](https://linux-hardware.org/?probe=195240c264) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | UN45                        | [bde2e2efb1](https://linux-hardware.org/?probe=bde2e2efb1) | Dec 31, 2022 |
| MSI           | MS-7502 Fab D               | [9126e1035f](https://linux-hardware.org/?probe=9126e1035f) | Dec 31, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [b0dd8fc6b5](https://linux-hardware.org/?probe=b0dd8fc6b5) | Dec 31, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [3258ffa0c1](https://linux-hardware.org/?probe=3258ffa0c1) | Dec 29, 2022 |
| Gigabyte      | H61M-D2H                    | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| MSI           | Z97 PC Mate                 | [1b7e70ab6e](https://linux-hardware.org/?probe=1b7e70ab6e) | Dec 29, 2022 |
| ASUSTek       | P5K SE/EPU                  | [3f0c89985c](https://linux-hardware.org/?probe=3f0c89985c) | Dec 29, 2022 |
| Gigabyte      | MJPLNBB-00                  | [879a5b77ff](https://linux-hardware.org/?probe=879a5b77ff) | Dec 28, 2022 |
| Dell          | 0HN7XN A01                  | [43a0d87199](https://linux-hardware.org/?probe=43a0d87199) | Dec 28, 2022 |
| Pegatron      | APX85-GS                    | [82db9f15c6](https://linux-hardware.org/?probe=82db9f15c6) | Dec 27, 2022 |
| Acer          | Aspire TC-865 V:1.1         | [0c8add55fe](https://linux-hardware.org/?probe=0c8add55fe) | Dec 27, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [bc68280036](https://linux-hardware.org/?probe=bc68280036) | Dec 26, 2022 |
| Lenovo        | SHARKBAY NOK                | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| Gigabyte      | G41MT-S2PT                  | [14611d6c99](https://linux-hardware.org/?probe=14611d6c99) | Dec 26, 2022 |
| HP            | 2AF7                        | [96344d97ba](https://linux-hardware.org/?probe=96344d97ba) | Dec 26, 2022 |
| Gigabyte      | B450M S2H                   | [500abd4186](https://linux-hardware.org/?probe=500abd4186) | Dec 25, 2022 |
| ASUSTek       | NARRA3                      | [cc0a64d0df](https://linux-hardware.org/?probe=cc0a64d0df) | Dec 25, 2022 |
| Pegatron      | IPPPV-D3G                   | [4d1a2299dc](https://linux-hardware.org/?probe=4d1a2299dc) | Dec 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [9e269ee2a4](https://linux-hardware.org/?probe=9e269ee2a4) | Dec 24, 2022 |
| ASRock        | FM2A68M-DG3+                | [11eb39826a](https://linux-hardware.org/?probe=11eb39826a) | Dec 24, 2022 |
| Dell          | 0J3C2F A00                  | [f993ebb9ed](https://linux-hardware.org/?probe=f993ebb9ed) | Dec 23, 2022 |
| MSI           | 880GM-E41                   | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | [561b98afc3](https://linux-hardware.org/?probe=561b98afc3) | Dec 23, 2022 |
| Dell          | 0JJW8N A03                  | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| ASRock        | FM2A88M-HD+                 | [18b83ae613](https://linux-hardware.org/?probe=18b83ae613) | Dec 22, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [003ac98d7f](https://linux-hardware.org/?probe=003ac98d7f) | Dec 21, 2022 |
| PERTOSA       | GA-H110TN-M                 | [048d8cca49](https://linux-hardware.org/?probe=048d8cca49) | Dec 21, 2022 |
| Dell          | 0VHWTR A01                  | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| ECS           | G31T-M7                     | [327ac25b68](https://linux-hardware.org/?probe=327ac25b68) | Dec 20, 2022 |
| Gigabyte      | 945GCMX-S2                  | [3b9937e6df](https://linux-hardware.org/?probe=3b9937e6df) | Dec 20, 2022 |
| MSI           | H81M-E34                    | [3aa811568d](https://linux-hardware.org/?probe=3aa811568d) | Dec 19, 2022 |
| ASUSTek       | P5QL PRO                    | [5f3343c803](https://linux-hardware.org/?probe=5f3343c803) | Dec 19, 2022 |
| Gigabyte      | H61M-DS2                    | [b5c4e6cf61](https://linux-hardware.org/?probe=b5c4e6cf61) | Dec 19, 2022 |
| Dell          | 0M858N A00                  | [e46a95080d](https://linux-hardware.org/?probe=e46a95080d) | Dec 18, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [71ebf721cc](https://linux-hardware.org/?probe=71ebf721cc) | Dec 17, 2022 |
| HP            | 8055                        | [6c7fa83dc9](https://linux-hardware.org/?probe=6c7fa83dc9) | Dec 17, 2022 |
| Dell          | 0RW203                      | [2f5bede488](https://linux-hardware.org/?probe=2f5bede488) | Dec 16, 2022 |
| Gigabyte      | F2A85X-UP4                  | [80358a5ba1](https://linux-hardware.org/?probe=80358a5ba1) | Dec 15, 2022 |
| Acer          | Veriton N2620G              | [a626bf668e](https://linux-hardware.org/?probe=a626bf668e) | Dec 15, 2022 |
| Toshiba       | STI 006998G                 | [a41e0d92a7](https://linux-hardware.org/?probe=a41e0d92a7) | Dec 15, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [ffe60f958c](https://linux-hardware.org/?probe=ffe60f958c) | Dec 15, 2022 |
| Dell          | 0FR6WH A01                  | [46d6c645fe](https://linux-hardware.org/?probe=46d6c645fe) | Dec 15, 2022 |
| Gigabyte      | F2A68HM-H                   | [f18234034f](https://linux-hardware.org/?probe=f18234034f) | Dec 15, 2022 |
| HP            | 2AFB                        | [4c57ea0ee7](https://linux-hardware.org/?probe=4c57ea0ee7) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [587fac961e](https://linux-hardware.org/?probe=587fac961e) | Dec 15, 2022 |
| Dell          | 0VD92X A00                  | [9feb549665](https://linux-hardware.org/?probe=9feb549665) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0a564c9f0f](https://linux-hardware.org/?probe=0a564c9f0f) | Dec 14, 2022 |
| Datto         | SSD                         | [a9bff0a51c](https://linux-hardware.org/?probe=a9bff0a51c) | Dec 14, 2022 |
| HP            | 304Ah                       | [d8b600f39e](https://linux-hardware.org/?probe=d8b600f39e) | Dec 13, 2022 |
| ECS           | H61H2-M2                    | [8525777743](https://linux-hardware.org/?probe=8525777743) | Dec 13, 2022 |
| Dell          | 0T10XW A02                  | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| ASUSTek       | Z10PH-D16 Series            | [18911cf243](https://linux-hardware.org/?probe=18911cf243) | Dec 13, 2022 |
| Gigabyte      | H310M S2V                   | [6895902fe7](https://linux-hardware.org/?probe=6895902fe7) | Dec 12, 2022 |
| ASUSTek       | AM1M-A                      | [260a382d54](https://linux-hardware.org/?probe=260a382d54) | Dec 12, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [62f6fd5f8d](https://linux-hardware.org/?probe=62f6fd5f8d) | Dec 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [9537bff125](https://linux-hardware.org/?probe=9537bff125) | Dec 11, 2022 |
| Dell          | 0KG317                      | [cf7f697a0a](https://linux-hardware.org/?probe=cf7f697a0a) | Dec 11, 2022 |
| ASUSTek       | P8Z77-V LX                  | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| Dell          | 01TKCC A01                  | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| HP            | 18E7                        | [9759493e06](https://linux-hardware.org/?probe=9759493e06) | Dec 09, 2022 |
| ASRock        | 945GCM-S                    | [926787ea67](https://linux-hardware.org/?probe=926787ea67) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| Dell          | 0P301D A02                  | [8ab7a916f1](https://linux-hardware.org/?probe=8ab7a916f1) | Dec 08, 2022 |
| MSI           | 760GM-P23                   | [29337f7359](https://linux-hardware.org/?probe=29337f7359) | Dec 08, 2022 |
| ASRock        | B550 Taichi                 | [0203e79add](https://linux-hardware.org/?probe=0203e79add) | Dec 08, 2022 |
| Gigabyte      | Z370M D3H-CF                | [dabda33265](https://linux-hardware.org/?probe=dabda33265) | Dec 07, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [c3fc86b5d4](https://linux-hardware.org/?probe=c3fc86b5d4) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [664d064b07](https://linux-hardware.org/?probe=664d064b07) | Dec 06, 2022 |
| Lenovo        | 0x36A017AA 31900058 STD     | [ccc212b757](https://linux-hardware.org/?probe=ccc212b757) | Dec 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| Intel         | HURONRIVER                  | [d8a4f4a923](https://linux-hardware.org/?probe=d8a4f4a923) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| ECS           | 945P/PL-A                   | [8db8eec28d](https://linux-hardware.org/?probe=8db8eec28d) | Dec 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [fa3aeacc17](https://linux-hardware.org/?probe=fa3aeacc17) | Dec 05, 2022 |
| Dell          | 0M863N A01                  | [ee8183087b](https://linux-hardware.org/?probe=ee8183087b) | Dec 04, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [e98fcde376](https://linux-hardware.org/?probe=e98fcde376) | Dec 04, 2022 |
| Lenovo        | SHARKBAY NOK                | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [1dbda8e648](https://linux-hardware.org/?probe=1dbda8e648) | Dec 04, 2022 |
| Acer          | Aspire X3950                | [96044c1932](https://linux-hardware.org/?probe=96044c1932) | Dec 03, 2022 |
| ASUSTek       | H97-PLUS                    | [c79b15a3cf](https://linux-hardware.org/?probe=c79b15a3cf) | Dec 03, 2022 |
| HP            | 8648                        | [79673ee467](https://linux-hardware.org/?probe=79673ee467) | Dec 02, 2022 |
| ASUSTek       | P7P55D PRO                  | [b566591b3c](https://linux-hardware.org/?probe=b566591b3c) | Dec 02, 2022 |
| ASUSTek       | M5A97 PLUS                  | [63820e3937](https://linux-hardware.org/?probe=63820e3937) | Dec 01, 2022 |
| ASUSTek       | PRIME B250M-K               | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| Medion        | MS-7748                     | [0e92aa55ca](https://linux-hardware.org/?probe=0e92aa55ca) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| Medion        | MS-7800                     | [a5658a6933](https://linux-hardware.org/?probe=a5658a6933) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | [1d20e4ba6d](https://linux-hardware.org/?probe=1d20e4ba6d) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| ECS           | 945P/PL-A                   | [ff47651dd8](https://linux-hardware.org/?probe=ff47651dd8) | Nov 29, 2022 |
| Biostar       | H81MHV3 5.0                 | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Gigabyte      | B450 AORUS M                | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| ASRock        | B550M-ITX/ac                | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | [c218724cb4](https://linux-hardware.org/?probe=c218724cb4) | Nov 27, 2022 |
| MSI           | Z77MA-G45                   | [feb165c344](https://linux-hardware.org/?probe=feb165c344) | Nov 27, 2022 |
| ASRock        | A88M-G                      | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| MSI           | P55-CD53                    | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| HP            | 3397                        | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [9419d2017e](https://linux-hardware.org/?probe=9419d2017e) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2L                   | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| HP            | 0AECh D                     | [857616948b](https://linux-hardware.org/?probe=857616948b) | Nov 26, 2022 |
| HP            | 1589                        | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | [7948a35f59](https://linux-hardware.org/?probe=7948a35f59) | Nov 25, 2022 |
| HP            | 2215                        | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| Wistron       | ProLiant ML110 G6           | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| Foxconn       | 2A92                        | [e21715c047](https://linux-hardware.org/?probe=e21715c047) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| Foxconn       | 2ADA                        | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| Wistron       | ProLiant ML110 G5           | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| Dell          | 0M863N A01                  | [ca7e5eab8d](https://linux-hardware.org/?probe=ca7e5eab8d) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| Intel         | DG41TY AAE47335-302         | [ae2fb8d0b3](https://linux-hardware.org/?probe=ae2fb8d0b3) | Nov 22, 2022 |
| HP            | 3399                        | [bce6df1ffb](https://linux-hardware.org/?probe=bce6df1ffb) | Nov 21, 2022 |
| ASUSTek       | F1A55-M LE                  | [f2120128c1](https://linux-hardware.org/?probe=f2120128c1) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASRock        | B450M Steel Legend          | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Pegatron      | NARRA5                      | [d8632e2872](https://linux-hardware.org/?probe=d8632e2872) | Nov 21, 2022 |
| ASRock        | P67 Extreme4                | [569fd8178d](https://linux-hardware.org/?probe=569fd8178d) | Nov 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [049f06f11d](https://linux-hardware.org/?probe=049f06f11d) | Nov 21, 2022 |
| AZW           | SEi                         | [a8e813c483](https://linux-hardware.org/?probe=a8e813c483) | Nov 21, 2022 |
| Dell          | 00NNT0 A00                  | [c25787d8b9](https://linux-hardware.org/?probe=c25787d8b9) | Nov 20, 2022 |
| ASUSTek       | H81M-PLUS                   | [880e6565e8](https://linux-hardware.org/?probe=880e6565e8) | Nov 20, 2022 |
| ASUSTek       | Z97-C                       | [733140c078](https://linux-hardware.org/?probe=733140c078) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI             | [5b31194732](https://linux-hardware.org/?probe=5b31194732) | Nov 20, 2022 |
| Shuttle       | FS61                        | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| Pegatron      | 2A94h                       | [be99475703](https://linux-hardware.org/?probe=be99475703) | Nov 19, 2022 |
| ECS           | G41T-M7                     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Intel         | X99                         | [c95c1d173b](https://linux-hardware.org/?probe=c95c1d173b) | Nov 18, 2022 |
| TPV-INVENT... | 2AC6 A01                    | [04b3ba4242](https://linux-hardware.org/?probe=04b3ba4242) | Nov 18, 2022 |
| Gigabyte      | 970A-DS3P                   | [fc7b21bd04](https://linux-hardware.org/?probe=fc7b21bd04) | Nov 18, 2022 |
| Gigabyte      | A520M H                     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Huanan        | X99-8M-F V1.1               | [b1d1b0ad4c](https://linux-hardware.org/?probe=b1d1b0ad4c) | Nov 18, 2022 |
| ASUSTek       | P5KPL/1600                  | [24b13d1967](https://linux-hardware.org/?probe=24b13d1967) | Nov 16, 2022 |
| HP            | 843B                        | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| Intel         | H61                         | [faeac27433](https://linux-hardware.org/?probe=faeac27433) | Nov 16, 2022 |
| Medion        | MS-7728                     | [813d86814d](https://linux-hardware.org/?probe=813d86814d) | Nov 16, 2022 |
| Acer          | Veriton N4630G              | [f4566a57a9](https://linux-hardware.org/?probe=f4566a57a9) | Nov 16, 2022 |
| ALDO          | C2016-BSWI-D2               | [0e4c4c6806](https://linux-hardware.org/?probe=0e4c4c6806) | Nov 16, 2022 |
| AZW           | Gemini M                    | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| ASUSTek       | H81M-A                      | [ff63827781](https://linux-hardware.org/?probe=ff63827781) | Nov 15, 2022 |
| ASRock        | B450M Steel Legend          | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| HP            | 22F8                        | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | [2d904e2be7](https://linux-hardware.org/?probe=2d904e2be7) | Nov 13, 2022 |
| HP            | 84FD                        | [6ee4b6828c](https://linux-hardware.org/?probe=6ee4b6828c) | Nov 13, 2022 |
| Deltron       | H81H3-M4                    | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| MSI           | H97 GUARD-PRO               | [3ea9d7a74a](https://linux-hardware.org/?probe=3ea9d7a74a) | Nov 13, 2022 |
| Gigabyte      | H87-HD3                     | [e5a8d4700d](https://linux-hardware.org/?probe=e5a8d4700d) | Nov 12, 2022 |
| ASRock        | B450M Pro4 R2.0             | [c5952a73e7](https://linux-hardware.org/?probe=c5952a73e7) | Nov 12, 2022 |
| ASUSTek       | H81M-K                      | [052f42f29a](https://linux-hardware.org/?probe=052f42f29a) | Nov 12, 2022 |
| ASUSTek       | P5K SE/EPU                  | [d5e58b3718](https://linux-hardware.org/?probe=d5e58b3718) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| ASRock        | B365M Pro4-F                | [aa006ea111](https://linux-hardware.org/?probe=aa006ea111) | Nov 10, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [4488e0a71a](https://linux-hardware.org/?probe=4488e0a71a) | Nov 10, 2022 |
| Acer          | RS880M05                    | [cb216f090c](https://linux-hardware.org/?probe=cb216f090c) | Nov 09, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [fb87099a0d](https://linux-hardware.org/?probe=fb87099a0d) | Nov 09, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [ac916f47fc](https://linux-hardware.org/?probe=ac916f47fc) | Nov 08, 2022 |
| ASUSTek       | P5E-VM SE                   | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| Acer          | Aspire X1700                | [764516b8f0](https://linux-hardware.org/?probe=764516b8f0) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| ASRock        | Z170 Extreme4               | [f0b56da15d](https://linux-hardware.org/?probe=f0b56da15d) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [09c5b6e39e](https://linux-hardware.org/?probe=09c5b6e39e) | Nov 06, 2022 |
| Pegatron      | 2AE3                        | [19ae75aacc](https://linux-hardware.org/?probe=19ae75aacc) | Nov 06, 2022 |
| ASRock        | 4CoreDual-SATA2             | [e1a81edea7](https://linux-hardware.org/?probe=e1a81edea7) | Nov 05, 2022 |
| MSI           | GF615M-P33                  | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| HP            | 2820h                       | [6378a2e9c3](https://linux-hardware.org/?probe=6378a2e9c3) | Nov 05, 2022 |
| VS Company    | MCP61M                      | [ef6adc510d](https://linux-hardware.org/?probe=ef6adc510d) | Nov 05, 2022 |
| ASUSTek       | H170I-PLUS D3               | [74df37995c](https://linux-hardware.org/?probe=74df37995c) | Nov 04, 2022 |
| ASUSTek       | PRIME B365M-K               | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| Acer          | Aspire X1430                | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| ASUSTek       | M4A78 PLUS                  | [bac044cd22](https://linux-hardware.org/?probe=bac044cd22) | Oct 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | [c23efa8caa](https://linux-hardware.org/?probe=c23efa8caa) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Apple         | Mac-F221BEC8                | [12b6232cdd](https://linux-hardware.org/?probe=12b6232cdd) | Oct 30, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [2a7d6b757b](https://linux-hardware.org/?probe=2a7d6b757b) | Oct 29, 2022 |
| MSI           | P45 Platinum                | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| ASUSTek       | M5A87                       | [88e6b582c9](https://linux-hardware.org/?probe=88e6b582c9) | Oct 28, 2022 |
| Dell          | 0WMJ54 A01                  | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| Unknown       | Unknown                     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| ASUSTek       | P8B75-V                     | [ca5c26654a](https://linux-hardware.org/?probe=ca5c26654a) | Oct 27, 2022 |
| ASRock        | B550M-HDV                   | [4d5068a3be](https://linux-hardware.org/?probe=4d5068a3be) | Oct 27, 2022 |
| Acer          | Veriton M275                | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Dell          | 0WR7PY A03                  | [fa0daeab26](https://linux-hardware.org/?probe=fa0daeab26) | Oct 26, 2022 |
| Acer          | Veriton NBU                 | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| Gigabyte      | G41MT-S2PT                  | [2fb43f4be2](https://linux-hardware.org/?probe=2fb43f4be2) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | [218d55e0ca](https://linux-hardware.org/?probe=218d55e0ca) | Oct 25, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| Dell          | 0GX297                      | [a047bbd7a0](https://linux-hardware.org/?probe=a047bbd7a0) | Oct 24, 2022 |
| ASRock        | N68-VS3 UCC                 | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Gigabyte      | H310M S2H x.x               | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| ASUSTek       | P5QL-E                      | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| Acer          | WMCP78M                     | [f4e3945dea](https://linux-hardware.org/?probe=f4e3945dea) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| ASRock        | B450M Pro4                  | [12b83ecfd4](https://linux-hardware.org/?probe=12b83ecfd4) | Oct 22, 2022 |
| Dell          | 0HX555                      | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| Philco        | DTC-A55                     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| Acer          | WG43M                       | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Gigabyte      | GA-790FXTA-UD5              | [78218a5b63](https://linux-hardware.org/?probe=78218a5b63) | Oct 21, 2022 |
| MSI           | H61M-P20                    | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6c32002395](https://linux-hardware.org/?probe=6c32002395) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| HP            | 1825                        | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| Dell          | 0M5DCD A00                  | [e14791bb51](https://linux-hardware.org/?probe=e14791bb51) | Oct 19, 2022 |
| HP            | 805D                        | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| Intel         | DH61BF AAG81311-101         | [770d8bf876](https://linux-hardware.org/?probe=770d8bf876) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| ASUSTek       | P5KPL-E                     | [2f1e1cbbf4](https://linux-hardware.org/?probe=2f1e1cbbf4) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | [5823a0c5d0](https://linux-hardware.org/?probe=5823a0c5d0) | Oct 18, 2022 |
| Dell          | 02YYK5 A01                  | [5872b35f8c](https://linux-hardware.org/?probe=5872b35f8c) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| ASRock        | Z87 Pro3                    | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Dell          | 0XFWHV A00                  | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| HP            | 1850                        | [eda9bb7861](https://linux-hardware.org/?probe=eda9bb7861) | Oct 15, 2022 |
| Gigabyte      | H61M-D2H                    | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| Intel         | DP45SG AAE27733-403         | [f391a78f4d](https://linux-hardware.org/?probe=f391a78f4d) | Oct 15, 2022 |
| ASUSTek       | PRIME H510M-A               | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| Gigabyte      | F2A55M-DS2                  | [1feb9942e8](https://linux-hardware.org/?probe=1feb9942e8) | Oct 14, 2022 |
| ASUSTek       | PRIME H410M-A               | [8dc5e6f530](https://linux-hardware.org/?probe=8dc5e6f530) | Oct 14, 2022 |
| ASUSTek       | PRIME B450M-A II            | [6144d2247a](https://linux-hardware.org/?probe=6144d2247a) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| HP            | 1497                        | [ff6d690da4](https://linux-hardware.org/?probe=ff6d690da4) | Oct 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| ASUSTek       | PRIME H410M-A               | [dc990d0395](https://linux-hardware.org/?probe=dc990d0395) | Oct 12, 2022 |
| AMD           | A88                         | [1ee2502537](https://linux-hardware.org/?probe=1ee2502537) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| Dell          | 0T656F A01                  | [1680fa50c0](https://linux-hardware.org/?probe=1680fa50c0) | Oct 11, 2022 |
| HP            | 2171                        | [105af7e899](https://linux-hardware.org/?probe=105af7e899) | Oct 11, 2022 |
| Gigabyte      | B75M-D3H                    | [4bc40092b2](https://linux-hardware.org/?probe=4bc40092b2) | Oct 11, 2022 |
| Lenovo        | ThinkCentre M58 7359WES     | [1c00ee45c1](https://linux-hardware.org/?probe=1c00ee45c1) | Oct 11, 2022 |
| ASRock        | G41C-GS R2.0                | [92ab2501ea](https://linux-hardware.org/?probe=92ab2501ea) | Oct 11, 2022 |
| Acer          | Aspire XC-230               | [d213bca85f](https://linux-hardware.org/?probe=d213bca85f) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| ASUSTek       | PRIME H410I-PLUS            | [10709dd95e](https://linux-hardware.org/?probe=10709dd95e) | Oct 10, 2022 |
| Gigabyte      | F2A58M-HD2                  | [a219433035](https://linux-hardware.org/?probe=a219433035) | Oct 10, 2022 |
| AZW           | U59                         | [8300f61a93](https://linux-hardware.org/?probe=8300f61a93) | Oct 10, 2022 |
| HP            | 805D                        | [8938f51322](https://linux-hardware.org/?probe=8938f51322) | Oct 09, 2022 |
| Lenovo        | Dory CRB                    | [33ae78632a](https://linux-hardware.org/?probe=33ae78632a) | Oct 09, 2022 |
| ASUSTek       | PRIME Z590-P                | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| Chuwi         | RZBOX                       | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| MSI           | A55M-P33                    | [127b8f180e](https://linux-hardware.org/?probe=127b8f180e) | Oct 08, 2022 |
| ASRock        | M3N78D FX                   | [e40ba3988f](https://linux-hardware.org/?probe=e40ba3988f) | Oct 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [feb96964b1](https://linux-hardware.org/?probe=feb96964b1) | Oct 08, 2022 |
| Dell          | 0MN1TX A01                  | [a9faf44fe8](https://linux-hardware.org/?probe=a9faf44fe8) | Oct 07, 2022 |
| MSI           | H110M PRO-VH PLUS           | [9dc72dc357](https://linux-hardware.org/?probe=9dc72dc357) | Oct 07, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [7a7bc387f4](https://linux-hardware.org/?probe=7a7bc387f4) | Oct 06, 2022 |
| Medion        | MS-7797                     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| ASUSTek       | M2V-MX                      | [55b3f7f6b0](https://linux-hardware.org/?probe=55b3f7f6b0) | Oct 06, 2022 |
| HP            | 18E4                        | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Dell          | 01TKCC A01                  | [65103a04c3](https://linux-hardware.org/?probe=65103a04c3) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| ASUSTek       | P5W DH Deluxe               | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Intel         | H55                         | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | [f6a6361e08](https://linux-hardware.org/?probe=f6a6361e08) | Oct 03, 2022 |
| ASRock        | G41C-GS R2.0                | [c6e6708366](https://linux-hardware.org/?probe=c6e6708366) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M58p 6234FB9    | [3c772e3e1d](https://linux-hardware.org/?probe=3c772e3e1d) | Oct 02, 2022 |
| MSI           | A75A-G35                    | [66b1d71092](https://linux-hardware.org/?probe=66b1d71092) | Oct 02, 2022 |
| Biostar       | A75MG                       | [ba1785b4b6](https://linux-hardware.org/?probe=ba1785b4b6) | Oct 02, 2022 |
| MSI           | B75MA-E33                   | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | [ce1567bb35](https://linux-hardware.org/?probe=ce1567bb35) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| MSI           | MS-7235                     | [838e2c27f1](https://linux-hardware.org/?probe=838e2c27f1) | Oct 01, 2022 |
| Lenovo        | 0x30F617AA NOK              | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| MSI           | B350M PRO-VDH               | [1a0d8b695d](https://linux-hardware.org/?probe=1a0d8b695d) | Oct 01, 2022 |
| Lenovo        | 3098 NOK                    | [a46521af41](https://linux-hardware.org/?probe=a46521af41) | Oct 01, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [982b143d73](https://linux-hardware.org/?probe=982b143d73) | Oct 01, 2022 |
| ASUSTek       | M5A78L-M LX                 | [d967f57569](https://linux-hardware.org/?probe=d967f57569) | Oct 01, 2022 |
| ASUSTek       | M5A87                       | [89ca067566](https://linux-hardware.org/?probe=89ca067566) | Oct 01, 2022 |
| Gigabyte      | GA-970A-D3                  | [8c24fa2271](https://linux-hardware.org/?probe=8c24fa2271) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| ASRock        | B450M Pro4-F                | [75b0aa3c75](https://linux-hardware.org/?probe=75b0aa3c75) | Sep 30, 2022 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | [a6b14fdcf3](https://linux-hardware.org/?probe=a6b14fdcf3) | Sep 30, 2022 |
| Acer          | Batman A01                  | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | PRIME B450M-A               | [cfe1aba7e6](https://linux-hardware.org/?probe=cfe1aba7e6) | Sep 30, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [66877298d4](https://linux-hardware.org/?probe=66877298d4) | Sep 30, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Corei... | [a40d59533c](https://linux-hardware.org/?probe=a40d59533c) | Sep 29, 2022 |
| Acer          | Veriton M275                | [f871926a8e](https://linux-hardware.org/?probe=f871926a8e) | Sep 29, 2022 |
| Intel         | DQ67SW AAG12527-310         | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | [5a7ad7dba9](https://linux-hardware.org/?probe=5a7ad7dba9) | Sep 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [3bafc34ffc](https://linux-hardware.org/?probe=3bafc34ffc) | Sep 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [8749a17d26](https://linux-hardware.org/?probe=8749a17d26) | Sep 25, 2022 |
| ASUSTek       | CM1740                      | [6ebc913933](https://linux-hardware.org/?probe=6ebc913933) | Sep 25, 2022 |
| Dell          | 0NV0M7 A02                  | [02925c7220](https://linux-hardware.org/?probe=02925c7220) | Sep 24, 2022 |
| MSI           | Z390-A PRO                  | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| ASRock        | X300M-STX                   | [c354f2b293](https://linux-hardware.org/?probe=c354f2b293) | Sep 24, 2022 |
| Intel         | DG41WV AAE90316-103         | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Dell          | 0M5DCD A00                  | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| Dell          | 0PTTT9 A00                  | [21bde061e9](https://linux-hardware.org/?probe=21bde061e9) | Sep 23, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| ASUSTek       | PRIME B560M-A AC            | [a99682c38d](https://linux-hardware.org/?probe=a99682c38d) | Sep 23, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| HP            | 1998                        | [5148539ae1](https://linux-hardware.org/?probe=5148539ae1) | Sep 21, 2022 |
| MACHINIST     | B75 PRO V1.0                | [752cb8efae](https://linux-hardware.org/?probe=752cb8efae) | Sep 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [a82f4ceccc](https://linux-hardware.org/?probe=a82f4ceccc) | Sep 20, 2022 |
| Lenovo        | 3728 SDK0R32862 WIN 3258... | [d78d85bde3](https://linux-hardware.org/?probe=d78d85bde3) | Sep 20, 2022 |
| HP            | 2B34                        | [a9e82bbb40](https://linux-hardware.org/?probe=a9e82bbb40) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| HP            | 2B29                        | [391e407d29](https://linux-hardware.org/?probe=391e407d29) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| HP            | 843F                        | [7694ed2ffa](https://linux-hardware.org/?probe=7694ed2ffa) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [f75308c465](https://linux-hardware.org/?probe=f75308c465) | Sep 17, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| HP            | 1495                        | [462389df36](https://linux-hardware.org/?probe=462389df36) | Sep 14, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [832824de54](https://linux-hardware.org/?probe=832824de54) | Sep 14, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [6ee9d3e2c4](https://linux-hardware.org/?probe=6ee9d3e2c4) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Gigabyte      | X570 AORUS PRO              | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| MSI           | Z97 MPOWER                  | [a98aedda05](https://linux-hardware.org/?probe=a98aedda05) | Sep 13, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [0937dcb89c](https://linux-hardware.org/?probe=0937dcb89c) | Sep 12, 2022 |
| ASRock        | X99 Taichi                  | [2eb979e980](https://linux-hardware.org/?probe=2eb979e980) | Sep 12, 2022 |
| Dell          | 0H8052                      | [1ade497706](https://linux-hardware.org/?probe=1ade497706) | Sep 12, 2022 |
| Gigabyte      | EX58-UD3R                   | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| Shuttle       | XH310V2                     | [c99efae947](https://linux-hardware.org/?probe=c99efae947) | Sep 12, 2022 |
| MSI           | MAG Z390M MORTAR            | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| HP            | 158B                        | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| HP            | 304Bh                       | [0a7bcbdd9e](https://linux-hardware.org/?probe=0a7bcbdd9e) | Sep 11, 2022 |
| MSI           | B560M PRO                   | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| MSI           | 0A48                        | [2619140b48](https://linux-hardware.org/?probe=2619140b48) | Sep 10, 2022 |
| Dell          | 01TKCC A01                  | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| ASUSTek       | P8B75-M LX                  | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
| Dell          | 03NVJ6 A00                  | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| ASRock        | G41M-VS3                    | [021bcda428](https://linux-hardware.org/?probe=021bcda428) | Sep 10, 2022 |
| Gigabyte      | Z68AP-D3                    | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| Dell          | 0J3C2F A00                  | [40c43aff10](https://linux-hardware.org/?probe=40c43aff10) | Sep 10, 2022 |
| Apple         | Mac-F221BEC8                | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [cd84312899](https://linux-hardware.org/?probe=cd84312899) | Sep 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [36b349b529](https://linux-hardware.org/?probe=36b349b529) | Sep 09, 2022 |
| Dell          | 0M5DCD A00                  | [1a5c8e32b7](https://linux-hardware.org/?probe=1a5c8e32b7) | Sep 09, 2022 |
| Gigabyte      | A520M DS3H                  | [036c262ad4](https://linux-hardware.org/?probe=036c262ad4) | Sep 08, 2022 |
| ASRock        | Z170 Extreme4               | [70e3d85420](https://linux-hardware.org/?probe=70e3d85420) | Sep 07, 2022 |
| MSI           | IONA                        | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| MSI           | A320M PRO-M2 V2             | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [8a66fbdadd](https://linux-hardware.org/?probe=8a66fbdadd) | Sep 06, 2022 |
| ECS           | GeForce 8000 series         | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [537708f71a](https://linux-hardware.org/?probe=537708f71a) | Sep 06, 2022 |
| MSI           | B350M PRO-VDH               | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| HP            | 8076                        | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| ASRock        | B450 Pro4                   | [4d5b865aed](https://linux-hardware.org/?probe=4d5b865aed) | Sep 05, 2022 |
| Unknown       | Unknown                     | [e2115bf207](https://linux-hardware.org/?probe=e2115bf207) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [b36d7be7c1](https://linux-hardware.org/?probe=b36d7be7c1) | Sep 04, 2022 |
| HP            | 304Bh                       | [d395dd6c91](https://linux-hardware.org/?probe=d395dd6c91) | Sep 04, 2022 |
| Gigabyte      | H97N-WIFI                   | [fb64be85f1](https://linux-hardware.org/?probe=fb64be85f1) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [792cbc3418](https://linux-hardware.org/?probe=792cbc3418) | Sep 04, 2022 |
| HP            | 8767 A                      | [33800541e3](https://linux-hardware.org/?probe=33800541e3) | Sep 04, 2022 |
| Gigabyte      | B560 AORUS PRO AX           | [fbd2e39516](https://linux-hardware.org/?probe=fbd2e39516) | Sep 04, 2022 |
| ECS           | H61H-G11/7.0                | [790b93cbee](https://linux-hardware.org/?probe=790b93cbee) | Sep 03, 2022 |
| Unknown       | Intel X79                   | [9e666e1530](https://linux-hardware.org/?probe=9e666e1530) | Sep 02, 2022 |
| HP            | 8053                        | [2e48f3f13e](https://linux-hardware.org/?probe=2e48f3f13e) | Sep 02, 2022 |
| Dell          | 0TP412                      | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| ASRock        | A320M-DVS R4.0              | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| Foxconn       | 2ABF                        | [c9a801a4d2](https://linux-hardware.org/?probe=c9a801a4d2) | Sep 01, 2022 |
| ASRock        | X99 Taichi                  | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| ASRock        | B550M-ITX/ac                | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| MSI           | H510M-A PRO                 | [120400698e](https://linux-hardware.org/?probe=120400698e) | Aug 31, 2022 |
| Vorke         | V1 Plus                     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI           | Z97 GAMING 7                | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| ASRock        | N68C-S UCC                  | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Gigabyte      | VM900M                      | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| Dell          | 0R230R A00                  | [0ea749e83c](https://linux-hardware.org/?probe=0ea749e83c) | Aug 30, 2022 |
| HP            | 0A60h                       | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [33aaa7baf4](https://linux-hardware.org/?probe=33aaa7baf4) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | [0099ab3432](https://linux-hardware.org/?probe=0099ab3432) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M58p 6234CL2    | [14449a705a](https://linux-hardware.org/?probe=14449a705a) | Aug 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| ASUSTek       | A88XM-A                     | [d8a4e4d954](https://linux-hardware.org/?probe=d8a4e4d954) | Aug 28, 2022 |
| Medion        | B460H6-EM                   | [91371e505d](https://linux-hardware.org/?probe=91371e505d) | Aug 28, 2022 |
| Gigabyte      | GA-MA78LMT-S2               | [a18db0fafd](https://linux-hardware.org/?probe=a18db0fafd) | Aug 27, 2022 |
| ASUSTek       | P8B WS                      | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [f74dc71ad8](https://linux-hardware.org/?probe=f74dc71ad8) | Aug 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [67712f11d9](https://linux-hardware.org/?probe=67712f11d9) | Aug 27, 2022 |
| ASUSTek       | PRIME Z390-A                | [459c7c1eee](https://linux-hardware.org/?probe=459c7c1eee) | Aug 27, 2022 |
| MSI           | G31TM-P21                   | [cf0bc232f5](https://linux-hardware.org/?probe=cf0bc232f5) | Aug 26, 2022 |
| ASRock        | FM2A68M-HD+                 | [22cc477cd2](https://linux-hardware.org/?probe=22cc477cd2) | Aug 26, 2022 |
| MSI           | 760GM-P21                   | [7e45cde899](https://linux-hardware.org/?probe=7e45cde899) | Aug 26, 2022 |
| HP            | 1497                        | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | M5A78L LE                   | [e4a6425675](https://linux-hardware.org/?probe=e4a6425675) | Aug 26, 2022 |
| Dell          | 0RJ290                      | [ca82162ed5](https://linux-hardware.org/?probe=ca82162ed5) | Aug 25, 2022 |
| Acer          | Aspire XC-710 V:1.1         | [0b76e0f97d](https://linux-hardware.org/?probe=0b76e0f97d) | Aug 25, 2022 |
| Foxconn       | H61M/H61M-S                 | [18e7da32e9](https://linux-hardware.org/?probe=18e7da32e9) | Aug 25, 2022 |
| ASRock        | N68C-GS4 FX                 | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| ASUSTek       | PRIME B350M-A               | [1c98247f4c](https://linux-hardware.org/?probe=1c98247f4c) | Aug 25, 2022 |
| OEM           | A320                        | [4dffd629cf](https://linux-hardware.org/?probe=4dffd629cf) | Aug 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d1cae6aca8](https://linux-hardware.org/?probe=d1cae6aca8) | Aug 24, 2022 |
| HP            | 21D0                        | [1bd58d519c](https://linux-hardware.org/?probe=1bd58d519c) | Aug 24, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | [e75751c55b](https://linux-hardware.org/?probe=e75751c55b) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Gigabyte      | F2A68HM-H                   | [c824203d0a](https://linux-hardware.org/?probe=c824203d0a) | Aug 24, 2022 |
| Dell          | 08HPGT A01                  | [744f838dc2](https://linux-hardware.org/?probe=744f838dc2) | Aug 24, 2022 |
| ICP / iEi     | B217 V1.0                   | [9b540ece9f](https://linux-hardware.org/?probe=9b540ece9f) | Aug 23, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [7dae220687](https://linux-hardware.org/?probe=7dae220687) | Aug 23, 2022 |
| Dell          | 0YJPT1 A00                  | [1de0aeba8f](https://linux-hardware.org/?probe=1de0aeba8f) | Aug 22, 2022 |
| ASUSTek       | PRIME Z390-P                | [ca7534d4dc](https://linux-hardware.org/?probe=ca7534d4dc) | Aug 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [fa5f1121d5](https://linux-hardware.org/?probe=fa5f1121d5) | Aug 22, 2022 |
| Intel         | H61                         | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| ASUSTek       | Z87-C                       | [8de83c544f](https://linux-hardware.org/?probe=8de83c544f) | Aug 21, 2022 |
| HP            | 1998                        | [69b6b04268](https://linux-hardware.org/?probe=69b6b04268) | Aug 21, 2022 |
| ASRock        | N68C-S UCC                  | [bb19c0586c](https://linux-hardware.org/?probe=bb19c0586c) | Aug 20, 2022 |
| Gigabyte      | B365M DS3H WIFI             | [142e25352d](https://linux-hardware.org/?probe=142e25352d) | Aug 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | [56a34e0816](https://linux-hardware.org/?probe=56a34e0816) | Aug 20, 2022 |
| ASUSTek       | P5KPL-SE                    | [2925e63a87](https://linux-hardware.org/?probe=2925e63a87) | Aug 20, 2022 |
| AZW           | MII-V                       | [59698f6b33](https://linux-hardware.org/?probe=59698f6b33) | Aug 20, 2022 |
| OEM           | Intel H81                   | [5e354c60d1](https://linux-hardware.org/?probe=5e354c60d1) | Aug 20, 2022 |
| ASUSTek       | P5KPL-VM                    | [803031cd3b](https://linux-hardware.org/?probe=803031cd3b) | Aug 19, 2022 |
| Gigabyte      | B450M S2H                   | [a0a7a845e3](https://linux-hardware.org/?probe=a0a7a845e3) | Aug 18, 2022 |
| Gigabyte      | P43-ES3G                    | [de6e02672c](https://linux-hardware.org/?probe=de6e02672c) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | [859884934f](https://linux-hardware.org/?probe=859884934f) | Aug 17, 2022 |
| Acer          | MRS600M                     | [ec4c10d06e](https://linux-hardware.org/?probe=ec4c10d06e) | Aug 17, 2022 |
| ASUSTek       | PRIME B250-PRO              | [870d7102f5](https://linux-hardware.org/?probe=870d7102f5) | Aug 17, 2022 |
| Gigabyte      | H410M S2 V2                 | [944a99ea66](https://linux-hardware.org/?probe=944a99ea66) | Aug 17, 2022 |
| Gigabyte      | H81M-S2PH                   | [c8f8e78df8](https://linux-hardware.org/?probe=c8f8e78df8) | Aug 17, 2022 |
| Gigabyte      | B460M DS3H                  | [2b97e09efa](https://linux-hardware.org/?probe=2b97e09efa) | Aug 17, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [7b3d6b544c](https://linux-hardware.org/?probe=7b3d6b544c) | Aug 16, 2022 |
| Dell          | 0T656F A01                  | [ec4014a549](https://linux-hardware.org/?probe=ec4014a549) | Aug 16, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [08e3444b3c](https://linux-hardware.org/?probe=08e3444b3c) | Aug 15, 2022 |
| HP            | 2AE2                        | [1fd0bb70dc](https://linux-hardware.org/?probe=1fd0bb70dc) | Aug 15, 2022 |
| Gigabyte      | P43-ES3G                    | [2b0691bddd](https://linux-hardware.org/?probe=2b0691bddd) | Aug 15, 2022 |
| Dell          | 0PC5F7 A03                  | [56ee42afe3](https://linux-hardware.org/?probe=56ee42afe3) | Aug 15, 2022 |
| Dell          | 0NC2VH A01                  | [170b178361](https://linux-hardware.org/?probe=170b178361) | Aug 15, 2022 |
| HP            | 18E7                        | [06374a6240](https://linux-hardware.org/?probe=06374a6240) | Aug 14, 2022 |
| ASRock        | 960GM-VGS3 FX               | [55c4e8059c](https://linux-hardware.org/?probe=55c4e8059c) | Aug 14, 2022 |
| MSI           | X570-A PRO                  | [30146876c6](https://linux-hardware.org/?probe=30146876c6) | Aug 14, 2022 |
| ASRock        | J3455-ITX                   | [4386fccad1](https://linux-hardware.org/?probe=4386fccad1) | Aug 14, 2022 |
| Lenovo        | SHARKBAY NOK                | [ee169e47b3](https://linux-hardware.org/?probe=ee169e47b3) | Aug 13, 2022 |
| Dell          | 08WKV3 A00                  | [4e57c20454](https://linux-hardware.org/?probe=4e57c20454) | Aug 13, 2022 |
| Lenovo        | ThinkCentre XXXX 739527G    | [ca5fe11e2c](https://linux-hardware.org/?probe=ca5fe11e2c) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | [fd41ccab04](https://linux-hardware.org/?probe=fd41ccab04) | Aug 13, 2022 |
| HP            | 1850                        | [33933e3e5d](https://linux-hardware.org/?probe=33933e3e5d) | Aug 12, 2022 |
| ASRock        | H61M-DGS                    | [50b7221c5a](https://linux-hardware.org/?probe=50b7221c5a) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A II            | [bc32ff70b7](https://linux-hardware.org/?probe=bc32ff70b7) | Aug 12, 2022 |
| Gigabyte      | EP35C-DS3R                  | [762d78160d](https://linux-hardware.org/?probe=762d78160d) | Aug 12, 2022 |
| MSI           | A68HM-E33 V2                | [2f3db9cd91](https://linux-hardware.org/?probe=2f3db9cd91) | Aug 12, 2022 |
| ASRock        | Z97M Pro4                   | [245d189a61](https://linux-hardware.org/?probe=245d189a61) | Aug 11, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [73bf30c596](https://linux-hardware.org/?probe=73bf30c596) | Aug 11, 2022 |
| Gigabyte      | P35-DS3L                    | [c765f5b81c](https://linux-hardware.org/?probe=c765f5b81c) | Aug 11, 2022 |
| Foxconn       | 2ABF                        | [3b20387bcc](https://linux-hardware.org/?probe=3b20387bcc) | Aug 10, 2022 |
| ASRock        | H81M-DGS                    | [31bdc504d4](https://linux-hardware.org/?probe=31bdc504d4) | Aug 10, 2022 |
| Dell          | 07KY25 A00                  | [676025f81a](https://linux-hardware.org/?probe=676025f81a) | Aug 10, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | [62d813423e](https://linux-hardware.org/?probe=62d813423e) | Aug 10, 2022 |
| MSI           | X470 GAMING M7 AC           | [58947090d5](https://linux-hardware.org/?probe=58947090d5) | Aug 09, 2022 |
| eMachines     | Veriton V2110               | [3492540d77](https://linux-hardware.org/?probe=3492540d77) | Aug 09, 2022 |
| ASRock        | AB350 Pro4                  | [2df31a9fbf](https://linux-hardware.org/?probe=2df31a9fbf) | Aug 09, 2022 |
| ASUSTek       | Z87-PRO                     | [89a77b442f](https://linux-hardware.org/?probe=89a77b442f) | Aug 09, 2022 |
| Gigabyte      | EP35-DS3P                   | [5c29aee903](https://linux-hardware.org/?probe=5c29aee903) | Aug 08, 2022 |
| ASUSTek       | AT3IONT-I DELUXE            | [642e31466d](https://linux-hardware.org/?probe=642e31466d) | Aug 08, 2022 |
| Dell          | 0782GW A01                  | [b3ebc3aed3](https://linux-hardware.org/?probe=b3ebc3aed3) | Aug 08, 2022 |
| HP            | 304Bh                       | [e1e3f301cb](https://linux-hardware.org/?probe=e1e3f301cb) | Aug 08, 2022 |
| Intel         | H61                         | [eabc8be629](https://linux-hardware.org/?probe=eabc8be629) | Aug 08, 2022 |
| Gigabyte      | H55M-UD2H                   | [4d6a861120](https://linux-hardware.org/?probe=4d6a861120) | Aug 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [95f444c24c](https://linux-hardware.org/?probe=95f444c24c) | Aug 07, 2022 |
| Gigabyte      | EP45-UD3R                   | [6c434341ce](https://linux-hardware.org/?probe=6c434341ce) | Aug 07, 2022 |
| ASUSTek       | M3A78 PRO                   | [0b63e92a55](https://linux-hardware.org/?probe=0b63e92a55) | Aug 07, 2022 |
| HP            | 2215                        | [75304ada6c](https://linux-hardware.org/?probe=75304ada6c) | Aug 06, 2022 |
| Toshiba       | STI 006998G                 | [3de3fa77fc](https://linux-hardware.org/?probe=3de3fa77fc) | Aug 06, 2022 |
| ASRock        | H110M-STX                   | [62b1924710](https://linux-hardware.org/?probe=62b1924710) | Aug 06, 2022 |
| Gigabyte      | A320M-H-CF                  | [4015089c1e](https://linux-hardware.org/?probe=4015089c1e) | Aug 06, 2022 |
| MSI           | 2A9C                        | [8913065613](https://linux-hardware.org/?probe=8913065613) | Aug 06, 2022 |
| Dell          | 0NV0M7 A02                  | [dbf000aacd](https://linux-hardware.org/?probe=dbf000aacd) | Aug 06, 2022 |
| Gigabyte      | A520M S2H                   | [daa1f68f01](https://linux-hardware.org/?probe=daa1f68f01) | Aug 06, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | [a722bef081](https://linux-hardware.org/?probe=a722bef081) | Aug 06, 2022 |
| MSI           | Z87-G43 GAMING              | [490239de9e](https://linux-hardware.org/?probe=490239de9e) | Aug 05, 2022 |
| Dell          | 0GY6Y8 A01                  | [1ad9e54625](https://linux-hardware.org/?probe=1ad9e54625) | Aug 05, 2022 |
| ASUSTek       | M2N68-AM SE2                | [b68c110fde](https://linux-hardware.org/?probe=b68c110fde) | Aug 05, 2022 |
| ASRock        | A300M-STX                   | [f6b820d15f](https://linux-hardware.org/?probe=f6b820d15f) | Aug 05, 2022 |
| ASRock        | H270M-ITX/ac                | [273c214064](https://linux-hardware.org/?probe=273c214064) | Aug 05, 2022 |
| Dell          | 0KG317                      | [65c105e2be](https://linux-hardware.org/?probe=65c105e2be) | Aug 04, 2022 |
| ASUSTek       | A68HM-K                     | [d5d981cf7b](https://linux-hardware.org/?probe=d5d981cf7b) | Aug 04, 2022 |
| ASUSTek       | H110M-K                     | [8c6442a868](https://linux-hardware.org/?probe=8c6442a868) | Aug 04, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [7893ade7cb](https://linux-hardware.org/?probe=7893ade7cb) | Aug 04, 2022 |
| ASUSTek       | PRIME B350M-E               | [f9e07e62c2](https://linux-hardware.org/?probe=f9e07e62c2) | Aug 04, 2022 |
| Unknown       | Unknown                     | [0725792da0](https://linux-hardware.org/?probe=0725792da0) | Aug 04, 2022 |
| Gigabyte      | B360M GAMING HD             | [95e1eb0fcb](https://linux-hardware.org/?probe=95e1eb0fcb) | Aug 03, 2022 |
| Lenovo        | 3102                        | [73e0fee2bc](https://linux-hardware.org/?probe=73e0fee2bc) | Aug 03, 2022 |
| Gigabyte      | Z170X-UD3-CF                | [450fee0496](https://linux-hardware.org/?probe=450fee0496) | Aug 03, 2022 |
| HP            | 2B29                        | [5fcf3a8320](https://linux-hardware.org/?probe=5fcf3a8320) | Aug 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [97dba8f5e3](https://linux-hardware.org/?probe=97dba8f5e3) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [6b790e8a9b](https://linux-hardware.org/?probe=6b790e8a9b) | Aug 02, 2022 |
| Acer          | EM61SM/EM61PM               | [1a35a6d7dc](https://linux-hardware.org/?probe=1a35a6d7dc) | Aug 02, 2022 |
| Foxconn       | 2ABF                        | [4f1fca6662](https://linux-hardware.org/?probe=4f1fca6662) | Aug 02, 2022 |
| ASUSTek       | P8H67                       | [508b0275e3](https://linux-hardware.org/?probe=508b0275e3) | Aug 02, 2022 |
| Gigabyte      | H61M-S2PH                   | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| Gigabyte      | H87-HD3                     | [daaf600950](https://linux-hardware.org/?probe=daaf600950) | Aug 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [b5fded6824](https://linux-hardware.org/?probe=b5fded6824) | Aug 01, 2022 |
| HP            | 339A                        | [251a764917](https://linux-hardware.org/?probe=251a764917) | Aug 01, 2022 |
| ASUSTek       | P7P55D-E PRO                | [d58be7b6d1](https://linux-hardware.org/?probe=d58be7b6d1) | Aug 01, 2022 |
| MSI           | Z590-A PRO                  | [7051f56dda](https://linux-hardware.org/?probe=7051f56dda) | Aug 01, 2022 |
| MSI           | Z77A-GD65                   | [fcadad42a5](https://linux-hardware.org/?probe=fcadad42a5) | Aug 01, 2022 |
| HP            | 843F                        | [eeba83fecb](https://linux-hardware.org/?probe=eeba83fecb) | Aug 01, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [7e6cd7bcb3](https://linux-hardware.org/?probe=7e6cd7bcb3) | Jul 31, 2022 |
| ASUSTek       | P8B75-M LX                  | [653f46c8e3](https://linux-hardware.org/?probe=653f46c8e3) | Jul 31, 2022 |
| ASUSTek       | P5G41C-M LX                 | [4e30dc6361](https://linux-hardware.org/?probe=4e30dc6361) | Jul 31, 2022 |
| MSI           | B85M-P33                    | [6e9af1d1e4](https://linux-hardware.org/?probe=6e9af1d1e4) | Jul 31, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [cb7c9442d6](https://linux-hardware.org/?probe=cb7c9442d6) | Jul 31, 2022 |
| Unknown       | Unknown                     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| ASUSTek       | Z97-A-USB31                 | [25db3983fe](https://linux-hardware.org/?probe=25db3983fe) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [10ece2cb6c](https://linux-hardware.org/?probe=10ece2cb6c) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [edd98c5418](https://linux-hardware.org/?probe=edd98c5418) | Jul 30, 2022 |
| ASRock        | J5040-ITX                   | [2cc4fd5d75](https://linux-hardware.org/?probe=2cc4fd5d75) | Jul 30, 2022 |
| ASUSTek       | M3A78 PRO                   | [c30fca013c](https://linux-hardware.org/?probe=c30fca013c) | Jul 30, 2022 |
| HP            | 2ADC                        | [86608333bc](https://linux-hardware.org/?probe=86608333bc) | Jul 29, 2022 |
| PCWare        | IPMH61R2                    | [b3245af28d](https://linux-hardware.org/?probe=b3245af28d) | Jul 29, 2022 |
| HP            | 0AA0h                       | [5d21c69a99](https://linux-hardware.org/?probe=5d21c69a99) | Jul 29, 2022 |
| HP            | 18E4                        | [d13265fa57](https://linux-hardware.org/?probe=d13265fa57) | Jul 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e1d666e84a](https://linux-hardware.org/?probe=e1d666e84a) | Jul 29, 2022 |
| Dell          | OptiPlex 780                | [7a029315b9](https://linux-hardware.org/?probe=7a029315b9) | Jul 28, 2022 |
| ASRock        | Z97 Anniversary             | [768b11cbe4](https://linux-hardware.org/?probe=768b11cbe4) | Jul 28, 2022 |
| MSI           | G31TM-P35                   | [1bc8def241](https://linux-hardware.org/?probe=1bc8def241) | Jul 28, 2022 |
| MSI           | AM1I                        | [63e6d4040e](https://linux-hardware.org/?probe=63e6d4040e) | Jul 28, 2022 |
| Gigabyte      | B450M H                     | [1357e3b3d3](https://linux-hardware.org/?probe=1357e3b3d3) | Jul 28, 2022 |
| ASUSTek       | H110M-A/M.2                 | [93ad7b0efb](https://linux-hardware.org/?probe=93ad7b0efb) | Jul 28, 2022 |
| ASRock        | B450M Steel Legend          | [db492973ec](https://linux-hardware.org/?probe=db492973ec) | Jul 28, 2022 |
| ASRock        | A320M-HDV                   | [cc72c3c914](https://linux-hardware.org/?probe=cc72c3c914) | Jul 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [24e94dd87e](https://linux-hardware.org/?probe=24e94dd87e) | Jul 28, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [0068653ca3](https://linux-hardware.org/?probe=0068653ca3) | Jul 28, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [d64175b64b](https://linux-hardware.org/?probe=d64175b64b) | Jul 28, 2022 |
| ASRock        | A88M-ITX/ac                 | [e339941033](https://linux-hardware.org/?probe=e339941033) | Jul 27, 2022 |
| Intel         | D54250WYK H13922-303        | [71b03b93a2](https://linux-hardware.org/?probe=71b03b93a2) | Jul 27, 2022 |
| Acer          | Aspire X1930                | [6a650f512e](https://linux-hardware.org/?probe=6a650f512e) | Jul 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [d0ef6d20cf](https://linux-hardware.org/?probe=d0ef6d20cf) | Jul 27, 2022 |
| Foxconn       | A76ML-K 30                  | [7b118c6a6b](https://linux-hardware.org/?probe=7b118c6a6b) | Jul 27, 2022 |
| Dell          | 09KPNV A00                  | [610282a0e6](https://linux-hardware.org/?probe=610282a0e6) | Jul 27, 2022 |
| Dell          | 0YF8P5 A00                  | [04ebe8cd88](https://linux-hardware.org/?probe=04ebe8cd88) | Jul 27, 2022 |
| ASRock        | B450M Pro4                  | [5b4bccdf27](https://linux-hardware.org/?probe=5b4bccdf27) | Jul 27, 2022 |
| HP            | 1495                        | [61a8f473e2](https://linux-hardware.org/?probe=61a8f473e2) | Jul 27, 2022 |
| MSI           | B250M PRO-VDH               | [eb1ff40d2d](https://linux-hardware.org/?probe=eb1ff40d2d) | Jul 27, 2022 |
| ASUSTek       | Z97-P                       | [eeb9068dca](https://linux-hardware.org/?probe=eeb9068dca) | Jul 27, 2022 |
| Gigabyte      | H55M-S2H                    | [a9a6ab85ac](https://linux-hardware.org/?probe=a9a6ab85ac) | Jul 27, 2022 |
| Dell          | 0NW6H5 A00                  | [b76e9e02fa](https://linux-hardware.org/?probe=b76e9e02fa) | Jul 27, 2022 |
| Gigabyte      | H81M-HD3                    | [0cfb15d654](https://linux-hardware.org/?probe=0cfb15d654) | Jul 27, 2022 |
| ASRock        | FM2A88X-ITX+                | [24e0844619](https://linux-hardware.org/?probe=24e0844619) | Jul 27, 2022 |
| Acer          | IPXHW-RL                    | [d99b7cb71e](https://linux-hardware.org/?probe=d99b7cb71e) | Jul 27, 2022 |
| Intel         | DH67VR AAG27177-201         | [3aeca135cd](https://linux-hardware.org/?probe=3aeca135cd) | Jul 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [05947b595a](https://linux-hardware.org/?probe=05947b595a) | Jul 26, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [e487b063ea](https://linux-hardware.org/?probe=e487b063ea) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [17954b8ac5](https://linux-hardware.org/?probe=17954b8ac5) | Jul 26, 2022 |
| Dell          | 0C27VV A03                  | [c1c4edd1e5](https://linux-hardware.org/?probe=c1c4edd1e5) | Jul 26, 2022 |
| Dell          | 042P49 A01                  | [f9003ad850](https://linux-hardware.org/?probe=f9003ad850) | Jul 26, 2022 |
| Login Info... | LOG-H310M-G                 | [f02a0ed6dd](https://linux-hardware.org/?probe=f02a0ed6dd) | Jul 26, 2022 |
| Acer          | Aspire XC-830               | [02572035c8](https://linux-hardware.org/?probe=02572035c8) | Jul 26, 2022 |
| Dell          | 04YP6J A02                  | [8161693c82](https://linux-hardware.org/?probe=8161693c82) | Jul 26, 2022 |
| Pegatron      | 2AE2                        | [772ded1d83](https://linux-hardware.org/?probe=772ded1d83) | Jul 25, 2022 |
| Dell          | 0V8WGR A01                  | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Acer          | EM61SM/EM61PM               | [e470dff38f](https://linux-hardware.org/?probe=e470dff38f) | Jul 25, 2022 |
| Lenovo        | ThinkCentre M58p 6137B28    | [5473e97fa6](https://linux-hardware.org/?probe=5473e97fa6) | Jul 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.3/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003       | 2037     | 91.26%  |
| 5.16.13-desktop-1omv4003      | 182      | 8.15%   |
| 5.17.1-desktop-2omv4050       | 2        | 0.09%   |
| 5.16.5-desktop-2omv4003       | 2        | 0.09%   |
| 5.16.3-desktop-2omv4050       | 2        | 0.09%   |
| 5.10.14-desktop-1omv4002      | 2        | 0.09%   |
| 6.5.3-desktop-1omv2390        | 1        | 0.04%   |
| 5.17.7-desktop-1omv4090       | 1        | 0.04%   |
| 5.16.7-desktop-clang-1omv4003 | 1        | 0.04%   |
| 5.16.13-desktop-1omv4050      | 1        | 0.04%   |
| 5.11.12-desktop-1omv4002      | 1        | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16.7  | 2038     | 91.31%  |
| 5.16.13 | 183      | 8.2%    |
| 5.17.1  | 2        | 0.09%   |
| 5.16.5  | 2        | 0.09%   |
| 5.16.3  | 2        | 0.09%   |
| 5.10.14 | 2        | 0.09%   |
| 6.5.3   | 1        | 0.04%   |
| 5.17.7  | 1        | 0.04%   |
| 5.11.12 | 1        | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16    | 2185     | 99.68%  |
| 5.17    | 3        | 0.14%   |
| 5.10    | 2        | 0.09%   |
| 6.5     | 1        | 0.05%   |
| 5.11    | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2191     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 2186     | 99.64%  |
| LXQt     | 3        | 0.14%   |
| Unknown  | 3        | 0.14%   |
| Cinnamon | 2        | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2168     | 98.95%  |
| Wayland | 23       | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SDDM | 2191     | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 1187     | 53.69%  |
| de_DE | 198      | 8.96%   |
| ru_RU | 157      | 7.1%    |
| fr_FR | 109      | 4.93%   |
| pt_BR | 98       | 4.43%   |
| pl_PL | 68       | 3.08%   |
| it_IT | 51       | 2.31%   |
| es_ES | 42       | 1.9%    |
| en_GB | 40       | 1.81%   |
| es_AR | 30       | 1.36%   |
| es_MX | 23       | 1.04%   |
| cs_CZ | 21       | 0.95%   |
| de_AT | 18       | 0.81%   |
| en_IN | 16       | 0.72%   |
| hu_HU | 14       | 0.63%   |
| tr_TR | 11       | 0.5%    |
| en_CA | 11       | 0.5%    |
| fr_CA | 9        | 0.41%   |
| es_CO | 9        | 0.41%   |
| en_AU | 9        | 0.41%   |
| ru_UA | 8        | 0.36%   |
| de_CH | 8        | 0.36%   |
| pt_PT | 7        | 0.32%   |
| nl_NL | 6        | 0.27%   |
| fr_BE | 6        | 0.27%   |
| es_CL | 6        | 0.27%   |
| da_DK | 6        | 0.27%   |
| es_VE | 5        | 0.23%   |
| es_PE | 4        | 0.18%   |
| nb_NO | 3        | 0.14%   |
| es_CR | 3        | 0.14%   |
| uk_UA | 2        | 0.09%   |
| fr_CH | 2        | 0.09%   |
| es_UY | 2        | 0.09%   |
| es_SV | 2        | 0.09%   |
| es_DO | 2        | 0.09%   |
| en_ZA | 2        | 0.09%   |
| en_IL | 2        | 0.09%   |
| en_HK | 2        | 0.09%   |
| ar_SA | 2        | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1226     | 55.83%  |
| EFI  | 970      | 44.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Overlay  | 1783     | 79.7%   |
| Ext4     | 440      | 19.67%  |
| Xfs      | 5        | 0.22%   |
| Btrfs    | 3        | 0.13%   |
| F2fs     | 2        | 0.09%   |
| Ext3     | 2        | 0.09%   |
| Reiserfs | 1        | 0.04%   |
| Jfs      | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1366     | 61.92%  |
| MBR     | 821      | 37.22%  |
| Unknown | 19       | 0.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1359     | 61.44%  |
| No        | 853      | 38.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1239     | 56.37%  |
| No        | 959      | 43.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 485      | 22.14%  |
| Gigabyte Technology | 413      | 18.85%  |
| MSI                 | 247      | 11.27%  |
| ASRock              | 193      | 8.81%   |
| Hewlett-Packard     | 180      | 8.22%   |
| Dell                | 170      | 7.76%   |
| Lenovo              | 93       | 4.24%   |
| Intel               | 70       | 3.19%   |
| Acer                | 58       | 2.65%   |
| Fujitsu             | 32       | 1.46%   |
| Foxconn             | 28       | 1.28%   |
| Pegatron            | 27       | 1.23%   |
| Biostar             | 25       | 1.14%   |
| ECS                 | 18       | 0.82%   |
| Medion              | 14       | 0.64%   |
| Unknown             | 14       | 0.64%   |
| Positivo            | 12       | 0.55%   |
| AZW                 | 9        | 0.41%   |
| Shuttle             | 7        | 0.32%   |
| MACHINIST           | 6        | 0.27%   |
| Fujitsu Siemens     | 6        | 0.27%   |
| Alienware           | 6        | 0.27%   |
| BESSTAR Tech        | 5        | 0.23%   |
| PCWare              | 4        | 0.18%   |
| Packard Bell        | 4        | 0.18%   |
| OEM                 | 4        | 0.18%   |
| Apple               | 4        | 0.18%   |
| Wistron             | 3        | 0.14%   |
| WesternDigital      | 2        | 0.09%   |
| Supermicro          | 2        | 0.09%   |
| Semp Toshiba        | 2        | 0.09%   |
| Philco              | 2        | 0.09%   |
| MAXSUN              | 2        | 0.09%   |
| Login Informatica   | 2        | 0.09%   |
| Itautec             | 2        | 0.09%   |
| Huanan              | 2        | 0.09%   |
| Gateway             | 2        | 0.09%   |
| ACTION              | 2        | 0.09%   |
| VS Company          | 1        | 0.05%   |
| Vorke               | 1        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 46       | 2.1%    |
| Gigabyte H410M H V3          | 27       | 1.23%   |
| ASUS SABERTOOTH Z77          | 19       | 0.87%   |
| Dell OptiPlex 7010           | 18       | 0.82%   |
| Unknown                      | 15       | 0.68%   |
| Intel H61                    | 11       | 0.5%    |
| Dell OptiPlex 780            | 10       | 0.46%   |
| MSI MS-7C91                  | 9        | 0.41%   |
| Gigabyte B450M DS3H          | 9        | 0.41%   |
| HP ProDesk 600 G1 SFF        | 8        | 0.37%   |
| Dell OptiPlex 9020           | 8        | 0.37%   |
| Dell OptiPlex 790            | 8        | 0.37%   |
| Dell OptiPlex 380            | 8        | 0.37%   |
| Dell OptiPlex 3020           | 8        | 0.37%   |
| ASUS PRIME B450M-A II        | 8        | 0.37%   |
| MSI MS-7A38                  | 7        | 0.32%   |
| HP EliteDesk 800 G1 SFF      | 7        | 0.32%   |
| MSI MS-7C37                  | 6        | 0.27%   |
| MSI MS-7C02                  | 6        | 0.27%   |
| MSI MS-7B79                  | 6        | 0.27%   |
| MSI MS-7721                  | 6        | 0.27%   |
| MSI MS-7641                  | 6        | 0.27%   |
| HP EliteDesk 800 G1 USDT     | 6        | 0.27%   |
| HP Compaq Pro 6300 SFF       | 6        | 0.27%   |
| Gigabyte 970A-DS3P           | 6        | 0.27%   |
| Dell OptiPlex 760            | 6        | 0.27%   |
| Dell OptiPlex 745            | 6        | 0.27%   |
| Dell OptiPlex 7020           | 6        | 0.27%   |
| ASUS TUF Gaming B550-PLUS    | 6        | 0.27%   |
| ASUS ROG STRIX B550-F GAMING | 6        | 0.27%   |
| ASUS PRIME B450-PLUS         | 6        | 0.27%   |
| ASUS PRIME A320M-K           | 6        | 0.27%   |
| ASUS M5A78L-M/USB3           | 6        | 0.27%   |
| MSI MS-7C84                  | 5        | 0.23%   |
| MSI MS-7788                  | 5        | 0.23%   |
| MSI MS-7529                  | 5        | 0.23%   |
| HP Compaq 8200 Elite SFF PC  | 5        | 0.23%   |
| HP Compaq 8100 Elite CMT PC  | 5        | 0.23%   |
| Gigabyte B550M AORUS PRO-P   | 5        | 0.23%   |
| Gigabyte A320M-S2H           | 5        | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 115      | 5.25%   |
| ASUS PRIME             | 86       | 3.93%   |
| Lenovo ThinkCentre     | 62       | 2.83%   |
| HP Compaq              | 61       | 2.78%   |
| ASUS All               | 46       | 2.1%    |
| Acer Aspire            | 39       | 1.78%   |
| ASUS TUF               | 37       | 1.69%   |
| HP EliteDesk           | 33       | 1.51%   |
| ASUS ROG               | 33       | 1.51%   |
| Gigabyte H410M         | 31       | 1.41%   |
| Fujitsu ESPRIMO        | 28       | 1.28%   |
| HP ProDesk             | 27       | 1.23%   |
| ASUS SABERTOOTH        | 25       | 1.14%   |
| Dell Precision         | 20       | 0.91%   |
| ASUS M5A78L-M          | 20       | 0.91%   |
| Gigabyte B450M         | 19       | 0.87%   |
| Unknown                | 15       | 0.68%   |
| Acer Veriton           | 14       | 0.64%   |
| Dell Vostro            | 13       | 0.59%   |
| Dell Inspiron          | 13       | 0.59%   |
| Intel H61              | 12       | 0.55%   |
| Gigabyte Z390          | 11       | 0.5%    |
| Gigabyte X570          | 11       | 0.5%    |
| ASUS M5A97             | 11       | 0.5%    |
| Gigabyte GA-78LMT-USB3 | 10       | 0.46%   |
| Gigabyte B550M         | 10       | 0.46%   |
| ASUS P8H61-M           | 10       | 0.46%   |
| ASRock B450M           | 10       | 0.46%   |
| MSI MS-7C91            | 9        | 0.41%   |
| HP Pavilion            | 9        | 0.41%   |
| Gigabyte B450          | 9        | 0.41%   |
| Lenovo ThinkStation    | 8        | 0.37%   |
| Lenovo IdeaCentre      | 8        | 0.37%   |
| ASRock A320M-HDV       | 8        | 0.37%   |
| MSI MS-7A38            | 7        | 0.32%   |
| ASRock B450            | 7        | 0.32%   |
| MSI MS-7C37            | 6        | 0.27%   |
| MSI MS-7C02            | 6        | 0.27%   |
| MSI MS-7B79            | 6        | 0.27%   |
| MSI MS-7721            | 6        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 244      | 11.14%  |
| 2013 | 205      | 9.36%   |
| 2018 | 188      | 8.58%   |
| 2011 | 176      | 8.03%   |
| 2014 | 171      | 7.8%    |
| 2020 | 144      | 6.57%   |
| 2010 | 144      | 6.57%   |
| 2021 | 143      | 6.53%   |
| 2009 | 130      | 5.93%   |
| 2019 | 120      | 5.48%   |
| 2008 | 102      | 4.66%   |
| 2017 | 99       | 4.52%   |
| 2016 | 93       | 4.24%   |
| 2015 | 80       | 3.65%   |
| 2007 | 67       | 3.06%   |
| 2006 | 50       | 2.28%   |
| 2022 | 25       | 1.14%   |
| 2005 | 7        | 0.32%   |
| 2023 | 3        | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2191     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2191     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2191     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 502      | 22.77%  |
| 16.01-24.0      | 465      | 21.09%  |
| 4.01-8.0        | 439      | 19.91%  |
| 3.01-4.0        | 390      | 17.69%  |
| 32.01-64.0      | 223      | 10.11%  |
| 1.01-2.0        | 62       | 2.81%   |
| 64.01-256.0     | 50       | 2.27%   |
| 24.01-32.0      | 47       | 2.13%   |
| 2.01-3.0        | 22       | 1%      |
| 0.51-1.0        | 3        | 0.14%   |
| More than 256.0 | 2        | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 1462     | 65.53%  |
| 0.51-1.0  | 498      | 22.32%  |
| 2.01-3.0  | 179      | 8.02%   |
| 0.01-0.5  | 54       | 2.42%   |
| 3.01-4.0  | 22       | 0.99%   |
| 4.01-8.0  | 10       | 0.45%   |
| 8.01-16.0 | 6        | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 945      | 42.59%  |
| 2      | 606      | 27.31%  |
| 3      | 293      | 13.2%   |
| 4      | 182      | 8.2%    |
| 5      | 78       | 3.52%   |
| 0      | 50       | 2.25%   |
| 6      | 32       | 1.44%   |
| 7      | 12       | 0.54%   |
| 8      | 7        | 0.32%   |
| 9      | 6        | 0.27%   |
| 13     | 2        | 0.09%   |
| 12     | 2        | 0.09%   |
| 11     | 2        | 0.09%   |
| 15     | 1        | 0.05%   |
| 10     | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1236     | 56.21%  |
| No        | 963      | 43.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2177     | 99.36%  |
| No        | 14       | 0.64%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1426     | 64.82%  |
| Yes       | 774      | 35.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1726     | 78.49%  |
| Yes       | 473      | 21.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 272      | 12.4%   |
| USA          | 271      | 12.35%  |
| Russia       | 191      | 8.71%   |
| Brazil       | 149      | 6.79%   |
| France       | 148      | 6.75%   |
| Poland       | 121      | 5.52%   |
| Italy        | 88       | 4.01%   |
| Canada       | 57       | 2.6%    |
| UK           | 55       | 2.51%   |
| Spain        | 55       | 2.51%   |
| Australia    | 45       | 2.05%   |
| India        | 42       | 1.91%   |
| Mexico       | 39       | 1.78%   |
| Argentina    | 36       | 1.64%   |
| Czechia      | 30       | 1.37%   |
| Ukraine      | 29       | 1.32%   |
| Japan        | 29       | 1.32%   |
| Netherlands  | 27       | 1.23%   |
| Austria      | 26       | 1.19%   |
| Hungary      | 22       | 1%      |
| Romania      | 21       | 0.96%   |
| Switzerland  | 20       | 0.91%   |
| Indonesia    | 20       | 0.91%   |
| Turkey       | 19       | 0.87%   |
| Sweden       | 18       | 0.82%   |
| Serbia       | 17       | 0.77%   |
| Belgium      | 15       | 0.68%   |
| Portugal     | 14       | 0.64%   |
| Colombia     | 14       | 0.64%   |
| Egypt        | 13       | 0.59%   |
| Uruguay      | 11       | 0.5%    |
| Slovakia     | 11       | 0.5%    |
| Israel       | 11       | 0.5%    |
| Algeria      | 11       | 0.5%    |
| Venezuela    | 10       | 0.46%   |
| Finland      | 10       | 0.46%   |
| China        | 10       | 0.46%   |
| Thailand     | 9        | 0.41%   |
| Peru         | 9        | 0.41%   |
| South Africa | 8        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 33       | 1.48%   |
| Gonikoppal        | 22       | 0.98%   |
| Warsaw            | 19       | 0.85%   |
| Strzyzow          | 17       | 0.76%   |
| Sao Paulo         | 16       | 0.72%   |
| Berlin            | 16       | 0.72%   |
| St Petersburg     | 15       | 0.67%   |
| Mexico City       | 14       | 0.63%   |
| Vienna            | 13       | 0.58%   |
| Paris             | 13       | 0.58%   |
| Munich            | 13       | 0.58%   |
| Sydney            | 11       | 0.49%   |
| Milan             | 11       | 0.49%   |
| Rio de Janeiro    | 10       | 0.45%   |
| Istanbul          | 9        | 0.4%    |
| Cairo             | 9        | 0.4%    |
| Belgrade          | 9        | 0.4%    |
| Poznan            | 8        | 0.36%   |
| Nizhniy Novgorod  | 8        | 0.36%   |
| Hamburg           | 8        | 0.36%   |
| Budapest          | 8        | 0.36%   |
| Bucharest         | 8        | 0.36%   |
| Brisbane          | 8        | 0.36%   |
| Braganca Paulista | 8        | 0.36%   |
| Yekaterinburg     | 7        | 0.31%   |
| Skopje            | 7        | 0.31%   |
| Rome              | 7        | 0.31%   |
| Montevideo        | 7        | 0.31%   |
| Marseille         | 7        | 0.31%   |
| Lima              | 7        | 0.31%   |
| Kyiv              | 7        | 0.31%   |
| Jakarta           | 7        | 0.31%   |
| Buenos Aires      | 7        | 0.31%   |
| San Jose          | 6        | 0.27%   |
| Prague            | 6        | 0.27%   |
| Madrid            | 6        | 0.27%   |
| Gdansk            | 6        | 0.27%   |
| Chelyabinsk       | 6        | 0.27%   |
| Bratislava        | 6        | 0.27%   |
| Zagreb            | 5        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 750      | 1011   | 19.72%  |
| Seagate             | 690      | 927    | 18.14%  |
| Samsung Electronics | 502      | 669    | 13.2%   |
| Kingston            | 227      | 264    | 5.97%   |
| Toshiba             | 217      | 252    | 5.7%    |
| Crucial             | 186      | 222    | 4.89%   |
| SanDisk             | 154      | 184    | 4.05%   |
| Hitachi             | 144      | 164    | 3.79%   |
| A-DATA Technology   | 107      | 116    | 2.81%   |
| China               | 49       | 57     | 1.29%   |
| Unknown             | 42       | 66     | 1.1%    |
| Maxtor              | 39       | 46     | 1.03%   |
| HGST                | 34       | 42     | 0.89%   |
| SPCC                | 30       | 34     | 0.79%   |
| Intel               | 29       | 30     | 0.76%   |
| PNY                 | 27       | 36     | 0.71%   |
| GOODRAM             | 27       | 29     | 0.71%   |
| Patriot             | 25       | 27     | 0.66%   |
| Gigabyte Technology | 23       | 23     | 0.6%    |
| Intenso             | 22       | 23     | 0.58%   |
| Apacer              | 22       | 23     | 0.58%   |
| OCZ                 | 21       | 21     | 0.55%   |
| Team                | 19       | 20     | 0.5%    |
| Micron Technology   | 19       | 19     | 0.5%    |
| Corsair             | 18       | 19     | 0.47%   |
| Unknown             | 18       | 19     | 0.47%   |
| Phison              | 17       | 20     | 0.45%   |
| Netac               | 17       | 19     | 0.45%   |
| JMicron Technology  | 17       | 19     | 0.45%   |
| Transcend           | 14       | 16     | 0.37%   |
| Hewlett-Packard     | 14       | 18     | 0.37%   |
| SK hynix            | 13       | 13     | 0.34%   |
| ASMT                | 13       | 15     | 0.34%   |
| XPG                 | 12       | 15     | 0.32%   |
| Silicon Motion      | 8        | 9      | 0.21%   |
| LITEON              | 8        | 8      | 0.21%   |
| KIOXIA-EXCERIA      | 8        | 8      | 0.21%   |
| KingSpec            | 8        | 8      | 0.21%   |
| Apple               | 8        | 8      | 0.21%   |
| KingFast            | 7        | 7      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 77       | 1.76%   |
| Seagate ST1000DM010-2EP102 1TB   | 64       | 1.46%   |
| Kingston SA400S37240G 240GB SSD  | 53       | 1.21%   |
| WDC WD10EZEX-08WN4A0 1TB         | 41       | 0.93%   |
| Toshiba DT01ACA100 1TB           | 40       | 0.91%   |
| Seagate ST2000DM008-2FR102 2TB   | 37       | 0.84%   |
| Kingston SA400S37480G 480GB SSD  | 33       | 0.75%   |
| Crucial CT500MX500SSD1 500GB     | 33       | 0.75%   |
| Samsung SSD 860 EVO 500GB        | 31       | 0.71%   |
| Samsung SSD 860 EVO 250GB        | 31       | 0.71%   |
| Toshiba DT01ACA050 500GB         | 30       | 0.68%   |
| Samsung SSD 850 EVO 250GB        | 29       | 0.66%   |
| Kingston SA400S37120G 120GB SSD  | 28       | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB   | 27       | 0.62%   |
| Samsung HD502HJ 500GB            | 23       | 0.52%   |
| Kingston SV300S37A120G 120GB SSD | 23       | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 22       | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB   | 22       | 0.5%    |
| Crucial CT240BX500SSD1 240GB     | 22       | 0.5%    |
| Crucial CT1000MX500SSD1 1TB      | 22       | 0.5%    |
| A-DATA SU750 256GB SSD           | 22       | 0.5%    |
| Seagate ST3500418AS 500GB        | 21       | 0.48%   |
| Seagate ST1000DM003-1CH162 1TB   | 21       | 0.48%   |
| Crucial CT480BX500SSD1 480GB     | 21       | 0.48%   |
| Samsung SSD 850 EVO 500GB        | 20       | 0.46%   |
| Unknown SD/MMC/MS PRO 128GB      | 19       | 0.43%   |
| Toshiba HDWD110 1TB              | 19       | 0.43%   |
| Toshiba DT01ACA200 2TB           | 18       | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB   | 18       | 0.41%   |
| Seagate ST1000DM003-1SB102 1TB   | 18       | 0.41%   |
| Unknown                          | 18       | 0.41%   |
| Seagate ST3500413AS 500GB        | 17       | 0.39%   |
| SanDisk SSD PLUS 240GB           | 17       | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB     | 17       | 0.39%   |
| Samsung HD322HJ 320GB            | 16       | 0.36%   |
| Seagate ST31000528AS 1TB         | 15       | 0.34%   |
| SanDisk SSD PLUS 1000GB          | 15       | 0.34%   |
| SanDisk SDSSDA240G 240GB         | 15       | 0.34%   |
| WDC WD10EZEX-00BN5A0 1TB         | 14       | 0.32%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 13       | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 681      | 909    | 34%     |
| WDC                 | 654      | 842    | 32.65%  |
| Toshiba             | 199      | 233    | 9.94%   |
| Samsung Electronics | 163      | 194    | 8.14%   |
| Hitachi             | 144      | 164    | 7.19%   |
| Maxtor              | 38       | 45     | 1.9%    |
| HGST                | 34       | 42     | 1.7%    |
| Unknown             | 20       | 20     | 1%      |
| JMicron Technology  | 13       | 15     | 0.65%   |
| Apple               | 8        | 8      | 0.4%    |
| TO Exter            | 6        | 6      | 0.3%    |
| IBM/Hitachi         | 5        | 7      | 0.25%   |
| Fujitsu             | 5        | 5      | 0.25%   |
| Intenso             | 4        | 4      | 0.2%    |
| ASMT                | 4        | 5      | 0.2%    |
| WD MediaMax         | 3        | 4      | 0.15%   |
| SABRENT             | 3        | 4      | 0.15%   |
| Hewlett-Packard     | 3        | 4      | 0.15%   |
| Magnetic Data       | 2        | 2      | 0.1%    |
| Initio              | 2        | 2      | 0.1%    |
| HPE                 | 2        | 3      | 0.1%    |
| Unknown             | 2        | 2      | 0.1%    |
| RSH-339             | 1        | 1      | 0.05%   |
| QUANTUM             | 1        | 1      | 0.05%   |
| MARVELL             | 1        | 1      | 0.05%   |
| Inateck             | 1        | 1      | 0.05%   |
| External            | 1        | 1      | 0.05%   |
| ExcelStor           | 1        | 1      | 0.05%   |
| Config              | 1        | 1      | 0.05%   |
| China               | 1        | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 253      | 309    | 17.83%  |
| Kingston            | 193      | 222    | 13.6%   |
| Crucial             | 154      | 179    | 10.85%  |
| SanDisk             | 140      | 166    | 9.87%   |
| WDC                 | 90       | 110    | 6.34%   |
| A-DATA Technology   | 89       | 91     | 6.27%   |
| China               | 48       | 56     | 3.38%   |
| GOODRAM             | 25       | 25     | 1.76%   |
| PNY                 | 23       | 30     | 1.62%   |
| SPCC                | 22       | 25     | 1.55%   |
| OCZ                 | 21       | 21     | 1.48%   |
| Patriot             | 20       | 22     | 1.41%   |
| Apacer              | 20       | 20     | 1.41%   |
| Intel               | 19       | 20     | 1.34%   |
| Team                | 18       | 18     | 1.27%   |
| Micron Technology   | 18       | 18     | 1.27%   |
| Unknown             | 16       | 17     | 1.13%   |
| Gigabyte Technology | 15       | 15     | 1.06%   |
| Toshiba             | 14       | 15     | 0.99%   |
| Netac               | 14       | 16     | 0.99%   |
| Intenso             | 14       | 15     | 0.99%   |
| Transcend           | 12       | 13     | 0.85%   |
| ASMT                | 9        | 10     | 0.63%   |
| KingSpec            | 8        | 8      | 0.56%   |
| Hewlett-Packard     | 8        | 10     | 0.56%   |
| LITEON              | 7        | 7      | 0.49%   |
| KingFast            | 7        | 7      | 0.49%   |
| Corsair             | 7        | 7      | 0.49%   |
| KIOXIA-EXCERIA      | 6        | 6      | 0.42%   |
| Colorful            | 6        | 8      | 0.42%   |
| KingDian            | 5        | 6      | 0.35%   |
| Emtec               | 5        | 5      | 0.35%   |
| USB3.0              | 4        | 4      | 0.28%   |
| SK hynix            | 4        | 4      | 0.28%   |
| Seagate             | 4        | 4      | 0.28%   |
| LITEONIT            | 4        | 4      | 0.28%   |
| Leven               | 4        | 4      | 0.28%   |
| Zheino              | 3        | 4      | 0.21%   |
| Mushkin             | 3        | 3      | 0.21%   |
| Lexar               | 3        | 3      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1543     | 2528   | 49.39%  |
| SSD     | 1129     | 1612   | 36.14%  |
| NVMe    | 403      | 526    | 12.9%   |
| Unknown | 40       | 63     | 1.28%   |
| MMC     | 9        | 10     | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2044     | 3989   | 77.9%   |
| NVMe | 400      | 518    | 15.24%  |
| SAS  | 171      | 222    | 6.52%   |
| MMC  | 9        | 10     | 0.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1633     | 2485   | 57.04%  |
| 0.51-1.0   | 777      | 1054   | 27.14%  |
| 1.01-2.0   | 269      | 338    | 9.4%    |
| 2.01-3.0   | 65       | 86     | 2.27%   |
| 3.01-4.0   | 57       | 82     | 1.99%   |
| 4.01-10.0  | 51       | 84     | 1.78%   |
| 10.01-20.0 | 10       | 10     | 0.35%   |
| 20.01-50.0 | 1        | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1137     | 50.69%  |
| Unknown        | 290      | 12.93%  |
| 101-250        | 286      | 12.75%  |
| 251-500        | 177      | 7.89%   |
| 21-50          | 97       | 4.32%   |
| 501-1000       | 94       | 4.19%   |
| 51-100         | 82       | 3.66%   |
| 1001-2000      | 45       | 2.01%   |
| More than 3000 | 20       | 0.89%   |
| 2001-3000      | 15       | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1697     | 76.06%  |
| Unknown        | 290      | 13%     |
| 101-250        | 58       | 2.6%    |
| 21-50          | 51       | 2.29%   |
| 51-100         | 46       | 2.06%   |
| 251-500        | 35       | 1.57%   |
| 501-1000       | 32       | 1.43%   |
| 1001-2000      | 14       | 0.63%   |
| More than 3000 | 6        | 0.27%   |
| 2001-3000      | 2        | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 36       | 38     | 4.17%   |
| Samsung Electronics HD322HJ 320GB | 11       | 12     | 1.27%   |
| Seagate ST1000DM010-2EP102 1TB    | 9        | 11     | 1.04%   |
| Seagate ST1000DM003-9YN162 1TB    | 9        | 9      | 1.04%   |
| WDC WD10EARS-00Y5B1 1TB           | 8        | 9      | 0.93%   |
| Seagate ST3500413AS 500GB         | 8        | 8      | 0.93%   |
| Kingston SV300S37A120G 120GB SSD  | 8        | 8      | 0.93%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 7        | 8      | 0.81%   |
| Seagate ST9500325AS 500GB         | 7        | 7      | 0.81%   |
| Seagate ST3500418AS 500GB         | 7        | 8      | 0.81%   |
| Samsung Electronics HD502HJ 500GB | 7        | 7      | 0.81%   |
| Samsung Electronics HD502HI 500GB | 7        | 8      | 0.81%   |
| WDC WD5000AAKS-00V1A0 500GB       | 6        | 6      | 0.7%    |
| WDC WD10EALX-009BA0 1TB           | 6        | 6      | 0.7%    |
| Toshiba DT01ACA050 500GB          | 6        | 7      | 0.7%    |
| Seagate ST31000524AS 1TB          | 6        | 7      | 0.7%    |
| Seagate ST2000DM001-1CH164 2TB    | 6        | 6      | 0.7%    |
| SanDisk SSD PLUS 240GB            | 6        | 6      | 0.7%    |
| Hitachi HDS721050CLA362 500GB     | 6        | 7      | 0.7%    |
| WDC WD5000AAKX-00ERMA0 500GB      | 5        | 5      | 0.58%   |
| WDC WD5000AADS-00S9B0 500GB       | 5        | 5      | 0.58%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 5        | 5      | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB          | 5        | 5      | 0.58%   |
| Toshiba DT01ACA100 1TB            | 5        | 6      | 0.58%   |
| Seagate ST3320418AS 320GB         | 5        | 5      | 0.58%   |
| Seagate ST31000528AS 1TB          | 5        | 6      | 0.58%   |
| Seagate ST1000DM003-1SB102 1TB    | 5        | 5      | 0.58%   |
| Seagate ST1000DM003-1CH162 1TB    | 5        | 6      | 0.58%   |
| Maxtor STM3250310AS 250GB         | 5        | 5      | 0.58%   |
| GOODRAM SSD 120GB                 | 5        | 5      | 0.58%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 4        | 4      | 0.46%   |
| WDC WD3200AAJS-00L7A0 320GB       | 4        | 4      | 0.46%   |
| WDC WD20EARS-00MVWB0 2TB          | 4        | 4      | 0.46%   |
| Seagate ST92505610AS 250GB        | 4        | 4      | 0.46%   |
| Seagate ST380013AS 80GB           | 4        | 4      | 0.46%   |
| Seagate ST3320613AS 320GB         | 4        | 4      | 0.46%   |
| Seagate ST250DM000-1BD141 250GB   | 4        | 4      | 0.46%   |
| SanDisk SSD PLUS 480GB            | 4        | 4      | 0.46%   |
| Samsung Electronics SP2504C 250GB | 4        | 4      | 0.46%   |
| Samsung Electronics HD753LJ 752GB | 4        | 4      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 248      | 284    | 30.1%   |
| WDC                 | 229      | 255    | 27.79%  |
| Samsung Electronics | 86       | 96     | 10.44%  |
| Hitachi             | 69       | 76     | 8.37%   |
| Toshiba             | 32       | 34     | 3.88%   |
| Maxtor              | 25       | 27     | 3.03%   |
| SanDisk             | 20       | 21     | 2.43%   |
| Kingston            | 19       | 20     | 2.31%   |
| HGST                | 12       | 13     | 1.46%   |
| A-DATA Technology   | 9        | 10     | 1.09%   |
| Crucial             | 8        | 9      | 0.97%   |
| Intel               | 6        | 6      | 0.73%   |
| Micron Technology   | 5        | 5      | 0.61%   |
| IBM/Hitachi         | 5        | 7      | 0.61%   |
| GOODRAM             | 5        | 5      | 0.61%   |
| China               | 4        | 5      | 0.49%   |
| ASMT                | 4        | 4      | 0.49%   |
| Patriot             | 3        | 3      | 0.36%   |
| OCZ                 | 3        | 3      | 0.36%   |
| SPCC                | 2        | 2      | 0.24%   |
| LITEON              | 2        | 2      | 0.24%   |
| Hewlett-Packard     | 2        | 3      | 0.24%   |
| Fujitsu             | 2        | 2      | 0.24%   |
| Unknown             | 2        | 2      | 0.24%   |
| WDC WDS2            | 1        | 1      | 0.12%   |
| WD MediaMax         | 1        | 1      | 0.12%   |
| USB3.0              | 1        | 1      | 0.12%   |
| Transcend           | 1        | 1      | 0.12%   |
| TO Exter            | 1        | 1      | 0.12%   |
| TEXTORM             | 1        | 1      | 0.12%   |
| TCSUNBOW            | 1        | 1      | 0.12%   |
| RSH-339             | 1        | 1      | 0.12%   |
| Neo                 | 1        | 1      | 0.12%   |
| LITEONIT            | 1        | 1      | 0.12%   |
| KingSpec            | 1        | 1      | 0.12%   |
| Kingmax             | 1        | 1      | 0.12%   |
| KingDian            | 1        | 1      | 0.12%   |
| INNOVATION IT       | 1        | 1      | 0.12%   |
| Initio              | 1        | 1      | 0.12%   |
| HPE                 | 1        | 1      | 0.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 248      | 284    | 35.63%  |
| WDC                 | 218      | 241    | 31.32%  |
| Samsung Electronics | 77       | 86     | 11.06%  |
| Hitachi             | 69       | 76     | 9.91%   |
| Toshiba             | 32       | 34     | 4.6%    |
| Maxtor              | 25       | 27     | 3.59%   |
| HGST                | 12       | 13     | 1.72%   |
| IBM/Hitachi         | 5        | 7      | 0.72%   |
| Fujitsu             | 2        | 2      | 0.29%   |
| WD MediaMax         | 1        | 1      | 0.14%   |
| TO Exter            | 1        | 1      | 0.14%   |
| RSH-339             | 1        | 1      | 0.14%   |
| Initio              | 1        | 1      | 0.14%   |
| HPE                 | 1        | 1      | 0.14%   |
| Hewlett-Packard     | 1        | 2      | 0.14%   |
| ExcelStor           | 1        | 1      | 0.14%   |
| Unknown             | 1        | 1      | 0.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 603      | 779    | 82.72%  |
| SSD  | 121      | 132    | 16.6%   |
| NVMe | 5        | 6      | 0.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Samsung Electronics HD103SJ 1TB                  | 3        | 3      | 12.5%   |
| Apple HDD HTS541010A9E662 1TB                    | 3        | 3      | 12.5%   |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1        | 1      | 4.17%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1        | 1      | 4.17%   |
| WDC WD1600YS-23SHB0 160GB                        | 1        | 1      | 4.17%   |
| Toshiba MQ01ABD050 500GB                         | 1        | 1      | 4.17%   |
| Toshiba MK3256GSY 320GB                          | 1        | 1      | 4.17%   |
| Toshiba DT01ACA100 1TB                           | 1        | 1      | 4.17%   |
| Seagate STM31000528AS 1TB                        | 1        | 1      | 4.17%   |
| Seagate ST980811AS 80GB                          | 1        | 1      | 4.17%   |
| Seagate ST3250318AS 250GB                        | 1        | 1      | 4.17%   |
| Seagate ST3160215A 160GB                         | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 980 500GB                | 1        | 1      | 4.17%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 4.17%   |
| Samsung Electronics HM160HI 160GB                | 1        | 1      | 4.17%   |
| Samsung Electronics HD103UJ 1TB                  | 1        | 1      | 4.17%   |
| Hitachi HTS725050A7E630 500GB                    | 1        | 1      | 4.17%   |
| Hitachi HDS721010DLE630 1TB                      | 1        | 1      | 4.17%   |
| Hitachi HDP725050GLA360 500GB                    | 1        | 1      | 4.17%   |
| GOODRAM SSDPR-PX500-256-80 256GB                 | 1        | 1      | 4.17%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 7      | 29.17%  |
| Seagate             | 4        | 4      | 16.67%  |
| WDC                 | 3        | 3      | 12.5%   |
| Toshiba             | 3        | 3      | 12.5%   |
| Hitachi             | 3        | 3      | 12.5%   |
| Apple               | 3        | 3      | 12.5%   |
| GOODRAM             | 1        | 1      | 4.17%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1802     | 3581   | 66.67%  |
| Malfunc  | 707      | 917    | 26.16%  |
| Detected | 171      | 217    | 6.33%   |
| Failed   | 23       | 24     | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1444     | 49.3%   |
| AMD                              | 660      | 22.53%  |
| Samsung Electronics              | 136      | 4.64%   |
| JMicron Technology               | 97       | 3.31%   |
| ASMedia Technology               | 82       | 2.8%    |
| Marvell Technology Group         | 76       | 2.59%   |
| Nvidia                           | 72       | 2.46%   |
| SanDisk                          | 68       | 2.32%   |
| Phison Electronics               | 51       | 1.74%   |
| Kingston Technology Company      | 41       | 1.4%    |
| Micron/Crucial Technology        | 38       | 1.3%    |
| Silicon Motion                   | 36       | 1.23%   |
| VIA Technologies                 | 23       | 0.79%   |
| ADATA Technology                 | 19       | 0.65%   |
| Realtek Semiconductor            | 13       | 0.44%   |
| SK hynix                         | 8        | 0.27%   |
| Broadcom / LSI                   | 8        | 0.27%   |
| Seagate Technology               | 7        | 0.24%   |
| MAXIO Technology (Hangzhou)      | 6        | 0.2%    |
| Integrated Technology Express    | 6        | 0.2%    |
| Toshiba America Info Systems     | 5        | 0.17%   |
| Micron Technology                | 4        | 0.14%   |
| Lite-On Technology               | 4        | 0.14%   |
| Adaptec                          | 4        | 0.14%   |
| LSI Logic / Symbios Logic        | 3        | 0.1%    |
| Union Memory (Shenzhen)          | 2        | 0.07%   |
| Silicon Image                    | 2        | 0.07%   |
| Shenzhen Longsys Electronics     | 2        | 0.07%   |
| Promise Technology               | 2        | 0.07%   |
| KIOXIA                           | 2        | 0.07%   |
| Yangtze Memory Technologies      | 1        | 0.03%   |
| Solid State Storage Technology   | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| Netac Technology                 | 1        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.03%   |
| INNOGRIT                         | 1        | 0.03%   |
| Hewlett-Packard                  | 1        | 0.03%   |
| 3ware                            | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 318      | 8.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 209      | 5.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 135      | 3.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 132      | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 120      | 3.19%   |
| AMD 400 Series Chipset SATA Controller                                                  | 119      | 3.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 108      | 2.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 97       | 2.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 95       | 2.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 90       | 2.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 85       | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 82       | 2.18%   |
| AMD 500 Series Chipset SATA Controller                                                  | 80       | 2.13%   |
| Intel SATA Controller [RAID mode]                                                       | 79       | 2.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 77       | 2.05%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 76       | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 70       | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 70       | 1.86%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 66       | 1.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 66       | 1.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 59       | 1.57%   |
| Nvidia MCP61 SATA Controller                                                            | 42       | 1.12%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 41       | 1.09%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 35       | 0.93%   |
| Nvidia MCP61 IDE                                                                        | 34       | 0.9%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 34       | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 34       | 0.9%    |
| AMD FCH IDE Controller                                                                  | 33       | 0.88%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 32       | 0.85%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 32       | 0.85%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 29       | 0.77%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 28       | 0.75%   |
| Phison E12 NVMe Controller                                                              | 27       | 0.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 26       | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 25       | 0.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 24       | 0.64%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 24       | 0.64%   |
| AMD 300 Series Chipset SATA Controller                                                  | 24       | 0.64%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 23       | 0.61%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 23       | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1672     | 57.38%  |
| IDE  | 713      | 24.47%  |
| NVMe | 397      | 13.62%  |
| RAID | 114      | 3.91%   |
| SAS  | 12       | 0.41%   |
| SCSI | 6        | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1468     | 67%     |
| AMD    | 723      | 33%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-10400 CPU @ 2.90GHz           | 41       | 1.87%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 33       | 1.5%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 30       | 1.37%   |
| AMD Ryzen 5 3600 6-Core Processor           | 29       | 1.32%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 28       | 1.27%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 28       | 1.27%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 25       | 1.14%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 24       | 1.09%   |
| AMD FX-8350 Eight-Core Processor            | 24       | 1.09%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 22       | 1%      |
| AMD Ryzen 5 5600G with Radeon Graphics      | 22       | 1%      |
| Intel Core i3-3220 CPU @ 3.30GHz            | 21       | 0.96%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 21       | 0.96%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 20       | 0.91%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 19       | 0.86%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 19       | 0.86%   |
| AMD FX-6300 Six-Core Processor              | 19       | 0.86%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 18       | 0.82%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 18       | 0.82%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 17       | 0.77%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 16       | 0.73%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 16       | 0.73%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 16       | 0.73%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 15       | 0.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 15       | 0.68%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 14       | 0.64%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 14       | 0.64%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 14       | 0.64%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 14       | 0.64%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 13       | 0.59%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 13       | 0.59%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 12       | 0.55%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 12       | 0.55%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 12       | 0.55%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 12       | 0.55%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 12       | 0.55%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 12       | 0.55%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 12       | 0.55%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 11       | 0.5%    |
| Intel Core i5-3330 CPU @ 3.00GHz            | 11       | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 451      | 20.56%  |
| Intel Core i3           | 221      | 10.07%  |
| Intel Core i7           | 182      | 8.3%    |
| AMD Ryzen 5             | 147      | 6.7%    |
| Intel Core 2 Duo        | 99       | 4.51%   |
| AMD FX                  | 97       | 4.42%   |
| Intel Xeon              | 84       | 3.83%   |
| Intel Pentium           | 84       | 3.83%   |
| Intel Celeron           | 84       | 3.83%   |
| AMD Ryzen 7             | 84       | 3.83%   |
| Intel Core 2 Quad       | 65       | 2.96%   |
| Intel Pentium Dual-Core | 51       | 2.32%   |
| Other                   | 50       | 2.28%   |
| AMD Ryzen 3             | 41       | 1.87%   |
| AMD Phenom II X4        | 36       | 1.64%   |
| AMD A8                  | 35       | 1.6%    |
| AMD Athlon II X2        | 30       | 1.37%   |
| Intel Core 2            | 24       | 1.09%   |
| AMD Ryzen 9             | 24       | 1.09%   |
| AMD A10                 | 24       | 1.09%   |
| AMD A4                  | 23       | 1.05%   |
| AMD Athlon 64 X2        | 22       | 1%      |
| Intel Pentium Dual      | 20       | 0.91%   |
| AMD Athlon              | 20       | 0.91%   |
| AMD A6                  | 17       | 0.77%   |
| Intel Core i9           | 15       | 0.68%   |
| AMD Athlon II X4        | 12       | 0.55%   |
| Intel Pentium Gold      | 11       | 0.5%    |
| AMD Phenom II X6        | 11       | 0.5%    |
| AMD Athlon X4           | 11       | 0.5%    |
| AMD Athlon II X3        | 11       | 0.5%    |
| Intel Atom              | 10       | 0.46%   |
| AMD Ryzen 5 PRO         | 10       | 0.46%   |
| AMD Phenom              | 10       | 0.46%   |
| Intel Pentium D         | 9        | 0.41%   |
| AMD Sempron             | 9        | 0.41%   |
| Intel Pentium 4         | 7        | 0.32%   |
| AMD Phenom II X2        | 6        | 0.27%   |
| AMD Athlon 64           | 6        | 0.27%   |
| AMD Ryzen 3 PRO         | 5        | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 837      | 38.15%  |
| 2      | 770      | 35.1%   |
| 6      | 297      | 13.54%  |
| 8      | 133      | 6.06%   |
| 1      | 55       | 2.51%   |
| 3      | 42       | 1.91%   |
| 12     | 27       | 1.23%   |
| 16     | 19       | 0.87%   |
| 10     | 7        | 0.32%   |
| 14     | 4        | 0.18%   |
| 44     | 1        | 0.05%   |
| 28     | 1        | 0.05%   |
| 20     | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2174     | 99.22%  |
| 2      | 17       | 0.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1108     | 50.52%  |
| 2      | 1083     | 49.38%  |
| 4      | 2        | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2191     | 99.95%  |
| Unknown        | 1        | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 252      | 11.44%  |
| 0x306a9    | 170      | 7.72%   |
| 0x1067a    | 167      | 7.58%   |
| 0x206a7    | 152      | 6.9%    |
| 0x506e3    | 73       | 3.31%   |
| 0x08701021 | 72       | 3.27%   |
| 0x906ea    | 69       | 3.13%   |
| Unknown    | 54       | 2.45%   |
| 0x906e9    | 52       | 2.36%   |
| 0xa0655    | 47       | 2.13%   |
| 0x010000c8 | 41       | 1.86%   |
| 0xa0653    | 40       | 1.82%   |
| 0x0800820d | 39       | 1.77%   |
| 0x6fb      | 38       | 1.72%   |
| 0x06001119 | 37       | 1.68%   |
| 0x08108109 | 30       | 1.36%   |
| 0x06000822 | 30       | 1.36%   |
| 0x0a50000c | 29       | 1.32%   |
| 0x06003106 | 29       | 1.32%   |
| 0x106e5    | 26       | 1.18%   |
| 0x6fd      | 25       | 1.13%   |
| 0x10676    | 25       | 1.13%   |
| 0x20655    | 23       | 1.04%   |
| 0x08101016 | 23       | 1.04%   |
| 0xa0671    | 22       | 1%      |
| 0x906eb    | 20       | 0.91%   |
| 0x010000b6 | 20       | 0.91%   |
| 0x0a201016 | 18       | 0.82%   |
| 0x08001138 | 16       | 0.73%   |
| 0x90672    | 15       | 0.68%   |
| 0x106a5    | 15       | 0.68%   |
| 0x08600106 | 15       | 0.68%   |
| 0x06000852 | 15       | 0.68%   |
| 0x0600081c | 14       | 0.64%   |
| 0x03000027 | 14       | 0.64%   |
| 0x906ec    | 13       | 0.59%   |
| 0x206d7    | 13       | 0.59%   |
| 0x20652    | 13       | 0.59%   |
| 0x6f2      | 12       | 0.54%   |
| 0x306f2    | 12       | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 270      | 12.3%   |
| Penryn           | 202      | 9.2%    |
| IvyBridge        | 183      | 8.34%   |
| KabyLake         | 174      | 7.93%   |
| SandyBridge      | 168      | 7.65%   |
| K10              | 122      | 5.56%   |
| Piledriver       | 119      | 5.42%   |
| Zen 2            | 102      | 4.65%   |
| Core             | 90       | 4.1%    |
| CometLake        | 87       | 3.96%   |
| Zen 3            | 80       | 3.64%   |
| Zen+             | 79       | 3.6%    |
| Skylake          | 76       | 3.46%   |
| Zen              | 67       | 3.05%   |
| Westmere         | 45       | 2.05%   |
| Nehalem          | 43       | 1.96%   |
| Steamroller      | 34       | 1.55%   |
| K8 Hammer        | 33       | 1.5%    |
| Icelake          | 22       | 1%      |
| Alderlake Hybrid | 20       | 0.91%   |
| NetBurst         | 19       | 0.87%   |
| K10 Llano        | 19       | 0.87%   |
| Bulldozer        | 19       | 0.87%   |
| Silvermont       | 18       | 0.82%   |
| Excavator        | 17       | 0.77%   |
| Jaguar           | 14       | 0.64%   |
| Goldmont plus    | 14       | 0.64%   |
| Broadwell        | 12       | 0.55%   |
| Puma             | 11       | 0.5%    |
| Tremont          | 8        | 0.36%   |
| Goldmont         | 8        | 0.36%   |
| Bonnell          | 8        | 0.36%   |
| Bobcat           | 7        | 0.32%   |
| Unknown          | 4        | 0.18%   |
| TigerLake        | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 793      | 34.93%  |
| Intel                      | 790      | 34.8%   |
| AMD                        | 678      | 29.87%  |
| VIA Technologies           | 3        | 0.13%   |
| Matrox Electronics Systems | 3        | 0.13%   |
| Conexant Systems           | 1        | 0.04%   |
| ATI Technologies           | 1        | 0.04%   |
| ASPEED Technology          | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 139      | 6.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 95       | 4.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 83       | 3.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 74       | 3.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 64       | 2.77%   |
| Nvidia GK208B [GeForce GT 710]                                              | 61       | 2.64%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 57       | 2.47%   |
| Nvidia GT218 [GeForce 210]                                                  | 49       | 2.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 46       | 1.99%   |
| Intel HD Graphics 530                                                       | 42       | 1.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 41       | 1.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 38       | 1.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 33       | 1.43%   |
| Nvidia GK208B [GeForce GT 730]                                              | 32       | 1.38%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 32       | 1.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 31       | 1.34%   |
| Intel HD Graphics 630                                                       | 28       | 1.21%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 25       | 1.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 25       | 1.08%   |
| Nvidia GF108 [GeForce GT 630]                                               | 23       | 1%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 22       | 0.95%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 21       | 0.91%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 21       | 0.91%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 19       | 0.82%   |
| AMD RS780L [Radeon 3000]                                                    | 19       | 0.82%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 19       | 0.82%   |
| Intel Core Processor Integrated Graphics Controller                         | 18       | 0.78%   |
| Nvidia GF119 [GeForce GT 610]                                               | 17       | 0.74%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 17       | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 16       | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 16       | 0.69%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 16       | 0.69%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 16       | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 15       | 0.65%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 15       | 0.65%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 15       | 0.65%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 14       | 0.61%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 14       | 0.61%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 13       | 0.56%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 12       | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 762      | 34.65%  |
| 1 x Intel                | 723      | 32.88%  |
| 1 x AMD                  | 637      | 28.97%  |
| 2 x AMD                  | 29       | 1.32%   |
| Intel + Nvidia           | 19       | 0.86%   |
| Intel + AMD              | 9        | 0.41%   |
| 2 x Nvidia               | 6        | 0.27%   |
| AMD + Nvidia             | 5        | 0.23%   |
| 1 x VIA                  | 3        | 0.14%   |
| 1 x Matrox               | 3        | 0.14%   |
| 3 x AMD                  | 1        | 0.05%   |
| Nvidia + ASPEED          | 1        | 0.05%   |
| Intel + Conexant Systems | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2106     | 96.08%  |
| Unknown     | 82       | 3.74%   |
| Proprietary | 4        | 0.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 800      | 36.38%  |
| 1.01-2.0   | 373      | 16.96%  |
| 0.51-1.0   | 338      | 15.37%  |
| 0.01-0.5   | 285      | 12.96%  |
| 3.01-4.0   | 151      | 6.87%   |
| 7.01-8.0   | 142      | 6.46%   |
| 5.01-6.0   | 55       | 2.5%    |
| 2.01-3.0   | 26       | 1.18%   |
| 8.01-16.0  | 24       | 1.09%   |
| 16.01-24.0 | 4        | 0.18%   |
| 4.01-5.0   | 1        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 369      | 17.1%   |
| Goldstar             | 241      | 11.17%  |
| Dell                 | 207      | 9.59%   |
| Hewlett-Packard      | 199      | 9.22%   |
| Acer                 | 158      | 7.32%   |
| AOC                  | 142      | 6.58%   |
| Philips              | 131      | 6.07%   |
| BenQ                 | 91       | 4.22%   |
| Ancor Communications | 76       | 3.52%   |
| ViewSonic            | 64       | 2.97%   |
| Iiyama               | 38       | 1.76%   |
| Sony                 | 27       | 1.25%   |
| ASUSTek Computer     | 27       | 1.25%   |
| Lenovo               | 26       | 1.2%    |
| Eizo                 | 21       | 0.97%   |
| Fujitsu Siemens      | 19       | 0.88%   |
| NEC Computers        | 16       | 0.74%   |
| HannStar             | 14       | 0.65%   |
| Panasonic            | 11       | 0.51%   |
| MSI                  | 10       | 0.46%   |
| Toshiba              | 9        | 0.42%   |
| Sceptre Tech         | 9        | 0.42%   |
| Medion               | 9        | 0.42%   |
| Hitachi              | 8        | 0.37%   |
| Vestel Elektronik    | 7        | 0.32%   |
| Unknown (XXX)        | 7        | 0.32%   |
| Unknown              | 7        | 0.32%   |
| TCL                  | 7        | 0.32%   |
| ___                  | 6        | 0.28%   |
| Packard Bell         | 6        | 0.28%   |
| CHD                  | 6        | 0.28%   |
| Xiaomi               | 5        | 0.23%   |
| Vizio                | 5        | 0.23%   |
| MStar                | 5        | 0.23%   |
| Mitsubishi           | 5        | 0.23%   |
| MiTAC                | 5        | 0.23%   |
| IOD                  | 5        | 0.23%   |
| GDH                  | 5        | 0.23%   |
| Belinea              | 5        | 0.23%   |
| Sharp                | 4        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                      | 22       | 1%      |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 17       | 0.77%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                 | 14       | 0.63%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 10       | 0.45%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9        | 0.41%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 9        | 0.41%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 9        | 0.41%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 8        | 0.36%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 8        | 0.36%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 7        | 0.32%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 7        | 0.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 7        | 0.32%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 7        | 0.32%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 7        | 0.32%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 7        | 0.32%   |
| AOC 2217 AOC2217 1680x1050 470x300mm 22.0-inch                        | 7        | 0.32%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch     | 6        | 0.27%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 6        | 0.27%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch      | 6        | 0.27%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 6        | 0.27%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 6        | 0.27%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch  | 5        | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5        | 0.23%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch  | 5        | 0.23%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 5        | 0.23%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch            | 5        | 0.23%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 5        | 0.23%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 5        | 0.23%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 5        | 0.23%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 5        | 0.23%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 5        | 0.23%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 5        | 0.23%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 4        | 0.18%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 4        | 0.18%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 4        | 0.18%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 4        | 0.18%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 4        | 0.18%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 4        | 0.18%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 4        | 0.18%   |
| Hewlett-Packard 27er HWP3326 1920x1080 600x340mm 27.2-inch            | 4        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1030     | 48.47%  |
| 1280x1024 (SXGA)   | 191      | 8.99%   |
| 3840x2160 (4K)     | 161      | 7.58%   |
| 1680x1050 (WSXGA+) | 125      | 5.88%   |
| 2560x1440 (QHD)    | 122      | 5.74%   |
| 1366x768 (WXGA)    | 121      | 5.69%   |
| 1440x900 (WXGA+)   | 84       | 3.95%   |
| 1600x900 (HD+)     | 78       | 3.67%   |
| 1920x1200 (WUXGA)  | 68       | 3.2%    |
| 1360x768           | 38       | 1.79%   |
| 3440x1440          | 24       | 1.13%   |
| 2560x1080          | 19       | 0.89%   |
| 1920x540           | 13       | 0.61%   |
| 1024x768 (XGA)     | 12       | 0.56%   |
| 1600x1200          | 10       | 0.47%   |
| 1280x720 (HD)      | 6        | 0.28%   |
| 2288x1287          | 5        | 0.24%   |
| 2048x1152          | 4        | 0.19%   |
| 1280x960           | 4        | 0.19%   |
| 2560x1600          | 3        | 0.14%   |
| 1280x768           | 2        | 0.09%   |
| 3840x1600          | 1        | 0.05%   |
| 3840x1200          | 1        | 0.05%   |
| 3840x1080          | 1        | 0.05%   |
| 2160x1440          | 1        | 0.05%   |
| Unknown            | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 302      | 13.97%  |
| 21      | 280      | 12.95%  |
| 27      | 277      | 12.81%  |
| 24      | 275      | 12.72%  |
| 19      | 188      | 8.7%    |
| 18      | 123      | 5.69%   |
| 31      | 109      | 5.04%   |
| 22      | 101      | 4.67%   |
| 17      | 96       | 4.44%   |
| 20      | 76       | 3.52%   |
| 34      | 39       | 1.8%    |
| 84      | 38       | 1.76%   |
| 15      | 31       | 1.43%   |
| 32      | 30       | 1.39%   |
| Unknown | 27       | 1.25%   |
| 40      | 23       | 1.06%   |
| 72      | 18       | 0.83%   |
| 54      | 17       | 0.79%   |
| 25      | 14       | 0.65%   |
| 26      | 11       | 0.51%   |
| 65      | 9        | 0.42%   |
| 52      | 9        | 0.42%   |
| 46      | 7        | 0.32%   |
| 33      | 7        | 0.32%   |
| 48      | 6        | 0.28%   |
| 12      | 6        | 0.28%   |
| 28      | 5        | 0.23%   |
| 42      | 4        | 0.19%   |
| 39      | 4        | 0.19%   |
| 35      | 4        | 0.19%   |
| 29      | 4        | 0.19%   |
| 142     | 3        | 0.14%   |
| 43      | 3        | 0.14%   |
| 14      | 3        | 0.14%   |
| 55      | 2        | 0.09%   |
| 37      | 2        | 0.09%   |
| 85      | 1        | 0.05%   |
| 60      | 1        | 0.05%   |
| 58      | 1        | 0.05%   |
| 57      | 1        | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 815      | 38.55%  |
| 401-500        | 664      | 31.41%  |
| 601-700        | 138      | 6.53%   |
| 301-350        | 123      | 5.82%   |
| 351-400        | 108      | 5.11%   |
| 701-800        | 75       | 3.55%   |
| 1501-2000      | 57       | 2.7%    |
| 1001-1500      | 56       | 2.65%   |
| 801-900        | 34       | 1.61%   |
| Unknown        | 27       | 1.28%   |
| 201-300        | 8        | 0.38%   |
| 901-1000       | 6        | 0.28%   |
| More than 2000 | 3        | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1479     | 71.07%  |
| 16/10   | 308      | 14.8%   |
| 5/4     | 185      | 8.89%   |
| 21/9    | 43       | 2.07%   |
| 4/3     | 39       | 1.87%   |
| 3/2     | 10       | 0.48%   |
| 6/5     | 6        | 0.29%   |
| 1.00    | 3        | 0.14%   |
| Unknown | 3        | 0.14%   |
| 32/9    | 2        | 0.1%    |
| 3.20    | 1        | 0.05%   |
| 2.00    | 1        | 0.05%   |
| 1.96    | 1        | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 773      | 36.19%  |
| 151-200        | 351      | 16.43%  |
| 301-350        | 285      | 13.34%  |
| 141-150        | 191      | 8.94%   |
| 351-500        | 190      | 8.9%    |
| 251-300        | 119      | 5.57%   |
| More than 1000 | 105      | 4.92%   |
| 501-1000       | 50       | 2.34%   |
| Unknown        | 27       | 1.26%   |
| 101-110        | 24       | 1.12%   |
| 111-120        | 7        | 0.33%   |
| 71-80          | 5        | 0.23%   |
| 81-90          | 3        | 0.14%   |
| 131-140        | 3        | 0.14%   |
| 61-70          | 1        | 0.05%   |
| 121-130        | 1        | 0.05%   |
| 91-100         | 1        | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1503     | 72.4%   |
| 101-120 | 371      | 17.87%  |
| 1-50    | 94       | 4.53%   |
| 121-160 | 61       | 2.94%   |
| Unknown | 27       | 1.3%    |
| 161-240 | 20       | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1962     | 89.3%   |
| 2     | 175      | 7.97%   |
| 0     | 42       | 1.91%   |
| 3     | 15       | 0.68%   |
| 4     | 2        | 0.09%   |
| 7     | 1        | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1436     | 49.57%  |
| Intel                           | 747      | 25.79%  |
| Qualcomm Atheros                | 187      | 6.45%   |
| Ralink Technology               | 87       | 3%      |
| Broadcom                        | 68       | 2.35%   |
| Nvidia                          | 58       | 2%      |
| TP-Link                         | 38       | 1.31%   |
| Ralink                          | 35       | 1.21%   |
| Marvell Technology Group        | 22       | 0.76%   |
| Broadcom Limited                | 21       | 0.72%   |
| Qualcomm Atheros Communications | 20       | 0.69%   |
| D-Link System                   | 15       | 0.52%   |
| NetGear                         | 13       | 0.45%   |
| Huawei Technologies             | 11       | 0.38%   |
| VIA Technologies                | 10       | 0.35%   |
| MediaTek                        | 10       | 0.35%   |
| D-Link                          | 10       | 0.35%   |
| Motorola PCS                    | 9        | 0.31%   |
| Samsung Electronics             | 8        | 0.28%   |
| Aquantia                        | 8        | 0.28%   |
| Microsoft                       | 7        | 0.24%   |
| IMC Networks                    | 6        | 0.21%   |
| Edimax Technology               | 6        | 0.21%   |
| Belkin Components               | 6        | 0.21%   |
| Xiaomi                          | 5        | 0.17%   |
| ASUSTek Computer                | 5        | 0.17%   |
| ASIX Electronics                | 4        | 0.14%   |
| Mellanox Technologies           | 3        | 0.1%    |
| AVM                             | 3        | 0.1%    |
| 3Com                            | 3        | 0.1%    |
| ZTE WCDMA Technologies MSM      | 2        | 0.07%   |
| Spreadtrum Communications       | 2        | 0.07%   |
| OnePlus Technology (Shenzhen)   | 2        | 0.07%   |
| Mercucys                        | 2        | 0.07%   |
| JMicron Technology              | 2        | 0.07%   |
| HTC (High Tech Computer)        | 2        | 0.07%   |
| Chu Yuen Enterprise             | 2        | 0.07%   |
| ZyXEL Communications            | 1        | 0.03%   |
| ZyDAS                           | 1        | 0.03%   |
| vivo                            | 1        | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1181     | 36.92%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 81       | 2.53%   |
| Intel Ethernet Connection I217-LM                                      | 77       | 2.41%   |
| Realtek RTL8125 2.5GbE Controller                                      | 76       | 2.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 72       | 2.25%   |
| Intel I211 Gigabit Network Connection                                  | 61       | 1.91%   |
| Intel Wi-Fi 6 AX200                                                    | 58       | 1.81%   |
| Intel Ethernet Connection (2) I219-V                                   | 54       | 1.69%   |
| Intel 82579V Gigabit Network Connection                                | 44       | 1.38%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 40       | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 38       | 1.19%   |
| Ralink MT7601U Wireless Adapter                                        | 38       | 1.19%   |
| Nvidia MCP61 Ethernet                                                  | 35       | 1.09%   |
| Intel Ethernet Connection (7) I219-V                                   | 35       | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 31       | 0.97%   |
| Intel Ethernet Controller I225-V                                       | 30       | 0.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 29       | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                                  | 24       | 0.75%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 23       | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 21       | 0.66%   |
| Intel Ethernet Connection I217-V                                       | 21       | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 20       | 0.63%   |
| Intel Wireless 7260                                                    | 18       | 0.56%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 18       | 0.56%   |
| Intel Wireless 3165                                                    | 17       | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 16       | 0.5%    |
| Ralink RT5370 Wireless Adapter                                         | 16       | 0.5%    |
| Intel Ethernet Connection (2) I218-V                                   | 16       | 0.5%    |
| Intel 82574L Gigabit Network Connection                                | 15       | 0.47%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 14       | 0.44%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 14       | 0.44%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 14       | 0.44%   |
| Qualcomm Atheros AR9271 802.11n                                        | 14       | 0.44%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 14       | 0.44%   |
| Intel Wireless 7265                                                    | 14       | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 14       | 0.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 13       | 0.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 12       | 0.38%   |
| Intel 82578DM Gigabit Network Connection                               | 12       | 0.38%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 12       | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 228      | 28.22%  |
| Realtek Semiconductor                 | 203      | 25.12%  |
| Qualcomm Atheros                      | 101      | 12.5%   |
| Ralink Technology                     | 87       | 10.77%  |
| TP-Link                               | 37       | 4.58%   |
| Ralink                                | 35       | 4.33%   |
| Qualcomm Atheros Communications       | 20       | 2.48%   |
| NetGear                               | 13       | 1.61%   |
| Broadcom                              | 11       | 1.36%   |
| D-Link                                | 10       | 1.24%   |
| MediaTek                              | 8        | 0.99%   |
| Microsoft                             | 7        | 0.87%   |
| IMC Networks                          | 6        | 0.74%   |
| Edimax Technology                     | 6        | 0.74%   |
| D-Link System                         | 6        | 0.74%   |
| Belkin Components                     | 6        | 0.74%   |
| ASUSTek Computer                      | 5        | 0.62%   |
| Broadcom Limited                      | 3        | 0.37%   |
| AVM                                   | 3        | 0.37%   |
| Mercucys                              | 2        | 0.25%   |
| Chu Yuen Enterprise                   | 2        | 0.25%   |
| ZyXEL Communications                  | 1        | 0.12%   |
| ZyDAS                                 | 1        | 0.12%   |
| TRENDnet                              | 1        | 0.12%   |
| Philips (or NXP)                      | 1        | 0.12%   |
| Logitec                               | 1        | 0.12%   |
| Linksys                               | 1        | 0.12%   |
| Gemtek                                | 1        | 0.12%   |
| BUFFALO                               | 1        | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 58       | 7.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 38       | 4.67%   |
| Ralink MT7601U Wireless Adapter                            | 38       | 4.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 31       | 3.81%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 23       | 2.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 20       | 2.46%   |
| Intel Wireless 7260                                        | 18       | 2.21%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]    | 18       | 2.21%   |
| Intel Wireless 3165                                        | 17       | 2.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 16       | 1.97%   |
| Ralink RT5370 Wireless Adapter                             | 16       | 1.97%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 14       | 1.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 14       | 1.72%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 14       | 1.72%   |
| Qualcomm Atheros AR9271 802.11n                            | 14       | 1.72%   |
| Intel Wireless 7265                                        | 14       | 1.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 13       | 1.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                      | 12       | 1.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 11       | 1.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]  | 11       | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 11       | 1.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 10       | 1.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 10       | 1.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 10       | 1.23%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 10       | 1.23%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter            | 9        | 1.11%   |
| Realtek 802.11ac NIC                                       | 9        | 1.11%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 8        | 0.98%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                     | 7        | 0.86%   |
| Ralink RT2561/RT61 802.11g PCI                             | 7        | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 7        | 0.86%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 7        | 0.86%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 6        | 0.74%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 6        | 0.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 6        | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 6        | 0.74%   |
| Microsoft Xbox 360 Wireless Adapter                        | 6        | 0.74%   |
| Intel Wireless 8260                                        | 6        | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                             | 6        | 0.74%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 6        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1366     | 59.19%  |
| Intel                             | 603      | 26.13%  |
| Qualcomm Atheros                  | 93       | 4.03%   |
| Nvidia                            | 58       | 2.51%   |
| Broadcom                          | 57       | 2.47%   |
| Marvell Technology Group          | 22       | 0.95%   |
| Broadcom Limited                  | 18       | 0.78%   |
| VIA Technologies                  | 10       | 0.43%   |
| Huawei Technologies               | 10       | 0.43%   |
| Motorola PCS                      | 9        | 0.39%   |
| D-Link System                     | 9        | 0.39%   |
| Samsung Electronics               | 8        | 0.35%   |
| Aquantia                          | 8        | 0.35%   |
| Xiaomi                            | 5        | 0.22%   |
| ASIX Electronics                  | 4        | 0.17%   |
| Mellanox Technologies             | 3        | 0.13%   |
| 3Com                              | 3        | 0.13%   |
| Spreadtrum Communications         | 2        | 0.09%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.09%   |
| MediaTek                          | 2        | 0.09%   |
| JMicron Technology                | 2        | 0.09%   |
| HTC (High Tech Computer)          | 2        | 0.09%   |
| vivo                              | 1        | 0.04%   |
| TP-Link                           | 1        | 0.04%   |
| T & A Mobile Phones               | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.04%   |
| Qualcomm                          | 1        | 0.04%   |
| OPPO Electronics                  | 1        | 0.04%   |
| Netchip Technology                | 1        | 0.04%   |
| Emulex                            | 1        | 0.04%   |
| DisplayLink                       | 1        | 0.04%   |
| Davicom Semiconductor             | 1        | 0.04%   |
| Adnaco Technology                 | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1181     | 49.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 81       | 3.4%    |
| Intel Ethernet Connection I217-LM                                      | 77       | 3.24%   |
| Realtek RTL8125 2.5GbE Controller                                      | 76       | 3.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 72       | 3.03%   |
| Intel I211 Gigabit Network Connection                                  | 61       | 2.56%   |
| Intel Ethernet Connection (2) I219-V                                   | 54       | 2.27%   |
| Intel 82579V Gigabit Network Connection                                | 44       | 1.85%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 40       | 1.68%   |
| Nvidia MCP61 Ethernet                                                  | 35       | 1.47%   |
| Intel Ethernet Connection (7) I219-V                                   | 35       | 1.47%   |
| Intel Ethernet Controller I225-V                                       | 30       | 1.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 29       | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                                  | 24       | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 21       | 0.88%   |
| Intel Ethernet Connection I217-V                                       | 21       | 0.88%   |
| Intel Ethernet Connection (2) I218-V                                   | 16       | 0.67%   |
| Intel 82574L Gigabit Network Connection                                | 15       | 0.63%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 14       | 0.59%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 14       | 0.59%   |
| Intel 82578DM Gigabit Network Connection                               | 12       | 0.5%    |
| Intel 82566DM-2 Gigabit Network Connection                             | 12       | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 11       | 0.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11       | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 11       | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 11       | 0.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 11       | 0.46%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 10       | 0.42%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 9        | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 9        | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 9        | 0.38%   |
| Intel 82578DC Gigabit Network Connection                               | 9        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8        | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 8        | 0.34%   |
| Intel Ethernet Connection (14) I219-V                                  | 8        | 0.34%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 8        | 0.34%   |
| Nvidia MCP77 Ethernet                                                  | 7        | 0.29%   |
| Intel Ethernet Connection (2) I218-LM                                  | 7        | 0.29%   |
| Intel 82567V-2 Gigabit Network Connection                              | 7        | 0.29%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 7        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2177     | 73.67%  |
| WiFi     | 773      | 26.16%  |
| Modem    | 4        | 0.14%   |
| Unknown  | 1        | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1835     | 85.03%  |
| WiFi     | 323      | 14.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1548     | 70.49%  |
| 2     | 574      | 26.14%  |
| 3     | 49       | 2.23%   |
| 0     | 18       | 0.82%   |
| 4     | 6        | 0.27%   |
| 5     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1537     | 69.77%  |
| Yes  | 666      | 30.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 206      | 42.83%  |
| Cambridge Silicon Radio         | 134      | 27.86%  |
| Realtek Semiconductor           | 36       | 7.48%   |
| ASUSTek Computer                | 25       | 5.2%    |
| Broadcom                        | 19       | 3.95%   |
| Qualcomm Atheros Communications | 18       | 3.74%   |
| IMC Networks                    | 12       | 2.49%   |
| MediaTek                        | 5        | 1.04%   |
| Apple                           | 4        | 0.83%   |
| Lite-On Technology              | 3        | 0.62%   |
| Dynex                           | 3        | 0.62%   |
| TP-Link                         | 2        | 0.42%   |
| Integrated System Solution      | 2        | 0.42%   |
| Accel Semiconductor             | 2        | 0.42%   |
| Unknown                         | 2        | 0.42%   |
| SiW                             | 1        | 0.21%   |
| SINO WEALTH                     | 1        | 0.21%   |
| Ralink                          | 1        | 0.21%   |
| Primax Electronics              | 1        | 0.21%   |
| Foxconn / Hon Hai               | 1        | 0.21%   |
| Edimax Technology               | 1        | 0.21%   |
| Dell                            | 1        | 0.21%   |
| Belkin Components               | 1        | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 134      | 27.86%  |
| Intel Bluetooth wireless interface                       | 59       | 12.27%  |
| Intel AX200 Bluetooth                                    | 54       | 11.23%  |
| Intel Wireless-AC 3168 Bluetooth                         | 28       | 5.82%   |
| Realtek Bluetooth Radio                                  | 21       | 4.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 17       | 3.53%   |
| Intel AX201 Bluetooth                                    | 17       | 3.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 13       | 2.7%    |
| Intel AX210 Bluetooth                                    | 12       | 2.49%   |
| Realtek  Bluetooth 4.2 Adapter                           | 11       | 2.29%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 11       | 2.29%   |
| IMC Networks Bluetooth Radio                             | 9        | 1.87%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 9        | 1.87%   |
| ASUS ASUS USB-BT500                                      | 8        | 1.66%   |
| Qualcomm Atheros  Bluetooth Device                       | 7        | 1.46%   |
| MediaTek Wireless_Device                                 | 5        | 1.04%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 4        | 0.83%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 4        | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 3        | 0.62%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 3        | 0.62%   |
| TP-Link TP-Link Bluetooth USB Adapter                    | 2        | 0.42%   |
| Realtek RTL8821A Bluetooth                               | 2        | 0.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 2        | 0.42%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 0.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 2        | 0.42%   |
| Intel AX211 Bluetooth                                    | 2        | 0.42%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 2        | 0.42%   |
| ASUS Qualcomm Bluetooth 4.1                              | 2        | 0.42%   |
| ASUS Bluetooth Radio                                     | 2        | 0.42%   |
| ASUS Bluetooth Adapter                                   | 2        | 0.42%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 2        | 0.42%   |
| Accel Bluetooth Device                                   | 2        | 0.42%   |
| Unknown                                                  | 2        | 0.42%   |
| SiW SiW                                                  | 1        | 0.21%   |
| SINO WEALTH RK Bluetooth Keyboar                         | 1        | 0.21%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 1        | 0.21%   |
| Realtek 802.11ac WLAN Adapter                            | 1        | 0.21%   |
| Ralink RT3290 Bluetooth                                  | 1        | 0.21%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter            | 1        | 0.21%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1        | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1411     | 41.81%  |
| AMD                                          | 884      | 26.19%  |
| Nvidia                                       | 737      | 21.84%  |
| C-Media Electronics                          | 82       | 2.43%   |
| Creative Labs                                | 51       | 1.51%   |
| Logitech                                     | 29       | 0.86%   |
| Texas Instruments                            | 19       | 0.56%   |
| JMTek                                        | 11       | 0.33%   |
| Creative Technology                          | 11       | 0.33%   |
| ASUSTek Computer                             | 11       | 0.33%   |
| Generalplus Technology                       | 9        | 0.27%   |
| VIA Technologies                             | 7        | 0.21%   |
| GN Netcom                                    | 7        | 0.21%   |
| Plantronics                                  | 6        | 0.18%   |
| XMOS                                         | 4        | 0.12%   |
| Tenx Technology                              | 4        | 0.12%   |
| Kingston Technology                          | 4        | 0.12%   |
| Blue Microphones                             | 4        | 0.12%   |
| SteelSeries ApS                              | 3        | 0.09%   |
| Sony                                         | 3        | 0.09%   |
| Samson Technologies                          | 3        | 0.09%   |
| Razer USA                                    | 3        | 0.09%   |
| KTMicro                                      | 3        | 0.09%   |
| Ensoniq                                      | 3        | 0.09%   |
| Corsair                                      | 3        | 0.09%   |
| BEHRINGER International                      | 3        | 0.09%   |
| Trust                                        | 2        | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.06%   |
| ROCCAT                                       | 2        | 0.06%   |
| QinHeng Electronics                          | 2        | 0.06%   |
| PreSonus Audio Electronics                   | 2        | 0.06%   |
| Micro Star International                     | 2        | 0.06%   |
| Medeli Electronics                           | 2        | 0.06%   |
| Hewlett-Packard                              | 2        | 0.06%   |
| GYROCOM C&C                                  | 2        | 0.06%   |
| Giga-Byte Technology                         | 2        | 0.06%   |
| FiiO Electronics Technology                  | 2        | 0.06%   |
| Audient                                      | 2        | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.03%   |
| ZOOM                                         | 1        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 214      | 5.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 191      | 4.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 191      | 4.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 164      | 4.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 137      | 3.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 127      | 3.19%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 124      | 3.12%   |
| AMD FCH Azalia Controller                                                         | 123      | 3.09%   |
| AMD Starship/Matisse HD Audio Controller                                          | 116      | 2.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 105      | 2.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 91       | 2.29%   |
| Intel 200 Series PCH HD Audio                                                     | 80       | 2.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 77       | 1.94%   |
| Nvidia High Definition Audio Controller                                           | 72       | 1.81%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 70       | 1.76%   |
| Intel Cannon Lake PCH cAVS                                                        | 68       | 1.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 68       | 1.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 66       | 1.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 64       | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 62       | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 59       | 1.48%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 58       | 1.46%   |
| Nvidia GF108 High Definition Audio Controller                                     | 51       | 1.28%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 50       | 1.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 46       | 1.16%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 42       | 1.06%   |
| Nvidia MCP61 High Definition Audio                                                | 41       | 1.03%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 38       | 0.96%   |
| Nvidia GF119 HDMI Audio Controller                                                | 37       | 0.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 36       | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                                     | 34       | 0.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 32       | 0.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 31       | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                     | 29       | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                                | 29       | 0.73%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 28       | 0.7%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 26       | 0.65%   |
| Nvidia GP108 High Definition Audio Controller                                     | 25       | 0.63%   |
| AMD Trinity HDMI Audio Controller                                                 | 25       | 0.63%   |
| AMD Kabini HDMI/DP Audio                                                          | 25       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 486      | 18.57%  |
| Kingston            | 464      | 17.73%  |
| Samsung Electronics | 263      | 10.05%  |
| Corsair             | 198      | 7.57%   |
| SK hynix            | 196      | 7.49%   |
| Crucial             | 187      | 7.15%   |
| G.Skill             | 166      | 6.34%   |
| Micron Technology   | 142      | 5.43%   |
| A-DATA Technology   | 58       | 2.22%   |
| Unknown             | 49       | 1.87%   |
| Patriot             | 37       | 1.41%   |
| Nanya Technology    | 36       | 1.38%   |
| Ramaxel Technology  | 31       | 1.18%   |
| Team                | 29       | 1.11%   |
| GOODRAM             | 22       | 0.84%   |
| Elpida              | 22       | 0.84%   |
| Transcend           | 19       | 0.73%   |
| Smart               | 19       | 0.73%   |
| AMD                 | 11       | 0.42%   |
| Silicon Power       | 10       | 0.38%   |
| Kingmax             | 9        | 0.34%   |
| GeIL                | 9        | 0.34%   |
| Apacer              | 8        | 0.31%   |
| Unknown (ABCD)      | 7        | 0.27%   |
| PNY                 | 7        | 0.27%   |
| CSX                 | 7        | 0.27%   |
| Unifosa             | 6        | 0.23%   |
| Teikon              | 5        | 0.19%   |
| Qimonda             | 5        | 0.19%   |
| Super Talent        | 4        | 0.15%   |
| OM Nanotech         | 4        | 0.15%   |
| Ramos Technology    | 3        | 0.11%   |
| Kllisre             | 3        | 0.11%   |
| KLEVV               | 3        | 0.11%   |
| Goldkey             | 3        | 0.11%   |
| Wilk Elektronik     | 2        | 0.08%   |
| V-GeN               | 2        | 0.08%   |
| Unknown (2C0B)      | 2        | 0.08%   |
| Unknown (0x0DD5)    | 2        | 0.08%   |
| Sesame              | 2        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown                                                | 49       | 1.69%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 40       | 1.38%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 39       | 1.35%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 34       | 1.18%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 28       | 0.97%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 23       | 0.8%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 23       | 0.8%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 21       | 0.73%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 20       | 0.69%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s               | 18       | 0.62%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s  | 18       | 0.62%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s    | 18       | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 17       | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 16       | 0.55%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 16       | 0.55%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s | 16       | 0.55%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 16       | 0.55%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 15       | 0.52%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s    | 15       | 0.52%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s         | 15       | 0.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 14       | 0.48%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 14       | 0.48%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 13       | 0.45%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 13       | 0.45%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 13       | 0.45%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 13       | 0.45%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 13       | 0.45%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s    | 13       | 0.45%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 12       | 0.41%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s | 12       | 0.41%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 12       | 0.41%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 12       | 0.41%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s  | 12       | 0.41%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 11       | 0.38%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 11       | 0.38%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s    | 11       | 0.38%   |
| Unknown RAM Module 1GB DIMM 800MT/s                    | 10       | 0.35%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 10       | 0.35%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 10       | 0.35%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s  | 10       | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 921      | 41.3%   |
| DDR4    | 743      | 33.32%  |
| Unknown | 187      | 8.39%   |
| DDR2    | 171      | 7.67%   |
| SDRAM   | 157      | 7.04%   |
| DDR     | 34       | 1.52%   |
| LPDDR4  | 9        | 0.4%    |
| DDR5    | 7        | 0.31%   |
| DRAM    | 1        | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2033     | 93.51%  |
| SODIMM       | 133      | 6.12%   |
| RIMM         | 4        | 0.18%   |
| FB-DIMM      | 3        | 0.14%   |
| Row Of Chips | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 830      | 33.32%  |
| 4096  | 734      | 29.47%  |
| 2048  | 511      | 20.51%  |
| 16384 | 210      | 8.43%   |
| 1024  | 139      | 5.58%   |
| 32768 | 45       | 1.81%   |
| 512   | 21       | 0.84%   |
| 12288 | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 566      | 22.48%  |
| 1333    | 373      | 14.81%  |
| 800     | 142      | 5.64%   |
| 3200    | 137      | 5.44%   |
| 2400    | 134      | 5.32%   |
| 3600    | 117      | 4.65%   |
| 2667    | 105      | 4.17%   |
| 2133    | 105      | 4.17%   |
| Unknown | 86       | 3.42%   |
| 667     | 84       | 3.34%   |
| 1867    | 57       | 2.26%   |
| 1866    | 55       | 2.18%   |
| 2666    | 49       | 1.95%   |
| 1800    | 36       | 1.43%   |
| 3400    | 35       | 1.39%   |
| 3000    | 32       | 1.27%   |
| 1066    | 29       | 1.15%   |
| 400     | 25       | 0.99%   |
| 4000    | 23       | 0.91%   |
| 3733    | 23       | 0.91%   |
| 533     | 23       | 0.91%   |
| 1067    | 21       | 0.83%   |
| 2933    | 20       | 0.79%   |
| 3466    | 17       | 0.68%   |
| 2048    | 15       | 0.6%    |
| 1334    | 14       | 0.56%   |
| 3800    | 13       | 0.52%   |
| 3066    | 13       | 0.52%   |
| 3666    | 11       | 0.44%   |
| 2000    | 9        | 0.36%   |
| 49926   | 8        | 0.32%   |
| 1639    | 8        | 0.32%   |
| 333     | 7        | 0.28%   |
| 2800    | 6        | 0.24%   |
| 2200    | 6        | 0.24%   |
| 1648    | 6        | 0.24%   |
| 3500    | 5        | 0.2%    |
| 3334    | 5        | 0.2%    |
| 3333    | 5        | 0.2%    |
| 2866    | 5        | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 55       | 37.67%  |
| Brother Industries    | 35       | 23.97%  |
| Canon                 | 18       | 12.33%  |
| Samsung Electronics   | 13       | 8.9%    |
| Seiko Epson           | 9        | 6.16%   |
| Lexmark International | 5        | 3.42%   |
| Xerox                 | 3        | 2.05%   |
| Kyocera               | 2        | 1.37%   |
| Zebra                 | 1        | 0.68%   |
| Ricoh                 | 1        | 0.68%   |
| QinHeng Electronics   | 1        | 0.68%   |
| NXP Semiconductors    | 1        | 0.68%   |
| Dymo-CoStar           | 1        | 0.68%   |
| Citizen               | 1        | 0.68%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Samsung M2070 Series                         | 4        | 2.74%   |
| HP LaserJet 1020                             | 3        | 2.05%   |
| HP LaserJet 1010                             | 3        | 2.05%   |
| HP ENVY 4520 series                          | 3        | 2.05%   |
| Seiko Epson ET-4760 Series                   | 2        | 1.37%   |
| Samsung SCX-3400 Series                      | 2        | 1.37%   |
| Samsung M2020 Series                         | 2        | 1.37%   |
| Samsung CLP-310 Color Laser Printer          | 2        | 1.37%   |
| HP LaserJet P1005                            | 2        | 1.37%   |
| HP LaserJet 1200                             | 2        | 1.37%   |
| HP LaserJet 1018                             | 2        | 1.37%   |
| HP Ink Tank Wireless 410 series              | 2        | 1.37%   |
| HP ENVY 4500 series                          | 2        | 1.37%   |
| HP DeskJet 5550                              | 2        | 1.37%   |
| HP DeskJet 2700 series                       | 2        | 1.37%   |
| HP DeskJet 2300 series                       | 2        | 1.37%   |
| HP Deskjet 1050 J410                         | 2        | 1.37%   |
| Canon TS5100 series                          | 2        | 1.37%   |
| Canon PIXMA MG3600 Series                    | 2        | 1.37%   |
| Brother Printer                              | 2        | 1.37%   |
| Brother MFC-L2710DW series                   | 2        | 1.37%   |
| Brother MFC-J470DW                           | 2        | 1.37%   |
| Brother HL-L2370DW series                    | 2        | 1.37%   |
| Brother HL-L2300D series                     | 2        | 1.37%   |
| Brother DCP-T310                             | 2        | 1.37%   |
| Zebra LP2824                                 | 1        | 0.68%   |
| Xerox Phaser 6510                            | 1        | 0.68%   |
| Xerox Phaser 6010N                           | 1        | 0.68%   |
| Xerox Phaser 3260                            | 1        | 0.68%   |
| Seiko Epson XP-2100 Series                   | 1        | 0.68%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.68%   |
| Seiko Epson L365 Series                      | 1        | 0.68%   |
| Seiko Epson L3150 Series                     | 1        | 0.68%   |
| Seiko Epson L120 Series                      | 1        | 0.68%   |
| Seiko Epson ET-3750 Series                   | 1        | 0.68%   |
| Seiko Epson EPSON WF-2510 Series             | 1        | 0.68%   |
| Samsung ML-2850 Series                       | 1        | 0.68%   |
| Samsung ML-1640 Series Laser Printer         | 1        | 0.68%   |
| Samsung M267x 287x Series                    | 1        | 0.68%   |
| Ricoh SP 213w                                | 1        | 0.68%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 13       | 72.22%  |
| Seiko Epson     | 2        | 11.11%  |
| Mustek Systems  | 2        | 11.11%  |
| Hewlett-Packard | 1        | 5.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 2        | 11.11%  |
| Canon CanoScan N670U/N676U/LiDE 20            | 2        | 11.11%  |
| Canon CanoScan N1240U/LiDE 30                 | 2        | 11.11%  |
| Canon CanoScan LiDE 120                       | 2        | 11.11%  |
| Canon CanoScan LiDE 110                       | 2        | 11.11%  |
| Canon CanoScan LiDE 100                       | 2        | 11.11%  |
| Mustek Systems SNAPSCAN e22                   | 1        | 5.56%   |
| Mustek Systems ScanExpress 1200 CU            | 1        | 5.56%   |
| HP ScanJet 2400c                              | 1        | 5.56%   |
| Canon CanoScan LIDE 25                        | 1        | 5.56%   |
| Canon CanoScan LiDE 210                       | 1        | 5.56%   |
| Canon CanoScan 5200F                          | 1        | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 116      | 39.46%  |
| Microdia                      | 22       | 7.48%   |
| Microsoft                     | 19       | 6.46%   |
| Generalplus Technology        | 12       | 4.08%   |
| Realtek Semiconductor         | 10       | 3.4%    |
| KYE Systems (Mouse Systems)   | 9        | 3.06%   |
| Chicony Electronics           | 8        | 2.72%   |
| Aveo Technology               | 7        | 2.38%   |
| Z-Star Microelectronics       | 6        | 2.04%   |
| Cubeternet                    | 6        | 2.04%   |
| Sunplus Innovation Technology | 5        | 1.7%    |
| Samsung Electronics           | 5        | 1.7%    |
| Hewlett-Packard               | 5        | 1.7%    |
| Apple                         | 5        | 1.7%    |
| Trust                         | 4        | 1.36%   |
| ARC International             | 4        | 1.36%   |
| Unknown                       | 3        | 1.02%   |
| Jieli Technology              | 3        | 1.02%   |
| GEMBIRD                       | 3        | 1.02%   |
| Creative Technology           | 3        | 1.02%   |
| Pixart Imaging                | 2        | 0.68%   |
| MacroSilicon                  | 2        | 0.68%   |
| IMC Networks                  | 2        | 0.68%   |
| Genesys Logic                 | 2        | 0.68%   |
| AVerMedia Technologies        | 2        | 0.68%   |
| Alcor Micro                   | 2        | 0.68%   |
| 2M UVC CAMERA                 | 2        | 0.68%   |
| WCM_USB                       | 1        | 0.34%   |
| WaveRider Communications      | 1        | 0.34%   |
| Valve Software                | 1        | 0.34%   |
| USB3.0 HD Audio Capture       | 1        | 0.34%   |
| Tobii Technology AB           | 1        | 0.34%   |
| SunplusIT                     | 1        | 0.34%   |
| Sonix Technology              | 1        | 0.34%   |
| Silicon Motion                | 1        | 0.34%   |
| SiGma Micro                   | 1        | 0.34%   |
| SHENZHEN EMEET TECHNOLOGY     | 1        | 0.34%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 0.34%   |
| Remo Tech                     | 1        | 0.34%   |
| Razer USA                     | 1        | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 29       | 9.8%    |
| Logitech HD Webcam C525                 | 14       | 4.73%   |
| Logitech HD Pro Webcam C920             | 13       | 4.39%   |
| Generalplus GENERAL WEBCAM              | 11       | 3.72%   |
| Microsoft LifeCam HD-3000               | 10       | 3.38%   |
| Logitech Webcam C170                    | 9        | 3.04%   |
| Logitech Webcam C310                    | 7        | 2.36%   |
| Logitech HD Webcam C615                 | 7        | 2.36%   |
| Aveo USB2.0 Camera                      | 6        | 2.03%   |
| Samsung Galaxy series, misc. (MTP mode) | 5        | 1.69%   |
| Microdia Camera                         | 5        | 1.69%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 5        | 1.69%   |
| Microdia Webcam Vitade AF               | 4        | 1.35%   |
| Microdia USB 2.0 Camera                 | 4        | 1.35%   |
| ARC International Camera                | 4        | 1.35%   |
| Unknown HD camera                       | 3        | 1.01%   |
| Microdia Integrated Camera              | 3        | 1.01%   |
| Logitech Webcam Pro 9000                | 3        | 1.01%   |
| Logitech HD Webcam C510                 | 3        | 1.01%   |
| Logitech C922 Pro Stream Webcam         | 3        | 1.01%   |
| Jieli USB PHY 2.0                       | 3        | 1.01%   |
| HP HP Webcam HD 2300                    | 3        | 1.01%   |
| Cubeternet USB2.0 Camera                | 3        | 1.01%   |
| Z-Star A4 TECH USB2.0 PC Camera J       | 2        | 0.68%   |
| Trust WB-6250X Webcam                   | 2        | 0.68%   |
| Sunplus HD 720P webcam                  | 2        | 0.68%   |
| Sunplus Full HD webcam                  | 2        | 0.68%   |
| Realtek USB Camera                      | 2        | 0.68%   |
| Realtek Thronmax Webcam Mic             | 2        | 0.68%   |
| Realtek NexiGo N660P FHD Webcam         | 2        | 0.68%   |
| Realtek FULL HD 1080P Webcam            | 2        | 0.68%   |
| Microsoft LifeCam VX-800                | 2        | 0.68%   |
| Microsoft LifeCam Studio                | 2        | 0.68%   |
| Microsoft LifeCam Cinema                | 2        | 0.68%   |
| MacroSilicon USB Video                  | 2        | 0.68%   |
| Logitech Webcam C930e                   | 2        | 0.68%   |
| Logitech Webcam C250                    | 2        | 0.68%   |
| Logitech Webcam C110                    | 2        | 0.68%   |
| Logitech QuickCam Pro 9000              | 2        | 0.68%   |
| Logitech QuickCam E 3500                | 2        | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Validity Sensors      | 1        | 33.33%  |
| Upek                  | 1        | 33.33%  |
| LighTuning Technology | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 1        | 33.33%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 33.33%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 25%     |
| Gemalto (was Gemplus) | 2        | 25%     |
| Bit4id                | 2        | 25%     |
| SCM Microsystems      | 1        | 12.5%   |
| Cherry                | 1        | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 2        | 25%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 2        | 25%     |
| SCM Microsystems CLOUD 2700 F Smart Card Reader   | 1        | 12.5%   |
| Cherry Smart Terminal XX44                        | 1        | 12.5%   |
| Bit4id miniLector EVO                             | 1        | 12.5%   |
| BIT4ID miniLector AIR NFC v3                      | 1        | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1957     | 89.2%   |
| 1     | 217      | 9.89%   |
| 2     | 14       | 0.64%   |
| 3     | 4        | 0.18%   |
| 7     | 1        | 0.05%   |
| 4     | 1        | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 125      | 49.8%   |
| Net/wireless             | 49       | 19.52%  |
| Unassigned class         | 19       | 7.57%   |
| Communication controller | 16       | 6.37%   |
| Multimedia controller    | 9        | 3.59%   |
| Bluetooth                | 8        | 3.19%   |
| Chipcard                 | 7        | 2.79%   |
| Wireless                 | 3        | 1.2%    |
| Network                  | 3        | 1.2%    |
| Fingerprint reader       | 3        | 1.2%    |
| Camera                   | 3        | 1.2%    |
| Storage/raid             | 2        | 0.8%    |
| Net/ethernet             | 2        | 0.8%    |
| Card reader              | 2        | 0.8%    |

