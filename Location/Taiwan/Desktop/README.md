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

Total: 513

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkCentre M90 5474AE9     | [5fb2a43c33](https://linux-hardware.org/?probe=5fb2a43c33) | Dec 31, 2025 |
| ASUSTek       | Pro H610M-C                 | [3e9c303fb2](https://linux-hardware.org/?probe=3e9c303fb2) | Dec 30, 2025 |
| Lenovo        | ThinkCentre M90 5474AE9     | [888b8ba895](https://linux-hardware.org/?probe=888b8ba895) | Dec 25, 2025 |
| OEM           | PB-1900-A                   | [495d273691](https://linux-hardware.org/?probe=495d273691) | Dec 18, 2025 |
| MSI           | MS-B0A91                    | [25d69e44da](https://linux-hardware.org/?probe=25d69e44da) | Dec 12, 2025 |
| MSI           | B450M MORTAR MAX            | [46702f2299](https://linux-hardware.org/?probe=46702f2299) | Dec 10, 2025 |
| MSI           | PRO H610M-E DDR4            | [7cc05e8413](https://linux-hardware.org/?probe=7cc05e8413) | Dec 07, 2025 |
| Gigabyte      | Z97MX-Gaming 5              | [0867935d51](https://linux-hardware.org/?probe=0867935d51) | Nov 22, 2025 |
| Gigabyte      | Z97MX-Gaming 5              | [3448eb22e1](https://linux-hardware.org/?probe=3448eb22e1) | Nov 22, 2025 |
| ASUSTek       | Z170M-PLUS                  | [feba3de312](https://linux-hardware.org/?probe=feba3de312) | Nov 21, 2025 |
| ASUSTek       | Z170M-PLUS                  | [528fd43f7f](https://linux-hardware.org/?probe=528fd43f7f) | Nov 17, 2025 |
| MSI           | MS-B0A91                    | [27dae67dfa](https://linux-hardware.org/?probe=27dae67dfa) | Nov 06, 2025 |
| ASUSTek       | PRIME B650M-K               | [b843e7ab4e](https://linux-hardware.org/?probe=b843e7ab4e) | Oct 31, 2025 |
| ASUSTek       | F2A85-M                     | [32a5190340](https://linux-hardware.org/?probe=32a5190340) | Oct 21, 2025 |
| AZW           | EQ                          | [e3bbac8ecd](https://linux-hardware.org/?probe=e3bbac8ecd) | Oct 17, 2025 |
| Intel         | ADL-F10                     | [5421ddd946](https://linux-hardware.org/?probe=5421ddd946) | Oct 14, 2025 |
| ASUSTek       | P5K-E                       | [78ec0abf04](https://linux-hardware.org/?probe=78ec0abf04) | Oct 12, 2025 |
| ASUSTek       | PRIME A520M-K               | [138f614e7a](https://linux-hardware.org/?probe=138f614e7a) | Oct 12, 2025 |
| ASUSTek       | ProArt Z790-CREATOR WIFI    | [dbdc8fabd0](https://linux-hardware.org/?probe=dbdc8fabd0) | Sep 26, 2025 |
| ASUSTek       | P8B75-M                     | [5c24cc8dab](https://linux-hardware.org/?probe=5c24cc8dab) | Sep 26, 2025 |
| HC Technol... | HCAR6000-MI2                | [e77956cff8](https://linux-hardware.org/?probe=e77956cff8) | Sep 25, 2025 |
| Gigabyte      | B75M-D3H                    | [301e25532a](https://linux-hardware.org/?probe=301e25532a) | Sep 23, 2025 |
| ASUSTek       | PRIME A520M-K               | [0e05567765](https://linux-hardware.org/?probe=0e05567765) | Sep 09, 2025 |
| HP            | 21D0                        | [288d8697c8](https://linux-hardware.org/?probe=288d8697c8) | Sep 05, 2025 |
| ASUSTek       | PRIME B360M-A               | [6e350f18cb](https://linux-hardware.org/?probe=6e350f18cb) | Sep 01, 2025 |
| Gigabyte      | X670E AORUS MASTER          | [ae0eb5ba93](https://linux-hardware.org/?probe=ae0eb5ba93) | Aug 19, 2025 |
| Unknown       | Unknown                     | [b312736120](https://linux-hardware.org/?probe=b312736120) | Aug 13, 2025 |
| Gigabyte      | B660M D2H DDR4              | [6f29ad608f](https://linux-hardware.org/?probe=6f29ad608f) | Jul 18, 2025 |
| Gigabyte      | B850 AORUS ELITE WIFI7      | [1b333ab690](https://linux-hardware.org/?probe=1b333ab690) | Jul 17, 2025 |
| HP            | 83EF                        | [da37391138](https://linux-hardware.org/?probe=da37391138) | Jul 16, 2025 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [486d440aea](https://linux-hardware.org/?probe=486d440aea) | Jul 06, 2025 |
| HP            | 895C                        | [75cba3aaae](https://linux-hardware.org/?probe=75cba3aaae) | Jul 05, 2025 |
| Gigabyte      | B850 AORUS ELITE WIFI7      | [47e1d567d6](https://linux-hardware.org/?probe=47e1d567d6) | Jul 03, 2025 |
| Dell          | 03X0YG A00                  | [217535d3a1](https://linux-hardware.org/?probe=217535d3a1) | Jun 29, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [c4083c7539](https://linux-hardware.org/?probe=c4083c7539) | Jun 18, 2025 |
| Acer          | Aspire M1470                | [dfbd4e48f4](https://linux-hardware.org/?probe=dfbd4e48f4) | Jun 11, 2025 |
| Gigabyte      | TRX50 AI TOP                | [7b0c722a8c](https://linux-hardware.org/?probe=7b0c722a8c) | May 18, 2025 |
| Gigabyte      | TRX50 AI TOP                | [92c68148a5](https://linux-hardware.org/?probe=92c68148a5) | May 18, 2025 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [0805bc99b8](https://linux-hardware.org/?probe=0805bc99b8) | May 17, 2025 |
| Huanan        | B85                         | [5d1cb73604](https://linux-hardware.org/?probe=5d1cb73604) | May 14, 2025 |
| Red Hat       | RHEL RHEL-9.4.0 PC          | [2993f98162](https://linux-hardware.org/?probe=2993f98162) | May 03, 2025 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [580e4b4766](https://linux-hardware.org/?probe=580e4b4766) | May 03, 2025 |
| Gigabyte      | Z77M-D3H                    | [1788881b72](https://linux-hardware.org/?probe=1788881b72) | Apr 28, 2025 |
| ASRock        | B660M-STX                   | [d177db2a83](https://linux-hardware.org/?probe=d177db2a83) | Apr 27, 2025 |
| ASRock        | X79 Champion                | [cd9df643eb](https://linux-hardware.org/?probe=cd9df643eb) | Apr 14, 2025 |
| ASUSTek       | BM6630_BM6330_BP6230        | [7661e69618](https://linux-hardware.org/?probe=7661e69618) | Apr 09, 2025 |
| MSI           | MPG Z790 EDGE TI MAX WIF... | [8e6702b5d9](https://linux-hardware.org/?probe=8e6702b5d9) | Apr 06, 2025 |
| Gigabyte      | Z77M-D3H                    | [edf5cb6673](https://linux-hardware.org/?probe=edf5cb6673) | Mar 27, 2025 |
| Gigabyte      | B650M AORUS ELITE AX ICE    | [64e8a92518](https://linux-hardware.org/?probe=64e8a92518) | Mar 20, 2025 |
| MSI           | B550M PRO-VDH WIFI          | [8c43862415](https://linux-hardware.org/?probe=8c43862415) | Mar 18, 2025 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [86be6255cb](https://linux-hardware.org/?probe=86be6255cb) | Mar 09, 2025 |
| ASRock        | X79 Champion                | [9970f3187a](https://linux-hardware.org/?probe=9970f3187a) | Mar 03, 2025 |
| Intel         | SHARKBAY                    | [0129a78b8a](https://linux-hardware.org/?probe=0129a78b8a) | Mar 02, 2025 |
| ASRock        | X79 Champion                | [e60f60a23e](https://linux-hardware.org/?probe=e60f60a23e) | Mar 01, 2025 |
| Standard      | EL Series                   | [579196360c](https://linux-hardware.org/?probe=579196360c) | Feb 26, 2025 |
| ASRock        | A320M-HDV R4.0              | [fba7f06d5d](https://linux-hardware.org/?probe=fba7f06d5d) | Feb 24, 2025 |
| Gigabyte      | B550M DS3H AC               | [94f74377db](https://linux-hardware.org/?probe=94f74377db) | Feb 18, 2025 |
| MSI           | MPG X570 GAMING PRO CARB... | [130989a3cc](https://linux-hardware.org/?probe=130989a3cc) | Feb 12, 2025 |
| Dell          | 0NK5PH A00                  | [ec5ece324f](https://linux-hardware.org/?probe=ec5ece324f) | Feb 06, 2025 |
| AURES         | 7300X7D2 04                 | [c63acad854](https://linux-hardware.org/?probe=c63acad854) | Jan 24, 2025 |
| Gigabyte      | H81N                        | [edbcbf2d92](https://linux-hardware.org/?probe=edbcbf2d92) | Jan 22, 2025 |
| Gigabyte      | H81N                        | [052bbd961d](https://linux-hardware.org/?probe=052bbd961d) | Jan 20, 2025 |
| ASUSTek       | PRIME A520M-K               | [b03b54b323](https://linux-hardware.org/?probe=b03b54b323) | Jan 18, 2025 |
| ASUSTek       | PRIME A520M-K               | [7149a4eec1](https://linux-hardware.org/?probe=7149a4eec1) | Jan 15, 2025 |
| Unknown       | Unknown                     | [2c69d75780](https://linux-hardware.org/?probe=2c69d75780) | Jan 08, 2025 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | [f01c6a5473](https://linux-hardware.org/?probe=f01c6a5473) | Jan 08, 2025 |
| Unknown       | Unknown                     | [52f6250403](https://linux-hardware.org/?probe=52f6250403) | Jan 08, 2025 |
| Dell          | 04Y8V0 A02                  | [2864d95f71](https://linux-hardware.org/?probe=2864d95f71) | Jan 01, 2025 |
| Dell          | 04Y8V0 A02                  | [dd5b8644a1](https://linux-hardware.org/?probe=dd5b8644a1) | Jan 01, 2025 |
| Gigabyte      | X570 AORUS ULTRA            | [8b12a21b9a](https://linux-hardware.org/?probe=8b12a21b9a) | Dec 31, 2024 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [a4872cd0ec](https://linux-hardware.org/?probe=a4872cd0ec) | Dec 27, 2024 |
| MSI           | A78M-E35 V2                 | [37ed0bfc1f](https://linux-hardware.org/?probe=37ed0bfc1f) | Dec 24, 2024 |
| ASUSTek       | PRIME Z390M-PLUS            | [da6ad47fac](https://linux-hardware.org/?probe=da6ad47fac) | Dec 23, 2024 |
| ASUSTek       | PRIME Z390M-PLUS            | [0a0b737503](https://linux-hardware.org/?probe=0a0b737503) | Dec 23, 2024 |
| ASUSTek       | BM6660                      | [6a96fbe6fb](https://linux-hardware.org/?probe=6a96fbe6fb) | Dec 21, 2024 |
| Acer          | A Power T200                | [c3aefafdb9](https://linux-hardware.org/?probe=c3aefafdb9) | Dec 14, 2024 |
| JGINYUE       | X99-8D4G Server             | [9d7190d871](https://linux-hardware.org/?probe=9d7190d871) | Dec 10, 2024 |
| Tianbei       | GEM12                       | [a9116936ae](https://linux-hardware.org/?probe=a9116936ae) | Nov 29, 2024 |
| Acer          | A Power T200                | [5cb8f1ede1](https://linux-hardware.org/?probe=5cb8f1ede1) | Nov 27, 2024 |
| Acer          | A Power T200                | [c34c318d09](https://linux-hardware.org/?probe=c34c318d09) | Nov 18, 2024 |
| Gigabyte      | Z170X-Gaming 5              | [ac49d10d4b](https://linux-hardware.org/?probe=ac49d10d4b) | Nov 08, 2024 |
| ASUSTek       | BM5295                      | [0e8c2a71ad](https://linux-hardware.org/?probe=0e8c2a71ad) | Nov 03, 2024 |
| ASUSTek       | UN62                        | [8a9a9a8a39](https://linux-hardware.org/?probe=8a9a9a8a39) | Oct 25, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [8a56d14426](https://linux-hardware.org/?probe=8a56d14426) | Oct 16, 2024 |
| MSI           | Z370 GAMING PRO CARBON      | [3143d75e4c](https://linux-hardware.org/?probe=3143d75e4c) | Oct 15, 2024 |
| MSI           | Z370 GAMING PRO CARBON      | [0c3c722b3e](https://linux-hardware.org/?probe=0c3c722b3e) | Oct 15, 2024 |
| Gigabyte      | H67M-D2-B3                  | [126c347ac7](https://linux-hardware.org/?probe=126c347ac7) | Sep 19, 2024 |
| Dell          | 0NW73C A00                  | [b9955b6aed](https://linux-hardware.org/?probe=b9955b6aed) | Sep 10, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [79ffedea38](https://linux-hardware.org/?probe=79ffedea38) | Jul 25, 2024 |
| Gigabyte      | MJPLNCB-00                  | [ade57b33b2](https://linux-hardware.org/?probe=ade57b33b2) | Jul 24, 2024 |
| Gigabyte      | MJPLNCB-00                  | [083b19f9d8](https://linux-hardware.org/?probe=083b19f9d8) | Jul 24, 2024 |
| Acer          | Veriton M6620G v1.0         | [24727969e0](https://linux-hardware.org/?probe=24727969e0) | Jul 22, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [dcb993f549](https://linux-hardware.org/?probe=dcb993f549) | Jul 05, 2024 |
| HP            | 2129                        | [5f6c1730b6](https://linux-hardware.org/?probe=5f6c1730b6) | Jul 05, 2024 |
| MSI           | PRO Z790-A WIFI             | [52e9dbfb7d](https://linux-hardware.org/?probe=52e9dbfb7d) | Jul 01, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [7e0f424897](https://linux-hardware.org/?probe=7e0f424897) | Jun 30, 2024 |
| Gigabyte      | MJPLNCB-00                  | [3674335450](https://linux-hardware.org/?probe=3674335450) | Jun 13, 2024 |
| HP            | 21D0                        | [1d1b18c4a7](https://linux-hardware.org/?probe=1d1b18c4a7) | Jun 12, 2024 |
| MSI           | PRO Z790-A WIFI             | [5df0be9868](https://linux-hardware.org/?probe=5df0be9868) | Jun 12, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [3ef05260af](https://linux-hardware.org/?probe=3ef05260af) | Jun 08, 2024 |
| Gigabyte      | MJPLNCB-00                  | [1b40f81d23](https://linux-hardware.org/?probe=1b40f81d23) | Jun 05, 2024 |
| HP            | 870B                        | [a1ea4b1730](https://linux-hardware.org/?probe=a1ea4b1730) | May 22, 2024 |
| HP            | 870B                        | [10cd820ee4](https://linux-hardware.org/?probe=10cd820ee4) | May 22, 2024 |
| ASRock        | X300M-STX                   | [df3903c990](https://linux-hardware.org/?probe=df3903c990) | May 18, 2024 |
| Huanan        | X99-TF V3.0 JX              | [bb51640f19](https://linux-hardware.org/?probe=bb51640f19) | Apr 21, 2024 |
| ASUSTek       | H170M-PLUS                  | [36ed031c7f](https://linux-hardware.org/?probe=36ed031c7f) | Apr 17, 2024 |
| ASUSTek       | WS C422 PRO_SE              | [f4279202a4](https://linux-hardware.org/?probe=f4279202a4) | Apr 12, 2024 |
| Lenovo        | 36C5 SDK0L77767 WIN 3423... | [79cb6ea23b](https://linux-hardware.org/?probe=79cb6ea23b) | Apr 10, 2024 |
| Gigabyte      | GA-H61TN-SI                 | [3f6b496eb7](https://linux-hardware.org/?probe=3f6b496eb7) | Apr 02, 2024 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [d1554bd2c0](https://linux-hardware.org/?probe=d1554bd2c0) | Apr 01, 2024 |
| JGINYUE       | X99M-PLUS D4 V3.1           | [e44ab52f45](https://linux-hardware.org/?probe=e44ab52f45) | Mar 29, 2024 |
| ASUSTek       | PRIME B560M-K               | [75a6f1b690](https://linux-hardware.org/?probe=75a6f1b690) | Mar 29, 2024 |
| Gigabyte      | GA-770TA-UD3                | [2b6ed8b07a](https://linux-hardware.org/?probe=2b6ed8b07a) | Mar 26, 2024 |
| Gigabyte      | GA-770TA-UD3                | [04474844f0](https://linux-hardware.org/?probe=04474844f0) | Mar 26, 2024 |
| ASRock        | X300M-STX                   | [41f3f09405](https://linux-hardware.org/?probe=41f3f09405) | Mar 23, 2024 |
| JGINYUE       | X99 TITANIUM D3             | [4ba18d3790](https://linux-hardware.org/?probe=4ba18d3790) | Mar 22, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [fe713b8d04](https://linux-hardware.org/?probe=fe713b8d04) | Mar 21, 2024 |
| MSI           | H110M PRO-VD                | [29f63e63c9](https://linux-hardware.org/?probe=29f63e63c9) | Mar 16, 2024 |
| EBN           | MA1N                        | [03917cfce5](https://linux-hardware.org/?probe=03917cfce5) | Mar 06, 2024 |
| OEM           | B85 JHS359                  | [30c44600e2](https://linux-hardware.org/?probe=30c44600e2) | Mar 06, 2024 |
| Huanan        | B85                         | [22ee4d4c6d](https://linux-hardware.org/?probe=22ee4d4c6d) | Mar 05, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [a4297d40d4](https://linux-hardware.org/?probe=a4297d40d4) | Feb 13, 2024 |
| Centerm       | C92                         | [5b7b85d16b](https://linux-hardware.org/?probe=5b7b85d16b) | Feb 03, 2024 |
| EBN           | MA1N                        | [302ea43954](https://linux-hardware.org/?probe=302ea43954) | Feb 01, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | [276a0b5785](https://linux-hardware.org/?probe=276a0b5785) | Jan 19, 2024 |
| Unknown       | Unknown                     | [1c86716af5](https://linux-hardware.org/?probe=1c86716af5) | Jan 15, 2024 |
| Unknown       | Unknown                     | [5e8d8eb89f](https://linux-hardware.org/?probe=5e8d8eb89f) | Jan 15, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [537c95bdae](https://linux-hardware.org/?probe=537c95bdae) | Jan 11, 2024 |
| Gigabyte      | Z77M-D3H                    | [d20dfe448d](https://linux-hardware.org/?probe=d20dfe448d) | Jan 06, 2024 |
| ASRock        | X300M-STX                   | [a9f024df00](https://linux-hardware.org/?probe=a9f024df00) | Jan 03, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [ca2b52b64f](https://linux-hardware.org/?probe=ca2b52b64f) | Dec 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [da58685854](https://linux-hardware.org/?probe=da58685854) | Dec 25, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | [9d3fa026ff](https://linux-hardware.org/?probe=9d3fa026ff) | Dec 25, 2023 |
| ASUSTek       | D500MD                      | [21870febdd](https://linux-hardware.org/?probe=21870febdd) | Dec 25, 2023 |
| HP            | 21D0                        | [733191fd29](https://linux-hardware.org/?probe=733191fd29) | Dec 24, 2023 |
| Gigabyte      | B660I AORUS PRO DDR4        | [f9552f9e38](https://linux-hardware.org/?probe=f9552f9e38) | Dec 21, 2023 |
| Dell          | 0101XX A00                  | [13751aa80b](https://linux-hardware.org/?probe=13751aa80b) | Dec 21, 2023 |
| HP            | 8061                        | [9700867e8c](https://linux-hardware.org/?probe=9700867e8c) | Dec 13, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [6ed556a0a1](https://linux-hardware.org/?probe=6ed556a0a1) | Dec 03, 2023 |
| HP            | 8061                        | [8f86201dfb](https://linux-hardware.org/?probe=8f86201dfb) | Dec 01, 2023 |
| HP            | 83E2                        | [b580eaa5fa](https://linux-hardware.org/?probe=b580eaa5fa) | Nov 27, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [15c6e07487](https://linux-hardware.org/?probe=15c6e07487) | Nov 27, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [84b3b5a3a1](https://linux-hardware.org/?probe=84b3b5a3a1) | Nov 25, 2023 |
| HP            | 21D0                        | [3e85a284ec](https://linux-hardware.org/?probe=3e85a284ec) | Nov 23, 2023 |
| ASRock        | B660M-STX                   | [883a70813a](https://linux-hardware.org/?probe=883a70813a) | Nov 19, 2023 |
| Acer          | EG43LMK                     | [bc1ab38f8f](https://linux-hardware.org/?probe=bc1ab38f8f) | Nov 18, 2023 |
| ASUSTek       | W580/SYS                    | [31a696a5bc](https://linux-hardware.org/?probe=31a696a5bc) | Nov 14, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [61b583fe07](https://linux-hardware.org/?probe=61b583fe07) | Nov 12, 2023 |
| Unknown       | ADL-N Prod                  | [c3e54c030c](https://linux-hardware.org/?probe=c3e54c030c) | Nov 08, 2023 |
| Unknown       | ADL-N Prod                  | [023eb019ba](https://linux-hardware.org/?probe=023eb019ba) | Nov 08, 2023 |
| ASRock        | H97M Anniversary            | [6c66e3862d](https://linux-hardware.org/?probe=6c66e3862d) | Nov 01, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [39f8a7c959](https://linux-hardware.org/?probe=39f8a7c959) | Nov 01, 2023 |
| ASUSTek       | PRIME B360M-C               | [874efda598](https://linux-hardware.org/?probe=874efda598) | Oct 31, 2023 |
| ASUSTek       | PRIME B360M-C               | [16da68741a](https://linux-hardware.org/?probe=16da68741a) | Oct 31, 2023 |
| ASUSTek       | P5E Deluxe                  | [5601096ffc](https://linux-hardware.org/?probe=5601096ffc) | Oct 29, 2023 |
| Gigabyte      | GA-770TA-UD3                | [f1a5d466cd](https://linux-hardware.org/?probe=f1a5d466cd) | Oct 29, 2023 |
| ASUSTek       | H81M-E                      | [1cd579935b](https://linux-hardware.org/?probe=1cd579935b) | Oct 27, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d49188de1a](https://linux-hardware.org/?probe=d49188de1a) | Oct 26, 2023 |
| Gigabyte      | GA-770TA-UD3                | [6944656466](https://linux-hardware.org/?probe=6944656466) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bb6c63a5b3](https://linux-hardware.org/?probe=bb6c63a5b3) | Oct 26, 2023 |
| Dell          | 097YXY A00                  | [31dc22d5af](https://linux-hardware.org/?probe=31dc22d5af) | Oct 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3130876407](https://linux-hardware.org/?probe=3130876407) | Oct 17, 2023 |
| Acer          | EG31M P01-A0                | [1e500b6b4a](https://linux-hardware.org/?probe=1e500b6b4a) | Oct 17, 2023 |
| ONDA          | H110CD3 VER1.01             | [df23b03be3](https://linux-hardware.org/?probe=df23b03be3) | Oct 15, 2023 |
| HP            | 802F                        | [ed3a09f912](https://linux-hardware.org/?probe=ed3a09f912) | Oct 12, 2023 |
| MSI           | PRO H610M-G DDR4            | [c698bae21a](https://linux-hardware.org/?probe=c698bae21a) | Oct 12, 2023 |
| MSI           | PRO H610M-G DDR4            | [167f75f814](https://linux-hardware.org/?probe=167f75f814) | Oct 12, 2023 |
| HP            | 802F                        | [c2b0f9720e](https://linux-hardware.org/?probe=c2b0f9720e) | Oct 12, 2023 |
| ASUSTek       | P5Q3 DELUXE                 | [29bb46e198](https://linux-hardware.org/?probe=29bb46e198) | Oct 12, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [a5904a1aeb](https://linux-hardware.org/?probe=a5904a1aeb) | Oct 07, 2023 |
| Dell          | 00010C A00                  | [40d7defca4](https://linux-hardware.org/?probe=40d7defca4) | Sep 23, 2023 |
| Centerm       | C92                         | [022344ea10](https://linux-hardware.org/?probe=022344ea10) | Sep 22, 2023 |
| Acer          | Revo RN86                   | [315559ee42](https://linux-hardware.org/?probe=315559ee42) | Sep 21, 2023 |
| ASUSTek       | Z170-P D3                   | [fad69be075](https://linux-hardware.org/?probe=fad69be075) | Sep 12, 2023 |
| MSI           | MS-B0A81                    | [2c4cc9e78f](https://linux-hardware.org/?probe=2c4cc9e78f) | Sep 05, 2023 |
| Gigabyte      | GA-770TA-UD3                | [6bd78c519f](https://linux-hardware.org/?probe=6bd78c519f) | Aug 25, 2023 |
| ASUSTek       | M11AD                       | [a107c7eb20](https://linux-hardware.org/?probe=a107c7eb20) | Aug 25, 2023 |
| Acer          | Predator G3610              | [008082be63](https://linux-hardware.org/?probe=008082be63) | Aug 19, 2023 |
| Acer          | Predator G3610              | [d362c81682](https://linux-hardware.org/?probe=d362c81682) | Aug 19, 2023 |
| ASUSTek       | BM6875_BM6675_BP6375        | [0a2cdad4c1](https://linux-hardware.org/?probe=0a2cdad4c1) | Aug 15, 2023 |
| Gigabyte      | B550M K                     | [139e314619](https://linux-hardware.org/?probe=139e314619) | Jul 31, 2023 |
| Dell          | 00010C A00                  | [71eca6ee4c](https://linux-hardware.org/?probe=71eca6ee4c) | Jul 20, 2023 |
| Altos         | BrainSphere P10 F7          | [8608df7a38](https://linux-hardware.org/?probe=8608df7a38) | Jul 20, 2023 |
| AAEON         | GENE-CML5 V1.0              | [4120e07431](https://linux-hardware.org/?probe=4120e07431) | Jul 19, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [62238aaf82](https://linux-hardware.org/?probe=62238aaf82) | Jul 17, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [bc805d82a7](https://linux-hardware.org/?probe=bc805d82a7) | Jul 13, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [36b6c49552](https://linux-hardware.org/?probe=36b6c49552) | Jul 09, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [ffa5984711](https://linux-hardware.org/?probe=ffa5984711) | Jul 09, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [f15cf1d31b](https://linux-hardware.org/?probe=f15cf1d31b) | Jul 02, 2023 |
| Intel         | X99                         | [81dbd5c4f0](https://linux-hardware.org/?probe=81dbd5c4f0) | Jul 01, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [e72c8358c4](https://linux-hardware.org/?probe=e72c8358c4) | Jun 22, 2023 |
| ASRock        | X370 Killer SLI             | [10939cb152](https://linux-hardware.org/?probe=10939cb152) | Jun 20, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [2734ce8c5d](https://linux-hardware.org/?probe=2734ce8c5d) | Jun 16, 2023 |
| MSI           | B250M MORTAR ARCTIC         | [5e0e6586b7](https://linux-hardware.org/?probe=5e0e6586b7) | Jun 11, 2023 |
| MSI           | H97 GAMING 3                | [f9c0a669c5](https://linux-hardware.org/?probe=f9c0a669c5) | Jun 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [936b06e11f](https://linux-hardware.org/?probe=936b06e11f) | May 25, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [2adc02040e](https://linux-hardware.org/?probe=2adc02040e) | May 21, 2023 |
| Win elemen... | M600                        | [4c5d685663](https://linux-hardware.org/?probe=4c5d685663) | May 21, 2023 |
| Win elemen... | M600                        | [84de4a3207](https://linux-hardware.org/?probe=84de4a3207) | May 20, 2023 |
| Unknown       | Unknown                     | [661a7cf306](https://linux-hardware.org/?probe=661a7cf306) | May 11, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [867e98f955](https://linux-hardware.org/?probe=867e98f955) | May 05, 2023 |
| MSI           | H55M-P31                    | [386b720202](https://linux-hardware.org/?probe=386b720202) | May 04, 2023 |
| Acer          | Veriton M2630G V:1.0        | [7ffa9c83d7](https://linux-hardware.org/?probe=7ffa9c83d7) | May 03, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [e5051f5355](https://linux-hardware.org/?probe=e5051f5355) | May 02, 2023 |
| HP            | 83E2                        | [f10d975821](https://linux-hardware.org/?probe=f10d975821) | Apr 26, 2023 |
| ASRock        | X300M-STX                   | [4a8d662bee](https://linux-hardware.org/?probe=4a8d662bee) | Apr 25, 2023 |
| Gigabyte      | H81N                        | [5729c6c6a9](https://linux-hardware.org/?probe=5729c6c6a9) | Apr 20, 2023 |
| Acer          | Predator G3610              | [3d1841fa41](https://linux-hardware.org/?probe=3d1841fa41) | Apr 17, 2023 |
| Acer          | EG43LMK                     | [78b389b848](https://linux-hardware.org/?probe=78b389b848) | Apr 15, 2023 |
| Acer          | Predator G3610              | [d49e4d680c](https://linux-hardware.org/?probe=d49e4d680c) | Apr 14, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [ad8009e647](https://linux-hardware.org/?probe=ad8009e647) | Apr 11, 2023 |
| Win elemen... | M600                        | [7723a03558](https://linux-hardware.org/?probe=7723a03558) | Apr 10, 2023 |
| Win elemen... | M600                        | [e20927ec15](https://linux-hardware.org/?probe=e20927ec15) | Apr 10, 2023 |
| Gigabyte      | F2A78M-DS2                  | [0528b2df2b](https://linux-hardware.org/?probe=0528b2df2b) | Apr 01, 2023 |
| Unknown       | Unknown                     | [8f1561c37b](https://linux-hardware.org/?probe=8f1561c37b) | Mar 28, 2023 |
| ASRock        | N68-GS4/USB3 FX             | [b846b11174](https://linux-hardware.org/?probe=b846b11174) | Mar 25, 2023 |
| ASUSTek       | H110M-K D3                  | [24a568ad05](https://linux-hardware.org/?probe=24a568ad05) | Mar 25, 2023 |
| MSI           | H55M-P31                    | [07a5228600](https://linux-hardware.org/?probe=07a5228600) | Mar 25, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [b03324de35](https://linux-hardware.org/?probe=b03324de35) | Mar 24, 2023 |
| Gigabyte      | B75N                        | [8a16ffed3b](https://linux-hardware.org/?probe=8a16ffed3b) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [7d1cd9aded](https://linux-hardware.org/?probe=7d1cd9aded) | Mar 20, 2023 |
| OEM           | B85 JHS359                  | [1d5d7e95fc](https://linux-hardware.org/?probe=1d5d7e95fc) | Mar 16, 2023 |
| Gigabyte      | G31M-ES2L                   | [f5535f53dc](https://linux-hardware.org/?probe=f5535f53dc) | Mar 08, 2023 |
| ASUSTek       | H81M-E                      | [fc1a09013d](https://linux-hardware.org/?probe=fc1a09013d) | Mar 05, 2023 |
| MSI           | MEG X670E ACE               | [ee356bc253](https://linux-hardware.org/?probe=ee356bc253) | Mar 02, 2023 |
| ASRock        | X300M-STX                   | [061edbf583](https://linux-hardware.org/?probe=061edbf583) | Mar 01, 2023 |
| ASRock        | X300M-STX                   | [97a1558878](https://linux-hardware.org/?probe=97a1558878) | Feb 25, 2023 |
| Maxtang       | EHL30 V1.0                  | [4d133c615c](https://linux-hardware.org/?probe=4d133c615c) | Feb 10, 2023 |
| ASRockRack    | X570D4U                     | [bb2c98768e](https://linux-hardware.org/?probe=bb2c98768e) | Feb 10, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [7f895dc97f](https://linux-hardware.org/?probe=7f895dc97f) | Feb 04, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [9e9deedf0d](https://linux-hardware.org/?probe=9e9deedf0d) | Jan 31, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| Gigabyte      | H81N                        | [e7cf6a4216](https://linux-hardware.org/?probe=e7cf6a4216) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| Acer          | Aspire XC-105               | [8192fe90a8](https://linux-hardware.org/?probe=8192fe90a8) | Jan 19, 2023 |
| Acer          | FMCP7A-ION-LE               | [84a2abec03](https://linux-hardware.org/?probe=84a2abec03) | Jan 07, 2023 |
| Unknown       | Unknown                     | [34b6109940](https://linux-hardware.org/?probe=34b6109940) | Dec 29, 2022 |
| ASUSTek       | PRIME H510M-K               | [9b1f8e9a10](https://linux-hardware.org/?probe=9b1f8e9a10) | Dec 18, 2022 |
| ASUSTek       | CM1530                      | [3990cff263](https://linux-hardware.org/?probe=3990cff263) | Dec 06, 2022 |
| Dell          | 0NNFGG A00                  | [b955357ccc](https://linux-hardware.org/?probe=b955357ccc) | Dec 05, 2022 |
| Gigabyte      | Z370M DS3H-CF               | [580b716020](https://linux-hardware.org/?probe=580b716020) | Dec 03, 2022 |
| ASUSTek       | Z97-K                       | [52aaeb537b](https://linux-hardware.org/?probe=52aaeb537b) | Dec 03, 2022 |
| ASRock        | X300M-STX                   | [97ceee65f3](https://linux-hardware.org/?probe=97ceee65f3) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [5b7f983a24](https://linux-hardware.org/?probe=5b7f983a24) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [42ddb2463e](https://linux-hardware.org/?probe=42ddb2463e) | Dec 01, 2022 |
| Dell          | 0XJ5V0 A03                  | [b954e4c174](https://linux-hardware.org/?probe=b954e4c174) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [aea7b4c016](https://linux-hardware.org/?probe=aea7b4c016) | Nov 23, 2022 |
| Gigabyte      | Z490 AORUS PRO AX           | [abe3da973c](https://linux-hardware.org/?probe=abe3da973c) | Nov 19, 2022 |
| Intel         | Burnside                    | [5db283bd1f](https://linux-hardware.org/?probe=5db283bd1f) | Nov 17, 2022 |
| ASRock        | A320M-HDV R4.0              | [7764c0fea2](https://linux-hardware.org/?probe=7764c0fea2) | Nov 15, 2022 |
| MSI           | A320M PRO-VH                | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Location/Taiwan/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 18.04       | 51       | 13.01%  |
| Ubuntu 20.04       | 39       | 9.95%   |
| Ubuntu 22.04       | 29       | 7.4%    |
| Ubuntu 24.04       | 14       | 3.57%   |
| Arch Rolling       | 13       | 3.32%   |
| Debian 11          | 10       | 2.55%   |
| OpenMandriva 4.2   | 9        | 2.3%    |
| Debian 12          | 8        | 2.04%   |
| Linux Mint 20.3    | 7        | 1.79%   |
| OpenMandriva 23.03 | 6        | 1.53%   |
| OpenMandriva 23.01 | 6        | 1.53%   |
| Xubuntu 20.04      | 5        | 1.28%   |
| Xubuntu 18.04      | 5        | 1.28%   |
| OpenMandriva 4.3   | 5        | 1.28%   |
| Fedora 41          | 5        | 1.28%   |
| Fedora 39          | 5        | 1.28%   |
| Pop!_OS 20.04      | 4        | 1.02%   |
| OpenMandriva 25.90 | 4        | 1.02%   |
| OpenMandriva 23.08 | 4        | 1.02%   |
| Linux Mint 22.1    | 4        | 1.02%   |
| Fedora 38          | 4        | 1.02%   |
| Fedora 37          | 4        | 1.02%   |
| Ubuntu 21.10       | 3        | 0.77%   |
| Ubuntu 19.04       | 3        | 0.77%   |
| OpenMandriva 5.0   | 3        | 0.77%   |
| OpenMandriva 25.06 | 3        | 0.77%   |
| Linux Mint 22.2    | 3        | 0.77%   |
| Kubuntu 20.04      | 3        | 0.77%   |
| Debian 13          | 3        | 0.77%   |
| Zorin 17           | 2        | 0.51%   |
| Zorin 16           | 2        | 0.51%   |
| Ubuntu 23.10       | 2        | 0.51%   |
| Ubuntu 23.04       | 2        | 0.51%   |
| Ubuntu 22.10       | 2        | 0.51%   |
| Ubuntu 20.10       | 2        | 0.51%   |
| Ubuntu 19.10       | 2        | 0.51%   |
| Ubuntu 18.10       | 2        | 0.51%   |
| Ubuntu 16.04       | 2        | 0.51%   |
| TUXEDO OS 24.04    | 2        | 0.51%   |
| ROSA R11           | 2        | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 154      | 41.29%  |
| OpenMandriva  | 42       | 11.26%  |
| Fedora        | 27       | 7.24%   |
| Debian        | 24       | 6.43%   |
| Linux Mint    | 23       | 6.17%   |
| Arch          | 14       | 3.75%   |
| Xubuntu       | 13       | 3.49%   |
| Manjaro       | 10       | 2.68%   |
| Pop!_OS       | 7        | 1.88%   |
| Zorin         | 5        | 1.34%   |
| Kubuntu       | 5        | 1.34%   |
| Kali          | 5        | 1.34%   |
| Ubuntu MATE   | 4        | 1.07%   |
| ROSA          | 4        | 1.07%   |
| openSUSE      | 4        | 1.07%   |
| Endless       | 4        | 1.07%   |
| Gentoo        | 3        | 0.8%    |
| TUXEDO OS     | 2        | 0.54%   |
| SteamOS       | 2        | 0.54%   |
| NixOS         | 2        | 0.54%   |
| Lubuntu       | 2        | 0.54%   |
| KDE neon      | 2        | 0.54%   |
| Clear Linux   | 2        | 0.54%   |
| CentOS        | 2        | 0.54%   |
| Ubuntu Unity  | 1        | 0.27%   |
| Ubuntu Budgie | 1        | 0.27%   |
| OpenEuler     | 1        | 0.27%   |
| Mageia        | 1        | 0.27%   |
| Lilidog       | 1        | 0.27%   |
| Garuda Linux  | 1        | 0.27%   |
| EndeavourOS   | 1        | 0.27%   |
| BlackPanther  | 1        | 0.27%   |
| Bazzite       | 1        | 0.27%   |
| Atz           | 1        | 0.27%   |
| ArcoLinux     | 1        | 0.27%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 6.6.2-desktop-1omv2390   | 7        | 1.65%   |
| 6.14.2-desktop-3omv2590  | 7        | 1.65%   |
| 5.10.14-desktop-1omv4002 | 7        | 1.65%   |
| 6.1.1-desktop-1omv2290   | 6        | 1.42%   |
| 6.2.6-desktop-1omv2390   | 5        | 1.18%   |
| 5.4.0-42-generic         | 5        | 1.18%   |
| 5.16.7-desktop-1omv4003  | 5        | 1.18%   |
| 5.8.0-50-generic         | 4        | 0.95%   |
| 5.4.0-45-generic         | 4        | 0.95%   |
| 5.4.0-28-generic         | 4        | 0.95%   |
| 6.8.0-51-generic         | 3        | 0.71%   |
| 6.8.0-45-generic         | 3        | 0.71%   |
| 6.5.0-27-generic         | 3        | 0.71%   |
| 5.4.0-58-generic         | 3        | 0.71%   |
| 5.19.0-46-generic        | 3        | 0.71%   |
| 5.11.0-27-generic        | 3        | 0.71%   |
| 5.0.0-37-generic         | 3        | 0.71%   |
| 5.0.0-23-generic         | 3        | 0.71%   |
| 4.15.0-66-generic        | 3        | 0.71%   |
| 4.15.0-29-generic        | 3        | 0.71%   |
| 6.8.0-50-generic         | 2        | 0.47%   |
| 6.5.5-desktop-1omv2390   | 2        | 0.47%   |
| 6.5.0-35-generic         | 2        | 0.47%   |
| 6.4.8-desktop-2omv2390   | 2        | 0.47%   |
| 6.4.11-desktop-1omv2390  | 2        | 0.47%   |
| 6.2.0-35-generic         | 2        | 0.47%   |
| 6.14.0-29-generic        | 2        | 0.47%   |
| 6.12.57+deb13-amd64      | 2        | 0.47%   |
| 5.8.0-55-generic         | 2        | 0.47%   |
| 5.8.0-43-generic         | 2        | 0.47%   |
| 5.8.0-38-generic         | 2        | 0.47%   |
| 5.5.0-kali2-amd64        | 2        | 0.47%   |
| 5.4.0-81-generic         | 2        | 0.47%   |
| 5.4.0-80-generic         | 2        | 0.47%   |
| 5.4.0-77-generic         | 2        | 0.47%   |
| 5.4.0-66-generic         | 2        | 0.47%   |
| 5.4.0-54-generic         | 2        | 0.47%   |
| 5.4.0-53-generic         | 2        | 0.47%   |
| 5.4.0-48-generic         | 2        | 0.47%   |
| 5.4.0-150-generic        | 2        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 55       | 13.78%  |
| 4.15.0  | 27       | 6.77%   |
| 5.15.0  | 19       | 4.76%   |
| 6.8.0   | 18       | 4.51%   |
| 6.5.0   | 14       | 3.51%   |
| 5.8.0   | 13       | 3.26%   |
| 5.11.0  | 11       | 2.76%   |
| 5.0.0   | 11       | 2.76%   |
| 4.18.0  | 10       | 2.51%   |
| 6.2.0   | 9        | 2.26%   |
| 6.14.0  | 9        | 2.26%   |
| 5.3.0   | 9        | 2.26%   |
| 5.19.0  | 9        | 2.26%   |
| 6.6.2   | 8        | 2.01%   |
| 5.13.0  | 8        | 2.01%   |
| 6.14.2  | 7        | 1.75%   |
| 6.1.0   | 7        | 1.75%   |
| 5.10.14 | 7        | 1.75%   |
| 6.1.1   | 6        | 1.5%    |
| 6.2.6   | 5        | 1.25%   |
| 5.16.7  | 5        | 1.25%   |
| 5.10.0  | 5        | 1.25%   |
| 6.11.0  | 4        | 1%      |
| 6.4.0   | 3        | 0.75%   |
| 6.5.5   | 2        | 0.5%    |
| 6.4.8   | 2        | 0.5%    |
| 6.4.11  | 2        | 0.5%    |
| 6.2.2   | 2        | 0.5%    |
| 6.2.12  | 2        | 0.5%    |
| 6.12.57 | 2        | 0.5%    |
| 6.11.11 | 2        | 0.5%    |
| 5.5.0   | 2        | 0.5%    |
| 5.18.12 | 2        | 0.5%    |
| 5.15.83 | 2        | 0.5%    |
| 5.15.23 | 2        | 0.5%    |
| 5.11.12 | 2        | 0.5%    |
| 4.19.57 | 2        | 0.5%    |
| 4.19.0  | 2        | 0.5%    |
| 4.12.14 | 2        | 0.5%    |
| 6.9.3   | 1        | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 55       | 13.96%  |
| 5.15    | 28       | 7.11%   |
| 4.15    | 27       | 6.85%   |
| 6.5     | 22       | 5.58%   |
| 6.2     | 22       | 5.58%   |
| 6.8     | 20       | 5.08%   |
| 6.14    | 18       | 4.57%   |
| 6.1     | 17       | 4.31%   |
| 5.10    | 17       | 4.31%   |
| 5.8     | 15       | 3.81%   |
| 6.6     | 14       | 3.55%   |
| 5.11    | 14       | 3.55%   |
| 5.0     | 12       | 3.05%   |
| 4.18    | 11       | 2.79%   |
| 5.19    | 10       | 2.54%   |
| 6.11    | 9        | 2.28%   |
| 5.3     | 9        | 2.28%   |
| 6.4     | 8        | 2.03%   |
| 6.12    | 8        | 2.03%   |
| 5.13    | 8        | 2.03%   |
| 5.16    | 7        | 1.78%   |
| 6.0     | 6        | 1.52%   |
| 6.3     | 4        | 1.02%   |
| 4.19    | 4        | 1.02%   |
| 6.13    | 3        | 0.76%   |
| 5.5     | 3        | 0.76%   |
| 5.18    | 3        | 0.76%   |
| 6.7     | 2        | 0.51%   |
| 6.17    | 2        | 0.51%   |
| 4.12    | 2        | 0.51%   |
| 6.9     | 1        | 0.25%   |
| 6.16    | 1        | 0.25%   |
| 6.15    | 1        | 0.25%   |
| 6.10    | 1        | 0.25%   |
| 5.9     | 1        | 0.25%   |
| 5.7     | 1        | 0.25%   |
| 5.17    | 1        | 0.25%   |
| 5.14    | 1        | 0.25%   |
| 5.12    | 1        | 0.25%   |
| 5.1     | 1        | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 360      | 98.09%  |
| i686    | 6        | 1.63%   |
| riscv64 | 1        | 0.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 174      | 45.91%  |
| Unknown          | 59       | 15.57%  |
| KDE5             | 57       | 15.04%  |
| XFCE             | 23       | 6.07%   |
| X-Cinnamon       | 14       | 3.69%   |
| KDE6             | 13       | 3.43%   |
| LXQt             | 8        | 2.11%   |
| Cinnamon         | 7        | 1.85%   |
| MATE             | 6        | 1.58%   |
| KDE              | 5        | 1.32%   |
| LXDE             | 2        | 0.53%   |
| Hyprland         | 2        | 0.53%   |
| GNOME Classic    | 2        | 0.53%   |
| Unity            | 1        | 0.26%   |
| lightdm-xsession | 1        | 0.26%   |
| KDE4             | 1        | 0.26%   |
| i3               | 1        | 0.26%   |
| Deepin           | 1        | 0.26%   |
| COSMIC           | 1        | 0.26%   |
| Budgie           | 1        | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 247      | 63.99%  |
| Wayland | 95       | 24.61%  |
| Unknown | 30       | 7.77%   |
| Tty     | 14       | 3.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 156      | 41.82%  |
| SDDM    | 64       | 17.16%  |
| GDM3    | 64       | 17.16%  |
| GDM     | 54       | 14.48%  |
| LightDM | 25       | 6.7%    |
| TDM     | 8        | 2.14%   |
| KDM     | 2        | 0.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 164      | 43.5%   |
| zh_TW      | 132      | 35.01%  |
| Unknown    | 48       | 12.73%  |
| C          | 12       | 3.18%   |
| zh_CN      | 7        | 1.86%   |
| zh_HK      | 2        | 0.53%   |
| en_HK      | 2        | 0.53%   |
| en_GB      | 2        | 0.53%   |
| POSIX      | 1        | 0.27%   |
| lzh_TW     | 1        | 0.27%   |
| it_IT      | 1        | 0.27%   |
| es_ES      | 1        | 0.27%   |
| en_US.UTF8 | 1        | 0.27%   |
| en_SG      | 1        | 0.27%   |
| en_PH      | 1        | 0.27%   |
| en_AU      | 1        | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 200      | 53.48%  |
| BIOS | 174      | 46.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 244      | 65.07%  |
| Btrfs   | 51       | 13.6%   |
| Tmpfs   | 30       | 8%      |
| Overlay | 24       | 6.4%    |
| Xfs     | 14       | 3.73%   |
| Unknown | 7        | 1.87%   |
| Ext2    | 3        | 0.8%    |
| Rootfs  | 1        | 0.27%   |
| Ext3    | 1        | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 203      | 54.42%  |
| Unknown | 144      | 38.61%  |
| MBR     | 26       | 6.97%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 286      | 76.88%  |
| Yes       | 86       | 23.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 223      | 58.99%  |
| Yes       | 155      | 41.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 114      | 31.06%  |
| Gigabyte Technology | 83       | 22.62%  |
| MSI                 | 36       | 9.81%   |
| ASRock              | 25       | 6.81%   |
| Acer                | 20       | 5.45%   |
| Hewlett-Packard     | 15       | 4.09%   |
| Dell                | 15       | 4.09%   |
| Unknown             | 12       | 3.27%   |
| Lenovo              | 9        | 2.45%   |
| Intel               | 5        | 1.36%   |
| JGINYUE             | 3        | 0.82%   |
| OEM                 | 2        | 0.54%   |
| Huanan              | 2        | 0.54%   |
| EBN                 | 2        | 0.54%   |
| Win element         | 1        | 0.27%   |
| Tianbei             | 1        | 0.27%   |
| Supermicro          | 1        | 0.27%   |
| Standard            | 1        | 0.27%   |
| Ruckus Wireless     | 1        | 0.27%   |
| Red Hat             | 1        | 0.27%   |
| PANSHI              | 1        | 0.27%   |
| ONDA                | 1        | 0.27%   |
| NEXCOM              | 1        | 0.27%   |
| Maxtang             | 1        | 0.27%   |
| HC Technology.      | 1        | 0.27%   |
| Foxconn             | 1        | 0.27%   |
| eMachines           | 1        | 0.27%   |
| DNI                 | 1        | 0.27%   |
| DFI                 | 1        | 0.27%   |
| Centerm             | 1        | 0.27%   |
| BESSTAR Tech        | 1        | 0.27%   |
| AZW                 | 1        | 0.27%   |
| AURES               | 1        | 0.27%   |
| ASRockRack          | 1        | 0.27%   |
| Apple               | 1        | 0.27%   |
| Altos               | 1        | 0.27%   |
| Accton              | 1        | 0.27%   |
| AAEON               | 1        | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 12       | 3.27%   |
| ASUS All Series                 | 7        | 1.91%   |
| Gigabyte B75M-D3H               | 5        | 1.36%   |
| Gigabyte B550I AORUS PRO AX     | 4        | 1.09%   |
| ASUS M5A78L-M/USB3              | 4        | 1.09%   |
| ASRock X300M-STX                | 4        | 1.09%   |
| Lenovo ThinkCentre M58 7627AA9  | 3        | 0.82%   |
| Gigabyte Z97MX-Gaming 5         | 3        | 0.82%   |
| Dell Inspiron 531s              | 3        | 0.82%   |
| ASUS TUF Gaming B550M-PLUS      | 3        | 0.82%   |
| ASUS Pro WS X570-ACE            | 3        | 0.82%   |
| ASUS CM6630_CM6730_CM6830       | 3        | 0.82%   |
| Acer Veriton L480               | 3        | 0.82%   |
| MSI MS-7C95                     | 2        | 0.54%   |
| MSI MS-7C52                     | 2        | 0.54%   |
| MSI MS-7B89                     | 2        | 0.54%   |
| MSI MS-7A69                     | 2        | 0.54%   |
| MSI MS-7721                     | 2        | 0.54%   |
| Intel SHARKBAY                  | 2        | 0.54%   |
| HP ProDesk 600 G1 DM            | 2        | 0.54%   |
| Gigabyte Z77M-D3H               | 2        | 0.54%   |
| Gigabyte H81N                   | 2        | 0.54%   |
| Gigabyte G31M-ES2L              | 2        | 0.54%   |
| Gigabyte B85M-D2V               | 2        | 0.54%   |
| Gigabyte B450 I AORUS PRO WIFI  | 2        | 0.54%   |
| ASUS TUF Gaming B560M-PLUS WIFI | 2        | 0.54%   |
| ASUS ROG STRIX B350-F GAMING    | 2        | 0.54%   |
| ASUS PRIME B660M-A WIFI D4      | 2        | 0.54%   |
| ASUS P8Z77-V LX                 | 2        | 0.54%   |
| ASRock N68-GS4/USB3 FX          | 2        | 0.54%   |
| ASRock H310M-ITX/ac             | 2        | 0.54%   |
| ASRock A320M-HDV R4.0           | 2        | 0.54%   |
| ASRock A300M-STX                | 2        | 0.54%   |
| ASRock 960GC-GS FX              | 2        | 0.54%   |
| Acer Veriton M6620G             | 2        | 0.54%   |
| Win element M600                | 1        | 0.27%   |
| Tianbei GEM12                   | 1        | 0.27%   |
| Supermicro C9Z490-PGW           | 1        | 0.27%   |
| Standard EL Series              | 1        | 0.27%   |
| Ruckus Wireless SCG-100         | 1        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS TUF              | 16       | 4.36%   |
| ASUS PRIME            | 16       | 4.36%   |
| ASUS ROG              | 13       | 3.54%   |
| Unknown               | 12       | 3.27%   |
| Acer Aspire           | 9        | 2.45%   |
| ASUS All              | 7        | 1.91%   |
| Acer Veriton          | 7        | 1.91%   |
| ASUS Pro              | 6        | 1.63%   |
| ASUS M5A78L-M         | 6        | 1.63%   |
| Gigabyte B75M-D3H     | 5        | 1.36%   |
| Dell Inspiron         | 5        | 1.36%   |
| Lenovo ThinkCentre    | 4        | 1.09%   |
| HP ProDesk            | 4        | 1.09%   |
| Gigabyte B550I        | 4        | 1.09%   |
| Dell Precision        | 4        | 1.09%   |
| Dell OptiPlex         | 4        | 1.09%   |
| ASRock X300M-STX      | 4        | 1.09%   |
| Gigabyte Z97MX-Gaming | 3        | 0.82%   |
| Gigabyte B550M        | 3        | 0.82%   |
| Gigabyte B450         | 3        | 0.82%   |
| ASUS P8Z77-V          | 3        | 0.82%   |
| ASUS CM6630           | 3        | 0.82%   |
| MSI PRO               | 2        | 0.54%   |
| MSI MS-7C95           | 2        | 0.54%   |
| MSI MS-7C52           | 2        | 0.54%   |
| MSI MS-7B89           | 2        | 0.54%   |
| MSI MS-7A69           | 2        | 0.54%   |
| MSI MS-7721           | 2        | 0.54%   |
| Lenovo IdeaCentre     | 2        | 0.54%   |
| Intel SHARKBAY        | 2        | 0.54%   |
| HP Z240               | 2        | 0.54%   |
| Gigabyte Z77M-D3H     | 2        | 0.54%   |
| Gigabyte X570S        | 2        | 0.54%   |
| Gigabyte X570         | 2        | 0.54%   |
| Gigabyte H81N         | 2        | 0.54%   |
| Gigabyte G31M-ES2L    | 2        | 0.54%   |
| Gigabyte G1.Sniper    | 2        | 0.54%   |
| Gigabyte B85M-D2V     | 2        | 0.54%   |
| Gigabyte B360         | 2        | 0.54%   |
| ASUS WS               | 2        | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 38       | 10.35%  |
| 2018    | 36       | 9.81%   |
| 2014    | 31       | 8.45%   |
| 2012    | 31       | 8.45%   |
| 2022    | 30       | 8.17%   |
| 2021    | 30       | 8.17%   |
| 2013    | 26       | 7.08%   |
| 2011    | 19       | 5.18%   |
| 2019    | 16       | 4.36%   |
| 2016    | 16       | 4.36%   |
| 2023    | 15       | 4.09%   |
| 2015    | 15       | 4.09%   |
| 2009    | 15       | 4.09%   |
| 2017    | 14       | 3.81%   |
| 2010    | 10       | 2.72%   |
| 2008    | 10       | 2.72%   |
| 2024    | 9        | 2.45%   |
| 2007    | 5        | 1.36%   |
| Unknown | 1        | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 367      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 355      | 96.47%  |
| Enabled  | 13       | 3.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 367      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 89       | 23.73%  |
| 32.01-64.0      | 78       | 20.8%   |
| 4.01-8.0        | 53       | 14.13%  |
| 8.01-16.0       | 50       | 13.33%  |
| 3.01-4.0        | 47       | 12.53%  |
| 64.01-256.0     | 36       | 9.6%    |
| 24.01-32.0      | 13       | 3.47%   |
| 1.01-2.0        | 6        | 1.6%    |
| More than 256.0 | 3        | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 130      | 31.71%  |
| 2.01-3.0   | 90       | 21.95%  |
| 4.01-8.0   | 71       | 17.32%  |
| 3.01-4.0   | 60       | 14.63%  |
| 8.01-16.0  | 27       | 6.59%   |
| 0.51-1.0   | 14       | 3.41%   |
| 16.01-24.0 | 6        | 1.46%   |
| 32.01-64.0 | 4        | 0.98%   |
| 24.01-32.0 | 4        | 0.98%   |
| 0.01-0.5   | 4        | 0.98%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 143      | 37.63%  |
| 2      | 116      | 30.53%  |
| 3      | 65       | 17.11%  |
| 4      | 24       | 6.32%   |
| 5      | 14       | 3.68%   |
| 0      | 8        | 2.11%   |
| 6      | 6        | 1.58%   |
| 7      | 2        | 0.53%   |
| 14     | 1        | 0.26%   |
| 9      | 1        | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 266      | 71.7%   |
| Yes       | 105      | 28.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 364      | 99.18%  |
| No        | 3        | 0.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 190      | 51.35%  |
| Yes       | 180      | 48.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 231      | 61.76%  |
| Yes       | 143      | 38.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Taiwan  | 367      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Taipei            | 102      | 26.56%  |
| New Taipei        | 79       | 20.57%  |
| Taichung          | 31       | 8.07%   |
| Hsinchu           | 31       | 8.07%   |
| Taoyuan District  | 26       | 6.77%   |
| Kaohsiung City    | 23       | 5.99%   |
| Tainan City       | 18       | 4.69%   |
| Hsinchu County    | 6        | 1.56%   |
| Chang-hua         | 6        | 1.56%   |
| Zhongli District  | 5        | 1.3%    |
| Keelung           | 4        | 1.04%   |
| Taichung City     | 3        | 0.78%   |
| Nantou City       | 3        | 0.78%   |
| Miaoli            | 3        | 0.78%   |
| Zhudong           | 2        | 0.52%   |
| Zhubei            | 2        | 0.52%   |
| Yilan             | 2        | 0.52%   |
| Yangmei District  | 2        | 0.52%   |
| Kanzijiao         | 2        | 0.52%   |
| Chiayi City       | 2        | 0.52%   |
| Changhua          | 2        | 0.52%   |
| Beimiao           | 2        | 0.52%   |
| Banqiao           | 2        | 0.52%   |
| Baitang           | 2        | 0.52%   |
| Yingge District   | 1        | 0.26%   |
| Xinzhuang         | 1        | 0.26%   |
| Xindian District  | 1        | 0.26%   |
| Xindian           | 1        | 0.26%   |
| Xiatayou          | 1        | 0.26%   |
| Taoyuan City      | 1        | 0.26%   |
| Taitung           | 1        | 0.26%   |
| Taishan           | 1        | 0.26%   |
| Sanchong District | 1        | 0.26%   |
| Pingzhen District | 1        | 0.26%   |
| Pingtung City     | 1        | 0.26%   |
| Neihu District    | 1        | 0.26%   |
| Magong            | 1        | 0.26%   |
| Longtan District  | 1        | 0.26%   |
| Hualien City      | 1        | 0.26%   |
| Guishan           | 1        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 101      | 170    | 14.6%   |
| WDC                          | 92       | 135    | 13.29%  |
| Toshiba                      | 54       | 71     | 7.8%    |
| Crucial                      | 51       | 69     | 7.37%   |
| Intel                        | 35       | 49     | 5.06%   |
| Samsung Electronics          | 26       | 31     | 3.76%   |
| Hitachi                      | 26       | 30     | 3.76%   |
| A-DATA Technology            | 25       | 28     | 3.61%   |
| Kingston                     | 22       | 29     | 3.18%   |
| Transcend                    | 18       | 19     | 2.6%    |
| SanDisk                      | 17       | 26     | 2.46%   |
| Unknown                      | 15       | 20     | 2.17%   |
| Phison Electronics           | 11       | 13     | 1.59%   |
| ANACOMDA                     | 11       | 16     | 1.59%   |
| Micron/Crucial Technology    | 10       | 13     | 1.45%   |
| Micron Technology            | 9        | 10     | 1.3%    |
| Apacer                       | 9        | 13     | 1.3%    |
| ADATA Technology             | 9        | 16     | 1.3%    |
| SK hynix                     | 8        | 8      | 1.16%   |
| Plextor                      | 8        | 9      | 1.16%   |
| China                        | 8        | 9      | 1.16%   |
| SPCC                         | 7        | 9      | 1.01%   |
| Silicon Motion               | 7        | 7      | 1.01%   |
| Team                         | 5        | 6      | 0.72%   |
| MAXIO Technology (Hangzhou)  | 5        | 6      | 0.72%   |
| KLEVV                        | 5        | 8      | 0.72%   |
| HGST                         | 5        | 7      | 0.72%   |
| XPG                          | 4        | 5      | 0.58%   |
| PNY                          | 4        | 7      | 0.58%   |
| Phison                       | 4        | 5      | 0.58%   |
| Patriot                      | 4        | 6      | 0.58%   |
| Lite-On                      | 4        | 4      | 0.58%   |
| Fujitsu                      | 4        | 6      | 0.58%   |
| Unknown                      | 4        | 4      | 0.58%   |
| Maxtor                       | 3        | 3      | 0.43%   |
| KIOXIA                       | 3        | 3      | 0.43%   |
| USB                          | 2        | 3      | 0.29%   |
| TOPMORE                      | 2        | 2      | 0.29%   |
| Shenzhen Longsys Electronics | 2        | 2      | 0.29%   |
| Realtek Semiconductor        | 2        | 3      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                             | 20       | 2.62%   |
| Crucial CT500MX500SSD1 500GB                                       | 16       | 2.09%   |
| Toshiba DT01ACA200 2TB                                             | 12       | 1.57%   |
| Crucial CT1000MX500SSD1 1TB                                        | 12       | 1.57%   |
| Seagate ST2000DM008-2FR102 2TB                                     | 9        | 1.18%   |
| Seagate ST500DM002-1BD142 500GB                                    | 7        | 0.92%   |
| Seagate ST3500418AS 500GB                                          | 7        | 0.92%   |
| Seagate ST1000DM010-2EP102 1TB                                     | 7        | 0.92%   |
| Toshiba MQ01ABD032 320GB                                           | 5        | 0.65%   |
| Seagate ST2000DM001-1CH164 2TB                                     | 5        | 0.65%   |
| Seagate ST1000DM003-1SB102 1TB                                     | 5        | 0.65%   |
| SanDisk NVMe SSD Drive 500GB                                       | 5        | 0.65%   |
| Crucial CT2000MX500SSD1 2TB                                        | 5        | 0.65%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 5        | 0.65%   |
| A-DATA SU800 512GB SSD                                             | 5        | 0.65%   |
| WDC WDS250G1B0B-00AS40 250GB SSD                                   | 4        | 0.52%   |
| WDC WDS100T2B0C-00PXH0 1TB                                         | 4        | 0.52%   |
| WDC WD10EZEX-75WN4A1 1TB                                           | 4        | 0.52%   |
| Unknown SD/MMC/MS PRO 2GB                                          | 4        | 0.52%   |
| Seagate ST6000DM003-2CY186 6TB                                     | 4        | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB                                     | 4        | 0.52%   |
| Phison E16 PCIe4 NVMe Controller 1TB                               | 4        | 0.52%   |
| Patriot Burst 120GB SSD                                            | 4        | 0.52%   |
| Kingston SA400S37480G 480GB SSD                                    | 4        | 0.52%   |
| Hitachi HDT721010SLA360 1TB                                        | 4        | 0.52%   |
| Crucial CT240BX500SSD1 240GB                                       | 4        | 0.52%   |
| A-DATA SU800 256GB SSD                                             | 4        | 0.52%   |
| Unknown                                                            | 4        | 0.52%   |
| WDC WD6402AAEX-00Z3A0 640GB                                        | 3        | 0.39%   |
| WDC WD3200AAKS-00L9A0 320GB                                        | 3        | 0.39%   |
| WDC WD1600AAJS-08L7A0 160GB                                        | 3        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                                           | 3        | 0.39%   |
| Unknown 004G60  4GB                                                | 3        | 0.39%   |
| Transcend TS128GSSD340 128GB                                       | 3        | 0.39%   |
| Silicon Motion NVMe SSD Drive 512GB                                | 3        | 0.39%   |
| Seagate ST750LX003-1AC154 752GB                                    | 3        | 0.39%   |
| Seagate ST3320613AS 320GB                                          | 3        | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB                                     | 3        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                                         | 3        | 0.39%   |
| Samsung SSD 980 1TB                                                | 3        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 100      | 167    | 37.45%  |
| WDC                 | 72       | 105    | 26.97%  |
| Toshiba             | 52       | 69     | 19.48%  |
| Hitachi             | 26       | 30     | 9.74%   |
| Unknown             | 5        | 7      | 1.87%   |
| HGST                | 5        | 7      | 1.87%   |
| Maxtor              | 3        | 3      | 1.12%   |
| Samsung Electronics | 2        | 3      | 0.75%   |
| USB                 | 1        | 2      | 0.37%   |
| Fujitsu             | 1        | 2      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 45       | 60     | 19.48%  |
| A-DATA Technology   | 21       | 24     | 9.09%   |
| Intel               | 19       | 26     | 8.23%   |
| Transcend           | 17       | 18     | 7.36%   |
| Kingston            | 14       | 18     | 6.06%   |
| WDC                 | 12       | 17     | 5.19%   |
| ANACOMDA            | 10       | 15     | 4.33%   |
| Plextor             | 7        | 8      | 3.03%   |
| China               | 7        | 8      | 3.03%   |
| SPCC                | 6        | 8      | 2.6%    |
| Samsung Electronics | 6        | 6      | 2.6%    |
| Apacer              | 6        | 8      | 2.6%    |
| SanDisk             | 5        | 7      | 2.16%   |
| KLEVV               | 5        | 8      | 2.16%   |
| Team                | 4        | 5      | 1.73%   |
| Patriot             | 4        | 6      | 1.73%   |
| Micron Technology   | 4        | 4      | 1.73%   |
| Toshiba             | 2        | 2      | 0.87%   |
| Pioneer             | 2        | 2      | 0.87%   |
| OCZ                 | 2        | 2      | 0.87%   |
| Leven               | 2        | 2      | 0.87%   |
| Gigastone           | 2        | 2      | 0.87%   |
| Fujitsu             | 2        | 2      | 0.87%   |
| ASMT                | 2        | 2      | 0.87%   |
| ZHITAI              | 1        | 1      | 0.43%   |
| Wintec              | 1        | 1      | 0.43%   |
| Unknown             | 1        | 1      | 0.43%   |
| UNITEK              | 1        | 1      | 0.43%   |
| UMAX                | 1        | 1      | 0.43%   |
| T-FORCE             | 1        | 1      | 0.43%   |
| Sony                | 1        | 1      | 0.43%   |
| SK hynix            | 1        | 1      | 0.43%   |
| SINKER              | 1        | 1      | 0.43%   |
| SCY                 | 1        | 1      | 0.43%   |
| OCZ-VECT            | 1        | 1      | 0.43%   |
| OCZ-REVODRIVE       | 1        | 4      | 0.43%   |
| MemoCom             | 1        | 2      | 0.43%   |
| LITEONIT            | 1        | 1      | 0.43%   |
| Lite-On             | 1        | 1      | 0.43%   |
| Kingchuxing         | 1        | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 212      | 395    | 37.46%  |
| SSD     | 188      | 291    | 33.22%  |
| NVMe    | 150      | 234    | 26.5%   |
| Unknown | 11       | 14     | 1.94%   |
| MMC     | 5        | 5      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 305      | 660    | 63.15%  |
| NVMe | 149      | 233    | 30.85%  |
| SAS  | 24       | 41     | 4.97%   |
| MMC  | 5        | 5      | 1.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 206      | 347    | 46.29%  |
| 0.51-1.0   | 139      | 190    | 31.24%  |
| 1.01-2.0   | 52       | 80     | 11.69%  |
| 3.01-4.0   | 21       | 31     | 4.72%   |
| 2.01-3.0   | 11       | 12     | 2.47%   |
| 4.01-10.0  | 11       | 21     | 2.47%   |
| 10.01-20.0 | 5        | 5      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 89       | 22.65%  |
| 251-500        | 59       | 15.01%  |
| 501-1000       | 53       | 13.49%  |
| 1001-2000      | 48       | 12.21%  |
| More than 3000 | 35       | 8.91%   |
| 2001-3000      | 30       | 7.63%   |
| 51-100         | 28       | 7.12%   |
| 1-20           | 20       | 5.09%   |
| 21-50          | 16       | 4.07%   |
| Unknown        | 15       | 3.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 138      | 34.33%  |
| 21-50          | 54       | 13.43%  |
| 51-100         | 51       | 12.69%  |
| 101-250        | 49       | 12.19%  |
| 251-500        | 27       | 6.72%   |
| 1001-2000      | 26       | 6.47%   |
| 501-1000       | 23       | 5.72%   |
| Unknown        | 15       | 3.73%   |
| More than 3000 | 13       | 3.23%   |
| 2001-3000      | 6        | 1.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Intel SSDPEKKW256G7 256GB           | 2        | 3      | 5%      |
| Hitachi HDT721010SLA360 1TB         | 2        | 2      | 5%      |
| WDC WDS100T2B0C-00PXH0 1TB          | 1        | 1      | 2.5%    |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 2.5%    |
| WDC WD5000AAKX-001CA0 500GB         | 1        | 1      | 2.5%    |
| WDC WD5000AADS-00L4B1 500GB         | 1        | 1      | 2.5%    |
| WDC WD3200AAKS-00L9A0 320GB         | 1        | 1      | 2.5%    |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1      | 2.5%    |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 2.5%    |
| WDC WD10EFRX-68JCSN0 1TB            | 1        | 1      | 2.5%    |
| WDC WD10EALS-00Z8A0 1TB             | 1        | 1      | 2.5%    |
| WDC WD1002FAEX-00Z3A0 1TB           | 1        | 1      | 2.5%    |
| Transcend TS64GSSD340 64GB          | 1        | 1      | 2.5%    |
| Toshiba DT01ACA100 1TB              | 1        | 1      | 2.5%    |
| Seagate ST9250315AS 250GB           | 1        | 1      | 2.5%    |
| Seagate ST500LM000-1EJ162 500GB     | 1        | 1      | 2.5%    |
| Seagate ST4000DX001-1CE168 4TB      | 1        | 2      | 2.5%    |
| Seagate ST380811AS 80GB             | 1        | 1      | 2.5%    |
| Seagate ST3500418AS 500GB           | 1        | 1      | 2.5%    |
| Seagate ST3500410SV 500GB           | 1        | 1      | 2.5%    |
| Seagate ST3160811AS 160GB           | 1        | 1      | 2.5%    |
| Seagate ST31000528AS 1TB            | 1        | 1      | 2.5%    |
| Seagate ST2000VN000-1H3164 2TB      | 1        | 2      | 2.5%    |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 1      | 2.5%    |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 1      | 2.5%    |
| SanDisk SDSSDX240GG25 240GB         | 1        | 2      | 2.5%    |
| Samsung Electronics HM321HI 320GB   | 1        | 2      | 2.5%    |
| Plextor PX-128M6Pro 128GB SSD       | 1        | 1      | 2.5%    |
| LITEONIT E200-080 80GB SSD          | 1        | 1      | 2.5%    |
| KLEVV SSD NEO N500 240GB            | 1        | 1      | 2.5%    |
| Kingston SV300S37A60G 64GB SSD      | 1        | 1      | 2.5%    |
| Kingston SKC2500M8500G 500GB        | 1        | 1      | 2.5%    |
| Intel SSDSC2BB016T7 2TB             | 1        | 1      | 2.5%    |
| Hitachi HDS723020BLA642 2TB         | 1        | 2      | 2.5%    |
| HGST HTS545050A7E680 500GB          | 1        | 1      | 2.5%    |
| Fujitsu F500S-480GB SSD             | 1        | 1      | 2.5%    |
| Crucial CT275MX300SSD4 275GB        | 1        | 1      | 2.5%    |
| A-DATA Technology IMSS332-960GB SSD | 1        | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 13     | 27.5%   |
| WDC                 | 10       | 10     | 25%     |
| Intel               | 3        | 4      | 7.5%    |
| Hitachi             | 3        | 4      | 7.5%    |
| Kingston            | 2        | 2      | 5%      |
| Transcend           | 1        | 1      | 2.5%    |
| Toshiba             | 1        | 1      | 2.5%    |
| SanDisk             | 1        | 2      | 2.5%    |
| Samsung Electronics | 1        | 2      | 2.5%    |
| Plextor             | 1        | 1      | 2.5%    |
| LITEONIT            | 1        | 1      | 2.5%    |
| KLEVV               | 1        | 1      | 2.5%    |
| HGST                | 1        | 1      | 2.5%    |
| Fujitsu             | 1        | 1      | 2.5%    |
| Crucial             | 1        | 1      | 2.5%    |
| A-DATA Technology   | 1        | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 13     | 42.31%  |
| WDC                 | 9        | 9      | 34.62%  |
| Hitachi             | 3        | 4      | 11.54%  |
| Toshiba             | 1        | 1      | 3.85%   |
| Samsung Electronics | 1        | 2      | 3.85%   |
| HGST                | 1        | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 30     | 62.16%  |
| SSD  | 10       | 11     | 27.03%  |
| NVMe | 4        | 5      | 10.81%  |

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
| Detected | 206      | 514    | 50.37%  |
| Works    | 167      | 379    | 40.83%  |
| Malfunc  | 36       | 46     | 8.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 255      | 45.45%  |
| AMD                             | 97       | 17.29%  |
| Phison Electronics              | 26       | 4.63%   |
| SanDisk                         | 22       | 3.92%   |
| ASMedia Technology              | 20       | 3.57%   |
| Samsung Electronics             | 18       | 3.21%   |
| Micron/Crucial Technology       | 17       | 3.03%   |
| ADATA Technology                | 14       | 2.5%    |
| Silicon Motion                  | 9        | 1.6%    |
| Nvidia                          | 9        | 1.6%    |
| Kingston Technology Company     | 9        | 1.6%    |
| SK hynix                        | 7        | 1.25%   |
| Micron Technology               | 7        | 1.25%   |
| MAXIO Technology (Hangzhou)     | 7        | 1.25%   |
| Marvell Technology Group        | 7        | 1.25%   |
| JMicron Technology              | 6        | 1.07%   |
| Realtek Semiconductor           | 3        | 0.53%   |
| Lite-On Technology              | 3        | 0.53%   |
| KIOXIA                          | 3        | 0.53%   |
| INNOGRIT                        | 3        | 0.53%   |
| Broadcom / LSI                  | 3        | 0.53%   |
| Solidigm                        | 2        | 0.36%   |
| Solid State Storage Technology  | 2        | 0.36%   |
| Shenzhen Longsys Electronics    | 2        | 0.36%   |
| LSI Logic / Symbios Logic       | 2        | 0.36%   |
| Biwin Storage Technology        | 2        | 0.36%   |
| Yangtze Memory Technologies     | 1        | 0.18%   |
| Silicon Image                   | 1        | 0.18%   |
| Shenzhen Techwinsemi Technology | 1        | 0.18%   |
| Seagate Technology              | 1        | 0.18%   |
| Integrated Technology Express   | 1        | 0.18%   |
| Innodisk                        | 1        | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 47       | 6.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 33       | 4.85%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 20       | 2.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 19       | 2.79%   |
| AMD 500 Series Chipset SATA Controller                                                  | 18       | 2.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 16       | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 2.35%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 15       | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 2.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13       | 1.91%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 12       | 1.76%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 12       | 1.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12       | 1.76%   |
| AMD 600 Series Chipset SATA Controller                                                  | 12       | 1.76%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 11       | 1.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11       | 1.62%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 1.62%   |
| Intel SATA Controller [RAID mode]                                                       | 10       | 1.47%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 9        | 1.32%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 9        | 1.32%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 9        | 1.32%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8        | 1.18%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 8        | 1.18%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 1.03%   |
| Intel Alder Lake-N SATA AHCI Controller                                                 | 7        | 1.03%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 1.03%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6        | 0.88%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 6        | 0.88%   |
| Phison E12 NVMe Controller                                                              | 6        | 0.88%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 0.88%   |
| Nvidia MCP61 IDE                                                                        | 6        | 0.88%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                        | 6        | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 0.88%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 0.88%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 0.74%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 5        | 0.74%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 302      | 54.61%  |
| NVMe | 149      | 26.94%  |
| IDE  | 70       | 12.66%  |
| RAID | 25       | 4.52%   |
| SAS  | 5        | 0.9%    |
| SCSI | 2        | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 259      | 70.57%  |
| AMD           | 107      | 29.16%  |
| sifive,u74-mc | 1        | 0.27%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel 12th Gen Core i7-12700                | 7        | 1.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 6        | 1.61%   |
| AMD Ryzen 5 3600 6-Core Processor           | 6        | 1.61%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 1.34%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 5        | 1.34%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 4        | 1.07%   |
| Intel Core i5-4670T CPU @ 2.30GHz           | 4        | 1.07%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 1.07%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 1.07%   |
| Intel 12th Gen Core i5-12400                | 4        | 1.07%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 4        | 1.07%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4        | 1.07%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 1.07%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 1.07%   |
| AMD FX-6300 Six-Core Processor              | 4        | 1.07%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 3        | 0.8%    |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz         | 3        | 0.8%    |
| Intel Pentium CPU G840 @ 2.80GHz            | 3        | 0.8%    |
| Intel N100                                  | 3        | 0.8%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 0.8%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 0.8%    |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 0.8%    |
| Intel Core i7-10700 CPU @ 2.90GHz           | 3        | 0.8%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.8%    |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 0.8%    |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 0.8%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 0.8%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 0.8%    |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 3        | 0.8%    |
| Intel Celeron J4105 CPU @ 1.50GHz           | 3        | 0.8%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 0.8%    |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 3        | 0.8%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 0.8%    |
| AMD Ryzen 5 3500X 6-Core Processor          | 3        | 0.8%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 0.8%    |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 2        | 0.54%   |
| Intel Pentium Gold G5500 CPU @ 3.80GHz      | 2        | 0.54%   |
| Intel N97                                   | 2        | 0.54%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 0.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 62       | 16.67%  |
| Intel Core i7           | 44       | 11.83%  |
| Other                   | 38       | 10.22%  |
| Intel Core i3           | 32       | 8.6%    |
| AMD Ryzen 5             | 30       | 8.06%   |
| Intel Xeon              | 28       | 7.53%   |
| AMD Ryzen 7             | 20       | 5.38%   |
| Intel Celeron           | 15       | 4.03%   |
| AMD Ryzen 9             | 14       | 3.76%   |
| Intel Core 2 Quad       | 12       | 3.23%   |
| Intel Pentium           | 10       | 2.69%   |
| AMD FX                  | 9        | 2.42%   |
| Intel Core 2 Duo        | 5        | 1.34%   |
| AMD Ryzen 5 PRO         | 5        | 1.34%   |
| Intel Pentium Gold      | 4        | 1.08%   |
| Intel Pentium Dual-Core | 4        | 1.08%   |
| Intel Core i9           | 4        | 1.08%   |
| AMD Athlon 64 X2        | 4        | 1.08%   |
| Intel Genuine           | 3        | 0.81%   |
| AMD Ryzen 3             | 3        | 0.81%   |
| AMD Phenom II X4        | 3        | 0.81%   |
| Intel Atom              | 2        | 0.54%   |
| AMD Ryzen Threadripper  | 2        | 0.54%   |
| AMD Athlon II X4        | 2        | 0.54%   |
| AMD Athlon II X2        | 2        | 0.54%   |
| AMD A8                  | 2        | 0.54%   |
| AMD A4                  | 2        | 0.54%   |
| AMD A10                 | 2        | 0.54%   |
| Intel Pentium Silver    | 1        | 0.27%   |
| Intel Core              | 1        | 0.27%   |
| AMD Sempron             | 1        | 0.27%   |
| AMD Ryzen 7 PRO         | 1        | 0.27%   |
| AMD Phenom II X6        | 1        | 0.27%   |
| AMD Phenom II X2        | 1        | 0.27%   |
| AMD E                   | 1        | 0.27%   |
| AMD Athlon              | 1        | 0.27%   |
| AMD A6                  | 1        | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 142      | 38.27%  |
| 2       | 74       | 19.95%  |
| 6       | 63       | 16.98%  |
| 8       | 39       | 10.51%  |
| 12      | 19       | 5.12%   |
| 16      | 11       | 2.96%   |
| 28      | 4        | 1.08%   |
| 24      | 3        | 0.81%   |
| 14      | 3        | 0.81%   |
| 3       | 3        | 0.81%   |
| 10      | 2        | 0.54%   |
| 48      | 1        | 0.27%   |
| 44      | 1        | 0.27%   |
| 32      | 1        | 0.27%   |
| 22      | 1        | 0.27%   |
| 20      | 1        | 0.27%   |
| 18      | 1        | 0.27%   |
| 1       | 1        | 0.27%   |
| Unknown | 1        | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 356      | 97%     |
| 2       | 9        | 2.45%   |
| 4       | 1        | 0.27%   |
| Unknown | 1        | 0.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 220      | 59.3%   |
| 1       | 150      | 40.43%  |
| Unknown | 1        | 0.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 361      | 98.1%   |
| Unknown        | 7        | 1.9%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 162      | 42.19%  |
| 0x306c3    | 27       | 7.03%   |
| 0x306a9    | 17       | 4.43%   |
| 0x206a7    | 14       | 3.65%   |
| 0x506e3    | 10       | 2.6%    |
| 0x08701021 | 9        | 2.34%   |
| 0x1067a    | 8        | 2.08%   |
| 0x906ea    | 7        | 1.82%   |
| 0x906eb    | 6        | 1.56%   |
| 0x06000852 | 5        | 1.3%    |
| 0x90672    | 4        | 1.04%   |
| 0x706a1    | 4        | 1.04%   |
| 0x10676    | 4        | 1.04%   |
| 0xa0655    | 3        | 0.78%   |
| 0xa0653    | 3        | 0.78%   |
| 0x406f1    | 3        | 0.78%   |
| 0x10677    | 3        | 0.78%   |
| 0x0a601203 | 3        | 0.78%   |
| 0x0a50000d | 3        | 0.78%   |
| 0x0a201009 | 3        | 0.78%   |
| 0x0810100b | 3        | 0.78%   |
| 0x08001138 | 3        | 0.78%   |
| 0x06001119 | 3        | 0.78%   |
| 0x010000c8 | 3        | 0.78%   |
| 0xb0671    | 2        | 0.52%   |
| 0xa0671    | 2        | 0.52%   |
| 0x906ed    | 2        | 0.52%   |
| 0x90661    | 2        | 0.52%   |
| 0x6fb      | 2        | 0.52%   |
| 0x50654    | 2        | 0.52%   |
| 0x306f2    | 2        | 0.52%   |
| 0x306e4    | 2        | 0.52%   |
| 0x206c2    | 2        | 0.52%   |
| 0x106e5    | 2        | 0.52%   |
| 0x0a50000c | 2        | 0.52%   |
| 0x0a20120a | 2        | 0.52%   |
| 0x0a20102b | 2        | 0.52%   |
| 0x0a201016 | 2        | 0.52%   |
| 0x08600106 | 2        | 0.52%   |
| 0x08101016 | 2        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Haswell           | 47       | 12.77%  |
| KabyLake          | 37       | 10.05%  |
| Unknown           | 33       | 8.97%   |
| IvyBridge         | 28       | 7.61%   |
| Zen 2             | 23       | 6.25%   |
| Skylake           | 22       | 5.98%   |
| SandyBridge       | 22       | 5.98%   |
| Zen 3             | 20       | 5.43%   |
| Penryn            | 20       | 5.43%   |
| Alderlake Hybrid  | 18       | 4.89%   |
| Piledriver        | 12       | 3.26%   |
| CometLake         | 11       | 2.99%   |
| Zen               | 10       | 2.72%   |
| K10               | 10       | 2.72%   |
| Zen+              | 9        | 2.45%   |
| Broadwell         | 7        | 1.9%    |
| Westmere          | 5        | 1.36%   |
| Icelake           | 5        | 1.36%   |
| Nehalem           | 4        | 1.09%   |
| K8 Hammer         | 4        | 1.09%   |
| Goldmont plus     | 4        | 1.09%   |
| Tremont           | 3        | 0.82%   |
| Silvermont        | 3        | 0.82%   |
| Jaguar            | 2        | 0.54%   |
| Core              | 2        | 0.54%   |
| Steamroller       | 1        | 0.27%   |
| Meteorlake Hybrid | 1        | 0.27%   |
| K10 Llano         | 1        | 0.27%   |
| Gracemont         | 1        | 0.27%   |
| Goldmont          | 1        | 0.27%   |
| Bulldozer         | 1        | 0.27%   |
| Bonnell           | 1        | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 152      | 38.87%  |
| Intel                      | 145      | 37.08%  |
| AMD                        | 88       | 22.51%  |
| ASPEED Technology          | 3        | 0.77%   |
| Matrox Electronics Systems | 2        | 0.51%   |
| Red Hat                    | 1        | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 21       | 5.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17       | 4.23%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 12       | 2.99%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 10       | 2.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 10       | 2.49%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 9        | 2.24%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 9        | 2.24%   |
| Nvidia GK208B [GeForce GT 710]                                              | 8        | 1.99%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 8        | 1.99%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 7        | 1.74%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 7        | 1.74%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 1.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 1.74%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 1.74%   |
| AMD RS780L [Radeon 3000]                                                    | 6        | 1.49%   |
| AMD Raphael                                                                 | 6        | 1.49%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 1.49%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 5        | 1.24%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 5        | 1.24%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 5        | 1.24%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 1.24%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 5        | 1.24%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 5        | 1.24%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 1%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1%      |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 4        | 1%      |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 4        | 1%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1%      |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 0.75%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 0.75%   |
| Nvidia GM107GL [Quadro K2200]                                               | 3        | 0.75%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 3        | 0.75%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 0.75%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 3        | 0.75%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 3        | 0.75%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 3        | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3        | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3        | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 134      | 36.12%  |
| 1 x Intel      | 128      | 34.5%   |
| 1 x AMD        | 75       | 20.22%  |
| Intel + Nvidia | 12       | 3.23%   |
| AMD + Nvidia   | 6        | 1.62%   |
| 2 x AMD        | 4        | 1.08%   |
| Other          | 3        | 0.81%   |
| 1 x Matrox     | 2        | 0.54%   |
| Intel + AMD    | 2        | 0.54%   |
| 1 x ASPEED     | 2        | 0.54%   |
| 2 x Nvidia     | 1        | 0.27%   |
| 1 x Red Hat    | 1        | 0.27%   |
| AMD + ASPEED   | 1        | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 265      | 70.67%  |
| Proprietary | 76       | 20.27%  |
| Unknown     | 34       | 9.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 203      | 53.42%  |
| 1.01-2.0   | 41       | 10.79%  |
| 0.51-1.0   | 30       | 7.89%   |
| 0.01-0.5   | 30       | 7.89%   |
| 3.01-4.0   | 25       | 6.58%   |
| 5.01-6.0   | 18       | 4.74%   |
| 8.01-16.0  | 15       | 3.95%   |
| 7.01-8.0   | 12       | 3.16%   |
| 2.01-3.0   | 3        | 0.79%   |
| 16.01-24.0 | 3        | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Ancor Communications | 42       | 11.17%  |
| BenQ                 | 39       | 10.37%  |
| Acer                 | 38       | 10.11%  |
| ViewSonic            | 30       | 7.98%   |
| Dell                 | 25       | 6.65%   |
| Goldstar             | 23       | 6.12%   |
| ASUSTek Computer     | 23       | 6.12%   |
| AOC                  | 18       | 4.79%   |
| Samsung Electronics  | 14       | 3.72%   |
| Philips              | 12       | 3.19%   |
| NEX                  | 10       | 2.66%   |
| Gigabyte Technology  | 9        | 2.39%   |
| Hewlett-Packard      | 8        | 2.13%   |
| Eizo                 | 8        | 2.13%   |
| MSI                  | 6        | 1.6%    |
| Envision Peripherals | 6        | 1.6%    |
| Unknown              | 5        | 1.33%   |
| LG Electronics       | 4        | 1.06%   |
| Vizio                | 3        | 0.8%    |
| Sony                 | 3        | 0.8%    |
| Compal               | 3        | 0.8%    |
| Unknown              | 3        | 0.8%    |
| Wacom                | 2        | 0.53%   |
| Unknown (XXX)        | 2        | 0.53%   |
| Mi                   | 2        | 0.53%   |
| KTC                  | 2        | 0.53%   |
| Chimei Innolux       | 2        | 0.53%   |
| AUS                  | 2        | 0.53%   |
| AOpen                | 2        | 0.53%   |
| ___                  | 1        | 0.27%   |
| VST                  | 1        | 0.27%   |
| VIZ                  | 1        | 0.27%   |
| Toshiba              | 1        | 0.27%   |
| Tatung               | 1        | 0.27%   |
| SMP                  | 1        | 0.27%   |
| Sharp                | 1        | 0.27%   |
| RTK                  | 1        | 0.27%   |
| RHT                  | 1        | 0.27%   |
| PFH                  | 1        | 0.27%   |
| ONX                  | 1        | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch           | 8        | 2.08%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 6        | 1.56%   |
| Gigabyte Technology GS32QC GBT3212 2560x1440 709x403mm 32.1-inch      | 6        | 1.56%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 4        | 1.04%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 4        | 1.04%   |
| BenQ EW2480 BNQ7951 1920x1080 527x296mm 23.8-inch                     | 4        | 1.04%   |
| Ancor Communications VX239 ACI23E1 1920x1080 510x290mm 23.1-inch      | 4        | 1.04%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                    | 4        | 1.04%   |
| BenQ GC2870 BNQ78DD 1920x1080 621x341mm 27.9-inch                     | 3        | 0.78%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 3        | 0.78%   |
| Ancor Communications ASUS VS207 ACI20F2 1600x900 432x240mm 19.5-inch  | 3        | 0.78%   |
| Ancor Communications ASUS VH228 ACI22FC 1920x1080 477x268mm 21.5-inch | 3        | 0.78%   |
| Acer XV272U ACR06C1 2560x1440 597x336mm 27.0-inch                     | 3        | 0.78%   |
| Acer V226HQL ACR0335 1920x1080 477x268mm 21.5-inch                    | 3        | 0.78%   |
| Unknown                                                               | 3        | 0.78%   |
| Wacom Cintiq 13HD WAC1040 1920x1080 293x165mm 13.2-inch               | 2        | 0.52%   |
| ViewSonic VX2476 Series VSCD332 1920x1080 527x296mm 23.8-inch         | 2        | 0.52%   |
| ViewSonic VA916 Series VSC7C20 1280x1024 376x301mm 19.0-inch          | 2        | 0.52%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch         | 2        | 0.52%   |
| ViewSonic VA1932 Series VSC8724 1440x900 408x255mm 18.9-inch          | 2        | 0.52%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.52%   |
| Unknown LCD Monitor Kingston Technology 43 TV 1920x1080               | 2        | 0.52%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 950x540mm 43.0-inch             | 2        | 0.52%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2        | 0.52%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 2        | 0.52%   |
| KTC 43'TV KTC4300 3840x2160 953x543mm 43.2-inch                       | 2        | 0.52%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 2        | 0.52%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 2        | 0.52%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.52%   |
| Envision Peripherals LED H963wLs ENV1963 1366x768 410x230mm 18.5-inch | 2        | 0.52%   |
| Envision Peripherals LED 2271wh ENV2271 1920x1080 476x268mm 21.5-inch | 2        | 0.52%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2        | 0.52%   |
| Dell U2311H DELA05F 1920x1080 509x286mm 23.0-inch                     | 2        | 0.52%   |
| Dell P2319H DELD0D7 1920x1080 509x286mm 23.0-inch                     | 2        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 2        | 0.52%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                     | 2        | 0.52%   |
| BenQ GW2455 BNQ78D8 1920x1080 521x293mm 23.5-inch                     | 2        | 0.52%   |
| BenQ GW2450H BNQ78C1 1920x1080 531x298mm 24.0-inch                    | 2        | 0.52%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                     | 2        | 0.52%   |
| BenQ GL2450H BNQ78A6 1920x1080 531x298mm 24.0-inch                    | 2        | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 201      | 56.62%  |
| 2560x1440 (QHD)    | 38       | 10.7%   |
| 3840x2160 (4K)     | 29       | 8.17%   |
| 1366x768 (WXGA)    | 17       | 4.79%   |
| 2560x1080          | 11       | 3.1%    |
| 1680x1050 (WSXGA+) | 10       | 2.82%   |
| 1280x1024 (SXGA)   | 10       | 2.82%   |
| 1920x1200 (WUXGA)  | 8        | 2.25%   |
| 1440x900 (WXGA+)   | 8        | 2.25%   |
| 1600x900 (HD+)     | 7        | 1.97%   |
| 3840x1080          | 3        | 0.85%   |
| 3440x1440          | 3        | 0.85%   |
| 1920x540           | 2        | 0.56%   |
| 1024x768 (XGA)     | 2        | 0.56%   |
| Unknown            | 2        | 0.56%   |
| 2560x1397          | 1        | 0.28%   |
| 2200x1650          | 1        | 0.28%   |
| 1600x1200          | 1        | 0.28%   |
| 1360x768           | 1        | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 68       | 18.38%  |
| 21      | 57       | 15.41%  |
| 24      | 54       | 14.59%  |
| 23      | 42       | 11.35%  |
| Unknown | 35       | 9.46%   |
| 19      | 20       | 5.41%   |
| 31      | 13       | 3.51%   |
| 18      | 12       | 3.24%   |
| 34      | 9        | 2.43%   |
| 32      | 8        | 2.16%   |
| 22      | 7        | 1.89%   |
| 15      | 7        | 1.89%   |
| 43      | 5        | 1.35%   |
| 13      | 4        | 1.08%   |
| 63      | 3        | 0.81%   |
| 42      | 3        | 0.81%   |
| 40      | 3        | 0.81%   |
| 20      | 3        | 0.81%   |
| 48      | 2        | 0.54%   |
| 17      | 2        | 0.54%   |
| 84      | 1        | 0.27%   |
| 75      | 1        | 0.27%   |
| 69      | 1        | 0.27%   |
| 65      | 1        | 0.27%   |
| 64      | 1        | 0.27%   |
| 54      | 1        | 0.27%   |
| 52      | 1        | 0.27%   |
| 49      | 1        | 0.27%   |
| 41      | 1        | 0.27%   |
| 29      | 1        | 0.27%   |
| 26      | 1        | 0.27%   |
| 25      | 1        | 0.27%   |
| 12      | 1        | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 150      | 41.55%  |
| 401-500     | 91       | 25.21%  |
| Unknown     | 35       | 9.7%    |
| 601-700     | 22       | 6.09%   |
| 701-800     | 17       | 4.71%   |
| 1001-1500   | 10       | 2.77%   |
| 901-1000    | 9        | 2.49%   |
| 301-350     | 8        | 2.22%   |
| 351-400     | 7        | 1.94%   |
| 201-300     | 6        | 1.66%   |
| 801-900     | 3        | 0.83%   |
| 1501-2000   | 3        | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 249      | 72.81%  |
| Unknown | 34       | 9.94%   |
| 16/10   | 30       | 8.77%   |
| 5/4     | 9        | 2.63%   |
| 21/9    | 9        | 2.63%   |
| 4/3     | 5        | 1.46%   |
| 32/9    | 4        | 1.17%   |
| 6/5     | 1        | 0.29%   |
| 3/2     | 1        | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 129      | 34.96%  |
| 301-350        | 68       | 18.43%  |
| 151-200        | 42       | 11.38%  |
| Unknown        | 35       | 9.49%   |
| 351-500        | 31       | 8.4%    |
| 251-300        | 15       | 4.07%   |
| 501-1000       | 15       | 4.07%   |
| 141-150        | 12       | 3.25%   |
| More than 1000 | 10       | 2.71%   |
| 101-110        | 5        | 1.36%   |
| 71-80          | 4        | 1.08%   |
| 81-90          | 1        | 0.27%   |
| 121-130        | 1        | 0.27%   |
| 111-120        | 1        | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 211      | 58.61%  |
| 101-120 | 85       | 23.61%  |
| Unknown | 35       | 9.72%   |
| 121-160 | 11       | 3.06%   |
| 161-240 | 10       | 2.78%   |
| 1-50    | 8        | 2.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 305      | 81.99%  |
| 0     | 33       | 8.87%   |
| 2     | 29       | 7.8%    |
| 3     | 3        | 0.81%   |
| 4     | 2        | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 216      | 39.27%  |
| Intel                                  | 178      | 32.36%  |
| Qualcomm Atheros                       | 21       | 3.82%   |
| MediaTek                               | 16       | 2.91%   |
| Ralink Technology                      | 14       | 2.55%   |
| Broadcom                               | 14       | 2.55%   |
| Aquantia                               | 13       | 2.36%   |
| ASUSTek Computer                       | 10       | 1.82%   |
| TP-Link                                | 8        | 1.45%   |
| Edimax Technology                      | 8        | 1.45%   |
| Marvell Technology Group               | 6        | 1.09%   |
| Nvidia                                 | 5        | 0.91%   |
| HTC (High Tech Computer)               | 4        | 0.73%   |
| D-Link                                 | 3        | 0.55%   |
| Winbond Electronics                    | 2        | 0.36%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.36%   |
| Samsung Electronics                    | 2        | 0.36%   |
| Ralink                                 | 2        | 0.36%   |
| Microsoft                              | 2        | 0.36%   |
| Mercucys                               | 2        | 0.36%   |
| ZyXEL Communications                   | 1        | 0.18%   |
| Xiaomi                                 | 1        | 0.18%   |
| SparkFun                               | 1        | 0.18%   |
| Senao                                  | 1        | 0.18%   |
| Qualcomm Technologies                  | 1        | 0.18%   |
| Qualcomm Atheros Communications        | 1        | 0.18%   |
| Qualcomm                               | 1        | 0.18%   |
| Prolific Technology                    | 1        | 0.18%   |
| OPPO Electronics                       | 1        | 0.18%   |
| Mellanox Technologies                  | 1        | 0.18%   |
| IBM                                    | 1        | 0.18%   |
| Huawei Technologies                    | 1        | 0.18%   |
| Google                                 | 1        | 0.18%   |
| DisplayLink                            | 1        | 0.18%   |
| D-Link System                          | 1        | 0.18%   |
| BUFFALO                                | 1        | 0.18%   |
| ASIX Electronics                       | 1        | 0.18%   |
| Arduino SA                             | 1        | 0.18%   |
| Apple                                  | 1        | 0.18%   |
| American Megatrends                    | 1        | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 163      | 25.43%  |
| Realtek RTL8125 2.5GbE Controller                                               | 27       | 4.21%   |
| Intel I211 Gigabit Network Connection                                           | 25       | 3.9%    |
| Intel Ethernet Controller I225-V                                                | 24       | 3.74%   |
| Intel Wi-Fi 6 AX200                                                             | 22       | 3.43%   |
| Intel I210 Gigabit Network Connection                                           | 11       | 1.72%   |
| Intel Ethernet Connection (2) I219-V                                            | 11       | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                | 11       | 1.72%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 10       | 1.56%   |
| Intel Ethernet Connection (7) I219-V                                            | 10       | 1.56%   |
| Ralink MT7601U Wireless Adapter                                                 | 9        | 1.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 9        | 1.4%    |
| Intel Ethernet Controller I226-V                                                | 7        | 1.09%   |
| Intel Ethernet Connection I217-LM                                               | 7        | 1.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 6        | 0.94%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 6        | 0.94%   |
| Intel Ethernet Connection I217-V                                                | 6        | 0.94%   |
| Intel Ethernet Connection (17) I219-V                                           | 6        | 0.94%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                | 6        | 0.94%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                      | 5        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                             | 5        | 0.78%   |
| Realtek 802.11ac NIC                                                            | 5        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 5        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                                           | 5        | 0.78%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                  | 5        | 0.78%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                  | 5        | 0.78%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 5        | 0.78%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]  | 5        | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 4        | 0.62%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 4        | 0.62%   |
| Intel 82574L Gigabit Network Connection                                         | 4        | 0.62%   |
| HTC (High Tech Computer) Desire HD (modem mode)                                 | 4        | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                 | 3        | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                 | 3        | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                           | 3        | 0.47%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller               | 3        | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                           | 3        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                        | 3        | 0.47%   |
| Nvidia MCP61 Ethernet                                                           | 3        | 0.47%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                         | 3        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 77       | 40.1%   |
| Realtek Semiconductor           | 34       | 17.71%  |
| Ralink Technology               | 14       | 7.29%   |
| MediaTek                        | 14       | 7.29%   |
| ASUSTek Computer                | 10       | 5.21%   |
| Edimax Technology               | 8        | 4.17%   |
| Broadcom                        | 7        | 3.65%   |
| TP-Link                         | 6        | 3.13%   |
| Qualcomm Atheros                | 4        | 2.08%   |
| D-Link                          | 3        | 1.56%   |
| Ralink                          | 2        | 1.04%   |
| Microsoft                       | 2        | 1.04%   |
| Mercucys                        | 2        | 1.04%   |
| ZyXEL Communications            | 1        | 0.52%   |
| Xiaomi                          | 1        | 0.52%   |
| Senao                           | 1        | 0.52%   |
| Qualcomm Technologies           | 1        | 0.52%   |
| Qualcomm Atheros Communications | 1        | 0.52%   |
| Qualcomm                        | 1        | 0.52%   |
| D-Link System                   | 1        | 0.52%   |
| BUFFALO                         | 1        | 0.52%   |
| Accton Technology               | 1        | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 22       | 11.06%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 11       | 5.53%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 10       | 5.03%   |
| Ralink MT7601U Wireless Adapter                                      | 9        | 4.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 6        | 3.02%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 6        | 3.02%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 5        | 2.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 5        | 2.51%   |
| Realtek 802.11ac NIC                                                 | 5        | 2.51%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 5        | 2.51%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 5        | 2.51%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]       | 5        | 2.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 4        | 2.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3        | 1.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3        | 1.51%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3        | 1.51%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3        | 1.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3        | 1.51%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 3        | 1.51%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 3        | 1.51%   |
| ASUS 802.11ac NIC                                                    | 3        | 1.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2        | 1.01%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2        | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2        | 1.01%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 2        | 1.01%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2        | 1.01%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 2        | 1.01%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                    | 2        | 1.01%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 2        | 1.01%   |
| Intel Wireless 8265 / 8275                                           | 2        | 1.01%   |
| Intel Wireless 3165                                                  | 2        | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2        | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2        | 1.01%   |
| Intel Alder Lake-N PCH CNVi WiFi                                     | 2        | 1.01%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]         | 1        | 0.5%    |
| Xiaomi MediaTek MT7601U [MI WiFi]                                    | 1        | 0.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1        | 0.5%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 1        | 0.5%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 0.5%    |
| TP-Link 802.11ac NIC                                                 | 1        | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 198      | 48.18%  |
| Intel                                  | 143      | 34.79%  |
| Qualcomm Atheros                       | 17       | 4.14%   |
| Aquantia                               | 13       | 3.16%   |
| Broadcom                               | 8        | 1.95%   |
| Marvell Technology Group               | 6        | 1.46%   |
| Nvidia                                 | 5        | 1.22%   |
| HTC (High Tech Computer)               | 4        | 0.97%   |
| TP-Link                                | 2        | 0.49%   |
| Samsung Electronics                    | 2        | 0.49%   |
| MediaTek                               | 2        | 0.49%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.24%   |
| OPPO Electronics                       | 1        | 0.24%   |
| Mellanox Technologies                  | 1        | 0.24%   |
| IBM                                    | 1        | 0.24%   |
| Huawei Technologies                    | 1        | 0.24%   |
| Google                                 | 1        | 0.24%   |
| DisplayLink                            | 1        | 0.24%   |
| ASIX Electronics                       | 1        | 0.24%   |
| Apple                                  | 1        | 0.24%   |
| American Megatrends                    | 1        | 0.24%   |
| 3Com                                   | 1        | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 163      | 37.39%  |
| Realtek RTL8125 2.5GbE Controller                                               | 27       | 6.19%   |
| Intel I211 Gigabit Network Connection                                           | 25       | 5.73%   |
| Intel Ethernet Controller I225-V                                                | 24       | 5.5%    |
| Intel I210 Gigabit Network Connection                                           | 11       | 2.52%   |
| Intel Ethernet Connection (2) I219-V                                            | 11       | 2.52%   |
| Intel Ethernet Connection (7) I219-V                                            | 10       | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 9        | 2.06%   |
| Intel Ethernet Controller I226-V                                                | 7        | 1.61%   |
| Intel Ethernet Connection I217-LM                                               | 7        | 1.61%   |
| Intel Ethernet Connection I217-V                                                | 6        | 1.38%   |
| Intel Ethernet Connection (17) I219-V                                           | 6        | 1.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 5        | 1.15%   |
| Intel Ethernet Connection (7) I219-LM                                           | 5        | 1.15%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 5        | 1.15%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]  | 5        | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 4        | 0.92%   |
| Intel 82574L Gigabit Network Connection                                         | 4        | 0.92%   |
| HTC (High Tech Computer) Desire HD (modem mode)                                 | 4        | 0.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                                           | 3        | 0.69%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller               | 3        | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                        | 3        | 0.69%   |
| Nvidia MCP61 Ethernet                                                           | 3        | 0.69%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                         | 3        | 0.69%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                         | 3        | 0.69%   |
| Intel Ethernet Connection (17) I219-LM                                          | 3        | 0.69%   |
| Intel Ethernet Connection (14) I219-V                                           | 3        | 0.69%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                            | 3        | 0.69%   |
| Intel 82579V Gigabit Network Connection                                         | 3        | 0.69%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]               | 3        | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 2        | 0.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 2        | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                       | 2        | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 2        | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                        | 2        | 0.46%   |
| MediaTek Infinix HOT 50i                                                        | 2        | 0.46%   |
| Intel I350 Gigabit Network Connection                                           | 2        | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                                           | 2        | 0.46%   |
| Intel Ethernet Connection (2) I218-V                                            | 2        | 0.46%   |
| Intel Ethernet Connection (11) I219-V                                           | 2        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 362      | 66.06%  |
| WiFi     | 180      | 32.85%  |
| Modem    | 5        | 0.91%   |
| Unknown  | 1        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 281      | 74.93%  |
| WiFi     | 94       | 25.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 189      | 51.08%  |
| 2     | 135      | 36.49%  |
| 3     | 28       | 7.57%   |
| 0     | 10       | 2.7%    |
| 4     | 5        | 1.35%   |
| 6     | 2        | 0.54%   |
| 10    | 1        | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 310      | 83.11%  |
| Yes  | 63       | 16.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 75       | 51.02%  |
| Cambridge Silicon Radio         | 22       | 14.97%  |
| MediaTek                        | 10       | 6.8%    |
| Realtek Semiconductor           | 9        | 6.12%   |
| IMC Networks                    | 6        | 4.08%   |
| ASUSTek Computer                | 6        | 4.08%   |
| Foxconn / Hon Hai               | 5        | 3.4%    |
| TP-Link                         | 3        | 2.04%   |
| Broadcom                        | 3        | 2.04%   |
| Apple                           | 3        | 2.04%   |
| Qualcomm Atheros Communications | 2        | 1.36%   |
| Ralink                          | 1        | 0.68%   |
| Mercucys                        | 1        | 0.68%   |
| Edimax Technology               | 1        | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 22       | 14.97%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 22       | 14.97%  |
| Intel AX201 Bluetooth                                 | 12       | 8.16%   |
| Intel Wireless-AC 3168 Bluetooth                      | 11       | 7.48%   |
| MediaTek Wireless_Device                              | 10       | 6.8%    |
| Realtek Bluetooth Radio                               | 8        | 5.44%   |
| Intel Bluetooth wireless interface                    | 8        | 5.44%   |
| Intel AX210 Bluetooth                                 | 8        | 5.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 6        | 4.08%   |
| Intel Bluetooth Device                                | 4        | 2.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 4        | 2.72%   |
| TP-Link TP-T@- UB500 Adapter                          | 3        | 2.04%   |
| Foxconn / Hon Hai Bluetooth Device                    | 3        | 2.04%   |
| ASUS Bluetooth Radio                                  | 3        | 2.04%   |
| IMC Networks Wireless_Device                          | 2        | 1.36%   |
| IMC Networks Bluetooth Radio                          | 2        | 1.36%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 1.36%   |
| ASUS ASUS USB-BT500                                   | 2        | 1.36%   |
| Apple Bluetooth Host Controller                       | 2        | 1.36%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 0.68%   |
| Ralink RT3290 Bluetooth                               | 1        | 0.68%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 0.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 0.68%   |
| Mercucys Mercusys MA530 Adapter                       | 1        | 0.68%   |
| IMC Networks Bluetooth Device                         | 1        | 0.68%   |
| IMC Networks BCM20702A0                               | 1        | 0.68%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 1        | 0.68%   |
| Foxconn / Hon Hai BCM43142A0                          | 1        | 0.68%   |
| Edimax Bluetooth Device                               | 1        | 0.68%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 0.68%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.68%   |
| Apple Bluetooth USB Host Controller                   | 1        | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 251      | 42.69%  |
| Nvidia                                       | 144      | 24.49%  |
| AMD                                          | 121      | 20.58%  |
| C-Media Electronics                          | 8        | 1.36%   |
| Texas Instruments                            | 6        | 1.02%   |
| Logitech                                     | 5        | 0.85%   |
| ASUSTek Computer                             | 5        | 0.85%   |
| Micro Star International                     | 4        | 0.68%   |
| Generalplus Technology                       | 4        | 0.68%   |
| XMOS                                         | 3        | 0.51%   |
| JMTek                                        | 3        | 0.51%   |
| SAVITECH                                     | 2        | 0.34%   |
| Realtek Semiconductor                        | 2        | 0.34%   |
| KORG                                         | 2        | 0.34%   |
| Giga-Byte Technology                         | 2        | 0.34%   |
| Focusrite-Novation                           | 2        | 0.34%   |
| Audio-Technica                               | 2        | 0.34%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.17%   |
| ZOOM                                         | 1        | 0.17%   |
| Yamaha                                       | 1        | 0.17%   |
| USB Audio                                    | 1        | 0.17%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.17%   |
| SteelSeries ApS                              | 1        | 0.17%   |
| Sony                                         | 1        | 0.17%   |
| RME                                          | 1        | 0.17%   |
| OPPO Electronics                             | 1        | 0.17%   |
| Novra/IDC/Wegener                            | 1        | 0.17%   |
| Microdia                                     | 1        | 0.17%   |
| Kingston Technology                          | 1        | 0.17%   |
| Harman                                       | 1        | 0.17%   |
| GN Netcom                                    | 1        | 0.17%   |
| Elite Silicon                                | 1        | 0.17%   |
| EDIFIER                                      | 1        | 0.17%   |
| Dell                                         | 1        | 0.17%   |
| Creative Technology                          | 1        | 0.17%   |
| Creative Labs                                | 1        | 0.17%   |
| Comtrue                                      | 1        | 0.17%   |
| AVerMedia Technologies                       | 1        | 0.17%   |
| 2.4G Composite Device                        | 1        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 35       | 5.12%   |
| AMD Ryzen HD Audio Controller                                              | 31       | 4.54%   |
| AMD Starship/Matisse HD Audio Controller                                   | 30       | 4.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 24       | 3.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 24       | 3.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 23       | 3.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21       | 3.07%   |
| Intel Alder Lake-S HD Audio Controller                                     | 20       | 2.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 18       | 2.64%   |
| Nvidia GP106 High Definition Audio Controller                              | 16       | 2.34%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15       | 2.2%    |
| Intel 200 Series PCH HD Audio                                              | 14       | 2.05%   |
| AMD Radeon High Definition Audio Controller                                | 13       | 1.9%    |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 12       | 1.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 11       | 1.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 11       | 1.61%   |
| Nvidia GP108 High Definition Audio Controller                              | 10       | 1.46%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 10       | 1.46%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10       | 1.46%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 9        | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 1.17%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8        | 1.17%   |
| Nvidia GF116 High Definition Audio Controller                              | 7        | 1.02%   |
| Nvidia GA106 High Definition Audio Controller                              | 7        | 1.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7        | 1.02%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 7        | 1.02%   |
| AMD FCH Azalia Controller                                                  | 7        | 1.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 1.02%   |
| Nvidia MCP61 High Definition Audio                                         | 6        | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 0.88%   |
| Nvidia GA102 High Definition Audio Controller                              | 6        | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 0.88%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6        | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 0.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 0.73%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 47       | 19.34%  |
| Crucial             | 41       | 16.87%  |
| Transcend           | 22       | 9.05%   |
| Unknown             | 21       | 8.64%   |
| A-DATA Technology   | 20       | 8.23%   |
| Samsung Electronics | 19       | 7.82%   |
| Micron Technology   | 16       | 6.58%   |
| SK hynix            | 14       | 5.76%   |
| G.Skill             | 6        | 2.47%   |
| Unknown             | 6        | 2.47%   |
| Team                | 4        | 1.65%   |
| Unifosa             | 3        | 1.23%   |
| Silicon Power       | 3        | 1.23%   |
| Patriot             | 3        | 1.23%   |
| KLEVV               | 2        | 0.82%   |
| ASint Technology    | 2        | 0.82%   |
| Apacer              | 2        | 0.82%   |
| V-Color             | 1        | 0.41%   |
| Unknown (09A4)      | 1        | 0.41%   |
| UMAX                | 1        | 0.41%   |
| Red Hat             | 1        | 0.41%   |
| Ramaxel Technology  | 1        | 0.41%   |
| Nanya Technology    | 1        | 0.41%   |
| GLOWAY              | 1        | 0.41%   |
| Essencore Limited   | 1        | 0.41%   |
| CUSO                | 1        | 0.41%   |
| Corsair             | 1        | 0.41%   |
| Advantech           | 1        | 0.41%   |
| ACPI Digital        | 1        | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown                                                   | 6        | 2.32%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s       | 4        | 1.54%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s          | 3        | 1.16%   |
| Transcend RAM Module 4GB DIMM DDR3 1600MT/s               | 3        | 1.16%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM 1600MT/s          | 3        | 1.16%   |
| A-DATA RAM Module 4096MB SODIMM DDR4 2400MT/s             | 3        | 1.16%   |
| A-DATA RAM DDR4 3000 2OZ 8GB DIMM DDR4 3000MT/s           | 3        | 1.16%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 2        | 0.77%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s         | 2        | 0.77%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s        | 2        | 0.77%   |
| SK hynix RAM HMA82GU6MFR8N-TF 16GB DIMM DDR4 2133MT/s     | 2        | 0.77%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s      | 2        | 0.77%   |
| Silicon Power RAM SP008GBLTU160N02 8GB DIMM DDR3 1600MT/s | 2        | 0.77%   |
| Samsung RAM M393A2G40DB1-CRC 16GB DIMM DDR4 2400MT/s      | 2        | 0.77%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s           | 2        | 0.77%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s        | 2        | 0.77%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 2        | 0.77%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1867MT/s       | 2        | 0.77%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s     | 2        | 0.77%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s    | 2        | 0.77%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 3600MT/s      | 2        | 0.77%   |
| Crucial RAM CT32G4DFD832A.C16FE 32GB DIMM DDR4 3200MT/s   | 2        | 0.77%   |
| Crucial RAM BL16G36C16U4W.M16FE1 16GB DIMM DDR4 3733MT/s  | 2        | 0.77%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                  | 2        | 0.77%   |
| V-Color RAM TD4G8C11-H11 4GB DIMM DDR3 1600MT/s           | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                 | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM 667MT/s                       | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM                               | 1        | 0.39%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s              | 1        | 0.39%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                   | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                      | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 0.39%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 1        | 0.39%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                  | 1        | 0.39%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 1        | 0.39%   |
| Unknown RAM Module 2GB DIMM 667MT/s                       | 1        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 115      | 53.24%  |
| DDR3    | 57       | 26.39%  |
| DDR5    | 19       | 8.8%    |
| Unknown | 13       | 6.02%   |
| DDR2    | 6        | 2.78%   |
| SDRAM   | 4        | 1.85%   |
| RAM     | 1        | 0.46%   |
| DDR     | 1        | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 186      | 86.11%  |
| SODIMM | 29       | 13.43%  |
| RIMM   | 1        | 0.46%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 76       | 33.63%  |
| 16384 | 66       | 29.2%   |
| 4096  | 33       | 14.6%   |
| 32768 | 26       | 11.5%   |
| 2048  | 20       | 8.85%   |
| 1024  | 2        | 0.88%   |
| 98304 | 1        | 0.44%   |
| 65536 | 1        | 0.44%   |
| 9000  | 1        | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 45       | 18.99%  |
| 3200    | 41       | 17.3%   |
| 2667    | 20       | 8.44%   |
| 2400    | 17       | 7.17%   |
| 1333    | 16       | 6.75%   |
| 2133    | 13       | 5.49%   |
| 3600    | 10       | 4.22%   |
| 3733    | 7        | 2.95%   |
| 4800    | 6        | 2.53%   |
| 800     | 6        | 2.53%   |
| 3000    | 5        | 2.11%   |
| 6000    | 4        | 1.69%   |
| 5600    | 4        | 1.69%   |
| 4000    | 4        | 1.69%   |
| 3800    | 3        | 1.27%   |
| 2933    | 3        | 1.27%   |
| 667     | 3        | 1.27%   |
| 5200    | 2        | 0.84%   |
| 3466    | 2        | 0.84%   |
| 2666    | 2        | 0.84%   |
| 1334    | 2        | 0.84%   |
| 1066    | 2        | 0.84%   |
| Unknown | 2        | 0.84%   |
| 6400    | 1        | 0.42%   |
| 6200    | 1        | 0.42%   |
| 5800    | 1        | 0.42%   |
| 4333    | 1        | 0.42%   |
| 3866    | 1        | 0.42%   |
| 3400    | 1        | 0.42%   |
| 3334    | 1        | 0.42%   |
| 3333    | 1        | 0.42%   |
| 3134    | 1        | 0.42%   |
| 2866    | 1        | 0.42%   |
| 2448    | 1        | 0.42%   |
| 2000    | 1        | 0.42%   |
| 1867    | 1        | 0.42%   |
| 1800    | 1        | 0.42%   |
| 1632    | 1        | 0.42%   |
| 1067    | 1        | 0.42%   |
| 533     | 1        | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 66.67%  |
| Seiko Epson         | 1        | 16.67%  |
| Prolific Technology | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seiko Epson XP-240 Series        | 1        | 16.67%  |
| Prolific PL2305 Parallel Port    | 1        | 16.67%  |
| HP LaserJet Professional P1102w  | 1        | 16.67%  |
| HP LaserJet Professional P 1102w | 1        | 16.67%  |
| HP LaserJet M402dn               | 1        | 16.67%  |
| HP LaserJet 1020                 | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Seiko Epson Perfection V37/V370                               | 1        | 50%     |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 15       | 48.39%  |
| Microdia                      | 3        | 9.68%   |
| Generalplus Technology        | 3        | 9.68%   |
| Sunplus Innovation Technology | 2        | 6.45%   |
| Unison                        | 1        | 3.23%   |
| Samsung Electronics           | 1        | 3.23%   |
| Realtek Semiconductor         | 1        | 3.23%   |
| MacroSilicon                  | 1        | 3.23%   |
| KYE Systems (Mouse Systems)   | 1        | 3.23%   |
| eMeet                         | 1        | 3.23%   |
| Apple                         | 1        | 3.23%   |
| A4Tech                        | 1        | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 5        | 16.13%  |
| Logitech Webcam C120                            | 3        | 9.68%   |
| Logitech Webcam C930e                           | 2        | 6.45%   |
| Generalplus GENERAL WEBCAM                      | 2        | 6.45%   |
| Unison Webcam 2M                                | 1        | 3.23%   |
| Sunplus HanChen Wise Camera                     | 1        | 3.23%   |
| Sunplus ezcap U3 capture-04                     | 1        | 3.23%   |
| Samsung Galaxy series, misc. (MTP mode)         | 1        | 3.23%   |
| Realtek Bluetooth Radio                         | 1        | 3.23%   |
| Microdia USB 2.0 Camera                         | 1        | 3.23%   |
| Microdia Rapoo Camera                           | 1        | 3.23%   |
| Microdia Integrated Camera                      | 1        | 3.23%   |
| MacroSilicon USB Video                          | 1        | 3.23%   |
| Logitech Webcam C170                            | 1        | 3.23%   |
| Logitech QuickCam Sphere                        | 1        | 3.23%   |
| Logitech QuickCam Home                          | 1        | 3.23%   |
| Logitech QuickCam E 3500                        | 1        | 3.23%   |
| Logitech HD Pro Webcam C920                     | 1        | 3.23%   |
| KYE Systems (Mouse Systems) Genius WideCam F100 | 1        | 3.23%   |
| Generalplus 808 Camera #9 (web-cam mode)        | 1        | 3.23%   |
| eMeet HD Webcam C960                            | 1        | 3.23%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                 | 1        | 3.23%   |
| A4Tech FHD 1080P PC Camera                      | 1        | 3.23%   |

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
| 0     | 300      | 79.58%  |
| 1     | 61       | 16.18%  |
| 2     | 10       | 2.65%   |
| 3     | 3        | 0.8%    |
| 5     | 2        | 0.53%   |
| 4     | 1        | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 31       | 34.83%  |
| Net/wireless             | 21       | 23.6%   |
| Unassigned class         | 13       | 14.61%  |
| Communication controller | 7        | 7.87%   |
| Net/ethernet             | 4        | 4.49%   |
| Card reader              | 3        | 3.37%   |
| Storage/raid             | 2        | 2.25%   |
| Sound                    | 2        | 2.25%   |
| Multimedia controller    | 2        | 2.25%   |
| Bluetooth                | 2        | 2.25%   |
| Network                  | 1        | 1.12%   |
| Camera                   | 1        | 1.12%   |

