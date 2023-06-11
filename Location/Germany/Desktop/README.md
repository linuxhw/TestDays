Linux in Germany - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Germany.

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

Total: 11955

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | H57M-USB3                   | [91b1655f60](https://linux-hardware.org/?probe=91b1655f60) | Jun 10, 2023 |
| ASRock        | H61M-DGS R2.0               | [cc206f52b1](https://linux-hardware.org/?probe=cc206f52b1) | Jun 10, 2023 |
| HP            | 2B4B                        | [3ade78a07e](https://linux-hardware.org/?probe=3ade78a07e) | Jun 10, 2023 |
| HP            | 2B4B                        | [2da60252b5](https://linux-hardware.org/?probe=2da60252b5) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [08114e8a97](https://linux-hardware.org/?probe=08114e8a97) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [93555cfd25](https://linux-hardware.org/?probe=93555cfd25) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [2e6d82c14f](https://linux-hardware.org/?probe=2e6d82c14f) | Jun 10, 2023 |
| Seco          | C40 C                       | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| ASRock        | B360M Pro4                  | [9b52b20f3e](https://linux-hardware.org/?probe=9b52b20f3e) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [afa2a30d75](https://linux-hardware.org/?probe=afa2a30d75) | Jun 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [a1877cb5b3](https://linux-hardware.org/?probe=a1877cb5b3) | Jun 09, 2023 |
| ASRock        | H61M-DGS R2.0               | [37c25e136f](https://linux-hardware.org/?probe=37c25e136f) | Jun 09, 2023 |
| Gigabyte      | B550M DS3H                  | [ea724e204b](https://linux-hardware.org/?probe=ea724e204b) | Jun 09, 2023 |
| MSI           | 970A-G46                    | [e4471b7a38](https://linux-hardware.org/?probe=e4471b7a38) | Jun 09, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [6491127e6e](https://linux-hardware.org/?probe=6491127e6e) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [f9677c0861](https://linux-hardware.org/?probe=f9677c0861) | Jun 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [cc1f571000](https://linux-hardware.org/?probe=cc1f571000) | Jun 09, 2023 |
| Gigabyte      | Q87M-D2H                    | [56421d7b0f](https://linux-hardware.org/?probe=56421d7b0f) | Jun 09, 2023 |
| ASUSTek       | M4A785G-HTPC                | [76304dfb4a](https://linux-hardware.org/?probe=76304dfb4a) | Jun 09, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | [9fb55abc56](https://linux-hardware.org/?probe=9fb55abc56) | Jun 08, 2023 |
| MSI           | H110M PRO-D                 | [ad5baed526](https://linux-hardware.org/?probe=ad5baed526) | Jun 08, 2023 |
| Gigabyte      | B75M-D3H                    | [8c84a543bf](https://linux-hardware.org/?probe=8c84a543bf) | Jun 08, 2023 |
| Dell          | 0GDG8Y A00                  | [4789561d79](https://linux-hardware.org/?probe=4789561d79) | Jun 08, 2023 |
| Inventec      | VXC Class A02               | [c2bc26120f](https://linux-hardware.org/?probe=c2bc26120f) | Jun 08, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [1d84d556bf](https://linux-hardware.org/?probe=1d84d556bf) | Jun 07, 2023 |
| Gigabyte      | B85M-D3H                    | [befd126f43](https://linux-hardware.org/?probe=befd126f43) | Jun 07, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | [f836a7d0ff](https://linux-hardware.org/?probe=f836a7d0ff) | Jun 07, 2023 |
| Gigabyte      | B85M-D3H                    | [e146923f12](https://linux-hardware.org/?probe=e146923f12) | Jun 07, 2023 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | [1d36e85f27](https://linux-hardware.org/?probe=1d36e85f27) | Jun 07, 2023 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | [b18ffc5311](https://linux-hardware.org/?probe=b18ffc5311) | Jun 07, 2023 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [bcb9105121](https://linux-hardware.org/?probe=bcb9105121) | Jun 06, 2023 |
| Gigabyte      | Z390 UD                     | [1bf88bda62](https://linux-hardware.org/?probe=1bf88bda62) | Jun 06, 2023 |
| HP            | 2820h                       | [eb7322ad95](https://linux-hardware.org/?probe=eb7322ad95) | Jun 06, 2023 |
| Gigabyte      | Q87M-D2H                    | [05a3b3210a](https://linux-hardware.org/?probe=05a3b3210a) | Jun 06, 2023 |
| Gigabyte      | Z590 VISION G               | [ee1abb360e](https://linux-hardware.org/?probe=ee1abb360e) | Jun 06, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [9286154198](https://linux-hardware.org/?probe=9286154198) | Jun 05, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [91ee57c108](https://linux-hardware.org/?probe=91ee57c108) | Jun 05, 2023 |
| Gigabyte      | Q87M-D2H                    | [eeaf6dbd4c](https://linux-hardware.org/?probe=eeaf6dbd4c) | Jun 05, 2023 |
| ASRock        | N68C-S UCC                  | [741e39b142](https://linux-hardware.org/?probe=741e39b142) | Jun 05, 2023 |
| Gigabyte      | B85M-D3H                    | [0bd595e07a](https://linux-hardware.org/?probe=0bd595e07a) | Jun 04, 2023 |
| Medion        | TJ4125                      | [3faed0102f](https://linux-hardware.org/?probe=3faed0102f) | Jun 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | [0bd883cae2](https://linux-hardware.org/?probe=0bd883cae2) | Jun 04, 2023 |
| HP            | 1495                        | [0cbf6bee1f](https://linux-hardware.org/?probe=0cbf6bee1f) | Jun 04, 2023 |
| ASRock        | A75M-HVS                    | [69bc52dc4f](https://linux-hardware.org/?probe=69bc52dc4f) | Jun 04, 2023 |
| Biostar       | B350GT5                     | [18e1da8cce](https://linux-hardware.org/?probe=18e1da8cce) | Jun 04, 2023 |
| Biostar       | B350GT5                     | [123beb390f](https://linux-hardware.org/?probe=123beb390f) | Jun 04, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [60749b6e47](https://linux-hardware.org/?probe=60749b6e47) | Jun 04, 2023 |
| HP            | 2B43                        | [d66cd5f48e](https://linux-hardware.org/?probe=d66cd5f48e) | Jun 04, 2023 |
| ASUSTek       | P5Q-PRO                     | [76cd01b045](https://linux-hardware.org/?probe=76cd01b045) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [51868dd3c8](https://linux-hardware.org/?probe=51868dd3c8) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| ASUSTek       | Z170-A                      | [4f512af4c2](https://linux-hardware.org/?probe=4f512af4c2) | Jun 03, 2023 |
| ASRock        | H81M-HDS                    | [248372dd54](https://linux-hardware.org/?probe=248372dd54) | Jun 03, 2023 |
| Medion        | TJ4125                      | [6244ae0e43](https://linux-hardware.org/?probe=6244ae0e43) | Jun 02, 2023 |
| Gigabyte      | B85M-D3H                    | [908f094e9d](https://linux-hardware.org/?probe=908f094e9d) | Jun 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [914fa73266](https://linux-hardware.org/?probe=914fa73266) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [25721b28d3](https://linux-hardware.org/?probe=25721b28d3) | Jun 02, 2023 |
| HC Technol... | HCAR357-NR                  | [58f698b10a](https://linux-hardware.org/?probe=58f698b10a) | Jun 02, 2023 |
| ASUSTek       | Z87-C                       | [20242d8299](https://linux-hardware.org/?probe=20242d8299) | Jun 02, 2023 |
| ASUSTek       | B85M-E                      | [ba95473e9c](https://linux-hardware.org/?probe=ba95473e9c) | Jun 02, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | [c716b12ee2](https://linux-hardware.org/?probe=c716b12ee2) | Jun 02, 2023 |
| Gigabyte      | B85-HD3                     | [9931f8e663](https://linux-hardware.org/?probe=9931f8e663) | Jun 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [7baed02e0e](https://linux-hardware.org/?probe=7baed02e0e) | Jun 01, 2023 |
| Gigabyte      | H61M-S2PV                   | [6c86bd69e0](https://linux-hardware.org/?probe=6c86bd69e0) | Jun 01, 2023 |
| Gigabyte      | Q87M-D2H                    | [8f3525a119](https://linux-hardware.org/?probe=8f3525a119) | Jun 01, 2023 |
| Gigabyte      | Z390 UD                     | [b66cbe20f8](https://linux-hardware.org/?probe=b66cbe20f8) | Jun 01, 2023 |
| Gigabyte      | Z390 UD                     | [3cca879110](https://linux-hardware.org/?probe=3cca879110) | Jun 01, 2023 |
| ASUSTek       | B85M-E                      | [57f47246aa](https://linux-hardware.org/?probe=57f47246aa) | Jun 01, 2023 |
| ASRock        | H81M-HDS                    | [775913e245](https://linux-hardware.org/?probe=775913e245) | Jun 01, 2023 |
| Inventec      | D CLASS A02                 | [433df815db](https://linux-hardware.org/?probe=433df815db) | Jun 01, 2023 |
| MSI           | P55-GD55                    | [1400fdf705](https://linux-hardware.org/?probe=1400fdf705) | May 31, 2023 |
| HP            | 1497                        | [cc138de04b](https://linux-hardware.org/?probe=cc138de04b) | May 31, 2023 |
| Gigabyte      | Q87M-D2H                    | [7400ec0f1a](https://linux-hardware.org/?probe=7400ec0f1a) | May 31, 2023 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [c0ff761729](https://linux-hardware.org/?probe=c0ff761729) | May 31, 2023 |
| ASUSTek       | P5Q                         | [e936e44332](https://linux-hardware.org/?probe=e936e44332) | May 31, 2023 |
| ASUSTek       | B85M-E                      | [08e31c6634](https://linux-hardware.org/?probe=08e31c6634) | May 31, 2023 |
| ZOTAC         | Unknown                     | [0626de1b2a](https://linux-hardware.org/?probe=0626de1b2a) | May 31, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2703e7856e](https://linux-hardware.org/?probe=2703e7856e) | May 30, 2023 |
| ASRock        | Q1900B-ITX                  | [88e4924fa2](https://linux-hardware.org/?probe=88e4924fa2) | May 30, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [45e5adbb22](https://linux-hardware.org/?probe=45e5adbb22) | May 30, 2023 |
| Dell          | 002KVM A01                  | [09d2d63c82](https://linux-hardware.org/?probe=09d2d63c82) | May 30, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [e51651a755](https://linux-hardware.org/?probe=e51651a755) | May 30, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ffbccb8f47](https://linux-hardware.org/?probe=ffbccb8f47) | May 30, 2023 |
| Gigabyte      | Q87M-D2H                    | [5e7eb5b41c](https://linux-hardware.org/?probe=5e7eb5b41c) | May 29, 2023 |
| Inventec      | VXC Class A02               | [0befe25313](https://linux-hardware.org/?probe=0befe25313) | May 29, 2023 |
| ASUSTek       | B85M-E                      | [eea74e88a5](https://linux-hardware.org/?probe=eea74e88a5) | May 29, 2023 |
| Inventec      | VXC Class A02               | [363827ad8c](https://linux-hardware.org/?probe=363827ad8c) | May 29, 2023 |
| MSI           | 970A-G46                    | [180eb351d7](https://linux-hardware.org/?probe=180eb351d7) | May 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [d98102f69a](https://linux-hardware.org/?probe=d98102f69a) | May 29, 2023 |
| HP            | 82F2 A01                    | [fb729f1358](https://linux-hardware.org/?probe=fb729f1358) | May 29, 2023 |
| Packard Be... | MCP73                       | [e180017a10](https://linux-hardware.org/?probe=e180017a10) | May 29, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [16b9dfbbe0](https://linux-hardware.org/?probe=16b9dfbbe0) | May 29, 2023 |
| Gigabyte      | Z77X-UD5H                   | [e947dd7da1](https://linux-hardware.org/?probe=e947dd7da1) | May 29, 2023 |
| MSI           | P67A-GD65                   | [fe5e3bcd7b](https://linux-hardware.org/?probe=fe5e3bcd7b) | May 29, 2023 |
| ASUSTek       | Z10PA-D8 Series             | [02821a3220](https://linux-hardware.org/?probe=02821a3220) | May 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | [f4a8ca4825](https://linux-hardware.org/?probe=f4a8ca4825) | May 29, 2023 |
| ASRock        | J4105-ITX                   | [570bc894da](https://linux-hardware.org/?probe=570bc894da) | May 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9e0fc265de](https://linux-hardware.org/?probe=9e0fc265de) | May 29, 2023 |
| ASRock        | 970 Pro3 R2.0               | [a9ff8334b4](https://linux-hardware.org/?probe=a9ff8334b4) | May 28, 2023 |
| ASRock        | 970 Pro3 R2.0               | [4ae997cf6b](https://linux-hardware.org/?probe=4ae997cf6b) | May 28, 2023 |
| Gigabyte      | J4005ND2P-CF                | [ccc5d73179](https://linux-hardware.org/?probe=ccc5d73179) | May 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [dbb348e8bf](https://linux-hardware.org/?probe=dbb348e8bf) | May 28, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [ccf71ca66c](https://linux-hardware.org/?probe=ccf71ca66c) | May 27, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [1a3a921775](https://linux-hardware.org/?probe=1a3a921775) | May 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [6465343084](https://linux-hardware.org/?probe=6465343084) | May 27, 2023 |
| MSI           | A55M-E33                    | [c25cb7cbb6](https://linux-hardware.org/?probe=c25cb7cbb6) | May 27, 2023 |
| ASRock        | H87M Pro4                   | [efd2db0783](https://linux-hardware.org/?probe=efd2db0783) | May 27, 2023 |
| Dell          | 00V62H A01                  | [0d8c590c8d](https://linux-hardware.org/?probe=0d8c590c8d) | May 27, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [b82f4b77f4](https://linux-hardware.org/?probe=b82f4b77f4) | May 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [4862d28e3f](https://linux-hardware.org/?probe=4862d28e3f) | May 26, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6bcf3cf056](https://linux-hardware.org/?probe=6bcf3cf056) | May 26, 2023 |
| HP            | 0AA4h                       | [41ec821e77](https://linux-hardware.org/?probe=41ec821e77) | May 26, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [5d54a10d85](https://linux-hardware.org/?probe=5d54a10d85) | May 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [e29fb14e81](https://linux-hardware.org/?probe=e29fb14e81) | May 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [84d0d9807f](https://linux-hardware.org/?probe=84d0d9807f) | May 26, 2023 |
| Fujitsu Si... | D2464-A1 S26361-D2464-A1    | [313c8a3663](https://linux-hardware.org/?probe=313c8a3663) | May 26, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [f757bc2c6e](https://linux-hardware.org/?probe=f757bc2c6e) | May 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [1c62418caf](https://linux-hardware.org/?probe=1c62418caf) | May 25, 2023 |
| MSI           | Z590 PLUS                   | [1f531f4e58](https://linux-hardware.org/?probe=1f531f4e58) | May 25, 2023 |
| Gigabyte      | Q87M-D2H                    | [a3e5c89fe6](https://linux-hardware.org/?probe=a3e5c89fe6) | May 25, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [c2d85ba655](https://linux-hardware.org/?probe=c2d85ba655) | May 25, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [94da2a33fe](https://linux-hardware.org/?probe=94da2a33fe) | May 25, 2023 |
| ASUSTek       | F2A85-V                     | [c166f91030](https://linux-hardware.org/?probe=c166f91030) | May 25, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [ac28804681](https://linux-hardware.org/?probe=ac28804681) | May 25, 2023 |
| ASUSTek       | Berkeley                    | [c3e5448952](https://linux-hardware.org/?probe=c3e5448952) | May 24, 2023 |
| ASRock        | AB350M Pro4                 | [1efd2eb268](https://linux-hardware.org/?probe=1efd2eb268) | May 24, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [ddfad3653a](https://linux-hardware.org/?probe=ddfad3653a) | May 24, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [647a30ff09](https://linux-hardware.org/?probe=647a30ff09) | May 24, 2023 |
| MSI           | B550-A PRO                  | [f77697fdd0](https://linux-hardware.org/?probe=f77697fdd0) | May 24, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [2dfed39533](https://linux-hardware.org/?probe=2dfed39533) | May 24, 2023 |
| HP            | 8906 SMVB                   | [ca3ed99a5c](https://linux-hardware.org/?probe=ca3ed99a5c) | May 24, 2023 |
| ASRock        | B85M-HDS                    | [fc128a2474](https://linux-hardware.org/?probe=fc128a2474) | May 24, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [3a26097c6a](https://linux-hardware.org/?probe=3a26097c6a) | May 24, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [8c6370ac0d](https://linux-hardware.org/?probe=8c6370ac0d) | May 23, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [fcefb35b05](https://linux-hardware.org/?probe=fcefb35b05) | May 23, 2023 |
| Medion        | H110H4-EM                   | [218e19be02](https://linux-hardware.org/?probe=218e19be02) | May 23, 2023 |
| ASRock        | H270 Performance            | [b3f7fdc329](https://linux-hardware.org/?probe=b3f7fdc329) | May 23, 2023 |
| Gigabyte      | Q87M-D2H                    | [3c82eec4d2](https://linux-hardware.org/?probe=3c82eec4d2) | May 23, 2023 |
| MSI           | B550-A PRO                  | [0a952bd502](https://linux-hardware.org/?probe=0a952bd502) | May 22, 2023 |
| Packard Be... | MCP73                       | [1203dc5301](https://linux-hardware.org/?probe=1203dc5301) | May 22, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [a1fb857bcc](https://linux-hardware.org/?probe=a1fb857bcc) | May 22, 2023 |
| ASRock        | B550 Taichi                 | [175272b7e0](https://linux-hardware.org/?probe=175272b7e0) | May 22, 2023 |
| Dell          | 033FF6 A00                  | [086dd9367e](https://linux-hardware.org/?probe=086dd9367e) | May 21, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [7b5628af0e](https://linux-hardware.org/?probe=7b5628af0e) | May 21, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d4460792c6](https://linux-hardware.org/?probe=d4460792c6) | May 21, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | [80c62a0473](https://linux-hardware.org/?probe=80c62a0473) | May 21, 2023 |
| Gigabyte      | Q87M-D2H                    | [ee4eca623f](https://linux-hardware.org/?probe=ee4eca623f) | May 21, 2023 |
| MSI           | MPG Z790 EDGE WIFI          | [30e9eb3dd1](https://linux-hardware.org/?probe=30e9eb3dd1) | May 21, 2023 |
| Foxconn       | TPS01                       | [385129d471](https://linux-hardware.org/?probe=385129d471) | May 21, 2023 |
| ASUSTek       | H110M-A/M.2                 | [3f97487981](https://linux-hardware.org/?probe=3f97487981) | May 21, 2023 |
| Unknown       | HX90                        | [d640a32296](https://linux-hardware.org/?probe=d640a32296) | May 21, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [262bc7c88f](https://linux-hardware.org/?probe=262bc7c88f) | May 21, 2023 |
| Gigabyte      | B450 AORUS M                | [71a87fa176](https://linux-hardware.org/?probe=71a87fa176) | May 20, 2023 |
| Gigabyte      | F2A88X-D3H                  | [a547a22c01](https://linux-hardware.org/?probe=a547a22c01) | May 20, 2023 |
| Biostar       | NF520D3                     | [806beba322](https://linux-hardware.org/?probe=806beba322) | May 20, 2023 |
| HP            | 8055                        | [ddfca600c1](https://linux-hardware.org/?probe=ddfca600c1) | May 20, 2023 |
| Medion        | BTDD-LT                     | [3b5eac782c](https://linux-hardware.org/?probe=3b5eac782c) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [7384b29d21](https://linux-hardware.org/?probe=7384b29d21) | May 20, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [0c87a87d33](https://linux-hardware.org/?probe=0c87a87d33) | May 20, 2023 |
| Foxconn       | TPS01                       | [853284b818](https://linux-hardware.org/?probe=853284b818) | May 20, 2023 |
| HP            | 8433 11                     | [5d9e3a1dcc](https://linux-hardware.org/?probe=5d9e3a1dcc) | May 20, 2023 |
| HP            | 8055                        | [d7b466e881](https://linux-hardware.org/?probe=d7b466e881) | May 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [22ef34bb50](https://linux-hardware.org/?probe=22ef34bb50) | May 20, 2023 |
| MSI           | B350M BAZOOKA               | [49e536226c](https://linux-hardware.org/?probe=49e536226c) | May 19, 2023 |
| MSI           | X370 GAMING PLUS            | [610c8c1a42](https://linux-hardware.org/?probe=610c8c1a42) | May 19, 2023 |
| Acer          | TDPS05                      | [ed5384ee4d](https://linux-hardware.org/?probe=ed5384ee4d) | May 19, 2023 |
| MSI           | B350M BAZOOKA               | [2abefd21ea](https://linux-hardware.org/?probe=2abefd21ea) | May 19, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [8bd01d7d16](https://linux-hardware.org/?probe=8bd01d7d16) | May 19, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [1e7af790ed](https://linux-hardware.org/?probe=1e7af790ed) | May 19, 2023 |
| ASUSTek       | A88XM-A                     | [eea6382d39](https://linux-hardware.org/?probe=eea6382d39) | May 19, 2023 |
| Gigabyte      | H67A-D3H-B3                 | [606bb335e6](https://linux-hardware.org/?probe=606bb335e6) | May 19, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [f79cecb83e](https://linux-hardware.org/?probe=f79cecb83e) | May 19, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [584948af65](https://linux-hardware.org/?probe=584948af65) | May 19, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [87418d1634](https://linux-hardware.org/?probe=87418d1634) | May 18, 2023 |
| ASRock        | X370 Taichi                 | [94bf603662](https://linux-hardware.org/?probe=94bf603662) | May 18, 2023 |
| Gigabyte      | B450M DS3H V2               | [c9f5da779c](https://linux-hardware.org/?probe=c9f5da779c) | May 18, 2023 |
| MSI           | MAG B460M MORTAR            | [da74cacf64](https://linux-hardware.org/?probe=da74cacf64) | May 18, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5e003a073d](https://linux-hardware.org/?probe=5e003a073d) | May 18, 2023 |
| Unknown       | Unknown                     | [58066198c4](https://linux-hardware.org/?probe=58066198c4) | May 18, 2023 |
| HP            | 339A                        | [44a6e1f861](https://linux-hardware.org/?probe=44a6e1f861) | May 17, 2023 |
| ASRock        | N68-GS4/USB3 FX             | [80fa152a82](https://linux-hardware.org/?probe=80fa152a82) | May 17, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [84bd50bc27](https://linux-hardware.org/?probe=84bd50bc27) | May 17, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [3a7b647f0b](https://linux-hardware.org/?probe=3a7b647f0b) | May 17, 2023 |
| AMI           | Cherry Trail CR             | [60abe2cf78](https://linux-hardware.org/?probe=60abe2cf78) | May 17, 2023 |
| Acer          | TDPS05                      | [2cfc303d36](https://linux-hardware.org/?probe=2cfc303d36) | May 17, 2023 |
| Dell          | 048DY8 A01                  | [aaf390dad1](https://linux-hardware.org/?probe=aaf390dad1) | May 17, 2023 |
| Dell          | 048DY8 A00                  | [1456bc7f66](https://linux-hardware.org/?probe=1456bc7f66) | May 17, 2023 |
| ZOTAC         | Unknown                     | [5ae0ed6f5a](https://linux-hardware.org/?probe=5ae0ed6f5a) | May 16, 2023 |
| ASRock        | Z97 Pro3                    | [f8be8d5d2c](https://linux-hardware.org/?probe=f8be8d5d2c) | May 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | [e2878f2250](https://linux-hardware.org/?probe=e2878f2250) | May 16, 2023 |
| TYAN Compu... | S2505T                      | [a17c60c707](https://linux-hardware.org/?probe=a17c60c707) | May 16, 2023 |
| Unknown       | Unknown                     | [baa2041a25](https://linux-hardware.org/?probe=baa2041a25) | May 16, 2023 |
| ASUSTek       | PRIME B450M-K II            | [e77f91338e](https://linux-hardware.org/?probe=e77f91338e) | May 16, 2023 |
| HP            | 8055                        | [639cc3308f](https://linux-hardware.org/?probe=639cc3308f) | May 16, 2023 |
| HP            | 8055                        | [15c8401c45](https://linux-hardware.org/?probe=15c8401c45) | May 16, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [294fe7853f](https://linux-hardware.org/?probe=294fe7853f) | May 15, 2023 |
| Unknown       | Unknown                     | [39f109f45a](https://linux-hardware.org/?probe=39f109f45a) | May 15, 2023 |
| ASUSTek       | H110I-PLUS                  | [652d9e0fa9](https://linux-hardware.org/?probe=652d9e0fa9) | May 15, 2023 |
| Gigabyte      | Q87M-D2H                    | [98f104037a](https://linux-hardware.org/?probe=98f104037a) | May 15, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [34e7782996](https://linux-hardware.org/?probe=34e7782996) | May 15, 2023 |
| MSI           | Z87-G45 GAMING              | [06e1ef84b3](https://linux-hardware.org/?probe=06e1ef84b3) | May 15, 2023 |
| ASUSTek       | PRIME B550M-K               | [61e6c3f5f1](https://linux-hardware.org/?probe=61e6c3f5f1) | May 15, 2023 |
| ASUSTek       | P8B75-M LX                  | [a0632f2587](https://linux-hardware.org/?probe=a0632f2587) | May 15, 2023 |
| AMI           | Intel                       | [05850f17d5](https://linux-hardware.org/?probe=05850f17d5) | May 14, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [94d901f023](https://linux-hardware.org/?probe=94d901f023) | May 14, 2023 |
| MSI           | B550-A PRO                  | [c226d29f06](https://linux-hardware.org/?probe=c226d29f06) | May 14, 2023 |
| ASRock        | Z790M-ITX WiFi              | [1560f547ad](https://linux-hardware.org/?probe=1560f547ad) | May 14, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [aa0e7978c5](https://linux-hardware.org/?probe=aa0e7978c5) | May 14, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [34efd36999](https://linux-hardware.org/?probe=34efd36999) | May 14, 2023 |
| Gigabyte      | Q87M-D2H                    | [42db835c47](https://linux-hardware.org/?probe=42db835c47) | May 14, 2023 |
| Intel         | D510MO AAE76523-404         | [03221e90c1](https://linux-hardware.org/?probe=03221e90c1) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [41dee90f85](https://linux-hardware.org/?probe=41dee90f85) | May 14, 2023 |
| ASRock        | B650E PG Riptide WiFi       | [9243456914](https://linux-hardware.org/?probe=9243456914) | May 14, 2023 |
| Foxconn       | nT-330i                     | [b95166587e](https://linux-hardware.org/?probe=b95166587e) | May 14, 2023 |
| Pegatron      | 2AB5                        | [2381fb0c55](https://linux-hardware.org/?probe=2381fb0c55) | May 14, 2023 |
| Gigabyte      | Q87M-D2H                    | [3f4eafaf9c](https://linux-hardware.org/?probe=3f4eafaf9c) | May 13, 2023 |
| ASRock        | G41M-GS3                    | [8859685e86](https://linux-hardware.org/?probe=8859685e86) | May 13, 2023 |
| ASUSTek       | PRIME X570-PRO              | [0701f94970](https://linux-hardware.org/?probe=0701f94970) | May 13, 2023 |
| ASRock        | H370M-ITX/ac                | [7f4f38aeb1](https://linux-hardware.org/?probe=7f4f38aeb1) | May 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [878a94a7c7](https://linux-hardware.org/?probe=878a94a7c7) | May 13, 2023 |
| MSI           | MEG X399 CREATION           | [7f11045d3f](https://linux-hardware.org/?probe=7f11045d3f) | May 13, 2023 |
| ASRock        | Z97 Pro3                    | [34b2fb40b9](https://linux-hardware.org/?probe=34b2fb40b9) | May 13, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [fdf45a81de](https://linux-hardware.org/?probe=fdf45a81de) | May 13, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [921f919bb6](https://linux-hardware.org/?probe=921f919bb6) | May 12, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [bd6f8927b4](https://linux-hardware.org/?probe=bd6f8927b4) | May 12, 2023 |
| Medion        | TJ4125                      | [a0fcafbf70](https://linux-hardware.org/?probe=a0fcafbf70) | May 12, 2023 |
| Gigabyte      | B85M-D3H                    | [67122d7cd6](https://linux-hardware.org/?probe=67122d7cd6) | May 12, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [a2a47b4c35](https://linux-hardware.org/?probe=a2a47b4c35) | May 12, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [b56358c287](https://linux-hardware.org/?probe=b56358c287) | May 12, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [41b69ae4db](https://linux-hardware.org/?probe=41b69ae4db) | May 12, 2023 |
| Gigabyte      | B85M-D3H                    | [9c8ffba5f4](https://linux-hardware.org/?probe=9c8ffba5f4) | May 12, 2023 |
| Medion        | TJ4125                      | [4d7467c0bc](https://linux-hardware.org/?probe=4d7467c0bc) | May 12, 2023 |
| Unknown       | T3 MRD                      | [c37c04d223](https://linux-hardware.org/?probe=c37c04d223) | May 12, 2023 |
| Gigabyte      | Q87M-D2H                    | [99c9764b7e](https://linux-hardware.org/?probe=99c9764b7e) | May 12, 2023 |
| Medion        | BTDD-LT                     | [86a5697c9c](https://linux-hardware.org/?probe=86a5697c9c) | May 12, 2023 |
| Gigabyte      | Z77-DS3H                    | [c86f346e1d](https://linux-hardware.org/?probe=c86f346e1d) | May 12, 2023 |
| ASUSTek       | X79-DELUXE                  | [ad6be5fe7c](https://linux-hardware.org/?probe=ad6be5fe7c) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6c61b581ba](https://linux-hardware.org/?probe=6c61b581ba) | May 12, 2023 |
| Gigabyte      | GA-970A-D3                  | [2302fc6860](https://linux-hardware.org/?probe=2302fc6860) | May 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [92a39a22a2](https://linux-hardware.org/?probe=92a39a22a2) | May 12, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [cfa81980a9](https://linux-hardware.org/?probe=cfa81980a9) | May 12, 2023 |
| AZW           | Green G3                    | [e11013e93f](https://linux-hardware.org/?probe=e11013e93f) | May 11, 2023 |
| ZOTAC         | Unknown                     | [9495c6ca84](https://linux-hardware.org/?probe=9495c6ca84) | May 11, 2023 |
| Dell          | 0GY6Y8 A02                  | [99ad79383e](https://linux-hardware.org/?probe=99ad79383e) | May 11, 2023 |
| ASRock        | Z590M-ITX/ax                | [2d3692d380](https://linux-hardware.org/?probe=2d3692d380) | May 11, 2023 |
| ASRock        | Z590M-ITX/ax                | [3c43bfe7bc](https://linux-hardware.org/?probe=3c43bfe7bc) | May 11, 2023 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [4b5279de3c](https://linux-hardware.org/?probe=4b5279de3c) | May 11, 2023 |
| Dell          | 0GU083 A00                  | [eec8f60d12](https://linux-hardware.org/?probe=eec8f60d12) | May 11, 2023 |
| Dell          | 0J3C2F A02                  | [622dd024aa](https://linux-hardware.org/?probe=622dd024aa) | May 11, 2023 |
| MSI           | K9N6PGM2-V2                 | [a011c93e5a](https://linux-hardware.org/?probe=a011c93e5a) | May 11, 2023 |
| MSI           | K9N6PGM2-V2                 | [175c8a6b39](https://linux-hardware.org/?probe=175c8a6b39) | May 11, 2023 |
| Acer          | EQ45M                       | [57fa86c8dc](https://linux-hardware.org/?probe=57fa86c8dc) | May 11, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [53d9e318f6](https://linux-hardware.org/?probe=53d9e318f6) | May 11, 2023 |
| Lenovo        | 3138 SDK0J40697 WIN 3305... | [36022cb1ac](https://linux-hardware.org/?probe=36022cb1ac) | May 11, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [3df5f7ec7e](https://linux-hardware.org/?probe=3df5f7ec7e) | May 11, 2023 |
| ASRock        | J4125M                      | [bf3fa2ddd3](https://linux-hardware.org/?probe=bf3fa2ddd3) | May 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [1b20151b4c](https://linux-hardware.org/?probe=1b20151b4c) | May 10, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [0625860f59](https://linux-hardware.org/?probe=0625860f59) | May 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [554b258b3c](https://linux-hardware.org/?probe=554b258b3c) | May 10, 2023 |
| MSI           | B350M PRO-VDH               | [76dbae3614](https://linux-hardware.org/?probe=76dbae3614) | May 10, 2023 |
| Dell          | 0GM819                      | [ccd99ab6c3](https://linux-hardware.org/?probe=ccd99ab6c3) | May 10, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [f53beea0c9](https://linux-hardware.org/?probe=f53beea0c9) | May 10, 2023 |
| MSI           | B450 GAMING PLUS            | [df94e4a72a](https://linux-hardware.org/?probe=df94e4a72a) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [719d80a236](https://linux-hardware.org/?probe=719d80a236) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [b25b524237](https://linux-hardware.org/?probe=b25b524237) | May 10, 2023 |
| ASUSTek       | P8H77-V                     | [f86702afcf](https://linux-hardware.org/?probe=f86702afcf) | May 10, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [ebe0f52831](https://linux-hardware.org/?probe=ebe0f52831) | May 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [02db88a814](https://linux-hardware.org/?probe=02db88a814) | May 10, 2023 |
| HP            | 18E5                        | [09eb27d0c5](https://linux-hardware.org/?probe=09eb27d0c5) | May 09, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [f2f9e06eaf](https://linux-hardware.org/?probe=f2f9e06eaf) | May 09, 2023 |
| Gigabyte      | AX370-Gaming 5              | [462a9b182b](https://linux-hardware.org/?probe=462a9b182b) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [1e41703eca](https://linux-hardware.org/?probe=1e41703eca) | May 09, 2023 |
| ASUSTek       | M5A78L-M LX3                | [7a623e22fc](https://linux-hardware.org/?probe=7a623e22fc) | May 09, 2023 |
| ASUSTek       | PRIME B450M-A II            | [aee249559e](https://linux-hardware.org/?probe=aee249559e) | May 09, 2023 |
| Gigabyte      | Q87M-D2H                    | [a70e02af94](https://linux-hardware.org/?probe=a70e02af94) | May 09, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [aa31c3dd8f](https://linux-hardware.org/?probe=aa31c3dd8f) | May 09, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [bf3fee03d2](https://linux-hardware.org/?probe=bf3fee03d2) | May 09, 2023 |
| ASRockRack    | X470D4U2/1N1                | [0df088e75f](https://linux-hardware.org/?probe=0df088e75f) | May 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [e98eff32d6](https://linux-hardware.org/?probe=e98eff32d6) | May 08, 2023 |
| ASRock        | J4125M                      | [a702df382b](https://linux-hardware.org/?probe=a702df382b) | May 08, 2023 |
| Acer          | H57M01                      | [3cdf8244ef](https://linux-hardware.org/?probe=3cdf8244ef) | May 08, 2023 |
| Gigabyte      | Z390 UD                     | [19d78d1685](https://linux-hardware.org/?probe=19d78d1685) | May 08, 2023 |
| ASRock        | Z87 Pro4                    | [e3971068b6](https://linux-hardware.org/?probe=e3971068b6) | May 08, 2023 |
| Dell          | 0JP3NX A00                  | [974cb924d5](https://linux-hardware.org/?probe=974cb924d5) | May 08, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [aa2af0a4bc](https://linux-hardware.org/?probe=aa2af0a4bc) | May 08, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [dc43e4a7e3](https://linux-hardware.org/?probe=dc43e4a7e3) | May 08, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [bfd53a8d28](https://linux-hardware.org/?probe=bfd53a8d28) | May 08, 2023 |
| ASUSTek       | P5QLD PRO                   | [c2a0653c52](https://linux-hardware.org/?probe=c2a0653c52) | May 08, 2023 |
| ASUSTek       | P8P67-M                     | [386d7c9de4](https://linux-hardware.org/?probe=386d7c9de4) | May 07, 2023 |
| Gigabyte      | P35-DS4                     | [fd830a3568](https://linux-hardware.org/?probe=fd830a3568) | May 07, 2023 |
| Gigabyte      | Q87M-D2H                    | [7d861acbd6](https://linux-hardware.org/?probe=7d861acbd6) | May 07, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [31123c256d](https://linux-hardware.org/?probe=31123c256d) | May 07, 2023 |
| ASUSTek       | M5A88-V EVO                 | [c174fcc2d8](https://linux-hardware.org/?probe=c174fcc2d8) | May 07, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1e62d5884b](https://linux-hardware.org/?probe=1e62d5884b) | May 07, 2023 |
| Gigabyte      | B450 AORUS M                | [87e972803c](https://linux-hardware.org/?probe=87e972803c) | May 07, 2023 |
| Dell          | 042P49 A02                  | [de394c8663](https://linux-hardware.org/?probe=de394c8663) | May 07, 2023 |
| ECS           | H410-SF110                  | [5e5011bdd3](https://linux-hardware.org/?probe=5e5011bdd3) | May 07, 2023 |
| ASRock        | B650E PG Riptide WiFi       | [ed03df615e](https://linux-hardware.org/?probe=ed03df615e) | May 07, 2023 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | [eeb37c9c4f](https://linux-hardware.org/?probe=eeb37c9c4f) | May 07, 2023 |
| Gigabyte      | Z390 UD                     | [b5a495cf0a](https://linux-hardware.org/?probe=b5a495cf0a) | May 07, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [f894b9a2c4](https://linux-hardware.org/?probe=f894b9a2c4) | May 07, 2023 |
| ASUSTek       | Z77-A                       | [92b5951471](https://linux-hardware.org/?probe=92b5951471) | May 07, 2023 |
| ASUSTek       | WS X299 SAGE                | [1c9e5ee2a6](https://linux-hardware.org/?probe=1c9e5ee2a6) | May 07, 2023 |
| ASRock        | J4125M                      | [57865d6cea](https://linux-hardware.org/?probe=57865d6cea) | May 07, 2023 |
| Medion        | TJ4125                      | [583b49089e](https://linux-hardware.org/?probe=583b49089e) | May 07, 2023 |
| Gigabyte      | B85M-D3H                    | [11a41c975d](https://linux-hardware.org/?probe=11a41c975d) | May 07, 2023 |
| ASUSTek       | P5Q SE/R                    | [4d78dbbdc6](https://linux-hardware.org/?probe=4d78dbbdc6) | May 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [f3ea9b926d](https://linux-hardware.org/?probe=f3ea9b926d) | May 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | [42a38fb30a](https://linux-hardware.org/?probe=42a38fb30a) | May 06, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [087681f84e](https://linux-hardware.org/?probe=087681f84e) | May 06, 2023 |
| ASRock        | N3150-NUC                   | [5775b2c94f](https://linux-hardware.org/?probe=5775b2c94f) | May 06, 2023 |
| Acer          | Predator PO3-640            | [6417de34e5](https://linux-hardware.org/?probe=6417de34e5) | May 06, 2023 |
| ASUSTek       | M11BB                       | [35d2ca0280](https://linux-hardware.org/?probe=35d2ca0280) | May 06, 2023 |
| MSI           | B450M PRO-VDH MAX           | [a9d1794eec](https://linux-hardware.org/?probe=a9d1794eec) | May 06, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f4e56e51d7](https://linux-hardware.org/?probe=f4e56e51d7) | May 06, 2023 |
| ASUSTek       | M4A78LT-M-LE                | [b561c005c5](https://linux-hardware.org/?probe=b561c005c5) | May 06, 2023 |
| Medion        | MS-7621                     | [83c862da24](https://linux-hardware.org/?probe=83c862da24) | May 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [1b7398e5e8](https://linux-hardware.org/?probe=1b7398e5e8) | May 06, 2023 |
| ASUSTek       | M4A78LT-M-LE                | [b08872130e](https://linux-hardware.org/?probe=b08872130e) | May 06, 2023 |
| Acer          | EG43M                       | [50ee9c3423](https://linux-hardware.org/?probe=50ee9c3423) | May 06, 2023 |
| ASUSTek       | SABERTOOTH X79              | [f9d2b57c91](https://linux-hardware.org/?probe=f9d2b57c91) | May 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1445a9b10d](https://linux-hardware.org/?probe=1445a9b10d) | May 06, 2023 |
| HP            | 8055                        | [693d157be0](https://linux-hardware.org/?probe=693d157be0) | May 06, 2023 |
| ASUSTek       | M4A87TD EVO                 | [ecb5894e85](https://linux-hardware.org/?probe=ecb5894e85) | May 06, 2023 |
| ASRock        | Q270 Pro BTC+               | [4fc3d2c86f](https://linux-hardware.org/?probe=4fc3d2c86f) | May 05, 2023 |
| Medion        | TJ4125                      | [2255946fa5](https://linux-hardware.org/?probe=2255946fa5) | May 05, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [09bd22441b](https://linux-hardware.org/?probe=09bd22441b) | May 05, 2023 |
| Dell          | 0RN474                      | [b638694274](https://linux-hardware.org/?probe=b638694274) | May 05, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [b6ec076cc6](https://linux-hardware.org/?probe=b6ec076cc6) | May 05, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [307dfb1c46](https://linux-hardware.org/?probe=307dfb1c46) | May 05, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [101ec0a833](https://linux-hardware.org/?probe=101ec0a833) | May 05, 2023 |
| ASUSTek       | PRIME B350M-A               | [c5a8cec4f6](https://linux-hardware.org/?probe=c5a8cec4f6) | May 05, 2023 |
| Gigabyte      | GA-970A-UD3                 | [f1dec1f586](https://linux-hardware.org/?probe=f1dec1f586) | May 05, 2023 |
| YANYU         | EPIC-N56_I522E Ver          | [b2ff986f07](https://linux-hardware.org/?probe=b2ff986f07) | May 04, 2023 |
| Acer          | Predator G3-605             | [6f91022c83](https://linux-hardware.org/?probe=6f91022c83) | May 04, 2023 |
| ASUSTek       | P5N73-CM                    | [e64a3c2da5](https://linux-hardware.org/?probe=e64a3c2da5) | May 04, 2023 |
| Gigabyte      | GA-970A-UD3                 | [d83f1c354f](https://linux-hardware.org/?probe=d83f1c354f) | May 04, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [11e132041b](https://linux-hardware.org/?probe=11e132041b) | May 04, 2023 |
| MSI           | H61M-E33                    | [f8f3b7bfcd](https://linux-hardware.org/?probe=f8f3b7bfcd) | May 04, 2023 |
| Gigabyte      | P55M-UD2                    | [a07a7cf773](https://linux-hardware.org/?probe=a07a7cf773) | May 04, 2023 |
| HP            | 8055                        | [b17e451ea7](https://linux-hardware.org/?probe=b17e451ea7) | May 03, 2023 |
| ASRock        | H310CM-HDV                  | [788d950ad8](https://linux-hardware.org/?probe=788d950ad8) | May 03, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [2dabac74e0](https://linux-hardware.org/?probe=2dabac74e0) | May 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [d0df4d195a](https://linux-hardware.org/?probe=d0df4d195a) | May 03, 2023 |
| Gigabyte      | B85-HD3                     | [1e7a8a2576](https://linux-hardware.org/?probe=1e7a8a2576) | May 03, 2023 |
| ASUSTek       | P5NT WS                     | [70d5fd7a1d](https://linux-hardware.org/?probe=70d5fd7a1d) | May 03, 2023 |
| ASRock        | H81M-HDS R2.0               | [d0120d30ca](https://linux-hardware.org/?probe=d0120d30ca) | May 03, 2023 |
| Dell          | 00V62H A01                  | [a8d6e3cb45](https://linux-hardware.org/?probe=a8d6e3cb45) | May 03, 2023 |
| Gigabyte      | H87-HD3                     | [f0e4057e5f](https://linux-hardware.org/?probe=f0e4057e5f) | May 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [89ae1a3e9d](https://linux-hardware.org/?probe=89ae1a3e9d) | May 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6dd26d16c2](https://linux-hardware.org/?probe=6dd26d16c2) | May 03, 2023 |
| ASUSTek       | P8B75-M LX                  | [48cd52c257](https://linux-hardware.org/?probe=48cd52c257) | May 03, 2023 |
| ASUSTek       | P8B75-M LX                  | [6f581a5919](https://linux-hardware.org/?probe=6f581a5919) | May 03, 2023 |
| MSI           | B450 GAMING PLUS            | [017222d810](https://linux-hardware.org/?probe=017222d810) | May 02, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [9bb83ed0d4](https://linux-hardware.org/?probe=9bb83ed0d4) | May 02, 2023 |
| MSI           | B550-A PRO                  | [97620ac3e7](https://linux-hardware.org/?probe=97620ac3e7) | May 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [0dd7d869b2](https://linux-hardware.org/?probe=0dd7d869b2) | May 02, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | [6ee65c19d2](https://linux-hardware.org/?probe=6ee65c19d2) | May 02, 2023 |
| Gigabyte      | B85M-D3H                    | [f9c27ab898](https://linux-hardware.org/?probe=f9c27ab898) | May 02, 2023 |
| MSI           | K9N6PGM2-V2                 | [d7c60c4667](https://linux-hardware.org/?probe=d7c60c4667) | May 02, 2023 |
| Gigabyte      | Q87M-D2H                    | [ae586408c4](https://linux-hardware.org/?probe=ae586408c4) | May 02, 2023 |
| BESSTAR Te... | DMAF5                       | [b9f947fec3](https://linux-hardware.org/?probe=b9f947fec3) | May 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [ee8e81add2](https://linux-hardware.org/?probe=ee8e81add2) | May 01, 2023 |
| ASRock        | B550M-ITX/ac                | [b77341d8f0](https://linux-hardware.org/?probe=b77341d8f0) | May 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [00dc63bf78](https://linux-hardware.org/?probe=00dc63bf78) | May 01, 2023 |
| ASUSTek       | PRIME H410M-A               | [147006a71f](https://linux-hardware.org/?probe=147006a71f) | May 01, 2023 |
| Medion        | B360H4-EM V1.0              | [86a89a1986](https://linux-hardware.org/?probe=86a89a1986) | May 01, 2023 |
| MSI           | B450M PRO-VDH MAX           | [8fb29cf081](https://linux-hardware.org/?probe=8fb29cf081) | May 01, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [56c837b00f](https://linux-hardware.org/?probe=56c837b00f) | May 01, 2023 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [b971501e28](https://linux-hardware.org/?probe=b971501e28) | May 01, 2023 |
| ASRock        | B550 Taichi                 | [826fd3bad0](https://linux-hardware.org/?probe=826fd3bad0) | May 01, 2023 |
| Unknown       | Unknown                     | [31f41f9646](https://linux-hardware.org/?probe=31f41f9646) | May 01, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | [9b6f7cea89](https://linux-hardware.org/?probe=9b6f7cea89) | May 01, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [705ff684a9](https://linux-hardware.org/?probe=705ff684a9) | Apr 30, 2023 |
| ASRock        | FM2A68M-HD+                 | [467bb5ded2](https://linux-hardware.org/?probe=467bb5ded2) | Apr 30, 2023 |
| Shuttle       | DL20N                       | [3f97bcaa08](https://linux-hardware.org/?probe=3f97bcaa08) | Apr 30, 2023 |
| ASRock        | 960GM-GS3 FX                | [392492c032](https://linux-hardware.org/?probe=392492c032) | Apr 30, 2023 |
| Medion        | H81H3-EM2                   | [c85a3da4ab](https://linux-hardware.org/?probe=c85a3da4ab) | Apr 30, 2023 |
| ASRock        | N68-GS4 FX                  | [354f8689e7](https://linux-hardware.org/?probe=354f8689e7) | Apr 30, 2023 |
| MSI           | X570-A PRO                  | [4d31b88bbf](https://linux-hardware.org/?probe=4d31b88bbf) | Apr 30, 2023 |
| MSI           | X570-A PRO                  | [47a253784a](https://linux-hardware.org/?probe=47a253784a) | Apr 30, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [ac7894081f](https://linux-hardware.org/?probe=ac7894081f) | Apr 30, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [a88277b7f9](https://linux-hardware.org/?probe=a88277b7f9) | Apr 30, 2023 |
| Acer          | Aspire X3950                | [406366d5c1](https://linux-hardware.org/?probe=406366d5c1) | Apr 30, 2023 |
| MSI           | B450 GAMING PLUS            | [8aa973e0f5](https://linux-hardware.org/?probe=8aa973e0f5) | Apr 30, 2023 |
| Gigabyte      | Q87M-D2H                    | [16279b3c8b](https://linux-hardware.org/?probe=16279b3c8b) | Apr 30, 2023 |
| Gigabyte      | B85M-D3H                    | [2fe28d7f43](https://linux-hardware.org/?probe=2fe28d7f43) | Apr 29, 2023 |
| Medion        | TJ4125                      | [ad46974b2a](https://linux-hardware.org/?probe=ad46974b2a) | Apr 29, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [4ac7cbf111](https://linux-hardware.org/?probe=4ac7cbf111) | Apr 29, 2023 |
| Gigabyte      | B450 AORUS M                | [ccc2fbf8a9](https://linux-hardware.org/?probe=ccc2fbf8a9) | Apr 29, 2023 |
| ASRock        | N68C-S UCC                  | [13628f3559](https://linux-hardware.org/?probe=13628f3559) | Apr 29, 2023 |
| ASUSTek       | X99-A                       | [6505e46b86](https://linux-hardware.org/?probe=6505e46b86) | Apr 29, 2023 |
| MSI           | B85M-E45                    | [db824980e5](https://linux-hardware.org/?probe=db824980e5) | Apr 29, 2023 |
| MSI           | B85M-E45                    | [42703e0a76](https://linux-hardware.org/?probe=42703e0a76) | Apr 29, 2023 |
| Intel         | DB75EN AAG39650-303         | [713c422641](https://linux-hardware.org/?probe=713c422641) | Apr 29, 2023 |
| Hardkernel    | ODROID-H3                   | [139d61e128](https://linux-hardware.org/?probe=139d61e128) | Apr 29, 2023 |
| Gigabyte      | Z790 UD                     | [536a24a0e3](https://linux-hardware.org/?probe=536a24a0e3) | Apr 29, 2023 |
| ASRock        | N68C-S UCC                  | [f7f4643b8f](https://linux-hardware.org/?probe=f7f4643b8f) | Apr 29, 2023 |
| HP            | 3397                        | [8b84766d3d](https://linux-hardware.org/?probe=8b84766d3d) | Apr 29, 2023 |
| YANYU         | EPIC-N56_I522E Ver          | [4798ab5c06](https://linux-hardware.org/?probe=4798ab5c06) | Apr 29, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [e47ae2080c](https://linux-hardware.org/?probe=e47ae2080c) | Apr 29, 2023 |
| HP            | 845A                        | [d0aa2a4a7a](https://linux-hardware.org/?probe=d0aa2a4a7a) | Apr 29, 2023 |
| HP            | 845A                        | [f8bc4601ef](https://linux-hardware.org/?probe=f8bc4601ef) | Apr 29, 2023 |
| Medion        | TJ4125                      | [8f319cff50](https://linux-hardware.org/?probe=8f319cff50) | Apr 28, 2023 |
| Gigabyte      | B85M-D3H                    | [c0c226bf8c](https://linux-hardware.org/?probe=c0c226bf8c) | Apr 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [6503ed5a4c](https://linux-hardware.org/?probe=6503ed5a4c) | Apr 28, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [77150d1166](https://linux-hardware.org/?probe=77150d1166) | Apr 28, 2023 |
| ASUSTek       | PRIME X370-PRO              | [ddb48a2def](https://linux-hardware.org/?probe=ddb48a2def) | Apr 28, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [99745be007](https://linux-hardware.org/?probe=99745be007) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [278ed4fdd2](https://linux-hardware.org/?probe=278ed4fdd2) | Apr 28, 2023 |
| HP            | ProLiant ML350e Gen8 v2     | [968f941e2d](https://linux-hardware.org/?probe=968f941e2d) | Apr 28, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [2427e67de4](https://linux-hardware.org/?probe=2427e67de4) | Apr 28, 2023 |
| ASRock        | A75M-HVS                    | [528362dfca](https://linux-hardware.org/?probe=528362dfca) | Apr 28, 2023 |
| Unknown       | Unknown                     | [5f5809c40f](https://linux-hardware.org/?probe=5f5809c40f) | Apr 27, 2023 |
| Shenzhen M... | F6BFC                       | [e2f7b853b1](https://linux-hardware.org/?probe=e2f7b853b1) | Apr 27, 2023 |
| HP            | 82F2 A01                    | [ea8f7364db](https://linux-hardware.org/?probe=ea8f7364db) | Apr 27, 2023 |
| ASRock        | A330GC                      | [d1a2e8dd13](https://linux-hardware.org/?probe=d1a2e8dd13) | Apr 27, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [7f2f7e75b7](https://linux-hardware.org/?probe=7f2f7e75b7) | Apr 27, 2023 |
| Dell          | 0HHV7N A00                  | [33517b7bfe](https://linux-hardware.org/?probe=33517b7bfe) | Apr 27, 2023 |
| Lenovo        | ThinkCentre M71e 3129B8G    | [2b6c3d498a](https://linux-hardware.org/?probe=2b6c3d498a) | Apr 27, 2023 |
| Gigabyte      | Z97P-D3                     | [40b51d3cae](https://linux-hardware.org/?probe=40b51d3cae) | Apr 27, 2023 |
| HP            | 18E7                        | [c6a760cb50](https://linux-hardware.org/?probe=c6a760cb50) | Apr 27, 2023 |
| Gigabyte      | H61MA-D3V                   | [3a1d89d5a0](https://linux-hardware.org/?probe=3a1d89d5a0) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [812906148b](https://linux-hardware.org/?probe=812906148b) | Apr 27, 2023 |
| MSI           | B350M PRO-VDH               | [a15fa484d4](https://linux-hardware.org/?probe=a15fa484d4) | Apr 26, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2dcf65cf8e](https://linux-hardware.org/?probe=2dcf65cf8e) | Apr 26, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [eaac4c0ba0](https://linux-hardware.org/?probe=eaac4c0ba0) | Apr 26, 2023 |
| Gigabyte      | Z370M D3H-CF                | [ada8ff75dd](https://linux-hardware.org/?probe=ada8ff75dd) | Apr 26, 2023 |
| MSI           | B450-A PRO MAX              | [2d7c2dd8f9](https://linux-hardware.org/?probe=2d7c2dd8f9) | Apr 26, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [64b15b4b1d](https://linux-hardware.org/?probe=64b15b4b1d) | Apr 26, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [45c453eb4e](https://linux-hardware.org/?probe=45c453eb4e) | Apr 26, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [b79a40ebdc](https://linux-hardware.org/?probe=b79a40ebdc) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Gigabyte      | B75M-D3H                    | [4f1e4da37e](https://linux-hardware.org/?probe=4f1e4da37e) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [6dec479f55](https://linux-hardware.org/?probe=6dec479f55) | Apr 25, 2023 |
| ASUSTek       | Z170-A                      | [fa21ed6900](https://linux-hardware.org/?probe=fa21ed6900) | Apr 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [a2875a31b2](https://linux-hardware.org/?probe=a2875a31b2) | Apr 25, 2023 |
| ASUSTek       | PRIME B450M-A               | [d8c1be05af](https://linux-hardware.org/?probe=d8c1be05af) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [4668a2409b](https://linux-hardware.org/?probe=4668a2409b) | Apr 25, 2023 |
| Lenovo        | ThinkCentre A70z 0401G6G    | [b1b8bf3df6](https://linux-hardware.org/?probe=b1b8bf3df6) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [7b091628e5](https://linux-hardware.org/?probe=7b091628e5) | Apr 25, 2023 |
| ASRock        | X670E Pro RS                | [e36216c3c7](https://linux-hardware.org/?probe=e36216c3c7) | Apr 25, 2023 |
| ASUSTek       | PRIME A520M-K               | [a437a858a4](https://linux-hardware.org/?probe=a437a858a4) | Apr 25, 2023 |
| MSI           | B560M PRO-VDH               | [61cdcbbe0c](https://linux-hardware.org/?probe=61cdcbbe0c) | Apr 25, 2023 |
| ASRock        | Z690 Extreme                | [3767d30290](https://linux-hardware.org/?probe=3767d30290) | Apr 25, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [7d7fd385cc](https://linux-hardware.org/?probe=7d7fd385cc) | Apr 25, 2023 |
| Gigabyte      | B450M S2H                   | [db176db0db](https://linux-hardware.org/?probe=db176db0db) | Apr 25, 2023 |
| Lenovo        | 313A NOK                    | [34a521ebad](https://linux-hardware.org/?probe=34a521ebad) | Apr 24, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [88c455761b](https://linux-hardware.org/?probe=88c455761b) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [25ac3a297e](https://linux-hardware.org/?probe=25ac3a297e) | Apr 24, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [e18fd8d449](https://linux-hardware.org/?probe=e18fd8d449) | Apr 24, 2023 |
| Lenovo        | 32E9 SDK0T76463 WIN 3422... | [9f49daf25a](https://linux-hardware.org/?probe=9f49daf25a) | Apr 24, 2023 |
| Lenovo        | 32E9 SDK0T76463 WIN 3422... | [cc7a31d3d6](https://linux-hardware.org/?probe=cc7a31d3d6) | Apr 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | [eb716c53fa](https://linux-hardware.org/?probe=eb716c53fa) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [4939e609de](https://linux-hardware.org/?probe=4939e609de) | Apr 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [2a0ee71044](https://linux-hardware.org/?probe=2a0ee71044) | Apr 23, 2023 |
| Gigabyte      | B450M S2H                   | [f3c853b789](https://linux-hardware.org/?probe=f3c853b789) | Apr 23, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [e5c6fc2738](https://linux-hardware.org/?probe=e5c6fc2738) | Apr 23, 2023 |
| Foxconn       | H67M-S/H67M-V/H67           | [92fa61186f](https://linux-hardware.org/?probe=92fa61186f) | Apr 23, 2023 |
| MSI           | MEG X570S ACE MAX           | [b7ab5c207b](https://linux-hardware.org/?probe=b7ab5c207b) | Apr 23, 2023 |
| Gigabyte      | Q87M-D2H                    | [5827cd2604](https://linux-hardware.org/?probe=5827cd2604) | Apr 23, 2023 |
| HP            | 339A                        | [aa81655af9](https://linux-hardware.org/?probe=aa81655af9) | Apr 23, 2023 |
| Gigabyte      | B85M-D3H                    | [88a6d9040e](https://linux-hardware.org/?probe=88a6d9040e) | Apr 23, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [e653a5dd45](https://linux-hardware.org/?probe=e653a5dd45) | Apr 23, 2023 |
| ASUSTek       | F1A55-M LK R2.0             | [234e0d0738](https://linux-hardware.org/?probe=234e0d0738) | Apr 23, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [95e77b87f5](https://linux-hardware.org/?probe=95e77b87f5) | Apr 23, 2023 |
| Medion        | TJ4125                      | [faa241e4bc](https://linux-hardware.org/?probe=faa241e4bc) | Apr 23, 2023 |
| Dell          | 09KPNV A00                  | [0ba7a36003](https://linux-hardware.org/?probe=0ba7a36003) | Apr 23, 2023 |
| Dell          | 09KPNV A00                  | [a99600dad6](https://linux-hardware.org/?probe=a99600dad6) | Apr 23, 2023 |
| ASRock        | N68-GS4 FX                  | [58dfb135e4](https://linux-hardware.org/?probe=58dfb135e4) | Apr 23, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [a65124c792](https://linux-hardware.org/?probe=a65124c792) | Apr 23, 2023 |
| ASRock        | N68-GS4 FX                  | [6edcfed28d](https://linux-hardware.org/?probe=6edcfed28d) | Apr 23, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [eac9934073](https://linux-hardware.org/?probe=eac9934073) | Apr 23, 2023 |
| Gigabyte      | Z390 UD                     | [418754830b](https://linux-hardware.org/?probe=418754830b) | Apr 23, 2023 |
| Packard Be... | IPOWER G3610                | [05de2306b0](https://linux-hardware.org/?probe=05de2306b0) | Apr 23, 2023 |
| MSI           | G41M-P26                    | [342a1163ab](https://linux-hardware.org/?probe=342a1163ab) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [b342cd8fe0](https://linux-hardware.org/?probe=b342cd8fe0) | Apr 23, 2023 |
| Gigabyte      | 970A-DS3P                   | [4a55a10fd0](https://linux-hardware.org/?probe=4a55a10fd0) | Apr 23, 2023 |
| ASRock        | A75M-HVS                    | [a4964506f7](https://linux-hardware.org/?probe=a4964506f7) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [93790f1835](https://linux-hardware.org/?probe=93790f1835) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [fb4c86b0c4](https://linux-hardware.org/?probe=fb4c86b0c4) | Apr 23, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [8db6f88fd3](https://linux-hardware.org/?probe=8db6f88fd3) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c4a5aad8a1](https://linux-hardware.org/?probe=c4a5aad8a1) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [180784b3a2](https://linux-hardware.org/?probe=180784b3a2) | Apr 22, 2023 |
| Biostar       | A75MG                       | [50cb5c256e](https://linux-hardware.org/?probe=50cb5c256e) | Apr 22, 2023 |
| Gigabyte      | Z790 UD                     | [8536a23081](https://linux-hardware.org/?probe=8536a23081) | Apr 22, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [475a4d151d](https://linux-hardware.org/?probe=475a4d151d) | Apr 22, 2023 |
| Gigabyte      | B550M S2H                   | [485f002152](https://linux-hardware.org/?probe=485f002152) | Apr 22, 2023 |
| MSI           | Z77A-G41                    | [9cd2294229](https://linux-hardware.org/?probe=9cd2294229) | Apr 22, 2023 |
| Biostar       | H410MH S2                   | [0f2593dc78](https://linux-hardware.org/?probe=0f2593dc78) | Apr 22, 2023 |
| Fujitsu Si... | D2156-A1 S26361-D2156-A1    | [617f821f9a](https://linux-hardware.org/?probe=617f821f9a) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [519c11a569](https://linux-hardware.org/?probe=519c11a569) | Apr 21, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [d4d3e7f8d6](https://linux-hardware.org/?probe=d4d3e7f8d6) | Apr 21, 2023 |
| MSI           | IONA                        | [3820fb6576](https://linux-hardware.org/?probe=3820fb6576) | Apr 21, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [a898476ffa](https://linux-hardware.org/?probe=a898476ffa) | Apr 21, 2023 |
| ASRock        | H81M-HDS R2.0               | [eaf8476afd](https://linux-hardware.org/?probe=eaf8476afd) | Apr 21, 2023 |
| Gigabyte      | B550M DS3H                  | [e98b4fdd23](https://linux-hardware.org/?probe=e98b4fdd23) | Apr 21, 2023 |
| ASUSTek       | M5A97 R2.0                  | [1c0e6f85fe](https://linux-hardware.org/?probe=1c0e6f85fe) | Apr 21, 2023 |
| HP            | 8054                        | [0f2c12c877](https://linux-hardware.org/?probe=0f2c12c877) | Apr 20, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [00b1045cf9](https://linux-hardware.org/?probe=00b1045cf9) | Apr 20, 2023 |
| Gigabyte      | B85-HD3                     | [07ecc38bef](https://linux-hardware.org/?probe=07ecc38bef) | Apr 20, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [f79af9bad0](https://linux-hardware.org/?probe=f79af9bad0) | Apr 20, 2023 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | [9ff4edba5b](https://linux-hardware.org/?probe=9ff4edba5b) | Apr 20, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [68e853f4c1](https://linux-hardware.org/?probe=68e853f4c1) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [adb291235a](https://linux-hardware.org/?probe=adb291235a) | Apr 20, 2023 |
| MSI           | H110M PRO-VD                | [509d9126e1](https://linux-hardware.org/?probe=509d9126e1) | Apr 19, 2023 |
| Acer          | Veriton X2632G V:1.0        | [0fa4554c3c](https://linux-hardware.org/?probe=0fa4554c3c) | Apr 19, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [e1da556a0b](https://linux-hardware.org/?probe=e1da556a0b) | Apr 19, 2023 |
| ASUSTek       | PRIME B350M-A               | [c6cd36eaed](https://linux-hardware.org/?probe=c6cd36eaed) | Apr 19, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8afed7ed9c](https://linux-hardware.org/?probe=8afed7ed9c) | Apr 19, 2023 |
| AMI           | Intel                       | [3f1890d683](https://linux-hardware.org/?probe=3f1890d683) | Apr 19, 2023 |
| MSI           | A320M-A PRO MAX             | [630a9718a0](https://linux-hardware.org/?probe=630a9718a0) | Apr 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [47831c9091](https://linux-hardware.org/?probe=47831c9091) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a775ede9a0](https://linux-hardware.org/?probe=a775ede9a0) | Apr 18, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [da85d2406d](https://linux-hardware.org/?probe=da85d2406d) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | [2a7fe6d74b](https://linux-hardware.org/?probe=2a7fe6d74b) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | [be92b53515](https://linux-hardware.org/?probe=be92b53515) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [dc707578c9](https://linux-hardware.org/?probe=dc707578c9) | Apr 18, 2023 |
| Gigabyte      | X570 GAMING X               | [f9f95d964c](https://linux-hardware.org/?probe=f9f95d964c) | Apr 18, 2023 |
| Medion        | BTDD-LT                     | [b26cb60a3f](https://linux-hardware.org/?probe=b26cb60a3f) | Apr 18, 2023 |
| ASUSTek       | PRIME A320M-K               | [fd82dc08dc](https://linux-hardware.org/?probe=fd82dc08dc) | Apr 18, 2023 |
| Gigabyte      | H77N-WIFI                   | [10e158aabd](https://linux-hardware.org/?probe=10e158aabd) | Apr 18, 2023 |
| ASRock        | B650M PG Riptide            | [89670d9e1f](https://linux-hardware.org/?probe=89670d9e1f) | Apr 17, 2023 |
| ASUSTek       | B85-PRO GAMER               | [bbe3e437d6](https://linux-hardware.org/?probe=bbe3e437d6) | Apr 17, 2023 |
| Dell          | 03NVJ6 A02                  | [2b0ef62ec7](https://linux-hardware.org/?probe=2b0ef62ec7) | Apr 17, 2023 |
| HP            | 1850                        | [fa2fa68792](https://linux-hardware.org/?probe=fa2fa68792) | Apr 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [307e22b0d6](https://linux-hardware.org/?probe=307e22b0d6) | Apr 17, 2023 |
| ASUSTek       | PRIME H410M-E               | [a537c2bd18](https://linux-hardware.org/?probe=a537c2bd18) | Apr 17, 2023 |
| MSI           | X570-A PRO                  | [65d3714b3b](https://linux-hardware.org/?probe=65d3714b3b) | Apr 17, 2023 |
| HP            | 8055                        | [f9b8b05db5](https://linux-hardware.org/?probe=f9b8b05db5) | Apr 17, 2023 |
| HP            | 8055                        | [462446d664](https://linux-hardware.org/?probe=462446d664) | Apr 17, 2023 |
| Dell          | 09KPNV A00                  | [c55a50526d](https://linux-hardware.org/?probe=c55a50526d) | Apr 16, 2023 |
| Medion        | MS-7728                     | [1da2d605db](https://linux-hardware.org/?probe=1da2d605db) | Apr 16, 2023 |
| Acer          | Aspire X3950                | [5a9abbd85f](https://linux-hardware.org/?probe=5a9abbd85f) | Apr 16, 2023 |
| ASUSTek       | X99-A/USB                   | [d686a4d03c](https://linux-hardware.org/?probe=d686a4d03c) | Apr 16, 2023 |
| ASRock        | X370 Killer SLI             | [912a7f830b](https://linux-hardware.org/?probe=912a7f830b) | Apr 16, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [286c8ef93c](https://linux-hardware.org/?probe=286c8ef93c) | Apr 16, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [0134b33f82](https://linux-hardware.org/?probe=0134b33f82) | Apr 16, 2023 |
| ASRock        | A300M-STX                   | [8f9e883980](https://linux-hardware.org/?probe=8f9e883980) | Apr 16, 2023 |
| ASRock        | Z270 Extreme4               | [c388675553](https://linux-hardware.org/?probe=c388675553) | Apr 16, 2023 |
| ASUSTek       | PRIME H410M-E               | [fedecfd9ff](https://linux-hardware.org/?probe=fedecfd9ff) | Apr 16, 2023 |
| Foxconn       | A7DA 3 series               | [a8f557c1c3](https://linux-hardware.org/?probe=a8f557c1c3) | Apr 16, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [c228cbe8e1](https://linux-hardware.org/?probe=c228cbe8e1) | Apr 16, 2023 |
| Foxconn       | A7DA 3 series               | [4f7648a3d0](https://linux-hardware.org/?probe=4f7648a3d0) | Apr 16, 2023 |
| Gigabyte      | B85-HD3                     | [25e7d545ae](https://linux-hardware.org/?probe=25e7d545ae) | Apr 16, 2023 |
| HP            | 18E4                        | [bc45bcdf89](https://linux-hardware.org/?probe=bc45bcdf89) | Apr 16, 2023 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | [4cb39d1136](https://linux-hardware.org/?probe=4cb39d1136) | Apr 15, 2023 |
| HP            | 8055                        | [7e5328ded9](https://linux-hardware.org/?probe=7e5328ded9) | Apr 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [e405d73576](https://linux-hardware.org/?probe=e405d73576) | Apr 15, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | [c34c2e032c](https://linux-hardware.org/?probe=c34c2e032c) | Apr 15, 2023 |
| Foxconn       | 2A8C                        | [8a75d034c7](https://linux-hardware.org/?probe=8a75d034c7) | Apr 15, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [9deba6cdac](https://linux-hardware.org/?probe=9deba6cdac) | Apr 15, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [c7568482a9](https://linux-hardware.org/?probe=c7568482a9) | Apr 15, 2023 |
| MSI           | Z390-A PRO                  | [7226bd3eab](https://linux-hardware.org/?probe=7226bd3eab) | Apr 15, 2023 |
| Gigabyte      | GA-870A-UD3                 | [a359e8f3ea](https://linux-hardware.org/?probe=a359e8f3ea) | Apr 15, 2023 |
| Acer          | WG43M                       | [a3a49836f9](https://linux-hardware.org/?probe=a3a49836f9) | Apr 15, 2023 |
| Biostar       | A960D+V2                    | [da262e3956](https://linux-hardware.org/?probe=da262e3956) | Apr 14, 2023 |
| ASUSTek       | ET1612I                     | [f67ace875b](https://linux-hardware.org/?probe=f67ace875b) | Apr 14, 2023 |
| MSI           | B450 GAMING PLUS            | [d49b1775be](https://linux-hardware.org/?probe=d49b1775be) | Apr 14, 2023 |
| Gigabyte      | B85M-D3H                    | [7041b36ac5](https://linux-hardware.org/?probe=7041b36ac5) | Apr 14, 2023 |
| Medion        | TJ4125                      | [887d24e023](https://linux-hardware.org/?probe=887d24e023) | Apr 14, 2023 |
| Dell          | 00V62H A01                  | [a06e8fe70f](https://linux-hardware.org/?probe=a06e8fe70f) | Apr 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [8a5b5b102c](https://linux-hardware.org/?probe=8a5b5b102c) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d7768947bc](https://linux-hardware.org/?probe=d7768947bc) | Apr 14, 2023 |
| ASRock        | A75M-HVS                    | [4d217e7a68](https://linux-hardware.org/?probe=4d217e7a68) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [d00ebfbc62](https://linux-hardware.org/?probe=d00ebfbc62) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [8b0e1ffa20](https://linux-hardware.org/?probe=8b0e1ffa20) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [3b2ac9206c](https://linux-hardware.org/?probe=3b2ac9206c) | Apr 14, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3741318176](https://linux-hardware.org/?probe=3741318176) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [16ee5e0082](https://linux-hardware.org/?probe=16ee5e0082) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [1b21351033](https://linux-hardware.org/?probe=1b21351033) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [f6f55c801f](https://linux-hardware.org/?probe=f6f55c801f) | Apr 14, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a1c457ea48](https://linux-hardware.org/?probe=a1c457ea48) | Apr 14, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [6cf54a6bf4](https://linux-hardware.org/?probe=6cf54a6bf4) | Apr 14, 2023 |
| ASRock        | B550 Steel Legend           | [9da868694f](https://linux-hardware.org/?probe=9da868694f) | Apr 14, 2023 |
| ASUSTek       | PRIME B450M-K II            | [9055d69d2f](https://linux-hardware.org/?probe=9055d69d2f) | Apr 14, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [5be961705c](https://linux-hardware.org/?probe=5be961705c) | Apr 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3aaeeb54ca](https://linux-hardware.org/?probe=3aaeeb54ca) | Apr 13, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [505fa87a7b](https://linux-hardware.org/?probe=505fa87a7b) | Apr 13, 2023 |
| HP            | 3397                        | [0e4d29ffcd](https://linux-hardware.org/?probe=0e4d29ffcd) | Apr 13, 2023 |
| HP            | 21EF                        | [d2b3751fd1](https://linux-hardware.org/?probe=d2b3751fd1) | Apr 13, 2023 |
| Gigabyte      | B550M DS3H                  | [d79c9f1cf1](https://linux-hardware.org/?probe=d79c9f1cf1) | Apr 12, 2023 |
| Gigabyte      | Z270-Gaming K3              | [0c03014734](https://linux-hardware.org/?probe=0c03014734) | Apr 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [df185fb277](https://linux-hardware.org/?probe=df185fb277) | Apr 12, 2023 |
| Gigabyte      | B450M DS3H V2               | [63c52bc5db](https://linux-hardware.org/?probe=63c52bc5db) | Apr 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [108725a205](https://linux-hardware.org/?probe=108725a205) | Apr 12, 2023 |
| MiTAC         | PD10EHI                     | [13f79a1843](https://linux-hardware.org/?probe=13f79a1843) | Apr 12, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [62a6c66983](https://linux-hardware.org/?probe=62a6c66983) | Apr 11, 2023 |
| Gigabyte      | EP45-DS3L                   | [ba55619ab6](https://linux-hardware.org/?probe=ba55619ab6) | Apr 11, 2023 |
| Gigabyte      | EP45-DS3L                   | [1a9f2f74bd](https://linux-hardware.org/?probe=1a9f2f74bd) | Apr 11, 2023 |
| MSI           | A320M-A PRO MAX             | [d5e033eb2e](https://linux-hardware.org/?probe=d5e033eb2e) | Apr 11, 2023 |
| Gigabyte      | GA-870A-UD3                 | [38d6c9f7ab](https://linux-hardware.org/?probe=38d6c9f7ab) | Apr 11, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [fcb884a8aa](https://linux-hardware.org/?probe=fcb884a8aa) | Apr 11, 2023 |
| Gigabyte      | Z390 UD                     | [9a5ae96f52](https://linux-hardware.org/?probe=9a5ae96f52) | Apr 11, 2023 |
| MSI           | MEG X570S ACE MAX           | [22e5416847](https://linux-hardware.org/?probe=22e5416847) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | [d041ee40cc](https://linux-hardware.org/?probe=d041ee40cc) | Apr 11, 2023 |
| ASUSTek       | H97I-PLUS                   | [8fdee327be](https://linux-hardware.org/?probe=8fdee327be) | Apr 11, 2023 |
| Dell          | 0K240Y A01                  | [1daf1b0ff6](https://linux-hardware.org/?probe=1daf1b0ff6) | Apr 10, 2023 |
| Gigabyte      | X570 GAMING X               | [761450c579](https://linux-hardware.org/?probe=761450c579) | Apr 10, 2023 |
| MSI           | B450M MORTAR MAX            | [e2cffb810b](https://linux-hardware.org/?probe=e2cffb810b) | Apr 10, 2023 |
| Lenovo        | 3138 SDK0J40697 WIN 3305... | [491da3c2c2](https://linux-hardware.org/?probe=491da3c2c2) | Apr 10, 2023 |
| ASRock        | B550M-ITX/ac                | [e043c1c94c](https://linux-hardware.org/?probe=e043c1c94c) | Apr 10, 2023 |
| ASRock        | X670E Pro RS                | [0f078152ca](https://linux-hardware.org/?probe=0f078152ca) | Apr 10, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [cd7d44fb7f](https://linux-hardware.org/?probe=cd7d44fb7f) | Apr 10, 2023 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [54fabc7712](https://linux-hardware.org/?probe=54fabc7712) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [5b0601fc42](https://linux-hardware.org/?probe=5b0601fc42) | Apr 09, 2023 |
| Medion        | TJ4125                      | [5c5f39a8fd](https://linux-hardware.org/?probe=5c5f39a8fd) | Apr 09, 2023 |
| Gigabyte      | B85M-D3H                    | [87be7a6dc0](https://linux-hardware.org/?probe=87be7a6dc0) | Apr 09, 2023 |
| MSI           | B350M MORTAR                | [03960a3def](https://linux-hardware.org/?probe=03960a3def) | Apr 09, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [e2521c6d93](https://linux-hardware.org/?probe=e2521c6d93) | Apr 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4644a0ea43](https://linux-hardware.org/?probe=4644a0ea43) | Apr 09, 2023 |
| MSI           | B450 GAMING PLUS            | [b35b8e1503](https://linux-hardware.org/?probe=b35b8e1503) | Apr 09, 2023 |
| Intel         | DH67BL AAG10189-207         | [1f13dff346](https://linux-hardware.org/?probe=1f13dff346) | Apr 08, 2023 |
| Gigabyte      | Q87M-D2H                    | [2c83dbd3ef](https://linux-hardware.org/?probe=2c83dbd3ef) | Apr 08, 2023 |
| Medion        | MS-7848                     | [40e46961a4](https://linux-hardware.org/?probe=40e46961a4) | Apr 08, 2023 |
| MSI           | B350 PC MATE                | [5c6c535e4d](https://linux-hardware.org/?probe=5c6c535e4d) | Apr 08, 2023 |
| AMI           | Cherry Trail CR             | [58dea5f209](https://linux-hardware.org/?probe=58dea5f209) | Apr 08, 2023 |
| ASUSTek       | P8H77-M PRO                 | [c8b30dba27](https://linux-hardware.org/?probe=c8b30dba27) | Apr 08, 2023 |
| HPE           | ProLiant MicroServer Gen... | [e378272577](https://linux-hardware.org/?probe=e378272577) | Apr 08, 2023 |
| Gigabyte      | B450M S2H                   | [f08d8d6bbd](https://linux-hardware.org/?probe=f08d8d6bbd) | Apr 08, 2023 |
| Acer          | Aspire X3990                | [4d4816d6f8](https://linux-hardware.org/?probe=4d4816d6f8) | Apr 08, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [36c87da9d9](https://linux-hardware.org/?probe=36c87da9d9) | Apr 07, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [c76171c0a7](https://linux-hardware.org/?probe=c76171c0a7) | Apr 07, 2023 |
| Inventec      | D CLASS A02                 | [3d53baddbf](https://linux-hardware.org/?probe=3d53baddbf) | Apr 07, 2023 |
| Inventec      | VXC Class A02               | [3ff1b18b81](https://linux-hardware.org/?probe=3ff1b18b81) | Apr 07, 2023 |
| MSI           | KA790GX                     | [c3dfb7614d](https://linux-hardware.org/?probe=c3dfb7614d) | Apr 07, 2023 |
| Foxconn       | 2A8C                        | [f202bac0de](https://linux-hardware.org/?probe=f202bac0de) | Apr 06, 2023 |
| ASRock        | A320M-DVS R4.0              | [c6e30ff3cc](https://linux-hardware.org/?probe=c6e30ff3cc) | Apr 06, 2023 |
| MSI           | B250M PRO-VDH               | [123883b7dd](https://linux-hardware.org/?probe=123883b7dd) | Apr 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9e99b4150b](https://linux-hardware.org/?probe=9e99b4150b) | Apr 06, 2023 |
| eMachines     | EL1352                      | [ccd83551e0](https://linux-hardware.org/?probe=ccd83551e0) | Apr 06, 2023 |
| HP            | 8055                        | [8ef78a4649](https://linux-hardware.org/?probe=8ef78a4649) | Apr 06, 2023 |
| HP            | 8055                        | [8afe68fd20](https://linux-hardware.org/?probe=8afe68fd20) | Apr 06, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [c599e701fc](https://linux-hardware.org/?probe=c599e701fc) | Apr 06, 2023 |
| MSI           | MEG X570S ACE MAX           | [57505ad220](https://linux-hardware.org/?probe=57505ad220) | Apr 06, 2023 |
| MSI           | MEG X570S ACE MAX           | [f3703c6b73](https://linux-hardware.org/?probe=f3703c6b73) | Apr 06, 2023 |
| ASUSTek       | PRIME Z370-A II             | [8f229e46c6](https://linux-hardware.org/?probe=8f229e46c6) | Apr 05, 2023 |
| ASUSTek       | H97M-PLUS                   | [ec5d1abdf5](https://linux-hardware.org/?probe=ec5d1abdf5) | Apr 05, 2023 |
| Lenovo        | 313A NOK                    | [824eadb157](https://linux-hardware.org/?probe=824eadb157) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [8b89901dc6](https://linux-hardware.org/?probe=8b89901dc6) | Apr 05, 2023 |
| Dell          | 0HHV7N A00                  | [b715735168](https://linux-hardware.org/?probe=b715735168) | Apr 05, 2023 |
| ASRock        | H87 Performance             | [34f591b007](https://linux-hardware.org/?probe=34f591b007) | Apr 05, 2023 |
| Dell          | 0HHV7N A00                  | [4f1c6c0b48](https://linux-hardware.org/?probe=4f1c6c0b48) | Apr 05, 2023 |
| ASRock        | A320M-DVS R4.0              | [6da0293a4b](https://linux-hardware.org/?probe=6da0293a4b) | Apr 05, 2023 |
| Gigabyte      | EP45-DS3L                   | [c400615c85](https://linux-hardware.org/?probe=c400615c85) | Apr 05, 2023 |
| Gigabyte      | EP45-DS3L                   | [85a4cbc899](https://linux-hardware.org/?probe=85a4cbc899) | Apr 05, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [5304b3bb66](https://linux-hardware.org/?probe=5304b3bb66) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [5012c822d7](https://linux-hardware.org/?probe=5012c822d7) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [33eb81c75e](https://linux-hardware.org/?probe=33eb81c75e) | Apr 05, 2023 |
| ASUSTek       | M4A87TD EVO                 | [6f3f9cf977](https://linux-hardware.org/?probe=6f3f9cf977) | Apr 05, 2023 |
| Gigabyte      | GA-A75M-UD2H                | [7f4b812a58](https://linux-hardware.org/?probe=7f4b812a58) | Apr 05, 2023 |
| BESSTAR Te... | UM350                       | [ccff8e1838](https://linux-hardware.org/?probe=ccff8e1838) | Apr 05, 2023 |
| Gigabyte      | H61MA-D3V                   | [ba4ee67415](https://linux-hardware.org/?probe=ba4ee67415) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | [58cf8c28ff](https://linux-hardware.org/?probe=58cf8c28ff) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | [7f904181ea](https://linux-hardware.org/?probe=7f904181ea) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [aa3b0a7d6f](https://linux-hardware.org/?probe=aa3b0a7d6f) | Apr 04, 2023 |
| ASUSTek       | A68HM-PLUS                  | [4246e4df2b](https://linux-hardware.org/?probe=4246e4df2b) | Apr 04, 2023 |
| Dell          | 0VHWTR A02                  | [64ca43bef0](https://linux-hardware.org/?probe=64ca43bef0) | Apr 04, 2023 |
| Dell          | 0VHWTR A02                  | [ac36b6f948](https://linux-hardware.org/?probe=ac36b6f948) | Apr 04, 2023 |
| Dell          | 0GX297                      | [5d1513fb01](https://linux-hardware.org/?probe=5d1513fb01) | Apr 04, 2023 |
| Acer          | WG43M                       | [10bf0c0d1a](https://linux-hardware.org/?probe=10bf0c0d1a) | Apr 04, 2023 |
| MSI           | B450-A PRO MAX              | [31d10a7e98](https://linux-hardware.org/?probe=31d10a7e98) | Apr 04, 2023 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | [015c7769f4](https://linux-hardware.org/?probe=015c7769f4) | Apr 04, 2023 |
| Dell          | 0D6H9T A00                  | [2bedb15c21](https://linux-hardware.org/?probe=2bedb15c21) | Apr 04, 2023 |
| ASUSTek       | P5N-EM HDMI                 | [2db7dfe129](https://linux-hardware.org/?probe=2db7dfe129) | Apr 04, 2023 |
| Dell          | 0GX297                      | [80c6b0b4f3](https://linux-hardware.org/?probe=80c6b0b4f3) | Apr 04, 2023 |
| Medion        | MS-7707                     | [c490d9dc74](https://linux-hardware.org/?probe=c490d9dc74) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2fccbc61e2](https://linux-hardware.org/?probe=2fccbc61e2) | Apr 04, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [60f7987af4](https://linux-hardware.org/?probe=60f7987af4) | Apr 04, 2023 |
| MSI           | PRO X670-P WIFI             | [a1457b032d](https://linux-hardware.org/?probe=a1457b032d) | Apr 03, 2023 |
| ASUSTek       | PRIME X370-PRO              | [c05957b7c0](https://linux-hardware.org/?probe=c05957b7c0) | Apr 03, 2023 |
| MSI           | X570-A PRO                  | [a03fbcf098](https://linux-hardware.org/?probe=a03fbcf098) | Apr 03, 2023 |
| MSI           | B450 GAMING PLUS            | [731bd99503](https://linux-hardware.org/?probe=731bd99503) | Apr 03, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [aaa2e273c1](https://linux-hardware.org/?probe=aaa2e273c1) | Apr 03, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [db0170e4f7](https://linux-hardware.org/?probe=db0170e4f7) | Apr 03, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [11d3f42d9c](https://linux-hardware.org/?probe=11d3f42d9c) | Apr 03, 2023 |
| MSI           | B450-A PRO                  | [c487bcedab](https://linux-hardware.org/?probe=c487bcedab) | Apr 03, 2023 |
| Unknown       | Unknown                     | [cbcfbb8783](https://linux-hardware.org/?probe=cbcfbb8783) | Apr 03, 2023 |
| BESSTAR Te... | HM90                        | [722013016f](https://linux-hardware.org/?probe=722013016f) | Apr 03, 2023 |
| Acer          | Veriton X4610G              | [49b3c45306](https://linux-hardware.org/?probe=49b3c45306) | Apr 03, 2023 |
| Shuttle       | FH370                       | [29b2ad6149](https://linux-hardware.org/?probe=29b2ad6149) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [f9d9946012](https://linux-hardware.org/?probe=f9d9946012) | Apr 02, 2023 |
| MSI           | MAG H670 TOMAHAWK WIFI D... | [453a5fd36e](https://linux-hardware.org/?probe=453a5fd36e) | Apr 02, 2023 |
| ASRock        | B450M Pro4                  | [7bfb9086ab](https://linux-hardware.org/?probe=7bfb9086ab) | Apr 02, 2023 |
| Medion        | MS-7728                     | [83f7f01bde](https://linux-hardware.org/?probe=83f7f01bde) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ea4626fdcc](https://linux-hardware.org/?probe=ea4626fdcc) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [118effffda](https://linux-hardware.org/?probe=118effffda) | Apr 02, 2023 |
| MSI           | FM2-A75IA-E53               | [f8092c0da9](https://linux-hardware.org/?probe=f8092c0da9) | Apr 02, 2023 |
| MSI           | B350 GAMING PRO CARBON      | [0ffb7303f2](https://linux-hardware.org/?probe=0ffb7303f2) | Apr 02, 2023 |
| MSI           | MPG Z590 GAMING CARBON W... | [d0006b7678](https://linux-hardware.org/?probe=d0006b7678) | Apr 02, 2023 |
| HP            | 0AA4h                       | [9b84d8c935](https://linux-hardware.org/?probe=9b84d8c935) | Apr 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [bc77efa103](https://linux-hardware.org/?probe=bc77efa103) | Apr 01, 2023 |
| MSI           | MS-7318                     | [3d02816b24](https://linux-hardware.org/?probe=3d02816b24) | Apr 01, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [d645276b0a](https://linux-hardware.org/?probe=d645276b0a) | Apr 01, 2023 |
| Medion        | TJ4125                      | [2627cc2d42](https://linux-hardware.org/?probe=2627cc2d42) | Apr 01, 2023 |
| Gigabyte      | B85M-D3H                    | [77187502c9](https://linux-hardware.org/?probe=77187502c9) | Apr 01, 2023 |
| Gigabyte      | Q87M-D2H                    | [4552b7c999](https://linux-hardware.org/?probe=4552b7c999) | Apr 01, 2023 |
| MSI           | P67A-C43                    | [f3e7913310](https://linux-hardware.org/?probe=f3e7913310) | Apr 01, 2023 |
| BESSTAR Te... | HM80                        | [4242425ada](https://linux-hardware.org/?probe=4242425ada) | Apr 01, 2023 |
| BESSTAR Te... | HM80                        | [702890870e](https://linux-hardware.org/?probe=702890870e) | Apr 01, 2023 |
| Unknown       | Unknown                     | [fdd5cd8cd8](https://linux-hardware.org/?probe=fdd5cd8cd8) | Apr 01, 2023 |
| AZW           | MINI S 10                   | [19d66110ff](https://linux-hardware.org/?probe=19d66110ff) | Apr 01, 2023 |
| MSI           | 970A-G46                    | [92ee520881](https://linux-hardware.org/?probe=92ee520881) | Apr 01, 2023 |
| Biostar       | A740G M2+                   | [182d84f68a](https://linux-hardware.org/?probe=182d84f68a) | Apr 01, 2023 |
| Gigabyte      | Q87M-D2H                    | [b627db43dd](https://linux-hardware.org/?probe=b627db43dd) | Apr 01, 2023 |
| Lenovo        | 317E SDK0K17763 WIN 1801... | [a4cad34ac9](https://linux-hardware.org/?probe=a4cad34ac9) | Apr 01, 2023 |
| Dell          | 0MGK50 A02                  | [3a042b5160](https://linux-hardware.org/?probe=3a042b5160) | Apr 01, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [824aa0ae13](https://linux-hardware.org/?probe=824aa0ae13) | Apr 01, 2023 |
| ASUSTek       | PRIME X470-PRO              | [96fcc41161](https://linux-hardware.org/?probe=96fcc41161) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS            | [539137fb36](https://linux-hardware.org/?probe=539137fb36) | Apr 01, 2023 |
| Acer          | Aspire XC-780               | [206239c162](https://linux-hardware.org/?probe=206239c162) | Apr 01, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [86241cd6ad](https://linux-hardware.org/?probe=86241cd6ad) | Apr 01, 2023 |
| HP            | 84FD                        | [79367d5f7d](https://linux-hardware.org/?probe=79367d5f7d) | Apr 01, 2023 |
| Lenovo        | ThinkCentre M58 9728AHG     | [cb0fa70953](https://linux-hardware.org/?probe=cb0fa70953) | Apr 01, 2023 |
| HP            | 2AFA                        | [d177838277](https://linux-hardware.org/?probe=d177838277) | Mar 31, 2023 |
| ASRock        | Z87 Extreme6                | [675d214cbe](https://linux-hardware.org/?probe=675d214cbe) | Mar 31, 2023 |
| Dell          | 0JP3NX A00                  | [016632c560](https://linux-hardware.org/?probe=016632c560) | Mar 31, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | [672242513c](https://linux-hardware.org/?probe=672242513c) | Mar 31, 2023 |
| ASUSTek       | A68HM-PLUS                  | [520ad2ca86](https://linux-hardware.org/?probe=520ad2ca86) | Mar 31, 2023 |
| ASRock        | A320M-DVS R4.0              | [e6463ab36d](https://linux-hardware.org/?probe=e6463ab36d) | Mar 31, 2023 |
| Gigabyte      | Z390 M-CF                   | [a939015daa](https://linux-hardware.org/?probe=a939015daa) | Mar 31, 2023 |
| MSI           | B550-A PRO                  | [ab4f36e0fa](https://linux-hardware.org/?probe=ab4f36e0fa) | Mar 31, 2023 |
| ASRock        | B760M Pro RS/D4             | [6a63402e9c](https://linux-hardware.org/?probe=6a63402e9c) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [9addea9f4a](https://linux-hardware.org/?probe=9addea9f4a) | Mar 31, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [fc9a42e387](https://linux-hardware.org/?probe=fc9a42e387) | Mar 31, 2023 |
| ASUSTek       | Z97-K                       | [da56f6c38c](https://linux-hardware.org/?probe=da56f6c38c) | Mar 31, 2023 |
| ASUSTek       | P8H67-M LE                  | [11b3a7cdb1](https://linux-hardware.org/?probe=11b3a7cdb1) | Mar 31, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [0945961c85](https://linux-hardware.org/?probe=0945961c85) | Mar 31, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [72c08c8ca9](https://linux-hardware.org/?probe=72c08c8ca9) | Mar 31, 2023 |
| Gigabyte      | B450 GAMING X               | [495c58a5c6](https://linux-hardware.org/?probe=495c58a5c6) | Mar 31, 2023 |
| ASUSTek       | H110M-R                     | [bd1a48e47d](https://linux-hardware.org/?probe=bd1a48e47d) | Mar 31, 2023 |
| Gigabyte      | A320M-S2H-CF                | [1c982255fa](https://linux-hardware.org/?probe=1c982255fa) | Mar 31, 2023 |
| ASRock        | Z97 Anniversary             | [c23aeb60ba](https://linux-hardware.org/?probe=c23aeb60ba) | Mar 31, 2023 |
| ECS           | G31T-M7                     | [c197c4ed1d](https://linux-hardware.org/?probe=c197c4ed1d) | Mar 31, 2023 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [56c886069b](https://linux-hardware.org/?probe=56c886069b) | Mar 31, 2023 |
| ASUSTek       | Z87-K                       | [e596dbb5bd](https://linux-hardware.org/?probe=e596dbb5bd) | Mar 30, 2023 |
| ASUSTek       | EB1036                      | [955d389e06](https://linux-hardware.org/?probe=955d389e06) | Mar 30, 2023 |
| Unknown       | Unknown                     | [3773f3cd04](https://linux-hardware.org/?probe=3773f3cd04) | Mar 30, 2023 |
| Packard Be... | FMP55                       | [88a15e20b2](https://linux-hardware.org/?probe=88a15e20b2) | Mar 30, 2023 |
| ASUSTek       | B85M-E                      | [7c7f9d0e36](https://linux-hardware.org/?probe=7c7f9d0e36) | Mar 30, 2023 |
| Acer          | Aspire XC-1760              | [68e6aec940](https://linux-hardware.org/?probe=68e6aec940) | Mar 30, 2023 |
| HP            | 339A                        | [8f484ab259](https://linux-hardware.org/?probe=8f484ab259) | Mar 30, 2023 |
| MSI           | X79A-GD45                   | [6d78703b2c](https://linux-hardware.org/?probe=6d78703b2c) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [fbcdd4ed13](https://linux-hardware.org/?probe=fbcdd4ed13) | Mar 30, 2023 |
| HP            | 0AA4h                       | [97457bb10c](https://linux-hardware.org/?probe=97457bb10c) | Mar 30, 2023 |
| Medion        | B250H4-EM                   | [f569d44749](https://linux-hardware.org/?probe=f569d44749) | Mar 30, 2023 |
| HP            | 8399                        | [d8c0ad05f5](https://linux-hardware.org/?probe=d8c0ad05f5) | Mar 30, 2023 |
| Intel         | D510MO AAE76523-403         | [0d06f88081](https://linux-hardware.org/?probe=0d06f88081) | Mar 30, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [936e8b10c5](https://linux-hardware.org/?probe=936e8b10c5) | Mar 30, 2023 |
| MSI           | B550-A PRO                  | [b4a4247459](https://linux-hardware.org/?probe=b4a4247459) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [baf3c567a7](https://linux-hardware.org/?probe=baf3c567a7) | Mar 29, 2023 |
| Medion        | TJ4125                      | [e03693b0f0](https://linux-hardware.org/?probe=e03693b0f0) | Mar 29, 2023 |
| ASRock        | B550M Pro4                  | [a78f53a6b4](https://linux-hardware.org/?probe=a78f53a6b4) | Mar 29, 2023 |
| ASRock        | B550M Pro4                  | [a4c3b109dc](https://linux-hardware.org/?probe=a4c3b109dc) | Mar 29, 2023 |
| ASUSTek       | PRIME A320M-K               | [4f9eed1de2](https://linux-hardware.org/?probe=4f9eed1de2) | Mar 29, 2023 |
| MSI           | X79A-GD45                   | [bb4680bc5b](https://linux-hardware.org/?probe=bb4680bc5b) | Mar 29, 2023 |
| HP            | 0AA4h                       | [801f843749](https://linux-hardware.org/?probe=801f843749) | Mar 29, 2023 |
| Lenovo        | 30D2 NOK                    | [e4d898e37d](https://linux-hardware.org/?probe=e4d898e37d) | Mar 29, 2023 |
| ASUSTek       | A78M-A                      | [e2ee931df2](https://linux-hardware.org/?probe=e2ee931df2) | Mar 28, 2023 |
| ASUSTek       | M3N78 PRO                   | [0f9abe9400](https://linux-hardware.org/?probe=0f9abe9400) | Mar 28, 2023 |
| ASUSTek       | Z97-P                       | [0a0ca96d28](https://linux-hardware.org/?probe=0a0ca96d28) | Mar 28, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [4807db08a9](https://linux-hardware.org/?probe=4807db08a9) | Mar 28, 2023 |
| Unknown       | Unknown                     | [fb22157f03](https://linux-hardware.org/?probe=fb22157f03) | Mar 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ad5969356b](https://linux-hardware.org/?probe=ad5969356b) | Mar 28, 2023 |
| Gigabyte      | B85M-D3H                    | [a074e581b0](https://linux-hardware.org/?probe=a074e581b0) | Mar 28, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [1c14b29af5](https://linux-hardware.org/?probe=1c14b29af5) | Mar 28, 2023 |
| ASUSTek       | PRIME B450M-A II            | [4fe0ddab4b](https://linux-hardware.org/?probe=4fe0ddab4b) | Mar 28, 2023 |
| Gigabyte      | X58A-UD3R                   | [74d9c5e704](https://linux-hardware.org/?probe=74d9c5e704) | Mar 28, 2023 |
| Lenovo        | ThinkStation S30 0568E8G    | [ea3855cca5](https://linux-hardware.org/?probe=ea3855cca5) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [611b42e6fd](https://linux-hardware.org/?probe=611b42e6fd) | Mar 28, 2023 |
| Acer          | Predator G3-605             | [8caea0f833](https://linux-hardware.org/?probe=8caea0f833) | Mar 27, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | [91a63afb10](https://linux-hardware.org/?probe=91a63afb10) | Mar 27, 2023 |
| Gigabyte      | B450M S2H                   | [0901eb1e27](https://linux-hardware.org/?probe=0901eb1e27) | Mar 27, 2023 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [8d039976c9](https://linux-hardware.org/?probe=8d039976c9) | Mar 27, 2023 |
| MSI           | B550 GAMING GEN3            | [8b14146424](https://linux-hardware.org/?probe=8b14146424) | Mar 27, 2023 |
| Gigabyte      | H97M-HD3                    | [1b531d5ada](https://linux-hardware.org/?probe=1b531d5ada) | Mar 27, 2023 |
| ASUSTek       | PRIME Z590-P                | [ab55adbf68](https://linux-hardware.org/?probe=ab55adbf68) | Mar 27, 2023 |
| ASRock        | 770 Extreme3                | [9cd5d1485c](https://linux-hardware.org/?probe=9cd5d1485c) | Mar 27, 2023 |
| Gigabyte      | Q87M-D2H                    | [dd71be113d](https://linux-hardware.org/?probe=dd71be113d) | Mar 27, 2023 |
| Medion        | TJ4125                      | [571b476915](https://linux-hardware.org/?probe=571b476915) | Mar 27, 2023 |
| Lenovo        | 102F NO DPK                 | [85a4bbf301](https://linux-hardware.org/?probe=85a4bbf301) | Mar 27, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [94cd15664b](https://linux-hardware.org/?probe=94cd15664b) | Mar 27, 2023 |
| HP            | 3648h                       | [fbc5138852](https://linux-hardware.org/?probe=fbc5138852) | Mar 27, 2023 |
| Lenovo        | ThinkCentre M71e 3157AE2    | [a71ced0077](https://linux-hardware.org/?probe=a71ced0077) | Mar 27, 2023 |
| Gigabyte      | H87M-D3H                    | [b277bc971f](https://linux-hardware.org/?probe=b277bc971f) | Mar 27, 2023 |
| MSI           | B450 GAMING PLUS            | [5242d56a0f](https://linux-hardware.org/?probe=5242d56a0f) | Mar 27, 2023 |
| ASUSTek       | H110-PLUS                   | [b108ebc14f](https://linux-hardware.org/?probe=b108ebc14f) | Mar 27, 2023 |
| ASRock        | B450M Pro4                  | [a6bb6f959c](https://linux-hardware.org/?probe=a6bb6f959c) | Mar 27, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [8af0f96567](https://linux-hardware.org/?probe=8af0f96567) | Mar 27, 2023 |
| ASRock        | AM1B-ITX                    | [e5dc5f70ac](https://linux-hardware.org/?probe=e5dc5f70ac) | Mar 27, 2023 |
| ASUSTek       | N3150I-C                    | [6c977806a1](https://linux-hardware.org/?probe=6c977806a1) | Mar 27, 2023 |
| Gigabyte      | A520M H                     | [7afe508254](https://linux-hardware.org/?probe=7afe508254) | Mar 27, 2023 |
| Gigabyte      | Z590 GAMING X               | [de1cb772e9](https://linux-hardware.org/?probe=de1cb772e9) | Mar 27, 2023 |
| Gigabyte      | Z590 GAMING X               | [db7671affd](https://linux-hardware.org/?probe=db7671affd) | Mar 27, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [83448b2d9b](https://linux-hardware.org/?probe=83448b2d9b) | Mar 26, 2023 |
| ASRock        | X300-ITX                    | [34402bbf9b](https://linux-hardware.org/?probe=34402bbf9b) | Mar 26, 2023 |
| MSI           | Z490 PLUS                   | [06032b5e04](https://linux-hardware.org/?probe=06032b5e04) | Mar 26, 2023 |
| ASRock        | B450M-HDV R4.0              | [e069fb2622](https://linux-hardware.org/?probe=e069fb2622) | Mar 26, 2023 |
| Medion        | P2A4-EM                     | [45e86dd60d](https://linux-hardware.org/?probe=45e86dd60d) | Mar 26, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [a8d31fc431](https://linux-hardware.org/?probe=a8d31fc431) | Mar 26, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Gigabyte      | H67MA-USB3-B3               | [ae3d30a042](https://linux-hardware.org/?probe=ae3d30a042) | Mar 26, 2023 |
| Gigabyte      | H67MA-USB3-B3               | [b31a6f01f6](https://linux-hardware.org/?probe=b31a6f01f6) | Mar 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [b527095c8c](https://linux-hardware.org/?probe=b527095c8c) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [6553d2c85a](https://linux-hardware.org/?probe=6553d2c85a) | Mar 26, 2023 |
| Chuwi         | RZBOX                       | [14ef8add03](https://linux-hardware.org/?probe=14ef8add03) | Mar 26, 2023 |
| Gigabyte      | Q87M-D2H                    | [8690ae647e](https://linux-hardware.org/?probe=8690ae647e) | Mar 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cba16003d7](https://linux-hardware.org/?probe=cba16003d7) | Mar 26, 2023 |
| ASUSTek       | M2N68-AM Plus               | [e274c03773](https://linux-hardware.org/?probe=e274c03773) | Mar 26, 2023 |
| Gigabyte      | A520M H                     | [cfacabcd33](https://linux-hardware.org/?probe=cfacabcd33) | Mar 26, 2023 |
| Gigabyte      | A520M H                     | [ed01b04ada](https://linux-hardware.org/?probe=ed01b04ada) | Mar 26, 2023 |
| ASUSTek       | PRIME A520M-K               | [f01520e14a](https://linux-hardware.org/?probe=f01520e14a) | Mar 26, 2023 |
| Gigabyte      | B85M-D3H                    | [890cd39d63](https://linux-hardware.org/?probe=890cd39d63) | Mar 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [74cf067852](https://linux-hardware.org/?probe=74cf067852) | Mar 26, 2023 |
| Shuttle       | B10IE01                     | [bc74a6b1a2](https://linux-hardware.org/?probe=bc74a6b1a2) | Mar 26, 2023 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | [0fc1609d81](https://linux-hardware.org/?probe=0fc1609d81) | Mar 26, 2023 |
| Dell          | 0MGK50 A02                  | [93b35b776a](https://linux-hardware.org/?probe=93b35b776a) | Mar 26, 2023 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | [b7b93f24a2](https://linux-hardware.org/?probe=b7b93f24a2) | Mar 26, 2023 |
| Medion        | TJ4125                      | [74b96baec4](https://linux-hardware.org/?probe=74b96baec4) | Mar 25, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [cb325c06e8](https://linux-hardware.org/?probe=cb325c06e8) | Mar 25, 2023 |
| Lenovo        | 30D2 NOK                    | [dc62baadff](https://linux-hardware.org/?probe=dc62baadff) | Mar 25, 2023 |
| ASUSTek       | P8H77-M                     | [6fc56d2339](https://linux-hardware.org/?probe=6fc56d2339) | Mar 25, 2023 |
| HP            | 3397                        | [2ad66803de](https://linux-hardware.org/?probe=2ad66803de) | Mar 25, 2023 |
| Packard Be... | FIH57                       | [794fd45482](https://linux-hardware.org/?probe=794fd45482) | Mar 25, 2023 |
| MSI           | H81M-P33                    | [0944bc82b9](https://linux-hardware.org/?probe=0944bc82b9) | Mar 25, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [76d02ffbf0](https://linux-hardware.org/?probe=76d02ffbf0) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [227aba28f2](https://linux-hardware.org/?probe=227aba28f2) | Mar 25, 2023 |
| MSI           | H110M PRO-D                 | [104b9b1c12](https://linux-hardware.org/?probe=104b9b1c12) | Mar 25, 2023 |
| MSI           | H110M PRO-D                 | [a822425dcf](https://linux-hardware.org/?probe=a822425dcf) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [f2b287b461](https://linux-hardware.org/?probe=f2b287b461) | Mar 25, 2023 |
| MSI           | MEG X570S ACE MAX           | [3a32e79b17](https://linux-hardware.org/?probe=3a32e79b17) | Mar 25, 2023 |
| HPE           | ProLiant MicroServer Gen... | [72f90312db](https://linux-hardware.org/?probe=72f90312db) | Mar 25, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [ca8bcc6073](https://linux-hardware.org/?probe=ca8bcc6073) | Mar 25, 2023 |
| ASUSTek       | PRIME Z590-A                | [9a8b9b917f](https://linux-hardware.org/?probe=9a8b9b917f) | Mar 24, 2023 |
| HP            | 3048h                       | [69cd88b0c0](https://linux-hardware.org/?probe=69cd88b0c0) | Mar 24, 2023 |
| ASUSTek       | M4A78T-E                    | [a820ffe411](https://linux-hardware.org/?probe=a820ffe411) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [dac7782920](https://linux-hardware.org/?probe=dac7782920) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [ec6fdc917b](https://linux-hardware.org/?probe=ec6fdc917b) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9240540b33](https://linux-hardware.org/?probe=9240540b33) | Mar 24, 2023 |
| HPE           | ProLiant MicroServer Gen... | [2c8daaa4f2](https://linux-hardware.org/?probe=2c8daaa4f2) | Mar 24, 2023 |
| Fujitsu       | D3162-B1 S26361-D3162-B1    | [a2c287936d](https://linux-hardware.org/?probe=a2c287936d) | Mar 24, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [a5795c9f91](https://linux-hardware.org/?probe=a5795c9f91) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [fd2f6925ba](https://linux-hardware.org/?probe=fd2f6925ba) | Mar 23, 2023 |
| MSI           | G41M-P26                    | [49854744e6](https://linux-hardware.org/?probe=49854744e6) | Mar 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c83000783a](https://linux-hardware.org/?probe=c83000783a) | Mar 23, 2023 |
| MSI           | MEG X570S ACE MAX           | [528ed2d3af](https://linux-hardware.org/?probe=528ed2d3af) | Mar 23, 2023 |
| Lenovo        | ThinkCentre M58 9728AHG     | [e1cfc1c76d](https://linux-hardware.org/?probe=e1cfc1c76d) | Mar 23, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [effc5602f9](https://linux-hardware.org/?probe=effc5602f9) | Mar 23, 2023 |
| MSI           | MS-7255                     | [7322068101](https://linux-hardware.org/?probe=7322068101) | Mar 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [bbd16627c2](https://linux-hardware.org/?probe=bbd16627c2) | Mar 22, 2023 |
| Dell          | 0X9M3X A01                  | [38f83864e4](https://linux-hardware.org/?probe=38f83864e4) | Mar 22, 2023 |
| ASUSTek       | P9X79 PRO                   | [fdc301b3ab](https://linux-hardware.org/?probe=fdc301b3ab) | Mar 22, 2023 |
| Dell          | 0NW73C A01                  | [39e1f031d9](https://linux-hardware.org/?probe=39e1f031d9) | Mar 22, 2023 |
| ASRockRack    | B665D4U-1L                  | [2be23ead3c](https://linux-hardware.org/?probe=2be23ead3c) | Mar 22, 2023 |
| Unknown       | Unknown                     | [de1dd4e459](https://linux-hardware.org/?probe=de1dd4e459) | Mar 22, 2023 |
| Unknown       | Unknown                     | [33ebf18165](https://linux-hardware.org/?probe=33ebf18165) | Mar 22, 2023 |
| Dell          | 0RK936                      | [af3e7f60cb](https://linux-hardware.org/?probe=af3e7f60cb) | Mar 22, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | [2f50a76b96](https://linux-hardware.org/?probe=2f50a76b96) | Mar 22, 2023 |
| ASRock        | FM2A68M-HD+                 | [7723ce424a](https://linux-hardware.org/?probe=7723ce424a) | Mar 21, 2023 |
| Dell          | 0RK936                      | [6c2680e4e9](https://linux-hardware.org/?probe=6c2680e4e9) | Mar 21, 2023 |
| Dell          | 0DFRFW A01                  | [0d10f51874](https://linux-hardware.org/?probe=0d10f51874) | Mar 21, 2023 |
| NZXT          | N7 B550                     | [8ca9bc3db9](https://linux-hardware.org/?probe=8ca9bc3db9) | Mar 21, 2023 |
| MSI           | Z170A GAMING PRO            | [8948f99354](https://linux-hardware.org/?probe=8948f99354) | Mar 21, 2023 |
| Dell          | 0XCR8D A00                  | [e86eb83730](https://linux-hardware.org/?probe=e86eb83730) | Mar 21, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [5ea7504472](https://linux-hardware.org/?probe=5ea7504472) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [cd12accab0](https://linux-hardware.org/?probe=cd12accab0) | Mar 21, 2023 |
| Packard Be... | IXTREME M5800               | [62d90f07ba](https://linux-hardware.org/?probe=62d90f07ba) | Mar 20, 2023 |
| Unknown       | Unknown                     | [a931b7a520](https://linux-hardware.org/?probe=a931b7a520) | Mar 20, 2023 |
| Packard Be... | IXTREME M5800               | [653b1820fe](https://linux-hardware.org/?probe=653b1820fe) | Mar 20, 2023 |
| Gigabyte      | Z68A-D3H-B3                 | [6c420d8fba](https://linux-hardware.org/?probe=6c420d8fba) | Mar 20, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [db3e17d5f1](https://linux-hardware.org/?probe=db3e17d5f1) | Mar 20, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [5eee23b1db](https://linux-hardware.org/?probe=5eee23b1db) | Mar 20, 2023 |
| Gigabyte      | H81M-HD3                    | [8aaef31933](https://linux-hardware.org/?probe=8aaef31933) | Mar 19, 2023 |
| ASRock        | G31M-GS                     | [abef6c6862](https://linux-hardware.org/?probe=abef6c6862) | Mar 19, 2023 |
| ASRock        | B450M Pro4                  | [81e36f47be](https://linux-hardware.org/?probe=81e36f47be) | Mar 19, 2023 |
| HP            | 0A9Ch                       | [e29fa7c9f7](https://linux-hardware.org/?probe=e29fa7c9f7) | Mar 19, 2023 |
| Gigabyte      | 990FXA-UD5                  | [0daa99f732](https://linux-hardware.org/?probe=0daa99f732) | Mar 19, 2023 |
| Gigabyte      | Q87M-D2H                    | [fb5c67c585](https://linux-hardware.org/?probe=fb5c67c585) | Mar 19, 2023 |
| Gigabyte      | B85M-D3H                    | [605bc3d5b0](https://linux-hardware.org/?probe=605bc3d5b0) | Mar 19, 2023 |
| MSI           | A68HM-P33                   | [3e8c6c3d52](https://linux-hardware.org/?probe=3e8c6c3d52) | Mar 19, 2023 |
| ASRock        | Z590M-ITX/ax                | [715b1e5c6b](https://linux-hardware.org/?probe=715b1e5c6b) | Mar 18, 2023 |
| Medion        | TJ4125                      | [6895b929a4](https://linux-hardware.org/?probe=6895b929a4) | Mar 18, 2023 |
| ASRock        | X570 Steel Legend           | [480bbff9d1](https://linux-hardware.org/?probe=480bbff9d1) | Mar 18, 2023 |
| ASUSTek       | M4A87TD/USB3                | [ed76176dfa](https://linux-hardware.org/?probe=ed76176dfa) | Mar 18, 2023 |
| Gigabyte      | 990FXA-UD7                  | [faab19eb56](https://linux-hardware.org/?probe=faab19eb56) | Mar 18, 2023 |
| Gigabyte      | Q87M-D2H                    | [7051e25dc0](https://linux-hardware.org/?probe=7051e25dc0) | Mar 18, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [a3e8bcd9dd](https://linux-hardware.org/?probe=a3e8bcd9dd) | Mar 18, 2023 |
| ASUSTek       | X99-E WS/USB                | [f8029380c5](https://linux-hardware.org/?probe=f8029380c5) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d8004fdcde](https://linux-hardware.org/?probe=d8004fdcde) | Mar 18, 2023 |
| Fujitsu       | D3601-A1 S26361-D3601-A1    | [ec47c2dcb7](https://linux-hardware.org/?probe=ec47c2dcb7) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | [8a94a38026](https://linux-hardware.org/?probe=8a94a38026) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | [31851c4e15](https://linux-hardware.org/?probe=31851c4e15) | Mar 18, 2023 |
| Gigabyte      | B85M-D3H                    | [4cee2dc95e](https://linux-hardware.org/?probe=4cee2dc95e) | Mar 18, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | [8cf99eb521](https://linux-hardware.org/?probe=8cf99eb521) | Mar 18, 2023 |
| ASUSTek       | A68HM-PLUS                  | [5d307f2d26](https://linux-hardware.org/?probe=5d307f2d26) | Mar 18, 2023 |
| Acer          | Aspire XC600 v1.0           | [ef3e267972](https://linux-hardware.org/?probe=ef3e267972) | Mar 18, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [7cf7439659](https://linux-hardware.org/?probe=7cf7439659) | Mar 18, 2023 |
| Gigabyte      | Z68XP-UD4                   | [9d5f79bbf4](https://linux-hardware.org/?probe=9d5f79bbf4) | Mar 18, 2023 |
| ASUSTek       | M5A97 R2.0                  | [cd8dd26e2d](https://linux-hardware.org/?probe=cd8dd26e2d) | Mar 17, 2023 |
| Medion        | MS-7707                     | [4748632926](https://linux-hardware.org/?probe=4748632926) | Mar 17, 2023 |
| Gigabyte      | B450 AORUS M                | [79a285d86b](https://linux-hardware.org/?probe=79a285d86b) | Mar 17, 2023 |
| Medion        | H81H3-EM2 H81EM2W08.217     | [1e1a430355](https://linux-hardware.org/?probe=1e1a430355) | Mar 17, 2023 |
| Gigabyte      | H110M-S2HP-CF               | [17d28488f3](https://linux-hardware.org/?probe=17d28488f3) | Mar 17, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [557a99333f](https://linux-hardware.org/?probe=557a99333f) | Mar 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | [7e11b106d7](https://linux-hardware.org/?probe=7e11b106d7) | Mar 17, 2023 |
| ASUSTek       | PRIME B450M-A               | [fbf7dd9d94](https://linux-hardware.org/?probe=fbf7dd9d94) | Mar 17, 2023 |
| ASRock        | B450M Pro4                  | [a0fd9e4138](https://linux-hardware.org/?probe=a0fd9e4138) | Mar 16, 2023 |
| Packard Be... | IXTREME M5800               | [4efa1b8600](https://linux-hardware.org/?probe=4efa1b8600) | Mar 16, 2023 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [14c33dda50](https://linux-hardware.org/?probe=14c33dda50) | Mar 16, 2023 |
| Inventec      | D CLASS A02                 | [6b0555ac0f](https://linux-hardware.org/?probe=6b0555ac0f) | Mar 16, 2023 |
| Pegatron      | 2AB5                        | [09fdb4daa2](https://linux-hardware.org/?probe=09fdb4daa2) | Mar 16, 2023 |
| Acer          | FX58M                       | [ffc55de046](https://linux-hardware.org/?probe=ffc55de046) | Mar 16, 2023 |
| Dell          | 0PGKWF A00                  | [d03e035ed6](https://linux-hardware.org/?probe=d03e035ed6) | Mar 16, 2023 |
| Dell          | 0PGKWF A00                  | [2b34503276](https://linux-hardware.org/?probe=2b34503276) | Mar 16, 2023 |
| ASRock        | B450M Pro4                  | [108d237ebe](https://linux-hardware.org/?probe=108d237ebe) | Mar 16, 2023 |
| Dell          | 0773VG A00                  | [53c02c1bb8](https://linux-hardware.org/?probe=53c02c1bb8) | Mar 16, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [5200e8032c](https://linux-hardware.org/?probe=5200e8032c) | Mar 15, 2023 |
| Fujitsu       | D3632-A1 S26361-D3632-A1    | [56662cb899](https://linux-hardware.org/?probe=56662cb899) | Mar 15, 2023 |
| ASRock        | N68C-S UCC                  | [9fcdcbd033](https://linux-hardware.org/?probe=9fcdcbd033) | Mar 15, 2023 |
| ASRock        | N68C-S UCC                  | [a2630bc693](https://linux-hardware.org/?probe=a2630bc693) | Mar 15, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b843a727ce](https://linux-hardware.org/?probe=b843a727ce) | Mar 15, 2023 |
| ASRock        | Z390M-ITX/ac                | [623a5ed92b](https://linux-hardware.org/?probe=623a5ed92b) | Mar 15, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [4d5bb23ec0](https://linux-hardware.org/?probe=4d5bb23ec0) | Mar 15, 2023 |
| Unknown       | Unknown                     | [b20f8089c3](https://linux-hardware.org/?probe=b20f8089c3) | Mar 15, 2023 |
| MSI           | B450M MORTAR                | [14a4314e39](https://linux-hardware.org/?probe=14a4314e39) | Mar 15, 2023 |
| Lenovo        | 36EB NOK                    | [b6d8243d49](https://linux-hardware.org/?probe=b6d8243d49) | Mar 15, 2023 |
| Unknown       | Unknown                     | [b0b8ac79d9](https://linux-hardware.org/?probe=b0b8ac79d9) | Mar 15, 2023 |
| Dell          | 0WMJ54 A01                  | [de299316cc](https://linux-hardware.org/?probe=de299316cc) | Mar 15, 2023 |
| MSI           | Z97 PC Mate                 | [5b00c07288](https://linux-hardware.org/?probe=5b00c07288) | Mar 15, 2023 |
| Acer          | TDPS05                      | [a2cdc5b3cd](https://linux-hardware.org/?probe=a2cdc5b3cd) | Mar 15, 2023 |
| Acer          | TDPS05                      | [8f528a91a5](https://linux-hardware.org/?probe=8f528a91a5) | Mar 15, 2023 |
| ASRock        | X470 Master SLI             | [06141a871e](https://linux-hardware.org/?probe=06141a871e) | Mar 15, 2023 |
| ASRock        | B365M Pro4                  | [e237668eb2](https://linux-hardware.org/?probe=e237668eb2) | Mar 15, 2023 |
| Gigabyte      | B75M-D3H                    | [d45d6dce3b](https://linux-hardware.org/?probe=d45d6dce3b) | Mar 15, 2023 |
| ASUSTek       | PRIME A320I-K               | [91695981f2](https://linux-hardware.org/?probe=91695981f2) | Mar 15, 2023 |
| MSI           | B550-A PRO                  | [117ca7e4ef](https://linux-hardware.org/?probe=117ca7e4ef) | Mar 15, 2023 |
| Gigabyte      | H97M-HD3                    | [6831505433](https://linux-hardware.org/?probe=6831505433) | Mar 14, 2023 |
| Dell          | 0W0CHX A00                  | [8086e2dcee](https://linux-hardware.org/?probe=8086e2dcee) | Mar 14, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [867aa61b78](https://linux-hardware.org/?probe=867aa61b78) | Mar 14, 2023 |
| ASRock        | B550 Extreme4               | [9a139b5bad](https://linux-hardware.org/?probe=9a139b5bad) | Mar 14, 2023 |
| MSI           | B450M PRO-VDH V2            | [342fc7ec97](https://linux-hardware.org/?probe=342fc7ec97) | Mar 14, 2023 |
| MSI           | B450M PRO-VDH V2            | [056353c290](https://linux-hardware.org/?probe=056353c290) | Mar 14, 2023 |
| ASRock        | H81M-HDS                    | [58f8534073](https://linux-hardware.org/?probe=58f8534073) | Mar 14, 2023 |
| Shenzhen M... | F6BFC                       | [46cb84be25](https://linux-hardware.org/?probe=46cb84be25) | Mar 14, 2023 |
| Gigabyte      | Z390 UD                     | [5f205e8b6f](https://linux-hardware.org/?probe=5f205e8b6f) | Mar 14, 2023 |
| Gigabyte      | Z390 UD                     | [916ea037f9](https://linux-hardware.org/?probe=916ea037f9) | Mar 14, 2023 |
| ASRock        | 970 Pro3 R2.0               | [137a000737](https://linux-hardware.org/?probe=137a000737) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [39ded01df5](https://linux-hardware.org/?probe=39ded01df5) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [529e83761c](https://linux-hardware.org/?probe=529e83761c) | Mar 14, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [52e2dade5d](https://linux-hardware.org/?probe=52e2dade5d) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [c215f0cf02](https://linux-hardware.org/?probe=c215f0cf02) | Mar 14, 2023 |
| ASRock        | Z270 Gaming K6              | [3afad06d79](https://linux-hardware.org/?probe=3afad06d79) | Mar 14, 2023 |
| ASUSTek       | P7P55D                      | [c685130644](https://linux-hardware.org/?probe=c685130644) | Mar 14, 2023 |
| Intel         | DX79TO AAG28805-402         | [9d21f71f9d](https://linux-hardware.org/?probe=9d21f71f9d) | Mar 14, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | [09dae67fd1](https://linux-hardware.org/?probe=09dae67fd1) | Mar 14, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | [942d1f4c2c](https://linux-hardware.org/?probe=942d1f4c2c) | Mar 14, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [e836500efa](https://linux-hardware.org/?probe=e836500efa) | Mar 14, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | [3222c6ea63](https://linux-hardware.org/?probe=3222c6ea63) | Mar 14, 2023 |
| Dell          | 0Y7WYT A00                  | [f8c17c2464](https://linux-hardware.org/?probe=f8c17c2464) | Mar 14, 2023 |
| Foxconn       | TPS01                       | [60ae6d3891](https://linux-hardware.org/?probe=60ae6d3891) | Mar 14, 2023 |
| Dell          | 0773VG A00                  | [42baaa40b9](https://linux-hardware.org/?probe=42baaa40b9) | Mar 14, 2023 |
| Fujitsu Si... | D1547 S26361-D1547          | [95a9c8655d](https://linux-hardware.org/?probe=95a9c8655d) | Mar 14, 2023 |
| HP            | ProLiant SL4540 Gen8        | [fb493ce600](https://linux-hardware.org/?probe=fb493ce600) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2662a08251](https://linux-hardware.org/?probe=2662a08251) | Mar 14, 2023 |
| MSI           | CSM-H87M-G43                | [9df13e200e](https://linux-hardware.org/?probe=9df13e200e) | Mar 14, 2023 |
| ASRock        | H170M Pro4                  | [c34ef2441a](https://linux-hardware.org/?probe=c34ef2441a) | Mar 14, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [eb761f4a30](https://linux-hardware.org/?probe=eb761f4a30) | Mar 14, 2023 |
| ASRock        | A320M-HDV R4.0              | [723cb09007](https://linux-hardware.org/?probe=723cb09007) | Mar 14, 2023 |
| Gigabyte      | A320M-S2H-CF                | [4b0af487e9](https://linux-hardware.org/?probe=4b0af487e9) | Mar 14, 2023 |
| Gigabyte      | A320M-S2H-CF                | [729bfdc60d](https://linux-hardware.org/?probe=729bfdc60d) | Mar 14, 2023 |
| Gigabyte      | X58A-UD7                    | [95248fc9a0](https://linux-hardware.org/?probe=95248fc9a0) | Mar 14, 2023 |
| Dell          | 0RK936                      | [59cbc1f071](https://linux-hardware.org/?probe=59cbc1f071) | Mar 14, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [631e225bab](https://linux-hardware.org/?probe=631e225bab) | Mar 14, 2023 |
| Gigabyte      | H110M-S2HP-CF               | [e59eca90ee](https://linux-hardware.org/?probe=e59eca90ee) | Mar 13, 2023 |
| Medion        | MS-7707                     | [14febb7194](https://linux-hardware.org/?probe=14febb7194) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [e1fc53bd25](https://linux-hardware.org/?probe=e1fc53bd25) | Mar 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [05da6b812c](https://linux-hardware.org/?probe=05da6b812c) | Mar 13, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [a22f7f4309](https://linux-hardware.org/?probe=a22f7f4309) | Mar 13, 2023 |
| Pegatron      | 2AB6                        | [8feb2e38c0](https://linux-hardware.org/?probe=8feb2e38c0) | Mar 13, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [d4f6b075c4](https://linux-hardware.org/?probe=d4f6b075c4) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [25c6ceb9e8](https://linux-hardware.org/?probe=25c6ceb9e8) | Mar 13, 2023 |
| Biostar       | A960D+V3                    | [e18f6a3a84](https://linux-hardware.org/?probe=e18f6a3a84) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [abb73d2e5f](https://linux-hardware.org/?probe=abb73d2e5f) | Mar 13, 2023 |
| ASUSTek       | PRIME B560M-A               | [a7e24ac4b6](https://linux-hardware.org/?probe=a7e24ac4b6) | Mar 13, 2023 |
| Wortmann      | Terra 3100                  | [126586f434](https://linux-hardware.org/?probe=126586f434) | Mar 12, 2023 |
| ASRockRack    | ROMED6U-2L2T                | [1af076312d](https://linux-hardware.org/?probe=1af076312d) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [1e0274aed9](https://linux-hardware.org/?probe=1e0274aed9) | Mar 12, 2023 |
| Apple         | Mac-F221BEC8                | [d57befe967](https://linux-hardware.org/?probe=d57befe967) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [8efb3d3950](https://linux-hardware.org/?probe=8efb3d3950) | Mar 12, 2023 |
| Medion        | MS-7707                     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Gigabyte      | MJPLNBB-00                  | [e8c31757e0](https://linux-hardware.org/?probe=e8c31757e0) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [36981b0d78](https://linux-hardware.org/?probe=36981b0d78) | Mar 12, 2023 |
| Medion        | TJ4125                      | [5b8893bf40](https://linux-hardware.org/?probe=5b8893bf40) | Mar 12, 2023 |
| Gigabyte      | Z87X-OC Force-CF            | [17deac9c67](https://linux-hardware.org/?probe=17deac9c67) | Mar 12, 2023 |
| Gigabyte      | B560M DS3H V2               | [77b7a9348b](https://linux-hardware.org/?probe=77b7a9348b) | Mar 12, 2023 |
| Medion        | MS-7707                     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Acer          | FX58M                       | [5974103b03](https://linux-hardware.org/?probe=5974103b03) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [35ad1f11db](https://linux-hardware.org/?probe=35ad1f11db) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H                    | [f9dfd84f86](https://linux-hardware.org/?probe=f9dfd84f86) | Mar 12, 2023 |
| Gigabyte      | Q87M-D2H                    | [0c699c2214](https://linux-hardware.org/?probe=0c699c2214) | Mar 12, 2023 |
| Acer          | E946GZ                      | [9b79cd2b84](https://linux-hardware.org/?probe=9b79cd2b84) | Mar 12, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 1217     | 14.67%  |
| Ubuntu 18.04                 | 546      | 6.58%   |
| Ubuntu 22.04                 | 385      | 4.64%   |
| OpenMandriva 4.3             | 261      | 3.15%   |
| OpenMandriva 4.2             | 261      | 3.15%   |
| Linux Mint 20.3              | 238      | 2.87%   |
| Linux Mint 20.2              | 224      | 2.7%    |
| Debian 11                    | 220      | 2.65%   |
| Manjaro                      | 163      | 1.96%   |
| Arch Rolling                 | 154      | 1.86%   |
| Linux Mint 20.1              | 145      | 1.75%   |
| Ubuntu 21.10                 | 142      | 1.71%   |
| Linux Mint 21.1              | 141      | 1.7%    |
| Zorin 16                     | 119      | 1.43%   |
| KDE neon 20.04               | 118      | 1.42%   |
| Linux Mint 19.3              | 116      | 1.4%    |
| Arch                         | 116      | 1.4%    |
| Ubuntu 20.10                 | 112      | 1.35%   |
| Linux Mint 20                | 109      | 1.31%   |
| Xubuntu 20.04                | 108      | 1.3%    |
| Ubuntu 21.04                 | 102      | 1.23%   |
| Ubuntu 19.10                 | 93       | 1.12%   |
| openSUSE Tumbleweed-XXXXXXXX | 88       | 1.06%   |
| OpenMandriva 23.01           | 85       | 1.02%   |
| Ubuntu 19.04                 | 83       | 1%      |
| Ubuntu 22.10                 | 76       | 0.92%   |
| Pop!_OS 22.04                | 75       | 0.9%    |
| Debian 10                    | 74       | 0.89%   |
| OpenMandriva 23.03           | 72       | 0.87%   |
| Linux Mint 21                | 69       | 0.83%   |
| Kubuntu 20.04                | 65       | 0.78%   |
| Pop!_OS 20.10                | 57       | 0.69%   |
| BlackPanther 18.1            | 55       | 0.66%   |
| Linux Mint 19.2              | 51       | 0.61%   |
| Pop!_OS 20.04                | 48       | 0.58%   |
| Fedora 36                    | 48       | 0.58%   |
| Fedora 33                    | 48       | 0.58%   |
| ArcoLinux Rolling            | 47       | 0.57%   |
| Pop!_OS 21.04                | 46       | 0.55%   |
| Fedora 32                    | 44       | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 2666     | 34.4%   |
| Linux Mint    | 1046     | 13.5%   |
| OpenMandriva  | 710      | 9.16%   |
| Debian        | 374      | 4.83%   |
| Manjaro       | 310      | 4%      |
| Fedora        | 280      | 3.61%   |
| Arch          | 256      | 3.3%    |
| Pop!_OS       | 251      | 3.24%   |
| Xubuntu       | 193      | 2.49%   |
| Kubuntu       | 168      | 2.17%   |
| Zorin         | 166      | 2.14%   |
| ROSA          | 165      | 2.13%   |
| openSUSE      | 162      | 2.09%   |
| KDE neon      | 140      | 1.81%   |
| Gentoo        | 104      | 1.34%   |
| BlackPanther  | 57       | 0.74%   |
| Ubuntu Unity  | 55       | 0.71%   |
| ArcoLinux     | 54       | 0.7%    |
| Ubuntu MATE   | 51       | 0.66%   |
| Elementary    | 42       | 0.54%   |
| LMDE          | 39       | 0.5%    |
| Lubuntu       | 37       | 0.48%   |
| EndeavourOS   | 36       | 0.46%   |
| Endless       | 30       | 0.39%   |
| CentOS        | 26       | 0.34%   |
| Ubuntu Budgie | 25       | 0.32%   |
| Kali          | 25       | 0.32%   |
| Garuda Linux  | 23       | 0.3%    |
| Nobara        | 19       | 0.25%   |
| Clear Linux   | 19       | 0.25%   |
| MX            | 18       | 0.23%   |
| QTS           | 15       | 0.19%   |
| Ubuntu Studio | 12       | 0.15%   |
| LinuxFX       | 11       | 0.14%   |
| RHEL          | 10       | 0.13%   |
| NixOS         | 9        | 0.12%   |
| Artix         | 9        | 0.12%   |
| Solus         | 8        | 0.1%    |
| Reborn OS     | 8        | 0.1%    |
| Peppermint    | 8        | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 260      | 2.76%   |
| 5.16.7-desktop-1omv4003  | 252      | 2.68%   |
| 5.4.0-42-generic         | 120      | 1.27%   |
| 5.4.0-58-generic         | 100      | 1.06%   |
| 5.15.0-56-generic        | 91       | 0.97%   |
| 6.1.1-desktop-1omv2290   | 80       | 0.85%   |
| 5.4.0-52-generic         | 77       | 0.82%   |
| 6.2.6-desktop-1omv2390   | 70       | 0.74%   |
| 5.4.0-48-generic         | 70       | 0.74%   |
| 5.15.0-48-generic        | 70       | 0.74%   |
| 5.15.0-58-generic        | 69       | 0.73%   |
| 5.19.0-35-generic        | 67       | 0.71%   |
| 5.4.0-91-generic         | 64       | 0.68%   |
| 5.4.0-26-generic         | 64       | 0.68%   |
| 5.15.0-60-generic        | 59       | 0.63%   |
| 5.4.0-40-generic         | 58       | 0.62%   |
| 5.15.0-52-generic        | 58       | 0.62%   |
| 5.11.0-27-generic        | 54       | 0.57%   |
| 5.4.0-65-generic         | 53       | 0.56%   |
| 5.4.0-54-generic         | 51       | 0.54%   |
| 5.15.0-67-generic        | 51       | 0.54%   |
| 5.15.0-46-generic        | 47       | 0.5%    |
| 5.13.0-28-generic        | 47       | 0.5%    |
| 5.4.0-37-generic         | 46       | 0.49%   |
| 5.4.0-29-generic         | 46       | 0.49%   |
| 5.3.0-40-generic         | 46       | 0.49%   |
| 5.11.0-37-generic        | 46       | 0.49%   |
| 5.11.0-38-generic        | 45       | 0.48%   |
| 5.13.0-30-generic        | 44       | 0.47%   |
| 5.11.0-40-generic        | 44       | 0.47%   |
| 5.13.0-39-generic        | 43       | 0.46%   |
| 4.18.16-desktop-1bP      | 42       | 0.45%   |
| 5.15.0-47-generic        | 41       | 0.44%   |
| 5.4.0-88-generic         | 40       | 0.42%   |
| 5.4.0-81-generic         | 40       | 0.42%   |
| 5.15.0-53-generic        | 40       | 0.42%   |
| 5.8.0-43-generic         | 38       | 0.4%    |
| 5.4.0-72-generic         | 38       | 0.4%    |
| 5.15.0-43-generic        | 38       | 0.4%    |
| 5.8.0-53-generic         | 37       | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 1692     | 19.66%  |
| 5.15.0  | 715      | 8.31%   |
| 4.15.0  | 541      | 6.28%   |
| 5.8.0   | 467      | 5.43%   |
| 5.11.0  | 444      | 5.16%   |
| 5.13.0  | 422      | 4.9%    |
| 5.3.0   | 275      | 3.19%   |
| 5.10.14 | 262      | 3.04%   |
| 5.19.0  | 260      | 3.02%   |
| 5.16.7  | 256      | 2.97%   |
| 5.10.0  | 207      | 2.4%    |
| 5.0.0   | 203      | 2.36%   |
| 4.18.0  | 145      | 1.68%   |
| 6.2.6   | 95       | 1.1%    |
| 6.1.1   | 89       | 1.03%   |
| 4.19.0  | 70       | 0.81%   |
| 4.18.16 | 46       | 0.53%   |
| 5.3.18  | 39       | 0.45%   |
| 6.1.0   | 37       | 0.43%   |
| 4.4.0   | 34       | 0.39%   |
| 6.2.0   | 32       | 0.37%   |
| 4.9.20  | 27       | 0.31%   |
| 5.18.12 | 25       | 0.29%   |
| 5.17.1  | 25       | 0.29%   |
| 4.9.60  | 25       | 0.29%   |
| 5.14.0  | 24       | 0.28%   |
| 5.12.4  | 24       | 0.28%   |
| 6.0.12  | 23       | 0.27%   |
| 6.1.12  | 21       | 0.24%   |
| 5.18.0  | 21       | 0.24%   |
| 5.14.21 | 21       | 0.24%   |
| 5.9.11  | 19       | 0.22%   |
| 5.9.0   | 19       | 0.22%   |
| 5.9.16  | 18       | 0.21%   |
| 5.17.5  | 18       | 0.21%   |
| 6.0.10  | 17       | 0.2%    |
| 5.6.14  | 17       | 0.2%    |
| 4.12.14 | 17       | 0.2%    |
| 3.10.0  | 17       | 0.2%    |
| 6.0.0   | 16       | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 1802     | 21.21%  |
| 5.15    | 890      | 10.48%  |
| 5.10    | 600      | 7.06%   |
| 5.8     | 568      | 6.69%   |
| 4.15    | 544      | 6.4%    |
| 5.11    | 542      | 6.38%   |
| 5.13    | 489      | 5.76%   |
| 5.16    | 354      | 4.17%   |
| 5.19    | 337      | 3.97%   |
| 5.3     | 335      | 3.94%   |
| 6.1     | 245      | 2.88%   |
| 5.0     | 213      | 2.51%   |
| 4.18    | 196      | 2.31%   |
| 6.2     | 193      | 2.27%   |
| 6.0     | 115      | 1.35%   |
| 5.9     | 114      | 1.34%   |
| 5.18    | 109      | 1.28%   |
| 5.14    | 99       | 1.17%   |
| 4.9     | 99       | 1.17%   |
| 5.6     | 93       | 1.09%   |
| 4.19    | 87       | 1.02%   |
| 5.17    | 85       | 1%      |
| 5.12    | 72       | 0.85%   |
| 5.7     | 67       | 0.79%   |
| 5.5     | 48       | 0.56%   |
| 4.4     | 38       | 0.45%   |
| 6.3     | 22       | 0.26%   |
| 5.2     | 22       | 0.26%   |
| 4.14    | 17       | 0.2%    |
| 4.12    | 17       | 0.2%    |
| 4.1     | 17       | 0.2%    |
| 3.10    | 17       | 0.2%    |
| 5.1     | 14       | 0.16%   |
| 4.13    | 8        | 0.09%   |
| 4.17    | 7        | 0.08%   |
| 4.20    | 6        | 0.07%   |
| 4.10    | 3        | 0.04%   |
| 4.8     | 2        | 0.02%   |
| 4.2     | 2        | 0.02%   |
| 4.16    | 2        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| x86_64   | 7290     | 97.81%  |
| i686     | 155      | 2.08%   |
| armv7l   | 3        | 0.04%   |
| ppc      | 2        | 0.03%   |
| armv5tel | 2        | 0.03%   |
| aarch64  | 1        | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GNOME             | 2950     | 37.56%  |
| KDE5              | 1460     | 18.59%  |
| Unknown           | 1043     | 13.28%  |
| X-Cinnamon        | 852      | 10.85%  |
| XFCE              | 533      | 6.79%   |
| KDE               | 234      | 2.98%   |
| MATE              | 224      | 2.85%   |
| KDE4              | 95       | 1.21%   |
| Cinnamon          | 87       | 1.11%   |
| Unity             | 54       | 0.69%   |
| LXQt              | 48       | 0.61%   |
| i3                | 45       | 0.57%   |
| Pantheon          | 43       | 0.55%   |
| Budgie            | 41       | 0.52%   |
| LXDE              | 34       | 0.43%   |
| GNOME Classic     | 16       | 0.2%    |
| Deepin            | 15       | 0.19%   |
| GNOME Flashback   | 14       | 0.18%   |
| awesome           | 9        | 0.11%   |
| sway              | 8        | 0.1%    |
| bspwm             | 6        | 0.08%   |
| qtile             | 5        | 0.06%   |
| Openbox           | 5        | 0.06%   |
| hyprland          | 5        | 0.06%   |
| lightdm-xsession  | 4        | 0.05%   |
| Yaru:ubuntu:GNOME | 3        | 0.04%   |
| xmonad            | 3        | 0.04%   |
| trinity           | 3        | 0.04%   |
| herbstluftwm      | 3        | 0.04%   |
| DWM               | 3        | 0.04%   |
| chadwm            | 3        | 0.04%   |
| ubuntustudio      | 1        | 0.01%   |
| pearl:GNOME       | 1        | 0.01%   |
| none+awesome      | 1        | 0.01%   |
| LeftWM            | 1        | 0.01%   |
| ICEWM             | 1        | 0.01%   |
| i3-with-shmlog    | 1        | 0.01%   |
| enlightenment     | 1        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 6091     | 79.19%  |
| Wayland     | 876      | 11.39%  |
| Unknown     | 491      | 6.38%   |
| Tty         | 231      | 3%      |
| Web         | 2        | 0.03%   |
| Unspecified | 1        | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 4041     | 51.79%  |
| SDDM    | 1274     | 16.33%  |
| GDM3    | 890      | 11.41%  |
| LightDM | 755      | 9.68%   |
| GDM     | 476      | 6.1%    |
| TDM     | 234      | 3%      |
| KDM     | 95       | 1.22%   |
| XDM     | 14       | 0.18%   |
| SLiM    | 11       | 0.14%   |
| MDM     | 4        | 0.05%   |
| NODM    | 3        | 0.04%   |
| LXDM    | 3        | 0.04%   |
| Ly      | 2        | 0.03%   |
| GREETD  | 1        | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| de_DE       | 5100     | 66.63%  |
| en_US       | 1211     | 15.82%  |
| Unknown     | 892      | 11.65%  |
| en_GB       | 122      | 1.59%   |
| C           | 122      | 1.59%   |
| en_DE       | 24       | 0.31%   |
| POSIX       | 23       | 0.3%    |
| ru_RU       | 18       | 0.24%   |
| fr_FR       | 14       | 0.18%   |
| de_AT       | 14       | 0.18%   |
| pl_PL       | 12       | 0.16%   |
| it_IT       | 10       | 0.13%   |
| es_ES       | 9        | 0.12%   |
| en_IE       | 8        | 0.1%    |
| C.UTF8      | 8        | 0.1%    |
| de_CH       | 7        | 0.09%   |
| nl_NL       | 6        | 0.08%   |
| hu_HU       | 6        | 0.08%   |
| en_CA       | 5        | 0.07%   |
| en_DK       | 4        | 0.05%   |
| ro_RO       | 3        | 0.04%   |
| el_GR       | 3        | 0.04%   |
| de_BE       | 3        | 0.04%   |
| tr_TR       | 2        | 0.03%   |
| ru_UA       | 2        | 0.03%   |
| pt_PT       | 2        | 0.03%   |
| hr_HR       | 2        | 0.03%   |
| de_IT       | 2        | 0.03%   |
| cs_CZ       | 2        | 0.03%   |
| bs_BA       | 2        | 0.03%   |
| zh_CN       | 1        | 0.01%   |
| uk_UA       | 1        | 0.01%   |
| fi_FI       | 1        | 0.01%   |
| en_US.UFS-8 | 1        | 0.01%   |
| en_US-UTF-8 | 1        | 0.01%   |
| en_NZ       | 1        | 0.01%   |
| en_IL       | 1        | 0.01%   |
| en_AU       | 1        | 0.01%   |
| en_AT       | 1        | 0.01%   |
| de_LI       | 1        | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 4648     | 60.87%  |
| EFI  | 2988     | 39.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Ext4          | 5737     | 74.79%  |
| Overlay       | 788      | 10.27%  |
| Btrfs         | 556      | 7.25%   |
| Unknown       | 255      | 3.32%   |
| Xfs           | 108      | 1.41%   |
| Tmpfs         | 70       | 0.91%   |
| Zfs           | 60       | 0.78%   |
| Ext2          | 37       | 0.48%   |
| Ext3          | 36       | 0.47%   |
| F2fs          | 10       | 0.13%   |
| Reiserfs      | 5        | 0.07%   |
| Rootfs        | 2        | 0.03%   |
| XXXXXXX       | 1        | 0.01%   |
| XXXXX         | 1        | 0.01%   |
| XXXX          | 1        | 0.01%   |
| XXX4          | 1        | 0.01%   |
| Jfs           | 1        | 0.01%   |
| Fuse.snapfuse | 1        | 0.01%   |
| Aufs          | 1        | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 4298     | 55.7%   |
| GPT     | 2429     | 31.48%  |
| MBR     | 990      | 12.83%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 5905     | 76.74%  |
| Yes       | 1790     | 23.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4944     | 64.6%   |
| Yes       | 2709     | 35.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1817     | 24.38%  |
| Gigabyte Technology                  | 1217     | 16.33%  |
| MSI                                  | 1086     | 14.57%  |
| ASRock                               | 915      | 12.28%  |
| Hewlett-Packard                      | 437      | 5.86%   |
| Dell                                 | 369      | 4.95%   |
| Fujitsu                              | 323      | 4.33%   |
| Lenovo                               | 213      | 2.86%   |
| Acer                                 | 178      | 2.39%   |
| Medion                               | 159      | 2.13%   |
| Intel                                | 81       | 1.09%   |
| Fujitsu Siemens                      | 75       | 1.01%   |
| Biostar                              | 75       | 1.01%   |
| Unknown                              | 74       | 0.99%   |
| Foxconn                              | 57       | 0.76%   |
| Shuttle                              | 37       | 0.5%    |
| Pegatron                             | 36       | 0.48%   |
| Packard Bell                         | 32       | 0.43%   |
| BESSTAR Tech                         | 28       | 0.38%   |
| ASRockRack                           | 21       | 0.28%   |
| Supermicro                           | 17       | 0.23%   |
| Apple                                | 17       | 0.23%   |
| ECS                                  | 16       | 0.21%   |
| Inventec                             | 15       | 0.2%    |
| AMI                                  | 12       | 0.16%   |
| ZOTAC                                | 10       | 0.13%   |
| Hardkernel                           | 7        | 0.09%   |
| eMachines                            | 7        | 0.09%   |
| AOpen                                | 7        | 0.09%   |
| ABIT                                 | 7        | 0.09%   |
| Wortmann AG                          | 6        | 0.08%   |
| EVGA                                 | 6        | 0.08%   |
| AZW                                  | 6        | 0.08%   |
| IBM                                  | 5        | 0.07%   |
| Alienware                            | 5        | 0.07%   |
| Shenzhen Meigao Electronic Equipment | 4        | 0.05%   |
| Seco                                 | 4        | 0.05%   |
| PC Engines                           | 4        | 0.05%   |
| Tekram Technology                    | 3        | 0.04%   |
| AWOW                                 | 3        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 131      | 1.76%   |
| Unknown                      | 82       | 1.1%    |
| MSI MS-7C37                  | 69       | 0.93%   |
| MSI MS-7B86                  | 60       | 0.81%   |
| MSI MS-7A38                  | 47       | 0.63%   |
| ASUS PRIME A320M-K           | 45       | 0.6%    |
| ASUS PRIME B350-PLUS         | 37       | 0.5%    |
| ASRock B450M Pro4            | 34       | 0.46%   |
| ASUS M5A78L-M/USB3           | 33       | 0.44%   |
| MSI MS-7C02                  | 32       | 0.43%   |
| MSI MS-7B89                  | 32       | 0.43%   |
| Gigabyte X570 AORUS ELITE    | 31       | 0.42%   |
| Dell OptiPlex 7010           | 31       | 0.42%   |
| MSI MS-7B79                  | 29       | 0.39%   |
| ASUS PRIME X370-PRO          | 29       | 0.39%   |
| MSI MS-7C56                  | 28       | 0.38%   |
| Gigabyte 970A-DS3P           | 27       | 0.36%   |
| Dell OptiPlex 790            | 26       | 0.35%   |
| MSI MS-7693                  | 25       | 0.34%   |
| ASUS TUF Gaming X570-PLUS    | 24       | 0.32%   |
| ASUS A68HM-PLUS              | 24       | 0.32%   |
| ASUS A0000001                | 24       | 0.32%   |
| MSI MS-7C91                  | 22       | 0.3%    |
| MSI MS-7C52                  | 22       | 0.3%    |
| Gigabyte GA-78LMT-USB3 6.0   | 22       | 0.3%    |
| Dell OptiPlex 780            | 22       | 0.3%    |
| ASUS PRIME B450M-A           | 22       | 0.3%    |
| ASRock B450 Pro4             | 22       | 0.3%    |
| ASRock 970 Pro3 R2.0         | 22       | 0.3%    |
| Medion MS-7728               | 21       | 0.28%   |
| Gigabyte GA-78LMT-S2P        | 21       | 0.28%   |
| ASUS TUF Gaming B550-PLUS    | 21       | 0.28%   |
| ASUS PRIME X470-PRO          | 21       | 0.28%   |
| ASUS M5A97 R2.0              | 21       | 0.28%   |
| MSI MS-7A32                  | 20       | 0.27%   |
| Gigabyte B450M DS3H          | 19       | 0.25%   |
| ASUS ROG STRIX B550-F GAMING | 19       | 0.25%   |
| MSI MS-7A34                  | 18       | 0.24%   |
| ASUS Z170 PRO GAMING         | 18       | 0.24%   |
| ASRock N68C-S UCC            | 18       | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 342      | 4.59%   |
| Dell OptiPlex           | 234      | 3.14%   |
| Fujitsu ESPRIMO         | 226      | 3.03%   |
| ASUS ROG                | 201      | 2.7%    |
| HP Compaq               | 139      | 1.87%   |
| ASUS All                | 131      | 1.76%   |
| Lenovo ThinkCentre      | 121      | 1.62%   |
| Acer Aspire             | 113      | 1.52%   |
| ASUS TUF                | 104      | 1.4%    |
| Unknown                 | 82       | 1.1%    |
| ASUS M5A78L-M           | 81       | 1.09%   |
| Gigabyte X570           | 70       | 0.94%   |
| MSI MS-7C37             | 69       | 0.93%   |
| MSI MS-7B86             | 60       | 0.81%   |
| Dell Precision          | 60       | 0.81%   |
| HP EliteDesk            | 53       | 0.71%   |
| Gigabyte B450           | 53       | 0.71%   |
| ASRock 970              | 49       | 0.66%   |
| Gigabyte GA-78LMT-USB3  | 48       | 0.64%   |
| MSI MS-7A38             | 47       | 0.63%   |
| ASUS M5A97              | 47       | 0.63%   |
| Gigabyte B550           | 45       | 0.6%    |
| ASRock B450             | 42       | 0.56%   |
| Gigabyte B450M          | 41       | 0.55%   |
| Fujitsu Siemens ESPRIMO | 38       | 0.51%   |
| Fujitsu CELSIUS         | 37       | 0.5%    |
| ASRock B450M            | 36       | 0.48%   |
| Lenovo IdeaCentre       | 35       | 0.47%   |
| MSI MS-7C02             | 32       | 0.43%   |
| MSI MS-7B89             | 32       | 0.43%   |
| HP ProDesk              | 32       | 0.43%   |
| Acer Veriton            | 31       | 0.42%   |
| HP Pavilion             | 30       | 0.4%    |
| Gigabyte 970A-DS3P      | 30       | 0.4%    |
| MSI MS-7B79             | 29       | 0.39%   |
| MSI MS-7C56             | 28       | 0.38%   |
| Lenovo ThinkStation     | 28       | 0.38%   |
| ASRock X570             | 28       | 0.38%   |
| Dell Inspiron           | 26       | 0.35%   |
| MSI MS-7693             | 25       | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 774      | 10.39%  |
| 2012    | 755      | 10.13%  |
| 2019    | 638      | 8.56%   |
| 2013    | 607      | 8.15%   |
| 2011    | 575      | 7.72%   |
| 2020    | 534      | 7.17%   |
| 2017    | 530      | 7.11%   |
| 2014    | 464      | 6.23%   |
| 2010    | 452      | 6.07%   |
| 2009    | 402      | 5.39%   |
| 2015    | 356      | 4.78%   |
| 2016    | 298      | 4%      |
| 2008    | 282      | 3.78%   |
| 2021    | 260      | 3.49%   |
| 2007    | 196      | 2.63%   |
| 2022    | 125      | 1.68%   |
| 2006    | 100      | 1.34%   |
| 2005    | 41       | 0.55%   |
| 2023    | 16       | 0.21%   |
| 2004    | 16       | 0.21%   |
| Unknown | 13       | 0.17%   |
| 2003    | 10       | 0.13%   |
| 2000    | 4        | 0.05%   |
| 2002    | 3        | 0.04%   |
| 2001    | 1        | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 7452     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 7269     | 97.11%  |
| Enabled  | 216      | 2.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 7444     | 99.89%  |
| Yes  | 8        | 0.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1972     | 25.88%  |
| 8.01-16.0       | 1511     | 19.83%  |
| 32.01-64.0      | 1166     | 15.3%   |
| 3.01-4.0        | 1065     | 13.97%  |
| 4.01-8.0        | 1035     | 13.58%  |
| 64.01-256.0     | 385      | 5.05%   |
| 24.01-32.0      | 208      | 2.73%   |
| 1.01-2.0        | 162      | 2.13%   |
| 2.01-3.0        | 73       | 0.96%   |
| 0.51-1.0        | 27       | 0.35%   |
| More than 256.0 | 10       | 0.13%   |
| 0.01-0.5        | 5        | 0.07%   |
| Unknown         | 2        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 3368     | 39.88%  |
| 2.01-3.0    | 1890     | 22.38%  |
| 4.01-8.0    | 1126     | 13.33%  |
| 3.01-4.0    | 880      | 10.42%  |
| 0.51-1.0    | 610      | 7.22%   |
| 8.01-16.0   | 321      | 3.8%    |
| 0.01-0.5    | 109      | 1.29%   |
| 16.01-24.0  | 71       | 0.84%   |
| 32.01-64.0  | 31       | 0.37%   |
| 24.01-32.0  | 29       | 0.34%   |
| 64.01-256.0 | 6        | 0.07%   |
| 0           | 2        | 0.02%   |
| Unknown     | 2        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2696     | 34.32%  |
| 2       | 2255     | 28.71%  |
| 3       | 1317     | 16.77%  |
| 4       | 780      | 9.93%   |
| 5       | 383      | 4.88%   |
| 6       | 171      | 2.18%   |
| 7       | 87       | 1.11%   |
| 0       | 82       | 1.04%   |
| 8       | 36       | 0.46%   |
| 9       | 14       | 0.18%   |
| 10      | 11       | 0.14%   |
| 13      | 5        | 0.06%   |
| 12      | 4        | 0.05%   |
| 17      | 3        | 0.04%   |
| 11      | 3        | 0.04%   |
| Unknown | 3        | 0.04%   |
| 29      | 1        | 0.01%   |
| 23      | 1        | 0.01%   |
| 22      | 1        | 0.01%   |
| 20      | 1        | 0.01%   |
| 16      | 1        | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4528     | 59.9%   |
| No        | 3031     | 40.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 7399     | 99.28%  |
| No        | 54       | 0.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4940     | 65.19%  |
| Yes       | 2638     | 34.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 5538     | 73.1%   |
| Yes       | 2038     | 26.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Germany | 7452     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Berlin                | 605      | 7.45%   |
| Hamburg               | 327      | 4.03%   |
| Munich                | 294      | 3.62%   |
| Frankfurt am Main     | 252      | 3.1%    |
| Cologne               | 158      | 1.95%   |
| Stuttgart             | 141      | 1.74%   |
| Leipzig               | 121      | 1.49%   |
| Essen                 | 90       | 1.11%   |
| Düsseldorf           | 84       | 1.03%   |
| Nuremberg             | 83       | 1.02%   |
| Dresden               | 80       | 0.98%   |
| Mannheim              | 75       | 0.92%   |
| Karlsruhe             | 75       | 0.92%   |
| Dortmund              | 61       | 0.75%   |
| Falkenstein           | 60       | 0.74%   |
| Hanover               | 57       | 0.7%    |
| Duisburg              | 55       | 0.68%   |
| Bremen                | 48       | 0.59%   |
| Bonn                  | 48       | 0.59%   |
| Chemnitz              | 42       | 0.52%   |
| Bochum                | 42       | 0.52%   |
| Wuppertal             | 40       | 0.49%   |
| Augsburg              | 40       | 0.49%   |
| Münster              | 39       | 0.48%   |
| Mainz                 | 37       | 0.46%   |
| Kiel                  | 36       | 0.44%   |
| Darmstadt             | 36       | 0.44%   |
| Wiesbaden             | 34       | 0.42%   |
| Krefeld               | 32       | 0.39%   |
| Braunschweig          | 32       | 0.39%   |
| Bielefeld             | 32       | 0.39%   |
| Reutlingen            | 31       | 0.38%   |
| Regensburg            | 30       | 0.37%   |
| Ludwigshafen am Rhein | 29       | 0.36%   |
| Gelsenkirchen         | 29       | 0.36%   |
| Aachen                | 29       | 0.36%   |
| Halle                 | 28       | 0.34%   |
| Hamm                  | 27       | 0.33%   |
| Bamberg               | 27       | 0.33%   |
| Giessen               | 26       | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 2939     | 5432   | 20.94%  |
| WDC                         | 2442     | 4336   | 17.4%   |
| Seagate                     | 2210     | 3725   | 15.75%  |
| SanDisk                     | 1018     | 1558   | 7.25%   |
| Crucial                     | 847      | 1277   | 6.03%   |
| Toshiba                     | 773      | 1175   | 5.51%   |
| Kingston                    | 510      | 699    | 3.63%   |
| Intenso                     | 448      | 652    | 3.19%   |
| Hitachi                     | 439      | 619    | 3.13%   |
| Unknown                     | 191      | 337    | 1.36%   |
| Intel                       | 184      | 252    | 1.31%   |
| A-DATA Technology           | 135      | 186    | 0.96%   |
| Phison                      | 134      | 189    | 0.95%   |
| HGST                        | 120      | 182    | 0.86%   |
| OCZ                         | 114      | 148    | 0.81%   |
| Micron Technology           | 78       | 109    | 0.56%   |
| Maxtor                      | 74       | 112    | 0.53%   |
| Micron/Crucial Technology   | 72       | 115    | 0.51%   |
| Transcend                   | 67       | 83     | 0.48%   |
| Patriot                     | 66       | 101    | 0.47%   |
| Corsair                     | 64       | 82     | 0.46%   |
| China                       | 60       | 74     | 0.43%   |
| SPCC                        | 51       | 73     | 0.36%   |
| Silicon Motion              | 45       | 65     | 0.32%   |
| SK hynix                    | 43       | 52     | 0.31%   |
| Phison Electronics          | 43       | 53     | 0.31%   |
| JMicron Technology          | 40       | 47     | 0.29%   |
| PNY                         | 37       | 54     | 0.26%   |
| Leven                       | 36       | 46     | 0.26%   |
| ASMT                        | 36       | 47     | 0.26%   |
| Apacer                      | 28       | 31     | 0.2%    |
| XPG                         | 22       | 25     | 0.16%   |
| WD MediaMax                 | 22       | 27     | 0.16%   |
| SABRENT                     | 22       | 28     | 0.16%   |
| Hewlett-Packard             | 22       | 30     | 0.16%   |
| Unknown                     | 22       | 30     | 0.16%   |
| Verbatim                    | 19       | 29     | 0.14%   |
| LITEON                      | 18       | 22     | 0.13%   |
| INNOVATION IT               | 18       | 22     | 0.13%   |
| Kingston Technology Company | 17       | 26     | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                           | 259      | 1.55%   |
| Samsung SSD 860 EVO 500GB                           | 205      | 1.23%   |
| Samsung SSD 850 EVO 500GB                           | 176      | 1.05%   |
| Crucial CT1000MX500SSD1 1TB                         | 148      | 0.88%   |
| Seagate ST500DM002-1BD142 500GB                     | 145      | 0.87%   |
| Toshiba DT01ACA100 1TB                              | 144      | 0.86%   |
| Samsung SSD 860 EVO 1TB                             | 131      | 0.78%   |
| Crucial CT500MX500SSD1 500GB                        | 127      | 0.76%   |
| Samsung NVMe SSD Drive 500GB                        | 126      | 0.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 109      | 0.65%   |
| Samsung NVMe SSD Drive 1TB                          | 105      | 0.63%   |
| Toshiba HDWD110 1TB                                 | 103      | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB                      | 99       | 0.59%   |
| Samsung SSD 840 EVO 250GB                           | 97       | 0.58%   |
| Seagate ST2000DM008-2FR102 2TB                      | 96       | 0.57%   |
| Samsung SSD 860 EVO 250GB                           | 86       | 0.51%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 85       | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 85       | 0.51%   |
| SanDisk SSD PLUS 1000GB                             | 85       | 0.51%   |
| Toshiba DT01ACA200 2TB                              | 83       | 0.5%    |
| Crucial CT240BX500SSD1 240GB                        | 83       | 0.5%    |
| Samsung SSD 840 EVO 120GB                           | 82       | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB                        | 80       | 0.48%   |
| Seagate ST1000DM003-1CH162 1TB                      | 79       | 0.47%   |
| SanDisk SSD PLUS 480GB                              | 77       | 0.46%   |
| SanDisk SSD PLUS 240GB                              | 73       | 0.44%   |
| Unknown SD/MMC/MS PRO 64GB                          | 72       | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB                      | 71       | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB                      | 71       | 0.42%   |
| Samsung HD103SJ 1TB                                 | 66       | 0.39%   |
| Seagate ST4000DM004-2CV104 4TB                      | 65       | 0.39%   |
| Samsung SSD 860 QVO 1TB                             | 65       | 0.39%   |
| Kingston SA400S37240G 240GB SSD                     | 65       | 0.39%   |
| Seagate ST1000DM003-1ER162 1TB                      | 59       | 0.35%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 58       | 0.35%   |
| Samsung HD103UJ 1TB                                 | 58       | 0.35%   |
| WDC WD20EARX-00PASB0 2TB                            | 57       | 0.34%   |
| Kingston SV300S37A120G 120GB SSD                    | 57       | 0.34%   |
| Samsung HD501LJ 500GB                               | 56       | 0.33%   |
| Seagate ST3500418AS 500GB                           | 55       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2221     | 3925   | 33.53%  |
| Seagate             | 2175     | 3663   | 32.84%  |
| Toshiba             | 683      | 1036   | 10.31%  |
| Samsung Electronics | 657      | 1026   | 9.92%   |
| Hitachi             | 439      | 619    | 6.63%   |
| HGST                | 120      | 182    | 1.81%   |
| Unknown             | 75       | 97     | 1.13%   |
| Maxtor              | 72       | 107    | 1.09%   |
| Intenso             | 52       | 84     | 0.79%   |
| Fujitsu             | 17       | 20     | 0.26%   |
| WD MediaMax         | 12       | 17     | 0.18%   |
| ASMT                | 12       | 14     | 0.18%   |
| ExcelStor           | 9        | 10     | 0.14%   |
| ASMedia             | 7        | 7      | 0.11%   |
| USB3.0              | 6        | 6      | 0.09%   |
| Inateck             | 5        | 5      | 0.08%   |
| Apple               | 5        | 5      | 0.08%   |
| Hewlett-Packard     | 4        | 4      | 0.06%   |
| Dell                | 4        | 8      | 0.06%   |
| USB                 | 3        | 3      | 0.05%   |
| SSK                 | 3        | 3      | 0.05%   |
| IBM/Hitachi         | 3        | 3      | 0.05%   |
| IBM                 | 3        | 4      | 0.05%   |
| HPE                 | 3        | 7      | 0.05%   |
| HGST HTS            | 3        | 3      | 0.05%   |
| MDT                 | 2        | 2      | 0.03%   |
| Maxone              | 2        | 2      | 0.03%   |
| MARVELL             | 2        | 2      | 0.03%   |
| Magnetic Data       | 2        | 3      | 0.03%   |
| KESU                | 2        | 2      | 0.03%   |
| External            | 2        | 2      | 0.03%   |
| China               | 2        | 3      | 0.03%   |
| TPH00800640GB       | 1        | 1      | 0.02%   |
| TANDBERG            | 1        | 1      | 0.02%   |
| Synology            | 1        | 1      | 0.02%   |
| SABRENT             | 1        | 2      | 0.02%   |
| Quantum             | 1        | 1      | 0.02%   |
| PHD 3.0             | 1        | 2      | 0.02%   |
| LIO-ORG             | 1        | 2      | 0.02%   |
| LaCie               | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1750     | 2814   | 31.47%  |
| SanDisk             | 870      | 1328   | 15.64%  |
| Crucial             | 785      | 1177   | 14.12%  |
| Kingston            | 350      | 476    | 6.29%   |
| Intenso             | 333      | 468    | 5.99%   |
| WDC                 | 219      | 293    | 3.94%   |
| A-DATA Technology   | 115      | 157    | 2.07%   |
| OCZ                 | 110      | 140    | 1.98%   |
| Intel               | 107      | 150    | 1.92%   |
| Toshiba             | 74       | 96     | 1.33%   |
| Micron Technology   | 64       | 87     | 1.15%   |
| Patriot             | 59       | 91     | 1.06%   |
| China               | 57       | 70     | 1.02%   |
| Transcend           | 54       | 62     | 0.97%   |
| SPCC                | 42       | 60     | 0.76%   |
| Leven               | 35       | 45     | 0.63%   |
| Corsair             | 35       | 49     | 0.63%   |
| JMicron Technology  | 31       | 36     | 0.56%   |
| PNY                 | 27       | 42     | 0.49%   |
| Apacer              | 24       | 27     | 0.43%   |
| ASMT                | 22       | 30     | 0.4%    |
| SK hynix            | 21       | 25     | 0.38%   |
| Unknown             | 20       | 27     | 0.36%   |
| INNOVATION IT       | 18       | 22     | 0.32%   |
| Verbatim            | 17       | 27     | 0.31%   |
| SABRENT             | 17       | 22     | 0.31%   |
| LITEON              | 16       | 20     | 0.29%   |
| KingDian            | 15       | 18     | 0.27%   |
| Team                | 14       | 20     | 0.25%   |
| Seagate             | 13       | 17     | 0.23%   |
| Plextor             | 13       | 13     | 0.23%   |
| LITEONIT            | 13       | 13     | 0.23%   |
| Netac               | 12       | 14     | 0.22%   |
| Hewlett-Packard     | 12       | 15     | 0.22%   |
| Emtec               | 12       | 14     | 0.22%   |
| Mushkin             | 11       | 24     | 0.2%    |
| Unknown             | 10       | 11     | 0.18%   |
| Phison              | 10       | 26     | 0.18%   |
| GOODRAM             | 9        | 13     | 0.16%   |
| TO Exter            | 8        | 12     | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 4983     | 10896  | 42.82%  |
| SSD     | 4406     | 8240   | 37.87%  |
| NVMe    | 1937     | 3175   | 16.65%  |
| Unknown | 257      | 421    | 2.21%   |
| MMC     | 53       | 67     | 0.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 6773     | 18451  | 71.81%  |
| NVMe | 1935     | 3164   | 20.52%  |
| SAS  | 671      | 1117   | 7.11%   |
| MMC  | 53       | 67     | 0.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 5107     | 9653   | 48.88%  |
| 0.51-1.0   | 2949     | 5138   | 28.23%  |
| 1.01-2.0   | 1261     | 2195   | 12.07%  |
| 3.01-4.0   | 484      | 882    | 4.63%   |
| 2.01-3.0   | 334      | 616    | 3.2%    |
| 4.01-10.0  | 239      | 507    | 2.29%   |
| 10.01-20.0 | 69       | 136    | 0.66%   |
| 20.01-50.0 | 4        | 8      | 0.04%   |
| 0          | 1        | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1755     | 21.64%  |
| 251-500        | 1355     | 16.71%  |
| 501-1000       | 1236     | 15.24%  |
| 1001-2000      | 931      | 11.48%  |
| More than 3000 | 805      | 9.92%   |
| 1-20           | 622      | 7.67%   |
| 2001-3000      | 454      | 5.6%    |
| 51-100         | 379      | 4.67%   |
| Unknown        | 374      | 4.61%   |
| 21-50          | 200      | 2.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 2785     | 33.2%   |
| 21-50          | 1127     | 13.44%  |
| 101-250        | 958      | 11.42%  |
| 51-100         | 774      | 9.23%   |
| 251-500        | 700      | 8.35%   |
| 501-1000       | 663      | 7.9%    |
| 1001-2000      | 484      | 5.77%   |
| Unknown        | 374      | 4.46%   |
| More than 3000 | 305      | 3.64%   |
| 2001-3000      | 215      | 2.56%   |
| 0              | 3        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 19       | 24     | 2.32%   |
| Crucial CT525MX300SSD1 528GB          | 13       | 14     | 1.59%   |
| Samsung Electronics HD103UJ 1TB       | 12       | 12     | 1.46%   |
| SanDisk SSD PLUS 480GB                | 11       | 12     | 1.34%   |
| WDC WD20EARS-00MVWB0 2TB              | 10       | 13     | 1.22%   |
| Samsung Electronics SP2504C 250GB     | 9        | 10     | 1.1%    |
| Samsung Electronics HD501LJ 500GB     | 9        | 16     | 1.1%    |
| WDC WD20EFRX-68EUZN0 2TB              | 8        | 13     | 0.98%   |
| WDC WD10EARS-00Y5B1 1TB               | 8        | 9      | 0.98%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 7        | 8      | 0.85%   |
| Seagate ST3500418AS 500GB             | 7        | 8      | 0.85%   |
| Seagate ST1000DM003-9YN162 1TB        | 7        | 9      | 0.85%   |
| SanDisk SSD PLUS 240GB                | 7        | 7      | 0.85%   |
| WDC WD5000AADS-00S9B0 500GB           | 6        | 7      | 0.73%   |
| WDC WD20EARX-00PASB0 2TB              | 6        | 6      | 0.73%   |
| Seagate ST31000528AS 1TB              | 6        | 7      | 0.73%   |
| Seagate ST2000DL003-9VT166 2TB        | 6        | 6      | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB        | 6        | 8      | 0.73%   |
| Samsung Electronics HD160JJ 160GB     | 6        | 9      | 0.73%   |
| Samsung Electronics HD103SI 1TB       | 6        | 6      | 0.73%   |
| Toshiba DT01ACA100 1TB                | 5        | 6      | 0.61%   |
| Seagate ST31000524AS 1TB              | 5        | 5      | 0.61%   |
| Seagate ST2000DM001-1CH164 2TB        | 5        | 5      | 0.61%   |
| Samsung Electronics SSD 840 EVO 120GB | 5        | 6      | 0.61%   |
| Samsung Electronics HD753LJ 752GB     | 5        | 6      | 0.61%   |
| Samsung Electronics HD103SJ 1TB       | 5        | 5      | 0.61%   |
| Kingston SV300S37A120G 120GB SSD      | 5        | 6      | 0.61%   |
| Hitachi HDS721010CLA332 1TB           | 5        | 6      | 0.61%   |
| WDC WD5000AAKX-001CA0 500GB           | 4        | 5      | 0.49%   |
| WDC WD40EFRX-68N32N0 4TB              | 4        | 8      | 0.49%   |
| WDC WD30EFRX-68EUZN0 3TB              | 4        | 5      | 0.49%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 4        | 9      | 0.49%   |
| WDC WD20EZRX-00DC0B0 2TB              | 4        | 5      | 0.49%   |
| WDC WD10JPVX-22JC3T0 1TB              | 4        | 4      | 0.49%   |
| WDC WD10EARS-22Y5B1 1TB               | 4        | 4      | 0.49%   |
| WDC WD10EADS-00L5B1 1TB               | 4        | 4      | 0.49%   |
| Toshiba DT01ACA050 500GB              | 4        | 4      | 0.49%   |
| Seagate ST9500325AS 500GB             | 4        | 6      | 0.49%   |
| Seagate ST4000DM004-2CV104 4TB        | 4        | 4      | 0.49%   |
| Seagate ST3250410AS 250GB             | 4        | 4      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 209      | 291    | 26.26%  |
| Seagate             | 204      | 256    | 25.63%  |
| Samsung Electronics | 134      | 166    | 16.83%  |
| SanDisk             | 45       | 51     | 5.65%   |
| Hitachi             | 43       | 61     | 5.4%    |
| Crucial             | 29       | 35     | 3.64%   |
| Toshiba             | 28       | 31     | 3.52%   |
| Intenso             | 14       | 15     | 1.76%   |
| Intel               | 14       | 14     | 1.76%   |
| Maxtor              | 12       | 18     | 1.51%   |
| Kingston            | 10       | 12     | 1.26%   |
| HGST                | 10       | 10     | 1.26%   |
| Micron Technology   | 6        | 6      | 0.75%   |
| A-DATA Technology   | 5        | 5      | 0.63%   |
| WD MediaMax         | 4        | 4      | 0.5%    |
| IBM                 | 3        | 3      | 0.38%   |
| SK hynix            | 2        | 2      | 0.25%   |
| OCZ                 | 2        | 4      | 0.25%   |
| MDT                 | 2        | 2      | 0.25%   |
| Fujitsu             | 2        | 3      | 0.25%   |
| XPG                 | 1        | 1      | 0.13%   |
| USB3.0              | 1        | 1      | 0.13%   |
| Unknown             | 1        | 1      | 0.13%   |
| Transcend           | 1        | 1      | 0.13%   |
| TO Exter            | 1        | 1      | 0.13%   |
| SPCC                | 1        | 1      | 0.13%   |
| Plextor             | 1        | 1      | 0.13%   |
| OCZ-VERTEX2         | 1        | 1      | 0.13%   |
| Neo Forza           | 1        | 1      | 0.13%   |
| Mushkin             | 1        | 1      | 0.13%   |
| INNOVATION IT       | 1        | 1      | 0.13%   |
| IBM/Hitachi         | 1        | 1      | 0.13%   |
| IB                  | 1        | 1      | 0.13%   |
| Hewlett-Packard     | 1        | 1      | 0.13%   |
| GOODRAM             | 1        | 1      | 0.13%   |
| Corsair             | 1        | 1      | 0.13%   |
| ASMedia             | 1        | 1      | 0.13%   |
| Apple               | 1        | 1      | 0.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 204      | 256    | 33.5%   |
| WDC                 | 200      | 280    | 32.84%  |
| Samsung Electronics | 92       | 115    | 15.11%  |
| Hitachi             | 43       | 61     | 7.06%   |
| Toshiba             | 28       | 31     | 4.6%    |
| Maxtor              | 12       | 18     | 1.97%   |
| HGST                | 10       | 10     | 1.64%   |
| WD MediaMax         | 4        | 4      | 0.66%   |
| IBM                 | 3        | 3      | 0.49%   |
| MDT                 | 2        | 2      | 0.33%   |
| Intenso             | 2        | 2      | 0.33%   |
| Fujitsu             | 2        | 3      | 0.33%   |
| USB3.0              | 1        | 1      | 0.16%   |
| Unknown             | 1        | 1      | 0.16%   |
| IBM/Hitachi         | 1        | 1      | 0.16%   |
| IB                  | 1        | 1      | 0.16%   |
| Hewlett-Packard     | 1        | 1      | 0.16%   |
| ASMedia             | 1        | 1      | 0.16%   |
| Apple               | 1        | 1      | 0.16%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 558      | 792    | 75%     |
| SSD  | 160      | 186    | 21.51%  |
| NVMe | 26       | 29     | 3.49%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Samsung Electronics HD103UJ 1TB                  | 3        | 4      | 15%     |
| Samsung Electronics HD252HJ 250GB                | 2        | 2      | 10%     |
| WDC WD30EZRS-00J99B0 3TB                         | 1        | 1      | 5%      |
| WDC WD1600YS-23SHB0 160GB                        | 1        | 1      | 5%      |
| TPH00800640GB 640GB                              | 1        | 1      | 5%      |
| Toshiba MK3265GSX 320GB                          | 1        | 1      | 5%      |
| Toshiba MG03ACA300 3TB                           | 1        | 1      | 5%      |
| Seagate ST3640323AS 640GB                        | 1        | 1      | 5%      |
| Samsung Electronics SSD 980 500GB                | 1        | 1      | 5%      |
| Samsung Electronics SSD 980 1TB                  | 1        | 1      | 5%      |
| Samsung Electronics SSD 850 250GB                | 1        | 1      | 5%      |
| Samsung Electronics MZVLB1T0HALR-00000 1TB       | 1        | 2      | 5%      |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1        | 1      | 5%      |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1        | 2      | 5%      |
| Maxtor STM3500320AS 500GB                        | 1        | 1      | 5%      |
| Intenso SSD SATAIII 120GB                        | 1        | 1      | 5%      |
| Hitachi HDP725040GLA360 400GB                    | 1        | 1      | 5%      |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 14     | 55%     |
| WDC                 | 2        | 2      | 10%     |
| Toshiba             | 2        | 2      | 10%     |
| TPH00800640GB       | 1        | 1      | 5%      |
| Seagate             | 1        | 1      | 5%      |
| Maxtor              | 1        | 1      | 5%      |
| Intenso             | 1        | 1      | 5%      |
| Hitachi             | 1        | 1      | 5%      |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 4731     | 14188  | 56.69%  |
| Works    | 2875     | 7580   | 34.45%  |
| Malfunc  | 718      | 1007   | 8.6%    |
| Failed   | 20       | 23     | 0.24%   |
| Limited  | 1        | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 4179     | 38.62%  |
| AMD                              | 2971     | 27.45%  |
| Samsung Electronics              | 1065     | 9.84%   |
| ASMedia Technology               | 444      | 4.1%    |
| JMicron Technology               | 291      | 2.69%   |
| Marvell Technology Group         | 279      | 2.58%   |
| Nvidia                           | 253      | 2.34%   |
| SanDisk                          | 247      | 2.28%   |
| Phison Electronics               | 219      | 2.02%   |
| Kingston Technology Company      | 178      | 1.64%   |
| Micron/Crucial Technology        | 151      | 1.4%    |
| Silicon Motion                   | 69       | 0.64%   |
| VIA Technologies                 | 66       | 0.61%   |
| Adaptec                          | 50       | 0.46%   |
| Silicon Image                    | 48       | 0.44%   |
| ADATA Technology                 | 44       | 0.41%   |
| Broadcom / LSI                   | 34       | 0.31%   |
| LSI Logic / Symbios Logic        | 33       | 0.3%    |
| Toshiba America Info Systems     | 26       | 0.24%   |
| SK hynix                         | 21       | 0.19%   |
| Seagate Technology               | 19       | 0.18%   |
| Realtek Semiconductor            | 18       | 0.17%   |
| Micron Technology                | 16       | 0.15%   |
| KIOXIA                           | 13       | 0.12%   |
| MAXIO Technology (Hangzhou)      | 12       | 0.11%   |
| Integrated Technology Express    | 9        | 0.08%   |
| 3ware                            | 9        | 0.08%   |
| Silicon Integrated Systems [SiS] | 8        | 0.07%   |
| OCZ Technology Group             | 8        | 0.07%   |
| Shenzhen Longsys Electronics     | 5        | 0.05%   |
| Hewlett-Packard                  | 5        | 0.05%   |
| Lite-On Technology               | 4        | 0.04%   |
| Apple                            | 3        | 0.03%   |
| Advanced System Products         | 3        | 0.03%   |
| Union Memory (Shenzhen)          | 2        | 0.02%   |
| Transcend                        | 2        | 0.02%   |
| Tekram Technology                | 2        | 0.02%   |
| Promise Technology               | 2        | 0.02%   |
| Netac Technology                 | 2        | 0.02%   |
| Lite-On IT Corp. / Plextor       | 2        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1657     | 11.97%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 680      | 4.91%   |
| AMD 400 Series Chipset SATA Controller                                                  | 630      | 4.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 563      | 4.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 501      | 3.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 469      | 3.39%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 415      | 3%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 379      | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 378      | 2.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 370      | 2.67%   |
| AMD 500 Series Chipset SATA Controller                                                  | 336      | 2.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 320      | 2.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 268      | 1.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 245      | 1.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 198      | 1.43%   |
| Intel SATA Controller [RAID mode]                                                       | 187      | 1.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 185      | 1.34%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 183      | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 168      | 1.21%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 154      | 1.11%   |
| AMD 300 Series Chipset SATA Controller                                                  | 152      | 1.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 138      | 1%      |
| AMD FCH SATA Controller D                                                               | 136      | 0.98%   |
| AMD X370 Series Chipset SATA Controller                                                 | 123      | 0.89%   |
| Phison E12 NVMe Controller                                                              | 116      | 0.84%   |
| Nvidia MCP61 SATA Controller                                                            | 113      | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 106      | 0.77%   |
| Nvidia MCP61 IDE                                                                        | 101      | 0.73%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 101      | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 96       | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 94       | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 91       | 0.66%   |
| Kingston Company A2000 NVMe SSD                                                         | 87       | 0.63%   |
| Samsung NVMe SSD Controller 980                                                         | 86       | 0.62%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 86       | 0.62%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 76       | 0.55%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 70       | 0.51%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 68       | 0.49%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 68       | 0.49%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 67       | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 6254     | 58.3%   |
| NVMe | 1972     | 18.38%  |
| IDE  | 1951     | 18.19%  |
| RAID | 419      | 3.91%   |
| SCSI | 66       | 0.62%   |
| SAS  | 65       | 0.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4265     | 57.23%  |
| AMD                   | 3179     | 42.66%  |
| ARM                   | 3        | 0.04%   |
| Marvell Semiconductor | 2        | 0.03%   |
| PowerMac3,6           | 1        | 0.01%   |
| PowerMac10,2          | 1        | 0.01%   |
| Unknown               | 1        | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 185      | 2.46%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 166      | 2.21%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 111      | 1.48%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 103      | 1.37%   |
| AMD FX-8350 Eight-Core Processor            | 103      | 1.37%   |
| AMD FX-6300 Six-Core Processor              | 87       | 1.16%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 81       | 1.08%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 80       | 1.07%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 76       | 1.01%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 73       | 0.97%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 70       | 0.93%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 70       | 0.93%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 68       | 0.91%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 66       | 0.88%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 65       | 0.87%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 63       | 0.84%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 63       | 0.84%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 61       | 0.81%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 61       | 0.81%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 54       | 0.72%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 54       | 0.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 52       | 0.69%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 52       | 0.69%   |
| AMD FX-4300 Quad-Core Processor             | 52       | 0.69%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 50       | 0.67%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 50       | 0.67%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 49       | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 48       | 0.64%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 47       | 0.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 45       | 0.6%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 44       | 0.59%   |
| AMD Phenom II X4 955 Processor              | 44       | 0.59%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 43       | 0.57%   |
| AMD Phenom II X4 965 Processor              | 42       | 0.56%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 41       | 0.55%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 40       | 0.53%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 40       | 0.53%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 40       | 0.53%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 40       | 0.53%   |
| AMD Athlon II X2 250 Processor              | 40       | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1263     | 16.88%  |
| Intel Core i7           | 916      | 12.24%  |
| AMD Ryzen 5             | 760      | 10.15%  |
| AMD Ryzen 7             | 579      | 7.74%   |
| AMD FX                  | 410      | 5.48%   |
| Intel Core i3           | 390      | 5.21%   |
| Intel Xeon              | 325      | 4.34%   |
| Intel Core 2 Duo        | 233      | 3.11%   |
| Intel Celeron           | 215      | 2.87%   |
| AMD Ryzen 9             | 209      | 2.79%   |
| Intel Core 2 Quad       | 197      | 2.63%   |
| Other                   | 164      | 2.19%   |
| AMD Phenom II X4        | 159      | 2.12%   |
| Intel Pentium           | 148      | 1.98%   |
| AMD Ryzen 3             | 122      | 1.63%   |
| AMD Athlon II X2        | 116      | 1.55%   |
| Intel Pentium Dual-Core | 113      | 1.51%   |
| AMD A8                  | 108      | 1.44%   |
| AMD A10                 | 95       | 1.27%   |
| Intel Core i9           | 68       | 0.91%   |
| Intel Atom              | 66       | 0.88%   |
| AMD Athlon II X4        | 64       | 0.86%   |
| AMD Athlon 64 X2        | 60       | 0.8%    |
| AMD A4                  | 60       | 0.8%    |
| Intel Pentium 4         | 53       | 0.71%   |
| Intel Core 2            | 53       | 0.71%   |
| AMD Ryzen 5 PRO         | 47       | 0.63%   |
| AMD Phenom II X6        | 44       | 0.59%   |
| AMD Ryzen Threadripper  | 41       | 0.55%   |
| AMD Athlon              | 40       | 0.53%   |
| Intel Pentium D         | 24       | 0.32%   |
| AMD Phenom              | 24       | 0.32%   |
| Intel Pentium Dual      | 23       | 0.31%   |
| AMD A6                  | 23       | 0.31%   |
| AMD Ryzen 7 PRO         | 22       | 0.29%   |
| AMD G                   | 20       | 0.27%   |
| AMD E                   | 19       | 0.25%   |
| AMD Athlon X4           | 19       | 0.25%   |
| Intel Pentium Silver    | 18       | 0.24%   |
| AMD Athlon 64           | 18       | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 3110     | 41.49%  |
| 2       | 1769     | 23.6%   |
| 6       | 1087     | 14.5%   |
| 8       | 777      | 10.37%  |
| 12      | 190      | 2.53%   |
| 1       | 182      | 2.43%   |
| 3       | 147      | 1.96%   |
| 16      | 121      | 1.61%   |
| 10      | 47       | 0.63%   |
| Unknown | 20       | 0.27%   |
| 24      | 12       | 0.16%   |
| 14      | 11       | 0.15%   |
| 18      | 9        | 0.12%   |
| 32      | 8        | 0.11%   |
| 5       | 3        | 0.04%   |
| 20      | 2        | 0.03%   |
| 64      | 1        | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 7385     | 99.1%   |
| 2      | 67       | 0.9%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 4222     | 56.44%  |
| 1       | 3236     | 43.26%  |
| Unknown | 20       | 0.27%   |
| 4       | 2        | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 7327     | 98.01%  |
| Unknown        | 110      | 1.47%   |
| 32-bit         | 38       | 0.51%   |
| 64-bit         | 1        | 0.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1782     | 22.82%  |
| 0x306c3    | 533      | 6.82%   |
| 0x206a7    | 380      | 4.87%   |
| 0x306a9    | 375      | 4.8%    |
| 0x08701021 | 311      | 3.98%   |
| 0x1067a    | 303      | 3.88%   |
| 0x506e3    | 289      | 3.7%    |
| 0x06000852 | 229      | 2.93%   |
| 0x0800820d | 227      | 2.91%   |
| 0x010000c8 | 206      | 2.64%   |
| 0x906ea    | 173      | 2.22%   |
| 0x906e9    | 136      | 1.74%   |
| 0x08701013 | 132      | 1.69%   |
| 0x06001119 | 128      | 1.64%   |
| 0x6fb      | 98       | 1.25%   |
| 0x08108109 | 91       | 1.17%   |
| 0x08001138 | 81       | 1.04%   |
| 0x106e5    | 76       | 0.97%   |
| 0x0a201016 | 70       | 0.9%    |
| 0x0600063e | 67       | 0.86%   |
| 0x08001137 | 61       | 0.78%   |
| 0x010000db | 59       | 0.76%   |
| 0x0a201009 | 58       | 0.74%   |
| 0x906ed    | 57       | 0.73%   |
| 0xa0655    | 53       | 0.68%   |
| 0x08101016 | 52       | 0.67%   |
| 0x306f2    | 46       | 0.59%   |
| 0x08600106 | 46       | 0.59%   |
| 0x0810100b | 45       | 0.58%   |
| 0xa0671    | 44       | 0.56%   |
| 0x106a5    | 44       | 0.56%   |
| 0x6fd      | 43       | 0.55%   |
| 0x06003106 | 42       | 0.54%   |
| 0x20655    | 40       | 0.51%   |
| 0xa0653    | 37       | 0.47%   |
| 0x6f6      | 37       | 0.47%   |
| 0x406c4    | 36       | 0.46%   |
| 0x0a50000c | 36       | 0.46%   |
| 0x90672    | 35       | 0.45%   |
| 0x20652    | 35       | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 744      | 9.93%   |
| Zen 2            | 646      | 8.63%   |
| KabyLake         | 537      | 7.17%   |
| SandyBridge      | 516      | 6.89%   |
| IvyBridge        | 485      | 6.48%   |
| Piledriver       | 484      | 6.46%   |
| Zen+             | 461      | 6.16%   |
| K10              | 459      | 6.13%   |
| Penryn           | 428      | 5.72%   |
| Skylake          | 402      | 5.37%   |
| Zen              | 362      | 4.83%   |
| Zen 3            | 324      | 4.33%   |
| Core             | 236      | 3.15%   |
| Nehalem          | 158      | 2.11%   |
| Westmere         | 125      | 1.67%   |
| CometLake        | 114      | 1.52%   |
| Unknown          | 108      | 1.44%   |
| K8 Hammer        | 107      | 1.43%   |
| Silvermont       | 102      | 1.36%   |
| NetBurst         | 88       | 1.18%   |
| Bulldozer        | 83       | 1.11%   |
| Goldmont plus    | 64       | 0.85%   |
| Excavator        | 61       | 0.81%   |
| Steamroller      | 58       | 0.77%   |
| Alderlake Hybrid | 56       | 0.75%   |
| Bonnell          | 47       | 0.63%   |
| Bobcat           | 39       | 0.52%   |
| Broadwell        | 34       | 0.45%   |
| Jaguar           | 30       | 0.4%    |
| Icelake          | 29       | 0.39%   |
| K10 Llano        | 28       | 0.37%   |
| Goldmont         | 25       | 0.33%   |
| Puma             | 21       | 0.28%   |
| Tremont          | 9        | 0.12%   |
| TigerLake        | 6        | 0.08%   |
| P6               | 6        | 0.08%   |
| K6               | 5        | 0.07%   |
| Gracemont        | 2        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 3112     | 39.38%  |
| AMD                                          | 2697     | 34.13%  |
| Intel                                        | 1988     | 25.16%  |
| ASPEED Technology                            | 43       | 0.54%   |
| Matrox Electronics Systems                   | 40       | 0.51%   |
| ATI Technologies                             | 8        | 0.1%    |
| VIA Technologies                             | 4        | 0.05%   |
| Silicon Integrated Systems [SiS]             | 4        | 0.05%   |
| S3 Graphics                                  | 4        | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.03%   |
| Dome Imaging Systems                         | 1        | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 365      | 4.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 312      | 3.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 228      | 2.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 201      | 2.46%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 162      | 1.98%   |
| Intel HD Graphics 530                                                                    | 158      | 1.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 153      | 1.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 151      | 1.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 149      | 1.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 140      | 1.72%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 124      | 1.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 122      | 1.49%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 113      | 1.38%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 113      | 1.38%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 103      | 1.26%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 100      | 1.23%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 98       | 1.2%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 92       | 1.13%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 88       | 1.08%   |
| Nvidia GT218 [GeForce 210]                                                               | 83       | 1.02%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 81       | 0.99%   |
| Intel HD Graphics 630                                                                    | 79       | 0.97%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 76       | 0.93%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 74       | 0.91%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 73       | 0.89%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 73       | 0.89%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 71       | 0.87%   |
| AMD RS780L [Radeon 3000]                                                                 | 71       | 0.87%   |
| AMD Renoir                                                                               | 63       | 0.77%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 62       | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 62       | 0.76%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 62       | 0.76%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 61       | 0.75%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 59       | 0.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 54       | 0.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 53       | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 50       | 0.61%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 47       | 0.58%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 47       | 0.58%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 44       | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Nvidia                        | 2889     | 38.17%  |
| 1 x AMD                           | 2501     | 33.04%  |
| 1 x Intel                         | 1701     | 22.47%  |
| 2 x AMD                           | 98       | 1.29%   |
| Intel + Nvidia                    | 93       | 1.23%   |
| AMD + Nvidia                      | 61       | 0.81%   |
| 2 x Nvidia                        | 59       | 0.78%   |
| Intel + AMD                       | 40       | 0.53%   |
| 1 x Matrox                        | 37       | 0.49%   |
| 1 x ASPEED                        | 33       | 0.44%   |
| Other                             | 19       | 0.25%   |
| Nvidia + ASPEED                   | 5        | 0.07%   |
| 2 x Intel                         | 4        | 0.05%   |
| 1 x VIA                           | 4        | 0.05%   |
| 1 x SiS                           | 4        | 0.05%   |
| 1 x S3 Graphics                   | 4        | 0.05%   |
| AMD + ASPEED                      | 4        | 0.05%   |
| Nvidia + Matrox                   | 3        | 0.04%   |
| Nvidia + XGI                      | 2        | 0.03%   |
| Intel + AMD + 1 x Nvidia          | 2        | 0.03%   |
| 5 x AMD                           | 1        | 0.01%   |
| 4 x Nvidia                        | 1        | 0.01%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.01%   |
| Nvidia + Dome Imaging Systems     | 1        | 0.01%   |
| 1 x Intel + 4 x AMD               | 1        | 0.01%   |
| Intel + 2 x Nvidia                | 1        | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 5431     | 71.11%  |
| Proprietary | 1800     | 23.57%  |
| Unknown     | 407      | 5.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2946     | 37.64%  |
| 1.01-2.0   | 1143     | 14.6%   |
| 0.51-1.0   | 901      | 11.51%  |
| 0.01-0.5   | 814      | 10.4%   |
| 7.01-8.0   | 765      | 9.77%   |
| 3.01-4.0   | 690      | 8.82%   |
| 5.01-6.0   | 244      | 3.12%   |
| 8.01-16.0  | 204      | 2.61%   |
| 2.01-3.0   | 88       | 1.12%   |
| 16.01-24.0 | 23       | 0.29%   |
| 4.01-5.0   | 9        | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 1329     | 16.55%  |
| Goldstar             | 750      | 9.34%   |
| Acer                 | 659      | 8.21%   |
| Dell                 | 602      | 7.5%    |
| BenQ                 | 563      | 7.01%   |
| Ancor Communications | 425      | 5.29%   |
| Hewlett-Packard      | 368      | 4.58%   |
| AOC                  | 330      | 4.11%   |
| Philips              | 314      | 3.91%   |
| Fujitsu Siemens      | 249      | 3.1%    |
| Iiyama               | 241      | 3%      |
| Eizo                 | 206      | 2.57%   |
| Medion               | 173      | 2.15%   |
| LG Electronics       | 118      | 1.47%   |
| ASUSTek Computer     | 110      | 1.37%   |
| Unknown              | 105      | 1.31%   |
| Lenovo               | 104      | 1.3%    |
| NEC Computers        | 92       | 1.15%   |
| HannStar             | 87       | 1.08%   |
| ViewSonic            | 86       | 1.07%   |
| Sony                 | 80       | 1%      |
| Belinea              | 57       | 0.71%   |
| Vestel Elektronik    | 53       | 0.66%   |
| Compal               | 53       | 0.66%   |
| Panasonic            | 51       | 0.64%   |
| Idek Iiyama          | 44       | 0.55%   |
| Grundig              | 41       | 0.51%   |
| Toshiba              | 38       | 0.47%   |
| MSI                  | 32       | 0.4%    |
| FUS                  | 29       | 0.36%   |
| Hitachi              | 24       | 0.3%    |
| Plain Tree Systems   | 20       | 0.25%   |
| Gigabyte Technology  | 20       | 0.25%   |
| Unknown              | 20       | 0.25%   |
| AUS                  | 19       | 0.24%   |
| HPN                  | 18       | 0.22%   |
| HannStar Display     | 17       | 0.21%   |
| HKC                  | 16       | 0.2%    |
| DENON                | 16       | 0.2%    |
| CHD                  | 15       | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch  | 53       | 0.61%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 45       | 0.52%   |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch     | 40       | 0.46%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 37       | 0.43%   |
| Grundig WUXGA GRU4448 1920x1080                                       | 37       | 0.43%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 34       | 0.39%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 33       | 0.38%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 31       | 0.36%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 27       | 0.31%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 27       | 0.31%   |
| Acer S242HL ACR0216 1920x1080 531x299mm 24.0-inch                     | 27       | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 24       | 0.28%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch      | 24       | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 23       | 0.27%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 22       | 0.25%   |
| Panasonic TV MEIA296 3840x2160 708x398mm 32.0-inch                    | 21       | 0.24%   |
| Unknown                                                               | 20       | 0.23%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 19       | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 19       | 0.22%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 19       | 0.22%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 19       | 0.22%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 18       | 0.21%   |
| Goldstar 32inch FHD GSM76F5 1920x1080 698x392mm 31.5-inch             | 18       | 0.21%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 18       | 0.21%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                  | 17       | 0.2%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 17       | 0.2%    |
| BenQ GL2450 BNQ78A5 1920x1080 530x300mm 24.0-inch                     | 17       | 0.2%    |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 17       | 0.2%    |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 17       | 0.2%    |
| Toshiba TV TSB0108 1920x540                                           | 16       | 0.19%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                  | 16       | 0.19%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 16       | 0.19%   |
| Unknown LCD Monitor SAMSUNG                                           | 15       | 0.17%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 15       | 0.17%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                  | 14       | 0.16%   |
| Fujitsu Siemens P19-2 FUS0552 1280x1024 376x301mm 19.0-inch           | 14       | 0.16%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 14       | 0.16%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                     | 14       | 0.16%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 14       | 0.16%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 14       | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 3408     | 43.4%   |
| 3840x2160 (4K)     | 807      | 10.28%  |
| 1280x1024 (SXGA)   | 659      | 8.39%   |
| 2560x1440 (QHD)    | 654      | 8.33%   |
| 1680x1050 (WSXGA+) | 623      | 7.93%   |
| 1920x1200 (WUXGA)  | 360      | 4.58%   |
| Unknown            | 267      | 3.4%    |
| 3440x1440          | 155      | 1.97%   |
| 1440x900 (WXGA+)   | 130      | 1.66%   |
| 3840x1080          | 125      | 1.59%   |
| 1600x900 (HD+)     | 69       | 0.88%   |
| 2560x1080          | 66       | 0.84%   |
| 1366x768 (WXGA)    | 66       | 0.84%   |
| 1600x1200          | 64       | 0.81%   |
| 1920x540           | 51       | 0.65%   |
| 1360x768           | 45       | 0.57%   |
| 1024x768 (XGA)     | 37       | 0.47%   |
| 4480x1440          | 21       | 0.27%   |
| 3840x1600          | 21       | 0.27%   |
| 3840x1200          | 20       | 0.25%   |
| 2560x1600          | 16       | 0.2%    |
| 5760x2160          | 14       | 0.18%   |
| 1280x720 (HD)      | 14       | 0.18%   |
| 3200x1080          | 12       | 0.15%   |
| 2048x1152          | 11       | 0.14%   |
| 3600x1080          | 10       | 0.13%   |
| 5120x1440          | 9        | 0.11%   |
| 5760x1080          | 8        | 0.1%    |
| 1400x1050          | 8        | 0.1%    |
| 7680x2160          | 7        | 0.09%   |
| 2288x1287          | 7        | 0.09%   |
| 3360x1080          | 4        | 0.05%   |
| 1280x768           | 4        | 0.05%   |
| 6400x2160          | 3        | 0.04%   |
| 3360x1050          | 3        | 0.04%   |
| 7680x1440          | 2        | 0.03%   |
| 5520x1080          | 2        | 0.03%   |
| 5360x1440          | 2        | 0.03%   |
| 5280x1080          | 2        | 0.03%   |
| 5200x1200          | 2        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 1268     | 16.01%  |
| 24      | 1263     | 15.94%  |
| Unknown | 983      | 12.41%  |
| 23      | 938      | 11.84%  |
| 21      | 621      | 7.84%   |
| 19      | 546      | 6.89%   |
| 22      | 482      | 6.08%   |
| 31      | 268      | 3.38%   |
| 17      | 181      | 2.28%   |
| 34      | 165      | 2.08%   |
| 20      | 157      | 1.98%   |
| 84      | 155      | 1.96%   |
| 40      | 86       | 1.09%   |
| 54      | 81       | 1.02%   |
| 72      | 80       | 1.01%   |
| 32      | 75       | 0.95%   |
| 25      | 74       | 0.93%   |
| 18      | 66       | 0.83%   |
| 15      | 50       | 0.63%   |
| 28      | 34       | 0.43%   |
| 65      | 31       | 0.39%   |
| 26      | 28       | 0.35%   |
| 48      | 25       | 0.32%   |
| 16      | 24       | 0.3%    |
| 37      | 23       | 0.29%   |
| 33      | 23       | 0.29%   |
| 35      | 19       | 0.24%   |
| 52      | 18       | 0.23%   |
| 42      | 17       | 0.21%   |
| 36      | 15       | 0.19%   |
| 39      | 12       | 0.15%   |
| 55      | 11       | 0.14%   |
| 49      | 11       | 0.14%   |
| 29      | 11       | 0.14%   |
| 43      | 10       | 0.13%   |
| 46      | 9        | 0.11%   |
| 50      | 8        | 0.1%    |
| 47      | 8        | 0.1%    |
| 14      | 7        | 0.09%   |
| 60      | 6        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 3162     | 41.19%  |
| 401-500        | 1447     | 18.85%  |
| Unknown        | 983      | 12.81%  |
| 601-700        | 461      | 6.01%   |
| 351-400        | 454      | 5.91%   |
| 701-800        | 277      | 3.61%   |
| 301-350        | 251      | 3.27%   |
| 1501-2000      | 239      | 3.11%   |
| 1001-1500      | 215      | 2.8%    |
| 801-900        | 142      | 1.85%   |
| 901-1000       | 24       | 0.31%   |
| 201-300        | 14       | 0.18%   |
| More than 2000 | 5        | 0.07%   |
| 101-200        | 2        | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 4277     | 57.81%  |
| 16/10   | 1124     | 15.19%  |
| Unknown | 884      | 11.95%  |
| 5/4     | 607      | 8.2%    |
| 21/9    | 217      | 2.93%   |
| 4/3     | 138      | 1.87%   |
| 3/2     | 59       | 0.8%    |
| 32/9    | 39       | 0.53%   |
| 6/5     | 37       | 0.5%    |
| 1.00    | 7        | 0.09%   |
| 3.20    | 4        | 0.05%   |
| 0.56    | 3        | 0.04%   |
| 1.96    | 1        | 0.01%   |
| 0.25    | 1        | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 2582     | 33.21%  |
| 301-350        | 1291     | 16.61%  |
| Unknown        | 983      | 12.64%  |
| 151-200        | 868      | 11.17%  |
| 351-500        | 589      | 7.58%   |
| 251-300        | 540      | 6.95%   |
| More than 1000 | 408      | 5.25%   |
| 141-150        | 218      | 2.8%    |
| 501-1000       | 202      | 2.6%    |
| 101-110        | 50       | 0.64%   |
| 131-140        | 24       | 0.31%   |
| 71-80          | 6        | 0.08%   |
| 111-120        | 4        | 0.05%   |
| 91-100         | 3        | 0.04%   |
| 1-40           | 2        | 0.03%   |
| 81-90          | 1        | 0.01%   |
| 61-70          | 1        | 0.01%   |
| 51-60          | 1        | 0.01%   |
| 121-130        | 1        | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 4554     | 61.53%  |
| 101-120       | 1166     | 15.75%  |
| Unknown       | 983      | 13.28%  |
| 121-160       | 315      | 4.26%   |
| 1-50          | 247      | 3.34%   |
| 161-240       | 134      | 1.81%   |
| More than 240 | 2        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5743     | 75.24%  |
| 2     | 1220     | 15.98%  |
| 0     | 495      | 6.48%   |
| 3     | 153      | 2%      |
| 4     | 20       | 0.26%   |
| 5     | 2        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 4455     | 44.6%   |
| Intel                           | 3022     | 30.26%  |
| Qualcomm Atheros                | 539      | 5.4%    |
| Broadcom                        | 269      | 2.69%   |
| Nvidia                          | 213      | 2.13%   |
| Ralink Technology               | 168      | 1.68%   |
| TP-Link                         | 137      | 1.37%   |
| AVM                             | 98       | 0.98%   |
| Microsoft                       | 97       | 0.97%   |
| Marvell Technology Group        | 68       | 0.68%   |
| MediaTek                        | 64       | 0.64%   |
| Broadcom Limited                | 64       | 0.64%   |
| IMC Networks                    | 63       | 0.63%   |
| Ralink                          | 61       | 0.61%   |
| D-Link System                   | 55       | 0.55%   |
| Edimax Technology               | 51       | 0.51%   |
| Aquantia                        | 51       | 0.51%   |
| Samsung Electronics             | 37       | 0.37%   |
| Qualcomm Atheros Communications | 35       | 0.35%   |
| D-Link                          | 33       | 0.33%   |
| ASUSTek Computer                | 31       | 0.31%   |
| VIA Technologies                | 28       | 0.28%   |
| NetGear                         | 22       | 0.22%   |
| Belkin Components               | 22       | 0.22%   |
| ASIX Electronics                | 19       | 0.19%   |
| Huawei Technologies             | 18       | 0.18%   |
| Sitecom Europe                  | 17       | 0.17%   |
| Mellanox Technologies           | 17       | 0.17%   |
| 3Com                            | 16       | 0.16%   |
| DisplayLink                     | 13       | 0.13%   |
| Xiaomi                          | 12       | 0.12%   |
| American Megatrends             | 12       | 0.12%   |
| ZyXEL Communications            | 8        | 0.08%   |
| Arduino SA                      | 8        | 0.08%   |
| Dresden Elektronik              | 7        | 0.07%   |
| ZyDAS                           | 5        | 0.05%   |
| Holtek Semiconductor            | 5        | 0.05%   |
| Apple                           | 5        | 0.05%   |
| ADMtek                          | 5        | 0.05%   |
| Texas Instruments               | 4        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3715     | 33.31%  |
| Intel I211 Gigabit Network Connection                             | 514      | 4.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 325      | 2.91%   |
| Intel Wi-Fi 6 AX200                                               | 296      | 2.65%   |
| Intel Ethernet Connection (2) I219-V                              | 296      | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 277      | 2.48%   |
| Intel 82579V Gigabit Network Connection                           | 164      | 1.47%   |
| Intel Ethernet Controller I225-V                                  | 152      | 1.36%   |
| Intel Ethernet Connection I217-LM                                 | 143      | 1.28%   |
| Intel Ethernet Connection I217-V                                  | 134      | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 122      | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 112      | 1%      |
| Intel Ethernet Connection (7) I219-V                              | 110      | 0.99%   |
| Nvidia MCP61 Ethernet                                             | 104      | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 101      | 0.91%   |
| Intel I210 Gigabit Network Connection                             | 89       | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                             | 87       | 0.78%   |
| Intel Ethernet Connection (2) I218-V                              | 85       | 0.76%   |
| Intel Wireless-AC 9260                                            | 84       | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 73       | 0.65%   |
| Intel 82574L Gigabit Network Connection                           | 70       | 0.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 64       | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62       | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 59       | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 56       | 0.5%    |
| Microsoft Xbox 360 Wireless Adapter                               | 53       | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 50       | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 49       | 0.44%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]              | 49       | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 48       | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 47       | 0.42%   |
| Realtek 802.11ac NIC                                              | 47       | 0.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 45       | 0.4%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 43       | 0.39%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 41       | 0.37%   |
| Intel Wireless 3165                                               | 40       | 0.36%   |
| Intel Wireless 8260                                               | 39       | 0.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 39       | 0.35%   |
| AVM FRITZ!WLAN AC 860                                             | 39       | 0.35%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 38       | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 857      | 30.52%  |
| Realtek Semiconductor                 | 661      | 23.54%  |
| Qualcomm Atheros                      | 234      | 8.33%   |
| Ralink Technology                     | 168      | 5.98%   |
| TP-Link                               | 127      | 4.52%   |
| AVM                                   | 98       | 3.49%   |
| Microsoft                             | 97       | 3.45%   |
| Broadcom                              | 75       | 2.67%   |
| IMC Networks                          | 63       | 2.24%   |
| MediaTek                              | 62       | 2.21%   |
| Ralink                                | 61       | 2.17%   |
| Edimax Technology                     | 51       | 1.82%   |
| D-Link System                         | 42       | 1.5%    |
| Qualcomm Atheros Communications       | 35       | 1.25%   |
| ASUSTek Computer                      | 31       | 1.1%    |
| D-Link                                | 30       | 1.07%   |
| NetGear                               | 22       | 0.78%   |
| Belkin Components                     | 19       | 0.68%   |
| Sitecom Europe                        | 17       | 0.61%   |
| ZyXEL Communications                  | 8        | 0.28%   |
| Broadcom Limited                      | 8        | 0.28%   |
| ZyDAS                                 | 5        | 0.18%   |
| Philips (or NXP)                      | 4        | 0.14%   |
| Marvell Technology Group              | 4        | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.14%   |
| Wacom                                 | 3        | 0.11%   |
| Linksys                               | 3        | 0.11%   |
| Gemtek                                | 3        | 0.11%   |
| Sweex                                 | 2        | 0.07%   |
| Accton Technology                     | 2        | 0.07%   |
| Z-Com                                 | 1        | 0.04%   |
| Wilocity                              | 1        | 0.04%   |
| VIA Technologies                      | 1        | 0.04%   |
| Texas Instruments                     | 1        | 0.04%   |
| Sierra Wireless                       | 1        | 0.04%   |
| PLANEX                                | 1        | 0.04%   |
| LSI                                   | 1        | 0.04%   |
| Intersil                              | 1        | 0.04%   |
| Fujitsu Siemens Computers             | 1        | 0.04%   |
| Fiberline                             | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 296      | 10.4%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 122      | 4.29%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 112      | 3.94%   |
| Intel Wireless-AC 9260                                               | 84       | 2.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 59       | 2.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 56       | 1.97%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 53       | 1.86%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                 | 49       | 1.72%   |
| Realtek 802.11ac NIC                                                 | 47       | 1.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 45       | 1.58%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 41       | 1.44%   |
| Intel Wireless 3165                                                  | 40       | 1.41%   |
| Intel Wireless 8260                                                  | 39       | 1.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 39       | 1.37%   |
| AVM FRITZ!WLAN AC 860                                                | 39       | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 37       | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 37       | 1.3%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 36       | 1.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 33       | 1.16%   |
| Intel Wireless 7265                                                  | 33       | 1.16%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 33       | 1.16%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 33       | 1.16%   |
| Microsoft XBOX ACC                                                   | 31       | 1.09%   |
| Intel Wireless 7260                                                  | 31       | 1.09%   |
| Ralink RT5370 Wireless Adapter                                       | 30       | 1.05%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 29       | 1.02%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 29       | 1.02%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 27       | 0.95%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 27       | 0.95%   |
| Ralink RT5572 Wireless Adapter                                       | 27       | 0.95%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 27       | 0.95%   |
| Intel Wireless 8265 / 8275                                           | 26       | 0.91%   |
| AVM FRITZ WLAN N v2 [RT5572/rt2870.bin]                              | 26       | 0.91%   |
| Qualcomm Atheros AR9271 802.11n                                      | 25       | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 24       | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 24       | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 23       | 0.81%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 22       | 0.77%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 22       | 0.77%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B2) [Ralink RT3072] | 22       | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 4208     | 52.95%  |
| Intel                                  | 2587     | 32.55%  |
| Qualcomm Atheros                       | 324      | 4.08%   |
| Nvidia                                 | 213      | 2.68%   |
| Broadcom                               | 196      | 2.47%   |
| Marvell Technology Group               | 64       | 0.81%   |
| Broadcom Limited                       | 56       | 0.7%    |
| Aquantia                               | 51       | 0.64%   |
| VIA Technologies                       | 27       | 0.34%   |
| Samsung Electronics                    | 26       | 0.33%   |
| ASIX Electronics                       | 19       | 0.24%   |
| 3Com                                   | 16       | 0.2%    |
| Mellanox Technologies                  | 15       | 0.19%   |
| DisplayLink                            | 13       | 0.16%   |
| D-Link System                          | 13       | 0.16%   |
| Xiaomi                                 | 12       | 0.15%   |
| Huawei Technologies                    | 12       | 0.15%   |
| American Megatrends                    | 12       | 0.15%   |
| TP-Link                                | 10       | 0.13%   |
| Apple                                  | 5        | 0.06%   |
| ADMtek                                 | 5        | 0.06%   |
| JMicron Technology                     | 4        | 0.05%   |
| Emulex                                 | 4        | 0.05%   |
| ZTE WCDMA Technologies MSM             | 3        | 0.04%   |
| Qualcomm                               | 3        | 0.04%   |
| Netchip Technology                     | 3        | 0.04%   |
| Google                                 | 3        | 0.04%   |
| D-Link                                 | 3        | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.03%   |
| Silicon Integrated Systems [SiS]       | 2        | 0.03%   |
| QLogic                                 | 2        | 0.03%   |
| MediaTek                               | 2        | 0.03%   |
| Lenovo                                 | 2        | 0.03%   |
| ICS Advent                             | 2        | 0.03%   |
| HMD Global                             | 2        | 0.03%   |
| Dell                                   | 2        | 0.03%   |
| Belkin Components                      | 2        | 0.03%   |
| Trident Microsystems                   | 1        | 0.01%   |
| Total Phase                            | 1        | 0.01%   |
| Tehuti Networks                        | 1        | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3715     | 45.23%  |
| Intel I211 Gigabit Network Connection                             | 514      | 6.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 325      | 3.96%   |
| Intel Ethernet Connection (2) I219-V                              | 296      | 3.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 277      | 3.37%   |
| Intel 82579V Gigabit Network Connection                           | 164      | 2%      |
| Intel Ethernet Controller I225-V                                  | 152      | 1.85%   |
| Intel Ethernet Connection I217-LM                                 | 143      | 1.74%   |
| Intel Ethernet Connection I217-V                                  | 134      | 1.63%   |
| Intel Ethernet Connection (7) I219-V                              | 110      | 1.34%   |
| Nvidia MCP61 Ethernet                                             | 104      | 1.27%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 101      | 1.23%   |
| Intel I210 Gigabit Network Connection                             | 89       | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 87       | 1.06%   |
| Intel Ethernet Connection (2) I218-V                              | 85       | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 73       | 0.89%   |
| Intel 82574L Gigabit Network Connection                           | 70       | 0.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 64       | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62       | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 50       | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 49       | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 48       | 0.58%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 47       | 0.57%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 43       | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 38       | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 37       | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 35       | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 32       | 0.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 32       | 0.39%   |
| Intel 82578DM Gigabit Network Connection                          | 29       | 0.35%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 27       | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 26       | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 26       | 0.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 26       | 0.32%   |
| Intel 82578DC Gigabit Network Connection                          | 26       | 0.32%   |
| Nvidia MCP73 Ethernet                                             | 25       | 0.3%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 25       | 0.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 24       | 0.29%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 23       | 0.28%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 22       | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 7399     | 73.13%  |
| WiFi     | 2629     | 25.98%  |
| Modem    | 73       | 0.72%   |
| Unknown  | 17       | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 6367     | 82.91%  |
| WiFi     | 1309     | 17.05%  |
| Unknown  | 2        | 0.03%   |
| Modem    | 1        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5281     | 70.43%  |
| 2     | 1838     | 24.51%  |
| 3     | 259      | 3.45%   |
| 4     | 43       | 0.57%   |
| 0     | 43       | 0.57%   |
| 5     | 15       | 0.2%    |
| 6     | 10       | 0.13%   |
| 7     | 3        | 0.04%   |
| 18    | 2        | 0.03%   |
| 8     | 2        | 0.03%   |
| 12    | 1        | 0.01%   |
| 9     | 1        | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4995     | 64.62%  |
| Yes  | 2735     | 35.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 790      | 37.67%  |
| Cambridge Silicon Radio         | 604      | 28.8%   |
| Realtek Semiconductor           | 167      | 7.96%   |
| ASUSTek Computer                | 147      | 7.01%   |
| Broadcom                        | 102      | 4.86%   |
| Qualcomm Atheros Communications | 66       | 3.15%   |
| MediaTek                        | 42       | 2%      |
| IMC Networks                    | 34       | 1.62%   |
| Lite-On Technology              | 22       | 1.05%   |
| Apple                           | 22       | 1.05%   |
| Integrated System Solution      | 21       | 1%      |
| Belkin Components               | 16       | 0.76%   |
| TP-Link                         | 14       | 0.67%   |
| Edimax Technology               | 10       | 0.48%   |
| Logitech                        | 7        | 0.33%   |
| Foxconn / Hon Hai               | 5        | 0.24%   |
| HTC (High Tech Computer)        | 4        | 0.19%   |
| Qcom                            | 3        | 0.14%   |
| Micro Star International        | 3        | 0.14%   |
| Unknown                         | 3        | 0.14%   |
| Motorola PCS                    | 2        | 0.1%    |
| Conwise Technology              | 2        | 0.1%    |
| Toshiba                         | 1        | 0.05%   |
| SINO WEALTH                     | 1        | 0.05%   |
| Realtek                         | 1        | 0.05%   |
| National Semiconductor          | 1        | 0.05%   |
| Microsoft                       | 1        | 0.05%   |
| ISSC                            | 1        | 0.05%   |
| i.Tech Dynamic Limited          | 1        | 0.05%   |
| Hewlett-Packard                 | 1        | 0.05%   |
| Fujitsu Siemens Computers       | 1        | 0.05%   |
| Dell                            | 1        | 0.05%   |
| AVM                             | 1        | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 603      | 28.69%  |
| Intel AX200 Bluetooth                                 | 271      | 12.89%  |
| Intel Bluetooth wireless interface                    | 181      | 8.61%   |
| Intel Wireless-AC 3168 Bluetooth                      | 116      | 5.52%   |
| Realtek Bluetooth Radio                               | 113      | 5.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 81       | 3.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 69       | 3.28%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 65       | 3.09%   |
| MediaTek Wireless_Device                              | 42       | 2%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 42       | 2%      |
| Intel AX201 Bluetooth                                 | 39       | 1.86%   |
| Intel AX210 Bluetooth                                 | 38       | 1.81%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 37       | 1.76%   |
| Realtek  Bluetooth 4.2 Adapter                        | 35       | 1.67%   |
| ASUS ASUS USB-BT500                                   | 26       | 1.24%   |
| ASUS Bluetooth Radio                                  | 22       | 1.05%   |
| IMC Networks Bluetooth Radio                          | 17       | 0.81%   |
| Intel Bluetooth Device                                | 15       | 0.71%   |
| TP-Link UB500 Adapter                                 | 14       | 0.67%   |
| Lite-On Bluetooth Device                              | 12       | 0.57%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 12       | 0.57%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 11       | 0.52%   |
| ASUS Bluetooth Adapter                                | 11       | 0.52%   |
| Integrated System Solution Bluetooth Device           | 10       | 0.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 9        | 0.43%   |
| Realtek RTL8821A Bluetooth                            | 8        | 0.38%   |
| Realtek Bluetooth 5.1 Radio                           | 8        | 0.38%   |
| Qualcomm Atheros  Bluetooth Device                    | 8        | 0.38%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 8        | 0.38%   |
| ASUS Qualcomm Bluetooth 4.1                           | 8        | 0.38%   |
| Apple Bluetooth Host Controller                       | 8        | 0.38%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 7        | 0.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 7        | 0.33%   |
| Edimax Bluetooth Adapter                              | 7        | 0.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 7        | 0.33%   |
| IMC Networks Wireless_Device                          | 6        | 0.29%   |
| ASUS BCM20702A0                                       | 6        | 0.29%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 5        | 0.24%   |
| Broadcom Bluetooth 3.0 Device                         | 5        | 0.24%   |
| Broadcom BCM2035 Bluetooth dongle                     | 5        | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 3925     | 31.38%  |
| AMD                       | 3682     | 29.44%  |
| Nvidia                    | 2932     | 23.44%  |
| C-Media Electronics       | 357      | 2.85%   |
| Creative Labs             | 208      | 1.66%   |
| Logitech                  | 140      | 1.12%   |
| Texas Instruments         | 86       | 0.69%   |
| GN Netcom                 | 61       | 0.49%   |
| Focusrite-Novation        | 59       | 0.47%   |
| JMTek                     | 58       | 0.46%   |
| Creative Technology       | 58       | 0.46%   |
| Kingston Technology       | 56       | 0.45%   |
| VIA Technologies          | 54       | 0.43%   |
| Razer USA                 | 44       | 0.35%   |
| ASUSTek Computer          | 44       | 0.35%   |
| Plantronics               | 38       | 0.3%    |
| Yamaha                    | 35       | 0.28%   |
| DSEA A/S                  | 31       | 0.25%   |
| SteelSeries ApS           | 30       | 0.24%   |
| Generalplus Technology    | 30       | 0.24%   |
| Corsair                   | 30       | 0.24%   |
| RODE Microphones          | 26       | 0.21%   |
| Samson Technologies       | 23       | 0.18%   |
| BEHRINGER International   | 21       | 0.17%   |
| TerraTec Electronic       | 16       | 0.13%   |
| Micro Star International  | 16       | 0.13%   |
| Realtek Semiconductor     | 14       | 0.11%   |
| Sennheiser Communications | 13       | 0.1%    |
| Dell                      | 13       | 0.1%    |
| Native Instruments        | 12       | 0.1%    |
| M-Audio                   | 12       | 0.1%    |
| GYROCOM C&C               | 12       | 0.1%    |
| Blue Microphones          | 12       | 0.1%    |
| USB MICROPHONE            | 11       | 0.09%   |
| ROCCAT                    | 11       | 0.09%   |
| Tenx Technology           | 10       | 0.08%   |
| Valve Software            | 9        | 0.07%   |
| Sony                      | 9        | 0.07%   |
| AKAI Professional M.I.    | 9        | 0.07%   |
| XMOS                      | 8        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 773      | 5.2%    |
| AMD Starship/Matisse HD Audio Controller                                          | 749      | 5.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 538      | 3.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 501      | 3.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 467      | 3.14%   |
| AMD Family 17h/19h HD Audio Controller                                            | 431      | 2.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 411      | 2.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 365      | 2.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 364      | 2.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 341      | 2.29%   |
| AMD FCH Azalia Controller                                                         | 287      | 1.93%   |
| Intel 200 Series PCH HD Audio                                                     | 278      | 1.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 276      | 1.86%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 271      | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 242      | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 222      | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                        | 206      | 1.39%   |
| Nvidia GP104 High Definition Audio Controller                                     | 195      | 1.31%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 193      | 1.3%    |
| Nvidia GP106 High Definition Audio Controller                                     | 189      | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 175      | 1.18%   |
| AMD Navi 10 HDMI Audio                                                            | 168      | 1.13%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 163      | 1.1%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 159      | 1.07%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 154      | 1.04%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 147      | 0.99%   |
| Nvidia High Definition Audio Controller                                           | 139      | 0.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 139      | 0.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 137      | 0.92%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 136      | 0.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 136      | 0.92%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 131      | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                                     | 125      | 0.84%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 124      | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                     | 120      | 0.81%   |
| Nvidia GP108 High Definition Audio Controller                                     | 113      | 0.76%   |
| Nvidia MCP61 High Definition Audio                                                | 107      | 0.72%   |
| Nvidia GK104 HDMI Audio Controller                                                | 104      | 0.7%    |
| Nvidia GF119 HDMI Audio Controller                                                | 103      | 0.69%   |
| Nvidia TU106 High Definition Audio Controller                                     | 102      | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 598      | 14.65%  |
| Unknown             | 594      | 14.55%  |
| Kingston            | 532      | 13.03%  |
| Corsair             | 492      | 12.05%  |
| Crucial             | 470      | 11.51%  |
| Samsung Electronics | 453      | 11.09%  |
| SK hynix            | 291      | 7.13%   |
| Micron Technology   | 192      | 4.7%    |
| Nanya Technology    | 67       | 1.64%   |
| A-DATA Technology   | 64       | 1.57%   |
| Team                | 50       | 1.22%   |
| Ramaxel Technology  | 30       | 0.73%   |
| Patriot             | 27       | 0.66%   |
| Unknown             | 26       | 0.64%   |
| Elpida              | 19       | 0.47%   |
| Unknown (ABCD)      | 16       | 0.39%   |
| Transcend           | 16       | 0.39%   |
| GeIL                | 13       | 0.32%   |
| GOODRAM             | 12       | 0.29%   |
| Unifosa             | 8        | 0.2%    |
| Avant               | 8        | 0.2%    |
| Toshiba             | 6        | 0.15%   |
| PNY                 | 4        | 0.1%    |
| Mushkin             | 4        | 0.1%    |
| Hewlett-Packard     | 4        | 0.1%    |
| CSX                 | 4        | 0.1%    |
| Apacer              | 4        | 0.1%    |
| Timetec             | 3        | 0.07%   |
| Swissbit            | 3        | 0.07%   |
| Silicon Power       | 3        | 0.07%   |
| Qimonda             | 3        | 0.07%   |
| Patriot Memory      | 3        | 0.07%   |
| Lexar               | 3        | 0.07%   |
| Golden Empire       | 3        | 0.07%   |
| Exceleram           | 3        | 0.07%   |
| Aeneon              | 3        | 0.07%   |
| 48spaces            | 3        | 0.07%   |
| Unknown (0x9801)    | 2        | 0.05%   |
| TakeMS              | 2        | 0.05%   |
| S                   | 2        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 81       | 1.82%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 52       | 1.17%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 47       | 1.05%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s             | 43       | 0.96%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 40       | 0.9%    |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s        | 39       | 0.87%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s           | 31       | 0.69%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 30       | 0.67%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 27       | 0.61%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s          | 26       | 0.58%   |
| Unknown                                                        | 26       | 0.58%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 22       | 0.49%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 22       | 0.49%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 22       | 0.49%   |
| Corsair RAM CMX8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s            | 19       | 0.43%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 19       | 0.43%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 18       | 0.4%    |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s           | 18       | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 17       | 0.38%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s            | 17       | 0.38%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s            | 17       | 0.38%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 17       | 0.38%   |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 3200MT/s          | 17       | 0.38%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 17       | 0.38%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 16       | 0.36%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 16       | 0.36%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s                 | 16       | 0.36%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 16       | 0.36%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 16       | 0.36%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                   | 15       | 0.34%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 15       | 0.34%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 15       | 0.34%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 15       | 0.34%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s         | 15       | 0.34%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s          | 15       | 0.34%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s          | 15       | 0.34%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 14       | 0.31%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 14       | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 14       | 0.31%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 14       | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 1794     | 48.55%  |
| DDR3    | 1185     | 32.07%  |
| Unknown | 278      | 7.52%   |
| DDR2    | 180      | 4.87%   |
| SDRAM   | 162      | 4.38%   |
| DDR     | 37       | 1%      |
| DDR5    | 30       | 0.81%   |
| LPDDR4  | 22       | 0.6%    |
| DRAM    | 6        | 0.16%   |
| LPDDR3  | 1        | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| DIMM            | 3342     | 92.04%  |
| SODIMM          | 264      | 7.27%   |
| RIMM            | 9        | 0.25%   |
| FB-DIMM         | 9        | 0.25%   |
| Row Of Chips    | 5        | 0.14%   |
| Proprietary Car | 1        | 0.03%   |
| Chip            | 1        | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 1564     | 39.46%  |
| 4096  | 890      | 22.45%  |
| 16384 | 648      | 16.35%  |
| 2048  | 523      | 13.19%  |
| 32768 | 163      | 4.11%   |
| 1024  | 152      | 3.83%   |
| 512   | 21       | 0.53%   |
| 65536 | 1        | 0.03%   |
| 256   | 1        | 0.03%   |
| 16    | 1        | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 731      | 18.12%  |
| 1333    | 509      | 12.62%  |
| 3200    | 436      | 10.81%  |
| 3600    | 269      | 6.67%   |
| 2400    | 253      | 6.27%   |
| 2667    | 222      | 5.5%    |
| 2133    | 212      | 5.26%   |
| 800     | 161      | 3.99%   |
| 667     | 104      | 2.58%   |
| Unknown | 73       | 1.81%   |
| 1866    | 71       | 1.76%   |
| 1800    | 66       | 1.64%   |
| 3000    | 65       | 1.61%   |
| 2666    | 62       | 1.54%   |
| 3400    | 58       | 1.44%   |
| 1867    | 58       | 1.44%   |
| 3866    | 57       | 1.41%   |
| 2933    | 50       | 1.24%   |
| 3733    | 48       | 1.19%   |
| 1066    | 41       | 1.02%   |
| 3800    | 40       | 0.99%   |
| 400     | 34       | 0.84%   |
| 3266    | 33       | 0.82%   |
| 3533    | 27       | 0.67%   |
| 2800    | 20       | 0.5%    |
| 1334    | 20       | 0.5%    |
| 3666    | 19       | 0.47%   |
| 3500    | 18       | 0.45%   |
| 4000    | 17       | 0.42%   |
| 1067    | 17       | 0.42%   |
| 4800    | 16       | 0.4%    |
| 3466    | 16       | 0.4%    |
| 3534    | 13       | 0.32%   |
| 533     | 13       | 0.32%   |
| 3100    | 12       | 0.3%    |
| 2048    | 12       | 0.3%    |
| 2000    | 12       | 0.3%    |
| 3066    | 11       | 0.27%   |
| 333     | 10       | 0.25%   |
| 2465    | 9        | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 155      | 28.65%  |
| Brother Industries       | 112      | 20.7%   |
| Canon                    | 95       | 17.56%  |
| Samsung Electronics      | 67       | 12.38%  |
| Seiko Epson              | 38       | 7.02%   |
| Kyocera                  | 13       | 2.4%    |
| Dymo-CoStar              | 13       | 2.4%    |
| Prolific Technology      | 12       | 2.22%   |
| QinHeng Electronics      | 10       | 1.85%   |
| Lexmark International    | 10       | 1.85%   |
| Xerox                    | 3        | 0.55%   |
| Ricoh                    | 3        | 0.55%   |
| Dell                     | 3        | 0.55%   |
| Magic Control Technology | 2        | 0.37%   |
| Seiko Instruments        | 1        | 0.18%   |
| Oki Data                 | 1        | 0.18%   |
| ATEN International       | 1        | 0.18%   |
| Agere Systems (Lucent)   | 1        | 0.18%   |
| Unknown                  | 1        | 0.18%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port                              | 12       | 2.2%    |
| Samsung M2020 Series                                       | 11       | 2.02%   |
| Brother HL-2030 Laser Printer                              | 11       | 2.02%   |
| QinHeng CH340S                                             | 10       | 1.83%   |
| Canon LiDE 300                                             | 9        | 1.65%   |
| Canon iP7200 series                                        | 9        | 1.65%   |
| Canon LiDE 400                                             | 8        | 1.47%   |
| Samsung C48x Series                                        | 7        | 1.28%   |
| HP ENVY 4520 series                                        | 7        | 1.28%   |
| Canon PIXMA MX920 Series                                   | 6        | 1.1%    |
| Seiko Epson XP-2100 Series                                 | 5        | 0.92%   |
| Samsung SCX-472x Series                                    | 5        | 0.92%   |
| Samsung M2070 Series                                       | 5        | 0.92%   |
| HP OfficeJet 3830 series                                   | 5        | 0.92%   |
| HP DeskJet F4200 series                                    | 5        | 0.92%   |
| Canon TR8500 series                                        | 5        | 0.92%   |
| Brother MFC-L2710DW series                                 | 5        | 0.92%   |
| Seiko Epson ET-2710 Series                                 | 4        | 0.73%   |
| Samsung ML-1640 Series Laser Printer                       | 4        | 0.73%   |
| HP Officejet Pro 8100                                      | 4        | 0.73%   |
| HP OfficeJet 5200 series                                   | 4        | 0.73%   |
| HP ENVY 4500 series                                        | 4        | 0.73%   |
| HP Deskjet 3520 series                                     | 4        | 0.73%   |
| HP DeskJet 2700 series                                     | 4        | 0.73%   |
| HP DeskJet 1110 series                                     | 4        | 0.73%   |
| Dymo-CoStar LabelWriter 450                                | 4        | 0.73%   |
| Dymo-CoStar LabelWriter 400                                | 4        | 0.73%   |
| Canon PIXMA MG3600 Series                                  | 4        | 0.73%   |
| Brother HL-3142CW series                                   | 4        | 0.73%   |
| Brother DCP-7030                                           | 4        | 0.73%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F     | 3        | 0.55%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 3        | 0.55%   |
| Samsung M283x Series                                       | 3        | 0.55%   |
| Samsung C43x Series                                        | 3        | 0.55%   |
| HP OfficeJet Pro 7720 series                               | 3        | 0.55%   |
| HP OfficeJet Pro 69                                        | 3        | 0.55%   |
| HP OfficeJet 4650 series                                   | 3        | 0.55%   |
| HP Officejet 4620 series                                   | 3        | 0.55%   |
| HP Officejet 2620 series                                   | 3        | 0.55%   |
| HP DeskJet 990c                                            | 3        | 0.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Canon                  | 149      | 72.33%  |
| Seiko Epson            | 31       | 15.05%  |
| Hewlett-Packard        | 12       | 5.83%   |
| AGFA-Gevaert NV        | 7        | 3.4%    |
| Mustek Systems         | 5        | 2.43%   |
| Nikon                  | 1        | 0.49%   |
| Microtek International | 1        | 0.49%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                       | 23       | 11.17%  |
| Canon CanoScan LiDE 220                                       | 21       | 10.19%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 14       | 6.8%    |
| Canon CanoScan LIDE 25                                        | 14       | 6.8%    |
| Canon CanoScan LiDE 110                                       | 14       | 6.8%    |
| Canon CanoScan LiDE 120                                       | 10       | 4.85%   |
| Canon CanoScan LiDE 100                                       | 10       | 4.85%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]           | 8        | 3.88%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                        | 7        | 3.4%    |
| Canon CanoScan LiDE 90                                        | 5        | 2.43%   |
| Canon CanoScan LiDE 200                                       | 5        | 2.43%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 4        | 1.94%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 4        | 1.94%   |
| Canon CanoScan LiDE 60                                        | 4        | 1.94%   |
| Canon CanoScan 9000F Mark II                                  | 4        | 1.94%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 3        | 1.46%   |
| HP ScanJet 3970c                                              | 3        | 1.46%   |
| Canon CanoScan N1240U/LiDE 30                                 | 3        | 1.46%   |
| Canon CanoScan 8800F                                          | 3        | 1.46%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 3        | 1.46%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]   | 2        | 0.97%   |
| Seiko Epson GT-6600U [Perfection 610]                         | 2        | 0.97%   |
| Mustek Systems ScanExpress 1200 CU                            | 2        | 0.97%   |
| Canon CanoScan LiDE 700F                                      | 2        | 0.97%   |
| Canon CanoScan LiDE 600F                                      | 2        | 0.97%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 1        | 0.49%   |
| Seiko Epson GT-F700 [Perfection V350]                         | 1        | 0.49%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1        | 0.49%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                  | 1        | 0.49%   |
| Seiko Epson GT-9400UF [Perfection 3170]                       | 1        | 0.49%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 0.49%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1        | 0.49%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]                    | 1        | 0.49%   |
| Nikon Coolscan LS 40 ED                                       | 1        | 0.49%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                    | 1        | 0.49%   |
| Mustek Systems ScanExpress A3 USB                             | 1        | 0.49%   |
| Mustek Systems ScanExpress 1200 CU Plus                       | 1        | 0.49%   |
| Microtek International USB1200 Scanner                        | 1        | 0.49%   |
| HP ScanJet Pro 2500 f1                                        | 1        | 0.49%   |
| HP ScanJet G3010                                              | 1        | 0.49%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 549      | 40.67%  |
| Microdia                      | 127      | 9.41%   |
| Microsoft                     | 125      | 9.26%   |
| Samsung Electronics           | 48       | 3.56%   |
| Sunplus Innovation Technology | 46       | 3.41%   |
| Creative Technology           | 39       | 2.89%   |
| Generalplus Technology        | 32       | 2.37%   |
| ARC International             | 31       | 2.3%    |
| Realtek Semiconductor         | 27       | 2%      |
| Apple                         | 20       | 1.48%   |
| Chicony Electronics           | 19       | 1.41%   |
| Cubeternet                    | 18       | 1.33%   |
| Trust                         | 17       | 1.26%   |
| MacroSilicon                  | 15       | 1.11%   |
| Jieli Technology              | 15       | 1.11%   |
| Z-Star Microelectronics       | 14       | 1.04%   |
| GEMBIRD                       | 13       | 0.96%   |
| webcam                        | 10       | 0.74%   |
| Valve Software                | 9        | 0.67%   |
| Sonix Technology              | 9        | 0.67%   |
| IMC Networks                  | 9        | 0.67%   |
| Philips (or NXP)              | 8        | 0.59%   |
| Sunplus IT                    | 7        | 0.52%   |
| Razer USA                     | 7        | 0.52%   |
| Huawei Technologies           | 7        | 0.52%   |
| Genesys Logic                 | 7        | 0.52%   |
| Tobii Technology AB           | 6        | 0.44%   |
| KYE Systems (Mouse Systems)   | 6        | 0.44%   |
| Arkmicro Technologies         | 6        | 0.44%   |
| Guillemot                     | 5        | 0.37%   |
| Alcor Micro                   | 5        | 0.37%   |
| WaveRider Communications      | 4        | 0.3%    |
| Sony                          | 4        | 0.3%    |
| Aveo Technology               | 4        | 0.3%    |
| Xiaomi                        | 3        | 0.22%   |
| Unknown                       | 3        | 0.22%   |
| SHENZHEN EMEET TECHNOLOGY     | 3        | 0.22%   |
| MediaTek                      | 3        | 0.22%   |
| Linux Foundation              | 3        | 0.22%   |
| LG Electronics                | 3        | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 123      | 9.05%   |
| Logitech HD Pro Webcam C920                       | 88       | 6.48%   |
| Microsoft LifeCam HD-3000                         | 56       | 4.12%   |
| Samsung Galaxy series, misc. (MTP mode)           | 47       | 3.46%   |
| Logitech HD Webcam C525                           | 42       | 3.09%   |
| Logitech Webcam C310                              | 33       | 2.43%   |
| Logitech C922 Pro Stream Webcam                   | 32       | 2.35%   |
| ARC International Camera                          | 29       | 2.13%   |
| Microdia Webcam Vitade AF                         | 26       | 1.91%   |
| Generalplus GENERAL WEBCAM                        | 23       | 1.69%   |
| Microdia Sonix USB 2.0 Camera                     | 22       | 1.62%   |
| Microdia USB 2.0 Camera                           | 20       | 1.47%   |
| Microdia Camera                                   | 20       | 1.47%   |
| Logitech HD Webcam C510                           | 18       | 1.32%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 18       | 1.32%   |
| Sunplus FHD Camera Microphone                     | 17       | 1.25%   |
| Microdia CameraA                                  | 16       | 1.18%   |
| Logitech Webcam C170                              | 16       | 1.18%   |
| Logitech HD Webcam C910                           | 16       | 1.18%   |
| Logitech Webcam C930e                             | 15       | 1.1%    |
| Jieli USB PHY 2.0                                 | 15       | 1.1%    |
| MacroSilicon usb video                            | 14       | 1.03%   |
| Creative Live! Cam Sync HD [VF0770]               | 14       | 1.03%   |
| Logitech Webcam Pro 9000                          | 13       | 0.96%   |
| Logitech StreamCam                                | 13       | 0.96%   |
| Microsoft LifeCam Cinema                          | 12       | 0.88%   |
| Realtek FULL HD 1080P Webcam                      | 11       | 0.81%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]        | 11       | 0.81%   |
| webcam webcam                                     | 10       | 0.74%   |
| Logitech Webcam C250                              | 10       | 0.74%   |
| Logitech Webcam B500                              | 10       | 0.74%   |
| Logitech QuickCam Pro 9000                        | 10       | 0.74%   |
| Logitech BRIO Ultra HD Webcam                     | 10       | 0.74%   |
| Valve Software 3D Camera                          | 9        | 0.66%   |
| Microsoft LifeCam HD-5000                         | 9        | 0.66%   |
| Logitech QuickCam E 3500                          | 9        | 0.66%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 9        | 0.66%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 9        | 0.66%   |
| Sunplus HD 720P webcam                            | 8        | 0.59%   |
| Microsoft MicrosoftÂ LifeCam Studio              | 8        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Elan Microelectronics      | 8        | 38.1%   |
| AuthenTec                  | 5        | 23.81%  |
| STMicroelectronics         | 2        | 9.52%   |
| Validity Sensors           | 1        | 4.76%   |
| Upek                       | 1        | 4.76%   |
| Synaptics                  | 1        | 4.76%   |
| Shenzhen Goodix Technology | 1        | 4.76%   |
| LighTuning Technology      | 1        | 4.76%   |
| DigitalPersona             | 1        | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]            | 8        | 38.1%   |
| STMicroelectronics Fingerprint Reader                  | 2        | 9.52%   |
| AuthenTec Fingerprint Sensor                           | 2        | 9.52%   |
| AuthenTec AES1600                                      | 2        | 9.52%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1        | 4.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 4.76%   |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1        | 4.76%   |
| Shenzhen Goodix  Fingerprint Device                    | 1        | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1        | 4.76%   |
| DigitalPersona Fingerprint Reader                      | 1        | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1        | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Reiner SCT Kartensysteme  | 22       | 31.88%  |
| Cherry                    | 7        | 10.14%  |
| Clay Logic                | 6        | 8.7%    |
| Alcor Micro               | 6        | 8.7%    |
| SCM Microsystems          | 4        | 5.8%    |
| OmniKey                   | 4        | 5.8%    |
| Fujitsu Siemens Computers | 4        | 5.8%    |
| Advanced Card Systems     | 4        | 5.8%    |
| Kobil Systems             | 3        | 4.35%   |
| Yubico.com                | 2        | 2.9%    |
| Gemalto (was Gemplus)     | 2        | 2.9%    |
| Realtek Semiconductor     | 1        | 1.45%   |
| Lenovo                    | 1        | 1.45%   |
| In Focus Systems          | 1        | 1.45%   |
| Chicony Electronics       | 1        | 1.45%   |
| Aladdin Knowledge Systems | 1        | 1.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 10       | 14.49%  |
| Reiner SCT Kartensysteme cyberJack one                                     | 7        | 10.14%  |
| Clay Logic Nitrokey Pro                                                    | 6        | 8.7%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 5        | 7.25%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 4        | 5.8%    |
| SCM Microsystems SCR335 SmartCard Reader                                   | 3        | 4.35%   |
| Reiner SCT Kartensysteme tanJack USB                                       | 3        | 4.35%   |
| OmniKey CardMan 3021 / 3121                                                | 3        | 4.35%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 2        | 2.9%    |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                            | 2        | 2.9%    |
| Kobil Systems KOBIL Class 3 Reader                                         | 2        | 2.9%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 2        | 2.9%    |
| Alcor Micro Watchdata W 1981                                               | 2        | 2.9%    |
| Advanced Card Systems ACR38 SmartCard Reader                               | 2        | 2.9%    |
| Advanced Card Systems ACR122U                                              | 2        | 2.9%    |
| SCM Microsystems SCR331 SmartCard Reader                                   | 1        | 1.45%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 1        | 1.45%   |
| OmniKey CardMan 3121 (HID Technologies)                                    | 1        | 1.45%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 1.45%   |
| Kobil Systems Smart Token                                                  | 1        | 1.45%   |
| In Focus Systems EMV Smartcard Reader                                      | 1        | 1.45%   |
| Fujitsu Siemens Computers Smartcard Reader D323                            | 1        | 1.45%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 1.45%   |
| Fujitsu Siemens Computers Keyboard KB100 SCR eSIG                          | 1        | 1.45%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                  | 1        | 1.45%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 1        | 1.45%   |
| Cherry SmartTerminal XX44                                                  | 1        | 1.45%   |
| Cherry Smart Card Reader USB                                               | 1        | 1.45%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 1.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 6416     | 83.94%  |
| 1     | 993      | 12.99%  |
| 2     | 168      | 2.2%    |
| 3     | 38       | 0.5%    |
| 4     | 13       | 0.17%   |
| 5     | 12       | 0.16%   |
| 8     | 2        | 0.03%   |
| 7     | 1        | 0.01%   |
| 6     | 1        | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 501      | 34.2%   |
| Net/wireless             | 291      | 19.86%  |
| Communication controller | 156      | 10.65%  |
| Unassigned class         | 98       | 6.69%   |
| Sound                    | 75       | 5.12%   |
| Multimedia controller    | 73       | 4.98%   |
| Card reader              | 56       | 3.82%   |
| Chipcard                 | 44       | 3%      |
| Camera                   | 29       | 1.98%   |
| Bluetooth                | 28       | 1.91%   |
| Fingerprint reader       | 20       | 1.37%   |
| Net/ethernet             | 19       | 1.3%    |
| Network                  | 18       | 1.23%   |
| Storage/raid             | 15       | 1.02%   |
| Storage/ide              | 13       | 0.89%   |
| Dvb card                 | 6        | 0.41%   |
| Modem                    | 5        | 0.34%   |
| Tv card                  | 4        | 0.27%   |
| Firewire controller      | 4        | 0.27%   |
| Storage/nvme             | 3        | 0.2%    |
| Storage                  | 3        | 0.2%    |
| Unclassified device      | 2        | 0.14%   |
| Video                    | 1        | 0.07%   |
| Storage/ata              | 1        | 0.07%   |

