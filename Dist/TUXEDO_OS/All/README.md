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

Total: 141

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P50 20EQS42M00     | Notebook    | [f4761a87e1](https://linux-hardware.org/?probe=f4761a87e1) | Nov 06, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [4a5e89566c](https://linux-hardware.org/?probe=4a5e89566c) | Nov 05, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [0845a0ec43](https://linux-hardware.org/?probe=0845a0ec43) | Nov 03, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [ca743b4e40](https://linux-hardware.org/?probe=ca743b4e40) | Nov 01, 2023 |
| Dell          | Precision 5480              | Notebook    | [0d66f24fe1](https://linux-hardware.org/?probe=0d66f24fe1) | Oct 25, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | Notebook    | [017d43654d](https://linux-hardware.org/?probe=017d43654d) | Oct 22, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [78df342ad3](https://linux-hardware.org/?probe=78df342ad3) | Oct 21, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [af44d01ae9](https://linux-hardware.org/?probe=af44d01ae9) | Oct 19, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [5573fff3e6](https://linux-hardware.org/?probe=5573fff3e6) | Oct 17, 2023 |
| Dell          | Latitude E6540              | Notebook    | [78c4b71781](https://linux-hardware.org/?probe=78c4b71781) | Oct 04, 2023 |
| Dell          | Latitude E6540              | Notebook    | [290b4bd42e](https://linux-hardware.org/?probe=290b4bd42e) | Oct 03, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [886b5140ec](https://linux-hardware.org/?probe=886b5140ec) | Oct 03, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3Y60... | Notebook    | [294e5069a4](https://linux-hardware.org/?probe=294e5069a4) | Oct 01, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3Y60... | Notebook    | [9452219aa3](https://linux-hardware.org/?probe=9452219aa3) | Oct 01, 2023 |
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
| TUXEDO OS 22.04 | 109       | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 109       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 6.1.0-1009-tuxedo    | 17        | 14.66%  |
| 6.2.0-10018-tuxedo   | 14        | 12.07%  |
| 6.2.0-10022-tuxedo   | 13        | 11.21%  |
| 6.2.0-10007-tuxedo   | 11        | 9.48%   |
| 6.2.0-10005-tuxedo   | 11        | 9.48%   |
| 6.2.0-10011-tuxedo   | 9         | 7.76%   |
| 5.15.0-10058-tuxedo  | 7         | 6.03%   |
| 6.2.0-10010-tuxedo   | 6         | 5.17%   |
| 6.2.0-10027-tuxedo   | 5         | 4.31%   |
| 6.5.0-10006-tuxedo   | 4         | 3.45%   |
| 5.15.0-10048-tuxedo  | 4         | 3.45%   |
| 5.15.0-10053-tuxedo  | 3         | 2.59%   |
| 5.15.0-10052-tuxedo  | 3         | 2.59%   |
| 5.15.0-10057-tuxedo  | 2         | 1.72%   |
| 5.15.0-10056-tuxedo  | 2         | 1.72%   |
| 5.15.0-10050-tuxedo  | 2         | 1.72%   |
| 6.5.4-060504-generic | 1         | 0.86%   |
| 6.2.0-10014-tuxedo   | 1         | 0.86%   |
| 6.0.0-1010-oem       | 1         | 0.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 70        | 60.34%  |
| 5.15.0  | 23        | 19.83%  |
| 6.1.0   | 17        | 14.66%  |
| 6.5.0   | 4         | 3.45%   |
| 6.5.4   | 1         | 0.86%   |
| 6.0.0   | 1         | 0.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 70        | 60.34%  |
| 5.15    | 23        | 19.83%  |
| 6.1     | 17        | 14.66%  |
| 6.5     | 5         | 4.31%   |
| 6.0     | 1         | 0.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 109       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| KDE5 | 109       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 105       | 95.45%  |
| Wayland | 5         | 4.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 86        | 77.48%  |
| SDDM    | 25        | 22.52%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| de_DE | 49        | 44.95%  |
| en_US | 26        | 23.85%  |
| en_GB | 7         | 6.42%   |
| pl_PL | 3         | 2.75%   |
| en_ZA | 3         | 2.75%   |
| en_AU | 3         | 2.75%   |
| en_AG | 3         | 2.75%   |
| pt_PT | 2         | 1.83%   |
| nb_NO | 2         | 1.83%   |
| it_IT | 2         | 1.83%   |
| fr_FR | 2         | 1.83%   |
| pt_BR | 1         | 0.92%   |
| hu_HU | 1         | 0.92%   |
| es_ES | 1         | 0.92%   |
| en_DK | 1         | 0.92%   |
| en_CA | 1         | 0.92%   |
| de_CH | 1         | 0.92%   |
| de_AT | 1         | 0.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 88        | 80%     |
| EFI  | 22        | 20%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 92        | 83.64%  |
| Btrfs   | 9         | 8.18%   |
| Tmpfs   | 4         | 3.64%   |
| Overlay | 3         | 2.73%   |
| Xfs     | 2         | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 86        | 77.48%  |
| GPT     | 23        | 20.72%  |
| MBR     | 2         | 1.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 94.55%  |
| Yes       | 6         | 5.45%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 91.82%  |
| Yes       | 9         | 8.18%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| TUXEDO              | 32        | 29.36%  |
| Lenovo              | 16        | 14.68%  |
| Hewlett-Packard     | 12        | 11.01%  |
| Dell                | 12        | 11.01%  |
| ASUSTek Computer    | 11        | 10.09%  |
| MSI                 | 6         | 5.5%    |
| Apple               | 4         | 3.67%   |
| ASRock              | 3         | 2.75%   |
| Notebook            | 2         | 1.83%   |
| Gigabyte Technology | 2         | 1.83%   |
| Acer                | 2         | 1.83%   |
| Schenker            | 1         | 0.92%   |
| Metabox             | 1         | 0.92%   |
| Fujitsu             | 1         | 0.92%   |
| Fanless Mini PC     | 1         | 0.92%   |
| Chuwi               | 1         | 0.92%   |
| BESSTAR Tech        | 1         | 0.92%   |
| Unknown             | 1         | 0.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| TUXEDO InfinityBook S 15/17 Gen7    | 4         | 3.67%   |
| Unknown                             | 3         | 2.75%   |
| TUXEDO XMG FUSION 15 (XFU15L19)     | 2         | 1.83%   |
| TUXEDO Stellaris/Polaris AMD Gen4   | 2         | 1.83%   |
| TUXEDO Stellaris Intel Gen5         | 2         | 1.83%   |
| TUXEDO Pulse 15 Gen2                | 2         | 1.83%   |
| TUXEDO Pulse 15 Gen1                | 2         | 1.83%   |
| TUXEDO InfinityBook Pro Gen7 (MK2)  | 2         | 1.83%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 2         | 1.83%   |
| TUXEDO InfinityBook Pro 14 Gen6     | 2         | 1.83%   |
| TUXEDO Aura 15 Gen2                 | 2         | 1.83%   |
| MSI MS-7D17                         | 2         | 1.83%   |
| Dell Latitude E6540                 | 2         | 1.83%   |
| ASUS PRIME B450-PLUS                | 2         | 1.83%   |
| Apple MacBookPro8,1                 | 2         | 1.83%   |
| TUXEDO Stellaris AMD Gen3 (CZN)     | 1         | 0.92%   |
| TUXEDO Polaris AMD Gen3 (CZN)       | 1         | 0.92%   |
| TUXEDO Polaris 15 AMD Gen1          | 1         | 0.92%   |
| TUXEDO P64_HJ,HK1                   | 1         | 0.92%   |
| TUXEDO N7x0WU                       | 1         | 0.92%   |
| TUXEDO N13xWU                       | 1         | 0.92%   |
| TUXEDO InfinityBook S 15 Gen6       | 1         | 0.92%   |
| TUXEDO Book XUX7 Gen13              | 1         | 0.92%   |
| Schenker VISION 15 E23 (SVS15E23)   | 1         | 0.92%   |
| Notebook W65_W67RB                  | 1         | 0.92%   |
| Notebook NP5x_NP6x_NP7xHP           | 1         | 0.92%   |
| MSI Prestige 15 A10SC               | 1         | 0.92%   |
| MSI MS-7D25                         | 1         | 0.92%   |
| MSI MS-7C37                         | 1         | 0.92%   |
| MSI GE75 Raider 10SF                | 1         | 0.92%   |
| Metabox Prime-X X170KM              | 1         | 0.92%   |
| Lenovo Yoga S740-15IRH 81NX         | 1         | 0.92%   |
| Lenovo ThinkPad X200 Tablet 7450WN9 | 1         | 0.92%   |
| Lenovo ThinkPad T490s 20NYS3Y600    | 1         | 0.92%   |
| Lenovo ThinkPad T490 20N3SBU219     | 1         | 0.92%   |
| Lenovo ThinkPad P50 20EQS42M00      | 1         | 0.92%   |
| Lenovo ThinkPad P50 20EQS37F00      | 1         | 0.92%   |
| Lenovo ThinkPad P1 Gen 3 20TJS1W700 | 1         | 0.92%   |
| Lenovo ThinkPad E580 20KS003SUS     | 1         | 0.92%   |
| Lenovo ThinkPad 20JB002BUS          | 1         | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| TUXEDO InfinityBook | 11        | 10.09%  |
| Lenovo ThinkPad     | 8         | 7.34%   |
| TUXEDO Stellaris    | 5         | 4.59%   |
| TUXEDO Pulse        | 4         | 3.67%   |
| Dell Latitude       | 4         | 3.67%   |
| HP Pavilion         | 3         | 2.75%   |
| Dell Precision      | 3         | 2.75%   |
| ASUS ROG            | 3         | 2.75%   |
| ASUS PRIME          | 3         | 2.75%   |
| Unknown             | 3         | 2.75%   |
| TUXEDO XMG          | 2         | 1.83%   |
| TUXEDO Polaris      | 2         | 1.83%   |
| TUXEDO Aura         | 2         | 1.83%   |
| MSI MS-7D17         | 2         | 1.83%   |
| Lenovo IdeaPad      | 2         | 1.83%   |
| HP Laptop           | 2         | 1.83%   |
| HP EliteBook        | 2         | 1.83%   |
| Dell Inspiron       | 2         | 1.83%   |
| Apple MacBookPro8   | 2         | 1.83%   |
| TUXEDO P64          | 1         | 0.92%   |
| TUXEDO N7x0WU       | 1         | 0.92%   |
| TUXEDO N13xWU       | 1         | 0.92%   |
| TUXEDO Book         | 1         | 0.92%   |
| Schenker VISION     | 1         | 0.92%   |
| Notebook W65        | 1         | 0.92%   |
| Notebook NP5x       | 1         | 0.92%   |
| MSI Prestige        | 1         | 0.92%   |
| MSI MS-7D25         | 1         | 0.92%   |
| MSI MS-7C37         | 1         | 0.92%   |
| MSI GE75            | 1         | 0.92%   |
| Metabox Prime-X     | 1         | 0.92%   |
| Lenovo Yoga         | 1         | 0.92%   |
| Lenovo ThinkCentre  | 1         | 0.92%   |
| Lenovo ThinkBook    | 1         | 0.92%   |
| Lenovo Legion       | 1         | 0.92%   |
| Lenovo G580         | 1         | 0.92%   |
| Lenovo G50-80       | 1         | 0.92%   |
| HP ZBook            | 1         | 0.92%   |
| HP OMEN             | 1         | 0.92%   |
| HP Notebook         | 1         | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 23        | 21.1%   |
| 2020 | 16        | 14.68%  |
| 2021 | 13        | 11.93%  |
| 2019 | 10        | 9.17%   |
| 2015 | 9         | 8.26%   |
| 2023 | 7         | 6.42%   |
| 2012 | 6         | 5.5%    |
| 2018 | 4         | 3.67%   |
| 2017 | 4         | 3.67%   |
| 2013 | 4         | 3.67%   |
| 2011 | 4         | 3.67%   |
| 2014 | 3         | 2.75%   |
| 2016 | 2         | 1.83%   |
| 2008 | 2         | 1.83%   |
| 2010 | 1         | 0.92%   |
| 2009 | 1         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 86        | 78.9%   |
| Desktop     | 20        | 18.35%  |
| Tablet      | 1         | 0.92%   |
| Convertible | 1         | 0.92%   |
| Mini pc     | 1         | 0.92%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 109       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 109       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 25        | 22.94%  |
| 16.01-24.0  | 24        | 22.02%  |
| 8.01-16.0   | 19        | 17.43%  |
| 4.01-8.0    | 18        | 16.51%  |
| 64.01-256.0 | 13        | 11.93%  |
| 3.01-4.0    | 7         | 6.42%   |
| 24.01-32.0  | 3         | 2.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 40        | 34.48%  |
| 2.01-3.0   | 26        | 22.41%  |
| 1.01-2.0   | 23        | 19.83%  |
| 3.01-4.0   | 16        | 13.79%  |
| 8.01-16.0  | 8         | 6.9%    |
| 16.01-24.0 | 3         | 2.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 56        | 50.91%  |
| 2      | 38        | 34.55%  |
| 3      | 6         | 5.45%   |
| 4      | 5         | 4.55%   |
| 5      | 3         | 2.73%   |
| 6      | 1         | 0.91%   |
| 0      | 1         | 0.91%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 81.65%  |
| Yes       | 20        | 18.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 84.4%   |
| No        | 17        | 15.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 90.83%  |
| No        | 10        | 9.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 82.73%  |
| No        | 19        | 17.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 54        | 49.54%  |
| USA          | 13        | 11.93%  |
| UK           | 5         | 4.59%   |
| Switzerland  | 4         | 3.67%   |
| South Africa | 3         | 2.75%   |
| Portugal     | 3         | 2.75%   |
| Poland       | 3         | 2.75%   |
| Austria      | 3         | 2.75%   |
| Australia    | 3         | 2.75%   |
| Spain        | 2         | 1.83%   |
| Norway       | 2         | 1.83%   |
| Netherlands  | 2         | 1.83%   |
| France       | 2         | 1.83%   |
| Turkey       | 1         | 0.92%   |
| Romania      | 1         | 0.92%   |
| Italy        | 1         | 0.92%   |
| Egypt        | 1         | 0.92%   |
| Denmark      | 1         | 0.92%   |
| Czechia      | 1         | 0.92%   |
| Canada       | 1         | 0.92%   |
| Bulgaria     | 1         | 0.92%   |
| Brazil       | 1         | 0.92%   |
| Aruba        | 1         | 0.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Munich                 | 6         | 5.45%   |
| Vienna                 | 3         | 2.73%   |
| Zurich                 | 2         | 1.82%   |
| Schweinfurt            | 2         | 1.82%   |
| Nuremberg              | 2         | 1.82%   |
| Lucerne                | 2         | 1.82%   |
| Leipzig                | 2         | 1.82%   |
| Langevag               | 2         | 1.82%   |
| Johannesburg           | 2         | 1.82%   |
| Hürth                 | 2         | 1.82%   |
| Hamburg                | 2         | 1.82%   |
| Brisbane               | 2         | 1.82%   |
| Berlin                 | 2         | 1.82%   |
| Zalău                 | 1         | 0.91%   |
| Zabrze                 | 1         | 0.91%   |
| Wembley                | 1         | 0.91%   |
| Watertown              | 1         | 0.91%   |
| Warsaw                 | 1         | 0.91%   |
| Walsall                | 1         | 0.91%   |
| Venlo                  | 1         | 0.91%   |
| Vallejo                | 1         | 0.91%   |
| Ulm                    | 1         | 0.91%   |
| Stuttgart              | 1         | 0.91%   |
| Stockstadt am Main     | 1         | 0.91%   |
| Solingen               | 1         | 0.91%   |
| Sistov                 | 1         | 0.91%   |
| Seattle                | 1         | 0.91%   |
| Schwarzenberg          | 1         | 0.91%   |
| Santa Cruz de Tenerife | 1         | 0.91%   |
| San Diego              | 1         | 0.91%   |
| Rio Maior              | 1         | 0.91%   |
| Reno                   | 1         | 0.91%   |
| Rennes                 | 1         | 0.91%   |
| Redcar                 | 1         | 0.91%   |
| Quarteira              | 1         | 0.91%   |
| Pruem                  | 1         | 0.91%   |
| Prague                 | 1         | 0.91%   |
| Perth                  | 1         | 0.91%   |
| Perrysburg             | 1         | 0.91%   |
| Peitz                  | 1         | 0.91%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 57        | 79     | 35.19%  |
| SanDisk                     | 17        | 21     | 10.49%  |
| Seagate                     | 16        | 21     | 9.88%   |
| Kingston                    | 8         | 8      | 4.94%   |
| WDC                         | 6         | 7      | 3.7%    |
| Hitachi                     | 6         | 9      | 3.7%    |
| SK hynix                    | 4         | 5      | 2.47%   |
| Toshiba                     | 3         | 4      | 1.85%   |
| Micron/Crucial Technology   | 3         | 5      | 1.85%   |
| Unknown                     | 2         | 2      | 1.23%   |
| SPCC                        | 2         | 2      | 1.23%   |
| Phison Electronics          | 2         | 2      | 1.23%   |
| Phison                      | 2         | 4      | 1.23%   |
| Micron Technology           | 2         | 2      | 1.23%   |
| Kingston Technology Company | 2         | 2      | 1.23%   |
| Intel                       | 2         | 2      | 1.23%   |
| GOODRAM                     | 2         | 2      | 1.23%   |
| USB3.0                      | 1         | 1      | 0.62%   |
| Transcend                   | 1         | 1      | 0.62%   |
| Silicon Motion              | 1         | 2      | 0.62%   |
| OWC                         | 1         | 1      | 0.62%   |
| Netac                       | 1         | 1      | 0.62%   |
| LITEONIT                    | 1         | 1      | 0.62%   |
| Lite-On Technology          | 1         | 1      | 0.62%   |
| Lenovo                      | 1         | 1      | 0.62%   |
| KIOXIA                      | 1         | 1      | 0.62%   |
| KingFast                    | 1         | 1      | 0.62%   |
| Kingchuxing                 | 1         | 1      | 0.62%   |
| Intenso                     | 1         | 1      | 0.62%   |
| HS-SSD-E100                 | 1         | 1      | 0.62%   |
| Hikvision                   | 1         | 2      | 0.62%   |
| HGST HTS                    | 1         | 1      | 0.62%   |
| HGST                        | 1         | 1      | 0.62%   |
| CT1000BX                    | 1         | 1      | 0.62%   |
| Crucial                     | 1         | 1      | 0.62%   |
| China                       | 1         | 1      | 0.62%   |
| ASMT                        | 1         | 1      | 0.62%   |
| ASMedia                     | 1         | 2      | 0.62%   |
| Apple                       | 1         | 1      | 0.62%   |
| Apacer                      | 1         | 1      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 11        | 6.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 10        | 5.65%   |
| Samsung SSD 980 500GB                              | 8         | 4.52%   |
| Samsung SSD 980 1TB                                | 7         | 3.95%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB  | 5         | 2.82%   |
| Samsung SSD 970 EVO Plus 1TB                       | 3         | 1.69%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB              | 3         | 1.69%   |
| Kingston SA400S37240G 240GB SSD                    | 3         | 1.69%   |
| Seagate ST3500418AS 500GB                          | 2         | 1.13%   |
| Seagate ST1000VT001-1RE172 1TB                     | 2         | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB                     | 2         | 1.13%   |
| Sandisk WD Blue SN570 1TB                          | 2         | 1.13%   |
| Sandisk WD Black SN850 1TB                         | 2         | 1.13%   |
| SanDisk SSD PLUS 120GB                             | 2         | 1.13%   |
| SanDisk SDSSDA240G 240GB                           | 2         | 1.13%   |
| Samsung SSD 980 PRO 500GB                          | 2         | 1.13%   |
| Samsung SSD 980 PRO 1TB                            | 2         | 1.13%   |
| Samsung SSD 850 EVO 500GB                          | 2         | 1.13%   |
| Samsung SSD 850 EVO 1TB                            | 2         | 1.13%   |
| Hitachi HTS727550A9E364 500GB                      | 2         | 1.13%   |
| Hitachi HCS545050GLA380 500GB                      | 2         | 1.13%   |
| WDC WD80EAZZ-00BKLB0 8TB                           | 1         | 0.56%   |
| WDC WD3200BPVT-24JJ5T0 320GB                       | 1         | 0.56%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 1         | 0.56%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 0.56%   |
| WDC WD10JPVX-11JC3T0 1TB                           | 1         | 0.56%   |
| WDC WD10EZEX-00BN5A0 1TB                           | 1         | 0.56%   |
| WDC WD Elements SE SSD 1TB                         | 1         | 0.56%   |
| USB3.0 Super Speed 2TB                             | 1         | 0.56%   |
| Unknown MMC Card  64GB                             | 1         | 0.56%   |
| Unknown MMC Card  2GB                              | 1         | 0.56%   |
| Transcend TS512GSSD230S 512GB                      | 1         | 0.56%   |
| Toshiba XG4 NVMe SSD Controller 256GB              | 1         | 0.56%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 0.56%   |
| Toshiba BG3 NVMe SSD Controller 128GB              | 1         | 0.56%   |
| SPCC M.2 SSD 256GB                                 | 1         | 0.56%   |
| SPCC M.2 PCIe SSD 1TB                              | 1         | 0.56%   |
| SK hynix SKHynix_HFS512GEJ4X112N 512GB             | 1         | 0.56%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB               | 1         | 0.56%   |
| SK hynix SHGP31-1000GM 1TB                         | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 20     | 48.39%  |
| Hitachi             | 6         | 9      | 19.35%  |
| WDC                 | 5         | 6      | 16.13%  |
| USB3.0              | 1         | 1      | 3.23%   |
| Toshiba             | 1         | 1      | 3.23%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| HGST HTS            | 1         | 1      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 14     | 30%     |
| Kingston            | 6         | 6      | 15%     |
| SanDisk             | 5         | 6      | 12.5%   |
| GOODRAM             | 2         | 2      | 5%      |
| WDC                 | 1         | 1      | 2.5%    |
| Transcend           | 1         | 1      | 2.5%    |
| SPCC                | 1         | 1      | 2.5%    |
| SK hynix            | 1         | 2      | 2.5%    |
| OWC                 | 1         | 1      | 2.5%    |
| Netac               | 1         | 1      | 2.5%    |
| Micron Technology   | 1         | 1      | 2.5%    |
| LITEONIT            | 1         | 1      | 2.5%    |
| Intenso             | 1         | 1      | 2.5%    |
| CT1000BX            | 1         | 1      | 2.5%    |
| Crucial             | 1         | 1      | 2.5%    |
| China               | 1         | 1      | 2.5%    |
| ASMT                | 1         | 1      | 2.5%    |
| Apple               | 1         | 1      | 2.5%    |
| Apacer              | 1         | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 76        | 115    | 52.05%  |
| SSD     | 35        | 44     | 23.97%  |
| HDD     | 28        | 40     | 19.18%  |
| Unknown | 4         | 5      | 2.74%   |
| MMC     | 3         | 3      | 2.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 76        | 115    | 55.88%  |
| SATA | 51        | 81     | 37.5%   |
| SAS  | 6         | 8      | 4.41%   |
| MMC  | 3         | 3      | 2.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 48     | 52.31%  |
| 0.51-1.0   | 25        | 30     | 38.46%  |
| 1.01-2.0   | 4         | 4      | 6.15%   |
| 4.01-10.0  | 2         | 2      | 3.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 31        | 27.93%  |
| 251-500        | 21        | 18.92%  |
| 101-250        | 21        | 18.92%  |
| 1001-2000      | 15        | 13.51%  |
| 1-20           | 7         | 6.31%   |
| 2001-3000      | 6         | 5.41%   |
| More than 3000 | 4         | 3.6%    |
| 21-50          | 2         | 1.8%    |
| 51-100         | 2         | 1.8%    |
| Unknown        | 2         | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 37        | 32.46%  |
| 21-50          | 31        | 27.19%  |
| 101-250        | 15        | 13.16%  |
| 51-100         | 9         | 7.89%   |
| 251-500        | 8         | 7.02%   |
| 501-1000       | 7         | 6.14%   |
| 1001-2000      | 4         | 3.51%   |
| Unknown        | 2         | 1.75%   |
| More than 3000 | 1         | 0.88%   |

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
| Detected | 86        | 167    | 76.79%  |
| Works    | 26        | 40     | 23.21%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 55        | 35.03%  |
| Samsung Electronics          | 48        | 30.57%  |
| AMD                          | 17        | 10.83%  |
| SanDisk                      | 12        | 7.64%   |
| Phison Electronics           | 4         | 2.55%   |
| Kingston Technology Company  | 4         | 2.55%   |
| SK hynix                     | 3         | 1.91%   |
| Micron/Crucial Technology    | 3         | 1.91%   |
| Toshiba America Info Systems | 2         | 1.27%   |
| Silicon Motion               | 2         | 1.27%   |
| Seagate Technology           | 1         | 0.64%   |
| Micron Technology            | 1         | 0.64%   |
| Lite-On Technology           | 1         | 0.64%   |
| Lenovo                       | 1         | 0.64%   |
| KIOXIA                       | 1         | 0.64%   |
| ASMedia Technology           | 1         | 0.64%   |
| ADATA Technology             | 1         | 0.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 8.82%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 15        | 8.82%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 8.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 13        | 7.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.12%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 3.53%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 2.94%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 4         | 2.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 2.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 2.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.76%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 1.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.76%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 1.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 1.18%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 1.18%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.18%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2         | 1.18%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.18%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.18%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.18%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.59%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 1         | 0.59%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 1         | 0.59%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                      | 1         | 0.59%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 0.59%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 0.59%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.59%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.59%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.59%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.59%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 0.59%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 76        | 50.33%  |
| SATA | 63        | 41.72%  |
| RAID | 10        | 6.62%   |
| IDE  | 2         | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 81        | 74.31%  |
| AMD    | 28        | 25.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H                 | 4         | 3.67%   |
| Intel 12th Gen Core i7-1260P                  | 4         | 3.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.75%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 3         | 2.75%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 1.83%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 1.83%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.83%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.83%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.83%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 1.83%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.83%   |
| Intel 13th Gen Core i9-13900HX                | 2         | 1.83%   |
| Intel 12th Gen Core i7-1255U                  | 2         | 1.83%   |
| Intel 12th Gen Core i5-1240P                  | 2         | 1.83%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 2         | 1.83%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.83%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.83%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 1.83%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.83%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.92%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.92%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 1         | 0.92%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.92%   |
| Intel N100                                    | 1         | 0.92%   |
| Intel Core i9-10900KF CPU @ 3.70GHz           | 1         | 0.92%   |
| Intel Core i7-7Y75 CPU @ 1.30GHz              | 1         | 0.92%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.92%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.92%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.92%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.92%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 0.92%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 0.92%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.92%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 0.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.92%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Other            | 28        | 25.69%  |
| Intel Core i7    | 25        | 22.94%  |
| Intel Core i5    | 18        | 16.51%  |
| AMD Ryzen 7      | 12        | 11.01%  |
| AMD Ryzen 5      | 9         | 8.26%   |
| Intel Xeon       | 2         | 1.83%   |
| Intel Pentium    | 2         | 1.83%   |
| Intel Core i3    | 2         | 1.83%   |
| Intel Celeron    | 2         | 1.83%   |
| AMD Ryzen 9      | 2         | 1.83%   |
| AMD Ryzen 3      | 2         | 1.83%   |
| Intel Core i9    | 1         | 0.92%   |
| Intel Core 2 Duo | 1         | 0.92%   |
| AMD Turion II    | 1         | 0.92%   |
| AMD Ryzen 5 PRO  | 1         | 0.92%   |
| AMD A8           | 1         | 0.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 35        | 32.11%  |
| 6      | 21        | 19.27%  |
| 2      | 19        | 17.43%  |
| 8      | 16        | 14.68%  |
| 12     | 7         | 6.42%   |
| 14     | 5         | 4.59%   |
| 10     | 3         | 2.75%   |
| 24     | 2         | 1.83%   |
| 16     | 1         | 0.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 109       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 96        | 88.07%  |
| 1      | 13        | 11.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 109       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 97        | 87.39%  |
| 0x906a4    | 2         | 1.8%    |
| 0xa0653    | 1         | 0.9%    |
| 0x906ea    | 1         | 0.9%    |
| 0x906e9    | 1         | 0.9%    |
| 0x906a3    | 1         | 0.9%    |
| 0x806c1    | 1         | 0.9%    |
| 0x306d4    | 1         | 0.9%    |
| 0x0a704101 | 1         | 0.9%    |
| 0x0a50000d | 1         | 0.9%    |
| 0x0a50000c | 1         | 0.9%    |
| 0x08701030 | 1         | 0.9%    |
| 0x08608103 | 1         | 0.9%    |
| 0x010000c8 | 1         | 0.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 24        | 22.02%  |
| KabyLake         | 15        | 13.76%  |
| Zen 2            | 9         | 8.26%   |
| IvyBridge        | 9         | 8.26%   |
| CometLake        | 8         | 7.34%   |
| Alderlake Hybrid | 7         | 6.42%   |
| Zen 3            | 6         | 5.5%    |
| Haswell          | 6         | 5.5%    |
| Skylake          | 5         | 4.59%   |
| TigerLake        | 4         | 3.67%   |
| SandyBridge      | 4         | 3.67%   |
| Zen+             | 3         | 2.75%   |
| Broadwell        | 3         | 2.75%   |
| Westmere         | 1         | 0.92%   |
| Puma             | 1         | 0.92%   |
| Penryn           | 1         | 0.92%   |
| K10              | 1         | 0.92%   |
| Gracemont        | 1         | 0.92%   |
| Goldmont plus    | 1         | 0.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 73        | 50%     |
| Nvidia | 43        | 29.45%  |
| AMD    | 30        | 20.55%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 10        | 6.85%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 4.79%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 6         | 4.11%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 5         | 3.42%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 5         | 3.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 5         | 3.42%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 3.42%   |
| Intel UHD Graphics 620                                                      | 4         | 2.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 2.74%   |
| Intel HD Graphics 530                                                       | 4         | 2.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 2.74%   |
| AMD Lucienne                                                                | 4         | 2.74%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                    | 3         | 2.05%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                               | 3         | 2.05%   |
| Intel HD Graphics 630                                                       | 3         | 2.05%   |
| AMD Rembrandt [Radeon 680M]                                                 | 3         | 2.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 2.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.37%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.37%   |
| Nvidia GF108M [GeForce GT 635M]                                             | 2         | 1.37%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                             | 2         | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 1.37%   |
| Intel Raptor Lake-S UHD Graphics                                            | 2         | 1.37%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 2         | 1.37%   |
| Intel HD Graphics 5500                                                      | 2         | 1.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.37%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 2         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.37%   |
| AMD Mars XTX [Radeon HD 8790M]                                              | 2         | 1.37%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 0.68%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1         | 0.68%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 0.68%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.68%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                            | 1         | 0.68%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 40%     |
| Intel + Nvidia | 22        | 20%     |
| 1 x AMD        | 17        | 15.45%  |
| 1 x Nvidia     | 13        | 11.82%  |
| AMD + Nvidia   | 8         | 7.27%   |
| Intel + AMD    | 6         | 5.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 71        | 65.14%  |
| Proprietary | 37        | 33.94%  |
| Unknown     | 1         | 0.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 66.36%  |
| 5.01-6.0   | 12        | 10.91%  |
| 7.01-8.0   | 9         | 8.18%   |
| 3.01-4.0   | 7         | 6.36%   |
| 1.01-2.0   | 5         | 4.55%   |
| 8.01-16.0  | 2         | 1.82%   |
| 0.01-0.5   | 2         | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 31        | 23.85%  |
| Samsung Electronics | 16        | 12.31%  |
| AU Optronics        | 16        | 12.31%  |
| LG Display          | 8         | 6.15%   |
| Chimei Innolux      | 8         | 6.15%   |
| Acer                | 8         | 6.15%   |
| Dell                | 5         | 3.85%   |
| CSO                 | 5         | 3.85%   |
| Goldstar            | 4         | 3.08%   |
| Apple               | 4         | 3.08%   |
| BenQ                | 3         | 2.31%   |
| AOC                 | 3         | 2.31%   |
| Sharp               | 2         | 1.54%   |
| Lenovo              | 2         | 1.54%   |
| Iiyama              | 2         | 1.54%   |
| Hewlett-Packard     | 2         | 1.54%   |
| Yamaha              | 1         | 0.77%   |
| ViewSonic           | 1         | 0.77%   |
| Sony                | 1         | 0.77%   |
| SGT                 | 1         | 0.77%   |
| RTK                 | 1         | 0.77%   |
| Philips             | 1         | 0.77%   |
| PANDA               | 1         | 0.77%   |
| InfoVision          | 1         | 0.77%   |
| Fujitsu Siemens     | 1         | 0.77%   |
| Eizo                | 1         | 0.77%   |
| ASUSTek Computer    | 1         | 0.77%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 5         | 3.62%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 4         | 2.9%    |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 4         | 2.9%    |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 3         | 2.17%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                     | 2         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch        | 2         | 1.45%   |
| BOE LCD Monitor BOE0AF0 2560x1600 344x215mm 16.0-inch                   | 2         | 1.45%   |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch                   | 2         | 1.45%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                   | 2         | 1.45%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                   | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 1.45%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                  | 2         | 1.45%   |
| Acer EK240Y ACR0758 1920x1080 520x320mm 24.0-inch                       | 2         | 1.45%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.72%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1         | 0.72%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                           | 1         | 0.72%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.72%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                 | 1         | 0.72%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 0.72%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM0486 1920x1080                        | 1         | 0.72%   |
| Samsung Electronics SMB1930HD SAM0708 1360x768 410x230mm 18.5-inch      | 1         | 0.72%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch       | 1         | 0.72%   |
| Samsung Electronics S27C36x SAM7315 1920x1080 598x336mm 27.0-inch       | 1         | 0.72%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 530x300mm 24.0-inch       | 1         | 0.72%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC424D 2160x1440 254x169mm 12.0-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch    | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch   | 1         | 0.72%   |
| Samsung Electronics LC27T55 SAM701E 1920x1080 610x350mm 27.7-inch       | 1         | 0.72%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch       | 1         | 0.72%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 0.72%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch       | 1         | 0.72%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 59        | 48.36%  |
| 1366x768 (WXGA)    | 12        | 9.84%   |
| 2560x1440 (QHD)    | 11        | 9.02%   |
| 3840x2160 (4K)     | 8         | 6.56%   |
| 2880x1800          | 5         | 4.1%    |
| 2560x1600          | 4         | 3.28%   |
| 1920x1200 (WUXGA)  | 4         | 3.28%   |
| 1280x800 (WXGA)    | 4         | 3.28%   |
| 1600x900 (HD+)     | 2         | 1.64%   |
| 1280x1024 (SXGA)   | 2         | 1.64%   |
| 3840x1080          | 1         | 0.82%   |
| 3440x1440          | 1         | 0.82%   |
| 3200x1800 (QHD+)   | 1         | 0.82%   |
| 2560x1080          | 1         | 0.82%   |
| 2240x1400          | 1         | 0.82%   |
| 2160x1440          | 1         | 0.82%   |
| 1920x540           | 1         | 0.82%   |
| 1680x1050 (WSXGA+) | 1         | 0.82%   |
| 1440x900 (WXGA+)   | 1         | 0.82%   |
| 1360x768           | 1         | 0.82%   |
| Unknown            | 1         | 0.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 43        | 32.09%  |
| 27      | 11        | 8.21%   |
| 14      | 11        | 8.21%   |
| 24      | 10        | 7.46%   |
| 17      | 10        | 7.46%   |
| 13      | 10        | 7.46%   |
| 16      | 6         | 4.48%   |
| 12      | 5         | 3.73%   |
| 21      | 4         | 2.99%   |
| 31      | 3         | 2.24%   |
| 23      | 3         | 2.24%   |
| Unknown | 3         | 2.24%   |
| 40      | 2         | 1.49%   |
| 22      | 2         | 1.49%   |
| 20      | 2         | 1.49%   |
| 18      | 2         | 1.49%   |
| 84      | 1         | 0.75%   |
| 60      | 1         | 0.75%   |
| 46      | 1         | 0.75%   |
| 43      | 1         | 0.75%   |
| 34      | 1         | 0.75%   |
| 33      | 1         | 0.75%   |
| 19      | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 62        | 48.06%  |
| 501-600     | 20        | 15.5%   |
| 201-300     | 12        | 9.3%    |
| 351-400     | 11        | 8.53%   |
| 401-500     | 10        | 7.75%   |
| 801-900     | 3         | 2.33%   |
| 601-700     | 3         | 2.33%   |
| Unknown     | 3         | 2.33%   |
| 1001-1500   | 2         | 1.55%   |
| 701-800     | 1         | 0.78%   |
| 1501-2000   | 1         | 0.78%   |
| 901-1000    | 1         | 0.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 87        | 75%     |
| 16/10   | 21        | 18.1%   |
| 5/4     | 2         | 1.72%   |
| 3/2     | 2         | 1.72%   |
| 21/9    | 2         | 1.72%   |
| 32/9    | 1         | 0.86%   |
| Unknown | 1         | 0.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 43        | 32.09%  |
| 81-90          | 19        | 14.18%  |
| 301-350        | 11        | 8.21%   |
| 201-250        | 11        | 8.21%   |
| 121-130        | 9         | 6.72%   |
| 151-200        | 6         | 4.48%   |
| 111-120        | 6         | 4.48%   |
| 61-70          | 5         | 3.73%   |
| 351-500        | 5         | 3.73%   |
| 251-300        | 5         | 3.73%   |
| 501-1000       | 4         | 2.99%   |
| 141-150        | 3         | 2.24%   |
| Unknown        | 3         | 2.24%   |
| More than 1000 | 2         | 1.49%   |
| 71-80          | 2         | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 46        | 35.94%  |
| 51-100        | 27        | 21.09%  |
| 101-120       | 25        | 19.53%  |
| 161-240       | 16        | 12.5%   |
| More than 240 | 9         | 7.03%   |
| Unknown       | 3         | 2.34%   |
| 1-50          | 2         | 1.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 78        | 71.56%  |
| 2     | 25        | 22.94%  |
| 3     | 5         | 4.59%   |
| 0     | 1         | 0.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 79        | 44.38%  |
| Realtek Semiconductor             | 63        | 35.39%  |
| Qualcomm Atheros                  | 8         | 4.49%   |
| Broadcom                          | 6         | 3.37%   |
| Ralink Technology                 | 4         | 2.25%   |
| Huawei Technologies               | 4         | 2.25%   |
| Broadcom Limited                  | 4         | 2.25%   |
| MediaTek                          | 2         | 1.12%   |
| DisplayLink                       | 2         | 1.12%   |
| TP-Link                           | 1         | 0.56%   |
| Sierra Wireless                   | 1         | 0.56%   |
| Ericsson Business Mobile Networks | 1         | 0.56%   |
| Dell                              | 1         | 0.56%   |
| D-Link                            | 1         | 0.56%   |
| ASIX Electronics                  | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 21.74%  |
| Intel Wi-Fi 6 AX200                                               | 26        | 12.56%  |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 4.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 9         | 4.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.42%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.42%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3         | 1.45%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.45%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                  | 3         | 1.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.45%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.97%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.97%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.97%   |
| Intel Wireless 8260                                               | 2         | 0.97%   |
| Intel Wireless 3165                                               | 2         | 0.97%   |
| Intel Wireless 3160                                               | 2         | 0.97%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.97%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 2         | 0.97%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.97%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.97%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.97%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.97%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 2         | 0.97%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 0.97%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.48%   |
| Sierra Wireless EM7455                                            | 1         | 0.48%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.48%   |
| Realtek 802.11ac NIC                                              | 1         | 0.48%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 70.87%  |
| Realtek Semiconductor | 8         | 7.77%   |
| Qualcomm Atheros      | 5         | 4.85%   |
| Broadcom              | 5         | 4.85%   |
| Ralink Technology     | 4         | 3.88%   |
| Broadcom Limited      | 3         | 2.91%   |
| MediaTek              | 2         | 1.94%   |
| TP-Link               | 1         | 0.97%   |
| Sierra Wireless       | 1         | 0.97%   |
| D-Link                | 1         | 0.97%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 26        | 25.24%  |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 9         | 8.74%   |
| Intel Wireless 8265 / 8275                                           | 5         | 4.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3         | 2.91%   |
| Intel Wi-Fi 6 AX201                                                  | 3         | 2.91%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 2.91%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 2.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.94%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2         | 1.94%   |
| Intel Wireless 8260                                                  | 2         | 1.94%   |
| Intel Wireless 3165                                                  | 2         | 1.94%   |
| Intel Wireless 3160                                                  | 2         | 1.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 2         | 1.94%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 2         | 1.94%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 1.94%   |
| Intel 700 Series Chipset Family Wi-Fi                                | 2         | 1.94%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 2         | 1.94%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.97%   |
| Sierra Wireless EM7455                                               | 1         | 0.97%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.97%   |
| Realtek 802.11ac NIC                                                 | 1         | 0.97%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 0.97%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1         | 0.97%   |
| Intel Wireless-AC 9260                                               | 1         | 0.97%   |
| Intel Wireless 7260                                                  | 1         | 0.97%   |
| Intel Ultimate N WiFi Link 5300                                      | 1         | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 0.97%   |
| Intel CNVi: Wi-Fi                                                    | 1         | 0.97%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 0.97%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 0.97%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1         | 0.97%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 61        | 63.54%  |
| Intel                 | 24        | 25%     |
| Broadcom              | 4         | 4.17%   |
| Qualcomm Atheros      | 3         | 3.13%   |
| DisplayLink           | 2         | 2.08%   |
| Broadcom Limited      | 1         | 1.04%   |
| ASIX Electronics      | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 45.92%  |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 9.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 5.1%    |
| Intel Ethernet Controller I225-V                                  | 4         | 4.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.06%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 3.06%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.04%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.04%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.02%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.02%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.02%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.02%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.02%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.02%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.02%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.02%   |
| DisplayLink USB-C Dual-4K Dock                                    | 1         | 1.02%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.02%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                    | 1         | 1.02%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 1.02%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 99        | 50.25%  |
| Ethernet | 92        | 46.7%   |
| Modem    | 6         | 3.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 71        | 62.28%  |
| Ethernet | 43        | 37.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 72        | 66.06%  |
| 1     | 32        | 29.36%  |
| 3     | 4         | 3.67%   |
| 0     | 1         | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 53.21%  |
| Yes  | 51        | 46.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 68        | 73.91%  |
| Realtek Semiconductor           | 6         | 6.52%   |
| Foxconn / Hon Hai               | 4         | 4.35%   |
| Apple                           | 4         | 4.35%   |
| Cambridge Silicon Radio         | 3         | 3.26%   |
| Broadcom                        | 2         | 2.17%   |
| Qualcomm Atheros Communications | 1         | 1.09%   |
| IMC Networks                    | 1         | 1.09%   |
| Dell                            | 1         | 1.09%   |
| ASUSTek Computer                | 1         | 1.09%   |
| Unknown                         | 1         | 1.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 25        | 27.17%  |
| Intel Bluetooth wireless interface                  | 12        | 13.04%  |
| Intel AX201 Bluetooth                               | 12        | 13.04%  |
| Intel Bluetooth Device                              | 11        | 11.96%  |
| Realtek Bluetooth Radio                             | 3         | 3.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 3.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.26%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.17%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.17%   |
| Intel AX210 Bluetooth                               | 2         | 2.17%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 2.17%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.17%   |
| Apple Bluetooth Host Controller                     | 2         | 2.17%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.09%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.09%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.09%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.09%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.09%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.09%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.09%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.09%   |
| ASUS ASUS USB-BT500                                 | 1         | 1.09%   |
| Unknown                                             | 1         | 1.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 78        | 50.98%  |
| Nvidia                                 | 36        | 23.53%  |
| AMD                                    | 28        | 18.3%   |
| Razer USA                              | 2         | 1.31%   |
| Valve Software                         | 1         | 0.65%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.65%   |
| Logitech                               | 1         | 0.65%   |
| Lenovo                                 | 1         | 0.65%   |
| Kingston Technology                    | 1         | 0.65%   |
| JMTek                                  | 1         | 0.65%   |
| GN Netcom                              | 1         | 0.65%   |
| Creative Technology                    | 1         | 0.65%   |
| Creative Labs                          | 1         | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 24        | 13.41%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 13        | 7.26%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 6.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 4.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 3.91%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 3.35%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 2.79%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 2.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.79%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 2.23%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 2.23%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.68%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.68%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.12%   |
| Nvidia Audio device                                                        | 2         | 1.12%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2         | 1.12%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.12%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.12%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.12%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 2         | 1.12%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 1         | 0.56%   |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 0.56%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver] | 1         | 0.56%   |
| Razer USA Razer Seiren Mini                                                | 1         | 0.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.56%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.56%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 35.14%  |
| SK hynix            | 8         | 21.62%  |
| Micron Technology   | 6         | 16.22%  |
| Unknown             | 3         | 8.11%   |
| Unknown (ABCD)      | 1         | 2.7%    |
| Team                | 1         | 2.7%    |
| KLEVV               | 1         | 2.7%    |
| Kingston            | 1         | 2.7%    |
| Elpida              | 1         | 2.7%    |
| Crucial             | 1         | 2.7%    |
| ASint Technology    | 1         | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 7.89%   |
| Unknown                                                          | 3         | 7.89%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 5.26%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 5.26%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 2.63%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 2.63%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.63%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 2.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.63%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s           | 1         | 2.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.63%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 2.63%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.63%   |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s              | 1         | 2.63%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.63%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.63%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 2.63%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.63%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 1         | 2.63%   |
| Micron RAM MT62F1G32D2DS-026 WT 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.63%   |
| Micron RAM MT52L1G32D4PG-107 8GB Chip LPDDR3 1867MT/s            | 1         | 2.63%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s               | 1         | 2.63%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s              | 1         | 2.63%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 1         | 2.63%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 2.63%   |
| KLEVV RAM KD48GU880-32A160X 8GB DIMM DDR4 2666MT/s               | 1         | 2.63%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 1         | 2.63%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 2.63%   |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s           | 1         | 2.63%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s               | 1         | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 18        | 56.25%  |
| LPDDR5 | 5         | 15.63%  |
| DDR3   | 5         | 15.63%  |
| DDR5   | 2         | 6.25%   |
| LPDDR4 | 1         | 3.13%   |
| LPDDR3 | 1         | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 68.75%  |
| Row Of Chips | 5         | 15.63%  |
| DIMM         | 4         | 12.5%   |
| Chip         | 1         | 3.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 34.29%  |
| 16384 | 8         | 22.86%  |
| 32768 | 6         | 17.14%  |
| 4096  | 4         | 11.43%  |
| 2048  | 4         | 11.43%  |
| 3072  | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 11        | 32.35%  |
| 6400  | 5         | 14.71%  |
| 1600  | 4         | 11.76%  |
| 2667  | 3         | 8.82%   |
| 8400  | 2         | 5.88%   |
| 2400  | 2         | 5.88%   |
| 5600  | 1         | 2.94%   |
| 4800  | 1         | 2.94%   |
| 3733  | 1         | 2.94%   |
| 2666  | 1         | 2.94%   |
| 2133  | 1         | 2.94%   |
| 1867  | 1         | 2.94%   |
| 1067  | 1         | 2.94%   |

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
| Chicony Electronics                    | 35        | 43.21%  |
| Bison Electronics                      | 11        | 13.58%  |
| Microdia                               | 7         | 8.64%   |
| Sunplus Innovation Technology          | 3         | 3.7%    |
| Lite-On Technology                     | 3         | 3.7%    |
| IMC Networks                           | 3         | 3.7%    |
| Apple                                  | 3         | 3.7%    |
| Suyin                                  | 2         | 2.47%   |
| Valve Software                         | 1         | 1.23%   |
| Unknown                                | 1         | 1.23%   |
| Syntek                                 | 1         | 1.23%   |
| Sony Ericsson Mobile Communications AB | 1         | 1.23%   |
| Ricoh                                  | 1         | 1.23%   |
| Realtek Semiconductor                  | 1         | 1.23%   |
| Luxvisions Innotech Limited            | 1         | 1.23%   |
| Logitech                               | 1         | 1.23%   |
| Lenovo                                 | 1         | 1.23%   |
| KYE Systems (Mouse Systems)            | 1         | 1.23%   |
| Importek                               | 1         | 1.23%   |
| HYGD-220831-A                          | 1         | 1.23%   |
| Generalplus Technology                 | 1         | 1.23%   |
| Alpha Imaging Technology               | 1         | 1.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                    | 10        | 12.35%  |
| Chicony FHD Webcam                                   | 7         | 8.64%   |
| Chicony USB2.0 Camera                                | 6         | 7.41%   |
| Bison BisonCam,NB Pro                                | 4         | 4.94%   |
| IMC Networks Integrated Camera                       | 3         | 3.7%    |
| Chicony Integrated Camera                            | 3         | 3.7%    |
| Bison HD Webcam                                      | 3         | 3.7%    |
| Apple FaceTime HD Camera                             | 3         | 3.7%    |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 2.47%   |
| Microdia Integrated_Webcam_FHD                       | 2         | 2.47%   |
| Bison Lenovo EasyCamera                              | 2         | 2.47%   |
| Valve Software 3D Camera                             | 1         | 1.23%   |
| Unknown HD camera                                    | 1         | 1.23%   |
| Syntek Integrated Camera                             | 1         | 1.23%   |
| Suyin RGBIR Camera                                   | 1         | 1.23%   |
| Suyin HP TrueVision HD                               | 1         | 1.23%   |
| Sunplus SPCA2281 Web Camera                          | 1         | 1.23%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.23%   |
| Sunplus Asus Webcam                                  | 1         | 1.23%   |
| Sony Ericsson Mobile AB XQ-CC54                      | 1         | 1.23%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 1.23%   |
| Realtek Integrated Webcam                            | 1         | 1.23%   |
| Microdia Sonix USB 2.0 Camera                        | 1         | 1.23%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 1.23%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.23%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.23%   |
| Logitech Brio 500                                    | 1         | 1.23%   |
| Lite-On Integrated Camera                            | 1         | 1.23%   |
| Lite-On HP Wide Vision HD Camera                     | 1         | 1.23%   |
| Lite-On HP Webcam                                    | 1         | 1.23%   |
| Lenovo FHD Webcam Audio                              | 1         | 1.23%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera           | 1         | 1.23%   |
| Importek HP Webcam                                   | 1         | 1.23%   |
| HYGD-220831-A Hy-Usb2.0-1*MIC                        | 1         | 1.23%   |
| Generalplus WEB CAM                                  | 1         | 1.23%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 1.23%   |
| Chicony USB 2.0 Camera                               | 1         | 1.23%   |
| Chicony ThinkPad T490 Webcam                         | 1         | 1.23%   |
| Chicony HP TrueVision HD Camera                      | 1         | 1.23%   |
| Chicony HP Truevision HD                             | 1         | 1.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 10        | 55.56%  |
| Validity Sensors      | 7         | 38.89%  |
| LighTuning Technology | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 16.67%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 11.11%  |
| Unknown                                                                    | 2         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 5.56%   |
| Validity Sensors VFS491                                                    | 1         | 5.56%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 5.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 5.56%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 5.56%   |
| Synaptics WBDI                                                             | 1         | 5.56%   |
| Synaptics UWP WBDI                                                         | 1         | 5.56%   |
| Synaptics TouchPad                                                         | 1         | 5.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 5.56%   |
| LighTuning Fingerprint Reader                                              | 1         | 5.56%   |

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
| 0     | 67        | 61.47%  |
| 1     | 40        | 36.7%   |
| 3     | 1         | 0.92%   |
| 2     | 1         | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 18        | 39.13%  |
| Multimedia controller | 13        | 28.26%  |
| Chipcard              | 6         | 13.04%  |
| Graphics card         | 4         | 8.7%    |
| Net/wireless          | 3         | 6.52%   |
| Modem                 | 1         | 2.17%   |
| Camera                | 1         | 2.17%   |

