Linux in Taiwan - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Taiwan.

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

Total: 259

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | P5Q3 DELUXE                 | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| MSI           | A320M PRO-VH                | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| HP            | 1589                        | [a6be3ee931](https://linux-hardware.org/?probe=a6be3ee931) | Oct 17, 2022 |
| HP            | 1589                        | [c36aa260eb](https://linux-hardware.org/?probe=c36aa260eb) | Oct 17, 2022 |
| ASUSTek       | X99-A/USB                   | [11fc608e0a](https://linux-hardware.org/?probe=11fc608e0a) | Oct 10, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [5c45d7b1bf](https://linux-hardware.org/?probe=5c45d7b1bf) | Oct 09, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [0d7188c951](https://linux-hardware.org/?probe=0d7188c951) | Oct 03, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [dbe024bea9](https://linux-hardware.org/?probe=dbe024bea9) | Sep 16, 2022 |
| DNI           | SNDTP-1513N 5508015890      | [9570ee789c](https://linux-hardware.org/?probe=9570ee789c) | Aug 30, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [96a87ada26](https://linux-hardware.org/?probe=96a87ada26) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [aaf726faa0](https://linux-hardware.org/?probe=aaf726faa0) | Aug 20, 2022 |
| ASRock        | B550M-ITX/ac                | [8898e9247d](https://linux-hardware.org/?probe=8898e9247d) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [2d41c9a29f](https://linux-hardware.org/?probe=2d41c9a29f) | Aug 08, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [21d06392bc](https://linux-hardware.org/?probe=21d06392bc) | Aug 06, 2022 |
| Gigabyte      | B550M DS3H                  | [69188053f5](https://linux-hardware.org/?probe=69188053f5) | Aug 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [6f083e1754](https://linux-hardware.org/?probe=6f083e1754) | Jul 27, 2022 |
| Gigabyte      | H310MSTX-HD3-CF             | [13e7ed20e1](https://linux-hardware.org/?probe=13e7ed20e1) | Jul 27, 2022 |
| BESSTAR Te... | HM90                        | [cb4da5b649](https://linux-hardware.org/?probe=cb4da5b649) | Jul 23, 2022 |
| BESSTAR Te... | HM90                        | [380230bbf6](https://linux-hardware.org/?probe=380230bbf6) | Jul 22, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [d88edfec1f](https://linux-hardware.org/?probe=d88edfec1f) | Jul 20, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f32b12f921](https://linux-hardware.org/?probe=f32b12f921) | Jul 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [11fc460e29](https://linux-hardware.org/?probe=11fc460e29) | Jul 13, 2022 |
| MSI           | H81M-P33                    | [e523b324e6](https://linux-hardware.org/?probe=e523b324e6) | Jul 11, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [32e2995911](https://linux-hardware.org/?probe=32e2995911) | Jun 30, 2022 |
| MSI           | H81M-P33                    | [1a0e20ab20](https://linux-hardware.org/?probe=1a0e20ab20) | Jun 29, 2022 |
| MSI           | H81M-P33                    | [e25d17a838](https://linux-hardware.org/?probe=e25d17a838) | Jun 25, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [39cc29c976](https://linux-hardware.org/?probe=39cc29c976) | Jun 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d610c245f8](https://linux-hardware.org/?probe=d610c245f8) | Jun 22, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [73c4749082](https://linux-hardware.org/?probe=73c4749082) | Jun 10, 2022 |
| Gigabyte      | B460 AORUS PRO AC           | [2966cd34b8](https://linux-hardware.org/?probe=2966cd34b8) | May 31, 2022 |
| MSI           | B150M BAZOOKA               | [b8ec3bee43](https://linux-hardware.org/?probe=b8ec3bee43) | May 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2c8abb0fed](https://linux-hardware.org/?probe=2c8abb0fed) | May 12, 2022 |
| Ruckus Wir... | SCG-100                     | [781560aa15](https://linux-hardware.org/?probe=781560aa15) | May 09, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE-10G... | [4ebf4d9cc8](https://linux-hardware.org/?probe=4ebf4d9cc8) | May 09, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [288bb26592](https://linux-hardware.org/?probe=288bb26592) | Apr 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6af9cfacd0](https://linux-hardware.org/?probe=6af9cfacd0) | Apr 23, 2022 |
| Dell          | Precision 3260              | [70a8481a89](https://linux-hardware.org/?probe=70a8481a89) | Apr 19, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [9d2aeecf05](https://linux-hardware.org/?probe=9d2aeecf05) | Apr 15, 2022 |
| Gigabyte      | B75M-D3H                    | [79aee125b7](https://linux-hardware.org/?probe=79aee125b7) | Apr 05, 2022 |
| ASUSTek       | M3A78-EMH HDMI              | [4462ffed73](https://linux-hardware.org/?probe=4462ffed73) | Apr 01, 2022 |
| Gigabyte      | EP31-DS3L                   | [7a4dfc156e](https://linux-hardware.org/?probe=7a4dfc156e) | Mar 28, 2022 |
| Gigabyte      | X570S AERO G                | [97cfd592c5](https://linux-hardware.org/?probe=97cfd592c5) | Mar 22, 2022 |
| ASUSTek       | P8H77-M PRO                 | [f7ee97d348](https://linux-hardware.org/?probe=f7ee97d348) | Mar 16, 2022 |
| ASRock        | X300M-STX                   | [5b18945822](https://linux-hardware.org/?probe=5b18945822) | Mar 15, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [8d52e31d86](https://linux-hardware.org/?probe=8d52e31d86) | Mar 09, 2022 |
| ASRock        | A300M-STX                   | [d9c28765e7](https://linux-hardware.org/?probe=d9c28765e7) | Mar 03, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [c11d937631](https://linux-hardware.org/?probe=c11d937631) | Feb 23, 2022 |
| ASUSTek       | B75M-PLUS                   | [c408f72a53](https://linux-hardware.org/?probe=c408f72a53) | Feb 23, 2022 |
| ASRock        | H81M-ITX                    | [bf52168e79](https://linux-hardware.org/?probe=bf52168e79) | Feb 14, 2022 |
| ASUSTek       | CM6630_CM6730_CM6830        | [bb588fd423](https://linux-hardware.org/?probe=bb588fd423) | Feb 07, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [589137e95b](https://linux-hardware.org/?probe=589137e95b) | Feb 02, 2022 |
| ASUSTek       | P5P41T/USB3                 | [f45dc3454a](https://linux-hardware.org/?probe=f45dc3454a) | Jan 25, 2022 |
| ASUSTek       | P5P41T/USB3                 | [105593cece](https://linux-hardware.org/?probe=105593cece) | Jan 23, 2022 |
| ASUSTek       | P5P41T/USB3                 | [8db65bef56](https://linux-hardware.org/?probe=8db65bef56) | Jan 20, 2022 |
| Acer          | Aspire M3970                | [e10ce7d132](https://linux-hardware.org/?probe=e10ce7d132) | Dec 31, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [cbb5305dc7](https://linux-hardware.org/?probe=cbb5305dc7) | Dec 30, 2021 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [8eec04fc92](https://linux-hardware.org/?probe=8eec04fc92) | Dec 29, 2021 |
| DFI           | HD330-Q87CR                 | [000e53fce1](https://linux-hardware.org/?probe=000e53fce1) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f8a6ac527d](https://linux-hardware.org/?probe=f8a6ac527d) | Dec 27, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [85bcddc2e5](https://linux-hardware.org/?probe=85bcddc2e5) | Dec 27, 2021 |
| Huanan        | B85                         | [d2b55c013c](https://linux-hardware.org/?probe=d2b55c013c) | Dec 07, 2021 |
| Acer          | EG43LMK                     | [28e31230a4](https://linux-hardware.org/?probe=28e31230a4) | Nov 28, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8fb57be688](https://linux-hardware.org/?probe=8fb57be688) | Nov 22, 2021 |
| MSI           | PRO Z690-A DDR4             | [ae15f235e1](https://linux-hardware.org/?probe=ae15f235e1) | Nov 20, 2021 |
| ASRock        | G41C-VS                     | [e4a0a0c2c1](https://linux-hardware.org/?probe=e4a0a0c2c1) | Nov 19, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | [edc27953c6](https://linux-hardware.org/?probe=edc27953c6) | Oct 28, 2021 |
| eMachines     | EMCP73VT-PM                 | [6fe6c2d416](https://linux-hardware.org/?probe=6fe6c2d416) | Oct 27, 2021 |
| ASUSTek       | PRIME B350M-A               | [f20f2bfc32](https://linux-hardware.org/?probe=f20f2bfc32) | Oct 26, 2021 |
| eMachines     | EMCP73VT-PM                 | [22fd625209](https://linux-hardware.org/?probe=22fd625209) | Oct 26, 2021 |
| PANSHI        | B85-S1 V1.0                 | [963f2f28d4](https://linux-hardware.org/?probe=963f2f28d4) | Oct 24, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [09e3d5da46](https://linux-hardware.org/?probe=09e3d5da46) | Oct 21, 2021 |
| HP            | 84FD 10                     | [fb32fc7215](https://linux-hardware.org/?probe=fb32fc7215) | Oct 14, 2021 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [caeaeaddf2](https://linux-hardware.org/?probe=caeaeaddf2) | Oct 12, 2021 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [eef22ec3df](https://linux-hardware.org/?probe=eef22ec3df) | Oct 10, 2021 |
| HP            | 21D0                        | [4fccb60381](https://linux-hardware.org/?probe=4fccb60381) | Oct 08, 2021 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [4b370353e4](https://linux-hardware.org/?probe=4b370353e4) | Sep 29, 2021 |
| Gigabyte      | H81M-H                      | [b961548815](https://linux-hardware.org/?probe=b961548815) | Sep 26, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [7114ee3f72](https://linux-hardware.org/?probe=7114ee3f72) | Sep 13, 2021 |
| Lenovo        | ThinkCentre M58 7627AA9     | [e5bedff47d](https://linux-hardware.org/?probe=e5bedff47d) | Aug 29, 2021 |
| HP            | 802E                        | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek       | H61-PLUS                    | [806118d8b3](https://linux-hardware.org/?probe=806118d8b3) | Aug 22, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | [51947c0182](https://linux-hardware.org/?probe=51947c0182) | Aug 07, 2021 |
| Gigabyte      | H110M-H-CF                  | [37ac6809ad](https://linux-hardware.org/?probe=37ac6809ad) | Jul 31, 2021 |
| MSI           | B250M MORTAR                | [6c6e37fbfe](https://linux-hardware.org/?probe=6c6e37fbfe) | Jul 31, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a8c5113f4c](https://linux-hardware.org/?probe=a8c5113f4c) | Jul 06, 2021 |
| Gigabyte      | H67MA-UD2H-B3               | [e014f9e41f](https://linux-hardware.org/?probe=e014f9e41f) | Jul 05, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [d90a6deaeb](https://linux-hardware.org/?probe=d90a6deaeb) | Jun 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [0e6ca5f944](https://linux-hardware.org/?probe=0e6ca5f944) | Jun 27, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [42090bac96](https://linux-hardware.org/?probe=42090bac96) | Jun 27, 2021 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [cf9f5ab2b6](https://linux-hardware.org/?probe=cf9f5ab2b6) | Jun 23, 2021 |
| ASUSTek       | P8Z77-V LX                  | [98be9faa06](https://linux-hardware.org/?probe=98be9faa06) | Jun 21, 2021 |
| Supermicro    | C9Z490-PGW                  | [9b89e87202](https://linux-hardware.org/?probe=9b89e87202) | Jun 15, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [18b2fc7e21](https://linux-hardware.org/?probe=18b2fc7e21) | Jun 15, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [db99ef3085](https://linux-hardware.org/?probe=db99ef3085) | Jun 14, 2021 |
| Intel         | SHARKBAY                    | [2b38485e94](https://linux-hardware.org/?probe=2b38485e94) | Jun 13, 2021 |
| Dell          | 05GD68 A00                  | [b87ca56da6](https://linux-hardware.org/?probe=b87ca56da6) | Jun 11, 2021 |
| ASUSTek       | P5P41T/USB3                 | [be02c1622c](https://linux-hardware.org/?probe=be02c1622c) | Jun 06, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [ba117fef7e](https://linux-hardware.org/?probe=ba117fef7e) | May 31, 2021 |
| ASUSTek       | P5P41T/USB3                 | [e7eca73b93](https://linux-hardware.org/?probe=e7eca73b93) | May 30, 2021 |
| Dell          | 0RY206                      | [f02982ff12](https://linux-hardware.org/?probe=f02982ff12) | May 29, 2021 |
| ASRock        | H310M-ITX/ac                | [839b20476a](https://linux-hardware.org/?probe=839b20476a) | May 29, 2021 |
| ASRock        | X300M-STX                   | [6b0f0cd327](https://linux-hardware.org/?probe=6b0f0cd327) | May 27, 2021 |
| Gigabyte      | Z390 UD                     | [bbc8131c67](https://linux-hardware.org/?probe=bbc8131c67) | May 05, 2021 |
| Lenovo        | MAHOBAY                     | [6928edc4c3](https://linux-hardware.org/?probe=6928edc4c3) | Apr 30, 2021 |
| ASRock        | H55M/USB3                   | [8041f40ea2](https://linux-hardware.org/?probe=8041f40ea2) | Apr 22, 2021 |
| ASUSTek       | P8Z68-V LX                  | [060122f540](https://linux-hardware.org/?probe=060122f540) | Apr 19, 2021 |
| HP            | 0AECh D                     | [4e2517cb92](https://linux-hardware.org/?probe=4e2517cb92) | Apr 17, 2021 |
| ASUSTek       | P8Z68-V LX                  | [f67c224c2d](https://linux-hardware.org/?probe=f67c224c2d) | Apr 17, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3dcec36efc](https://linux-hardware.org/?probe=3dcec36efc) | Mar 24, 2021 |
| Acer          | M1930                       | [ecd09c75f9](https://linux-hardware.org/?probe=ecd09c75f9) | Mar 23, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [6fed85f2b6](https://linux-hardware.org/?probe=6fed85f2b6) | Mar 21, 2021 |
| Acer          | Veriton L4630G V:1.0        | [d5413884e0](https://linux-hardware.org/?probe=d5413884e0) | Feb 15, 2021 |
| Gigabyte      | B75M-D3H                    | [626560cf30](https://linux-hardware.org/?probe=626560cf30) | Feb 04, 2021 |
| ASRock        | HM87-MXM                    | [95efd1e9a2](https://linux-hardware.org/?probe=95efd1e9a2) | Feb 04, 2021 |
| Acer          | IPIMB-AR                    | [eb7a1feeff](https://linux-hardware.org/?probe=eb7a1feeff) | Jan 25, 2021 |
| MSI           | 760GM-P23                   | [8fdb02babb](https://linux-hardware.org/?probe=8fdb02babb) | Jan 24, 2021 |
| MSI           | 760GM-P23                   | [9ebcac45bd](https://linux-hardware.org/?probe=9ebcac45bd) | Jan 24, 2021 |
| ASUSTek       | TUF Gaming A520M-PLUS       | [ac56dd5c89](https://linux-hardware.org/?probe=ac56dd5c89) | Jan 23, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | [1deb2b04c5](https://linux-hardware.org/?probe=1deb2b04c5) | Jan 21, 2021 |
| ASRock        | X300M-STX                   | [b690109a78](https://linux-hardware.org/?probe=b690109a78) | Jan 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [7ade5574be](https://linux-hardware.org/?probe=7ade5574be) | Jan 14, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [e5dc6589db](https://linux-hardware.org/?probe=e5dc6589db) | Jan 05, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| ASUSTek       | P5P41T/USB3                 | [f8f8546b66](https://linux-hardware.org/?probe=f8f8546b66) | Dec 28, 2020 |
| Gigabyte      | H310M H                     | [dfa5c13a96](https://linux-hardware.org/?probe=dfa5c13a96) | Dec 22, 2020 |
| MSI           | AM1M                        | [e7e7d1e0cc](https://linux-hardware.org/?probe=e7e7d1e0cc) | Dec 21, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [fb4b7a114e](https://linux-hardware.org/?probe=fb4b7a114e) | Dec 14, 2020 |
| Gigabyte      | H87-HD3                     | [55f095e43d](https://linux-hardware.org/?probe=55f095e43d) | Dec 13, 2020 |
| Gigabyte      | EP43-S3L                    | [7c9b5cd232](https://linux-hardware.org/?probe=7c9b5cd232) | Nov 28, 2020 |
| Gigabyte      | EP43-S3L                    | [218d68cc94](https://linux-hardware.org/?probe=218d68cc94) | Nov 27, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [799008f314](https://linux-hardware.org/?probe=799008f314) | Nov 26, 2020 |
| Gigabyte      | EP43-S3L                    | [c91fdcd723](https://linux-hardware.org/?probe=c91fdcd723) | Nov 26, 2020 |
| ASUSTek       | GR8 II-K                    | [dce0e65158](https://linux-hardware.org/?probe=dce0e65158) | Nov 24, 2020 |
| ASUSTek       | H97-PRO                     | [df130b5488](https://linux-hardware.org/?probe=df130b5488) | Nov 23, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | [8b7818376f](https://linux-hardware.org/?probe=8b7818376f) | Nov 18, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | [3d64c2bcc8](https://linux-hardware.org/?probe=3d64c2bcc8) | Nov 17, 2020 |
| ASUSTek       | PRIME B250M-K               | [35bc246b54](https://linux-hardware.org/?probe=35bc246b54) | Nov 13, 2020 |
| ASRock        | HM87-MXM                    | [d47723e369](https://linux-hardware.org/?probe=d47723e369) | Nov 03, 2020 |
| Unknown       | Unknown                     | [3ed3ea4f60](https://linux-hardware.org/?probe=3ed3ea4f60) | Oct 29, 2020 |
| Unknown       | Unknown                     | [c80fe9e03a](https://linux-hardware.org/?probe=c80fe9e03a) | Oct 29, 2020 |
| Gigabyte      | B85M-D2V                    | [1f2b50c872](https://linux-hardware.org/?probe=1f2b50c872) | Oct 24, 2020 |
| Gigabyte      | B75M-D3H                    | [352ce3d09c](https://linux-hardware.org/?probe=352ce3d09c) | Oct 16, 2020 |
| ASUSTek       | K30AM-J_A_F_K31AM-J         | [8de90e5004](https://linux-hardware.org/?probe=8de90e5004) | Oct 12, 2020 |
| MSI           | B450M-A PRO MAX             | [3712afebf5](https://linux-hardware.org/?probe=3712afebf5) | Oct 09, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [605fe21a48](https://linux-hardware.org/?probe=605fe21a48) | Oct 03, 2020 |
| ASUSTek       | M4A785D-M PRO               | [c8033471fb](https://linux-hardware.org/?probe=c8033471fb) | Oct 01, 2020 |
| HP            | 339A                        | [84f1e1735f](https://linux-hardware.org/?probe=84f1e1735f) | Sep 19, 2020 |
| Dell          | 0RY206                      | [40e7b0cafb](https://linux-hardware.org/?probe=40e7b0cafb) | Sep 05, 2020 |
| ASUSTek       | B85M-K                      | [8fe74ac1ad](https://linux-hardware.org/?probe=8fe74ac1ad) | Sep 04, 2020 |
| Unknown       | Unknown                     | [e5e9a43e32](https://linux-hardware.org/?probe=e5e9a43e32) | Sep 04, 2020 |
| NEXCOM        | SKLD4-P1                    | [23c5f53c73](https://linux-hardware.org/?probe=23c5f53c73) | Sep 03, 2020 |
| NEXCOM        | SKLD4-P1                    | [e27e3df3f3](https://linux-hardware.org/?probe=e27e3df3f3) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [26c3ba8ef4](https://linux-hardware.org/?probe=26c3ba8ef4) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [066c04a858](https://linux-hardware.org/?probe=066c04a858) | Sep 02, 2020 |
| MSI           | B450M-A PRO MAX             | [e46d6617a9](https://linux-hardware.org/?probe=e46d6617a9) | Aug 28, 2020 |
| Lenovo        | 7Z74                        | [84586c4db2](https://linux-hardware.org/?probe=84586c4db2) | Aug 27, 2020 |
| ASUSTek       | B85M-K                      | [9fd11c530f](https://linux-hardware.org/?probe=9fd11c530f) | Aug 21, 2020 |
| Gigabyte      | H170-Gaming 3               | [b4bad24684](https://linux-hardware.org/?probe=b4bad24684) | Aug 21, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [67cf1d26af](https://linux-hardware.org/?probe=67cf1d26af) | Aug 12, 2020 |
| Lenovo        | 0B98401 WIN                 | [20cb7c14f8](https://linux-hardware.org/?probe=20cb7c14f8) | Jul 10, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [e012c28e4a](https://linux-hardware.org/?probe=e012c28e4a) | Jul 06, 2020 |
| Gigabyte      | B75M-D3H                    | [925fdfd7c7](https://linux-hardware.org/?probe=925fdfd7c7) | Jun 16, 2020 |
| Dell          | 0RY206                      | [648bdee6ec](https://linux-hardware.org/?probe=648bdee6ec) | May 29, 2020 |
| Gigabyte      | G31M-ES2L                   | [9c2d3cb657](https://linux-hardware.org/?probe=9c2d3cb657) | May 24, 2020 |
| ASRock        | N68-GS4/USB3 FX             | [baefccea96](https://linux-hardware.org/?probe=baefccea96) | May 22, 2020 |
| Gigabyte      | B85M-D2V                    | [ec5da680aa](https://linux-hardware.org/?probe=ec5da680aa) | May 16, 2020 |
| Gigabyte      | B75M-D3H                    | [1069d9adc6](https://linux-hardware.org/?probe=1069d9adc6) | May 10, 2020 |
| Accton        | SAU5041                     | [b1efc2e064](https://linux-hardware.org/?probe=b1efc2e064) | May 07, 2020 |
| ASUSTek       | P8H77-V LE                  | [5ef719f7d8](https://linux-hardware.org/?probe=5ef719f7d8) | May 06, 2020 |
| Gigabyte      | B75M-D3H                    | [235c047618](https://linux-hardware.org/?probe=235c047618) | May 04, 2020 |
| ASUSTek       | P5Q                         | [c6681e044f](https://linux-hardware.org/?probe=c6681e044f) | May 02, 2020 |
| ASUSTek       | P5Q                         | [e620caac82](https://linux-hardware.org/?probe=e620caac82) | May 02, 2020 |
| Lenovo        | 0B98401 WIN                 | [e818900359](https://linux-hardware.org/?probe=e818900359) | May 01, 2020 |
| Lenovo        | 0B98401 WIN                 | [ef970e6611](https://linux-hardware.org/?probe=ef970e6611) | Apr 30, 2020 |
| Gigabyte      | H77M-D3H                    | [b34b605dda](https://linux-hardware.org/?probe=b34b605dda) | Apr 30, 2020 |
| Gigabyte      | B75M-D3H                    | [530e0b1725](https://linux-hardware.org/?probe=530e0b1725) | Apr 24, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [a90f89123d](https://linux-hardware.org/?probe=a90f89123d) | Apr 20, 2020 |
| Accton        | SAU5041                     | [c23eb2c1bb](https://linux-hardware.org/?probe=c23eb2c1bb) | Apr 13, 2020 |
| Unknown       | Unknown                     | [c3983e6074](https://linux-hardware.org/?probe=c3983e6074) | Mar 31, 2020 |
| Unknown       | Unknown                     | [df51a87843](https://linux-hardware.org/?probe=df51a87843) | Mar 31, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [5568d1765b](https://linux-hardware.org/?probe=5568d1765b) | Mar 30, 2020 |
| MSI           | MEG X299 CREATION           | [8112942b50](https://linux-hardware.org/?probe=8112942b50) | Mar 26, 2020 |
| Gigabyte      | Z77-D3H                     | [0a6d8786dc](https://linux-hardware.org/?probe=0a6d8786dc) | Mar 22, 2020 |
| Gigabyte      | Z77-D3H                     | [0b49d54fce](https://linux-hardware.org/?probe=0b49d54fce) | Mar 20, 2020 |
| ASUSTek       | D340MC-C                    | [e1396240d9](https://linux-hardware.org/?probe=e1396240d9) | Mar 19, 2020 |
| ASUSTek       | D840MB                      | [c2599225a3](https://linux-hardware.org/?probe=c2599225a3) | Mar 11, 2020 |
| Lenovo        | Board                       | [81650f1328](https://linux-hardware.org/?probe=81650f1328) | Mar 03, 2020 |
| MSI           | MEG X299 CREATION           | [dc2b1917fc](https://linux-hardware.org/?probe=dc2b1917fc) | Mar 02, 2020 |
| ASRock        | A300M-STX                   | [fed0334ebb](https://linux-hardware.org/?probe=fed0334ebb) | Feb 25, 2020 |
| Gigabyte      | B360 M AORUS PRO-CF         | [8b8bf9eb3c](https://linux-hardware.org/?probe=8b8bf9eb3c) | Feb 05, 2020 |
| Gigabyte      | Z68A-D3H-B3                 | [ec012fce91](https://linux-hardware.org/?probe=ec012fce91) | Jan 30, 2020 |
| ASUSTek       | M5A78L-M LE/USB3            | [871b431e0b](https://linux-hardware.org/?probe=871b431e0b) | Jan 23, 2020 |
| Gigabyte      | P55A-UD4                    | [0765c0e746](https://linux-hardware.org/?probe=0765c0e746) | Jan 23, 2020 |
| ASUSTek       | P8H61-M LX PLUS             | [e1061f8758](https://linux-hardware.org/?probe=e1061f8758) | Jan 17, 2020 |
| Dell          | 0TP412                      | [92059b060a](https://linux-hardware.org/?probe=92059b060a) | Jan 15, 2020 |
| ASUSTek       | Z87-PRO                     | [4c444b85d5](https://linux-hardware.org/?probe=4c444b85d5) | Jan 11, 2020 |
| Foxconn       | 2ADA                        | [161e031506](https://linux-hardware.org/?probe=161e031506) | Jan 11, 2020 |
| MSI           | K9N6PGM2-V2                 | [93e77f9dc3](https://linux-hardware.org/?probe=93e77f9dc3) | Dec 26, 2019 |
| MSI           | K9N6PGM2-V2                 | [7cac7cc3cc](https://linux-hardware.org/?probe=7cac7cc3cc) | Dec 26, 2019 |
| Foxconn       | 2ADA                        | [61f3387aaa](https://linux-hardware.org/?probe=61f3387aaa) | Dec 19, 2019 |
| Acer          | M1930                       | [6f798ab348](https://linux-hardware.org/?probe=6f798ab348) | Dec 16, 2019 |
| ASRock        | 960GC-GS FX                 | [3e7a8d31ef](https://linux-hardware.org/?probe=3e7a8d31ef) | Dec 03, 2019 |
| ASUSTek       | P8Z77-V LX                  | [9f10e816c5](https://linux-hardware.org/?probe=9f10e816c5) | Nov 21, 2019 |
| ASUSTek       | P8Z77-V LX                  | [ad60feb203](https://linux-hardware.org/?probe=ad60feb203) | Nov 21, 2019 |
| MSI           | P45 Platinum                | [178de664ca](https://linux-hardware.org/?probe=178de664ca) | Oct 28, 2019 |
| Lenovo        | ThinkCentre M58 7627AA9     | [4ca1d19d3a](https://linux-hardware.org/?probe=4ca1d19d3a) | Oct 18, 2019 |
| MSI           | K9N6PGM2-V2                 | [8dd08d1a97](https://linux-hardware.org/?probe=8dd08d1a97) | Oct 09, 2019 |
| ASUSTek       | M5A78L-M/USB3               | [0a39f948fd](https://linux-hardware.org/?probe=0a39f948fd) | Sep 29, 2019 |
| ASRock        | H81M-ITX                    | [ce10f2cbfe](https://linux-hardware.org/?probe=ce10f2cbfe) | Sep 26, 2019 |
| ASRock        | H81M-ITX                    | [aed359375a](https://linux-hardware.org/?probe=aed359375a) | Sep 26, 2019 |
| MSI           | X399 SLI PLUS               | [b281f9ca55](https://linux-hardware.org/?probe=b281f9ca55) | Sep 15, 2019 |
| MSI           | X399 SLI PLUS               | [130f51b891](https://linux-hardware.org/?probe=130f51b891) | Sep 11, 2019 |
| MSI           | X399 SLI PLUS               | [8da6642033](https://linux-hardware.org/?probe=8da6642033) | Sep 11, 2019 |
| ASRock        | H81M-VG4 R2.0               | [a6a357de21](https://linux-hardware.org/?probe=a6a357de21) | Aug 08, 2019 |
| Gigabyte      | EX58-UD3R                   | [f5c15b4975](https://linux-hardware.org/?probe=f5c15b4975) | Aug 01, 2019 |
| ASUSTek       | P7H55-M/USB3                | [517d2f4be4](https://linux-hardware.org/?probe=517d2f4be4) | Jul 31, 2019 |
| Gigabyte      | MZGLKCH-SI                  | [0f78f0b23e](https://linux-hardware.org/?probe=0f78f0b23e) | Jul 24, 2019 |
| Unknown       | Unknown                     | [55981af24a](https://linux-hardware.org/?probe=55981af24a) | Jul 17, 2019 |
| Unknown       | Unknown                     | [efe95ef406](https://linux-hardware.org/?probe=efe95ef406) | Jul 17, 2019 |
| Unknown       | Unknown                     | [e8900d6721](https://linux-hardware.org/?probe=e8900d6721) | Jul 15, 2019 |
| Acer          | Veriton M4630G V:1.0        | [087f924e20](https://linux-hardware.org/?probe=087f924e20) | Jul 15, 2019 |
| Unknown       | Unknown                     | [e58e143a7f](https://linux-hardware.org/?probe=e58e143a7f) | Jul 15, 2019 |
| Acer          | Veriton M4630G V:1.0        | [683b87be0f](https://linux-hardware.org/?probe=683b87be0f) | Jul 15, 2019 |
| Acer          | Veriton M4630G V:1.0        | [43db5dc346](https://linux-hardware.org/?probe=43db5dc346) | Jul 15, 2019 |
| Unknown       | Unknown                     | [4124a2b6aa](https://linux-hardware.org/?probe=4124a2b6aa) | Jul 12, 2019 |
| ASUSTek       | Z170-DELUXE                 | [093c4071fd](https://linux-hardware.org/?probe=093c4071fd) | Jul 10, 2019 |
| Unknown       | Unknown                     | [25b6099cd2](https://linux-hardware.org/?probe=25b6099cd2) | Jul 09, 2019 |
| Unknown       | Unknown                     | [c9ae4d965c](https://linux-hardware.org/?probe=c9ae4d965c) | Jul 09, 2019 |
| Unknown       | Unknown                     | [1e3ba128f6](https://linux-hardware.org/?probe=1e3ba128f6) | Jul 08, 2019 |
| ASUSTek       | M5A78L-M LE/USB3            | [44650751a9](https://linux-hardware.org/?probe=44650751a9) | Jul 04, 2019 |
| Gigabyte      | B450M GAMING                | [154fbbffd3](https://linux-hardware.org/?probe=154fbbffd3) | Jul 04, 2019 |
| Gigabyte      | G1.Sniper Z97               | [7552a8cb4c](https://linux-hardware.org/?probe=7552a8cb4c) | Jun 20, 2019 |
| Gigabyte      | GA-M56S-S3                  | [21fb8f59a4](https://linux-hardware.org/?probe=21fb8f59a4) | Jun 07, 2019 |
| Gigabyte      | Z370P D3-CF                 | [a210ba04d3](https://linux-hardware.org/?probe=a210ba04d3) | Jun 04, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [d2e0085e5f](https://linux-hardware.org/?probe=d2e0085e5f) | Jun 04, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [f96a5f5393](https://linux-hardware.org/?probe=f96a5f5393) | Jun 04, 2019 |
| ASUSTek       | WS X299 PRO                 | [510ae49df2](https://linux-hardware.org/?probe=510ae49df2) | May 22, 2019 |
| Acer          | Veriton M6620G v1.0         | [4f1a9afa27](https://linux-hardware.org/?probe=4f1a9afa27) | May 21, 2019 |
| Gigabyte      | Z170M-HERO-CF               | [0d7f7b5382](https://linux-hardware.org/?probe=0d7f7b5382) | Apr 28, 2019 |
| Acer          | Veriton M6620G v1.0         | [d5403368f6](https://linux-hardware.org/?probe=d5403368f6) | Apr 28, 2019 |
| Acer          | Veriton M6620G v1.0         | [1c42aae9b4](https://linux-hardware.org/?probe=1c42aae9b4) | Apr 27, 2019 |
| Gigabyte      | G41M-Combo                  | [f70f72098a](https://linux-hardware.org/?probe=f70f72098a) | Apr 21, 2019 |
| ASRock        | 960GC-GS FX                 | [2ab4402059](https://linux-hardware.org/?probe=2ab4402059) | Apr 13, 2019 |
| MSI           | Z68MA-G45                   | [c3e718dfec](https://linux-hardware.org/?probe=c3e718dfec) | Apr 09, 2019 |
| HP            | ProLiant ML150 Gen9         | [d9b1ec3c37](https://linux-hardware.org/?probe=d9b1ec3c37) | Apr 09, 2019 |
| HP            | ProLiant ML150 Gen9         | [d61584bf4e](https://linux-hardware.org/?probe=d61584bf4e) | Apr 09, 2019 |
| ASRock        | 960GC-GS FX                 | [925ee04320](https://linux-hardware.org/?probe=925ee04320) | Apr 07, 2019 |
| ASUSTek       | BM1AF_BP1AF_BM6AF           | [dcf80c3fe6](https://linux-hardware.org/?probe=dcf80c3fe6) | Apr 03, 2019 |
| Gigabyte      | F2A88X-D3H                  | [d9a29354a7](https://linux-hardware.org/?probe=d9a29354a7) | Feb 19, 2019 |
| Gigabyte      | F2A88X-D3H                  | [a3a29982fd](https://linux-hardware.org/?probe=a3a29982fd) | Feb 19, 2019 |
| ASRock        | H310M-ITX/ac                | [0ae0ba17de](https://linux-hardware.org/?probe=0ae0ba17de) | Feb 02, 2019 |
| Gigabyte      | H87M-D3H                    | [dd3cc86ec3](https://linux-hardware.org/?probe=dd3cc86ec3) | Jan 29, 2019 |
| ASRock        | H310M-ITX/ac                | [899220711e](https://linux-hardware.org/?probe=899220711e) | Jan 25, 2019 |
| Gigabyte      | H87M-D3H                    | [90a29cddfa](https://linux-hardware.org/?probe=90a29cddfa) | Dec 21, 2018 |
| ASRock        | H310M-STX/COM               | [d350550408](https://linux-hardware.org/?probe=d350550408) | Dec 07, 2018 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [3eaee61f5f](https://linux-hardware.org/?probe=3eaee61f5f) | Nov 29, 2018 |
| Gigabyte      | H310 D3                     | [eb95ee1f27](https://linux-hardware.org/?probe=eb95ee1f27) | Nov 20, 2018 |
| MSI           | FM2-A75MA-E35               | [d4730289c0](https://linux-hardware.org/?probe=d4730289c0) | Nov 12, 2018 |
| ASUSTek       | P8H67                       | [821e6f68ce](https://linux-hardware.org/?probe=821e6f68ce) | Sep 17, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 18.04        | 47       | 24.35%  |
| Ubuntu 20.04        | 33       | 17.1%   |
| OpenMandriva 4.2    | 9        | 4.66%   |
| Xubuntu 18.04       | 5        | 2.59%   |
| Ubuntu 22.04        | 5        | 2.59%   |
| Linux Mint 20.3     | 5        | 2.59%   |
| Xubuntu 20.04       | 4        | 2.07%   |
| Pop!_OS 20.04       | 4        | 2.07%   |
| OpenMandriva 4.3    | 4        | 2.07%   |
| Ubuntu 21.10        | 3        | 1.55%   |
| Ubuntu 19.04        | 3        | 1.55%   |
| Kubuntu 20.04       | 3        | 1.55%   |
| Debian 11           | 3        | 1.55%   |
| Zorin 16            | 2        | 1.04%   |
| Ubuntu 20.10        | 2        | 1.04%   |
| Ubuntu 19.10        | 2        | 1.04%   |
| Ubuntu 18.10        | 2        | 1.04%   |
| Ubuntu 16.04        | 2        | 1.04%   |
| ROSA R11            | 2        | 1.04%   |
| openSUSE Leap-15.0  | 2        | 1.04%   |
| OpenMandriva 4.90   | 2        | 1.04%   |
| Linux Mint 20.2     | 2        | 1.04%   |
| KDE neon 20.04      | 2        | 1.04%   |
| Kali 2020.2         | 2        | 1.04%   |
| Fedora 33           | 2        | 1.04%   |
| Endless 3.5.4       | 2        | 1.04%   |
| Debian 10           | 2        | 1.04%   |
| Arch Rolling        | 2        | 1.04%   |
| Zorin 15            | 1        | 0.52%   |
| Xubuntu 22.04       | 1        | 0.52%   |
| Xubuntu 19.04       | 1        | 0.52%   |
| Xubuntu 16.04       | 1        | 0.52%   |
| Ubuntu Unity 16.04  | 1        | 0.52%   |
| Ubuntu MATE 20.04   | 1        | 0.52%   |
| Ubuntu MATE 18.04   | 1        | 0.52%   |
| Ubuntu Budgie 20.04 | 1        | 0.52%   |
| Ubuntu 21.04        | 1        | 0.52%   |
| Pop!_OS 20.10       | 1        | 0.52%   |
| Manjaro 21.3.5      | 1        | 0.52%   |
| Manjaro 21.2.6      | 1        | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 97       | 51.32%  |
| OpenMandriva  | 15       | 7.94%   |
| Xubuntu       | 12       | 6.35%   |
| Linux Mint    | 12       | 6.35%   |
| Fedora        | 6        | 3.17%   |
| Pop!_OS       | 5        | 2.65%   |
| Debian        | 5        | 2.65%   |
| Kubuntu       | 4        | 2.12%   |
| Endless       | 4        | 2.12%   |
| Zorin         | 3        | 1.59%   |
| Manjaro       | 3        | 1.59%   |
| Arch          | 3        | 1.59%   |
| Ubuntu MATE   | 2        | 1.06%   |
| ROSA          | 2        | 1.06%   |
| openSUSE      | 2        | 1.06%   |
| KDE neon      | 2        | 1.06%   |
| Kali          | 2        | 1.06%   |
| Gentoo        | 2        | 1.06%   |
| Clear Linux   | 2        | 1.06%   |
| CentOS        | 2        | 1.06%   |
| Ubuntu Unity  | 1        | 0.53%   |
| Ubuntu Budgie | 1        | 0.53%   |
| Mageia        | 1        | 0.53%   |
| BlackPanther  | 1        | 0.53%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 7        | 3.33%   |
| 5.4.0-42-generic         | 5        | 2.38%   |
| 5.8.0-50-generic         | 4        | 1.9%    |
| 5.4.0-45-generic         | 4        | 1.9%    |
| 5.4.0-28-generic         | 4        | 1.9%    |
| 5.16.7-desktop-1omv4003  | 4        | 1.9%    |
| 5.4.0-58-generic         | 3        | 1.43%   |
| 5.11.0-27-generic        | 3        | 1.43%   |
| 5.0.0-37-generic         | 3        | 1.43%   |
| 5.0.0-23-generic         | 3        | 1.43%   |
| 4.15.0-66-generic        | 3        | 1.43%   |
| 4.15.0-29-generic        | 3        | 1.43%   |
| 5.8.0-55-generic         | 2        | 0.95%   |
| 5.8.0-43-generic         | 2        | 0.95%   |
| 5.8.0-38-generic         | 2        | 0.95%   |
| 5.5.0-kali2-amd64        | 2        | 0.95%   |
| 5.4.0-91-generic         | 2        | 0.95%   |
| 5.4.0-81-generic         | 2        | 0.95%   |
| 5.4.0-80-generic         | 2        | 0.95%   |
| 5.4.0-77-generic         | 2        | 0.95%   |
| 5.4.0-54-generic         | 2        | 0.95%   |
| 5.4.0-53-generic         | 2        | 0.95%   |
| 5.4.0-48-generic         | 2        | 0.95%   |
| 5.4.0-122-generic        | 2        | 0.95%   |
| 5.3.0-40-generic         | 2        | 0.95%   |
| 5.3.0-28-generic         | 2        | 0.95%   |
| 5.18.12-desktop-3omv4090 | 2        | 0.95%   |
| 5.15.0-48-generic        | 2        | 0.95%   |
| 5.13.0-35-generic        | 2        | 0.95%   |
| 5.13.0-30-generic        | 2        | 0.95%   |
| 5.11.12-desktop-1omv4002 | 2        | 0.95%   |
| 5.11.0-43-generic        | 2        | 0.95%   |
| 5.11.0-40-generic        | 2        | 0.95%   |
| 4.19.57                  | 2        | 0.95%   |
| 4.18.0-25-generic        | 2        | 0.95%   |
| 4.18.0-12-generic        | 2        | 0.95%   |
| 4.15.0-99-generic        | 2        | 0.95%   |
| 4.15.0-43-generic        | 2        | 0.95%   |
| 4.12.14-lp150.11-default | 2        | 0.95%   |
| 5.9.8-1000.native        | 1        | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 48       | 24.49%  |
| 4.15.0  | 27       | 13.78%  |
| 5.8.0   | 13       | 6.63%   |
| 5.11.0  | 11       | 5.61%   |
| 5.0.0   | 10       | 5.1%    |
| 4.18.0  | 10       | 5.1%    |
| 5.3.0   | 9        | 4.59%   |
| 5.13.0  | 8        | 4.08%   |
| 5.15.0  | 7        | 3.57%   |
| 5.10.14 | 7        | 3.57%   |
| 5.16.7  | 4        | 2.04%   |
| 5.5.0   | 2        | 1.02%   |
| 5.18.12 | 2        | 1.02%   |
| 5.15.23 | 2        | 1.02%   |
| 5.11.12 | 2        | 1.02%   |
| 5.10.0  | 2        | 1.02%   |
| 4.19.57 | 2        | 1.02%   |
| 4.19.0  | 2        | 1.02%   |
| 4.12.14 | 2        | 1.02%   |
| 5.9.8   | 1        | 0.51%   |
| 5.8.5   | 1        | 0.51%   |
| 5.8.18  | 1        | 0.51%   |
| 5.7.2   | 1        | 0.51%   |
| 5.7.10  | 1        | 0.51%   |
| 5.5.5   | 1        | 0.51%   |
| 5.19.0  | 1        | 0.51%   |
| 5.18.0  | 1        | 0.51%   |
| 5.17.6  | 1        | 0.51%   |
| 5.16.18 | 1        | 0.51%   |
| 5.16.13 | 1        | 0.51%   |
| 5.15.55 | 1        | 0.51%   |
| 5.15.52 | 1        | 0.51%   |
| 5.15.32 | 1        | 0.51%   |
| 5.14.0  | 1        | 0.51%   |
| 5.12.9  | 1        | 0.51%   |
| 5.11.22 | 1        | 0.51%   |
| 5.10.9  | 1        | 0.51%   |
| 5.10.12 | 1        | 0.51%   |
| 5.1.4   | 1        | 0.51%   |
| 5.0.10  | 1        | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 48       | 24.62%  |
| 4.15    | 27       | 13.85%  |
| 5.8     | 15       | 7.69%   |
| 5.11    | 14       | 7.18%   |
| 5.15    | 12       | 6.15%   |
| 5.10    | 11       | 5.64%   |
| 5.0     | 11       | 5.64%   |
| 4.18    | 11       | 5.64%   |
| 5.3     | 9        | 4.62%   |
| 5.13    | 8        | 4.1%    |
| 5.16    | 6        | 3.08%   |
| 4.19    | 4        | 2.05%   |
| 5.5     | 3        | 1.54%   |
| 5.18    | 3        | 1.54%   |
| 4.12    | 2        | 1.03%   |
| 5.9     | 1        | 0.51%   |
| 5.7     | 1        | 0.51%   |
| 5.19    | 1        | 0.51%   |
| 5.17    | 1        | 0.51%   |
| 5.14    | 1        | 0.51%   |
| 5.12    | 1        | 0.51%   |
| 5.1     | 1        | 0.51%   |
| 4.9     | 1        | 0.51%   |
| 4.4     | 1        | 0.51%   |
| 4.14    | 1        | 0.51%   |
| 3.10    | 1        | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 181      | 96.79%  |
| i686   | 6        | 3.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 87       | 45.55%  |
| Unknown       | 42       | 21.99%  |
| KDE5          | 25       | 13.09%  |
| XFCE          | 14       | 7.33%   |
| Cinnamon      | 6        | 3.14%   |
| X-Cinnamon    | 5        | 2.62%   |
| MATE          | 3        | 1.57%   |
| KDE           | 3        | 1.57%   |
| Unity         | 1        | 0.52%   |
| LXQt          | 1        | 0.52%   |
| KDE4          | 1        | 0.52%   |
| i3            | 1        | 0.52%   |
| GNOME Classic | 1        | 0.52%   |
| Budgie        | 1        | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 145      | 76.32%  |
| Unknown | 25       | 13.16%  |
| Wayland | 16       | 8.42%   |
| Tty     | 4        | 2.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 110      | 57.89%  |
| GDM     | 28       | 14.74%  |
| SDDM    | 23       | 12.11%  |
| GDM3    | 11       | 5.79%   |
| LightDM | 9        | 4.74%   |
| TDM     | 8        | 4.21%   |
| KDM     | 1        | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| zh_TW   | 71       | 37.37%  |
| en_US   | 60       | 31.58%  |
| Unknown | 44       | 23.16%  |
| C       | 4        | 2.11%   |
| zh_HK   | 2        | 1.05%   |
| en_HK   | 2        | 1.05%   |
| en_GB   | 2        | 1.05%   |
| zh_CN   | 1        | 0.53%   |
| it_IT   | 1        | 0.53%   |
| es_ES   | 1        | 0.53%   |
| en_PH   | 1        | 0.53%   |
| en_AU   | 1        | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 95       | 50%     |
| EFI  | 95       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 146      | 77.66%  |
| Overlay | 16       | 8.51%   |
| Btrfs   | 12       | 6.38%   |
| Unknown | 7        | 3.72%   |
| Xfs     | 4        | 2.13%   |
| Ext2    | 3        | 1.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 110      | 58.2%   |
| GPT     | 65       | 34.39%  |
| MBR     | 14       | 7.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 146      | 76.84%  |
| Yes       | 44       | 23.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 104      | 54.74%  |
| Yes       | 86       | 45.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 62       | 33.16%  |
| Gigabyte Technology | 48       | 25.67%  |
| MSI                 | 18       | 9.63%   |
| ASRock              | 15       | 8.02%   |
| Acer                | 8        | 4.28%   |
| Hewlett-Packard     | 7        | 3.74%   |
| Lenovo              | 6        | 3.21%   |
| Dell                | 6        | 3.21%   |
| Unknown             | 5        | 2.67%   |
| Supermicro          | 1        | 0.53%   |
| Ruckus Wireless     | 1        | 0.53%   |
| PANSHI              | 1        | 0.53%   |
| NEXCOM              | 1        | 0.53%   |
| Intel               | 1        | 0.53%   |
| Huanan              | 1        | 0.53%   |
| Foxconn             | 1        | 0.53%   |
| eMachines           | 1        | 0.53%   |
| DNI                 | 1        | 0.53%   |
| DFI                 | 1        | 0.53%   |
| BESSTAR Tech        | 1        | 0.53%   |
| Accton              | 1        | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 5        | 2.67%   |
| Gigabyte B75M-D3H               | 4        | 2.14%   |
| Gigabyte B550I AORUS PRO AX     | 4        | 2.14%   |
| ASUS All Series                 | 4        | 2.14%   |
| Lenovo ThinkCentre M58 7627AA9  | 3        | 1.6%    |
| Dell Inspiron 531s              | 3        | 1.6%    |
| ASUS M5A78L-M/USB3              | 3        | 1.6%    |
| MSI MS-7C52                     | 2        | 1.07%   |
| Gigabyte Z97MX-Gaming 5         | 2        | 1.07%   |
| Gigabyte B85M-D2V               | 2        | 1.07%   |
| ASUS TUF Gaming B550M-PLUS      | 2        | 1.07%   |
| ASUS ROG STRIX B350-F GAMING    | 2        | 1.07%   |
| ASUS Pro WS X570-ACE            | 2        | 1.07%   |
| ASUS P8Z77-V LX                 | 2        | 1.07%   |
| ASUS CM6630_CM6730_CM6830       | 2        | 1.07%   |
| ASRock H310M-ITX/ac             | 2        | 1.07%   |
| ASRock A300M-STX                | 2        | 1.07%   |
| ASRock 960GC-GS FX              | 2        | 1.07%   |
| Supermicro C9Z490-PGW           | 1        | 0.53%   |
| Ruckus Wireless SCG-100         | 1        | 0.53%   |
| PANSHI B85-S1 V1.0              | 1        | 0.53%   |
| NEXCOM SKLD4-P1                 | 1        | 0.53%   |
| MSI MS-7D25                     | 1        | 0.53%   |
| MSI MS-7D19                     | 1        | 0.53%   |
| MSI MS-7D08                     | 1        | 0.53%   |
| MSI MS-7C06                     | 1        | 0.53%   |
| MSI MS-7B89                     | 1        | 0.53%   |
| MSI MS-7B09                     | 1        | 0.53%   |
| MSI MS-7A69                     | 1        | 0.53%   |
| MSI MS-7A32                     | 1        | 0.53%   |
| MSI MS-7982                     | 1        | 0.53%   |
| MSI MS-7865                     | 1        | 0.53%   |
| MSI MS-7817                     | 1        | 0.53%   |
| MSI MS-7721                     | 1        | 0.53%   |
| MSI MS-7676                     | 1        | 0.53%   |
| MSI MS-7641                     | 1        | 0.53%   |
| MSI MS-7512                     | 1        | 0.53%   |
| MSI MS-7309                     | 1        | 0.53%   |
| Lenovo ThinkSystem ST650V2      | 1        | 0.53%   |
| Lenovo ThinkStation C30 11361G5 | 1        | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS ROG                | 9        | 4.81%   |
| ASUS TUF                | 8        | 4.28%   |
| Unknown                 | 5        | 2.67%   |
| Gigabyte B75M-D3H       | 4        | 2.14%   |
| Gigabyte B550I          | 4        | 2.14%   |
| Dell Inspiron           | 4        | 2.14%   |
| ASUS PRIME              | 4        | 2.14%   |
| ASUS M5A78L-M           | 4        | 2.14%   |
| ASUS All                | 4        | 2.14%   |
| Acer Veriton            | 4        | 2.14%   |
| Acer Aspire             | 4        | 2.14%   |
| Lenovo ThinkCentre      | 3        | 1.6%    |
| ASUS Pro                | 3        | 1.6%    |
| ASUS P8Z77-V            | 3        | 1.6%    |
| MSI MS-7C52             | 2        | 1.07%   |
| Gigabyte Z97MX-Gaming   | 2        | 1.07%   |
| Gigabyte B85M-D2V       | 2        | 1.07%   |
| Dell Precision          | 2        | 1.07%   |
| ASUS P8H61-M            | 2        | 1.07%   |
| ASUS CM6630             | 2        | 1.07%   |
| ASUS ASUSPRO            | 2        | 1.07%   |
| ASRock H310M-ITX        | 2        | 1.07%   |
| ASRock A300M-STX        | 2        | 1.07%   |
| ASRock 960GC-GS         | 2        | 1.07%   |
| Supermicro C9Z490-PGW   | 1        | 0.53%   |
| Ruckus Wireless SCG-100 | 1        | 0.53%   |
| PANSHI B85-S1           | 1        | 0.53%   |
| NEXCOM SKLD4-P1         | 1        | 0.53%   |
| MSI MS-7D25             | 1        | 0.53%   |
| MSI MS-7D19             | 1        | 0.53%   |
| MSI MS-7D08             | 1        | 0.53%   |
| MSI MS-7C06             | 1        | 0.53%   |
| MSI MS-7B89             | 1        | 0.53%   |
| MSI MS-7B09             | 1        | 0.53%   |
| MSI MS-7A69             | 1        | 0.53%   |
| MSI MS-7A32             | 1        | 0.53%   |
| MSI MS-7982             | 1        | 0.53%   |
| MSI MS-7865             | 1        | 0.53%   |
| MSI MS-7817             | 1        | 0.53%   |
| MSI MS-7721             | 1        | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 26       | 13.9%   |
| 2020 | 23       | 12.3%   |
| 2012 | 19       | 10.16%  |
| 2013 | 16       | 8.56%   |
| 2021 | 14       | 7.49%   |
| 2014 | 14       | 7.49%   |
| 2011 | 13       | 6.95%   |
| 2019 | 9        | 4.81%   |
| 2017 | 9        | 4.81%   |
| 2016 | 9        | 4.81%   |
| 2009 | 9        | 4.81%   |
| 2008 | 8        | 4.28%   |
| 2010 | 7        | 3.74%   |
| 2015 | 6        | 3.21%   |
| 2007 | 4        | 2.14%   |
| 2022 | 1        | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 187      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 185      | 98.4%   |
| Enabled  | 3        | 1.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 187      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 45       | 23.81%  |
| 32.01-64.0      | 37       | 19.58%  |
| 8.01-16.0       | 33       | 17.46%  |
| 3.01-4.0        | 31       | 16.4%   |
| 4.01-8.0        | 25       | 13.23%  |
| 64.01-256.0     | 8        | 4.23%   |
| 1.01-2.0        | 5        | 2.65%   |
| 24.01-32.0      | 4        | 2.12%   |
| More than 256.0 | 1        | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 83       | 41.29%  |
| 2.01-3.0   | 52       | 25.87%  |
| 4.01-8.0   | 27       | 13.43%  |
| 3.01-4.0   | 23       | 11.44%  |
| 0.51-1.0   | 6        | 2.99%   |
| 8.01-16.0  | 5        | 2.49%   |
| 16.01-24.0 | 2        | 1%      |
| 0.01-0.5   | 2        | 1%      |
| 24.01-32.0 | 1        | 0.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 70       | 37.23%  |
| 2      | 54       | 28.72%  |
| 3      | 33       | 17.55%  |
| 4      | 12       | 6.38%   |
| 5      | 8        | 4.26%   |
| 0      | 6        | 3.19%   |
| 6      | 3        | 1.6%    |
| 14     | 1        | 0.53%   |
| 7      | 1        | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 65.96%  |
| Yes       | 64       | 34.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 183      | 97.86%  |
| No        | 4        | 2.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 108      | 57.75%  |
| Yes       | 79       | 42.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 65.26%  |
| Yes       | 66       | 34.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Taiwan  | 187      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Taipei            | 58       | 30.05%  |
| New Taipei        | 33       | 17.1%   |
| Taoyuan District  | 16       | 8.29%   |
| Hsinchu           | 16       | 8.29%   |
| Taichung          | 15       | 7.77%   |
| Tainan City       | 12       | 6.22%   |
| Kaohsiung City    | 12       | 6.22%   |
| Chang-hua         | 4        | 2.07%   |
| Miaoli            | 3        | 1.55%   |
| Keelung           | 3        | 1.55%   |
| Yilan             | 2        | 1.04%   |
| Kanzijiao         | 2        | 1.04%   |
| Hsinchu County    | 2        | 1.04%   |
| Zhudong           | 1        | 0.52%   |
| Xinzhuang         | 1        | 0.52%   |
| Xindian           | 1        | 0.52%   |
| Xiatayou          | 1        | 0.52%   |
| Taoyuan City      | 1        | 0.52%   |
| Taishan           | 1        | 0.52%   |
| Taichung City     | 1        | 0.52%   |
| Sanchong District | 1        | 0.52%   |
| Nantou City       | 1        | 0.52%   |
| Magong            | 1        | 0.52%   |
| Hualien City      | 1        | 0.52%   |
| Chongde           | 1        | 0.52%   |
| Chiayi City       | 1        | 0.52%   |
| Chiayi            | 1        | 0.52%   |
| Aquan             | 1        | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 59       | 92     | 17.4%   |
| Seagate                   | 59       | 104    | 17.4%   |
| Toshiba                   | 34       | 46     | 10.03%  |
| Crucial                   | 24       | 30     | 7.08%   |
| Intel                     | 20       | 27     | 5.9%    |
| Hitachi                   | 15       | 19     | 4.42%   |
| Kingston                  | 13       | 18     | 3.83%   |
| A-DATA Technology         | 13       | 15     | 3.83%   |
| SanDisk                   | 10       | 15     | 2.95%   |
| Transcend                 | 9        | 10     | 2.65%   |
| Unknown                   | 8        | 9      | 2.36%   |
| Samsung Electronics       | 8        | 9      | 2.36%   |
| Plextor                   | 7        | 8      | 2.06%   |
| Apacer                    | 6        | 8      | 1.77%   |
| Silicon Motion            | 3        | 3      | 0.88%   |
| Micron/Crucial Technology | 3        | 4      | 0.88%   |
| Micron Technology         | 3        | 3      | 0.88%   |
| Maxtor                    | 3        | 3      | 0.88%   |
| Lite-On                   | 3        | 3      | 0.88%   |
| ANACOMDA                  | 3        | 3      | 0.88%   |
| SPCC                      | 2        | 2      | 0.59%   |
| PNY                       | 2        | 2      | 0.59%   |
| Phison                    | 2        | 3      | 0.59%   |
| Patriot                   | 2        | 2      | 0.59%   |
| OCZ                       | 2        | 2      | 0.59%   |
| Fujitsu                   | 2        | 3      | 0.59%   |
| ASMT                      | 2        | 2      | 0.59%   |
| XPG                       | 1        | 1      | 0.29%   |
| Wintec                    | 1        | 1      | 0.29%   |
| Unknown (583)             | 1        | 1      | 0.29%   |
| Team                      | 1        | 2      | 0.29%   |
| SSSTC                     | 1        | 1      | 0.29%   |
| Sony                      | 1        | 1      | 0.29%   |
| Pioneer                   | 1        | 1      | 0.29%   |
| OCZ-VECT                  | 1        | 1      | 0.29%   |
| OCZ-REVODRIVE             | 1        | 4      | 0.29%   |
| MemoCom                   | 1        | 2      | 0.29%   |
| LITEONIT                  | 1        | 1      | 0.29%   |
| KLEVV                     | 1        | 1      | 0.29%   |
| Hikvision                 | 1        | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB              | 10       | 2.67%   |
| Toshiba DT01ACA200 2TB              | 9        | 2.41%   |
| Crucial CT500MX500SSD1 500GB        | 8        | 2.14%   |
| Seagate ST2000DM008-2FR102 2TB      | 7        | 1.87%   |
| Toshiba MQ01ABD032 320GB            | 5        | 1.34%   |
| Seagate ST500DM002-1BD142 500GB     | 5        | 1.34%   |
| Crucial CT1000MX500SSD1 1TB         | 5        | 1.34%   |
| WDC WDS250G1B0B-00AS40 250GB SSD    | 4        | 1.07%   |
| Seagate ST3500418AS 500GB           | 4        | 1.07%   |
| Seagate ST2000DM001-1CH164 2TB      | 4        | 1.07%   |
| WDC WD6402AAEX-00Z3A0 640GB         | 3        | 0.8%    |
| WDC WD1600AAJS-08L7A0 160GB         | 3        | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB            | 3        | 0.8%    |
| Unknown 004G60  4GB                 | 3        | 0.8%    |
| Silicon Motion NVMe SSD Drive 512GB | 3        | 0.8%    |
| Seagate ST750LX003-1AC154 752GB     | 3        | 0.8%    |
| Seagate ST1000DM003-1ER162 1TB      | 3        | 0.8%    |
| SanDisk NVMe SSD Drive 500GB        | 3        | 0.8%    |
| Micron/Crucial NVMe SSD Drive 1TB   | 3        | 0.8%    |
| Kingston SA400S37480G 480GB SSD     | 3        | 0.8%    |
| Apacer 256GB SATA Flash Drive SSD   | 3        | 0.8%    |
| WDC WDS500G2B0C-00PXH0 500GB        | 2        | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2        | 0.53%   |
| WDC WD5000AAKX-001CA0 500GB         | 2        | 0.53%   |
| WDC WD3200AAKS-00L9A0 320GB         | 2        | 0.53%   |
| WDC WD20EARX-00PASB0 2TB            | 2        | 0.53%   |
| WDC WD1001FALS-00J7B1 1TB           | 2        | 0.53%   |
| Transcend TS128GSSD340 128GB        | 2        | 0.53%   |
| Toshiba MQ02ABF050H 500GB           | 2        | 0.53%   |
| Toshiba DT02ABA400 4TB              | 2        | 0.53%   |
| SPCC Solid State Disk 120GB         | 2        | 0.53%   |
| Seagate ST6000DM003-2CY186 6TB      | 2        | 0.53%   |
| Seagate ST4000VN000-1H4168 4TB      | 2        | 0.53%   |
| Seagate ST3500410SV 500GB           | 2        | 0.53%   |
| Seagate ST3320613AS 320GB           | 2        | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB      | 2        | 0.53%   |
| SanDisk Ultra II 480GB SSD          | 2        | 0.53%   |
| SanDisk NVMe SSD Drive 1TB          | 2        | 0.53%   |
| PNY CS3030 2TB SSD                  | 2        | 0.53%   |
| Patriot Burst 120GB SSD             | 2        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 59       | 102    | 37.58%  |
| WDC                 | 43       | 66     | 27.39%  |
| Toshiba             | 32       | 44     | 20.38%  |
| Hitachi             | 15       | 19     | 9.55%   |
| Maxtor              | 3        | 3      | 1.91%   |
| Unknown (583)       | 1        | 1      | 0.64%   |
| Unknown             | 1        | 1      | 0.64%   |
| Samsung Electronics | 1        | 1      | 0.64%   |
| HGST                | 1        | 2      | 0.64%   |
| Fujitsu             | 1        | 2      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 23       | 28     | 19.17%  |
| Intel               | 12       | 14     | 10%     |
| WDC                 | 11       | 16     | 9.17%   |
| A-DATA Technology   | 10       | 12     | 8.33%   |
| Transcend           | 9        | 10     | 7.5%    |
| Kingston            | 7        | 9      | 5.83%   |
| Plextor             | 6        | 7      | 5%      |
| Apacer              | 5        | 7      | 4.17%   |
| Samsung Electronics | 4        | 4      | 3.33%   |
| SanDisk             | 3        | 4      | 2.5%    |
| ANACOMDA            | 3        | 3      | 2.5%    |
| Toshiba             | 2        | 2      | 1.67%   |
| SPCC                | 2        | 2      | 1.67%   |
| Patriot             | 2        | 2      | 1.67%   |
| OCZ                 | 2        | 2      | 1.67%   |
| Micron Technology   | 2        | 2      | 1.67%   |
| ASMT                | 2        | 2      | 1.67%   |
| Wintec              | 1        | 1      | 0.83%   |
| Unknown             | 1        | 1      | 0.83%   |
| Team                | 1        | 2      | 0.83%   |
| Sony                | 1        | 1      | 0.83%   |
| OCZ-VECT            | 1        | 1      | 0.83%   |
| OCZ-REVODRIVE       | 1        | 4      | 0.83%   |
| MemoCom             | 1        | 2      | 0.83%   |
| LITEONIT            | 1        | 1      | 0.83%   |
| KLEVV               | 1        | 1      | 0.83%   |
| Hewlett-Packard     | 1        | 1      | 0.83%   |
| Fujitsu             | 1        | 1      | 0.83%   |
| EZLINK              | 1        | 1      | 0.83%   |
| AXIOMTEK            | 1        | 1      | 0.83%   |
| ATP                 | 1        | 1      | 0.83%   |
| AGI                 | 1        | 2      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 125      | 241    | 44.8%   |
| SSD     | 97       | 147    | 34.77%  |
| NVMe    | 50       | 77     | 17.92%  |
| Unknown | 4        | 6      | 1.43%   |
| MMC     | 3        | 3      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 166      | 371    | 72.49%  |
| NVMe | 50       | 77     | 21.83%  |
| SAS  | 10       | 23     | 4.37%   |
| MMC  | 3        | 3      | 1.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 118      | 206    | 49.58%  |
| 0.51-1.0   | 65       | 92     | 27.31%  |
| 1.01-2.0   | 32       | 52     | 13.45%  |
| 3.01-4.0   | 11       | 14     | 4.62%   |
| 4.01-10.0  | 6        | 16     | 2.52%   |
| 2.01-3.0   | 5        | 7      | 2.1%    |
| 10.01-20.0 | 1        | 1      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 45       | 22.96%  |
| 251-500        | 36       | 18.37%  |
| 1001-2000      | 23       | 11.73%  |
| 501-1000       | 23       | 11.73%  |
| 2001-3000      | 17       | 8.67%   |
| 51-100         | 16       | 8.16%   |
| 1-20           | 11       | 5.61%   |
| More than 3000 | 10       | 5.1%    |
| 21-50          | 9        | 4.59%   |
| Unknown        | 6        | 3.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 76       | 37.81%  |
| 101-250        | 27       | 13.43%  |
| 51-100         | 26       | 12.94%  |
| 21-50          | 25       | 12.44%  |
| 251-500        | 12       | 5.97%   |
| 1001-2000      | 12       | 5.97%   |
| 501-1000       | 11       | 5.47%   |
| Unknown        | 6        | 2.99%   |
| More than 3000 | 3        | 1.49%   |
| 2001-3000      | 3        | 1.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Intel SSDPEKKW256G7 256GB           | 2        | 3      | 8.7%    |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-001CA0 500GB         | 1        | 1      | 4.35%   |
| WDC WD5000AADS-00L4B1 500GB         | 1        | 1      | 4.35%   |
| WDC WD3200AAKS-00L9A0 320GB         | 1        | 1      | 4.35%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1      | 4.35%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 4.35%   |
| WDC WD10EFRX-68JCSN0 1TB            | 1        | 1      | 4.35%   |
| WDC WD10EALS-00Z8A0 1TB             | 1        | 1      | 4.35%   |
| Transcend TS64GSSD340 64GB          | 1        | 1      | 4.35%   |
| Seagate ST4000DX001-1CE168 4TB      | 1        | 1      | 4.35%   |
| Seagate ST3500410SV 500GB           | 1        | 1      | 4.35%   |
| Seagate ST3160811AS 160GB           | 1        | 1      | 4.35%   |
| Seagate ST2000VN000-1H3164 2TB      | 1        | 2      | 4.35%   |
| Samsung Electronics HM321HI 320GB   | 1        | 1      | 4.35%   |
| Plextor PX-128M6Pro 128GB SSD       | 1        | 1      | 4.35%   |
| LITEONIT E200-080 80GB SSD          | 1        | 1      | 4.35%   |
| Kingston SV300S37A60G 64GB SSD      | 1        | 1      | 4.35%   |
| Hitachi HDT721010SLA360 1TB         | 1        | 1      | 4.35%   |
| Hitachi HDS723020BLA642 2TB         | 1        | 2      | 4.35%   |
| Crucial CT275MX300SSD4 275GB        | 1        | 1      | 4.35%   |
| A-DATA Technology IMSS332-960GB SSD | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 8      | 34.78%  |
| Seagate             | 4        | 5      | 17.39%  |
| Intel               | 2        | 3      | 8.7%    |
| Hitachi             | 2        | 3      | 8.7%    |
| Transcend           | 1        | 1      | 4.35%   |
| Samsung Electronics | 1        | 1      | 4.35%   |
| Plextor             | 1        | 1      | 4.35%   |
| LITEONIT            | 1        | 1      | 4.35%   |
| Kingston            | 1        | 1      | 4.35%   |
| Crucial             | 1        | 1      | 4.35%   |
| A-DATA Technology   | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 8      | 53.33%  |
| Seagate             | 4        | 5      | 26.67%  |
| Hitachi             | 2        | 3      | 13.33%  |
| Samsung Electronics | 1        | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 17     | 61.9%   |
| SSD  | 6        | 6      | 28.57%  |
| NVMe | 2        | 3      | 9.52%   |

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
| Detected | 115      | 304    | 56.1%   |
| Works    | 69       | 144    | 33.66%  |
| Malfunc  | 21       | 26     | 10.24%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 129      | 49.24%  |
| AMD                            | 53       | 20.23%  |
| SanDisk                        | 14       | 5.34%   |
| ASMedia Technology             | 11       | 4.2%    |
| Phison Electronics             | 7        | 2.67%   |
| Nvidia                         | 7        | 2.67%   |
| Kingston Technology Company    | 6        | 2.29%   |
| Micron/Crucial Technology      | 5        | 1.91%   |
| Marvell Technology Group       | 5        | 1.91%   |
| Silicon Motion                 | 4        | 1.53%   |
| ADATA Technology               | 4        | 1.53%   |
| Samsung Electronics            | 3        | 1.15%   |
| Lite-On Technology             | 3        | 1.15%   |
| JMicron Technology             | 3        | 1.15%   |
| Solid State Storage Technology | 2        | 0.76%   |
| LSI Logic / Symbios Logic      | 2        | 0.76%   |
| Silicon Image                  | 1        | 0.38%   |
| Micron Technology              | 1        | 0.38%   |
| Integrated Technology Express  | 1        | 0.38%   |
| Broadcom / LSI                 | 1        | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 30       | 8.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20       | 5.97%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 3.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 3.28%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 2.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 2.69%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 2.39%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 7        | 2.09%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 7        | 2.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 2.09%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 2.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 2.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 1.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5        | 1.49%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.49%   |
| Nvidia MCP61 IDE                                                                        | 5        | 1.49%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 1.49%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.49%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.49%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 4        | 1.19%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 1.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4        | 1.19%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.19%   |
| ASMedia 106x SATA/RAID Controller                                                       | 4        | 1.19%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 4        | 1.19%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 0.9%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 0.9%    |
| Phison E12 NVMe Controller                                                              | 3        | 0.9%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 3        | 0.9%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.9%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.9%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.9%    |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3        | 0.9%    |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3        | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 0.9%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 150      | 57.47%  |
| NVMe | 50       | 19.16%  |
| IDE  | 48       | 18.39%  |
| RAID | 9        | 3.45%   |
| SAS  | 3        | 1.15%   |
| SCSI | 1        | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 128      | 68.45%  |
| AMD    | 59       | 31.55%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 2.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 2.12%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 4        | 2.12%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz         | 3        | 1.59%   |
| Intel Pentium CPU G840 @ 2.80GHz            | 3        | 1.59%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 1.59%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 3        | 1.59%   |
| Intel Celeron J4105 CPU @ 1.50GHz           | 3        | 1.59%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 1.59%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 2        | 1.06%   |
| Intel Pentium Gold G5500 CPU @ 3.80GHz      | 2        | 1.06%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 1.06%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 1.06%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.06%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 1.06%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.06%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.06%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.06%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.06%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2        | 1.06%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 2        | 1.06%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.06%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.06%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.06%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.06%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 1.06%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.06%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 1.06%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 1.06%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.06%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 1.06%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.06%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.06%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2        | 1.06%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 2        | 1.06%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.06%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.06%   |
| AMD Athlon 64 X2 Dual Core Processor 3600+  | 2        | 1.06%   |
| Intel Xeon W-3275 CPU @ 2.50GHz             | 1        | 0.53%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 30       | 15.87%  |
| Intel Core i3           | 22       | 11.64%  |
| Intel Core i7           | 21       | 11.11%  |
| AMD Ryzen 5             | 16       | 8.47%   |
| Intel Xeon              | 14       | 7.41%   |
| AMD Ryzen 7             | 12       | 6.35%   |
| Intel Core 2 Quad       | 8        | 4.23%   |
| Other                   | 7        | 3.7%    |
| Intel Celeron           | 7        | 3.7%    |
| AMD Ryzen 9             | 7        | 3.7%    |
| Intel Pentium           | 6        | 3.17%   |
| AMD FX                  | 6        | 3.17%   |
| Intel Core 2 Duo        | 4        | 2.12%   |
| AMD Athlon 64 X2        | 4        | 2.12%   |
| Intel Pentium Gold      | 3        | 1.59%   |
| Intel Genuine           | 3        | 1.59%   |
| Intel Pentium Dual-Core | 2        | 1.06%   |
| Intel Core i9           | 2        | 1.06%   |
| AMD Ryzen 5 PRO         | 2        | 1.06%   |
| AMD Phenom II X4        | 2        | 1.06%   |
| AMD Athlon II X2        | 2        | 1.06%   |
| Intel Pentium Silver    | 1        | 0.53%   |
| AMD Sempron             | 1        | 0.53%   |
| AMD Ryzen Threadripper  | 1        | 0.53%   |
| AMD Ryzen 3             | 1        | 0.53%   |
| AMD Phenom II X6        | 1        | 0.53%   |
| AMD Phenom II X2        | 1        | 0.53%   |
| AMD Athlon              | 1        | 0.53%   |
| AMD A8                  | 1        | 0.53%   |
| AMD A10                 | 1        | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 78       | 41.49%  |
| 2      | 49       | 26.06%  |
| 6      | 21       | 11.17%  |
| 8      | 19       | 10.11%  |
| 12     | 9        | 4.79%   |
| 16     | 6        | 3.19%   |
| 3      | 2        | 1.06%   |
| 48     | 1        | 0.53%   |
| 44     | 1        | 0.53%   |
| 28     | 1        | 0.53%   |
| 18     | 1        | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 182      | 97.33%  |
| 2      | 5        | 2.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 105      | 55.56%  |
| 1      | 84       | 44.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 182      | 96.81%  |
| Unknown        | 6        | 3.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 15.63%  |
| 0x306c3    | 22       | 11.46%  |
| 0x306a9    | 15       | 7.81%   |
| 0x206a7    | 12       | 6.25%   |
| 0x08701021 | 8        | 4.17%   |
| 0x506e3    | 7        | 3.65%   |
| 0x1067a    | 7        | 3.65%   |
| 0x906eb    | 6        | 3.13%   |
| 0x906ea    | 5        | 2.6%    |
| 0x706a1    | 4        | 2.08%   |
| 0x90672    | 3        | 1.56%   |
| 0x10676    | 3        | 1.56%   |
| 0x0810100b | 3        | 1.56%   |
| 0x08001138 | 3        | 1.56%   |
| 0x06000852 | 3        | 1.56%   |
| 0xa0671    | 2        | 1.04%   |
| 0xa0655    | 2        | 1.04%   |
| 0xa0653    | 2        | 1.04%   |
| 0x6fb      | 2        | 1.04%   |
| 0x50654    | 2        | 1.04%   |
| 0x106e5    | 2        | 1.04%   |
| 0x10677    | 2        | 1.04%   |
| 0x0a50000c | 2        | 1.04%   |
| 0x0a20120a | 2        | 1.04%   |
| 0x0a201016 | 2        | 1.04%   |
| 0x0a201009 | 2        | 1.04%   |
| 0x08600106 | 2        | 1.04%   |
| 0x08101016 | 2        | 1.04%   |
| 0x0800820d | 2        | 1.04%   |
| 0x0800820b | 2        | 1.04%   |
| 0x010000c8 | 2        | 1.04%   |
| 0x906ed    | 1        | 0.52%   |
| 0x90671    | 1        | 0.52%   |
| 0x606a4    | 1        | 0.52%   |
| 0x506ca    | 1        | 0.52%   |
| 0x50665    | 1        | 0.52%   |
| 0x406f0    | 1        | 0.52%   |
| 0x406e3    | 1        | 0.52%   |
| 0x306f2    | 1        | 0.52%   |
| 0x306e4    | 1        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 28       | 14.89%  |
| IvyBridge        | 18       | 9.57%   |
| Zen 2            | 15       | 7.98%   |
| SandyBridge      | 15       | 7.98%   |
| KabyLake         | 15       | 7.98%   |
| Penryn           | 13       | 6.91%   |
| Skylake          | 12       | 6.38%   |
| Zen 3            | 10       | 5.32%   |
| Zen              | 10       | 5.32%   |
| K10              | 7        | 3.72%   |
| Piledriver       | 6        | 3.19%   |
| Zen+             | 5        | 2.66%   |
| K8 Hammer        | 4        | 2.13%   |
| Goldmont plus    | 4        | 2.13%   |
| CometLake        | 4        | 2.13%   |
| Unknown          | 4        | 2.13%   |
| Nehalem          | 3        | 1.6%    |
| Icelake          | 3        | 1.6%    |
| Westmere         | 2        | 1.06%   |
| Core             | 2        | 1.06%   |
| Broadwell        | 2        | 1.06%   |
| Steamroller      | 1        | 0.53%   |
| Silvermont       | 1        | 0.53%   |
| Jaguar           | 1        | 0.53%   |
| Goldmont         | 1        | 0.53%   |
| Bulldozer        | 1        | 0.53%   |
| Alderlake Hybrid | 1        | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 84       | 43.75%  |
| Intel                      | 64       | 33.33%  |
| AMD                        | 40       | 20.83%  |
| Matrox Electronics Systems | 2        | 1.04%   |
| ASPEED Technology          | 2        | 1.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 5.15%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 4.64%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 3.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 3.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 3.61%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 3.09%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 3.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 2.58%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 4        | 2.06%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 2.06%   |
| Intel AlderLake-S GT1                                                       | 4        | 2.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 2.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 2.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 2.06%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 1.55%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.55%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.55%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 3        | 1.55%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 1.55%   |
| Intel HD Graphics 530                                                       | 3        | 1.55%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3        | 1.55%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.55%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 1.55%   |
| AMD Renoir                                                                  | 3        | 1.55%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.55%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.03%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.03%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.03%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 1.03%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 2        | 1.03%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 1.03%   |
| ASPEED Technology ASPEED Graphics Family                                    | 2        | 1.03%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.03%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.03%   |
| AMD Cezanne                                                                 | 2        | 1.03%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.52%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.52%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.52%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 78       | 41.27%  |
| 1 x Intel      | 61       | 32.28%  |
| 1 x AMD        | 39       | 20.63%  |
| Intel + Nvidia | 4        | 2.12%   |
| Other          | 2        | 1.06%   |
| 1 x Matrox     | 2        | 1.06%   |
| 1 x ASPEED     | 2        | 1.06%   |
| AMD + Nvidia   | 1        | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 133      | 68.91%  |
| Proprietary | 45       | 23.32%  |
| Unknown     | 15       | 7.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 85       | 43.37%  |
| 1.01-2.0   | 29       | 14.8%   |
| 0.51-1.0   | 20       | 10.2%   |
| 0.01-0.5   | 19       | 9.69%   |
| 5.01-6.0   | 16       | 8.16%   |
| 3.01-4.0   | 16       | 8.16%   |
| 7.01-8.0   | 5        | 2.55%   |
| 2.01-3.0   | 3        | 1.53%   |
| 8.01-16.0  | 3        | 1.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Ancor Communications    | 25       | 13.3%   |
| BenQ                    | 23       | 12.23%  |
| ViewSonic               | 17       | 9.04%   |
| Acer                    | 17       | 9.04%   |
| Dell                    | 12       | 6.38%   |
| Goldstar                | 10       | 5.32%   |
| AOC                     | 10       | 5.32%   |
| Samsung Electronics     | 9        | 4.79%   |
| Philips                 | 9        | 4.79%   |
| Hewlett-Packard         | 7        | 3.72%   |
| ASUSTek Computer        | 6        | 3.19%   |
| Unknown                 | 5        | 2.66%   |
| Eizo                    | 5        | 2.66%   |
| NEX                     | 4        | 2.13%   |
| LG Electronics          | 4        | 2.13%   |
| Envision Peripherals    | 4        | 2.13%   |
| Vizio                   | 2        | 1.06%   |
| Unknown (XXX)           | 2        | 1.06%   |
| Sony                    | 2        | 1.06%   |
| AUS                     | 2        | 1.06%   |
| ___                     | 1        | 0.53%   |
| VIZ                     | 1        | 0.53%   |
| Toshiba                 | 1        | 0.53%   |
| Tatung                  | 1        | 0.53%   |
| NEC Computers           | 1        | 0.53%   |
| MSI                     | 1        | 0.53%   |
| KTC                     | 1        | 0.53%   |
| KEB                     | 1        | 0.53%   |
| GLE                     | 1        | 0.53%   |
| Chi Mei Optoelectronics | 1        | 0.53%   |
| Arnos Instruments       | 1        | 0.53%   |
| AMT International       | 1        | 0.53%   |
| Unknown                 | 1        | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch           | 5        | 2.6%    |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 4        | 2.08%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 3        | 1.56%   |
| Ancor Communications ASUS VS207 ACI20F2 1600x900 432x240mm 19.5-inch  | 3        | 1.56%   |
| ViewSonic VX2476 Series VSCD332 1920x1080 527x296mm 23.8-inch         | 2        | 1.04%   |
| ViewSonic VA916 Series VSC7C20 1280x1024 376x301mm 19.0-inch          | 2        | 1.04%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 1.04%   |
| Unknown LCD Monitor Kingston Technology 43 TV 1920x1080               | 2        | 1.04%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 2        | 1.04%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 2        | 1.04%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 2        | 1.04%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 1.04%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 1.04%   |
| Envision Peripherals LED H963wLs ENV1963 1366x768 410x230mm 18.5-inch | 2        | 1.04%   |
| Envision Peripherals LED 2271wh ENV2271 1920x1080 470x260mm 21.1-inch | 2        | 1.04%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                     | 2        | 1.04%   |
| BenQ GL2450H BNQ78A6 1920x1080 531x298mm 24.0-inch                    | 2        | 1.04%   |
| BenQ GC2870 BNQ78DD 1920x1080 621x341mm 27.9-inch                     | 2        | 1.04%   |
| BenQ EW2775ZH BNQ7944 1920x1080 598x336mm 27.0-inch                   | 2        | 1.04%   |
| BenQ EW2730V BNQ7931 1920x1080 597x336mm 27.0-inch                    | 2        | 1.04%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                     | 2        | 1.04%   |
| Ancor Communications ASUS VW247 ACI2496 1920x1080 531x299mm 24.0-inch | 2        | 1.04%   |
| Ancor Communications ASUS VW193S ACI19D4 1440x900 408x255mm 18.9-inch | 2        | 1.04%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                    | 2        | 1.04%   |
| ___ LCD Monitor ___0217 1920x1080 930x530mm 42.1-inch                 | 1        | 0.52%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1        | 0.52%   |
| Vizio M3D470KD VIZ0078 1920x1080 1039x584mm 46.9-inch                 | 1        | 0.52%   |
| VIZ LCD Monitor SV472XVT-T 1920x1080                                  | 1        | 0.52%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch         | 1        | 0.52%   |
| ViewSonic VE150 VSC5547 1024x768 304x228mm 15.0-inch                  | 1        | 0.52%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1        | 0.52%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch         | 1        | 0.52%   |
| ViewSonic LCD Monitor VX2270 SERIES 1920x1080                         | 1        | 0.52%   |
| ViewSonic LCD Monitor VSCC132 1920x1080 600x340mm 27.2-inch           | 1        | 0.52%   |
| ViewSonic LCD Monitor VSC732E 1920x1080 520x290mm 23.4-inch           | 1        | 0.52%   |
| ViewSonic LCD Monitor VSC692F 1920x1080 480x270mm 21.7-inch           | 1        | 0.52%   |
| Unknown LCD Monitor 0217 1920x1080 930x523mm 42.0-inch                | 1        | 0.52%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 0.52%   |
| Unknown (XXX) Beyond TV XXX2851 1920x1080 1209x680mm 54.6-inch        | 1        | 0.52%   |
| Toshiba IDTI_HDMI LCD2482 1920x1080 477x268mm 21.5-inch               | 1        | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 100      | 54.64%  |
| 2560x1440 (QHD)    | 17       | 9.29%   |
| 3840x2160 (4K)     | 10       | 5.46%   |
| 1366x768 (WXGA)    | 9        | 4.92%   |
| 1280x1024 (SXGA)   | 9        | 4.92%   |
| 1680x1050 (WSXGA+) | 8        | 4.37%   |
| 2560x1080          | 6        | 3.28%   |
| 1600x900 (HD+)     | 6        | 3.28%   |
| 1440x900 (WXGA+)   | 6        | 3.28%   |
| 1920x1200 (WUXGA)  | 4        | 2.19%   |
| 1024x768 (XGA)     | 2        | 1.09%   |
| Unknown            | 2        | 1.09%   |
| 3840x1080          | 1        | 0.55%   |
| 3440x1440          | 1        | 0.55%   |
| 1920x540           | 1        | 0.55%   |
| 1360x768           | 1        | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 29       | 15.51%  |
| Unknown | 28       | 14.97%  |
| 24      | 27       | 14.44%  |
| 21      | 27       | 14.44%  |
| 23      | 19       | 10.16%  |
| 19      | 19       | 10.16%  |
| 22      | 6        | 3.21%   |
| 34      | 5        | 2.67%   |
| 31      | 5        | 2.67%   |
| 18      | 5        | 2.67%   |
| 15      | 4        | 2.14%   |
| 54      | 2        | 1.07%   |
| 43      | 2        | 1.07%   |
| 17      | 2        | 1.07%   |
| 65      | 1        | 0.53%   |
| 46      | 1        | 0.53%   |
| 42      | 1        | 0.53%   |
| 41      | 1        | 0.53%   |
| 26      | 1        | 0.53%   |
| 25      | 1        | 0.53%   |
| 20      | 1        | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 67       | 37.02%  |
| 401-500     | 51       | 28.18%  |
| Unknown     | 28       | 15.47%  |
| 601-700     | 10       | 5.52%   |
| 351-400     | 6        | 3.31%   |
| 701-800     | 5        | 2.76%   |
| 301-350     | 5        | 2.76%   |
| 1001-1500   | 4        | 2.21%   |
| 901-1000    | 4        | 2.21%   |
| 201-300     | 1        | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 113      | 62.78%  |
| Unknown | 27       | 15%     |
| 16/10   | 23       | 12.78%  |
| 5/4     | 8        | 4.44%   |
| 21/9    | 5        | 2.78%   |
| 4/3     | 2        | 1.11%   |
| 6/5     | 1        | 0.56%   |
| 32/9    | 1        | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 63       | 34.05%  |
| 301-350        | 30       | 16.22%  |
| 151-200        | 28       | 15.14%  |
| Unknown        | 28       | 15.14%  |
| 351-500        | 10       | 5.41%   |
| 251-300        | 7        | 3.78%   |
| 141-150        | 7        | 3.78%   |
| 501-1000       | 5        | 2.7%    |
| More than 1000 | 3        | 1.62%   |
| 101-110        | 2        | 1.08%   |
| 121-130        | 1        | 0.54%   |
| 111-120        | 1        | 0.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 110      | 60.11%  |
| 101-120 | 35       | 19.13%  |
| Unknown | 28       | 15.3%   |
| 121-160 | 7        | 3.83%   |
| 1-50    | 3        | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 161      | 84.74%  |
| 0     | 15       | 7.89%   |
| 2     | 13       | 6.84%   |
| 3     | 1        | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 107      | 39.63%  |
| Intel                                  | 84       | 31.11%  |
| Qualcomm Atheros                       | 13       | 4.81%   |
| Ralink Technology                      | 9        | 3.33%   |
| Broadcom                               | 7        | 2.59%   |
| Aquantia                               | 7        | 2.59%   |
| MediaTek                               | 5        | 1.85%   |
| Edimax Technology                      | 5        | 1.85%   |
| HTC (High Tech Computer)               | 4        | 1.48%   |
| Nvidia                                 | 3        | 1.11%   |
| ASUSTek Computer                       | 3        | 1.11%   |
| TP-Link                                | 2        | 0.74%   |
| Marvell Technology Group               | 2        | 0.74%   |
| ZyXEL Communications                   | 1        | 0.37%   |
| SparkFun                               | 1        | 0.37%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.37%   |
| Samsung Electronics                    | 1        | 0.37%   |
| Ralink                                 | 1        | 0.37%   |
| Prolific Technology                    | 1        | 0.37%   |
| OPPO Electronics                       | 1        | 0.37%   |
| Microsoft                              | 1        | 0.37%   |
| Mercucys                               | 1        | 0.37%   |
| IBM                                    | 1        | 0.37%   |
| Huawei Technologies                    | 1        | 0.37%   |
| Google                                 | 1        | 0.37%   |
| D-Link System                          | 1        | 0.37%   |
| D-Link                                 | 1        | 0.37%   |
| BUFFALO                                | 1        | 0.37%   |
| Arduino SA                             | 1        | 0.37%   |
| Apple                                  | 1        | 0.37%   |
| Accton Technology                      | 1        | 0.37%   |
| 3Com                                   | 1        | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 88       | 28.66%  |
| Intel I211 Gigabit Network Connection                               | 17       | 5.54%   |
| Intel Ethernet Controller I225-V                                    | 12       | 3.91%   |
| Realtek RTL8125 2.5GbE Controller                                   | 11       | 3.58%   |
| Intel Wi-Fi 6 AX200                                                 | 11       | 3.58%   |
| Ralink MT7601U Wireless Adapter                                     | 7        | 2.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 7        | 2.28%   |
| Intel Wireless-AC 9260                                              | 6        | 1.95%   |
| Intel I210 Gigabit Network Connection                               | 5        | 1.63%   |
| Intel Ethernet Connection (7) I219-V                                | 5        | 1.63%   |
| Intel Ethernet Connection (2) I219-V                                | 5        | 1.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 5        | 1.63%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 5        | 1.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 4        | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 4        | 1.3%    |
| Intel Ethernet Connection I217-V                                    | 4        | 1.3%    |
| Intel Ethernet Connection I217-LM                                   | 4        | 1.3%    |
| HTC (High Tech Computer) Desire HD (modem mode)                     | 4        | 1.3%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]      | 4        | 1.3%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                          | 3        | 0.98%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 3        | 0.98%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2        | 0.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 0.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 2        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.65%   |
| Nvidia MCP61 Ethernet                                               | 2        | 0.65%   |
| Intel Wireless 8265 / 8275                                          | 2        | 0.65%   |
| Intel Wireless 3165                                                 | 2        | 0.65%   |
| Intel I350 Gigabit Network Connection                               | 2        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                               | 2        | 0.65%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.65%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 2        | 0.65%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 2        | 0.65%   |
| Intel 82579V Gigabit Network Connection                             | 2        | 0.65%   |
| ASUS 802.11ac NIC                                                   | 2        | 0.65%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.65%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]        | 1        | 0.33%   |
| TP-Link USB 10/100 LAN                                              | 1        | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 39       | 46.99%  |
| Ralink Technology     | 9        | 10.84%  |
| Realtek Semiconductor | 8        | 9.64%   |
| MediaTek              | 5        | 6.02%   |
| Edimax Technology     | 5        | 6.02%   |
| Broadcom              | 3        | 3.61%   |
| ASUSTek Computer      | 3        | 3.61%   |
| Qualcomm Atheros      | 2        | 2.41%   |
| ZyXEL Communications  | 1        | 1.2%    |
| TP-Link               | 1        | 1.2%    |
| Ralink                | 1        | 1.2%    |
| Microsoft             | 1        | 1.2%    |
| Mercucys              | 1        | 1.2%    |
| D-Link System         | 1        | 1.2%    |
| D-Link                | 1        | 1.2%    |
| BUFFALO               | 1        | 1.2%    |
| Accton Technology     | 1        | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 11       | 13.1%   |
| Ralink MT7601U Wireless Adapter                                         | 7        | 8.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7        | 8.33%   |
| Intel Wireless-AC 9260                                                  | 6        | 7.14%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4        | 4.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4        | 4.76%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 4        | 4.76%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 3        | 3.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2        | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2        | 2.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2        | 2.38%   |
| Intel Wireless 8265 / 8275                                              | 2        | 2.38%   |
| Intel Wireless 3165                                                     | 2        | 2.38%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2        | 2.38%   |
| ASUS 802.11ac NIC                                                       | 2        | 2.38%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]            | 1        | 1.19%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1        | 1.19%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1        | 1.19%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1        | 1.19%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1        | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 1.19%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1        | 1.19%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 1.19%   |
| Mercucys 802.11n NIC                                                    | 1        | 1.19%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                      | 1        | 1.19%   |
| Intel Wireless 8260                                                     | 1        | 1.19%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1        | 1.19%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1        | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1        | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 1.19%   |
| Edimax AC1200 MU-MIMO USB2.0 Adapter                                    | 1        | 1.19%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]    | 1        | 1.19%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 1.19%   |
| BUFFALO WLI-UC-GN Wireless LAN Adapter [Ralink RT3070]                  | 1        | 1.19%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1        | 1.19%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1        | 1.19%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1        | 1.19%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 1        | 1.19%   |
| Accton SMCWUSB-G 802.11bg                                               | 1        | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 102      | 50%     |
| Intel                    | 67       | 32.84%  |
| Qualcomm Atheros         | 11       | 5.39%   |
| Aquantia                 | 7        | 3.43%   |
| Broadcom                 | 4        | 1.96%   |
| Nvidia                   | 3        | 1.47%   |
| Marvell Technology Group | 2        | 0.98%   |
| TP-Link                  | 1        | 0.49%   |
| Samsung Electronics      | 1        | 0.49%   |
| OPPO Electronics         | 1        | 0.49%   |
| IBM                      | 1        | 0.49%   |
| Huawei Technologies      | 1        | 0.49%   |
| Google                   | 1        | 0.49%   |
| Apple                    | 1        | 0.49%   |
| 3Com                     | 1        | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 88       | 40.93%  |
| Intel I211 Gigabit Network Connection                               | 17       | 7.91%   |
| Intel Ethernet Controller I225-V                                    | 12       | 5.58%   |
| Realtek RTL8125 2.5GbE Controller                                   | 11       | 5.12%   |
| Intel I210 Gigabit Network Connection                               | 5        | 2.33%   |
| Intel Ethernet Connection (7) I219-V                                | 5        | 2.33%   |
| Intel Ethernet Connection (2) I219-V                                | 5        | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 5        | 2.33%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 5        | 2.33%   |
| Intel Ethernet Connection I217-V                                    | 4        | 1.86%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 1.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 3        | 1.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.93%   |
| Nvidia MCP61 Ethernet                                               | 2        | 0.93%   |
| Intel I350 Gigabit Network Connection                               | 2        | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                               | 2        | 0.93%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.93%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 2        | 0.93%   |
| Intel 82579V Gigabit Network Connection                             | 2        | 0.93%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.93%   |
| TP-Link USB 10/100 LAN                                              | 1        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 1        | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1        | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                               | 1        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 1        | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.47%   |
| OPPO RMX2180                                                        | 1        | 0.47%   |
| Nvidia MCP65 Ethernet                                               | 1        | 0.47%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller             | 1        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.47%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                   | 1        | 0.47%   |
| Intel Ethernet Controller X550                                      | 1        | 0.47%   |
| Intel Ethernet Connection X552 10 GbE SFP+                          | 1        | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                               | 1        | 0.47%   |
| Intel Ethernet Connection (17) I219-V                               | 1        | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 181      | 67.54%  |
| WiFi     | 79       | 29.48%  |
| Modem    | 7        | 2.61%   |
| Unknown  | 1        | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 144      | 75.79%  |
| WiFi     | 43       | 22.63%  |
| Modem    | 2        | 1.05%   |
| Unknown  | 1        | 0.53%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 102      | 54.55%  |
| 2     | 64       | 34.22%  |
| 3     | 9        | 4.81%   |
| 0     | 8        | 4.28%   |
| 6     | 2        | 1.07%   |
| 10    | 1        | 0.53%   |
| 4     | 1        | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 169      | 88.95%  |
| Yes  | 21       | 11.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 38       | 57.58%  |
| Cambridge Silicon Radio | 12       | 18.18%  |
| MediaTek                | 4        | 6.06%   |
| Realtek Semiconductor   | 3        | 4.55%   |
| Broadcom                | 3        | 4.55%   |
| IMC Networks            | 2        | 3.03%   |
| ASUSTek Computer        | 2        | 3.03%   |
| Ralink                  | 1        | 1.52%   |
| Apple                   | 1        | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 12       | 18.18%  |
| Intel AX200 Bluetooth                                 | 11       | 16.67%  |
| Intel Wireless-AC 3168 Bluetooth                      | 7        | 10.61%  |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 6        | 9.09%   |
| Intel Bluetooth wireless interface                    | 5        | 7.58%   |
| MediaTek Wireless_Device                              | 4        | 6.06%   |
| Intel AX210 Bluetooth                                 | 4        | 6.06%   |
| Intel AX201 Bluetooth                                 | 4        | 6.06%   |
| Realtek Bluetooth Radio                               | 2        | 3.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 1.52%   |
| Ralink RT3290 Bluetooth                               | 1        | 1.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 1.52%   |
| IMC Networks Bluetooth Device                         | 1        | 1.52%   |
| IMC Networks BCM20702A0                               | 1        | 1.52%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 1.52%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.52%   |
| ASUS Bluetooth Radio                                  | 1        | 1.52%   |
| Apple Bluetooth USB Host Controller                   | 1        | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 121      | 40.47%  |
| Nvidia                               | 80       | 26.76%  |
| AMD                                  | 66       | 22.07%  |
| C-Media Electronics                  | 4        | 1.34%   |
| ASUSTek Computer                     | 4        | 1.34%   |
| Generalplus Technology               | 3        | 1%      |
| Texas Instruments                    | 2        | 0.67%   |
| SAVITECH                             | 2        | 0.67%   |
| Focusrite-Novation                   | 2        | 0.67%   |
| Audio-Technica                       | 2        | 0.67%   |
| ZOOM                                 | 1        | 0.33%   |
| Yamaha                               | 1        | 0.33%   |
| XMOS                                 | 1        | 0.33%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.33%   |
| Sony                                 | 1        | 0.33%   |
| Novra/IDC/Wegener                    | 1        | 0.33%   |
| Micro Star International             | 1        | 0.33%   |
| Logitech                             | 1        | 0.33%   |
| GN Netcom                            | 1        | 0.33%   |
| Elite Silicon                        | 1        | 0.33%   |
| Dell                                 | 1        | 0.33%   |
| Creative Technology                  | 1        | 0.33%   |
| Creative Labs                        | 1        | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22       | 6.51%   |
| AMD Starship/Matisse HD Audio Controller                                   | 18       | 5.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16       | 4.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 4.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14       | 4.14%   |
| Nvidia GP106 High Definition Audio Controller                              | 11       | 3.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 11       | 3.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10       | 2.96%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10       | 2.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 2.96%   |
| Nvidia GP108 High Definition Audio Controller                              | 7        | 2.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 2.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7        | 2.07%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 2.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 2.07%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6        | 1.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 1.78%   |
| Nvidia MCP61 High Definition Audio                                         | 5        | 1.48%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 1.48%   |
| Nvidia GF116 High Definition Audio Controller                              | 5        | 1.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 1.48%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 1.48%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.18%   |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 1.18%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4        | 1.18%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 1.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 1.18%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.18%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.18%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 0.89%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.89%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 0.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.89%   |
| Generalplus Technology USB Audio Device                                    | 3        | 0.89%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 0.89%   |
| AMD FCH Azalia Controller                                                  | 3        | 0.89%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 20       | 19.23%  |
| Kingston            | 17       | 16.35%  |
| Unknown             | 12       | 11.54%  |
| Transcend           | 12       | 11.54%  |
| A-DATA Technology   | 9        | 8.65%   |
| Micron Technology   | 8        | 7.69%   |
| SK hynix            | 6        | 5.77%   |
| Samsung Electronics | 3        | 2.88%   |
| G.Skill             | 3        | 2.88%   |
| Unifosa             | 2        | 1.92%   |
| Team                | 2        | 1.92%   |
| V-Color             | 1        | 0.96%   |
| UMAX                | 1        | 0.96%   |
| Silicon Power       | 1        | 0.96%   |
| Ramaxel Technology  | 1        | 0.96%   |
| Patriot             | 1        | 0.96%   |
| KLEVV               | 1        | 0.96%   |
| CUSO                | 1        | 0.96%   |
| ASint Technology    | 1        | 0.96%   |
| Apacer              | 1        | 0.96%   |
| Unknown             | 1        | 0.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Transcend RAM TS1GLK64V6H 8192MB DIMM DDR3 1600MT/s      | 3        | 2.65%   |
| A-DATA RAM Module 4096MB SODIMM DDR4 2400MT/s            | 3        | 2.65%   |
| A-DATA RAM DDR4 3000 2OZ 8GB DIMM DDR4 3000MT/s          | 3        | 2.65%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s        | 2        | 1.77%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 1.77%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 2        | 1.77%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s   | 2        | 1.77%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s     | 2        | 1.77%   |
| V-Color RAM TD4G8C11-H11 4GB DIMM DDR3 1600MT/s          | 1        | 0.88%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.88%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 0.88%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 1        | 0.88%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.88%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 1        | 0.88%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                     | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 1        | 0.88%   |
| Unknown RAM Module 1GB DIMM 533MT/s                      | 1        | 0.88%   |
| Unknown RAM Module 16GB SODIMM DDR4 2400MT/s             | 1        | 0.88%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2400MT/s          | 1        | 0.88%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s            | 1        | 0.88%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 0.88%   |
| Unifosa RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 0.88%   |
| UMAX RAM D4-3200-16G-2048X8-L 16384MB DIMM DDR4 3200MT/s | 1        | 0.88%   |
| Transcend RAM TX2400KLN-8GK 4096MB DIMM DDR3 1600MT/s    | 1        | 0.88%   |
| Transcend RAM TX2133KLN-8GK 4096MB DIMM DDR3 2000MT/s    | 1        | 0.88%   |
| Transcend RAM TS512MLK72V6N 4GB DIMM DDR3 1600MT/s       | 1        | 0.88%   |
| Transcend RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 0.88%   |
| Transcend RAM JM1600KLN-4G 4096MB DIMM DDR3 1600MT/s     | 1        | 0.88%   |
| Transcend RAM JM1600KLH-8G 8GB DIMM DDR3 1600MT/s        | 1        | 0.88%   |
| Transcend RAM JM1600KLH-16GK 8192MB DIMM DDR3 1600MT/s   | 1        | 0.88%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s      | 1        | 0.88%   |
| Team RAM TEAMGROUP-UD4-2666 16384MB DIMM DDR4 3000MT/s   | 1        | 0.88%   |
| SK hynix RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 0.88%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1600MT/s            | 1        | 0.88%   |
| SK hynix RAM HMT451U7BFR8C-RD 4GB DIMM DDR3 1333MT/s     | 1        | 0.88%   |
| SK hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.88%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 53       | 57.61%  |
| DDR3    | 28       | 30.43%  |
| Unknown | 6        | 6.52%   |
| DDR2    | 3        | 3.26%   |
| DDR5    | 1        | 1.09%   |
| DDR     | 1        | 1.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 82       | 89.13%  |
| SODIMM | 10       | 10.87%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 35       | 36.46%  |
| 16384 | 29       | 30.21%  |
| 4096  | 18       | 18.75%  |
| 2048  | 8        | 8.33%   |
| 32768 | 4        | 4.17%   |
| 1024  | 2        | 2.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 26       | 25.49%  |
| 3200  | 16       | 15.69%  |
| 2667  | 8        | 7.84%   |
| 2400  | 8        | 7.84%   |
| 1333  | 7        | 6.86%   |
| 2133  | 6        | 5.88%   |
| 3000  | 5        | 4.9%    |
| 3733  | 3        | 2.94%   |
| 3600  | 3        | 2.94%   |
| 667   | 3        | 2.94%   |
| 4800  | 2        | 1.96%   |
| 2933  | 2        | 1.96%   |
| 2666  | 2        | 1.96%   |
| 4000  | 1        | 0.98%   |
| 3866  | 1        | 0.98%   |
| 3466  | 1        | 0.98%   |
| 3334  | 1        | 0.98%   |
| 3134  | 1        | 0.98%   |
| 2866  | 1        | 0.98%   |
| 2000  | 1        | 0.98%   |
| 1066  | 1        | 0.98%   |
| 800   | 1        | 0.98%   |
| 533   | 1        | 0.98%   |
| 400   | 1        | 0.98%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 75%     |
| Seiko Epson     | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson XP-243 245 247 Series | 1        | 25%     |
| HP LaserJet Professional P1102w   | 1        | 25%     |
| HP LaserJet Professional P 1102w  | 1        | 25%     |
| HP LaserJet 1020                  | 1        | 25%     |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 11       | 73.33%  |
| Sunplus Innovation Technology | 1        | 6.67%   |
| KYE Systems (Mouse Systems)   | 1        | 6.67%   |
| Apple                         | 1        | 6.67%   |
| A4Tech                        | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 3        | 20%     |
| Logitech Webcam C120                            | 3        | 20%     |
| Sunplus ezcap U3 capture-04                     | 1        | 6.67%   |
| Logitech Webcam C930e                           | 1        | 6.67%   |
| Logitech Webcam C170                            | 1        | 6.67%   |
| Logitech QuickCam Home                          | 1        | 6.67%   |
| Logitech QuickCam E 3500                        | 1        | 6.67%   |
| Logitech HD Pro Webcam C920                     | 1        | 6.67%   |
| KYE Systems (Mouse Systems) Genius WideCam F100 | 1        | 6.67%   |
| Apple iPhone 5/5C/5S/6/SE                       | 1        | 6.67%   |
| A4Tech FHD 1080P PC Camera                      | 1        | 6.67%   |

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
| 0     | 153      | 80.1%   |
| 1     | 31       | 16.23%  |
| 2     | 3        | 1.57%   |
| 3     | 2        | 1.05%   |
| 5     | 1        | 0.52%   |
| 4     | 1        | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 17       | 39.53%  |
| Unassigned class         | 7        | 16.28%  |
| Communication controller | 5        | 11.63%  |
| Net/wireless             | 3        | 6.98%   |
| Card reader              | 3        | 6.98%   |
| Sound                    | 2        | 4.65%   |
| Bluetooth                | 2        | 4.65%   |
| Storage/raid             | 1        | 2.33%   |
| Network                  | 1        | 2.33%   |
| Net/ethernet             | 1        | 2.33%   |
| Camera                   | 1        | 2.33%   |

