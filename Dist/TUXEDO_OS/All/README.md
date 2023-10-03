TUXEDO OS - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for TUXEDO OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/TUXEDO_OS/Desktop/README.md) and [notebooks](/Dist/TUXEDO_OS/Notebook/README.md).

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

Total: 127

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Prestige 15 A10SC           | Notebook    | [6e53cd8a65](https://linux-hardware.org/?probe=6e53cd8a65) | Sep 30, 2023 |
| Metabox       | Prime-X X170KM              | Notebook    | [8ab33a8bd3](https://linux-hardware.org/?probe=8ab33a8bd3) | Sep 30, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | Notebook    | [6d981e4890](https://linux-hardware.org/?probe=6d981e4890) | Sep 29, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [ade3d11822](https://linux-hardware.org/?probe=ade3d11822) | Sep 24, 2023 |
| Schenker      | VISION 15 E23 (SVS15E23)    | Notebook    | [d905d3589d](https://linux-hardware.org/?probe=d905d3589d) | Sep 24, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [147b087f20](https://linux-hardware.org/?probe=147b087f20) | Sep 23, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [0a29d5f7f6](https://linux-hardware.org/?probe=0a29d5f7f6) | Sep 22, 2023 |
| Chuwi         | MiniBook X                  | Notebook    | [50d0819b3b](https://linux-hardware.org/?probe=50d0819b3b) | Sep 20, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [2a7bf627ba](https://linux-hardware.org/?probe=2a7bf627ba) | Sep 19, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [a4f7b61af6](https://linux-hardware.org/?probe=a4f7b61af6) | Sep 18, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [804223592d](https://linux-hardware.org/?probe=804223592d) | Sep 17, 2023 |
| HP            | Pavilion dv5                | Notebook    | [2c55682860](https://linux-hardware.org/?probe=2c55682860) | Sep 15, 2023 |
| HP            | Pavilion dv5                | Notebook    | [8d25f8969b](https://linux-hardware.org/?probe=8d25f8969b) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [6d7c6c42f5](https://linux-hardware.org/?probe=6d7c6c42f5) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [fe64bd3017](https://linux-hardware.org/?probe=fe64bd3017) | Sep 13, 2023 |
| Lenovo        | ThinkPad P50 20EQS37F00     | Notebook    | [0eaf502e28](https://linux-hardware.org/?probe=0eaf502e28) | Sep 12, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | Notebook    | [a28ff634a0](https://linux-hardware.org/?probe=a28ff634a0) | Sep 11, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | Notebook    | [28283f9fcf](https://linux-hardware.org/?probe=28283f9fcf) | Sep 11, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [9ff135c2a6](https://linux-hardware.org/?probe=9ff135c2a6) | Sep 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [abb6dcaeb2](https://linux-hardware.org/?probe=abb6dcaeb2) | Sep 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1e6219cb6e](https://linux-hardware.org/?probe=1e6219cb6e) | Sep 09, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [376e22722b](https://linux-hardware.org/?probe=376e22722b) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [388f380783](https://linux-hardware.org/?probe=388f380783) | Sep 02, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [c53e992822](https://linux-hardware.org/?probe=c53e992822) | Aug 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [679cf99998](https://linux-hardware.org/?probe=679cf99998) | Aug 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cd3074537b](https://linux-hardware.org/?probe=cd3074537b) | Aug 15, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [b6e2112ccb](https://linux-hardware.org/?probe=b6e2112ccb) | Aug 13, 2023 |
| Dell          | Precision 7750              | Notebook    | [cebb7f5165](https://linux-hardware.org/?probe=cebb7f5165) | Aug 06, 2023 |
| TUXEDO        | N7x0WU                      | Notebook    | [1c2cb06178](https://linux-hardware.org/?probe=1c2cb06178) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [01846991de](https://linux-hardware.org/?probe=01846991de) | Aug 04, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [64e640ff2b](https://linux-hardware.org/?probe=64e640ff2b) | Aug 04, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [07d668ee3d](https://linux-hardware.org/?probe=07d668ee3d) | Aug 03, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [c6078d0836](https://linux-hardware.org/?probe=c6078d0836) | Aug 02, 2023 |
| Lenovo        | ThinkPad E580 20KS003SUS    | Notebook    | [9b8485b740](https://linux-hardware.org/?probe=9b8485b740) | Aug 01, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fde0e0e94f](https://linux-hardware.org/?probe=fde0e0e94f) | Jul 29, 2023 |
| HP            | Notebook                    | Notebook    | [beef8e7fce](https://linux-hardware.org/?probe=beef8e7fce) | Jul 25, 2023 |
| HP            | Notebook                    | Notebook    | [4746f66332](https://linux-hardware.org/?probe=4746f66332) | Jul 23, 2023 |
| Lenovo        | ThinkPad 20JB002BUS         | Tablet      | [ac659620e6](https://linux-hardware.org/?probe=ac659620e6) | Jul 20, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [bcd1c01ad6](https://linux-hardware.org/?probe=bcd1c01ad6) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [390008fe3c](https://linux-hardware.org/?probe=390008fe3c) | Jul 15, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [fd0926d15b](https://linux-hardware.org/?probe=fd0926d15b) | Jul 14, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [26fda3b894](https://linux-hardware.org/?probe=26fda3b894) | Jul 14, 2023 |
| Dell          | Latitude E6530              | Notebook    | [25cbd87821](https://linux-hardware.org/?probe=25cbd87821) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [29a9ad60a6](https://linux-hardware.org/?probe=29a9ad60a6) | Jul 13, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [2015dd83cb](https://linux-hardware.org/?probe=2015dd83cb) | Jul 12, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [54ac55c49e](https://linux-hardware.org/?probe=54ac55c49e) | Jul 07, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [296474a1b1](https://linux-hardware.org/?probe=296474a1b1) | Jul 07, 2023 |
| TUXEDO        | Book XUX7 Gen13             | Notebook    | [e480e61359](https://linux-hardware.org/?probe=e480e61359) | Jul 06, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [3d599df965](https://linux-hardware.org/?probe=3d599df965) | Jul 02, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b15b3b6025](https://linux-hardware.org/?probe=b15b3b6025) | Jun 30, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [ed4a581e3e](https://linux-hardware.org/?probe=ed4a581e3e) | Jun 28, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [c2a5aeb291](https://linux-hardware.org/?probe=c2a5aeb291) | Jun 28, 2023 |
| TUXEDO        | P64_HJ,HK1                  | Notebook    | [4c542d50e7](https://linux-hardware.org/?probe=4c542d50e7) | Jun 27, 2023 |
| BESSTAR Te... | X400                        | Notebook    | [8e98b345cf](https://linux-hardware.org/?probe=8e98b345cf) | Jun 26, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [c8f3981a52](https://linux-hardware.org/?probe=c8f3981a52) | Jun 23, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [6fb60cf84a](https://linux-hardware.org/?probe=6fb60cf84a) | Jun 18, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [818c9bc358](https://linux-hardware.org/?probe=818c9bc358) | Jun 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [c47936b50c](https://linux-hardware.org/?probe=c47936b50c) | Jun 09, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c16266c1c9](https://linux-hardware.org/?probe=c16266c1c9) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [f75fb35204](https://linux-hardware.org/?probe=f75fb35204) | May 28, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [66c9773a5f](https://linux-hardware.org/?probe=66c9773a5f) | May 26, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [65cc5e45b0](https://linux-hardware.org/?probe=65cc5e45b0) | May 26, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [7332acbb0e](https://linux-hardware.org/?probe=7332acbb0e) | May 15, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [6142fe7fbd](https://linux-hardware.org/?probe=6142fe7fbd) | May 14, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| Lenovo        | IdeaPad N581 7505           | Notebook    | [5d340c1aa2](https://linux-hardware.org/?probe=5d340c1aa2) | May 04, 2023 |
| HP            | Pavilion dv6                | Notebook    | [be01072653](https://linux-hardware.org/?probe=be01072653) | May 03, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [756500f10b](https://linux-hardware.org/?probe=756500f10b) | May 03, 2023 |
| HP            | Pavilion dv6                | Notebook    | [87f0c054fa](https://linux-hardware.org/?probe=87f0c054fa) | May 03, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Dell          | Inspiron 16 5630            | Notebook    | [7bfe5bb892](https://linux-hardware.org/?probe=7bfe5bb892) | Apr 27, 2023 |
| Dell          | Latitude 7530               | Notebook    | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [04a458482b](https://linux-hardware.org/?probe=04a458482b) | Apr 19, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [3b77631ed6](https://linux-hardware.org/?probe=3b77631ed6) | Apr 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [22c0e4cdec](https://linux-hardware.org/?probe=22c0e4cdec) | Apr 02, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aabb4d79b8](https://linux-hardware.org/?probe=aabb4d79b8) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490 20N3SBU219    | Notebook    | [b8e8125150](https://linux-hardware.org/?probe=b8e8125150) | Mar 27, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [885b757cdc](https://linux-hardware.org/?probe=885b757cdc) | Mar 24, 2023 |
| HP            | 2B3E                        | All in one  | [c6dd260a92](https://linux-hardware.org/?probe=c6dd260a92) | Mar 22, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [5e01f2c134](https://linux-hardware.org/?probe=5e01f2c134) | Mar 22, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [8aaef31933](https://linux-hardware.org/?probe=8aaef31933) | Mar 19, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [0db668b5ec](https://linux-hardware.org/?probe=0db668b5ec) | Mar 18, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [094b530ce7](https://linux-hardware.org/?probe=094b530ce7) | Mar 18, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [3fcbfecb5a](https://linux-hardware.org/?probe=3fcbfecb5a) | Mar 14, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [4c5eee300d](https://linux-hardware.org/?probe=4c5eee300d) | Mar 13, 2023 |
| Dell          | Precision 7720              | Notebook    | [dbe0d4c5c4](https://linux-hardware.org/?probe=dbe0d4c5c4) | Mar 12, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [40a0328a5f](https://linux-hardware.org/?probe=40a0328a5f) | Mar 11, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [3cde6f345c](https://linux-hardware.org/?probe=3cde6f345c) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [769cd87ebd](https://linux-hardware.org/?probe=769cd87ebd) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [e1846f2a68](https://linux-hardware.org/?probe=e1846f2a68) | Mar 07, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [886aa04456](https://linux-hardware.org/?probe=886aa04456) | Mar 07, 2023 |
| Fujitsu       | LIFEBOOK U7412              | Notebook    | [980dd72471](https://linux-hardware.org/?probe=980dd72471) | Mar 06, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [9088ef4d11](https://linux-hardware.org/?probe=9088ef4d11) | Mar 06, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [7a21cf8349](https://linux-hardware.org/?probe=7a21cf8349) | Mar 05, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [20d14c7576](https://linux-hardware.org/?probe=20d14c7576) | Mar 04, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [01f7386d8c](https://linux-hardware.org/?probe=01f7386d8c) | Mar 02, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [1e1da6a575](https://linux-hardware.org/?probe=1e1da6a575) | Feb 24, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [497a8d66e5](https://linux-hardware.org/?probe=497a8d66e5) | Feb 22, 2023 |
| Dell          | Precision 7720              | Notebook    | [2f7837d5b6](https://linux-hardware.org/?probe=2f7837d5b6) | Feb 21, 2023 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [4f507f4e5a](https://linux-hardware.org/?probe=4f507f4e5a) | Feb 20, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [7cc71e6021](https://linux-hardware.org/?probe=7cc71e6021) | Feb 12, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [ed14b057dd](https://linux-hardware.org/?probe=ed14b057dd) | Feb 09, 2023 |
| HP            | 2B34                        | Desktop     | [3376fc38b3](https://linux-hardware.org/?probe=3376fc38b3) | Feb 05, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [4a2fcb6bd0](https://linux-hardware.org/?probe=4a2fcb6bd0) | Jan 31, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [e163d98802](https://linux-hardware.org/?probe=e163d98802) | Jan 28, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [fa53a29f7e](https://linux-hardware.org/?probe=fa53a29f7e) | Jan 01, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [aeb826326b](https://linux-hardware.org/?probe=aeb826326b) | Dec 20, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [731b31c845](https://linux-hardware.org/?probe=731b31c845) | Dec 02, 2022 |
| TUXEDO        | N13xWU                      | Notebook    | [55935f091d](https://linux-hardware.org/?probe=55935f091d) | Dec 01, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [fd06ca029c](https://linux-hardware.org/?probe=fd06ca029c) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [5043f6c54e](https://linux-hardware.org/?probe=5043f6c54e) | Nov 20, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [5d82e9f6ac](https://linux-hardware.org/?probe=5d82e9f6ac) | Nov 19, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [9d20af2c30](https://linux-hardware.org/?probe=9d20af2c30) | Nov 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | Notebook    | [d58eb8b2f0](https://linux-hardware.org/?probe=d58eb8b2f0) | Oct 30, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | Notebook    | [032bc01698](https://linux-hardware.org/?probe=032bc01698) | Oct 30, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [99555fc4eb](https://linux-hardware.org/?probe=99555fc4eb) | Oct 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| ASUSTek       | BU201LAV                    | Notebook    | [9d1fe7cb6f](https://linux-hardware.org/?probe=9d1fe7cb6f) | Oct 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [36e033aa01](https://linux-hardware.org/?probe=36e033aa01) | Oct 09, 2022 |
| Notebook      | W65_W67RB                   | Notebook    | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| TUXEDO OS 22.04 | 98        | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 98        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 6.1.0-1009-tuxedo    | 17        | 16.35%  |
| 6.2.0-10018-tuxedo   | 14        | 13.46%  |
| 6.2.0-10007-tuxedo   | 11        | 10.58%  |
| 6.2.0-10005-tuxedo   | 11        | 10.58%  |
| 6.2.0-10022-tuxedo   | 10        | 9.62%   |
| 6.2.0-10011-tuxedo   | 9         | 8.65%   |
| 5.15.0-10058-tuxedo  | 7         | 6.73%   |
| 6.2.0-10010-tuxedo   | 6         | 5.77%   |
| 5.15.0-10048-tuxedo  | 4         | 3.85%   |
| 5.15.0-10053-tuxedo  | 3         | 2.88%   |
| 5.15.0-10052-tuxedo  | 3         | 2.88%   |
| 5.15.0-10057-tuxedo  | 2         | 1.92%   |
| 5.15.0-10056-tuxedo  | 2         | 1.92%   |
| 5.15.0-10050-tuxedo  | 2         | 1.92%   |
| 6.5.4-060504-generic | 1         | 0.96%   |
| 6.2.0-10014-tuxedo   | 1         | 0.96%   |
| 6.0.0-1010-oem       | 1         | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 62        | 59.62%  |
| 5.15.0  | 23        | 22.12%  |
| 6.1.0   | 17        | 16.35%  |
| 6.5.4   | 1         | 0.96%   |
| 6.0.0   | 1         | 0.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 62        | 59.62%  |
| 5.15    | 23        | 22.12%  |
| 6.1     | 17        | 16.35%  |
| 6.5     | 1         | 0.96%   |
| 6.0     | 1         | 0.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 98        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| KDE5 | 98        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 95        | 95.96%  |
| Wayland | 4         | 4.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 79        | 79%     |
| SDDM    | 21        | 21%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| de_DE | 45        | 45.92%  |
| en_US | 21        | 21.43%  |
| en_GB | 7         | 7.14%   |
| pl_PL | 3         | 3.06%   |
| en_ZA | 3         | 3.06%   |
| en_AU | 3         | 3.06%   |
| en_AG | 3         | 3.06%   |
| pt_PT | 2         | 2.04%   |
| it_IT | 2         | 2.04%   |
| fr_FR | 2         | 2.04%   |
| pt_BR | 1         | 1.02%   |
| hu_HU | 1         | 1.02%   |
| es_ES | 1         | 1.02%   |
| en_DK | 1         | 1.02%   |
| en_CA | 1         | 1.02%   |
| de_CH | 1         | 1.02%   |
| de_AT | 1         | 1.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 81        | 81.82%  |
| EFI  | 18        | 18.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 82        | 82.83%  |
| Btrfs   | 9         | 9.09%   |
| Tmpfs   | 3         | 3.03%   |
| Overlay | 3         | 3.03%   |
| Xfs     | 2         | 2.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 79        | 79%     |
| GPT     | 19        | 19%     |
| MBR     | 2         | 2%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 93        | 93.94%  |
| Yes       | 6         | 6.06%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 92.93%  |
| Yes       | 7         | 7.07%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| TUXEDO              | 30        | 30.61%  |
| Lenovo              | 13        | 13.27%  |
| Hewlett-Packard     | 12        | 12.24%  |
| ASUSTek Computer    | 11        | 11.22%  |
| Dell                | 9         | 9.18%   |
| MSI                 | 5         | 5.1%    |
| Apple               | 4         | 4.08%   |
| ASRock              | 3         | 3.06%   |
| Acer                | 2         | 2.04%   |
| Schenker            | 1         | 1.02%   |
| Notebook            | 1         | 1.02%   |
| Metabox             | 1         | 1.02%   |
| Gigabyte Technology | 1         | 1.02%   |
| Fujitsu             | 1         | 1.02%   |
| Fanless Mini PC     | 1         | 1.02%   |
| Chuwi               | 1         | 1.02%   |
| BESSTAR Tech        | 1         | 1.02%   |
| Unknown             | 1         | 1.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| TUXEDO InfinityBook S 15/17 Gen7    | 4         | 4.08%   |
| Unknown                             | 3         | 3.06%   |
| TUXEDO Stellaris/Polaris AMD Gen4   | 2         | 2.04%   |
| TUXEDO Stellaris Intel Gen5         | 2         | 2.04%   |
| TUXEDO Pulse 15 Gen2                | 2         | 2.04%   |
| TUXEDO Pulse 15 Gen1                | 2         | 2.04%   |
| TUXEDO InfinityBook Pro Gen7 (MK2)  | 2         | 2.04%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 2         | 2.04%   |
| TUXEDO InfinityBook Pro 14 Gen6     | 2         | 2.04%   |
| MSI MS-7D17                         | 2         | 2.04%   |
| ASUS PRIME B450-PLUS                | 2         | 2.04%   |
| Apple MacBookPro8,1                 | 2         | 2.04%   |
| TUXEDO XMG FUSION 15 (XFU15L19)     | 1         | 1.02%   |
| TUXEDO Stellaris AMD Gen3 (CZN)     | 1         | 1.02%   |
| TUXEDO Polaris AMD Gen3 (CZN)       | 1         | 1.02%   |
| TUXEDO Polaris 15 AMD Gen1          | 1         | 1.02%   |
| TUXEDO P64_HJ,HK1                   | 1         | 1.02%   |
| TUXEDO N7x0WU                       | 1         | 1.02%   |
| TUXEDO N13xWU                       | 1         | 1.02%   |
| TUXEDO InfinityBook S 15 Gen6       | 1         | 1.02%   |
| TUXEDO Book XUX7 Gen13              | 1         | 1.02%   |
| TUXEDO Aura 15 Gen2                 | 1         | 1.02%   |
| Schenker VISION 15 E23 (SVS15E23)   | 1         | 1.02%   |
| Notebook W65_W67RB                  | 1         | 1.02%   |
| MSI Prestige 15 A10SC               | 1         | 1.02%   |
| MSI MS-7D25                         | 1         | 1.02%   |
| MSI GE75 Raider 10SF                | 1         | 1.02%   |
| Metabox Prime-X X170KM              | 1         | 1.02%   |
| Lenovo Yoga S740-15IRH 81NX         | 1         | 1.02%   |
| Lenovo ThinkPad X200 Tablet 7450WN9 | 1         | 1.02%   |
| Lenovo ThinkPad T490 20N3SBU219     | 1         | 1.02%   |
| Lenovo ThinkPad P50 20EQS37F00      | 1         | 1.02%   |
| Lenovo ThinkPad P1 Gen 3 20TJS1W700 | 1         | 1.02%   |
| Lenovo ThinkPad E580 20KS003SUS     | 1         | 1.02%   |
| Lenovo ThinkPad 20JB002BUS          | 1         | 1.02%   |
| Lenovo ThinkCentre M700 10GSS05X48  | 1         | 1.02%   |
| Lenovo ThinkBook 14 G2 ARE 20VF     | 1         | 1.02%   |
| Lenovo Legion 5 15ACH6H 82JU        | 1         | 1.02%   |
| Lenovo IdeaPad N581 7505            | 1         | 1.02%   |
| Lenovo G580 20150                   | 1         | 1.02%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| TUXEDO InfinityBook | 11        | 11.22%  |
| Lenovo ThinkPad     | 6         | 6.12%   |
| TUXEDO Stellaris    | 5         | 5.1%    |
| TUXEDO Pulse        | 4         | 4.08%   |
| HP Pavilion         | 3         | 3.06%   |
| ASUS ROG            | 3         | 3.06%   |
| ASUS PRIME          | 3         | 3.06%   |
| Unknown             | 3         | 3.06%   |
| TUXEDO Polaris      | 2         | 2.04%   |
| MSI MS-7D17         | 2         | 2.04%   |
| HP Laptop           | 2         | 2.04%   |
| HP EliteBook        | 2         | 2.04%   |
| Dell Precision      | 2         | 2.04%   |
| Dell Latitude       | 2         | 2.04%   |
| Dell Inspiron       | 2         | 2.04%   |
| Apple MacBookPro8   | 2         | 2.04%   |
| TUXEDO XMG          | 1         | 1.02%   |
| TUXEDO P64          | 1         | 1.02%   |
| TUXEDO N7x0WU       | 1         | 1.02%   |
| TUXEDO N13xWU       | 1         | 1.02%   |
| TUXEDO Book         | 1         | 1.02%   |
| TUXEDO Aura         | 1         | 1.02%   |
| Schenker VISION     | 1         | 1.02%   |
| Notebook W65        | 1         | 1.02%   |
| MSI Prestige        | 1         | 1.02%   |
| MSI MS-7D25         | 1         | 1.02%   |
| MSI GE75            | 1         | 1.02%   |
| Metabox Prime-X     | 1         | 1.02%   |
| Lenovo Yoga         | 1         | 1.02%   |
| Lenovo ThinkCentre  | 1         | 1.02%   |
| Lenovo ThinkBook    | 1         | 1.02%   |
| Lenovo Legion       | 1         | 1.02%   |
| Lenovo IdeaPad      | 1         | 1.02%   |
| Lenovo G580         | 1         | 1.02%   |
| Lenovo G50-80       | 1         | 1.02%   |
| HP ZBook            | 1         | 1.02%   |
| HP OMEN             | 1         | 1.02%   |
| HP Notebook         | 1         | 1.02%   |
| HP ENVY             | 1         | 1.02%   |
| HP 280              | 1         | 1.02%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 22        | 22.45%  |
| 2020 | 14        | 14.29%  |
| 2021 | 12        | 12.24%  |
| 2019 | 8         | 8.16%   |
| 2015 | 8         | 8.16%   |
| 2012 | 6         | 6.12%   |
| 2023 | 5         | 5.1%    |
| 2018 | 4         | 4.08%   |
| 2017 | 4         | 4.08%   |
| 2011 | 4         | 4.08%   |
| 2014 | 3         | 3.06%   |
| 2016 | 2         | 2.04%   |
| 2013 | 2         | 2.04%   |
| 2008 | 2         | 2.04%   |
| 2010 | 1         | 1.02%   |
| 2009 | 1         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 77        | 78.57%  |
| Desktop     | 18        | 18.37%  |
| Tablet      | 1         | 1.02%   |
| Convertible | 1         | 1.02%   |
| Mini pc     | 1         | 1.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 98        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 98        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 21        | 21.43%  |
| 16.01-24.0  | 21        | 21.43%  |
| 8.01-16.0   | 18        | 18.37%  |
| 4.01-8.0    | 16        | 16.33%  |
| 64.01-256.0 | 12        | 12.24%  |
| 3.01-4.0    | 7         | 7.14%   |
| 24.01-32.0  | 3         | 3.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 34        | 33.01%  |
| 2.01-3.0   | 24        | 23.3%   |
| 1.01-2.0   | 22        | 21.36%  |
| 3.01-4.0   | 14        | 13.59%  |
| 8.01-16.0  | 7         | 6.8%    |
| 16.01-24.0 | 2         | 1.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 50.51%  |
| 2      | 36        | 36.36%  |
| 3      | 5         | 5.05%   |
| 4      | 4         | 4.04%   |
| 5      | 3         | 3.03%   |
| 6      | 1         | 1.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 81        | 82.65%  |
| Yes       | 17        | 17.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 83.67%  |
| No        | 16        | 16.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 90.82%  |
| No        | 9         | 9.18%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 82.83%  |
| No        | 17        | 17.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 49        | 50%     |
| USA          | 10        | 10.2%   |
| UK           | 5         | 5.1%    |
| Switzerland  | 4         | 4.08%   |
| South Africa | 3         | 3.06%   |
| Portugal     | 3         | 3.06%   |
| Poland       | 3         | 3.06%   |
| Austria      | 3         | 3.06%   |
| Australia    | 3         | 3.06%   |
| Spain        | 2         | 2.04%   |
| Netherlands  | 2         | 2.04%   |
| France       | 2         | 2.04%   |
| Turkey       | 1         | 1.02%   |
| Romania      | 1         | 1.02%   |
| Egypt        | 1         | 1.02%   |
| Denmark      | 1         | 1.02%   |
| Czechia      | 1         | 1.02%   |
| Canada       | 1         | 1.02%   |
| Bulgaria     | 1         | 1.02%   |
| Brazil       | 1         | 1.02%   |
| Aruba        | 1         | 1.02%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Munich                 | 5         | 5.05%   |
| Vienna                 | 3         | 3.03%   |
| Zurich                 | 2         | 2.02%   |
| Schweinfurt            | 2         | 2.02%   |
| Nuremberg              | 2         | 2.02%   |
| Lucerne                | 2         | 2.02%   |
| Leipzig                | 2         | 2.02%   |
| Johannesburg           | 2         | 2.02%   |
| Hürth                 | 2         | 2.02%   |
| Brisbane               | 2         | 2.02%   |
| Berlin                 | 2         | 2.02%   |
| Zalău                 | 1         | 1.01%   |
| Zabrze                 | 1         | 1.01%   |
| Wembley                | 1         | 1.01%   |
| Watertown              | 1         | 1.01%   |
| Warsaw                 | 1         | 1.01%   |
| Walsall                | 1         | 1.01%   |
| Venlo                  | 1         | 1.01%   |
| Vallejo                | 1         | 1.01%   |
| Ulm                    | 1         | 1.01%   |
| Stuttgart              | 1         | 1.01%   |
| Stockstadt am Main     | 1         | 1.01%   |
| Solingen               | 1         | 1.01%   |
| Sistov                 | 1         | 1.01%   |
| Seattle                | 1         | 1.01%   |
| Schwarzenberg          | 1         | 1.01%   |
| Santa Cruz de Tenerife | 1         | 1.01%   |
| Rio Maior              | 1         | 1.01%   |
| Reno                   | 1         | 1.01%   |
| Rennes                 | 1         | 1.01%   |
| Redcar                 | 1         | 1.01%   |
| Quarteira              | 1         | 1.01%   |
| Pruem                  | 1         | 1.01%   |
| Prague                 | 1         | 1.01%   |
| Perth                  | 1         | 1.01%   |
| Perrysburg             | 1         | 1.01%   |
| Peitz                  | 1         | 1.01%   |
| Paris                  | 1         | 1.01%   |
| Paderborn              | 1         | 1.01%   |
| Oranjestad             | 1         | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 53        | 70     | 35.81%  |
| Seagate                     | 16        | 21     | 10.81%  |
| SanDisk                     | 16        | 19     | 10.81%  |
| Kingston                    | 6         | 6      | 4.05%   |
| Hitachi                     | 6         | 9      | 4.05%   |
| WDC                         | 5         | 6      | 3.38%   |
| Toshiba                     | 3         | 4      | 2.03%   |
| Micron/Crucial Technology   | 3         | 5      | 2.03%   |
| Unknown                     | 2         | 2      | 1.35%   |
| SPCC                        | 2         | 2      | 1.35%   |
| SK hynix                    | 2         | 3      | 1.35%   |
| Phison Electronics          | 2         | 2      | 1.35%   |
| Micron Technology           | 2         | 2      | 1.35%   |
| GOODRAM                     | 2         | 2      | 1.35%   |
| USB3.0                      | 1         | 1      | 0.68%   |
| Transcend                   | 1         | 1      | 0.68%   |
| Silicon Motion              | 1         | 2      | 0.68%   |
| Phison                      | 1         | 3      | 0.68%   |
| OWC                         | 1         | 1      | 0.68%   |
| Netac                       | 1         | 1      | 0.68%   |
| LITEONIT                    | 1         | 1      | 0.68%   |
| Lite-On Technology          | 1         | 1      | 0.68%   |
| Lenovo                      | 1         | 1      | 0.68%   |
| Kingston Technology Company | 1         | 1      | 0.68%   |
| KingFast                    | 1         | 1      | 0.68%   |
| Kingchuxing                 | 1         | 1      | 0.68%   |
| Intenso                     | 1         | 1      | 0.68%   |
| Intel                       | 1         | 1      | 0.68%   |
| HS-SSD-E100                 | 1         | 1      | 0.68%   |
| Hikvision                   | 1         | 2      | 0.68%   |
| HGST HTS                    | 1         | 1      | 0.68%   |
| HGST                        | 1         | 1      | 0.68%   |
| CT1000BX                    | 1         | 1      | 0.68%   |
| Crucial                     | 1         | 1      | 0.68%   |
| China                       | 1         | 1      | 0.68%   |
| ASMT                        | 1         | 1      | 0.68%   |
| ASMedia                     | 1         | 1      | 0.68%   |
| Apple                       | 1         | 1      | 0.68%   |
| Apacer                      | 1         | 1      | 0.68%   |
| AMD                         | 1         | 2      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 10        | 6.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 9         | 5.59%   |
| Samsung SSD 980 500GB                               | 8         | 4.97%   |
| Samsung SSD 980 1TB                                 | 6         | 3.73%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 5         | 3.11%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 1.86%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 3         | 1.86%   |
| Seagate ST3500418AS 500GB                           | 2         | 1.24%   |
| Seagate ST1000VT001-1RE172 1TB                      | 2         | 1.24%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 1.24%   |
| Sandisk WD Black SN850 1TB                          | 2         | 1.24%   |
| SanDisk SSD PLUS 120GB                              | 2         | 1.24%   |
| SanDisk SDSSDA240G 240GB                            | 2         | 1.24%   |
| Samsung SSD 980 PRO 500GB                           | 2         | 1.24%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 1.24%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 1.24%   |
| Samsung SSD 850 EVO 1TB                             | 2         | 1.24%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1.24%   |
| Hitachi HTS727550A9E364 500GB                       | 2         | 1.24%   |
| Hitachi HCS545050GLA380 500GB                       | 2         | 1.24%   |
| WDC WD80EAZZ-00BKLB0 8TB                            | 1         | 0.62%   |
| WDC WD3200BPVT-24JJ5T0 320GB                        | 1         | 0.62%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1         | 0.62%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.62%   |
| WDC WD10JPVX-11JC3T0 1TB                            | 1         | 0.62%   |
| WDC WD Elements SE SSD 1TB                          | 1         | 0.62%   |
| USB3.0 Super Speed 500GB                            | 1         | 0.62%   |
| Unknown MMC Card  64GB                              | 1         | 0.62%   |
| Unknown MMC Card  2GB                               | 1         | 0.62%   |
| Transcend TS512GSSD230S 512GB                       | 1         | 0.62%   |
| Toshiba XG4 NVMe SSD Controller 512GB               | 1         | 0.62%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.62%   |
| Toshiba BG3 NVMe SSD Controller 512GB               | 1         | 0.62%   |
| SPCC M.2 SSD 256GB                                  | 1         | 0.62%   |
| SPCC M.2 PCIe SSD 1TB                               | 1         | 0.62%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 1         | 0.62%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 0.62%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 500GB | 1         | 0.62%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 0.62%   |
| Seagate ST500LM034-2GH17A 500GB                     | 1         | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 15        | 20     | 51.72%  |
| Hitachi  | 6         | 9      | 20.69%  |
| WDC      | 4         | 5      | 13.79%  |
| USB3.0   | 1         | 1      | 3.45%   |
| Toshiba  | 1         | 1      | 3.45%   |
| HGST HTS | 1         | 1      | 3.45%   |
| HGST     | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 29.73%  |
| SanDisk             | 5         | 6      | 13.51%  |
| Kingston            | 4         | 4      | 10.81%  |
| GOODRAM             | 2         | 2      | 5.41%   |
| WDC                 | 1         | 1      | 2.7%    |
| Transcend           | 1         | 1      | 2.7%    |
| SPCC                | 1         | 1      | 2.7%    |
| SK hynix            | 1         | 2      | 2.7%    |
| OWC                 | 1         | 1      | 2.7%    |
| Netac               | 1         | 1      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| LITEONIT            | 1         | 1      | 2.7%    |
| Intenso             | 1         | 1      | 2.7%    |
| CT1000BX            | 1         | 1      | 2.7%    |
| Crucial             | 1         | 1      | 2.7%    |
| China               | 1         | 1      | 2.7%    |
| ASMT                | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |
| Apacer              | 1         | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 67        | 101    | 50.38%  |
| SSD     | 32        | 40     | 24.06%  |
| HDD     | 27        | 38     | 20.3%   |
| Unknown | 4         | 4      | 3.01%   |
| MMC     | 3         | 3      | 2.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 67        | 101    | 54.03%  |
| SATA | 48        | 75     | 38.71%  |
| SAS  | 6         | 7      | 4.84%   |
| MMC  | 3         | 3      | 2.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 47     | 52.46%  |
| 0.51-1.0   | 23        | 25     | 37.7%   |
| 1.01-2.0   | 4         | 4      | 6.56%   |
| 4.01-10.0  | 2         | 2      | 3.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 28        | 28.28%  |
| 251-500        | 20        | 20.2%   |
| 101-250        | 20        | 20.2%   |
| 1001-2000      | 11        | 11.11%  |
| 2001-3000      | 5         | 5.05%   |
| 1-20           | 5         | 5.05%   |
| More than 3000 | 4         | 4.04%   |
| 21-50          | 2         | 2.02%   |
| 51-100         | 2         | 2.02%   |
| Unknown        | 2         | 2.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 31        | 30.69%  |
| 21-50          | 29        | 28.71%  |
| 101-250        | 14        | 13.86%  |
| 251-500        | 8         | 7.92%   |
| 51-100         | 8         | 7.92%   |
| 501-1000       | 5         | 4.95%   |
| 1001-2000      | 3         | 2.97%   |
| Unknown        | 2         | 1.98%   |
| More than 3000 | 1         | 0.99%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 80        | 153    | 78.43%  |
| Works    | 22        | 33     | 21.57%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 49        | 35.25%  |
| Samsung Electronics          | 45        | 32.37%  |
| AMD                          | 15        | 10.79%  |
| SanDisk                      | 11        | 7.91%   |
| Phison Electronics           | 3         | 2.16%   |
| Micron/Crucial Technology    | 3         | 2.16%   |
| Kingston Technology Company  | 3         | 2.16%   |
| Toshiba America Info Systems | 2         | 1.44%   |
| Silicon Motion               | 2         | 1.44%   |
| SK hynix                     | 1         | 0.72%   |
| Seagate Technology           | 1         | 0.72%   |
| Micron Technology            | 1         | 0.72%   |
| Lite-On Technology           | 1         | 0.72%   |
| Lenovo                       | 1         | 0.72%   |
| ADATA Technology             | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980                                                | 14        | 9.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 8.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 13        | 8.72%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 8.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 3.36%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.68%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 3         | 2.01%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 2.01%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.01%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 2.01%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 1.34%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.34%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2         | 1.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.34%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.34%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.34%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.67%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.67%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.67%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                      | 1         | 0.67%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 0.67%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 0.67%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.67%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.67%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.67%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.67%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.67%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 0.67%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 0.67%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.67%   |
| Lenovo LENSE30256GMSP34MEAT3TA                                                 | 1         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 67        | 50.38%  |
| SATA | 57        | 42.86%  |
| RAID | 7         | 5.26%   |
| IDE  | 2         | 1.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 73        | 74.49%  |
| AMD    | 25        | 25.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H                 | 4         | 4.08%   |
| Intel 12th Gen Core i7-1260P                  | 4         | 4.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 3.06%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 3         | 3.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.04%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 2.04%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 2.04%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 2.04%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 2.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 2.04%   |
| Intel 13th Gen Core i9-13900HX                | 2         | 2.04%   |
| Intel 12th Gen Core i7-1255U                  | 2         | 2.04%   |
| Intel 12th Gen Core i5-1240P                  | 2         | 2.04%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 2         | 2.04%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 2.04%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 2.04%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 2.04%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 2.04%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.04%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 1.02%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 1         | 1.02%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 1.02%   |
| Intel N100                                    | 1         | 1.02%   |
| Intel Core i9-10900KF CPU @ 3.70GHz           | 1         | 1.02%   |
| Intel Core i7-7Y75 CPU @ 1.30GHz              | 1         | 1.02%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 1.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.02%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.02%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.02%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 1.02%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.02%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 1.02%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.02%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.02%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.02%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 1.02%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.02%   |
| Intel Core i5-7600T CPU @ 2.80GHz             | 1         | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Other            | 26        | 26.53%  |
| Intel Core i7    | 22        | 22.45%  |
| Intel Core i5    | 16        | 16.33%  |
| AMD Ryzen 7      | 11        | 11.22%  |
| AMD Ryzen 5      | 7         | 7.14%   |
| Intel Pentium    | 2         | 2.04%   |
| Intel Core i3    | 2         | 2.04%   |
| Intel Celeron    | 2         | 2.04%   |
| AMD Ryzen 9      | 2         | 2.04%   |
| AMD Ryzen 3      | 2         | 2.04%   |
| Intel Xeon       | 1         | 1.02%   |
| Intel Core i9    | 1         | 1.02%   |
| Intel Core 2 Duo | 1         | 1.02%   |
| AMD Turion II    | 1         | 1.02%   |
| AMD Ryzen 5 PRO  | 1         | 1.02%   |
| AMD A8           | 1         | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 31        | 31.63%  |
| 2      | 19        | 19.39%  |
| 6      | 17        | 17.35%  |
| 8      | 14        | 14.29%  |
| 12     | 7         | 7.14%   |
| 14     | 4         | 4.08%   |
| 10     | 3         | 3.06%   |
| 24     | 2         | 2.04%   |
| 16     | 1         | 1.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 98        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 85        | 86.73%  |
| 1      | 13        | 13.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 98        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 88%     |
| 0x906a4    | 2         | 2%      |
| 0xa0653    | 1         | 1%      |
| 0x906ea    | 1         | 1%      |
| 0x906e9    | 1         | 1%      |
| 0x906a3    | 1         | 1%      |
| 0x806c1    | 1         | 1%      |
| 0x306d4    | 1         | 1%      |
| 0x0a50000d | 1         | 1%      |
| 0x0a50000c | 1         | 1%      |
| 0x08608103 | 1         | 1%      |
| 0x010000c8 | 1         | 1%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 21        | 21.43%  |
| KabyLake         | 13        | 13.27%  |
| IvyBridge        | 9         | 9.18%   |
| Zen 2            | 8         | 8.16%   |
| CometLake        | 7         | 7.14%   |
| Zen 3            | 6         | 6.12%   |
| Alderlake Hybrid | 6         | 6.12%   |
| TigerLake        | 4         | 4.08%   |
| Skylake          | 4         | 4.08%   |
| SandyBridge      | 4         | 4.08%   |
| Haswell          | 4         | 4.08%   |
| Zen+             | 3         | 3.06%   |
| Broadwell        | 3         | 3.06%   |
| Westmere         | 1         | 1.02%   |
| Puma             | 1         | 1.02%   |
| Penryn           | 1         | 1.02%   |
| K10              | 1         | 1.02%   |
| Gracemont        | 1         | 1.02%   |
| Goldmont plus    | 1         | 1.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 66        | 51.16%  |
| Nvidia | 37        | 28.68%  |
| AMD    | 26        | 20.16%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P Integrated Graphics Controller                           | 10        | 7.75%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 5.43%   |
| AMD Renoir                                                                  | 6         | 4.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 3.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 4         | 3.1%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 4         | 3.1%    |
| Intel UHD Graphics 620                                                      | 4         | 3.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 3.1%    |
| Intel HD Graphics 530                                                       | 4         | 3.1%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 3.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 3.1%    |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                    | 3         | 2.33%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                               | 3         | 2.33%   |
| Intel HD Graphics 630                                                       | 3         | 2.33%   |
| AMD Rembrandt [Radeon 680M]                                                 | 3         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 2.33%   |
| AMD Lucienne                                                                | 3         | 2.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.55%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.55%   |
| Nvidia GF108M [GeForce GT 635M]                                             | 2         | 1.55%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                             | 2         | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.55%   |
| Intel Raptor Lake-S UHD Graphics                                            | 2         | 1.55%   |
| Intel HD Graphics 5500                                                      | 2         | 1.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.55%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 2         | 1.55%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.78%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1         | 0.78%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 0.78%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.78%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                            | 1         | 0.78%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.78%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 0.78%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 1         | 0.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 43        | 43.43%  |
| Intel + Nvidia | 18        | 18.18%  |
| 1 x AMD        | 15        | 15.15%  |
| 1 x Nvidia     | 11        | 11.11%  |
| AMD + Nvidia   | 8         | 8.08%   |
| Intel + AMD    | 4         | 4.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 66        | 67.35%  |
| Proprietary | 31        | 31.63%  |
| Unknown     | 1         | 1.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 67.68%  |
| 5.01-6.0   | 10        | 10.1%   |
| 7.01-8.0   | 8         | 8.08%   |
| 3.01-4.0   | 7         | 7.07%   |
| 1.01-2.0   | 3         | 3.03%   |
| 8.01-16.0  | 2         | 2.02%   |
| 0.01-0.5   | 2         | 2.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 28        | 23.93%  |
| Samsung Electronics | 15        | 12.82%  |
| AU Optronics        | 15        | 12.82%  |
| Acer                | 8         | 6.84%   |
| LG Display          | 7         | 5.98%   |
| Chimei Innolux      | 6         | 5.13%   |
| Dell                | 5         | 4.27%   |
| Goldstar            | 4         | 3.42%   |
| CSO                 | 4         | 3.42%   |
| Apple               | 4         | 3.42%   |
| Lenovo              | 2         | 1.71%   |
| Iiyama              | 2         | 1.71%   |
| Hewlett-Packard     | 2         | 1.71%   |
| BenQ                | 2         | 1.71%   |
| AOC                 | 2         | 1.71%   |
| Yamaha              | 1         | 0.85%   |
| ViewSonic           | 1         | 0.85%   |
| Sony                | 1         | 0.85%   |
| Sharp               | 1         | 0.85%   |
| SGT                 | 1         | 0.85%   |
| RTK                 | 1         | 0.85%   |
| Philips             | 1         | 0.85%   |
| PANDA               | 1         | 0.85%   |
| InfoVision          | 1         | 0.85%   |
| Eizo                | 1         | 0.85%   |
| ASUSTek Computer    | 1         | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 5         | 4.13%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 4         | 3.31%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 4         | 3.31%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                     | 2         | 1.65%   |
| BOE LCD Monitor BOE0AF0 2560x1600 344x215mm 16.0-inch                   | 2         | 1.65%   |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch                   | 2         | 1.65%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 2         | 1.65%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 1.65%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                  | 2         | 1.65%   |
| Acer EK240Y ACR0758 1920x1080 520x320mm 24.0-inch                       | 2         | 1.65%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.83%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1         | 0.83%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                           | 1         | 0.83%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.83%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 0.83%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 0.83%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch       | 1         | 0.83%   |
| Samsung Electronics S27C36x SAM7315 1920x1080 598x336mm 27.0-inch       | 1         | 0.83%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 1         | 0.83%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC424D 2160x1440 254x169mm 12.0-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch    | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.83%   |
| Samsung Electronics LC27T55 SAM701E 1920x1080 609x349mm 27.6-inch       | 1         | 0.83%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch       | 1         | 0.83%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 0.83%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch       | 1         | 0.83%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 0.83%   |
| RTK Wimaxit FHD RTK5A5B 1920x1080 344x195mm 15.6-inch                   | 1         | 0.83%   |
| Philips 170S4 PHL0818 1280x1024 338x270mm 17.0-inch                     | 1         | 0.83%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.83%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD0545 3200x1800 293x165mm 13.2-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch            | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 52        | 48.15%  |
| 1366x768 (WXGA)    | 12        | 11.11%  |
| 2560x1440 (QHD)    | 10        | 9.26%   |
| 3840x2160 (4K)     | 7         | 6.48%   |
| 2880x1800          | 4         | 3.7%    |
| 2560x1600          | 4         | 3.7%    |
| 1280x800 (WXGA)    | 4         | 3.7%    |
| 1920x1200 (WUXGA)  | 3         | 2.78%   |
| 1600x900 (HD+)     | 2         | 1.85%   |
| 1280x1024 (SXGA)   | 2         | 1.85%   |
| 3440x1440          | 1         | 0.93%   |
| 3200x1800 (QHD+)   | 1         | 0.93%   |
| 2560x1080          | 1         | 0.93%   |
| 2240x1400          | 1         | 0.93%   |
| 2160x1440          | 1         | 0.93%   |
| 1920x540           | 1         | 0.93%   |
| 1680x1050 (WSXGA+) | 1         | 0.93%   |
| 1440x900 (WXGA+)   | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 38        | 32.2%   |
| 27      | 10        | 8.47%   |
| 17      | 9         | 7.63%   |
| 14      | 9         | 7.63%   |
| 13      | 9         | 7.63%   |
| 24      | 8         | 6.78%   |
| 16      | 6         | 5.08%   |
| 12      | 5         | 4.24%   |
| 21      | 4         | 3.39%   |
| 31      | 3         | 2.54%   |
| 23      | 3         | 2.54%   |
| 40      | 2         | 1.69%   |
| 22      | 2         | 1.69%   |
| 20      | 2         | 1.69%   |
| 84      | 1         | 0.85%   |
| 60      | 1         | 0.85%   |
| 43      | 1         | 0.85%   |
| 34      | 1         | 0.85%   |
| 33      | 1         | 0.85%   |
| 19      | 1         | 0.85%   |
| 18      | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 47.37%  |
| 501-600     | 18        | 15.79%  |
| 201-300     | 12        | 10.53%  |
| 351-400     | 10        | 8.77%   |
| 401-500     | 9         | 7.89%   |
| 801-900     | 3         | 2.63%   |
| 601-700     | 3         | 2.63%   |
| 701-800     | 1         | 0.88%   |
| 1501-2000   | 1         | 0.88%   |
| 1001-1500   | 1         | 0.88%   |
| 901-1000    | 1         | 0.88%   |
| Unknown     | 1         | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 78        | 75%     |
| 16/10 | 19        | 18.27%  |
| 5/4   | 2         | 1.92%   |
| 3/2   | 2         | 1.92%   |
| 21/9  | 2         | 1.92%   |
| 32/9  | 1         | 0.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 32.2%   |
| 81-90          | 16        | 13.56%  |
| 201-250        | 11        | 9.32%   |
| 301-350        | 10        | 8.47%   |
| 121-130        | 8         | 6.78%   |
| 151-200        | 6         | 5.08%   |
| 111-120        | 6         | 5.08%   |
| 61-70          | 5         | 4.24%   |
| 351-500        | 5         | 4.24%   |
| 251-300        | 3         | 2.54%   |
| 501-1000       | 3         | 2.54%   |
| More than 1000 | 2         | 1.69%   |
| 71-80          | 2         | 1.69%   |
| 141-150        | 2         | 1.69%   |
| Unknown        | 1         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 35.71%  |
| 101-120       | 24        | 21.43%  |
| 51-100        | 24        | 21.43%  |
| 161-240       | 15        | 13.39%  |
| More than 240 | 7         | 6.25%   |
| 1-50          | 1         | 0.89%   |
| Unknown       | 1         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 71        | 72.45%  |
| 2     | 23        | 23.47%  |
| 3     | 3         | 3.06%   |
| 0     | 1         | 1.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 70        | 43.21%  |
| Realtek Semiconductor             | 58        | 35.8%   |
| Qualcomm Atheros                  | 8         | 4.94%   |
| Broadcom                          | 6         | 3.7%    |
| Ralink Technology                 | 4         | 2.47%   |
| Broadcom Limited                  | 4         | 2.47%   |
| Huawei Technologies               | 3         | 1.85%   |
| DisplayLink                       | 2         | 1.23%   |
| TP-Link                           | 1         | 0.62%   |
| Sierra Wireless                   | 1         | 0.62%   |
| MediaTek                          | 1         | 0.62%   |
| Ericsson Business Mobile Networks | 1         | 0.62%   |
| Dell                              | 1         | 0.62%   |
| D-Link                            | 1         | 0.62%   |
| ASIX Electronics                  | 1         | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 22.04%  |
| Intel Wi-Fi 6 AX200                                               | 22        | 11.83%  |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 4.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 9         | 4.84%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.15%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3         | 1.61%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.61%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.61%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.08%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.08%   |
| Intel Wireless 3165                                               | 2         | 1.08%   |
| Intel Wireless 3160                                               | 2         | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.08%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.08%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 2         | 1.08%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                  | 2         | 1.08%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 1.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.54%   |
| Sierra Wireless EM7455                                            | 1         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.54%   |
| Realtek 802.11ac NIC                                              | 1         | 0.54%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.54%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.54%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.54%   |
| Intel Wireless-AC 9260                                            | 1         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 64        | 68.82%  |
| Realtek Semiconductor | 8         | 8.6%    |
| Qualcomm Atheros      | 5         | 5.38%   |
| Broadcom              | 5         | 5.38%   |
| Ralink Technology     | 4         | 4.3%    |
| Broadcom Limited      | 3         | 3.23%   |
| TP-Link               | 1         | 1.08%   |
| Sierra Wireless       | 1         | 1.08%   |
| MediaTek              | 1         | 1.08%   |
| D-Link                | 1         | 1.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 22        | 23.66%  |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 9         | 9.68%   |
| Intel Wireless 8265 / 8275                                           | 5         | 5.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3         | 3.23%   |
| Intel Wi-Fi 6 AX201                                                  | 3         | 3.23%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 3.23%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 3.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 2.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 2.15%   |
| Intel Wireless 3165                                                  | 2         | 2.15%   |
| Intel Wireless 3160                                                  | 2         | 2.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 2         | 2.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 2.15%   |
| Intel 700 Series Chipset Family Wi-Fi                                | 2         | 2.15%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 2         | 2.15%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 1.08%   |
| Sierra Wireless EM7455                                               | 1         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 1.08%   |
| Realtek 802.11ac NIC                                                 | 1         | 1.08%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 1.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1         | 1.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 1         | 1.08%   |
| Intel Wireless-AC 9260                                               | 1         | 1.08%   |
| Intel Wireless 8260                                                  | 1         | 1.08%   |
| Intel Wireless 7260                                                  | 1         | 1.08%   |
| Intel Ultimate N WiFi Link 5300                                      | 1         | 1.08%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 1         | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 1.08%   |
| Intel CNVi: Wi-Fi                                                    | 1         | 1.08%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 1.08%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1         | 1.08%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1         | 1.08%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter           | 1         | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 56        | 65.12%  |
| Intel                 | 19        | 22.09%  |
| Broadcom              | 4         | 4.65%   |
| Qualcomm Atheros      | 3         | 3.49%   |
| DisplayLink           | 2         | 2.33%   |
| Broadcom Limited      | 1         | 1.16%   |
| ASIX Electronics      | 1         | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 46.59%  |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 10.23%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 4.55%   |
| Intel Ethernet Controller I225-V                                  | 3         | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 3.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.27%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.14%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.14%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.14%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.14%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.14%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.14%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.14%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.14%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.14%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.14%   |
| DisplayLink USB-C Triple-4K Dock                                  | 1         | 1.14%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.14%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                    | 1         | 1.14%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 89        | 50.57%  |
| Ethernet | 82        | 46.59%  |
| Modem    | 5         | 2.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 60.78%  |
| Ethernet | 40        | 39.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 64        | 65.31%  |
| 1     | 29        | 29.59%  |
| 3     | 4         | 4.08%   |
| 0     | 1         | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 52        | 53.06%  |
| Yes  | 46        | 46.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 72.29%  |
| Realtek Semiconductor           | 6         | 7.23%   |
| Apple                           | 4         | 4.82%   |
| Foxconn / Hon Hai               | 3         | 3.61%   |
| Cambridge Silicon Radio         | 3         | 3.61%   |
| Broadcom                        | 2         | 2.41%   |
| Qualcomm Atheros Communications | 1         | 1.2%    |
| IMC Networks                    | 1         | 1.2%    |
| Dell                            | 1         | 1.2%    |
| ASUSTek Computer                | 1         | 1.2%    |
| Unknown                         | 1         | 1.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 21        | 25.3%   |
| Intel Bluetooth wireless interface                  | 12        | 14.46%  |
| Intel AX201 Bluetooth                               | 12        | 14.46%  |
| Intel Bluetooth Device                              | 9         | 10.84%  |
| Realtek Bluetooth Radio                             | 3         | 3.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.61%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.41%   |
| Intel AX210 Bluetooth                               | 2         | 2.41%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.41%   |
| Apple Bluetooth Host Controller                     | 2         | 2.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.2%    |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.2%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.2%    |
| IMC Networks Bluetooth Radio                        | 1         | 1.2%    |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.2%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.2%    |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.2%    |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.2%    |
| Broadcom HP Portable SoftSailing                    | 1         | 1.2%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.2%    |
| ASUS ASUS USB-BT500                                 | 1         | 1.2%    |
| Unknown                                             | 1         | 1.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 70        | 51.47%  |
| Nvidia                                 | 31        | 22.79%  |
| AMD                                    | 26        | 19.12%  |
| Valve Software                         | 1         | 0.74%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.74%   |
| Razer USA                              | 1         | 0.74%   |
| Logitech                               | 1         | 0.74%   |
| Lenovo                                 | 1         | 0.74%   |
| Kingston Technology                    | 1         | 0.74%   |
| JMTek                                  | 1         | 0.74%   |
| GN Netcom                              | 1         | 0.74%   |
| Creative Technology                    | 1         | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 22        | 13.92%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 13        | 8.23%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 6.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 5.06%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 3.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 3.16%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 3.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.16%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 2.53%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 2.53%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.9%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.9%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.9%    |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.27%   |
| Nvidia Audio device                                                        | 2         | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.27%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.27%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.27%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 2         | 1.27%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 1         | 0.63%   |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 0.63%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver] | 1         | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.63%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.63%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1         | 0.63%   |
| Lenovo USB Headset                                                         | 1         | 0.63%   |
| Kingston Technology HyperX QuadCast S                                      | 1         | 0.63%   |
| JMTek USB Audio Device                                                     | 1         | 0.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.63%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 37.5%   |
| SK hynix            | 7         | 21.88%  |
| Micron Technology   | 5         | 15.63%  |
| Unknown             | 2         | 6.25%   |
| Unknown (ABCD)      | 1         | 3.13%   |
| Team                | 1         | 3.13%   |
| KLEVV               | 1         | 3.13%   |
| Elpida              | 1         | 3.13%   |
| Crucial             | 1         | 3.13%   |
| ASint Technology    | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 3         | 9.09%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s         | 2         | 6.06%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 6.06%   |
| Unknown                                                        | 2         | 6.06%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 1         | 3.03%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s          | 1         | 3.03%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 3.03%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 3.03%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 3.03%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s         | 1         | 3.03%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 3.03%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 3.03%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 3.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 3.03%   |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s            | 1         | 3.03%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 3.03%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s      | 1         | 3.03%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 3.03%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s       | 1         | 3.03%   |
| Micron RAM MT52L1G32D4PG-107 8GB Chip LPDDR3 1867MT/s          | 1         | 3.03%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s             | 1         | 3.03%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s            | 1         | 3.03%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s           | 1         | 3.03%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s         | 1         | 3.03%   |
| KLEVV RAM KD48GU880-32A160X 8GB DIMM DDR4 2666MT/s             | 1         | 3.03%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s          | 1         | 3.03%   |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s         | 1         | 3.03%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s             | 1         | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 16        | 57.14%  |
| DDR3   | 5         | 17.86%  |
| LPDDR5 | 3         | 10.71%  |
| DDR5   | 2         | 7.14%   |
| LPDDR4 | 1         | 3.57%   |
| LPDDR3 | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 21        | 75%     |
| Row Of Chips | 3         | 10.71%  |
| DIMM         | 3         | 10.71%  |
| Chip         | 1         | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 11        | 35.48%  |
| 16384 | 7         | 22.58%  |
| 32768 | 6         | 19.35%  |
| 2048  | 4         | 12.9%   |
| 4096  | 2         | 6.45%   |
| 3072  | 1         | 3.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 11        | 37.93%  |
| 1600  | 4         | 13.79%  |
| 6400  | 3         | 10.34%  |
| 8400  | 2         | 6.9%    |
| 2667  | 2         | 6.9%    |
| 2400  | 2         | 6.9%    |
| 5600  | 1         | 3.45%   |
| 4800  | 1         | 3.45%   |
| 2666  | 1         | 3.45%   |
| 1867  | 1         | 3.45%   |
| 1067  | 1         | 3.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 100%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 43.66%  |
| Bison Electronics                      | 7         | 9.86%   |
| Microdia                               | 5         | 7.04%   |
| Sunplus Innovation Technology          | 3         | 4.23%   |
| Lite-On Technology                     | 3         | 4.23%   |
| IMC Networks                           | 3         | 4.23%   |
| Apple                                  | 3         | 4.23%   |
| Acer                                   | 3         | 4.23%   |
| Suyin                                  | 2         | 2.82%   |
| Valve Software                         | 1         | 1.41%   |
| Unknown                                | 1         | 1.41%   |
| Sony Ericsson Mobile Communications AB | 1         | 1.41%   |
| Ricoh                                  | 1         | 1.41%   |
| Realtek Semiconductor                  | 1         | 1.41%   |
| Luxvisions Innotech Limited            | 1         | 1.41%   |
| Logitech                               | 1         | 1.41%   |
| Importek                               | 1         | 1.41%   |
| HYGD-220831-A                          | 1         | 1.41%   |
| Generalplus Technology                 | 1         | 1.41%   |
| Alpha Imaging Technology               | 1         | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony FHD Webcam                                   | 7         | 9.86%   |
| Chicony Integrated IR Camera                         | 6         | 8.45%   |
| Chicony USB2.0 Camera                                | 5         | 7.04%   |
| IMC Networks Integrated Camera                       | 3         | 4.23%   |
| Chicony HD Webcam                                    | 3         | 4.23%   |
| Bison HD Webcam                                      | 3         | 4.23%   |
| Apple FaceTime HD Camera                             | 3         | 4.23%   |
| Acer BisonCam,NB Pro                                 | 3         | 4.23%   |
| Microdia Integrated_Webcam_FHD                       | 2         | 2.82%   |
| Chicony Integrated Camera                            | 2         | 2.82%   |
| Bison Lenovo EasyCamera                              | 2         | 2.82%   |
| Valve Software 3D Camera                             | 1         | 1.41%   |
| Unknown HD camera                                    | 1         | 1.41%   |
| Suyin RGBIR Camera                                   | 1         | 1.41%   |
| Suyin HP TrueVision HD                               | 1         | 1.41%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.41%   |
| Sunplus HD720P Webcam                                | 1         | 1.41%   |
| Sunplus Asus Webcam                                  | 1         | 1.41%   |
| Sony Ericsson Mobile AB XQ-CC54                      | 1         | 1.41%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 1.41%   |
| Realtek Integrated Webcam                            | 1         | 1.41%   |
| Microdia Sonix USB 2.0 Camera                        | 1         | 1.41%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 1.41%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.41%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.41%   |
| Logitech Brio 500                                    | 1         | 1.41%   |
| Lite-On Integrated Camera                            | 1         | 1.41%   |
| Lite-On HP Wide Vision HD Camera                     | 1         | 1.41%   |
| Lite-On HP Webcam                                    | 1         | 1.41%   |
| Importek HP Webcam                                   | 1         | 1.41%   |
| HYGD-220831-A Hy-Usb2.0-1*MIC                        | 1         | 1.41%   |
| Generalplus WEB CAM                                  | 1         | 1.41%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 1.41%   |
| Chicony USB 2.0 Camera                               | 1         | 1.41%   |
| Chicony HP TrueVision HD Camera                      | 1         | 1.41%   |
| Chicony HP Truevision HD                             | 1         | 1.41%   |
| Chicony HP HD Camera                                 | 1         | 1.41%   |
| Chicony FJ Camera                                    | 1         | 1.41%   |
| Chicony ACER FHD User Facing                         | 1         | 1.41%   |
| Chicony 1.3M Webcam                                  | 1         | 1.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 9         | 56.25%  |
| Validity Sensors      | 6         | 37.5%   |
| LighTuning Technology | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics UWP WBDI                                                         | 2         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 12.5%   |
| Unknown                                                                    | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 6.25%   |
| Validity Sensors VFS491                                                    | 1         | 6.25%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 6.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.25%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 6.25%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 6.25%   |
| Synaptics WBDI                                                             | 1         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 6.25%   |
| LighTuning Fingerprint Reader                                              | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 66.67%  |
| Alcor Micro | 2         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 2         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 59        | 60.2%   |
| 1     | 37        | 37.76%  |
| 3     | 1         | 1.02%   |
| 2     | 1         | 1.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 16        | 37.21%  |
| Multimedia controller | 11        | 25.58%  |
| Chipcard              | 6         | 13.95%  |
| Graphics card         | 5         | 11.63%  |
| Net/wireless          | 3         | 6.98%   |
| Modem                 | 1         | 2.33%   |
| Camera                | 1         | 2.33%   |

