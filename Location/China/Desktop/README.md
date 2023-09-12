Linux in China - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in China.

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

Total: 634

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0NDYHG A01                  | [250bc7b8ea](https://linux-hardware.org/?probe=250bc7b8ea) | Sep 07, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | [48e1f16931](https://linux-hardware.org/?probe=48e1f16931) | Sep 05, 2023 |
| Unknown       | Unknown                     | [0c53c2df55](https://linux-hardware.org/?probe=0c53c2df55) | Sep 04, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | [a99a5ccc55](https://linux-hardware.org/?probe=a99a5ccc55) | Aug 30, 2023 |
| TSINGHUA T... | B460M-HDV                   | [f82a030bce](https://linux-hardware.org/?probe=f82a030bce) | Aug 30, 2023 |
| ASUSTek       | PRIME X570-PRO              | [bbae205fe2](https://linux-hardware.org/?probe=bbae205fe2) | Aug 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [266edae3d0](https://linux-hardware.org/?probe=266edae3d0) | Aug 23, 2023 |
| MSI           | Z370-OC PRO                 | [4ee0bb1c63](https://linux-hardware.org/?probe=4ee0bb1c63) | Aug 23, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [236b200fd8](https://linux-hardware.org/?probe=236b200fd8) | Aug 22, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [16d770ddb1](https://linux-hardware.org/?probe=16d770ddb1) | Aug 22, 2023 |
| MSI           | Z370-OC PRO                 | [bbd85c94d6](https://linux-hardware.org/?probe=bbd85c94d6) | Aug 22, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | [cc09706b5f](https://linux-hardware.org/?probe=cc09706b5f) | Aug 19, 2023 |
| AZW           | EQ                          | [6fda99ad46](https://linux-hardware.org/?probe=6fda99ad46) | Aug 18, 2023 |
| CWWK          | N3050 P1                    | [dd3dfb0c02](https://linux-hardware.org/?probe=dd3dfb0c02) | Aug 17, 2023 |
| Shenzhen M... | F7BSC                       | [bfe3223b92](https://linux-hardware.org/?probe=bfe3223b92) | Aug 17, 2023 |
| TSINGHUA T... | B460M-HDV                   | [815cb59889](https://linux-hardware.org/?probe=815cb59889) | Aug 16, 2023 |
| TSINGHUA T... | B460-N2                     | [f7f87f7a07](https://linux-hardware.org/?probe=f7f87f7a07) | Aug 16, 2023 |
| Dell          | 0GNVHC A00                  | [27e3be4942](https://linux-hardware.org/?probe=27e3be4942) | Aug 12, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [dad31fab00](https://linux-hardware.org/?probe=dad31fab00) | Aug 12, 2023 |
| YANYU         | EPIC-C57                    | [6d42c0f9af](https://linux-hardware.org/?probe=6d42c0f9af) | Aug 10, 2023 |
| GMKtec        | NucBox K4                   | [64b27a1390](https://linux-hardware.org/?probe=64b27a1390) | Aug 05, 2023 |
| Gigabyte      | H510M H                     | [d74aab937a](https://linux-hardware.org/?probe=d74aab937a) | Aug 02, 2023 |
| MSI           | Z97S SLI Krait Edition      | [136d063ffc](https://linux-hardware.org/?probe=136d063ffc) | Jul 23, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [ef3c6c941e](https://linux-hardware.org/?probe=ef3c6c941e) | Jul 18, 2023 |
| ONDA          | A320SD4-ITX Ver:2.00        | [ffe435deca](https://linux-hardware.org/?probe=ffe435deca) | Jul 18, 2023 |
| ASRock        | X470 Gaming K4              | [7217058966](https://linux-hardware.org/?probe=7217058966) | Jul 18, 2023 |
| MSI           | MAG Z690 TORPEDO            | [8f4a9f7202](https://linux-hardware.org/?probe=8f4a9f7202) | Jul 16, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [538375bd43](https://linux-hardware.org/?probe=538375bd43) | Jul 14, 2023 |
| Unknown       | Unknown                     | [beea313884](https://linux-hardware.org/?probe=beea313884) | Jul 13, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [3924343595](https://linux-hardware.org/?probe=3924343595) | Jul 10, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | [97348ef480](https://linux-hardware.org/?probe=97348ef480) | Jul 10, 2023 |
| WeiBu         | ADL-N Prod                  | [23746411d7](https://linux-hardware.org/?probe=23746411d7) | Jul 10, 2023 |
| Supermicro    | X9DAi                       | [952f122742](https://linux-hardware.org/?probe=952f122742) | Jul 07, 2023 |
| HP            | 8860 A                      | [5bc7810c4b](https://linux-hardware.org/?probe=5bc7810c4b) | Jul 06, 2023 |
| Lenovo        | ThinkCentre M6300T          | [d70e22a967](https://linux-hardware.org/?probe=d70e22a967) | Jul 05, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | [10aeee3539](https://linux-hardware.org/?probe=10aeee3539) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d6cb722f64](https://linux-hardware.org/?probe=d6cb722f64) | Jun 29, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | [7baa260d16](https://linux-hardware.org/?probe=7baa260d16) | Jun 29, 2023 |
| ASUSTek       | EX-B250M-V3                 | [0746c8e92b](https://linux-hardware.org/?probe=0746c8e92b) | Jun 27, 2023 |
| Gigabyte      | B450M GAMING                | [bc4e778aa5](https://linux-hardware.org/?probe=bc4e778aa5) | Jun 26, 2023 |
| MSI           | B660M BOMBER DDR4           | [bebc7de8d4](https://linux-hardware.org/?probe=bebc7de8d4) | Jun 17, 2023 |
| MSI           | B660M BOMBER DDR4           | [0a02c36bd6](https://linux-hardware.org/?probe=0a02c36bd6) | Jun 17, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [53a0b2f173](https://linux-hardware.org/?probe=53a0b2f173) | Jun 15, 2023 |
| Win elemen... | M600                        | [360ab80d9b](https://linux-hardware.org/?probe=360ab80d9b) | Jun 06, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [6640281a3b](https://linux-hardware.org/?probe=6640281a3b) | Jun 06, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [f06cb8954c](https://linux-hardware.org/?probe=f06cb8954c) | Jun 06, 2023 |
| HP            | 8768 A                      | [17d0560a85](https://linux-hardware.org/?probe=17d0560a85) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [54e2e07ac6](https://linux-hardware.org/?probe=54e2e07ac6) | Jun 05, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [4ba1a29c23](https://linux-hardware.org/?probe=4ba1a29c23) | Jun 05, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [f88c53fd11](https://linux-hardware.org/?probe=f88c53fd11) | Jun 04, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [c142ea01cd](https://linux-hardware.org/?probe=c142ea01cd) | Jun 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [0523005c68](https://linux-hardware.org/?probe=0523005c68) | Jun 03, 2023 |
| ChangWang     | CW56-58                     | [e00e626ea6](https://linux-hardware.org/?probe=e00e626ea6) | Jun 01, 2023 |
| ONDA          | M3 miniPC VER               | [1a6a6ab3e6](https://linux-hardware.org/?probe=1a6a6ab3e6) | May 27, 2023 |
| ONDA          | M3 miniPC VER               | [c4c78fe843](https://linux-hardware.org/?probe=c4c78fe843) | May 24, 2023 |
| Dell          | 0J1C3P A00                  | [5f3d8a94e6](https://linux-hardware.org/?probe=5f3d8a94e6) | May 22, 2023 |
| Dell          | 0FDY5C A00                  | [3d9b02954b](https://linux-hardware.org/?probe=3d9b02954b) | May 16, 2023 |
| MSI           | MAG B560M MORTAR            | [2323128fd2](https://linux-hardware.org/?probe=2323128fd2) | May 16, 2023 |
| Koloe         | X58                         | [7c1acc3b84](https://linux-hardware.org/?probe=7c1acc3b84) | May 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [850ea7c843](https://linux-hardware.org/?probe=850ea7c843) | May 06, 2023 |
| MSI           | Z97S SLI Krait Edition      | [eb289c3d5f](https://linux-hardware.org/?probe=eb289c3d5f) | May 06, 2023 |
| Huanan        | B75                         | [597233d5d2](https://linux-hardware.org/?probe=597233d5d2) | May 02, 2023 |
| Huanan        | B75                         | [1f988e5101](https://linux-hardware.org/?probe=1f988e5101) | May 02, 2023 |
| MAXSUN        | MS-A86FX FS M.3             | [3ce20d3b05](https://linux-hardware.org/?probe=3ce20d3b05) | May 01, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [b37927b9d4](https://linux-hardware.org/?probe=b37927b9d4) | May 01, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [a188684584](https://linux-hardware.org/?probe=a188684584) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [233ea7cdd8](https://linux-hardware.org/?probe=233ea7cdd8) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [177fe2fc00](https://linux-hardware.org/?probe=177fe2fc00) | Apr 30, 2023 |
| HEDYCOMPUT... | IH81MF-Q3                   | [3444236ed4](https://linux-hardware.org/?probe=3444236ed4) | Apr 30, 2023 |
| Gigabyte      | H77-DS3H                    | [6750e5f83d](https://linux-hardware.org/?probe=6750e5f83d) | Apr 30, 2023 |
| Colorful T... | CVN Z590 GAMING PRO V20     | [209ec5e477](https://linux-hardware.org/?probe=209ec5e477) | Apr 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [429d6f994a](https://linux-hardware.org/?probe=429d6f994a) | Apr 28, 2023 |
| Lenovo        | SHARKBAY NO DPK             | [9a22f330c4](https://linux-hardware.org/?probe=9a22f330c4) | Apr 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [97a3b73c44](https://linux-hardware.org/?probe=97a3b73c44) | Apr 27, 2023 |
| Unknown       | Unknown                     | [c5824f9cae](https://linux-hardware.org/?probe=c5824f9cae) | Apr 25, 2023 |
| Lenovo        | 1036 NO DPK                 | [f5b9a50e56](https://linux-hardware.org/?probe=f5b9a50e56) | Apr 23, 2023 |
| Lenovo        | 1036 NO DPK                 | [edcf4e959d](https://linux-hardware.org/?probe=edcf4e959d) | Apr 23, 2023 |
| Lenovo        | 1036 NO DPK                 | [d1ca2bb309](https://linux-hardware.org/?probe=d1ca2bb309) | Apr 23, 2023 |
| ASRock        | Z170 Gaming K4              | [8209f53171](https://linux-hardware.org/?probe=8209f53171) | Apr 22, 2023 |
| Dell          | 0FDY5C A00                  | [ddf678b11a](https://linux-hardware.org/?probe=ddf678b11a) | Apr 20, 2023 |
| UGREEN        | DX4600                      | [cbe70de89c](https://linux-hardware.org/?probe=cbe70de89c) | Apr 19, 2023 |
| Unknown       | Unknown                     | [d45af08c99](https://linux-hardware.org/?probe=d45af08c99) | Apr 14, 2023 |
| Unknown       | Unknown                     | [6925c48705](https://linux-hardware.org/?probe=6925c48705) | Apr 14, 2023 |
| Unknown       | Unknown                     | [158dacc1ce](https://linux-hardware.org/?probe=158dacc1ce) | Apr 13, 2023 |
| Unknown       | Unknown                     | [52aeca6f98](https://linux-hardware.org/?probe=52aeca6f98) | Apr 13, 2023 |
| ASRock        | B150 Combo                  | [c4acc08020](https://linux-hardware.org/?probe=c4acc08020) | Apr 09, 2023 |
| ASUSTek       | A68HM-E                     | [0c9ae9bcd7](https://linux-hardware.org/?probe=0c9ae9bcd7) | Apr 06, 2023 |
| HP            | 1790                        | [55e3d423e0](https://linux-hardware.org/?probe=55e3d423e0) | Apr 05, 2023 |
| Unknown       | Unknown                     | [cdd67e12ca](https://linux-hardware.org/?probe=cdd67e12ca) | Apr 03, 2023 |
| Lenovo        | SHARKBAY NOK                | [091d2eda88](https://linux-hardware.org/?probe=091d2eda88) | Apr 01, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [a33a768662](https://linux-hardware.org/?probe=a33a768662) | Mar 29, 2023 |
| Dell          | 0R5KF8 A03                  | [decf0f5193](https://linux-hardware.org/?probe=decf0f5193) | Mar 28, 2023 |
| Unknown       | FT2000plus Generic Borad... | [43ec5396f3](https://linux-hardware.org/?probe=43ec5396f3) | Mar 28, 2023 |
| Unknown       | FT2000plus Generic Borad... | [c305aa7562](https://linux-hardware.org/?probe=c305aa7562) | Mar 28, 2023 |
| ASRock        | A320M-HDV                   | [9685e81600](https://linux-hardware.org/?probe=9685e81600) | Mar 27, 2023 |
| ASUSTek       | Z97-K R2.0                  | [b1e1f4d711](https://linux-hardware.org/?probe=b1e1f4d711) | Mar 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4731c6e59f](https://linux-hardware.org/?probe=4731c6e59f) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [127173d60b](https://linux-hardware.org/?probe=127173d60b) | Mar 23, 2023 |
| Dell          | 0NDYHG A00                  | [f007ab3692](https://linux-hardware.org/?probe=f007ab3692) | Mar 20, 2023 |
| Lenovo        | 1036 NO DPK                 | [3b6514e9c4](https://linux-hardware.org/?probe=3b6514e9c4) | Mar 16, 2023 |
| Unknown       | Unknown                     | [0eb13c3117](https://linux-hardware.org/?probe=0eb13c3117) | Mar 15, 2023 |
| Unknown       | Unknown                     | [6e24f7a3c1](https://linux-hardware.org/?probe=6e24f7a3c1) | Mar 15, 2023 |
| Lenovo        | 313A SDK0L77767 WIN 3423... | [869582f7a7](https://linux-hardware.org/?probe=869582f7a7) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [a5a874dac0](https://linux-hardware.org/?probe=a5a874dac0) | Mar 10, 2023 |
| AZW           | GTR V02                     | [06b17c5206](https://linux-hardware.org/?probe=06b17c5206) | Mar 09, 2023 |
| Lenovo        | 313A SDK0L77767 WIN 3423... | [828ae3c8fd](https://linux-hardware.org/?probe=828ae3c8fd) | Mar 07, 2023 |
| Gigabyte      | Z690 UD DDR4 V2             | [fa84567d3f](https://linux-hardware.org/?probe=fa84567d3f) | Mar 06, 2023 |
| Gigabyte      | Z690 UD DDR4 V2             | [b58f671799](https://linux-hardware.org/?probe=b58f671799) | Mar 06, 2023 |
| Unknown       | Unknown                     | [89822406cc](https://linux-hardware.org/?probe=89822406cc) | Feb 28, 2023 |
| ASUSTek       | H87-PLUS                    | [f56bb767fd](https://linux-hardware.org/?probe=f56bb767fd) | Feb 26, 2023 |
| ASUSTek       | H87-PLUS                    | [98e70b4028](https://linux-hardware.org/?probe=98e70b4028) | Feb 26, 2023 |
| Unknown       | Unknown                     | [65a35ffeea](https://linux-hardware.org/?probe=65a35ffeea) | Feb 24, 2023 |
| Unknown       | Unknown                     | [3d8e9cb31b](https://linux-hardware.org/?probe=3d8e9cb31b) | Feb 24, 2023 |
| Dell          | 0CNWVK A02                  | [1fd825c3df](https://linux-hardware.org/?probe=1fd825c3df) | Feb 24, 2023 |
| Dell          | 0V7K5Y A00                  | [831a493e15](https://linux-hardware.org/?probe=831a493e15) | Feb 24, 2023 |
| ASUSTek       | X99-M WS                    | [69eb540783](https://linux-hardware.org/?probe=69eb540783) | Feb 20, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | [cd5fcc7d4c](https://linux-hardware.org/?probe=cd5fcc7d4c) | Feb 17, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | [8ef4a011f7](https://linux-hardware.org/?probe=8ef4a011f7) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [5160909d57](https://linux-hardware.org/?probe=5160909d57) | Feb 17, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [2c3699dc3c](https://linux-hardware.org/?probe=2c3699dc3c) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [21ef26978d](https://linux-hardware.org/?probe=21ef26978d) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [ba50ff27b1](https://linux-hardware.org/?probe=ba50ff27b1) | Feb 17, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | [ad9381188b](https://linux-hardware.org/?probe=ad9381188b) | Feb 17, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [96e79838f4](https://linux-hardware.org/?probe=96e79838f4) | Feb 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [ddafe146cc](https://linux-hardware.org/?probe=ddafe146cc) | Feb 17, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | [386273f2fc](https://linux-hardware.org/?probe=386273f2fc) | Feb 17, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | [1a9e50653b](https://linux-hardware.org/?probe=1a9e50653b) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [d97f8e5a87](https://linux-hardware.org/?probe=d97f8e5a87) | Feb 17, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [a8816819e2](https://linux-hardware.org/?probe=a8816819e2) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [38223114be](https://linux-hardware.org/?probe=38223114be) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [afe7d688f2](https://linux-hardware.org/?probe=afe7d688f2) | Feb 17, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [cbc7919c26](https://linux-hardware.org/?probe=cbc7919c26) | Feb 17, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | [4a97ea8e7a](https://linux-hardware.org/?probe=4a97ea8e7a) | Feb 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [976a71dfac](https://linux-hardware.org/?probe=976a71dfac) | Feb 17, 2023 |
| MSI           | A520M-A PRO                 | [fd678baa9f](https://linux-hardware.org/?probe=fd678baa9f) | Feb 16, 2023 |
| Unknown       | Unknown                     | [fe12f077df](https://linux-hardware.org/?probe=fe12f077df) | Feb 15, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | [63a1a75985](https://linux-hardware.org/?probe=63a1a75985) | Feb 14, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | [b1d0b59ec2](https://linux-hardware.org/?probe=b1d0b59ec2) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [7c15b6acdf](https://linux-hardware.org/?probe=7c15b6acdf) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [9e6adb8535](https://linux-hardware.org/?probe=9e6adb8535) | Feb 14, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | [df0ce521b3](https://linux-hardware.org/?probe=df0ce521b3) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [f427323448](https://linux-hardware.org/?probe=f427323448) | Feb 14, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [c62c075365](https://linux-hardware.org/?probe=c62c075365) | Feb 14, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [2bde59c923](https://linux-hardware.org/?probe=2bde59c923) | Feb 14, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [745ac39390](https://linux-hardware.org/?probe=745ac39390) | Feb 14, 2023 |
| Dell          | 0Y7WYT A00                  | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| Unknown       | Unknown                     | [c49317ce12](https://linux-hardware.org/?probe=c49317ce12) | Feb 13, 2023 |
| Unknown       | Unknown                     | [b1d1f36f51](https://linux-hardware.org/?probe=b1d1f36f51) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [1423d5ac1b](https://linux-hardware.org/?probe=1423d5ac1b) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [bb589c5e58](https://linux-hardware.org/?probe=bb589c5e58) | Feb 10, 2023 |
| Loongson      | LS3A5000-7A1000-1w-EVB-V... | [cbf5d56cfc](https://linux-hardware.org/?probe=cbf5d56cfc) | Feb 09, 2023 |
| Lenovo        | 3328 SDK0T76479 WIN 3423... | [8667299d04](https://linux-hardware.org/?probe=8667299d04) | Feb 04, 2023 |
| Lenovo        | 3328 SDK0T76479 WIN 3423... | [7862a9afc7](https://linux-hardware.org/?probe=7862a9afc7) | Feb 04, 2023 |
| Lenovo        | 3148 NOK                    | [72815c2ab8](https://linux-hardware.org/?probe=72815c2ab8) | Jan 30, 2023 |
| OEM           | KX-01 V1.0                  | [75d9dc396c](https://linux-hardware.org/?probe=75d9dc396c) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [510b879339](https://linux-hardware.org/?probe=510b879339) | Jan 26, 2023 |
| ASUSTek       | A88XM-PLUS                  | [68fcb008b1](https://linux-hardware.org/?probe=68fcb008b1) | Jan 15, 2023 |
| ASUSTek       | PRIME Z790-P                | [a4fb531cc9](https://linux-hardware.org/?probe=a4fb531cc9) | Jan 13, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [eab87def73](https://linux-hardware.org/?probe=eab87def73) | Jan 12, 2023 |
| ASUSTek       | A88XM-PLUS                  | [a595895c7e](https://linux-hardware.org/?probe=a595895c7e) | Jan 11, 2023 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [56544d809f](https://linux-hardware.org/?probe=56544d809f) | Jan 11, 2023 |
| AZW           | EQ59                        | [3eb85d9ee5](https://linux-hardware.org/?probe=3eb85d9ee5) | Jan 10, 2023 |
| Intel         | JSL MRD                     | [f567ba0a06](https://linux-hardware.org/?probe=f567ba0a06) | Dec 24, 2022 |
| MSI           | H510M BOMBER                | [bb7a4c8457](https://linux-hardware.org/?probe=bb7a4c8457) | Dec 23, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [37de981132](https://linux-hardware.org/?probe=37de981132) | Dec 21, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [b270e219ba](https://linux-hardware.org/?probe=b270e219ba) | Dec 20, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [525bdfe9c0](https://linux-hardware.org/?probe=525bdfe9c0) | Dec 20, 2022 |
| Dell          | 0J1C3P A00                  | [1bd9b328b2](https://linux-hardware.org/?probe=1bd9b328b2) | Dec 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d872d58e4c](https://linux-hardware.org/?probe=d872d58e4c) | Dec 15, 2022 |
| ASUSTek       | Z10PH-D16 Series            | [18911cf243](https://linux-hardware.org/?probe=18911cf243) | Dec 13, 2022 |
| Dell          | 0NK5PH A00                  | [08b0ff8839](https://linux-hardware.org/?probe=08b0ff8839) | Dec 12, 2022 |
| Gigabyte      | X299 UD4 Pro-CF             | [89da872b13](https://linux-hardware.org/?probe=89da872b13) | Dec 12, 2022 |
| Huanan        | X99-T8D V1.0                | [e4bd42a26b](https://linux-hardware.org/?probe=e4bd42a26b) | Dec 09, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [b0bf36f700](https://linux-hardware.org/?probe=b0bf36f700) | Dec 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [f5a5a30379](https://linux-hardware.org/?probe=f5a5a30379) | Dec 01, 2022 |
| ONDA          | M3 miniPC VER               | [35f4c45eb5](https://linux-hardware.org/?probe=35f4c45eb5) | Dec 01, 2022 |
| Pegatron      | BYT-X1                      | [edadb85201](https://linux-hardware.org/?probe=edadb85201) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | [b248df8671](https://linux-hardware.org/?probe=b248df8671) | Nov 30, 2022 |
| ASRock        | B450M Pro4-F                | [8d0514a0df](https://linux-hardware.org/?probe=8d0514a0df) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [f168cc5b93](https://linux-hardware.org/?probe=f168cc5b93) | Nov 27, 2022 |
| Gigabyte      | X299 UD4 Pro-CF             | [4ef7a46399](https://linux-hardware.org/?probe=4ef7a46399) | Nov 25, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [d742abf044](https://linux-hardware.org/?probe=d742abf044) | Nov 23, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [cac488b207](https://linux-hardware.org/?probe=cac488b207) | Nov 21, 2022 |
| GuoGuang      | IC2M1028N-3                 | [32351ceb62](https://linux-hardware.org/?probe=32351ceb62) | Nov 16, 2022 |
| HP            | 212B                        | [e1c7e7693e](https://linux-hardware.org/?probe=e1c7e7693e) | Nov 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | [a3c41dcc96](https://linux-hardware.org/?probe=a3c41dcc96) | Nov 16, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [340f38c8e2](https://linux-hardware.org/?probe=340f38c8e2) | Nov 15, 2022 |
| Lenovo        | 3716 SDK0K17763 WIN 1801... | [93c2091f01](https://linux-hardware.org/?probe=93c2091f01) | Nov 15, 2022 |
| Dell          | 0CNWVK A02                  | [726074bce6](https://linux-hardware.org/?probe=726074bce6) | Nov 09, 2022 |
| Dell          | 0CNWVK A02                  | [3ac38eb9be](https://linux-hardware.org/?probe=3ac38eb9be) | Nov 09, 2022 |
| Unknown       | Unknown                     | [ff3d968ae9](https://linux-hardware.org/?probe=ff3d968ae9) | Nov 08, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [0fa75a005b](https://linux-hardware.org/?probe=0fa75a005b) | Nov 08, 2022 |
| ASUSTek       | Maximus VII HERO            | [010836bb97](https://linux-hardware.org/?probe=010836bb97) | Nov 07, 2022 |
| IBM           | M97IP SIT                   | [78703d62ae](https://linux-hardware.org/?probe=78703d62ae) | Nov 07, 2022 |
| ONDA          | M3 miniPC VER               | [d485a7def3](https://linux-hardware.org/?probe=d485a7def3) | Nov 07, 2022 |
| IBM           | M97IP SIT                   | [0301b99674](https://linux-hardware.org/?probe=0301b99674) | Nov 07, 2022 |
| MSI           | 880GMS-E41                  | [2f53fa13ed](https://linux-hardware.org/?probe=2f53fa13ed) | Nov 06, 2022 |
| Unknown       | Unknown                     | [aa1a843244](https://linux-hardware.org/?probe=aa1a843244) | Nov 04, 2022 |
| Unknown       | Unknown                     | [0a55753066](https://linux-hardware.org/?probe=0a55753066) | Nov 04, 2022 |
| Unknown       | Unknown                     | [0e60d35498](https://linux-hardware.org/?probe=0e60d35498) | Nov 04, 2022 |
| Intel         | ChiefRiver                  | [1e1f44f251](https://linux-hardware.org/?probe=1e1f44f251) | Nov 04, 2022 |
| Dell          | 0CNWVK A02                  | [9017e31507](https://linux-hardware.org/?probe=9017e31507) | Nov 04, 2022 |
| Intel         | ChiefRiver                  | [64e4630da2](https://linux-hardware.org/?probe=64e4630da2) | Nov 04, 2022 |
| Dell          | 0N0992 A01                  | [6f4decf3b2](https://linux-hardware.org/?probe=6f4decf3b2) | Nov 04, 2022 |
| Unknown       | Unknown                     | [4457bb7b7e](https://linux-hardware.org/?probe=4457bb7b7e) | Nov 03, 2022 |
| Unknown       | Unknown                     | [bc4f9a5a35](https://linux-hardware.org/?probe=bc4f9a5a35) | Nov 02, 2022 |
| Unknown       | Unknown                     | [f87c0b1010](https://linux-hardware.org/?probe=f87c0b1010) | Nov 01, 2022 |
| OEM           | H310MD4                     | [947bf0d86f](https://linux-hardware.org/?probe=947bf0d86f) | Nov 01, 2022 |
| Unknown       | Unknown                     | [0e92fb8c99](https://linux-hardware.org/?probe=0e92fb8c99) | Oct 31, 2022 |
| Unknown       | Unknown                     | [673c23713c](https://linux-hardware.org/?probe=673c23713c) | Oct 30, 2022 |
| Huanan        | H510-D4 V4.0                | [89b298973c](https://linux-hardware.org/?probe=89b298973c) | Oct 30, 2022 |
| Unknown       | Unknown                     | [a517f2e2dd](https://linux-hardware.org/?probe=a517f2e2dd) | Oct 30, 2022 |
| Unknown       | Unknown                     | [03f3800569](https://linux-hardware.org/?probe=03f3800569) | Oct 29, 2022 |
| Unknown       | Unknown                     | [79b9335389](https://linux-hardware.org/?probe=79b9335389) | Oct 26, 2022 |
| Unknown       | Unknown                     | [07a0af33a1](https://linux-hardware.org/?probe=07a0af33a1) | Oct 26, 2022 |
| Unknown       | Unknown                     | [3ba090d9a2](https://linux-hardware.org/?probe=3ba090d9a2) | Oct 26, 2022 |
| Biostar       | H61MLV2                     | [5b6f2b76da](https://linux-hardware.org/?probe=5b6f2b76da) | Oct 25, 2022 |
| Dell          | 0MWYPT A02                  | [cf186994cc](https://linux-hardware.org/?probe=cf186994cc) | Oct 25, 2022 |
| MSI           | Z97S SLI Krait Edition      | [e31e22263a](https://linux-hardware.org/?probe=e31e22263a) | Oct 23, 2022 |
| NORCO         | BPC-7951                    | [7612662684](https://linux-hardware.org/?probe=7612662684) | Oct 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7afa527ad7](https://linux-hardware.org/?probe=7afa527ad7) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [547c973486](https://linux-hardware.org/?probe=547c973486) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [ca42d57a93](https://linux-hardware.org/?probe=ca42d57a93) | Oct 14, 2022 |
| AMD           | A88                         | [1ee2502537](https://linux-hardware.org/?probe=1ee2502537) | Oct 12, 2022 |
| ASUSTek       | V-P8H67E                    | [b4f0f561d2](https://linux-hardware.org/?probe=b4f0f561d2) | Oct 08, 2022 |
| OEM           | Unknown                     | [306d50f7e3](https://linux-hardware.org/?probe=306d50f7e3) | Oct 03, 2022 |
| OEM           | Unknown                     | [68b7e03b06](https://linux-hardware.org/?probe=68b7e03b06) | Sep 29, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [f750ea8b83](https://linux-hardware.org/?probe=f750ea8b83) | Sep 26, 2022 |
| MSI           | Z97S SLI Krait Edition      | [f35b53ca7c](https://linux-hardware.org/?probe=f35b53ca7c) | Sep 25, 2022 |
| ASRock        | E3V5 Performance Gaming/... | [3653dbd804](https://linux-hardware.org/?probe=3653dbd804) | Sep 20, 2022 |
| AZW           | GK55                        | [9a9019eee6](https://linux-hardware.org/?probe=9a9019eee6) | Sep 19, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [4dce87f7fa](https://linux-hardware.org/?probe=4dce87f7fa) | Sep 16, 2022 |
| Lenovo        | 1036 NO DPK                 | [1b7cb7f0d2](https://linux-hardware.org/?probe=1b7cb7f0d2) | Sep 14, 2022 |
| Lenovo        | 1036 NO DPK                 | [0ac056f016](https://linux-hardware.org/?probe=0ac056f016) | Sep 14, 2022 |
| ONDA          | M3 miniPC VER               | [81ebde1d65](https://linux-hardware.org/?probe=81ebde1d65) | Sep 13, 2022 |
| Colorful T... | H510M-D M.2 V20 V20         | [9b25859acf](https://linux-hardware.org/?probe=9b25859acf) | Sep 11, 2022 |
| MSI           | B450M MORTAR                | [2e0d41f272](https://linux-hardware.org/?probe=2e0d41f272) | Sep 10, 2022 |
| MSI           | B450M MORTAR                | [06ee689632](https://linux-hardware.org/?probe=06ee689632) | Sep 10, 2022 |
| Unknown       | Unknown                     | [a0c1db14a0](https://linux-hardware.org/?probe=a0c1db14a0) | Sep 09, 2022 |
| ONDA          | M3 miniPC VER               | [40f73e6e82](https://linux-hardware.org/?probe=40f73e6e82) | Sep 07, 2022 |
| Dell          | 0NV0M7 A02                  | [23024b776e](https://linux-hardware.org/?probe=23024b776e) | Sep 06, 2022 |
| ASUSTek       | BM6630_BM6330_BP6230        | [d510db88c4](https://linux-hardware.org/?probe=d510db88c4) | Sep 02, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [f872d36cd5](https://linux-hardware.org/?probe=f872d36cd5) | Sep 01, 2022 |
| Unknown       | Unknown                     | [ef43339df1](https://linux-hardware.org/?probe=ef43339df1) | Aug 28, 2022 |
| retsamarre... | Unknown                     | [5bc4dd4776](https://linux-hardware.org/?probe=5bc4dd4776) | Aug 23, 2022 |
| retsamarre... | Unknown                     | [8f8e0f49df](https://linux-hardware.org/?probe=8f8e0f49df) | Aug 23, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [8898d24c48](https://linux-hardware.org/?probe=8898d24c48) | Aug 22, 2022 |
| Biostar       | B550M-SILVER                | [d3a371bce6](https://linux-hardware.org/?probe=d3a371bce6) | Aug 20, 2022 |
| Lenovo        | 3102 SDK0L77767 WIN 3423... | [5d884c320f](https://linux-hardware.org/?probe=5d884c320f) | Aug 16, 2022 |
| MSI           | MAG B550M MORTAR            | [baf348cae9](https://linux-hardware.org/?probe=baf348cae9) | Aug 12, 2022 |
| HP            | 8183                        | [19f5199de8](https://linux-hardware.org/?probe=19f5199de8) | Aug 12, 2022 |
| HP            | 8183                        | [c441ead9f8](https://linux-hardware.org/?probe=c441ead9f8) | Aug 11, 2022 |
| ASRock        | H81M-HDS                    | [1d636956f2](https://linux-hardware.org/?probe=1d636956f2) | Aug 07, 2022 |
| Unknown       | Unknown                     | [7d2ea1146a](https://linux-hardware.org/?probe=7d2ea1146a) | Aug 07, 2022 |
| Unknown       | Unknown                     | [dbafe167dc](https://linux-hardware.org/?probe=dbafe167dc) | Aug 06, 2022 |
| Gigabyte      | B450M GAMING                | [c1d23f2838](https://linux-hardware.org/?probe=c1d23f2838) | Aug 06, 2022 |
| Lenovo        | 102F NO DPK                 | [1a040c2717](https://linux-hardware.org/?probe=1a040c2717) | Aug 04, 2022 |
| Intel         | X99                         | [33e0d23783](https://linux-hardware.org/?probe=33e0d23783) | Aug 04, 2022 |
| Lenovo        | 3133 SDK0J40675 WIN 3305... | [4434d4d78a](https://linux-hardware.org/?probe=4434d4d78a) | Jul 29, 2022 |
| ASUSTek       | F2A55-M LK2 PLUS            | [a0a4abeb19](https://linux-hardware.org/?probe=a0a4abeb19) | Jul 28, 2022 |
| Intel         | D54250WYK H13922-303        | [5ff32931fa](https://linux-hardware.org/?probe=5ff32931fa) | Jul 27, 2022 |
| Gigabyte      | Z690I A ULTRA PLUS D4       | [453b2cce27](https://linux-hardware.org/?probe=453b2cce27) | Jul 22, 2022 |
| X79-1356      | Unknown                     | [2db70d0471](https://linux-hardware.org/?probe=2db70d0471) | Jul 22, 2022 |
| Lenovo        | NOK                         | [a47a727578](https://linux-hardware.org/?probe=a47a727578) | Jul 22, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [6ff44b9490](https://linux-hardware.org/?probe=6ff44b9490) | Jul 15, 2022 |
| MSI           | Z370-OC PRO                 | [2c9d1d78df](https://linux-hardware.org/?probe=2c9d1d78df) | Jul 12, 2022 |
| Colorful T... | H310M-T PRO V21             | [b922e2142b](https://linux-hardware.org/?probe=b922e2142b) | Jul 11, 2022 |
| Unknown       | Unknown                     | [7b1c72c3e7](https://linux-hardware.org/?probe=7b1c72c3e7) | Jul 06, 2022 |
| Gigabyte      | Z87P-D3                     | [2ae62ac227](https://linux-hardware.org/?probe=2ae62ac227) | Jun 30, 2022 |
| MSI           | Z68A-GD80                   | [2e2ca703b0](https://linux-hardware.org/?probe=2e2ca703b0) | Jun 30, 2022 |
| Gigabyte      | EP45-UD3                    | [bb62363ad2](https://linux-hardware.org/?probe=bb62363ad2) | Jun 29, 2022 |
| MSI           | B360M MORTAR                | [607f489961](https://linux-hardware.org/?probe=607f489961) | Jun 25, 2022 |
| Unknown       | Unknown                     | [b3def4c8ad](https://linux-hardware.org/?probe=b3def4c8ad) | Jun 25, 2022 |
| MSI           | MAG B550M MORTAR            | [209001317a](https://linux-hardware.org/?probe=209001317a) | Jun 23, 2022 |
| MAINBRD       | OPS62A-SHA                  | [7c16967701](https://linux-hardware.org/?probe=7c16967701) | Jun 10, 2022 |
| Unknown       | Unknown                     | [2a25ea86fc](https://linux-hardware.org/?probe=2a25ea86fc) | Jun 05, 2022 |
| Unknown       | Unknown                     | [4c36218f66](https://linux-hardware.org/?probe=4c36218f66) | Jun 04, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [a9c714d138](https://linux-hardware.org/?probe=a9c714d138) | Jun 03, 2022 |
| MAINBRD       | OPS62A-SHA                  | [33201d3794](https://linux-hardware.org/?probe=33201d3794) | Jun 02, 2022 |
| Unknown       | Unknown                     | [bcb55ce8ce](https://linux-hardware.org/?probe=bcb55ce8ce) | Jun 01, 2022 |
| Unknown       | Unknown                     | [24a7b3121f](https://linux-hardware.org/?probe=24a7b3121f) | May 29, 2022 |
| Gigabyte      | X570 GAMING X               | [3ddc17645b](https://linux-hardware.org/?probe=3ddc17645b) | May 29, 2022 |
| Unknown       | Unknown                     | [1da299e36e](https://linux-hardware.org/?probe=1da299e36e) | May 29, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [91306ce19f](https://linux-hardware.org/?probe=91306ce19f) | May 29, 2022 |
| Intel         | D54250WYK H13922-303        | [59eda31291](https://linux-hardware.org/?probe=59eda31291) | May 24, 2022 |
| MSI           | H97M-P35                    | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| Intel         | HURONRIVER                  | [1ebb900517](https://linux-hardware.org/?probe=1ebb900517) | May 22, 2022 |
| MSI           | B450M-A PRO MAX             | [fce678a9e8](https://linux-hardware.org/?probe=fce678a9e8) | May 21, 2022 |
| Lenovo        | NOK                         | [567c167a97](https://linux-hardware.org/?probe=567c167a97) | May 20, 2022 |
| MAXSUN        | MS-M3A78EL                  | [98d8c5a6ee](https://linux-hardware.org/?probe=98d8c5a6ee) | May 14, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | [a83103153b](https://linux-hardware.org/?probe=a83103153b) | May 12, 2022 |
| TSINGHUA T... | B460M-HDV                   | [3c126b8a1d](https://linux-hardware.org/?probe=3c126b8a1d) | May 10, 2022 |
| Lenovo        | NO DPK                      | [24340ea9a8](https://linux-hardware.org/?probe=24340ea9a8) | May 06, 2022 |
| Lenovo        | NO DPK                      | [dc8d8b070e](https://linux-hardware.org/?probe=dc8d8b070e) | May 05, 2022 |
| OEM           | V1.0                        | [167ee50568](https://linux-hardware.org/?probe=167ee50568) | Apr 29, 2022 |
| ASRock        | Z170 Gaming K4              | [96b772b4e6](https://linux-hardware.org/?probe=96b772b4e6) | Apr 24, 2022 |
| ASRock        | Z170 Gaming K4              | [81e06a1dcb](https://linux-hardware.org/?probe=81e06a1dcb) | Apr 18, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [c4561b1073](https://linux-hardware.org/?probe=c4561b1073) | Apr 18, 2022 |
| J&W           | J1900T                      | [7c87f17ed7](https://linux-hardware.org/?probe=7c87f17ed7) | Apr 17, 2022 |
| ASRock        | H110M-DVS R2.0              | [aa88339957](https://linux-hardware.org/?probe=aa88339957) | Apr 16, 2022 |
| Lenovo        | MAHOBAY 31900005 STD        | [d82d73ba0a](https://linux-hardware.org/?probe=d82d73ba0a) | Apr 12, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [a8e2ef2c76](https://linux-hardware.org/?probe=a8e2ef2c76) | Apr 12, 2022 |
| Intel         | SHARKBAY                    | [f676b9a255](https://linux-hardware.org/?probe=f676b9a255) | Apr 11, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [686ef53bc5](https://linux-hardware.org/?probe=686ef53bc5) | Apr 07, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [aad4b24a04](https://linux-hardware.org/?probe=aad4b24a04) | Apr 06, 2022 |
| ASUSTek       | X99-DELUXE II               | [82939dc69f](https://linux-hardware.org/?probe=82939dc69f) | Apr 05, 2022 |
| Unknown       | Unknown                     | [aac8a6f7e4](https://linux-hardware.org/?probe=aac8a6f7e4) | Apr 03, 2022 |
| Lenovo        | 32E9 SDK0T76479 WIN 3423... | [d8dbd14b3e](https://linux-hardware.org/?probe=d8dbd14b3e) | Apr 02, 2022 |
| Lenovo        | QiTianM7150                 | [a6a37565b7](https://linux-hardware.org/?probe=a6a37565b7) | Apr 02, 2022 |
| Inspur        | NF5270M3                    | [053fcd58fc](https://linux-hardware.org/?probe=053fcd58fc) | Mar 26, 2022 |
| ASUSTek       | B360M-D3H                   | [bf6e46cd01](https://linux-hardware.org/?probe=bf6e46cd01) | Mar 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [847b9e1fbb](https://linux-hardware.org/?probe=847b9e1fbb) | Mar 23, 2022 |
| MSI           | B450M MORTAR                | [4c4039754c](https://linux-hardware.org/?probe=4c4039754c) | Mar 13, 2022 |
| Lenovo        | 3187 SDK0L77769 WIN 3423... | [545b878c51](https://linux-hardware.org/?probe=545b878c51) | Mar 10, 2022 |
| ASUSTek       | PRIME H510M-K               | [3edcfcdf53](https://linux-hardware.org/?probe=3edcfcdf53) | Mar 08, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [5c95114871](https://linux-hardware.org/?probe=5c95114871) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6931b9fe82](https://linux-hardware.org/?probe=6931b9fe82) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [842379fc35](https://linux-hardware.org/?probe=842379fc35) | Mar 01, 2022 |
| Lenovo        | MAHOBAY                     | [cd7e96054b](https://linux-hardware.org/?probe=cd7e96054b) | Mar 01, 2022 |
| Gigabyte      | EP43T-UD3L                  | [e1ba37c64a](https://linux-hardware.org/?probe=e1ba37c64a) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [5d56069677](https://linux-hardware.org/?probe=5d56069677) | Feb 27, 2022 |
| Lenovo        | NOK                         | [05c2b02bd3](https://linux-hardware.org/?probe=05c2b02bd3) | Feb 26, 2022 |
| MSI           | B350 TOMAHAWK               | [a07d445338](https://linux-hardware.org/?probe=a07d445338) | Feb 21, 2022 |
| Lenovo        | NOK                         | [3936474618](https://linux-hardware.org/?probe=3936474618) | Feb 18, 2022 |
| Lenovo        | NOK                         | [1236b9a36b](https://linux-hardware.org/?probe=1236b9a36b) | Feb 17, 2022 |
| MSI           | A88XM-E45                   | [b58bd64798](https://linux-hardware.org/?probe=b58bd64798) | Feb 17, 2022 |
| ECS           | BSWI-DA                     | [2b3dda83e5](https://linux-hardware.org/?probe=2b3dda83e5) | Feb 04, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [0bef76b548](https://linux-hardware.org/?probe=0bef76b548) | Jan 28, 2022 |
| ASUSTek       | PRIME Z370-A                | [53b2c696ff](https://linux-hardware.org/?probe=53b2c696ff) | Jan 26, 2022 |
| ASUSTek       | PRIME Z370-A                | [7b2482036e](https://linux-hardware.org/?probe=7b2482036e) | Jan 26, 2022 |
| Intel         | G41 V1.0                    | [e1f1c99851](https://linux-hardware.org/?probe=e1f1c99851) | Jan 22, 2022 |
| MSI           | H310M-S03                   | [8c009a1259](https://linux-hardware.org/?probe=8c009a1259) | Jan 17, 2022 |
| ASUSTek       | PRO B460M-C                 | [31b2f44066](https://linux-hardware.org/?probe=31b2f44066) | Jan 17, 2022 |
| Dell          | 0MWYPT A02                  | [08d5ba6a97](https://linux-hardware.org/?probe=08d5ba6a97) | Dec 30, 2021 |
| ASRock        | Z170 Gaming K4              | [590ae02fdb](https://linux-hardware.org/?probe=590ae02fdb) | Dec 29, 2021 |
| TSINGHUA T... | B460M-HDV                   | [8447bd4156](https://linux-hardware.org/?probe=8447bd4156) | Dec 22, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [50d0f206e1](https://linux-hardware.org/?probe=50d0f206e1) | Dec 21, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [1564f2f5ea](https://linux-hardware.org/?probe=1564f2f5ea) | Dec 18, 2021 |
| Lenovo        | Unknown                     | [64951d70ab](https://linux-hardware.org/?probe=64951d70ab) | Dec 16, 2021 |
| TSINGHUA T... | B460M-HDV                   | [1146dc777c](https://linux-hardware.org/?probe=1146dc777c) | Dec 15, 2021 |
| ASUSTek       | B85M-F                      | [04b3b165f6](https://linux-hardware.org/?probe=04b3b165f6) | Dec 14, 2021 |
| ASRock        | Z170 Gaming K4              | [4f8e294d95](https://linux-hardware.org/?probe=4f8e294d95) | Dec 13, 2021 |
| Lenovo        | 3141 NOK                    | [cc90d7c889](https://linux-hardware.org/?probe=cc90d7c889) | Dec 13, 2021 |
| MSI           | B450I GAMING PLUS AC        | [fe97757850](https://linux-hardware.org/?probe=fe97757850) | Dec 10, 2021 |
| ASUSTek       | PRO B460M-C                 | [ff8706d7ac](https://linux-hardware.org/?probe=ff8706d7ac) | Dec 07, 2021 |
| OEM           | TOP77D Ver1.0               | [5747ccfcd4](https://linux-hardware.org/?probe=5747ccfcd4) | Dec 07, 2021 |
| ASRock        | B360M-ITX/ac                | [2490a94114](https://linux-hardware.org/?probe=2490a94114) | Dec 07, 2021 |
| AOC           | A815HB                      | [b1aec8b16c](https://linux-hardware.org/?probe=b1aec8b16c) | Dec 04, 2021 |
| OEM           | TOP77D Ver1.0               | [6b91b58b81](https://linux-hardware.org/?probe=6b91b58b81) | Nov 30, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [69a76fd0b6](https://linux-hardware.org/?probe=69a76fd0b6) | Nov 29, 2021 |
| ASUSTek       | PRO B460M-C                 | [b316c12d03](https://linux-hardware.org/?probe=b316c12d03) | Nov 27, 2021 |
| Gigabyte      | H61M-DS2                    | [c487bf6a9c](https://linux-hardware.org/?probe=c487bf6a9c) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [fa956800a1](https://linux-hardware.org/?probe=fa956800a1) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3d27077285](https://linux-hardware.org/?probe=3d27077285) | Nov 24, 2021 |
| ASUSTek       | B85M-G PLUS                 | [e198df930c](https://linux-hardware.org/?probe=e198df930c) | Nov 23, 2021 |
| ASUSTek       | B85M-G PLUS                 | [023ab776cd](https://linux-hardware.org/?probe=023ab776cd) | Nov 23, 2021 |
| Google        | Panther                     | [5e5d9936ec](https://linux-hardware.org/?probe=5e5d9936ec) | Nov 23, 2021 |
| ASRock        | Z170 Gaming K4              | [6a0bda5a7d](https://linux-hardware.org/?probe=6a0bda5a7d) | Nov 22, 2021 |
| Dell          | 0R790T A00                  | [af9a5a76c3](https://linux-hardware.org/?probe=af9a5a76c3) | Nov 22, 2021 |
| Gigabyte      | B85M-D3V-A                  | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| ASRock        | TRX40 Creator               | [bdd3471fa2](https://linux-hardware.org/?probe=bdd3471fa2) | Nov 17, 2021 |
| AOC           | A815HB                      | [e56b509a5a](https://linux-hardware.org/?probe=e56b509a5a) | Nov 16, 2021 |
| ASUSTek       | PRIME Z370-A                | [01b7731b34](https://linux-hardware.org/?probe=01b7731b34) | Nov 14, 2021 |
| Shanghai Z... | EA170_ TBD                  | [edc1846e0f](https://linux-hardware.org/?probe=edc1846e0f) | Nov 10, 2021 |
| Shanghai Z... | EA170_ TBD                  | [9f839630ac](https://linux-hardware.org/?probe=9f839630ac) | Nov 10, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [74d845aae1](https://linux-hardware.org/?probe=74d845aae1) | Nov 07, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [cafc4421b2](https://linux-hardware.org/?probe=cafc4421b2) | Oct 29, 2021 |
| Lenovo        | 3107 SDK0L77769 WIN 3423... | [6a7a621271](https://linux-hardware.org/?probe=6a7a621271) | Oct 22, 2021 |
| Unknown       | Unknown                     | [2fb1797d3d](https://linux-hardware.org/?probe=2fb1797d3d) | Oct 19, 2021 |
| ASRock        | B85M Pro4                   | [bf91ce9da1](https://linux-hardware.org/?probe=bf91ce9da1) | Oct 14, 2021 |
| Dell          | 0C96W1 A02                  | [edb83b3d2f](https://linux-hardware.org/?probe=edb83b3d2f) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [3eb7a24e5a](https://linux-hardware.org/?probe=3eb7a24e5a) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [38bb1cfdc4](https://linux-hardware.org/?probe=38bb1cfdc4) | Oct 12, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [5e8e9aea62](https://linux-hardware.org/?probe=5e8e9aea62) | Oct 12, 2021 |
| ASUSTek       | A55BM-E                     | [970153a68c](https://linux-hardware.org/?probe=970153a68c) | Oct 03, 2021 |
| Lenovo        | MAHOBAY                     | [f1420c5af0](https://linux-hardware.org/?probe=f1420c5af0) | Sep 29, 2021 |
| ASRock        | TRX40 Creator               | [c7b8fcc312](https://linux-hardware.org/?probe=c7b8fcc312) | Sep 29, 2021 |
| Unknown       | Unknown                     | [4c18e17d7d](https://linux-hardware.org/?probe=4c18e17d7d) | Sep 29, 2021 |
| MSI           | B450M MORTAR MAX            | [8adcff21a2](https://linux-hardware.org/?probe=8adcff21a2) | Sep 27, 2021 |
| Gigabyte      | B450M DS3H-CF               | [10ce8f4e5e](https://linux-hardware.org/?probe=10ce8f4e5e) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [b62637ba85](https://linux-hardware.org/?probe=b62637ba85) | Sep 25, 2021 |
| ASUSTek       | H87-PRO                     | [508bab38ae](https://linux-hardware.org/?probe=508bab38ae) | Sep 20, 2021 |
| ASUSTek       | H87-PRO                     | [8b09747789](https://linux-hardware.org/?probe=8b09747789) | Sep 20, 2021 |
| Sapphire      | Pure Platinum 970A-PLUS     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| TSINGHUA T... | B460M-HDV                   | [bc175433f9](https://linux-hardware.org/?probe=bc175433f9) | Sep 18, 2021 |
| TSINGHUA T... | B460M-HDV                   | [80017bc79b](https://linux-hardware.org/?probe=80017bc79b) | Sep 18, 2021 |
| ASUSTek       | B360M-BASALT                | [f1783ce369](https://linux-hardware.org/?probe=f1783ce369) | Sep 18, 2021 |
| Lenovo        | NOK                         | [61a15d9531](https://linux-hardware.org/?probe=61a15d9531) | Sep 14, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [a48ec730b7](https://linux-hardware.org/?probe=a48ec730b7) | Sep 13, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [db46242eec](https://linux-hardware.org/?probe=db46242eec) | Sep 13, 2021 |
| ASUSTek       | Z170-A                      | [2d0a7ed28d](https://linux-hardware.org/?probe=2d0a7ed28d) | Aug 28, 2021 |
| ASUSTek       | Z170-A                      | [fc294326ce](https://linux-hardware.org/?probe=fc294326ce) | Aug 28, 2021 |
| Dell          | 0R790T A00                  | [03b37f86b2](https://linux-hardware.org/?probe=03b37f86b2) | Aug 27, 2021 |
| Lenovo        | SHARKBAY NOK                | [33cc1aba5f](https://linux-hardware.org/?probe=33cc1aba5f) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e0e805180d](https://linux-hardware.org/?probe=e0e805180d) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [ce37ed52aa](https://linux-hardware.org/?probe=ce37ed52aa) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [18f0785e64](https://linux-hardware.org/?probe=18f0785e64) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [753b5b706d](https://linux-hardware.org/?probe=753b5b706d) | Aug 18, 2021 |
| Yanling       | YL-KBRL2 Series Ver:1.01    | [ad2f5f75d8](https://linux-hardware.org/?probe=ad2f5f75d8) | Aug 10, 2021 |
| TSINGHUA T... | B460-N2                     | [59d9384348](https://linux-hardware.org/?probe=59d9384348) | Aug 09, 2021 |
| ASUSTek       | Z97-PRO                     | [a0e65d5ee7](https://linux-hardware.org/?probe=a0e65d5ee7) | Aug 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [07e9ee8610](https://linux-hardware.org/?probe=07e9ee8610) | Aug 02, 2021 |
| Dell          | 0R790T A00                  | [474dfcb3e3](https://linux-hardware.org/?probe=474dfcb3e3) | Jul 26, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | [d84332d50b](https://linux-hardware.org/?probe=d84332d50b) | Jul 14, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | [f68b508049](https://linux-hardware.org/?probe=f68b508049) | Jul 14, 2021 |
| AMD           | BL2 V2.3                    | [1053adf355](https://linux-hardware.org/?probe=1053adf355) | Jul 12, 2021 |
| MSI           | Z590-A PRO                  | [50d75ad77d](https://linux-hardware.org/?probe=50d75ad77d) | Jul 03, 2021 |
| Dell          | 0GX297                      | [f4debf994a](https://linux-hardware.org/?probe=f4debf994a) | Jun 30, 2021 |
| HP            | 18E7                        | [5f0e216922](https://linux-hardware.org/?probe=5f0e216922) | Jun 28, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | [70d8ede642](https://linux-hardware.org/?probe=70d8ede642) | Jun 23, 2021 |
| Gigabyte      | GA-970A-D3                  | [61460e5cfc](https://linux-hardware.org/?probe=61460e5cfc) | Jun 23, 2021 |
| Gigabyte      | GA-970A-D3                  | [c916e64b0d](https://linux-hardware.org/?probe=c916e64b0d) | Jun 23, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | [8431bcbed8](https://linux-hardware.org/?probe=8431bcbed8) | Jun 22, 2021 |
| ASUSTek       | P5QL PRO                    | [c76462e732](https://linux-hardware.org/?probe=c76462e732) | Jun 20, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [c0ecdee03e](https://linux-hardware.org/?probe=c0ecdee03e) | Jun 20, 2021 |
| ASUSTek       | P5QL PRO                    | [8b9f25c98b](https://linux-hardware.org/?probe=8b9f25c98b) | Jun 19, 2021 |
| Loongson      | LS3A3000-7A1000-1w-V1.2-... | [014bdabb68](https://linux-hardware.org/?probe=014bdabb68) | Jun 16, 2021 |
| Lenovo        | H310                        | [309031a039](https://linux-hardware.org/?probe=309031a039) | Jun 12, 2021 |
| Advantech     | DMS-BC30 A101-2             | [e9ee5e90e8](https://linux-hardware.org/?probe=e9ee5e90e8) | Jun 08, 2021 |
| Advantech     | DMS-BC30 A101-2             | [2fd059f38d](https://linux-hardware.org/?probe=2fd059f38d) | Jun 08, 2021 |
| Lenovo        | H310                        | [f36653c4fb](https://linux-hardware.org/?probe=f36653c4fb) | Jun 06, 2021 |
| Unknown       | Kunpeng Desktop Board D9... | [2a8b1a08bc](https://linux-hardware.org/?probe=2a8b1a08bc) | Jun 04, 2021 |
| Unknown       | Kunpeng Desktop Board D9... | [ead2c4250e](https://linux-hardware.org/?probe=ead2c4250e) | Jun 04, 2021 |
| Huanghe       | PRO H410M-C                 | [37534d085b](https://linux-hardware.org/?probe=37534d085b) | Jun 04, 2021 |
| Huanghe       | PRO H410M-C                 | [1c92e63940](https://linux-hardware.org/?probe=1c92e63940) | May 31, 2021 |
| Huanan        | X79 VAA1                    | [150afcb2d1](https://linux-hardware.org/?probe=150afcb2d1) | May 30, 2021 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [a22fbcde28](https://linux-hardware.org/?probe=a22fbcde28) | May 26, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [59f94e4db6](https://linux-hardware.org/?probe=59f94e4db6) | May 25, 2021 |
| Centerm       | C92                         | [fe4761d2b2](https://linux-hardware.org/?probe=fe4761d2b2) | May 25, 2021 |
| Acer          | Aspire TC-606               | [db910234a6](https://linux-hardware.org/?probe=db910234a6) | May 25, 2021 |
| Soyo          | SY-I5GC2-L                  | [02a90f300e](https://linux-hardware.org/?probe=02a90f300e) | May 24, 2021 |
| Soyo          | SY-I5GC2-L                  | [91bdc4a9a0](https://linux-hardware.org/?probe=91bdc4a9a0) | May 24, 2021 |
| MSI           | Z590-A PRO                  | [b74e96d4be](https://linux-hardware.org/?probe=b74e96d4be) | May 22, 2021 |
| Dell          | 0HN7XN A01                  | [fa2352afac](https://linux-hardware.org/?probe=fa2352afac) | May 19, 2021 |
| Gigabyte      | B365M D2V                   | [887f18105e](https://linux-hardware.org/?probe=887f18105e) | May 17, 2021 |
| Gigabyte      | B365M D2V                   | [644431aa47](https://linux-hardware.org/?probe=644431aa47) | May 17, 2021 |
| Gigabyte      | Z170X-UD3-CF                | [41fbd83170](https://linux-hardware.org/?probe=41fbd83170) | May 17, 2021 |
| Lenovo        | 3176 SDK0L77767 WIN 3423... | [d418b8e0e9](https://linux-hardware.org/?probe=d418b8e0e9) | May 17, 2021 |
| Lenovo        | 3176 SDK0L77767 WIN 3423... | [b04d956c6e](https://linux-hardware.org/?probe=b04d956c6e) | May 17, 2021 |
| MSI           | Z590-A PRO                  | [b2cc4333b0](https://linux-hardware.org/?probe=b2cc4333b0) | May 16, 2021 |
| Gigabyte      | B460M AORUS PRO             | [ef3422dd2d](https://linux-hardware.org/?probe=ef3422dd2d) | May 14, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [321f62efb9](https://linux-hardware.org/?probe=321f62efb9) | May 04, 2021 |
| MSI           | B450M MORTAR                | [586195f9e8](https://linux-hardware.org/?probe=586195f9e8) | May 03, 2021 |
| MSI           | B450M MORTAR                | [0f71a5127c](https://linux-hardware.org/?probe=0f71a5127c) | May 01, 2021 |
| Lenovo        | No DPK                      | [15a0f7dbe3](https://linux-hardware.org/?probe=15a0f7dbe3) | Apr 27, 2021 |
| ELSKY         | M219F-6C                    | [85ce077799](https://linux-hardware.org/?probe=85ce077799) | Apr 22, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [c557439d9f](https://linux-hardware.org/?probe=c557439d9f) | Apr 03, 2021 |
| MSI           | B450M MORTAR                | [8406dee7f4](https://linux-hardware.org/?probe=8406dee7f4) | Apr 02, 2021 |
| MSI           | B450M MORTAR                | [6e403bbf50](https://linux-hardware.org/?probe=6e403bbf50) | Apr 02, 2021 |
| SYWZ          | S210H Series                | [2e8183b6eb](https://linux-hardware.org/?probe=2e8183b6eb) | Mar 14, 2021 |
| SYWZ          | S210H Series                | [d0f36756ab](https://linux-hardware.org/?probe=d0f36756ab) | Mar 14, 2021 |
| Dell          | 03CPWF A00                  | [126a2e8974](https://linux-hardware.org/?probe=126a2e8974) | Feb 22, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [0ac46a588c](https://linux-hardware.org/?probe=0ac46a588c) | Feb 21, 2021 |
| Gigabyte      | B85M-D2V-SI                 | [a0779807a2](https://linux-hardware.org/?probe=a0779807a2) | Feb 15, 2021 |
| Dell          | 04VF8V A01                  | [14d2de53c9](https://linux-hardware.org/?probe=14d2de53c9) | Feb 14, 2021 |
| ASRock        | A320M-HDV                   | [d844c4f50e](https://linux-hardware.org/?probe=d844c4f50e) | Feb 05, 2021 |
| ASRock        | A320M-HDV                   | [5c23d11a52](https://linux-hardware.org/?probe=5c23d11a52) | Feb 05, 2021 |
| HUAWEI        | SP1PGUM M1020               | [bd05c84564](https://linux-hardware.org/?probe=bd05c84564) | Feb 04, 2021 |
| Dell          | 06JWJY A00                  | [1f2099e9d3](https://linux-hardware.org/?probe=1f2099e9d3) | Feb 02, 2021 |
| MSI           | B450I GAMING PLUS AC        | [5b274af228](https://linux-hardware.org/?probe=5b274af228) | Feb 02, 2021 |
| ASUSTek       | PRIME Z270-A                | [9c21c30887](https://linux-hardware.org/?probe=9c21c30887) | Jan 30, 2021 |
| MSI           | MAG B460M MORTAR WIFI       | [35d97e2d21](https://linux-hardware.org/?probe=35d97e2d21) | Jan 28, 2021 |
| MSI           | B450I GAMING PLUS AC        | [a1c263681f](https://linux-hardware.org/?probe=a1c263681f) | Jan 26, 2021 |
| ASUSTek       | PRIME H310M-F R2.0          | [3c4d584c27](https://linux-hardware.org/?probe=3c4d584c27) | Jan 26, 2021 |
| ASUSTek       | PRIME H410M-E               | [1b100a591d](https://linux-hardware.org/?probe=1b100a591d) | Jan 19, 2021 |
| Lenovo        | 317E SDK0L77767 WIN 3423... | [6e82572f07](https://linux-hardware.org/?probe=6e82572f07) | Jan 17, 2021 |
| MSI           | B450 TOMAHAWK               | [edbfbb65b8](https://linux-hardware.org/?probe=edbfbb65b8) | Jan 15, 2021 |
| Lenovo        | 3107 NOK                    | [902ea74b31](https://linux-hardware.org/?probe=902ea74b31) | Jan 08, 2021 |
| Google        | Zako                        | [d8df4eefd6](https://linux-hardware.org/?probe=d8df4eefd6) | Jan 01, 2021 |
| Google        | Zako                        | [6bedd150e9](https://linux-hardware.org/?probe=6bedd150e9) | Jan 01, 2021 |
| HP            | 82A4                        | [bf686ef745](https://linux-hardware.org/?probe=bf686ef745) | Jan 01, 2021 |
| Lenovo        | 1.0                         | [897523f5fd](https://linux-hardware.org/?probe=897523f5fd) | Dec 27, 2020 |
| Lenovo        | 1.0                         | [53a763dc24](https://linux-hardware.org/?probe=53a763dc24) | Dec 27, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | [fd025ae38b](https://linux-hardware.org/?probe=fd025ae38b) | Dec 23, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | [a141f2ed51](https://linux-hardware.org/?probe=a141f2ed51) | Dec 22, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [224c36cf4d](https://linux-hardware.org/?probe=224c36cf4d) | Dec 15, 2020 |
| ASRock        | Z170 Gaming K4              | [a246612b17](https://linux-hardware.org/?probe=a246612b17) | Dec 13, 2020 |
| ASUSTek       | PRIME H270-PLUS             | [0c0911cd7b](https://linux-hardware.org/?probe=0c0911cd7b) | Dec 11, 2020 |
| ASUSTek       | PRIME B450M-A               | [b20c8c639e](https://linux-hardware.org/?probe=b20c8c639e) | Dec 08, 2020 |
| HUAWEI        | Kunpeng Desktop             | [cbd268b858](https://linux-hardware.org/?probe=cbd268b858) | Dec 04, 2020 |
| HUAWEI        | Kunpeng Desktop             | [da163e34c7](https://linux-hardware.org/?probe=da163e34c7) | Dec 04, 2020 |
| ASUSTek       | PRIME A520M-K               | [7eb641e51d](https://linux-hardware.org/?probe=7eb641e51d) | Dec 01, 2020 |
| ASUSTek       | B85M-G                      | [216a0f765e](https://linux-hardware.org/?probe=216a0f765e) | Dec 01, 2020 |
| Gigabyte      | B250-D3A-CF                 | [907d35d953](https://linux-hardware.org/?probe=907d35d953) | Nov 30, 2020 |
| Gigabyte      | B250-HD3-CF                 | [d1c0a8df13](https://linux-hardware.org/?probe=d1c0a8df13) | Nov 23, 2020 |
| Gigabyte      | B250-HD3-CF                 | [7975ba3888](https://linux-hardware.org/?probe=7975ba3888) | Nov 23, 2020 |
| Unknown       | Unknown                     | [d58e8b793e](https://linux-hardware.org/?probe=d58e8b793e) | Nov 22, 2020 |
| Unknown       | Unknown                     | [c0e8909067](https://linux-hardware.org/?probe=c0e8909067) | Nov 22, 2020 |
| Unknown       | Unknown                     | [c0d7c657b1](https://linux-hardware.org/?probe=c0d7c657b1) | Nov 22, 2020 |
| Gigabyte      | 970-GAMING                  | [44f42f7676](https://linux-hardware.org/?probe=44f42f7676) | Nov 21, 2020 |
| Colorful T... | C.H110M-K PRO V21           | [c8211ace73](https://linux-hardware.org/?probe=c8211ace73) | Nov 20, 2020 |
| ASUSTek       | PRIME X570-P                | [0999a52054](https://linux-hardware.org/?probe=0999a52054) | Nov 18, 2020 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a5d5227154](https://linux-hardware.org/?probe=a5d5227154) | Nov 12, 2020 |
| HP            | 8455                        | [8fbf07649a](https://linux-hardware.org/?probe=8fbf07649a) | Nov 03, 2020 |
| Intel         | SKYBAY                      | [ebc35582c8](https://linux-hardware.org/?probe=ebc35582c8) | Oct 23, 2020 |
| Intel         | SKYBAY                      | [ce89df6806](https://linux-hardware.org/?probe=ce89df6806) | Oct 23, 2020 |
| MSI           | X99A XPOWER GAMING TITAN... | [6faf6514f5](https://linux-hardware.org/?probe=6faf6514f5) | Oct 15, 2020 |
| Gigabyte      | B85M-D2V                    | [3393bfd809](https://linux-hardware.org/?probe=3393bfd809) | Sep 25, 2020 |
| Gigabyte      | B85M-D2V                    | [4ef60f3d1d](https://linux-hardware.org/?probe=4ef60f3d1d) | Sep 25, 2020 |
| ASRock        | FM2A85M-DG3                 | [8516ddc869](https://linux-hardware.org/?probe=8516ddc869) | Sep 24, 2020 |
| AEWIN         | SCB-1711A                   | [2d8dbb0d3a](https://linux-hardware.org/?probe=2d8dbb0d3a) | Sep 09, 2020 |
| RBQ           | RongBotQiu X79.810          | [71e839ea6f](https://linux-hardware.org/?probe=71e839ea6f) | Sep 03, 2020 |
| Lenovo        | 36EF SDK0L77767 WIN 3423... | [a01c93c314](https://linux-hardware.org/?probe=a01c93c314) | Sep 01, 2020 |
| Lenovo        | 36EF SDK0L77767 WIN 3423... | [2800d63edf](https://linux-hardware.org/?probe=2800d63edf) | Aug 30, 2020 |
| Gigabyte      | B450 AORUS M                | [f0d9b71d6d](https://linux-hardware.org/?probe=f0d9b71d6d) | Aug 15, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [e32815911a](https://linux-hardware.org/?probe=e32815911a) | Aug 11, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [36a4789e67](https://linux-hardware.org/?probe=36a4789e67) | Aug 10, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| Lenovo        | NOK                         | [99cea2b8c1](https://linux-hardware.org/?probe=99cea2b8c1) | Jul 22, 2020 |
| Lenovo        | Unknown                     | [9e428d8ef9](https://linux-hardware.org/?probe=9e428d8ef9) | Jul 16, 2020 |
| MSI           | 880GM-E41                   | [620e8dbc2c](https://linux-hardware.org/?probe=620e8dbc2c) | Jul 13, 2020 |
| Gigabyte      | AB350M-DS2-CF               | [014b2718ae](https://linux-hardware.org/?probe=014b2718ae) | Jul 13, 2020 |
| Gigabyte      | AB350M-DS2-CF               | [6ea3c86837](https://linux-hardware.org/?probe=6ea3c86837) | Jul 13, 2020 |
| Gigabyte      | Z77M-D3H                    | [ce5f57a42d](https://linux-hardware.org/?probe=ce5f57a42d) | Jul 09, 2020 |
| Intel         | H81C                        | [54732275c2](https://linux-hardware.org/?probe=54732275c2) | Jul 04, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [176c1bcb0a](https://linux-hardware.org/?probe=176c1bcb0a) | Jun 24, 2020 |
| MSI           | Z370-OC PRO                 | [a37abc19ef](https://linux-hardware.org/?probe=a37abc19ef) | Jun 08, 2020 |
| ASUSTek       | Z97-PRO                     | [c534bc4bc6](https://linux-hardware.org/?probe=c534bc4bc6) | Jun 04, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | [29eb8f828b](https://linux-hardware.org/?probe=29eb8f828b) | May 30, 2020 |
| HP            | 82A1                        | [ddd727fd22](https://linux-hardware.org/?probe=ddd727fd22) | May 25, 2020 |
| HP            | 807D                        | [0523c549d5](https://linux-hardware.org/?probe=0523c549d5) | May 25, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [220e504029](https://linux-hardware.org/?probe=220e504029) | May 23, 2020 |
| HP            | 807D                        | [d82ca940de](https://linux-hardware.org/?probe=d82ca940de) | May 22, 2020 |
| Biostar       | H110MLC                     | [70e9170fa4](https://linux-hardware.org/?probe=70e9170fa4) | May 15, 2020 |
| Dell          | 09PR9H A02                  | [a0f6d2eac4](https://linux-hardware.org/?probe=a0f6d2eac4) | May 11, 2020 |
| ASUSTek       | Z97-C                       | [6eb7ec99eb](https://linux-hardware.org/?probe=6eb7ec99eb) | May 08, 2020 |
| Gigabyte      | X58A-UD3R                   | [a244f111f8](https://linux-hardware.org/?probe=a244f111f8) | May 05, 2020 |
| Gigabyte      | X58A-UD3R                   | [69210022d8](https://linux-hardware.org/?probe=69210022d8) | May 05, 2020 |
| Gigabyte      | F2A88XM-DS2-TE              | [2b96fc655b](https://linux-hardware.org/?probe=2b96fc655b) | Apr 28, 2020 |
| Gigabyte      | F2A88XM-DS2-TE              | [c53b21972a](https://linux-hardware.org/?probe=c53b21972a) | Apr 28, 2020 |
| ASUSTek       | B85M-G                      | [1339b47680](https://linux-hardware.org/?probe=1339b47680) | Apr 22, 2020 |
| Dell          | 042P49 A02                  | [bd064eace3](https://linux-hardware.org/?probe=bd064eace3) | Apr 21, 2020 |
| Lenovo        | Tiger Hill                  | [7f92e05b46](https://linux-hardware.org/?probe=7f92e05b46) | Apr 14, 2020 |
| Dell          | 040DDP A01                  | [ab41c29212](https://linux-hardware.org/?probe=ab41c29212) | Mar 31, 2020 |
| ECS           | H61H2-TAIO                  | [e6f8d21b5a](https://linux-hardware.org/?probe=e6f8d21b5a) | Mar 24, 2020 |
| ASUSTek       | Z170-A                      | [4629800e33](https://linux-hardware.org/?probe=4629800e33) | Mar 19, 2020 |
| Gigabyte      | B85-HD3                     | [fb4cdf6f1a](https://linux-hardware.org/?probe=fb4cdf6f1a) | Mar 09, 2020 |
| ECS           | H61H2-TAIO                  | [6ee3574f22](https://linux-hardware.org/?probe=6ee3574f22) | Feb 26, 2020 |
| ECS           | H61H2-TAIO                  | [32a0959f61](https://linux-hardware.org/?probe=32a0959f61) | Feb 25, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [73afca4618](https://linux-hardware.org/?probe=73afca4618) | Feb 17, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [81586acd13](https://linux-hardware.org/?probe=81586acd13) | Jan 27, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [a9cada02fe](https://linux-hardware.org/?probe=a9cada02fe) | Jan 27, 2020 |
| Colorful T... | C.Q1900M PRO V20            | [17664b4797](https://linux-hardware.org/?probe=17664b4797) | Jan 25, 2020 |
| Colorful T... | C.Q1900M PRO V20            | [8bc2fe0d86](https://linux-hardware.org/?probe=8bc2fe0d86) | Jan 25, 2020 |
| MSI           | B450M MORTAR                | [eb4106d83f](https://linux-hardware.org/?probe=eb4106d83f) | Jan 10, 2020 |
| ASUSTek       | Z97-PRO                     | [e814486254](https://linux-hardware.org/?probe=e814486254) | Jan 07, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [34f134e5b0](https://linux-hardware.org/?probe=34f134e5b0) | Jan 06, 2020 |
| ASUSTek       | H110M-E/M.2                 | [df17ba12c1](https://linux-hardware.org/?probe=df17ba12c1) | Jan 05, 2020 |
| Intel         | MAHOBAY                     | [30a583066a](https://linux-hardware.org/?probe=30a583066a) | Dec 29, 2019 |
| ONDA          | B320-IPC Ver:1.02           | [06286179c2](https://linux-hardware.org/?probe=06286179c2) | Dec 09, 2019 |
| MSI           | X99A XPOWER GAMING TITAN... | [65df5317a4](https://linux-hardware.org/?probe=65df5317a4) | Dec 06, 2019 |
| Dell          | 0XR1GT A00                  | [76dba7bb94](https://linux-hardware.org/?probe=76dba7bb94) | Nov 22, 2019 |
| ASUSTek       | M5A97                       | [ac3e990070](https://linux-hardware.org/?probe=ac3e990070) | Nov 20, 2019 |
| ASUSTek       | M5A97                       | [742601efb5](https://linux-hardware.org/?probe=742601efb5) | Nov 20, 2019 |
| Gigabyte      | Z87P-D3                     | [db5a6d60dd](https://linux-hardware.org/?probe=db5a6d60dd) | Nov 17, 2019 |
| ASUSTek       | B75M-A                      | [bba74ed5a2](https://linux-hardware.org/?probe=bba74ed5a2) | Nov 15, 2019 |
| HP            | 843C                        | [e5e15df58d](https://linux-hardware.org/?probe=e5e15df58d) | Nov 14, 2019 |
| MSI           | X99A XPOWER GAMING TITAN... | [bda577e787](https://linux-hardware.org/?probe=bda577e787) | Nov 12, 2019 |
| Lenovo        | 3107 NOK                    | [8545691fd8](https://linux-hardware.org/?probe=8545691fd8) | Oct 24, 2019 |
| MSI           | Z370 GAMING PRO CARBON A... | [30939907c1](https://linux-hardware.org/?probe=30939907c1) | Oct 13, 2019 |
| MSI           | Z370 GAMING PRO CARBON A... | [6b0db76cfd](https://linux-hardware.org/?probe=6b0db76cfd) | Oct 12, 2019 |
| ASUSTek       | Z8NA-D6                     | [5eab0577d3](https://linux-hardware.org/?probe=5eab0577d3) | Sep 28, 2019 |
| ASUSTek       | B85M-G PLUS/USB             | [174aed26d5](https://linux-hardware.org/?probe=174aed26d5) | Sep 27, 2019 |
| Lenovo        | QiTianM6900                 | [670fee2c10](https://linux-hardware.org/?probe=670fee2c10) | Sep 20, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [9f0b99fb29](https://linux-hardware.org/?probe=9f0b99fb29) | Sep 03, 2019 |
| Lenovo        | 36EB SDK0L77769 WIN 3423... | [5697eebc76](https://linux-hardware.org/?probe=5697eebc76) | Sep 02, 2019 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5652e9e755](https://linux-hardware.org/?probe=5652e9e755) | Aug 31, 2019 |
| Gigabyte      | Z270-HD3-CF                 | [1245fd6da5](https://linux-hardware.org/?probe=1245fd6da5) | Aug 30, 2019 |
| HP            | 81C7 MVB 0C                 | [931ea9a398](https://linux-hardware.org/?probe=931ea9a398) | Aug 27, 2019 |
| Dell          | 0GDG8Y A00                  | [a055c74af6](https://linux-hardware.org/?probe=a055c74af6) | Aug 18, 2019 |
| Gigabyte      | M68M-S2P                    | [0decbcaa1f](https://linux-hardware.org/?probe=0decbcaa1f) | Aug 16, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [ee8b6a4998](https://linux-hardware.org/?probe=ee8b6a4998) | Aug 14, 2019 |
| ASRock        | X470 Gaming-ITX/ac          | [641383210d](https://linux-hardware.org/?probe=641383210d) | Aug 12, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [e87b327f29](https://linux-hardware.org/?probe=e87b327f29) | Aug 11, 2019 |
| AMI           | PB_1900A                    | [2c3f429517](https://linux-hardware.org/?probe=2c3f429517) | Aug 10, 2019 |
| ASUSTek       | Z97-AR                      | [510b031ce9](https://linux-hardware.org/?probe=510b031ce9) | Aug 09, 2019 |
| Lenovo        | 36E7 SDK0L77769 WIN 3423... | [69d10d1093](https://linux-hardware.org/?probe=69d10d1093) | Aug 02, 2019 |
| Dell          | 0N9Y46 A00                  | [3548830389](https://linux-hardware.org/?probe=3548830389) | Jul 23, 2019 |
| Gigabyte      | B250M-D3V-CF                | [cba535c695](https://linux-hardware.org/?probe=cba535c695) | Jul 18, 2019 |
| HP            | 0B10H                       | [758924e4f2](https://linux-hardware.org/?probe=758924e4f2) | Jul 08, 2019 |
| Lenovo        | MAHOBAY NOK                 | [74dfe126d0](https://linux-hardware.org/?probe=74dfe126d0) | Jul 04, 2019 |
| Dell          | 0DNKMN A00                  | [24870345d1](https://linux-hardware.org/?probe=24870345d1) | Jun 25, 2019 |
| Dell          | 0DNKMN A00                  | [44e012b7fb](https://linux-hardware.org/?probe=44e012b7fb) | Jun 25, 2019 |
| Dell          | 0C96W1 A03                  | [3d80eacdfc](https://linux-hardware.org/?probe=3d80eacdfc) | Jun 18, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [579eebbcea](https://linux-hardware.org/?probe=579eebbcea) | Jun 07, 2019 |
| ASUSTek       | P8P67 LE                    | [63f1b6d26c](https://linux-hardware.org/?probe=63f1b6d26c) | Jun 06, 2019 |
| ASUSTek       | P8P67 LE                    | [928d66c1a0](https://linux-hardware.org/?probe=928d66c1a0) | Jun 06, 2019 |
| ASUSTek       | P8P67 LE                    | [7ece60be1d](https://linux-hardware.org/?probe=7ece60be1d) | Jun 05, 2019 |
| ASUSTek       | P8P67 LE                    | [83a1805c76](https://linux-hardware.org/?probe=83a1805c76) | Jun 05, 2019 |
| Lenovo        | ZHENGJIUZHE REN7000-28IC... | [1b85d8db4e](https://linux-hardware.org/?probe=1b85d8db4e) | Jun 04, 2019 |
| Gigabyte      | B85M-D2V-SI                 | [6be6da3a8e](https://linux-hardware.org/?probe=6be6da3a8e) | May 31, 2019 |
| Gigabyte      | B85M-D2V-SI                 | [900bc7e93c](https://linux-hardware.org/?probe=900bc7e93c) | May 31, 2019 |
| ASUSTek       | PRIME H310T                 | [851b9539e3](https://linux-hardware.org/?probe=851b9539e3) | May 24, 2019 |
| Dell          | 0XFWHV A00                  | [6dac78db97](https://linux-hardware.org/?probe=6dac78db97) | May 23, 2019 |
| Dell          | 0XFWHV A00                  | [82e6a2d735](https://linux-hardware.org/?probe=82e6a2d735) | May 19, 2019 |
| ASUSTek       | P6X58D PREMIUM              | [e9440445bc](https://linux-hardware.org/?probe=e9440445bc) | May 09, 2019 |
| Gigabyte      | B85N PHOENIX-CF             | [734eb3795e](https://linux-hardware.org/?probe=734eb3795e) | May 08, 2019 |
| ASUSTek       | M2A-VM                      | [3a02e6759d](https://linux-hardware.org/?probe=3a02e6759d) | May 08, 2019 |
| ASUSTek       | H61M-E                      | [6f9f39bbb6](https://linux-hardware.org/?probe=6f9f39bbb6) | May 07, 2019 |
| ASUSTek       | M2A-VM                      | [ac318056f7](https://linux-hardware.org/?probe=ac318056f7) | May 07, 2019 |
| Acer          | Aspire TC-606               | [5de5deb65e](https://linux-hardware.org/?probe=5de5deb65e) | May 06, 2019 |
| Lenovo        | SHARKBAY NOK                | [8df3c6b792](https://linux-hardware.org/?probe=8df3c6b792) | May 06, 2019 |
| Acer          | Aspire TC-606               | [1900e5ff06](https://linux-hardware.org/?probe=1900e5ff06) | May 06, 2019 |
| Gigabyte      | H270N-WIFI-CF               | [61bd5624bb](https://linux-hardware.org/?probe=61bd5624bb) | Apr 30, 2019 |
| Gigabyte      | H270N-WIFI-CF               | [b0a660db1e](https://linux-hardware.org/?probe=b0a660db1e) | Apr 23, 2019 |
| Gigabyte      | H270N-WIFI-CF               | [3fd02cfa82](https://linux-hardware.org/?probe=3fd02cfa82) | Apr 23, 2019 |
| ASUSTek       | B85M-G PLUS/USB             | [8f686df361](https://linux-hardware.org/?probe=8f686df361) | Apr 15, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [6a9582e524](https://linux-hardware.org/?probe=6a9582e524) | Apr 10, 2019 |
| ASRock        | B360M-HDV                   | [59151791cf](https://linux-hardware.org/?probe=59151791cf) | Apr 09, 2019 |
| Gigabyte      | B150M-Power2-EC-CF          | [68b2380c53](https://linux-hardware.org/?probe=68b2380c53) | Apr 05, 2019 |
| Gigabyte      | Z170X-Gaming 5              | [4efc7fbdc6](https://linux-hardware.org/?probe=4efc7fbdc6) | Apr 01, 2019 |
| Lenovo        | SHARKBAY NOK                | [14cba25e3e](https://linux-hardware.org/?probe=14cba25e3e) | Apr 01, 2019 |
| Lenovo        | 1030 SBB0J05441 WIN 3305... | [92262238c3](https://linux-hardware.org/?probe=92262238c3) | Mar 28, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [175525d48c](https://linux-hardware.org/?probe=175525d48c) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [dccca67c2e](https://linux-hardware.org/?probe=dccca67c2e) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [d0787d5045](https://linux-hardware.org/?probe=d0787d5045) | Mar 25, 2019 |
| Lenovo        | 36E7 SDK0L77767 WIN 3423... | [80816fc39e](https://linux-hardware.org/?probe=80816fc39e) | Mar 25, 2019 |
| Gigabyte      | Z87-HD3                     | [050c0abdc8](https://linux-hardware.org/?probe=050c0abdc8) | Mar 18, 2019 |
| ASUSTek       | PRIME Z370-P II             | [0b6eea7daa](https://linux-hardware.org/?probe=0b6eea7daa) | Mar 15, 2019 |
| Yeston Dig... | YESTON A78L Policeman V3... | [3a74ed7842](https://linux-hardware.org/?probe=3a74ed7842) | Mar 12, 2019 |
| Yeston Dig... | YESTON A78L Policeman V3... | [3c900dd5ac](https://linux-hardware.org/?probe=3c900dd5ac) | Mar 12, 2019 |
| Gigabyte      | Z87-HD3                     | [a4ad17d97c](https://linux-hardware.org/?probe=a4ad17d97c) | Mar 02, 2019 |
| ASUSTek       | PRIME Z370-A                | [a9e837c9eb](https://linux-hardware.org/?probe=a9e837c9eb) | Feb 08, 2019 |
| Lenovo        | 36E7 SDK0L77769 WIN 3423... | [1b722df896](https://linux-hardware.org/?probe=1b722df896) | Jan 21, 2019 |
| ASUSTek       | PRIME B450M-A               | [e077ae4d59](https://linux-hardware.org/?probe=e077ae4d59) | Jan 20, 2019 |
| HP            | 2B4F                        | [188b0e90bc](https://linux-hardware.org/?probe=188b0e90bc) | Jan 08, 2019 |
| Dell          | 077RRV A00                  | [c7b9c0beb8](https://linux-hardware.org/?probe=c7b9c0beb8) | Dec 29, 2018 |
| Dell          | 077RRV A00                  | [88d3983de4](https://linux-hardware.org/?probe=88d3983de4) | Dec 29, 2018 |
| ASUSTek       | B85M-G PLUS/USB             | [cbb464c414](https://linux-hardware.org/?probe=cbb464c414) | Dec 04, 2018 |
| Lenovo        | 3102 SDK0L77769 WIN 3423... | [2143ae0253](https://linux-hardware.org/?probe=2143ae0253) | Nov 13, 2018 |
| Huanan        | X79 PLUS V6.11              | [0a36000504](https://linux-hardware.org/?probe=0a36000504) | Nov 05, 2018 |
| Huanan        | X79 V1.4                    | [1204ed863a](https://linux-hardware.org/?probe=1204ed863a) | Oct 29, 2018 |
| Lenovo        | 36C5 SDK0L77767 WIN 3423... | [73b72b86b8](https://linux-hardware.org/?probe=73b72b86b8) | Oct 29, 2018 |
| Gigabyte      | F2A88XM-D3H                 | [94d087771b](https://linux-hardware.org/?probe=94d087771b) | Sep 24, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/China/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 57       | 12.75%  |
| Ubuntu 18.04       | 50       | 11.19%  |
| Ubuntu 22.04       | 25       | 5.59%   |
| Debian 11          | 19       | 4.25%   |
| Arch               | 19       | 4.25%   |
| Arch Rolling       | 15       | 3.36%   |
| Ubuntu 16.04       | 12       | 2.68%   |
| Ubuntu 19.04       | 11       | 2.46%   |
| UOS 20             | 10       | 2.24%   |
| OpenMandriva 4.3   | 10       | 2.24%   |
| Debian 10          | 9        | 2.01%   |
| Ubuntu 21.04       | 8        | 1.79%   |
| Ubuntu 19.10       | 6        | 1.34%   |
| OpenMandriva 23.03 | 6        | 1.34%   |
| Manjaro            | 6        | 1.34%   |
| Debian 8           | 6        | 1.34%   |
| Ubuntu Unity 16.04 | 5        | 1.12%   |
| Ubuntu 21.10       | 5        | 1.12%   |
| OpenMandriva 4.2   | 5        | 1.12%   |
| Debian Unstable    | 5        | 1.12%   |
| Ubuntu 18.10       | 4        | 0.89%   |
| OpenMandriva 4.50  | 4        | 0.89%   |
| KDE neon 20.04     | 4        | 0.89%   |
| Fedora 36          | 4        | 0.89%   |
| Fedora 32          | 4        | 0.89%   |
| Debian 12          | 4        | 0.89%   |
| CentOS 7           | 4        | 0.89%   |
| Atz 11.7           | 4        | 0.89%   |
| Zorin 16           | 3        | 0.67%   |
| Ubuntu 23.04       | 3        | 0.67%   |
| Ubuntu 20.10       | 3        | 0.67%   |
| Linux Mint 20.3    | 3        | 0.67%   |
| Linux Mint 20.2    | 3        | 0.67%   |
| Gentoo 2.7         | 3        | 0.67%   |
| Fedora 38          | 3        | 0.67%   |
| Debian 9           | 3        | 0.67%   |
| Debian 7           | 3        | 0.67%   |
| CentOS 8           | 3        | 0.67%   |
| Atz 11.5           | 3        | 0.67%   |
| ArcoLinux Rolling  | 3        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 180      | 41.86%  |
| Debian           | 50       | 11.63%  |
| Arch             | 34       | 7.91%   |
| OpenMandriva     | 28       | 6.51%   |
| Manjaro          | 14       | 3.26%   |
| Deepin           | 14       | 3.26%   |
| Linux Mint       | 13       | 3.02%   |
| Fedora           | 13       | 3.02%   |
| Gentoo           | 8        | 1.86%   |
| CentOS           | 8        | 1.86%   |
| Ubuntu Unity     | 7        | 1.63%   |
| Atz              | 6        | 1.4%    |
| KDE neon         | 5        | 1.16%   |
| Xubuntu          | 4        | 0.93%   |
| ROSA             | 4        | 0.93%   |
| ArcoLinux        | 4        | 0.93%   |
| Zorin            | 3        | 0.7%    |
| Pop!_OS          | 3        | 0.7%    |
| Clear Linux      | 3        | 0.7%    |
| openSUSE         | 2        | 0.47%   |
| NFS Desktop      | 2        | 0.47%   |
| Loongnix         | 2        | 0.47%   |
| Kubuntu          | 2        | 0.47%   |
| Elementary       | 2        | 0.47%   |
| Ubuntu Kylin     | 1        | 0.23%   |
| Trisquel         | 1        | 0.23%   |
| Slackware        | 1        | 0.23%   |
| RHEL             | 1        | 0.23%   |
| RedFlag          | 1        | 0.23%   |
| RED              | 1        | 0.23%   |
| Parabola         | 1        | 0.23%   |
| org.kde.Platform | 1        | 0.23%   |
| OpenWrt          | 1        | 0.23%   |
| OpenEuler        | 1        | 0.23%   |
| LFS              | 1        | 0.23%   |
| Kylin            | 1        | 0.23%   |
| Endless          | 1        | 0.23%   |
| Devuan           | 1        | 0.23%   |
| BlackPanther     | 1        | 0.23%   |
| AOSC OS          | 1        | 0.23%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003            | 9        | 1.92%   |
| 6.2.6-desktop-1omv2390             | 6        | 1.28%   |
| 5.15.0-56-generic                  | 6        | 1.28%   |
| 5.15.0-52-generic                  | 6        | 1.28%   |
| 5.0.0-23-generic                   | 6        | 1.28%   |
| 4.15.0-142-generic                 | 6        | 1.28%   |
| 5.13.0-22-generic                  | 5        | 1.07%   |
| 5.10.14-desktop-1omv4002           | 5        | 1.07%   |
| 6.2.0-26-generic                   | 4        | 0.85%   |
| 5.4.0-58-generic                   | 4        | 0.85%   |
| 5.13.0-30-generic                  | 4        | 0.85%   |
| 5.12.4-desktop-1omv4050            | 4        | 0.85%   |
| 5.11.0-43-generic                  | 4        | 0.85%   |
| 5.10.0-22-rt-amd64                 | 4        | 0.85%   |
| 5.0.0-25-generic                   | 4        | 0.85%   |
| 4.19.147-rivoreo-amd64             | 4        | 0.85%   |
| 4.18.0-16-generic                  | 4        | 0.85%   |
| 4.1.42-rivoreo-powerpc64-largepage | 4        | 0.85%   |
| 4.1.42-rivoreo-powerpc64           | 4        | 0.85%   |
| 5.8.0-50-generic                   | 3        | 0.64%   |
| 5.4.0-74-generic                   | 3        | 0.64%   |
| 5.4.0-42-generic                   | 3        | 0.64%   |
| 5.19.0-46-generic                  | 3        | 0.64%   |
| 5.15.0-67-generic                  | 3        | 0.64%   |
| 5.15.0-46-generic                  | 3        | 0.64%   |
| 5.11.0-41-generic                  | 3        | 0.64%   |
| 5.10.35-gentoo                     | 3        | 0.64%   |
| 5.10.0-amd64-desktop               | 3        | 0.64%   |
| 5.10.0-18-amd64                    | 3        | 0.64%   |
| 4.19.0-amd64-desktop               | 3        | 0.64%   |
| 4.18.0-10-generic                  | 3        | 0.64%   |
| 4.15.0-58-generic                  | 3        | 0.64%   |
| 6.4.3-arch1-2                      | 2        | 0.43%   |
| 6.4.10-arch1-1                     | 2        | 0.43%   |
| 6.2.0-20-generic                   | 2        | 0.43%   |
| 5.8.0-63-generic                   | 2        | 0.43%   |
| 5.8.0-43-generic                   | 2        | 0.43%   |
| 5.4.0-84-generic                   | 2        | 0.43%   |
| 5.4.0-73-generic                   | 2        | 0.43%   |
| 5.4.0-54-generic                   | 2        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 48       | 10.67%  |
| 4.15.0   | 31       | 6.89%   |
| 5.15.0   | 30       | 6.67%   |
| 5.0.0    | 23       | 5.11%   |
| 5.10.0   | 21       | 4.67%   |
| 5.11.0   | 20       | 4.44%   |
| 4.18.0   | 18       | 4%      |
| 5.13.0   | 16       | 3.56%   |
| 5.8.0    | 13       | 2.89%   |
| 4.19.0   | 11       | 2.44%   |
| 5.19.0   | 9        | 2%      |
| 5.16.7   | 9        | 2%      |
| 6.2.0    | 7        | 1.56%   |
| 5.3.0    | 7        | 1.56%   |
| 4.1.42   | 7        | 1.56%   |
| 6.2.6    | 6        | 1.33%   |
| 6.1.0    | 6        | 1.33%   |
| 5.10.14  | 5        | 1.11%   |
| 5.14.0   | 4        | 0.89%   |
| 5.12.4   | 4        | 0.89%   |
| 4.19.147 | 4        | 0.89%   |
| 6.4.10   | 3        | 0.67%   |
| 5.16.0   | 3        | 0.67%   |
| 5.10.35  | 3        | 0.67%   |
| 4.9.0    | 3        | 0.67%   |
| 4.19.271 | 3        | 0.67%   |
| 3.10.0   | 3        | 0.67%   |
| 6.4.3    | 2        | 0.44%   |
| 6.3.5    | 2        | 0.44%   |
| 6.1.11   | 2        | 0.44%   |
| 5.9.8    | 2        | 0.44%   |
| 5.9.10   | 2        | 0.44%   |
| 5.7.7    | 2        | 0.44%   |
| 5.6.14   | 2        | 0.44%   |
| 5.18.16  | 2        | 0.44%   |
| 5.18.12  | 2        | 0.44%   |
| 5.18.0   | 2        | 0.44%   |
| 5.17.0   | 2        | 0.44%   |
| 5.16.13  | 2        | 0.44%   |
| 5.15.77  | 2        | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 58       | 12.95%  |
| 5.15    | 46       | 10.27%  |
| 5.10    | 44       | 9.82%   |
| 4.15    | 31       | 6.92%   |
| 5.0     | 25       | 5.58%   |
| 5.11    | 22       | 4.91%   |
| 5.13    | 19       | 4.24%   |
| 4.19    | 19       | 4.24%   |
| 4.18    | 18       | 4.02%   |
| 6.2     | 15       | 3.35%   |
| 5.8     | 14       | 3.13%   |
| 5.16    | 14       | 3.13%   |
| 6.1     | 12       | 2.68%   |
| 5.19    | 11       | 2.46%   |
| 5.18    | 9        | 2.01%   |
| 6.4     | 8        | 1.79%   |
| 5.9     | 8        | 1.79%   |
| 5.17    | 8        | 1.79%   |
| 5.12    | 8        | 1.79%   |
| 5.3     | 7        | 1.56%   |
| 5.14    | 7        | 1.56%   |
| 4.1     | 7        | 1.56%   |
| 5.6     | 5        | 1.12%   |
| 4.9     | 5        | 1.12%   |
| 6.3     | 4        | 0.89%   |
| 5.7     | 4        | 0.89%   |
| 4.4     | 3        | 0.67%   |
| 3.10    | 3        | 0.67%   |
| 5.1     | 2        | 0.45%   |
| 4.13    | 2        | 0.45%   |
| 2.6     | 2        | 0.45%   |
| 6.5     | 1        | 0.22%   |
| 6.0     | 1        | 0.22%   |
| 5.5     | 1        | 0.22%   |
| 5.2     | 1        | 0.22%   |
| 4.20    | 1        | 0.22%   |
| 4.14    | 1        | 0.22%   |
| 3.4     | 1        | 0.22%   |
| 2.6.16  | 1        | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 396      | 93.18%  |
| ppc64       | 7        | 1.65%   |
| riscv64     | 5        | 1.18%   |
| aarch64     | 4        | 0.94%   |
| loongarch64 | 3        | 0.71%   |
| ppc64le     | 2        | 0.47%   |
| i686        | 2        | 0.47%   |
| sparc64     | 1        | 0.24%   |
| sh4a        | 1        | 0.24%   |
| ppc         | 1        | 0.24%   |
| mips64      | 1        | 0.24%   |
| i586        | 1        | 0.24%   |
| armv7l      | 1        | 0.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 171      | 39.22%  |
| Unknown       | 112      | 25.69%  |
| KDE5          | 53       | 12.16%  |
| XFCE          | 38       | 8.72%   |
| Deepin        | 13       | 2.98%   |
| X-Cinnamon    | 8        | 1.83%   |
| KDE           | 8        | 1.83%   |
| Unity         | 7        | 1.61%   |
| MATE          | 6        | 1.38%   |
| UKUI          | 2        | 0.46%   |
| sway          | 2        | 0.46%   |
| Pantheon      | 2        | 0.46%   |
| LXDE          | 2        | 0.46%   |
| KDE4          | 2        | 0.46%   |
| i3            | 2        | 0.46%   |
| Cinnamon      | 2        | 0.46%   |
| Wayfire       | 1        | 0.23%   |
| LXQt          | 1        | 0.23%   |
| GNOME Classic | 1        | 0.23%   |
| default       | 1        | 0.23%   |
| Budgie        | 1        | 0.23%   |
| awesome       | 1        | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 284      | 65.59%  |
| Wayland | 56       | 12.93%  |
| Unknown | 49       | 11.32%  |
| Tty     | 44       | 10.16%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 214      | 49.77%  |
| GDM3    | 57       | 13.26%  |
| SDDM    | 50       | 11.63%  |
| LightDM | 50       | 11.63%  |
| GDM     | 49       | 11.4%   |
| TDM     | 6        | 1.4%    |
| KDM     | 2        | 0.47%   |
| SLiM    | 1        | 0.23%   |
| LXDM    | 1        | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| zh_CN       | 182      | 42.13%  |
| en_US       | 138      | 31.94%  |
| Unknown     | 74       | 17.13%  |
| C           | 26       | 6.02%   |
| en_HK       | 4        | 0.93%   |
| en_GB       | 2        | 0.46%   |
| zh_TW       | 1        | 0.23%   |
| ru_RU       | 1        | 0.23%   |
| ja_JP       | 1        | 0.23%   |
| en_US.utf-8 | 1        | 0.23%   |
| en_SG       | 1        | 0.23%   |
| en_AU       | 1        | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 231      | 53.97%  |
| BIOS | 197      | 46.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Desktops | Percent |
|------------|----------|---------|
| Ext4       | 331      | 76.8%   |
| Btrfs      | 27       | 6.26%   |
| Overlay    | 26       | 6.03%   |
| Xfs        | 19       | 4.41%   |
| Unknown    | 10       | 2.32%   |
| Tmpfs      | 7        | 1.62%   |
| Zfs        | 6        | 1.39%   |
| Rootfs     | 3        | 0.7%    |
| Reiserfs   | 1        | 0.23%   |
| Fuse.sshfs | 1        | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 194      | 45.33%  |
| Unknown | 175      | 40.89%  |
| MBR     | 59       | 13.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 335      | 77.91%  |
| Yes       | 95       | 22.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 268      | 62.62%  |
| Yes       | 160      | 37.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 96       | 22.59%  |
| Lenovo                               | 54       | 12.71%  |
| Gigabyte Technology                  | 53       | 12.47%  |
| MSI                                  | 38       | 8.94%   |
| Dell                                 | 31       | 7.29%   |
| Unknown                              | 27       | 6.35%   |
| ASRock                               | 16       | 3.76%   |
| Hewlett-Packard                      | 14       | 3.29%   |
| Intel                                | 10       | 2.35%   |
| TSINGHUA TONGFANG COMPUTER           | 8        | 1.88%   |
| Huanan                               | 6        | 1.41%   |
| Colorful Technology                  | 6        | 1.41%   |
| OEM                                  | 5        | 1.18%   |
| Loongson                             | 4        | 0.94%   |
| AZW                                  | 4        | 0.94%   |
| ONDA                                 | 3        | 0.71%   |
| Biostar                              | 3        | 0.71%   |
| MAXSUN                               | 2        | 0.47%   |
| HUAWEI                               | 2        | 0.47%   |
| Google                               | 2        | 0.47%   |
| ECS                                  | 2        | 0.47%   |
| AMD                                  | 2        | 0.47%   |
| Acer                                 | 2        | 0.47%   |
| Yeston Digital Technology            | 1        | 0.24%   |
| YANYU                                | 1        | 0.24%   |
| Yanling                              | 1        | 0.24%   |
| X79-1356                             | 1        | 0.24%   |
| Win element                          | 1        | 0.24%   |
| WeiBu                                | 1        | 0.24%   |
| UGREEN                               | 1        | 0.24%   |
| SYWZ                                 | 1        | 0.24%   |
| Supermicro                           | 1        | 0.24%   |
| Soyo                                 | 1        | 0.24%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.24%   |
| Shanghai Zhaoxin Semiconductor       | 1        | 0.24%   |
| Sapphire                             | 1        | 0.24%   |
| retsamarret                          | 1        | 0.24%   |
| RBQ                                  | 1        | 0.24%   |
| Pegatron                             | 1        | 0.24%   |
| NORCO                                | 1        | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Unknown                                   | 32       | 7.53%   |
| ASUS All Series                           | 14       | 3.29%   |
| TSINGHUA TONGFANG COMPUTER E500           | 8        | 1.88%   |
| MSI MS-7B89                               | 6        | 1.41%   |
| ASUS TUF Gaming B550M-PLUS                | 5        | 1.18%   |
| MSI MS-7C94                               | 4        | 0.94%   |
| Lenovo ThinkStation P520 30BFSG3Y00       | 4        | 0.94%   |
| Gigabyte X299 AORUS Gaming 7              | 3        | 0.71%   |
| Dell Precision 3660                       | 3        | 0.71%   |
| ASUS ROG STRIX X299-E GAMING              | 3        | 0.71%   |
| ASUS M5A78L-M LX3 PLUS                    | 3        | 0.71%   |
| MSI MS-7A40                               | 2        | 0.47%   |
| Lenovo YangTianT4900c-00 90ETCTO1WW       | 2        | 0.47%   |
| Lenovo ThinkStation P300 10DACTO1WW       | 2        | 0.47%   |
| Lenovo ThinkCentre M910t-N000 10N9CTO1WW  | 2        | 0.47%   |
| Gigabyte Z87P-D3                          | 2        | 0.47%   |
| Gigabyte X299 UD4 Pro                     | 2        | 0.47%   |
| Gigabyte F2A88XM-D3H                      | 2        | 0.47%   |
| Gigabyte B85M-D2V-SI                      | 2        | 0.47%   |
| Gigabyte B450M GAMING                     | 2        | 0.47%   |
| Dell Precision 3650 Tower                 | 2        | 0.47%   |
| Dell OptiPlex 9020                        | 2        | 0.47%   |
| Dell OptiPlex 7060                        | 2        | 0.47%   |
| Dell OptiPlex 7040                        | 2        | 0.47%   |
| Dell OptiPlex 7010                        | 2        | 0.47%   |
| ASUS Z170-A                               | 2        | 0.47%   |
| ASUS TUF Gaming Z590-PLUS WIFI            | 2        | 0.47%   |
| ASUS TUF Gaming X570-PLUS                 | 2        | 0.47%   |
| ASUS TUF B450M-PLUS GAMING                | 2        | 0.47%   |
| ASUS PRIME Z370-A                         | 2        | 0.47%   |
| ASUS PRIME B450M-A                        | 2        | 0.47%   |
| ASRock Z170 Gaming K4                     | 2        | 0.47%   |
| ASRock A320M-HDV                          | 2        | 0.47%   |
| Acer Aspire TC-606                        | 2        | 0.47%   |
| Yeston Digital YESTON A78L Policeman V3.1 | 1        | 0.24%   |
| YANYU EPIC-C57                            | 1        | 0.24%   |
| Yanling YL-KBRL2 Series                   | 1        | 0.24%   |
| Win element M600                          | 1        | 0.24%   |
| WeiBu ADL-N                               | 1        | 0.24%   |
| UGREEN DX4600                             | 1        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 32       | 7.53%   |
| ASUS PRIME                      | 20       | 4.71%   |
| ASUS TUF                        | 19       | 4.47%   |
| Dell OptiPlex                   | 18       | 4.24%   |
| Lenovo ThinkCentre              | 14       | 3.29%   |
| ASUS All                        | 14       | 3.29%   |
| ASUS ROG                        | 12       | 2.82%   |
| Lenovo ThinkStation             | 10       | 2.35%   |
| TSINGHUA TONGFANG COMPUTER E500 | 8        | 1.88%   |
| Dell Precision                  | 8        | 1.88%   |
| MSI MS-7B89                     | 6        | 1.41%   |
| Gigabyte X299                   | 5        | 1.18%   |
| MSI MS-7C94                     | 4        | 0.94%   |
| Lenovo ZHENGJIUZHE              | 4        | 0.94%   |
| Huanan X79                      | 3        | 0.71%   |
| HP ProDesk                      | 3        | 0.71%   |
| Gigabyte B450M                  | 3        | 0.71%   |
| Dell Inspiron                   | 3        | 0.71%   |
| ASUS M5A78L-M                   | 3        | 0.71%   |
| MSI MS-7A40                     | 2        | 0.47%   |
| Lenovo YangTianT4900v-00        | 2        | 0.47%   |
| Lenovo YangTianT4900c-00        | 2        | 0.47%   |
| Lenovo IdeaCentre               | 2        | 0.47%   |
| Gigabyte Z87P-D3                | 2        | 0.47%   |
| Gigabyte X570                   | 2        | 0.47%   |
| Gigabyte F2A88XM-D3H            | 2        | 0.47%   |
| Gigabyte B85M-D2V-SI            | 2        | 0.47%   |
| Gigabyte B450                   | 2        | 0.47%   |
| Dell Vostro                     | 2        | 0.47%   |
| Colorful CVN                    | 2        | 0.47%   |
| ASUS Z170-A                     | 2        | 0.47%   |
| ASUS PRO                        | 2        | 0.47%   |
| ASUS M5A97                      | 2        | 0.47%   |
| ASRock Z170                     | 2        | 0.47%   |
| ASRock X470                     | 2        | 0.47%   |
| ASRock A320M-HDV                | 2        | 0.47%   |
| Acer Aspire                     | 2        | 0.47%   |
| Yeston Digital YESTON           | 1        | 0.24%   |
| YANYU EPIC-C57                  | 1        | 0.24%   |
| Yanling YL-KBRL2                | 1        | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 60       | 14.12%  |
| 2020    | 48       | 11.29%  |
| 2017    | 39       | 9.18%   |
| 2019    | 38       | 8.94%   |
| 2021    | 34       | 8%      |
| 2015    | 29       | 6.82%   |
| 2012    | 27       | 6.35%   |
| 2013    | 26       | 6.12%   |
| 2022    | 25       | 5.88%   |
| Unknown | 23       | 5.41%   |
| 2014    | 19       | 4.47%   |
| 2016    | 17       | 4%      |
| 2011    | 11       | 2.59%   |
| 2010    | 9        | 2.12%   |
| 2023    | 7        | 1.65%   |
| 2009    | 6        | 1.41%   |
| 2008    | 4        | 0.94%   |
| 2007    | 3        | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 425      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 416      | 97.88%  |
| Enabled  | 9        | 2.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 423      | 99.53%  |
| Yes  | 2        | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 103      | 23.9%   |
| 32.01-64.0      | 82       | 19.03%  |
| 4.01-8.0        | 68       | 15.78%  |
| 8.01-16.0       | 68       | 15.78%  |
| 64.01-256.0     | 40       | 9.28%   |
| 3.01-4.0        | 33       | 7.66%   |
| Unknown         | 13       | 3.02%   |
| 24.01-32.0      | 11       | 2.55%   |
| 1.01-2.0        | 5        | 1.16%   |
| 0.51-1.0        | 3        | 0.7%    |
| 0.01-0.5        | 2        | 0.46%   |
| More than 256.0 | 1        | 0.23%   |
| 2.01-3.0        | 1        | 0.23%   |
| 0               | 1        | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 142      | 31.21%  |
| 2.01-3.0    | 106      | 23.3%   |
| 4.01-8.0    | 60       | 13.19%  |
| 3.01-4.0    | 54       | 11.87%  |
| 8.01-16.0   | 21       | 4.62%   |
| 0.51-1.0    | 20       | 4.4%    |
| Unknown     | 16       | 3.52%   |
| 0.01-0.5    | 15       | 3.3%    |
| 16.01-24.0  | 12       | 2.64%   |
| 32.01-64.0  | 3        | 0.66%   |
| 24.01-32.0  | 3        | 0.66%   |
| 64.01-256.0 | 3        | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 162      | 37.33%  |
| 2      | 148      | 34.1%   |
| 3      | 64       | 14.75%  |
| 4      | 27       | 6.22%   |
| 5      | 16       | 3.69%   |
| 0      | 7        | 1.61%   |
| 6      | 4        | 0.92%   |
| 9      | 2        | 0.46%   |
| 46     | 1        | 0.23%   |
| 11     | 1        | 0.23%   |
| 10     | 1        | 0.23%   |
| 8      | 1        | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 351      | 82.2%   |
| Yes       | 76       | 17.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 416      | 97.88%  |
| No        | 9        | 2.12%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 228      | 53.15%  |
| Yes       | 201      | 46.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 283      | 65.21%  |
| Yes       | 151      | 34.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| China   | 425      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Beijing          | 86       | 19.63%  |
| Shanghai         | 36       | 8.22%   |
| Shenzhen         | 34       | 7.76%   |
| Guangzhou        | 25       | 5.71%   |
| Hangzhou         | 22       | 5.02%   |
| Wuhan            | 16       | 3.65%   |
| Chengdu          | 12       | 2.74%   |
| Nanjing          | 10       | 2.28%   |
| Nanhao           | 9        | 2.05%   |
| Haidian          | 8        | 1.83%   |
| Xi'an            | 7        | 1.6%    |
| Bieligutai       | 7        | 1.6%    |
| Zhengzhou        | 6        | 1.37%   |
| Xiamen           | 6        | 1.37%   |
| Tianjin          | 6        | 1.37%   |
| Qingdao          | 6        | 1.37%   |
| Foshan           | 6        | 1.37%   |
| Chongqing        | 6        | 1.37%   |
| Xuhui            | 5        | 1.14%   |
| Jinan            | 5        | 1.14%   |
| Hefei            | 4        | 0.91%   |
| Suzhou           | 3        | 0.68%   |
| Shijiazhuang     | 3        | 0.68%   |
| Putuo            | 3        | 0.68%   |
| Jinrongjie       | 3        | 0.68%   |
| Changsha         | 3        | 0.68%   |
| Zhangzhou        | 2        | 0.46%   |
| Xicheng District | 2        | 0.46%   |
| Wuxi             | 2        | 0.46%   |
| Wulipu           | 2        | 0.46%   |
| Wuhu             | 2        | 0.46%   |
| Nanping          | 2        | 0.46%   |
| Nanning          | 2        | 0.46%   |
| Nanchang         | 2        | 0.46%   |
| Lanzhou          | 2        | 0.46%   |
| Langfang         | 2        | 0.46%   |
| Kunming          | 2        | 0.46%   |
| Huangpu          | 2        | 0.46%   |
| Hongkou          | 2        | 0.46%   |
| Hohhot           | 2        | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 139      | 189    | 18.17%  |
| Seagate                     | 139      | 271    | 18.17%  |
| Samsung Electronics         | 90       | 115    | 11.76%  |
| Toshiba                     | 39       | 57     | 5.1%    |
| SanDisk                     | 29       | 33     | 3.79%   |
| Kingston                    | 28       | 35     | 3.66%   |
| Intel                       | 21       | 28     | 2.75%   |
| Unknown                     | 17       | 26     | 2.22%   |
| Silicon Motion              | 17       | 21     | 2.22%   |
| HGST                        | 12       | 19     | 1.57%   |
| Plextor                     | 11       | 13     | 1.44%   |
| Hitachi                     | 10       | 16     | 1.31%   |
| Phison                      | 9        | 11     | 1.18%   |
| ZHITAI                      | 8        | 10     | 1.05%   |
| SK hynix                    | 8        | 8      | 1.05%   |
| FORESEE                     | 8        | 8      | 1.05%   |
| Crucial                     | 7        | 7      | 0.92%   |
| Yangtze Memory Technologies | 6        | 8      | 0.78%   |
| Micron Technology           | 6        | 7      | 0.78%   |
| Hewlett-Packard             | 6        | 8      | 0.78%   |
| GLOWAY                      | 6        | 9      | 0.78%   |
| Colorful                    | 6        | 8      | 0.78%   |
| Unknown                     | 6        | 9      | 0.78%   |
| Teclast                     | 5        | 5      | 0.65%   |
| LITEON                      | 5        | 7      | 0.65%   |
| Lenovo                      | 5        | 6      | 0.65%   |
| GALAX                       | 5        | 5      | 0.65%   |
| Netac                       | 4        | 5      | 0.52%   |
| Lite-On                     | 4        | 6      | 0.52%   |
| KIOXIA-EXCERIA              | 4        | 4      | 0.52%   |
| faspeed                     | 4        | 4      | 0.52%   |
| China                       | 4        | 4      | 0.52%   |
| A-DATA Technology           | 4        | 5      | 0.52%   |
| tigo                        | 3        | 3      | 0.39%   |
| MAXIO Technology (Hangzhou) | 3        | 3      | 0.39%   |
| KIOXIA                      | 3        | 3      | 0.39%   |
| Kingchuxing                 | 3        | 3      | 0.39%   |
| Fujitsu                     | 3        | 3      | 0.39%   |
| StoreJet                    | 2        | 2      | 0.26%   |
| ShineDisk                   | 2        | 2      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                              | 24       | 2.82%   |
| Seagate ST1000DM010-2EP102 1TB                        | 17       | 2%      |
| Seagate ST1000DM003-1SB102 1TB                        | 14       | 1.65%   |
| Seagate ST500DM002-1BD142 500GB                       | 10       | 1.18%   |
| Samsung SSD 860 EVO 500GB                             | 10       | 1.18%   |
| WDC WD10EZEX-08M2NA0 1TB                              | 8        | 0.94%   |
| Seagate ST6000NM0115-1YZ110 6TB                       | 8        | 0.94%   |
| Toshiba DT01ACA200 2TB                                | 7        | 0.82%   |
| Seagate ST3500418AS 500GB                             | 7        | 0.82%   |
| SanDisk NVMe SSD Drive 1TB                            | 7        | 0.82%   |
| WDC WD10EZEX-22MFCA0 1TB                              | 6        | 0.71%   |
| Seagate ST3000DM001-1ER166 3TB                        | 6        | 0.71%   |
| Kingston SA400S37480G 480GB SSD                       | 6        | 0.71%   |
| Unknown                                               | 6        | 0.71%   |
| WDC WDS100T2B0C-00PXH0 1TB                            | 5        | 0.59%   |
| Seagate ST300MM0008 304GB                             | 5        | 0.59%   |
| Seagate ST300MM0006 304GB                             | 5        | 0.59%   |
| Seagate ST3000DM008-2DM166 3TB                        | 5        | 0.59%   |
| Seagate ST2000DM006-2DM164 2TB                        | 5        | 0.59%   |
| Seagate ST1000DM003-1ER162 1TB                        | 5        | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 5        | 0.59%   |
| Toshiba TR200 480GB SSD                               | 4        | 0.47%   |
| Toshiba DT01ACA100 1TB                                | 4        | 0.47%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 4        | 0.47%   |
| Seagate ST3500413AS 500GB                             | 4        | 0.47%   |
| SanDisk NVMe SSD Drive 512GB                          | 4        | 0.47%   |
| Samsung SSD 850 EVO 250GB                             | 4        | 0.47%   |
| Samsung NVMe SSD Drive 128GB                          | 4        | 0.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 4        | 0.47%   |
| Plextor PX-256M8VC 256GB SSD                          | 4        | 0.47%   |
| ZHITAI SC001 Active 512GB SSD                         | 3        | 0.35%   |
| Yangtze Memory ZHITAI TiPlus5000 1TB                  | 3        | 0.35%   |
| WDC WDS500G2B0C-00PXH0 500GB                          | 3        | 0.35%   |
| WDC WD5000AAKX-0 500GB                                | 3        | 0.35%   |
| WDC WD30EZRZ-00GXCB0 3TB                              | 3        | 0.35%   |
| WDC WD20EZRX-00D8PB0 2TB                              | 3        | 0.35%   |
| Unknown SD64G  64GB                                   | 3        | 0.35%   |
| Toshiba Q300. 240GB SSD                               | 3        | 0.35%   |
| Toshiba DT01ACA300 3TB                                | 3        | 0.35%   |
| Toshiba DT01ACA100 LENOVO 1TB                         | 3        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 138      | 270    | 41.57%  |
| WDC                 | 123      | 163    | 37.05%  |
| Toshiba             | 30       | 42     | 9.04%   |
| HGST                | 12       | 19     | 3.61%   |
| Hitachi             | 10       | 16     | 3.01%   |
| Samsung Electronics | 5        | 5      | 1.51%   |
| Fujitsu             | 3        | 3      | 0.9%    |
| Unknown             | 2        | 3      | 0.6%    |
| SSK                 | 1        | 1      | 0.3%    |
| Pear 2TB            | 1        | 1      | 0.3%    |
| IBM H0              | 1        | 1      | 0.3%    |
| Hewlett-Packard     | 1        | 1      | 0.3%    |
| GOKE                | 1        | 1      | 0.3%    |
| FORESEE             | 1        | 1      | 0.3%    |
| External            | 1        | 2      | 0.3%    |
| ExcelStor           | 1        | 1      | 0.3%    |
| ACASIS              | 1        | 1      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 47       | 56     | 20.89%  |
| Kingston            | 19       | 24     | 8.44%   |
| Intel               | 12       | 18     | 5.33%   |
| Toshiba             | 11       | 13     | 4.89%   |
| SanDisk             | 10       | 11     | 4.44%   |
| Plextor             | 10       | 11     | 4.44%   |
| WDC                 | 6        | 7      | 2.67%   |
| ZHITAI              | 5        | 6      | 2.22%   |
| Teclast             | 5        | 5      | 2.22%   |
| LITEON              | 5        | 7      | 2.22%   |
| GLOWAY              | 5        | 8      | 2.22%   |
| GALAX               | 5        | 5      | 2.22%   |
| Crucial             | 5        | 5      | 2.22%   |
| Unknown             | 4        | 5      | 1.78%   |
| Lenovo              | 4        | 5      | 1.78%   |
| China               | 4        | 4      | 1.78%   |
| tigo                | 3        | 3      | 1.33%   |
| Netac               | 3        | 4      | 1.33%   |
| Micron Technology   | 3        | 4      | 1.33%   |
| Kingchuxing         | 3        | 3      | 1.33%   |
| FORESEE             | 3        | 3      | 1.33%   |
| Faspeed             | 3        | 3      | 1.33%   |
| A-DATA Technology   | 3        | 3      | 1.33%   |
| Unknown             | 3        | 5      | 1.33%   |
| StoreJet            | 2        | 2      | 0.89%   |
| Q200                | 2        | 5      | 0.89%   |
| Pear                | 2        | 8      | 0.89%   |
| OCZ                 | 2        | 2      | 0.89%   |
| KingShare           | 2        | 2      | 0.89%   |
| KINGBANK            | 2        | 2      | 0.89%   |
| Hewlett-Packard     | 2        | 4      | 0.89%   |
| Colorful            | 2        | 2      | 0.89%   |
| aigo                | 2        | 2      | 0.89%   |
| YANYU               | 1        | 1      | 0.44%   |
| Vaseky              | 1        | 1      | 0.44%   |
| UNIC2               | 1        | 1      | 0.44%   |
| Soyo                | 1        | 1      | 0.44%   |
| ShineDisk           | 1        | 1      | 0.44%   |
| Ramsta              | 1        | 1      | 0.44%   |
| Pioneer             | 1        | 1      | 0.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 270      | 531    | 40.85%  |
| SSD     | 190      | 276    | 28.74%  |
| NVMe    | 172      | 233    | 26.02%  |
| Unknown | 22       | 28     | 3.33%   |
| MMC     | 7        | 11     | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 349      | 774    | 62.21%  |
| NVMe | 171      | 232    | 30.48%  |
| SAS  | 34       | 62     | 6.06%   |
| MMC  | 7        | 11     | 1.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 224      | 378    | 44.89%  |
| 0.51-1.0   | 167      | 203    | 33.47%  |
| 1.01-2.0   | 42       | 62     | 8.42%   |
| 4.01-10.0  | 20       | 86     | 4.01%   |
| 2.01-3.0   | 18       | 31     | 3.61%   |
| 3.01-4.0   | 16       | 26     | 3.21%   |
| 10.01-20.0 | 12       | 21     | 2.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 101      | 22.95%  |
| 251-500        | 79       | 17.95%  |
| 501-1000       | 66       | 15%     |
| 1001-2000      | 46       | 10.45%  |
| More than 3000 | 36       | 8.18%   |
| 51-100         | 33       | 7.5%    |
| 1-20           | 23       | 5.23%   |
| Unknown        | 20       | 4.55%   |
| 21-50          | 18       | 4.09%   |
| 2001-3000      | 18       | 4.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 173      | 38.53%  |
| 101-250        | 66       | 14.7%   |
| 21-50          | 60       | 13.36%  |
| 51-100         | 38       | 8.46%   |
| 251-500        | 33       | 7.35%   |
| 501-1000       | 22       | 4.9%    |
| Unknown        | 20       | 4.45%   |
| 1001-2000      | 19       | 4.23%   |
| More than 3000 | 10       | 2.23%   |
| 2001-3000      | 8        | 1.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST31000524AS 1TB              | 2        | 2      | 5%      |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1        | 1      | 2.5%    |
| WDC WD5003ABYZ-011FA0 500GB           | 1        | 1      | 2.5%    |
| WDC WD5003ABYX-01WERA1 500GB          | 1        | 1      | 2.5%    |
| WDC WD5000AAKX-08ERMA0 500GB          | 1        | 1      | 2.5%    |
| WDC WD5000AAKX-083CA1 500GB           | 1        | 1      | 2.5%    |
| WDC WD5000AAKX-00PWEA0 500GB          | 1        | 1      | 2.5%    |
| WDC WD5000AAKX-0 500GB                | 1        | 1      | 2.5%    |
| WDC WD40EJRX-89AKWY0 4TB              | 1        | 3      | 2.5%    |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 2.5%    |
| WDC WD10JPVX-22JC3T0 1TB              | 1        | 1      | 2.5%    |
| WDC WD10JPLX-00MBPT1 1TB              | 1        | 2      | 2.5%    |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 2.5%    |
| WDC WD100EZAZ-11TDBA0 10TB            | 1        | 2      | 2.5%    |
| Toshiba DT01ACA300 3TB                | 1        | 1      | 2.5%    |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 2.5%    |
| Seagate ST980811AS 80GB               | 1        | 1      | 2.5%    |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1        | 1      | 2.5%    |
| Seagate ST500LT012-1DG142 500GB       | 1        | 1      | 2.5%    |
| Seagate ST500DM009-2DM14C 500GB       | 1        | 1      | 2.5%    |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 2.5%    |
| Seagate ST5000AS0011-1L5178 5TB       | 1        | 1      | 2.5%    |
| Seagate ST4000VX007-2DT166 4TB        | 1        | 1      | 2.5%    |
| Seagate ST3500413AS 500GB             | 1        | 1      | 2.5%    |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 2      | 2.5%    |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 2.5%    |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 2.5%    |
| Ramsta SSD S300 240GB                 | 1        | 1      | 2.5%    |
| Plextor PX-256M6S 256GB SSD           | 1        | 1      | 2.5%    |
| Intel SSDSC2KW256G8 256GB             | 1        | 1      | 2.5%    |
| Intel SSDSC2KW240H6 240GB             | 1        | 1      | 2.5%    |
| Intel SSDSC2BW360H6 360GB             | 1        | 1      | 2.5%    |
| Hewlett-Packard SSD EX900 250GB       | 1        | 1      | 2.5%    |
| GLOWAY VAL120GS3-S7 120GB SSD         | 1        | 4      | 2.5%    |
| GLOWAY FER120GS3-S7 120GB SSD         | 1        | 1      | 2.5%    |
| Fujitsu MJA2250BH G2 250GB            | 1        | 1      | 2.5%    |
| ExcelStor Technology J9250S 250GB     | 1        | 1      | 2.5%    |
| Crucial CT240M500SSD1 240GB           | 1        | 1      | 2.5%    |
| Colorful SL500 320GB SSD              | 1        | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 17     | 34.21%  |
| Seagate             | 9        | 12     | 23.68%  |
| Intel               | 3        | 3      | 7.89%   |
| Toshiba             | 2        | 2      | 5.26%   |
| Samsung Electronics | 2        | 2      | 5.26%   |
| GLOWAY              | 2        | 5      | 5.26%   |
| Ramsta              | 1        | 1      | 2.63%   |
| Plextor             | 1        | 1      | 2.63%   |
| Hewlett-Packard     | 1        | 1      | 2.63%   |
| Fujitsu             | 1        | 1      | 2.63%   |
| ExcelStor           | 1        | 1      | 2.63%   |
| Crucial             | 1        | 1      | 2.63%   |
| Colorful            | 1        | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor    | Desktops | Drives | Percent |
|-----------|----------|--------|---------|
| WDC       | 12       | 16     | 48%     |
| Seagate   | 9        | 12     | 36%     |
| Toshiba   | 2        | 2      | 8%      |
| Fujitsu   | 1        | 1      | 4%      |
| ExcelStor | 1        | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 32     | 68.57%  |
| SSD  | 9        | 14     | 25.71%  |
| NVMe | 2        | 2      | 5.71%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 20%     |
| Seagate ST31500341AS 1TB          | 1        | 1      | 20%     |
| Samsung Electronics HM160HI 160GB | 1        | 1      | 20%     |
| HGST HUH728080ALN600 8TB          | 1        | 1      | 20%     |
| Hewlett-Packard SSD S700 500GB    | 1        | 2      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 2      | 40%     |
| Samsung Electronics | 1        | 1      | 20%     |
| HGST                | 1        | 1      | 20%     |
| Hewlett-Packard     | 1        | 2      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 230      | 560    | 48.94%  |
| Works    | 203      | 465    | 43.19%  |
| Malfunc  | 32       | 48     | 6.81%   |
| Failed   | 5        | 6      | 1.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 292      | 46.28%  |
| AMD                              | 99       | 15.69%  |
| Samsung Electronics              | 41       | 6.5%    |
| SanDisk                          | 35       | 5.55%   |
| Silicon Motion                   | 24       | 3.8%    |
| ASMedia Technology               | 15       | 2.38%   |
| Marvell Technology Group         | 12       | 1.9%    |
| Phison Electronics               | 11       | 1.74%   |
| Kingston Technology Company      | 11       | 1.74%   |
| Yangtze Memory Technologies      | 8        | 1.27%   |
| SK hynix                         | 8        | 1.27%   |
| MAXIO Technology (Hangzhou)      | 7        | 1.11%   |
| KIOXIA                           | 5        | 0.79%   |
| IBM                              | 5        | 0.79%   |
| Broadcom / LSI                   | 5        | 0.79%   |
| Shenzhen Longsys Electronics     | 4        | 0.63%   |
| Loongson Technology              | 4        | 0.63%   |
| Lite-On Technology               | 4        | 0.63%   |
| JMicron Technology               | 4        | 0.63%   |
| Toshiba America Info Systems     | 3        | 0.48%   |
| Micron/Crucial Technology        | 3        | 0.48%   |
| Micron Technology                | 3        | 0.48%   |
| Huawei Technologies              | 3        | 0.48%   |
| Beijing Starblaze Technology     | 3        | 0.48%   |
| Zhaoxin                          | 2        | 0.32%   |
| Union Memory (Shenzhen)          | 2        | 0.32%   |
| Solid State Storage Technology   | 2        | 0.32%   |
| Silicon Image                    | 2        | 0.32%   |
| Realtek Semiconductor            | 2        | 0.32%   |
| Mylex                            | 2        | 0.32%   |
| ADATA Technology                 | 2        | 0.32%   |
| ULi Electronics                  | 1        | 0.16%   |
| Silicon Integrated Systems [SiS] | 1        | 0.16%   |
| Seagate Technology               | 1        | 0.16%   |
| Nvidia                           | 1        | 0.16%   |
| LSI Logic / Symbios Logic        | 1        | 0.16%   |
| HighPoint Technologies           | 1        | 0.16%   |
| Hefei DATANG Storage Technology  | 1        | 0.16%   |
| Adaptec                          | 1        | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 62       | 8.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 43       | 5.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 35       | 4.73%   |
| AMD 400 Series Chipset SATA Controller                                                  | 28       | 3.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 20       | 2.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 19       | 2.57%   |
| AMD 500 Series Chipset SATA Controller                                                  | 19       | 2.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18       | 2.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 17       | 2.3%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 16       | 2.16%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 15       | 2.03%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 15       | 2.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14       | 1.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12       | 1.62%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 12       | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 1.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11       | 1.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 10       | 1.35%   |
| Intel SATA Controller [RAID mode]                                                       | 10       | 1.35%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 9        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 1.08%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 7        | 0.95%   |
| Phison PS5013 E13 NVMe Controller                                                       | 7        | 0.95%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 0.95%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 6        | 0.81%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 6        | 0.81%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 0.81%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 6        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 0.81%   |
| AMD FCH IDE Controller                                                                  | 6        | 0.81%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 5        | 0.68%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5        | 0.68%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 5        | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 0.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 0.68%   |
| IBM Obsidian chipset SCSI controller                                                    | 5        | 0.68%   |
| Yangtze Memory ZHITAI TiPro5000 NVMe SSD                                                | 4        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 362      | 57.37%  |
| NVMe | 172      | 27.26%  |
| IDE  | 53       | 8.4%    |
| RAID | 32       | 5.07%   |
| SAS  | 7        | 1.11%   |
| SCSI | 5        | 0.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 294      | 69.18%  |
| AMD               | 103      | 24.24%  |
| Unknown           | 9        | 2.12%   |
| CHRP IBM,8233-E8B | 5        | 1.18%   |
| sifive,bullet0    | 3        | 0.71%   |
| Loongson          | 2        | 0.47%   |
| CHRP IBM,9131-52A | 2        | 0.47%   |
| CentaurHauls      | 2        | 0.47%   |
| sifive,u74-mc     | 1        | 0.24%   |
| PowerNV FP5466G2  | 1        | 0.24%   |
| PowerNV C829UAG3  | 1        | 0.24%   |
| FSP-1             | 1        | 0.24%   |
| ARM               | 1        | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz                          | 10       | 2.34%   |
| Intel Core i7-10700 CPU @ 2.90GHz                         | 9        | 2.11%   |
|                                                           | 9        | 2.11%   |
| Intel Core i7-8700 CPU @ 3.20GHz                          | 8        | 1.87%   |
| Intel Core i7-7800X CPU @ 3.50GHz                         | 8        | 1.87%   |
| Intel Core i7-7700 CPU @ 3.60GHz                          | 8        | 1.87%   |
| Intel Core i7-4790 CPU @ 3.60GHz                          | 7        | 1.64%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz                    | 7        | 1.64%   |
| Intel Core i5-8400 CPU @ 2.80GHz                          | 6        | 1.41%   |
| AMD Ryzen 7 3700X 8-Core Processor                        | 6        | 1.41%   |
| AMD Ryzen 5 3600 6-Core Processor                         | 6        | 1.41%   |
| Intel Core i7-6700 CPU @ 3.40GHz                          | 5        | 1.17%   |
| Intel Core i5-10400 CPU @ 2.90GHz                         | 5        | 1.17%   |
| CHRP IBM,8233-E8B POWER7 (architected), altivec supported | 5        | 1.17%   |
| AMD Ryzen 5 2600 Six-Core Processor                       | 5        | 1.17%   |
| Intel Xeon W-2223 CPU @ 3.60GHz                           | 4        | 0.94%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz                       | 4        | 0.94%   |
| Intel Core i7-8700K CPU @ 3.70GHz                         | 4        | 0.94%   |
| Intel Core i7-4790K CPU @ 4.00GHz                         | 4        | 0.94%   |
| Intel Core i5-7400 CPU @ 3.00GHz                          | 4        | 0.94%   |
| Intel Core i5-6500 CPU @ 3.20GHz                          | 4        | 0.94%   |
| Intel Celeron N5105 @ 2.00GHz                             | 4        | 0.94%   |
| Intel 12th Gen Core i9-12900K                             | 4        | 0.94%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics                | 4        | 0.94%   |
| AMD Ryzen 7 5700G with Radeon Graphics                    | 4        | 0.94%   |
| AMD Ryzen 5 5600G with Radeon Graphics                    | 4        | 0.94%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics               | 4        | 0.94%   |
| sifive,bullet0 rv64imafdc                                 | 3        | 0.7%    |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz                       | 3        | 0.7%    |
| Intel Pentium CPU G2030 @ 3.00GHz                         | 3        | 0.7%    |
| Intel Core i9-10900K CPU @ 3.70GHz                        | 3        | 0.7%    |
| Intel Core i7-7700K CPU @ 4.20GHz                         | 3        | 0.7%    |
| Intel Core i7-3770 CPU @ 3.40GHz                          | 3        | 0.7%    |
| Intel Core i5-9400F CPU @ 2.90GHz                         | 3        | 0.7%    |
| Intel Core i5-7500 CPU @ 3.40GHz                          | 3        | 0.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz                          | 3        | 0.7%    |
| Intel Core i5-3570 CPU @ 3.40GHz                          | 3        | 0.7%    |
| Intel Core i3-2100 CPU @ 3.10GHz                          | 3        | 0.7%    |
| Intel Celeron CPU J1900 @ 1.99GHz                         | 3        | 0.7%    |
| Intel 12th Gen Core i7-12700K                             | 3        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 79       | 18.54%  |
| Intel Core i5           | 68       | 15.96%  |
| Other                   | 59       | 13.85%  |
| Intel Xeon              | 38       | 8.92%   |
| AMD Ryzen 5             | 29       | 6.81%   |
| Intel Core i3           | 26       | 6.1%    |
| Intel Celeron           | 22       | 5.16%   |
| AMD Ryzen 7             | 18       | 4.23%   |
| AMD Ryzen 9             | 13       | 3.05%   |
| Intel Pentium           | 10       | 2.35%   |
| AMD FX                  | 7        | 1.64%   |
| Intel Core i9           | 6        | 1.41%   |
| AMD Athlon II X2        | 6        | 1.41%   |
| AMD A8                  | 5        | 1.17%   |
| Intel Core 2 Duo        | 4        | 0.94%   |
| AMD Ryzen 7 PRO         | 4        | 0.94%   |
| AMD Athlon X4           | 4        | 0.94%   |
| Intel Pentium Dual-Core | 3        | 0.7%    |
| Intel Genuine           | 3        | 0.7%    |
| AMD Athlon              | 3        | 0.7%    |
| Intel Core 2 Quad       | 2        | 0.47%   |
| Intel Atom              | 2        | 0.47%   |
| AMD Ryzen 5 PRO         | 2        | 0.47%   |
| AMD Ryzen 3             | 2        | 0.47%   |
| Intel Xeon Bronze       | 1        | 0.23%   |
| Intel Pentium Silver    | 1        | 0.23%   |
| Intel Pentium Dual      | 1        | 0.23%   |
| Intel Core 2            | 1        | 0.23%   |
| ARM Allwinner           | 1        | 0.23%   |
| AMD Ryzen Threadripper  | 1        | 0.23%   |
| AMD Phenom II X4        | 1        | 0.23%   |
| AMD Athlon II X4        | 1        | 0.23%   |
| AMD Athlon 64 X2        | 1        | 0.23%   |
| AMD A6                  | 1        | 0.23%   |
| AMD A10                 | 1        | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 144      | 33.72%  |
| 2       | 83       | 19.44%  |
| 6       | 76       | 17.8%   |
| 8       | 58       | 13.58%  |
| 12      | 17       | 3.98%   |
| 16      | 13       | 3.04%   |
| 1       | 11       | 2.58%   |
| 10      | 9        | 2.11%   |
| Unknown | 6        | 1.41%   |
| 24      | 3        | 0.7%    |
| 32      | 2        | 0.47%   |
| 64      | 1        | 0.23%   |
| 40      | 1        | 0.23%   |
| 28      | 1        | 0.23%   |
| 22      | 1        | 0.23%   |
| 3       | 1        | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 407      | 95.76%  |
| 2       | 10       | 2.35%   |
| Unknown | 6        | 1.41%   |
| 16      | 1        | 0.24%   |
| 6       | 1        | 0.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 260      | 61.03%  |
| 1       | 153      | 35.92%  |
| 4       | 6        | 1.41%   |
| Unknown | 6        | 1.41%   |
| 8       | 1        | 0.23%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 402      | 94.59%  |
| Unknown        | 22       | 5.18%   |
| 64-bit         | 1        | 0.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 135      | 31.18%  |
| 0x306c3    | 34       | 7.85%   |
| 0x906ea    | 19       | 4.39%   |
| 0x906e9    | 17       | 3.93%   |
| 0x306a9    | 17       | 3.93%   |
| 0xa0655    | 13       | 3%      |
| 0x506e3    | 13       | 3%      |
| 0x206a7    | 12       | 2.77%   |
| 0x90672    | 8        | 1.85%   |
| 0x50654    | 8        | 1.85%   |
| 0x08701013 | 8        | 1.85%   |
| 0x1067a    | 7        | 1.62%   |
| 0xa0671    | 6        | 1.39%   |
| 0x06003106 | 6        | 1.39%   |
| 0xa0653    | 5        | 1.15%   |
| 0x50657    | 5        | 1.15%   |
| 0x30678    | 5        | 1.15%   |
| 0x08701021 | 5        | 1.15%   |
| 0x010000c8 | 5        | 1.15%   |
| 0xb0671    | 4        | 0.92%   |
| 0x306f2    | 4        | 0.92%   |
| 0x0a50000d | 4        | 0.92%   |
| 0x0a50000c | 4        | 0.92%   |
| 0x0810100b | 4        | 0.92%   |
| 0x906c0    | 3        | 0.69%   |
| 0x206d7    | 3        | 0.69%   |
| 0x206c2    | 3        | 0.69%   |
| 0x08600106 | 3        | 0.69%   |
| 0x0800820d | 3        | 0.69%   |
| 0x08001138 | 3        | 0.69%   |
| 0x06001119 | 3        | 0.69%   |
| 0x906ed    | 2        | 0.46%   |
| 0x906eb    | 2        | 0.46%   |
| 0x806c1    | 2        | 0.46%   |
| 0x406f1    | 2        | 0.46%   |
| 0x40651    | 2        | 0.46%   |
| 0x306f1    | 2        | 0.46%   |
| 0x306e4    | 2        | 0.46%   |
| 0x30661    | 2        | 0.46%   |
| 0x0a20120a | 2        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 58       | 13.62%  |
| KabyLake         | 57       | 13.38%  |
| Unknown          | 51       | 11.97%  |
| Skylake          | 34       | 7.98%   |
| CometLake        | 30       | 7.04%   |
| IvyBridge        | 28       | 6.57%   |
| Zen 2            | 26       | 6.1%    |
| Zen 3            | 20       | 4.69%   |
| SandyBridge      | 17       | 3.99%   |
| Zen              | 13       | 3.05%   |
| Penryn           | 11       | 2.58%   |
| K10              | 9        | 2.11%   |
| Zen+             | 8        | 1.88%   |
| Silvermont       | 8        | 1.88%   |
| Piledriver       | 8        | 1.88%   |
| Steamroller      | 7        | 1.64%   |
| Alderlake Hybrid | 7        | 1.64%   |
| Icelake          | 6        | 1.41%   |
| Broadwell        | 4        | 0.94%   |
| Westmere         | 3        | 0.7%    |
| Tremont          | 3        | 0.7%    |
| Core             | 3        | 0.7%    |
| TigerLake        | 2        | 0.47%   |
| Gracemont        | 2        | 0.47%   |
| Bulldozer        | 2        | 0.47%   |
| Bonnell          | 2        | 0.47%   |
| Puma             | 1        | 0.23%   |
| NetBurst         | 1        | 0.23%   |
| Nehalem          | 1        | 0.23%   |
| K8 Hammer        | 1        | 0.23%   |
| Goldmont plus    | 1        | 0.23%   |
| Goldmont         | 1        | 0.23%   |
| Excavator        | 1        | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 175      | 37.47%  |
| Nvidia                           | 143      | 30.62%  |
| AMD                              | 127      | 27.19%  |
| Matrox Electronics Systems       | 6        | 1.28%   |
| ASPEED Technology                | 6        | 1.28%   |
| Loongson Technology              | 4        | 0.86%   |
| Zhaoxin                          | 2        | 0.43%   |
| Silicon Integrated Systems [SiS] | 1        | 0.21%   |
| Moore Threads Technology         | 1        | 0.21%   |
| Cirrus Logic                     | 1        | 0.21%   |
| 3DLabs                           | 1        | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 23       | 4.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 21       | 4.39%   |
| Intel HD Graphics 630                                                       | 15       | 3.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 15       | 3.14%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 13       | 2.72%   |
| Intel HD Graphics 530                                                       | 12       | 2.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11       | 2.3%    |
| Nvidia GK208B [GeForce GT 730]                                              | 10       | 2.09%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 1.88%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 8        | 1.67%   |
| Nvidia GK208B [GeForce GT 710]                                              | 8        | 1.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 8        | 1.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8        | 1.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 1.46%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 6        | 1.26%   |
| Intel JasperLake [UHD Graphics]                                             | 6        | 1.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 6        | 1.26%   |
| Intel AlderLake-S GT1                                                       | 6        | 1.26%   |
| ASPEED Technology ASPEED Graphics Family                                    | 6        | 1.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.05%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 5        | 1.05%   |
| Matrox Electronics Systems Millennium G550                                  | 5        | 1.05%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 5        | 1.05%   |
| AMD Renoir                                                                  | 5        | 1.05%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1.05%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 5        | 1.05%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 0.84%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 0.84%   |
| Nvidia GP106GL [Quadro P2200]                                               | 4        | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 0.84%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 0.84%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 0.84%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 0.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4        | 0.84%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 0.84%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 0.84%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 3        | 0.63%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 3        | 0.63%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 3        | 0.63%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| 1 x Intel                    | 141      | 32.64%  |
| 1 x Nvidia                   | 121      | 28.01%  |
| 1 x AMD                      | 108      | 25%     |
| Intel + Nvidia               | 10       | 2.31%   |
| Other                        | 8        | 1.85%   |
| 2 x Nvidia                   | 6        | 1.39%   |
| 1 x Matrox                   | 6        | 1.39%   |
| Intel + AMD                  | 6        | 1.39%   |
| 1 x ASPEED                   | 3        | 0.69%   |
| AMD + Nvidia                 | 3        | 0.69%   |
| 2 x AMD                      | 2        | 0.46%   |
| 1 x Zhaoxin                  | 2        | 0.46%   |
| Nvidia + ASPEED              | 2        | 0.46%   |
| 1 x Loongson Technology      | 2        | 0.46%   |
| AMD + Matrox                 | 2        | 0.46%   |
| AMD + Loongson Technology    | 2        | 0.46%   |
| 2 x Intel                    | 1        | 0.23%   |
| 1 x SiS                      | 1        | 0.23%   |
| 1 x Moore Threads Technology | 1        | 0.23%   |
| 1 x Intel + 3 x Nvidia       | 1        | 0.23%   |
| Intel + 2 x Nvidia           | 1        | 0.23%   |
| 1 x Cirrus Logic             | 1        | 0.23%   |
| AMD + ASPEED                 | 1        | 0.23%   |
| AMD + 3DLabs                 | 1        | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 291      | 67.36%  |
| Proprietary | 77       | 17.82%  |
| Unknown     | 64       | 14.81%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 237      | 54.61%  |
| 1.01-2.0   | 47       | 10.83%  |
| 0.51-1.0   | 37       | 8.53%   |
| 0.01-0.5   | 29       | 6.68%   |
| 3.01-4.0   | 26       | 5.99%   |
| 7.01-8.0   | 20       | 4.61%   |
| 5.01-6.0   | 13       | 3%      |
| 8.01-16.0  | 8        | 1.84%   |
| 2.01-3.0   | 6        | 1.38%   |
| 4.01-5.0   | 5        | 1.15%   |
| 16.01-24.0 | 4        | 0.92%   |
| 24.01-32.0 | 2        | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 65       | 17.62%  |
| AOC                  | 52       | 14.09%  |
| Lenovo               | 38       | 10.3%   |
| Philips              | 27       | 7.32%   |
| Samsung Electronics  | 22       | 5.96%   |
| ViewSonic            | 16       | 4.34%   |
| Goldstar             | 14       | 3.79%   |
| Hewlett-Packard      | 13       | 3.52%   |
| BenQ                 | 10       | 2.71%   |
| Acer                 | 10       | 2.71%   |
| HKC                  | 8        | 2.17%   |
| Ancor Communications | 4        | 1.08%   |
| Xiaomi               | 3        | 0.81%   |
| Unknown              | 3        | 0.81%   |
| RTK                  | 3        | 0.81%   |
| Mi                   | 3        | 0.81%   |
| LG Electronics       | 3        | 0.81%   |
| Lenovo Group Limited | 3        | 0.81%   |
| IPS                  | 3        | 0.81%   |
| Eizo                 | 3        | 0.81%   |
| Unknown              | 3        | 0.81%   |
| TFC                  | 2        | 0.54%   |
| Sony                 | 2        | 0.54%   |
| SKY                  | 2        | 0.54%   |
| SGT                  | 2        | 0.54%   |
| SAC                  | 2        | 0.54%   |
| KOIOS                | 2        | 0.54%   |
| HannStar             | 2        | 0.54%   |
| Envision Peripherals | 2        | 0.54%   |
| DSC                  | 2        | 0.54%   |
| Daewoo               | 2        | 0.54%   |
| CHR                  | 2        | 0.54%   |
| CHD                  | 2        | 0.54%   |
| BOE                  | 2        | 0.54%   |
| AGO                  | 2        | 0.54%   |
| ZTY                  | 1        | 0.27%   |
| ZLS                  | 1        | 0.27%   |
| Xiangye              | 1        | 0.27%   |
| Unknown (AAA)        | 1        | 0.27%   |
| TUP                  | 1        | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                   | 5        | 1.27%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch            | 4        | 1.02%   |
| Lenovo T24s-28 LEN62C7 1920x1080 527x296mm 23.8-inch               | 4        | 1.02%   |
| Dell P2422H DELA1C5 1920x1080 530x300mm 24.0-inch                  | 4        | 1.02%   |
| AOC Q2790 AOC2790 2560x1440 597x336mm 27.0-inch                    | 4        | 1.02%   |
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch         | 3        | 0.76%   |
| Philips 190VL PHLC080 1440x900 408x255mm 18.9-inch                 | 3        | 0.76%   |
| Lenovo LEN T2254A LEN60CD 1680x1050 474x296mm 22.0-inch            | 3        | 0.76%   |
| Lenovo LEN LI2364 LEN65C7 1920x1080 509x286mm 23.0-inch            | 3        | 0.76%   |
| Dell P2422H DELA1C3 1920x1080 527x296mm 23.8-inch                  | 3        | 0.76%   |
| AOC Q27G1WG4 AOC2701 2560x1440 597x336mm 27.0-inch                 | 3        | 0.76%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                 | 3        | 0.76%   |
| Unknown                                                            | 3        | 0.76%   |
| Xiaomi Mi TV XMD004A 1920x1080 890x500mm 40.2-inch                 | 2        | 0.51%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch          | 2        | 0.51%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch | 2        | 0.51%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch  | 2        | 0.51%   |
| Samsung Electronics LCD Monitor S19B360                            | 2        | 0.51%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch  | 2        | 0.51%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch            | 2        | 0.51%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch            | 2        | 0.51%   |
| Mi Redmi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch             | 2        | 0.51%   |
| Lenovo X24q-10 LEN61A4 2560x1440 530x300mm 24.0-inch               | 2        | 0.51%   |
| Lenovo LT2252p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch          | 2        | 0.51%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch              | 2        | 0.51%   |
| IPS DP IPS2700 3840x2160 619x348mm 28.0-inch                       | 2        | 0.51%   |
| HKC CH70 HKC27A9 1920x1080 597x336mm 27.0-inch                     | 2        | 0.51%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 2        | 0.51%   |
| DSC Paperlike H D DSC0001 2200x1650 200x150mm 9.8-inch             | 2        | 0.51%   |
| Dell U2518D DEL413C 2560x1440 553x311mm 25.0-inch                  | 2        | 0.51%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                  | 2        | 0.51%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                   | 2        | 0.51%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                  | 2        | 0.51%   |
| Dell P2721Q DELF125 3840x2160 597x336mm 27.0-inch                  | 2        | 0.51%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                  | 2        | 0.51%   |
| Dell P2414H DELA09A 1920x1080 527x297mm 23.8-inch                  | 2        | 0.51%   |
| Dell P2317H DEL40F3 1920x1080 509x286mm 23.0-inch                  | 2        | 0.51%   |
| Dell E2316H DELF06A 1920x1080 509x286mm 23.0-inch                  | 2        | 0.51%   |
| Dell E2216HV DELF06F 1920x1080 476x268mm 21.5-inch                 | 2        | 0.51%   |
| Daewoo HDMI DWE2100 1280x1024 470x260mm 21.1-inch                  | 2        | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 189      | 50.67%  |
| 3840x2160 (4K)     | 46       | 12.33%  |
| 2560x1440 (QHD)    | 41       | 10.99%  |
| 1440x900 (WXGA+)   | 19       | 5.09%   |
| 1280x1024 (SXGA)   | 13       | 3.49%   |
| 1920x1200 (WUXGA)  | 10       | 2.68%   |
| 1680x1050 (WSXGA+) | 10       | 2.68%   |
| 1600x900 (HD+)     | 9        | 2.41%   |
| Unknown            | 9        | 2.41%   |
| 3440x1440          | 5        | 1.34%   |
| 1366x768 (WXGA)    | 4        | 1.07%   |
| 3360x1080          | 2        | 0.54%   |
| 3286x1080          | 2        | 0.54%   |
| 2288x1287          | 2        | 0.54%   |
| 2200x1650          | 2        | 0.54%   |
| 6400x2160          | 1        | 0.27%   |
| 5206x1080          | 1        | 0.27%   |
| 3600x1080          | 1        | 0.27%   |
| 3520x1080          | 1        | 0.27%   |
| 2560x1600          | 1        | 0.27%   |
| 2560x1080          | 1        | 0.27%   |
| 1600x1200          | 1        | 0.27%   |
| 1400x1050          | 1        | 0.27%   |
| 1360x768           | 1        | 0.27%   |
| 1280x800 (WXGA)    | 1        | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 76       | 20.49%  |
| 24      | 51       | 13.75%  |
| 21      | 50       | 13.48%  |
| 27      | 49       | 13.21%  |
| Unknown | 32       | 8.63%   |
| 19      | 17       | 4.58%   |
| 31      | 12       | 3.23%   |
| 22      | 11       | 2.96%   |
| 18      | 10       | 2.7%    |
| 17      | 9        | 2.43%   |
| 25      | 8        | 2.16%   |
| 20      | 8        | 2.16%   |
| 34      | 4        | 1.08%   |
| 12      | 4        | 1.08%   |
| 40      | 3        | 0.81%   |
| 142     | 2        | 0.54%   |
| 65      | 2        | 0.54%   |
| 63      | 2        | 0.54%   |
| 32      | 2        | 0.54%   |
| 28      | 2        | 0.54%   |
| 26      | 2        | 0.54%   |
| 15      | 2        | 0.54%   |
| 13      | 2        | 0.54%   |
| 72      | 1        | 0.27%   |
| 54      | 1        | 0.27%   |
| 46      | 1        | 0.27%   |
| 43      | 1        | 0.27%   |
| 42      | 1        | 0.27%   |
| 39      | 1        | 0.27%   |
| 37      | 1        | 0.27%   |
| 36      | 1        | 0.27%   |
| 35      | 1        | 0.27%   |
| 14      | 1        | 0.27%   |
| 11      | 1        | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 173      | 48.06%  |
| 401-500        | 89       | 24.72%  |
| Unknown        | 32       | 8.89%   |
| 601-700        | 18       | 5%      |
| 301-350        | 11       | 3.06%   |
| 801-900        | 7        | 1.94%   |
| 201-300        | 7        | 1.94%   |
| 701-800        | 6        | 1.67%   |
| 351-400        | 6        | 1.67%   |
| 1001-1500      | 6        | 1.67%   |
| More than 2000 | 2        | 0.56%   |
| 901-1000       | 2        | 0.56%   |
| 1501-2000      | 1        | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 248      | 70.66%  |
| 16/10   | 45       | 12.82%  |
| Unknown | 31       | 8.83%   |
| 5/4     | 13       | 3.7%    |
| 4/3     | 6        | 1.71%   |
| 21/9    | 5        | 1.42%   |
| 1.00    | 2        | 0.57%   |
| 2.00    | 1        | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 139      | 38.08%  |
| 151-200        | 63       | 17.26%  |
| 301-350        | 51       | 13.97%  |
| Unknown        | 32       | 8.77%   |
| 251-300        | 23       | 6.3%    |
| 351-500        | 20       | 5.48%   |
| 141-150        | 11       | 3.01%   |
| More than 1000 | 8        | 2.19%   |
| 501-1000       | 8        | 2.19%   |
| 71-80          | 4        | 1.1%    |
| 81-90          | 2        | 0.55%   |
| 101-110        | 2        | 0.55%   |
| 61-70          | 1        | 0.27%   |
| 51-60          | 1        | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 213      | 58.68%  |
| 101-120 | 75       | 20.66%  |
| Unknown | 32       | 8.82%   |
| 121-160 | 18       | 4.96%   |
| 161-240 | 17       | 4.68%   |
| 1-50    | 8        | 2.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 308      | 71.3%   |
| 0     | 79       | 18.29%  |
| 2     | 41       | 9.49%   |
| 3     | 4        | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 265      | 44.24%  |
| Intel                           | 207      | 34.56%  |
| Qualcomm Atheros                | 26       | 4.34%   |
| Ralink Technology               | 20       | 3.34%   |
| Broadcom                        | 11       | 1.84%   |
| MediaTek                        | 10       | 1.67%   |
| IBM                             | 5        | 0.83%   |
| Huawei Technologies             | 5        | 0.83%   |
| Microsoft                       | 4        | 0.67%   |
| Loongson Technology             | 4        | 0.67%   |
| Tenda                           | 3        | 0.5%    |
| Marvell Technology Group        | 3        | 0.5%    |
| D-Link                          | 3        | 0.5%    |
| ASIX Electronics                | 3        | 0.5%    |
| Aquantia                        | 3        | 0.5%    |
| ZTE WCDMA Technologies MSM      | 2        | 0.33%   |
| Xiaomi                          | 2        | 0.33%   |
| TP-Link                         | 2        | 0.33%   |
| Samsung Electronics             | 2        | 0.33%   |
| Qualcomm                        | 2        | 0.33%   |
| Oculus VR                       | 2        | 0.33%   |
| NetGear                         | 2        | 0.33%   |
| Mellanox Technologies           | 2        | 0.33%   |
| Broadcom Limited                | 2        | 0.33%   |
| Wilocity                        | 1        | 0.17%   |
| Sagem                           | 1        | 0.17%   |
| Qualcomm Atheros Communications | 1        | 0.17%   |
| OPPO Electronics                | 1        | 0.17%   |
| Nvidia                          | 1        | 0.17%   |
| Google                          | 1        | 0.17%   |
| Exar                            | 1        | 0.17%   |
| DisplayLink                     | 1        | 0.17%   |
| D-Link System                   | 1        | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 190      | 27.42%  |
| Realtek RTL8125 2.5GbE Controller                                 | 27       | 3.9%    |
| Intel Ethernet Connection (2) I219-V                              | 26       | 3.75%   |
| Intel Wi-Fi 6 AX200                                               | 25       | 3.61%   |
| Intel I211 Gigabit Network Connection                             | 22       | 3.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18       | 2.6%    |
| Intel Ethernet Controller I225-V                                  | 14       | 2.02%   |
| Realtek 802.11ac NIC                                              | 13       | 1.88%   |
| Ralink MT7601U Wireless Adapter                                   | 13       | 1.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 11       | 1.59%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 1.44%   |
| Intel Ethernet Connection (12) I219-V                             | 10       | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 1.44%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 8        | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 8        | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 7        | 1.01%   |
| Intel I350 Gigabit Network Connection                             | 7        | 1.01%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 7        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6        | 0.87%   |
| Intel Wireless-AC 9260                                            | 6        | 0.87%   |
| Intel Wireless 7260                                               | 6        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 0.87%   |
| Intel Ethernet Connection (2) I218-V                              | 6        | 0.87%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 5        | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 5        | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5        | 0.72%   |
| Intel I210 Gigabit Network Connection                             | 5        | 0.72%   |
| IBM IBM                                                           | 5        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4        | 0.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4        | 0.58%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 4        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.58%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                | 4        | 0.58%   |
| Intel Wireless 7265                                               | 4        | 0.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                             | 4        | 0.58%   |
| Intel Ethernet Connection (2) I218-LM                             | 4        | 0.58%   |
| Tenda U12                                                         | 3        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 81       | 37.85%  |
| Realtek Semiconductor           | 62       | 28.97%  |
| Ralink Technology               | 20       | 9.35%   |
| Qualcomm Atheros                | 16       | 7.48%   |
| MediaTek                        | 10       | 4.67%   |
| Broadcom                        | 5        | 2.34%   |
| Tenda                           | 3        | 1.4%    |
| Microsoft                       | 3        | 1.4%    |
| D-Link                          | 3        | 1.4%    |
| TP-Link                         | 2        | 0.93%   |
| NetGear                         | 2        | 0.93%   |
| Broadcom Limited                | 2        | 0.93%   |
| Xiaomi                          | 1        | 0.47%   |
| Wilocity                        | 1        | 0.47%   |
| Sagem                           | 1        | 0.47%   |
| Qualcomm Atheros Communications | 1        | 0.47%   |
| D-Link System                   | 1        | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 25       | 11.42%  |
| Realtek 802.11ac NIC                                       | 13       | 5.94%   |
| Ralink MT7601U Wireless Adapter                            | 13       | 5.94%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)  | 8        | 3.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 8        | 3.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 7        | 3.2%    |
| Intel Alder Lake-S PCH CNVi WiFi                           | 7        | 3.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 6        | 2.74%   |
| Intel Wireless-AC 9260                                     | 6        | 2.74%   |
| Intel Wireless 7260                                        | 6        | 2.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 5        | 2.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 5        | 2.28%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 5        | 2.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 5        | 2.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 4        | 1.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 4        | 1.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 4        | 1.83%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter         | 4        | 1.83%   |
| Intel Wireless 7265                                        | 4        | 1.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 4        | 1.83%   |
| Tenda U12                                                  | 3        | 1.37%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 3        | 1.37%   |
| Intel Wireless 8260                                        | 3        | 1.37%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 3        | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 3        | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                             | 3        | 1.37%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 3        | 1.37%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                      | 2        | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2        | 0.91%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 2        | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 2        | 0.91%   |
| Realtek 802.11n WLAN Adapter                               | 2        | 0.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2        | 0.91%   |
| Microsoft Xbox Wireless Adapter for Windows                | 2        | 0.91%   |
| MediaTek 802.11 n WLAN                                     | 2        | 0.91%   |
| Intel Wireless 3165                                        | 2        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2        | 0.91%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 2        | 0.91%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                          | 1        | 0.46%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter         | 1        | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 237      | 52.67%  |
| Intel                    | 159      | 35.33%  |
| Qualcomm Atheros         | 13       | 2.89%   |
| Broadcom                 | 6        | 1.33%   |
| IBM                      | 5        | 1.11%   |
| Huawei Technologies      | 5        | 1.11%   |
| Loongson Technology      | 4        | 0.89%   |
| Marvell Technology Group | 3        | 0.67%   |
| ASIX Electronics         | 3        | 0.67%   |
| Aquantia                 | 3        | 0.67%   |
| Samsung Electronics      | 2        | 0.44%   |
| Qualcomm                 | 2        | 0.44%   |
| Mellanox Technologies    | 2        | 0.44%   |
| Xiaomi                   | 1        | 0.22%   |
| OPPO Electronics         | 1        | 0.22%   |
| Nvidia                   | 1        | 0.22%   |
| Microsoft                | 1        | 0.22%   |
| Google                   | 1        | 0.22%   |
| DisplayLink              | 1        | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 190      | 40.51%  |
| Realtek RTL8125 2.5GbE Controller                                 | 27       | 5.76%   |
| Intel Ethernet Connection (2) I219-V                              | 26       | 5.54%   |
| Intel I211 Gigabit Network Connection                             | 22       | 4.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18       | 3.84%   |
| Intel Ethernet Controller I225-V                                  | 14       | 2.99%   |
| Intel Ethernet Connection (2) I219-LM                             | 11       | 2.35%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 2.13%   |
| Intel Ethernet Connection (12) I219-V                             | 10       | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 2.13%   |
| Intel I350 Gigabit Network Connection                             | 7        | 1.49%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 1.28%   |
| Intel Ethernet Connection (2) I218-V                              | 6        | 1.28%   |
| Intel I210 Gigabit Network Connection                             | 5        | 1.07%   |
| IBM IBM                                                           | 5        | 1.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                             | 4        | 0.85%   |
| Intel Ethernet Connection (2) I218-LM                             | 4        | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 0.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.64%   |
| Intel Ethernet Controller I226-V                                  | 3        | 0.64%   |
| Intel Ethernet Connection (17) I219-LM                            | 3        | 0.64%   |
| Intel Ethernet Connection (14) I219-LM                            | 3        | 0.64%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 0.64%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.64%   |
| Huawei HNS GE/10GE/25GE RDMA Network Controller                   | 3        | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 0.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.43%   |
| Loongson Gigabit Ethernet Controller                              | 2        | 0.43%   |
| Loongson Ethernet controller                                      | 2        | 0.43%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.43%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.43%   |
| Intel 82546GB Gigabit Ethernet Controller                         | 2        | 0.43%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 2        | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 0.21%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.21%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.21%   |
| Samsung Android USB Device                                        | 1        | 0.21%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 416      | 66.88%  |
| WiFi     | 201      | 32.32%  |
| Modem    | 3        | 0.48%   |
| Unknown  | 2        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 312      | 75%     |
| WiFi     | 104      | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 241      | 56.18%  |
| 2     | 132      | 30.77%  |
| 3     | 26       | 6.06%   |
| 0     | 11       | 2.56%   |
| 4     | 10       | 2.33%   |
| 6     | 6        | 1.4%    |
| 8     | 1        | 0.23%   |
| 7     | 1        | 0.23%   |
| 5     | 1        | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 374      | 87.38%  |
| Yes  | 54       | 12.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 76       | 49.67%  |
| Cambridge Silicon Radio         | 39       | 25.49%  |
| Realtek Semiconductor           | 12       | 7.84%   |
| ASUSTek Computer                | 9        | 5.88%   |
| Qualcomm Atheros Communications | 7        | 4.58%   |
| MediaTek                        | 4        | 2.61%   |
| Broadcom                        | 3        | 1.96%   |
| Realtek                         | 1        | 0.65%   |
| Foxconn / Hon Hai               | 1        | 0.65%   |
| Apple                           | 1        | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 39       | 25.49%  |
| Intel Bluetooth wireless interface                    | 25       | 16.34%  |
| Intel AX200 Bluetooth                                 | 23       | 15.03%  |
| Intel AX201 Bluetooth                                 | 11       | 7.19%   |
| Realtek Bluetooth Radio                               | 9        | 5.88%   |
| Intel Bluetooth Device                                | 6        | 3.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 5        | 3.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 4        | 2.61%   |
| MediaTek Wireless_Device                              | 4        | 2.61%   |
| Intel AX210 Bluetooth                                 | 4        | 2.61%   |
| ASUS Bluetooth Radio                                  | 4        | 2.61%   |
| Qualcomm Atheros  Bluetooth Device                    | 3        | 1.96%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 3        | 1.96%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 1.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 1.31%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 1.31%   |
| Realtek 802.11n WLAN Adapter                          | 1        | 0.65%   |
| Realtek Bluetooth Radio                               | 1        | 0.65%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1        | 0.65%   |
| Broadcom Bluetooth 3.0 USB Dongle                     | 1        | 0.65%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 0.65%   |
| ASUS Bluetooth Device                                 | 1        | 0.65%   |
| Apple Bluetooth Host Controller                       | 1        | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 280      | 44.94%  |
| AMD                              | 153      | 24.56%  |
| Nvidia                           | 135      | 21.67%  |
| C-Media Electronics              | 6        | 0.96%   |
| Realtek Semiconductor            | 4        | 0.64%   |
| Loongson Technology              | 4        | 0.64%   |
| Creative Labs                    | 4        | 0.64%   |
| XMOS                             | 3        | 0.48%   |
| Zhaoxin                          | 2        | 0.32%   |
| Texas Instruments                | 2        | 0.32%   |
| Giga-Byte Technology             | 2        | 0.32%   |
| Dell                             | 2        | 0.32%   |
| VIA Technologies                 | 1        | 0.16%   |
| USB-Speaker                      | 1        | 0.16%   |
| ULi Electronics                  | 1        | 0.16%   |
| TerraTec Electronic              | 1        | 0.16%   |
| SteelSeries ApS                  | 1        | 0.16%   |
| Sony                             | 1        | 0.16%   |
| Silicon Integrated Systems [SiS] | 1        | 0.16%   |
| Sennheiser Communications        | 1        | 0.16%   |
| Polycom                          | 1        | 0.16%   |
| NXP Semiconductors               | 1        | 0.16%   |
| Moore Threads Technology         | 1        | 0.16%   |
| Micro Star International         | 1        | 0.16%   |
| Medeli Electronics               | 1        | 0.16%   |
| M-Audio                          | 1        | 0.16%   |
| KTMicro                          | 1        | 0.16%   |
| Kingston Technology              | 1        | 0.16%   |
| JMTek                            | 1        | 0.16%   |
| Jieli Technology                 | 1        | 0.16%   |
| HECATE G2 GAMING HEADSET         | 1        | 0.16%   |
| Generalplus Technology           | 1        | 0.16%   |
| DCMT Technology                  | 1        | 0.16%   |
| Atmel                            | 1        | 0.16%   |
| ASUSTek Computer                 | 1        | 0.16%   |
| ASRock                           | 1        | 0.16%   |
| Anlya.cn                         | 1        | 0.16%   |
| Actions Semiconductor            | 1        | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 200 Series PCH HD Audio                                                     | 46       | 6.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 40       | 5.53%   |
| AMD Starship/Matisse HD Audio Controller                                          | 30       | 4.15%   |
| AMD Family 17h/19h HD Audio Controller                                            | 30       | 4.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 23       | 3.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 21       | 2.9%    |
| Intel Comet Lake PCH-V cAVS                                                       | 20       | 2.77%   |
| Intel Cannon Lake PCH cAVS                                                        | 20       | 2.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 19       | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 19       | 2.63%   |
| Nvidia GP106 High Definition Audio Controller                                     | 17       | 2.35%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 17       | 2.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 16       | 2.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 15       | 2.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 14       | 1.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 14       | 1.94%   |
| AMD FCH Azalia Controller                                                         | 13       | 1.8%    |
| Nvidia TU116 High Definition Audio Controller                                     | 12       | 1.66%   |
| Intel Alder Lake-S HD Audio Controller                                            | 12       | 1.66%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 11       | 1.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 11       | 1.52%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 11       | 1.52%   |
| Nvidia GP104 High Definition Audio Controller                                     | 10       | 1.38%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 10       | 1.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 10       | 1.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 10       | 1.38%   |
| Nvidia GF119 HDMI Audio Controller                                                | 9        | 1.24%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 9        | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 9        | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 8        | 1.11%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 7        | 0.97%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 7        | 0.97%   |
| Nvidia GM206 High Definition Audio Controller                                     | 6        | 0.83%   |
| Nvidia GA106 High Definition Audio Controller                                     | 6        | 0.83%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 6        | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 6        | 0.83%   |
| Nvidia GP102 HDMI Audio Controller                                                | 5        | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5        | 0.69%   |
| Nvidia GA102 High Definition Audio Controller                                     | 5        | 0.69%   |
| Intel Jasper Lake HD Audio                                                        | 5        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston                           | 74       | 29.37%  |
| Samsung Electronics                | 34       | 13.49%  |
| Unknown                            | 23       | 9.13%   |
| A-DATA Technology                  | 19       | 7.54%   |
| SK hynix                           | 18       | 7.14%   |
| Micron Technology                  | 11       | 4.37%   |
| Corsair                            | 11       | 4.37%   |
| Crucial                            | 9        | 3.57%   |
| Unknown                            | 8        | 3.17%   |
| Team                               | 4        | 1.59%   |
| Kingmax                            | 4        | 1.59%   |
| Ramsta                             | 3        | 1.19%   |
| Ramaxel Technology                 | 3        | 1.19%   |
| KINGBANK                           | 3        | 1.19%   |
| Juhor                              | 3        | 1.19%   |
| G.Skill                            | 3        | 1.19%   |
| GLOWAY                             | 2        | 0.79%   |
| Unknown (ABCD)                     | 1        | 0.4%    |
| Unknown (8AF1)                     | 1        | 0.4%    |
| Unknown (0x0B92)                   | 1        | 0.4%    |
| Transcend                          | 1        | 0.4%    |
| tigo                               | 1        | 0.4%    |
| Thermaltake                        | 1        | 0.4%    |
| Shenzhen Mic                       | 1        | 0.4%    |
| Shenzhen Longsys                   | 1        | 0.4%    |
| Sesame                             | 1        | 0.4%    |
| PCCOOLER                           | 1        | 0.4%    |
| MAXSUN                             | 1        | 0.4%    |
| KLEVV                              | 1        | 0.4%    |
| Kimtigo Semiconductor (HK) Limited | 1        | 0.4%    |
| Huanan                             | 1        | 0.4%    |
| GeIL                               | 1        | 0.4%    |
| CUSO                               | 1        | 0.4%    |
| Colorful                           | 1        | 0.4%    |
| Asgard                             | 1        | 0.4%    |
| Apacer                             | 1        | 0.4%    |
| 89670000802C                       | 1        | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown                                                  | 8        | 2.88%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 7        | 2.52%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s               | 5        | 1.8%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 5        | 1.8%    |
| Kingston RAM TF32D4U2S1MEH-8 8192MB DIMM DDR4 3200MT/s   | 4        | 1.44%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s  | 4        | 1.44%   |
| Corsair RAM Module 16GB DIMM DDR4 2133MT/s               | 4        | 1.44%   |
| Kingston RAM 99P5474-013.A00LF 4GB DIMM DDR3 1600MT/s    | 3        | 1.08%   |
| Kingston RAM 99P5471-033.A00LF 8192MB DIMM DDR3 1600MT/s | 3        | 1.08%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s  | 3        | 1.08%   |
| Corsair RAM CM4X16GC3200C16K2E 16GB DIMM DDR4 3200MT/s   | 3        | 1.08%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 2        | 0.72%   |
| Team RAM TEAMGROUP-UD3-1600 8192MB DIMM DDR3 1600MT/s    | 2        | 0.72%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s  | 2        | 0.72%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s    | 2        | 0.72%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s      | 2        | 0.72%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 2        | 0.72%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s      | 2        | 0.72%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 2        | 0.72%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s      | 2        | 0.72%   |
| Kingston RAM 99P5474-014.A00LF 4GB DIMM DDR3 1333MT/s    | 2        | 0.72%   |
| Kingston RAM 99P5471-016.A00LF 8192MB DIMM DDR3 1600MT/s | 2        | 0.72%   |
| Kingston RAM 9905701-011.A00G 16GB DIMM DDR4 2400MT/s    | 2        | 0.72%   |
| GLOWAY RAM TYA4U2666D19161C 16384MB DIMM DDR4 2667MT/s   | 2        | 0.72%   |
| Crucial RAM BL16G32C16U4W.16FE 16GB DIMM DDR4 3200MT/s   | 2        | 0.72%   |
| A-DATA RAM Module 8GB DIMM DDR4 2666MT/s                 | 2        | 0.72%   |
| A-DATA RAM Module 4GB DIMM DDR3 1600MT/s                 | 2        | 0.72%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s              | 2        | 0.72%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s              | 1        | 0.36%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                | 1        | 0.36%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                   | 1        | 0.36%   |
| Unknown RAM Module 8192MB                                | 1        | 0.36%   |
| Unknown RAM Module 512MB DIMM DDR2 333MT/s               | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                 | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM SDRAM                     | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR3 667MT/s                 | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 1        | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 118      | 51.08%  |
| DDR3    | 76       | 32.9%   |
| Unknown | 11       | 4.76%   |
| DDR5    | 10       | 4.33%   |
| SDRAM   | 7        | 3.03%   |
| LPDDR4  | 4        | 1.73%   |
| DDR2    | 4        | 1.73%   |
| LPDDR5  | 1        | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 203      | 87.5%   |
| SODIMM       | 23       | 9.91%   |
| Row Of Chips | 4        | 1.72%   |
| RIMM         | 1        | 0.43%   |
| Unknown      | 1        | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 92       | 36.95%  |
| 16384 | 67       | 26.91%  |
| 4096  | 52       | 20.88%  |
| 32768 | 21       | 8.43%   |
| 2048  | 15       | 6.02%   |
| 1024  | 1        | 0.4%    |
| 512   | 1        | 0.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 53       | 20.46%  |
| 3200    | 24       | 9.27%   |
| 2400    | 21       | 8.11%   |
| 3600    | 19       | 7.34%   |
| 2133    | 18       | 6.95%   |
| 1333    | 17       | 6.56%   |
| 2667    | 15       | 5.79%   |
| 2666    | 15       | 5.79%   |
| 4800    | 8        | 3.09%   |
| 800     | 8        | 3.09%   |
| 3466    | 5        | 1.93%   |
| 1866    | 5        | 1.93%   |
| Unknown | 5        | 1.93%   |
| 3000    | 4        | 1.54%   |
| 2933    | 4        | 1.54%   |
| 1800    | 4        | 1.54%   |
| 1066    | 3        | 1.16%   |
| 6400    | 2        | 0.77%   |
| 3733    | 2        | 0.77%   |
| 3400    | 2        | 0.77%   |
| 2800    | 2        | 0.77%   |
| 1867    | 2        | 0.77%   |
| 65535   | 1        | 0.39%   |
| 5600    | 1        | 0.39%   |
| 5200    | 1        | 0.39%   |
| 4266    | 1        | 0.39%   |
| 4199    | 1        | 0.39%   |
| 4133    | 1        | 0.39%   |
| 4000    | 1        | 0.39%   |
| 3933    | 1        | 0.39%   |
| 3800    | 1        | 0.39%   |
| 3534    | 1        | 0.39%   |
| 3500    | 1        | 0.39%   |
| 3333    | 1        | 0.39%   |
| 3266    | 1        | 0.39%   |
| 3066    | 1        | 0.39%   |
| 2200    | 1        | 0.39%   |
| 2187    | 1        | 0.39%   |
| 1067    | 1        | 0.39%   |
| 667     | 1        | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Hewlett-Packard                    | 2        | 33.33%  |
| Seiko Epson                        | 1        | 16.67%  |
| Canon                              | 1        | 16.67%  |
| Brother Industries                 | 1        | 16.67%  |
| BeiJing LanXum Computer Technology | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson M105 Series                                 | 1        | 16.67%  |
| HP LaserJet 1020                                        | 1        | 16.67%  |
| HP DeskJet 2130 series                                  | 1        | 16.67%  |
| Canon PIXMA MP280                                       | 1        | 16.67%  |
| Brother HL-5440D series                                 | 1        | 16.67%  |
| BeiJing LanXum Technology Black and White Laser Printer | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 120 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 20%     |
| Realtek Semiconductor         | 3        | 10%     |
| Microdia                      | 3        | 10%     |
| Z-Star Microelectronics       | 2        | 6.67%   |
| Sunplus Innovation Technology | 2        | 6.67%   |
| Apple                         | 2        | 6.67%   |
| Alcor Micro                   | 2        | 6.67%   |
| Sonix Technology              | 1        | 3.33%   |
| SN0002                        | 1        | 3.33%   |
| Silicon Motion                | 1        | 3.33%   |
| MacroSilicon                  | 1        | 3.33%   |
| JSXRGB0230-D046               | 1        | 3.33%   |
| IMC Networks                  | 1        | 3.33%   |
| Google                        | 1        | 3.33%   |
| Genesys Logic                 | 1        | 3.33%   |
| Generalplus Technology        | 1        | 3.33%   |
| GEMBIRD                       | 1        | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Realtek USB Camera                      | 2        | 6.45%   |
| Microdia Camera                         | 2        | 6.45%   |
| Logitech Webcam C310                    | 2        | 6.45%   |
| Logitech HD Pro Webcam C920             | 2        | 6.45%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 2        | 6.45%   |
| Z-Star Venus USB2.0 Camera              | 1        | 3.23%   |
| Z-Star Traveler TV 6500 SF Dia-scanner  | 1        | 3.23%   |
| Sunplus papalook AF 925                 | 1        | 3.23%   |
| Sunplus aoni webcam A30                 | 1        | 3.23%   |
| Sonix S1020B                            | 1        | 3.23%   |
| SN0002 HIK 2K USB CAMERA                | 1        | 3.23%   |
| Silicon Motion 300k Pixel Camera        | 1        | 3.23%   |
| Realtek Windows Hello CAM               | 1        | 3.23%   |
| Microdia Document Scanner               | 1        | 3.23%   |
| MacroSilicon USB Video                  | 1        | 3.23%   |
| Logitech Webcam C270                    | 1        | 3.23%   |
| Logitech Logitech Webcam C100           | 1        | 3.23%   |
| Logitech C930c                          | 1        | 3.23%   |
| JSXRGB0230-D046 JSXRGB0230-D046         | 1        | 3.23%   |
| IMC Networks XHC Camera                 | 1        | 3.23%   |
| Google Nexus/Pixel Device (MTP + debug) | 1        | 3.23%   |
| Genesys Logic Camera                    | 1        | 3.23%   |
| Generalplus CAMERA - UVC                | 1        | 3.23%   |
| GEMBIRD USB2.0 PC CAMERA                | 1        | 3.23%   |
| Alcor Micro USB Video Device            | 1        | 3.23%   |
| Alcor Micro USB 2.0 PC cam              | 1        | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Shenzhen Goodix Technology | 1        | 50%     |
| LighTuning Technology      | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Shenzhen Goodix Fingerprint Reader | 1        | 50%     |
| LighTuning Fingerprint Sensor      | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 322      | 73.18%  |
| 1     | 86       | 19.55%  |
| 2     | 17       | 3.86%   |
| 3     | 6        | 1.36%   |
| 4     | 5        | 1.14%   |
| 8     | 1        | 0.23%   |
| 7     | 1        | 0.23%   |
| 6     | 1        | 0.23%   |
| 5     | 1        | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 61       | 36.75%  |
| Net/wireless             | 35       | 21.08%  |
| Communication controller | 18       | 10.84%  |
| Unassigned class         | 13       | 7.83%   |
| Sound                    | 11       | 6.63%   |
| Bluetooth                | 8        | 4.82%   |
| Net/ethernet             | 5        | 3.01%   |
| Storage/raid             | 4        | 2.41%   |
| Network                  | 4        | 2.41%   |
| Fingerprint reader       | 2        | 1.2%    |
| Camera                   | 2        | 1.2%    |
| Storage/ata              | 1        | 0.6%    |
| Chipcard                 | 1        | 0.6%    |
| Card reader              | 1        | 0.6%    |

