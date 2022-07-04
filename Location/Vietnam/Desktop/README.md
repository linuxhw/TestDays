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

Total: 108

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 23       | 29.87%  |
| Ubuntu 18.04                 | 16       | 20.78%  |
| Arch                         | 4        | 5.19%   |
| Ubuntu 16.04                 | 3        | 3.9%    |
| Ubuntu 19.04                 | 2        | 2.6%    |
| Pop!_OS 20.10                | 2        | 2.6%    |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 2.6%    |
| Manjaro 20.2                 | 2        | 2.6%    |
| Debian 10                    | 2        | 2.6%    |
| ArcoLinux Rolling            | 2        | 2.6%    |
| Arch Rolling                 | 2        | 2.6%    |
| Zorin 16                     | 1        | 1.3%    |
| Zorin 15                     | 1        | 1.3%    |
| Xubuntu 20.04                | 1        | 1.3%    |
| Ubuntu 21.04                 | 1        | 1.3%    |
| Parrot 4.11                  | 1        | 1.3%    |
| OpenMandriva 4.2             | 1        | 1.3%    |
| Manjaro 21.0.1               | 1        | 1.3%    |
| Manjaro 20.0.3               | 1        | 1.3%    |
| Manjaro                      | 1        | 1.3%    |
| Linux Mint 20.3              | 1        | 1.3%    |
| Linux Mint 20                | 1        | 1.3%    |
| Kubuntu 20.04                | 1        | 1.3%    |
| KDE neon 20.04               | 1        | 1.3%    |
| Elementary 6                 | 1        | 1.3%    |
| Debian 11                    | 1        | 1.3%    |
| Clear Linux 34500            | 1        | 1.3%    |
| Clear Linux 32260            | 1        | 1.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 43       | 57.33%  |
| Arch         | 6        | 8%      |
| Manjaro      | 5        | 6.67%   |
| Debian       | 3        | 4%      |
| Zorin        | 2        | 2.67%   |
| Pop!_OS      | 2        | 2.67%   |
| openSUSE     | 2        | 2.67%   |
| Linux Mint   | 2        | 2.67%   |
| Clear Linux  | 2        | 2.67%   |
| ArcoLinux    | 2        | 2.67%   |
| Xubuntu      | 1        | 1.33%   |
| Parrot       | 1        | 1.33%   |
| OpenMandriva | 1        | 1.33%   |
| Kubuntu      | 1        | 1.33%   |
| KDE neon     | 1        | 1.33%   |
| Elementary   | 1        | 1.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-58-generic         | 4        | 4.94%   |
| 5.4.0-37-generic         | 3        | 3.7%    |
| 5.4.0-26-generic         | 3        | 3.7%    |
| 5.11.0-38-generic        | 3        | 3.7%    |
| 5.0.0-23-generic         | 3        | 3.7%    |
| 5.9.11-3-MANJARO         | 2        | 2.47%   |
| 5.8.0-7642-generic       | 2        | 2.47%   |
| 5.4.0-48-generic         | 2        | 2.47%   |
| 5.4.0-47-generic         | 2        | 2.47%   |
| 5.4.0-42-generic         | 2        | 2.47%   |
| 5.11.0-37-generic        | 2        | 2.47%   |
| 4.18.0-25-generic        | 2        | 2.47%   |
| 5.9.12-arch1-1           | 1        | 1.23%   |
| 5.9.0-0.bpo.5-amd64      | 1        | 1.23%   |
| 5.8.0-59-generic         | 1        | 1.23%   |
| 5.8.0-55-generic         | 1        | 1.23%   |
| 5.8.0-53-generic         | 1        | 1.23%   |
| 5.8.0-50-generic         | 1        | 1.23%   |
| 5.8.0-45-generic         | 1        | 1.23%   |
| 5.8.0-43-generic         | 1        | 1.23%   |
| 5.6.15-1-MANJARO         | 1        | 1.23%   |
| 5.6.0-1-default          | 1        | 1.23%   |
| 5.4.78-2-pve             | 1        | 1.23%   |
| 5.4.18-902.native        | 1        | 1.23%   |
| 5.4.0-99-generic         | 1        | 1.23%   |
| 5.4.0-90-generic         | 1        | 1.23%   |
| 5.4.0-72-generic         | 1        | 1.23%   |
| 5.4.0-65-generic         | 1        | 1.23%   |
| 5.4.0-52-generic         | 1        | 1.23%   |
| 5.4.0-39-generic         | 1        | 1.23%   |
| 5.4.0-33-generic         | 1        | 1.23%   |
| 5.4.0-31-generic         | 1        | 1.23%   |
| 5.4.0-28-generic         | 1        | 1.23%   |
| 5.17.9-arch1-1           | 1        | 1.23%   |
| 5.17.1-arch1-1           | 1        | 1.23%   |
| 5.15.0-15parrot1-amd64   | 1        | 1.23%   |
| 5.12.8-arch1-1           | 1        | 1.23%   |
| 5.12.8-163-tkg-cacule    | 1        | 1.23%   |
| 5.12.15-arch1-1          | 1        | 1.23%   |
| 5.12.1-arch1-1           | 1        | 1.23%   |
| 5.11.16-1-default        | 1        | 1.23%   |
| 5.11.0-42-generic        | 1        | 1.23%   |
| 5.11.0-41-generic        | 1        | 1.23%   |
| 5.11.0-40-generic        | 1        | 1.23%   |
| 5.11.0-25-generic        | 1        | 1.23%   |
| 5.10.42-1-MANJARO        | 1        | 1.23%   |
| 5.10.26-1-MANJARO        | 1        | 1.23%   |
| 5.10.19-1032.native      | 1        | 1.23%   |
| 5.10.14-desktop-1omv4002 | 1        | 1.23%   |
| 5.10.0-9-amd64           | 1        | 1.23%   |
| 5.0.0-36-generic         | 1        | 1.23%   |
| 5.0.0-25-generic         | 1        | 1.23%   |
| 5.0.0-21-generic         | 1        | 1.23%   |
| 5.0.0-13-generic         | 1        | 1.23%   |
| 4.19.97-1-lts            | 1        | 1.23%   |
| 4.15.18-041518-generic   | 1        | 1.23%   |
| 4.15.0-54-generic        | 1        | 1.23%   |
| 4.15.0-36-generic        | 1        | 1.23%   |
| 4.15.0-166-generic       | 1        | 1.23%   |
| 4.15.0-142-generic       | 1        | 1.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 23       | 29.49%  |
| 5.11.0  | 9        | 11.54%  |
| 5.8.0   | 8        | 10.26%  |
| 5.0.0   | 6        | 7.69%   |
| 4.15.0  | 6        | 7.69%   |
| 5.9.11  | 2        | 2.56%   |
| 5.12.8  | 2        | 2.56%   |
| 4.18.0  | 2        | 2.56%   |
| 5.9.12  | 1        | 1.28%   |
| 5.9.0   | 1        | 1.28%   |
| 5.6.15  | 1        | 1.28%   |
| 5.6.0   | 1        | 1.28%   |
| 5.4.78  | 1        | 1.28%   |
| 5.4.18  | 1        | 1.28%   |
| 5.17.9  | 1        | 1.28%   |
| 5.17.1  | 1        | 1.28%   |
| 5.15.0  | 1        | 1.28%   |
| 5.12.15 | 1        | 1.28%   |
| 5.12.1  | 1        | 1.28%   |
| 5.11.16 | 1        | 1.28%   |
| 5.10.42 | 1        | 1.28%   |
| 5.10.26 | 1        | 1.28%   |
| 5.10.19 | 1        | 1.28%   |
| 5.10.14 | 1        | 1.28%   |
| 5.10.0  | 1        | 1.28%   |
| 4.19.97 | 1        | 1.28%   |
| 4.15.18 | 1        | 1.28%   |
| 4.10.0  | 1        | 1.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 25       | 32.05%  |
| 5.11    | 10       | 12.82%  |
| 5.8     | 8        | 10.26%  |
| 4.15    | 7        | 8.97%   |
| 5.0     | 6        | 7.69%   |
| 5.10    | 5        | 6.41%   |
| 5.9     | 4        | 5.13%   |
| 5.12    | 4        | 5.13%   |
| 5.6     | 2        | 2.56%   |
| 5.17    | 2        | 2.56%   |
| 4.18    | 2        | 2.56%   |
| 5.15    | 1        | 1.28%   |
| 4.19    | 1        | 1.28%   |
| 4.10    | 1        | 1.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 74       | 98.67%  |
| i686   | 1        | 1.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 41       | 53.25%  |
| Unknown    | 16       | 20.78%  |
| KDE5       | 6        | 7.79%   |
| MATE       | 3        | 3.9%    |
| XFCE       | 2        | 2.6%    |
| Unity      | 2        | 2.6%    |
| KDE        | 2        | 2.6%    |
| X-Cinnamon | 1        | 1.3%    |
| Pantheon   | 1        | 1.3%    |
| i3         | 1        | 1.3%    |
| Cinnamon   | 1        | 1.3%    |
| awesome    | 1        | 1.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 58       | 76.32%  |
| Unknown | 9        | 11.84%  |
| Wayland | 6        | 7.89%   |
| Tty     | 3        | 3.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 39       | 51.32%  |
| GDM     | 15       | 19.74%  |
| SDDM    | 6        | 7.89%   |
| LightDM | 6        | 7.89%   |
| TDM     | 5        | 6.58%   |
| GDM3    | 4        | 5.26%   |
| XDM     | 1        | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 60       | 78.95%  |
| Unknown | 10       | 13.16%  |
| vi_VN   | 5        | 6.58%   |
| ru_RU   | 1        | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 39       | 51.32%  |
| EFI  | 37       | 48.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 65       | 85.53%  |
| Overlay | 4        | 5.26%   |
| Btrfs   | 3        | 3.95%   |
| Zfs     | 2        | 2.63%   |
| Unknown | 2        | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 41       | 54.67%  |
| GPT     | 23       | 30.67%  |
| MBR     | 11       | 14.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 80.26%  |
| Yes       | 15       | 19.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 38       | 50%     |
| No        | 38       | 50%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 25       | 33.33%  |
| ASUSTek Computer    | 19       | 25.33%  |
| MSI                 | 9        | 12%     |
| Dell                | 5        | 6.67%   |
| Hewlett-Packard     | 3        | 4%      |
| Wistron             | 2        | 2.67%   |
| Lenovo              | 2        | 2.67%   |
| Foxconn             | 2        | 2.67%   |
| ASRock              | 2        | 2.67%   |
| Shuttle             | 1        | 1.33%   |
| Koloe               | 1        | 1.33%   |
| Intel               | 1        | 1.33%   |
| Huanan              | 1        | 1.33%   |
| Colorful Technology | 1        | 1.33%   |
| Unknown             | 1        | 1.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte H61M-DS2                  | 5        | 6.67%   |
| ASUS All Series                    | 3        | 4%      |
| MSI MS-7B89                        | 2        | 2.67%   |
| MSI MS-7823                        | 2        | 2.67%   |
| Gigabyte G41M-ES2L                 | 2        | 2.67%   |
| ASUS P8H61-MX R2.0                 | 2        | 2.67%   |
| ASUS B75M-A                        | 2        | 2.67%   |
| Wistron FMVDD2A0H0                 | 1        | 1.33%   |
| Wistron FMVCEG40Y                  | 1        | 1.33%   |
| Shuttle DS81D                      | 1        | 1.33%   |
| MSI MS-7C67                        | 1        | 1.33%   |
| MSI MS-7C31                        | 1        | 1.33%   |
| MSI MS-7B98                        | 1        | 1.33%   |
| MSI MS-7A38                        | 1        | 1.33%   |
| MSI MS-7388                        | 1        | 1.33%   |
| Lenovo ThinkCentre M93p 10A8CTO1WW | 1        | 1.33%   |
| Lenovo ThinkCentre M55e 9389AN1    | 1        | 1.33%   |
| Koloe Thurley                      | 1        | 1.33%   |
| Intel DP55WG AAE57269-407          | 1        | 1.33%   |
| Huanan X79 249PC V2.1              | 1        | 1.33%   |
| HP Z620 Workstation                | 1        | 1.33%   |
| HP 500-504x                        | 1        | 1.33%   |
| HP 251-152l                        | 1        | 1.33%   |
| Gigabyte Z97X-UD3H                 | 1        | 1.33%   |
| Gigabyte Z390 UD                   | 1        | 1.33%   |
| Gigabyte Z170-D3H                  | 1        | 1.33%   |
| Gigabyte P110-D3                   | 1        | 1.33%   |
| Gigabyte H81M-DS2                  | 1        | 1.33%   |
| Gigabyte H170-Gaming 3             | 1        | 1.33%   |
| Gigabyte GB-BXBT-2807              | 1        | 1.33%   |
| Gigabyte G1.Sniper B5              | 1        | 1.33%   |
| Gigabyte F2A68HM-HD2               | 1        | 1.33%   |
| Gigabyte EP43T-S3L                 | 1        | 1.33%   |
| Gigabyte EG31MF-S2                 | 1        | 1.33%   |
| Gigabyte B85M-DS3H                 | 1        | 1.33%   |
| Gigabyte B75M-D3H                  | 1        | 1.33%   |
| Gigabyte B450M GAMING              | 1        | 1.33%   |
| Gigabyte B450 AORUS ELITE          | 1        | 1.33%   |
| Gigabyte B360M AORUS Gaming 3      | 1        | 1.33%   |
| Gigabyte B360 M AORUS PRO          | 1        | 1.33%   |
| Gigabyte B250M-D2V                 | 1        | 1.33%   |
| Foxconn p6-2241l                   | 1        | 1.33%   |
| Foxconn H61MD/H61MD-V              | 1        | 1.33%   |
| Dell Vostro 200                    | 1        | 1.33%   |
| Dell Precision Tower 7910          | 1        | 1.33%   |
| Dell OptiPlex 780                  | 1        | 1.33%   |
| Dell OptiPlex 3060                 | 1        | 1.33%   |
| Dell Inspiron 3847                 | 1        | 1.33%   |
| Colorful C.A68M-BTC YV14           | 1        | 1.33%   |
| ASUS Z10PE-D8 WS                   | 1        | 1.33%   |
| ASUS SABERTOOTH Z77                | 1        | 1.33%   |
| ASUS ROG STRIX Z390-F GAMING       | 1        | 1.33%   |
| ASUS PRIME Z370-P                  | 1        | 1.33%   |
| ASUS PRIME X370-PRO                | 1        | 1.33%   |
| ASUS PRIME H110M-P                 | 1        | 1.33%   |
| ASUS PRIME B250M-K                 | 1        | 1.33%   |
| ASUS P9X79 WS                      | 1        | 1.33%   |
| ASUS P8H61-MX                      | 1        | 1.33%   |
| ASUS P7H55-M LX                    | 1        | 1.33%   |
| ASUS EB1036                        | 1        | 1.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Gigabyte H61M-DS2     | 5        | 6.67%   |
| ASUS PRIME            | 4        | 5.33%   |
| ASUS P8H61-MX         | 3        | 4%      |
| ASUS All              | 3        | 4%      |
| MSI MS-7B89           | 2        | 2.67%   |
| MSI MS-7823           | 2        | 2.67%   |
| Lenovo ThinkCentre    | 2        | 2.67%   |
| Gigabyte G41M-ES2L    | 2        | 2.67%   |
| Dell OptiPlex         | 2        | 2.67%   |
| ASUS B75M-A           | 2        | 2.67%   |
| Wistron FMVDD2A0H0    | 1        | 1.33%   |
| Wistron FMVCEG40Y     | 1        | 1.33%   |
| Shuttle DS81D         | 1        | 1.33%   |
| MSI MS-7C67           | 1        | 1.33%   |
| MSI MS-7C31           | 1        | 1.33%   |
| MSI MS-7B98           | 1        | 1.33%   |
| MSI MS-7A38           | 1        | 1.33%   |
| MSI MS-7388           | 1        | 1.33%   |
| Koloe Thurley         | 1        | 1.33%   |
| Intel DP55WG          | 1        | 1.33%   |
| Huanan X79            | 1        | 1.33%   |
| HP Z620               | 1        | 1.33%   |
| HP 500-504x           | 1        | 1.33%   |
| HP 251-152l           | 1        | 1.33%   |
| Gigabyte Z97X-UD3H    | 1        | 1.33%   |
| Gigabyte Z390         | 1        | 1.33%   |
| Gigabyte Z170-D3H     | 1        | 1.33%   |
| Gigabyte P110-D3      | 1        | 1.33%   |
| Gigabyte H81M-DS2     | 1        | 1.33%   |
| Gigabyte H170-Gaming  | 1        | 1.33%   |
| Gigabyte GB-BXBT-2807 | 1        | 1.33%   |
| Gigabyte G1.Sniper    | 1        | 1.33%   |
| Gigabyte F2A68HM-HD2  | 1        | 1.33%   |
| Gigabyte EP43T-S3L    | 1        | 1.33%   |
| Gigabyte EG31MF-S2    | 1        | 1.33%   |
| Gigabyte B85M-DS3H    | 1        | 1.33%   |
| Gigabyte B75M-D3H     | 1        | 1.33%   |
| Gigabyte B450M        | 1        | 1.33%   |
| Gigabyte B450         | 1        | 1.33%   |
| Gigabyte B360M        | 1        | 1.33%   |
| Gigabyte B360         | 1        | 1.33%   |
| Gigabyte B250M-D2V    | 1        | 1.33%   |
| Foxconn p6-2241l      | 1        | 1.33%   |
| Foxconn H61MD         | 1        | 1.33%   |
| Dell Vostro           | 1        | 1.33%   |
| Dell Precision        | 1        | 1.33%   |
| Dell Inspiron         | 1        | 1.33%   |
| Colorful C.A68M-BTC   | 1        | 1.33%   |
| ASUS Z10PE-D8         | 1        | 1.33%   |
| ASUS SABERTOOTH       | 1        | 1.33%   |
| ASUS ROG              | 1        | 1.33%   |
| ASUS P9X79            | 1        | 1.33%   |
| ASUS P7H55-M          | 1        | 1.33%   |
| ASUS EB1036           | 1        | 1.33%   |
| ASUS A68HM-K          | 1        | 1.33%   |
| ASRock G41M-VS3       | 1        | 1.33%   |
| ASRock AOD790GX       | 1        | 1.33%   |
| Unknown               | 1        | 1.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 12       | 16%     |
| 2012 | 12       | 16%     |
| 2014 | 10       | 13.33%  |
| 2013 | 8        | 10.67%  |
| 2010 | 7        | 9.33%   |
| 2019 | 5        | 6.67%   |
| 2017 | 5        | 6.67%   |
| 2009 | 4        | 5.33%   |
| 2016 | 3        | 4%      |
| 2015 | 3        | 4%      |
| 2020 | 2        | 2.67%   |
| 2011 | 1        | 1.33%   |
| 2008 | 1        | 1.33%   |
| 2007 | 1        | 1.33%   |
| 2006 | 1        | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 75       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 71       | 94.67%  |
| Enabled  | 4        | 5.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 75       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 20       | 26.32%  |
| 16.01-24.0  | 16       | 21.05%  |
| 3.01-4.0    | 14       | 18.42%  |
| 4.01-8.0    | 8        | 10.53%  |
| 32.01-64.0  | 7        | 9.21%   |
| 1.01-2.0    | 7        | 9.21%   |
| 24.01-32.0  | 3        | 3.95%   |
| 64.01-256.0 | 1        | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 29       | 38.16%  |
| 2.01-3.0  | 23       | 30.26%  |
| 3.01-4.0  | 10       | 13.16%  |
| 4.01-8.0  | 8        | 10.53%  |
| 8.01-16.0 | 4        | 5.26%   |
| 0.51-1.0  | 1        | 1.32%   |
| 0.01-0.5  | 1        | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 33       | 43.42%  |
| 1      | 26       | 34.21%  |
| 3      | 9        | 11.84%  |
| 4      | 5        | 6.58%   |
| 9      | 1        | 1.32%   |
| 5      | 1        | 1.32%   |
| 0      | 1        | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 76%     |
| Yes       | 18       | 24%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 74       | 98.67%  |
| No        | 1        | 1.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 60%     |
| Yes       | 30       | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 68.42%  |
| Yes       | 24       | 31.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Vietnam | 75       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Ho Chi Minh City | 41       | 54.67%  |
| Hanoi            | 18       | 24%     |
| Nga Bay          | 2        | 2.67%   |
| Vũng Tàu       | 1        | 1.33%   |
| Vi Thanh         | 1        | 1.33%   |
| Tay Ninh         | 1        | 1.33%   |
| Quảng Ngai     | 1        | 1.33%   |
| Nha Trang        | 1        | 1.33%   |
| Nam Định      | 1        | 1.33%   |
| Haiphong         | 1        | 1.33%   |
| Hai Duong        | 1        | 1.33%   |
| Di An            | 1        | 1.33%   |
| Da Nang          | 1        | 1.33%   |
| Can Tho          | 1        | 1.33%   |
| Bien Hoa         | 1        | 1.33%   |
| Bến Tre        | 1        | 1.33%   |
| Bac Giang        | 1        | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 37       | 46     | 28.03%  |
| Seagate               | 25       | 32     | 18.94%  |
| Samsung Electronics   | 11       | 12     | 8.33%   |
| Toshiba               | 7        | 12     | 5.3%    |
| Kingston              | 7        | 8      | 5.3%    |
| Intel                 | 4        | 4      | 3.03%   |
| SanDisk               | 3        | 3      | 2.27%   |
| Lexar                 | 3        | 3      | 2.27%   |
| Hitachi               | 3        | 3      | 2.27%   |
| Crucial               | 3        | 6      | 2.27%   |
| Colorful              | 3        | 3      | 2.27%   |
| ZOTAC                 | 2        | 2      | 1.52%   |
| Unknown               | 2        | 2      | 1.52%   |
| TO Exter              | 2        | 3      | 1.52%   |
| OCZ                   | 2        | 2      | 1.52%   |
| Netac                 | 2        | 2      | 1.52%   |
| HGST                  | 2        | 2      | 1.52%   |
| Fujitsu               | 2        | 2      | 1.52%   |
| Vaseky                | 1        | 1      | 0.76%   |
| Transcend             | 1        | 1      | 0.76%   |
| Realtek Semiconductor | 1        | 2      | 0.76%   |
| Phison                | 1        | 2      | 0.76%   |
| Micron Technology     | 1        | 1      | 0.76%   |
| Maxtor                | 1        | 1      | 0.76%   |
| Lite-On               | 1        | 1      | 0.76%   |
| KING                  | 1        | 1      | 0.76%   |
| Gigabyte Technology   | 1        | 1      | 0.76%   |
| External              | 1        | 1      | 0.76%   |
| EK                    | 1        | 1      | 0.76%   |
| BR                    | 1        | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD  | 4        | 2.84%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 3        | 2.13%   |
| WDC WD2500AAKX-00ERMA0 250GB      | 3        | 2.13%   |
| Seagate ST1000DM010-2EP102 1TB    | 3        | 2.13%   |
| Kingston SA400S37240G 240GB SSD   | 3        | 2.13%   |
| ZOTAC SATA SSD 120GB              | 2        | 1.42%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 2        | 1.42%   |
| WDC WD3200AAKX-001CA0 320GB       | 2        | 1.42%   |
| Toshiba DT01ABA100V 1TB           | 2        | 1.42%   |
| TO Exter nal USB 3.0 256GB        | 2        | 1.42%   |
| Seagate ST500DM002-1BD142 500GB   | 2        | 1.42%   |
| Seagate ST2000DM006-2DM164 2TB    | 2        | 1.42%   |
| Seagate ST1000DM003-1ER162 1TB    | 2        | 1.42%   |
| Samsung SSD 860 EVO 500GB         | 2        | 1.42%   |
| Samsung SSD 860 EVO 250GB         | 2        | 1.42%   |
| Samsung SSD 860 EVO 1TB           | 2        | 1.42%   |
| Samsung SSD 750 EVO 120GB         | 2        | 1.42%   |
| Lexar 128GB SSD                   | 2        | 1.42%   |
| Crucial CT250MX500SSD1 250GB      | 2        | 1.42%   |
| WDC WDS500G2B0C-00PXH0 500GB      | 1        | 0.71%   |
| WDC WDS250G2B0A-00SM50 250GB SSD  | 1        | 0.71%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 0.71%   |
| WDC WDS120G1G0A-00SS50 120GB SSD  | 1        | 0.71%   |
| WDC WDS100T3X0C-00SJG0 1TB        | 1        | 0.71%   |
| WDC WD80EFBX-68AZZN0 8TB          | 1        | 0.71%   |
| WDC WD80 03FFBX-68B9AN0 8TB       | 1        | 0.71%   |
| WDC WD60PURX-64T0ZY0 6TB          | 1        | 0.71%   |
| WDC WD5000LPVX-75V0TT0 500GB      | 1        | 0.71%   |
| WDC WD5000AZLX-75K2TA0 500GB      | 1        | 0.71%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 0.71%   |
| WDC WD40EZRZ-00GXCB0 4TB          | 1        | 0.71%   |
| WDC WD3200BPVT-75ZEST0 320GB      | 1        | 0.71%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1        | 0.71%   |
| WDC WD3200AAJS-56M0A0 320GB       | 1        | 0.71%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1        | 0.71%   |
| WDC WD2500JS-60MHB5 250GB         | 1        | 0.71%   |
| WDC WD2500AAKX-60U6AA0 250GB      | 1        | 0.71%   |
| WDC WD2002FAEX-007BA0 2TB         | 1        | 0.71%   |
| WDC WD10EZEX-75WN4A0 1TB          | 1        | 0.71%   |
| WDC WD10EZEX-75M2NA0 1TB          | 1        | 0.71%   |
| WDC WD10EZEX-22MFCA0 1TB          | 1        | 0.71%   |
| WDC WD10EZEX-08WN4A0 1TB          | 1        | 0.71%   |
| WDC WD10EZEX-00RKKA0 1TB          | 1        | 0.71%   |
| WDC WD10EZEX-00BBHA0 1TB          | 1        | 0.71%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 0.71%   |
| WDC WD1003FZEX-00K3CA0 1TB        | 1        | 0.71%   |
| WDC WD1000DHTZ-04N21V0 1TB        | 1        | 0.71%   |
| WDC PC SN720 SED SDAQNTW-1T00 1TB | 1        | 0.71%   |
| Vaseky V800/120G 120GB            | 1        | 0.71%   |
| Unknown TP02000GB 2TB             | 1        | 0.71%   |
| Unknown SD/MMC/MS PRO 128GB       | 1        | 0.71%   |
| Transcend TS256GSSD230S 256GB     | 1        | 0.71%   |
| Toshiba THNSNH128GCST 128GB SSD   | 1        | 0.71%   |
| Toshiba MQ01ABF050 500GB          | 1        | 0.71%   |
| Toshiba HDWD120 2TB               | 1        | 0.71%   |
| Toshiba DT01ACA100 1TB            | 1        | 0.71%   |
| Toshiba DT01ACA050 500GB          | 1        | 0.71%   |
| Seagate ST8000DM004-2CX188 8TB    | 1        | 0.71%   |
| Seagate ST500DM002-1SB10A 500GB   | 1        | 0.71%   |
| Seagate ST500DM002-1ER14C 500GB   | 1        | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 27       | 34     | 40.91%  |
| Seagate | 25       | 32     | 37.88%  |
| Toshiba | 6        | 11     | 9.09%   |
| Hitachi | 3        | 3      | 4.55%   |
| HGST    | 2        | 2      | 3.03%   |
| Fujitsu | 2        | 2      | 3.03%   |
| Unknown | 1        | 1      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 11     | 18.18%  |
| WDC                 | 9        | 9      | 16.36%  |
| Kingston            | 7        | 8      | 12.73%  |
| Intel               | 4        | 4      | 7.27%   |
| SanDisk             | 3        | 3      | 5.45%   |
| Lexar               | 3        | 3      | 5.45%   |
| Crucial             | 3        | 4      | 5.45%   |
| ZOTAC               | 2        | 2      | 3.64%   |
| TO Exter            | 2        | 3      | 3.64%   |
| Netac               | 2        | 2      | 3.64%   |
| Colorful            | 2        | 2      | 3.64%   |
| Vaseky              | 1        | 1      | 1.82%   |
| Transcend           | 1        | 1      | 1.82%   |
| Toshiba             | 1        | 1      | 1.82%   |
| OCZ                 | 1        | 1      | 1.82%   |
| Micron Technology   | 1        | 1      | 1.82%   |
| Maxtor              | 1        | 1      | 1.82%   |
| Gigabyte Technology | 1        | 1      | 1.82%   |
| EK                  | 1        | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 55       | 85     | 47.83%  |
| SSD     | 46       | 59     | 40%     |
| NVMe    | 10       | 13     | 8.7%    |
| Unknown | 4        | 4      | 3.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 70       | 141    | 83.33%  |
| NVMe | 9        | 12     | 10.71%  |
| SAS  | 5        | 8      | 5.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 62       | 93     | 65.26%  |
| 0.51-1.0   | 20       | 29     | 21.05%  |
| 1.01-2.0   | 6        | 8      | 6.32%   |
| 4.01-10.0  | 5        | 12     | 5.26%   |
| 3.01-4.0   | 1        | 1      | 1.05%   |
| 2.01-3.0   | 1        | 1      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 27       | 35.06%  |
| 501-1000       | 13       | 16.88%  |
| 251-500        | 9        | 11.69%  |
| 1001-2000      | 6        | 7.79%   |
| More than 3000 | 5        | 6.49%   |
| 1-20           | 5        | 6.49%   |
| 21-50          | 4        | 5.19%   |
| 2001-3000      | 3        | 3.9%    |
| 51-100         | 3        | 3.9%    |
| Unknown        | 2        | 2.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 33       | 43.42%  |
| 51-100         | 10       | 13.16%  |
| 21-50          | 9        | 11.84%  |
| 501-1000       | 6        | 7.89%   |
| 251-500        | 5        | 6.58%   |
| 101-250        | 4        | 5.26%   |
| More than 3000 | 3        | 3.95%   |
| 2001-3000      | 2        | 2.63%   |
| 1001-2000      | 2        | 2.63%   |
| Unknown        | 2        | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD3200AAKX-001CA0 320GB     | 2        | 2      | 20%     |
| WDC WD1003FZEX-00MK2A0 1TB      | 1        | 1      | 10%     |
| Transcend TS256GSSD230S 256GB   | 1        | 1      | 10%     |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 10%     |
| Seagate ST1000DM003-1ER162 1TB  | 1        | 1      | 10%     |
| Intel SSDSC2CW120A3 120GB       | 1        | 1      | 10%     |
| Hitachi HUA722020ALA331 2TB     | 1        | 1      | 10%     |
| HGST HTS725050A7E630 500GB      | 1        | 1      | 10%     |
| Fujitsu MHK2120AT 12GB          | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor    | Desktops | Drives | Percent |
|-----------|----------|--------|---------|
| WDC       | 3        | 3      | 30%     |
| Seagate   | 2        | 2      | 20%     |
| Transcend | 1        | 1      | 10%     |
| Intel     | 1        | 1      | 10%     |
| Hitachi   | 1        | 1      | 10%     |
| HGST      | 1        | 1      | 10%     |
| Fujitsu   | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 37.5%   |
| Seagate | 2        | 2      | 25%     |
| Hitachi | 1        | 1      | 12.5%   |
| HGST    | 1        | 1      | 12.5%   |
| Fujitsu | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 8      | 88.89%  |
| SSD  | 1        | 2      | 11.11%  |

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
| Detected | 41       | 83     | 49.4%   |
| Works    | 34       | 68     | 40.96%  |
| Malfunc  | 8        | 10     | 9.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 64       | 71.11%  |
| AMD                       | 11       | 12.22%  |
| SanDisk                   | 3        | 3.33%   |
| ASMedia Technology        | 3        | 3.33%   |
| Samsung Electronics       | 1        | 1.11%   |
| Realtek Semiconductor     | 1        | 1.11%   |
| Phison Electronics        | 1        | 1.11%   |
| OCZ Technology Group      | 1        | 1.11%   |
| Micron/Crucial Technology | 1        | 1.11%   |
| Marvell Technology Group  | 1        | 1.11%   |
| LSI Logic / Symbios Logic | 1        | 1.11%   |
| Lite-On Technology        | 1        | 1.11%   |
| JMicron Technology        | 1        | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 10.71%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 7.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 5.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 4.46%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 4.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 4.46%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 3.57%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 2.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.68%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.68%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.79%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.79%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.89%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.89%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.89%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.89%   |
| Phison NVMe Storage Controller                                                          | 1        | 0.89%   |
| OCZ Group RD400/400A SSD                                                                | 1        | 0.89%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.89%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.89%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                                    | 1        | 0.89%   |
| Lite-On Non-Volatile memory controller                                                  | 1        | 0.89%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.89%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.89%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.89%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.89%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.89%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.89%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.89%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 0.89%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 0.89%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 57       | 64.04%  |
| IDE  | 19       | 21.35%  |
| NVMe | 9        | 10.11%  |
| RAID | 3        | 3.37%   |
| SAS  | 1        | 1.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 64       | 85.33%  |
| AMD    | 11       | 14.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz                | 4        | 5.33%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 4        | 5.33%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 3        | 4%      |
| Intel Core i5-4460 CPU @ 3.20GHz                | 3        | 4%      |
| Intel Core i7-4790K CPU @ 4.00GHz               | 2        | 2.67%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 2        | 2.67%   |
| Intel Core i5-2500 CPU @ 3.30GHz                | 2        | 2.67%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 2        | 2.67%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 2        | 2.67%   |
| Intel Core i3 CPU 540 @ 3.07GHz                 | 2        | 2.67%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 2        | 2.67%   |
| AMD Ryzen 5 3600 6-Core Processor               | 2        | 2.67%   |
| Intel Xeon CPU X5570 @ 2.93GHz                  | 1        | 1.33%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz              | 1        | 1.33%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz             | 1        | 1.33%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz              | 1        | 1.33%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz             | 1        | 1.33%   |
| Intel Xeon CPU E31235 @ 3.20GHz                 | 1        | 1.33%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz             | 1        | 1.33%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 1.33%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz          | 1        | 1.33%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1        | 1.33%   |
| Intel Pentium CPU G2020 @ 2.90GHz               | 1        | 1.33%   |
| Intel Core i9-9900KF CPU @ 3.60GHz              | 1        | 1.33%   |
| Intel Core i7-9700F CPU @ 3.00GHz               | 1        | 1.33%   |
| Intel Core i7-7700T CPU @ 2.90GHz               | 1        | 1.33%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 1        | 1.33%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 1.33%   |
| Intel Core i7-3930K CPU @ 3.20GHz               | 1        | 1.33%   |
| Intel Core i5-9600K CPU @ 3.70GHz               | 1        | 1.33%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1        | 1.33%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1        | 1.33%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1        | 1.33%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 1        | 1.33%   |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1        | 1.33%   |
| Intel Core i5-4670 CPU @ 3.40GHz                | 1        | 1.33%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1        | 1.33%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 1.33%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 1        | 1.33%   |
| Intel Core i5-3570K CPU @ 3.40GHz               | 1        | 1.33%   |
| Intel Core i5 CPU 650 @ 3.20GHz                 | 1        | 1.33%   |
| Intel Core i3-9100 CPU @ 3.60GHz                | 1        | 1.33%   |
| Intel Core i3-7100 CPU @ 3.90GHz                | 1        | 1.33%   |
| Intel Core i3-3225 CPU @ 3.30GHz                | 1        | 1.33%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 1        | 1.33%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz            | 1        | 1.33%   |
| Intel Celeron CPU N2807 @ 1.58GHz               | 1        | 1.33%   |
| Intel Celeron CPU J1900 @ 1.99GHz               | 1        | 1.33%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics      | 1        | 1.33%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 1.33%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 1        | 1.33%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1        | 1.33%   |
| AMD Phenom II X4 20 Processor                   | 1        | 1.33%   |
| AMD Athlon II X2 240 Processor                  | 1        | 1.33%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G   | 1        | 1.33%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.33%   |
| AMD A10-5800K APU with Radeon HD Graphics       | 1        | 1.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 26       | 34.67%  |
| Intel Core i3           | 10       | 13.33%  |
| Intel Xeon              | 7        | 9.33%   |
| Intel Core i7           | 7        | 9.33%   |
| Intel Core 2 Duo        | 7        | 9.33%   |
| AMD Ryzen 5             | 4        | 5.33%   |
| Intel Pentium           | 2        | 2.67%   |
| Intel Celeron           | 2        | 2.67%   |
| AMD A10                 | 2        | 2.67%   |
| Intel Pentium Dual-Core | 1        | 1.33%   |
| Intel Pentium Dual      | 1        | 1.33%   |
| Intel Core i9           | 1        | 1.33%   |
| AMD Ryzen 7 PRO         | 1        | 1.33%   |
| AMD Ryzen 3             | 1        | 1.33%   |
| AMD Phenom II X4        | 1        | 1.33%   |
| AMD Athlon II X2        | 1        | 1.33%   |
| AMD A8                  | 1        | 1.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 32       | 42.67%  |
| 2      | 26       | 34.67%  |
| 6      | 10       | 13.33%  |
| 8      | 4        | 5.33%   |
| 28     | 1        | 1.33%   |
| 24     | 1        | 1.33%   |
| 16     | 1        | 1.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 72       | 96%     |
| 2      | 3        | 4%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 44       | 58.67%  |
| 2      | 31       | 41.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 74       | 98.67%  |
| Unknown        | 1        | 1.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 18.67%  |
| 0x306c3    | 9        | 12%     |
| 0x306a9    | 7        | 9.33%   |
| 0x1067a    | 7        | 9.33%   |
| 0x206a7    | 5        | 6.67%   |
| 0x906ea    | 4        | 5.33%   |
| 0x906e9    | 3        | 4%      |
| 0x206d7    | 3        | 4%      |
| 0x906ed    | 2        | 2.67%   |
| 0x506e3    | 2        | 2.67%   |
| 0x30678    | 2        | 2.67%   |
| 0x20655    | 2        | 2.67%   |
| 0x06003106 | 2        | 2.67%   |
| 0x906eb    | 1        | 1.33%   |
| 0x6fd      | 1        | 1.33%   |
| 0x406f1    | 1        | 1.33%   |
| 0x306f2    | 1        | 1.33%   |
| 0x106a5    | 1        | 1.33%   |
| 0x10676    | 1        | 1.33%   |
| 0x08701021 | 1        | 1.33%   |
| 0x08701013 | 1        | 1.33%   |
| 0x08108109 | 1        | 1.33%   |
| 0x0810100b | 1        | 1.33%   |
| 0x06001119 | 1        | 1.33%   |
| 0x010000db | 1        | 1.33%   |
| 0x010000c7 | 1        | 1.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 15       | 20%     |
| KabyLake    | 13       | 17.33%  |
| IvyBridge   | 9        | 12%     |
| SandyBridge | 8        | 10.67%  |
| Penryn      | 8        | 10.67%  |
| Zen 2       | 3        | 4%      |
| Westmere    | 3        | 4%      |
| Skylake     | 3        | 4%      |
| Zen+        | 2        | 2.67%   |
| Steamroller | 2        | 2.67%   |
| Silvermont  | 2        | 2.67%   |
| K10         | 2        | 2.67%   |
| Zen         | 1        | 1.33%   |
| Piledriver  | 1        | 1.33%   |
| Nehalem     | 1        | 1.33%   |
| Core        | 1        | 1.33%   |
| Broadwell   | 1        | 1.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 34       | 40.48%  |
| Intel             | 30       | 35.71%  |
| AMD               | 19       | 22.62%  |
| ASPEED Technology | 1        | 1.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 8.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 6.98%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 5.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.49%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 3.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.49%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 3.49%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 2.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 2.33%   |
| Intel HD Graphics 630                                                       | 2        | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 2.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.33%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 2.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.16%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.16%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 1.16%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 1.16%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.16%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 1.16%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.16%   |
| Nvidia GP106 [GeForce GTX 1060 6GB Rev. 2]                                  | 1        | 1.16%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1        | 1.16%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.16%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.16%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 1.16%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.16%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.16%   |
| Nvidia GK208 [GeForce GT 710]                                               | 1        | 1.16%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.16%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.16%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 1.16%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 1        | 1.16%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.16%   |
| Intel HD Graphics 530                                                       | 1        | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.16%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 1        | 1.16%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.16%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.16%   |
| AMD Trinity [Radeon HD 7660D]                                               | 1        | 1.16%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 1        | 1.16%   |
| AMD RS780D [Radeon HD 3300]                                                 | 1        | 1.16%   |
| AMD Renoir                                                                  | 1        | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.16%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.16%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.16%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 1.16%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.16%   |
| AMD Cape Verde LE [Radeon HD 7730/8730]                                     | 1        | 1.16%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 1.16%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 27       | 36%     |
| 1 x Intel       | 22       | 29.33%  |
| 1 x AMD         | 19       | 25.33%  |
| Intel + Nvidia  | 6        | 8%      |
| Nvidia + ASPEED | 1        | 1.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 49       | 65.33%  |
| Proprietary | 26       | 34.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 36%     |
| 1.01-2.0   | 16       | 21.33%  |
| 3.01-4.0   | 10       | 13.33%  |
| 0.51-1.0   | 6        | 8%      |
| 7.01-8.0   | 5        | 6.67%   |
| 0.01-0.5   | 5        | 6.67%   |
| 5.01-6.0   | 3        | 4%      |
| 8.01-16.0  | 3        | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 23       | 31.94%  |
| Samsung Electronics  | 14       | 19.44%  |
| Goldstar             | 7        | 9.72%   |
| Ancor Communications | 4        | 5.56%   |
| Panasonic            | 3        | 4.17%   |
| Hewlett-Packard      | 3        | 4.17%   |
| AOC                  | 3        | 4.17%   |
| ViewSonic            | 2        | 2.78%   |
| BenQ                 | 2        | 2.78%   |
| Unknown (ADA)        | 1        | 1.39%   |
| Sony                 | 1        | 1.39%   |
| Philips              | 1        | 1.39%   |
| NEC Computers        | 1        | 1.39%   |
| LG Electronics       | 1        | 1.39%   |
| Lenovo Group Limited | 1        | 1.39%   |
| Lenovo               | 1        | 1.39%   |
| HOP                  | 1        | 1.39%   |
| CGC                  | 1        | 1.39%   |
| AUS                  | 1        | 1.39%   |
| Acer                 | 1        | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Panasonic TV MEIC33B 1366x768 521x293mm 23.5-inch                       | 3        | 3.95%   |
| Samsung Electronics SME1720NR SAM0696 1280x1024 338x270mm 17.0-inch     | 2        | 2.63%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                    | 2        | 2.63%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                       | 2        | 2.63%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 477x268mm 21.5-inch              | 1        | 1.32%   |
| ViewSonic VA2201-FHD VSC683B 1920x1080 480x260mm 21.5-inch              | 1        | 1.32%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch           | 1        | 1.32%   |
| Sony TV SNY8E03 1920x1080                                               | 1        | 1.32%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 1        | 1.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 1.32%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 1.32%   |
| Samsung Electronics S20D300 SAM0B39 1600x900 432x240mm 19.5-inch        | 1        | 1.32%   |
| Samsung Electronics S20B370 SAM08B7 1600x900 443x249mm 20.0-inch        | 1        | 1.32%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch        | 1        | 1.32%   |
| Samsung Electronics S19C170 SAM0B02 1366x768 410x230mm 18.5-inch        | 1        | 1.32%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 1        | 1.32%   |
| Samsung Electronics LCD Monitor SME1720NR 1280x1024                     | 1        | 1.32%   |
| Samsung Electronics LCD Monitor SMB1930N                                | 1        | 1.32%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 1872x1053mm 84.6-inch | 1        | 1.32%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 890x500mm 40.2-inch   | 1        | 1.32%   |
| Samsung Electronics LCD Monitor SAM0658 1920x1080 886x498mm 40.0-inch   | 1        | 1.32%   |
| Philips 24PHT4003S/74 PHT4003 1360x768 525x297mm 23.7-inch              | 1        | 1.32%   |
| NEC Computers LCD172VXM NEC67C5 1280x1024 338x270mm 17.0-inch           | 1        | 1.32%   |
| LG Electronics LCD Monitor MP59G                                        | 1        | 1.32%   |
| Lenovo LEN L1900pA LEN114F 1280x1024 376x301mm 19.0-inch                | 1        | 1.32%   |
| Lenovo Group Limited LCD Monitor LEN L1900pA 1280x1024                  | 1        | 1.32%   |
| HOP DVI HOP2700 1920x1080 597x336mm 27.0-inch                           | 1        | 1.32%   |
| Hewlett-Packard w1707 HWP2800 1440x900 370x230mm 17.2-inch              | 1        | 1.32%   |
| Hewlett-Packard N220 HPN3408 1920x1080 476x268mm 21.5-inch              | 1        | 1.32%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch             | 1        | 1.32%   |
| Goldstar W2043 GSM4E9E 1600x900 443x249mm 20.0-inch                     | 1        | 1.32%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch                | 1        | 1.32%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 1        | 1.32%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                  | 1        | 1.32%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                  | 1        | 1.32%   |
| Dell U4320Q DEL41D4 3840x2160 941x529mm 42.5-inch                       | 1        | 1.32%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                       | 1        | 1.32%   |
| Dell U2419H DEL4148 1920x1080 527x296mm 23.8-inch                       | 1        | 1.32%   |
| Dell U2414H DELA0B2 1920x1080 527x296mm 23.8-inch                       | 1        | 1.32%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                       | 1        | 1.32%   |
| Dell U2311H DELA05E 1920x1080 509x286mm 23.0-inch                       | 1        | 1.32%   |
| Dell S2340L DELD058 1920x1080 510x290mm 23.1-inch                       | 1        | 1.32%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                       | 1        | 1.32%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                       | 1        | 1.32%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                       | 1        | 1.32%   |
| Dell P2314H DEL409A 1920x1080 509x286mm 23.0-inch                       | 1        | 1.32%   |
| Dell P2314H DEL4099 1920x1080 510x290mm 23.1-inch                       | 1        | 1.32%   |
| Dell P2012H DEL4079 1600x900 443x249mm 20.0-inch                        | 1        | 1.32%   |
| Dell LCD Monitor U2718Q 3840x2160                                       | 1        | 1.32%   |
| Dell LCD Monitor U2518D 2560x1440                                       | 1        | 1.32%   |
| Dell LCD Monitor S2319H 1920x1080                                       | 1        | 1.32%   |
| Dell LCD Monitor P2717H 1920x1080                                       | 1        | 1.32%   |
| Dell LCD Monitor E2314H 3286x1080                                       | 1        | 1.32%   |
| Dell IN2030M DELF03D 1600x900 443x249mm 20.0-inch                       | 1        | 1.32%   |
| Dell E2414H DEL4091 1920x1080 531x299mm 24.0-inch                       | 1        | 1.32%   |
| Dell E2318H DELF092 1920x1080 509x286mm 23.0-inch                       | 1        | 1.32%   |
| Dell E2016H DELA0C7 1600x900 432x236mm 19.4-inch                        | 1        | 1.32%   |
| Dell E197FP DELA024 1280x1024 380x305mm 19.2-inch                       | 1        | 1.32%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                       | 1        | 1.32%   |
| CGC Z2788P CGC2788 1920x1080 598x336mm 27.0-inch                        | 1        | 1.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 32       | 43.84%  |
| 1366x768 (WXGA)  | 8        | 10.96%  |
| 1280x1024 (SXGA) | 8        | 10.96%  |
| 3840x2160 (4K)   | 7        | 9.59%   |
| 1600x900 (HD+)   | 6        | 8.22%   |
| 2560x1440 (QHD)  | 3        | 4.11%   |
| Unknown          | 3        | 4.11%   |
| 1440x900 (WXGA+) | 2        | 2.74%   |
| 3840x1080        | 1        | 1.37%   |
| 3286x1080        | 1        | 1.37%   |
| 1360x768         | 1        | 1.37%   |
| 1280x800 (WXGA)  | 1        | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 12       | 16.67%  |
| 21      | 11       | 15.28%  |
| Unknown | 10       | 13.89%  |
| 24      | 9        | 12.5%   |
| 27      | 6        | 8.33%   |
| 20      | 5        | 6.94%   |
| 18      | 5        | 6.94%   |
| 17      | 5        | 6.94%   |
| 19      | 4        | 5.56%   |
| 84      | 2        | 2.78%   |
| 42      | 1        | 1.39%   |
| 40      | 1        | 1.39%   |
| 7       | 1        | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 25       | 35.21%  |
| 401-500     | 23       | 32.39%  |
| Unknown     | 10       | 14.08%  |
| 301-350     | 4        | 5.63%   |
| 351-400     | 3        | 4.23%   |
| 1501-2000   | 2        | 2.82%   |
| 801-900     | 1        | 1.41%   |
| 601-700     | 1        | 1.41%   |
| 101-200     | 1        | 1.41%   |
| 901-1000    | 1        | 1.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 50       | 73.53%  |
| Unknown | 9        | 13.24%  |
| 5/4     | 6        | 8.82%   |
| 16/10   | 2        | 2.94%   |
| 3/2     | 1        | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 28       | 39.44%  |
| 151-200        | 12       | 16.9%   |
| Unknown        | 10       | 14.08%  |
| 141-150        | 9        | 12.68%  |
| 301-350        | 6        | 8.45%   |
| More than 1000 | 2        | 2.82%   |
| 501-1000       | 2        | 2.82%   |
| 1-40           | 1        | 1.41%   |
| 131-140        | 1        | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 43       | 61.43%  |
| 101-120 | 13       | 18.57%  |
| Unknown | 10       | 14.29%  |
| 161-240 | 2        | 2.86%   |
| 121-160 | 2        | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 61       | 81.33%  |
| 2     | 8        | 10.67%  |
| 0     | 6        | 8%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 50       | 45.87%  |
| Intel                 | 22       | 20.18%  |
| Qualcomm Atheros      | 8        | 7.34%   |
| Broadcom              | 8        | 7.34%   |
| Ralink Technology     | 7        | 6.42%   |
| ASIX Electronics      | 4        | 3.67%   |
| TP-Link               | 2        | 1.83%   |
| Ralink                | 2        | 1.83%   |
| D-Link                | 2        | 1.83%   |
| Samsung Electronics   | 1        | 0.92%   |
| MediaTek              | 1        | 0.92%   |
| ICS Advent            | 1        | 0.92%   |
| Edimax Technology     | 1        | 0.92%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45       | 37.82%  |
| Intel Ethernet Connection (7) I219-V                              | 4        | 3.36%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 2.52%   |
| Intel I210 Gigabit Network Connection                             | 3        | 2.52%   |
| ASIX AX88772A Fast Ethernet                                       | 3        | 2.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.68%   |
| Realtek 802.11ac NIC                                              | 2        | 1.68%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 1.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.68%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.68%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.68%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.68%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.68%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.68%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2        | 1.68%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2        | 1.68%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2        | 1.68%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.84%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.84%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.84%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.84%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.84%   |
| Ralink RT2070 Wireless Adapter                                    | 1        | 0.84%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.84%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 1        | 0.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 0.84%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.84%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.84%   |
| MediaTek TECNO SPARK 6 Go                                         | 1        | 0.84%   |
| Intel Wireless 7265                                               | 1        | 0.84%   |
| Intel Wireless 3165                                               | 1        | 0.84%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 0.84%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.84%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.84%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.84%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1        | 0.84%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 1        | 0.84%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1        | 0.84%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.84%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                | 1        | 0.84%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1        | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.84%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 24.24%  |
| Ralink Technology     | 7        | 21.21%  |
| Qualcomm Atheros      | 4        | 12.12%  |
| Broadcom              | 4        | 12.12%  |
| Intel                 | 3        | 9.09%   |
| TP-Link               | 2        | 6.06%   |
| Ralink                | 2        | 6.06%   |
| D-Link                | 2        | 6.06%   |
| Edimax Technology     | 1        | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                | 3        | 9.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 6.06%   |
| Realtek 802.11ac NIC                                           | 2        | 6.06%   |
| Ralink RT5370 Wireless Adapter                                 | 2        | 6.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 6.06%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2        | 6.06%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2        | 6.06%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 3.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1        | 3.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 3.03%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 3.03%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 3.03%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 3.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 3.03%   |
| Ralink RT2070 Wireless Adapter                                 | 1        | 3.03%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1        | 3.03%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 1        | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 3.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 3.03%   |
| Intel Wireless 7265                                            | 1        | 3.03%   |
| Intel Wireless 3165                                            | 1        | 3.03%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 3.03%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 3.03%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter             | 1        | 3.03%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1        | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 48       | 58.54%  |
| Intel                 | 19       | 23.17%  |
| Qualcomm Atheros      | 4        | 4.88%   |
| Broadcom              | 4        | 4.88%   |
| ASIX Electronics      | 4        | 4.88%   |
| Samsung Electronics   | 1        | 1.22%   |
| MediaTek              | 1        | 1.22%   |
| ICS Advent            | 1        | 1.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45       | 52.33%  |
| Intel Ethernet Connection (7) I219-V                              | 4        | 4.65%   |
| Intel I210 Gigabit Network Connection                             | 3        | 3.49%   |
| ASIX AX88772A Fast Ethernet                                       | 3        | 3.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 2.33%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.33%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.33%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.33%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.33%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.33%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2        | 2.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.16%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.16%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.16%   |
| MediaTek TECNO SPARK 6 Go                                         | 1        | 1.16%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.16%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.16%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.16%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.16%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.16%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1        | 1.16%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1        | 1.16%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.16%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 1.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 74       | 71.15%  |
| WiFi     | 30       | 28.85%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 55       | 70.51%  |
| WiFi     | 23       | 29.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 55       | 73.33%  |
| 2     | 16       | 21.33%  |
| 3     | 3        | 4%      |
| 0     | 1        | 1.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 76.32%  |
| Yes  | 18       | 23.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 13       | 54.17%  |
| Intel                           | 3        | 12.5%   |
| Realtek Semiconductor           | 2        | 8.33%   |
| Qualcomm Atheros Communications | 2        | 8.33%   |
| Broadcom                        | 2        | 8.33%   |
| Conwise Technology              | 1        | 4.17%   |
| Apple                           | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13       | 54.17%  |
| Realtek Bluetooth Radio                             | 2        | 8.33%   |
| Intel Bluetooth wireless interface                  | 2        | 8.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 4.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 4.17%   |
| Intel AX200 Bluetooth                               | 1        | 4.17%   |
| Conwise CW6622                                      | 1        | 4.17%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1        | 4.17%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1        | 4.17%   |
| Apple Bluetooth Host Controller                     | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 63       | 49.61%  |
| Nvidia                   | 33       | 25.98%  |
| AMD                      | 21       | 16.54%  |
| C-Media Electronics      | 4        | 3.15%   |
| Creative Labs            | 2        | 1.57%   |
| Nordic Semiconductor ASA | 1        | 0.79%   |
| JMTek                    | 1        | 0.79%   |
| GYROCOM C&C              | 1        | 0.79%   |
| Generalplus Technology   | 1        | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 8.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 6.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 5.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 4.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 4.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 4.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6        | 4.2%    |
| Intel 200 Series PCH HD Audio                                              | 5        | 3.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 3.5%    |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 2.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 2.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 2.1%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 2.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 2.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 2.1%    |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 2.1%    |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.4%    |
| Nvidia TU102 High Definition Audio Controller                              | 2        | 1.4%    |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 1.4%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.4%    |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.4%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 1.4%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.4%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.4%    |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 1.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.4%    |
| AMD FCH Azalia Controller                                                  | 2        | 1.4%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.7%    |
| Nvidia High Definition Audio Controller                                    | 1        | 0.7%    |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.7%    |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.7%    |
| Nvidia GM200 High Definition Audio                                         | 1        | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.7%    |
| Nordic Semiconductor ASA SG Control Mic                                    | 1        | 0.7%    |
| JMTek USB PnP Audio Device                                                 | 1        | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 0.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 0.7%    |
| GYROCOM C&C NuForce ÂµDAC 2 HP                                           | 1        | 0.7%    |
| Generalplus Technology IMYB 7.1 Channel                                    | 1        | 0.7%    |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                 | 1        | 0.7%    |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 0.7%    |
| C-Media Electronics USB PnP Audio Device                                   | 1        | 0.7%    |
| C-Media Electronics USB Advanced Audio Device                              | 1        | 0.7%    |
| C-Media Electronics CM6631A Audio Processor                                | 1        | 0.7%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 0.7%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 0.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 0.7%    |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1        | 0.7%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 0.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 0.7%    |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 0.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 0.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 10       | 22.22%  |
| Corsair             | 9        | 20%     |
| Unknown             | 6        | 13.33%  |
| SK hynix            | 4        | 8.89%   |
| Samsung Electronics | 4        | 8.89%   |
| G.Skill             | 4        | 8.89%   |
| Kingmax             | 3        | 6.67%   |
| Crucial             | 2        | 4.44%   |
| Team                | 1        | 2.22%   |
| Ramaxel Technology  | 1        | 2.22%   |
| A-DATA Technology   | 1        | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 1GB DIMM 800MT/s                        | 2        | 4.17%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s       | 2        | 4.17%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s               | 1        | 2.08%   |
| Unknown RAM Module 2048MB DIMM DDR2 200MT/s                | 1        | 2.08%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                 | 1        | 2.08%   |
| Unknown RAM BAPC08G3000D4T8 8192MB DIMM DDR4 2133MT/s      | 1        | 2.08%   |
| Team RAM TEAMGROUP-UD3-160 4096MB DIMM DDR3 1333MT/s       | 1        | 2.08%   |
| SK hynix RAM SNOAMOO Ltd:016M00 4096MB DIMM DDR3 1600MT/s  | 1        | 2.08%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s        | 1        | 2.08%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s       | 1        | 2.08%   |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB DIMM DDR3 1600MT/s    | 1        | 2.08%   |
| Samsung RAM M393B2K70CM0-YF8 16384MB DIMM DDR3 1067MT/s    | 1        | 2.08%   |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1600MT/s           | 1        | 2.08%   |
| Samsung RAM M393A2K40BB1-CRC 16GB DIMM DDR4 2400MT/s       | 1        | 2.08%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s        | 1        | 2.08%   |
| Ramaxel RAM RMR5040MM58F9F1600 4096MB DIMM DDR3 1600MT/s   | 1        | 2.08%   |
| Kingston RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 2.08%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 2.08%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 1        | 2.08%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s          | 1        | 2.08%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s        | 1        | 2.08%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s      | 1        | 2.08%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 2.08%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 2.08%   |
| Kingston RAM 9965525-139.A00LF 8192MB DIMM DDR3 1600MT/s   | 1        | 2.08%   |
| Kingston RAM 9965413-002.A00LF 4096MB DIMM DDR3 1333MT/s   | 1        | 2.08%   |
| Kingston RAM 9905712-008.A00G 16GB SODIMM DDR4 2400MT/s    | 1        | 2.08%   |
| Kingmax RAM GLAH22F-18--------- 16384MB DIMM DDR4 2666MT/s | 1        | 2.08%   |
| Kingmax RAM FLGF65F-D8KM 4GB DIMM DDR3 1333MT/s            | 1        | 2.08%   |
| Kingmax RAM FLFF65F-C8KL 4GB DIMM DDR3 1333MT/s            | 1        | 2.08%   |
| Kingmax RAM FLFF65F-C6NG9 4GB DIMM DDR3 1333MT/s           | 1        | 2.08%   |
| G.Skill RAM F4-3000C15-8GTZB 8GB DIMM DDR4 3007MT/s        | 1        | 2.08%   |
| G.Skill RAM F4-2800C17-8GIS 8192MB DIMM DDR4 2800MT/s      | 1        | 2.08%   |
| G.Skill RAM F4-2400C15-8GIS 8192MB DIMM DDR4 2400MT/s      | 1        | 2.08%   |
| G.Skill RAM F4-2400C15-16GVR 16GB DIMM DDR4 2400MT/s       | 1        | 2.08%   |
| G.Skill RAM F3-12800CL9-4GBSR 4GB DIMM DDR3 1600MT/s       | 1        | 2.08%   |
| Crucial RAM CT51264BF160B.C16F 4GB DIMM DDR3 1600MT/s      | 1        | 2.08%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s     | 1        | 2.08%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 800MT/s        | 1        | 2.08%   |
| Corsair RAM CMZ4GX3M1A1600C9 4096MB DIMM DDR3 1600MT/s     | 1        | 2.08%   |
| Corsair RAM CMX4GX3M1A1600C11 4GB DIMM DDR3 1600MT/s       | 1        | 2.08%   |
| Corsair RAM CMT16GX4M2C3200C16 8192MB DIMM DDR4 3200MT/s   | 1        | 2.08%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s       | 1        | 2.08%   |
| Corsair RAM CMK16GX4M2A2400C14 8GB DIMM DDR4 2800MT/s      | 1        | 2.08%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM 3000MT/s           | 1        | 2.08%   |
| A-DATA RAM DDR4 2666 2OZ 8GB DIMM DDR4 2667MT/s            | 1        | 2.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 19       | 46.34%  |
| DDR4    | 17       | 41.46%  |
| DDR2    | 2        | 4.88%   |
| Unknown | 2        | 4.88%   |
| DDR     | 1        | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 40       | 97.56%  |
| SODIMM | 1        | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 39.53%  |
| 4096  | 13       | 30.23%  |
| 16384 | 7        | 16.28%  |
| 1024  | 4        | 9.3%    |
| 2048  | 2        | 4.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 14       | 29.79%  |
| 2400  | 6        | 12.77%  |
| 1333  | 6        | 12.77%  |
| 3000  | 3        | 6.38%   |
| 800   | 3        | 6.38%   |
| 3200  | 2        | 4.26%   |
| 2800  | 2        | 4.26%   |
| 3466  | 1        | 2.13%   |
| 3334  | 1        | 2.13%   |
| 3007  | 1        | 2.13%   |
| 2667  | 1        | 2.13%   |
| 2666  | 1        | 2.13%   |
| 2133  | 1        | 2.13%   |
| 1867  | 1        | 2.13%   |
| 1866  | 1        | 2.13%   |
| 1067  | 1        | 2.13%   |
| 200   | 1        | 2.13%   |
| 133   | 1        | 2.13%   |

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
| Logitech                        | 4        | 57.14%  |
| KYE Systems (Mouse Systems)     | 1        | 14.29%  |
| Intel                           | 1        | 14.29%  |
| IDS Imaging Development Systems | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 3        | 42.86%  |
| Logitech Webcam C310                           | 1        | 14.29%  |
| KYE Systems (Mouse Systems) Genius Webcam      | 1        | 14.29%  |
| Intel RealSense Depth Camera 435               | 1        | 14.29%  |
| IDS Imaging Development Systems USB 3.0 Camera | 1        | 14.29%  |

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
| 0     | 68       | 90.67%  |
| 1     | 6        | 8%      |
| 2     | 1        | 1.33%   |

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

