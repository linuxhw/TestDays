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

Total: 132

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 24       | 24.49%  |
| Ubuntu 18.04                 | 16       | 16.33%  |
| Ubuntu 22.04                 | 5        | 5.1%    |
| Arch                         | 5        | 5.1%    |
| ArcoLinux Rolling            | 3        | 3.06%   |
| Arch Rolling                 | 3        | 3.06%   |
| Zorin 16                     | 2        | 2.04%   |
| Ubuntu Unity 16.04           | 2        | 2.04%   |
| Ubuntu 19.04                 | 2        | 2.04%   |
| Pop!_OS 20.10                | 2        | 2.04%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 2.04%   |
| Manjaro 20.2                 | 2        | 2.04%   |
| Manjaro                      | 2        | 2.04%   |
| Linux Mint 20.3              | 2        | 2.04%   |
| Fedora 37                    | 2        | 2.04%   |
| Debian 11                    | 2        | 2.04%   |
| Debian 10                    | 2        | 2.04%   |
| Zorin 15                     | 1        | 1.02%   |
| Xubuntu 20.04                | 1        | 1.02%   |
| Ubuntu 21.04                 | 1        | 1.02%   |
| Ubuntu 16.04                 | 1        | 1.02%   |
| Parrot 4.11                  | 1        | 1.02%   |
| OpenMandriva 4.50            | 1        | 1.02%   |
| OpenMandriva 4.3             | 1        | 1.02%   |
| OpenMandriva 4.2             | 1        | 1.02%   |
| Manjaro 21.0.1               | 1        | 1.02%   |
| Manjaro 20.0.3               | 1        | 1.02%   |
| Linux Mint 20                | 1        | 1.02%   |
| Kubuntu 22.04                | 1        | 1.02%   |
| Kubuntu 20.04                | 1        | 1.02%   |
| KDE neon 22.04               | 1        | 1.02%   |
| KDE neon 20.04               | 1        | 1.02%   |
| Fedora 36                    | 1        | 1.02%   |
| EndeavourOS Rolling          | 1        | 1.02%   |
| Elementary 6                 | 1        | 1.02%   |
| Clear Linux 34500            | 1        | 1.02%   |
| Clear Linux 32260            | 1        | 1.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 47       | 48.96%  |
| Arch         | 8        | 8.33%   |
| Manjaro      | 6        | 6.25%   |
| Debian       | 4        | 4.17%   |
| Zorin        | 3        | 3.13%   |
| OpenMandriva | 3        | 3.13%   |
| Linux Mint   | 3        | 3.13%   |
| Fedora       | 3        | 3.13%   |
| ArcoLinux    | 3        | 3.13%   |
| Ubuntu Unity | 2        | 2.08%   |
| Pop!_OS      | 2        | 2.08%   |
| openSUSE     | 2        | 2.08%   |
| Kubuntu      | 2        | 2.08%   |
| KDE neon     | 2        | 2.08%   |
| Clear Linux  | 2        | 2.08%   |
| Xubuntu      | 1        | 1.04%   |
| Parrot       | 1        | 1.04%   |
| EndeavourOS  | 1        | 1.04%   |
| Elementary   | 1        | 1.04%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.4.0-58-generic       | 4        | 3.81%   |
| 5.4.0-37-generic       | 3        | 2.86%   |
| 5.4.0-26-generic       | 3        | 2.86%   |
| 5.15.0-52-generic      | 3        | 2.86%   |
| 5.11.0-38-generic      | 3        | 2.86%   |
| 5.0.0-23-generic       | 3        | 2.86%   |
| 6.0.12-300.fc37.x86_64 | 2        | 1.9%    |
| 5.9.11-3-MANJARO       | 2        | 1.9%    |
| 5.8.0-7642-generic     | 2        | 1.9%    |
| 5.4.0-48-generic       | 2        | 1.9%    |
| 5.4.0-47-generic       | 2        | 1.9%    |
| 5.4.0-42-generic       | 2        | 1.9%    |
| 5.11.0-37-generic      | 2        | 1.9%    |
| 4.18.0-25-generic      | 2        | 1.9%    |
| 6.0.2-x64v1-xanmod1-1  | 1        | 0.95%   |
| 6.0.0-rc5              | 1        | 0.95%   |
| 5.9.12-arch1-1         | 1        | 0.95%   |
| 5.9.0-0.bpo.5-amd64    | 1        | 0.95%   |
| 5.8.0-59-generic       | 1        | 0.95%   |
| 5.8.0-55-generic       | 1        | 0.95%   |
| 5.8.0-53-generic       | 1        | 0.95%   |
| 5.8.0-50-generic       | 1        | 0.95%   |
| 5.8.0-45-generic       | 1        | 0.95%   |
| 5.8.0-43-generic       | 1        | 0.95%   |
| 5.6.15-1-MANJARO       | 1        | 0.95%   |
| 5.6.0-1-default        | 1        | 0.95%   |
| 5.4.78-2-pve           | 1        | 0.95%   |
| 5.4.18-902.native      | 1        | 0.95%   |
| 5.4.0-99-generic       | 1        | 0.95%   |
| 5.4.0-90-generic       | 1        | 0.95%   |
| 5.4.0-72-generic       | 1        | 0.95%   |
| 5.4.0-65-generic       | 1        | 0.95%   |
| 5.4.0-52-generic       | 1        | 0.95%   |
| 5.4.0-39-generic       | 1        | 0.95%   |
| 5.4.0-33-generic       | 1        | 0.95%   |
| 5.4.0-31-generic       | 1        | 0.95%   |
| 5.4.0-28-generic       | 1        | 0.95%   |
| 5.19.7-arch1-1         | 1        | 0.95%   |
| 5.19.4-arch1-1         | 1        | 0.95%   |
| 5.19.3-zen1-1-zen      | 1        | 0.95%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 23       | 22.77%  |
| 5.15.0  | 9        | 8.91%   |
| 5.11.0  | 9        | 8.91%   |
| 5.8.0   | 8        | 7.92%   |
| 5.0.0   | 6        | 5.94%   |
| 4.15.0  | 6        | 5.94%   |
| 6.0.12  | 2        | 1.98%   |
| 5.9.11  | 2        | 1.98%   |
| 5.15.60 | 2        | 1.98%   |
| 5.12.8  | 2        | 1.98%   |
| 4.18.0  | 2        | 1.98%   |
| 6.0.2   | 1        | 0.99%   |
| 6.0.0   | 1        | 0.99%   |
| 5.9.12  | 1        | 0.99%   |
| 5.9.0   | 1        | 0.99%   |
| 5.6.15  | 1        | 0.99%   |
| 5.6.0   | 1        | 0.99%   |
| 5.4.78  | 1        | 0.99%   |
| 5.4.18  | 1        | 0.99%   |
| 5.19.7  | 1        | 0.99%   |
| 5.19.4  | 1        | 0.99%   |
| 5.19.3  | 1        | 0.99%   |
| 5.19.17 | 1        | 0.99%   |
| 5.19.12 | 1        | 0.99%   |
| 5.18.9  | 1        | 0.99%   |
| 5.17.9  | 1        | 0.99%   |
| 5.17.1  | 1        | 0.99%   |
| 5.16.7  | 1        | 0.99%   |
| 5.15.53 | 1        | 0.99%   |
| 5.14.0  | 1        | 0.99%   |
| 5.12.15 | 1        | 0.99%   |
| 5.12.1  | 1        | 0.99%   |
| 5.11.16 | 1        | 0.99%   |
| 5.10.42 | 1        | 0.99%   |
| 5.10.26 | 1        | 0.99%   |
| 5.10.19 | 1        | 0.99%   |
| 5.10.14 | 1        | 0.99%   |
| 5.10.0  | 1        | 0.99%   |
| 4.19.97 | 1        | 0.99%   |
| 4.15.18 | 1        | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 25       | 25%     |
| 5.15    | 11       | 11%     |
| 5.11    | 10       | 10%     |
| 5.8     | 8        | 8%      |
| 4.15    | 7        | 7%      |
| 5.0     | 6        | 6%      |
| 5.19    | 5        | 5%      |
| 5.10    | 5        | 5%      |
| 6.0     | 4        | 4%      |
| 5.9     | 4        | 4%      |
| 5.12    | 4        | 4%      |
| 5.6     | 2        | 2%      |
| 5.17    | 2        | 2%      |
| 4.18    | 2        | 2%      |
| 5.18    | 1        | 1%      |
| 5.16    | 1        | 1%      |
| 5.14    | 1        | 1%      |
| 4.19    | 1        | 1%      |
| 4.10    | 1        | 1%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 94       | 98.95%  |
| i686   | 1        | 1.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 52       | 53.61%  |
| Unknown    | 18       | 18.56%  |
| KDE5       | 11       | 11.34%  |
| XFCE       | 3        | 3.09%   |
| MATE       | 3        | 3.09%   |
| Unity      | 2        | 2.06%   |
| KDE        | 2        | 2.06%   |
| X-Cinnamon | 1        | 1.03%   |
| Pantheon   | 1        | 1.03%   |
| i3         | 1        | 1.03%   |
| Cinnamon   | 1        | 1.03%   |
| bspwm      | 1        | 1.03%   |
| awesome    | 1        | 1.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 71       | 72.45%  |
| Wayland | 14       | 14.29%  |
| Unknown | 9        | 9.18%   |
| Tty     | 4        | 4.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 44       | 45.83%  |
| GDM     | 20       | 20.83%  |
| SDDM    | 11       | 11.46%  |
| LightDM | 8        | 8.33%   |
| GDM3    | 8        | 8.33%   |
| TDM     | 4        | 4.17%   |
| XDM     | 1        | 1.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 77       | 80.21%  |
| Unknown | 12       | 12.5%   |
| vi_VN   | 5        | 5.21%   |
| ru_RU   | 1        | 1.04%   |
| C       | 1        | 1.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 54       | 56.25%  |
| BIOS | 42       | 43.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 80       | 82.47%  |
| Overlay | 6        | 6.19%   |
| Btrfs   | 6        | 6.19%   |
| Zfs     | 2        | 2.06%   |
| Unknown | 2        | 2.06%   |
| F2fs    | 1        | 1.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 45       | 46.88%  |
| GPT     | 40       | 41.67%  |
| MBR     | 11       | 11.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 81.25%  |
| Yes       | 18       | 18.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 50       | 51.55%  |
| No        | 47       | 48.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 35       | 36.84%  |
| ASUSTek Computer    | 22       | 23.16%  |
| MSI                 | 10       | 10.53%  |
| Hewlett-Packard     | 8        | 8.42%   |
| Dell                | 6        | 6.32%   |
| Wistron             | 2        | 2.11%   |
| Lenovo              | 2        | 2.11%   |
| Foxconn             | 2        | 2.11%   |
| ASRock              | 2        | 2.11%   |
| Shuttle             | 1        | 1.05%   |
| Koloe               | 1        | 1.05%   |
| Intel               | 1        | 1.05%   |
| Huanan              | 1        | 1.05%   |
| Colorful Technology | 1        | 1.05%   |
| Unknown             | 1        | 1.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Gigabyte H61M-DS2                    | 5        | 5.26%   |
| ASUS All Series                      | 3        | 3.16%   |
| MSI MS-7B89                          | 2        | 2.11%   |
| MSI MS-7823                          | 2        | 2.11%   |
| Gigabyte G41M-ES2L                   | 2        | 2.11%   |
| Gigabyte B450M GAMING                | 2        | 2.11%   |
| Gigabyte B360M-D3H                   | 2        | 2.11%   |
| ASUS P8H61-MX R2.0                   | 2        | 2.11%   |
| ASUS B75M-A                          | 2        | 2.11%   |
| Wistron FMVDD2A0H0                   | 1        | 1.05%   |
| Wistron FMVCEG40Y                    | 1        | 1.05%   |
| Shuttle DS81D                        | 1        | 1.05%   |
| MSI MS-7C89                          | 1        | 1.05%   |
| MSI MS-7C67                          | 1        | 1.05%   |
| MSI MS-7C31                          | 1        | 1.05%   |
| MSI MS-7B98                          | 1        | 1.05%   |
| MSI MS-7A38                          | 1        | 1.05%   |
| MSI MS-7388                          | 1        | 1.05%   |
| Lenovo ThinkCentre M93p 10A8CTO1WW   | 1        | 1.05%   |
| Lenovo ThinkCentre M55e 9389AN1      | 1        | 1.05%   |
| Koloe Thurley                        | 1        | 1.05%   |
| Intel DP55WG AAE57269-407            | 1        | 1.05%   |
| Huanan X79 249PC V2.1                | 1        | 1.05%   |
| HP Z620 Workstation                  | 1        | 1.05%   |
| HP Z440 Workstation                  | 1        | 1.05%   |
| HP Z2 Tower G4 Workstation           | 1        | 1.05%   |
| HP ProDesk 600 G1 SFF                | 1        | 1.05%   |
| HP p2-1221l                          | 1        | 1.05%   |
| HP 510-p042l                         | 1        | 1.05%   |
| HP 500-504x                          | 1        | 1.05%   |
| HP 251-152l                          | 1        | 1.05%   |
| Gigabyte Z97X-UD3H                   | 1        | 1.05%   |
| Gigabyte Z690 AORUS ELITE AX DDR4 V2 | 1        | 1.05%   |
| Gigabyte Z390 UD                     | 1        | 1.05%   |
| Gigabyte Z170-D3H                    | 1        | 1.05%   |
| Gigabyte X570 UD                     | 1        | 1.05%   |
| Gigabyte P110-D3                     | 1        | 1.05%   |
| Gigabyte H81M-DS2                    | 1        | 1.05%   |
| Gigabyte H170M-D3H-CF                | 1        | 1.05%   |
| Gigabyte H170-Gaming 3               | 1        | 1.05%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Gigabyte H61M-DS2  | 5        | 5.26%   |
| ASUS PRIME         | 5        | 5.26%   |
| Dell OptiPlex      | 3        | 3.16%   |
| ASUS ROG           | 3        | 3.16%   |
| ASUS P8H61-MX      | 3        | 3.16%   |
| ASUS All           | 3        | 3.16%   |
| MSI MS-7B89        | 2        | 2.11%   |
| MSI MS-7823        | 2        | 2.11%   |
| Lenovo ThinkCentre | 2        | 2.11%   |
| Gigabyte G41M-ES2L | 2        | 2.11%   |
| Gigabyte B450M     | 2        | 2.11%   |
| Gigabyte B360M-D3H | 2        | 2.11%   |
| ASUS B75M-A        | 2        | 2.11%   |
| Wistron FMVDD2A0H0 | 1        | 1.05%   |
| Wistron FMVCEG40Y  | 1        | 1.05%   |
| Shuttle DS81D      | 1        | 1.05%   |
| MSI MS-7C89        | 1        | 1.05%   |
| MSI MS-7C67        | 1        | 1.05%   |
| MSI MS-7C31        | 1        | 1.05%   |
| MSI MS-7B98        | 1        | 1.05%   |
| MSI MS-7A38        | 1        | 1.05%   |
| MSI MS-7388        | 1        | 1.05%   |
| Koloe Thurley      | 1        | 1.05%   |
| Intel DP55WG       | 1        | 1.05%   |
| Huanan X79         | 1        | 1.05%   |
| HP Z620            | 1        | 1.05%   |
| HP Z440            | 1        | 1.05%   |
| HP Z2              | 1        | 1.05%   |
| HP ProDesk         | 1        | 1.05%   |
| HP p2-1221l        | 1        | 1.05%   |
| HP 510-p042l       | 1        | 1.05%   |
| HP 500-504x        | 1        | 1.05%   |
| HP 251-152l        | 1        | 1.05%   |
| Gigabyte Z97X-UD3H | 1        | 1.05%   |
| Gigabyte Z690      | 1        | 1.05%   |
| Gigabyte Z390      | 1        | 1.05%   |
| Gigabyte Z170-D3H  | 1        | 1.05%   |
| Gigabyte X570      | 1        | 1.05%   |
| Gigabyte P110-D3   | 1        | 1.05%   |
| Gigabyte H81M-DS2  | 1        | 1.05%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 16       | 16.84%  |
| 2014 | 11       | 11.58%  |
| 2012 | 11       | 11.58%  |
| 2013 | 9        | 9.47%   |
| 2019 | 8        | 8.42%   |
| 2010 | 7        | 7.37%   |
| 2020 | 6        | 6.32%   |
| 2017 | 5        | 5.26%   |
| 2015 | 5        | 5.26%   |
| 2016 | 4        | 4.21%   |
| 2009 | 4        | 4.21%   |
| 2022 | 2        | 2.11%   |
| 2021 | 2        | 2.11%   |
| 2011 | 2        | 2.11%   |
| 2008 | 1        | 1.05%   |
| 2007 | 1        | 1.05%   |
| 2006 | 1        | 1.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 95       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 91       | 95.79%  |
| Enabled  | 4        | 4.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 95       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 23       | 23.96%  |
| 8.01-16.0   | 22       | 22.92%  |
| 3.01-4.0    | 14       | 14.58%  |
| 32.01-64.0  | 13       | 13.54%  |
| 4.01-8.0    | 11       | 11.46%  |
| 1.01-2.0    | 7        | 7.29%   |
| 24.01-32.0  | 4        | 4.17%   |
| 64.01-256.0 | 2        | 2.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 30       | 30.93%  |
| 1.01-2.0   | 30       | 30.93%  |
| 3.01-4.0   | 14       | 14.43%  |
| 4.01-8.0   | 12       | 12.37%  |
| 8.01-16.0  | 8        | 8.25%   |
| 16.01-24.0 | 1        | 1.03%   |
| 0.51-1.0   | 1        | 1.03%   |
| 0.01-0.5   | 1        | 1.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 43       | 43.88%  |
| 1      | 31       | 31.63%  |
| 3      | 13       | 13.27%  |
| 4      | 7        | 7.14%   |
| 5      | 2        | 2.04%   |
| 9      | 1        | 1.02%   |
| 0      | 1        | 1.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 78.95%  |
| Yes       | 20       | 21.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 94       | 98.95%  |
| No        | 1        | 1.05%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 53.13%  |
| Yes       | 45       | 46.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 66.67%  |
| Yes       | 32       | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Vietnam | 95       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Ho Chi Minh City | 55       | 57.29%  |
| Hanoi            | 23       | 23.96%  |
| Nga Bay          | 2        | 2.08%   |
| Da Nang          | 2        | 2.08%   |
| Vũng Tàu       | 1        | 1.04%   |
| Vi Thanh         | 1        | 1.04%   |
| Thai Nguyen      | 1        | 1.04%   |
| Tay Ninh         | 1        | 1.04%   |
| Quảng Ngai     | 1        | 1.04%   |
| Nha Trang        | 1        | 1.04%   |
| Nam Định      | 1        | 1.04%   |
| Haiphong         | 1        | 1.04%   |
| Hai Duong        | 1        | 1.04%   |
| Di An            | 1        | 1.04%   |
| Can Tho          | 1        | 1.04%   |
| Bien Hoa         | 1        | 1.04%   |
| Bến Tre        | 1        | 1.04%   |
| Bac Giang        | 1        | 1.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 45       | 58     | 26.63%  |
| Seagate               | 30       | 38     | 17.75%  |
| Samsung Electronics   | 20       | 28     | 11.83%  |
| Kingston              | 12       | 15     | 7.1%    |
| Toshiba               | 8        | 16     | 4.73%   |
| Intel                 | 4        | 4      | 2.37%   |
| Hitachi               | 4        | 5      | 2.37%   |
| Crucial               | 4        | 7      | 2.37%   |
| Unknown               | 3        | 3      | 1.78%   |
| SanDisk               | 3        | 3      | 1.78%   |
| Lexar                 | 3        | 3      | 1.78%   |
| HGST                  | 3        | 3      | 1.78%   |
| Colorful              | 3        | 3      | 1.78%   |
| ZOTAC                 | 2        | 2      | 1.18%   |
| Transcend             | 2        | 2      | 1.18%   |
| TO Exter              | 2        | 3      | 1.18%   |
| OCZ                   | 2        | 2      | 1.18%   |
| Netac                 | 2        | 2      | 1.18%   |
| Gigabyte Technology   | 2        | 2      | 1.18%   |
| Fujitsu               | 2        | 2      | 1.18%   |
| Vaseky                | 1        | 1      | 0.59%   |
| SK hynix              | 1        | 1      | 0.59%   |
| Realtek Semiconductor | 1        | 2      | 0.59%   |
| Phison                | 1        | 2      | 0.59%   |
| Patriot               | 1        | 1      | 0.59%   |
| Mushkin               | 1        | 1      | 0.59%   |
| Micron Technology     | 1        | 1      | 0.59%   |
| Maxtor                | 1        | 1      | 0.59%   |
| Lite-On               | 1        | 1      | 0.59%   |
| KING                  | 1        | 1      | 0.59%   |
| External              | 1        | 1      | 0.59%   |
| EK                    | 1        | 1      | 0.59%   |
| BR                    | 1        | 1      | 0.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 5        | 2.67%   |
| Seagate ST1000DM010-2EP102 1TB                      | 4        | 2.14%   |
| Kingston SA400S37240G 240GB SSD                     | 4        | 2.14%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 3        | 1.6%    |
| WDC WD2500AAKX-00ERMA0 250GB                        | 3        | 1.6%    |
| ZOTAC SATA SSD 120GB                                | 2        | 1.07%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 2        | 1.07%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 2        | 1.07%   |
| WDC WD3200AAKX-001CA0 320GB                         | 2        | 1.07%   |
| Unknown SD/MMC/MS PRO 2GB                           | 2        | 1.07%   |
| Toshiba DT01ABA100V 1TB                             | 2        | 1.07%   |
| TO Exter nal USB 3.0 500GB                          | 2        | 1.07%   |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 1.07%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 1.07%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2        | 1.07%   |
| Seagate ST1000DM003-1ER162 1TB                      | 2        | 1.07%   |
| Samsung SSD 980 1TB                                 | 2        | 1.07%   |
| Samsung SSD 860 EVO 500GB                           | 2        | 1.07%   |
| Samsung SSD 860 EVO 250GB                           | 2        | 1.07%   |
| Samsung SSD 860 EVO 1TB                             | 2        | 1.07%   |
| Samsung SSD 750 EVO 120GB                           | 2        | 1.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2        | 1.07%   |
| Lexar 128GB SSD                                     | 2        | 1.07%   |
| Kingston SKC600256G 256GB SSD                       | 2        | 1.07%   |
| Kingston SA400S37120G 120GB SSD                     | 2        | 1.07%   |
| Hitachi HDT725032VLA380 320GB                       | 2        | 1.07%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD                | 2        | 1.07%   |
| Crucial CT250MX500SSD1 250GB                        | 2        | 1.07%   |
| WDC WDS500G2B0C-00PXH0 500GB                        | 1        | 0.53%   |
| WDC WDS250G3X0C-00SJG0 250GB                        | 1        | 0.53%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 1        | 0.53%   |
| WDC WDS120G1G0A-00SS50 120GB SSD                    | 1        | 0.53%   |
| WDC WDS100T3X0C-00SJG0 1TB                          | 1        | 0.53%   |
| WDC WD80EFBX-68AZZN0 8TB                            | 1        | 0.53%   |
| WDC WD80 03FFBX-68B9AN0 8TB                         | 1        | 0.53%   |
| WDC WD60PURX-64T0ZY0 6TB                            | 1        | 0.53%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1        | 0.53%   |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1        | 0.53%   |
| WDC WD5000AZLX-75K2TA0 500GB                        | 1        | 0.53%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 34       | 42     | 41.46%  |
| Seagate | 30       | 37     | 36.59%  |
| Toshiba | 7        | 13     | 8.54%   |
| Hitachi | 4        | 5      | 4.88%   |
| HGST    | 3        | 3      | 3.66%   |
| Unknown | 2        | 2      | 2.44%   |
| Fujitsu | 2        | 2      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 12       | 17     | 17.14%  |
| Kingston            | 12       | 15     | 17.14%  |
| WDC                 | 11       | 11     | 15.71%  |
| Intel               | 4        | 4      | 5.71%   |
| Crucial             | 4        | 5      | 5.71%   |
| SanDisk             | 3        | 3      | 4.29%   |
| Lexar               | 3        | 3      | 4.29%   |
| Colorful            | 3        | 3      | 4.29%   |
| ZOTAC               | 2        | 2      | 2.86%   |
| Transcend           | 2        | 2      | 2.86%   |
| TO Exter            | 2        | 3      | 2.86%   |
| Netac               | 2        | 2      | 2.86%   |
| Gigabyte Technology | 2        | 2      | 2.86%   |
| Vaseky              | 1        | 1      | 1.43%   |
| Toshiba             | 1        | 1      | 1.43%   |
| SK hynix            | 1        | 1      | 1.43%   |
| Patriot             | 1        | 1      | 1.43%   |
| OCZ                 | 1        | 1      | 1.43%   |
| Micron Technology   | 1        | 1      | 1.43%   |
| Maxtor              | 1        | 1      | 1.43%   |
| EK                  | 1        | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 66       | 104    | 44%     |
| SSD     | 59       | 80     | 39.33%  |
| NVMe    | 21       | 28     | 14%     |
| Unknown | 4        | 4      | 2.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 85       | 179    | 75.89%  |
| NVMe | 20       | 27     | 17.86%  |
| SAS  | 7        | 10     | 6.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 76       | 119    | 63.33%  |
| 0.51-1.0   | 28       | 39     | 23.33%  |
| 1.01-2.0   | 8        | 11     | 6.67%   |
| 4.01-10.0  | 5        | 12     | 4.17%   |
| 3.01-4.0   | 2        | 2      | 1.67%   |
| 2.01-3.0   | 1        | 1      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 34       | 34%     |
| 501-1000       | 17       | 17%     |
| 251-500        | 14       | 14%     |
| 1001-2000      | 8        | 8%      |
| 51-100         | 6        | 6%      |
| More than 3000 | 5        | 5%      |
| 1-20           | 5        | 5%      |
| 21-50          | 4        | 4%      |
| Unknown        | 4        | 4%      |
| 2001-3000      | 3        | 3%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 37       | 37.37%  |
| 21-50          | 13       | 13.13%  |
| 51-100         | 13       | 13.13%  |
| 251-500        | 10       | 10.1%   |
| 101-250        | 8        | 8.08%   |
| 501-1000       | 7        | 7.07%   |
| Unknown        | 4        | 4.04%   |
| More than 3000 | 3        | 3.03%   |
| 2001-3000      | 2        | 2.02%   |
| 1001-2000      | 2        | 2.02%   |

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
| Works    | 48       | 106    | 44.44%  |
| Detected | 47       | 94     | 43.52%  |
| Malfunc  | 12       | 15     | 11.11%  |
| Failed   | 1        | 1      | 0.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 79       | 64.23%  |
| AMD                          | 16       | 13.01%  |
| Samsung Electronics          | 10       | 8.13%   |
| SanDisk                      | 5        | 4.07%   |
| ASMedia Technology           | 3        | 2.44%   |
| Toshiba America Info Systems | 1        | 0.81%   |
| Silicon Motion               | 1        | 0.81%   |
| Realtek Semiconductor        | 1        | 0.81%   |
| Phison Electronics           | 1        | 0.81%   |
| OCZ Technology Group         | 1        | 0.81%   |
| Micron/Crucial Technology    | 1        | 0.81%   |
| Marvell Technology Group     | 1        | 0.81%   |
| LSI Logic / Symbios Logic    | 1        | 0.81%   |
| Lite-On Technology           | 1        | 0.81%   |
| JMicron Technology           | 1        | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 8.72%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 8.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 6.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 5.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 4.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 4.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 3.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 3.36%   |
| Samsung NVMe SSD Controller 980                                                         | 4        | 2.68%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 2.01%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 2.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.01%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.34%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.34%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.34%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.34%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.34%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.34%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.34%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.34%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.34%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.67%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.67%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.67%   |
| Phison NVMe Storage Controller                                                          | 1        | 0.67%   |
| OCZ Group RD400/400A SSD                                                                | 1        | 0.67%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.67%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.67%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                                    | 1        | 0.67%   |
| Lite-On Non-Volatile memory controller                                                  | 1        | 0.67%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.67%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 76       | 63.33%  |
| NVMe | 20       | 16.67%  |
| IDE  | 19       | 15.83%  |
| RAID | 4        | 3.33%   |
| SAS  | 1        | 0.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 79       | 83.16%  |
| AMD    | 16       | 16.84%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 4.21%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 4.21%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 3.16%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 3.16%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 2.11%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 2.11%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 2.11%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 2.11%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 2.11%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 2.11%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 2.11%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 2        | 2.11%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 2.11%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 2.11%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 2.11%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 1.05%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1        | 1.05%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1        | 1.05%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz          | 1        | 1.05%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 1.05%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 1.05%   |
| Intel Xeon CPU E31235 @ 3.20GHz             | 1        | 1.05%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1        | 1.05%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 1.05%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.05%   |
| Intel Pentium CPU G640T @ 2.40GHz           | 1        | 1.05%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 1.05%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.05%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 1.05%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 1.05%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 1.05%   |
| Intel Core i7-7700T CPU @ 2.90GHz           | 1        | 1.05%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.05%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.05%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 1        | 1.05%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.05%   |
| Intel Core i5-9500 CPU @ 3.00GHz            | 1        | 1.05%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.05%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.05%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1.05%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 28       | 29.47%  |
| Intel Core i3           | 15       | 15.79%  |
| Intel Core i7           | 10       | 10.53%  |
| Intel Xeon              | 8        | 8.42%   |
| Intel Core 2 Duo        | 7        | 7.37%   |
| AMD Ryzen 5             | 7        | 7.37%   |
| Other                   | 3        | 3.16%   |
| Intel Pentium           | 3        | 3.16%   |
| Intel Celeron           | 2        | 2.11%   |
| AMD Ryzen 9             | 2        | 2.11%   |
| AMD A10                 | 2        | 2.11%   |
| Intel Pentium Dual-Core | 1        | 1.05%   |
| Intel Pentium Dual      | 1        | 1.05%   |
| Intel Core i9           | 1        | 1.05%   |
| AMD Ryzen 7 PRO         | 1        | 1.05%   |
| AMD Ryzen 3             | 1        | 1.05%   |
| AMD Phenom II X4        | 1        | 1.05%   |
| AMD Athlon II X2        | 1        | 1.05%   |
| AMD A8                  | 1        | 1.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 39       | 40.63%  |
| 2      | 28       | 29.17%  |
| 6      | 18       | 18.75%  |
| 8      | 5        | 5.21%   |
| 16     | 3        | 3.13%   |
| 28     | 1        | 1.04%   |
| 24     | 1        | 1.04%   |
| 12     | 1        | 1.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 93       | 96.88%  |
| 2      | 3        | 3.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 51.58%  |
| 2      | 46       | 48.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 94       | 98.95%  |
| Unknown        | 1        | 1.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 17.89%  |
| 0x306c3    | 10       | 10.53%  |
| 0x306a9    | 7        | 7.37%   |
| 0x1067a    | 7        | 7.37%   |
| 0x906ea    | 6        | 6.32%   |
| 0x206a7    | 6        | 6.32%   |
| 0x906eb    | 3        | 3.16%   |
| 0x906e9    | 3        | 3.16%   |
| 0x506e3    | 3        | 3.16%   |
| 0x206d7    | 3        | 3.16%   |
| 0xa0653    | 2        | 2.11%   |
| 0x906ed    | 2        | 2.11%   |
| 0x90672    | 2        | 2.11%   |
| 0x30678    | 2        | 2.11%   |
| 0x20655    | 2        | 2.11%   |
| 0x08701021 | 2        | 2.11%   |
| 0x06003106 | 2        | 2.11%   |
| 0x90675    | 1        | 1.05%   |
| 0x6fd      | 1        | 1.05%   |
| 0x406f1    | 1        | 1.05%   |
| 0x306f2    | 1        | 1.05%   |
| 0x106a5    | 1        | 1.05%   |
| 0x10676    | 1        | 1.05%   |
| 0x0a50000d | 1        | 1.05%   |
| 0x0a20120a | 1        | 1.05%   |
| 0x0a201016 | 1        | 1.05%   |
| 0x08701013 | 1        | 1.05%   |
| 0x08108109 | 1        | 1.05%   |
| 0x0810100b | 1        | 1.05%   |
| 0x0800820d | 1        | 1.05%   |
| 0x06001119 | 1        | 1.05%   |
| 0x010000db | 1        | 1.05%   |
| 0x010000c7 | 1        | 1.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 17       | 17.89%  |
| Haswell          | 17       | 17.89%  |
| SandyBridge      | 9        | 9.47%   |
| IvyBridge        | 9        | 9.47%   |
| Penryn           | 8        | 8.42%   |
| Skylake          | 6        | 6.32%   |
| Zen 2            | 4        | 4.21%   |
| Zen+             | 3        | 3.16%   |
| Zen 3            | 3        | 3.16%   |
| Westmere         | 3        | 3.16%   |
| Alderlake Hybrid | 3        | 3.16%   |
| Steamroller      | 2        | 2.11%   |
| Silvermont       | 2        | 2.11%   |
| K10              | 2        | 2.11%   |
| CometLake        | 2        | 2.11%   |
| Zen              | 1        | 1.05%   |
| Piledriver       | 1        | 1.05%   |
| Nehalem          | 1        | 1.05%   |
| Core             | 1        | 1.05%   |
| Broadwell        | 1        | 1.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 46       | 42.99%  |
| Intel             | 37       | 34.58%  |
| AMD               | 23       | 21.5%   |
| ASPEED Technology | 1        | 0.93%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 7.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 7.27%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 5.45%   |
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 5.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 3.64%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 2.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 2.73%   |
| Intel HD Graphics 530                                                       | 3        | 2.73%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 2.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.73%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.82%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.82%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.82%   |
| Intel HD Graphics 630                                                       | 2        | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 1.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.82%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.82%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.82%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.91%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.91%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.91%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.91%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.91%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.91%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.91%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB Rev. 2]                                  | 1        | 0.91%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1        | 0.91%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.91%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.91%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 0.91%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 0.91%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.91%   |
| Nvidia GK208 [GeForce GT 710]                                               | 1        | 0.91%   |
| Nvidia GK107GL [Quadro K420]                                                | 1        | 0.91%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.91%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.91%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 0.91%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.91%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 38       | 39.58%  |
| 1 x Intel       | 27       | 28.13%  |
| 1 x AMD         | 23       | 23.96%  |
| Intel + Nvidia  | 7        | 7.29%   |
| Nvidia + ASPEED | 1        | 1.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 61       | 62.89%  |
| Proprietary | 35       | 36.08%  |
| Unknown     | 1        | 1.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 36.46%  |
| 1.01-2.0   | 17       | 17.71%  |
| 3.01-4.0   | 14       | 14.58%  |
| 7.01-8.0   | 6        | 6.25%   |
| 5.01-6.0   | 6        | 6.25%   |
| 8.01-16.0  | 6        | 6.25%   |
| 0.51-1.0   | 6        | 6.25%   |
| 0.01-0.5   | 6        | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 28       | 30.11%  |
| Samsung Electronics  | 16       | 17.2%   |
| Goldstar             | 10       | 10.75%  |
| Hewlett-Packard      | 4        | 4.3%    |
| AOC                  | 4        | 4.3%    |
| Ancor Communications | 4        | 4.3%    |
| ViewSonic            | 3        | 3.23%   |
| Panasonic            | 3        | 3.23%   |
| Gigabyte Technology  | 2        | 2.15%   |
| BenQ                 | 2        | 2.15%   |
| ASUSTek Computer     | 2        | 2.15%   |
| Unknown              | 2        | 2.15%   |
| Unknown (ADA)        | 1        | 1.08%   |
| Sony                 | 1        | 1.08%   |
| Philips              | 1        | 1.08%   |
| NEC Computers        | 1        | 1.08%   |
| Mi                   | 1        | 1.08%   |
| LG Electronics       | 1        | 1.08%   |
| Lenovo Group Limited | 1        | 1.08%   |
| Lenovo               | 1        | 1.08%   |
| HPN                  | 1        | 1.08%   |
| HOP                  | 1        | 1.08%   |
| CGC                  | 1        | 1.08%   |
| AUS                  | 1        | 1.08%   |
| Acer                 | 1        | 1.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Panasonic TV MEIC33B 1366x768 521x293mm 23.5-inch                     | 3        | 3.09%   |
| Samsung Electronics SME1720NR SAM0696 1280x1024 338x270mm 17.0-inch   | 2        | 2.06%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 2.06%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 2        | 2.06%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 2        | 2.06%   |
| Unknown                                                               | 2        | 2.06%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 477x268mm 21.5-inch            | 1        | 1.03%   |
| ViewSonic VA2201-FHD VSC683B 1920x1080 480x260mm 21.5-inch            | 1        | 1.03%   |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                             | 1        | 1.03%   |
| Unknown (ADA) LCD Monitor ADA0004 1024x600 150x100mm 7.1-inch         | 1        | 1.03%   |
| Sony TV SNY8E03 1920x1080                                             | 1        | 1.03%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 1        | 1.03%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 1.03%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch     | 1        | 1.03%   |
| Samsung Electronics S20D300 SAM0B39 1600x900 432x240mm 19.5-inch      | 1        | 1.03%   |
| Samsung Electronics S20B370 SAM08B7 1600x900 443x249mm 20.0-inch      | 1        | 1.03%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch      | 1        | 1.03%   |
| Samsung Electronics S19C170 SAM0B02 1366x768 410x230mm 18.5-inch      | 1        | 1.03%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1        | 1.03%   |
| Samsung Electronics LCD Monitor SME1720NR 1280x1024                   | 1        | 1.03%   |
| Samsung Electronics LCD Monitor SMB1930N                              | 1        | 1.03%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 950x540mm 43.0-inch | 1        | 1.03%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 950x540mm 43.0-inch | 1        | 1.03%   |
| Samsung Electronics LCD Monitor SAM0658 1920x1080 886x498mm 40.0-inch | 1        | 1.03%   |
| Philips 24PHT4003S/74 PHT4003 1360x768 525x297mm 23.7-inch            | 1        | 1.03%   |
| NEC Computers LCD172VXM NEC67C5 1280x1024 338x270mm 17.0-inch         | 1        | 1.03%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 1        | 1.03%   |
| LG Electronics LCD Monitor MP59G                                      | 1        | 1.03%   |
| Lenovo LEN L1900pA LEN114F 1280x1024 376x301mm 19.0-inch              | 1        | 1.03%   |
| Lenovo Group Limited LCD Monitor LEN L1900pA 1280x1024                | 1        | 1.03%   |
| HPN LCD Monitor HP Z23n G2 1920x1080                                  | 1        | 1.03%   |
| HOP DVI HOP2700 1920x1080 597x336mm 27.0-inch                         | 1        | 1.03%   |
| Hewlett-Packard w1707 HWP2800 1440x900 370x230mm 17.2-inch            | 1        | 1.03%   |
| Hewlett-Packard N220 HPN3408 1920x1080 476x268mm 21.5-inch            | 1        | 1.03%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 1        | 1.03%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch           | 1        | 1.03%   |
| Goldstar W2043 GSM4E9E 1600x900 443x249mm 20.0-inch                   | 1        | 1.03%   |
| Goldstar MP59G GSM5B33 1920x1080 480x270mm 21.7-inch                  | 1        | 1.03%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 1.03%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                | 1        | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 44       | 47.31%  |
| 3840x2160 (4K)    | 9        | 9.68%   |
| 1366x768 (WXGA)   | 8        | 8.6%    |
| 1280x1024 (SXGA)  | 8        | 8.6%    |
| 2560x1440 (QHD)   | 7        | 7.53%   |
| 1600x900 (HD+)    | 6        | 6.45%   |
| Unknown           | 3        | 3.23%   |
| 1440x900 (WXGA+)  | 2        | 2.15%   |
| 3840x1080         | 1        | 1.08%   |
| 3440x1440         | 1        | 1.08%   |
| 3286x1080         | 1        | 1.08%   |
| 1920x1200 (WUXGA) | 1        | 1.08%   |
| 1360x768          | 1        | 1.08%   |
| 1280x800 (WXGA)   | 1        | 1.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 15       | 16.13%  |
| Unknown | 14       | 15.05%  |
| 27      | 13       | 13.98%  |
| 21      | 13       | 13.98%  |
| 24      | 12       | 12.9%   |
| 20      | 5        | 5.38%   |
| 18      | 5        | 5.38%   |
| 17      | 5        | 5.38%   |
| 19      | 4        | 4.3%    |
| 84      | 2        | 2.15%   |
| 42      | 1        | 1.08%   |
| 40      | 1        | 1.08%   |
| 34      | 1        | 1.08%   |
| 25      | 1        | 1.08%   |
| 7       | 1        | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 39       | 42.39%  |
| 401-500     | 25       | 27.17%  |
| Unknown     | 14       | 15.22%  |
| 301-350     | 4        | 4.35%   |
| 351-400     | 3        | 3.26%   |
| 1501-2000   | 2        | 2.17%   |
| 801-900     | 1        | 1.09%   |
| 701-800     | 1        | 1.09%   |
| 601-700     | 1        | 1.09%   |
| 101-200     | 1        | 1.09%   |
| 901-1000    | 1        | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 66       | 74.16%  |
| Unknown | 13       | 14.61%  |
| 5/4     | 6        | 6.74%   |
| 16/10   | 2        | 2.25%   |
| 3/2     | 1        | 1.12%   |
| 21/9    | 1        | 1.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 36       | 39.13%  |
| Unknown        | 14       | 15.22%  |
| 301-350        | 13       | 14.13%  |
| 151-200        | 12       | 13.04%  |
| 141-150        | 9        | 9.78%   |
| More than 1000 | 2        | 2.17%   |
| 501-1000       | 2        | 2.17%   |
| 351-500        | 1        | 1.09%   |
| 1-40           | 1        | 1.09%   |
| 251-300        | 1        | 1.09%   |
| 131-140        | 1        | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 52       | 57.14%  |
| 101-120 | 19       | 20.88%  |
| Unknown | 14       | 15.38%  |
| 161-240 | 4        | 4.4%    |
| 121-160 | 2        | 2.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 81       | 85.26%  |
| 2     | 8        | 8.42%   |
| 0     | 6        | 6.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 62       | 44.29%  |
| Intel                 | 34       | 24.29%  |
| Ralink Technology     | 9        | 6.43%   |
| Qualcomm Atheros      | 9        | 6.43%   |
| Broadcom              | 8        | 5.71%   |
| TP-Link               | 5        | 3.57%   |
| ASIX Electronics      | 4        | 2.86%   |
| Ralink                | 2        | 1.43%   |
| D-Link                | 2        | 1.43%   |
| Samsung Electronics   | 1        | 0.71%   |
| MediaTek              | 1        | 0.71%   |
| ICS Advent            | 1        | 0.71%   |
| Edimax Technology     | 1        | 0.71%   |
| Aquantia              | 1        | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52       | 33.33%  |
| Intel Ethernet Connection (7) I219-V                              | 6        | 3.85%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 3.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 2.56%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 2.56%   |
| Intel I210 Gigabit Network Connection                             | 3        | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.92%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.92%   |
| ASIX AX88772A Fast Ethernet                                       | 3        | 1.92%   |
| TP-Link 802.11ac NIC                                              | 2        | 1.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 1.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.28%   |
| Realtek 802.11ac NIC                                              | 2        | 1.28%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 1.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.28%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 1.28%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.28%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.28%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.28%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.28%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2        | 1.28%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2        | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2        | 1.28%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.64%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.64%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.64%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.64%   |
| Ralink RT2070 Wireless Adapter                                    | 1        | 0.64%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1        | 0.64%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.64%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 1        | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 23.4%   |
| Ralink Technology     | 9        | 19.15%  |
| Intel                 | 9        | 19.15%  |
| TP-Link               | 5        | 10.64%  |
| Qualcomm Atheros      | 4        | 8.51%   |
| Broadcom              | 4        | 8.51%   |
| Ralink                | 2        | 4.26%   |
| D-Link                | 2        | 4.26%   |
| Edimax Technology     | 1        | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 5        | 10.64%  |
| Ralink MT7601U Wireless Adapter                                | 4        | 8.51%   |
| TP-Link 802.11ac NIC                                           | 2        | 4.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2        | 4.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 4.26%   |
| Realtek 802.11ac NIC                                           | 2        | 4.26%   |
| Ralink RT5370 Wireless Adapter                                 | 2        | 4.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 4.26%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2        | 4.26%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2        | 4.26%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 2.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1        | 2.13%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 2.13%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 2.13%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 2.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 2.13%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 2.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 2.13%   |
| Ralink RT2070 Wireless Adapter                                 | 1        | 2.13%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1        | 2.13%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1        | 2.13%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 1        | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 2.13%   |
| Intel Wireless 7265                                            | 1        | 2.13%   |
| Intel Wireless 3165                                            | 1        | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 2.13%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 2.13%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 2.13%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter             | 1        | 2.13%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1        | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 59       | 56.19%  |
| Intel                 | 29       | 27.62%  |
| Qualcomm Atheros      | 5        | 4.76%   |
| Broadcom              | 4        | 3.81%   |
| ASIX Electronics      | 4        | 3.81%   |
| Samsung Electronics   | 1        | 0.95%   |
| MediaTek              | 1        | 0.95%   |
| ICS Advent            | 1        | 0.95%   |
| Aquantia              | 1        | 0.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52       | 47.71%  |
| Intel Ethernet Connection (7) I219-V                              | 6        | 5.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 3.67%   |
| Intel I210 Gigabit Network Connection                             | 3        | 2.75%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.75%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.75%   |
| ASIX AX88772A Fast Ethernet                                       | 3        | 2.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 1.83%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.83%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.83%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.83%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.83%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2        | 1.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.92%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.92%   |
| MediaTek TECNO CAMON 18P                                          | 1        | 0.92%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.92%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.92%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.92%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.92%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 0.92%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 0.92%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.92%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.92%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1        | 0.92%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1        | 0.92%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.92%   |
| Aquantia Ethernet controller                                      | 1        | 0.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 68.12%  |
| WiFi     | 44       | 31.88%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 68       | 68.69%  |
| WiFi     | 31       | 31.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 67       | 69.79%  |
| 2     | 22       | 22.92%  |
| 3     | 6        | 6.25%   |
| 0     | 1        | 1.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 73       | 76.04%  |
| Yes  | 23       | 23.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 14       | 43.75%  |
| Intel                           | 9        | 28.13%  |
| Realtek Semiconductor           | 3        | 9.38%   |
| Qualcomm Atheros Communications | 2        | 6.25%   |
| Broadcom                        | 2        | 6.25%   |
| Conwise Technology              | 1        | 3.13%   |
| Apple                           | 1        | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14       | 43.75%  |
| Intel AX200 Bluetooth                               | 5        | 15.63%  |
| Realtek Bluetooth Radio                             | 3        | 9.38%   |
| Intel Bluetooth wireless interface                  | 2        | 6.25%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 3.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 3.13%   |
| Intel Bluetooth Device                              | 1        | 3.13%   |
| Intel AX210 Bluetooth                               | 1        | 3.13%   |
| Conwise CW6622                                      | 1        | 3.13%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1        | 3.13%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1        | 3.13%   |
| Apple Bluetooth Host Controller                     | 1        | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 78       | 46.99%  |
| Nvidia                    | 45       | 27.11%  |
| AMD                       | 27       | 16.27%  |
| C-Media Electronics       | 4        | 2.41%   |
| Creative Labs             | 2        | 1.2%    |
| Shenzhen Rapoo Technology | 1        | 0.6%    |
| Nordic Semiconductor ASA  | 1        | 0.6%    |
| Logitech                  | 1        | 0.6%    |
| JMTek                     | 1        | 0.6%    |
| GYROCOM C&C               | 1        | 0.6%    |
| Generalplus Technology    | 1        | 0.6%    |
| Elgato Systems            | 1        | 0.6%    |
| Creative Technology       | 1        | 0.6%    |
| Apple                     | 1        | 0.6%    |
| AGPTek                    | 1        | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 6.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 5.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 5.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 4.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 4.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 4.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8        | 4.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 3.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 3.21%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 2.67%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 2.67%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 2.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 2.14%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 2.14%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.6%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1.6%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 1.6%    |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.6%    |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.07%   |
| Nvidia TU102 High Definition Audio Controller                              | 2        | 1.07%   |
| Nvidia High Definition Audio Controller                                    | 2        | 1.07%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 1.07%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.07%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.07%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.07%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 1.07%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 1.07%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.07%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.07%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.07%   |
| Shenzhen Rapoo Technology Rapoo Gaming Headset                             | 1        | 0.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Kingston              | 14       | 22.22%  |
| Corsair               | 13       | 20.63%  |
| G.Skill               | 7        | 11.11%  |
| Unknown               | 6        | 9.52%   |
| Samsung Electronics   | 5        | 7.94%   |
| SK hynix              | 4        | 6.35%   |
| Kingmax               | 4        | 6.35%   |
| Crucial               | 3        | 4.76%   |
| A-DATA Technology     | 2        | 3.17%   |
| Team                  | 1        | 1.59%   |
| Ramaxel Technology    | 1        | 1.59%   |
| Patriot               | 1        | 1.59%   |
| Micron Technology     | 1        | 1.59%   |
| Kingmax Semiconductor | 1        | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s       | 4        | 5.8%    |
| Unknown RAM Module 1GB DIMM 800MT/s                        | 2        | 2.9%    |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s     | 2        | 2.9%    |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s               | 1        | 1.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 200MT/s                | 1        | 1.45%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                 | 1        | 1.45%   |
| Unknown RAM BAPC08G3000D4T8 8192MB DIMM DDR4 2133MT/s      | 1        | 1.45%   |
| Team RAM TEAMGROUP-UD3-160 4096MB DIMM DDR3 1333MT/s       | 1        | 1.45%   |
| SK hynix RAM SNOAMOO Ltd:016M00 4096MB DIMM DDR3 1600MT/s  | 1        | 1.45%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s        | 1        | 1.45%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s       | 1        | 1.45%   |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB DIMM DDR3 1600MT/s    | 1        | 1.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1        | 1.45%   |
| Samsung RAM M393B2K70CM0-YF8 16GB DIMM DDR3 1067MT/s       | 1        | 1.45%   |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1866MT/s           | 1        | 1.45%   |
| Samsung RAM M393A2K40BB1-CRC 16GB DIMM DDR4 2400MT/s       | 1        | 1.45%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s        | 1        | 1.45%   |
| Ramaxel RAM RMR5040MM58F9F1600 4096MB DIMM DDR3 1600MT/s   | 1        | 1.45%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s             | 1        | 1.45%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 1        | 1.45%   |
| Kingston RAM Module 8GB DIMM DDR4 2667MT/s                 | 1        | 1.45%   |
| Kingston RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 1.45%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 1.45%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s       | 1        | 1.45%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 1        | 1.45%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s          | 1        | 1.45%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3                 | 1        | 1.45%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s      | 1        | 1.45%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s      | 1        | 1.45%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s      | 1        | 1.45%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 1.45%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 1.45%   |
| Kingston RAM 9965525-139.A00LF 8192MB DIMM DDR3 1600MT/s   | 1        | 1.45%   |
| Kingston RAM 9965413-002.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 1.45%   |
| Kingston RAM 9905712-008.A00G 16GB SODIMM DDR4 2400MT/s    | 1        | 1.45%   |
| Kingmax RAM GZNH23F-18--------- 16GB DIMM DDR4 2666MT/s    | 1        | 1.45%   |
| Kingmax RAM GLAH22F-18--------- 16384MB DIMM DDR4 2666MT/s | 1        | 1.45%   |
| Kingmax RAM FLGF65F-D8KM 4GB DIMM DDR3 1333MT/s            | 1        | 1.45%   |
| Kingmax RAM FLGE85F-B8KLB 2GB DIMM DDR3 1067MT/s           | 1        | 1.45%   |
| Kingmax RAM FLFF65F-D8KL9 4GB DIMM DDR3 1066MT/s           | 1        | 1.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 31       | 54.39%  |
| DDR3    | 21       | 36.84%  |
| DDR2    | 2        | 3.51%   |
| Unknown | 2        | 3.51%   |
| DDR     | 1        | 1.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 55       | 96.49%  |
| SODIMM | 2        | 3.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 26       | 43.33%  |
| 4096  | 14       | 23.33%  |
| 16384 | 13       | 21.67%  |
| 1024  | 4        | 6.67%   |
| 2048  | 3        | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 13       | 19.4%   |
| 3200  | 7        | 10.45%  |
| 3000  | 7        | 10.45%  |
| 2400  | 7        | 10.45%  |
| 1333  | 6        | 8.96%   |
| 2667  | 3        | 4.48%   |
| 800   | 3        | 4.48%   |
| 3600  | 2        | 2.99%   |
| 2800  | 2        | 2.99%   |
| 2666  | 2        | 2.99%   |
| 1866  | 2        | 2.99%   |
| 1067  | 2        | 2.99%   |
| 3666  | 1        | 1.49%   |
| 3466  | 1        | 1.49%   |
| 3400  | 1        | 1.49%   |
| 3334  | 1        | 1.49%   |
| 3007  | 1        | 1.49%   |
| 2133  | 1        | 1.49%   |
| 1867  | 1        | 1.49%   |
| 1648  | 1        | 1.49%   |
| 1066  | 1        | 1.49%   |
| 200   | 1        | 1.49%   |
| 133   | 1        | 1.49%   |

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
| Logitech                        | 5        | 50%     |
| Samsung Electronics             | 1        | 10%     |
| Microdia                        | 1        | 10%     |
| KYE Systems (Mouse Systems)     | 1        | 10%     |
| Intel                           | 1        | 10%     |
| IDS Imaging Development Systems | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 3        | 30%     |
| Samsung Galaxy A5 (MTP)                         | 1        | 10%     |
| Microdia Rapoo Camera                           | 1        | 10%     |
| Logitech Webcam C310                            | 1        | 10%     |
| Logitech Webcam C210                            | 1        | 10%     |
| KYE Systems (Mouse Systems) JOYACCESS JA-Webcam | 1        | 10%     |
| Intel RealSense Depth Camera 435                | 1        | 10%     |
| IDS Imaging Development Systems USB 3.0 Camera  | 1        | 10%     |

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
| 0     | 84       | 88.42%  |
| 1     | 10       | 10.53%  |
| 2     | 1        | 1.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 41.67%  |
| Unassigned class         | 3        | 25%     |
| Net/wireless             | 3        | 25%     |
| Communication controller | 1        | 8.33%   |

