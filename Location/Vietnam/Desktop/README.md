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

Total: 139

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 24       | 23.08%  |
| Ubuntu 18.04                 | 16       | 15.38%  |
| Ubuntu 22.04                 | 5        | 4.81%   |
| Fedora 37                    | 5        | 4.81%   |
| Arch                         | 5        | 4.81%   |
| Manjaro                      | 3        | 2.88%   |
| ArcoLinux Rolling            | 3        | 2.88%   |
| Arch Rolling                 | 3        | 2.88%   |
| Zorin 16                     | 2        | 1.92%   |
| Ubuntu Unity 16.04           | 2        | 1.92%   |
| Ubuntu 19.04                 | 2        | 1.92%   |
| Pop!_OS 20.10                | 2        | 1.92%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 1.92%   |
| Manjaro 20.2                 | 2        | 1.92%   |
| Linux Mint 20.3              | 2        | 1.92%   |
| Debian 11                    | 2        | 1.92%   |
| Debian 10                    | 2        | 1.92%   |
| Zorin 15                     | 1        | 0.96%   |
| Xubuntu 20.04                | 1        | 0.96%   |
| Ubuntu 21.04                 | 1        | 0.96%   |
| Ubuntu 16.04                 | 1        | 0.96%   |
| Parrot 4.11                  | 1        | 0.96%   |
| OpenMandriva 4.50            | 1        | 0.96%   |
| OpenMandriva 4.3             | 1        | 0.96%   |
| OpenMandriva 4.2             | 1        | 0.96%   |
| Manjaro 21.0.1               | 1        | 0.96%   |
| Manjaro 20.0.3               | 1        | 0.96%   |
| Linux Mint 21.1              | 1        | 0.96%   |
| Linux Mint 20                | 1        | 0.96%   |
| Kubuntu 22.04                | 1        | 0.96%   |
| Kubuntu 20.04                | 1        | 0.96%   |
| KDE neon 22.04               | 1        | 0.96%   |
| KDE neon 20.04               | 1        | 0.96%   |
| Gentoo 2.9                   | 1        | 0.96%   |
| Fedora 36                    | 1        | 0.96%   |
| EndeavourOS Rolling          | 1        | 0.96%   |
| Elementary 6                 | 1        | 0.96%   |
| Clear Linux 34500            | 1        | 0.96%   |
| Clear Linux 32260            | 1        | 0.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 47       | 46.08%  |
| Arch         | 8        | 7.84%   |
| Manjaro      | 7        | 6.86%   |
| Fedora       | 6        | 5.88%   |
| Linux Mint   | 4        | 3.92%   |
| Debian       | 4        | 3.92%   |
| Zorin        | 3        | 2.94%   |
| OpenMandriva | 3        | 2.94%   |
| ArcoLinux    | 3        | 2.94%   |
| Ubuntu Unity | 2        | 1.96%   |
| Pop!_OS      | 2        | 1.96%   |
| openSUSE     | 2        | 1.96%   |
| Kubuntu      | 2        | 1.96%   |
| KDE neon     | 2        | 1.96%   |
| Clear Linux  | 2        | 1.96%   |
| Xubuntu      | 1        | 0.98%   |
| Parrot       | 1        | 0.98%   |
| Gentoo       | 1        | 0.98%   |
| EndeavourOS  | 1        | 0.98%   |
| Elementary   | 1        | 0.98%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.4.0-58-generic       | 4        | 3.6%    |
| 5.4.0-37-generic       | 3        | 2.7%    |
| 5.4.0-26-generic       | 3        | 2.7%    |
| 5.15.0-52-generic      | 3        | 2.7%    |
| 5.11.0-38-generic      | 3        | 2.7%    |
| 5.0.0-23-generic       | 3        | 2.7%    |
| 6.0.12-300.fc37.x86_64 | 2        | 1.8%    |
| 5.9.11-3-MANJARO       | 2        | 1.8%    |
| 5.8.0-7642-generic     | 2        | 1.8%    |
| 5.4.0-48-generic       | 2        | 1.8%    |
| 5.4.0-47-generic       | 2        | 1.8%    |
| 5.4.0-42-generic       | 2        | 1.8%    |
| 5.11.0-37-generic      | 2        | 1.8%    |
| 4.18.0-25-generic      | 2        | 1.8%    |
| 6.1.13-200.fc37.x86_64 | 1        | 0.9%    |
| 6.1.12-gentoonovirt    | 1        | 0.9%    |
| 6.1.11-200.fc37.x86_64 | 1        | 0.9%    |
| 6.1.11-1-MANJARO       | 1        | 0.9%    |
| 6.1.10-200.fc37.x86_64 | 1        | 0.9%    |
| 6.0.2-x64v1-xanmod1-1  | 1        | 0.9%    |
| 6.0.0-rc5              | 1        | 0.9%    |
| 5.9.12-arch1-1         | 1        | 0.9%    |
| 5.9.0-0.bpo.5-amd64    | 1        | 0.9%    |
| 5.8.0-59-generic       | 1        | 0.9%    |
| 5.8.0-55-generic       | 1        | 0.9%    |
| 5.8.0-53-generic       | 1        | 0.9%    |
| 5.8.0-50-generic       | 1        | 0.9%    |
| 5.8.0-45-generic       | 1        | 0.9%    |
| 5.8.0-43-generic       | 1        | 0.9%    |
| 5.6.15-1-MANJARO       | 1        | 0.9%    |
| 5.6.0-1-default        | 1        | 0.9%    |
| 5.4.78-2-pve           | 1        | 0.9%    |
| 5.4.18-902.native      | 1        | 0.9%    |
| 5.4.0-99-generic       | 1        | 0.9%    |
| 5.4.0-90-generic       | 1        | 0.9%    |
| 5.4.0-72-generic       | 1        | 0.9%    |
| 5.4.0-65-generic       | 1        | 0.9%    |
| 5.4.0-52-generic       | 1        | 0.9%    |
| 5.4.0-39-generic       | 1        | 0.9%    |
| 5.4.0-33-generic       | 1        | 0.9%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 23       | 21.5%   |
| 5.15.0  | 10       | 9.35%   |
| 5.11.0  | 9        | 8.41%   |
| 5.8.0   | 8        | 7.48%   |
| 5.0.0   | 6        | 5.61%   |
| 4.15.0  | 6        | 5.61%   |
| 6.1.11  | 2        | 1.87%   |
| 6.0.12  | 2        | 1.87%   |
| 5.9.11  | 2        | 1.87%   |
| 5.15.60 | 2        | 1.87%   |
| 5.12.8  | 2        | 1.87%   |
| 4.18.0  | 2        | 1.87%   |
| 6.1.13  | 1        | 0.93%   |
| 6.1.12  | 1        | 0.93%   |
| 6.1.10  | 1        | 0.93%   |
| 6.0.2   | 1        | 0.93%   |
| 6.0.0   | 1        | 0.93%   |
| 5.9.12  | 1        | 0.93%   |
| 5.9.0   | 1        | 0.93%   |
| 5.6.15  | 1        | 0.93%   |
| 5.6.0   | 1        | 0.93%   |
| 5.4.78  | 1        | 0.93%   |
| 5.4.18  | 1        | 0.93%   |
| 5.19.7  | 1        | 0.93%   |
| 5.19.4  | 1        | 0.93%   |
| 5.19.3  | 1        | 0.93%   |
| 5.19.17 | 1        | 0.93%   |
| 5.19.12 | 1        | 0.93%   |
| 5.18.9  | 1        | 0.93%   |
| 5.17.9  | 1        | 0.93%   |
| 5.17.1  | 1        | 0.93%   |
| 5.16.7  | 1        | 0.93%   |
| 5.15.53 | 1        | 0.93%   |
| 5.14.0  | 1        | 0.93%   |
| 5.12.15 | 1        | 0.93%   |
| 5.12.1  | 1        | 0.93%   |
| 5.11.16 | 1        | 0.93%   |
| 5.10.42 | 1        | 0.93%   |
| 5.10.26 | 1        | 0.93%   |
| 5.10.19 | 1        | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 25       | 23.58%  |
| 5.15    | 12       | 11.32%  |
| 5.11    | 10       | 9.43%   |
| 5.8     | 8        | 7.55%   |
| 4.15    | 7        | 6.6%    |
| 5.0     | 6        | 5.66%   |
| 6.1     | 5        | 4.72%   |
| 5.19    | 5        | 4.72%   |
| 5.10    | 5        | 4.72%   |
| 6.0     | 4        | 3.77%   |
| 5.9     | 4        | 3.77%   |
| 5.12    | 4        | 3.77%   |
| 5.6     | 2        | 1.89%   |
| 5.17    | 2        | 1.89%   |
| 4.18    | 2        | 1.89%   |
| 5.18    | 1        | 0.94%   |
| 5.16    | 1        | 0.94%   |
| 5.14    | 1        | 0.94%   |
| 4.19    | 1        | 0.94%   |
| 4.10    | 1        | 0.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 100      | 99.01%  |
| i686   | 1        | 0.99%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 55       | 53.4%   |
| Unknown    | 18       | 17.48%  |
| KDE5       | 13       | 12.62%  |
| XFCE       | 3        | 2.91%   |
| MATE       | 3        | 2.91%   |
| X-Cinnamon | 2        | 1.94%   |
| Unity      | 2        | 1.94%   |
| KDE        | 2        | 1.94%   |
| Pantheon   | 1        | 0.97%   |
| i3         | 1        | 0.97%   |
| Cinnamon   | 1        | 0.97%   |
| bspwm      | 1        | 0.97%   |
| awesome    | 1        | 0.97%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 74       | 71.15%  |
| Wayland | 17       | 16.35%  |
| Unknown | 9        | 8.65%   |
| Tty     | 4        | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 49.02%  |
| GDM     | 20       | 19.61%  |
| SDDM    | 11       | 10.78%  |
| LightDM | 8        | 7.84%   |
| GDM3    | 8        | 7.84%   |
| TDM     | 4        | 3.92%   |
| XDM     | 1        | 0.98%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 80       | 78.43%  |
| Unknown | 12       | 11.76%  |
| vi_VN   | 7        | 6.86%   |
| ru_RU   | 1        | 0.98%   |
| en_GB   | 1        | 0.98%   |
| C       | 1        | 0.98%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 58       | 56.86%  |
| BIOS | 44       | 43.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 83       | 80.58%  |
| Btrfs   | 9        | 8.74%   |
| Overlay | 6        | 5.83%   |
| Zfs     | 2        | 1.94%   |
| Unknown | 2        | 1.94%   |
| F2fs    | 1        | 0.97%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 51       | 50%     |
| GPT     | 40       | 39.22%  |
| MBR     | 11       | 10.78%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 82.35%  |
| Yes       | 18       | 17.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 51.46%  |
| Yes       | 50       | 48.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 35       | 34.65%  |
| ASUSTek Computer    | 26       | 25.74%  |
| MSI                 | 11       | 10.89%  |
| Hewlett-Packard     | 8        | 7.92%   |
| Dell                | 6        | 5.94%   |
| ASRock              | 3        | 2.97%   |
| Wistron             | 2        | 1.98%   |
| Lenovo              | 2        | 1.98%   |
| Foxconn             | 2        | 1.98%   |
| Shuttle             | 1        | 0.99%   |
| Koloe               | 1        | 0.99%   |
| Intel               | 1        | 0.99%   |
| Huanan              | 1        | 0.99%   |
| Colorful Technology | 1        | 0.99%   |
| Unknown             | 1        | 0.99%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Gigabyte H61M-DS2                    | 5        | 4.95%   |
| ASUS All Series                      | 3        | 2.97%   |
| MSI MS-7C89                          | 2        | 1.98%   |
| MSI MS-7B89                          | 2        | 1.98%   |
| MSI MS-7823                          | 2        | 1.98%   |
| Gigabyte G41M-ES2L                   | 2        | 1.98%   |
| Gigabyte B450M GAMING                | 2        | 1.98%   |
| Gigabyte B360M-D3H                   | 2        | 1.98%   |
| ASUS P8H61-MX R2.0                   | 2        | 1.98%   |
| ASUS B75M-A                          | 2        | 1.98%   |
| Wistron FMVDD2A0H0                   | 1        | 0.99%   |
| Wistron FMVCEG40Y                    | 1        | 0.99%   |
| Shuttle DS81D                        | 1        | 0.99%   |
| MSI MS-7C67                          | 1        | 0.99%   |
| MSI MS-7C31                          | 1        | 0.99%   |
| MSI MS-7B98                          | 1        | 0.99%   |
| MSI MS-7A38                          | 1        | 0.99%   |
| MSI MS-7388                          | 1        | 0.99%   |
| Lenovo ThinkCentre M93p 10A8CTO1WW   | 1        | 0.99%   |
| Lenovo ThinkCentre M55e 9389AN1      | 1        | 0.99%   |
| Koloe Thurley                        | 1        | 0.99%   |
| Intel DP55WG AAE57269-407            | 1        | 0.99%   |
| Huanan X79 249PC V2.1                | 1        | 0.99%   |
| HP Z620 Workstation                  | 1        | 0.99%   |
| HP Z440 Workstation                  | 1        | 0.99%   |
| HP Z2 Tower G4 Workstation           | 1        | 0.99%   |
| HP ProDesk 600 G1 SFF                | 1        | 0.99%   |
| HP p2-1221l                          | 1        | 0.99%   |
| HP 510-p042l                         | 1        | 0.99%   |
| HP 500-504x                          | 1        | 0.99%   |
| HP 251-152l                          | 1        | 0.99%   |
| Gigabyte Z97X-UD3H                   | 1        | 0.99%   |
| Gigabyte Z690 AORUS ELITE AX DDR4 V2 | 1        | 0.99%   |
| Gigabyte Z390 UD                     | 1        | 0.99%   |
| Gigabyte Z170-D3H                    | 1        | 0.99%   |
| Gigabyte X570 UD                     | 1        | 0.99%   |
| Gigabyte P110-D3                     | 1        | 0.99%   |
| Gigabyte H81M-DS2                    | 1        | 0.99%   |
| Gigabyte H170M-D3H-CF                | 1        | 0.99%   |
| Gigabyte H170-Gaming 3               | 1        | 0.99%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 7        | 6.93%   |
| Gigabyte H61M-DS2  | 5        | 4.95%   |
| Dell OptiPlex      | 3        | 2.97%   |
| ASUS ROG           | 3        | 2.97%   |
| ASUS P8H61-MX      | 3        | 2.97%   |
| ASUS All           | 3        | 2.97%   |
| MSI MS-7C89        | 2        | 1.98%   |
| MSI MS-7B89        | 2        | 1.98%   |
| MSI MS-7823        | 2        | 1.98%   |
| Lenovo ThinkCentre | 2        | 1.98%   |
| Gigabyte G41M-ES2L | 2        | 1.98%   |
| Gigabyte B450M     | 2        | 1.98%   |
| Gigabyte B360M-D3H | 2        | 1.98%   |
| ASUS B75M-A        | 2        | 1.98%   |
| Wistron FMVDD2A0H0 | 1        | 0.99%   |
| Wistron FMVCEG40Y  | 1        | 0.99%   |
| Shuttle DS81D      | 1        | 0.99%   |
| MSI MS-7C67        | 1        | 0.99%   |
| MSI MS-7C31        | 1        | 0.99%   |
| MSI MS-7B98        | 1        | 0.99%   |
| MSI MS-7A38        | 1        | 0.99%   |
| MSI MS-7388        | 1        | 0.99%   |
| Koloe Thurley      | 1        | 0.99%   |
| Intel DP55WG       | 1        | 0.99%   |
| Huanan X79         | 1        | 0.99%   |
| HP Z620            | 1        | 0.99%   |
| HP Z440            | 1        | 0.99%   |
| HP Z2              | 1        | 0.99%   |
| HP ProDesk         | 1        | 0.99%   |
| HP p2-1221l        | 1        | 0.99%   |
| HP 510-p042l       | 1        | 0.99%   |
| HP 500-504x        | 1        | 0.99%   |
| HP 251-152l        | 1        | 0.99%   |
| Gigabyte Z97X-UD3H | 1        | 0.99%   |
| Gigabyte Z690      | 1        | 0.99%   |
| Gigabyte Z390      | 1        | 0.99%   |
| Gigabyte Z170-D3H  | 1        | 0.99%   |
| Gigabyte X570      | 1        | 0.99%   |
| Gigabyte P110-D3   | 1        | 0.99%   |
| Gigabyte H81M-DS2  | 1        | 0.99%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 17       | 16.83%  |
| 2014 | 11       | 10.89%  |
| 2012 | 11       | 10.89%  |
| 2019 | 9        | 8.91%   |
| 2013 | 9        | 8.91%   |
| 2020 | 7        | 6.93%   |
| 2010 | 7        | 6.93%   |
| 2017 | 5        | 4.95%   |
| 2015 | 5        | 4.95%   |
| 2009 | 5        | 4.95%   |
| 2016 | 4        | 3.96%   |
| 2021 | 3        | 2.97%   |
| 2011 | 3        | 2.97%   |
| 2022 | 2        | 1.98%   |
| 2008 | 1        | 0.99%   |
| 2007 | 1        | 0.99%   |
| 2006 | 1        | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 101      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 97       | 96.04%  |
| Enabled  | 4        | 3.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 101      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 25       | 24.51%  |
| 8.01-16.0   | 23       | 22.55%  |
| 3.01-4.0    | 15       | 14.71%  |
| 32.01-64.0  | 14       | 13.73%  |
| 4.01-8.0    | 12       | 11.76%  |
| 1.01-2.0    | 7        | 6.86%   |
| 24.01-32.0  | 4        | 3.92%   |
| 64.01-256.0 | 2        | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 32       | 31.07%  |
| 1.01-2.0   | 30       | 29.13%  |
| 3.01-4.0   | 15       | 14.56%  |
| 4.01-8.0   | 14       | 13.59%  |
| 8.01-16.0  | 9        | 8.74%   |
| 16.01-24.0 | 1        | 0.97%   |
| 0.51-1.0   | 1        | 0.97%   |
| 0.01-0.5   | 1        | 0.97%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 47       | 45.19%  |
| 1      | 31       | 29.81%  |
| 3      | 15       | 14.42%  |
| 4      | 7        | 6.73%   |
| 5      | 2        | 1.92%   |
| 9      | 1        | 0.96%   |
| 0      | 1        | 0.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 78.22%  |
| Yes       | 22       | 21.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 100      | 99.01%  |
| No        | 1        | 0.99%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 54.9%   |
| Yes       | 46       | 45.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 65.69%  |
| Yes       | 35       | 34.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Vietnam | 101      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Ho Chi Minh City | 59       | 57.84%  |
| Hanoi            | 23       | 22.55%  |
| Bac Giang        | 3        | 2.94%   |
| Nga Bay          | 2        | 1.96%   |
| Da Nang          | 2        | 1.96%   |
| Vũng Tàu       | 1        | 0.98%   |
| Vi Thanh         | 1        | 0.98%   |
| Thai Nguyen      | 1        | 0.98%   |
| Tay Ninh         | 1        | 0.98%   |
| Quảng Ngai     | 1        | 0.98%   |
| Nha Trang        | 1        | 0.98%   |
| Nam Định      | 1        | 0.98%   |
| Haiphong         | 1        | 0.98%   |
| Hai Duong        | 1        | 0.98%   |
| Di An            | 1        | 0.98%   |
| Can Tho          | 1        | 0.98%   |
| Bien Hoa         | 1        | 0.98%   |
| Bến Tre        | 1        | 0.98%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 49       | 63     | 26.78%  |
| Seagate                     | 32       | 40     | 17.49%  |
| Samsung Electronics         | 20       | 28     | 10.93%  |
| Kingston                    | 12       | 15     | 6.56%   |
| Toshiba                     | 8        | 16     | 4.37%   |
| Hitachi                     | 5        | 6      | 2.73%   |
| SanDisk                     | 4        | 4      | 2.19%   |
| Intel                       | 4        | 4      | 2.19%   |
| Crucial                     | 4        | 7      | 2.19%   |
| Unknown                     | 3        | 3      | 1.64%   |
| Lexar                       | 3        | 3      | 1.64%   |
| HGST                        | 3        | 3      | 1.64%   |
| Colorful                    | 3        | 3      | 1.64%   |
| ZOTAC                       | 2        | 2      | 1.09%   |
| Transcend                   | 2        | 2      | 1.09%   |
| TO Exter                    | 2        | 3      | 1.09%   |
| OCZ                         | 2        | 2      | 1.09%   |
| Netac                       | 2        | 2      | 1.09%   |
| JMicron Technology          | 2        | 2      | 1.09%   |
| Gigabyte Technology         | 2        | 2      | 1.09%   |
| Fujitsu                     | 2        | 2      | 1.09%   |
| VSP                         | 1        | 1      | 0.55%   |
| Vaseky                      | 1        | 1      | 0.55%   |
| SK hynix                    | 1        | 1      | 0.55%   |
| Realtek Semiconductor       | 1        | 2      | 0.55%   |
| Phison                      | 1        | 2      | 0.55%   |
| Patriot                     | 1        | 1      | 0.55%   |
| Mushkin                     | 1        | 1      | 0.55%   |
| Micron/Crucial Technology   | 1        | 1      | 0.55%   |
| Micron Technology           | 1        | 1      | 0.55%   |
| Maxtor                      | 1        | 1      | 0.55%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.55%   |
| Lite-On                     | 1        | 1      | 0.55%   |
| KING                        | 1        | 1      | 0.55%   |
| External                    | 1        | 1      | 0.55%   |
| EK                          | 1        | 1      | 0.55%   |
| China                       | 1        | 1      | 0.55%   |
| BR                          | 1        | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 6        | 2.97%   |
| Seagate ST1000DM010-2EP102 1TB                      | 4        | 1.98%   |
| Kingston SA400S37240G 240GB SSD                     | 4        | 1.98%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 3        | 1.49%   |
| WDC WD2500AAKX-00ERMA0 250GB                        | 3        | 1.49%   |
| ZOTAC SATA SSD 120GB                                | 2        | 0.99%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 2        | 0.99%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 2        | 0.99%   |
| WDC WD3200AAKX-001CA0 320GB                         | 2        | 0.99%   |
| Unknown SD/MMC/MS PRO 16GB                          | 2        | 0.99%   |
| Toshiba DT01ABA100V 1TB                             | 2        | 0.99%   |
| TO Exter nal USB 3.0 240GB                          | 2        | 0.99%   |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 0.99%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 0.99%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2        | 0.99%   |
| Seagate ST1000DM003-1ER162 1TB                      | 2        | 0.99%   |
| Samsung SSD 980 1TB                                 | 2        | 0.99%   |
| Samsung SSD 860 EVO 500GB                           | 2        | 0.99%   |
| Samsung SSD 860 EVO 250GB                           | 2        | 0.99%   |
| Samsung SSD 860 EVO 1TB                             | 2        | 0.99%   |
| Samsung SSD 750 EVO 120GB                           | 2        | 0.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2        | 0.99%   |
| Lexar 128GB SSD                                     | 2        | 0.99%   |
| Kingston SKC600256G 256GB SSD                       | 2        | 0.99%   |
| Kingston SA400S37120G 120GB SSD                     | 2        | 0.99%   |
| JMicron Tech 250GB                                  | 2        | 0.99%   |
| Hitachi HDT725032VLA380 320GB                       | 2        | 0.99%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD                | 2        | 0.99%   |
| Crucial CT250MX500SSD1 250GB                        | 2        | 0.99%   |
| WDC WDS500G2B0C-00PXH0 500GB                        | 1        | 0.5%    |
| WDC WDS250G3X0C-00SJG0 250GB                        | 1        | 0.5%    |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 1        | 0.5%    |
| WDC WDS120G1G0A-00SS50 120GB SSD                    | 1        | 0.5%    |
| WDC WDS100T3X0C-00SJG0 1TB                          | 1        | 0.5%    |
| WDC WD80EFBX-68AZZN0 8TB                            | 1        | 0.5%    |
| WDC WD80 03FFBX-68B9AN0 8TB                         | 1        | 0.5%    |
| WDC WD60PURX-64T0ZY0 6TB                            | 1        | 0.5%    |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1        | 0.5%    |
| WDC WD5000LPLX-66ZNTT1 500GB                        | 1        | 0.5%    |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 37       | 46     | 42.05%  |
| Seagate | 32       | 39     | 36.36%  |
| Toshiba | 7        | 13     | 7.95%   |
| Hitachi | 5        | 6      | 5.68%   |
| HGST    | 3        | 3      | 3.41%   |
| Unknown | 2        | 2      | 2.27%   |
| Fujitsu | 2        | 2      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 16.44%  |
| Samsung Electronics | 12       | 17     | 16.44%  |
| Kingston            | 12       | 15     | 16.44%  |
| Intel               | 4        | 4      | 5.48%   |
| Crucial             | 4        | 5      | 5.48%   |
| SanDisk             | 3        | 3      | 4.11%   |
| Lexar               | 3        | 3      | 4.11%   |
| Colorful            | 3        | 3      | 4.11%   |
| ZOTAC               | 2        | 2      | 2.74%   |
| Transcend           | 2        | 2      | 2.74%   |
| TO Exter            | 2        | 3      | 2.74%   |
| Netac               | 2        | 2      | 2.74%   |
| Gigabyte Technology | 2        | 2      | 2.74%   |
| VSP                 | 1        | 1      | 1.37%   |
| Vaseky              | 1        | 1      | 1.37%   |
| Toshiba             | 1        | 1      | 1.37%   |
| SK hynix            | 1        | 1      | 1.37%   |
| Patriot             | 1        | 1      | 1.37%   |
| OCZ                 | 1        | 1      | 1.37%   |
| Micron Technology   | 1        | 1      | 1.37%   |
| Maxtor              | 1        | 1      | 1.37%   |
| EK                  | 1        | 1      | 1.37%   |
| China               | 1        | 1      | 1.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 71       | 111    | 43.83%  |
| SSD     | 62       | 83     | 38.27%  |
| NVMe    | 23       | 31     | 14.2%   |
| Unknown | 6        | 6      | 3.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 91       | 188    | 74.59%  |
| NVMe | 22       | 30     | 18.03%  |
| SAS  | 9        | 13     | 7.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 82       | 127    | 64.06%  |
| 0.51-1.0   | 30       | 41     | 23.44%  |
| 1.01-2.0   | 8        | 11     | 6.25%   |
| 4.01-10.0  | 5        | 12     | 3.91%   |
| 3.01-4.0   | 2        | 2      | 1.56%   |
| 2.01-3.0   | 1        | 1      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 36       | 33.96%  |
| 251-500        | 17       | 16.04%  |
| 501-1000       | 17       | 16.04%  |
| 1001-2000      | 8        | 7.55%   |
| 51-100         | 6        | 5.66%   |
| More than 3000 | 5        | 4.72%   |
| 1-20           | 5        | 4.72%   |
| 21-50          | 4        | 3.77%   |
| 2001-3000      | 4        | 3.77%   |
| Unknown        | 4        | 3.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 37       | 35.24%  |
| 51-100         | 15       | 14.29%  |
| 21-50          | 14       | 13.33%  |
| 251-500        | 11       | 10.48%  |
| 101-250        | 10       | 9.52%   |
| 501-1000       | 7        | 6.67%   |
| Unknown        | 4        | 3.81%   |
| More than 3000 | 3        | 2.86%   |
| 2001-3000      | 2        | 1.9%    |
| 1001-2000      | 2        | 1.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD3200AAKX-001CA0 320GB         | 2        | 2      | 14.29%  |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 1      | 7.14%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1        | 1      | 7.14%   |
| Transcend TS256GSSD230S 256GB       | 1        | 1      | 7.14%   |
| Seagate ST9250410AS 250GB           | 1        | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 7.14%   |
| Seagate ST1000DM003-1ER162 1TB      | 1        | 1      | 7.14%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 7.14%   |
| Intel SSDSC2CW120A3 120GB           | 1        | 1      | 7.14%   |
| Hitachi HUA722020ALA331 2TB         | 1        | 1      | 7.14%   |
| Hitachi HDT725032VLA380 320GB       | 1        | 2      | 7.14%   |
| HGST HTS725050A7E630 500GB          | 1        | 1      | 7.14%   |
| Fujitsu MHK2120AT 12GB              | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 28.57%  |
| Seagate             | 3        | 3      | 21.43%  |
| Hitachi             | 2        | 3      | 14.29%  |
| Transcend           | 1        | 1      | 7.14%   |
| Samsung Electronics | 1        | 1      | 7.14%   |
| Intel               | 1        | 1      | 7.14%   |
| HGST                | 1        | 1      | 7.14%   |
| Fujitsu             | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 30%     |
| Seagate | 3        | 3      | 30%     |
| Hitachi | 2        | 3      | 20%     |
| HGST    | 1        | 1      | 10%     |
| Fujitsu | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 11     | 76.92%  |
| SSD  | 3        | 4      | 23.08%  |

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
| Detected | 53       | 108    | 46.09%  |
| Works    | 49       | 107    | 42.61%  |
| Malfunc  | 12       | 15     | 10.43%  |
| Failed   | 1        | 1      | 0.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 84       | 63.64%  |
| AMD                          | 17       | 12.88%  |
| Samsung Electronics          | 10       | 7.58%   |
| SanDisk                      | 6        | 4.55%   |
| ASMedia Technology           | 3        | 2.27%   |
| Micron/Crucial Technology    | 2        | 1.52%   |
| Toshiba America Info Systems | 1        | 0.76%   |
| Silicon Motion               | 1        | 0.76%   |
| Realtek Semiconductor        | 1        | 0.76%   |
| Phison Electronics           | 1        | 0.76%   |
| OCZ Technology Group         | 1        | 0.76%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.76%   |
| Marvell Technology Group     | 1        | 0.76%   |
| LSI Logic / Symbios Logic    | 1        | 0.76%   |
| Lite-On Technology           | 1        | 0.76%   |
| JMicron Technology           | 1        | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 8.07%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 8.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 5.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 4.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 4.35%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 4.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 3.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 3.11%   |
| Samsung NVMe SSD Controller 980                                                         | 4        | 2.48%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3        | 1.86%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 1.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.86%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.24%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.24%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.24%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.24%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.24%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.24%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.62%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.62%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.62%   |
| Phison NVMe Storage Controller                                                          | 1        | 0.62%   |
| OCZ Group RD400/400A SSD                                                                | 1        | 0.62%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.62%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.62%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1        | 0.62%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.62%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                                    | 1        | 0.62%   |
| Lite-On Non-Volatile memory controller                                                  | 1        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 80       | 62.5%   |
| NVMe | 22       | 17.19%  |
| IDE  | 21       | 16.41%  |
| RAID | 4        | 3.13%   |
| SAS  | 1        | 0.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 84       | 83.17%  |
| AMD    | 17       | 16.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 3.96%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 3.96%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 2.97%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 2.97%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 1.98%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.98%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.98%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 1.98%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.98%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.98%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.98%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.98%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 2        | 1.98%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.98%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.98%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.98%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 0.99%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1        | 0.99%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1        | 0.99%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz          | 1        | 0.99%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.99%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.99%   |
| Intel Xeon CPU E31235 @ 3.20GHz             | 1        | 0.99%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1        | 0.99%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.99%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.99%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.99%   |
| Intel Pentium CPU G640T @ 2.40GHz           | 1        | 0.99%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.99%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.99%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 0.99%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.99%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.99%   |
| Intel Core i7-7700T CPU @ 2.90GHz           | 1        | 0.99%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.99%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.99%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 1        | 0.99%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.99%   |
| Intel Core i5-9500 CPU @ 3.00GHz            | 1        | 0.99%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 28       | 27.72%  |
| Intel Core i3           | 18       | 17.82%  |
| Intel Core i7           | 10       | 9.9%    |
| Intel Xeon              | 8        | 7.92%   |
| AMD Ryzen 5             | 8        | 7.92%   |
| Intel Core 2 Duo        | 7        | 6.93%   |
| Other                   | 3        | 2.97%   |
| Intel Pentium           | 3        | 2.97%   |
| Intel Celeron           | 2        | 1.98%   |
| AMD Ryzen 9             | 2        | 1.98%   |
| AMD A10                 | 2        | 1.98%   |
| Intel Pentium Gold      | 1        | 0.99%   |
| Intel Pentium Dual-Core | 1        | 0.99%   |
| Intel Pentium Dual      | 1        | 0.99%   |
| Intel Core i9           | 1        | 0.99%   |
| Intel Core 2 Quad       | 1        | 0.99%   |
| AMD Ryzen 7 PRO         | 1        | 0.99%   |
| AMD Ryzen 3             | 1        | 0.99%   |
| AMD Phenom II X4        | 1        | 0.99%   |
| AMD Athlon II X2        | 1        | 0.99%   |
| AMD A8                  | 1        | 0.99%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 42       | 41.18%  |
| 2      | 30       | 29.41%  |
| 6      | 19       | 18.63%  |
| 8      | 5        | 4.9%    |
| 16     | 3        | 2.94%   |
| 28     | 1        | 0.98%   |
| 24     | 1        | 0.98%   |
| 12     | 1        | 0.98%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 99       | 97.06%  |
| 2      | 3        | 2.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 51       | 50.5%   |
| 1      | 50       | 49.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 100      | 99.01%  |
| Unknown        | 1        | 0.99%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 17.82%  |
| 0x306c3    | 10       | 9.9%    |
| 0x306a9    | 8        | 7.92%   |
| 0x906ea    | 7        | 6.93%   |
| 0x1067a    | 7        | 6.93%   |
| 0x206a7    | 6        | 5.94%   |
| 0xa0653    | 4        | 3.96%   |
| 0x906eb    | 3        | 2.97%   |
| 0x906e9    | 3        | 2.97%   |
| 0x506e3    | 3        | 2.97%   |
| 0x206d7    | 3        | 2.97%   |
| 0x906ed    | 2        | 1.98%   |
| 0x90672    | 2        | 1.98%   |
| 0x30678    | 2        | 1.98%   |
| 0x20655    | 2        | 1.98%   |
| 0x08701021 | 2        | 1.98%   |
| 0x06003106 | 2        | 1.98%   |
| 0x90675    | 1        | 0.99%   |
| 0x6fd      | 1        | 0.99%   |
| 0x406f1    | 1        | 0.99%   |
| 0x306f2    | 1        | 0.99%   |
| 0x106a5    | 1        | 0.99%   |
| 0x10676    | 1        | 0.99%   |
| 0x0a50000d | 1        | 0.99%   |
| 0x0a50000c | 1        | 0.99%   |
| 0x0a20120a | 1        | 0.99%   |
| 0x0a201016 | 1        | 0.99%   |
| 0x08701013 | 1        | 0.99%   |
| 0x08108109 | 1        | 0.99%   |
| 0x0810100b | 1        | 0.99%   |
| 0x0800820d | 1        | 0.99%   |
| 0x06001119 | 1        | 0.99%   |
| 0x010000db | 1        | 0.99%   |
| 0x010000c7 | 1        | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 18       | 17.82%  |
| Haswell          | 17       | 16.83%  |
| IvyBridge        | 10       | 9.9%    |
| SandyBridge      | 9        | 8.91%   |
| Penryn           | 9        | 8.91%   |
| Skylake          | 6        | 5.94%   |
| Zen 3            | 4        | 3.96%   |
| Zen 2            | 4        | 3.96%   |
| CometLake        | 4        | 3.96%   |
| Zen+             | 3        | 2.97%   |
| Westmere         | 3        | 2.97%   |
| Alderlake Hybrid | 3        | 2.97%   |
| Steamroller      | 2        | 1.98%   |
| Silvermont       | 2        | 1.98%   |
| K10              | 2        | 1.98%   |
| Zen              | 1        | 0.99%   |
| Piledriver       | 1        | 0.99%   |
| Nehalem          | 1        | 0.99%   |
| Core             | 1        | 0.99%   |
| Broadwell        | 1        | 0.99%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 49       | 43.36%  |
| Intel             | 39       | 34.51%  |
| AMD               | 24       | 21.24%  |
| ASPEED Technology | 1        | 0.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 6.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 6.9%    |
| Nvidia GK208B [GeForce GT 730]                                              | 7        | 6.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 5.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 3.45%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 2.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 2.59%   |
| Intel HD Graphics 530                                                       | 3        | 2.59%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 2.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.59%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 2        | 1.72%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.72%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.72%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.72%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 1.72%   |
| Intel HD Graphics 630                                                       | 2        | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 1.72%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.72%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.72%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.86%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.86%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.86%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.86%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.86%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.86%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 6GB Rev. 2]                                  | 1        | 0.86%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1        | 0.86%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.86%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.86%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 0.86%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 0.86%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.86%   |
| Nvidia GK208 [GeForce GT 710]                                               | 1        | 0.86%   |
| Nvidia GK107GL [Quadro K420]                                                | 1        | 0.86%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.86%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 0.86%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 41       | 40.2%   |
| 1 x Intel       | 29       | 28.43%  |
| 1 x AMD         | 24       | 23.53%  |
| Intel + Nvidia  | 7        | 6.86%   |
| Nvidia + ASPEED | 1        | 0.98%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 65       | 63.11%  |
| Proprietary | 37       | 35.92%  |
| Unknown     | 1        | 0.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 37       | 36.27%  |
| 1.01-2.0   | 17       | 16.67%  |
| 3.01-4.0   | 15       | 14.71%  |
| 0.51-1.0   | 8        | 7.84%   |
| 7.01-8.0   | 7        | 6.86%   |
| 5.01-6.0   | 6        | 5.88%   |
| 8.01-16.0  | 6        | 5.88%   |
| 0.01-0.5   | 6        | 5.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 28       | 28%     |
| Samsung Electronics  | 17       | 17%     |
| Goldstar             | 10       | 10%     |
| Hewlett-Packard      | 5        | 5%      |
| AOC                  | 5        | 5%      |
| ViewSonic            | 4        | 4%      |
| Ancor Communications | 4        | 4%      |
| Panasonic            | 3        | 3%      |
| Gigabyte Technology  | 2        | 2%      |
| FPT                  | 2        | 2%      |
| BenQ                 | 2        | 2%      |
| ASUSTek Computer     | 2        | 2%      |
| Acer                 | 2        | 2%      |
| Unknown              | 2        | 2%      |
| Unknown (ADA)        | 1        | 1%      |
| Sony                 | 1        | 1%      |
| Philips              | 1        | 1%      |
| NEC Computers        | 1        | 1%      |
| Mi                   | 1        | 1%      |
| LG Electronics       | 1        | 1%      |
| Lenovo Group Limited | 1        | 1%      |
| Lenovo               | 1        | 1%      |
| HPN                  | 1        | 1%      |
| HOP                  | 1        | 1%      |
| CGC                  | 1        | 1%      |
| AUS                  | 1        | 1%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Panasonic TV MEIC33B 1366x768 521x293mm 23.5-inch                     | 3        | 2.88%   |
| Samsung Electronics SME1720NR SAM0696 1280x1024 338x270mm 17.0-inch   | 2        | 1.92%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 1.92%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 2        | 1.92%   |
| FPT F22FAD FPTF22F 1920x1080 477x268mm 21.5-inch                      | 2        | 1.92%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 2        | 1.92%   |
| Unknown                                                               | 2        | 1.92%   |
| ViewSonic VA2409-FHD VSC983D 1920x1080 521x293mm 23.5-inch            | 1        | 0.96%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 477x268mm 21.5-inch            | 1        | 0.96%   |
| ViewSonic VA2201-FHD VSC683B 1920x1080 480x260mm 21.5-inch            | 1        | 0.96%   |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                             | 1        | 0.96%   |
| Unknown (ADA) LCD Monitor ADA0004 1024x600 150x100mm 7.1-inch         | 1        | 0.96%   |
| Sony TV SNY8E03 1920x1080                                             | 1        | 0.96%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 1        | 0.96%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.96%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch     | 1        | 0.96%   |
| Samsung Electronics S20D300 SAM0B39 1600x900 432x240mm 19.5-inch      | 1        | 0.96%   |
| Samsung Electronics S20B370 SAM08B7 1600x900 443x249mm 20.0-inch      | 1        | 0.96%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch      | 1        | 0.96%   |
| Samsung Electronics S19C300 SAM0A12 1366x768 410x230mm 18.5-inch      | 1        | 0.96%   |
| Samsung Electronics S19C170 SAM0B02 1366x768 410x230mm 18.5-inch      | 1        | 0.96%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1        | 0.96%   |
| Samsung Electronics LCD Monitor SME1720NR 1280x1024                   | 1        | 0.96%   |
| Samsung Electronics LCD Monitor SMB1930N                              | 1        | 0.96%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 950x540mm 43.0-inch | 1        | 0.96%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 950x540mm 43.0-inch | 1        | 0.96%   |
| Samsung Electronics LCD Monitor SAM0658 1920x1080 886x498mm 40.0-inch | 1        | 0.96%   |
| Philips 24PHT4003S/74 PHT4003 1360x768 525x297mm 23.7-inch            | 1        | 0.96%   |
| NEC Computers LCD172VXM NEC67C5 1280x1024 338x270mm 17.0-inch         | 1        | 0.96%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 1        | 0.96%   |
| LG Electronics LCD Monitor MP59G                                      | 1        | 0.96%   |
| Lenovo LEN L1900pA LEN114F 1280x1024 376x301mm 19.0-inch              | 1        | 0.96%   |
| Lenovo Group Limited LCD Monitor LEN L1900pA 1280x1024                | 1        | 0.96%   |
| HPN LCD Monitor HP Z23n G2 1920x1080                                  | 1        | 0.96%   |
| HOP DVI HOP2700 1920x1080 597x336mm 27.0-inch                         | 1        | 0.96%   |
| Hewlett-Packard w1707 HWP2800 1440x900 370x230mm 17.2-inch            | 1        | 0.96%   |
| Hewlett-Packard N220 HPN3408 1920x1080 476x268mm 21.5-inch            | 1        | 0.96%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 1        | 0.96%   |
| Hewlett-Packard LCD Monitor E242 1920x1200                            | 1        | 0.96%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch           | 1        | 0.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 48       | 48%     |
| 3840x2160 (4K)    | 9        | 9%      |
| 1366x768 (WXGA)   | 9        | 9%      |
| 1280x1024 (SXGA)  | 8        | 8%      |
| 2560x1440 (QHD)   | 7        | 7%      |
| 1600x900 (HD+)    | 7        | 7%      |
| Unknown           | 3        | 3%      |
| 1920x1200 (WUXGA) | 2        | 2%      |
| 1440x900 (WXGA+)  | 2        | 2%      |
| 3840x1080         | 1        | 1%      |
| 3440x1440         | 1        | 1%      |
| 3286x1080         | 1        | 1%      |
| 1360x768          | 1        | 1%      |
| 1280x800 (WXGA)   | 1        | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 16       | 16%     |
| 21      | 15       | 15%     |
| Unknown | 15       | 15%     |
| 27      | 13       | 13%     |
| 24      | 13       | 13%     |
| 18      | 6        | 6%      |
| 20      | 5        | 5%      |
| 19      | 5        | 5%      |
| 17      | 5        | 5%      |
| 84      | 2        | 2%      |
| 42      | 1        | 1%      |
| 40      | 1        | 1%      |
| 34      | 1        | 1%      |
| 25      | 1        | 1%      |
| 7       | 1        | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 41       | 41.84%  |
| 401-500     | 28       | 28.57%  |
| Unknown     | 15       | 15.31%  |
| 301-350     | 4        | 4.08%   |
| 351-400     | 3        | 3.06%   |
| 1501-2000   | 2        | 2.04%   |
| 801-900     | 1        | 1.02%   |
| 701-800     | 1        | 1.02%   |
| 601-700     | 1        | 1.02%   |
| 101-200     | 1        | 1.02%   |
| 901-1000    | 1        | 1.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 70       | 73.68%  |
| Unknown | 14       | 14.74%  |
| 5/4     | 6        | 6.32%   |
| 16/10   | 3        | 3.16%   |
| 3/2     | 1        | 1.05%   |
| 21/9    | 1        | 1.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 37       | 37.76%  |
| Unknown        | 15       | 15.31%  |
| 151-200        | 14       | 14.29%  |
| 301-350        | 13       | 13.27%  |
| 141-150        | 10       | 10.2%   |
| More than 1000 | 2        | 2.04%   |
| 251-300        | 2        | 2.04%   |
| 501-1000       | 2        | 2.04%   |
| 351-500        | 1        | 1.02%   |
| 1-40           | 1        | 1.02%   |
| 131-140        | 1        | 1.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 56       | 57.14%  |
| 101-120 | 21       | 21.43%  |
| Unknown | 15       | 15.31%  |
| 161-240 | 4        | 4.08%   |
| 121-160 | 2        | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 87       | 86.14%  |
| 2     | 8        | 7.92%   |
| 0     | 6        | 5.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 65       | 44.22%  |
| Intel                 | 37       | 25.17%  |
| Ralink Technology     | 9        | 6.12%   |
| Qualcomm Atheros      | 9        | 6.12%   |
| Broadcom              | 8        | 5.44%   |
| TP-Link               | 6        | 4.08%   |
| ASIX Electronics      | 4        | 2.72%   |
| Ralink                | 2        | 1.36%   |
| D-Link                | 2        | 1.36%   |
| Samsung Electronics   | 1        | 0.68%   |
| MediaTek              | 1        | 0.68%   |
| ICS Advent            | 1        | 0.68%   |
| Edimax Technology     | 1        | 0.68%   |
| Aquantia              | 1        | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54       | 33.13%  |
| Intel Ethernet Connection (7) I219-V                              | 6        | 3.68%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 3.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 2.45%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 2.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.84%   |
| Intel I210 Gigabit Network Connection                             | 3        | 1.84%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.84%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.84%   |
| ASIX AX88772A Fast Ethernet                                       | 3        | 1.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.23%   |
| TP-Link 802.11ac NIC                                              | 2        | 1.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.23%   |
| Realtek 802.11ac NIC                                              | 2        | 1.23%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 1.23%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 1.23%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.23%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.23%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.23%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.23%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2        | 1.23%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2        | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2        | 1.23%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.61%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.61%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.61%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.61%   |
| Ralink RT2070 Wireless Adapter                                    | 1        | 0.61%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1        | 0.61%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 22.92%  |
| Ralink Technology     | 9        | 18.75%  |
| Intel                 | 9        | 18.75%  |
| TP-Link               | 6        | 12.5%   |
| Qualcomm Atheros      | 4        | 8.33%   |
| Broadcom              | 4        | 8.33%   |
| Ralink                | 2        | 4.17%   |
| D-Link                | 2        | 4.17%   |
| Edimax Technology     | 1        | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 5        | 10.42%  |
| Ralink MT7601U Wireless Adapter                                | 4        | 8.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2        | 4.17%   |
| TP-Link 802.11ac NIC                                           | 2        | 4.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2        | 4.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 4.17%   |
| Realtek 802.11ac NIC                                           | 2        | 4.17%   |
| Ralink RT5370 Wireless Adapter                                 | 2        | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 4.17%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2        | 4.17%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2        | 4.17%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 2.08%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 2.08%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 2.08%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 2.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 2.08%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 2.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 2.08%   |
| Ralink RT2070 Wireless Adapter                                 | 1        | 2.08%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1        | 2.08%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1        | 2.08%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 1        | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 2.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 2.08%   |
| Intel Wireless 7265                                            | 1        | 2.08%   |
| Intel Wireless 3165                                            | 1        | 2.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 2.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 2.08%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 2.08%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter             | 1        | 2.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1        | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 62       | 55.86%  |
| Intel                 | 32       | 28.83%  |
| Qualcomm Atheros      | 5        | 4.5%    |
| Broadcom              | 4        | 3.6%    |
| ASIX Electronics      | 4        | 3.6%    |
| Samsung Electronics   | 1        | 0.9%    |
| MediaTek              | 1        | 0.9%    |
| ICS Advent            | 1        | 0.9%    |
| Aquantia              | 1        | 0.9%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54       | 46.96%  |
| Intel Ethernet Connection (7) I219-V                              | 6        | 5.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 3.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.61%   |
| Intel I210 Gigabit Network Connection                             | 3        | 2.61%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.61%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.61%   |
| ASIX AX88772A Fast Ethernet                                       | 3        | 2.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 1.74%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.74%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.74%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.74%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.74%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.74%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2        | 1.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.87%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.87%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.87%   |
| MediaTek Armor 8 Pro                                              | 1        | 0.87%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.87%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.87%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.87%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.87%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 0.87%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.87%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.87%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 0.87%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1        | 0.87%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1        | 0.87%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.87%   |
| Aquantia Ethernet controller                                      | 1        | 0.87%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 100      | 68.97%  |
| WiFi     | 45       | 31.03%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 73       | 69.52%  |
| WiFi     | 32       | 30.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 72       | 70.59%  |
| 2     | 23       | 22.55%  |
| 3     | 6        | 5.88%   |
| 0     | 1        | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 75.49%  |
| Yes  | 25       | 24.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 15       | 42.86%  |
| Intel                           | 9        | 25.71%  |
| Realtek Semiconductor           | 4        | 11.43%  |
| Qualcomm Atheros Communications | 2        | 5.71%   |
| Broadcom                        | 2        | 5.71%   |
| TP-Link                         | 1        | 2.86%   |
| Conwise Technology              | 1        | 2.86%   |
| Apple                           | 1        | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15       | 42.86%  |
| Intel AX200 Bluetooth                               | 5        | 14.29%  |
| Realtek Bluetooth Radio                             | 4        | 11.43%  |
| Intel Bluetooth wireless interface                  | 2        | 5.71%   |
| TP-Link TPuLink UB500 Adapter                       | 1        | 2.86%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 2.86%   |
| Intel Bluetooth Device                              | 1        | 2.86%   |
| Intel AX210 Bluetooth                               | 1        | 2.86%   |
| Conwise CW6622                                      | 1        | 2.86%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1        | 2.86%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1        | 2.86%   |
| Apple Bluetooth Host Controller                     | 1        | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 83       | 46.63%  |
| Nvidia                    | 48       | 26.97%  |
| AMD                       | 28       | 15.73%  |
| C-Media Electronics       | 4        | 2.25%   |
| Generalplus Technology    | 3        | 1.69%   |
| Creative Labs             | 2        | 1.12%   |
| Shenzhen Rapoo Technology | 1        | 0.56%   |
| Nordic Semiconductor ASA  | 1        | 0.56%   |
| Logitech                  | 1        | 0.56%   |
| JMTek                     | 1        | 0.56%   |
| GYROCOM C&C               | 1        | 0.56%   |
| Elgato Systems            | 1        | 0.56%   |
| Creative Technology       | 1        | 0.56%   |
| Audient                   | 1        | 0.56%   |
| Apple                     | 1        | 0.56%   |
| AGPTek                    | 1        | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 6.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 6%      |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 5%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9        | 4.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 4.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 4%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8        | 4%      |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 3.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7        | 3.5%    |
| Intel 200 Series PCH HD Audio                                              | 6        | 3%      |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 2.5%    |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 2.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 2%      |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 2%      |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.5%    |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.5%    |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 1.5%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1.5%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 1.5%    |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.5%    |
| Generalplus Technology USB Audio Device                                    | 3        | 1.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.5%    |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1%      |
| Nvidia TU102 High Definition Audio Controller                              | 2        | 1%      |
| Nvidia High Definition Audio Controller                                    | 2        | 1%      |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 1%      |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1%      |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1%      |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 1%      |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1%      |
| AMD FCH Azalia Controller                                                  | 2        | 1%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1%      |
| Shenzhen Rapoo Technology Rapoo Gaming Headset                             | 1        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Kingston              | 15       | 23.08%  |
| Corsair               | 13       | 20%     |
| G.Skill               | 7        | 10.77%  |
| Unknown               | 6        | 9.23%   |
| Samsung Electronics   | 5        | 7.69%   |
| SK hynix              | 4        | 6.15%   |
| Kingmax               | 4        | 6.15%   |
| Crucial               | 3        | 4.62%   |
| A-DATA Technology     | 2        | 3.08%   |
| Team                  | 1        | 1.54%   |
| Ramaxel Technology    | 1        | 1.54%   |
| Patriot               | 1        | 1.54%   |
| Micron Technology     | 1        | 1.54%   |
| Kingmax Semiconductor | 1        | 1.54%   |
| Apacer                | 1        | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s       | 4        | 5.63%   |
| Unknown RAM Module 1GB DIMM 800MT/s                        | 2        | 2.82%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s     | 2        | 2.82%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s               | 1        | 1.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 200MT/s                | 1        | 1.41%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                 | 1        | 1.41%   |
| Unknown RAM BAPC08G3000D4T8 8192MB DIMM DDR4 2133MT/s      | 1        | 1.41%   |
| Team RAM TEAMGROUP-UD3-160 4096MB DIMM DDR3 1333MT/s       | 1        | 1.41%   |
| SK hynix RAM SNOAMOO Ltd:016M00 4096MB DIMM DDR3 1600MT/s  | 1        | 1.41%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s        | 1        | 1.41%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s       | 1        | 1.41%   |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB DIMM DDR3 1600MT/s    | 1        | 1.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1        | 1.41%   |
| Samsung RAM M393B2K70CM0-YF8 16GB DIMM DDR3 1067MT/s       | 1        | 1.41%   |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1866MT/s           | 1        | 1.41%   |
| Samsung RAM M393A2K40BB1-CRC 16GB DIMM DDR4 2400MT/s       | 1        | 1.41%   |
| Samsung RAM M378A5244CB0-CTD 4096MB DIMM DDR4 3334MT/s     | 1        | 1.41%   |
| Ramaxel RAM RMR5040MM58F9F1600 4096MB DIMM DDR3 1600MT/s   | 1        | 1.41%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s             | 1        | 1.41%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 1        | 1.41%   |
| Kingston RAM Module 8GB DIMM DDR4 2667MT/s                 | 1        | 1.41%   |
| Kingston RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 1.41%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 1.41%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s       | 1        | 1.41%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 1        | 1.41%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s          | 1        | 1.41%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s        | 1        | 1.41%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s      | 1        | 1.41%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s      | 1        | 1.41%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s      | 1        | 1.41%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Kingston RAM 9965525-139.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Kingston RAM 9965413-002.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 1.41%   |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 2667MT/s       | 1        | 1.41%   |
| Kingston RAM 9905712-008.A00G 16GB SODIMM DDR4 2400MT/s    | 1        | 1.41%   |
| Kingmax RAM GZNH23F-18--------- 16GB DIMM DDR4 2666MT/s    | 1        | 1.41%   |
| Kingmax RAM GLAH22F-18--------- 16384MB DIMM DDR4 2666MT/s | 1        | 1.41%   |
| Kingmax RAM FLGF65F-D8KM 4GB DIMM DDR3 1333MT/s            | 1        | 1.41%   |
| Kingmax RAM FLGE85F-B8KLB 2GB DIMM DDR3 1067MT/s           | 1        | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 32       | 55.17%  |
| DDR3    | 21       | 36.21%  |
| DDR2    | 2        | 3.45%   |
| Unknown | 2        | 3.45%   |
| DDR     | 1        | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 56       | 96.55%  |
| SODIMM | 2        | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 27       | 43.55%  |
| 4096  | 15       | 24.19%  |
| 16384 | 13       | 20.97%  |
| 1024  | 4        | 6.45%   |
| 2048  | 3        | 4.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 13       | 19.12%  |
| 3200  | 7        | 10.29%  |
| 3000  | 7        | 10.29%  |
| 2400  | 7        | 10.29%  |
| 1333  | 6        | 8.82%   |
| 2667  | 4        | 5.88%   |
| 800   | 3        | 4.41%   |
| 3600  | 2        | 2.94%   |
| 2800  | 2        | 2.94%   |
| 2666  | 2        | 2.94%   |
| 1866  | 2        | 2.94%   |
| 1067  | 2        | 2.94%   |
| 3666  | 1        | 1.47%   |
| 3466  | 1        | 1.47%   |
| 3400  | 1        | 1.47%   |
| 3334  | 1        | 1.47%   |
| 3007  | 1        | 1.47%   |
| 2133  | 1        | 1.47%   |
| 1867  | 1        | 1.47%   |
| 1648  | 1        | 1.47%   |
| 1066  | 1        | 1.47%   |
| 200   | 1        | 1.47%   |
| 133   | 1        | 1.47%   |

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
| Logitech                        | 5        | 41.67%  |
| Samsung Electronics             | 1        | 8.33%   |
| Microdia                        | 1        | 8.33%   |
| KYE Systems (Mouse Systems)     | 1        | 8.33%   |
| Intel                           | 1        | 8.33%   |
| IDS Imaging Development Systems | 1        | 8.33%   |
| Aveo Technology                 | 1        | 8.33%   |
| Apple                           | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 3        | 25%     |
| Samsung Galaxy A5 (MTP)                         | 1        | 8.33%   |
| Microdia Rapoo Camera                           | 1        | 8.33%   |
| Logitech Webcam C310                            | 1        | 8.33%   |
| Logitech Webcam C210                            | 1        | 8.33%   |
| KYE Systems (Mouse Systems) JOYACCESS JA-Webcam | 1        | 8.33%   |
| Intel RealSense Depth Camera 435                | 1        | 8.33%   |
| IDS Imaging Development Systems USB 3.0 Camera  | 1        | 8.33%   |
| Aveo USB2.0 Camera                              | 1        | 8.33%   |
| Apple iPhone 5/5C/5S/6/SE                       | 1        | 8.33%   |

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
| 0     | 89       | 88.12%  |
| 1     | 11       | 10.89%  |
| 2     | 1        | 0.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 38.46%  |
| Unassigned class         | 3        | 23.08%  |
| Net/wireless             | 3        | 23.08%  |
| Communication controller | 1        | 7.69%   |
| Camera                   | 1        | 7.69%   |

