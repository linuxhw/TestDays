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

Total: 119

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| HP            | 158A                     | [428326af76](https://linux-hardware.org/?probe=428326af76) | Sep 21, 2022 |
| Gigabyte      | X570 UD                  | [7e840fc9d0](https://linux-hardware.org/?probe=7e840fc9d0) | Sep 12, 2022 |
| Dell          | 0VNM11 A00               | [9ae0ae5ac4](https://linux-hardware.org/?probe=9ae0ae5ac4) | Sep 10, 2022 |
| Gigabyte      | H110M-DS2-CF             | [ecc2f4c975](https://linux-hardware.org/?probe=ecc2f4c975) | Sep 06, 2022 |
| MSI           | H410M PRO                | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| HP            | 18E7                     | [9344f12eea](https://linux-hardware.org/?probe=9344f12eea) | Aug 31, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO  | [46c6096b6e](https://linux-hardware.org/?probe=46c6096b6e) | Aug 23, 2022 |
| Gigabyte      | B450M GAMING             | [a3d9fca7aa](https://linux-hardware.org/?probe=a3d9fca7aa) | Aug 16, 2022 |
| HP            | 2AE2                     | [1fd0bb70dc](https://linux-hardware.org/?probe=1fd0bb70dc) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING  | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| HP            | 8455                     | [62b146bca0](https://linux-hardware.org/?probe=62b146bca0) | Jul 08, 2022 |
| Gigabyte      | H61M-DS2                 | [09ba129a3b](https://linux-hardware.org/?probe=09ba129a3b) | May 25, 2022 |
| Foxconn       | H61MD/H61MD-V            | [25b52955ee](https://linux-hardware.org/?probe=25b52955ee) | Apr 29, 2022 |
| Foxconn       | H61MD/H61MD-V            | [7bb124e322](https://linux-hardware.org/?probe=7bb124e322) | Apr 06, 2022 |
| Wistron       | JIG31B3                  | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| Foxconn       | 2ADA                     | [64f5921b5b](https://linux-hardware.org/?probe=64f5921b5b) | Feb 13, 2022 |
| Gigabyte      | B85M-DS3H                | [be7876abf4](https://linux-hardware.org/?probe=be7876abf4) | Jan 05, 2022 |
| Gigabyte      | B75M-D3H                 | [1524f751eb](https://linux-hardware.org/?probe=1524f751eb) | Dec 24, 2021 |
| ASUSTek       | P8H61-MX                 | [cee5f081e3](https://linux-hardware.org/?probe=cee5f081e3) | Dec 19, 2021 |
| ASUSTek       | P8H61-MX                 | [297d964b96](https://linux-hardware.org/?probe=297d964b96) | Dec 18, 2021 |
| MSI           | MAG B365M MORTAR         | [bd72de2067](https://linux-hardware.org/?probe=bd72de2067) | Dec 12, 2021 |
| ASUSTek       | H81M-K                   | [412accf186](https://linux-hardware.org/?probe=412accf186) | Dec 09, 2021 |
| ASUSTek       | PRIME Z370-P             | [fa62ac7a45](https://linux-hardware.org/?probe=fa62ac7a45) | Nov 23, 2021 |
| ASUSTek       | P8H61-MX R2.0            | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| MSI           | B450M MORTAR MAX         | [84c316ee57](https://linux-hardware.org/?probe=84c316ee57) | Nov 08, 2021 |
| Gigabyte      | H61M-DS2                 | [042607d7f1](https://linux-hardware.org/?probe=042607d7f1) | Oct 31, 2021 |
| Gigabyte      | H61M-DS2                 | [11527ae3f9](https://linux-hardware.org/?probe=11527ae3f9) | Oct 31, 2021 |
| Gigabyte      | G31MF-S2                 | [370ad865cf](https://linux-hardware.org/?probe=370ad865cf) | Oct 31, 2021 |
| Gigabyte      | B450M GAMING             | [f316c0a82e](https://linux-hardware.org/?probe=f316c0a82e) | Oct 25, 2021 |
| Gigabyte      | EP43T-S3L                | [8a1adefcb3](https://linux-hardware.org/?probe=8a1adefcb3) | Oct 20, 2021 |
| Gigabyte      | G31MF-S2                 | [7459a9ed47](https://linux-hardware.org/?probe=7459a9ed47) | Oct 18, 2021 |
| ASUSTek       | PRIME X370-PRO           | [8b3b2655bb](https://linux-hardware.org/?probe=8b3b2655bb) | Oct 03, 2021 |
| Gigabyte      | G1.Sniper B5-CF          | [886b00678b](https://linux-hardware.org/?probe=886b00678b) | Aug 09, 2021 |
| ASUSTek       | PRIME B250M-K            | [10c0149671](https://linux-hardware.org/?probe=10c0149671) | Jul 17, 2021 |
| Gigabyte      | H61M-DS2                 | [894db66628](https://linux-hardware.org/?probe=894db66628) | Jul 05, 2021 |
| Gigabyte      | P110-D3-CF               | [37aab1ae76](https://linux-hardware.org/?probe=37aab1ae76) | Jun 29, 2021 |
| Colorful T... | C.A68M-BTC YV14          | [9b6c7d9e82](https://linux-hardware.org/?probe=9b6c7d9e82) | Jun 23, 2021 |
| Huanan        | X79 249PC V2.1           | [b6fd95e48e](https://linux-hardware.org/?probe=b6fd95e48e) | Jun 15, 2021 |
| MSI           | B365M PRO-VH             | [ea30bb632e](https://linux-hardware.org/?probe=ea30bb632e) | Jun 10, 2021 |
| Gigabyte      | Z170-D3H-CF              | [428cb5bb99](https://linux-hardware.org/?probe=428cb5bb99) | Jun 05, 2021 |
| Gigabyte      | Z170-D3H-CF              | [38acf36fce](https://linux-hardware.org/?probe=38acf36fce) | Jun 05, 2021 |
| ASUSTek       | P7H55-M LX               | [4401c591ee](https://linux-hardware.org/?probe=4401c591ee) | Jun 01, 2021 |
| ASUSTek       | P7H55-M LX               | [f1d33c68f6](https://linux-hardware.org/?probe=f1d33c68f6) | Jun 01, 2021 |
| Gigabyte      | B450 AORUS ELITE         | [35c74e640b](https://linux-hardware.org/?probe=35c74e640b) | May 31, 2021 |
| ASUSTek       | PRIME H110M-P            | [63effde8c3](https://linux-hardware.org/?probe=63effde8c3) | May 08, 2021 |
| ASUSTek       | PRIME H110M-P            | [99ac06d5e2](https://linux-hardware.org/?probe=99ac06d5e2) | May 08, 2021 |
| ASUSTek       | B75M-A                   | [2fabbbebb9](https://linux-hardware.org/?probe=2fabbbebb9) | Apr 29, 2021 |
| ASUSTek       | B75M-A                   | [23cc5c25c3](https://linux-hardware.org/?probe=23cc5c25c3) | Apr 29, 2021 |
| ASRock        | G41M-VS3                 | [599315872a](https://linux-hardware.org/?probe=599315872a) | Apr 24, 2021 |
| Gigabyte      | Z97X-UD3H-CF             | [c941a697c2](https://linux-hardware.org/?probe=c941a697c2) | Apr 22, 2021 |
| MSI           | B450M MORTAR MAX         | [e55472cf5f](https://linux-hardware.org/?probe=e55472cf5f) | Apr 18, 2021 |
| MSI           | B450M PRO-VDH MAX        | [abf17f0c92](https://linux-hardware.org/?probe=abf17f0c92) | Apr 17, 2021 |
| Gigabyte      | MZBAYAP-00               | [cdfb323202](https://linux-hardware.org/?probe=cdfb323202) | Apr 04, 2021 |
| Dell          | 04Y8V0 A02               | [241289046a](https://linux-hardware.org/?probe=241289046a) | Mar 16, 2021 |
| Gigabyte      | Z390 UD                  | [d56654c11c](https://linux-hardware.org/?probe=d56654c11c) | Mar 12, 2021 |
| Dell          | 088DT1 A01               | [d1bd158872](https://linux-hardware.org/?probe=d1bd158872) | Mar 10, 2021 |
| Dell          | 088DT1 A01               | [9e8527b842](https://linux-hardware.org/?probe=9e8527b842) | Mar 05, 2021 |
| Gigabyte      | H81M-DS2                 | [96fd52e1f2](https://linux-hardware.org/?probe=96fd52e1f2) | Mar 02, 2021 |
| Gigabyte      | B450M GAMING             | [bb980a20ea](https://linux-hardware.org/?probe=bb980a20ea) | Feb 18, 2021 |
| ASUSTek       | EB1036                   | [d77c773bc7](https://linux-hardware.org/?probe=d77c773bc7) | Feb 17, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD  | [e9acf54209](https://linux-hardware.org/?probe=e9acf54209) | Jan 15, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD  | [d462b4ca25](https://linux-hardware.org/?probe=d462b4ca25) | Jan 12, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD  | [8ae2ef5b3b](https://linux-hardware.org/?probe=8ae2ef5b3b) | Jan 07, 2021 |
| MSI           | Z390-A PRO               | [4a11009c6f](https://linux-hardware.org/?probe=4a11009c6f) | Jan 06, 2021 |
| ASUSTek       | B75M-A                   | [cf3d073aae](https://linux-hardware.org/?probe=cf3d073aae) | Jan 06, 2021 |
| Intel         | DP55WG AAE57269-407      | [8b549321e4](https://linux-hardware.org/?probe=8b549321e4) | Dec 31, 2020 |
| Gigabyte      | G41M-ES2L                | [540115f336](https://linux-hardware.org/?probe=540115f336) | Dec 28, 2020 |
| Gigabyte      | F2A68HM-HD2              | [2e581b986a](https://linux-hardware.org/?probe=2e581b986a) | Dec 28, 2020 |
| Gigabyte      | G41M-ES2L                | [cd0b939f13](https://linux-hardware.org/?probe=cd0b939f13) | Dec 27, 2020 |
| HP            | 158A                     | [9c309002d1](https://linux-hardware.org/?probe=9c309002d1) | Dec 10, 2020 |
| HP            | 2B2C                     | [ffd83f6d60](https://linux-hardware.org/?probe=ffd83f6d60) | Dec 08, 2020 |
| HP            | 158A                     | [eaab601c40](https://linux-hardware.org/?probe=eaab601c40) | Dec 02, 2020 |
| HP            | 158A                     | [64320f7764](https://linux-hardware.org/?probe=64320f7764) | Dec 02, 2020 |
| MSI           | Z390-A PRO               | [318f172f36](https://linux-hardware.org/?probe=318f172f36) | Oct 27, 2020 |
| ASUSTek       | SABERTOOTH Z77           | [bcc1019568](https://linux-hardware.org/?probe=bcc1019568) | Oct 07, 2020 |
| Dell          | 0215PR A02               | [a37475889b](https://linux-hardware.org/?probe=a37475889b) | Oct 03, 2020 |
| Koloe         | X58                      | [81d474ab62](https://linux-hardware.org/?probe=81d474ab62) | Sep 20, 2020 |
| ASUSTek       | Z10PE-D8 WS              | [55e8990643](https://linux-hardware.org/?probe=55e8990643) | Sep 17, 2020 |
| Unknown       | SKYBAY                   | [190c1e6486](https://linux-hardware.org/?probe=190c1e6486) | Aug 31, 2020 |
| Unknown       | SKYBAY                   | [889530c9b1](https://linux-hardware.org/?probe=889530c9b1) | Aug 28, 2020 |
| Unknown       | SKYBAY                   | [01f13cc1c7](https://linux-hardware.org/?probe=01f13cc1c7) | Aug 25, 2020 |
| Dell          | 0200DY A02               | [dc862d439b](https://linux-hardware.org/?probe=dc862d439b) | Aug 24, 2020 |
| MSI           | B85M Night Elf           | [d9fe6d88cd](https://linux-hardware.org/?probe=d9fe6d88cd) | Aug 14, 2020 |
| HP            | 2B2C                     | [ed031034e8](https://linux-hardware.org/?probe=ed031034e8) | Jul 18, 2020 |
| HP            | 2B2C                     | [dd85e7a5e1](https://linux-hardware.org/?probe=dd85e7a5e1) | Jul 18, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING  | [601726ae15](https://linux-hardware.org/?probe=601726ae15) | Jul 01, 2020 |
| ASUSTek       | A68HM-K                  | [7fc608d8c2](https://linux-hardware.org/?probe=7fc608d8c2) | Jun 21, 2020 |
| MSI           | B85M Night Elf           | [f223bc5b5e](https://linux-hardware.org/?probe=f223bc5b5e) | Jun 19, 2020 |
| MSI           | B85M Night Elf           | [27d008955f](https://linux-hardware.org/?probe=27d008955f) | Jun 19, 2020 |
| ASUSTek       | H97-PRO GAMER            | [ce4a203e0f](https://linux-hardware.org/?probe=ce4a203e0f) | Jun 19, 2020 |
| Gigabyte      | B450M GAMING             | [7b0270fb87](https://linux-hardware.org/?probe=7b0270fb87) | Jun 04, 2020 |
| Gigabyte      | H170-Gaming 3            | [b0f5fc9b10](https://linux-hardware.org/?probe=b0f5fc9b10) | May 26, 2020 |
| Gigabyte      | B450M GAMING             | [ffb18f222a](https://linux-hardware.org/?probe=ffb18f222a) | May 15, 2020 |
| Gigabyte      | B450M GAMING             | [a4ec49073e](https://linux-hardware.org/?probe=a4ec49073e) | May 02, 2020 |
| ASRock        | AOD790GX/128M            | [8ba6b55d11](https://linux-hardware.org/?probe=8ba6b55d11) | Apr 28, 2020 |
| Gigabyte      | H61M-DS2                 | [1aa80c5f94](https://linux-hardware.org/?probe=1aa80c5f94) | Apr 26, 2020 |
| Gigabyte      | B250M-D2V-CF             | [45b9a81a90](https://linux-hardware.org/?probe=45b9a81a90) | Apr 08, 2020 |
| Shuttle       | FS81                     | [93c00d64e6](https://linux-hardware.org/?probe=93c00d64e6) | Feb 07, 2020 |
| Gigabyte      | B360M AORUS Gaming 3-CF  | [e3cbb2da5f](https://linux-hardware.org/?probe=e3cbb2da5f) | Jan 24, 2020 |
| ASUSTek       | P9X79 WS                 | [7a8ccfd558](https://linux-hardware.org/?probe=7a8ccfd558) | Nov 21, 2019 |
| Dell          | 0CU409                   | [a5aabfdba4](https://linux-hardware.org/?probe=a5aabfdba4) | Sep 09, 2019 |
| Dell          | 0CU409                   | [8efe3a4b92](https://linux-hardware.org/?probe=8efe3a4b92) | Sep 08, 2019 |
| Gigabyte      | B360 M AORUS PRO-CF      | [657b0b4115](https://linux-hardware.org/?probe=657b0b4115) | Aug 28, 2019 |
| Gigabyte      | B450M GAMING             | [6a22791c51](https://linux-hardware.org/?probe=6a22791c51) | Aug 02, 2019 |
| Gigabyte      | B450M GAMING             | [9394c6057f](https://linux-hardware.org/?probe=9394c6057f) | Aug 01, 2019 |
| ASUSTek       | P8H61-MX R2.0            | [6cf789df63](https://linux-hardware.org/?probe=6cf789df63) | Jul 26, 2019 |
| Gigabyte      | B450M GAMING             | [a6040fd25f](https://linux-hardware.org/?probe=a6040fd25f) | Jul 21, 2019 |
| Gigabyte      | B450M GAMING             | [e4ad262a5d](https://linux-hardware.org/?probe=e4ad262a5d) | Jul 18, 2019 |
| ASUSTek       | P8H61-MX R2.0            | [c52b084692](https://linux-hardware.org/?probe=c52b084692) | Jul 08, 2019 |
| ASUSTek       | P8H61-MX R2.0            | [06efccb71d](https://linux-hardware.org/?probe=06efccb71d) | Jul 07, 2019 |
| Wistron       | JIH55Y                   | [75d7b2909e](https://linux-hardware.org/?probe=75d7b2909e) | Jul 07, 2019 |
| MSI           | K9A2 Neo2                | [ab1717a7d5](https://linux-hardware.org/?probe=ab1717a7d5) | Jul 05, 2019 |
| MSI           | K9A2 Neo2                | [32eed13a8c](https://linux-hardware.org/?probe=32eed13a8c) | Jul 05, 2019 |
| ASUSTek       | H81M-K                   | [0142c9d319](https://linux-hardware.org/?probe=0142c9d319) | May 08, 2019 |
| ASUSTek       | H81M-K                   | [eab65462c8](https://linux-hardware.org/?probe=eab65462c8) | May 08, 2019 |
| Gigabyte      | H61M-DS2                 | [6c2f44420a](https://linux-hardware.org/?probe=6c2f44420a) | Nov 09, 2018 |
| Gigabyte      | H61M-DS2                 | [795142797e](https://linux-hardware.org/?probe=795142797e) | Nov 09, 2018 |
| Lenovo        | ThinkCentre M55e 9389AN1 | [850f4b963c](https://linux-hardware.org/?probe=850f4b963c) | Dec 08, 2017 |
| Lenovo        | ThinkCentre M55e 9389AN1 | [e764602f25](https://linux-hardware.org/?probe=e764602f25) | Dec 02, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 23       | 26.14%  |
| Ubuntu 18.04                 | 16       | 18.18%  |
| Arch                         | 5        | 5.68%   |
| Arch Rolling                 | 3        | 3.41%   |
| Zorin 16                     | 2        | 2.27%   |
| Ubuntu Unity 16.04           | 2        | 2.27%   |
| Ubuntu 22.04                 | 2        | 2.27%   |
| Ubuntu 19.04                 | 2        | 2.27%   |
| Pop!_OS 20.10                | 2        | 2.27%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 2.27%   |
| Manjaro 20.2                 | 2        | 2.27%   |
| Manjaro                      | 2        | 2.27%   |
| Linux Mint 20.3              | 2        | 2.27%   |
| Debian 11                    | 2        | 2.27%   |
| Debian 10                    | 2        | 2.27%   |
| ArcoLinux Rolling            | 2        | 2.27%   |
| Zorin 15                     | 1        | 1.14%   |
| Xubuntu 20.04                | 1        | 1.14%   |
| Ubuntu 21.04                 | 1        | 1.14%   |
| Ubuntu 16.04                 | 1        | 1.14%   |
| Parrot 4.11                  | 1        | 1.14%   |
| OpenMandriva 4.3             | 1        | 1.14%   |
| OpenMandriva 4.2             | 1        | 1.14%   |
| Manjaro 21.0.1               | 1        | 1.14%   |
| Manjaro 20.0.3               | 1        | 1.14%   |
| Linux Mint 20                | 1        | 1.14%   |
| Kubuntu 20.04                | 1        | 1.14%   |
| KDE neon 20.04               | 1        | 1.14%   |
| Fedora 36                    | 1        | 1.14%   |
| EndeavourOS Rolling          | 1        | 1.14%   |
| Elementary 6                 | 1        | 1.14%   |
| Clear Linux 34500            | 1        | 1.14%   |
| Clear Linux 32260            | 1        | 1.14%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 43       | 50%     |
| Arch         | 8        | 9.3%    |
| Manjaro      | 6        | 6.98%   |
| Debian       | 4        | 4.65%   |
| Zorin        | 3        | 3.49%   |
| Linux Mint   | 3        | 3.49%   |
| Ubuntu Unity | 2        | 2.33%   |
| Pop!_OS      | 2        | 2.33%   |
| openSUSE     | 2        | 2.33%   |
| OpenMandriva | 2        | 2.33%   |
| Clear Linux  | 2        | 2.33%   |
| ArcoLinux    | 2        | 2.33%   |
| Xubuntu      | 1        | 1.16%   |
| Parrot       | 1        | 1.16%   |
| Kubuntu      | 1        | 1.16%   |
| KDE neon     | 1        | 1.16%   |
| Fedora       | 1        | 1.16%   |
| EndeavourOS  | 1        | 1.16%   |
| Elementary   | 1        | 1.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.4.0-58-generic       | 4        | 4.35%   |
| 5.4.0-37-generic       | 3        | 3.26%   |
| 5.4.0-26-generic       | 3        | 3.26%   |
| 5.11.0-38-generic      | 3        | 3.26%   |
| 5.0.0-23-generic       | 3        | 3.26%   |
| 5.9.11-3-MANJARO       | 2        | 2.17%   |
| 5.8.0-7642-generic     | 2        | 2.17%   |
| 5.4.0-48-generic       | 2        | 2.17%   |
| 5.4.0-47-generic       | 2        | 2.17%   |
| 5.4.0-42-generic       | 2        | 2.17%   |
| 5.11.0-37-generic      | 2        | 2.17%   |
| 4.18.0-25-generic      | 2        | 2.17%   |
| 6.0.0-rc5              | 1        | 1.09%   |
| 5.9.12-arch1-1         | 1        | 1.09%   |
| 5.9.0-0.bpo.5-amd64    | 1        | 1.09%   |
| 5.8.0-59-generic       | 1        | 1.09%   |
| 5.8.0-55-generic       | 1        | 1.09%   |
| 5.8.0-53-generic       | 1        | 1.09%   |
| 5.8.0-50-generic       | 1        | 1.09%   |
| 5.8.0-45-generic       | 1        | 1.09%   |
| 5.8.0-43-generic       | 1        | 1.09%   |
| 5.6.15-1-MANJARO       | 1        | 1.09%   |
| 5.6.0-1-default        | 1        | 1.09%   |
| 5.4.78-2-pve           | 1        | 1.09%   |
| 5.4.18-902.native      | 1        | 1.09%   |
| 5.4.0-99-generic       | 1        | 1.09%   |
| 5.4.0-90-generic       | 1        | 1.09%   |
| 5.4.0-72-generic       | 1        | 1.09%   |
| 5.4.0-65-generic       | 1        | 1.09%   |
| 5.4.0-52-generic       | 1        | 1.09%   |
| 5.4.0-39-generic       | 1        | 1.09%   |
| 5.4.0-33-generic       | 1        | 1.09%   |
| 5.4.0-31-generic       | 1        | 1.09%   |
| 5.4.0-28-generic       | 1        | 1.09%   |
| 5.19.7-arch1-1         | 1        | 1.09%   |
| 5.19.4-arch1-1         | 1        | 1.09%   |
| 5.19.3-zen1-1-zen      | 1        | 1.09%   |
| 5.18.9-200.fc36.x86_64 | 1        | 1.09%   |
| 5.17.9-arch1-1         | 1        | 1.09%   |
| 5.17.1-arch1-1         | 1        | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 23       | 25.84%  |
| 5.11.0  | 9        | 10.11%  |
| 5.8.0   | 8        | 8.99%   |
| 5.0.0   | 6        | 6.74%   |
| 4.15.0  | 6        | 6.74%   |
| 5.15.0  | 3        | 3.37%   |
| 5.9.11  | 2        | 2.25%   |
| 5.12.8  | 2        | 2.25%   |
| 4.18.0  | 2        | 2.25%   |
| 6.0.0   | 1        | 1.12%   |
| 5.9.12  | 1        | 1.12%   |
| 5.9.0   | 1        | 1.12%   |
| 5.6.15  | 1        | 1.12%   |
| 5.6.0   | 1        | 1.12%   |
| 5.4.78  | 1        | 1.12%   |
| 5.4.18  | 1        | 1.12%   |
| 5.19.7  | 1        | 1.12%   |
| 5.19.4  | 1        | 1.12%   |
| 5.19.3  | 1        | 1.12%   |
| 5.18.9  | 1        | 1.12%   |
| 5.17.9  | 1        | 1.12%   |
| 5.17.1  | 1        | 1.12%   |
| 5.16.7  | 1        | 1.12%   |
| 5.15.60 | 1        | 1.12%   |
| 5.15.53 | 1        | 1.12%   |
| 5.14.0  | 1        | 1.12%   |
| 5.12.15 | 1        | 1.12%   |
| 5.12.1  | 1        | 1.12%   |
| 5.11.16 | 1        | 1.12%   |
| 5.10.42 | 1        | 1.12%   |
| 5.10.26 | 1        | 1.12%   |
| 5.10.19 | 1        | 1.12%   |
| 5.10.14 | 1        | 1.12%   |
| 5.10.0  | 1        | 1.12%   |
| 4.19.97 | 1        | 1.12%   |
| 4.15.18 | 1        | 1.12%   |
| 4.10.0  | 1        | 1.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 25       | 28.09%  |
| 5.11    | 10       | 11.24%  |
| 5.8     | 8        | 8.99%   |
| 4.15    | 7        | 7.87%   |
| 5.0     | 6        | 6.74%   |
| 5.15    | 5        | 5.62%   |
| 5.10    | 5        | 5.62%   |
| 5.9     | 4        | 4.49%   |
| 5.12    | 4        | 4.49%   |
| 5.19    | 3        | 3.37%   |
| 5.6     | 2        | 2.25%   |
| 5.17    | 2        | 2.25%   |
| 4.18    | 2        | 2.25%   |
| 6.0     | 1        | 1.12%   |
| 5.18    | 1        | 1.12%   |
| 5.16    | 1        | 1.12%   |
| 5.14    | 1        | 1.12%   |
| 4.19    | 1        | 1.12%   |
| 4.10    | 1        | 1.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 84       | 98.82%  |
| i686   | 1        | 1.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 46       | 52.87%  |
| Unknown    | 17       | 19.54%  |
| KDE5       | 9        | 10.34%  |
| XFCE       | 3        | 3.45%   |
| MATE       | 3        | 3.45%   |
| Unity      | 2        | 2.3%    |
| KDE        | 2        | 2.3%    |
| X-Cinnamon | 1        | 1.15%   |
| Pantheon   | 1        | 1.15%   |
| i3         | 1        | 1.15%   |
| Cinnamon   | 1        | 1.15%   |
| awesome    | 1        | 1.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 65       | 74.71%  |
| Wayland | 9        | 10.34%  |
| Unknown | 9        | 10.34%  |
| Tty     | 4        | 4.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 41       | 47.67%  |
| GDM     | 17       | 19.77%  |
| SDDM    | 9        | 10.47%  |
| LightDM | 8        | 9.3%    |
| GDM3    | 6        | 6.98%   |
| TDM     | 4        | 4.65%   |
| XDM     | 1        | 1.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 68       | 79.07%  |
| Unknown | 11       | 12.79%  |
| vi_VN   | 5        | 5.81%   |
| ru_RU   | 1        | 1.16%   |
| C       | 1        | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 46       | 53.49%  |
| BIOS | 40       | 46.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 74       | 85.06%  |
| Overlay | 5        | 5.75%   |
| Btrfs   | 3        | 3.45%   |
| Zfs     | 2        | 2.3%    |
| Unknown | 2        | 2.3%    |
| F2fs    | 1        | 1.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 43       | 50.59%  |
| GPT     | 31       | 36.47%  |
| MBR     | 11       | 12.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 80.23%  |
| Yes       | 17       | 19.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 45       | 52.33%  |
| No        | 41       | 47.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 28       | 32.94%  |
| ASUSTek Computer    | 21       | 24.71%  |
| MSI                 | 10       | 11.76%  |
| Hewlett-Packard     | 6        | 7.06%   |
| Dell                | 6        | 7.06%   |
| Wistron             | 2        | 2.35%   |
| Lenovo              | 2        | 2.35%   |
| Foxconn             | 2        | 2.35%   |
| ASRock              | 2        | 2.35%   |
| Shuttle             | 1        | 1.18%   |
| Koloe               | 1        | 1.18%   |
| Intel               | 1        | 1.18%   |
| Huanan              | 1        | 1.18%   |
| Colorful Technology | 1        | 1.18%   |
| Unknown             | 1        | 1.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte H61M-DS2                  | 5        | 5.88%   |
| ASUS All Series                    | 3        | 3.53%   |
| MSI MS-7B89                        | 2        | 2.35%   |
| MSI MS-7823                        | 2        | 2.35%   |
| Gigabyte G41M-ES2L                 | 2        | 2.35%   |
| Gigabyte B450M GAMING              | 2        | 2.35%   |
| ASUS P8H61-MX R2.0                 | 2        | 2.35%   |
| ASUS B75M-A                        | 2        | 2.35%   |
| Wistron FMVDD2A0H0                 | 1        | 1.18%   |
| Wistron FMVCEG40Y                  | 1        | 1.18%   |
| Shuttle DS81D                      | 1        | 1.18%   |
| MSI MS-7C89                        | 1        | 1.18%   |
| MSI MS-7C67                        | 1        | 1.18%   |
| MSI MS-7C31                        | 1        | 1.18%   |
| MSI MS-7B98                        | 1        | 1.18%   |
| MSI MS-7A38                        | 1        | 1.18%   |
| MSI MS-7388                        | 1        | 1.18%   |
| Lenovo ThinkCentre M93p 10A8CTO1WW | 1        | 1.18%   |
| Lenovo ThinkCentre M55e 9389AN1    | 1        | 1.18%   |
| Koloe Thurley                      | 1        | 1.18%   |
| Intel DP55WG AAE57269-407          | 1        | 1.18%   |
| Huanan X79 249PC V2.1              | 1        | 1.18%   |
| HP Z620 Workstation                | 1        | 1.18%   |
| HP Z2 Tower G4 Workstation         | 1        | 1.18%   |
| HP ProDesk 600 G1 SFF              | 1        | 1.18%   |
| HP p2-1221l                        | 1        | 1.18%   |
| HP 500-504x                        | 1        | 1.18%   |
| HP 251-152l                        | 1        | 1.18%   |
| Gigabyte Z97X-UD3H                 | 1        | 1.18%   |
| Gigabyte Z390 UD                   | 1        | 1.18%   |
| Gigabyte Z170-D3H                  | 1        | 1.18%   |
| Gigabyte X570 UD                   | 1        | 1.18%   |
| Gigabyte P110-D3                   | 1        | 1.18%   |
| Gigabyte H81M-DS2                  | 1        | 1.18%   |
| Gigabyte H170-Gaming 3             | 1        | 1.18%   |
| Gigabyte H110M-DS2                 | 1        | 1.18%   |
| Gigabyte GB-BXBT-2807              | 1        | 1.18%   |
| Gigabyte G1.Sniper B5              | 1        | 1.18%   |
| Gigabyte F2A68HM-HD2               | 1        | 1.18%   |
| Gigabyte EP43T-S3L                 | 1        | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Gigabyte H61M-DS2     | 5        | 5.88%   |
| ASUS PRIME            | 4        | 4.71%   |
| Dell OptiPlex         | 3        | 3.53%   |
| ASUS ROG              | 3        | 3.53%   |
| ASUS P8H61-MX         | 3        | 3.53%   |
| ASUS All              | 3        | 3.53%   |
| MSI MS-7B89           | 2        | 2.35%   |
| MSI MS-7823           | 2        | 2.35%   |
| Lenovo ThinkCentre    | 2        | 2.35%   |
| Gigabyte G41M-ES2L    | 2        | 2.35%   |
| Gigabyte B450M        | 2        | 2.35%   |
| ASUS B75M-A           | 2        | 2.35%   |
| Wistron FMVDD2A0H0    | 1        | 1.18%   |
| Wistron FMVCEG40Y     | 1        | 1.18%   |
| Shuttle DS81D         | 1        | 1.18%   |
| MSI MS-7C89           | 1        | 1.18%   |
| MSI MS-7C67           | 1        | 1.18%   |
| MSI MS-7C31           | 1        | 1.18%   |
| MSI MS-7B98           | 1        | 1.18%   |
| MSI MS-7A38           | 1        | 1.18%   |
| MSI MS-7388           | 1        | 1.18%   |
| Koloe Thurley         | 1        | 1.18%   |
| Intel DP55WG          | 1        | 1.18%   |
| Huanan X79            | 1        | 1.18%   |
| HP Z620               | 1        | 1.18%   |
| HP Z2                 | 1        | 1.18%   |
| HP ProDesk            | 1        | 1.18%   |
| HP p2-1221l           | 1        | 1.18%   |
| HP 500-504x           | 1        | 1.18%   |
| HP 251-152l           | 1        | 1.18%   |
| Gigabyte Z97X-UD3H    | 1        | 1.18%   |
| Gigabyte Z390         | 1        | 1.18%   |
| Gigabyte Z170-D3H     | 1        | 1.18%   |
| Gigabyte X570         | 1        | 1.18%   |
| Gigabyte P110-D3      | 1        | 1.18%   |
| Gigabyte H81M-DS2     | 1        | 1.18%   |
| Gigabyte H170-Gaming  | 1        | 1.18%   |
| Gigabyte H110M-DS2    | 1        | 1.18%   |
| Gigabyte GB-BXBT-2807 | 1        | 1.18%   |
| Gigabyte G1.Sniper    | 1        | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 13       | 15.29%  |
| 2012 | 12       | 14.12%  |
| 2014 | 11       | 12.94%  |
| 2013 | 9        | 10.59%  |
| 2019 | 7        | 8.24%   |
| 2010 | 7        | 8.24%   |
| 2017 | 5        | 5.88%   |
| 2020 | 4        | 4.71%   |
| 2016 | 4        | 4.71%   |
| 2009 | 4        | 4.71%   |
| 2015 | 3        | 3.53%   |
| 2022 | 1        | 1.18%   |
| 2021 | 1        | 1.18%   |
| 2011 | 1        | 1.18%   |
| 2008 | 1        | 1.18%   |
| 2007 | 1        | 1.18%   |
| 2006 | 1        | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 85       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 81       | 95.29%  |
| Enabled  | 4        | 4.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 85       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 21       | 24.42%  |
| 16.01-24.0  | 20       | 23.26%  |
| 3.01-4.0    | 14       | 16.28%  |
| 32.01-64.0  | 11       | 12.79%  |
| 4.01-8.0    | 9        | 10.47%  |
| 1.01-2.0    | 7        | 8.14%   |
| 24.01-32.0  | 3        | 3.49%   |
| 64.01-256.0 | 1        | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 30       | 34.88%  |
| 2.01-3.0  | 24       | 27.91%  |
| 3.01-4.0  | 13       | 15.12%  |
| 4.01-8.0  | 10       | 11.63%  |
| 8.01-16.0 | 7        | 8.14%   |
| 0.51-1.0  | 1        | 1.16%   |
| 0.01-0.5  | 1        | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 39       | 44.83%  |
| 1      | 28       | 32.18%  |
| 3      | 10       | 11.49%  |
| 4      | 6        | 6.9%    |
| 5      | 2        | 2.3%    |
| 9      | 1        | 1.15%   |
| 0      | 1        | 1.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 80%     |
| Yes       | 17       | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 84       | 98.82%  |
| No        | 1        | 1.18%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 55.29%  |
| Yes       | 38       | 44.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 66.28%  |
| Yes       | 29       | 33.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Vietnam | 85       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Ho Chi Minh City | 49       | 56.98%  |
| Hanoi            | 21       | 24.42%  |
| Nga Bay          | 2        | 2.33%   |
| Vũng Tàu       | 1        | 1.16%   |
| Vi Thanh         | 1        | 1.16%   |
| Tay Ninh         | 1        | 1.16%   |
| Quảng Ngai     | 1        | 1.16%   |
| Nha Trang        | 1        | 1.16%   |
| Nam Định      | 1        | 1.16%   |
| Haiphong         | 1        | 1.16%   |
| Hai Duong        | 1        | 1.16%   |
| Di An            | 1        | 1.16%   |
| Da Nang          | 1        | 1.16%   |
| Can Tho          | 1        | 1.16%   |
| Bien Hoa         | 1        | 1.16%   |
| Bến Tre        | 1        | 1.16%   |
| Bac Giang        | 1        | 1.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 42       | 51     | 27.63%  |
| Seagate               | 26       | 34     | 17.11%  |
| Samsung Electronics   | 17       | 22     | 11.18%  |
| Kingston              | 9        | 10     | 5.92%   |
| Toshiba               | 7        | 12     | 4.61%   |
| Intel                 | 4        | 4      | 2.63%   |
| Hitachi               | 4        | 4      | 2.63%   |
| Crucial               | 4        | 7      | 2.63%   |
| SanDisk               | 3        | 3      | 1.97%   |
| Lexar                 | 3        | 3      | 1.97%   |
| HGST                  | 3        | 3      | 1.97%   |
| Colorful              | 3        | 3      | 1.97%   |
| ZOTAC                 | 2        | 2      | 1.32%   |
| Unknown               | 2        | 2      | 1.32%   |
| TO Exter              | 2        | 3      | 1.32%   |
| OCZ                   | 2        | 2      | 1.32%   |
| Netac                 | 2        | 2      | 1.32%   |
| Fujitsu               | 2        | 2      | 1.32%   |
| Vaseky                | 1        | 1      | 0.66%   |
| Transcend             | 1        | 1      | 0.66%   |
| SK hynix              | 1        | 1      | 0.66%   |
| Realtek Semiconductor | 1        | 2      | 0.66%   |
| Phison                | 1        | 2      | 0.66%   |
| Patriot               | 1        | 1      | 0.66%   |
| Mushkin               | 1        | 1      | 0.66%   |
| Micron Technology     | 1        | 1      | 0.66%   |
| Maxtor                | 1        | 1      | 0.66%   |
| Lite-On               | 1        | 1      | 0.66%   |
| KING                  | 1        | 1      | 0.66%   |
| Gigabyte Technology   | 1        | 1      | 0.66%   |
| External              | 1        | 1      | 0.66%   |
| EK                    | 1        | 1      | 0.66%   |
| BR                    | 1        | 1      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD | 5        | 3.05%   |
| Kingston SA400S37240G 240GB SSD  | 4        | 2.44%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 3        | 1.83%   |
| WDC WD2500AAKX-00ERMA0 250GB     | 3        | 1.83%   |
| Seagate ST1000DM010-2EP102 1TB   | 3        | 1.83%   |
| ZOTAC SATA SSD 120GB             | 2        | 1.22%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2        | 1.22%   |
| WDC WD3200AAKX-001CA0 320GB      | 2        | 1.22%   |
| Toshiba DT01ABA100V 1TB          | 2        | 1.22%   |
| TO Exter nal USB 3.0 180GB       | 2        | 1.22%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 1.22%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 1.22%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 1.22%   |
| Samsung SSD 860 EVO 500GB        | 2        | 1.22%   |
| Samsung SSD 860 EVO 250GB        | 2        | 1.22%   |
| Samsung SSD 860 EVO 1TB          | 2        | 1.22%   |
| Samsung SSD 750 EVO 120GB        | 2        | 1.22%   |
| Lexar 128GB SSD                  | 2        | 1.22%   |
| Hitachi HDT725032VLA380 320GB    | 2        | 1.22%   |
| Crucial CT250MX500SSD1 250GB     | 2        | 1.22%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 0.61%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 1        | 0.61%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 0.61%   |
| WDC WDS120G1G0A-00SS50 120GB SSD | 1        | 0.61%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 1        | 0.61%   |
| WDC WD80EFBX-68AZZN0 8TB         | 1        | 0.61%   |
| WDC WD80 03FFBX-68B9AN0 8TB      | 1        | 0.61%   |
| WDC WD60PURX-64T0ZY0 6TB         | 1        | 0.61%   |
| WDC WD5000LPVX-75V0TT0 500GB     | 1        | 0.61%   |
| WDC WD5000AZLX-75K2TA0 500GB     | 1        | 0.61%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.61%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1        | 0.61%   |
| WDC WD40EFAX-68JH4N0 4TB         | 1        | 0.61%   |
| WDC WD3200BPVT-75ZEST0 320GB     | 1        | 0.61%   |
| WDC WD3200BEKT-75PVMT1 320GB     | 1        | 0.61%   |
| WDC WD3200AAJS-56M0A0 320GB      | 1        | 0.61%   |
| WDC WD3200AAJS-00L7A0 320GB      | 1        | 0.61%   |
| WDC WD2500JS-60MHB5 250GB        | 1        | 0.61%   |
| WDC WD2500AAKX-60U6AA0 250GB     | 1        | 0.61%   |
| WDC WD2002FAEX-007BA0 2TB        | 1        | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 30       | 37     | 41.67%  |
| Seagate | 26       | 33     | 36.11%  |
| Toshiba | 6        | 11     | 8.33%   |
| Hitachi | 4        | 4      | 5.56%   |
| HGST    | 3        | 3      | 4.17%   |
| Fujitsu | 2        | 2      | 2.78%   |
| Unknown | 1        | 1      | 1.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 14     | 17.74%  |
| WDC                 | 10       | 10     | 16.13%  |
| Kingston            | 9        | 10     | 14.52%  |
| Intel               | 4        | 4      | 6.45%   |
| Crucial             | 4        | 5      | 6.45%   |
| SanDisk             | 3        | 3      | 4.84%   |
| Lexar               | 3        | 3      | 4.84%   |
| ZOTAC               | 2        | 2      | 3.23%   |
| TO Exter            | 2        | 3      | 3.23%   |
| Netac               | 2        | 2      | 3.23%   |
| Colorful            | 2        | 2      | 3.23%   |
| Vaseky              | 1        | 1      | 1.61%   |
| Transcend           | 1        | 1      | 1.61%   |
| Toshiba             | 1        | 1      | 1.61%   |
| SK hynix            | 1        | 1      | 1.61%   |
| Patriot             | 1        | 1      | 1.61%   |
| OCZ                 | 1        | 1      | 1.61%   |
| Micron Technology   | 1        | 1      | 1.61%   |
| Maxtor              | 1        | 1      | 1.61%   |
| Gigabyte Technology | 1        | 1      | 1.61%   |
| EK                  | 1        | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 60       | 91     | 44.78%  |
| SSD     | 52       | 68     | 38.81%  |
| NVMe    | 17       | 22     | 12.69%  |
| Unknown | 5        | 5      | 3.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 77       | 156    | 77.78%  |
| NVMe | 16       | 21     | 16.16%  |
| SAS  | 6        | 9      | 6.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 69       | 103    | 65.09%  |
| 0.51-1.0   | 23       | 33     | 21.7%   |
| 1.01-2.0   | 6        | 8      | 5.66%   |
| 4.01-10.0  | 5        | 12     | 4.72%   |
| 3.01-4.0   | 2        | 2      | 1.89%   |
| 2.01-3.0   | 1        | 1      | 0.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 31       | 35.23%  |
| 501-1000       | 13       | 14.77%  |
| 251-500        | 12       | 13.64%  |
| 1001-2000      | 7        | 7.95%   |
| More than 3000 | 5        | 5.68%   |
| 1-20           | 5        | 5.68%   |
| 51-100         | 5        | 5.68%   |
| 21-50          | 4        | 4.55%   |
| 2001-3000      | 3        | 3.41%   |
| Unknown        | 3        | 3.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 34       | 39.08%  |
| 21-50          | 13       | 14.94%  |
| 51-100         | 11       | 12.64%  |
| 251-500        | 7        | 8.05%   |
| 101-250        | 6        | 6.9%    |
| 501-1000       | 6        | 6.9%    |
| More than 3000 | 3        | 3.45%   |
| Unknown        | 3        | 3.45%   |
| 2001-3000      | 2        | 2.3%    |
| 1001-2000      | 2        | 2.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD3200AAKX-001CA0 320GB      | 2        | 2      | 16.67%  |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 1      | 8.33%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 1        | 1      | 8.33%   |
| Transcend TS256GSSD230S 256GB    | 1        | 1      | 8.33%   |
| Seagate ST500DM002-1BD142 500GB  | 1        | 1      | 8.33%   |
| Seagate ST1000DM003-1ER162 1TB   | 1        | 1      | 8.33%   |
| Intel SSDSC2CW120A3 120GB        | 1        | 1      | 8.33%   |
| Hitachi HUA722020ALA331 2TB      | 1        | 1      | 8.33%   |
| Hitachi HDT725032VLA380 320GB    | 1        | 1      | 8.33%   |
| HGST HTS725050A7E630 500GB       | 1        | 1      | 8.33%   |
| Fujitsu MHK2120AT 12GB           | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor    | Desktops | Drives | Percent |
|-----------|----------|--------|---------|
| WDC       | 4        | 4      | 33.33%  |
| Seagate   | 2        | 2      | 16.67%  |
| Hitachi   | 2        | 2      | 16.67%  |
| Transcend | 1        | 1      | 8.33%   |
| Intel     | 1        | 1      | 8.33%   |
| HGST      | 1        | 1      | 8.33%   |
| Fujitsu   | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 33.33%  |
| Seagate | 2        | 2      | 22.22%  |
| Hitachi | 2        | 2      | 22.22%  |
| HGST    | 1        | 1      | 11.11%  |
| Fujitsu | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 9      | 81.82%  |
| SSD  | 2        | 3      | 18.18%  |

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
| Detected | 44       | 88     | 45.83%  |
| Works    | 41       | 85     | 42.71%  |
| Malfunc  | 10       | 12     | 10.42%  |
| Failed   | 1        | 1      | 1.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 70       | 64.81%  |
| AMD                       | 15       | 13.89%  |
| Samsung Electronics       | 7        | 6.48%   |
| SanDisk                   | 4        | 3.7%    |
| ASMedia Technology        | 3        | 2.78%   |
| Silicon Motion            | 1        | 0.93%   |
| Realtek Semiconductor     | 1        | 0.93%   |
| Phison Electronics        | 1        | 0.93%   |
| OCZ Technology Group      | 1        | 0.93%   |
| Micron/Crucial Technology | 1        | 0.93%   |
| Marvell Technology Group  | 1        | 0.93%   |
| LSI Logic / Symbios Logic | 1        | 0.93%   |
| Lite-On Technology        | 1        | 0.93%   |
| JMicron Technology        | 1        | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 9.85%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 11       | 8.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 4.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 4.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 4.55%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 3.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 3.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 3.03%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 2.27%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 2.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.27%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.52%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.52%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.52%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.76%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.76%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.76%   |
| Phison NVMe Storage Controller                                                          | 1        | 0.76%   |
| OCZ Group RD400/400A SSD                                                                | 1        | 0.76%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.76%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.76%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                                    | 1        | 0.76%   |
| Lite-On Non-Volatile memory controller                                                  | 1        | 0.76%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.76%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.76%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.76%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.76%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 67       | 63.21%  |
| IDE  | 19       | 17.92%  |
| NVMe | 16       | 15.09%  |
| RAID | 3        | 2.83%   |
| SAS  | 1        | 0.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 70       | 82.35%  |
| AMD    | 15       | 17.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 4.71%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 4.71%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 3.53%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 3.53%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 2.35%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 2.35%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 2.35%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 2.35%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 2.35%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 2.35%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 2        | 2.35%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 2.35%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 2.35%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 2.35%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 1.18%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1        | 1.18%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1        | 1.18%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz          | 1        | 1.18%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 1.18%   |
| Intel Xeon CPU E31235 @ 3.20GHz             | 1        | 1.18%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1        | 1.18%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 1.18%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.18%   |
| Intel Pentium CPU G640T @ 2.40GHz           | 1        | 1.18%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 1.18%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.18%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 1.18%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 1.18%   |
| Intel Core i7-7700T CPU @ 2.90GHz           | 1        | 1.18%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.18%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 1        | 1.18%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.18%   |
| Intel Core i5-9500 CPU @ 3.00GHz            | 1        | 1.18%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.18%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.18%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1.18%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 1.18%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.18%   |
| Intel Core i5-4670 CPU @ 3.40GHz            | 1        | 1.18%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.18%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 27       | 31.76%  |
| Intel Core i3           | 12       | 14.12%  |
| Intel Core i7           | 8        | 9.41%   |
| Intel Xeon              | 7        | 8.24%   |
| Intel Core 2 Duo        | 7        | 8.24%   |
| AMD Ryzen 5             | 6        | 7.06%   |
| Intel Pentium           | 3        | 3.53%   |
| Intel Celeron           | 2        | 2.35%   |
| AMD Ryzen 9             | 2        | 2.35%   |
| AMD A10                 | 2        | 2.35%   |
| Other                   | 1        | 1.18%   |
| Intel Pentium Dual-Core | 1        | 1.18%   |
| Intel Pentium Dual      | 1        | 1.18%   |
| Intel Core i9           | 1        | 1.18%   |
| AMD Ryzen 7 PRO         | 1        | 1.18%   |
| AMD Ryzen 3             | 1        | 1.18%   |
| AMD Phenom II X4        | 1        | 1.18%   |
| AMD Athlon II X2        | 1        | 1.18%   |
| AMD A8                  | 1        | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 34       | 39.53%  |
| 2      | 28       | 32.56%  |
| 6      | 14       | 16.28%  |
| 8      | 5        | 5.81%   |
| 16     | 2        | 2.33%   |
| 28     | 1        | 1.16%   |
| 24     | 1        | 1.16%   |
| 12     | 1        | 1.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 83       | 96.51%  |
| 2      | 3        | 3.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 54.12%  |
| 2      | 39       | 45.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 84       | 98.82%  |
| Unknown        | 1        | 1.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 17.65%  |
| 0x306c3    | 10       | 11.76%  |
| 0x306a9    | 7        | 8.24%   |
| 0x1067a    | 7        | 8.24%   |
| 0x206a7    | 6        | 7.06%   |
| 0x906ea    | 5        | 5.88%   |
| 0x906e9    | 3        | 3.53%   |
| 0x206d7    | 3        | 3.53%   |
| 0x906ed    | 2        | 2.35%   |
| 0x506e3    | 2        | 2.35%   |
| 0x30678    | 2        | 2.35%   |
| 0x20655    | 2        | 2.35%   |
| 0x08701021 | 2        | 2.35%   |
| 0x06003106 | 2        | 2.35%   |
| 0xa0653    | 1        | 1.18%   |
| 0x906eb    | 1        | 1.18%   |
| 0x90675    | 1        | 1.18%   |
| 0x6fd      | 1        | 1.18%   |
| 0x406f1    | 1        | 1.18%   |
| 0x306f2    | 1        | 1.18%   |
| 0x106a5    | 1        | 1.18%   |
| 0x10676    | 1        | 1.18%   |
| 0x0a20120a | 1        | 1.18%   |
| 0x0a201016 | 1        | 1.18%   |
| 0x08701013 | 1        | 1.18%   |
| 0x08108109 | 1        | 1.18%   |
| 0x0810100b | 1        | 1.18%   |
| 0x0800820d | 1        | 1.18%   |
| 0x06001119 | 1        | 1.18%   |
| 0x010000db | 1        | 1.18%   |
| 0x010000c7 | 1        | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 16       | 18.82%  |
| KabyLake         | 14       | 16.47%  |
| SandyBridge      | 9        | 10.59%  |
| IvyBridge        | 9        | 10.59%  |
| Penryn           | 8        | 9.41%   |
| Zen 2            | 4        | 4.71%   |
| Skylake          | 4        | 4.71%   |
| Zen+             | 3        | 3.53%   |
| Westmere         | 3        | 3.53%   |
| Zen 3            | 2        | 2.35%   |
| Steamroller      | 2        | 2.35%   |
| Silvermont       | 2        | 2.35%   |
| K10              | 2        | 2.35%   |
| Zen              | 1        | 1.18%   |
| Piledriver       | 1        | 1.18%   |
| Nehalem          | 1        | 1.18%   |
| Core             | 1        | 1.18%   |
| CometLake        | 1        | 1.18%   |
| Broadwell        | 1        | 1.18%   |
| Alderlake Hybrid | 1        | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 39       | 41.05%  |
| Intel             | 33       | 34.74%  |
| AMD               | 22       | 23.16%  |
| ASPEED Technology | 1        | 1.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 8.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 8.25%   |
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 6.19%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 4.12%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 3.09%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.09%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 3.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.09%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 2.06%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 2.06%   |
| Intel HD Graphics 630                                                       | 2        | 2.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 2.06%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.06%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.06%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 2.06%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.03%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.03%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.03%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.03%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 1.03%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 1.03%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.03%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 1.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB Rev. 2]                                  | 1        | 1.03%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1        | 1.03%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.03%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.03%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 1.03%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.03%   |
| Nvidia GK208 [GeForce GT 710]                                               | 1        | 1.03%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.03%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.03%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 1.03%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.03%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 1        | 1.03%   |
| Intel VGA compatible controller                                             | 1        | 1.03%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 32       | 37.21%  |
| 1 x Intel       | 25       | 29.07%  |
| 1 x AMD         | 22       | 25.58%  |
| Intel + Nvidia  | 6        | 6.98%   |
| Nvidia + ASPEED | 1        | 1.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 54       | 62.79%  |
| Proprietary | 31       | 36.05%  |
| Unknown     | 1        | 1.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 36.05%  |
| 1.01-2.0   | 17       | 19.77%  |
| 3.01-4.0   | 11       | 12.79%  |
| 7.01-8.0   | 6        | 6.98%   |
| 0.51-1.0   | 6        | 6.98%   |
| 5.01-6.0   | 5        | 5.81%   |
| 8.01-16.0  | 5        | 5.81%   |
| 0.01-0.5   | 5        | 5.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 25       | 30.49%  |
| Samsung Electronics  | 15       | 18.29%  |
| Goldstar             | 9        | 10.98%  |
| Hewlett-Packard      | 4        | 4.88%   |
| Ancor Communications | 4        | 4.88%   |
| ViewSonic            | 3        | 3.66%   |
| Panasonic            | 3        | 3.66%   |
| AOC                  | 3        | 3.66%   |
| BenQ                 | 2        | 2.44%   |
| Unknown (ADA)        | 1        | 1.22%   |
| Sony                 | 1        | 1.22%   |
| Philips              | 1        | 1.22%   |
| NEC Computers        | 1        | 1.22%   |
| LG Electronics       | 1        | 1.22%   |
| Lenovo Group Limited | 1        | 1.22%   |
| Lenovo               | 1        | 1.22%   |
| HPN                  | 1        | 1.22%   |
| HOP                  | 1        | 1.22%   |
| CGC                  | 1        | 1.22%   |
| AUS                  | 1        | 1.22%   |
| ASUSTek Computer     | 1        | 1.22%   |
| Acer                 | 1        | 1.22%   |
| Unknown              | 1        | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Panasonic TV MEIC33B 1366x768 521x293mm 23.5-inch                       | 3        | 3.49%   |
| Samsung Electronics SME1720NR SAM0696 1280x1024 338x270mm 17.0-inch     | 2        | 2.33%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                    | 2        | 2.33%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                       | 2        | 2.33%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 477x268mm 21.5-inch              | 1        | 1.16%   |
| ViewSonic VA2201-FHD VSC683B 1920x1080 480x260mm 21.5-inch              | 1        | 1.16%   |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                               | 1        | 1.16%   |
| Unknown (ADA) LCD Monitor ADA0004 1024x600 150x100mm 7.1-inch           | 1        | 1.16%   |
| Sony TV SNY8E03 1920x1080                                               | 1        | 1.16%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 1        | 1.16%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 1.16%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch       | 1        | 1.16%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 1.16%   |
| Samsung Electronics S20D300 SAM0B39 1600x900 432x240mm 19.5-inch        | 1        | 1.16%   |
| Samsung Electronics S20B370 SAM08B7 1600x900 443x249mm 20.0-inch        | 1        | 1.16%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch        | 1        | 1.16%   |
| Samsung Electronics S19C170 SAM0B02 1366x768 410x230mm 18.5-inch        | 1        | 1.16%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SME1720NR 1280x1024                     | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SMB1930N                                | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 1872x1053mm 84.6-inch | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 1872x1053mm 84.6-inch | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SAM0658 1920x1080 880x500mm 39.8-inch   | 1        | 1.16%   |
| Philips 24PHT4003S/74 PHT4003 1360x768 525x297mm 23.7-inch              | 1        | 1.16%   |
| NEC Computers LCD172VXM NEC67C5 1280x1024 338x270mm 17.0-inch           | 1        | 1.16%   |
| LG Electronics LCD Monitor MP59G                                        | 1        | 1.16%   |
| Lenovo LEN L1900pA LEN114F 1280x1024 376x301mm 19.0-inch                | 1        | 1.16%   |
| Lenovo Group Limited LCD Monitor LEN L1900pA 1280x1024                  | 1        | 1.16%   |
| HPN LCD Monitor HP Z23n G2 1920x1080                                    | 1        | 1.16%   |
| HOP DVI HOP2700 1920x1080 597x336mm 27.0-inch                           | 1        | 1.16%   |
| Hewlett-Packard w1707 HWP2800 1440x900 370x230mm 17.2-inch              | 1        | 1.16%   |
| Hewlett-Packard N220 HPN3408 1920x1080 476x268mm 21.5-inch              | 1        | 1.16%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch             | 1        | 1.16%   |
| Hewlett-Packard E273q HPN3474 2560x1440 600x340mm 27.2-inch             | 1        | 1.16%   |
| Goldstar W2043 GSM4E9E 1600x900 443x249mm 20.0-inch                     | 1        | 1.16%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 1        | 1.16%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                  | 1        | 1.16%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                  | 1        | 1.16%   |
| Goldstar 27GN950 GSM5B9A 3840x2160 600x340mm 27.2-inch                  | 1        | 1.16%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                  | 1        | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 37       | 44.58%  |
| 3840x2160 (4K)   | 9        | 10.84%  |
| 1366x768 (WXGA)  | 8        | 9.64%   |
| 1280x1024 (SXGA) | 8        | 9.64%   |
| 2560x1440 (QHD)  | 6        | 7.23%   |
| 1600x900 (HD+)   | 6        | 7.23%   |
| Unknown          | 3        | 3.61%   |
| 1440x900 (WXGA+) | 2        | 2.41%   |
| 3840x1080        | 1        | 1.2%    |
| 3286x1080        | 1        | 1.2%    |
| 1360x768         | 1        | 1.2%    |
| 1280x800 (WXGA)  | 1        | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 15.85%  |
| 23      | 12       | 14.63%  |
| 27      | 11       | 13.41%  |
| 24      | 11       | 13.41%  |
| 21      | 11       | 13.41%  |
| 20      | 5        | 6.1%    |
| 18      | 5        | 6.1%    |
| 17      | 5        | 6.1%    |
| 19      | 4        | 4.88%   |
| 84      | 2        | 2.44%   |
| 42      | 1        | 1.22%   |
| 40      | 1        | 1.22%   |
| 7       | 1        | 1.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 32       | 39.51%  |
| 401-500     | 23       | 28.4%   |
| Unknown     | 13       | 16.05%  |
| 301-350     | 4        | 4.94%   |
| 351-400     | 3        | 3.7%    |
| 1501-2000   | 2        | 2.47%   |
| 801-900     | 1        | 1.23%   |
| 601-700     | 1        | 1.23%   |
| 101-200     | 1        | 1.23%   |
| 901-1000    | 1        | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 57       | 73.08%  |
| Unknown | 12       | 15.38%  |
| 5/4     | 6        | 7.69%   |
| 16/10   | 2        | 2.56%   |
| 3/2     | 1        | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 30       | 37.04%  |
| Unknown        | 13       | 16.05%  |
| 151-200        | 12       | 14.81%  |
| 301-350        | 11       | 13.58%  |
| 141-150        | 9        | 11.11%  |
| More than 1000 | 2        | 2.47%   |
| 501-1000       | 2        | 2.47%   |
| 1-40           | 1        | 1.23%   |
| 131-140        | 1        | 1.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 46       | 57.5%   |
| 101-120 | 15       | 18.75%  |
| Unknown | 13       | 16.25%  |
| 161-240 | 4        | 5%      |
| 121-160 | 2        | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 71       | 83.53%  |
| 2     | 8        | 9.41%   |
| 0     | 6        | 7.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 56       | 44.8%   |
| Intel                 | 29       | 23.2%   |
| Qualcomm Atheros      | 9        | 7.2%    |
| Ralink Technology     | 8        | 6.4%    |
| Broadcom              | 8        | 6.4%    |
| ASIX Electronics      | 4        | 3.2%    |
| TP-Link               | 3        | 2.4%    |
| Ralink                | 2        | 1.6%    |
| D-Link                | 2        | 1.6%    |
| Samsung Electronics   | 1        | 0.8%    |
| MediaTek              | 1        | 0.8%    |
| ICS Advent            | 1        | 0.8%    |
| Edimax Technology     | 1        | 0.8%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48       | 34.53%  |
| Intel Wi-Fi 6 AX200                                               | 5        | 3.6%    |
| Realtek 802.11ac NIC                                              | 4        | 2.88%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 2.88%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 2.88%   |
| Intel I210 Gigabit Network Connection                             | 3        | 2.16%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.16%   |
| ASIX AX88772A Fast Ethernet                                       | 3        | 2.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.44%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 1.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 1.44%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.44%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.44%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.44%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.44%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.44%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2        | 1.44%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2        | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2        | 1.44%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.72%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.72%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.72%   |
| Ralink RT2070 Wireless Adapter                                    | 1        | 0.72%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.72%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 1        | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.72%   |
| MediaTek TECNO POVA 2                                             | 1        | 0.72%   |
| Intel Wireless 7265                                               | 1        | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 21.95%  |
| Ralink Technology     | 8        | 19.51%  |
| Intel                 | 8        | 19.51%  |
| Qualcomm Atheros      | 4        | 9.76%   |
| Broadcom              | 4        | 9.76%   |
| TP-Link               | 3        | 7.32%   |
| Ralink                | 2        | 4.88%   |
| D-Link                | 2        | 4.88%   |
| Edimax Technology     | 1        | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 5        | 12.2%   |
| Realtek 802.11ac NIC                                           | 4        | 9.76%   |
| Ralink MT7601U Wireless Adapter                                | 4        | 9.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 4.88%   |
| Ralink RT5370 Wireless Adapter                                 | 2        | 4.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 4.88%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2        | 4.88%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2        | 4.88%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 2.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1        | 2.44%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 2.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 2.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 2.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 2.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 2.44%   |
| Ralink RT2070 Wireless Adapter                                 | 1        | 2.44%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1        | 2.44%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 1        | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 2.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 2.44%   |
| Intel Wireless 7265                                            | 1        | 2.44%   |
| Intel Wireless 3165                                            | 1        | 2.44%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 2.44%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 2.44%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter             | 1        | 2.44%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1        | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 53       | 56.38%  |
| Intel                 | 25       | 26.6%   |
| Qualcomm Atheros      | 5        | 5.32%   |
| Broadcom              | 4        | 4.26%   |
| ASIX Electronics      | 4        | 4.26%   |
| Samsung Electronics   | 1        | 1.06%   |
| MediaTek              | 1        | 1.06%   |
| ICS Advent            | 1        | 1.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48       | 48.98%  |
| Intel Ethernet Connection (7) I219-V                              | 4        | 4.08%   |
| Intel I210 Gigabit Network Connection                             | 3        | 3.06%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.06%   |
| ASIX AX88772A Fast Ethernet                                       | 3        | 3.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 2.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 2.04%   |
| Intel I211 Gigabit Network Connection                             | 2        | 2.04%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.04%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.04%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.04%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.04%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2        | 2.04%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.02%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.02%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.02%   |
| MediaTek TECNO POVA 2                                             | 1        | 1.02%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.02%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.02%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 1.02%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.02%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.02%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.02%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1        | 1.02%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1        | 1.02%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.02%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 84       | 68.85%  |
| WiFi     | 38       | 31.15%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 68.18%  |
| WiFi     | 28       | 31.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 60       | 69.77%  |
| 2     | 20       | 23.26%  |
| 3     | 5        | 5.81%   |
| 0     | 1        | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 66       | 76.74%  |
| Yes  | 20       | 23.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 13       | 44.83%  |
| Intel                           | 8        | 27.59%  |
| Realtek Semiconductor           | 2        | 6.9%    |
| Qualcomm Atheros Communications | 2        | 6.9%    |
| Broadcom                        | 2        | 6.9%    |
| Conwise Technology              | 1        | 3.45%   |
| Apple                           | 1        | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13       | 44.83%  |
| Intel AX200 Bluetooth                               | 5        | 17.24%  |
| Realtek Bluetooth Radio                             | 2        | 6.9%    |
| Intel Bluetooth wireless interface                  | 2        | 6.9%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 3.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 3.45%   |
| Intel Bluetooth Device                              | 1        | 3.45%   |
| Conwise CW6622                                      | 1        | 3.45%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1        | 3.45%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1        | 3.45%   |
| Apple Bluetooth Host Controller                     | 1        | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 69       | 46.62%  |
| Nvidia                    | 38       | 25.68%  |
| AMD                       | 26       | 17.57%  |
| C-Media Electronics       | 4        | 2.7%    |
| Creative Labs             | 2        | 1.35%   |
| Shenzhen Rapoo Technology | 1        | 0.68%   |
| Nordic Semiconductor ASA  | 1        | 0.68%   |
| JMTek                     | 1        | 0.68%   |
| GYROCOM C&C               | 1        | 0.68%   |
| Generalplus Technology    | 1        | 0.68%   |
| Elgato Systems            | 1        | 0.68%   |
| Creative Technology       | 1        | 0.68%   |
| Apple                     | 1        | 0.68%   |
| AGPTek                    | 1        | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 7.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 6.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 5.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 4.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8        | 4.79%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 4.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 3.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 3.59%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 2.99%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 2.99%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 2.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 2.4%    |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 1.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.8%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 1.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.8%    |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 1.8%    |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.2%    |
| Nvidia TU102 High Definition Audio Controller                              | 2        | 1.2%    |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 1.2%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.2%    |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.2%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 1.2%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.2%    |
| AMD FCH Azalia Controller                                                  | 2        | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.2%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.2%    |
| Shenzhen Rapoo Technology Rapoo Gaming Headset                             | 1        | 0.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.6%    |
| Nvidia High Definition Audio Controller                                    | 1        | 0.6%    |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.6%    |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.6%    |
| Nvidia GM200 High Definition Audio                                         | 1        | 0.6%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.6%    |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Kingston              | 11       | 20.37%  |
| Corsair               | 10       | 18.52%  |
| Unknown               | 6        | 11.11%  |
| G.Skill               | 6        | 11.11%  |
| Samsung Electronics   | 5        | 9.26%   |
| SK hynix              | 4        | 7.41%   |
| Kingmax               | 4        | 7.41%   |
| Crucial               | 2        | 3.7%    |
| Team                  | 1        | 1.85%   |
| Ramaxel Technology    | 1        | 1.85%   |
| Patriot               | 1        | 1.85%   |
| Micron Technology     | 1        | 1.85%   |
| Kingmax Semiconductor | 1        | 1.85%   |
| A-DATA Technology     | 1        | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s       | 3        | 5.17%   |
| Unknown RAM Module 1GB DIMM 800MT/s                        | 2        | 3.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s               | 1        | 1.72%   |
| Unknown RAM Module 2048MB DIMM DDR2 200MT/s                | 1        | 1.72%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                 | 1        | 1.72%   |
| Unknown RAM BAPC08G3000D4T8 8192MB DIMM DDR4 2133MT/s      | 1        | 1.72%   |
| Team RAM TEAMGROUP-UD3-160 4096MB DIMM DDR3 1333MT/s       | 1        | 1.72%   |
| SK hynix RAM SNOAMOO Ltd:016M00 4096MB DIMM DDR3 1600MT/s  | 1        | 1.72%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s        | 1        | 1.72%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s       | 1        | 1.72%   |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB DIMM DDR3 1600MT/s    | 1        | 1.72%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1        | 1.72%   |
| Samsung RAM M393B2K70CM0-YF8 16GB DIMM DDR3 1067MT/s       | 1        | 1.72%   |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1866MT/s           | 1        | 1.72%   |
| Samsung RAM M393A2K40BB1-CRC 16GB DIMM DDR4 2400MT/s       | 1        | 1.72%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s        | 1        | 1.72%   |
| Ramaxel RAM RMR5040MM58F9F1600 4096MB DIMM DDR3 1600MT/s   | 1        | 1.72%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s             | 1        | 1.72%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 1        | 1.72%   |
| Kingston RAM Module 8GB DIMM DDR4 2667MT/s                 | 1        | 1.72%   |
| Kingston RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 1.72%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 1.72%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 1        | 1.72%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s       | 1        | 1.72%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s        | 1        | 1.72%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s      | 1        | 1.72%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 1.72%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 1.72%   |
| Kingston RAM 9965525-139.A00LF 8192MB DIMM DDR3 1600MT/s   | 1        | 1.72%   |
| Kingston RAM 9965413-002.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 1.72%   |
| Kingston RAM 9905712-008.A00G 16GB SODIMM DDR4 2400MT/s    | 1        | 1.72%   |
| Kingmax RAM GZNH23F-18--------- 16GB DIMM DDR4 2666MT/s    | 1        | 1.72%   |
| Kingmax RAM GLAH22F-18--------- 16384MB DIMM DDR4 2666MT/s | 1        | 1.72%   |
| Kingmax RAM FLGF65F-D8KM 4GB DIMM DDR3 1333MT/s            | 1        | 1.72%   |
| Kingmax RAM FLGE85F-B8KLB 2GB DIMM DDR3 1067MT/s           | 1        | 1.72%   |
| Kingmax RAM FLFF65F-D8KL9 4GB DIMM DDR3 1066MT/s           | 1        | 1.72%   |
| Kingmax RAM FLFF65F-C8KL 4GB DIMM DDR3 1333MT/s            | 1        | 1.72%   |
| Kingmax RAM FLFF65F-C6NG9 4GB DIMM DDR3 1333MT/s           | 1        | 1.72%   |
| G.Skill RAM F4-3600C18-16GTZN 16GB DIMM DDR4 3666MT/s      | 1        | 1.72%   |
| G.Skill RAM F4-3000C16-8GTZR 8GB DIMM DDR4 3200MT/s        | 1        | 1.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 23       | 46.94%  |
| DDR3    | 21       | 42.86%  |
| DDR2    | 2        | 4.08%   |
| Unknown | 2        | 4.08%   |
| DDR     | 1        | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 47       | 95.92%  |
| SODIMM | 2        | 4.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 22       | 42.31%  |
| 4096  | 14       | 26.92%  |
| 16384 | 9        | 17.31%  |
| 1024  | 4        | 7.69%   |
| 2048  | 3        | 5.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 14       | 24.56%  |
| 2400  | 6        | 10.53%  |
| 1333  | 6        | 10.53%  |
| 3200  | 4        | 7.02%   |
| 3000  | 4        | 7.02%   |
| 2667  | 3        | 5.26%   |
| 800   | 3        | 5.26%   |
| 2800  | 2        | 3.51%   |
| 2666  | 2        | 3.51%   |
| 1866  | 2        | 3.51%   |
| 1067  | 2        | 3.51%   |
| 3666  | 1        | 1.75%   |
| 3466  | 1        | 1.75%   |
| 3334  | 1        | 1.75%   |
| 3007  | 1        | 1.75%   |
| 2133  | 1        | 1.75%   |
| 1867  | 1        | 1.75%   |
| 1066  | 1        | 1.75%   |
| 200   | 1        | 1.75%   |
| 133   | 1        | 1.75%   |

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
| Logitech                        | 4        | 50%     |
| Microdia                        | 1        | 12.5%   |
| KYE Systems (Mouse Systems)     | 1        | 12.5%   |
| Intel                           | 1        | 12.5%   |
| IDS Imaging Development Systems | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 3        | 37.5%   |
| Microdia Rapoo Camera                           | 1        | 12.5%   |
| Logitech Webcam C310                            | 1        | 12.5%   |
| KYE Systems (Mouse Systems) JOYACCESS JA-Webcam | 1        | 12.5%   |
| Intel RealSense Depth Camera 435                | 1        | 12.5%   |
| IDS Imaging Development Systems USB 3.0 Camera  | 1        | 12.5%   |

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
| 0     | 78       | 91.76%  |
| 1     | 6        | 7.06%   |
| 2     | 1        | 1.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 3        | 37.5%   |
| Unassigned class         | 2        | 25%     |
| Net/wireless             | 2        | 25%     |
| Communication controller | 1        | 12.5%   |

