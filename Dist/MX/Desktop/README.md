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

Total: 282

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MX 21          | 114      | 51.35%  |
| MX 19          | 46       | 20.72%  |
| MX 23          | 25       | 11.26%  |
| MX 20          | 22       | 9.91%   |
| MX 18          | 12       | 5.41%   |
| MX 22          | 1        | 0.45%   |
| MX 17          | 1        | 0.45%   |
| MX 16-migrated | 1        | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MX   | 217      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 4.19.0-6-amd64            | 20       | 8.55%   |
| 5.10.0-21-amd64           | 15       | 6.41%   |
| 5.10.0-20-amd64           | 13       | 5.56%   |
| 6.0.0-6mx-amd64           | 10       | 4.27%   |
| 5.14.0-4mx-amd64          | 7        | 2.99%   |
| 6.1.0-10-amd64            | 6        | 2.56%   |
| 5.6.0-2-amd64             | 6        | 2.56%   |
| 5.10.0-5mx-amd64          | 6        | 2.56%   |
| 5.10.0-23-amd64           | 6        | 2.56%   |
| 5.10.0-19-amd64           | 6        | 2.56%   |
| 5.10.0-18-amd64           | 6        | 2.56%   |
| 6.1.0-13-amd64            | 5        | 2.14%   |
| 5.18.0-4mx-amd64          | 5        | 2.14%   |
| 5.10.0-13-amd64           | 5        | 2.14%   |
| 4.19.0-17-amd64           | 5        | 2.14%   |
| 6.1.0-11-amd64            | 4        | 1.71%   |
| 5.8.0-3-amd64             | 4        | 1.71%   |
| 5.10.0-16-amd64           | 4        | 1.71%   |
| 5.10.0-15-amd64           | 4        | 1.71%   |
| 4.19.0-14-amd64           | 4        | 1.71%   |
| 6.4.0-1mx-ahs-amd64       | 3        | 1.28%   |
| 6.0.0-10.1-liquorix-amd64 | 3        | 1.28%   |
| 5.4.0-3-amd64             | 3        | 1.28%   |
| 5.16.0-5mx-amd64          | 3        | 1.28%   |
| 4.19.0-5-amd64            | 3        | 1.28%   |
| 4.19.0-18-amd64           | 3        | 1.28%   |
| 4.19.0-13-amd64           | 3        | 1.28%   |
| 4.19.0-1-amd64            | 3        | 1.28%   |
| 5.8.16-antix.1-amd64-smp  | 2        | 0.85%   |
| 5.14.0-3mx-amd64          | 2        | 0.85%   |
| 5.10.0-9-amd64            | 2        | 0.85%   |
| 5.10.0-11-amd64           | 2        | 0.85%   |
| 4.19.0-16-amd64           | 2        | 0.85%   |
| 4.19.0-12-amd64           | 2        | 0.85%   |
| 6.5.5-2-liquorix-amd64    | 1        | 0.43%   |
| 6.5.0-2-amd64             | 1        | 0.43%   |
| 6.5.0-1mx-ahs-amd64       | 1        | 0.43%   |
| 6.4.14-1-liquorix-amd64   | 1        | 0.43%   |
| 6.4.0-3mx-ahs-amd64       | 1        | 0.43%   |
| 6.3.9-1-liquorix-amd64    | 1        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 78       | 34.67%  |
| 4.19.0   | 45       | 20%     |
| 6.1.0    | 16       | 7.11%   |
| 6.0.0    | 15       | 6.67%   |
| 5.14.0   | 10       | 4.44%   |
| 5.6.0    | 6        | 2.67%   |
| 5.5.0    | 5        | 2.22%   |
| 5.18.0   | 5        | 2.22%   |
| 5.16.0   | 5        | 2.22%   |
| 6.4.0    | 4        | 1.78%   |
| 5.8.0    | 4        | 1.78%   |
| 5.4.0    | 3        | 1.33%   |
| 5.19.0   | 3        | 1.33%   |
| 5.15.0   | 3        | 1.33%   |
| 6.5.0    | 2        | 0.89%   |
| 5.8.16   | 2        | 0.89%   |
| 5.3.0    | 2        | 0.89%   |
| 6.5.5    | 1        | 0.44%   |
| 6.4.14   | 1        | 0.44%   |
| 6.3.9    | 1        | 0.44%   |
| 6.2.14   | 1        | 0.44%   |
| 6.1.15   | 1        | 0.44%   |
| 6.0.5    | 1        | 0.44%   |
| 5.4.7    | 1        | 0.44%   |
| 5.4.10   | 1        | 0.44%   |
| 5.2.21   | 1        | 0.44%   |
| 5.17.0   | 1        | 0.44%   |
| 5.11.0   | 1        | 0.44%   |
| 5.10.52  | 1        | 0.44%   |
| 5.10.113 | 1        | 0.44%   |
| 5.10.111 | 1        | 0.44%   |
| 4.9.91   | 1        | 0.44%   |
| 4.18.0   | 1        | 0.44%   |
| 4.15.0   | 1        | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 81       | 36%     |
| 4.19    | 45       | 20%     |
| 6.1     | 17       | 7.56%   |
| 6.0     | 16       | 7.11%   |
| 5.14    | 10       | 4.44%   |
| 5.8     | 6        | 2.67%   |
| 5.6     | 6        | 2.67%   |
| 6.4     | 5        | 2.22%   |
| 5.5     | 5        | 2.22%   |
| 5.4     | 5        | 2.22%   |
| 5.18    | 5        | 2.22%   |
| 5.16    | 5        | 2.22%   |
| 6.5     | 3        | 1.33%   |
| 5.19    | 3        | 1.33%   |
| 5.15    | 3        | 1.33%   |
| 5.3     | 2        | 0.89%   |
| 6.3     | 1        | 0.44%   |
| 6.2     | 1        | 0.44%   |
| 5.2     | 1        | 0.44%   |
| 5.17    | 1        | 0.44%   |
| 5.11    | 1        | 0.44%   |
| 4.9     | 1        | 0.44%   |
| 4.18    | 1        | 0.44%   |
| 4.15    | 1        | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 210      | 96.77%  |
| i686   | 7        | 3.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 166      | 76.15%  |
| KDE5             | 41       | 18.81%  |
| MATE             | 3        | 1.38%   |
| lightdm-xsession | 3        | 1.38%   |
| X-Cinnamon       | 1        | 0.46%   |
| LXQt             | 1        | 0.46%   |
| KDE4             | 1        | 0.46%   |
| KDE              | 1        | 0.46%   |
| Unknown          | 1        | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 216      | 99.54%  |
| Tty  | 1        | 0.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 175      | 80.28%  |
| SDDM    | 37       | 16.97%  |
| SLiM    | 3        | 1.38%   |
| TDM     | 2        | 0.92%   |
| GDM     | 1        | 0.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 81       | 36.49%  |
| Unknown | 34       | 15.32%  |
| de_DE   | 21       | 9.46%   |
| en_GB   | 11       | 4.95%   |
| it_IT   | 9        | 4.05%   |
| es_ES   | 8        | 3.6%    |
| ru_RU   | 7        | 3.15%   |
| pl_PL   | 7        | 3.15%   |
| sk_SK   | 5        | 2.25%   |
| pt_BR   | 5        | 2.25%   |
| fr_FR   | 5        | 2.25%   |
| es_AR   | 5        | 2.25%   |
| es_MX   | 3        | 1.35%   |
| en_AU   | 3        | 1.35%   |
| de_CH   | 3        | 1.35%   |
| sv_SE   | 2        | 0.9%    |
| hu_HU   | 2        | 0.9%    |
| hr_HR   | 2        | 0.9%    |
| en_IE   | 2        | 0.9%    |
| uk_UA   | 1        | 0.45%   |
| tr_TR   | 1        | 0.45%   |
| fi_FI   | 1        | 0.45%   |
| es_VE   | 1        | 0.45%   |
| es_CO   | 1        | 0.45%   |
| en_NZ   | 1        | 0.45%   |
| en_CA   | 1        | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 129      | 58.9%   |
| EFI  | 90       | 41.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 195      | 89.86%  |
| Overlay  | 12       | 5.53%   |
| Btrfs    | 5        | 2.3%    |
| Tmpfs    | 2        | 0.92%   |
| Xfs      | 1        | 0.46%   |
| Reiserfs | 1        | 0.46%   |
| Ext3     | 1        | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 124      | 56.36%  |
| MBR     | 94       | 42.73%  |
| Unknown | 2        | 0.91%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 146      | 65.18%  |
| Yes       | 78       | 34.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 121      | 55.76%  |
| No        | 96       | 44.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 47       | 21.66%  |
| Gigabyte Technology                  | 34       | 15.67%  |
| MSI                                  | 25       | 11.52%  |
| ASRock                               | 24       | 11.06%  |
| Dell                                 | 20       | 9.22%   |
| Hewlett-Packard                      | 15       | 6.91%   |
| Intel                                | 9        | 4.15%   |
| Lenovo                               | 7        | 3.23%   |
| Unknown                              | 4        | 1.84%   |
| Foxconn                              | 3        | 1.38%   |
| Biostar                              | 3        | 1.38%   |
| Pegatron                             | 2        | 0.92%   |
| Medion                               | 2        | 0.92%   |
| Gateway                              | 2        | 0.92%   |
| Fujitsu                              | 2        | 0.92%   |
| ECS                                  | 2        | 0.92%   |
| ZOTAC                                | 1        | 0.46%   |
| SLIMBOOK                             | 1        | 0.46%   |
| SIRAGON                              | 1        | 0.46%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.46%   |
| Positivo                             | 1        | 0.46%   |
| OEM                                  | 1        | 0.46%   |
| MP                                   | 1        | 0.46%   |
| IBM                                  | 1        | 0.46%   |
| Huanan                               | 1        | 0.46%   |
| GreatWall                            | 1        | 0.46%   |
| GALAX                                | 1        | 0.46%   |
| Fujitsu Siemens                      | 1        | 0.46%   |
| BESSTAR Tech                         | 1        | 0.46%   |
| AZW                                  | 1        | 0.46%   |
| AOpen                                | 1        | 0.46%   |
| Acer                                 | 1        | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 9        | 4.15%   |
| Unknown                                    | 6        | 2.76%   |
| MSI MS-7C91                                | 2        | 0.92%   |
| MSI MS-7A34                                | 2        | 0.92%   |
| Intel H81                                  | 2        | 0.92%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 0.92%   |
| Foxconn Pro3500 Series                     | 2        | 0.92%   |
| Dell Studio 540                            | 2        | 0.92%   |
| Dell OptiPlex 9020                         | 2        | 0.92%   |
| Dell OptiPlex 9010                         | 2        | 0.92%   |
| Dell OptiPlex 790                          | 2        | 0.92%   |
| Dell OptiPlex 755                          | 2        | 0.92%   |
| ASUS ROG Maximus XIII HERO                 | 2        | 0.92%   |
| ASUS PRIME B450M-A                         | 2        | 0.92%   |
| ASRock K8A780LM                            | 2        | 0.92%   |
| SLIMBOOK ONE-AMD-M4                        | 1        | 0.46%   |
| SIRAGON AIO-5150                           | 1        | 0.46%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.46%   |
| Positivo POS-PQ45AU                        | 1        | 0.46%   |
| Pegatron FQ425AA-ABA a6655f                | 1        | 0.46%   |
| Pegatron 2AD5                              | 1        | 0.46%   |
| OEM Intel H81                              | 1        | 0.46%   |
| MSI MS-7E12                                | 1        | 0.46%   |
| MSI MS-7C95                                | 1        | 0.46%   |
| MSI MS-7C94                                | 1        | 0.46%   |
| MSI MS-7C88                                | 1        | 0.46%   |
| MSI MS-7C56                                | 1        | 0.46%   |
| MSI MS-7C37                                | 1        | 0.46%   |
| MSI MS-7B98                                | 1        | 0.46%   |
| MSI MS-7B86                                | 1        | 0.46%   |
| MSI MS-7B53                                | 1        | 0.46%   |
| MSI MS-7A63                                | 1        | 0.46%   |
| MSI MS-7917                                | 1        | 0.46%   |
| MSI MS-7823                                | 1        | 0.46%   |
| MSI MS-7815                                | 1        | 0.46%   |
| MSI MS-7808                                | 1        | 0.46%   |
| MSI MS-7758                                | 1        | 0.46%   |
| MSI MS-7721                                | 1        | 0.46%   |
| MSI MS-7693                                | 1        | 0.46%   |
| MSI MS-7641                                | 1        | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 14       | 6.45%   |
| ASUS PRIME                                 | 9        | 4.15%   |
| ASUS All                                   | 9        | 4.15%   |
| Unknown                                    | 6        | 2.76%   |
| HP Compaq                                  | 5        | 2.3%    |
| ASUS ROG                                   | 5        | 2.3%    |
| ASUS TUF                                   | 4        | 1.84%   |
| MSI MS-7C91                                | 2        | 0.92%   |
| MSI MS-7A34                                | 2        | 0.92%   |
| Lenovo ThinkCentre                         | 2        | 0.92%   |
| Lenovo IdeaCentre                          | 2        | 0.92%   |
| Intel H81                                  | 2        | 0.92%   |
| Gigabyte Z390                              | 2        | 0.92%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 0.92%   |
| Gigabyte B550M                             | 2        | 0.92%   |
| Foxconn Pro3500                            | 2        | 0.92%   |
| Dell Studio                                | 2        | 0.92%   |
| Dell Inspiron                              | 2        | 0.92%   |
| ASUS P5GC-MX                               | 2        | 0.92%   |
| ASRock X370                                | 2        | 0.92%   |
| ASRock K8A780LM                            | 2        | 0.92%   |
| SLIMBOOK ONE-AMD-M4                        | 1        | 0.46%   |
| SIRAGON AIO-5150                           | 1        | 0.46%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.46%   |
| Positivo POS-PQ45AU                        | 1        | 0.46%   |
| Pegatron FQ425AA-ABA                       | 1        | 0.46%   |
| Pegatron 2AD5                              | 1        | 0.46%   |
| OEM Intel                                  | 1        | 0.46%   |
| MSI MS-7E12                                | 1        | 0.46%   |
| MSI MS-7C95                                | 1        | 0.46%   |
| MSI MS-7C94                                | 1        | 0.46%   |
| MSI MS-7C88                                | 1        | 0.46%   |
| MSI MS-7C56                                | 1        | 0.46%   |
| MSI MS-7C37                                | 1        | 0.46%   |
| MSI MS-7B98                                | 1        | 0.46%   |
| MSI MS-7B86                                | 1        | 0.46%   |
| MSI MS-7B53                                | 1        | 0.46%   |
| MSI MS-7A63                                | 1        | 0.46%   |
| MSI MS-7917                                | 1        | 0.46%   |
| MSI MS-7823                                | 1        | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 19       | 8.76%   |
| 2018 | 17       | 7.83%   |
| 2011 | 17       | 7.83%   |
| 2021 | 16       | 7.37%   |
| 2012 | 16       | 7.37%   |
| 2020 | 15       | 6.91%   |
| 2019 | 14       | 6.45%   |
| 2022 | 13       | 5.99%   |
| 2014 | 12       | 5.53%   |
| 2010 | 12       | 5.53%   |
| 2016 | 11       | 5.07%   |
| 2009 | 11       | 5.07%   |
| 2017 | 9        | 4.15%   |
| 2008 | 9        | 4.15%   |
| 2015 | 8        | 3.69%   |
| 2007 | 8        | 3.69%   |
| 2006 | 4        | 1.84%   |
| 2023 | 3        | 1.38%   |
| 2005 | 2        | 0.92%   |
| 2004 | 1        | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 217      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 217      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 217      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 54       | 24.77%  |
| 8.01-16.0   | 53       | 24.31%  |
| 4.01-8.0    | 36       | 16.51%  |
| 32.01-64.0  | 29       | 13.3%   |
| 3.01-4.0    | 23       | 10.55%  |
| 24.01-32.0  | 8        | 3.67%   |
| 1.01-2.0    | 7        | 3.21%   |
| 64.01-256.0 | 3        | 1.38%   |
| 0.51-1.0    | 3        | 1.38%   |
| 2.01-3.0    | 2        | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 77       | 34.22%  |
| 2.01-3.0   | 61       | 27.11%  |
| 3.01-4.0   | 32       | 14.22%  |
| 4.01-8.0   | 29       | 12.89%  |
| 0.51-1.0   | 16       | 7.11%   |
| 8.01-16.0  | 7        | 3.11%   |
| 0.01-0.5   | 2        | 0.89%   |
| 16.01-24.0 | 1        | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 79       | 35.27%  |
| 2      | 67       | 29.91%  |
| 3      | 42       | 18.75%  |
| 4      | 17       | 7.59%   |
| 5      | 12       | 5.36%   |
| 8      | 3        | 1.34%   |
| 9      | 1        | 0.45%   |
| 7      | 1        | 0.45%   |
| 6      | 1        | 0.45%   |
| 0      | 1        | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 111      | 50.68%  |
| No        | 108      | 49.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 216      | 99.54%  |
| No        | 1        | 0.46%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 114      | 52.53%  |
| Yes       | 103      | 47.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 157      | 72.35%  |
| Yes       | 60       | 27.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 51       | 23.5%   |
| Germany                | 19       | 8.76%   |
| Italy                  | 11       | 5.07%   |
| UK                     | 10       | 4.61%   |
| Spain                  | 10       | 4.61%   |
| Russia                 | 10       | 4.61%   |
| Poland                 | 9        | 4.15%   |
| France                 | 8        | 3.69%   |
| Slovakia               | 7        | 3.23%   |
| India                  | 7        | 3.23%   |
| Canada                 | 7        | 3.23%   |
| Australia              | 7        | 3.23%   |
| Sweden                 | 6        | 2.76%   |
| Brazil                 | 6        | 2.76%   |
| Finland                | 5        | 2.3%    |
| Argentina              | 5        | 2.3%    |
| Switzerland            | 3        | 1.38%   |
| Serbia                 | 3        | 1.38%   |
| Mexico                 | 3        | 1.38%   |
| Venezuela              | 2        | 0.92%   |
| Singapore              | 2        | 0.92%   |
| Netherlands            | 2        | 0.92%   |
| Indonesia              | 2        | 0.92%   |
| Hungary                | 2        | 0.92%   |
| Denmark                | 2        | 0.92%   |
| Bosnia and Herzegovina | 2        | 0.92%   |
| Belgium                | 2        | 0.92%   |
| Ukraine                | 1        | 0.46%   |
| Turkey                 | 1        | 0.46%   |
| South Africa           | 1        | 0.46%   |
| Romania                | 1        | 0.46%   |
| Philippines            | 1        | 0.46%   |
| New Zealand            | 1        | 0.46%   |
| Ireland                | 1        | 0.46%   |
| Greece                 | 1        | 0.46%   |
| French Guiana          | 1        | 0.46%   |
| Estonia                | 1        | 0.46%   |
| Croatia                | 1        | 0.46%   |
| Colombia               | 1        | 0.46%   |
| Austria                | 1        | 0.46%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bratislava               | 7        | 3.17%   |
| Sydney                   | 4        | 1.81%   |
| Moscow                   | 4        | 1.81%   |
| Florianópolis           | 3        | 1.36%   |
| Berlin                   | 3        | 1.36%   |
| Bengaluru                | 3        | 1.36%   |
| Barcelona                | 3        | 1.36%   |
| Toronto                  | 2        | 0.9%    |
| St Petersburg            | 2        | 0.9%    |
| Singapore                | 2        | 0.9%    |
| Mesquite                 | 2        | 0.9%    |
| Melbourne                | 2        | 0.9%    |
| Krakow                   | 2        | 0.9%    |
| Houston                  | 2        | 0.9%    |
| Ettingen                 | 2        | 0.9%    |
| Espoo                    | 2        | 0.9%    |
| Córdoba                 | 2        | 0.9%    |
| Centreville              | 2        | 0.9%    |
| Cazin                    | 2        | 0.9%    |
| Birmingham               | 2        | 0.9%    |
| Belgrade                 | 2        | 0.9%    |
| Alma                     | 2        | 0.9%    |
| Albertslund Municipality | 2        | 0.9%    |
| Zagreb                   | 1        | 0.45%   |
| Yuzhno-Sakhalinsk        | 1        | 0.45%   |
| Warsaw                   | 1        | 0.45%   |
| Warren                   | 1        | 0.45%   |
| Wandsworth               | 1        | 0.45%   |
| Volos                    | 1        | 0.45%   |
| Voghera                  | 1        | 0.45%   |
| Virginia Beach           | 1        | 0.45%   |
| Villeurbanne             | 1        | 0.45%   |
| Vilhelmina               | 1        | 0.45%   |
| Vienna                   | 1        | 0.45%   |
| Vera                     | 1        | 0.45%   |
| Vasco da Gama            | 1        | 0.45%   |
| Valencia                 | 1        | 0.45%   |
| Vaidasoo                 | 1        | 0.45%   |
| Tuglie                   | 1        | 0.45%   |
| Tomsk                    | 1        | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 77       | 101    | 18.38%  |
| Seagate                     | 73       | 104    | 17.42%  |
| Samsung Electronics         | 63       | 104    | 15.04%  |
| Kingston                    | 34       | 36     | 8.11%   |
| Toshiba                     | 22       | 28     | 5.25%   |
| SanDisk                     | 19       | 22     | 4.53%   |
| Hitachi                     | 17       | 23     | 4.06%   |
| Crucial                     | 16       | 17     | 3.82%   |
| China                       | 12       | 15     | 2.86%   |
| A-DATA Technology           | 12       | 12     | 2.86%   |
| Unknown                     | 6        | 8      | 1.43%   |
| Intel                       | 6        | 7      | 1.43%   |
| PNY                         | 5        | 7      | 1.19%   |
| Maxtor                      | 5        | 6      | 1.19%   |
| GOODRAM                     | 5        | 6      | 1.19%   |
| Corsair                     | 4        | 4      | 0.95%   |
| Apacer                      | 4        | 4      | 0.95%   |
| SPCC                        | 3        | 3      | 0.72%   |
| Silicon Motion              | 3        | 3      | 0.72%   |
| Mushkin                     | 3        | 3      | 0.72%   |
| Transcend                   | 2        | 2      | 0.48%   |
| Team                        | 2        | 2      | 0.48%   |
| Micron/Crucial Technology   | 2        | 2      | 0.48%   |
| XPG                         | 1        | 1      | 0.24%   |
| WDC WDS1                    | 1        | 1      | 0.24%   |
| WALRAM                      | 1        | 1      | 0.24%   |
| Vaseky                      | 1        | 1      | 0.24%   |
| Rogueware                   | 1        | 2      | 0.24%   |
| Phison Electronics          | 1        | 1      | 0.24%   |
| Phison                      | 1        | 1      | 0.24%   |
| OCZ                         | 1        | 1      | 0.24%   |
| Netac                       | 1        | 1      | 0.24%   |
| Micron Technology           | 1        | 1      | 0.24%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.24%   |
| Lexar                       | 1        | 1      | 0.24%   |
| KingSpec                    | 1        | 1      | 0.24%   |
| KingFast                    | 1        | 1      | 0.24%   |
| JMicron Technology          | 1        | 1      | 0.24%   |
| Intenso                     | 1        | 1      | 0.24%   |
| IBM/Hitachi                 | 1        | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 9        | 1.86%   |
| Seagate ST2000DM008-2FR102 2TB   | 7        | 1.44%   |
| Seagate ST4000DM004-2CV104 4TB   | 6        | 1.24%   |
| Samsung SSD 860 EVO 500GB        | 6        | 1.24%   |
| Seagate ST1000DM010-2EP102 1TB   | 5        | 1.03%   |
| Samsung SSD 970 EVO Plus 1TB     | 5        | 1.03%   |
| Samsung SSD 850 EVO 250GB        | 5        | 1.03%   |
| Kingston SV300S37A240G 240GB SSD | 5        | 1.03%   |
| Toshiba DT01ACA100 1TB           | 4        | 0.82%   |
| Seagate ST500DM002-1BD142 500GB  | 4        | 0.82%   |
| Seagate ST3500413AS 500GB        | 4        | 0.82%   |
| Samsung SSD 860 EVO 250GB        | 4        | 0.82%   |
| WDC WD10EZEX-60WN4A0 1TB         | 3        | 0.62%   |
| WDC WD10EZEX-00BN5A0 1TB         | 3        | 0.62%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 3        | 0.62%   |
| SanDisk SDSSDA240G 240GB         | 3        | 0.62%   |
| SanDisk NVMe SSD Drive 1TB       | 3        | 0.62%   |
| Samsung SSD 980 PRO 1TB          | 3        | 0.62%   |
| Samsung SSD 980 500GB            | 3        | 0.62%   |
| Samsung SSD 970 PRO 512GB        | 3        | 0.62%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.62%   |
| Samsung SSD 870 EVO 500GB        | 3        | 0.62%   |
| Samsung SSD 860 QVO 1TB          | 3        | 0.62%   |
| Samsung SSD 860 EVO 1TB          | 3        | 0.62%   |
| Samsung SSD 850 EVO 500GB        | 3        | 0.62%   |
| Samsung SSD 850 EVO 1TB          | 3        | 0.62%   |
| Samsung SSD 840 Series 120GB     | 3        | 0.62%   |
| Kingston SV300S37A120G 120GB SSD | 3        | 0.62%   |
| Kingston SA400S37120G 120GB SSD  | 3        | 0.62%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 2        | 0.41%   |
| WDC WD60EZRZ-00RWYB1 6TB         | 2        | 0.41%   |
| WDC WD60EFRX-68L0BN1 6TB         | 2        | 0.41%   |
| WDC WD3200AAKS-75B3A0 320GB      | 2        | 0.41%   |
| WDC WD30EZRX-00D8PB0 3TB         | 2        | 0.41%   |
| WDC WD30EFRX-68AX9N0 3TB         | 2        | 0.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 2        | 0.41%   |
| WDC WD15EARX-00PASB0 1TB         | 2        | 0.41%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 2        | 0.41%   |
| WDC WD10EZEX-75WN4A0 1TB         | 2        | 0.41%   |
| Unknown SD/MMC/MS PRO 16GB       | 2        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 73       | 103    | 37.24%  |
| WDC                 | 66       | 89     | 33.67%  |
| Toshiba             | 22       | 28     | 11.22%  |
| Hitachi             | 17       | 23     | 8.67%   |
| Samsung Electronics | 7        | 10     | 3.57%   |
| Maxtor              | 5        | 6      | 2.55%   |
| Unknown             | 2        | 2      | 1.02%   |
| IBM/Hitachi         | 1        | 1      | 0.51%   |
| HGST                | 1        | 1      | 0.51%   |
| Fujitsu             | 1        | 1      | 0.51%   |
| External            | 1        | 1      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 45       | 60     | 26.79%  |
| Kingston            | 29       | 31     | 17.26%  |
| SanDisk             | 13       | 15     | 7.74%   |
| Crucial             | 13       | 14     | 7.74%   |
| China               | 12       | 15     | 7.14%   |
| A-DATA Technology   | 11       | 11     | 6.55%   |
| WDC                 | 8        | 9      | 4.76%   |
| GOODRAM             | 5        | 6      | 2.98%   |
| PNY                 | 4        | 5      | 2.38%   |
| SPCC                | 3        | 3      | 1.79%   |
| Intel               | 3        | 4      | 1.79%   |
| Transcend           | 2        | 2      | 1.19%   |
| Team                | 2        | 2      | 1.19%   |
| Mushkin             | 2        | 2      | 1.19%   |
| Apacer              | 2        | 2      | 1.19%   |
| WDC WDS1            | 1        | 1      | 0.6%    |
| WALRAM              | 1        | 1      | 0.6%    |
| Vaseky              | 1        | 1      | 0.6%    |
| Unknown             | 1        | 1      | 0.6%    |
| Rogueware           | 1        | 2      | 0.6%    |
| OCZ                 | 1        | 1      | 0.6%    |
| Micron Technology   | 1        | 1      | 0.6%    |
| KingSpec            | 1        | 1      | 0.6%    |
| KingFast            | 1        | 1      | 0.6%    |
| Intenso             | 1        | 1      | 0.6%    |
| Gigabyte Technology | 1        | 1      | 0.6%    |
| CT1000P3            | 1        | 1      | 0.6%    |
| Avant               | 1        | 1      | 0.6%    |
| Acer                | 1        | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 147      | 265    | 42%     |
| SSD     | 139      | 196    | 39.71%  |
| NVMe    | 59       | 76     | 16.86%  |
| Unknown | 4        | 6      | 1.14%   |
| MMC     | 1        | 1      | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 199      | 449    | 73.16%  |
| NVMe | 59       | 76     | 21.69%  |
| SAS  | 13       | 18     | 4.78%   |
| MMC  | 1        | 1      | 0.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 159      | 253    | 50.8%   |
| 0.51-1.0   | 85       | 117    | 27.16%  |
| 1.01-2.0   | 36       | 45     | 11.5%   |
| 2.01-3.0   | 12       | 15     | 3.83%   |
| 3.01-4.0   | 11       | 12     | 3.51%   |
| 4.01-10.0  | 9        | 18     | 2.88%   |
| 10.01-20.0 | 1        | 1      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 49       | 21.68%  |
| 251-500        | 44       | 19.47%  |
| 501-1000       | 32       | 14.16%  |
| 1001-2000      | 29       | 12.83%  |
| More than 3000 | 20       | 8.85%   |
| 2001-3000      | 20       | 8.85%   |
| 51-100         | 19       | 8.41%   |
| 1-20           | 7        | 3.1%    |
| 21-50          | 6        | 2.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 55       | 24.66%  |
| 101-250        | 37       | 16.59%  |
| 21-50          | 34       | 15.25%  |
| 251-500        | 26       | 11.66%  |
| 51-100         | 24       | 10.76%  |
| 501-1000       | 17       | 7.62%   |
| 1001-2000      | 16       | 7.17%   |
| More than 3000 | 7        | 3.14%   |
| 2001-3000      | 7        | 3.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| China SSD 512GB                 | 2        | 2      | 2.82%   |
| WDC WDS100T2B0A-00SM50 1TB SSD  | 1        | 1      | 1.41%   |
| WDC WD5003ABYX-01WERA1 500GB    | 1        | 1      | 1.41%   |
| WDC WD40EZRX-00SPEB0 4TB        | 1        | 1      | 1.41%   |
| WDC WD3200AAKS-00UU3A0 320GB    | 1        | 1      | 1.41%   |
| WDC WD3200AAJS-00B4A0 320GB     | 1        | 1      | 1.41%   |
| WDC WD2500AAJS-00B4A0 250GB     | 1        | 2      | 1.41%   |
| WDC WD20EZRX-00D8PB0 2TB        | 1        | 1      | 1.41%   |
| WDC WD20EARX-00PASB0 2TB        | 1        | 1      | 1.41%   |
| WDC WD20EARS-00J99B0 2TB        | 1        | 1      | 1.41%   |
| WDC WD1600AVVS-63L2B0 160GB     | 1        | 1      | 1.41%   |
| WDC WD15EADS-11P8B2 1TB         | 1        | 1      | 1.41%   |
| WDC WD10EZRZ-00HTKB0 1TB        | 1        | 1      | 1.41%   |
| WDC WD10EZEX-75WN4A0 1TB        | 1        | 1      | 1.41%   |
| WDC WD10EAVS-00D7B1 1TB         | 1        | 1      | 1.41%   |
| WDC WD10EADS-98M2B0 1TB         | 1        | 1      | 1.41%   |
| WDC WD10EADS-00M2B0 1TB         | 1        | 1      | 1.41%   |
| Toshiba MQ01ABF050 500GB        | 1        | 1      | 1.41%   |
| Toshiba MK7575GSX 752GB         | 1        | 1      | 1.41%   |
| Toshiba MK6465GSX 640GB         | 1        | 1      | 1.41%   |
| Toshiba MK1234GSX 120GB         | 1        | 1      | 1.41%   |
| Toshiba DT01ACA050 500GB        | 1        | 1      | 1.41%   |
| SPCC Solid State Disk 512GB     | 1        | 1      | 1.41%   |
| Seagate ST500LT012-9WS142 500GB | 1        | 1      | 1.41%   |
| Seagate ST500LM021-1KJ152 500GB | 1        | 1      | 1.41%   |
| Seagate ST380815AS 80GB         | 1        | 1      | 1.41%   |
| Seagate ST3750330NS 752GB       | 1        | 1      | 1.41%   |
| Seagate ST3500820AS 500GB       | 1        | 1      | 1.41%   |
| Seagate ST3500413AS 500GB       | 1        | 1      | 1.41%   |
| Seagate ST3360320AS 360GB       | 1        | 1      | 1.41%   |
| Seagate ST3320418AS 320GB       | 1        | 1      | 1.41%   |
| Seagate ST3320413CS 320GB       | 1        | 1      | 1.41%   |
| Seagate ST33000651NS 3TB        | 1        | 1      | 1.41%   |
| Seagate ST320LT020-9YG142 320GB | 1        | 1      | 1.41%   |
| Seagate ST320LT012-1DG14C 320GB | 1        | 2      | 1.41%   |
| Seagate ST31500341AS 1TB        | 1        | 1      | 1.41%   |
| Seagate ST31000524AS 1TB        | 1        | 1      | 1.41%   |
| Seagate ST250DM000-1BD141 250GB | 1        | 1      | 1.41%   |
| Seagate ST2000DM001-1ER164 2TB  | 1        | 1      | 1.41%   |
| Seagate ST1000VM002-1CT162 1TB  | 1        | 1      | 1.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 20     | 26.09%  |
| WDC                 | 16       | 17     | 23.19%  |
| Toshiba             | 5        | 5      | 7.25%   |
| Samsung Electronics | 5        | 8      | 7.25%   |
| Hitachi             | 5        | 6      | 7.25%   |
| Maxtor              | 4        | 4      | 5.8%    |
| Kingston            | 2        | 2      | 2.9%    |
| Crucial             | 2        | 2      | 2.9%    |
| China               | 2        | 2      | 2.9%    |
| A-DATA Technology   | 2        | 2      | 2.9%    |
| SPCC                | 1        | 1      | 1.45%   |
| Lexar               | 1        | 1      | 1.45%   |
| KingSpec            | 1        | 1      | 1.45%   |
| Intenso             | 1        | 1      | 1.45%   |
| IBM/Hitachi         | 1        | 1      | 1.45%   |
| HGST                | 1        | 1      | 1.45%   |
| GOODRAM             | 1        | 1      | 1.45%   |
| Fujitsu             | 1        | 1      | 1.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 20     | 35.29%  |
| WDC                 | 15       | 16     | 29.41%  |
| Toshiba             | 5        | 5      | 9.8%    |
| Hitachi             | 5        | 6      | 9.8%    |
| Maxtor              | 4        | 4      | 7.84%   |
| Samsung Electronics | 1        | 2      | 1.96%   |
| IBM/Hitachi         | 1        | 1      | 1.96%   |
| HGST                | 1        | 1      | 1.96%   |
| Fujitsu             | 1        | 1      | 1.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 48       | 56     | 73.85%  |
| SSD  | 16       | 19     | 24.62%  |
| NVMe | 1        | 1      | 1.54%   |

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
| Works    | 193      | 423    | 68.44%  |
| Malfunc  | 62       | 76     | 21.99%  |
| Detected | 24       | 41     | 8.51%   |
| Failed   | 3        | 4      | 1.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 143      | 46.58%  |
| AMD                         | 64       | 20.85%  |
| Samsung Electronics         | 22       | 7.17%   |
| ASMedia Technology          | 13       | 4.23%   |
| JMicron Technology          | 9        | 2.93%   |
| SanDisk                     | 8        | 2.61%   |
| Phison Electronics          | 8        | 2.61%   |
| Marvell Technology Group    | 8        | 2.61%   |
| Silicon Motion              | 6        | 1.95%   |
| Micron/Crucial Technology   | 5        | 1.63%   |
| Kingston Technology Company | 5        | 1.63%   |
| Nvidia                      | 4        | 1.3%    |
| VIA Technologies            | 3        | 0.98%   |
| MAXIO Technology (Hangzhou) | 3        | 0.98%   |
| ULi Electronics             | 2        | 0.65%   |
| ADATA Technology            | 2        | 0.65%   |
| Silicon Image               | 1        | 0.33%   |
| LSI Logic / Symbios Logic   | 1        | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28       | 7.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17       | 4.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 3.37%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 13       | 3.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 3.37%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 3.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 2.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10       | 2.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9        | 2.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 2.07%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 2.07%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 1.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 1.81%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 1.55%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 5        | 1.3%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.3%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 1.3%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.3%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 1.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5        | 1.3%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5        | 1.3%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 1.3%    |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.3%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4        | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.04%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4        | 1.04%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.04%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.04%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.04%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.04%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 3        | 0.78%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.78%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 180      | 58.63%  |
| NVMe | 57       | 18.57%  |
| IDE  | 57       | 18.57%  |
| RAID | 12       | 3.91%   |
| SCSI | 1        | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 146      | 67.28%  |
| AMD          | 70       | 32.26%  |
| CentaurHauls | 1        | 0.46%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz        | 6        | 2.76%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 5        | 2.3%    |
| AMD Ryzen 7 3700X 8-Core Processor      | 4        | 1.84%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 4        | 1.84%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 3        | 1.38%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 3        | 1.38%   |
| Intel Core i5-4690K CPU @ 3.50GHz       | 3        | 1.38%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 3        | 1.38%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz  | 3        | 1.38%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3        | 1.38%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 3        | 1.38%   |
| AMD Ryzen 5 1600X Six-Core Processor    | 3        | 1.38%   |
| Intel Pentium CPU G3240 @ 3.10GHz       | 2        | 0.92%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 2        | 0.92%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 2        | 0.92%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 2        | 0.92%   |
| Intel Core i7-5820K CPU @ 3.30GHz       | 2        | 0.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2        | 0.92%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 2        | 0.92%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2        | 0.92%   |
| Intel Core i5-6600K CPU @ 3.50GHz       | 2        | 0.92%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2        | 0.92%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 2        | 0.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2        | 0.92%   |
| Intel Core i5-3350P CPU @ 3.10GHz       | 2        | 0.92%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2        | 0.92%   |
| Intel Core i5 CPU 750 @ 2.67GHz         | 2        | 0.92%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 2        | 0.92%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 2        | 0.92%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 2        | 0.92%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz   | 2        | 0.92%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 2        | 0.92%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz  | 2        | 0.92%   |
| AMD Ryzen 9 7900X 12-Core Processor     | 2        | 0.92%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 2        | 0.92%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 2        | 0.92%   |
| AMD Phenom II X6 1090T Processor        | 2        | 0.92%   |
| AMD Phenom II X4 925 Processor          | 2        | 0.92%   |
| AMD Athlon II X4 630 Processor          | 2        | 0.92%   |
| AMD A4-3300 APU with Radeon HD Graphics | 2        | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 41       | 18.89%  |
| Intel Core i7           | 27       | 12.44%  |
| AMD Ryzen 5             | 22       | 10.14%  |
| Intel Core i3           | 16       | 7.37%   |
| AMD Ryzen 7             | 13       | 5.99%   |
| Other                   | 11       | 5.07%   |
| Intel Core 2 Duo        | 10       | 4.61%   |
| Intel Celeron           | 7        | 3.23%   |
| Intel Core 2 Quad       | 6        | 2.76%   |
| Intel Xeon              | 5        | 2.3%    |
| Intel Pentium           | 5        | 2.3%    |
| AMD Phenom II X4        | 5        | 2.3%    |
| Intel Pentium 4         | 4        | 1.84%   |
| Intel Core i9           | 3        | 1.38%   |
| AMD Ryzen 9             | 3        | 1.38%   |
| AMD Athlon II X4        | 3        | 1.38%   |
| AMD Athlon II X2        | 3        | 1.38%   |
| Intel Pentium Gold      | 2        | 0.92%   |
| Intel Pentium Dual-Core | 2        | 0.92%   |
| Intel Pentium D         | 2        | 0.92%   |
| AMD Sempron             | 2        | 0.92%   |
| AMD Ryzen 3             | 2        | 0.92%   |
| AMD Phenom II X6        | 2        | 0.92%   |
| AMD Phenom              | 2        | 0.92%   |
| AMD FX                  | 2        | 0.92%   |
| AMD Athlon              | 2        | 0.92%   |
| AMD A4                  | 2        | 0.92%   |
| Intel Pentium Dual      | 1        | 0.46%   |
| Intel Core M            | 1        | 0.46%   |
| Intel Core 2 Extreme    | 1        | 0.46%   |
| Intel Celeron D         | 1        | 0.46%   |
| Intel Atom              | 1        | 0.46%   |
| CentaurHauls VIA Esther | 1        | 0.46%   |
| AMD Ryzen Threadripper  | 1        | 0.46%   |
| AMD Ryzen 5 PRO         | 1        | 0.46%   |
| AMD E1                  | 1        | 0.46%   |
| AMD Athlon X4           | 1        | 0.46%   |
| AMD Athlon 64 X2        | 1        | 0.46%   |
| AMD A8                  | 1        | 0.46%   |
| AMD A10                 | 1        | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 84       | 38.71%  |
| 2      | 56       | 25.81%  |
| 6      | 35       | 16.13%  |
| 8      | 23       | 10.6%   |
| 1      | 9        | 4.15%   |
| 12     | 6        | 2.76%   |
| 10     | 2        | 0.92%   |
| 16     | 1        | 0.46%   |
| 3      | 1        | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 216      | 99.54%  |
| 2      | 1        | 0.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 111      | 50.92%  |
| 1      | 107      | 49.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 214      | 98.62%  |
| 32-bit         | 3        | 1.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 13.76%  |
| 0x306c3    | 23       | 10.55%  |
| 0x206a7    | 15       | 6.88%   |
| 0x306a9    | 13       | 5.96%   |
| 0x1067a    | 9        | 4.13%   |
| 0x08701021 | 7        | 3.21%   |
| 0x906ed    | 6        | 2.75%   |
| 0x0800820d | 6        | 2.75%   |
| 0xa0671    | 5        | 2.29%   |
| 0xa0653    | 5        | 2.29%   |
| 0x506e3    | 5        | 2.29%   |
| 0x106e5    | 4        | 1.83%   |
| 0x010000db | 4        | 1.83%   |
| 0x010000c8 | 4        | 1.83%   |
| 0x906ea    | 3        | 1.38%   |
| 0x6fb      | 3        | 1.38%   |
| 0x0a601203 | 3        | 1.38%   |
| 0x08108109 | 3        | 1.38%   |
| 0x01000083 | 3        | 1.38%   |
| 0x906e9    | 2        | 0.92%   |
| 0x706a1    | 2        | 0.92%   |
| 0x6fd      | 2        | 0.92%   |
| 0x506c9    | 2        | 0.92%   |
| 0x306f2    | 2        | 0.92%   |
| 0x20655    | 2        | 0.92%   |
| 0x10677    | 2        | 0.92%   |
| 0x0a50000d | 2        | 0.92%   |
| 0x0a20120a | 2        | 0.92%   |
| 0x08600106 | 2        | 0.92%   |
| 0x08001138 | 2        | 0.92%   |
| 0x08001137 | 2        | 0.92%   |
| 0x010000dc | 2        | 0.92%   |
| 0xf65      | 1        | 0.46%   |
| 0xf64      | 1        | 0.46%   |
| 0xf4a      | 1        | 0.46%   |
| 0xf49      | 1        | 0.46%   |
| 0xf47      | 1        | 0.46%   |
| 0xf34      | 1        | 0.46%   |
| 0xf29      | 1        | 0.46%   |
| 0xb0671    | 1        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 29       | 13.36%  |
| SandyBridge      | 17       | 7.83%   |
| K10              | 16       | 7.37%   |
| Penryn           | 15       | 6.91%   |
| KabyLake         | 15       | 6.91%   |
| IvyBridge        | 15       | 6.91%   |
| Zen+             | 12       | 5.53%   |
| Zen 2            | 11       | 5.07%   |
| Unknown          | 10       | 4.61%   |
| Zen 3            | 8        | 3.69%   |
| Zen              | 7        | 3.23%   |
| Skylake          | 7        | 3.23%   |
| NetBurst         | 7        | 3.23%   |
| Nehalem          | 6        | 2.76%   |
| CometLake        | 6        | 2.76%   |
| Core             | 5        | 2.3%    |
| Icelake          | 4        | 1.84%   |
| Alderlake Hybrid | 4        | 1.84%   |
| Westmere         | 3        | 1.38%   |
| K8 Hammer        | 3        | 1.38%   |
| Goldmont plus    | 3        | 1.38%   |
| Steamroller      | 2        | 0.92%   |
| K10 Llano        | 2        | 0.92%   |
| Goldmont         | 2        | 0.92%   |
| Tremont          | 1        | 0.46%   |
| Silvermont       | 1        | 0.46%   |
| Piledriver       | 1        | 0.46%   |
| Jaguar           | 1        | 0.46%   |
| Excavator        | 1        | 0.46%   |
| Bulldozer        | 1        | 0.46%   |
| Broadwell        | 1        | 0.46%   |
| Bonnell          | 1        | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 93       | 38.75%  |
| Intel            | 76       | 31.67%  |
| AMD              | 70       | 29.17%  |
| VIA Technologies | 1        | 0.42%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 3.66%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 3.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 3.25%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 2.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 2.44%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 2.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 2.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 2.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.03%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.63%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 1.63%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.63%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 1.63%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.63%   |
| AMD Raphael                                                                 | 4        | 1.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 1.63%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.22%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 3        | 1.22%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3        | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 1.22%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 1.22%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                           | 3        | 1.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.22%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 1.22%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.22%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 3        | 1.22%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.22%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.81%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 2        | 0.81%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.81%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.81%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 2        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.81%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.81%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.81%   |
| Nvidia GK107GL [Quadro K600]                                                | 2        | 0.81%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.81%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 0.81%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 2        | 0.81%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 86       | 38.91%  |
| 1 x AMD        | 62       | 28.05%  |
| 1 x Intel      | 60       | 27.15%  |
| AMD + Nvidia   | 5        | 2.26%   |
| Intel + AMD    | 3        | 1.36%   |
| Intel + Nvidia | 2        | 0.9%    |
| 3 x AMD        | 1        | 0.45%   |
| 2 x AMD        | 1        | 0.45%   |
| 1 x VIA        | 1        | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 152      | 69.72%  |
| Proprietary | 57       | 26.15%  |
| Unknown     | 9        | 4.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 78       | 35.29%  |
| 1.01-2.0   | 36       | 16.29%  |
| 0.51-1.0   | 28       | 12.67%  |
| 3.01-4.0   | 23       | 10.41%  |
| 0.01-0.5   | 22       | 9.95%   |
| 7.01-8.0   | 19       | 8.6%    |
| 8.01-16.0  | 7        | 3.17%   |
| 5.01-6.0   | 4        | 1.81%   |
| 2.01-3.0   | 4        | 1.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 38       | 16.45%  |
| Dell                 | 24       | 10.39%  |
| Goldstar             | 23       | 9.96%   |
| Acer                 | 21       | 9.09%   |
| Hewlett-Packard      | 12       | 5.19%   |
| BenQ                 | 10       | 4.33%   |
| Ancor Communications | 10       | 4.33%   |
| AOC                  | 9        | 3.9%    |
| Philips              | 8        | 3.46%   |
| ViewSonic            | 7        | 3.03%   |
| Sony                 | 6        | 2.6%    |
| ASUSTek Computer     | 6        | 2.6%    |
| Iiyama               | 5        | 2.16%   |
| Fujitsu Siemens      | 5        | 2.16%   |
| Lenovo               | 4        | 1.73%   |
| Eizo                 | 4        | 1.73%   |
| Vestel Elektronik    | 3        | 1.3%    |
| MSI                  | 3        | 1.3%    |
| Medion               | 3        | 1.3%    |
| Vizio                | 2        | 0.87%   |
| Sceptre Tech         | 2        | 0.87%   |
| Gigabyte Technology  | 2        | 0.87%   |
| Yeyian               | 1        | 0.43%   |
| Xiaomi               | 1        | 0.43%   |
| Videoseven           | 1        | 0.43%   |
| Toshiba              | 1        | 0.43%   |
| SANYO                | 1        | 0.43%   |
| Sangyo               | 1        | 0.43%   |
| SAC                  | 1        | 0.43%   |
| RTK                  | 1        | 0.43%   |
| RIS                  | 1        | 0.43%   |
| Panasonic            | 1        | 0.43%   |
| NECCI                | 1        | 0.43%   |
| NEC Computers        | 1        | 0.43%   |
| MiTAC                | 1        | 0.43%   |
| LG Electronics       | 1        | 0.43%   |
| JRY                  | 1        | 0.43%   |
| IBM                  | 1        | 0.43%   |
| HYO                  | 1        | 0.43%   |
| Hitachi              | 1        | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 6        | 2.49%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                     | 3        | 1.24%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch            | 2        | 0.83%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                   | 2        | 0.83%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch    | 2        | 0.83%   |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                      | 2        | 0.83%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                 | 2        | 0.83%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                | 2        | 0.83%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                | 2        | 0.83%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch     | 2        | 0.83%   |
| Dell E2417H DELA0E2 1920x1080 527x296mm 23.8-inch                    | 2        | 0.83%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                   | 2        | 0.83%   |
| Yeyian YMG-4K27-01 YEY2700 3840x2160 600x330mm 27.0-inch             | 1        | 0.41%   |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                    | 1        | 0.41%   |
| Vizio E550i-B2 VIZ1004 1920x1080 477x268mm 21.5-inch                 | 1        | 0.41%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                   | 1        | 0.41%   |
| ViewSonic XG2705 VSC0E39 1920x1080 600x340mm 27.2-inch               | 1        | 0.41%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch               | 1        | 0.41%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch        | 1        | 0.41%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch             | 1        | 0.41%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch           | 1        | 0.41%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch              | 1        | 0.41%   |
| Toshiba TSB-TV TSB0206 1360x768 930x520mm 41.9-inch                  | 1        | 0.41%   |
| Sony TV SNY0801 1360x768                                             | 1        | 0.41%   |
| Sony TV *00 SNY7105 3840x2160 1218x685mm 55.0-inch                   | 1        | 0.41%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                 | 1        | 0.41%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                   | 1        | 0.41%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch       | 1        | 0.41%   |
| Sceptre Tech E225W-1920 SPT08D5 1920x1080 443x249mm 20.0-inch        | 1        | 0.41%   |
| SANYO LED MONITOR SAN2213 1600x900 477x268mm 21.5-inch               | 1        | 0.41%   |
| Sangyo LCD Monitor M27A3 1920x1080                                   | 1        | 0.41%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch    | 1        | 0.41%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch    | 1        | 0.41%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1        | 0.41%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                     | 1        | 0.41%   |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch | 1        | 0.41%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch | 1        | 0.41%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch | 1        | 0.41%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch | 1        | 0.41%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 1        | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 104      | 45.61%  |
| 3840x2160 (4K)     | 21       | 9.21%   |
| 2560x1440 (QHD)    | 20       | 8.77%   |
| 1280x1024 (SXGA)   | 18       | 7.89%   |
| 1680x1050 (WSXGA+) | 15       | 6.58%   |
| 1366x768 (WXGA)    | 9        | 3.95%   |
| 1600x1200          | 7        | 3.07%   |
| 1440x900 (WXGA+)   | 7        | 3.07%   |
| 1600x900 (HD+)     | 6        | 2.63%   |
| 3440x1440          | 3        | 1.32%   |
| 1920x1200 (WUXGA)  | 3        | 1.32%   |
| 1360x768           | 3        | 1.32%   |
| 2560x1080          | 2        | 0.88%   |
| 1280x720 (HD)      | 2        | 0.88%   |
| 1024x768 (XGA)     | 2        | 0.88%   |
| Unknown            | 2        | 0.88%   |
| 3840x1080          | 1        | 0.44%   |
| 2560x1600          | 1        | 0.44%   |
| 2048x1536          | 1        | 0.44%   |
| 1920x1440          | 1        | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 33       | 14.29%  |
| 23      | 32       | 13.85%  |
| 21      | 31       | 13.42%  |
| 24      | 26       | 11.26%  |
| 31      | 16       | 6.93%   |
| 22      | 13       | 5.63%   |
| 19      | 13       | 5.63%   |
| 18      | 11       | 4.76%   |
| 17      | 9        | 3.9%    |
| Unknown | 7        | 3.03%   |
| 20      | 6        | 2.6%    |
| 84      | 5        | 2.16%   |
| 65      | 5        | 2.16%   |
| 34      | 5        | 2.16%   |
| 15      | 4        | 1.73%   |
| 54      | 3        | 1.3%    |
| 25      | 2        | 0.87%   |
| 74      | 1        | 0.43%   |
| 72      | 1        | 0.43%   |
| 61      | 1        | 0.43%   |
| 52      | 1        | 0.43%   |
| 42      | 1        | 0.43%   |
| 40      | 1        | 0.43%   |
| 32      | 1        | 0.43%   |
| 28      | 1        | 0.43%   |
| 26      | 1        | 0.43%   |
| 16      | 1        | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 85       | 37.78%  |
| 401-500     | 64       | 28.44%  |
| 601-700     | 20       | 8.89%   |
| 351-400     | 12       | 5.33%   |
| 301-350     | 12       | 5.33%   |
| 1001-1500   | 10       | 4.44%   |
| 1501-2000   | 7        | 3.11%   |
| Unknown     | 7        | 3.11%   |
| 701-800     | 6        | 2.67%   |
| 801-900     | 1        | 0.44%   |
| 901-1000    | 1        | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 153      | 69.55%  |
| 16/10   | 27       | 12.27%  |
| 5/4     | 18       | 8.18%   |
| 4/3     | 10       | 4.55%   |
| Unknown | 6        | 2.73%   |
| 21/9    | 5        | 2.27%   |
| 3/2     | 1        | 0.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 88       | 39.11%  |
| 301-350        | 33       | 14.67%  |
| 151-200        | 30       | 13.33%  |
| 351-500        | 23       | 10.22%  |
| More than 1000 | 16       | 7.11%   |
| 141-150        | 14       | 6.22%   |
| 251-300        | 7        | 3.11%   |
| Unknown        | 7        | 3.11%   |
| 101-110        | 2        | 0.89%   |
| 501-1000       | 2        | 0.89%   |
| 121-130        | 1        | 0.44%   |
| 111-120        | 1        | 0.44%   |
| 91-100         | 1        | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 149      | 67.73%  |
| 101-120 | 42       | 19.09%  |
| 1-50    | 12       | 5.45%   |
| 121-160 | 7        | 3.18%   |
| Unknown | 7        | 3.18%   |
| 161-240 | 3        | 1.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 181      | 82.65%  |
| 2     | 31       | 14.16%  |
| 0     | 5        | 2.28%   |
| 3     | 2        | 0.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 138      | 43.53%  |
| Intel                           | 87       | 27.44%  |
| Qualcomm Atheros                | 18       | 5.68%   |
| TP-Link                         | 11       | 3.47%   |
| Ralink Technology               | 8        | 2.52%   |
| MediaTek                        | 8        | 2.52%   |
| Broadcom                        | 8        | 2.52%   |
| Ralink                          | 5        | 1.58%   |
| Broadcom Limited                | 4        | 1.26%   |
| Nvidia                          | 3        | 0.95%   |
| VIA Technologies                | 2        | 0.63%   |
| Samsung Electronics             | 2        | 0.63%   |
| Qualcomm Atheros Communications | 2        | 0.63%   |
| OPPO Electronics                | 2        | 0.63%   |
| Microsoft                       | 2        | 0.63%   |
| Marvell Technology Group        | 2        | 0.63%   |
| Linksys                         | 2        | 0.63%   |
| D-Link System                   | 2        | 0.63%   |
| Xiaomi                          | 1        | 0.32%   |
| U-Blox                          | 1        | 0.32%   |
| NetGear                         | 1        | 0.32%   |
| Mercucys                        | 1        | 0.32%   |
| JMicron Technology              | 1        | 0.32%   |
| IMC Networks                    | 1        | 0.32%   |
| Edimax Technology               | 1        | 0.32%   |
| D-Link                          | 1        | 0.32%   |
| AVM                             | 1        | 0.32%   |
| ASUSTek Computer                | 1        | 0.32%   |
| Aquantia                        | 1        | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 106      | 29.94%  |
| Intel Ethernet Controller I225-V                                  | 11       | 3.11%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 2.54%   |
| Intel I211 Gigabit Network Connection                             | 8        | 2.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 1.98%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 1.98%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7        | 1.98%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 1.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5        | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 1.41%   |
| Ralink MT7601U Wireless Adapter                                   | 5        | 1.41%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 1.41%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.41%   |
| Realtek 802.11ac NIC                                              | 4        | 1.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4        | 1.13%   |
| Intel Wireless-AC 9260                                            | 4        | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 1.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 0.85%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 3        | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.85%   |
| Nvidia MCP61 Ethernet                                             | 3        | 0.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 0.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.85%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.56%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.56%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.56%   |
| OPPO RMX2027                                                      | 2        | 0.56%   |
| Intel Wireless 8260                                               | 2        | 0.56%   |
| Intel Wireless 7260                                               | 2        | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 31       | 26.72%  |
| Intel                           | 25       | 21.55%  |
| TP-Link                         | 11       | 9.48%   |
| Qualcomm Atheros                | 9        | 7.76%   |
| Ralink Technology               | 8        | 6.9%    |
| MediaTek                        | 8        | 6.9%    |
| Ralink                          | 5        | 4.31%   |
| Broadcom                        | 4        | 3.45%   |
| Qualcomm Atheros Communications | 2        | 1.72%   |
| Microsoft                       | 2        | 1.72%   |
| Linksys                         | 2        | 1.72%   |
| NetGear                         | 1        | 0.86%   |
| Mercucys                        | 1        | 0.86%   |
| IMC Networks                    | 1        | 0.86%   |
| Edimax Technology               | 1        | 0.86%   |
| D-Link System                   | 1        | 0.86%   |
| D-Link                          | 1        | 0.86%   |
| Broadcom Limited                | 1        | 0.86%   |
| AVM                             | 1        | 0.86%   |
| ASUSTek Computer                | 1        | 0.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 5        | 4.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 5        | 4.27%   |
| Ralink MT7601U Wireless Adapter                                                               | 5        | 4.27%   |
| Intel Wi-Fi 6 AX200                                                                           | 5        | 4.27%   |
| Realtek 802.11ac NIC                                                                          | 4        | 3.42%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 4        | 3.42%   |
| Intel Wireless-AC 9260                                                                        | 4        | 3.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 4        | 3.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 3        | 2.56%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 3        | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 2.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 3        | 2.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 3        | 2.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 3        | 2.56%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 1.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 1.71%   |
| Intel Wireless 8260                                                                           | 2        | 1.71%   |
| Intel Wireless 7260                                                                           | 2        | 1.71%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 0.85%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                         | 1        | 0.85%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.85%   |
| TP-Link 802.11ac NIC                                                                          | 1        | 0.85%   |
| TP-Link 802.11 NIC                                                                            | 1        | 0.85%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 1        | 0.85%   |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller                                   | 1        | 0.85%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 0.85%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 0.85%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1        | 0.85%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 0.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 0.85%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.85%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1        | 0.85%   |
| Realtek 802.11ac WLAN Adapter                                                                 | 1        | 0.85%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.85%   |
| Ralink RT3572 Wireless Adapter                                                                | 1        | 0.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1        | 0.85%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                                   | 1        | 0.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 124      | 53.91%  |
| Intel                    | 75       | 32.61%  |
| Qualcomm Atheros         | 9        | 3.91%   |
| Broadcom                 | 4        | 1.74%   |
| Nvidia                   | 3        | 1.3%    |
| Broadcom Limited         | 3        | 1.3%    |
| VIA Technologies         | 2        | 0.87%   |
| Samsung Electronics      | 2        | 0.87%   |
| OPPO Electronics         | 2        | 0.87%   |
| Marvell Technology Group | 2        | 0.87%   |
| Xiaomi                   | 1        | 0.43%   |
| JMicron Technology       | 1        | 0.43%   |
| D-Link System            | 1        | 0.43%   |
| Aquantia                 | 1        | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 106      | 44.92%  |
| Intel Ethernet Controller I225-V                                  | 11       | 4.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 4.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 3.81%   |
| Intel I211 Gigabit Network Connection                             | 8        | 3.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 2.97%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.97%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7        | 2.97%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 2.54%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 2.12%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.27%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.27%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.27%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 1.27%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.27%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.85%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.85%   |
| OPPO RMX2027                                                      | 2        | 0.85%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.85%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.85%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.85%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.85%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.42%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.42%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.42%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.42%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.42%   |
| Intel Ethernet Connection I218-V                                  | 1        | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.42%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.42%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 216      | 67.5%   |
| WiFi     | 103      | 32.19%  |
| Modem    | 1        | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 155      | 69.82%  |
| WiFi     | 67       | 30.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 145      | 66.82%  |
| 2     | 64       | 29.49%  |
| 3     | 8        | 3.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 173      | 79%     |
| Yes  | 46       | 21%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 22       | 36.67%  |
| Cambridge Silicon Radio         | 11       | 18.33%  |
| Realtek Semiconductor           | 6        | 10%     |
| MediaTek                        | 6        | 10%     |
| Broadcom                        | 4        | 6.67%   |
| TP-Link                         | 3        | 5%      |
| ASUSTek Computer                | 3        | 5%      |
| Foxconn / Hon Hai               | 2        | 3.33%   |
| Qualcomm Atheros Communications | 1        | 1.67%   |
| Lite-On Technology              | 1        | 1.67%   |
| Apple                           | 1        | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 11       | 18.33%  |
| Realtek Bluetooth Radio                               | 6        | 10%     |
| MediaTek Wireless_Device                              | 6        | 10%     |
| Intel Bluetooth wireless interface                    | 5        | 8.33%   |
| Intel AX200 Bluetooth                                 | 5        | 8.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 4        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 6.67%   |
| TP-Link UB500 Adapter                                 | 3        | 5%      |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 5%      |
| Intel AX210 Bluetooth                                 | 2        | 3.33%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 3.33%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1        | 1.67%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 1.67%   |
| Intel Bluetooth Device                                | 1        | 1.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 1.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 1.67%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.67%   |
| ASUS BCM20702A0                                       | 1        | 1.67%   |
| Apple Bluetooth Host Controller                       | 1        | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 140      | 37.53%  |
| AMD                     | 90       | 24.13%  |
| Nvidia                  | 87       | 23.32%  |
| C-Media Electronics     | 11       | 2.95%   |
| Creative Labs           | 10       | 2.68%   |
| VIA Technologies        | 3        | 0.8%    |
| Texas Instruments       | 3        | 0.8%    |
| JMTek                   | 3        | 0.8%    |
| ROCCAT                  | 2        | 0.54%   |
| Kingston Technology     | 2        | 0.54%   |
| Focusrite-Novation      | 2        | 0.54%   |
| ULi Electronics         | 1        | 0.27%   |
| TerraTec Electronic     | 1        | 0.27%   |
| Tenx Technology         | 1        | 0.27%   |
| Setek Elektronik        | 1        | 0.27%   |
| Schiit Audio            | 1        | 0.27%   |
| Razer USA               | 1        | 0.27%   |
| Microsoft               | 1        | 0.27%   |
| M-Audio                 | 1        | 0.27%   |
| Logitech                | 1        | 0.27%   |
| Jieli Technology        | 1        | 0.27%   |
| GYROCOM C&C             | 1        | 0.27%   |
| GN Netcom               | 1        | 0.27%   |
| Giga-Byte Technology    | 1        | 0.27%   |
| Generalplus Technology  | 1        | 0.27%   |
| Fortemedia              | 1        | 0.27%   |
| Ensoniq                 | 1        | 0.27%   |
| Emotiva                 | 1        | 0.27%   |
| Digidesign              | 1        | 0.27%   |
| Cambridge Silicon Radio | 1        | 0.27%   |
| BEHRINGER International | 1        | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 17       | 3.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 17       | 3.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 16       | 3.76%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 16       | 3.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 14       | 3.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 14       | 3.29%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 12       | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 11       | 2.58%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 10       | 2.35%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 9        | 2.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 9        | 2.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 8        | 1.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 7        | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                                      | 7        | 1.64%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 7        | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 7        | 1.64%   |
| Intel 200 Series PCH HD Audio                                                                   | 7        | 1.64%   |
| Nvidia High Definition Audio Controller                                                         | 6        | 1.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 6        | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 6        | 1.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 6        | 1.41%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 6        | 1.41%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 5        | 1.17%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 5        | 1.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 5        | 1.17%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 5        | 1.17%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 5        | 1.17%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 5        | 1.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 5        | 1.17%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 5        | 1.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 5        | 1.17%   |
| AMD FCH Azalia Controller                                                                       | 5        | 1.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 5        | 1.17%   |
| Nvidia GK106 HDMI Audio Controller                                                              | 4        | 0.94%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 4        | 0.94%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 4        | 0.94%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 4        | 0.94%   |
| Nvidia TU104 HD Audio Controller                                                                | 3        | 0.7%    |
| Nvidia MCP61 High Definition Audio                                                              | 3        | 0.7%    |
| Nvidia GK110 High Definition Audio Controller                                                   | 3        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 43       | 17.84%  |
| Kingston                                | 37       | 15.35%  |
| Corsair                                 | 34       | 14.11%  |
| Samsung Electronics                     | 22       | 9.13%   |
| G.Skill                                 | 21       | 8.71%   |
| SK hynix                                | 15       | 6.22%   |
| Crucial                                 | 13       | 5.39%   |
| A-DATA Technology                       | 9        | 3.73%   |
| Ramaxel Technology                      | 6        | 2.49%   |
| Micron Technology                       | 6        | 2.49%   |
| Nanya Technology                        | 5        | 2.07%   |
| Unknown (ABCD)                          | 3        | 1.24%   |
| Patriot                                 | 3        | 1.24%   |
| Transcend                               | 2        | 0.83%   |
| Elpida                                  | 2        | 0.83%   |
| Apacer                                  | 2        | 0.83%   |
| Unknown                                 | 2        | 0.83%   |
| Unknown (AB)                            | 1        | 0.41%   |
| Unknown (0x0E9D)                        | 1        | 0.41%   |
| Unifosa                                 | 1        | 0.41%   |
| Timetec                                 | 1        | 0.41%   |
| Smart                                   | 1        | 0.41%   |
| Silicon Power Computer & Communications | 1        | 0.41%   |
| RZX                                     | 1        | 0.41%   |
| Qumo                                    | 1        | 0.41%   |
| PNY                                     | 1        | 0.41%   |
| Patriot Memory (PDP Systems)            | 1        | 0.41%   |
| OCZ                                     | 1        | 0.41%   |
| Lexar Co Limited                        | 1        | 0.41%   |
| Golden Empire                           | 1        | 0.41%   |
| CSX                                     | 1        | 0.41%   |
| Axiom                                   | 1        | 0.41%   |
| Avant                                   | 1        | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 7        | 2.63%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 3        | 1.13%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                        | 3        | 1.13%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 3        | 1.13%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 3        | 1.13%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 3        | 1.13%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 3        | 1.13%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                       | 2        | 0.75%   |
| Unknown RAM Module 2GB DIMM 667MT/s                            | 2        | 0.75%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 2        | 0.75%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 2        | 0.75%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                     | 2        | 0.75%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s          | 2        | 0.75%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 0.75%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 0.75%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM 1333MT/s                | 2        | 0.75%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 2        | 0.75%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s                 | 2        | 0.75%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s             | 2        | 0.75%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 2        | 0.75%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2667MT/s          | 2        | 0.75%   |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8192MB DIMM DDR4 3600MT/s     | 2        | 0.75%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s           | 2        | 0.75%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 2        | 0.75%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s          | 2        | 0.75%   |
| Unknown                                                        | 2        | 0.75%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.38%   |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s                   | 1        | 0.38%   |
| Unknown RAM Module 512MB DIMM SDRAM                            | 1        | 0.38%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                      | 1        | 0.38%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                      | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                       | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR2 533MT/s                       | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM 667MT/s                            | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM                                    | 1        | 0.38%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 1        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 84       | 38.36%  |
| DDR3    | 73       | 33.33%  |
| DDR2    | 17       | 7.76%   |
| Unknown | 17       | 7.76%   |
| SDRAM   | 13       | 5.94%   |
| DDR     | 6        | 2.74%   |
| DDR5    | 5        | 2.28%   |
| LPDDR4  | 3        | 1.37%   |
| LPDDR3  | 1        | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 197      | 92.06%  |
| SODIMM | 17       | 7.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 71       | 30.47%  |
| 4096  | 64       | 27.47%  |
| 2048  | 39       | 16.74%  |
| 16384 | 33       | 14.16%  |
| 1024  | 15       | 6.44%   |
| 32768 | 7        | 3%      |
| 512   | 3        | 1.29%   |
| 256   | 1        | 0.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 37       | 15.48%  |
| 1333    | 35       | 14.64%  |
| 3200    | 20       | 8.37%   |
| 3600    | 16       | 6.69%   |
| 2400    | 12       | 5.02%   |
| 2667    | 10       | 4.18%   |
| 800     | 10       | 4.18%   |
| 667     | 10       | 4.18%   |
| 2133    | 8        | 3.35%   |
| Unknown | 8        | 3.35%   |
| 3000    | 7        | 2.93%   |
| 2933    | 5        | 2.09%   |
| 1800    | 5        | 2.09%   |
| 1867    | 4        | 1.67%   |
| 333     | 4        | 1.67%   |
| 6000    | 3        | 1.26%   |
| 3533    | 3        | 1.26%   |
| 3266    | 3        | 1.26%   |
| 2666    | 3        | 1.26%   |
| 2048    | 3        | 1.26%   |
| 1866    | 3        | 1.26%   |
| 533     | 3        | 1.26%   |
| 400     | 3        | 1.26%   |
| 49926   | 2        | 0.84%   |
| 3466    | 2        | 0.84%   |
| 3400    | 2        | 0.84%   |
| 2800    | 2        | 0.84%   |
| 1639    | 2        | 0.84%   |
| 1067    | 2        | 0.84%   |
| 5800    | 1        | 0.42%   |
| 4800    | 1        | 0.42%   |
| 4133    | 1        | 0.42%   |
| 3866    | 1        | 0.42%   |
| 3733    | 1        | 0.42%   |
| 3100    | 1        | 0.42%   |
| 2934    | 1        | 0.42%   |
| 2200    | 1        | 0.42%   |
| 2000    | 1        | 0.42%   |
| 1632    | 1        | 0.42%   |
| 1066    | 1        | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Canon                 | 4        | 33.33%  |
| Brother Industries    | 3        | 25%     |
| Hewlett-Packard       | 2        | 16.67%  |
| Seiko Epson           | 1        | 8.33%   |
| Lexmark International | 1        | 8.33%   |
| Konica Minolta        | 1        | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon MF641C                  | 2        | 16.67%  |
| Seiko Epson L380 Series       | 1        | 8.33%   |
| Lexmark International CS417dn | 1        | 8.33%   |
| Konica Minolta 206            | 1        | 8.33%   |
| HP ENVY 4500 series           | 1        | 8.33%   |
| HP Deskjet 1510               | 1        | 8.33%   |
| Canon PIXMA MG5600 Series     | 1        | 8.33%   |
| Canon MG5700 series           | 1        | 8.33%   |
| Brother MFC-7340              | 1        | 8.33%   |
| Brother HL-L2350DW series     | 1        | 8.33%   |
| Brother DCP-L2540DW           | 1        | 8.33%   |

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
| Logitech                      | 12       | 32.43%  |
| Microsoft                     | 6        | 16.22%  |
| Sunplus Innovation Technology | 4        | 10.81%  |
| Microdia                      | 2        | 5.41%   |
| Generalplus Technology        | 2        | 5.41%   |
| Chicony Electronics           | 2        | 5.41%   |
| Z-Star Microelectronics       | 1        | 2.7%    |
| Trust                         | 1        | 2.7%    |
| Sunplus Technology            | 1        | 2.7%    |
| Sonix Technology              | 1        | 2.7%    |
| Pixart Imaging                | 1        | 2.7%    |
| Huawei Technologies           | 1        | 2.7%    |
| Hewlett-Packard               | 1        | 2.7%    |
| Aveo Technology               | 1        | 2.7%    |
| Arkmicro Technologies         | 1        | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                               | 4        | 10.81%  |
| Sunplus Full HD webcam                                  | 3        | 8.11%   |
| Logitech Webcam C270                                    | 3        | 8.11%   |
| Logitech Webcam C930e                                   | 2        | 5.41%   |
| Logitech Webcam C200                                    | 2        | 5.41%   |
| Z-Star Traveler TV 6500 SF Dia-scanner                  | 1        | 2.7%    |
| Trust Widescreen 3MP Webcam                             | 1        | 2.7%    |
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode) | 1        | 2.7%    |
| Sunplus Aukey-PC-LM1E Camera                            | 1        | 2.7%    |
| Sonix USB Camera                                        | 1        | 2.7%    |
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 1        | 2.7%    |
| Microsoft LifeCam VX-800                                | 1        | 2.7%    |
| Microsoft LifeCam VX-500 [1357]                         | 1        | 2.7%    |
| Microdia USB 2.0 Camera                                 | 1        | 2.7%    |
| Microdia Camera                                         | 1        | 2.7%    |
| Logitech Webcam Pro 9000                                | 1        | 2.7%    |
| Logitech Webcam C310                                    | 1        | 2.7%    |
| Logitech Webcam C110                                    | 1        | 2.7%    |
| Logitech HD Webcam C615                                 | 1        | 2.7%    |
| Logitech B525 HD Webcam                                 | 1        | 2.7%    |
| Huawei UVC Camera                                       | 1        | 2.7%    |
| HP Webcam HD 2300                                       | 1        | 2.7%    |
| Generalplus GENERAL WEBCAM                              | 1        | 2.7%    |
| Generalplus 808 Camera #9 (web-cam mode)                | 1        | 2.7%    |
| Chicony HP Prem AF Webcam KQ245AA                       | 1        | 2.7%    |
| Chicony HD Webcam                                       | 1        | 2.7%    |
| Aveo Camera                                             | 1        | 2.7%    |
| Arkmicro USB2.0 PC CAMERA                               | 1        | 2.7%    |

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
| 0     | 183      | 84.33%  |
| 1     | 30       | 13.82%  |
| 3     | 2        | 0.92%   |
| 2     | 2        | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 15       | 40.54%  |
| Net/wireless             | 10       | 27.03%  |
| Unassigned class         | 3        | 8.11%   |
| Communication controller | 3        | 8.11%   |
| Network                  | 1        | 2.7%    |
| Multimedia controller    | 1        | 2.7%    |
| Fingerprint reader       | 1        | 2.7%    |
| Dvb card                 | 1        | 2.7%    |
| Card reader              | 1        | 2.7%    |
| Camera                   | 1        | 2.7%    |

