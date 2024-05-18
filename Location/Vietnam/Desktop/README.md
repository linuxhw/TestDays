Linux in Vietnam - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Vietnam.

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

Total: 219

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| AZW           | MINI S 10                   | [ae2d077638](https://linux-hardware.org/?probe=ae2d077638) | Apr 22, 2024 |
| Gigabyte      | Z490 UD                     | [09c22645d8](https://linux-hardware.org/?probe=09c22645d8) | Apr 19, 2024 |
| MSI           | Z390-A PRO                  | [5357679252](https://linux-hardware.org/?probe=5357679252) | Apr 18, 2024 |
| Dell          | 0D28YY A03                  | [894b628494](https://linux-hardware.org/?probe=894b628494) | Apr 12, 2024 |
| MSI           | Z390-A PRO                  | [1c61456dc2](https://linux-hardware.org/?probe=1c61456dc2) | Apr 11, 2024 |
| MSI           | Z390-A PRO                  | [bbb0e8daf4](https://linux-hardware.org/?probe=bbb0e8daf4) | Apr 02, 2024 |
| Gigabyte      | Z490 UD                     | [d60c1ed904](https://linux-hardware.org/?probe=d60c1ed904) | Apr 02, 2024 |
| ASUSTek       | PRIME B250M-A               | [5d12c5c26e](https://linux-hardware.org/?probe=5d12c5c26e) | Mar 31, 2024 |
| ASUSTek       | PRIME B250M-A               | [142a42435b](https://linux-hardware.org/?probe=142a42435b) | Mar 30, 2024 |
| MSI           | H310M PRO-VDH PLUS          | [99e78f54fd](https://linux-hardware.org/?probe=99e78f54fd) | Mar 18, 2024 |
| Gigabyte      | H61M-DS2                    | [af8cc61afe](https://linux-hardware.org/?probe=af8cc61afe) | Mar 14, 2024 |
| Gigabyte      | H61M-DS2                    | [ba3ec85a8c](https://linux-hardware.org/?probe=ba3ec85a8c) | Mar 14, 2024 |
| ASUSTek       | H81M-E                      | [17ef9e97c9](https://linux-hardware.org/?probe=17ef9e97c9) | Mar 06, 2024 |
| ASUSTek       | PRIME H510M-F               | [21e4b5ffeb](https://linux-hardware.org/?probe=21e4b5ffeb) | Feb 20, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [efd4bd356f](https://linux-hardware.org/?probe=efd4bd356f) | Feb 17, 2024 |
| Dell          | 0NW6H5 A00                  | [ac9d05a0b5](https://linux-hardware.org/?probe=ac9d05a0b5) | Jan 30, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | [61d19fb0bc](https://linux-hardware.org/?probe=61d19fb0bc) | Jan 29, 2024 |
| Gigabyte      | Z490 UD                     | [41cff556c1](https://linux-hardware.org/?probe=41cff556c1) | Jan 29, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0996781568](https://linux-hardware.org/?probe=0996781568) | Jan 21, 2024 |
| Supermicro    | X10DRL-i                    | [874482c96c](https://linux-hardware.org/?probe=874482c96c) | Jan 10, 2024 |
| Supermicro    | X10DRL-i                    | [d51207de50](https://linux-hardware.org/?probe=d51207de50) | Jan 09, 2024 |
| MSI           | Z390-A PRO                  | [bde414f757](https://linux-hardware.org/?probe=bde414f757) | Jan 09, 2024 |
| Gigabyte      | Z490 UD                     | [764d37dd86](https://linux-hardware.org/?probe=764d37dd86) | Jan 05, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | [4254a865ee](https://linux-hardware.org/?probe=4254a865ee) | Jan 04, 2024 |
| Gigabyte      | Z490 UD                     | [939fe5ab0c](https://linux-hardware.org/?probe=939fe5ab0c) | Jan 02, 2024 |
| Gigabyte      | Z490 UD                     | [e0aa5cc2d1](https://linux-hardware.org/?probe=e0aa5cc2d1) | Dec 29, 2023 |
| Unknown       | Unknown                     | [a97c12a4c8](https://linux-hardware.org/?probe=a97c12a4c8) | Dec 28, 2023 |
| MSI           | Z390-A PRO                  | [555b9489dd](https://linux-hardware.org/?probe=555b9489dd) | Dec 27, 2023 |
| MSI           | Z390-A PRO                  | [27856e6bb2](https://linux-hardware.org/?probe=27856e6bb2) | Dec 27, 2023 |
| MSI           | Z490-A PRO                  | [9440079733](https://linux-hardware.org/?probe=9440079733) | Dec 27, 2023 |
| HP            | 86E9 A                      | [e373d2be5d](https://linux-hardware.org/?probe=e373d2be5d) | Dec 27, 2023 |
| MSI           | B150M MORTAR                | [c179cdb6dc](https://linux-hardware.org/?probe=c179cdb6dc) | Dec 27, 2023 |
| Gigabyte      | B75M-D3H                    | [c7a5f771ce](https://linux-hardware.org/?probe=c7a5f771ce) | Dec 26, 2023 |
| MSI           | B150M MORTAR                | [23577ab5f1](https://linux-hardware.org/?probe=23577ab5f1) | Dec 26, 2023 |
| HP            | 86E9 A                      | [c13adc0c5e](https://linux-hardware.org/?probe=c13adc0c5e) | Dec 26, 2023 |
| Gigabyte      | Z490 UD                     | [09813a10ac](https://linux-hardware.org/?probe=09813a10ac) | Dec 26, 2023 |
| Gigabyte      | A320M-S2H-CF                | [74cbcabaa1](https://linux-hardware.org/?probe=74cbcabaa1) | Dec 17, 2023 |
| ZOTAC         | Unknown                     | [a91d567af3](https://linux-hardware.org/?probe=a91d567af3) | Dec 14, 2023 |
| Gigabyte      | A320M-S2H-CF                | [5a7d45a007](https://linux-hardware.org/?probe=5a7d45a007) | Dec 05, 2023 |
| Gigabyte      | A320M-S2H-CF                | [2d6eaf642b](https://linux-hardware.org/?probe=2d6eaf642b) | Dec 05, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [52374a1dea](https://linux-hardware.org/?probe=52374a1dea) | Dec 03, 2023 |
| Gigabyte      | H310M DS2                   | [14a8656c8b](https://linux-hardware.org/?probe=14a8656c8b) | Nov 28, 2023 |
| HP            | 212B                        | [90bc0d4d2d](https://linux-hardware.org/?probe=90bc0d4d2d) | Nov 25, 2023 |
| Intel         | X99                         | [cb3515efba](https://linux-hardware.org/?probe=cb3515efba) | Nov 03, 2023 |
| Gigabyte      | AX370M-Gaming 3-CF          | [3e5415671f](https://linux-hardware.org/?probe=3e5415671f) | Nov 01, 2023 |
| MSI           | A320M PRO-M2 V2             | [9854f25018](https://linux-hardware.org/?probe=9854f25018) | Oct 26, 2023 |
| MSI           | B450M MORTAR MAX            | [824215ab50](https://linux-hardware.org/?probe=824215ab50) | Oct 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | [62ca63bc89](https://linux-hardware.org/?probe=62ca63bc89) | Oct 23, 2023 |
| Dell          | 0NW6H5 A00                  | [2b88710042](https://linux-hardware.org/?probe=2b88710042) | Oct 22, 2023 |
| Dell          | 0NW6H5 A00                  | [a7f899353b](https://linux-hardware.org/?probe=a7f899353b) | Oct 21, 2023 |
| ASUSTek       | H81M-K                      | [0875e69e22](https://linux-hardware.org/?probe=0875e69e22) | Oct 17, 2023 |
| Gigabyte      | H81M-DS2                    | [9240952796](https://linux-hardware.org/?probe=9240952796) | Oct 16, 2023 |
| MSI           | B450I GAMING PLUS AC        | [b1ff58e369](https://linux-hardware.org/?probe=b1ff58e369) | Oct 10, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [3e29eb1d63](https://linux-hardware.org/?probe=3e29eb1d63) | Sep 26, 2023 |
| ASRock        | A320M-HDV                   | [2beb623746](https://linux-hardware.org/?probe=2beb623746) | Sep 26, 2023 |
| ASUSTek       | EX-H110M-V3                 | [c38af5d04d](https://linux-hardware.org/?probe=c38af5d04d) | Aug 31, 2023 |
| ASUSTek       | EX-H110M-V3                 | [e2b97e4436](https://linux-hardware.org/?probe=e2b97e4436) | Aug 31, 2023 |
| GuoGuang      | IC2M1028N                   | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [a01053a59a](https://linux-hardware.org/?probe=a01053a59a) | Jul 15, 2023 |
| Dell          | 051FJ8 A02                  | [d8310de68b](https://linux-hardware.org/?probe=d8310de68b) | Jul 12, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7aaa5d2eec](https://linux-hardware.org/?probe=7aaa5d2eec) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ef49f25cf8](https://linux-hardware.org/?probe=ef49f25cf8) | Jun 30, 2023 |
| ZOTAC         | Unknown                     | [8454119675](https://linux-hardware.org/?probe=8454119675) | Jun 22, 2023 |
| Lenovo        | MAHOBAY                     | [ebedbde736](https://linux-hardware.org/?probe=ebedbde736) | Jun 16, 2023 |
| Gigabyte      | Z370M D3H-CF                | [d704e4a5d3](https://linux-hardware.org/?probe=d704e4a5d3) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | [b3303b8ed6](https://linux-hardware.org/?probe=b3303b8ed6) | Jun 13, 2023 |
| GuoGuang      | IC2M1028V-J                 | [d7c1b01b69](https://linux-hardware.org/?probe=d7c1b01b69) | Jun 10, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bf2fc7d3b7](https://linux-hardware.org/?probe=bf2fc7d3b7) | Jun 08, 2023 |
| GuoGuang      | IC2M1028V-J                 | [04527d6ad9](https://linux-hardware.org/?probe=04527d6ad9) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [4ecbee26b1](https://linux-hardware.org/?probe=4ecbee26b1) | May 04, 2023 |
| Dell          | 08WKV3 A00                  | [ed0486cda1](https://linux-hardware.org/?probe=ed0486cda1) | May 03, 2023 |
| T-bao         | MINI PC V1.0                | [8e77950434](https://linux-hardware.org/?probe=8e77950434) | Apr 30, 2023 |
| ASRock        | B550M Pro4                  | [b53354af62](https://linux-hardware.org/?probe=b53354af62) | Apr 25, 2023 |
| Intel         | H81                         | [fbc2766f35](https://linux-hardware.org/?probe=fbc2766f35) | Apr 22, 2023 |
| HP            | 1825                        | [e586a2657b](https://linux-hardware.org/?probe=e586a2657b) | Apr 21, 2023 |
| Unknown       | Unknown                     | [c67c78ba10](https://linux-hardware.org/?probe=c67c78ba10) | Apr 11, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [ca1cdc7f46](https://linux-hardware.org/?probe=ca1cdc7f46) | Apr 06, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [6844d471e4](https://linux-hardware.org/?probe=6844d471e4) | Apr 02, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [d7b27c1822](https://linux-hardware.org/?probe=d7b27c1822) | Mar 19, 2023 |
| ASUSTek       | PRIME B450M-A               | [dee1b60a0d](https://linux-hardware.org/?probe=dee1b60a0d) | Mar 07, 2023 |
| ASRock        | H61M-VS                     | [04d5b9593e](https://linux-hardware.org/?probe=04d5b9593e) | Feb 28, 2023 |
| ASUSTek       | PRIME B450M-A               | [373f4f8123](https://linux-hardware.org/?probe=373f4f8123) | Feb 27, 2023 |
| ASUSTek       | PRIME H510M-K               | [5fb951a350](https://linux-hardware.org/?probe=5fb951a350) | Feb 21, 2023 |
| MSI           | H410M PRO-VH                | [669d124e33](https://linux-hardware.org/?probe=669d124e33) | Feb 21, 2023 |
| MSI           | H410M PRO-VH                | [ccc1cbf2fa](https://linux-hardware.org/?probe=ccc1cbf2fa) | Feb 18, 2023 |
| ASUSTek       | EX-H310M-V3 R2.0            | [d42c40dd2e](https://linux-hardware.org/?probe=d42c40dd2e) | Feb 16, 2023 |
| ASUSTek       | P5QPL-AM                    | [a3b4daa09d](https://linux-hardware.org/?probe=a3b4daa09d) | Feb 16, 2023 |
| HP            | 81B4                        | [01229ad5ec](https://linux-hardware.org/?probe=01229ad5ec) | Jan 29, 2023 |
| Gigabyte      | B360M D3H-CF                | [b7971f413f](https://linux-hardware.org/?probe=b7971f413f) | Jan 06, 2023 |
| HP            | 158A                        | [c80bfd7c30](https://linux-hardware.org/?probe=c80bfd7c30) | Dec 28, 2022 |
| Gigabyte      | B360M D3H-CF                | [fed4383ac0](https://linux-hardware.org/?probe=fed4383ac0) | Dec 18, 2022 |
| ASUSTek       | PRIME H410M-E               | [cb7bfc231e](https://linux-hardware.org/?probe=cb7bfc231e) | Dec 15, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [324b5a49e4](https://linux-hardware.org/?probe=324b5a49e4) | Nov 22, 2022 |
| Gigabyte      | H110M-DS2-CF                | [4adf740f59](https://linux-hardware.org/?probe=4adf740f59) | Nov 15, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| HP            | 212B                        | [adf4c58f4c](https://linux-hardware.org/?probe=adf4c58f4c) | Oct 22, 2022 |
| Gigabyte      | B360M DS3H                  | [ca57bb441c](https://linux-hardware.org/?probe=ca57bb441c) | Oct 18, 2022 |
| HP            | 158A                        | [6b1d53174a](https://linux-hardware.org/?probe=6b1d53174a) | Oct 12, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4... | [080242408d](https://linux-hardware.org/?probe=080242408d) | Oct 11, 2022 |
| Gigabyte      | H170M-D3H-CF                | [1bff176b39](https://linux-hardware.org/?probe=1bff176b39) | Oct 05, 2022 |
| HP            | 158A                        | [428326af76](https://linux-hardware.org/?probe=428326af76) | Sep 21, 2022 |
| Gigabyte      | X570 UD                     | [7e840fc9d0](https://linux-hardware.org/?probe=7e840fc9d0) | Sep 12, 2022 |
| Dell          | 0VNM11 A00                  | [9ae0ae5ac4](https://linux-hardware.org/?probe=9ae0ae5ac4) | Sep 10, 2022 |
| Gigabyte      | H110M-DS2-CF                | [ecc2f4c975](https://linux-hardware.org/?probe=ecc2f4c975) | Sep 06, 2022 |
| MSI           | H410M PRO                   | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| HP            | 18E7                        | [9344f12eea](https://linux-hardware.org/?probe=9344f12eea) | Aug 31, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [46c6096b6e](https://linux-hardware.org/?probe=46c6096b6e) | Aug 23, 2022 |
| Gigabyte      | B450M GAMING                | [a3d9fca7aa](https://linux-hardware.org/?probe=a3d9fca7aa) | Aug 16, 2022 |
| HP            | 2AE2                        | [1fd0bb70dc](https://linux-hardware.org/?probe=1fd0bb70dc) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| HP            | 8455                        | [62b146bca0](https://linux-hardware.org/?probe=62b146bca0) | Jul 08, 2022 |
| Gigabyte      | H61M-DS2                    | [09ba129a3b](https://linux-hardware.org/?probe=09ba129a3b) | May 25, 2022 |
| Foxconn       | H61MD/H61MD-V               | [25b52955ee](https://linux-hardware.org/?probe=25b52955ee) | Apr 29, 2022 |
| Foxconn       | H61MD/H61MD-V               | [7bb124e322](https://linux-hardware.org/?probe=7bb124e322) | Apr 06, 2022 |
| Wistron       | JIG31B3                     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| Foxconn       | 2ADA                        | [64f5921b5b](https://linux-hardware.org/?probe=64f5921b5b) | Feb 13, 2022 |
| Gigabyte      | B85M-DS3H                   | [be7876abf4](https://linux-hardware.org/?probe=be7876abf4) | Jan 05, 2022 |
| Gigabyte      | B75M-D3H                    | [1524f751eb](https://linux-hardware.org/?probe=1524f751eb) | Dec 24, 2021 |
| ASUSTek       | P8H61-MX                    | [cee5f081e3](https://linux-hardware.org/?probe=cee5f081e3) | Dec 19, 2021 |
| ASUSTek       | P8H61-MX                    | [297d964b96](https://linux-hardware.org/?probe=297d964b96) | Dec 18, 2021 |
| MSI           | MAG B365M MORTAR            | [bd72de2067](https://linux-hardware.org/?probe=bd72de2067) | Dec 12, 2021 |
| ASUSTek       | H81M-K                      | [412accf186](https://linux-hardware.org/?probe=412accf186) | Dec 09, 2021 |
| ASUSTek       | PRIME Z370-P                | [fa62ac7a45](https://linux-hardware.org/?probe=fa62ac7a45) | Nov 23, 2021 |
| ASUSTek       | P8H61-MX R2.0               | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| MSI           | B450M MORTAR MAX            | [84c316ee57](https://linux-hardware.org/?probe=84c316ee57) | Nov 08, 2021 |
| Gigabyte      | H61M-DS2                    | [042607d7f1](https://linux-hardware.org/?probe=042607d7f1) | Oct 31, 2021 |
| Gigabyte      | H61M-DS2                    | [11527ae3f9](https://linux-hardware.org/?probe=11527ae3f9) | Oct 31, 2021 |
| Gigabyte      | G31MF-S2                    | [370ad865cf](https://linux-hardware.org/?probe=370ad865cf) | Oct 31, 2021 |
| Gigabyte      | B450M GAMING                | [f316c0a82e](https://linux-hardware.org/?probe=f316c0a82e) | Oct 25, 2021 |
| Gigabyte      | EP43T-S3L                   | [8a1adefcb3](https://linux-hardware.org/?probe=8a1adefcb3) | Oct 20, 2021 |
| Gigabyte      | G31MF-S2                    | [7459a9ed47](https://linux-hardware.org/?probe=7459a9ed47) | Oct 18, 2021 |
| ASUSTek       | PRIME X370-PRO              | [8b3b2655bb](https://linux-hardware.org/?probe=8b3b2655bb) | Oct 03, 2021 |
| Gigabyte      | G1.Sniper B5-CF             | [886b00678b](https://linux-hardware.org/?probe=886b00678b) | Aug 09, 2021 |
| ASUSTek       | PRIME B250M-K               | [10c0149671](https://linux-hardware.org/?probe=10c0149671) | Jul 17, 2021 |
| Gigabyte      | H61M-DS2                    | [894db66628](https://linux-hardware.org/?probe=894db66628) | Jul 05, 2021 |
| Gigabyte      | P110-D3-CF                  | [37aab1ae76](https://linux-hardware.org/?probe=37aab1ae76) | Jun 29, 2021 |
| Colorful T... | C.A68M-BTC YV14             | [9b6c7d9e82](https://linux-hardware.org/?probe=9b6c7d9e82) | Jun 23, 2021 |
| Huanan        | X79 249PC V2.1              | [b6fd95e48e](https://linux-hardware.org/?probe=b6fd95e48e) | Jun 15, 2021 |
| MSI           | B365M PRO-VH                | [ea30bb632e](https://linux-hardware.org/?probe=ea30bb632e) | Jun 10, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [428cb5bb99](https://linux-hardware.org/?probe=428cb5bb99) | Jun 05, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [38acf36fce](https://linux-hardware.org/?probe=38acf36fce) | Jun 05, 2021 |
| ASUSTek       | P7H55-M LX                  | [4401c591ee](https://linux-hardware.org/?probe=4401c591ee) | Jun 01, 2021 |
| ASUSTek       | P7H55-M LX                  | [f1d33c68f6](https://linux-hardware.org/?probe=f1d33c68f6) | Jun 01, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [35c74e640b](https://linux-hardware.org/?probe=35c74e640b) | May 31, 2021 |
| ASUSTek       | PRIME H110M-P               | [63effde8c3](https://linux-hardware.org/?probe=63effde8c3) | May 08, 2021 |
| ASUSTek       | PRIME H110M-P               | [99ac06d5e2](https://linux-hardware.org/?probe=99ac06d5e2) | May 08, 2021 |
| ASUSTek       | B75M-A                      | [2fabbbebb9](https://linux-hardware.org/?probe=2fabbbebb9) | Apr 29, 2021 |
| ASUSTek       | B75M-A                      | [23cc5c25c3](https://linux-hardware.org/?probe=23cc5c25c3) | Apr 29, 2021 |
| ASRock        | G41M-VS3                    | [599315872a](https://linux-hardware.org/?probe=599315872a) | Apr 24, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [c941a697c2](https://linux-hardware.org/?probe=c941a697c2) | Apr 22, 2021 |
| MSI           | B450M MORTAR MAX            | [e55472cf5f](https://linux-hardware.org/?probe=e55472cf5f) | Apr 18, 2021 |
| MSI           | B450M PRO-VDH MAX           | [abf17f0c92](https://linux-hardware.org/?probe=abf17f0c92) | Apr 17, 2021 |
| Gigabyte      | MZBAYAP-00                  | [cdfb323202](https://linux-hardware.org/?probe=cdfb323202) | Apr 04, 2021 |
| Dell          | 04Y8V0 A02                  | [241289046a](https://linux-hardware.org/?probe=241289046a) | Mar 16, 2021 |
| Gigabyte      | Z390 UD                     | [d56654c11c](https://linux-hardware.org/?probe=d56654c11c) | Mar 12, 2021 |
| Dell          | 088DT1 A01                  | [d1bd158872](https://linux-hardware.org/?probe=d1bd158872) | Mar 10, 2021 |
| Dell          | 088DT1 A01                  | [9e8527b842](https://linux-hardware.org/?probe=9e8527b842) | Mar 05, 2021 |
| Gigabyte      | H81M-DS2                    | [96fd52e1f2](https://linux-hardware.org/?probe=96fd52e1f2) | Mar 02, 2021 |
| Gigabyte      | B450M GAMING                | [bb980a20ea](https://linux-hardware.org/?probe=bb980a20ea) | Feb 18, 2021 |
| ASUSTek       | EB1036                      | [d77c773bc7](https://linux-hardware.org/?probe=d77c773bc7) | Feb 17, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | [e9acf54209](https://linux-hardware.org/?probe=e9acf54209) | Jan 15, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | [d462b4ca25](https://linux-hardware.org/?probe=d462b4ca25) | Jan 12, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | [8ae2ef5b3b](https://linux-hardware.org/?probe=8ae2ef5b3b) | Jan 07, 2021 |
| MSI           | Z390-A PRO                  | [4a11009c6f](https://linux-hardware.org/?probe=4a11009c6f) | Jan 06, 2021 |
| ASUSTek       | B75M-A                      | [cf3d073aae](https://linux-hardware.org/?probe=cf3d073aae) | Jan 06, 2021 |
| Intel         | DP55WG AAE57269-407         | [8b549321e4](https://linux-hardware.org/?probe=8b549321e4) | Dec 31, 2020 |
| Gigabyte      | G41M-ES2L                   | [540115f336](https://linux-hardware.org/?probe=540115f336) | Dec 28, 2020 |
| Gigabyte      | F2A68HM-HD2                 | [2e581b986a](https://linux-hardware.org/?probe=2e581b986a) | Dec 28, 2020 |
| Gigabyte      | G41M-ES2L                   | [cd0b939f13](https://linux-hardware.org/?probe=cd0b939f13) | Dec 27, 2020 |
| HP            | 158A                        | [9c309002d1](https://linux-hardware.org/?probe=9c309002d1) | Dec 10, 2020 |
| HP            | 2B2C                        | [ffd83f6d60](https://linux-hardware.org/?probe=ffd83f6d60) | Dec 08, 2020 |
| HP            | 158A                        | [eaab601c40](https://linux-hardware.org/?probe=eaab601c40) | Dec 02, 2020 |
| HP            | 158A                        | [64320f7764](https://linux-hardware.org/?probe=64320f7764) | Dec 02, 2020 |
| MSI           | Z390-A PRO                  | [318f172f36](https://linux-hardware.org/?probe=318f172f36) | Oct 27, 2020 |
| ASUSTek       | SABERTOOTH Z77              | [bcc1019568](https://linux-hardware.org/?probe=bcc1019568) | Oct 07, 2020 |
| Dell          | 0215PR A02                  | [a37475889b](https://linux-hardware.org/?probe=a37475889b) | Oct 03, 2020 |
| Koloe         | X58                         | [81d474ab62](https://linux-hardware.org/?probe=81d474ab62) | Sep 20, 2020 |
| ASUSTek       | Z10PE-D8 WS                 | [55e8990643](https://linux-hardware.org/?probe=55e8990643) | Sep 17, 2020 |
| Unknown       | SKYBAY                      | [190c1e6486](https://linux-hardware.org/?probe=190c1e6486) | Aug 31, 2020 |
| Unknown       | SKYBAY                      | [889530c9b1](https://linux-hardware.org/?probe=889530c9b1) | Aug 28, 2020 |
| Unknown       | SKYBAY                      | [01f13cc1c7](https://linux-hardware.org/?probe=01f13cc1c7) | Aug 25, 2020 |
| Dell          | 0200DY A02                  | [dc862d439b](https://linux-hardware.org/?probe=dc862d439b) | Aug 24, 2020 |
| MSI           | B85M Night Elf              | [d9fe6d88cd](https://linux-hardware.org/?probe=d9fe6d88cd) | Aug 14, 2020 |
| HP            | 2B2C                        | [ed031034e8](https://linux-hardware.org/?probe=ed031034e8) | Jul 18, 2020 |
| HP            | 2B2C                        | [dd85e7a5e1](https://linux-hardware.org/?probe=dd85e7a5e1) | Jul 18, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [601726ae15](https://linux-hardware.org/?probe=601726ae15) | Jul 01, 2020 |
| ASUSTek       | A68HM-K                     | [7fc608d8c2](https://linux-hardware.org/?probe=7fc608d8c2) | Jun 21, 2020 |
| MSI           | B85M Night Elf              | [f223bc5b5e](https://linux-hardware.org/?probe=f223bc5b5e) | Jun 19, 2020 |
| MSI           | B85M Night Elf              | [27d008955f](https://linux-hardware.org/?probe=27d008955f) | Jun 19, 2020 |
| ASUSTek       | H97-PRO GAMER               | [ce4a203e0f](https://linux-hardware.org/?probe=ce4a203e0f) | Jun 19, 2020 |
| Gigabyte      | B450M GAMING                | [7b0270fb87](https://linux-hardware.org/?probe=7b0270fb87) | Jun 04, 2020 |
| Gigabyte      | H170-Gaming 3               | [b0f5fc9b10](https://linux-hardware.org/?probe=b0f5fc9b10) | May 26, 2020 |
| Gigabyte      | B450M GAMING                | [ffb18f222a](https://linux-hardware.org/?probe=ffb18f222a) | May 15, 2020 |
| Gigabyte      | B450M GAMING                | [a4ec49073e](https://linux-hardware.org/?probe=a4ec49073e) | May 02, 2020 |
| ASRock        | AOD790GX/128M               | [8ba6b55d11](https://linux-hardware.org/?probe=8ba6b55d11) | Apr 28, 2020 |
| Gigabyte      | H61M-DS2                    | [1aa80c5f94](https://linux-hardware.org/?probe=1aa80c5f94) | Apr 26, 2020 |
| Gigabyte      | B250M-D2V-CF                | [45b9a81a90](https://linux-hardware.org/?probe=45b9a81a90) | Apr 08, 2020 |
| Shuttle       | FS81                        | [93c00d64e6](https://linux-hardware.org/?probe=93c00d64e6) | Feb 07, 2020 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [e3cbb2da5f](https://linux-hardware.org/?probe=e3cbb2da5f) | Jan 24, 2020 |
| ASUSTek       | P9X79 WS                    | [7a8ccfd558](https://linux-hardware.org/?probe=7a8ccfd558) | Nov 21, 2019 |
| Dell          | 0CU409                      | [a5aabfdba4](https://linux-hardware.org/?probe=a5aabfdba4) | Sep 09, 2019 |
| Dell          | 0CU409                      | [8efe3a4b92](https://linux-hardware.org/?probe=8efe3a4b92) | Sep 08, 2019 |
| Gigabyte      | B360 M AORUS PRO-CF         | [657b0b4115](https://linux-hardware.org/?probe=657b0b4115) | Aug 28, 2019 |
| Gigabyte      | B450M GAMING                | [6a22791c51](https://linux-hardware.org/?probe=6a22791c51) | Aug 02, 2019 |
| Gigabyte      | B450M GAMING                | [9394c6057f](https://linux-hardware.org/?probe=9394c6057f) | Aug 01, 2019 |
| ASUSTek       | P8H61-MX R2.0               | [6cf789df63](https://linux-hardware.org/?probe=6cf789df63) | Jul 26, 2019 |
| Gigabyte      | B450M GAMING                | [a6040fd25f](https://linux-hardware.org/?probe=a6040fd25f) | Jul 21, 2019 |
| Gigabyte      | B450M GAMING                | [e4ad262a5d](https://linux-hardware.org/?probe=e4ad262a5d) | Jul 18, 2019 |
| ASUSTek       | P8H61-MX R2.0               | [c52b084692](https://linux-hardware.org/?probe=c52b084692) | Jul 08, 2019 |
| ASUSTek       | P8H61-MX R2.0               | [06efccb71d](https://linux-hardware.org/?probe=06efccb71d) | Jul 07, 2019 |
| Wistron       | JIH55Y                      | [75d7b2909e](https://linux-hardware.org/?probe=75d7b2909e) | Jul 07, 2019 |
| MSI           | K9A2 Neo2                   | [ab1717a7d5](https://linux-hardware.org/?probe=ab1717a7d5) | Jul 05, 2019 |
| MSI           | K9A2 Neo2                   | [32eed13a8c](https://linux-hardware.org/?probe=32eed13a8c) | Jul 05, 2019 |
| ASUSTek       | H81M-K                      | [0142c9d319](https://linux-hardware.org/?probe=0142c9d319) | May 08, 2019 |
| ASUSTek       | H81M-K                      | [eab65462c8](https://linux-hardware.org/?probe=eab65462c8) | May 08, 2019 |
| Gigabyte      | H61M-DS2                    | [6c2f44420a](https://linux-hardware.org/?probe=6c2f44420a) | Nov 09, 2018 |
| Gigabyte      | H61M-DS2                    | [795142797e](https://linux-hardware.org/?probe=795142797e) | Nov 09, 2018 |
| Lenovo        | ThinkCentre M55e 9389AN1    | [850f4b963c](https://linux-hardware.org/?probe=850f4b963c) | Dec 08, 2017 |
| Lenovo        | ThinkCentre M55e 9389AN1    | [e764602f25](https://linux-hardware.org/?probe=e764602f25) | Dec 02, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 29       | 18.13%  |
| Ubuntu 18.04                 | 16       | 10%     |
| Ubuntu 22.04                 | 13       | 8.13%   |
| Arch Rolling                 | 10       | 6.25%   |
| OpenMandriva 23.03           | 5        | 3.13%   |
| Manjaro                      | 5        | 3.13%   |
| Fedora 37                    | 5        | 3.13%   |
| ArcoLinux Rolling            | 5        | 3.13%   |
| Arch                         | 5        | 3.13%   |
| Zorin 16                     | 3        | 1.88%   |
| Fedora 38                    | 3        | 1.88%   |
| Debian 12                    | 3        | 1.88%   |
| Debian 11                    | 3        | 1.88%   |
| Debian 10                    | 3        | 1.88%   |
| Ubuntu Unity 16.04           | 2        | 1.25%   |
| Ubuntu 23.10                 | 2        | 1.25%   |
| Ubuntu 19.04                 | 2        | 1.25%   |
| Pop!_OS 20.10                | 2        | 1.25%   |
| Oracle Linux 8.9             | 2        | 1.25%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 1.25%   |
| Manjaro 20.2                 | 2        | 1.25%   |
| Linux Mint 20.3              | 2        | 1.25%   |
| Gentoo 2.13                  | 2        | 1.25%   |
| Zorin 15                     | 1        | 0.63%   |
| Xubuntu 20.04                | 1        | 0.63%   |
| Ubuntu MATE 22.04            | 1        | 0.63%   |
| Ubuntu 21.04                 | 1        | 0.63%   |
| Ubuntu 19.10                 | 1        | 0.63%   |
| Ubuntu 16.04                 | 1        | 0.63%   |
| SteamOS 4                    | 1        | 0.63%   |
| Pop!_OS 22.04                | 1        | 0.63%   |
| Parrot 4.11                  | 1        | 0.63%   |
| openSUSE Leap-15.5           | 1        | 0.63%   |
| OpenMandriva 4.50            | 1        | 0.63%   |
| OpenMandriva 4.3             | 1        | 0.63%   |
| OpenMandriva 4.2             | 1        | 0.63%   |
| OpenMandriva 23.08           | 1        | 0.63%   |
| OpenMandriva 23.01           | 1        | 0.63%   |
| Manjaro 21.0.1               | 1        | 0.63%   |
| Manjaro 20.0.3               | 1        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 63       | 40.13%  |
| Arch         | 15       | 9.55%   |
| OpenMandriva | 10       | 6.37%   |
| Manjaro      | 9        | 5.73%   |
| Fedora       | 9        | 5.73%   |
| Debian       | 9        | 5.73%   |
| ArcoLinux    | 6        | 3.82%   |
| Linux Mint   | 5        | 3.18%   |
| Zorin        | 4        | 2.55%   |
| Pop!_OS      | 3        | 1.91%   |
| openSUSE     | 3        | 1.91%   |
| Gentoo       | 3        | 1.91%   |
| Ubuntu Unity | 2        | 1.27%   |
| Oracle Linux | 2        | 1.27%   |
| Kubuntu      | 2        | 1.27%   |
| KDE neon     | 2        | 1.27%   |
| Clear Linux  | 2        | 1.27%   |
| Xubuntu      | 1        | 0.64%   |
| Ubuntu MATE  | 1        | 0.64%   |
| SteamOS      | 1        | 0.64%   |
| Parrot       | 1        | 0.64%   |
| EndeavourOS  | 1        | 0.64%   |
| Elementary   | 1        | 0.64%   |
| ChimeraOS    | 1        | 0.64%   |
| Alpine       | 1        | 0.64%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| 6.2.6-desktop-1omv2390                                 | 5        | 2.94%   |
| 5.4.0-58-generic                                       | 4        | 2.35%   |
| 5.4.0-37-generic                                       | 3        | 1.76%   |
| 5.4.0-26-generic                                       | 3        | 1.76%   |
| 5.15.0-91-generic                                      | 3        | 1.76%   |
| 5.15.0-52-generic                                      | 3        | 1.76%   |
| 5.11.0-38-generic                                      | 3        | 1.76%   |
| 5.0.0-23-generic                                       | 3        | 1.76%   |
| 6.5.8-arch1-1                                          | 2        | 1.18%   |
| 6.2.0-36-generic                                       | 2        | 1.18%   |
| 6.0.12-300.fc37.x86_64                                 | 2        | 1.18%   |
| 5.9.11-3-MANJARO                                       | 2        | 1.18%   |
| 5.8.0-7642-generic                                     | 2        | 1.18%   |
| 5.4.0-48-generic                                       | 2        | 1.18%   |
| 5.4.0-47-generic                                       | 2        | 1.18%   |
| 5.4.0-42-generic                                       | 2        | 1.18%   |
| 5.11.0-41-generic                                      | 2        | 1.18%   |
| 5.11.0-37-generic                                      | 2        | 1.18%   |
| 4.18.0-25-generic                                      | 2        | 1.18%   |
| 6.8.1-arch1-1                                          | 1        | 0.59%   |
| 6.7.8-arch1-1                                          | 1        | 0.59%   |
| 6.7.1-arch1-1                                          | 1        | 0.59%   |
| 6.7.0-0.rc3.20231202gt815fb87b.332.vanilla.fc39.x86_64 | 1        | 0.59%   |
| 6.6.8-arch1-1                                          | 1        | 0.59%   |
| 6.6.6-0-lts                                            | 1        | 0.59%   |
| 6.6.3-arch1-1                                          | 1        | 0.59%   |
| 6.6.16-2-MANJARO                                       | 1        | 0.59%   |
| 6.6.13-x64v3-xanmod1                                   | 1        | 0.59%   |
| 6.6.1-arch1-1                                          | 1        | 0.59%   |
| 6.5.7-arch1-1                                          | 1        | 0.59%   |
| 6.5.5-200.fc38.x86_64                                  | 1        | 0.59%   |
| 6.5.3-chos1-chimeraos-1                                | 1        | 0.59%   |
| 6.5.0-28-generic                                       | 1        | 0.59%   |
| 6.5.0-15-generic                                       | 1        | 0.59%   |
| 6.4.3-arch1-1                                          | 1        | 0.59%   |
| 6.4.11-desktop-1omv2390                                | 1        | 0.59%   |
| 6.4.0-0.rc5.20230607gta4d7d701.342.vanilla.fc38.x86_64 | 1        | 0.59%   |
| 6.3.9-arch1-1                                          | 1        | 0.59%   |
| 6.3.7-zen1-1-zen                                       | 1        | 0.59%   |
| 6.3.0-gentoo                                           | 1        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 23       | 13.94%  |
| 5.15.0  | 18       | 10.91%  |
| 5.11.0  | 10       | 6.06%   |
| 5.8.0   | 8        | 4.85%   |
| 6.2.6   | 7        | 4.24%   |
| 6.2.0   | 6        | 3.64%   |
| 5.0.0   | 6        | 3.64%   |
| 4.15.0  | 6        | 3.64%   |
| 6.1.0   | 3        | 1.82%   |
| 4.18.0  | 3        | 1.82%   |
| 6.5.8   | 2        | 1.21%   |
| 6.5.0   | 2        | 1.21%   |
| 6.2.9   | 2        | 1.21%   |
| 6.1.11  | 2        | 1.21%   |
| 6.0.12  | 2        | 1.21%   |
| 5.9.11  | 2        | 1.21%   |
| 5.15.60 | 2        | 1.21%   |
| 5.12.8  | 2        | 1.21%   |
| 6.8.1   | 1        | 0.61%   |
| 6.7.8   | 1        | 0.61%   |
| 6.7.1   | 1        | 0.61%   |
| 6.7.0   | 1        | 0.61%   |
| 6.6.8   | 1        | 0.61%   |
| 6.6.6   | 1        | 0.61%   |
| 6.6.3   | 1        | 0.61%   |
| 6.6.16  | 1        | 0.61%   |
| 6.6.13  | 1        | 0.61%   |
| 6.6.1   | 1        | 0.61%   |
| 6.5.7   | 1        | 0.61%   |
| 6.5.5   | 1        | 0.61%   |
| 6.5.3   | 1        | 0.61%   |
| 6.4.3   | 1        | 0.61%   |
| 6.4.11  | 1        | 0.61%   |
| 6.4.0   | 1        | 0.61%   |
| 6.3.9   | 1        | 0.61%   |
| 6.3.7   | 1        | 0.61%   |
| 6.3.0   | 1        | 0.61%   |
| 6.1.31  | 1        | 0.61%   |
| 6.1.15  | 1        | 0.61%   |
| 6.1.13  | 1        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 25       | 15.24%  |
| 5.15    | 20       | 12.2%   |
| 6.2     | 15       | 9.15%   |
| 6.1     | 11       | 6.71%   |
| 5.11    | 11       | 6.71%   |
| 5.8     | 8        | 4.88%   |
| 6.5     | 7        | 4.27%   |
| 4.15    | 7        | 4.27%   |
| 6.6     | 6        | 3.66%   |
| 5.19    | 6        | 3.66%   |
| 5.0     | 6        | 3.66%   |
| 5.10    | 5        | 3.05%   |
| 6.0     | 4        | 2.44%   |
| 5.9     | 4        | 2.44%   |
| 5.12    | 4        | 2.44%   |
| 6.7     | 3        | 1.83%   |
| 6.4     | 3        | 1.83%   |
| 6.3     | 3        | 1.83%   |
| 4.18    | 3        | 1.83%   |
| 5.6     | 2        | 1.22%   |
| 5.17    | 2        | 1.22%   |
| 5.14    | 2        | 1.22%   |
| 4.19    | 2        | 1.22%   |
| 6.8     | 1        | 0.61%   |
| 5.3     | 1        | 0.61%   |
| 5.18    | 1        | 0.61%   |
| 5.16    | 1        | 0.61%   |
| 4.10    | 1        | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 154      | 99.35%  |
| i686   | 1        | 0.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 76       | 47.8%   |
| Unknown    | 33       | 20.75%  |
| KDE5       | 23       | 14.47%  |
| XFCE       | 8        | 5.03%   |
| MATE       | 4        | 2.52%   |
| i3         | 3        | 1.89%   |
| X-Cinnamon | 2        | 1.26%   |
| Unity      | 2        | 1.26%   |
| KDE        | 2        | 1.26%   |
| Pantheon   | 1        | 0.63%   |
| LXQt       | 1        | 0.63%   |
| KDE6       | 1        | 0.63%   |
| Cinnamon   | 1        | 0.63%   |
| bspwm      | 1        | 0.63%   |
| awesome    | 1        | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 109      | 68.55%  |
| Wayland | 29       | 18.24%  |
| Unknown | 14       | 8.81%   |
| Tty     | 7        | 4.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 74       | 46.84%  |
| GDM     | 28       | 17.72%  |
| SDDM    | 20       | 12.66%  |
| LightDM | 15       | 9.49%   |
| GDM3    | 15       | 9.49%   |
| TDM     | 4        | 2.53%   |
| XDM     | 1        | 0.63%   |
| LY-DM   | 1        | 0.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 116      | 74.36%  |
| Unknown     | 24       | 15.38%  |
| vi_VN       | 8        | 5.13%   |
| C           | 3        | 1.92%   |
| en_GB       | 2        | 1.28%   |
| ru_RU       | 1        | 0.64%   |
| ja_JP       | 1        | 0.64%   |
| en_US.UTF=8 | 1        | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 93       | 59.24%  |
| BIOS | 64       | 40.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 112      | 70.89%  |
| Btrfs   | 20       | 12.66%  |
| Overlay | 14       | 8.86%   |
| Tmpfs   | 5        | 3.16%   |
| Zfs     | 3        | 1.9%    |
| Unknown | 2        | 1.27%   |
| Xfs     | 1        | 0.63%   |
| F2fs    | 1        | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 81       | 51.59%  |
| Unknown | 61       | 38.85%  |
| MBR     | 15       | 9.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 122      | 78.21%  |
| Yes       | 34       | 21.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 54.72%  |
| Yes       | 72       | 45.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 46       | 29.68%  |
| ASUSTek Computer    | 37       | 23.87%  |
| MSI                 | 20       | 12.9%   |
| Hewlett-Packard     | 11       | 7.1%    |
| Dell                | 11       | 7.1%    |
| ASRock              | 5        | 3.23%   |
| Lenovo              | 3        | 1.94%   |
| Intel               | 3        | 1.94%   |
| GuoGuang            | 3        | 1.94%   |
| Unknown             | 3        | 1.94%   |
| ZOTAC               | 2        | 1.29%   |
| Wistron             | 2        | 1.29%   |
| Foxconn             | 2        | 1.29%   |
| T-bao               | 1        | 0.65%   |
| Supermicro          | 1        | 0.65%   |
| Shuttle             | 1        | 0.65%   |
| Koloe               | 1        | 0.65%   |
| Huanan              | 1        | 0.65%   |
| Colorful Technology | 1        | 0.65%   |
| AZW                 | 1        | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte H61M-DS2                  | 6        | 3.87%   |
| ASUS All Series                    | 5        | 3.23%   |
| Unknown                            | 5        | 3.23%   |
| MSI MS-7B98                        | 3        | 1.94%   |
| MSI MS-7B89                        | 3        | 1.94%   |
| MSI MS-7C89                        | 2        | 1.29%   |
| MSI MS-7823                        | 2        | 1.29%   |
| HP Z440 Workstation                | 2        | 1.29%   |
| GuoGuang IC2M1028V-J               | 2        | 1.29%   |
| Gigabyte H81M-DS2                  | 2        | 1.29%   |
| Gigabyte G41M-ES2L                 | 2        | 1.29%   |
| Gigabyte B75M-D3H                  | 2        | 1.29%   |
| Gigabyte B450M GAMING              | 2        | 1.29%   |
| Gigabyte B360M-D3H                 | 2        | 1.29%   |
| ASUS ROG STRIX B650E-I GAMING WIFI | 2        | 1.29%   |
| ASUS ROG CROSSHAIR VIII HERO       | 2        | 1.29%   |
| ASUS PRIME B450M-A                 | 2        | 1.29%   |
| ASUS P8H61-MX R2.0                 | 2        | 1.29%   |
| ASUS B75M-A                        | 2        | 1.29%   |
| Wistron FMVDD2A0H0                 | 1        | 0.65%   |
| Wistron FMVCEG40Y                  | 1        | 0.65%   |
| T-bao MINI PC                      | 1        | 0.65%   |
| Supermicro SYS-6018R-CMG367-HM005  | 1        | 0.65%   |
| Shuttle DS81D                      | 1        | 0.65%   |
| MSI MS-7C75                        | 1        | 0.65%   |
| MSI MS-7C67                        | 1        | 0.65%   |
| MSI MS-7C37                        | 1        | 0.65%   |
| MSI MS-7C31                        | 1        | 0.65%   |
| MSI MS-7C09                        | 1        | 0.65%   |
| MSI MS-7B84                        | 1        | 0.65%   |
| MSI MS-7A40                        | 1        | 0.65%   |
| MSI MS-7A38                        | 1        | 0.65%   |
| MSI MS-7972                        | 1        | 0.65%   |
| MSI MS-7388                        | 1        | 0.65%   |
| Lenovo ThinkCentre M93p 10A8CTO1WW | 1        | 0.65%   |
| Lenovo ThinkCentre M92p m92p       | 1        | 0.65%   |
| Lenovo ThinkCentre M55e 9389AN1    | 1        | 0.65%   |
| Koloe Thurley                      | 1        | 0.65%   |
| Intel X99                          | 1        | 0.65%   |
| Intel H81                          | 1        | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS PRIME                        | 10       | 6.45%   |
| Dell OptiPlex                     | 8        | 5.16%   |
| ASUS ROG                          | 7        | 4.52%   |
| Gigabyte H61M-DS2                 | 6        | 3.87%   |
| ASUS All                          | 5        | 3.23%   |
| Unknown                           | 5        | 3.23%   |
| MSI MS-7B98                       | 3        | 1.94%   |
| MSI MS-7B89                       | 3        | 1.94%   |
| Lenovo ThinkCentre                | 3        | 1.94%   |
| ASUS P8H61-MX                     | 3        | 1.94%   |
| MSI MS-7C89                       | 2        | 1.29%   |
| MSI MS-7823                       | 2        | 1.29%   |
| HP Z440                           | 2        | 1.29%   |
| GuoGuang IC2M1028V-J              | 2        | 1.29%   |
| Gigabyte X570                     | 2        | 1.29%   |
| Gigabyte H81M-DS2                 | 2        | 1.29%   |
| Gigabyte G41M-ES2L                | 2        | 1.29%   |
| Gigabyte B75M-D3H                 | 2        | 1.29%   |
| Gigabyte B660M                    | 2        | 1.29%   |
| Gigabyte B450M                    | 2        | 1.29%   |
| Gigabyte B360M-D3H                | 2        | 1.29%   |
| ASUS B75M-A                       | 2        | 1.29%   |
| Wistron FMVDD2A0H0                | 1        | 0.65%   |
| Wistron FMVCEG40Y                 | 1        | 0.65%   |
| T-bao MINI                        | 1        | 0.65%   |
| Supermicro SYS-6018R-CMG367-HM005 | 1        | 0.65%   |
| Shuttle DS81D                     | 1        | 0.65%   |
| MSI MS-7C75                       | 1        | 0.65%   |
| MSI MS-7C67                       | 1        | 0.65%   |
| MSI MS-7C37                       | 1        | 0.65%   |
| MSI MS-7C31                       | 1        | 0.65%   |
| MSI MS-7C09                       | 1        | 0.65%   |
| MSI MS-7B84                       | 1        | 0.65%   |
| MSI MS-7A40                       | 1        | 0.65%   |
| MSI MS-7A38                       | 1        | 0.65%   |
| MSI MS-7972                       | 1        | 0.65%   |
| MSI MS-7388                       | 1        | 0.65%   |
| Koloe Thurley                     | 1        | 0.65%   |
| Intel X99                         | 1        | 0.65%   |
| Intel H81                         | 1        | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 27       | 17.42%  |
| 2014 | 17       | 10.97%  |
| 2013 | 16       | 10.32%  |
| 2019 | 14       | 9.03%   |
| 2012 | 13       | 8.39%   |
| 2020 | 12       | 7.74%   |
| 2017 | 8        | 5.16%   |
| 2016 | 8        | 5.16%   |
| 2015 | 8        | 5.16%   |
| 2010 | 7        | 4.52%   |
| 2021 | 6        | 3.87%   |
| 2009 | 5        | 3.23%   |
| 2022 | 4        | 2.58%   |
| 2011 | 4        | 2.58%   |
| 2023 | 3        | 1.94%   |
| 2008 | 1        | 0.65%   |
| 2007 | 1        | 0.65%   |
| 2006 | 1        | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 155      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 150      | 96.77%  |
| Enabled  | 5        | 3.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 155      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 37       | 23.57%  |
| 8.01-16.0   | 31       | 19.75%  |
| 32.01-64.0  | 28       | 17.83%  |
| 4.01-8.0    | 21       | 13.38%  |
| 3.01-4.0    | 21       | 13.38%  |
| 1.01-2.0    | 7        | 4.46%   |
| 24.01-32.0  | 6        | 3.82%   |
| 64.01-256.0 | 6        | 3.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 44       | 26.83%  |
| 1.01-2.0   | 41       | 25%     |
| 4.01-8.0   | 29       | 17.68%  |
| 3.01-4.0   | 25       | 15.24%  |
| 8.01-16.0  | 14       | 8.54%   |
| 16.01-24.0 | 5        | 3.05%   |
| 0.51-1.0   | 4        | 2.44%   |
| 24.01-32.0 | 1        | 0.61%   |
| 0.01-0.5   | 1        | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 71       | 44.38%  |
| 1      | 46       | 28.75%  |
| 3      | 30       | 18.75%  |
| 4      | 8        | 5%      |
| 5      | 3        | 1.88%   |
| 9      | 1        | 0.63%   |
| 0      | 1        | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 131      | 84.52%  |
| Yes       | 24       | 15.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 154      | 99.35%  |
| No        | 1        | 0.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 55.41%  |
| Yes       | 70       | 44.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 99       | 63.06%  |
| Yes       | 58       | 36.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Vietnam | 155      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Ho Chi Minh City | 80       | 51.28%  |
| Hanoi            | 46       | 29.49%  |
| Bac Giang        | 4        | 2.56%   |
| Tua Chua         | 3        | 1.92%   |
| Can Tho          | 3        | 1.92%   |
| Nga Bay          | 2        | 1.28%   |
| Da Nang          | 2        | 1.28%   |
| Vũng Tàu       | 1        | 0.64%   |
| Vi Thanh         | 1        | 0.64%   |
| Tinh Binh Duong  | 1        | 0.64%   |
| Thai Nguyen      | 1        | 0.64%   |
| Tay Ninh         | 1        | 0.64%   |
| Quảng Ngai     | 1        | 0.64%   |
| Nha Trang        | 1        | 0.64%   |
| Nam Định      | 1        | 0.64%   |
| My Binh          | 1        | 0.64%   |
| Hung Yen         | 1        | 0.64%   |
| Haiphong         | 1        | 0.64%   |
| Hai Duong        | 1        | 0.64%   |
| Di An            | 1        | 0.64%   |
| Binh Duong       | 1        | 0.64%   |
| Bien Hoa         | 1        | 0.64%   |
| Bến Tre        | 1        | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 69       | 96     | 24.21%  |
| Seagate                     | 41       | 50     | 14.39%  |
| Samsung Electronics         | 38       | 59     | 13.33%  |
| Kingston                    | 16       | 21     | 5.61%   |
| Toshiba                     | 15       | 26     | 5.26%   |
| Sandisk                     | 9        | 9      | 3.16%   |
| Hitachi                     | 6        | 7      | 2.11%   |
| Unknown                     | 5        | 5      | 1.75%   |
| XSTAR                       | 4        | 4      | 1.4%    |
| Lexar                       | 4        | 4      | 1.4%    |
| Intel                       | 4        | 4      | 1.4%    |
| HGST                        | 4        | 4      | 1.4%    |
| Crucial                     | 4        | 7      | 1.4%    |
| Netac                       | 3        | 3      | 1.05%   |
| Colorful                    | 3        | 3      | 1.05%   |
| ZOTAC                       | 2        | 2      | 0.7%    |
| Transcend                   | 2        | 2      | 0.7%    |
| TO Exter                    | 2        | 3      | 0.7%    |
| SK hynix                    | 2        | 2      | 0.7%    |
| Plextor                     | 2        | 2      | 0.7%    |
| OCZ                         | 2        | 2      | 0.7%    |
| Mushkin                     | 2        | 2      | 0.7%    |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.7%    |
| KingSpec                    | 2        | 2      | 0.7%    |
| JMicron Technology          | 2        | 2      | 0.7%    |
| Gigabyte Technology         | 2        | 2      | 0.7%    |
| Fujitsu                     | 2        | 2      | 0.7%    |
| China                       | 2        | 2      | 0.7%    |
| Unknown                     | 2        | 2      | 0.7%    |
| VSP                         | 1        | 1      | 0.35%   |
| Vaseky                      | 1        | 1      | 0.35%   |
| TXRUI                       | 1        | 1      | 0.35%   |
| SSSTC                       | 1        | 1      | 0.35%   |
| Realtek Semiconductor       | 1        | 2      | 0.35%   |
| Realtek                     | 1        | 1      | 0.35%   |
| PNY                         | 1        | 1      | 0.35%   |
| Phison                      | 1        | 2      | 0.35%   |
| Patriot                     | 1        | 1      | 0.35%   |
| OSCOO                       | 1        | 1      | 0.35%   |
| Micron/Crucial Technology   | 1        | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 6        | 1.9%    |
| Kingston SA400S37240G 240GB SSD                   | 6        | 1.9%    |
| WDC WD5000AAKX-00ERMA0 500GB                      | 5        | 1.58%   |
| Samsung SSD 860 EVO 250GB                         | 5        | 1.58%   |
| XSTAR SSD 128GB                                   | 4        | 1.27%   |
| WDC WD2500AAKX-00ERMA0 250GB                      | 4        | 1.27%   |
| Unknown SD/MMC/MS PRO 128GB                       | 4        | 1.27%   |
| Seagate ST500DM002-1BD142 500GB                   | 4        | 1.27%   |
| Seagate ST1000DM010-2EP102 1TB                    | 4        | 1.27%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                | 4        | 1.27%   |
| Samsung SSD 980 1TB                               | 4        | 1.27%   |
| Samsung SSD 860 EVO 500GB                         | 4        | 1.27%   |
| WDC WD5000LPLX-66ZNTT1 500GB                      | 3        | 0.95%   |
| WDC WD1502FYPS-02W3B0 1TB                         | 3        | 0.95%   |
| Samsung SSD 860 EVO 1TB                           | 3        | 0.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3        | 0.95%   |
| ZOTAC SATA SSD 120GB                              | 2        | 0.63%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 2        | 0.63%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 2        | 0.63%   |
| WDC WD5000LPLX-60ZNTT1 500GB                      | 2        | 0.63%   |
| WDC WD3200AAKX-001CA0 320GB                       | 2        | 0.63%   |
| WDC WD10EZEX-00BBHA0 1TB                          | 2        | 0.63%   |
| WDC WD1003FZEX-00K3CA0 1TB                        | 2        | 0.63%   |
| Toshiba KXG5AZNV512G 512GB                        | 2        | 0.63%   |
| Toshiba HDWD120 2TB                               | 2        | 0.63%   |
| Toshiba DT01ABA100V 1TB                           | 2        | 0.63%   |
| TO Exter nal USB 3.0 500GB                        | 2        | 0.63%   |
| Seagate ST3250318AS 250GB                         | 2        | 0.63%   |
| Seagate ST250DM000-1BD141 250GB                   | 2        | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB                    | 2        | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB                    | 2        | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB                    | 2        | 0.63%   |
| Samsung SSD 980 PRO 1TB                           | 2        | 0.63%   |
| Samsung SSD 980 500GB                             | 2        | 0.63%   |
| Samsung SSD 870 EVO 500GB                         | 2        | 0.63%   |
| Samsung SSD 750 EVO 120GB                         | 2        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB | 2        | 0.63%   |
| Netac SSD 128GB                                   | 2        | 0.63%   |
| Mushkin MKNSSDHL1TB-D8                            | 2        | 0.63%   |
| Lexar 128GB SSD                                   | 2        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 55       | 76     | 42.97%  |
| Seagate  | 41       | 49     | 32.03%  |
| Toshiba  | 13       | 20     | 10.16%  |
| Hitachi  | 6        | 7      | 4.69%   |
| Unknown  | 4        | 4      | 3.13%   |
| HGST     | 4        | 4      | 3.13%   |
| TO Exter | 2        | 3      | 1.56%   |
| Fujitsu  | 2        | 2      | 1.56%   |
| CSD      | 1        | 1      | 0.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 22       | 33     | 20.56%  |
| Kingston            | 15       | 20     | 14.02%  |
| WDC                 | 13       | 13     | 12.15%  |
| XSTAR               | 4        | 4      | 3.74%   |
| SanDisk             | 4        | 4      | 3.74%   |
| Lexar               | 4        | 4      | 3.74%   |
| Intel               | 4        | 4      | 3.74%   |
| Crucial             | 4        | 5      | 3.74%   |
| Netac               | 3        | 3      | 2.8%    |
| Colorful            | 3        | 3      | 2.8%    |
| ZOTAC               | 2        | 2      | 1.87%   |
| Transcend           | 2        | 2      | 1.87%   |
| Toshiba             | 2        | 2      | 1.87%   |
| Plextor             | 2        | 2      | 1.87%   |
| KingSpec            | 2        | 2      | 1.87%   |
| Gigabyte Technology | 2        | 2      | 1.87%   |
| China               | 2        | 2      | 1.87%   |
| VSP                 | 1        | 1      | 0.93%   |
| Vaseky              | 1        | 1      | 0.93%   |
| SK hynix            | 1        | 1      | 0.93%   |
| PNY                 | 1        | 1      | 0.93%   |
| Patriot             | 1        | 1      | 0.93%   |
| OSCOO               | 1        | 1      | 0.93%   |
| OCZ                 | 1        | 1      | 0.93%   |
| Micron Technology   | 1        | 1      | 0.93%   |
| Maxtor              | 1        | 1      | 0.93%   |
| LITEONIT            | 1        | 1      | 0.93%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.93%   |
| HS-SSD-HB1          | 1        | 1      | 0.93%   |
| External            | 1        | 1      | 0.93%   |
| EK                  | 1        | 1      | 0.93%   |
| Apacer              | 1        | 1      | 0.93%   |
| AOSENKE             | 1        | 1      | 0.93%   |
| Unknown             | 1        | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 101      | 166    | 40.56%  |
| SSD     | 92       | 124    | 36.95%  |
| NVMe    | 46       | 66     | 18.47%  |
| Unknown | 10       | 10     | 4.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 135      | 284    | 69.23%  |
| NVMe | 46       | 64     | 23.59%  |
| SAS  | 14       | 18     | 7.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 120      | 190    | 63.16%  |
| 0.51-1.0   | 42       | 55     | 22.11%  |
| 1.01-2.0   | 14       | 21     | 7.37%   |
| 4.01-10.0  | 7        | 16     | 3.68%   |
| 3.01-4.0   | 5        | 6      | 2.63%   |
| 2.01-3.0   | 2        | 2      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 54       | 33.54%  |
| 501-1000       | 25       | 15.53%  |
| 251-500        | 21       | 13.04%  |
| Unknown        | 19       | 11.8%   |
| More than 3000 | 8        | 4.97%   |
| 1001-2000      | 8        | 4.97%   |
| 51-100         | 8        | 4.97%   |
| 1-20           | 7        | 4.35%   |
| 21-50          | 6        | 3.73%   |
| 2001-3000      | 5        | 3.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 55       | 34.16%  |
| 21-50          | 22       | 13.66%  |
| Unknown        | 19       | 11.8%   |
| 51-100         | 18       | 11.18%  |
| 101-250        | 15       | 9.32%   |
| 251-500        | 14       | 8.7%    |
| 501-1000       | 9        | 5.59%   |
| More than 3000 | 4        | 2.48%   |
| 1001-2000      | 3        | 1.86%   |
| 2001-3000      | 2        | 1.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD3200AAKX-001CA0 320GB         | 2        | 2      | 7.14%   |
| Kingston SA400S37240G 240GB SSD     | 2        | 2      | 7.14%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 1      | 3.57%   |
| WDC WD60PURZ-85ZUFY1 6TB            | 1        | 3      | 3.57%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 1      | 3.57%   |
| WDC WD10EZRX-00A3KB0 1TB            | 1        | 1      | 3.57%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 1      | 3.57%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1        | 1      | 3.57%   |
| Transcend TS256GSSD230S 256GB       | 1        | 1      | 3.57%   |
| Toshiba MK3275GSX 320GB             | 1        | 1      | 3.57%   |
| Seagate ST9250410AS 250GB           | 1        | 1      | 3.57%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 3.57%   |
| Seagate ST250DM000-1BD141 250GB     | 1        | 1      | 3.57%   |
| Seagate ST1000DM003-1ER162 1TB      | 1        | 1      | 3.57%   |
| Samsung Electronics SSD 980 1TB     | 1        | 1      | 3.57%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 3.57%   |
| Kingston SKC600512G 512GB SSD       | 1        | 3      | 3.57%   |
| Intel SSDSC2CW120A3 120GB           | 1        | 1      | 3.57%   |
| Hitachi HUA722020ALA331 2TB         | 1        | 1      | 3.57%   |
| Hitachi HTS725016A9A364 160GB       | 1        | 1      | 3.57%   |
| Hitachi HDT725032VLA380 320GB       | 1        | 2      | 3.57%   |
| HGST HTS725050A7E630 500GB          | 1        | 1      | 3.57%   |
| HGST HTS545050A7E680 500GB          | 1        | 1      | 3.57%   |
| Fujitsu MHK2120AT 12GB              | 1        | 1      | 3.57%   |
| CSD CAA500S 500GB                   | 1        | 1      | 3.57%   |
| China MSATA 32GB SSD                | 1        | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 10     | 28.57%  |
| Seagate             | 4        | 4      | 14.29%  |
| Kingston            | 3        | 5      | 10.71%  |
| Hitachi             | 3        | 4      | 10.71%  |
| Samsung Electronics | 2        | 2      | 7.14%   |
| HGST                | 2        | 2      | 7.14%   |
| Transcend           | 1        | 1      | 3.57%   |
| Toshiba             | 1        | 1      | 3.57%   |
| Intel               | 1        | 1      | 3.57%   |
| Fujitsu             | 1        | 1      | 3.57%   |
| CSD                 | 1        | 1      | 3.57%   |
| China               | 1        | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 9      | 36.84%  |
| Seagate | 4        | 4      | 21.05%  |
| Hitachi | 3        | 4      | 15.79%  |
| HGST    | 2        | 2      | 10.53%  |
| Toshiba | 1        | 1      | 5.26%   |
| Fujitsu | 1        | 1      | 5.26%   |
| CSD     | 1        | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 22     | 69.23%  |
| SSD  | 7        | 10     | 26.92%  |
| NVMe | 1        | 1      | 3.85%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 83       | 187    | 46.11%  |
| Detected | 73       | 145    | 40.56%  |
| Malfunc  | 23       | 33     | 12.78%  |
| Failed   | 1        | 1      | 0.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 121      | 56.81%  |
| AMD                            | 32       | 15.02%  |
| Samsung Electronics            | 20       | 9.39%   |
| SanDisk                        | 12       | 5.63%   |
| ASMedia Technology             | 4        | 1.88%   |
| Toshiba America Info Systems   | 3        | 1.41%   |
| Silicon Motion                 | 3        | 1.41%   |
| Phison Electronics             | 2        | 0.94%   |
| Micron/Crucial Technology      | 2        | 0.94%   |
| MAXIO Technology (Hangzhou)    | 2        | 0.94%   |
| Kingston Technology Company    | 2        | 0.94%   |
| ADATA Technology               | 2        | 0.94%   |
| Solid State Storage Technology | 1        | 0.47%   |
| SK hynix                       | 1        | 0.47%   |
| Realtek Semiconductor          | 1        | 0.47%   |
| OCZ Technology Group           | 1        | 0.47%   |
| Marvell Technology Group       | 1        | 0.47%   |
| LSI Logic / Symbios Logic      | 1        | 0.47%   |
| Lite-On Technology             | 1        | 0.47%   |
| JMicron Technology             | 1        | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24       | 9.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18       | 7.06%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 12       | 4.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12       | 4.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 3.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 3.92%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 3.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 3.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 2.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 7        | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 2.75%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 6        | 2.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.35%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 5        | 1.96%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 4        | 1.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 1.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.57%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.57%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 1.57%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 4        | 1.57%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 1.57%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 1.18%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.18%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.18%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 1.18%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.18%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.18%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 2        | 0.78%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 2        | 0.78%   |
| Intel SATA controller                                                                   | 2        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.78%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.78%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.78%   |
| AMD 600 Series Chipset SATA Controller                                                  | 2        | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 127      | 61.95%  |
| NVMe | 46       | 22.44%  |
| IDE  | 26       | 12.68%  |
| RAID | 5        | 2.44%   |
| SAS  | 1        | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 122      | 78.71%  |
| AMD    | 33       | 21.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i5-9600K CPU @ 3.70GHz      | 4        | 2.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 4        | 2.56%   |
| Intel Core i3-4160 CPU @ 3.60GHz       | 4        | 2.56%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 4        | 2.56%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 3        | 1.92%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 3        | 1.92%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 1.92%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 3        | 1.92%   |
| Intel Core i3-3240 CPU @ 3.40GHz       | 3        | 1.92%   |
| Intel Atom CPU D2550 @ 1.86GHz         | 3        | 1.92%   |
| AMD Ryzen 5 5500                       | 3        | 1.92%   |
| AMD Ryzen 5 3600 6-Core Processor      | 3        | 1.92%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 3        | 1.92%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz    | 2        | 1.28%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2        | 1.28%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 2        | 1.28%   |
| Intel Core i5-9400 CPU @ 2.90GHz       | 2        | 1.28%   |
| Intel Core i5-7400 CPU @ 3.00GHz       | 2        | 1.28%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2        | 1.28%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 2        | 1.28%   |
| Intel Core i5-2500 CPU @ 3.30GHz       | 2        | 1.28%   |
| Intel Core i3-8100 CPU @ 3.60GHz       | 2        | 1.28%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 2        | 1.28%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 2        | 1.28%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 2        | 1.28%   |
| Intel Core i3 CPU 540 @ 3.07GHz        | 2        | 1.28%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz   | 2        | 1.28%   |
| Intel Celeron CPU N3150 @ 1.60GHz      | 2        | 1.28%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 2        | 1.28%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 2        | 1.28%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 2        | 1.28%   |
| Intel Xeon CPU X5570 @ 2.93GHz         | 1        | 0.64%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz     | 1        | 0.64%   |
| Intel Xeon CPU E5-2686 v4 @ 2.30GHz    | 1        | 0.64%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz    | 1        | 0.64%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz     | 1        | 0.64%   |
| Intel Xeon CPU E5-2667 v4 @ 3.20GHz    | 1        | 0.64%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz    | 1        | 0.64%   |
| Intel Xeon CPU E31235 @ 3.20GHz        | 1        | 0.64%   |
| Intel Xeon CPU E3-1265L v3 @ 2.50GHz   | 1        | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 42       | 27.1%   |
| Intel Core i3           | 24       | 15.48%  |
| AMD Ryzen 5             | 16       | 10.32%  |
| Intel Xeon              | 13       | 8.39%   |
| Intel Core i7           | 11       | 7.1%    |
| Intel Core 2 Duo        | 7        | 4.52%   |
| Other                   | 6        | 3.87%   |
| Intel Celeron           | 5        | 3.23%   |
| Intel Pentium           | 4        | 2.58%   |
| AMD Ryzen 7             | 4        | 2.58%   |
| Intel Core i9           | 3        | 1.94%   |
| Intel Atom              | 3        | 1.94%   |
| AMD Ryzen 9             | 3        | 1.94%   |
| AMD Ryzen 3             | 2        | 1.29%   |
| AMD A10                 | 2        | 1.29%   |
| Intel Pentium Gold      | 1        | 0.65%   |
| Intel Pentium Dual-Core | 1        | 0.65%   |
| Intel Pentium Dual      | 1        | 0.65%   |
| Intel Core 2 Quad       | 1        | 0.65%   |
| AMD Ryzen 7 PRO         | 1        | 0.65%   |
| AMD Ryzen 5 PRO         | 1        | 0.65%   |
| AMD Phenom II X4        | 1        | 0.65%   |
| AMD Athlon II X2        | 1        | 0.65%   |
| AMD Athlon              | 1        | 0.65%   |
| AMD A8                  | 1        | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 60       | 38.46%  |
| 2      | 42       | 26.92%  |
| 6      | 33       | 21.15%  |
| 8      | 10       | 6.41%   |
| 16     | 4        | 2.56%   |
| 24     | 2        | 1.28%   |
| 10     | 2        | 1.28%   |
| 36     | 1        | 0.64%   |
| 28     | 1        | 0.64%   |
| 12     | 1        | 0.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 151      | 96.79%  |
| 2      | 5        | 3.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 86       | 55.13%  |
| 1      | 70       | 44.87%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 153      | 98.71%  |
| Unknown        | 2        | 1.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 32.28%  |
| 0x306c3    | 12       | 7.59%   |
| 0x306a9    | 10       | 6.33%   |
| 0x906ea    | 8        | 5.06%   |
| 0x1067a    | 7        | 4.43%   |
| 0x206a7    | 6        | 3.8%    |
| 0xa0653    | 4        | 2.53%   |
| 0x906e9    | 4        | 2.53%   |
| 0x906eb    | 3        | 1.9%    |
| 0x506e3    | 3        | 1.9%    |
| 0x206d7    | 3        | 1.9%    |
| 0x0a50000d | 3        | 1.9%    |
| 0x0a201016 | 3        | 1.9%    |
| 0x0810100b | 3        | 1.9%    |
| 0x906ed    | 2        | 1.27%   |
| 0x90675    | 2        | 1.27%   |
| 0x90672    | 2        | 1.27%   |
| 0x30678    | 2        | 1.27%   |
| 0x20655    | 2        | 1.27%   |
| 0x0a50000c | 2        | 1.27%   |
| 0x0a20120a | 2        | 1.27%   |
| 0x08701021 | 2        | 1.27%   |
| 0x08108109 | 2        | 1.27%   |
| 0x0800820d | 2        | 1.27%   |
| 0x06003106 | 2        | 1.27%   |
| 0xa0655    | 1        | 0.63%   |
| 0x906ec    | 1        | 0.63%   |
| 0x6fd      | 1        | 0.63%   |
| 0x406f1    | 1        | 0.63%   |
| 0x306f2    | 1        | 0.63%   |
| 0x30661    | 1        | 0.63%   |
| 0x106a5    | 1        | 0.63%   |
| 0x10676    | 1        | 0.63%   |
| 0x0a601206 | 1        | 0.63%   |
| 0x0a601203 | 1        | 0.63%   |
| 0x08701030 | 1        | 0.63%   |
| 0x08701013 | 1        | 0.63%   |
| 0x08600106 | 1        | 0.63%   |
| 0x06001119 | 1        | 0.63%   |
| 0x010000db | 1        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 27       | 17.42%  |
| Haswell          | 25       | 16.13%  |
| IvyBridge        | 15       | 9.68%   |
| Zen 3            | 10       | 6.45%   |
| SandyBridge      | 10       | 6.45%   |
| Penryn           | 9        | 5.81%   |
| Skylake          | 8        | 5.16%   |
| CometLake        | 7        | 4.52%   |
| Zen+             | 6        | 3.87%   |
| Zen 2            | 6        | 3.87%   |
| Zen              | 4        | 2.58%   |
| Silvermont       | 4        | 2.58%   |
| Westmere         | 3        | 1.94%   |
| Broadwell        | 3        | 1.94%   |
| Bonnell          | 3        | 1.94%   |
| Alderlake Hybrid | 3        | 1.94%   |
| Unknown          | 3        | 1.94%   |
| Steamroller      | 2        | 1.29%   |
| K10              | 2        | 1.29%   |
| Gracemont        | 2        | 1.29%   |
| Piledriver       | 1        | 0.65%   |
| Nehalem          | 1        | 0.65%   |
| Core             | 1        | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 72       | 41.38%  |
| Intel             | 63       | 36.21%  |
| AMD               | 38       | 21.84%  |
| ASPEED Technology | 1        | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10       | 5.59%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9        | 5.03%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 8        | 4.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7        | 3.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7        | 3.91%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6        | 3.35%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 4        | 2.23%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4        | 2.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4        | 2.23%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 4        | 2.23%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 1.68%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3        | 1.68%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3        | 1.68%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3        | 1.68%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3        | 1.68%   |
| Intel HD Graphics 630                                                                    | 3        | 1.68%   |
| Intel HD Graphics 530                                                                    | 3        | 1.68%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3        | 1.68%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 1.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 1.68%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3        | 1.68%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2        | 1.12%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 2        | 1.12%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 2        | 1.12%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 2        | 1.12%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 2        | 1.12%   |
| Nvidia GK107 [GeForce GT 740]                                                            | 2        | 1.12%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2        | 1.12%   |
| Nvidia GA102GL [RTX A5000]                                                               | 2        | 1.12%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.12%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 2        | 1.12%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 1.12%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2        | 1.12%   |
| AMD Raphael                                                                              | 2        | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 1.12%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 2        | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 1.12%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 58       | 36.94%  |
| 1 x Intel       | 50       | 31.85%  |
| 1 x AMD         | 35       | 22.29%  |
| Intel + Nvidia  | 10       | 6.37%   |
| AMD + Nvidia    | 2        | 1.27%   |
| Nvidia + ASPEED | 1        | 0.64%   |
| Intel + AMD     | 1        | 0.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 101      | 63.92%  |
| Proprietary | 52       | 32.91%  |
| Unknown     | 5        | 3.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 69       | 43.67%  |
| 1.01-2.0   | 22       | 13.92%  |
| 3.01-4.0   | 16       | 10.13%  |
| 7.01-8.0   | 12       | 7.59%   |
| 0.51-1.0   | 11       | 6.96%   |
| 8.01-16.0  | 10       | 6.33%   |
| 5.01-6.0   | 8        | 5.06%   |
| 0.01-0.5   | 8        | 5.06%   |
| 2.01-3.0   | 1        | 0.63%   |
| 16.01-24.0 | 1        | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 43       | 30.07%  |
| Samsung Electronics  | 21       | 14.69%  |
| Goldstar             | 15       | 10.49%  |
| AOC                  | 8        | 5.59%   |
| Acer                 | 7        | 4.9%    |
| ViewSonic            | 6        | 4.2%    |
| Hewlett-Packard      | 6        | 4.2%    |
| ASUSTek Computer     | 4        | 2.8%    |
| Ancor Communications | 4        | 2.8%    |
| Panasonic            | 3        | 2.1%    |
| Unknown              | 3        | 2.1%    |
| Sony                 | 2        | 1.4%    |
| Gigabyte Technology  | 2        | 1.4%    |
| Fujitsu              | 2        | 1.4%    |
| FPT                  | 2        | 1.4%    |
| BenQ                 | 2        | 1.4%    |
| VSP                  | 1        | 0.7%    |
| Unknown (ADA)        | 1        | 0.7%    |
| Philips              | 1        | 0.7%    |
| NEC Computers        | 1        | 0.7%    |
| Mi                   | 1        | 0.7%    |
| LG Electronics       | 1        | 0.7%    |
| Lenovo Group Limited | 1        | 0.7%    |
| Lenovo               | 1        | 0.7%    |
| IPS                  | 1        | 0.7%    |
| HPN                  | 1        | 0.7%    |
| HOP                  | 1        | 0.7%    |
| CGC                  | 1        | 0.7%    |
| AUS                  | 1        | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Dell SE198WFP DELF004 1440x900 410x260mm 19.1-inch                      | 4        | 2.7%    |
| Panasonic TV MEIC33B 1366x768 521x293mm 23.5-inch                       | 3        | 2.03%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                       | 3        | 2.03%   |
| AOC G2460PG AOC2460 1920x1080 531x299mm 24.0-inch                       | 3        | 2.03%   |
| Unknown                                                                 | 3        | 2.03%   |
| Samsung Electronics SME1720NR SAM0696 1280x1024 338x270mm 17.0-inch     | 2        | 1.35%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch        | 2        | 1.35%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 2        | 1.35%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                    | 2        | 1.35%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2        | 1.35%   |
| Fujitsu VL-17BSE FUJE711 1280x1024 338x270mm 17.0-inch                  | 2        | 1.35%   |
| FPT F22FAD FPTF22F 1920x1080 477x268mm 21.5-inch                        | 2        | 1.35%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                       | 2        | 1.35%   |
| Dell LCD Monitor P2419H 1920x1080                                       | 2        | 1.35%   |
| Dell E2016H DELA0C7 1600x900 432x236mm 19.4-inch                        | 2        | 1.35%   |
| Acer LCD Monitor EK241Y 1920x1080                                       | 2        | 1.35%   |
| Acer EK241Y ACR0755 1920x1080 527x296mm 23.8-inch                       | 2        | 1.35%   |
| VSP IP2407S VSP0995 1920x1080 530x290mm 23.8-inch                       | 1        | 0.68%   |
| ViewSonic VX2480-2K VSC7B3B 2560x1440 530x300mm 24.0-inch               | 1        | 0.68%   |
| ViewSonic VG2239 Series VSCC42B 1920x1080 477x268mm 21.5-inch           | 1        | 0.68%   |
| ViewSonic VA2409-FHD VSC983D 1920x1080 521x293mm 23.5-inch              | 1        | 0.68%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 477x268mm 21.5-inch              | 1        | 0.68%   |
| ViewSonic VA2201-FHD VSC683B 1920x1080 479x260mm 21.5-inch              | 1        | 0.68%   |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                               | 1        | 0.68%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch           | 1        | 0.68%   |
| Sony TV SNYAC03 1360x768                                                | 1        | 0.68%   |
| Sony TV SNY8E03 1920x1080                                               | 1        | 0.68%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 1        | 0.68%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.68%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch       | 1        | 0.68%   |
| Samsung Electronics S20D300 SAM0B39 1600x900 432x240mm 19.5-inch        | 1        | 0.68%   |
| Samsung Electronics S20B370 SAM08B7 1600x900 443x249mm 20.0-inch        | 1        | 0.68%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch        | 1        | 0.68%   |
| Samsung Electronics S19C300 SAM0A12 1366x768 410x230mm 18.5-inch        | 1        | 0.68%   |
| Samsung Electronics S19C170 SAM0B02 1366x768 410x230mm 18.5-inch        | 1        | 0.68%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SME1720NR 1280x1024                     | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SMB1930N                                | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM7129 3840x2160 950x540mm 43.0-inch   | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 1872x1053mm 84.6-inch | 1        | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 69       | 48.59%  |
| 3840x2160 (4K)    | 12       | 8.45%   |
| 2560x1440 (QHD)   | 12       | 8.45%   |
| 1600x900 (HD+)    | 11       | 7.75%   |
| 1280x1024 (SXGA)  | 10       | 7.04%   |
| 1366x768 (WXGA)   | 9        | 6.34%   |
| 1440x900 (WXGA+)  | 6        | 4.23%   |
| Unknown           | 4        | 2.82%   |
| 1920x1200 (WUXGA) | 2        | 1.41%   |
| 1360x768          | 2        | 1.41%   |
| 3840x1080         | 1        | 0.7%    |
| 3440x1440         | 1        | 0.7%    |
| 3286x1080         | 1        | 0.7%    |
| 2560x1080         | 1        | 0.7%    |
| 1280x800 (WXGA)   | 1        | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 23       | 16.08%  |
| 21      | 23       | 16.08%  |
| Unknown | 21       | 14.69%  |
| 23      | 17       | 11.89%  |
| 27      | 15       | 10.49%  |
| 19      | 10       | 6.99%   |
| 20      | 7        | 4.9%    |
| 17      | 7        | 4.9%    |
| 18      | 6        | 4.2%    |
| 84      | 3        | 2.1%    |
| 40      | 2        | 1.4%    |
| 34      | 2        | 1.4%    |
| 31      | 2        | 1.4%    |
| 25      | 2        | 1.4%    |
| 72      | 1        | 0.7%    |
| 42      | 1        | 0.7%    |
| 7       | 1        | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 55       | 39.01%  |
| 401-500     | 43       | 30.5%   |
| Unknown     | 21       | 14.89%  |
| 301-350     | 6        | 4.26%   |
| 1501-2000   | 4        | 2.84%   |
| 601-700     | 3        | 2.13%   |
| 351-400     | 3        | 2.13%   |
| 801-900     | 2        | 1.42%   |
| 701-800     | 2        | 1.42%   |
| 101-200     | 1        | 0.71%   |
| 901-1000    | 1        | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 97       | 70.8%   |
| Unknown | 20       | 14.6%   |
| 16/10   | 9        | 6.57%   |
| 5/4     | 8        | 5.84%   |
| 21/9    | 2        | 1.46%   |
| 3/2     | 1        | 0.73%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 52       | 36.62%  |
| 151-200        | 23       | 16.2%   |
| Unknown        | 21       | 14.79%  |
| 301-350        | 15       | 10.56%  |
| 141-150        | 12       | 8.45%   |
| 251-300        | 6        | 4.23%   |
| More than 1000 | 4        | 2.82%   |
| 351-500        | 4        | 2.82%   |
| 501-1000       | 3        | 2.11%   |
| 1-40           | 1        | 0.7%    |
| 131-140        | 1        | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 81       | 57.45%  |
| 101-120 | 30       | 21.28%  |
| Unknown | 21       | 14.89%  |
| 161-240 | 4        | 2.84%   |
| 121-160 | 4        | 2.84%   |
| 1-50    | 1        | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 131      | 82.91%  |
| 0     | 17       | 10.76%  |
| 2     | 10       | 6.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 105      | 47.3%   |
| Intel                 | 60       | 27.03%  |
| Qualcomm Atheros      | 10       | 4.5%    |
| Ralink Technology     | 9        | 4.05%   |
| Broadcom              | 9        | 4.05%   |
| TP-Link               | 7        | 3.15%   |
| ASIX Electronics      | 5        | 2.25%   |
| MediaTek              | 4        | 1.8%    |
| Ralink                | 3        | 1.35%   |
| D-Link                | 2        | 0.9%    |
| Broadcom Limited      | 2        | 0.9%    |
| Samsung Electronics   | 1        | 0.45%   |
| Novatel Wireless      | 1        | 0.45%   |
| ICS Advent            | 1        | 0.45%   |
| Edimax Technology     | 1        | 0.45%   |
| Aquantia              | 1        | 0.45%   |
| Unknown               | 1        | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 86       | 34.68%  |
| Realtek RTL8125 2.5GbE Controller                                      | 9        | 3.63%   |
| Intel Ethernet Connection (7) I219-V                                   | 9        | 3.63%   |
| Intel Wi-Fi 6 AX200                                                    | 7        | 2.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 2.02%   |
| Intel Ethernet Connection I217-LM                                      | 5        | 2.02%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 1.61%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 1.61%   |
| Intel I210 Gigabit Network Connection                                  | 4        | 1.61%   |
| Intel Ethernet Controller I225-V                                       | 4        | 1.61%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 1.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 3        | 1.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3        | 1.21%   |
| Realtek 802.11ac NIC                                                   | 3        | 1.21%   |
| Intel Wireless 7260                                                    | 3        | 1.21%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3        | 1.21%   |
| ASIX AX88772A Fast Ethernet                                            | 3        | 1.21%   |
| TP-Link 802.11ac NIC                                                   | 2        | 0.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.81%   |
| Ralink RT5370 Wireless Adapter                                         | 2        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2        | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2        | 0.81%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2        | 0.81%   |
| Intel Wireless 7265                                                    | 2        | 0.81%   |
| Intel Ethernet Connection I217-V                                       | 2        | 0.81%   |
| Intel Ethernet Connection (2) I218-LM                                  | 2        | 0.81%   |
| Intel Ethernet Connection (12) I219-V                                  | 2        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 0.81%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.81%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 0.81%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                         | 2        | 0.81%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                  | 2        | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2        | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2        | 0.81%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 0.4%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 20       | 27.4%   |
| Realtek Semiconductor | 16       | 21.92%  |
| Ralink Technology     | 9        | 12.33%  |
| TP-Link               | 7        | 9.59%   |
| Qualcomm Atheros      | 5        | 6.85%   |
| Broadcom              | 5        | 6.85%   |
| Ralink                | 3        | 4.11%   |
| MediaTek              | 3        | 4.11%   |
| D-Link                | 2        | 2.74%   |
| Broadcom Limited      | 2        | 2.74%   |
| Edimax Technology     | 1        | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 7        | 9.59%   |
| Ralink MT7601U Wireless Adapter                                      | 4        | 5.48%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 3        | 4.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 4.11%   |
| Realtek 802.11ac NIC                                                 | 3        | 4.11%   |
| Intel Wireless 7260                                                  | 3        | 4.11%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 3        | 4.11%   |
| TP-Link 802.11ac NIC                                                 | 2        | 2.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2        | 2.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2        | 2.74%   |
| Ralink RT5370 Wireless Adapter                                       | 2        | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2        | 2.74%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2        | 2.74%   |
| Intel Wireless 7265                                                  | 2        | 2.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2        | 2.74%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 2        | 2.74%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2        | 2.74%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 1.37%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1        | 1.37%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1        | 1.37%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1        | 1.37%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 1.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 1.37%   |
| Ralink RT2070 Wireless Adapter                                       | 1        | 1.37%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                    | 1        | 1.37%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1        | 1.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 1        | 1.37%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 1        | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 1.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1        | 1.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 1        | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1        | 1.37%   |
| Intel Wireless 3165                                                  | 1        | 1.37%   |
| Intel Wireless 3160                                                  | 1        | 1.37%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1        | 1.37%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 1        | 1.37%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1        | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 101      | 60.12%  |
| Intel                 | 49       | 29.17%  |
| Qualcomm Atheros      | 5        | 2.98%   |
| ASIX Electronics      | 5        | 2.98%   |
| Broadcom              | 4        | 2.38%   |
| Samsung Electronics   | 1        | 0.6%    |
| MediaTek              | 1        | 0.6%    |
| ICS Advent            | 1        | 0.6%    |
| Aquantia              | 1        | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 86       | 49.71%  |
| Realtek RTL8125 2.5GbE Controller                                              | 9        | 5.2%    |
| Intel Ethernet Connection (7) I219-V                                           | 9        | 5.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5        | 2.89%   |
| Intel Ethernet Connection I217-LM                                              | 5        | 2.89%   |
| Intel I211 Gigabit Network Connection                                          | 4        | 2.31%   |
| Intel I210 Gigabit Network Connection                                          | 4        | 2.31%   |
| Intel Ethernet Controller I225-V                                               | 4        | 2.31%   |
| Intel Ethernet Connection (2) I219-V                                           | 4        | 2.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4        | 2.31%   |
| ASIX AX88772A Fast Ethernet                                                    | 3        | 1.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2        | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2        | 1.16%   |
| Intel Ethernet Connection I217-V                                               | 2        | 1.16%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2        | 1.16%   |
| Intel Ethernet Connection (12) I219-V                                          | 2        | 1.16%   |
| Intel 82579V Gigabit Network Connection                                        | 2        | 1.16%   |
| Intel 82574L Gigabit Network Connection                                        | 2        | 1.16%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 2        | 1.16%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2        | 1.16%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 0.58%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1        | 0.58%   |
| MediaTek Infinix NOTE 30 VIP                                                   | 1        | 0.58%   |
| Intel Ethernet Controller I226-V                                               | 1        | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.58%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 0.58%   |
| Intel Ethernet Connection (2) I218-V                                           | 1        | 0.58%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1        | 0.58%   |
| Intel Ethernet Connection (14) I219-V                                          | 1        | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1        | 0.58%   |
| Intel 82562V-2 10/100 Network Connection                                       | 1        | 0.58%   |
| Intel 82541PI Gigabit Ethernet Controller                                      | 1        | 0.58%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1        | 0.58%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 1        | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1        | 0.58%   |
| Aquantia Antigua NBase-T/IEEE 802.3an Ethernet Controller - Engineering Sample | 1        | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 154      | 68.44%  |
| WiFi     | 69       | 30.67%  |
| Modem    | 1        | 0.44%   |
| Unknown  | 1        | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 112      | 70%     |
| WiFi     | 47       | 29.38%  |
| Modem    | 1        | 0.63%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 100      | 63.29%  |
| 2     | 46       | 29.11%  |
| 3     | 10       | 6.33%   |
| 4     | 1        | 0.63%   |
| 0     | 1        | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 121      | 77.56%  |
| Yes  | 35       | 22.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 19       | 32.76%  |
| Cambridge Silicon Radio         | 16       | 27.59%  |
| Realtek Semiconductor           | 8        | 13.79%  |
| Foxconn / Hon Hai               | 3        | 5.17%   |
| Qualcomm Atheros Communications | 2        | 3.45%   |
| IMC Networks                    | 2        | 3.45%   |
| Broadcom                        | 2        | 3.45%   |
| Apple                           | 2        | 3.45%   |
| TP-Link                         | 1        | 1.72%   |
| Ralink                          | 1        | 1.72%   |
| Lite-On Technology              | 1        | 1.72%   |
| Conwise Technology              | 1        | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16       | 27.59%  |
| Realtek Bluetooth Radio                             | 7        | 12.07%  |
| Intel AX200 Bluetooth                               | 7        | 12.07%  |
| Intel Bluetooth wireless interface                  | 6        | 10.34%  |
| Intel AX210 Bluetooth                               | 3        | 5.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 3.45%   |
| Foxconn / Hon Hai Wireless_Device                   | 2        | 3.45%   |
| Apple Bluetooth Host Controller                     | 2        | 3.45%   |
| TP-Link UB500 Adapter                               | 1        | 1.72%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.72%   |
| Ralink RT3290 Bluetooth                             | 1        | 1.72%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 1.72%   |
| Lite-On Bluetooth Radio                             | 1        | 1.72%   |
| Intel AX211 Bluetooth                               | 1        | 1.72%   |
| IMC Networks Wireless_Device                        | 1        | 1.72%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.72%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1        | 1.72%   |
| Conwise CW6622                                      | 1        | 1.72%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1        | 1.72%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1        | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 120      | 44.78%  |
| Nvidia                    | 70       | 26.12%  |
| AMD                       | 46       | 17.16%  |
| Generalplus Technology    | 5        | 1.87%   |
| C-Media Electronics       | 4        | 1.49%   |
| Logitech                  | 3        | 1.12%   |
| Audient                   | 3        | 1.12%   |
| JMTek                     | 2        | 0.75%   |
| Creative Labs             | 2        | 0.75%   |
| ASUSTek Computer          | 2        | 0.75%   |
| Texas Instruments         | 1        | 0.37%   |
| Shenzhen Rapoo Technology | 1        | 0.37%   |
| Nordic Semiconductor ASA  | 1        | 0.37%   |
| Kingston Technology       | 1        | 0.37%   |
| GYROCOM C&C               | 1        | 0.37%   |
| FIFINE Microphones        | 1        | 0.37%   |
| Elgato Systems            | 1        | 0.37%   |
| Creative Technology       | 1        | 0.37%   |
| Conexant Systems          | 1        | 0.37%   |
| Apple                     | 1        | 0.37%   |
| AGPTek                    | 1        | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20       | 6.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15       | 4.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 4.58%   |
| Intel Cannon Lake PCH cAVS                                                 | 13       | 4.25%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 3.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10       | 3.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10       | 3.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10       | 3.27%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10       | 3.27%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 2.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 2.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 2.61%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7        | 2.29%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 1.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 1.96%   |
| Nvidia TU102 High Definition Audio Controller                              | 5        | 1.63%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 1.63%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 1.63%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 1.63%   |
| Generalplus Technology USB Audio Device                                    | 5        | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 1.63%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 1.31%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 1.31%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1.31%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.31%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.31%   |
| Nvidia High Definition Audio Controller                                    | 3        | 0.98%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 0.98%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 0.98%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.98%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.98%   |
| Audient EVO4                                                               | 3        | 0.98%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.65%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 0.65%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.65%   |
| JMTek USB PnP Audio Device                                                 | 2        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Kingston              | 30       | 26.09%  |
| G.Skill               | 17       | 14.78%  |
| Corsair               | 16       | 13.91%  |
| Samsung Electronics   | 9        | 7.83%   |
| SK hynix              | 7        | 6.09%   |
| Unknown               | 6        | 5.22%   |
| Kingmax               | 6        | 5.22%   |
| Micron Technology     | 5        | 4.35%   |
| Crucial               | 3        | 2.61%   |
| A-DATA Technology     | 3        | 2.61%   |
| Team                  | 2        | 1.74%   |
| Ramaxel Technology    | 2        | 1.74%   |
| Unknown               | 2        | 1.74%   |
| PNY                   | 1        | 0.87%   |
| Patriot               | 1        | 0.87%   |
| Nanya Technology      | 1        | 0.87%   |
| Kingmax Semiconductor | 1        | 0.87%   |
| AVEXIR                | 1        | 0.87%   |
| ASint Technology      | 1        | 0.87%   |
| Apacer                | 1        | 0.87%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 5        | 3.94%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3066MT/s   | 5        | 3.94%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 3        | 2.36%   |
| G.Skill RAM F4-3600C18-16GTZN 16GB DIMM DDR4 3666MT/s  | 3        | 2.36%   |
| Unknown RAM Module 1GB DIMM 800MT/s                    | 2        | 1.57%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 2        | 1.57%   |
| Kingston RAM SNY1600S11-4G-ED 4GB SODIMM DDR3 1066MT/s | 2        | 1.57%   |
| Kingmax RAM FLGF65F-D8KMB 4096MB DIMM DDR3 1600MT/s    | 2        | 1.57%   |
| G.Skill RAM F4-3000C16-16GTZR 16GB DIMM DDR4 3000MT/s  | 2        | 1.57%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s | 2        | 1.57%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s  | 2        | 1.57%   |
| Unknown                                                | 2        | 1.57%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s           | 1        | 0.79%   |
| Unknown RAM Module 2048MB DIMM DDR2 200MT/s            | 1        | 0.79%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s             | 1        | 0.79%   |
| Unknown RAM BAPC08G3000D4T8 8192MB DIMM DDR4 2133MT/s  | 1        | 0.79%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1067MT/s     | 1        | 0.79%   |
| Team RAM TEAMGROUP-UD3-160 4096MB DIMM DDR3 1333MT/s   | 1        | 0.79%   |
| SK hynix RAM SNOAMOO Ltd:016M00 4GB DIMM DDR3 1600MT/s | 1        | 0.79%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s    | 1        | 0.79%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.79%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DIMM DDR3 1600MT/s   | 1        | 0.79%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s | 1        | 0.79%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.79%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s  | 1        | 0.79%   |
| SK hynix RAM HMA42GR7AFR4N-TF 16GB DIMM DDR4 2133MT/s  | 1        | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s    | 1        | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s  | 1        | 0.79%   |
| Samsung RAM M393B2K70CM0-YF8 16GB DIMM DDR3 1067MT/s   | 1        | 0.79%   |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1866MT/s       | 1        | 0.79%   |
| Samsung RAM M393A2K40BB1-CRC 16GB DIMM DDR4 2400MT/s   | 1        | 0.79%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s   | 1        | 0.79%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2400MT/s   | 1        | 0.79%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 0.79%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s    | 1        | 0.79%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB DIMM DDR3 1333MT/s  | 1        | 0.79%   |
| Ramaxel RAM RMR5040MM58F9F1600 4GB DIMM DDR3 1600MT/s  | 1        | 0.79%   |
| PNY RAM 8GBF1X08LFHH35-12-K 8GB DIMM DDR4 2667MT/s     | 1        | 0.79%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s         | 1        | 0.79%   |
| Nanya RAM M2F4GH64CB8HB6N-CG 4GB DIMM DDR3 1333MT/s    | 1        | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 57       | 57.58%  |
| DDR3    | 32       | 32.32%  |
| DDR5    | 3        | 3.03%   |
| DRAM    | 2        | 2.02%   |
| DDR2    | 2        | 2.02%   |
| Unknown | 2        | 2.02%   |
| DDR     | 1        | 1.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 89       | 90.82%  |
| SODIMM | 9        | 9.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 45       | 42.06%  |
| 16384 | 27       | 25.23%  |
| 4096  | 27       | 25.23%  |
| 1024  | 4        | 3.74%   |
| 32768 | 2        | 1.87%   |
| 2048  | 2        | 1.87%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 21       | 18.42%  |
| 3200  | 17       | 14.91%  |
| 2400  | 10       | 8.77%   |
| 1333  | 9        | 7.89%   |
| 2667  | 6        | 5.26%   |
| 3066  | 5        | 4.39%   |
| 3733  | 4        | 3.51%   |
| 3000  | 4        | 3.51%   |
| 3666  | 3        | 2.63%   |
| 3600  | 3        | 2.63%   |
| 2666  | 3        | 2.63%   |
| 1066  | 3        | 2.63%   |
| 800   | 3        | 2.63%   |
| 3466  | 2        | 1.75%   |
| 3400  | 2        | 1.75%   |
| 2800  | 2        | 1.75%   |
| 2133  | 2        | 1.75%   |
| 1866  | 2        | 1.75%   |
| 1067  | 2        | 1.75%   |
| 6400  | 1        | 0.88%   |
| 5600  | 1        | 0.88%   |
| 5200  | 1        | 0.88%   |
| 3334  | 1        | 0.88%   |
| 3007  | 1        | 0.88%   |
| 2448  | 1        | 0.88%   |
| 1867  | 1        | 0.88%   |
| 1800  | 1        | 0.88%   |
| 1648  | 1        | 0.88%   |
| 200   | 1        | 0.88%   |
| 133   | 1        | 0.88%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Ricoh                 | 1        | 33.33%  |
| Intermec Technologies | 1        | 33.33%  |
| Brother Industries    | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Ricoh Printing Support   | 1        | 33.33%  |
| Intermec PC43t           | 1        | 33.33%  |
| Brother HL-L2360D series | 1        | 33.33%  |

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


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech                        | 5        | 29.41%  |
| Sonix Technology                | 1        | 5.88%   |
| Samsung Electronics             | 1        | 5.88%   |
| Realtek Semiconductor           | 1        | 5.88%   |
| Microdia                        | 1        | 5.88%   |
| KYE Systems (Mouse Systems)     | 1        | 5.88%   |
| Intel                           | 1        | 5.88%   |
| IDS Imaging Development Systems | 1        | 5.88%   |
| Aveo Technology                 | 1        | 5.88%   |
| Apple                           | 1        | 5.88%   |
| Alpha Imaging Technology        | 1        | 5.88%   |
| Alcor Micro                     | 1        | 5.88%   |
| 04004000_P040200_SN0002         | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 3        | 17.65%  |
| Sonix SHUNCCM                                  | 1        | 5.88%   |
| Samsung Galaxy series, misc. (MTP mode)        | 1        | 5.88%   |
| Realtek Dell_Monitor_IR_Webcam                 | 1        | 5.88%   |
| Microdia Rapoo Camera                          | 1        | 5.88%   |
| Logitech Webcam C310                           | 1        | 5.88%   |
| Logitech Webcam C210                           | 1        | 5.88%   |
| KYE Systems (Mouse Systems) Genius Webcam      | 1        | 5.88%   |
| Intel RealSense Depth Camera 435               | 1        | 5.88%   |
| IDS Imaging Development Systems USB 3.0 Camera | 1        | 5.88%   |
| Aveo USB2.0 Camera                             | 1        | 5.88%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                | 1        | 5.88%   |
| Alpha Imaging DS-2CS54U0B-SD                   | 1        | 5.88%   |
| Alcor Micro USB 2.0 PC Camera                  | 1        | 5.88%   |
| 04004000_P040200_SN0002 1080P Web Camera       | 1        | 5.88%   |

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
| 0     | 136      | 87.18%  |
| 1     | 17       | 10.9%   |
| 2     | 2        | 1.28%   |
| 3     | 1        | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 11       | 45.83%  |
| Unassigned class         | 6        | 25%     |
| Net/wireless             | 3        | 12.5%   |
| Communication controller | 2        | 8.33%   |
| Camera                   | 1        | 4.17%   |
| Bluetooth                | 1        | 4.17%   |

