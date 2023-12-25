MX - Tested Hardware & Statistics (Desktops)
--------------------------------------------

A project to collect tested hardware configurations for MX.

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

Total: 297

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 033FF6 A00                  | [88cad415fb](https://linux-hardware.org/?probe=88cad415fb) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f912bcd96a](https://linux-hardware.org/?probe=f912bcd96a) | Dec 20, 2023 |
| ASUSTek       | M4A87TD/USB3                | [df3eb3c253](https://linux-hardware.org/?probe=df3eb3c253) | Dec 17, 2023 |
| HP            | 8265                        | [cc0b59e7f7](https://linux-hardware.org/?probe=cc0b59e7f7) | Dec 13, 2023 |
| Gigabyte      | MRHM7AP                     | [ba4400c919](https://linux-hardware.org/?probe=ba4400c919) | Dec 13, 2023 |
| ASRock        | A620M Pro RS WiFi           | [3bbc394b2e](https://linux-hardware.org/?probe=3bbc394b2e) | Dec 08, 2023 |
| Gigabyte      | G41M-ES2L                   | [442d7a2388](https://linux-hardware.org/?probe=442d7a2388) | Dec 03, 2023 |
| Dell          | 03NVJ6 A03                  | [9a5c924695](https://linux-hardware.org/?probe=9a5c924695) | Nov 26, 2023 |
| MSI           | A68HM-P33 V2                | [bee7ef1689](https://linux-hardware.org/?probe=bee7ef1689) | Nov 22, 2023 |
| HP            | 8265                        | [d798ead6f7](https://linux-hardware.org/?probe=d798ead6f7) | Nov 20, 2023 |
| Dell          | 0MNPJ9 A01                  | [80ded618fb](https://linux-hardware.org/?probe=80ded618fb) | Nov 19, 2023 |
| Gigabyte      | B365M DS3H                  | [23196bda4d](https://linux-hardware.org/?probe=23196bda4d) | Nov 14, 2023 |
| HP            | 3397                        | [67e178009d](https://linux-hardware.org/?probe=67e178009d) | Nov 09, 2023 |
| Gigabyte      | B365M DS3H                  | [25ab11fca1](https://linux-hardware.org/?probe=25ab11fca1) | Nov 08, 2023 |
| ASUSTek       | Maximus VIII HERO           | [0d65b73ae2](https://linux-hardware.org/?probe=0d65b73ae2) | Nov 07, 2023 |
| HP            | 2B34                        | [52737869e2](https://linux-hardware.org/?probe=52737869e2) | Nov 06, 2023 |
| ASRock        | A320M Pro4-F                | [7dab52cd8c](https://linux-hardware.org/?probe=7dab52cd8c) | Nov 05, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [e95902544f](https://linux-hardware.org/?probe=e95902544f) | Nov 03, 2023 |
| Gigabyte      | B365M DS3H                  | [0a5b6171b7](https://linux-hardware.org/?probe=0a5b6171b7) | Oct 30, 2023 |
| Intel         | H81                         | [2e37259d45](https://linux-hardware.org/?probe=2e37259d45) | Oct 29, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [2cb1fb1ec9](https://linux-hardware.org/?probe=2cb1fb1ec9) | Oct 27, 2023 |
| HP            | 339A                        | [d0deadc097](https://linux-hardware.org/?probe=d0deadc097) | Oct 27, 2023 |
| Lenovo        | 376D SDK0T76465 WIN 3422... | [2a97bb6c00](https://linux-hardware.org/?probe=2a97bb6c00) | Oct 27, 2023 |
| AZW           | SER V1                      | [8c734a7dfc](https://linux-hardware.org/?probe=8c734a7dfc) | Oct 21, 2023 |
| MSI           | A68HM-E33 V2                | [f6a5fcd391](https://linux-hardware.org/?probe=f6a5fcd391) | Oct 21, 2023 |
| Acer          | Aspire TC-1760              | [9e4ac23c4b](https://linux-hardware.org/?probe=9e4ac23c4b) | Oct 19, 2023 |
| Gigabyte      | Z690 UD AX DDR4             | [273e4a294a](https://linux-hardware.org/?probe=273e4a294a) | Oct 15, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [665eba904c](https://linux-hardware.org/?probe=665eba904c) | Oct 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [00fc33d73e](https://linux-hardware.org/?probe=00fc33d73e) | Oct 13, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [6f4fb2dff4](https://linux-hardware.org/?probe=6f4fb2dff4) | Oct 10, 2023 |
| ASUSTek       | PRIME H510M-D               | [e583e35b95](https://linux-hardware.org/?probe=e583e35b95) | Oct 03, 2023 |
| ASUSTek       | PRIME H510M-D               | [538889d79f](https://linux-hardware.org/?probe=538889d79f) | Oct 03, 2023 |
| MSI           | G41M4                       | [0554e9757f](https://linux-hardware.org/?probe=0554e9757f) | Sep 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4054ad9d77](https://linux-hardware.org/?probe=4054ad9d77) | Sep 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [76d936bb5b](https://linux-hardware.org/?probe=76d936bb5b) | Sep 26, 2023 |
| ASUSTek       | Z97-P                       | [d72c4b5cce](https://linux-hardware.org/?probe=d72c4b5cce) | Sep 06, 2023 |
| Foxconn       | 2ABF                        | [baad816533](https://linux-hardware.org/?probe=baad816533) | Sep 05, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [a9fdf4f92b](https://linux-hardware.org/?probe=a9fdf4f92b) | Sep 03, 2023 |
| ASRock        | J4205-ITX                   | [8831793b97](https://linux-hardware.org/?probe=8831793b97) | Sep 03, 2023 |
| MSI           | A68HM-E33 V2                | [af96cda252](https://linux-hardware.org/?probe=af96cda252) | Sep 02, 2023 |
| Foxconn       | 2A92                        | [50ca8342d7](https://linux-hardware.org/?probe=50ca8342d7) | Sep 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [51ea627e30](https://linux-hardware.org/?probe=51ea627e30) | Aug 25, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [c8e9f89359](https://linux-hardware.org/?probe=c8e9f89359) | Aug 25, 2023 |
| Pegatron      | 2AD5                        | [fcb0ac31fe](https://linux-hardware.org/?probe=fcb0ac31fe) | Aug 23, 2023 |
| Gigabyte      | MZGLKCP-00                  | [c6f294e543](https://linux-hardware.org/?probe=c6f294e543) | Aug 21, 2023 |
| Gigabyte      | MZGLKCP-00                  | [d6e0b89f34](https://linux-hardware.org/?probe=d6e0b89f34) | Aug 21, 2023 |
| Biostar       | H310MHC2                    | [12f3b0d269](https://linux-hardware.org/?probe=12f3b0d269) | Aug 20, 2023 |
| Gigabyte      | H510M S2H                   | [e5661bef5b](https://linux-hardware.org/?probe=e5661bef5b) | Aug 16, 2023 |
| ASUSTek       | F1A75-M LE                  | [f059d25382](https://linux-hardware.org/?probe=f059d25382) | Aug 14, 2023 |
| MSI           | A68HM-E33 V2                | [44556227ff](https://linux-hardware.org/?probe=44556227ff) | Aug 05, 2023 |
| OEM           | Intel H81                   | [82606b5050](https://linux-hardware.org/?probe=82606b5050) | Aug 03, 2023 |
| Gigabyte      | B560 AORUS PRO AX           | [c7e057da76](https://linux-hardware.org/?probe=c7e057da76) | Aug 02, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [a0270160ad](https://linux-hardware.org/?probe=a0270160ad) | Aug 02, 2023 |
| Intel         | JSL MRD                     | [feb19ee725](https://linux-hardware.org/?probe=feb19ee725) | Jul 29, 2023 |
| Intel         | JSL MRD                     | [ca5990cfa3](https://linux-hardware.org/?probe=ca5990cfa3) | Jul 29, 2023 |
| ASUSTek       | LEUCITE3                    | [bb2046286f](https://linux-hardware.org/?probe=bb2046286f) | Jul 26, 2023 |
| ASUSTek       | LEUCITE3                    | [6ced09890f](https://linux-hardware.org/?probe=6ced09890f) | Jul 26, 2023 |
| ASRock        | B660M-HDV                   | [3a0685bcf0](https://linux-hardware.org/?probe=3a0685bcf0) | Jul 18, 2023 |
| Medion        | MS-7667                     | [52ff08b634](https://linux-hardware.org/?probe=52ff08b634) | Jul 09, 2023 |
| AOpen         | D1009 A1A4                  | [2819e086aa](https://linux-hardware.org/?probe=2819e086aa) | Jul 02, 2023 |
| ASRock        | A620M Pro RS WiFi           | [d04862302e](https://linux-hardware.org/?probe=d04862302e) | Jul 01, 2023 |
| MSI           | B350M MORTAR                | [6e5323aa42](https://linux-hardware.org/?probe=6e5323aa42) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | [fc4b07cbb0](https://linux-hardware.org/?probe=fc4b07cbb0) | Jun 09, 2023 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [c64fbbcad9](https://linux-hardware.org/?probe=c64fbbcad9) | Jun 02, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [7070e55aa0](https://linux-hardware.org/?probe=7070e55aa0) | Jun 01, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [5ae19394fc](https://linux-hardware.org/?probe=5ae19394fc) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [14548bc77a](https://linux-hardware.org/?probe=14548bc77a) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | [5ca1acbf9b](https://linux-hardware.org/?probe=5ca1acbf9b) | May 19, 2023 |
| Unknown       | Unknown                     | [58066198c4](https://linux-hardware.org/?probe=58066198c4) | May 18, 2023 |
| Dell          | 06X1TJ A00                  | [d3107c9603](https://linux-hardware.org/?probe=d3107c9603) | May 14, 2023 |
| Gigabyte      | 990FXA-UD3                  | [3bc96663a8](https://linux-hardware.org/?probe=3bc96663a8) | May 14, 2023 |
| Gigabyte      | X670 GAMING X AX            | [ebd2a32ce2](https://linux-hardware.org/?probe=ebd2a32ce2) | May 12, 2023 |
| Gigabyte      | X670 GAMING X AX            | [352c0902e9](https://linux-hardware.org/?probe=352c0902e9) | May 11, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [f894b9a2c4](https://linux-hardware.org/?probe=f894b9a2c4) | May 07, 2023 |
| ASRock        | P55 Extreme                 | [e8721751c6](https://linux-hardware.org/?probe=e8721751c6) | May 03, 2023 |
| ASRock        | P55 Extreme                 | [e426e8e40b](https://linux-hardware.org/?probe=e426e8e40b) | May 03, 2023 |
| ASRock        | N68-S UCC                   | [f62abcbed6](https://linux-hardware.org/?probe=f62abcbed6) | May 02, 2023 |
| Dell          | 0PC5F7 A02                  | [2d1086090c](https://linux-hardware.org/?probe=2d1086090c) | May 01, 2023 |
| ASUSTek       | Z97-P                       | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| Gigabyte      | H61MA-D3V                   | [a37deef915](https://linux-hardware.org/?probe=a37deef915) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [4939e609de](https://linux-hardware.org/?probe=4939e609de) | Apr 24, 2023 |
| HP            | 090Ch                       | [01d609bbab](https://linux-hardware.org/?probe=01d609bbab) | Apr 23, 2023 |
| ASRock        | Z690 Pro RS                 | [acb9cde3d7](https://linux-hardware.org/?probe=acb9cde3d7) | Apr 23, 2023 |
| Gateway       | DX4860                      | [5583641f1b](https://linux-hardware.org/?probe=5583641f1b) | Apr 22, 2023 |
| ASUSTek       | GRYPHON Z87                 | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| HP            | 3646h                       | [c36653d824](https://linux-hardware.org/?probe=c36653d824) | Apr 12, 2023 |
| HP            | 18E5                        | [441d2678ff](https://linux-hardware.org/?probe=441d2678ff) | Apr 07, 2023 |
| ASUSTek       | P8P67 LE                    | [aea33c89a1](https://linux-hardware.org/?probe=aea33c89a1) | Apr 05, 2023 |
| ASUSTek       | Z97-P                       | [86d8d7f80f](https://linux-hardware.org/?probe=86d8d7f80f) | Apr 05, 2023 |
| HP            | 3029h                       | [153b913406](https://linux-hardware.org/?probe=153b913406) | Mar 27, 2023 |
| Unknown       | GB01                        | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| MSI           | B360M PRO-VH                | [2706ed39b7](https://linux-hardware.org/?probe=2706ed39b7) | Mar 23, 2023 |
| HP            | 3048h                       | [cd326ce9fa](https://linux-hardware.org/?probe=cd326ce9fa) | Mar 22, 2023 |
| ASRock        | AB350 Pro4                  | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| Shenzhen M... | F6BFC                       | [46cb84be25](https://linux-hardware.org/?probe=46cb84be25) | Mar 14, 2023 |
| MSI           | CSM-H87M-G43                | [9df13e200e](https://linux-hardware.org/?probe=9df13e200e) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| HP            | 8184 X4                     | [b42f6862c7](https://linux-hardware.org/?probe=b42f6862c7) | Mar 04, 2023 |
| Unknown       | 1.0                         | [bab30a1ac1](https://linux-hardware.org/?probe=bab30a1ac1) | Feb 24, 2023 |
| Positivo      | POS-PQ45AU POSITIVO         | [8ed6dacaa7](https://linux-hardware.org/?probe=8ed6dacaa7) | Feb 23, 2023 |
| Dell          | 0D441T A03                  | [351a527308](https://linux-hardware.org/?probe=351a527308) | Feb 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [482c922bbc](https://linux-hardware.org/?probe=482c922bbc) | Feb 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [13492935fd](https://linux-hardware.org/?probe=13492935fd) | Feb 09, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [11f3874a6f](https://linux-hardware.org/?probe=11f3874a6f) | Feb 07, 2023 |
| ASUSTek       | Z97M-PLUS                   | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| SLIMBOOK      | ONE-AMD-M4                  | [dc948f9e70](https://linux-hardware.org/?probe=dc948f9e70) | Feb 05, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [42e242e6bf](https://linux-hardware.org/?probe=42e242e6bf) | Feb 04, 2023 |
| Unknown       | Unknown                     | [793f52c99a](https://linux-hardware.org/?probe=793f52c99a) | Feb 03, 2023 |
| ECS           | P4M800PRO-M                 | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| Intel         | D34010WYK H14771-303        | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [dd017ac78a](https://linux-hardware.org/?probe=dd017ac78a) | Jan 31, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [a32a9ba13a](https://linux-hardware.org/?probe=a32a9ba13a) | Jan 30, 2023 |
| Gigabyte      | GA-MA770-UD3                | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| BESSTAR Te... | UM340                       | [77efbbb270](https://linux-hardware.org/?probe=77efbbb270) | Jan 27, 2023 |
| MSI           | Z390-A PRO                  | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Gigabyte      | Z77X-D3H                    | [e81c0bcfc4](https://linux-hardware.org/?probe=e81c0bcfc4) | Jan 22, 2023 |
| Dell          | 0PC5F7 A02                  | [7671c99c3c](https://linux-hardware.org/?probe=7671c99c3c) | Jan 19, 2023 |
| HP            | 3396                        | [2085b91098](https://linux-hardware.org/?probe=2085b91098) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| ASRock        | X370 Taichi                 | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| ASUSTek       | H81M-E                      | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Dell          | 0D881F A06                  | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| ZOTAC         | Unknown                     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | Z390-A PRO                  | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | 0HY9JP A02                  | [c195f58592](https://linux-hardware.org/?probe=c195f58592) | Dec 24, 2022 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | [70e125f0d0](https://linux-hardware.org/?probe=70e125f0d0) | Dec 23, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | [6487bbd7b7](https://linux-hardware.org/?probe=6487bbd7b7) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| HP            | 304Ah                       | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| ASRock        | B365M Pro4                  | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| ASRock        | H81M-HG4 R4.0               | [732e924bbb](https://linux-hardware.org/?probe=732e924bbb) | Nov 07, 2022 |
| ASRock        | B365M Pro4                  | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| MSI           | X570-A PRO                  | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Biostar       | H61MH                       | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| Lenovo        | 318E NOK                    | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| ASRock        | H370M-ITX/ac                | [fa925dcefb](https://linux-hardware.org/?probe=fa925dcefb) | Oct 24, 2022 |
| Pegatron      | NARRA3                      | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [bb43eb5333](https://linux-hardware.org/?probe=bb43eb5333) | Oct 04, 2022 |
| ASUSTek       | Z170-P                      | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| ASUSTek       | P5G41T-M LX                 | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| HP            | 1632                        | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Medion        | H110H4-EM                   | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| ASRock        | H370M-ITX/ac                | [1a577be107](https://linux-hardware.org/?probe=1a577be107) | Sep 04, 2022 |
| Gigabyte      | B560M DS3H V2               | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Biostar       | A780L3B                     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| Intel         | DH55TC AAE70932-303         | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| MP            | MS-7848                     | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| AOpen         | D1009 A1A4                  | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell          | 0DR845                      | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| MSI           | B350 TOMAHAWK               | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Gigabyte      | H410M S2H V3                | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| ASUSTek       | SABERTOOTH X99              | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Intel         | V1.3                        | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| ASUSTek       | SABERTOOTH X99              | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| ASUSTek       | M4A785-M                    | [03878be4ec](https://linux-hardware.org/?probe=03878be4ec) | Apr 20, 2022 |
| Gigabyte      | B550M S2H                   | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Dell          | 0YXT71 A01                  | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Gigabyte      | P35-DS3P                    | [9c4373296f](https://linux-hardware.org/?probe=9c4373296f) | Mar 21, 2022 |
| Lenovo        | 1046 NO DPK                 | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| HP            | 3647h                       | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| ASUSTek       | PRIME H510M-A               | [4521c22268](https://linux-hardware.org/?probe=4521c22268) | Mar 06, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| MSI           | Z97 GAMING 5                | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| ASRock        | FM2A68M-HD+ R2.0            | [d0ba3786b2](https://linux-hardware.org/?probe=d0ba3786b2) | Feb 03, 2022 |
| Intel         | H81                         | [c1763fe2cf](https://linux-hardware.org/?probe=c1763fe2cf) | Jan 29, 2022 |
| ASUSTek       | X99-DELUXE                  | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| IBM           | 8183B2U                     | [d070680dfb](https://linux-hardware.org/?probe=d070680dfb) | Jan 14, 2022 |
| HP            | 0B4Ch D                     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| Gigabyte      | F2A88X-UP4                  | [52e09bab91](https://linux-hardware.org/?probe=52e09bab91) | Jan 02, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| GALAX         | B550M                       | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| ECS           | A55F-M3                     | [5439a8e37c](https://linux-hardware.org/?probe=5439a8e37c) | Nov 27, 2021 |
| Lenovo        | SHARKBAY NO DPK             | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| ASRock        | X570 Steel Legend           | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| MSI           | B460M PRO                   | [ae3e01fef8](https://linux-hardware.org/?probe=ae3e01fef8) | Oct 31, 2021 |
| ECS           | A55F-M3                     | [27e84aca95](https://linux-hardware.org/?probe=27e84aca95) | Oct 31, 2021 |
| Gigabyte      | X570 AORUS PRO              | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | Maximus VII HERO            | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| Gigabyte      | B550M DS3H                  | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Dell          | 00F82W A01                  | [08e803937e](https://linux-hardware.org/?probe=08e803937e) | Oct 18, 2021 |
| Dell          | 0P611C A00                  | [c11bd1c981](https://linux-hardware.org/?probe=c11bd1c981) | Oct 11, 2021 |
| HP            | 21D0                        | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| GreatWall     | U320                        | [483d23be23](https://linux-hardware.org/?probe=483d23be23) | Oct 06, 2021 |
| GreatWall     | U320                        | [043d1121f4](https://linux-hardware.org/?probe=043d1121f4) | Oct 06, 2021 |
| Dell          | 0M017G A00                  | [3549222788](https://linux-hardware.org/?probe=3549222788) | Oct 02, 2021 |
| Intel         | Unknown                     | [e97eb92439](https://linux-hardware.org/?probe=e97eb92439) | Oct 01, 2021 |
| ASRock        | H470M-ITX/ac                | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| Dell          | 0M017G A00                  | [2bf98ef81c](https://linux-hardware.org/?probe=2bf98ef81c) | Sep 24, 2021 |
| Dell          | 0P611C A00                  | [eadaa5e6cb](https://linux-hardware.org/?probe=eadaa5e6cb) | Aug 20, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| ASUSTek       | X79-DELUXE                  | [bc56fe50dd](https://linux-hardware.org/?probe=bc56fe50dd) | Jul 24, 2021 |
| ASRock        | H170M Pro4                  | [f291edbc4a](https://linux-hardware.org/?probe=f291edbc4a) | Jul 18, 2021 |
| Gigabyte      | H110M-S2H-CF                | [192043ebbd](https://linux-hardware.org/?probe=192043ebbd) | Jul 12, 2021 |
| Dell          | 00F82W A01                  | [b85b636b73](https://linux-hardware.org/?probe=b85b636b73) | Jun 26, 2021 |
| Intel         | DZ77SL-50K AAG55115-300     | [bae9a4e960](https://linux-hardware.org/?probe=bae9a4e960) | May 16, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| MSI           | B450-A PRO MAX              | [506efba999](https://linux-hardware.org/?probe=506efba999) | May 02, 2021 |
| ASRock        | B560M Pro4                  | [d4484f50cd](https://linux-hardware.org/?probe=d4484f50cd) | Apr 08, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [4959cfd244](https://linux-hardware.org/?probe=4959cfd244) | Apr 07, 2021 |
| ASUSTek       | P5K-E                       | [f0c435ead1](https://linux-hardware.org/?probe=f0c435ead1) | Apr 01, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [8d8771e1ef](https://linux-hardware.org/?probe=8d8771e1ef) | Mar 30, 2021 |
| Dell          | 0XR1GT A00                  | [04145c0b36](https://linux-hardware.org/?probe=04145c0b36) | Mar 29, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| MSI           | B350 TOMAHAWK               | [d77d6984e4](https://linux-hardware.org/?probe=d77d6984e4) | Mar 19, 2021 |
| MSI           | MS-7210 100                 | [e8723eb58b](https://linux-hardware.org/?probe=e8723eb58b) | Mar 17, 2021 |
| ASRock        | H81M-ITX                    | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASUSTek       | A8R-MVP                     | [ce881d4659](https://linux-hardware.org/?probe=ce881d4659) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [4789c5df48](https://linux-hardware.org/?probe=4789c5df48) | Feb 06, 2021 |
| ASRock        | K8A780LM                    | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | [62ab746796](https://linux-hardware.org/?probe=62ab746796) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | [00e4deffa2](https://linux-hardware.org/?probe=00e4deffa2) | Jan 14, 2021 |
| Intel         | MAHOBAY                     | [d3e3aa3011](https://linux-hardware.org/?probe=d3e3aa3011) | Nov 28, 2020 |
| Intel         | MAHOBAY                     | [b51d9808ea](https://linux-hardware.org/?probe=b51d9808ea) | Nov 28, 2020 |
| ASUSTek       | M5A97 R2.0                  | [6a65eeffd1](https://linux-hardware.org/?probe=6a65eeffd1) | Nov 27, 2020 |
| HP            | 1905                        | [03a91e7ecc](https://linux-hardware.org/?probe=03a91e7ecc) | Nov 27, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b7fec4788f](https://linux-hardware.org/?probe=b7fec4788f) | Nov 25, 2020 |
| ASUSTek       | PRIME B450M-A               | [d4f8648d28](https://linux-hardware.org/?probe=d4f8648d28) | Nov 24, 2020 |
| Intel         | MAHOBAY                     | [282590eccb](https://linux-hardware.org/?probe=282590eccb) | Nov 24, 2020 |
| ASRock        | H110M-ITX                   | [e3ca7996d2](https://linux-hardware.org/?probe=e3ca7996d2) | Nov 13, 2020 |
| ASUSTek       | PRIME B450M-A               | [a7bb20fa67](https://linux-hardware.org/?probe=a7bb20fa67) | Nov 08, 2020 |
| MSI           | Z87 MPOWER MAX              | [c4f4df2ec5](https://linux-hardware.org/?probe=c4f4df2ec5) | Oct 31, 2020 |
| Dell          | 0D28YY A00                  | [584335af3e](https://linux-hardware.org/?probe=584335af3e) | Oct 29, 2020 |
| Dell          | 0M9KCM A02                  | [3e66c830f8](https://linux-hardware.org/?probe=3e66c830f8) | Sep 22, 2020 |
| Gigabyte      | B450M DS3H-CF               | [a2151aadf5](https://linux-hardware.org/?probe=a2151aadf5) | Sep 14, 2020 |
| HP            | 8265                        | [38f924e8f9](https://linux-hardware.org/?probe=38f924e8f9) | Sep 07, 2020 |
| Dell          | 0M5DCD A00                  | [f138fd7e0c](https://linux-hardware.org/?probe=f138fd7e0c) | Aug 09, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [2f71e9b242](https://linux-hardware.org/?probe=2f71e9b242) | Aug 03, 2020 |
| HP            | 3031h                       | [205dd10b09](https://linux-hardware.org/?probe=205dd10b09) | Jul 29, 2020 |
| HP            | 3031h                       | [22ebc88fac](https://linux-hardware.org/?probe=22ebc88fac) | Jul 29, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [2233b1466b](https://linux-hardware.org/?probe=2233b1466b) | Jul 06, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [c70f8ee92e](https://linux-hardware.org/?probe=c70f8ee92e) | Jul 06, 2020 |
| MSI           | 970A-G43                    | [ada20a047e](https://linux-hardware.org/?probe=ada20a047e) | May 27, 2020 |
| Gigabyte      | P55-USB3                    | [901dfafdbf](https://linux-hardware.org/?probe=901dfafdbf) | May 21, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [a7d4e8b1e4](https://linux-hardware.org/?probe=a7d4e8b1e4) | Apr 10, 2020 |
| Intel         | DCP847SKE G80890-105        | [0357ef50d4](https://linux-hardware.org/?probe=0357ef50d4) | Apr 05, 2020 |
| ASUSTek       | P8Z77-V LX                  | [893f6857b2](https://linux-hardware.org/?probe=893f6857b2) | Apr 04, 2020 |
| ASUSTek       | Z97-E                       | [42c2810369](https://linux-hardware.org/?probe=42c2810369) | Apr 03, 2020 |
| ASUSTek       | P8Z77-V LX                  | [ec1375a9f8](https://linux-hardware.org/?probe=ec1375a9f8) | Apr 02, 2020 |
| MSI           | 760GM-P23                   | [67de432cb4](https://linux-hardware.org/?probe=67de432cb4) | Apr 01, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [67d9f2023b](https://linux-hardware.org/?probe=67d9f2023b) | Apr 01, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | [104b035076](https://linux-hardware.org/?probe=104b035076) | Apr 01, 2020 |
| Gigabyte      | A320M-DS2-CF                | [27d1900fba](https://linux-hardware.org/?probe=27d1900fba) | Mar 28, 2020 |
| Gigabyte      | Z68AP-D3                    | [617031b37d](https://linux-hardware.org/?probe=617031b37d) | Mar 28, 2020 |
| ASRock        | Z68 Pro3-M                  | [73690787f9](https://linux-hardware.org/?probe=73690787f9) | Mar 26, 2020 |
| Dell          | 0F373D A00                  | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1243c4a0d9](https://linux-hardware.org/?probe=1243c4a0d9) | Mar 24, 2020 |
| HP            | 1790                        | [68a167efd3](https://linux-hardware.org/?probe=68a167efd3) | Mar 24, 2020 |
| ASUSTek       | M4A77T                      | [75d0b42f08](https://linux-hardware.org/?probe=75d0b42f08) | Mar 01, 2020 |
| ASUSTek       | PRIME H310M-K               | [ed464b4172](https://linux-hardware.org/?probe=ed464b4172) | Jan 23, 2020 |
| ASRock        | K8A780LM                    | [e0d3030787](https://linux-hardware.org/?probe=e0d3030787) | Jan 18, 2020 |
| ASRock        | K8A780LM                    | [83dca94e72](https://linux-hardware.org/?probe=83dca94e72) | Jan 17, 2020 |
| ASRock        | K8A780LM                    | [a5e0479887](https://linux-hardware.org/?probe=a5e0479887) | Jan 16, 2020 |
| Gigabyte      | GA-880GA-UD3H               | [03401edcb4](https://linux-hardware.org/?probe=03401edcb4) | Jan 13, 2020 |
| ASRock        | X370 Gaming X               | [8a0171b4b0](https://linux-hardware.org/?probe=8a0171b4b0) | Jan 13, 2020 |
| Gateway       | SX2185                      | [74f9db3262](https://linux-hardware.org/?probe=74f9db3262) | Jan 13, 2020 |
| Dell          | 088DT1 A01                  | [3c957a3758](https://linux-hardware.org/?probe=3c957a3758) | Dec 23, 2019 |
| MSI           | MS-7199                     | [8fe7e9e6a6](https://linux-hardware.org/?probe=8fe7e9e6a6) | Dec 21, 2019 |
| MSI           | B75MA-E33                   | [a08cc9782c](https://linux-hardware.org/?probe=a08cc9782c) | Nov 17, 2019 |
| Gigabyte      | P43-ES3G                    | [96fa353482](https://linux-hardware.org/?probe=96fa353482) | Nov 07, 2019 |
| ASRock        | H81M-ITX                    | [431ea0cbed](https://linux-hardware.org/?probe=431ea0cbed) | Oct 25, 2019 |
| Dell          | 0F8096                      | [d1f6910c12](https://linux-hardware.org/?probe=d1f6910c12) | Oct 20, 2019 |
| ASUSTek       | M2N-MX SE Plus              | [f4fcd6e28c](https://linux-hardware.org/?probe=f4fcd6e28c) | Oct 20, 2019 |
| ASRock        | H81M-ITX                    | [c5f47f2f27](https://linux-hardware.org/?probe=c5f47f2f27) | Oct 20, 2019 |
| ASUSTek       | SABERTOOTH X79              | [13dbc6f66d](https://linux-hardware.org/?probe=13dbc6f66d) | Oct 06, 2019 |
| ASUSTek       | Z97-A                       | [6a9aa2dd84](https://linux-hardware.org/?probe=6a9aa2dd84) | Jul 22, 2019 |
| Gigabyte      | EP45-UD3LR                  | [e42fd626b2](https://linux-hardware.org/?probe=e42fd626b2) | Apr 23, 2019 |
| Gigabyte      | EP45-UD3LR                  | [8469904453](https://linux-hardware.org/?probe=8469904453) | Apr 17, 2019 |
| Gigabyte      | Z370 AORUS Gaming 7         | [c68bd6bce7](https://linux-hardware.org/?probe=c68bd6bce7) | Feb 23, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| MX 21          | 118      | 50.86%  |
| MX 19          | 46       | 19.83%  |
| MX 23          | 31       | 13.36%  |
| MX 20          | 22       | 9.48%   |
| MX 18          | 12       | 5.17%   |
| MX 22          | 1        | 0.43%   |
| MX 17          | 1        | 0.43%   |
| MX 16-migrated | 1        | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MX   | 227      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 4.19.0-6-amd64            | 20       | 8.1%    |
| 5.10.0-21-amd64           | 15       | 6.07%   |
| 5.10.0-20-amd64           | 13       | 5.26%   |
| 6.0.0-6mx-amd64           | 10       | 4.05%   |
| 6.1.0-13-amd64            | 8        | 3.24%   |
| 5.14.0-4mx-amd64          | 7        | 2.83%   |
| 5.10.0-23-amd64           | 7        | 2.83%   |
| 6.1.0-10-amd64            | 6        | 2.43%   |
| 5.6.0-2-amd64             | 6        | 2.43%   |
| 5.10.0-5mx-amd64          | 6        | 2.43%   |
| 5.10.0-19-amd64           | 6        | 2.43%   |
| 5.10.0-18-amd64           | 6        | 2.43%   |
| 5.18.0-4mx-amd64          | 5        | 2.02%   |
| 5.10.0-13-amd64           | 5        | 2.02%   |
| 4.19.0-17-amd64           | 5        | 2.02%   |
| 6.5.0-1mx-ahs-amd64       | 4        | 1.62%   |
| 6.1.0-11-amd64            | 4        | 1.62%   |
| 6.0.0-10.1-liquorix-amd64 | 4        | 1.62%   |
| 5.8.0-3-amd64             | 4        | 1.62%   |
| 5.10.0-16-amd64           | 4        | 1.62%   |
| 5.10.0-15-amd64           | 4        | 1.62%   |
| 4.19.0-14-amd64           | 4        | 1.62%   |
| 6.4.0-1mx-ahs-amd64       | 3        | 1.21%   |
| 5.4.0-3-amd64             | 3        | 1.21%   |
| 5.16.0-5mx-amd64          | 3        | 1.21%   |
| 4.19.0-5-amd64            | 3        | 1.21%   |
| 4.19.0-18-amd64           | 3        | 1.21%   |
| 4.19.0-13-amd64           | 3        | 1.21%   |
| 4.19.0-1-amd64            | 3        | 1.21%   |
| 5.8.16-antix.1-amd64-smp  | 2        | 0.81%   |
| 5.14.0-3mx-amd64          | 2        | 0.81%   |
| 5.10.0-9-amd64            | 2        | 0.81%   |
| 5.10.0-11-amd64           | 2        | 0.81%   |
| 4.19.0-16-amd64           | 2        | 0.81%   |
| 4.19.0-12-amd64           | 2        | 0.81%   |
| 6.5.5-2-liquorix-amd64    | 1        | 0.4%    |
| 6.5.11-1-liquorix-amd64   | 1        | 0.4%    |
| 6.5.0-2-amd64             | 1        | 0.4%    |
| 6.4.14-1-liquorix-amd64   | 1        | 0.4%    |
| 6.4.0-3mx-ahs-amd64       | 1        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 80       | 33.76%  |
| 4.19.0   | 45       | 18.99%  |
| 6.1.0    | 20       | 8.44%   |
| 6.0.0    | 16       | 6.75%   |
| 5.14.0   | 10       | 4.22%   |
| 5.6.0    | 6        | 2.53%   |
| 6.5.0    | 5        | 2.11%   |
| 5.5.0    | 5        | 2.11%   |
| 5.18.0   | 5        | 2.11%   |
| 5.16.0   | 5        | 2.11%   |
| 6.4.0    | 4        | 1.69%   |
| 5.8.0    | 4        | 1.69%   |
| 5.19.0   | 4        | 1.69%   |
| 5.4.0    | 3        | 1.27%   |
| 5.15.0   | 3        | 1.27%   |
| 5.8.16   | 2        | 0.84%   |
| 5.3.0    | 2        | 0.84%   |
| 6.5.5    | 1        | 0.42%   |
| 6.5.11   | 1        | 0.42%   |
| 6.4.14   | 1        | 0.42%   |
| 6.3.9    | 1        | 0.42%   |
| 6.2.14   | 1        | 0.42%   |
| 6.1.15   | 1        | 0.42%   |
| 6.0.5    | 1        | 0.42%   |
| 5.4.7    | 1        | 0.42%   |
| 5.4.10   | 1        | 0.42%   |
| 5.2.21   | 1        | 0.42%   |
| 5.17.0   | 1        | 0.42%   |
| 5.11.0   | 1        | 0.42%   |
| 5.10.52  | 1        | 0.42%   |
| 5.10.113 | 1        | 0.42%   |
| 5.10.111 | 1        | 0.42%   |
| 4.9.91   | 1        | 0.42%   |
| 4.18.0   | 1        | 0.42%   |
| 4.15.0   | 1        | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 83       | 35.02%  |
| 4.19    | 45       | 18.99%  |
| 6.1     | 21       | 8.86%   |
| 6.0     | 17       | 7.17%   |
| 5.14    | 10       | 4.22%   |
| 6.5     | 7        | 2.95%   |
| 5.8     | 6        | 2.53%   |
| 5.6     | 6        | 2.53%   |
| 6.4     | 5        | 2.11%   |
| 5.5     | 5        | 2.11%   |
| 5.4     | 5        | 2.11%   |
| 5.18    | 5        | 2.11%   |
| 5.16    | 5        | 2.11%   |
| 5.19    | 4        | 1.69%   |
| 5.15    | 3        | 1.27%   |
| 5.3     | 2        | 0.84%   |
| 6.3     | 1        | 0.42%   |
| 6.2     | 1        | 0.42%   |
| 5.2     | 1        | 0.42%   |
| 5.17    | 1        | 0.42%   |
| 5.11    | 1        | 0.42%   |
| 4.9     | 1        | 0.42%   |
| 4.18    | 1        | 0.42%   |
| 4.15    | 1        | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 219      | 96.48%  |
| i686   | 8        | 3.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 175      | 76.75%  |
| KDE5             | 42       | 18.42%  |
| MATE             | 3        | 1.32%   |
| lightdm-xsession | 3        | 1.32%   |
| X-Cinnamon       | 1        | 0.44%   |
| LXQt             | 1        | 0.44%   |
| KDE4             | 1        | 0.44%   |
| KDE              | 1        | 0.44%   |
| Unknown          | 1        | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 226      | 99.56%  |
| Tty  | 1        | 0.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 184      | 80.7%   |
| SDDM    | 38       | 16.67%  |
| SLiM    | 3        | 1.32%   |
| TDM     | 2        | 0.88%   |
| GDM     | 1        | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 85       | 36.64%  |
| Unknown | 34       | 14.66%  |
| de_DE   | 21       | 9.05%   |
| en_GB   | 12       | 5.17%   |
| ru_RU   | 9        | 3.88%   |
| it_IT   | 9        | 3.88%   |
| es_ES   | 8        | 3.45%   |
| pl_PL   | 7        | 3.02%   |
| sk_SK   | 6        | 2.59%   |
| pt_BR   | 5        | 2.16%   |
| fr_FR   | 5        | 2.16%   |
| es_AR   | 5        | 2.16%   |
| en_AU   | 4        | 1.72%   |
| es_MX   | 3        | 1.29%   |
| de_CH   | 3        | 1.29%   |
| sv_SE   | 2        | 0.86%   |
| hu_HU   | 2        | 0.86%   |
| hr_HR   | 2        | 0.86%   |
| en_IE   | 2        | 0.86%   |
| uk_UA   | 1        | 0.43%   |
| tr_TR   | 1        | 0.43%   |
| fi_FI   | 1        | 0.43%   |
| es_VE   | 1        | 0.43%   |
| es_CO   | 1        | 0.43%   |
| en_NZ   | 1        | 0.43%   |
| en_CA   | 1        | 0.43%   |
| de_AT   | 1        | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 135      | 58.95%  |
| EFI  | 94       | 41.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 205      | 90.31%  |
| Overlay  | 12       | 5.29%   |
| Btrfs    | 5        | 2.2%    |
| Tmpfs    | 2        | 0.88%   |
| Xfs      | 1        | 0.44%   |
| Reiserfs | 1        | 0.44%   |
| Ext3     | 1        | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 130      | 56.52%  |
| MBR     | 98       | 42.61%  |
| Unknown | 2        | 0.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 154      | 65.53%  |
| Yes       | 81       | 34.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 127      | 55.95%  |
| No        | 100      | 44.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 49       | 21.59%  |
| Gigabyte Technology                  | 36       | 15.86%  |
| MSI                                  | 26       | 11.45%  |
| ASRock                               | 24       | 10.57%  |
| Dell                                 | 23       | 10.13%  |
| Hewlett-Packard                      | 17       | 7.49%   |
| Intel                                | 9        | 3.96%   |
| Lenovo                               | 7        | 3.08%   |
| Unknown                              | 4        | 1.76%   |
| Foxconn                              | 3        | 1.32%   |
| Biostar                              | 3        | 1.32%   |
| Pegatron                             | 2        | 0.88%   |
| Medion                               | 2        | 0.88%   |
| Gateway                              | 2        | 0.88%   |
| Fujitsu                              | 2        | 0.88%   |
| ECS                                  | 2        | 0.88%   |
| ZOTAC                                | 1        | 0.44%   |
| SLIMBOOK                             | 1        | 0.44%   |
| SIRAGON                              | 1        | 0.44%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.44%   |
| Positivo                             | 1        | 0.44%   |
| OEM                                  | 1        | 0.44%   |
| MP                                   | 1        | 0.44%   |
| IBM                                  | 1        | 0.44%   |
| Huanan                               | 1        | 0.44%   |
| GreatWall                            | 1        | 0.44%   |
| GALAX                                | 1        | 0.44%   |
| Fujitsu Siemens                      | 1        | 0.44%   |
| BESSTAR Tech                         | 1        | 0.44%   |
| AZW                                  | 1        | 0.44%   |
| AOpen                                | 1        | 0.44%   |
| Acer                                 | 1        | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 9        | 3.96%   |
| Unknown                                    | 6        | 2.64%   |
| MSI MS-7C91                                | 2        | 0.88%   |
| MSI MS-7A34                                | 2        | 0.88%   |
| Intel H81                                  | 2        | 0.88%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 0.88%   |
| Foxconn Pro3500 Series                     | 2        | 0.88%   |
| Dell Studio 540                            | 2        | 0.88%   |
| Dell OptiPlex 9020                         | 2        | 0.88%   |
| Dell OptiPlex 9010                         | 2        | 0.88%   |
| Dell OptiPlex 790                          | 2        | 0.88%   |
| Dell OptiPlex 780                          | 2        | 0.88%   |
| Dell OptiPlex 755                          | 2        | 0.88%   |
| ASUS ROG Maximus XIII HERO                 | 2        | 0.88%   |
| ASUS PRIME B450M-A                         | 2        | 0.88%   |
| ASRock K8A780LM                            | 2        | 0.88%   |
| SLIMBOOK ONE-AMD-M4                        | 1        | 0.44%   |
| SIRAGON AIO-5150                           | 1        | 0.44%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.44%   |
| Positivo POS-PQ45AU                        | 1        | 0.44%   |
| Pegatron FQ425AA-ABA a6655f                | 1        | 0.44%   |
| Pegatron 2AD5                              | 1        | 0.44%   |
| OEM Intel H81                              | 1        | 0.44%   |
| MSI MS-7E12                                | 1        | 0.44%   |
| MSI MS-7C95                                | 1        | 0.44%   |
| MSI MS-7C94                                | 1        | 0.44%   |
| MSI MS-7C88                                | 1        | 0.44%   |
| MSI MS-7C56                                | 1        | 0.44%   |
| MSI MS-7C37                                | 1        | 0.44%   |
| MSI MS-7B98                                | 1        | 0.44%   |
| MSI MS-7B86                                | 1        | 0.44%   |
| MSI MS-7B53                                | 1        | 0.44%   |
| MSI MS-7A63                                | 1        | 0.44%   |
| MSI MS-7917                                | 1        | 0.44%   |
| MSI MS-7895                                | 1        | 0.44%   |
| MSI MS-7823                                | 1        | 0.44%   |
| MSI MS-7815                                | 1        | 0.44%   |
| MSI MS-7808                                | 1        | 0.44%   |
| MSI MS-7758                                | 1        | 0.44%   |
| MSI MS-7721                                | 1        | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 15       | 6.61%   |
| ASUS PRIME                                 | 9        | 3.96%   |
| ASUS All                                   | 9        | 3.96%   |
| HP Compaq                                  | 6        | 2.64%   |
| Unknown                                    | 6        | 2.64%   |
| ASUS ROG                                   | 5        | 2.2%    |
| ASUS TUF                                   | 4        | 1.76%   |
| Dell Inspiron                              | 3        | 1.32%   |
| MSI MS-7C91                                | 2        | 0.88%   |
| MSI MS-7A34                                | 2        | 0.88%   |
| Lenovo ThinkCentre                         | 2        | 0.88%   |
| Lenovo IdeaCentre                          | 2        | 0.88%   |
| Intel H81                                  | 2        | 0.88%   |
| HP EliteDesk                               | 2        | 0.88%   |
| Gigabyte Z390                              | 2        | 0.88%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 0.88%   |
| Gigabyte B550M                             | 2        | 0.88%   |
| Foxconn Pro3500                            | 2        | 0.88%   |
| Dell Studio                                | 2        | 0.88%   |
| Dell Precision                             | 2        | 0.88%   |
| ASUS P5GC-MX                               | 2        | 0.88%   |
| ASRock X370                                | 2        | 0.88%   |
| ASRock K8A780LM                            | 2        | 0.88%   |
| SLIMBOOK ONE-AMD-M4                        | 1        | 0.44%   |
| SIRAGON AIO-5150                           | 1        | 0.44%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.44%   |
| Positivo POS-PQ45AU                        | 1        | 0.44%   |
| Pegatron FQ425AA-ABA                       | 1        | 0.44%   |
| Pegatron 2AD5                              | 1        | 0.44%   |
| OEM Intel                                  | 1        | 0.44%   |
| MSI MS-7E12                                | 1        | 0.44%   |
| MSI MS-7C95                                | 1        | 0.44%   |
| MSI MS-7C94                                | 1        | 0.44%   |
| MSI MS-7C88                                | 1        | 0.44%   |
| MSI MS-7C56                                | 1        | 0.44%   |
| MSI MS-7C37                                | 1        | 0.44%   |
| MSI MS-7B98                                | 1        | 0.44%   |
| MSI MS-7B86                                | 1        | 0.44%   |
| MSI MS-7B53                                | 1        | 0.44%   |
| MSI MS-7A63                                | 1        | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 21       | 9.25%   |
| 2018 | 17       | 7.49%   |
| 2012 | 17       | 7.49%   |
| 2011 | 17       | 7.49%   |
| 2021 | 16       | 7.05%   |
| 2020 | 15       | 6.61%   |
| 2019 | 14       | 6.17%   |
| 2010 | 14       | 6.17%   |
| 2022 | 13       | 5.73%   |
| 2014 | 13       | 5.73%   |
| 2009 | 13       | 5.73%   |
| 2016 | 11       | 4.85%   |
| 2017 | 10       | 4.41%   |
| 2015 | 9        | 3.96%   |
| 2008 | 9        | 3.96%   |
| 2007 | 8        | 3.52%   |
| 2006 | 4        | 1.76%   |
| 2023 | 3        | 1.32%   |
| 2005 | 2        | 0.88%   |
| 2004 | 1        | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 227      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 227      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 227      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 57       | 25%     |
| 8.01-16.0   | 54       | 23.68%  |
| 4.01-8.0    | 38       | 16.67%  |
| 32.01-64.0  | 30       | 13.16%  |
| 3.01-4.0    | 25       | 10.96%  |
| 24.01-32.0  | 8        | 3.51%   |
| 1.01-2.0    | 7        | 3.07%   |
| 64.01-256.0 | 4        | 1.75%   |
| 0.51-1.0    | 3        | 1.32%   |
| 2.01-3.0    | 2        | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 80       | 33.61%  |
| 2.01-3.0   | 66       | 27.73%  |
| 4.01-8.0   | 33       | 13.87%  |
| 3.01-4.0   | 33       | 13.87%  |
| 0.51-1.0   | 16       | 6.72%   |
| 8.01-16.0  | 7        | 2.94%   |
| 0.01-0.5   | 2        | 0.84%   |
| 16.01-24.0 | 1        | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 81       | 34.47%  |
| 2      | 72       | 30.64%  |
| 3      | 44       | 18.72%  |
| 4      | 19       | 8.09%   |
| 5      | 12       | 5.11%   |
| 8      | 3        | 1.28%   |
| 9      | 1        | 0.43%   |
| 7      | 1        | 0.43%   |
| 6      | 1        | 0.43%   |
| 0      | 1        | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 117      | 51.09%  |
| No        | 112      | 48.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 226      | 99.56%  |
| No        | 1        | 0.44%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 51.98%  |
| Yes       | 109      | 48.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 164      | 72.25%  |
| Yes       | 63       | 27.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 54       | 23.68%  |
| Germany                | 19       | 8.33%   |
| Russia                 | 12       | 5.26%   |
| Italy                  | 11       | 4.82%   |
| UK                     | 10       | 4.39%   |
| Spain                  | 10       | 4.39%   |
| Poland                 | 9        | 3.95%   |
| Slovakia               | 8        | 3.51%   |
| France                 | 8        | 3.51%   |
| Australia              | 8        | 3.51%   |
| India                  | 7        | 3.07%   |
| Canada                 | 7        | 3.07%   |
| Sweden                 | 6        | 2.63%   |
| Brazil                 | 6        | 2.63%   |
| Finland                | 5        | 2.19%   |
| Argentina              | 5        | 2.19%   |
| Switzerland            | 3        | 1.32%   |
| Serbia                 | 3        | 1.32%   |
| Mexico                 | 3        | 1.32%   |
| Indonesia              | 3        | 1.32%   |
| Venezuela              | 2        | 0.88%   |
| Singapore              | 2        | 0.88%   |
| Netherlands            | 2        | 0.88%   |
| Ireland                | 2        | 0.88%   |
| Hungary                | 2        | 0.88%   |
| Denmark                | 2        | 0.88%   |
| Bosnia and Herzegovina | 2        | 0.88%   |
| Belgium                | 2        | 0.88%   |
| Austria                | 2        | 0.88%   |
| Ukraine                | 1        | 0.44%   |
| Turkey                 | 1        | 0.44%   |
| South Africa           | 1        | 0.44%   |
| Romania                | 1        | 0.44%   |
| Philippines            | 1        | 0.44%   |
| New Zealand            | 1        | 0.44%   |
| Greece                 | 1        | 0.44%   |
| French Guiana          | 1        | 0.44%   |
| Estonia                | 1        | 0.44%   |
| Croatia                | 1        | 0.44%   |
| Colombia               | 1        | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bratislava               | 7        | 3%      |
| Sydney                   | 4        | 1.72%   |
| Moscow                   | 4        | 1.72%   |
| Melbourne                | 3        | 1.29%   |
| Florianópolis           | 3        | 1.29%   |
| Berlin                   | 3        | 1.29%   |
| Bengaluru                | 3        | 1.29%   |
| Barcelona                | 3        | 1.29%   |
| Vienna                   | 2        | 0.86%   |
| Toronto                  | 2        | 0.86%   |
| St Petersburg            | 2        | 0.86%   |
| Singapore                | 2        | 0.86%   |
| Mesquite                 | 2        | 0.86%   |
| Krakow                   | 2        | 0.86%   |
| Houston                  | 2        | 0.86%   |
| Ettingen                 | 2        | 0.86%   |
| Espoo                    | 2        | 0.86%   |
| Córdoba                 | 2        | 0.86%   |
| Centreville              | 2        | 0.86%   |
| Cazin                    | 2        | 0.86%   |
| Birmingham               | 2        | 0.86%   |
| Belgrade                 | 2        | 0.86%   |
| Alma                     | 2        | 0.86%   |
| Albertslund Municipality | 2        | 0.86%   |
| Zagreb                   | 1        | 0.43%   |
| Yuzhno-Sakhalinsk        | 1        | 0.43%   |
| Warsaw                   | 1        | 0.43%   |
| Warren                   | 1        | 0.43%   |
| Wandsworth               | 1        | 0.43%   |
| Volos                    | 1        | 0.43%   |
| Voghera                  | 1        | 0.43%   |
| Virginia Beach           | 1        | 0.43%   |
| Villeurbanne             | 1        | 0.43%   |
| Vilhelmina               | 1        | 0.43%   |
| Vera                     | 1        | 0.43%   |
| Vasco da Gama            | 1        | 0.43%   |
| Valencia                 | 1        | 0.43%   |
| Vaidasoo                 | 1        | 0.43%   |
| Tuglie                   | 1        | 0.43%   |
| Tomsk                    | 1        | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 80       | 108    | 18.26%  |
| Seagate                     | 76       | 110    | 17.35%  |
| Samsung Electronics         | 65       | 108    | 14.84%  |
| Kingston                    | 36       | 38     | 8.22%   |
| Toshiba                     | 22       | 28     | 5.02%   |
| SanDisk                     | 20       | 23     | 4.57%   |
| Hitachi                     | 18       | 25     | 4.11%   |
| Crucial                     | 17       | 19     | 3.88%   |
| China                       | 12       | 17     | 2.74%   |
| A-DATA Technology           | 12       | 13     | 2.74%   |
| Unknown                     | 6        | 8      | 1.37%   |
| Intel                       | 6        | 7      | 1.37%   |
| PNY                         | 5        | 7      | 1.14%   |
| Maxtor                      | 5        | 6      | 1.14%   |
| GOODRAM                     | 5        | 6      | 1.14%   |
| Apacer                      | 5        | 5      | 1.14%   |
| Corsair                     | 4        | 4      | 0.91%   |
| Team                        | 3        | 3      | 0.68%   |
| SPCC                        | 3        | 3      | 0.68%   |
| Silicon Motion              | 3        | 3      | 0.68%   |
| Mushkin                     | 3        | 3      | 0.68%   |
| Transcend                   | 2        | 2      | 0.46%   |
| Micron/Crucial Technology   | 2        | 2      | 0.46%   |
| Lexar                       | 2        | 2      | 0.46%   |
| Gigabyte Technology         | 2        | 2      | 0.46%   |
| XPG                         | 1        | 1      | 0.23%   |
| WDC WDS1                    | 1        | 1      | 0.23%   |
| WALRAM                      | 1        | 1      | 0.23%   |
| Vaseky                      | 1        | 1      | 0.23%   |
| SABRENT                     | 1        | 2      | 0.23%   |
| Rogueware                   | 1        | 2      | 0.23%   |
| Plextor                     | 1        | 1      | 0.23%   |
| Phison Electronics          | 1        | 1      | 0.23%   |
| Phison                      | 1        | 1      | 0.23%   |
| OCZ                         | 1        | 1      | 0.23%   |
| Netac                       | 1        | 2      | 0.23%   |
| Micron Technology           | 1        | 1      | 0.23%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.23%   |
| KingSpec                    | 1        | 1      | 0.23%   |
| KingFast                    | 1        | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 9        | 1.77%   |
| Seagate ST2000DM008-2FR102 2TB   | 7        | 1.38%   |
| Seagate ST4000DM004-2CV104 4TB   | 6        | 1.18%   |
| Samsung SSD 860 EVO 500GB        | 6        | 1.18%   |
| Samsung SSD 850 EVO 250GB        | 6        | 1.18%   |
| Seagate ST1000DM010-2EP102 1TB   | 5        | 0.98%   |
| Samsung SSD 970 EVO Plus 1TB     | 5        | 0.98%   |
| Kingston SV300S37A240G 240GB SSD | 5        | 0.98%   |
| WDC WD10EZEX-00BN5A0 1TB         | 4        | 0.79%   |
| Toshiba DT01ACA100 1TB           | 4        | 0.79%   |
| Seagate ST500DM002-1BD142 500GB  | 4        | 0.79%   |
| Seagate ST3500413AS 500GB        | 4        | 0.79%   |
| Samsung SSD 860 EVO 250GB        | 4        | 0.79%   |
| Samsung SSD 860 EVO 1TB          | 4        | 0.79%   |
| Kingston SA400S37120G 120GB SSD  | 4        | 0.79%   |
| WDC WD10EZEX-60WN4A0 1TB         | 3        | 0.59%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 3        | 0.59%   |
| Seagate ST500LM021-1KJ152 500GB  | 3        | 0.59%   |
| SanDisk SSD PLUS 1000GB          | 3        | 0.59%   |
| SanDisk SDSSDA240G 240GB         | 3        | 0.59%   |
| SanDisk NVMe SSD Drive 1TB       | 3        | 0.59%   |
| Samsung SSD 980 PRO 1TB          | 3        | 0.59%   |
| Samsung SSD 980 500GB            | 3        | 0.59%   |
| Samsung SSD 970 PRO 512GB        | 3        | 0.59%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.59%   |
| Samsung SSD 870 EVO 500GB        | 3        | 0.59%   |
| Samsung SSD 860 QVO 1TB          | 3        | 0.59%   |
| Samsung SSD 850 EVO 500GB        | 3        | 0.59%   |
| Samsung SSD 850 EVO 1TB          | 3        | 0.59%   |
| Samsung SSD 840 Series 120GB     | 3        | 0.59%   |
| Kingston SV300S37A120G 120GB SSD | 3        | 0.59%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 0.59%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 2        | 0.39%   |
| WDC WD60EZRZ-00RWYB1 6TB         | 2        | 0.39%   |
| WDC WD60EFRX-68L0BN1 6TB         | 2        | 0.39%   |
| WDC WD3200AAKS-75B3A0 320GB      | 2        | 0.39%   |
| WDC WD30EZRX-00D8PB0 3TB         | 2        | 0.39%   |
| WDC WD30EFRX-68AX9N0 3TB         | 2        | 0.39%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 2        | 0.39%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 76       | 109    | 37.44%  |
| WDC                 | 69       | 96     | 33.99%  |
| Toshiba             | 22       | 28     | 10.84%  |
| Hitachi             | 18       | 25     | 8.87%   |
| Samsung Electronics | 7        | 10     | 3.45%   |
| Maxtor              | 5        | 6      | 2.46%   |
| Unknown             | 2        | 2      | 0.99%   |
| IBM/Hitachi         | 1        | 1      | 0.49%   |
| HGST                | 1        | 1      | 0.49%   |
| Fujitsu             | 1        | 1      | 0.49%   |
| External            | 1        | 1      | 0.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 47       | 64     | 26.7%   |
| Kingston            | 31       | 33     | 17.61%  |
| SanDisk             | 14       | 16     | 7.95%   |
| Crucial             | 14       | 16     | 7.95%   |
| China               | 12       | 17     | 6.82%   |
| A-DATA Technology   | 11       | 12     | 6.25%   |
| WDC                 | 8        | 9      | 4.55%   |
| GOODRAM             | 5        | 6      | 2.84%   |
| PNY                 | 4        | 5      | 2.27%   |
| Team                | 3        | 3      | 1.7%    |
| SPCC                | 3        | 3      | 1.7%    |
| Intel               | 3        | 4      | 1.7%    |
| Apacer              | 3        | 3      | 1.7%    |
| Transcend           | 2        | 2      | 1.14%   |
| Mushkin             | 2        | 2      | 1.14%   |
| WDC WDS1            | 1        | 1      | 0.57%   |
| WALRAM              | 1        | 1      | 0.57%   |
| Vaseky              | 1        | 1      | 0.57%   |
| Unknown             | 1        | 1      | 0.57%   |
| Rogueware           | 1        | 2      | 0.57%   |
| Plextor             | 1        | 1      | 0.57%   |
| OCZ                 | 1        | 1      | 0.57%   |
| Micron Technology   | 1        | 1      | 0.57%   |
| KingSpec            | 1        | 1      | 0.57%   |
| KingFast            | 1        | 1      | 0.57%   |
| Intenso             | 1        | 1      | 0.57%   |
| Gigabyte Technology | 1        | 1      | 0.57%   |
| Avant               | 1        | 1      | 0.57%   |
| Acer                | 1        | 1      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 154      | 280    | 41.96%  |
| SSD     | 146      | 210    | 39.78%  |
| NVMe    | 62       | 82     | 16.89%  |
| Unknown | 4        | 6      | 1.09%   |
| MMC     | 1        | 1      | 0.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 209      | 479    | 73.33%  |
| NVMe | 61       | 79     | 21.4%   |
| SAS  | 14       | 20     | 4.91%   |
| MMC  | 1        | 1      | 0.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 166      | 264    | 50.15%  |
| 0.51-1.0   | 93       | 128    | 28.1%   |
| 1.01-2.0   | 39       | 52     | 11.78%  |
| 3.01-4.0   | 12       | 13     | 3.63%   |
| 2.01-3.0   | 12       | 15     | 3.63%   |
| 4.01-10.0  | 8        | 17     | 2.42%   |
| 10.01-20.0 | 1        | 1      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 51       | 21.52%  |
| 251-500        | 46       | 19.41%  |
| 501-1000       | 34       | 14.35%  |
| 1001-2000      | 29       | 12.24%  |
| 2001-3000      | 23       | 9.7%    |
| More than 3000 | 22       | 9.28%   |
| 51-100         | 19       | 8.02%   |
| 1-20           | 7        | 2.95%   |
| 21-50          | 6        | 2.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 57       | 24.26%  |
| 101-250        | 38       | 16.17%  |
| 21-50          | 35       | 14.89%  |
| 251-500        | 27       | 11.49%  |
| 51-100         | 27       | 11.49%  |
| 1001-2000      | 19       | 8.09%   |
| 501-1000       | 17       | 7.23%   |
| More than 3000 | 8        | 3.4%    |
| 2001-3000      | 7        | 2.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Hitachi HUA722020ALA331 2TB     | 2        | 2      | 2.7%    |
| China SSD 512GB                 | 2        | 2      | 2.7%    |
| WDC WDS100T2B0A-00SM50 1TB SSD  | 1        | 1      | 1.35%   |
| WDC WD5003ABYX-01WERA1 500GB    | 1        | 1      | 1.35%   |
| WDC WD40EZRX-00SPEB0 4TB        | 1        | 1      | 1.35%   |
| WDC WD3200AAKS-00UU3A0 320GB    | 1        | 1      | 1.35%   |
| WDC WD3200AAJS-00B4A0 320GB     | 1        | 1      | 1.35%   |
| WDC WD2500AAJS-00B4A0 250GB     | 1        | 3      | 1.35%   |
| WDC WD20EZRX-00D8PB0 2TB        | 1        | 1      | 1.35%   |
| WDC WD20EFRX-68EUZN0 2TB        | 1        | 2      | 1.35%   |
| WDC WD20EARX-00PASB0 2TB        | 1        | 1      | 1.35%   |
| WDC WD20EARS-00J99B0 2TB        | 1        | 1      | 1.35%   |
| WDC WD1600AVVS-63L2B0 160GB     | 1        | 1      | 1.35%   |
| WDC WD15EADS-11P8B2 1TB         | 1        | 1      | 1.35%   |
| WDC WD10EZRZ-00HTKB0 1TB        | 1        | 1      | 1.35%   |
| WDC WD10EZEX-75WN4A0 1TB        | 1        | 1      | 1.35%   |
| WDC WD10EAVS-00D7B1 1TB         | 1        | 1      | 1.35%   |
| WDC WD10EADS-98M2B0 1TB         | 1        | 1      | 1.35%   |
| WDC WD10EADS-00M2B0 1TB         | 1        | 1      | 1.35%   |
| Toshiba MQ01ABF050 500GB        | 1        | 1      | 1.35%   |
| Toshiba MK7575GSX 752GB         | 1        | 1      | 1.35%   |
| Toshiba MK6465GSX 640GB         | 1        | 1      | 1.35%   |
| Toshiba MK1234GSX 120GB         | 1        | 1      | 1.35%   |
| Toshiba DT01ACA050 500GB        | 1        | 1      | 1.35%   |
| SPCC Solid State Disk 512GB     | 1        | 1      | 1.35%   |
| Seagate ST500LT012-9WS142 500GB | 1        | 1      | 1.35%   |
| Seagate ST500LM021-1KJ152 500GB | 1        | 1      | 1.35%   |
| Seagate ST380815AS 80GB         | 1        | 1      | 1.35%   |
| Seagate ST3750330NS 752GB       | 1        | 1      | 1.35%   |
| Seagate ST3500820AS 500GB       | 1        | 1      | 1.35%   |
| Seagate ST3500413AS 500GB       | 1        | 1      | 1.35%   |
| Seagate ST3360320AS 360GB       | 1        | 1      | 1.35%   |
| Seagate ST3320418AS 320GB       | 1        | 1      | 1.35%   |
| Seagate ST3320413CS 320GB       | 1        | 1      | 1.35%   |
| Seagate ST33000651NS 3TB        | 1        | 1      | 1.35%   |
| Seagate ST320LT020-9YG142 320GB | 1        | 1      | 1.35%   |
| Seagate ST320LT012-1DG14C 320GB | 1        | 2      | 1.35%   |
| Seagate ST31500341AS 1TB        | 1        | 1      | 1.35%   |
| Seagate ST31000524AS 1TB        | 1        | 1      | 1.35%   |
| Seagate ST250DM000-1BD141 250GB | 1        | 1      | 1.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 20     | 25%     |
| WDC                 | 17       | 20     | 23.61%  |
| Hitachi             | 7        | 8      | 9.72%   |
| Toshiba             | 5        | 5      | 6.94%   |
| Samsung Electronics | 5        | 8      | 6.94%   |
| Maxtor              | 4        | 4      | 5.56%   |
| Kingston            | 2        | 2      | 2.78%   |
| Crucial             | 2        | 2      | 2.78%   |
| China               | 2        | 2      | 2.78%   |
| A-DATA Technology   | 2        | 3      | 2.78%   |
| SPCC                | 1        | 1      | 1.39%   |
| Lexar               | 1        | 1      | 1.39%   |
| KingSpec            | 1        | 1      | 1.39%   |
| Intenso             | 1        | 1      | 1.39%   |
| IBM/Hitachi         | 1        | 1      | 1.39%   |
| HGST                | 1        | 1      | 1.39%   |
| GOODRAM             | 1        | 1      | 1.39%   |
| Fujitsu             | 1        | 1      | 1.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 20     | 33.33%  |
| WDC                 | 16       | 19     | 29.63%  |
| Hitachi             | 7        | 8      | 12.96%  |
| Toshiba             | 5        | 5      | 9.26%   |
| Maxtor              | 4        | 4      | 7.41%   |
| Samsung Electronics | 1        | 2      | 1.85%   |
| IBM/Hitachi         | 1        | 1      | 1.85%   |
| HGST                | 1        | 1      | 1.85%   |
| Fujitsu             | 1        | 1      | 1.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 50       | 61     | 74.63%  |
| SSD  | 16       | 20     | 23.88%  |
| NVMe | 1        | 1      | 1.49%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Toshiba MK5065GSX 500GB   | 2        | 2      | 66.67%  |
| Seagate ST3500418AS 500GB | 1        | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 2        | 2      | 66.67%  |
| Seagate | 1        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 204      | 450    | 68.92%  |
| Malfunc  | 64       | 82     | 21.62%  |
| Detected | 25       | 43     | 8.45%   |
| Failed   | 3        | 4      | 1.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 150      | 46.73%  |
| AMD                         | 67       | 20.87%  |
| Samsung Electronics         | 22       | 6.85%   |
| ASMedia Technology          | 14       | 4.36%   |
| JMicron Technology          | 10       | 3.12%   |
| Phison Electronics          | 9        | 2.8%    |
| SanDisk                     | 8        | 2.49%   |
| Marvell Technology Group    | 8        | 2.49%   |
| Silicon Motion              | 6        | 1.87%   |
| Micron/Crucial Technology   | 5        | 1.56%   |
| Kingston Technology Company | 5        | 1.56%   |
| Nvidia                      | 4        | 1.25%   |
| VIA Technologies            | 3        | 0.93%   |
| MAXIO Technology (Hangzhou) | 3        | 0.93%   |
| ULi Electronics             | 2        | 0.62%   |
| LSI Logic / Symbios Logic   | 2        | 0.62%   |
| ADATA Technology            | 2        | 0.62%   |
| Silicon Image               | 1        | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 30       | 7.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17       | 4.21%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14       | 3.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 3.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 3.22%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 2.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11       | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 2.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10       | 2.48%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9        | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 9        | 2.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 1.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 1.98%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 1.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 1.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 1.73%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.49%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6        | 1.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6        | 1.49%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6        | 1.49%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 6        | 1.49%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 1.49%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 5        | 1.24%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.24%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 1.24%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.24%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4        | 0.99%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 0.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.99%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4        | 0.99%   |
| Phison E12 NVMe Controller                                                              | 4        | 0.99%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.99%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.99%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.99%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 3        | 0.74%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 0.74%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 189      | 58.7%   |
| IDE  | 61       | 18.94%  |
| NVMe | 58       | 18.01%  |
| RAID | 12       | 3.73%   |
| SAS  | 1        | 0.31%   |
| SCSI | 1        | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 153      | 67.4%   |
| AMD          | 73       | 32.16%  |
| CentaurHauls | 1        | 0.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz       | 7        | 3.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 5        | 2.2%    |
| AMD Ryzen 7 3700X 8-Core Processor     | 4        | 1.76%   |
| AMD Ryzen 5 1600 Six-Core Processor    | 4        | 1.76%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 3        | 1.32%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 3        | 1.32%   |
| Intel Core i5-4690K CPU @ 3.50GHz      | 3        | 1.32%   |
| Intel Core i3-4160 CPU @ 3.60GHz       | 3        | 1.32%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz | 3        | 1.32%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 3        | 1.32%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 3        | 1.32%   |
| AMD Ryzen 5 1600X Six-Core Processor   | 3        | 1.32%   |
| AMD Phenom II X6 1090T Processor       | 3        | 1.32%   |
| Intel Pentium CPU G3240 @ 3.10GHz      | 2        | 0.88%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 2        | 0.88%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 2        | 0.88%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 2        | 0.88%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 2        | 0.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 2        | 0.88%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 2        | 0.88%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 2        | 0.88%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 2        | 0.88%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2        | 0.88%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 2        | 0.88%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 2        | 0.88%   |
| Intel Core i5-3350P CPU @ 3.10GHz      | 2        | 0.88%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 0.88%   |
| Intel Core i5 CPU 750 @ 2.67GHz        | 2        | 0.88%   |
| Intel Core i3-4130 CPU @ 3.40GHz       | 2        | 0.88%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 2        | 0.88%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 2        | 0.88%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz  | 2        | 0.88%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz  | 2        | 0.88%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz   | 2        | 0.88%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz | 2        | 0.88%   |
| AMD Ryzen 9 7900X 12-Core Processor    | 2        | 0.88%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 2        | 0.88%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 2        | 0.88%   |
| AMD Phenom II X4 925 Processor         | 2        | 0.88%   |
| AMD Athlon II X4 630 Processor         | 2        | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 42       | 18.5%   |
| Intel Core i7           | 29       | 12.78%  |
| AMD Ryzen 5             | 22       | 9.69%   |
| Intel Core i3           | 17       | 7.49%   |
| AMD Ryzen 7             | 13       | 5.73%   |
| Other                   | 12       | 5.29%   |
| Intel Core 2 Duo        | 10       | 4.41%   |
| Intel Core 2 Quad       | 7        | 3.08%   |
| Intel Celeron           | 7        | 3.08%   |
| Intel Xeon              | 6        | 2.64%   |
| Intel Pentium           | 5        | 2.2%    |
| AMD Phenom II X4        | 5        | 2.2%    |
| Intel Pentium 4         | 4        | 1.76%   |
| Intel Pentium Dual-Core | 3        | 1.32%   |
| Intel Core i9           | 3        | 1.32%   |
| AMD Ryzen 9             | 3        | 1.32%   |
| AMD Phenom II X6        | 3        | 1.32%   |
| AMD Athlon II X4        | 3        | 1.32%   |
| AMD Athlon II X2        | 3        | 1.32%   |
| Intel Pentium Gold      | 2        | 0.88%   |
| Intel Pentium D         | 2        | 0.88%   |
| AMD Sempron             | 2        | 0.88%   |
| AMD Ryzen 3             | 2        | 0.88%   |
| AMD Phenom              | 2        | 0.88%   |
| AMD FX                  | 2        | 0.88%   |
| AMD Athlon X4           | 2        | 0.88%   |
| AMD Athlon              | 2        | 0.88%   |
| AMD A4                  | 2        | 0.88%   |
| Intel Pentium Dual      | 1        | 0.44%   |
| Intel Core M            | 1        | 0.44%   |
| Intel Core 2 Extreme    | 1        | 0.44%   |
| Intel Celeron D         | 1        | 0.44%   |
| Intel Atom              | 1        | 0.44%   |
| CentaurHauls VIA Esther | 1        | 0.44%   |
| AMD Ryzen Threadripper  | 1        | 0.44%   |
| AMD Ryzen 5 PRO         | 1        | 0.44%   |
| AMD E1                  | 1        | 0.44%   |
| AMD Athlon 64 X2        | 1        | 0.44%   |
| AMD A8                  | 1        | 0.44%   |
| AMD A10                 | 1        | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 88       | 38.77%  |
| 2      | 60       | 26.43%  |
| 6      | 36       | 15.86%  |
| 8      | 23       | 10.13%  |
| 1      | 10       | 4.41%   |
| 12     | 6        | 2.64%   |
| 10     | 2        | 0.88%   |
| 16     | 1        | 0.44%   |
| 3      | 1        | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 226      | 99.56%  |
| 2      | 1        | 0.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 118      | 51.75%  |
| 1      | 110      | 48.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 224      | 98.68%  |
| 32-bit         | 3        | 1.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 14.04%  |
| 0x306c3    | 23       | 10.09%  |
| 0x206a7    | 15       | 6.58%   |
| 0x306a9    | 14       | 6.14%   |
| 0x1067a    | 10       | 4.39%   |
| 0x08701021 | 7        | 3.07%   |
| 0x906ed    | 6        | 2.63%   |
| 0x506e3    | 6        | 2.63%   |
| 0x0800820d | 6        | 2.63%   |
| 0xa0671    | 5        | 2.19%   |
| 0xa0653    | 5        | 2.19%   |
| 0x6fb      | 4        | 1.75%   |
| 0x106e5    | 4        | 1.75%   |
| 0x010000db | 4        | 1.75%   |
| 0x010000c8 | 4        | 1.75%   |
| 0x906ea    | 3        | 1.32%   |
| 0x0a601203 | 3        | 1.32%   |
| 0x08108109 | 3        | 1.32%   |
| 0x010000dc | 3        | 1.32%   |
| 0x01000083 | 3        | 1.32%   |
| 0x906e9    | 2        | 0.88%   |
| 0x706a1    | 2        | 0.88%   |
| 0x6fd      | 2        | 0.88%   |
| 0x506c9    | 2        | 0.88%   |
| 0x306f2    | 2        | 0.88%   |
| 0x206d7    | 2        | 0.88%   |
| 0x20655    | 2        | 0.88%   |
| 0x10677    | 2        | 0.88%   |
| 0x0a50000d | 2        | 0.88%   |
| 0x0a20120a | 2        | 0.88%   |
| 0x08600106 | 2        | 0.88%   |
| 0x08001138 | 2        | 0.88%   |
| 0x08001137 | 2        | 0.88%   |
| 0xf65      | 1        | 0.44%   |
| 0xf64      | 1        | 0.44%   |
| 0xf4a      | 1        | 0.44%   |
| 0xf49      | 1        | 0.44%   |
| 0xf47      | 1        | 0.44%   |
| 0xf34      | 1        | 0.44%   |
| 0xf29      | 1        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 29       | 12.78%  |
| SandyBridge      | 18       | 7.93%   |
| K10              | 17       | 7.49%   |
| IvyBridge        | 17       | 7.49%   |
| Penryn           | 16       | 7.05%   |
| KabyLake         | 15       | 6.61%   |
| Zen+             | 12       | 5.29%   |
| Zen 2            | 11       | 4.85%   |
| Unknown          | 10       | 4.41%   |
| Zen 3            | 8        | 3.52%   |
| Skylake          | 8        | 3.52%   |
| Zen              | 7        | 3.08%   |
| NetBurst         | 7        | 3.08%   |
| Nehalem          | 6        | 2.64%   |
| Core             | 6        | 2.64%   |
| CometLake        | 6        | 2.64%   |
| Westmere         | 4        | 1.76%   |
| Icelake          | 4        | 1.76%   |
| Alderlake Hybrid | 4        | 1.76%   |
| Steamroller      | 3        | 1.32%   |
| K8 Hammer        | 3        | 1.32%   |
| Goldmont plus    | 3        | 1.32%   |
| K10 Llano        | 2        | 0.88%   |
| Goldmont         | 2        | 0.88%   |
| Excavator        | 2        | 0.88%   |
| Tremont          | 1        | 0.44%   |
| Silvermont       | 1        | 0.44%   |
| Piledriver       | 1        | 0.44%   |
| Jaguar           | 1        | 0.44%   |
| Bulldozer        | 1        | 0.44%   |
| Broadwell        | 1        | 0.44%   |
| Bonnell          | 1        | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 97       | 38.65%  |
| Intel            | 80       | 31.87%  |
| AMD              | 73       | 29.08%  |
| VIA Technologies | 1        | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 11       | 4.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 3.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 3.09%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 2.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 2.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 2.32%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 1.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 1.93%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.54%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 1.54%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                         | 4        | 1.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 1.54%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.54%   |
| AMD Raphael                                                                 | 4        | 1.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 1.54%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 1.16%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 3        | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3        | 1.16%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 1.16%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                           | 3        | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.16%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 1.16%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.16%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 3        | 1.16%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.16%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 3        | 1.16%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.77%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 2        | 0.77%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.77%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.77%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 2        | 0.77%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.77%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.77%   |
| Nvidia GK107GL [Quadro K600]                                                | 2        | 0.77%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.77%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 0.77%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 2        | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 90       | 38.79%  |
| 1 x AMD        | 65       | 28.02%  |
| 1 x Intel      | 63       | 27.16%  |
| AMD + Nvidia   | 5        | 2.16%   |
| Intel + AMD    | 3        | 1.29%   |
| 2 x AMD        | 2        | 0.86%   |
| Intel + Nvidia | 2        | 0.86%   |
| 3 x AMD        | 1        | 0.43%   |
| 1 x VIA        | 1        | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 160      | 70.18%  |
| Proprietary | 59       | 25.88%  |
| Unknown     | 9        | 3.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 81       | 34.91%  |
| 1.01-2.0   | 38       | 16.38%  |
| 0.51-1.0   | 30       | 12.93%  |
| 3.01-4.0   | 24       | 10.34%  |
| 0.01-0.5   | 24       | 10.34%  |
| 7.01-8.0   | 20       | 8.62%   |
| 8.01-16.0  | 7        | 3.02%   |
| 5.01-6.0   | 4        | 1.72%   |
| 2.01-3.0   | 4        | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 38       | 15.7%   |
| Dell                 | 25       | 10.33%  |
| Goldstar             | 24       | 9.92%   |
| Acer                 | 22       | 9.09%   |
| Hewlett-Packard      | 13       | 5.37%   |
| AOC                  | 11       | 4.55%   |
| BenQ                 | 10       | 4.13%   |
| Ancor Communications | 10       | 4.13%   |
| ViewSonic            | 9        | 3.72%   |
| Philips              | 8        | 3.31%   |
| Sony                 | 7        | 2.89%   |
| ASUSTek Computer     | 6        | 2.48%   |
| Iiyama               | 5        | 2.07%   |
| Fujitsu Siemens      | 5        | 2.07%   |
| Lenovo               | 4        | 1.65%   |
| Eizo                 | 4        | 1.65%   |
| Vestel Elektronik    | 3        | 1.24%   |
| MSI                  | 3        | 1.24%   |
| Medion               | 3        | 1.24%   |
| Vizio                | 2        | 0.83%   |
| Sceptre Tech         | 2        | 0.83%   |
| Gigabyte Technology  | 2        | 0.83%   |
| Yeyian               | 1        | 0.41%   |
| Xiaomi               | 1        | 0.41%   |
| Videoseven           | 1        | 0.41%   |
| Toshiba              | 1        | 0.41%   |
| SANYO                | 1        | 0.41%   |
| Sangyo               | 1        | 0.41%   |
| SAC                  | 1        | 0.41%   |
| RTK                  | 1        | 0.41%   |
| RIS                  | 1        | 0.41%   |
| Panasonic            | 1        | 0.41%   |
| NECCI                | 1        | 0.41%   |
| NEC Computers        | 1        | 0.41%   |
| MiTAC                | 1        | 0.41%   |
| LG Electronics       | 1        | 0.41%   |
| JRY                  | 1        | 0.41%   |
| Insignia             | 1        | 0.41%   |
| IBM                  | 1        | 0.41%   |
| HYO                  | 1        | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 6        | 2.38%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch   | 3        | 1.19%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch            | 2        | 0.79%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                   | 2        | 0.79%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch    | 2        | 0.79%   |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                      | 2        | 0.79%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                 | 2        | 0.79%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                | 2        | 0.79%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                | 2        | 0.79%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch     | 2        | 0.79%   |
| Dell E2417H DELA0E2 1920x1080 527x296mm 23.8-inch                    | 2        | 0.79%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                   | 2        | 0.79%   |
| Yeyian YMG-4K27-01 YEY2700 3840x2160 600x330mm 27.0-inch             | 1        | 0.4%    |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                    | 1        | 0.4%    |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                   | 1        | 0.4%    |
| Vizio E480i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                 | 1        | 0.4%    |
| ViewSonic XG2705 VSC0E39 1920x1080 600x340mm 27.2-inch               | 1        | 0.4%    |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch               | 1        | 0.4%    |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch        | 1        | 0.4%    |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch        | 1        | 0.4%    |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch             | 1        | 0.4%    |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch           | 1        | 0.4%    |
| ViewSonic VA2012wSERIES VSC6A1C 1680x1050 430x270mm 20.0-inch        | 1        | 0.4%    |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch              | 1        | 0.4%    |
| Toshiba TV TSB0206 1920x1080 890x500mm 40.2-inch                     | 1        | 0.4%    |
| Sony TV SNY2C02 1920x1080 708x398mm 32.0-inch                        | 1        | 0.4%    |
| Sony TV SNY0801 1360x768                                             | 1        | 0.4%    |
| Sony TV *00 SNY7105 3840x2160 1218x685mm 55.0-inch                   | 1        | 0.4%    |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                 | 1        | 0.4%    |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                   | 1        | 0.4%    |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 520x320mm 24.0-inch       | 1        | 0.4%    |
| Sceptre Tech E225W-1920 SPT08D5 1920x1080 443x249mm 20.0-inch        | 1        | 0.4%    |
| SANYO LED MONITOR SAN2213 1600x900 477x268mm 21.5-inch               | 1        | 0.4%    |
| Sangyo LCD Monitor M27A3 1920x1080                                   | 1        | 0.4%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch    | 1        | 0.4%    |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch    | 1        | 0.4%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1        | 0.4%    |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                     | 1        | 0.4%    |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch | 1        | 0.4%    |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch | 1        | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 110      | 46.22%  |
| 3840x2160 (4K)     | 22       | 9.24%   |
| 2560x1440 (QHD)    | 21       | 8.82%   |
| 1280x1024 (SXGA)   | 18       | 7.56%   |
| 1680x1050 (WSXGA+) | 16       | 6.72%   |
| 1366x768 (WXGA)    | 10       | 4.2%    |
| 1600x1200          | 7        | 2.94%   |
| 1440x900 (WXGA+)   | 7        | 2.94%   |
| 1600x900 (HD+)     | 6        | 2.52%   |
| 3440x1440          | 3        | 1.26%   |
| 1920x1200 (WUXGA)  | 3        | 1.26%   |
| 1360x768           | 3        | 1.26%   |
| 2560x1080          | 2        | 0.84%   |
| 1280x720 (HD)      | 2        | 0.84%   |
| 1024x768 (XGA)     | 2        | 0.84%   |
| Unknown            | 2        | 0.84%   |
| 3840x1080          | 1        | 0.42%   |
| 2560x1600          | 1        | 0.42%   |
| 2048x1536          | 1        | 0.42%   |
| 1920x1440          | 1        | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 34       | 14.05%  |
| 23      | 34       | 14.05%  |
| 21      | 34       | 14.05%  |
| 24      | 26       | 10.74%  |
| 31      | 16       | 6.61%   |
| 22      | 14       | 5.79%   |
| 19      | 13       | 5.37%   |
| 18      | 12       | 4.96%   |
| 17      | 9        | 3.72%   |
| 20      | 7        | 2.89%   |
| Unknown | 7        | 2.89%   |
| 84      | 5        | 2.07%   |
| 65      | 5        | 2.07%   |
| 34      | 5        | 2.07%   |
| 15      | 4        | 1.65%   |
| 54      | 3        | 1.24%   |
| 25      | 2        | 0.83%   |
| 74      | 1        | 0.41%   |
| 72      | 1        | 0.41%   |
| 61      | 1        | 0.41%   |
| 55      | 1        | 0.41%   |
| 52      | 1        | 0.41%   |
| 49      | 1        | 0.41%   |
| 42      | 1        | 0.41%   |
| 40      | 1        | 0.41%   |
| 32      | 1        | 0.41%   |
| 28      | 1        | 0.41%   |
| 26      | 1        | 0.41%   |
| 16      | 1        | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 87       | 37.02%  |
| 401-500     | 69       | 29.36%  |
| 601-700     | 21       | 8.94%   |
| 351-400     | 12       | 5.11%   |
| 301-350     | 12       | 5.11%   |
| 1001-1500   | 12       | 5.11%   |
| 1501-2000   | 7        | 2.98%   |
| Unknown     | 7        | 2.98%   |
| 701-800     | 6        | 2.55%   |
| 801-900     | 1        | 0.43%   |
| 901-1000    | 1        | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 162      | 70.43%  |
| 16/10   | 28       | 12.17%  |
| 5/4     | 18       | 7.83%   |
| 4/3     | 10       | 4.35%   |
| Unknown | 6        | 2.61%   |
| 21/9    | 5        | 2.17%   |
| 3/2     | 1        | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 93       | 39.41%  |
| 301-350        | 34       | 14.41%  |
| 151-200        | 32       | 13.56%  |
| 351-500        | 23       | 9.75%   |
| More than 1000 | 18       | 7.63%   |
| 141-150        | 15       | 6.36%   |
| 251-300        | 7        | 2.97%   |
| Unknown        | 7        | 2.97%   |
| 101-110        | 2        | 0.85%   |
| 501-1000       | 2        | 0.85%   |
| 121-130        | 1        | 0.42%   |
| 111-120        | 1        | 0.42%   |
| 91-100         | 1        | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 153      | 66.52%  |
| 101-120 | 45       | 19.57%  |
| 1-50    | 14       | 6.09%   |
| 121-160 | 8        | 3.48%   |
| Unknown | 7        | 3.04%   |
| 161-240 | 3        | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 190      | 82.97%  |
| 2     | 32       | 13.97%  |
| 0     | 5        | 2.18%   |
| 3     | 2        | 0.87%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 143      | 42.94%  |
| Intel                           | 92       | 27.63%  |
| Qualcomm Atheros                | 19       | 5.71%   |
| TP-Link                         | 12       | 3.6%    |
| Broadcom                        | 10       | 3%      |
| Ralink Technology               | 9        | 2.7%    |
| MediaTek                        | 8        | 2.4%    |
| Ralink                          | 5        | 1.5%    |
| Broadcom Limited                | 5        | 1.5%    |
| Nvidia                          | 3        | 0.9%    |
| VIA Technologies                | 2        | 0.6%    |
| Samsung Electronics             | 2        | 0.6%    |
| Qualcomm Atheros Communications | 2        | 0.6%    |
| OPPO Electronics                | 2        | 0.6%    |
| Microsoft                       | 2        | 0.6%    |
| Marvell Technology Group        | 2        | 0.6%    |
| Linksys                         | 2        | 0.6%    |
| D-Link System                   | 2        | 0.6%    |
| Xiaomi                          | 1        | 0.3%    |
| U-Blox                          | 1        | 0.3%    |
| NetGear                         | 1        | 0.3%    |
| Mercucys                        | 1        | 0.3%    |
| JMicron Technology              | 1        | 0.3%    |
| IMC Networks                    | 1        | 0.3%    |
| Edimax Technology               | 1        | 0.3%    |
| D-Link                          | 1        | 0.3%    |
| AVM                             | 1        | 0.3%    |
| ASUSTek Computer                | 1        | 0.3%    |
| Aquantia                        | 1        | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 110      | 29.57%  |
| Intel Ethernet Controller I225-V                                  | 11       | 2.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 2.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 2.69%   |
| Intel I211 Gigabit Network Connection                             | 8        | 2.15%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 2.15%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8        | 2.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 1.88%   |
| Ralink MT7601U Wireless Adapter                                   | 6        | 1.61%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 1.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5        | 1.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 1.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5        | 1.34%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 1.34%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.34%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4        | 1.08%   |
| Intel Wireless-AC 9260                                            | 4        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 1.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 0.81%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 3        | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.81%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.81%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.81%   |
| Realtek 802.11ac NIC                                              | 3        | 0.81%   |
| Nvidia MCP61 Ethernet                                             | 3        | 0.81%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 0.81%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.81%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 0.81%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.81%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.54%   |
| Realtek 802.11ac WLAN Adapter                                     | 2        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.54%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.54%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.54%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.54%   |
| OPPO RMX3623                                                      | 2        | 0.54%   |
| Intel Wireless 8260                                               | 2        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 33       | 26.83%  |
| Intel                           | 27       | 21.95%  |
| TP-Link                         | 12       | 9.76%   |
| Qualcomm Atheros                | 10       | 8.13%   |
| Ralink Technology               | 9        | 7.32%   |
| MediaTek                        | 8        | 6.5%    |
| Ralink                          | 5        | 4.07%   |
| Broadcom                        | 4        | 3.25%   |
| Qualcomm Atheros Communications | 2        | 1.63%   |
| Microsoft                       | 2        | 1.63%   |
| Linksys                         | 2        | 1.63%   |
| NetGear                         | 1        | 0.81%   |
| Mercucys                        | 1        | 0.81%   |
| IMC Networks                    | 1        | 0.81%   |
| Edimax Technology               | 1        | 0.81%   |
| D-Link System                   | 1        | 0.81%   |
| D-Link                          | 1        | 0.81%   |
| Broadcom Limited                | 1        | 0.81%   |
| AVM                             | 1        | 0.81%   |
| ASUSTek Computer                | 1        | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                               | 6        | 4.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 5        | 4.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 5        | 4.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 5        | 4.03%   |
| Intel Wi-Fi 6 AX200                                                                           | 5        | 4.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 4        | 3.23%   |
| Intel Wireless-AC 9260                                                                        | 4        | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 4        | 3.23%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 3        | 2.42%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 3        | 2.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 2.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 3        | 2.42%   |
| Realtek 802.11ac NIC                                                                          | 3        | 2.42%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 3        | 2.42%   |
| Realtek 802.11ac WLAN Adapter                                                                 | 2        | 1.61%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 1.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 1.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 2        | 1.61%   |
| Intel Wireless 8260                                                                           | 2        | 1.61%   |
| Intel Wireless 7260                                                                           | 2        | 1.61%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 0.81%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                         | 1        | 0.81%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.81%   |
| TP-Link 802.11n NIC                                                                           | 1        | 0.81%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 0.81%   |
| TP-Link 802.11ac NIC                                                                          | 1        | 0.81%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 1        | 0.81%   |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller                                   | 1        | 0.81%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 0.81%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 0.81%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1        | 0.81%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 0.81%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1        | 0.81%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.81%   |
| Realtek B1610311068                                                                           | 1        | 0.81%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1        | 0.81%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 128      | 53.33%  |
| Intel                    | 79       | 32.92%  |
| Qualcomm Atheros         | 9        | 3.75%   |
| Broadcom                 | 6        | 2.5%    |
| Broadcom Limited         | 4        | 1.67%   |
| Nvidia                   | 3        | 1.25%   |
| VIA Technologies         | 2        | 0.83%   |
| OPPO Electronics         | 2        | 0.83%   |
| Marvell Technology Group | 2        | 0.83%   |
| Xiaomi                   | 1        | 0.42%   |
| Samsung Electronics      | 1        | 0.42%   |
| JMicron Technology       | 1        | 0.42%   |
| D-Link System            | 1        | 0.42%   |
| Aquantia                 | 1        | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 110      | 44.72%  |
| Intel Ethernet Controller I225-V                                  | 11       | 4.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 4.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 4.07%   |
| Intel I211 Gigabit Network Connection                             | 8        | 3.25%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 3.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8        | 3.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 2.85%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 2.44%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 2.03%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.22%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.22%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.22%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 1.22%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.22%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.81%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.81%   |
| OPPO RMX3623                                                      | 2        | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.81%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.81%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.81%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.81%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.41%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.41%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.41%   |
| Intel Ethernet Connection I218-V                                  | 1        | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.41%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.41%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 0.41%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 226      | 67.06%  |
| WiFi     | 109      | 32.34%  |
| Modem    | 2        | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 163      | 69.36%  |
| WiFi     | 72       | 30.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 151      | 66.52%  |
| 2     | 68       | 29.96%  |
| 3     | 8        | 3.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 183      | 79.91%  |
| Yes  | 46       | 20.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 24       | 36.92%  |
| Cambridge Silicon Radio         | 12       | 18.46%  |
| MediaTek                        | 7        | 10.77%  |
| Realtek Semiconductor           | 6        | 9.23%   |
| Broadcom                        | 5        | 7.69%   |
| TP-Link                         | 3        | 4.62%   |
| ASUSTek Computer                | 3        | 4.62%   |
| Foxconn / Hon Hai               | 2        | 3.08%   |
| Qualcomm Atheros Communications | 1        | 1.54%   |
| Lite-On Technology              | 1        | 1.54%   |
| Apple                           | 1        | 1.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 12       | 18.46%  |
| MediaTek Wireless_Device                              | 7        | 10.77%  |
| Realtek Bluetooth Radio                               | 6        | 9.23%   |
| Intel Bluetooth wireless interface                    | 5        | 7.69%   |
| Intel AX200 Bluetooth                                 | 5        | 7.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 5        | 7.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 4        | 6.15%   |
| Intel AX210 Bluetooth                                 | 4        | 6.15%   |
| TP-Link TP-Cdj+ UB5A Adapter                          | 3        | 4.62%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 4.62%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 3.08%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 1.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1        | 1.54%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 1.54%   |
| Intel Bluetooth Device                                | 1        | 1.54%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 1.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 1.54%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.54%   |
| ASUS BCM20702A0                                       | 1        | 1.54%   |
| Apple Bluetooth Host Controller                       | 1        | 1.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 147      | 37.89%  |
| AMD                     | 94       | 24.23%  |
| Nvidia                  | 90       | 23.2%   |
| C-Media Electronics     | 11       | 2.84%   |
| Creative Labs           | 10       | 2.58%   |
| VIA Technologies        | 3        | 0.77%   |
| Texas Instruments       | 3        | 0.77%   |
| JMTek                   | 3        | 0.77%   |
| ROCCAT                  | 2        | 0.52%   |
| Kingston Technology     | 2        | 0.52%   |
| Generalplus Technology  | 2        | 0.52%   |
| Focusrite-Novation      | 2        | 0.52%   |
| ULi Electronics         | 1        | 0.26%   |
| TerraTec Electronic     | 1        | 0.26%   |
| Tenx Technology         | 1        | 0.26%   |
| Setek Elektronik        | 1        | 0.26%   |
| Schiit Audio            | 1        | 0.26%   |
| Razer USA               | 1        | 0.26%   |
| Microsoft               | 1        | 0.26%   |
| M-Audio                 | 1        | 0.26%   |
| Logitech                | 1        | 0.26%   |
| GYROCOM C&C             | 1        | 0.26%   |
| GN Netcom               | 1        | 0.26%   |
| Giga-Byte Technology    | 1        | 0.26%   |
| Fortemedia              | 1        | 0.26%   |
| Ensoniq                 | 1        | 0.26%   |
| Emotiva                 | 1        | 0.26%   |
| Digidesign              | 1        | 0.26%   |
| Cambridge Silicon Radio | 1        | 0.26%   |
| BR25                    | 1        | 0.26%   |
| BEHRINGER International | 1        | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                                    | 18       | 4.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 17       | 3.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 16       | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 16       | 3.6%    |
| AMD Family 17h/19h HD Audio Controller                                                          | 16       | 3.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 14       | 3.15%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 12       | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 11       | 2.47%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 11       | 2.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 10       | 2.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 9        | 2.02%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 9        | 2.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 8        | 1.8%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 8        | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 8        | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                                      | 7        | 1.57%   |
| Intel 200 Series PCH HD Audio                                                                   | 7        | 1.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 7        | 1.57%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 7        | 1.57%   |
| Nvidia High Definition Audio Controller                                                         | 6        | 1.35%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 6        | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 6        | 1.35%   |
| AMD FCH Azalia Controller                                                                       | 6        | 1.35%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 6        | 1.35%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 5        | 1.12%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 5        | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 5        | 1.12%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 5        | 1.12%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 5        | 1.12%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 5        | 1.12%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 5        | 1.12%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 5        | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 5        | 1.12%   |
| Nvidia GK106 HDMI Audio Controller                                                              | 4        | 0.9%    |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 4        | 0.9%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 4        | 0.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 4        | 0.9%    |
| Nvidia TU104 HD Audio Controller                                                                | 3        | 0.67%   |
| Nvidia MCP61 High Definition Audio                                                              | 3        | 0.67%   |
| Nvidia GK110 High Definition Audio Controller                                                   | 3        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 45       | 17.79%  |
| Kingston                                | 41       | 16.21%  |
| Corsair                                 | 34       | 13.44%  |
| Samsung Electronics                     | 23       | 9.09%   |
| G.Skill                                 | 21       | 8.3%    |
| SK hynix                                | 18       | 7.11%   |
| Crucial                                 | 13       | 5.14%   |
| A-DATA Technology                       | 9        | 3.56%   |
| Ramaxel Technology                      | 7        | 2.77%   |
| Micron Technology                       | 7        | 2.77%   |
| Nanya Technology                        | 5        | 1.98%   |
| Unknown (ABCD)                          | 3        | 1.19%   |
| Patriot                                 | 3        | 1.19%   |
| Transcend                               | 2        | 0.79%   |
| Elpida                                  | 2        | 0.79%   |
| Apacer                                  | 2        | 0.79%   |
| Unknown                                 | 2        | 0.79%   |
| Unknown (AB)                            | 1        | 0.4%    |
| Unknown (0x0E9D)                        | 1        | 0.4%    |
| Unifosa                                 | 1        | 0.4%    |
| Timetec                                 | 1        | 0.4%    |
| Smart                                   | 1        | 0.4%    |
| Silicon Power Computer & Communications | 1        | 0.4%    |
| RZX                                     | 1        | 0.4%    |
| Qumo                                    | 1        | 0.4%    |
| PNY                                     | 1        | 0.4%    |
| Patriot Memory (PDP Systems)            | 1        | 0.4%    |
| OCZ                                     | 1        | 0.4%    |
| Lexar Co Limited                        | 1        | 0.4%    |
| Golden Empire                           | 1        | 0.4%    |
| CSX                                     | 1        | 0.4%    |
| Axiom                                   | 1        | 0.4%    |
| Avant                                   | 1        | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s             | 7        | 2.49%   |
| Unknown RAM Module 4GB DIMM SDRAM                                 | 3        | 1.07%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                           | 3        | 1.07%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                            | 3        | 1.07%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 3        | 1.07%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s              | 3        | 1.07%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s               | 3        | 1.07%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s             | 3        | 1.07%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 2        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                          | 2        | 0.71%   |
| Unknown RAM Module 2GB DIMM 800MT/s                               | 2        | 0.71%   |
| Unknown RAM Module 2GB DIMM 667MT/s                               | 2        | 0.71%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 2        | 0.71%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                           | 2        | 0.71%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                        | 2        | 0.71%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s             | 2        | 0.71%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s              | 2        | 0.71%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s              | 2        | 0.71%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s               | 2        | 0.71%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s               | 2        | 0.71%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3600MT/s               | 2        | 0.71%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s              | 2        | 0.71%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2667MT/s             | 2        | 0.71%   |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8GB DIMM DDR4 3600MT/s           | 2        | 0.71%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s              | 2        | 0.71%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s            | 2        | 0.71%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s             | 2        | 0.71%   |
| Unknown                                                           | 2        | 0.71%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1        | 0.36%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 1        | 0.36%   |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s                      | 1        | 0.36%   |
| Unknown RAM Module 512MB DIMM SDRAM                               | 1        | 0.36%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                         | 1        | 0.36%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                         | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                         | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                          | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR2 533MT/s                          | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM 667MT/s                               | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM                                       | 1        | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 86       | 37.39%  |
| DDR3    | 80       | 34.78%  |
| Unknown | 19       | 8.26%   |
| DDR2    | 17       | 7.39%   |
| SDRAM   | 13       | 5.65%   |
| DDR     | 6        | 2.61%   |
| DDR5    | 5        | 2.17%   |
| LPDDR4  | 3        | 1.3%    |
| LPDDR3  | 1        | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 206      | 91.96%  |
| SODIMM | 18       | 8.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 73       | 30.04%  |
| 4096  | 68       | 27.98%  |
| 2048  | 41       | 16.87%  |
| 16384 | 34       | 13.99%  |
| 1024  | 16       | 6.58%   |
| 32768 | 7        | 2.88%   |
| 512   | 3        | 1.23%   |
| 256   | 1        | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 41       | 16.33%  |
| 1333    | 37       | 14.74%  |
| 3200    | 20       | 7.97%   |
| 3600    | 18       | 7.17%   |
| 2400    | 13       | 5.18%   |
| 800     | 12       | 4.78%   |
| 2667    | 10       | 3.98%   |
| 667     | 10       | 3.98%   |
| 3000    | 8        | 3.19%   |
| 2133    | 8        | 3.19%   |
| Unknown | 8        | 3.19%   |
| 1800    | 6        | 2.39%   |
| 2933    | 5        | 1.99%   |
| 1867    | 4        | 1.59%   |
| 333     | 4        | 1.59%   |
| 6000    | 3        | 1.2%    |
| 3533    | 3        | 1.2%    |
| 2666    | 3        | 1.2%    |
| 2048    | 3        | 1.2%    |
| 1866    | 3        | 1.2%    |
| 533     | 3        | 1.2%    |
| 400     | 3        | 1.2%    |
| 49926   | 2        | 0.8%    |
| 3733    | 2        | 0.8%    |
| 3466    | 2        | 0.8%    |
| 3400    | 2        | 0.8%    |
| 2800    | 2        | 0.8%    |
| 1639    | 2        | 0.8%    |
| 1067    | 2        | 0.8%    |
| 5800    | 1        | 0.4%    |
| 4800    | 1        | 0.4%    |
| 4133    | 1        | 0.4%    |
| 3866    | 1        | 0.4%    |
| 3266    | 1        | 0.4%    |
| 3100    | 1        | 0.4%    |
| 2200    | 1        | 0.4%    |
| 2000    | 1        | 0.4%    |
| 1632    | 1        | 0.4%    |
| 1334    | 1        | 0.4%    |
| 1066    | 1        | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Canon                 | 4        | 30.77%  |
| Brother Industries    | 4        | 30.77%  |
| Hewlett-Packard       | 2        | 15.38%  |
| Seiko Epson           | 1        | 7.69%   |
| Lexmark International | 1        | 7.69%   |
| Konica Minolta        | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon MF641C                  | 2        | 15.38%  |
| Seiko Epson L382 Series       | 1        | 7.69%   |
| Lexmark International CS417dn | 1        | 7.69%   |
| Konica Minolta 206            | 1        | 7.69%   |
| HP ENVY 4500 series           | 1        | 7.69%   |
| HP Deskjet 1510               | 1        | 7.69%   |
| Canon PIXMA MG5600 Series     | 1        | 7.69%   |
| Canon MG5700 series           | 1        | 7.69%   |
| Brother Printer               | 1        | 7.69%   |
| Brother MFC-7340              | 1        | 7.69%   |
| Brother HL-L2350DW series     | 1        | 7.69%   |
| Brother DCP-L2540DW           | 1        | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 4        | 80%     |
| Seiko Epson | 1        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500] | 1        | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20    | 1        | 20%     |
| Canon CanoScan LIDE 25                | 1        | 20%     |
| Canon CanoScan LiDE 210               | 1        | 20%     |
| Canon CanoScan 8800F                  | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 13       | 33.33%  |
| Microsoft                     | 6        | 15.38%  |
| Sunplus Innovation Technology | 4        | 10.26%  |
| Microdia                      | 3        | 7.69%   |
| Generalplus Technology        | 2        | 5.13%   |
| Chicony Electronics           | 2        | 5.13%   |
| Z-Star Microelectronics       | 1        | 2.56%   |
| Trust                         | 1        | 2.56%   |
| Sunplus Technology            | 1        | 2.56%   |
| Sonix Technology              | 1        | 2.56%   |
| Pixart Imaging                | 1        | 2.56%   |
| Huawei Technologies           | 1        | 2.56%   |
| Hewlett-Packard               | 1        | 2.56%   |
| Aveo Technology               | 1        | 2.56%   |
| Arkmicro Technologies         | 1        | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                               | 4        | 10.26%  |
| Logitech Webcam C930e                                   | 3        | 7.69%   |
| Logitech Webcam C270                                    | 3        | 7.69%   |
| Sunplus HD 720P webcam                                  | 2        | 5.13%   |
| Logitech Webcam C200                                    | 2        | 5.13%   |
| Z-Star Traveler TV 6500 SF Dia-scanner                  | 1        | 2.56%   |
| Trust Widescreen 3MP Webcam                             | 1        | 2.56%   |
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode) | 1        | 2.56%   |
| Sunplus NexiGo N930AF FHD Webcam                        | 1        | 2.56%   |
| Sunplus 5Mega Webcam                                    | 1        | 2.56%   |
| Sonix USB Camera                                        | 1        | 2.56%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 1        | 2.56%   |
| Microsoft LifeCam VX-800                                | 1        | 2.56%   |
| Microsoft LifeCam VX-500 [1357]                         | 1        | 2.56%   |
| Microdia USB Camera                                     | 1        | 2.56%   |
| Microdia Integrated Camera                              | 1        | 2.56%   |
| Microdia Camera                                         | 1        | 2.56%   |
| Logitech Webcam Pro 9000                                | 1        | 2.56%   |
| Logitech Webcam C310                                    | 1        | 2.56%   |
| Logitech Webcam C110                                    | 1        | 2.56%   |
| Logitech HD Webcam C615                                 | 1        | 2.56%   |
| Logitech B525 HD Webcam                                 | 1        | 2.56%   |
| Huawei UVC Camera                                       | 1        | 2.56%   |
| HP Webcam HD 2300                                       | 1        | 2.56%   |
| Generalplus GENERAL WEBCAM                              | 1        | 2.56%   |
| Generalplus 808 Camera #9 (web-cam mode)                | 1        | 2.56%   |
| Chicony HP Prem AF Webcam KQ245AA                       | 1        | 2.56%   |
| Chicony HD Webcam                                       | 1        | 2.56%   |
| Aveo Camera                                             | 1        | 2.56%   |
| Arkmicro Acme CA04                                      | 1        | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Microsoft Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 191      | 83.77%  |
| 1     | 33       | 14.47%  |
| 3     | 2        | 0.88%   |
| 2     | 2        | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 16       | 40%     |
| Net/wireless             | 11       | 27.5%   |
| Unassigned class         | 3        | 7.5%    |
| Communication controller | 3        | 7.5%    |
| Network                  | 1        | 2.5%    |
| Multimedia controller    | 1        | 2.5%    |
| Fingerprint reader       | 1        | 2.5%    |
| Dvb card                 | 1        | 2.5%    |
| Card reader              | 1        | 2.5%    |
| Camera                   | 1        | 2.5%    |
| Bluetooth                | 1        | 2.5%    |

