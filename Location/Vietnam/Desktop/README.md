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

Total: 164

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 25       | 20%     |
| Ubuntu 18.04                 | 16       | 12.8%   |
| Ubuntu 22.04                 | 7        | 5.6%    |
| OpenMandriva 23.03           | 5        | 4%      |
| Fedora 37                    | 5        | 4%      |
| Arch Rolling                 | 5        | 4%      |
| Arch                         | 5        | 4%      |
| Manjaro                      | 4        | 3.2%    |
| Zorin 16                     | 3        | 2.4%    |
| Debian 11                    | 3        | 2.4%    |
| Debian 10                    | 3        | 2.4%    |
| ArcoLinux Rolling            | 3        | 2.4%    |
| Ubuntu Unity 16.04           | 2        | 1.6%    |
| Ubuntu 19.04                 | 2        | 1.6%    |
| Pop!_OS 20.10                | 2        | 1.6%    |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 1.6%    |
| Manjaro 20.2                 | 2        | 1.6%    |
| Linux Mint 20.3              | 2        | 1.6%    |
| Gentoo 2.13                  | 2        | 1.6%    |
| Fedora 38                    | 2        | 1.6%    |
| Zorin 15                     | 1        | 0.8%    |
| Xubuntu 20.04                | 1        | 0.8%    |
| Ubuntu 21.04                 | 1        | 0.8%    |
| Ubuntu 16.04                 | 1        | 0.8%    |
| Pop!_OS 22.04                | 1        | 0.8%    |
| Parrot 4.11                  | 1        | 0.8%    |
| OpenMandriva 4.50            | 1        | 0.8%    |
| OpenMandriva 4.3             | 1        | 0.8%    |
| OpenMandriva 4.2             | 1        | 0.8%    |
| OpenMandriva 23.01           | 1        | 0.8%    |
| Manjaro 21.0.1               | 1        | 0.8%    |
| Manjaro 20.0.3               | 1        | 0.8%    |
| Linux Mint 21.1              | 1        | 0.8%    |
| Linux Mint 20                | 1        | 0.8%    |
| Kubuntu 22.04                | 1        | 0.8%    |
| Kubuntu 20.04                | 1        | 0.8%    |
| KDE neon 22.04               | 1        | 0.8%    |
| KDE neon 20.04               | 1        | 0.8%    |
| Gentoo 2.9                   | 1        | 0.8%    |
| Fedora 36                    | 1        | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 50       | 40.65%  |
| Arch         | 10       | 8.13%   |
| OpenMandriva | 9        | 7.32%   |
| Manjaro      | 8        | 6.5%    |
| Fedora       | 8        | 6.5%    |
| Debian       | 7        | 5.69%   |
| Zorin        | 4        | 3.25%   |
| Linux Mint   | 4        | 3.25%   |
| Pop!_OS      | 3        | 2.44%   |
| Gentoo       | 3        | 2.44%   |
| ArcoLinux    | 3        | 2.44%   |
| Ubuntu Unity | 2        | 1.63%   |
| openSUSE     | 2        | 1.63%   |
| Kubuntu      | 2        | 1.63%   |
| KDE neon     | 2        | 1.63%   |
| Clear Linux  | 2        | 1.63%   |
| Xubuntu      | 1        | 0.81%   |
| Parrot       | 1        | 0.81%   |
| EndeavourOS  | 1        | 0.81%   |
| Elementary   | 1        | 0.81%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| 6.2.6-desktop-1omv2390                                 | 5        | 3.76%   |
| 5.4.0-58-generic                                       | 4        | 3.01%   |
| 5.4.0-37-generic                                       | 3        | 2.26%   |
| 5.4.0-26-generic                                       | 3        | 2.26%   |
| 5.15.0-52-generic                                      | 3        | 2.26%   |
| 5.11.0-38-generic                                      | 3        | 2.26%   |
| 5.0.0-23-generic                                       | 3        | 2.26%   |
| 6.0.12-300.fc37.x86_64                                 | 2        | 1.5%    |
| 5.9.11-3-MANJARO                                       | 2        | 1.5%    |
| 5.8.0-7642-generic                                     | 2        | 1.5%    |
| 5.4.0-48-generic                                       | 2        | 1.5%    |
| 5.4.0-47-generic                                       | 2        | 1.5%    |
| 5.4.0-42-generic                                       | 2        | 1.5%    |
| 5.11.0-37-generic                                      | 2        | 1.5%    |
| 4.18.0-25-generic                                      | 2        | 1.5%    |
| 6.4.3-arch1-1                                          | 1        | 0.75%   |
| 6.4.12-200.fc38.x86_64                                 | 1        | 0.75%   |
| 6.4.0-0.rc5.20230607gta4d7d701.342.vanilla.fc38.x86_64 | 1        | 0.75%   |
| 6.3.9-arch1-1                                          | 1        | 0.75%   |
| 6.3.0-gentoo                                           | 1        | 0.75%   |
| 6.2.9-060209-generic                                   | 1        | 0.75%   |
| 6.2.6-76060206-generic                                 | 1        | 0.75%   |
| 6.2.6-1-pve                                            | 1        | 0.75%   |
| 6.2.0-pf2-llvm                                         | 1        | 0.75%   |
| 6.1.31-2-MANJARO                                       | 1        | 0.75%   |
| 6.1.15-1-pve                                           | 1        | 0.75%   |
| 6.1.13-200.fc37.x86_64                                 | 1        | 0.75%   |
| 6.1.12-gentoonovirt                                    | 1        | 0.75%   |
| 6.1.11-200.fc37.x86_64                                 | 1        | 0.75%   |
| 6.1.11-1-MANJARO                                       | 1        | 0.75%   |
| 6.1.10-200.fc37.x86_64                                 | 1        | 0.75%   |
| 6.1.1-desktop-1omv2290                                 | 1        | 0.75%   |
| 6.1.0-8-amd64                                          | 1        | 0.75%   |
| 6.0.2-x64v1-xanmod1-1                                  | 1        | 0.75%   |
| 6.0.0-rc5                                              | 1        | 0.75%   |
| 5.9.12-arch1-1                                         | 1        | 0.75%   |
| 5.9.0-0.bpo.5-amd64                                    | 1        | 0.75%   |
| 5.8.0-59-generic                                       | 1        | 0.75%   |
| 5.8.0-55-generic                                       | 1        | 0.75%   |
| 5.8.0-53-generic                                       | 1        | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 23       | 17.83%  |
| 5.15.0  | 13       | 10.08%  |
| 5.11.0  | 9        | 6.98%   |
| 5.8.0   | 8        | 6.2%    |
| 6.2.6   | 7        | 5.43%   |
| 5.0.0   | 6        | 4.65%   |
| 4.15.0  | 6        | 4.65%   |
| 6.1.11  | 2        | 1.55%   |
| 6.0.12  | 2        | 1.55%   |
| 5.9.11  | 2        | 1.55%   |
| 5.15.60 | 2        | 1.55%   |
| 5.12.8  | 2        | 1.55%   |
| 4.18.0  | 2        | 1.55%   |
| 6.4.3   | 1        | 0.78%   |
| 6.4.12  | 1        | 0.78%   |
| 6.4.0   | 1        | 0.78%   |
| 6.3.9   | 1        | 0.78%   |
| 6.3.0   | 1        | 0.78%   |
| 6.2.9   | 1        | 0.78%   |
| 6.2.0   | 1        | 0.78%   |
| 6.1.31  | 1        | 0.78%   |
| 6.1.15  | 1        | 0.78%   |
| 6.1.13  | 1        | 0.78%   |
| 6.1.12  | 1        | 0.78%   |
| 6.1.10  | 1        | 0.78%   |
| 6.1.1   | 1        | 0.78%   |
| 6.1.0   | 1        | 0.78%   |
| 6.0.2   | 1        | 0.78%   |
| 6.0.0   | 1        | 0.78%   |
| 5.9.12  | 1        | 0.78%   |
| 5.9.0   | 1        | 0.78%   |
| 5.6.15  | 1        | 0.78%   |
| 5.6.0   | 1        | 0.78%   |
| 5.4.78  | 1        | 0.78%   |
| 5.4.18  | 1        | 0.78%   |
| 5.19.7  | 1        | 0.78%   |
| 5.19.4  | 1        | 0.78%   |
| 5.19.3  | 1        | 0.78%   |
| 5.19.17 | 1        | 0.78%   |
| 5.19.12 | 1        | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 25       | 19.53%  |
| 5.15    | 15       | 11.72%  |
| 5.11    | 10       | 7.81%   |
| 6.2     | 9        | 7.03%   |
| 6.1     | 9        | 7.03%   |
| 5.8     | 8        | 6.25%   |
| 4.15    | 7        | 5.47%   |
| 5.0     | 6        | 4.69%   |
| 5.19    | 5        | 3.91%   |
| 5.10    | 5        | 3.91%   |
| 6.0     | 4        | 3.13%   |
| 5.9     | 4        | 3.13%   |
| 5.12    | 4        | 3.13%   |
| 6.4     | 3        | 2.34%   |
| 6.3     | 2        | 1.56%   |
| 5.6     | 2        | 1.56%   |
| 5.17    | 2        | 1.56%   |
| 4.19    | 2        | 1.56%   |
| 4.18    | 2        | 1.56%   |
| 5.18    | 1        | 0.78%   |
| 5.16    | 1        | 0.78%   |
| 5.14    | 1        | 0.78%   |
| 4.10    | 1        | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 121      | 99.18%  |
| i686   | 1        | 0.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 65       | 52.42%  |
| Unknown    | 21       | 16.94%  |
| KDE5       | 19       | 15.32%  |
| XFCE       | 4        | 3.23%   |
| MATE       | 3        | 2.42%   |
| X-Cinnamon | 2        | 1.61%   |
| Unity      | 2        | 1.61%   |
| KDE        | 2        | 1.61%   |
| Pantheon   | 1        | 0.81%   |
| LXQt       | 1        | 0.81%   |
| i3         | 1        | 0.81%   |
| Cinnamon   | 1        | 0.81%   |
| bspwm      | 1        | 0.81%   |
| awesome    | 1        | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 87       | 69.6%   |
| Wayland | 22       | 17.6%   |
| Unknown | 10       | 8%      |
| Tty     | 6        | 4.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 57       | 46.34%  |
| GDM     | 25       | 20.33%  |
| SDDM    | 16       | 13.01%  |
| LightDM | 10       | 8.13%   |
| GDM3    | 10       | 8.13%   |
| TDM     | 4        | 3.25%   |
| XDM     | 1        | 0.81%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 98       | 79.67%  |
| Unknown | 13       | 10.57%  |
| vi_VN   | 7        | 5.69%   |
| en_GB   | 2        | 1.63%   |
| C       | 2        | 1.63%   |
| ru_RU   | 1        | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 71       | 57.72%  |
| BIOS | 52       | 42.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 94       | 75.81%  |
| Btrfs   | 15       | 12.1%   |
| Overlay | 9        | 7.26%   |
| Zfs     | 2        | 1.61%   |
| Unknown | 2        | 1.61%   |
| Tmpfs   | 1        | 0.81%   |
| F2fs    | 1        | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 56       | 45.53%  |
| Unknown | 55       | 44.72%  |
| MBR     | 12       | 9.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 78.86%  |
| Yes       | 26       | 21.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 52.42%  |
| Yes       | 59       | 47.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 38       | 31.15%  |
| ASUSTek Computer    | 30       | 24.59%  |
| MSI                 | 12       | 9.84%   |
| Hewlett-Packard     | 9        | 7.38%   |
| Dell                | 9        | 7.38%   |
| ASRock              | 4        | 3.28%   |
| Lenovo              | 3        | 2.46%   |
| GuoGuang            | 3        | 2.46%   |
| Wistron             | 2        | 1.64%   |
| Intel               | 2        | 1.64%   |
| Foxconn             | 2        | 1.64%   |
| Unknown             | 2        | 1.64%   |
| ZOTAC               | 1        | 0.82%   |
| T-bao               | 1        | 0.82%   |
| Shuttle             | 1        | 0.82%   |
| Koloe               | 1        | 0.82%   |
| Huanan              | 1        | 0.82%   |
| Colorful Technology | 1        | 0.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte H61M-DS2                  | 5        | 4.1%    |
| ASUS All Series                    | 3        | 2.46%   |
| Unknown                            | 3        | 2.46%   |
| MSI MS-7C89                        | 2        | 1.64%   |
| MSI MS-7B89                        | 2        | 1.64%   |
| MSI MS-7823                        | 2        | 1.64%   |
| GuoGuang IC2M1028V-J               | 2        | 1.64%   |
| Gigabyte G41M-ES2L                 | 2        | 1.64%   |
| Gigabyte B450M GAMING              | 2        | 1.64%   |
| Gigabyte B360M-D3H                 | 2        | 1.64%   |
| ASUS PRIME B450M-A                 | 2        | 1.64%   |
| ASUS P8H61-MX R2.0                 | 2        | 1.64%   |
| ASUS B75M-A                        | 2        | 1.64%   |
| Wistron FMVDD2A0H0                 | 1        | 0.82%   |
| Wistron FMVCEG40Y                  | 1        | 0.82%   |
| T-bao MINI PC                      | 1        | 0.82%   |
| Shuttle DS81D                      | 1        | 0.82%   |
| MSI MS-7C67                        | 1        | 0.82%   |
| MSI MS-7C37                        | 1        | 0.82%   |
| MSI MS-7C31                        | 1        | 0.82%   |
| MSI MS-7B98                        | 1        | 0.82%   |
| MSI MS-7A38                        | 1        | 0.82%   |
| MSI MS-7388                        | 1        | 0.82%   |
| Lenovo ThinkCentre M93p 10A8CTO1WW | 1        | 0.82%   |
| Lenovo ThinkCentre M92p m92p       | 1        | 0.82%   |
| Lenovo ThinkCentre M55e 9389AN1    | 1        | 0.82%   |
| Koloe Thurley                      | 1        | 0.82%   |
| Intel H81                          | 1        | 0.82%   |
| Intel DP55WG AAE57269-407          | 1        | 0.82%   |
| Huanan X79 249PC V2.1              | 1        | 0.82%   |
| HP Z620 Workstation                | 1        | 0.82%   |
| HP Z440 Workstation                | 1        | 0.82%   |
| HP Z2 Tower G4 Workstation         | 1        | 0.82%   |
| HP ProDesk 600 G1 SFF              | 1        | 0.82%   |
| HP p2-1221l                        | 1        | 0.82%   |
| HP EliteDesk 800 G1 DM             | 1        | 0.82%   |
| HP 510-p042l                       | 1        | 0.82%   |
| HP 500-504x                        | 1        | 0.82%   |
| HP 251-152l                        | 1        | 0.82%   |
| GuoGuang IC2M1028N                 | 1        | 0.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 8        | 6.56%   |
| Dell OptiPlex        | 6        | 4.92%   |
| Gigabyte H61M-DS2    | 5        | 4.1%    |
| ASUS ROG             | 4        | 3.28%   |
| Lenovo ThinkCentre   | 3        | 2.46%   |
| ASUS P8H61-MX        | 3        | 2.46%   |
| ASUS All             | 3        | 2.46%   |
| Unknown              | 3        | 2.46%   |
| MSI MS-7C89          | 2        | 1.64%   |
| MSI MS-7B89          | 2        | 1.64%   |
| MSI MS-7823          | 2        | 1.64%   |
| GuoGuang IC2M1028V-J | 2        | 1.64%   |
| Gigabyte X570        | 2        | 1.64%   |
| Gigabyte G41M-ES2L   | 2        | 1.64%   |
| Gigabyte B450M       | 2        | 1.64%   |
| Gigabyte B360M-D3H   | 2        | 1.64%   |
| ASUS B75M-A          | 2        | 1.64%   |
| Wistron FMVDD2A0H0   | 1        | 0.82%   |
| Wistron FMVCEG40Y    | 1        | 0.82%   |
| T-bao MINI           | 1        | 0.82%   |
| Shuttle DS81D        | 1        | 0.82%   |
| MSI MS-7C67          | 1        | 0.82%   |
| MSI MS-7C37          | 1        | 0.82%   |
| MSI MS-7C31          | 1        | 0.82%   |
| MSI MS-7B98          | 1        | 0.82%   |
| MSI MS-7A38          | 1        | 0.82%   |
| MSI MS-7388          | 1        | 0.82%   |
| Koloe Thurley        | 1        | 0.82%   |
| Intel H81            | 1        | 0.82%   |
| Intel DP55WG         | 1        | 0.82%   |
| Huanan X79           | 1        | 0.82%   |
| HP Z620              | 1        | 0.82%   |
| HP Z440              | 1        | 0.82%   |
| HP Z2                | 1        | 0.82%   |
| HP ProDesk           | 1        | 0.82%   |
| HP p2-1221l          | 1        | 0.82%   |
| HP EliteDesk         | 1        | 0.82%   |
| HP 510-p042l         | 1        | 0.82%   |
| HP 500-504x          | 1        | 0.82%   |
| HP 251-152l          | 1        | 0.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 20       | 16.39%  |
| 2014 | 14       | 11.48%  |
| 2019 | 13       | 10.66%  |
| 2013 | 13       | 10.66%  |
| 2020 | 11       | 9.02%   |
| 2012 | 11       | 9.02%   |
| 2010 | 7        | 5.74%   |
| 2016 | 6        | 4.92%   |
| 2017 | 5        | 4.1%    |
| 2015 | 5        | 4.1%    |
| 2009 | 5        | 4.1%    |
| 2022 | 3        | 2.46%   |
| 2021 | 3        | 2.46%   |
| 2011 | 3        | 2.46%   |
| 2008 | 1        | 0.82%   |
| 2007 | 1        | 0.82%   |
| 2006 | 1        | 0.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 122      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 117      | 95.9%   |
| Enabled  | 5        | 4.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 122      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 31       | 25.2%   |
| 8.01-16.0   | 24       | 19.51%  |
| 3.01-4.0    | 19       | 15.45%  |
| 32.01-64.0  | 18       | 14.63%  |
| 4.01-8.0    | 15       | 12.2%   |
| 1.01-2.0    | 7        | 5.69%   |
| 24.01-32.0  | 5        | 4.07%   |
| 64.01-256.0 | 4        | 3.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 41       | 33.06%  |
| 1.01-2.0   | 34       | 27.42%  |
| 4.01-8.0   | 17       | 13.71%  |
| 3.01-4.0   | 16       | 12.9%   |
| 8.01-16.0  | 10       | 8.06%   |
| 0.51-1.0   | 3        | 2.42%   |
| 24.01-32.0 | 1        | 0.81%   |
| 16.01-24.0 | 1        | 0.81%   |
| 0.01-0.5   | 1        | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 54       | 42.86%  |
| 1      | 39       | 30.95%  |
| 3      | 20       | 15.87%  |
| 4      | 8        | 6.35%   |
| 5      | 3        | 2.38%   |
| 9      | 1        | 0.79%   |
| 0      | 1        | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 81.97%  |
| Yes       | 22       | 18.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 121      | 99.18%  |
| No        | 1        | 0.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 55.28%  |
| Yes       | 55       | 44.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 63.41%  |
| Yes       | 45       | 36.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Vietnam | 122      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Ho Chi Minh City | 67       | 54.47%  |
| Hanoi            | 30       | 24.39%  |
| Tua Chua         | 3        | 2.44%   |
| Can Tho          | 3        | 2.44%   |
| Bac Giang        | 3        | 2.44%   |
| Nga Bay          | 2        | 1.63%   |
| Da Nang          | 2        | 1.63%   |
| Vũng Tàu       | 1        | 0.81%   |
| Vi Thanh         | 1        | 0.81%   |
| Thai Nguyen      | 1        | 0.81%   |
| Tay Ninh         | 1        | 0.81%   |
| Quảng Ngai     | 1        | 0.81%   |
| Nha Trang        | 1        | 0.81%   |
| Nam Định      | 1        | 0.81%   |
| Hung Yen         | 1        | 0.81%   |
| Haiphong         | 1        | 0.81%   |
| Hai Duong        | 1        | 0.81%   |
| Di An            | 1        | 0.81%   |
| Bien Hoa         | 1        | 0.81%   |
| Bến Tre        | 1        | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 57       | 76     | 26.03%  |
| Seagate                     | 35       | 44     | 15.98%  |
| Samsung Electronics         | 26       | 36     | 11.87%  |
| Kingston                    | 12       | 15     | 5.48%   |
| Toshiba                     | 10       | 21     | 4.57%   |
| SanDisk                     | 6        | 6      | 2.74%   |
| Hitachi                     | 6        | 7      | 2.74%   |
| Unknown                     | 4        | 4      | 1.83%   |
| Lexar                       | 4        | 4      | 1.83%   |
| Intel                       | 4        | 4      | 1.83%   |
| HGST                        | 4        | 4      | 1.83%   |
| Crucial                     | 4        | 7      | 1.83%   |
| Colorful                    | 3        | 3      | 1.37%   |
| ZOTAC                       | 2        | 2      | 0.91%   |
| Transcend                   | 2        | 2      | 0.91%   |
| TO Exter                    | 2        | 3      | 0.91%   |
| SK hynix                    | 2        | 2      | 0.91%   |
| OCZ                         | 2        | 2      | 0.91%   |
| Netac                       | 2        | 2      | 0.91%   |
| Mushkin                     | 2        | 2      | 0.91%   |
| JMicron Technology          | 2        | 2      | 0.91%   |
| Gigabyte Technology         | 2        | 2      | 0.91%   |
| Fujitsu                     | 2        | 2      | 0.91%   |
| China                       | 2        | 2      | 0.91%   |
| XSTAR                       | 1        | 1      | 0.46%   |
| VSP                         | 1        | 1      | 0.46%   |
| Vaseky                      | 1        | 1      | 0.46%   |
| Realtek Semiconductor       | 1        | 2      | 0.46%   |
| Phison                      | 1        | 2      | 0.46%   |
| Patriot                     | 1        | 1      | 0.46%   |
| OSCOO                       | 1        | 1      | 0.46%   |
| Micron/Crucial Technology   | 1        | 1      | 0.46%   |
| Micron Technology           | 1        | 1      | 0.46%   |
| Maxtor                      | 1        | 1      | 0.46%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.46%   |
| LITEONIT                    | 1        | 1      | 0.46%   |
| Lite-On                     | 1        | 1      | 0.46%   |
| KIOXIA-EXCERIA              | 1        | 1      | 0.46%   |
| Kingston Technology Company | 1        | 1      | 0.46%   |
| KING                        | 1        | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 6        | 2.45%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 5        | 2.04%   |
| WDC WD2500AAKX-00ERMA0 250GB                        | 4        | 1.63%   |
| Seagate ST500DM002-1BD142 500GB                     | 4        | 1.63%   |
| Seagate ST1000DM010-2EP102 1TB                      | 4        | 1.63%   |
| Samsung SSD 860 EVO 250GB                           | 4        | 1.63%   |
| Kingston SA400S37240G 240GB SSD                     | 4        | 1.63%   |
| WDC WD5000LPLX-66ZNTT1 500GB                        | 3        | 1.22%   |
| WDC WD1502FYPS-02W3B0 1TB                           | 3        | 1.22%   |
| Unknown SD/MMC/MS PRO 1GB                           | 3        | 1.22%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 3        | 1.22%   |
| Samsung SSD 860 EVO 1TB                             | 3        | 1.22%   |
| ZOTAC SATA SSD 120GB                                | 2        | 0.82%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 2        | 0.82%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 2        | 0.82%   |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 2        | 0.82%   |
| WDC WD3200AAKX-001CA0 320GB                         | 2        | 0.82%   |
| Toshiba KXG5AZNV512G 512GB                          | 2        | 0.82%   |
| Toshiba HDWD120 2TB                                 | 2        | 0.82%   |
| Toshiba DT01ABA100V 1TB                             | 2        | 0.82%   |
| TO Exter nal USB 3.0 2TB                            | 2        | 0.82%   |
| Seagate ST250DM000-1BD141 250GB                     | 2        | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 0.82%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2        | 0.82%   |
| Seagate ST1000DM003-1ER162 1TB                      | 2        | 0.82%   |
| Samsung SSD 980 500GB                               | 2        | 0.82%   |
| Samsung SSD 980 1TB                                 | 2        | 0.82%   |
| Samsung SSD 860 EVO 500GB                           | 2        | 0.82%   |
| Samsung SSD 750 EVO 120GB                           | 2        | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2        | 0.82%   |
| Mushkin MKNSSDHL1TB-D8                              | 2        | 0.82%   |
| Lexar 128GB SSD                                     | 2        | 0.82%   |
| Kingston SKC600256G 256GB SSD                       | 2        | 0.82%   |
| Kingston SA400S37120G 120GB SSD                     | 2        | 0.82%   |
| JMicron Tech 250GB                                  | 2        | 0.82%   |
| Hitachi HDT725032VLA380 320GB                       | 2        | 0.82%   |
| HGST HTS545050A7E680 500GB                          | 2        | 0.82%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD                | 2        | 0.82%   |
| Crucial CT250MX500SSD1 250GB                        | 2        | 0.82%   |
| XSTAR SSD 128GB                                     | 1        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 44       | 57     | 42.31%  |
| Seagate  | 35       | 43     | 33.65%  |
| Toshiba  | 9        | 16     | 8.65%   |
| Hitachi  | 6        | 7      | 5.77%   |
| HGST     | 4        | 4      | 3.85%   |
| Unknown  | 3        | 3      | 2.88%   |
| Fujitsu  | 2        | 2      | 1.92%   |
| External | 1        | 1      | 0.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 16       | 22     | 19.28%  |
| WDC                 | 12       | 12     | 14.46%  |
| Kingston            | 12       | 15     | 14.46%  |
| Lexar               | 4        | 4      | 4.82%   |
| Intel               | 4        | 4      | 4.82%   |
| Crucial             | 4        | 5      | 4.82%   |
| SanDisk             | 3        | 3      | 3.61%   |
| Colorful            | 3        | 3      | 3.61%   |
| ZOTAC               | 2        | 2      | 2.41%   |
| Transcend           | 2        | 2      | 2.41%   |
| TO Exter            | 2        | 3      | 2.41%   |
| Netac               | 2        | 2      | 2.41%   |
| Gigabyte Technology | 2        | 2      | 2.41%   |
| China               | 2        | 2      | 2.41%   |
| XSTAR               | 1        | 1      | 1.2%    |
| VSP                 | 1        | 1      | 1.2%    |
| Vaseky              | 1        | 1      | 1.2%    |
| Toshiba             | 1        | 1      | 1.2%    |
| SK hynix            | 1        | 1      | 1.2%    |
| Patriot             | 1        | 1      | 1.2%    |
| OSCOO               | 1        | 1      | 1.2%    |
| OCZ                 | 1        | 1      | 1.2%    |
| Micron Technology   | 1        | 1      | 1.2%    |
| Maxtor              | 1        | 1      | 1.2%    |
| LITEONIT            | 1        | 1      | 1.2%    |
| KIOXIA-EXCERIA      | 1        | 1      | 1.2%    |
| EK                  | 1        | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 83       | 133    | 43.23%  |
| SSD     | 70       | 94     | 36.46%  |
| NVMe    | 32       | 44     | 16.67%  |
| Unknown | 7        | 7      | 3.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 107      | 220    | 71.81%  |
| NVMe | 32       | 44     | 21.48%  |
| SAS  | 10       | 14     | 6.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 95       | 150    | 63.76%  |
| 0.51-1.0   | 33       | 44     | 22.15%  |
| 1.01-2.0   | 12       | 17     | 8.05%   |
| 4.01-10.0  | 5        | 12     | 3.36%   |
| 3.01-4.0   | 3        | 3      | 2.01%   |
| 2.01-3.0   | 1        | 1      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 46       | 36.22%  |
| 251-500        | 20       | 15.75%  |
| 501-1000       | 18       | 14.17%  |
| 1001-2000      | 8        | 6.3%    |
| More than 3000 | 7        | 5.51%   |
| 51-100         | 7        | 5.51%   |
| 1-20           | 6        | 4.72%   |
| 21-50          | 5        | 3.94%   |
| 2001-3000      | 5        | 3.94%   |
| Unknown        | 5        | 3.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 45       | 35.71%  |
| 21-50          | 18       | 14.29%  |
| 51-100         | 17       | 13.49%  |
| 251-500        | 12       | 9.52%   |
| 101-250        | 12       | 9.52%   |
| 501-1000       | 9        | 7.14%   |
| Unknown        | 5        | 3.97%   |
| More than 3000 | 4        | 3.17%   |
| 2001-3000      | 2        | 1.59%   |
| 1001-2000      | 2        | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD3200AAKX-001CA0 320GB         | 2        | 2      | 9.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 1      | 4.76%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 1      | 4.76%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 1      | 4.76%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1        | 1      | 4.76%   |
| Transcend TS256GSSD230S 256GB       | 1        | 1      | 4.76%   |
| Toshiba MK3275GSX 320GB             | 1        | 1      | 4.76%   |
| Seagate ST9250410AS 250GB           | 1        | 1      | 4.76%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 4.76%   |
| Seagate ST250DM000-1BD141 250GB     | 1        | 1      | 4.76%   |
| Seagate ST1000DM003-1ER162 1TB      | 1        | 1      | 4.76%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 4.76%   |
| Intel SSDSC2CW120A3 120GB           | 1        | 1      | 4.76%   |
| Hitachi HUA722020ALA331 2TB         | 1        | 1      | 4.76%   |
| Hitachi HTS725016A9A364 160GB       | 1        | 1      | 4.76%   |
| Hitachi HDT725032VLA380 320GB       | 1        | 2      | 4.76%   |
| HGST HTS725050A7E630 500GB          | 1        | 1      | 4.76%   |
| HGST HTS545050A7E680 500GB          | 1        | 1      | 4.76%   |
| Fujitsu MHK2120AT 12GB              | 1        | 1      | 4.76%   |
| China MSATA 32GB SSD                | 1        | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 28.57%  |
| Seagate             | 4        | 4      | 19.05%  |
| Hitachi             | 3        | 4      | 14.29%  |
| HGST                | 2        | 2      | 9.52%   |
| Transcend           | 1        | 1      | 4.76%   |
| Toshiba             | 1        | 1      | 4.76%   |
| Samsung Electronics | 1        | 1      | 4.76%   |
| Intel               | 1        | 1      | 4.76%   |
| Fujitsu             | 1        | 1      | 4.76%   |
| China               | 1        | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 5      | 31.25%  |
| Seagate | 4        | 4      | 25%     |
| Hitachi | 3        | 4      | 18.75%  |
| HGST    | 2        | 2      | 12.5%   |
| Toshiba | 1        | 1      | 6.25%   |
| Fujitsu | 1        | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 17     | 78.95%  |
| SSD  | 4        | 5      | 21.05%  |

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
| Works    | 62       | 135    | 44.6%   |
| Detected | 59       | 120    | 42.45%  |
| Malfunc  | 17       | 22     | 12.23%  |
| Failed   | 1        | 1      | 0.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 96       | 57.83%  |
| AMD                          | 25       | 15.06%  |
| Samsung Electronics          | 13       | 7.83%   |
| SanDisk                      | 10       | 6.02%   |
| ASMedia Technology           | 4        | 2.41%   |
| Silicon Motion               | 3        | 1.81%   |
| Toshiba America Info Systems | 2        | 1.2%    |
| Micron/Crucial Technology    | 2        | 1.2%    |
| SK hynix                     | 1        | 0.6%    |
| Realtek Semiconductor        | 1        | 0.6%    |
| Phison Electronics           | 1        | 0.6%    |
| OCZ Technology Group         | 1        | 0.6%    |
| MAXIO Technology (Hangzhou)  | 1        | 0.6%    |
| Marvell Technology Group     | 1        | 0.6%    |
| LSI Logic / Symbios Logic    | 1        | 0.6%    |
| Lite-On Technology           | 1        | 0.6%    |
| Kingston Technology Company  | 1        | 0.6%    |
| JMicron Technology           | 1        | 0.6%    |
| ADATA Technology             | 1        | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 19       | 9.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 7.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 5.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 4.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 4.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 4.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 3.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 3.05%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5        | 2.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 2.54%   |
| Samsung NVMe SSD Controller 980                                                         | 5        | 2.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.54%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 2.03%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 2.03%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 1.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 1.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.52%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.52%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 1.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.52%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 2        | 1.02%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.02%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.02%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1        | 0.51%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.51%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                                   | 1        | 0.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.51%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.51%   |
| Phison E8 PCIe3 NVMe Controller                                                         | 1        | 0.51%   |
| OCZ Group RD400/400A SSD                                                                | 1        | 0.51%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 0.51%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                               | 1        | 0.51%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 96       | 60.76%  |
| NVMe | 32       | 20.25%  |
| IDE  | 25       | 15.82%  |
| RAID | 4        | 2.53%   |
| SAS  | 1        | 0.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 97       | 79.51%  |
| AMD    | 25       | 20.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 3.28%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 3.28%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 2.46%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 2.46%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 2.46%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 2.46%   |
| Intel Atom CPU D2550 @ 1.86GHz              | 3        | 2.46%   |
| AMD Ryzen 5 5500                            | 3        | 2.46%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 2.46%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 1.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.64%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.64%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 1.64%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.64%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.64%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.64%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.64%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.64%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 2        | 1.64%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.64%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 1.64%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.64%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.64%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 0.82%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1        | 0.82%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1        | 0.82%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz          | 1        | 0.82%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.82%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.82%   |
| Intel Xeon CPU E31235 @ 3.20GHz             | 1        | 0.82%   |
| Intel Xeon CPU E3-1265L v3 @ 2.50GHz        | 1        | 0.82%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1        | 0.82%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.82%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.82%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.82%   |
| Intel Pentium CPU G640T @ 2.40GHz           | 1        | 0.82%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.82%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.82%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 0.82%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 34       | 27.87%  |
| Intel Core i3           | 19       | 15.57%  |
| AMD Ryzen 5             | 13       | 10.66%  |
| Intel Core i7           | 11       | 9.02%   |
| Intel Xeon              | 9        | 7.38%   |
| Intel Core 2 Duo        | 7        | 5.74%   |
| Other                   | 3        | 2.46%   |
| Intel Pentium           | 3        | 2.46%   |
| Intel Celeron           | 3        | 2.46%   |
| Intel Atom              | 3        | 2.46%   |
| AMD Ryzen 9             | 3        | 2.46%   |
| AMD Ryzen 7             | 2        | 1.64%   |
| AMD A10                 | 2        | 1.64%   |
| Intel Pentium Gold      | 1        | 0.82%   |
| Intel Pentium Dual-Core | 1        | 0.82%   |
| Intel Pentium Dual      | 1        | 0.82%   |
| Intel Core i9           | 1        | 0.82%   |
| Intel Core 2 Quad       | 1        | 0.82%   |
| AMD Ryzen 7 PRO         | 1        | 0.82%   |
| AMD Ryzen 3             | 1        | 0.82%   |
| AMD Phenom II X4        | 1        | 0.82%   |
| AMD Athlon II X2        | 1        | 0.82%   |
| AMD A8                  | 1        | 0.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 50       | 40.65%  |
| 2      | 35       | 28.46%  |
| 6      | 24       | 19.51%  |
| 8      | 7        | 5.69%   |
| 16     | 4        | 3.25%   |
| 28     | 1        | 0.81%   |
| 24     | 1        | 0.81%   |
| 12     | 1        | 0.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 120      | 97.56%  |
| 2      | 3        | 2.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 66       | 54.1%   |
| 1      | 56       | 45.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 121      | 99.18%  |
| Unknown        | 1        | 0.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 21.31%  |
| 0x306c3    | 12       | 9.84%   |
| 0x306a9    | 9        | 7.38%   |
| 0x906ea    | 8        | 6.56%   |
| 0x1067a    | 7        | 5.74%   |
| 0x206a7    | 6        | 4.92%   |
| 0xa0653    | 4        | 3.28%   |
| 0x906eb    | 3        | 2.46%   |
| 0x906e9    | 3        | 2.46%   |
| 0x506e3    | 3        | 2.46%   |
| 0x206d7    | 3        | 2.46%   |
| 0x0a201016 | 3        | 2.46%   |
| 0x906ed    | 2        | 1.64%   |
| 0x90672    | 2        | 1.64%   |
| 0x30678    | 2        | 1.64%   |
| 0x20655    | 2        | 1.64%   |
| 0x0a50000d | 2        | 1.64%   |
| 0x0a50000c | 2        | 1.64%   |
| 0x0a20120a | 2        | 1.64%   |
| 0x08701021 | 2        | 1.64%   |
| 0x0810100b | 2        | 1.64%   |
| 0x06003106 | 2        | 1.64%   |
| 0x90675    | 1        | 0.82%   |
| 0x6fd      | 1        | 0.82%   |
| 0x406f1    | 1        | 0.82%   |
| 0x306f2    | 1        | 0.82%   |
| 0x30661    | 1        | 0.82%   |
| 0x106a5    | 1        | 0.82%   |
| 0x10676    | 1        | 0.82%   |
| 0x0a601203 | 1        | 0.82%   |
| 0x08701030 | 1        | 0.82%   |
| 0x08701013 | 1        | 0.82%   |
| 0x08108109 | 1        | 0.82%   |
| 0x0800820d | 1        | 0.82%   |
| 0x06001119 | 1        | 0.82%   |
| 0x010000db | 1        | 0.82%   |
| 0x010000c7 | 1        | 0.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 21       | 17.21%  |
| KabyLake         | 19       | 15.57%  |
| IvyBridge        | 13       | 10.66%  |
| Zen 3            | 9        | 7.38%   |
| SandyBridge      | 9        | 7.38%   |
| Penryn           | 9        | 7.38%   |
| Skylake          | 7        | 5.74%   |
| Zen 2            | 5        | 4.1%    |
| CometLake        | 4        | 3.28%   |
| Zen+             | 3        | 2.46%   |
| Westmere         | 3        | 2.46%   |
| Silvermont       | 3        | 2.46%   |
| Bonnell          | 3        | 2.46%   |
| Alderlake Hybrid | 3        | 2.46%   |
| Zen              | 2        | 1.64%   |
| Steamroller      | 2        | 1.64%   |
| K10              | 2        | 1.64%   |
| Piledriver       | 1        | 0.82%   |
| Nehalem          | 1        | 0.82%   |
| Core             | 1        | 0.82%   |
| Broadwell        | 1        | 0.82%   |
| Unknown          | 1        | 0.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 54       | 40%     |
| Intel             | 50       | 37.04%  |
| AMD               | 30       | 22.22%  |
| ASPEED Technology | 1        | 0.74%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 7.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 6.52%   |
| Nvidia GK208B [GeForce GT 730]                                              | 8        | 5.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 7        | 5.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 3.62%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 3.62%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 2.17%   |
| Intel HD Graphics 530                                                       | 3        | 2.17%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller             | 3        | 2.17%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 2.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.17%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 2.17%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 2        | 1.45%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.45%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.45%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 1.45%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.45%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.45%   |
| Intel HD Graphics 630                                                       | 2        | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 1.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.45%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.45%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.72%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.72%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.72%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.72%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.72%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.72%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.72%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB Rev. 2]                                  | 1        | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.72%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1        | 0.72%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.72%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.72%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 45       | 36.59%  |
| 1 x Intel       | 40       | 32.52%  |
| 1 x AMD         | 29       | 23.58%  |
| Intel + Nvidia  | 7        | 5.69%   |
| Nvidia + ASPEED | 1        | 0.81%   |
| AMD + Nvidia    | 1        | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 83       | 66.94%  |
| Proprietary | 39       | 31.45%  |
| Unknown     | 2        | 1.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 50       | 40.65%  |
| 1.01-2.0   | 17       | 13.82%  |
| 3.01-4.0   | 15       | 12.2%   |
| 7.01-8.0   | 11       | 8.94%   |
| 0.51-1.0   | 8        | 6.5%    |
| 5.01-6.0   | 7        | 5.69%   |
| 8.01-16.0  | 7        | 5.69%   |
| 0.01-0.5   | 7        | 5.69%   |
| 2.01-3.0   | 1        | 0.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 33       | 28.21%  |
| Samsung Electronics  | 20       | 17.09%  |
| Goldstar             | 11       | 9.4%    |
| AOC                  | 8        | 6.84%   |
| ViewSonic            | 6        | 5.13%   |
| Hewlett-Packard      | 5        | 4.27%   |
| Ancor Communications | 4        | 3.42%   |
| Panasonic            | 3        | 2.56%   |
| Acer                 | 3        | 2.56%   |
| Gigabyte Technology  | 2        | 1.71%   |
| Fujitsu              | 2        | 1.71%   |
| FPT                  | 2        | 1.71%   |
| BenQ                 | 2        | 1.71%   |
| ASUSTek Computer     | 2        | 1.71%   |
| Unknown              | 2        | 1.71%   |
| Unknown (ADA)        | 1        | 0.85%   |
| Sony                 | 1        | 0.85%   |
| Philips              | 1        | 0.85%   |
| NEC Computers        | 1        | 0.85%   |
| Mi                   | 1        | 0.85%   |
| LG Electronics       | 1        | 0.85%   |
| Lenovo Group Limited | 1        | 0.85%   |
| Lenovo               | 1        | 0.85%   |
| HPN                  | 1        | 0.85%   |
| HOP                  | 1        | 0.85%   |
| CGC                  | 1        | 0.85%   |
| AUS                  | 1        | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Panasonic TV MEIC33B 1366x768 521x293mm 23.5-inch                       | 3        | 2.48%   |
| AOC 2460X AOC2460 1920x1200 518x324mm 24.1-inch                         | 3        | 2.48%   |
| Samsung Electronics SME1720NR SAM0696 1280x1024 338x270mm 17.0-inch     | 2        | 1.65%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 2        | 1.65%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                    | 2        | 1.65%   |
| Fujitsu VL-17BSE FUJE711 1280x1024 338x270mm 17.0-inch                  | 2        | 1.65%   |
| FPT F22FAD FPTF22F 1920x1080 477x268mm 21.5-inch                        | 2        | 1.65%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                       | 2        | 1.65%   |
| Unknown                                                                 | 2        | 1.65%   |
| ViewSonic VX2480-2K VSC7B3B 2560x1440 527x296mm 23.8-inch               | 1        | 0.83%   |
| ViewSonic VG2239 Series VSCC42B 1920x1080 477x268mm 21.5-inch           | 1        | 0.83%   |
| ViewSonic VA2409-FHD VSC983D 1920x1080 521x293mm 23.5-inch              | 1        | 0.83%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 477x268mm 21.5-inch              | 1        | 0.83%   |
| ViewSonic VA2201-FHD VSC683B 1920x1080 480x260mm 21.5-inch              | 1        | 0.83%   |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                               | 1        | 0.83%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch           | 1        | 0.83%   |
| Sony TV SNY8E03 1920x1080                                               | 1        | 0.83%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch        | 1        | 0.83%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 1        | 0.83%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.83%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch       | 1        | 0.83%   |
| Samsung Electronics S20D300 SAM0B39 1600x900 432x240mm 19.5-inch        | 1        | 0.83%   |
| Samsung Electronics S20B370 SAM08B7 1600x900 443x249mm 20.0-inch        | 1        | 0.83%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch        | 1        | 0.83%   |
| Samsung Electronics S19C300 SAM0A12 1366x768 410x230mm 18.5-inch        | 1        | 0.83%   |
| Samsung Electronics S19C170 SAM0B02 1366x768 410x230mm 18.5-inch        | 1        | 0.83%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 1        | 0.83%   |
| Samsung Electronics LCD Monitor SME1720NR 1280x1024                     | 1        | 0.83%   |
| Samsung Electronics LCD Monitor SMB1930N                                | 1        | 0.83%   |
| Samsung Electronics LCD Monitor SAM7129 3840x2160 950x540mm 43.0-inch   | 1        | 0.83%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 950x540mm 43.0-inch   | 1        | 0.83%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 1872x1053mm 84.6-inch | 1        | 0.83%   |
| Samsung Electronics LCD Monitor SAM0658 1920x1080 886x498mm 40.0-inch   | 1        | 0.83%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 0.83%   |
| Philips 24PHT4003/98 PHT4003 1360x768 525x297mm 23.7-inch               | 1        | 0.83%   |
| NEC Computers LCD172VXM NEC67C5 1280x1024 338x270mm 17.0-inch           | 1        | 0.83%   |
| Mi Redmi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                  | 1        | 0.83%   |
| LG Electronics LCD Monitor MP59G                                        | 1        | 0.83%   |
| Lenovo LEN L193pC LEN114F 1280x1024 376x301mm 19.0-inch                 | 1        | 0.83%   |
| Lenovo Group Limited LCD Monitor LEN L1900pA 1280x1024                  | 1        | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 57       | 48.72%  |
| 3840x2160 (4K)    | 10       | 8.55%   |
| 2560x1440 (QHD)   | 10       | 8.55%   |
| 1280x1024 (SXGA)  | 10       | 8.55%   |
| 1366x768 (WXGA)   | 9        | 7.69%   |
| 1600x900 (HD+)    | 8        | 6.84%   |
| Unknown           | 3        | 2.56%   |
| 1920x1200 (WUXGA) | 2        | 1.71%   |
| 1440x900 (WXGA+)  | 2        | 1.71%   |
| 3840x1080         | 1        | 0.85%   |
| 3440x1440         | 1        | 0.85%   |
| 3286x1080         | 1        | 0.85%   |
| 2560x1080         | 1        | 0.85%   |
| 1360x768          | 1        | 0.85%   |
| 1280x800 (WXGA)   | 1        | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 19       | 16.38%  |
| 21      | 18       | 15.52%  |
| 24      | 16       | 13.79%  |
| Unknown | 15       | 12.93%  |
| 27      | 14       | 12.07%  |
| 17      | 7        | 6.03%   |
| 20      | 6        | 5.17%   |
| 18      | 6        | 5.17%   |
| 19      | 5        | 4.31%   |
| 84      | 3        | 2.59%   |
| 34      | 2        | 1.72%   |
| 25      | 2        | 1.72%   |
| 42      | 1        | 0.86%   |
| 40      | 1        | 0.86%   |
| 7       | 1        | 0.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 49       | 42.98%  |
| 401-500     | 32       | 28.07%  |
| Unknown     | 15       | 13.16%  |
| 301-350     | 6        | 5.26%   |
| 351-400     | 3        | 2.63%   |
| 1501-2000   | 3        | 2.63%   |
| 701-800     | 2        | 1.75%   |
| 801-900     | 1        | 0.88%   |
| 601-700     | 1        | 0.88%   |
| 101-200     | 1        | 0.88%   |
| 901-1000    | 1        | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 81       | 72.97%  |
| Unknown | 14       | 12.61%  |
| 5/4     | 8        | 7.21%   |
| 16/10   | 5        | 4.5%    |
| 21/9    | 2        | 1.8%    |
| 3/2     | 1        | 0.9%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 44       | 38.26%  |
| 151-200        | 16       | 13.91%  |
| Unknown        | 15       | 13.04%  |
| 301-350        | 14       | 12.17%  |
| 141-150        | 12       | 10.43%  |
| 251-300        | 5        | 4.35%   |
| More than 1000 | 3        | 2.61%   |
| 351-500        | 2        | 1.74%   |
| 501-1000       | 2        | 1.74%   |
| 1-40           | 1        | 0.87%   |
| 131-140        | 1        | 0.87%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 69       | 60%     |
| 101-120 | 23       | 20%     |
| Unknown | 15       | 13.04%  |
| 161-240 | 4        | 3.48%   |
| 121-160 | 4        | 3.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 106      | 86.89%  |
| 2     | 9        | 7.38%   |
| 0     | 7        | 5.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 79       | 45.14%  |
| Intel                 | 45       | 25.71%  |
| Ralink Technology     | 9        | 5.14%   |
| Qualcomm Atheros      | 9        | 5.14%   |
| Broadcom              | 9        | 5.14%   |
| TP-Link               | 7        | 4%      |
| ASIX Electronics      | 4        | 2.29%   |
| Ralink                | 3        | 1.71%   |
| MediaTek              | 2        | 1.14%   |
| D-Link                | 2        | 1.14%   |
| Samsung Electronics   | 1        | 0.57%   |
| Novatel Wireless      | 1        | 0.57%   |
| ICS Advent            | 1        | 0.57%   |
| Edimax Technology     | 1        | 0.57%   |
| Aquantia              | 1        | 0.57%   |
| Unknown               | 1        | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65       | 33.33%  |
| Intel Wi-Fi 6 AX200                                               | 6        | 3.08%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 3.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 2.56%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 2.56%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 2.05%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.05%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 1.54%   |
| Intel I211 Gigabit Network Connection                             | 3        | 1.54%   |
| Intel I210 Gigabit Network Connection                             | 3        | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.54%   |
| ASIX AX88772A Fast Ethernet                                       | 3        | 1.54%   |
| TP-Link 802.11ac NIC                                              | 2        | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.03%   |
| Realtek 802.11ac NIC                                              | 2        | 1.03%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 1.03%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.03%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.03%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.03%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.03%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2        | 1.03%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2        | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2        | 1.03%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1        | 0.51%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.51%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.51%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 13       | 22.81%  |
| Realtek Semiconductor | 12       | 21.05%  |
| Ralink Technology     | 9        | 15.79%  |
| TP-Link               | 7        | 12.28%  |
| Broadcom              | 5        | 8.77%   |
| Qualcomm Atheros      | 4        | 7.02%   |
| Ralink                | 3        | 5.26%   |
| D-Link                | 2        | 3.51%   |
| MediaTek              | 1        | 1.75%   |
| Edimax Technology     | 1        | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 6        | 10.53%  |
| Ralink MT7601U Wireless Adapter                                | 4        | 7.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3        | 5.26%   |
| TP-Link 802.11ac NIC                                           | 2        | 3.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2        | 3.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 3.51%   |
| Realtek 802.11ac NIC                                           | 2        | 3.51%   |
| Ralink RT5370 Wireless Adapter                                 | 2        | 3.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 3.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2        | 3.51%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2        | 3.51%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2        | 3.51%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                          | 1        | 1.75%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1        | 1.75%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 1.75%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 1.75%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 1.75%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 1.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 1.75%   |
| Ralink RT2070 Wireless Adapter                                 | 1        | 1.75%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1        | 1.75%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1        | 1.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1        | 1.75%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 1        | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 1.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 1.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1        | 1.75%   |
| Intel Wireless 7265                                            | 1        | 1.75%   |
| Intel Wireless 7260                                            | 1        | 1.75%   |
| Intel Wireless 3165                                            | 1        | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 1.75%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 1.75%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 1.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1        | 1.75%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter             | 1        | 1.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1        | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 76       | 57.58%  |
| Intel                 | 39       | 29.55%  |
| Qualcomm Atheros      | 5        | 3.79%   |
| Broadcom              | 4        | 3.03%   |
| ASIX Electronics      | 4        | 3.03%   |
| Samsung Electronics   | 1        | 0.76%   |
| MediaTek              | 1        | 0.76%   |
| ICS Advent            | 1        | 0.76%   |
| Aquantia              | 1        | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65       | 47.79%  |
| Intel Ethernet Connection (7) I219-V                              | 6        | 4.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 3.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 3.68%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 3.68%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 3        | 2.21%   |
| Intel I210 Gigabit Network Connection                             | 3        | 2.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 2.21%   |
| ASIX AX88772A Fast Ethernet                                       | 3        | 2.21%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 1.47%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.47%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.47%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.47%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.47%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.47%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2        | 1.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.74%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.74%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.74%   |
| MediaTek Infinix HOT 11S NFC                                      | 1        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.74%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.74%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.74%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 0.74%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.74%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.74%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 0.74%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1        | 0.74%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1        | 0.74%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.74%   |
| Aquantia Antigua Engineering Sample                               | 1        | 0.74%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 121      | 68.36%  |
| WiFi     | 54       | 30.51%  |
| Modem    | 1        | 0.56%   |
| Unknown  | 1        | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 86       | 68.25%  |
| WiFi     | 39       | 30.95%  |
| Modem    | 1        | 0.79%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 81       | 65.85%  |
| 2     | 34       | 27.64%  |
| 3     | 7        | 5.69%   |
| 0     | 1        | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 95       | 77.24%  |
| Yes  | 28       | 22.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 15       | 33.33%  |
| Intel                           | 13       | 28.89%  |
| Realtek Semiconductor           | 7        | 15.56%  |
| Qualcomm Atheros Communications | 2        | 4.44%   |
| Broadcom                        | 2        | 4.44%   |
| TP-Link                         | 1        | 2.22%   |
| Ralink                          | 1        | 2.22%   |
| IMC Networks                    | 1        | 2.22%   |
| Foxconn / Hon Hai               | 1        | 2.22%   |
| Conwise Technology              | 1        | 2.22%   |
| Apple                           | 1        | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15       | 33.33%  |
| Realtek Bluetooth Radio                             | 7        | 15.56%  |
| Intel AX200 Bluetooth                               | 6        | 13.33%  |
| Intel Bluetooth wireless interface                  | 3        | 6.67%   |
| Intel Bluetooth Device                              | 2        | 4.44%   |
| Intel AX210 Bluetooth                               | 2        | 4.44%   |
| TP-Link UB5A Adapter                                | 1        | 2.22%   |
| Ralink RT3290 Bluetooth                             | 1        | 2.22%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 2.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 2.22%   |
| IMC Networks Bluetooth Radio                        | 1        | 2.22%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 2.22%   |
| Conwise CW6622                                      | 1        | 2.22%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1        | 2.22%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1        | 2.22%   |
| Apple Bluetooth Host Controller                     | 1        | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 96       | 45.71%  |
| Nvidia                    | 53       | 25.24%  |
| AMD                       | 35       | 16.67%  |
| Generalplus Technology    | 5        | 2.38%   |
| C-Media Electronics       | 4        | 1.9%    |
| Audient                   | 3        | 1.43%   |
| Creative Labs             | 2        | 0.95%   |
| Shenzhen Rapoo Technology | 1        | 0.48%   |
| Nordic Semiconductor ASA  | 1        | 0.48%   |
| Logitech                  | 1        | 0.48%   |
| JMTek                     | 1        | 0.48%   |
| GYROCOM C&C               | 1        | 0.48%   |
| FIFINE Microphones        | 1        | 0.48%   |
| Elgato Systems            | 1        | 0.48%   |
| Creative Technology       | 1        | 0.48%   |
| Conexant Systems          | 1        | 0.48%   |
| ASUSTek Computer          | 1        | 0.48%   |
| Apple                     | 1        | 0.48%   |
| AGPTek                    | 1        | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17       | 7.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 5.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 4.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10       | 4.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10       | 4.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 4.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 3.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 3.73%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 3.32%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 3.32%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 2.9%    |
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 2.49%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 2.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 2.07%   |
| Generalplus Technology USB Audio Device                                    | 5        | 2.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 2.07%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 1.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1.66%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 1.24%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.24%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.24%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 1.24%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1.24%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 1.24%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.24%   |
| Audient EVO4                                                               | 3        | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.24%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.24%   |
| Nvidia TU102 High Definition Audio Controller                              | 2        | 0.83%   |
| Nvidia High Definition Audio Controller                                    | 2        | 0.83%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.83%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.83%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.83%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 0.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.83%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Kingston              | 23       | 27.71%  |
| Corsair               | 15       | 18.07%  |
| G.Skill               | 10       | 12.05%  |
| Unknown               | 6        | 7.23%   |
| SK hynix              | 6        | 7.23%   |
| Samsung Electronics   | 5        | 6.02%   |
| Kingmax               | 4        | 4.82%   |
| Crucial               | 3        | 3.61%   |
| Ramaxel Technology    | 2        | 2.41%   |
| Micron Technology     | 2        | 2.41%   |
| A-DATA Technology     | 2        | 2.41%   |
| Team                  | 1        | 1.2%    |
| Patriot               | 1        | 1.2%    |
| Kingmax Semiconductor | 1        | 1.2%    |
| ASint Technology      | 1        | 1.2%    |
| Apacer                | 1        | 1.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s      | 4        | 4.44%   |
| Unknown RAM Module 1GB DIMM 800MT/s                       | 2        | 2.22%   |
| Kingston RAM SNY1600S11-4G-ED 4GB SODIMM DDR3 1066MT/s    | 2        | 2.22%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s   | 2        | 2.22%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s     | 2        | 2.22%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s    | 2        | 2.22%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 1        | 1.11%   |
| Unknown RAM Module 2048MB DIMM DDR2 200MT/s               | 1        | 1.11%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                | 1        | 1.11%   |
| Unknown RAM BAPC08G3000D4T8 8192MB DIMM DDR4 2133MT/s     | 1        | 1.11%   |
| Team RAM TEAMGROUP-UD3-160 4096MB DIMM DDR3 1333MT/s      | 1        | 1.11%   |
| SK hynix RAM SNOAMOO Ltd:016M00 4096MB DIMM DDR3 1600MT/s | 1        | 1.11%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s       | 1        | 1.11%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s      | 1        | 1.11%   |
| SK hynix RAM HMT425S6AFR6A-PB 4GB DIMM DDR3 1600MT/s      | 1        | 1.11%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1        | 1.11%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 1.11%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1        | 1.11%   |
| Samsung RAM M393B2K70CM0-YF8 16GB DIMM DDR3 1067MT/s      | 1        | 1.11%   |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1866MT/s          | 1        | 1.11%   |
| Samsung RAM M393A2K40BB1-CRC 16GB DIMM DDR4 2400MT/s      | 1        | 1.11%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s       | 1        | 1.11%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB DIMM DDR3 1333MT/s     | 1        | 1.11%   |
| Ramaxel RAM RMR5040MM58F9F1600 4096MB DIMM DDR3 1600MT/s  | 1        | 1.11%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s            | 1        | 1.11%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 1.11%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s      | 1        | 1.11%   |
| Kingston RAM Module 8GB DIMM DDR4 2667MT/s                | 1        | 1.11%   |
| Kingston RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 1.11%   |
| Kingston RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 1.11%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 1.11%   |
| Kingston RAM KVR16LS11/8 8GB SODIMM DDR3 1600MT/s         | 1        | 1.11%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 1.11%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 1        | 1.11%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s      | 1        | 1.11%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s       | 1        | 1.11%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s     | 1        | 1.11%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s     | 1        | 1.11%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 1.11%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 1.11%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 39       | 53.42%  |
| DDR3    | 28       | 38.36%  |
| DDR2    | 2        | 2.74%   |
| Unknown | 2        | 2.74%   |
| DDR5    | 1        | 1.37%   |
| DDR     | 1        | 1.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 66       | 90.41%  |
| SODIMM | 7        | 9.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 33       | 42.31%  |
| 4096  | 21       | 26.92%  |
| 16384 | 17       | 21.79%  |
| 1024  | 4        | 5.13%   |
| 2048  | 2        | 2.56%   |
| 32768 | 1        | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 18       | 20.93%  |
| 3200  | 11       | 12.79%  |
| 1333  | 8        | 9.3%    |
| 3000  | 7        | 8.14%   |
| 2400  | 7        | 8.14%   |
| 3600  | 5        | 5.81%   |
| 2667  | 4        | 4.65%   |
| 1066  | 3        | 3.49%   |
| 800   | 3        | 3.49%   |
| 2800  | 2        | 2.33%   |
| 2666  | 2        | 2.33%   |
| 1866  | 2        | 2.33%   |
| 1067  | 2        | 2.33%   |
| 5200  | 1        | 1.16%   |
| 3666  | 1        | 1.16%   |
| 3466  | 1        | 1.16%   |
| 3400  | 1        | 1.16%   |
| 3334  | 1        | 1.16%   |
| 3007  | 1        | 1.16%   |
| 2448  | 1        | 1.16%   |
| 2133  | 1        | 1.16%   |
| 1867  | 1        | 1.16%   |
| 1648  | 1        | 1.16%   |
| 200   | 1        | 1.16%   |
| 133   | 1        | 1.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Ricoh  | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Ricoh Printing Support | 1        | 100%    |

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
| Logitech                        | 5        | 33.33%  |
| Sonix Technology                | 1        | 6.67%   |
| Samsung Electronics             | 1        | 6.67%   |
| Realtek Semiconductor           | 1        | 6.67%   |
| Microdia                        | 1        | 6.67%   |
| KYE Systems (Mouse Systems)     | 1        | 6.67%   |
| Intel                           | 1        | 6.67%   |
| IDS Imaging Development Systems | 1        | 6.67%   |
| Aveo Technology                 | 1        | 6.67%   |
| Apple                           | 1        | 6.67%   |
| Alpha Imaging Technology        | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 3        | 20%     |
| Sonix ZZ3                                      | 1        | 6.67%   |
| Samsung Galaxy series, misc. (MTP mode)        | 1        | 6.67%   |
| Realtek Dell_Monitor_IR_Webcam                 | 1        | 6.67%   |
| Microdia Rapoo Camera                          | 1        | 6.67%   |
| Logitech Webcam C310                           | 1        | 6.67%   |
| Logitech Webcam C210                           | 1        | 6.67%   |
| KYE Systems (Mouse Systems) Genius Webcam      | 1        | 6.67%   |
| Intel RealSense Depth Camera 435               | 1        | 6.67%   |
| IDS Imaging Development Systems USB 3.0 Camera | 1        | 6.67%   |
| Aveo USB2.0 Camera                             | 1        | 6.67%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                | 1        | 6.67%   |
| Alpha Imaging DS-2CS54U0B-SD                   | 1        | 6.67%   |

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
| 0     | 107      | 87.7%   |
| 1     | 14       | 11.48%  |
| 2     | 1        | 0.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 43.75%  |
| Unassigned class         | 3        | 18.75%  |
| Net/wireless             | 3        | 18.75%  |
| Communication controller | 1        | 6.25%   |
| Camera                   | 1        | 6.25%   |
| Bluetooth                | 1        | 6.25%   |

