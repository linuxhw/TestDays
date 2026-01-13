Linux in Costa Rica - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Costa Rica.

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

Total: 169

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | PRO H510M-B                 | [8036e7a91b](https://linux-hardware.org/?probe=8036e7a91b) | Dec 31, 2025 |
| ASUSTek       | PRIME A520M-K               | [91d580213a](https://linux-hardware.org/?probe=91d580213a) | Dec 18, 2025 |
| TianBei       | N1 PRO                      | [44537b7424](https://linux-hardware.org/?probe=44537b7424) | Dec 13, 2025 |
| Unknown       | Unknown                     | [5a520c1aaa](https://linux-hardware.org/?probe=5a520c1aaa) | Dec 09, 2025 |
| B450MV1       | 1006                        | [6b11d3e030](https://linux-hardware.org/?probe=6b11d3e030) | Dec 02, 2025 |
| MSI           | MAG X870 TOMAHAWK WIFI      | [19d101d68b](https://linux-hardware.org/?probe=19d101d68b) | Nov 24, 2025 |
| TianBei       | N1 PRO                      | [6d2cd6d361](https://linux-hardware.org/?probe=6d2cd6d361) | Nov 13, 2025 |
| SZQFTX        | Unknown                     | [29a7664a9b](https://linux-hardware.org/?probe=29a7664a9b) | Nov 04, 2025 |
| HP            | 212B                        | [16f18f460f](https://linux-hardware.org/?probe=16f18f460f) | Oct 28, 2025 |
| Gigabyte      | H510M H                     | [edd28fd73a](https://linux-hardware.org/?probe=edd28fd73a) | Oct 12, 2025 |
| Gigabyte      | X870E AORUS PRO             | [5f7d65a7f3](https://linux-hardware.org/?probe=5f7d65a7f3) | Oct 09, 2025 |
| SZQFTX        | Unknown                     | [facc329a5a](https://linux-hardware.org/?probe=facc329a5a) | Sep 06, 2025 |
| Dell          | 03KWTV A00                  | [0b6a643a6d](https://linux-hardware.org/?probe=0b6a643a6d) | Sep 01, 2025 |
| Gigabyte      | Z790I AORUS ULTRA           | [06a3039912](https://linux-hardware.org/?probe=06a3039912) | Aug 23, 2025 |
| Dell          | 096JG8 A01                  | [924150dc28](https://linux-hardware.org/?probe=924150dc28) | Jun 22, 2025 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [f05d78c516](https://linux-hardware.org/?probe=f05d78c516) | Jun 22, 2025 |
| Dell          | 06D7TR A01                  | [9add0ff1c8](https://linux-hardware.org/?probe=9add0ff1c8) | Jun 21, 2025 |
| Unknown       | ROUTER                      | [fcd55b143d](https://linux-hardware.org/?probe=fcd55b143d) | Jun 15, 2025 |
| Gigabyte      | B450 AORUS ELITE V2         | [669b1429ef](https://linux-hardware.org/?probe=669b1429ef) | Jun 10, 2025 |
| Dell          | 096JG8 A01                  | [1a0dde453e](https://linux-hardware.org/?probe=1a0dde453e) | Jun 08, 2025 |
| ASUSTek       | A88XM-A/USB                 | [634c8694e2](https://linux-hardware.org/?probe=634c8694e2) | May 21, 2025 |
| ASRock        | B450M-HDV R4.0              | [c820736d19](https://linux-hardware.org/?probe=c820736d19) | May 16, 2025 |
| HP            | 8062                        | [22f2d5fc14](https://linux-hardware.org/?probe=22f2d5fc14) | May 14, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [1061a3acfb](https://linux-hardware.org/?probe=1061a3acfb) | May 14, 2025 |
| HP            | 82FE 11                     | [7f5fde25fc](https://linux-hardware.org/?probe=7f5fde25fc) | Mar 18, 2025 |
| ASUSTek       | PRIME A320M-K               | [a34bda55ad](https://linux-hardware.org/?probe=a34bda55ad) | Mar 14, 2025 |
| Gigabyte      | 970A-DS3P                   | [84845b7995](https://linux-hardware.org/?probe=84845b7995) | Feb 14, 2025 |
| MSI           | PRO B760M-E DDR4            | [4264ba425c](https://linux-hardware.org/?probe=4264ba425c) | Feb 13, 2025 |
| Gigabyte      | Z790I AORUS ULTRA           | [46217d52e3](https://linux-hardware.org/?probe=46217d52e3) | Jan 31, 2025 |
| B450MV1       | 1006                        | [cf4e566765](https://linux-hardware.org/?probe=cf4e566765) | Jan 28, 2025 |
| HP            | 212B                        | [58dd5a94cd](https://linux-hardware.org/?probe=58dd5a94cd) | Jan 22, 2025 |
| Gigabyte      | B550M DS3H                  | [88adc247f8](https://linux-hardware.org/?probe=88adc247f8) | Jan 22, 2025 |
| HP            | 3048h                       | [45684db6a9](https://linux-hardware.org/?probe=45684db6a9) | Jan 16, 2025 |
| Unknown       | ROUTER                      | [c6bf9058fa](https://linux-hardware.org/?probe=c6bf9058fa) | Dec 10, 2024 |
| ASUSTek       | H81M-K                      | [c3a615acb3](https://linux-hardware.org/?probe=c3a615acb3) | Nov 12, 2024 |
| ASUSTek       | H110M-A/DP                  | [00f803e8a2](https://linux-hardware.org/?probe=00f803e8a2) | Sep 18, 2024 |
| ASUSTek       | PRIME A320M-K               | [3b88a5d126](https://linux-hardware.org/?probe=3b88a5d126) | Aug 14, 2024 |
| Pegatron      | 2AE4                        | [db698b9ba0](https://linux-hardware.org/?probe=db698b9ba0) | Jul 31, 2024 |
| MSI           | X470 GAMING PLUS MAX        | [7c6efb1095](https://linux-hardware.org/?probe=7c6efb1095) | Jun 30, 2024 |
| Gigabyte      | B560M GAMING HD             | [c93b542abf](https://linux-hardware.org/?probe=c93b542abf) | Jun 19, 2024 |
| HP            | 83F2                        | [e802a9a41a](https://linux-hardware.org/?probe=e802a9a41a) | Jun 03, 2024 |
| Dell          | 0VD5HY A07                  | [a64b949879](https://linux-hardware.org/?probe=a64b949879) | May 28, 2024 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [001ab54ab1](https://linux-hardware.org/?probe=001ab54ab1) | May 23, 2024 |
| MSI           | K9N6PGM2-V2                 | [a79d33d7cf](https://linux-hardware.org/?probe=a79d33d7cf) | May 06, 2024 |
| Dell          | 0WMJ54 A00                  | [306aac13ae](https://linux-hardware.org/?probe=306aac13ae) | Mar 18, 2024 |
| Lenovo        | SHARKBAY NOK                | [abfba381b6](https://linux-hardware.org/?probe=abfba381b6) | Mar 02, 2024 |
| Lenovo        | SHARKBAY NOK                | [5d03e50172](https://linux-hardware.org/?probe=5d03e50172) | Mar 02, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [d72d6f6951](https://linux-hardware.org/?probe=d72d6f6951) | Feb 09, 2024 |
| Gigabyte      | H110M-H-CF                  | [d1065a1aca](https://linux-hardware.org/?probe=d1065a1aca) | Jan 30, 2024 |
| ZOTAC         | NM10                        | [e185a9b292](https://linux-hardware.org/?probe=e185a9b292) | Jan 18, 2024 |
| MSI           | A320M-A PRO                 | [f118f7960d](https://linux-hardware.org/?probe=f118f7960d) | Jan 18, 2024 |
| Dell          | 0GY6Y8 A01                  | [bece296ba4](https://linux-hardware.org/?probe=bece296ba4) | Jan 15, 2024 |
| Dell          | 0GY6Y8 A01                  | [6eb80a3aae](https://linux-hardware.org/?probe=6eb80a3aae) | Jan 15, 2024 |
| Lenovo        | Annapurna CRB NO DPK        | [7d003c702a](https://linux-hardware.org/?probe=7d003c702a) | Dec 27, 2023 |
| Gigabyte      | B150-HD3-CF                 | [d7e062f534](https://linux-hardware.org/?probe=d7e062f534) | Nov 15, 2023 |
| ZOTAC         | NM10                        | [5a951d80a6](https://linux-hardware.org/?probe=5a951d80a6) | Oct 31, 2023 |
| HP            | 3047h                       | [cdd7fbc37f](https://linux-hardware.org/?probe=cdd7fbc37f) | Oct 25, 2023 |
| HP            | 3047h                       | [4235f287b2](https://linux-hardware.org/?probe=4235f287b2) | Oct 25, 2023 |
| ZOTAC         | NM10                        | [2e0ab67bec](https://linux-hardware.org/?probe=2e0ab67bec) | Oct 21, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a8028e0998](https://linux-hardware.org/?probe=a8028e0998) | Oct 11, 2023 |
| ASRock        | A320M-HDV R4.0              | [d1d30ae371](https://linux-hardware.org/?probe=d1d30ae371) | Oct 10, 2023 |
| Dell          | 0D28YY A00                  | [ef531e70d1](https://linux-hardware.org/?probe=ef531e70d1) | Sep 22, 2023 |
| Dell          | 0RW203 A00                  | [0c76c5a1a7](https://linux-hardware.org/?probe=0c76c5a1a7) | Aug 30, 2023 |
| MSI           | A320M-A PRO                 | [a0394c8f0b](https://linux-hardware.org/?probe=a0394c8f0b) | Jul 30, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | [23633cafce](https://linux-hardware.org/?probe=23633cafce) | Jul 27, 2023 |
| ASUSTek       | A55BM-E                     | [4e99483733](https://linux-hardware.org/?probe=4e99483733) | Jul 13, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [a98b1d131d](https://linux-hardware.org/?probe=a98b1d131d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [eb913300f2](https://linux-hardware.org/?probe=eb913300f2) | Jul 06, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [607d40a328](https://linux-hardware.org/?probe=607d40a328) | Jul 04, 2023 |
| MSI           | A320M-A PRO                 | [7dffb9055b](https://linux-hardware.org/?probe=7dffb9055b) | Jun 29, 2023 |
| MSI           | Z390-A PRO                  | [638d6b4ef3](https://linux-hardware.org/?probe=638d6b4ef3) | Jun 27, 2023 |
| Dell          | 0WMJ54 A00                  | [5875771b0c](https://linux-hardware.org/?probe=5875771b0c) | May 24, 2023 |
| Dell          | 0WMJ54 A00                  | [50283ef123](https://linux-hardware.org/?probe=50283ef123) | May 24, 2023 |
| ZOTAC         | NM10                        | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| ASRock        | 970 Extreme3                | [906f9d6d04](https://linux-hardware.org/?probe=906f9d6d04) | Mar 30, 2023 |
| MSI           | PRO B650M-A WIFI            | [457915fe10](https://linux-hardware.org/?probe=457915fe10) | Mar 23, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| MSI           | 970A GAMING PRO CARBON      | [0649eea8a9](https://linux-hardware.org/?probe=0649eea8a9) | Feb 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [d6fea43eb5](https://linux-hardware.org/?probe=d6fea43eb5) | Feb 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cc2d26e52e](https://linux-hardware.org/?probe=cc2d26e52e) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| MACHINIST     | X79 V2.82H                  | [e6028c8640](https://linux-hardware.org/?probe=e6028c8640) | Jan 04, 2023 |
| ZOTAC         | NM10                        | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Gigabyte      | B150-HD3-CF                 | [173dde2177](https://linux-hardware.org/?probe=173dde2177) | Dec 14, 2022 |
| MSI           | PRO B650M-A WIFI            | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| Gigabyte      | H410M H                     | [09129dad50](https://linux-hardware.org/?probe=09129dad50) | Nov 28, 2022 |
| Gigabyte      | H410M H                     | [88ca303518](https://linux-hardware.org/?probe=88ca303518) | Nov 28, 2022 |
| Gigabyte      | H81M-DS2                    | [f278eb7e59](https://linux-hardware.org/?probe=f278eb7e59) | Nov 27, 2022 |
| ASRock        | B660M Steel Legend          | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| MACHINIST     | X79 V2.82H                  | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| ASUSTek       | PRIME Z370-A                | [5d789a1783](https://linux-hardware.org/?probe=5d789a1783) | Sep 28, 2022 |
| Intel         | DG41WV AAE90316-103         | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Dell          | 0HD5W2 A01                  | [1bb8ad599d](https://linux-hardware.org/?probe=1bb8ad599d) | Sep 11, 2022 |
| ASRock        | N68-S UCC                   | [1d38f1f08e](https://linux-hardware.org/?probe=1d38f1f08e) | Aug 30, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [b932802b52](https://linux-hardware.org/?probe=b932802b52) | Aug 04, 2022 |
| MACHINIST     | X79 V2.82H                  | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| Unknown       | Unknown                     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| Unknown       | Unknown                     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| HP            | 0AECh D                     | [68adfe0740](https://linux-hardware.org/?probe=68adfe0740) | May 12, 2022 |
| HP            | 83EE                        | [55171637ca](https://linux-hardware.org/?probe=55171637ca) | Apr 29, 2022 |
| Dell          | 040DDP A01                  | [1f14473753](https://linux-hardware.org/?probe=1f14473753) | Apr 19, 2022 |
| ZOTAC         | NM10                        | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| Dell          | 040DDP A01                  | [8e31fed1d4](https://linux-hardware.org/?probe=8e31fed1d4) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [ff072aa20b](https://linux-hardware.org/?probe=ff072aa20b) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [9cd507e648](https://linux-hardware.org/?probe=9cd507e648) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [e5b52520a8](https://linux-hardware.org/?probe=e5b52520a8) | Apr 07, 2022 |
| ASRock        | B450 Steel Legend           | [6a631fae48](https://linux-hardware.org/?probe=6a631fae48) | Mar 22, 2022 |
| Dell          | 0RW203 A00                  | [21ac06a9f6](https://linux-hardware.org/?probe=21ac06a9f6) | Feb 12, 2022 |
| Dell          | 09KPNV A01                  | [8fc6552bc9](https://linux-hardware.org/?probe=8fc6552bc9) | Feb 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [ac53ba49ef](https://linux-hardware.org/?probe=ac53ba49ef) | Jan 28, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | [9158036ed3](https://linux-hardware.org/?probe=9158036ed3) | Dec 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b482ef13ea](https://linux-hardware.org/?probe=b482ef13ea) | Dec 26, 2021 |
| ASUSTek       | H81M-C                      | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| MSI           | H55M-E33                    | [f0786be9c3](https://linux-hardware.org/?probe=f0786be9c3) | Nov 14, 2021 |
| HP            | 18E4                        | [692c64d7c1](https://linux-hardware.org/?probe=692c64d7c1) | Nov 08, 2021 |
| HP            | 18E4                        | [499e85c152](https://linux-hardware.org/?probe=499e85c152) | Nov 07, 2021 |
| MSI           | H55M-E33                    | [3d8c474259](https://linux-hardware.org/?probe=3d8c474259) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [2a83508f22](https://linux-hardware.org/?probe=2a83508f22) | Oct 10, 2021 |
| TPV-INVENT... | 2AF2 A01                    | [23e967d7f5](https://linux-hardware.org/?probe=23e967d7f5) | Oct 06, 2021 |
| ZOTAC         | NM10                        | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| ZOTAC         | NM10                        | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| Dell          | 0PU052                      | [25ce6d5bbd](https://linux-hardware.org/?probe=25ce6d5bbd) | Aug 05, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [a5a9cfcd44](https://linux-hardware.org/?probe=a5a9cfcd44) | Jul 18, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [689b83e978](https://linux-hardware.org/?probe=689b83e978) | Jul 18, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [b05fbab283](https://linux-hardware.org/?probe=b05fbab283) | Jun 06, 2021 |
| ASUSTek       | PRIME A320M-K               | [3e92571a0c](https://linux-hardware.org/?probe=3e92571a0c) | May 26, 2021 |
| Pegatron      | 2AE4                        | [604b735ad8](https://linux-hardware.org/?probe=604b735ad8) | May 02, 2021 |
| Intel         | D33217CK G76541-302         | [1db9d29c38](https://linux-hardware.org/?probe=1db9d29c38) | Apr 19, 2021 |
| ASUSTek       | PRIME A320M-K               | [48f003363a](https://linux-hardware.org/?probe=48f003363a) | Apr 09, 2021 |
| Dell          | 096JG8 A01                  | [1cf6d1daea](https://linux-hardware.org/?probe=1cf6d1daea) | Apr 02, 2021 |
| Supermicro    | X9DAi                       | [ff94b1201c](https://linux-hardware.org/?probe=ff94b1201c) | Mar 31, 2021 |
| Unknown       | i845G-W83627HF              | [2ff9864ce6](https://linux-hardware.org/?probe=2ff9864ce6) | Mar 29, 2021 |
| Pegatron      | 2AE4                        | [8570b15385](https://linux-hardware.org/?probe=8570b15385) | Feb 14, 2021 |
| ASUSTek       | H110M-K                     | [34bf1da3fe](https://linux-hardware.org/?probe=34bf1da3fe) | Feb 13, 2021 |
| ASRock        | 970 Extreme3                | [48548effcd](https://linux-hardware.org/?probe=48548effcd) | Feb 13, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [e0de5d87e6](https://linux-hardware.org/?probe=e0de5d87e6) | Feb 04, 2021 |
| Unknown       | i845G-W83627HF              | [6c9d42b55d](https://linux-hardware.org/?probe=6c9d42b55d) | Jan 08, 2021 |
| Unknown       | i845G-W83627HF              | [9ff8161bec](https://linux-hardware.org/?probe=9ff8161bec) | Jan 08, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [6706c380ab](https://linux-hardware.org/?probe=6706c380ab) | Dec 21, 2020 |
| Gigabyte      | H110M-S2-CF                 | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2d9e84acd0](https://linux-hardware.org/?probe=2d9e84acd0) | Dec 13, 2020 |
| Gigabyte      | GA-970A-D3                  | [3c6c9b7bd3](https://linux-hardware.org/?probe=3c6c9b7bd3) | Dec 11, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Alienware     | 06G6JW A01                  | [812527d15d](https://linux-hardware.org/?probe=812527d15d) | Dec 02, 2020 |
| Dell          | 042P49 A01                  | [36ddd61132](https://linux-hardware.org/?probe=36ddd61132) | Aug 12, 2020 |
| Gigabyte      | H110M-H-CF                  | [d8a8eb467a](https://linux-hardware.org/?probe=d8a8eb467a) | Aug 02, 2020 |
| Gateway       | FMCP7AM                     | [58e88b2df5](https://linux-hardware.org/?probe=58e88b2df5) | Jul 28, 2020 |
| ABIT          | AW9D-MAX                    | [fca26e4a11](https://linux-hardware.org/?probe=fca26e4a11) | Jul 21, 2020 |
| ASRock        | H81M-VG4 R2.0               | [c00d0feee3](https://linux-hardware.org/?probe=c00d0feee3) | Jul 21, 2020 |
| MSI           | 970 GAMING                  | [73c5756fdd](https://linux-hardware.org/?probe=73c5756fdd) | Jul 01, 2020 |
| ASRock        | B450 Steel Legend           | [7d9ad3146b](https://linux-hardware.org/?probe=7d9ad3146b) | Jun 12, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b9c266ed55](https://linux-hardware.org/?probe=b9c266ed55) | May 20, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [6252910769](https://linux-hardware.org/?probe=6252910769) | May 11, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [8fc4603f6c](https://linux-hardware.org/?probe=8fc4603f6c) | May 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [33cd43676f](https://linux-hardware.org/?probe=33cd43676f) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [1a81d95494](https://linux-hardware.org/?probe=1a81d95494) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [cd09b6b8a5](https://linux-hardware.org/?probe=cd09b6b8a5) | May 09, 2020 |
| ASRock        | 775i65GV                    | [0367c8a291](https://linux-hardware.org/?probe=0367c8a291) | Jan 07, 2020 |
| ASRock        | 775i65GV                    | [d0a8b9d7da](https://linux-hardware.org/?probe=d0a8b9d7da) | Dec 25, 2019 |
| Dell          | 042P49 A01                  | [ce3194fcde](https://linux-hardware.org/?probe=ce3194fcde) | Oct 28, 2019 |
| Gigabyte      | GA-78LMT-S2                 | [4ddf2bb220](https://linux-hardware.org/?probe=4ddf2bb220) | Oct 06, 2019 |
| Biostar       | H61MGV3                     | [911486bcc2](https://linux-hardware.org/?probe=911486bcc2) | Sep 08, 2019 |
| Biostar       | H61MGV3                     | [0b1e8f1f08](https://linux-hardware.org/?probe=0b1e8f1f08) | Jun 12, 2019 |
| Intel         | DG41WV AAE90316-103         | [7b2dc235f8](https://linux-hardware.org/?probe=7b2dc235f8) | May 18, 2019 |
| Lenovo        | SHARKBAY 31900003 STD       | [e7164fcda2](https://linux-hardware.org/?probe=e7164fcda2) | Dec 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 9        | 6.43%   |
| OpenMandriva 4.2   | 9        | 6.43%   |
| Ubuntu 22.04       | 8        | 5.71%   |
| Ubuntu 18.04       | 4        | 2.86%   |
| OpenMandriva 23.03 | 4        | 2.86%   |
| OpenMandriva 4.3   | 3        | 2.14%   |
| Linux Mint 20.2    | 3        | 2.14%   |
| Zorin 16           | 2        | 1.43%   |
| Xubuntu 22.04      | 2        | 1.43%   |
| Ubuntu 22.10       | 2        | 1.43%   |
| Pop!_OS 22.04      | 2        | 1.43%   |
| Pop!_OS 21.04      | 2        | 1.43%   |
| OpenMandriva 25.04 | 2        | 1.43%   |
| OpenMandriva 25.01 | 2        | 1.43%   |
| OpenMandriva 24.07 | 2        | 1.43%   |
| OpenMandriva 23.01 | 2        | 1.43%   |
| Lubuntu 25.10      | 2        | 1.43%   |
| Lubuntu 22.04      | 2        | 1.43%   |
| Linux Mint 22.1    | 2        | 1.43%   |
| Linux Mint 19.3    | 2        | 1.43%   |
| Kubuntu 24.04      | 2        | 1.43%   |
| KDE neon 22.04     | 2        | 1.43%   |
| Fedora 41          | 2        | 1.43%   |
| Fedora 38          | 2        | 1.43%   |
| Fedora 32          | 2        | 1.43%   |
| ArcoLinux Rolling  | 2        | 1.43%   |
| Arch Rolling       | 2        | 1.43%   |
| Zorin 17           | 1        | 0.71%   |
| Zorin 15           | 1        | 0.71%   |
| Zorin 12           | 1        | 0.71%   |
| Xubuntu 24.04      | 1        | 0.71%   |
| UbuntuDDE 20.04    | 1        | 0.71%   |
| Ubuntu 24.04       | 1        | 0.71%   |
| Ubuntu 20.10       | 1        | 0.71%   |
| Ubuntu 19.10       | 1        | 0.71%   |
| Ubuntu 1.3.2       | 1        | 0.71%   |
| ROSA R8.1          | 1        | 0.71%   |
| ROSA R11.1         | 1        | 0.71%   |
| ROSA R11           | 1        | 0.71%   |
| Pop!_OS 24.04      | 1        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| OpenMandriva | 28       | 21.54%  |
| Ubuntu       | 27       | 20.77%  |
| Fedora       | 11       | 8.46%   |
| Linux Mint   | 10       | 7.69%   |
| Pop!_OS      | 7        | 5.38%   |
| Manjaro      | 7        | 5.38%   |
| Lubuntu      | 6        | 4.62%   |
| Zorin        | 5        | 3.85%   |
| KDE neon     | 4        | 3.08%   |
| Xubuntu      | 3        | 2.31%   |
| Kubuntu      | 3        | 2.31%   |
| Debian       | 3        | 2.31%   |
| ArcoLinux    | 3        | 2.31%   |
| Arch         | 3        | 2.31%   |
| ROSA         | 2        | 1.54%   |
| Elementary   | 2        | 1.54%   |
| UbuntuDDE    | 1        | 0.77%   |
| Nobara       | 1        | 0.77%   |
| EndeavourOS  | 1        | 0.77%   |
| Deepin       | 1        | 0.77%   |
| BlackPanther | 1        | 0.77%   |
| Bazzite      | 1        | 0.77%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 9        | 6.04%   |
| 6.2.6-desktop-1omv2390   | 4        | 2.68%   |
| 6.14.2-desktop-3omv2590  | 3        | 2.01%   |
| 5.4.0-70-generic         | 3        | 2.01%   |
| 5.16.7-desktop-1omv4003  | 3        | 2.01%   |
| 6.4.11-desktop-1omv2390  | 2        | 1.34%   |
| 6.10.0-desktop-1omv2490  | 2        | 1.34%   |
| 5.4.0-42-generic         | 2        | 1.34%   |
| 5.19.0-45-generic        | 2        | 1.34%   |
| 5.15.0-53-generic        | 2        | 1.34%   |
| 6.9.7-zen1-1-zen         | 1        | 0.67%   |
| 6.8.12-10-pve            | 1        | 0.67%   |
| 6.8.10-300.fc40.x86_64   | 1        | 0.67%   |
| 6.8.0-86-generic         | 1        | 0.67%   |
| 6.8.0-79-generic         | 1        | 0.67%   |
| 6.8.0-60-generic         | 1        | 0.67%   |
| 6.8.0-52-generic         | 1        | 0.67%   |
| 6.8.0-51-generic         | 1        | 0.67%   |
| 6.8.0-40-generic         | 1        | 0.67%   |
| 6.7.0-custom             | 1        | 0.67%   |
| 6.7.0-arch3-1            | 1        | 0.67%   |
| 6.6.2-desktop-1omv2390   | 1        | 0.67%   |
| 6.6.19-1-MANJARO         | 1        | 0.67%   |
| 6.6.0-custom             | 1        | 0.67%   |
| 6.5.6-200.fc38.x86_64    | 1        | 0.67%   |
| 6.5.0-41-generic         | 1        | 0.67%   |
| 6.5.0-35-generic         | 1        | 0.67%   |
| 6.5.0-21-generic         | 1        | 0.67%   |
| 6.4.6-76060406-generic   | 1        | 0.67%   |
| 6.3.8-200.fc38.x86_64    | 1        | 0.67%   |
| 6.3.3-custom             | 1        | 0.67%   |
| 6.2.7-200.fc37.x86_64    | 1        | 0.67%   |
| 6.2.0-33-generic         | 1        | 0.67%   |
| 6.18.0-x86-64-v3-custom  | 1        | 0.67%   |
| 6.17.9-76061709-generic  | 1        | 0.67%   |
| 6.17.7-alderlake-custom  | 1        | 0.67%   |
| 6.17.1-arch1-1           | 1        | 0.67%   |
| 6.17.1-300.fc43.x86_64   | 1        | 0.67%   |
| 6.17.0-6-generic         | 1        | 0.67%   |
| 6.15.2-x86-64-v2-custom  | 1        | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 12       | 8.22%   |
| 5.15.0  | 11       | 7.53%   |
| 5.10.14 | 9        | 6.16%   |
| 6.8.0   | 6        | 4.11%   |
| 4.15.0  | 6        | 4.11%   |
| 5.19.0  | 5        | 3.42%   |
| 6.2.6   | 4        | 2.74%   |
| 6.14.0  | 4        | 2.74%   |
| 5.8.0   | 4        | 2.74%   |
| 5.11.0  | 4        | 2.74%   |
| 6.5.0   | 3        | 2.05%   |
| 6.14.2  | 3        | 2.05%   |
| 5.16.7  | 3        | 2.05%   |
| 6.7.0   | 2        | 1.37%   |
| 6.4.11  | 2        | 1.37%   |
| 6.17.1  | 2        | 1.37%   |
| 6.12.1  | 2        | 1.37%   |
| 6.11.0  | 2        | 1.37%   |
| 6.10.0  | 2        | 1.37%   |
| 6.1.1   | 2        | 1.37%   |
| 5.3.0   | 2        | 1.37%   |
| 5.13.0  | 2        | 1.37%   |
| 6.9.7   | 1        | 0.68%   |
| 6.8.12  | 1        | 0.68%   |
| 6.8.10  | 1        | 0.68%   |
| 6.6.2   | 1        | 0.68%   |
| 6.6.19  | 1        | 0.68%   |
| 6.6.0   | 1        | 0.68%   |
| 6.5.6   | 1        | 0.68%   |
| 6.4.6   | 1        | 0.68%   |
| 6.3.8   | 1        | 0.68%   |
| 6.3.3   | 1        | 0.68%   |
| 6.2.7   | 1        | 0.68%   |
| 6.2.0   | 1        | 0.68%   |
| 6.18.0  | 1        | 0.68%   |
| 6.17.9  | 1        | 0.68%   |
| 6.17.7  | 1        | 0.68%   |
| 6.17.0  | 1        | 0.68%   |
| 6.15.2  | 1        | 0.68%   |
| 6.14.6  | 1        | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 13       | 8.97%   |
| 5.15    | 13       | 8.97%   |
| 5.10    | 12       | 8.28%   |
| 6.14    | 9        | 6.21%   |
| 6.8     | 8        | 5.52%   |
| 6.2     | 6        | 4.14%   |
| 4.15    | 6        | 4.14%   |
| 6.17    | 5        | 3.45%   |
| 6.12    | 5        | 3.45%   |
| 6.1     | 5        | 3.45%   |
| 5.19    | 5        | 3.45%   |
| 5.11    | 5        | 3.45%   |
| 6.5     | 4        | 2.76%   |
| 5.8     | 4        | 2.76%   |
| 5.6     | 4        | 2.76%   |
| 6.6     | 3        | 2.07%   |
| 6.4     | 3        | 2.07%   |
| 6.11    | 3        | 2.07%   |
| 6.10    | 3        | 2.07%   |
| 6.0     | 3        | 2.07%   |
| 5.16    | 3        | 2.07%   |
| 5.13    | 3        | 2.07%   |
| 6.7     | 2        | 1.38%   |
| 6.3     | 2        | 1.38%   |
| 6.13    | 2        | 1.38%   |
| 5.9     | 2        | 1.38%   |
| 5.3     | 2        | 1.38%   |
| 5.18    | 2        | 1.38%   |
| 6.9     | 1        | 0.69%   |
| 6.18    | 1        | 0.69%   |
| 6.15    | 1        | 0.69%   |
| 5.7     | 1        | 0.69%   |
| 5.17    | 1        | 0.69%   |
| 5.14    | 1        | 0.69%   |
| 4.18    | 1        | 0.69%   |
| 4.1     | 1        | 0.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 117      | 97.5%   |
| i686   | 3        | 2.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 48       | 37.8%   |
| KDE5          | 28       | 22.05%  |
| Unknown       | 11       | 8.66%   |
| KDE6          | 10       | 7.87%   |
| LXQt          | 8        | 6.3%    |
| XFCE          | 6        | 4.72%   |
| X-Cinnamon    | 6        | 4.72%   |
| Pantheon      | 2        | 1.57%   |
| MATE          | 2        | 1.57%   |
| KDE           | 1        | 0.79%   |
| Hyprland      | 1        | 0.79%   |
| GNOME Classic | 1        | 0.79%   |
| Deepin        | 1        | 0.79%   |
| DDE           | 1        | 0.79%   |
| COSMIC        | 1        | 0.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 90       | 72%     |
| Wayland | 32       | 25.6%   |
| Tty     | 3        | 2.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 52       | 41.94%  |
| SDDM    | 42       | 33.87%  |
| GDM3    | 12       | 9.68%   |
| GDM     | 10       | 8.06%   |
| LightDM | 6        | 4.84%   |
| TDM     | 2        | 1.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 55       | 42.64%  |
| es_CR   | 51       | 39.53%  |
| es_MX   | 10       | 7.75%   |
| es_ES   | 5        | 3.88%   |
| Unknown | 5        | 3.88%   |
| en_GB   | 1        | 0.78%   |
| de_DE   | 1        | 0.78%   |
| C       | 1        | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 63       | 51.64%  |
| BIOS | 59       | 48.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 75       | 59.06%  |
| Overlay | 21       | 16.54%  |
| Btrfs   | 20       | 15.75%  |
| Tmpfs   | 8        | 6.3%    |
| Xfs     | 2        | 1.57%   |
| Unknown | 1        | 0.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 63       | 50.81%  |
| Unknown | 52       | 41.94%  |
| MBR     | 9        | 7.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 78.69%  |
| Yes       | 26       | 21.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 63.41%  |
| Yes       | 45       | 36.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 23       | 19.17%  |
| Gigabyte Technology | 21       | 17.5%   |
| Dell                | 18       | 15%     |
| MSI                 | 16       | 13.33%  |
| Hewlett-Packard     | 10       | 8.33%   |
| ASRock              | 9        | 7.5%    |
| Unknown             | 4        | 3.33%   |
| Lenovo              | 3        | 2.5%    |
| TianBei             | 2        | 1.67%   |
| Intel               | 2        | 1.67%   |
| ZOTAC               | 1        | 0.83%   |
| TPV-INVENTA         | 1        | 0.83%   |
| SZQFTX              | 1        | 0.83%   |
| Supermicro          | 1        | 0.83%   |
| Pegatron            | 1        | 0.83%   |
| MACHINIST           | 1        | 0.83%   |
| Gateway             | 1        | 0.83%   |
| Foxconn             | 1        | 0.83%   |
| Biostar             | 1        | 0.83%   |
| B450MV1             | 1        | 0.83%   |
| Alienware           | 1        | 0.83%   |
| ABIT                | 1        | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Dell OptiPlex 3020                       | 6        | 5%      |
| Unknown                                  | 5        | 4.17%   |
| MSI MS-7C51                              | 3        | 2.5%    |
| Dell OptiPlex 7040                       | 3        | 2.5%    |
| ASUS PRIME A320M-K                       | 3        | 2.5%    |
| TianBei N1 PRO                           | 2        | 1.67%   |
| HP Z440 Workstation                      | 2        | 1.67%   |
| Gigabyte H110M-H                         | 2        | 1.67%   |
| Gigabyte B250M-DS3H                      | 2        | 1.67%   |
| ASUS TUF Gaming X570-PLUS                | 2        | 1.67%   |
| ASUS PRIME H310M-E R2.0                  | 2        | 1.67%   |
| ASUS All Series                          | 2        | 1.67%   |
| ASRock B450 Steel Legend                 | 2        | 1.67%   |
| ZOTAC NM10                               | 1        | 0.83%   |
| TPV-INVENTA 18-2003LA                    | 1        | 0.83%   |
| Supermicro X9DAi                         | 1        | 0.83%   |
| Pegatron CQ2728LA                        | 1        | 0.83%   |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1        | 0.83%   |
| MSI MS-7E51                              | 1        | 0.83%   |
| MSI MS-7E05                              | 1        | 0.83%   |
| MSI MS-7D77                              | 1        | 0.83%   |
| MSI MS-7D48                              | 1        | 0.83%   |
| MSI MS-7C91                              | 1        | 0.83%   |
| MSI MS-7B98                              | 1        | 0.83%   |
| MSI MS-7B86                              | 1        | 0.83%   |
| MSI MS-7B79                              | 1        | 0.83%   |
| MSI MS-7992                              | 1        | 0.83%   |
| MSI MS-7693                              | 1        | 0.83%   |
| MSI MS-7636                              | 1        | 0.83%   |
| MSI MS-7309                              | 1        | 0.83%   |
| MACHINIST X79 V2.82H                     | 1        | 0.83%   |
| Lenovo ThinkCentre M93p 10A8S41Q00       | 1        | 0.83%   |
| Lenovo ThinkCentre M78 21131C7           | 1        | 0.83%   |
| Lenovo H530S 10132                       | 1        | 0.83%   |
| Intel DG41WV AAE90316-103                | 1        | 0.83%   |
| Intel D33217CK G76541-302                | 1        | 0.83%   |
| HP Z800 Workstation                      | 1        | 0.83%   |
| HP ProDesk 600 G4 SFF                    | 1        | 0.83%   |
| HP ProDesk 400 G5 SFF                    | 1        | 0.83%   |
| HP ProDesk 400 G3 SFF                    | 1        | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 15       | 12.5%   |
| ASUS PRIME            | 7        | 5.83%   |
| Unknown               | 5        | 4.17%   |
| MSI MS-7C51           | 3        | 2.5%    |
| HP ProDesk            | 3        | 2.5%    |
| ASUS TUF              | 3        | 2.5%    |
| ASUS ROG              | 3        | 2.5%    |
| TianBei N1            | 2        | 1.67%   |
| Lenovo ThinkCentre    | 2        | 1.67%   |
| HP Z440               | 2        | 1.67%   |
| HP Compaq             | 2        | 1.67%   |
| Gigabyte H110M-H      | 2        | 1.67%   |
| Gigabyte B550M        | 2        | 1.67%   |
| Gigabyte B250M-DS3H   | 2        | 1.67%   |
| Dell Precision        | 2        | 1.67%   |
| ASUS SABERTOOTH       | 2        | 1.67%   |
| ASUS All              | 2        | 1.67%   |
| ASRock B450           | 2        | 1.67%   |
| ZOTAC NM10            | 1        | 0.83%   |
| TPV-INVENTA 18-2003LA | 1        | 0.83%   |
| Supermicro X9DAi      | 1        | 0.83%   |
| Pegatron CQ2728LA     | 1        | 0.83%   |
| MSI Z390              | 1        | 0.83%   |
| MSI MS-7E51           | 1        | 0.83%   |
| MSI MS-7E05           | 1        | 0.83%   |
| MSI MS-7D77           | 1        | 0.83%   |
| MSI MS-7D48           | 1        | 0.83%   |
| MSI MS-7C91           | 1        | 0.83%   |
| MSI MS-7B98           | 1        | 0.83%   |
| MSI MS-7B86           | 1        | 0.83%   |
| MSI MS-7B79           | 1        | 0.83%   |
| MSI MS-7992           | 1        | 0.83%   |
| MSI MS-7693           | 1        | 0.83%   |
| MSI MS-7636           | 1        | 0.83%   |
| MSI MS-7309           | 1        | 0.83%   |
| MACHINIST X79         | 1        | 0.83%   |
| Lenovo H530S          | 1        | 0.83%   |
| Intel DG41WV          | 1        | 0.83%   |
| Intel D33217CK        | 1        | 0.83%   |
| HP Z800               | 1        | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2016 | 13       | 10.83%  |
| 2019 | 12       | 10%     |
| 2014 | 12       | 10%     |
| 2013 | 12       | 10%     |
| 2018 | 9        | 7.5%    |
| 2020 | 7        | 5.83%   |
| 2012 | 7        | 5.83%   |
| 2024 | 6        | 5%      |
| 2021 | 6        | 5%      |
| 2017 | 5        | 4.17%   |
| 2015 | 5        | 4.17%   |
| 2023 | 4        | 3.33%   |
| 2011 | 4        | 3.33%   |
| 2010 | 4        | 3.33%   |
| 2009 | 4        | 3.33%   |
| 2022 | 3        | 2.5%    |
| 2008 | 2        | 1.67%   |
| 2007 | 2        | 1.67%   |
| 2005 | 2        | 1.67%   |
| 2025 | 1        | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 120      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 113      | 93.39%  |
| Enabled  | 8        | 6.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 120      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 39       | 31.45%  |
| 8.01-16.0       | 26       | 20.97%  |
| 4.01-8.0        | 16       | 12.9%   |
| 32.01-64.0      | 15       | 12.1%   |
| 3.01-4.0        | 13       | 10.48%  |
| 64.01-256.0     | 6        | 4.84%   |
| 1.01-2.0        | 5        | 4.03%   |
| 24.01-32.0      | 2        | 1.61%   |
| More than 256.0 | 1        | 0.81%   |
| 2.01-3.0        | 1        | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 47       | 34.81%  |
| 2.01-3.0   | 31       | 22.96%  |
| 4.01-8.0   | 23       | 17.04%  |
| 3.01-4.0   | 18       | 13.33%  |
| 0.51-1.0   | 7        | 5.19%   |
| 8.01-16.0  | 3        | 2.22%   |
| 0.01-0.5   | 3        | 2.22%   |
| 16.01-24.0 | 2        | 1.48%   |
| 24.01-32.0 | 1        | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 52       | 41.27%  |
| 2      | 41       | 32.54%  |
| 3      | 15       | 11.9%   |
| 4      | 11       | 8.73%   |
| 5      | 3        | 2.38%   |
| 9      | 1        | 0.79%   |
| 8      | 1        | 0.79%   |
| 7      | 1        | 0.79%   |
| 6      | 1        | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 65.85%  |
| Yes       | 42       | 34.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 119      | 99.17%  |
| No        | 1        | 0.83%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 53.28%  |
| Yes       | 57       | 46.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 66.94%  |
| Yes       | 41       | 33.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Costa Rica | 120      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| San José     | 60       | 44.78%  |
| Heredia       | 23       | 17.16%  |
| Grecia        | 7        | 5.22%   |
| Escazu        | 6        | 4.48%   |
| Cartago       | 5        | 3.73%   |
| Alajuela      | 5        | 3.73%   |
| Quesada       | 3        | 2.24%   |
| Liberia       | 3        | 2.24%   |
| Santa Fe      | 2        | 1.49%   |
| Santa Ana     | 2        | 1.49%   |
| Perez Zeledon | 2        | 1.49%   |
| Pavas         | 2        | 1.49%   |
| Tres Rios     | 1        | 0.75%   |
| Tibas         | 1        | 0.75%   |
| Siquirres     | 1        | 0.75%   |
| San Ramon     | 1        | 0.75%   |
| San Pedro     | 1        | 0.75%   |
| Rio Segundo   | 1        | 0.75%   |
| Puntarenas    | 1        | 0.75%   |
| Palmares      | 1        | 0.75%   |
| Nosara        | 1        | 0.75%   |
| Naranjo       | 1        | 0.75%   |
| Curridabat    | 1        | 0.75%   |
| Cariblanca    | 1        | 0.75%   |
| Bajo Perez    | 1        | 0.75%   |
| Alajuelita    | 1        | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 39       | 64     | 16.74%  |
| WDC                         | 32       | 40     | 13.73%  |
| Kingston                    | 25       | 33     | 10.73%  |
| Toshiba                     | 18       | 20     | 7.73%   |
| A-DATA Technology           | 17       | 18     | 7.3%    |
| Samsung Electronics         | 13       | 24     | 5.58%   |
| Patriot                     | 8        | 13     | 3.43%   |
| SanDisk                     | 7        | 8      | 3%      |
| Hitachi                     | 7        | 9      | 3%      |
| Realtek Semiconductor       | 6        | 8      | 2.58%   |
| XPG                         | 4        | 4      | 1.72%   |
| Unknown                     | 3        | 4      | 1.29%   |
| Micron/Crucial Technology   | 3        | 3      | 1.29%   |
| HGST                        | 3        | 3      | 1.29%   |
| Crucial                     | 3        | 3      | 1.29%   |
| ADATA Technology            | 3        | 4      | 1.29%   |
| ZOTAC                       | 2        | 3      | 0.86%   |
| Team                        | 2        | 2      | 0.86%   |
| Phison Electronics          | 2        | 2      | 0.86%   |
| Netac                       | 2        | 3      | 0.86%   |
| Mushkin                     | 2        | 2      | 0.86%   |
| Maxtor                      | 2        | 2      | 0.86%   |
| Intel                       | 2        | 2      | 0.86%   |
| Gigabyte Technology         | 2        | 3      | 0.86%   |
| China                       | 2        | 2      | 0.86%   |
| Biostar                     | 2        | 2      | 0.86%   |
| ASint Technology            | 2        | 2      | 0.86%   |
| Wicgtyp                     | 1        | 2      | 0.43%   |
| WD MediaMax                 | 1        | 1      | 0.43%   |
| T-FORCE                     | 1        | 1      | 0.43%   |
| SSSTC                       | 1        | 1      | 0.43%   |
| Silicon Motion              | 1        | 1      | 0.43%   |
| Shenzhen                    | 1        | 1      | 0.43%   |
| SABRENT                     | 1        | 1      | 0.43%   |
| PNY                         | 1        | 1      | 0.43%   |
| Lexar                       | 1        | 1      | 0.43%   |
| KIOXIA                      | 1        | 1      | 0.43%   |
| Kingston Technology Company | 1        | 2      | 0.43%   |
| JMicron Technology          | 1        | 1      | 0.43%   |
| HS-SSD-WAVE(N)              | 1        | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                                    | 9        | 3.53%   |
| Toshiba DT01ACA100 1TB                                             | 6        | 2.35%   |
| A-DATA SU630 480GB SSD                                             | 5        | 1.96%   |
| WDC WD10EZEX-75WN4A1 1TB                                           | 4        | 1.57%   |
| WDC WD10EZEX-08WN4A0 1TB                                           | 4        | 1.57%   |
| Seagate ST1000DM003-1CH162 1TB                                     | 4        | 1.57%   |
| A-DATA SU650 120GB SSD                                             | 4        | 1.57%   |
| WDC WD10EZEX-60WN4A0 1TB                                           | 3        | 1.18%   |
| Toshiba MQ01ABD100 1TB                                             | 3        | 1.18%   |
| Seagate ST500DM002-1BD142 500GB                                    | 3        | 1.18%   |
| Realtek RTS5763DL NVMe SSD Controller 512GB                        | 3        | 1.18%   |
| Patriot P210 256GB SSD                                             | 3        | 1.18%   |
| Kingston SV300S37A120G 120GB SSD                                   | 3        | 1.18%   |
| Kingston SA400S37480G 480GB SSD                                    | 3        | 1.18%   |
| XPG GAMMIX S11 Pro 1TB                                             | 2        | 0.78%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                   | 2        | 0.78%   |
| Seagate ST8000DM004-2CX188 8TB                                     | 2        | 0.78%   |
| Seagate ST4000DM004-2CV104 4TB                                     | 2        | 0.78%   |
| Seagate ST380815AS 80GB                                            | 2        | 0.78%   |
| Seagate ST2000LM015-2E8174 2TB                                     | 2        | 0.78%   |
| Seagate ST2000LM007-1R8174 2TB                                     | 2        | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB                                     | 2        | 0.78%   |
| Seagate Backup+ Desk 5TB                                           | 2        | 0.78%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                                | 2        | 0.78%   |
| Samsung SSD 860 EVO 500GB                                          | 2        | 0.78%   |
| Patriot M.2 P300 256GB                                             | 2        | 0.78%   |
| Patriot Burst Elite 240GB SSD                                      | 2        | 0.78%   |
| Mushkin MKNSSDEL240GB                                              | 2        | 0.78%   |
| Kingston SUV400S37240G 240GB SSD                                   | 2        | 0.78%   |
| Kingston SUV400S37120G 120GB SSD                                   | 2        | 0.78%   |
| Kingston SKC400S37256G 256GB SSD                                   | 2        | 0.78%   |
| Hitachi HUA722020ALA331 2TB                                        | 2        | 0.78%   |
| HGST HTS541075A9E680 752GB                                         | 2        | 0.78%   |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD                               | 2        | 0.78%   |
| Biostar S100-120GB SSD                                             | 2        | 0.78%   |
| ASint AS606 256GB SSD                                              | 2        | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 2        | 0.78%   |
| A-DATA SX8100NP 256GB                                              | 2        | 0.78%   |
| ZOTAC ZTSSD-S11-240G-P 240GB                                       | 1        | 0.39%   |
| ZOTAC ZTSSD-S11-120G-MD 120GB                                      | 1        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 38       | 62     | 35.85%  |
| WDC                 | 30       | 35     | 28.3%   |
| Toshiba             | 15       | 17     | 14.15%  |
| Hitachi             | 7        | 9      | 6.6%    |
| Samsung Electronics | 4        | 4      | 3.77%   |
| Unknown             | 3        | 4      | 2.83%   |
| HGST                | 3        | 3      | 2.83%   |
| Maxtor              | 2        | 2      | 1.89%   |
| WD MediaMax         | 1        | 1      | 0.94%   |
| Shenzhen            | 1        | 1      | 0.94%   |
| JMicron Technology  | 1        | 1      | 0.94%   |
| ASMedia             | 1        | 1      | 0.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 22       | 28     | 26.83%  |
| A-DATA Technology   | 14       | 15     | 17.07%  |
| Samsung Electronics | 6        | 13     | 7.32%   |
| Patriot             | 6        | 10     | 7.32%   |
| SanDisk             | 4        | 5      | 4.88%   |
| WDC                 | 3        | 5      | 3.66%   |
| ZOTAC               | 2        | 3      | 2.44%   |
| Team                | 2        | 2      | 2.44%   |
| Mushkin             | 2        | 2      | 2.44%   |
| Intel               | 2        | 2      | 2.44%   |
| Gigabyte Technology | 2        | 3      | 2.44%   |
| Crucial             | 2        | 2      | 2.44%   |
| Biostar             | 2        | 2      | 2.44%   |
| ASint Technology    | 2        | 2      | 2.44%   |
| Wicgtyp             | 1        | 2      | 1.22%   |
| SSSTC               | 1        | 1      | 1.22%   |
| SABRENT             | 1        | 1      | 1.22%   |
| PNY                 | 1        | 1      | 1.22%   |
| Netac               | 1        | 1      | 1.22%   |
| Lexar               | 1        | 1      | 1.22%   |
| Dahua               | 1        | 1      | 1.22%   |
| CT120BX5            | 1        | 1      | 1.22%   |
| China               | 1        | 1      | 1.22%   |
| AGI                 | 1        | 1      | 1.22%   |
| Acer                | 1        | 1      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 78       | 140    | 42.16%  |
| SSD     | 68       | 106    | 36.76%  |
| NVMe    | 34       | 54     | 18.38%  |
| Unknown | 5        | 5      | 2.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 115      | 231    | 71.43%  |
| NVMe | 34       | 54     | 21.12%  |
| SAS  | 12       | 20     | 7.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 86       | 141    | 51.81%  |
| 0.51-1.0   | 49       | 64     | 29.52%  |
| 1.01-2.0   | 14       | 15     | 8.43%   |
| 4.01-10.0  | 6        | 9      | 3.61%   |
| 3.01-4.0   | 5        | 9      | 3.01%   |
| 2.01-3.0   | 5        | 7      | 3.01%   |
| 10.01-20.0 | 1        | 1      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 29       | 21.64%  |
| 501-1000       | 28       | 20.9%   |
| 1001-2000      | 18       | 13.43%  |
| 251-500        | 16       | 11.94%  |
| 1-20           | 16       | 11.94%  |
| More than 3000 | 9        | 6.72%   |
| 51-100         | 8        | 5.97%   |
| Unknown        | 5        | 3.73%   |
| 2001-3000      | 3        | 2.24%   |
| 21-50          | 2        | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 52       | 37.41%  |
| 21-50          | 22       | 15.83%  |
| 101-250        | 13       | 9.35%   |
| 51-100         | 13       | 9.35%   |
| 251-500        | 12       | 8.63%   |
| 501-1000       | 9        | 6.47%   |
| More than 3000 | 5        | 3.6%    |
| Unknown        | 5        | 3.6%    |
| 1001-2000      | 4        | 2.88%   |
| 2001-3000      | 3        | 2.16%   |
| 0              | 1        | 0.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST1000DM003-1CH162 1TB      | 2        | 3      | 10.53%  |
| SanDisk SD6SB1M-128G-1006 128GB SSD | 2        | 3      | 10.53%  |
| Kingston SV300S37A120G 120GB SSD    | 2        | 2      | 10.53%  |
| A-DATA Technology SX8100NP 256GB    | 2        | 2      | 10.53%  |
| WDC WD1002FBYS-01A6B0 1TB           | 1        | 1      | 5.26%   |
| Unknown MB3000EBKAB 3TB             | 1        | 1      | 5.26%   |
| Seagate ST9160412AS 160GB           | 1        | 1      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB     | 1        | 1      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 2      | 5.26%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 5.26%   |
| Samsung Electronics HM641JI 640GB   | 1        | 1      | 5.26%   |
| Maxtor STM3160215AS 160GB           | 1        | 1      | 5.26%   |
| Kingston SA400S37480G 480GB SSD     | 1        | 1      | 5.26%   |
| Kingston SA400S37240G 240GB SSD     | 1        | 1      | 5.26%   |
| Hitachi HDE721010SLA330 1TB         | 1        | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 7      | 26.32%  |
| Kingston            | 4        | 4      | 21.05%  |
| SanDisk             | 2        | 3      | 10.53%  |
| Samsung Electronics | 2        | 2      | 10.53%  |
| A-DATA Technology   | 2        | 2      | 10.53%  |
| WDC                 | 1        | 1      | 5.26%   |
| Unknown             | 1        | 1      | 5.26%   |
| Maxtor              | 1        | 1      | 5.26%   |
| Hitachi             | 1        | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 7      | 50%     |
| WDC                 | 1        | 1      | 10%     |
| Unknown             | 1        | 1      | 10%     |
| Samsung Electronics | 1        | 1      | 10%     |
| Maxtor              | 1        | 1      | 10%     |
| Hitachi             | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 12     | 47.06%  |
| SSD  | 7        | 8      | 41.18%  |
| NVMe | 2        | 2      | 11.76%  |

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
| Detected | 67       | 152    | 48.2%   |
| Works    | 58       | 131    | 41.73%  |
| Malfunc  | 14       | 22     | 10.07%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 73       | 42.2%   |
| AMD                          | 43       | 24.86%  |
| Realtek Semiconductor        | 8        | 4.62%   |
| ASMedia Technology           | 7        | 4.05%   |
| ADATA Technology             | 7        | 4.05%   |
| Micron/Crucial Technology    | 4        | 2.31%   |
| Kingston Technology Company  | 4        | 2.31%   |
| SanDisk                      | 3        | 1.73%   |
| Samsung Electronics          | 3        | 1.73%   |
| Nvidia                       | 3        | 1.73%   |
| LSI Logic / Symbios Logic    | 3        | 1.73%   |
| Toshiba America Info Systems | 2        | 1.16%   |
| Silicon Motion               | 2        | 1.16%   |
| Phison Electronics           | 2        | 1.16%   |
| INNOGRIT                     | 2        | 1.16%   |
| Hosin Global Electronics     | 2        | 1.16%   |
| Silicon Image                | 1        | 0.58%   |
| OCZ Technology Group         | 1        | 0.58%   |
| Marvell Technology Group     | 1        | 0.58%   |
| KIOXIA                       | 1        | 0.58%   |
| JMicron Technology           | 1        | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17       | 8.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14       | 7.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10       | 5.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8        | 4.08%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 8        | 4.08%   |
| AMD 500 Series Chipset SATA Controller                                         | 7        | 3.57%   |
| AMD 400 Series Chipset SATA Controller                                         | 7        | 3.57%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 6        | 3.06%   |
| Intel SATA Controller [RAID mode]                                              | 6        | 3.06%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 6        | 3.06%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 6        | 3.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5        | 2.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 2.04%   |
| Intel Alder Lake-N SATA AHCI Controller                                        | 4        | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 1.53%   |
| AMD 600 Series Chipset SATA Controller                                         | 3        | 1.53%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2        | 1.02%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 2        | 1.02%   |
| Nvidia MCP61 SATA Controller                                                   | 2        | 1.02%   |
| Nvidia MCP61 IDE                                                               | 2        | 1.02%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2        | 1.02%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                           | 2        | 1.02%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 2        | 1.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.02%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 1.02%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 1.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 1.02%   |
| Hosin Global Patriot P300 NVMe SSD (DRAM-less)                                 | 2        | 1.02%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1        | 0.51%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 0.51%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.51%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1        | 0.51%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1        | 0.51%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1        | 0.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 0.51%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.51%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1        | 0.51%   |
| Phison E12 NVMe Controller                                                     | 1        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 103      | 62.42%  |
| NVMe | 34       | 20.61%  |
| IDE  | 15       | 9.09%   |
| RAID | 10       | 6.06%   |
| SAS  | 2        | 1.21%   |
| SCSI | 1        | 0.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 75       | 62.5%   |
| AMD    | 45       | 37.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz            | 6        | 4.96%   |
| Intel N150                                  | 4        | 3.31%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 3.31%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 3.31%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 2.48%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3        | 2.48%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.65%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 2        | 1.65%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.65%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.65%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 1.65%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.65%   |
| AMD Ryzen 5 5500                            | 2        | 1.65%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.65%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.65%   |
| Intel Xeon CPU X5667 @ 3.07GHz              | 1        | 0.83%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.83%   |
| Intel Xeon CPU E5405 @ 2.00GHz              | 1        | 0.83%   |
| Intel Xeon CPU E5-2660 v2 @ 2.20GHz         | 1        | 0.83%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 0.83%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.83%   |
| Intel Xeon CPU E5-1603 v4 @ 2.80GHz         | 1        | 0.83%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.83%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 0.83%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.83%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1        | 0.83%   |
| Intel N100                                  | 1        | 0.83%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 0.83%   |
| Intel Core i9-14900KS                       | 1        | 0.83%   |
| Intel Core i9-14900KF                       | 1        | 0.83%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.83%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.83%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.83%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 1        | 0.83%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.83%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.83%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 0.83%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.83%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 27       | 22.5%   |
| AMD Ryzen 5             | 12       | 10%     |
| Intel Core i3           | 10       | 8.33%   |
| Other                   | 9        | 7.5%    |
| Intel Xeon              | 8        | 6.67%   |
| Intel Core i7           | 7        | 5.83%   |
| AMD Ryzen 3             | 7        | 5.83%   |
| AMD Ryzen 7             | 6        | 5%      |
| AMD FX                  | 6        | 5%      |
| Intel Celeron           | 3        | 2.5%    |
| AMD Ryzen 9             | 3        | 2.5%    |
| Intel Pentium           | 2        | 1.67%   |
| Intel Core i9           | 2        | 1.67%   |
| Intel Core 2 Quad       | 2        | 1.67%   |
| AMD Athlon II X2        | 2        | 1.67%   |
| Intel Pentium Dual-Core | 1        | 0.83%   |
| Intel Pentium 4         | 1        | 0.83%   |
| Intel Core 2 Duo        | 1        | 0.83%   |
| Intel Core 2            | 1        | 0.83%   |
| Intel Atom              | 1        | 0.83%   |
| AMD Sempron             | 1        | 0.83%   |
| AMD Ryzen 7 PRO         | 1        | 0.83%   |
| AMD Phenom II X4        | 1        | 0.83%   |
| AMD E2                  | 1        | 0.83%   |
| AMD E1                  | 1        | 0.83%   |
| AMD A8                  | 1        | 0.83%   |
| AMD A6                  | 1        | 0.83%   |
| AMD A4                  | 1        | 0.83%   |
| AMD A12                 | 1        | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 61       | 50.83%  |
| 6      | 20       | 16.67%  |
| 2      | 17       | 14.17%  |
| 8      | 10       | 8.33%   |
| 1      | 5        | 4.17%   |
| 12     | 2        | 1.67%   |
| 24     | 1        | 0.83%   |
| 20     | 1        | 0.83%   |
| 16     | 1        | 0.83%   |
| 10     | 1        | 0.83%   |
| 3      | 1        | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 118      | 98.33%  |
| 2      | 2        | 1.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 65       | 54.17%  |
| 2      | 55       | 45.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 118      | 98.33%  |
| 32-bit         | 1        | 0.83%   |
| Unknown        | 1        | 0.83%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 59       | 46.09%  |
| 0x306c3    | 10       | 7.81%   |
| 0x906e9    | 5        | 3.91%   |
| 0x306a9    | 5        | 3.91%   |
| 0x08701021 | 4        | 3.13%   |
| 0x506e3    | 3        | 2.34%   |
| 0x08108109 | 3        | 2.34%   |
| 0x906eb    | 2        | 1.56%   |
| 0x306e4    | 2        | 1.56%   |
| 0x10676    | 2        | 1.56%   |
| 0x08101016 | 2        | 1.56%   |
| 0x06000852 | 2        | 1.56%   |
| 0x05000119 | 2        | 1.56%   |
| 0x010000c8 | 2        | 1.56%   |
| 0xf49      | 1        | 0.78%   |
| 0xf29      | 1        | 0.78%   |
| 0x906ec    | 1        | 0.78%   |
| 0x906ea    | 1        | 0.78%   |
| 0x90675    | 1        | 0.78%   |
| 0x90672    | 1        | 0.78%   |
| 0x706a8    | 1        | 0.78%   |
| 0x6f6      | 1        | 0.78%   |
| 0x30678    | 1        | 0.78%   |
| 0x106e5    | 1        | 0.78%   |
| 0x106ca    | 1        | 0.78%   |
| 0x106a5    | 1        | 0.78%   |
| 0x10677    | 1        | 0.78%   |
| 0x0a601201 | 1        | 0.78%   |
| 0x08701011 | 1        | 0.78%   |
| 0x0870100a | 1        | 0.78%   |
| 0x08600109 | 1        | 0.78%   |
| 0x08600106 | 1        | 0.78%   |
| 0x0800820d | 1        | 0.78%   |
| 0x06001119 | 1        | 0.78%   |
| 0x06001116 | 1        | 0.78%   |
| 0x06000822 | 1        | 0.78%   |
| 0x0500010d | 1        | 0.78%   |
| 0x010000c7 | 1        | 0.78%   |
| 0x00000000 | 1        | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 15       | 12.5%   |
| KabyLake         | 14       | 11.67%  |
| Zen 3            | 10       | 8.33%   |
| Zen 2            | 8        | 6.67%   |
| Skylake          | 8        | 6.67%   |
| IvyBridge        | 8        | 6.67%   |
| Piledriver       | 7        | 5.83%   |
| Zen+             | 6        | 5%      |
| Penryn           | 5        | 4.17%   |
| Gracemont        | 5        | 4.17%   |
| Unknown          | 5        | 4.17%   |
| K10              | 4        | 3.33%   |
| CometLake        | 3        | 2.5%    |
| Zen              | 2        | 1.67%   |
| SandyBridge      | 2        | 1.67%   |
| NetBurst         | 2        | 1.67%   |
| Nehalem          | 2        | 1.67%   |
| Bobcat           | 2        | 1.67%   |
| Alderlake Hybrid | 2        | 1.67%   |
| Westmere         | 1        | 0.83%   |
| Steamroller      | 1        | 0.83%   |
| Silvermont       | 1        | 0.83%   |
| Icelake          | 1        | 0.83%   |
| Goldmont plus    | 1        | 0.83%   |
| Excavator        | 1        | 0.83%   |
| Core             | 1        | 0.83%   |
| Bulldozer        | 1        | 0.83%   |
| Broadwell        | 1        | 0.83%   |
| Bonnell          | 1        | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 51       | 37.5%   |
| Nvidia | 47       | 34.56%  |
| AMD    | 38       | 27.94%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 7.8%    |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 7        | 4.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 4.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 4.26%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 3.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 2.84%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 4        | 2.84%   |
| Intel Alder Lake-N [Intel Graphics]                                         | 4        | 2.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 2.84%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 2.13%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.42%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.42%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 1.42%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.42%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.42%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 2        | 1.42%   |
| AMD Raphael                                                                 | 2        | 1.42%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 1.42%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 1.42%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.42%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.42%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.71%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.71%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.71%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.71%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.71%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.71%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 0.71%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 0.71%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.71%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                        | 1        | 0.71%   |
| Nvidia GT218 [ION]                                                          | 1        | 0.71%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.71%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.71%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.71%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 0.71%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.71%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 45       | 36%     |
| 1 x Nvidia     | 40       | 32%     |
| 1 x AMD        | 28       | 22.4%   |
| AMD + Nvidia   | 6        | 4.8%    |
| 2 x AMD        | 4        | 3.2%    |
| Intel + Nvidia | 2        | 1.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 90       | 72.58%  |
| Proprietary | 24       | 19.35%  |
| Unknown     | 10       | 8.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 66       | 51.56%  |
| 1.01-2.0   | 19       | 14.84%  |
| 3.01-4.0   | 11       | 8.59%   |
| 0.51-1.0   | 10       | 7.81%   |
| 0.01-0.5   | 9        | 7.03%   |
| 5.01-6.0   | 5        | 3.91%   |
| 7.01-8.0   | 4        | 3.13%   |
| 8.01-16.0  | 4        | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| AOC                  | 29       | 20.57%  |
| Hewlett-Packard      | 18       | 12.77%  |
| Dell                 | 18       | 12.77%  |
| Goldstar             | 13       | 9.22%   |
| Acer                 | 7        | 4.96%   |
| Samsung Electronics  | 6        | 4.26%   |
| BenQ                 | 6        | 4.26%   |
| ViewSonic            | 5        | 3.55%   |
| Sony                 | 3        | 2.13%   |
| Panasonic            | 3        | 2.13%   |
| MSI                  | 3        | 2.13%   |
| Lenovo               | 3        | 2.13%   |
| AGO                  | 3        | 2.13%   |
| Xiaomi               | 2        | 1.42%   |
| ASUSTek Computer     | 2        | 1.42%   |
| Ancor Communications | 2        | 1.42%   |
| Xerox                | 1        | 0.71%   |
| Unknown (XXX)        | 1        | 0.71%   |
| RTK                  | 1        | 0.71%   |
| Royal Information    | 1        | 0.71%   |
| RGT                  | 1        | 0.71%   |
| Philips              | 1        | 0.71%   |
| Mi                   | 1        | 0.71%   |
| LTM                  | 1        | 0.71%   |
| KTC                  | 1        | 0.71%   |
| ITE                  | 1        | 0.71%   |
| HJW                  | 1        | 0.71%   |
| Hitachi              | 1        | 0.71%   |
| Haier                | 1        | 0.71%   |
| Gigabyte Technology  | 1        | 0.71%   |
| DZX                  | 1        | 0.71%   |
| Denver               | 1        | 0.71%   |
| ASRock               | 1        | 0.71%   |
| ASR                  | 1        | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                       | 5        | 3.27%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                       | 5        | 3.27%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 4        | 2.61%   |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                  | 4        | 2.61%   |
| Dell AW2518HF DELA101 1920x1080 544x303mm 24.5-inch                  | 4        | 2.61%   |
| AOC LCD Monitor AOC2070 1600x900 430x240mm 19.4-inch                 | 3        | 1.96%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                | 3        | 1.96%   |
| Xiaomi Mi TV XMD00E1 1440x900 708x398mm 32.0-inch                    | 2        | 1.31%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 2        | 1.31%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 2        | 1.31%   |
| Lenovo LEN T27h-20 LEN61EC 2560x1440 597x336mm 27.0-inch             | 2        | 1.31%   |
| Hewlett-Packard LCD Monitor E232 2944x1080                           | 2        | 1.31%   |
| Hewlett-Packard L1910 HWP26E6 1280x1024 380x300mm 19.1-inch          | 2        | 1.31%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2        | 1.31%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch           | 2        | 1.31%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch           | 2        | 1.31%   |
| Goldstar FULL HD GSM5B9E 1920x1080 600x340mm 27.2-inch               | 2        | 1.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 1.31%   |
| AOC 1670W AOC1670 1366x768 344x194mm 15.5-inch                       | 2        | 1.31%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                   | 2        | 1.31%   |
| Xerox XA3-17 XER7B10 1280x1024 337x270mm 17.0-inch                   | 1        | 0.65%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch        | 1        | 0.65%   |
| ViewSonic VA2231 Series VSCBB25 1920x1080 477x268mm 21.5-inch        | 1        | 0.65%   |
| ViewSonic VA1703wb-2 VSCA21F 1440x900 367x230mm 17.1-inch            | 1        | 0.65%   |
| ViewSonic LCD Monitor VX2458-mhd 3286x1080                           | 1        | 0.65%   |
| ViewSonic LCD Monitor VX2260WM                                       | 1        | 0.65%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 0.65%   |
| Sony TV SNY5703 1920x1080                                            | 1        | 0.65%   |
| Sony TV SNY1B02 1360x768                                             | 1        | 0.65%   |
| Sony TV SNY0902 1360x768                                             | 1        | 0.65%   |
| Samsung Electronics S24A31x SAM7115 1920x1080 527x296mm 23.8-inch    | 1        | 0.65%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch | 1        | 0.65%   |
| Samsung Electronics LC34G55T SAM7119 3440x1440 798x334mm 34.1-inch   | 1        | 0.65%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1        | 0.65%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                    | 1        | 0.65%   |
| Royal Information Monitor TRL1012 1280x1024 320x240mm 15.7-inch      | 1        | 0.65%   |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                | 1        | 0.65%   |
| Philips LCD Monitor 170B4 1280x1024                                  | 1        | 0.65%   |
| Panasonic TV MEIC13C 1280x720 708x398mm 32.0-inch                    | 1        | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 60       | 43.17%  |
| 1366x768 (WXGA)   | 19       | 13.67%  |
| 3840x2160 (4K)    | 11       | 7.91%   |
| 1600x900 (HD+)    | 9        | 6.47%   |
| 1280x1024 (SXGA)  | 8        | 5.76%   |
| 2560x1440 (QHD)   | 7        | 5.04%   |
| 1440x900 (WXGA+)  | 7        | 5.04%   |
| 1280x720 (HD)     | 3        | 2.16%   |
| 3440x1440         | 2        | 1.44%   |
| 3286x1080         | 2        | 1.44%   |
| 2944x1080         | 2        | 1.44%   |
| 2560x1080         | 2        | 1.44%   |
| Unknown           | 2        | 1.44%   |
| 1920x540          | 1        | 0.72%   |
| 1920x1200 (WUXGA) | 1        | 0.72%   |
| 1400x1050         | 1        | 0.72%   |
| 1360x768          | 1        | 0.72%   |
| 1280x960          | 1        | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 20       | 14.08%  |
| 23      | 17       | 11.97%  |
| 19      | 15       | 10.56%  |
| 21      | 14       | 9.86%   |
| 18      | 13       | 9.15%   |
| 27      | 9        | 6.34%   |
| Unknown | 9        | 6.34%   |
| 15      | 7        | 4.93%   |
| 17      | 5        | 3.52%   |
| 72      | 4        | 2.82%   |
| 34      | 3        | 2.11%   |
| 31      | 3        | 2.11%   |
| 12      | 3        | 2.11%   |
| 84      | 2        | 1.41%   |
| 65      | 2        | 1.41%   |
| 43      | 2        | 1.41%   |
| 40      | 2        | 1.41%   |
| 32      | 2        | 1.41%   |
| 26      | 2        | 1.41%   |
| 20      | 2        | 1.41%   |
| 63      | 1        | 0.7%    |
| 54      | 1        | 0.7%    |
| 49      | 1        | 0.7%    |
| 44      | 1        | 0.7%    |
| 36      | 1        | 0.7%    |
| 22      | 1        | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 46       | 33.82%  |
| 401-500     | 38       | 27.94%  |
| 301-350     | 11       | 8.09%   |
| Unknown     | 9        | 6.62%   |
| 701-800     | 6        | 4.41%   |
| 1501-2000   | 6        | 4.41%   |
| 1001-1500   | 5        | 3.68%   |
| 351-400     | 4        | 2.94%   |
| 601-700     | 3        | 2.21%   |
| 201-300     | 3        | 2.21%   |
| 901-1000    | 3        | 2.21%   |
| 801-900     | 2        | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 88       | 72.13%  |
| 16/10   | 9        | 7.38%   |
| Unknown | 9        | 7.38%   |
| 5/4     | 7        | 5.74%   |
| 4/3     | 5        | 4.1%    |
| 21/9    | 3        | 2.46%   |
| 32/9    | 1        | 0.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 37       | 26.06%  |
| 151-200        | 22       | 15.49%  |
| 141-150        | 16       | 11.27%  |
| 251-300        | 12       | 8.45%   |
| More than 1000 | 10       | 7.04%   |
| 301-350        | 10       | 7.04%   |
| Unknown        | 9        | 6.34%   |
| 351-500        | 8        | 5.63%   |
| 501-1000       | 7        | 4.93%   |
| 101-110        | 5        | 3.52%   |
| 71-80          | 3        | 2.11%   |
| 131-140        | 1        | 0.7%    |
| 111-120        | 1        | 0.7%    |
| 91-100         | 1        | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 81       | 61.36%  |
| 101-120 | 27       | 20.45%  |
| 1-50    | 9        | 6.82%   |
| Unknown | 9        | 6.82%   |
| 161-240 | 4        | 3.03%   |
| 121-160 | 2        | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 90       | 72%     |
| 2     | 27       | 21.6%   |
| 0     | 7        | 5.6%    |
| 3     | 1        | 0.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 87       | 51.79%  |
| Intel                           | 38       | 22.62%  |
| Qualcomm Atheros                | 8        | 4.76%   |
| TP-Link                         | 6        | 3.57%   |
| MediaTek                        | 5        | 2.98%   |
| Broadcom                        | 4        | 2.38%   |
| Ralink                          | 3        | 1.79%   |
| Nvidia                          | 3        | 1.79%   |
| Xiaomi                          | 2        | 1.19%   |
| Ralink Technology               | 2        | 1.19%   |
| Linksys                         | 2        | 1.19%   |
| Huawei Technologies             | 2        | 1.19%   |
| D-Link                          | 2        | 1.19%   |
| Qualcomm Technologies           | 1        | 0.6%    |
| Qualcomm Atheros Communications | 1        | 0.6%    |
| Davicom Semiconductor           | 1        | 0.6%    |
| Broadcom Limited                | 1        | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 68       | 35.42%  |
| Realtek RTL8125 2.5GbE Controller                                      | 6        | 3.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5        | 2.6%    |
| Intel Ethernet Controller I225-V                                       | 5        | 2.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4        | 2.08%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 3        | 1.56%   |
| Realtek 802.11ac NIC                                                   | 3        | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3        | 1.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 3        | 1.56%   |
| Intel Ethernet Controller I226-V                                       | 3        | 1.56%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 1.56%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 1.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 1.04%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 2        | 1.04%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 2        | 1.04%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller              | 2        | 1.04%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 1.04%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 1.04%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2        | 1.04%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2        | 1.04%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 1.04%   |
| Intel Ethernet Connection (2) I218-LM                                  | 2        | 1.04%   |
| Intel Centrino Advanced-N 6235                                         | 2        | 1.04%   |
| Huawei FOA-LX9                                                         | 2        | 1.04%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2        | 1.04%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                              | 1        | 0.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.52%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1        | 0.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1        | 0.52%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1        | 0.52%   |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller            | 1        | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 0.52%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1        | 0.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1        | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 0.52%   |
| Realtek RTL8126 5GbE Controller                                        | 1        | 0.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 0.52%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 24       | 38.1%   |
| Intel                           | 12       | 19.05%  |
| TP-Link                         | 6        | 9.52%   |
| Qualcomm Atheros                | 5        | 7.94%   |
| MediaTek                        | 5        | 7.94%   |
| Ralink                          | 3        | 4.76%   |
| Ralink Technology               | 2        | 3.17%   |
| Linksys                         | 2        | 3.17%   |
| D-Link                          | 2        | 3.17%   |
| Qualcomm Technologies           | 1        | 1.59%   |
| Qualcomm Atheros Communications | 1        | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 5        | 7.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 6.25%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3        | 4.69%   |
| Realtek 802.11ac NIC                                                                          | 3        | 4.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 3        | 4.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 3        | 4.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2        | 3.13%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 2        | 3.13%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 2        | 3.13%   |
| Ralink MT7601U Wireless Adapter                                                               | 2        | 3.13%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 2        | 3.13%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 2        | 3.13%   |
| Intel Centrino Advanced-N 6235                                                                | 2        | 3.13%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 1.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 1.56%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 1.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 1.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 1        | 1.56%   |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller                                   | 1        | 1.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1        | 1.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 1.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 1.56%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.56%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1        | 1.56%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1        | 1.56%   |
| Ralink RT2800 802.11n PCI                                                                     | 1        | 1.56%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]                              | 1        | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1        | 1.56%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 1.56%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 1.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 1        | 1.56%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]                          | 1        | 1.56%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]                                | 1        | 1.56%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1        | 1.56%   |
| Intel Wireless 8260                                                                           | 1        | 1.56%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2                               | 1        | 1.56%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 1        | 1.56%   |
| Intel 700 Series Chipset CNVi WiFi                                                            | 1        | 1.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 79       | 62.7%   |
| Intel                 | 31       | 24.6%   |
| Broadcom              | 4        | 3.17%   |
| Qualcomm Atheros      | 3        | 2.38%   |
| Nvidia                | 3        | 2.38%   |
| Xiaomi                | 2        | 1.59%   |
| Huawei Technologies   | 2        | 1.59%   |
| Davicom Semiconductor | 1        | 0.79%   |
| Broadcom Limited      | 1        | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 68       | 53.13%  |
| Realtek RTL8125 2.5GbE Controller                                      | 6        | 4.69%   |
| Intel Ethernet Controller I225-V                                       | 5        | 3.91%   |
| Intel Ethernet Controller I226-V                                       | 3        | 2.34%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 2.34%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 2.34%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 2.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 2.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 1.56%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 1.56%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 1.56%   |
| Intel Ethernet Connection (2) I218-LM                                  | 2        | 1.56%   |
| Huawei FOA-LX9                                                         | 2        | 1.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2        | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 0.78%   |
| Realtek RTL8126 5GbE Controller                                        | 1        | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 0.78%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1        | 0.78%   |
| Nvidia MCP79 Ethernet                                                  | 1        | 0.78%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 0.78%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.78%   |
| Intel 82801DB PRO/100 VE (CNR) Ethernet Controller                     | 1        | 0.78%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 0.78%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 0.78%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                   | 1        | 0.78%   |
| Davicom DM9102 Fast Ethernet Controller                                | 1        | 0.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1        | 0.78%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 1        | 0.78%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express        | 1        | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 119      | 67.61%  |
| WiFi     | 57       | 32.39%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 72.87%  |
| WiFi     | 35       | 27.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 75       | 61.48%  |
| 2     | 42       | 34.43%  |
| 4     | 3        | 2.46%   |
| 3     | 2        | 1.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 118      | 97.52%  |
| Yes  | 3        | 2.48%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 13       | 30.95%  |
| Intel                   | 11       | 26.19%  |
| Realtek Semiconductor   | 6        | 14.29%  |
| MediaTek                | 3        | 7.14%   |
| ASUSTek Computer        | 3        | 7.14%   |
| TP-Link                 | 2        | 4.76%   |
| Foxconn / Hon Hai       | 2        | 4.76%   |
| IMC Networks            | 1        | 2.38%   |
| Broadcom                | 1        | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 13       | 30.95%  |
| Realtek Bluetooth Radio                                      | 6        | 14.29%  |
| MediaTek Wireless_Device                                     | 3        | 7.14%   |
| TP-Link TP-T@- UB500 Adapter                                 | 2        | 4.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 2        | 4.76%   |
| Intel Centrino Bluetooth Wireless Transceiver                | 2        | 4.76%   |
| Intel AX210 Bluetooth                                        | 2        | 4.76%   |
| Foxconn / Hon Hai Bluetooth Device                           | 2        | 4.76%   |
| Intel Bluetooth wireless interface                           | 1        | 2.38%   |
| Intel Bluetooth Device                                       | 1        | 2.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 1        | 2.38%   |
| Intel AX201 Bluetooth                                        | 1        | 2.38%   |
| Intel AX200 Bluetooth                                        | 1        | 2.38%   |
| IMC Networks Bluetooth Radio                                 | 1        | 2.38%   |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 1        | 2.38%   |
| ASUS Qualcomm Bluetooth 4.1                                  | 1        | 2.38%   |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 1        | 2.38%   |
| ASUS Bluetooth Radio                                         | 1        | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 72       | 37.11%  |
| AMD                                          | 51       | 26.29%  |
| Nvidia                                       | 45       | 23.2%   |
| C-Media Electronics                          | 5        | 2.58%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 1.03%   |
| Logitech                                     | 2        | 1.03%   |
| GN Netcom                                    | 2        | 1.03%   |
| Unknown                                      | 1        | 0.52%   |
| Soundprese                                   | 1        | 0.52%   |
| Sony                                         | 1        | 0.52%   |
| Realtek Semiconductor                        | 1        | 0.52%   |
| Micro Star International                     | 1        | 0.52%   |
| Medeli Electronics                           | 1        | 0.52%   |
| Kingston Technology                          | 1        | 0.52%   |
| Giga-Byte Technology                         | 1        | 0.52%   |
| Ensoniq                                      | 1        | 0.52%   |
| Creative Labs                                | 1        | 0.52%   |
| Corsair                                      | 1        | 0.52%   |
| BEHRINGER International                      | 1        | 0.52%   |
| Astro Gaming                                 | 1        | 0.52%   |
| Argosy Research                              | 1        | 0.52%   |
| A-DATA Technology                            | 1        | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Ryzen HD Audio Controller                                              | 16       | 6.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 5.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11       | 4.62%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11       | 4.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 4.2%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 9        | 3.78%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 7        | 2.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 2.94%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 2.52%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 2.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 2.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 2.1%    |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 5        | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 2.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 2.1%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 2.1%    |
| Nvidia High Definition Audio Controller                                    | 4        | 1.68%   |
| AMD FCH Azalia Controller                                                  | 4        | 1.68%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.26%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 1.26%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 1.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.26%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 1.26%   |
| AMD Radeon High Definition Audio Controller                                | 3        | 1.26%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 2        | 0.84%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.84%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.84%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.84%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.84%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 0.84%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2        | 0.84%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.84%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 0.84%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 0.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 0.84%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 14       | 16.28%  |
| SK hynix                     | 12       | 13.95%  |
| Micron Technology            | 11       | 12.79%  |
| Samsung Electronics          | 7        | 8.14%   |
| G.Skill                      | 7        | 8.14%   |
| A-DATA Technology            | 7        | 8.14%   |
| Corsair                      | 6        | 6.98%   |
| Unknown                      | 5        | 5.81%   |
| Crucial                      | 5        | 5.81%   |
| Unknown (0x0FF4)             | 2        | 2.33%   |
| Team                         | 2        | 2.33%   |
| Ramaxel Technology           | 2        | 2.33%   |
| V-Color                      | 1        | 1.16%   |
| Ramos Technology             | 1        | 1.16%   |
| Patriot Memory (PDP Systems) | 1        | 1.16%   |
| Patriot                      | 1        | 1.16%   |
| Kimtigo                      | 1        | 1.16%   |
| Unknown                      | 1        | 1.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                    | 5        | 5.21%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s                  | 3        | 3.13%   |
| Unknown RAM 3600 C18 Series 16GB DIMM DDR4 2933MT/s                    | 2        | 2.08%   |
| Unknown (0x0FF4) RAM SS42J04NAR-16 16GB SODIMM DDR4 2667MT/s           | 2        | 2.08%   |
| SK hynix RAM Module 3GB Row Of Chips LPDDR5 4800MT/s                   | 2        | 2.08%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s                   | 2        | 2.08%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                   | 2        | 2.08%   |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s                   | 2        | 2.08%   |
| A-DATA RAM Module 16GB DIMM DDR4 2667MT/s                              | 2        | 2.08%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s                           | 2        | 2.08%   |
| V-Color RAM TN4G8C11-H11 4GB DIMM DDR3 1600MT/s                        | 1        | 1.04%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                              | 1        | 1.04%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                   | 1        | 1.04%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                             | 1        | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                          | 1        | 1.04%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s                     | 1        | 1.04%   |
| Team RAM Module 8GB DIMM DDR4 2133MT/s                                 | 1        | 1.04%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                            | 1        | 1.04%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s                   | 1        | 1.04%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                   | 1        | 1.04%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s                   | 1        | 1.04%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s                   | 1        | 1.04%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s                   | 1        | 1.04%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                 | 1        | 1.04%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s                   | 1        | 1.04%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s                 | 1        | 1.04%   |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1866MT/s                       | 1        | 1.04%   |
| Samsung RAM M393A1G40DB1-CRC 8GB DIMM DDR4 2400MT/s                    | 1        | 1.04%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s                    | 1        | 1.04%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s                    | 1        | 1.04%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s                    | 1        | 1.04%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s                    | 1        | 1.04%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                    | 1        | 1.04%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s                   | 1        | 1.04%   |
| Ramos RAM EWB8GB681PAE-16IC 4GB DIMM DDR3 1600MT/s                     | 1        | 1.04%   |
| Ramaxel RAM RMR5030MJ68F9F1600 4GB DIMM DDR3 1600MT/s                  | 1        | 1.04%   |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s                  | 1        | 1.04%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                        | 1        | 1.04%   |
| Patriot Memory (PDP Systems) RAM PSD416G320081 16GB DIMM DDR4 3200MT/s | 1        | 1.04%   |
| Micron RAM Module 4GB Row Of Chips LPDDR5 6400MT/s                     | 1        | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 36       | 51.43%  |
| DDR3    | 23       | 32.86%  |
| SDRAM   | 4        | 5.71%   |
| LPDDR5  | 3        | 4.29%   |
| DDR5    | 2        | 2.86%   |
| DDR2    | 1        | 1.43%   |
| Unknown | 1        | 1.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 57       | 85.07%  |
| SODIMM       | 7        | 10.45%  |
| Row Of Chips | 3        | 4.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 26       | 35.14%  |
| 4096  | 19       | 25.68%  |
| 16384 | 14       | 18.92%  |
| 32768 | 7        | 9.46%   |
| 2048  | 6        | 8.11%   |
| 3072  | 2        | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 19       | 23.46%  |
| 2667  | 9        | 11.11%  |
| 3600  | 6        | 7.41%   |
| 2400  | 6        | 7.41%   |
| 1333  | 6        | 7.41%   |
| 4800  | 3        | 3.7%    |
| 3866  | 3        | 3.7%    |
| 3200  | 3        | 3.7%    |
| 2933  | 3        | 3.7%    |
| 2133  | 3        | 3.7%    |
| 667   | 2        | 2.47%   |
| 6400  | 1        | 1.23%   |
| 6200  | 1        | 1.23%   |
| 4333  | 1        | 1.23%   |
| 4000  | 1        | 1.23%   |
| 3800  | 1        | 1.23%   |
| 3733  | 1        | 1.23%   |
| 3466  | 1        | 1.23%   |
| 3400  | 1        | 1.23%   |
| 3100  | 1        | 1.23%   |
| 3066  | 1        | 1.23%   |
| 2934  | 1        | 1.23%   |
| 2666  | 1        | 1.23%   |
| 2465  | 1        | 1.23%   |
| 2448  | 1        | 1.23%   |
| 2000  | 1        | 1.23%   |
| 1867  | 1        | 1.23%   |
| 1866  | 1        | 1.23%   |
| 1800  | 1        | 1.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 4        | 50%     |
| Seiko Epson     | 2        | 25%     |
| Canon           | 2        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seiko Epson L3110 Series        | 2        | 25%     |
| HP Ink Tank Wireless 410 series | 1        | 12.5%   |
| HP DeskJet 2600 series          | 1        | 12.5%   |
| HP DeskJet 2130 series          | 1        | 12.5%   |
| HP Deskjet 2050 J510            | 1        | 12.5%   |
| Canon G2000 series              | 1        | 12.5%   |
| Canon E400 series               | 1        | 12.5%   |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 7        | 29.17%  |
| Microdia                | 5        | 20.83%  |
| Microsoft               | 3        | 12.5%   |
| Chicony Electronics     | 2        | 8.33%   |
| Z-Star Microelectronics | 1        | 4.17%   |
| TANDBERG                | 1        | 4.17%   |
| Philips (or NXP)        | 1        | 4.17%   |
| Jieli Technology        | 1        | 4.17%   |
| Huawei Technologies     | 1        | 4.17%   |
| Aveo Technology         | 1        | 4.17%   |
| Arkmicro Technologies   | 1        | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 4        | 16.67%  |
| Microsoft LifeCam HD-3000             | 2        | 8.33%   |
| Microdia USB 2.0 Camera               | 2        | 8.33%   |
| Microdia Integrated Camera            | 2        | 8.33%   |
| Z-Star A4 TECH USB2.0 PC Camera E     | 1        | 4.17%   |
| TANDBERG PrecisionHD Camera           | 1        | 4.17%   |
| Philips (or NXP) SPC 1300NC PC Camera | 1        | 4.17%   |
| Microsoft LifeCam Cinema              | 1        | 4.17%   |
| Microdia Webcam Vitade AF             | 1        | 4.17%   |
| Logitech Webcam Pro 9000              | 1        | 4.17%   |
| Logitech Webcam C310                  | 1        | 4.17%   |
| Logitech HD Pro Webcam C920           | 1        | 4.17%   |
| Jieli USB PHY 2.0                     | 1        | 4.17%   |
| Huawei HiCamera                       | 1        | 4.17%   |
| Chicony HP High Definition 1MP Webcam | 1        | 4.17%   |
| Chicony HP 720p HD Monitor Webcam     | 1        | 4.17%   |
| Aveo USB2.0 UVC PC Camera             | 1        | 4.17%   |
| Arkmicro USB2.0 PC CAMERA             | 1        | 4.17%   |

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


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| SCM Microsystems           | 1        | 33.33%  |
| OmniKey                    | 1        | 33.33%  |
| Athena Smartcard Solutions | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 33.33%  |
| OmniKey CardMan 3021 / 3121                            | 1        | 33.33%  |
| Athena Smartcard Solutions ASEDrive V3C                | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 100      | 81.97%  |
| 1     | 18       | 14.75%  |
| 3     | 2        | 1.64%   |
| 2     | 2        | 1.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 10       | 37.04%  |
| Net/wireless             | 6        | 22.22%  |
| Communication controller | 3        | 11.11%  |
| Chipcard                 | 3        | 11.11%  |
| Unassigned class         | 2        | 7.41%   |
| Storage/raid             | 1        | 3.7%    |
| Sound                    | 1        | 3.7%    |
| Network                  | 1        | 3.7%    |

